# Optical Amplifier (EDFA) Performance Analysis

## Aim: 
To study the gain and noise performance of an Erbium Doped Fiber Amplifier (EDFA) using Python simulation.

## Apparatus/Software Required:
	Python (NumPy) in Google Colab

## Theory:
	EDFA amplifies optical signals in the C band (1530–1565 nm) using stimulated emission.
	Gain depends on wavelength and pump power.
	Noise figure quantifies SNR degradation.

## Formulas:
## Key Equations
## 1. Gain
Amplifier gain:
G=P_out/P_in 

Gain in dB:
G_dB=10〖log⁡〗_10 (P_out/P_in )

________________________________________
## 2. ASE Power
P_ASE=2n_sp (G-1)hνB_o

where:
	n_sp= spontaneous emission factor 
	G= amplifier gain (linear) 
	h= Planck's constant 
	ν= optical frequency 
	B_o= optical bandwidth 
________________________________________
## 3. Noise Figure
Noise Factor:
F=(SNR_in)/(SNR_out )

For EDFA:
F=2n_sp  (G-1)/G

Noise Figure in dB:
NF=10〖log⁡〗_10 (F)

For high-gain EDFAs (G≫1):
NF≈10〖log⁡〗_10 (2n_sp)

Typical commercial EDFAs have:
NF≈4"-" 6" dB"

________________________________________
## Typical Practical Values
Parameter	Typical Value
Pump wavelength	980 nm / 1480 nm
Signal wavelength	1530–1565 nm
Peak gain	25–40 dB
Saturation output power	10–23 dBm
Noise figure	4–6 dB
Fiber length	5–20 m

## Sample Output
   	Graph: Gain spectrum curve peaking near 1550 nm.
<img width="528" height="388" alt="image" src="https://github.com/user-attachments/assets/15e6aaff-d3f3-42d1-aa76-66bb575b6c93" />
<img width="518" height="469" alt="image" src="https://github.com/user-attachments/assets/cce70c57-34f5-4634-a90e-df47c4e45b62" />
<img width="561" height="461" alt="image" src="https://github.com/user-attachments/assets/0f298da2-0dc1-43fd-bab6-0641a5210748" />

## Python Code

## Output

## Result

