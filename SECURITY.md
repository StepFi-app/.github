# Security Policy

Security is a top priority for StepFi. This policy applies to every repository in the
[StepFi-app](https://github.com/StepFi-app) organization unless a repository publishes its own `SECURITY.md`.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, report privately through **either** of these channels:

- **GitHub private advisory** — use the "Report a vulnerability" button under the **Security** tab of the affected repository (preferred).
- **Email** — `security@stepfi.io`

You should receive an acknowledgement within **72 hours**. If you do not, please follow up to make sure we received your report.

## What to include

To help us triage quickly, please provide:

- The affected repository, branch, and commit (or deployed URL / network).
- A description of the vulnerability and its potential impact.
- Step-by-step reproduction instructions or a proof of concept.
- Any relevant logs, transaction hashes, XDR, request/response payloads, or screenshots.
- Your assessment of severity and any suggested remediation.

## Our commitment

- We will acknowledge your report within **72 hours**.
- We will provide an initial assessment and expected timeline within **7 days**.
- We will keep you informed as we work toward a fix.
- We will credit you in the advisory once the issue is resolved, unless you prefer to remain anonymous.

## Coordinated disclosure

We follow a coordinated-disclosure model. Please give us a reasonable window to remediate before any public disclosure. We will work with you to agree on a disclosure date once a fix is available.

## Scope

In scope:

- Smart contracts (`StepFi-Contracts`), API (`StepFi-API`), web (`StepFi-Web`), and mobile (`StepFi-App`) code in this organization.
- Authentication, authorization, funds handling, and data-integrity flaws.

Out of scope:

- Findings that require physical access to a user's unlocked device.
- Social engineering of StepFi staff or contributors.
- Denial-of-service via traffic volume alone.
- Reports from automated scanners without a demonstrated, exploitable impact.

## Safe harbor

We consider security research conducted in good faith and in accordance with this policy to be authorized. We will not pursue or support legal action against researchers who follow this policy. If in doubt, contact us before testing.
