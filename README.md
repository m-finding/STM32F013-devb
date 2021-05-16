# STM32F103-devb
#### STM32F103 Development Board  
This repository includes all manufacturing files for an STM32f103 Dev. Board - a STM Blue-pill-inspired project.  
  
Features:  
- STM32F103C8T6 MCU
- SWD interface
- Bootmode header
- Breadboard compatible
- 2 Timer LEDs


Instructions for ordering (files adapted to JLCPCB assembly service):
  - go to jlcpcb.com
  - click "quote now"
  - upload gerber.zip
  - Fill in L1-L4 in layer stackup (follow filenames)
  - Choose "Specify a Location" in "Remove Order Number"
  - activate SMT Assembly option and choose "Assemble Top Side"
  - click next
  - Upload BOM and CPL file
  - click next
  - review component selection (if nothing is in red you're good)
  - Done!

##### ToDo:
- fix USB OTG  

#### Assembly references:
  



Front:
![STM32F103_front.png](/STM32F103_front.png)
Back:
![STM32F103_back.png](/STM32F103_back.png)
