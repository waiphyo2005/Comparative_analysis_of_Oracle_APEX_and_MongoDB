Comparative Analysis of SQL and NoSQL: Evaluating Oracle APEX and MongoDB Performance and Storage Efficiency

Overview
This repository serves as supporting documentation for our research paper, performing comparative analysis on the performance and storage utilization efficiency of Oracle APEX and MongoDB across three medium-scale dataset sizes.

Repository Contents
This repository is organized into three main directories:

Proof of Testing for Execution Speed for Read Write Operations/
This directory contains screenshots of read and write operation benchmarks conducted on both Oracle APEX and MongoDB Atlas. Tests were performed on three datasets of varying sizes (25,000, 50,000, and 100,000 records). The screenshots provide evidence of operation execution times for both database management systems. 

Proof of Testing for Execution Speed for Read Write Operations/
This directory contains screenshots of storage utilization for both databases. The screenshots demonstrate the storage space consumed by each of the three datasets when stored in Oracle APEX versus MongoDB, providing empirical evidence for storage efficiency comparison. Additionally, this directory includes a text file containing queries used to retrieve storage size from MongoDB. The query to retrieve from Oracle APEX is not included due to the use of GUI interface for storage size retrival.

Datasets Utilized for Testing/
This directory contains the three CSV datasets used throughout the testing process:
data_25k.csv - 25,000 records
data_50k.csv - 50,000 records
data_100k.csv - 100,000 records
These datasets were imported into both Oracle APEX and MongoDB Atlas to ensure consistent and comparable testing conditions.
