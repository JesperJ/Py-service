# What is this
Demo python webserver in docker.

On push to main repository, github workflow updates the Docker image in Docker Hub.

# Install
docker run -dp 5000:5000 --name py-service jjesper/py-service
