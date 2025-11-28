# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DIFFERENTIATOR

## AIM:
To design and test the performance of differentiator circuits using Op-amp.

## APPARATUS REQUIRED:
<img width="984" height="273" alt="image" src="https://github.com/user-attachments/assets/2bfcbf8e-9b24-441c-a0c5-b04e0b1bee8d" />

## THEORY:
## DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,

Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1. Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 μF, calculate the value of Rf.
2. Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.
The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM:
![WhatsApp Image 2025-11-28 at 10 54 05_5d26b8c9](https://github.com/user-attachments/assets/25a56696-2b53-46ab-815f-29552dee3bbc)


## MODEL GRAPH:
![WhatsApp Image 2025-11-28 at 10 54 06_973240f2](https://github.com/user-attachments/assets/5d6c864a-bc24-47da-9f90-9956e8b5f7ec)
![WhatsApp Image 2025-11-28 at 10 54 06_2294f857](https://github.com/user-attachments/assets/df2840f4-163a-4267-9d46-1d11157e122e)



## PROCEDURE:
### Differentiator:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
   
## DESIGN:
<img width="837" height="443" alt="image" src="https://github.com/user-attachments/assets/fee44ef4-8ae5-4b7a-938e-927c4492992e" />

## TABULATION:
![WhatsApp Image 2025-11-28 at 10 54 05_26468eb1](https://github.com/user-attachments/assets/e6b4941b-b936-4983-9eba-2d30fec5f379)

## GRAPH:
![WhatsApp Image 2025-11-28 at 10 54 06_a74029e8](https://github.com/user-attachments/assets/98e91dd7-dda2-4dd7-8f0c-6ace29da5663)



## RESULT:
Thus the Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
