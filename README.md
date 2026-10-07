# E-Cell VIT Mumbai — GitHub Organization

> **Engineering the infrastructure behind entrepreneurship, innovation, and technology at VIT Mumbai.**

This repository contains the **organization-wide GitHub configuration, governance documents, contribution standards, templates, and automation** for **E-Cell VIT Mumbai**.

It acts as the central configuration and governance layer for repositories maintained under the E-Cell VIT Mumbai GitHub organization.

---

## Purpose

The `.github` repository exists to establish a consistent engineering culture across the organization's projects.

It provides shared standards for:

- Contribution
- Code review
- Project proposals
- Documentation
- Security
- Repository governance
- Issue management
- Pull requests
- Community conduct
- Organization-wide workflows

The goal is simple:

> **Build systems that remain useful long after the people who built them graduate.**

---

# Repository Structure

```text
.github/
│
├── profile/
│   └── README.md
│
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml
│   ├── feature_request.yml
│   ├── project_proposal.yml
│   └── documentation.yml
│
├── workflows/
│   ├── stale.yml
│   └── link-check.yml
│
├── CODEOWNERS
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── GOVERNANCE.md
├── SECURITY.md
├── SUPPORT.md
└── PULL_REQUEST_TEMPLATE.md
```

---

# What This Repository Controls

## Organization Profile

`profile/README.md`

Defines the public-facing GitHub organization profile.

It introduces:

- E-Cell VIT Mumbai
- Our mission
- Our technical ecosystem
- Entrepreneurship initiatives
- Innovation
- Open source
- Technology
- Community

---

## Contribution Standards

`CONTRIBUTING.md`

Defines how contributors work with E-Cell repositories.

This includes:

- Branching
- Commits
- Pull requests
- Code review
- Testing
- Documentation
- Security expectations
- Contribution workflow

---

## Community Standards

`CODE_OF_CONDUCT.md`

Defines the standards expected from contributors, maintainers and participants in E-Cell technical communities.

We believe that strong technical communities require both:

> **High engineering standards + professional collaboration.**

---

## Security

`SECURITY.md`

Defines how security vulnerabilities should be reported and handled.

Never report sensitive vulnerabilities through public GitHub issues.

Never commit:

```text
API keys
Passwords
Access tokens
Private keys
Database credentials
.env files
Certificates
Personal data
```

---

## Governance

`GOVERNANCE.md`

Defines how technical projects and repositories are managed.

It covers:

- Technical leadership
- Repository ownership
- Teams
- Permissions
- Maintainers
- Project lifecycle
- Technical decisions
- Open-source governance
- Intellectual property considerations
- Annual handover
- Maintainer succession

---

## Support

`SUPPORT.md`

Explains where contributors should go when they need help.

```text
Bug
 ↓
Issue

Feature
 ↓
Feature Request

Project / Initiative
 ↓
Project Proposal

Documentation
 ↓
Documentation Issue

General Question
 ↓
Discussions

Security Vulnerability
 ↓
Private Security Contact
```

---

# Issue Templates

The organization provides standardized issue forms for common types of work.

### Bug Report

Use when something is broken or behaving unexpectedly.

```text
Problem
→ Reproduction
→ Expected behaviour
→ Actual behaviour
→ Environment
→ Evidence
```

### Feature Request

Use when proposing an improvement to an existing project.

```text
Problem
→ Users
→ Proposed solution
→ Alternatives
→ Impact
```

### Project Proposal
