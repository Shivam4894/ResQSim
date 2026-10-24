# ResQSim — Emergency Response Decision Simulator

ResQSim is a flood emergency response planning and simulation prototype designed to explore how limited rescue resources can be allocated across affected zones.

## Overview

During floods, rescue teams may need to prioritize multiple affected areas while working with limited boats, passenger capacity, travel time, and operational windows. ResQSim allows users to explore these trade-offs through a deterministic simulation.

## Key Features

- **Citizen Flood Reporting:** Submit hypothetical or observed flood reports through a form.
- **Coordinator Dashboard:** Review and manage submitted reports.
- **Resource Allocation Simulation:** Compare two strategies:
  - **Plan A — Nearest-First:** Prioritizes reachable zones based on travel time.
  - **Plan B — Severity-Weighted Triage:** Prioritizes higher-severity zones while considering travel time and resource constraints.
- **Visual Comparison:** View estimated people reached, unmet demand, first-arrival time, and resource utilization.
- **Disaster Information Links:** Access official Indian disaster-monitoring portals, including NDMA SACHET, IMD, and Bihar FMISC.

## How to Run Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Navigate through the reporting, coordinator, disaster alerts, and simulation sections.

## Important Limitations

- ResQSim is a **demonstration and training prototype**, not a real emergency dispatch system.
- Simulation outputs are estimates based on the configured assumptions and inputs.
- Citizen reports are stored in browser local storage and are not automatically shared between different users or devices.
- Official disaster portal links do not necessarily mean live data is being fetched. Live-feed availability depends on supported data access and network restrictions.
- The system does not contact emergency services or verify real-world rescue operations.

## Technology

- HTML
- CSS
- JavaScript
- Browser local storage

## Official Information Sources

- [NDMA SACHET](https://sachet.ndma.gov.in/)
- [India Meteorological Department](https://mausam.imd.gov.in/)
- [Bihar FMISC River-Level Monitoring](https://beams.fmiscwrdbihar.gov.in/Alerttotalinfo/realtimetotal.aspx)

---

**Project:** ResQSim  
**Purpose:** Flood response planning, resource allocation, and strategy comparison for educational demonstration.
