# MBCN AI — Workflow

> **Purpose:** MBCN AI is a customized platform for tracking the full student journey (learning, growth, skills, therapy, and home management) for Mata Bhagwanti Chanda Niketan (MBCN) — a school for specially-abled students.

---

## 📌 High-Level Workflow

The workflow of MBCN AI revolves around **role-based access**, **student-centered data management**, and **modular progression** across assessments, planning, execution, and reporting.

### 1. Custom User Authentication & Role Assignment

* Custom users register or log in.
* The system assigns role-based permissions:

  * **Super Admin** → Full CRUD (Create, Read, Update, Delete).
  * **Admin** → CRU (no delete).
  * **Teacher** → Manage students, assessments, IEPs, progress reports.
  * **Therapist** → Manage therapies, update progress, contribute to IEPs.
  * **Guardian** → Mostly read-only access, guided by home management modules.

    ![WhatsApp Image 2025-08-14 at 17 39 52_d8ad257b](https://github.com/user-attachments/assets/23d7c6cb-6c03-4699-a834-058f67f754b9)


---

### 2. Student Registration Workflow

1. A teacher/admin/therapist creates a new student profile.
2. Data captured includes personal details (name, age, disability), guardian details, and initial program assignment.
3. Once registered, the student record becomes the **central hub** for all future data (assessments, IEP, therapy, reports).

![WhatsApp Image 2025-09-11 at 11 54 13_626f9703](https://github.com/user-attachments/assets/c8b948de-0d57-4e6e-a2e4-5331abe924f0)


---

### 3. Assessment Workflow

1. Teacher or therapist logs in.
2. Selects a student → adds assessment details (date, type, results, observations).
3. Data is stored and linked to that student’s profile.
4. Assessments can later inform IEP goal creation.

   ![WhatsApp Image 2025-09-11 at 11 57 00_a0fbd502](https://github.com/user-attachments/assets/0d7e6b70-168a-4fbd-b3e8-6ff568551abc)




---

### 4. IEP (Individualized Educational Plan) Workflow

1. Teacher/Therapist reviews assessment results.
2. Creates IEP goals by selecting from predefined domains (e.g., Gross Motor, Communication, Reading Skills).
3. Each goal includes:

   * Target skill/behavior
   * Evaluation criteria
   * Timeline
   * Percentage/marks for progress
4. Goals are continuously updated as progress is made.

   ![WhatsApp Image 2025-09-11 at 11 54 31_7b5ab41c](https://github.com/user-attachments/assets/c430733b-70ab-4548-a885-81041fa84b63)



---

### 5. Program Workflow

1. Admin/Teacher assigns the student to a program type (e.g., Academic, Autism, VTC) and level (e.g., Pre-Academic, Functional Academic).
2. Programs define the **context** in which IEPs and therapies operate.
3. Students may transition between programs as they grow.



---

### 6. Progress Report Workflow

1. Teacher/Admin generates periodic reports.
2. Report aggregates:

   * Assessments
   * IEP goal progress
   * Attendance
   * Teacher feedback
3. Reports are shared with guardians and stored in the student’s record.

   ![WhatsApp Image 2025-09-11 at 11 55 58_8554eb89](https://github.com/user-attachments/assets/2853030d-c15f-48d6-a6e3-c59906267d49)




---

### 7. Therapy Workflow

1. Therapist logs in → chooses a student → creates a therapy session.
2. Selects **Department** (Speech, Occupational, Physiotherapy).
3. Records activities performed, outcomes, and observations.
4. Sessions are mapped to relevant IEP domains.

   ![WhatsApp Image 2025-09-11 at 11 55 07_c55a5fa9](https://github.com/user-attachments/assets/e46f7161-8576-4ffe-b82c-4d5f757c5cd1)




---

### 8. Home Management Workflow

1. Teacher/Therapist provides practical home guidance.
2. Guardians receive personalized recommendations (e.g., daily exercises, behavioral tips).
3. Guardians can access this anytime via their limited-access accounts.



---

*This workflow documentation focuses on the practical sequence of interactions between users and modules, making the system’s functionality clear for both developers and stakeholders.*

