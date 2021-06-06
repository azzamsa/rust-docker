ARG BASE_IMAGE=rust:1.52.1-slim-buster

FROM $BASE_IMAGE
WORKDIR app
COPY . .
RUN cargo build --release
CMD ["./target/release/hello"]
