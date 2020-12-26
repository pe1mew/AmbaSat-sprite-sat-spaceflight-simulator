# AmbaSat sprite-sat spaceflight-simulator
A space flight simulator for the AmbaSat sprite satellite.

AmbaSat is an intiative that will allow participants (backers) to fly their own sprite satellite.
See: https://ambasat.com/.

The sprite satellite is a small PCB that contains a LoRa radio, a ATMEGA328 microprocessor, gyroscope, accelerometer, magnetometer (LSM9DS1) as well as a range of other sensor options. While the flying stallites will use solar cells to power the satellite, for development purpose batteries (2xAA) will be used. 
Telemetry is send back to earth using LoRaWAN and The Things network (https://www.thethingsnetwork.org/)
Software development is done by the owner of a sprite-sat. 

Flight trough space by the sprite-sat will have a tumbling character that will affect powergeneration by the solarcells as well as sensor readings. To help with the simulation of these effects on earth while studying, a cardian suspension was created to simulate the tumbling character of space flight.

![AmbaSat spaceflight simulator](media/2020-12-24_15.19.06_small.jpg
 "AmbaSat sprite-sat spaceflight-simulator")

The cardian suspension can be 3D printed using the STL files in this repository.

# Disclaimer
The AmbaSat sprite-sat spaceflight-simulator is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
 
# License
The AmbaSat sprite-sat spaceflight-simulator is free: 
you can redistribute it and/or modify it under the terms of a Creative Commons Attribution-NonCommercial 4.0 International License (http://creativecommons.org/licenses/by-nc/4.0/) by PE1MEW (http://pe1mew.nl) E-mail: pe1mew@pe1mew.nl

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
