# Bus Booking



# Project-documentation

<p align="center">
  <a href="" rel="noopener">
 <img width=500px height=200px src="HomePage.png" alt="Project logo"></a>
</p>


<h3 align="center">HomePage</h3>

---

<p align="center"> In my project, I had implemented Bus booking system that allows users to book bus tickets online using Java programming language and a database.
  <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Flow Chart](#flowchart)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
The Bus Booking System is a software application that allows users to book bus tickets online using Java programming language and a database. The system offers a user-friendly interface for searching and booking buses, selecting seats, and managing bookings. It utilizes a database to store and manage user information, bus schedules, seat availability. The system also includes an admin interface for managing buses, routes, and fares, as well as generating reports and analytics. This system provides a convenient and efficient way for users to book bus tickets online and for bus operators to manage their operations.


## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

1.Open NetBeans IDE and select new project and give your project name

2.Right click on project and select JFrame form and design the form using pallete properties

3.Download MySQL-connector jar file and add into libraries

4.Using that, Give database connection using JDBC

5.To perform database operations download SQLYOG 

### Prerequisites
we have to install

NetBeans IDE

SQLYOG version 5

### Installing
A step by step series of examples that tell you how to get a development env running.

You need to download NetBeans here,

https://netbeans.apache.org/download/index.html

 And download SQLYOG here

 https://sqlyog.en.softonic.com/?ex=DINS-635.2

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>
Before run the project we have to make sure that,

1. Right click on the pannel and select properties, then select code on the top right corner after that click generate center

2. Click on source and right click then select Run File

### Break down into end to end tests
User registration:

Test that users can create new accounts with valid information.

Test that users cannot create accounts with invalid or incomplete information.

Test that the system displays appropriate error messages when users provide incorrect information.

Bus search and selection:

Test that users can search for buses based on different criteria (e.g. origin, destination, date, time).

Test that users can view details of available buses (e.g. price, schedule, amenities).

Test that users can select a bus and proceed to the booking process.

Booking process:

Test that users can select the desired seats for the selected bus.

Test that users can enter passenger details and payment information.

Test that users can review their booking details and make changes before finalizing the booking.

Test that the system generates a confirmation page and sends a confirmation email to the user after successful booking.


## 🎈 Usage <a name="usage"></a>
Travelers can use the system to search for available buses, view schedules and fares, select their preferred seats, and make payments for their bookings. They can also cancel or modify their reservations if necessary.

## 🚀 Deployment <a name = "deployment"></a>
 You need to decide where you will deploy your bus booking system. You can either deploy it on-premises or on the cloud. Cloud deployment offers the advantage of scalability, flexibility, and ease of management. If you choose to deploy on-premises, ensure you have the necessary hardware and software infrastructure.

To deploy the application to a production environment follow these steps:

1. Ensure that you have installed the reqired softwares and the necessary environment variables, such as the database connection variables.
2. Start the application by selecting source and then select "Run file"
3. Use proper JDBC code for database connectivity.

## ⛏ Flow Chart <a name = "flowchart"></a>

![bg width:1000px](./LoginPageflowchart.png)

- [MySQL](https://www.mysql.com/) - Database
- [NetBeans](https://netbeans.com/) - software

## ✍️ Authors <a name = "authors"></a>
- [@SkillLync](https://github.com/kylelobo) - FSD

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- I would like to thank the following individuals for their contributions to this project:
- The team at Skill-Lync for generously providing the data used in this project
- References: https://code-projects.org/bus-ticket-booking-system-in-java-with-source-code/