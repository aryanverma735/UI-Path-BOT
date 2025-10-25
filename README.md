
# UiPath Automation Bot: Email-to-Ticket Assignment

 Overview
This UiPath automation bot streamlines the **ticket creation process** by automatically scanning incoming emails from the company's mailbox, extracting relevant details, and creating tickets in the internal system. It then assigns these tickets to the appropriate associates based on predefined rules, reducing manual effort and improving turnaround time.

---

##  Key Features
- **Automated Email Parsing**: Reads and processes incoming emails to identify ticket requests.
- **Dynamic Ticket Creation**: Creates tickets in the service management system with accurate metadata.
- **Intelligent Assignment**: Assigns tickets to associates based on workload, department, or skill set.
- **Error Handling & Logging**: Implements robust exception handling and logs all activities for audit purposes.
- **Scalability**: Designed to handle high volumes of email requests without performance degradation.
- **Compliance & Security**: Ensures sensitive data is processed securely and adheres to organizational compliance standards.
- **Notification System**: Sends confirmation emails to users once their ticket is created and assigned.

---

##  Prerequisites
- **UiPath Studio** (2021.10 or later)
- **UiPath.Mail.Activities** package for email integration
- Access to:
  - Company email account (IMAP/Outlook)
  - Ticketing system API or web portal
- .NET Framework 4.6.1 or higher
- Valid credentials stored securely in **Orchestrator Assets** or **Windows Credential Manager**

---

## ⚙️ Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/<aryanverma735>/<UI-Path-BOT>.git


