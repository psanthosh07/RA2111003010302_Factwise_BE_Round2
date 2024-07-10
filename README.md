# Team Project Planner

## overview

Project to implement a team planner tool with the help of Python ,by creating API's for the operations and storing and accesing the data locally using JSON files
## Tech Stack Used :
<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="100" height="100" /></div>

## Features
 **1)User Management :**
 -create,list,describe and update Users
 -search for teams and informations for a particular user

 **2)Team Management :**
 -create,list,describe and update teams
 -Add/team remove users from the team
 -list users in a particular team

 **3)Project Board Managment**
 -create,list,clsoe project boards
 -add tasks to boards,update task status
 -export board to a presentable view

## MODULES:
 - **user_base.py**: Implements API for user management
 - **team_base.py**:Implements API for team Management
 - **user_datamodel.py**:Defines the User data model structure
 - **persistence.py**Handling of Data persistance oprations

 ## Concepts Used and why
 - **Data Persistence**:
data is handled using the JSON files and it is managed by the persistance.py file.
 - **Data Model Definition**:
  Data model is defines the data structures ('User' ,'Team) used throught the project
 - **Modular API Design**:
  Each modules perform a specific operations and has its own classes and methods to handle according to their domains
- **Data Intergrity Checks**:
   API methods to perform robus exception handling and data intergrity checking
