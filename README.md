**Project Requirements**
⦁	IntelliJ 
⦁	JDK 1.8 
⦁	Maven 3.9.3
⦁	SpringBoot - 3.1.2
⦁	React 18.2.0
⦁	Node js v18.17.0
⦁	npm 9.6.7
⦁	Mongodb 6.0.8


**Database**
Database name - urlshortener
Database table - URL_table
1.	To create a database - use urlshortener
2.	To create a table (in mongodb its a collection name ) - db.createCollection("URL_table")
3.	To insert data - db.URL_ta ble.insertOne({" _id": "", " originalUrl" : "https://yahoo.com",    "shortUrl": "http://localhost:7070/08fba31e"," createdAt": "ISODate("2023-07-23T10:37:56.678Z")", "expiresAt" : "ISODate("2023-07-23T10:42:56.678Z")"  })
4.	db.URL_table.find().pretty() - used to show all the documents available in that collection.

   
**React - **
1.	npx create react-app UrlShortener - to create a react app 
2.	cd URlShortener -  get inside the application 
3.	npm install axios - create HTTP requests that are present externally 
4.	npm start - command to start a frontend application

   
**Backend - **
i.	 Import the project
ii.	Go to the Maven Settings. Under Maven settings go to maven and browse apache-maven  zip folder and extract and add it to maven home path and click on apply and next click OK .
iii.	Under Maven -  click on importing and select JDK in JDK Importer and click on OK.
iv.	At last run UrlShortenerApplication 
