Linux in Puerto Rico - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Puerto Rico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Puerto_Rico/Desktop/README.md) and [notebooks](/Location/Puerto_Rico/Notebook/README.md).

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

Total: 193

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-AE031                    | All in one  | [d6f4214361](https://linux-hardware.org/?probe=d6f4214361) | Jun 30, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| MSI           | MS-B0A1                     | Desktop     | [3193cbe3fd](https://linux-hardware.org/?probe=3193cbe3fd) | Jun 20, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [9eaa432fcd](https://linux-hardware.org/?probe=9eaa432fcd) | Jun 02, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [83ed9adfc1](https://linux-hardware.org/?probe=83ed9adfc1) | May 04, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [074f1f75dc](https://linux-hardware.org/?probe=074f1f75dc) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [656e8c50dd](https://linux-hardware.org/?probe=656e8c50dd) | Apr 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1911200c56](https://linux-hardware.org/?probe=1911200c56) | Mar 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [fd3185704d](https://linux-hardware.org/?probe=fd3185704d) | Mar 21, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell          | Inspiron 17-7778            | Notebook    | [bcc52b2596](https://linux-hardware.org/?probe=bcc52b2596) | Mar 17, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [f96e26bb9a](https://linux-hardware.org/?probe=f96e26bb9a) | Mar 08, 2022 |
| Dell          | OptiPlex 7020               | Desktop     | [ba82f9d852](https://linux-hardware.org/?probe=ba82f9d852) | Mar 01, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a1ecd8a3cb](https://linux-hardware.org/?probe=a1ecd8a3cb) | Feb 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [e7ce3f2f38](https://linux-hardware.org/?probe=e7ce3f2f38) | Feb 09, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [86dbaf1d07](https://linux-hardware.org/?probe=86dbaf1d07) | Jan 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [51e8a3a34d](https://linux-hardware.org/?probe=51e8a3a34d) | Dec 31, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [464d10c41d](https://linux-hardware.org/?probe=464d10c41d) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | Notebook    | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [7bc4106877](https://linux-hardware.org/?probe=7bc4106877) | Dec 12, 2021 |
| Dell          | 0R6JMP A00                  | Desktop     | [2b3e03c89b](https://linux-hardware.org/?probe=2b3e03c89b) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| HP            | 1998                        | Desktop     | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9af646fd14](https://linux-hardware.org/?probe=9af646fd14) | Nov 10, 2021 |
| ASRock        | Q1900M                      | Desktop     | [8482ae3a2f](https://linux-hardware.org/?probe=8482ae3a2f) | Nov 09, 2021 |
| HP            | 339A                        | Desktop     | [e2ce00d1ec](https://linux-hardware.org/?probe=e2ce00d1ec) | Nov 08, 2021 |
| Alienware     | 07W25T A00                  | Desktop     | [c08c87521f](https://linux-hardware.org/?probe=c08c87521f) | Nov 08, 2021 |
| HP            | ENVY Laptop 17m-bw0xxx      | Notebook    | [9ec292c9d9](https://linux-hardware.org/?probe=9ec292c9d9) | Oct 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8649bba9b6](https://linux-hardware.org/?probe=8649bba9b6) | Oct 22, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fede248f75](https://linux-hardware.org/?probe=fede248f75) | Oct 19, 2021 |
| HP            | ProBook 6450b               | Notebook    | [518e694864](https://linux-hardware.org/?probe=518e694864) | Oct 19, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [29c7fa76a8](https://linux-hardware.org/?probe=29c7fa76a8) | Oct 10, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [6818ec3abc](https://linux-hardware.org/?probe=6818ec3abc) | Oct 10, 2021 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [732c00f018](https://linux-hardware.org/?probe=732c00f018) | Oct 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [7ecda0a147](https://linux-hardware.org/?probe=7ecda0a147) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [9ed2b3cf12](https://linux-hardware.org/?probe=9ed2b3cf12) | Sep 21, 2021 |
| GPU Compan... | GWTN156-9                   | Notebook    | [a9ac79c22a](https://linux-hardware.org/?probe=a9ac79c22a) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a96d28c504](https://linux-hardware.org/?probe=a96d28c504) | Sep 16, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [686eb55129](https://linux-hardware.org/?probe=686eb55129) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d120a0016d](https://linux-hardware.org/?probe=d120a0016d) | Aug 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [9ad69ca6ad](https://linux-hardware.org/?probe=9ad69ca6ad) | Jul 27, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [75fd544183](https://linux-hardware.org/?probe=75fd544183) | Jul 26, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a3b055840b](https://linux-hardware.org/?probe=a3b055840b) | Jul 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [cbcf0ae65d](https://linux-hardware.org/?probe=cbcf0ae65d) | Jul 07, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [c3b8ac12be](https://linux-hardware.org/?probe=c3b8ac12be) | Jul 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3a88077121](https://linux-hardware.org/?probe=3a88077121) | Jul 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [17a65dfb0e](https://linux-hardware.org/?probe=17a65dfb0e) | Jul 06, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [5af810dc36](https://linux-hardware.org/?probe=5af810dc36) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675992d5f9](https://linux-hardware.org/?probe=675992d5f9) | Jul 04, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [4782df79ce](https://linux-hardware.org/?probe=4782df79ce) | Jul 02, 2021 |
| HP            | ProBook 6560b               | Notebook    | [806dfcb6f0](https://linux-hardware.org/?probe=806dfcb6f0) | Jul 01, 2021 |
| HP            | ProBook 6450b               | Notebook    | [a8689c5d60](https://linux-hardware.org/?probe=a8689c5d60) | Jun 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [fed4ef6298](https://linux-hardware.org/?probe=fed4ef6298) | Jun 23, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [14e1d81078](https://linux-hardware.org/?probe=14e1d81078) | Jun 23, 2021 |
| HP            | ProBook 6450b               | Notebook    | [b4c7a0fd32](https://linux-hardware.org/?probe=b4c7a0fd32) | Jun 21, 2021 |
| Pegatron      | 2ACD                        | Desktop     | [fd757c14ce](https://linux-hardware.org/?probe=fd757c14ce) | Jun 13, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| HP            | 1998                        | Desktop     | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [6b2ff5fb12](https://linux-hardware.org/?probe=6b2ff5fb12) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| HP            | ENVY dv7                    | Notebook    | [651a68adc6](https://linux-hardware.org/?probe=651a68adc6) | May 24, 2021 |
| HP            | 339A                        | Desktop     | [ac11f05a1a](https://linux-hardware.org/?probe=ac11f05a1a) | May 21, 2021 |
| Intel         | SKYBAY                      | Desktop     | [9bc7ab87d1](https://linux-hardware.org/?probe=9bc7ab87d1) | May 19, 2021 |
| ASRock        | Q1900M                      | Desktop     | [7c778b5654](https://linux-hardware.org/?probe=7c778b5654) | May 02, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [7442c54767](https://linux-hardware.org/?probe=7442c54767) | Apr 29, 2021 |
| HP            | 1998                        | Desktop     | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | Desktop     | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Lenovo        | ThinkPad T410 2516ADU       | Notebook    | [5feb962d24](https://linux-hardware.org/?probe=5feb962d24) | Apr 07, 2021 |
| Intel         | SKYBAY                      | Desktop     | [472818e347](https://linux-hardware.org/?probe=472818e347) | Apr 04, 2021 |
| HP            | 1998                        | Desktop     | [f515fbf660](https://linux-hardware.org/?probe=f515fbf660) | Apr 01, 2021 |
| HP            | 1998                        | Desktop     | [3bc0a0dcb6](https://linux-hardware.org/?probe=3bc0a0dcb6) | Mar 20, 2021 |
| HP            | 1998                        | Desktop     | [a10d91fc1b](https://linux-hardware.org/?probe=a10d91fc1b) | Mar 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [5ab0183bc4](https://linux-hardware.org/?probe=5ab0183bc4) | Mar 18, 2021 |
| Intel         | SKYBAY                      | Desktop     | [ecefc99ed5](https://linux-hardware.org/?probe=ecefc99ed5) | Mar 14, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [332f4238da](https://linux-hardware.org/?probe=332f4238da) | Mar 09, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [775057eb07](https://linux-hardware.org/?probe=775057eb07) | Feb 20, 2021 |
| Acer          | AAHD3.VC                    | Desktop     | [b11309575f](https://linux-hardware.org/?probe=b11309575f) | Feb 19, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [48d2054858](https://linux-hardware.org/?probe=48d2054858) | Feb 16, 2021 |
| Dell          | 0DFRFW A00                  | Desktop     | [093c47fb9c](https://linux-hardware.org/?probe=093c47fb9c) | Feb 13, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d4372897b8](https://linux-hardware.org/?probe=d4372897b8) | Feb 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [190f14bae7](https://linux-hardware.org/?probe=190f14bae7) | Feb 13, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [2140e64244](https://linux-hardware.org/?probe=2140e64244) | Feb 13, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81a3e9faea](https://linux-hardware.org/?probe=81a3e9faea) | Feb 11, 2021 |
| HP            | 18E4                        | Desktop     | [db6eb1d366](https://linux-hardware.org/?probe=db6eb1d366) | Feb 05, 2021 |
| HP            | 18E4                        | Desktop     | [bad5f5110c](https://linux-hardware.org/?probe=bad5f5110c) | Feb 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63a2a56eda](https://linux-hardware.org/?probe=63a2a56eda) | Jan 25, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [b2513f813d](https://linux-hardware.org/?probe=b2513f813d) | Jan 16, 2021 |
| ASUSTek       | K53E                        | Notebook    | [0523ff890c](https://linux-hardware.org/?probe=0523ff890c) | Jan 15, 2021 |
| HP            | 18E4                        | Desktop     | [729391b32e](https://linux-hardware.org/?probe=729391b32e) | Jan 08, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [5780c56d1e](https://linux-hardware.org/?probe=5780c56d1e) | Jan 06, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [ecaae6f562](https://linux-hardware.org/?probe=ecaae6f562) | Jan 05, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [5e4b418568](https://linux-hardware.org/?probe=5e4b418568) | Dec 19, 2020 |
| AZW           | GT-R                        | Notebook    | [19b47cf9f6](https://linux-hardware.org/?probe=19b47cf9f6) | Dec 16, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [ba371f8d43](https://linux-hardware.org/?probe=ba371f8d43) | Dec 07, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [646f020b0d](https://linux-hardware.org/?probe=646f020b0d) | Nov 27, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [844bb428a9](https://linux-hardware.org/?probe=844bb428a9) | Nov 22, 2020 |
| MSI           | MS-B1711                    | Desktop     | [8d69ecec16](https://linux-hardware.org/?probe=8d69ecec16) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [958741b7b6](https://linux-hardware.org/?probe=958741b7b6) | Nov 17, 2020 |
| MSI           | MS-B1711                    | Desktop     | [3c327ae485](https://linux-hardware.org/?probe=3c327ae485) | Nov 17, 2020 |
| CompuLab      | fit-PC3                     | Mini pc     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Dell          | Latitude E6410              | Notebook    | [d188c9653d](https://linux-hardware.org/?probe=d188c9653d) | Nov 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [caf34f9e21](https://linux-hardware.org/?probe=caf34f9e21) | Nov 02, 2020 |
| MSI           | MS-B1711                    | Desktop     | [26c2dcf112](https://linux-hardware.org/?probe=26c2dcf112) | Nov 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [62ebca752a](https://linux-hardware.org/?probe=62ebca752a) | Oct 31, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [362d74125d](https://linux-hardware.org/?probe=362d74125d) | Oct 31, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7ec0211fb](https://linux-hardware.org/?probe=f7ec0211fb) | Oct 27, 2020 |
| ASRock        | Q1900M                      | Desktop     | [72cddfd9ae](https://linux-hardware.org/?probe=72cddfd9ae) | Oct 24, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [9d734dee6e](https://linux-hardware.org/?probe=9d734dee6e) | Sep 30, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e5448099f1](https://linux-hardware.org/?probe=e5448099f1) | Sep 27, 2020 |
| HP            | 339A                        | Desktop     | [47db0521b7](https://linux-hardware.org/?probe=47db0521b7) | Sep 23, 2020 |
| HP            | 339A                        | Desktop     | [51cec5b6f8](https://linux-hardware.org/?probe=51cec5b6f8) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [a027a185e5](https://linux-hardware.org/?probe=a027a185e5) | Sep 23, 2020 |
| HP            | ENVY dv7                    | Notebook    | [ff87d18b2b](https://linux-hardware.org/?probe=ff87d18b2b) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [37cfc48ef8](https://linux-hardware.org/?probe=37cfc48ef8) | Sep 21, 2020 |
| HP            | 339A                        | Desktop     | [254f23a364](https://linux-hardware.org/?probe=254f23a364) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| HP            | 18E4                        | Desktop     | [277593bde6](https://linux-hardware.org/?probe=277593bde6) | Aug 07, 2020 |
| Acer          | Swift SF314-51              | Notebook    | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [f9271f6dae](https://linux-hardware.org/?probe=f9271f6dae) | Jul 09, 2020 |
| MSI           | Z370-A PRO                  | Desktop     | [f8629928a6](https://linux-hardware.org/?probe=f8629928a6) | Jun 18, 2020 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9aaeabab3d](https://linux-hardware.org/?probe=9aaeabab3d) | Jun 18, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d161c397ca](https://linux-hardware.org/?probe=d161c397ca) | Jun 14, 2020 |
| HP            | ENVY dv7                    | Notebook    | [2ae56a2828](https://linux-hardware.org/?probe=2ae56a2828) | May 24, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [98ba3a8ad5](https://linux-hardware.org/?probe=98ba3a8ad5) | May 17, 2020 |
| Sony          | VPCEA36FX                   | Notebook    | [572157356f](https://linux-hardware.org/?probe=572157356f) | May 13, 2020 |
| HP            | 18E4                        | Desktop     | [1fe1707854](https://linux-hardware.org/?probe=1fe1707854) | May 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [8805cd4168](https://linux-hardware.org/?probe=8805cd4168) | Apr 16, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e8b9eefb82](https://linux-hardware.org/?probe=e8b9eefb82) | Apr 13, 2020 |
| HP            | ENVY dv7                    | Notebook    | [e2de1ae596](https://linux-hardware.org/?probe=e2de1ae596) | Apr 04, 2020 |
| HP            | ENVY dv7                    | Notebook    | [97ae3dc919](https://linux-hardware.org/?probe=97ae3dc919) | Mar 14, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [44caca0bb1](https://linux-hardware.org/?probe=44caca0bb1) | Mar 12, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [3d3261ccc3](https://linux-hardware.org/?probe=3d3261ccc3) | Mar 09, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [c0f180f342](https://linux-hardware.org/?probe=c0f180f342) | Mar 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [4ac0a3b1fe](https://linux-hardware.org/?probe=4ac0a3b1fe) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a2582aaec1](https://linux-hardware.org/?probe=a2582aaec1) | Mar 06, 2020 |
| ASRock        | G31M-S                      | Desktop     | [a63cd159a1](https://linux-hardware.org/?probe=a63cd159a1) | Mar 06, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [aa32ea3cb7](https://linux-hardware.org/?probe=aa32ea3cb7) | Mar 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [efa77a90cb](https://linux-hardware.org/?probe=efa77a90cb) | Mar 01, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [aca2204df4](https://linux-hardware.org/?probe=aca2204df4) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [40a8750e54](https://linux-hardware.org/?probe=40a8750e54) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [399d92cf32](https://linux-hardware.org/?probe=399d92cf32) | Feb 28, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7c094d733b](https://linux-hardware.org/?probe=7c094d733b) | Feb 28, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [ddebe02bcd](https://linux-hardware.org/?probe=ddebe02bcd) | Feb 28, 2020 |
| HP            | Notebook                    | Notebook    | [80f2a12798](https://linux-hardware.org/?probe=80f2a12798) | Feb 28, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [132413f9bd](https://linux-hardware.org/?probe=132413f9bd) | Feb 21, 2020 |
| HP            | 18E4                        | Desktop     | [ee3dae8f72](https://linux-hardware.org/?probe=ee3dae8f72) | Feb 17, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fa684e430c](https://linux-hardware.org/?probe=fa684e430c) | Feb 13, 2020 |
| MSI           | B150 PC MATE                | Desktop     | [ed98074061](https://linux-hardware.org/?probe=ed98074061) | Oct 08, 2019 |
| ASRock        | G31M-S                      | Desktop     | [d1f69377d4](https://linux-hardware.org/?probe=d1f69377d4) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [595867810d](https://linux-hardware.org/?probe=595867810d) | Aug 18, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| ASRock        | 945GCM-S                    | Desktop     | [d4ea4c5cb6](https://linux-hardware.org/?probe=d4ea4c5cb6) | May 04, 2019 |
| HP            | 18E4                        | Desktop     | [36f9656af0](https://linux-hardware.org/?probe=36f9656af0) | Feb 15, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [d24fc7f682](https://linux-hardware.org/?probe=d24fc7f682) | Jan 30, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [525707b787](https://linux-hardware.org/?probe=525707b787) | Jan 21, 2019 |
| Toshiba       | Satellite L655              | Notebook    | [a7616fb055](https://linux-hardware.org/?probe=a7616fb055) | Jan 21, 2019 |
| HP            | 18E4                        | Desktop     | [c6cf9c7817](https://linux-hardware.org/?probe=c6cf9c7817) | Jan 04, 2019 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [85398272dc](https://linux-hardware.org/?probe=85398272dc) | Dec 03, 2018 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [10a5b1559d](https://linux-hardware.org/?probe=10a5b1559d) | Dec 03, 2018 |
| Dell          | Inspiron MP061              | Notebook    | [113fc7a00d](https://linux-hardware.org/?probe=113fc7a00d) | Jul 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [82229858ec](https://linux-hardware.org/?probe=82229858ec) | Jun 15, 2018 |
| ASRock        | G31M-S                      | Desktop     | [90f397422e](https://linux-hardware.org/?probe=90f397422e) | Jun 15, 2018 |
| ASRock        | 945GCM-S                    | Desktop     | [c7cbed362d](https://linux-hardware.org/?probe=c7cbed362d) | May 27, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 23        | 19.17%  |
| Ubuntu 18.04        | 11        | 9.17%   |
| OpenMandriva 4.2    | 6         | 5%      |
| Ubuntu 21.10        | 4         | 3.33%   |
| Ubuntu 20.10        | 4         | 3.33%   |
| Zorin 16            | 3         | 2.5%    |
| OpenMandriva 4.3    | 3         | 2.5%    |
| Manjaro             | 3         | 2.5%    |
| Linux Mint 20.1     | 3         | 2.5%    |
| Linux Mint 19.3     | 3         | 2.5%    |
| KDE neon 20.04      | 3         | 2.5%    |
| BlackPanther 18.1   | 3         | 2.5%    |
| Xubuntu 20.04       | 2         | 1.67%   |
| Ubuntu 19.10        | 2         | 1.67%   |
| ROSA R11            | 2         | 1.67%   |
| ROSA R10            | 2         | 1.67%   |
| Lubuntu 20.04       | 2         | 1.67%   |
| LMDE 4              | 2         | 1.67%   |
| Linux Mint 20.3     | 2         | 1.67%   |
| Linux Mint 20.2     | 2         | 1.67%   |
| Linux Mint 20       | 2         | 1.67%   |
| Garuda Linux        | 2         | 1.67%   |
| Fedora 36           | 2         | 1.67%   |
| ArcoLinux Rolling   | 2         | 1.67%   |
| Zorin 15            | 1         | 0.83%   |
| Xubuntu 20.10       | 1         | 0.83%   |
| Ubuntu MATE 20.04   | 1         | 0.83%   |
| Ubuntu Budgie 21.04 | 1         | 0.83%   |
| ROSA R9             | 1         | 0.83%   |
| Pop!_OS 21.10       | 1         | 0.83%   |
| Pop!_OS 21.04       | 1         | 0.83%   |
| Pop!_OS 20.10       | 1         | 0.83%   |
| Pop!_OS 20.04       | 1         | 0.83%   |
| Pop!_OS 19.10       | 1         | 0.83%   |
| Peppermint 9        | 1         | 0.83%   |
| Parrot 4.11         | 1         | 0.83%   |
| openSUSE Leap-15.2  | 1         | 0.83%   |
| OpenMandriva 4.50   | 1         | 0.83%   |
| Manjaro 21.1.5      | 1         | 0.83%   |
| Manjaro 20.1.2      | 1         | 0.83%   |
| LinuxFX 11          | 1         | 0.83%   |
| Linux Mint 19.1     | 1         | 0.83%   |
| Fedora 33           | 1         | 0.83%   |
| Endless 3.9.1       | 1         | 0.83%   |
| Endless 3.7.8       | 1         | 0.83%   |
| EndeavourOS Rolling | 1         | 0.83%   |
| Devuan 4            | 1         | 0.83%   |
| Debian 9            | 1         | 0.83%   |
| Debian 10           | 1         | 0.83%   |
| CentOS 8            | 1         | 0.83%   |
| Arch                | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 42        | 37.17%  |
| OpenMandriva  | 10        | 8.85%   |
| Linux Mint    | 10        | 8.85%   |
| Pop!_OS       | 5         | 4.42%   |
| Zorin         | 4         | 3.54%   |
| ROSA          | 4         | 3.54%   |
| Manjaro       | 4         | 3.54%   |
| Xubuntu       | 3         | 2.65%   |
| KDE neon      | 3         | 2.65%   |
| Fedora        | 3         | 2.65%   |
| BlackPanther  | 3         | 2.65%   |
| Lubuntu       | 2         | 1.77%   |
| LMDE          | 2         | 1.77%   |
| Garuda Linux  | 2         | 1.77%   |
| Endless       | 2         | 1.77%   |
| Debian        | 2         | 1.77%   |
| ArcoLinux     | 2         | 1.77%   |
| Ubuntu MATE   | 1         | 0.88%   |
| Ubuntu Budgie | 1         | 0.88%   |
| Peppermint    | 1         | 0.88%   |
| Parrot        | 1         | 0.88%   |
| openSUSE      | 1         | 0.88%   |
| LinuxFX       | 1         | 0.88%   |
| EndeavourOS   | 1         | 0.88%   |
| Devuan        | 1         | 0.88%   |
| CentOS        | 1         | 0.88%   |
| Arch          | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 6         | 4.29%   |
| 5.4.0-58-generic               | 4         | 2.86%   |
| 5.8.0-59-generic               | 3         | 2.14%   |
| 5.16.7-desktop-1omv4003        | 3         | 2.14%   |
| 5.11.0-38-generic              | 3         | 2.14%   |
| 4.15.0-43-generic              | 3         | 2.14%   |
| 5.8.18-1-MANJARO               | 2         | 1.43%   |
| 5.8.0-55-generic               | 2         | 1.43%   |
| 5.8.0-45-generic               | 2         | 1.43%   |
| 5.4.0-73-generic               | 2         | 1.43%   |
| 5.4.0-72-generic               | 2         | 1.43%   |
| 5.4.0-52-generic               | 2         | 1.43%   |
| 5.4.0-48-generic               | 2         | 1.43%   |
| 5.4.0-47-generic               | 2         | 1.43%   |
| 5.4.0-40-generic               | 2         | 1.43%   |
| 5.4.0-109-generic              | 2         | 1.43%   |
| 5.3.0-41-generic               | 2         | 1.43%   |
| 5.3.0-28-generic               | 2         | 1.43%   |
| 5.13.0-40-generic              | 2         | 1.43%   |
| 5.13.0-39-generic              | 2         | 1.43%   |
| 5.13.0-35-generic              | 2         | 1.43%   |
| 5.13.0-30-generic              | 2         | 1.43%   |
| 5.11.0-41-generic              | 2         | 1.43%   |
| 5.11.0-27-generic              | 2         | 1.43%   |
| 4.18.16-desktop-1bP            | 2         | 1.43%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 2         | 1.43%   |
| 5.9.16-200.fc33.x86_64         | 1         | 0.71%   |
| 5.9.16-1-MANJARO               | 1         | 0.71%   |
| 5.9.1-1-MANJARO                | 1         | 0.71%   |
| 5.8.5-zen1-1-zen               | 1         | 0.71%   |
| 5.8.14-zen1-1-zen              | 1         | 0.71%   |
| 5.8.0-7630-generic             | 1         | 0.71%   |
| 5.8.0-63-generic               | 1         | 0.71%   |
| 5.8.0-54-generic               | 1         | 0.71%   |
| 5.8.0-53-generic               | 1         | 0.71%   |
| 5.8.0-49-generic               | 1         | 0.71%   |
| 5.8.0-44-generic               | 1         | 0.71%   |
| 5.8.0-29-generic               | 1         | 0.71%   |
| 5.8.0-25-generic               | 1         | 0.71%   |
| 5.8.0-14-generic               | 1         | 0.71%   |
| 5.8.0-1011-raspi               | 1         | 0.71%   |
| 5.8.0-1008-raspi               | 1         | 0.71%   |
| 5.8.0-1006-raspi               | 1         | 0.71%   |
| 5.6.14-desktop-2bP             | 1         | 0.71%   |
| 5.4.0-89-generic               | 1         | 0.71%   |
| 5.4.0-88-generic               | 1         | 0.71%   |
| 5.4.0-84-generic               | 1         | 0.71%   |
| 5.4.0-77-generic               | 1         | 0.71%   |
| 5.4.0-7634-generic             | 1         | 0.71%   |
| 5.4.0-70-generic               | 1         | 0.71%   |
| 5.4.0-65-generic               | 1         | 0.71%   |
| 5.4.0-62-generic               | 1         | 0.71%   |
| 5.4.0-60-generic               | 1         | 0.71%   |
| 5.4.0-59-generic               | 1         | 0.71%   |
| 5.4.0-55-generic               | 1         | 0.71%   |
| 5.4.0-42-generic               | 1         | 0.71%   |
| 5.4.0-37-generic               | 1         | 0.71%   |
| 5.4.0-29-generic               | 1         | 0.71%   |
| 5.3.6-050306-generic           | 1         | 0.71%   |
| 5.3.18-lp152.57-default        | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 29        | 23.97%  |
| 5.8.0   | 14        | 11.57%  |
| 5.13.0  | 11        | 9.09%   |
| 4.15.0  | 10        | 8.26%   |
| 5.11.0  | 9         | 7.44%   |
| 5.3.0   | 6         | 4.96%   |
| 5.10.14 | 6         | 4.96%   |
| 5.16.7  | 3         | 2.48%   |
| 4.19.0  | 3         | 2.48%   |
| 4.18.0  | 3         | 2.48%   |
| 5.9.16  | 2         | 1.65%   |
| 5.8.18  | 2         | 1.65%   |
| 5.10.0  | 2         | 1.65%   |
| 4.9.60  | 2         | 1.65%   |
| 4.18.16 | 2         | 1.65%   |
| 5.9.1   | 1         | 0.83%   |
| 5.8.5   | 1         | 0.83%   |
| 5.8.14  | 1         | 0.83%   |
| 5.6.14  | 1         | 0.83%   |
| 5.3.6   | 1         | 0.83%   |
| 5.3.18  | 1         | 0.83%   |
| 5.18.6  | 1         | 0.83%   |
| 5.18.5  | 1         | 0.83%   |
| 5.17.1  | 1         | 0.83%   |
| 5.15.5  | 1         | 0.83%   |
| 5.14.8  | 1         | 0.83%   |
| 5.13.19 | 1         | 0.83%   |
| 5.12.4  | 1         | 0.83%   |
| 5.11.16 | 1         | 0.83%   |
| 5.11.13 | 1         | 0.83%   |
| 4.9.20  | 1         | 0.83%   |
| 4.9.0   | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 24.37%  |
| 5.8     | 18        | 15.13%  |
| 5.13    | 12        | 10.08%  |
| 5.11    | 10        | 8.4%    |
| 4.15    | 10        | 8.4%    |
| 5.3     | 8         | 6.72%   |
| 5.10    | 8         | 6.72%   |
| 4.9     | 4         | 3.36%   |
| 4.18    | 4         | 3.36%   |
| 5.9     | 3         | 2.52%   |
| 5.16    | 3         | 2.52%   |
| 4.19    | 3         | 2.52%   |
| 5.18    | 2         | 1.68%   |
| 5.6     | 1         | 0.84%   |
| 5.17    | 1         | 0.84%   |
| 5.15    | 1         | 0.84%   |
| 5.14    | 1         | 0.84%   |
| 5.12    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 95        | 95.96%  |
| i686    | 2         | 2.02%   |
| aarch64 | 2         | 2.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 53        | 46.9%   |
| KDE5       | 21        | 18.58%  |
| X-Cinnamon | 8         | 7.08%   |
| XFCE       | 7         | 6.19%   |
| Unknown    | 6         | 5.31%   |
| MATE       | 4         | 3.54%   |
| LXQt       | 2         | 1.77%   |
| LXDE       | 2         | 1.77%   |
| KDE4       | 2         | 1.77%   |
| KDE        | 2         | 1.77%   |
| Budgie     | 2         | 1.77%   |
| Unity      | 1         | 0.88%   |
| i3         | 1         | 0.88%   |
| Deepin     | 1         | 0.88%   |
| Cinnamon   | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 92        | 92%     |
| Wayland | 7         | 7%      |
| Unknown | 1         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 63.64%  |
| SDDM    | 14        | 12.73%  |
| GDM3    | 10        | 9.09%   |
| GDM     | 6         | 5.45%   |
| LightDM | 5         | 4.55%   |
| TDM     | 3         | 2.73%   |
| KDM     | 2         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 82        | 81.19%  |
| Unknown | 12        | 11.88%  |
| es_PR   | 5         | 4.95%   |
| es_ES   | 1         | 0.99%   |
| C       | 1         | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 58        | 55.77%  |
| EFI  | 46        | 44.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 75.24%  |
| Overlay | 13        | 12.38%  |
| Btrfs   | 6         | 5.71%   |
| Unknown | 5         | 4.76%   |
| Zfs     | 1         | 0.95%   |
| Xfs     | 1         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 72.64%  |
| GPT     | 21        | 19.81%  |
| MBR     | 8         | 7.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 85.58%  |
| Yes       | 15        | 14.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 74.53%  |
| Yes       | 27        | 25.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 18        | 18.18%  |
| Dell                    | 17        | 17.17%  |
| Gigabyte Technology     | 9         | 9.09%   |
| MSI                     | 8         | 8.08%   |
| ASUSTek Computer        | 8         | 8.08%   |
| Lenovo                  | 7         | 7.07%   |
| ASRock                  | 7         | 7.07%   |
| Acer                    | 5         | 5.05%   |
| Toshiba                 | 3         | 3.03%   |
| Apple                   | 3         | 3.03%   |
| Sony                    | 2         | 2.02%   |
| Raspberry Pi Foundation | 2         | 2.02%   |
| Intel                   | 2         | 2.02%   |
| TUXEDO                  | 1         | 1.01%   |
| Pegatron                | 1         | 1.01%   |
| GPU Company             | 1         | 1.01%   |
| CompuLab                | 1         | 1.01%   |
| AZW                     | 1         | 1.01%   |
| AMI                     | 1         | 1.01%   |
| Alienware               | 1         | 1.01%   |
| Acidanthera             | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Dell Vostro 3550                        | 3         | 3.03%   |
| RPi Raspberry Pi                        | 2         | 2.02%   |
| MSI Cubi N 8GL (MS-B171)                | 2         | 2.02%   |
| Intel SKYBAY                            | 2         | 2.02%   |
| ASRock Q1900M                           | 2         | 2.02%   |
| ASRock 945GCM-S                         | 2         | 2.02%   |
| TUXEDO Aura 15 Gen1                     | 1         | 1.01%   |
| Toshiba Satellite P755                  | 1         | 1.01%   |
| Toshiba Satellite L655                  | 1         | 1.01%   |
| Toshiba Satellite C55-C                 | 1         | 1.01%   |
| Sony VPCEA36FX                          | 1         | 1.01%   |
| Sony VGN-CS320J                         | 1         | 1.01%   |
| Pegatron QW716AA#ABA                    | 1         | 1.01%   |
| MSI US PIO PRO AP241                    | 1         | 1.01%   |
| MSI MS-7B48                             | 1         | 1.01%   |
| MSI MS-7971                             | 1         | 1.01%   |
| MSI MS-7817                             | 1         | 1.01%   |
| MSI GF65 Thin 10SDR                     | 1         | 1.01%   |
| MSI Cubi N JSL (MS-B0A1)                | 1         | 1.01%   |
| Lenovo Yoga 910-13IKB 80VF              | 1         | 1.01%   |
| Lenovo ThinkPad T410 2516ADU            | 1         | 1.01%   |
| Lenovo ThinkCentre M91p 7033CG1         | 1         | 1.01%   |
| Lenovo ThinkCentre M58p 6136A66         | 1         | 1.01%   |
| Lenovo IdeaPad 120S-11IAP 81A4          | 1         | 1.01%   |
| Lenovo IdeaCentre 510A-15ARR 90J0000PUS | 1         | 1.01%   |
| Lenovo G50-45 80E3                      | 1         | 1.01%   |
| HP Stream Laptop 14-CB1xxx              | 1         | 1.01%   |
| HP ProBook 6560b                        | 1         | 1.01%   |
| HP ProBook 6450b                        | 1         | 1.01%   |
| HP Pavilion Gaming Laptop 15-dk0xxx     | 1         | 1.01%   |
| HP Notebook                             | 1         | 1.01%   |
| HP Laptop 15-dy1xxx                     | 1         | 1.01%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.01%   |
| HP Laptop 14-dk1xxx                     | 1         | 1.01%   |
| HP ENVY Laptop 17m-bw0xxx               | 1         | 1.01%   |
| HP ENVY dv7                             | 1         | 1.01%   |
| HP EliteDesk 800 G1 TWR                 | 1         | 1.01%   |
| HP EliteDesk 800 G1 SFF                 | 1         | 1.01%   |
| HP EliteBook 840 G2                     | 1         | 1.01%   |
| HP Compaq Pro 6300 SFF                  | 1         | 1.01%   |
| HP Compaq Pro 6300 MT                   | 1         | 1.01%   |
| HP Compaq nc6400 (RB516UT#ABA)          | 1         | 1.01%   |
| HP Compaq dc7800p Small Form Factor     | 1         | 1.01%   |
| HP Compaq 8200 Elite SFF PC             | 1         | 1.01%   |
| GPU Company GWTN156-9                   | 1         | 1.01%   |
| Gigabyte Z97M-DS3H                      | 1         | 1.01%   |
| Gigabyte X570 GAMING X                  | 1         | 1.01%   |
| Gigabyte X570 AORUS ELITE WIFI          | 1         | 1.01%   |
| Gigabyte X399 AORUS Gaming 7            | 1         | 1.01%   |
| Gigabyte J1900N-D3V                     | 1         | 1.01%   |
| Gigabyte F2A78M-HD2                     | 1         | 1.01%   |
| Gigabyte F2A68HM-H                      | 1         | 1.01%   |
| Gigabyte B450M DS3H                     | 1         | 1.01%   |
| Gigabyte B450 AORUS PRO WIFI            | 1         | 1.01%   |
| Dell Studio 540                         | 1         | 1.01%   |
| Dell OptiPlex 960                       | 1         | 1.01%   |
| Dell OptiPlex 9020                      | 1         | 1.01%   |
| Dell OptiPlex 780                       | 1         | 1.01%   |
| Dell OptiPlex 7020                      | 1         | 1.01%   |
| Dell Latitude E6410                     | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 7         | 7.07%   |
| HP Compaq             | 5         | 5.05%   |
| Dell OptiPlex         | 4         | 4.04%   |
| Toshiba Satellite     | 3         | 3.03%   |
| MSI Cubi              | 3         | 3.03%   |
| HP Laptop             | 3         | 3.03%   |
| Dell Vostro           | 3         | 3.03%   |
| Acer Aspire           | 3         | 3.03%   |
| RPi Raspberry         | 2         | 2.02%   |
| Lenovo ThinkCentre    | 2         | 2.02%   |
| Intel SKYBAY          | 2         | 2.02%   |
| HP ProBook            | 2         | 2.02%   |
| HP ENVY               | 2         | 2.02%   |
| HP EliteDesk          | 2         | 2.02%   |
| Gigabyte X570         | 2         | 2.02%   |
| Dell Latitude         | 2         | 2.02%   |
| ASUS ROG              | 2         | 2.02%   |
| ASRock Q1900M         | 2         | 2.02%   |
| ASRock 945GCM-S       | 2         | 2.02%   |
| Acer Swift            | 2         | 2.02%   |
| TUXEDO Aura           | 1         | 1.01%   |
| Sony VPCEA36FX        | 1         | 1.01%   |
| Sony VGN-CS320J       | 1         | 1.01%   |
| Pegatron QW716AA#ABA  | 1         | 1.01%   |
| MSI US                | 1         | 1.01%   |
| MSI MS-7B48           | 1         | 1.01%   |
| MSI MS-7971           | 1         | 1.01%   |
| MSI MS-7817           | 1         | 1.01%   |
| MSI GF65              | 1         | 1.01%   |
| Lenovo Yoga           | 1         | 1.01%   |
| Lenovo ThinkPad       | 1         | 1.01%   |
| Lenovo IdeaPad        | 1         | 1.01%   |
| Lenovo IdeaCentre     | 1         | 1.01%   |
| Lenovo G50-45         | 1         | 1.01%   |
| HP Stream             | 1         | 1.01%   |
| HP Pavilion           | 1         | 1.01%   |
| HP Notebook           | 1         | 1.01%   |
| HP EliteBook          | 1         | 1.01%   |
| GPU Company GWTN156-9 | 1         | 1.01%   |
| Gigabyte Z97M-DS3H    | 1         | 1.01%   |
| Gigabyte X399         | 1         | 1.01%   |
| Gigabyte J1900N-D3V   | 1         | 1.01%   |
| Gigabyte F2A78M-HD2   | 1         | 1.01%   |
| Gigabyte F2A68HM-H    | 1         | 1.01%   |
| Gigabyte B450M        | 1         | 1.01%   |
| Gigabyte B450         | 1         | 1.01%   |
| Dell Studio           | 1         | 1.01%   |
| CompuLab fit-PC3      | 1         | 1.01%   |
| AZW GT-R              | 1         | 1.01%   |
| ASUS X540SAA          | 1         | 1.01%   |
| ASUS TUF              | 1         | 1.01%   |
| ASUS PRIME            | 1         | 1.01%   |
| ASUS M5A78L-M         | 1         | 1.01%   |
| ASUS M2N-E            | 1         | 1.01%   |
| ASUS K53E             | 1         | 1.01%   |
| ASRock Z270           | 1         | 1.01%   |
| ASRock G31M-S         | 1         | 1.01%   |
| ASRock B450M-HDV      | 1         | 1.01%   |
| Apple MacBookPro8     | 1         | 1.01%   |
| Apple MacBookPro5     | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 12        | 12.12%  |
| 2019    | 11        | 11.11%  |
| 2018    | 11        | 11.11%  |
| 2014    | 9         | 9.09%   |
| 2020    | 7         | 7.07%   |
| 2015    | 7         | 7.07%   |
| 2016    | 6         | 6.06%   |
| 2008    | 6         | 6.06%   |
| 2012    | 5         | 5.05%   |
| 2010    | 5         | 5.05%   |
| 2021    | 4         | 4.04%   |
| 2013    | 4         | 4.04%   |
| 2017    | 3         | 3.03%   |
| 2009    | 3         | 3.03%   |
| 2006    | 2         | 2.02%   |
| Unknown | 2         | 2.02%   |
| 2007    | 1         | 1.01%   |
| 2005    | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 48        | 48.48%  |
| Notebook       | 44        | 44.44%  |
| All in one     | 3         | 3.03%   |
| System on chip | 2         | 2.02%   |
| Convertible    | 1         | 1.01%   |
| Mini pc        | 1         | 1.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 94        | 94%     |
| Enabled  | 6         | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 32.35%  |
| 3.01-4.0    | 21        | 20.59%  |
| 8.01-16.0   | 20        | 19.61%  |
| 16.01-24.0  | 13        | 12.75%  |
| 32.01-64.0  | 6         | 5.88%   |
| 1.01-2.0    | 5         | 4.9%    |
| 24.01-32.0  | 2         | 1.96%   |
| 64.01-256.0 | 2         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 47.93%  |
| 2.01-3.0  | 24        | 19.83%  |
| 3.01-4.0  | 16        | 13.22%  |
| 4.01-8.0  | 13        | 10.74%  |
| 0.51-1.0  | 9         | 7.44%   |
| 8.01-16.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 57.94%  |
| 2      | 22        | 20.56%  |
| 3      | 15        | 14.02%  |
| 4      | 5         | 4.67%   |
| 6      | 1         | 0.93%   |
| 5      | 1         | 0.93%   |
| 0      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 51.96%  |
| No        | 49        | 48.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 87.88%  |
| No        | 12        | 12.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 73.27%  |
| No        | 27        | 26.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 58.82%  |
| No        | 42        | 41.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Puerto Rico | 99        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San Juan      | 40        | 36.36%  |
| Bayam??n      | 19        | 17.27%  |
| Carolina      | 9         | 8.18%   |
| Ponce         | 4         | 3.64%   |
| Cayey         | 4         | 3.64%   |
| Caguas        | 4         | 3.64%   |
| Aguadilla     | 3         | 2.73%   |
| Vega Alta     | 2         | 1.82%   |
| Sabana Grande | 2         | 1.82%   |
| Mayag??ez     | 2         | 1.82%   |
| Lares         | 2         | 1.82%   |
| Guayama       | 2         | 1.82%   |
| Dorado        | 2         | 1.82%   |
| San Sebastian | 1         | 0.91%   |
| Rio Grande    | 1         | 0.91%   |
| Patillas      | 1         | 0.91%   |
| Morovis       | 1         | 0.91%   |
| Maunabo       | 1         | 0.91%   |
| Las Piedras   | 1         | 0.91%   |
| Humacao       | 1         | 0.91%   |
| Hatillo       | 1         | 0.91%   |
| Gurabo        | 1         | 0.91%   |
| Fajardo       | 1         | 0.91%   |
| Ensenada      | 1         | 0.91%   |
| Coamo         | 1         | 0.91%   |
| Catano        | 1         | 0.91%   |
| Barceloneta   | 1         | 0.91%   |
| Arecibo       | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 31        | 72     | 21.23%  |
| Seagate                     | 19        | 35     | 13.01%  |
| Toshiba                     | 15        | 18     | 10.27%  |
| Samsung Electronics         | 10        | 19     | 6.85%   |
| Crucial                     | 9         | 12     | 6.16%   |
| Hitachi                     | 8         | 22     | 5.48%   |
| Unknown                     | 7         | 10     | 4.79%   |
| China                       | 5         | 7      | 3.42%   |
| A-DATA Technology           | 5         | 10     | 3.42%   |
| Silicon Motion              | 3         | 3      | 2.05%   |
| SanDisk                     | 3         | 3      | 2.05%   |
| Micron/Crucial Technology   | 3         | 3      | 2.05%   |
| External                    | 3         | 4      | 2.05%   |
| TDAS                        | 2         | 10     | 1.37%   |
| SABRENT                     | 2         | 2      | 1.37%   |
| PNY                         | 2         | 2      | 1.37%   |
| Phison                      | 2         | 2      | 1.37%   |
| LITEONIT                    | 2         | 2      | 1.37%   |
| WD MediaMax                 | 1         | 3      | 0.68%   |
| W800SH                      | 1         | 1      | 0.68%   |
| USB3.0                      | 1         | 1      | 0.68%   |
| Team                        | 1         | 1      | 0.68%   |
| SK hynix                    | 1         | 2      | 0.68%   |
| Micron Technology           | 1         | 1      | 0.68%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.68%   |
| Kingston                    | 1         | 1      | 0.68%   |
| JMicron Technology          | 1         | 4      | 0.68%   |
| INTEL SS                    | 1         | 1      | 0.68%   |
| Intel                       | 1         | 1      | 0.68%   |
| HGST                        | 1         | 1      | 0.68%   |
| Axiom                       | 1         | 3      | 0.68%   |
| Argon                       | 1         | 1      | 0.68%   |
| addlink                     | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB           | 5         | 3.11%   |
| WDC WD5000LPVT-22G33T0 500GB           | 3         | 1.86%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.86%   |
| External USB3.0 120GB                  | 3         | 1.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 1.24%   |
| WDC WDBNCE2500PNC 250GB SSD            | 2         | 1.24%   |
| WDC WD5000LPLX-22ZNTT0 500GB           | 2         | 1.24%   |
| WDC WD2500BEVS-60UST0 250GB            | 2         | 1.24%   |
| Unknown MMC Card  2GB                  | 2         | 1.24%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 1.24%   |
| Toshiba MK3261GSYN 320GB               | 2         | 1.24%   |
| Toshiba DT01ACA050 500GB               | 2         | 1.24%   |
| TDAS TerraMaster 1TB                   | 2         | 1.24%   |
| Seagate ST320DM001 HD322GJ 320GB       | 2         | 1.24%   |
| Seagate ST2000VM003-1CT164 2TB         | 2         | 1.24%   |
| Seagate Expansion 1TB                  | 2         | 1.24%   |
| Samsung SSD 850 EVO 500GB              | 2         | 1.24%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2         | 1.24%   |
| SABRENT Disk 1TB                       | 2         | 1.24%   |
| Micron/Crucial NVMe SSD Drive 500GB    | 2         | 1.24%   |
| Hitachi HTS547550A9E384 500GB          | 2         | 1.24%   |
| Crucial CT240M500SSD1 240GB            | 2         | 1.24%   |
| China SATA SSD 512GB                   | 2         | 1.24%   |
| WDC WDBNCE0010PNC 1TB SSD              | 1         | 0.62%   |
| WDC WD7500BPVX-60JC3T0 752GB           | 1         | 0.62%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.62%   |
| WDC WD5000BPVT-75HXZT1 500GB           | 1         | 0.62%   |
| WDC WD40EZRZ-22GXCB0 4TB               | 1         | 0.62%   |
| WDC WD30EZRZ-00WN9B0 3TB               | 1         | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 1         | 0.62%   |
| WDC WD1600AAJS-00PSA0 160GB            | 1         | 0.62%   |
| WDC WD1500HLFS-01G6U1 150GB            | 1         | 0.62%   |
| WDC WD1200BEVS-75UST0 120GB            | 1         | 0.62%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.62%   |
| WDC WD10SPZX-22Z10T1 1TB               | 1         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 0.62%   |
| WDC WD10SPCX-75KHST0 1TB               | 1         | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.62%   |
| WDC WD10EZRX-00L4HB0 1TB               | 1         | 0.62%   |
| WDC WD10EZEX-75WN4A1 1TB               | 1         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1         | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB               | 1         | 0.62%   |
| WDC WD10EURX-63FH1Y0 1TB               | 1         | 0.62%   |
| WDC WD10EAVS-00D7B1 1TB                | 1         | 0.62%   |
| WDC WD1003FBYZ-010FB0 1TB              | 1         | 0.62%   |
| WDC WD1003FBYX-05Y7B0 1TB              | 1         | 0.62%   |
| WDC PC SN530 SDBPNPZ-512G-1032 512GB   | 1         | 0.62%   |
| WD MediaMax WL500GSA3272 500GB         | 1         | 0.62%   |
| W800SH 512GB SSD                       | 1         | 0.62%   |
| USB3.0 Super Speed 320GB               | 1         | 0.62%   |
| Unknown MMC Card  64GB                 | 1         | 0.62%   |
| Unknown MMC Card  32GB                 | 1         | 0.62%   |
| Unknown MMC Card  10GB                 | 1         | 0.62%   |
| Unknown HBG4a2  32GB                   | 1         | 0.62%   |
| Unknown Externa 250GB                  | 1         | 0.62%   |
| Unknown DA4064  64GB                   | 1         | 0.62%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 0.62%   |
| Toshiba MQ01ABF050 500GB               | 1         | 0.62%   |
| Toshiba MK3276GSX 320GB                | 1         | 0.62%   |
| Toshiba MK3254GSY 320GB                | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 62     | 36.76%  |
| Seagate             | 19        | 35     | 27.94%  |
| Toshiba             | 14        | 17     | 20.59%  |
| Hitachi             | 8         | 22     | 11.76%  |
| Samsung Electronics | 1         | 1      | 1.47%   |
| HGST                | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 21.95%  |
| Samsung Electronics | 7         | 11     | 17.07%  |
| WDC                 | 5         | 8      | 12.2%   |
| China               | 5         | 7      | 12.2%   |
| A-DATA Technology   | 5         | 10     | 12.2%   |
| PNY                 | 2         | 2      | 4.88%   |
| LITEONIT            | 2         | 2      | 4.88%   |
| W800SH              | 1         | 1      | 2.44%   |
| USB3.0              | 1         | 1      | 2.44%   |
| SanDisk             | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| INTEL SS            | 1         | 1      | 2.44%   |
| Argon               | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 61        | 138    | 45.86%  |
| SSD     | 38        | 58     | 28.57%  |
| NVMe    | 22        | 33     | 16.54%  |
| MMC     | 6         | 9      | 4.51%   |
| Unknown | 6         | 21     | 4.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 196    | 69.05%  |
| NVMe | 19        | 27     | 15.08%  |
| SAS  | 14        | 27     | 11.11%  |
| MMC  | 6         | 9      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 99     | 54.37%  |
| 0.51-1.0   | 35        | 69     | 33.98%  |
| 1.01-2.0   | 8         | 19     | 7.77%   |
| 3.01-4.0   | 3         | 8      | 2.91%   |
| 2.01-3.0   | 1         | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 22.13%  |
| 101-250        | 25        | 20.49%  |
| 501-1000       | 22        | 18.03%  |
| 1-20           | 11        | 9.02%   |
| 1001-2000      | 10        | 8.2%    |
| 2001-3000      | 9         | 7.38%   |
| More than 3000 | 8         | 6.56%   |
| 51-100         | 4         | 3.28%   |
| 21-50          | 3         | 2.46%   |
| Unknown        | 3         | 2.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 44        | 35.77%  |
| 21-50     | 22        | 17.89%  |
| 101-250   | 14        | 11.38%  |
| 51-100    | 12        | 9.76%   |
| 251-500   | 11        | 8.94%   |
| 501-1000  | 10        | 8.13%   |
| 1001-2000 | 6         | 4.88%   |
| Unknown   | 3         | 2.44%   |
| 2001-3000 | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-60UST0 250GB                      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 8.33%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 8.33%   |
| Seagate ST320DM001 HD322GJ 320GB                 | 1         | 1      | 8.33%   |
| Seagate ST2000VM003-1CT164 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST2000LM007-1R8174 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 8.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 8.33%   |
| Hitachi HTS545025B9A300 250GB                    | 1         | 1      | 8.33%   |
| A-DATA Technology SU630 240GB SSD                | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 6      | 40%     |
| WDC                 | 1         | 1      | 10%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 6      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 9      | 70%     |
| SSD  | 3         | 3      | 30%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 78        | 215    | 71.56%  |
| Works    | 21        | 32     | 19.27%  |
| Malfunc  | 10        | 12     | 9.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 61.06%  |
| AMD                          | 22        | 19.47%  |
| Silicon Motion               | 4         | 3.54%   |
| Samsung Electronics          | 3         | 2.65%   |
| Phison Electronics           | 3         | 2.65%   |
| Micron/Crucial Technology    | 3         | 2.65%   |
| SanDisk                      | 2         | 1.77%   |
| Nvidia                       | 2         | 1.77%   |
| Toshiba America Info Systems | 1         | 0.88%   |
| SK hynix                     | 1         | 0.88%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.88%   |
| Kingston Technology Company  | 1         | 0.88%   |
| ASMedia Technology           | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 13.24%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 4.41%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 3.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 2.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 2.94%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.21%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 2.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 2.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.21%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 2.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.47%   |
| AMD FCH IDE Controller                                                                  | 2         | 1.47%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.74%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1         | 0.74%   |
| Nvidia CK804 IDE                                                                        | 1         | 0.74%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1002                                            | 1         | 0.74%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.74%   |
| Intel NVMe Optane Memory Series                                                         | 1         | 0.74%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1         | 0.74%   |
| Intel Comet Lake PCH-H RAID                                                             | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.74%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1         | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.74%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1         | 0.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.74%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 60%     |
| NVMe | 19        | 15.83%  |
| IDE  | 18        | 15%     |
| RAID | 11        | 9.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 73.74%  |
| AMD    | 24        | 24.24%  |
| ARM    | 2         | 2.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 3         | 3.03%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 3.03%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3         | 3.03%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 2.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 2.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.02%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 2         | 2.02%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2         | 2.02%   |
| ARM Processor                               | 2         | 2.02%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 2.02%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 2.02%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 2         | 2.02%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.01%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 1.01%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 1.01%   |
| Intel Genuine CPU T2250 @ 1.73GHz           | 1         | 1.01%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.01%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.01%   |
| Intel Core i7-3540M CPU @ 3.00GHz           | 1         | 1.01%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.01%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.01%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.01%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 1.01%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.01%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.01%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.01%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.01%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.01%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.01%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 1.01%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1         | 1.01%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.01%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.01%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.01%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1         | 1.01%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.01%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 1.01%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.01%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.01%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.01%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.01%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1         | 1.01%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1         | 1.01%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.01%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1         | 1.01%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.01%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 1         | 1.01%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 19.19%  |
| Intel Celeron           | 14        | 14.14%  |
| Intel Core i7           | 10        | 10.1%   |
| Intel Core i3           | 10        | 10.1%   |
| Intel Core 2 Duo        | 7         | 7.07%   |
| Other                   | 5         | 5.05%   |
| AMD Ryzen 5             | 5         | 5.05%   |
| Intel Pentium Silver    | 4         | 4.04%   |
| AMD Ryzen 7             | 4         | 4.04%   |
| AMD A8                  | 4         | 4.04%   |
| AMD Ryzen 3             | 3         | 3.03%   |
| Intel Pentium Dual-Core | 2         | 2.02%   |
| Intel Pentium           | 2         | 2.02%   |
| AMD A6                  | 2         | 2.02%   |
| Intel Genuine           | 1         | 1.01%   |
| Intel Core 2            | 1         | 1.01%   |
| AMD Ryzen Threadripper  | 1         | 1.01%   |
| AMD G                   | 1         | 1.01%   |
| AMD FX                  | 1         | 1.01%   |
| AMD Athlon 64 X2        | 1         | 1.01%   |
| AMD Athlon              | 1         | 1.01%   |
| AMD A10                 | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 54.55%  |
| 4      | 28        | 28.28%  |
| 6      | 8         | 8.08%   |
| 8      | 5         | 5.05%   |
| 1      | 3         | 3.03%   |
| 16     | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 52.53%  |
| 1      | 47        | 47.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 96        | 96%     |
| Unknown        | 3         | 3%      |
| 32-bit         | 1         | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 20.19%  |
| 0x206a7    | 9         | 8.65%   |
| 0x306c3    | 6         | 5.77%   |
| 0x806e9    | 4         | 3.85%   |
| 0x706a1    | 4         | 3.85%   |
| 0x306a9    | 4         | 3.85%   |
| 0x20655    | 4         | 3.85%   |
| 0x1067a    | 4         | 3.85%   |
| 0x30678    | 3         | 2.88%   |
| 0x06001119 | 3         | 2.88%   |
| 0xa0671    | 2         | 1.92%   |
| 0x906ea    | 2         | 1.92%   |
| 0x806ea    | 2         | 1.92%   |
| 0x6fd      | 2         | 1.92%   |
| 0x406e3    | 2         | 1.92%   |
| 0x306d4    | 2         | 1.92%   |
| 0x08701013 | 2         | 1.92%   |
| 0x08108109 | 2         | 1.92%   |
| 0x06003106 | 2         | 1.92%   |
| 0xa0652    | 1         | 0.96%   |
| 0x906ed    | 1         | 0.96%   |
| 0x906e9    | 1         | 0.96%   |
| 0x906c0    | 1         | 0.96%   |
| 0x806c1    | 1         | 0.96%   |
| 0x706e5    | 1         | 0.96%   |
| 0x6fb      | 1         | 0.96%   |
| 0x6e8      | 1         | 0.96%   |
| 0x506e3    | 1         | 0.96%   |
| 0x506c9    | 1         | 0.96%   |
| 0x406c4    | 1         | 0.96%   |
| 0x406c3    | 1         | 0.96%   |
| 0x40651    | 1         | 0.96%   |
| 0x30679    | 1         | 0.96%   |
| 0x20652    | 1         | 0.96%   |
| 0x10676    | 1         | 0.96%   |
| 0x08600106 | 1         | 0.96%   |
| 0x08101007 | 1         | 0.96%   |
| 0x0800820d | 1         | 0.96%   |
| 0x08001137 | 1         | 0.96%   |
| 0x07030105 | 1         | 0.96%   |
| 0x06000852 | 1         | 0.96%   |
| 0x05000119 | 1         | 0.96%   |
| 0x03000027 | 1         | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 10        | 10.1%   |
| KabyLake      | 10        | 10.1%   |
| Penryn        | 8         | 8.08%   |
| Haswell       | 7         | 7.07%   |
| Silvermont    | 6         | 6.06%   |
| Zen+          | 5         | 5.05%   |
| Zen 2         | 5         | 5.05%   |
| Westmere      | 5         | 5.05%   |
| Goldmont plus | 5         | 5.05%   |
| Skylake       | 4         | 4.04%   |
| Piledriver    | 4         | 4.04%   |
| IvyBridge     | 4         | 4.04%   |
| Core          | 4         | 4.04%   |
| Zen           | 3         | 3.03%   |
| Unknown       | 3         | 3.03%   |
| Steamroller   | 2         | 2.02%   |
| Icelake       | 2         | 2.02%   |
| Broadwell     | 2         | 2.02%   |
| Zen 3         | 1         | 1.01%   |
| Tremont       | 1         | 1.01%   |
| TigerLake     | 1         | 1.01%   |
| Puma          | 1         | 1.01%   |
| P6            | 1         | 1.01%   |
| K8 Hammer     | 1         | 1.01%   |
| K10 Llano     | 1         | 1.01%   |
| Goldmont      | 1         | 1.01%   |
| CometLake     | 1         | 1.01%   |
| Bobcat        | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 62.04%  |
| AMD    | 22        | 20.37%  |
| Nvidia | 19        | 17.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 8.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 4.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.59%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 2.59%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.59%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 1.72%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 2         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.72%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.72%   |
| Intel HD Graphics 620                                                                    | 2         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 1.72%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.86%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.86%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.86%   |
| Nvidia GK208 [GeForce GT 720]                                                            | 1         | 0.86%   |
| Nvidia GK110GL [Tesla K20Xm]                                                             | 1         | 0.86%   |
| Nvidia GK104GL [GRID K2]                                                                 | 1         | 0.86%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.86%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.86%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1         | 0.86%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.86%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.86%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.86%   |
| Intel HD Graphics 630                                                                    | 1         | 0.86%   |
| Intel HD Graphics 500                                                                    | 1         | 0.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.86%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 0.86%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.86%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 0.86%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 1         | 0.86%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 58        | 57.43%  |
| 1 x AMD            | 19        | 18.81%  |
| 1 x Nvidia         | 11        | 10.89%  |
| Intel + Nvidia     | 5         | 4.95%   |
| Intel + AMD        | 3         | 2.97%   |
| Other              | 2         | 1.98%   |
| Intel + 2 x Nvidia | 2         | 1.98%   |
| 2 x Nvidia         | 1         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 85        | 82.52%  |
| Proprietary | 12        | 11.65%  |
| Unknown     | 6         | 5.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 63.21%  |
| 0.01-0.5   | 11        | 10.38%  |
| 0.51-1.0   | 10        | 9.43%   |
| 1.01-2.0   | 7         | 6.6%    |
| 3.01-4.0   | 5         | 4.72%   |
| 5.01-6.0   | 3         | 2.83%   |
| 8.01-16.0  | 2         | 1.89%   |
| 2.01-3.0   | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 10.09%  |
| LG Display              | 9         | 8.26%   |
| Goldstar                | 9         | 8.26%   |
| Dell                    | 7         | 6.42%   |
| Chimei Innolux          | 7         | 6.42%   |
| AU Optronics            | 6         | 5.5%    |
| Acer                    | 6         | 5.5%    |
| Hewlett-Packard         | 5         | 4.59%   |
| BOE                     | 5         | 4.59%   |
| ViewSonic               | 4         | 3.67%   |
| Sony                    | 4         | 3.67%   |
| AOC                     | 4         | 3.67%   |
| Vizio                   | 3         | 2.75%   |
| Sceptre Tech            | 3         | 2.75%   |
| Gateway                 | 3         | 2.75%   |
| Element                 | 3         | 2.75%   |
| Apple                   | 3         | 2.75%   |
| VIZ                     | 2         | 1.83%   |
| Tech Concepts           | 2         | 1.83%   |
| eMachines               | 2         | 1.83%   |
| Unknown                 | 1         | 0.92%   |
| UGD                     | 1         | 0.92%   |
| Seiki                   | 1         | 0.92%   |
| RTK                     | 1         | 0.92%   |
| PANDA                   | 1         | 0.92%   |
| ONN                     | 1         | 0.92%   |
| MStar                   | 1         | 0.92%   |
| Lenovo                  | 1         | 0.92%   |
| InnoLux Display         | 1         | 0.92%   |
| Chi Mei Optoelectronics | 1         | 0.92%   |
| ASUSTek Computer        | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 4.35%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch            | 3         | 2.61%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 3         | 2.61%   |
| Element ELEFW504A ELE1366 1920x1080                                    | 3         | 2.61%   |
| VIZ LCD Monitor M551d-A2R                                              | 2         | 1.74%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch          | 2         | 1.74%   |
| Sony TV  *00 SNY4B04 3840x2160                                         | 2         | 1.74%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2         | 1.74%   |
| Gateway LCD Monitor FHX2300                                            | 2         | 1.74%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                  | 2         | 1.74%   |
| eMachines E19T6W EMA0783 1440x900 410x260mm 19.1-inch                  | 2         | 1.74%   |
| Dell DELLSE2216HV DELF072 1920x1080 476x268mm 21.5-inch                | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.74%   |
| Acer LCD Monitor G236HL 5760x1080                                      | 2         | 1.74%   |
| Vizio M422i-B1 VIZ1006 1920x1080 930x523mm 42.0-inch                   | 1         | 0.87%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1         | 0.87%   |
| Vizio D32f-G1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1         | 0.87%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch               | 1         | 0.87%   |
| ViewSonic VA1930wm VSC171F 1440x900 410x260mm 19.1-inch                | 1         | 0.87%   |
| Unknown LCD Monitor Dell S2719DGF 2560x1440                            | 1         | 0.87%   |
| UGD Artist 156 UGD1501 1920x1080 293x165mm 13.2-inch                   | 1         | 0.87%   |
| Tech Concepts LCD Monitor 43S431 3840x2160                             | 1         | 0.87%   |
| Tech Concepts LCD Monitor 43S423 1920x1080                             | 1         | 0.87%   |
| Sony TV SNYEA01 1920x1080                                              | 1         | 0.87%   |
| Sony TV SNY4502 1920x1080                                              | 1         | 0.87%   |
| Seiki SE241TS SEK0CF0 1920x1080 520x290mm 23.4-inch                    | 1         | 0.87%   |
| Sceptre Tech Sceptre X22HG SPT2204 1920x1080 474x296mm 22.0-inch       | 1         | 0.87%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 598x336mm 27.0-inch         | 1         | 0.87%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                 | 1         | 0.87%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.87%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5857 1440x900 367x230mm 17.1-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.87%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1         | 0.87%   |
| RTK PRO AP241 RTK2136 1920x1080 527x296mm 23.8-inch                    | 1         | 0.87%   |
| PANDA LCD Monitor NCP0030 1920x1080 344x194mm 15.5-inch                | 1         | 0.87%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                   | 1         | 0.87%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 1         | 0.87%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD051E 3840x2160 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0513 1920x1080 382x215mm 17.3-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch            | 1         | 0.87%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch            | 1         | 0.87%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                | 1         | 0.87%   |
| InnoLux Display LCD Monitor INL0028 1366x768 309x174mm 14.0-inch       | 1         | 0.87%   |
| Hewlett-Packard P17A HWP3142 1280x1024 338x270mm 17.0-inch             | 1         | 0.87%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1         | 0.87%   |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch          | 1         | 0.87%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch             | 1         | 0.87%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 0.87%   |
| Goldstar W2240 GSM57A1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.87%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1         | 0.87%   |
| Gateway LCD Monitor FHX2300 3840x1080                                  | 1         | 0.87%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                     | 1         | 0.87%   |
| Dell S2330MX DELD049 1920x1080 509x286mm 23.0-inch                     | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 41%     |
| 1366x768 (WXGA)    | 23        | 23%     |
| 3840x2160 (4K)     | 10        | 10%     |
| 1440x900 (WXGA+)   | 6         | 6%      |
| 1600x900 (HD+)     | 4         | 4%      |
| 1280x800 (WXGA)    | 4         | 4%      |
| 5760x1080          | 2         | 2%      |
| 1280x1024 (SXGA)   | 2         | 2%      |
| Unknown            | 2         | 2%      |
| 3840x1080          | 1         | 1%      |
| 3440x1440          | 1         | 1%      |
| 2560x1440 (QHD)    | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 1680x1050 (WSXGA+) | 1         | 1%      |
| 1280x720 (HD)      | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 21.7%   |
| 21      | 13        | 12.26%  |
| 23      | 10        | 9.43%   |
| 72      | 7         | 6.6%    |
| 14      | 7         | 6.6%    |
| 31      | 6         | 5.66%   |
| 17      | 6         | 5.66%   |
| 19      | 5         | 4.72%   |
| Unknown | 5         | 4.72%   |
| 20      | 4         | 3.77%   |
| 13      | 4         | 3.77%   |
| 27      | 3         | 2.83%   |
| 34      | 2         | 1.89%   |
| 11      | 2         | 1.89%   |
| 84      | 1         | 0.94%   |
| 64      | 1         | 0.94%   |
| 52      | 1         | 0.94%   |
| 49      | 1         | 0.94%   |
| 32      | 1         | 0.94%   |
| 25      | 1         | 0.94%   |
| 24      | 1         | 0.94%   |
| 22      | 1         | 0.94%   |
| 18      | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 29.81%  |
| 401-500     | 23        | 22.12%  |
| 501-600     | 14        | 13.46%  |
| 1501-2000   | 8         | 7.69%   |
| 601-700     | 6         | 5.77%   |
| 351-400     | 6         | 5.77%   |
| 201-300     | 5         | 4.81%   |
| Unknown     | 5         | 4.81%   |
| 701-800     | 3         | 2.88%   |
| 1001-1500   | 3         | 2.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 76.34%  |
| 16/10   | 12        | 12.9%   |
| Unknown | 5         | 5.38%   |
| 5/4     | 3         | 3.23%   |
| 21/9    | 2         | 2.15%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 21.9%   |
| 201-250        | 21        | 20%     |
| 151-200        | 13        | 12.38%  |
| More than 1000 | 10        | 9.52%   |
| 81-90          | 10        | 9.52%   |
| 351-500        | 9         | 8.57%   |
| Unknown        | 5         | 4.76%   |
| 301-350        | 3         | 2.86%   |
| 141-150        | 3         | 2.86%   |
| 121-130        | 3         | 2.86%   |
| 51-60          | 2         | 1.9%    |
| 71-80          | 1         | 0.95%   |
| 251-300        | 1         | 0.95%   |
| 131-140        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 38.61%  |
| 51-100        | 33        | 32.67%  |
| 121-160       | 12        | 11.88%  |
| 1-50          | 10        | 9.9%    |
| Unknown       | 5         | 4.95%   |
| More than 240 | 1         | 0.99%   |
| 161-240       | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 76.7%   |
| 2     | 18        | 17.48%  |
| 0     | 4         | 3.88%   |
| 3     | 2         | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 39.13%  |
| Intel                    | 52        | 32.3%   |
| Qualcomm Atheros         | 15        | 9.32%   |
| Broadcom                 | 6         | 3.73%   |
| NetGear                  | 5         | 3.11%   |
| Ralink Technology        | 4         | 2.48%   |
| Marvell Technology Group | 3         | 1.86%   |
| Broadcom Limited         | 3         | 1.86%   |
| TP-Link                  | 2         | 1.24%   |
| Samsung Electronics      | 2         | 1.24%   |
| Nvidia                   | 2         | 1.24%   |
| Ralink                   | 1         | 0.62%   |
| Gemtek                   | 1         | 0.62%   |
| Belkin Components        | 1         | 0.62%   |
| Aquantia                 | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 40        | 21.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.37%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 2.19%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.19%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 4         | 2.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3         | 1.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 3         | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 1.64%   |
| Intel Wireless 7265                                                            | 3         | 1.64%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.64%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.09%   |
| Realtek 802.11ac NIC                                                           | 2         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 2         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 1.09%   |
| NetGear LB1120-100NAS                                                          | 2         | 1.09%   |
| Intel Wireless 3160                                                            | 2         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 1.09%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 1.09%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.09%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.09%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                        | 2         | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.55%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                     | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1         | 0.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1         | 0.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.55%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                         | 1         | 0.55%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.55%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                              | 1         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.55%   |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1         | 0.55%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.55%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.55%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 0.55%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.55%   |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                               | 1         | 0.55%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                    | 1         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.55%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 38.37%  |
| Realtek Semiconductor | 22        | 25.58%  |
| Qualcomm Atheros      | 12        | 13.95%  |
| Broadcom              | 5         | 5.81%   |
| Ralink Technology     | 4         | 4.65%   |
| NetGear               | 3         | 3.49%   |
| TP-Link               | 2         | 2.33%   |
| Broadcom Limited      | 2         | 2.33%   |
| Ralink                | 1         | 1.16%   |
| Gemtek                | 1         | 1.16%   |
| Belkin Components     | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                     | Computers | Percent |
|-------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                       | 6         | 6.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                | 5         | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                  | 4         | 4.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                          | 4         | 4.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                        | 3         | 3.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                   | 3         | 3.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                | 3         | 3.3%    |
| Intel Wireless 7265                                                                       | 3         | 3.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                           | 2         | 2.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                     | 2         | 2.2%    |
| Realtek 802.11ac NIC                                                                      | 2         | 2.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                     | 2         | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                | 2         | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                | 2         | 2.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                          | 2         | 2.2%    |
| Intel Wireless 3160                                                                       | 2         | 2.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                     | 2         | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                            | 2         | 2.2%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                             | 2         | 2.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                              | 2         | 2.2%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                             | 2         | 2.2%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                   | 2         | 2.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                              | 1         | 1.1%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                | 1         | 1.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                   | 1         | 1.1%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                | 1         | 1.1%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                           | 1         | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                    | 1         | 1.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                               | 1         | 1.1%    |
| Realtek RTL8188RU 802.11n WLAN Adapter                                                    | 1         | 1.1%    |
| Realtek RTL8187 Wireless Adapter                                                          | 1         | 1.1%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                         | 1         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                                           | 1         | 1.1%    |
| Ralink RT2561/RT61 802.11g PCI                                                            | 1         | 1.1%    |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                | 1         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                          | 1         | 1.1%    |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                     | 1         | 1.1%    |
| NetGear MA111(v2) 802.11b Wireless [SIS SIS 162]                                          | 1         | 1.1%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                               | 1         | 1.1%    |
| Intel Wireless 8265 / 8275                                                                | 1         | 1.1%    |
| Intel Wireless 7260                                                                       | 1         | 1.1%    |
| Intel Wireless 3165                                                                       | 1         | 1.1%    |
| Intel WiFi Link 5100                                                                      | 1         | 1.1%    |
| Intel Wi-Fi 6 AX201 160MHz                                                                | 1         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                                       | 1         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                                            | 1         | 1.1%    |
| Intel Gemini Lake PCH CNVi WiFi                                                           | 1         | 1.1%    |
| Gemtek WUBR-177G [Ralink RT2571W]                                                         | 1         | 1.1%    |
| Broadcom BCM4331 802.11a/b/g/n                                                            | 1         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                    | 1         | 1.1%    |
| Broadcom BCM4321 802.11a/b/g/n                                                            | 1         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                                             | 1         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                       | 1         | 1.1%    |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU] | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 55.43%  |
| Intel                    | 25        | 27.17%  |
| Qualcomm Atheros         | 3         | 3.26%   |
| Marvell Technology Group | 3         | 3.26%   |
| Samsung Electronics      | 2         | 2.17%   |
| Nvidia                   | 2         | 2.17%   |
| NetGear                  | 2         | 2.17%   |
| Broadcom                 | 2         | 2.17%   |
| Broadcom Limited         | 1         | 1.09%   |
| Aquantia                 | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 40        | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 6.52%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 4.35%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 3.26%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.17%   |
| NetGear LB1120-100NAS                                                          | 2         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.09%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.09%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.09%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.09%   |
| Nvidia CK804 Ethernet Controller                                               | 1         | 1.09%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.09%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.09%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.09%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 1.09%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.09%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.09%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 1.09%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 54.04%  |
| WiFi     | 74        | 45.96%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 51.89%  |
| Ethernet | 51        | 48.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 49.5%   |
| 1     | 46        | 45.54%  |
| 3     | 3         | 2.97%   |
| 0     | 2         | 1.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 96.97%  |
| Yes  | 3         | 3.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 44.44%  |
| Realtek Semiconductor           | 7         | 11.11%  |
| Cambridge Silicon Radio         | 7         | 11.11%  |
| Qualcomm Atheros Communications | 5         | 7.94%   |
| Lite-On Technology              | 3         | 4.76%   |
| Apple                           | 3         | 4.76%   |
| Foxconn / Hon Hai               | 2         | 3.17%   |
| Broadcom                        | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| IMC Networks                    | 1         | 1.59%   |
| Hewlett-Packard                 | 1         | 1.59%   |
| Dynex                           | 1         | 1.59%   |
| Belkin Components               | 1         | 1.59%   |
| Alps Electric                   | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 12.7%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 11.11%  |
| Intel AX200 Bluetooth                                                               | 6         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 7.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 6.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 6.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.76%   |
| Intel Bluetooth Device                                                              | 3         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.76%   |
| Lite-On Bluetooth Device                                                            | 2         | 3.17%   |
| Broadcom Bluetooth Device                                                           | 2         | 3.17%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.17%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.59%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.59%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.59%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.59%   |
| Dynex BCM20702A0                                                                    | 1         | 1.59%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 1.59%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.59%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 72        | 59.02%  |
| AMD                                             | 23        | 18.85%  |
| Nvidia                                          | 16        | 13.11%  |
| Logitech                                        | 6         | 4.92%   |
| C-Media Electronics                             | 2         | 1.64%   |
| Nintendo                                        | 1         | 0.82%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.82%   |
| Kingston Technology                             | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 6%      |
| AMD FCH Azalia Controller                                                                         | 7         | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 4.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.67%   |
| Logitech EasyCall Speakerphone                                                                    | 3         | 2%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 2%      |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 2%      |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.33%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 1.33%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.33%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.33%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.67%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nintendo WUP-021-0                                                                                | 1         | 0.67%   |
| Logitech QuickCam Fusion                                                                          | 1         | 0.67%   |
| Logitech Headset H390                                                                             | 1         | 0.67%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 0.67%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 0.67%   |
| Kingston Technology HyperX SoloCast                                                               | 1         | 0.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.67%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.67%   |
| Intel Audio device                                                                                | 1         | 0.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.67%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.67%   |
| C-Media Electronics CM6501                                                                        | 1         | 0.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 23.53%  |
| Samsung Electronics | 8         | 23.53%  |
| Unknown             | 7         | 20.59%  |
| Kingston            | 3         | 8.82%   |
| Corsair             | 2         | 5.88%   |
| Sesame              | 1         | 2.94%   |
| PNY                 | 1         | 2.94%   |
| Micron Technology   | 1         | 2.94%   |
| G.Skill             | 1         | 2.94%   |
| Crucial             | 1         | 2.94%   |
| A-DATA Technology   | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 3         | 7.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2         | 5.13%   |
| Unknown RAM WPBS26D408SWC-8G 8192MB SODIMM DDR4 2667MT/s | 1         | 2.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1         | 2.56%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 1         | 2.56%   |
| Unknown RAM CL18-20-20 D4-3600 8192MB DIMM DDR4 3600MT/s | 1         | 2.56%   |
| SK hynix RAM Module 2048MB SODIMM DDR 667MT/s            | 1         | 2.56%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 2.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 2.56%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1         | 2.56%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s   | 1         | 2.56%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 2.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 2.56%   |
| Sesame RAM S939A2UGS-ITR 8192MB DIMM DDR3 1600MT/s       | 1         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 1         | 2.56%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s | 1         | 2.56%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s      | 1         | 2.56%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s   | 1         | 2.56%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s      | 1         | 2.56%   |
| PNY RAM 4GBH1X04E9992 4096MB DIMM DDR3 1600MT/s          | 1         | 2.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 1         | 2.56%   |
| Kingston RAM X2YH1K-MIE-NX 16GB DIMM DDR4 3200MT/s       | 1         | 2.56%   |
| Kingston RAM HP691160-H66-MCN 8GB SODIMM DDR3 1600MT/s   | 1         | 2.56%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s   | 1         | 2.56%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s   | 1         | 2.56%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8GB DIMM DDR3 1333MT/s     | 1         | 2.56%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s | 1         | 2.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1         | 2.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 1         | 2.56%   |
| A-DATA RAM AM1L16BC4R1-B1YS 4GB SODIMM DDR3 800MT/s      | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 44.12%  |
| DDR4    | 12        | 35.29%  |
| SDRAM   | 3         | 8.82%   |
| LPDDR4  | 2         | 5.88%   |
| DDR     | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 18        | 54.55%  |
| SODIMM | 15        | 45.45%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 45.71%  |
| 8192  | 13        | 37.14%  |
| 2048  | 5         | 14.29%  |
| 16384 | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 31.43%  |
| 2667    | 6         | 17.14%  |
| 3200    | 3         | 8.57%   |
| 1333    | 3         | 8.57%   |
| Unknown | 3         | 8.57%   |
| 3600    | 2         | 5.71%   |
| 667     | 2         | 5.71%   |
| 3466    | 1         | 2.86%   |
| 3266    | 1         | 2.86%   |
| 1867    | 1         | 2.86%   |
| 1866    | 1         | 2.86%   |
| 800     | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP OfficeJet Pro 6960 | 1         | 50%     |
| Brother MFC-L2685DW   | 1         | 50%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 18.37%  |
| Microdia                               | 6         | 12.24%  |
| Ricoh                                  | 5         | 10.2%   |
| Logitech                               | 5         | 10.2%   |
| Realtek Semiconductor                  | 3         | 6.12%   |
| Quanta                                 | 3         | 6.12%   |
| Acer                                   | 3         | 6.12%   |
| Suyin                                  | 2         | 4.08%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Lite-On Technology                     | 2         | 4.08%   |
| Apple                                  | 2         | 4.08%   |
| Luxvisions Innotech Limited            | 1         | 2.04%   |
| Lenovo                                 | 1         | 2.04%   |
| Jieli Technology                       | 1         | 2.04%   |
| IMC Networks                           | 1         | 2.04%   |
| Goertek Electronics                    | 1         | 2.04%   |
| Cubeternet                             | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Camera                                                | 4         | 8.16%   |
| Ricoh Integrated Webcam                                        | 3         | 6.12%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 4.08%   |
| Chicony HD WebCam                                              | 2         | 4.08%   |
| Suyin USB 2.0 Camera                                           | 1         | 2.04%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 2.04%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam       | 1         | 2.04%   |
| Ricoh HD Webcam                                                | 1         | 2.04%   |
| Realtek USB2.0 camera                                          | 1         | 2.04%   |
| Realtek USB Camera                                             | 1         | 2.04%   |
| Realtek Integrated Webcam HD                                   | 1         | 2.04%   |
| Quanta VGA WebCam                                              | 1         | 2.04%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.04%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 2.04%   |
| Microdia USB 2.0 Camera                                        | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 2.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.04%   |
| Logitech Webcam Pro 9000                                       | 1         | 2.04%   |
| Logitech Webcam C310                                           | 1         | 2.04%   |
| Logitech Webcam C270                                           | 1         | 2.04%   |
| Logitech HD Pro Webcam C920                                    | 1         | 2.04%   |
| Logitech CrystalCam                                            | 1         | 2.04%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 2.04%   |
| Lite-On HP HD Webcam                                           | 1         | 2.04%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.04%   |
| Jieli USB PHY 2.0                                              | 1         | 2.04%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 2.04%   |
| Goertek USB2.0 VGA UVC WebCam                                  | 1         | 2.04%   |
| Cubeternet GL-UPC822 UVC WebCam                                | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 2.04%   |
| Chicony Toshiba Integrated Webcam                              | 1         | 2.04%   |
| Chicony Integrated HP HD Webcam                                | 1         | 2.04%   |
| Chicony HP Webcam                                              | 1         | 2.04%   |
| Chicony HP Truevision HD                                       | 1         | 2.04%   |
| Chicony EasyCamera                                             | 1         | 2.04%   |
| Chicony CNF9055 Toshiba Webcam                                 | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.04%   |
| Apple FaceTime HD Camera                                       | 1         | 2.04%   |
| Apple Built-in iSight                                          | 1         | 2.04%   |
| Acer Lenovo EasyCamera                                         | 1         | 2.04%   |
| Acer EasyCamera                                                | 1         | 2.04%   |
| Acer BisonCam,NB Pro                                           | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 77.78%  |
| LighTuning Technology | 2         | 22.22%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 33.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader  | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI             | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner        | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 70.09%  |
| 1     | 28        | 26.17%  |
| 2     | 4         | 3.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 14        | 42.42%  |
| Fingerprint reader       | 9         | 27.27%  |
| Graphics card            | 5         | 15.15%  |
| Communication controller | 2         | 6.06%   |
| Net/ethernet             | 1         | 3.03%   |
| Multimedia controller    | 1         | 3.03%   |
| Chipcard                 | 1         | 3.03%   |

