# handheld-led-matrix-prototype

A handheld game console prototype built around a Teensy 4.1 and a 64×32 HUB75 RGB LED matrix display.

This project combines embedded systems, digital electronics, PCB design, and mechanical design to create a fully custom handheld gaming platform. The system uses a Teensy 4.1 to drive a high-speed RGB LED matrix through custom logic-level shifting circuitry and other supporting electronics.

I originally started this project because I wanted to learn more about embedded systems beyond the classroom and create something visually impressive that could showcase both hardware and software engineering skills. 

I also learned alot about soldering doing this project since one of my original goals was to create this project completely from scratch. I had a lot of trial and error using perfboards and although my goals have changed, I now understand the fundamentals of soldering. In fact, I even soldered 2.54mm header pins to Teensy 4.1 since it my ordered package did not arrive pre-soldered. 

---

## Hardware
* Teensy 4.1 microcontroller
* 64×32 HUB75 RGB LED Matrix (P2.5, 1/16 Scan)
* Custom logic-level shifting circuitry

  * 2× SN74AHCT245 bus transceivers
  * 1× SN74HCT374 D FlipFlops
* 470 µF power supply capacitor
* 0.1uF decoupling capacitors
* Inline fuse protection
* 5V barrel jack external power supply
* Custom PCB (in development)
* 3D-printed handheld enclosure (in development)

---

## Software
* Arduino IDE
* Teensyduino
* SmartMatrix Library
* Custom game engine and display routines
* Input handling and game logic
* Used Altium Designer for PCB design
* Used TinkerCAD for outer handheld enclosure

---

## Design Goals

* Create a fully custom handheld gaming platform
* Design and manufacture a custom PCB
* Develop a modular software framework for multiple games
* Design a 3D-printed enclosure using TinkerCAD
* Explore thermal, mechanical, and power design considerations
* Document the complete engineering process for portfolio and educational purposes

---

## Documentation
https://docs.google.com/document/d/1Mj_qr_Yws2TstoquD6Upexz5me1fRSkTJ5Tjjy_lT1I/edit?usp=sharing 

<img width="2304" height="3072" alt="image" src="https://github.com/user-attachments/assets/3731e4c7-69a0-4e9a-87de-6d2ac40fbd49" />
<img width="2304" height="3072" alt="image" src="https://github.com/user-attachments/assets/d268a1f6-8ba1-4286-a253-da5ac3b131ed" />
<img width="2304" height="3072" alt="image" src="https://github.com/user-attachments/assets/dc6e70f2-03d7-4dcc-9678-c04a5345be7c" />



