## Memory Address Register (MAR)

Stores the address for CPU memory accesses.

[View schematic (PDF)](MAR_schematic.pdf)

---

### Details

- Synchronous 8-bit register (74HC173 4-bit IC x2)
- blue LEDs to show register contents

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active high*)
- MAR in (*synchronous - active low*)
- 8-bit CPU bus

---

### Outputs

- 8-bit MAR contents (*to RAM memory address*)

---

### PCB Spec

- *2 layer*
- *24.75 mm × 53 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/mar_pcb_top.PNG" alt="MAR pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the MAR PCB</em></p>

<p align="center">
  <img src="../../images/mar_pcb_bottom.PNG" alt="MAR pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the MAR PCB</em></p>

<p align="center">
  <img src="../../images/mar_pcb_design.PNG" alt="MAR pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the MAR PCB</em></p>

