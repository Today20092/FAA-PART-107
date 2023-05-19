---
weight: 4
---

# Chapter 4 - Loading & Performance

## Introduction

- **REMOTE PIC** is in charge of all **safety** for the sUAS
  - anything placed **on** or **carried** by the drone must be attached securely
- use the **manufacturers** recommendation for testing & evaluation performance
- Must check weather conditions prior & during the flight
- Main control system
  - alerion
  - elevator
  - rudder
- Secondary control system
  - spoiler
  - leading edge
  - trim
  - wing flaps

### Questions

- Remote pic must ensure objects carried on the sUAS are secure
- The rudder operates the yaw on a sUAS airplane
  - ![](https://i.imgur.com/nrHWs9z.gif)

## Determining Speed & Altitude

- cannot be flown faster than 100mph or 87knots
- use gps to tell speed
- use timing between two fixed positions to tell speed
- use a radar gun to measure speed
- use an anemometer with inertial information from onboard sensor
- KEY TERMS:
  - **Dead Reckoning** : navigation by means of computations based on _time, airspeed, distance, and direction_
  - **Pilotage** : Navigation by _landmarks_ or _checkpoints_
  - **Wind Triangle** : navigation by _triangulation_
    - ![](https://i.imgur.com/l5UWNaa.png)
- Determine **altitude** from the _ground_ :
  - calibrated altitude reporting device
  - gps device
  - have sUAS 400 feet away and tell the visual size
  - if cs has measure of 400 feet fly the sUAS directly overhead to see its visual perspective
  - use known local terrain
  - Sectional chart tells you altitude and terrain and structures

### Questions

- you are operating sUAS that does **not** have gps or installed ground speed limiter how can you determine the **speed** you are operating? :: Dead Reckoning
<!--SR:!2023-05-16,4,270-->
- Remote pilot can determine the altitude of terrain & structures in the sectional chart
- Your sUAS does **not** have Gps or altimeter, how do you determine **altitude** :: Gain a visual perspective of what 400 feet looks like on the ground before flight
<!--SR:!2023-05-16,4,270-->

## Loading

- make sure the sUAS is corrected loaded & balanced.
- take into consideration wind, altitude, heat, humidity in terms of aircraft performance and weight capacity.
  - need to reduce weight to make sure there is good performance
- change of weight during flight will also effect aircraft performance
  - eg : dropping off package, releasing agriculture spray, etc
- Make sure weight is evenly balanced across the sUAS before & after loads

## Computing Weight & Balance

- Key terms
  - **Empty Weight** : Weight including airfame, powersource, fixed equipment, and unusable fuel
  - **Useful Load** : Includes power source, & payload/ mission equipment
  - **Arm** : Horizontal distance from datum line to a point of the sUAS
    - Forward : (-)
    - Backward : (+)
  - **Moment** : Weight of an object \* is arm expressed in pound-inches (lbs-in)\
    - Weight \* Arm = Moment
- Excess weight consequences
  - reduce rate of climb
  - lower max altitude
  - shorter endurance
  - reduced maneuverability

### Questions

- when **loading** cameras & other equipment mount the items in a manner that does not adversely affect the center of gravity
- To ensure sUAS center of gravity are not exceeded follow **loading** instructions in Pilot's Operating Handbook or sUAS Flight Manual
- Shorter endurance is a consequence of overweight sUAS
- **Remote PIC** is **responsible** for using the most recent weight and balance data for sUAS
- Operations outside weight & balance **limitation** may result in loss of control
- sUAS with **rearward** _center of gravity_ is less stable at all speeds
<!--SR:!2023-05-16,4,270!2023-05-15,3,250!2023-05-13,1,230!2023-05-15,3,250!2023-05-15,3,250!2023-05-15,3,250-->

## Load Factor

- 1g is the pull of gravity
- Load factor : load imposed on wings or rotor in flight
- Aircraft stall when critical angle of attack is exceeded
  - occurs when performing sharp maneuver or pitching up/down too steeply

### Questions

- when operating sUAS the remote pic should consider the **load factor** in wings/rotors may increase anytime the aircraft is subjected to **maneuvers** other than straight and level flight
- Amount of excess load on the wing of an airplane depends on the speed of the airplanes
- turns increase the load factor on sUAS
<!--SR:!2023-05-16,4,270!2023-05-13,1,230!2023-05-15,3,250-->

## Stalls

- **chord line**: straights line from leading edge to trailing edge
- **airfoil**: structure that produces a useful reaction to air
- **relative wind**:wind that is experiences by the airfoil
- **angle of attack** : angle between chord line and relative path of airfoil
- **critical angle of attack**:angle at which stall occurs

### Questions

- term critical angle of attack is defined as the angle between wing chord line and relative wind
- angle of attack at which an airfoil will stall is the critical angle of attack
- stall occurs when smooth airflow over the wing is disrupted and lift degenerates rapid when wing exceed its critical angle of attack
- increase in load factor will cause a sUAS to stall at higher speed
- in a 45 degree banking turn a sUAS will stall at a higher seed
<!--SR:!2023-05-15,3,250-->

## Performance

- follow all manufacturer recommendations
- Remote PIC should be familiar with
  - operating environment
  - available information regarding safe and recommended operation of sUAS
  - conditions that may impact the performance of sUAS
- PIC is responsible every flight can be safe

### Questions

- uphill terrain slope increases launch distance
