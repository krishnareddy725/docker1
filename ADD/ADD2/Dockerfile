FROM almalinux:8
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
RUN chmod 777 /usr/share/nginx/html/index.html
ADD https://github.com/itsfoss/text-script-files/blob/master/README.md /tmp
ADD https://getsamplefiles.com/sample-archive-files/tar/sample-1.tar /tmp
CMD ["nginx","-g","daemon off;"]

