---
title: Code Review
weight: 10
level: 1
tldr: All code changes are peer-reviewed before being merged into the main branch.
rationale: Peer review is a critical step in our development process. It helps us to identify and fix bugs, security vulnerabilities, and other issues before they reach production. It also promotes knowledge sharing and improves the overall quality of our code.
---

# {{% param "title" %}}
{{< area_head >}}

## Our Process

We use **GitHub Pull Requests** to facilitate our code review process. The process is as follows:

1.  When a developer has completed a change, they open a Pull Request.
2.  The Pull Request is assigned to at least one other developer for review.
3.  The reviewer checks the code for correctness, clarity, and security.
4.  If the reviewer has any feedback, they leave comments on the Pull Request.
5.  The original developer addresses the feedback and pushes the changes to the same branch.
6.  Once the reviewer is satisfied with the changes, they approve the Pull Request.
7.  The Pull Request can then be merged into the `main` branch.

## ISO 27001 Compliance

Our code review process supports our compliance with ISO 27001 in several ways:

*   **A.14.2.1 Secure development policy:** Our code review process is a key part of our secure development policy.
*   **A.14.2.2 System change control procedures:** Our use of Pull Requests ensures that all changes to our production systems are made in a controlled and audited manner.
*   **A.14.2.8 System security testing:** Our code review process is a form of manual security testing.
