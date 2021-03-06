<h1> Coding Exercise </h1>

<h1> Motivation </h1>
Building this project to showcase my technical skill in Core Java 8 and Spring Boot.
The project has a restful UI to check if two cities are connected or not, where orgin and destination are passed in the HTTP GET request param.
Sample Restful UI of this project.Note : Please start the Spring Boot Applicaion before trying the below URL.
<ul>
  <li><a href="http://localhost:8080/connected?origin=Boston&destination=Newark"> http://localhost:8080/connected?origin=Boston&destination=Newark </a></li>
  <li><a href="http://localhost:8080/connected?origin=Boston&destination=Philadelphia"> http://localhost:8080/connected?origin=Boston&destination=Philadelphia </a></li>
  <li><a href="http://localhost:8080/connected?origin=Philadelphia&destination=Albany"> http://localhost:8080/connected?origin=Philadelphia&destination=Albany </a></li>
</ul>
  
  
<h1> Build status </h1>
Build : Success


<h1> Screenshots </h1>
To verify the screen shot of the Junit and Testing, please open the attached microsoft document. -<a href= "https://github.com/neeraj1982/Coding-Exercise/blob/master/Testing-ScreenShot.docx">Testing ScreenShot </a>

<h1> Programming Language and Framework used </h1>
<ul>
<li> Core Java 1.8 </li>
<li> Spring Boot 2.3.1 </li>
</ul>

<h1> Code Example </h1>
<ul>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/Application.java">Application.java</a> - Main Spring Boot application file.Please run this to start the Spring Boot Application which by default runs in Tomcat on default port 8080. </li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/controller/CityController.java">CityController.java</a> - RestController which defines the HTTP GET request for checking the connection between cities.It accept two request 
param origin and destination. <a href = http://localhost:8080/connected?origin=Boston&destination=Newark </a> </li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/model/City.java">City.java </a> - Model Class to encapsulate the City Object.The attributes are origin and destination. </li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/model/Constants.java">Constants.java</a> - Java Class to hold the constant variable used in this project. </li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/service/CityGraph.java">CityGraph.java</a> - Graph data structure populated with city data.The city data gets loaded from city.txt file.Each vertex in the graph data structure is one city and its store the link of the connected cities. </li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/java/com/city/service/CityService.java">CityService.java</a> - Service class used to write logic for checking the connection between cities.</li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/resources/city.txt">city.txt</a> - The input text file which has the information of the interconneced cities.</a></li>
<li><a href="https://github.com/neeraj1982/Coding-Exercise/blob/master/src/main/resources/application.properties">application.properties</a> application properties file to store the properties values used in this project.</li>
</ul>


<h1>Tests</h1>
Please run the Junit Test cases CityControllerTest.java.
This <a href ="https://github.com/neeraj1982/Coding-Exercise/blob/master/Testing-ScreenShot.docx"> Testing Screen Shot Document </a>  captures the Junit and Manual Tesing done. 


<h1>License</h1>
Neeraj Kumar <a href="https://www.linkedin.com/in/kr28neeraj"> Linkedin </a>









