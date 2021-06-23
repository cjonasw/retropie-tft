# RetroPie on 2.8" TFT Screen

![Pixel Raspberry](/theme-extras/raspberry.png "Pixel Raspberry")

I have the Adafruit 2.8" TFT LCD (320x240 / 240x320).
I run these scripts on a Retropie image to switch between HDMI and the TFT display.

I am only using [fbcb](https://learn.adafruit.com/running-opengl-based-games-and-emulators-on-adafruit-pitft-displays/pitft-setup).

Raspbian comes with the driver for this product (`pitft28-resistive`).

```
git clone https://github.com/cjonasw/retropie-tft.git
chmod -R 755 retropie-tft
cd retropie-tft/
```

## 2.8"

```
sudo ./show-28TFT
sudo reboot
```
## HDMI (Default RetroPie settings)

```
sudo ./show-HDMI-defaults
sudo reboot
```
## HDMI

This is the default RetroPie settings with overscan disabled (to remove the black border).

```
sudo ./show-HDMI
sudo reboot
```