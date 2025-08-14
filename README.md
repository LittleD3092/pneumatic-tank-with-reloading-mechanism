# Pneumatic Tank with Reloading Mechanism

A pneumatic projectile launcher designed with a custom automated reloading mechanism. This project is based on a course named mechanical practice.

## Overview

- Pneumatic projectile launching system using compressed air for firing
- Rotary magazine mechanism for automated reloading
- Monocular camera-based range estimation with YOLOv8 object detection to enable autonomous target acquisition and aiming

## Demo

<img src="doc/2023-05-19%20封面.jpg" alt="Cover" width="50%">

[Watch the video](https://youtu.be/MhBOqN-i4nw)

## Technical Highlights

- **Control System**:
  - Arduino for basic control logic
  - Raspberry Pi Compute Module for high-level control logic and capturing image
  - Steam deck for image recognition system and user interface
- **Launching**: Compressed CO2
- **Reload Mechanism**: Rotating magazine with a nozzle that push the next round into the chamber
- **Design Tools**: Solidworks 2019, 3D printing for custom parts

## Design & Documentation

```
├───cad # 3D cad
├───doc # Documents
├── pic # Pictures
└── src # Source code
```

## Gallery

<table>
  <tr>
    <td><img src="pic/chassis.jpg" alt="Chassis" width="250"/></td>
    <td><img src="pic/rotation-exploded-view.png" alt="Rotation Mechanism Exploded View" width="250"/></td>
  </tr>
  <tr>
    <td><img src="pic/reloading-animation.gif" alt="Reloading Mechanism Animation" width="250"/></td>
    <td><img src="pic/firing-exploded-view.png" alt="Firing Mechanism Exploded View" width="250"/></td>
  </tr>
  <tr>
    <td><img src="pic/cad.png" alt="CAD Overview" width="250"/></td>
    <td></td>
  </tr>
</table>

## Authors

| Competition Member                  | Responsibilities                                    | Allocation (%) |
|--------------------------------------|-----------------------------------------------------|----------------|
| **Wu Dian-Mou, Dept. of Mechanical Eng.**   | **PPT creation, all programming**                   | **36**             |
| Chen O Wen, Dept. of Mechanical Eng. | Mid-term presentation, reloading mechanism, firing mechanism | 25             |
| Hsieh O En, Dept. of Mechanical Eng.| Final presentation, steering, integration           | 25             |
| Wang O Yi, Dept. of Mechanical Eng.  | Base platform                                        | 10             |
| Chang O Yuan, Dept. of Mechanical Eng.| Reloading                                           | 4              |

> Some members' names not fully displayed due to privacy reasons.
