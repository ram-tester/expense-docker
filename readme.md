This project automated by containers using docker
expense has 3 diff components frontend,backend and database
docker compose used to run all at once and if dependency is there also you have give it manually 
follow all best practices to reduce the image size and your app should work
use docker hub to get official image and alpine os to reduce your image size
all the steps which are not frequently change place before which are not changes so that it will fetch from cache as image layering approach
always run as a non root user
