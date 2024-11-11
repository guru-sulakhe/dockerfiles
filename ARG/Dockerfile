ARG version
FROM almalinux:${version:-9}
#RUN cat /etc/*release
#setting default values to the ARG command
ARG COURSE=Docker
ARG USER=Guru
ENV DURATION=120hrs
RUN echo "Course is: ${COURSE}, User is: ${USER}, Duration is: ${DURATION}"
#container will run for only 60 seconds
CMD ["sleep", "60"] 