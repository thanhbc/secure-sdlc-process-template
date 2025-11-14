---
title: Dependency Management
weight: 20
tldr: All dependencies are tracked and scanned for vulnerabilities.
rationale: Managing the dependencies in our software is critical for security and license compliance. We must ensure that we are not using any components with known vulnerabilities or licenses that are incompatible with our business model.
level: 1
---

# {{% param "title" %}}
{{< area_head >}}

## Background

Our software is built using various open-source and third-party components. These dependencies can introduce security risks and licensing issues if not managed properly.

## Our Process

We use the following tools and processes to manage our dependencies:

*   **Dependency Scanning:** We use **Dependabot** and **OSV (local)** to automatically scan our dependencies for known vulnerabilities.
*   **License Compliance:** We review the licenses of all our dependencies to ensure that they are compatible with our products.
*   **Software Bill of Materials (SBOM):** We maintain a list of all the dependencies used in our software.

## ISO 27001 Compliance

Our dependency management process supports our compliance with ISO 27001 in several ways:

*   **A.14.2.1 Secure development policy:** Our dependency management process is a key part of our secure development policy.
*   **A.14.2.8 System security testing:** Our use of dependency scanning tools is a form of system security testing.
*   **A.18.1.4 Privacy and protection of personally identifiable information:** By ensuring that our dependencies are secure, we are helping to protect the privacy of our users.
