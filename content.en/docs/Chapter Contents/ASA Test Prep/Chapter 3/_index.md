---
weight: 3
---

# Chapter 3 - Weather

## Introduction

- atmospheric pressure
- wind and currents
- uneven surface heating
- visibility and cloud clearance
- precipitation
- Convective currents when warm air rising
- Urban areas give off more heat & are more likely to have updrafts

### Questions

- Current weather conditions are an important consideration when evaluating unmanned aircraft performance.
- Every physical process is accompanied by or result of heat exchange
- Unequal heating in earth's surface causes variations in altimeter settings between weather reporting points
- Development of thermals depends on solar heating
- ![](https://i.imgur.com/XDGhP62.png)
  - Which area would have the most thermal current? 5, 7 or 2?::2

<!--SR:!2023-05-26,14,270-->

- Clouds, fog, or dew will always form when water vapor condenses
<!--SR:!2023-05-13,1,186-->

## Wind

- winds can affect flight time and stability
- winds can create updraft near buildings and downdraft from over the buildings
- flying low may create rapidly changing wind

## Air Masses & Fronts

- air takes on properties it rests on or moves over.
  - :air mass modification
- cold front is leading edge of cold air
  - poor weather ahead & passes quickly & wind shift
- warm front leading edge of warm air
  - more heavy effect on weather & move half as fast as cold
- ridge: high pressure
- trough: low pressure

## Atmospheric Stability

- stable atmosphere is resistant to vertical motion
- stable layers of air is associated with temperature inversion

### Questions

- Stable air mass has showery precipitation characteristic
- Moist unstable airmass has haze and smoke
- stable air has poor visibility and steady precipitation
- actual lapse rate determines stability of atmosphere
- Warming from below decreases stability
- unstable air mass approaching, thunderstorms and turbulent conditions are concern
- Low level temperature inversion & high relative humidity = :: smooth air, poor visibility, fog haze or low clouds
<!--SR:!2023-05-13,1,186-->

## Visibility & Clouds

- 3SM visibility from control station
- sUAS is kept 500feet below clouds & 2000 feet horizontally

## Thunderstorms

- three requimrents
  - sufficient water vapr
  - sufficient lapse rate
  - initial upward boost
- virga is water that evaporates before it hits the ground and should be avoided
- avoid 20sm from storms because of turbulent conditions
- the mature stage is the greatest intensity
- thunderstorms draw in air from the middle creating a vortex
- microburst is a intense small scale downdraft

### Questions

- continuous updraft is associated with cumulus stage of thunderstorms
- Precipitation falling is a sign of the beginning of the mature stage of a thunderstorm
- High humidity, a lifting force, and unstable conditions are necessary for the formation of clouds
- Dissipating stage is mostly downdrafts
- Squall line thunderstorms produce the most intense hazard to aircraft
- Nonfrontal narrow band of active thunderstorms ahead of a cold front is called the squall line
- Wind shear is a hazard associated with all thunderstorms
- Lightning and thunder is associated with thunderstorms
- static electricity is a hazard when flying near thunderstorms
- Duration of microburst is less than 15 minutes from when it strikes the ground
- Squall is most likely to form at any altitude
<!--SR:!2023-05-22,10,250!2023-05-19,7,246!2023-05-16,4,206!2023-05-13,1,226!2023-05-21,9,226!2023-05-24,12,246!2023-05-13,1,186!2023-05-16,4,206!2023-05-26,14,266!2023-05-26,14,266!2023-05-23,11,246-->

## Icing

- icing occurs when water is supercooled
- any indication of icing the pilot should recover the sUAS immediately
- visible moisture is necessary for structural icing to form

### Questions

- presence of ice pellets at surface is evidence that there is freezing rain at higher altitude.
- visible moisture is required for structural icing to form
- frost will occur with dewpoint of _surface_ below freezing & dewpoint is above freezing
<!--SR:!2023-05-22,10,250!2023-05-28,16,266!2023-05-17,5,226-->

## Fog

- fog comes from water added to air near surface
- fog requires low temperature/dew point spread
- fog is more prevalent around industrial areas
- many types of fog:
  - radiation
  - advection
  - upslope
  - precipitation induced
  - steam
- Pilot must recover when <3SM visibility occurs

### Questions

## Density Altitude

- sUAS performance will decrease with high temperature, marginally with high humidity, low atmospheric pressure, and altitude increase

### Questions

## Weather Briefing

- remote pic are encouraged to use [1800wxbrief.com](https://1800wxbrief.com) for weather reporting and NOTAMS
- [aviationweather.gov](https://aviationweather.gov)

## Weather Reports, Forecasts, & Charts

- (ASOS) Automated Surface Observing System - primary weather observing
  - processes weather, minute by minute, computer transmitted
- (AWOS) - marked by (**AUTO**)
- ![Metar Report Example](metar.png)
- METAR is standard international format - scheduled
  - _METAR KGG 161753Z AUTO 14021G26KT 3/4SM +TSRA BR BKN008 OVC012CB 18/17 A2970 RMK PRESFR_
    - TYPE : **METAR** OR **SPECI**
    - STATION Identifier : **KGG**
    - DATE & TIME (SIX DIGITS) : **161753Z**
      - 16 = Date
      - 1753 = Time
      - Z = Zulu Time
    - Modifier : **AUTO** or **COR** (Corrected)
    - Wind : **14021KT** (five digits or 6 if greater than 99 knots)
      - 140 = Direction true win is blowing in tens of degree
      - or **VBR** = variable
      - **G** for gusting
      - **V** to separate extreme wind direction
    - Visibility : **3/4SM**
      - **R/** = runway visibility
    - Weather : qualifiers & phenomena : **+TSRA**
      - - = HEAY
      - TS = THUNDERSTORMS
      - RA = RAIN
    - Sky Condition : amount, height, & type in that order : height is in hundreds of feet
      - **BKN008** : Broken 800 feet
      - **OVC012CB** : Overcast 1,200 feet
      - VV003 : Vertically visible 300 feet
      - ![](https://i.imgur.com/IlNjRQ7.jpg)
    - Temperature & Dew Point in order : **18/17**
      - In Celsius, M if minus (M18/M17)
    - Altimeter settings : **A2970**
      - inches of mercury (Hg) 4 digit number always A infront
      - PRES**RR** - RISING RAPIDLY
      - PRES**FR** - FALLING RAPIDLY
    - Zulu time
    - Remarks : **RMK** comments
{{< hint info >}}
You can copy and paste a Metar report into ChatGPT and tell it to describe each section of the Metar Report.
{{< /hint >}}
  

- TAF - another weather report usually given 4 times a day (0000Z 0600Z 1200Z 1800Z)
  - _TAF KPIR 111130Z 1112/1212 15012KT P6SM BKN090 TEMPO 1112/1114 5SM BR FM1500 16015G25KT P6SM SCT040 BKN250 FM120000 14012KT P6SM BKN080 OVC150 PROB30 1200/1204 3SM TSRA BKN030CB FM120400 1408KT P6SM SCT040 OVC080 TEMPO 1204/1208 3SM TSRA OVC030CB_
  - Type of report : **TAF** or **TAF AMD**
  - ICAO Station identifier : **KPIR**
  - Date & time of origin : **111130Z**
  - Valid period dates & times : **1112/1212** first two being day & 2nd two are hour
    - 11th hour 12
    - 12th hour 12
  - Forecast wind : **15012KT**
    - 150 = wind in true north
    - 12KT = 12 knots
    - or 120KT = 120KT
  - Forecast visibility : **P6SM**
    - in statue miles (P6SM means over 6 miles)
  - Forecast significant weather : **BKN090**
    - same format as METAR
  - Forecast sky condition
  - Forecast Change Group : **TEMPO**
    - **TEMPO** = Temporary within 1 hour
    - **FM** = Rapid & significant change within hour
  - PROB30 = given percentage of thunderstorms and precipitation in the coming hours

### Questions

- what is true of ASOS/AWOS :: ASOS locations **perform weather observing functions** necessary to generate METAR reports
<!--SR:!2023-05-13,1,215-->
-
