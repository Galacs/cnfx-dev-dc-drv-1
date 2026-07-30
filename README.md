# CNFX Dev DC Driver 1

Dual 5V 1.5A DC motor driver for the cnfx series

## IC List

- STM32F103C8T6 (Main MCU)
- HT7533 (MCU 3v3 LDO)
- SN65HVD230DR (CAN transceiver)
- WS2812B (RGB addressable led)
- TPS259472 (+5V input efuse)
- DRV8837 (Integrated H-Bridge)

## Top preview

<img width="895" height="897" alt="image" src="https://github.com/user-attachments/assets/fd454d6e-0b61-4745-85b7-09c4aeea2078" />

## Preview 3d render

<img width="949" height="857" alt="image" src="https://github.com/user-attachments/assets/f997284e-3064-4cf8-a75c-4457a0362abb" />

## Pin definitions

```c

#define CAN_TX_PIN PA12
#define CAN_RX_PIN PA11
#define CAN_STATUS_PIN PA15

#define RGB_PIN PB13
#define ILM_PIN PB0
#define BTN_PIN PB12

#define SEL_0_PIN PB5
#define SEL_1_PIN PB6
#define SEL_2_PIN PB7

#define DC_1_SLEEP PA5
#define DC_1_IN1 PA6
#define DC_1_IN2 PA7

#define DC_1_SLEEP PA0
#define DC_1_IN1 PA1
#define DC_1_IN2 PA2
```
