# Signal-Driven Outreach Automation

Auto-draft and send personalized LinkedIn messages when connections accept your invitations.

## Workflow

1. **Gmail Trigger** - Catches LinkedIn acceptance emails
2. **Get Message** - Fetches full email content
3. **Extract Data** - Pulls name, job title, company, profile URL
4. **Draft Message** - Creates personalized message template
5. **Send Preview** - Emails draft to you for approval
6. **Send LinkedIn** - One-click send to LinkedIn

## Setup

- n8n instance
- Gmail connected
- LinkedIn profile URL extracted from email

## Files

- `Signal-Driven Outreach Automation.json` - n8n workflow export
