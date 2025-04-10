FROM mcr.microsoft.com/vscode/devcontainers/python:3.10

# Install git
RUN apt-get update && apt-get install -y git
# Add ~/.local/bin to PATH
ENV PATH="/home/vscode/.local/bin:${PATH}"