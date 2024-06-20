# I am the Author of the Image
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/index.html
ONBUILD COPY index.html /usr/share/nginx/index.html
CMD [ "nginx", "-g", "daemon off;" ]
