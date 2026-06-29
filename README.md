# Database_programming_assingment2_30625-2025
# Assignment II: Oracle Pluggable Database (PDB) Administration

## 1. Assignment Overview
The objective of this assignment is to gain practical experience in managing Oracle Multitenant Architecture, specifically focusing on creating, configuring, and managing Pluggable Databases (PDBs) and user accounts.

## 2. Oracle Environment
* **Oracle Version:** Oracle Database 21c Express Edition
* **Operating System:** Windows 11
* **Tools Used:** SQL*Plus, Command Prompt

## 3. Task Documentation
* **PDB Creation:** Successfully created the PDB `Al_pdb_306252025` using the `FILE_NAME_CONVERT` command.
* **User Creation:** Created user `Ali_plsqlauca_306252025` and granted the required `DBA` privileges.
* **Temporary PDB:** Created and subsequently dropped `Al_to_delete_pdb_306252025`.
* **OEM Configuration:** Attempted access to Oracle Enterprise Manager (OEM); however, the service could not be started in the current environment.

## 4. Challenges and Solutions
* **Challenge 1:** Encountered `ORA-65005` and `ORA-65016` errors during PDB creation due to invalid file name patterns. 
  * **Solution:** Resolved by explicitly specifying the full path in `FILE_NAME_CONVERT` matching the local directory structure.
* **Challenge 2:** The Oracle Enterprise Manager (OEM) and the listener service failed to initialize properly.
  * **Status:** This remains an unresolved technical limitation in the current local setup.

## 5. Lessons Learned
Through this assignment, I learned how to manage Oracle PDBs and handle common configuration errors related to file paths and privileges. I gained a deeper understanding of the Multitenant architecture and how to troubleshoot database creation issues.

## 6. Integrity Statement
"I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged."
