# HP303B

This component is used to add support for the wemos [Barometric Pressure Shield (HP303B)](https://www.wemos.cc/en/latest/d1_mini_shield/barometric_pressure.html).


![front](https://www.wemos.cc/en/latest/_images/hp303b_v1.0.0_1_16x16.jpg)
![back](https://www.wemos.cc/en/latest/_images/hp303b_v1.0.0_2_16x16.jpg)

Add the following lines to your esphome yaml file:

```
  libraries:
    - Wire
    - SPI
    - "https://github.com/wemos/LOLIN_HP303B_Library.git"

external_components:
  - source: github://thijsk/esphome-components
    components: [ hp303b ]
```

This component is maintained by [shish](https://github.com/shish/esphome-projects/tree/master/components/hp303b), this is a mirror.