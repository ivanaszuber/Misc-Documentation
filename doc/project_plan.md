#Project Plan

2. Business Goals and Project Goals


Business Goal


Automatic development of offers for domestic and foreign customers from the data contained in the system.
Tracking of available stock, reserving available stock, ordering out-of-stock products.

The Offer Monitoring system should present an invaluable support in decision making at various levels of management and every day operational  work; such as quick access to information, an ease report, the establishment and operational execution of workflows (process access) (Shtub, 2009:123). In addition, a user-friendly system should provide an integrated solution where by the wise management one can reach all the necessary information interesting to the offer management department.


Project Goal

Design, develop and implement an automated, dynamic offer monitoring system by Q1 2014.

Project goal is to develop and implement an integrated, process-oriented Offer Monitoring System, which contains all the elements for keeping up-to-date information about the company’s offers. The system should consist of a series of ready- made solutions, which by using a methodological approach, should adapt to organizations of various activities  and industries. All parts of the system should contain the same rules and standardized operation, and be very easy to use.

The basic features of the Offer Management System should include:
-     Process approach
-     Documentation System
-     Security
-     Administration

The final goal is to develop a centralized offer management  system. All data is to be stored in a central database and data access achieved by the client program.
Client server architecture is to be used to support operations, entering information into the system, configuration of the system and the use of peripheral devices (printers, scanners, bar code readers ...).


The Offer Monitoring System should consist of the following layers:

1.  Basic functionality:
-     Layer for data storage (databases)
-     User Interface


2.  Service functions:
-     Automatic upgrade by new versions
-     Reporting system
-     LDAP directory service for user authentication (Active Directory)


3. Scope


The OMS project includes the development,  delivery and implementation of the OMS system at the central Customer location. Project is based on Customer`s requirements and includes:


-     Offer Monitoring System
-     Maintenance
-     Reports

Activities and parts of the OMS comprised by the project include:


-     Project preparation
-     Database implementation
-     User authentication implementation
-     Presentation system development
       - Business Catalogue
       - Articles catalogue
       - Price list
       - Offers
       -     Maintenance
            -  Automatic upgrade
            -  Reports


Project preparation

Project preparation phase should include the creation of functional specifications with a list of all user requirements and the description of business processes and data structures related to Offer Monitoring, Maintenance and Reports. Analysis phase is to be made on the site through team workshops with responsible persons, and include a list of documents that are necessary to implement the proposed system.
In addition, special attention should be given to the making of a detailed protocol for data exchange with the internal offer management system.
Through the preparation phase of the project a detailed schedule with a list of activities is to be developed.


Database

The primary function of the database should be the storing of information and management of data integrity, and the establishment of agreed rules in the data model, by processes and information.
MS SQL Server 2012 is to be used as a database management system.


Layer for database access

Communication of the OMS application with the database should be executed by a series of software components made by using the Microsoft .NET technology (Parthasarthy, 2007:89). The only way in which components are to access the data is through the specially made sites in the database containing a rich set of SQL stored procedures.


The presentation layer, user interface

The user interface is to be made as a .NET Windows application in which a broad set of interaction possibilities between user and computer are to be embedded. During the development of application forms, all the standard Windows functions should be implemented, such as grouping, sorting and filtering data in lists.


System upgrade

OMS should be a system that strongly respects the versioning. A set of software components within the layers should form a package that has a label version. Any change in the components (for example, correction of perceived errors, and the   installation  of   new   functionality)     within    any    layer    should   require   the   change   of   the   version. The upgrading includes a number of steps that are performed completely  automatically  without any need for User intervention.


The Reporting System

For the creation of all the required reports, the MS Reporting Services technology is to be used. The Reporting Services (RS) technology standard allows that all published  reports can be opened via a web browser. The reports are to be stored on the server and, in accordance with the user rights, available to be viewed via internet browser.


For User registration and authorization a special set of components that communicate with Microsoft Active Directory by directory service are to be used.


4. Time and Budget Constraints


Time Constraint

The Project must be finished during the period of four months.

The beginning of project realization is securing all technical and technological prerequisites by the Customer and signing the contract.


Budget Constraint

The budget  for the project is set to $60,000.

All expenses that arise during the implementation period are part of the project budget and the Customer isn't obliged to pay any additional costs.