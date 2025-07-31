# 💍 Ultimate Wedding Planner – Google + Notion Integration
## Overview
The Ultimate Wedding Planner is an integrated system built with Google Forms, Google Sheets, and Notion to help brides manage wedding planning stress-free. It streamlines RSVP tracking, alerts brides when an uninvited guest submits a form, and centralizes all planning tasks in a Notion dashboard for easy access and organization. <br>

This system combines the flexibility of Google tools with the aesthetic and project management power of Notion—making it the perfect digital assistant for the modern bride.

## ✨ Features
✅ Google Form for RSVPs<br>
Guests submit responses to wedding events (ceremony, reception, etc.)<br>

📋 Google Sheets with Guest Verification<br>
Form responses are checked against a preloaded guest list. If a match is found, it updates the guest’s status and details.<br>

❌ Email Alert for Unlisted Guests<br>
If a guest not on the official guest list tries to RSVP, the bride receives an automatic email notification.<br>

🧠 Notion Dashboard Sync<br>
The Google Sheet connects to a Notion dashboard where:<br>

Guest list updates live<br>

RSVP statuses are visible at a glance<br>

Wedding to-do list is organized in one place (venue, dress, budget, vendor contacts, etc.)<br>

🔁 Real-Time Updates<br>
All components are synced to reflect changes in real time, ensuring brides stay up-to-date without manual data entry.<br>

## 🛠 Tech Stack
Google Forms – RSVP collection<br>

Google Sheets – Guest list logic & response processing<br>

Apps Script – Automated email alerts + Notion sync trigger<br>

Notion API – Dashboard integration for planning and tracking<br>

## 📌 How It Works
### Set Up the Guest List

A Google Sheet contains all invited guest names and emails.<br>

### Collect RSVPs

Guests fill out a Google Form linked to that Sheet.<br>

### Run Script Check

A Google Apps Script verifies if the respondent is on the official list.<br>

✅ If found: RSVP info is logged.<br>

❌ If not found: An email alert is sent to the bride.<br>

### Sync to Notion

The guest list and RSVP info are mirrored into a Notion database.<br>

The Notion dashboard also includes tabs for budget, vendors, checklist, and more.<br>

## 🚀 Impact
🕒 Saves hours of manual RSVP checking<br>

📬 Prevents uninvited guests from slipping through<br>

📊 Consolidates planning into one clean, visual dashboard<br>

💡 Enables brides to plan proactively instead of reactively<br>
