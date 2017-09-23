# docker-php-ecosystem
docker php develop environment, including php,php-fpm,nginx,elasticsearch,mysql,phpmyadmin, supervisord,redis, beanstalk. And has composer, gruntjs, gulp, bower...etc

# getting start

1. clone this project

 ``` bash
 git clone https://github.com/longguojin/docker-php-ecosystem.git

```

2. feel free to edit docker-compose.yml file to fit your needs

3. run the docker-compose
 ``` bash
 docker-compose up

 ```

well done, your are ready to go !


# quick access
1. phpmyadmin
  http://localhost:8080/

2. php app
  http://localhost/

3. kibana
  http://localhost:5601/

4. for supervisord, redis, beanstalk. And has composer, gruntjs, gulp, bower...etc , you can login the php-ecosystem via docker-compose

  ``` bash

  #get the php-ecosystem container id
  docker ps

  #login the php-ecosystem container, replace [container id] with the real id
  docker-compose exec -it [container id] /bin/bash
 ```
