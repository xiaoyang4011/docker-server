FROM alpine:latest
MAINTAINER shawn 7csa.com

# install nginx
RUN apk --update add nginx

EXPOSE 80
EXPOSE 88

CMD ["nginx", "-g", "daemon off;"]
