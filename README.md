Comparative Analysis of SQL and NoSQL: Evaluating Oracle APEX and MongoDB Performance and Storage Efficiency

Overview
This repository serves as supporting documentation for our research paper, performing comparative analysis on the performance and storage utilization efficiency of Oracle Database and MongoDB across three medium-scale dataset sizes.

Repository Contents
This repository is organized into three main directories:

performance-tests/
This directory contains screenshot documentation of read and write operation benchmarks conducted on both Oracle Database and MongoDB. Tests were performed on three datasets of varying sizes (25,000, 50,000, and 100,000 records). The screenshots provide evidence of operation execution times and throughput metrics for both database management systems.

storage-analysis/
This directory contains screenshot documentation of storage utilization analysis for both databases. The screenshots demonstrate the disk space consumed by each of the three datasets when stored in Oracle Database versus MongoDB, providing empirical evidence for storage efficiency comparison.

datasets/
This directory contains the three CSV datasets used throughout the testing process:
dataset_25k.csv - 25,000 records
dataset_50k.csv - 50,000 records
dataset_100k.csv - 100,000 records
These datasets were imported into both Oracle Database and MongoDB to ensure consistent and comparable testing conditions.
