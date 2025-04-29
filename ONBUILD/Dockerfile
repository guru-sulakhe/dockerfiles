FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["sleep","60"]

#ONBUILD instruction adds to the image a instruction to be executed at a later time when the image is used as the base image for another build
# $ docker build -t onbuild:v1 .
# in the above example index.html instruction will be executed when someone are trying to building the image with onbuild:v1 as base image 