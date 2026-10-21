# TWRP for Moto G Play 2024 (fogona)

Unofficial TWRP recovery for the Motorola Moto G Play 2024 (`fogona`).

**Status: experimental.** TWRP boots and the touchscreen works. Nothing else has been verified yet, because the development device is no longer working. Testers are welcome.

## Device

| | |
| --- | --- |
| Model | Motorola Moto G Play 2024 |
| Codename | `fogona` |
| Recovery | TWRP (unofficial) |

## Feature status

| Feature | Status |
| --- | --- |
| Boots to TWRP | Working |
| Touchscreen | Working |
| ADB | Untested |
| MTP | Untested |
| Backup / restore | Untested |
| Flashing ZIPs | Untested |
| Flashing images | Untested |
| SD card | Untested |
| USB OTG | Untested |
| Decryption | Not expected to work |

## Before you start

- **Use this at your own risk.** This build is provided as-is, without warranty. The author isn't responsible for bricked devices, data loss or damaged partitions.
- **Back up your data** before you flash or boot anything.
- **Know how to recover your device** (for example with your stock firmware and fastboot) before you try this.
- If you only want to test it, use `fastboot boot` instead of flashing it. Check first whether your device supports this.

## Testing and bug reports

The original test device is broken, so further testing depends on the community. If you have a Moto G Play 2024, please report what works as well as what doesn't. Confirming that a feature works is just as useful.

When you open an issue, please include:

- the TWRP build you used
- what you did, what you expected, and what happened instead
- the exact error messages
- the recovery log (`/tmp/recovery.log`; save it with **Advanced → Copy Log**, or pull it with `adb pull /tmp/recovery.log`)
- steps to reproduce the problem

## Contributing

Pull requests, logs and test reports are welcome. Open an issue first to discuss larger changes.

## Credits

- [Team Win Recovery Project](https://twrp.me/) and everyone who contributes to TWRP
- Everyone who tests and contributes to this build for `fogona`
