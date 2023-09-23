Xiaomi Button Multi-Action Blueprint for Home Assistant
Overview
This blueprint allows you to create automations in Home Assistant that react to single, double, or hold actions of a Xiaomi button. Specifically, it toggles associated input_boolean entities based on the last_action attribute of the Xiaomi button.

Features
Toggle an input_boolean when a Xiaomi button is single-pressed.
Toggle a different input_boolean when the button is double-pressed.
Toggle yet another input_boolean when the button is held.
Installation
Via Home Assistant UI
Go to Home Assistant Dashboard > Configuration > Blueprints.
Click on "Import Blueprint" and paste the GitHub URL for this blueprint.
Click "Preview Blueprint" and then "Import Blueprint".
Via File System
Clone this repository or download the YAML file for the blueprint.
Move the downloaded YAML file to your config/blueprints/automation/ directory. Create the directory if it doesn't exist.
Restart Home Assistant.
Usage
After installing the blueprint, go to Configuration > Automations.
Click on the "Add Automation" button.
Select the "Xiaomi Button Multi-Action" blueprint under "Blueprints".
Configure the automation by selecting the Xiaomi button entity and the input_boolean entities you want to toggle.
Save the automation.
Contributing
Feel free to contribute to this blueprint by creating a pull request or opening an issue.

License
This blueprint is under the MIT License. See the LICENSE file for more details.
