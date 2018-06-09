Inspired from: https://github.com/nanoninja/docker-nginx-php-mysql
## How to use
- Copy environment file `.env.dist` to `.env`
- Edit parameters in the `.env` file: `NGINX_HOST`
- Choose the Nginx configuration will be use in `docker-compose.yml` file
- Make sure the ports using in the docker-compose will be free
- Run `docker-compose up -d`
## Issues
Message: `Error starting userland proxy`
OS: Windows 10
Fix: Restart Docker
Fix #2: Uncheck Fast startup option
Url: https://github.com/docker/for-win/issues/573
