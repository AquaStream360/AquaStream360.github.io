# AquaStream360: An integrated Water System Analysis Platform

AquaStream360 is an advanced, integrated software platform for managing water distribution systems. It offers several capabilities dedicated for network modeling, operational analysis, and infrastructure management, which include data analysis and processing, topographical analysis with GIS and 2D/3D modes, water quality simulations, advanced animations and graphics, automated and manual analysis, scenario testing, optimization, calibration, climate-informed simulation, and evaluation of water distribution networks. All modules are fully capable on their own, and GIS, 2D/3D visualization, and advanced graphics can be enabled or used depending on the user’s workflow. **Georeferencing is fast and can be performed with just two clicks.**

---

## Core Philosophy

AquaStream360 combines robust manual workflows and automated capabilities, giving users full control over network modeling, simulation, and analysis. Modules operate independently, while GIS, 2D/3D visualization, and advanced animations are platform-wide features that can be enabled as needed.

**Self-Guiding Interface:** AquaStream360 guides users with visual cues, pop-ups, and status indicators, highlighting required actions, missing inputs, and next steps, ensuring users navigate workflows efficiently while retaining full control over the software. The interface communicates workflow information through visual cues and optional audio feedback, without restricting user control.

---

## Key Network Engineering Capabilities

AquaStream360 offers a broad set of features dedicated for network engineering. A few of these capabilities include:

- **Integrated Modeling & Analysis:** Construct, modify, simulate, and evaluate water networks.  
- **Automated Network Building:** Generate hydraulic models for existing networks from structured survey data or multiple file formats (supports dozens of sources, including Excel, CSV, Shapefiles, and more).
- **Visualization:** 2D/3D flow animations, advanced animations, pressure maps, graphical analysis, animated flow paths, and animated contaminant movement within the network.  
- **Water Quality Simulation:** Simulate urban water quality conditions, contaminant propagation, decay, persistence, and transport under varying operational states.  
- **Contamination Analysis, Tracing & Automated Investigation:** Trace the movement of contaminants through the network, investigate source and spread patterns, evaluate affected zones, assess likely impacts of contamination events, and perform automated analysis to support advanced investigations, scenario-based contamination assessment, and planning against water quality incidents.  
- **Geospatial Integration:** GIS features integrated into all modules, enabling spatial visualization of hydraulic and water quality results when networks are georeferenced.  
- **Scenario Testing & Optimization:** Sandbox environments for risk-free testing and calibration.  
- **Criticality & Resilience Assessment:** Analyze system robustness and component importance.  
- **Disaster Modeling:** Simulate extreme events such as pipe failures or contamination.  
- **Comparative Analysis:** Automatically compare multiple network states or scenarios.  
- **Climate-Informed Analysis and Forecasting:** Incorporates climate and hydrological data (auto-fetched from NASA) to support planning, brings into context the influence of climate in network performance and water consumption, laying a foundation for informed decision-making. Advanced ML-driven simulation capabilities allow users to run "what-if" scenarios by adjusting input weather parameters interactively and receive outputs instantly.  
- **Advanced Automated Calibration Tool:** Set conditions, run scenarios, and automatically evaluate trends and values that closely match actual network performance.  
- **Calibrator Tool:** Computational evaluation engine for network modeling. Define operating conditions, simulate scenarios, measure deviations, rank alternatives, and identify optimal configurations. Generates structured, real-time analytical reports, integrating data from multiple modules for network-wide insight.

---

## Hydraulic Simulation Capabilities

Simulation is one component among several hydraulic capabilities the software offers, however it is ___ workflows:  

1. **AquaPulse (In-House Simulator):** A transient simulation engine capable of modeling water hammer, pump trips, valve operations, and surge propagation. It tracks pressure envelopes and potential cavitation, reflecting phenomena typically modeled only by high-end commercial tools.  
2. **Environmental and Material Modeling (In-House Simulator):** Accounts for environmental and operational context, e.g., soil chemistry, pipe aging, operating conditions, and other factors affecting infrastructure performance. Performs structural integrity and risk analysis, enabling assessment of pipe stresses, structural performance of network components, failure probabilities, and burst risks.  
3. **Monitoring (In Development):** Leverages the platform’s simulation and analysis outputs to provide real-time system performance evaluation, predictive assessment, and early detection of operational risks.  
4. **Foundational Hydraulic Simulations:** **EPANET-style** steady-state and extended-period analyses for baseline network hydraulics.  
5. **WNTR Integration:** Resilience assessments, leak simulations, and failure scenario analyses.  

**Supports all EPANET and WNTR simulations.**

---

## Output & Reporting

Analysis forms the biggest part of AquaStream360. Every analysis can display numerous performance metrics and communicate insights that may be difficult to capture from observing raw performance data alone. Outputs are highly automated, context-sensitive, and interactive, and include:

- **Interactive Graphs & Visuals:** Fully responsive and manipulable, allowing users to explore trends, flows, pressures, and contaminant propagation with advanced control.  
- **GIS & 3D Maps:** Spatial representation of hydraulic, water quality, or network data, with interactive attributes, pop-ups, and animated flows in 3D. Physical infrastructure, such as buildings, can be included for realistic visualization of the environment.  
- **Advanced 3D Graphics:** Independent of GIS, capable of representing flows, pressures, network operations, and contaminant transport in immersive, manipulable views.  
- **Context-Specific Visualizations:** Outputs adapt to the analysis being performed, emphasizing the most relevant performance metrics for clarity and insight.  
- **Instant, Analytical Reports:** Generate detailed summaries, scenario comparisons, resilience metrics, and operational insights immediately, supporting decision-making.  
- **Advanced Automated Reporting Capability:** A fully automated reporting engine that extracts data across modules and assembles a comprehensive, network-wide report. Book-style formatting captures detailed performance metrics (hydraulics, resilience, costs, operational issues, etc.) with several, insight-rich, graphics, imagery, tables, color maps, summaries, and captions all generated and inserted in place. Users can select which attributes to include. Reports can integrate criticality analyses if desired, or complete the process in under 10 seconds for faster outputs. Depending on network size, reports may exceed 100 pages, providing a complete view of network performance without manual compilation.  
- **Export Flexibility:** Results can be exported in Excel, CSV, GIS files, CAD drawings, EPANET models, HTML, PDF, and more.

This ensures every analysis is visually rich, analytically meaningful, and contextually tailored, enabling users to explore, interpret, and communicate insights effectively.

---

