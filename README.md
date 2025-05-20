# 📊 Querying a Data Warehouse in Microsoft Fabric

## 🎯 Objective  
The goal of this lab was to explore how to query a data warehouse within Microsoft Fabric using its integrated SQL query editor. This exercise focused on gaining analytical insights from preloaded data and applying best practices for data consistency, modeling, and transformation — all within a modern data warehousing environment.

---

## 🔧 Steps Performed

1. **Workspace Creation**  
   A new workspace was created in Microsoft Fabric with trial capacity enabled to host the data resources.

2. **Sample Data Warehouse Setup**  
   A pre-populated sample data warehouse named `sample-dw` was created, containing trip-related data for analysis.

3. **Query Execution**  
   Several SQL queries were executed to:
   - Analyze total trips and revenue by month
   - Calculate average trip durations and distances by day
   - Identify top pickup and drop-off cities

4. **Data Consistency Checks**  
   The dataset was checked for anomalies such as:
   - Trips with durations exceeding 24 hours
   - Trips with negative durations (which were deleted)

5. **View Creation for Reusability**  
   A filtered query for January trips was saved as a reusable view named `vw_JanTrip` to enable easier reporting.

6. **Cleanup**  
   Once the exploration was complete, the workspace was deleted to release resources.

---

## 📘 What I Learned

- Gained hands-on experience with Microsoft Fabric’s data warehouse environment and SQL query editor.
- Understood how to retrieve analytical insights through groupings, aggregations, and joins.
- Learned the importance of validating and cleaning data for reliable results.
- Practiced creating reusable views for filtered datasets to support reporting and dashboarding.
- Improved my understanding of semantic models integrated with Power BI in DirectLake mode.

---

This lab provided a practical, end-to-end scenario for querying and managing data in a modern warehouse, using only the tools and features available within Microsoft Fabric.

---

## Screenshots

<img width="1398" alt="1" src="https://github.com/user-attachments/assets/c1225ed3-4d71-44d2-8495-7be5416df1d8" />

<img width="1249" alt="2" src="https://github.com/user-attachments/assets/15b85c16-363f-440d-9e74-22f370795730" />

<img width="1145" alt="3" src="https://github.com/user-attachments/assets/96b5e335-93f0-4a8a-b20f-ea4247b1879e" />

<img width="1035" alt="4" src="https://github.com/user-attachments/assets/ee5bc077-067c-4baf-8f50-981a5497af0a" />

<img width="1279" alt="5" src="https://github.com/user-attachments/assets/55fcf651-3fc4-459f-9cb2-42f8cfe06743" />

<img width="1223" alt="6" src="https://github.com/user-attachments/assets/58af892c-c78a-4736-ad5c-0343f268ddeb" />

<img width="1308" alt="7" src="https://github.com/user-attachments/assets/8b601cc1-5f1b-4bf8-a39e-3b62e8371ab1" />

<img width="1379" alt="8" src="https://github.com/user-attachments/assets/a3a59570-de4e-496f-81c6-e10286f5a817" />


