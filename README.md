#PocketPlayer

An open-source, iPod-style MP3 player built from scratch to learn embedded systems, audio decoding, and hardware design

Project V1: Open-source iPod-style MP3 player

Then answer these exact questions:

1️⃣ What will it play?

✔ MP3


2️⃣ Where is music stored?

✔ MicroSD card

3️⃣ How do you control it?

✔ Physical buttons

Play / Pause

Next

Previous

Menu (optional)

(No scroll wheel yet)

4️⃣ How do you see info?

✔ Small screen

Track name

Play/Pause icon

Time elapsed

5️⃣ How do you listen?

✔ Wired headphones (3.5mm)

6️⃣ Power

✔ Rechargeable battery
✔ USB-C charging

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

PARTS

MCU - ESP32

Audio output: I2S DAC → 3.5mm headphone jack

MicroSD Card Module

	SPI interface

	Uses FAT32

Display - ST7789 SPI TFT

	Size: 1.54”

	Resolution: 240 × 240

	Interface: SPI (NOT parallel, NOT HDMI)

Battery - Power: LiPo + TP4056 (USB-C)

Controls - 4 tactile buttons

	Play / Pause

	Next

	Previous

	Menu / Back

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

TinkerCad Link

https://www.tinkercad.com/things/fyp4QuNLCbY/edit?returnTo=%2Fdashboard
