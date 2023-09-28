
# Classroom Docker image
The classroom docker image can be [found here](https://github.com/braingeneers/braingeneers-docker-images). Currently we pull the latest braingeneers image. 
However, if something breaks, you can change the code so that it pulls an images from the past that doesn't cause problems.
To change the docker image being used, edit the code in `.devcontainer/devcontainer.json`.
Specifically, if you want to run the original version of the homeworks (v0.0.1 of each hw repository) with absolute certainty that it will work, us the docker image, `ghcr.io/braingeneers/classroom:2023.09.28`.
