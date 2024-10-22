FROM almalinux:9
EXPOSE 80
LABEL author=Amar \
      project=expense \
ENV Name="Amar" \
    Environment="Dev"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
  