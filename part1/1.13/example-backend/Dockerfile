FROM golang:1.16-alpine
WORKDIR /app
COPY . .

RUN apk add --update alpine-sdk

EXPOSE 8080

#using defaults
#ENV PORT=8080
#ENV REQUEST_ORIGIN=https://example.com

RUN go build
RUN go test

CMD ./server
