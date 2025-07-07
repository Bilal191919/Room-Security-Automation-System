# 🔐 Final Room Security & Automation System

This project simulates a **Room Security and Automation System** using **NI Multisim**. It validates a user-entered binary password using logic gates and flip-flops. Upon successful authentication, the system unlocks the room and activates connected devices (like lights or fans), all in a simulated environment.

## 🎯 Objective

To build a logic circuit that:
- Verifies a digital password using combinational logic.
- Unlocks a simulated room on correct entry.
- Activates devices automatically when access is granted.

## 🧰 Components Used

| Component                  | Quantity | Purpose                                                |
|---------------------------|----------|--------------------------------------------------------|
| SPST Switches             | 10       | Simulate user and stored password bits                 |
| XNOR Gates                | 4        | Compare password input with stored values              |
| 5-input AND Gate          | 1        | Check for full password match                          |
| 2-input AND Gates         | 6        | Control logic for outputs                              |
| NOT Gates                 | 3        | Invert signals for proper control                      |
| JK Flip-Flops             | 2        | Store system state (locked/unlocked)                   |
| Clock Generator (2Hz)     | 1        | Provide timing for state toggling                      |
| HEX to 7-Segment Decoder  | 1        | Convert binary to display format                       |
| 7-Segment Display         | 1        | Display system status                                  |
| Output Loads (LEDs, etc.)| 5        | Represent activated devices (fans, alarms, etc.)       |

## ⚙️ Working Principle

- **Password Entry:** Simulated using SPST switches.
- **Password Matching:** XNOR gates check each input bit with stored bits.
- **Validation Logic:** AND gates determine if all bits match.
- **State Control:** Flip-flops toggle system between locked and unlocked based on the match.
- **Display Output:** 7-segment display shows system status.
- **Device Activation:** Connected outputs activate only when system is unlocked.

## 💡 Features

- Fully digital simulation in Multisim.
- Combines combinational and sequential logic.
- Real-time state display via 7-segment output.
- Simple yet expandable design.

## 🖥️ How to Use

1. Open the project file in **NI Multisim**.
2. Toggle the password input switches.
3. Observe system behavior (unlocking + activation of outputs).
4. Watch the 7-segment display change status.

## 📸 Screenshot

![IMG_20250622_192054 1](https://github.com/user-attachments/assets/adc97e49-bd14-4213-a07f-f5e76374cdc7)


## 🧠 Learning Outcome

Through this project, I learned:
- The use of combinational and sequential logic components.
- How flip-flops maintain system state.
- Design of password-based access systems.
- Circuit debugging and waveform analysis in Multisim.

---

## 🔗 Connect with Me

Want to collaborate or learn more?  
📧 Email: your.email@example.com  
🌐 GitHub: [https://github.com/Bilal191919]

