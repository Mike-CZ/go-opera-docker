FROM golang:1.18-buster

RUN go install github.com/go-delve/delve/cmd/dlv@latest

WORKDIR /var/opera

CMD ["tail", "-f", "/dev/null"]