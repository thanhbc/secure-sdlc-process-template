---
title: Defined Toolchain
level: 3
weight: 20
tldr: Our build and deployment toolchain is defined and managed to ensure consistency and security.
rationale: A defined toolchain is essential for building and deploying software in a secure and repeatable manner. It helps to prevent unauthorized changes and ensures that our software is built in a controlled environment.
---
# {{% param "title" %}}
{{< area_head >}}

## Our Toolchain

We use a defined set of tools for our software development lifecycle. This ensures that we have a consistent and secure process for building, testing, and deploying our software.

*   **Version Control:** GitHub
*   **CI/CD:** GitHub Actions, Jenkins
*   **Project Management:** Jira
*   **Security Scanning:** Dependabot, OSV (local)
*   **Secrets Management:** AWS Secrets Manager

## Build Environments

Our build environments are defined as code, primarily using Dockerfiles and configurations for GitHub Actions and Jenkins. This approach allows us to:

*   **Ensure consistency:** Every build runs in the same environment, reducing the risk of "it works on my machine" issues.
*   **Enable auditing:** We can track changes to our build environments over time.
*   **Improve security:** We can scan our build environments for vulnerabilities and apply security best practices.

## ISO 27001 Compliance

Our defined toolchain supports our compliance with ISO 27001 in several ways:

*   **A.12.1.1 Documented operating procedures:** Our toolchain is documented here, and the configurations are stored in version control.
*   **A.14.2.2 System change control procedures:** Our use of CI/CD pipelines ensures that all changes to our production systems are made in a controlled and automated manner.
*   **A.14.2.5 Secure system engineering principles:** Our use of security scanning tools and defined build environments helps us to build security into our systems from the ground up.
