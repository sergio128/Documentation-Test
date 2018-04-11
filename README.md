# DIGITAL PLATFORM – ADMINISTRATOR

## GETTING STARTED
An overview of the platform, how to configure and use all the functions that the Company Administrator role have.

The administrator has the Setting menu, which will be explained in this guide, therefore, you must make sure that you have the role of Company Administrator, in the upper right corner

## 1. Configuration

Here you can modify the main information of the company and its main page.
To start editing you must click on the edit button in the upper right corner.
 
The fields will be unlocked to enter information such as:
* Company name
* Phone
* Location
* Address
* Custom domain name
* Logos
 
You can also see the connection string, API Client ID and Secret API by clicking on the green lock icon to the right of these.
 
Finally, you can modify the landing page of your platform, by clicking on the Theme Editor button in the upper right part of the window. When clicking, the following view will appear.
 
In this editor you will have a section on the right to include basic objects by dragging them to the preview on the left.
 
You can also switch between different predesigned topics, as well as include form fields.

## 2. Payment Gateways

In this menu the payment gateways available on the platform are configured 

To do this you must click on the “Configure” button and it will show you a window where you must enter the user and password of the payment method you want to add

## 3. Forms

In this menu you can modify the custom forms that appear on the platform 

To link a form with a data set you must click on the button   . It will be used to link a form with a dataset, which is created in the Data Framework menu - Data Sets

When you click on one of the forms, the editor will appear in which you can modify the names and location of the fields, or add additional fields as necessary.

## 4. Apps
In this menu you can add more apps, which are embedded pages on the same platform and that will appear in the "My Apps" menu.

To add more apps you must click on the Add App button in the upper right corner. A window will appear in which you must enter the name and url of the application.

## 5. Bots

In this menu you can configure the url of the chatbots that will be included in the platform 

To do this you must click on the Add Bot button located in the upper right corner and enter the name of the bot as well as its URL

## 6. Data Framework

### a. Connections

In this menu you can configure and add the database connections that will be used on the platform. 

Connections to on-premises resources require Microsoft Hybrid Connection Manager Installed and Configured. And you can download the hybrid connection manager here.

You have 2 options to add a connection which you will find by clicking the Add button in the upper right corner.

**Add SQL Connection**

The following information must be entered:

Connection Name

Type: MS SQL Server / Oracle SQL Server / MySQL Server

User Name

Password

Server Name

Port

Database Name

On Premises Resource


**Add PartStore Connection**

The following information must be entered:
Connection Name

User Name

Password

Nonce

Web Service Url

Web Service Hostname

Port

Declare Code

On Premises Resource 


### Data Sets

In this menu you can set up and add data sets that will be used on the platform
 
To set up a new data set you must first create it by clicking the Add Data Set button in the upper right corner and entering the following information:

* Connection: Deberá elegir una conexión creada en el menú Data Framework - Connections
* Name
* Update Type
* * Full: Load the entire table always, truncate and load
* * Incremental: Lad only deltas (new / updated records)
* * Live: Makes the query direct to the table in its location (without moving data to the platform in the cloud)
* Refresh: Cada qué tiempo se recargará
 
After you create it you can enter the SQL Query in which the data set will be based
 
You will also have 3 tabs to modify the dataset settings
* Properties
* Power BI
* Alerts

You can also see a history of the execution of the data set 

### c. Reports

In this menu you can configure and paste the reports that will appear in the Reports menu 

To add a new report you must click on the Add Report button in the upper right corner, a window will appear in which you must enter:
* Report Description
* Report File: PBIX file or powerBI file
* Sort Order
* RLs (Row Level Security): you can only see what is related to the customer account that you have set. Only affects the customer, the admin can see everything


## 7. Security

### a. Users

In this menu you can view and register and invite users to the platform
 
To add a new user you will have to click on the Add User button in the upper right corner.

The following information must be entered:

* Email Address
* Phone Number
* First Name
* Last Name
* Legal Entity
* User Type: Company User / Customer / Vendor

You can also invite users by clicking on these buttons

To edit a user you must click on a row.

Then you will have to click on the Edit button in the upper right corner 

Clicking the button allows you to edit the Legal Entity and Phone fields. You can also link roles, customers and vendors by clicking on the respective Add button at the bottom right 

### b.	Roles
In this menu you can create and edit the roles of the platform


To add a new role you will need to click the Add Role button in the upper right corner, and then enter the name of the role.

To view the information related to a role you will have to click on one of them and you will be able to see the list of users that have that role and edit the different accesses that has the role with respect to all the menus of the platform

To add or remove these accesses, you must first click on the Edit button at the top right, then you can make the respective changes in each of the tabs.
 
### c. Permissions

In this menu you can create the permissions that will be used on the platform 

To register a new permission you must click on the ADD permission button located in the upper right corner and enter the name and description of the permission.

### d. Customers

In this menu you can modify and add the customers for the platform

You can synchronize the Dynamics AX table by clicking the Autosync button located in the upper right corner

To add a new customer you must click on the Add Customer button in the upper right corner and enter the following information:

* Customer Number
* Company Name
* Legal Entity


To modify a customer you must click on the row, then click on the Edit button in the upper right corner to modify your information and also link users by clicking on the link User button located in the lower right corner

### e. Vendors

In this menu you can modify and add the vendors for the platform 

You can synchronize the Dynamics AX table by clicking the Autosync button located in the upper right corner

To add a new vendor you will need to click the Add Vendor button in the upper right corner and enter the following information:
* Vendor Number
* Company Name
* Legal Entity
  

To modify a vendor you must click on the row, then click on the Edit button in the upper right corner to modify your information and also link users by clicking on the link User button located in the lower right corner

