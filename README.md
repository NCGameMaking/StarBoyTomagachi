# StarBoyTomagachi

<img width="1917" height="1095" alt="image" src="https://github.com/user-attachments/assets/99a4dbc4-0e56-4d2e-ba7d-a86713356867" />



**This is Starbie, my first hardware project. Starbie is a tiny motion-controlled digital pet: basically a desktop Tamagotchi with minimal gameplay buttons. Instead of pressing controls, you interact with it by physically moving the board.**

## What it is
Starbie is designed to sit on your desk, show its personality on a small display, and react to how you handle it. Tilting, moving, and otherwise checking in on your pet are meant to be part of the experience.

The board includes a microcontroller, display, motion sensor, and environmental sensor in a compact PCB design. It is USB powered and built around beginner-friendly through-hole soldering for the add-on components.

## Why?
This project was created to be the week 1 beginner tutorial for halflife!

## Project status
The PCB design, renders, and an Arduino starter firmware are included here. The default program is a cute duck with a tilt-controlled radial menu, hidden stats, and a shake reaction.

## Software
Firmware/ contains one self-contained Arduino IDE sketch for the XIAO ESP32-C3. Builders customize pins, menu actions, starting values, and motion settings together at the top of the sketch. The folder also includes a draggable browser simulator.

*Made for the HackClub Halflife Program : Week 1!*
