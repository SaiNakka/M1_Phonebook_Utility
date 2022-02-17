
# Description

Phonebook is a very simple project in C. Phonebook contains a set of basic functions for adding, searching, updating, and deleting new contacts.

## Identifying features
This application provides information on adding, viewing, modifying, receiving, and deleting data from/to files. Adding new entries, browsing them, editing and updating, searching for saved contacts, and deleting contacts in the phonebook is one of the most important services that become the main menu in the phonebook application. When you add anything to your phone book, you will be asked for personal information such as name, gender, first name, phone number, email address, and address. You can then edit, view, search, and delete this text.

# 5W's and 1H

## What
Helps store complete information under single contact number.

## Why
Can be used by any shops or companies and all other people to access to their contacts in future.

## When
Works specifically for easily contacting people whenever any need occurs.

## Where
Can be used by any of the world wide users.

## Who
User provides given information to store that application.

## How
Using C programming language.




# SWOT Analysis

![SWOT](https://user-images.githubusercontent.com/57895309/154569361-ec2f8d89-c1b6-4122-94b9-6dee05dadda1.png)



# Requirements

## High level Requirements

|Sl.NO|	ID	|Description|
|:---:|:---:|:---------:|
|1.	|HLR1	|Add a contact|
|2.	|HLR2	|Delete a contact|
|3.	|HLR3 | Search a contact|
|4.	|HLR4  |Modify a contact|

## Low level Requirements

|Sl.NO|	ID	|Description|
|:---:|:---:|:---------:|
|1.	|LLR1	|Storing a contact|
|2.	|LLR2	|Details of particular contacts |
|3.	|LLR3 | Exit from the main menu|

# Architecture

## Design

## Structural Diagram

![Diagram (2)](https://user-images.githubusercontent.com/57895309/154573001-15b6fa52-d38d-4662-9adb-415a34eb3db9.png)

## Behavioural Diagram

![Diagram](https://user-images.githubusercontent.com/57895309/154573095-11c0356f-89a9-41d2-a858-67e23e417e2d.png)

## Use case Diagram

![Diagram1](https://user-images.githubusercontent.com/57895309/154573407-16dc1bc3-463c-48f5-b635-94ca9e4232cd.png)


# TEST PLAN
## High level test plan


|Test ID|	Description|	Expected Output|	Actual Output	|Result|
|:-----:|:----------:|:---------------:|:--------------:|:-----:|
|H_01	|Check if the new contact is created or not|	SUCCESS	|SUCCESS|	PASS|
|H_02| Check if the contact information is updated or not|	SUCCESSS|	SUCCESS|	PASS|
|H_03|	Check if the contact is modified|	SUCCESS		|SUCCESS	|PASS|
|H_04|	Check if the contact is saved|	SUCCESSS|	SUCCESS|	PASS|
|H_05|	Check if the contact is saved|	SUCCESS|	SUCCESS|	PASS|


## Low level test plan


|Test ID|Description|	Exp IN|Exp OUT	|Actual OUT|
|:-----:|:---------:|:-----------:|:--------------:|:-----:|
|L_01|	During saving check if contact is unique in that application|	Name|	SUCCESS|	SUCCESS|
|L_02|	During saving if name alrady exists, do not allow for saving|	Name and other	|NAME_ALREADY_EXISTS|	NAME_ALREADY_EXISTS|
|L_03|	Check if contact is properly saved|	Name and other information	|SUCCESS|	SUCCESS||
|L_04|	If data is collected from file during when the user needed|	Contact file|	SUCCESS	|SUCCESS|
|L_05	|If the contact is removed then delete|	Contact|	SUCCESS	|SUCCESS|


# Output
![Output](https://user-images.githubusercontent.com/57895309/154581714-c1c9767a-9148-474c-a010-3f82e8602f21.png)


![output1](https://user-images.githubusercontent.com/57895309/154581251-867054f3-5ba0-4283-a427-54aa217ae975.png)

