## Arithmetic and Logic Unit (ALU)

Stores the result of all ALU operations, except from compare instructions where the ALU result is discarded. (UPDATE)

[View schematic (PDF)](ALU_schematic.pdf)

---

### Details

- Synchronous 8-bit register (74HC173 4-bit IC x2)  (UPDATE)
- Red LEDs to show register contents             (UPDATE)

---

### Inputs

- 5V / GND
- 8-bit ALU register (*RALU*)
- 8-bit CPU bus
- 3-bit ALU operation select
- ALU function select
- Carry flag from FLAG register (*to preserve during certain operations*)

---

### Outputs

- 8-bit ALU contents (*to accumulator register - ACC*)
- 4 flags (*to FLAG register*)

---

### PCB Spec

- *Blue*
- *4 layer*
- *166.25 mm × 56.5 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/alu_pcb_top.PNG" alt="ALU pcb top" width="600"/>
</p>
<p align="center"><em>Top view of the ALU PCB</em></p>

<p align="center">
  <img src="../../images/alu_pcb_bottom.PNG" alt="ALU pcb bottom" width="600"/>
</p>
<p align="center"><em>Bottom view of the ALU PCB</em></p>

<p align="center">
  <img src="../../images/alu_pcb_design.PNG" alt="ALU pcb design" width="600"/>
</p>
<p align="center"><em>Layout view of the ALU PCB</em></p>

