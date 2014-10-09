nginx-node-bower-gulp
=====================
nginx server with node bower and gulp installed

Nginx config
------------
Create Dockerfile and copy your own nginx config


    FROM jorgenfb/nginx-nodejs-bower-gulp
    COPY nginx.conf /etc/nginx/nginx.conf
