# create an image
docker build -t hello-world-docker-image .

# run a docker container
docker run -p 8080:8080 --name testor -it hello-world-docker-image

# access localhost:8080
