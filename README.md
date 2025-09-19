# Battery Eliminator using Zener diode:
'''
A Battery Eliminator Circuit (BEC) using a Zener diode is designed to provide a stable and regulated DC output voltage from an AC mains supply. The primary objective of the circuit is to eliminate the need for conventional batteries in low-power electronic devices by delivering a constant voltage, even when input voltage levels fluctuate. The Zener diode acts as the key voltage-regulating component, maintaining a fixed output voltage by clamping any excess voltage and protecting the connected load. The circuit is expected to operate efficiently across varying input conditions and ambient temperatures, while minimizing power consumption and heat generation. Simplicity, reliability, and cost-effectiveness are central to the design, using basic and readily available components such as resistors, capacitors, diodes, and a transformer. Proper safety features, including current-limiting resistors and isolation through a step-down transformer, are included to ensure safe operation in accordance with electrical safety standards.

'''
# Components and its description:
1.Zener Diode:
A Zener diode is a two-terminal semiconductor device specifically designed to operate in the reverse breakdown region. The key characteristic of a Zener diode is its ability to maintain a constant voltage across its terminals once the reverse voltage exceeds a specified breakdown value, known as the Zener voltage. This makes it an ideal component for voltage regulation and protection in electronic circuits. When connected in reverse bias and the input voltage reaches the Zener breakdown level, the diode conducts and stabilizes the voltage, protecting sensitive components from overvoltage conditions. Unlike regular diodes, which block reverse current, the Zener diode allows controlled reverse current flow, making it suitable for use in power supplies, reference voltage sources, surge suppressors, and clamping circuits. While it cannot amplify signals, the Zener diode is widely used in circuits requiring precise voltage control and reliable operation under fluctuating input condition.

2.Electrolytic Capacitor:
A capacitor is a device that stores electrical energy in an electric field by accumulating electric charges on two closely spaced surfaces that are insulated from each other. It is a passive electronic component with two terminals.

3.Transformer
The transformer used here is a center-tapped step down transformer with an output voltage of 9-0-9V. A center- tapped transformer is chosen here because a full wave rectifier can be modeled using one.

4.	PN Junction Diodes:
FIGURE 2.5.3 PN Junction Diode
Two 1N4007 diodes are used in our circuit. The 1N4007 is picked here for its versatility and its ability to block current while in reverse bias.

5.Resistor:
Two 1kΩ and one 330Ω resistors are used. The 1kΩ resistors are used as load resistors, and the 330Ω resistor is used to limit the current  fed into the Zener.

6.Led:
A led is used to indicate that a constant dc voltage is been provided.

Alternate Components:


<img width="538" height="184" alt="image" src="https://github.com/user-attachments/assets/8467389e-ee82-4fb0-a7b3-f51ce4031a9e" />





