# ⚡ WireSystemLang

> **WireSystemLang** is a programming language similar to C++ and uses the same compiler. WireSystem is designed for beginners in C++ programming. It allows for easier programming for microcontrollers like the ESP-32 or Arduino, and all devices that support C++ coding.

---

## 🚀 Concept & Philosophy

**WireSystemLang** acts as an accessible entry point to modern hardware programming. Because it maps directly to standard C++ syntax and utilizes native C++ compilers (like GCC/MinGW), it provides an educational runway: you learn the core logic of embedded systems programming today, and transition smoothly to raw C++ tomorrow.

### Why WireSystemLang?
* 🔧 **Zero Performance Loss:** Since it shares the exact same compiler backend as C++, your code runs at maximum native speed on hardware.
* 🎓 **Tailored for Beginners:** Cuts down verbose syntax into clear, logical structures.
* 🎛️ **Cross-Platform Microcontroller Support:** Developed with architectures like the ESP32 (e.g., ESP32-S3) and Arduino Uno in mind.

---

## 📝 Syntax Structure

Here is a look at how a basic macro script or hardware automation flow is structured in `WireSystemLang`:

```text
// Standard WireSystem Setup & Execution Loop
PIN 2 = INPUT_PULLUP

LOOP {
    IF CLICK(2) {
        SEND_HOTKEY("CTRL+SHIFT+M")
        DELAY 1000  // Built-in non-blocking delay helper
    }
}
