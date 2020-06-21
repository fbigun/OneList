FROM debian:stable-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
        ca-certificates libssl1.1 openssl \
        && rm -rf /var/lib/apt/lists/*

COPY OneDriveUploader /usr/local/bin/
CMD ["OneDriveUploader", "--help"]
