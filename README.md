# 🔤 Alphabet Input System using OR Gates and Seven-Segment Display

---

# 📌 Overview

This project demonstrates an **Alphabet Input System** built entirely using **OR gates** and a **14-segment alphanumeric display**.

The system allows users to input alphabets (**A–Z**) through manual toggle switches, which illuminate the corresponding segments on the display using simple **combinational logic circuits**.

The project is fully hardware-based and does not require any microcontroller, programming, or embedded software, making it an excellent educational project for understanding digital electronics fundamentals.

---

# ⚡ Features

* Displays all **26 alphabets (A–Z)** using a 14-segment display
* Pure **combinational logic design** using IC 7432 OR gates
* No microcontroller or coding required
* Demonstrates practical implementation of digital logic circuits
* Reliable and clearly visible output display
* Educational tool for learning display interfacing and logic design

---

# 🛠 Components Required

| Component                       | Quantity    |
| ------------------------------- | ----------- |
| 14-Segment Alphanumeric Display | 2           |
| IC 7432 (2-input OR Gate)       | 2           |
| Toggle Switches                 | 26          |
| Breadboards                     | 2           |
| Resistors                       | As required |
| Jumper Wires                    | As required |
| Regulated 5V Power Supply       | 1           |

---

# 🔎 Working Principle

* Each alphabet is assigned a unique combination of display segments.
* When a toggle switch is pressed, it generates a **HIGH (1)** logic signal.
* The signal passes through the **OR gate network**, activating the required display segments.
* Shared segments used by multiple alphabets are efficiently handled using OR logic.
* Example:

  * Pressing **A** activates segments:

    **a, b, c, e, f, g**

This creates the visual representation of the selected alphabet on the display.

---

# 📐 Implementation Steps

1. Identify segment combinations for all alphabets (A–Z)
2. Assign one toggle switch to each alphabet
3. Connect switch outputs through OR gates
4. Route OR gate outputs to the 14-segment display
5. Provide regulated **5V DC power supply**
6. Test all switches for correct alphabet display

---

# 🎥 Project Demo

[▶ Click Here to Watch the Demo](https://drive.google.com/file/d/1XRofJHZc3qJxnnURpC2ViybCfp4XUh8S/view?usp=sharing)

---

# 🚀 Future Enhancements

* Multi-character input system for words and messages
* Integration with microcontrollers or FPGAs
* Scrolling text display system
* Keyboard matrix-based alphabet input
* Wireless or voice-controlled input methods

---

# 🎯 Learning Outcomes

* Understanding of combinational logic circuits
* Practical implementation of OR gate logic
* Hands-on experience with 14-segment displays
* Hardware-based system design without microcontrollers
* Circuit prototyping and debugging skills

---

# 📚 References

1. M. Morris Mano — *Digital Design with an Introduction to Verilog HDL, VHDL, and SystemVerilog* (6th Edition)

2. Thomas L. Floyd — *Digital Fundamentals* (11th Edition)

---

# ✨ Contributors

* Nishant Kumar Karn
* Nikhil Singh Dhruwe
* Anuradha Kumari
* Saswat Kumar Panigrahi
* Pranjal Pal
* MS Payal

---

# 🏫 Affiliation

🎓 **National Institute of Technology Agartala**

---

# 🌟 Conclusion

This project successfully demonstrates how combinational logic circuits can be used to create an alphabet display system without relying on programmable devices. It provides strong foundational knowledge in digital electronics, display interfacing, and hardware logic design.
