FROM almalinux:8

# Install nginx
RUN yum install nginx -y

# Create a simple HTML file
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html

RUN yum install git -y \
    && yum install maven -y \
    && yum install gcc -y
# Start nginx with daemon off
RUN echo "Hello World"
CMD ["nginx", "-g", "daemon off;"]

