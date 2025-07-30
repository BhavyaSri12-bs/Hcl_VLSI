The Seq Check project is a digital logic design that detects a specific sequence of bits in a serial input stream using a Finite State Machine (FSM). It is a classic application of sequential circuits, widely used in digital communication, error detection, and control systems.

Features:
Detects a predefined binary sequence (e.g., 1011) in a serial input

Built using FSM principles (Mealy or Moore – specify in your design)

Outputs a high signal (1) when the sequence is detected

Can be easily modified to detect different sequences

Works efficiently in FPGA/ASIC implementations or simulations

Working Principle:
The FSM transitions between states based on the incoming bit stream.

When the desired pattern is recognized, the output goes high.

Overlapping sequences can also be detected (if enabled in the design).
