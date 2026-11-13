# Authentication Log Analyzer

**Status:** Planned — documentation scaffold only.

## Objective
Build a Python utility that parses sample authentication logs and highlights patterns such as repeated failed logins.

## Planned Features
- Parse a documented sample log format.
- Count successful and failed authentication events.
- Group failed attempts by source address and time window.
- Export a concise summary report.
- Handle malformed lines safely.

## Planned Structure
```text
authentication-log-analyzer/
├── src/
│   └── log_analyzer.py
├── samples/
│   └── sample_auth.log
├── tests/
├── reports/
└── README.md
```

## Data & Safety
Use synthetic or properly anonymized logs only. Do not commit real usernames, IP addresses, tokens, hostnames, or other identifying operational data.

## Setup
Implementation, dependencies, and execution examples will be documented after development.

## Evidence & Results
_Add sample input, sanitized output, tests, and analysis notes after completion._

## Learning Outcomes
- File handling and parsing
- Python collections and datetime
- Basic detection logic
- Data sanitization and reporting
