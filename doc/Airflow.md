## Airflow

The Box is 38.54956 m3 (1412.59 ft2)
On the [GrowLink Blog](https://blog.growlink.com/airflow-basics-for-indoor-cannabis-grows) they recommend changing the air in the room every 1 to 3 minutes!.
Then [AC Infinity](https://acinfinity.com/pages/grower-setup/grow-tent-ventilation.html) shows that the cubic space is equal to the amount of air you need to change in a minute.

We need to cycle 40m3/60s air in the room to get one minute refresh of the air.
Or we could do 13m3/60s to refresh every three minutes.

Other recommend sizing above these needs by 25% which would be 50m3 (1765 CFM) for this container.

Estimate **250W** power requirement for the fan.

### Vent Fans

Here is a random [24VDC 16in fan](https://flex-a-lite.com/24-volt-16-inch-trimline-auxiliary-reversible-electric-fan.html).
It would connect directly to our 24V rail in the box.
Will have 15A fuse and draws 7A (24*7=168W).

Another fan was we saw had 11A draw, (24*11=246W).


### Internal Movement Fans (Oscillating)

On [SensiSeeds](https://sensiseeds.com/en/blog/grow-tent-ventilation-how-to-calculate-your-needs/) they tell us to use internal fans to keep the air inside moving.
We'll need some oscillating fans.


### PC Fan Thought Experiment

This [140mm PC Fan](https://www.aliexpress.com/item/3256807326225222.html) can move 1.699m3/60s (60CFM) and consume 2.88W.

This [140mm PC Fans](https://www.aliexpress.com/item/3256807023998653.html) can move 2.548m3/60s of air; 12VDC @ 0.16A (12*0.16=1.92W).  Would require 16 of these fans for 30.72W of power.
