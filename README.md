# Hi, I'm P. S. Prashanth 👋

### Software Engineering Student | Full-Stack Developer | AI & Cloud Enthusiast

[LinkedIn](linkedin.com/in/prashanth-p-s-2988a7387) • [GitHub](github.com/psprashanth25)

---

## Introduction

I am an Integrated M.Tech Software Engineering student at **VIT-AP University**, graduating in **2027**, with a current CGPA of **8.61 / 10**. I focus on full-stack web development, software engineering fundamentals, RESTful API architecture, and applying AI and cloud technologies to build practical, scalable software.

- 🎓 **Education:** Integrated M.Tech in Software Engineering at VIT-AP University (2022 – 2027)
- 💻 **Core Focus:** Full-Stack Web Development, System Architecture, and RESTful APIs
- 🌱 **Current Learning:** React, Node.js, Express.js, TypeScript, Java, and MongoDB
- 🤖 **Interests:** Machine Learning, Computer Vision, Generative AI, and Cloud Infrastructure
- 🎯 **Looking for:** Software engineering, full-stack, and backend internship opportunities

---

## Education

| Qualification | Stream / Program | Institution | Board / University | Year | Marks / CGPA |
|---|---|---|---|---|---|
| **Integrated M.Tech** | Software Engineering | VIT-AP University | VIT-AP University | 2027 (Expected) | **8.61 / 10 CGPA** |
| **Intermediate (Class XII)** | MPC (Mathematics, Physics, Chemistry) | Sai Sri Chaitanya Junior College,Palamaner | BIEAP | 2022 | **861 / 1000 — A Grade** |
| **SSC (Class X)** | General | Sri Sarada E.M. High School, Palamaner | BSEAP | 2020 | **577 / 600 — First Division** |

---

## Technical Skills

- **Languages:** Java, JavaScript, Python, SQL
- **Frontend:** React.js, TypeScript, HTML5, CSS3, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js, REST APIs, FastAPI
- **Databases:** MongoDB, Relational Databases (SQL)
- **Core Concepts:** Object-Oriented Programming (OOP), Data Structures & Algorithms, Database Management Systems (DBMS), Operating Systems, Computer Networks, Agile / SDLC
- **AI / ML:** PyTorch, YOLOv5, XGBoost, Computer Vision (OpenCV), Streamlit
- **Tools & Platforms:** Git, GitHub, Render, Vercel, Postman

---

## Featured Projects

### Government Scheme Checker

A full-stack AI-enabled web application designed to help Indian citizens discover government welfare schemes, understand complex requirements, and evaluate their eligibility based on socioeconomic parameters.

- **Problem Solved:** Eliminates information asymmetry, fragmented ministerial portals, language barriers, and complex qualification criteria across 115+ Central and State welfare programs.
- **Application Workflow:** A guided 6-step questionnaire capturing personal, social category, economic status, education level, geographic location, and targeted preferences (such as BPL and minority status) with automatic draft saving to `localStorage`.
- **Dual Eligibility Engine:** Evaluates citizen profiles through a high-performance Python FastAPI microservice powered by an XGBoost classification model (trained on 345,000 synthetic citizen profiles, achieving 99.86% test accuracy) alongside a resilient deterministic client-side rule evaluation engine for offline and fallback evaluation.
- **AI Scheme Assistant:** Context-aware chatbot powered by an OpenAI API proxy (ChatGPT-4o-mini) delivering real-time guidance on required documents, program benefits, and application steps with quick topic pills.
- **Output & Reporting:** Provides instant eligibility score breakdown, categorized recommendations (Fully Eligible vs. Partially Eligible), direct official application links, and one-click PDF eligibility report generation.

**Technologies:**
- **Frontend:** React 19, TypeScript, Vite, Tailwind CSS v4, React Router, i18next (multilingual support across English, Hindi, Telugu, Kannada, Malayalam, and Tamil)
- **Backend:** Node.js, Express.js, REST APIs, Python, FastAPI
- **Machine Learning & AI:** XGBoost Classifier, OpenAI API proxy (ChatGPT-4o-mini)
- **Database:** MongoDB (Mongoose)
- **Document Generation:** jsPDF

**Project Link:** [View Repository](https://github.com/psprashanth25/Government-Scheme-Checker)

---

### Budget Buddy

A modern, full-stack personal finance and pocket-money management web application tailored specifically for college and hostel students.

- **Problem Solved:** Solves the real-world financial challenges of campus living by balancing irregular pocket-money transfers from parents, recurring living costs, and maintaining a bank balance buffer to prevent overdrafting.
- **Key Capabilities:** Features a student-centric financial ledger with dual-mode analytics (Pocket Money tracking vs. Total Bank Balance protection), hierarchical expense categorization with protected default categories, date-restricted transaction entry validation, and interactive category distribution charts.
- **Statements & Security:** Executive-grade printable A4 PDF statement generation, secure JWT authentication with 6-digit email OTP verification via Nodemailer, and continuous API health check monitoring.

**Technologies:**
- **Frontend:** React 19, Vite, Tailwind CSS, Recharts, jsPDF (Deployed on Vercel)
- **Backend:** Node.js 20+, Express.js 5, JWT Authentication, Nodemailer (Deployed on Render)
- **Database:** MongoDB Atlas (Mongoose)

**Highlights:**
- Dual-mode financial ledger with automated balance tracking and spending guard
- Interactive Recharts spending distributions and monthly audit trail
- Client-side executive-grade printable A4 PDF statement export

**Project Link:** [View Repository](https://github.com/psprashanth25/budgetbuddy)

---

### Object Detection System

An end-to-end, real-time computer vision application designed for multi-class object localization, classification, and tracking across static images, pre-recorded video files, and live webcam streams.

- **Deep Learning Engine:** Utilizes YOLOv5 neural network architecture with PyTorch for low-latency inference on the 80 common object categories of the MS COCO dataset.
- **Multi-Source Pipeline:** Automated inference pipeline supporting static image uploads (`.jpg`, `.jpeg`, `.png`), video file processing (`.mp4`, `.avi`, `.mov`, `.mkv`), and low-latency live webcam streams.
- **Interactive Tuning & Telemetry:** Dynamic sidebar controls to adjust Confidence and IoU (Non-Maximum Suppression) thresholds on the fly without restarting the service, alongside live telemetry metrics (FPS, inference latency in milliseconds, bounding-box coordinate breakdown).

**Technologies:**
- **Deep Learning & CV:** Python, PyTorch, YOLOv5 (Ultralytics), OpenCV, Pillow
- **Web Interface:** Streamlit
- **Data Analytics:** Pandas, NumPy

**Highlights:**
- Real-time multi-class object detection across images, video files, and live webcam feeds
- Dynamic hyperparameter tuning (Confidence and IoU thresholds) during live execution
- Performance telemetry with tabular bounding-box coordinate breakdown and single-click media export

**Project Link:** [View Repository](https://github.com/psprashanth25/Object-Detection-System)

---

### Pulse Analytics

A performance-oriented client-side analytics dashboard engineered to slice-and-dice, filter, aggregate, and visualize tens of thousands of records entirely within the browser while maintaining a smooth 60fps interaction lifecycle.

- **Core Engineering:** Solves client-side main thread UI degradation using a single-pass O(N) combined filtering and reduction algorithm with O(1) hash map accumulators, eliminating repeated multi-pass array sweeps.
- **DOM Virtualization:** Integrates TanStack Table and TanStack Virtual to mount only ~25 visible rows into the DOM out of 60,000+ in-memory records, eliminating memory bloat and scroll stutter.
- **Interactive Analytics:** Multi-factor filtering (date windows, categories, regions), 300ms debounced search, period-over-period KPI comparisons, live browser telemetry (heap footprint, filter latency), and high-contrast dark/light theme switching.

**Technologies:**
- **Frontend Architecture:** React 19, TypeScript, Vite, Tailwind CSS, React Router
- **Data & Tables:** TanStack Table, TanStack Virtual, Recharts
- **Icons & UI:** Lucide React (Deployed on Vercel)

**Highlights:**
- Single-pass reduction algorithm processing 60,000+ records in client memory at 60fps
- Virtualized data grid with multi-column sorting, row density switcher, and CSV export
- In-browser benchmark runner profiling real-time CPU execution latency

**Project Link:** [View Repository](https://github.com/psprashanth25/pulse-analytics)

---

## Certifications

A consolidated overview of verified professional certifications and technical programs:

| Certification | Issuing Organization | Issue Date | Expiration Date | Certificate |
|---|---|:---:|:---:|:---:|
| **Oracle Cloud Infrastructure 2025 Certified Generative AI Professional** | Oracle (Oracle University) | October 3, 2025 | October 3, 2027 | [View PDF](certificates/oracle_genai-1_clean_landscape.pdf) |
| **Oracle Cloud Infrastructure 2025 Certified Foundations Associate** | Oracle (Oracle University) | October 31, 2025 | October 31, 2027 | [View PDF](certificates/oracle_foundations-1_clean_landscape.pdf) |
| **Hashgraph Developer Course** | The Hashgraph Association / Hedera | March 9, 2026 | — | [View PDF](certificates/hedera-1_clean_landscape.pdf) |
| **Web Development Internship Program** | Rinex Technologies (E-Cell IIT Bhubaneswar) | July 5, 2024 | August 31, 2024 | [View PDF](certificates/rinex_internship-1_clean_landscape.pdf) |
| **Web Development Course (Grade A+)** | Rinex Organization (Skill India & NSDC) | July 5, 2024 | — | [View PDF](certificates/rinex_completion-1_clean_landscape.pdf) |
| **Web Development Course (Achievement)** | Rinex (Google for Education Partner) | July 5, 2024 | — | [View PDF](certificates/rinex_course-1_clean_landscape.pdf) |

> Detailed credential IDs, descriptions, and verification references are also maintained in [CERTIFICATIONS.md](CERTIFICATIONS.md).

---

## Certificate Documents

Official certificate documents are stored directly in the repository's `certificates/` folder:

- [Oracle Generative AI Professional Certificate](certificates/oracle_genai-1_clean_landscape.pdf)
- [Oracle Cloud Foundations Certificate](certificates/oracle_foundations-1_clean_landscape.pdf)
- [Hedera Certificate](certificates/hedera-1_clean_landscape.pdf)
- [RINEX Web Development Course Certificate](certificates/rinex_course-1_clean_landscape.pdf)
- [RINEX Internship Certificate](certificates/rinex_internship-1_clean_landscape.pdf)
- [RINEX Course Completion Certificate](certificates/rinex_completion-1_clean_landscape.pdf)

---

## Connect With Me

- **LinkedIn:** [LinkedIn](linkedin.com/in/prashanth-p-s-2988a738)
- **GitHub:** [GitHub](github.com/psprashanth25)
