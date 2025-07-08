CSE B Seat Arranger
Overview
The CSE B Seat Arranger is a simple, intuitive web application designed to efficiently organize classroom seating for students in CSE B. It automates the process of assigning students to benches, ensuring gender segregation and adhering to specific seating capacity rules. The application provides a clear visual representation of the seating plan, making it easy for teachers to manage and locate students.

Features
Automated Seat Arrangement: Generates a new seating plan with a single click.

Strict Bench Capacity: Ensures exactly 3 students are seated per bench across all 24 benches (4 columns x 6 rows).

Gender Segregation:

Columns 1 and 2 are primarily designated for girls.

Columns 3 and 4 are primarily designated for boys.

Includes a special adjustment rule to place male students in Bench 12 (the last bench of Column 2) if male-preferred benches are full.

Roll Number Based: Students are identified and displayed by their roll numbers only.

Interactive Search: Allows users to quickly find a student by their roll number, highlighting their bench and scrolling it into view.

Clear/Reset Search: A button to clear the search input and remove highlights.

Persistent Seating Plan: The generated seating plan is saved locally in the browser, so it persists even if the page is closed and reopened.

Responsive Design: Optimized for seamless viewing and interaction across various devices, including mobile phones, tablets, and desktops.

User-Friendly Interface: Clean, professional UI with a calming color theme and subtle animations.

Arrangement Cooldown (Currently Disabled for Demo): By default, the application includes a 5-day cooldown period for re-arranging seats to ensure stability. This feature is currently disabled in the provided code for easy demonstration.

How to Use
This application is a single HTML file, making it incredibly easy to use:

Download: Save the index.html file to your computer.

Open: Double-click the index.html file in your browser, or drag and drop it into any modern web browser (Chrome, Firefox, Edge, Safari).

Arrange Seats: Click the "Arrange Seats" button to generate the initial seating plan.

Search: Enter a student's roll number in the "Find student by roll no..." input field and click the "Search" button to highlight their bench and scroll to it.

Clear Search: Click the "×" button next to the search bar to clear the search and remove highlights.

Re-arrange: (If the cooldown is re-enabled) Wait for the 5-day timer to expire, then click "Arrange Seats" again. (Currently, you can click it anytime).

Technologies Used
HTML5: For the structure of the web page.

CSS3 (with Tailwind CSS): For styling and responsive layout. Tailwind CSS CDN is used for utility-first styling.

JavaScript: For all the interactive logic, including seat arrangement algorithms, search functionality, and local storage management.

Done by
Geo Cherian Mathew
