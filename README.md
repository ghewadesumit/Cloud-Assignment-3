# Cloud Computing Assignment Number 3: Web application to display Forecast records
In Assignment number 3 the objective is to develop User interface for the weather application to display forecast of next 7 days.
Angular JS is used to populate the table without refreshing the whole page. Here user is given a text box to search for a desired date 
of which he wish to know the forecast and next 6 days.


## Important Information about the web application
Here the webapplication showcases the data of Cincinnati weather for last three years. 
A csv file is provided which gives the data for the Cincinnati's weather for last three years.
The csv file consist of three columns which are 
1) DATE - YYYYMMDD format
2) TMAX - Daily Max Temperature 
3) TMIN -  Daily Min Temperature

This Data is converted into JSON format and consumed by the webservices and can be accessed upon request.

## Getting Started:
Use the following link:
### http://ec2-54-186-40-227.us-west-2.compute.amazonaws.com:8080/Rest_proj/rest/supersumoz

### 1. /historical/:
Method that will be used here will be **GET** 
The expected output is to display all the DATES for which the weather report is available.

To test the **/historical/** end point use the following link:
### http://ec2-54-186-40-227.us-west-2.compute.amazonaws.com:8080/Rest_proj/rest/supersumoz/historical

### 2. /historical/dateYYYYMMDD:
Method that will be used here is **GET**
The expected output is to display the weather report for the given particular date

To test the **/historical/20130101** end point use the following link:
### http://ec2-54-186-40-227.us-west-2.compute.amazonaws.com:8080/Rest_proj/rest/supersumoz/historical/20130101

### 3. /forecast/dateYYYYMMDD:

Method that will be used here is **GET**
The expected output is to display the weather report for next seven days

To test the **/forecast/20130101:

### http://ec2-54-186-40-227.us-west-2.compute.amazonaws.com:8080/Rest_proj/rest/supersumoz/forecast/20130101

### Prerequisities

Internet connectivity, 
Browser

## References

1. Deploy Java Web App on Amazon Linux EC2 Instance Using Tomcat 
https://www.youtube.com/watch?v=_d-c9uGcUrU


## Author

* **Sumit Ghewade** - *Initial work* - [ghewadesumit](https://github.com/ghewadesumit)
