# EPS Sensors

## Background
- The Electronic Power System of a CubeSat is critical subsytem that is responsible for generating, storing, regulating and
distributing power to all other subsystems.
- Sensors and other ICs are required to monitor the state of the system.
- Sensors/ICs include: Temperature Sensors, Current and Voltage sensors, Fuel Gauges, Battery Protection ICs

## Project Objectives
1. Understand the role of sensors in EPS.
2. Select a sensor from the list above (or one of your own) and investigate the requirements
3. Design methods to test the sensors.
4. Create a PCB to test one or more of these Sensors

## Resources to get you started
- First it's a good idea to gain a high level understanding of EPS, and the role of your chosen sensor/s.
These are some good resources:
- [EPS $1000 CubeSat](https://www.youtube.com/watch?v=G9YJTCb8phU&list=PLW7PVoULStKCJPlciXTRpPKIm9vugan-e&index=7)
- https://gomspace.com/shop/subsystems/power/nanopower-p31u.aspx
- https://www.researchgate.net/publication/353971086_A_Comprehensive_Review_on_CubeSat_Electrical_Power_System_Architectures
- You should investigate how to interface sensors with a microcontroller. E.g. What communication protocols are used,
  what microcontroller to use (we have Arduino Nanos, Espressif ESP32s, and STM32 development boards available)
  but you may also choose to use a microcontroller chip.

## Tips
- Define what you want to test and how from the start. Do you need to simulate the conditions of space? Or simulate over-current or over voltage?
- Feel free to extend this project to other aspects of EPS, e.g. battery heating, MPPT, Power distribution and operational modes.
- Do your research to understand how EPS architectures are generally structured, and the role of your chosen sensors within the system.
- Take notes and maintain documentation.
