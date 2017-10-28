# ESP-Assign2

**Overview:-**
Team Backbenchers have implemented a web application known as “Easy Twitter” which provides a user interface for Twitter REST API’s. The user can use the application to perform various tasks like search tweets by a phrase, search tweets by geographical location, post tweets.

The project was build in Eclipse Oxygen Release (4.7.0) and was compiled using Apache Maven 3.5. Software details are as follows:
1. Java 1.8.0_144
2. Angular JS 1.6.6
3. Bootstrap 3.3.7
4. Apache Camel 2.19.3
5. Apache Karaf 4.0.10

**Installation steps**
1. Pull the code from Git repository and import it as a maven project in Eclipse
2. Build the project from eclipse or use following command in command prompt - mvn clean install
3. Install Karaf and start karaf using karaf.bat

   In karaf console execute following commands:
   
   feature:repo-add camel 2.19.3
   
   feature:install camel-blueprint
   
   feature:install camel-twitter
   
   feature:install camel-websocket
   
   install -s mvn:org.apache.camel/twitter-camel

4. Open following link in web-browser to navigate through the application. http://localhost:9090/ 
