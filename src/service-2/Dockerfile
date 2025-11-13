# Use a minimal base image with an HTTP server
FROM nginx:stable-alpine3.21-perl

# Copy static HTML file to the default nginx public directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start nginx server
CMD ["nginx", "-g", "daemon off;"]