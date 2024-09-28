# 📝📊 Database Design and Implementation for LockedIn
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?logo=mysql&logoColor=white)

⚡ Database Design, Entity-Relationship Modeling, and SQL Query Implementation ⚡

> [!NOTE]
> This project was conducted by Kaibo Zhang, Malo Thomassin, George Gueorguiev, Sofia Karim, and Aissatou Fanny, students from the Desautels Faculty of Management at McGill University. The study focused on developing a database design for LockedIn, a professional networking platform similar to LinkedIn, and was part of the INSY-437-001 Managing Data & Databases course.

## Overview

In today's business landscape, professional networking platforms like LinkedIn are essential for career advancement and business growth. Our project, LockedIn, aims to create a database-driven platform that caters to the professional networking needs of individuals, streamlining connectivity, job searching, and content sharing. This project emphasizes a simplified, distraction-free user experience by focusing on core functionalities without the clutter often associated with larger platforms.
![image](https://github.com/user-attachments/assets/b68f2581-4a35-47ba-b01a-75e882470606)


## Repo Structure
```
LockedIn_Database_Design/
├── README.md
├── 4_phase1.pdf                            # summary report
├── 4_phase2.txt                            # DDL and DML code for implementation and demonstration
├── 4_phase3.pdf                            # presentation slide
```

### Step-by-step Breakdown

1. <details>
    <summary>Data Collection and Business Processes.</summary>

    - The LockedIn database was designed to support key functionalities inspired by LinkedIn while minimizing distractions. The primary processes include:
        - **User Registration and Profile Creation:** Users create profiles that highlight their education, experience, and skills.
        - **Networking and Connection Building:** Users connect with other professionals based on industry, location, and job title.
        - **Content Creation and Sharing:** Users can post text-based content relevant to their professional field.
        - **Job Search and Recruitment:** Users can search for jobs, and companies can post job openings to recruit candidates.

   </details>

2. <details>
    <summary>Conceptual Model: ERD.</summary>

    - The conceptual model was developed based on the mission objectives of LockedIn, capturing the essential data entities and their relationships. Below is the Entity-Relationship Diagram (ERD) illustrating the conceptual design of the database.

    ![image](https://github.com/user-attachments/assets/c532dd46-01f9-46d3-ab3a-46fa5628d879)


   </details>

3. <details>
    <summary>Relational Model.</summary>

    - The relational model was constructed to define the attributes of each entity and their interconnections. The model includes tables such as `userProfile`, `education`, `experience`, `company`, `job`, and others, designed to support the core functions of the LockedIn platform.

   </details>

4. <details>
    <summary>Physical Implementation and SQL Queries.</summary>

    - The relational schema was implemented using MySQL, with tables physically created and tested on DB Fiddle. The database supports multiple queries categorized by user focus (candidates, companies, and LockedIn management). Sample queries include data retrieval for user profiles, job searches, and interaction tracking. The database is physically implemented on `db-fiddle` and can be found [here](https://www.db-fiddle.com/f/gp3nd3ctRAVvGu5Yqts1r4/21).

   </details>

5. <details>
    <summary>Challenges and Future Implementations.</summary>

    - Challenges included defining the project scope, finalizing the ERD through iterative design, and ensuring the coherence of dummy data across interrelated tables. Future objectives include adding private messaging features, expanding the dataset for more realistic query testing, and integrating an API to allow third-party platform integration.

   </details>

---


