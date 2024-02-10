FROM almalinux
RUN yum update -y 
RUN yum install nginx -y
ADD apache-tomcat-9.0.73-embed.tar.gz /tmp/ROM/almalinux
RUN yum install nginx -y
CMD ["nginx", "-g", "daemon off;"]
# CMD ["sleep", "20"] there should be only one CMD instruction. if we give multiple the last one will be considered 