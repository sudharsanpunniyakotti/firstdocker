DOCKER BUILD:   docker build -t my-test .
DOCKER RUN with PORT :docker run  -p 80:80 my-test
DOCKER RUN WITH VOLUME :  docker run  -p 80:80 -v /root/docker/src:/var/www/html/ my-test

