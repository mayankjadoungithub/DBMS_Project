# DBMS_Project
This project is about creating the database about Railway Management System. 
The railway management system facilitates the passengers to enquire about the trains available.

Booking and cancellation of tickets. enquire about the status of the booked ticket, etc. The aim of case study is to design and 
develop a database maintaining the records of different trains. Train status, and passengers. The record of train includes 
its number, name, whereas record of train status includes dates for which tickets are booked, total number of seats available.

Passengers can book their tickets for the train in which seats are available. For this, passenger has to provide 
the desired train number.


Once the train number and booking date are validated, it is checked whether the seat is available. 
If yes, the ticket is booked with confirm status and corresponding ticket ID is generated which is stored along with
other details of the passenger. The ticket once booked can be cancelled at anytime. For this, the passenger has to provide 
the ticket ID (the unique key). The ticket ID is searched and the corresponding record is deleted. With this, the first ticket
with waiting status also gets confirmed.
