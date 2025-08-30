# Alphabet Input System using OR Gates and Seven-Segment Display  

## 📌 Overview  
This project demonstrates an **Alphabet Input System** built using only **OR gates** and a **14-segment alphanumeric display**. It allows users to input alphabets (A–Z) through manual switches, which illuminate the correct segments on the display using simple combinational logic. The entire system is hardware-based, requiring no microcontrollers or programming.  

---

## ⚡ Features  
- Displays **all 26 alphabets (A–Z)** on a 14-segment display.  
- Pure **combinational logic design** using IC 7432 OR gates.  
- No microcontroller or software required.  
- Educational tool for learning **digital logic** and **seven-segment displays**.  
- Clear and visible outputs with reliable operation.  

---

## 🛠 Components Required  
- 14-Segment Alphanumeric Display × 2  
- IC 7432 (2-input OR Gate) × 2  
- Toggle Switches × 26  
- Breadboards × 2  
- Resistors and Jumper Wires  
- Regulated 5V Power Supply  

---

## 🔎 Working Principle  
- Each alphabet is mapped to a **specific combination of segments**.  
- When a switch is pressed, it outputs a **HIGH (1)** signal.  
- The signal passes through **OR gates**, activating the required segments.  
- Shared segments (used by multiple letters) are efficiently handled by OR logic.  
- Example: Pressing **A** → segments **a, b, c, e, f, g** light up.  

---

## 📐 Implementation Steps  
1. Identify segment mapping for all 26 alphabets (A–Z).  
2. Assign each toggle switch to a letter.  
3. Route signals from switches through OR gates to control segments.  
4. Connect OR gate outputs to the 14-segment display.  
5. Power the system with **5V DC**.  
6. Test switches to verify correct alphabet display.  

---

## 🚀 Future Enhancements  
- Multi-character input system (for words and messages).  
- Integration with **FPGAs or microcontrollers** for advanced features.  
- Scrolling text or keyboard-matrix based inputs.  
- Wireless or voice-controlled input methods.  

---

## 🎯 Learning Outcomes  
- Understanding of **combinational logic circuits**.  
- Practical use of **seven-segment displays**.  
- Designing functional systems without microcontrollers.  
- Hands-on experience in digital hardware prototyping.  

---

## 📚 References  
- M. Morris Mano – *Digital Design with an Introduction to Verilog HDL, VHDL, and SystemVerilog* (6th Edition)  
- Thomas L. Floyd – *Digital Fundamentals* (11th Edition)  

---

## ✨ Contributors  
- Nishant Kumar Karn  
- Nikhil Singh Dhruwe  
- Anuradha Kumari  
- Saswat Kumar Panigrahi  
- Pranjal Pal  
- MS Payal  

🎓 *National Institute of Technology, Agartala*  

---
