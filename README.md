# Docker_commands

sudo yum update -y

sudo yum install docker -y

docker --version

sudo su/sudo -i

systemctl enable docker -if we enable service if we stopping instance also we start instance- automatically service also gets started if not enable service whenever restarting instance again need to start the service.

systemctl start docker

systemctl status docker

To create container and give name:
docker run -it --name cont_name ubuntu /bin/bash.

difference between base image and changes on it then
docker diff cont_name

To create image from container.
docker commit <container_name_or_id> <new_image_name>:<tag>.

.

