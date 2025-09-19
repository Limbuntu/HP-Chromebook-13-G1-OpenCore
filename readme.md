# HP-Chromebook-13-G1-OpenCore

## 概况

HP-Chromebook-13-G1黑苹果EFI分享，Chromebook刷机前需要先[刷入完整UEFI](https://docs.mrchromebox.tech/docs/getting-started.html)

### MacOS版本：Monterey  (12.7.5)

### OpenCore版本：OpenCore 1.0.5

------

## 硬件信息

| 硬件      | 型号                             |
| --------- | -------------------------------- |
| 处理器    | 英特尔酷睿m5-6y57                |
| 内存      | 8GB（4GB x2）LPDDR3-1866（板载） |
| 硬盘      | 32G eMMC 5.0                     |
| 显卡      | 英特尔核芯显卡 UHD 515           |
| 无线+蓝牙 | 英特尔 AC7265 蓝牙4.2            |
| 声卡      | 英特尔SOF音频智音技术            |
| 显示器    | HP（13.3英寸3200*1800分辨率）    |

## 硬件驱动情况

| 硬件                   | 驱动情况 | 备注                                                    |
| ---------------------- | -------- | ------------------------------------------------------- |
| 核显                   | 正常     | 驱动正常、分辨率正常、显存正常                          |
| 屏幕亮度               | 正常     |                                                         |
| 核显解码器             | 正常     |                                                         |
| 键盘                   | 正常     |                                                         |
| 触控板                 | 正常     |                                                         |
| 蓝牙                   | 正常     | 配合BlueToolFixup.kext、IntelBluetoothFirmware.kext正常 |
| WIFI                   | 正常     | 配合AirportItlwm-Monterey.kext正常                      |
| DP/HDMI                | 正常     |                                                         |
| 音频（扬声器、麦克风） | 不工作   | Chromebook原因无法解决                                  |
| 键盘背光               | 正常     | 配合特制VoodooPS2Controller.kext正常                    |
| 键盘快捷键             | 需要映射 |                                                         |
| 电池                   | 正常     | 需要配合ECenabler使用                                   |
| EMMC                   | 正常     | SSDT-HPET.aml配合EmeraldSDHC.kext正常驱动               |
| 摄像头                 | 正常     |                                                         |
| USB                    | 正常     |                                                         |
| 3.5mm耳机              | 不工作   |                                                         |
| SD卡                   | 不工作   |                                                         |

| 硬件    | 驱动情况 | 备注                   |
| ------- | -------- | ---------------------- |
| 睿频    | 正常     |                        |
| 睡眠    | 正常     |                        |
| Airdrop | 正常     | 只能单向识别，无法传输 |
| 风扇    | 没有     |                        |
| USB速度 | 正常     |                        |

## 注意事项

待补充...