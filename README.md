

---

# AquaStream360: An integrated Water System Analysis Platform

AquaStream360 is a water management and hydraulic modeling software platform.
It enables users to build, analyze, and optimize water distribution systems using data.
It aims to improve efficiency, planning, and decision-making in water utilities.

---

## Core Philosophy

AquaStream360 combines both interactive manual workflows and automated capabilities, giving users full control over network modeling, simulation, analysis, optimization and more. 

**Self-Guiding Interface:** AquaStream360 has several user-guiding features which includes visual cues, pop-ups, and status indicators, highlighting required actions, missing inputs, and next steps, ensuring users navigate workflows efficiently while retaining full control over the software. The interface communicates workflow information through visual cues and optional audio feedback, without restricting user control.

---

## Key Network Engineering Capabilities

AquaStream360 offers a broad set of features dedicated for network engineering. A **few** of these capabilities include:

- **Integrated Modeling & Analysis:** Construct, modify, simulate, and evaluate water networks.
- **Automated Network Building:** Generate hydraulic models for existing networks from structured survey data or multiple file formats (supports dozens of sources, including Excel, CSV, Shapefiles, and more).
- **Visualization:** 2D/3D graphics capable of live animations and color mapping 
ping
- **Contamination Analysis, Tracing & Automated Investigation:** Trace the movement of contaminants through the network, investigate source and spread patterns, evaluate affected zones, assess likely impacts of contamination events, and perform automated analysis to support investigations, scenario-based contamination assessment, and planning against water quality incidents.
- **Geospatial Integration:** GIS capabilities are available platform-wide, serving different purposes across the software. In network modelling, a dedicated GIS environment provides a full workspace where networks can be constructed, edited, and analysed spatially — supporting DMA and pressure zone delineation, geospatial data import, and spatial clustering, among others. Mapping capabilities are accessible throughout the software, enabling spatial context to be brought into any workflow. Topographical analysis capabilities bring an additional dimension to network analysis — for example, networks can be analysed directly on a 3D terrain surface, with performance metrics such as pressure distributions and flow conditions visualised as colour maps and animations on the actual terrain. Georeferencing can be performed with just few clicks without direct manual input.
- **Scenario Testing & Optimization:** Sandbox environments for risk-free testing and calibration.
- **Criticality & Resilience Assessment:** Analyze system robustness and component importance.
- **Disaster Modeling:** Simulate extreme events such as pipe failures or contamination.
- **Comparative Analysis:** Automatically compare multiple network states or scenarios.
- **Climate-Informed Analysis and Forecasting:** Incorporates climate and hydrological data (auto-fetched from NASA) to support planning, brings into context the influence of climate in network performance and water consumption, laying a foundation for informed decision-making. ML-driven simulation capabilities allow users to run "what-if" scenarios by adjusting input weather parameters interactively and receive outputs instantly.
- **Automated or Interactive Calibration & Optimization Tools:** Define target performance conditions, run multiple scenarios, and automatically analyze results to identify solutions that best align simulated outputs with real-world network behavior—whether for full network calibration, tank performance tuning, DMA optimization, or selected system elements.

---

## Hydraulic Simulation

Simulation is one component among several hydraulic capabilities the software offers; however, it represents a multi-capability, extensive functionality within integrated engineering workflows. AquaStream360 does not rely on a single solver but instead provides a multi-engine framework to address diverse analytical requirements:

1. **AquaPulse Simulator (Custom Simulator):** A transient simulation engine capable of modeling water hammer, pump trips, valve operations, and surge propagation, including pressure envelopes and potential cavitation.
2. **Network Integrity Simulator (Custom Simulator):** Models the influence of environmental and operational factors, such as soil chemistry, pipe aging, and operating conditions, on network integrity. It assesses pipe stresses, structural performance, failure probabilities, and overall system robustness.
3. **Optimization Evaluation Engine (Custom Simulator):** A simulation engine designed for rapid evaluation of design alternatives within large-scale optimization workflows. Instead of executing full standalone simulations for every candidate design—which becomes computationally prohibitive in large design spaces—it evaluates populations of designs efficiently within an optimization loop. This is achieved through vectorized computation, parallel execution, learning-guided search, and evolutionary update strategies. Once the optimization process converges, a full EPANET-class simulation is executed on the selected design(s) to provide final validation with complete hydraulic fidelity.
4. **Foundational and Extended Simulations:** Supports all hydraulic and water quality EPANET and WNTR simulations.

- **Water Quality Dynamics:** Visualization of contaminant propagation, persistence, and transport under varying operational conditions, available both graphically and within GIS-integrated maps.
- **Incident Tracing:** Enables tracing of contaminants throughout the network to evaluate affected zones and perform scenario-based investigations, supporting risk assessment and operational planning.

---

## Output & Reporting

Analysis forms the biggest part of AquaStream360. Every analysis can display numerous performance metrics and communicate insights that may be difficult to capture from observing raw performance data alone. Outputs are automated, context-sensitive, and interactive, and include:

- **Interactive Graphs & Visuals:** Fully responsive and manipulable, allowing users to explore trends, flows, pressures, and contaminant propagation with full control.
- **GIS Maps:** Spatial representation of hydraulic, water quality, or network data, with interactive attributes, pop-ups, and animations (1D/2D/3D). Physical infrastructure, such as buildings, can be included for realistic visualization of the environment.
- **Graphics:** Independent of GIS, capable of representing flows, pressures, network operations, and contaminant transport in immersive, manipulable views.
- **Context-Specific Visualizations:** Outputs adapt to the analysis being performed, emphasizing the most relevant performance metrics for clarity and insight.
- **Instant, Analytical Reports:** Generate detailed summaries, scenario comparisons, resilience metrics, and operational insights immediately, supporting decision-making.
- **Automated Reporting Capability:** A fully automated reporting engine that extracts data across modules and assembles a network-wide report. Book-style formatting captures detailed performance metrics (hydraulics, resilience, costs, operational issues, etc.) with graphics, imagery, tables, color maps, summaries, and captions all generated and inserted in place. Users can select which attributes to include. Reports can integrate criticality analyses if desired, or complete the process in under 10 seconds for faster outputs. Depending on network size, reports may exceed 100 pages, providing a complete view of network performance without manual compilation.
- **Export Flexibility:** Results can be exported in Excel, CSV, GIS files, CAD drawings, EPANET models, HTML, PDF, and more.

This ensures every analysis is visually rich, analytically meaningful, and contextually tailored, enabling users to explore, interpret, and communicate insights effectively.

---