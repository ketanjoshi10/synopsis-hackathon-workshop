FROM amytabb/docker_ubuntu16_essentials
COPY HelloWorld /HelloWorld
WORKDIR /HelloWorld/
RUN g++ -o HelloWorld helloworld.cpp
COPY script.sh /HelloWorld/script.sh
EXPOSE 80
RUN ["chmod", "+x", "/HelloWorld/script.sh"]
ENTRYPOINT ["/HelloWorld/script.sh"]
