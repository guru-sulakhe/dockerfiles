FROM almalinux:9
RUN adduser expense
USER expense
CMD ["sleep", "100"]

#USER instruction is used to provide non-root access to the dockerimage for security purpose
#USER instruction will change root user access to non-root access i.,e only expense USER can access the dockerimage