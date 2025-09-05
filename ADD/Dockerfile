FROM almalinux:9.6
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/chaithanyareddy0891/dockerfiles/blob/main/README.md /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]