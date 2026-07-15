# Smart City Database Management System

## Project Overview
This database system is designed to manage and analyze critical data within a smart city environment. It structures and connects information regarding **Citizens**, **Districts**, **Buildings**, and **Services** to optimize city administration and resource allocation.

## Course Details
* **Course Code & Name:** DPR400210 Database Programming
* **Instructor:** Eric Maniraguha
* **Student ID:** 32583/2025
* **Academic Year:** 2025-2026

## Database Schema & ERD
The database consists of four main relational tables designed in 3rd Normal Form (3NF):
1. **Districts**: Stores unique city zones.
2. **Citizens**: Manages demographic data of individuals linked to districts.
3. **Buildings**: Tracks infrastructure assets and their locations.
4. **Services**: Outlines services (e.g., Health, Education) offered within specific buildings.

## Advanced PL/SQL Features Implemented
* **Triggers & Auditing:** Automated system to log new registrations for security and auditing purposes.
* **Procedures with Exception Handling:** Robust citizen registration mechanism preventing invalid district IDs or duplicated keys.
* **Functions & Cursors:** Performance-optimized cursor function to calculate the total population of any given district.
* **Packages:** Modular encapsulation of core database functions and procedures.
