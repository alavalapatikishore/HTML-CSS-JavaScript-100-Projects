# Use a lightweight web server as the base image
FROM nginx:alpine

# Copy the HTML, CSS, and JS files to the appropriate location in the container
COPY index.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/
COPY app.js /usr/share/nginx/html/

# Expose port 80 to allow incoming web traffic
EXPOSE 80

# Start the nginx web server when the container starts
CMD ["nginx", "-g", "daemon off;"]
