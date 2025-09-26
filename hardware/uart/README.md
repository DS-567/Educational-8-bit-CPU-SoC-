## UART

UART peripheral capable of transmitting and receving bytes at a fixed baud rate of 19,200. Can generate an interrupt everytime a new byte is received. The status of the UART transmit and receive circuits can be read by the CPU software.

[View schematic (PDF)](UART_schematic.pdf)

---

### Details

- 1.2288MHz oscillator
- UART data frame -> 1 start bit, 8 data bits, 1 stop bit, no parity bits
- Parallel-to-serial shift register for Tx (74HC165 IC x2)
- Serial-to-parallel shift register for Rx (74HC164 IC)
- Red LEDs to show the UART Rx byte received
- Yellow LEDs to show the UART status bits (*Tx ready, Rx byte received and Rx byte overrun*)

---

### Inputs

- 5V / GND
- Clock
- Clear (*asynchronous - active high*) - NOT USED
- Inverted clear (*asynchronous - active low*) - NOT USED
- UART enable (*asynchronous - active high*)
- 8-bit CPU bus

---

### Outputs

- 8-bit UART receive byte latch contents / UART status bits (*to CPU bus*)
- UART interrupt (*asynchronous - active high*)

---

### PCB Spec

- *Black*
- *4 layer*
- *61.75 mm × 204.25 mm*

---

### PCB Views

<p align="center">
  <img src="../../images/uart_pcb_top.PNG" alt="UART pcb top" width="800"/>
</p>
<p align="center"><em>Top view of the UART PCB</em></p>

<p align="center">
  <img src="../../images/uart_pcb_bottom.PNG" alt="UART pcb bottom" width="800"/>
</p>
<p align="center"><em>Bottom view of the UART PCB</em></p>

<p align="center">
  <img src="../../images/uart_pcb_design.PNG" alt="UART pcb design" width="800"/>
</p>
<p align="center"><em>Layout view of the UART PCB</em></p>

