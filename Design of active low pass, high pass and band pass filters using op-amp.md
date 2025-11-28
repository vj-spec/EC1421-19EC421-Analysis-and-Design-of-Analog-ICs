# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2025-11-28 at 11 48 27_ed517786](https://github.com/user-attachments/assets/26c71bca-0560-4911-a99e-9a01313f3488)

## HIGH-PASS
![WhatsApp Image 2025-11-28 at 11 48 27_d29113f4](https://github.com/user-attachments/assets/b06ca706-77c4-48c0-82c0-f70e0e0e6eed)

## BAND-PASS
![WhatsApp Image 2025-11-28 at 11 48 27_c9694e99](https://github.com/user-attachments/assets/99776731-b73a-4e40-9248-2e9b7cb66b8f)


## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-28 at 11 48 27_c550265a](https://github.com/user-attachments/assets/b30f2cc6-b44f-4e21-baaf-d78b25949b89)

## HIGH-PASS
![WhatsApp Image 2025-11-28 at 11 48 28_36f387b0](https://github.com/user-attachments/assets/7d99eade-30ff-4c21-b829-f2802e8719bf)

## BAND-PASS
![WhatsApp Image 2025-11-28 at 11 48 28_6a348078](https://github.com/user-attachments/assets/fa4d3683-2776-4fdb-b6c5-3388255c61b6)


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-28 at 11 48 28_5145356f](https://github.com/user-attachments/assets/a09da6e1-8eae-4e97-95f3-ff4475aef6f3)

## HIGH-PASS
![WhatsApp Image 2025-11-28 at 11 48 28_1190180e](https://github.com/user-attachments/assets/a25f7e90-670b-4ab4-9104-35d51bbe62f5)

## BAND-PASS
![WhatsApp Image 2025-11-28 at 11 48 29_b5f9c25e](https://github.com/user-attachments/assets/baf0f352-f7b6-440f-b928-4df94f8c6ea3)

## GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-28 at 11 56 00_9e3a67c2](https://github.com/user-attachments/assets/f6742139-f094-42df-aad0-efed20ea8eb4)

## HIGH-PASS
![WhatsApp Image 2025-11-28 at 11 56 01_5a814921](https://github.com/user-attachments/assets/d0c11266-d616-4460-a29b-28025e267702)

## BAND-PASS
![WhatsApp Image 2025-11-28 at 11 56 01_ab383593](https://github.com/user-attachments/assets/c10054a8-5c1c-4cfc-9cb8-8426db162814)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

