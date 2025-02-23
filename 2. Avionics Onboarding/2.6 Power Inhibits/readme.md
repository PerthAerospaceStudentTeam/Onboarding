# Power Inhibits

## Background 
The electronic power system must have safety features as specified in the [JAXA Specifications](https://humans-in-space.jaxa.jp/kibouser/library/item/jx-espc_8e_en.pdf).
This configuration may include deployment switches, battery protection ICs and a Remove Before Flight pin. 
These features are designed to mitigate hazards, including overcharge, overdischarge and external shorts. 
Find the relavent specifications in section 3.2.

## Project Objectives
- Understand the Electrical Interface requirements outlined in the JAXA specifications.
- Understand the purpose of Power Inhibits and how they fit into the wider CubeSat electronic power system.
- Design a power inhibit circuit that complies with the specifications and can be integrated into an EPS board and
  accomodate 4 Lithium Ion batteries.
- The circuit may include Battery Protection ICs, deployment switches, kill switch, RBF
- Turn the circuit into a PCB using Altium Designer.

## Tips
- The PCB needs to be able to interface with the physical switches. Consider the mechanical interface in your design.
- It may also be a good idea enable the pcb to be powered externally some way, so the inhibitors can be tested.
- Consider adding redundant switches and ICs
- Consider the current capacity of the switches. This affects the trace width when routing.
- For additional safety, incorporating an extra kill switch or reset button on the board could be useful.

## Resources to get you started
- [JAXA Specifications](https://humans-in-space.jaxa.jp/kibouser/library/item/jx-espc_8e_en.pdf).
- [Understanding System Safety: Hazards, Controls, Inhibits, and Independence - Cal Poly ](http://mstl.atl.calpoly.edu/~workshop/archive/2013/Summer/Day%202/1130-Shaw-UnderstandingSystemSafety.pdf)
- [Small reddit thread](https://www.reddit.com/r/cubesat/comments/ckrglv/rbf_and_kill_switches/)
- https://jossonline.com/wp-content/uploads/2021/07/Final-Kim-BIRDS-BUS-A-Standard-CubeSat-BUS-for-an-Annual-Educational-Satellite-Project.pdf
- Inhibitor Switches that PAST has ordered already: [ZMT05ACJP00SCE](https://www.digikey.com.au/en/products/detail/c-k/ZMT05ACJP00SCE/16161380?srsltid=AfmBOoqVPIPycyup-A40ewQXsPAnRZBBdgYE5dVWQJ2ow3VlIRZyUzBj), [SS0750300F070P1A](https://www.digikey.com.au/en/products/detail/e-switch/SS0750300F070P1A/3778167?srsltid=AfmBOooJEi3PdkcblksKu35PJoMpTbgLc6Xz2kU1TYYO-kbOoVRPlCd4)

This is a power inhibits diagram from the [GT-1 Mission](https://digitalcommons.usu.edu/context/smallsat/article/4895/viewcontent/SSC21_P2_48.pdf)
from the Space Systems Design Laboratory at Georgia Tech.

<img width="241" alt="image" src="https://github.com/user-attachments/assets/c5e4926b-61b0-4c78-aa99-bcbee525dccb" />

  
