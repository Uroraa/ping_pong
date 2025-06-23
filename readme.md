🎮 Ping Pong Game on STM32F429ZIT6-DISCO (TouchGFX)
This project is a simple Ping Pong game built using TouchGFX on the STM32F429ZIT6-DISCO board (Rev D01). It features smooth graphics, button or joystick control, and optional sound output via an I2S-based MAX98357A amplifier module.

📱 Display Configuration
Resolution: 320 x 240 pixels, 16bpp (RGB565)

🎮 Controls

Joystick1:

VCC → 3.3V

GND → GND

VRx → PC3 (ADC input on STM32)

Joystick2:

VCC → 3.3V

GND → GND

VRx → PA5 (ADC input on STM32)

🔊 Audio Output (Optional)
Supports sound output using the MAX98357A I2S audio amplifier.

Wiring:

VDD	→ 5V	
GND → GND	
DIN	→ PC12
LRC	→ PA15
OUT+ →	Speaker (+)	Audio output
OUT- →	Speaker (-)	Audio output

📌 Notes
The project can be flashed directly from TouchGFX Designer using GCC and STM32CubeIDE.

STM32CubeIDE is required and can be downloaded from ST's official website.