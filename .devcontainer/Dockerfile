FROM mcr.microsoft.com/devcontainers/rust:0-1-bullseye

                            # for hot-reload
RUN cargo install dioxus-cli wasm-pack cargo-watch \
    && rustup target add wasm32-unknown-unknown