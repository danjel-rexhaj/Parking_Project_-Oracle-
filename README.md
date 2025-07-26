# Parking_Project_-Oracle-
Parking Management System — Oracle SQL Database
This project implements a comprehensive Parking Management System designed to manage multiple parking locations, customers, vehicles, employees, and billing activities using Oracle SQL.

Features
Customer Groups & Discounts: Manage customer groups (e.g., VIP, Student, Resident) with different discount rates.

Clients and Vehicles: Store client information and their associated vehicles with unique license plates.

Parking Locations: Define multiple parking points/locations.

Membership Cards & Subscriptions: Track membership cards linked to subscriptions and parking locations.

Pricing by Time Slots: Set variable parking prices based on different time intervals per location.

Parking Activity Logs: Record vehicle entries and exits, associating them with specific parking locations.

Employee Management: Manage employees responsible for parking operations and pricing.

Billing & Invoices: Automatically calculate parking fees considering discounts and subscriptions; generate invoices.

Daily Cash Management: Track daily earnings per employee with procedures to close daily activities.

Data Integrity: Triggers prevent double parking of the same vehicle at overlapping times.

Invoice Cancellation: Procedures to cancel invoices with negative value entries for refunds or corrections.

Database Structure
The system uses relational tables for:

Customer groups (Grupe_Klientesh)

Clients (Klientet)

Vehicles (Mjetet)

Parking locations (Pika_Parkimi)

Membership cards (Karte_Antarsie)

Subscriptions (Abonimet)

Parking pricing (Cmime_Parkimi)

Parking activity (Aktivitet_Parkimi)

Employees (Punonjesit)

Invoices (Fatura)

Daily cash balance (Gjendja_Arkes)

Usage
The system supports full lifecycle management of parking activities from vehicle entry, fee calculation, invoice creation, to daily financial reconciliation.

Technologies
Oracle Database (PL/SQL)

Tables, Views, Triggers, Stored Procedures, and Functions
