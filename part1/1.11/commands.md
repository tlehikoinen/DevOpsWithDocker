git clone git@github.com:docker-hy/material-applications.git  
cd spring-example-project  
#make Dockerfile!  
docker build . -t spring && docker run -p 8080:8080 spring  
  
Success!


