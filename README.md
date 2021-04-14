# WAREMA - An home assistant plugin to add and control window awning / ZIP blinds


## Description
This platform plugin allows you to control window awnings / ZIP blinds from the manufacturer Warema (Warema.com). 
The plugin controls your components via the Warema API.

## Requirements
You need to have Warema "WMS WebControl pro" installed to your network and have enabled the cloud connect.
"WMS WebControl pro" is a hardware for integrating a mobile end device into the WMS as an additional transmitter. It is operated by app or web browser. The system is operating at home directly via the WLAN network or with a worldwide access via optional cloud connection.

Warema window awnings: https://warema.com
<img src="./assets/ZIP-Example.jpg" alt="Warema window awning" width="75%">

WMS WebControl pro: https://www.warema.com/en/control-systems/radio-systems/wms-webcontrol-pro.php
![WMS WebControl pro](./assets/WMS.png)

## Installation
y

## Configuration
### Upgrading from an old component version
* Remove all configuration from Home Assistants config file `configuration.yaml`
* Upgrade the component via HACS or manually replace the files in the custom_component folder (see install manually below)
* Restart Home Assistant
* Add the component again as per below (install + configuration)

### Install with HACS (recommended)
Do you you have [HACS](https://community.home-assistant.io/t/custom-component-hacs) installed? Just search for `Warema` and install it direct from HACS. HACS will keep track of updates and you can easly upgrade Warema to the latest version.

### Install manually
Make sure you have an account on your Warema WMS WebControl pro!

Clone or copy the repository and copy the folder `homeassistant/custom_component/warema` into `<config dir>/custom_components`

## Configuration
* Restart Home Assistant
* Add and configure the component via the UI: `Configuration` > `Integrations` > search for `Warema` and follow the wizard to configure (use your Warema WMS WebControl pro credentials)
* All available components and controls should be added automatically

### Configuration flow settings
Use your "Warema WMS WebControl pro" credentials
* Username 
* Password

## Exposed entities

- `cover.warema_[YOUR-ENTITY-Name]` for each of your Warema window awnings

## Limitations
x

## To be done
1. c
