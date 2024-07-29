# Base image
FROM julia:latest

ENV DEBIAN_FRONTEND=noninteractive

# Set working directory
WORKDIR /workspace

# Install required packages
RUN apt-get update && \
    apt-get install -y zsh git wget curl && \
    apt-get clean

# Install Oh My Zsh
RUN wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O - | zsh || true

# Set the default shell to zsh
RUN chsh -s $(which zsh)