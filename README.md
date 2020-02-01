## CTD_Project1
BME450 Project 1

Code URL: https://github.com/etomlin27/CTD_Project1/blob/master/BME%20450%20Tomlin%20Project%201.ipynb
Raw Code URL: https://raw.githubusercontent.com/etomlin27/CTD_Project1/master/BME%20450%20Tomlin%20Project%201.ipynb
README URL: https://raw.githubusercontent.com/etomlin27/CTD_Project1/master/README.md

# Problem Statement:

The speed of sound in water varies as a function of the medium's density; temperature, salinity, and depth (head) all contribute to variations in density and must be measured to calculate the speed of sound at a given location. In order to understand how the speed of sound changes in the ocean at a single location through various depths, CTD instruments are used to take measurements of temperature, conductivity, and pressure as they dive and surface between set depths. These can be fed into the speed of sound equation at each data point to develop a speed of sound profile vs. depth using equation (1). These profiles can then be analyzed graphically to determine how seasonal, hourly, and geographic variables affect the profile.

Equation 1:     1449.2 + 4.6(T) - 0.055(T^2) + 0.00029(T^3) + (1.34 - 0.01(T)) + 0.016Z

Where: T = temperature in degrees Celsius and Z = depth in meters
  
# Backround/ Solution/ Results:

The various ocean observatories have different periods of downtime and maintenance, as well as technical issues that make the data unavailable. As a result, dates were chosen as close to January 2, 2020 for winter and July 18, 2019 for summer as possible. In instances where the data is not available for wide periods of time surrounding these dates, identical dates from earlier years were prioritized. Even within these parameters, two of the instruments (The Oregon Slope Base Shallow Profiler and the Oregon Offshore Cabled Shallow Profiler Mooring) were recording in the selected time frame, but did not complete any dives. As a result, the speed of sound profile can only be calculated at their respective surface depths. It is important to note that the surface depths are not necessarily at the surface of the ocean and can still be seen in figure 1a-b for the Oregon Slope Base Shallow Profiler and figure 2a-b for the Oregon Offshore Cabled Shallow Profiler Mooring. The remaining instruments completed at least one dive in the 24 hour period of data analyzed and a speed of sound profile could be developed.

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure3.png)

*Figure 1a: Oregon Slope Base Shallow Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure4.png)

*Figure 1b: Oregon Slope Base Shallow Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure7.png)

*Figure 2a: Oregon Offshore Cabled Shallow Profiler Mooring SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure8.png)

*Figure 2b: Oregon Offshore Cabled Shallow Profiler Mooring SSP for Winter.*

For the remaining instruments when comparing the frequency of dives in a 24 hour period, it was not consistant for the shallow or deep insruments to perform more dives. The Oregon Offshore Cabled Deep Profiler Mooring performed many more dives than its shallow counterpart as seen in figures 3a-b but the Axial Base Shallow Profiler performed more dives than its deep counterpart as seen in figures 4a-b and 5a-b. Due to the limited data and inconsistancy of the dates, the average speed of sound profile can not be compated between instruments with any validity. Examining the data purely from a seasonal perspective and assuming the geographic proximity is negligible, it can be seen in the comparisons in figures 3-7 a-b that the summer speed of suind profle shifts the curve up, documenting a lower speed of sound nearer to the surface. This is consistant with expectations that in warmer weather, the extra sunlight results in increased temperature at the surface and increased runoff in costal areas. Both these factors lower the water density in proximity to the surface which in turn lowers the speed of sound.

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure1.png)

*Figure 3a: Oregon Shelf Surface Piercing Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure2.png)

*Figure 3b: Oregon Shelf Surface Piercing Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure5.png)

*Figure 4a: Oregon Offshore Cabled Deep Profiler Mooring SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure6.png)

*Figure 4b: Oregon Offshore Cabled Deep Profiler Mooring SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure9.png)

*Figure 5a: Oregon Slope Base Deep Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure10.png)

*Figure 5b: Oregon Slope Base Deep Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure11.png)

*Figure 6a: Axial Base Shallow Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure12.png)

*Figure 6b: Axial Base Shallow Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure13.png)

*Figure 7a: Axial Base Deep Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure14.png)

*Figure 7b: Axial Base Deep Profiler SSP for Winter.*

Regardless of the season, the maximum value for the speed of sound occured at the lowest depth for the deep sensors and the surface depth for the shallow sensors. This is likely due to the minimum value occuring between the two sensors and thus each sensor only displayes the upper or lower end of the curve. 

The effects of day vs. night could not be analyzed do to time constraints restricting the conversion of the instrument time to local time. The expected effect is that in the daytime as temperatures at the surface are higher, the speed of sound profile will shift up slightly. This effect is expected to be much less in magnitude than the similer influence of the differing season, but follow the same reasoning. The increased temperature lowers the density near the surface, but has little effect in the depths and thus raises the depth with the minimum speed of sound.


# Conclusion:

Temperature changes in the ocean, usually as a result of solar radiation measured at different times of day and different seasons in the year, has a dominant effect on the speed of sound through the water. As the temperature of the ocean in increased, especially near the surface, the speed of sound profile shifts up. This is further illistrated by examining the formula for calculating the speed of sound in water as seen in equation (1). It can then be extrapolated that further effects on ocean temperature from climate change and pollution can have a dramatic affect on the acoustic properties of the water. This in turn, will likely have a severe adverse affect on any marine life that depends on the accoustic properties for their wellbeing and survival.

# References:

https://ooinet.oceanobservatories.org/
