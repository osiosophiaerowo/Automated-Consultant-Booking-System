# Automated-Consultant-Booking-System
A professional booking system i set up to manage a client's schedule. It automates meeting requests, collects info from the guests upfront & uses buffer settings to prevent back-to-back meetings 

## Project Overview
I configured a professional automated scheduling system for a Strategy Consultant to manage his intake, calendar protection & time-zone synchronization. This set-up  eliminates manual scheduling, ensures the consultant is prepared for every session & protects the consultant's schedule from burnout through custom "guardrail" logic.

## Key Implementations/System Configuration

### 1. Availabilty Logic
* **Increments:** Set to 30 minutes for a professional, organised calendar view.
* **Time Zone: Set to "Automatic" to detect the guest's location and prevent scheduling errors.

### 2. Calendar Guardrails
To ensure the consultant remains productive and prepared, I configured:
* **Buffer Times:** 15-minute windows before and after every meeting to prevent back-to-back fatigue.
* **Daily Limits:** A cap of 4 sessions per day to protect "deep work" hours.
* **Notice Periods:** A 4-hour minimum lead time to prevent surprise bookings.

### 2. Smart Intake Form
I engineered a custom questionnaire to qualify leads before they ever reach the calendar:
* **Goal Setting:** Mandatory response for "What is your #1 goal for this call?" (Required).
* **Contact Logic:** Automated phone/video detail collection based on meeting type.

### 3. Conflict Resolution
* **Live Sync:** Integrated with Google Calendar to provide 100% real-time accuracy and zero double-bookings.

---

## 📸 System Walkthrough

### The Booking Experience
*How clients see available slots.*
![Booking Page](IMAGE_URL_HERE)

### Intake Logic
*The form used to gather critical client data.*
![Intake Form](IMAGE_URL_HERE)

### Protection Settings
*The backend logic for buffers and limits.*
![Settings](IMAGE_URL_HERE)
