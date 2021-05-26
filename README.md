## Platformio adaptation of USBasp project

This is USPasp project source code with Platformio project stub added 

### Why

- I consider Makefiles way too complicated
- I want to support more targets in the future, specifically Atmega168/Atmega328, also Atmega32u4 is good candidate
- Platformio provides especially good support of multi-target development
- I need to port TPI programming method to another board, specifically with high voltage programming mode as well
- In future add one-wire protocol support
- I don't want to keep any binaries in the repo, that's just wrong

But first of all i just wanted to update my own USBasp, and I want to do it the way, I will be bale to recall next time. No magic console commands preferably.

### References

- [USBasp project](https://www.fischl.de/usbasp/)
- [How to update AVR USBasp firmware to latest version](https://blog.podkalicki.com/how-to-update-avr-usbasp-firmware-to-latest-version/)
- [AVR TPI Programming With usbasp For Dummies](http://kevincuzner.com/2020/11/08/avr-tpi-programming-with-usbasp-for-dummies/)