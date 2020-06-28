FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-bionic
MAINTAINER ddrsql@hotmail.com

RUN apt-get update \
    && apt-get install -y --allow-unauthenticated \
        libc6-dev \
        libgdiplus \
        libx11-dev \
     && rm -rf /var/lib/apt/lists/*