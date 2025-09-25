## Program Counter Register (PC)

Stores the address of the current instruction being executed by the CPU.

[View schematic (PDF)](PC_schematic.pdf)

---

### Details

- Synchronous 8-bit register (74HC173 4-bit IC x2)
- blue LEDs to show register contents
- Tri-state output buffer (74HC245 IC)

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active low*)
- PC in (*synchronous - active low*)
- PC increment (*synchronous - active high*)
- PC out (*asynchronous - active low*)
- 8-bit CPU bus

---

### Outputs

- 8-bit PC contents (*to CPU bus*)

---

### PCB Spec

- *2 layer*
- *24.5 mm × 56.5 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/pc_pcb_top.PNG" alt="PC pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the PC PCB</em></p>

<p align="center">
  <img src="../../images/pc_pcb_bottom.PNG" alt="PC pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the PC PCB</em></p>

<p align="center">
  <img src="../../images/pc_pcb_design.PNG" alt="PC pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the PC PCB</em></p>


