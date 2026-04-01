# Cuprite

160mm^3 High speed corexy

<img width="1600" height="1200" alt="Toolhead_Focus_Cuprite" src="https://github.com/user-attachments/assets/4da86686-0a3b-4680-99f1-c2d6e73032b8" />



* [Design Components](#design-components)
* [Design Reasoning](#why-i-designed-this)
* [Wiring Diagram](#wiring-diagram)
* [Firmware](#firmware)
* [BOM](#bom)

## Files
- [CAD (F3Z)](CAD/Cuprite.f3z)
- [CAD (STEP)](CAD/Cuprite.step)
- [PCB Gerbers](PCB/Cuprite_ADXL_gerbers.zip)
- Bom soon

<img width="1633" height="1057" alt="Cuprite v28" src="https://github.com/user-attachments/assets/f74e0692-8187-4863-8bf5-a33d90ebe6fd" />


### Sponsors
* [Hack Club (Blueprint)](https://highway.hackclub.com/) 
* [Sunlu](https://www.sunlu.com/)
* [OSHWLAB(JLCPCB)](https://oshwlab.com/activities/stars)
* [LDO](https://ldomotion.com/)
* [BST Automation](https://www.bstautomation.com/)
* [Filastruder](https://www.filastruder.com/)



## Design Components
- Fast and Rigid Corexy Gantry
  * Monolith Inspired gantry
  * 12mm AWD using 2504 s55 nema 17s, with 48V
  * Full cnc components for rigidty and reduced mass
- Solid Frame
  * 4040 verticals and 2040/4040 horizontals
  * 5mm structural aluminum panels
- Triple Z Axis
  * Triple Nema 17 G2Z
  * 9mm Belts
  * Maxwell motion coupling for accurate bed leveling (Inspired by ANNEX K3 Z)
- Rigid Toolhead 
  * CNC and SLM toolhead
  * Custom hotend for a cheap long meltzone (~55mm)
  * Center of mass optimized
  * Duct design aided by CFD
- Aesthic panels
  * Parametric Kumiko panels that allow for customizablity
  * Covers up 1/2" of PIR insulation
  * Integrates an extrusion based door

## Why did I design this?
The original concept for Cuprite was an extremely high speed corexy that focused on rigidity and made as little comprimises as possible. Other than the build volume and size. Its suprirsingly larger than a P1s for having 100mm less bed size.

The original one was a rushed design that happened in 2 weeks last summer, but it taught me a lot about printer design and I managed to get some sponsors. Now, I'm incorporating everything I've learned about good 3d printer design. 

Also, I thought the original was a bit boring with plane aluminum panels.

## What could you use from this project?
My build is pretty unique, so I dont expect people to build a similar printer, however you could utilize multiple aspects from it:
- The toolhead is afaik the most compact com optimized toolhead with a 50mm long meltzone. It about 10mm shorter than other similar toolheads.
- Kumiko panels is parametric, so you can use it on a lot of printers (not that reliable, so you might need to ask me for help with specific configurations)
- G2Z drives and Z joints. Normally G2Z drives are used on v2s or microns, but not that often on trident-like printers
- You could use my gantry, but the monolith CNC gantry is coming out soon and will be a better price to performance

## Wiring?
The LDO leviathan + extension board has enough ports for all of the components, so its simply pluging into the correct ports. The only other wiring is ssrs for heatbed and chamber heater.

## BOM:

