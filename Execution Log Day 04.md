Execution Log: Day 04
Date: January 26, 2026

Focus: Memory-Mapped I/O (MMIO) and Registers

1. Concept: The Register
-Defined as a specialized storage location that is hard-wired to physical hardware functions.

-Unlike variables, registers have "side effects" (e.g., turning on a motor, starting a timer).

2. Concept: Memory-Mapped I/O
-Understanding that the CPU communicates with hardware using the same "Address Bus" it uses for RAM.

-Hardware is essentially "pretending" to be memory addresses so the CPU can talk to it easily.

3. The Systems Perspective
-Hardware control is fundamentally just Pointer Manipulation.

-To control any piece of hardware, a systems engineer only needs two things: The Address (from the datasheet) and the Value (what the bits do).