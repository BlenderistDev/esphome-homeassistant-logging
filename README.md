# Home assistant shell script to log esphome devices to files.

Saving logs for home assistant esphome addon. Saves all your ESP logs to /config/esphome/logs. 

Logs will be saved to a file untill addon esphome restarts.

# Install
```
git clone https://github.com/BlenderistDev/esphome-homeassistant-logging.git
cd esphome-homeassistant-logging
chmod +x esplog
```

## Launch

```
./esplog
```

## Launch for specific devices

```
./esplog mydevice1.yaml mydevice2.yaml
```
