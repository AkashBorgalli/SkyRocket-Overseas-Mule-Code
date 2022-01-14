
# SkyRocket Overseas Chatbot Project MuleSoft-Code

🚩***Problem Statement***: \
Sky Rocket Overseas Company wants to reduce task & time of the employees where the role of the employees is to be available till the working hours waiting for the Customers to arrive on their online system and once customer is arrived  collect necessary details from the user that are planning to study abroad and also help them with their queries related to their company after which notify the Overseas Consultants for the same as well as feed the customer details in database for future analysis of data.




## 📜 Data Description:
We would receive data from ChatBot in a form of json where we would get Customers Name, Country, Degree, intakeYear, Course, email-id, Date and Mobile Number.
## 📝 Features

- Convert data in respective datatype.
- Send Email Notification to Gmail.
- Tranfer data to CosmosDB for future data analysis.
- Encrypted crucial information like paswords using AES Encryption.
- Applied Client Enforcement Policy to secure our API.


## 🛠️ Environment Variables

To run this project, you will need to add the following environment variables in properties section of runtime manager before deploying

`env`

`secure.key`

`anypoint.platform.client_id`

`anypoint.platform.client_secret`


## ⚙️ Run Locally
***Note: Please do changes in configuration files as per your credentials***\
Steps : 1. Download as zip or clone this repository.\
2. Extract it and then open Anypoint Studio.\
3. Click on file from the top menubar and then select open project from file system.\
4. Click the project folder and Click Finish.\
5. Go to run option from the top menubar -> run configuration for the particular project -> add env and secure.key variable.\
6. Right click Run project chatbot-api.



## ✔️ Deployment

Steps: 1. Export code as Jar file from anypoint studio.\
       2. Upload Jar file in Runtime Manager using [Anypoint Platform](https://anypoint.mulesoft.com/login/).




# 🎯 Demo

[My MuleSoft Code Walkthrough with Deployment for this project](https://youtu.be/T4LgmYt-Pvs).


## 💻 Tech Stack

**Client:** Microsoft Bot Framework Composer

**Server:** MuleSoft, Gmail, CosmosDB


## 💡 Usage/Examples

- It can be used to integrate many applications like Databases, Sharepoint, FTP etc.
- secure data transfer using secure policies
- Transforming data


## Author <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25>

- [@Akash Borgalli](https://www.linkedin.com/in/akashborgalli/)

