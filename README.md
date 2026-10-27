# ha-bot

ESPHome configuration for using a Spotpear Puck as a voice assistant for Home Assistant.

The Puck uses the same firmware and pin layout as the Spotpear Ball v2. This
configuration follows the latest [Ball v2 configuration](https://github.com/RealDeco/xiaozhi-esphome/blob/main/devices/Spotpear%20Balls/Ball_v2.yaml)
and keeps the Puck-specific display orientation and personal settings.

## Secrets

Define these keys in the ESPHome `secrets.yaml` file used by your installation:

```yaml
wifi_ssid: "your Wi-Fi network"
wifi_password: "your Wi-Fi password"
wifi_ap_password: "a password of at least 8 characters"
```

Do not commit `secrets.yaml` or real credentials to this repository.
