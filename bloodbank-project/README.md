# Blood Bank Database Management System (BBDMS)

## Setup Steps

1. Run schema files:
   - schema/tables.sql
   - schema/sequences.sql

2. Insert data:
   - data/inserts.sql

3. Load logic:
   - logic/functions.sql
   - logic/procedures.sql
   - logic/triggers.sql

4. Run test cases:
   - test/test_cases.sql

## Features
- Donor eligibility validation (90-day rule)
- Blood compatibility logic
- Automated unit release after screening
- Full audit logging via triggers
- Stored procedures for real-world operations

## Tech Stack
- Oracle SQL / PL-SQL
- Docker (Oracle DB)
- DBeaver (Client)
