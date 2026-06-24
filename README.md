# 🧯 Gas Leakage Detection System

This project demonstrates how to detect dangerous gas leaks using an MQ-2 gas sensor connected to an Arduino UNO. The system continuously monitors gas concentration and alerts users when unsafe gas levels are detected.

---

## 🧰 Hardware Components

- Arduino UNO
- MQ-2 Gas Sensor
- LCD Display (16x2)
- Buzzer
- Potentiometer
- Breadboard
- Jumper Wires

---

## 🚀 How to Run

1. Connect all components to the Arduino UNO.
2. Upload the Arduino code.
3. Power the system.
4. The LCD displays gas concentration values.
5. When gas concentration exceeds the threshold:
   - Warning message appears on the LCD.
   - Buzzer alarm is activated.
6. When gas levels return to normal:
   - LCD displays "Safe Area".
   - Buzzer turns off.

---

## 📸 Project Demonstration

### Safe State

<img src="images/safe-state.jpg" width="500">

**Output:**
- LCD displays "Safe Area"
- Gas level is shown on the screen
- Buzzer remains OFF

### Warning State

<img src="images/warning-state.jpg" width="500">

**Output:**
- LCD displays "Warning!"
- Gas level exceeds the threshold value
- Buzzer alarm turns ON

---

## ✅ Expected Output

- Continuous gas monitoring.
- Real-time gas level display on LCD.
- Audible alert when gas leakage is detected.
- Automatic return to safe mode after gas levels decrease.

---

## 🎯 Project Objectives

- Detect gas leaks automatically.
- Alert users immediately when dangerous gas levels are detected.
- Provide a low-cost safety solution.
- Improve safety in homes and workplaces.

---

## 📈 Future Improvements

- Send notifications to mobile phones.
- Add Wi-Fi monitoring capability.
- Automatic gas valve shutoff.
- Battery backup support.
- Cloud-based monitoring system.

---

## 📌 Conclusion

This project successfully demonstrates a simple and effective gas leakage detection system using Arduino UNO and the MQ-2 gas sensor. The system provides both visual and audible alerts, making it suitable for improving safety in homes, kitchens, and industrial environments.
