# Python-WIFI-Router-Login-Project
For this project I used Python to build a login system for a WiFi router that only allows those with administrative credentials to log in.
I created a function named getCreds that prompts the user for their username and password. 
This function returns a dictionary called userInfo.
Next, I created a function named checkLogin with two parameters: the userInfo and the adminList .
This function checks the credentials to see if they are contained within the admin list of logins. 
The function sets a variable loggedIn to True if the credentials are found in the admin list, and set to False otherwise.
Next, I created a while loop that will continue to call getCreds and checkLogin until a user logs inwith admin credentials.
I found this project to be very interesting and useful. Creating a set of login credentials and then prompting the user to provide those credentials is a powerful tool. 
