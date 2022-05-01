Gentoo - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 928

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| HP            | ZBook 15 G3                 | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Dell          | G3 3500                     | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [b3985fd156](https://linux-hardware.org/?probe=b3985fd156) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a889f37319](https://linux-hardware.org/?probe=a889f37319) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [50b0cb93c7](https://linux-hardware.org/?probe=50b0cb93c7) | Apr 16, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [425620585b](https://linux-hardware.org/?probe=425620585b) | Apr 15, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| Acer          | Aspire E5-571G              | [b478ae5085](https://linux-hardware.org/?probe=b478ae5085) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [23ed880c8d](https://linux-hardware.org/?probe=23ed880c8d) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| MSI           | GE66 Raider 11UE            | [82b79674a9](https://linux-hardware.org/?probe=82b79674a9) | Apr 05, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [31bc256291](https://linux-hardware.org/?probe=31bc256291) | Mar 30, 2022 |
| MSI           | GE66 Raider 11UE            | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [e0ae9fa252](https://linux-hardware.org/?probe=e0ae9fa252) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| Apple         | MacBookPro11,3              | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| MSI           | MS-7A34                     | [a3cfb1ce48](https://linux-hardware.org/?probe=a3cfb1ce48) | Mar 18, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [bcbbb88250](https://linux-hardware.org/?probe=bcbbb88250) | Mar 17, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [aa5e521c49](https://linux-hardware.org/?probe=aa5e521c49) | Mar 09, 2022 |
| Framework     | Laptop                      | [15219c6b68](https://linux-hardware.org/?probe=15219c6b68) | Mar 08, 2022 |
| Framework     | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [8180499429](https://linux-hardware.org/?probe=8180499429) | Mar 04, 2022 |
| Toshiba       | Satellite L50-C             | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [ca3fe9963a](https://linux-hardware.org/?probe=ca3fe9963a) | Mar 02, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [0e7e6ce7e1](https://linux-hardware.org/?probe=0e7e6ce7e1) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [04e5a51e94](https://linux-hardware.org/?probe=04e5a51e94) | Feb 23, 2022 |
| Dell          | XPS 17 9710                 | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Dell          | XPS 17 9710                 | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [2fd76a0745](https://linux-hardware.org/?probe=2fd76a0745) | Feb 16, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| Acer          | Aspire E5-571G              | [2506ade681](https://linux-hardware.org/?probe=2506ade681) | Feb 09, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [7ecbb8ed25](https://linux-hardware.org/?probe=7ecbb8ed25) | Feb 09, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [7904674fda](https://linux-hardware.org/?probe=7904674fda) | Feb 02, 2022 |
| Samsung       | RC530/RC730                 | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| Acer          | Aspire E5-571G              | [1c5a3f10d3](https://linux-hardware.org/?probe=1c5a3f10d3) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Dell          | Precision 7520              | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [cd9e338125](https://linux-hardware.org/?probe=cd9e338125) | Jan 26, 2022 |
| HP            | ProBook 430 G7              | [f0d96ec1ea](https://linux-hardware.org/?probe=f0d96ec1ea) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Timi          | RedmiBook 13                | [b424ef43c2](https://linux-hardware.org/?probe=b424ef43c2) | Jan 25, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [56ec9cdd58](https://linux-hardware.org/?probe=56ec9cdd58) | Jan 23, 2022 |
| Dell          | XPS 15 9570                 | [fce4bfa776](https://linux-hardware.org/?probe=fce4bfa776) | Jan 23, 2022 |
| Dell          | XPS 15 9570                 | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| MSI           | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Dell          | XPS 17 9710                 | [597fae9cb6](https://linux-hardware.org/?probe=597fae9cb6) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Acer          | Aspire E5-571G              | [bc4098b5ef](https://linux-hardware.org/?probe=bc4098b5ef) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Apple         | MacBookPro6,2               | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| Acer          | Aspire E5-571G              | [e522a5a92a](https://linux-hardware.org/?probe=e522a5a92a) | Jan 12, 2022 |
| Acer          | Swift SF314-59              | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Samsung       | 700T1C                      | [349d306d37](https://linux-hardware.org/?probe=349d306d37) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| HUAWEI        | HVY-WXX9                    | [f6376ab7d5](https://linux-hardware.org/?probe=f6376ab7d5) | Jan 10, 2022 |
| Acer          | Aspire E5-571G              | [2f20abfd2f](https://linux-hardware.org/?probe=2f20abfd2f) | Jan 09, 2022 |
| Acer          | Aspire E5-571G              | [d52b087b18](https://linux-hardware.org/?probe=d52b087b18) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [407b47a081](https://linux-hardware.org/?probe=407b47a081) | Jan 06, 2022 |
| Acer          | Aspire E5-571G              | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| Dell          | Precision 7560              | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [06c202dbf5](https://linux-hardware.org/?probe=06c202dbf5) | Jan 01, 2022 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [ac139db0b3](https://linux-hardware.org/?probe=ac139db0b3) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [403fbb398a](https://linux-hardware.org/?probe=403fbb398a) | Dec 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | Inspiron 15 5510            | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Framework     | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Dell          | Latitude 5420               | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| Samsung       | 700T1C                      | [f63266db56](https://linux-hardware.org/?probe=f63266db56) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [67b6be4367](https://linux-hardware.org/?probe=67b6be4367) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [cda6cea62a](https://linux-hardware.org/?probe=cda6cea62a) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [4458df4b9b](https://linux-hardware.org/?probe=4458df4b9b) | Nov 26, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Timi          | A35                         | [05d29d4f49](https://linux-hardware.org/?probe=05d29d4f49) | Nov 25, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6cc3a7d87b](https://linux-hardware.org/?probe=6cc3a7d87b) | Nov 24, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [1bb2b21d60](https://linux-hardware.org/?probe=1bb2b21d60) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| HP            | Compaq 6730b (KE717AV)      | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [069285656d](https://linux-hardware.org/?probe=069285656d) | Nov 18, 2021 |
| HP            | ProBook 430 G5              | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [49148de6c4](https://linux-hardware.org/?probe=49148de6c4) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| HP            | ProBook 430 G5              | [ebe62afb01](https://linux-hardware.org/?probe=ebe62afb01) | Nov 09, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Dell          | Latitude E7440              | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [98cddd6e21](https://linux-hardware.org/?probe=98cddd6e21) | Nov 04, 2021 |
| Samsung       | RC530/RC730                 | [a4d9d06231](https://linux-hardware.org/?probe=a4d9d06231) | Nov 02, 2021 |
| Dell          | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Dell          | Latitude 5520               | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| Dell          | Latitude E6530              | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| HP            | Pavilion Notebook           | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cb7d97fd9e](https://linux-hardware.org/?probe=cb7d97fd9e) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [280b8af5cc](https://linux-hardware.org/?probe=280b8af5cc) | Oct 23, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [f34760d3fe](https://linux-hardware.org/?probe=f34760d3fe) | Oct 16, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [fa58c39541](https://linux-hardware.org/?probe=fa58c39541) | Oct 09, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Samsung       | RC530/RC730                 | [931664ed89](https://linux-hardware.org/?probe=931664ed89) | Oct 04, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [8debdfa001](https://linux-hardware.org/?probe=8debdfa001) | Oct 02, 2021 |
| ASUSTek       | Unknown                     | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| Dell          | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [5c7ce8f98b](https://linux-hardware.org/?probe=5c7ce8f98b) | Sep 24, 2021 |
| ASUSTek       | GX501VIK                    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| Samsung       | RC530/RC730                 | [4aa6a34c0c](https://linux-hardware.org/?probe=4aa6a34c0c) | Sep 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [e3b8b92fdb](https://linux-hardware.org/?probe=e3b8b92fdb) | Sep 17, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| Dell          | Latitude 5410               | [97ed647d4c](https://linux-hardware.org/?probe=97ed647d4c) | Sep 10, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [9dcddb807d](https://linux-hardware.org/?probe=9dcddb807d) | Sep 10, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [572c0c5198](https://linux-hardware.org/?probe=572c0c5198) | Sep 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [36bf3dd55d](https://linux-hardware.org/?probe=36bf3dd55d) | Sep 09, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| Dell          | Precision 7560              | [3fa67e38db](https://linux-hardware.org/?probe=3fa67e38db) | Sep 08, 2021 |
| HP            | Pavilion g6                 | [1161032a20](https://linux-hardware.org/?probe=1161032a20) | Sep 08, 2021 |
| Dell          | Precision 7560              | [03d7773132](https://linux-hardware.org/?probe=03d7773132) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [5a43bd347f](https://linux-hardware.org/?probe=5a43bd347f) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| ASUSTek       | X550ZA                      | [0d41969b6b](https://linux-hardware.org/?probe=0d41969b6b) | Sep 02, 2021 |
| Dell          | Latitude E6510              | [2ab208b5cd](https://linux-hardware.org/?probe=2ab208b5cd) | Sep 02, 2021 |
| HP            | 255 G6 Notebook PC          | [4f71a8ad02](https://linux-hardware.org/?probe=4f71a8ad02) | Sep 01, 2021 |
| HP            | ZBook 15 G3                 | [d6872bd9e9](https://linux-hardware.org/?probe=d6872bd9e9) | Sep 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [3319bbb803](https://linux-hardware.org/?probe=3319bbb803) | Aug 31, 2021 |
| HP            | 255 G6 Notebook PC          | [3076551390](https://linux-hardware.org/?probe=3076551390) | Aug 30, 2021 |
| IBM           | ThinkPad T42 2373V4F        | [2362291c05](https://linux-hardware.org/?probe=2362291c05) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [5a606b504c](https://linux-hardware.org/?probe=5a606b504c) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [2af8736235](https://linux-hardware.org/?probe=2af8736235) | Aug 28, 2021 |
| HP            | 255 G6 Notebook PC          | [a8c5a1a4c7](https://linux-hardware.org/?probe=a8c5a1a4c7) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [aabbe0dbcc](https://linux-hardware.org/?probe=aabbe0dbcc) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| HP            | 255 G6 Notebook PC          | [b776f7f3b7](https://linux-hardware.org/?probe=b776f7f3b7) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [62ba09ac38](https://linux-hardware.org/?probe=62ba09ac38) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 23259H1       | [fb125d2779](https://linux-hardware.org/?probe=fb125d2779) | Aug 25, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [badf30135c](https://linux-hardware.org/?probe=badf30135c) | Aug 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4736a01d82](https://linux-hardware.org/?probe=4736a01d82) | Aug 17, 2021 |
| Dell          | Inspiron 5415               | [909e2cdc93](https://linux-hardware.org/?probe=909e2cdc93) | Aug 15, 2021 |
| Dell          | Inspiron 5415               | [96cd32b528](https://linux-hardware.org/?probe=96cd32b528) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef36f1dc4d](https://linux-hardware.org/?probe=ef36f1dc4d) | Aug 15, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [7a50fc3510](https://linux-hardware.org/?probe=7a50fc3510) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c45478eae5](https://linux-hardware.org/?probe=c45478eae5) | Aug 12, 2021 |
| Dell          | Inspiron 5415               | [63594290cf](https://linux-hardware.org/?probe=63594290cf) | Aug 11, 2021 |
| TUXEDO        | Book XC1711                 | [806e284c8a](https://linux-hardware.org/?probe=806e284c8a) | Aug 11, 2021 |
| Jumper        | EZpad                       | [da2436c208](https://linux-hardware.org/?probe=da2436c208) | Aug 11, 2021 |
| Jumper        | EZpad                       | [6215ba7396](https://linux-hardware.org/?probe=6215ba7396) | Aug 10, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [a2eec215a6](https://linux-hardware.org/?probe=a2eec215a6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [660b357dde](https://linux-hardware.org/?probe=660b357dde) | Aug 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ddf6a2277a](https://linux-hardware.org/?probe=ddf6a2277a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4ce0735262](https://linux-hardware.org/?probe=4ce0735262) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | X510UR                      | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| TUXEDO        | Book_XA1510                 | [f4f777ed12](https://linux-hardware.org/?probe=f4f777ed12) | Aug 03, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [d8386898c1](https://linux-hardware.org/?probe=d8386898c1) | Jul 31, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [380758e335](https://linux-hardware.org/?probe=380758e335) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a5a11a0de1](https://linux-hardware.org/?probe=a5a11a0de1) | Jul 28, 2021 |
| Dell          | XPS 15 7590                 | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [e5dd847990](https://linux-hardware.org/?probe=e5dd847990) | Jul 24, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3de3129139](https://linux-hardware.org/?probe=3de3129139) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [6cba1afdb8](https://linux-hardware.org/?probe=6cba1afdb8) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6a7c7d9d8](https://linux-hardware.org/?probe=c6a7c7d9d8) | Jul 19, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [2830192011](https://linux-hardware.org/?probe=2830192011) | Jul 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [483690e890](https://linux-hardware.org/?probe=483690e890) | Jul 14, 2021 |
| Dell          | Latitude E6430              | [3dc281ca01](https://linux-hardware.org/?probe=3dc281ca01) | Jul 13, 2021 |
| Dell          | XPS 13 9310                 | [6835266a32](https://linux-hardware.org/?probe=6835266a32) | Jul 10, 2021 |
| Dell          | Latitude E6430              | [f5a73f4d90](https://linux-hardware.org/?probe=f5a73f4d90) | Jul 09, 2021 |
| Dell          | Latitude E6430              | [8d685287ce](https://linux-hardware.org/?probe=8d685287ce) | Jul 09, 2021 |
| HP            | Pavilion Notebook           | [68c41ed42b](https://linux-hardware.org/?probe=68c41ed42b) | Jul 08, 2021 |
| HP            | Pavilion Notebook           | [5a6fca486a](https://linux-hardware.org/?probe=5a6fca486a) | Jul 08, 2021 |
| Acer          | Aspire A315-32              | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| HP            | Pro Tablet 608 G1           | [c1a115b721](https://linux-hardware.org/?probe=c1a115b721) | Jun 28, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [5d9bde452b](https://linux-hardware.org/?probe=5d9bde452b) | Jun 27, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| HUAWEI        | HN-WX9X                     | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Apple         | MacBookPro8,3               | [1453a09197](https://linux-hardware.org/?probe=1453a09197) | Jun 25, 2021 |
| Apple         | MacBookPro8,3               | [94f589e95c](https://linux-hardware.org/?probe=94f589e95c) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [8ac09d11a4](https://linux-hardware.org/?probe=8ac09d11a4) | Jun 20, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [70c10f988f](https://linux-hardware.org/?probe=70c10f988f) | Jun 20, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [613754139b](https://linux-hardware.org/?probe=613754139b) | Jun 20, 2021 |
| Dell          | Latitude E7440              | [9302b47a78](https://linux-hardware.org/?probe=9302b47a78) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7b589175d7](https://linux-hardware.org/?probe=7b589175d7) | Jun 14, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [8d5844241c](https://linux-hardware.org/?probe=8d5844241c) | Jun 13, 2021 |
| HP            | Laptop 14-dk0xxx            | [9b07d82840](https://linux-hardware.org/?probe=9b07d82840) | Jun 12, 2021 |
| Acer          | Aspire A315-42              | [efab65cf1d](https://linux-hardware.org/?probe=efab65cf1d) | Jun 12, 2021 |
| Acer          | Aspire E5-571G              | [b3ffc705fc](https://linux-hardware.org/?probe=b3ffc705fc) | Jun 11, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [f1d0d2bda6](https://linux-hardware.org/?probe=f1d0d2bda6) | Jun 09, 2021 |
| Lenovo        | G50-30 80G0                 | [ab9da369c0](https://linux-hardware.org/?probe=ab9da369c0) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [407abb051f](https://linux-hardware.org/?probe=407abb051f) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e6aba1341](https://linux-hardware.org/?probe=5e6aba1341) | Jun 09, 2021 |
| Dell          | Inspiron 7375               | [7704e5289b](https://linux-hardware.org/?probe=7704e5289b) | Jun 07, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [7e7084b78c](https://linux-hardware.org/?probe=7e7084b78c) | Jun 06, 2021 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [f8e58be450](https://linux-hardware.org/?probe=f8e58be450) | Jun 03, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | [b571e885e2](https://linux-hardware.org/?probe=b571e885e2) | Jun 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [f3f3c323ab](https://linux-hardware.org/?probe=f3f3c323ab) | Jun 03, 2021 |
| Dell          | XPS 13 9300                 | [e85b21841c](https://linux-hardware.org/?probe=e85b21841c) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | [8a7fbf7026](https://linux-hardware.org/?probe=8a7fbf7026) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | [fbbaf8088b](https://linux-hardware.org/?probe=fbbaf8088b) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | [024ffa0922](https://linux-hardware.org/?probe=024ffa0922) | Jun 01, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [32f7b77b77](https://linux-hardware.org/?probe=32f7b77b77) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| Dell          | Inspiron 5415               | [bbf1e95976](https://linux-hardware.org/?probe=bbf1e95976) | May 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Inspiron 5415               | [abc4464787](https://linux-hardware.org/?probe=abc4464787) | May 26, 2021 |
| Dell          | Inspiron 5415               | [27c5c40e12](https://linux-hardware.org/?probe=27c5c40e12) | May 26, 2021 |
| Lenovo        | ThinkPad X230 2325BF1       | [0d334af224](https://linux-hardware.org/?probe=0d334af224) | May 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| HP            | Pavilion Notebook           | [10cf947d23](https://linux-hardware.org/?probe=10cf947d23) | May 24, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [81fb83e4cd](https://linux-hardware.org/?probe=81fb83e4cd) | May 23, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| ASUSTek       | X550ZA                      | [aef8ea73d8](https://linux-hardware.org/?probe=aef8ea73d8) | May 20, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [8a05529e0c](https://linux-hardware.org/?probe=8a05529e0c) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | [6daf66a738](https://linux-hardware.org/?probe=6daf66a738) | May 18, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [50b75a0212](https://linux-hardware.org/?probe=50b75a0212) | May 17, 2021 |
| Lenovo        | Yoga 2 13 20344             | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [8b13fead92](https://linux-hardware.org/?probe=8b13fead92) | May 15, 2021 |
| Samsung       | RC530/RC730                 | [1da22350d7](https://linux-hardware.org/?probe=1da22350d7) | May 15, 2021 |
| Samsung       | RC530/RC730                 | [f79cbc4e24](https://linux-hardware.org/?probe=f79cbc4e24) | May 15, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| HP            | Unknown                     | [d11a5ff11b](https://linux-hardware.org/?probe=d11a5ff11b) | May 13, 2021 |
| Dell          | Inspiron 3135               | [2773a72a9b](https://linux-hardware.org/?probe=2773a72a9b) | May 10, 2021 |
| HP            | ProBook 445 G7              | [6c504fbdf0](https://linux-hardware.org/?probe=6c504fbdf0) | May 10, 2021 |
| HP            | Pavilion Notebook           | [7e483f822d](https://linux-hardware.org/?probe=7e483f822d) | May 09, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [5b8198d382](https://linux-hardware.org/?probe=5b8198d382) | May 08, 2021 |
| HP            | Unknown                     | [923ee16061](https://linux-hardware.org/?probe=923ee16061) | May 08, 2021 |
| HP            | Pavilion Notebook           | [993f3384ed](https://linux-hardware.org/?probe=993f3384ed) | May 08, 2021 |
| Dell          | Inspiron 3135               | [9bcfced245](https://linux-hardware.org/?probe=9bcfced245) | May 07, 2021 |
| Dell          | XPS 13 9310                 | [c3e8ad6826](https://linux-hardware.org/?probe=c3e8ad6826) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| Dell          | G3 3500                     | [f6624959c4](https://linux-hardware.org/?probe=f6624959c4) | May 05, 2021 |
| Dell          | G3 3500                     | [03ad0892de](https://linux-hardware.org/?probe=03ad0892de) | May 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [761feac522](https://linux-hardware.org/?probe=761feac522) | May 04, 2021 |
| HP            | Unknown                     | [3b8a91fb03](https://linux-hardware.org/?probe=3b8a91fb03) | May 03, 2021 |
| HP            | Pavilion Notebook           | [79a8f7d7d8](https://linux-hardware.org/?probe=79a8f7d7d8) | May 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1d95f1feca](https://linux-hardware.org/?probe=1d95f1feca) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | Pavilion Notebook           | [5feda7dcc9](https://linux-hardware.org/?probe=5feda7dcc9) | May 02, 2021 |
| Dell          | Inspiron 3542               | [aa72a49a15](https://linux-hardware.org/?probe=aa72a49a15) | Apr 30, 2021 |
| Lenovo        | ThinkPad P50 20EN0006UK     | [6f9d0f45bb](https://linux-hardware.org/?probe=6f9d0f45bb) | Apr 30, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [83c0ac9888](https://linux-hardware.org/?probe=83c0ac9888) | Apr 30, 2021 |
| Dell          | G3 3500                     | [db309111ed](https://linux-hardware.org/?probe=db309111ed) | Apr 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0bbb4df743](https://linux-hardware.org/?probe=0bbb4df743) | Apr 27, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [2ed72a5012](https://linux-hardware.org/?probe=2ed72a5012) | Apr 22, 2021 |
| Dell          | G3 3500                     | [d1a4723065](https://linux-hardware.org/?probe=d1a4723065) | Apr 20, 2021 |
| Dell          | G3 3500                     | [3295e38ea9](https://linux-hardware.org/?probe=3295e38ea9) | Apr 20, 2021 |
| Dell          | XPS 17 9700                 | [144d6867d6](https://linux-hardware.org/?probe=144d6867d6) | Apr 18, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b10d744c6c](https://linux-hardware.org/?probe=b10d744c6c) | Apr 18, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [6d94f31cd6](https://linux-hardware.org/?probe=6d94f31cd6) | Apr 14, 2021 |
| Fujitsu       | LIFEBOOK T901               | [cb4c0ac9a9](https://linux-hardware.org/?probe=cb4c0ac9a9) | Apr 13, 2021 |
| TUXEDO        | N24_25BU                    | [32cc7aa6c2](https://linux-hardware.org/?probe=32cc7aa6c2) | Apr 12, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [89d46a7375](https://linux-hardware.org/?probe=89d46a7375) | Apr 12, 2021 |
| HP            | Pavilion Notebook           | [5159073240](https://linux-hardware.org/?probe=5159073240) | Apr 11, 2021 |
| HP            | Pavilion Notebook           | [99daea7567](https://linux-hardware.org/?probe=99daea7567) | Apr 11, 2021 |
| Dell          | G3 3500                     | [3510f864f1](https://linux-hardware.org/?probe=3510f864f1) | Apr 10, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5120fd67](https://linux-hardware.org/?probe=7e5120fd67) | Apr 06, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [eac55aff15](https://linux-hardware.org/?probe=eac55aff15) | Apr 05, 2021 |
| Dell          | Latitude X1                 | [a35f6c0969](https://linux-hardware.org/?probe=a35f6c0969) | Apr 05, 2021 |
| Dell          | Latitude 5480               | [a61529e37c](https://linux-hardware.org/?probe=a61529e37c) | Apr 03, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| Dell          | Latitude X1                 | [1e053513e0](https://linux-hardware.org/?probe=1e053513e0) | Apr 03, 2021 |
| MSI           | GE62 6QD                    | [d76949a11c](https://linux-hardware.org/?probe=d76949a11c) | Apr 01, 2021 |
| Acer          | Aspire E5-571G              | [c730c15bc5](https://linux-hardware.org/?probe=c730c15bc5) | Mar 31, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [e11852c937](https://linux-hardware.org/?probe=e11852c937) | Mar 26, 2021 |
| ASUSTek       | N501VW                      | [46863f1f90](https://linux-hardware.org/?probe=46863f1f90) | Mar 24, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [5330bba5eb](https://linux-hardware.org/?probe=5330bba5eb) | Mar 19, 2021 |
| ASUSTek       | 1000H                       | [eda3ceb029](https://linux-hardware.org/?probe=eda3ceb029) | Mar 18, 2021 |
| Dell          | XPS 13 9380                 | [a8f5a8232e](https://linux-hardware.org/?probe=a8f5a8232e) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [65f8817baf](https://linux-hardware.org/?probe=65f8817baf) | Mar 17, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [9378abad5c](https://linux-hardware.org/?probe=9378abad5c) | Mar 16, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ed79695034](https://linux-hardware.org/?probe=ed79695034) | Mar 12, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [ff1e5f1771](https://linux-hardware.org/?probe=ff1e5f1771) | Mar 12, 2021 |
| Dell          | Inspiron 3537               | [2ed429a812](https://linux-hardware.org/?probe=2ed429a812) | Mar 09, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| Dell          | Latitude 5410               | [f7ff0d1881](https://linux-hardware.org/?probe=f7ff0d1881) | Mar 07, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ceb4b7fdab](https://linux-hardware.org/?probe=ceb4b7fdab) | Mar 06, 2021 |
| Dell          | Latitude 5410               | [2f64a4536e](https://linux-hardware.org/?probe=2f64a4536e) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [04c46743cb](https://linux-hardware.org/?probe=04c46743cb) | Mar 05, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [ebc962c6c8](https://linux-hardware.org/?probe=ebc962c6c8) | Mar 05, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [513b3181df](https://linux-hardware.org/?probe=513b3181df) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d7384efac7](https://linux-hardware.org/?probe=d7384efac7) | Mar 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb357781c5](https://linux-hardware.org/?probe=eb357781c5) | Mar 04, 2021 |
| HP            | Pavilion Notebook           | [18e2e1ba5d](https://linux-hardware.org/?probe=18e2e1ba5d) | Mar 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ff0e82cc06](https://linux-hardware.org/?probe=ff0e82cc06) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [f343af14eb](https://linux-hardware.org/?probe=f343af14eb) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| HP            | ProBook 450 G5              | [0cf52b6b45](https://linux-hardware.org/?probe=0cf52b6b45) | Mar 03, 2021 |
| ASUSTek       | ASUSPRO P2540FAC_P2540FA    | [723ba4e443](https://linux-hardware.org/?probe=723ba4e443) | Feb 28, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [f9cf2ced7e](https://linux-hardware.org/?probe=f9cf2ced7e) | Feb 28, 2021 |
| Dell          | G3 3500                     | [784b943c30](https://linux-hardware.org/?probe=784b943c30) | Feb 28, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f2ce82aade](https://linux-hardware.org/?probe=f2ce82aade) | Feb 27, 2021 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [83b0002691](https://linux-hardware.org/?probe=83b0002691) | Feb 27, 2021 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [b8542f3302](https://linux-hardware.org/?probe=b8542f3302) | Feb 27, 2021 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [922d2a406f](https://linux-hardware.org/?probe=922d2a406f) | Feb 26, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | [b443d08b6f](https://linux-hardware.org/?probe=b443d08b6f) | Feb 26, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| TUXEDO        | Unknown                     | [ad91e37e92](https://linux-hardware.org/?probe=ad91e37e92) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | ProBook 450 G5              | [e5dd23490f](https://linux-hardware.org/?probe=e5dd23490f) | Feb 20, 2021 |
| HP            | EliteBook 820 G3            | [e9e3b904a9](https://linux-hardware.org/?probe=e9e3b904a9) | Feb 19, 2021 |
| HP            | ProBook 450 G5              | [757c263c73](https://linux-hardware.org/?probe=757c263c73) | Feb 17, 2021 |
| ASUSTek       | G2SV                        | [2dcd0e4e69](https://linux-hardware.org/?probe=2dcd0e4e69) | Feb 15, 2021 |
| ASUSTek       | G2SV                        | [5b8e446be1](https://linux-hardware.org/?probe=5b8e446be1) | Feb 15, 2021 |
| TUXEDO        | Unknown                     | [c1b424bc28](https://linux-hardware.org/?probe=c1b424bc28) | Feb 15, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [fbf20e8baa](https://linux-hardware.org/?probe=fbf20e8baa) | Feb 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [418d6ee98e](https://linux-hardware.org/?probe=418d6ee98e) | Feb 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d2a976e336](https://linux-hardware.org/?probe=d2a976e336) | Feb 13, 2021 |
| HP            | OMEN by HP Laptop           | [d20f245092](https://linux-hardware.org/?probe=d20f245092) | Feb 13, 2021 |
| Acer          | Nitro AN515-53              | [66e023417c](https://linux-hardware.org/?probe=66e023417c) | Feb 13, 2021 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [de910b3b6f](https://linux-hardware.org/?probe=de910b3b6f) | Feb 11, 2021 |
| HP            | EliteBook 820 G3            | [0dcb414448](https://linux-hardware.org/?probe=0dcb414448) | Feb 10, 2021 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [c77ec688d3](https://linux-hardware.org/?probe=c77ec688d3) | Feb 08, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [d45ff60cd3](https://linux-hardware.org/?probe=d45ff60cd3) | Feb 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [49814ed1ce](https://linux-hardware.org/?probe=49814ed1ce) | Feb 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1df927bea6](https://linux-hardware.org/?probe=1df927bea6) | Feb 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| Dell          | XPS 13 9370                 | [8e541c3c46](https://linux-hardware.org/?probe=8e541c3c46) | Feb 01, 2021 |
| Dell          | G3 3500                     | [e83eb8401d](https://linux-hardware.org/?probe=e83eb8401d) | Jan 29, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| HP            | Pavilion Notebook           | [ce1a55614c](https://linux-hardware.org/?probe=ce1a55614c) | Jan 28, 2021 |
| HP            | Unknown                     | [b7892094b3](https://linux-hardware.org/?probe=b7892094b3) | Jan 27, 2021 |
| Chuwi         | UBook Pro                   | [d82fb9fdaf](https://linux-hardware.org/?probe=d82fb9fdaf) | Jan 26, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [21f3792542](https://linux-hardware.org/?probe=21f3792542) | Jan 26, 2021 |
| Google        | Peppy                       | [0b7e4ccb8e](https://linux-hardware.org/?probe=0b7e4ccb8e) | Jan 26, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [88cf2bc0f5](https://linux-hardware.org/?probe=88cf2bc0f5) | Jan 15, 2021 |
| Lenovo        | Unknown                     | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| IT Channel... | PA70ES                      | [f5671ea0b0](https://linux-hardware.org/?probe=f5671ea0b0) | Jan 11, 2021 |
| ASUSTek       | X555LJ                      | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [ae10447c4d](https://linux-hardware.org/?probe=ae10447c4d) | Jan 08, 2021 |
| HP            | Pavilion dm1                | [db518ed539](https://linux-hardware.org/?probe=db518ed539) | Jan 08, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [ae395b2f7a](https://linux-hardware.org/?probe=ae395b2f7a) | Jan 06, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| ASUSTek       | A7V                         | [79a40b4127](https://linux-hardware.org/?probe=79a40b4127) | Jan 06, 2021 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [d6cb8dec76](https://linux-hardware.org/?probe=d6cb8dec76) | Jan 05, 2021 |
| HP            | ZBook 15 G4                 | [46ee3cd25c](https://linux-hardware.org/?probe=46ee3cd25c) | Jan 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [367d882a57](https://linux-hardware.org/?probe=367d882a57) | Jan 04, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [39cec3e63e](https://linux-hardware.org/?probe=39cec3e63e) | Jan 03, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [96374442c4](https://linux-hardware.org/?probe=96374442c4) | Jan 02, 2021 |
| Unknown       | Unknown                     | [1eb453e2b1](https://linux-hardware.org/?probe=1eb453e2b1) | Jan 02, 2021 |
| Unknown       | Unknown                     | [fee86bed02](https://linux-hardware.org/?probe=fee86bed02) | Dec 31, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [61ce6be19c](https://linux-hardware.org/?probe=61ce6be19c) | Dec 29, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | XPS 13 9380                 | [021a0a73f4](https://linux-hardware.org/?probe=021a0a73f4) | Dec 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8a19941ffe](https://linux-hardware.org/?probe=8a19941ffe) | Dec 26, 2020 |
| ASUSTek       | X550ZE                      | [8cf715c40b](https://linux-hardware.org/?probe=8cf715c40b) | Dec 23, 2020 |
| ASUSTek       | X550ZE                      | [e3e9f32f6d](https://linux-hardware.org/?probe=e3e9f32f6d) | Dec 23, 2020 |
| HP            | Pavilion Notebook           | [5e08a85ebc](https://linux-hardware.org/?probe=5e08a85ebc) | Dec 21, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Unknown       | Unknown                     | [bf1f9d4982](https://linux-hardware.org/?probe=bf1f9d4982) | Dec 17, 2020 |
| Unknown       | Unknown                     | [5f4a9f2dc3](https://linux-hardware.org/?probe=5f4a9f2dc3) | Dec 17, 2020 |
| Dell          | Latitude 7390               | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| Acer          | Swift SF314-42              | [6e2749f503](https://linux-hardware.org/?probe=6e2749f503) | Dec 16, 2020 |
| HP            | Laptop 15-bs0xx             | [6b216f692c](https://linux-hardware.org/?probe=6b216f692c) | Dec 15, 2020 |
| Dell          | XPS 15 7590                 | [4312c9878e](https://linux-hardware.org/?probe=4312c9878e) | Dec 14, 2020 |
| Dell          | XPS 15 7590                 | [4a80e8baf4](https://linux-hardware.org/?probe=4a80e8baf4) | Dec 14, 2020 |
| Lenovo        | ThinkPad X201 3249CTO       | [a4e14d24c6](https://linux-hardware.org/?probe=a4e14d24c6) | Dec 13, 2020 |
| Lenovo        | ThinkPad P52s 20LBS0FF00    | [4826998fda](https://linux-hardware.org/?probe=4826998fda) | Dec 12, 2020 |
| HP            | ProBook 430 G5              | [c9a8c10a8f](https://linux-hardware.org/?probe=c9a8c10a8f) | Dec 10, 2020 |
| Samsung       | RC530/RC730                 | [69c8fa5fee](https://linux-hardware.org/?probe=69c8fa5fee) | Dec 09, 2020 |
| MSI           | GF63 Thin 9SC               | [5a23e8cfc4](https://linux-hardware.org/?probe=5a23e8cfc4) | Dec 06, 2020 |
| Dell          | XPS 13 9370                 | [bd8f5aa7df](https://linux-hardware.org/?probe=bd8f5aa7df) | Dec 05, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Lenovo        | ThinkPad P50 20EQS30D00     | [356758a7d8](https://linux-hardware.org/?probe=356758a7d8) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | [9c9bf0480d](https://linux-hardware.org/?probe=9c9bf0480d) | Nov 30, 2020 |
| Lenovo        | Yoga 2 13 20344             | [d1c3991da4](https://linux-hardware.org/?probe=d1c3991da4) | Nov 29, 2020 |
| Lenovo        | Yoga 2 13 20344             | [43b95135e2](https://linux-hardware.org/?probe=43b95135e2) | Nov 29, 2020 |
| Dell          | XPS 13 9370                 | [60ec1448d4](https://linux-hardware.org/?probe=60ec1448d4) | Nov 29, 2020 |
| Dell          | Latitude E5500              | [079101f502](https://linux-hardware.org/?probe=079101f502) | Nov 29, 2020 |
| Dell          | XPS 15 9570                 | [613707835e](https://linux-hardware.org/?probe=613707835e) | Nov 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| HP            | OMEN by HP Laptop 17-cb0... | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [49a0bab061](https://linux-hardware.org/?probe=49a0bab061) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a175dbabc2](https://linux-hardware.org/?probe=a175dbabc2) | Nov 12, 2020 |
| Dell          | Latitude 5490               | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [0f18132717](https://linux-hardware.org/?probe=0f18132717) | Nov 11, 2020 |
| HP            | EliteBook 820 G4            | [13e0c5e646](https://linux-hardware.org/?probe=13e0c5e646) | Nov 10, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [3a052bbb91](https://linux-hardware.org/?probe=3a052bbb91) | Nov 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [53efc559ad](https://linux-hardware.org/?probe=53efc559ad) | Nov 08, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [2c929e66bc](https://linux-hardware.org/?probe=2c929e66bc) | Nov 07, 2020 |
| Dell          | XPS 13 9360                 | [a6cf5e7036](https://linux-hardware.org/?probe=a6cf5e7036) | Nov 07, 2020 |
| Dell          | Latitude 7410               | [af066ad306](https://linux-hardware.org/?probe=af066ad306) | Nov 04, 2020 |
| HP            | Pavilion Notebook           | [5b2b100711](https://linux-hardware.org/?probe=5b2b100711) | Nov 04, 2020 |
| Acer          | Nitro AN715-51              | [8cb76bb2f8](https://linux-hardware.org/?probe=8cb76bb2f8) | Nov 03, 2020 |
| Acer          | Nitro AN715-51              | [485080dff0](https://linux-hardware.org/?probe=485080dff0) | Nov 03, 2020 |
| Dell          | G3 3500                     | [fb7c201de0](https://linux-hardware.org/?probe=fb7c201de0) | Nov 01, 2020 |
| Dell          | G3 3500                     | [130552c6a0](https://linux-hardware.org/?probe=130552c6a0) | Nov 01, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [ec44c959a4](https://linux-hardware.org/?probe=ec44c959a4) | Nov 01, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| Lenovo        | B51-80 80LM                 | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| Sony          | VPCSC41FM                   | [a7607a7b93](https://linux-hardware.org/?probe=a7607a7b93) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [ef90a9df54](https://linux-hardware.org/?probe=ef90a9df54) | Oct 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [c15ef33580](https://linux-hardware.org/?probe=c15ef33580) | Oct 25, 2020 |
| Acer          | Aspire E5-571G              | [b52fb33c4d](https://linux-hardware.org/?probe=b52fb33c4d) | Oct 25, 2020 |
| HP            | Pavilion g7                 | [585d199b71](https://linux-hardware.org/?probe=585d199b71) | Oct 25, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [447a3a003d](https://linux-hardware.org/?probe=447a3a003d) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [f8f15c63ad](https://linux-hardware.org/?probe=f8f15c63ad) | Oct 25, 2020 |
| HP            | ProBook 430 G5              | [b3df3d26f0](https://linux-hardware.org/?probe=b3df3d26f0) | Oct 24, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f0cf2671f2](https://linux-hardware.org/?probe=f0cf2671f2) | Oct 24, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 455 G7              | [70aaf58443](https://linux-hardware.org/?probe=70aaf58443) | Oct 19, 2020 |
| HP            | Pavilion dv7                | [65917ebd9d](https://linux-hardware.org/?probe=65917ebd9d) | Oct 18, 2020 |
| Dell          | XPS 15 7590                 | [daa70ce737](https://linux-hardware.org/?probe=daa70ce737) | Oct 17, 2020 |
| HP            | EliteBook 820 G4            | [ea2fe3b4dc](https://linux-hardware.org/?probe=ea2fe3b4dc) | Oct 15, 2020 |
| HP            | Pavilion Notebook           | [bd93e81149](https://linux-hardware.org/?probe=bd93e81149) | Oct 14, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0W10... | [64c3cf228e](https://linux-hardware.org/?probe=64c3cf228e) | Oct 14, 2020 |
| Dell          | Latitude E7270              | [efcbc76194](https://linux-hardware.org/?probe=efcbc76194) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [6199eaf93c](https://linux-hardware.org/?probe=6199eaf93c) | Oct 12, 2020 |
| Dell          | Latitude E7270              | [c04da65193](https://linux-hardware.org/?probe=c04da65193) | Oct 11, 2020 |
| Fujitsu       | LIFEBOOK P770               | [48fc4ff4db](https://linux-hardware.org/?probe=48fc4ff4db) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5cd90973fc](https://linux-hardware.org/?probe=5cd90973fc) | Oct 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c5d15be62](https://linux-hardware.org/?probe=9c5d15be62) | Oct 04, 2020 |
| Dell          | G5 5587                     | [c99b5f8c72](https://linux-hardware.org/?probe=c99b5f8c72) | Oct 02, 2020 |
| ASUSTek       | X555LJ                      | [bd5306ec57](https://linux-hardware.org/?probe=bd5306ec57) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [7f2e2caef1](https://linux-hardware.org/?probe=7f2e2caef1) | Sep 27, 2020 |
| Dell          | G3 3500                     | [23b58bcd77](https://linux-hardware.org/?probe=23b58bcd77) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [951fafbea0](https://linux-hardware.org/?probe=951fafbea0) | Sep 19, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [e638fa0818](https://linux-hardware.org/?probe=e638fa0818) | Sep 19, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Lenovo        | Unknown                     | [5107d64dc0](https://linux-hardware.org/?probe=5107d64dc0) | Sep 16, 2020 |
| HP            | ProBook 450 G5              | [9d3b97061b](https://linux-hardware.org/?probe=9d3b97061b) | Sep 15, 2020 |
| HP            | ProBook 450 G5              | [4d67605a9a](https://linux-hardware.org/?probe=4d67605a9a) | Sep 14, 2020 |
| Dell          | G3 3500                     | [73839e86fc](https://linux-hardware.org/?probe=73839e86fc) | Sep 14, 2020 |
| PC Special... | GK7NP5R                     | [2ba7289378](https://linux-hardware.org/?probe=2ba7289378) | Sep 11, 2020 |
| Dell          | Latitude 5501               | [bceeec9520](https://linux-hardware.org/?probe=bceeec9520) | Sep 10, 2020 |
| Dell          | Latitude 5501               | [0df822dc02](https://linux-hardware.org/?probe=0df822dc02) | Sep 09, 2020 |
| Lenovo        | ThinkPad X220 429029G       | [2e86679c2f](https://linux-hardware.org/?probe=2e86679c2f) | Sep 05, 2020 |
| Apple         | MacBookPro12,1              | [0f915dee52](https://linux-hardware.org/?probe=0f915dee52) | Sep 03, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [294fd98c3f](https://linux-hardware.org/?probe=294fd98c3f) | Sep 01, 2020 |
| HUAWEI        | HLY-WX9XX                   | [51bcf816e6](https://linux-hardware.org/?probe=51bcf816e6) | Sep 01, 2020 |
| Apple         | MacBookPro12,1              | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| Apple         | MacBookPro12,1              | [d48e12ebbd](https://linux-hardware.org/?probe=d48e12ebbd) | Aug 31, 2020 |
| HP            | Pavilion 11 x360 PC         | [2857ef3b7b](https://linux-hardware.org/?probe=2857ef3b7b) | Aug 30, 2020 |
| Dell          | Latitude 5401               | [fdb1d25e99](https://linux-hardware.org/?probe=fdb1d25e99) | Aug 27, 2020 |
| ASUSTek       | GL552VW                     | [9462a9e9ec](https://linux-hardware.org/?probe=9462a9e9ec) | Aug 26, 2020 |
| ASUSTek       | GL552VW                     | [1e5df72d90](https://linux-hardware.org/?probe=1e5df72d90) | Aug 25, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [63d74a10a6](https://linux-hardware.org/?probe=63d74a10a6) | Aug 25, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [5590d3f68a](https://linux-hardware.org/?probe=5590d3f68a) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [744c56e875](https://linux-hardware.org/?probe=744c56e875) | Aug 25, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a0960a7256](https://linux-hardware.org/?probe=a0960a7256) | Aug 25, 2020 |
| Dell          | XPS 15 7590                 | [1ecbfe31cc](https://linux-hardware.org/?probe=1ecbfe31cc) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [d475ab6b1f](https://linux-hardware.org/?probe=d475ab6b1f) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [25f98c006e](https://linux-hardware.org/?probe=25f98c006e) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [c2d9b7b8f9](https://linux-hardware.org/?probe=c2d9b7b8f9) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [7c299b5384](https://linux-hardware.org/?probe=7c299b5384) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [19586f3d92](https://linux-hardware.org/?probe=19586f3d92) | Aug 23, 2020 |
| Lenovo        | ThinkPad P53 20QN001JUS     | [d5c4efd016](https://linux-hardware.org/?probe=d5c4efd016) | Aug 23, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [c82c12e968](https://linux-hardware.org/?probe=c82c12e968) | Aug 22, 2020 |
| Notebook      | N141CU                      | [9c7c4fff3e](https://linux-hardware.org/?probe=9c7c4fff3e) | Aug 22, 2020 |
| Wortmann      | TERRA_MOBILE_1590S          | [ade9df5306](https://linux-hardware.org/?probe=ade9df5306) | Aug 21, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [8f067e33b6](https://linux-hardware.org/?probe=8f067e33b6) | Aug 21, 2020 |
| Dell          | G3 3500                     | [093682c4c4](https://linux-hardware.org/?probe=093682c4c4) | Aug 20, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [2c9e565b99](https://linux-hardware.org/?probe=2c9e565b99) | Aug 20, 2020 |
| Lenovo        | G580 20150                  | [1e7c1ee27a](https://linux-hardware.org/?probe=1e7c1ee27a) | Aug 20, 2020 |
| Dell          | G3 3500                     | [c64b8a0e61](https://linux-hardware.org/?probe=c64b8a0e61) | Aug 20, 2020 |
| Lenovo        | ThinkPad T590 20N4001YPB    | [c6283736fd](https://linux-hardware.org/?probe=c6283736fd) | Aug 19, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [fd339f3d69](https://linux-hardware.org/?probe=fd339f3d69) | Aug 17, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [19177595c8](https://linux-hardware.org/?probe=19177595c8) | Aug 16, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [9d003ef2fe](https://linux-hardware.org/?probe=9d003ef2fe) | Aug 16, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c7793f1daa](https://linux-hardware.org/?probe=c7793f1daa) | Aug 15, 2020 |
| Apple         | MacBookPro4,1               | [184e80bbc6](https://linux-hardware.org/?probe=184e80bbc6) | Aug 13, 2020 |
| Apple         | MacBookPro4,1               | [64593dd4a6](https://linux-hardware.org/?probe=64593dd4a6) | Aug 13, 2020 |
| Dell          | Inspiron 5755               | [89d1209c2c](https://linux-hardware.org/?probe=89d1209c2c) | Aug 12, 2020 |
| Notebook      | N141CU                      | [3aa97540ba](https://linux-hardware.org/?probe=3aa97540ba) | Aug 10, 2020 |
| Notebook      | N141CU                      | [38cc94083d](https://linux-hardware.org/?probe=38cc94083d) | Aug 10, 2020 |
| Apple         | MacBookPro8,2               | [1dd9ee1d09](https://linux-hardware.org/?probe=1dd9ee1d09) | Aug 09, 2020 |
| Apple         | MacBookPro8,1               | [092f544ecc](https://linux-hardware.org/?probe=092f544ecc) | Aug 08, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4fe8ac3a02](https://linux-hardware.org/?probe=4fe8ac3a02) | Aug 08, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad X270 20HN002UGE    | [c0b7a3c300](https://linux-hardware.org/?probe=c0b7a3c300) | Aug 07, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [a7ae8a6f78](https://linux-hardware.org/?probe=a7ae8a6f78) | Aug 07, 2020 |
| ASUSTek       | X406UAR                     | [97f52734c2](https://linux-hardware.org/?probe=97f52734c2) | Aug 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [d67ba67beb](https://linux-hardware.org/?probe=d67ba67beb) | Aug 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [8eaf4e509b](https://linux-hardware.org/?probe=8eaf4e509b) | Aug 05, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Apple         | MacBookPro5,1               | [c896b174a5](https://linux-hardware.org/?probe=c896b174a5) | Aug 03, 2020 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [4c08ca19cf](https://linux-hardware.org/?probe=4c08ca19cf) | Jul 30, 2020 |
| Dell          | Latitude 5500               | [4e1eb098f2](https://linux-hardware.org/?probe=4e1eb098f2) | Jul 28, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [cce195a7ce](https://linux-hardware.org/?probe=cce195a7ce) | Jul 25, 2020 |
| Sony          | VPCSC41FM                   | [3a1470664d](https://linux-hardware.org/?probe=3a1470664d) | Jul 24, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [a235d0f3c3](https://linux-hardware.org/?probe=a235d0f3c3) | Jul 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [68c95d0921](https://linux-hardware.org/?probe=68c95d0921) | Jul 17, 2020 |
| Acer          | Nitro AN515-53              | [85bf9e9450](https://linux-hardware.org/?probe=85bf9e9450) | Jul 17, 2020 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [43a917118a](https://linux-hardware.org/?probe=43a917118a) | Jul 14, 2020 |
| XMG           | C504                        | [a97e52282c](https://linux-hardware.org/?probe=a97e52282c) | Jul 13, 2020 |
| System76      | Lemur Pro                   | [ef0445b033](https://linux-hardware.org/?probe=ef0445b033) | Jul 09, 2020 |
| HP            | EliteBook 745 G6            | [b7f42e3bd9](https://linux-hardware.org/?probe=b7f42e3bd9) | Jul 06, 2020 |
| HP            | EliteBook 745 G6            | [d73fb2d895](https://linux-hardware.org/?probe=d73fb2d895) | Jul 05, 2020 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [359f4615fa](https://linux-hardware.org/?probe=359f4615fa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X100e 35089TU      | [6dccb35fcb](https://linux-hardware.org/?probe=6dccb35fcb) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [9729dd440a](https://linux-hardware.org/?probe=9729dd440a) | Jul 03, 2020 |
| HP            | EliteBook 820 G4            | [26a392b2c1](https://linux-hardware.org/?probe=26a392b2c1) | Jul 03, 2020 |
| Samsung       | R530/R730/P530              | [e1539a8d98](https://linux-hardware.org/?probe=e1539a8d98) | Jul 01, 2020 |
| Dell          | Latitude 5491               | [f861e71f84](https://linux-hardware.org/?probe=f861e71f84) | Jun 28, 2020 |
| Acer          | Nitro AN515-53              | [64802f828b](https://linux-hardware.org/?probe=64802f828b) | Jun 27, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [71beca8605](https://linux-hardware.org/?probe=71beca8605) | Jun 25, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Lenovo        | G710 20252                  | [f83c73bef0](https://linux-hardware.org/?probe=f83c73bef0) | Jun 15, 2020 |
| Acer          | Nitro AN515-53              | [aaaa4c011c](https://linux-hardware.org/?probe=aaaa4c011c) | Jun 15, 2020 |
| Dell          | Latitude 5480               | [d0d56fbb1d](https://linux-hardware.org/?probe=d0d56fbb1d) | Jun 14, 2020 |
| Acer          | Nitro AN515-53              | [0ebfb52f0d](https://linux-hardware.org/?probe=0ebfb52f0d) | Jun 13, 2020 |
| Acer          | Nitro AN515-53              | [701ffbf49a](https://linux-hardware.org/?probe=701ffbf49a) | Jun 12, 2020 |
| Dell          | XPS 13 9360                 | [b4be1dd313](https://linux-hardware.org/?probe=b4be1dd313) | Jun 09, 2020 |
| Acer          | Swift SF315-51              | [e703cb72e3](https://linux-hardware.org/?probe=e703cb72e3) | Jun 08, 2020 |
| Dell          | XPS 15 9530                 | [b93caec229](https://linux-hardware.org/?probe=b93caec229) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca7ca5b14e](https://linux-hardware.org/?probe=ca7ca5b14e) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| Dell          | Latitude E5570              | [e7012f0658](https://linux-hardware.org/?probe=e7012f0658) | Jun 05, 2020 |
| Dell          | XPS L702X                   | [a993cb7099](https://linux-hardware.org/?probe=a993cb7099) | Jun 04, 2020 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [b52ad09036](https://linux-hardware.org/?probe=b52ad09036) | Jun 04, 2020 |
| Dell          | XPS 13 9360                 | [e1d648a5f2](https://linux-hardware.org/?probe=e1d648a5f2) | Jun 04, 2020 |
| Lenovo        | ThinkPad L390 20NR001KRT    | [19809108e4](https://linux-hardware.org/?probe=19809108e4) | Jun 04, 2020 |
| Dell          | Inspiron 5577               | [b29e45343d](https://linux-hardware.org/?probe=b29e45343d) | Jun 04, 2020 |
| ASUSTek       | X555LJ                      | [8a0dab5948](https://linux-hardware.org/?probe=8a0dab5948) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [a173aacb52](https://linux-hardware.org/?probe=a173aacb52) | Jun 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d082b8d834](https://linux-hardware.org/?probe=d082b8d834) | Jun 03, 2020 |
| ASUSTek       | UX310UAR                    | [1b9a59e4ca](https://linux-hardware.org/?probe=1b9a59e4ca) | Jun 03, 2020 |
| ASUSTek       | UX410UAR                    | [d3b1cf2698](https://linux-hardware.org/?probe=d3b1cf2698) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [31a6aa1e70](https://linux-hardware.org/?probe=31a6aa1e70) | May 31, 2020 |
| Acer          | Aspire VN7-592G             | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| MSI           | GT63 Titan 8SG              | [85363c0652](https://linux-hardware.org/?probe=85363c0652) | May 25, 2020 |
| Acer          | Aspire V3-771               | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [a37835c09e](https://linux-hardware.org/?probe=a37835c09e) | May 25, 2020 |
| Chuwi         | LapBook Pro                 | [017c1e4813](https://linux-hardware.org/?probe=017c1e4813) | May 24, 2020 |
| Chuwi         | LapBook Pro                 | [a4be681659](https://linux-hardware.org/?probe=a4be681659) | May 23, 2020 |
| Timi          | Mi Laptop Air 12.5          | [fea499e36a](https://linux-hardware.org/?probe=fea499e36a) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | Unknown                     | [0be27afc58](https://linux-hardware.org/?probe=0be27afc58) | May 22, 2020 |
| Dell          | Latitude E6440              | [cb23d3096c](https://linux-hardware.org/?probe=cb23d3096c) | May 19, 2020 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [25ed02b04a](https://linux-hardware.org/?probe=25ed02b04a) | May 19, 2020 |
| Dell          | Latitude E5540              | [8ea71ba2ae](https://linux-hardware.org/?probe=8ea71ba2ae) | May 19, 2020 |
| Unknown       | Unknown                     | [48a9c9544a](https://linux-hardware.org/?probe=48a9c9544a) | May 16, 2020 |
| Dell          | Latitude 3400               | [0787585d2e](https://linux-hardware.org/?probe=0787585d2e) | May 15, 2020 |
| Dell          | Latitude 3400               | [04b3381928](https://linux-hardware.org/?probe=04b3381928) | May 15, 2020 |
| Lenovo        | IdeaPad Z370                | [81a1579081](https://linux-hardware.org/?probe=81a1579081) | May 15, 2020 |
| HP            | Pavilion Notebook           | [01b6eef865](https://linux-hardware.org/?probe=01b6eef865) | May 14, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [0efeb1e15a](https://linux-hardware.org/?probe=0efeb1e15a) | May 14, 2020 |
| HP            | Pavilion Notebook           | [1cb7e4e70a](https://linux-hardware.org/?probe=1cb7e4e70a) | May 13, 2020 |
| HP            | Pavilion Notebook           | [75714d5542](https://linux-hardware.org/?probe=75714d5542) | May 13, 2020 |
| Dell          | Latitude E6520              | [e275465d57](https://linux-hardware.org/?probe=e275465d57) | May 13, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9e904a50ca](https://linux-hardware.org/?probe=9e904a50ca) | May 12, 2020 |
| SECO          | UDOO x86                    | [62ae920d77](https://linux-hardware.org/?probe=62ae920d77) | May 12, 2020 |
| Toshiba       | Satellite L50-A-16G         | [dea54eb8a1](https://linux-hardware.org/?probe=dea54eb8a1) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [bd8e53be4e](https://linux-hardware.org/?probe=bd8e53be4e) | May 11, 2020 |
| HP            | Pavilion Notebook           | [70466d71d3](https://linux-hardware.org/?probe=70466d71d3) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [748a1ea384](https://linux-hardware.org/?probe=748a1ea384) | May 11, 2020 |
| ASUSTek       | E402NA                      | [bc0fa6176d](https://linux-hardware.org/?probe=bc0fa6176d) | May 11, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [b2649601d3](https://linux-hardware.org/?probe=b2649601d3) | May 10, 2020 |
| Unknown       | Unknown                     | [7740c04b4b](https://linux-hardware.org/?probe=7740c04b4b) | May 08, 2020 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [e0968088b3](https://linux-hardware.org/?probe=e0968088b3) | May 08, 2020 |
| Apple         | MacBookPro8,2               | [9602f32094](https://linux-hardware.org/?probe=9602f32094) | May 03, 2020 |
| Unknown       | Unknown                     | [97f8a22d28](https://linux-hardware.org/?probe=97f8a22d28) | May 03, 2020 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [be25ab70cb](https://linux-hardware.org/?probe=be25ab70cb) | May 01, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [729a079629](https://linux-hardware.org/?probe=729a079629) | Apr 28, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [6e5f544240](https://linux-hardware.org/?probe=6e5f544240) | Apr 28, 2020 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [0b983a161c](https://linux-hardware.org/?probe=0b983a161c) | Apr 27, 2020 |
| Unknown       | Unknown                     | [eb36ed044f](https://linux-hardware.org/?probe=eb36ed044f) | Apr 26, 2020 |
| Dell          | Latitude E6420              | [f33530c32a](https://linux-hardware.org/?probe=f33530c32a) | Apr 26, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [bf47e6f662](https://linux-hardware.org/?probe=bf47e6f662) | Apr 26, 2020 |
| Dell          | Latitude 7390               | [59c245d756](https://linux-hardware.org/?probe=59c245d756) | Apr 20, 2020 |
| Dell          | Latitude 7390               | [c91eb58962](https://linux-hardware.org/?probe=c91eb58962) | Apr 20, 2020 |
| Dell          | Latitude E5470              | [568a079f29](https://linux-hardware.org/?probe=568a079f29) | Apr 17, 2020 |
| Dell          | Latitude E5470              | [9bad86d9c9](https://linux-hardware.org/?probe=9bad86d9c9) | Apr 17, 2020 |
| Dell          | Latitude E7440              | [037a28c347](https://linux-hardware.org/?probe=037a28c347) | Apr 17, 2020 |
| Dell          | Latitude E5470              | [c2b554cdcf](https://linux-hardware.org/?probe=c2b554cdcf) | Apr 15, 2020 |
| HP            | x360 310 G1 PC              | [9751d299ad](https://linux-hardware.org/?probe=9751d299ad) | Apr 15, 2020 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c80d705080](https://linux-hardware.org/?probe=c80d705080) | Apr 12, 2020 |
| Dell          | Inspiron 7520               | [31c3181139](https://linux-hardware.org/?probe=31c3181139) | Apr 12, 2020 |
| Lenovo        | G570 20079                  | [af1e15f9d1](https://linux-hardware.org/?probe=af1e15f9d1) | Apr 11, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [ca529580d5](https://linux-hardware.org/?probe=ca529580d5) | Apr 10, 2020 |
| Acer          | Aspire V3-331               | [3556b592c2](https://linux-hardware.org/?probe=3556b592c2) | Apr 09, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [89ce2a3948](https://linux-hardware.org/?probe=89ce2a3948) | Apr 05, 2020 |
| Dell          | Precision M4600             | [b88c9f527c](https://linux-hardware.org/?probe=b88c9f527c) | Apr 03, 2020 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [de1b814a88](https://linux-hardware.org/?probe=de1b814a88) | Apr 02, 2020 |
| HP            | ProBook 4510s               | [26fb60e010](https://linux-hardware.org/?probe=26fb60e010) | Apr 01, 2020 |
| Acer          | Aspire VN7-571G             | [259bfff741](https://linux-hardware.org/?probe=259bfff741) | Mar 29, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [5f5388221b](https://linux-hardware.org/?probe=5f5388221b) | Mar 29, 2020 |
| Lenovo        | ThinkPad 20F6CTO1WW         | [6bc7d86b9c](https://linux-hardware.org/?probe=6bc7d86b9c) | Mar 28, 2020 |
| HP            | OMEN by HP Laptop           | [e7e39b1152](https://linux-hardware.org/?probe=e7e39b1152) | Mar 22, 2020 |
| HP            | Pavilion ZV6100 (EE984EA... | [0b441e5085](https://linux-hardware.org/?probe=0b441e5085) | Mar 20, 2020 |
| HP            | OMEN by HP Laptop 17-cb0... | [a42a77029d](https://linux-hardware.org/?probe=a42a77029d) | Mar 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| HUAWEI        | HLY-WX9XX                   | [763c1a213c](https://linux-hardware.org/?probe=763c1a213c) | Mar 02, 2020 |
| Lenovo        | ThinkPad Z61m 945038U       | [e5c5ce1445](https://linux-hardware.org/?probe=e5c5ce1445) | Mar 01, 2020 |
| Dell          | XPS 15 7590                 | [57bc59f308](https://linux-hardware.org/?probe=57bc59f308) | Feb 27, 2020 |
| Dell          | XPS 15 7590                 | [293a792a22](https://linux-hardware.org/?probe=293a792a22) | Feb 27, 2020 |
| Dell          | XPS 15 7590                 | [fba41b433f](https://linux-hardware.org/?probe=fba41b433f) | Feb 27, 2020 |
| Acer          | Aspire V3-331               | [98986faf06](https://linux-hardware.org/?probe=98986faf06) | Feb 21, 2020 |
| Acer          | Aspire V3-331               | [400111ccfc](https://linux-hardware.org/?probe=400111ccfc) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| MSI           | GT73EVR 7RF                 | [99e70d86e2](https://linux-hardware.org/?probe=99e70d86e2) | Feb 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d140409c65](https://linux-hardware.org/?probe=d140409c65) | Feb 18, 2020 |
| Acer          | Aspire V3-331               | [68e659c87d](https://linux-hardware.org/?probe=68e659c87d) | Feb 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | [28fbda9ecd](https://linux-hardware.org/?probe=28fbda9ecd) | Feb 11, 2020 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [80f496eacd](https://linux-hardware.org/?probe=80f496eacd) | Feb 11, 2020 |
| Acer          | Aspire V3-331               | [1ed27701ea](https://linux-hardware.org/?probe=1ed27701ea) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [5fe84895f2](https://linux-hardware.org/?probe=5fe84895f2) | Feb 10, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [bf08aa9738](https://linux-hardware.org/?probe=bf08aa9738) | Feb 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dbdccc5696](https://linux-hardware.org/?probe=dbdccc5696) | Feb 06, 2020 |
| Acer          | Aspire V3-331               | [f970ff6696](https://linux-hardware.org/?probe=f970ff6696) | Feb 05, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [423ca04065](https://linux-hardware.org/?probe=423ca04065) | Jan 30, 2020 |
| Lenovo        | ThinkPad L580 20LXS5PE0V    | [e4e856b6f2](https://linux-hardware.org/?probe=e4e856b6f2) | Jan 30, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [d5fbd58f8b](https://linux-hardware.org/?probe=d5fbd58f8b) | Jan 27, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [3240ab7b3c](https://linux-hardware.org/?probe=3240ab7b3c) | Jan 27, 2020 |
| Lenovo        | ThinkPad T460s 20FAS03K0... | [88338e7031](https://linux-hardware.org/?probe=88338e7031) | Jan 27, 2020 |
| HP            | Pavilion dv7                | [119a35f980](https://linux-hardware.org/?probe=119a35f980) | Jan 26, 2020 |
| Lenovo        | Y50-70 20378                | [39a9917502](https://linux-hardware.org/?probe=39a9917502) | Jan 24, 2020 |
| MSI           | GE62 6QD                    | [54574b77f2](https://linux-hardware.org/?probe=54574b77f2) | Jan 24, 2020 |
| Lenovo        | Y50-70 20378                | [c34eecb4fb](https://linux-hardware.org/?probe=c34eecb4fb) | Jan 24, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| HP            | ZBook 15 G2                 | [2b62bc6c8a](https://linux-hardware.org/?probe=2b62bc6c8a) | Jan 19, 2020 |
| HP            | ZBook 15 G2                 | [191021f74e](https://linux-hardware.org/?probe=191021f74e) | Jan 19, 2020 |
| Lenovo        | ThinkPad T450s 20BWS3F00... | [cf32529cfe](https://linux-hardware.org/?probe=cf32529cfe) | Jan 09, 2020 |
| Lenovo        | ThinkPad 20QJ001GMX         | [e720c77930](https://linux-hardware.org/?probe=e720c77930) | Jan 09, 2020 |
| Medion        | P6669 MD60147               | [b857f2b82d](https://linux-hardware.org/?probe=b857f2b82d) | Jan 07, 2020 |
| Lenovo        | ThinkPad T490s 20NX007AG... | [12b5e06a49](https://linux-hardware.org/?probe=12b5e06a49) | Jan 04, 2020 |
| Acer          | Aspire A315-42              | [96d84c0576](https://linux-hardware.org/?probe=96d84c0576) | Dec 22, 2019 |
| Acer          | Aspire A315-42              | [e36036a3d5](https://linux-hardware.org/?probe=e36036a3d5) | Dec 21, 2019 |
| Acer          | Aspire A315-42              | [f708209c00](https://linux-hardware.org/?probe=f708209c00) | Dec 21, 2019 |
| Acer          | Aspire A315-42              | [35673db932](https://linux-hardware.org/?probe=35673db932) | Dec 17, 2019 |
| Acer          | Aspire A315-42              | [f16e75f852](https://linux-hardware.org/?probe=f16e75f852) | Dec 14, 2019 |
| HP            | EliteBook 840 G6            | [6b2396c6ac](https://linux-hardware.org/?probe=6b2396c6ac) | Dec 08, 2019 |
| Dell          | G3 3779                     | [716cb93844](https://linux-hardware.org/?probe=716cb93844) | Dec 06, 2019 |
| Dell          | Latitude 7390               | [714656669c](https://linux-hardware.org/?probe=714656669c) | Dec 02, 2019 |
| HP            | ZBook 15                    | [196dfe92a3](https://linux-hardware.org/?probe=196dfe92a3) | Nov 27, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [be40a37ea8](https://linux-hardware.org/?probe=be40a37ea8) | Nov 24, 2019 |
| Acer          | Aspire V5-431               | [6a087dd575](https://linux-hardware.org/?probe=6a087dd575) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [0e0be8ef86](https://linux-hardware.org/?probe=0e0be8ef86) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [f6081d54b1](https://linux-hardware.org/?probe=f6081d54b1) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [3200b20576](https://linux-hardware.org/?probe=3200b20576) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [65529afb99](https://linux-hardware.org/?probe=65529afb99) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [b7089462b3](https://linux-hardware.org/?probe=b7089462b3) | Nov 16, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ec55fd6791](https://linux-hardware.org/?probe=ec55fd6791) | Oct 06, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [e46079e2f8](https://linux-hardware.org/?probe=e46079e2f8) | Oct 06, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [94e842d2eb](https://linux-hardware.org/?probe=94e842d2eb) | Oct 06, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [e1dfe6707d](https://linux-hardware.org/?probe=e1dfe6707d) | Oct 06, 2019 |
| Acer          | Aspire E5-511               | [af59a812bc](https://linux-hardware.org/?probe=af59a812bc) | Sep 29, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [215d2a28a4](https://linux-hardware.org/?probe=215d2a28a4) | Aug 15, 2019 |
| Dell          | Latitude 7390               | [d360b45394](https://linux-hardware.org/?probe=d360b45394) | Aug 15, 2019 |
| HP            | Pavilion ZV6100 (EE984EA... | [e643de7d13](https://linux-hardware.org/?probe=e643de7d13) | Aug 15, 2019 |
| Dell          | Latitude 7390               | [d1454b26c6](https://linux-hardware.org/?probe=d1454b26c6) | Aug 15, 2019 |
| Timi          | Mi Laptop Air 12.5          | [8d36fc215c](https://linux-hardware.org/?probe=8d36fc215c) | Aug 14, 2019 |
| Lenovo        | ThinkPad T440s 20AQ0066M... | [54b33d56bb](https://linux-hardware.org/?probe=54b33d56bb) | Aug 14, 2019 |
| Dell          | Latitude E6430              | [4e38982788](https://linux-hardware.org/?probe=4e38982788) | Aug 13, 2019 |
| Dell          | Latitude 7390               | [05cdc89a9d](https://linux-hardware.org/?probe=05cdc89a9d) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [1369716caa](https://linux-hardware.org/?probe=1369716caa) | Aug 12, 2019 |
| Dell          | Latitude E6430              | [e90e03524b](https://linux-hardware.org/?probe=e90e03524b) | Aug 12, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [65e73516b5](https://linux-hardware.org/?probe=65e73516b5) | Aug 03, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [7b994d2ec2](https://linux-hardware.org/?probe=7b994d2ec2) | Jul 31, 2019 |
| Apple         | MacBookPro1,1               | [46f4e56e3f](https://linux-hardware.org/?probe=46f4e56e3f) | Jul 21, 2019 |
| Apple         | MacBookPro8,2               | [88b8816bfe](https://linux-hardware.org/?probe=88b8816bfe) | Jul 11, 2019 |
| Lenovo        | ThinkPad L450 20DTS01R00    | [8556fe8940](https://linux-hardware.org/?probe=8556fe8940) | Jul 11, 2019 |
| Apple         | MacBookPro8,2               | [3d2225e709](https://linux-hardware.org/?probe=3d2225e709) | Jul 11, 2019 |
| Dell          | Latitude E7250              | [64dc3ace03](https://linux-hardware.org/?probe=64dc3ace03) | Jun 17, 2019 |
| Dell          | Latitude E7250              | [02b9759d77](https://linux-hardware.org/?probe=02b9759d77) | Jun 16, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [31a261423c](https://linux-hardware.org/?probe=31a261423c) | Jun 11, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [6a667c9ba7](https://linux-hardware.org/?probe=6a667c9ba7) | Jun 11, 2019 |
| Dell          | Inspiron 7520               | [744af8e456](https://linux-hardware.org/?probe=744af8e456) | Jun 10, 2019 |
| Dell          | Inspiron 7520               | [9ed6957c8b](https://linux-hardware.org/?probe=9ed6957c8b) | Jun 07, 2019 |
| HP            | OMEN by HP Laptop 15-dc0... | [06ee78ee4d](https://linux-hardware.org/?probe=06ee78ee4d) | Apr 26, 2019 |
| HP            | ProBook 4510s               | [b1ed13a854](https://linux-hardware.org/?probe=b1ed13a854) | Mar 29, 2019 |
| Dell          | Latitude E7250              | [0ee5638d26](https://linux-hardware.org/?probe=0ee5638d26) | Mar 29, 2019 |
| Positivo      | WCBT1013                    | [e6f1ac9248](https://linux-hardware.org/?probe=e6f1ac9248) | Mar 27, 2019 |
| Dell          | Latitude E7250              | [fcd5b5c6f3](https://linux-hardware.org/?probe=fcd5b5c6f3) | Mar 23, 2019 |
| Dell          | Latitude E7250              | [61982fcb92](https://linux-hardware.org/?probe=61982fcb92) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [3c8e2e4aba](https://linux-hardware.org/?probe=3c8e2e4aba) | Mar 19, 2019 |
| Dell          | Latitude E7250              | [ae7e990d2c](https://linux-hardware.org/?probe=ae7e990d2c) | Mar 19, 2019 |
| HP            | OMEN by HP Laptop           | [7bd53b3ffb](https://linux-hardware.org/?probe=7bd53b3ffb) | Nov 28, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [9a4db5d6fd](https://linux-hardware.org/?probe=9a4db5d6fd) | Nov 14, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [f38ca9409c](https://linux-hardware.org/?probe=f38ca9409c) | Nov 14, 2018 |
| ASUSTek       | Strix 17 GL703GE            | [93a71f7e7f](https://linux-hardware.org/?probe=93a71f7e7f) | Nov 14, 2018 |
| Lenovo        | ThinkPad X230 23252UU       | [cefd5e879b](https://linux-hardware.org/?probe=cefd5e879b) | Nov 08, 2018 |
| ASUSTek       | K55VJ                       | [f23b5bf0da](https://linux-hardware.org/?probe=f23b5bf0da) | Nov 01, 2018 |
| Medion        | X783X                       | [852662bdf3](https://linux-hardware.org/?probe=852662bdf3) | Oct 31, 2018 |
| Lenovo        | ThinkPad X1 Carbon 3460B... | [b7014678b5](https://linux-hardware.org/?probe=b7014678b5) | Oct 30, 2018 |
| Lenovo        | ThinkPad T480 20L6S01W00    | [6f9dca6953](https://linux-hardware.org/?probe=6f9dca6953) | Oct 29, 2018 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4438a85b31](https://linux-hardware.org/?probe=4438a85b31) | Oct 26, 2018 |
| ASUSTek       | N73SM                       | [a5a0da657b](https://linux-hardware.org/?probe=a5a0da657b) | Oct 11, 2018 |
| Positivo      | Unknown                     | [d826611187](https://linux-hardware.org/?probe=d826611187) | Sep 24, 2018 |
| HP            | OMEN by HP Laptop 17-an0... | [142d7492c2](https://linux-hardware.org/?probe=142d7492c2) | Sep 16, 2018 |
| HP            | OMEN by HP Laptop 17-an0... | [65292e94a4](https://linux-hardware.org/?probe=65292e94a4) | Sep 16, 2018 |
| Dell          | XPS 13 9370                 | [424d23c5fe](https://linux-hardware.org/?probe=424d23c5fe) | Sep 01, 2018 |
| Dell          | XPS 13 9370                 | [f4ea533636](https://linux-hardware.org/?probe=f4ea533636) | Sep 01, 2018 |
| Acer          | Aspire SW3-016              | [425d589d65](https://linux-hardware.org/?probe=425d589d65) | Apr 01, 2018 |
| Samsung       | R425/R525                   | [eeb54d2d46](https://linux-hardware.org/?probe=eeb54d2d46) | Oct 04, 2017 |
| Samsung       | R425/R525                   | [140a1aad88](https://linux-hardware.org/?probe=140a1aad88) | Oct 04, 2017 |
| Lenovo        | B50-30 20382                | [b4e99f70a9](https://linux-hardware.org/?probe=b4e99f70a9) | Sep 28, 2017 |
| MSI           | GE72 6QF                    | [1c47bc90e4](https://linux-hardware.org/?probe=1c47bc90e4) | Dec 18, 2016 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [25576a8571](https://linux-hardware.org/?probe=25576a8571) | Jul 16, 2016 |
| Samsung       | NC10                        | [3ad0ff0e13](https://linux-hardware.org/?probe=3ad0ff0e13) | Jul 12, 2016 |
| MSI           | GS60 6QC                    | [404f145917](https://linux-hardware.org/?probe=404f145917) | May 18, 2016 |
| Samsung       | NC10                        | [6da4c3c370](https://linux-hardware.org/?probe=6da4c3c370) | Mar 06, 2016 |
| ASUSTek       | N501VW                      | [5b1076ea3c](https://linux-hardware.org/?probe=5b1076ea3c) | Mar 02, 2016 |
| HP            | EliteBook 2540p             | [bd135661d2](https://linux-hardware.org/?probe=bd135661d2) | Feb 11, 2016 |
| HP            | EliteBook 2540p             | [f25f73d78c](https://linux-hardware.org/?probe=f25f73d78c) | Feb 11, 2016 |
| Acer          | Aspire E5-522               | [76013f1c62](https://linux-hardware.org/?probe=76013f1c62) | Feb 04, 2016 |
| Lenovo        | G570 20079                  | [2239d316e8](https://linux-hardware.org/?probe=2239d316e8) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 242       | 48.99%  |
| Gentoo 2.6     | 185       | 37.45%  |
| Gentoo 2.8     | 43        | 8.7%    |
| Gentoo         | 15        | 3.04%   |
| Gentoo 2.4.1   | 2         | 0.4%    |
| Gentoo 2.3     | 2         | 0.4%    |
| Gentoo 2.2     | 2         | 0.4%    |
| Gentoo Pelikan | 1         | 0.2%    |
| Gentoo 2.1     | 1         | 0.2%    |
| Gentoo 1       | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 452       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.27-gentoo               | 16        | 2.7%    |
| 5.10.61-gentoo               | 14        | 2.36%   |
| 5.4.38-gentoo                | 11        | 1.86%   |
| 5.4.80-gentoo-r1             | 9         | 1.52%   |
| 5.4.48-gentoo                | 9         | 1.52%   |
| 5.10.76-gentoo-r1            | 9         | 1.52%   |
| 5.10.76-gentoo-r1-x86_64     | 7         | 1.18%   |
| 5.10.52-gentoo               | 7         | 1.18%   |
| 5.4.97-gentoo                | 6         | 1.01%   |
| 5.10.27-gentoo-x86_64        | 6         | 1.01%   |
| 5.4.28-gentoo                | 5         | 0.84%   |
| 4.19.97-gentoo               | 5         | 0.84%   |
| 5.8.0-gentoo-r1              | 4         | 0.68%   |
| 5.4.97-gentoo-x86_64         | 4         | 0.68%   |
| 5.4.60-gentoo                | 4         | 0.68%   |
| 5.4.48-gentoo-x86_64         | 4         | 0.68%   |
| 5.15.26-gentoo               | 4         | 0.68%   |
| 5.15.16-gentoo               | 4         | 0.68%   |
| 5.10.61-gentoo-x86_64        | 4         | 0.68%   |
| 4.14.65-gentoo               | 4         | 0.68%   |
| 5.4.66-gentoo                | 3         | 0.51%   |
| 5.4.38-gentoo-x86_64         | 3         | 0.51%   |
| 5.17.3-gentoo                | 3         | 0.51%   |
| 5.15.5-gentoo                | 3         | 0.51%   |
| 5.15.32-gentoo-r1            | 3         | 0.51%   |
| 5.15.26-gentoo-x86_64        | 3         | 0.51%   |
| 5.15.23-gentoo-x86_64        | 3         | 0.51%   |
| 5.15.23-gentoo               | 3         | 0.51%   |
| 5.15.13-gentoo               | 3         | 0.51%   |
| 5.15.10-gentoo-x86_64        | 3         | 0.51%   |
| 5.14.9-gentoo-x86_64         | 3         | 0.51%   |
| 5.11.2-gentoo                | 3         | 0.51%   |
| 5.10.4-gentoo-x86_64         | 3         | 0.51%   |
| 5.10.33-gentoo-dist          | 3         | 0.51%   |
| 4.19.97-gentoo-x86_64        | 3         | 0.51%   |
| 4.19.86-gentoo               | 3         | 0.51%   |
| 4.19.72-gentoo               | 3         | 0.51%   |
| 4.19.57-gentoo               | 3         | 0.51%   |
| 5.9.8-gentoo                 | 2         | 0.34%   |
| 5.9.2-gentoo                 | 2         | 0.34%   |
| 5.8.16-gentoo                | 2         | 0.34%   |
| 5.8.1-gentoo                 | 2         | 0.34%   |
| 5.7.7-gentoo-x86_64          | 2         | 0.34%   |
| 5.7.4-gentoo                 | 2         | 0.34%   |
| 5.7.0-gentoo                 | 2         | 0.34%   |
| 5.6.15-gentoo                | 2         | 0.34%   |
| 5.6.15                       | 2         | 0.34%   |
| 5.4.92-gentoo-x86_64         | 2         | 0.34%   |
| 5.4.92-gentoo                | 2         | 0.34%   |
| 5.4.72-gentoo-x86_64         | 2         | 0.34%   |
| 5.4.72-gentoo                | 2         | 0.34%   |
| 5.4.72                       | 2         | 0.34%   |
| 5.4.66-gentoo-x86_64         | 2         | 0.34%   |
| 5.4.1-gentoo                 | 2         | 0.34%   |
| 5.17.1-gentoo-r1             | 2         | 0.34%   |
| 5.16.0-gentoo-x86_64         | 2         | 0.34%   |
| 5.15.7-gentoo                | 2         | 0.34%   |
| 5.15.6-gentoo                | 2         | 0.34%   |
| 5.15.32-gentoo-r1-x86_64     | 2         | 0.34%   |
| 5.15.19-gentoo-112-overlayfs | 2         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 4.23%   |
| 5.10.76 | 21        | 3.55%   |
| 5.4.48  | 20        | 3.38%   |
| 5.10.61 | 19        | 3.21%   |
| 5.4.38  | 16        | 2.71%   |
| 5.4.97  | 12        | 2.03%   |
| 5.4.80  | 12        | 2.03%   |
| 5.4.28  | 11        | 1.86%   |
| 5.10.52 | 11        | 1.86%   |
| 5.15.11 | 10        | 1.69%   |
| 4.19.97 | 9         | 1.52%   |
| 5.15.23 | 8         | 1.35%   |
| 5.4.72  | 7         | 1.18%   |
| 5.15.32 | 7         | 1.18%   |
| 5.15.26 | 7         | 1.18%   |
| 5.4.66  | 6         | 1.02%   |
| 5.4.60  | 6         | 1.02%   |
| 5.16.0  | 6         | 1.02%   |
| 5.15.10 | 6         | 1.02%   |
| 5.9.0   | 5         | 0.85%   |
| 5.8.0   | 5         | 0.85%   |
| 5.15.5  | 5         | 0.85%   |
| 5.15.13 | 5         | 0.85%   |
| 5.14.9  | 5         | 0.85%   |
| 5.11.0  | 5         | 0.85%   |
| 5.10.4  | 5         | 0.85%   |
| 4.19.57 | 5         | 0.85%   |
| 5.9.1   | 4         | 0.68%   |
| 5.6.15  | 4         | 0.68%   |
| 5.4.92  | 4         | 0.68%   |
| 5.17.1  | 4         | 0.68%   |
| 5.16.10 | 4         | 0.68%   |
| 5.15.16 | 4         | 0.68%   |
| 5.12.4  | 4         | 0.68%   |
| 5.12.0  | 4         | 0.68%   |
| 5.11.2  | 4         | 0.68%   |
| 4.19.72 | 4         | 0.68%   |
| 4.14.65 | 4         | 0.68%   |
| 5.9.8   | 3         | 0.51%   |
| 5.9.11  | 3         | 0.51%   |
| 5.8.16  | 3         | 0.51%   |
| 5.8.1   | 3         | 0.51%   |
| 5.7.4   | 3         | 0.51%   |
| 5.4.1   | 3         | 0.51%   |
| 5.17.3  | 3         | 0.51%   |
| 5.15.12 | 3         | 0.51%   |
| 5.15.1  | 3         | 0.51%   |
| 5.14.8  | 3         | 0.51%   |
| 5.14.14 | 3         | 0.51%   |
| 5.14.1  | 3         | 0.51%   |
| 5.13.12 | 3         | 0.51%   |
| 5.12.10 | 3         | 0.51%   |
| 5.10.74 | 3         | 0.51%   |
| 5.10.33 | 3         | 0.51%   |
| 5.10.15 | 3         | 0.51%   |
| 5.10.13 | 3         | 0.51%   |
| 4.19.86 | 3         | 0.51%   |
| 4.19.0  | 3         | 0.51%   |
| 4.14.83 | 3         | 0.51%   |
| 5.9.6   | 2         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 107       | 19.85%  |
| 5.4     | 101       | 18.74%  |
| 5.15    | 63        | 11.69%  |
| 4.19    | 33        | 6.12%   |
| 5.9     | 23        | 4.27%   |
| 5.6     | 22        | 4.08%   |
| 5.16    | 22        | 4.08%   |
| 5.14    | 22        | 4.08%   |
| 5.11    | 21        | 3.9%    |
| 5.8     | 20        | 3.71%   |
| 5.12    | 18        | 3.34%   |
| 5.7     | 16        | 2.97%   |
| 5.13    | 13        | 2.41%   |
| 5.17    | 9         | 1.67%   |
| 4.14    | 8         | 1.48%   |
| 5.5     | 7         | 1.3%    |
| 5.3     | 5         | 0.93%   |
| 5.1     | 5         | 0.93%   |
| 4.4     | 5         | 0.93%   |
| 5.2     | 3         | 0.56%   |
| 4.9     | 3         | 0.56%   |
| 4.18    | 3         | 0.56%   |
| 5.0     | 2         | 0.37%   |
| 4.6     | 2         | 0.37%   |
| 4.12    | 2         | 0.37%   |
| 4.5     | 1         | 0.19%   |
| 4.20    | 1         | 0.19%   |
| 4.10    | 1         | 0.19%   |
| 4.1     | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 438       | 96.9%   |
| i686   | 11        | 2.43%   |
| ppc    | 3         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 233       | 48.14%  |
| KDE5           | 72        | 14.88%  |
| GNOME          | 61        | 12.6%   |
| XFCE           | 36        | 7.44%   |
| KDE            | 24        | 4.96%   |
| MATE           | 13        | 2.69%   |
| DWM            | 7         | 1.45%   |
| Sway           | 6         | 1.24%   |
| LXQt           | 5         | 1.03%   |
| LXDE           | 5         | 1.03%   |
| XSession       | 4         | 0.83%   |
| openbox        | 3         | 0.62%   |
| awesome        | 3         | 0.62%   |
| X-Cinnamon     | 2         | 0.41%   |
| Cinnamon       | 2         | 0.41%   |
| qt5ct          | 1         | 0.21%   |
| i3-with-shmlog | 1         | 0.21%   |
| i3             | 1         | 0.21%   |
| GNOME Classic  | 1         | 0.21%   |
| fvwm           | 1         | 0.21%   |
| fluxbox        | 1         | 0.21%   |
| Enlightenment  | 1         | 0.21%   |
| bspwm          | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 289       | 60.08%  |
| Unknown | 74        | 15.38%  |
| Tty     | 62        | 12.89%  |
| Wayland | 56        | 11.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 255       | 53.57%  |
| SDDM    | 102       | 21.43%  |
| LightDM | 49        | 10.29%  |
| GDM     | 47        | 9.87%   |
| XDM     | 10        | 2.1%    |
| SLiM    | 7         | 1.47%   |
| LXDM    | 2         | 0.42%   |
| GREETD  | 2         | 0.42%   |
| KDM     | 1         | 0.21%   |
| GDM3    | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Notebooks | Percent |
|----------------------|-----------|---------|
| en_US                | 182       | 37.92%  |
| Unknown              | 89        | 18.54%  |
| de_DE                | 29        | 6.04%   |
| C.UTF8               | 29        | 6.04%   |
| en_GB                | 25        | 5.21%   |
| ru_RU                | 21        | 4.38%   |
| fr_FR                | 11        | 2.29%   |
| it_IT                | 8         | 1.67%   |
| C                    | 8         | 1.67%   |
| es_ES                | 7         | 1.46%   |
| en_AU                | 7         | 1.46%   |
| zh_CN                | 5         | 1.04%   |
| POSIX                | 5         | 1.04%   |
| en_CA                | 5         | 1.04%   |
| pl_PL                | 4         | 0.83%   |
| el_GR                | 4         | 0.83%   |
| pt_BR                | 3         | 0.63%   |
| nl_NL                | 3         | 0.63%   |
| uk_UA                | 2         | 0.42%   |
| nl_BE                | 2         | 0.42%   |
| ja_JP                | 2         | 0.42%   |
| fr_CA                | 2         | 0.42%   |
| es_CL                | 2         | 0.42%   |
| es_AR                | 2         | 0.42%   |
| en_ZA                | 2         | 0.42%   |
| en_US.UTF8           | 2         | 0.42%   |
| en_MX                | 2         | 0.42%   |
| zh_TW                | 1         | 0.21%   |
| tr_TR.UTF8           | 1         | 0.21%   |
| tr_TR                | 1         | 0.21%   |
| sv_SE                | 1         | 0.21%   |
| ru_UA                | 1         | 0.21%   |
| lt_LT                | 1         | 0.21%   |
| ko_KR                | 1         | 0.21%   |
| fr_BE                | 1         | 0.21%   |
| en_US@euro           | 1         | 0.21%   |
| en_NZ                | 1         | 0.21%   |
| en_IE                | 1         | 0.21%   |
| en_FR                | 1         | 0.21%   |
| de_DE.UTF8           | 1         | 0.21%   |
| de_DE.iso885915@euro | 1         | 0.21%   |
| de_CH                | 1         | 0.21%   |
| cs_CZ                | 1         | 0.21%   |
| ca_ES                | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 347       | 74.95%  |
| BIOS | 116       | 25.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 282       | 61.44%  |
| Btrfs    | 105       | 22.88%  |
| Xfs      | 20        | 4.36%   |
| Unknown  | 19        | 4.14%   |
| F2fs     | 15        | 3.27%   |
| Zfs      | 11        | 2.4%    |
| Reiserfs | 2         | 0.44%   |
| Ext3     | 2         | 0.44%   |
| XXXXXXX  | 1         | 0.22%   |
| Jfs      | 1         | 0.22%   |
| Ext2     | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 381       | 83.01%  |
| MBR     | 45        | 9.8%    |
| Unknown | 33        | 7.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 352       | 75.7%   |
| Yes       | 113       | 24.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 314       | 67.97%  |
| Yes       | 148       | 32.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 136       | 30.09%  |
| Dell                | 85        | 18.81%  |
| Hewlett-Packard     | 61        | 13.5%   |
| ASUSTek Computer    | 46        | 10.18%  |
| Acer                | 26        | 5.75%   |
| Apple               | 14        | 3.1%    |
| MSI                 | 13        | 2.88%   |
| Timi                | 8         | 1.77%   |
| Samsung Electronics | 7         | 1.55%   |
| HUAWEI              | 7         | 1.55%   |
| TUXEDO              | 6         | 1.33%   |
| Toshiba             | 6         | 1.33%   |
| Unknown             | 4         | 0.88%   |
| Razer               | 3         | 0.66%   |
| System76            | 2         | 0.44%   |
| Positivo            | 2         | 0.44%   |
| Notebook            | 2         | 0.44%   |
| Medion              | 2         | 0.44%   |
| IBM                 | 2         | 0.44%   |
| Fujitsu             | 2         | 0.44%   |
| Framework           | 2         | 0.44%   |
| Chuwi               | 2         | 0.44%   |
| XMG                 | 1         | 0.22%   |
| Wortmann AG         | 1         | 0.22%   |
| Sony                | 1         | 0.22%   |
| SIEMENS             | 1         | 0.22%   |
| SECO                | 1         | 0.22%   |
| Schenker            | 1         | 0.22%   |
| Purism              | 1         | 0.22%   |
| PC Specialist       | 1         | 0.22%   |
| MOTILE              | 1         | 0.22%   |
| LG Electronics      | 1         | 0.22%   |
| Jumper              | 1         | 0.22%   |
| IT Channel Pty      | 1         | 0.22%   |
| Google              | 1         | 0.22%   |
| BANGHO              | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 11        | 2.43%   |
| Dell XPS 15 9570                     | 4         | 0.88%   |
| Dell XPS 13 9310                     | 4         | 0.88%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE | 3         | 0.66%   |
| Lenovo Legion Y530-15ICH 81FV        | 3         | 0.66%   |
| HP Pavilion Notebook                 | 3         | 0.66%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 3         | 0.66%   |
| HP OMEN by HP Laptop                 | 3         | 0.66%   |
| Dell XPS 17 9710                     | 3         | 0.66%   |
| Dell XPS 15 7590                     | 3         | 0.66%   |
| Dell XPS 13 9370                     | 3         | 0.66%   |
| Dell XPS 13 9360                     | 3         | 0.66%   |
| Dell Latitude E7440                  | 3         | 0.66%   |
| Dell Latitude 7390                   | 3         | 0.66%   |
| Toshiba NB100                        | 2         | 0.44%   |
| Timi RedmiBook 13 R                  | 2         | 0.44%   |
| Lenovo ThinkPad T480 20L5CTO1WW      | 2         | 0.44%   |
| Lenovo Legion R7000 2020 82B6        | 2         | 0.44%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 2         | 0.44%   |
| HUAWEI BOHK-WAX9X                    | 2         | 0.44%   |
| HP ProBook 455 G7                    | 2         | 0.44%   |
| HP Pavilion dv7                      | 2         | 0.44%   |
| HP Laptop 15s-eq0xxx                 | 2         | 0.44%   |
| HP EliteBook 855 G7 Notebook PC      | 2         | 0.44%   |
| Framework Laptop                     | 2         | 0.44%   |
| Dell XPS 13 9380                     | 2         | 0.44%   |
| Dell Precision 7560                  | 2         | 0.44%   |
| Dell Latitude E6530                  | 2         | 0.44%   |
| Dell Latitude E6430                  | 2         | 0.44%   |
| Dell Latitude 5480                   | 2         | 0.44%   |
| Dell Inspiron 5577                   | 2         | 0.44%   |
| Dell G3 3500                         | 2         | 0.44%   |
| ASUS X550ZA                          | 2         | 0.44%   |
| ASUS N501VW                          | 2         | 0.44%   |
| Apple MacBookPro8,2                  | 2         | 0.44%   |
| Apple MacBookPro11,3                 | 2         | 0.44%   |
| Acer Nitro AN515-53                  | 2         | 0.44%   |
| Acer Aspire V3-331                   | 2         | 0.44%   |
| Acer Aspire A315-42                  | 2         | 0.44%   |
| XMG C504                             | 1         | 0.22%   |
| Wortmann AG TERRA_MOBILE_1590S       | 1         | 0.22%   |
| TUXEDO Pulse 15 Gen1                 | 1         | 0.22%   |
| TUXEDO N24_25BU                      | 1         | 0.22%   |
| TUXEDO InfinityBook Pro 14 Gen6      | 1         | 0.22%   |
| TUXEDO Book_XA1510                   | 1         | 0.22%   |
| TUXEDO Book XC1711                   | 1         | 0.22%   |
| Toshiba Satellite L50-C              | 1         | 0.22%   |
| Toshiba Satellite L50-A-16G          | 1         | 0.22%   |
| Toshiba Satellite C850D-118          | 1         | 0.22%   |
| Toshiba Satellite A200               | 1         | 0.22%   |
| Timi RedmiBook Pro 15S               | 1         | 0.22%   |
| Timi RedmiBook Air 13                | 1         | 0.22%   |
| Timi RedmiBook 13                    | 1         | 0.22%   |
| Timi Mi Laptop Pro 15                | 1         | 0.22%   |
| Timi Mi Laptop Air 12.5              | 1         | 0.22%   |
| Timi A35                             | 1         | 0.22%   |
| System76 Lemur Pro                   | 1         | 0.22%   |
| System76 Gazelle                     | 1         | 0.22%   |
| Sony VPCSC41FM                       | 1         | 0.22%   |
| SIEMENS SIMATIC Field PG M6          | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 78        | 17.26%  |
| Dell Latitude       | 34        | 7.52%   |
| Dell XPS            | 28        | 6.19%   |
| Lenovo Legion       | 20        | 4.42%   |
| Lenovo IdeaPad      | 18        | 3.98%   |
| Acer Aspire         | 17        | 3.76%   |
| HP Pavilion         | 15        | 3.32%   |
| Dell Inspiron       | 12        | 2.65%   |
| Unknown             | 11        | 2.43%   |
| HP EliteBook        | 10        | 2.21%   |
| HP ProBook          | 9         | 1.99%   |
| HP OMEN             | 8         | 1.77%   |
| HP Laptop           | 7         | 1.55%   |
| ASUS ZenBook        | 7         | 1.55%   |
| Timi RedmiBook      | 5         | 1.11%   |
| Lenovo Yoga         | 5         | 1.11%   |
| HP ZBook            | 5         | 1.11%   |
| Dell Precision      | 5         | 1.11%   |
| ASUS ROG            | 5         | 1.11%   |
| Acer Nitro          | 5         | 1.11%   |
| Toshiba Satellite   | 4         | 0.88%   |
| ASUS VivoBook       | 4         | 0.88%   |
| Apple MacBookPro8   | 4         | 0.88%   |
| Razer Blade         | 3         | 0.66%   |
| Lenovo ThinkBook    | 3         | 0.66%   |
| Dell G3             | 3         | 0.66%   |
| Acer Swift          | 3         | 0.66%   |
| TUXEDO Book         | 2         | 0.44%   |
| Toshiba NB100       | 2         | 0.44%   |
| Timi Mi             | 2         | 0.44%   |
| MSI GF63            | 2         | 0.44%   |
| IBM ThinkPad        | 2         | 0.44%   |
| HUAWEI BOHK-WAX9X   | 2         | 0.44%   |
| Fujitsu LIFEBOOK    | 2         | 0.44%   |
| Framework Laptop    | 2         | 0.44%   |
| Dell G5             | 2         | 0.44%   |
| ASUS X550ZA         | 2         | 0.44%   |
| ASUS TUF            | 2         | 0.44%   |
| ASUS N501VW         | 2         | 0.44%   |
| ASUS ASUS           | 2         | 0.44%   |
| Apple MacBookPro11  | 2         | 0.44%   |
| XMG C504            | 1         | 0.22%   |
| Wortmann AG TERRA   | 1         | 0.22%   |
| TUXEDO Pulse        | 1         | 0.22%   |
| TUXEDO N24          | 1         | 0.22%   |
| TUXEDO InfinityBook | 1         | 0.22%   |
| Timi A35            | 1         | 0.22%   |
| System76 Lemur      | 1         | 0.22%   |
| System76 Gazelle    | 1         | 0.22%   |
| Sony VPCSC41FM      | 1         | 0.22%   |
| SIEMENS SIMATIC     | 1         | 0.22%   |
| SECO UDOO           | 1         | 0.22%   |
| Schenker XMG        | 1         | 0.22%   |
| Samsung RC530       | 1         | 0.22%   |
| Samsung R530        | 1         | 0.22%   |
| Samsung R425        | 1         | 0.22%   |
| Samsung NC10        | 1         | 0.22%   |
| Samsung N150P       | 1         | 0.22%   |
| Samsung 700T1C      | 1         | 0.22%   |
| Samsung 300E4C      | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 83        | 18.36%  |
| 2019    | 76        | 16.81%  |
| 2018    | 56        | 12.39%  |
| 2021    | 43        | 9.51%   |
| 2014    | 32        | 7.08%   |
| 2017    | 29        | 6.42%   |
| 2015    | 25        | 5.53%   |
| 2016    | 21        | 4.65%   |
| 2012    | 21        | 4.65%   |
| 2011    | 19        | 4.2%    |
| 2010    | 11        | 2.43%   |
| 2008    | 10        | 2.21%   |
| 2013    | 9         | 1.99%   |
| Unknown | 4         | 0.88%   |
| 2009    | 3         | 0.66%   |
| 2007    | 3         | 0.66%   |
| 2006    | 3         | 0.66%   |
| 2005    | 2         | 0.44%   |
| 2022    | 1         | 0.22%   |
| 2004    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 452       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 441       | 97.35%  |
| Enabled  | 12        | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 447       | 98.89%  |
| Yes  | 5         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 116       | 25.11%  |
| 8.01-16.0   | 102       | 22.08%  |
| 4.01-8.0    | 95        | 20.56%  |
| 32.01-64.0  | 62        | 13.42%  |
| 3.01-4.0    | 33        | 7.14%   |
| 64.01-256.0 | 15        | 3.25%   |
| 24.01-32.0  | 14        | 3.03%   |
| 1.01-2.0    | 12        | 2.6%    |
| 2.01-3.0    | 8         | 1.73%   |
| 0.51-1.0    | 4         | 0.87%   |
| 0.01-0.5    | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 144       | 27.32%  |
| 2.01-3.0   | 89        | 16.89%  |
| 4.01-8.0   | 84        | 15.94%  |
| 3.01-4.0   | 63        | 11.95%  |
| 0.51-1.0   | 52        | 9.87%   |
| 0.01-0.5   | 52        | 9.87%   |
| 8.01-16.0  | 39        | 7.4%    |
| 16.01-24.0 | 3         | 0.57%   |
| 24.01-32.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 313       | 67.17%  |
| 2      | 131       | 28.11%  |
| 3      | 16        | 3.43%   |
| 0      | 4         | 0.86%   |
| 4      | 2         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 380       | 83.33%  |
| Yes       | 76        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 356       | 77.73%  |
| No        | 102       | 22.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 98.89%  |
| No        | 5         | 1.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 394       | 86.4%   |
| No        | 62        | 13.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 77        | 16.89%  |
| Germany      | 66        | 14.47%  |
| Russia       | 43        | 9.43%   |
| France       | 22        | 4.82%   |
| UK           | 18        | 3.95%   |
| China        | 18        | 3.95%   |
| Italy        | 15        | 3.29%   |
| Canada       | 15        | 3.29%   |
| Poland       | 14        | 3.07%   |
| Netherlands  | 14        | 3.07%   |
| Spain        | 12        | 2.63%   |
| Ukraine      | 11        | 2.41%   |
| Sweden       | 9         | 1.97%   |
| Czechia      | 9         | 1.97%   |
| Greece       | 8         | 1.75%   |
| Australia    | 8         | 1.75%   |
| Turkey       | 7         | 1.54%   |
| Finland      | 6         | 1.32%   |
| Brazil       | 6         | 1.32%   |
| Belgium      | 6         | 1.32%   |
| Switzerland  | 5         | 1.1%    |
| Japan        | 5         | 1.1%    |
| India        | 5         | 1.1%    |
| Norway       | 4         | 0.88%   |
| South Africa | 3         | 0.66%   |
| Romania      | 3         | 0.66%   |
| Portugal     | 3         | 0.66%   |
| Mexico       | 3         | 0.66%   |
| Hong Kong    | 3         | 0.66%   |
| Belarus      | 3         | 0.66%   |
| Austria      | 3         | 0.66%   |
| Argentina    | 3         | 0.66%   |
| Vietnam      | 2         | 0.44%   |
| Taiwan       | 2         | 0.44%   |
| Slovenia     | 2         | 0.44%   |
| New Zealand  | 2         | 0.44%   |
| Iran         | 2         | 0.44%   |
| Indonesia    | 2         | 0.44%   |
| Hungary      | 2         | 0.44%   |
| Chile        | 2         | 0.44%   |
| Uruguay      | 1         | 0.22%   |
| Tunisia      | 1         | 0.22%   |
| Syria        | 1         | 0.22%   |
| South Korea  | 1         | 0.22%   |
| Slovakia     | 1         | 0.22%   |
| Singapore    | 1         | 0.22%   |
| Saudi Arabia | 1         | 0.22%   |
| Philippines  | 1         | 0.22%   |
| Nepal        | 1         | 0.22%   |
| Lithuania    | 1         | 0.22%   |
| Kazakhstan   | 1         | 0.22%   |
| Croatia      | 1         | 0.22%   |
| Bulgaria     | 1         | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Berlin                       | 17        | 3.42%   |
| Moscow                       | 15        | 3.02%   |
| St Petersburg                | 7         | 1.41%   |
| Athens                       | 7         | 1.41%   |
| Kyiv                         | 6         | 1.21%   |
| Guangzhou                    | 6         | 1.21%   |
| Munich                       | 5         | 1.01%   |
| Sydney                       | 4         | 0.8%    |
| Paris                        | 4         | 0.8%    |
| Istanbul                     | 4         | 0.8%    |
| Beijing                      | 4         | 0.8%    |
| Warsaw                       | 3         | 0.6%    |
| Stockholm                    | 3         | 0.6%    |
| San Jose                     | 3         | 0.6%    |
| Prague                       | 3         | 0.6%    |
| Minsk                        | 3         | 0.6%    |
| Melbourne                    | 3         | 0.6%    |
| Manitowoc                    | 3         | 0.6%    |
| Heraklion                    | 3         | 0.6%    |
| Helsinki                     | 3         | 0.6%    |
| Hamburg                      | 3         | 0.6%    |
| Frankfurt am Main            | 3         | 0.6%    |
| Amsterdam                    | 3         | 0.6%    |
| Zhengzhou                    | 2         | 0.4%    |
| Wuelfrath                    | 2         | 0.4%    |
| Wroclaw                      | 2         | 0.4%    |
| Winnipeg                     | 2         | 0.4%    |
| Wetzlar                      | 2         | 0.4%    |
| West Orange                  | 2         | 0.4%    |
| Vleuten                      | 2         | 0.4%    |
| Vladivostok                  | 2         | 0.4%    |
| Vienna                       | 2         | 0.4%    |
| Vancouver                    | 2         | 0.4%    |
| TromsÃ¸                    | 2         | 0.4%    |
| Tehran                       | 2         | 0.4%    |
| Smolensk                     | 2         | 0.4%    |
| Shelby                       | 2         | 0.4%    |
| San Francisco                | 2         | 0.4%    |
| Saltillo                     | 2         | 0.4%    |
| Rome                         | 2         | 0.4%    |
| Rochester                    | 2         | 0.4%    |
| Omsk                         | 2         | 0.4%    |
| Mountain Home                | 2         | 0.4%    |
| Montreal                     | 2         | 0.4%    |
| Milan                        | 2         | 0.4%    |
| MariÃ¡nskÃ© LÃ¡znÄ› | 2         | 0.4%    |
| Madrid                       | 2         | 0.4%    |
| Los Angeles                  | 2         | 0.4%    |
| London                       | 2         | 0.4%    |
| Ljubljana                    | 2         | 0.4%    |
| Leipzig                      | 2         | 0.4%    |
| Jena                         | 2         | 0.4%    |
| Ingolstadt                   | 2         | 0.4%    |
| Huxi                         | 2         | 0.4%    |
| Hoboken                      | 2         | 0.4%    |
| Ho Chi Minh City             | 2         | 0.4%    |
| GoiÃ¢nia                   | 2         | 0.4%    |
| Fulda                        | 2         | 0.4%    |
| College Station              | 2         | 0.4%    |
| Cesson                       | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 141       | 225    | 23.9%   |
| WDC                            | 90        | 130    | 15.25%  |
| Seagate                        | 46        | 61     | 7.8%    |
| SK Hynix                       | 41        | 50     | 6.95%   |
| Toshiba                        | 40        | 45     | 6.78%   |
| Intel                          | 38        | 61     | 6.44%   |
| Unknown                        | 26        | 37     | 4.41%   |
| SanDisk                        | 24        | 43     | 4.07%   |
| HGST                           | 23        | 24     | 3.9%    |
| Kingston                       | 21        | 28     | 3.56%   |
| Micron Technology              | 16        | 18     | 2.71%   |
| Crucial                        | 10        | 11     | 1.69%   |
| KIOXIA                         | 9         | 11     | 1.53%   |
| Hitachi                        | 8         | 8      | 1.36%   |
| Apple                          | 6         | 8      | 1.02%   |
| A-DATA Technology              | 5         | 13     | 0.85%   |
| LITEON                         | 4         | 6      | 0.68%   |
| Fujitsu                        | 4         | 5      | 0.68%   |
| OCZ                            | 3         | 5      | 0.51%   |
| Lenovo                         | 3         | 5      | 0.51%   |
| China                          | 3         | 7      | 0.51%   |
| Transcend                      | 2         | 6      | 0.34%   |
| PHISON                         | 2         | 2      | 0.34%   |
| Netac                          | 2         | 2      | 0.34%   |
| MyDigitalSSD                   | 2         | 2      | 0.34%   |
| LITEONIT                       | 2         | 3      | 0.34%   |
| XrayDisk                       | 1         | 1      | 0.17%   |
| XPG                            | 1         | 1      | 0.17%   |
| SPCC                           | 1         | 1      | 0.17%   |
| Solid State Storage Technology | 1         | 1      | 0.17%   |
| ShanDianZhe                    | 1         | 2      | 0.17%   |
| RevuAhn                        | 1         | 1      | 0.17%   |
| PLEXTOR                        | 1         | 1      | 0.17%   |
| OSCOO                          | 1         | 1      | 0.17%   |
| Mushkin                        | 1         | 1      | 0.17%   |
| Lite-On                        | 1         | 1      | 0.17%   |
| Linux                          | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA                 | 1         | 4      | 0.17%   |
| Kingmax                        | 1         | 1      | 0.17%   |
| KingDian                       | 1         | 1      | 0.17%   |
| IBM/Hitachi                    | 1         | 1      | 0.17%   |
| faspeed                        | 1         | 1      | 0.17%   |
| e2e4                           | 1         | 1      | 0.17%   |
| BIWIN                          | 1         | 1      | 0.17%   |
| ASUS-PHISON                    | 1         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 14        | 2.23%   |
| Intel SSDPEKNW010T8 1TB                | 9         | 1.43%   |
| Samsung SSD 850 EVO 250GB              | 8         | 1.27%   |
| Samsung MZVLB512HBJQ-000L2 512GB       | 8         | 1.27%   |
| Seagate ST1000LM049-2GH172 1TB         | 6         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB         | 6         | 0.96%   |
| Samsung SSD 970 EVO Plus 500GB         | 6         | 0.96%   |
| Unknown MMC Card  16GB                 | 5         | 0.8%    |
| Samsung SSD 980 PRO 2TB                | 5         | 0.8%    |
| Samsung SSD 860 EVO 500GB              | 5         | 0.8%    |
| Samsung NVMe SSD Drive 512GB           | 5         | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 4         | 0.64%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 4         | 0.64%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 4         | 0.64%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.64%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 0.64%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 4         | 0.64%   |
| SK Hynix PC711 NVMe 1TB                | 4         | 0.64%   |
| Samsung SSD 970 EVO Plus 250GB         | 4         | 0.64%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.64%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 4         | 0.64%   |
| Samsung MZVLB512HAJQ-00000 512GB       | 4         | 0.64%   |
| Samsung MZALQ512HALU-000L2 512GB       | 4         | 0.64%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.64%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.64%   |
| Intel SSDPEKNU512GZ 512GB              | 4         | 0.64%   |
| Intel SSDPEKKF256G8L 256GB             | 4         | 0.64%   |
| HGST HTS541010A9E680 1TB               | 4         | 0.64%   |
| WDC WD16 00BB-55GUA0 160GB             | 3         | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.48%   |
| Toshiba KXG60ZNV512G NVMe KIOXIA 512GB | 3         | 0.48%   |
| SK Hynix SKHynix_HFS512GDE9X084N 512GB | 3         | 0.48%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB   | 3         | 0.48%   |
| SK Hynix SC311 SATA 256GB SSD          | 3         | 0.48%   |
| Seagate ST2000LX001-1RG174 2TB         | 3         | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB         | 3         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.48%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.48%   |
| Samsung SSD 980 1TB                    | 3         | 0.48%   |
| Samsung SSD 970 PRO 512GB              | 3         | 0.48%   |
| Samsung SSD 860 QVO 1TB                | 3         | 0.48%   |
| Samsung SSD 850 EVO 1TB                | 3         | 0.48%   |
| Samsung Portable SSD T5 500GB          | 3         | 0.48%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 3         | 0.48%   |
| KIOXIA KBG40ZNV512G 512GB              | 3         | 0.48%   |
| KIOXIA KBG40ZNS256G NVMe 256GB         | 3         | 0.48%   |
| Intel SSDPEKNW512G8 512GB              | 3         | 0.48%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 2         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.32%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 2         | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.32%   |
| WDC WD10JPVX-75JC3T0 1TB               | 2         | 0.32%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 2         | 0.32%   |
| WDC PC SN730 NVMe 1024GB               | 2         | 0.32%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB   | 2         | 0.32%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 2         | 0.32%   |
| WDC PC SN530 NVMe 512GB                | 2         | 0.32%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB   | 2         | 0.32%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB   | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 59     | 32.84%  |
| WDC                 | 36        | 43     | 26.87%  |
| HGST                | 23        | 24     | 17.16%  |
| Toshiba             | 17        | 18     | 12.69%  |
| Hitachi             | 8         | 8      | 5.97%   |
| Fujitsu             | 4         | 5      | 2.99%   |
| Samsung Electronics | 1         | 2      | 0.75%   |
| IBM/Hitachi         | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 90     | 32.45%  |
| SanDisk             | 19        | 38     | 10.11%  |
| WDC                 | 12        | 25     | 6.38%   |
| Kingston            | 12        | 19     | 6.38%   |
| SK Hynix            | 11        | 12     | 5.85%   |
| Intel               | 11        | 11     | 5.85%   |
| Micron Technology   | 8         | 9      | 4.26%   |
| Crucial             | 8         | 9      | 4.26%   |
| Toshiba             | 5         | 6      | 2.66%   |
| A-DATA Technology   | 5         | 13     | 2.66%   |
| Apple               | 4         | 5      | 2.13%   |
| OCZ                 | 3         | 5      | 1.6%    |
| China               | 3         | 7      | 1.6%    |
| Transcend           | 2         | 6      | 1.06%   |
| Netac               | 2         | 2      | 1.06%   |
| MyDigitalSSD        | 2         | 2      | 1.06%   |
| LITEONIT            | 2         | 3      | 1.06%   |
| XrayDisk            | 1         | 1      | 0.53%   |
| SPCC                | 1         | 1      | 0.53%   |
| ShanDianZhe         | 1         | 2      | 0.53%   |
| Seagate             | 1         | 1      | 0.53%   |
| RevuAhn             | 1         | 1      | 0.53%   |
| PLEXTOR             | 1         | 1      | 0.53%   |
| PHISON              | 1         | 1      | 0.53%   |
| Mushkin             | 1         | 1      | 0.53%   |
| LITEON              | 1         | 2      | 0.53%   |
| Lite-On             | 1         | 1      | 0.53%   |
| Linux               | 1         | 1      | 0.53%   |
| Lenovo              | 1         | 2      | 0.53%   |
| Kingmax             | 1         | 1      | 0.53%   |
| KingDian            | 1         | 1      | 0.53%   |
| faspeed             | 1         | 1      | 0.53%   |
| e2e4                | 1         | 1      | 0.53%   |
| BIWIN               | 1         | 1      | 0.53%   |
| ASUS-PHISON         | 1         | 2      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 241       | 357    | 42.5%   |
| SSD     | 171       | 284    | 30.16%  |
| HDD     | 127       | 160    | 22.4%   |
| MMC     | 26        | 35     | 4.59%   |
| Unknown | 2         | 4      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 257       | 433    | 47.95%  |
| NVMe | 241       | 357    | 44.96%  |
| MMC  | 26        | 35     | 4.85%   |
| SAS  | 12        | 15     | 2.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 175       | 288    | 59.12%  |
| 0.51-1.0   | 107       | 136    | 36.15%  |
| 1.01-2.0   | 13        | 19     | 4.39%   |
| 4.01-10.0  | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 126       | 25.87%  |
| 101-250        | 109       | 22.38%  |
| 501-1000       | 89        | 18.28%  |
| 1001-2000      | 50        | 10.27%  |
| 51-100         | 33        | 6.78%   |
| 1-20           | 29        | 5.95%   |
| Unknown        | 24        | 4.93%   |
| 21-50          | 12        | 2.46%   |
| More than 3000 | 8         | 1.64%   |
| 2001-3000      | 7         | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 124       | 24.03%  |
| 21-50          | 90        | 17.44%  |
| 101-250        | 83        | 16.09%  |
| 251-500        | 74        | 14.34%  |
| 51-100         | 63        | 12.21%  |
| 501-1000       | 38        | 7.36%   |
| Unknown        | 24        | 4.65%   |
| 1001-2000      | 15        | 2.91%   |
| 2001-3000      | 3         | 0.58%   |
| More than 3000 | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                  | 3         | 4      | 6.12%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD     | 2         | 2      | 4.08%   |
| Seagate ST2000LX001-1RG174 2TB            | 2         | 2      | 4.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 2         | 13     | 4.08%   |
| Samsung Electronics SSD 850 EVO 1TB       | 2         | 2      | 4.08%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 2.04%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 2.04%   |
| WDC WD10EZEX-08M2NA0 1TB                  | 1         | 1      | 2.04%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD  | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 2.04%   |
| Toshiba MK4026GAX 40GB                    | 1         | 1      | 2.04%   |
| Toshiba MK1629GSG 160GB                   | 1         | 1      | 2.04%   |
| SK Hynix SH920 mSATA 256GB SSD            | 1         | 1      | 2.04%   |
| SK Hynix SC210 mSATA 128GB SSD            | 1         | 2      | 2.04%   |
| Seagate ST9750420AS 752GB                 | 1         | 1      | 2.04%   |
| Seagate ST9100824AS 100GB                 | 1         | 1      | 2.04%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 2.04%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 4      | 2.04%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 1      | 2.04%   |
| SanDisk SSD PLUS 480GB                    | 1         | 1      | 2.04%   |
| SanDisk SD9SN8W 128GB SSD                 | 1         | 1      | 2.04%   |
| SanDisk SD7SB2Q512G1001 512GB SSD         | 1         | 1      | 2.04%   |
| Samsung Electronics SSD SM841 mSATA 512GB | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 2TB       | 1         | 1      | 2.04%   |
| Samsung Electronics HM160HC 160GB         | 1         | 1      | 2.04%   |
| LITEON CV8-8E128-HP 128GB SSD             | 1         | 2      | 2.04%   |
| Intel SSDSCKKF256G8H 256GB                | 1         | 1      | 2.04%   |
| Intel SSDSC2BW480A4 480GB                 | 1         | 1      | 2.04%   |
| Intel SSDSC2BW180A3L 180GB                | 1         | 1      | 2.04%   |
| Intel SSDPEKKF256G8L 256GB                | 1         | 1      | 2.04%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB         | 1         | 1      | 2.04%   |
| Hitachi HTS723225L9SA62 250GB             | 1         | 1      | 2.04%   |
| Hitachi HTS547550A9E384 500GB             | 1         | 1      | 2.04%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 1      | 2.04%   |
| Hitachi HTS542525K9A300 250GB             | 1         | 1      | 2.04%   |
| HGST HTS725050A7E635 OPAL 500GB           | 1         | 1      | 2.04%   |
| HGST HTS541010B7E610 1TB                  | 1         | 1      | 2.04%   |
| Fujitsu MHZ2160BJ G2 160GB                | 1         | 1      | 2.04%   |
| Fujitsu MHT2080AH 80GB                    | 1         | 1      | 2.04%   |
| Crucial CT1000P1SSD8 1TB                  | 1         | 1      | 2.04%   |
| A-DATA Technology SP550 240GB SSD         | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 13     | 18.75%  |
| Samsung Electronics | 5         | 5      | 10.42%  |
| HGST                | 5         | 6      | 10.42%  |
| Toshiba             | 4         | 4      | 8.33%   |
| SK Hynix            | 4         | 5      | 8.33%   |
| SanDisk             | 4         | 16     | 8.33%   |
| Intel               | 4         | 4      | 8.33%   |
| Hitachi             | 4         | 4      | 8.33%   |
| WDC                 | 3         | 3      | 6.25%   |
| Fujitsu             | 2         | 2      | 4.17%   |
| LITEON              | 1         | 2      | 2.08%   |
| IBM/Hitachi         | 1         | 1      | 2.08%   |
| Crucial             | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 13     | 32.14%  |
| HGST                | 5         | 6      | 17.86%  |
| Hitachi             | 4         | 4      | 14.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Fujitsu             | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| IBM/Hitachi         | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 33     | 58.33%  |
| SSD  | 18        | 32     | 37.5%   |
| NVMe | 2         | 2      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 50%     |
| Hitachi HTS721010G9SA00 100GB    | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 381       | 663    | 75.6%   |
| Detected | 74        | 108    | 14.68%  |
| Malfunc  | 47        | 67     | 9.33%   |
| Failed   | 2         | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 285       | 49.22%  |
| Samsung Electronics            | 96        | 16.58%  |
| AMD                            | 58        | 10.02%  |
| Sandisk                        | 47        | 8.12%   |
| SK Hynix                       | 30        | 5.18%   |
| Toshiba America Info Systems   | 19        | 3.28%   |
| KIOXIA                         | 9         | 1.55%   |
| Kingston Technology Company    | 9         | 1.55%   |
| Micron Technology              | 8         | 1.38%   |
| Lite-On Technology             | 3         | 0.52%   |
| Nvidia                         | 2         | 0.35%   |
| Micron/Crucial Technology      | 2         | 0.35%   |
| Lenovo                         | 2         | 0.35%   |
| Apple                          | 2         | 0.35%   |
| Union Memory (Shenzhen)        | 1         | 0.17%   |
| Solid State Storage Technology | 1         | 0.17%   |
| Silicon Motion                 | 1         | 0.17%   |
| Seagate Technology             | 1         | 0.17%   |
| Phison Electronics             | 1         | 0.17%   |
| JMicron Technology             | 1         | 0.17%   |
| ADATA Technology               | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 57        | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 53        | 8.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 36        | 5.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 31        | 5.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 4.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 19        | 3.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 19        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 2.96%   |
| SK Hynix Gold P31 SSD                                                            | 15        | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 2.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 14        | 2.3%    |
| Intel SSD 660P Series                                                            | 14        | 2.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.3%    |
| Samsung NVMe SSD Controller 980                                                  | 13        | 2.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 12        | 1.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 1.81%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 10        | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10        | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 8         | 1.32%   |
| Micron Non-Volatile memory controller                                            | 8         | 1.32%   |
| KIOXIA Non-Volatile memory controller                                            | 8         | 1.32%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.15%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 6         | 0.99%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.99%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.82%   |
| SK Hynix Non-Volatile memory controller                                          | 5         | 0.82%   |
| Sandisk Non-Volatile memory controller                                           | 5         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.82%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.66%   |
| Intel Non-Volatile memory controller                                             | 4         | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.66%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.49%   |
| Lite-On Non-Volatile memory controller                                           | 3         | 0.49%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.49%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.49%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 0.33%   |
| Toshiba America Info Systems NVMe Controller                                     | 2         | 0.33%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.33%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.33%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.33%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.33%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.33%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.33%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.33%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 280       | 47.78%  |
| NVMe | 244       | 41.64%  |
| RAID | 37        | 6.31%   |
| IDE  | 25        | 4.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 350       | 77.43%  |
| AMD          | 99        | 21.9%   |
| PowerBook5,6 | 1         | 0.22%   |
| PowerBook5,4 | 1         | 0.22%   |
| PowerBook3,4 | 1         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 3.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 3.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 3.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 2.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 2.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 2.43%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 11        | 2.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 2.21%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.99%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 1.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.77%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 1.77%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 1.33%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.33%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 1.11%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.11%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.11%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.88%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.88%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.88%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 3         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.66%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.66%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 3         | 0.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.66%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.66%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 3         | 0.66%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.66%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 3         | 0.66%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.44%   |
| Intel Pentium 3556U @ 1.70GHz                 | 2         | 0.44%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.44%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.44%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.44%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.44%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.44%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.44%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.44%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.44%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 2         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 163       | 36.06%  |
| Intel Core i5           | 92        | 20.35%  |
| AMD Ryzen 7             | 40        | 8.85%   |
| Other                   | 36        | 7.96%   |
| AMD Ryzen 5             | 19        | 4.2%    |
| AMD Ryzen 7 PRO         | 14        | 3.1%    |
| Intel Celeron           | 11        | 2.43%   |
| Intel Core 2 Duo        | 10        | 2.21%   |
| Intel Atom              | 8         | 1.77%   |
| Intel Core i9           | 7         | 1.55%   |
| Intel Pentium           | 6         | 1.33%   |
| Intel Core i3           | 6         | 1.33%   |
| AMD A6                  | 5         | 1.11%   |
| Intel Pentium M         | 4         | 0.88%   |
| AMD Ryzen 9             | 4         | 0.88%   |
| Intel Core m3           | 3         | 0.66%   |
| AMD Ryzen 5 PRO         | 3         | 0.66%   |
| AMD Ryzen 3             | 3         | 0.66%   |
| AMD A8                  | 3         | 0.66%   |
| Intel Xeon              | 2         | 0.44%   |
| Intel Genuine           | 2         | 0.44%   |
| Intel Pentium Silver    | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| Intel Celeron M         | 1         | 0.22%   |
| AMD Turion II Dual-Core | 1         | 0.22%   |
| AMD E1                  | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |
| AMD Athlon Neo X2       | 1         | 0.22%   |
| AMD Athlon 64           | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |
| AMD A12                 | 1         | 0.22%   |
| AMD A10                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 192       | 42.48%  |
| 2       | 120       | 26.55%  |
| 8       | 68        | 15.04%  |
| 6       | 55        | 12.17%  |
| 1       | 13        | 2.88%   |
| Unknown | 2         | 0.44%   |
| 14      | 1         | 0.22%   |
| 12      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 450       | 99.56%  |
| Unknown | 2         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 377       | 83.22%  |
| 1       | 74        | 16.34%  |
| Unknown | 2         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 436       | 96.46%  |
| 32-bit         | 13        | 2.88%   |
| Unknown        | 3         | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 12.88%  |
| 0x906ea    | 37        | 7.94%   |
| 0x806ea    | 29        | 6.22%   |
| 0x806ec    | 22        | 4.72%   |
| 0x206a7    | 19        | 4.08%   |
| 0x806c1    | 17        | 3.65%   |
| 0x08600106 | 17        | 3.65%   |
| 0x306a9    | 16        | 3.43%   |
| 0x806e9    | 15        | 3.22%   |
| 0x506e3    | 15        | 3.22%   |
| 0x40651    | 15        | 3.22%   |
| 0xa0652    | 14        | 3%      |
| 0x0a50000c | 14        | 3%      |
| 0x906e9    | 12        | 2.58%   |
| 0x806d1    | 11        | 2.36%   |
| 0x306d4    | 11        | 2.36%   |
| 0x08600103 | 11        | 2.36%   |
| 0x306c3    | 10        | 2.15%   |
| 0x08108109 | 10        | 2.15%   |
| 0x406e3    | 9         | 1.93%   |
| 0x08108102 | 9         | 1.93%   |
| 0x906ed    | 8         | 1.72%   |
| 0x30678    | 8         | 1.72%   |
| 0x08600104 | 6         | 1.29%   |
| 0x806eb    | 5         | 1.07%   |
| 0x706e5    | 4         | 0.86%   |
| 0x6d8      | 4         | 0.86%   |
| 0x706a1    | 3         | 0.64%   |
| 0x6fb      | 3         | 0.64%   |
| 0x106c2    | 3         | 0.64%   |
| 0x1067a    | 3         | 0.64%   |
| 0x10676    | 3         | 0.64%   |
| 0x08608103 | 3         | 0.64%   |
| 0x06003106 | 3         | 0.64%   |
| 0x6e8      | 2         | 0.43%   |
| 0x406c4    | 2         | 0.43%   |
| 0x40661    | 2         | 0.43%   |
| 0x20655    | 2         | 0.43%   |
| 0x0a50000b | 2         | 0.43%   |
| 0x08600102 | 2         | 0.43%   |
| 0x0810100b | 2         | 0.43%   |
| 0xa0671    | 1         | 0.21%   |
| 0xa0660    | 1         | 0.21%   |
| 0x906a3    | 1         | 0.21%   |
| 0x806c2    | 1         | 0.21%   |
| 0x706a8    | 1         | 0.21%   |
| 0x6fd      | 1         | 0.21%   |
| 0x6f6      | 1         | 0.21%   |
| 0x6d6      | 1         | 0.21%   |
| 0x406c3    | 1         | 0.21%   |
| 0x20652    | 1         | 0.21%   |
| 0x106ca    | 1         | 0.21%   |
| 0x08701013 | 1         | 0.21%   |
| 0x08608102 | 1         | 0.21%   |
| 0x08101007 | 1         | 0.21%   |
| 0x08001105 | 1         | 0.21%   |
| 0x07030105 | 1         | 0.21%   |
| 0x0700010b | 1         | 0.21%   |
| 0x06006705 | 1         | 0.21%   |
| 0x0600611a | 1         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 148       | 32.67%  |
| Zen 2            | 41        | 9.05%   |
| Haswell          | 28        | 6.18%   |
| Skylake          | 26        | 5.74%   |
| SandyBridge      | 21        | 4.64%   |
| TigerLake        | 20        | 4.42%   |
| Zen+             | 19        | 4.19%   |
| IvyBridge        | 17        | 3.75%   |
| Zen 3            | 16        | 3.53%   |
| Icelake          | 15        | 3.31%   |
| CometLake        | 15        | 3.31%   |
| Broadwell        | 12        | 2.65%   |
| Unknown          | 12        | 2.65%   |
| Silvermont       | 11        | 2.43%   |
| P6               | 7         | 1.55%   |
| Westmere         | 6         | 1.32%   |
| Penryn           | 6         | 1.32%   |
| Core             | 5         | 1.1%    |
| Zen              | 4         | 0.88%   |
| Goldmont plus    | 4         | 0.88%   |
| Bonnell          | 4         | 0.88%   |
| Steamroller      | 3         | 0.66%   |
| Puma             | 2         | 0.44%   |
| K8 Hammer        | 2         | 0.44%   |
| K10 Llano        | 2         | 0.44%   |
| Excavator        | 2         | 0.44%   |
| Bobcat           | 2         | 0.44%   |
| Jaguar           | 1         | 0.22%   |
| Goldmont         | 1         | 0.22%   |
| Alderlake Hybrid | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 316       | 51.89%  |
| Nvidia | 180       | 29.56%  |
| AMD    | 113       | 18.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 6.91%   |
| AMD Renoir                                                                               | 37        | 5.95%   |
| Intel UHD Graphics 620                                                                   | 34        | 5.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 3.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 3.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 3.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 3.05%   |
| Intel HD Graphics 530                                                                    | 16        | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 2.25%   |
| Intel HD Graphics 620                                                                    | 14        | 2.25%   |
| AMD Cezanne                                                                              | 13        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 9         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.45%   |
| Intel HD Graphics 630                                                                    | 8         | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 1.13%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 1.13%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.96%   |
| Nvidia TU117M                                                                            | 6         | 0.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.96%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.64%   |
| AMD Lucienne                                                                             | 4         | 0.64%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.48%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.48%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.48%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 3         | 0.48%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.48%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.48%   |
| Intel UHD Graphics 615                                                                   | 3         | 0.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.48%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.48%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.48%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.32%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.32%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 2         | 0.32%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.32%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.32%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.32%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.32%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.32%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.32%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 2         | 0.32%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 174       | 38.24%  |
| Intel + Nvidia | 129       | 28.35%  |
| 1 x AMD        | 81        | 17.8%   |
| 1 x Nvidia     | 37        | 8.13%   |
| AMD + Nvidia   | 15        | 3.3%    |
| Intel + AMD    | 12        | 2.64%   |
| 2 x AMD        | 6         | 1.32%   |
| 2 x Nvidia     | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 356       | 76.39%  |
| Proprietary | 97        | 20.82%  |
| Unknown     | 13        | 2.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 270       | 58.19%  |
| 0.01-0.5   | 67        | 14.44%  |
| 1.01-2.0   | 46        | 9.91%   |
| 3.01-4.0   | 37        | 7.97%   |
| 0.51-1.0   | 16        | 3.45%   |
| 5.01-6.0   | 15        | 3.23%   |
| 7.01-8.0   | 8         | 1.72%   |
| 8.01-16.0  | 3         | 0.65%   |
| 2.01-3.0   | 2         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 98        | 17.82%  |
| LG Display              | 80        | 14.55%  |
| BOE                     | 71        | 12.91%  |
| Chimei Innolux          | 65        | 11.82%  |
| Samsung Electronics     | 42        | 7.64%   |
| Sharp                   | 33        | 6%      |
| Dell                    | 32        | 5.82%   |
| Apple                   | 17        | 3.09%   |
| Chi Mei Optoelectronics | 13        | 2.36%   |
| Lenovo                  | 9         | 1.64%   |
| Goldstar                | 8         | 1.45%   |
| CSO                     | 7         | 1.27%   |
| PANDA                   | 6         | 1.09%   |
| Hewlett-Packard         | 6         | 1.09%   |
| InfoVision              | 5         | 0.91%   |
| BenQ                    | 5         | 0.91%   |
| AOC                     | 5         | 0.91%   |
| Ancor Communications    | 5         | 0.91%   |
| Philips                 | 4         | 0.73%   |
| Iiyama                  | 4         | 0.73%   |
| Acer                    | 4         | 0.73%   |
| ViewSonic               | 3         | 0.55%   |
| ASUSTek Computer        | 3         | 0.55%   |
| Sony                    | 2         | 0.36%   |
| LGD                     | 2         | 0.36%   |
| Gigabyte Technology     | 2         | 0.36%   |
| Fujitsu Siemens         | 2         | 0.36%   |
| Eizo                    | 2         | 0.36%   |
| CMN                     | 2         | 0.36%   |
| WST                     | 1         | 0.18%   |
| Unknown                 | 1         | 0.18%   |
| Toshiba                 | 1         | 0.18%   |
| TMX                     | 1         | 0.18%   |
| RTK                     | 1         | 0.18%   |
| QBell                   | 1         | 0.18%   |
| MSI                     | 1         | 0.18%   |
| Mi                      | 1         | 0.18%   |
| LG Philips              | 1         | 0.18%   |
| IBM                     | 1         | 0.18%   |
| HannStar                | 1         | 0.18%   |
| Gateway                 | 1         | 0.18%   |
| CPT                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 1.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 6         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 1.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.9%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.72%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.54%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.54%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 3         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.54%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.54%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                        | 3         | 0.54%   |
| Dell U2414H DELA0A3 1920x1080 527x296mm 23.8-inch                        | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.54%   |
| BOE LCD Monitor BOE0898 1920x1080 294x165mm 13.3-inch                    | 3         | 0.54%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x174mm 14.0-inch           | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch           | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.54%   |
| Apple Color LCD APP9C20 1280x854 321x214mm 15.2-inch                     | 3         | 0.54%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.36%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 2         | 0.36%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 2         | 0.36%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 2         | 0.36%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 2         | 0.36%   |
| Samsung Electronics U28E570 SAM0D71 3840x2160 608x345mm 27.5-inch        | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch    | 2         | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.36%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.36%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.36%   |
| LG Display LCD Monitor LGD06E0 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD054F 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.36%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch         | 2         | 0.36%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 520x320mm 24.0-inch         | 2         | 0.36%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                        | 2         | 0.36%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 2         | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14E4 1920x1080 309x173mm 13.9-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 2         | 0.36%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 276       | 53.7%   |
| 1366x768 (WXGA)    | 62        | 12.06%  |
| 3840x2160 (4K)     | 30        | 5.84%   |
| 2560x1440 (QHD)    | 24        | 4.67%   |
| 1600x900 (HD+)     | 18        | 3.5%    |
| 1920x1200 (WUXGA)  | 12        | 2.33%   |
| 2560x1600          | 10        | 1.95%   |
| 3840x2400          | 9         | 1.75%   |
| 1440x900 (WXGA+)   | 9         | 1.75%   |
| 1680x1050 (WSXGA+) | 8         | 1.56%   |
| 1280x800 (WXGA)    | 8         | 1.56%   |
| 3440x1440          | 6         | 1.17%   |
| 2880x1800          | 4         | 0.78%   |
| 1280x1024 (SXGA)   | 4         | 0.78%   |
| 1024x600           | 4         | 0.78%   |
| 3200x1800 (QHD+)   | 3         | 0.58%   |
| 1280x854           | 3         | 0.58%   |
| 3840x1080          | 2         | 0.39%   |
| 2256x1504          | 2         | 0.39%   |
| 2160x1440          | 2         | 0.39%   |
| 2048x1152          | 2         | 0.39%   |
| Unknown            | 2         | 0.39%   |
| 5040x1080          | 1         | 0.19%   |
| 3840x1200          | 1         | 0.19%   |
| 3840x1100          | 1         | 0.19%   |
| 3456x2160          | 1         | 0.19%   |
| 3200x2000          | 1         | 0.19%   |
| 3072x1920          | 1         | 0.19%   |
| 2520x1680          | 1         | 0.19%   |
| 2304x1440          | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 2240x1400          | 1         | 0.19%   |
| 1920x1280          | 1         | 0.19%   |
| 1600x1200          | 1         | 0.19%   |
| 1400x1050          | 1         | 0.19%   |
| 1280x768           | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 202       | 37.13%  |
| 13      | 87        | 15.99%  |
| 14      | 56        | 10.29%  |
| 17      | 34        | 6.25%   |
| 27      | 30        | 5.51%   |
| 12      | 25        | 4.6%    |
| 24      | 23        | 4.23%   |
| 23      | 16        | 2.94%   |
| 11      | 10        | 1.84%   |
| 16      | 8         | 1.47%   |
| 21      | 7         | 1.29%   |
| Unknown | 7         | 1.29%   |
| 34      | 6         | 1.1%    |
| 19      | 5         | 0.92%   |
| 22      | 4         | 0.74%   |
| 31      | 3         | 0.55%   |
| 25      | 3         | 0.55%   |
| 18      | 3         | 0.55%   |
| 40      | 2         | 0.37%   |
| 10      | 2         | 0.37%   |
| 8       | 2         | 0.37%   |
| 142     | 1         | 0.18%   |
| 75      | 1         | 0.18%   |
| 72      | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 43      | 1         | 0.18%   |
| 37      | 1         | 0.18%   |
| 29      | 1         | 0.18%   |
| 26      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 304       | 56.51%  |
| 201-300        | 82        | 15.24%  |
| 501-600        | 66        | 12.27%  |
| 351-400        | 37        | 6.88%   |
| 401-500        | 19        | 3.53%   |
| 601-700        | 7         | 1.3%    |
| Unknown        | 7         | 1.3%    |
| 701-800        | 6         | 1.12%   |
| 801-900        | 3         | 0.56%   |
| 1501-2000      | 2         | 0.37%   |
| 101-200        | 2         | 0.37%   |
| 1001-1500      | 2         | 0.37%   |
| More than 2000 | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 380       | 79.5%   |
| 16/10   | 64        | 13.39%  |
| 3/2     | 12        | 2.51%   |
| 21/9    | 6         | 1.26%   |
| Unknown | 6         | 1.26%   |
| 5/4     | 3         | 0.63%   |
| 4/3     | 3         | 0.63%   |
| 32/9    | 1         | 0.21%   |
| 3.40    | 1         | 0.21%   |
| 3.20    | 1         | 0.21%   |
| 1.00    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 201       | 36.81%  |
| 81-90          | 101       | 18.5%   |
| 71-80          | 42        | 7.69%   |
| 201-250        | 37        | 6.78%   |
| 301-350        | 31        | 5.68%   |
| 121-130        | 29        | 5.31%   |
| 61-70          | 23        | 4.21%   |
| 251-300        | 14        | 2.56%   |
| 51-60          | 11        | 2.01%   |
| 351-500        | 10        | 1.83%   |
| 111-120        | 9         | 1.65%   |
| 151-200        | 7         | 1.28%   |
| Unknown        | 7         | 1.28%   |
| 501-1000       | 5         | 0.92%   |
| 141-150        | 4         | 0.73%   |
| 131-140        | 4         | 0.73%   |
| 91-100         | 4         | 0.73%   |
| More than 1000 | 3         | 0.55%   |
| 41-50          | 2         | 0.37%   |
| 1-40           | 2         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 262       | 49.06%  |
| 101-120       | 84        | 15.73%  |
| 51-100        | 80        | 14.98%  |
| 161-240       | 64        | 11.99%  |
| More than 240 | 35        | 6.55%   |
| Unknown       | 7         | 1.31%   |
| 1-50          | 2         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 353       | 74.79%  |
| 2     | 91        | 19.28%  |
| 0     | 15        | 3.18%   |
| 3     | 13        | 2.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 304       | 42.94%  |
| Realtek Semiconductor             | 214       | 30.23%  |
| Qualcomm Atheros                  | 77        | 10.88%  |
| Broadcom                          | 25        | 3.53%   |
| Lenovo                            | 9         | 1.27%   |
| Marvell Technology Group          | 7         | 0.99%   |
| Dell                              | 7         | 0.99%   |
| ASIX Electronics                  | 7         | 0.99%   |
| MediaTek                          | 6         | 0.85%   |
| Ericsson Business Mobile Networks | 5         | 0.71%   |
| Apple                             | 5         | 0.71%   |
| Sierra Wireless                   | 4         | 0.56%   |
| Fibocom                           | 4         | 0.56%   |
| Samsung Electronics               | 3         | 0.42%   |
| Qualcomm Atheros Communications   | 3         | 0.42%   |
| Qualcomm                          | 3         | 0.42%   |
| Broadcom Limited                  | 3         | 0.42%   |
| Xiaomi                            | 2         | 0.28%   |
| TP-Link                           | 2         | 0.28%   |
| Ralink Technology                 | 2         | 0.28%   |
| Ralink                            | 2         | 0.28%   |
| D-Link System                     | 2         | 0.28%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.14%   |
| Shenzhen Goodix Technology        | 1         | 0.14%   |
| Prusa                             | 1         | 0.14%   |
| Nvidia                            | 1         | 0.14%   |
| NetGear                           | 1         | 0.14%   |
| Microsoft                         | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| ICS Advent                        | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| Google                            | 1         | 0.14%   |
| BUFFALO                           | 1         | 0.14%   |
| AMD                               | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 155       | 17.92%  |
| Intel Wi-Fi 6 AX200                                                     | 54        | 6.24%   |
| Intel Wireless 8265 / 8275                                              | 40        | 4.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 3.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 22        | 2.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 2.08%   |
| Intel Wireless 7265                                                     | 18        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.85%   |
| Intel Wireless 7260                                                     | 15        | 1.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 14        | 1.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.39%   |
| Intel Wireless 8260                                                     | 11        | 1.27%   |
| Intel Ethernet Connection (4) I219-V                                    | 11        | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 1.16%   |
| Intel Wireless 3165                                                     | 10        | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                                    | 8         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 7         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 7         | 0.81%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                   | 7         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.58%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 4         | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.35%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.35%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 3         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 3         | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 3         | 0.35%   |
| Lenovo USB-C Dock Ethernet                                              | 3         | 0.35%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 3         | 0.35%   |
| Intel Wireless 3160                                                     | 3         | 0.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.35%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 0.35%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.35%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.35%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 0.35%   |
| Intel Ethernet Connection (14) I219-LM                                  | 3         | 0.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 296       | 63.11%  |
| Qualcomm Atheros                | 63        | 13.43%  |
| Realtek Semiconductor           | 54        | 11.51%  |
| Broadcom                        | 23        | 4.9%    |
| MEDIATEK                        | 5         | 1.07%   |
| Dell                            | 5         | 1.07%   |
| Sierra Wireless                 | 4         | 0.85%   |
| Qualcomm Atheros Communications | 3         | 0.64%   |
| Qualcomm                        | 3         | 0.64%   |
| Fibocom                         | 3         | 0.64%   |
| Ralink Technology               | 2         | 0.43%   |
| Ralink                          | 2         | 0.43%   |
| D-Link System                   | 2         | 0.43%   |
| TP-Link                         | 1         | 0.21%   |
| NetGear                         | 1         | 0.21%   |
| Microsoft                       | 1         | 0.21%   |
| BUFFALO                         | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 54        | 11.46%  |
| Intel Wireless 8265 / 8275                                              | 40        | 8.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 6.16%   |
| Intel Wireless 7265                                                     | 18        | 3.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 3.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 3.4%    |
| Intel Wi-Fi 6 AX201                                                     | 16        | 3.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 3.4%    |
| Intel Wireless 7260                                                     | 15        | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 2.55%   |
| Intel Wireless 8260                                                     | 11        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 2.12%   |
| Intel Wireless 3165                                                     | 10        | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 1.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 7         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.06%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.06%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.64%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 3         | 0.64%   |
| Intel Wireless 3160                                                     | 3         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.64%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.64%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.64%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.64%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 0.42%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.42%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.42%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.42%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.42%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.42%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.42%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.42%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 2         | 0.42%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.42%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.42%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 2         | 0.42%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.21%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.21%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.21%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 196       | 52.55%  |
| Intel                      | 106       | 28.42%  |
| Qualcomm Atheros           | 20        | 5.36%   |
| Lenovo                     | 9         | 2.41%   |
| Broadcom                   | 9         | 2.41%   |
| Marvell Technology Group   | 7         | 1.88%   |
| ASIX Electronics           | 7         | 1.88%   |
| Apple                      | 5         | 1.34%   |
| Broadcom Limited           | 3         | 0.8%    |
| Xiaomi                     | 2         | 0.54%   |
| Samsung Electronics        | 2         | 0.54%   |
| ZTE WCDMA Technologies MSM | 1         | 0.27%   |
| TP-Link                    | 1         | 0.27%   |
| Nvidia                     | 1         | 0.27%   |
| JMicron Technology         | 1         | 0.27%   |
| ICS Advent                 | 1         | 0.27%   |
| Huawei Technologies        | 1         | 0.27%   |
| FIBOCOM                    | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 155       | 41.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 22        | 5.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 4.77%   |
| Intel Ethernet Connection (4) I219-LM                                          | 14        | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 3.71%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 2.92%   |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 2.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 1.86%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.86%   |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 1.86%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.8%    |
| Lenovo USB-C Dock Ethernet                                                     | 3         | 0.8%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 3         | 0.8%    |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.8%    |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.8%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.8%    |
| Intel Ethernet Connection (14) I219-LM                                         | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.53%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.53%   |
| Intel Ethernet Connection (5) I219-V                                           | 2         | 0.53%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.53%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.53%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.53%   |
| ASIX AX88772B Fast Ethernet Controller                                         | 2         | 0.53%   |
| ASIX AX88772B                                                                  | 2         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.53%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                                | 2         | 0.53%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.27%   |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.27%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.27%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Lenovo USB-C to LAN                                                            | 1         | 0.27%   |
| Lenovo Thinkpad USB LAN                                                        | 1         | 0.27%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.27%   |
| Intel Ethernet controller                                                      | 1         | 0.27%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.27%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 447       | 54.51%  |
| Ethernet | 356       | 43.41%  |
| Modem    | 16        | 1.95%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 377       | 67.93%  |
| Ethernet | 178       | 32.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 309       | 68.36%  |
| 1     | 131       | 28.98%  |
| 3     | 10        | 2.21%   |
| 0     | 2         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 419       | 90.3%   |
| Yes  | 45        | 9.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 64.05%  |
| Realtek Semiconductor           | 31        | 7.85%   |
| Qualcomm Atheros Communications | 20        | 5.06%   |
| Lite-On Technology              | 16        | 4.05%   |
| Apple                           | 13        | 3.29%   |
| Foxconn / Hon Hai               | 11        | 2.78%   |
| Broadcom                        | 10        | 2.53%   |
| IMC Networks                    | 9         | 2.28%   |
| Dell                            | 7         | 1.77%   |
| Realtek                         | 6         | 1.52%   |
| Cambridge Silicon Radio         | 6         | 1.52%   |
| Toshiba                         | 3         | 0.76%   |
| Hewlett-Packard                 | 3         | 0.76%   |
| ASUSTek Computer                | 2         | 0.51%   |
| Ralink Technology               | 1         | 0.25%   |
| Opticis                         | 1         | 0.25%   |
| Foxconn International           | 1         | 0.25%   |
| Chicony Electronics             | 1         | 0.25%   |
| Askey Computer                  | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 92        | 23.29%  |
| Intel AX200 Bluetooth                                                               | 54        | 13.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 48        | 12.15%  |
| Intel Bluetooth Device                                                              | 40        | 10.13%  |
| Realtek Bluetooth Radio                                                             | 15        | 3.8%    |
| Lite-On Bluetooth Device                                                            | 9         | 2.28%   |
| Apple Bluetooth Host Controller                                                     | 9         | 2.28%   |
| Intel AX210 Bluetooth                                                               | 8         | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 1.77%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 1.77%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.77%   |
| Realtek Bluetooth Radio                                                             | 6         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 6         | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.52%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 1.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.76%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.76%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.76%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.76%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.51%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.51%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.51%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.25%   |
| Ralink CSR BS8510                                                                   | 1         | 0.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.25%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.25%   |
| Opticis Bluetooth Radio                                                             | 1         | 0.25%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.25%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.25%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.25%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.25%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.25%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.25%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.25%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.25%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.25%   |
| Askey Bluetooth Device                                                              | 1         | 0.25%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 344       | 55.84%  |
| Nvidia                      | 107       | 17.37%  |
| AMD                         | 103       | 16.72%  |
| Lenovo                      | 10        | 1.62%   |
| Realtek Semiconductor       | 7         | 1.14%   |
| C-Media Electronics         | 6         | 0.97%   |
| Plantronics                 | 4         | 0.65%   |
| Logitech                    | 3         | 0.49%   |
| Dell                        | 3         | 0.49%   |
| Blue Microphones            | 3         | 0.49%   |
| Razer USA                   | 2         | 0.32%   |
| No brand                    | 2         | 0.32%   |
| GYROCOM C&C                 | 2         | 0.32%   |
| Creative Technology         | 2         | 0.32%   |
| Texas Instruments           | 1         | 0.16%   |
| Tdlasunnic                  | 1         | 0.16%   |
| SteelSeries ApS             | 1         | 0.16%   |
| Samson Technologies         | 1         | 0.16%   |
| RODE Microphones            | 1         | 0.16%   |
| LG Electronics              | 1         | 0.16%   |
| Kingston Technology         | 1         | 0.16%   |
| JMTek                       | 1         | 0.16%   |
| iCreate Technologies        | 1         | 0.16%   |
| GN Netcom                   | 1         | 0.16%   |
| FiiO Electronics Technology | 1         | 0.16%   |
| Behringer.......            | 1         | 0.16%   |
| AVer Information            | 1         | 0.16%   |
| AudioQuest                  | 1         | 0.16%   |
| ATOLL Electronique          | 1         | 0.16%   |
| Apple                       | 1         | 0.16%   |
| ACTIONS                     | 1         | 0.16%   |
| A4Tech                      | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 82        | 11.14%  |
| Intel Sunrise Point-LP HD Audio                                            | 63        | 8.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 51        | 6.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 46        | 6.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 23        | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21        | 2.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.17%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 2.17%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.9%    |
| Intel CM238 HD Audio Controller                                            | 13        | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 1.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 1.63%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.49%   |
| Nvidia Audio device                                                        | 9         | 1.22%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.09%   |
| Realtek Semiconductor USB Audio                                            | 7         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7         | 0.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.82%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.54%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.54%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.41%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 3         | 0.41%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 3         | 0.41%   |
| Lenovo ThinkPad Dock USB Audio                                             | 3         | 0.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.41%   |
| Dell AC511 USB SoundBar                                                    | 3         | 0.41%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 0.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.41%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3         | 0.41%   |
| Razer USA Razer Kraken X USB                                               | 2         | 0.27%   |
| Plantronics Blackwire 5220 Series                                          | 2         | 0.27%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.27%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.27%   |
| No brand Thunderbolt 3 Audio                                               | 2         | 0.27%   |
| Logitech G935 Gaming Headset                                               | 2         | 0.27%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 2         | 0.27%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.27%   |
| GYROCOM C&C Fiio E10                                                       | 2         | 0.27%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 161       | 31.38%  |
| SK Hynix                     | 120       | 23.39%  |
| Micron Technology            | 67        | 13.06%  |
| Kingston                     | 39        | 7.6%    |
| Unknown                      | 29        | 5.65%   |
| Crucial                      | 27        | 5.26%   |
| Ramaxel Technology           | 13        | 2.53%   |
| Corsair                      | 8         | 1.56%   |
| Elpida                       | 7         | 1.36%   |
| A-DATA Technology            | 7         | 1.36%   |
| Transcend                    | 5         | 0.97%   |
| G.Skill                      | 5         | 0.97%   |
| Team                         | 4         | 0.78%   |
| Nanya Technology             | 4         | 0.78%   |
| GOODRAM                      | 4         | 0.78%   |
| Patriot                      | 3         | 0.58%   |
| Unknown (ABCD)               | 2         | 0.39%   |
| Unknown (0x5D00000000000000) | 1         | 0.19%   |
| TIMETEC                      | 1         | 0.19%   |
| Teikon                       | 1         | 0.19%   |
| Saikano                      | 1         | 0.19%   |
| Magnum Tech                  | 1         | 0.19%   |
| Goldkey                      | 1         | 0.19%   |
| AMD                          | 1         | 0.19%   |
| 48spaces                     | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 9         | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 9         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 8         | 1.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 8         | 1.48%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s    | 7         | 1.3%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 7         | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s      | 7         | 1.3%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s      | 7         | 1.3%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s       | 7         | 1.3%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 6         | 1.11%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 6         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s      | 6         | 1.11%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 1.11%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 5         | 0.93%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 5         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 5         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 5         | 0.93%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 4         | 0.74%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 4         | 0.74%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 4         | 0.74%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s        | 4         | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 4         | 0.74%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 4         | 0.74%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 4         | 0.74%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.74%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s       | 4         | 0.74%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 3         | 0.56%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 0.56%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 0.56%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s       | 3         | 0.56%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 3         | 0.56%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 3         | 0.56%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s     | 3         | 0.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s         | 3         | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 3         | 0.56%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 3         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 3         | 0.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 0.56%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s      | 3         | 0.56%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s  | 3         | 0.56%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s         | 3         | 0.56%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 3         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s    | 3         | 0.56%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 3         | 0.56%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 3         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.37%   |
| Unknown RAM Module 1GB SODIMM DDR                             | 2         | 0.37%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s         | 2         | 0.37%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.37%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.37%   |
| SK Hynix RAM Module 4GB SODIMM DDR4 2400MT/s                  | 2         | 0.37%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s         | 2         | 0.37%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s      | 2         | 0.37%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 0.37%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s     | 2         | 0.37%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s     | 2         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 265       | 61.2%   |
| DDR3    | 108       | 24.94%  |
| LPDDR4  | 20        | 4.62%   |
| LPDDR3  | 16        | 3.7%    |
| DDR2    | 14        | 3.23%   |
| DDR     | 4         | 0.92%   |
| SDRAM   | 3         | 0.69%   |
| Unknown | 2         | 0.46%   |
| DRAM    | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 387       | 89.17%  |
| Row Of Chips | 41        | 9.45%   |
| Chip         | 4         | 0.92%   |
| DIMM         | 2         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 208       | 44.16%  |
| 4096  | 101       | 21.44%  |
| 16384 | 87        | 18.47%  |
| 2048  | 35        | 7.43%   |
| 32768 | 23        | 4.88%   |
| 1024  | 13        | 2.76%   |
| 512   | 2         | 0.42%   |
| 256   | 2         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 139       | 29.45%  |
| 3200    | 93        | 19.7%   |
| 1600    | 77        | 16.31%  |
| 2400    | 36        | 7.63%   |
| 2133    | 28        | 5.93%   |
| 1333    | 15        | 3.18%   |
| 4267    | 11        | 2.33%   |
| 1334    | 11        | 2.33%   |
| 667     | 10        | 2.12%   |
| 1867    | 8         | 1.69%   |
| Unknown | 8         | 1.69%   |
| 3266    | 7         | 1.48%   |
| 1067    | 5         | 1.06%   |
| 800     | 5         | 1.06%   |
| 4266    | 3         | 0.64%   |
| 2933    | 3         | 0.64%   |
| 8400    | 2         | 0.42%   |
| 3733    | 2         | 0.42%   |
| 3000    | 2         | 0.42%   |
| 533     | 2         | 0.42%   |
| 400     | 2         | 0.42%   |
| 4800    | 1         | 0.21%   |
| 4199    | 1         | 0.21%   |
| 1066    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 25%     |
| Hewlett-Packard     | 2         | 25%     |
| Xiaomi              | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Konica Minolta      | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 12.5%   |
| Seiko Epson WF-2510 Series           | 1         | 12.5%   |
| Seiko Epson AL-M310DN                | 1         | 12.5%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 12.5%   |
| Konica Minolta magicolor 1680MF scan | 1         | 12.5%   |
| HP Deskjet D1500 series              | 1         | 12.5%   |
| HP DeskJet 5440                      | 1         | 12.5%   |
| Canon CanoScan LiDE 300              | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 109       | 27.32%  |
| IMC Networks                           | 53        | 13.28%  |
| Microdia                               | 38        | 9.52%   |
| Realtek Semiconductor                  | 35        | 8.77%   |
| Acer                                   | 31        | 7.77%   |
| Sunplus Innovation Technology          | 23        | 5.76%   |
| Lite-On Technology                     | 15        | 3.76%   |
| Quanta                                 | 14        | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.51%   |
| Logitech                               | 10        | 2.51%   |
| Syntek                                 | 9         | 2.26%   |
| Luxvisions Innotech Limited            | 9         | 2.26%   |
| Apple                                  | 9         | 2.26%   |
| Z-Star Microelectronics                | 3         | 0.75%   |
| DigiTech                               | 3         | 0.75%   |
| Suyin                                  | 2         | 0.5%    |
| Silicon Motion                         | 2         | 0.5%    |
| Samsung Electronics                    | 2         | 0.5%    |
| Microsoft                              | 2         | 0.5%    |
| LG Electronics                         | 2         | 0.5%    |
| USB3.0 HD Audio Capture                | 1         | 0.25%   |
| ShineTech                              | 1         | 0.25%   |
| Ricoh                                  | 1         | 0.25%   |
| Razer USA                              | 1         | 0.25%   |
| Omnivision                             | 1         | 0.25%   |
| Lenovo                                 | 1         | 0.25%   |
| Intel                                  | 1         | 0.25%   |
| Holitech                               | 1         | 0.25%   |
| Hewlett-Packard                        | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| Genesys Logic                          | 1         | 0.25%   |
| AVer Information                       | 1         | 0.25%   |
| Aveo Technology                        | 1         | 0.25%   |
| Alcor Micro                            | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 33        | 8.17%   |
| Microdia Integrated_Webcam_HD                        | 25        | 6.19%   |
| IMC Networks Integrated Camera                       | 24        | 5.94%   |
| Realtek Integrated_Webcam_HD                         | 17        | 4.21%   |
| Chicony HD Webcam                                    | 13        | 3.22%   |
| Acer Integrated Camera                               | 13        | 3.22%   |
| Sunplus Integrated_Webcam_HD                         | 12        | 2.97%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 9         | 2.23%   |
| Lite-On Integrated Camera                            | 7         | 1.73%   |
| Chicony HP HD Camera                                 | 7         | 1.73%   |
| Chicony USB2.0 Camera                                | 6         | 1.49%   |
| Syntek Integrated Camera                             | 5         | 1.24%   |
| Sunplus HD WebCam                                    | 5         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 1.24%   |
| Microdia Integrated Webcam                           | 4         | 0.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 0.99%   |
| Logitech HD Pro Webcam C920                          | 4         | 0.99%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 4         | 0.99%   |
| Chicony Lenovo EasyCamera                            | 4         | 0.99%   |
| Chicony HD User Facing                               | 4         | 0.99%   |
| Chicony EasyCamera                                   | 4         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 4         | 0.99%   |
| Apple FaceTime HD Camera                             | 4         | 0.99%   |
| Acer SunplusIT Integrated Camera                     | 4         | 0.99%   |
| Acer BisonCam, NB Pro                                | 4         | 0.99%   |
| Realtek USB2.0 HD UVC WebCam                         | 3         | 0.74%   |
| Realtek Integrated Webcam HD                         | 3         | 0.74%   |
| Quanta HP Wide Vision HD Camera                      | 3         | 0.74%   |
| Quanta HD User Facing                                | 3         | 0.74%   |
| Lite-On TOSHIBA Web Camera - HD                      | 3         | 0.74%   |
| IMC Networks ov9734_azurewave_camera                 | 3         | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 0.74%   |
| Chicony USB 2.0 Camera                               | 3         | 0.74%   |
| Chicony ThinkPad T490 Webcam                         | 3         | 0.74%   |
| Apple Built-in iSight                                | 3         | 0.74%   |
| Syntek Lenovo EasyCamera                             | 2         | 0.5%    |
| Suyin HP TrueVision HD                               | 2         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.5%    |
| Samsung Galaxy A5 (MTP)                              | 2         | 0.5%    |
| Realtek USB Camera                                   | 2         | 0.5%    |
| Realtek Integrated Webcam_HD                         | 2         | 0.5%    |
| Realtek Integrated Webcam                            | 2         | 0.5%    |
| Quanta VGA WebCam                                    | 2         | 0.5%    |
| Quanta HP HD Camera                                  | 2         | 0.5%    |
| Quanta HD WebCam                                     | 2         | 0.5%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.5%    |
| Microdia Integrated Webcam HD                        | 2         | 0.5%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.5%    |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 0.5%    |
| Logitech Webcam C310                                 | 2         | 0.5%    |
| Lite-On HP Wide Vision HD Camera                     | 2         | 0.5%    |
| Lite-On HP HD Camera                                 | 2         | 0.5%    |
| IMC Networks VGA UVC WebCam                          | 2         | 0.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.5%    |
| IMC Networks USB Camera                              | 2         | 0.5%    |
| IMC Networks Integrated RGB Camera                   | 2         | 0.5%    |
| IMC Networks HD Camera                               | 2         | 0.5%    |
| DigiTech USB 2.0 PC Camera                           | 2         | 0.5%    |
| Chicony Integrated IR Camera                         | 2         | 0.5%    |
| Chicony HP Wide Vision HD                            | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 43        | 46.74%  |
| Validity Sensors           | 19        | 20.65%  |
| Shenzhen Goodix Technology | 15        | 16.3%   |
| Elan Microelectronics      | 5         | 5.43%   |
| AuthenTec                  | 4         | 4.35%   |
| STMicroelectronics         | 3         | 3.26%   |
| LighTuning Technology      | 2         | 2.17%   |
| Upek                       | 1         | 1.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 19        | 20.65%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 12        | 13.04%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 6.52%   |
| Shenzhen Goodix  Fingerprint Device                        | 6         | 6.52%   |
| Unknown                                                    | 6         | 6.52%   |
| Validity Sensors Synaptics WBDI                            | 5         | 5.43%   |
| Shenzhen Goodix FingerPrint                                | 5         | 5.43%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 4.35%   |
| Elan ELAN:Fingerprint                                      | 4         | 4.35%   |
| STMicroelectronics Fingerprint Reader                      | 3         | 3.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 2.17%   |
| Validity Sensors Fingerprint scanner                       | 2         | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 2         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 2.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 1.09%   |
| Synaptics WBDI Device                                      | 1         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 1.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.09%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.09%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.09%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 1.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Alcor Micro          | 30        | 45.45%  |
| Broadcom             | 27        | 40.91%  |
| Upek                 | 4         | 6.06%   |
| O2 Micro             | 2         | 3.03%   |
| Yubico.com           | 1         | 1.52%   |
| Purism, SPC          | 1         | 1.52%   |
| Microchip Technology | 1         | 1.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 45.45%  |
| Broadcom 5880                                                                | 10        | 15.15%  |
| Broadcom 58200                                                               | 7         | 10.61%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.06%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.03%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.52%   |
| Purism, SPC Librem Key                                                       | 1         | 1.52%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 159       | 31.55%  |
| 1     | 131       | 25.99%  |
| 2     | 87        | 17.26%  |
| 3     | 65        | 12.9%   |
| 4     | 36        | 7.14%   |
| 5     | 16        | 3.17%   |
| 6     | 8         | 1.59%   |
| 8     | 1         | 0.2%    |
| 7     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 124       | 16.89%  |
| Camera                   | 103       | 14.03%  |
| Bluetooth                | 98        | 13.35%  |
| Fingerprint reader       | 92        | 12.53%  |
| Graphics card            | 75        | 10.22%  |
| Chipcard                 | 55        | 7.49%   |
| Card reader              | 52        | 7.08%   |
| Multimedia controller    | 41        | 5.59%   |
| Net/wireless             | 36        | 4.9%    |
| Modem                    | 11        | 1.5%    |
| Net/ethernet             | 9         | 1.23%   |
| Sound                    | 8         | 1.09%   |
| Storage/ata              | 6         | 0.82%   |
| Network                  | 6         | 0.82%   |
| Storage                  | 5         | 0.68%   |
| Storage/ide              | 4         | 0.54%   |
| Tv card                  | 2         | 0.27%   |
| Firewire controller      | 2         | 0.27%   |
| Dvb card                 | 2         | 0.27%   |
| Wireless                 | 1         | 0.14%   |
| Storage/raid             | 1         | 0.14%   |
| Storage/nvme             | 1         | 0.14%   |
