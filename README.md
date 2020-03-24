# mux_sh lite
This is a simplified version of the mux_sh accent mod board for the e-licktronic Nava TR-909 clone. It eliminates three of the sample & hold circuits attached to the multiplexer, because these circuits are unconnected to any part of the Nava accent circuitry. 

## Rationale
I had trouble getting the mux_sh boards included with my Nava to work correctly. Even after much tinkering and testing, I'd get erratic or unpredictable accent behavior from them. I'd get completely different behavior after reflowing any given solder joint on the board.  

I decided to try getting rid of the unused S&H circuits, thereby removing three opamps, several capacitors, and many traces and vias from the PCB design. So far, with the reduced density on the very small PCB, things seem to be more stable and reliable. 

[e-licktronic Nava project page](http://www.e-licktronic.com/en/nava-parts-kit/50-nava-tr909-clone.html)

[Oshpark mux_sh lite project page](https://oshpark.com/shared_projects/01qCJ78d)