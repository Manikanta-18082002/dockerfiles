# FROM almalinux:9
# RUN dnf install nginx -y
# CMD [ "nginx", "-g", "daemon off;" ]

FROM almalinux:9
RUN useradd expense
# Below changed user from root access to Expense user (Normal User)
USER expense
CMD [ "sleep", "100" ]