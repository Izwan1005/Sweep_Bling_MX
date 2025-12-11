# Sweep Bling by @zwn.a

## 🌀 Description

**Wireless Ferris Sweep** with a twist. Each half of the case is designed to accommodate **two 401230 LiPo batteries (150mAh)** — one beneath the MCU and another under the palm rest.

## 🎮 Supported Controllers

- **RP2040**
- **Supermini NRF52840**
- **Nice!Nano**

## 🔧 Firmware Options

I wrote two firmwares for it:

- **ZMK**  
  Optimized for wireless controllers like **Supermini** and **Nice!Nano**.

- **QMK-VIAL**  
  Tailored for **RP2040** setups, offering advanced customization via VIAL interface.

  ## 🔧 Compile Error

If you are experiencing firmware compiling error, please check build.yml and west.yml regarding the firmware version:

- **This depends on the ZMK feature that you are planning to use**  
  Please see here (https://zmk.dev/blog/2025/06/20/pinned-zmk)
  
  <img width="412" height="339" alt="image" src="https://github.com/user-attachments/assets/5ebe257e-d195-43ba-a9a6-0d13783756be" />

  <img width="499" height="250" alt="image" src="https://github.com/user-attachments/assets/fcf589de-c5e8-4347-98e0-52de756a66ad" />


