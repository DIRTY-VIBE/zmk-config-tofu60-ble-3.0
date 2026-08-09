# zmk-config-tofu60-ble-3.0

## Leader key

The Leader key uses the external
[`urob/zmk-leader-key`](https://github.com/urob/zmk-leader-key) module.

Hold the base-layer Space key to open the `space` layer, then tap `B` to start a
Leader sequence. Release Space before entering the sequence if any of its keys
would otherwise be remapped on the `space` layer.

| Sequence | Action |
| --- | --- |
| `U S B` | Switch output to USB |
| `B L E` | Switch output to Bluetooth |
| `B 0` | Select Bluetooth profile 0 |
| `B 1` | Select Bluetooth profile 1 |
| `B 2` | Select Bluetooth profile 2 |
