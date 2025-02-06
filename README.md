# Oplus_Convert_Global_Status
## The status about convert global of OP/Realme phones!
### Something important to read before:

```
#include <std_disclaimer.h>
/*Your warranty is now void.*/ 
I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you 
getting fired because the alarm app failed.
Please do some research if you have any concerns about features  before flashing it!
YOU are choosing to make these modifications, and if you point the finger at me for
messing up your device, I will laugh at you.
```

1. There are lots of ways to convert global, and the method is **device-based**, such as substitution method or fastboot method. **Please beware of that**. Since the boot process of OPlus device is very fragile, it can easily bricked if the conversion fails, **espacially with an locked bootloader.**
2. The region of Global ROM is **limited**. Usually the safest region is IN and EU, **but there's still a chance to lose IMEI, especially for MTK devices!** Also, there may be some HW/FW difference among rigeons, which may cause bugs or function loss. Do at your own risk!
3. The version of China ROM is **limited**. It's the common issue for those model which requires Deeptesting. You can downgrade to certain version of CN ROM, convert to global, and continue the update process.
4. After conversion, for those device that lose the ability to OTA, **backup your data first before update!** Unless you can make sure the update package won't ruin the partition or messup the device! 
5. This post is for CN device to Global, **NOT Global to CN**. I don't have any mind about convert to CN. **If you seek of that, leave this page.**


### Availability/Aval.
| flags | statement |
| ----- | -------- |
| ✅ | Available with freely or no need to unlock bootloader |
| 🔼 | Available with certain condition. e.g. EDL/Deeptesting |
| ❓ | **Teoritically** available, but not proven |
| ❌ | Unavailable |

## Functionality
| flags | Lock BL | Camera | OTA | Signal |
| ----- | ------- | ------ | --- | ------ |
| ☑️ | Yes | Works | Works without problems | Works
| 💬 | Yes but unsafe | Partially works | Works but need to flash img | Partially works |
| ⚠️ | - | Malfunctional without patch | - | Malfunctional without patch |
| ❌ | No | Impossible to fix | No | Impossible to fix |
| ❓ | Unknown | Unknown | Unknown | Unknown |

## Devices
### OPPO
| Aval. | Device name in CN | Device name in GLO | Lock BL | Camera | OTA | Signal | Other issue |
| - | - | - | - | - | - | - | - |
|✅|Find N3|OnePlus Open|☑️|☑️|☑️|☑️|
|🔼|Find X7 Ultra|OnePlus 12|☑️|❌|☑️|❓|No touchscreen|
|🔼|K12 Plus|OnePlus Nord CE4|☑️|☑️|☑️|☑️|Battery difference|
|✅|K12|OnePlus Nord CE4|☑️|☑️|☑️|☑️|NFC broken|
|✅|K12x|OnePlus Nord CE4 Lite|☑️|☑️|☑️|☑️|
|✅|K11|OnePlus Nord CE3|☑️|☑️|☑️|☑️|
|✅|K11x|OnePlus Nord CE3 Lite|☑️|☑️|☑️|☑️|
|✅|Reno 10 Pro+|Reno 10 Pro+|☑️|☑️|☑️|☑️|
|✅|Reno 10|Reno 10 Pro|☑️|❓|☑️|☑️|
|🔼|Reno 11|Reno 11 Pro|☑️|☑️|☑️|☑️|
|🔼|A96(CN)|OnePlus Nord N20|☑️|❓|❓|❓|
|✅|OPPO Pad 3 Pro|OnePlus Pad 2|☑️|☑️|☑️|☑️| stylo not works|
|❓|OPPO Pad Air 2|OnePlus Pad Go
|❌|Any model with significant HW difference.|-|

### Oneplus
| Aval. | Device name in CN | Device name in GLO | Lock BL | Camera | OTA | Signal | Other issue |
| - | - | - | - | - | - | - | - |
|✅|13|13|💬|☑️|💬|⚠️|
|✅|12|12|☑️|☑️|☑️|☑️|
|✅|11|11|☑️|☑️|☑️|☑️|Chance to lose bootloader|
|✅|10 Pro|10 Pro|☑️|☑️|☑️|☑️|
|✅|Ace 5|13R|☑️|💬|☑️|☑️|Camera blurs|
|✅|Ace 3|12R|☑️|☑️|☑️|💬|No 5G|
|✅|Ace 3V|Nord 4|❌|☑️|❌|☑️|
|✅|Ace 2|11R|☑️|💬|☑️|☑️|Screen flickers|
|✅|Ace 2V|Nord 3|💬|⚠️|💬|☑️|
|✅|Ace Pro|10T|☑️|☑️|☑️|☑️|
|✅|Ace|10R|☑️|☑️|☑️|☑️|
|✅|OnePlus Pad Pro|OnePlus Pad 2|☑️|☑️|☑️|☑️|stylo not works|
|❌|Ace 5 Pro|Unofficial|❌|
|❌|Ace 3 Pro|Unofficial|❌|
|❌|Ace 2 Pro|Unofficial|❌|

### Realme
| Aval. | Device name in CN | Device name in GLO | Lock BL | Camera | OTA | Signal | Other issue |
| - | - | - | - | - | - | - | - |
|🔼|GT7 Pro|GT7 Pro|❓|☑️|☑️|❓|No facial/fingerprint|
|🔼|GT Neo 6|GT 6|❌|⚠️|💬|☑️|No facial/fingerprint|
|✅|GT Neo 6 SE|GT 6T|💬|☑️|💬|☑️|No facial/fingerprint|
|✅|GT Neo 5|GT3 240W|☑️|☑️|☑️|☑️|Battery difference|
|✅|GT Neo 5 240W|GT3 240W|☑️|☑️|☑️|☑️|
|🔼|GT Neo 5 SE|GT Neo 5 SE|💬|☑️|❌|☑️|
|✅|GT Neo 3|GT Neo 3|☑️|☑️|☑️|☑️|
|🔼|GT Neo 3|OnePlus 10R|❌|☑️|❌|☑️|
|✅|GT 2 Pro|GT 2 Pro|☑️|☑️|☑️|☑️|
|✅|13 Pro+|13 Pro+|☑️|☑️|☑️|☑️|
|✅|12 Pro+|12 Pro+|☑️|☑️|☑️|☑️|NFC broken|
|❓|12 Pro|12 Pro|
|❌|GT5|-|
|❌|GT5 Pro|-|
|❌|GT6|-|
|❌|Neo 7|-|

