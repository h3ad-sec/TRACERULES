# TRACERULES

**Detection Query Arsenal — Part of [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/)**

TRACERULES is a curated collection of detection queries mapped to MITRE ATT&CK tactics and techniques. Queries are available in KQL, Sigma, and XQL formats, sourced from the [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) data repository.

## Features

- Detection queries mapped to ATT&CK tactic and technique
- Supports KQL (Microsoft Sentinel / Defender), Sigma, and XQL (Cortex XDR)
- Filter by platform (KQL / Sigma / XQL)
- Full-text search across query titles and descriptions
- Lazy-loaded query content — manifest loads on start, full query loads on view
- One-click copy to clipboard

## Query Structure

Each detection entry includes:
- Title
- ATT&CK tactic and technique reference
- Description
- Platform-specific query

## Data Source

Queries live in [QUERYVAULT](https://github.com/h3ad-sec/QUERYVAULT) under `detections/kql/`, `detections/sigma/`, and `detections/xql/`. TRACERULES reads from the manifest at load time.

## Live Tool

[h3ad-sec.github.io/TRACERULES](https://h3ad-sec.github.io/TRACERULES/)

## Part of H3AD-SEC

TRACERULES is a sub-tool under [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/), the detection engineering hub of the [H3AD-SEC](https://h3ad-sec.github.io) platform.


## H3AD-SEC Platform Modules

| Module | Tools |
|--------|-------|
| [H3AD-X](https://h3ad-sec.github.io/H3AD-X/) | X-VERDIKT, PARSE-X, DNSCOPE |
| [H3AD-AI](https://h3ad-sec.github.io/H3AD-AI/) | INSIGHT-AI, QUERYCRAFT-AI, FPLENS-AI, ATTMAP-AI, CHRONO-AI, THREATBRIEF-AI, PERSONA-AI, DEBRIEF-AI, MALBRIEF-AI |
| [H3AD-DETECT](https://h3ad-sec.github.io/H3AD-DETECT/) | TRACERULES |
| [H3AD-HUNT](https://h3ad-sec.github.io/H3AD-HUNT/) | HYPOS, PIVEX, TRACEPULSE |
| [H3AD-OPS](https://h3ad-sec.github.io/H3AD-OPS/) | QUICKTRACE, SHIFTLOG |
| [H3AD-DF](https://h3ad-sec.github.io/H3AD-DF/) | REGSCOPE, MALBRIEF-AI, EVTXPARSE, ARTIFACTDB |
| [H3AD-IR](https://h3ad-sec.github.io/H3AD-IR/) | DEBRIEF-AI, CASEBOARD |
