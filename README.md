# commands for deploy with docker :

docker build -t node_deploy:1.0.0 .
docker run -p 3000:8000 node_deploy:1.0.0