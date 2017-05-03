## _Title_
	Epicodus- Java - Leap Year
	
#### _Creator_
	Lilo Onwuzu 
	
#### _Date_
	04.18.2016

#### _Description_
	This java code allows a user to enter a year and then checks if that year is a leap year
  Restful web pages are routered and rendered through the Spark Framework. 
	Velocity tool is used to create html (with lightweight java code) templates for our Spark routines (get/post etc).
	VelocityTemplateEngine is used as an adapter to add Velocity templates to our Spark routines.	
The code was designed using Behavoir Driven Development (BDD) testing principles. 
The unit testing of the backend is done using jUnit. 
The integration testing of the user interface was done using Selenium Webdriver tests and a FluentLenium Adapter. 
All testing dependencies were managed using Gradle for the app version with db that runs locally. 

#### _Setup/Installation Requirements_
	 
	1. Set Up To Run Database Locally On Computer (Optional- for testing)
		First clone this repository
		Install Gradle (a build & test automation program that will manage all our dependencies)
		Build in the terminal using 'gradle run' command
		Install Postgres
		Run "pg_ctl start" in terminal to start running postgres server
		Run "psql" in a new terminal to access DB
		In psql: 
			Run "CREATE DATABASE band_tracker;"
			Run "CREATE DATABASE band_tracker_test WITH TEMPLATE band_tracker;"
		In Terminal:
			Run "psql band_tracker < band_tracker.sql"
		Open localhost:4567 in any browser to use the web application
		
	2. Visit app with database running on remote heroku server: https://bands-and-venues.herokuapp.com/
	
	3. Interact with the app by adding new bands, new venues and adding different bands to play at different venues
		 View list of venues and which bands are playing there 
		 View list of bands and what venues they will be playing 

#### _Known Bugs_
 	None

#### _Support and contact details_
	lpr422@gmail.com
	
#### _Technologies Used_
	HTML, CSS, Object Oriented Java, SQL on POSTGREs DB, Selenium Web Driver- UI Testing, Fluentinum Adapter, Gradle, BDD Testing, 
	jUnit backend testing, Spark Framework, Velocity Templates, Velocity Template Engine, Google API Fonts, RESTful routing
	Many to Many Database Relationships, Gradle Dependency Manager, Maven Dependency Manager, Heroku Postgres,  

#### _License_
	This software is licensed under the MIT license
	Copyright (c) 2016 IPONWUZU


