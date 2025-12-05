Task 1: Data Analysis and Dashboard Visualization

Objective:
Daikibo, a multinational manufacturing company, collects machine telemetry every 10 minutes from nine device types across its four factories located in Tokyo, Osaka, Berlin and Shenzhen. The telemetry describes machine health and can be used to estimate downtime. This task required identifying:
- The factory with the highest total machine downtime.
- The machine types responsible for most of the downtime in that factory.

Work Done:
- Loaded the provided one-month telemetry dataset (May 2021) into Tableau.
- Created a calculated measure named Unhealthy, representing 10 minutes of downtime for each unhealthy machine status.
- Built two visualizations to explore downtime:
  - Down Time per Factory, showing total downtime for each location.
  - Down Time per Device Type, showing downtime broken down by machine type.
- Combined both visualizations into a single dashboard.
- Added an interactive filter so that selecting a factory dynamically updates the machine-level breakdown.

Result:
The final dashboard revealed that Daikibo Factory Seiko (Osaka) experienced the highest total machine downtime. Using the interactive filter, the second visualization highlights the specific machine types most responsible for downtime within that factory. This provides a clear direction for maintenance prioritization and further investigation into operational issues. The screenshot of the completed dashboard is included in this folder.
