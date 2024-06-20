ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
#ENV DURATION=120hrs
ARG DURATION=120hrs
ENV Duration = ${DURATION}
RUN echo "Course is ${COURSE} and Duration is ${DURATION}"
CMD [ "sleep", "100" ]
