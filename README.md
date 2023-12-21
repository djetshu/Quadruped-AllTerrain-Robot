# Quadruped-AllTerrain-Robot
<p align="center" width="100%">
 <img width="40%" src=Images/q1.png>
 <img width="40%" src=Images/q4.png>
</p>

## Introduction

This repository contains information about the design and development of a quadruped robot. It includes details about the advantages of legged robots over wheeled robots, commercial and popular products in the field, mechanical design, and more.

## Advantages of Robots with Legs / Legs over Wheeled Robots

- Greater ability to overcome obstacles - agility
- Increased pulling force

## Commercial and Popular Products

| Anymal C - ETHZ / Anybotics | Spot - Boston Dynamics | Cheetah - MIT |
| :--------------------------: | :---------------------: | :------------: |
| <p align="center" width="100%"><img width="60%" src=Images/anybotic1.png></p> | <p align="center" width="100%"><img width="60%" src=Images/spot.png></p> | <p align="center" width="100%"><img width="90%" src=Images/cheetah.png></p> |
| <p align="center" colspan="3">Leg mechanism</p> | <p align="center" colspan="3">Leg mechanism</p> | <p align="center" colspan="3">Leg mechanism</p> |
| Motors in joints | 4 bars| Synchronous belts | 
| <p align="center" width="100%"><img width="80%" src=Images/anymal_leg.jpeg></p> | <p align="center" width="100%"><img width="80%" src=Images/spot_leg.png></p> | <p align="center" width="100%"><img width="90%" src=Images/cheetah_leg.png></p> |

# Mechanical design of Quadruped AllTerrain Robot

<p align="center" width="100%">
 <img width="60%" src=Images/q3.png>
</p>

- Length: 63 cm
- Width: 49 cm
- Standard height: 43 cm
- Motors: [CuberMars AK10-9](https://www.cubemars.com/goods-1141-AK10-9+V20.html)
- Foot sensor: [Rokubi FT Sensor](https://www.botasys.com/force-torque-sensors/rokubi)
- Materials: Aluminum
- Weight: 18 kg (Mechanics only - estimated final weight: 30 kg)
- Maximum load capacity: 10 kg

### Key Features of the Design

- IP 67 Sealed Design
    
    Each motor AK10-9 is fully sealed with couplings and oring components.
    <p align="center" width="100%">
     <img width="30%" src=Images/cubemarsak109.png>
     <img width="40%" src=Images/cubemarsak109_sealed.png>
    </p>
    
- Scalable (Smaller or Larger Robot)
    
    By replacing the plates that connect the motors, the size of the robot can be adjusted within a certain range.
    <p align="center" width="100%">
     <img width="60%" src=Images/q5.png>
    </p>
    
- Modular
    
    Components such as a force sensor or a wheel motor can be easily attached without affecting other mechanical components or completely disassembling the robot.
    <p align="center" width="100%">
     <img width="40%" src=Images/q1.png>
     <img width="40%" src=Images/q4.png>
    </p>

- Easy Prototyping

    Given that simple shapes and geometries of every part of the design, it easy to 3D print and laser cut to prototype.

  <p align="center" width="100%">
     <img width="60%" src=Images/q2.png>
    </p>

## Next Steps
- Preliminary budget (Actuators, sensors, materials, and machining)
- Prototyping of a leg with 3D printing and laser cutting
- Complete design of wheel attachment in the last joint
- Simulations (torque verification, motion checks)

## Contact Information

For inquiries, collaboration opportunities, or questions about the Quadruped AllTerrain Robot project, feel free to contact us:

- **Email:** queque.daffer@pucp.edu.pe
