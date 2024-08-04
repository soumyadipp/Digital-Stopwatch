## Digital Stopwatch using IC 7490 and 7447

This project is a digital stopwatch built using IC 7490 decade counters and IC 7447 seven-segment display drivers. The stopwatch features six seven-segment displays: two for minutes, two for seconds, and two for hundredths of a second, providing precision timing. A crystal oscillator is used to provide a stable clock signal for accurate timekeeping. The design effectively demonstrates the practical application of digital logic circuits in building a functional stopwatch. This project is ideal for learning about counters, display drivers, and the integration of digital components in a real-world application.

We have used a crsytal oscialltor giving a pulse of frequency of 4.096 MHz .


![image](https://github.com/user-attachments/assets/bb51a207-4515-45a0-9abe-5de9cbdf026d)


It was brought down to 1 KHz by using IC 4060 , which was brought down again to 100 Hz for double digit precision .
This 100 Hz clock was used to run the Decade counter IC's (IC 74LS90) serially one after another and appropiate seven segemnt encoding logic was used by IC 7447 seven-segment display drivers. 


The circuit was initially run on a breadboard for testing purposes. The workbench included the ICs, seven-segment displays, crystal oscillator, and necessary wiring to ensure proper functionality before final assembly.


![Breadborad_test](https://github.com/user-attachments/assets/1720f8b5-1f39-4ba0-8691-07ab87293f91)


Then the circuit was made on Veroboard using a soldering kit. This involved carefully placing the components onto the board and soldering them in place to ensure secure and reliable connections. This step provided a more permanent and durable setup compared to the initial breadboard version.



The final setup involved mounting the components on Veroboard and soldering them in place. This provided a durable and reliable stopwatch, replacing the initial breadboard prototype for long-term use.


![Setup](https://github.com/user-attachments/assets/4a15f609-bf9c-494f-b504-9a8f9c654125)


The circuit was successfully run, demonstrating accurate timekeeping. The final Veroboard setup performed reliably, validating the design and proving the effectiveness of the initial breadboard prototype.


![Upfront](https://github.com/user-attachments/assets/27e37e9a-7da6-4418-b65c-548917cd4bd7)
