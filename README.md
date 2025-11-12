This project presents the simulation of a Switched-Capacitor Boost Inverter (SCBI) topology using MATLAB/Simulink, designed to operate efficiently from a constant DC source.
The model integrates the principles of both switched-capacitor (SC) circuits and inverter configurations to achieve a high voltage gain without the need for bulky magnetic components or multiple DC sources.
By using a reduced switch count, the circuit minimizes conduction and switching losses, improving overall efficiency and reliability.
The system effectively converts the constant DC input into a boosted multilevel AC output, making it highly suitable for renewable energy and low-power conversion applications.
Performance is analyzed in terms of voltage gain, output waveform quality, and component stress, highlighting the advantages of the SCBI topology for compact and cost-effective power conversion systems.
Working:
1.DC Input:
A single DC source (Vdc) is given as the input to the inverter.

2.Capacitor Charging:
Some switches turn ON to charge the capacitors from the DC source.

3.Series Connection (Boosting):
During switching, the capacitors are connected in series with the source to boost the output voltage.

4.Different Voltage Levels:
By changing the switch combinations, different output voltages are produced like Vdc, 2Vdc, 3Vdc, 0, -Vdc, -2Vdc, -3Vdc (7 levels).

5.PWM Control:
PWM (Pulse Width Modulation) is used to control which switches turn ON and for how long, shaping the AC output waveform.

6.Gate Pulses:
The PWM signals are converted into gate pulses that drive the MOSFETs, deciding the ON/OFF timing of each switch.

7.AC Output:
The combined action of switches, capacitors, and PWM produces a 7-level stepped AC output that approximates a sine wave.
