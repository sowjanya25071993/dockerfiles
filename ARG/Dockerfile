ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG course
ARG trainer
RUN echo "course:${course},trainer:${trainer}"
ENV course=${course}
ENV trainer=${trainer}
CMD ["sleep","100"]