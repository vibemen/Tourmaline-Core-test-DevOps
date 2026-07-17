# Tourmaline-Core-test-DevOps
Tourmaline Core DevOps Internship Test Assignment – OpenNebula in Pipeline


This repository contains my implementation of the Tourmaline Core DevOps Internship Test Assignment. The goal is to automate the setup of a tiny OpenNebula cloud in a GitHub Actions pipeline, including the creation of resources (2 small Ubuntu VMs and MinIO S3) and covering it with E2E tests.

---

### Completed stages
- **Stage 1: Manual Setup:** Manually install OpenNebula on a local Ubuntu machine, create the required resources (2 small Ubuntu VMs and MinIO S3 on a dedicated VM), and configure networking. No automation tools used.

Future stages will be added as they are completed and merged via PRs.

---



### How to Reproduce

- Clone this repository: ```git clone https://github.com/vibemen/Tourmaline-Core-test-DevOps.git```
- Follow the runbook in the respective stage's Markdown file (e.g., docs/stage-1-manual-setup.md).
- For Stage 1, execute the commands on a clean Ubuntu installation. 

### Repository Structure

- docs/: Contains Markdown runbooks for each stage.
- screenshots/: Images referenced in the documentation.
