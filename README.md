# Appointment No-Show Saver

## Project Demo Video

**Loom Demo:** https://www.loom.com/share/71970b77497248e18686d802a1d7b2ab

## Project Overview
Appointment No-Show Saver is an n8n automation project designed to reduce missed appointments through automated reminders, appointment status updates, consent management, and rebooking workflows.

## Technologies Used
- n8n
- Google Sheets
- Webhooks
- AI-generated SMS messages
- TextBee API
- JavaScript

## Main Features
1. New appointment intake through webhook.
2. Appointment data storage in Google Sheets.
3. Automated appointment reminder workflow.
4. Appointment status updates.
5. No-show detection and rebooking workflow.
6. SMS STOP and START consent management.
7. AI-generated reminder messages.
8. Error-handling paths.

## Google Sheets
The project uses three sheets:
- Appointments
- Consent
- Logs

## Testing
The following tests were completed:
- Appointment creation webhook.
- Duplicate appointment check.
- Appointment status update.
- SMS STOP opt-out functionality.
- AI-generated reminder preview in dry-run mode.

**Note:** Dry-run mode was enabled during reminder testing. No real SMS was sent. Rebooking and complete error-handling tests are not yet confirmed.

## Setup Instructions
1. Import the workflow JSON file into n8n.
2. Connect your Google Sheets account.
3. Configure the required Google Sheets document and tabs.
4. Configure webhook URLs and workflow settings.
5. Set up the required SMS provider credentials.
6. Test the workflow using dry-run mode before enabling live SMS.

## Configuration
Use environment variables or n8n credentials for API keys and sensitive information. Never upload private API keys or passwords to GitHub.

## Repository
GitHub: https://github.com/hamzaking0838/taw-n8n-appointment-no-show-saver

## Project Status
Project 1 – Appointment No-Show Saver.

Demo video and project repository links are included above.
