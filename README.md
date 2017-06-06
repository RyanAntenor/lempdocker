# Docker Container LEMP
    docker-compose up -d
## Nginx
 nginx/sites-available/default  
 nginx/sites-enabled/default  
 is mapped to

    nginx/default

### Log files:
    logs/nginx-access.log
    logs/nginx-error.log

## MYSQL
      MYSQL_ROOT_PASSWORD: root
      MYSQL_DATABASE: db_test
      MYSQL_USER: admin
      MYSQL_PASSWORD: admin

## PHP MyAdmin
[http://localhost:8080](http://localhost:8080)  

Access:

    MPMA_USER: admin
    PMA_PASSWORD: admin
    PMA_ARBITRARY: 1


## License

Copyright &copy; 2017 [Antenor Ryan](http://github.com/RyanAntenor). Licensed under the terms of the [MIT license](LICENSE.md).