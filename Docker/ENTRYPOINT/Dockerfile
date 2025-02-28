FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 8090
ENTRYPOINT ["nginx", "-g", "daemon off;"]