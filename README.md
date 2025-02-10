# Automated System Health Check
This project automates system health checks using GitHub Actions and Ansible.
It runs daily at 5 AM and generates a system report.

## Features:
- Checks CPU, Memory, and Disk Usage
- Generates a report
- Fully automated using GitHub Actions

## Usage
- Clone the repo
- Run the playbook using `ansible-playbook ansible/health_check.yml`
- View the report at `/tmp/health_report.txt`
