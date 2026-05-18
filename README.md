# QUICKTRACE

**Daily Workflow Query Library — Part of [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/)**

QUICKTRACE is a curated library of operational SOC queries for day-to-day analyst workflows. Queries are organized by category and platform, sourced from the [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) data repository.

## Features

- Queries organized into four operational categories
- Supports KQL (Microsoft Sentinel / Defender), Sigma, and XQL (Cortex XDR)
- Filter by category (AUTH / NETWORK / ENDPOINT / CLOUD)
- Full-text search across titles and descriptions
- Lazy-loaded query content — fast initial load
- One-click copy to clipboard

## Categories

| Category | Focus |
|----------|-------|
| AUTH | Authentication events, login failures, privilege escalation |
| NETWORK | Traffic anomalies, DNS, lateral movement |
| ENDPOINT | Process activity, file writes, scheduled tasks |
| CLOUD | Cloud service events, IAM, storage access |

## Data Source

Queries live in [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) under `quicktrace/auth/`, `quicktrace/network/`, `quicktrace/endpoint/`, and `quicktrace/cloud/`.

## Live Tool

[h3ad-sec.github.io/QUICKTRACE](https://h3ad-sec.github.io/QUICKTRACE/)

## Part of H3AD-SEC

QUICKTRACE is a sub-tool under [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/), the SOC operations hub of the [H3AD-SEC](https://h3ad-sec.github.io) platform.
