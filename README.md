## Sequential LED Lighting and Reverse Effect
**Description:** A project where 6 LEDs light up sequentially and then light up in reverse order, creating a looping effect.

### Hardware:
- Arduino board
- 6 LEDs
- 6 Resistors
- Jumper wires

### Software:
- Arduino IDE

### How to Use:
1. Connect 6 LEDs to digital pins `2, 3, 4, 5, 6, 7` on the Arduino.
2. Use resistors to prevent excessive current through the LEDs.
3. Upload the provided code to the Arduino board.
4. Watch the LEDs light up sequentially and then in reverse order with a delay of 50ms between each step.

---

### Code Overview:
- **Setup:** Initializes the 6 LEDs as output pins.
- **Loop:** Lights up the LEDs one by one in forward order, then reverses the sequence to create a back-and-forth lighting effect.

---

### Note:
This project is excellent for beginners looking to explore arrays and loops in Arduino programming.

