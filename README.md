# Maji-Ndogo-Water-Services-Analysis
This project, Maji Ndogo Water Services Analysis, focuses on building and managing a relational database to track, monitor, and improve water accessibility in the fictional region of Maji Ndogo. The database serves as a central hub for field survey data, employee management, and international benchmarking.

**Database Architecture**
The system is built on a MySQL backbone with a schema designed to handle geographic data, environmental quality metrics, and organizational logistics.

Core Data Modules
Geographic Mapping (location): Contains 15,000+ records mapping residential and commercial addresses, categorized by province and location type (Urban vs. Rural).

Human Resources (employee): Manages field surveyors and engineers, tracking their assignments and contact information to coordinate large-scale data collection.

Quality & Safety (water_quality, well_pollution): Tracks subjective quality scores and objective pollution metrics, including biological and chemical contaminant levels (ppm).

Global Benchmarking (global_water_access): Integrates international data (2015–2020) to compare Maji Ndogo’s water infrastructure against other nations in the Sub-Saharan region.

**Technical Implementation**
The project demonstrates expertise in full-cycle database management:

Data Integrity: Implementation of Primary and Foreign Keys to ensure referential integrity between survey visits, locations, and employees.

Metadata Management: Built a comprehensive data_dictionary to document data types, relationships, and business logic for future maintainability.

Normalization: Structured data into distinct entities (Employees, Locations, Sources) to reduce redundancy and optimize query performance.

Advanced Analytics: Facilitates the analysis of water wait times, source reliability (e.g., broken taps vs. functional wells), and regional accessibility disparities.

**Key Project Goals**
Workforce Efficiency: Analyzing employee visit counts to optimize field operations.

Infrastructure Prioritization: Identifying "broken" sources and highly polluted wells for immediate repair.

Policy Support: Providing data-driven insights to help local government reach the same water service standards as top-performing global regions.
