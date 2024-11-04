# Start with the official Nginx image
FROM nginx:latest

# Copy static files or configurations (optional)
# Uncomment the line below if you have files to serve or specific configurations
# COPY ./your-content /usr/share/nginx/html

COPY /app /usr/share/nginx/html

# Expose port 80 to allow web traffic
EXPOSE 80

# The official Nginx image automatically starts the Nginx server, 
# so no additional CMD is required.
