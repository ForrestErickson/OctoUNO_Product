# OctoUNO_Product
A curve tracer based on Arduino UNO and display on PC with a Processing program DISPLAY
Demonstrating also use the Best Widget Ever, a product development template. And idea for a template for doucmentation to help beginners when developing a project / product.

## Project plan for OcotUNO_Product
![Schematic OctoUNO](/pcb/Schematic20210722_1633.png)
![PCB OctoUNO](/pcb/PCBScreenShot.png)  
Note I started the schematic and PCB with files from this resource: https://forum.expresspcb.com/community-library/package/57/


Folders:  
- firmware, holds Arduino Uno firmware for product and Processing DISPLAY.
- parts, holds specifications for all parts for PCB and enclosure etc. This folder has subfolders and a simple "Parts Master" spread sheet.
- pcb, holds the schematic and PCB design files.
- assembly, holds the folders and files for assembly of the PCB and the BWE.
- testing, holds the test procedure and testing specifications for BWE.

## This project milestones
From start of design to first production.
- 20 July 2021 schematics drawin in lab notbook cover date "Start 2013" See starting at page 76.
- 21 July bread board up per schematic on page 81. Software composed of UNO firmware and Proccessing Drawing working. Push unversioned Software to github at repository: https://github.com/ForrestErickson/OctoUNO
- 23 July Added event driven serial read to OctoUNO firmware. Reading some commands that are slightly SCPI like (I don't really know yet) and add mouse control from the DISPLAY control. Add button to start ( and some times stop) data capture. Update SCH and PCB so that OctoUNO can reset it's self. Add version numbers. Modify schematic and PCB. Add button to start/stop. Add prototype area. Wire another ADC input to connector. Update firmware and display. Add notes on probe signal names. Version 0.0.3.

## Future project milestones
 
- Update Drawings for all parts in folders, electrical and mechanical 
- Update parts master to assign PartNumbers
- Schematic release V0.0.1 for initial review
- Review for manufacturing, testing, loading firmware, EMC, signal integerity, power distribution, safety, maximum temprature, ect...
- Update Schematic release V0.0.2 etc...
- Setup PCB software or train self for PCB manufacturing designe rules.

- Schematic approved for start of PCB layout V0.1.xx 
- Enclosure design review. (Make card board mockup, Cable mock up. PCB mockup.) 
- Enclosure design freeze for prototype PCB. PCB outline and connector placement freeze.
- PCB outline import parts and make and connector placement. Make mockup for fit to enclosure
- Milestone: PCB mechanical fit test, (PCB mockup with connector fits enclosure with cables etc...)
- Component placement for optimum routing and heat and Electromatnetic compatibility.  Then route.
- Review by fabricator of PCB against design rules.
- Inventory and order parts including PCB and stencile.
- Assemble first unit(s) and engineering test.
- Engineering revise and relese for rest of Prototype Run. Update of engineering, sales, legal documentation with photographs measurements of real hardware.
- Changes and repeat all of above for Pilot Run (First selleable units with serial numbers etc).



