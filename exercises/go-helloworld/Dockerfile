FROM golang:alpine

LABEL maintainer "Mayank Shah"

WORKDIR /go/src/app
ADD . .

RUN go build  -o helloworld

EXPOSE 6111

CMD ["./helloworld"]
