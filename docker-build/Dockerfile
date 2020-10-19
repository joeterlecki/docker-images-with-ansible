FROM nginx:latest

# Default Nginx static file location
# Idealy, we would edit the nginx.conf for new configuration
WORKDIR /usr/share/nginx/html

# Add all local static files to image working directory
ADD ./ ./

# If there was a lot of ADD COPY and RUN Steps,  Bash script file is common practice
# To bootstrap the image without additional layers
# RUN /bootstrap.sh

# Self explanitory
EXPOSE 8080