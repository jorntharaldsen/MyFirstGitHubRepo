FROM gcc:latest
COPY ./hello.cpp /usr/src/hello/hello.cpp
WORKDIR /usr/src/hello
RUN g++ -std=c++11 -o hello hello.cpp > out.log
CMD ["./hello"]
