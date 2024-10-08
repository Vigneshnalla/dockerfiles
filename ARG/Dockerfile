ARG version=9
FROM almalinux:${version}

# Set ARG and ENV properly
ARG Duration=120hrs
ENV Duration=${Duration}

# Run command to check ENV variable during build
RUN echo "Course ${COURSE} and Duration is ${Duration}"

# Default CMD to keep the container alive
CMD [ "sleep", "100" ]
