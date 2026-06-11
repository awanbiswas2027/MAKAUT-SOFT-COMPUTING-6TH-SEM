# MAKAUT Soft Computing Study Portal 🎓📚

An interactive, responsive, and exam-focused single-page application (SPA) study portal designed for B.Tech CSE (AI & ML) Semester VI students under Maulana Abul Kalam Azad University of Technology (MAKAUT), West Bengal.

This portal maps **100% of the MAKAUT syllabus** for:
*   **Theory (PCCAIML603)**: Soft Computing
*   **Practical (PCCAIML693)**: Soft Computing Lab

---

## 🌟 Key Features

### 1. 📋 Syllabus Dashboard
*   Organized unit-by-unit according to the MAKAUT syllabus layout (Units 1 to 5).
*   Collapsible topics containing:
    *   **Why Learn This**: Contextual and real-world importance.
    *   **Exam Relevance**: Weightage and standard exam expectations.
    *   **Study Time**: Recommended time allocation.
    *   **Curated Video Matrix**: Side-by-side comparison of **Best Choice** and **Alternative** lectures from India's top channels (Gate Smashers, 5 Minutes Engineering, NPTEL, etc.) with beginner/exam/clarity ratings.

### 2. ⚡ 80/20 Fast-Track Study Path
*   Filters out auxiliary theory to present a consolidated checklist of the **most critical, high-weightage topics** (such as Backpropagation derivations, Fuzzy Set composition operations, Defuzzification numericals, etc.).
*   Includes an estimated study time and a **Suggested 3-Week master schedule** designed to secure passing marks efficiently.

### 3. ⏱️ Revision Planners
*   **1-Week Revision Plan**: A daily scheduled plan outlining study modules and target videos, estimating marks impact day-by-day.
*   **1-Day Crash Revision Plan**: A last-minute high-yield selector focusing exclusively on formulas, short notes definitions, and essential viva-vocal concepts.

### 4. 🧪 Practical & Viva Lab Guide
*   Explicit mapping of Soft Computing Practical (PCCAIML693) experiments.
*   Includes target Python/MATLAB source code guidelines alongside viva concepts videos to help tackle external examiners.

### 5. 📊 PYQ Mapping & Exam Analysis
*   MAKAUT Semester exam pattern breakdown (Part A, Part B, Part C).
*   List of repeatedly asked concepts (e.g., Backpropagation derivations, defuzzification methods, selection algorithms) and long-answer potentials.

### 6. 🏆 Ranked Educational Catalog
*   A filterable and sortable card catalog listing all curated videos ranked by calculated score metrics out of 40 points (Beginner-friendliness, Exam focus, Practical relevance, Clarity).

### 7. 🔍 Instant Filtering & Local Progress Tracking
*   **Search Engine**: Real-time filtering across topics, channels, and keywords.
*   **Progress Save**: Interactive checkboxes persist completion data in the browser's `localStorage`. Shows global progress indicator with an animated progress bar.

---

## 🛠️ Technology Stack

*   **Markup**: HTML5 (Semantic elements)
*   **Styling**: Vanilla CSS3 (Custom properties, dark/light theme toggle, glassmorphism panel styles, linear gradients, floating background orbs, responsive layouts)
*   **Icons & Fonts**: Font Awesome (v6.4.0), Google Fonts (Outfit & Inter)
*   **Client Logic**: Vanilla JavaScript (Standard DOM manipulation, LocalStorage persistent state, iframe-based inline modal video players)

---

## 📂 Directory Index

*   `index.html` — Main SPA code containing all styling, logic, layouts, and curated video database.
*   `link_audit_report.md` — Link health report documenting automated verification of all reference links (100% availability verification).
*   `README.md` — Main project documentation.

---

## 🚀 How to Run Locally

Since the application is built entirely as a standalone frontend SPA:
1.  Clone this repository or download the files.
2.  Simply double-click `index.html` or drag it into any modern web browser (Chrome, Edge, Firefox, Safari).
3.  No local server, node modules, or database configurations are required!
