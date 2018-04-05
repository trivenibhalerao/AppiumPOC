# AppiumPOC
Simple Appium Repository with MAVEN


1.	Install eclipse
2.	Create new maven project (File- new – other – MAVN project)
3.	Install testing
4.	Install TestNG in Eclipse 
a.	1. Help -> Install New Software
b.	Click on Add -> Enter TestNG and path http://beust.com/eclipse/ -> click OK
5.	Check the project structure and right click on JRE System Library and click on properties.
6.	Add below dependency 

Copy below code within <Project> tag of Pom.xml
7.	<dependencies>
8.	<dependency>
9.	<groupId>junit</groupId>
10.	<artifactId>junit</artifactId>
11.	<version>4.11</version>
12.	<scope>provided</scope>
13.	</dependency>
14.	<dependency>
15.	<groupId>org.seleniumhq.selenium</groupId>
16.	<artifactId>selenium-java</artifactId>
17.	<version>2.46.0</version>
18.	<scope>provided</scope>
19.	</dependency>
20.	<dependency>
21.	<groupId>io.appium</groupId>
22.	<artifactId>java-client</artifactId>
23.	<version>3.1.0</version>
24.	<scope>provided</scope>
25.	</dependency>
26.	<dependency>
27.	  <groupId>org.testng</groupId>
28.	  <artifactId>testng</artifactId>
29.	  <version>6.8</version>
30.	  <scope>test</scope>
31.	</dependency>
32.	</dependencies>


7. Create a TestNG class and write a sample Test Case . Refer Appium tutorial for writing sample test case.And you can run maven test by right clicking on project and click on maven test.


