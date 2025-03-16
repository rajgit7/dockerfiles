FROM almalinux:9
RUN mkdir /tmp/docker
#here cd is not able so we need to put workdir
WORKDIR /tmp/docker 
RUN pwd
RUN echo "Hello" > hello.txt
CMD ["sleep", "100"]