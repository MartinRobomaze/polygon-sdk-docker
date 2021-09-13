FROM golang

ARG DATA_DIR
ENV DATA_DIR=${DATA_DIR:-data-dir}

WORKDIR /polygon-sdk

RUN git clone https://github.com/0xPolygon/polygon-sdk.git .

RUN go run main.go ibft init --data-dir DATA_DIR
