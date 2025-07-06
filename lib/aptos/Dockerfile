FROM rust:1.81-slim

LABEL vendor="SecDim/OtterSec/AptosLabs" \
    copyright="Security Dimension Pty Ltd. & OtterSec. & Aptos Labs. All rights reserved" \
    description="SecDim Aptos CTF Challenge" \
    version="1.0.0"

ENV APP_HOME /app
ENV PORT 31337

WORKDIR ${APP_HOME}
COPY src src

EXPOSE ${PORT}

ENTRYPOINT ["./src/run-server.sh"] 