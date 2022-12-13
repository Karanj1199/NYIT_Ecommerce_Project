# NYIT_Ecommerce_Project

software enginerring group project 7

Table of Contents

Background
Install
Usage
Generator
Changelog
Maintainers
Contributing
License



1. Description
An e-commerce website made as part of the project in the course software engineering from New york Institute of Technology.

2. Features and functionality

Detection
Categorization
Possibility to run on different models
Frame skipping & interpolation
3. Technologies used

Python Language - application logic
OpenCV - object detecion framwork
PyQt - user inteface framework
FFmpeg - video processing
3. Installation

**Installation:**


      1) Clone the project repository: https://github.com/Karanj1199/eCommerceSite-PHP.git

      2) Install XAMPP

      3) Unzip the project inside for windows C:\xampp\htdocs,  (Your download loc may vary)

      4) Start XAMPP

      5) Start APACHE & MySQL

      6) Click on "Admin" button besides "MySQL" in XAMPP app

      7) Create new database table with name: "ecommerceweb"

      8) After keeping the database "ecommerceweb" selected,import "ecommerce.sql" file from C:\xampp\htdocs\eCommerceSite-PHP\DATABASE FILE  (Your download loc may vary)

      9) Launch the website : http://localhost/eCommerceSite-PHP/login.php  

**For User login/Register**

      1) Register filling info

      2) Click on "Admin" button besides "MySQL" in XAMPP app

      3) Select "ecommerceweb" database which we imported.

      4) Click on "tbl_customer"

      5) Edit the new user by changing cust_status from "0" to "1"

      6) Login to your website


**For Admin login**

    1) http://localhost/eCommerceSite-PHP/admin/login.php

    2) email: admin@mail.com
       Password: Password@123
   
  
**Technologies:**
    
      1.Backend: PHP, JavaScript, MySQL
   
      2.Frontend:HTML ,CSS, Bootstrap
   
      3.Other Technologies: Paypal, Xampp Server(Apache)
   
   
   
Changelog

v1(29 March—9 April) Implement the log in verification. CustomerDaoImpl has a lot of redundant code in the multiple methods. It is also simpler to convert the commonly used variables into member variables and initialize them in the constructor. The rest of the DAO layer recommendations follow this approach

v2(12 April — 25 April) Add two JavaBeans, Course and Video, and aggregate the Course collection into the Customer and Trainer classes. The CustomerDaoImpl constructor is not rigorous enough and has been modified. Add customer deleting function. Improve TrainerDaoImpl and other implementation. Add VideoWrapper. Add .idea to gitignore. Prevent to commit the .idea/ directory into git. To achieve video playback function, see TestVideo. Java for specific call.

v3(26 April—9 May) Implement TrainerSchedule page presentation course. Show Coach Information. User registration and information verification function. Improve the front-end page.

v4(10 May-21 May) Merge remote-tracking branch 'origin/master' into master. Merge new front end.

v5(24 May-31 May) Merge operation about course.

**ScreenShots:**


**Contributing**

You can see our contribution here

Contributors
1.Karan Patel — kpate312@nyit.edu

2.Arthi Reddy — akolanu@nyit.edu

3.Denish Moradiya— Dmoradiy@nyit.edu

4.Thanushree E G —teadalag@nyit.edu

5.Supraja — ssirikon@nyit.edu

6.Jaya Surya — jpagidi@nyit.edu


