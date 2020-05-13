# docker-compose-file
## Description
This file contains the code to compose three containers(mysql,wordpress,adminer).This contains **WordPress** , which is a free and open source blogging tool and a **content management system (CMS)** based on PHP and MySQL, which runs on a web hosting service. **Mysql** is also used to store data. MySQL is the world's most popular **open source database**.And last but not least, I have used **adminer**. Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP.

### Starting the compose containers

#### Pre-requisites for starting docker-compose file:-
1. You should have installed docker on your system.
1. The httpd services of your system must be running.

#### Running the compose file containers:-
1. To run the code put the code in a seperate directory where no other compose file exists. 
1. Then to run code and create the containers go to the directory which contains the compose file
1. Run the command **"docker-compose up"**.

##### You are all set to go now.

### How to access the containers:-
1. If u want to open wordpress:
    1.Go to the web browser and search for **"host_ip:8080"** in search bar.
    1.It will forward you to the wordpress and now you can use that wordpress container in whatever way you want.
1. Also if you want to open adminer:
    1. Go to the web browser and search for **"host_ip:7070"** in search bar.
    1. It will forward you to the adminer webpage.
        1. Here you can see what tables are present in your database.
        1. Also you manipulate the database from here.

##### All the data will be automatically stored in the mysql volumes.

### Stop the containers
To stop the containers run the command **"docker-compose down"**.It will stop all the containers of compose file.

### Extras
For more information about containers visit:

1. https://hub.docker.com/_/mysql

2. https://hub.docker.com/_/wordpress

3. https://hub.docker.com/_/adminer 

