# todo-list-application
A simple to-do list application that utilizes SQL and allows for CRUD.

## How to Use
This application requires:
- MySQL Server
- Apache

These applications are bundled together via XAMPP. [[Download Link](https://www.apachefriends.org/download.html)]
The setup is quite simple once you have these applications installed, as you just need to run Apache and MySQL.

***

### Setup

**Note: when using XAMPP, you must place the php files in the htdocs folder.**

For a default install:
- Windows: `C:\xampp\htdocs\`

#### Note on setting up the Apache server
You may have to edit the httpd.conf file in order to change the port you're running the server on. I set my port to 8080.
You must place all of the php files in the htdocs folder.

#### Note on setting up the SQL Server
- Once the Apache and MySQL servers are running, go to localhost:[port]/phpmyadmin
- Click on the SQL tab on the top navigation bar
- Input the SQL query that is located in tasks.sql and select Go to create the database 

***

### Dependencies
This application uses PHP to connect to a locally stored MySQL database. Using the tools provided through XAMPP's installer, you can easily host this todo list application. The SQL code required to create the database has now been included.

### Uses
This application is more of a proof of concept, but you can try and find a practical use out of it if you'd like.

### Takeaway
Learning PHP was a lot easier than JavaScript, but solving problems in JavaScript is much more interesting. At first, I approached this using JavaScript and Node.js, but I was running into too many issues with the SQL code.

So, I switched over to PHP and decided that it would be easier to send update commands from a GUI. I'm also going to include (on another branch) the progress that I was making while creating this using Node.js.

Had I not switched to PHP for this application, my other option was going to be Python, which I find to be really be a jack of all trades when it comes to any sort of programming project.

### Update
If you check out the v0.1js branch, all of the files for the node version of this application are included. I thought it was an interesting approach, and figured I would include it.
