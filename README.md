# ATTiny412 Magnetic Reed Notifier

[<img src="img/IMG_6034-min.JPG" width="500"/>](img/IMG_6034-min.JPG)

A simple Magnetic Reed Notifier working exclusively on battery and solar power.

The device sends a heartbeat to the Roboguard HQ device every 15 mins.

The device has an internal switch so that the device can be learned on the Roboguard HQ.

The device has a tamper function (not used in this case).

An alarm signal is sent every 5 seconds when the reed switch is opened.

# versions

V1:
- LD1117 regulator
- IRF9540 mosfet
- BAT85 schottky

V1.3:

Uses mostly SMD parts

- LD1117 replaced with FS8860C33H regulator
- IRF9540 replaced with SI2303 p-channel mosfet
- BAT85 replaced with BAT54S schottky


# Index
- 1

# Components

Component list:
- Battery
    - 1x 3.7v, 2.59wh, 700mAh lipo (ICR 16340) battery
    - 1x battery holder
- Charge Module
    - 1x TP4056 with protection
- Diodes
    - 2x BAT85 Schottky diodes
- Mosfets
    - 1x IRF9540 P-channel
- Regulator
    - 1x LD1117 LDO 3.3v
- Microcontroller
    - 1x ATtiny412
- Capacitors
    - 1x 100nf
    - 1x 10uf
    - 2x 100uf
- Resistors
    - 1x 10k
- Transmitter
    - 1x WL102-341 3.3v 433.92 Mhz RF
- PCB Switch
    - 1x 1pin dip switch
- Magnetic Switch
    - 1x reed switch
- Case
    - 1x Sonoff case
- Wires
    - 1x red roll
    - 1x black roll

# Transmitter Details

- About the transmitter module (square shape)
    - Model: WL102-341
    - Material: Plastic Metal
    - Colour: shown as pictures
    - Size: 16x12x1mm
    - Operating frequency: 433.92 MHz
    - Mains input voltage range: 2.0V-3.6V
    - Shutdown mode current is less than 1uA
    - Transfer rate: up to 20KHz
    - Launch distance: 20-200 meters
    - External antenna: 25cm ordinary multi-core or single-core line
    - Temperature range: -45℃～85℃
    - Operating current :20-28mA
    - Output Power: 11dBm
    - Modulation mode: OOK (Amplitude Modulation)