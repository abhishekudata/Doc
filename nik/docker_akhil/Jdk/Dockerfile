FROM openjdk
COPY . /usr/src/myapp
VOLUME .:/usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac Main.java
CMD ["java","Main"]
