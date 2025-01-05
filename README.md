# Supply-leftover-food-to-poor
This project aims to streamline the process of leftover food distribution using salesforce.
1. Project Overview
This project aims to streamline the process of leftover food distribution using Salesforce.

Goal: Efficiently distribute leftover food to reduce food waste and address hunger.
Impact: Reduce food waste, address hunger, and improve the management of food distribution points, tasks, and volunteers.
Technology: Salesforce tools manage records, workflows, and data visualization, ensuring seamless operations.
2. Objectives
The project defines measurable goals for societal and operational improvement.

Business Goals
Address societal issues like food waste and hunger.
Enhance operations, transparency, and accountability.
Specific Outcomes
Deliverables include:

Custom objects: Drop-Off Point, Task, Volunteer, and Execution Detail.
Reports and dashboards for operational insights.
Automated workflows for efficiency.
3. Custom Objects
Drop-Off Point
Purpose: Tracks food drop-off locations for effective management.
Fields:
Name, Location Details, Distance, Venue (lookup to Venue object).
Task
Purpose: Manages and tracks tasks related to food distribution.
Fields:
Name, Date, Rating, Drop-Off Point (lookup), Sponsored By (lookup).
Volunteer
Purpose: Tracks individuals involved in food distribution.
Fields:
Name, Contact Email, Contact Phone, Assigned Tasks (related list).
Execution Detail
Purpose: Captures detailed food distribution activity information.
Fields:
Name, Linked Volunteer (master-detail), Linked Task (master-detail), Additional Details.
4. Key Features
Custom Objects: Store essential data for food distribution management.
Relationships:
Master-Detail: Strict dependencies (e.g., Execution Detail links to Volunteer or Task).
Lookup: Flexible associations (e.g., Drop-Off Point linked to Venue).
Flows: Automates data entry for venues and other processes.
Dashboards: Visualize drop-off points, task completion rates, and volunteer participation.
5. Testing and Validation
Unit Testing: Ensures all components (Apex triggers, workflows) operate correctly.
UI Testing: Verifies user interface usability and correctness.
6. Key Scenarios Addressed
Food Distribution Coordination: Tracks food drop-off points and related tasks.
Volunteer Management: Links tasks to volunteers for accountability.
Data Visibility: Dashboards and reports improve decision-making and transparency.
7. Conclusion
The Salesforce Food Connect App successfully enhances food distribution efficiency by leveraging Salesforce's capabilities. It improves coordination and transparency in food donation efforts, addressing food insecurity and maximizing resource utilization.

