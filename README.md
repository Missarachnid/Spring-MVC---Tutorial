## [Serving Web Content with Spring MVC - Tutorial](https://spring.io/guides/gs/serving-web-content/#scratch)
 This contains the code that was in the initial folder of the project, that was added to during the tutorial.


### This project builds a "Hello World" website with Spring.
*  First a home page opens with a link to the greeting page
*  You can add the parameter to the page address "http://localhost:8080/greeting?name=User"
*  You will get a response saying "Hello, User!"
*  Gradle was used for the build


####  Issues I had during this tutorial
*  Initially I could not do a successful build when finished with the project. There was an issue where the version of Java was not recognized. I had to use brew to install Java8, and then uninstall the version I had downloaded. I found many reports of similar issues on stackoverflow and github, so a solution was not hard to find. 