
# Mailhog - Docker Compose

Your local smtp server using docker container.

  

    $ git clone git@github.com:tiks-vincent-delafuente/mailhog-docker-compose.git mailhog
    $ cd mailhog
    $ sudo docker-compose up -d

  

In your laravel application .env

    MAIL_DRIVER=smtp
    
    MAIL_HOST=<your-ip-address>
    
    MAIL_PORT=1025
    
    MAIL_USERNAME=null
    
    MAIL_PASSWORD=null
    
    MAIL_ENCRYPTION=null

  

To view your mail

  

    <your-ip-address or localhost>:8025

 
Done.

