# Lovelace Analog Clock Card

A simple analog clock card for Home Assistant. Colors are based on your current theme.

![Example](https://raw.githubusercontent.com/Villhellm/README_images/master/clock-card.png)

| Name | Type | Requirement | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | "custom:clock-card"
| time_zone | string | **Optional** | The timezone you would like to display. If ommited your current device time will be used.

## Example Configuration

```yaml
- type: "custom:clock-card"
  time_zone: "America/Chicago"
```

[Troubleshooting](https://github.com/thomasloven/hass-config/wiki/Lovelace-Plugins)