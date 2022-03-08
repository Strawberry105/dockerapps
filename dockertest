FROM ubuntu:latest
LABEL maintainer="myname@abcompany.com"
RUN apt-get update && apt-get upgrade -y
RUN apt-get install nginx -y
EXPOSE 80
CMD ["NGINX", "-g", "daemon off;"]
