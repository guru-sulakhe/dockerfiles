ARG version
FROM almalinux:${version:-9}
#RUN cat /etc/*release
#setting default values to the ARG command
ARG COURSE=Docker
ARG USER=Guru
ARG DURATION=120hrs
ENV DURATION=${DURATION}
RUN echo "Course is: ${COURSE}, User is: ${USER}, Duration is: ${DURATION}"
#container will run for only 60 seconds
CMD ["sleep", "60"] 

#ARG DURATION=${DURATION}, this will be executed only when during the image building, i.,e $ docker build -t arg:1.0 --build-arg version=8