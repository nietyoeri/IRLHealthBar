# IRLHealthBar
A small home project to display my ingame health using an esp32devBoard and Leds

## Repositories

[![Minecraft Mod](https://img.shields.io/badge/Minecraft_Mod-GitHub-blue?logo=github)](https://github.com/nietyoeri/HealthBarFabricMod)
[![Arduino Code](https://img.shields.io/badge/Arduino_Code-GitHub-green?logo=github)](https://github.com/nietyoeri/HealthBarESP32Code)

## Project Overview

This project reads your Minecraft health and displays it physically using LEDs connected to an ESP32.

## Features

- Real-time health display
- Easy setup for ESP32 Dev Board
  
## Installation Guide

### 1️⃣ Flash the ESP32

1. Clone the **Arduino code repository** to your local machine.  
2. Open the project in the **Arduino IDE**.  
3. Edit the WiFi credentials to match your local network (make sure it's the same network as the device running Minecraft).  
4. Upload the sketch to your **ESP32 Dev Board**.  
5. Connect the ESP32 to a power supply.  

---

### 2️⃣ Install the Minecraft Mod

1. Clone the **Minecraft Mod repository**.  
2. Update the IP address in the mod code to match your ESP32's local IP (the ESP32 should display its IP in the Serial Monitor after boot).  
3. Build the mod using:

   `gradlew build`

4. Locate the generated `.jar` file in:

   `build/libs/`

5. Install the `.jar` file in your Minecraft `mods` folder using **Fabric**.  
   Installation guide: https://docs.fabricmc.net/players/installing-mods

### Boot up the game
your **IRLHealthBar** should now reflect your in-game health in real time.

