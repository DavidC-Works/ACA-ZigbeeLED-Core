# ACA-ZigbeeLED-Core

### Overview
This project establishes a foundation for working with the ESP32-C6 using ESP-IDF.  
It begins with a single-board LED + button toggle (GPIO fundamentals) and expands to BLE-based LED synchronization between two boards.

### Objectives
- Learn GPIO input/output handling and debouncing.
- Implement FreeRTOS task loops for stable button reading.
- Add BLE GATT communication for real-time LED sync.

### Milestones
- **v0.1** – LED + Button toggle (standalone)
- **v0.2** – BLE server/client sync between two boards

### Build & Flash
```bash
idf.py set-target esp32c6
idf.py build
idf.py -p <PORT> flash monitor
