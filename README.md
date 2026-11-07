# Home Assistant blueprints

Automation blueprints I use at home, written for current Home Assistant releases (2026.10+).

| Blueprint | What it does | Import |
|---|---|---|
| [Winter window condensation alert](winter_condensation_alert.yaml) | Once a day, warns your phone when it's cold outside and any room's humidity is high enough to fog or frost windows. Lists the rooms over the limit, worst first. | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fkapsaicin%2Fha-blueprints%2Fblob%2Fmain%2Fwinter_condensation_alert.yaml) |
| [Window-aware blind closing](window_aware_blind_close.yaml) | Closes a blind at sunset, but stops at a vent position if a window in the room is open, then finishes closing once the windows shut. Optional sunrise open. | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fkapsaicin%2Fha-blueprints%2Fblob%2Fmain%2Fwindow_aware_blind_close.yaml) |
| [Lutron Aurora (Hue-protocol firmware) light dimmer](lutron_aurora_hue_firmware.yaml) | Press to toggle, dial to dim, and optional double-press and long-press actions for a Lutron Aurora Z3-1BRL on ZHA. Needs the quirk from [zigpy/zha-device-handlers#5330](https://github.com/zigpy/zha-device-handlers/pull/5330). An optional helper keeps fast dial turns accurate. | [![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fkapsaicin%2Fha-blueprints%2Fblob%2Fmain%2Flutron_aurora_hue_firmware.yaml) |

Each blueprint's description in Home Assistant explains its inputs. Issues and pull requests are welcome.

## License

MIT
