# counter-application-with-74hc393
Digital electronics 4 bits counter 74hc393

Counter Application with 74HC393
 Electronics Lab  
In this application, we will examine the 74HC393 counter IC. First of all, let's look at the general features of the 74HC393 IC.


This counter IC contains two 4-bit counters. It can also be used as a 4-bit counter only if desired. It is possible to make 4-bit and 8-bit connections according to the need in digital circuits. When we connect the Q3 pin of the 4-bit counter to the CP pin of the other 4-bit counter, we get the 8-bit counter. Similarly, we can increase the 74HC393 integrated number to obtain 16-bit, 24-bit, 32-bit counters. Such successive connections are called cascade connections.

74HC393
The 74HC393 IC is a TTL IC. The supply voltage must be between 3 volts and 6 volts. It is written in the manufacturer's data sheets of the integrated that the operating speed is 28 MHz. It is possible to push this frequency a little more.
Where is this integrated used? The first application that comes to mind is the clock application.
It can be used as a level scanning element in circuits that convert digital to analog signals.
It can be used in digital circuits where time division is required. This means frequency division.
Examples of applications made with this integrated can be multiplied.
We tried the basic test circuit we made on the BreadBoard with 8 LEDs. We connected 1K resistors so that the LEDs and the IC are not damaged by excessive current.
We connected the square wave output of our signal generator (XR2206) to the clock input of the 74HC393 IC. We tested the binary counting operation at different speeds by changing the frequency stages of the signal generator.

The application we have made is available on our youtube channel.

Related link : https://milivolt.news/post/counter-application-with-74hc393
Related video: https://youtu.be/A3ucIgSRem4?si=OOTok6sQ-nV3cnyO
