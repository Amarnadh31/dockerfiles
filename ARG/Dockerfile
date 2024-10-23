ARG version
FROM almalinux:${version:-9}
ARG NAME=Ramesh \
    COURSE=DevOps
ENV BROKER=$NAME \
    DUTY=$COURSE
RUN echo "my name is $NAME, I have taken $COURSE training"
CMD ["sleep", "100"]