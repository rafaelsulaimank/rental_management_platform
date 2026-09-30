# rental_management_platform
# Rental Management Platform

**An operational platform for managing long-term property rentals.**

A custom web application developed for a client managing long-term rental properties. The platform is deployed and actively used by the client.

It brings property, tenant, contract and payment information into one administrative interface, with tools for tracking outstanding balances and handling recurring tasks.

## Business Need

The client needed a centralized way to manage rental operations, including:

- Connecting properties, tenants and rental contracts.
- Tracking rent and maintenance charges.
- Recording full and partial payments.
- Identifying overdue balances.
- Monitoring contract expiration dates.
- Organizing tenant documentation.

These requirements informed the application’s data model, workflows and administrative interface.

## My Role

I translated the client’s requirements into functional workflows and participated directly in development, deployment and ongoing improvements.

My involvement included:

- Defining the application scope and business rules.
- Structuring relationships between properties, tenants, contracts and payments.
- Developing and refining functionality with AI assistance.
- Reviewing application behavior against the client’s requirements.
- Deploying the application and configuring scheduled tasks.
- Resolving issues and improving workflows based on client feedback.

## Implemented Features

### Property and Tenant Management

- Centralized property and tenant records.
- Relationships between properties, tenants and contracts.
- Tenant document management.

### Contract Management

- Contract start and end dates.
- Monthly rent and maintenance amounts.
- Security deposit records.
- Payment due dates and grace periods.
- Contract status and PDF attachments.

### Payment Tracking

- Recurring monthly payment generation.
- Manual payment recording.
- Support for partial payments.
- Tracking of rent and maintenance components.
- Historical payment records.

### Outstanding Balances and Dashboards

- Visibility into pending and overdue payments.
- Dashboards supporting collection follow-up.
- Balance tracking following contract extensions.

### Operational Alerts

- Alerts for contracts approaching expiration.
- Alerts for expired contracts.
- Tracking of handled alerts.
- Scheduled daily alert generation.

## Technology Stack

| Component | Technology |
| --- | --- |
| Application framework | Laravel |
| Administrative interface | Filament |
| Programming language | PHP |
| Database | MySQL |
| Web server | Nginx |
| Hosting | DigitalOcean |
| Scheduled processing | Laravel Scheduler and cron |
| Interface language | Spanish |

## Application Structure

The application centers on the following entities:

- **Property:** Rental property information.
- **Tenant:** Tenant records and associated documentation.
- **Contract:** Rental terms linking a property and tenant.
- **Payment:** Monthly charges, recorded payments and outstanding balances.
- **Alert:** Contract-related notifications and their handling status.
- **Tenant Document:** Documents associated with tenant records.
- **User:** Application access.

## Scheduled Operations

The application runs daily tasks using the America/Mexico_City timezone:

- **07:00:** Generate monthly payment records.
- **08:00:** Generate and update contract alerts.

## AI-Assisted Development

AI was used to support implementation, troubleshooting and iteration.

Business requirements and client feedback guided the development process. AI-generated suggestions were reviewed, adapted and checked against application behavior before being incorporated.

This project reflects my approach to using AI as a practical development tool while retaining responsibility for scope, technical decisions and delivery.

## Current Status

**Deployed and actively used by the client.**

The implemented scope includes rental administration, contracts, payment tracking, outstanding balances, tenant documents and operational alerts.

Automatic bank reconciliation is a potential future enhancement and is not part of the current implementation.

## Repository Scope

This repository presents a case study of a privately deployed client application.

Production source code, credentials, database exports, client documents and identifying tenant information are not included. Any screenshots published here will use fictional or anonymized data.

## What This Project Demonstrates

- Translating business requirements into a working application.
- Connecting technical implementation with operational needs.
- Delivering and maintaining a client solution.
- Using AI to support practical software development.
- Improving application workflows through real client feedback.

## Author

**Rafael Sulaiman Karam**  
Technology entrepreneur and business leader  
Mexico City, Mexico

[www.sulaisafe.com](https://www.sulaisafe.com)
