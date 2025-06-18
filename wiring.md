# Power
- Anker 100W USB-C PSU → USB-C to Micro USB Adapter → Raspberry Pi 3B+ (Micro USB Power Input)

# Storage
- SanDisk 32GB MicroSD → Inserted into Raspberry Pi microSD card slot

# Display
- 3.5" Touchscreen Display (GPIO version) → Mounted directly onto Raspberry Pi GPIO header (uses pins 1–26)

# Bluetooth Speaker
- Anker Soundcore 2 → Connects via Bluetooth (no physical wiring)

# Rotary Encoder (KY-040) #1
- GND  → GPIO Pin 6 (GND)
- +    → GPIO Pin 1 (3.3V)
- CLK  → GPIO Pin 11 (GPIO17)
- DT   → GPIO Pin 12 (GPIO18)
- SW   → GPIO Pin 13 (GPIO27)

# Rotary Encoder (KY-040) #2
- GND  → GPIO Pin 9 (GND)
- +    → GPIO Pin 17 (3.3V)
- CLK  → GPIO Pin 15 (GPIO22)
- DT   → GPIO Pin 16 (GPIO23)
- SW   → GPIO Pin 18 (GPIO24)

# Rotary Encoders #3–#5
- Use remaining GPIO pins:
  - CLK, DT, SW → assign to free GPIOs (e.g., GPIO25, GPIO5, GPIO6, GPIO26, GPIO19, etc.)
- Share GND and 3.3V lines using jumper wires or a breadboard

# Jumper Wires
- Used to connect KY-040 rotary encoders to Raspberry Pi GPIO header
