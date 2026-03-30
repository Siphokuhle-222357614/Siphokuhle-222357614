# Siphokuhle Gedze - Digital Portfolio

## 🎓 About Me

Welcome to my Work-Integrated Learning (WIL) portfolio. I am a 3rd-year IT student at the Cape Peninsula University of Technology (CPUT), specializing in Application Development. This portfolio showcases my technical skills, entrepreneurial mindset, and readiness for the ICT industry.

- **Name:** Siphokuhle Gedze
- **Student Number:** 222357614
- **Email:** 222357614@mycput.ac.za
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/siphokuhle-gedze-b49683233/)
- **Graduating:** December 2025

---

## 📂 Portfolio of Evidence (POE)

This portfolio is my submission for **Project Presentation III (PRP372S)** . It demonstrates my preparedness for the workplace through curated evidence of my skills, reflections, and professional development.

### Module 1: CV Writing & Personal Branding
A professional CV is a critical tool for securing interviews. My CV highlights my technical skills, academic achievements, and work experience.

- **[View My CV (PDF)]** [`[Insert link to your CV PDF file]`](https://drive.google.com/file/d/1KGt9S1-OSYqgh1XiNNE7vExxVgkMdh5T/view?usp=drive_link)

### Module 2: Mock Interview & Interview Skills
To demonstrate my interview readiness, I completed a mock interview. This video showcases my ability to answer technical, behavioral, and personality-based questions professionally.

- **[Watch My Mock Interview Video]** [`[Insert link to your video file or YouTube link]`](https://drive.google.com/file/d/1Wv7PIrTRUkdGS4Pjx3lNYUxn5J2Ve4JF/view?usp=drive_link)

### Module 3: GitHub Portfolio & Markdown
This digital portfolio itself is a demonstration of my ability to use **Git**, **GitHub Pages**, and **Markdown** to present information in a structured and professional manner.

---

## 🚀 Key Projects

### TymelessTyre – Full Stack Tyre Management System
A web-based application designed to streamline tyre sales, inventory management, and customer appointments for a tyre shop. The system consists of a backend API and a responsive frontend built with Vue.js.

#### Backend Repository
- **[TymelessTyre Backend]** [`[Insert link to your backend repo]`](https://github.com/Siphokuhle-222357614/TymelessTyre)
- **Tech Stack:** Spring Boot, JPA, MySQL, REST API

#### Frontend Repository
- **[TymelessTyre Frontend]** [`[Insert link to your frontend repo]`](https://github.com/Siphokuhle-222357614/TymelessTyre-frontend)
- **Tech Stack:** Vue.js, Vue Router, Axios, HTML, CSS

#### Key Features
- User authentication and role-based access (admin, staff, customer)
- Inventory management (add, update, delete tyres)
- Appointment scheduling for tyre fitting
- Sales order processing
- Customer management

---

## 🧠 Entrepreneurial WIL (eWIL) Component

As part of the curriculum, I have developed a business case and Agile project plan for TymelessTyre.

### Business Case: TymelessTyre
- **[View Full Business Case (PDF)]** [`[Insert link to business case PDF]`](https://github.com/Siphokuhle-222357614/Siphokuhle-222357614/blob/main/business-case.md)

### Agile Project Plan & Logbook
I applied Agile (Scrum) methodology to manage the development of TymelessTyre. Below is an overview of the project plan and a logbook tracking my progress.

- **[View Agile Project Plan]** `[Insert link to your agile plan file or section below]`
- **[View Agile Logbook]** [`[Insert link to your logbook file or section below]`
](https://github.com/Siphokuhle-222357614/Siphokuhle-222357614/blob/main/agile-logbook.md)
*(The logbook is also embedded below for quick reference.)*

---

## 📓 Agile Logbook (Summary)
*(For a detailed logbook, see the separate file linked above)*

### Sprint 1: [e.g., 01–14 July 2025] – Backend Foundation
| Task Board       | Description |
|------------------|-------------|
| **BACKLOG**      | User authentication, appointment booking, sales reporting |
| **IN PROGRESS**  | Database design, REST endpoints for tyres |
| **COMPLETED**    | Spring Boot project setup, Tyre entity, CRUD for tyres |

**Daily Stand-up Sample:**
- *Day 1:* Created backend repo, configured Spring Boot. Next: design database. Impediments: none.
- *Day 2:* Designed JPA entities (Tyre, User, Appointment). Next: implement REST controller for tyres.
- *...*

**Sprint Retrospective:**  
*What went well:* Quick setup, clear requirements.  
*What could be improved:* Need to add unit tests earlier.  
*Action items:* Write service layer tests in next sprint.

### Sprint 2: [15–28 August 2025] – Frontend Setup & Tyre Listing
| Task Board       | Description |
|------------------|-------------|
| **BACKLOG**      | Appointment UI, sales reporting UI |
| **IN PROGRESS**  | Vue component for tyre listing, API integration |
| **COMPLETED**    | Vue project setup, Axios configuration, basic tyre table |

**Sprint Retrospective:**  
*What went well:* Vue CLI made project scaffolding easy.  
*What could be improved:* Need to manage environment variables better.  
*Action items:* Use `.env` for API base URL.

### Sprint 3: [29 August – 11 September 2025] – Authentication & User Management
| Task Board       | Description |
|------------------|-------------|
| **BACKLOG**      | Appointment booking, sales reporting |
| **IN PROGRESS**  | Login page, JWT storage, protected routes |
| **COMPLETED**    | Spring Security with JWT, Vue login component, role-based redirects |

**Sprint Retrospective:**  
*What went well:* Token refresh mechanism works reliably.  
*What could be improved:* Better error messages for login failures.  
*Action items:* Add loading states and form validation.

---

## 💡 Graduate Attributes Reflection

The following reflections connect my work on TymelessTyre to the core graduate attributes of CPUT. *(Please replace these examples with your own actual experiences.)*

### 1. Ubuntu
- **Understanding needs, values, cultures:** When designing TymelessTyre, I considered that some shop staff may not be tech-savvy. I created a clean, intuitive interface with clear labels and confirmation dialogs to minimize errors and respect their time.
- **Interpersonal skills:** During a group discussion about feature priorities, I listened to a teammate’s concern about database performance and we jointly researched an indexing strategy that satisfied both performance and simplicity.
- **Interprofessional skills:** I collaborated with a design student to create a logo and color scheme for TymelessTyre, translating technical constraints (e.g., readability, contrast) into design requirements.

### 2. Knowing, Technological Capability & Foresight
- **Using technology to effect change in society:** TymelessTyre helps small tyre shops digitize their inventory and appointments, reducing manual errors, improving customer service, and supporting local businesses.

### 3. Resilience & Problem-Solving Capability
- **Solving complex problems:** I encountered a CORS error when connecting the Vue frontend to the Spring Boot backend. After researching, I configured Spring Security to allow requests from the frontend URL and resolved the issue within a day.
- **Perseverance:** Debugging a NullPointerException in the appointment service took me several hours. I used systematic logging and step‑through debugging to find that a required field was not being passed from the frontend. I fixed it by adding validation on both ends.
- **Organisational and financial skills:** For this project, I created a simple budget spreadsheet estimating hosting costs (AWS vs. local server) and tracked my time using Trello to ensure I met deadlines.
- **Entrepreneurship, innovation and research:** I researched existing tyre shop management software and found that most are expensive and overly complex for small shops. TymelessTyre aims to fill that gap with an affordable, easy‑to‑use alternative.

### 4. Ethical Capability & Respect
- **Using moral values to make ethical decisions:** I ensured that all user data (customer names, contact details) is stored securely using encryption and that passwords are hashed. I also avoided collecting any unnecessary personal information.
- **Acting on unethical practices:** I noticed a classmate copying code from an online repository without attribution. I discussed with them the importance of academic integrity and offered to help them understand the code so they could write their own version.

---

## 📜 Certifications & Courses
[`[Insert link to your certification image/file]`](https://drive.google.com/file/d/1xtB962-ZQyeNduaKxP1jC-WbYdo6iaOK/view?usp=drive_link)

---

## 📞 Let's Connect!

I am actively seeking a WIL placement for the 2026 academic year. I am open to roles in software development, web development, or system administration. Please feel free to reach out.

- **Email:** 222357614@mycput.ac.za
- **LinkedIn:** [https://www.linkedin.com/in/siphokuhle-gedze-b49683233/](https://www.linkedin.com/in/siphokuhle-gedze-b49683233/)

---
*This portfolio was created as part of the PRP37XS curriculum at CPUT.*
