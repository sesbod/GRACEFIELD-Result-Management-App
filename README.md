# Result Management System

A simple, role-based result management system built with HTML, CSS, and Vanilla JavaScript.

## Features

-   **Role-Based Access Control**:
    -   **Admin**: Full access to the Master Broadsheet, student management, and report card generation.
    -   **Subject Teachers**: Restricted to entering/editing marks only for their assigned subjects.
-   **Master Broadsheet**: Automatically calculates student averages and displays a summary of all results.
-   **PDF Report Card**: Generates a formatted, printable PDF report card using `html2pdf.js`.
-   **Data Persistence**: Uses `localStorage` to keep data between sessions.

## Demo Credentials

| Role | Username | Password | Subject |
| :--- | :--- | :--- | :--- |
| Admin | `admin` | `admin` | All |
| Teacher | `teacher1` | `teacher1` | Mathematics |
| Teacher | `teacher2` | `teacher2` | English |

## How to Run

1. Open `index.html` in any modern web browser.
2. Use the credentials above to log in.
3. As a teacher, enter scores for students.
4. As an admin, view the broadsheet and click "View Report" to generate and download a PDF.

## Technical Details

-   **Frontend**: HTML5, CSS3, JavaScript (ES6+).
-   **PDF Library**: [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) via CDN.
-   **Storage**: Browser `localStorage`.
