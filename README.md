# Spring Rest Demo

 In this sample code demo , how Spring can be used to pass info from the Rest- Client to Rest-Webservices using  [Jackson Databind] (https://github.com/FasterXML/jackson-databind)  which converts json to Java Pojo class for the controller and then sends the data back to Rest Client by converting Java Pojo back to json to display the data on Rest Client


### Maven Dependencies used for this demo
 - spring-webmvc   -- MVC and REST integration
 - jackson-databind -- json converter
 - javax.servlet-api -- Config Dispatcher Servlet Initializer 

### Server
   Server used is TomCat-9.0
 
### Api end-points
- /spring-rest-demo/testapi/helloapp  -- Display Hello App
- /spring-rest-demo/api/rules     --   json data displayed
These end-points can be tested on POSTMAN when Tomcat server is up and running

### General Approach
 When data needs to be handled from external source like txt file OR  property file then there is some amount of maintenace to upkeep the data. So the improvement of this process is to build the data using Rest Client and the data is consumed by the controller and the data can be sent back to the REST-Client to be used like CRUD operation (GET/POST/PATCH/DELETE)


   
   

  



















 


   
   
 
   
   
  
 
