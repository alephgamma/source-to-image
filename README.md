# Simple repo for S2I deployments

## 1. http-helloworld

Simple index.html

## 2. nginx-helloworld

Simple webpage served from nginx

* But it requires changes from port 80->8080 in /etc/nginx/nginx.conf using a Dockerfile
* Without a Dockerfile there's an message: "error: No language matched the source repository"

## 3. php-helloworld

Simple index.php
