# OctoUNO_Product
A curve tracer based on Arduino UNO and display on PC with a Processing program DISPLAY. 
Demonstrating also useing the 'Best Widget Ever', a product development template. And idea for a template for documentation to help beginners when developing a project / product.

See Arduino firmware and PC Processing software on the repository for the software at: https://github.com/ForrestErickson/OctoUNO  
**Note:** the software at the OctoUNO GitHub site is my first release and I may try to include in this repository in the future. 

## Project plan for OcotUNO_Product
- Display OctoUNO Back to Back Diodes
<img alt= "Display OctoUNO" src="https://github.com/ForrestErickson/OctoUNO/blob/main/ScreenShotDisplay.png" width="320" />  
- Display OctoUNO Base Emitter of NPN 2N2222
<img alt= "Display OctoUNO BE 2N2222 " src="ScreenShotDisplay_BE2N2222.png" width="320" />  
- Display OctoUNO Base Emitter of PNP 2N2907
<img alt= "Display OctoUNO BE 2N2907 " src="ScreenShotDisplay_BE2N2907.png" width="320" />  
- Display OctoUNO Base Emitter of simulated leaky NPNP 2N2222. A 10K resistor was placed in parallel with BE.
<img alt= "Display OctoUNO BE 2N2907 " src="ScreenShotDisplay_10KleakeyBE2N2222.png" width="320" />  

- Schematic OctoUNO in ExpressPCB    
<img alt= "Schematic OctoUNO]" src="/pcb/expresspcb/Schematic20210722_1633.png " width="320" />  

- PCB OctoUNO in single sided ExpressPCB  
<img alt= "PCB OctoUNO in single sided ExpressPCB]" src="/pcb/expresspcb/PCBScreenShot.png " width="320" />  

Note I started the ExpressPCB schematic and PCB with files from this resource: https://forum.expresspcb.com/community-library/package/57/


Folders:  
- firmware, holds Arduino Uno firmware for product and Processing DISPLAY.
- parts, holds specifications for all parts for PCB and enclosure etc. This folder has subfolders and a simple "Parts Master" spread sheet.
- pcb, holds the schematic and PCB design files.
- assembly, holds the folders and files for assembly of the PCB and the BWE.
- testing, holds the test procedure and testing specifications for BWE.

## This project milestones
From start of design to first production.
- 20 July 2021: schematics drawn in lab notebook cover date "Start 2013" See starting at page 76.
- 21 July: Bread board up per schematic on page 81. Software composed of UNO firmware and Proccessing Drawing working. Push unversioned Software to github at repository: https://github.com/ForrestErickson/OctoUNO
- 23 July: Added event driven serial read to OctoUNO firmware. Reading some commands that are slightly SCPI like (I don't really know yet) and add mouse control from the DISPLAY control. Add button to start ( and some times stop) data capture. Update SCH and PCB so that OctoUNO can reset it's self. Add version numbers. Modify schematic and PCB. Add button to start/stop. Add prototype area. Wire another ADC input to connector. Update firmware and display. Add notes on probe signal names. Version 0.0.3.
- 8 September: Fix Q2 schematic for PNP. Update PCB. Make new schematic and PCB screen shots which show prototype area. Schematic and PCB marked version 0.0.4.
- Late September early October: Design PCB in KiCad.
- 5 October: move files for ExpressPCB schematic and PCB into a subfolder of the pcb folder.  Added the DXF files generated by ExpressPCB.
- 9 September:  Schematic release V0.0.1 for initial review. 2021 Ordered PCB designed in KiCAD. 
- Late October: Assemble KiCad PCB based boards. Made assembly drawings from KiCAD. Tested and Found bad footprint on Q1. 
- 10 November: Updated Arduino firmware and Processing software for calibrated display.
  
## Future project milestones
 
- Push KiCAD files to github.
- Fix KiCAD Q1 foot print error
- Update Drawings for all parts in folders, electrical and mechanical 
- Update parts master to assign PartNumbers
- Review for manufacturing, testing, loading firmware, EMC, signal integrity, power distribution, safety, maximum temperature, ect...
- Update Schematic release V0.0.2 etc...
- Setup PCB software or train self for PCB manufacturing design rules.

- Schematic approved for start of PCB layout V0.1.xx 
- Enclosure design review. (Make card board mock up, Cable mock up. PCB mock up.) 
- Enclosure design freeze for prototype PCB. PCB outline and connector placement freeze.
- PCB outline import parts and make and connector placement. Make mock up for fit to enclosure
- Milestone: PCB mechanical fit test, (PCB mock up with connector fits enclosure with cables etc...)
- Component placement for optimum routing and heat and Electromagnetic compatibility.  Then route.
- Review by fabricator of PCB against design rules.
- Inventory and order parts including PCB and stencil.
- Assemble first unit(s) and engineering test.
- Engineering revise and release for rest of Prototype Run. Update of engineering, sales, legal documentation with photographs measurements of real hardware.
- Changes and repeat all of above for Pilot Run (First selleable units with serial numbers etc).



