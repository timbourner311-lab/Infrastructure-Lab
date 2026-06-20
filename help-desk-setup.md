Goal: Deployed osTicket for help desk automation.

Components: Integrated local mail server fetching via IMAP and automated task scheduling using cron.
Lessons Learned:
"Resolved initial mail fetching delays by correctly configuring IMAP settings and verifying that the cron job was properly scheduled to trigger the mail fetcher. This highlighted the importance of matching service-level configurations with system-level task automation for reliable help desk operation."****

### System Hardening & Access Control.
To ensure the security of the osTicket environment, I implemented principle-of-least-privilege access by creating dedicated staff accounts with restricted roles, rather than using the primary administrator account for daily tasks. Additionally, I enforced strong password complexity requirements for all user logins to prevent unauthorized access to the help desk infrastructure.
