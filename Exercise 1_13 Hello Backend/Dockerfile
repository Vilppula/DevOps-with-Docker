FROM golang:1.16

EXPOSE 8080

WORKDIR /app

ADD . /app

RUN go build

ENV REQUEST_ORIGIN http://localhost

CMD ["./server"]
