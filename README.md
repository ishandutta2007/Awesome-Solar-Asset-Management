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

| Platform | Description | Starting Tier Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[AlsoEnergy / PowerTrack](https://www.alsoenergy.com/)** | Solar asset monitoring and management platform for commercial and utility-scale portfolios, with multi-vendor data aggregation and O&M support. | Starts at $500/site/year (hardware logger bundle tier) | No free tier or trial; guided live demo on request |
| **[Power Factors](https://www.powerfactors.com/)** | Enterprise asset performance management platform (Drive / former Greenbyte) for multi-GW solar and wind portfolios. | Starts at $30/user/month (basic user tier entry) | No free tier or trial; personalized sales demo on request |
| **[Solar-Log](https://www.solar-log.com/)** | PV monitoring and energy management platform used for residential to commercial installations with multi-inverter support. | Starts at €20/year (WEB Enerest M package) | Free forever tier for systems up to 3 kWp; 30-day free trial for premium packages |
| **[Raptor Maps](https://raptormaps.com/)** | AI-powered aerial inspection and solar asset analytics platform that turns drone/thermal imagery into module-level insights. | Starts at $300/map (inspection mission starting rate) | No free tier or trial; live interactive demo on request |
| **[Aurora Solar](https://www.aurorasolar.com/)** | Solar design, sales, and performance platform widely used for residential and commercial project design, 3D shading analysis, and proposals. | Starts at $159/user/month (Foundation plan) | No free tier or trial; live product demo available on request |
| **[HelioScope](https://www.helioscope.com/)** | Web-based PV layout design, shading, and bankable energy yield modeling software for commercial and utility solar. | Starts at $159/license/month (Basic plan, up to 10 projects/month & 1.25 MW DC capacity) | 30-day free trial (up to 5 projects with full feature access) |
| **[Scanifly](https://scanifly.com/)** | Drone-based 3D photogrammetry and site assessment tool for PV shading analysis and layout design. | Starts at $150/user/month (base subscription tier) | No free trial or free tier; 1-project paid demo flight available |
| **[PVcase](https://pvcase.com/)** | Utility-scale and commercial PV design automation plugin for AutoCAD / Civil 3D. | Starts at $10,000/year (plus ~$2,000/year AutoCAD license requirement) | 14-day free trial (requires active AutoCAD installation and demo approval) |
| **[RatedPower](https://ratedpower.com/)** | Cloud software for utility-scale solar plant engineering and automated layout optimization. | Starts at $15,000/year (Basic enterprise plan with unlimited projects) | No free trial or free tier; 1-on-1 sales demo available on request |
| **[Deck Monitoring](https://www.deck.co/)** | Solar PV data acquisition hardware and monitoring software for commercial and industrial installations. | Starts at $500/site (includes hardware logger + 5-year monitoring license package) | No free tier or trial; hardware installation demonstration on request |
| **[Unity Monitoring](https://powerfactors.com/solutions/unity/)** | SCADA, power plant controller (PPC), and real-time monitoring suite for utility-scale PV assets. | Starts at $15,000/site/year (utility SCADA and monitoring package) | No free tier or trial; live SCADA environment demo available on request |
| **[DroneDeploy Solar](https://www.dronedeploy.com/)** | Drone mapping, thermal inspection, and 360-degree construction progress tracking platform. | Starts at $329/month (or $4,188/year for Individual plan) | 14-day free trial with full drone mapping and 360 ground capture (no credit card required) |
| **[HelioVolta / SolarGrade](https://solargrade.io/)** | Fieldwork, inspection, and O&M work-order management software for solar PV assets. | Starts at $39/user/month (Pro plan) | 14-day free trial with full mobile app and workflow access |
| **[SolarNexus](https://www.solarnexus.com/)** | Solar CRM, project management, and sales quoting workflow software for installers and developers. | Starts at $49/user/month (Solo base platform tier) | 14-day free trial available upon request |
| **[Solargis](https://solargis.com/)** | Solar resource data, irradiance, satellite climate data, and bankable PV yield simulation services. | Starts at €4,800/year (Solargis Prospect base subscription) | Free forever tier for 1 MWp system simulation & free global solar maps; no trial for full suite |



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
