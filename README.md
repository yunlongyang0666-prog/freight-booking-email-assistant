# Freight Booking Email Assistant

A browser-based workflow tool that turns shipment details and booking rules into consistent, copy-ready freight-booking emails.

> Portfolio demo: all company names, contacts, contract numbers and addresses in this repository are fictional. The original internal version used real operational data and remains private.

## Problem

Freight booking emails repeatedly required the same operational details to be found, checked and reformatted. This slowed down routine work and made it easier to omit contract instructions, recipient details or shipment information.

## Solution

The assistant converts a multi-step manual task into a guided form. Users select a booking route, enter the shipment details and receive a structured subject line, recipient list and email body that can be copied into the next workflow step.

## How it works

- Supports multiple contract, partner and collect-booking templates.
- Parses slash- or comma-separated booking text into form fields.
- Generates a consistent subject line, CC list and email body.
- Allows template details to be edited in the browser.
- Saves demo configuration in browser `localStorage` and supports JSON import/export.

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

The internal version reduced a typical booking-email preparation task from about five minutes to under two minutes and was used by approximately 10–15 colleagues. The public repository is a sanitised demonstration of that workflow rather than the production data source.

## Live demo

The sanitised public demo will be linked here after deployment. The existing internal deployment should not be used as the portfolio link because it contains real operational data.

## Current limitations

- Demo data is fictional and does not represent current carrier or contract terms.
- Data is stored only in the current browser unless exported manually.
- The tool prepares email content but does not send email or connect to company systems.
