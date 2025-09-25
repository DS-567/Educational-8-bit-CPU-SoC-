## Peripheral Enable Register (PER_EN)

Stores the enable bits for the 5 SoC peripherals (DISP, LCD, I/O, UART and TIMER).

[View schematic (PDF)](PER_EN_schematic.pdf)

---

### Details

- Synchronous 5-bit register (74HC173 4-bit IC x2)
- Red LEDs to show register contents

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active high*)
- PER_EN in (*synchronous - active low*)
- 5-bits of CPU bus

---

### Outputs

- 5-bits of PER_EN contents (*to SoC peripherals - DISP, LCD, I/O, UART and TIMER*)

---

### PCB Spec

- *Black*
- *2 layer*
- *34 mm × 76.5 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/per_en_pcb_top.PNG" alt="PER_EN pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the PER_EN PCB</em></p>

<p align="center">
  <img src="../../images/per_en_pcb_bottom.PNG" alt="PER_EN pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the PER_EN PCB</em></p>

<p align="center">
  <img src="../../images/per_en_pcb_design.PNG" alt="PER_EN pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the PER_EN PCB</em></p>



