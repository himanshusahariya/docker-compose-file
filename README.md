# docker-compose file
## Description
This file contains the code to compose three containers(mysql,wordpress,adminer).This contains **WordPress** , which is a free and open source blogging tool and a **content management system (CMS)** based on PHP and MySQL, which runs on a web hosting service. **Mysql** is also used to store data. MySQL is the world's most popular **open source database**.And last but not least, I have used **adminer**. Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP.
## Purpose of creating this compose file:
Basically, In today's world, people like every work to be done easily. And simply this was the central idea for me to create this compose file. So, the question is why this file ? 
    And, the answer is that by command line this is very hard and lengthy process to manage our database for the people who don't
have the enough knowledge about databases. So, the answer for this problem is adminer, which provides graphical way to manipulate our databases. Thus making communication with databases easy for newbies.
    I have used wordpress here to use the database and store the data here. Wordpress is a content management tool or blogging tool. So, whatever data is created there is stored in these databases. And here comes the use of Adminer. It here is used to manipulate the stored data, databases and tables etc.
### Starting the compose containers

#### Pre-requisites for starting docker-compose file:-

1. You should have installed docker on your system.
1. The httpd services of your system must be running.
1. You shoud have the following images for docker downloaded in docker:
    1. Mysql:5.7
    1. Wordpress:5.1.1-php7.3-apache
    1. Adminer:latest
1. To download these images you can run the command **docker pull IMAGE_NAME**.
1. You should have stable internet connection to communicate with containers using browser.

#### Running the compose file containers:-
1. To run the code put the code in a seperate directory where no other compose file exists. 
1. Then to run code and create the containers go to the directory which contains the compose file
1. Run the command **"docker-compose up"**.

#### You are all set to go now but before that use given info :
1. Default user = **himanshu**
1. Password for the default user = **qwertyuiop**  
1. Root password = **qwertyuiop**
1. Name of the database used = **mydatabase**
1. Name of the Mysql container = **dbos**

**Note :** *These environment variables can be altered by committing changes to the provided code.*

### How to access the containers:-
1. If u want to open wordpress:
    1. Go to the web browser and search for **"host_ip:8080"** in search bar.
    1. It will forward you to the wordpress and now you can use that wordpress container in whatever way you want.
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

### contact details:

##### Gmail :  labhanshusahariya@gmail.com
##### Linkedin : www.linkedin.com/in/himanshu-sahariya-926513198
##### GitHub : https://github.com/himanshusahariya


## #VimalDaga #IIEC_RISE #Docker #RightToEducation #RightEducation

