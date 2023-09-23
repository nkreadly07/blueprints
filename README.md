# Aqara/Xiaomi Button Multi-Action Blueprint for Home Assistant

## Overview

This blueprint allows you to create automations in Home Assistant that react to single, double, or hold actions of a Xiaomi button. Specifically, it toggles associated `input_boolean` entities based on the `last_action` attribute of the Xiaomi button.

This is for Aqara Motion Sensor P1

## Features

- Toggle an `input_boolean` when a Xiaomi button is single-pressed.
- Toggle a different `input_boolean` when the button is double-pressed.
- Toggle yet another `input_boolean` when the button is held.

## Known Issues

### Last Action Attribute

If the `last_action` attribute doesn't change (for example, from "single" to something else), the state of the binary_sensor won't change. Consequently, the trigger for the automation won't fire again. This is a limitation that we are aware of, and we welcome any ideas or contributions to improve this behavior.

## Installation

### Via Home Assistant UI

1. Go to Home Assistant Dashboard > Configuration > Blueprints.
2. Click on "Import Blueprint" and paste the GitHub URL for this blueprint.
3. Click "Preview Blueprint" and then "Import Blueprint".

### Via File System

1. Clone this repository or download the YAML file for the blueprint.
2. Move the downloaded YAML file to your `config/blueprints/automation/` directory. Create the directory if it doesn't exist.
3. Restart Home Assistant.

## Usage

1. After installing the blueprint, go to Configuration > Automations.
2. Click on the "Add Automation" button.
3. Select the "Xiaomi Button Multi-Action" blueprint under "Blueprints".
4. Configure the automation by selecting the Xiaomi button entity and the `input_boolean` entities you want to toggle.
5. Save the automation.

## Contributing

Feel free to contribute to this blueprint by creating a pull request or opening an issue.

## License

This blueprint is under the MIT License. See the LICENSE file for more details.


## License

This blueprint is under the MIT License. See the LICENSE file for more details.

