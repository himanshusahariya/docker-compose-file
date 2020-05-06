# docker-compose-file
## Description
This file contains the code to compose three containers(mysql,wordpress,adminer).This contains **WordPress** , which is a free and open source blogging tool and a **content management system (CMS)** based on PHP and MySQL, which runs on a web hosting service. **Mysql** is also used to store data. MySQL is the world's most popular open source database.And last but not least, I have used **adminer**. Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP.
### Starting the compose containers
To run the code put the code in a seperate directory where no other compose file exists. Then to run code and ccccreate the containers go to the directory which contains the compose file and run the command **"docker-compose up"**.You are all set to go now.
### How to access the containers
Now if u want to run wordpress,go to the web browser and search for **"host_ip:8080"**. It will forward you to the wordpress and now you are ready to go.

Also if you want to run adminer, go to the web browser and search for **"host_ip:7070"**. It will forward you to the adminer webpage.

All the data will be automatically stored in the mysql volumes.
### Stop the containers
To stop the containers run the command **"docker-compose down"**.It will stop all the containers of compose file.
### Extras
For more information about containers visit:

1. https://hub.docker.com/_/mysql

2. https://hub.docker.com/_/wordpress

3. https://hub.docker.com/_/adminer 

