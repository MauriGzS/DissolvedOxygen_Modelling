# Dissolved Oxygen Modelling in the Urban Canal Network of Padua

Process-based water quality modelling group work for Nature In Context Course at the University of Padova. This repository develops and compares numerical models to simulate continuous dissolved oxygen (DO) dynamics along a canal stretch in Padova using empirical monitoring data.

## Project Goal
- Develop a simple, process-based water quality model grounded in a real case study.
- Simulate continuous **dissolved oxygen (DO) concentration mg/L** at the downstream monitoring section of an urban canal stretch in Padova.
- Follow a ecological modelling workflow (system definition, model conceptualization, formulation, calibration/parameter estimation, validation/evaluation, and comparison).
- Build and compare at least two model formulations balancing **goodness-of-fit** and **model complexity**:
  - **1-State-Variable Model:** DO concentration over time in the modelled canal stretch.
  - **2-State-Variable Model:** DO and Biochemical Oxygen Demand (BOD) concentrations over time in the modelled canal stretch.

## Dataset and Inputs
Provided by the professor, stored locally and excluded from Git via `.gitignore`:

    • The data recorded by miniDOT Loggers at both an upstream and a downstream section of the canal network: battery voltage, water temperature, dissolved oxygen (DO) concentration and percent saturation, and an indicator for measurement quality. Please note that the DO concentration (in mg/L) in the downstream section is the target state variable to be simulated in the group work.
    • Water level time series measured by pressure gauges at both upstream and downstream section. Please notice that water level refers to the elevation of the water surface with respect to a fixed datum (in this case it is the IGM40 one), and NOT to the water depth in the canals.
    • Some characteristics of the urban sub-basins draining (i.e., discharging combined sewer water) in between the upstream and the downstream sections.
    • Some discharge measurements obtained in sections located close to the monitoring stations together with the corresponding water levels at the stations.
    • Canal bed elevation profiles of the monitoring sections, obtained using acoustic doppler profilers.
    • Precipitation and Global Solar Radiation time series measured at the ARPAV monitoring station in Padua.
    • A map of the hydrographic network of Padua, including the position of the monitoring stations.
