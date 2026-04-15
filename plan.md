Role: Act as a Full-Stack Developer.
Objective: Create a single-page web application for a private music teacher to manage student enrollments, schedules, and finances.

1. Data Schema & Logic
Violin Lessons: 30 min ($90), 45 min ($135), 60 min ($180).

Music Theory: 60 min ($40).

Credit System: Each student has a "Credits Remaining" balance. When the user clicks "Mark Attended," 1 credit is deducted. When "Add Payment" is clicked, user inputs a number of lessons (e.g., 4) to add to the balance.

2. UI Components (Interactive Dashboard)
Student Registry Table: Columns for Name, Instrument (Dropdown), Lesson Duration (Dropdown), Credit Balance, and Payment Status (Auto-calculated: "Paid" if balance > 0, "Overdue" if balance ≤ 0).

Visual Weekly Timetable: * Weekdays (3 PM – 8 PM): Dedicated to Violin.

Weekends (Full Day): Dedicated to Music Theory.

Feature: Cells should be color-coded by instrument and show the student's name.

Profit Analytics Section: * Display Total Revenue (sum of all historical payments).

Display Projected Revenue (value of lessons currently on the schedule for the week).

Alerts Panel: A dedicated "Action Required" list showing students with 0 or negative credits.

3. User Experience (UX) Improvements
Bulk Actions: Ability to "Mark all for today as attended" to save time.

Local Storage: Use localStorage so that data persists in the browser without needing a complex backend database.

Color Logic: Rows for students with "Overdue" status should highlight in soft red; "Upcoming" in green.

Responsive Design: Ensure the timetable is readable on both a tablet and a desktop.

4. Sample Data to Include (Initial State)
Alice Wong: Violin, 45 min, Mon 3:00 PM.

Bob Smith: Theory, 60 min, Sun 10:00 AM.

Charlie Day: Violin, 60 min, Mon 5:30 PM.

Leo J: Violin, 60 min, Tue 7:00 PM.