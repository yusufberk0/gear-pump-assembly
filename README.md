# External Gear Pump: Flange-Mounted Assembly

SolidWorks model of a flange-mounted external gear pump: mounting flange, gear housing, rear cover, two meshing spur gears on parallel shafts, bushings, seal rings and threaded port fittings, with an exploded view and animations.

<p align="center">

<img width="627" height="671" alt="hydraulic-pump-isometric" src="https://github.com/user-attachments/assets/3dd524aa-6f7b-4329-aa54-bf29d5a69a26" />

</p>

> Built as a skill-building project to practise assembly design, standard components and exploded views in SolidWorks. The focus is geometry and assembly: no hydraulic performance or strength calculations were performed, so the dimensions are not intended for manufacturing.

## Highlights

- **Flange-mounted external gear pump** with a keyed drive shaft and two meshing spur gears
- **ISO spur gears** defined from standard parameters (module 2.75, 11 teeth, 20° pressure angle, 23 mm face width)
- **Rear cover clamped with four socket-head cap screws**
- **Two threaded port fittings** for inlet and outlet
- **Exploded view and animations** that show how the parts stack together

## Views

<p align="center">

  
 <img width="627" height="672" alt="hydraulic-pump-isometric-back" src="https://github.com/user-attachments/assets/e71384ea-3306-49c8-90ff-0ce7c5e44e71" />



<img width="627" height="610" alt="hydraulic-pump-transparent" src="https://github.com/user-attachments/assets/b5eebaef-6758-499d-8364-57955933605b" />


  
</p>

## Exploded view

<p align="center">


<img width="627" height="468" alt="hydraulic-pump-exploded" src="https://github.com/user-attachments/assets/bb41aea9-971d-4b44-8767-81f185098f29" />



  
</p>

## Animations




https://github.com/user-attachments/assets/3c4f2b18-9e8b-49a2-8697-fc893dbf22be






https://github.com/user-attachments/assets/3abd02ae-18c2-4cbf-ac81-f87ba98b3335




## Components

| Part | Description |
|---|---|
| Mounting flange | Square flange with four mounting holes and the shaft bore |
| Gear housing | Central body with the gear chamber and port openings |
| Rear cover | Closes the housing, clamped with four socket-head cap screws |
| Drive shaft and gear | Keyed shaft carrying the driving spur gear |
| Driven shaft and gear | Second shaft and spur gear meshing with the drive gear |
| Bushings | Bushing blocks supporting both shafts |
| Seal rings | Sealing between flange, housing and cover |
| Port fittings | Two threaded hex fittings for inlet and outlet |
| Fasteners | Socket-head cap screws |

## Gear data

| Parameter | Value |
|---|---|
| Standard | ISO spur gear (SolidWorks Toolbox) |
| Module | 2.75 mm |
| Number of teeth | 11 |
| Pressure angle | 20° |
| Face width | 23 mm |
| Hub style | Type A |
| Nominal shaft diameter | Ø18 mm |
| Pitch diameter (module × teeth) | 30.25 mm |

## Design approach

- The gear pair is defined from standard ISO parameters, so module, tooth count and face width can be changed to resize the pump.
- Standard components such as the spur gears are used where appropriate; the housing, flange, cover and the rest of the assembly were designed and assembled by me.
- The exploded view documents the assembly order and makes it easy to see how each part fits.

## Repository structure

```
gear-pump-assembly/
├── cad/        SolidWorks parts and assembly (.SLDPRT / .SLDASM)
├── step/       Neutral CAD format (.step), opens in any CAD software
├── images/     Renders, transparent and exploded views
└── media/      Animations
```

## How to open the files

- **SolidWorks:** open the assembly file in `cad/`. All parts are in the same folder, so keep them together.
- **No SolidWorks?** Open the `.step` files in a free viewer such as eDrawings, FreeCAD or Autodesk Fusion.
- **Quick look:** the images in `images/` and the animations in `media/` need no software.

## Possible next steps

- Estimate theoretical displacement and flow from the gear geometry
- Add technical drawings with tolerances
- Check the housing under working pressure with a simple FEA

## Tools

SolidWorks (part, assembly, exploded view, animation) and SolidWorks Toolbox.

## Contact

**Yusuf Berk Say**, Mechanical Engineer, Istanbul

- LinkedIn: [Yusuf Berk Say](https://www.linkedin.com/in/yusuf-berk-say-9bb68a234/)
- Email: yusufberk.say0@gmail.com
