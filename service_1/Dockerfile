FROM golang:1.24-alpine

WORKDIR /app
COPY . .
RUN go build -o service1
CMD ["./service1"]