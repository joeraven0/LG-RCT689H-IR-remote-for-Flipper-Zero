# LG RCT689H – Samsung32 IR Test File

Flipper Zero infrared remote file for controlling the **LG RCT689H** DVD/VHS recorder. The file has been tested and confirmed to work on the LG RCT689H.

> [!NOTE]
> This is a community-created remote profile and is not an official LG file.

## File

`LG_RCT689H_SAMSUNG32_TEST.ir`

## Commands

| Signal | Function | Command |
| --- | --- | --- |
| `KNOWN_DVD` | Switches to DVD mode | `F1` |
| `KNOWN_RESOLUTION` | Changes the output resolution | `F5` |
| `VCR_MODE` | Switch to VHS/VCR mode | `F3` |
| `REWIND` | Rewind | `32` |
| `FAST_FORWARD` | Fast-forward | `33` |
| `PLAY` | Play | `31` |
| `STOP` | Stop | `39` |
| `PAUSE` | Pause | `38` |
| `EJECT` | Eject | `36` |
| `SKIP_NEXT` | Skip to next | `34` |
| `SKIP_PREV` | Skip to previous | `35` |
| `DISPLAY` | Display information | `3A` |
| `REW_ALT_4C` | Alternative rewind command | `4C` |

## Installation on Flipper Zero

1. Connect the Flipper Zero to your computer or open its microSD card.
2. Copy `LG_RCT689H_SAMSUNG32_TEST.ir` to the `infrared` folder.
3. On the Flipper Zero, open **Infrared → Saved remotes**.
4. Select the file and test the signals with a clear line of sight to the device.

## Technical Information

- File format: Flipper Zero IR signals file, version 1
- Protocol: `Samsung32`
- Address: `2D 00 00 00`
- Target model: LG RCT689H
- Compatibility: Tested and confirmed working

## Disclaimer

This file is provided as-is for testing purposes. It is not an official LG remote-control profile.
