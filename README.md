# BounceStop
Debounce interface with gadgeteer connections
Allows for hardware debouncing of signals with significant noise prevention.  Good for interfacing switches and other "slow" devices since the device has a built in delay/debounce.

Early prototype.  Not for production. Gadgeteer pinouts are not correct on 0.1 and 0.2 versions.  Will be corrected shortly.


0.2 version adds the pins for _CH and _EN which will allow a one shot trigger event when any pin is triggered...then you toggle to reset.  This allows the board to also be used as an 8:1 Interrupt expander or other functions
