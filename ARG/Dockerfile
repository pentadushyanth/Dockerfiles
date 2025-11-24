ARG version
FROM almalinux:${version:-9}
ARG COURSE="Docker" \
    Tech="Devops"
ENV COURSE=${COURSE} #to access the args inside the container
RUN echo "Technology: ${Tech}, Course: ${COURSE}, Version: ${version}"
CMD ["sleep","1000"]