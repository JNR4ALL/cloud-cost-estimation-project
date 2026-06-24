# Azure vs AWS Cost Comparison Learning Program

## Overview

This project compares the estimated monthly and annual cost of hosting a small web application on Amazon Web Services (AWS) and Microsoft Azure.

## Application Requirements

* 1 Virtual Machine
* 2 vCPUs
* 4 GB RAM
* 100 GB SSD Storage
* Managed Database Service
* 200 GB Monthly Data Transfer
* Linux Operating System

## Service Equivalency Mapping

| AWS               | Azure                  |
| ----------------- | ---------------------- |
| Amazon EC2        | Azure Virtual Machines |
| Amazon EBS        | Azure Managed Disk     |
| Amazon RDS        | Azure SQL Database     |
| AWS Data Transfer | Azure Bandwidth        |

## Cost Comparison Summary

| Provider | Monthly Cost | Annual Cost |
| -------- | ------------ | ----------- |
| AWS      | $814.64      | $9,775.68   |
| Azure    | $452.68      | $5,432.16   |

## Key Findings

* Azure was approximately 44.43% less expensive than AWS for this workload.
* Database pricing had the largest impact on total cost.
* Both providers offer discount mechanisms such as Reserved Instances and long-term commitment plans.

## Repository Contents

* Cost Comparison Report
* AWS Pricing Calculator Screenshots
* Azure Pricing Calculator Screenshots
* Cost Analysis
* Business Context Summary
* Supporting Documentation

## Conclusion

The analysis indicates that Microsoft Azure provides a lower overall cost for the selected workload while maintaining comparable functionality and scalability.
