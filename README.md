# n8n Workflow Portfolio

A collection of reusable n8n workflow templates, automation examples, and case studies focused on CRM, sales, customer operations, and business process automation.

These projects demonstrate how I design automation systems that reduce repetitive work, improve data accuracy, prevent missed follow-ups, and connect business tools through APIs.

## About This Repository

This repository contains public-safe versions of selected automation projects.

All published workflows are:

- Sanitized to remove client information
- Shared without credentials, tokens, passwords, or private URLs
- Configured with fictional example data
- Intended for education, demonstration, and portfolio purposes
- Designed to be reviewed and tested before production use

Complete production workflows and client-specific implementations are kept private.

## Featured Workflow

### US Business Day and Holiday Utility

An n8n utility workflow that checks whether a date is a valid US business day.

It can be used to prevent automated emails, reminders, task creation, or scheduled actions from running during:

- Saturdays and Sundays
- US federal holidays
- Observed holidays
- Timezone-sensitive non-working days

Possible use cases include:

- Sales follow-up sequences
- Meeting reminder workflows
- Customer onboarding
- CRM task automation
- Invoice and payment reminders
- Scheduled email campaigns

## Automation Areas

The projects in this portfolio may include examples related to:

- CRM workflow automation
- Lead routing and nurturing
- Sales follow-up sequences
- Meeting scheduling and reminders
- Email reply detection
- Customer onboarding
- Document processing
- Salesforce automation
- Microsoft Outlook and Microsoft 365 integrations
- API integrations
- Error handling and human-review workflows
- Duplicate prevention and data validation

## Tools and Technologies

- n8n
- Salesforce
- Microsoft Outlook
- Microsoft 365
- SharePoint
- Calendly
- REST APIs
- Webhooks
- JavaScript
- JSON
- OAuth
- GitHub

## Workflow Design Principles

I build workflows with reliability and maintainability in mind.

Common safeguards include:

- Input validation
- Duplicate detection
- Test mode
- Draft mode
- Retry logic
- Error notifications
- Human-review checkpoints
- Execution logging
- Batch limits
- Stop conditions
- Clear workflow documentation

## Using the Workflow Templates

1. Download the workflow JSON file.
2. Open your n8n instance.
3. Create a new workflow.
4. Select **Import from File**.
5. Upload the JSON file.
6. Add your own credentials.
7. Replace all placeholder values.
8. Test the workflow using fictional data.
9. Review every node before activation.
10. Activate it only after successful testing.

Never add real credentials directly inside workflow fields or Code nodes.

## Security

No working credentials are included in this repository.

Before using any template, replace values such as:

```text
SAMPLE_RECORD_ID
user@example.com
REPLACE_WITH_ENVIRONMENT_VARIABLE
https://example.com
