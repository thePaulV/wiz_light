# wiz_light
A WiZ Light integration for Home Assistant

## Install for testing 
If you want to try the integration please clone this repo to `<confdir>/custom_components/`. Run `git clone https://github.com/sbidy/wiz_light`
You also have to install the `pip install pywizlight` package.

## HA config
To enable the platform integration add 
```
light:
  - platform: wiz_light
    ip: <IP of the bulb>
```
