FROM ubuntu:latest

#set working directory in the image
WORKDIR /app

#copy the files from the host file system to the image file system
COPY . /app

#Install all the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

#set Enviornment varibales
ENV NAME world

#RUn a command to start the applications
CMD ["python3","app.py"] 
