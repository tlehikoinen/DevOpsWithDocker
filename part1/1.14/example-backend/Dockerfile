FROM golang:1.16-alpine
WORKDIR /app
COPY . .

RUN apk add --update alpine-sdk

EXPOSE 8000

ENV PORT=8000
ENV REQUEST_ORIGIN=http://localhost:5000

RUN go build
RUN go test

CMD ./server
