 vendor-caterer-database

 Vendor & Caterer Database System

-- Overview --

This project is about designing a database system for a catering business to replace manual record-keeping using logbooks and Excel.


 --Objectives--

 *Identify system requirements
 *Design structured database
 *Improve data accuracy and security


-- Problems Identified--
 
 *Data redundancy
* Difficult data sharing
* Lack of security
* Hard to generate reports

 --My Role--

* Project Manager
* Designed system flow
* Contributed to database design

--Entities--

* Customer
* Orders
* Payment
* Venue
* Event
* Package

-- Relationships--

* Customer → Orders (1:M)
* Orders → Payment (1:1)
* Venue → Event (1:M)

-- Key Learning--

* Database design (ERD)
* SQL basics
* System thinking
* Team collaboration






--ERD--

This Entity Relationship Diagram (ERD) shows the structure of the Vendor and Caterer Database System. It includes main entities such as Customer, Orders, Payment, Venue, Event, Book, and Package.

Each customer can make multiple bookings and orders. The Orders entity is connected to Package, which shows the selected catering package. Each order also has one payment record to store payment details.

The Venue entity is related to Event, where each venue can host multiple events. The Book entity connects Customer and Venue, representing booking information.

This design helps organize data properly, reduce duplication, and improve system efficiency.




--FLOWCHART--

This flowchart shows the current system process for handling customer bookings in the catering business.

The process starts when staff receive a customer inquiry and check the customer information. If the customer is new, the staff will register the customer and record the details. If the customer already exists, the staff will check venue availability and record event details.

Next, the customer selects a menu package and proceeds to choose a payment method such as cash, QR, or bank transfer. After payment is completed, the staff creates the order record and updates the data into the system for reporting.

This process is currently done manually, which can cause delays and increase the risk of errors.
