# Intelligent IP Subnetting for a Multi-Department University Network

## Overview

This project presents a strategic and scalable IP addressing and subnetting scheme for a mid-sized university. The design focuses on optimal address allocation, future scalability, and minimal wastage using **Variable Length Subnet Masking (VLSM)**. Each department receives a tailored subnet based on size and growth expectations.

The plan was developed as part of the **Complex Computing Problem (CCP)** for the **Computer Networks (CC251)** course at the **University of Management and Technology (UMT), Lahore**, Spring 2025.

---

## Objectives

- Efficiently utilize the provided IP block `192.168.0.0/22`
- Customize subnet sizes based on departmental needs
- Avoid IP wastage using VLSM
- Allow future network expansion through reserved address space
- Ensure logical segmentation for secure and manageable networking

---

## Departments Covered

- Computer Science (CS)
- Electrical Engineering (EE)
- Mechanical Engineering (ME)
- Civil Engineering
- Administration
- Library
- Faculty Block
- Hostel

---

## Subnetting Strategy

- **CIDR Block Used:** `192.168.0.0/22`
- **Method:** VLSM (Variable Length Subnet Masking)
- **Allocation Based on:** Department size and anticipated growth
- **Reserved Ranges:** For future departments and scalability

Each department’s subnet includes:
- Subnet ID
- Subnet Mask
- Usable IP Range
- Broadcast Address
- Number of Hosts

A complete subnetting table is included in the documentation.

---

## Key Outcomes

- Structured and scalable subnet distribution
- Reduced IP address wastage
- Logical separation of network domains
- Flexibility for future departmental additions

---
