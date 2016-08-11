# Set nginx base image
FROM nginx

# Copy custom configuration file from the current directory
RUN mkdir -p /etc/nginx
WORKDIR /etc/nginx
COPY nginx.conf /etc/nginx/nginx.conf

RUN mkdir -p /etc/nginx/static
COPY static /etc/nginx/static
RUN ls -l /etc/nginx/static