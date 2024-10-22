FROM almalinux:9
EXPOSE 80
LABEL author=Amar \
      project=expense 
ENV name=Amar environment=Dev
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
  