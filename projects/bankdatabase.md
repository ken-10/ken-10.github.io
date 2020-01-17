---
layout: project
type: project
image: images/bankbase_thumbnail.png
title: Bank Database
permalink: projects/bankdatabase
# All dates must be YYYY-MM-DD format!
date: 2020-1-16
labels:
  - C
  - C++
summary: Create a bank database program with a singly linked list in both C & C++
---

## Bank Database Software
This application allows users to add, view, delete and modify the address of a record.
<br/>
I created this with a singly linked list data structure in C first as a project for my ICS 212 class. I then converted it into a C++ program. 
<br/>
Each record in the database contains an account number, name, and an address. We needed to be able to add new records without duplicate account numbers and the program should sort all records in descending order. 
<br/>
There are two viewing options in this program. You are able to view a specific account number by providing the account number, or you can view all accounts in the database. The delete option takes in an account number and will delete the account associated with the account number if it exists.
<br/>
Lastly, there was an option to modify the address of an existing account number. All information in the bank database is saved into a text file that is generated if one doesn't exists at the launch of the program. If there is a save file, it will read from that rather than creating a new one. Before the program quits, it will rewrite the data into the save file. 
<br/>
[GitHub Repository](https://github.com/ken-10/ICS-212-Project-1-Project-2-Bank-Database-) <br/>
Video Demo (coming soon)<br/>
<br/>
<img class="ui image" src="../images/bankbase_thumbnail.png">
