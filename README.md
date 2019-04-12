# LimeScan Device
This repository is for running LimeScan on a raspberry pi. It uses [limetools](https://github.com/myriadrf/lime-tools) and [limesuite](https://github.com/myriadrf/LimeSuite).

## Getting Started
Currently it requires running with sudo due to lime-tools, so it can be ran once with:
```
sudo python3 limescan-device.py
```

If you want to run continious scans then something like this:
```
watch -n0 sudo python3 limescan-device.py
```