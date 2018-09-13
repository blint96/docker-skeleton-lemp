Quickstart
1. Install docker https://docs.docker.com/install/
2. Install docker-compose https://docs.docker.com/compose/install/
3. Change passwords in the docker-compose.yml (default ones aren't safe enought ;))
4. Navigate to the root folder of this project
5. Run command docker-compose up -d

Links:
1. phpmyadmin will be available under url: http://yoursite.com:8181
2. nginx with php-fpm 7.2 will be available under url: http://yoursite.com (default port 80, support 443 SSL)

Troubleshoot:
If containers won't start, run command 
docker build -t php-docker .

And finally, one more time
docker-compose up -d
