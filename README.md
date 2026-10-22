# XBody EMS Studio & Professional Computing Portfolio

**Candidate:** Nicoleta Loredana Badoi  
**Programme:** FdSc Computing (Elizabeth School of London / NCG, Leeds)  
**Module:** S2-PFD200 – Professional Development (Portfolio Task 1, 2 & 3)  
**LinkedIn:** [linkedin.com/in/nicoleta-badoi-38495424b](https://www.linkedin.com/in/nicoleta-badoi-38495424b)  

---

## 1. Project Overview
This repository contains the full source code and technical implementation for the **XBody EMS Studio Web Application**, developed to fulfill Task 2 (Project Development) and Task 3 (Digital Portfolio Creation) of module S2-PFD200.

The application serves as a commercial client acquisition and booking portal for a Leeds-based Electro Muscle Stimulation (EMS) fitness studio. It integrates a high-performance, dark-mode front end with a secure Python Flask back end, automated contraindication pre-screening, and SQLite appointment persistence.

---

## 2. Core Technical Features
- **Responsive Front End:** Implemented using semantic HTML5, modern CSS3 (Flexbox/Grid), and vanilla JavaScript DOM manipulation with 100% custom SVG iconography.
- **Medical Contraindication Pre-Screening:** Enforces safety guidelines by preventing online bookings for clients with medical contraindications (e.g., cardiac pacemakers, circulatory disorders) until manual GP clearance is supplied.
- **Appointment Scheduling Engine:** Prevents double-booking collisions by querying existing SQLite records prior to confirmation.
- **Member Access Terminal:** Provides session-based authentication for studio members and administrators (`/login` and `/dashboard`).
- **Protocol Pricing Matrix:** Interactive 3-tier membership structure with direct modal synchronization.

---

## 3. Technology Stack
- **Languages:** Python 3, HTML5, CSS3, JavaScript (ES6+), SQL
- **Framework:** Flask (WSGI web server)
- **Database:** SQLite3
- **Standards:** WCAG 2.1 Contrast & Accessibility, UK GDPR & Health Data Compliance

---

## 4. Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/xbody-ems-studio.git
   cd xbody-ems-studio