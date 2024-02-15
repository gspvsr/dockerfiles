FROM almalinux:8

# Install nginx
RUN yum install nginx -y
RUN rm -rf /usr/share/html/index.html
# Create a simple HTML file
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html
# Start nginx with daemon off
ENTRYPOINT ["nginx", "-g", "daemon off;"]

