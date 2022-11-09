#FROM alpine:latest
FROM busybox:latest

RUN echo "hello from " `hostname` > index.html

CMD ["busybox", "httpd", "-f", "-p", "80"]

