FROM rust:1.42-stretch

WORKDIR /usr/src/app
COPY . .

RUN cargo install --path .

CMD ["rust-echo-server"]