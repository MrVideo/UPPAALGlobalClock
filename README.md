# Global clock in UPPAAL

This [UPPAAL](https://uppaal.org/) model provides a simple example of a global clock that starts first and controls all other templates through a system-defined priority hierarchy.

The clock follows a simple sawtooth graph: it is first initialised at 0, then it is incremented until it reaches a value of 1; finally, it is reset to 0 and the clock tick signal is sent through the `tick` channel.
