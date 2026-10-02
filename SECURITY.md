# Security and Public Data Policy

This repository is intended for public demonstration.

## Public-data rule

Do not commit customer-specific or confidential information.

This includes, but is not limited to:

- customer/company names
- Dynatrace tenant URLs
- environment IDs
- account IDs
- real hostnames
- internal DNS names
- real IP addresses
- customer application names
- customer business-service names
- service-offering names
- employee or team identities
- customer email addresses
- real Dynatrace entity IDs
- API tokens
- OAuth secrets
- passwords
- certificates
- internal file paths
- ticket or incident identifiers
- management-zone names
- confidential tags
- internal topology identifiers

## Demo-data standard

Public examples should use synthetic TechTurn demo identities such as:

- `TechTurn Demo PROD`
- `PaymentsPortal`
- `TechTurn Digital Platform`
- `tt-app-01`
- `tt-app-02`
- `tt-api-01`
- `payment-service`
- `customer-service`
- `gateway-service`
- `192.0.2.x`
- `run_demo_001`

## Before committing

Review:

1. screenshots
2. HTML output
3. JSON
4. CSV
5. logs
6. generated reports
7. metadata
8. source maps
9. embedded JavaScript data
10. browser-visible URLs

Large generated HTML reports can contain embedded customer data even when the first screen appears sanitized.

## Public interactive demo

The public interactive demo should use fully synthetic TechTurn data rather than a redacted customer report.
