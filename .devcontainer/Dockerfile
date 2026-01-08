# FROM mcr.microsoft.com/dotnet/sdk:10.0-preview
FROM mcr.microsoft.com/devcontainers/dotnet:10.0

# Optional dev tools
RUN apt-get update && apt-get install -y \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
