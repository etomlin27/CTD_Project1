# CTD_Project1
BME450 Project 1

Code URL: https://github.com/etomlin27/CTD_Project1/blob/master/BME%20450%20Tomlin%20Project%201.ipynb
Raw Code URL: https://raw.githubusercontent.com/etomlin27/CTD_Project1/master/BME%20450%20Tomlin%20Project%201.ipynb
README URL: https://raw.githubusercontent.com/etomlin27/CTD_Project1/master/README.md

Problem Statement:

The speed of sound in water varies as a function of the medium's density; temperature, salinity, and depth (head) all contribute to variations in density and must be measured to calculate the speed of sound at a given location. In order to understand how the speed of sound changes in the ocean at a single location through various depths, CTD instruments are used to take measurements of temperature, conductivity, and pressure as they dive and surface between set depths. These can be fed into the speed of sound equation at each data point to develop a speed of sound profile vs. depth using equation (1). These profiles can then be analyzed graphically to determine how seasonal, hourly, and geographic variables affect the profile.

Equation 1:     1449.2 + 4.6(T) - 0.055(T^2) + 0.00029(T^3) + (1.34 - 0.01(T)) + 0.016Z
Where: T = temperature in degrees Celsius and Z = depth in meters
  
Backround/ Solution/ Results:

The various ocean observatories have different periods of downtime and maintenance, as well as technical issues that make the data unavailable. As a result, dates were chosen as close to January 2, 2020 for winter and July 18, 2019 for summer as possible. In instances where the datay is not available for wide periods of time surrounding these dates, identical dates from earlier years were prioritized. Even within these parameters, two of the instruments (The Oregon Slope Base Shallow Profiler and the Oregon Offshore Cabled Shallow Profiler Mooring) were recording in the selected time frame, but did not complete any dives. As a result, the speed of sound profile can only be calculated at their respective surface depths. It is important to note that the surface depths are not necessarily at the surface of the ocean and can still be seen in figure 1a-b for the Oregon Slope Base Shallow Profiler and figure 2a-b for the Oregon Offshore Cabled Shallow Profiler Mooring. The remaining instruments completed at least one dive in the 24 hour period of data analyzed and a speed of sound profile could be developed.

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure3.png)

Figure 1a: Oregon Slope Base Shallow Profiler SSP for Summer.

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure4.png)

Figure 1b: Oregon Slope Base Shallow Profiler SSP for Winter.




Conclusion:

References:

https://ooinet.oceanobservatories.org/
