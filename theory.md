 

A counter is a sequential circuit that goes through a prescribed sequence of states upon the application of input pulses. The input pulses called count pulses, may be clock pulses, or they may originate from an external source and may occur at prescribed intervals of time or at random.

### Synchronous Counter

Synchronous counters are designed in such a way that the clock pulses are applied to the CP inputs of all the flip-flops. The common pulse triggers all the flip-flops simultaneously, rather than one at a time in succesion.

In the 3-bit synchronous counter, we have used three j-k flip-flops. As in the diagram, The J and K inputs of FF0 are connected to HIGH. The inputs J and K of FF1 are connected to the output of FF0, and the J and K inputs of FF2 are connected to the output of an AND gate, which is fed by the outputs of FF0 and FF1.
