# Install
`docker-compose build && docker-compose up`

# Structure
- Nginx config: `nginx/conf/`
- Modsecurity rules: `nginx/conf/`
- PHP config: `php-fpm/conf`
- PHP fpm unix socket: `shared/`
- App directory: `public_html/`
- Mariadb data dir: `mysql-data/`

# References
- https://www.nginx.com/blog/compiling-and-installing-modsecurity-for-open-source-nginx/
- https://www.lizettepreiss.com/setup-nginx-alpine-docker-container-modsecurity-redis/
