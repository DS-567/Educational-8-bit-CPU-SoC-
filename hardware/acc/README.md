## Accumulator Register (ACC)

Stores the result of all ALU operations, except from compare instructions where the ALU result is discarded.

[View schematic (PDF)](ACC_schematic.pdf)

---

### Details

- Synchronous 8-bit register (74HC173 4-bit IC x2)
- Red LEDs to show register contents
- Tri-state output buffer (74HC245 IC)

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active high*)
- Accumulator in (*synchronous - active low*)
- Accumulator out (*asynchronous - active low*)
- 8-bit CPU bus

---

### Outputs

- 8-bit accumulator contents (*to CPU bus*)

---

### PCB Dimensions

*24 mm × 60.25 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/acc_pcb_top.PNG" alt="accumulator pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the Accumulator PCB</em></p>

<p align="center">
  <img src="../../images/acc_pcb_bottom.PNG" alt="accumulator pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the Accumulator PCB</em></p>

<p align="center">
  <img src="../../images/acc_pcb_design.PNG" alt="accumulator pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the Accumulator PCB</em></p>
