# ESPavrisp
## using a Heltec "WiFi LoRa 32 v2" as a avrisp compatible programmer 

the code is liberated from here https://github.com/nathanjel/espavrisp and adjusted to the heltec board.

this worked fine to reprogram a "LoRa32u4 v1.3" with avrdude.

see code for pinout used, all pin defines should have a PIN in their name.

if the display part refuses to build (module version/api conflicts), anything display.* can be removed without impact.
(besides disabling the display)

any comments in the code can be about 2-3 generations of overhaul misleading.

### when in doubt, read the code, not the comments.
