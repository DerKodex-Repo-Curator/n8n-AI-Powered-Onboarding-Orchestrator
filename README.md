# AI-Powered HR Onboarding Orchestrator

![n8n](https://img.shields.io/badge/n8n-121212?style=for-the-badge&logo=n8n&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

An intelligent n8n workflow that automates and personalizes the new hire onboarding process, transforming a 3-hour manual task into a 5-minute intelligent workflow.

---

## The Problem

Manual HR onboarding is a significant operational bottleneck. The process is time-consuming, prone to human error, and often results in a disjointed and impersonal first impression for new employees. This inefficiency diverts skilled HR personnel from high-value, human-centric work to low-value administrative tasks.

## The Solution

This project orchestrates the entire onboarding process using a single n8n workflow. A manager fills out a simple web form, which triggers a cascade of automated actions powered by a central AI agent. The system handles everything from personalized communication to synchronized record-keeping and team announcements, all without manual intervention.

### Key Features
- ** AI-Powered Personalization**: A Google Gemini agent analyzes the new hire's role to generate a hyper-personalized welcome email, complete with relevant onboarding resources.
- ** End-to-End Automation**: Handles all core onboarding tasks: email communication, master roster updates, checklist creation, and team announcements.
- ** Centralized Record-Keeping**: Creates a single source of truth by instantly updating a master roster and a team-wide onboarding checklist.
- ** Robust Error Handling**: A dedicated error-handling workflow provides real-time Slack alerts for any failures, ensuring system reliability and immediate attention when needed.

## Workflow Diagram

*(**Action**: Take a screenshot of your streamlined Miro diagram and drag it into this section of the README file on GitHub)*

## Technical Stack
- **Automation Platform**: n8n
- **AI Engine**: Google Gemini
- **Connected Services**: Gmail, Google Sheets, Google Drive, Slack
