# Security Policy

## Supported version

Only the latest commit on `main` is maintained.

## Vulnerable by design

OWASP Juice Shop intentionally contains vulnerabilities for security training.
This repository contains a defensive educational report, not the Juice Shop
source. Run the referenced application only on loopback or an isolated lab
network that you own or are explicitly authorized to test. Never deploy it in
production.

## Reporting a security issue

Expected Juice Shop challenge behavior is not a vulnerability in this report
repository. Use GitHub private vulnerability reporting for leaked real secrets,
unsafe repository automation, or another unintended issue. Do not disclose
sensitive evidence publicly. Rotate an exposed credential before cleanup.

## Maintainer checks

Before publishing, run `pre-commit run --all-files`, GitHub secret scanning, and
the repository policy workflow. Keep vulnerable software versions pinned and
exclude raw captures and credentials.
