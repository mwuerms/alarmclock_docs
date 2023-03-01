# Alarmclock - Docs

## aim, goal


![clock01](images/clock01.jpg)

- [ ] display present time and next alarm time
- [ ] wooden case, proportions using golden ratio a/b = 1.61803
- [ ] RTC with backup battery, temp compensation
- [ ] user interface
- [ ] alarm signals using mp3 from a usd card, [DFPlayer](https://starthardware.org/dfplayer-mini-mp3-player-fuer-arduino/)
- [ ] USB supply (micro USB)
- [ ] sunrise simulation using warm white LEDs
- [ ] optional BLE for a ble handdevice

## why

## related projects

+ [alarmclock BLE central](https://github.com/mwuerms/alarmclock_ble_central), git@github.com:mwuerms/alarmclock_ble_central.git
  + main application
  + checkout to nRF5_SDK_16.0.0_98a08e2/examples/ble_central/
+ [alarmclock BLE handdevice](https://github.com/mwuerms/alarmclock_ble_handdevice), git@github.com:mwuerms/alarmclock_ble_handdevice.git
  + hand device to determine if sleeper is going to wake up soon
  + checkout to nRF5_SDK_16.0.0_98a08e2/examples/ble_peripheral/

using 

+ [nRF5 SDK v16](https://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v16.x.x/)
+ [SEGGER Embedded Studio for ARM](https://www.segger.com/downloads/embedded-studio) v7.10a

## structure
