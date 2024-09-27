# CrowPanel_for_ESPHome
The CrowPanel HMI RGB, All models have a touchscreen and integrated ESP32-S3 module with built-in wireless communication 2.4 GHz Wi-Fi (802.11 b/g/n) and Bluetooth 5.0.

Models
{!hardware/elecrow/crowpanel-hmi-rgb-table.html!}

The audio port and SD card are not supported by openHASP {< openhasp.version >}.

ESP32-S3 Modules have PSram and are more suitable for loading fonts, and graphics.

Video
Elecrow ESP32 Touch Screen TFT Display 5" VS 7"
<iframe title="YouTube video player" src="https://www.youtube.com/embed/i8AWqLOEmfk?rel=0&controls=1" class="embed-responsive-item" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
Cases
You can order the display either with or without matching acrylic case.

Flashing
Compile your own via platform.io and platformio_override.ini environment templates.

Also available via web installer at https://nightly.openhasp.com/

or the latest found under Github Actions, click on the latest action, and look under the Assets sections for zip files containing builds binary files.

Recommended method
Use the Nightly build website to initially flash the device.

Then update with the OTA file found under Actions, Assets on github. Or compile your own if comfortable doing that.
