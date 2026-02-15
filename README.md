# Oracle Pluggable Database Assignment II (Oracle 21c)

## Student Information
- **Name:** Kevine  
- **Student ID:** 29725  
- **Course:** Database Development with PL/SQL (INSY 8311)

---

## Oracle Environment Used
- Oracle Database 21c (Multitenant)
- SQL*Plus
- Oracle Enterprise Manager (OEM)

---

## Task 1: Create a New Pluggable Database

### PDB Created
- **PDB Name:** `ke_pdb_29725`

### User Created Inside the PDB
- **Username:** `kevine_plsqlauca_29725`
- **Privileges Granted:** CONNECT, RESOURCE, UNLIMITED TABLESPACE

### Evidence Screenshots
- PDB creation command
- PDB open state (READ WRITE)
- User created inside the PDB

---

## Task 2: Create and Delete a Temporary PDB

### Temporary PDB Created
- **PDB Name:** `ke_to_delete_pdb_29725`

### Actions Performed
- Created the PDB successfully
- Verified it exists
- Closed it
- Dropped it completely including datafiles
- Confirmed it no longer exists

### Evidence Screenshots
- PDB creation
- PDB deletion

---

## Task 3: Oracle Enterprise Manager (OEM)

### OEM Access
OEM was accessed successfully using:

- URL: `https://127.0.0.1:5500/em`
- Login user: `sys`
- Container: `CDB$ROOT`

### Evidence Screenshot
- OEM dashboard showing the Oracle environment and PDB information

---

## Issues Encountered
**Yes**  
- ORA-00904: CON_ID invalid identifier (fixed by using CDB_ views)
- ORA-65012: PDB already exists (confirmed PDB was already created)

---

## Integrity Statement
I confirm that this work was completed individually and reflects my own practical execution.
