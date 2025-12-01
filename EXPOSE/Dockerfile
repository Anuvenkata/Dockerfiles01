FROM almalinux:9
RUN dnf install nginx -y
RUN dnf install -y iputils
RUN rm -rf index.html /usr/share/nginx/index.html
COPY index.html /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80