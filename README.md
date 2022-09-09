# docker-maven
link: https://github.com/carlossg/docker-maven

* [3.8.6-openjdk-14](https://github.com/shshdxk/docker-maven/blob/main/maven-jdk-14/Dockerfile)

# How to use this image
## Linux
```shell
docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.8.6-jdk-14 mvn verify
```
