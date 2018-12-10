# Restapi
This is restapi sample project

This is laravel 5.7.16, To run this project kindly use the latest xampp server.

Config the valid email(gmail) address and password in the .env file, bacause i have used smtp.gmail.com for mail send functionalities.

Kindly view the restapi\routes\web.php file for the url's for (register,login,view list of users,edit user,image upload).

For registration we have to pass name,email,mobileno,password as parameters in post method in /register url.

For login send email and password by post method in /login url.

After login you will get the jwt token as a response.

To view the list of users pass jwt token as authorization : (jwt_token) in the headers for /users url by get method.

To edit the user details email is unique here am going to take this email value to update the other details, pass the values to update existing details of user. Here all values are required field(email,name,mobileno,password). jwt token as authorization : (jwt_token) in the headers for /update url by post method

To update image pass email and image as parameters to /profilepic url with jwt token as authorization : (jwt_token) in the headers.







