# test-ssl-audit-template

## Getting Started

Fork this repository to create a new repository for auditing your SSL configurations. Keep the repo public or private as you prefer. Public repos allow others to view your audit results but benefit from free Github Actions minutes.

Customise the list of URIs in `.github/workflows/audit.yml` to include the domains you wish to audit.

Customise the `.testssl-rules.json` file to include any specific rules you wish to apply during the audit.

## About

This repository is designed to audit SSL configurations using the Github Action:
- https://github.com/s01ipsist/test-ssl-auditor-action
