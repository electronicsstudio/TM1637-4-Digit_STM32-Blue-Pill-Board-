# TM1637-4-Digit_STM32-Blue-Pill-Board

🔧 TM1637 4-Digit Display Animation with STM32 (HAL-based)
This embedded C code is written for STM32 microcontrollers using the STM32 HAL library. It interfaces a TM1637 4-digit 7-segment display and provides multiple dynamic visual effects such as:

**Normal display mode (static number display),**

**Bouncing number animation (incrementing/decrementing with bounds),**

**Flashing digits (toggle on/off to create blinking),**

**Clock-style animation (segments light up in sequence).**

Modes automatically switch every 5 seconds. Display updates are handled by converting numerical values to segment patterns and pushing them via tm1637_DisplayHandle(). Timing is managed using HAL_GetTick() and simple software timers.

Useful for creating interactive, animated interfaces in DIY electronics, product demos, or learning display control with STM32.
