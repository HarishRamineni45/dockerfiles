FROM almalinux:9
RUN dnf install nginx -y 

# root access is not recommended in docker containers, so we will create a new user and switch to that user
RUN useradd roboshop

#switch to the new user
USER roboshop
CMD ["sleep","100"]
