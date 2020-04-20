# ASRock-Z390-Phantom-Gaming-ITXac-OpenCore-Hackintosh



## 电脑配置
|规格 | 详细信息|
|:-: | :-:|
|主板型号| ASRock Z390 Phantom Gaming-ITX/ac |
|操作系统|macOS Catalina 10.15.x |
|处理器|英特尔 酷睿 i9-9900k|
|内存|芝奇 16GBx2 3200Mhz C16|
|硬盘| 西数 SN750 1T |
|显卡|蓝宝石 5700XT 超白金|
|显示器|优派 VX2780-4K-ZERO|
|声卡| Realtek ALC1220|
|网卡| 94360CS2|


## BIOS设置

- ### BIOS版本：V4.2

  - Advanced \ Chipset Configuration → Vt-d : Disabled

  - Advanced \ Super IO Configuration → Serial Port: Disabled

  - Advanced \ USB Configuration → XHCI Hand-off : Enabled

  - Advanced \ Chipset Configuration → Share Memory : 128MB

  - Advanced \ Chipset Configuration → IGPU Multi-Monitor : Enabled

## 说明

 - 使用OC-5700XT只针对我使用的显卡进行相关“优化”并不通用！
 - OC-5700XT下的SSDT-XHC-RHUB.aml是ACPI定制USB，无需重复定制USB端口。
 - 其它显卡的直接使用“OC”即可，显卡相关优化请自行爬帖解决。
 - SSDT-TbtOnPch.aml是用于支持Type C热拔插的，但是会导致ACPI Error开机变慢。
 
 ## 其他大佬的EFI
 
  - [fangf2018](https://github.com/fangf2018/ASRock-Z390-Phantom-ITX-OpenCore-Hackintosh)
  


