---
layout: default
---

# Email Assistant

Email Assistant is Jason Doran’s privately operated system for tracking professional email conversations across accounts he owns or administers. It helps identify replies, organize follow-up reminders, and maintain job-search and business conversation records.

The Google authorization screen currently identifies the application as **Codex Job Search Gmail Connector**. Email Assistant is the shared system using that Google project; its dedicated monitoring connection requests Gmail read-only access.

## What the connection does

With the mailbox owner’s authorization, the monitoring connection reads email headers, message text, labels, and conversation identifiers. It uses recent incoming mail and historical Sent messages to recognize prior contacts, identify replies, and check monitoring coverage. Archived mail is included; routine monitoring excludes Spam and Trash.

Relevant information can be processed through Codex and delivered to Jason’s designated Telegram destinations. The system also maintains private conversation records and follow-up state. See the [privacy policy](privacy.html) for details.

## Account control

The direct monitoring connection requests only `gmail.readonly`. It cannot send, edit, delete, or mark messages. Interactive drafting and sending use separately connected ChatGPT Pages and the Gmail plugin, with Jason’s approval of the exact message before sending.

Email Assistant is for Jason’s authorized mailboxes. This documentation site does not offer public account registration or collect Google credentials.

## Contact

For questions about Email Assistant or its handling of email data, contact Jason Doran at [jason.p.doran@gmail.com](mailto:jason.p.doran@gmail.com).
