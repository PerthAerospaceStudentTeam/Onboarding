# Power Inhibits

# Background 
The electronic power system must have safety features as specified in the [JAXA Specifications](https://iss.jaxa.jp/kibouser/library/item/jx-espc_8c_en.pdf).
This configuration may include deployment switches, battery protection ICs and a Remove Before Flight pin. 
These features are designed to mitigate hazards, including overcharge, overdischarge and external shorts. 
Find the relavent specifications in section 3.2.

## Project Objectives
- Understand the Electrical Interface requirements outlined in the JAXA specifications.
- Design a power inhibit circuit that complies with the specifications and can be integrated into an EPS board and
  accomodate 4 Lithium Ion batteries.
- The circuit may include Battery Protection ICs, deployment switches, kill switch, RBF
- Turn the circuit into a PCB using Altium Designer.

## Tips
- The PCB needs to be able to interface with the physical switches.
- It may also be a good idea enable the pcb to be powered externally some way, so the inhibitors can be tested.
- Consider adding redundant switches and ICs
- For additional safety, incorporating an extra isolation switch or reset button on the board could be useful.

## Resources to get you started
- [JAXA Specifications](https://iss.jaxa.jp/kibouser/library/item/jx-espc_8c_en.pdf).
- [Understanding System Safety: Hazards, Controls, Inhibits, and Independence - Cal Poly ](http://mstl.atl.calpoly.edu/~workshop/archive/2013/Summer/Day%202/1130-Shaw-UnderstandingSystemSafety.pdf)
- [Small reddit thread](https://www.reddit.com/r/cubesat/comments/ckrglv/rbf_and_kill_switches/)
- https://jossonline.com/wp-content/uploads/2021/07/Final-Kim-BIRDS-BUS-A-Standard-CubeSat-BUS-for-an-Annual-Educational-Satellite-Project.pdf

This is a power inhibits diagram from the [GT-1 Mission](https://digitalcommons.usu.edu/context/smallsat/article/4895/viewcontent/SSC21_P2_48.pdf)
from the Space Systems Design Laboratory at Georgia Tech.

<img width="241" alt="image" src="https://github.com/user-attachments/assets/c5e4926b-61b0-4c78-aa99-bcbee525dccb" />

  
