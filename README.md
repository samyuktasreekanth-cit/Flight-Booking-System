This project is to implement an application system related to a flight booking system. The
projects includes both the database and front-end (Java) aspect to it. The database is done with
MySQL workbench and the front-end is done with eclipse. The project focuses on the general
purpose procedural programming language.


Detailed description and specifications:


There is an option for both the customer and the staff.
The customer should be able to log-in or sign up. A customer not existing in the database will be
given a randomly generated customer ID after signing up. I am assuming that every customer
enters unique username and password.
A customer can make many bookings. He/she provides his/her customerID before booking
process begins. The bookingID, luggageID and paymentID is automatically generated and
displayed to the customer.
There are only three flight classes(Economy, Business or First)
There are only two luggage types(Carry-on or Check-in)
There are only three modes of payments(Visa Debit Card, Visa Credit Card and PayPal)
A customer also has the option of viewing his/her bookings, since there are customers with
multiple bookings.
Customers can also cancel a booking, but they must provide their bookingID.
The staff also has an option to add or remove flights. For simplicity, I am allowing the staff to
only add flights and not the airports.
Any price, totals, or amounts are in decimals rounded to two decimal places.
The date format is in yyyy-mm-dd
