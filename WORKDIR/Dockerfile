FROM almalinux:9
RUN useradd amar
USER amar
RUN mkdir /tmp/docker
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello I'm here" > sample.txt
CMD ["sleep", "100"]