ElecticaOS - Autobidder Simulation

This repository contains a high-fidelity, browser-based simulation of ElecticaOS, an AI-driven energy trading and optimization platform inspired by Tesla's Autobidder. The project is built as a single-file HTML application using React and Tailwind CSS for easy demonstration and prototyping.
The simulation is split into two distinct versions, showcasing the evolution from a real-time monitoring system to a predictive, automated control platform.

Live Demos
Version 1.0 - Live Monitoring Dashboard
Version 2.0 - Predictive Control Platform
(Note: You will need to replace the placeholder URLs above with your actual GitHub Pages links after deployment.)

Key Features

Version 1.0: Live Monitoring Dashboard
Real-Time Grid Monitoring: Displays live grid status (Surplus/Deficit), total demand, and total supply from the distributed battery fleet.
Dynamic Asset Tracking: Simulates a fleet of Homeowner, Commercial, and Industrial batteries with continuously updating State of Charge (SoC) and power output based on their status (Charging, Discharging, Grid Support, Idle).
Live P&L Analysis: Features a continuous, multi-line chart that plots accumulating revenue from Arbitrage, FCAS, and Demand Response second-by-second. Includes a transparent breakdown of the live calculation rates.
Geospatial Fleet View: A predefined map of Indore showing the location of all assets, with markers colored by their real-time status.
Secure Login: A professional login screen to access the dashboard.

Version 2.0: Predictive Control Platform (In progress)
Simulated "Opticaster" Engine: The dashboard is driven by a simulated ML optimization engine that generates automated control signals.
24-Hour Dynamic Projections: Visualizes live, continuously evolving 24-hour forecasts for Grid Demand, Solar Generation, and IEX Market Prices, based on realistic historical data patterns.
Automated Command Dispatch: The Opticaster's control signals (e.g., "DISPATCH: RTM Arbitrage") are derived in real-time from the price forecasts, simulating how an autobidder makes profit-driven decisions.
Interactive Forecasts: Users can hover over the projection charts to see the precise forecasted values for any given hour.
Full Navigational UI: Includes a functional sidebar to switch between the predictive Dashboard, a live Assets overview, and the Strategy configuration panel.
Technology Stack
Frontend: React (run via in-browser Babel transpilation)
Styling: Tailwind CSS
Visualizations: Chart.js for P&L and forecast charts
Deployment: Packaged as single, self-contained HTML files that require no build step or server.

How to Run Locally
No server or build process is required.
Clone the Repository:
git clone [https://github.com/your-username/electica-os.git](https://github.com/your-username/electica-os.git)


Navigate to Directory:
cd electica-os
