# Project Datum Major (DM) — Core Engine

## Overview
Project Datum Major (DM) is an ethical data verification platform and registered B-Corp dedicated to establishing Grounded Data Sovereign Truth. By deploying the **Orbital Trust Engine**, DM calculates an immutable Asset Reputation Score for orbital and terrestrial data tracking systems, providing a robust liability shield for operators and insurers against data corruption, spoofing, and synchronization errors.

## Repository Structure
This repository is strictly modular to isolate the front-facing client interfaces from the core mathematical and ingestion pipelines:

*   **/frontend-landing**: Clean, high-conversion static UI built for early-access email capture and professional authority.
*   **/orbital-engine**: Core architectural logic and state machine definitions.
*   **/ingestion**: Data capture scripts for parsing TLE (Two-Line Element) records, Celestrak APIs, and MAGELLAN DNA files.
*   **/verification**: The "Sovereign Minimum" validation algorithms.
*   **/api-gateway**: Scoped, read-only interface schemas designed for external stakeholders and insurers.
*   **/database**: Time-series schemas and structural migrations.
*   **/docs**: System manifests, operational blueprints, and B-Corp compliance data.

## Design Identity
The user interface must convey absolute institutional trust, authority, and elegance.
*   **Aesthetic**: Streamlined, sophisticated, and professional.
*   **Strict Exclusions**: No cyberpunk, lo-fi, or cluttered "techbro" design frameworks.
*   **Core Palette**: Primary structural grounding utilizes `#6D6E5A`. Digital signal and interactive accents utilize `#CD7AFF`. Highlights and interface alerts utilize `#cce07b`.
