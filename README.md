# PCB-Design-of-Waiting-Lignes

I would like to share one of my latest PCB designs that I have just received from jlcpcb

First of all, I'd like to thank jlcpcb for their sponsorship and for supporting young tech enthusiasts like myself in being able to create quality pcb with greate precision

This is the PCB design of a LED display for waiting lines, it can be used in many different cases for example in postoffices, banks and general receptions.

The circuit is designed to optimise the pins of the microcontroller. Each segment is used with one pin of microcontroller. Shift registeris used and only 3 pins are connected to our microcontroller
1 data ( serial input )
2 Shift register clock pin
3 Storage register clock pin (latch pin)

uln2003 Darlington amplifier is used to have a strong current with 7 segment cathode commune.

The voltage regulator lm7805 is used to regulate and distribute the voltage in our circuit.
link of jlcpcb: https://jlcpcb.com/HAR
