FROM centos

RUN yum install -y epel-release 
RUN yum update -y
RUN yum install -y nginx
COPY index.html /usr/share/nginx/html
COPY 8080/index.html /usr/share/nginx/html/8080/
COPY nginx.conf /etc/nginx

EXPOSE 80 8080

ENTRYPOINT ["/usr/sbin/nginx","-g","daemon off;"]
