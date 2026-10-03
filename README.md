# OWASP Juice Shop Top 10 Lab

This repository contains a hands-on application security assessment report mapping executed OWASP Juice Shop v20.2.0 challenge vulnerabilities to the OWASP Top 10:2025 standard.

## Security Notice

> **Vulnerable by Design:** OWASP Juice Shop intentionally contains security
> weaknesses for training. This repository documents an educational lab and
> does not contain the Juice Shop application source or real credentials.

Use the material only in an isolated environment you own or are explicitly
authorized to test. Do not deploy the vulnerable application in production or
expose it to an untrusted network. To reproduce the documented version, use the
version-tagged image `bkimminich/juice-shop:v20.2.0` and bind it to loopback.

Do not deploy this project or the referenced vulnerable application in
production.

## Contents

Comprehensive technical assessment report documenting hands-on vulnerability execution, the OWASP Top 10:2025 mapping matrix, technical findings with proof-of-concept steps, defensive remediation controls, and environment configuration.

The report summarizes the tested workflows and defensive lessons. It does not
publish reusable exploit payloads or private raw traffic evidence.
## Scope

Testing was performed against a dedicated, locally hosted instance of OWASP Juice Shop (v20.2.0) running in an isolated environment. The objective was to validate and map active application vulnerabilities directly against the OWASP Top 10:2025 framework through hands-on exploitation, traffic analysis, and source verification.

## Read or reproduce

Open the DOCX locally to review the recorded assessment; no vulnerable service is
needed for that review. To reproduce the recorded version in an isolated lab with
Docker installed, bind the published port only to loopback:

```text
docker run --rm --name juice-shop-lab --publish 127.0.0.1:3000:3000 bkimminich/juice-shop:v20.2.0
```

Use a disposable environment and synthetic accounts. Stop it with
`docker stop juice-shop-lab`. A version tag is mutable; record and verify the image
digest for a reproducible new run. The existing report records historical tests;
this documentation update did not rerun the assessment or verify the image.

## Repository map

```text
owasp-juice-shop-top-10-lab/
|-- .github/
|-- .gitignore
|-- OWASP Juice Shop Top 10 2025 Mapping.docx
|-- README.md
`-- SECURITY.md
```

Source, fixtures and historical reports serve different purposes; follow the setup and safety boundaries above before running any code.
