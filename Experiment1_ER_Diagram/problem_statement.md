# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario : City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
*Paste or attach your diagram here*  
![ER Diagram](er_diagram_library.png)

### Entities and Attributes


| **Entity**                           | **Attributes**                                                              |
| ------------------------------------ | --------------------------------------------------------------------------- |
| **Member**                           | MemberID (PK), Name, Email, Phone, Address                                  |
| **Book**                             | BookID (PK), Title, Author, Category, AvailabilityStatus                    |
| **Loan** (Associative)               | LoanID (PK), LoanDate, ReturnDate, DueDate, FineAmount                      |
| **Event**                            | EventID (PK), EventName, EventDate, EventType (e.g., Cultural, Author Talk) |
| **Speaker/Author**                   | SpeakerID (PK), Name, Profession (Author, Scholar, Artist, etc.)            |
| **Room**                             | RoomID (PK), RoomName, Capacity, Purpose (Study / Event)                    |
| **Event Registration** (Associative) | RegistrationID (PK), RegistrationDate                                       |


### Assumptions
- 
- 
- 

---


## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
