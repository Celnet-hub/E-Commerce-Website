# E-Commerce-Website

## Building the DB Container Image
docker build --build-arg POSTGRES_PASSWORD=$(cat .env) -t my-postgres-image .

## Running the Docker Container
docker run --name my-postgres-db -d -p 5432:5432 my-postgres-image