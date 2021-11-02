# Breadboard-constant-voltage-power-supply-module
We can directly plug this module into breadboard and supply different voltages as our project needs.
Hello guys, welcome back to another tutorial, how to make a constant voltage power supply breadboard compatible module. In this, we will learn how to switch between different voltage levels. i.e., 5volts and 3.3volts. And how to make your own PCB design using the same technique. Specially, My PCB design is sponsored by JLCPCB.
![20211029_113540](https://user-images.githubusercontent.com/86649536/139813566-9b2434a4-3b38-448d-a0cf-6f4d3a2126e9.jpg)

Features:
1) 5v, 3.3volts switchable output
2) Micro USB port for Input
3) Usb Type c available for I/O
4) Power led and switch
5) USB type A for 5volt output
6) Pin compatible with generic breadboards
7) Extra female and male headers for Jumper wires

Circuit diagram:
![Schematic_breadboard v1_2021-10-27](https://user-images.githubusercontent.com/86649536/139813796-a1e81211-ece7-4c92-b8e9-9b3c000ca887.png)

Components used:
1) Ams1117-3.3volt x1
2) Ams1117-5volt x1
3) Micro USB jack x1
4) Usb c- type x1
5) Usb type A x1
6) Led 0805 package x1
7) 1k resistor 0805 package x1
8) 100nf capacitor 0805 x2
9) Slide switch
10) Pin headers (Male + female)

Circuit basics:
Here we are using AMS 1117 voltage regulators for stable dc output. Input can be given through any battery or charger, micro Usb and c-type port is provided to connect charger for input. USB type A is given for 5volt constant output. A slide switch is used to ON/OFF the circuit. Small LED with 1k resistor indicates the power. Two 100nf capacitor filter the input and output voltages. Through pin headers extra jumper wire can be connected.
![op](https://user-images.githubusercontent.com/86649536/139813922-1a3647a0-7bdf-4298-9e9f-4b8a2194ad43.jpg)

Working & switching between 2 different voltages:
Here, we can switch between two different voltages i.e 5volt/3.3volt. On both side of breadboard 4 pin headers are provided to change the mode manually using shorted female headers.
![Untitled](https://user-images.githubusercontent.com/86649536/139813986-aba6fa8f-f4cf-4351-8502-bb0a09b542b1.png)
We can use both the modes at same time, keeping one shorted jumper on 5volts and other at 3.3volts.

Pcb layout:
![2d view](https://user-images.githubusercontent.com/86649536/139814088-156caf2f-3770-442a-a516-e4543bf37e80.png)

About JLCPCB:
JLCPCB is CHINA’s No.1 PCB manufacturing company. Offers high precision Pcb boards, Low cost and fast delivery. Try JLCPCB in just $2 for 2-layer PCB boards and $5 for 4-layer PCB. Easy to order and provide 6-color solder mask options. Try from herehttps://jlcpcb.com/IAT
![op1](https://user-images.githubusercontent.com/86649536/139814186-344fc340-8c07-4c3d-9e1a-7e618db7d019.jpg)
register using this link and get $30 coupons to order PCB.

More projects:
1) Arduino based IR decoder.
2) IR remote control electric board using Arduino.
3) Inductor meter using Arduino.
4) Bass, Treble and volume control board using simple components.
