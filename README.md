# quiz-casi 🧠

Interactive self-assessment test engine for **CASI (Calidad y Auditoría de los Sistemas de Información / Information Systems Quality and Auditing)**.

This repository contains an original self-assessment platform and curated question set created by the repository owner with AI-assisted content generation, validation and refinement workflows.

Part of the DevQuiz-Hub ecosystem.

## 📚 Core Topics Covered

* **Block 1**: Information Security Management Systems (ISMS), CIA Triad, security policies, information assets and risk management.
* **Block 2**: IT Governance, Corporate Governance, ISO/IEC 38500, CISA certification and internal control systems.
* **Block 3**: IT Auditing, digital evidence, chain of custody, audit processes and compliance assessment.
* **Block 4**: Business Continuity, backup strategies, disaster recovery, security controls, firewalls, IDS, vulnerability assessment and web security attacks (SQL Injection, XSS).

## 🛠️ Data Contract & Logic

This repository implements the standardized architecture of the organization:

* **`Calidad y auditoría de los sistemas de información_Exámenes.json`**: Holds the structured question schema, metadata and explanatory content.
* **`quiz.js`**: Core asynchronous engine handling in-place shuffling, dynamic data fetching and client-side state management.
* **`index.html`**: Zero-dependency SPA frontend built with responsive modern CSS variables.

## 🚀 Live Demo

The application is fully deployed through GitHub Pages: reichgp.github.io/quiz-casi/

🔗 **https://devquiz-hub.github.io/quiz-casi/**

