### interface_specification
This is for internship entrance task. 

# Overview

A user interface for user management purposes

## Requirements

Should include a data screen that shows user datas
Button for adding new user
a form for adding user to data with following the filled form fields
User data required to have id, username, email, enabled setting for visibility

## UI Components

### 1. Header

3 components in a row

- New User Button
This is a button that allows the user to add a new user to the data. When clicked, it should make visible the add user form for adding a new user.

- Hide disabled User Checkbox
This is a checkbox to hiding datas that have 'disabled' in the data list.

- Save User Button
This is a button that allows to save datas and add to datalist following instructions on the fullfilled fields at add user section.

### 2. Main

2 components in a row

- #### Users List
This is a table that displays a list of all users in the data. It should display the following information for each user:
 - User ID
 - User Name
 - Display Name
 - Phone
 - Email
 - User Role
 - Enabled

- #### Add User Form
This is a form that containing required field for user which are:
 - Username
 - Display Name
 - Phone
 - Email
 - User Roles
 - Enabled

## Detailed Components

### Users List
The Users List table should be filterable and sortable according to informations. Should be responsive when shrinked to left column and informations should cover when filtered.

### Add User Form
<p>The Add User Form should be like this:</br>
Every information should be a row.</br> Username, Display Name, Phone, Email should be defined by text inputs.</br> 'User roles' should be defined by dropdown menu that contains Guest,Admin,Superadmin options.</br> 'Enabled' should be defined by checkbox.</p>


## User Interface Behavior
The User Management Screen should behave as follows:

- When the 'New User' button is clicked, The add User Form should be visible in the right column. The users list should shrink to left column. Save User button should be visible at just above of The Add User Form but should be in the header.
- When the 'Hide Disabled User' checkbox becomes checked, the users that has 'disabled' should become invisible in the users list.
- When the 'Save User' button is clicked, if the required fields is fullfilled in the 'Add User Form' it saves the values of fields into the data for being ready to listed in user list. Updates the screen for showing new user in userlist and closing the 'Add User Form'.

## Start Screen

When the user management screen is loaded, the user list should be displayed, and the header should be displayed that contains New User Button and Hide Disabled user Checkbox.
