FROM almalinux:9
RUN useradd amar
RUN dnf install nginx -y
USER amar
CMD ["nginx", "-g", "daemon off;"]