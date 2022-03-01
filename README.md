**DEV PREVIEW**

![image](https://user-images.githubusercontent.com/1661078/156165793-8d778cb6-b70a-479b-8289-c36ade7ff41e.png)

quadkit is an entry point for students, researchers, engineers, artists, and designers to start tracking and flying drones using a Qualisys motion capture system.

## Box Contents

- 2x Bitcraze Crazyflie Drones
- 1x Bitcraze Antenna
- 2x Bitcraze Spare Parts Bundle
- 2x Qualisys x Bitcraze Active Marker Deck

## QTM Settings

We recommend the following settings:

- Custom Euler angle definitions:
  - First Rotation Axis: `Z`, Positive Rotation: `Clockwise`, Name: `Yaw`, Angle Range: `-180 to 180 deg.`
  - Second Rotation Axis: `Y`, Positive Rotation: `Counterclockwise`, Name: `Pitch`
  - Third Rotation Axis: `X`, Positive Rotation: `Clockwise`, Name: `Roll`, Angle Range: `-180 to 180 deg.`
- Capture Rate: 100 Hz

## Software Environment

    pip install qtm cflib

## Bitcraze Crazyflie

For takeoff, the drone should be placed on the floor with its front pointing in the positive x-direction of the QTM coordinate system.

## Bitcraze Crazyflie Swarm

## DJI Tello
