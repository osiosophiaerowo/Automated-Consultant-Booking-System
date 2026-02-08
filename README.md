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

### 3. Client Intake Form
I engineered a custom questionnaire to qualify leads before they ever reach the calendar:
* **Challenge Identification:** "What is the current challenge of your business?"
* **Guidance Focus:** "Is there a specific area you need expert guidance?"
* **Commitment Check:** "Are you willing to follow the clear set of Next Steps we will end the call with?"

### 4. Conflict Resolution
* **Live Sync:** Integrated with Google Calendar to provide 100% real-time accuracy and zero double-bookings by monitoring consultant’s real-time availability. 
* **Dynamic Availability:** The system automatically cross-references all personal appointments and existing busy blocks, instantly removing those slots from the booking page to ensure zero scheduling conflicts.

---

## System Walkthrough


***1. Client Entry Point***

This is the professional landing page I configured to welcome clients. It features a clear value proposition for the '30 Minutes Strategy Meeting,' setting expectations immediately and ensuring a high-quality user experience from the very first click.



***2. Live Calendar***

The active booking interface where clients select their preferred date. I enabled automatic time-zone detection (shown here in Central Time) to eliminate scheduling confusion across different regions.


***3. Backend Availability***

A behind-the-scenes look at the 'Scheduling Engine.' I established a custom 10:00 - 16:00 window and manually designated specific 'Unavailable' days to protect the consultant’s deep-work time and prevent overbooking.
