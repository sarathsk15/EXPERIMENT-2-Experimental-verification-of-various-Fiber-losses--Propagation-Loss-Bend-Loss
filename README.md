
# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

**Theory:**  
- Losses due to absorption, scattering, bending  
- Plastic fiber loss ~180 dB/km  
- Bending loss increases with reduced loop diameter

  <img width="815" height="431" alt="image" src="https://github.com/user-attachments/assets/ef4632d0-e2dd-4b03-ae63-f571fafe3337" />


**Procedure:**  
- Setup for 660nm and 950nm measurements  
- Measure output voltages for 1m and 3m fibers  
- Calculate attenuation \( a \) using:  
V1/V2 = e [ -a (L1+L2 ) ] 
- Bend fiber and record output vs diameter  

**Tabulation:**

### Propagation Loss

| Fiber Length     | Input Amplitude (V)        | Output Amplitude (V)     |
|------------------|----------------------------|--------------------------|
|    1             |       5                    |       10                 |
|    0.5           |       5                    |       14                 |

### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|----------------------------|--------------------------|
|    1     for 8cm |       5                    |       10.3               |
|    0.5  for 6.4cm|       5                    |       9.76               |

**Calculation**

![WhatsApp Image 2025-11-16 at 17 46 30_7a29abba](https://github.com/user-attachments/assets/1a2ba9e8-e459-4f24-b033-7e568d22b49c)

**Result:**  
The experiment successfully verified the losses in a fiber-optic link:

The propagation (transmission) loss was measured over different lengths of the fiber for two wavelengths (660 nm & 950 nm) and found to increase with length, confirming the expected attenuation behaviour.

The bending loss was observed by varying the loop diameter of the fiber and measuring output amplitude — as the bend diameter decreased, the output dropped, verifying increased bending loss.

Hence, the aim of measuring both propagation loss and bending loss characteristics of the fiber was achieved.

---
