App Engine application for the Udacity training course.
Products

    App Engine

Language

    Java

APIs

    Google Cloud Endpoints
    Google App Engine Maven plugin

Setup Instructions

    1.Update the value of application in appengine-web.xml to the app ID you have registered in the App Engine admin console and would like to use to host your instance of this sample.
    2.Update the values in src/main/java/com/google/devrel/training/conference/Constants.java to reflect the respective client IDs you have registered in the Developer Console.
    3.(Optional) Mark this file as unchanged as follows: $ git update-index --assume-unchanged src/main/java/com/google/devrel/training/conference/Constants.java
   4. mvn clean install
    5.Run the application with mvn appengine:devserver, and ensure it's running by visiting your local server's address (by default localhost:8080.)
   6. Get the client library with mvn appengine:endpoints_get_client_lib
    Deploy your application.

