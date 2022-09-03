# hello-springboot-application
# hello-springboot-application

to run the demo spring boot application, follow below commands.

1. open the app in vs code or in any IDE.
2. create the Docker image 
    > docker vuild -t <image_name> .
3. you can see the docker image > docker images
4. copy the image id
5. now run the docker image
    > docker run -d -p 8080:8080 -it aa295a0596d7

6. access application.
http://localhost:8080/hello



Note: 
1. stackhawk files are just for testing purpose. 
    stackhawk work same as veracode.
2. Newrelic also we have configure.