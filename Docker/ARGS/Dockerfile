ARG version="9"
FROM almalinux:${version}
RUN dnf install nginx -y
ENV OSvesion=${version}
CMD ["nginx", "-g", "daemon off;"]