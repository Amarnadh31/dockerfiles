FROM almalinux:9
EXPOSE 80
LABEL author=Amar \
      project=expense
ENV environment=dev project=expense
RUN dnf install nginx -y
COPY ../docker.sh /tmp
  