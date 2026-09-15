# OWASP Juice Shop Top 10 Lab

This repository contains a hands-on application security assessment report mapping executed OWASP Juice Shop v20.2.0 challenge vulnerabilities to the OWASP Top 10:2025 standard.

## Security Notice

> **Vulnerable by Design:** OWASP Juice Shop intentionally contains security
> weaknesses for training. This repository documents an educational lab and
> does not contain the Juice Shop application source or real credentials.

Use the material only in an isolated environment you own or are explicitly
authorized to test. Do not deploy the vulnerable application in production or
expose it to an untrusted network. To reproduce the documented version, use the
pinned image `bkimminich/juice-shop:v20.2.0` and bind it to loopback.

Do not deploy this project or the referenced vulnerable application in
production.

## Contents

Comprehensive technical assessment report documenting hands-on vulnerability execution, the OWASP Top 10:2025 mapping matrix, technical findings with proof-of-concept steps, defensive remediation controls, and environment configuration.

The report summarizes the tested workflows and defensive lessons. It does not
publish reusable exploit payloads or private raw traffic evidence.
## Scope

Testing was performed against a dedicated, locally hosted instance of OWASP Juice Shop (v20.2.0) running in an isolated environment. The objective was to validate and map active application vulnerabilities directly against the OWASP Top 10:2025 framework through hands-on exploitation, traffic analysis, and source verification.
