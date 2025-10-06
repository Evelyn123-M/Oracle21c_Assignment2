# Oracle21c_Assignment2
oracle21c, database, sql, oem, assignment, AUCA, insy8314
# Oracle 21c Database Assignment II – Database Creation, Deletion & OEM

##  Student Information
**Name:** Mutuyimana Evelyne  
**Student ID:** [27701]  
**Course:** INSY 8314 – Database Systems  
**Institution:** Adventist University of Central Africa  
**Date:** October 2025

---

## Overview
This project demonstrates practical Oracle 21c Database administration tasks:
1. Creating a new Pluggable Database (PDB)
2. Deleting a PDB
3. Accessing and configuring Oracle Enterprise Manager (OEM)

The exercises were performed using **Oracle Database 21c Express Edition (XE)** on Windows.

---

## Task 1 – PDB Creation
**SQL Command:**
```sql
CREATE PLUGGABLE DATABASE EV_PDB_27701
ADMIN USER Evelyn IDENTIFIED BY "Michou@123"
FILE_NAME_CONVERT=(
'C:\ORACLE21C\ORADATA\ORACLEDB\PDBSEED\',
'C:\ORACLE21C\ORADATA\ORACLEDB\EV_PDB_27701\'
);
