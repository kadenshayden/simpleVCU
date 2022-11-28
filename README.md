# simpleVCU
This is a simple Vehicle Control Unit (VSU), utilizing arduino hardware. The intended use for this is motorcycles where the MicroSquirt is often used. 


This project was inspired by my project motorcycle, the 1978 Kawasaki KZ550A. I purchased this bike a few months ago and was frustrated by the constant breakdowns due to electrical issues. The bike itself is carburated, but I can't go very far if my headlight randomly goes out or if my brakelight calls in sick. 

So I started research on creating my own wiring harness, using what I learned from my time at Spartan Racing SJSU. Since the wiring is so simple, I can elimnate many unnesscary signals by utilizing wireless connections from off the shelf hardware. As well as this, utilizing the chassis as a ground will get rid of half the wiring in one simple step. 

The bike needs only a few +12V/-12V connections, battery charging circuit, and several relays to activate horn, signals, highlight (high/low beams), a running light, and a brake light. 

A prototype has been created using a bread board, arduino mega, and srd-12vdc-sl-c relays. 

The obvious worry is that Arduino hardware isn't weatherproofed or vibration isolated. An easy fix for this is to enclose it in an aluminum casing, utilinzg rubber standoffs from McMaster to isolate the board from vibration. I haven't heard of anybody having a board die from vibration, but you wouldn't want it to happen on the track. 

Goals:
-Add bluetooth support. This can be used for anything from anti-theft (disconnect ign.) to simply checking the charging circuit output.
-Elimate stock starter solenoid with something more compact
-Minimize total amount of wires needed on bike.
