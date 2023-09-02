#docker push patchigolladurgesh/b55-images:tagname to push into the docker repository

FYI
b55-images=Repository name
patchigolladurgesh=UserName of the docker hub to login

Using the below command we can build the docker image from our repository

Example : Kubernetes1/docker-imaging ]$ docker build -t docker.io/patchigolladurgesh/samples:v1 .

V1=tag name we created to identify the version 
. = As the Image is on the PWD 


docker push patchigolladurgesh/samples:v1  >to push the image to the repostory 
to do that you need to login 
#docker login

> In interview if any one asked how you run  container with which ID 
ANS: as per the org standards we will run using the syste accouts