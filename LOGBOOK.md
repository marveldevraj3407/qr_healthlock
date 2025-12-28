# PROJECT LOG BOOK

## Weekly Activity Log

### Week 1: Group Establishment
**Date:** 28/07/2025 - 02/08/2025
* **Activities Completed:**
    * Formed project group of 5 members and assigned roles (UI design, Backend, Database, Documentation).
    * [cite_start]Discussed project objective: Developing a system to store medical records digitally using QR codes[cite: 392].
    * [cite_start]Created GitHub repository to store all project files and track progress[cite: 393].
* **Next Plan:** Finalize the project topic and perform existing system survey.
* **Guide Interaction:** Initial discussion with guide regarding the hospital management domain and team structure.

### Week 2: Topic Selection
**Date:** 04/08/2025 - 16/08/2025
* **Activities Completed:**
    * [cite_start]Finalized topic: 'Document Storing Management System Using QR Code For Hospital'[cite: 402].
    * [cite_start]Defined key goals: Reduce paper usage, prevent loss of reports, and provide quick access via QR[cite: 403].
    * Conducted survey of existing paper-based systems and identified limitations.
* **Next Plan:** Start requirement analysis and identify modules.
* [cite_start]**Guide Interaction:** Guide approved the topic and emphasized the importance of data security in hospital systems[cite: 408].

### Week 3: Requirements Analysis & System Overview
**Date:** 18/08/2025 - 23/08/2025
* **Activities Completed:**
    * [cite_start]Identified three main modules: Admin, Patient, and Doctor[cite: 413].
    * [cite_start]Defined functional requirements: Document Upload, QR Code Generation, and Profile Management[cite: 414].
    * Selected software requirements: Windows 10, Google Chrome, and QR Code Libraries.
* **Next Plan:** Design system architecture and database schema.
* **Guide Interaction:** Guide reviewed the module breakdown and suggested adding specific roles for doctors to scan codes.

### Week 4: System Architecture Design
**Date:** 28/08/2025 - 02/09/2025
* **Activities Completed:**
    * [cite_start]Designed System Architecture: Frontend (HTML/CSS/JS) -> Backend (Node.js) -> Database (PostgreSQL via Neon Console)[cite: 424].
    * [cite_start]Planned the data flow for how a patient uploads a file and receives a QR code[cite: 425].
    * [cite_start]Designed database schema in Neon Console to link Patient IDs with Document URLs and QR codes[cite: 426].
* **Next Plan:** Begin Phase 1 Implementation: UI and Database setup.
* [cite_start]**Guide Interaction:** Guide validated the technology stack (Node.js + Neon PostgreSQL) and architecture flow[cite: 430].

### System Architecture Diagram
* **mermaid
graph LR
    A[Frontend (HTML/CSS/JS)] -->|Uploads File| B[Backend (Node.js/Express)]
    B -->|Stores Data| C[(PostgreSQL via Neon Console)]
    B -->|Generates| D[QR Code]
    D -->|Scanned By| E[Doctor Module]
    B -->|Deploys On| F[Render Dashboard]
    style C fill:#00bfff,stroke:#333,stroke-width:2px
    style F fill:#7b68ee,stroke:#333,stroke-width:2px

### Week 5: Phase I of Implementation
**Date:** 03/09/2025 - 13/09/2025
* **Activities Completed:**
    * [cite_start]Set up the project environment with Node.js and Express[cite: 435].
    * [cite_start]Created a PostgreSQL database instance on Neon Console[cite: 436].
    * [cite_start]Developed the 'Patient Registration' and 'Login' pages using HTML and CSS and connected to Neon DB[cite: 437].
* **Next Plan:** Implement backend logic for user authentication.
* **Guide Interaction:** Guide reviewed the UI designs for the registration forms and suggested including blood group details.

### Week 6: Combined Design & Implementation
**Date:** 15/09/2025 - 20/09/2025
* **Activities Completed:**
    * [cite_start]Connected Frontend forms with Backend Node.js APIs[cite: 446].
    * Implemented 'Patient Dashboard' where users can view their profile.
    * [cite_start]Tested basic database connectivity to Neon Console and user data insertion[cite: 448].
* **Next Plan:** Implement Document Upload and QR Code generation.
* **Guide Interaction:** Guide reviewed backend connectivity and advised on handling server-side errors.

### Week 7: Phase II of Implementation
**Date:** 22/09/2025 - 04/10/2025
* **Activities Completed:**
    * [cite_start]Developed 'Document Upload Module' allowing patients to upload PDFs/Images[cite: 457].
    * [cite_start]Integrated 'QR Code Library' to generate unique codes upon successful upload[cite: 458].
    * [cite_start]Ensured files are securely stored and linked to the specific patient ID in the database[cite: 459].
* **Next Plan:** Implement the Doctor's scanning and viewing module.
* **Guide Interaction:** Guide reviewed the QR generation process and suggested verifying the scanning speed.

### Week 8: Phase III of Implementation
**Date:** 06/10/2025 - 18/10/2025
* **Activities Completed:**
    * [cite_start]Finalized the 'Doctor Module' to allow scanning and viewing reports[cite: 468].
    * [cite_start]Implemented the 'Admin Module' to manage users and control system access[cite: 469].
    * [cite_start]Added password protection logic so only authorized persons can view files after scanning[cite: 470].
* **Next Plan:** Start full-system testing and deployment preparation.
* [cite_start]**Guide Interaction:** Guide reviewed the security features (Password + QR) and approved the module integration[cite: 474].

### Week 9: System Testing
**Date:** 29/10/2025 - 01/11/2025
* **Activities Completed:**
    * [cite_start]Deployed the complete application online using Render Dashboard[cite: 479].
    * [cite_start]Performed Unit Testing on Login, Registration, and Upload functions on the live Render link[cite: 480].
    * [cite_start]Tested the QR Code scanning flow using mobile devices[cite: 481].
* **Next Plan:** Analyze results and prepare documentation.
* [cite_start]**Guide Interaction:** Guide advised testing the system on different networks to ensure Render deployment stability[cite: 485].

### Week 10: Final Results & Analysis
**Date:** 03/11/2025 - 08/11/2025
* **Activities Completed:**
    * Analyzed system efficiency: Quick access to records vs paper-based search.
    * [cite_start]Captured screenshots of the working system (Render Dashboard, Neon Console, UI) for the report[cite: 491].
    * [cite_start]Confirmed the system meets objectives: Paperless and Eco-friendly[cite: 492].
* **Next Plan:** Draft the final report and conclusion.
* **Guide Interaction:** Guide reviewed the final results and screenshots, suggesting improvements for the conclusion section.

### Week 11: Final Report & Conclusion
**Date:** 10/11/2025 - 15/11/2025
* **Activities Completed:**
    * [cite_start]Compiled the Final Report: Introduction, Modules, Tech Stack (Neon, Render, Node.js), and Conclusion[cite: 501].
    * Documented the Future Scope (Cloud integration, Mobile App).
    * [cite_start]Finalized the Logbook and prepared for the project demonstration[cite: 503].
* **Next Plan:** Submit project and prepare for viva.
* [cite_start]**Guide Interaction:** Guide appreciated the completed system and 'Secure Hospital Document System' implementation[cite: 507].
