FROM almalinux:9
LABEL author="vignesh" comp="triniti" \
    description="From file"
RUN dnf install nginx -y
EXPOSE 8080
CMD [ "nginx","-g","daemon off;"]