# StockPrediction

Project Phase 1

CONTENTS OF THIS FILE
---------------------------------------

* Introduction
* Requirements
* Download and Installation
* Creating database and tables
* Data dump
* Maintainers


INTRODUCTION
------------------------
This project is created to get the historic and live stock values from the Yahoo Finance and store it in the database.

REQUIREMENTS
--------------------------
The system will initially require the installation of the following software on a UNIX based operating system.
1. Eclipse?
2. MySQL v 5.1.22?
3. Apache 2.0.64?

DOWNLOAD AND INSTALLATION
-----------------------------------------------
* ÊMAMP, a free software for MAC OSX at the following site: http://www.mamp.info/en/
* ÊWAMP, a free software for Windows at the following site: http://www.wampserver.com/en/
* ÊEclipse, at the following site: https://www.eclipse.org/downloads/

¥ The following are the dependencies of the program:?
* Êcom.yahoofinance-api
¥ Version: 1.3.0?
* Êorg.hibernate
 ÊÊÊÊÊ-	Version: 4.1.9.Final
* Êmysql
¥ Version: 5.1.22?

CREATING DATABASE AND TABLES
---------------------------------------------------
Data needs to be collected at frequent intervals for the system to be operational. 
A copy of the database used for testing can be found within tables.sql
Connection with the database has been established within StockPredictionDAO.java at the URL Êjdbc:mysql://localhost:*port_no*/sp1

DATA DUMP
----------------------
The results for the stock values are dumped in the CSV file. There is a separate file created for each stock having historic and live data as required. 

MAINTAINERS
----------------------
Current maintainers:
* Vishal Bhalla
* Careena Braganza
* Mayur Kabra
* Sahil Karkhanis
* Anvi Vora



