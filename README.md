# Cuprite

160mm^3 High speed corexy

<img width="1122" height="842" alt="Cuprite_V2_2026-Jun-14_01-05-33AM-000_CustomizedView40187612621_png" src="https://github.com/user-attachments/assets/fc7aa2cc-a4e0-41e4-9aa7-26b93f19dbe2" />


* [Design Components](#design-components)
* [Design Reasoning](#why-did-i-design-this)
* [BOM](<BOM.csv>)

## Files
- [CAD (F3Z)](CAD/Cuprite.f3z)
- [CAD (STEP)](CAD/Cuprite.step)
- [PCB Gerbers](PCB/Cuprite_ADXL_gerbers.zip)
- [BOM](<BOM.csv>)

<img width="420" height="595" alt="A5 - 1" src="https://github.com/user-attachments/assets/837b9a83-0750-4f6c-baa8-a9f89dc37416" />




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
  * Full cnc components for rigidity and reduced mass
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
- Aesthetic panels
  * Parametric Kumiko panels that allow for customizability
  * Covers up 1/2" of PIR insulation
  * Integrates an extrusion based door

## Why did I design this?
The original concept for Cuprite was an extremely high speed corexy that focused on rigidity and made as little comrpromises as possible. Other than the build volume and size. Surprisingly, it's larger than a P1S while having a 100mm smaller bed.

The original one was a rushed design that happened in 2 weeks last summer, but it taught me a lot about printer design and I managed to get some sponsors. Now, I'm incorporating everything I've learned about good 3d printer design. 

Also, I thought the original was a bit boring with plain aluminum panels.

## What could you use from this project?
My build is pretty unique, so I dont expect people to build a similar printer, however you could utilize multiple aspects from it:
- The toolhead is afaik the most compact com optimized toolhead with a 50mm long meltzone. It about 10mm shorter than other similar toolheads.
- Kumiko panels is parametric, so you can use it on a lot of printers (not that reliable, so you might need to ask me for help with specific configurations)
- G2Z drives and Z joints. Normally G2Z drives are used on v2s or microns, but not that often on trident-like printers
- You could use my gantry since it supports 12mm belts (Monolith cnc gantry is a great option otherwise)

## Wiring?
The LDO leviathan + extension board has enough ports for all of the components, so its simply pluging into the correct ports. The only other wiring is ssrs for heatbed and chamber heater.

## Inspiration/References:
- Monolith Gantry: https://github.com/Monolith3D/Monolith_Gantry
- Paper View's Kumiko Panels: https://makerworld.com/en/models/1614814-large-kumiko-frame-generator#profileId-1733448
- DK's toolhead: https://github.com/Kizime123/DKs-Monolith-Toolhead
- DDerg's cnc joints: https://github.com/dderg (no project link)
- Galileo2: https://github.com/JaredC01/Galileo2
- Scarecrow for fan information and CAD: https://github.com/Thescarecow/130K-RPM-28mm-ducted-fan-Cad-COM
- Hex-Zero for Z tensioner: https://github.com/Alexander-T-Moss/Hex-Zero
- Chamber Heater Mount: https://github.com/GiulianoM/PTC_Heater_Mount
- ADXL: https://github.com/xbst/KUSBA-PRO
- LED Strip Holder: https://www.printables.com/model/84735-led-strip-holder-for-voron-24
- Also big thanks to anyone who provided feedback on any of my designs
