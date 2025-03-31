# Box - Automated Grow

Box aims to create and document designs and methods for building solar powered automated grow solutions.
As designed here **Box** provides roughly 12 square meters of grow space.

```
erDiagram
    AC ||--|| INVERTER-CHARGER : "source-power"
    INVERTER-CHARGER ||--|{ BATTERY : "charges"
    INVERTER-CHARGER ||--o{ LOAD : "drives"
    SOLAR1 }|..|| MPTT1 : "source-power"
    SOLAR2 }|--|| MPTT2 : "source-power"
    MPTT1 ||--|| SHUNT : "conn"
    MPTT2 ||--|| SHUNT : "conn"
    SHUNT ||--|{ BATTERY : "charges"
    BATTERY }|--o{ LOAD : "powers"
```

## Current Objectives

- Designs for TEU Hydro/Aero-ponic Garden
- Solar Powered (Battery)
- Automate process w/raspberry-pi (or similar) hardware.


## Unit Conversion

We put all units in the standard measures (SI).

- You can [Convert cfm to cubic metre/minute](https://www.convertunits.com/from/cfm/to/cubic+metre/minute)
- Or Google to convert to Imperial.


## DC/DC Conversion

- [MEAN WELL DC/DC LED Drivers](https://www.meanwell-web.com/en-gb/dcdc-led-drivers)


## Lights

We've got a whole document on [./doc/Lights.md](Lights).
