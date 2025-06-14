## 🔁 5-Step Sequencer for Analog Synthesizer

This is a breadboard prototype of a **5-step CV sequencer** designed for analog synthesizers. It generates a sequence of control voltages (CV) that can be used to drive oscillators, filters, or other voltage-controlled modules in a rhythmic or melodic pattern.

### 🎛️ Features
- 5 adjustable steps using individual potentiometers
- Each step outputs a control voltage (typically 0–5V or 0–12V)
- LEDs indicate the active step in the sequence
- Clock input to control stepping speed
- Simple and modular design, easy to expand to more steps

### 🧩 Components Used
- Potentiometers (5x) to set CV for each step
- 555 Timer or external clock signal for stepping
- CD4017 Decade Counter (or similar) for step sequencing
- Transistors or diodes for LED drivers
- Resistors, capacitors, and basic passive components
- LEDs for visual step indication

### ⚙️ How It Works
- A clock pulse (internal or external) advances the sequence
- The active step’s voltage (set by the pot) is routed to the CV output
- LEDs show which step is currently active
- Repeats in a loop to create rhythmic or melodic patterns

> 🎵 Ideal for controlling VCO pitch, filter cutoff, or triggering envelope generators in analog synth setups.
