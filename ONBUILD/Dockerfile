FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /user/share/nginx/index.html
CMD ["nginx","-g","daemon off;"]