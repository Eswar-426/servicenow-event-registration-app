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
*(Add your YouTube or Google Drive demo link once uploaded)*

