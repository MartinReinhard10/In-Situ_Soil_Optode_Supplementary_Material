This repository is to function as supplementary material for the paper "A novel, standalone and low-cost system for in-situ chemical imaging with planar optodes in soils": https://doi.org/10.1016/j.snb.2024.136894

Please find 3D files for printing structural components, wiring diagram and information on electronic + additional components required.

For Python scripts regarding operating the imaging system please refer to the repository: https://github.com/MartinReinhard10/Operate_In-Situ_Soil_Optode

# All requests or questions regarding the repository should be directed at: martinreinhard@bio.au.dk
---

# System Hardware
This is a list of electronic, mechanical, and other components used in the OptodeSystem, including a Raspberry Pi 4, HQ Camera, UV-LED, stepper motors, and various sensors. The document also includes a wiring diagram and links to additional resources for each component.

File (.step) with full 3D model of the system can be provided if needed.
---

# Electronic Components

- **Raspberry Pi 4 Model B 4 GB RAM**
    
    [Raspberry Pi Documentation - Computers](https://www.raspberrypi.com/documentation/computers/)
        
    [Armor Aluminium Heatsink Case for Raspberry Pi 4 • RaspberryPi.dk](https://raspberrypi.dk/en/product/armor-aluminium-heatsink-case-for-raspberry-pi-4/)
    
- **Raspberry Pi HQ Camera**
    
    [Raspberry Pi Documentation - Camera](https://www.raspberrypi.com/documentation/accessories/camera.html)
    
- ****16mm Telephoto Lens for Raspberry Pi HQ Camera (C-mount)****
    
    [16mm Telephoto Lens for Raspberry Pi HQ Camera (C-mount) • Mouser.com]([https://raspberrypi.dk/en/product/16mm-telephoto-lens-raspberry-pi-hq-camera/](https://www.mouser.com/pdfDocs/DFRobot16mm10MPTelephotoLensPO.pdf))
    
- **UV-LED  -** 395 nm
    
    [Datasheet UV-LED](https://www.mouser.dk/datasheet/2/245/Luminus_SST_10_UV_Datasheet-1499199.pdf)
      
- **Resistor** - HS25 18R
    
    [acl_hs10-1890310.pdf](https://www.mouser.dk/datasheet/2/303/acl_hs10-1890310.pdf)
    
- **Stepper Motor (x2) -** 17HS08-1004
    
    [Documentation - 17HS08-1004S.pdf](https://www.oyostepper.com/images/upload/File/17HS08-1004S.pdf)
    
- **Stepper Driver** - A4988
    
    [a4988_DMOS_microstepping_driver_with_translator.pdf](https://www.pololu.com/file/0J450/a4988_DMOS_microstepping_driver_with_translator.pdf)
    
    [In-Depth: Control Stepper Motor with A4988 Driver Module & Arduino](https://lastminuteengineers.com/a4988-stepper-motor-driver-arduino-tutorial/)
    
    - **A4988 Expansion Board**
        (https://store.siqma.com/stepper-motor-driver-board.html?search=expansion)
      
        [Raspberry Pi Stepper Motor Control with NEMA 17 — Maker Portal](https://makersportal.com/blog/raspberry-pi-stepper-motor-control-with-nema-17)
        
        
- **Temperature & Humidity Sensor** - DHT22
    
    [DHT22 - Datasheet.pdf](https://www.sparkfun.com/datasheets/Sensors/Temperature/DHT22.pdf)
    
- **Distance Sensor (Time-Of-Flight)** - VL53L0X
    
    [m5-docs](https://docs.m5stack.com/en/unit/tof)
    
    [Datasheet - VL53L0X_en.pdf](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/VL53L0X_en.pdf)
    
- **Limit switch (x2)**
    
    [Mechanical Endstop - RepRap](https://reprap.org/wiki/Mechanical_Endstop)
    
- **5V Relay module**
    
    [5V Single Channel Relay Module](https://microcontrollerslab.com/5v-single-channel-relay-module-pinout-working-interfacing-applications-datasheet/)
    
- **Buck Converter** - LM2596
    
    [LM2596 Buck Converter Datasheet, Pinout, Features, Applications - The Engineering Projects](https://www.theengineeringprojects.com/2020/09/lm2596-buck-converter-datasheet-pinout-features-applications.html)
    
- **12V Cooling Fan (60x60x10mm)**
  
- **Slip Ring**
    
    [SNF-3P%20updated.pdf](https://cdn.sparkfun.com/datasheets/Robotics/SNF-3P%20updated.pdf)
    
- **Power supply - 12V DC 5A**

---

# Mechanical Components

20 x 40mm V-slot Aluminum Extrusion

20mm V-Gantry Plate with Wheels
       
GT2 Belt - 2mm pitch - 6mm width

GT2 Pulley 20 (diameter: 5mm)

Belt Tensioner 2020 Profile X-Axis

Ball Bearings 8x22x7mm (x4)

---

# Other Components

Ø250mm Plexiglass Cylinder  

- Emission Filter
    
    Zircon UV Blue Blocker from Lee Filters is used to cover the camera lens.
    (https://leefilters.com/colour/821-zircon-uv-blue-blocker/)    

Wiring - See Wiring Diagram

Dupont Wire Pin Header Connectors

Cable Ties

Bolts and Nuts for Assembly - See list of nuts & bolts


