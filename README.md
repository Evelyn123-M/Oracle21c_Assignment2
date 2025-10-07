# Oracle21c_Assignment2
oracle21c, database, sql, oem, assignment, AUCA, insy8314


##  Student Information
**Name:** Mutuyimana Evelyne  
**Student ID:** [27701]  
**Course:** INSY 8314 – Database Systems  
**Institution:** Adventist University of Central Africa  
**Date:** October 2025


## Overview
This project demonstrates practical Oracle 21c Database administration tasks:
1. Creating a new Pluggable Database (PDB)
2. Deleting a PDB
3. Accessing and configuring Oracle Enterprise Manager (OEM)

The exercises were performed using **Oracle Database 21c Express Edition (XE)** on Windows.


## Task 1 – PDB Creation
**SQL Command:**
```sql
CREATE PLUGGABLE DATABASE EV_PDB_27701
ADMIN USER Evelyn IDENTIFIED BY "Michou@123"
FILE_NAME_CONVERT=(
'C:\ORACLE21C\ORADATA\ORACLEDB\PDBSEED\',
'C:\ORACLE21C\ORADATA\ORACLEDB\EV_PDB_27701\'
);

<img width="541" height="315" alt="TASK1A" src="https://github.com/user-attachments/assets/d1812904-646a-4ba5-9923-dac73ad09e67" />

**Task 2 – PDB Deletion

ALTER PLUGGABLE DATABASE EV_to_delete_pdb_27701 CLOSE IMMEDIATE;
DROP PLUGGABLE DATABASE EV_to_delete_pdb_27701 INCLUDING DATAFILES

<img width="777" height="474" alt="TASK2" src="https://github.com/user-attachments/assets/b27f68ed-fe6f-4cc3-97f1-915380865fd7" />

**Task 3 – Oracle Enterprise Manager**

After configuration, the OEM Dashboard was accessed via:

http://localhost:5500/em


Username: Evelyn
Password: Michou@123
<img width="937" height="439" alt="task3" src="https://github.com/user-attachments/assets/aafdbbc6-ec77-4408-a244-883bfbabbdcd" />
<img width="937" height="439" alt="task3" src="https://github.com/user-attachments/assets/08fe97f6-7648-4bfb-88e4-799cc6a321c0" />




