FROM almalinux:9
#installing nginx package
RUN dnf install nginx -y
#running nginx for infinite times in order to run the container suceessfully
CMD ["nginx","-g","daemon off;"]
#CMD is similar to $ systemctl start nginx
#Note:
    #remember whenever you are using CMD instruction in Dockerfile make sure to run a instruction for infinite number of times, in order to run container successfully.