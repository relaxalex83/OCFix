# OCFix
Autoupdate tool for update fully OpenCore EFI modules and kexts

OCUpdateTool - утилита автоматического обновления загрузчика OpenCore и kext'ов

Подходит для версии OpenCore 0.5.9 и выше, на текущий момент до release 0.8.0

Обновление модулей загрузчика:
- BOOTx64.efi
- OpenCanopy.efi
- OpenRuntime.efi
- OpenCore.efi

Сравнение новых ключей загрузчика, начиная с версии 0.5.9, с текущим конфигом, и их безопасное добавление в config.plist

Автоматическое сравнение и обновление папки с kext'ами, список обновляемых:

Основные
- AirportBrcmFixup.kext
- AppleALC.kext
- AppleALCU.kext
- FakeSMC.kext
- Lilu.kext
- NVMeFix.kext
- SMCBatteryManager.kext
- VirtualSMC.kext
- WhateverGreen.kext
- VoodooPS2Controller.kext

Дополнительные
- AtherosE2200Ethernet.kext
- CPUFriend.kext
- CpuTscSync.kext
- BT4LEContinuityFixup.kext
- IntelCPUMonitor.kext
- LucyRTL8125Ethernet.kext
- IntelMausi.kext
- IntelMausiEthernet.kext
- RadeonMonitor.kext
- RealtekRTL8111.kext
- SMCLightSensor.kext

Мы постарались сделать максимально лёгким и безопасным переход вашей верисии OpenCore от старых, до релиза 0.8.0, и обновить всю папку EFI, но от текущих ошибок вашего конфига не застрахованы даже вы сами:) Проверить config.plist вы можете native утилитой OpenCore - ocvalidate.
