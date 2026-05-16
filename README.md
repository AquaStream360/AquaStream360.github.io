
---

# AquaStream360: An Integrated Water System Analysis Platform

AquaStream360 is a water management and hydraulic modeling software platform.
It enables users to build, analyze, and optimize water distribution systems using data.
It is designed to support efficiency, planning, and decision-making in water utilities.

> **AquaStream360 is completely free. Every feature, capability, and tool described in this document is freely accessible to all users — no subscriptions, no licensing fees, no paywalls, and no feature tiers. This applies to all current and future capabilities of the platform, without exception.**

---

## Core Philosophy

AquaStream360 combines interactive manual workflows with automated capabilities, giving users full control over network modeling, simulation, analysis, optimization, and related tasks.

**Self-Guiding Interface:** AquaStream360 includes user-guiding features such as visual cues, pop-ups, and status indicators that highlight required actions, missing inputs, and next steps. These features help users navigate workflows efficiently while maintaining full control over the software. The interface communicates workflow information through visual cues and optional audio feedback, without restricting user actions.

---

## Key Network Engineering Capabilities

AquaStream360 offers a broad set of features dedicated to network engineering. A few of these capabilities include:

- **Integrated Modeling & Analysis:** Construct, modify, simulate, and evaluate water networks.
- **Automated Network Building:** Generate hydraulic models from structured survey data or multiple file formats, including Excel, CSV, and Shapefiles.
- **Visualization:** 2D/3D graphics with live animations and color mapping of flows, pressures, and other performance attributes.
- **Contamination Analysis, Tracing & Automated Investigation:** Trace contaminant movement, identify source and spread patterns, evaluate affected zones, assess impacts, and support scenario-based investigations and planning for water quality events.

- **Geospatial Integration:** GIS capabilities are available across the platform. A dedicated GIS environment supports network construction, editing, and spatial analysis, including DMA and pressure zone delineation, geospatial data import, and spatial clustering. Mapping tools are available throughout workflows to provide spatial context. Networks can also be analyzed on 3D terrain surfaces, with flows, pressures, and other performance attributes visualized using color maps and animations. Georeferencing can be completed in a few clicks without or without manual input.

- **Scenario Testing & Optimization:** Sandbox environments for testing and calibration.
- **Criticality & Resilience Assessment:** Analyze system robustness and component importance.
- **Disaster Modeling:** Simulate events such as pipe failures or contamination.
- **Comparative Analysis:** Compare multiple network states or scenarios.

- **Climate-Informed Analysis and Forecasting:** Incorporates climate and hydrological data (auto-fetched from NASA) to support planning and analysis, including the influence of climate on network performance and water consumption. ML-driven simulation enables interactive "what-if" scenarios with immediate outputs.

- **Automated and Interactive Calibration & Optimization Tools:** Define target conditions, run scenarios, and analyze results to identify configurations that best match observed or desired network behavior across flows, pressures, and other performance attributes.

---

## Hydraulic Simulation

Simulation is one component among several hydraulic capabilities in the software. AquaStream360 does not rely on a single solver but provides a multi-engine framework for different analytical requirements:

1. **AquaPulse Simulator (Custom Simulator):** A transient simulation engine for modeling water hammer, pump trips, valve operations, surge propagation, pressure envelopes, and cavitation effects.

2. **Network Integrity Simulator (Custom Simulator):** Models environmental and operational influences such as soil chemistry, pipe aging, and operating conditions. It evaluates structural response, failure probability, and overall system robustness.

3. **Optimization Engine (Custom Simulator):** A physics-consistent simulator designed for rapid evaluation of design alternatives within large-scale optimization workflows. Instead of running full standalone simulations for every candidate design—which is computationally expensive in large design spaces—it evaluates populations of designs within an optimization loop. It uses vectorized computation, parallel execution, learning-guided search, and evolutionary update strategies. Once optimization converges, a full EPANET-class simulation is executed on the selected design(s) for final validation with complete hydraulic fidelity.

4. **Foundational and Extended Simulations:** Supports all hydraulic and water quality EPANET and WNTR simulations.

- **Water Quality Dynamics:** Visualization of contaminant transport, persistence, and propagation under varying operational conditions, including spatial maps and time-based analysis.
- **Incident Tracing:** Traces contaminants through the network to identify affected zones and support scenario-based investigations for risk assessment and planning.

---

## Output & Reporting

Analysis forms a major part of AquaStream360. Each analysis can display multiple performance metrics and provide insights that are difficult to obtain from raw data alone. Outputs are automated, context-sensitive, and interactive, and include:

- **Interactive Graphs & Visualizations:** Explore flows, pressures, and other performance attributes, trends, and system behavior with full control.
- **GIS Maps:** Spatial representation of hydraulic, water quality, and network data with interactive attributes, pop-ups, and 1D/2D/3D animations of flows, pressures, and other performance attributes.
- **Graphics:** Non-GIS visual representations of flows, pressures, other performance attributes, and system behavior.
- **Context-Specific Visualizations:** Outputs adapt to the type of analysis being performed.

- **Instant Analytical Reports:** Generate summaries, comparisons, resilience metrics, and operational insights across flows, pressures, and other performance attributes.

- **Automated Reporting Capability:** Generates structured network-wide reports combining outputs from multiple modules. Includes tables, graphics, images, maps, summaries, and captions. Users can select included attributes. Reports may include criticality analysis and can be generated quickly depending on system size.

- **Export Flexibility:** Results can be exported in Excel, CSV, GIS formats, CAD drawings, EPANET models, HTML, PDF, and more.