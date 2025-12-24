FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.geeksforgeeks.org/devops/introduction-to-docker/ /usr/share/nginx/html/index.html
CMD ["nginx", "-g" "daemon off;"]