## INTRODUCTION
Our integrated circuits and reference designs for automotive exterior rearview mirror modules help you accelerate design through accurate light sensors and LED lighting solutions with high precision in controlling and driving electrochromic mirrors and high integration for human interface (HMI) control.
Modern rearview mirror modules require:
Accurate, stable control of large capacitive load for electrochromic auto dimming.  Precise sensing of ambient light to allow effective auto dimming.

## FEATURES
### BLIND SPOT DETECTION 										
Blind Spot Detection tracks traffic just behind you. The alert stays active until the car in the adjacent lane is in front of you, or at least directly alongside and you’d have to be blind not to see it. Blind Spot Detection uses ultrasonic or radar sensors on the side and rear of the car.
### DEFOGGERS	
Defoggers are used to defog the rear window, and to remove raindrops, dew and frost from the outside rear view mirrors. The operation time changes according to the ambient temperature and vehicle speed, It may be 10 minutes to 25 minutes.

## COMPONENTS
### DC MOTOR
Each rear-view mirror has two DC motors. One DC motor operates the up/down function while the other DC motor operates the left/right function. Both switches inside the power mirror switch are constantly connected to the vehicle's electrical ground circuit with the switch at rest.
### INFRARED SENSOR
An infrared sensor (IR sensor) is a radiation-sensitive optoelectronic component with a spectral sensitivity in the infrared wavelength range 780 nm … 50 µm. IR sensors are now widely used in motion detectors, which are used in building services to switch on lamps or in alarm system.
### RADAR
Radar is a electromagnetic sensor used for detecting, locating, tracking, and recognizing objects of various kinds at considerable distances. 


## REQUIREMENTS

### HIGH LEVEL REQUIREMENTS

|   | TITLE  | MODULES  |  DESCRIPTION |
|---|---|---|---|
| SYS_1 | Requirments | DC MOTOR  | The Side Rear View Mirror should Open when the Engine Started.|
| SYS_2 | Requirments | DIGITAL CAMERA | The Main Camera Present in the Mirror gives the precise view of the mirror in an LCD Display inside the car when the weather outside is not good.|
| SYS_3 | Requirments | DC MOTOR  | When the Engine Turns off, the Mirror Should Close Automatically.|

### LOW LEVEL REQUIREMENTS

|   | TITLE  | MODULE  | DESCRIPTION  |
|---|---|---|---|
| SYS_1  | Requirements  | H-MOD  | The Defogger System should connect with the Aircon System to generate the heat and make the mirror crystal clear for the driver.|
| SYS_2  | Requirements  | INFRARED SENSOR  | The Sensor in the side mirror which can detect the chasing vehicle near it and gives a signal to the driver to be cautious.|
| SYS_3  | Requirements  | RADAR  | To detect the Blind spots of the DRIVER, up to 6 cameras have been placed in the rear mirror to cover the entire blind spot.|

## UML DIAGRAM
### STRUCTURAL










![11](https://user-images.githubusercontent.com/54714219/150665688-daba7717-9e8e-4486-8ba6-fe4450bcc293.jpg)

## WIPER CONTROL

Number |Requirements|	Description	|Features |
|-----------|------------|:---------:|:---------:|
HLR1 |	Rain and Humidity sensor| checks the intensity of rain and humidity| Wiper Control|	
HLR2	|Semi-Automatic control| Operated automatically or manually	|	Wiper Control|
HLR3	|Speed control |High,Medium,Low|	Wiper Control|
HLR4 |Dry mode |front and back wiper system| Wiper Control|

## Low Level Requirements
Number| Requirements|	Description|	Features|	
|--------------------|:---------:|:--------:|:-----:|
LLR1	|Lenght of wipers| Depends on the model of the car |	Wiper Control | 
LLR2	| Direction of wipers  | Same and Opposite Directions(180 degrees) |	Wiper Control | 
## BLOCK DIAGRAM

![WhatsApp Image 2022-01-24 at 9 05 13 AM](https://user-images.githubusercontent.com/94425272/150718005-332b73a8-8548-44ef-8eaa-b549370522be.jpeg)


![WhatsApp Image 2022-01-24 at 9 04 31 AM](https://user-images.githubusercontent.com/94425272/150718036-74384a19-ac34-4595-96db-6420ccaf77b5.jpeg)

## FLOW CHART

![WhatsApp Image 2022-01-24 at 9 06 37 AM](https://user-images.githubusercontent.com/94425272/150718176-306094bf-0418-42d8-9156-d5a7e6ee0d9b.jpeg)


# ANTI-LOCK BRAKING SYSTEM

## Introduction

ABS brake pressure in such a way that the wheels do not lock when you brake. This allows you to continue steering the vehicle when braking.
ABS helping you maintain directional control.

### Components

The four major components of a typical anti-lock braking system are:
- Speed sensors - These sensors monitor how fast the wheel or wheels are rotating
- Valves - Valves in the brake line allow, block and release pressure on the brakes by assuming three different positions
- Pump - These pumps are filled with hydraulic fluid and apply pressure to the brake drums or calipers on demand
- Controller - The electronic control unit (ECU) is the brain of the ABS and uses data from the sensors to determine whether or not to pump the brakes

## Structural Diagram

![structure](https://user-images.githubusercontent.com/94296796/152000876-324e66a6-6aec-4ea2-af02-b5d0db23fa14.png)

## REQUIREMENTS

|ID | Description |
|----|----------------|
SYS_1 | If a slight brake is applied, the wheels tend to slip, then the ABS provides grip to the wheels |
SYS_2 | If a sudden full brake is applied in heavy braking situations, the ABS should stop the wheels at a shorter distance to avoid any clashes |
SYS_3 | If vehicles are moving on slippery surfaces like snow, ice, watery, oily, there is less grip when brake is applied on the wheels, the ABS should detect the locking of a wheel and attempt to stop any skidding or locking from occurring |
SYS_4 | If a vehicle is applying brakes while moving on two different surfaces(slippery and non-slippery), then the ABS should provide stability to the vehicle to stop |
SYS_5 | If there are crosswinds, the heavy good vehicles face issues driving in strong crosswinds, here using ABS to apply the brakes to wheels and help keep lorries on the straight and narrow |
SYS_6 | If any fault occurs in the ABS Control system, it should be indicated by the illumination of the ABS warning indicator in the dashboard |

## Block Diagram

![block dia](https://user-images.githubusercontent.com/94296796/152001686-23f786d4-1929-4d9a-9e32-9702d4b9adb8.png)




