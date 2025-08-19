# 📘 **Priject_Name** -> "BidyaSetu"

> **BidyaSetu (বিদ্যা সেতু)** — *Bridge of Knowledge*. A unified school app connecting **Students, Parents, Teachers, and Admins** with attendance, classwork, results, notices, e-library, downloads, reports, and feedback.

---

## 👨‍🏫 Course Information
- **Course Teacher:** Md. Sadi Al Huda  
- **Designation:** Lecturer, Dept. of CSE  
- **Institution:** Khwaja Yunus Ali University

## 👥 Team Members
- Md. Nasir Uddin  
- Mst. Sharmin Khatun Sultana  
- Mst. Nusrat Zahan

---

## 🚀 Key Features
- 🔐 **Auth**: Sign Up, Sign In, Forget Password, Logout  
- 🏠 **Dashboard**: Profile, Attendance, Classwork, Exam, Results, Timetable, Activities  
- 📢 **Notices**: School/teacher announcements  
- 📚 **E-Library**: NCTB books, curated videos  
- ⬇️ **Download Center**: Books, assignments, videos  
- 📝 **Feedback**: Student/parent messages to teacher/admin  
- 📊 **Reports & Analytics**: Attendance & performance insights  
- ⚙️ **Settings**: Preferences, notifications  
- 🏫 **About School**: Vision, mission, contact

---

## 🎭 User Roles & Permissions (RBAC)
- **Student**: View dashboard, attendance, classwork, results, timetable, e-library; submit feedback; download materials.  
- **Parent**: View child’s attendance, results, reports, timetable; receive notices; submit feedback.  
- **Teacher**: Mark attendance; upload classwork, results, study materials; post notices; view reports.  
- **Admin**: Manage users, notices, library & downloads, reports, school info; respond to feedback.

---

## 🧱 Proposed Tech Stack
**Mobile (recommended):** Flutter  
**Backend:** Firebase (Auth, Firestore, Storage) or Node.js + REST  
**Database:** Firestore / MySQL  
**Auth:** Firebase Auth / JWT  
**Notifications:** Firebase Cloud Messaging (FCM)  
**Version Control:** Git & GitHub

---

## 📂 Suggested Project Structure
BidyaSetu/
├─ lib/ # Flutter source
│ ├─ screens/ # UI screens
│ ├─ widgets/ # Reusable components
│ ├─ models/ # Data models
│ ├─ services/ # API/DB services
│ ├─ providers/ # State management (e.g., Riverpod/Provider)
│ └─ main.dart # App entry
├─ assets/ # Images, icons, fonts
├─ docs/ # Diagrams & docs (UML, SRS, activity diagrams)
│ ├─ use-cases/ # Use case diagrams per role
│ ├─ activity/ # Activity diagram(s)
│ └─ er/ # ER diagram
├─ .github/ # Workflows, issue templates
├─ pubspec.yaml
└─ README.md
