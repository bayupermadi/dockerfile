Build the docker beanstalkd
$ docker build -t beanstalkd:1.10 .

Register and Run the docker container
$ docker run --name beanstalkd -d -p 11300:11300 beanstalkd:1.10

Stop the container
$ docker stop beanstalkd

Start the container
$ docker start beanstalkd

Dockerfile modified from: 
https://github.com/uretgec/docker-beanstalkd-alpine
