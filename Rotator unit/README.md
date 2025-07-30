The Rotator Unit is a digital logic module that performs circular rotation on an 8‑bit input value. On each clock cycle, it rotates the bits either left or right by one position, depending on the direction control signal. This project demonstrates sequential logic design and bit manipulation techniques in Verilog.

Features:
8‑bit circular rotation (wrap‑around rotation)

Direction control:

0 → Rotate Left

1 → Rotate Right

Operates on every clock cycle

Resettable to a given input value

Lightweight design for FPGA, CPLD, or simulation environments

Working Principle:
On reset, the module loads the given input (data_in).

On each positive clock edge:

If dir = 0, the bits are rotated left by one position.

If dir = 1, the bits are rotated right by one position.
