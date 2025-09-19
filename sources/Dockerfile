# Sử dụng PHP với Apache
FROM php:8.2-apache

# Copy code vào container
COPY . /var/www/html/

# Cài thêm các extension nếu cần (vd: mysqli, pdo, zip)
RUN docker-php-ext-install mysqli pdo pdo_mysql zip

# Expose port 80
EXPOSE 80
