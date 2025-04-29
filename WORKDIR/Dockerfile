FROM almalinux:9
RUN mkdir /app
#setup the pwd #you can't user RUN cd /app instead you can use WORKDIR /app
WORKDIR /app
RUN pwd
CMD ["sleep", "100"]
#WORKDIR instruction is used for changing the directory in dockerfile