🧩 Form Submission Workflow (n8n)
This workflow automates email notifications and task creation based on form submissions.
🔧 Workflow Overview
The automation begins whenever a new form submission occurs. It checks if the submission date is within the last 7 days and performs different actions accordingly.
Workflow Steps
📝 On Form Submission
Trigger node that activates when a form is submitted.
Captures form data such as name, email, and submission timestamp.
🕒 Check: Is within 7 days?
A conditional node that verifies whether the form submission occurred within the past 7 days.
Helps filter recent submissions from older ones.
📧 Send a Message (Gmail Node)
If the submission is within 7 days, an automated email notification is sent through Gmail.
Example use case: sending a confirmation or thank-you message to the user.
✅ TO-DO Node
If the submission is not within 7 days, it triggers a “To-Do” action.
This can be connected to another workflow or task management system for manual review.
📁 Folder Structure Suggestion
Form-Submission-Workflow/
│
├── My workflow 3.json
├── FORM SUBMISSION THROUGH N8N/
│   └── (form-related JSON files or screenshots)
└── README.md
🚀 Use Case
This workflow can be used in:
Online form systems (Google Forms, Typeform, etc.)
Project onboarding forms
Event registration tracking
Automated follow-up systems
⚙️ Tools Used
n8n (Workflow Automation Tool)
Gmail Node for automated email messaging
IF Node for conditional logic
🧠 Key Learning
This workflow demonstrates how to combine form triggers, conditional checks, and automated communication for efficient workflow management.
