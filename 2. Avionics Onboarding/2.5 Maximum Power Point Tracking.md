#  **Maximum Power Point Tracking**
## **Introduction**
MPPT or Maximum Power Point Tracking is used with inconsistent power sources to maximise energy output. A good example of the use case for MPPT is with renewables such as solar or wind, even optic power transmission.
CubeSats typically operate with power consumption below a kilowatt and can function solely on batteries. However, since their operational lifespan exceeds a single day, a recharging method is necessary. This is achieved using solar power through photovoltaic (PV) cells.

The fundamental relationship of Power (W), Voltage (V), and current (I) is P = V * I. As shown in the graph below, the current remains constant up to the maximum voltage point, after which the relationship between current and voltage follows an inverse exponential trend. To determine the maximum power output, you must identify the point where the derivative of current with respect to voltage (dI/dV) is equal and opposite to the I/V ratio or where the derivative of power with respect to voltage (dP/dV) equals zero. (you can also use the bisection method). 


![PV_2-format](https://github.com/user-attachments/assets/1b69dead-ffd1-4224-b39c-b84852c72a21)



## **Task**
For this task, you are required to research MPPTs, and;
- Write in short, an overview of the inner workings of an MPPT, and;
- Design a basic MPPT circuit using Altium to supply a battery with its recommended charge requirements.

## **Resources**
The PV cells and batteries can be found below 

Battery:
https://au.mouser.com/ProductDetail/Ultralife/UBBL23-C1?qs=HL%252BYNjdyZ0tF6TFfGMnuew%3D%3D

Solar Panels:
https://www.digikey.com/en/products/detail/anysolar-ltd/SM401K08L/13999183
