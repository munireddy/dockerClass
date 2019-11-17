
How to use this code:

Step 1: Clone the repo.

Step 2: cd dockerClass/nginxDocker

Step 3: To build the docker image :  sudo docker build -t <munireddy1<your reponame>>/nginx:latest  .
  
Step 4: To run the image : sudo docker run -p 80:80 -p 8080:8080 <munireddy1<your reponame>>/nginx:latest
  
once the docker container is running , you will be able to verify two differnt html pages servered for 80 and 8080 ports.
