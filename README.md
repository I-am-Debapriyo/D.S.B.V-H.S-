<div align="center">

  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Hosted%20On-GitHub%20Pages-blue?style=for-the-badge&logo=github" alt="GitHub Pages" />
  <img src="https://img.shields.io/badge/License-All%20Rights%20Reserved-orange?style=for-the-badge" alt="License" />

  <br />
  <br />

  #  Digsui Sadhana Banga Vidyalaya (H.S.)
  ### *Empowering Future Stars • Fostering Academic Excellence & Character*

  <p align="center">
    A modern, feature-packed digital portal for <b>Digsui Sadhana Banga Vidyalaya (H.S.)</b>, designed to bridge the gap between students, educators, and parents.
    <br />
    <br />
    <a href="https://i-am-debapriyo.github.io/D.S.B.V-H.S-/">🌐 <strong>Explore the Live Website »</strong></a>
    <br />
    <br />
    <a href="#-key-features">Key Features</a> •
    <a href="#-website-sitemap">Sitemap</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-contact--location">Contact</a>
  </p>

</div>

---

##  Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Website Sitemap](#-website-sitemap)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Future Enhancements](#-future-enhancements)
- [Contact & Location](#-contact--location)

---

##  About the Project

**Digsui Sadhana Banga Vidyalaya (H.S.)** is committed to providing holistic development, academic excellence, and student empowerment. 

This repository contains the complete frontend source code for the official web platform. The platform serves as a central hub for real-time announcements, academic resources, admission forms, extracurricular highlights, and post-Madhyamik guidance from experienced educators.

> *"Digsui Sadhana Banga Vidyalaya (H.S.) didn't just teach my child how to study; it taught them how to think, how to lead, and how to be a compassionate member of the community."*  
> — **Kalyan Mukherjee**, *Proud Parent*

---

##  Key Features

| Feature | Description |
| :--- | :--- |
|  **Academic Portal** | Comprehensive details regarding curriculum, examination schedules, and educational programs. |
|  **Admission Desk** | Step-by-step admission guidelines, downloadable details, and parent portal access. |
|  **Post-Madhyamik Guidance** | Dedicated mentorship section connecting educators with students to guide them on post-Class 10 career paths. |
|  **Interactive Lab Activities** | Showcases hands-on scientific experiments, computer lab programs, and practical learning updates. |
|  **Achievements & Sports** | Celebrates student milestones, athletic tournaments, cultural events, and academic victories. |
|  **Live Program Streaming** | Integration for virtual assemblies, interactive online sessions, and live broadcasts. |
|  **Campus Essentials** | Easy access to daily lunch menus, staff directories, and the official academic calendar. |

---

## 🗺️ Portal Architecture & User Flow

Instead of a basic file list, the portal is organized around user journeys to ensure effortless navigation for students, parents, and educators.

###  User Navigation Flow

```mermaid
graph TD
    A[ Landing Page - index.html] --> B[📚 Academic Hub]
    A --> C[ Student Guidance]
    A --> D[ School Life & Media]
    A --> E[ Administrative Desk]

    B --> B1[Academics.html - Syllabus & Courses]
    B --> B2[calender.html - Exam & Event Schedule]

    C --> C1[Guide.html - Post-Madhyamik Career Counseling]

    D --> D1[sports.html - Athletics & Tournaments]
    D --> D2[lab-activities.html - Science & Computer Labs]
    D --> D3[live-program.html - Virtual Assemblies & Broadcasts]
    D --> D4[achievements.html - Student & Teacher Wall of Fame]
    D --> D5[other-programs.html - Co-curricular Events]

    E --> E1[Admission.html - Guidelines & Parent Portal]
    E --> E2[Food.html - Daily Lunch Menu]
    E --> E3[contactus.html - Staff Directory & Inquiries]
