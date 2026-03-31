FROM golang:1.25

WORKDIR /app

COPY main.go . 

RUN go build -o server main.go

CMD ["./server"]
