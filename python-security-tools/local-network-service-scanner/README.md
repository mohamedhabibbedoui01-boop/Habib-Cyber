# Local Network Service Scanner

**Status:** Planned — documentation scaffold only.

## Objective
Create a Python learning tool to identify reachable hosts and common services inside a private lab network.

## Planned Features
- Require an explicit target range and clearly bounded port list.
- Use conservative timeouts and rate limits.
- Report reachable services with timestamps.
- Export results to a text or JSON report.
- Include tests using mocked sockets.

## Planned Structure
```text
local-network-service-scanner/
├── src/
│   └── scanner.py
├── tests/
├── examples/
└── README.md
```

## Authorized Scope Only
Run scans only against devices you own or have explicit permission to assess. Keep demonstrations inside a local lab. Do not add stealth, evasion, exploitation, or internet-wide scanning features.

## Setup
Commands, dependencies, and usage examples will be added after implementation.

## Evidence & Results
_Add a lab topology, sanitized output, test results, and limitations after completion._

## Learning Outcomes
- Python sockets
- TCP connection concepts
- Timeouts and error handling
- Responsible testing and scope control
