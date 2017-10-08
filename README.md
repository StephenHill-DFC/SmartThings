# Device Types
This is my repository of my smartthings device handlers.

By my own admission, I'm not a Groovy Programmer so these are created primarily for my own use but are free to use in your own environments if you so wish.

## TKB TZ69E

The sole purpose of the intial device type handler that I was using (created by Soon Chye - @chancsc) was to switch the Blue LED Indictator around from the LED being on when the device was off and off when the device was on.

This was fantastic, but unfortunately by doing this the device type handler lost a key feature of the TKB TZ69E and that was Power Monitoring. This device type handler restores that with the help of merging the standard Z Wave Metering Switch and Soon Chye's device type.
