# Analogue-CMOS-IC-Design-Assignment-2026-January
Voltage Reference 900mV, 1000ppm/V (1.2V to 1.8V), <25uA total current consumption, <10% transient overshoot/undershoot (1.2V to 1.5V pulse), C5 Process (0.6um).

Electric-9.07 (.jelib) Analogue Schematic and Layout, modified BMR from "A Compact Delay-Locked Loop for Multi-Phase Non-Overlapping Clock Generation" library and Atharva Raut's amplifier layout.

---

### LTspice simulated results using C5 model
**DC sweep**
<img width="1894" height="400" alt="image" src="https://github.com/user-attachments/assets/ce148344-2a64-4801-91f9-12334c8a55f3" />

**Transient**
<img width="1897" height="402" alt="image" src="https://github.com/user-attachments/assets/d6e419a1-5099-451c-a2e1-0ff7ec593db6" />

---

### Ad hoc Schematic and Layout
**Schematic**
<img width="725" height="840" alt="image" src="https://github.com/user-attachments/assets/eabdb61e-d6f2-44e3-a1f6-58b5f02a48b4" />

**Layout**
<img width="1589" height="733" alt="image" src="https://github.com/user-attachments/assets/d0ce054d-b7ae-4d37-9381-3ea62f1e467d" />
Size: 360 x 163.5 <br>
Technology: mocmos (scale=300.0nm,foundry=MOSIS)

---

### References:
https://cmosedu.com/jbaker/papers/2010/DLL_WMED_poster.pdf <br>
https://positivefb.com/beta-multiplier-reference/ <br>
https://github.com/Atharva-Raut/Electric_VLSI_Designs
