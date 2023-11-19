# Day-24

## Docker Commands 

1. Check docker is installed or not
	`sudo systemctl status docker`

	OR

	`sudo docker --version`

2. Install docker
	`sudo apt install docker.io`

3. Remove or un-install docker
	`sudo apt remove docker.io`

	OR 
	
	`sudo apt purge docker.io`

4. CHeck status of docker
	`sudo systemctl status docker`

5. List all the containers
	`sudo docker ps`
	
	OR

	`sudo docker ps -a`

6. Give docker permission to user
	`sudo usermod -aG docker <username>`

7. Pull the mysql image from DockerHub
	`sudo docker pull mysql`

	OR 

	`sudo docker pull <app-name>`

8. List all the images
	`sudo docker images`

9. Create container from images
	`sudo docker run -d -e <ENV-NAME=VALUE> <image-name>:<tag-name>`

10. Kill containers
	`sudo docker kill <CONTAINER-ID>`

11. Rename container name
	`sudo docker rename <old-name> <new-name>`

12. Copy/rename image tag
	`sudo docker tag <old-name> <new-name>`

13. Steaps to create basic Dockerfile
	* Get the base image using FROM
	* Create a Working Directory within container using WORKDIR
	* Copy the code/files from Local to inside container using COPY
	* Assign RUN Command to install addition librabries using RUN
	* Finally give the command to run entry file using CMD

	example
	
	FROM python3
	WORKDIR /app 
	COPY . /app
	RUN pip install flask
	CMD ["python3", "main.py"]
