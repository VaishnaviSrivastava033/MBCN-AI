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

---

### 2. Student Registration Workflow

1. A teacher/admin/therapist creates a new student profile.
2. Data captured includes personal details (name, age, disability), guardian details, and initial program assignment.
3. Once registered, the student record becomes the **central hub** for all future data (assessments, IEP, therapy, reports).


---

### 3. Assessment Workflow

1. Teacher or therapist logs in.
2. Selects a student → adds assessment details (date, type, results, observations).
3. Data is stored and linked to that student’s profile.
4. Assessments can later inform IEP goal creation.


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



---

### 7. Therapy Workflow

1. Therapist logs in → chooses a student → creates a therapy session.
2. Selects **Department** (Speech, Occupational, Physiotherapy).
3. Records activities performed, outcomes, and observations.
4. Sessions are mapped to relevant IEP domains.



---

### 8. Home Management Workflow

1. Teacher/Therapist provides practical home guidance.
2. Guardians receive personalized recommendations (e.g., daily exercises, behavioral tips).
3. Guardians can access this anytime via their limited-access accounts.



---

*This workflow documentation focuses on the practical sequence of interactions between users and modules, making the system’s functionality clear for both developers and stakeholders.*

