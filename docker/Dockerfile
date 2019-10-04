FROM rust:latest
RUN useradd -m rust
COPY config /config
COPY scripts /scripts
RUN chmod +x scripts/*
RUN apt update && apt install -y \
    jupyter-notebook \
    cmake
RUN cargo install evcxr_jupyter
USER 1000:1000
RUN evcxr_jupyter --install
