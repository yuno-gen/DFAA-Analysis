# **This Project is DFAA Analysis of contiguous the USA**


DFAA (Drought-Flood abrupt alternation)  events are examples of compound events, and combines drought and flood events and may exacerbate the adverse impacts caused by individual droughts or floods
DFAA could seriously threaten water security, ecological security, socio-economic, and human health.

<p align='center'>
<img width="470" alt="Screenshot 0006-07-28 at 9 17 50 AM" src="https://github.com/user-attachments/assets/1bb579d2-1445-45e3-ac1c-a483bc1c1568">
</p>

The efficient way for DFAA analysis is to use SPEI (Standardized precipitation evapotranspiration Index)
SPEI is the difference between the precipitation received and the atmospheric evaporation demand. So, when precipitation is less but more evaporation the SPEI value is negative suggesting a dry condition, on the flip side positive value refers to wet condition


**Dataset**

The dataset used is U.S. Gridded SPEI derived from nClimGrid-Monthly dataset timescale of 1 month.
Dimensions of the dataset: 
   *  (Lat: 596) x (Lon: 1385) x (Time: 1552)
   *  Total 129 years of SPEI monthly data.
   *  Time period: 1895-2023.
Multiple dataset derived from this for different analytical purposes.

  ### How many such DF events do we experience?
  ### When do we see such events happening?
  
<p align='center'>
<img width="475" alt="image" src="https://github.com/user-attachments/assets/10b60526-16dc-4dce-8e3e-9ef400eaba07">
</p>

As illustrated by this plot, the north central and east coast regions exhibit a notably high mean annual frequency of Drought - Flood (DF) events (IN: avg-103).

<p align='center'>
<img width="475" alt="image" src="https://github.com/user-attachments/assets/6f240836-d2d3-4766-a706-34840ddfadd3">
</p>

The plot above shows DF events affects the north central area in the winter season. For the other regions DF event is sporadic.
Indiana: South-Fall, Mid-Winter, North-Spring


**Libraries Used**: Xarray, cartopy, pymannkendall
**Skills Learned**: Multi-dimensional and long time series data manipulation on IU HPC
