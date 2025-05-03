# Database Management System for Agricultural Machinery Sales

This project focuses on designing and implementing a database management system to support various operational aspects of an agricultural machinery company. The system is tailored to manage sales, parts inventory, logistics, and customer interactions efficiently.

## 📝 Sommario
- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Methodology](#methodology)
- [Key Components](#key-components)
- [Database Design](#database-design)
- [Implementation Details](#implementation-details)
- [Python Interface](#python-interface)
- [How to Use](#how-to-use)
- [Authors](#authors)

## Overview
The project aims to develop a comprehensive database solution for Zamponi Srl, an agricultural machinery company. The database will facilitate the management of:

- **Sales and Purchases**: Handling transactions related to agricultural machinery and spare parts
- **Logistics**: Managing shipping and delivery processes
- **Customer Support**: Addressing customer requests and ensuring timely service

The system is designed to streamline operations, improve data accuracy, and enhance decision-making capabilities.

## Project Objectives
1. **Design a Robust Database Schema**:
   - Develop an Entity-Relationship (ER) model
   - Translate the ER model into a logical schema
2. **Implement the Database**:
   - Create the database using MySQL Workbench
   - Populate and test with SQL queries
3. **Develop a Python Interface**:
   - Build user-friendly CRUD operations
   - Enable complex query execution
4. **Ensure Scalability and Maintainability**:
   - Design for future growth
   - Comprehensive documentation

## Methodology
1. **Requirements Gathering**:
   - Interviews with Alessandra Zamponi
   - Identified key automation areas:
     - Sales/purchases
     - Spare parts management
     - Logistics
     - Customer support

2. **Volume and Operations Table**:
   - Documented concepts and expected volumes
   - Specified operation frequencies and types

3. **Conceptual Design**:
   - Created Entity-Relationship (ER) model
   - Captured all entities and relationships

4. **Logical Design**:
   - Translated to relational structure
   - Defined tables and relationships

5. **Implementation**:
   - Built in MySQL Workbench
   - Populated with ~120 records
   - Validated with 10 test queries

6. **Python Interface**:
   - Developed CRUD application
   - Enabled query execution and reporting

## Key Components
- **Database Schema**:
  - ER Diagram
  - Logical schema documentation
- **Sample Data**:
  - Realistic simulation data
- **SQL Queries**:
  - 10 functional examples
- **Python Application**:
  - Query execution
  - Data manipulation
  - Reporting tools

## Database Design
### Entity-Relationship Model
- Business entities: Customers, Machines, Parts, Orders
- Relationship types: one-to-many, many-to-many

### Logical Schema
| Table       | Description                     |
|-------------|---------------------------------|
| Customers   | Client information             |
| Machines    | Equipment inventory            |
| Parts       | Spare parts database           |
| Orders      | Sales transactions             |
| Shipments   | Delivery tracking              |

## Implementation Details
- **Database Tool**: MySQL Workbench
- **Database Name**: bd25
- **Records**: ~120 across all tables
- **Test Queries**: 10 validation queries

## Python Interface
Features include:
- SQL query execution
- CRUD operations
- Data analytics

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sorrentini.2002/AgricolaDBMS.git
    ```

## Set Up the Database

### Import SQL schema

Load sample data

### Run the Python Application:

```bash
pip install mysql-connector-python
python main.py
```
## Authors

- Tommaso Cristadoro

- Gabriele Seri
- Matteo Sorrentini
- Federico Trionfetti

## License
This project is licensed under the MIT License.
   
