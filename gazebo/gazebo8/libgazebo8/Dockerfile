# This is an auto generated Dockerfile for gazebo:libgazebo8
# generated from templates/docker_images/create_gzclient_image.Dockerfile.em
FROM gazebo:gzserver8
# install gazebo packages
RUN apt-get update && apt-get install -q -y \
    libgazebo8-dev=8.1.1-1* \
    && rm -rf /var/lib/apt/lists/*
