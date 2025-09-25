## Flag Register (FLAG)

Stores the result of all ALU operations, except from compare instructions where the ALU result is discarded.

[View schematic (PDF)](FLAG_schematic.pdf)

---

### Details

- Data in select (74HC157 2-1 mux IC)
- Synchronous 4-bit register (74HC173 4-bit IC)
- Green LEDs to show flags
- Tri-state output buffer (74HC125 IC)

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active high*)
- FLAG in (*synchronous - active low*)
- FLAG out (*asynchronous - active low*)
- FLAG data in select (*mux select - 0 = ALU flags, 1 = CPU bus*)
- 4-bit CPU bus
- 4-bit ALU flags

---

### Outputs

- 4-bit FLAG contents (*to CPU control unit - CU*)
- 4-bit FLAG contents (*to CPU bus*)

---

### PCB Spec

- Blue
- *4 layer*
- *24.25 mm × 60 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/flag_pcb_top.PNG" alt="FLAG pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the FLAG PCB</em></p>

<p align="center">
  <img src="../../images/flag_pcb_bottom.PNG" alt="FLAG pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the FLAG PCB</em></p>

<p align="center">
  <img src="../../images/flag_pcb_design.PNG" alt="FLAG pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the FLAG PCB</em></p>

