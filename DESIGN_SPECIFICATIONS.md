# Design Specifications Form

**Date:** October 20, 2025

## Team Information

**Team Name:** Team-o-Matic

**Team Members:**
- Leonard Chau
- Samuel Zimmerickers
- Ben Grimes
- Mohammed Azam

## Stakeholders

### Port Authorities (e.g., Port of Oakland)
- Emission reduction, infrastructure upgrade

### Terminal Operators/Logistics Companies
- Yard operations and vehicle fleets

### Fleet Operators/Equipment Managers
- Maintenance, scheduling, readiness of vehicles

### Airport Ground Operations Teams
- Rail yard operations managers
- Manufacturing and warehouse facilities

### Technical and Workforce
- Vehicle operators/drivers
- Maintenance crews/technicians
- Electrical/facilities engineers

### Energy and Infrastructure
- Utility companies/grid operators
- Battery suppliers and OEMs
- Third party charging infrastructure providers

### Regulatory and Community
- Environmental regulatory agencies (e.g., CARB)
- Local communities (NOx near ports)
- Policymakers and transportation departments

### Economic and Strategic
- Government grant agencies/funding bodies
- Investors/port development authorities
- Insurance and safety regulators

## Problem Statement

Current shipping port ground vehicles rely almost entirely on diesel engines for 24-hour operations. This dependency creates high emissions, operational noise, maintenance overhead, and refueling downtime. Existing battery technologies are limited by long charging times, making it incompatible with the continuous workflows of shipping ports. There is a need for a modular energy system that enables zero-emission and continuous operation without disrupting existing logistics.

Many high-duty industries, such as shipping ports, airports, and rail yards, rely on fossil fueled vehicles to maintain 24-hour operations. This dependency creates high emissions, operational noise, and downtime during refueling. Current electric battery technologies are hindered by long charging times, making them incompatible with continuous workflows.

Our project proposes a modular battery swapping system designed to enable continuous, zero-emission operations without disrupting existing logistics. The initial application focuses on shipping port yard vehicles, serving as a representative use case for broader implementation across other continuous-operation industries.

## Attributes

| Function(s) | Requirement(s) |
|------------|----------------|
| **360 degree movement** | Zero turning radius operation. Must be able to align itself with the recipient vehicle in tight spaces. |
| **Charging Station** | Recharge multiple depleted battery packs simultaneously. Must be able to use or minimally alter existing port power infrastructure to achieve this goal. |
| **Swap Mechanism** | Enable rapid battery exchange to minimize vehicle downtime. Swap time < 2 mins. Swap is automated and safe. |
| **Operational Continuity** | Allow uninterrupted operations. Maintain vehicle operation indefinitely by rotating charged/depleted packs without stopping for recharge. |
| **Safety systems** | Ensure safe operation for users during swap. Insulations, lockout/tagout, electrical handling compliance. |
| **Scalability** | Support adaptation to different vehicle types, sizes, and industries. Design modular, reconfigurable; swap station and pack standardized to support future scaling. |
| **Emissions** | Reduce emissions and noise. Demonstrate zero emissions for prototype, quantify equivalent potential diesel consumption. |

## Constraints

| Constraint(s) | Limit(s) |
|---------------|----------|
| **Cost** | Purchase needed parts for the prototype. <= $200 |
| **Size** | Does not interfere with other machines, keep operating costs to a minimum. < 4ft³ |
| **Scale** | Use of a scaled model to demonstrate functionality. No full size vehicles or batteries |
| **Timeline** | Build and demonstrate prototype to completion with report. < 2 semesters |
| **Safety** | Adhere to SFSU and lab guidelines. No high voltage (< 48V). Safety adherence |

## Objectives

| Objective(s) | Metric(s) |
|--------------|-----------|
| **Speed** | Needs to be able to swap without causing additional downtime. Must take less than 90 seconds. |
| **Reliability** | Needs to be able to perform its function with 100% accuracy. Zero failed swaps during presentation. |
| **Minimize cost** | Make this system economically attractive versus the current implementation. Cost analysis of energy vs fuel for representative use cases. |
| **Continuous operation** | The system can continuously operate while battery swapping. No throughput loss during power swap. |
| **Adaptability** | Demonstrate use beyond the shipping industry. Ease of implementation. |
| **Modularity** | Battery packs are interchangeable between all system vehicles. Battery pack swappable and compatible everywhere. |

---

*This document serves as the foundational design specifications for the Team-o-Matic modular battery swapping system project.*

