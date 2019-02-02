# This is a Micropython library for the MPL3115A2 Altimeter

## HOW TO USE THIS LIBRARY
---

import library
    
    from mpl3115a2 import MPL3115A2

Create the MPL object in altitude mode (mode 0)

    mpl = MPL3115A2(sda=Pin(21), scl=Pin(22), mode=0)

to read the altitude and temperature

    altitude = mpl.altitude()
    temperature = mpl.temperature()
    
Create the MPL object in pressure mode (mode 1)

    mpl = MPL3115A2(sda=Pin(21), scl=Pin(22), mode=1)

to read the pressure and temperature

    pressure = mpl.pressure()
    temperature = mpl.temperature()

