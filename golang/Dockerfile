# Dockerfile References: https://docs.docker.com/engine/reference/builder/
FROM golang:1.14
WORKDIR /go/src/app
COPY main.go .
RUN go get -d -v ./...
RUN go install -v ./...
RUN go build -o main .
CMD ["./main"]