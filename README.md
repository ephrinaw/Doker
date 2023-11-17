# Doker
The purpose of this assignment is to get familiar with the basics of docker such as pulling an image, creating and running a container and docker hub.
## Materials
 [What is Docker?](https://docs.docker.com/get-started/overview/) <br>
[Basic Docker Commands](https://docs.docker.com/engine/reference/commandline/docker/) <br>
[Introduction to Docker (LAB)](https://www.cloudskillsboost.google/focuses/1029?catalog_rank=%7B%22rank%22%3A4%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=12490347)

### The questions and answers 

1	Docker Exercise 

1.	Playing with busy box: <br>
a.	Pull busy box image from the docker hub. 
![image](https://github.com/ephrinaw/Doker/assets/39829776/3998ec91-303d-4732-835b-4a59c371c5cb)

b.	Display list of all images on your system. Make sure that you have busy box as well. Write the image id for the buysbox image.
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/0ad30f3e-e3d7-4924-9ad9-239dcae6e1af)

Image ID 42b97d3c2ae9
c.	Run a docker container based on the busybox image
i.	Docker run busybox 
1.	Nothing happens. This is not true, a lot has happened in the background but because you did not provide a command, it ran an empty command and then exited.
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/ef1046d7-1eb0-4310-b6ca-e00d2d7b9d92)

2.	Docker run busybox echo “hello world”
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/6823bc76-a1e8-4a97-9444-f36fa220b3d6)

ii.	Check what containers are currently running.
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/a3055dcb-3c0b-4d8a-a78b-2fe81087ab19)

iii.	List all containers that exited. 
![image](https://github.com/ephrinaw/Doker/assets/39829776/da85ea76-6c4b-41e8-b9e2-675d9a1334ad)

d.	Get into the interactive terminal with the -it flag and run ubuntu. It attaches an interactive terminal in the container. You can now run multiple commands. Run some of the following commands 
1.	Get into the home folder and create a home directory for yourself. The directory name can be your own name. 
![image](https://github.com/ephrinaw/Doker/assets/39829776/66ef2f95-6bf7-4960-9965-370ce9818485)
                                            
2.	We want to use nano text editor in the ubuntu image but is not available. Lets first update
	by typing apt-get update and then install nano apt-get install nano
  ![image](https://github.com/ephrinaw/Doker/assets/39829776/b1ae12de-bb7e-47fd-9b7d-3e7177c8bd47)
  ![image](https://github.com/ephrinaw/Doker/assets/39829776/acbf0485-e834-42c8-a3f9-8cad06b26910)
                                      
                                          
3.	Get into the home folder and create a simple text file. Write a couple of lines in the text file such as your name. 
  ![image](https://github.com/ephrinaw/Doker/assets/39829776/441d88e7-d0e9-4dd5-9123-8626b6258e67)
                                      
e.	Now that we have several images. Let’s delete the busybox image. 
   ![image](https://github.com/ephrinaw/Doker/assets/39829776/63547557-38ab-490d-8cd9-6fa658341fad)
                                   
f.	Delete all containers that have a status of exited. 
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/eebf6ca3-c297-4819-b11b-a0228c683733)


2.	Cleaning Up
a.	We have containers and images that won’t be used anymore. They occupy space therefore let’s find them and delete them
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/eb82ecf3-8fde-4fbb-b3c9-9717f35c2878)

b.	Find all images 
![image](https://github.com/ephrinaw/Doker/assets/39829776/b270818a-f16f-47a2-ac7b-f274da9ae1d4)

 

c.	Delete all images and containers that you won’t need anymore. 
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/dc62a21d-d4e5-4a92-8119-fd0aa73072ff)

d.	Submit the output for docker ps -a and docker images
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/c06067ad-7ece-43a9-9cfb-457983a722a7)

3.	Create an account in Docker Hub and browse for interesting images. List some that could be useful for you. 
 ![image](https://github.com/ephrinaw/Doker/assets/39829776/c1ec3394-3827-4d97-bcf0-169af1fad65f)

Some useful images:  
	Ubuntu
	Mysql
	Maiadb
	Wordpress
	Django
	Apach 
	Tomcat
	Joomla
	Ruby on Rails

 


