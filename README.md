# Apogee SN-500-SS Net Radiometer Waggle Plugin
Waggle Sensor Plug-In for the [Apogee SN-500-SS Net Radiometer](https://www.apogeeinstruments.com/net-radiometer-support/)

The Apogee SN-500-SS Net Radiometer provides observations on incoming/outgoing shortwave radiation (385-2105 nanometers) and incoming/outgoing longwave radiation (5-30 microns).
With these observations, net radiation can be derived. 

[Waggle Sensor Information](https://github.com/waggle-sensor)

## Determine the Serial Port

Therefore, to determine which port the instrument is plugged into, PySerial offers a handy toollist to list all serial ports currnetly in use.
```bash
python -m serial.tools.list_ports
```

The default serial settings for the SDI-12 interface are:
1. Baud Rate = 
1. Data Bits = 
1. Parity = 
1. Stop Bits = 

## Data Sample
```bash
``` 

## Testing 

Similar to the [Vaisala WXT536 plugin](https://portal.sagecontinuum.org/apps/app/jrobrien/waggle-wxt536) a docker container will be setup via Makefile 

### 1) Build the Container
```bash
make build
```

### 2) Deploy the Container in Background
```bash
make deploy
```

### 3) Test the plugin
```bash
make run
