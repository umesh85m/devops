# Use Ubuntu as base image
FROM ubuntu:22

# Update packages and install Apache2
RUN apt-get update && \
    apt-get install -y apache2 && \

# Copy a sample HTML file (optional)
COPY index.html /var/www/html/index.html

# Start Apache2 in foreground when container runs
CMD ["apache2ctl", "-D", "FOREGROUND"]