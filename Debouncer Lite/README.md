The Debouncer Lite is a digital circuit designed to eliminate switch bouncing effects from mechanical inputs such as push buttons and toggle switches. Switch bouncing can cause multiple unintended transitions, and this lightweight design ensures a clean and stable digital signal output.

Features:
Removes glitches caused by mechanical switch bounce

Provides a stable single output pulse for each button press

Lightweight implementation (optimized for resource efficiency)

Works with a wide range of clock frequencies

Can be easily integrated into FPGA, CPLD, or microcontroller projects

Working Principle:
When a mechanical switch is pressed, its contacts often bounce for a few milliseconds, creating multiple unwanted transitions.
The Debouncer Lite solves this problem by:

Sampling the input switch signal using a clock.

Waiting for the input to remain stable for a fixed time window.

Updating the output only after stability is confirmed.
