---
title: Security Vulnerability Scanning
level: 1
weight: 30
tldr: We scan our software for security vulnerabilities before every deployment.
rationale: Automated security scanning helps us to identify and fix common security vulnerabilities before they can be exploited by attackers.
---

# {{% param "title" %}}
{{< area_head >}}

## Our Process

We use a combination of tools to scan our software for security vulnerabilities:

*   **Dependency Scanning:** We use **Dependabot** and **OSV (local)** to automatically scan our dependencies for known vulnerabilities.
*   **Static Application Security Testing (SAST):** We use a variety of SAST tools to analyze our source code for security flaws.
*   **Dynamic Application Security Testing (DAST):** We use a variety of DAST tools to test our running applications for security vulnerabilities.

## ISO 27001 Compliance

Our security scanning process supports our compliance with ISO 27001 in several ways:

*   **A.14.2.1 Secure development policy:** Our security scanning process is a key part of our secure development policy.
*   **A.14.2.8 System security testing:** Our use of security scanning tools is a form of system security testing.
*   **A.14.2.9 System acceptance testing:** Our security scanning process helps us to ensure that our systems are secure before they are deployed to production.
