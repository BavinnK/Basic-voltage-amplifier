# Voltage Amplifier Simulation in Proteus

## Overview
This project demonstrates a simple voltage amplifier circuit using a **BC547 transistor**, designed and simulated in **Proteus**. The circuit takes an AC input signal of **2V peak-to-peak (Vpp)** and amplifies it to an output of approximately **9.56V peak-to-peak**, confirming a successful amplification process. The circuit is powered by a **15V DC power supply (Vcc)**.

## Circuit Components
- **Q1 (BC547 NPN Transistor)**: Acts as the amplifying element in a common-emitter configuration.
- **R1 (5kΩ) & R2 (100kΩ)**: Form the voltage divider network to bias the transistor.
- **R3 (13kΩ) & R4 (1kΩ)**: Determine the gain of the amplifier and stabilize the operation.
- **C1 (1µF) & C2 (0.47µF)**: Coupling capacitors to block DC and pass AC signals.
- **AC Signal Source**: Provides a 2V peak-to-peak input signal.
- **DC Power Supply (Vcc = 15V)**: Powers the transistor amplifier.
- **Oscilloscope & AC Voltmeters**: Used for analyzing input and output signals.
## Circuit Diagram and result
![digarm](https://github.com/user-attachments/assets/2358e1cc-ba30-4daa-8700-621921fa1b8a)


## Working Principle
1. The **input AC signal** passes through capacitor **C2**, which blocks any DC component and ensures only the AC signal reaches the transistor’s base.
2. **R1 and R2** form a voltage divider that provides a stable bias voltage to the transistor's base.
3. The **transistor (Q1)** amplifies the signal by increasing its voltage gain.
4. **R3 (Emitter Resistor)** provides stability, and **R4 (Collector Resistor)** affects the voltage gain.
5. The **output AC signal** is taken from the transistor’s collector and passes through **C1**, which blocks the DC component before reaching the output.
6. The oscilloscope confirms the amplified waveform, and AC voltmeters verify the voltage levels.

## Simulation Results
- **Input Voltage (Vpp)**: 2V
- **Output Voltage (RMS)**: 3.38V
- **Output Voltage (Vpp)**: ~9.56V
- **Amplification Factor**: ~4.78x

## How to Run the Simulation
1. Open **Proteus** and load the provided schematic file.
2. Ensure all components are properly placed as per the circuit diagram.
3. Apply a **2V peak-to-peak AC signal** at the input.
4. Connect **15V DC as Vcc** to power the circuit.
5. Observe the input and output signals using the **oscilloscope and AC voltmeters**.
6. Verify the amplification by comparing input and output voltage readings.

## Conclusion
This simple **transistor-based voltage amplifier** successfully amplifies the input signal, demonstrating a practical application of common-emitter amplifier design. The circuit can be further modified for higher gain, better stability, or different transistor choices based on specific needs.

## Future Improvements
- Implementing **negative feedback** for improved stability.
- Using a **Darlington pair** for higher gain.
- Adding a **bypass capacitor** across the emitter resistor to enhance AC gain.
- Simulating with different transistor models for comparison.



