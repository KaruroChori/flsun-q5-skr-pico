Why?
- Because the original mks robin nano 1.2 is semi-bricked and cannot accept upgrades via sd. This seems to be a common issue as I experienced it on two printers of the same model, and there are few references online.
- Support for tmc2209 with serial connection available.
- 2 PWM channels for fans.
- A significantly wider range of options in terms of connectivity.

Images have been built for klipper 0.12.x

Useful references:

- [MKS Robin Nano 1.2](https://github.com/makerbase-mks/MKS-Robin-Nano-V1.X/blob/master/hardware/MKS%20Robin%20Nano%20V1.2_003/MKS%20Robin%20Nano%20V1.2_003%20PIN.pdf)
- [SKR nano docs](https://github.com/bigtreetech/SKR-Pico/tree/master/Klipper)

Don't use as it is. The way I wired might be different from yours.  
I based my wiring on the functional equivalence in the default described by makerbase and bigthreetech documentations.  
However, it seems like the flsun q5 had the bed and extruder thermistors swapped, so take care of that when first testing it.
