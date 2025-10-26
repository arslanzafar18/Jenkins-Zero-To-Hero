FROM maven:3.8.8-eclipse-temurin-17

# Install docker CLI so Jenkins can build docker images
RUN apt-get update && apt-get install -y docker.io

# Keep the container alive for Jenkins to attach
ENTRYPOINT ["tail", "-f", "/dev/null"]

