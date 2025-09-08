# Use official Nginx image
FROM nginx:alpine

# Set working directory inside container
WORKDIR /usr/share/nginx/html

# Remove default Nginx static files
RUN rm -rf ./*

# Copy your project files (HTML, CSS, JS, images, libs) into container
COPY . .

# Expose port 80
EXPOSE 8000

# Nginx starts automatically with the base image
