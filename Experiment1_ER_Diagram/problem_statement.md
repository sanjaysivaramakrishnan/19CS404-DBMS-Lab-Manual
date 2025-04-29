# Experiment 1: Entity-Relationship (ER) Diagram

## 🎯 Objective:
To understand and apply the concepts of ER modeling by creating an ER diagram for a real-world application.

## 📚 Purpose:
The purpose of this workshop is to gain hands-on experience in designing ER diagrams that visually represent the structure of a database including entities, relationships, attributes, and constraints.

---

## 🧪 Choose One Scenario:

### 🔹 Scenario 1: University Database
Design a database to manage students, instructors, programs, courses, and student enrollments. Include prerequisites for courses.

**User Requirements:**
- Academic programs grouped under departments.
- Students have admission number, name, DOB, contact info.
- Instructors with staff number, contact info, etc.
- Courses have number, name, credits.
- Track course enrollments by students and enrollment date.
- Add support for prerequisites (some courses require others).

---

### 🔹 Scenario 2: Hospital Database
Design a database for patient management, appointments, medical records, and billing.

**User Requirements:**
- Patient details including contact and insurance.
- Doctors and their departments, contact info, specialization.
- Appointments with reason, time, patient-doctor link.
- Medical records with treatments, diagnosis, test results.
- Billing and payment details for each appointment.

---

## 📝 Tasks:
1. Identify entities, relationships, and attributes.
2. Draw the ER diagram using any tool (draw.io, dbdiagram.io, hand-drawn and scanned).
3. Include:
   - Cardinality & participation constraints
   - Prerequisites for University OR Billing for Hospital
4. Explain:
   - Why you chose the entities and relationships.
   - How you modeled prerequisites or billing.

# ER Diagram Submission - Student Name : AGILAN J

## Scenario Chosen:
University / Hospital (choose one)

## ER Diagram:
![Screenshot 2025-03-08 135120](https://github.com/user-attachments/assets/85390f08-ef17-4e95-83e1-62dc9678c768)

![Screenshot 2025-03-08 144402](https://github.com/user-attachments/assets/e31f263d-08c0-4942-96f4-ce25c9a5488b)



## Entities and Attributes:
- Entity1: Student_ID (Primary Key), Name, DOB, Address, Email, Phone
- Entity2: Program_ID (Primary Key), Program_Name, Duration
...

## Relationships and Constraints:
- Relationship1 (Cardinality, Participation)
- Relationship2 (Cardinality, Participation)
...

## Extension (Prerequisite / Billing):
This ER diagram models a university academic system encompassing key entities such as Student, Program, Course, Instructor, and Department. It captures relationships like students enrolling in programs, registering for courses, and instructors teaching courses. Each course belongs to a program, and each program is governed by a department. While the diagram effectively represents academic structures and associations, it does not currently include models for prerequisites or billing. Prerequisites—courses required before enrolling in another—can be modeled using a recursive relationship on the Course entity. Billing, which includes tuition or fee payments by students, can be represented by introducing a new Payment entity linked to Student or Register. These additions would enhance the system by supporting academic progression rules and financial tracking.

## Design Choices:
In designing this ER diagram, the entities and relationships were chosen to reflect the core components of an academic institution. The primary entities include Student, Program, Course, Instructor, and Department, as they represent essential real-world objects in a university setting. Relationships such as Enrolls, Register, and Teaching were included to model student participation in programs, course registrations, and instructor-course assignments respectively. The assumption is that a student can enroll in only one program at a time, but can register for multiple courses. Each course belongs to one program and is taught by one or more instructors. The Grouped relationship links programs to departments to indicate administrative oversight. Attributes like Credits, Experience, and contact information were added to support practical use cases such as course load calculation and communication. The design prioritizes normalization, avoiding redundancy while capturing meaningful academic relationships.
## RESULT
This ER diagram shows how students, courses, programs, and instructors are connected in a college system. It uses simple relationships based on how things work in real life, like students joining programs and registering for courses.
