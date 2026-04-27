# Your Project Name
Visualiseur audio

| | |
|-|-|
|`Author` | Your full name
|`Author` | TROACA Stefan-Mihail

## Description
Le projet comprendra 5 bandes de LED qui « afficheront » le signal d'un microphone, d'où son nom de visualiseur audio. Chaque bande de LED représentera une fréquence du morceau correspondant à une partie de la mélodie (par exemple, 20-100 Hz → grosse caisse + basse, correspondra à la première bande). Imaginez quelque chose comme ceci, mais en beaucoup plus simple : https://www.youtube.com/watch?v=rnBC-tmhHQc

## Motivation
J'ai choisi ce projet car je pense qu'il combine à la fois la matière que nous avons abordée dans les précédents laboratoires concernant la manipulation des LED via des cartes, mais aussi des notions plus théoriques comme les fonctions de Fourier que nous avons étudiées au cours des deux semestres de mathématiques spécialisées.

## Architecture

@@ -26,19 +28,19 @@

| Device | Usage | Price |
|--------|--------|-------|
| ESP32 Board | Project Board | [42 RON](https://www.emag.ro/modul-cu-microcontroler-esp32-compatibil-cu-arduino-uno-conectivitate-wi-fi-bluetooth-5-12v-2-e-044/pd/DG4TNLMBM/) |
| MAX9814 Microphone Amplifier | Microphone | [25.41 RON](https://www.emag.ro/amplificator-de-microfon-cu-microfon-20-hz-20-khz-thd-scazut-mov-negru-alb-5904162800209/pd/D97HKLMBM/) |
| WS2812B 5m 30 LED/m strip | LEDs (out of which we'll use 1 meter) | [95 RON](https://www.emag.ro/banda-led-ws2812b-5m-30-led-m-ip30-5v-ai1269/pd/DQN2W5MBM/) |


### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [Arduino FFT](https://docs.arduino.cc/libraries/arduinofft/#Compatibility) | A library for implementing floating point Fast Fourier Transform calculations on the Arduino framework. | Used for interpreting input from the mic  |
| [FastLED](https://docs.arduino.cc/libraries/fastled/) | Multi-platform library for controlling dozens of different types of LEDs along with optimized math, effect, and noise functions. FastLED is a fast, efficient, easy-to-use Arduino library for programming addressable LED strips and pixels such as WS2810, WS2811, LPD8806, Neopixel and more. FastLED also provides high-level math functions that can be used for generative art and graphics. | Used for controlling the LED groups  |

## Log

@@ -59,4 +61,4 @@

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
[Link title](https://projecthub.arduino.cc/)
