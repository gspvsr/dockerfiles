ARG version
FROM almalinux:${version:-8}
# ARG variable before from will not work after from
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course: ${COURSE}, trainer is: ${TRAINER}"