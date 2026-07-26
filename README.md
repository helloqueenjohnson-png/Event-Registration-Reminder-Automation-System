# 📅 Event Registration & Reminder Automation System

An automated event management workflow that validates registrations, personalizes attendee communication, and sends scheduled reminder emails to improve the attendee experience.

---

# 📌 Business Problem

Event organizers often spend significant time manually reviewing registrations, confirming attendee details, sending personalized confirmation emails, and reminding attendees before an event begins. As the number of registrations grows, this process becomes repetitive, time-consuming, and prone to errors.

---

# 💡 Solution

This workflow automates the event registration process from form submission to reminder notifications.

When an attendee registers for an event, the workflow:

- Captures registration details.
- Formats attendee names for professional communication.
- Validates event availability.
- Stores registration details in Google Sheets.
- Sends a personalized confirmation email based on the selected event.
- Schedules a reminder email before the event date.

---

# ⚙️ Workflow Architecture

Google Form

⬇️

Formatter by Zapier

⬇️

Filter Event Availability

⬇️

Google Sheets

⬇️

Paths by Zapier

⬇️

Personalized Confirmation Email

⬇️

Delay Until Event

⬇️

Reminder Email

---

# 🚀 Key Features

- Automated event registration
- Name formatting
- Event availability validation
- Google Sheets integration
- Personalized confirmation emails
- Multi-event routing using Paths
- Scheduled reminder emails

---

# 🛠 Technologies Used

- Zapier
- Google Forms
- Formatter by Zapier
- Filter by Zapier
- Paths by Zapier
- Delay by Zapier
- Google Sheets
- Gmail

---

# 🔄 Workflow Process

1. An attendee submits the registration form.
2. Formatter standardizes the attendee's name.
3. Filter verifies that the selected event is still available.
4. Registration details are stored in Google Sheets.
5. Paths identifies which event the attendee selected.
6. A personalized confirmation email is sent for that specific event.
7. Delay schedules the workflow until the appropriate reminder date.
8. A reminder email is automatically sent before the event.

---

# 📈 Business Benefits

- Eliminates manual attendee confirmations.
- Reduces administrative workload.
- Prevents generic email communication.
- Improves attendee engagement.
- Reduces missed events through automated reminders.

---

# 📸 Workflow Screenshots

Coming Soon

---

# 🎥 Demo Video

Coming Soon

---

# 📚 Future Improvements

- QR code ticket generation
- Calendar invitation (.ics) attachment
- SMS reminders
- Waitlist automation
- Attendance tracking
