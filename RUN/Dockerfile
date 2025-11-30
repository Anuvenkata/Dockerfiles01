FROM almalinux:9
RUN dnf install nginx -y
RUN dnf install -y iputils
CMD ["nginx", "-g", "daemon off;"]