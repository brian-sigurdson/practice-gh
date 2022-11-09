#FROM alpine:latest
FROM busybox:latest

RUN echo "Hello World at " $(date) > index.html

CMD ["busybox", "httpd", "-f", "-p", "80"]

