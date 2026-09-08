# Awesome-Solar-Asset-Management

## Top Solar Asset Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on PV Monitoring, Performance Analytics, O&M, Aerial Inspection, Design & Portfolio Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Solar Asset Management**. These tools help owners, operators, and EPCs monitor production, detect underperformance, manage O&M, analyze aerial/thermal inspections, and optimize solar portfolios across residential, commercial, and utility-scale assets.



**Examples** include AlsoEnergy (PowerTrack), Power Factors, Solar-Log, Deck, RatedPower, PVcase, Raptor Maps, HelioScope, Scanifly, Aurora Solar, Unity Monitoring, DroneDeploy Solar, HelioVolta, SolarNexus, and Solargis (the category leaders).



**Open-source emphasis**: Enterprise portfolio and utility-scale asset management platforms are largely commercial. Strong open-source options exist for self-hosted monitoring dashboards, performance quality control, inverter data collection, and energy management. **Solectrus**, **Sunalyzer**, **MyEMS**, **Pecos**, and related projects provide practical foundations. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AlsoEnergy / PowerTrack](https://www.alsoenergy.com/)**  

  Leading solar asset monitoring and management platform for commercial and utility-scale portfolios, with multi-vendor data aggregation, performance analytics, and O&M support.



- **[Power Factors](https://www.powerfactors.com/)**  

  Enterprise asset performance management platform (including Drive / former Greenbyte) for large renewable portfolios, offering monitoring, analytics, and reporting across technologies.



- **[Solar-Log](https://www.solar-log.com/)**  

  Established PV monitoring and energy management platform used for residential to commercial installations with multi-inverter support.



- **[Raptor Maps](https://raptormaps.com/)**  

  AI-powered aerial inspection and solar asset analytics platform that turns drone/thermal imagery into actionable module- and equipment-level insights.



- **[Aurora Solar](https://www.aurorasolar.com/)**  

  Solar design, sales, and performance platform widely used for residential and commercial project design, shading analysis, and proposals.



- **[HelioScope, Scanifly, PVcase, RatedPower](https://www.helioscope.com/)**  

  Design and engineering tools for PV system layout, bankable yield modeling, drone-based site assessment, and utility-scale design.



- **[Deck, Unity Monitoring, DroneDeploy Solar, HelioVolta, SolarNexus](https://www.deck.co/)**  

  Additional platforms covering monitoring, construction, O&M workflows, aerial data, and project lifecycle management.



- **[Solargis and resource platforms](https://solargis.com/)**  

  Solar resource data, irradiance, and bankable climate services that support design and performance assessment.



- **[Other solar APM & monitoring platforms](https://www.alsoenergy.com/)**  

  OEM portals, multi-vendor aggregators, and specialized O&M or inspection tools used across the solar industry.



## Open-Source GitHub Projects



- **[Solectrus](https://github.com/solectrus/solectrus)**  

  Self-hosted photovoltaic dashboard for monitoring solar production, consumption, battery usage, grid exchange, and financial performance. Designed for local control and clear energy insights.



- **[Sunalyzer](https://github.com/BorisBrock/Sunalyzer)**  

  Free, open-source, vendor-independent solar monitoring system with local data storage, responsive web UI, and support for self-hosting on Raspberry Pi or NAS via Docker.



- **[MyEMS](https://github.com/MyEMS/myems)**  

  Open-source Energy Management System with support for PV, energy storage, microgrids, and related assets. Suitable for broader energy and carbon monitoring that includes solar.



- **[Pecos (Sandia National Laboratories)](https://github.com/sandialabs/pecos)**  

  Open-source Python package for performance monitoring and quality-control testing of time-series data, originally developed for photovoltaic system monitoring and reporting.



- **[MeterMan and inverter monitoring tools](https://github.com/aamcrae/MeterMan)**  

  Utilities for monitoring solar PV output and electrical metering, with support for specific inverters and export to services such as PVOutput or Home Assistant.



- **[Solarmon and manufacturer-specific loggers](https://github.com/Elwell/solarmon)**  

  Scripts and suites for polling inverters (e.g., via Modbus) and uploading production data.



- **[Home Assistant + InfluxDB + Grafana stacks](https://github.com/lewei50/Solar-PV-Monitoring)**  

  Popular open-source combinations for local PV monitoring, energy dashboards, and long-term storage using widely adopted home/industrial automation tools.



- **[Other PV monitoring & IoT projects](https://github.com/search?q=solar+PV+monitoring+OR+photovoltaic+dashboard+OR+inverter+modbus)**  

  Community projects for string-level monitoring, SCADA-style supervision, and research-oriented performance analysis.



### Additional Strong Open-Source Options



- **pvlib-python**: Widely used open-source library for PV performance modeling and irradiance calculations.

- **Modbus / inverter protocol tools**: Libraries and gateways for reading data from common inverter brands.

- **Time-series databases & visualization**: InfluxDB, TimescaleDB, Grafana, and Prometheus stacks tailored for energy data.

- **Aerial & inspection helpers**: Open-source tools for processing drone imagery (generally paired with commercial analytics for large fleets).

- **O&M work-order systems**: General open-source CMMS tools adapted for solar maintenance tracking.

- Research frameworks for fault detection, soiling estimation, and digital twins of PV plants.



**Frameworks for building custom systems**:  

For self-hosted monitoring of residential or smaller commercial systems, start with **Solectrus**, **Sunalyzer**, or a **Home Assistant + Grafana** stack.  

**MyEMS** and **Pecos** support broader energy management and performance quality control.  

Utility-scale portfolio management, AI aerial inspection (Raptor Maps-style), bankable design (Aurora, HelioScope, PVcase), and multi-GW SCADA/APM remain dominated by commercial platforms (AlsoEnergy, Power Factors, Solar-Log, etc.).  

Many operators combine open-source edge monitoring and dashboards with commercial portfolio analytics and O&M platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Solar asset management systems influence revenue, safety, and contractual performance guarantees. Data quality, cybersecurity, and reliable alerting are critical.

- Open-source monitoring tools provide excellent transparency and local control but require proper integration with inverters/meters, secure networking, and ongoing maintenance. They are not automatic replacements for validated commercial APM platforms used on large fleets.



---



**Made for solar asset managers, O&M teams, EPCs, performance engineers, and renewable energy technologists.**  

Let's advance open, local-first, and interoperable tools for solar monitoring and asset management where practical.
