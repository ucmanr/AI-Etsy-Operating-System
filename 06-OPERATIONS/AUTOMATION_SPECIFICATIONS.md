# Automation Specifications (Blueprints)

## Purpose
To define the exact "If This, Then That" (IFTTT) workflows to be built in Make.com or Zapier, removing manual administrative work.

## Spec 1: New Sale → Customer Onboarding
- **Trigger**: New Etsy Order.
- **Action 1**: Add customer email to MailerLite/ConvertKit "New Buyer" sequence.
- **Action 2**: Log the sale in a Google Sheet (Date, Product, Revenue, AOV).
- **Action 3**: Send a Slack/Discord notification to the founder: "🎉 New Sale: [Product Name] for $[Amount]".

## Spec 2: Review Request (7 Days Post-Purchase)
- **Trigger**: 7 days after "New Sale" trigger.
- **Action**: Send automated, friendly Etsy message (using the template from `05-MARKETING/REVIEW_GENERATION_SYSTEM.md`).

## Spec 3: Weekly Analytics Pull
- **Trigger**: Every Friday at 9:00 AM.
- **Action**: Fetch Etsy Stats (Views, Orders, Revenue) via API.
- **Action**: Append to the `15-DASHBOARDS/WEEKLY_REVENUE_TRACKER.md` (via GitHub API or Google Sheets).

## AI Prompt for Manus
"Write a detailed, step-by-step Make.com scenario specification for 'Spec 1: New Sale → Customer Onboarding'. Include the exact modules needed, data mapping between Etsy and MailerLite, and error-handling rules."
