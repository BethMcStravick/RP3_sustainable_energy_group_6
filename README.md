Phase 1:
This notebook analyzes hourly power output for multiple renewable energy technologies using 2025 data. 
For geothermal energy, hourly output data (MW) are summarized and converted into total energy production (MWh) through the use of trapezoidal numerical integration which is implemented into the code. The annual output is then used to calculate the capacity factor of the plant. This is then plotted to display the data over a 30-day period. 
For solar energy, hourly shortwave radiation data (W/m^2) from Open-Meteo is used as the resource input. A simplified PV model is applied to convert irradiance into electrical power using the area of the panel array and the overall efficiency of the system. The resulting data is integrated using the same trapezoidal method to recieve an estimated total annual energy production (kWh). A seven day period is plotted based on the data from the first seven days of 2025. 

Phase 2:
