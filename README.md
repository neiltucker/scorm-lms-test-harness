# Offline SCORM & LMS Test Harness

A lightweight, single-page offline Learning Management System (LMS) API simulation environment. Use it to instantly run, test, and debug your interactive HTML5 SCORM packages locally in any browser without needing to upload files to a slow, remote corporate LMS.

[![Courseware Studio Logo](https://coursewarestudio.ai/logos/CoursewareStudio-Logo-Dark.svg)](https://coursewarestudio.ai)

👉 **[🚀 Launch Live In-Browser Test Harness](https://neiltucker.github.io/scorm-lms-test-harness/)** (No installation needed)

---

## ✨ Features

*   **SCORM 1.2 & SCORM 2004 Support:** Registers global interfaces (`window.API` and `window.API_1484_11`) automatically.
*   **Direct Drag & Drop Package Testing:** Drag any standard SCORM `.zip` package (or standalone `.html` file) directly onto the browser window. The harness extracts files in memory and executes the course with no server or local unzipping needed!
*   **One-Click Demo Course:** Click "Load Demo Course" to instantly run an interactive SCORM 2004 test course without needing any files prepared.
*   **Live CMI State Monitor:** Displays real-time values for completion status, success status, progress measure, and score directly above the console logs.
*   **Real-time Interaction Logging:** A persistent sidebar logs and color-codes all LMS transactions (`Initialize`, `GetValue`, `SetValue`, `Commit`, and `Terminate`) showing precisely what values the course is trying to read or write.
*   **In-Memory Database Simulation:** Simulates full session lifecycle tracking across SCORM 1.2 and SCORM 2004 specifications.
*   **Zero Dependencies / Pure Client-Side:** Runs completely inside your web browser. No backend server or cloud account required.

---

## 🚀 How to Use It

### Option 1: Use Online (Instant)
Open **[neiltucker.github.io/scorm-lms-test-harness](https://neiltucker.github.io/scorm-lms-test-harness/)** in any desktop web browser.

### Option 2: Run Locally
1.  **Clone or Download this Repository:**
    ```bash
    git clone https://github.com/neiltucker/scorm-lms-test-harness.git
    ```
2.  **Open `index.html`:**
    Double-click `index.html` to open it in any desktop web browser (Chrome, Firefox, Safari, Edge).
3.  **Load Your Course (3 Easy Ways):**
    *   **Drag & Drop:** Simply drag and drop any SCORM `.zip` file into the window.
    *   **Upload Package:** Click the **Upload SCORM (.ZIP / .HTML)** button and choose your package.
    *   **Relative Path / URL:** Enter a relative file path or URL in the text box and click **Launch**.
4.  **Instant Verification:**
    Your SCORM package loads in the sandboxed iframe. All initialization handshakes, progress updates, and completion flags stream instantly to the console and live CMI monitor!

---

## ⚡ Save Weeks of Planning and Course Writing

### 🚀 [Courseware Studio](https://coursewarestudio.ai) — AI-Powered Course Generation
Tired of manually configuring tracking hooks, writing slide templates, formatting student guides, and aligning learning objective summaries? Let **Courseware Studio** handle it.

Start with your topic, get a complete syllabus free, and instantly build high-fidelity training courses:
*   **Core LMS Bundle:** Platform-neutral SCORM 1.2, 2004, xAPI, and cmi5 interactive HTML5 packages that pass every LMS validation check.
*   **Instructor Materials:** Generated Student Manuals, Instructor Guides, PowerPoint slides, and assessments ready to teach.
*   **Self-Paced eLearning Add-on:** High-fidelity module intro videos, narrated slides, and transcripts out of the box.

👉 **[Create a Free Syllabus Now at CoursewareStudio.ai](https://coursewarestudio.ai)**

### 🎓 [Software Tutorial Services](https://www.softwaretutorialservices.com) — Enterprise Technical Training
Need enterprise-grade instructor delivery or curriculum licensing for your organization?
* Hands-on instructor-led courses for Microsoft SQL Server, Azure Cloud, Windows Server, PowerShell, and Python.
* Corporate bootcamps, custom technical labs, and certified instruction.

👉 **[Explore Courses at SoftwareTutorialServices.com](https://www.softwaretutorialservices.com)**

---

## 🧰 Related Free Tools for Trainers & Developers

*   **[Markdown to SCORM](https://github.com/neiltucker/markdown-to-scorm):** Turn markdown outlines into interactive SCORM 2004 packages.
*   **[Free SCORM Wrapper](https://github.com/neiltucker/free-scorm-wrapper):** HTML5 SCORM boilerplate template.
*   **[Timer3](https://github.com/neiltucker/timer3):** Presentation countdown timer for workshops and lab exercises.

---

## 📝 License
This test harness is open-source software licensed under the MIT License. Created in partnership with [Courseware Studio](https://coursewarestudio.ai) and [Software Tutorial Services](https://www.softwaretutorialservices.com).

