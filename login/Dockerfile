# Use official Nginx image as base
FROM nginx:alpine

# Copy our HTML file into Nginx web root
COPY login.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]
