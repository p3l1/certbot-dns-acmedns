FROM alpine

RUN apk --no-cache add \
    curl \
    bind-tools \
    python3 \
    py3-pip \
    python3-dev \
    gcc \
    libc-dev \
    libffi-dev \
    openssl-dev \
    jq

RUN pip3 install --upgrade pip

RUN pip3 install certbot