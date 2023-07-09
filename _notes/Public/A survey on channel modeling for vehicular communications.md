---
date: 2023-06-13
tags: 1st-significant lit-review/read 
aliases: 
---
# A survey on channel modeling for vehicular communications
Survey on [channel models](channel%20model.md), classifying by application, then input requirements, scalability, propagation scale, and environment. Then simulating the channel using Remcom Wireless Insite software.

Main focus on vehicle to infrastructure (V2I)

Antenna height is short and usually operates at 5.9GHz for Dedicated short-range communications (DSRC)
### DSRC
1 ctrl channel
6 service channels
with 10MHz BW and 5 MHz guard band.

### General V2X specs
Distance usually 10-500m
Main idea of [channel model](channel%20model.md) is usability of the model and amount of geographic information available
#objsidenote may need to look at geographic information available for BWSC route
## Chapter 2
Other vehicles might need to be a relay agent between two vehicles.
Wifi standard 802.11p used for V2X - 5.9GHz.
This can be used in an adverse environment.
[Road Side units (RSU)](Road%20Side%20units%20(RSU).md)
## Chapter 3
Path loss exponent is 1.6-2.9 on highways (references [11] and [12]).

Mean delay spread is 140-400ns

Used part of San Diego state uni to use as the environment.
##### 3.1.1.1 Link Types
Atennas on top for V2V.

##### 3.1.1.2 Vehicle Types
Trucks have attenuation which can be greater than 20dB - larger than personal vehicles
#question What is the attenuation of a personal vehicle?
#answer check: Geometry-based vehicle to vehicle channel
modeling for large-scale simulation and Impact
of a truck as an obstacle on vehicle-to-vehicle communications in rural and highway
scenarios
##### 3.1.1.3 Objects
Mobile objects are priority on highway.
Non-line of sight channels show larger root mean square delay spreads than line of sight (LOS).
### 3.2 Classification of Channel models
#### 3.2.1 Propagation Mechanisms
1. Varying path loss
2. high doppler shift
3. Frequency selective fading (caused by static/mobile objects)
Use [Piecemeal modeling](Piecemeal%20modeling.md) 
#### 3.2.2 Large scale propagation
[Log-distance path loss model](Log-distance%20path%20loss%20model.md)
Other options exist, including a [two-way ground reflection model](two-way%20ground%20reflection%20model.md)

#### 3.2.3 Small-scale fading

[^1]

# References
[^1]: [[../../03 - University/Thesis/literature review/1st - significant/A-SURVEY-ON-CHANNEL-MODELING-FOR-VEHICULAR-COMMUNICATIONS.pdf#page=22|A-SURVEY-ON-CHANNEL-MODELING-FOR-VEHICULAR-COMMUNICATIONS]]

