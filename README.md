# Inventory-API
## RESTFUL WEB SERVICES:
RESTful web services are built to work best on the Web. Representational State Transfer (REST) is an architectural style that specifies constraints, such as the uniform interface, that if applied to a web service induce desirable properties, such as performance, scalability, and modifiability, that enable services to work best on the Web. In the REST architectural style, data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs), typically links on the Web. 


The PUT, GET, POST and DELETE methods are typical used in REST based architectures.T - Requests data from a specified resource

### REQUIREMENTS
JAX-RS, Jersey, MAVEN

### DEPLOYING AND RUNNING
1. Create a dynamic web project in eclipse
Adding the Required Libraries
As a second step let us add Jersey Framework and its dependencies (libraries) in our project. Copy all jars from following directories of download jersey zip folder
2. You need to create a Web xml Configuration file which is an XML file and is used to specify Jersey framework servlet for our application.
3. Once you are done with creating source and web configuration files, you are ready for this step which is compiling and running your program. To do this, using Eclipse, export your application as a war file and deploy the same in tomcat.
# DOCKER APPLICATION
The  Project is designed to load and start Cincinnati Weather Project Docker image, 
Using Docker Hub: 

Run the command `sudo docker pull mekava/forecastweather `in your local intance

After above step you can find "mekava/forecastweather" image in your docker 
Use command to check the the same below:

`sudo docker images`

Run command `sudo docker run -p 8081:80 mekava/forecastweather` to start container for above image
 

Download  weather.tar file form my google drive accessing below link
https://drive.google.com/open?id=13OrhjXN3b3qLPQhLv2jJBG5CQ3U4pjKc 
  
And then run below commands 

`sudo docker load -i weatheroutfore.tar`

`sudo docker run -p 8081:80 forecastweather`

application will be running on your local instance and ready to accept requests on 8081 port.
