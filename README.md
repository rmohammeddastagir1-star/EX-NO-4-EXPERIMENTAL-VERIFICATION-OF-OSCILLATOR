# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:25.10.2025
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 450K, 1.5K,15k| 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
![WhatsApp Image 2025-12-01 at 00 56 00_cd37692b](https://github.com/user-attachments/assets/b578138e-de6b-4adb-ae0f-f0d895dbe4dd)




---

## MODEL GRAPH
<img width="414" height="324" alt="image" src="https://github.com/user-attachments/assets/3389b740-b70e-4148-9bf9-e5319627260f" />

## DESIGN

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION
![WhatsApp Image 2025-12-03 at 21 22 18_7aa571ba](https://github.com/user-attachments/assets/e18f6592-09a5-4b0b-91a9-49ed917a12f3)

![WhatsApp Image 2025-12-03 at 21 22 50_29598037](https://github.com/user-attachments/assets/238eacff-e98f-4df6-a39c-54c123565d78)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-01 at 01 05 19_1985c0fd](https://github.com/user-attachments/assets/be0df04d-8ca7-47a8-8828-2c9b845d63e1)

---
## THEORY
 ##WIEN BRIDGE
 ## DATE : 01.11.2025
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 30k,15k,1.5k | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
	![WhatsApp Image 2025-12-01 at 01 07 28_d8039572](https://github.com/user-attachments/assets/f7b7b22c-6d0a-4434-a38c-889a44060ad1)


---
## MODEL GRAPH
<img width="414" height="325" alt="image" src="https://github.com/user-attachments/assets/1cc285f7-05c7-4b65-af59-b28cf039fcd3" />

---

## DESIGN

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION
![WhatsApp Image 2025-12-01 at 01 08 48_7b063cf1](https://github.com/user-attachments/assets/eefef6cd-2776-4da7-9f6c-c72cfb2a7187)

![WhatsApp Image 2025-12-03 at 21 23 03_3cc72e5b](https://github.com/user-attachments/assets/f1d2a34d-7d7c-49e5-9776-1e0759d9fdf9)


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 01 09 29_fcd860d0](https://github.com/user-attachments/assets/1e8429c8-d76e-4d73-b5ff-624854d4f312)


---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
