# Cloud Computing Assignment Number 3: Web application to display Forecast records
In Assignment number 3 the objective is to develop User interface for the weather application to display forecast of next 7 days.
Angular JS is used to populate the table without refreshing the whole page. Here user is given a text box to search for a desired date 
of which he wish to know the forecast and next 6 days.


## Important Information about the web application
Here the user is given a Interface where he/she can enter a date from that date next 6 days forecast will be fetched from the service 
created in the assignment number 2. This is done by angular JS and there it can be seen that there is seemless transition of data been populated in the table of the next 6 days.

## Getting Started:
Use the following link:
### http://ec2-54-186-40-227.us-west-2.compute.amazonaws.com:8080/Rest_proj/

If the date is valid then next days forecast will be showcased. Otherwise the garbage values will be displayed.

### Prerequisities

Internet connectivity, 
Browser

## Operations Performed

Created Amazon linux EC2 instance using default security group. Used putty to execute linux command and installed apache-tomcat 8.5.39.
To run the application used apache tomcat 8.5.39 server on local machine. Uploaded the application on the apache tomcat on the linux server. To run the application on the server used the public DNS address of the EC2 instance and appended it with the port number of apache and the application name.


## References

1. Deploy Java Web App on Amazon Linux EC2 Instance Using Tomcat 
https://www.youtube.com/watch?v=_d-c9uGcUrU

2. Basic of Angular JS
https://www.w3schools.com/angular/

3. Docker file
https://docs.docker.com/engine/reference/builder/


## Author

* **Sumit Ghewade** - *Initial work* - [ghewadesumit](https://github.com/ghewadesumit)
