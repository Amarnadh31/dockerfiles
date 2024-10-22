FROM almalinux:9
LABEL author=Amar \
      project=expense \
EXPOSE 80
ENV Name="Amar" \
    Environment="Dev"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
  