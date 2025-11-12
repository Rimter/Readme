# 🧠 OctoWare – UEMT Project Team Management System

OctoWare is an **integrated team management platform** designed for university engineering communities.  
It enables structured learning, micro-projects, story point tracking, and performance-based progression for technical teams such as AI, IoT, DevOps, Front-End, and Project Management.

![OctoWare Dashboard](assets/dashboard_preview.png)

---

## 🧭 Table of Contents
- [About the Project](#about-the-project)
- [System Architecture](#system-architecture)
- [Core Features](#core-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 📖 About the Project

**OctoWare** was built to improve engagement and structure within student engineering teams.  
It provides a gamified project tracking and documentation system using **Notion**, **GitHub**, and **automation scripts** for progress visualization.

### 🎯 Objectives
- Bring transparency and structure to multi-team university projects.  
- Encourage self-learning through story-point-based progression.  
- Generate deployable projects that add real value to the community.

---

## 🏗️ System Architecture

```mermaid
graph TD
A[Junior Member] --> B[Notion Dashboard]
B --> C[Story Point Tracker]
C --> D[Promotion System]
B --> E[Project Kanban]
E --> F[Deployment Pipeline]
