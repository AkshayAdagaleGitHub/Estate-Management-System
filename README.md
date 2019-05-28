# Network-Based-Application
                                                   Estate Management System

Project Overview :
In the world of the internet, we know that everything is just a click away. Whether you want to buy a car or a mobile phone, all you need to do is just search for it and it is all there. If you want to sell something you just need to upload the information on some web server and anyone in the world can get their hands on it. Through this portal we try to simplify the task of buying/selling flats and row houses The end users(customers) can browse through the collection of row houses/flats and rates of the concerned construction company. If they find something of their interest they can book/mark a property of their interest and the company executive and be sent to the customer’s residence with additional information about the same.

Requirements:
The system is Client Server architecture. It requires following
- Front End : HTML, CSS, Servlets
- Back End : MySql.
- IDE : Netbeans.

Need: This portal saves the time of the end users who don’t have to move from office to office. It also saves the resources of the construction company which just needs to upload data to the web server with hardly any paperwork (for brochures etc). It may also save them office space. The construction company should also have an easy way to manage its staff (customer executives, agents, etc.)

Goal:
The project aims at developing a Construction company Portal which caters to the needs of people who are interested in buying and selling of flats, row houses. XYZ Real Estate Portal is an online service committed to helping users make wise and profitable decisions related to buying, selling of properties.
This portal will provide fresh new approach to our esteemed users to search for properties to buy or sale. It will also help the Real Estate organization to manage their resources and inventory of flats/row houses.

Future Scope:
We can extend our portal to give different additional functionalities.
- The real estate organization can use this for staff/employee management.
- Adding mobile communication: Advertisement of new upcoming projects to registered users via SMS.

Site Map :
Page Design:
User Page :
 After the user logins in with user credentials he will be taken to the userpage.jsp.
 Here he will be able to see his name and on the left hand side to welcome the user.
 He can select the view construction link on the left bar which will guide him to the view construction area page .
 This page displays the name of the company.
 It displays the footer with the port number and host number.
 It displays the header which has the logout , about and how .

Construction.jsp
 This page displays the areas or the construction sites where the construction is going on and the area which are available to the 
   customer through our portal
 It uses the jstl tag which is useful for security point of view.
 The user will be the audience of this page.
 It will display the area_id and the area_name and a select option where the user can select a particular area.

Society_display.jsp
 The audience of this page is User.
 The user can select a society from the area which he previously selected.
 Here the user has 3 fields the society_id the society_name and an option to select the society in which he is interested.
 The user will be guided to the next buildings.jsp after he selects a particular society.

Building.jsp
 This page lets the user select the type of building the user is interested in.
 The user can see the building name the building Id and the status of the flats in the building .
 He can see the number of floors the number of flats on each floor.
 When a user selects a particular building he can see the status of the flats and number of flats that are available to for him.
 When a user is ready to book a flat he can select the book a flat link and he can he will be shown the society , area , flat and as 
   he will be a registered user he will see this name and email .

Customer information.jsp
 Here the user can see his booking details and his contact details.
 After clicking on submit he will be guided to the submit display page.
 Where he will see that the customer support will contact you thank you for booking a flat.

Feedback.jsp
 This is on the home page and the user page here a new user without registering can also give a feedback and submit his details.
 Here the user has to enter the name contact number email address and their feedback .

Display Feedback.jsp
 This is the administrator page.
 Here the administrator can view all the user feedbacks and act on them.

Add construction.jsp
 Here the user can add new constructions.
 If there are any new areas where the company has started construction the he can add the constructions.

Applying Security Measures:
The application covers three main attacks against web applications. The following table summarizes the attacks, their corresponding countermeasures and chapters where they are covered.
-Attack
-Cross-site Scripting (XSS)
-Prevention
-JSTL out tag
-Attack
-SQL injection

Prevention
-Prepared Statements
Attack
-Social engineering
Prevention
-Hash and Salt Passwords

Conclusion:
This portal saves the time of the end users who don’t have to move from office to office.
It helps to the Customer to be aware about the current market. It also helps the Construction organization to easily reach to the 
customers and helps to manage their resources easily.
