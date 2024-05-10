This is the repository for 'Roll Over Beethoven', a foldable piano/keyboard.

**Contained herein:**
- MPR121 drivers (for capacitive touch detection) in Core/Src/mpr121.c
- Graphics display drivers (Adafruit 320 x 480 TFT Graphics Display Breakout Board drivers) in Core/Src/display.c
- Sound generation/synthesis code (for different harmonics) in Core/Src/audio.c
- Our tutorial for 'Hail to the Victors' across Core/Src/main.c and in Core/Src/audio.c
- Code to communicate with the pressure readings on gloves in Core/Src/pressure.c

**What our Piano looks like:**

![image](https://github.com/adviyer/cloth-piano/assets/70266102/f05b19bc-523b-4fa9-88c7-a6b47dae06ca)

Video: [https://twitter.com/i/status/1783915991854157952](https://twitter.com/advaitsi/status/1783915991854157952/video/4)

**What we used to build it:**
- STM32 Nucleo L4R5ZI-P microcontroller (1)
- MPR121 Capacitive Sensors (4)
- Adafruit 320 x 480 TFT Graphics Display Breakout (1)
- Sparkfun Audio Sound Breakout Board (1)
- Conductive Cloth (48 keys)
- Adafruit Massive Arcade Button with LED (1)
- XBees (2)
- Force Sensitive Resistors (5)
