# robot-luxo

Rendition of Pixar's Luxo Jr. with servo mounts, an IMU, and a Raspberry Pi. Using to explore reinforcement learning. The intent is for it to actually jump and move around. Work in progress. This repo heavily under construction.

![video](/video.gif?raw=true "video")

## Assembly

### 3D printed parts

See .stl files in design/

### COTS parts

#### Mechanical parts

* Lots x [Heat-set Inserts](https://www.mcmaster.com/94180a331), M3, OD=5.6mm, L=3.8mm ([Alternative](https://www.amazon.com/gp/product/B077CJV3Z9/))
* Lots x [Bearing](https://www.mcmaster.com/7804k106), ID=5mm, OD=10mm, L=4mm ([Alternative](https://www.amazon.com/gp/product/B00UW7SFU8/))
* 1 x [Needle-Roller Thrust Bearing](https://www.mcmaster.com/5909k16)
* 2 x [Washer](https://www.mcmaster.com/5909k76)
* [Button Hex Head Drive Screw](https://www.mcmaster.com/92095A222), M5, L=40mm, partially threaded
* [Button Hex Head Drive Screw](https://www.mcmaster.com/92095A228), M5, L=50mm, partially threaded
* [Button Hex Head Drive Screw](https://www.mcmaster.com/92095a225), M5, L=60mm, partially threaded
* [Nylon-Insert Locknut](https://www.mcmaster.com/90576a104), M5
* Half of [50mm christmas ornament](https://www.amazon.com/gp/product/B01GFW8H6U/) for bulb

#### Servos

* 1 x [Savox SH-0262MG](https://www.amazon.com/gp/product/B004IZSI9S/) for the head
* 4 x [Savox SC-1251MG](https://www.amazon.com/gp/product/B004K3FAJE/) for the rest of the joints

#### Other electronics

* 1 x Raspberry Pi 3 B+
* 1 x [IMX290 USB camera](https://www.amazon.com/gp/product/B07L6TPB35/)
* 1 x [12x5050 Neopixel ring](https://www.adafruit.com/product/1643)
* 1 x [BNO055 breakout](https://www.amazon.com/Adafruit-Absolute-Orientation-Fusion-Breakout/dp/B017PEIGIG)
* 1 x [PCA9685 breakout](https://www.amazon.com/gp/product/B01G61MZF4/)
* 1 x [12V to 6V 3A DC-DC](https://www.amazon.com/gp/product/B00CGQRIFG/) for servos
* 1 x [12V to 5V 3A DC-DC](https://www.amazon.com/gp/product/B00C63TLCC/) for Pi

## Code
