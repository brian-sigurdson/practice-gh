#FROM alpine:latest
FROM busybox:latest

RUN echo "hello world" > index.html

CMD ["busybox", "httpd", "-f", "-p", "80"]

