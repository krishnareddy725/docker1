FROM almalinux:8
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/idex.html
COPY idex.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
