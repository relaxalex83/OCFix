# OCUpdateTool
Autoupdate tool for update fully OpenCore EFI modules and kexts

OCUpdateTool - утилита автоматического обновления загрузчика OpenCore и kext'ов

Минимальная версия OpenCore для работы утилиты - 0.5.9.

[Скачать / Download](https://ihackline.com/wp-content/uploads/2020/12/OCUpdateTool.zip)

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
- SMCDellSensors.kext
- SMCLightSensor.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- VirtualSMC.kext
- WhateverGreen.kext
- VoodooPS2Controller.kext

Дополнительные
- AtherosE2200Ethernet.kext
- CPUFriend.kext
- CpuTscSync.kext
- IntelCPUMonitor.kext
- LucyRTL8125Ethernet.kext
- IntelMausi.kext
- IntelMausiEthernet.kext
- RadeonMonitor.kext
- RealtekRTL8111.kext
- SMCLightSensor.kext
- HibernationFixup.kext

Простое обновление вашей версии OpenCore от 0.5.9, до текущего релиза 0.8.9.
Проверить config.plist можете native утилитой OpenCore - ocvalidate.
