# ISellYouABrick CTF
Welcome to this memium/hard boot2root challange 🤓.
Why this name? Simply because a marketplace with these vulnerabilities can be just a scam. One in which you buy an electronic product with a strange low price and you will receive instead a brick.

## Requirements
- php ver 7.4.33 or lower.
- Preferably a linux machine. 

## Setup
- Create a new PostgreSQL database with a table called 'users' with the fallowing structure and values:

| **username** | **passwd**         | **account_type**   |
|:------------:|--------------------|--------------------|
|     Admin    | af1_2@df223g-$swea | RSnakeXKPLlGdf2gYf |
|    wiener    |        peter       |  dqwe13fdsfq2gys38 |

- Clone the repository.
- Open the login.php file and set the databse credentials in the pg_connect method.
- In the root folder open a new terminal.
- Start a php server typing ***php -S IP:PORT***.

## Note
At this moment the challange is not hosted, so you have to host by yourself in localhost and find the way to intercept the localhost requests with your proxy tool (Burp, Zap, etc.).

Morever, it is better to host the challange in a linux machine to avoid problems with all the tools that you need.

Moreover pt.2, precisely because it is hosted in localhost, you have full access to the source code, so obviously if you wont to solve the challange you do not have to read that code.

## Too hard?
Visit the wiki for hints and spoilers.
