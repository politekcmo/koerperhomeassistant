# koerperhomeassistant
HASSIO Home Assistant at Koerper Home

Hassio for:
Ease of install on Raspi3  -  Add-Ons  -  Snapshots


## What HASSIO Runs:

The official add-ons:
* [Let's Encrypt](https://letsencrypt.org) : Free, Open, Automated SSL/TLS Certificate Authority Service
* Node-RED
* Duck DNS
* Git Pull - This is a tricky one - a backup/snapshot is /VERY/ necessary because this add-on likes to nuke the config directory and a git commit is not possible as of yet from HASSIO...
* Configurator
* Samba Share

unofficial add-on:
* [Homebridge](https://github.com/home-assistant/homebridge-homeassistant) : Bridges HomeAssistant's components to Apple HomeKit
* SSH

EVENTUALLY 
* Pi Hole
* Home Assistant Control Panel
