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
- Fully responsive — works on mobile, tablet, and desktop

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


## H3AD-SEC Platform Modules

| Module | Tools |
|--------|-------|
| [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) | X-VERDIKT, PARSE-X, DNSCOPE, MAILSCOPE |
| [H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/) | INSIGHT-AI, QUERYCRAFT-AI, FPLENS-AI, ATTMAP-AI, CHRONO-AI, MALBRIEF-AI, PROMPTVAULT |
| [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) | TRACERULES |
| [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) | HYPOS, PIVEX, TRACEPULSE |
| [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) | QUICKTRACE, SHIFTLOG, PHISHOPS |
| [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) | REGSCOPE, MALBRIEF-AI |
| [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/) | PHISHBOOK |
| [H3AD-LEARN](https://h3ad-sec.github.io/H3AD-LEARN/) | Threat Hunting (9 ch), LOLBAS (8 ch) |
