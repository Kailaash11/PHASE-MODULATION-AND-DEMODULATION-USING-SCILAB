# PHASE-MODULATION-AND-DEMODULATION-USING-SCILAB
AIM

To write a program for Phase Modulation and Demodulation using SCILAB and to observe and measure the phase deviation and modulation index.

APPARATUS REQUIRED

Computer with i3 Processor or higher
SCILAB Software

THEORY

Phase Modulation (PM) is a modulation technique in which the phase of the carrier signal is varied in accordance with the instantaneous amplitude of the modulating signal, while the amplitude of the carrier remains constant.

Phase Deviation (Δφ)

Phase deviation represents the maximum change in phase of the carrier signal.

Δφ = kp * Am

Where:

kp = Phase sensitivity (rad/volt)
Am = Amplitude of modulating signal
Modulation Index (mp)
mp = Δφ

For sinusoidal signals:

mp = kp * Am
PM Signal Equation
s(t) = Ac cos(2πfc t + kp m(t))

For sinusoidal modulating signal:

s(t) = Ac cos(2πfc t + mp sin(2πfm t))

Where:

Ac = Carrier amplitude
fc = Carrier frequency
fm = Modulating frequency
kp = Phase sensitivity
mp = Modulation index

ALGORITHM

Define parameters:
Sampling frequency Fs
Time duration T
Carrier frequency fc
Modulating frequency fm
Phase sensitivity kp
Generate signals:
m(t) = sin(2πfm t)
c(t) = cos(2πfc t)
PM Modulation:
s(t) = cos(2πfc t + kp * m(t))
PM Demodulation:
Differentiate the PM signal
Apply envelope detection:
|s(t)|
Use low-pass filter to recover the original signal
Plot all signals:
Modulating signal
Carrier signal
PM signal
Demodulated signal

PROCEDURE

Refer to the algorithm and write the SCILAB code.
Open SCILAB software.
Create a new script file.
Enter the program and save it.
Execute the code.
Debug errors if any and re-run.
Observe the generated waveforms.

PROGRAM
![WhatsApp Image 2026-04-09 at 8 46 44 AM](https://github.com/user-attachments/assets/3029458a-a996-4cd2-8b26-5b35644baa4d)

![WhatsApp Image 2026-04-09 at 8 46 55 AM](https://github.com/user-attachments/assets/9c6625e7-dc8e-40aa-8d27-35f5e9b3f273)




TABULATIONS

![WhatsApp Image 2026-04-09 at 8 49 57 AM](https://github.com/user-attachments/assets/cd24485d-d8f5-4de5-9301-e8b015734842)

GRAPH:
![WhatsApp Image 2026-04-09 at 8 46 31 AM](https://github.com/user-attachments/assets/e5d6f452-1b9e-41a2-af76-6e7ba166d4da)


RESULT
.![WhatsApp Image 2026-04-09 at 8 47 06 AM](https://github.com/user-attachments/assets/6e69f495-5c9a-4863-9fc4-035cfafa978a)

