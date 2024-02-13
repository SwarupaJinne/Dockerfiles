FROM almalinux:8
RUN yum update -y 
RUN yum install nginx -y
ADD apache-tomcat-9.0.73-embed.tar.gz /tmp/F


# ADD can dowload directly from internet and untar the ta files where as COPY sets path from local to image(ec2-instance)