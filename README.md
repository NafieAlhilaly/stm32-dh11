Interfacing with DHT11 temperature and humidity senson using stm32 and libopencm3.

## Hardware
- Relay Module
- Motion sensor
- Photoresistor

## Run
To build the project, navigate to the firmware folder and run
```console

make

```

to compile the project and produce the image.

then run
```console

make burn

```
to burn the image to the Microcontroller flash memory

use `screen.sh` to monitor uart output
```terminal
./screen.sh

data -> 25
data -> 32
```