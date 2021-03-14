web: docker build -t "ls-db:Dockerfile" . -f Dockerfile-ls-db
web: docker run --name=ls-db -p 3453:3306 -d ls-db:Dockerfile
web: mvn clean spring-boot:run
