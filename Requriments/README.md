## INTRODUCTION
Our integrated circuits and reference designs for automotive exterior rearview mirror modules help you accelerate design through accurate light sensors and LED lighting solutions with high precision in controlling and driving electrochromic mirrors and high integration for human interface (HMI) control.
Modern rearview mirror modules require:
Accurate, stable control of large capacitive load for electrochromic auto dimming.  Precise sensing of ambient light to allow effective auto dimming.

## FEATURES
### BLIND SPOT DETECTION 										
Blind spot detection (BSD) was developed by Volvo a decade ago. BSD tracks traffic just behind you as well as what’s coming alongside. The alert stays active until the car in the adjacent lane is in front of you, or at least directly alongside and you’d have to be blind not to see it. It doesn’t care if you are in your lane or have drifted a bit into the next and are at risk of sideswiping another car. BSD uses ultrasonic or radar sensors on the side and rear of the car.
### DEFOGGERS	
These features are used to defog the rear window, and to remove raindrops, dew and frost from the outside rear view mirrors. The defoggers will automatically turn off after 15 to 60 minutes. The operation time changes according to the ambient temperature and vehicle speed.

## COMPONENTS
### DC MOTOR
Each rear-view mirror has two DC motors. One DC motor operates the up/down function while the other DC motor operates the left/right function. Both rocker switches inside the power mirror switch are constantly connected to the vehicle's electrical ground circuit with the switch at rest.
### INFRARED SENSOR
An infrared sensor (IR sensor) is a radiation-sensitive optoelectronic component with a spectral sensitivity in the infrared wavelength range 780 nm … 50 µm. IR sensors are now widely used in motion detectors, which are used in building services to switch on lamps or in alarm systems to detect unwelcome guests(In this case, Cars).
### RADAR
Radar is a electromagnetic sensor used for detecting, locating, tracking, and recognizing objects of various kinds at considerable distances. ... The targets may be aircraft, ships, spacecraft, automotive vehicles, and astronomical bodies, or even birds, insects, and rain.


## REQUIREMENTS

### HIGH LEVEL REQUIREMENTS

|   | TITLE  | MODULES  |  DESCRIPTION |
|---|---|---|---|
| SYS_1 | Requirments | DC MOTOR  | The Side Rear View Mirror should Open when the Engine Ignites.|
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


