# Powerhive

This application is a RESTFul api that generates random
numbers between -1 and 1, the application also sums the
numbers generated for each request made. 

The application has been developed in java with the 
JAX-RS reference implementation Jersey.

TOOLS & DEPENDANCIES
-------------------- 

- Eclipse 4.4.2 (Luna)
- Java 1.8
- Tomcat 7.0
- JAX-RS 2.0 (with Jersey 2.11)

DEPLOYMENT.
-----------

The api should be compiled to a .war file and deployed to
the tomcat /webapps directory.

Accessing the application can be accessed by using the GET method
to this url "http://[SERVER IP]:[PORT]/Powerhive/rest/randomnumber/generate",
via a web browser or from the command prompt using curl.
