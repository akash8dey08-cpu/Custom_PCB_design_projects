# Embedded Hardware & PCB Design Portfolio (KiCad)

A collection of custom 2-layer printed circuit boards designed in KiCad for power regulation, STM32 sensor telemetry, and analog signal conditioning.

## Projects Index

| Project | Key ICs / Components | Layers | Directory |
| :--- | :--- | :--- | :--- |
| **1. Dual-Input Buck + LDO Power Supply** | `LM2596T-ADJ`, `MIC29152WT`, `1N5822`, USB-C + Barrel Jack | 2-Layer | [`/01-Dual-Input-Power-Supply`](./01-Dual-Input-Power-Supply) |
| **2. STM32 Blackpill Sensor Carrier** | `AMS1117-3.3`, `MPU6050`, `BME280`, `HC-SR04`, `DHT22` | 2-Layer | [`/02-Blackpill-Sensor-Carrier`](./02-Blackpill-Sensor-Carrier) |
| **3. LDR07 Light Sensor Breakout** | `LDR07`, `10k` Divider, 3-Pin Header | 2-Layer | [`/03-LDR07-Light-Sensor-Breakout`](./03-LDR07-Light-Sensor-Breakout) |

---

## Layout Previews

### 1. Dual-Input Buck & LDO Power Distribution Board
![Power Supply PCB](./01-Dual-Input-Power-Supply/docs/power_supply_layout.png)

### 2. STM32 Blackpill Multi-Sensor Carrier Board
![Blackpill Carrier PCB](./02-Blackpill-Sensor-Carrier/docs/blackpill_carrier_layout.png)

### 3. LDR07 Analog Light Sensor Breakout
![LDR Breakout PCB](./03-LDR07-Light-Sensor-Breakout/docs/ldr_module_layout.png)
