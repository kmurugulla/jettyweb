# Sample Jetty WebApplication Project
#### A Sample maven based web application project that can be deployed to Jetty Web Server.

	### Highlights

	1.Using Jetty maven plugin for running jetty in eclipse with configurations
		a.to hot deploy code (target/classes)
		b.with a context root (/jetweb)

	2.Configured slf4J with log4J bindings
		a.src/mainresources/log4j.properties contais log4j configurations
		b.jetty-logging.properties is configured to use slf4j and loglevel set to "DEBUG"

	3.Using WebServlet annotation to register servlet

	### Setup Instructions

	1.Clone repository
	2.Import as existing maven project into eclipse
	3.mvn clean jetty:run will build and deploy the webapp to local jetty at 8080


