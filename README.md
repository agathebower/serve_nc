# serve_nc
Python script that holds binary-data for netcat! And a ducky script that downloads and starts this! ;)

### Command to start local nginx server to serve this..
docker container run --name serve_nc -v /root/serve_nc:/usr/share/nginx/html -p83:80 -d nginx
