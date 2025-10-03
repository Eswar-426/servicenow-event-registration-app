# servicenow-event-registration-app
A custom Event Registration application built on ServiceNow App Engine Studio and Flow Designer with automated approvals and notifications.
# 🎫 ServiceNow Event Registration Application

A custom **Event Registration Application** built on **ServiceNow App Engine Studio** and **Flow Designer**.  
This app automates the process of event creation, attendee registration, approvals, and feedback collection — all within the ServiceNow platform.

---

## 🚀 Overview

The **Event Registration App** allows users to register for events and sessions directly from the Service Catalog.  
Approvals and notifications are automated using Flow Designer.  
Admins can manage events, monitor registrations, and analyze feedback through reports and dashboards.

---

## ⚙️ Key Features

- 📝 **Catalog Item:** Enables users to register for events and sessions  
- 🔄 **Flow Designer:** Automates approvals and email notifications  
- 📬 **Notifications:** Confirmation emails for both users and admins  
- 🔐 **Role-Based Access:** Roles for `event_user` and `event_admin`  
- 📊 **Dashboard:** Displays active events, total registrations, and feedback insights  
- 💬 **Feedback Module:** Allows users to submit feedback after events  

---

## 🧩 Data Model

| Table Name | System Name | Description |
|-------------|--------------|-------------|
| **Event** | `x_1798866_event_ma_event` | Stores event details such as name, date, location, and description |
| **Registration** | `x_1798866_event_ma_registration` | Captures attendee registration details including event, session, and status |
| **Feedback** | `x_1798866_event_ma_feedback` | Stores user feedback and ratings for post-event evaluation |

---

## 🧠 Modules & Components Used

- **App Engine Studio** – for application creation and table design  
- **Flow Designer** – for automation of approval and notification flows  
- **Service Catalog** – to create event registration catalog items  
- **Notifications** – to send confirmation and approval emails  
- **Reporting & Dashboards** – to visualize events and feedback metrics  
- **ACLs & Roles** – for access control and secure visibility  

---

## 🧾 Demo Video

🎥 Watch the full live demo of this application here:  
https://drive.google.com/file/d/1OwbuvaB684DdwbyblkmvzfYEbcm7a9Tc/view?usp=drive_link
---

## 🧰 Installation Guide

To import and test this app in your own ServiceNow instance:

1. Download the update set XML file from the `/update_set` folder.  
2. In your instance, navigate to:  
   **System Update Sets → Retrieved Update Sets → Import Update Set from XML**  
3. Preview and Commit the update set.  
4. Assign roles (`event_user`, `event_admin`) to your test users.  
5. Access the Catalog Item under the Service Catalog to test event registration flow.

---

## 🧑‍💻 Developer Information

**👤 Eswar Ram Kumar Kanchi**  
🎓 Engineering Student | ServiceNow Developer | CSA Certified  

🔗 [LinkedIn Profile](https://www.linkedin.com/in/eswar-ram-kumar-kanchi)  
📧 eswarramkumar68@gmail.com 

---

## 📸 Screenshots

| Section | Screenshot |
|----------|-------------|
| Catalog Items | ![Catalog Item](screenshots/catalog_item.png) |
| Flow Designer Flow | ![Flow Designer](screenshots/flow_designer.png) |
| Dashboard | ![Dashboard](screenshots/dashboard.png) |
| Feedback Table | ![Feedback](screenshots/feedback.png) |



---

## 📜 License

MIT License © 2025 [Eswar Ram Kumar Kanchi](https://www.linkedin.com/in/eswar-ram-kumar-kanchi)

---

## 🌟 Highlights

✅ Built entirely on the **ServiceNow Platform**  
✅ Demonstrates **App Engine Studio, Flow Designer, Catalog, and Notification automation**  
✅ Designed with **role-based dashboards** and **modular tables**  
✅ Ideal for demonstrating **ServiceNow CAD & CSA**  level skills

---




