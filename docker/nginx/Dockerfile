FROM nginx:alpine
WORKDIR "/application"



# FROM debian:jessie

# MAINTAINER NGINX Docker Maintainers "docker-maint@nginx.com"

# ENV NGINX_VERSION 1.11.9-1~jessie

# Fix debconf warnings upon build
# ARG DEBIAN_FRONTEND=noninteractive

# RUN apt-key adv --keyserver hkp://pgp.mit.edu:80 --recv-keys 573BFD6B3D8FBC641079A6ABABF5BD827BD9BF62 \
#     && echo "deb http://nginx.org/packages/mainline/debian/ jessie nginx" >> /etc/apt/sources.list \
#     && apt-get update \
#     && apt-get install --no-install-recommends --no-install-suggests -y \
#                         ca-certificates \
#                         nginx=${NGINX_VERSION} \
#     && rm -rf /var/lib/apt/lists/*

# # forward request and error logs to docker log collector
# RUN ln -sf /dev/stdout /var/log/nginx/access.log \
#     && ln -sf /dev/stderr /var/log/nginx/error.log


# EXPOSE 80 443

# CMD ["nginx", "-g", "daemon off;"]