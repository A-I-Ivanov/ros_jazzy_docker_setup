FROM ros:jazzy

RUN apt-get update && \
    apt-get install -y nano && \
    rm -rf /var/lib/apt/lists/*

ARG USERNAME=ubuntu

RUN echo "ubuntu:pwd" | chpasswd
# [Optional] Set the default user. Omit if you want to keep the default as root.
USER $USERNAME


