ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG course=docker
ARG trainer=siva
ARG duration=10hrs
ENV duration=${duration}
RUN echo "course is ${course}, trainer is ${trainer}, duration is ${duration}"
CMD ["sleep", "100"]