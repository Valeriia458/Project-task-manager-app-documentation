**Issue / Bug Report: Task Tracker Manager**    

**Report ID:** BUG-2026-001  
**Severity:** High  
**Status:** Open  
**Issue Summary**  
The application fails to save the "Due Date" when a new task is created using the mobile
interface, resulting in tasks being listed without their associated deadlines.  
**Steps to Reproduce**
● Open the Task Tracker Manager app.  
● Navigate to the "Add New Task" screen.  
● Enter a title (e.g., "Submit Project Proposal") and a description.  
● Tap on the "Due Date" field and select a date from the calendar picker.  
● Click the "Save Task" button.  
● Return to the main dashboard and locate the newly created task.  
**Expected Result**  
The task should display the selected due date (e.g., "May 15, 2026") on the dashboard card.  
Actual Result  
The task appears on the dashboard, but the "Due Date" field is blank or displays "No Date Set."  
**Environment Details**  
 Device: Pixel 7, iPhone 14  
● Operating System: Android 14, iOS 17  
● App Version: v0.1.2 (MVP Beta)  
**Additional Comments**  
This issue seems to be a data-binding error between the frontend date picker component and
the backend API request. Preliminary checks show the date object is being cleared right before the POST request is sent.
