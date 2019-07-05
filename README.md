# Overview

DSL Stats to Influx DB is a Python service to login (via Telnet) to the Huawei Echolife HG612 Modem, retrieve connection information and post it to Influx DB. This means you have historical in-depth insight into your connection with the ability to use something such as Grafana to display the data in a visually pleasing manner.

**Note:** For this to work you will need a HG612 modem with unlocked firmware to allow Telnet access. This is done at your own risk.

## Stats collected:

* Attenuation downstream
* Attenuation upstream
* Available seconds
* Current downstream speed
* Current upstream speed
* Error seconds (downstream)
* Error seconds (upstream)
* Max downstream speed
* Max upstream speed
* Power (downstream)
* Power (upstream)
* Serious error seconds (downstream)
* Serious error seconds (upstream)
* SNR (downstream)
* SNR (upstream)
* System (modem) uptime
* Unavailable seconds (downstream)
* Unavailable seconds (upstream)

# Grafana dashboard example
The template for the below dashboard is in the ```grafana-dashboard``` subfolder
![HG612Dashboard](https://user-images.githubusercontent.com/39700437/60748553-0c766d80-9f87-11e9-82c0-6dfa754d1970.png)
