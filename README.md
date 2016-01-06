
# First Spring MVC Application in 25 Easy Steps
## Spring MVC Tutorial for Beginners

* [Running examples](#running-examples)
* [Course Overview](#course-overview)
  - Steps 1 to 7 : Build a normal Web Application
  - Steps 11 to 37 : Use Spring MVC to Build Your First Web Application
  - [Step wise details](#step-wise-details)
  - [Exercises](#exercises)
* [About in28Minutes](#about-in28minutes)
  - [Our Beliefs](#our-beliefs)
  - [Our Approach](#our-approach)
  - [Find Us](#useful-links)
  - [Other Courses](#other-courses)

##Installing Eclipse and Java
https://github.com/in28minutes/SpringIn28Minutes/blob/master/InstallationGuide-JavaEclipseAndMaven_v2.pdf

##Course Overview

You will learn about
- DispatcherServlet
- Basic Todo Management Application with Login/Logout
- Model, Controllers, ViewResolver and Filters 
- Forms - DataBinding, Validation
- Annotation based approach - @RequestParam, @PathVariable, @ModelAttribute, @SessionAttributes etc
- Bootstrap to style the page
- Spring Security
- Internationalization
- Exception Handling
- Basic REST Services

###Steps 1 to 7 - Build a normal Web Application
- Understand Basics of HTTP 
- HttpRequest - GET/POST, Request Parameters
- HTTP Response - Response Status - 404,200,500 etc
- Introduction to JSP, Servlets,  Scriptlets and EL
- HTML Form -  Method, Action & Form Data
- Understand Basics of using Maven, Tomcat and Eclipse
- Using Request Attributes for passing Model between Servlet and View

###Steps 11 to XX : Use Spring MVC to Build Your First Web Application
- Step 11 : Configure application to use Spring MVC
- Step 12 : First Spring MVC Controller, @ResponseBody, @Controller
- Step 13 : Redirect to Login JSP - LoginController, @ResponseBody and View Resolver
- Step 14 : DispatcherServlet and Log4j
- Step 15 : Show userid and password on the welcome page - ModelMap and @RequestParam 
- Step 16 : LoginService and Remove all JEE Servlets based code
- Step 17 : Spring Auto-wiring and Dependency Management - @Autowired and @Service
- Step 18 : Create TodoController and list-todos.jsp. Make TodoService a @Service and inject it.
- Step 19 : Add Todo model object. Create TodoService.
- Step 20 : Create TodoController and  list-todos.jsp
- Step 21 : Session vs Model vs Request - @SessionAttributes
- Step 22 : New Todo and redirect to a Controller
- Step 23 : JSTL
- Step 24 : Bootstrap - using Webjars
- Step 25 : Let's delete a Todo
- Step 26 : Use Bootstrap to format and add HTML5 Validations
- Step 27 : Introduce JSR 349 Validations using Hibernate Validator - First Command Bean.
- Step 28 : Let's update a Todo
- Step 29 : Let's add a Target Date for Todo - Use initBinder to Handle Date Fields
- Step 30 : Navigation bar and JSP Fragments
- Step 31 : Let's prepare for Spring Security
- Step 32 : Initial Setup for Spring Security
- Step 33 : Refactor and add Logout Functionality using Spring Security
- Step 34 : Exception Handling in Spring MVC - @ControllerAdvice, @ExceptionHandler and error-page in web.xml
- Step 35 : Let's add Internationalization - i18n
- Step 36 : Basic Spring Rest Services - @RestController and jackson-databind
- Step 37 : More Rest Services - @PathVariable

##Expectations
- For taking this course, you should already know Java. 
- We expect NO prior experience with web development using Java.
- We expect NO prior experience with Spring.

###Running Examples
- If you are downloading the zip file, unzip the file
- Open Command Prompt and Change directory to folder containing pom.xml
- Run command "mvn tomcat7:run"
- For help : user our installation guide - https://github.com/in28minutes/SpringIn28Minutes/blob/master/InstallationGuide-JavaEclipseAndMaven_v2.pdf


##Step wise details
- Step01.md : Up and running with a web app in Tomcat
- Step02.md :	First JSP
- Step03.md :	Adding a GET Parameter name
- Step04.md :	Adding another Get Parameter Password
- Step05.md : Lets add a form
- Step06.md :	New Form and doPost
- Step07.md :	Adding Password, validation of userid/password

##Exercises
- Split TodoController into different Controllers
- Use same TodoController for both updates and new todo
- Functionality to mark a Todo as complete

##Future Things To Do
- Unit Tests - WTF - why are they not here in the first set?

##About in28Minutes
- At in28Minutes, we ask ourselves one question everyday. How do we create more effective trainings?
- We use Problem-Solution based Step-By-Step Hands-on Approach With Practical, Real World Application Examples. 
- Our success on Udemy and Youtube (2 Million Views & 12K Subscribers) speaks volumes about the success of our approach.
- While our primary expertise is on Development, Design & Architecture Java & Related Frameworks (Spring, Struts, Hibernate) we are expanding into the front-end world (Bootstrap, JQuery, Angular JS). 

###Our Beliefs
- Best Course are interactive and fun.
- Foundations for building high quality applications are best laid down while learning.

###Our Approach
- Problem Solution based Step by Step Hands-on Learning
- Practical, Real World Application Examples.
- We use 80-20 Rule. We discuss 20% things used 80% of time in depth. We touch upon other things briefly equipping you with enough knowledge to find out more on your own. 
- We will be developing a demo application in the course, which could be reused in your projects, saving hours of your effort.
- All the code is available on Github, for most steps.

###Useful Links
- [Our Website](http://www.in28minutes.com)
- [Youtube Courses](https://www.youtube.com/user/rithustutorials/playlists)
- [Udemy Courses](https://www.udemy.com/user/in28minutes/)
- [Facebook](http://facebook.com/in28minutes)
- [Twitter](http://twitter.com/in28minutes)
- [Google Plus](https://plus.google.com/u/3/110861829188024231119)

###Other Courses
- [Spring Framework](https://www.udemy.com/spring-tutorial-for-beginners/)
- [Maven](http://www.in28minutes.com/p/maven-tutorial-for-beginners.html)
- [Eclipse](http://www.in28minutes.com/p/eclipse-java-video-tutorial.html)
- Java
  * [Java](https://www.youtube.com/watch?v=Y4ftqcYVh5I&list=PLE0D4634AE2DFA591&index=1)
  * [Java Collections](http://www.in28minutes.com/p/java-collections-framework-video.html)
  * [Java OOPS Concepts](https://www.udemy.com/learn-object-oriented-programming-in-java/) 
- [Design Patterns](http://www.in28minutes.com/p/design-patterns-tutorial.html)
- [JUnit](https://www.udemy.com/junit-tutorial-for-beginners-with-java-examples/)
- [C](https://www.udemy.com/c-tutorial-for-beginners-with-puzzles/)
- [C Puzzles](https://www.udemy.com/c-puzzles-for-beginners/)
- [Javascript](https://www.youtube.com/watch?v=6TZdD-FR6CY)
- [More Courses on Udemy](https://www.udemy.com/user/in28minutes/)
  * Java Servlets and JSP : Your first web application in 25 Steps
  * Learn Spring MVC in 25 Steps 
  * Learn Struts in 25 Steps 
  * Learn Hibernate in 25 Steps
  * 10 Steps to Professional Java Developer
- [Java Interview Guide](http://www.in28minutes.com/p/buy-our-java-interview-guide.html)
  * Core Java
  * Advanced Java
  * Spring, Spring MVC
  * Struts
  * Hibernate
  * Design Patterns
  * 400+ Questions
  * 23 Videos
