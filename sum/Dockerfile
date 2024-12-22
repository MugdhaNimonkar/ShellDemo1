FROM alpine:latest
RUN apk add --no-cache bash
COPY sum.sh /sum.sh
RUN chmod +x /sum.sh
CMD ["/sum.sh"]
