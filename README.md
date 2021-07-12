## Project – Sample Example For Adding, Updating and Deleting Products
* For Storing the product details used MYSQL Database.
* And we are specifying all the configuration details in application.properties file like driver, database name, username, password and the port number on which we want to run our application.
## Steps to Run:
* Clean install the application using maven install or maven build and if the Build is Success then
Run the application as RUN AS SPRING BOOT APP and then it shows the port number on which the 
Application is running.
* Open POSTMAN and hit the url with the portnumber http://localhost:9090/bookTrainTicket and provide the JSON data and hit it.
You will see the generated response .
## Sample Request:
{
    "name":"Bhavya",
    "quantity":"60",
    "price":"70.4"
}
## Sample Response:
{
    "name":"Bhavya",
    "quantity":"60",
    "price":"70.4"
}
