# Use the official Nginx image from Docker Hub as the base image
FROM nginx:alpine

# Copy your custom welcome page (index.html) to the Nginx default directory
COPY ./html /usr/share/nginx/html

# Expose port 80 to allow external access to the web server
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
