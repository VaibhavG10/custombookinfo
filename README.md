# custombookinfo
Create custom code from available sample code from https://istio.io/docs/examples/bookinfo/

### Build Java Code using gradle docker container
docker run --user root --rm -v "$(pwd)":/home/gradle/project -w /home/gradle/project gradle:4.8.1 gradle clean build
