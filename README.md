# standalone_nginx_conatiner
Nginx docker container with customized configuration to be used in dockers' private network 

How to start container to serve gunicorn app:

docker run --network=artnet --name ng -d -p 9999:80 ng
