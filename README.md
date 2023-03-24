# setup_wordpress_docker-compose

## marche à suivre (pour inté sans docker)

 - pull this repo
 - write .env file
 - suppr .git & .gitignore
 - create repo in wordpress/wp-content/theme/your_working_theme
 - first start: `sudo docker-compose up --build`
 - for access to phpmyadmin: root, DB_PASS_ROOT (in .env file)

## feture 2023

 - [X] add phpMyAdmin service
 - [ ] add wp-cli service ?
