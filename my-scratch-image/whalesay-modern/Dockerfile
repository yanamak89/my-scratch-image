FROM debian:bullseye-slim

RUN apt-get update && \
    apt-get install -y cowsay && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["/usr/games/cowsay"]

