# fpga-vcu-omega-encoder



Rotational encoder interface having support for the following types of encoders:
1. Quadranture A-B Encode
2. Quadranture A-B Encoder w/differential inputs
3. Quadranture A-B Encoder with X/Z channel
4. Quadranture A-B Encoder with X/Z channel and differential inputs
5. Greycode Encoder up to 24 bits

The IP core provides the following features:
- Absolute raw position (raw shaft position) in normalized form (fixed point)
- Output shaft position based on gear ratio in normalized form (fixed point)
- Odometer counter with reset (32 bits) (in counts)
- Encoder line error (bad transition, etc)
- Velocity Calculation in fixed point
- Acceleration Calculation in fixed point


The IP core can be interfaced with the following interfaces:
- AXI4-Lite (configuration and data access)
- AXI4-Stream
  - Raw Position Stream
  - Output Shaft Position Stream
  - Velocity Stream
  - Acceleration Stream
  
  
  








