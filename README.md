# ESPHome Samsung AC Blueprint

This repository contains a Blueprint for Home Assistant that integrates with the [esphome_samsung_ac](https://github.com/lanwin/esphome_samsung_ac) project. It allows users to monitor error codes from their Samsung AC units and send notifications when an error is detected.

## Features
- Monitors error codes from the Samsung AC unit.
- Sends notifications to selected devices when an error is detected.
- User-friendly setup through Home Assistant's Blueprint feature.
- Comprehensive error code handling: All relevant error codes for Samsung AC units are included in this Blueprint, ensuring that users receive accurate and specific error messages corresponding to their AC unit's status.
![HVAC System Error Code](https://github.com/omerfaruk-aran/esphome_samsung_ac_blueprint/blob/main/IMG_3992.jpg)

## How to Use
1. Import the Blueprint into Home Assistant.
2. Select your Samsung AC unit, error code sensor, and notification device.
3. The automation will trigger whenever an error code is detected and will send a notification with the corresponding error message.

## Installation

To add this Blueprint to your Home Assistant instance, click the button below:

[![Add Blueprint to Home Assistant](https://community-assets.home-assistant.io/original/4X/d/7/6/d7625545838a4970873f3a996172212440b7e0ae.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/omerfaruk-aran/esphome_samsung_ac_blueprint/main/blueprints/automation/esphome_samsung_ac/notification_blueprint.yaml)

## Requirements
- Home Assistant
- [esphome_samsung_ac](https://github.com/lanwin/esphome_samsung_ac) integration

## License
This project is licensed under the MIT License.
