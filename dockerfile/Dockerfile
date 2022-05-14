FROM centos:7
LABEL maintainer="cjp2952534851@qq.com"
COPY ./nginx.repo /etc/yum.repos.d/
RUN yum makecache
RUN yum install -y nginx
RUN echo "Hello! This is 陈金坪1145 index" > /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]                                  
