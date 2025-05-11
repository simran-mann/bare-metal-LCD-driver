# bare-metal-LCD-driver
A basic LCD driver developed using bare metal code to learn about the set up and how it works 
## **Project Setup**

- **LCD Screen**: ILI9341 with built-in touchscreen controller (SPI-compatible).
- **Microcontroller**: STM32F407-DISC1 board

### **Pin Connections**

#### LCD Display Pins:
- **LED**, **VCC** → 5V on STM32 board  
- **GND** → GND on STM32 board  
- **MISO** → PC2  
- **MOSI** → PB15  
- **SCK** → PB13  
- **DC** → PD9  
- **RESET** → PD10  
- **CS** → PB9  

#### Touchscreen Pins:
- **IRQ** → PA8  
- **CS** → PA15  
- **DIN** → PA7  
- **DO** → PA6  
- **CLK** → PA5  
