# Use nginx as the base image for serving static conten
FROM nginx:alpine

# Copy the index.html file to the nginx html directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 for web traffic
EXPOSE 80

# Command to run when the container starts
CMD ["nginx", "-g", "daemon off;"]