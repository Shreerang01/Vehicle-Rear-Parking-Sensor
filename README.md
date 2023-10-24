
# Vehicle Rear Parking Sensor

The "Vehicle Rear Parking Sensor" is a sophisticated yet user-friendly Arduino-based system designed to enhance vehicle safety during the reverse motion, particularly when parking. This project empowers drivers with a cost-effective and customizable solution to assist in avoiding collisions with obstacles and provides real-time feedback through both visual and audible cues.

## Table of Contents

- Installation
- Project Link
- Project Components
- Features
- Getting Started
- Schematic
- Usage
- Contributing
- Acknowledgements
- License
## Installation

```bash
  -Go to my project link below
  -Tinker/Copy it on your account
  -Run Locally by starting Simulation
```
    
## Poject Link

https://www.tinkercad.com/things/hjvod32Qztq?sharecode=NqhRaQLze1yFhvMTblv0qPBPCGoXOv7w3oCXxAKSJAk
## Project Components

-  Arduino Uno 
-  Ultrasonic Sensor 
-  LEDs 
-  Resistors (1 k Ω) 
-  Buzzer 
-  Connecting Wires 
-  Breadboard 


## Features

- Ultrasonic Sensing: 
  Utilizes ultrasonic sensors for accurate obstacle detection by   measuring sound wave reflection.
- Distance Measurement: 
  Provides real-time distance feedback to maintain a safe distance from obstacles.
- Visual Feedback: 
  Multiple LEDs indicate obstacle proximity, aiding quick decision-making.
- Audible Warning: 
  A buzzer emits alerts when the vehicle approaches obstacles dangerously close.
- Customizability: 
  Built on Arduino Uno, the project is open source and highly adaptable to user needs.

## Getting Started

For Actual Implementation

    1. Clone this repository to your local machine.

    2. Open the `vehicle_rear_car_parking_sensor1.ino` file using the Arduino IDE.

    3. Upload the code to your Arduino UNO R3.

    4. Wire up the hardware components as per the provided schematic.

    5. Power on your Arduino and interact with the system.

    6. Note the Obeservations
## Schematic

![Schematics](https://github.com/Shreerang01/Vehicle-Rear-Parking-Sensor/assets/113919844/59a0e707-7535-49c1-92b1-72ca9b3dfc8f)

## Usage

### Setting up the Parking Sensor System

- Hardware Setup:

    Mount the ultrasonic sensors on the rear bumper of the vehicle. Ensure they have a clear view of the area you want to monitor.
    Connect the sensors to the Arduino Uno as per the provided schematics.
    Make sure to provide power to the Arduino board.

- Software Setup:

    Download and install the Arduino IDE on your computer if you haven't already.
    Uploading the Code:

    Open the Arduino IDE and load the Arduino source code provided in this repository.
    Select the appropriate Arduino board and port in the IDE.
    Upload the code to the Arduino Uno.
    Using the Parking Sensor System

- Power On:

    Ensure that the parking sensor system is powered on and operational.
    Visual Feedback:

    Observe the LEDs on the system. They will provide visual feedback to indicate the proximity of obstacles:
    - Green LEDs: Obstacles are at a safe distance.
    - Yellow LEDs: The vehicle is getting closer to an obstacle.
    - Red LEDs: The vehicle is dangerously close to an obstacle.
    
- Audible Warning:

    Listen for the buzzer, which will produce a warning sound when the vehicle is dangerously near an obstacle.

- Parking Guidance:

    Use the visual and audible feedback to gauge your distance from obstacles while parking.
    Adjust your parking maneuvers based on the system's indications to avoid collisions


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

Anyone can contribute to the project by simply tinkering the project to your local machine and adding new features and functionalities and and making it more useful.

## Acknowledgements

 - [Tutorials Point ](https://www.tutorialspoint.com/arduino/arduino_ultrasonic_sensor.htm)
 - [Coderdojo Athlone ](https://coderdojoathlone.com/en/resources/electronicresources/ultrasonic-sensor-2019 )
 - [Last Minute Engineers  ](https://lastminuteengineers.com/arduino-sr04-ultrasonic-sensor-tutorial/ )
  - [Arduino Documentation  ](https://docs.arduino.cc/hardware/uno-rev3 )

 



## License

[MIT](https://choosealicense.com/licenses/mit/)

