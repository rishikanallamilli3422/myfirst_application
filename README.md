# myfirst_application
This is a simple application using node js which gives a static response of "Hello World".  

Phase-1:Steps to verify the application in local.  
To test this application in local machine all we need is to have node installed.  
step 1: Clone the repo into local.  
step 2: Change the directory to the application directory.  
step 3: run the command node app.js which is the start point of the application.  
This opens up a static web page displaying "Hello World".  

Building a docker image for this application.  
step 1: To build a docker image we create a docker file.  
step 2: Building the docker image.  
        run the commands  
        docker build -t rishika .(-t for tag name "rishika")  
 step 3:Docker run  
 step 4:docker push <user_name> /<image_name>  
        
step 1: Create an ec2 instance with free tier eligible preferably ubuntu.
step 2: clone this repo to local 
