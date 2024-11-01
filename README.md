# Sonoff S31 Smart Plug with Energy Monitoring, 15A WiFi

For hardware used, see here: <br /> https://itead.cc/product/sonoff-s31/ <br />

Or here: <br /> https://sonoff.tech/product/smart-plugs/s31-s31lite/ <br />

Or as 4-pack here: <br /> https://www.amazon.com/SONOFF-Monitoring-Compatible-4PCS-TPB/dp/B0C9ZBCJMC/147-9461940-1179210 <br />

Test hooks used to flash (to avoid soldering): <br /> https://www.amazon.com/dp/B0BJ627S1X <br />

USB to TTL UART Converter used (DSD TECH SH-U09C5 USB to TTL UART Converter Cable with FTDI Chip Support 5V 3.3V 2.5V 1.8V TTL), please remember to set to 3.3V: <br />  https://www.amazon.com/dp/B07WX2DSVB <br />

For detailled flash instructions (flashing starts at timestamp 13:53): <br /> https://youtu.be/6aeUWPLgaqY?si=nI2Jqq2ugKuAgVmX <br />

If you have issues flashing from the browser, or simply hate using vulnerable browser with too open APIs and too much telemetry (read, spying) like Chrome and Edge you can use "Manual download" in ESPHome to get the binary, and then flash it using Tasmotizer. This got me moving forward on a couple that simply would not flash from the WebGUI: https://github.com/tasmota/tasmotizer

Schematic and docs: <br /> https://github.com/techdregs/Sonoff-S31-Teardown <br />

This is run with Home-assistant: <br /> https://www.home-assistant.io/ <br />

and the ESPHome integration: <br /> https://esphome.io/ <br />

Initial config taken from here: <br /> https://github.com/techdregs/Sonoff-S31-Teardown/blob/main/YAML/S31.YAML <br />
