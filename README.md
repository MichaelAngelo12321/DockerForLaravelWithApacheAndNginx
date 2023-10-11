# Docker with Nginx and Apache for Laravel

If you're using Docker and working with Laravel, you can utilize this Docker configuration to run your project locally on a virtual machine. This configuration provides options for both Apache and Nginx. Depending on your preference, follow these steps:

## Using Apache:
1. Obtain the following files and directory:
 - docker-compose.Apache.yml
 - DockerFile_Apache_Laravel
 - The 'docker/apache' directory
 2. Copy these files and directories to your main project directory.
 3. Rename the file 'docker-compose.Apache.yml' to 'docker-compose.yml'.
 4. If desired, you can modify the 'docker-compose.yml' file according to your project's needs.
 5. You can also configure a different database if necessary.
 6. In your terminal, execute the following commands:
 - `docker-compose build --no-cache`
 - `docker-compose up -d`
 ## Using Nginx:

 1. Obtain the following files and directory:
 - docker-compose.Nginx.yml
 - DockerFile_Laravel
 - Dockerfile_Nginx
 - The 'docker/nginx' directory
 2. Copy these files and directories to your main project directory.
 3. Rename the file 'docker-compose.Nginx.yml' to 'docker-compose.yml'.
 4. If desired, you can modify the 'docker-compose.yml' file according to your project's needs.
 5. You can also configure a different database if necessary.
 6. In your terminal, execute the following commands:
 - `docker-compose build --no-cache`
 - `docker-compose up -d`



