# PostgreSQL Database Administration Lab

## Overview
A hands-on PostgreSQL DBA portfolio project using a fictional
payments database.

The lab demonstrates database setup, relational schema design,
data integrity and SQL reporting. Additional security, performance,
and recovery exercises are planned.

## Environment
- Host operating system: Windows
- Guest operating system: Ubuntu 26.10
- Database: PostgreSQL 17.12
- Desktop administration tool: pgAdmin 4
- Database name: payments_lab
- Application schema: payments

## Completed
- Installed PostgreSQL on an Ubuntu virtual machine.
- Verified database connectivity.
- Connected from pgAdmin on Windows.
- Created a dedicated database owner and application schema.
- Created customers, accounts and transactions tables.
- Inserted synthetic sample data.
- Verified customer-account-transaction relationships using joins.

## Database Structure
- customers: fictional customer details
- accounts: accounts linked to customers
- transactions: credits and debits linked to accounts

Relationship:
customers → accounts → transactions

## Sample Data
- 3 customers
- 3 accounts
- 6 transactions

Transaction examples include successful, pending and failed statuses.

## Implemented Constraints
- Primary keys
- Foreign keys
- Unique email addresses, account numbers and transaction references
- Required fields using NOT NULL
- Positive transaction amounts
- Restricted account and transaction statuses

## Repository Contents
- docs/: environment notes and recorded test results
- sql/: database setup, table definitions and verification scripts
- screenshots/: evidence from the lab

## Planned Work
- Invalid-data constraint testing
- Reporting-role access control
- Performance investigation and indexing
- Backup and restore testing

## Limitations
This is a learning lab, not a production payment platform.
It does not implement double-entry bookkeeping or account balances.

## Data and Security
All sample records are synthetic.
No real customer data, employer information or credentials are included.
