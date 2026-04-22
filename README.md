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
