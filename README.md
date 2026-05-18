<!-- This README is auto-deployed to https://github.com/manhoosbilli1/manhoosbilli1 -->

# Shoaib Mustafa

> Hardware engineer at [**Capistor**](https://capistor.com) · KiCad & EasyEDA Pro · ESP32 / STM32 / nRF / RP2040 / ATtiny / ATmega · USB-C, BLE, Cellular, addressable LEDs, motor drivers, isolated industrial I/O

I design custom PCBs for IoT devices, wearables, industrial controllers, and consumer prototypes — schematic capture through manufacturing-ready Gerbers. Also full-stack TypeScript/Next.js for the software side of hardware products.

📨 **shoaib.mustafa7@hotmail.com** · 🌐 [capistor.com](https://capistor.com)

---

## 🌟 Featured boards

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/dynaboard-button-controller">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/dynaboard-button-controller/main/reports/board-3d.png" alt="Dynaboard 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/dynaboard-button-controller">Dynaboard — STM32F103 button controller</a></h3>
Multi-button HID / control interface with USB-Type-C, 102 components, 590 routed tracks. Level shifting via BSS138, dedicated 5V (LD1117) and 3.3V (AMS1117) rails, 74LVC2G241 buffers, JST-PH external button daisy chain.
</td>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/tpa6110-stereo-amp-input-router">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/tpa6110-stereo-amp-input-router/main/reports/board-3d.png" alt="TPA6110 audio routing board"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/tpa6110-stereo-amp-input-router">Stereo audio amp + input router</a></h3>
TPA6110A2 stereo 150 mW headphone amp with 74AHC1G66 analog-switch source selection, TLV9001 + dual op-amp signal conditioning, BAV99 input clamps, fuse-protected supply.
</td>
</tr>

<tr>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/led-dimmer-pot-controller">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/led-dimmer-pot-controller/main/reports/board-3d.png" alt="LED dimmer 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/led-dimmer-pot-controller">High-current LED dimmer (PWM)</a></h3>
Pot-driven PWM dimmer for high-current LED loads. TLC555 oscillator + LM358 op-amps shape the gate drive into 5× parallel IRF540N N-MOSFETs. L7805 control rail. No microcontroller — fully analog.
</td>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/qx-rp2040-carrier">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/qx-rp2040-carrier/main/reports/board-3d.png" alt="QX RP2040 carrier 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/qx-rp2040-carrier">QX RP2040 carrier</a></h3>
Carrier board for the Raspberry Pi Pico (RP2040) — 12 V input, MP1584EN buck step-down, LCD/rotary-switch/button I/O, DS18B20 temperature sensor connector, dual solenoid drivers. Capistor QX product line.
</td>
</tr>

<tr>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/smart-cube-multi-pcb-flex-assembly">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/smart-cube-multi-pcb-flex-assembly/main/reports/board-3d.png" alt="Smart Cube 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/smart-cube-multi-pcb-flex-assembly">Smart Cube — multi-PCB flex assembly</a></h3>
Multi-board BLE cube device: nRF52832 MCU, BMI270 6-axis IMU, 3× 74HC4051 analog muxes (24 sensor channels), ceramic chip antenna, 32 MHz + 32.768 kHz dual crystals, FPC interconnects to sub-boards.
</td>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/atmega328-enclosure-tamper-alarm">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/atmega328-enclosure-tamper-alarm/main/reports/board-3d.png" alt="Enclosure tamper alarm 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/atmega328-enclosure-tamper-alarm">ATmega328 enclosure tamper alarm</a></h3>
Self-powered intrusion alarm. LTC4412 PowerPath seamlessly switches AC → battery backup, LTC2960 voltage supervisor trips on out-of-spec rails, LM5158 boost + TPS62933 buck, complementary N/P MOSFET load switching.
</td>
</tr>

<tr>
<td width="50%" valign="top">
<a href="https://github.com/manhoosbilli1/heater-controller-rev-a">
  <img src="https://raw.githubusercontent.com/manhoosbilli1/heater-controller-rev-a/main/reports/board-3d.png" alt="Heater controller Rev A 3D render"/>
</a>
<h3><a href="https://github.com/manhoosbilli1/heater-controller-rev-a">Battery heater controller (Rev A)</a></h3>
Battery-powered heater controller, 10 A switching via CSD17578Q3A (1.8 mΩ Rds(on)) — hierarchical schematic with dual-battery taps, USB-C charging, WS2812B RGB status, ATtiny MCU. Routed across 4 sheets.
</td>
<td width="50%" valign="top">
<h3>📑 More on capistor.com</h3>
<p>Full project catalog including cellular (AIR780E), isolated RS-485/Modbus, addressable-LED arrays, multi-input sensor matrices, ESP32-S3 portable IoT, and wearable LED necklaces.</p>
<p><a href="?tab=repositories">Browse all repositories →</a></p>
</td>
</tr>
</table>

---

## 🛠 Tech I work with

**Hardware:** KiCad 10 · EasyEDA Pro · Altium · Blender (3D renders) · JLCPCB / LCSC sourcing · Free-routing & hand-routing
**MCUs:** ESP32 (WROVER, WROOM, S3, C3) · STM32 · nRF52 · RP2040 · ATtiny · ATmega · AIR780E (cellular)
**Power:** TPS63020 buck-boost, MCP73831 LiPo charging, LM66200 / LTC4412 PowerPath, MP1584 / TPS62933 buck, LM5158 boost
**Sensors / peripherals:** LIS3DH, BMI270, DS18B20, WS2812B / SK6812 addressable LEDs, OLED displays, ceramic chip antennas
**Communication:** USB-C, BLE, Wi-Fi, RS-485 / Modbus (galvanic isolation via ISO7762/Si8642), cellular (4G Cat-1), RJ45 tethered
**Web side:** TypeScript · React · Next.js 15 · Prisma · Tailwind · Kinde Auth · Amazon SP API (for the warehouse-management app product line)

---

## 📂 Other notable repositories

- [iPhone 7 Batteryless Mod](https://github.com/manhoosbilli1/Iphone7-batteryless-MOD) — research project, 12★
- [RGB Laser Projector](https://github.com/manhoosbilli1/Laser_Projector) — STM32 + galvo mirrors
- [ESP32 Smart Watch (CapiWatch)](https://github.com/manhoosbilli1/Smart-Watch-ESP32-CapiWatch) — full smartwatch with GC9A01 LCD
- [Pet Feeder Complete](https://github.com/manhoosbilli1/pet-feeder-complete) — ESP32 IoT pet feeder, 2★
- [ESP32 Multi-Power Multi-Sensor Hub](https://github.com/manhoosbilli1/ESP32-Multi-Power-Source-Multi-Sensors)
- [Modular ESP32 Incubator](https://github.com/manhoosbilli1/Incubator_basic_esp32_modular_1_sided)
- [Teensy 24V Sensor/Controller Board](https://github.com/manhoosbilli1/Teensy_24V_INPUT_OUTPUT)

---

_💡 Need a custom PCB or a complete hardware/software product? Get in touch._
