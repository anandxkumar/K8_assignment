FROM golang:1.16-alpine

# Set destination for COPY
WORKDIR /app

COPY go.mod .
COPY go.sum .
RUN go mod download

COPY *.go ./

# Build
RUN go build -o /docker-gs-ping

EXPOSE 8090

# Run
CMD [ "/docker-gs-ping" ]
