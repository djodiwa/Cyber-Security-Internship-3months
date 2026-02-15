# Analysis

## OCR Extracted Text
Task 2: Operating System Security Fundamentals (Linux & Windows)

Tools:
- Primary: Ubuntu Linux (VM) / Windows Defender
- Alternatives: Kali Linux, Fedora

Hints / Mini Guide:
1. Install a Linux virtual machine using VirtualBox or use Windows security settings.
2. Explore user accounts, permissions, and access control mechanisms.
3. Learn file permissions using chmod, chown, and ls -l.
4. Understand administrator vs standard user privileges.
5. Enable firewall (UFW in Linux or Windows Firewall).
6. Identify running processes and services.
7. Disable unnecessary services to reduce attack surface.
8. Document best OS hardening practices.

Deliverables:
- OS security checklist document

Final Outcome:
- Understanding OS-level security and hardening

## Summary
The mini-guide covers foundational operating system security practices for both Linux and Windows, with emphasis on account/permission hygiene, firewall enablement, and service hardening.

## Observations
- The task is tool-flexible and supports either Linux VM workflow or Windows security workflow.
- It emphasizes access control and privilege boundaries.
- It includes both configuration tasks and documentation output.

## Risks (if security related)
- Over-privileged user accounts can increase compromise impact.
- Incorrect file permissions can expose sensitive data.
- Disabled/misconfigured firewall can expose unnecessary network paths.
- Unneeded running services expand attack surface.

## Mitigation / Improvements
- Apply least-privilege for user roles and administrative access.
- Audit and enforce secure file ownership and permissions regularly.
- Keep host firewall enabled with minimum required allow-rules.
- Disable or remove non-essential services after dependency validation.
- Maintain and periodically update an OS hardening checklist.

## TODO
- TODO: Add the original guide image file into `assets/images/` when available as a local file.
