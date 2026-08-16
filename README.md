API Testing with Postman and JMeter 

This project conducts API testing with the help of Postman and basic load testing with the help of Apache JMeter.  
API: JSONPlaceholder
Base URL: https://jsonplaceholder.typicode.com  
Tools Used: Postman  and Apache JMeter 

How I ran the Tests is as follows:

Postman  

1. Open Postman.  
2. create the Collection JSONPlaceholder-API-Testing.json. 
3. Open the collection.  
4. Add the request like Get, Post, Put or Delete. 
5. Add Url for Get request and then click send it give all the entities.
6. For validation of status code etc i open script and write javascript code for validation and click send.
7. Then I review my answer.
8. And repeat this for all the http methods for Post i provide data and it gives 201 status code means created.

JMeter  

1. Open Apache JMeter. 
2. Open the file called called test plan, which i rename with this “JSONPlaceholder-Load-Test.jmx”. Click on it.
3. Select the Thread Group. Check test settings:  
* Users: 10  
* Ramp-Up: 5 seconds  
* Loop Count:  
4. Click the Start button.
5. Open View Results Tree to view the answers. To view response time, throughput and error rate, I go to Summary Report. 
