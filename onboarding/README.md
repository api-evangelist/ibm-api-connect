# Programmatic API Onboarding — IBM API Connect

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for IBM API Connect: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`ibm-api-connect-api-auth.mjs`](ibm-api-connect-api-auth.mjs)
- Run `node ibm-api-connect-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/07/18/ibm-api-connect-real-consumer-api-no-front-door/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
