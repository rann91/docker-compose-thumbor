Custom Docker Compose template for [Thumbor](http://thumbor.org/).
This template is meant to be used with [nginx-proxy](https://github.com/jwilder/nginx-proxy). Use [this template](https://github.com/rann91/docker-compose-nginx-proxy) to setup nginx proxy quickly.

## Usage
Copy default .env file and configure variables. Then simply run docker-compose:
```
docker-compose up -d
```

To enable HTTPS, run the following command:
```
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
```

That's it!
 