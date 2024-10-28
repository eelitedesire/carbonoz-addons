# CARBONOZ SolarAutopilot

## Home Assistant Add-on: CARBONOZ SolarAutopilot

CARBONOZ Solar Autopilot is the dashboard of your choice for every day use of your Hybrid Solar system. We offer easy to use data logging, analytics, CO2 avoidance and powerful export features. Solar Autopilot is your first line of defence against overconsuming devices, drowning batteries and cloudy days. Manage easy to setup templates, automations and alerts by setting up event triggers. Solar Autopilot is available via Home Assistant Add-On Store so you can still benefit from the many other Home Assistant IoT integrations, features and automations available.

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

## About

SUPPORTED SOLAR HYBRID INVERTERS:

- Deye / Sunsynk
- Voltronic / Axpert / MPP Solar
- Growatt
- More to come...

## Repository Installation

Before installing the add-on, you need to add our repository to your Home Assistant instance:

1. Navigate to your Home Assistant instance
2. Go to Settings -> Add-ons
3. Click the three dots menu (⋮) in the top right corner
4. Select "Repositories"
5. Click the "Add" button (+ icon)
6. Copy and paste the following URL:
   ```
  https://github.com/eelitedesire/carbonoz-addons
   ```
7. Click "Add" to save ,check for updates and restart Home Assistant
8. The repository will now be added to your system

## Add-on Installation

After adding the repository, follow these steps to install the add-on:

1. Navigate to the Home Assistant Add-on Store
2. Find the "CARBONOZ SolarAutopilot" add-on in the list and click on it
3. Click on "Install"

## Configuration

After installation, you need to configure the add-on. Here are the available options:

```yaml
mqtt_host: 192.168.160.55
mqtt_port: 1883
mqtt_username: ""
mqtt_password: ""
battery_number: 
inverter_number: 
mqtt_topic_prefix: "solar_assistant_DEYE"
clientId: ""
clientSecret: ""
```

For additional information and documentation, please visit [https://solarautopilot.com/](https://solarautopilot.com/)

## License

MIT License

Copyright (c) 2024 CARBONOZ buyAfraction Limited

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
