
server {
    listen 80;
    server_name johnny-dev.pp.ua  www.johnny-dev.pp.ua;
    return 301 https://johnny-dev.pp.ua$request_uri;
}

server {
         listen 443 ssl default_server;
         server_name johnny-dev.pp.ua;

        location /.well-known/acme-challenge {
                root /var/www/website;

        }
        location / {
                proxy_pass http://localhost:8080;
        }
}





