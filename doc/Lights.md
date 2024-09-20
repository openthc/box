## Lights



The lights in Box can be very flexible, users choice.
Whichever lamps are selected, we will be removing the AC/DC Driver on it and connecting them to our [VDC Rails](Power.md).

| Lights | Watts | Count | Watts |
|--------|------:|------:|------:|
| Group1 | 150   | 8     | 1200  |
| Group2 | 800   | 8     | 6400  |


### Group 1

These are some random lights we found on Amazon, it's a DC ready panel; so it's directly ready to go.


- [120W LED Grow Light PCB Boards with Samsung LM281B+ 3000K 5000K UV and IR Full Spectrum Panel Lighting PCB Kit](https://www.amazon.com/KQO-Boards-Samsung-Spectrum-Lighting/dp/B08JXBCRCP)

This one would need a Power Driver.

It provides lighting in a 90x60cm area (0.54m2).
The container has 14m2 (2.4*6.1) so we need roughly 28 of these lamps to cover the area.

The total Power draw would be 3360W (28*120W)

### Some Power Maths

This lamp draws 48VDC at 2700mA Max (~120 Watts).
Our container would have 24 of them.
Consuming 48V * 2.7A * 24 == 3110.4 Watts
For 8 hours "sun" we need 24883.2 Watt-Hours
For 12 hours "sun" we need 37324.8 Watt-Hours


https://www.omnicalculator.com/physics/dc-wire-size


## Power Driver / DC SUpply

(https://www.meanwell.com/Upload/PDF/HLG-120H/HLG-120H-SPEC.PDF) which takes the AC and turns it into nice, clean DC.

https://www.ledsupply.com/dc-input-constant-current-led-drivers


## [Mars Hydro](https://www.mars-hydro.com/)

### [150 Watts](https://www.mars-hydro.com/fc-1500-samsung-lm301h-evo-led-grow-light)

| Size (mm) | Light Area (mm) | Watts |
|------|------------|-------|
| 417 x 417 x 9h | 0.700x0.700 (0.213677 m<sup>2</sup>) | 150 |

Eight of these 150*8==1200W per hour per container.


###  [800 Watts](https://www.mars-hydro.com/smart-fc8000-samsung-lm301h-evo-commercial-led-grow-light)

| Size (mm) | Light Area (mm) | Watts |
|------|------------|-------|
| 1143w x 1143d x 9h | 1524x1524 (2.32258 m<sup>2</sup>) | 800 |

Eight of these 800*8==6400W per hour per container.

## Amazon Stuff

- [VIPARSPECTRA KS5000 LED Grow Light 500W with Samsung LM301H](https://www.amazon.com/VIPARSPECTRA-KS5000-Coverage-Spectrum-Commercial/dp/B09MTSY9G2/ref=mp_s_a_1_1_sspa?crid=3H35GKE8U66C7&dib=eyJ2IjoiMSJ9.BG7T460oeeInkcSqNlik2mc728tvfLqujw3Sxay9QIvqy4rIf-VIqw-JTosy4aSG_d_tM1mh8aNyHRYv0FFhYu1FRLmaPVIXjZgNl01pws6tYoKTWxh4ic2_hcrOdjbVbyZ0hK-1lbjgy8sA-_VMn8bWhx3CTlizfiLMnUofkm8bZohbknUHTD2WNZeqwG4hTKFp6yjNPBsmn740aozeUw.pmEEZYbMjRh8dDp_wrtSvupaVSJtiwIHAIOUbgNeALM&dib_tag=se&keywords=viparspectra&qid=1714683948&sprefix=vipar%2Caps%2C600&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9waG9uZV9zZWFyY2hfYXRm&th=1)
- https://cdn.shopify.com/s/files/1/1538/8585/files/Scorpion_Diablo_X_L112210901.pdf?v=1669128794
- [Just a DC Lamp Panel](https://www.amazon.com/KQO-Boards-Samsung-Spectrum-Lighting/dp/B08JXBCRCP?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A2FTPOMGN8IJ2E)
- https://atreumlighting.com/products/atreum-144-2-60w-led-fixture-vegetative-full-spectrum-grow-light-panel-samsung-lm301b
- https://www.aliexpress.us/item/3256803461815252.html?gatewayAdapt=glo2usa4itemAdapt
