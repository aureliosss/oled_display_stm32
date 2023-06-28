# Oled Display and microcontriller STM32   🔧 🖥️ 📺 💡 

![image](https://github.com/aureliosss/oled_display_stm32/assets/84960010/26ded5c7-daad-4239-ab3a-eef9150ba03d)

![test](https://github.com/aureliosss/oled_display_stm32/assets/84960010/5f23773d-769b-447f-a82d-20178ee85293)  

STM32 Development with NUCLEO-L433RC-P and OLED Graphic Display

# Description
This project utilizes the NUCLEO-L433RC-P development board along with an OLED graphic display module (0.96" 128x64 pixels, white) connected via the I2C communication protocol. The project is developed using STM32CubeIDE, an integrated development environment for STM32 microcontrollers.

The OLED display is controlled using the SSD1306 driver, implemented as an Arduino-style C/C++ library. Communication with the display is established through the I2C serial communication interface.

The main objective of this project is to demonstrate the capabilities of the STM32 microcontroller platform and showcase the usage of an OLED graphic display for visual output. The provided code and circuit configuration allow for easy integration and customization based on specific project requirements.

# Features
Integration of NUCLEO-L433RC-P development board and OLED graphic display
Utilization of STM32CubeIDE for firmware development
Communication with the display module using the I2C protocol
SSD1306 driver implementation with Arduino-style C/C++ library
# Getting Started
To get started with this project, follow the steps below:

1. Connect the NUCLEO-L433RC-P development board to your computer.
2. Connect the OLED graphic display module to the appropriate pins on the development board using the I2C interface.
3. Download and install STM32CubeIDE from the official website.
4. Open the project in STM32CubeIDE.
5. Build and flash the firmware onto the NUCLEO-L433RC-P development board.
6. Verify the connection between the microcontroller and the OLED display.
7. Run the project and observe the output on the display.
Dependencies
*NUCLEO-L433RC-P development board
*OLED Graphic Display (0.96" 128x64 pixels, white) with SSD1306 driver
*STM32CubeIDE
*Arduino-style C/C++ library for SSD1306 driver.
