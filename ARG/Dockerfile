ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG course=docker
ARG trainer=siva
RUN echo "course is ${course}, trainer is ${trainer}"
CMD ["sleep", "100"]