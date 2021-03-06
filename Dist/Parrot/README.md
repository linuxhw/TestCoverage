Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 417

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4969dd4f5](https://linux-hardware.org/?probe=d4969dd4f5) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [39351344b4](https://linux-hardware.org/?probe=39351344b4) | Jun 14, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ffb41db26d](https://linux-hardware.org/?probe=ffb41db26d) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cee28f4953](https://linux-hardware.org/?probe=cee28f4953) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 95        | 31.46%  |
| Parrot 4.11  | 84        | 27.81%  |
| Parrot 4.10  | 59        | 19.54%  |
| Parrot 4.8   | 23        | 7.62%   |
| Parrot 4.9   | 22        | 7.28%   |
| Parrot 4.7   | 13        | 4.3%    |
| Parrot 4.6   | 2         | 0.66%   |
| Parrot 4.5   | 1         | 0.33%   |
| Parrot 4.4   | 1         | 0.33%   |
| Parrot 4.2.2 | 1         | 0.33%   |
| Parrot 3.10  | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 287       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 51        | 16.5%   |
| 5.16.0-12parrot1-amd64   | 46        | 14.89%  |
| 5.7.0-2parrot2-amd64     | 33        | 10.68%  |
| 5.10.0-6parrot1-amd64    | 30        | 9.71%   |
| 5.5.0-1parrot1-amd64     | 24        | 7.77%   |
| 5.10.0-8parrot1-amd64    | 18        | 5.83%   |
| 5.4.0-4parrot1-amd64     | 16        | 5.18%   |
| 5.15.0-15parrot1-amd64   | 11        | 3.56%   |
| 5.6.0-2parrot1-amd64     | 10        | 3.24%   |
| 5.14.0-2parrot1-amd64    | 10        | 3.24%   |
| 5.9.0-2parrot1-amd64     | 9         | 2.91%   |
| 5.8.0-2parrot1-amd64     | 5         | 1.62%   |
| 5.4.0-2parrot1-amd64     | 5         | 1.62%   |
| 5.10.0-3parrot1-amd64    | 5         | 1.62%   |
| 5.8.0-1parrot1-amd64     | 4         | 1.29%   |
| 5.10.0-5parrot1-amd64    | 4         | 1.29%   |
| 5.4.0-3parrot1-amd64     | 3         | 0.97%   |
| 5.3.0-3parrot3-amd64     | 3         | 0.97%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.97%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.97%   |
| 4.18.0-parrot10-amd64    | 2         | 0.65%   |
| 5.7.0-rc6-galliumos      | 1         | 0.32%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.32%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.32%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.32%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.32%   |
| 5.18.0-1parrot1-amd64    | 1         | 0.32%   |
| 5.16.0-12parrot1-686-pae | 1         | 0.32%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.32%   |
| 5.10.0-kali6-amd64       | 1         | 0.32%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.32%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.32%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.32%   |
| 4.14.0-parrot7-amd64     | 1         | 0.32%   |
| Unknown                  | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 59        | 19.22%  |
| 5.10.0  | 59        | 19.22%  |
| 5.16.0  | 47        | 15.31%  |
| 5.7.0   | 34        | 11.07%  |
| 5.4.0   | 26        | 8.47%   |
| 5.5.0   | 24        | 7.82%   |
| 5.15.0  | 12        | 3.91%   |
| 5.6.0   | 10        | 3.26%   |
| 5.9.0   | 9         | 2.93%   |
| 5.8.0   | 9         | 2.93%   |
| 5.3.0   | 5         | 1.63%   |
| 4.19.0  | 4         | 1.3%    |
| 5.2.0   | 3         | 0.98%   |
| 4.18.0  | 2         | 0.65%   |
| 5.18.0  | 1         | 0.33%   |
| 5.1.0   | 1         | 0.33%   |
| 4.14.0  | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 59        | 19.22%  |
| 5.10    | 59        | 19.22%  |
| 5.16    | 47        | 15.31%  |
| 5.7     | 34        | 11.07%  |
| 5.4     | 26        | 8.47%   |
| 5.5     | 24        | 7.82%   |
| 5.15    | 12        | 3.91%   |
| 5.6     | 10        | 3.26%   |
| 5.9     | 9         | 2.93%   |
| 5.8     | 9         | 2.93%   |
| 5.3     | 5         | 1.63%   |
| 4.19    | 4         | 1.3%    |
| 5.2     | 3         | 0.98%   |
| 4.18    | 2         | 0.65%   |
| 5.18    | 1         | 0.33%   |
| 5.1     | 1         | 0.33%   |
| 4.14    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 285       | 99.3%   |
| i686   | 2         | 0.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| MATE          | 185       | 62.93%  |
| KDE5          | 57        | 19.39%  |
| KDE           | 20        | 6.8%    |
| Unknown       | 19        | 6.46%   |
| XFCE          | 8         | 2.72%   |
| GNOME         | 2         | 0.68%   |
| LXDE          | 1         | 0.34%   |
| GNOME Classic | 1         | 0.34%   |
| Cinnamon      | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 283       | 98.61%  |
| Wayland | 3         | 1.05%   |
| Unknown | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 107       | 36.27%  |
| Unknown | 105       | 35.59%  |
| TDM     | 71        | 24.07%  |
| GDM     | 7         | 2.37%   |
| SDDM    | 5         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 148       | 51.39%  |
| en_GB   | 22        | 7.64%   |
| fr_FR   | 14        | 4.86%   |
| Unknown | 14        | 4.86%   |
| ru_RU   | 11        | 3.82%   |
| es_ES   | 10        | 3.47%   |
| de_DE   | 10        | 3.47%   |
| pt_BR   | 8         | 2.78%   |
| pl_PL   | 7         | 2.43%   |
| en_IN   | 7         | 2.43%   |
| en_AU   | 7         | 2.43%   |
| it_IT   | 3         | 1.04%   |
| cs_CZ   | 3         | 1.04%   |
| es_MX   | 2         | 0.69%   |
| en_HK   | 2         | 0.69%   |
| en_DK   | 2         | 0.69%   |
| tr_TR   | 1         | 0.35%   |
| ru_UA   | 1         | 0.35%   |
| pt_PT   | 1         | 0.35%   |
| nl_BE   | 1         | 0.35%   |
| mk_MK   | 1         | 0.35%   |
| id_ID   | 1         | 0.35%   |
| fr_CA   | 1         | 0.35%   |
| es_PE   | 1         | 0.35%   |
| es_CO   | 1         | 0.35%   |
| es_CL   | 1         | 0.35%   |
| es_AR   | 1         | 0.35%   |
| en_ZA   | 1         | 0.35%   |
| en_NZ   | 1         | 0.35%   |
| en_NG   | 1         | 0.35%   |
| en_CA   | 1         | 0.35%   |
| de_AT   | 1         | 0.35%   |
| C       | 1         | 0.35%   |
| an_ES   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 187       | 64.26%  |
| EFI  | 104       | 35.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 213       | 72.95%  |
| Ext4    | 53        | 18.15%  |
| Xfs     | 10        | 3.42%   |
| Overlay | 9         | 3.08%   |
| Unknown | 7         | 2.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 45.55%  |
| GPT     | 106       | 36.3%   |
| MBR     | 53        | 18.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 251       | 86.25%  |
| Yes       | 40        | 13.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 190       | 65.97%  |
| Yes       | 98        | 34.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 54        | 18.82%  |
| Dell                  | 44        | 15.33%  |
| Lenovo                | 41        | 14.29%  |
| ASUSTek Computer      | 41        | 14.29%  |
| Acer                  | 16        | 5.57%   |
| MSI                   | 14        | 4.88%   |
| Apple                 | 9         | 3.14%   |
| Gigabyte Technology   | 8         | 2.79%   |
| Toshiba               | 7         | 2.44%   |
| Samsung Electronics   | 5         | 1.74%   |
| Microsoft             | 3         | 1.05%   |
| HUAWEI                | 3         | 1.05%   |
| Foxconn               | 3         | 1.05%   |
| ASRock                | 3         | 1.05%   |
| Alienware             | 3         | 1.05%   |
| Sony                  | 2         | 0.7%    |
| Razer                 | 2         | 0.7%    |
| Positivo              | 2         | 0.7%    |
| Gateway               | 2         | 0.7%    |
| Fujitsu               | 2         | 0.7%    |
| ECS                   | 2         | 0.7%    |
| ZOTAC                 | 1         | 0.35%   |
| Wortmann AG           | 1         | 0.35%   |
| Wistron               | 1         | 0.35%   |
| Toxic                 | 1         | 0.35%   |
| Timi                  | 1         | 0.35%   |
| System76              | 1         | 0.35%   |
| SLIMBOOK              | 1         | 0.35%   |
| Positivo Bahia - VAIO | 1         | 0.35%   |
| Notebook              | 1         | 0.35%   |
| Metabox               | 1         | 0.35%   |
| Jumper                | 1         | 0.35%   |
| Intel                 | 1         | 0.35%   |
| GPU Company           | 1         | 0.35%   |
| Google                | 1         | 0.35%   |
| eMachines             | 1         | 0.35%   |
| Eluktronics           | 1         | 0.35%   |
| Digma                 | 1         | 0.35%   |
| Daewoo Lucoms         | 1         | 0.35%   |
| Chuwi                 | 1         | 0.35%   |
| Biostar               | 1         | 0.35%   |
| Unknown               | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.05%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.05%   |
| HP Notebook                                        | 3         | 1.05%   |
| HP EliteBook 8470p                                 | 3         | 1.05%   |
| Microsoft Surface Pro 3                            | 2         | 0.7%    |
| HP ProDesk 600 G1 SFF                              | 2         | 0.7%    |
| HP ProBook 650 G1                                  | 2         | 0.7%    |
| HP Pavilion dv6                                    | 2         | 0.7%    |
| HP Pavilion 15                                     | 2         | 0.7%    |
| HP ENVY x360 Convertible 13-bd0xxx                 | 2         | 0.7%    |
| Gigabyte AX370-Gaming                              | 2         | 0.7%    |
| Foxconn s5710t                                     | 2         | 0.7%    |
| Dell Latitude E7440                                | 2         | 0.7%    |
| Dell Latitude E6420                                | 2         | 0.7%    |
| Dell Latitude E6410                                | 2         | 0.7%    |
| Dell Inspiron MM061                                | 2         | 0.7%    |
| Dell Inspiron 5676                                 | 2         | 0.7%    |
| ASUS Q524UQ                                        | 2         | 0.7%    |
| ASUS M5A78L-M/USB3                                 | 2         | 0.7%    |
| ASUS H110I-PLUS                                    | 2         | 0.7%    |
| ASUS Basic 3221BM                                  | 2         | 0.7%    |
| Apple MacBookPro8,1                                | 2         | 0.7%    |
| Acer Nitro AN515-54                                | 2         | 0.7%    |
| Unknown                                            | 2         | 0.7%    |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.35%   |
| Wistron FMVDD2A0H0                                 | 1         | 0.35%   |
| Toxic GM7MQ8P                                      | 1         | 0.35%   |
| Toshiba Satellite-L845                             | 1         | 0.35%   |
| Toshiba Satellite L775D                            | 1         | 0.35%   |
| Toshiba Satellite L750                             | 1         | 0.35%   |
| Toshiba Satellite L655                             | 1         | 0.35%   |
| Toshiba Satellite L300D                            | 1         | 0.35%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.35%   |
| Toshiba Satellite C75D-B                           | 1         | 0.35%   |
| Timi TM1613                                        | 1         | 0.35%   |
| System76 Gazelle                                   | 1         | 0.35%   |
| Sony VPCCB15FG                                     | 1         | 0.35%   |
| Sony SVP1321L1EBI                                  | 1         | 0.35%   |
| SLIMBOOK ONE-AMD-M4                                | 1         | 0.35%   |
| Samsung RV415/RV515                                | 1         | 0.35%   |
| Samsung 930QDB                                     | 1         | 0.35%   |
| Samsung 550P5C/550P7C                              | 1         | 0.35%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.35%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.35%   |
| Razer Blade Stealth                                | 1         | 0.35%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.35%   |
| Positivo Q232A                                     | 1         | 0.35%   |
| Positivo POS-PIG43BC                               | 1         | 0.35%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.35%   |
| Notebook W510TU                                    | 1         | 0.35%   |
| MSI MS-7C02                                        | 1         | 0.35%   |
| MSI MS-7A69                                        | 1         | 0.35%   |
| MSI MS-7A34                                        | 1         | 0.35%   |
| MSI MS-7529                                        | 1         | 0.35%   |
| MSI GT60 2OC/2OD                                   | 1         | 0.35%   |
| MSI GS66 Stealth 10UG                              | 1         | 0.35%   |
| MSI GE75 Raider 10SF                               | 1         | 0.35%   |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.35%   |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.35%   |
| MSI GE62 6QE                                       | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 17        | 5.92%   |
| HP Pavilion                             | 15        | 5.23%   |
| Dell Latitude                           | 15        | 5.23%   |
| Dell Inspiron                           | 15        | 5.23%   |
| Lenovo IdeaPad                          | 11        | 3.83%   |
| Acer Aspire                             | 8         | 2.79%   |
| HP EliteBook                            | 7         | 2.44%   |
| Toshiba Satellite                       | 6         | 2.09%   |
| HP ENVY                                 | 6         | 2.09%   |
| HP ProBook                              | 5         | 1.74%   |
| HP Laptop                               | 5         | 1.74%   |
| HP Compaq                               | 5         | 1.74%   |
| Dell OptiPlex                           | 5         | 1.74%   |
| ASUS VivoBook                           | 4         | 1.39%   |
| MSI Modern                              | 3         | 1.05%   |
| Microsoft Surface                       | 3         | 1.05%   |
| HP Notebook                             | 3         | 1.05%   |
| ASUS ROG                                | 3         | 1.05%   |
| ASUS PRIME                              | 3         | 1.05%   |
| Acer Nitro                              | 3         | 1.05%   |
| Razer Blade                             | 2         | 0.7%    |
| Lenovo Yoga                             | 2         | 0.7%    |
| HP ZBook                                | 2         | 0.7%    |
| HP ProDesk                              | 2         | 0.7%    |
| Gigabyte AX370-Gaming                   | 2         | 0.7%    |
| Fujitsu LIFEBOOK                        | 2         | 0.7%    |
| Foxconn s5710t                          | 2         | 0.7%    |
| Dell XPS                                | 2         | 0.7%    |
| Dell Vostro                             | 2         | 0.7%    |
| Dell Precision                          | 2         | 0.7%    |
| ASUS Q524UQ                             | 2         | 0.7%    |
| ASUS M5A78L-M                           | 2         | 0.7%    |
| ASUS H110I-PLUS                         | 2         | 0.7%    |
| ASUS Basic                              | 2         | 0.7%    |
| Apple MacBookPro8                       | 2         | 0.7%    |
| Apple MacBookPro11                      | 2         | 0.7%    |
| Acer Swift                              | 2         | 0.7%    |
| Acer Predator                           | 2         | 0.7%    |
| Unknown                                 | 2         | 0.7%    |
| Wortmann AG TERRA                       | 1         | 0.35%   |
| Wistron FMVDD2A0H0                      | 1         | 0.35%   |
| Toxic GM7MQ8P                           | 1         | 0.35%   |
| Toshiba Satellite-L845                  | 1         | 0.35%   |
| Timi TM1613                             | 1         | 0.35%   |
| System76 Gazelle                        | 1         | 0.35%   |
| Sony VPCCB15FG                          | 1         | 0.35%   |
| Sony SVP1321L1EBI                       | 1         | 0.35%   |
| SLIMBOOK ONE-AMD-M4                     | 1         | 0.35%   |
| Samsung RV415                           | 1         | 0.35%   |
| Samsung 930QDB                          | 1         | 0.35%   |
| Samsung 550P5C                          | 1         | 0.35%   |
| Samsung 350V5C                          | 1         | 0.35%   |
| Samsung 300E4C                          | 1         | 0.35%   |
| Positivo Q232A                          | 1         | 0.35%   |
| Positivo POS-PIG43BC                    | 1         | 0.35%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.35%   |
| Notebook W510TU                         | 1         | 0.35%   |
| MSI MS-7C02                             | 1         | 0.35%   |
| MSI MS-7A69                             | 1         | 0.35%   |
| MSI MS-7A34                             | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 34        | 11.85%  |
| 2019 | 33        | 11.5%   |
| 2018 | 27        | 9.41%   |
| 2013 | 26        | 9.06%   |
| 2016 | 24        | 8.36%   |
| 2021 | 21        | 7.32%   |
| 2017 | 21        | 7.32%   |
| 2020 | 20        | 6.97%   |
| 2014 | 17        | 5.92%   |
| 2012 | 17        | 5.92%   |
| 2010 | 14        | 4.88%   |
| 2015 | 11        | 3.83%   |
| 2007 | 7         | 2.44%   |
| 2008 | 6         | 2.09%   |
| 2009 | 5         | 1.74%   |
| 2006 | 3         | 1.05%   |
| 2022 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 199       | 69.34%  |
| Desktop     | 72        | 25.09%  |
| Convertible | 10        | 3.48%   |
| Tablet      | 4         | 1.39%   |
| Mini pc     | 1         | 0.35%   |
| All in one  | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 287       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 286       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 70        | 24.14%  |
| 8.01-16.0   | 64        | 22.07%  |
| 16.01-24.0  | 57        | 19.66%  |
| 3.01-4.0    | 52        | 17.93%  |
| 32.01-64.0  | 23        | 7.93%   |
| 1.01-2.0    | 10        | 3.45%   |
| 64.01-256.0 | 7         | 2.41%   |
| 24.01-32.0  | 4         | 1.38%   |
| 2.01-3.0    | 3         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 99        | 32.78%  |
| 2.01-3.0   | 98        | 32.45%  |
| 3.01-4.0   | 42        | 13.91%  |
| 4.01-8.0   | 41        | 13.58%  |
| 0.51-1.0   | 13        | 4.3%    |
| 8.01-16.0  | 7         | 2.32%   |
| 16.01-24.0 | 1         | 0.33%   |
| 0.01-0.5   | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 166       | 56.85%  |
| 2      | 95        | 32.53%  |
| 3      | 22        | 7.53%   |
| 4      | 4         | 1.37%   |
| 5      | 3         | 1.03%   |
| 6      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 198       | 68.51%  |
| Yes       | 91        | 31.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 81.94%  |
| No        | 52        | 18.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 264       | 91.35%  |
| No        | 25        | 8.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 68.04%  |
| No        | 93        | 31.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 92        | 31.62%  |
| Germany         | 21        | 7.22%   |
| Spain           | 14        | 4.81%   |
| France          | 13        | 4.47%   |
| Brazil          | 12        | 4.12%   |
| UK              | 11        | 3.78%   |
| Netherlands     | 11        | 3.78%   |
| Russia          | 9         | 3.09%   |
| India           | 9         | 3.09%   |
| Mexico          | 7         | 2.41%   |
| Italy           | 6         | 2.06%   |
| Canada          | 6         | 2.06%   |
| Australia       | 6         | 2.06%   |
| Poland          | 4         | 1.37%   |
| Kenya           | 4         | 1.37%   |
| Indonesia       | 4         | 1.37%   |
| Denmark         | 4         | 1.37%   |
| Czechia         | 4         | 1.37%   |
| Sweden          | 3         | 1.03%   |
| South Africa    | 3         | 1.03%   |
| Iraq            | 3         | 1.03%   |
| Austria         | 3         | 1.03%   |
| Turkey          | 2         | 0.69%   |
| Portugal        | 2         | 0.69%   |
| Pakistan        | 2         | 0.69%   |
| Morocco         | 2         | 0.69%   |
| Hong Kong       | 2         | 0.69%   |
| Belgium         | 2         | 0.69%   |
| Bangladesh      | 2         | 0.69%   |
| Algeria         | 2         | 0.69%   |
| Vietnam         | 1         | 0.34%   |
| Ukraine         | 1         | 0.34%   |
| Switzerland     | 1         | 0.34%   |
| Romania         | 1         | 0.34%   |
| Puerto Rico     | 1         | 0.34%   |
| Peru            | 1         | 0.34%   |
| North Macedonia | 1         | 0.34%   |
| Nigeria         | 1         | 0.34%   |
| New Zealand     | 1         | 0.34%   |
| Myanmar         | 1         | 0.34%   |
| Mongolia        | 1         | 0.34%   |
| Latvia          | 1         | 0.34%   |
| Hungary         | 1         | 0.34%   |
| Greece          | 1         | 0.34%   |
| Georgia         | 1         | 0.34%   |
| Finland         | 1         | 0.34%   |
| Egypt           | 1         | 0.34%   |
| Croatia         | 1         | 0.34%   |
| Costa Rica      | 1         | 0.34%   |
| Colombia        | 1         | 0.34%   |
| Chile           | 1         | 0.34%   |
| Bulgaria        | 1         | 0.34%   |
| Belarus         | 1         | 0.34%   |
| Azerbaijan      | 1         | 0.34%   |
| Argentina       | 1         | 0.34%   |
| Unknown         | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 5         | 1.66%   |
| Nairobi             | 4         | 1.33%   |
| Madrid              | 4         | 1.33%   |
| Vienna              | 3         | 1%      |
| Sydney              | 3         | 1%      |
| Seattle             | 3         | 1%      |
| Melbourne           | 3         | 1%      |
| Los Angeles         | 3         | 1%      |
| Indianapolis        | 3         | 1%      |
| Eugene              | 3         | 1%      |
| Dallas              | 3         | 1%      |
| Chicago             | 3         | 1%      |
| Berlin              | 3         | 1%      |
| Atlanta             | 3         | 1%      |
| Warsaw              | 2         | 0.66%   |
| Uhersk?? Hradi??t?? | 2         | 0.66%   |
| Tangier             | 2         | 0.66%   |
| Stockholm           | 2         | 0.66%   |
| Sao Paulo           | 2         | 0.66%   |
| Saint Paul          | 2         | 0.66%   |
| Ruskin              | 2         | 0.66%   |
| Pretoria            | 2         | 0.66%   |
| Paris               | 2         | 0.66%   |
| Ngau Wu Tok         | 2         | 0.66%   |
| Newburgh            | 2         | 0.66%   |
| New York            | 2         | 0.66%   |
| Mostoles            | 2         | 0.66%   |
| Maricopa            | 2         | 0.66%   |
| Lyon                | 2         | 0.66%   |
| Khabarovsk          | 2         | 0.66%   |
| Houston             | 2         | 0.66%   |
| Dhaka               | 2         | 0.66%   |
| Camden              | 2         | 0.66%   |
| Bussum              | 2         | 0.66%   |
| Barcelona           | 2         | 0.66%   |
| Baghdad             | 2         | 0.66%   |
| Zurich              | 1         | 0.33%   |
| Zagreb              | 1         | 0.33%   |
| West Jordan         | 1         | 0.33%   |
| West Chester        | 1         | 0.33%   |
| Washington          | 1         | 0.33%   |
| Waren               | 1         | 0.33%   |
| Volgograd           | 1         | 0.33%   |
| Visalia             | 1         | 0.33%   |
| Villa Carlos Paz    | 1         | 0.33%   |
| Vila Nova de Gaia   | 1         | 0.33%   |
| Viby J              | 1         | 0.33%   |
| Veitsbronn          | 1         | 0.33%   |
| Vapi                | 1         | 0.33%   |
| Ulan Bator          | 1         | 0.33%   |
| Tulare              | 1         | 0.33%   |
| Ts'khinvali         | 1         | 0.33%   |
| Trivandrum          | 1         | 0.33%   |
| Tottenham           | 1         | 0.33%   |
| Toronto             | 1         | 0.33%   |
| Terrace             | 1         | 0.33%   |
| Tempe               | 1         | 0.33%   |
| Tangerang           | 1         | 0.33%   |
| Sviyazhsk           | 1         | 0.33%   |
| Surabaya            | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 64        | 84     | 15.42%  |
| Samsung Electronics | 59        | 75     | 14.22%  |
| Seagate             | 53        | 65     | 12.77%  |
| Toshiba             | 50        | 53     | 12.05%  |
| Unknown             | 27        | 28     | 6.51%   |
| Kingston            | 25        | 26     | 6.02%   |
| SanDisk             | 19        | 24     | 4.58%   |
| Hitachi             | 14        | 17     | 3.37%   |
| Crucial             | 14        | 19     | 3.37%   |
| HGST                | 9         | 11     | 2.17%   |
| SK hynix            | 8         | 8      | 1.93%   |
| Micron Technology   | 7         | 7      | 1.69%   |
| China               | 6         | 9      | 1.45%   |
| A-DATA Technology   | 6         | 6      | 1.45%   |
| Intel               | 5         | 12     | 1.2%    |
| Apple               | 5         | 5      | 1.2%    |
| LITEONIT            | 3         | 3      | 0.72%   |
| LITEON              | 3         | 3      | 0.72%   |
| JMicron Technology  | 3         | 3      | 0.72%   |
| Fujitsu             | 3         | 3      | 0.72%   |
| Team                | 2         | 3      | 0.48%   |
| SPCC                | 2         | 2      | 0.48%   |
| Silicon Motion      | 2         | 2      | 0.48%   |
| PNY                 | 2         | 2      | 0.48%   |
| Phison              | 2         | 2      | 0.48%   |
| KIOXIA              | 2         | 2      | 0.48%   |
| Intenso             | 2         | 3      | 0.48%   |
| HUAWEI              | 2         | 2      | 0.48%   |
| YMTC                | 1         | 1      | 0.24%   |
| W800SH              | 1         | 1      | 0.24%   |
| Transcend           | 1         | 1      | 0.24%   |
| S3+                 | 1         | 1      | 0.24%   |
| ROG                 | 1         | 1      | 0.24%   |
| Plextor             | 1         | 1      | 0.24%   |
| Patriot             | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| Netac               | 1         | 1      | 0.24%   |
| Lexar               | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 2      | 0.24%   |
| KingFast            | 1         | 2      | 0.24%   |
| FORESEE             | 1         | 1      | 0.24%   |
| Corsair             | 1         | 2      | 0.24%   |
| BHT                 | 1         | 1      | 0.24%   |
| ASMedia             | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB              | 10        | 2.22%   |
| Samsung SSD 860 EVO 500GB           | 7         | 1.55%   |
| Toshiba MQ01ABF050 500GB            | 6         | 1.33%   |
| Unknown SD/MMC/MS PRO 128GB         | 5         | 1.11%   |
| Toshiba DT01ACA200 2TB              | 5         | 1.11%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 5         | 1.11%   |
| Unknown MMC Card  32GB              | 4         | 0.89%   |
| Toshiba MQ01ABD100 1TB              | 4         | 0.89%   |
| SanDisk SSD PLUS 1000GB             | 4         | 0.89%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 0.89%   |
| Kingston NVMe SSD Drive 512GB       | 4         | 0.89%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.89%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.89%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.67%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.67%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.67%   |
| Seagate ST31000528AS 1TB            | 3         | 0.67%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.67%   |
| Seagate Expansion 1TB               | 3         | 0.67%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.67%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.67%   |
| Samsung HM500JI 500GB               | 3         | 0.67%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.67%   |
| JMicron Generic 2TB                 | 3         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.44%   |
| WDC WDS100T2B0B-00YS70 1TB SSD      | 2         | 0.44%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 0.44%   |
| WDC WD2500JS-75MHB0 250GB           | 2         | 0.44%   |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 0.44%   |
| WDC WD10SPZX-60Z10T0 1TB            | 2         | 0.44%   |
| WDC WD10EZRX-00L4HB0 1TB            | 2         | 0.44%   |
| WDC WD10EARS-00Y5B1 1TB             | 2         | 0.44%   |
| Toshiba DT01ACA100 1TB              | 2         | 0.44%   |
| Toshiba DT01ACA050 500GB            | 2         | 0.44%   |
| Seagate ST9250315AS 250GB           | 2         | 0.44%   |
| Seagate ST500VT000-1DK142 500GB     | 2         | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.44%   |
| Seagate ST500LM000-SSHD-8GB         | 2         | 0.44%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 2         | 0.44%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.44%   |
| SanDisk NVMe SSD Drive 1TB          | 2         | 0.44%   |
| Samsung SSD 980 1TB                 | 2         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.44%   |
| Samsung SSD 840 Series 250GB        | 2         | 0.44%   |
| Samsung MZVLB1T0HBLR-000L2 1TB      | 2         | 0.44%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.44%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.44%   |
| Intenso SSD SATAIII 480GB           | 2         | 0.44%   |
| Intel HBRPEKNX0202AHO 32GB          | 2         | 0.44%   |
| Intel HBRPEKNX0202AH 512GB          | 2         | 0.44%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 0.44%   |
| Fujitsu F300 480GB                  | 2         | 0.44%   |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.44%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.44%   |
| Apple SSD SM0256G 256GB             | 2         | 0.44%   |
| YMTC PC005 512GB                    | 1         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 65     | 28.8%   |
| WDC                 | 48        | 63     | 26.09%  |
| Toshiba             | 43        | 45     | 23.37%  |
| Hitachi             | 14        | 17     | 7.61%   |
| HGST                | 9         | 11     | 4.89%   |
| Samsung Electronics | 7         | 9      | 3.8%    |
| Unknown             | 5         | 5      | 2.72%   |
| JMicron Technology  | 3         | 3      | 1.63%   |
| Fujitsu             | 1         | 1      | 0.54%   |
| ASMedia             | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 38     | 21.64%  |
| Kingston            | 17        | 18     | 12.69%  |
| Crucial             | 13        | 18     | 9.7%    |
| SanDisk             | 12        | 13     | 8.96%   |
| WDC                 | 11        | 12     | 8.21%   |
| China               | 6         | 9      | 4.48%   |
| Toshiba             | 4         | 5      | 2.99%   |
| Apple               | 4         | 4      | 2.99%   |
| Micron Technology   | 3         | 3      | 2.24%   |
| LITEONIT            | 3         | 3      | 2.24%   |
| LITEON              | 3         | 3      | 2.24%   |
| Unknown             | 2         | 2      | 1.49%   |
| Team                | 2         | 3      | 1.49%   |
| SPCC                | 2         | 2      | 1.49%   |
| PNY                 | 2         | 2      | 1.49%   |
| Intenso             | 2         | 3      | 1.49%   |
| Intel               | 2         | 2      | 1.49%   |
| Fujitsu             | 2         | 2      | 1.49%   |
| A-DATA Technology   | 2         | 2      | 1.49%   |
| W800SH              | 1         | 1      | 0.75%   |
| Transcend           | 1         | 1      | 0.75%   |
| SK hynix            | 1         | 1      | 0.75%   |
| S3+                 | 1         | 1      | 0.75%   |
| Plextor             | 1         | 1      | 0.75%   |
| Patriot             | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 2      | 0.75%   |
| KingFast            | 1         | 1      | 0.75%   |
| FORESEE             | 1         | 1      | 0.75%   |
| Corsair             | 1         | 2      | 0.75%   |
| BHT                 | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 161       | 220    | 42.82%  |
| SSD     | 119       | 159    | 31.65%  |
| NVMe    | 72        | 92     | 19.15%  |
| MMC     | 19        | 22     | 5.05%   |
| Unknown | 5         | 5      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 228       | 360    | 66.86%  |
| NVMe | 72        | 92     | 21.11%  |
| SAS  | 22        | 24     | 6.45%   |
| MMC  | 19        | 22     | 5.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 166       | 239    | 57.04%  |
| 0.51-1.0   | 99        | 110    | 34.02%  |
| 1.01-2.0   | 21        | 25     | 7.22%   |
| 3.01-4.0   | 3         | 3      | 1.03%   |
| 2.01-3.0   | 1         | 1      | 0.34%   |
| 4.01-10.0  | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 77        | 26.19%  |
| 101-250        | 67        | 22.79%  |
| 501-1000       | 46        | 15.65%  |
| 1001-2000      | 34        | 11.56%  |
| Unknown        | 22        | 7.48%   |
| 51-100         | 16        | 5.44%   |
| 21-50          | 14        | 4.76%   |
| 2001-3000      | 9         | 3.06%   |
| 1-20           | 5         | 1.7%    |
| More than 3000 | 4         | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 87        | 28.9%   |
| 1-20           | 51        | 16.94%  |
| 51-100         | 49        | 16.28%  |
| 101-250        | 44        | 14.62%  |
| 251-500        | 31        | 10.3%   |
| Unknown        | 22        | 7.31%   |
| 501-1000       | 12        | 3.99%   |
| 1001-2000      | 3         | 1%      |
| More than 3000 | 2         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 3         | 3      | 7.32%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 2         | 2      | 4.88%   |
| WDC WD5000AAKS-75V0A0 500GB                         | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.44%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1      | 2.44%   |
| WDC WD10JUCX-63WPNY0 1TB                            | 1         | 1      | 2.44%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 2.44%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST3320418AS 320GB                           | 1         | 1      | 2.44%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 2.44%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.44%   |
| Seagate ST250DM000-1BD141 250GB                     | 1         | 1      | 2.44%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.44%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 1      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.44%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 2.44%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 2.44%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.44%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.44%   |
| Plextor PX-512M6Pro 512GB SSD                       | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.44%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.44%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 2.44%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.44%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.44%   |
| A-DATA Technology SX7000NP 128GB                    | 1         | 1      | 2.44%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.44%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 25.64%  |
| WDC                 | 6         | 6      | 15.38%  |
| Samsung Electronics | 5         | 5      | 12.82%  |
| SanDisk             | 4         | 4      | 10.26%  |
| Hitachi             | 4         | 4      | 10.26%  |
| A-DATA Technology   | 3         | 3      | 7.69%   |
| Toshiba             | 2         | 2      | 5.13%   |
| Plextor             | 1         | 1      | 2.56%   |
| Micron Technology   | 1         | 1      | 2.56%   |
| LITEON              | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 35.71%  |
| WDC                 | 6         | 6      | 21.43%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| Toshiba             | 2         | 2      | 7.14%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 30     | 70.27%  |
| SSD  | 9         | 9      | 24.32%  |
| NVMe | 2         | 2      | 5.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 480GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 154       | 264    | 46.25%  |
| Works    | 144       | 191    | 43.24%  |
| Malfunc  | 33        | 41     | 9.91%   |
| Failed   | 2         | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 200       | 60.24%  |
| AMD                          | 49        | 14.76%  |
| Samsung Electronics          | 27        | 8.13%   |
| SanDisk                      | 14        | 4.22%   |
| Kingston Technology Company  | 8         | 2.41%   |
| SK hynix                     | 7         | 2.11%   |
| Nvidia                       | 4         | 1.2%    |
| Micron Technology            | 4         | 1.2%    |
| Toshiba America Info Systems | 3         | 0.9%    |
| Silicon Motion               | 3         | 0.9%    |
| Phison Electronics           | 2         | 0.6%    |
| KIOXIA                       | 2         | 0.6%    |
| ADATA Technology             | 2         | 0.6%    |
| Yangtze Memory Technologies  | 1         | 0.3%    |
| VIA Technologies             | 1         | 0.3%    |
| Realtek Semiconductor        | 1         | 0.3%    |
| Micron/Crucial Technology    | 1         | 0.3%    |
| JMicron Technology           | 1         | 0.3%    |
| ASMedia Technology           | 1         | 0.3%    |
| Apple                        | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35        | 9.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 5.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 5.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 16        | 4.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 3.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 2.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 2.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 1.58%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 1.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.58%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 5         | 1.32%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 5         | 1.32%   |
| SK hynix BC511                                                                          | 4         | 1.06%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 4         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.06%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4         | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.79%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 3         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.79%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.53%   |
| SK hynix Gold P31 SSD                                                                   | 2         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.53%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.53%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.53%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.53%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.53%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.53%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.53%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.53%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.53%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 2         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 202       | 59.24%  |
| NVMe | 72        | 21.11%  |
| IDE  | 38        | 11.14%  |
| RAID | 29        | 8.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 228       | 79.44%  |
| AMD    | 59        | 20.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 2.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.05%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.05%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 2         | 0.7%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 2         | 0.7%    |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.7%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.7%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.7%    |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.7%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.7%    |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.7%    |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2         | 0.7%    |
| AMD Ryzen 7 1700X Eight-Core Processor        | 2         | 0.7%    |
| AMD E1-2500 APU with Radeon HD Graphics       | 2         | 0.7%    |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.7%    |
| Intel Xeon CPU X5460 @ 3.16GHz                | 1         | 0.35%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.35%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 27.18%  |
| Intel Core i7           | 70        | 24.39%  |
| Intel Core i3           | 23        | 8.01%   |
| Other                   | 15        | 5.23%   |
| AMD Ryzen 7             | 13        | 4.53%   |
| Intel Core 2 Duo        | 9         | 3.14%   |
| AMD Ryzen 5             | 9         | 3.14%   |
| Intel Celeron           | 8         | 2.79%   |
| Intel Pentium           | 6         | 2.09%   |
| AMD A6                  | 6         | 2.09%   |
| Intel Xeon              | 4         | 1.39%   |
| Intel Pentium Dual-Core | 4         | 1.39%   |
| AMD FX                  | 4         | 1.39%   |
| Intel Core 2            | 3         | 1.05%   |
| Intel Atom              | 3         | 1.05%   |
| AMD Ryzen 3             | 3         | 1.05%   |
| AMD E1                  | 3         | 1.05%   |
| AMD A4                  | 3         | 1.05%   |
| Intel Pentium Silver    | 2         | 0.7%    |
| Intel Core 2 Quad       | 2         | 0.7%    |
| AMD Athlon II X2        | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| AMD A10                 | 2         | 0.7%    |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Core M            | 1         | 0.35%   |
| Intel Core 2 Extreme    | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD Phenom              | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-50                | 1         | 0.35%   |
| AMD Athlon X2           | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD Athlon 64           | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 139       | 48.43%  |
| 4      | 100       | 34.84%  |
| 6      | 22        | 7.67%   |
| 8      | 17        | 5.92%   |
| 1      | 4         | 1.39%   |
| 12     | 2         | 0.7%    |
| 3      | 2         | 0.7%    |
| 14     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 286       | 99.65%  |
| 2      | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 204       | 71.08%  |
| 1      | 83        | 28.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 282       | 98.26%  |
| Unknown        | 5         | 1.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 47.46%  |
| 0x206a7    | 18        | 6.1%    |
| 0x306a9    | 10        | 3.39%   |
| 0x806e9    | 8         | 2.71%   |
| 0x806c1    | 8         | 2.71%   |
| 0x906ea    | 7         | 2.37%   |
| 0x806ec    | 7         | 2.37%   |
| 0x306c3    | 7         | 2.37%   |
| 0x906e9    | 6         | 2.03%   |
| 0x806ea    | 6         | 2.03%   |
| 0x406e3    | 6         | 2.03%   |
| 0x1067a    | 6         | 2.03%   |
| 0xa0652    | 5         | 1.69%   |
| 0x40651    | 5         | 1.69%   |
| 0x706e5    | 4         | 1.36%   |
| 0x6f6      | 3         | 1.02%   |
| 0x406c4    | 3         | 1.02%   |
| 0x07030105 | 3         | 1.02%   |
| 0x06006705 | 3         | 1.02%   |
| 0x906ed    | 2         | 0.68%   |
| 0x806d1    | 2         | 0.68%   |
| 0x706a8    | 2         | 0.68%   |
| 0x306d4    | 2         | 0.68%   |
| 0x08701021 | 2         | 0.68%   |
| 0x08600106 | 2         | 0.68%   |
| 0x08108109 | 2         | 0.68%   |
| 0x08001138 | 2         | 0.68%   |
| 0x06001119 | 2         | 0.68%   |
| 0x06000852 | 2         | 0.68%   |
| 0x03000027 | 2         | 0.68%   |
| 0x906a3    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x806c2    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6fd      | 1         | 0.34%   |
| 0x506e3    | 1         | 0.34%   |
| 0x506c9    | 1         | 0.34%   |
| 0x40661    | 1         | 0.34%   |
| 0x20655    | 1         | 0.34%   |
| 0x106a5    | 1         | 0.34%   |
| 0x0a201016 | 1         | 0.34%   |
| 0x08108102 | 1         | 0.34%   |
| 0x0810100b | 1         | 0.34%   |
| 0x0800820d | 1         | 0.34%   |
| 0x06006113 | 1         | 0.34%   |
| 0x0600111f | 1         | 0.34%   |
| 0x05000029 | 1         | 0.34%   |
| 0x01000095 | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 58        | 20.21%  |
| Haswell          | 29        | 10.1%   |
| SandyBridge      | 26        | 9.06%   |
| IvyBridge        | 20        | 6.97%   |
| Skylake          | 18        | 6.27%   |
| Penryn           | 14        | 4.88%   |
| Broadwell        | 11        | 3.83%   |
| TigerLake        | 10        | 3.48%   |
| Silvermont       | 9         | 3.14%   |
| Piledriver       | 8         | 2.79%   |
| Core             | 8         | 2.79%   |
| Zen+             | 7         | 2.44%   |
| Zen              | 7         | 2.44%   |
| IceLake          | 7         | 2.44%   |
| CometLake        | 7         | 2.44%   |
| Zen 2            | 6         | 2.09%   |
| Excavator        | 6         | 2.09%   |
| Westmere         | 5         | 1.74%   |
| K10              | 4         | 1.39%   |
| Unknown          | 4         | 1.39%   |
| Zen 3            | 3         | 1.05%   |
| Puma             | 3         | 1.05%   |
| Jaguar           | 3         | 1.05%   |
| Goldmont plus    | 3         | 1.05%   |
| K8 Hammer        | 2         | 0.7%    |
| K10 Llano        | 2         | 0.7%    |
| Bobcat           | 2         | 0.7%    |
| Steamroller      | 1         | 0.35%   |
| Nehalem          | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |
| Goldmont         | 1         | 0.35%   |
| Alderlake Hybrid | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 195       | 53.28%  |
| Nvidia | 92        | 25.14%  |
| AMD    | 79        | 21.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 3.23%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.7%    |
| Intel HD Graphics 5500                                                                   | 9         | 2.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.43%   |
| Intel HD Graphics 620                                                                    | 8         | 2.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.89%   |
| Intel HD Graphics 630                                                                    | 6         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.35%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.08%   |
| Intel HD Graphics 530                                                                    | 4         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.08%   |
| AMD Lucienne                                                                             | 4         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.81%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.81%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.81%   |
| AMD Renoir                                                                               | 3         | 0.81%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.81%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 3         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.54%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.54%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.54%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.54%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.54%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.54%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.54%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.54%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.54%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.54%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.54%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.54%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 41.81%  |
| 1 x AMD        | 59        | 20.56%  |
| Intel + Nvidia | 53        | 18.47%  |
| 1 x Nvidia     | 35        | 12.2%   |
| Intel + AMD    | 15        | 5.23%   |
| AMD + Nvidia   | 4         | 1.39%   |
| 2 x AMD        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 254       | 88.19%  |
| Proprietary | 31        | 10.76%  |
| Unknown     | 3         | 1.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 71.92%  |
| 1.01-2.0   | 23        | 7.88%   |
| 0.51-1.0   | 18        | 6.16%   |
| 3.01-4.0   | 16        | 5.48%   |
| 0.01-0.5   | 16        | 5.48%   |
| 7.01-8.0   | 5         | 1.71%   |
| 5.01-6.0   | 3         | 1.03%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 15.99%  |
| LG Display              | 41        | 12.85%  |
| Samsung Electronics     | 38        | 11.91%  |
| BOE                     | 33        | 10.34%  |
| Chimei Innolux          | 32        | 10.03%  |
| Dell                    | 12        | 3.76%   |
| Apple                   | 9         | 2.82%   |
| Acer                    | 9         | 2.82%   |
| Goldstar                | 7         | 2.19%   |
| Chi Mei Optoelectronics | 7         | 2.19%   |
| Philips                 | 6         | 1.88%   |
| Hewlett-Packard         | 6         | 1.88%   |
| BenQ                    | 6         | 1.88%   |
| Unknown                 | 5         | 1.57%   |
| Lenovo                  | 5         | 1.57%   |
| AOC                     | 5         | 1.57%   |
| Sharp                   | 4         | 1.25%   |
| Panasonic               | 4         | 1.25%   |
| Ancor Communications    | 4         | 1.25%   |
| PANDA                   | 3         | 0.94%   |
| AUS                     | 3         | 0.94%   |
| Vizio                   | 2         | 0.63%   |
| ViewSonic               | 2         | 0.63%   |
| Toshiba                 | 2         | 0.63%   |
| NEC Computers           | 2         | 0.63%   |
| InfoVision              | 2         | 0.63%   |
| Eizo                    | 2         | 0.63%   |
| ___                     | 1         | 0.31%   |
| Unknown (AAA)           | 1         | 0.31%   |
| STD                     | 1         | 0.31%   |
| STA                     | 1         | 0.31%   |
| Sony                    | 1         | 0.31%   |
| Sceptre Tech            | 1         | 0.31%   |
| Sceptre                 | 1         | 0.31%   |
| SANYO                   | 1         | 0.31%   |
| RIS                     | 1         | 0.31%   |
| Plain Tree Systems      | 1         | 0.31%   |
| ONN                     | 1         | 0.31%   |
| Kogan                   | 1         | 0.31%   |
| Insignia                | 1         | 0.31%   |
| Iiyama                  | 1         | 0.31%   |
| CSO                     | 1         | 0.31%   |
| Ativa                   | 1         | 0.31%   |
| AGO                     | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.93%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.62%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.62%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.62%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.62%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.62%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 0.62%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.62%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.62%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.62%   |
| Lenovo LCD Monitor LEN1144 1920x1200 520x320mm 24.0-inch              | 2         | 0.62%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 2         | 0.62%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2         | 0.62%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 2         | 0.62%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.62%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.62%   |
| AUS LCD Monitor VG245 1920x1080                                       | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.62%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                      | 2         | 0.62%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.31%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.31%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.31%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.31%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.31%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.31%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1         | 0.31%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                             | 1         | 0.31%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.31%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1         | 0.31%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.31%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1         | 0.31%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.31%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch               | 1         | 0.31%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.31%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.31%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.31%   |
| Sceptre LCD Monitor P30 2560x1080                                     | 1         | 0.31%   |
| SANYO LCD SAN0B51 1920x540                                            | 1         | 0.31%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch  | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch  | 1         | 0.31%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.31%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.31%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 135       | 44.12%  |
| 1366x768 (WXGA)    | 77        | 25.16%  |
| 1600x900 (HD+)     | 16        | 5.23%   |
| 1680x1050 (WSXGA+) | 11        | 3.59%   |
| 1280x800 (WXGA)    | 10        | 3.27%   |
| 3840x2160 (4K)     | 8         | 2.61%   |
| 1280x1024 (SXGA)   | 8         | 2.61%   |
| 1440x900 (WXGA+)   | 7         | 2.29%   |
| 2560x1440 (QHD)    | 5         | 1.63%   |
| 1360x768           | 5         | 1.63%   |
| 2160x1440          | 4         | 1.31%   |
| 1920x1200 (WUXGA)  | 4         | 1.31%   |
| 1920x540           | 3         | 0.98%   |
| 3840x1080          | 2         | 0.65%   |
| 2880x1800          | 2         | 0.65%   |
| 2560x1600          | 2         | 0.65%   |
| 2560x1080          | 2         | 0.65%   |
| Unknown            | 2         | 0.65%   |
| 3200x1080          | 1         | 0.33%   |
| 1280x720 (HD)      | 1         | 0.33%   |
| 1024x768 (XGA)     | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 94        | 29.47%  |
| 14      | 36        | 11.29%  |
| 13      | 34        | 10.66%  |
| 17      | 28        | 8.78%   |
| 24      | 17        | 5.33%   |
| Unknown | 17        | 5.33%   |
| 27      | 15        | 4.7%    |
| 23      | 14        | 4.39%   |
| 12      | 10        | 3.13%   |
| 22      | 9         | 2.82%   |
| 21      | 9         | 2.82%   |
| 31      | 8         | 2.51%   |
| 19      | 6         | 1.88%   |
| 11      | 4         | 1.25%   |
| 32      | 3         | 0.94%   |
| 40      | 2         | 0.63%   |
| 18      | 2         | 0.63%   |
| 16      | 2         | 0.63%   |
| 84      | 1         | 0.31%   |
| 72      | 1         | 0.31%   |
| 52      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 42      | 1         | 0.31%   |
| 41      | 1         | 0.31%   |
| 34      | 1         | 0.31%   |
| 25      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 156       | 49.68%  |
| 501-600     | 41        | 13.06%  |
| 351-400     | 28        | 8.92%   |
| 201-300     | 27        | 8.6%    |
| 401-500     | 24        | 7.64%   |
| Unknown     | 17        | 5.41%   |
| 601-700     | 9         | 2.87%   |
| 701-800     | 4         | 1.27%   |
| 801-900     | 2         | 0.64%   |
| 1501-2000   | 2         | 0.64%   |
| 1001-1500   | 2         | 0.64%   |
| 901-1000    | 2         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 231       | 78.31%  |
| 16/10   | 34        | 11.53%  |
| Unknown | 12        | 4.07%   |
| 5/4     | 7         | 2.37%   |
| 32/9    | 4         | 1.36%   |
| 3/2     | 3         | 1.02%   |
| 4/3     | 2         | 0.68%   |
| 6/5     | 1         | 0.34%   |
| 21/9    | 1         | 0.34%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 29.78%  |
| 81-90          | 59        | 18.5%   |
| 201-250        | 40        | 12.54%  |
| 121-130        | 20        | 6.27%   |
| Unknown        | 17        | 5.33%   |
| 301-350        | 15        | 4.7%    |
| 71-80          | 12        | 3.76%   |
| 351-500        | 12        | 3.76%   |
| 151-200        | 10        | 3.13%   |
| 61-70          | 9         | 2.82%   |
| 251-300        | 7         | 2.19%   |
| 141-150        | 7         | 2.19%   |
| 501-1000       | 5         | 1.57%   |
| 51-60          | 4         | 1.25%   |
| More than 1000 | 3         | 0.94%   |
| 131-140        | 3         | 0.94%   |
| 111-120        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 95        | 30.84%  |
| 101-120       | 88        | 28.57%  |
| 51-100        | 79        | 25.65%  |
| 161-240       | 17        | 5.52%   |
| Unknown       | 17        | 5.52%   |
| 1-50          | 7         | 2.27%   |
| More than 240 | 5         | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 239       | 82.13%  |
| 2     | 43        | 14.78%  |
| 3     | 5         | 1.72%   |
| 0     | 4         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 162       | 33.2%   |
| Intel                                  | 141       | 28.89%  |
| Qualcomm Atheros                       | 54        | 11.07%  |
| Broadcom                               | 29        | 5.94%   |
| Ralink Technology                      | 13        | 2.66%   |
| Qualcomm Atheros Communications        | 9         | 1.84%   |
| Broadcom Limited                       | 9         | 1.84%   |
| Samsung Electronics                    | 8         | 1.64%   |
| TP-Link                                | 7         | 1.43%   |
| MediaTek                               | 6         | 1.23%   |
| Huawei Technologies                    | 5         | 1.02%   |
| NetGear                                | 4         | 0.82%   |
| ASUSTek Computer                       | 4         | 0.82%   |
| Xiaomi                                 | 3         | 0.61%   |
| Ralink                                 | 3         | 0.61%   |
| Nvidia                                 | 3         | 0.61%   |
| Microsoft                              | 3         | 0.61%   |
| Marvell Technology Group               | 3         | 0.61%   |
| D-Link System                          | 3         | 0.61%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.41%   |
| Linksys                                | 2         | 0.41%   |
| ASIX Electronics                       | 2         | 0.41%   |
| ZyXEL Communications                   | 1         | 0.2%    |
| vivo                                   | 1         | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.2%    |
| Sagem                                  | 1         | 0.2%    |
| Realtek                                | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| ICS Advent                             | 1         | 0.2%    |
| Gemtek                                 | 1         | 0.2%    |
| Ericsson Business Mobile Networks      | 1         | 0.2%    |
| Davicom Semiconductor                  | 1         | 0.2%    |
| D-Link                                 | 1         | 0.2%    |
| Arduino SA                             | 1         | 0.2%    |
| Apple                                  | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 16.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 5.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.07%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.55%   |
| Intel Wireless 7265                                               | 9         | 1.55%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.21%   |
| Intel Wireless 7260                                               | 7         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 6         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.04%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 6         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.04%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.86%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 5         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.86%   |
| Intel Wireless 8260                                               | 5         | 0.86%   |
| Intel Wireless 3165                                               | 5         | 0.86%   |
| Intel Wireless 3160                                               | 5         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.69%   |
| Realtek 802.11ac NIC                                              | 4         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.69%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.52%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 3         | 0.52%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 3         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.52%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 3         | 0.52%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.52%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 121       | 38.78%  |
| Realtek Semiconductor           | 61        | 19.55%  |
| Qualcomm Atheros                | 41        | 13.14%  |
| Broadcom                        | 24        | 7.69%   |
| Ralink Technology               | 13        | 4.17%   |
| Qualcomm Atheros Communications | 9         | 2.88%   |
| TP-Link                         | 7         | 2.24%   |
| Broadcom Limited                | 7         | 2.24%   |
| NetGear                         | 4         | 1.28%   |
| MediaTek                        | 4         | 1.28%   |
| ASUSTek Computer                | 4         | 1.28%   |
| Ralink                          | 3         | 0.96%   |
| Microsoft                       | 3         | 0.96%   |
| Marvell Technology Group        | 3         | 0.96%   |
| Linksys                         | 2         | 0.64%   |
| ZyXEL Communications            | 1         | 0.32%   |
| Sagem                           | 1         | 0.32%   |
| Realtek                         | 1         | 0.32%   |
| Gemtek                          | 1         | 0.32%   |
| D-Link System                   | 1         | 0.32%   |
| D-Link                          | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 3.83%   |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 2.88%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.88%   |
| Intel Wireless 7265                                                     | 9         | 2.88%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 2.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.24%   |
| Intel Wireless 7260                                                     | 7         | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.24%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 6         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 6         | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 5         | 1.6%    |
| Intel Wireless 8260                                                     | 5         | 1.6%    |
| Intel Wireless 3165                                                     | 5         | 1.6%    |
| Intel Wireless 3160                                                     | 5         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.28%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.28%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.96%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 3         | 0.96%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 3         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 0.96%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 3         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.96%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 3         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.64%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.64%   |
| Ralink RT5372 Wireless Adapter                                          | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.64%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.64%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.64%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.64%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.64%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 140       | 55.34%  |
| Intel                 | 55        | 21.74%  |
| Qualcomm Atheros      | 21        | 8.3%    |
| Broadcom              | 9         | 3.56%   |
| Samsung Electronics   | 8         | 3.16%   |
| Xiaomi                | 3         | 1.19%   |
| Nvidia                | 3         | 1.19%   |
| MediaTek              | 2         | 0.79%   |
| D-Link System         | 2         | 0.79%   |
| Broadcom Limited      | 2         | 0.79%   |
| ASIX Electronics      | 2         | 0.79%   |
| vivo                  | 1         | 0.4%    |
| Lenovo                | 1         | 0.4%    |
| ICS Advent            | 1         | 0.4%    |
| Huawei Technologies   | 1         | 0.4%    |
| Davicom Semiconductor | 1         | 0.4%    |
| Apple                 | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 36.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 12.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.11%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 1.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.56%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.17%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.17%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.17%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.39%   |
| vivo 1806                                                         | 1         | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.39%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.39%   |
| MediaTek TECNO SPARK 6 Go                                         | 1         | 0.39%   |
| MediaTek TECNO SPARK 3                                            | 1         | 0.39%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.39%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.39%   |
| Intel Ethernet controller                                         | 1         | 0.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.39%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.39%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.39%   |
| Huawei COL-L29                                                    | 1         | 0.39%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 0.39%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.39%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 265       | 52.06%  |
| Ethernet | 235       | 46.17%  |
| Modem    | 5         | 0.98%   |
| Unknown  | 4         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 215       | 69.35%  |
| Ethernet | 93        | 30%     |
| Unknown  | 2         | 0.65%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 167       | 57.99%  |
| 1     | 112       | 38.89%  |
| 3     | 5         | 1.74%   |
| 0     | 4         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 242       | 83.16%  |
| Yes     | 48        | 16.49%  |
| Unknown | 1         | 0.34%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 48.48%  |
| Qualcomm Atheros Communications | 20        | 10.1%   |
| Realtek Semiconductor           | 19        | 9.6%    |
| Broadcom                        | 13        | 6.57%   |
| Cambridge Silicon Radio         | 10        | 5.05%   |
| Apple                           | 7         | 3.54%   |
| Lite-On Technology              | 6         | 3.03%   |
| Foxconn / Hon Hai               | 6         | 3.03%   |
| IMC Networks                    | 5         | 2.53%   |
| Dell                            | 4         | 2.02%   |
| Toshiba                         | 3         | 1.52%   |
| MediaTek                        | 3         | 1.52%   |
| Marvell Semiconductor           | 3         | 1.52%   |
| Realtek                         | 1         | 0.51%   |
| Ralink                          | 1         | 0.51%   |
| Dynex                           | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 20.2%   |
| Intel Bluetooth Device                                                              | 19        | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 9.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.05%   |
| Realtek Bluetooth Radio                                                             | 9         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 3.54%   |
| Intel AX200 Bluetooth                                                               | 6         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.02%   |
| IMC Networks Bluetooth Device                                                       | 4         | 2.02%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.02%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.02%   |
| MediaTek Wireless_Device                                                            | 3         | 1.52%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.52%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.01%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.01%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.01%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.01%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.01%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.51%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.51%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.51%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.51%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.51%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.51%   |
| Lite-On Wireless_Device                                                             | 1         | 0.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.51%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.51%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.51%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.51%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.51%   |
| Dynex BCM20702A0                                                                    | 1         | 0.51%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.51%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.51%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.51%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 221       | 60.22%  |
| AMD                    | 73        | 19.89%  |
| Nvidia                 | 60        | 16.35%  |
| C-Media Electronics    | 4         | 1.09%   |
| Yamaha                 | 1         | 0.27%   |
| SteelSeries ApS        | 1         | 0.27%   |
| Logitech               | 1         | 0.27%   |
| Lenovo                 | 1         | 0.27%   |
| GYROCOM C&C            | 1         | 0.27%   |
| Guillemot              | 1         | 0.27%   |
| GN Netcom              | 1         | 0.27%   |
| Generalplus Technology | 1         | 0.27%   |
| Apple                  | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 6.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 5.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 4.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.1%    |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.1%    |
| AMD FCH Azalia Controller                                                                         | 14        | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 2.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.44%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.77%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.11%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.11%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.11%   |
| Nvidia Audio device                                                                               | 4         | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.44%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.44%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.44%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.44%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.44%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.44%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 28.78%  |
| SK hynix            | 32        | 15.61%  |
| Micron Technology   | 28        | 13.66%  |
| Unknown             | 19        | 9.27%   |
| Crucial             | 16        | 7.8%    |
| Kingston            | 15        | 7.32%   |
| Corsair             | 8         | 3.9%    |
| Ramaxel Technology  | 6         | 2.93%   |
| Elpida              | 6         | 2.93%   |
| G.Skill             | 4         | 1.95%   |
| Nanya Technology    | 3         | 1.46%   |
| A-DATA Technology   | 3         | 1.46%   |
| Unknown (ABCD)      | 2         | 0.98%   |
| Team                | 1         | 0.49%   |
| Silicon Power       | 1         | 0.49%   |
| Saikano             | 1         | 0.49%   |
| S                   | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 2.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 2.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 1.4%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 3         | 1.4%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 3         | 1.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 2         | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 2         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 2         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.93%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s            | 2         | 0.93%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s                | 2         | 0.93%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s                | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 2         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 2         | 0.93%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.93%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 0.93%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM                                         | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.47%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 1         | 0.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.47%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.47%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                              | 1         | 0.47%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                 | 1         | 0.47%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.47%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 43.26%  |
| DDR3    | 71        | 39.89%  |
| LPDDR4  | 9         | 5.06%   |
| LPDDR3  | 7         | 3.93%   |
| DDR2    | 7         | 3.93%   |
| Unknown | 4         | 2.25%   |
| SDRAM   | 2         | 1.12%   |
| DDR     | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 128       | 72.32%  |
| DIMM         | 33        | 18.64%  |
| Row Of Chips | 14        | 7.91%   |
| Chip         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 77        | 39.9%   |
| 8192  | 61        | 31.61%  |
| 16384 | 22        | 11.4%   |
| 2048  | 20        | 10.36%  |
| 1024  | 9         | 4.66%   |
| 32768 | 4         | 2.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 23.83%  |
| 2667    | 42        | 21.76%  |
| 3200    | 21        | 10.88%  |
| 2400    | 17        | 8.81%   |
| 1334    | 13        | 6.74%   |
| 2133    | 10        | 5.18%   |
| 1333    | 8         | 4.15%   |
| Unknown | 5         | 2.59%   |
| 1867    | 4         | 2.07%   |
| 1067    | 4         | 2.07%   |
| 3600    | 3         | 1.55%   |
| 3266    | 3         | 1.55%   |
| 1066    | 3         | 1.55%   |
| 667     | 3         | 1.55%   |
| 4267    | 2         | 1.04%   |
| 800     | 2         | 1.04%   |
| 4800    | 1         | 0.52%   |
| 3466    | 1         | 0.52%   |
| 2666    | 1         | 0.52%   |
| 2200    | 1         | 0.52%   |
| 1866    | 1         | 0.52%   |
| 533     | 1         | 0.52%   |
| 400     | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| HP OfficeJet Pro 7720 series | 1         | 50%     |
| Brother HL-1210W series      | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 27.18%  |
| Acer                                   | 24        | 11.65%  |
| Microdia                               | 19        | 9.22%   |
| IMC Networks                           | 18        | 8.74%   |
| Sunplus Innovation Technology          | 13        | 6.31%   |
| Realtek Semiconductor                  | 12        | 5.83%   |
| Quanta                                 | 8         | 3.88%   |
| Apple                                  | 8         | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.91%   |
| Ricoh                                  | 5         | 2.43%   |
| Logitech                               | 4         | 1.94%   |
| Suyin                                  | 3         | 1.46%   |
| Silicon Motion                         | 3         | 1.46%   |
| Samsung Electronics                    | 3         | 1.46%   |
| Luxvisions Innotech Limited            | 3         | 1.46%   |
| Lite-On Technology                     | 3         | 1.46%   |
| Alcor Micro                            | 3         | 1.46%   |
| Syntek                                 | 2         | 0.97%   |
| Microsoft                              | 2         | 0.97%   |
| LG Electronics                         | 2         | 0.97%   |
| Creative Technology                    | 2         | 0.97%   |
| Teslong Camera                         | 1         | 0.49%   |
| Razer USA                              | 1         | 0.49%   |
| Primax Electronics                     | 1         | 0.49%   |
| Jieli Technology                       | 1         | 0.49%   |
| Importek                               | 1         | 0.49%   |
| Goertek Electronics                    | 1         | 0.49%   |
| ALi                                    | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 3.85%   |
| Realtek Integrated_Webcam_HD                        | 6         | 2.88%   |
| Acer HD Webcam                                      | 6         | 2.88%   |
| IMC Networks Integrated Camera                      | 5         | 2.4%    |
| Chicony HD Webcam                                   | 5         | 2.4%    |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.92%   |
| Microdia Webcam Vitade AF                           | 4         | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.92%   |
| Chicony HP TrueVision HD                            | 4         | 1.92%   |
| Chicony HD User Facing                              | 4         | 1.92%   |
| Acer EasyCamera                                     | 4         | 1.92%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 1.44%   |
| Microdia PC Microscope camera                       | 3         | 1.44%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.44%   |
| Microdia Integrated Webcam                          | 3         | 1.44%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.44%   |
| Chicony USB2.0 Camera                               | 3         | 1.44%   |
| Chicony EasyCamera                                  | 3         | 1.44%   |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.44%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.44%   |
| Acer SunplusIT Integrated Camera                    | 3         | 1.44%   |
| Acer Integrated Camera                              | 3         | 1.44%   |
| Syntek Integrated Camera                            | 2         | 0.96%   |
| Sunplus HD WebCam                                   | 2         | 0.96%   |
| Realtek Integrated Webcam                           | 2         | 0.96%   |
| Quanta VGA WebCam                                   | 2         | 0.96%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.96%   |
| Microsoft LifeCam Rear                              | 2         | 0.96%   |
| Microsoft LifeCam Front                             | 2         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.96%   |
| Logitech HD Webcam C615                             | 2         | 0.96%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 0.96%   |
| IMC Networks HD Camera                              | 2         | 0.96%   |
| Creative Live! Cam Sync HD [VF0770]                 | 2         | 0.96%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.96%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 0.96%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.96%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.96%   |
| Chicony HP HD Camera                                | 2         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.96%   |
| Apple FaceTime HD Camera                            | 2         | 0.96%   |
| Acer Lenovo EasyCamera                              | 2         | 0.96%   |
| Acer HD Camera                                      | 2         | 0.96%   |
| Teslong Camera                                      | 1         | 0.48%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.48%   |
| Suyin HP Truevision HD                              | 1         | 0.48%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.48%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.48%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.48%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.48%   |
| Sunplus Integrated Camera                           | 1         | 0.48%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.48%   |
| Sunplus FHD Camera Microphone                       | 1         | 0.48%   |
| Sunplus Asus Webcam                                 | 1         | 0.48%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.48%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.48%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.48%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 48.57%  |
| Synaptics                  | 10        | 28.57%  |
| Shenzhen Goodix Technology | 3         | 8.57%   |
| LighTuning Technology      | 2         | 5.71%   |
| Elan Microelectronics      | 2         | 5.71%   |
| AuthenTec                  | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 8.57%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 8.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.57%   |
| Unknown                                                                    | 3         | 8.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 5.71%   |
| Validity Sensors VFS491                                                    | 2         | 5.71%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.71%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.71%   |
| Synaptics  WBDI                                                            | 2         | 5.71%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 5.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.86%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.86%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 8         | 53.33%  |
| Alcor Micro      | 4         | 26.67%  |
| SCM Microsystems | 1         | 6.67%   |
| OmniKey          | 1         | 6.67%   |
| O2 Micro         | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 6.67%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 184       | 63.01%  |
| 1     | 89        | 30.48%  |
| 2     | 18        | 6.16%   |
| 3     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 29.27%  |
| Net/wireless             | 23        | 18.7%   |
| Graphics card            | 20        | 16.26%  |
| Chipcard                 | 13        | 10.57%  |
| Multimedia controller    | 12        | 9.76%   |
| Camera                   | 7         | 5.69%   |
| Storage                  | 4         | 3.25%   |
| Network                  | 2         | 1.63%   |
| Storage/raid             | 1         | 0.81%   |
| Net/ethernet             | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |
| Communication controller | 1         | 0.81%   |
| Card reader              | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |

