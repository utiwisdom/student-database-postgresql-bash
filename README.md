# 🎓 Student Database — PostgreSQL + Bash ETL

![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Scripting-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**A Bash script that turns messy CSV files into a clean, normalized, production-style database — zero manual entry, zero duplicate data, zero orphaned records.**

## Proof

30 students. 7 majors. Correctly linked. NULLs handled properly, not faked.

![Students table in pgAdmin](pgadmin-students-table.png)
![Query verification](query-verification.png)

## What It Does

CSV → validate → dedupe → load into a normalized 4-table PostgreSQL schema, enforced by foreign keys the database itself won't let you break.
