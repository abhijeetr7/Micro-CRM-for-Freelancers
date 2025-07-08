# Micro-CRM-for-Freelancers

This Micro CRM provides the following:

Dashboard: A quick overview of total clients, active projects, and upcoming reminders. It also shows recent activities.

Clients Section:

Add new clients with name, email, phone, company, and notes.

View all clients in a table.

Edit and delete client entries.

Projects Section:

Add new projects, linking them to existing clients.

Set deadlines and project status (To Do, In Progress, Completed, On Hold, Cancelled).

View all projects in a table with their associated client and status.

Edit and delete project entries.

Reminders Section:

Add reminders with a date, optional time, and optional related client.

View all reminders, sorted by date and time.

Edit and delete reminder entries.

Communication Logs Section:

Log various types of communication (Email, Call, Meeting, Other) with a client, date, time, subject/summary, and detailed notes.

View all communication logs in a table.

Edit and delete log entries.

Data Persistence: All your data (clients, projects, reminders, logs) is automatically saved to Firestore, so it persists across sessions.

Responsive Design: The layout is designed to adapt well to different screen sizes, from mobile to desktop.

User Feedback: Small message boxes appear at the bottom to confirm actions (e.g., "Client added successfully!") or show errors.

Confirmation Modal: A modal pops up to confirm deletions, preventing accidental data loss.

To use this, simply paste the code into an index.html file and open it in your browser. Your data will be stored securely in your private Firestore collection.
