## Accumulator Register (ACC)

Stores the result of all ALU operations, except from compare instructions where the result is discarded. 

---

### Details

- Synchronous 8-bit register (74HC173 4-bit IC x2)
- Red LEDs to show register contents
- Tri-state output buffer (74HC245 IC)

---

### Inputs

- 5V / GND
- Clock
- Clear (active high)
- Accumulator in (active low)
- Accumulator out (active low)
- 8-bit CPU bus

---

## Outputs

- 8-bit accumulator contents (to CPU bus)

---

### PCB View

**Top**

<p align="center">
  <img src="../../images/acc_pcb_top.PNG" alt="accumulator pcb top" width="600"/>
</p>

**Bottom**

<p align="center">
  <img src="../../images/acc_pcb_bottom.PNG" alt="accumulator pcb bottom" width="600"/>
</p>

**Layout**

<p align="center">
  <img src="../../images/acc_pcb_design.PNG" alt="accumulator pcb design" width="600"/>
</p>
