# Linux Monitoring Scripts

This project contains a collection of simple Linux monitoring scripts used to check system health and assist with troubleshooting.

## Purpose

These scripts simulate common diagnostics performed by help desk technicians and system administrators when investigating system issues.

## Scripts

### system-health-check.sh
Collects basic system information including:
- system uptime
- disk usage
- memory usage
- running processes

### check-service.sh
Checks whether a specified service is running.

## Example Usage

```bash
./scripts/system-health-check.sh
./scripts/check-service.sh ssh