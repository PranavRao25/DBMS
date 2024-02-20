Database Management System

Database is a collection of interrelated data
Management System is used to manage the data present in the DB (access, edit, delete, create)

Goal of DBMS - Provide efficent storage and management mechanisms for data

Disadvantages of File System:
1. Data Redundancy  and Inconsistency -
	1. Information maybe duplicated across various files
	2. Different files may have different formats, which may hamper the efficiently
2. Difficulty in accessing data

### Views of Data

We would want to provide different access permissions to different users. For this we incorporate Data Abstraction in form of Views

View is a sub-database of the main database which shows only those data which are requested.
Multiple views of the same database is possible

### Data Abstraction

1. Physical Level -
	1. Low level Data Structures
2. Logical Level -
	1. Describes the data properties and relationships
	2. Physical Data Independence
3. View/User Level -
	1. Part of the database which is requested by the user

<b>Instance</b> : Database state and its data at a particular moment of time
<b>Schema</b> : Design of the database

## Data Models

Collection of conceptual tools which describe the data, its relationships and semantics, and constraints

Types of Data Models:
1. Relational Model
	1. Data and their relationships are represented by tables (called relations)
2. Entity - Relationship Model (ER Model)
	1. Uses collection of entities and their relationships among each other
3. Object Base Data Model
	1. Combines OOP and ER Model
4. Semistructured Data Model:
	1. Individual Data items of the same type may have different set of attributes (XML)
5. Network Data Model
6. Hierarchical Data Model

#### Database Languages
1. DDL (Data Definition Language):
	1. Used to specify the database schema
2. DML (Data Manipulation Language):
	1. Used to specify queries and updates
