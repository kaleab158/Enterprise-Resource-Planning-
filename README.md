# Enterprise-Resource-Planning-
Design and Implementation of an Enterprise Resource Planning (ERP) System for Pharmacy Management
#	Background of the System
Pharmacies play an important role in Ethiopia’s health care system by supplying medicines to patients every day. Private pharmacies and drug stores in Addis Ababa and other cities and towns buy medicines from suppliers and importers, manage stock, sell to customers, and keep records of their income and expenses in Ethiopian Birr. Public health facilities also receive medicines through the Ethiopian Pharmaceutical Supply Agency (EPSA). In addition, pharmacies are expected to follow the rules of the Ethiopian Food and Drug Authority (EFDA), which regulates the quality, safety, and handling of medicines, including proper storage and the removal of expired products.
Despite these responsibilities, many pharmacies in Ethiopia still rely on paper registers, record books, or separate spreadsheets. This makes it hard to know what is in stock, which medicines are close to their expiry date, and how much the pharmacy sells and earns. Mistakes in counting and recording are common, and finding old records takes a lot of time.
Enterprise Resource Planning (ERP) is software that brings a business’s main processes into one system with a shared database. This project proposes an ERP system for pharmacy management that combines inventory, sales and billing, supplier and purchase management, and employee management in one place. The system will help pharmacy staff work faster, reduce errors, and make better decisions from accurate, up-to-date information. It will also make it easier for pharmacies to keep organized records that support EFDA inspection and reporting requirements.



# Problem Statement
Many pharmacies and drug stores in Ethiopia still manage their daily work with paper registers, record books, or separate spreadsheets. This manual way of working causes several problems:
•	Inaccurate stock records: Medicine stock is counted and recorded by hand, which leads to mistakes, stock-outs of important medicines, and overstocking of others. Staff often have to search the shelves to know whether a medicine is available.
•	Expired medicines: Expiry dates are not tracked in a central place, so medicines may expire on the shelf without anyone noticing. This causes financial loss and can put patients’ safety at risk.
•	Slow and error-prone sales and billing: Prices are calculated and receipts are written by hand, which takes time, causes mistakes in Birr amounts, and creates long waiting lines for customers.
•	Scattered supplier and purchase records: Orders, invoices, and supplier details are kept in different books or files, which makes reordering and payment follow-up difficult.
•	Difficulty in reporting and compliance: Managers cannot easily produce reports on sales, stock, and profit. Pharmacies also find it hard to prepare organized records for inspection by the Ethiopian Food and Drug Authority (EFDA).
•	Weak control over staff and records: Without user accounts and access levels, anyone can change or remove records, and it is hard to know who did what.
These problems waste time and money, reduce the quality of service to customers, and make it hard for pharmacy owners to manage their business well. Therefore, an integrated ERP system is needed that records inventory, sales, purchases, and staff activity in one place, produces accurate reports, and works reliably under local conditions such as limited internet access and power interruptions.
This is why our team developed this project, to fill the gap. Our Enterprise Resource Planning (ERP) system for pharmacy management offers practical benefits to pharmacies and to the country. It supports Ethiopia’s Digital Ethiopia 2030 strategy by promoting the use of digital technology in the health sector and in everyday business.

# Objectives
#  General Objective
The general objective of this project is to design and develop an Enterprise Resource Planning (ERP) system for pharmacy management in Ethiopia that integrates and automates the main pharmacy operations, including inventory, sales and billing, purchasing, and staff management, in order to improve accuracy, efficiency, and service quality.
# Specific Objectives
The specific objectives of this project are:
•	To study the current manual way of working in pharmacies and collect the system requirements through observation and interviews with pharmacy staff.
•	To analyze and design the system using UML diagrams, such as the use case diagram.
•	To develop an inventory module that tracks medicine stock, expiry dates, and low-stock alerts.
•	To develop a sales and billing module that calculates prices in Ethiopian Birr and prints receipts.
•	To develop a supplier and purchase management module that records orders, invoices, and supplier details.
•	To develop a user and employee management module with role-based access (admin, pharmacist, and cashier).
•	To generate reports on sales, stock, expired medicines, and profit to support decision making and EFDA inspection records.
•	To test the system for correctness and usability and fix any errors found.
# Significance
The ERP system for pharmacy management will be useful to several groups:
•	Pharmacy owners and managers: It gives accurate, up-to-date information on stock, sales, and profit, so they can make better decisions. It also reduces losses from expired medicines, miscounted stock, and billing mistakes.
•	Pharmacists and pharmacy staff: It makes daily tasks such as checking medicine availability, selling, and recording stock much faster and easier than searching registers and shelves by hand.
•	Customers and patients: They receive faster service, shorter waiting lines, and clear receipts in Ethiopian Birr. Tracking expiry dates also helps make sure that the medicines they buy are safe.
•	Regulatory and health authorities: Well-organized records make it easier for pharmacies to prepare for Ethiopian Food and Drug Authority (EFDA) inspections and to keep proper documentation.
•	The country: The project supports the Digital Ethiopia 2030 strategy by encouraging the use of digital technology in the health sector and in small businesses.
•	The project team and other students: It gives practical experience in applying software engineering principles, and the documentation can serve as a reference for future projects.
# Feasibility Analysis
Feasibility analysis checks whether the project can be completed successfully. This project is studied from four sides:
# Technical Feasibility
The system can be built with widely available, free technologies such as a web front end, a back-end programming language the team already knows, and a relational database. The team members have the programming and database skills needed to build the system. It will run on ordinary computers that pharmacies already have, so no special hardware is required. The system is also designed to work on a local network, so it can keep running when the internet connection is unstable.
# Economic Feasibility
The development cost is low because the team uses free and open-source tools, and the work is done by students as part of the course. For a pharmacy, the main benefits are less waste from expired medicines, fewer stock and billing errors, and time saved by staff. These benefits are greater than the small cost of setting up and maintaining the system, so the project is economically feasible.
# Operational Feasibility
The system has a simple and user-friendly interface, so pharmacy staff can learn it with little training, even if they have limited computer experience. It follows the way pharmacies already work (stock, selling, purchasing), so staff are likely to accept it because it makes their work easier. Role-based access for the admin, pharmacist, and cashier also matches the usual structure of a pharmacy.
# Schedule Feasibility
The scope is limited to a few core modules: inventory, sales and billing, supplier and purchase management, and user management. The work is divided into short sprints, and the team has assigned tasks to each member. For this reason, the team expects to finish the project within the time given for the course.
# Software Process Model
This project will use the Waterfall model, which is a sequential software development process. The work moves through a series of phases, and each phase must be completed and reviewed before the next one starts. The output of one phase becomes the input of the next, like water flowing down steps.
The phases of the Waterfall model in this project are:
1.	Requirements analysis and definition: The team studies how pharmacies in Ethiopia currently work and collects the requirements through observation and interviews with pharmacy staff. The functional and non-functional requirements of the ERP system are then written down and agreed on.
2.	System and software design: Based on the requirements, the team designs the system architecture, the database structure, and the user interface. UML diagrams, such as the use case, class, and sequence diagrams, are produced in this phase.
3.	Implementation (coding): The design is turned into working code. The team builds the modules one by one: inventory, sales and billing, supplier and purchase management, and user management.
4.	Testing: The modules are combined and the complete system is tested for errors. Unit, integration, and system testing are done to confirm that the system meets the requirements.
5.	Deployment: The tested system is installed and handed over to the pharmacy for use, and staff are given basic training on how to use it.
6.	Maintenance: After deployment, the team fixes any errors that appear and makes small improvements as needed.
Why Waterfall was chosen
•	The requirements of a pharmacy system (stock, sales, purchasing, and staff) are clear and well understood from the beginning, and are unlikely to change much.
•	The model is simple and easy to manage, which suits a student team with a fixed schedule.
•	Each phase has clear deliverables and documentation, such as the requirements document and design diagrams, which fits the documentation required by the course.
•	It is easy to track progress and assign tasks to team members phase by phase
