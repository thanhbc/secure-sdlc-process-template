---
title: Version Control
weight: 1
level: 1
tldr: Every change to the source is tracked in GitHub.
rationale: Version control allows us to track and manage changes to our software code. As a traceability system, it provides a means to understand how our software changes, who changes it, and why it was changed.
---
# {{% param "title" %}}
{{< area_head >}}

## Background
We use **Git** for version control and **GitHub** for repository hosting and user management. All source code for our applications is stored in GitHub repositories.

## Branching Strategy

We follow a **Feature Branch + Pull Request** branching strategy:

{{< figure src="/images/feature-branch-pr.svg" alt="Feature Branch Strategy" >}}

*   The `main` branch is protected.
*   All changes must be made in a feature branch.
*   To merge changes into the `main` branch, a Pull Request must be created.
*   Pull Requests must be approved by at least one other engineer before being merged.
*   Pull Request merges create merge or squash commits to ensure a clean and traceable history.

## Protected Branches

To ensure compliance with our code review and testing processes, we protect the `main` branch with the following requirements:

*   Merges require at least one approval.
*   All automated tests (CI) must pass successfully.
*   No unresolved merge conflicts are allowed.

## ISO 27001 Compliance (Annex A.8)

Our use of GitHub for version control directly supports our compliance with ISO 27001, particularly in the area of **Asset Management (Annex A.8)**:

*   **A.8.1.1 Inventory of assets:** All of our source code, which is a critical asset, is inventoried and managed within GitHub.
*   **A.8.1.3 Acceptable use of assets:** Access to our source code is controlled through GitHub's user management and permissions system.
*   **A.8.2.3 Handling of assets:** Our branching and pull request strategy ensures that all changes to our source code are handled in a controlled and audited manner.
