# DevOps Production Incident Reports

Hands-on DevOps incident simulations focused on troubleshooting, root-cause analysis, recovery procedures, and preventive actions.

This repository documents practical Docker and DevOps troubleshooting scenarios performed in a local lab environment to build real-world operational skills.

## Incident Reports

| Incident | Description | Status |
|---|---|---|
| 001 | Docker container did not restart after WSL/Docker restart | Resolved |
| 002 | Docker port mapping misconfiguration | Resolved |
| 003 | Docker application startup failure | Resolved |

## Skills Demonstrated

- Linux troubleshooting
- Docker container lifecycle management
- Docker logs and inspection
- Container networking and port mapping
- Application startup troubleshooting
- Root-cause analysis (RCA)
- Incident recovery and verification
- Preventive actions and documentation
- Git and GitHub

## Lab Environment

- OS: Ubuntu 22.04 on WSL2
- Container platform: Docker
- Application: Python Flask
- Programming language: Python
- Version control: Git and GitHub

## Repository Structure

```text
devops-production-incident-reports/
│
├── README.md
├── incident-001-container-restart.md
├── incident-002-docker-port-mapping.md
└── incident-003-docker-startup-failure.md
```

## Troubleshooting Methodology

Each incident follows a structured troubleshooting process:

1. Identify the incident and symptoms.
2. Collect evidence using Linux and Docker commands.
3. Inspect container status, logs, configuration, and application behaviour.
4. Identify the root cause based on evidence.
5. Apply the recovery procedure.
6. Verify that the application is working.
7. Document preventive measures and lessons learned.

## Important Note

These are self-directed, production-style incident simulations conducted in a personal lab environment. They demonstrate practical troubleshooting and recovery skills and are not claimed as commercial production incident experience.

## Objective

To continuously improve hands-on Cloud and DevOps troubleshooting skills through practical incident simulations and maintain documented evidence of technical learning.
