# Architecture

This inverter uses a full H-bridge consisting of four N-channel MOSFETs driven by a gate driver IC.

The microcontroller generates SPWM signals to control switching and produce an AC waveform from a DC source.

Power flow:

DC Source → Gate Driver → MOSFET H-Bridge → LC Filter → AC Output
