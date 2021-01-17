from ubuntu:18.04

RUN apt update && apt install --no-install-recommends -y jq && rm -rf /var/lib/apt/lists/*
RUN mkdir prac1
WORKDIR /prac1
COPY large-file .
COPY PlaylistExport.json .
