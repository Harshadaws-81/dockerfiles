FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# This ONBUILD runs only when any USER uses your Image as base Image
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx" , "-g" , "daemon off;"]