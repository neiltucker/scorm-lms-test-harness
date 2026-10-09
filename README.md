# Offline SCORM & LMS Test Harness

A lightweight, single-page offline Learning Management System (LMS) API simulation environment. Use it to instantly run, test, and debug your interactive HTML5 SCORM packages locally in any browser without needing to upload files to a slow, remote corporate LMS.

[![Courseware Studio Logo](https://coursewarestudio.ai/logos/CoursewareStudio-Logo-Dark.svg)](https://coursewarestudio.ai)

---

## ✨ Features

*   **SCORM 1.2 & SCORM 2004 Support:** Registers global interfaces (`window.API` and `window.API_1484_11`) automatically.
*   **Real-time Interaction Logging:** A persistent sidebar logs and color-codes all LMS transactions (`Initialize`, `GetValue`, `SetValue`, `Commit`, and `Terminate`) showing precisely what values the course is trying to read or write.
*   **In-Memory Database Simulation:** Tracks tracking status, completion status, and scores dynamically within the browser memory for standard verification testing.

---

## 🚀 How to Use It

1.  **Clone or Download this Repository:**
    ```bash
    git clone https://github.com/neiltucker/scorm-lms-test-harness.git
    ```
2.  **Open `index.html`:**
    Double-click `index.html` to open it in any desktop web browser (Chrome, Firefox, Safari, Edge).
3.  **Specify Your Course Path:**
    In the search bar at the top, enter the relative file path to the starting page of your SCORM package (e.g., `../free-scorm-wrapper/index.html` or `./my-course/index.html`).
4.  **Click "Launch Course":**
    Your SCORM package will load in the interactive iframe panel. All initialization handshakes, score updates, and completion flags will print instantly in the left console panel!

---

## ⚡ Save Weeks of Planning and Course Writing

Tired of manually configuring tracking hooks, writing slide templates, formatting student guides, and aligning learning objective summaries? Let **Courseware Studio** handle it.

Start with your topic, get a complete syllabus free, and instantly build high-fidelity training courses:
*   **Core LMS Bundle:** Platform-neutral SCORM 1.2, 2004, xAPI, and cmi5 interactive HTML5 packages that run perfectly on standard-compliant LMSs.
*   **Instructor Materials:** Generated Student Manuals, Instructor Guides, PowerPoint slides, and assessments ready to teach.
*   **Self-Paced eLearning Add-on:** High-fidelity module intro videos, narrated slides, and transcripts out of the box.

👉 **[Create a Free Syllabus Now at CoursewareStudio.ai](https://coursewarestudio.ai)**

---

## 📝 License
This test harness is open-source software licensed under the MIT License. Created in partnership with [Courseware Studio](https://coursewarestudio.ai).
