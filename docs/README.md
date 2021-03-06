# smartthings
## Device type handlers
### [cast-web](https://raw.githubusercontent.com/vervallsweg/smartthings/master/devicetypes/vervallsweg/cast-web.src/cast-web.groovy "cast-web")
Device handler for all Google Cast enabled devices (audio/video/groups). Works with as a music player with the Speaker Companion App, WebCoRE and many more. Due to limitations of the Samsung Smartthings platform it constantly requires a small HTTP API on your local network.
[Installation Guide](https://vervallsweg.github.io/smartthings/cast-web-installation-guide "Installation Guide")
-> [Changelog](https://github.com/vervallsweg/smartthings/blob/master/devicetypes/vervallsweg/cast-web.src/README.md "Changelog")
## Smartapps
### [cast-web-service-manager](https://raw.githubusercontent.com/vervallsweg/smartthings/master/smartapps/vervallsweg/cast-web-service-manager.src/cast-web-service-manager.groovy "cast-web-service-manager")
Service manager for the cast-web device handler. It let's you discover and add new devices, configure them, takes care of address changes and much more.
-> [Changelog](https://github.com/vervallsweg/smartthings/blob/master/smartapps/vervallsweg/cast-web-service-manager.src/README.md "Changelog")
### [cast-web-group-sync](https://raw.githubusercontent.com/vervallsweg/smartthings/master/smartapps/vervallsweg/cast-web-group-sync.src/cast-web-group-sync.groovy "cast-web-group-sync")
After you added your audio groups and there part of SmartThings, this app makes them work properly. Install it, select the audio group, its members (not the group itself), done! It now syncs the meta data between the group members and let's you level the group's volume, by taping the little play button next to the installed smartapp.
-> [Changelog](https://github.com/vervallsweg/smartthings/blob/master/smartapps/vervallsweg/cast-web-group-sync.src/README.md "Changelog")
## Tools
### [cast-web-preset-generator](https://vervallsweg.github.io/smartthings/cast-web-preset-generator/preset-generator.html "cast-web-preset-generator")
The cast-web dth let's you play presets by tapping the corresponding button in the dth or using a smartapp, routine, CoRE. The presets are saved in a JSON formated preset object and cannot be edited within Smartthings. Use this webapp to generate and edit your presets and save them to your cast-web device.