Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 8319

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Tactus        | GeoPad 220                  | Tablet      | [0be548592c](https://linux-hardware.org/?probe=0be548592c) | Jul 01, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [f0421c3e3f](https://linux-hardware.org/?probe=f0421c3e3f) | Jul 01, 2022 |
| Samsung       | Q210/P210                   | Notebook    | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| Tactus        | GeoPad 220                  | Tablet      | [a7e3223fa6](https://linux-hardware.org/?probe=a7e3223fa6) | Jul 01, 2022 |
| Acer          | Aspire C22-820              | All in one  | [0bb41ffb71](https://linux-hardware.org/?probe=0bb41ffb71) | Jul 01, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [0bbac8ce1f](https://linux-hardware.org/?probe=0bbac8ce1f) | Jul 01, 2022 |
| HP            | Presario CQ56               | Notebook    | [af108b4933](https://linux-hardware.org/?probe=af108b4933) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e14880c80](https://linux-hardware.org/?probe=7e14880c80) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [142c1c4ef2](https://linux-hardware.org/?probe=142c1c4ef2) | Jun 30, 2022 |
| HP            | 0B54h D                     | Desktop     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a90f7795b](https://linux-hardware.org/?probe=7a90f7795b) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [608388f911](https://linux-hardware.org/?probe=608388f911) | Jun 29, 2022 |
| Dell          | Latitude 7389               | Convertible | [6cc0f640ed](https://linux-hardware.org/?probe=6cc0f640ed) | Jun 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1eed1dcced](https://linux-hardware.org/?probe=1eed1dcced) | Jun 29, 2022 |
| Toshiba       | Satellite C850-1NU          | Notebook    | [2b83cb161e](https://linux-hardware.org/?probe=2b83cb161e) | Jun 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [828f0b9ef1](https://linux-hardware.org/?probe=828f0b9ef1) | Jun 29, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [4573e16702](https://linux-hardware.org/?probe=4573e16702) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [f52aacfbfe](https://linux-hardware.org/?probe=f52aacfbfe) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [e01155e6ba](https://linux-hardware.org/?probe=e01155e6ba) | Jun 28, 2022 |
| Acer          | Aspire Z3-615               | All in one  | [cccd2abbc8](https://linux-hardware.org/?probe=cccd2abbc8) | Jun 28, 2022 |
| Acer          | Aspire Z3-615               | All in one  | [34700612aa](https://linux-hardware.org/?probe=34700612aa) | Jun 28, 2022 |
| ASRock        | P43DE                       | Desktop     | [f52d106d92](https://linux-hardware.org/?probe=f52d106d92) | Jun 28, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | Pavilion TS 14              | Notebook    | [f851b6a57b](https://linux-hardware.org/?probe=f851b6a57b) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| HP            | Pavilion 15                 | Notebook    | [9e7a0c1889](https://linux-hardware.org/?probe=9e7a0c1889) | Jun 27, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [287a6346a7](https://linux-hardware.org/?probe=287a6346a7) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [47b4db95ed](https://linux-hardware.org/?probe=47b4db95ed) | Jun 26, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [74401fdf8b](https://linux-hardware.org/?probe=74401fdf8b) | Jun 26, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [dde9afd7cb](https://linux-hardware.org/?probe=dde9afd7cb) | Jun 26, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f0e913f715](https://linux-hardware.org/?probe=f0e913f715) | Jun 26, 2022 |
| HP            | 1496                        | Desktop     | [97616aecd6](https://linux-hardware.org/?probe=97616aecd6) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | Notebook    | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| HP            | 1496                        | Desktop     | [3ab73cb742](https://linux-hardware.org/?probe=3ab73cb742) | Jun 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| ASRock        | P43DE                       | Desktop     | [80f90e4fcd](https://linux-hardware.org/?probe=80f90e4fcd) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Sony          | VGN-FS415B                  | Notebook    | [00d146d9f4](https://linux-hardware.org/?probe=00d146d9f4) | Jun 24, 2022 |
| HP            | 8265                        | Desktop     | [3de1cae37a](https://linux-hardware.org/?probe=3de1cae37a) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [cfeb6fb78f](https://linux-hardware.org/?probe=cfeb6fb78f) | Jun 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [d08060fb50](https://linux-hardware.org/?probe=d08060fb50) | Jun 23, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [d87c55111a](https://linux-hardware.org/?probe=d87c55111a) | Jun 23, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1091cc416e](https://linux-hardware.org/?probe=1091cc416e) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [a678044765](https://linux-hardware.org/?probe=a678044765) | Jun 23, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [babd561a16](https://linux-hardware.org/?probe=babd561a16) | Jun 23, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| HP            | 3397                        | Desktop     | [3c7afd0ee2](https://linux-hardware.org/?probe=3c7afd0ee2) | Jun 23, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [4b44fc669a](https://linux-hardware.org/?probe=4b44fc669a) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [c812a957cf](https://linux-hardware.org/?probe=c812a957cf) | Jun 23, 2022 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [13a427bd3b](https://linux-hardware.org/?probe=13a427bd3b) | Jun 23, 2022 |
| Razer         | Blade                       | Notebook    | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [257f40005f](https://linux-hardware.org/?probe=257f40005f) | Jun 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [98350f1274](https://linux-hardware.org/?probe=98350f1274) | Jun 22, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [7a571de1b9](https://linux-hardware.org/?probe=7a571de1b9) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [6024015ecc](https://linux-hardware.org/?probe=6024015ecc) | Jun 21, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1f3b17165b](https://linux-hardware.org/?probe=1f3b17165b) | Jun 21, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [1cd927a911](https://linux-hardware.org/?probe=1cd927a911) | Jun 21, 2022 |
| Samsung       | Galaxy Book 12              | Tablet      | [01839134d7](https://linux-hardware.org/?probe=01839134d7) | Jun 21, 2022 |
| HP            | 2B4B                        | Desktop     | [0e699c16a4](https://linux-hardware.org/?probe=0e699c16a4) | Jun 21, 2022 |
| HP            | 2B4B                        | Desktop     | [d179d2050d](https://linux-hardware.org/?probe=d179d2050d) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [9423c99e6c](https://linux-hardware.org/?probe=9423c99e6c) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | Desktop     | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f3176204c8](https://linux-hardware.org/?probe=f3176204c8) | Jun 21, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b0d232a3c9](https://linux-hardware.org/?probe=b0d232a3c9) | Jun 20, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | Notebook    | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| HP            | 15                          | Notebook    | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [604913c4e4](https://linux-hardware.org/?probe=604913c4e4) | Jun 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eeadb7465a](https://linux-hardware.org/?probe=eeadb7465a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [8cecec73c6](https://linux-hardware.org/?probe=8cecec73c6) | Jun 19, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [714a296099](https://linux-hardware.org/?probe=714a296099) | Jun 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [560fa88cad](https://linux-hardware.org/?probe=560fa88cad) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [f420b36754](https://linux-hardware.org/?probe=f420b36754) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [e8f74093f9](https://linux-hardware.org/?probe=e8f74093f9) | Jun 19, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [8cc15a5651](https://linux-hardware.org/?probe=8cc15a5651) | Jun 19, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [d04b14aef0](https://linux-hardware.org/?probe=d04b14aef0) | Jun 19, 2022 |
| HP            | 843B                        | Desktop     | [21619041e8](https://linux-hardware.org/?probe=21619041e8) | Jun 19, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [ff71b93299](https://linux-hardware.org/?probe=ff71b93299) | Jun 19, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [d7e8fa7984](https://linux-hardware.org/?probe=d7e8fa7984) | Jun 19, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | Notebook    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| HP            | 1494                        | Desktop     | [2dc41c0b99](https://linux-hardware.org/?probe=2dc41c0b99) | Jun 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bbe948274e](https://linux-hardware.org/?probe=bbe948274e) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c61fdedfff](https://linux-hardware.org/?probe=c61fdedfff) | Jun 18, 2022 |
| Dell          | Inspiron 7370               | Notebook    | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f399990b6e](https://linux-hardware.org/?probe=f399990b6e) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [8121d73bc9](https://linux-hardware.org/?probe=8121d73bc9) | Jun 18, 2022 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [41945e4369](https://linux-hardware.org/?probe=41945e4369) | Jun 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [d6be55432d](https://linux-hardware.org/?probe=d6be55432d) | Jun 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| Sony          | VGN-P11Z_Q                  | Notebook    | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [198f6e8fca](https://linux-hardware.org/?probe=198f6e8fca) | Jun 16, 2022 |
| AZW           | Gemini T34                  | Desktop     | [553b174ce2](https://linux-hardware.org/?probe=553b174ce2) | Jun 16, 2022 |
| HP            | 3031h                       | Desktop     | [00080c0264](https://linux-hardware.org/?probe=00080c0264) | Jun 16, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42fd0dcad9](https://linux-hardware.org/?probe=42fd0dcad9) | Jun 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e8f85ab771](https://linux-hardware.org/?probe=e8f85ab771) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [507dcf06fc](https://linux-hardware.org/?probe=507dcf06fc) | Jun 16, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [64794fafd4](https://linux-hardware.org/?probe=64794fafd4) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [994f64f470](https://linux-hardware.org/?probe=994f64f470) | Jun 15, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d5cefb3aa6](https://linux-hardware.org/?probe=d5cefb3aa6) | Jun 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [5afd9dcda0](https://linux-hardware.org/?probe=5afd9dcda0) | Jun 15, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [e00b8334dd](https://linux-hardware.org/?probe=e00b8334dd) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [8e0da08d4d](https://linux-hardware.org/?probe=8e0da08d4d) | Jun 15, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [cf4df37657](https://linux-hardware.org/?probe=cf4df37657) | Jun 15, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b6cdb73504](https://linux-hardware.org/?probe=b6cdb73504) | Jun 15, 2022 |
| Dell          | 0XCR8D A02                  | Desktop     | [134e7208cc](https://linux-hardware.org/?probe=134e7208cc) | Jun 15, 2022 |
| Lenovo        | ThinkPad T430 2349AZ6       | Notebook    | [7369a5bd6b](https://linux-hardware.org/?probe=7369a5bd6b) | Jun 15, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [6edff2c2ad](https://linux-hardware.org/?probe=6edff2c2ad) | Jun 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [131a938c5e](https://linux-hardware.org/?probe=131a938c5e) | Jun 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5b6f3d52c5](https://linux-hardware.org/?probe=5b6f3d52c5) | Jun 14, 2022 |
| Samsung       | 935QDB                      | Convertible | [a140a593c5](https://linux-hardware.org/?probe=a140a593c5) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [15cb74d079](https://linux-hardware.org/?probe=15cb74d079) | Jun 13, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c1be5f13af](https://linux-hardware.org/?probe=c1be5f13af) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d40967b111](https://linux-hardware.org/?probe=d40967b111) | Jun 13, 2022 |
| Dell          | Studio XPS 1640             | Notebook    | [aac66b6b7b](https://linux-hardware.org/?probe=aac66b6b7b) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [fde3cee794](https://linux-hardware.org/?probe=fde3cee794) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e69ce900b7](https://linux-hardware.org/?probe=e69ce900b7) | Jun 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [6eef40304f](https://linux-hardware.org/?probe=6eef40304f) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [72ea50523c](https://linux-hardware.org/?probe=72ea50523c) | Jun 13, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [05b64cc5de](https://linux-hardware.org/?probe=05b64cc5de) | Jun 12, 2022 |
| HP            | 18E5                        | Desktop     | [275b8ca77c](https://linux-hardware.org/?probe=275b8ca77c) | Jun 12, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [c1e6618ac5](https://linux-hardware.org/?probe=c1e6618ac5) | Jun 12, 2022 |
| MSI           | P65 Creator 9SE             | Notebook    | [da30629803](https://linux-hardware.org/?probe=da30629803) | Jun 11, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [9967260c3c](https://linux-hardware.org/?probe=9967260c3c) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [83f46a355b](https://linux-hardware.org/?probe=83f46a355b) | Jun 11, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [64cf410189](https://linux-hardware.org/?probe=64cf410189) | Jun 10, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [53c2e38d14](https://linux-hardware.org/?probe=53c2e38d14) | Jun 10, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [ce4d95c7bf](https://linux-hardware.org/?probe=ce4d95c7bf) | Jun 10, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [ec0c59238f](https://linux-hardware.org/?probe=ec0c59238f) | Jun 10, 2022 |
| Dell          | Latitude E7270              | Notebook    | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [31275cdf72](https://linux-hardware.org/?probe=31275cdf72) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [9e574bef7c](https://linux-hardware.org/?probe=9e574bef7c) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [843d2132ad](https://linux-hardware.org/?probe=843d2132ad) | Jun 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d29d3120fb](https://linux-hardware.org/?probe=d29d3120fb) | Jun 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7cdc9be674](https://linux-hardware.org/?probe=7cdc9be674) | Jun 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6d195af721](https://linux-hardware.org/?probe=6d195af721) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| Acer          | Aspire C24-865              | All in one  | [232cfe0afa](https://linux-hardware.org/?probe=232cfe0afa) | Jun 08, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [36d73de92c](https://linux-hardware.org/?probe=36d73de92c) | Jun 08, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [b56845a5b8](https://linux-hardware.org/?probe=b56845a5b8) | Jun 08, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude E6510              | Notebook    | [083f1d576d](https://linux-hardware.org/?probe=083f1d576d) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [13c7b714dc](https://linux-hardware.org/?probe=13c7b714dc) | Jun 07, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [d67bb7d7c0](https://linux-hardware.org/?probe=d67bb7d7c0) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0b042e37b3](https://linux-hardware.org/?probe=0b042e37b3) | Jun 06, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [f5ded88514](https://linux-hardware.org/?probe=f5ded88514) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| Lenovo        | ThinkPad T480 20L5000AUK    | Notebook    | [0bf67e4018](https://linux-hardware.org/?probe=0bf67e4018) | Jun 06, 2022 |
| Dell          | Latitude E6400              | Notebook    | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| Acer          | Aspire C22-820              | All in one  | [32cb850c67](https://linux-hardware.org/?probe=32cb850c67) | Jun 05, 2022 |
| HP            | 8350                        | Desktop     | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| HYPA          | FLUX                        | Notebook    | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e579d912d0](https://linux-hardware.org/?probe=e579d912d0) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [39c37e56ec](https://linux-hardware.org/?probe=39c37e56ec) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| Acer          | Aspire C22-820              | All in one  | [682fb84b70](https://linux-hardware.org/?probe=682fb84b70) | Jun 04, 2022 |
| Acer          | Aspire C24-865              | All in one  | [62cdbbbf11](https://linux-hardware.org/?probe=62cdbbbf11) | Jun 04, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [13a3f2e1cd](https://linux-hardware.org/?probe=13a3f2e1cd) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [d147abfc52](https://linux-hardware.org/?probe=d147abfc52) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9829bd8f60](https://linux-hardware.org/?probe=9829bd8f60) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | Notebook    | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| HP            | 8055                        | Desktop     | [400c0e19cc](https://linux-hardware.org/?probe=400c0e19cc) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2a7bfa492d](https://linux-hardware.org/?probe=2a7bfa492d) | Jun 02, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [e683ab1965](https://linux-hardware.org/?probe=e683ab1965) | Jun 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [8b67a50c5e](https://linux-hardware.org/?probe=8b67a50c5e) | Jun 01, 2022 |
| Alienware     | M11x R2                     | Notebook    | [0b6837debb](https://linux-hardware.org/?probe=0b6837debb) | Jun 01, 2022 |
| Acer          | Aspire S3                   | Notebook    | [a78c44019e](https://linux-hardware.org/?probe=a78c44019e) | Jun 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM    | Notebook    | [8db5953984](https://linux-hardware.org/?probe=8db5953984) | Jun 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [86b732afda](https://linux-hardware.org/?probe=86b732afda) | Jun 01, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [fdadcc5b74](https://linux-hardware.org/?probe=fdadcc5b74) | Jun 01, 2022 |
| Dell          | G7 7700                     | Notebook    | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [2940e1d0b2](https://linux-hardware.org/?probe=2940e1d0b2) | May 31, 2022 |
| HP            | Presario C500 (RT155EA#A... | Notebook    | [5eb3ee9cc2](https://linux-hardware.org/?probe=5eb3ee9cc2) | May 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| HP            | 09E8h                       | Desktop     | [9c75a338fc](https://linux-hardware.org/?probe=9c75a338fc) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [4863034bc5](https://linux-hardware.org/?probe=4863034bc5) | May 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| HYPA          | FLUX                        | Notebook    | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [4a364390a6](https://linux-hardware.org/?probe=4a364390a6) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [87e8835eba](https://linux-hardware.org/?probe=87e8835eba) | May 30, 2022 |
| Gigabyte      | Q35M-S2                     | Desktop     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [69e61d13d7](https://linux-hardware.org/?probe=69e61d13d7) | May 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| ECS           | GF8100VM-M5                 | Desktop     | [f36fc15fdc](https://linux-hardware.org/?probe=f36fc15fdc) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [923158d12f](https://linux-hardware.org/?probe=923158d12f) | May 30, 2022 |
| Razer         | Blade                       | Notebook    | [d7271bb7c4](https://linux-hardware.org/?probe=d7271bb7c4) | May 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [ece4d207f3](https://linux-hardware.org/?probe=ece4d207f3) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Intel         | DQ35JO AAD82085-803         | Desktop     | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| Toshiba       | Satellite C850-1KN          | Notebook    | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| AZW           | GT-R                        | Notebook    | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0e5f6d9e4c](https://linux-hardware.org/?probe=0e5f6d9e4c) | May 29, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Microsoft     | Surface Go 2                | Tablet      | [2e809f0e07](https://linux-hardware.org/?probe=2e809f0e07) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [36ee0ea60c](https://linux-hardware.org/?probe=36ee0ea60c) | May 27, 2022 |
| YANYU         | ITX-N29 VER:1.3             | Desktop     | [b577dd621f](https://linux-hardware.org/?probe=b577dd621f) | May 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [5dc9e065e3](https://linux-hardware.org/?probe=5dc9e065e3) | May 27, 2022 |
| Dell          | Precision 5530              | Notebook    | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Dell          | Latitude 7389               | Convertible | [c7c04eece7](https://linux-hardware.org/?probe=c7c04eece7) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [4f083f0d35](https://linux-hardware.org/?probe=4f083f0d35) | May 25, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a4cfdafe9d](https://linux-hardware.org/?probe=a4cfdafe9d) | May 25, 2022 |
| Acer          | Aspire C24-865              | All in one  | [c0215bd100](https://linux-hardware.org/?probe=c0215bd100) | May 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [e46d84c5c8](https://linux-hardware.org/?probe=e46d84c5c8) | May 25, 2022 |
| Toshiba       | TECRA A50-C                 | Notebook    | [60a580cb3b](https://linux-hardware.org/?probe=60a580cb3b) | May 25, 2022 |
| Acer          | Aspire S3                   | Notebook    | [d91145e274](https://linux-hardware.org/?probe=d91145e274) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| Dell          | 0WG864                      | Desktop     | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [fea70c6484](https://linux-hardware.org/?probe=fea70c6484) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [de2c57e521](https://linux-hardware.org/?probe=de2c57e521) | May 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [2be14c5fa8](https://linux-hardware.org/?probe=2be14c5fa8) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f87621c475](https://linux-hardware.org/?probe=f87621c475) | May 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [7152b312be](https://linux-hardware.org/?probe=7152b312be) | May 23, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [0339b395ed](https://linux-hardware.org/?probe=0339b395ed) | May 23, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [70b5e91823](https://linux-hardware.org/?probe=70b5e91823) | May 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [afb47f4860](https://linux-hardware.org/?probe=afb47f4860) | May 23, 2022 |
| BOX           | W54_W94_W955TU,-T,-C        | Notebook    | [a36f54939d](https://linux-hardware.org/?probe=a36f54939d) | May 23, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [f833ddc13b](https://linux-hardware.org/?probe=f833ddc13b) | May 23, 2022 |
| Entroware     | Apollo                      | Notebook    | [30881be24b](https://linux-hardware.org/?probe=30881be24b) | May 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [2034bf506d](https://linux-hardware.org/?probe=2034bf506d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [47c446b3d8](https://linux-hardware.org/?probe=47c446b3d8) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [90d0bb5bc0](https://linux-hardware.org/?probe=90d0bb5bc0) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [48047cdaf6](https://linux-hardware.org/?probe=48047cdaf6) | May 22, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [63d7169ac1](https://linux-hardware.org/?probe=63d7169ac1) | May 22, 2022 |
| Acer          | Aspire C24-865              | All in one  | [98c5c2fbfd](https://linux-hardware.org/?probe=98c5c2fbfd) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [5bf86728dc](https://linux-hardware.org/?probe=5bf86728dc) | May 22, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [e856d4589a](https://linux-hardware.org/?probe=e856d4589a) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| MSI           | 2AE0                        | Desktop     | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1609781085](https://linux-hardware.org/?probe=1609781085) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| Entroware     | Triton                      | Notebook    | [2bfa3e5cc8](https://linux-hardware.org/?probe=2bfa3e5cc8) | May 20, 2022 |
| Acer          | Aspire C24-865              | All in one  | [97f59bfda5](https://linux-hardware.org/?probe=97f59bfda5) | May 20, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [45fa54c9ff](https://linux-hardware.org/?probe=45fa54c9ff) | May 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5c989cad8d](https://linux-hardware.org/?probe=5c989cad8d) | May 20, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ab767eaa59](https://linux-hardware.org/?probe=ab767eaa59) | May 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [27ebc7fd11](https://linux-hardware.org/?probe=27ebc7fd11) | May 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ae9b0dc77e](https://linux-hardware.org/?probe=ae9b0dc77e) | May 19, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [9e2c754ed6](https://linux-hardware.org/?probe=9e2c754ed6) | May 19, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d5712e1976](https://linux-hardware.org/?probe=d5712e1976) | May 19, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [8f9f8c2634](https://linux-hardware.org/?probe=8f9f8c2634) | May 18, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2e663e698c](https://linux-hardware.org/?probe=2e663e698c) | May 18, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [382192bd2c](https://linux-hardware.org/?probe=382192bd2c) | May 18, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [f92e29b330](https://linux-hardware.org/?probe=f92e29b330) | May 17, 2022 |
| Lenovo        | SDK0F82993 WIN              | All in one  | [39c4df81a2](https://linux-hardware.org/?probe=39c4df81a2) | May 17, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [2e9d55d3a7](https://linux-hardware.org/?probe=2e9d55d3a7) | May 17, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [874d108fe3](https://linux-hardware.org/?probe=874d108fe3) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [6c433b3b60](https://linux-hardware.org/?probe=6c433b3b60) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [06625fa3f2](https://linux-hardware.org/?probe=06625fa3f2) | May 15, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [beaaf4e7f7](https://linux-hardware.org/?probe=beaaf4e7f7) | May 15, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2555fd899e](https://linux-hardware.org/?probe=2555fd899e) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a48bb9c613](https://linux-hardware.org/?probe=a48bb9c613) | May 14, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [951323a711](https://linux-hardware.org/?probe=951323a711) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [eef86f3d24](https://linux-hardware.org/?probe=eef86f3d24) | May 14, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [b46632bd9a](https://linux-hardware.org/?probe=b46632bd9a) | May 14, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [67dbfe0d98](https://linux-hardware.org/?probe=67dbfe0d98) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [a28b44985d](https://linux-hardware.org/?probe=a28b44985d) | May 13, 2022 |
| Acer          | Aspire C24-865              | All in one  | [b164e17b68](https://linux-hardware.org/?probe=b164e17b68) | May 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
| Star Labs     | Lite                        | Notebook    | [dbe031aada](https://linux-hardware.org/?probe=dbe031aada) | May 13, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [40cc6f33b5](https://linux-hardware.org/?probe=40cc6f33b5) | May 13, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [433432f3ee](https://linux-hardware.org/?probe=433432f3ee) | May 12, 2022 |
| AZW           | BT3 X                       | Desktop     | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5d84102fa2](https://linux-hardware.org/?probe=5d84102fa2) | May 11, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| Dell          | Precision M6600             | Notebook    | [730205ec1e](https://linux-hardware.org/?probe=730205ec1e) | May 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c703872774](https://linux-hardware.org/?probe=c703872774) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | Notebook    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [08deba5f5f](https://linux-hardware.org/?probe=08deba5f5f) | May 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f790f52fa7](https://linux-hardware.org/?probe=f790f52fa7) | May 11, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [debc8c7d47](https://linux-hardware.org/?probe=debc8c7d47) | May 10, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [bef0e3659e](https://linux-hardware.org/?probe=bef0e3659e) | May 10, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0fed762686](https://linux-hardware.org/?probe=0fed762686) | May 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [b9afe34b9a](https://linux-hardware.org/?probe=b9afe34b9a) | May 10, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [bfdc40105f](https://linux-hardware.org/?probe=bfdc40105f) | May 10, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Clevo         | W55xEU                      | Notebook    | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [2b88c091bf](https://linux-hardware.org/?probe=2b88c091bf) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [77145b587d](https://linux-hardware.org/?probe=77145b587d) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [e3f65dec10](https://linux-hardware.org/?probe=e3f65dec10) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Acer          | Revo RL80                   | Desktop     | [c48857049a](https://linux-hardware.org/?probe=c48857049a) | May 08, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [49228d9f61](https://linux-hardware.org/?probe=49228d9f61) | May 08, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [912dbb8280](https://linux-hardware.org/?probe=912dbb8280) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b0b389263a](https://linux-hardware.org/?probe=b0b389263a) | May 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [87ed69fff0](https://linux-hardware.org/?probe=87ed69fff0) | May 08, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a1f8265785](https://linux-hardware.org/?probe=a1f8265785) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e97309bc05](https://linux-hardware.org/?probe=e97309bc05) | May 07, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [34bd31c9f9](https://linux-hardware.org/?probe=34bd31c9f9) | May 07, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [a864f8a7c4](https://linux-hardware.org/?probe=a864f8a7c4) | May 07, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [4a3960f047](https://linux-hardware.org/?probe=4a3960f047) | May 07, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [cae67b53da](https://linux-hardware.org/?probe=cae67b53da) | May 06, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [149d1c8c87](https://linux-hardware.org/?probe=149d1c8c87) | May 05, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [b9e969d2ba](https://linux-hardware.org/?probe=b9e969d2ba) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e074ed44da](https://linux-hardware.org/?probe=e074ed44da) | May 04, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d5cd65ba5b](https://linux-hardware.org/?probe=d5cd65ba5b) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | Notebook    | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [0e78293e95](https://linux-hardware.org/?probe=0e78293e95) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [d16211782e](https://linux-hardware.org/?probe=d16211782e) | May 03, 2022 |
| Dell          | Latitude E7470              | Notebook    | [7991dfd7a5](https://linux-hardware.org/?probe=7991dfd7a5) | May 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f337a6103d](https://linux-hardware.org/?probe=f337a6103d) | May 03, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [116d1b0421](https://linux-hardware.org/?probe=116d1b0421) | May 02, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [7431774485](https://linux-hardware.org/?probe=7431774485) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [6a9dfa32d3](https://linux-hardware.org/?probe=6a9dfa32d3) | May 02, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bbbfaa9157](https://linux-hardware.org/?probe=bbbfaa9157) | May 02, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [8e97662196](https://linux-hardware.org/?probe=8e97662196) | May 02, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Acer          | Aspire V5-573P              | Notebook    | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [fad7884cb4](https://linux-hardware.org/?probe=fad7884cb4) | May 02, 2022 |
| ASUSTek       | UX310UA                     | Notebook    | [80fce5caed](https://linux-hardware.org/?probe=80fce5caed) | May 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [a5fd51cc39](https://linux-hardware.org/?probe=a5fd51cc39) | May 01, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [b4d4e52220](https://linux-hardware.org/?probe=b4d4e52220) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [31b081b116](https://linux-hardware.org/?probe=31b081b116) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f62d8963d7](https://linux-hardware.org/?probe=f62d8963d7) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7797c23169](https://linux-hardware.org/?probe=7797c23169) | Apr 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b443315241](https://linux-hardware.org/?probe=b443315241) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BV001YMS    | Notebook    | [f38b762c83](https://linux-hardware.org/?probe=f38b762c83) | Apr 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ad8bbf54e3](https://linux-hardware.org/?probe=ad8bbf54e3) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [df82c076b8](https://linux-hardware.org/?probe=df82c076b8) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [589a22c0c6](https://linux-hardware.org/?probe=589a22c0c6) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a26fd2399d](https://linux-hardware.org/?probe=a26fd2399d) | Apr 29, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d291472a69](https://linux-hardware.org/?probe=d291472a69) | Apr 28, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [f7fed2c8eb](https://linux-hardware.org/?probe=f7fed2c8eb) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [773f69d63b](https://linux-hardware.org/?probe=773f69d63b) | Apr 28, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [4e6d6e311c](https://linux-hardware.org/?probe=4e6d6e311c) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [06ef070e40](https://linux-hardware.org/?probe=06ef070e40) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [8ef803f8c9](https://linux-hardware.org/?probe=8ef803f8c9) | Apr 28, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [a12d1b0c47](https://linux-hardware.org/?probe=a12d1b0c47) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2943b21899](https://linux-hardware.org/?probe=2943b21899) | Apr 28, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3b25bc9d0d](https://linux-hardware.org/?probe=3b25bc9d0d) | Apr 27, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [b45bd0a0a0](https://linux-hardware.org/?probe=b45bd0a0a0) | Apr 27, 2022 |
| HP            | 8437                        | Desktop     | [c9444c57eb](https://linux-hardware.org/?probe=c9444c57eb) | Apr 27, 2022 |
| HP            | 8437                        | Desktop     | [cb1aa84569](https://linux-hardware.org/?probe=cb1aa84569) | Apr 27, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [4c6852d631](https://linux-hardware.org/?probe=4c6852d631) | Apr 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1fc7423fdf](https://linux-hardware.org/?probe=1fc7423fdf) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [37501fa5f3](https://linux-hardware.org/?probe=37501fa5f3) | Apr 27, 2022 |
| Pegatron      | 2A99                        | Desktop     | [92c0dec6fa](https://linux-hardware.org/?probe=92c0dec6fa) | Apr 27, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [5edac5d5a6](https://linux-hardware.org/?probe=5edac5d5a6) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a3f49d1a04](https://linux-hardware.org/?probe=a3f49d1a04) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b47f678ce9](https://linux-hardware.org/?probe=b47f678ce9) | Apr 27, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [ba50a20e23](https://linux-hardware.org/?probe=ba50a20e23) | Apr 27, 2022 |
| Notebook      | W130SV                      | Notebook    | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [9202f4bade](https://linux-hardware.org/?probe=9202f4bade) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [d23e7110f6](https://linux-hardware.org/?probe=d23e7110f6) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [3390e01a9c](https://linux-hardware.org/?probe=3390e01a9c) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| PC Special... | NJ50_70CU                   | Notebook    | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [4ac0a4dff1](https://linux-hardware.org/?probe=4ac0a4dff1) | Apr 26, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [bc3cbdbc1f](https://linux-hardware.org/?probe=bc3cbdbc1f) | Apr 26, 2022 |
| Acer          | NC-E5-573-36PM              | Notebook    | [a98a807776](https://linux-hardware.org/?probe=a98a807776) | Apr 26, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [549c216d66](https://linux-hardware.org/?probe=549c216d66) | Apr 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [1f95a73d57](https://linux-hardware.org/?probe=1f95a73d57) | Apr 26, 2022 |
| AZW           | U59                         | Desktop     | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [6aae7c23ad](https://linux-hardware.org/?probe=6aae7c23ad) | Apr 26, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [a8626eb701](https://linux-hardware.org/?probe=a8626eb701) | Apr 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [35824f9b37](https://linux-hardware.org/?probe=35824f9b37) | Apr 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4a9e24224a](https://linux-hardware.org/?probe=4a9e24224a) | Apr 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [6564561a75](https://linux-hardware.org/?probe=6564561a75) | Apr 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [83093f24ef](https://linux-hardware.org/?probe=83093f24ef) | Apr 24, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [182279920b](https://linux-hardware.org/?probe=182279920b) | Apr 24, 2022 |
| ZOTAC         | ZBOXSD-ID12/ID13            | Mini pc     | [730b034ed7](https://linux-hardware.org/?probe=730b034ed7) | Apr 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [af6b49b2a5](https://linux-hardware.org/?probe=af6b49b2a5) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fbb2b97e0f](https://linux-hardware.org/?probe=fbb2b97e0f) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Intel         | X99                         | Desktop     | [1c9a508130](https://linux-hardware.org/?probe=1c9a508130) | Apr 23, 2022 |
| Purism        | Librem 14                   | Notebook    | [9d078217f1](https://linux-hardware.org/?probe=9d078217f1) | Apr 23, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d54074527](https://linux-hardware.org/?probe=5d54074527) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [0ca0b999d6](https://linux-hardware.org/?probe=0ca0b999d6) | Apr 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [796bf7f467](https://linux-hardware.org/?probe=796bf7f467) | Apr 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [18f00ab5d9](https://linux-hardware.org/?probe=18f00ab5d9) | Apr 22, 2022 |
| HP            | Pavilion dv6                | Notebook    | [16e2c4e6d3](https://linux-hardware.org/?probe=16e2c4e6d3) | Apr 22, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [cdc3ddaa2d](https://linux-hardware.org/?probe=cdc3ddaa2d) | Apr 22, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [12d817136f](https://linux-hardware.org/?probe=12d817136f) | Apr 22, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [5f754cd313](https://linux-hardware.org/?probe=5f754cd313) | Apr 22, 2022 |
| CyberPower... | Tracer II                   | Notebook    | [4582a60770](https://linux-hardware.org/?probe=4582a60770) | Apr 21, 2022 |
| Dynabook      | PORTEGE X30L-J              | Notebook    | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [80099b4b7f](https://linux-hardware.org/?probe=80099b4b7f) | Apr 21, 2022 |
| Dell          | Latitude D430               | Notebook    | [00ddfbe46f](https://linux-hardware.org/?probe=00ddfbe46f) | Apr 20, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| HP            | Notebook                    | Notebook    | [f6d84934cd](https://linux-hardware.org/?probe=f6d84934cd) | Apr 19, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [abf93cff25](https://linux-hardware.org/?probe=abf93cff25) | Apr 19, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [58dc7c7bf2](https://linux-hardware.org/?probe=58dc7c7bf2) | Apr 19, 2022 |
| Biostar       | H55A+                       | Desktop     | [3b18e10f6c](https://linux-hardware.org/?probe=3b18e10f6c) | Apr 19, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d2a4b7e7ed](https://linux-hardware.org/?probe=d2a4b7e7ed) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [c7f2c2e71c](https://linux-hardware.org/?probe=c7f2c2e71c) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [42db396ee8](https://linux-hardware.org/?probe=42db396ee8) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4dc4e0af40](https://linux-hardware.org/?probe=4dc4e0af40) | Apr 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d0cd53048e](https://linux-hardware.org/?probe=d0cd53048e) | Apr 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8436ff452b](https://linux-hardware.org/?probe=8436ff452b) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cc4a1b8b6f](https://linux-hardware.org/?probe=cc4a1b8b6f) | Apr 17, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [fa96d5405d](https://linux-hardware.org/?probe=fa96d5405d) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [b35ed6654a](https://linux-hardware.org/?probe=b35ed6654a) | Apr 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [9868b4e681](https://linux-hardware.org/?probe=9868b4e681) | Apr 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdb3506164](https://linux-hardware.org/?probe=bdb3506164) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [47fc027d41](https://linux-hardware.org/?probe=47fc027d41) | Apr 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dda68647](https://linux-hardware.org/?probe=a4dda68647) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9eac0ebbce](https://linux-hardware.org/?probe=9eac0ebbce) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b5094d96cc](https://linux-hardware.org/?probe=b5094d96cc) | Apr 16, 2022 |
| Lenovo        | ThinkPad L440 20ASA02800    | Notebook    | [697a90ffa2](https://linux-hardware.org/?probe=697a90ffa2) | Apr 16, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [48deb234f0](https://linux-hardware.org/?probe=48deb234f0) | Apr 15, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5ae4706be7](https://linux-hardware.org/?probe=5ae4706be7) | Apr 15, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [997b338c67](https://linux-hardware.org/?probe=997b338c67) | Apr 15, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [7d156875bb](https://linux-hardware.org/?probe=7d156875bb) | Apr 15, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4a93a73c74](https://linux-hardware.org/?probe=4a93a73c74) | Apr 15, 2022 |
| Toshiba       | Satellite P50t-A            | Notebook    | [f2eef93c50](https://linux-hardware.org/?probe=f2eef93c50) | Apr 15, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [1b0ad4ce13](https://linux-hardware.org/?probe=1b0ad4ce13) | Apr 14, 2022 |
| HP            | ENVY 13                     | Notebook    | [4b0b543bdf](https://linux-hardware.org/?probe=4b0b543bdf) | Apr 14, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [a10ea959f8](https://linux-hardware.org/?probe=a10ea959f8) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [4b3cedca6f](https://linux-hardware.org/?probe=4b3cedca6f) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [8734154fb6](https://linux-hardware.org/?probe=8734154fb6) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9e6fc630f4](https://linux-hardware.org/?probe=9e6fc630f4) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c9e8c79a2e](https://linux-hardware.org/?probe=c9e8c79a2e) | Apr 14, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [2550bb5cd7](https://linux-hardware.org/?probe=2550bb5cd7) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [960f707d0f](https://linux-hardware.org/?probe=960f707d0f) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [260c012f44](https://linux-hardware.org/?probe=260c012f44) | Apr 14, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [ca7dd7880b](https://linux-hardware.org/?probe=ca7dd7880b) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [2a5f0afcc8](https://linux-hardware.org/?probe=2a5f0afcc8) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [89de41a490](https://linux-hardware.org/?probe=89de41a490) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0517baf6ee](https://linux-hardware.org/?probe=0517baf6ee) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [92555ffe91](https://linux-hardware.org/?probe=92555ffe91) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [58ef1f3594](https://linux-hardware.org/?probe=58ef1f3594) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c0f293e16](https://linux-hardware.org/?probe=0c0f293e16) | Apr 13, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [df33a057b6](https://linux-hardware.org/?probe=df33a057b6) | Apr 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4c86ab8c47](https://linux-hardware.org/?probe=4c86ab8c47) | Apr 13, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [94783711b3](https://linux-hardware.org/?probe=94783711b3) | Apr 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ec9869d115](https://linux-hardware.org/?probe=ec9869d115) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bad4b60ec4](https://linux-hardware.org/?probe=bad4b60ec4) | Apr 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [986cb2363c](https://linux-hardware.org/?probe=986cb2363c) | Apr 13, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | Notebook    | [a31cc5eb3b](https://linux-hardware.org/?probe=a31cc5eb3b) | Apr 13, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b089bb9293](https://linux-hardware.org/?probe=b089bb9293) | Apr 13, 2022 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [6113e480b5](https://linux-hardware.org/?probe=6113e480b5) | Apr 13, 2022 |
| Toshiba       | TECRA X40-D                 | Notebook    | [d18cfd17bb](https://linux-hardware.org/?probe=d18cfd17bb) | Apr 13, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | Notebook    | [f7d44e9cd6](https://linux-hardware.org/?probe=f7d44e9cd6) | Apr 13, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [cfa1e38deb](https://linux-hardware.org/?probe=cfa1e38deb) | Apr 13, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| Dell          | Precision 5530              | Notebook    | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f2a040ef2b](https://linux-hardware.org/?probe=f2a040ef2b) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [0d208bc673](https://linux-hardware.org/?probe=0d208bc673) | Apr 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [25d8968f19](https://linux-hardware.org/?probe=25d8968f19) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [7a31392de4](https://linux-hardware.org/?probe=7a31392de4) | Apr 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5029c3c4a2](https://linux-hardware.org/?probe=5029c3c4a2) | Apr 13, 2022 |
| HP            | 2215                        | Desktop     | [5acea5fa0a](https://linux-hardware.org/?probe=5acea5fa0a) | Apr 13, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [b00858fa95](https://linux-hardware.org/?probe=b00858fa95) | Apr 13, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [221b65ebf0](https://linux-hardware.org/?probe=221b65ebf0) | Apr 12, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [5d33b64d12](https://linux-hardware.org/?probe=5d33b64d12) | Apr 12, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [710d07a9bd](https://linux-hardware.org/?probe=710d07a9bd) | Apr 12, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [677234b8b8](https://linux-hardware.org/?probe=677234b8b8) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| ASRock        | G41M-GS                     | Desktop     | [f3e24ea1c9](https://linux-hardware.org/?probe=f3e24ea1c9) | Apr 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5bce6bbead](https://linux-hardware.org/?probe=5bce6bbead) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [6c85a524a1](https://linux-hardware.org/?probe=6c85a524a1) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [e664ba6c5a](https://linux-hardware.org/?probe=e664ba6c5a) | Apr 10, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [01e9bf2cee](https://linux-hardware.org/?probe=01e9bf2cee) | Apr 10, 2022 |
| ASUSTek       | P6T                         | Desktop     | [579a4a7f83](https://linux-hardware.org/?probe=579a4a7f83) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [34b32b5b14](https://linux-hardware.org/?probe=34b32b5b14) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f4d9933ef2](https://linux-hardware.org/?probe=f4d9933ef2) | Apr 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [d7170319fc](https://linux-hardware.org/?probe=d7170319fc) | Apr 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8a0974e971](https://linux-hardware.org/?probe=8a0974e971) | Apr 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9971d706c5](https://linux-hardware.org/?probe=9971d706c5) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [eec4231e44](https://linux-hardware.org/?probe=eec4231e44) | Apr 10, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7187b2e6ee](https://linux-hardware.org/?probe=7187b2e6ee) | Apr 10, 2022 |
| ASUSTek       | UX310UA                     | Notebook    | [732364c253](https://linux-hardware.org/?probe=732364c253) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [0bac47f3e6](https://linux-hardware.org/?probe=0bac47f3e6) | Apr 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [5a09d1fa57](https://linux-hardware.org/?probe=5a09d1fa57) | Apr 09, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [cf308c090a](https://linux-hardware.org/?probe=cf308c090a) | Apr 09, 2022 |
| Advent        | Tacto Purple                | Notebook    | [5ad7851c7a](https://linux-hardware.org/?probe=5ad7851c7a) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [919af587bb](https://linux-hardware.org/?probe=919af587bb) | Apr 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [3b16991947](https://linux-hardware.org/?probe=3b16991947) | Apr 08, 2022 |
| CyberPower... | Tracer II                   | Notebook    | [735f98bbb9](https://linux-hardware.org/?probe=735f98bbb9) | Apr 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [86fff99f90](https://linux-hardware.org/?probe=86fff99f90) | Apr 08, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [afd87f36b2](https://linux-hardware.org/?probe=afd87f36b2) | Apr 08, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [53afee4cf6](https://linux-hardware.org/?probe=53afee4cf6) | Apr 08, 2022 |
| AZW           | U59                         | Desktop     | [d84f7caf26](https://linux-hardware.org/?probe=d84f7caf26) | Apr 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b7d6ae3171](https://linux-hardware.org/?probe=b7d6ae3171) | Apr 08, 2022 |
| Getac         | S400                        | Notebook    | [7f8a76a614](https://linux-hardware.org/?probe=7f8a76a614) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d75f38ec35](https://linux-hardware.org/?probe=d75f38ec35) | Apr 08, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [596a2a878c](https://linux-hardware.org/?probe=596a2a878c) | Apr 08, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [52f833f67d](https://linux-hardware.org/?probe=52f833f67d) | Apr 07, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [6451bf5197](https://linux-hardware.org/?probe=6451bf5197) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [b9eb04d2d8](https://linux-hardware.org/?probe=b9eb04d2d8) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| ARKA          | BOOK                        | Notebook    | [44809cec7b](https://linux-hardware.org/?probe=44809cec7b) | Apr 06, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [159b7c81e0](https://linux-hardware.org/?probe=159b7c81e0) | Apr 06, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [bb750c0f56](https://linux-hardware.org/?probe=bb750c0f56) | Apr 06, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [8b2c078f25](https://linux-hardware.org/?probe=8b2c078f25) | Apr 06, 2022 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [efae0e63ab](https://linux-hardware.org/?probe=efae0e63ab) | Apr 06, 2022 |
| MSI           | GL63 9SD                    | Notebook    | [6b4f4b5c10](https://linux-hardware.org/?probe=6b4f4b5c10) | Apr 06, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [77b4a03b19](https://linux-hardware.org/?probe=77b4a03b19) | Apr 05, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [069a2be036](https://linux-hardware.org/?probe=069a2be036) | Apr 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [943191da55](https://linux-hardware.org/?probe=943191da55) | Apr 05, 2022 |
| HP            | 0A9Ch                       | Desktop     | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8a3966d71c](https://linux-hardware.org/?probe=8a3966d71c) | Apr 05, 2022 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [ea53fbbc2a](https://linux-hardware.org/?probe=ea53fbbc2a) | Apr 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [952a71b37e](https://linux-hardware.org/?probe=952a71b37e) | Apr 04, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Acer          | Aspire M3910                | Desktop     | [bb407c8963](https://linux-hardware.org/?probe=bb407c8963) | Apr 04, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4efbcf88a2](https://linux-hardware.org/?probe=4efbcf88a2) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [b768d18e12](https://linux-hardware.org/?probe=b768d18e12) | Apr 04, 2022 |
| Sony          | VPCEB4L1E                   | Notebook    | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [bb18f1eb8f](https://linux-hardware.org/?probe=bb18f1eb8f) | Apr 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [894d2f4814](https://linux-hardware.org/?probe=894d2f4814) | Apr 03, 2022 |
| HP            | Notebook                    | Notebook    | [e1af57dc16](https://linux-hardware.org/?probe=e1af57dc16) | Apr 02, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [446d4b4c59](https://linux-hardware.org/?probe=446d4b4c59) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [35f6caff42](https://linux-hardware.org/?probe=35f6caff42) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [68483bc13a](https://linux-hardware.org/?probe=68483bc13a) | Apr 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4a757bd59d](https://linux-hardware.org/?probe=4a757bd59d) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | Desktop     | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [2671214482](https://linux-hardware.org/?probe=2671214482) | Apr 01, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [c22fa84e7b](https://linux-hardware.org/?probe=c22fa84e7b) | Apr 01, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d685d62203](https://linux-hardware.org/?probe=d685d62203) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e81da10444](https://linux-hardware.org/?probe=e81da10444) | Apr 01, 2022 |
| Toshiba       | dynabook R73/A              | Notebook    | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [01f7a198c5](https://linux-hardware.org/?probe=01f7a198c5) | Mar 31, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [c55872162d](https://linux-hardware.org/?probe=c55872162d) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [b0bacf15b5](https://linux-hardware.org/?probe=b0bacf15b5) | Mar 31, 2022 |
| System76      | Lemur Pro                   | Notebook    | [34b16b2584](https://linux-hardware.org/?probe=34b16b2584) | Mar 31, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [09c3268643](https://linux-hardware.org/?probe=09c3268643) | Mar 31, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [0236d370e9](https://linux-hardware.org/?probe=0236d370e9) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [9db5eb67b3](https://linux-hardware.org/?probe=9db5eb67b3) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [90ec98a922](https://linux-hardware.org/?probe=90ec98a922) | Mar 31, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [5e0222bdc7](https://linux-hardware.org/?probe=5e0222bdc7) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| ASRock        | P67 Pro3                    | Desktop     | [4a4493ce71](https://linux-hardware.org/?probe=4a4493ce71) | Mar 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [92eae45686](https://linux-hardware.org/?probe=92eae45686) | Mar 30, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [10fe068865](https://linux-hardware.org/?probe=10fe068865) | Mar 30, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [1f2167e189](https://linux-hardware.org/?probe=1f2167e189) | Mar 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [48e596f082](https://linux-hardware.org/?probe=48e596f082) | Mar 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fab15ee731](https://linux-hardware.org/?probe=fab15ee731) | Mar 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [33107e3ea3](https://linux-hardware.org/?probe=33107e3ea3) | Mar 29, 2022 |
| Samsung       | 930QCA                      | Convertible | [08d30ac431](https://linux-hardware.org/?probe=08d30ac431) | Mar 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [8cf6c58236](https://linux-hardware.org/?probe=8cf6c58236) | Mar 29, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [f271b0ce8b](https://linux-hardware.org/?probe=f271b0ce8b) | Mar 29, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [2a9a30b011](https://linux-hardware.org/?probe=2a9a30b011) | Mar 29, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [29e7a23412](https://linux-hardware.org/?probe=29e7a23412) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [2b7fe29925](https://linux-hardware.org/?probe=2b7fe29925) | Mar 28, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [7ec3f97491](https://linux-hardware.org/?probe=7ec3f97491) | Mar 28, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [d1635f1e9e](https://linux-hardware.org/?probe=d1635f1e9e) | Mar 28, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [996a5d269c](https://linux-hardware.org/?probe=996a5d269c) | Mar 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [bac5e4b9c2](https://linux-hardware.org/?probe=bac5e4b9c2) | Mar 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [12b7ee9f76](https://linux-hardware.org/?probe=12b7ee9f76) | Mar 27, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| Acer          | Predator G3-605             | Desktop     | [9a26fde0c3](https://linux-hardware.org/?probe=9a26fde0c3) | Mar 26, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [aae529497f](https://linux-hardware.org/?probe=aae529497f) | Mar 25, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [381e2b1130](https://linux-hardware.org/?probe=381e2b1130) | Mar 25, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| MSI           | GL63 9SD                    | Notebook    | [d82d8f7857](https://linux-hardware.org/?probe=d82d8f7857) | Mar 25, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [04bca4a56e](https://linux-hardware.org/?probe=04bca4a56e) | Mar 25, 2022 |
| Google        | Banon                       | Notebook    | [422e2dc398](https://linux-hardware.org/?probe=422e2dc398) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| HP            | 82FF                        | Desktop     | [cb8d5d95bb](https://linux-hardware.org/?probe=cb8d5d95bb) | Mar 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b3f93f17bb](https://linux-hardware.org/?probe=b3f93f17bb) | Mar 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cafc2e5aad](https://linux-hardware.org/?probe=cafc2e5aad) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | Desktop     | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | Desktop     | [87989ace9b](https://linux-hardware.org/?probe=87989ace9b) | Mar 24, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [c9775b9b30](https://linux-hardware.org/?probe=c9775b9b30) | Mar 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [b5b6beaa5d](https://linux-hardware.org/?probe=b5b6beaa5d) | Mar 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7c31f8a6ac](https://linux-hardware.org/?probe=7c31f8a6ac) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [6a88c14776](https://linux-hardware.org/?probe=6a88c14776) | Mar 23, 2022 |
| HP            | 1589                        | Desktop     | [1758805274](https://linux-hardware.org/?probe=1758805274) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [db93476384](https://linux-hardware.org/?probe=db93476384) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| HP            | Pavilion g7                 | Notebook    | [9d4d9b0c34](https://linux-hardware.org/?probe=9d4d9b0c34) | Mar 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3568c4160a](https://linux-hardware.org/?probe=3568c4160a) | Mar 22, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [c8afce0622](https://linux-hardware.org/?probe=c8afce0622) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| HP            | 0B54h D                     | Desktop     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [ce0d6584b2](https://linux-hardware.org/?probe=ce0d6584b2) | Mar 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [9ca3ea91d3](https://linux-hardware.org/?probe=9ca3ea91d3) | Mar 21, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fbbcb0de35](https://linux-hardware.org/?probe=fbbcb0de35) | Mar 21, 2022 |
| ASUSTek       | M4A78-VM                    | Desktop     | [c48ac764a4](https://linux-hardware.org/?probe=c48ac764a4) | Mar 20, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [543e44c95a](https://linux-hardware.org/?probe=543e44c95a) | Mar 20, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7ad353e47f](https://linux-hardware.org/?probe=7ad353e47f) | Mar 20, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [2de5cec732](https://linux-hardware.org/?probe=2de5cec732) | Mar 20, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [6e1d3b66a7](https://linux-hardware.org/?probe=6e1d3b66a7) | Mar 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| HP            | G61                         | Notebook    | [833491ff37](https://linux-hardware.org/?probe=833491ff37) | Mar 19, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [54c52f2837](https://linux-hardware.org/?probe=54c52f2837) | Mar 19, 2022 |
| Dell          | Latitude 3540               | Notebook    | [6d95fdc85c](https://linux-hardware.org/?probe=6d95fdc85c) | Mar 19, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [eab20e919d](https://linux-hardware.org/?probe=eab20e919d) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [a412a37e5f](https://linux-hardware.org/?probe=a412a37e5f) | Mar 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f3b0889850](https://linux-hardware.org/?probe=f3b0889850) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [35b41c3626](https://linux-hardware.org/?probe=35b41c3626) | Mar 18, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [1b90446e3a](https://linux-hardware.org/?probe=1b90446e3a) | Mar 17, 2022 |
| Packard Be... | IMEDIA S2885                | Desktop     | [1cf614db1e](https://linux-hardware.org/?probe=1cf614db1e) | Mar 17, 2022 |
| HP            | Presario CQ57               | Notebook    | [052d5a695c](https://linux-hardware.org/?probe=052d5a695c) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | Notebook    | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [f3e9d39894](https://linux-hardware.org/?probe=f3e9d39894) | Mar 17, 2022 |
| Gigabyte      | EX58-UD5                    | Desktop     | [f445174807](https://linux-hardware.org/?probe=f445174807) | Mar 17, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [4add06ac06](https://linux-hardware.org/?probe=4add06ac06) | Mar 17, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [763a31bbc5](https://linux-hardware.org/?probe=763a31bbc5) | Mar 16, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d5afbde22c](https://linux-hardware.org/?probe=d5afbde22c) | Mar 16, 2022 |
| HP            | EliteBook 2740p             | Notebook    | [8cfadb8983](https://linux-hardware.org/?probe=8cfadb8983) | Mar 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [c6a31b3447](https://linux-hardware.org/?probe=c6a31b3447) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6b3e010244](https://linux-hardware.org/?probe=6b3e010244) | Mar 15, 2022 |
| Dell          | 0P01GV A03                  | Desktop     | [1272dc8512](https://linux-hardware.org/?probe=1272dc8512) | Mar 14, 2022 |
| HP            | 8056                        | Desktop     | [4e8b5eb8bd](https://linux-hardware.org/?probe=4e8b5eb8bd) | Mar 14, 2022 |
| Google        | Samus                       | Notebook    | [9e3da82a58](https://linux-hardware.org/?probe=9e3da82a58) | Mar 14, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [4d32980028](https://linux-hardware.org/?probe=4d32980028) | Mar 14, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [1f948586ca](https://linux-hardware.org/?probe=1f948586ca) | Mar 14, 2022 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [446c515964](https://linux-hardware.org/?probe=446c515964) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [ef6a4d20a7](https://linux-hardware.org/?probe=ef6a4d20a7) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b8354230c7](https://linux-hardware.org/?probe=b8354230c7) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| Alienware     | M14xR1                      | Notebook    | [b98eb5e7cc](https://linux-hardware.org/?probe=b98eb5e7cc) | Mar 13, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [1e2a1731f7](https://linux-hardware.org/?probe=1e2a1731f7) | Mar 13, 2022 |
| ASUSTek       | PN61                        | Mini pc     | [d9003d95d7](https://linux-hardware.org/?probe=d9003d95d7) | Mar 13, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [595ba4af42](https://linux-hardware.org/?probe=595ba4af42) | Mar 13, 2022 |
| Gigabyte      | 8IPE775/-G                  | Desktop     | [7888ddbc2b](https://linux-hardware.org/?probe=7888ddbc2b) | Mar 13, 2022 |
| Lenovo        | ThinkPad T490 20N2S1CV00    | Notebook    | [b013642d11](https://linux-hardware.org/?probe=b013642d11) | Mar 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [99c139f47b](https://linux-hardware.org/?probe=99c139f47b) | Mar 12, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [0af6d015a3](https://linux-hardware.org/?probe=0af6d015a3) | Mar 12, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [b12027d55b](https://linux-hardware.org/?probe=b12027d55b) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [c92ad1d825](https://linux-hardware.org/?probe=c92ad1d825) | Mar 12, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [98fd2cf2c6](https://linux-hardware.org/?probe=98fd2cf2c6) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [034b528c9b](https://linux-hardware.org/?probe=034b528c9b) | Mar 11, 2022 |
| Toshiba       | Satellite L350D             | Notebook    | [9e9c1b741b](https://linux-hardware.org/?probe=9e9c1b741b) | Mar 11, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [8898d4987b](https://linux-hardware.org/?probe=8898d4987b) | Mar 11, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [7adb5a975b](https://linux-hardware.org/?probe=7adb5a975b) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Clevo         | P15xEMx                     | Notebook    | [08e970fd6c](https://linux-hardware.org/?probe=08e970fd6c) | Mar 10, 2022 |
| Dell          | Latitude 7420               | Notebook    | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [42f4724835](https://linux-hardware.org/?probe=42f4724835) | Mar 09, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [1cac878272](https://linux-hardware.org/?probe=1cac878272) | Mar 09, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [c9524dc5a1](https://linux-hardware.org/?probe=c9524dc5a1) | Mar 09, 2022 |
| Biostar       | X370GTN                     | Desktop     | [338dd33ac5](https://linux-hardware.org/?probe=338dd33ac5) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [22a8fc3127](https://linux-hardware.org/?probe=22a8fc3127) | Mar 09, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [e2ab3d192c](https://linux-hardware.org/?probe=e2ab3d192c) | Mar 09, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [6563e94c95](https://linux-hardware.org/?probe=6563e94c95) | Mar 09, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [55c84f7f05](https://linux-hardware.org/?probe=55c84f7f05) | Mar 09, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| HP            | Stream Notebook             | Notebook    | [ef7dc93a65](https://linux-hardware.org/?probe=ef7dc93a65) | Mar 08, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [2819c9e72e](https://linux-hardware.org/?probe=2819c9e72e) | Mar 07, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [38c484b64e](https://linux-hardware.org/?probe=38c484b64e) | Mar 07, 2022 |
| Acer          | TP-W700-53334G12            | Notebook    | [61d5d1483d](https://linux-hardware.org/?probe=61d5d1483d) | Mar 07, 2022 |
| HP            | 255 G3                      | Notebook    | [cd0bde08da](https://linux-hardware.org/?probe=cd0bde08da) | Mar 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f0a65362c5](https://linux-hardware.org/?probe=f0a65362c5) | Mar 07, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [3cd1923a76](https://linux-hardware.org/?probe=3cd1923a76) | Mar 06, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [055b6bd058](https://linux-hardware.org/?probe=055b6bd058) | Mar 06, 2022 |
| Toshiba       | Satellite Pro C50-A-1E5     | Notebook    | [ac3b4acda7](https://linux-hardware.org/?probe=ac3b4acda7) | Mar 06, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [35f0ef9cb6](https://linux-hardware.org/?probe=35f0ef9cb6) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [e45f91366e](https://linux-hardware.org/?probe=e45f91366e) | Mar 06, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b50e430cd8](https://linux-hardware.org/?probe=b50e430cd8) | Mar 06, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ca93876528](https://linux-hardware.org/?probe=ca93876528) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [2afe92c38f](https://linux-hardware.org/?probe=2afe92c38f) | Mar 06, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| MSI           | P67A-GD65                   | Desktop     | [b79a915db5](https://linux-hardware.org/?probe=b79a915db5) | Mar 05, 2022 |
| Acer          | TP-W700-53334G12            | Notebook    | [cf6bad7b5c](https://linux-hardware.org/?probe=cf6bad7b5c) | Mar 05, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [0d4a567ac4](https://linux-hardware.org/?probe=0d4a567ac4) | Mar 05, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [c447074d2b](https://linux-hardware.org/?probe=c447074d2b) | Mar 05, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [0b96f93c52](https://linux-hardware.org/?probe=0b96f93c52) | Mar 05, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2a1c30169a](https://linux-hardware.org/?probe=2a1c30169a) | Mar 05, 2022 |
| HP            | 843F                        | Desktop     | [c1a4bbe881](https://linux-hardware.org/?probe=c1a4bbe881) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [a74b04333e](https://linux-hardware.org/?probe=a74b04333e) | Mar 05, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [63c5cafc39](https://linux-hardware.org/?probe=63c5cafc39) | Mar 04, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [61191e0c42](https://linux-hardware.org/?probe=61191e0c42) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [caec25c98b](https://linux-hardware.org/?probe=caec25c98b) | Mar 04, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [3e98f59715](https://linux-hardware.org/?probe=3e98f59715) | Mar 04, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [7d46bb8f25](https://linux-hardware.org/?probe=7d46bb8f25) | Mar 03, 2022 |
| HP            | 15                          | Notebook    | [1d090e42e2](https://linux-hardware.org/?probe=1d090e42e2) | Mar 03, 2022 |
| HP            | 15                          | Notebook    | [c9a13c5150](https://linux-hardware.org/?probe=c9a13c5150) | Mar 03, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [30565cb2f9](https://linux-hardware.org/?probe=30565cb2f9) | Mar 03, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [806101c474](https://linux-hardware.org/?probe=806101c474) | Mar 03, 2022 |
| Dell          | Latitude E6530              | Notebook    | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| HP            | 0B54h D                     | Desktop     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [da9f6479f1](https://linux-hardware.org/?probe=da9f6479f1) | Mar 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7fc2d5d090](https://linux-hardware.org/?probe=7fc2d5d090) | Mar 02, 2022 |
| HP            | Unknown                     | Notebook    | [4c84c909eb](https://linux-hardware.org/?probe=4c84c909eb) | Mar 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b6502f1cf3](https://linux-hardware.org/?probe=b6502f1cf3) | Mar 02, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [3327e56999](https://linux-hardware.org/?probe=3327e56999) | Mar 01, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5e3f7f344c](https://linux-hardware.org/?probe=5e3f7f344c) | Mar 01, 2022 |
| HP            | ProBook 4340s               | Notebook    | [2b4257b1c2](https://linux-hardware.org/?probe=2b4257b1c2) | Mar 01, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0dcb1b8c3c](https://linux-hardware.org/?probe=0dcb1b8c3c) | Mar 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2660f37932](https://linux-hardware.org/?probe=2660f37932) | Mar 01, 2022 |
| Intel         | DQ965GF AAD41016-600        | Desktop     | [9f338ccbd8](https://linux-hardware.org/?probe=9f338ccbd8) | Mar 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [dc25902f7e](https://linux-hardware.org/?probe=dc25902f7e) | Feb 28, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [435548337a](https://linux-hardware.org/?probe=435548337a) | Feb 28, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [9648d5b905](https://linux-hardware.org/?probe=9648d5b905) | Feb 28, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [f2e18241da](https://linux-hardware.org/?probe=f2e18241da) | Feb 28, 2022 |
| Acer          | Aspire Z1801                | All in one  | [e4a1e2ea9b](https://linux-hardware.org/?probe=e4a1e2ea9b) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c4b3104959](https://linux-hardware.org/?probe=c4b3104959) | Feb 28, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d3f2971c3c](https://linux-hardware.org/?probe=d3f2971c3c) | Feb 27, 2022 |
| Notebook      | P15SM-A                     | Notebook    | [dfe7b95d25](https://linux-hardware.org/?probe=dfe7b95d25) | Feb 27, 2022 |
| Acer          | TP-W700-53334G12            | Notebook    | [4f274ebb66](https://linux-hardware.org/?probe=4f274ebb66) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [711184caa5](https://linux-hardware.org/?probe=711184caa5) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| Unknown       | Intel X79                   | Desktop     | [6a9245acd2](https://linux-hardware.org/?probe=6a9245acd2) | Feb 27, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [1163e289a9](https://linux-hardware.org/?probe=1163e289a9) | Feb 27, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fa88748b6b](https://linux-hardware.org/?probe=fa88748b6b) | Feb 27, 2022 |
| Entroware     | Hybris                      | Notebook    | [e7628c79c3](https://linux-hardware.org/?probe=e7628c79c3) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [eab0bfce5e](https://linux-hardware.org/?probe=eab0bfce5e) | Feb 27, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [4f5cd3d750](https://linux-hardware.org/?probe=4f5cd3d750) | Feb 26, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [532115a4ec](https://linux-hardware.org/?probe=532115a4ec) | Feb 26, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [cc86c9d580](https://linux-hardware.org/?probe=cc86c9d580) | Feb 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e3931f1fb](https://linux-hardware.org/?probe=2e3931f1fb) | Feb 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4365bdf905](https://linux-hardware.org/?probe=4365bdf905) | Feb 26, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [081ea4e585](https://linux-hardware.org/?probe=081ea4e585) | Feb 26, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [7f8770afc4](https://linux-hardware.org/?probe=7f8770afc4) | Feb 26, 2022 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [b4770c2901](https://linux-hardware.org/?probe=b4770c2901) | Feb 26, 2022 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [8a91d1a9ff](https://linux-hardware.org/?probe=8a91d1a9ff) | Feb 26, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [a61b7b1a9d](https://linux-hardware.org/?probe=a61b7b1a9d) | Feb 26, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [f719a93837](https://linux-hardware.org/?probe=f719a93837) | Feb 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [3030271376](https://linux-hardware.org/?probe=3030271376) | Feb 25, 2022 |
| Dell          | 0D28YY A03                  | Desktop     | [255c47a106](https://linux-hardware.org/?probe=255c47a106) | Feb 25, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [9f89568d74](https://linux-hardware.org/?probe=9f89568d74) | Feb 25, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [0149efd00d](https://linux-hardware.org/?probe=0149efd00d) | Feb 25, 2022 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [b4e5bf2bd6](https://linux-hardware.org/?probe=b4e5bf2bd6) | Feb 25, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | Notebook    | [ec01c23749](https://linux-hardware.org/?probe=ec01c23749) | Feb 24, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e1ddcb9f9a](https://linux-hardware.org/?probe=e1ddcb9f9a) | Feb 24, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [160a1d60b3](https://linux-hardware.org/?probe=160a1d60b3) | Feb 24, 2022 |
| HP            | 3047h                       | Desktop     | [34a5c05e7d](https://linux-hardware.org/?probe=34a5c05e7d) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b80a8fbd1b](https://linux-hardware.org/?probe=b80a8fbd1b) | Feb 24, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e639fc94c0](https://linux-hardware.org/?probe=e639fc94c0) | Feb 23, 2022 |
| MSI           | 2AE0                        | Desktop     | [74c496c824](https://linux-hardware.org/?probe=74c496c824) | Feb 23, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [182750aa6b](https://linux-hardware.org/?probe=182750aa6b) | Feb 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [6d2bec51f3](https://linux-hardware.org/?probe=6d2bec51f3) | Feb 23, 2022 |
| Google        | Edgar                       | Notebook    | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| Acer          | AO725                       | Notebook    | [65d4162ffe](https://linux-hardware.org/?probe=65d4162ffe) | Feb 23, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [742af9249b](https://linux-hardware.org/?probe=742af9249b) | Feb 23, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [892e886901](https://linux-hardware.org/?probe=892e886901) | Feb 23, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c4b59e08bc](https://linux-hardware.org/?probe=c4b59e08bc) | Feb 22, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [f1f42dcf94](https://linux-hardware.org/?probe=f1f42dcf94) | Feb 22, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [71cac3ebdd](https://linux-hardware.org/?probe=71cac3ebdd) | Feb 22, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [0dbe303c5a](https://linux-hardware.org/?probe=0dbe303c5a) | Feb 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d521452c73](https://linux-hardware.org/?probe=d521452c73) | Feb 22, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [320aa1e42f](https://linux-hardware.org/?probe=320aa1e42f) | Feb 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e5544b291b](https://linux-hardware.org/?probe=e5544b291b) | Feb 22, 2022 |
| Google        | Lindar                      | Notebook    | [1a350b747f](https://linux-hardware.org/?probe=1a350b747f) | Feb 22, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [555ecdf4e9](https://linux-hardware.org/?probe=555ecdf4e9) | Feb 22, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [8ebe1ad906](https://linux-hardware.org/?probe=8ebe1ad906) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [89c67bc757](https://linux-hardware.org/?probe=89c67bc757) | Feb 21, 2022 |
| Lenovo        | 3172 SDK0J40697 WIN 3305... | Mini pc     | [c419233c03](https://linux-hardware.org/?probe=c419233c03) | Feb 21, 2022 |
| Dell          | 0VV4V0 A00                  | All in one  | [362ee918ac](https://linux-hardware.org/?probe=362ee918ac) | Feb 21, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d1f67de0fb](https://linux-hardware.org/?probe=d1f67de0fb) | Feb 21, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [aea94057eb](https://linux-hardware.org/?probe=aea94057eb) | Feb 20, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [eb584535c7](https://linux-hardware.org/?probe=eb584535c7) | Feb 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [56e2e00db1](https://linux-hardware.org/?probe=56e2e00db1) | Feb 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2d5df75b0d](https://linux-hardware.org/?probe=2d5df75b0d) | Feb 20, 2022 |
| HP            | 843F                        | Desktop     | [8dfd1523c9](https://linux-hardware.org/?probe=8dfd1523c9) | Feb 20, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [6205aed9e8](https://linux-hardware.org/?probe=6205aed9e8) | Feb 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [afdbc607c5](https://linux-hardware.org/?probe=afdbc607c5) | Feb 19, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | Notebook    | [7326d20b88](https://linux-hardware.org/?probe=7326d20b88) | Feb 19, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [7ad48c7fcf](https://linux-hardware.org/?probe=7ad48c7fcf) | Feb 19, 2022 |
| Dell          | 0PU052                      | Desktop     | [20d5c30034](https://linux-hardware.org/?probe=20d5c30034) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [5a0d00befe](https://linux-hardware.org/?probe=5a0d00befe) | Feb 19, 2022 |
| Dell          | 0DR845                      | Desktop     | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [d8480748c7](https://linux-hardware.org/?probe=d8480748c7) | Feb 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [2d8f28d6c4](https://linux-hardware.org/?probe=2d8f28d6c4) | Feb 18, 2022 |
| Toshiba       | Satellite L350D             | Notebook    | [00eac655e9](https://linux-hardware.org/?probe=00eac655e9) | Feb 18, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [476adbddc1](https://linux-hardware.org/?probe=476adbddc1) | Feb 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [345b25d5eb](https://linux-hardware.org/?probe=345b25d5eb) | Feb 18, 2022 |
| HP            | Notebook                    | Notebook    | [aee3f5ce0b](https://linux-hardware.org/?probe=aee3f5ce0b) | Feb 18, 2022 |
| ASUSTek       | P5G41T-M LX3 PLUS           | Desktop     | [74fbcf5fd5](https://linux-hardware.org/?probe=74fbcf5fd5) | Feb 17, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [b9dec24676](https://linux-hardware.org/?probe=b9dec24676) | Feb 17, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [2dece71caa](https://linux-hardware.org/?probe=2dece71caa) | Feb 17, 2022 |
| ASUSTek       | X556UB                      | Notebook    | [33eaab7189](https://linux-hardware.org/?probe=33eaab7189) | Feb 16, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d1f8637478](https://linux-hardware.org/?probe=d1f8637478) | Feb 16, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [b5da44235a](https://linux-hardware.org/?probe=b5da44235a) | Feb 16, 2022 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [a1e396ab15](https://linux-hardware.org/?probe=a1e396ab15) | Feb 16, 2022 |
| ASRock        | N68-GS                      | Desktop     | [89ba0e5a52](https://linux-hardware.org/?probe=89ba0e5a52) | Feb 16, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [16f0a2b700](https://linux-hardware.org/?probe=16f0a2b700) | Feb 16, 2022 |
| Dell          | Latitude 5320               | Notebook    | [13c53062b6](https://linux-hardware.org/?probe=13c53062b6) | Feb 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dca11c2c66](https://linux-hardware.org/?probe=dca11c2c66) | Feb 16, 2022 |
| Jumper        | EZbook                      | Notebook    | [4e3450d009](https://linux-hardware.org/?probe=4e3450d009) | Feb 16, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [b889f04704](https://linux-hardware.org/?probe=b889f04704) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1e8c363a67](https://linux-hardware.org/?probe=1e8c363a67) | Feb 16, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [f54569882a](https://linux-hardware.org/?probe=f54569882a) | Feb 16, 2022 |
| Jumper        | EZbook                      | Notebook    | [f27f93bafe](https://linux-hardware.org/?probe=f27f93bafe) | Feb 16, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [0e15edeb64](https://linux-hardware.org/?probe=0e15edeb64) | Feb 15, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [20bf4c2464](https://linux-hardware.org/?probe=20bf4c2464) | Feb 15, 2022 |
| HP            | Notebook                    | Notebook    | [7e7b9be307](https://linux-hardware.org/?probe=7e7b9be307) | Feb 15, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [cd8a9df065](https://linux-hardware.org/?probe=cd8a9df065) | Feb 15, 2022 |
| Acer          | Veriton M680G               | Desktop     | [e25a40166f](https://linux-hardware.org/?probe=e25a40166f) | Feb 15, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [1ae327b586](https://linux-hardware.org/?probe=1ae327b586) | Feb 15, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [4a84859a37](https://linux-hardware.org/?probe=4a84859a37) | Feb 15, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [2a16a25836](https://linux-hardware.org/?probe=2a16a25836) | Feb 14, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [5765e1b103](https://linux-hardware.org/?probe=5765e1b103) | Feb 14, 2022 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [55a7c8230f](https://linux-hardware.org/?probe=55a7c8230f) | Feb 14, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [3dc88df597](https://linux-hardware.org/?probe=3dc88df597) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [f21dcf572e](https://linux-hardware.org/?probe=f21dcf572e) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [7f07e2a9da](https://linux-hardware.org/?probe=7f07e2a9da) | Feb 13, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [a8496ddfda](https://linux-hardware.org/?probe=a8496ddfda) | Feb 13, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [8bd0ac2f4d](https://linux-hardware.org/?probe=8bd0ac2f4d) | Feb 13, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [ead5c5ff20](https://linux-hardware.org/?probe=ead5c5ff20) | Feb 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [019b0aeeea](https://linux-hardware.org/?probe=019b0aeeea) | Feb 13, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [2e1614e8b3](https://linux-hardware.org/?probe=2e1614e8b3) | Feb 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a60918c82b](https://linux-hardware.org/?probe=a60918c82b) | Feb 13, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [8ae7432b94](https://linux-hardware.org/?probe=8ae7432b94) | Feb 13, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [b2d1482541](https://linux-hardware.org/?probe=b2d1482541) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | Notebook    | [a505a2ae47](https://linux-hardware.org/?probe=a505a2ae47) | Feb 12, 2022 |
| Lenovo        | ThinkPad L380 20M5S08R00    | Notebook    | [315d27f7d7](https://linux-hardware.org/?probe=315d27f7d7) | Feb 12, 2022 |
| HP            | 0B54h D                     | Desktop     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| Dell          | Latitude 3390 2-in-1        | Notebook    | [c6fa52f6e0](https://linux-hardware.org/?probe=c6fa52f6e0) | Feb 12, 2022 |
| Intel         | DQ35JO AAE41927-803         | Desktop     | [45149ce1e9](https://linux-hardware.org/?probe=45149ce1e9) | Feb 12, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [1bce93c4ad](https://linux-hardware.org/?probe=1bce93c4ad) | Feb 12, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [baa5837734](https://linux-hardware.org/?probe=baa5837734) | Feb 12, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [fcf08f865e](https://linux-hardware.org/?probe=fcf08f865e) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| Dell          | 0YC03K A04                  | Desktop     | [2c74fc8e5f](https://linux-hardware.org/?probe=2c74fc8e5f) | Feb 12, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [0d07efd7dd](https://linux-hardware.org/?probe=0d07efd7dd) | Feb 12, 2022 |
| ASUSTek       | P5G41T-M LX3 PLUS           | Desktop     | [0468bb5fc0](https://linux-hardware.org/?probe=0468bb5fc0) | Feb 12, 2022 |
| HP            | 255 G3                      | Notebook    | [73426584f7](https://linux-hardware.org/?probe=73426584f7) | Feb 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [7ffdca7ea4](https://linux-hardware.org/?probe=7ffdca7ea4) | Feb 11, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b138a07f00](https://linux-hardware.org/?probe=b138a07f00) | Feb 11, 2022 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [92612952d4](https://linux-hardware.org/?probe=92612952d4) | Feb 11, 2022 |
| Acer          | Aspire Z5610                | All in one  | [141f5642fc](https://linux-hardware.org/?probe=141f5642fc) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [c1ba1e4fe7](https://linux-hardware.org/?probe=c1ba1e4fe7) | Feb 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [302e757209](https://linux-hardware.org/?probe=302e757209) | Feb 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [7757be603c](https://linux-hardware.org/?probe=7757be603c) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [0bec7946da](https://linux-hardware.org/?probe=0bec7946da) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [50383ac9b6](https://linux-hardware.org/?probe=50383ac9b6) | Feb 11, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [4756364ef6](https://linux-hardware.org/?probe=4756364ef6) | Feb 10, 2022 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [42348fc745](https://linux-hardware.org/?probe=42348fc745) | Feb 10, 2022 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [18a9ddcd83](https://linux-hardware.org/?probe=18a9ddcd83) | Feb 10, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [5bc3063386](https://linux-hardware.org/?probe=5bc3063386) | Feb 10, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [5d231b638c](https://linux-hardware.org/?probe=5d231b638c) | Feb 10, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60ee5faa6c](https://linux-hardware.org/?probe=60ee5faa6c) | Feb 10, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [c9aa1fb558](https://linux-hardware.org/?probe=c9aa1fb558) | Feb 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [406d6d6fd0](https://linux-hardware.org/?probe=406d6d6fd0) | Feb 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f57e835c6e](https://linux-hardware.org/?probe=f57e835c6e) | Feb 09, 2022 |
| Intel         | DQ57TM AAE70931-401         | Desktop     | [532b003b77](https://linux-hardware.org/?probe=532b003b77) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7360a72c44](https://linux-hardware.org/?probe=7360a72c44) | Feb 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [fc1a305abe](https://linux-hardware.org/?probe=fc1a305abe) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 2349GAG       | Notebook    | [b2cd2857d3](https://linux-hardware.org/?probe=b2cd2857d3) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d0bfe3fa56](https://linux-hardware.org/?probe=d0bfe3fa56) | Feb 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [9196bd025d](https://linux-hardware.org/?probe=9196bd025d) | Feb 09, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b98ae7b6b2](https://linux-hardware.org/?probe=b98ae7b6b2) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [57130ac0ab](https://linux-hardware.org/?probe=57130ac0ab) | Feb 08, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [2b3ad05e55](https://linux-hardware.org/?probe=2b3ad05e55) | Feb 08, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [85f930f1fc](https://linux-hardware.org/?probe=85f930f1fc) | Feb 08, 2022 |
| ASRock        | Z87M Pro4                   | Desktop     | [9fc521ec2a](https://linux-hardware.org/?probe=9fc521ec2a) | Feb 08, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [44eeacc539](https://linux-hardware.org/?probe=44eeacc539) | Feb 08, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [6a3bd80ed5](https://linux-hardware.org/?probe=6a3bd80ed5) | Feb 08, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| HP            | 8350                        | Desktop     | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [c8e90b7e34](https://linux-hardware.org/?probe=c8e90b7e34) | Feb 08, 2022 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [c26f81e381](https://linux-hardware.org/?probe=c26f81e381) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0cc7c7e225](https://linux-hardware.org/?probe=0cc7c7e225) | Feb 08, 2022 |
| Pegatron      | 2A73                        | Desktop     | [c03e3773c2](https://linux-hardware.org/?probe=c03e3773c2) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [09af3e68dd](https://linux-hardware.org/?probe=09af3e68dd) | Feb 07, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [416a8fa0e3](https://linux-hardware.org/?probe=416a8fa0e3) | Feb 07, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [be3458e846](https://linux-hardware.org/?probe=be3458e846) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4cd52923d0](https://linux-hardware.org/?probe=4cd52923d0) | Feb 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [08cbea7180](https://linux-hardware.org/?probe=08cbea7180) | Feb 07, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [db93ace578](https://linux-hardware.org/?probe=db93ace578) | Feb 07, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [c924cab121](https://linux-hardware.org/?probe=c924cab121) | Feb 07, 2022 |
| Lenovo        | ThinkPad X201 3626AT7       | Notebook    | [92b79d9ade](https://linux-hardware.org/?probe=92b79d9ade) | Feb 07, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [3e64e98234](https://linux-hardware.org/?probe=3e64e98234) | Feb 07, 2022 |
| Google        | Pantheon                    | Notebook    | [eebf10f1bb](https://linux-hardware.org/?probe=eebf10f1bb) | Feb 07, 2022 |
| Google        | Pantheon                    | Notebook    | [54f96033d0](https://linux-hardware.org/?probe=54f96033d0) | Feb 07, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [56726f31e3](https://linux-hardware.org/?probe=56726f31e3) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | Desktop     | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | Desktop     | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Dell          | G5 5587                     | Notebook    | [33819e0316](https://linux-hardware.org/?probe=33819e0316) | Feb 06, 2022 |
| Dell          | G5 5587                     | Notebook    | [6fcaa54ab0](https://linux-hardware.org/?probe=6fcaa54ab0) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [da3b8d9778](https://linux-hardware.org/?probe=da3b8d9778) | Feb 06, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [a5db2b8436](https://linux-hardware.org/?probe=a5db2b8436) | Feb 06, 2022 |
| ASUSTek       | Puffer                      | Desktop     | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [dc86c1f5d5](https://linux-hardware.org/?probe=dc86c1f5d5) | Feb 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b9d4efb68c](https://linux-hardware.org/?probe=b9d4efb68c) | Feb 05, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ace4bb0837](https://linux-hardware.org/?probe=ace4bb0837) | Feb 05, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [beeb5ea0d7](https://linux-hardware.org/?probe=beeb5ea0d7) | Feb 05, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [7ca305cd80](https://linux-hardware.org/?probe=7ca305cd80) | Feb 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [63f2430481](https://linux-hardware.org/?probe=63f2430481) | Feb 05, 2022 |
| Acer          | Aspire 5551                 | Notebook    | [9287291d62](https://linux-hardware.org/?probe=9287291d62) | Feb 04, 2022 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [2423cfbdf7](https://linux-hardware.org/?probe=2423cfbdf7) | Feb 04, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [3fc3a14ef3](https://linux-hardware.org/?probe=3fc3a14ef3) | Feb 04, 2022 |
| HP            | 8703                        | Desktop     | [11bdfccc66](https://linux-hardware.org/?probe=11bdfccc66) | Feb 04, 2022 |
| Dell          | 0KCKR5 A02                  | Server      | [3a287683dc](https://linux-hardware.org/?probe=3a287683dc) | Feb 04, 2022 |
| Dell          | 0FRVY0 A00                  | Server      | [c8d2d41009](https://linux-hardware.org/?probe=c8d2d41009) | Feb 04, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [cd72b4c75e](https://linux-hardware.org/?probe=cd72b4c75e) | Feb 04, 2022 |
| TYAN Compu... | S5207                       | Desktop     | [421dcad166](https://linux-hardware.org/?probe=421dcad166) | Feb 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [38b8a1408d](https://linux-hardware.org/?probe=38b8a1408d) | Feb 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [5ed9b5b2b8](https://linux-hardware.org/?probe=5ed9b5b2b8) | Feb 04, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [5828b467b9](https://linux-hardware.org/?probe=5828b467b9) | Feb 04, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [748e3fae6c](https://linux-hardware.org/?probe=748e3fae6c) | Feb 04, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [dc54fcc2ff](https://linux-hardware.org/?probe=dc54fcc2ff) | Feb 04, 2022 |
| Google        | Banon                       | Notebook    | [66f185fafb](https://linux-hardware.org/?probe=66f185fafb) | Feb 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [28544c13f5](https://linux-hardware.org/?probe=28544c13f5) | Feb 04, 2022 |
| Google        | Banon                       | Notebook    | [be4603cd8a](https://linux-hardware.org/?probe=be4603cd8a) | Feb 03, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [61f97dad6e](https://linux-hardware.org/?probe=61f97dad6e) | Feb 03, 2022 |
| Dell          | 0TP406                      | Desktop     | [0f9ee9945c](https://linux-hardware.org/?probe=0f9ee9945c) | Feb 03, 2022 |
| MSI           | 0A48                        | Desktop     | [aeacbf4016](https://linux-hardware.org/?probe=aeacbf4016) | Feb 03, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [0bd2b97304](https://linux-hardware.org/?probe=0bd2b97304) | Feb 03, 2022 |
| Teclast       | F7S                         | Notebook    | [352c4a7941](https://linux-hardware.org/?probe=352c4a7941) | Feb 03, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [447e92a014](https://linux-hardware.org/?probe=447e92a014) | Feb 03, 2022 |
| MSI           | 0A48                        | Desktop     | [2a0ede94bd](https://linux-hardware.org/?probe=2a0ede94bd) | Feb 03, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [99abdcb1fe](https://linux-hardware.org/?probe=99abdcb1fe) | Feb 02, 2022 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| HP            | ProLiant DL160 G6           | Server      | [537e8d34b7](https://linux-hardware.org/?probe=537e8d34b7) | Feb 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [5f664815d0](https://linux-hardware.org/?probe=5f664815d0) | Feb 02, 2022 |
| Lenovo        | ThinkPad R61e 7649AL6       | Notebook    | [e7595e9b45](https://linux-hardware.org/?probe=e7595e9b45) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | Notebook    | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [93bb9c8e78](https://linux-hardware.org/?probe=93bb9c8e78) | Feb 01, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7db720ba39](https://linux-hardware.org/?probe=7db720ba39) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Toshiba       | Satellite Pro R850          | Notebook    | [8d5f88157a](https://linux-hardware.org/?probe=8d5f88157a) | Feb 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [7ea7ab684e](https://linux-hardware.org/?probe=7ea7ab684e) | Feb 01, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [3671be5b6a](https://linux-hardware.org/?probe=3671be5b6a) | Jan 31, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [1835f9c2d4](https://linux-hardware.org/?probe=1835f9c2d4) | Jan 31, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [8d478b1936](https://linux-hardware.org/?probe=8d478b1936) | Jan 31, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [83f9f7b941](https://linux-hardware.org/?probe=83f9f7b941) | Jan 31, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [a44843be2c](https://linux-hardware.org/?probe=a44843be2c) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| AVITA         | NS14A6                      | Notebook    | [bbf5494b7f](https://linux-hardware.org/?probe=bbf5494b7f) | Jan 30, 2022 |
| AVITA         | NS14A6                      | Notebook    | [5cb93a7ead](https://linux-hardware.org/?probe=5cb93a7ead) | Jan 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da8754f5d5](https://linux-hardware.org/?probe=da8754f5d5) | Jan 30, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a72ab8595e](https://linux-hardware.org/?probe=a72ab8595e) | Jan 30, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [87a19ca6bd](https://linux-hardware.org/?probe=87a19ca6bd) | Jan 30, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | Notebook    | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [625e78374f](https://linux-hardware.org/?probe=625e78374f) | Jan 29, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d06c6f8577](https://linux-hardware.org/?probe=d06c6f8577) | Jan 29, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [27250b902e](https://linux-hardware.org/?probe=27250b902e) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| GPD           | G1621-02                    | Notebook    | [7bc0adb6d3](https://linux-hardware.org/?probe=7bc0adb6d3) | Jan 28, 2022 |
| Acer          | Aspire Z5610                | All in one  | [9b77a999c4](https://linux-hardware.org/?probe=9b77a999c4) | Jan 28, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [bd70dabde4](https://linux-hardware.org/?probe=bd70dabde4) | Jan 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [49f803336e](https://linux-hardware.org/?probe=49f803336e) | Jan 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [aa8f4035b5](https://linux-hardware.org/?probe=aa8f4035b5) | Jan 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0b68e07d9b](https://linux-hardware.org/?probe=0b68e07d9b) | Jan 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c83a519db9](https://linux-hardware.org/?probe=c83a519db9) | Jan 27, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [6a8c5526f8](https://linux-hardware.org/?probe=6a8c5526f8) | Jan 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [bb36894a2c](https://linux-hardware.org/?probe=bb36894a2c) | Jan 27, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [c7bf1e2cab](https://linux-hardware.org/?probe=c7bf1e2cab) | Jan 26, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [38afcc5ebd](https://linux-hardware.org/?probe=38afcc5ebd) | Jan 26, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [11d9c59e44](https://linux-hardware.org/?probe=11d9c59e44) | Jan 26, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [a91c7ce0bd](https://linux-hardware.org/?probe=a91c7ce0bd) | Jan 26, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [e2a82eff7e](https://linux-hardware.org/?probe=e2a82eff7e) | Jan 26, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [c6c0f18149](https://linux-hardware.org/?probe=c6c0f18149) | Jan 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2ea8885694](https://linux-hardware.org/?probe=2ea8885694) | Jan 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f31c2dda65](https://linux-hardware.org/?probe=f31c2dda65) | Jan 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [ef096190b6](https://linux-hardware.org/?probe=ef096190b6) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0b57afd8bf](https://linux-hardware.org/?probe=0b57afd8bf) | Jan 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [e3308423e5](https://linux-hardware.org/?probe=e3308423e5) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [12e94e5413](https://linux-hardware.org/?probe=12e94e5413) | Jan 25, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [47e447f5da](https://linux-hardware.org/?probe=47e447f5da) | Jan 25, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [fe61272ae2](https://linux-hardware.org/?probe=fe61272ae2) | Jan 25, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [f9a8d0f268](https://linux-hardware.org/?probe=f9a8d0f268) | Jan 25, 2022 |
| ASUSTek       | PN50-E1                     | Mini pc     | [aafd5f07b5](https://linux-hardware.org/?probe=aafd5f07b5) | Jan 25, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e53b358176](https://linux-hardware.org/?probe=e53b358176) | Jan 25, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [f4ad8a6220](https://linux-hardware.org/?probe=f4ad8a6220) | Jan 25, 2022 |
| HP            | 83E2                        | Desktop     | [1f0f221e5b](https://linux-hardware.org/?probe=1f0f221e5b) | Jan 24, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [d914fce08c](https://linux-hardware.org/?probe=d914fce08c) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [269d1509c2](https://linux-hardware.org/?probe=269d1509c2) | Jan 24, 2022 |
| Dell          | Latitude D531               | Notebook    | [e9e8fa864a](https://linux-hardware.org/?probe=e9e8fa864a) | Jan 24, 2022 |
| Unknown       | Unknown                     | Soc         | [4320623bd1](https://linux-hardware.org/?probe=4320623bd1) | Jan 24, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [7cb75a1cf3](https://linux-hardware.org/?probe=7cb75a1cf3) | Jan 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7986235186](https://linux-hardware.org/?probe=7986235186) | Jan 23, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [65ce5265d3](https://linux-hardware.org/?probe=65ce5265d3) | Jan 23, 2022 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [f9fd02faac](https://linux-hardware.org/?probe=f9fd02faac) | Jan 23, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [ed1ec29d64](https://linux-hardware.org/?probe=ed1ec29d64) | Jan 23, 2022 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [47e812ac04](https://linux-hardware.org/?probe=47e812ac04) | Jan 23, 2022 |
| Acer          | Aspire A615-51              | Notebook    | [a7cd7b1960](https://linux-hardware.org/?probe=a7cd7b1960) | Jan 23, 2022 |
| ASUSTek       | X450LD                      | Notebook    | [07edc503a1](https://linux-hardware.org/?probe=07edc503a1) | Jan 23, 2022 |
| Acer          | Aspire 8935G                | Notebook    | [a1b815e026](https://linux-hardware.org/?probe=a1b815e026) | Jan 23, 2022 |
| HP            | 1495                        | Desktop     | [11a5c09560](https://linux-hardware.org/?probe=11a5c09560) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [619ebd38aa](https://linux-hardware.org/?probe=619ebd38aa) | Jan 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [cfb12999e8](https://linux-hardware.org/?probe=cfb12999e8) | Jan 23, 2022 |
| Unknown       | Intel X79                   | Desktop     | [7d1ab99839](https://linux-hardware.org/?probe=7d1ab99839) | Jan 23, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [05d9d96be4](https://linux-hardware.org/?probe=05d9d96be4) | Jan 23, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [157ee8c8d9](https://linux-hardware.org/?probe=157ee8c8d9) | Jan 23, 2022 |
| Alienware     | 17 R4                       | Notebook    | [d82171f734](https://linux-hardware.org/?probe=d82171f734) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [8cf6949b05](https://linux-hardware.org/?probe=8cf6949b05) | Jan 22, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c18fa2fa99](https://linux-hardware.org/?probe=c18fa2fa99) | Jan 22, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [b8b6a312b1](https://linux-hardware.org/?probe=b8b6a312b1) | Jan 21, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [f348809f89](https://linux-hardware.org/?probe=f348809f89) | Jan 21, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [42f09fd170](https://linux-hardware.org/?probe=42f09fd170) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [d44da01e91](https://linux-hardware.org/?probe=d44da01e91) | Jan 20, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [04926d5643](https://linux-hardware.org/?probe=04926d5643) | Jan 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4eeedfe547](https://linux-hardware.org/?probe=4eeedfe547) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [29fd90e072](https://linux-hardware.org/?probe=29fd90e072) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [a75addb4d5](https://linux-hardware.org/?probe=a75addb4d5) | Jan 18, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [1af13788c5](https://linux-hardware.org/?probe=1af13788c5) | Jan 18, 2022 |
| Jumper        | EZbook                      | Notebook    | [c6f783a8ad](https://linux-hardware.org/?probe=c6f783a8ad) | Jan 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [f476b26c5b](https://linux-hardware.org/?probe=f476b26c5b) | Jan 17, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [005887e692](https://linux-hardware.org/?probe=005887e692) | Jan 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | 86EE                        | All in one  | [b200dc3d0f](https://linux-hardware.org/?probe=b200dc3d0f) | Jan 17, 2022 |
| HP            | 3032h                       | Desktop     | [a7e9e3a024](https://linux-hardware.org/?probe=a7e9e3a024) | Jan 16, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f7e362d977](https://linux-hardware.org/?probe=f7e362d977) | Jan 16, 2022 |
| Lenovo        | ThinkPad X1 Tablet 20GHC... | Tablet      | [923ccb09a5](https://linux-hardware.org/?probe=923ccb09a5) | Jan 16, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Microsoft     | Surface Go 2                | Tablet      | [e530d905da](https://linux-hardware.org/?probe=e530d905da) | Jan 16, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [b59d482466](https://linux-hardware.org/?probe=b59d482466) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| Toshiba       | EQUIUM P200D                | Notebook    | [b28ab84bf8](https://linux-hardware.org/?probe=b28ab84bf8) | Jan 15, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [142bc361ba](https://linux-hardware.org/?probe=142bc361ba) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [dae8d10589](https://linux-hardware.org/?probe=dae8d10589) | Jan 15, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5d9e7dcdd1](https://linux-hardware.org/?probe=5d9e7dcdd1) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [fb799bb9f5](https://linux-hardware.org/?probe=fb799bb9f5) | Jan 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [80fb337bde](https://linux-hardware.org/?probe=80fb337bde) | Jan 15, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [30309c0416](https://linux-hardware.org/?probe=30309c0416) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [cc3a8808e7](https://linux-hardware.org/?probe=cc3a8808e7) | Jan 15, 2022 |
| LG Electro... | 16Z90P-K.AA72A1             | Notebook    | [5c76ea5424](https://linux-hardware.org/?probe=5c76ea5424) | Jan 15, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [fdac2f87fe](https://linux-hardware.org/?probe=fdac2f87fe) | Jan 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [fb9ba11b01](https://linux-hardware.org/?probe=fb9ba11b01) | Jan 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [8ee9c2f3fe](https://linux-hardware.org/?probe=8ee9c2f3fe) | Jan 14, 2022 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [7de1f8971f](https://linux-hardware.org/?probe=7de1f8971f) | Jan 14, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [ae9f25c32f](https://linux-hardware.org/?probe=ae9f25c32f) | Jan 14, 2022 |
| Dell          | Latitude D620               | Notebook    | [a43c35d2fa](https://linux-hardware.org/?probe=a43c35d2fa) | Jan 14, 2022 |
| MSI           | MS-B0961                    | All in one  | [de1e024cad](https://linux-hardware.org/?probe=de1e024cad) | Jan 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f11276b7a0](https://linux-hardware.org/?probe=f11276b7a0) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| ASUSTek       | K54C                        | Notebook    | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [766bd5092b](https://linux-hardware.org/?probe=766bd5092b) | Jan 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [c7567b5c29](https://linux-hardware.org/?probe=c7567b5c29) | Jan 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [b2621747db](https://linux-hardware.org/?probe=b2621747db) | Jan 13, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6e5a2e29f4](https://linux-hardware.org/?probe=6e5a2e29f4) | Jan 12, 2022 |
| Nvidia        | Tegra                       | Soc         | [71cf155467](https://linux-hardware.org/?probe=71cf155467) | Jan 12, 2022 |
| Intel         | DQ57TM AAE92694-400         | Desktop     | [59ef421003](https://linux-hardware.org/?probe=59ef421003) | Jan 12, 2022 |
| Dell          | 0PU052                      | Desktop     | [5eab76d857](https://linux-hardware.org/?probe=5eab76d857) | Jan 12, 2022 |
| Packard Be... | EG43M                       | Desktop     | [bd7097f415](https://linux-hardware.org/?probe=bd7097f415) | Jan 12, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [dc2a5d2e53](https://linux-hardware.org/?probe=dc2a5d2e53) | Jan 12, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [07ead176f9](https://linux-hardware.org/?probe=07ead176f9) | Jan 12, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4168195256](https://linux-hardware.org/?probe=4168195256) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| Dell          | Latitude 3410               | Notebook    | [f9933fb000](https://linux-hardware.org/?probe=f9933fb000) | Jan 11, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [79eb4b2eee](https://linux-hardware.org/?probe=79eb4b2eee) | Jan 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [80f69f0294](https://linux-hardware.org/?probe=80f69f0294) | Jan 11, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a7be44496a](https://linux-hardware.org/?probe=a7be44496a) | Jan 11, 2022 |
| HP            | G70                         | Notebook    | [5db05fe4eb](https://linux-hardware.org/?probe=5db05fe4eb) | Jan 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1e31796586](https://linux-hardware.org/?probe=1e31796586) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [63db2e4ecc](https://linux-hardware.org/?probe=63db2e4ecc) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [132d4e0b47](https://linux-hardware.org/?probe=132d4e0b47) | Jan 10, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [9683b70727](https://linux-hardware.org/?probe=9683b70727) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [bb8e7fc409](https://linux-hardware.org/?probe=bb8e7fc409) | Jan 10, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [e3e7fc8951](https://linux-hardware.org/?probe=e3e7fc8951) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Dell          | Latitude E6320              | Notebook    | [0e34f6fd45](https://linux-hardware.org/?probe=0e34f6fd45) | Jan 10, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [d537e0bc35](https://linux-hardware.org/?probe=d537e0bc35) | Jan 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [4bfe339a98](https://linux-hardware.org/?probe=4bfe339a98) | Jan 09, 2022 |
| Lenovo        | ThinkPad T570 20HAS11J00    | Notebook    | [8bcfe1042a](https://linux-hardware.org/?probe=8bcfe1042a) | Jan 09, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [34303e2252](https://linux-hardware.org/?probe=34303e2252) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [2fa8f23cb9](https://linux-hardware.org/?probe=2fa8f23cb9) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [a0b1a9f1d3](https://linux-hardware.org/?probe=a0b1a9f1d3) | Jan 09, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [dc2e38d1ed](https://linux-hardware.org/?probe=dc2e38d1ed) | Jan 09, 2022 |
| Acer          | Aspire 5551                 | Notebook    | [ce439720ef](https://linux-hardware.org/?probe=ce439720ef) | Jan 09, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [e5f97aa1fb](https://linux-hardware.org/?probe=e5f97aa1fb) | Jan 09, 2022 |
| ASUSTek       | Commando                    | Desktop     | [8ce355c181](https://linux-hardware.org/?probe=8ce355c181) | Jan 09, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [4f96e12143](https://linux-hardware.org/?probe=4f96e12143) | Jan 09, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [66a67c86af](https://linux-hardware.org/?probe=66a67c86af) | Jan 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f48dc8b412](https://linux-hardware.org/?probe=f48dc8b412) | Jan 08, 2022 |
| ASUSTek       | Commando                    | Desktop     | [e06fe58b34](https://linux-hardware.org/?probe=e06fe58b34) | Jan 08, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [31dca40457](https://linux-hardware.org/?probe=31dca40457) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| HP            | 81BB                        | All in one  | [516f843813](https://linux-hardware.org/?probe=516f843813) | Jan 08, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b5fbd6f1c9](https://linux-hardware.org/?probe=b5fbd6f1c9) | Jan 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4e21fb8625](https://linux-hardware.org/?probe=4e21fb8625) | Jan 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a6b32b67b4](https://linux-hardware.org/?probe=a6b32b67b4) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a23bb3d2c0](https://linux-hardware.org/?probe=a23bb3d2c0) | Jan 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d3bd574234](https://linux-hardware.org/?probe=d3bd574234) | Jan 07, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [5c63b79779](https://linux-hardware.org/?probe=5c63b79779) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [0106ee2bda](https://linux-hardware.org/?probe=0106ee2bda) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f09949e50f](https://linux-hardware.org/?probe=f09949e50f) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faffa9ba50](https://linux-hardware.org/?probe=faffa9ba50) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Samsung       | R530/R730                   | Notebook    | [d07e567173](https://linux-hardware.org/?probe=d07e567173) | Jan 07, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5cec5778a0](https://linux-hardware.org/?probe=5cec5778a0) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Lenovo        | ThinkPad L380 20M6S1VV00    | Notebook    | [bc4fe37053](https://linux-hardware.org/?probe=bc4fe37053) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [affb3b3f70](https://linux-hardware.org/?probe=affb3b3f70) | Jan 06, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [b1fe0d9671](https://linux-hardware.org/?probe=b1fe0d9671) | Jan 06, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [b5ab89a508](https://linux-hardware.org/?probe=b5ab89a508) | Jan 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [753514265b](https://linux-hardware.org/?probe=753514265b) | Jan 05, 2022 |
| HP            | Pavilion x2 Detachable      | Notebook    | [7b43e5d7fd](https://linux-hardware.org/?probe=7b43e5d7fd) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| Dell          | Latitude E6520              | Notebook    | [39a940ae21](https://linux-hardware.org/?probe=39a940ae21) | Jan 05, 2022 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [0e14f8a417](https://linux-hardware.org/?probe=0e14f8a417) | Jan 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2bcd672c37](https://linux-hardware.org/?probe=2bcd672c37) | Jan 04, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [c7f2471bdf](https://linux-hardware.org/?probe=c7f2471bdf) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | Notebook    | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [e88914bd49](https://linux-hardware.org/?probe=e88914bd49) | Jan 04, 2022 |
| Fujitsu       | D3446-S1 S26361-D3446-S1    | Desktop     | [8b38b529e9](https://linux-hardware.org/?probe=8b38b529e9) | Jan 03, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| HP            | Pavilion x2 Detachable      | Notebook    | [db6b6f9863](https://linux-hardware.org/?probe=db6b6f9863) | Jan 03, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [fcdc25fdc9](https://linux-hardware.org/?probe=fcdc25fdc9) | Jan 03, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [08864b62d7](https://linux-hardware.org/?probe=08864b62d7) | Jan 03, 2022 |
| Dell          | Latitude E5440              | Notebook    | [16fbe4c9c0](https://linux-hardware.org/?probe=16fbe4c9c0) | Jan 03, 2022 |
| Unknown       | Intel X79                   | Desktop     | [eb2d09ced7](https://linux-hardware.org/?probe=eb2d09ced7) | Jan 03, 2022 |
| Unknown       | Intel X79                   | Desktop     | [a8698b6f96](https://linux-hardware.org/?probe=a8698b6f96) | Jan 03, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f159c9804a](https://linux-hardware.org/?probe=f159c9804a) | Jan 03, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDA03... | Notebook    | [59a73a8864](https://linux-hardware.org/?probe=59a73a8864) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Acer          | FMCP7AM                     | Desktop     | [cd1463cb99](https://linux-hardware.org/?probe=cd1463cb99) | Jan 02, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [bcc27ef54b](https://linux-hardware.org/?probe=bcc27ef54b) | Jan 02, 2022 |
| Google        | Rammus                      | Notebook    | [aa3b26a209](https://linux-hardware.org/?probe=aa3b26a209) | Jan 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f483ddc44f](https://linux-hardware.org/?probe=f483ddc44f) | Jan 01, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [4c8824cb05](https://linux-hardware.org/?probe=4c8824cb05) | Jan 01, 2022 |
| ASUSTek       | G771JMC                     | Notebook    | [8a937cb99d](https://linux-hardware.org/?probe=8a937cb99d) | Jan 01, 2022 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [46c8424272](https://linux-hardware.org/?probe=46c8424272) | Dec 31, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [9ab20c3fde](https://linux-hardware.org/?probe=9ab20c3fde) | Dec 31, 2021 |
| Acer          | Aspire 5920                 | Notebook    | [b492dec09b](https://linux-hardware.org/?probe=b492dec09b) | Dec 31, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [c599a26a65](https://linux-hardware.org/?probe=c599a26a65) | Dec 31, 2021 |
| ASRock        | A75M-HVS                    | Desktop     | [d77bbe23b5](https://linux-hardware.org/?probe=d77bbe23b5) | Dec 30, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [7e02c5721d](https://linux-hardware.org/?probe=7e02c5721d) | Dec 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4c4cc2921d](https://linux-hardware.org/?probe=4c4cc2921d) | Dec 30, 2021 |
| Google        | Chell                       | Notebook    | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [a1a074beba](https://linux-hardware.org/?probe=a1a074beba) | Dec 30, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [7a52d24e53](https://linux-hardware.org/?probe=7a52d24e53) | Dec 30, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [c3973e2439](https://linux-hardware.org/?probe=c3973e2439) | Dec 30, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [9be23e2b2d](https://linux-hardware.org/?probe=9be23e2b2d) | Dec 30, 2021 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [3088a2d8ad](https://linux-hardware.org/?probe=3088a2d8ad) | Dec 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9e39899ddf](https://linux-hardware.org/?probe=9e39899ddf) | Dec 29, 2021 |
| Dell          | Inspiron 1720               | Notebook    | [b40685ea7b](https://linux-hardware.org/?probe=b40685ea7b) | Dec 29, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [6d7c53d047](https://linux-hardware.org/?probe=6d7c53d047) | Dec 29, 2021 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [121b6af376](https://linux-hardware.org/?probe=121b6af376) | Dec 29, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [80d5326578](https://linux-hardware.org/?probe=80d5326578) | Dec 29, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [14038ff02e](https://linux-hardware.org/?probe=14038ff02e) | Dec 28, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [d2cec18342](https://linux-hardware.org/?probe=d2cec18342) | Dec 28, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [d31b2036c2](https://linux-hardware.org/?probe=d31b2036c2) | Dec 28, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [4cce063737](https://linux-hardware.org/?probe=4cce063737) | Dec 28, 2021 |
| Dell          | Latitude E7470              | Notebook    | [55e3078baf](https://linux-hardware.org/?probe=55e3078baf) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [54c076eb59](https://linux-hardware.org/?probe=54c076eb59) | Dec 28, 2021 |
| HP            | 255 G5                      | Notebook    | [0bf7bc5435](https://linux-hardware.org/?probe=0bf7bc5435) | Dec 28, 2021 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [9189d1790a](https://linux-hardware.org/?probe=9189d1790a) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34c9874e50](https://linux-hardware.org/?probe=34c9874e50) | Dec 27, 2021 |
| Acer          | Aspire 5680                 | Notebook    | [3d8d482ea9](https://linux-hardware.org/?probe=3d8d482ea9) | Dec 27, 2021 |
| Acer          | Aspire 5680                 | Notebook    | [792445969b](https://linux-hardware.org/?probe=792445969b) | Dec 27, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | Notebook    | [c7612aac66](https://linux-hardware.org/?probe=c7612aac66) | Dec 26, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [f37b55a91b](https://linux-hardware.org/?probe=f37b55a91b) | Dec 26, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [052954142f](https://linux-hardware.org/?probe=052954142f) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [588620e35b](https://linux-hardware.org/?probe=588620e35b) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | Notebook    | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ff2ee90fee](https://linux-hardware.org/?probe=ff2ee90fee) | Dec 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6c56118d24](https://linux-hardware.org/?probe=6c56118d24) | Dec 25, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [88241722a5](https://linux-hardware.org/?probe=88241722a5) | Dec 25, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [d149e3e8cd](https://linux-hardware.org/?probe=d149e3e8cd) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [93e3145404](https://linux-hardware.org/?probe=93e3145404) | Dec 24, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [459f0e8c25](https://linux-hardware.org/?probe=459f0e8c25) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d971e22ea1](https://linux-hardware.org/?probe=d971e22ea1) | Dec 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [73cfb1d650](https://linux-hardware.org/?probe=73cfb1d650) | Dec 24, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [b3c9fc74c9](https://linux-hardware.org/?probe=b3c9fc74c9) | Dec 24, 2021 |
| HP            | ZBook 14 G2                 | Notebook    | [65796f1946](https://linux-hardware.org/?probe=65796f1946) | Dec 24, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [f84bf4846c](https://linux-hardware.org/?probe=f84bf4846c) | Dec 24, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [a4f7e27b61](https://linux-hardware.org/?probe=a4f7e27b61) | Dec 24, 2021 |
| Dell          | 0WF810                      | Desktop     | [77db7ecb38](https://linux-hardware.org/?probe=77db7ecb38) | Dec 23, 2021 |
| Sun Micros... | Sun Fire X2270 M2 375-36... | Server      | [f2e3845822](https://linux-hardware.org/?probe=f2e3845822) | Dec 23, 2021 |
| Dell          | Inspiron 1720               | Notebook    | [6d1e22e244](https://linux-hardware.org/?probe=6d1e22e244) | Dec 23, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [c658d7097b](https://linux-hardware.org/?probe=c658d7097b) | Dec 23, 2021 |
| ASRock        | H97 Killer                  | Desktop     | [c1b79b60e8](https://linux-hardware.org/?probe=c1b79b60e8) | Dec 23, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [8bb2ad2c01](https://linux-hardware.org/?probe=8bb2ad2c01) | Dec 23, 2021 |
| Dell          | Latitude E5540              | Notebook    | [e289fc7147](https://linux-hardware.org/?probe=e289fc7147) | Dec 23, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [4658d07ba2](https://linux-hardware.org/?probe=4658d07ba2) | Dec 23, 2021 |
| Pegatron      | Maureen                     | Desktop     | [4bb6b10ba4](https://linux-hardware.org/?probe=4bb6b10ba4) | Dec 23, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [efdf9bd8ec](https://linux-hardware.org/?probe=efdf9bd8ec) | Dec 23, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [482842307e](https://linux-hardware.org/?probe=482842307e) | Dec 23, 2021 |
| Advent        | Monza T100                  | Notebook    | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9dbb92d3c](https://linux-hardware.org/?probe=b9dbb92d3c) | Dec 22, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [5ce9a3ea6c](https://linux-hardware.org/?probe=5ce9a3ea6c) | Dec 22, 2021 |
| Dell          | Latitude E6230              | Notebook    | [f0372edeb0](https://linux-hardware.org/?probe=f0372edeb0) | Dec 22, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a955b3649c](https://linux-hardware.org/?probe=a955b3649c) | Dec 22, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [17162c392d](https://linux-hardware.org/?probe=17162c392d) | Dec 22, 2021 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [d883865ac9](https://linux-hardware.org/?probe=d883865ac9) | Dec 22, 2021 |
| Advent        | Tacto Purple                | Notebook    | [ac9fd78933](https://linux-hardware.org/?probe=ac9fd78933) | Dec 22, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [95f5a7b84d](https://linux-hardware.org/?probe=95f5a7b84d) | Dec 22, 2021 |
| Dell          | Latitude E6230              | Notebook    | [686fb1e16d](https://linux-hardware.org/?probe=686fb1e16d) | Dec 22, 2021 |
| HP            | 2820h                       | Desktop     | [3e0046043f](https://linux-hardware.org/?probe=3e0046043f) | Dec 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [08b6d29632](https://linux-hardware.org/?probe=08b6d29632) | Dec 21, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [e76b0dc53f](https://linux-hardware.org/?probe=e76b0dc53f) | Dec 21, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [8f7a53f316](https://linux-hardware.org/?probe=8f7a53f316) | Dec 20, 2021 |
| Dell          | G7 7700                     | Notebook    | [4d9c5113e2](https://linux-hardware.org/?probe=4d9c5113e2) | Dec 20, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| Dell          | G7 7700                     | Notebook    | [58e0b0cb22](https://linux-hardware.org/?probe=58e0b0cb22) | Dec 20, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [95a47ab984](https://linux-hardware.org/?probe=95a47ab984) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| HP            | Pavilion dv3                | Notebook    | [8a8a99eb2e](https://linux-hardware.org/?probe=8a8a99eb2e) | Dec 19, 2021 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [6a0d90696f](https://linux-hardware.org/?probe=6a0d90696f) | Dec 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bfc5e45295](https://linux-hardware.org/?probe=bfc5e45295) | Dec 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [184202cc4e](https://linux-hardware.org/?probe=184202cc4e) | Dec 19, 2021 |
| HP            | Pavilion 15                 | Notebook    | [809e8e53b8](https://linux-hardware.org/?probe=809e8e53b8) | Dec 19, 2021 |
| HP            | 1496                        | Desktop     | [c7f2e6586c](https://linux-hardware.org/?probe=c7f2e6586c) | Dec 19, 2021 |
| Dell          | 014GRG A03                  | Desktop     | [15c2ba91b7](https://linux-hardware.org/?probe=15c2ba91b7) | Dec 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [25c7dd18f2](https://linux-hardware.org/?probe=25c7dd18f2) | Dec 19, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [515a90b57b](https://linux-hardware.org/?probe=515a90b57b) | Dec 18, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [ab1b144f72](https://linux-hardware.org/?probe=ab1b144f72) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [615adeaed3](https://linux-hardware.org/?probe=615adeaed3) | Dec 18, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [28533baa5a](https://linux-hardware.org/?probe=28533baa5a) | Dec 18, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1a6d1fc80e](https://linux-hardware.org/?probe=1a6d1fc80e) | Dec 18, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [75aec07ed3](https://linux-hardware.org/?probe=75aec07ed3) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | Notebook    | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| Gigabyte      | P17FR5                      | Notebook    | [5259f024b4](https://linux-hardware.org/?probe=5259f024b4) | Dec 17, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [5ae44ae2be](https://linux-hardware.org/?probe=5ae44ae2be) | Dec 17, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [03ba4058db](https://linux-hardware.org/?probe=03ba4058db) | Dec 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [92071ce7a4](https://linux-hardware.org/?probe=92071ce7a4) | Dec 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [444737e990](https://linux-hardware.org/?probe=444737e990) | Dec 17, 2021 |
| Xunlong       | Orange Pi PC                | Soc         | [e112a02e93](https://linux-hardware.org/?probe=e112a02e93) | Dec 16, 2021 |
| Dell          | G5 5590                     | Notebook    | [b628b14dea](https://linux-hardware.org/?probe=b628b14dea) | Dec 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a77249c08b](https://linux-hardware.org/?probe=a77249c08b) | Dec 16, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [0fca0b679f](https://linux-hardware.org/?probe=0fca0b679f) | Dec 16, 2021 |
| ASUSTek       | K54L                        | Notebook    | [335a4179a6](https://linux-hardware.org/?probe=335a4179a6) | Dec 16, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | Desktop     | [7d11758943](https://linux-hardware.org/?probe=7d11758943) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ce1e47fdc8](https://linux-hardware.org/?probe=ce1e47fdc8) | Dec 16, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [3a5c1ae641](https://linux-hardware.org/?probe=3a5c1ae641) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2633be8cd](https://linux-hardware.org/?probe=e2633be8cd) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| PC Special... | TN1-156M                    | Notebook    | [979cb58b29](https://linux-hardware.org/?probe=979cb58b29) | Dec 15, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [da8c18883d](https://linux-hardware.org/?probe=da8c18883d) | Dec 15, 2021 |
| Dell          | 042P49 A01                  | Desktop     | [631c0da1c5](https://linux-hardware.org/?probe=631c0da1c5) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [3a62e5502b](https://linux-hardware.org/?probe=3a62e5502b) | Dec 15, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7d61b680b2](https://linux-hardware.org/?probe=7d61b680b2) | Dec 15, 2021 |
| ASUSTek       | K53E                        | Notebook    | [d6bec520cd](https://linux-hardware.org/?probe=d6bec520cd) | Dec 15, 2021 |
| ASUSTek       | PN51-E1                     | Mini pc     | [23354fdfc7](https://linux-hardware.org/?probe=23354fdfc7) | Dec 15, 2021 |
| HP            | 18E5                        | Desktop     | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [36ce439bef](https://linux-hardware.org/?probe=36ce439bef) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| Lenovo        | ThinkPad L440 20ASA15T00    | Notebook    | [65db46eac3](https://linux-hardware.org/?probe=65db46eac3) | Dec 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6211226c2e](https://linux-hardware.org/?probe=6211226c2e) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [e32681daca](https://linux-hardware.org/?probe=e32681daca) | Dec 13, 2021 |
| ASUSTek       | UL30A                       | Notebook    | [3f3677f6ee](https://linux-hardware.org/?probe=3f3677f6ee) | Dec 13, 2021 |
| ASUSTek       | N3050T                      | Desktop     | [e7cdbc085c](https://linux-hardware.org/?probe=e7cdbc085c) | Dec 13, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a3082eef5](https://linux-hardware.org/?probe=4a3082eef5) | Dec 13, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [28e1968e2a](https://linux-hardware.org/?probe=28e1968e2a) | Dec 13, 2021 |
| HP            | 18E9                        | Desktop     | [870f4a67a7](https://linux-hardware.org/?probe=870f4a67a7) | Dec 13, 2021 |
| HP            | Elite Dragonfly             | Convertible | [d25e8dec93](https://linux-hardware.org/?probe=d25e8dec93) | Dec 13, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [e8a44e7fb4](https://linux-hardware.org/?probe=e8a44e7fb4) | Dec 12, 2021 |
| Dell          | G7 7700                     | Notebook    | [5814c7f594](https://linux-hardware.org/?probe=5814c7f594) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Packard Be... | IMEDIA S2185                | Desktop     | [26f91db3d6](https://linux-hardware.org/?probe=26f91db3d6) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [981dc4e673](https://linux-hardware.org/?probe=981dc4e673) | Dec 12, 2021 |
| OBSIDIAN-P... | P65xHP                      | Notebook    | [73bbe1f2d5](https://linux-hardware.org/?probe=73bbe1f2d5) | Dec 12, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [d08ae710bd](https://linux-hardware.org/?probe=d08ae710bd) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [df25f864d4](https://linux-hardware.org/?probe=df25f864d4) | Dec 11, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [862776d0cd](https://linux-hardware.org/?probe=862776d0cd) | Dec 11, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [25566e4f44](https://linux-hardware.org/?probe=25566e4f44) | Dec 11, 2021 |
| Dell          | Latitude E5400              | Notebook    | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [34dacc4911](https://linux-hardware.org/?probe=34dacc4911) | Dec 11, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [433ef01ee4](https://linux-hardware.org/?probe=433ef01ee4) | Dec 11, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1b3b98bfd7](https://linux-hardware.org/?probe=1b3b98bfd7) | Dec 11, 2021 |
| Packard Be... | IMEDIA S3810                | Desktop     | [f8085b1034](https://linux-hardware.org/?probe=f8085b1034) | Dec 11, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [2ab5b57cc9](https://linux-hardware.org/?probe=2ab5b57cc9) | Dec 11, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [9d9b833c3a](https://linux-hardware.org/?probe=9d9b833c3a) | Dec 11, 2021 |
| ASUSTek       | T12Eg                       | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| HP            | 620                         | Notebook    | [2bb3a99685](https://linux-hardware.org/?probe=2bb3a99685) | Dec 11, 2021 |
| Dell          | Latitude 7300               | Notebook    | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| Lenovo        | ThinkPad T410 2537Z7A       | Notebook    | [d6ddba3925](https://linux-hardware.org/?probe=d6ddba3925) | Dec 10, 2021 |
| HP            | Pavilion 15                 | Notebook    | [a041b0e713](https://linux-hardware.org/?probe=a041b0e713) | Dec 10, 2021 |
| HP            | Compaq Presario CQ70        | Notebook    | [4bb08207dd](https://linux-hardware.org/?probe=4bb08207dd) | Dec 10, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [36b9025cb3](https://linux-hardware.org/?probe=36b9025cb3) | Dec 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| HP            | 2AE3                        | Desktop     | [097cb47ea8](https://linux-hardware.org/?probe=097cb47ea8) | Dec 10, 2021 |
| HP            | 2AE3                        | Desktop     | [751335e09a](https://linux-hardware.org/?probe=751335e09a) | Dec 10, 2021 |
| Dell          | Latitude E7440              | Notebook    | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [463119e0f9](https://linux-hardware.org/?probe=463119e0f9) | Dec 09, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [8b0a2e2d10](https://linux-hardware.org/?probe=8b0a2e2d10) | Dec 09, 2021 |
| Star Labs     | StarBook                    | Notebook    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [5a0e887e34](https://linux-hardware.org/?probe=5a0e887e34) | Dec 09, 2021 |
| HUAWEI        | HKD-WXX                     | Notebook    | [2e235ec353](https://linux-hardware.org/?probe=2e235ec353) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e7b92397a3](https://linux-hardware.org/?probe=e7b92397a3) | Dec 09, 2021 |
| Dell          | Inspiron 7386               | Convertible | [66e7ddf3f0](https://linux-hardware.org/?probe=66e7ddf3f0) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| MSI           | B365M PLUS                  | Desktop     | [2b5c7216f7](https://linux-hardware.org/?probe=2b5c7216f7) | Dec 08, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [8d99e35e5f](https://linux-hardware.org/?probe=8d99e35e5f) | Dec 08, 2021 |
| HP            | 2AE3                        | Desktop     | [a1cc0f1566](https://linux-hardware.org/?probe=a1cc0f1566) | Dec 08, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [025cafb2b9](https://linux-hardware.org/?probe=025cafb2b9) | Dec 08, 2021 |
| Lenovo        | ThinkPad T410 2537BU1       | Notebook    | [f39903a445](https://linux-hardware.org/?probe=f39903a445) | Dec 08, 2021 |
| Acer          | Aspire E1-530               | Notebook    | [e3ece66b6e](https://linux-hardware.org/?probe=e3ece66b6e) | Dec 08, 2021 |
| MSI           | Z97S SLI PLUS               | Desktop     | [aacfa64783](https://linux-hardware.org/?probe=aacfa64783) | Dec 08, 2021 |
| HP            | 0A60h                       | Desktop     | [e66c5a9a93](https://linux-hardware.org/?probe=e66c5a9a93) | Dec 07, 2021 |
| Dell          | G15 5515                    | Notebook    | [beea6ef657](https://linux-hardware.org/?probe=beea6ef657) | Dec 07, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [4c043a698b](https://linux-hardware.org/?probe=4c043a698b) | Dec 07, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [83e11d1eae](https://linux-hardware.org/?probe=83e11d1eae) | Dec 07, 2021 |
| Toshiba       | Satellite Pro A200          | Notebook    | [29468572fb](https://linux-hardware.org/?probe=29468572fb) | Dec 07, 2021 |
| HP            | 0A9Ch                       | Desktop     | [9bbd755279](https://linux-hardware.org/?probe=9bbd755279) | Dec 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [6c0b436855](https://linux-hardware.org/?probe=6c0b436855) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [8d158d2fb2](https://linux-hardware.org/?probe=8d158d2fb2) | Dec 06, 2021 |
| Samsung       | NC10                        | Notebook    | [323152de74](https://linux-hardware.org/?probe=323152de74) | Dec 06, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| iOTA          | FLO                         | Notebook    | [0331ac814d](https://linux-hardware.org/?probe=0331ac814d) | Dec 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [05538278b6](https://linux-hardware.org/?probe=05538278b6) | Dec 06, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [e9992afde5](https://linux-hardware.org/?probe=e9992afde5) | Dec 06, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [7f5adb4cb3](https://linux-hardware.org/?probe=7f5adb4cb3) | Dec 06, 2021 |
| Dell          | Precision M90               | Notebook    | [2e56447259](https://linux-hardware.org/?probe=2e56447259) | Dec 05, 2021 |
| Fujitsu       | D3446-S1 S26361-D3446-S1    | Desktop     | [077673c895](https://linux-hardware.org/?probe=077673c895) | Dec 05, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [b8b39011ae](https://linux-hardware.org/?probe=b8b39011ae) | Dec 05, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [d16dfb27de](https://linux-hardware.org/?probe=d16dfb27de) | Dec 05, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [d566229da2](https://linux-hardware.org/?probe=d566229da2) | Dec 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e146faa19c](https://linux-hardware.org/?probe=e146faa19c) | Dec 05, 2021 |
| Biostar       | N68S3B                      | Desktop     | [ce45df0214](https://linux-hardware.org/?probe=ce45df0214) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | Notebook    | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [ad8816adfe](https://linux-hardware.org/?probe=ad8816adfe) | Dec 05, 2021 |
| Lenovo        | 3744 WIN SDK0J40700 3258... | All in one  | [b3edfbfee7](https://linux-hardware.org/?probe=b3edfbfee7) | Dec 05, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [b8813e5654](https://linux-hardware.org/?probe=b8813e5654) | Dec 04, 2021 |
| HP            | Pavilion 15                 | Notebook    | [62a93f4abd](https://linux-hardware.org/?probe=62a93f4abd) | Dec 04, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [dc6750fc43](https://linux-hardware.org/?probe=dc6750fc43) | Dec 03, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [8812b5d4fd](https://linux-hardware.org/?probe=8812b5d4fd) | Dec 03, 2021 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [1e7448340f](https://linux-hardware.org/?probe=1e7448340f) | Dec 03, 2021 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [c7f6dbb8de](https://linux-hardware.org/?probe=c7f6dbb8de) | Dec 03, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [77cded600e](https://linux-hardware.org/?probe=77cded600e) | Dec 02, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [7691b4a03e](https://linux-hardware.org/?probe=7691b4a03e) | Dec 02, 2021 |
| Dell          | 0WF810                      | Desktop     | [d943ed3484](https://linux-hardware.org/?probe=d943ed3484) | Dec 02, 2021 |
| ASRock        | H170M-ITX/DL                | Desktop     | [a1583e74ac](https://linux-hardware.org/?probe=a1583e74ac) | Dec 02, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [4201144caa](https://linux-hardware.org/?probe=4201144caa) | Dec 02, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [a22a6ea09a](https://linux-hardware.org/?probe=a22a6ea09a) | Dec 02, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6a8021e535](https://linux-hardware.org/?probe=6a8021e535) | Dec 02, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [bf482fa861](https://linux-hardware.org/?probe=bf482fa861) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [807a8acefd](https://linux-hardware.org/?probe=807a8acefd) | Dec 02, 2021 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [32a7506932](https://linux-hardware.org/?probe=32a7506932) | Dec 01, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [61bcdd744b](https://linux-hardware.org/?probe=61bcdd744b) | Dec 01, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a70cef2501](https://linux-hardware.org/?probe=a70cef2501) | Dec 01, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [9abee94f22](https://linux-hardware.org/?probe=9abee94f22) | Dec 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [876f4598f0](https://linux-hardware.org/?probe=876f4598f0) | Dec 01, 2021 |
| Dell          | Latitude 7280               | Notebook    | [512a0bb958](https://linux-hardware.org/?probe=512a0bb958) | Dec 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [9aafaab56e](https://linux-hardware.org/?probe=9aafaab56e) | Dec 01, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [2c511573ce](https://linux-hardware.org/?probe=2c511573ce) | Nov 30, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [20db47125e](https://linux-hardware.org/?probe=20db47125e) | Nov 30, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [3ccb9d6a82](https://linux-hardware.org/?probe=3ccb9d6a82) | Nov 30, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| Tablet        | 8                           | Notebook    | [36164d26c8](https://linux-hardware.org/?probe=36164d26c8) | Nov 30, 2021 |
| HP            | 1495                        | Desktop     | [81d72efebc](https://linux-hardware.org/?probe=81d72efebc) | Nov 30, 2021 |
| HP            | 2215                        | Desktop     | [a9a43dfbe0](https://linux-hardware.org/?probe=a9a43dfbe0) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [b752e7c259](https://linux-hardware.org/?probe=b752e7c259) | Nov 30, 2021 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [8e8f9d7961](https://linux-hardware.org/?probe=8e8f9d7961) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [d5015724c8](https://linux-hardware.org/?probe=d5015724c8) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5e6aa10813](https://linux-hardware.org/?probe=5e6aa10813) | Nov 29, 2021 |
| Dell          | Latitude 7275               | Notebook    | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| HP            | ElitePad 1000 G2            | Notebook    | [1f9ff5886c](https://linux-hardware.org/?probe=1f9ff5886c) | Nov 29, 2021 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [c08d8f6418](https://linux-hardware.org/?probe=c08d8f6418) | Nov 28, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [af5f461e74](https://linux-hardware.org/?probe=af5f461e74) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [a9e4e25600](https://linux-hardware.org/?probe=a9e4e25600) | Nov 28, 2021 |
| MSI           | B75A-G41                    | Desktop     | [ebedf5b920](https://linux-hardware.org/?probe=ebedf5b920) | Nov 28, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [ee3aa93d09](https://linux-hardware.org/?probe=ee3aa93d09) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [11e8a78550](https://linux-hardware.org/?probe=11e8a78550) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GHC... | Tablet      | [c9a56629e1](https://linux-hardware.org/?probe=c9a56629e1) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [be44e9c10b](https://linux-hardware.org/?probe=be44e9c10b) | Nov 28, 2021 |
| Acer          | TravelMate P214-52          | Notebook    | [bea2d6c254](https://linux-hardware.org/?probe=bea2d6c254) | Nov 27, 2021 |
| Dell          | Inspiron 14-3452            | Notebook    | [b0fb64bf16](https://linux-hardware.org/?probe=b0fb64bf16) | Nov 27, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [2ffa26a48c](https://linux-hardware.org/?probe=2ffa26a48c) | Nov 27, 2021 |
| HP            | 83EE                        | Desktop     | [19b7dc07a6](https://linux-hardware.org/?probe=19b7dc07a6) | Nov 27, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [c5b8c42409](https://linux-hardware.org/?probe=c5b8c42409) | Nov 27, 2021 |
| PC Special... | X170KM-G                    | Notebook    | [6321e2900b](https://linux-hardware.org/?probe=6321e2900b) | Nov 27, 2021 |
| Medion        | BEAST X10                   | Notebook    | [98d8ad97d8](https://linux-hardware.org/?probe=98d8ad97d8) | Nov 27, 2021 |
| Acer          | Aspire Z3-615               | All in one  | [4e971f0caa](https://linux-hardware.org/?probe=4e971f0caa) | Nov 27, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [49a5e6faa8](https://linux-hardware.org/?probe=49a5e6faa8) | Nov 26, 2021 |
| Dell          | 0W5363                      | Desktop     | [60dbdd680a](https://linux-hardware.org/?probe=60dbdd680a) | Nov 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [de16934dc5](https://linux-hardware.org/?probe=de16934dc5) | Nov 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [05c154f263](https://linux-hardware.org/?probe=05c154f263) | Nov 26, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [e69007b550](https://linux-hardware.org/?probe=e69007b550) | Nov 26, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [2bc32a3aff](https://linux-hardware.org/?probe=2bc32a3aff) | Nov 26, 2021 |
| HP            | Pavilion g7                 | Notebook    | [e8dcea99ad](https://linux-hardware.org/?probe=e8dcea99ad) | Nov 26, 2021 |
| ENTITY        | ENTYA11Q120                 | Notebook    | [38796d7825](https://linux-hardware.org/?probe=38796d7825) | Nov 25, 2021 |
| HP            | 2179                        | Desktop     | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [ade3c9d36c](https://linux-hardware.org/?probe=ade3c9d36c) | Nov 25, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [9523dc010d](https://linux-hardware.org/?probe=9523dc010d) | Nov 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c2a925dc00](https://linux-hardware.org/?probe=c2a925dc00) | Nov 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [126f22ba0b](https://linux-hardware.org/?probe=126f22ba0b) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [5843422adb](https://linux-hardware.org/?probe=5843422adb) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6a09368b75](https://linux-hardware.org/?probe=6a09368b75) | Nov 24, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4a634caeca](https://linux-hardware.org/?probe=4a634caeca) | Nov 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [156a920647](https://linux-hardware.org/?probe=156a920647) | Nov 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [286c984252](https://linux-hardware.org/?probe=286c984252) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [774f732180](https://linux-hardware.org/?probe=774f732180) | Nov 24, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [35534f78a5](https://linux-hardware.org/?probe=35534f78a5) | Nov 23, 2021 |
| HP            | 83E1                        | Desktop     | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| Dell          | Latitude 5285               | Tablet      | [568757f9f8](https://linux-hardware.org/?probe=568757f9f8) | Nov 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4f44f7543f](https://linux-hardware.org/?probe=4f44f7543f) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [7a3c9113a5](https://linux-hardware.org/?probe=7a3c9113a5) | Nov 23, 2021 |
| Dell          | Latitude 5285               | Tablet      | [b94897c7f7](https://linux-hardware.org/?probe=b94897c7f7) | Nov 23, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [fade956732](https://linux-hardware.org/?probe=fade956732) | Nov 22, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [791626a325](https://linux-hardware.org/?probe=791626a325) | Nov 22, 2021 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [07c3e7d363](https://linux-hardware.org/?probe=07c3e7d363) | Nov 22, 2021 |
| HP            | 0AA4h                       | Desktop     | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1d6f8e4128](https://linux-hardware.org/?probe=1d6f8e4128) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3964ebaadd](https://linux-hardware.org/?probe=3964ebaadd) | Nov 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [47fe68608a](https://linux-hardware.org/?probe=47fe68608a) | Nov 22, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [d62dae58f1](https://linux-hardware.org/?probe=d62dae58f1) | Nov 21, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [6534c6b46c](https://linux-hardware.org/?probe=6534c6b46c) | Nov 21, 2021 |
| Gigabyte      | P55-UD3                     | Desktop     | [6fbfc34971](https://linux-hardware.org/?probe=6fbfc34971) | Nov 21, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d73b7c147b](https://linux-hardware.org/?probe=d73b7c147b) | Nov 21, 2021 |
| Dell          | Precision 7560              | Notebook    | [03782fee6b](https://linux-hardware.org/?probe=03782fee6b) | Nov 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [45a3de863b](https://linux-hardware.org/?probe=45a3de863b) | Nov 20, 2021 |
| Panasonic     | CF-192VYFX1M                | Notebook    | [efac7f4d90](https://linux-hardware.org/?probe=efac7f4d90) | Nov 20, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [e46e1b875a](https://linux-hardware.org/?probe=e46e1b875a) | Nov 20, 2021 |
| Panasonic     | CF-192VYFX1M                | Notebook    | [3bf756ab75](https://linux-hardware.org/?probe=3bf756ab75) | Nov 20, 2021 |
| HP            | 3048h                       | Desktop     | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e3644a6168](https://linux-hardware.org/?probe=e3644a6168) | Nov 20, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| Lenovo        | V155-15API 81V5             | Notebook    | [2fa6ddfb10](https://linux-hardware.org/?probe=2fa6ddfb10) | Nov 20, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [9cb0209a6c](https://linux-hardware.org/?probe=9cb0209a6c) | Nov 20, 2021 |
| MSI           | GE66 Raider 11UG            | Notebook    | [fe677aa4e9](https://linux-hardware.org/?probe=fe677aa4e9) | Nov 20, 2021 |
| Dell          | Precision M4800             | Notebook    | [01073ad18c](https://linux-hardware.org/?probe=01073ad18c) | Nov 19, 2021 |
| MSI           | H81M-P33                    | Desktop     | [cc4ed13747](https://linux-hardware.org/?probe=cc4ed13747) | Nov 19, 2021 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [e797ef583f](https://linux-hardware.org/?probe=e797ef583f) | Nov 19, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efaad13102](https://linux-hardware.org/?probe=efaad13102) | Nov 19, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| HP            | Stream Notebook             | Notebook    | [0745217a3b](https://linux-hardware.org/?probe=0745217a3b) | Nov 19, 2021 |
| ASUSTek       | X401A1                      | Notebook    | [fa9b9fa473](https://linux-hardware.org/?probe=fa9b9fa473) | Nov 19, 2021 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [aa6ce224ea](https://linux-hardware.org/?probe=aa6ce224ea) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | Notebook    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [b5ee9cfe18](https://linux-hardware.org/?probe=b5ee9cfe18) | Nov 19, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [294350e1a2](https://linux-hardware.org/?probe=294350e1a2) | Nov 19, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [d3cd1538f2](https://linux-hardware.org/?probe=d3cd1538f2) | Nov 18, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [1219c8fdca](https://linux-hardware.org/?probe=1219c8fdca) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c5c112ae1d](https://linux-hardware.org/?probe=c5c112ae1d) | Nov 18, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [6d0f30370a](https://linux-hardware.org/?probe=6d0f30370a) | Nov 17, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [3cbee876cb](https://linux-hardware.org/?probe=3cbee876cb) | Nov 17, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [92f0b10f02](https://linux-hardware.org/?probe=92f0b10f02) | Nov 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4115d29b86](https://linux-hardware.org/?probe=4115d29b86) | Nov 17, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [9c44bc92ae](https://linux-hardware.org/?probe=9c44bc92ae) | Nov 16, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [1f5deb0f31](https://linux-hardware.org/?probe=1f5deb0f31) | Nov 16, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [dfdeaca88b](https://linux-hardware.org/?probe=dfdeaca88b) | Nov 16, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [641218d2e6](https://linux-hardware.org/?probe=641218d2e6) | Nov 16, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [e72b06779f](https://linux-hardware.org/?probe=e72b06779f) | Nov 16, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ENTITY        | ENTYA11Q120                 | Notebook    | [d67e7a19dd](https://linux-hardware.org/?probe=d67e7a19dd) | Nov 16, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [75e04ad411](https://linux-hardware.org/?probe=75e04ad411) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [5f4573ad05](https://linux-hardware.org/?probe=5f4573ad05) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [345ebb92ec](https://linux-hardware.org/?probe=345ebb92ec) | Nov 15, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [5565624f6f](https://linux-hardware.org/?probe=5565624f6f) | Nov 15, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [f7f26d66a5](https://linux-hardware.org/?probe=f7f26d66a5) | Nov 15, 2021 |
| MOTILE        | M142                        | Notebook    | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| PC Special... | X170SM                      | Notebook    | [a177a36d19](https://linux-hardware.org/?probe=a177a36d19) | Nov 15, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a589e9ccfc](https://linux-hardware.org/?probe=a589e9ccfc) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [0e77c9ff09](https://linux-hardware.org/?probe=0e77c9ff09) | Nov 14, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [377f724a3e](https://linux-hardware.org/?probe=377f724a3e) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| HP            | 620                         | Notebook    | [86bcf95d93](https://linux-hardware.org/?probe=86bcf95d93) | Nov 14, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [5a55005b33](https://linux-hardware.org/?probe=5a55005b33) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | 900                         | Notebook    | [1919d281ef](https://linux-hardware.org/?probe=1919d281ef) | Nov 13, 2021 |
| ENTITY        | ENTYA11Q120                 | Notebook    | [0ee98ad50e](https://linux-hardware.org/?probe=0ee98ad50e) | Nov 13, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6419aed207](https://linux-hardware.org/?probe=6419aed207) | Nov 13, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [c5ea8c3a2a](https://linux-hardware.org/?probe=c5ea8c3a2a) | Nov 13, 2021 |
| HP            | Notebook                    | Notebook    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | Notebook    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| Medion        | MS-7800                     | Desktop     | [f87484fbec](https://linux-hardware.org/?probe=f87484fbec) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [7d4e321511](https://linux-hardware.org/?probe=7d4e321511) | Nov 12, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | Notebook    | [c64aae1257](https://linux-hardware.org/?probe=c64aae1257) | Nov 12, 2021 |
| Lenovo        | Aptio CRB 31900056 WIN      | Mini pc     | [0a2e33dad2](https://linux-hardware.org/?probe=0a2e33dad2) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a42a22a526](https://linux-hardware.org/?probe=a42a22a526) | Nov 11, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [51777be647](https://linux-hardware.org/?probe=51777be647) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [93456dc08a](https://linux-hardware.org/?probe=93456dc08a) | Nov 11, 2021 |
| HP            | 350 G2                      | Notebook    | [4622bfdef5](https://linux-hardware.org/?probe=4622bfdef5) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| HP            | ENVY m6                     | Notebook    | [83c010511b](https://linux-hardware.org/?probe=83c010511b) | Nov 10, 2021 |
| Toshiba       | Satellite C850-1KN          | Notebook    | [1640cd94d0](https://linux-hardware.org/?probe=1640cd94d0) | Nov 10, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [4549230d4e](https://linux-hardware.org/?probe=4549230d4e) | Nov 10, 2021 |
| SIEMENS       | SIMATIC Field PG M3         | Notebook    | [4482b478f6](https://linux-hardware.org/?probe=4482b478f6) | Nov 10, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| HP            | 1850                        | Desktop     | [be26330bbe](https://linux-hardware.org/?probe=be26330bbe) | Nov 09, 2021 |
| Dell          | Precision M3800             | Notebook    | [94e7e6104d](https://linux-hardware.org/?probe=94e7e6104d) | Nov 09, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [5831452011](https://linux-hardware.org/?probe=5831452011) | Nov 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c046d8e28c](https://linux-hardware.org/?probe=c046d8e28c) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a6a6f59d46](https://linux-hardware.org/?probe=a6a6f59d46) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [5e5fefb1b6](https://linux-hardware.org/?probe=5e5fefb1b6) | Nov 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3d661ce2df](https://linux-hardware.org/?probe=3d661ce2df) | Nov 09, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [319a6efc5a](https://linux-hardware.org/?probe=319a6efc5a) | Nov 09, 2021 |
| Lenovo        | ThinkPad E15 20RD006BUS     | Notebook    | [7bfaa1b6a9](https://linux-hardware.org/?probe=7bfaa1b6a9) | Nov 09, 2021 |
| Lenovo        | ThinkPad E15 20RD006BUS     | Notebook    | [d0bedfe49d](https://linux-hardware.org/?probe=d0bedfe49d) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [abffeccfd1](https://linux-hardware.org/?probe=abffeccfd1) | Nov 09, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [31ffcb5018](https://linux-hardware.org/?probe=31ffcb5018) | Nov 09, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c41b91ddde](https://linux-hardware.org/?probe=c41b91ddde) | Nov 09, 2021 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [eee48a9b12](https://linux-hardware.org/?probe=eee48a9b12) | Nov 09, 2021 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [1672137390](https://linux-hardware.org/?probe=1672137390) | Nov 08, 2021 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [d410e36b94](https://linux-hardware.org/?probe=d410e36b94) | Nov 08, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| Dell          | Latitude E6400              | Notebook    | [57751131b5](https://linux-hardware.org/?probe=57751131b5) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [4b834a3bff](https://linux-hardware.org/?probe=4b834a3bff) | Nov 07, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [8c6816916c](https://linux-hardware.org/?probe=8c6816916c) | Nov 07, 2021 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [80c808336f](https://linux-hardware.org/?probe=80c808336f) | Nov 07, 2021 |
| Toshiba       | Satellite Pro S300          | Notebook    | [a9dd74e832](https://linux-hardware.org/?probe=a9dd74e832) | Nov 07, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [2e89cb2e33](https://linux-hardware.org/?probe=2e89cb2e33) | Nov 07, 2021 |
| Acer          | Aspire Z3-615               | All in one  | [6b47cff347](https://linux-hardware.org/?probe=6b47cff347) | Nov 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [9ceab9ce1b](https://linux-hardware.org/?probe=9ceab9ce1b) | Nov 06, 2021 |
| ASRock        | B560M-HDV                   | Desktop     | [0246e9b73a](https://linux-hardware.org/?probe=0246e9b73a) | Nov 06, 2021 |
| HP            | 0A98h                       | Desktop     | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d7947a5a8](https://linux-hardware.org/?probe=9d7947a5a8) | Nov 06, 2021 |
| Dell          | 0GK35Y A00                  | Desktop     | [bd1f33d4b9](https://linux-hardware.org/?probe=bd1f33d4b9) | Nov 06, 2021 |
| Dell          | 0GK35Y A00                  | Desktop     | [bbd15fbb5c](https://linux-hardware.org/?probe=bbd15fbb5c) | Nov 06, 2021 |
| HP            | ProBook 430 G4              | Notebook    | [d5ff59ee05](https://linux-hardware.org/?probe=d5ff59ee05) | Nov 05, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [d4672db4a9](https://linux-hardware.org/?probe=d4672db4a9) | Nov 05, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [43d9b0df9e](https://linux-hardware.org/?probe=43d9b0df9e) | Nov 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [3690315342](https://linux-hardware.org/?probe=3690315342) | Nov 05, 2021 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [b69ad25203](https://linux-hardware.org/?probe=b69ad25203) | Nov 04, 2021 |
| MSI           | E350DM-E33                  | Desktop     | [d44e9f05c0](https://linux-hardware.org/?probe=d44e9f05c0) | Nov 04, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [03f41a1ad2](https://linux-hardware.org/?probe=03f41a1ad2) | Nov 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [e7bb09ee7d](https://linux-hardware.org/?probe=e7bb09ee7d) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc8f8db0fd](https://linux-hardware.org/?probe=dc8f8db0fd) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc325a808a](https://linux-hardware.org/?probe=dc325a808a) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9fe96f497b](https://linux-hardware.org/?probe=9fe96f497b) | Nov 04, 2021 |
| MSI           | GF75 Thin 10SDR             | Notebook    | [ebc4629f36](https://linux-hardware.org/?probe=ebc4629f36) | Nov 04, 2021 |
| MSI           | GF75 Thin 10SDR             | Notebook    | [619a95f37b](https://linux-hardware.org/?probe=619a95f37b) | Nov 04, 2021 |
| HP            | 350 G2                      | Notebook    | [34baec037c](https://linux-hardware.org/?probe=34baec037c) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | Notebook    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [5a4355a42b](https://linux-hardware.org/?probe=5a4355a42b) | Nov 04, 2021 |
| Pegatron      | EVE                         | Desktop     | [b3e2638017](https://linux-hardware.org/?probe=b3e2638017) | Nov 03, 2021 |
| Packard Be... | AAXSKB-VA                   | All in one  | [f2d5d040cf](https://linux-hardware.org/?probe=f2d5d040cf) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [cc1347a298](https://linux-hardware.org/?probe=cc1347a298) | Nov 03, 2021 |
| Samsung       | 950QDB                      | Convertible | [515607bf99](https://linux-hardware.org/?probe=515607bf99) | Nov 02, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [1cef1efaf7](https://linux-hardware.org/?probe=1cef1efaf7) | Nov 02, 2021 |
| HP            | Notebook                    | Notebook    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad X230 2325DV5       | Notebook    | [96534678e0](https://linux-hardware.org/?probe=96534678e0) | Nov 02, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [279da063de](https://linux-hardware.org/?probe=279da063de) | Nov 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [83204d14a3](https://linux-hardware.org/?probe=83204d14a3) | Nov 02, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [4958eac65a](https://linux-hardware.org/?probe=4958eac65a) | Nov 02, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [5dfe7ca832](https://linux-hardware.org/?probe=5dfe7ca832) | Nov 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c911492ba6](https://linux-hardware.org/?probe=c911492ba6) | Nov 01, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [d414f9ec2d](https://linux-hardware.org/?probe=d414f9ec2d) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80627a5a8a](https://linux-hardware.org/?probe=80627a5a8a) | Nov 01, 2021 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [01a3346d88](https://linux-hardware.org/?probe=01a3346d88) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [67f0b45a7a](https://linux-hardware.org/?probe=67f0b45a7a) | Nov 01, 2021 |
| Acer          | Aspire A517-52              | Notebook    | [efdb9e6636](https://linux-hardware.org/?probe=efdb9e6636) | Nov 01, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [6b2b63756d](https://linux-hardware.org/?probe=6b2b63756d) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [95c381ccd9](https://linux-hardware.org/?probe=95c381ccd9) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [bd1cb6f826](https://linux-hardware.org/?probe=bd1cb6f826) | Oct 31, 2021 |
| Dell          | 0T1D10 A01                  | Desktop     | [cfdd30c7c7](https://linux-hardware.org/?probe=cfdd30c7c7) | Oct 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d954a6ba33](https://linux-hardware.org/?probe=d954a6ba33) | Oct 31, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [381023907e](https://linux-hardware.org/?probe=381023907e) | Oct 31, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [6039985c3f](https://linux-hardware.org/?probe=6039985c3f) | Oct 31, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [d92a4dbde4](https://linux-hardware.org/?probe=d92a4dbde4) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [28b152bb19](https://linux-hardware.org/?probe=28b152bb19) | Oct 30, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [c3479871d7](https://linux-hardware.org/?probe=c3479871d7) | Oct 30, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [33fefe9de1](https://linux-hardware.org/?probe=33fefe9de1) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 2325L19       | Notebook    | [a120083d3c](https://linux-hardware.org/?probe=a120083d3c) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8bf4a2f1a1](https://linux-hardware.org/?probe=8bf4a2f1a1) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [27f53da246](https://linux-hardware.org/?probe=27f53da246) | Oct 30, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [d09085816d](https://linux-hardware.org/?probe=d09085816d) | Oct 29, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [cadb142111](https://linux-hardware.org/?probe=cadb142111) | Oct 29, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3cdc08297e](https://linux-hardware.org/?probe=3cdc08297e) | Oct 29, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [5fbdc9f939](https://linux-hardware.org/?probe=5fbdc9f939) | Oct 29, 2021 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [f802abef07](https://linux-hardware.org/?probe=f802abef07) | Oct 29, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [352946e177](https://linux-hardware.org/?probe=352946e177) | Oct 29, 2021 |
| Lenovo        | ThinkCentre Edge72 3484F... | Desktop     | [d99aef9e28](https://linux-hardware.org/?probe=d99aef9e28) | Oct 29, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [82b124d8c4](https://linux-hardware.org/?probe=82b124d8c4) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [c7fd942b8b](https://linux-hardware.org/?probe=c7fd942b8b) | Oct 29, 2021 |
| Fusion5       | FWIN232                     | Tablet      | [43e493b8cf](https://linux-hardware.org/?probe=43e493b8cf) | Oct 29, 2021 |
| PC Special... | NP5x_NP6x_NP7xHP            | Notebook    | [621aa75bf6](https://linux-hardware.org/?probe=621aa75bf6) | Oct 29, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [dec018e9b6](https://linux-hardware.org/?probe=dec018e9b6) | Oct 29, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [f7ce357637](https://linux-hardware.org/?probe=f7ce357637) | Oct 28, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [ec6b71abb7](https://linux-hardware.org/?probe=ec6b71abb7) | Oct 28, 2021 |
| MSI           | Z97M GAMING                 | Desktop     | [3aeeebeb96](https://linux-hardware.org/?probe=3aeeebeb96) | Oct 28, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [6ae3033841](https://linux-hardware.org/?probe=6ae3033841) | Oct 28, 2021 |
| Razer         | Blade                       | Notebook    | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7c73c4e6f0](https://linux-hardware.org/?probe=7c73c4e6f0) | Oct 27, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| Dell          | 0M858N A00                  | Desktop     | [f27a29129f](https://linux-hardware.org/?probe=f27a29129f) | Oct 27, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [cec5669039](https://linux-hardware.org/?probe=cec5669039) | Oct 27, 2021 |
| Dell          | Latitude 5420               | Notebook    | [6eef53ac22](https://linux-hardware.org/?probe=6eef53ac22) | Oct 27, 2021 |
| Dell          | Latitude 5420               | Notebook    | [6d4e346031](https://linux-hardware.org/?probe=6d4e346031) | Oct 27, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [0e8d69e9b8](https://linux-hardware.org/?probe=0e8d69e9b8) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [6378d53c40](https://linux-hardware.org/?probe=6378d53c40) | Oct 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [823c6074d8](https://linux-hardware.org/?probe=823c6074d8) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [406fcb6975](https://linux-hardware.org/?probe=406fcb6975) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Toshiba       | Satellite Pro S300          | Notebook    | [6a42c7bf7a](https://linux-hardware.org/?probe=6a42c7bf7a) | Oct 26, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [fe1d484f1b](https://linux-hardware.org/?probe=fe1d484f1b) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [0ad7e689f1](https://linux-hardware.org/?probe=0ad7e689f1) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d0cb96f5b2](https://linux-hardware.org/?probe=d0cb96f5b2) | Oct 26, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [58adbd547f](https://linux-hardware.org/?probe=58adbd547f) | Oct 26, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [39f15bd886](https://linux-hardware.org/?probe=39f15bd886) | Oct 26, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [0396eac317](https://linux-hardware.org/?probe=0396eac317) | Oct 26, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [a1bb38b636](https://linux-hardware.org/?probe=a1bb38b636) | Oct 25, 2021 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [58205197ac](https://linux-hardware.org/?probe=58205197ac) | Oct 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [111b26a250](https://linux-hardware.org/?probe=111b26a250) | Oct 25, 2021 |
| Acer          | AOA150                      | Notebook    | [1380638bb1](https://linux-hardware.org/?probe=1380638bb1) | Oct 25, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f0a8fa5e7a](https://linux-hardware.org/?probe=f0a8fa5e7a) | Oct 25, 2021 |
| HP            | 1850                        | Desktop     | [e8c750c4b9](https://linux-hardware.org/?probe=e8c750c4b9) | Oct 25, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [ad90be24b1](https://linux-hardware.org/?probe=ad90be24b1) | Oct 24, 2021 |
| Sun Micros... | Sun Fire X2270 M2 375-36... | Server      | [39b1b9c30a](https://linux-hardware.org/?probe=39b1b9c30a) | Oct 24, 2021 |
| ASUSTek       | N55SL                       | Notebook    | [11ed4def95](https://linux-hardware.org/?probe=11ed4def95) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [68fb8430c2](https://linux-hardware.org/?probe=68fb8430c2) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [3e2c50a321](https://linux-hardware.org/?probe=3e2c50a321) | Oct 24, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [59b7bef8c0](https://linux-hardware.org/?probe=59b7bef8c0) | Oct 24, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f3d65bb221](https://linux-hardware.org/?probe=f3d65bb221) | Oct 24, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [ce1a32bc3f](https://linux-hardware.org/?probe=ce1a32bc3f) | Oct 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [6014d2da08](https://linux-hardware.org/?probe=6014d2da08) | Oct 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7be969965e](https://linux-hardware.org/?probe=7be969965e) | Oct 24, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [3236bd0634](https://linux-hardware.org/?probe=3236bd0634) | Oct 23, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [56448c0f76](https://linux-hardware.org/?probe=56448c0f76) | Oct 23, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [09addf2612](https://linux-hardware.org/?probe=09addf2612) | Oct 23, 2021 |
| MSI           | GL73 8RD                    | Notebook    | [cf259f0674](https://linux-hardware.org/?probe=cf259f0674) | Oct 23, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [facb3c762d](https://linux-hardware.org/?probe=facb3c762d) | Oct 23, 2021 |
| Dell          | 0TP406                      | Desktop     | [df97b29e2e](https://linux-hardware.org/?probe=df97b29e2e) | Oct 23, 2021 |
| ZOOSTORM      | 7200-9041A                  | Notebook    | [6fe3800dd3](https://linux-hardware.org/?probe=6fe3800dd3) | Oct 22, 2021 |
| Dell          | 0TP406                      | Desktop     | [5e3ac96715](https://linux-hardware.org/?probe=5e3ac96715) | Oct 22, 2021 |
| HP            | 255 G5                      | Notebook    | [02e4b753ca](https://linux-hardware.org/?probe=02e4b753ca) | Oct 22, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [abf6fca6c4](https://linux-hardware.org/?probe=abf6fca6c4) | Oct 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [f0368052cb](https://linux-hardware.org/?probe=f0368052cb) | Oct 22, 2021 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [6a2b670752](https://linux-hardware.org/?probe=6a2b670752) | Oct 22, 2021 |
| Dell          | 0G679R                      | Desktop     | [e77852d5c2](https://linux-hardware.org/?probe=e77852d5c2) | Oct 22, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [51162ce3fb](https://linux-hardware.org/?probe=51162ce3fb) | Oct 22, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [08a5e38790](https://linux-hardware.org/?probe=08a5e38790) | Oct 22, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [8a199e27bf](https://linux-hardware.org/?probe=8a199e27bf) | Oct 22, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [271e56e195](https://linux-hardware.org/?probe=271e56e195) | Oct 21, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [3735576026](https://linux-hardware.org/?probe=3735576026) | Oct 21, 2021 |
| HP            | ENVY m6                     | Notebook    | [a3dfb4ccf4](https://linux-hardware.org/?probe=a3dfb4ccf4) | Oct 21, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [2d60265f85](https://linux-hardware.org/?probe=2d60265f85) | Oct 21, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [f106a5f8f7](https://linux-hardware.org/?probe=f106a5f8f7) | Oct 21, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [74a6f72f79](https://linux-hardware.org/?probe=74a6f72f79) | Oct 21, 2021 |
| Dell          | Latitude E6500              | Notebook    | [84217e1781](https://linux-hardware.org/?probe=84217e1781) | Oct 21, 2021 |
| Dell          | 0M858N A00                  | Desktop     | [a473e9ed9c](https://linux-hardware.org/?probe=a473e9ed9c) | Oct 21, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | GP72 2QD                    | Notebook    | [75801b27ae](https://linux-hardware.org/?probe=75801b27ae) | Oct 20, 2021 |
| MSI           | GP72 2QD                    | Notebook    | [bd12b3e948](https://linux-hardware.org/?probe=bd12b3e948) | Oct 20, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [dc6378e76b](https://linux-hardware.org/?probe=dc6378e76b) | Oct 20, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| Lenovo        | ThinkPad X220 4291B48       | Notebook    | [402ddbaa44](https://linux-hardware.org/?probe=402ddbaa44) | Oct 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4517a98ebf](https://linux-hardware.org/?probe=4517a98ebf) | Oct 20, 2021 |
| ASUSTek       | Basswood                    | Desktop     | [41a11f1678](https://linux-hardware.org/?probe=41a11f1678) | Oct 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [a6dc95fa65](https://linux-hardware.org/?probe=a6dc95fa65) | Oct 19, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [bcbf3d5ce9](https://linux-hardware.org/?probe=bcbf3d5ce9) | Oct 19, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [0ec3c548af](https://linux-hardware.org/?probe=0ec3c548af) | Oct 19, 2021 |
| Acer          | Extensa 215-51              | Notebook    | [a49d58aa94](https://linux-hardware.org/?probe=a49d58aa94) | Oct 19, 2021 |
| HP            | 255 G3                      | Notebook    | [e2b0881704](https://linux-hardware.org/?probe=e2b0881704) | Oct 19, 2021 |
| HP            | 255 G3                      | Notebook    | [46474a3fec](https://linux-hardware.org/?probe=46474a3fec) | Oct 19, 2021 |
| Dell          | Latitude D630               | Notebook    | [a21cbd39f7](https://linux-hardware.org/?probe=a21cbd39f7) | Oct 19, 2021 |
| Dell          | 0PU052                      | Desktop     | [1bb0034b64](https://linux-hardware.org/?probe=1bb0034b64) | Oct 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4bf0ef8f9b](https://linux-hardware.org/?probe=4bf0ef8f9b) | Oct 18, 2021 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [3738610b69](https://linux-hardware.org/?probe=3738610b69) | Oct 18, 2021 |
| Lenovo        | ThinkPad T450 20BUS1S81U    | Notebook    | [92fb8505aa](https://linux-hardware.org/?probe=92fb8505aa) | Oct 18, 2021 |
| ASUSTek       | A88XM-E                     | Desktop     | [82894be7a8](https://linux-hardware.org/?probe=82894be7a8) | Oct 18, 2021 |
| Dell          | Latitude E7440              | Notebook    | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| MSI           | GF62 8RC                    | Notebook    | [89d77a3654](https://linux-hardware.org/?probe=89d77a3654) | Oct 18, 2021 |
| AZW           | SEi                         | Notebook    | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| MSI           | MS-7255 V2.0                | Desktop     | [c61d7b8758](https://linux-hardware.org/?probe=c61d7b8758) | Oct 17, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [d5bcf80b27](https://linux-hardware.org/?probe=d5bcf80b27) | Oct 17, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90a3d77b31](https://linux-hardware.org/?probe=90a3d77b31) | Oct 17, 2021 |
| GEO           | GeoBook3X                   | Notebook    | [30b2e46c1b](https://linux-hardware.org/?probe=30b2e46c1b) | Oct 17, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f7ffa54af0](https://linux-hardware.org/?probe=f7ffa54af0) | Oct 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d8df5c8003](https://linux-hardware.org/?probe=d8df5c8003) | Oct 17, 2021 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [fb267ca5ae](https://linux-hardware.org/?probe=fb267ca5ae) | Oct 17, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [8b97914970](https://linux-hardware.org/?probe=8b97914970) | Oct 17, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [d10202fe29](https://linux-hardware.org/?probe=d10202fe29) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [088da5f604](https://linux-hardware.org/?probe=088da5f604) | Oct 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | Notebook    | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [59c0064e39](https://linux-hardware.org/?probe=59c0064e39) | Oct 17, 2021 |
| Lenovo        | ThinkPad T420 4236MD3       | Notebook    | [a23b230ad9](https://linux-hardware.org/?probe=a23b230ad9) | Oct 17, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [a55a4e03d5](https://linux-hardware.org/?probe=a55a4e03d5) | Oct 17, 2021 |
| Dell          | Latitude E6440              | Notebook    | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 8267 A01                    | Mini pc     | [edc6f2231b](https://linux-hardware.org/?probe=edc6f2231b) | Oct 16, 2021 |
| HP            | 8267 A01                    | Mini pc     | [0fa70257c9](https://linux-hardware.org/?probe=0fa70257c9) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8b87eef23f](https://linux-hardware.org/?probe=8b87eef23f) | Oct 16, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [deb206b64f](https://linux-hardware.org/?probe=deb206b64f) | Oct 16, 2021 |
| GEO           | GeoBook3X                   | Notebook    | [42793f73be](https://linux-hardware.org/?probe=42793f73be) | Oct 16, 2021 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aa8e220390](https://linux-hardware.org/?probe=aa8e220390) | Oct 16, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [34a5253469](https://linux-hardware.org/?probe=34a5253469) | Oct 16, 2021 |
| Lenovo        | ThinkCentre M81 5049P14     | Desktop     | [a704730f9f](https://linux-hardware.org/?probe=a704730f9f) | Oct 16, 2021 |
| Sony          | VGN-NR38S_S                 | Notebook    | [f7636d73e3](https://linux-hardware.org/?probe=f7636d73e3) | Oct 16, 2021 |
| Sony          | VGN-NR38S_S                 | Notebook    | [dfc2df1a7c](https://linux-hardware.org/?probe=dfc2df1a7c) | Oct 16, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [37a0658b60](https://linux-hardware.org/?probe=37a0658b60) | Oct 15, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [49e4112b11](https://linux-hardware.org/?probe=49e4112b11) | Oct 15, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [b4660289b3](https://linux-hardware.org/?probe=b4660289b3) | Oct 15, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [99d5f1aa6a](https://linux-hardware.org/?probe=99d5f1aa6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Dell          | 040DDP A00                  | Desktop     | [95249e56f5](https://linux-hardware.org/?probe=95249e56f5) | Oct 15, 2021 |
| HP            | 0A60h                       | Desktop     | [e2eb4c51df](https://linux-hardware.org/?probe=e2eb4c51df) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [06223f6db9](https://linux-hardware.org/?probe=06223f6db9) | Oct 15, 2021 |
| Clevo         | P65_P67SE                   | Notebook    | [9fbcbe3f46](https://linux-hardware.org/?probe=9fbcbe3f46) | Oct 15, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cc3eb1805e](https://linux-hardware.org/?probe=cc3eb1805e) | Oct 14, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [2a4135bc50](https://linux-hardware.org/?probe=2a4135bc50) | Oct 14, 2021 |
| Fujitsu       | D3598-B1 S26361-D3598-B1    | Desktop     | [33a89c4c5a](https://linux-hardware.org/?probe=33a89c4c5a) | Oct 14, 2021 |
| Lenovo        | ThinkPad T470 20HEA0TLUK    | Notebook    | [ca50fa4ac4](https://linux-hardware.org/?probe=ca50fa4ac4) | Oct 14, 2021 |
| ASUSTek       | E520                        | Desktop     | [a6f7d970df](https://linux-hardware.org/?probe=a6f7d970df) | Oct 14, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [9a64d0961f](https://linux-hardware.org/?probe=9a64d0961f) | Oct 14, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [e24a348b5f](https://linux-hardware.org/?probe=e24a348b5f) | Oct 13, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [120780e701](https://linux-hardware.org/?probe=120780e701) | Oct 13, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [d01836d406](https://linux-hardware.org/?probe=d01836d406) | Oct 13, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [023faa0df4](https://linux-hardware.org/?probe=023faa0df4) | Oct 13, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [d1cdbd537e](https://linux-hardware.org/?probe=d1cdbd537e) | Oct 13, 2021 |
| Lenovo        | ThinkCentre M81 5049P14     | Desktop     | [4d55080e0e](https://linux-hardware.org/?probe=4d55080e0e) | Oct 13, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [8fe4b6921b](https://linux-hardware.org/?probe=8fe4b6921b) | Oct 13, 2021 |
| Toshiba       | Satellite Pro S300          | Notebook    | [8465636993](https://linux-hardware.org/?probe=8465636993) | Oct 13, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8f9da6144d](https://linux-hardware.org/?probe=8f9da6144d) | Oct 12, 2021 |
| HP            | 1850                        | Desktop     | [60e45cdd58](https://linux-hardware.org/?probe=60e45cdd58) | Oct 12, 2021 |
| Dell          | Latitude E7270              | Notebook    | [425e5e3667](https://linux-hardware.org/?probe=425e5e3667) | Oct 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [92401f2840](https://linux-hardware.org/?probe=92401f2840) | Oct 12, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | Notebook    | [c8e9d8e7a9](https://linux-hardware.org/?probe=c8e9d8e7a9) | Oct 12, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [450992ab23](https://linux-hardware.org/?probe=450992ab23) | Oct 12, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [2a96c0566a](https://linux-hardware.org/?probe=2a96c0566a) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [eb4a97ceef](https://linux-hardware.org/?probe=eb4a97ceef) | Oct 12, 2021 |
| HUAWEI        | HBL-WX9                     | Notebook    | [4598e8498d](https://linux-hardware.org/?probe=4598e8498d) | Oct 12, 2021 |
| ASRock        | Z370 Gaming K6              | Desktop     | [3f995fd287](https://linux-hardware.org/?probe=3f995fd287) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [694de952d2](https://linux-hardware.org/?probe=694de952d2) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [91ba591940](https://linux-hardware.org/?probe=91ba591940) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | Notebook    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a94b3893c1](https://linux-hardware.org/?probe=a94b3893c1) | Oct 11, 2021 |
| Sun Micros... | Ultra 27 52                 | Desktop     | [144b473603](https://linux-hardware.org/?probe=144b473603) | Oct 11, 2021 |
| HP            | 8767 A                      | Desktop     | [9e052340b3](https://linux-hardware.org/?probe=9e052340b3) | Oct 11, 2021 |
| Alienware     | M11x R2                     | Notebook    | [e45fcc146d](https://linux-hardware.org/?probe=e45fcc146d) | Oct 10, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [d56e5dc989](https://linux-hardware.org/?probe=d56e5dc989) | Oct 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | Notebook    | [f8f9a09e2a](https://linux-hardware.org/?probe=f8f9a09e2a) | Oct 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aabedcd74f](https://linux-hardware.org/?probe=aabedcd74f) | Oct 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | Notebook    | [d6c8e16cdb](https://linux-hardware.org/?probe=d6c8e16cdb) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [96a8c4ff7a](https://linux-hardware.org/?probe=96a8c4ff7a) | Oct 10, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [43d48e705c](https://linux-hardware.org/?probe=43d48e705c) | Oct 09, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [e4e8fba89b](https://linux-hardware.org/?probe=e4e8fba89b) | Oct 09, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4eb9dff99e](https://linux-hardware.org/?probe=4eb9dff99e) | Oct 09, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [a7c68b574b](https://linux-hardware.org/?probe=a7c68b574b) | Oct 09, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [3238831a01](https://linux-hardware.org/?probe=3238831a01) | Oct 09, 2021 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [7d133d5c43](https://linux-hardware.org/?probe=7d133d5c43) | Oct 09, 2021 |
| Toshiba       | Satellite Pro S300          | Notebook    | [35569955fe](https://linux-hardware.org/?probe=35569955fe) | Oct 09, 2021 |
| Alienware     | M11x R2                     | Notebook    | [a2bb09f85a](https://linux-hardware.org/?probe=a2bb09f85a) | Oct 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [017240c471](https://linux-hardware.org/?probe=017240c471) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| Shuttle       | SX50 V10                    | Desktop     | [8547733d58](https://linux-hardware.org/?probe=8547733d58) | Oct 08, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7d98e00fdf](https://linux-hardware.org/?probe=7d98e00fdf) | Oct 08, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [92f15aeb4d](https://linux-hardware.org/?probe=92f15aeb4d) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b77373d120](https://linux-hardware.org/?probe=b77373d120) | Oct 08, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ae1e256153](https://linux-hardware.org/?probe=ae1e256153) | Oct 07, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5cabb513b7](https://linux-hardware.org/?probe=5cabb513b7) | Oct 07, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [7024487bcd](https://linux-hardware.org/?probe=7024487bcd) | Oct 07, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [d8a64024f9](https://linux-hardware.org/?probe=d8a64024f9) | Oct 07, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b5e4091864](https://linux-hardware.org/?probe=b5e4091864) | Oct 07, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [8f41815859](https://linux-hardware.org/?probe=8f41815859) | Oct 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [ceefec9a7f](https://linux-hardware.org/?probe=ceefec9a7f) | Oct 06, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [d28b90efdc](https://linux-hardware.org/?probe=d28b90efdc) | Oct 06, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [1571a4c2b8](https://linux-hardware.org/?probe=1571a4c2b8) | Oct 05, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a68932119c](https://linux-hardware.org/?probe=a68932119c) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2a1930c4e4](https://linux-hardware.org/?probe=2a1930c4e4) | Oct 05, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c020fa352e](https://linux-hardware.org/?probe=c020fa352e) | Oct 05, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a72102fdb0](https://linux-hardware.org/?probe=a72102fdb0) | Oct 05, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [aefc3c3de8](https://linux-hardware.org/?probe=aefc3c3de8) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c3cccd51c4](https://linux-hardware.org/?probe=c3cccd51c4) | Oct 05, 2021 |
| ASUSTek       | E520                        | Desktop     | [ea42a2f6ea](https://linux-hardware.org/?probe=ea42a2f6ea) | Oct 04, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [16641afc6c](https://linux-hardware.org/?probe=16641afc6c) | Oct 04, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [90dbdbed7b](https://linux-hardware.org/?probe=90dbdbed7b) | Oct 04, 2021 |
| MSI           | Traveller 1591              | Notebook    | [46430a6e00](https://linux-hardware.org/?probe=46430a6e00) | Oct 04, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d9637236c2](https://linux-hardware.org/?probe=d9637236c2) | Oct 04, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| Acer          | Aspire M3920                | Desktop     | [515bfbee2e](https://linux-hardware.org/?probe=515bfbee2e) | Oct 04, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [7191b6c18e](https://linux-hardware.org/?probe=7191b6c18e) | Oct 03, 2021 |
| ASUSTek       | P8H61-I LX                  | Desktop     | [9e9099a53d](https://linux-hardware.org/?probe=9e9099a53d) | Oct 03, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [96a7960f7d](https://linux-hardware.org/?probe=96a7960f7d) | Oct 03, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f7faec22bf](https://linux-hardware.org/?probe=f7faec22bf) | Oct 03, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [91b89eebf6](https://linux-hardware.org/?probe=91b89eebf6) | Oct 03, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5dea355f4](https://linux-hardware.org/?probe=f5dea355f4) | Oct 03, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [904bccbac0](https://linux-hardware.org/?probe=904bccbac0) | Oct 03, 2021 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [97958d9c7e](https://linux-hardware.org/?probe=97958d9c7e) | Oct 03, 2021 |
| Dell          | Inspiron N7010              | Notebook    | [8fb386fbe6](https://linux-hardware.org/?probe=8fb386fbe6) | Oct 03, 2021 |
| Toshiba       | Satellite C55D-A-15H        | Notebook    | [b182b45fa5](https://linux-hardware.org/?probe=b182b45fa5) | Oct 03, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [9ced5db194](https://linux-hardware.org/?probe=9ced5db194) | Oct 03, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [fc981d78af](https://linux-hardware.org/?probe=fc981d78af) | Oct 02, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 1497                        | Desktop     | [5a161ee044](https://linux-hardware.org/?probe=5a161ee044) | Oct 02, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [5b14d08827](https://linux-hardware.org/?probe=5b14d08827) | Oct 02, 2021 |
| Acer          | Veriton M680G               | Desktop     | [5ab503ab75](https://linux-hardware.org/?probe=5ab503ab75) | Oct 02, 2021 |
| MiTAC         | PD14RI                      | Desktop     | [04ec92a4b9](https://linux-hardware.org/?probe=04ec92a4b9) | Oct 02, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [627f5a64cf](https://linux-hardware.org/?probe=627f5a64cf) | Oct 02, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [8b1d38b8bf](https://linux-hardware.org/?probe=8b1d38b8bf) | Oct 02, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [51def17c28](https://linux-hardware.org/?probe=51def17c28) | Oct 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [4a4f239e4d](https://linux-hardware.org/?probe=4a4f239e4d) | Oct 01, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b877dfade2](https://linux-hardware.org/?probe=b877dfade2) | Oct 01, 2021 |
| ASRock        | H110M-G/M.2                 | Desktop     | [fa98bc9cc1](https://linux-hardware.org/?probe=fa98bc9cc1) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ac9ea9b008](https://linux-hardware.org/?probe=ac9ea9b008) | Sep 30, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [962373c0ab](https://linux-hardware.org/?probe=962373c0ab) | Sep 30, 2021 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [04aa52d7ef](https://linux-hardware.org/?probe=04aa52d7ef) | Sep 29, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a6dd9f56f4](https://linux-hardware.org/?probe=a6dd9f56f4) | Sep 29, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [ae8aed0f28](https://linux-hardware.org/?probe=ae8aed0f28) | Sep 29, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e11ce63403](https://linux-hardware.org/?probe=e11ce63403) | Sep 29, 2021 |
| Clevo         | P65_P67SE                   | Notebook    | [c7d36fe67f](https://linux-hardware.org/?probe=c7d36fe67f) | Sep 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b535b99341](https://linux-hardware.org/?probe=b535b99341) | Sep 29, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [f04c751d60](https://linux-hardware.org/?probe=f04c751d60) | Sep 29, 2021 |
| Chuwi         | UBook X                     | Convertible | [b227e694f7](https://linux-hardware.org/?probe=b227e694f7) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d0f4eaa9f8](https://linux-hardware.org/?probe=d0f4eaa9f8) | Sep 29, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [b8259fc9b0](https://linux-hardware.org/?probe=b8259fc9b0) | Sep 28, 2021 |
| Sony          | VPCCB3P1E                   | Notebook    | [963f47731d](https://linux-hardware.org/?probe=963f47731d) | Sep 28, 2021 |
| Linx          | LINX12X64                   | Tablet      | [f4c91e377c](https://linux-hardware.org/?probe=f4c91e377c) | Sep 28, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9b959d4529](https://linux-hardware.org/?probe=9b959d4529) | Sep 28, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [2acf5e4c6d](https://linux-hardware.org/?probe=2acf5e4c6d) | Sep 28, 2021 |
| Dell          | Latitude E6400              | Notebook    | [eb47d36417](https://linux-hardware.org/?probe=eb47d36417) | Sep 28, 2021 |
| Linx          | LINX1010B                   | Notebook    | [5fd6a97443](https://linux-hardware.org/?probe=5fd6a97443) | Sep 28, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cc901dcf4f](https://linux-hardware.org/?probe=cc901dcf4f) | Sep 27, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Dell          | 0TNXNR A01                  | Desktop     | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Purism        | Librem 14                   | Notebook    | [68e8f5b427](https://linux-hardware.org/?probe=68e8f5b427) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ec7578e1e4](https://linux-hardware.org/?probe=ec7578e1e4) | Sep 27, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [0308468347](https://linux-hardware.org/?probe=0308468347) | Sep 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [83dc9c6220](https://linux-hardware.org/?probe=83dc9c6220) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| Dell          | Latitude E5470              | Notebook    | [24f254f7e8](https://linux-hardware.org/?probe=24f254f7e8) | Sep 25, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8472ba62c8](https://linux-hardware.org/?probe=8472ba62c8) | Sep 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e47c168067](https://linux-hardware.org/?probe=e47c168067) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| Google        | Banon                       | Notebook    | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| MSI           | GF63 Thin 10SC              | Notebook    | [9901d02ea5](https://linux-hardware.org/?probe=9901d02ea5) | Sep 25, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [2822e5f0b3](https://linux-hardware.org/?probe=2822e5f0b3) | Sep 25, 2021 |
| Supermicro    | X8DTH                       | Server      | [d3dc168a2a](https://linux-hardware.org/?probe=d3dc168a2a) | Sep 25, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [45bf15cb7f](https://linux-hardware.org/?probe=45bf15cb7f) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M71e 3166W1D    | Desktop     | [a7bf48b126](https://linux-hardware.org/?probe=a7bf48b126) | Sep 24, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [505c585a78](https://linux-hardware.org/?probe=505c585a78) | Sep 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e3a2a08368](https://linux-hardware.org/?probe=e3a2a08368) | Sep 24, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f13da59e69](https://linux-hardware.org/?probe=f13da59e69) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | Notebook    | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [fa3f31f773](https://linux-hardware.org/?probe=fa3f31f773) | Sep 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [04d40a1180](https://linux-hardware.org/?probe=04d40a1180) | Sep 24, 2021 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [82e7b4e2b0](https://linux-hardware.org/?probe=82e7b4e2b0) | Sep 24, 2021 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b38d253458](https://linux-hardware.org/?probe=b38d253458) | Sep 23, 2021 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [5f070ce188](https://linux-hardware.org/?probe=5f070ce188) | Sep 23, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [01f37a66c7](https://linux-hardware.org/?probe=01f37a66c7) | Sep 23, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [cfa65f0f9c](https://linux-hardware.org/?probe=cfa65f0f9c) | Sep 22, 2021 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ff839b201e](https://linux-hardware.org/?probe=ff839b201e) | Sep 22, 2021 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96b28eb906](https://linux-hardware.org/?probe=96b28eb906) | Sep 22, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [e24cae5c2f](https://linux-hardware.org/?probe=e24cae5c2f) | Sep 22, 2021 |
| Samsung       | Galaxy A5U (EUR)            | Phone       | [fd645550c4](https://linux-hardware.org/?probe=fd645550c4) | Sep 22, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [454c9e999e](https://linux-hardware.org/?probe=454c9e999e) | Sep 22, 2021 |
| Entroware     | Aether                      | Notebook    | [c65a69857f](https://linux-hardware.org/?probe=c65a69857f) | Sep 22, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [0f2ea86a13](https://linux-hardware.org/?probe=0f2ea86a13) | Sep 22, 2021 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [393fcd4089](https://linux-hardware.org/?probe=393fcd4089) | Sep 22, 2021 |
| Dell          | Latitude E7240              | Notebook    | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | Notebook    | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [19fd5c624f](https://linux-hardware.org/?probe=19fd5c624f) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [c5d41182c1](https://linux-hardware.org/?probe=c5d41182c1) | Sep 21, 2021 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [855a10f536](https://linux-hardware.org/?probe=855a10f536) | Sep 21, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [e3d21c46e4](https://linux-hardware.org/?probe=e3d21c46e4) | Sep 20, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [51719d36a4](https://linux-hardware.org/?probe=51719d36a4) | Sep 20, 2021 |
| Dell          | Latitude 5401               | Notebook    | [334511b0c1](https://linux-hardware.org/?probe=334511b0c1) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb5bd05aed](https://linux-hardware.org/?probe=fb5bd05aed) | Sep 20, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [99528281d1](https://linux-hardware.org/?probe=99528281d1) | Sep 20, 2021 |
| Supermicro    | X8DTH                       | Server      | [d6a6b87b9c](https://linux-hardware.org/?probe=d6a6b87b9c) | Sep 20, 2021 |
| HP            | Compaq 2510p                | Notebook    | [1f3c069a21](https://linux-hardware.org/?probe=1f3c069a21) | Sep 20, 2021 |
| Maibenben     | PC34 V1.0                   | Desktop     | [10d3e02dfb](https://linux-hardware.org/?probe=10d3e02dfb) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [961e347941](https://linux-hardware.org/?probe=961e347941) | Sep 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [9ea3b3a8d4](https://linux-hardware.org/?probe=9ea3b3a8d4) | Sep 19, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [30e4588bc9](https://linux-hardware.org/?probe=30e4588bc9) | Sep 19, 2021 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [79de562e96](https://linux-hardware.org/?probe=79de562e96) | Sep 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS25D0G     | Notebook    | [21cc4f0d72](https://linux-hardware.org/?probe=21cc4f0d72) | Sep 19, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a8d544a8cc](https://linux-hardware.org/?probe=a8d544a8cc) | Sep 19, 2021 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ca800107fc](https://linux-hardware.org/?probe=ca800107fc) | Sep 18, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ffc90dca02](https://linux-hardware.org/?probe=ffc90dca02) | Sep 18, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3562e1d9e4](https://linux-hardware.org/?probe=3562e1d9e4) | Sep 18, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [e0a3dee012](https://linux-hardware.org/?probe=e0a3dee012) | Sep 18, 2021 |
| Toshiba       | Satellite C850-1KN          | Notebook    | [add02dc457](https://linux-hardware.org/?probe=add02dc457) | Sep 18, 2021 |
| PC Special... | NH5x_7xDCx_DDx              | Notebook    | [6e347c5a75](https://linux-hardware.org/?probe=6e347c5a75) | Sep 18, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [5f6c98d219](https://linux-hardware.org/?probe=5f6c98d219) | Sep 18, 2021 |
| MSI           | GF63 Thin 10SC              | Notebook    | [c91f893a5d](https://linux-hardware.org/?probe=c91f893a5d) | Sep 18, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [a6ad2cfbf4](https://linux-hardware.org/?probe=a6ad2cfbf4) | Sep 18, 2021 |
| Dell          | 0PU052                      | Desktop     | [a4220ae695](https://linux-hardware.org/?probe=a4220ae695) | Sep 18, 2021 |
| Acer          | Aspire 5542                 | Notebook    | [dfa471a829](https://linux-hardware.org/?probe=dfa471a829) | Sep 17, 2021 |
| Acer          | Aspire 5542                 | Notebook    | [d862c4ce39](https://linux-hardware.org/?probe=d862c4ce39) | Sep 17, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ba0e1028c3](https://linux-hardware.org/?probe=ba0e1028c3) | Sep 17, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [6ffc1e94a8](https://linux-hardware.org/?probe=6ffc1e94a8) | Sep 17, 2021 |
| AWOW          | AK41                        | Desktop     | [4acb262154](https://linux-hardware.org/?probe=4acb262154) | Sep 17, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [0198772029](https://linux-hardware.org/?probe=0198772029) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0abd7690c0](https://linux-hardware.org/?probe=0abd7690c0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | Notebook    | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [220acb8f8f](https://linux-hardware.org/?probe=220acb8f8f) | Sep 16, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [6bc981dced](https://linux-hardware.org/?probe=6bc981dced) | Sep 16, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [0e1e6ded7b](https://linux-hardware.org/?probe=0e1e6ded7b) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | Notebook    | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [03747e8a64](https://linux-hardware.org/?probe=03747e8a64) | Sep 15, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [36dbfef2b7](https://linux-hardware.org/?probe=36dbfef2b7) | Sep 15, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [aa3f685f0a](https://linux-hardware.org/?probe=aa3f685f0a) | Sep 15, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [cd630332c7](https://linux-hardware.org/?probe=cd630332c7) | Sep 15, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [bcb153aec3](https://linux-hardware.org/?probe=bcb153aec3) | Sep 15, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d0e1428a82](https://linux-hardware.org/?probe=d0e1428a82) | Sep 15, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f84ec7de50](https://linux-hardware.org/?probe=f84ec7de50) | Sep 15, 2021 |
| Toshiba       | Satellite Pro C850-1H8      | Notebook    | [ea23c035b2](https://linux-hardware.org/?probe=ea23c035b2) | Sep 15, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [bd0090fcf5](https://linux-hardware.org/?probe=bd0090fcf5) | Sep 15, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7159ae163a](https://linux-hardware.org/?probe=7159ae163a) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [9ec65d8702](https://linux-hardware.org/?probe=9ec65d8702) | Sep 14, 2021 |
| Intel         | NUC7JYB J67969-401          | Mini pc     | [c1f78b36e0](https://linux-hardware.org/?probe=c1f78b36e0) | Sep 14, 2021 |
| HP            | 8446                        | All in one  | [7744251d76](https://linux-hardware.org/?probe=7744251d76) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [0c17be4850](https://linux-hardware.org/?probe=0c17be4850) | Sep 14, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [3a3d47ae61](https://linux-hardware.org/?probe=3a3d47ae61) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [afe7ce5dd8](https://linux-hardware.org/?probe=afe7ce5dd8) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1e5aa389bc](https://linux-hardware.org/?probe=1e5aa389bc) | Sep 13, 2021 |
| ASRock        | Q77M vPro                   | Desktop     | [4ee80780df](https://linux-hardware.org/?probe=4ee80780df) | Sep 13, 2021 |
| ASRock        | Q77M vPro                   | Desktop     | [11278bcc7d](https://linux-hardware.org/?probe=11278bcc7d) | Sep 13, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [76922d0f6e](https://linux-hardware.org/?probe=76922d0f6e) | Sep 13, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [eee9e1661b](https://linux-hardware.org/?probe=eee9e1661b) | Sep 13, 2021 |
| GPD           | MicroPC                     | Notebook    | [e389ea1b46](https://linux-hardware.org/?probe=e389ea1b46) | Sep 13, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [bc67d877ef](https://linux-hardware.org/?probe=bc67d877ef) | Sep 13, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [90d1ec7a8e](https://linux-hardware.org/?probe=90d1ec7a8e) | Sep 12, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Latitude E5500              | Notebook    | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [f1c929c7fe](https://linux-hardware.org/?probe=f1c929c7fe) | Sep 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddde472ce9](https://linux-hardware.org/?probe=ddde472ce9) | Sep 11, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [de627f1a6c](https://linux-hardware.org/?probe=de627f1a6c) | Sep 10, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4721566a56](https://linux-hardware.org/?probe=4721566a56) | Sep 10, 2021 |
| Intel         | DG45FC AAE27730-305         | Desktop     | [5f39b924e3](https://linux-hardware.org/?probe=5f39b924e3) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [0e84cda6a6](https://linux-hardware.org/?probe=0e84cda6a6) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| HP            | Notebook                    | Notebook    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [b8fecfa6b6](https://linux-hardware.org/?probe=b8fecfa6b6) | Sep 09, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [e5ff747ab0](https://linux-hardware.org/?probe=e5ff747ab0) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| Acer          | Aspire M1930                | Desktop     | [b302c41ff0](https://linux-hardware.org/?probe=b302c41ff0) | Sep 09, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [570aa41791](https://linux-hardware.org/?probe=570aa41791) | Sep 09, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [044e6afdf4](https://linux-hardware.org/?probe=044e6afdf4) | Sep 09, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [92b0b6c126](https://linux-hardware.org/?probe=92b0b6c126) | Sep 09, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [619576a8a6](https://linux-hardware.org/?probe=619576a8a6) | Sep 09, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [1bc618039b](https://linux-hardware.org/?probe=1bc618039b) | Sep 09, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [514665210d](https://linux-hardware.org/?probe=514665210d) | Sep 09, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [443986835d](https://linux-hardware.org/?probe=443986835d) | Sep 09, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [b89568cf4b](https://linux-hardware.org/?probe=b89568cf4b) | Sep 09, 2021 |
| Linx          | LINX1010B                   | Notebook    | [9dd21e89cd](https://linux-hardware.org/?probe=9dd21e89cd) | Sep 09, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [5f255ee421](https://linux-hardware.org/?probe=5f255ee421) | Sep 08, 2021 |
| Biostar       | A780L3C                     | Desktop     | [65fe5eaa0f](https://linux-hardware.org/?probe=65fe5eaa0f) | Sep 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8fb079c22c](https://linux-hardware.org/?probe=8fb079c22c) | Sep 08, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eff923e231](https://linux-hardware.org/?probe=eff923e231) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [39518c4805](https://linux-hardware.org/?probe=39518c4805) | Sep 08, 2021 |
| Maibenben     | PC34 V1.0                   | Desktop     | [dd82d2282e](https://linux-hardware.org/?probe=dd82d2282e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| HP            | ENVY Notebook               | Notebook    | [5dbf3a9523](https://linux-hardware.org/?probe=5dbf3a9523) | Sep 08, 2021 |
| HP            | ENVY Notebook               | Notebook    | [3f338ee0d6](https://linux-hardware.org/?probe=3f338ee0d6) | Sep 08, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [0138372e13](https://linux-hardware.org/?probe=0138372e13) | Sep 07, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [922e1625b6](https://linux-hardware.org/?probe=922e1625b6) | Sep 07, 2021 |
| ASUSTek       | P5E                         | Desktop     | [f2536ac0ff](https://linux-hardware.org/?probe=f2536ac0ff) | Sep 07, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [4963032754](https://linux-hardware.org/?probe=4963032754) | Sep 07, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0C50... | Notebook    | [5ac7df1c1c](https://linux-hardware.org/?probe=5ac7df1c1c) | Sep 07, 2021 |
| HP            | 84DE                        | All in one  | [995c565e2c](https://linux-hardware.org/?probe=995c565e2c) | Sep 07, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [7ca1df084e](https://linux-hardware.org/?probe=7ca1df084e) | Sep 07, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [b094346e99](https://linux-hardware.org/?probe=b094346e99) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [e0fba8ec14](https://linux-hardware.org/?probe=e0fba8ec14) | Sep 07, 2021 |
| Toshiba       | TECRA M9                    | Notebook    | [75287979cc](https://linux-hardware.org/?probe=75287979cc) | Sep 07, 2021 |
| Acer          | Aspire 7738                 | Notebook    | [ab6b1bb415](https://linux-hardware.org/?probe=ab6b1bb415) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [e7d6b0559a](https://linux-hardware.org/?probe=e7d6b0559a) | Sep 06, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [1969f4e6ec](https://linux-hardware.org/?probe=1969f4e6ec) | Sep 06, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [b5e3a47db9](https://linux-hardware.org/?probe=b5e3a47db9) | Sep 06, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [938b16305c](https://linux-hardware.org/?probe=938b16305c) | Sep 06, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [67630c1611](https://linux-hardware.org/?probe=67630c1611) | Sep 06, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [6139009738](https://linux-hardware.org/?probe=6139009738) | Sep 05, 2021 |
| Dell          | Latitude E7450              | Notebook    | [090d2bd5c7](https://linux-hardware.org/?probe=090d2bd5c7) | Sep 05, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9c948c3882](https://linux-hardware.org/?probe=9c948c3882) | Sep 05, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7aeb789bf5](https://linux-hardware.org/?probe=7aeb789bf5) | Sep 05, 2021 |
| Gateway       | NV57H                       | Notebook    | [efa8fe88d3](https://linux-hardware.org/?probe=efa8fe88d3) | Sep 05, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [9da21e8c06](https://linux-hardware.org/?probe=9da21e8c06) | Sep 05, 2021 |
| Dell          | Latitude E6410              | Notebook    | [62c06fee3f](https://linux-hardware.org/?probe=62c06fee3f) | Sep 04, 2021 |
| Eii           | WSA116                      | Notebook    | [c3a328b794](https://linux-hardware.org/?probe=c3a328b794) | Sep 04, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [938038dc19](https://linux-hardware.org/?probe=938038dc19) | Sep 04, 2021 |
| Dell          | 0HP962                      | Desktop     | [48d5a5e8ef](https://linux-hardware.org/?probe=48d5a5e8ef) | Sep 04, 2021 |
| Dell          | Latitude E6410              | Notebook    | [68bfcce1f7](https://linux-hardware.org/?probe=68bfcce1f7) | Sep 04, 2021 |
| Chuwi         | CoreBook Pro                | Notebook    | [0fcccea10f](https://linux-hardware.org/?probe=0fcccea10f) | Sep 04, 2021 |
| Eii           | WSA116                      | Notebook    | [bad23ad0a0](https://linux-hardware.org/?probe=bad23ad0a0) | Sep 04, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f07151c6ac](https://linux-hardware.org/?probe=f07151c6ac) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [4d7a9bb2cf](https://linux-hardware.org/?probe=4d7a9bb2cf) | Sep 04, 2021 |
| Dell          | Latitude E7450              | Notebook    | [c2d943414c](https://linux-hardware.org/?probe=c2d943414c) | Sep 04, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [d2bba3f247](https://linux-hardware.org/?probe=d2bba3f247) | Sep 03, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [811f366c65](https://linux-hardware.org/?probe=811f366c65) | Sep 03, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0701437d79](https://linux-hardware.org/?probe=0701437d79) | Sep 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [eb63e95eda](https://linux-hardware.org/?probe=eb63e95eda) | Sep 03, 2021 |
| ASUSTek       | GR8                         | Notebook    | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [b548c2ffad](https://linux-hardware.org/?probe=b548c2ffad) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [43c77616d3](https://linux-hardware.org/?probe=43c77616d3) | Sep 02, 2021 |
| Dell          | 0J3C2F A01                  | Desktop     | [57e7819c28](https://linux-hardware.org/?probe=57e7819c28) | Sep 02, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [49170bd478](https://linux-hardware.org/?probe=49170bd478) | Sep 02, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Jumper        | EZbook                      | Notebook    | [d353bb80f2](https://linux-hardware.org/?probe=d353bb80f2) | Sep 02, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [67978afd9a](https://linux-hardware.org/?probe=67978afd9a) | Sep 01, 2021 |
| Lenovo        | 3703 SDK0J40700 WIN 3258... | All in one  | [5da493de55](https://linux-hardware.org/?probe=5da493de55) | Sep 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [7bb30a79c1](https://linux-hardware.org/?probe=7bb30a79c1) | Sep 01, 2021 |
| Fusion5       | FWIN232 PLUS                | Tablet      | [e6a99aea30](https://linux-hardware.org/?probe=e6a99aea30) | Sep 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ad1fdaa4c8](https://linux-hardware.org/?probe=ad1fdaa4c8) | Sep 01, 2021 |
| Dell          | 0N047H A03                  | Server      | [fef0199664](https://linux-hardware.org/?probe=fef0199664) | Sep 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [6ce2d4fb15](https://linux-hardware.org/?probe=6ce2d4fb15) | Sep 01, 2021 |
| Acer          | Aspire A315-54              | Notebook    | [402fd1200d](https://linux-hardware.org/?probe=402fd1200d) | Aug 31, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [e1dfe46f2f](https://linux-hardware.org/?probe=e1dfe46f2f) | Aug 31, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [8a4f402be1](https://linux-hardware.org/?probe=8a4f402be1) | Aug 31, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [32eee16f4c](https://linux-hardware.org/?probe=32eee16f4c) | Aug 31, 2021 |
| MSI           | E350DM-E33                  | Desktop     | [d1bc30b527](https://linux-hardware.org/?probe=d1bc30b527) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9a332493d0](https://linux-hardware.org/?probe=9a332493d0) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a3fee1671b](https://linux-hardware.org/?probe=a3fee1671b) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [8f1f4a2c99](https://linux-hardware.org/?probe=8f1f4a2c99) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [d33400a4fe](https://linux-hardware.org/?probe=d33400a4fe) | Aug 31, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [858de30180](https://linux-hardware.org/?probe=858de30180) | Aug 31, 2021 |
| Gigabyte      | X7V2                        | Notebook    | [320c23f0d7](https://linux-hardware.org/?probe=320c23f0d7) | Aug 31, 2021 |
| ASUSTek       | H110M-A                     | Desktop     | [1ce9477a20](https://linux-hardware.org/?probe=1ce9477a20) | Aug 31, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [3b8f234fa8](https://linux-hardware.org/?probe=3b8f234fa8) | Aug 31, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b86e557def](https://linux-hardware.org/?probe=b86e557def) | Aug 31, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [5e8d8b35df](https://linux-hardware.org/?probe=5e8d8b35df) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [9526471745](https://linux-hardware.org/?probe=9526471745) | Aug 30, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [d532b9c69c](https://linux-hardware.org/?probe=d532b9c69c) | Aug 30, 2021 |
| Sony          | SVE1712C5E                  | Notebook    | [4b7551ddca](https://linux-hardware.org/?probe=4b7551ddca) | Aug 30, 2021 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [06ee7d4c06](https://linux-hardware.org/?probe=06ee7d4c06) | Aug 30, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Notebook      | N150CU                      | Notebook    | [089eb8d3f8](https://linux-hardware.org/?probe=089eb8d3f8) | Aug 30, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [c56901e13e](https://linux-hardware.org/?probe=c56901e13e) | Aug 30, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [e120bda033](https://linux-hardware.org/?probe=e120bda033) | Aug 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [2ee21f9b6e](https://linux-hardware.org/?probe=2ee21f9b6e) | Aug 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a828ec8dd0](https://linux-hardware.org/?probe=a828ec8dd0) | Aug 30, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [875e21217a](https://linux-hardware.org/?probe=875e21217a) | Aug 30, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [bc5e53f3e1](https://linux-hardware.org/?probe=bc5e53f3e1) | Aug 29, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [13159b5018](https://linux-hardware.org/?probe=13159b5018) | Aug 29, 2021 |
| Sony          | SVE1511P1EW                 | Notebook    | [1d6a07ca23](https://linux-hardware.org/?probe=1d6a07ca23) | Aug 29, 2021 |
| Lenovo        | ThinkPad X260 20F600A2UK    | Notebook    | [a0b76184c5](https://linux-hardware.org/?probe=a0b76184c5) | Aug 29, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [7d6dae82da](https://linux-hardware.org/?probe=7d6dae82da) | Aug 29, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a089d56f43](https://linux-hardware.org/?probe=a089d56f43) | Aug 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c03162947f](https://linux-hardware.org/?probe=c03162947f) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| Teclast       | F15 Plus                    | Notebook    | [68843ef68c](https://linux-hardware.org/?probe=68843ef68c) | Aug 28, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | Notebook    | [167a9692d8](https://linux-hardware.org/?probe=167a9692d8) | Aug 28, 2021 |
| Acer          | Aspire 5745DG               | Notebook    | [17516ffffa](https://linux-hardware.org/?probe=17516ffffa) | Aug 28, 2021 |
| Sony          | SVE1511P1EW                 | Notebook    | [d94d23606c](https://linux-hardware.org/?probe=d94d23606c) | Aug 28, 2021 |
| Lenovo        | ThinkStation D20 415579G    | Desktop     | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b90ff9465e](https://linux-hardware.org/?probe=b90ff9465e) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b1272a2d2d](https://linux-hardware.org/?probe=b1272a2d2d) | Aug 28, 2021 |
| Acer          | Aspire 5745DG               | Notebook    | [2d07a72cbe](https://linux-hardware.org/?probe=2d07a72cbe) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4d249ae75f](https://linux-hardware.org/?probe=4d249ae75f) | Aug 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f6fa665265](https://linux-hardware.org/?probe=f6fa665265) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | Desktop     | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [7e1625f75d](https://linux-hardware.org/?probe=7e1625f75d) | Aug 27, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [c488aefbc6](https://linux-hardware.org/?probe=c488aefbc6) | Aug 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [dcbc419b6b](https://linux-hardware.org/?probe=dcbc419b6b) | Aug 26, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [285a023dd8](https://linux-hardware.org/?probe=285a023dd8) | Aug 26, 2021 |
| Teclast       | F15 Plus                    | Notebook    | [1da9444bdf](https://linux-hardware.org/?probe=1da9444bdf) | Aug 26, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [1fc077ad52](https://linux-hardware.org/?probe=1fc077ad52) | Aug 26, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [44472e729c](https://linux-hardware.org/?probe=44472e729c) | Aug 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ed679d238e](https://linux-hardware.org/?probe=ed679d238e) | Aug 26, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b5f3118201](https://linux-hardware.org/?probe=b5f3118201) | Aug 26, 2021 |
| ASRock        | H61M-ITX                    | Desktop     | [4f191c568f](https://linux-hardware.org/?probe=4f191c568f) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [d88bb2ec02](https://linux-hardware.org/?probe=d88bb2ec02) | Aug 26, 2021 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [dd4f9a4e00](https://linux-hardware.org/?probe=dd4f9a4e00) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2509d57e06](https://linux-hardware.org/?probe=2509d57e06) | Aug 25, 2021 |
| MSI           | GP62 7RD                    | Notebook    | [79183c00ea](https://linux-hardware.org/?probe=79183c00ea) | Aug 25, 2021 |
| HP            | Pavilion 15                 | Notebook    | [3535aaba36](https://linux-hardware.org/?probe=3535aaba36) | Aug 25, 2021 |
| Clevo         | P7xxDM2-G                   | Notebook    | [3ec36f9808](https://linux-hardware.org/?probe=3ec36f9808) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f4f3979169](https://linux-hardware.org/?probe=f4f3979169) | Aug 24, 2021 |
| Supermicro    | X8DTH                       | Server      | [e7e8b73641](https://linux-hardware.org/?probe=e7e8b73641) | Aug 24, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [268ea8030b](https://linux-hardware.org/?probe=268ea8030b) | Aug 24, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [5d6a3388dc](https://linux-hardware.org/?probe=5d6a3388dc) | Aug 24, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| Dell          | 0PU052                      | Desktop     | [639d8ed1b3](https://linux-hardware.org/?probe=639d8ed1b3) | Aug 23, 2021 |
| GEO           | GeoBook3                    | Notebook    | [fd999a9ccb](https://linux-hardware.org/?probe=fd999a9ccb) | Aug 23, 2021 |
| eMachines     | E525                        | Notebook    | [b50ab92d73](https://linux-hardware.org/?probe=b50ab92d73) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| Lenovo        | ThinkPad X220 4290PC9       | Notebook    | [1da25f0c39](https://linux-hardware.org/?probe=1da25f0c39) | Aug 23, 2021 |
| Lenovo        | ThinkPad X220 4290PC9       | Notebook    | [3003d19058](https://linux-hardware.org/?probe=3003d19058) | Aug 23, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [5947294929](https://linux-hardware.org/?probe=5947294929) | Aug 23, 2021 |
| Dell          | 0PU052                      | Desktop     | [7d02b28426](https://linux-hardware.org/?probe=7d02b28426) | Aug 23, 2021 |
| Dell          | Studio 1569                 | Notebook    | [600cbb330c](https://linux-hardware.org/?probe=600cbb330c) | Aug 23, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [fc54dc715f](https://linux-hardware.org/?probe=fc54dc715f) | Aug 23, 2021 |
| Dell          | Latitude E6410              | Notebook    | [764744f17c](https://linux-hardware.org/?probe=764744f17c) | Aug 23, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [5058172a35](https://linux-hardware.org/?probe=5058172a35) | Aug 22, 2021 |
| MSI           | E350DM-E33                  | Desktop     | [c1f85a0dd1](https://linux-hardware.org/?probe=c1f85a0dd1) | Aug 22, 2021 |
| Toshiba       | Satellite C55D-A-15H        | Notebook    | [68c3524d9f](https://linux-hardware.org/?probe=68c3524d9f) | Aug 22, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [9de02c2502](https://linux-hardware.org/?probe=9de02c2502) | Aug 22, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [592ec5b28e](https://linux-hardware.org/?probe=592ec5b28e) | Aug 22, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [f462df4832](https://linux-hardware.org/?probe=f462df4832) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [e0eedc1563](https://linux-hardware.org/?probe=e0eedc1563) | Aug 22, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c1434ce76](https://linux-hardware.org/?probe=1c1434ce76) | Aug 21, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [64757557ed](https://linux-hardware.org/?probe=64757557ed) | Aug 21, 2021 |
| Teclast       | F15S                        | Notebook    | [29cf2b77a8](https://linux-hardware.org/?probe=29cf2b77a8) | Aug 21, 2021 |
| ASUSTek       | ZenBook UX434FQ             | Notebook    | [e5778c606b](https://linux-hardware.org/?probe=e5778c606b) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| HP            | EliteBook 820 G4            | Notebook    | [d31c0fcaac](https://linux-hardware.org/?probe=d31c0fcaac) | Aug 21, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d79e5a84](https://linux-hardware.org/?probe=18d79e5a84) | Aug 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d6672308c5](https://linux-hardware.org/?probe=d6672308c5) | Aug 20, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [a679909847](https://linux-hardware.org/?probe=a679909847) | Aug 20, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [83dc2b2034](https://linux-hardware.org/?probe=83dc2b2034) | Aug 20, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| Teclast       | F15S                        | Notebook    | [256a38cfc0](https://linux-hardware.org/?probe=256a38cfc0) | Aug 20, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [6f08d0dd20](https://linux-hardware.org/?probe=6f08d0dd20) | Aug 20, 2021 |
| Dell          | 0RY007                      | Desktop     | [c0cc6172aa](https://linux-hardware.org/?probe=c0cc6172aa) | Aug 20, 2021 |
| Dell          | Latitude E4200              | Notebook    | [db5bad5ade](https://linux-hardware.org/?probe=db5bad5ade) | Aug 20, 2021 |
| HP            | ElitePad 1000 G2            | Notebook    | [d8d2d8a3d6](https://linux-hardware.org/?probe=d8d2d8a3d6) | Aug 20, 2021 |
| Lenovo        | ThinkPad T580 20LAS5XS00    | Notebook    | [472494a25c](https://linux-hardware.org/?probe=472494a25c) | Aug 20, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [6d4b2d1904](https://linux-hardware.org/?probe=6d4b2d1904) | Aug 19, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | Notebook    | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| HP            | Presario C700               | Notebook    | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| RuggedPC      | Caterpillar T20             | Tablet      | [1bf2275be4](https://linux-hardware.org/?probe=1bf2275be4) | Aug 19, 2021 |
| Dell          | Latitude 7390               | Notebook    | [d45edee596](https://linux-hardware.org/?probe=d45edee596) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Dell          | Latitude 7390               | Notebook    | [a24f4f931b](https://linux-hardware.org/?probe=a24f4f931b) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [969bb451d5](https://linux-hardware.org/?probe=969bb451d5) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | Notebook    | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Dell          | Latitude E6330              | Notebook    | [6116924818](https://linux-hardware.org/?probe=6116924818) | Aug 19, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [5b5ab8ed19](https://linux-hardware.org/?probe=5b5ab8ed19) | Aug 18, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [8ebd81f2b9](https://linux-hardware.org/?probe=8ebd81f2b9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | Notebook    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Lenovo        | H330                        | Desktop     | [3de8569fe7](https://linux-hardware.org/?probe=3de8569fe7) | Aug 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [701e3f8543](https://linux-hardware.org/?probe=701e3f8543) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| Dell          | Latitude 5401               | Notebook    | [9fd21a3e30](https://linux-hardware.org/?probe=9fd21a3e30) | Aug 18, 2021 |
| Toshiba       | PORTEGE Z930                | Notebook    | [a49ad7f306](https://linux-hardware.org/?probe=a49ad7f306) | Aug 18, 2021 |
| PC Special... | N130BU                      | Notebook    | [5fee63c283](https://linux-hardware.org/?probe=5fee63c283) | Aug 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [584785653a](https://linux-hardware.org/?probe=584785653a) | Aug 17, 2021 |
| Unknown       | TB-4000                     | Desktop     | [19fe989de3](https://linux-hardware.org/?probe=19fe989de3) | Aug 17, 2021 |
| Unknown       | TB-4000                     | Desktop     | [2cff8a7294](https://linux-hardware.org/?probe=2cff8a7294) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325V1K       | Notebook    | [7d414b5aee](https://linux-hardware.org/?probe=7d414b5aee) | Aug 17, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [b9a9785dcc](https://linux-hardware.org/?probe=b9a9785dcc) | Aug 17, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [10cec0686e](https://linux-hardware.org/?probe=10cec0686e) | Aug 17, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [d379d1e2a5](https://linux-hardware.org/?probe=d379d1e2a5) | Aug 16, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [2ec59cc4a3](https://linux-hardware.org/?probe=2ec59cc4a3) | Aug 16, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [537aee667d](https://linux-hardware.org/?probe=537aee667d) | Aug 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 2B3E                        | All in one  | [d2de88ef3c](https://linux-hardware.org/?probe=d2de88ef3c) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e47965ba8](https://linux-hardware.org/?probe=8e47965ba8) | Aug 15, 2021 |
| Acer          | Aspire E500                 | Desktop     | [90210dde7b](https://linux-hardware.org/?probe=90210dde7b) | Aug 15, 2021 |
| Acer          | Aspire E500                 | Desktop     | [b6d4223ae5](https://linux-hardware.org/?probe=b6d4223ae5) | Aug 15, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [e0da7c67e7](https://linux-hardware.org/?probe=e0da7c67e7) | Aug 15, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [4050883692](https://linux-hardware.org/?probe=4050883692) | Aug 15, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [ef71998e85](https://linux-hardware.org/?probe=ef71998e85) | Aug 15, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [37efc109dc](https://linux-hardware.org/?probe=37efc109dc) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f406892aa9](https://linux-hardware.org/?probe=f406892aa9) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b333da4703](https://linux-hardware.org/?probe=b333da4703) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [a6e0859eac](https://linux-hardware.org/?probe=a6e0859eac) | Aug 14, 2021 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [400f842023](https://linux-hardware.org/?probe=400f842023) | Aug 14, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [7828e457fd](https://linux-hardware.org/?probe=7828e457fd) | Aug 14, 2021 |
| Dell          | Vostro 14 5401              | Notebook    | [af21a56956](https://linux-hardware.org/?probe=af21a56956) | Aug 14, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9a62c654ea](https://linux-hardware.org/?probe=9a62c654ea) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [5ce5d800d3](https://linux-hardware.org/?probe=5ce5d800d3) | Aug 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [dfe51161fe](https://linux-hardware.org/?probe=dfe51161fe) | Aug 14, 2021 |
| ECS           | H61H2-TI                    | All in one  | [dd57d8772a](https://linux-hardware.org/?probe=dd57d8772a) | Aug 14, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [8339d132a3](https://linux-hardware.org/?probe=8339d132a3) | Aug 14, 2021 |
| Dell          | 0MH651                      | Desktop     | [5268cfdd62](https://linux-hardware.org/?probe=5268cfdd62) | Aug 14, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [599f91ad85](https://linux-hardware.org/?probe=599f91ad85) | Aug 14, 2021 |
| HP            | 630                         | Notebook    | [d55ac2f925](https://linux-hardware.org/?probe=d55ac2f925) | Aug 14, 2021 |
| ASRock        | X300TM-ITX                  | Desktop     | [7a67243762](https://linux-hardware.org/?probe=7a67243762) | Aug 14, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [816a9456a3](https://linux-hardware.org/?probe=816a9456a3) | Aug 14, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [a746c422c5](https://linux-hardware.org/?probe=a746c422c5) | Aug 14, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [cd8b8b47eb](https://linux-hardware.org/?probe=cd8b8b47eb) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Apple         | MacBookPro15,2              | Notebook    | [63f618a951](https://linux-hardware.org/?probe=63f618a951) | Aug 13, 2021 |
| Intel         | B75                         | Desktop     | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [ccc387436e](https://linux-hardware.org/?probe=ccc387436e) | Aug 13, 2021 |
| Dell          | Precision 7550              | Notebook    | [71ea7d7b3b](https://linux-hardware.org/?probe=71ea7d7b3b) | Aug 13, 2021 |
| Lenovo        | ThinkCentre Edge72 3484F... | Desktop     | [49c7fa8df0](https://linux-hardware.org/?probe=49c7fa8df0) | Aug 13, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [790aecb1f9](https://linux-hardware.org/?probe=790aecb1f9) | Aug 12, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [9f0ff56bae](https://linux-hardware.org/?probe=9f0ff56bae) | Aug 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [490660f375](https://linux-hardware.org/?probe=490660f375) | Aug 12, 2021 |
| Dell          | Latitude 5300               | Notebook    | [17a1dbdc0d](https://linux-hardware.org/?probe=17a1dbdc0d) | Aug 12, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [34848a17dc](https://linux-hardware.org/?probe=34848a17dc) | Aug 12, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Jumper        | EZbook                      | Notebook    | [2b7966034e](https://linux-hardware.org/?probe=2b7966034e) | Aug 11, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [73dd46e48a](https://linux-hardware.org/?probe=73dd46e48a) | Aug 11, 2021 |
| Supermicro    | X8DTH                       | Server      | [9cdd18878b](https://linux-hardware.org/?probe=9cdd18878b) | Aug 11, 2021 |
| eMachines     | E520 V1.06                  | Notebook    | [4f4024098f](https://linux-hardware.org/?probe=4f4024098f) | Aug 10, 2021 |
| Dell          | 0PU052                      | Desktop     | [950d7b72b8](https://linux-hardware.org/?probe=950d7b72b8) | Aug 10, 2021 |
| TYAN Compu... | S3970                       | Desktop     | [89a0dfa231](https://linux-hardware.org/?probe=89a0dfa231) | Aug 10, 2021 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [dc6d81f2c5](https://linux-hardware.org/?probe=dc6d81f2c5) | Aug 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [02a92f8ff3](https://linux-hardware.org/?probe=02a92f8ff3) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [2e1d243729](https://linux-hardware.org/?probe=2e1d243729) | Aug 10, 2021 |
| MSI           | FM2-A55M-P33                | Desktop     | [22ffcc8c10](https://linux-hardware.org/?probe=22ffcc8c10) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [cc3235c479](https://linux-hardware.org/?probe=cc3235c479) | Aug 09, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [e658937af2](https://linux-hardware.org/?probe=e658937af2) | Aug 09, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [3f30f452cf](https://linux-hardware.org/?probe=3f30f452cf) | Aug 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d914912052](https://linux-hardware.org/?probe=d914912052) | Aug 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [31f5694698](https://linux-hardware.org/?probe=31f5694698) | Aug 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [88cd03034a](https://linux-hardware.org/?probe=88cd03034a) | Aug 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d01419ba41](https://linux-hardware.org/?probe=d01419ba41) | Aug 08, 2021 |
| PC Special... | GK7NR0R                     | Notebook    | [97aec9c50f](https://linux-hardware.org/?probe=97aec9c50f) | Aug 08, 2021 |
| Dell          | Inspiron 1501               | Notebook    | [58a2ef72c9](https://linux-hardware.org/?probe=58a2ef72c9) | Aug 08, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9ca022bb25](https://linux-hardware.org/?probe=9ca022bb25) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | Desktop     | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| Acer          | Aspire 4820T                | Notebook    | [3711d645ea](https://linux-hardware.org/?probe=3711d645ea) | Aug 08, 2021 |
| MSI           | FM2-A55M-P33                | Desktop     | [5b435fd416](https://linux-hardware.org/?probe=5b435fd416) | Aug 08, 2021 |
| Jumper        | EZbook                      | Convertible | [bdc5a26fce](https://linux-hardware.org/?probe=bdc5a26fce) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [6db6e2e64e](https://linux-hardware.org/?probe=6db6e2e64e) | Aug 07, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [1cec27cddd](https://linux-hardware.org/?probe=1cec27cddd) | Aug 07, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [fd27db6b06](https://linux-hardware.org/?probe=fd27db6b06) | Aug 07, 2021 |
| MSI           | Z97 GAMING 9 AC             | Desktop     | [17ce8c5436](https://linux-hardware.org/?probe=17ce8c5436) | Aug 07, 2021 |
| Panasonic     | CF-19KDR78CE                | Notebook    | [29eee33555](https://linux-hardware.org/?probe=29eee33555) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [bbaf2f86e2](https://linux-hardware.org/?probe=bbaf2f86e2) | Aug 07, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [fd15e7b399](https://linux-hardware.org/?probe=fd15e7b399) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [24d92ae4db](https://linux-hardware.org/?probe=24d92ae4db) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [33674e8363](https://linux-hardware.org/?probe=33674e8363) | Aug 07, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [5049ffb672](https://linux-hardware.org/?probe=5049ffb672) | Aug 07, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [6222e37530](https://linux-hardware.org/?probe=6222e37530) | Aug 06, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [09fa4c99dc](https://linux-hardware.org/?probe=09fa4c99dc) | Aug 06, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3d75016d62](https://linux-hardware.org/?probe=3d75016d62) | Aug 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0a387b2df0](https://linux-hardware.org/?probe=0a387b2df0) | Aug 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [4c2763b512](https://linux-hardware.org/?probe=4c2763b512) | Aug 06, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e715646b33](https://linux-hardware.org/?probe=e715646b33) | Aug 05, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [f16fda6f0c](https://linux-hardware.org/?probe=f16fda6f0c) | Aug 05, 2021 |
| Dell          | 0MN1TX A03                  | Desktop     | [30bf6c3644](https://linux-hardware.org/?probe=30bf6c3644) | Aug 05, 2021 |
| Intel         | NUC9i5QNB K49247-403        | Mini pc     | [d553bc172b](https://linux-hardware.org/?probe=d553bc172b) | Aug 05, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [f3f2c36b90](https://linux-hardware.org/?probe=f3f2c36b90) | Aug 05, 2021 |
| Dell          | 0MN1TX A03                  | Desktop     | [5ed4bd700f](https://linux-hardware.org/?probe=5ed4bd700f) | Aug 05, 2021 |
| Lenovo        | ThinkPad T480s 20L70025U... | Notebook    | [6ac6264a7e](https://linux-hardware.org/?probe=6ac6264a7e) | Aug 05, 2021 |
| Lenovo        | ThinkPad T480s 20L70025U... | Notebook    | [88329f7bbc](https://linux-hardware.org/?probe=88329f7bbc) | Aug 05, 2021 |
| Intel         | H61M-S2PV                   | Desktop     | [a7ed913051](https://linux-hardware.org/?probe=a7ed913051) | Aug 05, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [943cd26aaa](https://linux-hardware.org/?probe=943cd26aaa) | Aug 05, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [554e2acead](https://linux-hardware.org/?probe=554e2acead) | Aug 05, 2021 |
| HP            | 3397                        | Desktop     | [40172ce141](https://linux-hardware.org/?probe=40172ce141) | Aug 04, 2021 |
| HP            | 3397                        | Desktop     | [720eb80d3e](https://linux-hardware.org/?probe=720eb80d3e) | Aug 04, 2021 |
| Intel         | NUC9i5QNB K49247-403        | Mini pc     | [4bc53024ba](https://linux-hardware.org/?probe=4bc53024ba) | Aug 04, 2021 |
| Samsung       | R519/R719                   | Notebook    | [63b8e64258](https://linux-hardware.org/?probe=63b8e64258) | Aug 04, 2021 |
| Dell          | Latitude E5500              | Notebook    | [0688139a45](https://linux-hardware.org/?probe=0688139a45) | Aug 04, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [76ae0e2554](https://linux-hardware.org/?probe=76ae0e2554) | Aug 04, 2021 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [6931fae5cc](https://linux-hardware.org/?probe=6931fae5cc) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [4c65635b12](https://linux-hardware.org/?probe=4c65635b12) | Aug 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [b9a947530b](https://linux-hardware.org/?probe=b9a947530b) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [fc2c2761bc](https://linux-hardware.org/?probe=fc2c2761bc) | Aug 03, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Notebook      | W65_67SZ                    | Notebook    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [f19b657d96](https://linux-hardware.org/?probe=f19b657d96) | Aug 03, 2021 |
| AMI           | Intel                       | Convertible | [af553a6cf8](https://linux-hardware.org/?probe=af553a6cf8) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Dell          | 0TY565                      | Desktop     | [e2b168eb4f](https://linux-hardware.org/?probe=e2b168eb4f) | Aug 02, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [a51160dff7](https://linux-hardware.org/?probe=a51160dff7) | Aug 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [dfdf1e3309](https://linux-hardware.org/?probe=dfdf1e3309) | Aug 02, 2021 |
| HP            | 2AE3                        | Desktop     | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [7b564a6ba6](https://linux-hardware.org/?probe=7b564a6ba6) | Aug 02, 2021 |
| HP            | Presario CQ61               | Notebook    | [b405d74912](https://linux-hardware.org/?probe=b405d74912) | Aug 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [f0164ad102](https://linux-hardware.org/?probe=f0164ad102) | Aug 02, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [cb617ee0fa](https://linux-hardware.org/?probe=cb617ee0fa) | Aug 02, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [fbd8d927e6](https://linux-hardware.org/?probe=fbd8d927e6) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [e9e0269b1a](https://linux-hardware.org/?probe=e9e0269b1a) | Aug 01, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [5144862148](https://linux-hardware.org/?probe=5144862148) | Aug 01, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | Notebook    | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [8486506e51](https://linux-hardware.org/?probe=8486506e51) | Aug 01, 2021 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [ce0a571a8e](https://linux-hardware.org/?probe=ce0a571a8e) | Aug 01, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [710ec38bd4](https://linux-hardware.org/?probe=710ec38bd4) | Aug 01, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [d9c0588d44](https://linux-hardware.org/?probe=d9c0588d44) | Aug 01, 2021 |
| HP            | 3648h                       | Desktop     | [b6fa1195a8](https://linux-hardware.org/?probe=b6fa1195a8) | Jul 31, 2021 |
| Dell          | Latitude E5520              | Notebook    | [495c7ad655](https://linux-hardware.org/?probe=495c7ad655) | Jul 31, 2021 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [43a6598dac](https://linux-hardware.org/?probe=43a6598dac) | Jul 31, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [3132af196e](https://linux-hardware.org/?probe=3132af196e) | Jul 31, 2021 |
| Acer          | Aspire 5920                 | Notebook    | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c46b65e280](https://linux-hardware.org/?probe=c46b65e280) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [28fd6ffaf6](https://linux-hardware.org/?probe=28fd6ffaf6) | Jul 30, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [6a85bc6617](https://linux-hardware.org/?probe=6a85bc6617) | Jul 29, 2021 |
| Samsung       | 935XDB                      | Notebook    | [ebc69d8a77](https://linux-hardware.org/?probe=ebc69d8a77) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| Intel         | DQ57TM AAE70931-404         | Desktop     | [ea8a454a4f](https://linux-hardware.org/?probe=ea8a454a4f) | Jul 29, 2021 |
| Acer          | Aspire V5-123               | Notebook    | [95f4089ece](https://linux-hardware.org/?probe=95f4089ece) | Jul 28, 2021 |
| Acer          | Aspire V5-123               | Notebook    | [06eeeeb88e](https://linux-hardware.org/?probe=06eeeeb88e) | Jul 28, 2021 |
| Packard Be... | EasyNote TK37               | Notebook    | [0bb3a8a239](https://linux-hardware.org/?probe=0bb3a8a239) | Jul 28, 2021 |
| Dell          | Inspiron 3502               | Notebook    | [9216707eed](https://linux-hardware.org/?probe=9216707eed) | Jul 28, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [105a1e855d](https://linux-hardware.org/?probe=105a1e855d) | Jul 28, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4772eaea38](https://linux-hardware.org/?probe=4772eaea38) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7fa4a7bf63](https://linux-hardware.org/?probe=7fa4a7bf63) | Jul 28, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4b4496337a](https://linux-hardware.org/?probe=4b4496337a) | Jul 27, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b00a4be291](https://linux-hardware.org/?probe=b00a4be291) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [e9628ef49a](https://linux-hardware.org/?probe=e9628ef49a) | Jul 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0a30fad96c](https://linux-hardware.org/?probe=0a30fad96c) | Jul 27, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [8120e40bf1](https://linux-hardware.org/?probe=8120e40bf1) | Jul 27, 2021 |
| Dell          | Latitude E5520              | Notebook    | [cae8dd2173](https://linux-hardware.org/?probe=cae8dd2173) | Jul 27, 2021 |
| OrangePi      | 4                           | Soc         | [b638d18837](https://linux-hardware.org/?probe=b638d18837) | Jul 27, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [7b93cc547a](https://linux-hardware.org/?probe=7b93cc547a) | Jul 27, 2021 |
| Biostar       | A780L3L                     | Desktop     | [fbf078ab5c](https://linux-hardware.org/?probe=fbf078ab5c) | Jul 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7770cf36c7](https://linux-hardware.org/?probe=7770cf36c7) | Jul 27, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Teclast       | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [4f0cb504ec](https://linux-hardware.org/?probe=4f0cb504ec) | Jul 26, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [855bff097c](https://linux-hardware.org/?probe=855bff097c) | Jul 26, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [c0b436063c](https://linux-hardware.org/?probe=c0b436063c) | Jul 26, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [51fe0127e7](https://linux-hardware.org/?probe=51fe0127e7) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Lenovo        | ThinkPad W541 20EGS3630L    | Notebook    | [f5300e1df8](https://linux-hardware.org/?probe=f5300e1df8) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [d0f249489f](https://linux-hardware.org/?probe=d0f249489f) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| HP            | 255 G3                      | Notebook    | [cd8de84d34](https://linux-hardware.org/?probe=cd8de84d34) | Jul 26, 2021 |
| HP            | G70                         | Notebook    | [70a70f922e](https://linux-hardware.org/?probe=70a70f922e) | Jul 26, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [3caa24688c](https://linux-hardware.org/?probe=3caa24688c) | Jul 26, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Acer          | Aspire X3990                | Desktop     | [82004eb423](https://linux-hardware.org/?probe=82004eb423) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Acer          | Aspire X3990                | Desktop     | [ff61ec9b47](https://linux-hardware.org/?probe=ff61ec9b47) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [074932b079](https://linux-hardware.org/?probe=074932b079) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [70ddebc8cc](https://linux-hardware.org/?probe=70ddebc8cc) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [455c830431](https://linux-hardware.org/?probe=455c830431) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [731b4837dc](https://linux-hardware.org/?probe=731b4837dc) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [96df68c59e](https://linux-hardware.org/?probe=96df68c59e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [edbcb6ab8d](https://linux-hardware.org/?probe=edbcb6ab8d) | Jul 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ac19f19ff3](https://linux-hardware.org/?probe=ac19f19ff3) | Jul 24, 2021 |
| Intel         | DQ57TM AAE70931-404         | Desktop     | [d9d7230d77](https://linux-hardware.org/?probe=d9d7230d77) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| HP            | G70                         | Notebook    | [ca61f66774](https://linux-hardware.org/?probe=ca61f66774) | Jul 24, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bf73ea51b4](https://linux-hardware.org/?probe=bf73ea51b4) | Jul 24, 2021 |
| Dell          | 02P9X9 A00                  | Server      | [b23b38cfa6](https://linux-hardware.org/?probe=b23b38cfa6) | Jul 24, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [2fc6763e52](https://linux-hardware.org/?probe=2fc6763e52) | Jul 24, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [a19ff7fb6a](https://linux-hardware.org/?probe=a19ff7fb6a) | Jul 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [d4c8d7a489](https://linux-hardware.org/?probe=d4c8d7a489) | Jul 23, 2021 |
| ASUSTek       | TP550LA                     | Notebook    | [2a5843180d](https://linux-hardware.org/?probe=2a5843180d) | Jul 23, 2021 |
| HP            | 3396                        | Desktop     | [59321676bc](https://linux-hardware.org/?probe=59321676bc) | Jul 23, 2021 |
| Dell          | Precision 7530              | Notebook    | [ae6bf75479](https://linux-hardware.org/?probe=ae6bf75479) | Jul 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [e05ed6b947](https://linux-hardware.org/?probe=e05ed6b947) | Jul 23, 2021 |
| HP            | 18E5                        | Desktop     | [52f8cb965f](https://linux-hardware.org/?probe=52f8cb965f) | Jul 22, 2021 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [8c32e162f5](https://linux-hardware.org/?probe=8c32e162f5) | Jul 22, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0112c3a302](https://linux-hardware.org/?probe=0112c3a302) | Jul 22, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [2b06fc5589](https://linux-hardware.org/?probe=2b06fc5589) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | Desktop     | [62eca59ba3](https://linux-hardware.org/?probe=62eca59ba3) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | Desktop     | [c469ee9d35](https://linux-hardware.org/?probe=c469ee9d35) | Jul 22, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [262db9da1d](https://linux-hardware.org/?probe=262db9da1d) | Jul 22, 2021 |
| Acer          | WMCP78M                     | Desktop     | [4d35606ff5](https://linux-hardware.org/?probe=4d35606ff5) | Jul 22, 2021 |
| Dell          | Latitude 5590               | Notebook    | [eed7897b2e](https://linux-hardware.org/?probe=eed7897b2e) | Jul 21, 2021 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [8e9fa75ba6](https://linux-hardware.org/?probe=8e9fa75ba6) | Jul 21, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [490d082b82](https://linux-hardware.org/?probe=490d082b82) | Jul 21, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [29e4fc068f](https://linux-hardware.org/?probe=29e4fc068f) | Jul 21, 2021 |
| Dell          | Latitude E6330              | Notebook    | [772c8f269b](https://linux-hardware.org/?probe=772c8f269b) | Jul 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [53c277ece0](https://linux-hardware.org/?probe=53c277ece0) | Jul 21, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fcc24e96e1](https://linux-hardware.org/?probe=fcc24e96e1) | Jul 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [d61be7331f](https://linux-hardware.org/?probe=d61be7331f) | Jul 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [7cd3b13d49](https://linux-hardware.org/?probe=7cd3b13d49) | Jul 20, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8aac3e0f74](https://linux-hardware.org/?probe=8aac3e0f74) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [eb9c99a6db](https://linux-hardware.org/?probe=eb9c99a6db) | Jul 20, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [daccb6a8e2](https://linux-hardware.org/?probe=daccb6a8e2) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [f1c20a19bb](https://linux-hardware.org/?probe=f1c20a19bb) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ff1bc803b](https://linux-hardware.org/?probe=1ff1bc803b) | Jul 19, 2021 |
| HP            | G62                         | Notebook    | [eb9037941e](https://linux-hardware.org/?probe=eb9037941e) | Jul 19, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [653301cedd](https://linux-hardware.org/?probe=653301cedd) | Jul 19, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2047045e78](https://linux-hardware.org/?probe=2047045e78) | Jul 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [29e1b14111](https://linux-hardware.org/?probe=29e1b14111) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e1d4b0e45d](https://linux-hardware.org/?probe=e1d4b0e45d) | Jul 18, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| Dell          | Inspiron 3780               | Notebook    | [b3bd1dbe25](https://linux-hardware.org/?probe=b3bd1dbe25) | Jul 18, 2021 |
| Dell          | Inspiron 3780               | Notebook    | [fba70c883f](https://linux-hardware.org/?probe=fba70c883f) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a2940be0c2](https://linux-hardware.org/?probe=a2940be0c2) | Jul 18, 2021 |
| Acer          | Veriton M680G               | Desktop     | [26d76634f5](https://linux-hardware.org/?probe=26d76634f5) | Jul 17, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [76152ddce8](https://linux-hardware.org/?probe=76152ddce8) | Jul 17, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [6075480dad](https://linux-hardware.org/?probe=6075480dad) | Jul 17, 2021 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [d26488aaaa](https://linux-hardware.org/?probe=d26488aaaa) | Jul 17, 2021 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [ac8b344912](https://linux-hardware.org/?probe=ac8b344912) | Jul 17, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [92e5b634e3](https://linux-hardware.org/?probe=92e5b634e3) | Jul 17, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [281e76021a](https://linux-hardware.org/?probe=281e76021a) | Jul 17, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [1c50e0b0ff](https://linux-hardware.org/?probe=1c50e0b0ff) | Jul 17, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [bedb8b374f](https://linux-hardware.org/?probe=bedb8b374f) | Jul 17, 2021 |
| EVGA          | 140-SS-E177                 | Desktop     | [f62e1f17ec](https://linux-hardware.org/?probe=f62e1f17ec) | Jul 16, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0d56a66148](https://linux-hardware.org/?probe=0d56a66148) | Jul 16, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [63feee4495](https://linux-hardware.org/?probe=63feee4495) | Jul 15, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [e5b47e2d75](https://linux-hardware.org/?probe=e5b47e2d75) | Jul 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [66444576e6](https://linux-hardware.org/?probe=66444576e6) | Jul 14, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [402385e552](https://linux-hardware.org/?probe=402385e552) | Jul 14, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [3c456ff1ff](https://linux-hardware.org/?probe=3c456ff1ff) | Jul 14, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP            | 829A                        | Mini pc     | [45e512f146](https://linux-hardware.org/?probe=45e512f146) | Jul 14, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [2fe5ad7a78](https://linux-hardware.org/?probe=2fe5ad7a78) | Jul 14, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [a087510823](https://linux-hardware.org/?probe=a087510823) | Jul 14, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [8d97ffe700](https://linux-hardware.org/?probe=8d97ffe700) | Jul 14, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [6dc021be20](https://linux-hardware.org/?probe=6dc021be20) | Jul 14, 2021 |
| ASUSTek       | UX32A                       | Notebook    | [0c2a7bcf53](https://linux-hardware.org/?probe=0c2a7bcf53) | Jul 14, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [929192be0f](https://linux-hardware.org/?probe=929192be0f) | Jul 14, 2021 |
| Dell          | 0RK936                      | Desktop     | [f0d44b4e2f](https://linux-hardware.org/?probe=f0d44b4e2f) | Jul 13, 2021 |
| Dell          | Precision M4600             | Notebook    | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5b9e8c2d22](https://linux-hardware.org/?probe=5b9e8c2d22) | Jul 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [e915c49d68](https://linux-hardware.org/?probe=e915c49d68) | Jul 13, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [72497bac92](https://linux-hardware.org/?probe=72497bac92) | Jul 12, 2021 |
| Pegatron      | 2A84h                       | Desktop     | [2320fe89e0](https://linux-hardware.org/?probe=2320fe89e0) | Jul 12, 2021 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [456981cfae](https://linux-hardware.org/?probe=456981cfae) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50f500af5b](https://linux-hardware.org/?probe=50f500af5b) | Jul 12, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ac11a7435b](https://linux-hardware.org/?probe=ac11a7435b) | Jul 12, 2021 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [422410f18b](https://linux-hardware.org/?probe=422410f18b) | Jul 12, 2021 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5301fe2213](https://linux-hardware.org/?probe=5301fe2213) | Jul 12, 2021 |
| Star Labs     | LabTop                      | Notebook    | [66b11f0101](https://linux-hardware.org/?probe=66b11f0101) | Jul 12, 2021 |
| Linx          | VISION004                   | Notebook    | [52bb79b8a7](https://linux-hardware.org/?probe=52bb79b8a7) | Jul 12, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [b856bd878e](https://linux-hardware.org/?probe=b856bd878e) | Jul 12, 2021 |
| Dell          | XPS 15 9575                 | Convertible | [9694d7fb43](https://linux-hardware.org/?probe=9694d7fb43) | Jul 12, 2021 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [2d2febc502](https://linux-hardware.org/?probe=2d2febc502) | Jul 11, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [44354be4d7](https://linux-hardware.org/?probe=44354be4d7) | Jul 11, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [975dc0ab8f](https://linux-hardware.org/?probe=975dc0ab8f) | Jul 11, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [62a4b43bb7](https://linux-hardware.org/?probe=62a4b43bb7) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7a7638e735](https://linux-hardware.org/?probe=7a7638e735) | Jul 11, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e6255c5a59](https://linux-hardware.org/?probe=e6255c5a59) | Jul 11, 2021 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [610b9319e9](https://linux-hardware.org/?probe=610b9319e9) | Jul 10, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [58f56b325b](https://linux-hardware.org/?probe=58f56b325b) | Jul 10, 2021 |
| Star Labs     | LabTop                      | Notebook    | [638d7361f8](https://linux-hardware.org/?probe=638d7361f8) | Jul 10, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [e7b4fc0440](https://linux-hardware.org/?probe=e7b4fc0440) | Jul 10, 2021 |
| Supermicro    | X8DTH                       | Server      | [2cd9beee8c](https://linux-hardware.org/?probe=2cd9beee8c) | Jul 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [aabd4b96a3](https://linux-hardware.org/?probe=aabd4b96a3) | Jul 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0b634b20a8](https://linux-hardware.org/?probe=0b634b20a8) | Jul 10, 2021 |
| Dell          | Precision M6800             | Notebook    | [0783858f11](https://linux-hardware.org/?probe=0783858f11) | Jul 09, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [ce4504e2f0](https://linux-hardware.org/?probe=ce4504e2f0) | Jul 09, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [927c1f1b83](https://linux-hardware.org/?probe=927c1f1b83) | Jul 09, 2021 |
| Lenovo        | IdeaCentre A310 10056       | All in one  | [8f25ed4108](https://linux-hardware.org/?probe=8f25ed4108) | Jul 09, 2021 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [3dab621700](https://linux-hardware.org/?probe=3dab621700) | Jul 09, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [65dab5ea20](https://linux-hardware.org/?probe=65dab5ea20) | Jul 08, 2021 |
| Acer          | Aspire X3990                | Desktop     | [93490ecc08](https://linux-hardware.org/?probe=93490ecc08) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [252e038506](https://linux-hardware.org/?probe=252e038506) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [bb7d68bae6](https://linux-hardware.org/?probe=bb7d68bae6) | Jul 08, 2021 |
| eMachines     | eME732                      | Notebook    | [50e1042533](https://linux-hardware.org/?probe=50e1042533) | Jul 08, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [cb24d096c3](https://linux-hardware.org/?probe=cb24d096c3) | Jul 08, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [f463800460](https://linux-hardware.org/?probe=f463800460) | Jul 08, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [34e19b7f44](https://linux-hardware.org/?probe=34e19b7f44) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | Notebook    | [34acf2547e](https://linux-hardware.org/?probe=34acf2547e) | Jul 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [36f2033f76](https://linux-hardware.org/?probe=36f2033f76) | Jul 07, 2021 |
| Acer          | Aspire 5749                 | Notebook    | [7aa3ecf46d](https://linux-hardware.org/?probe=7aa3ecf46d) | Jul 07, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [8c44ea27c9](https://linux-hardware.org/?probe=8c44ea27c9) | Jul 06, 2021 |
| ASUSTek       | X555LA                      | Notebook    | [9974f7325e](https://linux-hardware.org/?probe=9974f7325e) | Jul 06, 2021 |
| Biostar       | B450MH                      | Desktop     | [8c18de889a](https://linux-hardware.org/?probe=8c18de889a) | Jul 06, 2021 |
| HP            | 0A80h                       | Desktop     | [1d3b01bec4](https://linux-hardware.org/?probe=1d3b01bec4) | Jul 06, 2021 |
| HP            | 84DE                        | All in one  | [34723e30ec](https://linux-hardware.org/?probe=34723e30ec) | Jul 06, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [e2f7021326](https://linux-hardware.org/?probe=e2f7021326) | Jul 06, 2021 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [e1bee3cd30](https://linux-hardware.org/?probe=e1bee3cd30) | Jul 06, 2021 |
| Dell          | Precision M4400             | Notebook    | [684c6ee1c0](https://linux-hardware.org/?probe=684c6ee1c0) | Jul 06, 2021 |
| Lenovo        | ThinkPad X230 23252R0       | Notebook    | [cd6b8da5f5](https://linux-hardware.org/?probe=cd6b8da5f5) | Jul 06, 2021 |
| Lenovo        | ThinkPad X230 23252R0       | Notebook    | [8b7e31aeb4](https://linux-hardware.org/?probe=8b7e31aeb4) | Jul 06, 2021 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [fdf65e0442](https://linux-hardware.org/?probe=fdf65e0442) | Jul 06, 2021 |
| Entroware     | Apollo                      | Notebook    | [e707e4f502](https://linux-hardware.org/?probe=e707e4f502) | Jul 06, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [0345fe1b56](https://linux-hardware.org/?probe=0345fe1b56) | Jul 05, 2021 |
| Lenovo        | IdeaCentre A310 10056       | All in one  | [9d0bdddf87](https://linux-hardware.org/?probe=9d0bdddf87) | Jul 05, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [92cfe5edd3](https://linux-hardware.org/?probe=92cfe5edd3) | Jul 05, 2021 |
| HP            | 83E8                        | Desktop     | [dd469e94e9](https://linux-hardware.org/?probe=dd469e94e9) | Jul 05, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [5ba6ef3378](https://linux-hardware.org/?probe=5ba6ef3378) | Jul 05, 2021 |
| Dell          | 0TP406                      | Desktop     | [23a9dae189](https://linux-hardware.org/?probe=23a9dae189) | Jul 05, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [c9a7314217](https://linux-hardware.org/?probe=c9a7314217) | Jul 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [cf8e6fadef](https://linux-hardware.org/?probe=cf8e6fadef) | Jul 05, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [3803784209](https://linux-hardware.org/?probe=3803784209) | Jul 05, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [dfb6dc5f84](https://linux-hardware.org/?probe=dfb6dc5f84) | Jul 04, 2021 |
| PC Special... | N550RN                      | Notebook    | [dc21c20be8](https://linux-hardware.org/?probe=dc21c20be8) | Jul 04, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| MSI           | H310M PRO-D                 | Desktop     | [9e65e72132](https://linux-hardware.org/?probe=9e65e72132) | Jul 03, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b9f3018824](https://linux-hardware.org/?probe=b9f3018824) | Jul 03, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9282890b2e](https://linux-hardware.org/?probe=9282890b2e) | Jul 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Sony          | VGN-FZ11M                   | Notebook    | [24e370afbc](https://linux-hardware.org/?probe=24e370afbc) | Jul 02, 2021 |
| Sony          | VGN-FZ11M                   | Notebook    | [2654ceb68b](https://linux-hardware.org/?probe=2654ceb68b) | Jul 02, 2021 |
| MSI           | GE76 Raider 11UH            | Notebook    | [3f205f2881](https://linux-hardware.org/?probe=3f205f2881) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c198cbd693](https://linux-hardware.org/?probe=c198cbd693) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [ea85c0f143](https://linux-hardware.org/?probe=ea85c0f143) | Jul 02, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [36176e3082](https://linux-hardware.org/?probe=36176e3082) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [9acfe86828](https://linux-hardware.org/?probe=9acfe86828) | Jul 01, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [7dcd0d9b6f](https://linux-hardware.org/?probe=7dcd0d9b6f) | Jul 01, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [50ff643c64](https://linux-hardware.org/?probe=50ff643c64) | Jul 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0afed30de0](https://linux-hardware.org/?probe=0afed30de0) | Jul 01, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [c7b9018598](https://linux-hardware.org/?probe=c7b9018598) | Jul 01, 2021 |
| Dell          | Studio 1735                 | Notebook    | [2ed92032e0](https://linux-hardware.org/?probe=2ed92032e0) | Jul 01, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [d1ccd9254a](https://linux-hardware.org/?probe=d1ccd9254a) | Jul 01, 2021 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [44e9e4c71a](https://linux-hardware.org/?probe=44e9e4c71a) | Jul 01, 2021 |
| Dell          | 02P9X9 A03                  | Server      | [9dd822d511](https://linux-hardware.org/?probe=9dd822d511) | Jul 01, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [4da51dfa47](https://linux-hardware.org/?probe=4da51dfa47) | Jun 30, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [e214ce4b74](https://linux-hardware.org/?probe=e214ce4b74) | Jun 30, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [820725cbbd](https://linux-hardware.org/?probe=820725cbbd) | Jun 30, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [56d9443186](https://linux-hardware.org/?probe=56d9443186) | Jun 30, 2021 |
| ASUSTek       | 900HD                       | Notebook    | [7ac91a39d7](https://linux-hardware.org/?probe=7ac91a39d7) | Jun 30, 2021 |
| ASUSTek       | 900HD                       | Notebook    | [61e06e9ebd](https://linux-hardware.org/?probe=61e06e9ebd) | Jun 30, 2021 |
| Dell          | Latitude E6320              | Notebook    | [dd93a97faf](https://linux-hardware.org/?probe=dd93a97faf) | Jun 29, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [dcf91492a2](https://linux-hardware.org/?probe=dcf91492a2) | Jun 29, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [ee9a33e3d6](https://linux-hardware.org/?probe=ee9a33e3d6) | Jun 29, 2021 |
| Acer          | WMCP78M                     | Desktop     | [086bb70458](https://linux-hardware.org/?probe=086bb70458) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [81bbc7fe0f](https://linux-hardware.org/?probe=81bbc7fe0f) | Jun 29, 2021 |
| eMachines     | eME732                      | Notebook    | [1f334d1a64](https://linux-hardware.org/?probe=1f334d1a64) | Jun 29, 2021 |
| Dell          | G3 3579                     | Notebook    | [5c3d32395b](https://linux-hardware.org/?probe=5c3d32395b) | Jun 29, 2021 |
| Dell          | G3 3579                     | Notebook    | [5a87054082](https://linux-hardware.org/?probe=5a87054082) | Jun 29, 2021 |
| HP            | Stream Notebook PC 13       | Notebook    | [59f4d0c56b](https://linux-hardware.org/?probe=59f4d0c56b) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [c92e11a5de](https://linux-hardware.org/?probe=c92e11a5de) | Jun 29, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [2b17a2763c](https://linux-hardware.org/?probe=2b17a2763c) | Jun 28, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [a68897f1b5](https://linux-hardware.org/?probe=a68897f1b5) | Jun 28, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [aac1bf4737](https://linux-hardware.org/?probe=aac1bf4737) | Jun 28, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ceab39c39a](https://linux-hardware.org/?probe=ceab39c39a) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [29dedcc0c7](https://linux-hardware.org/?probe=29dedcc0c7) | Jun 28, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [61993f8c31](https://linux-hardware.org/?probe=61993f8c31) | Jun 28, 2021 |
| MSI           | B360-A PRO                  | Desktop     | [a623ec911c](https://linux-hardware.org/?probe=a623ec911c) | Jun 28, 2021 |
| Dixonsxp      | F71IX1                      | Notebook    | [104090904d](https://linux-hardware.org/?probe=104090904d) | Jun 28, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [498bab90e2](https://linux-hardware.org/?probe=498bab90e2) | Jun 28, 2021 |
| HP            | 339A                        | Desktop     | [f7045a85f1](https://linux-hardware.org/?probe=f7045a85f1) | Jun 27, 2021 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [8e0a4f8e98](https://linux-hardware.org/?probe=8e0a4f8e98) | Jun 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b0e2de6bbe](https://linux-hardware.org/?probe=b0e2de6bbe) | Jun 27, 2021 |
| HP            | 339A                        | Desktop     | [efc2a68df7](https://linux-hardware.org/?probe=efc2a68df7) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [15884a55b2](https://linux-hardware.org/?probe=15884a55b2) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [921fcdf0c3](https://linux-hardware.org/?probe=921fcdf0c3) | Jun 27, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [89753befcd](https://linux-hardware.org/?probe=89753befcd) | Jun 27, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [50c94838b6](https://linux-hardware.org/?probe=50c94838b6) | Jun 27, 2021 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [d48faf5072](https://linux-hardware.org/?probe=d48faf5072) | Jun 27, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5eefba228e](https://linux-hardware.org/?probe=5eefba228e) | Jun 27, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1f10b72f37](https://linux-hardware.org/?probe=1f10b72f37) | Jun 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [2279bef5dc](https://linux-hardware.org/?probe=2279bef5dc) | Jun 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [6bf8a2ed63](https://linux-hardware.org/?probe=6bf8a2ed63) | Jun 27, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8fae33ceb8](https://linux-hardware.org/?probe=8fae33ceb8) | Jun 26, 2021 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [61b50d18dd](https://linux-hardware.org/?probe=61b50d18dd) | Jun 26, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2a61b1829b](https://linux-hardware.org/?probe=2a61b1829b) | Jun 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [32ab76285a](https://linux-hardware.org/?probe=32ab76285a) | Jun 26, 2021 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [920b597b7a](https://linux-hardware.org/?probe=920b597b7a) | Jun 26, 2021 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [41fb54855c](https://linux-hardware.org/?probe=41fb54855c) | Jun 26, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [772a91651b](https://linux-hardware.org/?probe=772a91651b) | Jun 26, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [8bf331c7f3](https://linux-hardware.org/?probe=8bf331c7f3) | Jun 25, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [e5d0779ad2](https://linux-hardware.org/?probe=e5d0779ad2) | Jun 25, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [1f4ef21a29](https://linux-hardware.org/?probe=1f4ef21a29) | Jun 24, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [2b56e30c17](https://linux-hardware.org/?probe=2b56e30c17) | Jun 24, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3f4332e82f](https://linux-hardware.org/?probe=3f4332e82f) | Jun 24, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [1ef90ce444](https://linux-hardware.org/?probe=1ef90ce444) | Jun 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [e24031d13d](https://linux-hardware.org/?probe=e24031d13d) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [60e9dfbb43](https://linux-hardware.org/?probe=60e9dfbb43) | Jun 23, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [c640d90f90](https://linux-hardware.org/?probe=c640d90f90) | Jun 23, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0B    | Notebook    | [3e8ac913f5](https://linux-hardware.org/?probe=3e8ac913f5) | Jun 23, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [2f94e6e262](https://linux-hardware.org/?probe=2f94e6e262) | Jun 22, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d444752046](https://linux-hardware.org/?probe=d444752046) | Jun 22, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7c8ebe4ceb](https://linux-hardware.org/?probe=7c8ebe4ceb) | Jun 22, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [6e095bb160](https://linux-hardware.org/?probe=6e095bb160) | Jun 22, 2021 |
| Dell          | Latitude E7440              | Notebook    | [176b7cddb3](https://linux-hardware.org/?probe=176b7cddb3) | Jun 21, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [4ad401770e](https://linux-hardware.org/?probe=4ad401770e) | Jun 21, 2021 |
| Panasonic     | CF-30KAPAQ2B                | Notebook    | [2d99638aed](https://linux-hardware.org/?probe=2d99638aed) | Jun 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [14a96970a1](https://linux-hardware.org/?probe=14a96970a1) | Jun 21, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0a9814d6d9](https://linux-hardware.org/?probe=0a9814d6d9) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [d2519fe6fd](https://linux-hardware.org/?probe=d2519fe6fd) | Jun 21, 2021 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [235d2d6944](https://linux-hardware.org/?probe=235d2d6944) | Jun 21, 2021 |
| MSI           | 2AE0                        | Desktop     | [305442818d](https://linux-hardware.org/?probe=305442818d) | Jun 21, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [3e013acd03](https://linux-hardware.org/?probe=3e013acd03) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [49c2e3aee9](https://linux-hardware.org/?probe=49c2e3aee9) | Jun 21, 2021 |
| Dell          | Latitude E6400              | Notebook    | [341a89c91d](https://linux-hardware.org/?probe=341a89c91d) | Jun 20, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [8af31493ae](https://linux-hardware.org/?probe=8af31493ae) | Jun 20, 2021 |
| Dell          | Latitude E6400              | Notebook    | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [5cdcacb2f2](https://linux-hardware.org/?probe=5cdcacb2f2) | Jun 20, 2021 |
| ASUSTek       | A88XM-E                     | Desktop     | [f9c27b350f](https://linux-hardware.org/?probe=f9c27b350f) | Jun 20, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [bfac6e1e60](https://linux-hardware.org/?probe=bfac6e1e60) | Jun 20, 2021 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [094124cf96](https://linux-hardware.org/?probe=094124cf96) | Jun 19, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [5240b82490](https://linux-hardware.org/?probe=5240b82490) | Jun 19, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [069ad44fca](https://linux-hardware.org/?probe=069ad44fca) | Jun 19, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed52fe230a](https://linux-hardware.org/?probe=ed52fe230a) | Jun 19, 2021 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1154063733](https://linux-hardware.org/?probe=1154063733) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31c18be478](https://linux-hardware.org/?probe=31c18be478) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3dca88b4e4](https://linux-hardware.org/?probe=3dca88b4e4) | Jun 19, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [a30b82c873](https://linux-hardware.org/?probe=a30b82c873) | Jun 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d41809b4c9](https://linux-hardware.org/?probe=d41809b4c9) | Jun 19, 2021 |
| ECS           | H61H2-TI                    | All in one  | [f8a9a819f3](https://linux-hardware.org/?probe=f8a9a819f3) | Jun 18, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [162addf6e2](https://linux-hardware.org/?probe=162addf6e2) | Jun 18, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| HP            | 81C5 MVB                    | Desktop     | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| Dell          | Latitude E5510              | Notebook    | [e163ed19d5](https://linux-hardware.org/?probe=e163ed19d5) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | Notebook    | [22aabc71ef](https://linux-hardware.org/?probe=22aabc71ef) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | Notebook    | [99a0a332ec](https://linux-hardware.org/?probe=99a0a332ec) | Jun 17, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | Desktop     | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a5b1129bb5](https://linux-hardware.org/?probe=a5b1129bb5) | Jun 16, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [490fa8038c](https://linux-hardware.org/?probe=490fa8038c) | Jun 16, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [c4bb68787a](https://linux-hardware.org/?probe=c4bb68787a) | Jun 16, 2021 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [8a95d8badc](https://linux-hardware.org/?probe=8a95d8badc) | Jun 16, 2021 |
| Dell          | Latitude E6400              | Notebook    | [9f99c4d6e5](https://linux-hardware.org/?probe=9f99c4d6e5) | Jun 16, 2021 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [370f7f875d](https://linux-hardware.org/?probe=370f7f875d) | Jun 15, 2021 |
| Sony          | VGN-FW21L                   | Notebook    | [fe6647a4b1](https://linux-hardware.org/?probe=fe6647a4b1) | Jun 15, 2021 |
| Acer          | AOD257                      | Notebook    | [50b9a36d40](https://linux-hardware.org/?probe=50b9a36d40) | Jun 15, 2021 |
| Lenovo        | ThinkPad T420 4236RQ5       | Notebook    | [45dcaa268c](https://linux-hardware.org/?probe=45dcaa268c) | Jun 15, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [df12800afd](https://linux-hardware.org/?probe=df12800afd) | Jun 15, 2021 |
| Lenovo        | ThinkPad T420 4236RQ5       | Notebook    | [3dd4e39c6a](https://linux-hardware.org/?probe=3dd4e39c6a) | Jun 15, 2021 |
| Dell          | 0VD98F A04                  | Desktop     | [cb13b27ef2](https://linux-hardware.org/?probe=cb13b27ef2) | Jun 15, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [cc36c68569](https://linux-hardware.org/?probe=cc36c68569) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [a6cf581d50](https://linux-hardware.org/?probe=a6cf581d50) | Jun 14, 2021 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [8a654550e9](https://linux-hardware.org/?probe=8a654550e9) | Jun 14, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1b0ac499c3](https://linux-hardware.org/?probe=1b0ac499c3) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [48c28ecda7](https://linux-hardware.org/?probe=48c28ecda7) | Jun 14, 2021 |
| Lenovo        | ThinkPad E590 20NB0029UK    | Notebook    | [073912d946](https://linux-hardware.org/?probe=073912d946) | Jun 14, 2021 |
| Toshiba       | Satellite C55D-A-15H        | Notebook    | [95d4db4781](https://linux-hardware.org/?probe=95d4db4781) | Jun 14, 2021 |
| Lenovo        | ThinkPad P1 20MD0002UK      | Notebook    | [76bb868606](https://linux-hardware.org/?probe=76bb868606) | Jun 14, 2021 |
| Dell          | Latitude 3470               | Notebook    | [fc5081466f](https://linux-hardware.org/?probe=fc5081466f) | Jun 14, 2021 |
| Sony          | SVF1521A7EB                 | Notebook    | [0b7fc5715a](https://linux-hardware.org/?probe=0b7fc5715a) | Jun 13, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [f684e4786d](https://linux-hardware.org/?probe=f684e4786d) | Jun 13, 2021 |
| Dell          | Studio 1735                 | Notebook    | [6cd1b25005](https://linux-hardware.org/?probe=6cd1b25005) | Jun 13, 2021 |
| HP            | 3396                        | Desktop     | [79224b0b14](https://linux-hardware.org/?probe=79224b0b14) | Jun 13, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [4d915ac887](https://linux-hardware.org/?probe=4d915ac887) | Jun 13, 2021 |
| HP            | 3396                        | Desktop     | [be21a901a7](https://linux-hardware.org/?probe=be21a901a7) | Jun 13, 2021 |
| HP            | ENVY Notebook               | Notebook    | [a69f50c924](https://linux-hardware.org/?probe=a69f50c924) | Jun 13, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [5b1b3e5eb5](https://linux-hardware.org/?probe=5b1b3e5eb5) | Jun 12, 2021 |
| Dell          | 0WG864                      | Desktop     | [f87d1e613e](https://linux-hardware.org/?probe=f87d1e613e) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [98f14d9b09](https://linux-hardware.org/?probe=98f14d9b09) | Jun 11, 2021 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [32e7e7d668](https://linux-hardware.org/?probe=32e7e7d668) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [d188ddaff3](https://linux-hardware.org/?probe=d188ddaff3) | Jun 11, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [698a5ea843](https://linux-hardware.org/?probe=698a5ea843) | Jun 11, 2021 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [740e65713f](https://linux-hardware.org/?probe=740e65713f) | Jun 11, 2021 |
| Dell          | Latitude 3470               | Notebook    | [030ebe1467](https://linux-hardware.org/?probe=030ebe1467) | Jun 11, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [46d639e847](https://linux-hardware.org/?probe=46d639e847) | Jun 10, 2021 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [4bbf266b53](https://linux-hardware.org/?probe=4bbf266b53) | Jun 10, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ae5cc4dd77](https://linux-hardware.org/?probe=ae5cc4dd77) | Jun 10, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fa7bfd58f6](https://linux-hardware.org/?probe=fa7bfd58f6) | Jun 10, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [d84f718db5](https://linux-hardware.org/?probe=d84f718db5) | Jun 10, 2021 |
| Dell          | G5 5505                     | Notebook    | [4a64eaeed5](https://linux-hardware.org/?probe=4a64eaeed5) | Jun 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [1f8af79fb0](https://linux-hardware.org/?probe=1f8af79fb0) | Jun 09, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [e9ff1ba01f](https://linux-hardware.org/?probe=e9ff1ba01f) | Jun 09, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [7607b3bb86](https://linux-hardware.org/?probe=7607b3bb86) | Jun 09, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [28fb1b0135](https://linux-hardware.org/?probe=28fb1b0135) | Jun 08, 2021 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1dfe7bd3cb](https://linux-hardware.org/?probe=1dfe7bd3cb) | Jun 08, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [68132917e8](https://linux-hardware.org/?probe=68132917e8) | Jun 08, 2021 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [f5ca08156d](https://linux-hardware.org/?probe=f5ca08156d) | Jun 08, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4ad89178cc](https://linux-hardware.org/?probe=4ad89178cc) | Jun 08, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [ed9feab726](https://linux-hardware.org/?probe=ed9feab726) | Jun 07, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [172643ea98](https://linux-hardware.org/?probe=172643ea98) | Jun 07, 2021 |
| Fujitsu Si... | D1567 S26361-D1567          | Desktop     | [b26937abc3](https://linux-hardware.org/?probe=b26937abc3) | Jun 07, 2021 |
| Fujitsu Si... | D1567 S26361-D1567          | Desktop     | [ebb04fb6c9](https://linux-hardware.org/?probe=ebb04fb6c9) | Jun 07, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [60b4c707ad](https://linux-hardware.org/?probe=60b4c707ad) | Jun 07, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [f0bd1ecbba](https://linux-hardware.org/?probe=f0bd1ecbba) | Jun 07, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [18df123a3f](https://linux-hardware.org/?probe=18df123a3f) | Jun 07, 2021 |
| HP            | G62                         | Notebook    | [f779c341e4](https://linux-hardware.org/?probe=f779c341e4) | Jun 07, 2021 |
| Medion        | WIM2200                     | Notebook    | [85a41a6749](https://linux-hardware.org/?probe=85a41a6749) | Jun 07, 2021 |
| HP            | Compaq 6910p                | Notebook    | [dcf8ea2636](https://linux-hardware.org/?probe=dcf8ea2636) | Jun 07, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [c007f9db78](https://linux-hardware.org/?probe=c007f9db78) | Jun 06, 2021 |
| Jumper        | Ezbook X3                   | Notebook    | [156e7d1f45](https://linux-hardware.org/?probe=156e7d1f45) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [64d9cfa382](https://linux-hardware.org/?probe=64d9cfa382) | Jun 06, 2021 |
| Samsung       | 900X3G                      | Notebook    | [2ce9dac4c3](https://linux-hardware.org/?probe=2ce9dac4c3) | Jun 06, 2021 |
| Samsung       | 900X3G                      | Notebook    | [1f7e3d2301](https://linux-hardware.org/?probe=1f7e3d2301) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [b3d1e1b346](https://linux-hardware.org/?probe=b3d1e1b346) | Jun 06, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [803800a2ea](https://linux-hardware.org/?probe=803800a2ea) | Jun 06, 2021 |
| HP            | 870C                        | Desktop     | [2161a2184f](https://linux-hardware.org/?probe=2161a2184f) | Jun 06, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [7daa23eeed](https://linux-hardware.org/?probe=7daa23eeed) | Jun 06, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [aa7c5caf25](https://linux-hardware.org/?probe=aa7c5caf25) | Jun 06, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [48258c4c38](https://linux-hardware.org/?probe=48258c4c38) | Jun 06, 2021 |
| Samsung       | Q330                        | Notebook    | [4bdfd22fe6](https://linux-hardware.org/?probe=4bdfd22fe6) | Jun 05, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [6bd42268f6](https://linux-hardware.org/?probe=6bd42268f6) | Jun 05, 2021 |
| Dell          | 0WG864                      | Desktop     | [d72c25e601](https://linux-hardware.org/?probe=d72c25e601) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [53f89be1b8](https://linux-hardware.org/?probe=53f89be1b8) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [f9626d011c](https://linux-hardware.org/?probe=f9626d011c) | Jun 05, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8ca2af34b9](https://linux-hardware.org/?probe=8ca2af34b9) | Jun 05, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [eb4f7a5cf5](https://linux-hardware.org/?probe=eb4f7a5cf5) | Jun 05, 2021 |
| Acer          | Aspire 5742Z                | Notebook    | [89ae1206bb](https://linux-hardware.org/?probe=89ae1206bb) | Jun 05, 2021 |
| Medion        | WIM2200                     | Notebook    | [e2492d5642](https://linux-hardware.org/?probe=e2492d5642) | Jun 05, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [6bb04a23b1](https://linux-hardware.org/?probe=6bb04a23b1) | Jun 05, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [99bc345630](https://linux-hardware.org/?probe=99bc345630) | Jun 05, 2021 |
| MSI           | A78M-E35                    | Desktop     | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | Desktop     | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| Dell          | Latitude E6510              | Notebook    | [7f86c73ee7](https://linux-hardware.org/?probe=7f86c73ee7) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [659589f1a8](https://linux-hardware.org/?probe=659589f1a8) | Jun 04, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [53428cc56a](https://linux-hardware.org/?probe=53428cc56a) | Jun 04, 2021 |
| Motion Com... | C5te                        | Notebook    | [9eb48c4b07](https://linux-hardware.org/?probe=9eb48c4b07) | Jun 04, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [cf9db1ce7a](https://linux-hardware.org/?probe=cf9db1ce7a) | Jun 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWA0850... | Notebook    | [8390e1030c](https://linux-hardware.org/?probe=8390e1030c) | Jun 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [385c30d3a6](https://linux-hardware.org/?probe=385c30d3a6) | Jun 04, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c3e1c7c5ba](https://linux-hardware.org/?probe=c3e1c7c5ba) | Jun 03, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [746f47e17c](https://linux-hardware.org/?probe=746f47e17c) | Jun 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [7a364bc855](https://linux-hardware.org/?probe=7a364bc855) | Jun 03, 2021 |
| ECS           | H61H2-TI                    | All in one  | [35b729e93d](https://linux-hardware.org/?probe=35b729e93d) | Jun 03, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [56dc35f6b4](https://linux-hardware.org/?probe=56dc35f6b4) | Jun 03, 2021 |
| Toshiba       | Satellite C850-1KN          | Notebook    | [021f126726](https://linux-hardware.org/?probe=021f126726) | Jun 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [add42dfbf9](https://linux-hardware.org/?probe=add42dfbf9) | Jun 03, 2021 |
| Foxconn       | A76ML-K 30                  | Desktop     | [5981198dbd](https://linux-hardware.org/?probe=5981198dbd) | Jun 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [66dc392cc0](https://linux-hardware.org/?probe=66dc392cc0) | Jun 02, 2021 |
| Dell          | Studio 1735                 | Notebook    | [b0485d3960](https://linux-hardware.org/?probe=b0485d3960) | Jun 02, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [568847c7b0](https://linux-hardware.org/?probe=568847c7b0) | Jun 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1087      | 18.72%  |
| Ubuntu 18.04                 | 589       | 10.14%  |
| OpenMandriva 4.2             | 128       | 2.2%    |
| Linux Mint 20.2              | 110       | 1.89%   |
| Linux Mint 19.3              | 110       | 1.89%   |
| Pop!_OS 20.04                | 107       | 1.84%   |
| KDE neon 20.04               | 106       | 1.83%   |
| Ubuntu 19.04                 | 105       | 1.81%   |
| Zorin 16                     | 104       | 1.79%   |
| Ubuntu 20.10                 | 100       | 1.72%   |
| Pop!_OS 21.04                | 100       | 1.72%   |
| Ubuntu 21.10                 | 93        | 1.6%    |
| Debian 11                    | 93        | 1.6%    |
| Ubuntu 19.10                 | 91        | 1.57%   |
| Zorin 15                     | 88        | 1.52%   |
| Arch                         | 86        | 1.48%   |
| Pop!_OS 20.10                | 85        | 1.46%   |
| Manjaro                      | 84        | 1.45%   |
| Arch Rolling                 | 84        | 1.45%   |
| Linux Mint 20.1              | 82        | 1.41%   |
| Linux Mint 20.3              | 81        | 1.4%    |
| Ubuntu 21.04                 | 80        | 1.38%   |
| ArcoLinux Rolling            | 73        | 1.26%   |
| Xubuntu 20.04                | 70        | 1.21%   |
| Ubuntu 22.04                 | 70        | 1.21%   |
| OpenMandriva 4.3             | 68        | 1.17%   |
| Linux Mint 20                | 64        | 1.1%    |
| Fedora 34                    | 59        | 1.02%   |
| Ubuntu 18.10                 | 56        | 0.96%   |
| Pop!_OS 21.10                | 56        | 0.96%   |
| Kubuntu 20.04                | 55        | 0.95%   |
| Fedora 35                    | 55        | 0.95%   |
| Fedora 33                    | 48        | 0.83%   |
| Fedora 31                    | 48        | 0.83%   |
| Ubuntu 16.04                 | 46        | 0.79%   |
| Debian 10                    | 46        | 0.79%   |
| Fedora 32                    | 43        | 0.74%   |
| BlackPanther 18.1            | 39        | 0.67%   |
| Xubuntu 18.04                | 33        | 0.57%   |
| Linux Mint 19.1              | 33        | 0.57%   |
| Ubuntu MATE 20.04            | 32        | 0.55%   |
| ROSA R10                     | 32        | 0.55%   |
| Gentoo 2.7                   | 30        | 0.52%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.48%   |
| Fedora 36                    | 27        | 0.47%   |
| Endless 3.7.8                | 23        | 0.4%    |
| Linux Mint 19.2              | 22        | 0.38%   |
| Debian Testing               | 22        | 0.38%   |
| Gentoo 2.6                   | 21        | 0.36%   |
| Pop!_OS 22.04                | 20        | 0.34%   |
| Elementary 6.1               | 18        | 0.31%   |
| Fedora 30                    | 17        | 0.29%   |
| OpenMandriva 4.50            | 16        | 0.28%   |
| Garuda Linux Soaring         | 15        | 0.26%   |
| Elementary 5.1.7             | 15        | 0.26%   |
| ROSA R9                      | 14        | 0.24%   |
| LMDE 4                       | 14        | 0.24%   |
| CentOS 8                     | 14        | 0.24%   |
| Peppermint 10                | 13        | 0.22%   |
| Manjaro 20.2.1               | 13        | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2235      | 40.29%  |
| Linux Mint    | 488       | 8.8%    |
| Pop!_OS       | 349       | 6.29%   |
| Fedora        | 286       | 5.16%   |
| OpenMandriva  | 213       | 3.84%   |
| Zorin         | 202       | 3.64%   |
| Manjaro       | 184       | 3.32%   |
| Debian        | 179       | 3.23%   |
| Arch          | 168       | 3.03%   |
| Xubuntu       | 123       | 2.22%   |
| KDE neon      | 118       | 2.13%   |
| Kubuntu       | 116       | 2.09%   |
| ArcoLinux     | 77        | 1.39%   |
| ROSA          | 72        | 1.3%    |
| Ubuntu MATE   | 57        | 1.03%   |
| Gentoo        | 54        | 0.97%   |
| Elementary    | 53        | 0.96%   |
| Endless       | 50        | 0.9%    |
| openSUSE      | 46        | 0.83%   |
| Clear Linux   | 42        | 0.76%   |
| BlackPanther  | 40        | 0.72%   |
| Lubuntu       | 38        | 0.69%   |
| Kali          | 31        | 0.56%   |
| LMDE          | 24        | 0.43%   |
| CentOS        | 24        | 0.43%   |
| MX            | 18        | 0.32%   |
| Garuda Linux  | 18        | 0.32%   |
| Ubuntu Budgie | 17        | 0.31%   |
| EndeavourOS   | 17        | 0.31%   |
| Raspbian      | 14        | 0.25%   |
| Peppermint    | 14        | 0.25%   |
| RHEL          | 13        | 0.23%   |
| Parrot        | 11        | 0.2%    |
| Slackware     | 10        | 0.18%   |
| SteamOS       | 9         | 0.16%   |
| NixOS         | 8         | 0.14%   |
| Mageia        | 7         | 0.13%   |
| Alpine        | 7         | 0.13%   |
| Reborn OS     | 6         | 0.11%   |
| PureOS        | 5         | 0.09%   |
| Manjaro-ARM   | 5         | 0.09%   |
| Makulu        | 5         | 0.09%   |
| LinuxFX       | 5         | 0.09%   |
| Linux Lite    | 5         | 0.09%   |
| Chrome OS     | 5         | 0.09%   |
| Artix         | 5         | 0.09%   |
| Void Linux    | 4         | 0.07%   |
| Sparky        | 4         | 0.07%   |
| Oracle Linux  | 4         | 0.07%   |
| Hash Linux    | 4         | 0.07%   |
| Feren OS      | 4         | 0.07%   |
| UbuntuDDE     | 3         | 0.05%   |
| Ubuntu Studio | 3         | 0.05%   |
| Solus         | 3         | 0.05%   |
| Siduction     | 3         | 0.05%   |
| Q4OS          | 3         | 0.05%   |
| Nitrux        | 3         | 0.05%   |
| Devuan        | 3         | 0.05%   |
| antergos      | 3         | 0.05%   |
| Xero          | 2         | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 151       | 2.32%   |
| 5.10.14-desktop-1omv4002        | 125       | 1.92%   |
| 5.4.0-48-generic                | 81        | 1.25%   |
| 5.4.0-52-generic                | 76        | 1.17%   |
| 5.4.0-29-generic                | 73        | 1.12%   |
| 5.4.0-26-generic                | 69        | 1.06%   |
| 5.3.0-28-generic                | 65        | 1%      |
| 5.16.7-desktop-1omv4003         | 65        | 1%      |
| 5.3.0-40-generic                | 60        | 0.92%   |
| 5.4.0-40-generic                | 53        | 0.82%   |
| 5.4.0-37-generic                | 51        | 0.79%   |
| 5.4.0-58-generic                | 50        | 0.77%   |
| 5.11.0-27-generic               | 50        | 0.77%   |
| 5.4.0-65-generic                | 45        | 0.69%   |
| 5.4.0-33-generic                | 45        | 0.69%   |
| 5.11.0-38-generic               | 45        | 0.69%   |
| 5.0.0-32-generic                | 45        | 0.69%   |
| 5.13.0-7614-generic             | 43        | 0.66%   |
| 5.11.0-25-generic               | 43        | 0.66%   |
| 5.4.0-91-generic                | 41        | 0.63%   |
| 5.4.0-7634-generic              | 41        | 0.63%   |
| 5.4.0-54-generic                | 41        | 0.63%   |
| 5.3.0-46-generic                | 41        | 0.63%   |
| 5.4.0-74-generic                | 40        | 0.62%   |
| 5.4.0-66-generic                | 40        | 0.62%   |
| 5.8.0-7630-generic              | 39        | 0.6%    |
| 5.8.0-43-generic                | 39        | 0.6%    |
| 5.11.0-7620-generic             | 39        | 0.6%    |
| 5.0.0-37-generic                | 39        | 0.6%    |
| 5.11.0-40-generic               | 38        | 0.58%   |
| 5.11.0-37-generic               | 38        | 0.58%   |
| 5.3.0-42-generic                | 37        | 0.57%   |
| 5.13.0-28-generic               | 37        | 0.57%   |
| 5.8.0-44-generic                | 36        | 0.55%   |
| 5.4.0-56-generic                | 36        | 0.55%   |
| 5.8.0-50-generic                | 35        | 0.54%   |
| 5.4.0-47-generic                | 35        | 0.54%   |
| 5.13.0-39-generic               | 35        | 0.54%   |
| 5.11.0-43-generic               | 35        | 0.54%   |
| 5.4.0-31-generic                | 34        | 0.52%   |
| 5.4.0-73-generic                | 33        | 0.51%   |
| 5.11.0-41-generic               | 31        | 0.48%   |
| 5.11.0-34-generic               | 30        | 0.46%   |
| 5.10.0-8-amd64                  | 30        | 0.46%   |
| 4.18.0-15-generic               | 30        | 0.46%   |
| 4.18.16-desktop-1bP             | 29        | 0.45%   |
| 5.4.0-77-generic                | 27        | 0.42%   |
| 5.4.0-7642-generic              | 27        | 0.42%   |
| 5.13.0-30-generic               | 27        | 0.42%   |
| 5.8.0-53-generic                | 26        | 0.4%    |
| 5.8.0-48-generic                | 26        | 0.4%    |
| 5.4.0-72-generic                | 25        | 0.38%   |
| 5.15.0-27-generic               | 25        | 0.38%   |
| 5.13.0-27-generic               | 25        | 0.38%   |
| 5.0.0-23-generic                | 25        | 0.38%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 25        | 0.38%   |
| 5.8.0-55-generic                | 24        | 0.37%   |
| 5.4.0-81-generic                | 24        | 0.37%   |
| 5.4.0-80-generic                | 24        | 0.37%   |
| 5.4.0-70-generic                | 24        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1427      | 23.78%  |
| 5.11.0  | 448       | 7.47%   |
| 5.8.0   | 446       | 7.43%   |
| 4.15.0  | 410       | 6.83%   |
| 5.3.0   | 374       | 6.23%   |
| 5.13.0  | 347       | 5.78%   |
| 5.0.0   | 244       | 4.07%   |
| 4.18.0  | 178       | 2.97%   |
| 5.10.0  | 126       | 2.1%    |
| 5.10.14 | 125       | 2.08%   |
| 5.15.0  | 103       | 1.72%   |
| 5.16.7  | 66        | 1.1%    |
| 4.19.0  | 55        | 0.92%   |
| 4.18.16 | 32        | 0.53%   |
| 5.17.5  | 27        | 0.45%   |
| 4.9.60  | 26        | 0.43%   |
| 5.9.16  | 25        | 0.42%   |
| 5.14.0  | 25        | 0.42%   |
| 4.4.0   | 20        | 0.33%   |
| 5.16.11 | 18        | 0.3%    |
| 5.17.1  | 17        | 0.28%   |
| 5.15.12 | 17        | 0.28%   |
| 5.13.12 | 17        | 0.28%   |
| 4.9.20  | 16        | 0.27%   |
| 5.7.0   | 15        | 0.25%   |
| 5.15.15 | 15        | 0.25%   |
| 5.12.4  | 15        | 0.25%   |
| 5.12.13 | 15        | 0.25%   |
| 5.6.14  | 14        | 0.23%   |
| 5.6.0   | 14        | 0.23%   |
| 5.3.18  | 14        | 0.23%   |
| 5.16.0  | 14        | 0.23%   |
| 5.8.6   | 13        | 0.22%   |
| 5.17.0  | 13        | 0.22%   |
| 5.9.11  | 12        | 0.2%    |
| 5.9.1   | 12        | 0.2%    |
| 5.16.15 | 12        | 0.2%    |
| 5.15.5  | 12        | 0.2%    |
| 5.13.13 | 12        | 0.2%    |
| 4.9.0   | 12        | 0.2%    |
| 5.9.0   | 11        | 0.18%   |
| 5.8.11  | 11        | 0.18%   |
| 5.13.8  | 11        | 0.18%   |
| 5.13.19 | 11        | 0.18%   |
| 5.16.13 | 10        | 0.17%   |
| 5.15.6  | 10        | 0.17%   |
| 5.14.14 | 10        | 0.17%   |
| 5.14.10 | 10        | 0.17%   |
| 5.12.9  | 10        | 0.17%   |
| 5.6.15  | 9         | 0.15%   |
| 5.3.7   | 9         | 0.15%   |
| 5.16.18 | 9         | 0.15%   |
| 5.15.8  | 9         | 0.15%   |
| 5.15.32 | 9         | 0.15%   |
| 5.12.7  | 9         | 0.15%   |
| 5.9.14  | 8         | 0.13%   |
| 5.8.16  | 8         | 0.13%   |
| 5.4.13  | 8         | 0.13%   |
| 5.18.0  | 8         | 0.13%   |
| 5.16.2  | 8         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1516      | 25.61%  |
| 5.8     | 534       | 9.02%   |
| 5.11    | 506       | 8.55%   |
| 5.13    | 432       | 7.3%    |
| 5.3     | 424       | 7.16%   |
| 4.15    | 412       | 6.96%   |
| 5.10    | 381       | 6.44%   |
| 5.0     | 254       | 4.29%   |
| 5.15    | 240       | 4.05%   |
| 4.18    | 213       | 3.6%    |
| 5.16    | 168       | 2.84%   |
| 5.9     | 95        | 1.61%   |
| 5.14    | 91        | 1.54%   |
| 5.12    | 88        | 1.49%   |
| 5.17    | 86        | 1.45%   |
| 4.19    | 86        | 1.45%   |
| 5.6     | 75        | 1.27%   |
| 4.9     | 71        | 1.2%    |
| 5.7     | 67        | 1.13%   |
| 5.5     | 42        | 0.71%   |
| 4.4     | 24        | 0.41%   |
| 5.2     | 23        | 0.39%   |
| 5.18    | 21        | 0.35%   |
| 5.1     | 16        | 0.27%   |
| 4.14    | 10        | 0.17%   |
| 4.1     | 9         | 0.15%   |
| 3.10    | 7         | 0.12%   |
| 4.20    | 5         | 0.08%   |
| 4.13    | 5         | 0.08%   |
| 3.13    | 4         | 0.07%   |
| 4.16    | 3         | 0.05%   |
| 4.12    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 5.19    | 1         | 0.02%   |
| 5       | 1         | 0.02%   |
| 4.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.19    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5102      | 95.47%  |
| i686    | 165       | 3.09%   |
| aarch64 | 58        | 1.09%   |
| armv7l  | 19        | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2575      | 45.87%  |
| Unknown          | 868       | 15.46%  |
| KDE5             | 681       | 12.13%  |
| X-Cinnamon       | 386       | 6.88%   |
| XFCE             | 359       | 6.39%   |
| KDE              | 173       | 3.08%   |
| MATE             | 149       | 2.65%   |
| Cinnamon         | 77        | 1.37%   |
| Unity            | 49        | 0.87%   |
| Pantheon         | 49        | 0.87%   |
| LXQt             | 36        | 0.64%   |
| LXDE             | 36        | 0.64%   |
| KDE4             | 35        | 0.62%   |
| i3               | 25        | 0.45%   |
| Budgie           | 25        | 0.45%   |
| GNOME Flashback  | 23        | 0.41%   |
| Deepin           | 12        | 0.21%   |
| Openbox          | 8         | 0.14%   |
| sway             | 7         | 0.12%   |
| qtile            | 6         | 0.11%   |
| GNOME Classic    | 6         | 0.11%   |
| awesome          | 5         | 0.09%   |
| xmonad           | 4         | 0.07%   |
| DWM              | 3         | 0.05%   |
| bspwm            | 3         | 0.05%   |
| trinity          | 2         | 0.04%   |
| lightdm-xsession | 2         | 0.04%   |
| i3-with-shmlog   | 2         | 0.04%   |
| Cutefish         | 2         | 0.04%   |
| xubuntu          | 1         | 0.02%   |
| WindowMaker      | 1         | 0.02%   |
| Phosh:GNOME      | 1         | 0.02%   |
| LeftWM           | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |
| enlightenment    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4425      | 80.73%  |
| Wayland | 505       | 9.21%   |
| Unknown | 437       | 7.97%   |
| Tty     | 114       | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3468      | 62.44%  |
| SDDM    | 612       | 11.02%  |
| GDM     | 582       | 10.48%  |
| LightDM | 339       | 6.1%    |
| GDM3    | 292       | 5.26%   |
| TDM     | 200       | 3.6%    |
| KDM     | 34        | 0.61%   |
| XDM     | 13        | 0.23%   |
| LXDM    | 5         | 0.09%   |
| Ly      | 4         | 0.07%   |
| SLiM    | 3         | 0.05%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 3901      | 71.2%   |
| Unknown        | 799       | 14.58%  |
| en_US          | 534       | 9.75%   |
| C              | 81        | 1.48%   |
| pl_PL          | 47        | 0.86%   |
| ru_RU          | 10        | 0.18%   |
| en_CA          | 10        | 0.18%   |
| POSIX          | 9         | 0.16%   |
| de_DE          | 9         | 0.16%   |
| it_IT          | 8         | 0.15%   |
| en_IE          | 8         | 0.15%   |
| cs_CZ          | 6         | 0.11%   |
| en_IN          | 5         | 0.09%   |
| ro_RO          | 4         | 0.07%   |
| pt_PT          | 4         | 0.07%   |
| hu_HU          | 4         | 0.07%   |
| fr_FR          | 4         | 0.07%   |
| en_AU          | 4         | 0.07%   |
| zh_CN          | 3         | 0.05%   |
| sk_SK          | 3         | 0.05%   |
| pt_BR          | 3         | 0.05%   |
| C.UTF8         | 3         | 0.05%   |
| uk_UA          | 2         | 0.04%   |
| nl_NL          | 2         | 0.04%   |
| es_ES          | 2         | 0.04%   |
| da_DK          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| wbp_AU         | 1         | 0.02%   |
| tr_TR          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| fi_FI          | 1         | 0.02%   |
| en_ZA          | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |
| en_GB.iso88591 | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2928      | 53.65%  |
| EFI  | 2530      | 46.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4424      | 80.83%  |
| Btrfs    | 332       | 6.07%   |
| Overlay  | 316       | 5.77%   |
| Unknown  | 232       | 4.24%   |
| Xfs      | 76        | 1.39%   |
| Zfs      | 43        | 0.79%   |
| Ext2     | 18        | 0.33%   |
| Tmpfs    | 11        | 0.2%    |
| Ext3     | 10        | 0.18%   |
| F2fs     | 7         | 0.13%   |
| Reiserfs | 1         | 0.02%   |
| Lvm      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3605      | 66.24%  |
| GPT     | 1383      | 25.41%  |
| MBR     | 454       | 8.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4634      | 85.07%  |
| Yes       | 813       | 14.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3927      | 72.29%  |
| Yes       | 1505      | 27.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 856       | 16.03%  |
| ASUSTek Computer        | 783       | 14.66%  |
| Hewlett-Packard         | 686       | 12.85%  |
| Lenovo                  | 645       | 12.08%  |
| Gigabyte Technology     | 400       | 7.49%   |
| MSI                     | 285       | 5.34%   |
| Acer                    | 260       | 4.87%   |
| ASRock                  | 172       | 3.22%   |
| Apple                   | 154       | 2.88%   |
| Toshiba                 | 131       | 2.45%   |
| Intel                   | 102       | 1.91%   |
| Samsung Electronics     | 68        | 1.27%   |
| Raspberry Pi Foundation | 59        | 1.1%    |
| Sony                    | 52        | 0.97%   |
| Fujitsu                 | 38        | 0.71%   |
| PC Specialist           | 36        | 0.67%   |
| Unknown                 | 35        | 0.66%   |
| HUAWEI                  | 31        | 0.58%   |
| Packard Bell            | 29        | 0.54%   |
| Foxconn                 | 28        | 0.52%   |
| Notebook                | 25        | 0.47%   |
| Microsoft               | 25        | 0.47%   |
| Google                  | 24        | 0.45%   |
| Pegatron                | 20        | 0.37%   |
| Fujitsu Siemens         | 18        | 0.34%   |
| Alienware               | 18        | 0.34%   |
| Biostar                 | 15        | 0.28%   |
| Razer                   | 14        | 0.26%   |
| Medion                  | 14        | 0.26%   |
| Star Labs               | 13        | 0.24%   |
| Dixonsxp                | 13        | 0.24%   |
| Linx                    | 11        | 0.21%   |
| Entroware               | 11        | 0.21%   |
| AMI                     | 11        | 0.21%   |
| Chuwi                   | 10        | 0.19%   |
| Advent                  | 10        | 0.19%   |
| Clevo                   | 9         | 0.17%   |
| Jumper                  | 8         | 0.15%   |
| Valve                   | 7         | 0.13%   |
| Supermicro              | 7         | 0.13%   |
| Shuttle                 | 7         | 0.13%   |
| Panasonic               | 7         | 0.13%   |
| GEO                     | 7         | 0.13%   |
| ECS                     | 7         | 0.13%   |
| AZW                     | 7         | 0.13%   |
| TUXEDO                  | 5         | 0.09%   |
| Teclast                 | 5         | 0.09%   |
| Nvidia                  | 5         | 0.09%   |
| eMachines               | 5         | 0.09%   |
| ZOTAC                   | 4         | 0.07%   |
| TYAN Computer           | 4         | 0.07%   |
| LG Electronics          | 4         | 0.07%   |
| IP3 Tech                | 4         | 0.07%   |
| IBM                     | 4         | 0.07%   |
| Fusion5                 | 4         | 0.07%   |
| Timi                    | 3         | 0.06%   |
| Purism                  | 3         | 0.06%   |
| Pine Microsystems       | 3         | 0.06%   |
| OEGStone                | 3         | 0.06%   |
| Novatech                | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 59        | 1.1%    |
| Unknown                            | 56        | 1.05%   |
| Dell OptiPlex 7010                 | 25        | 0.47%   |
| RPi Raspberry Pi                   | 21        | 0.39%   |
| MSI MS-7C02                        | 20        | 0.37%   |
| HP Pavilion g6                     | 19        | 0.36%   |
| Dell OptiPlex 755                  | 17        | 0.32%   |
| HP Pavilion 15                     | 16        | 0.3%    |
| ASUS ROG STRIX B450-F GAMING       | 16        | 0.3%    |
| ASUS M5A78L-M/USB3                 | 16        | 0.3%    |
| MSI MS-7C37                        | 15        | 0.28%   |
| HP Pavilion Notebook               | 15        | 0.28%   |
| Dell OptiPlex 780                  | 14        | 0.26%   |
| HP Notebook                        | 13        | 0.24%   |
| Dell OptiPlex 790                  | 13        | 0.24%   |
| ASUS TUF Gaming X570-PLUS          | 13        | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 12        | 0.22%   |
| Dell XPS 13 9370                   | 12        | 0.22%   |
| Dell Inspiron 1545                 | 12        | 0.22%   |
| Gigabyte X570 AORUS ELITE          | 11        | 0.21%   |
| Dell XPS 15 9570                   | 11        | 0.21%   |
| Dell XPS 15 9560                   | 11        | 0.21%   |
| Dell XPS 15 7590                   | 11        | 0.21%   |
| Dell XPS 13 9360                   | 11        | 0.21%   |
| Dell Latitude E6410                | 11        | 0.21%   |
| Dell Latitude E6400                | 11        | 0.21%   |
| Lenovo V145-15AST 81MT             | 10        | 0.19%   |
| Gigabyte GA-78LMT-USB3             | 10        | 0.19%   |
| Gigabyte 970A-DS3P                 | 10        | 0.19%   |
| Dell Latitude E7240                | 10        | 0.19%   |
| Lenovo Z50-75 80EC                 | 9         | 0.17%   |
| HP 15                              | 9         | 0.17%   |
| Gigabyte GA-78LMT-USB3 6.0         | 9         | 0.17%   |
| Dell XPS 13 9380                   | 9         | 0.17%   |
| Dell Vostro 200                    | 9         | 0.17%   |
| ASUS PRIME B450M-A                 | 9         | 0.17%   |
| ASUS PRIME A320M-K                 | 9         | 0.17%   |
| Toshiba Satellite C660             | 8         | 0.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 8         | 0.15%   |
| MSI MS-7B85                        | 8         | 0.15%   |
| HP ProLiant MicroServer            | 8         | 0.15%   |
| HP Laptop 15-da0xxx                | 8         | 0.15%   |
| HP Laptop 15-bw0xx                 | 8         | 0.15%   |
| Gigabyte B450M DS3H                | 8         | 0.15%   |
| Dell XPS 15 9550                   | 8         | 0.15%   |
| Dell XPS 13 9310                   | 8         | 0.15%   |
| Dell Precision WorkStation T3500   | 8         | 0.15%   |
| Dell Latitude E7450                | 8         | 0.15%   |
| Dell Latitude E7440                | 8         | 0.15%   |
| ASUS ROG CROSSHAIR VIII HERO       | 8         | 0.15%   |
| ASUS PRIME X370-PRO                | 8         | 0.15%   |
| ASRock N68C-S UCC                  | 8         | 0.15%   |
| Apple MacBookPro9,2                | 8         | 0.15%   |
| Valve Jupiter                      | 7         | 0.13%   |
| MSI MS-7C91                        | 7         | 0.13%   |
| MSI MS-7B79                        | 7         | 0.13%   |
| MSI MS-7A34                        | 7         | 0.13%   |
| MSI MS-7758                        | 7         | 0.13%   |
| MSI MS-7721                        | 7         | 0.13%   |
| Microsoft Surface Pro 4            | 7         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 312       | 5.84%   |
| Dell Latitude          | 195       | 3.65%   |
| Acer Aspire            | 193       | 3.61%   |
| Dell Inspiron          | 180       | 3.37%   |
| Dell OptiPlex          | 149       | 2.79%   |
| Dell XPS               | 137       | 2.57%   |
| HP Pavilion            | 120       | 2.25%   |
| Toshiba Satellite      | 116       | 2.17%   |
| ASUS ROG               | 109       | 2.04%   |
| Lenovo IdeaPad         | 101       | 1.89%   |
| ASUS PRIME             | 92        | 1.72%   |
| HP EliteBook           | 82        | 1.54%   |
| Dell Precision         | 81        | 1.52%   |
| HP Compaq              | 80        | 1.5%    |
| RPi Raspberry          | 59        | 1.1%    |
| ASUS All               | 59        | 1.1%    |
| Unknown                | 56        | 1.05%   |
| Lenovo ThinkCentre     | 47        | 0.88%   |
| HP ProBook             | 44        | 0.82%   |
| HP Laptop              | 44        | 0.82%   |
| ASUS TUF               | 41        | 0.77%   |
| HP ENVY                | 39        | 0.73%   |
| Dell Vostro            | 36        | 0.67%   |
| ASUS VivoBook          | 34        | 0.64%   |
| HP ProLiant            | 28        | 0.52%   |
| Lenovo Yoga            | 27        | 0.51%   |
| Microsoft Surface      | 25        | 0.47%   |
| Gigabyte X570          | 25        | 0.47%   |
| HP Stream              | 24        | 0.45%   |
| ASUS M5A78L-M          | 23        | 0.43%   |
| Gigabyte GA-78LMT-USB3 | 21        | 0.39%   |
| MSI MS-7C02            | 20        | 0.37%   |
| HP Spectre             | 19        | 0.36%   |
| HP EliteDesk           | 19        | 0.36%   |
| Acer Swift             | 17        | 0.32%   |
| Lenovo Legion          | 16        | 0.3%    |
| Gigabyte Z390          | 16        | 0.3%    |
| Fujitsu ESPRIMO        | 16        | 0.3%    |
| Dell PowerEdge         | 16        | 0.3%    |
| ASUS ZenBook           | 16        | 0.3%    |
| MSI MS-7C37            | 15        | 0.28%   |
| ASUS SABERTOOTH        | 15        | 0.28%   |
| Razer Blade            | 14        | 0.26%   |
| HP 255                 | 14        | 0.26%   |
| Fujitsu LIFEBOOK       | 14        | 0.26%   |
| Lenovo IdeaCentre      | 13        | 0.24%   |
| HP ZBook               | 13        | 0.24%   |
| HP ProDesk             | 13        | 0.24%   |
| HP Presario            | 13        | 0.24%   |
| HP Notebook            | 13        | 0.24%   |
| Gigabyte B450M         | 12        | 0.22%   |
| Dell System            | 12        | 0.22%   |
| Dell Studio            | 12        | 0.22%   |
| ASUS Maximus           | 12        | 0.22%   |
| Packard Bell EasyNote  | 11        | 0.21%   |
| HP OMEN                | 11        | 0.21%   |
| Gigabyte B450          | 11        | 0.21%   |
| Gigabyte A320M-S2H     | 11        | 0.21%   |
| Gigabyte 970A-DS3P     | 11        | 0.21%   |
| ASUS P8Z77-V           | 11        | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 556       | 10.41%  |
| 2019    | 480       | 8.99%   |
| 2012    | 461       | 8.63%   |
| 2020    | 404       | 7.57%   |
| 2013    | 391       | 7.32%   |
| 2011    | 390       | 7.3%    |
| 2017    | 365       | 6.84%   |
| 2014    | 352       | 6.59%   |
| 2010    | 320       | 5.99%   |
| 2015    | 289       | 5.41%   |
| 2016    | 283       | 5.3%    |
| 2009    | 242       | 4.53%   |
| 2008    | 233       | 4.36%   |
| 2021    | 219       | 4.1%    |
| 2007    | 169       | 3.16%   |
| 2006    | 71        | 1.33%   |
| Unknown | 67        | 1.25%   |
| 2005    | 22        | 0.41%   |
| 2022    | 15        | 0.28%   |
| 2004    | 6         | 0.11%   |
| 2003    | 3         | 0.06%   |
| 2002    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2690      | 50.37%  |
| Desktop        | 2196      | 41.12%  |
| All in one     | 95        | 1.78%   |
| Convertible    | 89        | 1.67%   |
| Mini pc        | 88        | 1.65%   |
| System on chip | 69        | 1.29%   |
| Tablet         | 64        | 1.2%    |
| Server         | 44        | 0.82%   |
| Phone          | 4         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4954      | 92.08%  |
| Enabled  | 426       | 7.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5304      | 99.33%  |
| Yes  | 36        | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1183      | 21.77%  |
| 16.01-24.0      | 1160      | 21.35%  |
| 3.01-4.0        | 1019      | 18.75%  |
| 8.01-16.0       | 910       | 16.75%  |
| 32.01-64.0      | 528       | 9.72%   |
| 1.01-2.0        | 266       | 4.9%    |
| 64.01-256.0     | 139       | 2.56%   |
| 2.01-3.0        | 104       | 1.91%   |
| 24.01-32.0      | 66        | 1.21%   |
| 0.51-1.0        | 52        | 0.96%   |
| More than 256.0 | 4         | 0.07%   |
| 0.01-0.5        | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2355      | 39.36%  |
| 2.01-3.0    | 1431      | 23.92%  |
| 4.01-8.0    | 729       | 12.18%  |
| 3.01-4.0    | 670       | 11.2%   |
| 0.51-1.0    | 438       | 7.32%   |
| 8.01-16.0   | 206       | 3.44%   |
| 0.01-0.5    | 87        | 1.45%   |
| 16.01-24.0  | 34        | 0.57%   |
| 24.01-32.0  | 15        | 0.25%   |
| 32.01-64.0  | 12        | 0.2%    |
| Unknown     | 4         | 0.07%   |
| 64.01-256.0 | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3103      | 56.06%  |
| 2       | 1375      | 24.84%  |
| 3       | 455       | 8.22%   |
| 4       | 253       | 4.57%   |
| 5       | 136       | 2.46%   |
| 6       | 69        | 1.25%   |
| 0       | 62        | 1.12%   |
| 7       | 31        | 0.56%   |
| 9       | 14        | 0.25%   |
| 8       | 13        | 0.23%   |
| Unknown | 8         | 0.14%   |
| 11      | 5         | 0.09%   |
| 12      | 4         | 0.07%   |
| 13      | 3         | 0.05%   |
| 10      | 2         | 0.04%   |
| 21      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3042      | 56.31%  |
| Yes       | 2360      | 43.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4593      | 85.87%  |
| No        | 756       | 14.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4018      | 74.64%  |
| No        | 1365      | 25.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2994      | 55.36%  |
| No        | 2414      | 44.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 5340      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| London               | 302       | 5.16%   |
| Manchester           | 126       | 2.15%   |
| Birmingham           | 94        | 1.61%   |
| Bristol              | 90        | 1.54%   |
| Glasgow              | 87        | 1.49%   |
| Edinburgh            | 83        | 1.42%   |
| Sheffield            | 79        | 1.35%   |
| Nottingham           | 70        | 1.2%    |
| Liverpool            | 64        | 1.09%   |
| Leeds                | 54        | 0.92%   |
| Norwich              | 53        | 0.91%   |
| Reading              | 51        | 0.87%   |
| Islington            | 50        | 0.85%   |
| Cambridge            | 50        | 0.85%   |
| Southampton          | 39        | 0.67%   |
| Milton Keynes        | 39        | 0.67%   |
| Coventry             | 39        | 0.67%   |
| Derby                | 37        | 0.63%   |
| Croydon              | 37        | 0.63%   |
| Cardiff              | 35        | 0.6%    |
| Aberdeen             | 35        | 0.6%    |
| Leicester            | 34        | 0.58%   |
| Swindon              | 33        | 0.56%   |
| Hackney              | 33        | 0.56%   |
| Oxford               | 32        | 0.55%   |
| Gloucester           | 31        | 0.53%   |
| Clapham              | 30        | 0.51%   |
| Brighton             | 30        | 0.51%   |
| Bradford             | 30        | 0.51%   |
| Kensington           | 29        | 0.5%    |
| Bolton               | 29        | 0.5%    |
| Wigan                | 28        | 0.48%   |
| Newcastle upon Tyne  | 28        | 0.48%   |
| Wolverhampton        | 27        | 0.46%   |
| Plymouth             | 27        | 0.46%   |
| Walsall              | 26        | 0.44%   |
| York                 | 25        | 0.43%   |
| Sunderland           | 25        | 0.43%   |
| Harrow               | 25        | 0.43%   |
| Bromley              | 25        | 0.43%   |
| Ipswich              | 24        | 0.41%   |
| Camden               | 23        | 0.39%   |
| Belfast              | 23        | 0.39%   |
| Stoke-on-Trent       | 22        | 0.38%   |
| Balham               | 22        | 0.38%   |
| Stockport            | 21        | 0.36%   |
| Chesterfield         | 21        | 0.36%   |
| Woking               | 20        | 0.34%   |
| Swansea              | 20        | 0.34%   |
| Rotherham            | 20        | 0.34%   |
| Finchley             | 20        | 0.34%   |
| Chelmsford           | 20        | 0.34%   |
| Portsmouth           | 19        | 0.32%   |
| Poplar               | 19        | 0.32%   |
| Peterborough         | 19        | 0.32%   |
| Bermondsey           | 19        | 0.32%   |
| Barnsley             | 19        | 0.32%   |
| Telford              | 18        | 0.31%   |
| Slough               | 18        | 0.31%   |
| Royal Leamington Spa | 18        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1281      | 2111   | 15.94%  |
| Samsung Electronics       | 1213      | 1881   | 15.1%   |
| WDC                       | 1181      | 1952   | 14.7%   |
| Toshiba                   | 578       | 775    | 7.19%   |
| SanDisk                   | 452       | 584    | 5.63%   |
| Unknown                   | 423       | 593    | 5.26%   |
| Crucial                   | 397       | 574    | 4.94%   |
| Kingston                  | 358       | 488    | 4.46%   |
| Hitachi                   | 341       | 456    | 4.24%   |
| Intel                     | 162       | 217    | 2.02%   |
| SK hynix                  | 151       | 183    | 1.88%   |
| HGST                      | 145       | 209    | 1.8%    |
| Phison                    | 118       | 159    | 1.47%   |
| China                     | 78        | 107    | 0.97%   |
| Apple                     | 78        | 105    | 0.97%   |
| A-DATA Technology         | 73        | 95     | 0.91%   |
| Micron Technology         | 72        | 86     | 0.9%    |
| OCZ                       | 54        | 62     | 0.67%   |
| Maxtor                    | 54        | 81     | 0.67%   |
| Corsair                   | 44        | 59     | 0.55%   |
| PNY                       | 43        | 55     | 0.54%   |
| LITEON                    | 43        | 50     | 0.54%   |
| Transcend                 | 42        | 50     | 0.52%   |
| KIOXIA                    | 40        | 53     | 0.5%    |
| Fujitsu                   | 37        | 50     | 0.46%   |
| Silicon Motion            | 35        | 45     | 0.44%   |
| LITEONIT                  | 30        | 37     | 0.37%   |
| Micron/Crucial Technology | 19        | 27     | 0.24%   |
| JMicron Technology        | 19        | 30     | 0.24%   |
| ASMT                      | 19        | 47     | 0.24%   |
| Patriot                   | 18        | 29     | 0.22%   |
| Integral                  | 17        | 20     | 0.21%   |
| SABRENT                   | 16        | 18     | 0.2%    |
| Drevo                     | 15        | 19     | 0.19%   |
| Unknown                   | 15        | 16     | 0.19%   |
| Gigabyte Technology       | 14        | 20     | 0.17%   |
| Team                      | 12        | 12     | 0.15%   |
| SPCC                      | 12        | 20     | 0.15%   |
| Vaseky                    | 11        | 15     | 0.14%   |
| Netac                     | 11        | 13     | 0.14%   |
| Hewlett-Packard           | 11        | 35     | 0.14%   |
| Lexar                     | 10        | 12     | 0.12%   |
| TO Exter                  | 9         | 10     | 0.11%   |
| TCSUNBOW                  | 9         | 14     | 0.11%   |
| XPG                       | 8         | 9      | 0.1%    |
| KingFast                  | 8         | 8      | 0.1%    |
| KingDian                  | 8         | 11     | 0.1%    |
| Lenovo                    | 7         | 7      | 0.09%   |
| KIOXIA-EXCERIA            | 7         | 10     | 0.09%   |
| USB3.0                    | 6         | 10     | 0.07%   |
| Plextor                   | 6         | 9      | 0.07%   |
| KingSpec                  | 6         | 8      | 0.07%   |
| BIWIN                     | 6         | 6      | 0.07%   |
| ORTIAL                    | 5         | 5      | 0.06%   |
| NGFF                      | 5         | 5      | 0.06%   |
| Star                      | 4         | 5      | 0.05%   |
| SATA SSD                  | 4         | 4      | 0.05%   |
| Realtek                   | 4         | 5      | 0.05%   |
| Mushkin                   | 4         | 4      | 0.05%   |
| Intenso                   | 4         | 5      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 105       | 1.16%   |
| Samsung SSD 850 EVO 250GB              | 77        | 0.85%   |
| Seagate ST3500312CS 500GB              | 76        | 0.84%   |
| Samsung SSD 850 EVO 500GB              | 63        | 0.7%    |
| Kingston SA400S37240G 240GB SSD        | 63        | 0.7%    |
| Kingston SA400S37120G 120GB SSD        | 59        | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 58        | 0.64%   |
| Crucial CT500MX500SSD1 500GB           | 57        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 56        | 0.62%   |
| Unknown MMC Card  64GB                 | 55        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB         | 55        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB         | 54        | 0.6%    |
| Samsung SSD 860 EVO 500GB              | 54        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB         | 51        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB            | 50        | 0.55%   |
| Samsung NVMe SSD Drive 512GB           | 49        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB        | 48        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB           | 48        | 0.53%   |
| Unknown MMC Card  128GB                | 45        | 0.5%    |
| Toshiba MQ01ABD100 1TB                 | 45        | 0.5%    |
| Samsung SSD 860 EVO 1TB                | 45        | 0.5%    |
| Samsung NVMe SSD Drive 1TB             | 45        | 0.5%    |
| Samsung NVMe SSD Drive 256GB           | 44        | 0.49%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 37        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD       | 35        | 0.39%   |
| HGST HTS721010A9E630 1TB               | 35        | 0.39%   |
| Samsung SSD 840 EVO 250GB              | 34        | 0.38%   |
| Seagate Expansion 1TB                  | 33        | 0.37%   |
| Crucial CT250MX500SSD1 250GB           | 33        | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB         | 32        | 0.35%   |
| Unknown SD/MMC/MS PRO 128GB            | 31        | 0.34%   |
| SanDisk SSD PLUS 240GB                 | 31        | 0.34%   |
| HGST HTS541010A9E680 1TB               | 31        | 0.34%   |
| Crucial CT240BX500SSD1 240GB           | 31        | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB         | 30        | 0.33%   |
| Toshiba DT01ACA100 1TB                 | 29        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB         | 29        | 0.32%   |
| SanDisk NVMe SSD Drive 1TB             | 27        | 0.3%    |
| Toshiba MQ01ABF050 500GB               | 26        | 0.29%   |
| Seagate Expansion+ Desk 4TB            | 26        | 0.29%   |
| SanDisk SSD PLUS 480GB                 | 26        | 0.29%   |
| Samsung SSD 860 QVO 1TB                | 26        | 0.29%   |
| Samsung SSD 860 EVO 250GB              | 26        | 0.29%   |
| Unknown MMC Card  16GB                 | 25        | 0.28%   |
| Toshiba HDWD130 3TB                    | 25        | 0.28%   |
| Samsung HD103SJ 1TB                    | 25        | 0.28%   |
| WDC WD20EZRX-00D8PB0 2TB               | 24        | 0.27%   |
| Seagate ST3500418AS 500GB              | 24        | 0.27%   |
| Seagate ST1000DM003-1CH162 1TB         | 24        | 0.27%   |
| Samsung NVMe SSD Drive 250GB           | 24        | 0.27%   |
| Samsung NVMe SSD Drive 1024GB          | 24        | 0.27%   |
| Phison Sabrent 1TB                     | 24        | 0.27%   |
| WDC WD10EZEX-08WN4A0 1TB               | 23        | 0.25%   |
| SanDisk NVMe SSD Drive 512GB           | 23        | 0.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 22        | 0.24%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 22        | 0.24%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 22        | 0.24%   |
| Seagate ST2000DM006-2DM164 2TB         | 22        | 0.24%   |
| Crucial CT525MX300SSD1 528GB           | 22        | 0.24%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 21        | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1241      | 2033   | 35.45%  |
| WDC                 | 944       | 1599   | 26.96%  |
| Toshiba             | 424       | 582    | 12.11%  |
| Hitachi             | 340       | 454    | 9.71%   |
| Samsung Electronics | 176       | 248    | 5.03%   |
| HGST                | 145       | 209    | 4.14%   |
| Maxtor              | 44        | 71     | 1.26%   |
| Apple               | 39        | 43     | 1.11%   |
| Unknown             | 37        | 50     | 1.06%   |
| Fujitsu             | 37        | 50     | 1.06%   |
| ASMT                | 17        | 44     | 0.49%   |
| JMicron Technology  | 10        | 17     | 0.29%   |
| Hewlett-Packard     | 10        | 34     | 0.29%   |
| USB3.0              | 6         | 10     | 0.17%   |
| ASMT109x            | 3         | 5      | 0.09%   |
| ASMedia             | 3         | 8      | 0.09%   |
| WD MediaMax         | 2         | 2      | 0.06%   |
| USB                 | 2         | 2      | 0.06%   |
| LaCie               | 2         | 2      | 0.06%   |
| IBM/Hitachi         | 2         | 2      | 0.06%   |
| HPE                 | 2         | 4      | 0.06%   |
| ExcelStor           | 2         | 4      | 0.06%   |
| TrueNAS             | 1         | 3      | 0.03%   |
| SAGE                | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| NETAPP              | 1         | 4      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 8      | 0.03%   |
| KESU                | 1         | 5      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 645       | 943    | 23.57%  |
| Crucial             | 370       | 542    | 13.52%  |
| SanDisk             | 335       | 420    | 12.24%  |
| Kingston            | 311       | 416    | 11.37%  |
| WDC                 | 144       | 204    | 5.26%   |
| Intel               | 74        | 85     | 2.7%    |
| China               | 74        | 103    | 2.7%    |
| A-DATA Technology   | 58        | 74     | 2.12%   |
| OCZ                 | 54        | 62     | 1.97%   |
| Toshiba             | 48        | 58     | 1.75%   |
| Micron Technology   | 45        | 53     | 1.64%   |
| SK hynix            | 43        | 54     | 1.57%   |
| LITEON              | 42        | 49     | 1.54%   |
| Transcend           | 41        | 49     | 1.5%    |
| PNY                 | 40        | 48     | 1.46%   |
| Apple               | 36        | 48     | 1.32%   |
| LITEONIT            | 30        | 37     | 1.1%    |
| Corsair             | 26        | 36     | 0.95%   |
| Patriot             | 18        | 29     | 0.66%   |
| Integral            | 17        | 20     | 0.62%   |
| Unknown             | 16        | 18     | 0.58%   |
| Seagate             | 16        | 18     | 0.58%   |
| Drevo               | 15        | 19     | 0.55%   |
| Team                | 12        | 12     | 0.44%   |
| Vaseky              | 11        | 15     | 0.4%    |
| Netac               | 10        | 11     | 0.37%   |
| Maxtor              | 10        | 10     | 0.37%   |
| Lexar               | 10        | 12     | 0.37%   |
| Gigabyte Technology | 10        | 14     | 0.37%   |
| TO Exter            | 9         | 10     | 0.33%   |
| SPCC                | 9         | 17     | 0.33%   |
| TCSUNBOW            | 8         | 13     | 0.29%   |
| KingDian            | 7         | 10     | 0.26%   |
| Plextor             | 6         | 9      | 0.22%   |
| KIOXIA-EXCERIA      | 6         | 9      | 0.22%   |
| KingSpec            | 6         | 8      | 0.22%   |
| ORTIAL              | 5         | 5      | 0.18%   |
| NGFF                | 5         | 5      | 0.18%   |
| BIWIN               | 5         | 5      | 0.18%   |
| Star                | 4         | 5      | 0.15%   |
| Mushkin             | 4         | 4      | 0.15%   |
| Dogfish             | 4         | 4      | 0.15%   |
| BHT                 | 4         | 7      | 0.15%   |
| Argon               | 4         | 7      | 0.15%   |
| ZTC                 | 3         | 5      | 0.11%   |
| Zheino              | 3         | 6      | 0.11%   |
| Verbatim            | 3         | 3      | 0.11%   |
| Intenso             | 3         | 4      | 0.11%   |
| Hoodisk             | 3         | 3      | 0.11%   |
| FORESEE             | 3         | 3      | 0.11%   |
| BAITITON            | 3         | 4      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |
| W800S               | 2         | 2      | 0.07%   |
| VENO                | 2         | 4      | 0.07%   |
| V Series            | 2         | 2      | 0.07%   |
| Solid               | 2         | 2      | 0.07%   |
| Pioneer             | 2         | 2      | 0.07%   |
| OCZ-VERTEX          | 2         | 2      | 0.07%   |
| OCZ-AGIL            | 2         | 2      | 0.07%   |
| KIOXIA-E            | 2         | 3      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2841      | 5502   | 40.47%  |
| SSD     | 2323      | 3690   | 33.09%  |
| NVMe    | 1364      | 1958   | 19.43%  |
| MMC     | 372       | 513    | 5.3%    |
| Unknown | 120       | 177    | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4199      | 8793   | 67%     |
| NVMe | 1350      | 1934   | 21.54%  |
| MMC  | 372       | 513    | 5.94%   |
| SAS  | 346       | 600    | 5.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3153      | 5187   | 56.71%  |
| 0.51-1.0   | 1490      | 2287   | 26.8%   |
| 1.01-2.0   | 489       | 860    | 8.79%   |
| 3.01-4.0   | 163       | 295    | 2.93%   |
| 2.01-3.0   | 145       | 264    | 2.61%   |
| 4.01-10.0  | 103       | 259    | 1.85%   |
| 10.01-20.0 | 16        | 39     | 0.29%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1598      | 28.24%  |
| 251-500        | 1090      | 19.26%  |
| 501-1000       | 819       | 14.47%  |
| 1001-2000      | 431       | 7.62%   |
| 51-100         | 393       | 6.94%   |
| 1-20           | 357       | 6.31%   |
| More than 3000 | 330       | 5.83%   |
| 21-50          | 283       | 5%      |
| 2001-3000      | 182       | 3.22%   |
| Unknown        | 176       | 3.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2396      | 40.67%  |
| 21-50          | 971       | 16.48%  |
| 101-250        | 657       | 11.15%  |
| 51-100         | 625       | 10.61%  |
| 251-500        | 400       | 6.79%   |
| 501-1000       | 291       | 4.94%   |
| 1001-2000      | 185       | 3.14%   |
| Unknown        | 176       | 2.99%   |
| More than 3000 | 122       | 2.07%   |
| 2001-3000      | 67        | 1.14%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 6         | 7      | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB          | 4         | 4      | 1.07%   |
| Seagate ST3500418AS 500GB                | 4         | 4      | 1.07%   |
| Seagate ST3500312CS 500GB                | 4         | 6      | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 4         | 5      | 1.07%   |
| Samsung Electronics HD103UJ 1TB          | 4         | 6      | 1.07%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 1.07%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 1.07%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.8%    |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.8%    |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.8%    |
| Seagate ST9500325AS 500GB                | 3         | 4      | 0.8%    |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.8%    |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.8%    |
| Samsung Electronics SSD 960 EVO 250GB    | 3         | 4      | 0.8%    |
| Samsung Electronics HD103SJ 1TB          | 3         | 3      | 0.8%    |
| Hitachi HTS547575A9E384 752GB            | 3         | 5      | 0.8%    |
| Hitachi HTS542512K9SA00 120GB            | 3         | 3      | 0.8%    |
| Hitachi HDT721010SLA360 1TB              | 3         | 4      | 0.8%    |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.8%    |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.8%    |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.8%    |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.8%    |
| WDC WD800JD-00HKA0 80GB                  | 2         | 2      | 0.53%   |
| WDC WD6400AAKS-22A7B2 640GB              | 2         | 2      | 0.53%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2         | 2      | 0.53%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 2         | 3      | 0.53%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2         | 2      | 0.53%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.53%   |
| WDC WD2500BEVT-80A23T0 250GB             | 2         | 4      | 0.53%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 2         | 2      | 0.53%   |
| WDC WD10EADS-00L5B1 1TB                  | 2         | 2      | 0.53%   |
| Unknown MM0500EBKAE 500GB                | 2         | 2      | 0.53%   |
| Toshiba MK3276GSX -63 320GB              | 2         | 2      | 0.53%   |
| Toshiba MK1656GSY 160GB                  | 2         | 2      | 0.53%   |
| Toshiba DT01ACA100 1TB                   | 2         | 2      | 0.53%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 0.53%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 0.53%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 0.53%   |
| Seagate ST500LM000-SSHD-8GB              | 2         | 2      | 0.53%   |
| Seagate ST500DM002-1BC142 500GB          | 2         | 2      | 0.53%   |
| Seagate ST31000524AS 1TB                 | 2         | 2      | 0.53%   |
| Seagate ST31000333AS 1TB                 | 2         | 2      | 0.53%   |
| Seagate ST31000322CS 1TB                 | 2         | 2      | 0.53%   |
| Seagate ST1000DM003-9YN162 1TB           | 2         | 3      | 0.53%   |
| SanDisk SSD PLUS 480GB                   | 2         | 2      | 0.53%   |
| SanDisk SDSSDA240G 240GB                 | 2         | 3      | 0.53%   |
| Samsung Electronics SSD 970 EVO 2TB      | 2         | 2      | 0.53%   |
| Samsung Electronics SSD 870 EVO 2TB      | 2         | 5      | 0.53%   |
| Samsung Electronics SSD 840 Series 120GB | 2         | 2      | 0.53%   |
| Samsung Electronics HD501LJ 500GB        | 2         | 2      | 0.53%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD     | 2         | 2      | 0.53%   |
| Kingston SH103S3120G 120GB SSD           | 2         | 4      | 0.53%   |
| Intel SSDSA2M080G2GC 80GB                | 2         | 2      | 0.53%   |
| Intel SSDPEKKW512G7 512GB                | 2         | 3      | 0.53%   |
| Hitachi HUA723030ALA640 3TB              | 2         | 3      | 0.53%   |
| Hitachi HTS547564A9E384 640GB            | 2         | 2      | 0.53%   |
| Hitachi HTS545032B9A302 320GB            | 2         | 3      | 0.53%   |
| Hitachi HDS722020ALA330 2TB              | 2         | 16     | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 89        | 108    | 24.45%  |
| WDC                 | 75        | 125    | 20.6%   |
| Hitachi             | 47        | 70     | 12.91%  |
| Samsung Electronics | 32        | 40     | 8.79%   |
| Crucial             | 21        | 27     | 5.77%   |
| Toshiba             | 20        | 25     | 5.49%   |
| HGST                | 17        | 18     | 4.67%   |
| SanDisk             | 11        | 15     | 3.02%   |
| Intel               | 9         | 10     | 2.47%   |
| Kingston            | 7         | 9      | 1.92%   |
| Maxtor              | 4         | 4      | 1.1%    |
| Fujitsu             | 4         | 4      | 1.1%    |
| SK hynix            | 3         | 3      | 0.82%   |
| LITEON              | 3         | 3      | 0.82%   |
| Corsair             | 3         | 7      | 0.82%   |
| A-DATA Technology   | 3         | 3      | 0.82%   |
| Unknown             | 2         | 2      | 0.55%   |
| Micron Technology   | 2         | 2      | 0.55%   |
| Hewlett-Packard     | 2         | 2      | 0.55%   |
| Drevo               | 2         | 2      | 0.55%   |
| Zheino              | 1         | 2      | 0.27%   |
| VENO                | 1         | 1      | 0.27%   |
| Team                | 1         | 1      | 0.27%   |
| Faspeed             | 1         | 1      | 0.27%   |
| BIWIN               | 1         | 1      | 0.27%   |
| BAITITON            | 1         | 2      | 0.27%   |
| Apple               | 1         | 2      | 0.27%   |
| Apacer              | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 89        | 108    | 32.48%  |
| WDC                 | 74        | 124    | 27.01%  |
| Hitachi             | 47        | 70     | 17.15%  |
| Toshiba             | 19        | 24     | 6.93%   |
| HGST                | 17        | 18     | 6.2%    |
| Samsung Electronics | 15        | 19     | 5.47%   |
| Maxtor              | 4         | 4      | 1.46%   |
| Fujitsu             | 4         | 4      | 1.46%   |
| Unknown             | 2         | 2      | 0.73%   |
| Hewlett-Packard     | 2         | 2      | 0.73%   |
| Apple               | 1         | 2      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 250       | 377    | 73.53%  |
| SSD  | 75        | 96     | 22.06%  |
| NVMe | 15        | 17     | 4.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 2         | 3      | 50%     |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 25%     |
| Seagate ST3160815AS 160GB        | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 4      | 75%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3758      | 8120   | 65.85%  |
| Works    | 1616      | 3225   | 28.32%  |
| Malfunc  | 329       | 490    | 5.76%   |
| Failed   | 4         | 5      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3468      | 52.55%  |
| AMD                              | 1142      | 17.31%  |
| Samsung Electronics              | 557       | 8.44%   |
| SanDisk                          | 216       | 3.27%   |
| Phison Electronics               | 144       | 2.18%   |
| ASMedia Technology               | 140       | 2.12%   |
| Nvidia                           | 125       | 1.89%   |
| Toshiba America Info Systems     | 119       | 1.8%    |
| SK hynix                         | 104       | 1.58%   |
| Marvell Technology Group         | 102       | 1.55%   |
| JMicron Technology               | 75        | 1.14%   |
| Kingston Technology Company      | 49        | 0.74%   |
| Micron/Crucial Technology        | 46        | 0.7%    |
| Silicon Motion                   | 37        | 0.56%   |
| KIOXIA                           | 36        | 0.55%   |
| Micron Technology                | 29        | 0.44%   |
| LSI Logic / Symbios Logic        | 27        | 0.41%   |
| ADATA Technology                 | 25        | 0.38%   |
| Broadcom / LSI                   | 21        | 0.32%   |
| VIA Technologies                 | 20        | 0.3%    |
| Silicon Image                    | 18        | 0.27%   |
| Silicon Integrated Systems [SiS] | 15        | 0.23%   |
| Seagate Technology               | 15        | 0.23%   |
| Hewlett-Packard                  | 11        | 0.17%   |
| Realtek Semiconductor            | 7         | 0.11%   |
| Lenovo                           | 7         | 0.11%   |
| Apple                            | 7         | 0.11%   |
| Adaptec                          | 7         | 0.11%   |
| Union Memory (Shenzhen)          | 4         | 0.06%   |
| Lite-On Technology               | 4         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.03%   |
| Dell                             | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Initio                           | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Broadcom                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Areca Technology                 | 1         | 0.02%   |
| Advanced System Products         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 764       | 9.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 321       | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 235       | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 225       | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 213       | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 187       | 2.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 163       | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 157       | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 145       | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 139       | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 133       | 1.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 133       | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 131       | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 112       | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 107       | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 102       | 1.31%   |
| Intel SATA Controller [RAID mode]                                                       | 100       | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 100       | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 95        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 94        | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 92        | 1.18%   |
| Phison E12 NVMe Controller                                                              | 89        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 88        | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 88        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 87        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 78        | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 73        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 69        | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 64        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 62        | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 61        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 58        | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 56        | 0.72%   |
| Samsung NVMe SSD Controller 980                                                         | 56        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 56        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 55        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 52        | 0.67%   |
| Nvidia MCP61 SATA Controller                                                            | 51        | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 51        | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 51        | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 51        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 51        | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 50        | 0.64%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 50        | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 49        | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 48        | 0.62%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 45        | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 44        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 44        | 0.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 43        | 0.55%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 42        | 0.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 41        | 0.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 40        | 0.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 39        | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 39        | 0.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 39        | 0.5%    |
| Intel SSD 660P Series                                                                   | 38        | 0.49%   |
| Nvidia MCP61 IDE                                                                        | 37        | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 34        | 0.44%   |
| KIOXIA Non-Volatile memory controller                                                   | 34        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3860      | 57.97%  |
| NVMe | 1370      | 20.57%  |
| IDE  | 943       | 14.16%  |
| RAID | 431       | 6.47%   |
| SAS  | 30        | 0.45%   |
| SCSI | 25        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3948      | 73.93%  |
| AMD          | 1316      | 24.64%  |
| ARM          | 74        | 1.39%   |
| QUALCOMM     | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 67        | 1.25%   |
| ARM Processor                                 | 56        | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 50        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 41        | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 0.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 40        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 37        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 36        | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 34        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 0.62%   |
| AMD FX-8350 Eight-Core Processor              | 33        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 32        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 32        | 0.6%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 32        | 0.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 32        | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 31        | 0.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 31        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 31        | 0.58%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 30        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 30        | 0.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 30        | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 29        | 0.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.49%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 25        | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 24        | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 23        | 0.43%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 23        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 22        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 22        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 21        | 0.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 21        | 0.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 21        | 0.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.39%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 21        | 0.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 0.39%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 21        | 0.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 0.39%   |
| AMD FX-6300 Six-Core Processor                | 21        | 0.39%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 20        | 0.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 0.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 19        | 0.35%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 19        | 0.35%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 19        | 0.35%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 19        | 0.35%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 18        | 0.34%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.34%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 18        | 0.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.34%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 17        | 0.32%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 17        | 0.32%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 17        | 0.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1076      | 20.12%  |
| Intel Core i7           | 1066      | 19.93%  |
| Intel Core i3           | 345       | 6.45%   |
| Intel Core 2 Duo        | 260       | 4.86%   |
| Intel Celeron           | 259       | 4.84%   |
| AMD Ryzen 5             | 256       | 4.79%   |
| Other                   | 223       | 4.17%   |
| AMD Ryzen 7             | 216       | 4.04%   |
| Intel Xeon              | 165       | 3.09%   |
| Intel Pentium           | 154       | 2.88%   |
| AMD FX                  | 119       | 2.23%   |
| Intel Atom              | 105       | 1.96%   |
| AMD Ryzen 9             | 85        | 1.59%   |
| AMD A6                  | 68        | 1.27%   |
| AMD Ryzen 3             | 66        | 1.23%   |
| AMD A8                  | 62        | 1.16%   |
| Intel Core 2 Quad       | 60        | 1.12%   |
| Intel Pentium Dual-Core | 58        | 1.08%   |
| Intel Core 2            | 52        | 0.97%   |
| AMD A10                 | 49        | 0.92%   |
| Intel Core i9           | 41        | 0.77%   |
| Intel Pentium Dual      | 37        | 0.69%   |
| AMD Athlon II X2        | 35        | 0.65%   |
| AMD A4                  | 32        | 0.6%    |
| AMD Phenom II X4        | 29        | 0.54%   |
| Intel Genuine           | 24        | 0.45%   |
| Intel Pentium 4         | 21        | 0.39%   |
| AMD Athlon 64 X2        | 21        | 0.39%   |
| AMD Ryzen Threadripper  | 19        | 0.36%   |
| AMD E1                  | 19        | 0.36%   |
| Intel Celeron Dual-Core | 18        | 0.34%   |
| ARM BCM                 | 17        | 0.32%   |
| AMD E                   | 17        | 0.32%   |
| AMD Athlon              | 16        | 0.3%    |
| Intel Pentium D         | 14        | 0.26%   |
| AMD Athlon II X4        | 13        | 0.24%   |
| Intel Pentium Silver    | 12        | 0.22%   |
| Intel Celeron M         | 12        | 0.22%   |
| AMD Phenom II X6        | 12        | 0.22%   |
| AMD Phenom              | 11        | 0.21%   |
| AMD E2                  | 11        | 0.21%   |
| Intel Pentium M         | 9         | 0.17%   |
| AMD Sempron             | 9         | 0.17%   |
| AMD Ryzen 7 PRO         | 9         | 0.17%   |
| Intel Core m3           | 8         | 0.15%   |
| AMD Turion II Neo       | 7         | 0.13%   |
| AMD Turion 64 X2 Mobile | 7         | 0.13%   |
| AMD Athlon II           | 7         | 0.13%   |
| AMD Athlon X2           | 6         | 0.11%   |
| AMD Athlon 64           | 6         | 0.11%   |
| Intel Core m5           | 5         | 0.09%   |
| AMD Turion 64 Mobile    | 5         | 0.09%   |
| AMD Ryzen 5 PRO         | 5         | 0.09%   |
| AMD Phenom II X2        | 5         | 0.09%   |
| AMD Phenom II           | 5         | 0.09%   |
| AMD Opteron             | 5         | 0.09%   |
| AMD Athlon X4           | 5         | 0.09%   |
| AMD Athlon II X3        | 5         | 0.09%   |
| Intel Core M            | 4         | 0.07%   |
| Intel Core 2 Extreme    | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2281      | 42.66%  |
| 4       | 1858      | 34.75%  |
| 6       | 494       | 9.24%   |
| 8       | 343       | 6.41%   |
| 1       | 161       | 3.01%   |
| 12      | 69        | 1.29%   |
| 16      | 51        | 0.95%   |
| 3       | 49        | 0.92%   |
| 10      | 12        | 0.22%   |
| 24      | 10        | 0.19%   |
| 32      | 5         | 0.09%   |
| 14      | 4         | 0.07%   |
| Unknown | 3         | 0.06%   |
| 40      | 2         | 0.04%   |
| 20      | 2         | 0.04%   |
| 64      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5262      | 98.54%  |
| 2       | 72        | 1.35%   |
| Unknown | 3         | 0.06%   |
| 4       | 2         | 0.04%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3322      | 62.15%  |
| 1       | 2020      | 37.79%  |
| Unknown | 3         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5129      | 95.57%  |
| Unknown        | 164       | 3.06%   |
| 32-bit         | 69        | 1.29%   |
| 64-bit         | 5         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1152      | 20.85%  |
| 0x206a7    | 322       | 5.83%   |
| 0x306a9    | 311       | 5.63%   |
| 0x306c3    | 261       | 4.72%   |
| 0x1067a    | 229       | 4.14%   |
| 0x906ea    | 140       | 2.53%   |
| 0x506e3    | 114       | 2.06%   |
| 0x806ea    | 110       | 1.99%   |
| 0x40651    | 105       | 1.9%    |
| 0x20655    | 105       | 1.9%    |
| 0x406e3    | 104       | 1.88%   |
| 0x08701021 | 103       | 1.86%   |
| 0x806e9    | 100       | 1.81%   |
| 0x806ec    | 96        | 1.74%   |
| 0x906e9    | 91        | 1.65%   |
| 0x6fd      | 86        | 1.56%   |
| 0x306d4    | 83        | 1.5%    |
| 0x406c4    | 78        | 1.41%   |
| 0x806c1    | 71        | 1.28%   |
| 0x010000c8 | 67        | 1.21%   |
| 0x06000852 | 64        | 1.16%   |
| 0x06001119 | 62        | 1.12%   |
| 0x30678    | 60        | 1.09%   |
| 0x10676    | 59        | 1.07%   |
| 0x0800820d | 51        | 0.92%   |
| 0x08701013 | 50        | 0.9%    |
| 0x6fb      | 44        | 0.8%    |
| 0x08108109 | 43        | 0.78%   |
| 0x506c9    | 41        | 0.74%   |
| 0xa0652    | 39        | 0.71%   |
| 0x906ed    | 39        | 0.71%   |
| 0x20652    | 39        | 0.71%   |
| 0x406c3    | 36        | 0.65%   |
| 0x06006705 | 36        | 0.65%   |
| 0x08108102 | 35        | 0.63%   |
| 0x6f6      | 34        | 0.62%   |
| 0x706a1    | 31        | 0.56%   |
| 0x206c2    | 31        | 0.56%   |
| 0x106e5    | 30        | 0.54%   |
| 0x06003106 | 30        | 0.54%   |
| 0x07030105 | 28        | 0.51%   |
| 0x706e5    | 26        | 0.47%   |
| 0x08600106 | 26        | 0.47%   |
| 0x08001138 | 26        | 0.47%   |
| 0x106a5    | 25        | 0.45%   |
| 0x06006704 | 25        | 0.45%   |
| 0x05000119 | 24        | 0.43%   |
| 0x306f2    | 23        | 0.42%   |
| 0x306e4    | 23        | 0.42%   |
| 0x0a201016 | 23        | 0.42%   |
| 0x0810100b | 23        | 0.42%   |
| 0x206d7    | 22        | 0.4%    |
| 0x0a201009 | 22        | 0.4%    |
| 0x010000db | 20        | 0.36%   |
| 0xa0655    | 19        | 0.34%   |
| 0x806eb    | 19        | 0.34%   |
| 0x806d1    | 19        | 0.34%   |
| 0x706a8    | 18        | 0.33%   |
| 0x106c2    | 18        | 0.33%   |
| 0x08600104 | 17        | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 780       | 14.59%  |
| Haswell          | 465       | 8.7%    |
| SandyBridge      | 411       | 7.69%   |
| IvyBridge        | 390       | 7.3%    |
| Penryn           | 328       | 6.14%   |
| Skylake          | 274       | 5.13%   |
| Zen 2            | 268       | 5.01%   |
| Core             | 225       | 4.21%   |
| Silvermont       | 213       | 3.98%   |
| Westmere         | 206       | 3.85%   |
| Zen+             | 178       | 3.33%   |
| Piledriver       | 162       | 3.03%   |
| K10              | 148       | 2.77%   |
| Unknown          | 124       | 2.32%   |
| Zen              | 120       | 2.24%   |
| Broadwell        | 112       | 2.1%    |
| Excavator        | 90        | 1.68%   |
| CometLake        | 87        | 1.63%   |
| TigerLake        | 86        | 1.61%   |
| Zen 3            | 81        | 1.52%   |
| Nehalem          | 68        | 1.27%   |
| Goldmont plus    | 56        | 1.05%   |
| Icelake          | 55        | 1.03%   |
| K8 Hammer        | 52        | 0.97%   |
| Goldmont         | 50        | 0.94%   |
| Puma             | 44        | 0.82%   |
| Steamroller      | 43        | 0.8%    |
| NetBurst         | 40        | 0.75%   |
| Bonnell          | 39        | 0.73%   |
| P6               | 37        | 0.69%   |
| Bobcat           | 37        | 0.69%   |
| Bulldozer        | 23        | 0.43%   |
| Jaguar           | 22        | 0.41%   |
| K8 & K10 hybrid  | 10        | 0.19%   |
| K10 Llano        | 9         | 0.17%   |
| Alderlake Hybrid | 6         | 0.11%   |
| K6               | 4         | 0.07%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2933      | 48.78%  |
| Nvidia                                       | 1691      | 28.12%  |
| AMD                                          | 1321      | 21.97%  |
| Matrox Electronics Systems                   | 31        | 0.52%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.25%   |
| ATI Technologies                             | 7         | 0.12%   |
| ASPEED Technology                            | 7         | 0.12%   |
| VIA Technologies                             | 5         | 0.08%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Huawei Technologies                          | 1         | 0.02%   |
| Alliance Semiconductor                       | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 300       | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 212       | 3.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 132       | 2.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 128       | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 128       | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 123       | 1.98%   |
| Intel UHD Graphics 620                                                                   | 122       | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 122       | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 115       | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 106       | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 104       | 1.67%   |
| Intel HD Graphics 620                                                                    | 104       | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 93        | 1.49%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 85        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 85        | 1.37%   |
| Intel HD Graphics 630                                                                    | 84        | 1.35%   |
| Intel HD Graphics 5500                                                                   | 81        | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 1.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 80        | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 1.19%   |
| Intel HD Graphics 530                                                                    | 73        | 1.17%   |
| AMD Renoir                                                                               | 67        | 1.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 66        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 56        | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 52        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 51        | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 46        | 0.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 45        | 0.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 44        | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 43        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 43        | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 40        | 0.64%   |
| Intel HD Graphics 500                                                                    | 40        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 39        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 37        | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 37        | 0.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 37        | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 35        | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 33        | 0.53%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 33        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 32        | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 31        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 30        | 0.48%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 28        | 0.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 28        | 0.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.42%   |
| AMD RS780L [Radeon 3000]                                                                 | 26        | 0.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 25        | 0.4%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 23        | 0.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 23        | 0.37%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 22        | 0.35%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 21        | 0.34%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 20        | 0.32%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.32%   |
| AMD Lucienne                                                                             | 20        | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 2282      | 42.39%  |
| 1 x AMD                              | 1130      | 20.99%  |
| 1 x Nvidia                           | 1103      | 20.49%  |
| Intel + Nvidia                       | 502       | 9.33%   |
| Other                                | 83        | 1.54%   |
| Intel + AMD                          | 81        | 1.5%    |
| 2 x AMD                              | 55        | 1.02%   |
| AMD + Nvidia                         | 50        | 0.93%   |
| 1 x Matrox                           | 27        | 0.5%    |
| 2 x Nvidia                           | 26        | 0.48%   |
| 1 x SiS                              | 14        | 0.26%   |
| 1 x VIA                              | 5         | 0.09%   |
| 1 x ASPEED                           | 4         | 0.07%   |
| Nvidia + Matrox                      | 3         | 0.06%   |
| Nvidia + ASPEED                      | 3         | 0.06%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.04%   |
| Intel + 2 x Nvidia                   | 2         | 0.04%   |
| Intel + AMD + 1 x Nvidia             | 2         | 0.04%   |
| 3 x AMD                              | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.02%   |
| 2 x Intel                            | 1         | 0.02%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.02%   |
| 1 x XGI                              | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.02%   |
| 1 x Huawei Technologies              | 1         | 0.02%   |
| AMD + SiS                            | 1         | 0.02%   |
| AMD + ASPEED                         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4183      | 77.05%  |
| Proprietary | 969       | 17.85%  |
| Unknown     | 277       | 5.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2926      | 53.05%  |
| 0.01-0.5   | 672       | 12.18%  |
| 1.01-2.0   | 645       | 11.69%  |
| 0.51-1.0   | 431       | 7.81%   |
| 3.01-4.0   | 349       | 6.33%   |
| 7.01-8.0   | 248       | 4.5%    |
| 5.01-6.0   | 135       | 2.45%   |
| 8.01-16.0  | 63        | 1.14%   |
| 2.01-3.0   | 41        | 0.74%   |
| 16.01-24.0 | 3         | 0.05%   |
| 4.01-5.0   | 1         | 0.02%   |
| 24.01-32.0 | 1         | 0.02%   |
| 0          | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 661       | 11.78%  |
| AU Optronics            | 630       | 11.23%  |
| LG Display              | 484       | 8.62%   |
| Dell                    | 406       | 7.23%   |
| Chimei Innolux          | 367       | 6.54%   |
| BOE                     | 322       | 5.74%   |
| Acer                    | 262       | 4.67%   |
| Goldstar                | 202       | 3.6%    |
| Hewlett-Packard         | 189       | 3.37%   |
| AOC                     | 179       | 3.19%   |
| BenQ                    | 176       | 3.14%   |
| Sharp                   | 164       | 2.92%   |
| Apple                   | 124       | 2.21%   |
| Iiyama                  | 112       | 2%      |
| Ancor Communications    | 111       | 1.98%   |
| Lenovo                  | 101       | 1.8%    |
| Philips                 | 80        | 1.43%   |
| ViewSonic               | 66        | 1.18%   |
| Chi Mei Optoelectronics | 66        | 1.18%   |
| Sony                    | 63        | 1.12%   |
| Unknown                 | 59        | 1.05%   |
| HannStar                | 50        | 0.89%   |
| PANDA                   | 45        | 0.8%    |
| LG Philips              | 42        | 0.75%   |
| Panasonic               | 39        | 0.69%   |
| ASUSTek Computer        | 39        | 0.69%   |
| LG Electronics          | 34        | 0.61%   |
| Toshiba                 | 31        | 0.55%   |
| InfoVision              | 31        | 0.55%   |
| Vestel Elektronik       | 25        | 0.45%   |
| NEC Computers           | 20        | 0.36%   |
| MSI                     | 17        | 0.3%    |
| OEM                     | 15        | 0.27%   |
| Hitachi                 | 13        | 0.23%   |
| LGD                     | 12        | 0.21%   |
| Fujitsu Siemens         | 12        | 0.21%   |
| Idek Iiyama             | 11        | 0.2%    |
| Eizo                    | 11        | 0.2%    |
| InnoLux Display         | 10        | 0.18%   |
| Gigabyte Technology     | 10        | 0.18%   |
| CVT                     | 10        | 0.18%   |
| ___                     | 9         | 0.16%   |
| MiTAC                   | 9         | 0.16%   |
| Packard Bell            | 8         | 0.14%   |
| HPN                     | 8         | 0.14%   |
| GNR                     | 8         | 0.14%   |
| CPT                     | 8         | 0.14%   |
| Pixio                   | 7         | 0.12%   |
| MStar                   | 7         | 0.12%   |
| HannStar Display        | 7         | 0.12%   |
| DENON                   | 7         | 0.12%   |
| ANX                     | 7         | 0.12%   |
| Vestel                  | 6         | 0.11%   |
| Seiko/Epson             | 6         | 0.11%   |
| RTK                     | 6         | 0.11%   |
| Quanta Display          | 6         | 0.11%   |
| GKE                     | 6         | 0.11%   |
| RS                      | 5         | 0.09%   |
| Plain Tree Systems      | 5         | 0.09%   |
| Onkyo                   | 5         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 32        | 0.55%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                         | 25        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 25        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 24        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 24        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 23        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 22        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 21        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 19        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 16        | 0.27%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 16        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 14        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.24%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 13        | 0.22%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 13        | 0.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 13        | 0.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 13        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 13        | 0.22%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 13        | 0.22%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 12        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 12        | 0.21%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 12        | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 12        | 0.21%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 11        | 0.19%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 11        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 11        | 0.19%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 11        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 11        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 11        | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 11        | 0.19%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 11        | 0.19%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 11        | 0.19%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 10        | 0.17%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 10        | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 10        | 0.17%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 10        | 0.17%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                     | 10        | 0.17%   |
| Sharp LCD Monitor SHP14AD 3840x2160 290x170mm 13.2-inch               | 9         | 0.15%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 9         | 0.15%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 9         | 0.15%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 9         | 0.15%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 9         | 0.15%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 9         | 0.15%   |
| BenQ GL2250H BNQ78A1 1920x1080 477x268mm 21.5-inch                    | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch         | 9         | 0.15%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 9         | 0.15%   |
| ___ LCDTV16 ___9000 1360x768                                          | 8         | 0.14%   |
| Toshiba 49UHD_LCD_TV TSB3700 3840x2160 1872x1053mm 84.6-inch          | 8         | 0.14%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 8         | 0.14%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 8         | 0.14%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 8         | 0.14%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 8         | 0.14%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 8         | 0.14%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 8         | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2276      | 41.74%  |
| 1366x768 (WXGA)    | 949       | 17.4%   |
| 3840x2160 (4K)     | 388       | 7.12%   |
| 2560x1440 (QHD)    | 256       | 4.69%   |
| 1280x1024 (SXGA)   | 201       | 3.69%   |
| 1280x800 (WXGA)    | 176       | 3.23%   |
| 1600x900 (HD+)     | 158       | 2.9%    |
| 1440x900 (WXGA+)   | 153       | 2.81%   |
| 1680x1050 (WSXGA+) | 145       | 2.66%   |
| 1920x1200 (WUXGA)  | 113       | 2.07%   |
| Unknown            | 96        | 1.76%   |
| 3440x1440          | 57        | 1.05%   |
| 1360x768           | 50        | 0.92%   |
| 2560x1080          | 44        | 0.81%   |
| 3840x1080          | 39        | 0.72%   |
| 1920x540           | 32        | 0.59%   |
| 2560x1600          | 29        | 0.53%   |
| 1024x768 (XGA)     | 27        | 0.5%    |
| 3200x1800 (QHD+)   | 22        | 0.4%    |
| 3840x2400          | 20        | 0.37%   |
| 1024x600           | 18        | 0.33%   |
| 1600x1200          | 17        | 0.31%   |
| 1280x720 (HD)      | 17        | 0.31%   |
| 2736x1824          | 16        | 0.29%   |
| 2160x1440          | 13        | 0.24%   |
| 2880x1800          | 11        | 0.2%    |
| 2288x1287          | 8         | 0.15%   |
| 800x1280           | 7         | 0.13%   |
| 5760x1080          | 7         | 0.13%   |
| 5120x1440          | 7         | 0.13%   |
| 3840x1200          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 7680x2160          | 4         | 0.07%   |
| 3200x1080          | 4         | 0.07%   |
| 2880x1920          | 4         | 0.07%   |
| 2256x1504          | 4         | 0.07%   |
| 1680x945           | 4         | 0.07%   |
| 5760x2160          | 3         | 0.06%   |
| 4480x1440          | 3         | 0.06%   |
| 3072x1920          | 3         | 0.06%   |
| 1280x768           | 3         | 0.06%   |
| 4480x1080          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3456x2160          | 2         | 0.04%   |
| 3360x1080          | 2         | 0.04%   |
| 3360x1050          | 2         | 0.04%   |
| 3120x1050          | 2         | 0.04%   |
| 3000x2000          | 2         | 0.04%   |
| 2944x1080          | 2         | 0.04%   |
| 2560x1700          | 2         | 0.04%   |
| 2048x1152          | 2         | 0.04%   |
| 2048x1080          | 2         | 0.04%   |
| 1360x765           | 2         | 0.04%   |
| 1280x960           | 2         | 0.04%   |
| 8960x2160          | 1         | 0.02%   |
| 800x480            | 1         | 0.02%   |
| 7680x1440          | 1         | 0.02%   |
| 7680x1080          | 1         | 0.02%   |
| 7280x1440          | 1         | 0.02%   |
| 6720x1050          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1284      | 22.98%  |
| 13      | 521       | 9.32%   |
| 27      | 435       | 7.78%   |
| Unknown | 431       | 7.71%   |
| 24      | 397       | 7.1%    |
| 23      | 352       | 6.3%    |
| 21      | 314       | 5.62%   |
| 14      | 303       | 5.42%   |
| 17      | 291       | 5.21%   |
| 12      | 171       | 3.06%   |
| 19      | 156       | 2.79%   |
| 31      | 98        | 1.75%   |
| 22      | 92        | 1.65%   |
| 11      | 90        | 1.61%   |
| 18      | 76        | 1.36%   |
| 34      | 74        | 1.32%   |
| 84      | 73        | 1.31%   |
| 20      | 58        | 1.04%   |
| 72      | 44        | 0.79%   |
| 26      | 34        | 0.61%   |
| 10      | 33        | 0.59%   |
| 25      | 29        | 0.52%   |
| 54      | 27        | 0.48%   |
| 32      | 23        | 0.41%   |
| 16      | 16        | 0.29%   |
| 33      | 15        | 0.27%   |
| 55      | 13        | 0.23%   |
| 48      | 12        | 0.21%   |
| 40      | 12        | 0.21%   |
| 39      | 12        | 0.21%   |
| 65      | 9         | 0.16%   |
| 46      | 9         | 0.16%   |
| 28      | 9         | 0.16%   |
| 52      | 8         | 0.14%   |
| 43      | 7         | 0.13%   |
| 35      | 7         | 0.13%   |
| 8       | 7         | 0.13%   |
| 60      | 6         | 0.11%   |
| 29      | 6         | 0.11%   |
| 142     | 5         | 0.09%   |
| 47      | 4         | 0.07%   |
| 37      | 4         | 0.07%   |
| 49      | 3         | 0.05%   |
| 42      | 3         | 0.05%   |
| 99      | 2         | 0.04%   |
| 75      | 2         | 0.04%   |
| 57      | 2         | 0.04%   |
| 50      | 2         | 0.04%   |
| 30      | 2         | 0.04%   |
| 86      | 1         | 0.02%   |
| 66      | 1         | 0.02%   |
| 63      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 41      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1854      | 33.63%  |
| 501-600        | 1113      | 20.19%  |
| 201-300        | 616       | 11.17%  |
| 401-500        | 602       | 10.92%  |
| Unknown        | 431       | 7.82%   |
| 351-400        | 335       | 6.08%   |
| 601-700        | 176       | 3.19%   |
| 1501-2000      | 118       | 2.14%   |
| 701-800        | 112       | 2.03%   |
| 1001-1500      | 98        | 1.78%   |
| 801-900        | 34        | 0.62%   |
| 901-1000       | 10        | 0.18%   |
| More than 2000 | 7         | 0.13%   |
| 101-200        | 7         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3716      | 72.13%  |
| 16/10   | 630       | 12.23%  |
| Unknown | 375       | 7.28%   |
| 5/4     | 185       | 3.59%   |
| 21/9    | 88        | 1.71%   |
| 3/2     | 64        | 1.24%   |
| 4/3     | 55        | 1.07%   |
| 32/9    | 13        | 0.25%   |
| 6/5     | 8         | 0.16%   |
| 0.62    | 8         | 0.16%   |
| 1.00    | 7         | 0.14%   |
| 3.20    | 2         | 0.04%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1281      | 23.13%  |
| 201-250        | 927       | 16.74%  |
| 81-90          | 550       | 9.93%   |
| 301-350        | 460       | 8.3%    |
| Unknown        | 431       | 7.78%   |
| 151-200        | 330       | 5.96%   |
| 71-80          | 290       | 5.24%   |
| 351-500        | 224       | 4.04%   |
| More than 1000 | 195       | 3.52%   |
| 121-130        | 158       | 2.85%   |
| 61-70          | 152       | 2.74%   |
| 251-300        | 149       | 2.69%   |
| 141-150        | 140       | 2.53%   |
| 51-60          | 93        | 1.68%   |
| 501-1000       | 63        | 1.14%   |
| 131-140        | 39        | 0.7%    |
| 41-50          | 30        | 0.54%   |
| 111-120        | 14        | 0.25%   |
| 1-40           | 7         | 0.13%   |
| 91-100         | 6         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1748      | 32.35%  |
| 101-120       | 1348      | 24.95%  |
| 121-160       | 1246      | 23.06%  |
| Unknown       | 431       | 7.98%   |
| 161-240       | 327       | 6.05%   |
| 1-50          | 153       | 2.83%   |
| More than 240 | 150       | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4432      | 80.98%  |
| 2     | 692       | 12.64%  |
| 0     | 268       | 4.9%    |
| 3     | 73        | 1.33%   |
| 4     | 7         | 0.13%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2631      | 33.02%  |
| Realtek Semiconductor             | 2609      | 32.75%  |
| Qualcomm Atheros                  | 873       | 10.96%  |
| Broadcom                          | 587       | 7.37%   |
| Ralink Technology                 | 171       | 2.15%   |
| Marvell Technology Group          | 132       | 1.66%   |
| Broadcom Limited                  | 108       | 1.36%   |
| Nvidia                            | 103       | 1.29%   |
| Ralink                            | 95        | 1.19%   |
| TP-Link                           | 80        | 1%      |
| Ericsson Business Mobile Networks | 34        | 0.43%   |
| MediaTek                          | 33        | 0.41%   |
| Dell                              | 33        | 0.41%   |
| DisplayLink                       | 31        | 0.39%   |
| Microsoft                         | 27        | 0.34%   |
| Samsung Electronics               | 24        | 0.3%    |
| Belkin Components                 | 24        | 0.3%    |
| Qualcomm Atheros Communications   | 22        | 0.28%   |
| NetGear                           | 22        | 0.28%   |
| ASIX Electronics                  | 22        | 0.28%   |
| Edimax Technology                 | 21        | 0.26%   |
| Huawei Technologies               | 20        | 0.25%   |
| Lenovo                            | 17        | 0.21%   |
| Hewlett-Packard                   | 16        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 15        | 0.19%   |
| Aquantia                          | 12        | 0.15%   |
| VIA Technologies                  | 10        | 0.13%   |
| Qualcomm                          | 9         | 0.11%   |
| JMicron Technology                | 9         | 0.11%   |
| ASUSTek Computer                  | 9         | 0.11%   |
| D-Link                            | 8         | 0.1%    |
| Xiaomi                            | 7         | 0.09%   |
| Sierra Wireless                   | 7         | 0.09%   |
| Microchip Technology              | 7         | 0.09%   |
| Mellanox Technologies             | 7         | 0.09%   |
| Apple                             | 7         | 0.09%   |
| D-Link System                     | 6         | 0.08%   |
| Motorola PCS                      | 5         | 0.06%   |
| Micro Star International          | 5         | 0.06%   |
| Attansic Technology               | 5         | 0.06%   |
| Arduino SA                        | 5         | 0.06%   |
| ZyDAS                             | 4         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.05%   |
| OPPO Electronics                  | 4         | 0.05%   |
| Linksys                           | 4         | 0.05%   |
| IMC Networks                      | 4         | 0.05%   |
| ICS Advent                        | 4         | 0.05%   |
| 3Com                              | 4         | 0.05%   |
| TRENDnet                          | 3         | 0.04%   |
| Texas Instruments                 | 3         | 0.04%   |
| T & A Mobile Phones               | 3         | 0.04%   |
| Sitecom Europe                    | 3         | 0.04%   |
| QLogic                            | 3         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.04%   |
| Oculus VR                         | 3         | 0.04%   |
| Google                            | 3         | 0.04%   |
| Wacom                             | 2         | 0.03%   |
| U-Blox                            | 2         | 0.03%   |
| Standard Microsystems             | 2         | 0.03%   |
| Seeed Technology                  | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1733      | 18.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 330       | 3.5%    |
| Intel Wi-Fi 6 AX200                                                     | 252       | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 235       | 2.49%   |
| Intel I211 Gigabit Network Connection                                   | 187       | 1.98%   |
| Intel Wireless 8265 / 8275                                              | 147       | 1.56%   |
| Intel Wireless 7260                                                     | 134       | 1.42%   |
| Intel Wireless 7265                                                     | 128       | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 120       | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 118       | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 117       | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 110       | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                    | 97        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 94        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 91        | 0.96%   |
| Intel Wireless 8260                                                     | 91        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 0.94%   |
| Intel Wireless 3165                                                     | 88        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                       | 82        | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 76        | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 75        | 0.8%    |
| Intel Wireless-AC 9260                                                  | 75        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 74        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 61        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                 | 61        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 61        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                    | 58        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                         | 57        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 57        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 55        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 55        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 54        | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 51        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 50        | 0.53%   |
| Intel Ethernet Connection I218-LM                                       | 49        | 0.52%   |
| Realtek 802.11ac NIC                                                    | 48        | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 46        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 46        | 0.49%   |
| Ralink RT5370 Wireless Adapter                                          | 44        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 44        | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.47%   |
| Intel Wireless 3160                                                     | 44        | 0.47%   |
| Intel WiFi Link 5100                                                    | 43        | 0.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 43        | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                                   | 41        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 40        | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 0.42%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 0.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 38        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 37        | 0.39%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 36        | 0.38%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 36        | 0.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 35        | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 35        | 0.37%   |
| Intel Ethernet Connection I217-V                                        | 35        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1864      | 43.33%  |
| Qualcomm Atheros                | 703       | 16.34%  |
| Realtek Semiconductor           | 702       | 16.32%  |
| Broadcom                        | 367       | 8.53%   |
| Ralink Technology               | 171       | 3.97%   |
| Ralink                          | 94        | 2.19%   |
| Broadcom Limited                | 76        | 1.77%   |
| TP-Link                         | 75        | 1.74%   |
| Microsoft                       | 26        | 0.6%    |
| MediaTek                        | 24        | 0.56%   |
| Belkin Components               | 24        | 0.56%   |
| Qualcomm Atheros Communications | 22        | 0.51%   |
| NetGear                         | 22        | 0.51%   |
| Marvell Technology Group        | 21        | 0.49%   |
| Edimax Technology               | 21        | 0.49%   |
| Dell                            | 18        | 0.42%   |
| D-Link                          | 8         | 0.19%   |
| ASUSTek Computer                | 8         | 0.19%   |
| Sierra Wireless                 | 7         | 0.16%   |
| Micro Star International        | 5         | 0.12%   |
| D-Link System                   | 5         | 0.12%   |
| ZyDAS                           | 4         | 0.09%   |
| Qualcomm                        | 4         | 0.09%   |
| IMC Networks                    | 4         | 0.09%   |
| TRENDnet                        | 3         | 0.07%   |
| Sitecom Europe                  | 3         | 0.07%   |
| Linksys                         | 3         | 0.07%   |
| Wacom                           | 2         | 0.05%   |
| Gemtek                          | 2         | 0.05%   |
| Wilocity                        | 1         | 0.02%   |
| Texas Instruments               | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| Samsung Electronics             | 1         | 0.02%   |
| Philips (or NXP)                | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Hewlett-Packard                 | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fibocom                         | 1         | 0.02%   |
| CyberTAN Technology             | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |
| Apple                           | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |
| 3Com                            | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 252       | 5.8%    |
| Intel Wireless 8265 / 8275                                              | 147       | 3.39%   |
| Intel Wireless 7260                                                     | 134       | 3.09%   |
| Intel Wireless 7265                                                     | 128       | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 120       | 2.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 118       | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 110       | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 94        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 91        | 2.1%    |
| Intel Wireless 8260                                                     | 91        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 2.05%   |
| Intel Wireless 3165                                                     | 88        | 2.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 75        | 1.73%   |
| Intel Wireless-AC 9260                                                  | 75        | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 74        | 1.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 61        | 1.4%    |
| Ralink MT7601U Wireless Adapter                                         | 57        | 1.31%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 55        | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 55        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 54        | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 51        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 50        | 1.15%   |
| Realtek 802.11ac NIC                                                    | 48        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 46        | 1.06%   |
| Ralink RT5370 Wireless Adapter                                          | 44        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 1.01%   |
| Intel Wireless 3160                                                     | 44        | 1.01%   |
| Intel WiFi Link 5100                                                    | 43        | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 43        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 40        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 38        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 36        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 35        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 35        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 30        | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 29        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 29        | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 27        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 27        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 27        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.62%   |
| Intel Centrino Wireless-N 2230                                          | 27        | 0.62%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 25        | 0.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 25        | 0.58%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 24        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.53%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 23        | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 22        | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 22        | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 22        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 21        | 0.48%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 20        | 0.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 20        | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2319      | 47.74%  |
| Intel                                  | 1486      | 30.59%  |
| Broadcom                               | 310       | 6.38%   |
| Qualcomm Atheros                       | 246       | 5.06%   |
| Marvell Technology Group               | 111       | 2.28%   |
| Nvidia                                 | 103       | 2.12%   |
| Broadcom Limited                       | 35        | 0.72%   |
| DisplayLink                            | 31        | 0.64%   |
| Samsung Electronics                    | 23        | 0.47%   |
| ASIX Electronics                       | 22        | 0.45%   |
| Lenovo                                 | 16        | 0.33%   |
| Huawei Technologies                    | 16        | 0.33%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.29%   |
| Aquantia                               | 12        | 0.25%   |
| VIA Technologies                       | 10        | 0.21%   |
| MediaTek                               | 9         | 0.19%   |
| JMicron Technology                     | 9         | 0.19%   |
| Xiaomi                                 | 7         | 0.14%   |
| Microchip Technology                   | 7         | 0.14%   |
| Mellanox Technologies                  | 6         | 0.12%   |
| TP-Link                                | 5         | 0.1%    |
| Qualcomm                               | 5         | 0.1%    |
| Motorola PCS                           | 5         | 0.1%    |
| Attansic Technology                    | 5         | 0.1%    |
| Apple                                  | 5         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 4         | 0.08%   |
| OPPO Electronics                       | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| T & A Mobile Phones                    | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| Google                                 | 3         | 0.06%   |
| 3Com                                   | 3         | 0.06%   |
| Standard Microsystems                  | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| SysKonnect                             | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| Emulex                                 | 1         | 0.02%   |
| D-Link System                          | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1733      | 34.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 330       | 6.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 235       | 4.73%   |
| Intel I211 Gigabit Network Connection                             | 187       | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 117       | 2.36%   |
| Intel Ethernet Connection (2) I219-V                              | 97        | 1.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 1.65%   |
| Intel Ethernet Connection I217-LM                                 | 76        | 1.53%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 61        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 58        | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 49        | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 46        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 44        | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 41        | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 40        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37        | 0.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 36        | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 35        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 33        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 32        | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 31        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 29        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 28        | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 28        | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 27        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 24        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 23        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 23        | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19        | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.38%   |
| Intel 82562V-2 10/100 Network Connection                          | 18        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17        | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 16        | 0.32%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.3%    |
| Intel 82578DM Gigabit Network Connection                          | 15        | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.28%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.28%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.28%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.26%   |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 12        | 0.24%   |
| Huawei COL-L29                                                    | 12        | 0.24%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 11        | 0.22%   |
| Intel I350 Gigabit Network Connection                             | 11        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4589      | 52.6%   |
| WiFi     | 4010      | 45.96%  |
| Modem    | 111       | 1.27%   |
| Unknown  | 15        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3130      | 56.7%   |
| Ethernet | 2387      | 43.24%  |
| Modem    | 2         | 0.04%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2884      | 53.61%  |
| 1     | 2171      | 40.35%  |
| 0     | 155       | 2.88%   |
| 3     | 120       | 2.23%   |
| 4     | 31        | 0.58%   |
| 5     | 15        | 0.28%   |
| 6     | 3         | 0.06%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4893      | 90.39%  |
| Yes  | 520       | 9.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1386      | 45.58%  |
| Cambridge Silicon Radio         | 253       | 8.32%   |
| Qualcomm Atheros Communications | 247       | 8.12%   |
| Realtek Semiconductor           | 231       | 7.6%    |
| Broadcom                        | 221       | 7.27%   |
| Apple                           | 145       | 4.77%   |
| IMC Networks                    | 81        | 2.66%   |
| Lite-On Technology              | 78        | 2.56%   |
| Foxconn / Hon Hai               | 67        | 2.2%    |
| Dell                            | 67        | 2.2%    |
| ASUSTek Computer                | 61        | 2.01%   |
| Toshiba                         | 38        | 1.25%   |
| Hewlett-Packard                 | 37        | 1.22%   |
| Marvell Semiconductor           | 21        | 0.69%   |
| Realtek                         | 16        | 0.53%   |
| Alps Electric                   | 16        | 0.53%   |
| Belkin Components               | 14        | 0.46%   |
| Foxconn International           | 12        | 0.39%   |
| Ralink                          | 8         | 0.26%   |
| Integrated System Solution      | 8         | 0.26%   |
| Askey Computer                  | 6         | 0.2%    |
| Taiyo Yuden                     | 5         | 0.16%   |
| Ralink Technology               | 5         | 0.16%   |
| Logitech                        | 3         | 0.1%    |
| HTC (High Tech Computer)        | 3         | 0.1%    |
| TP-Link                         | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| MediaTek                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 591       | 19.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 253       | 8.32%   |
| Intel AX200 Bluetooth                               | 231       | 7.59%   |
| Intel Bluetooth Device                              | 175       | 5.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 160       | 5.26%   |
| Realtek Bluetooth Radio                             | 128       | 4.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 90        | 2.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 68        | 2.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 66        | 2.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 61        | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 57        | 1.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 56        | 1.84%   |
| Apple Bluetooth Host Controller                     | 54        | 1.78%   |
| Apple Bluetooth USB Host Controller                 | 53        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 52        | 1.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 42        | 1.38%   |
| Intel AX210 Bluetooth                               | 35        | 1.15%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 33        | 1.08%   |
| IMC Networks Bluetooth Radio                        | 33        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 0.89%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.79%   |
| IMC Networks Bluetooth Device                       | 23        | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite        | 19        | 0.62%   |
| Lite-On Bluetooth Device                            | 18        | 0.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 0.59%   |
| Apple Bluetooth HCI                                 | 17        | 0.56%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.53%   |
| Realtek Bluetooth Radio                             | 16        | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.43%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.39%   |
| Toshiba Bluetooth Device                            | 11        | 0.36%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 11        | 0.36%   |
| Dell Wireless 365 Bluetooth                         | 10        | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 0.3%    |
| IMC Networks Wireless_Device                        | 9         | 0.3%    |
| Ralink RT3290 Bluetooth                             | 8         | 0.26%   |
| Broadcom BCM43142A0 Bluetooth Device                | 8         | 0.26%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 0.26%   |
| Toshiba Integrated Bluetooth HCI                    | 7         | 0.23%   |
| Toshiba Atheros AR3012 Bluetooth                    | 7         | 0.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 7         | 0.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 7         | 0.23%   |
| Dell Wireless 370 Bluetooth Mini-card               | 7         | 0.23%   |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 0.23%   |
| Alps Electric BCM2046 Bluetooth Device              | 7         | 0.23%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 6         | 0.2%    |
| Belkin Components Bluetooth Mini Dongle             | 6         | 0.2%    |
| ASUS Qualcomm Bluetooth 4.1                         | 6         | 0.2%    |
| ASUS Bluetooth Radio                                | 6         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3717      | 50.49%  |
| AMD                                  | 1507      | 20.47%  |
| Nvidia                               | 1323      | 17.97%  |
| C-Media Electronics                  | 134       | 1.82%   |
| Creative Labs                        | 72        | 0.98%   |
| Texas Instruments                    | 40        | 0.54%   |
| Logitech                             | 39        | 0.53%   |
| JMTek                                | 27        | 0.37%   |
| Focusrite-Novation                   | 25        | 0.34%   |
| Creative Technology                  | 25        | 0.34%   |
| Realtek Semiconductor                | 23        | 0.31%   |
| Plantronics                          | 22        | 0.3%    |
| SteelSeries ApS                      | 21        | 0.29%   |
| GN Netcom                            | 20        | 0.27%   |
| Razer USA                            | 19        | 0.26%   |
| VIA Technologies                     | 17        | 0.23%   |
| Corsair                              | 17        | 0.23%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.2%    |
| Blue Microphones                     | 15        | 0.2%    |
| Kingston Technology                  | 14        | 0.19%   |
| ASUSTek Computer                     | 13        | 0.18%   |
| Generalplus Technology               | 12        | 0.16%   |
| Sennheiser Communications            | 10        | 0.14%   |
| Dell                                 | 10        | 0.14%   |
| Micro Star International             | 9         | 0.12%   |
| Lenovo                               | 9         | 0.12%   |
| ATI Technologies                     | 8         | 0.11%   |
| Apple                                | 8         | 0.11%   |
| AKAI Professional M.I.               | 8         | 0.11%   |
| Tenx Technology                      | 7         | 0.1%    |
| Sony                                 | 7         | 0.1%    |
| GYROCOM C&C                          | 7         | 0.1%    |
| Conexant Systems                     | 6         | 0.08%   |
| BEHRINGER International              | 6         | 0.08%   |
| XMOS                                 | 5         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.07%   |
| Yamaha                               | 4         | 0.05%   |
| Samson Technologies                  | 4         | 0.05%   |
| Microsoft                            | 4         | 0.05%   |
| M-Audio                              | 4         | 0.05%   |
| Hewlett-Packard                      | 4         | 0.05%   |
| Elgato Systems                       | 4         | 0.05%   |
| Alesis                               | 4         | 0.05%   |
| Valve Software                       | 3         | 0.04%   |
| Unknown                              | 3         | 0.04%   |
| Turtle Beach                         | 3         | 0.04%   |
| Samsung Electronics                  | 3         | 0.04%   |
| Nektar                               | 3         | 0.04%   |
| Native Instruments                   | 3         | 0.04%   |
| Elite Silicon                        | 3         | 0.04%   |
| EGO SYStems                          | 3         | 0.04%   |
| DigiTech                             | 3         | 0.04%   |
| Cambridge Audio                      | 3         | 0.04%   |
| AudioQuest                           | 3         | 0.04%   |
| Astro Gaming                         | 3         | 0.04%   |
| Asahi Kasei Microsystems             | 3         | 0.04%   |
| Toshiba                              | 2         | 0.03%   |
| RODE Microphones                     | 2         | 0.03%   |
| QinHeng Electronics                  | 2         | 0.03%   |
| KORG                                 | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 379       | 4.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 376       | 4.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 356       | 4.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 264       | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 257       | 2.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 243       | 2.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 233       | 2.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 233       | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 203       | 2.34%   |
| AMD FCH Azalia Controller                                                                         | 202       | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 198       | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 197       | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 147       | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 141       | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 137       | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 133       | 1.53%   |
| Intel 8 Series HD Audio Controller                                                                | 124       | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 124       | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 122       | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 119       | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 114       | 1.31%   |
| Intel 200 Series PCH HD Audio                                                                     | 106       | 1.22%   |
| Intel Broadwell-U Audio Controller                                                                | 104       | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 101       | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 99        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 97        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 96        | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 86        | 0.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 86        | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 86        | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 83        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 83        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 80        | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 77        | 0.89%   |
| Nvidia High Definition Audio Controller                                                           | 69        | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 66        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 66        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 66        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 63        | 0.73%   |
| Intel CM238 HD Audio Controller                                                                   | 63        | 0.73%   |
| AMD High Definition Audio Controller                                                              | 63        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 59        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 57        | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 57        | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 55        | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 55        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 54        | 0.62%   |
| AMD Navi 10 HDMI Audio                                                                            | 51        | 0.59%   |
| Nvidia MCP61 High Definition Audio                                                                | 50        | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 50        | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 50        | 0.58%   |
| AMD Trinity HDMI Audio Controller                                                                 | 50        | 0.58%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 49        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 48        | 0.55%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 47        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 45        | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 44        | 0.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 44        | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 40        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 534       | 19.52%  |
| SK hynix                     | 468       | 17.11%  |
| Corsair                      | 335       | 12.24%  |
| Unknown                      | 281       | 10.27%  |
| Micron Technology            | 274       | 10.01%  |
| Crucial                      | 263       | 9.61%   |
| Kingston                     | 249       | 9.1%    |
| Ramaxel Technology           | 42        | 1.54%   |
| Elpida                       | 37        | 1.35%   |
| Nanya Technology             | 35        | 1.28%   |
| A-DATA Technology            | 33        | 1.21%   |
| G.Skill                      | 28        | 1.02%   |
| Team                         | 22        | 0.8%    |
| Unknown (ABCD)               | 20        | 0.73%   |
| Patriot                      | 13        | 0.48%   |
| Transcend                    | 8         | 0.29%   |
| Qimonda                      | 8         | 0.29%   |
| ASint Technology             | 7         | 0.26%   |
| Hewlett-Packard              | 6         | 0.22%   |
| A Force                      | 6         | 0.22%   |
| Goodram                      | 5         | 0.18%   |
| Unknown                      | 5         | 0.18%   |
| Apacer                       | 4         | 0.15%   |
| Toshiba                      | 3         | 0.11%   |
| KLEVV                        | 3         | 0.11%   |
| Axiom                        | 3         | 0.11%   |
| Unknown (F301)               | 2         | 0.07%   |
| Unknown (0x0702)             | 2         | 0.07%   |
| Timetec                      | 2         | 0.07%   |
| Infineon                     | 2         | 0.07%   |
| GSkill                       | 2         | 0.07%   |
| CSX                          | 2         | 0.07%   |
| Avant                        | 2         | 0.07%   |
| ATP                          | 2         | 0.07%   |
| Wilk Elektronik              | 1         | 0.04%   |
| V-Color                      | 1         | 0.04%   |
| Uroad                        | 1         | 0.04%   |
| Unknown (0x4000000000000000) | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Undefined-000B               | 1         | 0.04%   |
| Thermaltake                  | 1         | 0.04%   |
| Smart                        | 1         | 0.04%   |
| Silicon Power                | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Ramos Technology             | 1         | 0.04%   |
| ProMos                       | 1         | 0.04%   |
| Princeton                    | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| OnBoard                      | 1         | 0.04%   |
| OCZ                          | 1         | 0.04%   |
| Miron                        | 1         | 0.04%   |
| Memox                        | 1         | 0.04%   |
| Lexar Co Limited             | 1         | 0.04%   |
| KETECH                       | 1         | 0.04%   |
| J&A Information              | 1         | 0.04%   |
| HPE                          | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| GeIL                         | 1         | 0.04%   |
| Essencore                    | 1         | 0.04%   |
| ChangXin Memory              | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 34        | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 24        | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 24        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 21        | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 21        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 19        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 18        | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 17        | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 16        | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 16        | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 15        | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 14        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 14        | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s            | 14        | 0.47%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s               | 14        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 13        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 13        | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 13        | 0.44%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s              | 13        | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 12        | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 12        | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 12        | 0.4%    |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s          | 12        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 11        | 0.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 11        | 0.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 10        | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 10        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 10        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 10        | 0.34%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 10        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 10        | 0.34%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s                 | 10        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 9         | 0.3%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 9         | 0.3%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 9         | 0.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 8         | 0.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.27%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.27%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 7         | 0.24%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 7         | 0.24%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 7         | 0.24%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.24%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 7         | 0.24%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 7         | 0.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 7         | 0.24%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 7         | 0.24%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s               | 7         | 0.24%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 6         | 0.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 6         | 0.2%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 6         | 0.2%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 6         | 0.2%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 6         | 0.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 6         | 0.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 6         | 0.2%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 0.2%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 6         | 0.2%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 6         | 0.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1046      | 44.02%  |
| DDR3    | 832       | 35.02%  |
| DDR2    | 145       | 6.1%    |
| LPDDR3  | 87        | 3.66%   |
| Unknown | 86        | 3.62%   |
| LPDDR4  | 77        | 3.24%   |
| SDRAM   | 72        | 3.03%   |
| DDR     | 23        | 0.97%   |
| DRAM    | 8         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1217      | 51.96%  |
| DIMM         | 934       | 39.88%  |
| Row Of Chips | 157       | 6.7%    |
| Chip         | 16        | 0.68%   |
| Unknown      | 9         | 0.38%   |
| RIMM         | 6         | 0.26%   |
| FB-DIMM      | 3         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 922       | 35.79%  |
| 4096   | 756       | 29.35%  |
| 2048   | 353       | 13.7%   |
| 16384  | 348       | 13.51%  |
| 1024   | 121       | 4.7%    |
| 32768  | 56        | 2.17%   |
| 512    | 16        | 0.62%   |
| 131072 | 1         | 0.04%   |
| 256    | 1         | 0.04%   |
| 16     | 1         | 0.04%   |
| 13     | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 551       | 21.3%   |
| 2667    | 357       | 13.8%   |
| 3200    | 266       | 10.28%  |
| 1333    | 210       | 8.12%   |
| 2400    | 207       | 8%      |
| 2133    | 143       | 5.53%   |
| 667     | 86        | 3.32%   |
| 3600    | 79        | 3.05%   |
| 1867    | 73        | 2.82%   |
| 1334    | 65        | 2.51%   |
| 800     | 64        | 2.47%   |
| Unknown | 51        | 1.97%   |
| 4267    | 35        | 1.35%   |
| 1067    | 35        | 1.35%   |
| 3266    | 29        | 1.12%   |
| 3000    | 29        | 1.12%   |
| 2048    | 26        | 1.01%   |
| 1066    | 26        | 1.01%   |
| 1866    | 18        | 0.7%    |
| 3400    | 17        | 0.66%   |
| 2666    | 17        | 0.66%   |
| 533     | 17        | 0.66%   |
| 4199    | 16        | 0.62%   |
| 3466    | 16        | 0.62%   |
| 3733    | 15        | 0.58%   |
| 2800    | 15        | 0.58%   |
| 400     | 15        | 0.58%   |
| 2933    | 12        | 0.46%   |
| 1800    | 11        | 0.43%   |
| 975     | 10        | 0.39%   |
| 49926   | 5         | 0.19%   |
| 4266    | 5         | 0.19%   |
| 3100    | 5         | 0.19%   |
| 1639    | 5         | 0.19%   |
| 3800    | 4         | 0.15%   |
| 2000    | 4         | 0.15%   |
| 4800    | 3         | 0.12%   |
| 3533    | 3         | 0.12%   |
| 3007    | 3         | 0.12%   |
| 2733    | 3         | 0.12%   |
| 2200    | 3         | 0.12%   |
| 933     | 3         | 0.12%   |
| 333     | 3         | 0.12%   |
| 4000    | 2         | 0.08%   |
| 3334    | 2         | 0.08%   |
| 3067    | 2         | 0.08%   |
| 3066    | 2         | 0.08%   |
| 3020    | 2         | 0.08%   |
| 2134    | 2         | 0.08%   |
| 8400    | 1         | 0.04%   |
| 3500    | 1         | 0.04%   |
| 3333    | 1         | 0.04%   |
| 2802    | 1         | 0.04%   |
| 2747    | 1         | 0.04%   |
| 2465    | 1         | 0.04%   |
| 2132    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1648    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 1367    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 57        | 42.22%  |
| Canon                 | 23        | 17.04%  |
| Seiko Epson           | 14        | 10.37%  |
| Samsung Electronics   | 12        | 8.89%   |
| Brother Industries    | 10        | 7.41%   |
| Prolific Technology   | 5         | 3.7%    |
| STMicroelectronics    | 2         | 1.48%   |
| Oki Data              | 2         | 1.48%   |
| Lexmark International | 2         | 1.48%   |
| Kyocera               | 2         | 1.48%   |
| Seiko Instruments     | 1         | 0.74%   |
| Ricoh                 | 1         | 0.74%   |
| QinHeng Electronics   | 1         | 0.74%   |
| Dymo-CoStar           | 1         | 0.74%   |
| Dell                  | 1         | 0.74%   |
| Apple                 | 1         | 0.74%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 6         | 4.38%   |
| Prolific PL2305 Parallel Port                             | 5         | 3.65%   |
| HP ENVY 5000 series                                       | 5         | 3.65%   |
| HP ENVY 4520 series                                       | 5         | 3.65%   |
| Canon PIXMA MG2500 Series                                 | 5         | 3.65%   |
| HP DeskJet 2620 All-in-One Printer                        | 4         | 2.92%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.46%   |
| Seiko Epson XP-243 245 247 Series                         | 2         | 1.46%   |
| Seiko Epson XP-202 203 206 Series                         | 2         | 1.46%   |
| Samsung ML-2250 Series                                    | 2         | 1.46%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.46%   |
| Samsung C43x Series                                       | 2         | 1.46%   |
| Oki Data USB Device                                       | 2         | 1.46%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.46%   |
| HP Deskjet F2280 series                                   | 2         | 1.46%   |
| HP DeskJet 3630 series                                    | 2         | 1.46%   |
| HP Deskjet 2540 series                                    | 2         | 1.46%   |
| HP DeskJet 2130 series                                    | 2         | 1.46%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.46%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.46%   |
| Canon PIXMA MP495                                         | 2         | 1.46%   |
| Canon MG5700 series                                       | 2         | 1.46%   |
| Canon LiDE 300                                            | 2         | 1.46%   |
| Canon iP7200 series                                       | 2         | 1.46%   |
| Brother HL-3140CW series                                  | 2         | 1.46%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.46%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.73%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.73%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.73%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.73%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.73%   |
| Seiko Epson L355 Series                                   | 1         | 0.73%   |
| Samsung SCX-4300 Series                                   | 1         | 0.73%   |
| Samsung ML-1865                                           | 1         | 0.73%   |
| Samsung M2020 Series                                      | 1         | 0.73%   |
| Samsung CLX-6260 Series                                   | 1         | 0.73%   |
| Samsung CLP-300 Series                                    | 1         | 0.73%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 1         | 0.73%   |
| Ricoh SP C260SFNw                                         | 1         | 0.73%   |
| QinHeng CH340S                                            | 1         | 0.73%   |
| Lexmark International MS610de                             | 1         | 0.73%   |
| Lexmark International C544                                | 1         | 0.73%   |
| Kyocera FS-1320D Printer                                  | 1         | 0.73%   |
| Kyocera FS-1041                                           | 1         | 0.73%   |
| HP PhotoSmart 130                                         | 1         | 0.73%   |
| HP OfficeJet Pro 7720 series                              | 1         | 0.73%   |
| HP OfficeJet Pro 6960                                     | 1         | 0.73%   |
| HP OfficeJet 5200 series                                  | 1         | 0.73%   |
| HP Officejet 4630 series                                  | 1         | 0.73%   |
| HP Officejet 4620 series                                  | 1         | 0.73%   |
| HP Officejet 4500 G510n-z                                 | 1         | 0.73%   |
| HP LaserJet Professional P 1102w                          | 1         | 0.73%   |
| HP LaserJet Pro M201dw                                    | 1         | 0.73%   |
| HP LaserJet Pro M148f-M149f                               | 1         | 0.73%   |
| HP LaserJet P2035                                         | 1         | 0.73%   |
| HP LaserJet P2015 series                                  | 1         | 0.73%   |
| HP LaserJet P1005                                         | 1         | 0.73%   |
| HP LaserJet 3050                                          | 1         | 0.73%   |
| HP LaserJet 2300d                                         | 1         | 0.73%   |
| HP LaserJet 1320                                          | 1         | 0.73%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 21        | 60%     |
| Seiko Epson        | 8         | 22.86%  |
| Ultima Electronics | 2         | 5.71%   |
| Hewlett-Packard    | 2         | 5.71%   |
| Mustek Systems     | 1         | 2.86%   |
| AGFA-Gevaert NV    | 1         | 2.86%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 4         | 11.43%  |
| Canon CanoScan LiDE 220                                                               | 4         | 11.43%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 8.57%   |
| Canon CanoScan LiDE 110                                                               | 3         | 8.57%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5.71%   |
| Seiko Epson Scanner                                                                   | 2         | 5.71%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 5.71%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.86%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.86%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.86%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.86%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.86%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.86%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.86%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.86%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.86%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.86%   |
| Canon CanoScan LiDE 210                                                               | 1         | 2.86%   |
| Canon CanoScan LiDE 200                                                               | 1         | 2.86%   |
| Canon CanoScan LiDE 100                                                               | 1         | 2.86%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.86%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.86%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 665       | 21.96%  |
| Microdia                               | 313       | 10.34%  |
| Realtek Semiconductor                  | 248       | 8.19%   |
| Logitech                               | 203       | 6.7%    |
| IMC Networks                           | 197       | 6.51%   |
| Acer                                   | 174       | 5.75%   |
| Sunplus Innovation Technology          | 147       | 4.85%   |
| Apple                                  | 119       | 3.93%   |
| Cheng Uei Precision Industry (Foxlink) | 113       | 3.73%   |
| Suyin                                  | 100       | 3.3%    |
| Quanta                                 | 86        | 2.84%   |
| Lite-On Technology                     | 67        | 2.21%   |
| Syntek                                 | 58        | 1.92%   |
| Microsoft                              | 58        | 1.92%   |
| Silicon Motion                         | 50        | 1.65%   |
| Alcor Micro                            | 45        | 1.49%   |
| Ricoh                                  | 41        | 1.35%   |
| Samsung Electronics                    | 36        | 1.19%   |
| Lenovo                                 | 30        | 0.99%   |
| Z-Star Microelectronics                | 22        | 0.73%   |
| Generalplus Technology                 | 21        | 0.69%   |
| ARC International                      | 19        | 0.63%   |
| GEMBIRD                                | 17        | 0.56%   |
| Creative Technology                    | 12        | 0.4%    |
| Primax Electronics                     | 11        | 0.36%   |
| Luxvisions Innotech Limited            | 11        | 0.36%   |
| MacroSilicon                           | 10        | 0.33%   |
| Aveo Technology                        | 10        | 0.33%   |
| ALi                                    | 10        | 0.33%   |
| Razer USA                              | 9         | 0.3%    |
| Unknown                                | 6         | 0.2%    |
| Sunplus Technology                     | 6         | 0.2%    |
| Sonix Technology                       | 6         | 0.2%    |
| OmniVision Technologies                | 6         | 0.2%    |
| Importek                               | 6         | 0.2%    |
| Huawei Technologies                    | 6         | 0.2%    |
| Genesys Logic                          | 6         | 0.2%    |
| DigiTech                               | 5         | 0.17%   |
| Tobii Technology AB                    | 4         | 0.13%   |
| SunplusIT                              | 4         | 0.13%   |
| Hewlett-Packard                        | 4         | 0.13%   |
| Arkmicro Technologies                  | 4         | 0.13%   |
| 2M UVC CAMERA                          | 4         | 0.13%   |
| WCM_USB                                | 3         | 0.1%    |
| WaveRider Communications               | 3         | 0.1%    |
| Pixart Imaging                         | 3         | 0.1%    |
| Leap Motion                            | 3         | 0.1%    |
| Intel                                  | 3         | 0.1%    |
| Google                                 | 3         | 0.1%    |
| Foxconn / Hon Hai                      | 3         | 0.1%    |
| Valve Software                         | 2         | 0.07%   |
| Trust                                  | 2         | 0.07%   |
| Nokia Mobile Phones                    | 2         | 0.07%   |
| KYE Systems (Mouse Systems)            | 2         | 0.07%   |
| Jieli Technology                       | 2         | 0.07%   |
| GenesysLogic Technology                | 2         | 0.07%   |
| Cubeternet                             | 2         | 0.07%   |
| AVerMedia Technologies                 | 2         | 0.07%   |
| Alpha Imaging Technology               | 2         | 0.07%   |
| YGTek                                  | 1         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 137       | 4.48%   |
| Chicony Integrated Camera                                      | 109       | 3.57%   |
| Realtek Integrated_Webcam_HD                                   | 75        | 2.45%   |
| Logitech HD Pro Webcam C920                                    | 62        | 2.03%   |
| IMC Networks Integrated Camera                                 | 58        | 1.9%    |
| Chicony HD WebCam                                              | 55        | 1.8%    |
| Sunplus Integrated_Webcam_HD                                   | 43        | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 42        | 1.37%   |
| Chicony TOSHIBA Web Camera - HD                                | 42        | 1.37%   |
| Logitech Webcam C270                                           | 39        | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 36        | 1.18%   |
| Apple FaceTime HD Camera (Built-in)                            | 36        | 1.18%   |
| Apple Built-in iSight                                          | 36        | 1.18%   |
| Acer Integrated Camera                                         | 34        | 1.11%   |
| Realtek USB Camera                                             | 33        | 1.08%   |
| Microdia Integrated Webcam                                     | 30        | 0.98%   |
| Chicony USB2.0 Camera                                          | 30        | 0.98%   |
| Lite-On Integrated Camera                                      | 28        | 0.92%   |
| Microdia Webcam Vitade AF                                      | 27        | 0.88%   |
| Chicony USB 2.0 Camera                                         | 27        | 0.88%   |
| Chicony HP Truevision HD camera                                | 26        | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 26        | 0.85%   |
| Microsoft LifeCam HD-3000                                      | 22        | 0.72%   |
| Chicony HP Truevision HD                                       | 21        | 0.69%   |
| Chicony EasyCamera                                             | 21        | 0.69%   |
| Alcor Micro USB 2.0 Camera                                     | 21        | 0.69%   |
| Microsoft LifeCam Cinema                                       | 20        | 0.65%   |
| Chicony VGA Webcam                                             | 20        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 20        | 0.65%   |
| Acer Lenovo EasyCamera                                         | 20        | 0.65%   |
| Syntek Lenovo EasyCamera                                       | 19        | 0.62%   |
| ARC International Camera                                       | 19        | 0.62%   |
| Apple FaceTime HD Camera                                       | 19        | 0.62%   |
| Acer SunplusIT Integrated Camera                               | 19        | 0.62%   |
| Chicony HP HD Camera                                           | 18        | 0.59%   |
| Acer BisonCam,NB Pro                                           | 18        | 0.59%   |
| Syntek Integrated Camera                                       | 17        | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 17        | 0.56%   |
| Microdia USB 2.0 Camera                                        | 16        | 0.52%   |
| Lenovo Integrated Webcam [R5U877]                              | 16        | 0.52%   |
| Chicony Integrated Camera (1280x720@30)                        | 16        | 0.52%   |
| Chicony CNF9055 Toshiba Webcam                                 | 16        | 0.52%   |
| Syntek EasyCamera                                              | 15        | 0.49%   |
| Quanta HD User Facing                                          | 15        | 0.49%   |
| Chicony HP Wide Vision HD Camera                               | 15        | 0.49%   |
| Suyin HP Truevision HD                                         | 14        | 0.46%   |
| Realtek Integrated Webcam HD                                   | 14        | 0.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 14        | 0.46%   |
| Acer EasyCamera                                                | 14        | 0.46%   |
| Realtek Integrated Webcam                                      | 13        | 0.43%   |
| Chicony HP HD Webcam                                           | 13        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 13        | 0.43%   |
| Realtek FULL HD 1080P Webcam                                   | 12        | 0.39%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 12        | 0.39%   |
| Microdia Integrated Webcam HD                                  | 12        | 0.39%   |
| Chicony Lenovo EasyCamera                                      | 12        | 0.39%   |
| Acer BisonCam, NB Pro                                          | 12        | 0.39%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 11        | 0.36%   |
| Chicony HP Webcam                                              | 11        | 0.36%   |
| Chicony HD User Facing                                         | 11        | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 170       | 32.38%  |
| Synaptics                  | 137       | 26.1%   |
| Shenzhen Goodix Technology | 75        | 14.29%  |
| AuthenTec                  | 40        | 7.62%   |
| Upek                       | 37        | 7.05%   |
| LighTuning Technology      | 25        | 4.76%   |
| Elan Microelectronics      | 24        | 4.57%   |
| STMicroelectronics         | 14        | 2.67%   |
| Samsung Electronics        | 1         | 0.19%   |
| HOLTEK                     | 1         | 0.19%   |
| Focal-systems.Corp         | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 41        | 7.81%   |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 7.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 6.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 6.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 5.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 4%      |
| Elan ELAN:Fingerprint                                                      | 21        | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 3.62%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 3.62%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 3.05%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.48%   |
| Synaptics  WBDI                                                            | 13        | 2.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.29%   |
| Validity Sensors VFS491                                                    | 11        | 2.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 11        | 2.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.71%   |
| AuthenTec AES2810                                                          | 8         | 1.52%   |
| Synaptics WBDI Device                                                      | 7         | 1.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.33%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 1.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 0.95%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.95%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.95%   |
| AuthenTec AES1600                                                          | 5         | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.76%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.76%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.57%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.19%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.19%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.19%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.19%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 132       | 51.97%  |
| Alcor Micro           | 59        | 23.23%  |
| Upek                  | 21        | 8.27%   |
| O2 Micro              | 16        | 6.3%    |
| Lenovo                | 15        | 5.91%   |
| SCM Microsystems      | 3         | 1.18%   |
| Gemalto (was Gemplus) | 3         | 1.18%   |
| Purism, SPC           | 1         | 0.39%   |
| Hewlett-Packard       | 1         | 0.39%   |
| Clay Logic            | 1         | 0.39%   |
| Chicony Electronics   | 1         | 0.39%   |
| BIT4ID                | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 60        | 23.62%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 21.65%  |
| Broadcom 5880                                                                | 31        | 12.2%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 9.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 8.27%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 5.91%   |
| Broadcom 58200                                                               | 15        | 5.91%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 4.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.97%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.57%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.18%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.79%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.79%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.39%   |
| Purism, SPC Librem Key                                                       | 1         | 0.39%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.39%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.39%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.39%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3898      | 71.11%  |
| 1     | 1257      | 22.93%  |
| 2     | 269       | 4.91%   |
| 3     | 40        | 0.73%   |
| 4     | 10        | 0.18%   |
| 5     | 3         | 0.05%   |
| 7     | 2         | 0.04%   |
| 6     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 510       | 26.62%  |
| Graphics card            | 356       | 18.58%  |
| Net/wireless             | 328       | 17.12%  |
| Chipcard                 | 236       | 12.32%  |
| Multimedia controller    | 111       | 5.79%   |
| Communication controller | 97        | 5.06%   |
| Unassigned class         | 43        | 2.24%   |
| Sound                    | 38        | 1.98%   |
| Camera                   | 38        | 1.98%   |
| Bluetooth                | 36        | 1.88%   |
| Storage                  | 35        | 1.83%   |
| Net/ethernet             | 17        | 0.89%   |
| Modem                    | 16        | 0.84%   |
| Card reader              | 16        | 0.84%   |
| Network                  | 12        | 0.63%   |
| Storage/raid             | 7         | 0.37%   |
| Flash memory             | 7         | 0.37%   |
| Firewire controller      | 5         | 0.26%   |
| Storage/ide              | 4         | 0.21%   |
| Dvb card                 | 3         | 0.16%   |
| Storage/nvme             | 1         | 0.05%   |

