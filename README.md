

# Technology used
  Docker
  
  Maven
  
  Nginx

# How to run locally
  git clone 
  ./mvnw package
  java -jar target/*.jar

# Steps followed

  Install & configure Jenkins
  Install Java & Jdk
  Install docker
  Create a pipeline project
  Configure essential plugins 
  write the pipeline using groovy sandbox
    include git checkout
    include maven compile, test, package steps
    include docker build, tag, push, deploy
  Build the pipeline
  install nginx
  configure nginx reverse proxy
  
  
  
