# Article CMS (FlaskWebProject)
### Create a Resource Group in Azure.
### Create an SQL Database in Azure that contains a user table, an article table, and data in each table (populated with the scripts provided in the SQL Scripts folder).
![image](https://user-images.githubusercontent.com/18415884/119339179-8dcd6b00-bc99-11eb-803d-3f6831ff93b2.png)

### Provide a screenshot of the populated tables as detailed further below.
#### table posts
![image](https://user-images.githubusercontent.com/18415884/119339317-ae95c080-bc99-11eb-820a-1a192b5dad23.png)


#### table users
![image](https://user-images.githubusercontent.com/18415884/119339352-b7869200-bc99-11eb-81f8-9afec356ff25.png)


### Create a Storage Container in Azure for images to be stored in a container.
### Provide a screenshot of the storage endpoint URL as detailed further below.
#### storage container
![image](https://user-images.githubusercontent.com/18415884/119339404-c79e7180-bc99-11eb-9f7e-bde3a4fe3330.png)



### Add functionality to the Sign In With Microsoft button.
### This will require completing TODOs in views.py with the msal library, along with appropriate registration in Azure Active Directory.
### Choose to use either a VM or App Service to deploy the FlaskWebProject to Azure. Complete the analysis template in WRITEUP.md (or include in the README) to compare the two options, as well as detail your reasoning behind choosing one or the other. Once you have made your choice, go through with deployment.
### Add logging for whether users successfully or unsuccessfully logged in.
### This will require completing TODOs in __init__.py, as well as adding logging where desired in views.py.
### To prove that the application in on Azure and working, go to the URL of your deployed app, log in using the credentials in this README, click the Create button, and create an article with the following data:
Title: "Hello World!"
Author: "Jane Doe"
Body: "My name is Jane Doe and this is my first article!"
### Upload an image of your choice. Must be either a .png or .jpg. After saving, click back on the article you created and provide a screenshot proving that it was created successfully. Please also make sure the URL is present in the screenshot.
### Log into the Azure Portal, go to your Resource Group, and provide a screenshot including all of the resources that were created to complete this project. (see sample screenshot in "example_images" folder)
### Take a screenshot of the Redirect URIs entered for your registered app, related to the MS Login button.
### Take a screenshot of your logs (can be from the Log stream in Azure) showing logging from an attempt to sign in with an invalid login, as well as a valid login.
