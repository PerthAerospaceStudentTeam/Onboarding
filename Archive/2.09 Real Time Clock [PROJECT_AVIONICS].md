# Real Time Click
This project involves researching possible real time clock modules for the flight computer along with researching batteries which are allowed on CubeSats. You will design a minature PCB (No larger than 25cm^2 area) which contains an RTC, battery and communication pins. Afterwards you will write software drivers for the RTC and calculate the lifespan of the RTC with one battery

## Background 
An RTC typically is included in a CubeSat to enable timestamps for communication. If a CubeSat was to lose power or reset, then the timestamps on communication packets would also reset, causing confusion with knowing the order of packets if they were to arrive from different ground stations (Typically multiple ground stations on different sides of the Earth for higher coverage is used).
A microcontroller typically contains a built-in RTC, however faults with a microcontroller may sometimes reset this RTC. If no other method of setting a time to the microcontroller (such as a GPS fault, or constant resetting), this may cause an issue. One method would be to use an external RTC with its own dedicated power source. This would separate any faults from the microcontroller from severely affecting the RTC.
The use of an external RTC is regulated in space, due to the use of batteries.

## ☑️ Project Deliverables
1. Research into regulations on a real time clock (RTC) & batteries
2. Research into suitable batteries which are allowed on CubeSats, typically they are small and low power
3. Research into suitable RTC modules for the flight computer
4. Design of a minature circuit to include the RTC, battery and flight computer connections. Ensure the battery is removable.
5. Turn the circuit into a PCB in Altium Designer. (PCB should have an area of less than 25cm^2).
6. Develop software drivers to communicate with the RTC and decode any data.
7. Calculate the lifespan of the RTC through its use of power and the battery capacity.

## Tips
- Think about how the power is connected, the RTC should still run even if the flight computer was to lose power
- Sometimes, communication lines may damage ICs if the ICs are not powered on.
- Flight computer connections can include 0.1" headers, FPC cables (typically PAST uses 16 / 4 pin ones)
- Some RTCs may use BCD instead of binary for formatting data.
- Ensure your communication protocol requirements are upheld (such as pull-up resistors if required)

## Project Extension

## Resources
- [CubeSat Design Specifications from Cal Poly](https://static1.squarespace.com/static/5418c831e4b0fa4ecac1bacd/t/62193b7fc9e72e0053f00910/1645820809779/CDS+REV14_1+2022-02-09.pdf)
