# Client Status Portal

A secure web portal that shows each client live sprint progress, releases, demos and their open
issues, fed from Jira, GitHub and SharePoint, with every client-facing update reviewed by a
Technical Lead and published by a Delivery Manager.

- Production: https://clientstatus.agripal.com
- Stack: Spring Boot 3 (Java 21), React, PostgreSQL 16, Keycloak, Docker Compose

## Branches

| Branch | Purpose |
| --- | --- |
| `main` | Released code; deploys to production |
| `dev`  | Ongoing work; deploys to staging (clientstatus-staging.agripal.com) |
