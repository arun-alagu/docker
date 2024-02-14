# Use the Nginx base image
FROM nginx:latest

# Copy custom configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy HTML file to the default Nginx public folder
COPY index.html /usr/share/nginx/html/

# Copy CSS file to the default Nginx public folder
COPY style.css /usr/share/nginx/html/

# Expose port 80
EXPOSE 80