# Use the official Nginx image as base
FROM nginx:alpine

# Set working directory inside container
WORKDIR C:\Users\Admin\Downloads\modeling-agency-website-template\modeling-agency-website-template

# Copy your project files (HTML, CSS, JS) into Nginx web root
COPY . .

# Expose port 80
EXPOSE 8080

# Nginx runs automatically as entrypoint in base image
