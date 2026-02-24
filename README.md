# AWS Web Database Application – Case Study

## Overview
This class project documents the design and implementation of a web-based database application deployed on AWS. The system allowed users to query a relational database through a browser interface and download results in tabular or Excel format.

Due to security considerations, source code, credentials, and private configuration files are not included. This repository focuses on system architecture and data flow.

---

## System Architecture
- Cloud Platform: AWS EC2 (Linux)
- Web Server: Apache
- Backend Logic: Python (CGI scripts)
- Database: MariaDB (MySQL-compatible)
- Data Processing: Pandas (Excel export)

---

## Functionality
- Web form for submitting SQL queries
- Parameter-based filtering (e.g., date and price conditions)
- Dynamic HTML table rendering of query results
- Downloadable Excel output generated using Pandas

---

## Implementation Highlights
- Designed end-to-end client–server data flow
- Integrated Python with SQL for dynamic query execution
- Deployed and tested the application on a live AWS EC2 instance
- Applied basic security practices by isolating credentials and limiting public access

---

## Notes
This repository presents the project as a system design and implementation case study. Sensitive files, credentials, and private keys are intentionally excluded.
