# Intel NUC10 Hackintosh OpenCore EFI

## OpenCore Version

- **0.9.7** [Download](https://github.com/acidanthera/OpenCorePkg)

## Hardware

- **Tested Model**: NUC10i5FNK

## macOS

- **Version**: Ventura 13.x

## BIOS Setup

### CFG Unlock

- See [`Disable_CFG_Lock_Guide.md`](Disable_CFG_Lock_Guide.md) for instructions.

### Settings

- **Advanced**
  - Storage -> SATA: **AHCI**
  - Video -> IGD Min Memory: **64MB**, Aperture Size: **256MB**, Primary Port: **Auto**
- **Boot**
  - Secure Boot: **Disabled**
  - Boot Priority -> UEFI: **Enabled**, Legacy: **Disabled**, Fast: **Disabled**
- **Power**
  - Deep S4/S5: **Enabled**
  - Wake on LAN/S5: **Disabled**

## Kexts

- **Lilu** 1.6.7: [GitHub](https://github.com/acidanthera/Lilu)
- **VirtualSMC** 1.3.2: [GitHub](https://github.com/acidanthera/VirtualSMC)
- **WhateverGreen** 1.6.6: [GitHub](https://github.com/acidanthera/WhateverGreen)
- **AppleALC** 1.8.8: [GitHub](https://github.com/acidanthera/AppleALC)
- **IntelMausi** 1.0.7: [GitHub](https://github.com/acidanthera/IntelMausi)
- **AirportItlwm** 2.2.0: [GitHub](https://github.com/OpenIntelWireless/itlwm)
- **Bluetooth** (BlueToolFixup, IntelBTPatcher, Firmware, Injector) 2.3.0: [GitHub](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)

Ensure BIOS is configured correctly for optimal performance and macOS compatibility. Kexts are essential for hardware functionality.
