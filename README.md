# Freight Booking Email Assistant

A browser-based workflow tool that turns shipment details and booking rules into consistent, copy-ready freight-booking emails.

**[Open the live demo](https://freight-booking-email-assistant.netlify.app/)**

> **Portfolio demo:** All company names, contacts, contract numbers and addresses in this repository are fictional. The original internal version used real operational data and remains private.

## At a glance

| Business need | Result |
| --- | --- |
| Repetitive freight-booking email preparation | Guided, copy-ready workflow |
| Typical processing time | Reduced from about **5 minutes to under 2 minutes** |
| Internal adoption | Used by approximately **10–15 colleagues** |
| Public data | Fictional and sanitised |

## Problem

Freight booking emails repeatedly required the same operational details to be found, checked and reformatted. This slowed down routine work and made it easier to omit contract instructions, recipient details or shipment information.

## Solution

The assistant converts a multi-step manual task into a guided form. Users select a booking route, enter the shipment details and receive a structured subject line, recipient list and email body that can be copied into the next workflow step.

## How it works

1. Select a booking route or contract type.
2. Enter or paste the shipment details.
3. Apply the relevant booking rules.
4. Generate the subject line, recipient list and email body.
5. Review and copy the result into the next operational step.

## Tools and technologies

- React 18
- JavaScript and JSX
- HTML and Tailwind CSS
- Browser `localStorage`
- Netlify for static hosting

The portfolio demo does not use an external API, backend or cloud database.

## Development approach

I mapped the real booking workflow, defined the template rules and iterated the interface around the information colleagues repeatedly needed. AI tools assisted with prototyping, code generation and interface refinement. I remained responsible for the workflow definition, operational rules, testing and final decisions.

Before preparing this public version, I removed the inactive image-recognition and cloud-sync prototypes and replaced confidential operational data with fictional examples. The project demonstrates AI-assisted development; it does not claim a live AI feature or API integration.

## Impact and result

- Reduced a typical booking-email preparation task from about **5 minutes to under 2 minutes**.
- Used by approximately **10–15 colleagues**.
- Reduced repetitive formatting and information lookup.

The public repository is a sanitised demonstration of the workflow rather than the production data source.

## Live demo

[Open the sanitised Netlify demo](https://freight-booking-email-assistant.netlify.app/)

The former internal deployment is not used as a portfolio link because it contained real operational data.

## Current limitations

- Demo data is fictional and does not represent current carrier or contract terms.
- Data is stored only in the current browser unless exported manually.
- The tool prepares email content but does not send email or connect to company systems.
