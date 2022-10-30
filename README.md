# cbwa_ca1
CA1. Student: Anastasiia Dumanitskaia. 2022067

Note: the repositiry has to be downloaded first

### To built the image:

Swich the working directory to within the CA folder

Run command:

docker build -t cbwa_ca1 .

### To run the image:

docker run -it --rm -p 8080:8080 cbwa_ca1

### To see the image:

Browse to http://localhost:8080

#
# Referenses:
https://github.com/lipanski/docker-static-website

https://hub.docker.com/_/alpine
