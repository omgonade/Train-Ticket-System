# Train-Ticket-System
It is a python GUI-based project which can be used to book tickets.
GUI is made with the help of tkinter library
The user has to choose the given source and destination and after pressing the Total button the cost, source, destination, etc. is shown to the user.
To book the ticket user has to press on submit button and confirm its ticket by clicking yes on pop up.
Once the user confirms the booking then an email will be sent to the email address which was input by the user for Ticket Confirmation.
The user data is saved in the MySQL database. 
In this, no different tables are made for people going to different destinations.
To differentiate tables based on their source and destination we can use the where clause in MySQL. For example:-
Select * from reservation4 where Departure ="Chandigarh" AND Arrival="Pune";
