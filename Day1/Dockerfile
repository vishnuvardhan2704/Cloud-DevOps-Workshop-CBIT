# Use official nginx image
FROM nginx:alpine

# Set working directory in the container
WORKDIR /usr/share/nginx/html

# Remove default Nginx index page
RUN rm -rf ./*

# Copy static files into the container
COPY index.html .
COPY style.css .

# Expose port 80
EXPOSE 80

# Nginx starts automatically on container start
