---
title: Secrets Management
level: 1
weight: 30
tldr: All secrets are stored securely in AWS Secrets Manager.
rationale: Proper secrets management is essential for protecting our systems and data from unauthorized access. Leaked secrets can lead to serious security breaches.
---

# {{% param "title" %}}
{{< area_head >}}

## Our Process

We use **AWS Secrets Manager** to store all of our secrets, including API keys, database credentials, and encryption keys. This provides us with a number of benefits:

*   **Centralized management:** All of our secrets are stored in a single, centralized location.
*   **Fine-grained access control:** We can control who has access to which secrets.
*   **Auditing:** We can track who has accessed which secrets and when.
*   **Automatic rotation:** We can automatically rotate our secrets to reduce the risk of them being compromised.

## ISO 27001 Compliance

Our use of AWS Secrets Manager supports our compliance with ISO 27001 in several ways:

*   **A.9.4.1 Information access restriction:** We use AWS Secrets Manager to restrict access to our secrets on a need-to-know basis.
*   **A.9.4.4 Use of privileged utility programs:** We use AWS Secrets Manager to control access to our privileged utility programs.
*   **A.12.3.1 Information backup:** We use AWS Secrets Manager to back up our secrets.
*   **A.14.1.1 Information security requirements analysis and specification:** We use AWS Secrets Manager to help us to meet the information security requirements of our systems.
