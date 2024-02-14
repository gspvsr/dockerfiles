FROM almalinux:8

# Install nginx
RUN yum install nginx -y

# Create a simple HTML file
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html

# Start nginx with daemon off
CMD ["nginx", "-g", "daemon off;"]
