# ESPHome Samsung AC Blueprint

This repository contains a Blueprint for Home Assistant that integrates with the [esphome_samsung_ac](https://github.com/lanwin/esphome_samsung_ac) project. It allows users to monitor error codes from their Samsung AC units and send notifications when an error is detected.

## Features
- Monitors error codes from the Samsung AC unit.
- Sends notifications to selected devices when an error is detected.
- User-friendly setup through Home Assistant's Blueprint feature.

## How to Use
1. Import the Blueprint into Home Assistant.
2. Select your Samsung AC unit, error code sensor, and notification device.
3. The automation will trigger whenever an error code is detected and will send a notification with the corresponding error message.

## Installation

To add this Blueprint to your Home Assistant instance, click the button below:

[![Add Blueprint to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/omerfaruk-aran/esphome_samsung_ac_blueprint/main/blueprints/automation/esphome_samsung_ac/notification_blueprint.yaml)

## Requirements
- Home Assistant
- [esphome_samsung_ac](https://github.com/lanwin/esphome_samsung_ac) integration

## License
This project is licensed under the MIT License.