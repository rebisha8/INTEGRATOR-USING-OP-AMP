# INTEGRATOR-USING-OP-AMP

## AIM:
To design and test the performance of integrator and differentiator circuits using Op-amp.

## APPARATUS REQUIRED:
<img width="700" height="201" alt="image" src="https://github.com/user-attachments/assets/7cbeb741-349e-43f5-a78f-312dd3f338b4" />

## THEORY:
## INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is  replaced by a capacitor Cf .  The expression for the output voltage is given as,

<img width="166" height="35" alt="image" src="https://github.com/user-attachments/assets/340f2d59-4180-462c-882e-e3a211fdd4d9" />

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,

<img width="99" height="47" alt="image" src="https://github.com/user-attachments/assets/5924cac3-b14a-4af2-9e4c-1290887907e6" />

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.

## DESIGN:
To obtain the output of an Integrator circuit with component values R1Cf = 0.1ms , Rf = 10 R1 and Cf = 0.01 µF and also if 1 V peak square wave at 1000Hz is applied as input.
We know the frequency at which the gain is 0 dB, fb = 1 / (2π R1 Cf) 
	

## INTEGRATOR CIRCUIT DIAGRAM:  
<img width="698" height="423" alt="image" src="https://github.com/user-attachments/assets/4d02dde2-a299-4481-9c63-abee62084cce" />

## PROCEDURE:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

## MODEL GRAPH:
i)	SINE WAVE INPUT
<img width="556" height="381" alt="image" src="https://github.com/user-attachments/assets/adeaae37-ac10-46c0-92b3-0397faca7165" />

ii)  SQUARE WAVE INPUT
<img width="847" height="553" alt="image" src="https://github.com/user-attachments/assets/ab1e5f5e-e1a5-47bf-affe-cc241b646aa5" />


## TABULATION:
![WhatsApp Image 2025-10-19 at 21 15 21_ed7ac177](https://github.com/user-attachments/assets/b1186bd4-94dc-4372-90db-f3461d2792e2)


## GRAPH:
![WhatsApp Image 2025-10-19 at 21 15 21_5c7e38bd](https://github.com/user-attachments/assets/292e8e19-97c5-42e9-84d5-04f3f6f54c05)
![WhatsApp Image 2025-10-19 at 21 15 20_af00806f](https://github.com/user-attachments/assets/990260f1-b77f-4bfc-8c40-da6000b2c590)


## RESULT:
Thus, the Integrator is designed and the performance is tested using Op-Amp.
