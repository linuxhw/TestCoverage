Linux in Greece - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Greece/Desktop/README.md) and [notebooks](/Location/Greece/Notebook/README.md).

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

Total: 1532

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d2903d25c5](https://linux-hardware.org/?probe=d2903d25c5) | Apr 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | Notebook    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [c6bf48bfb3](https://linux-hardware.org/?probe=c6bf48bfb3) | Apr 27, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | Notebook    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | Notebook    | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dddd6b6edd](https://linux-hardware.org/?probe=dddd6b6edd) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | 04PT3G A00                  | Desktop     | [a10754ebca](https://linux-hardware.org/?probe=a10754ebca) | Apr 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | Notebook    | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| HP            | G7000                       | Notebook    | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [761e954b86](https://linux-hardware.org/?probe=761e954b86) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [348af6c202](https://linux-hardware.org/?probe=348af6c202) | Apr 02, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| Sony          | VGN-AW11XU_Q                | Notebook    | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [61e5bd5c41](https://linux-hardware.org/?probe=61e5bd5c41) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [380efd9f08](https://linux-hardware.org/?probe=380efd9f08) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [1297813d45](https://linux-hardware.org/?probe=1297813d45) | Mar 27, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4fa05350b7](https://linux-hardware.org/?probe=4fa05350b7) | Mar 17, 2022 |
| Dell          | Latitude E7470              | Notebook    | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [623d2ec493](https://linux-hardware.org/?probe=623d2ec493) | Mar 15, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [44e9c813e9](https://linux-hardware.org/?probe=44e9c813e9) | Mar 14, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| HP            | 1850                        | Desktop     | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| MSI           | MS-7091                     | Desktop     | [6ff1d651e4](https://linux-hardware.org/?probe=6ff1d651e4) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c36fe6c067](https://linux-hardware.org/?probe=c36fe6c067) | Mar 10, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [2a7edc452e](https://linux-hardware.org/?probe=2a7edc452e) | Mar 09, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [f56996aab6](https://linux-hardware.org/?probe=f56996aab6) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| HP            | 3048h                       | Desktop     | [cb9a7b7f4f](https://linux-hardware.org/?probe=cb9a7b7f4f) | Mar 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cc5bac970](https://linux-hardware.org/?probe=3cc5bac970) | Mar 02, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [20d1ba1a89](https://linux-hardware.org/?probe=20d1ba1a89) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [2789dc5384](https://linux-hardware.org/?probe=2789dc5384) | Mar 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [3f6b2ab46e](https://linux-hardware.org/?probe=3f6b2ab46e) | Mar 01, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [d106079db9](https://linux-hardware.org/?probe=d106079db9) | Mar 01, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [eee862cee1](https://linux-hardware.org/?probe=eee862cee1) | Mar 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [7f43788673](https://linux-hardware.org/?probe=7f43788673) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | Notebook    | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Dell          | 0N185P A01                  | Desktop     | [996f9f7805](https://linux-hardware.org/?probe=996f9f7805) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | Notebook    | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [fc444df804](https://linux-hardware.org/?probe=fc444df804) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | Notebook    | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9e10ad29c3](https://linux-hardware.org/?probe=9e10ad29c3) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [c9d8bb9bd9](https://linux-hardware.org/?probe=c9d8bb9bd9) | Feb 16, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [87774dacdd](https://linux-hardware.org/?probe=87774dacdd) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3cf4dc7f97](https://linux-hardware.org/?probe=3cf4dc7f97) | Feb 15, 2022 |
| MSI           | MS-7176                     | Desktop     | [b54631ff57](https://linux-hardware.org/?probe=b54631ff57) | Feb 14, 2022 |
| e-shop.gr     | V113                        | Notebook    | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| e-shop.gr     | V113                        | Notebook    | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [57de891506](https://linux-hardware.org/?probe=57de891506) | Feb 12, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | Notebook    | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [d70247596b](https://linux-hardware.org/?probe=d70247596b) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| MSI           | MS-7176                     | Desktop     | [2e88c2ba3e](https://linux-hardware.org/?probe=2e88c2ba3e) | Jan 31, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [3dbf1d9544](https://linux-hardware.org/?probe=3dbf1d9544) | Jan 31, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | Notebook    | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | Notebook    | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| RuggedPC      | RuggedPadC86V               | Tablet      | [c9f76be971](https://linux-hardware.org/?probe=c9f76be971) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| VIA Techno... | VT8366-8233/5               | Desktop     | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [6a25ca99d2](https://linux-hardware.org/?probe=6a25ca99d2) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| HP            | 86F3 00100                  | All in one  | [6b9bc0d34d](https://linux-hardware.org/?probe=6b9bc0d34d) | Jan 24, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [07bd238c48](https://linux-hardware.org/?probe=07bd238c48) | Jan 24, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [571a7ec0b0](https://linux-hardware.org/?probe=571a7ec0b0) | Jan 24, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | 8434 11                     | Desktop     | [6bb20c8d64](https://linux-hardware.org/?probe=6bb20c8d64) | Jan 20, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [b105d56395](https://linux-hardware.org/?probe=b105d56395) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | NOK                         | Desktop     | [111a1caac8](https://linux-hardware.org/?probe=111a1caac8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [f4f3386726](https://linux-hardware.org/?probe=f4f3386726) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [ebef716d33](https://linux-hardware.org/?probe=ebef716d33) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [b9153e0c28](https://linux-hardware.org/?probe=b9153e0c28) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [597dfb85b7](https://linux-hardware.org/?probe=597dfb85b7) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0601abdfa6](https://linux-hardware.org/?probe=0601abdfa6) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [a96f2def6d](https://linux-hardware.org/?probe=a96f2def6d) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [910af5ce1a](https://linux-hardware.org/?probe=910af5ce1a) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [51d8172f5b](https://linux-hardware.org/?probe=51d8172f5b) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | Notebook    | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [8306c8cf0d](https://linux-hardware.org/?probe=8306c8cf0d) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32b2cea437](https://linux-hardware.org/?probe=32b2cea437) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| HP            | Notebook                    | Notebook    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | Notebook    | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7887040435](https://linux-hardware.org/?probe=7887040435) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| ECS           | G31T-M7                     | Desktop     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | Desktop     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | Compaq 6730s                | Notebook    | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [8e4a08a77a](https://linux-hardware.org/?probe=8e4a08a77a) | Dec 26, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [68ea35c97d](https://linux-hardware.org/?probe=68ea35c97d) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Gigabyte      | H170M-D3H DDR3-CF           | Desktop     | [537cb36279](https://linux-hardware.org/?probe=537cb36279) | Dec 25, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [8962cfd1c6](https://linux-hardware.org/?probe=8962cfd1c6) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | Desktop     | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| IBM           | 00D4062                     | Server      | [76a0ebbfc4](https://linux-hardware.org/?probe=76a0ebbfc4) | Dec 17, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [64a10ac62b](https://linux-hardware.org/?probe=64a10ac62b) | Dec 15, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [495d348f1e](https://linux-hardware.org/?probe=495d348f1e) | Dec 15, 2021 |
| HP            | G62                         | Notebook    | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [851401aeea](https://linux-hardware.org/?probe=851401aeea) | Dec 13, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [b86c41a0a9](https://linux-hardware.org/?probe=b86c41a0a9) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [20984b7808](https://linux-hardware.org/?probe=20984b7808) | Dec 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac3e0f0271](https://linux-hardware.org/?probe=ac3e0f0271) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1876329ada](https://linux-hardware.org/?probe=1876329ada) | Dec 10, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c97b5a008f](https://linux-hardware.org/?probe=c97b5a008f) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [11f31cc288](https://linux-hardware.org/?probe=11f31cc288) | Dec 08, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [93f59158b6](https://linux-hardware.org/?probe=93f59158b6) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Gateway       | DT55                        | Desktop     | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [998b2258eb](https://linux-hardware.org/?probe=998b2258eb) | Dec 05, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | Notebook    | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | Notebook    | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | Notebook    | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Dell          | 0WK833                      | Desktop     | [59fed7d754](https://linux-hardware.org/?probe=59fed7d754) | Nov 30, 2021 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8df2d4c785](https://linux-hardware.org/?probe=8df2d4c785) | Nov 29, 2021 |
| HP            | Pavilion g7                 | Notebook    | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | Notebook    | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [6e37f9cd8a](https://linux-hardware.org/?probe=6e37f9cd8a) | Nov 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [999b38ba1f](https://linux-hardware.org/?probe=999b38ba1f) | Nov 28, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| Toshiba       | Satellite C855-27U          | Notebook    | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b6396cac2d](https://linux-hardware.org/?probe=b6396cac2d) | Nov 25, 2021 |
| Sony          | SVF1521A1EW                 | Notebook    | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c14d4d6ad](https://linux-hardware.org/?probe=2c14d4d6ad) | Nov 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [000f6b6f44](https://linux-hardware.org/?probe=000f6b6f44) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| HP            | 304Bh                       | Desktop     | [d6f490c0ea](https://linux-hardware.org/?probe=d6f490c0ea) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [b3319a217d](https://linux-hardware.org/?probe=b3319a217d) | Nov 17, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| Dell          | 0Y2K8N A00                  | Desktop     | [db79ad16d3](https://linux-hardware.org/?probe=db79ad16d3) | Nov 16, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [770408fd3d](https://linux-hardware.org/?probe=770408fd3d) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cf9966c22](https://linux-hardware.org/?probe=2cf9966c22) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [7a3d3a2f06](https://linux-hardware.org/?probe=7a3d3a2f06) | Nov 12, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | Desktop     | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [476167fea8](https://linux-hardware.org/?probe=476167fea8) | Nov 10, 2021 |
| HP            | 339A                        | Desktop     | [702ccff1e4](https://linux-hardware.org/?probe=702ccff1e4) | Nov 09, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | Notebook    | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | Notebook    | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| Sony          | SVE1513Y1ESI                | Notebook    | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [44acfe85a5](https://linux-hardware.org/?probe=44acfe85a5) | Oct 31, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | Notebook    | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | Notebook    | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | Notebook    | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [02cc756dd4](https://linux-hardware.org/?probe=02cc756dd4) | Oct 26, 2021 |
| ASUSTek       | TP202NAS                    | Convertible | [3498f0a5df](https://linux-hardware.org/?probe=3498f0a5df) | Oct 26, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | Notebook    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | Notebook    | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| Lenovo        | ThinkCentre M71e 3167A46    | Desktop     | [afc98aba09](https://linux-hardware.org/?probe=afc98aba09) | Oct 20, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c76a2534a0](https://linux-hardware.org/?probe=c76a2534a0) | Oct 19, 2021 |
| HP            | Notebook                    | Notebook    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fa1ceccee5](https://linux-hardware.org/?probe=fa1ceccee5) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| HP            | 1496                        | Desktop     | [f438fdb757](https://linux-hardware.org/?probe=f438fdb757) | Oct 17, 2021 |
| Dell          | Precision M4800             | Notebook    | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| MSI           | H110I PRO                   | Desktop     | [0aeac6b99e](https://linux-hardware.org/?probe=0aeac6b99e) | Oct 16, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [95f8cd653d](https://linux-hardware.org/?probe=95f8cd653d) | Oct 12, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| HP            | 1496                        | Desktop     | [f6ad468908](https://linux-hardware.org/?probe=f6ad468908) | Oct 10, 2021 |
| ARIMA         | W651UI                      | Notebook    | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | H110I PRO                   | Desktop     | [33e1bf9b6c](https://linux-hardware.org/?probe=33e1bf9b6c) | Oct 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [13ee121adc](https://linux-hardware.org/?probe=13ee121adc) | Oct 07, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [fd3b108340](https://linux-hardware.org/?probe=fd3b108340) | Oct 07, 2021 |
| MSI           | Alpha 17 A4DEK              | Notebook    | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| HP            | 1496                        | Desktop     | [3f369a5dd6](https://linux-hardware.org/?probe=3f369a5dd6) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8bf300aa62](https://linux-hardware.org/?probe=8bf300aa62) | Oct 05, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [c627fc3c07](https://linux-hardware.org/?probe=c627fc3c07) | Oct 04, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [d68bf2f2b0](https://linux-hardware.org/?probe=d68bf2f2b0) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | Notebook    | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [68b6365968](https://linux-hardware.org/?probe=68b6365968) | Sep 28, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| HP            | Pavilion g6                 | Notebook    | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [bfa3ee0eda](https://linux-hardware.org/?probe=bfa3ee0eda) | Sep 22, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [927dfa2266](https://linux-hardware.org/?probe=927dfa2266) | Sep 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [4718ed26ca](https://linux-hardware.org/?probe=4718ed26ca) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | Notebook    | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [862999e242](https://linux-hardware.org/?probe=862999e242) | Aug 27, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [877e0e98a4](https://linux-hardware.org/?probe=877e0e98a4) | Aug 27, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [540c64bf79](https://linux-hardware.org/?probe=540c64bf79) | Aug 26, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [dee9503ed0](https://linux-hardware.org/?probe=dee9503ed0) | Aug 24, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [dcf6e0d950](https://linux-hardware.org/?probe=dcf6e0d950) | Aug 22, 2021 |
| Sony          | SVT1122B2EW                 | Notebook    | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [05298cb71d](https://linux-hardware.org/?probe=05298cb71d) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [57575daae2](https://linux-hardware.org/?probe=57575daae2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d436538e39](https://linux-hardware.org/?probe=d436538e39) | Aug 13, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | Notebook    | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b5f6eb1dc0](https://linux-hardware.org/?probe=b5f6eb1dc0) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [63fdc16b6d](https://linux-hardware.org/?probe=63fdc16b6d) | Aug 09, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | Notebook    | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [08cf0272da](https://linux-hardware.org/?probe=08cf0272da) | Aug 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | Notebook    | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [a9d13b1ccb](https://linux-hardware.org/?probe=a9d13b1ccb) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | Notebook    | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | Notebook    | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [494cd954e9](https://linux-hardware.org/?probe=494cd954e9) | Jul 22, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [190d4540e9](https://linux-hardware.org/?probe=190d4540e9) | Jul 20, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [aed568d94c](https://linux-hardware.org/?probe=aed568d94c) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | Notebook    | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | Notebook    | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [df5a9e402e](https://linux-hardware.org/?probe=df5a9e402e) | Jul 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [1777f4b534](https://linux-hardware.org/?probe=1777f4b534) | Jul 07, 2021 |
| Dell          | Latitude D531               | Notebook    | [5a671e0dc0](https://linux-hardware.org/?probe=5a671e0dc0) | Jul 06, 2021 |
| Dell          | Latitude D531               | Notebook    | [bc3e80d306](https://linux-hardware.org/?probe=bc3e80d306) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| Gigabyte      | P35-DS3                     | Desktop     | [1756b98ff7](https://linux-hardware.org/?probe=1756b98ff7) | Jul 04, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f57bd1d1d8](https://linux-hardware.org/?probe=f57bd1d1d8) | Jul 04, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3fcdda6371](https://linux-hardware.org/?probe=3fcdda6371) | Jul 04, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [69f8258d54](https://linux-hardware.org/?probe=69f8258d54) | Jul 03, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [16d31cc8f1](https://linux-hardware.org/?probe=16d31cc8f1) | Jul 02, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0812ba2f1d](https://linux-hardware.org/?probe=0812ba2f1d) | Jul 01, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ed31fd442f](https://linux-hardware.org/?probe=ed31fd442f) | Jul 01, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [479f6c752d](https://linux-hardware.org/?probe=479f6c752d) | Jul 01, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [e72a35c178](https://linux-hardware.org/?probe=e72a35c178) | Jun 26, 2021 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [03f12de5a1](https://linux-hardware.org/?probe=03f12de5a1) | Jun 17, 2021 |
| HP            | 339A                        | Desktop     | [88af8ec05f](https://linux-hardware.org/?probe=88af8ec05f) | Jun 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7563cf4f19](https://linux-hardware.org/?probe=7563cf4f19) | Jun 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| Dell          | Latitude 7400               | Notebook    | [c58ebb3bf8](https://linux-hardware.org/?probe=c58ebb3bf8) | Jun 15, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7a4b730903](https://linux-hardware.org/?probe=7a4b730903) | Jun 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [2989252679](https://linux-hardware.org/?probe=2989252679) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [128de02660](https://linux-hardware.org/?probe=128de02660) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [e8a90de6cd](https://linux-hardware.org/?probe=e8a90de6cd) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [88362a4659](https://linux-hardware.org/?probe=88362a4659) | Jun 10, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [d87f3ea107](https://linux-hardware.org/?probe=d87f3ea107) | Jun 10, 2021 |
| HP            | Compaq 6910p                | Notebook    | [5b4d256824](https://linux-hardware.org/?probe=5b4d256824) | Jun 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [356b7fd3c6](https://linux-hardware.org/?probe=356b7fd3c6) | Jun 09, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [831ff65864](https://linux-hardware.org/?probe=831ff65864) | Jun 07, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e7b9652dbd](https://linux-hardware.org/?probe=e7b9652dbd) | Jun 07, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [33dcfeee7b](https://linux-hardware.org/?probe=33dcfeee7b) | Jun 07, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| HP            | 304Bh                       | Desktop     | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [ef4e2ca66f](https://linux-hardware.org/?probe=ef4e2ca66f) | Jun 03, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2ff583b918](https://linux-hardware.org/?probe=2ff583b918) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [6018f18645](https://linux-hardware.org/?probe=6018f18645) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [03b8f35b44](https://linux-hardware.org/?probe=03b8f35b44) | Jun 02, 2021 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [5c26b20836](https://linux-hardware.org/?probe=5c26b20836) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [bd16a61719](https://linux-hardware.org/?probe=bd16a61719) | May 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [da0e32387a](https://linux-hardware.org/?probe=da0e32387a) | May 31, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [9a3529c8ae](https://linux-hardware.org/?probe=9a3529c8ae) | May 29, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [5d94a011e0](https://linux-hardware.org/?probe=5d94a011e0) | May 26, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e5a1aba629](https://linux-hardware.org/?probe=e5a1aba629) | May 26, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [b9c73baf1d](https://linux-hardware.org/?probe=b9c73baf1d) | May 25, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dd9596a6b0](https://linux-hardware.org/?probe=dd9596a6b0) | May 25, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [79e354be47](https://linux-hardware.org/?probe=79e354be47) | May 24, 2021 |
| ASUSTek       | A8V Deluxe                  | Desktop     | [e739f2f0ba](https://linux-hardware.org/?probe=e739f2f0ba) | May 24, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [10cf947d23](https://linux-hardware.org/?probe=10cf947d23) | May 24, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| HP            | G62                         | Notebook    | [72f8505e51](https://linux-hardware.org/?probe=72f8505e51) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | Notebook    | [ead418c0a3](https://linux-hardware.org/?probe=ead418c0a3) | May 17, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | Notebook    | [8312f6899d](https://linux-hardware.org/?probe=8312f6899d) | May 17, 2021 |
| HP            | 84EE 1100                   | All in one  | [df07e6aab4](https://linux-hardware.org/?probe=df07e6aab4) | May 17, 2021 |
| Dell          | Precision 3551              | Notebook    | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | Notebook    | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [8f3fc4eeda](https://linux-hardware.org/?probe=8f3fc4eeda) | May 15, 2021 |
| HP            | Unknown                     | Notebook    | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [3038e4027b](https://linux-hardware.org/?probe=3038e4027b) | May 14, 2021 |
| HP            | Compaq 6735s                | Notebook    | [b3d6b7770a](https://linux-hardware.org/?probe=b3d6b7770a) | May 13, 2021 |
| HP            | Compaq 6735s                | Notebook    | [cb89b8188f](https://linux-hardware.org/?probe=cb89b8188f) | May 13, 2021 |
| HP            | Unknown                     | Notebook    | [d11a5ff11b](https://linux-hardware.org/?probe=d11a5ff11b) | May 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e6848fb30e](https://linux-hardware.org/?probe=e6848fb30e) | May 13, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [342074c2e1](https://linux-hardware.org/?probe=342074c2e1) | May 13, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [54aedd8090](https://linux-hardware.org/?probe=54aedd8090) | May 13, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [643481b28f](https://linux-hardware.org/?probe=643481b28f) | May 10, 2021 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [b1375145c3](https://linux-hardware.org/?probe=b1375145c3) | May 10, 2021 |
| MSI           | GF75 Thin 10SCSR            | Notebook    | [d88c558cda](https://linux-hardware.org/?probe=d88c558cda) | May 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7e483f822d](https://linux-hardware.org/?probe=7e483f822d) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| HP            | Unknown                     | Notebook    | [923ee16061](https://linux-hardware.org/?probe=923ee16061) | May 08, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [993f3384ed](https://linux-hardware.org/?probe=993f3384ed) | May 08, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Sony          | SVE1513R1EB                 | Notebook    | [e87dd3a1c3](https://linux-hardware.org/?probe=e87dd3a1c3) | May 07, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [256c66503a](https://linux-hardware.org/?probe=256c66503a) | May 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [f483fd5a3b](https://linux-hardware.org/?probe=f483fd5a3b) | May 04, 2021 |
| HP            | Compaq 6735s                | Notebook    | [f50dd52975](https://linux-hardware.org/?probe=f50dd52975) | May 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [6f9d6686f3](https://linux-hardware.org/?probe=6f9d6686f3) | May 03, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| HP            | Unknown                     | Notebook    | [3b8a91fb03](https://linux-hardware.org/?probe=3b8a91fb03) | May 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [79a8f7d7d8](https://linux-hardware.org/?probe=79a8f7d7d8) | May 03, 2021 |
| QDI           | P4I865A                     | Desktop     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ad00f41e81](https://linux-hardware.org/?probe=ad00f41e81) | May 02, 2021 |
| Toshiba       | NB100                       | Notebook    | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [5feda7dcc9](https://linux-hardware.org/?probe=5feda7dcc9) | May 02, 2021 |
| HP            | G62                         | Notebook    | [327a8383cf](https://linux-hardware.org/?probe=327a8383cf) | Apr 30, 2021 |
| HP            | G62                         | Notebook    | [d2eaf7d20f](https://linux-hardware.org/?probe=d2eaf7d20f) | Apr 30, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7dbdf36326](https://linux-hardware.org/?probe=7dbdf36326) | Apr 30, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [abc02a4329](https://linux-hardware.org/?probe=abc02a4329) | Apr 30, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| MSI           | MS-7235                     | Desktop     | [3d8c008ca3](https://linux-hardware.org/?probe=3d8c008ca3) | Apr 27, 2021 |
| Acer          | AO756                       | Notebook    | [f398615a01](https://linux-hardware.org/?probe=f398615a01) | Apr 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | Notebook    | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| HP            | 1494                        | Desktop     | [775b59a599](https://linux-hardware.org/?probe=775b59a599) | Apr 20, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [4c7c9824db](https://linux-hardware.org/?probe=4c7c9824db) | Apr 19, 2021 |
| Dell          | G3 3590                     | Notebook    | [5fe47837ac](https://linux-hardware.org/?probe=5fe47837ac) | Apr 19, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0a7e8b0fab](https://linux-hardware.org/?probe=0a7e8b0fab) | Apr 19, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [7c519e9719](https://linux-hardware.org/?probe=7c519e9719) | Apr 17, 2021 |
| Google        | Coral                       | Notebook    | [d0fef96a1b](https://linux-hardware.org/?probe=d0fef96a1b) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [8695142550](https://linux-hardware.org/?probe=8695142550) | Apr 13, 2021 |
| Acer          | Predator G3-571             | Notebook    | [2db50fb736](https://linux-hardware.org/?probe=2db50fb736) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [fd8afa6f02](https://linux-hardware.org/?probe=fd8afa6f02) | Apr 11, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [166de8c643](https://linux-hardware.org/?probe=166de8c643) | Apr 11, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd3c6d01f7](https://linux-hardware.org/?probe=fd3c6d01f7) | Apr 11, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [3246784665](https://linux-hardware.org/?probe=3246784665) | Apr 09, 2021 |
| Gigabyte      | P41T-D3                     | Desktop     | [2f9a494265](https://linux-hardware.org/?probe=2f9a494265) | Apr 09, 2021 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [743700573c](https://linux-hardware.org/?probe=743700573c) | Apr 04, 2021 |
| MSI           | GF75 Thin 10SCSR            | Notebook    | [4c5b57df0f](https://linux-hardware.org/?probe=4c5b57df0f) | Apr 03, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| Lenovo        | Board                       | Desktop     | [6e0ad0f342](https://linux-hardware.org/?probe=6e0ad0f342) | Mar 31, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [a6ad1251de](https://linux-hardware.org/?probe=a6ad1251de) | Mar 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [d11d1f9916](https://linux-hardware.org/?probe=d11d1f9916) | Mar 28, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [7c4649ce56](https://linux-hardware.org/?probe=7c4649ce56) | Mar 26, 2021 |
| Quest         | GTN1408                     | Notebook    | [e0a15c69a8](https://linux-hardware.org/?probe=e0a15c69a8) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [5bedab76df](https://linux-hardware.org/?probe=5bedab76df) | Mar 25, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [4b75d2439e](https://linux-hardware.org/?probe=4b75d2439e) | Mar 25, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [5916c313e7](https://linux-hardware.org/?probe=5916c313e7) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [aab9ef0b36](https://linux-hardware.org/?probe=aab9ef0b36) | Mar 24, 2021 |
| Dell          | Latitude D530               | Notebook    | [bd67bc09cd](https://linux-hardware.org/?probe=bd67bc09cd) | Mar 22, 2021 |
| HP            | 0984h                       | Desktop     | [20a29fe8b0](https://linux-hardware.org/?probe=20a29fe8b0) | Mar 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [67d33fc829](https://linux-hardware.org/?probe=67d33fc829) | Mar 19, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f579ddfcb8](https://linux-hardware.org/?probe=f579ddfcb8) | Mar 17, 2021 |
| HP            | 18E4                        | Desktop     | [b5eec7a501](https://linux-hardware.org/?probe=b5eec7a501) | Mar 17, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [6378d46f22](https://linux-hardware.org/?probe=6378d46f22) | Mar 17, 2021 |
| ASUSTek       | N552VX                      | Notebook    | [79120776d5](https://linux-hardware.org/?probe=79120776d5) | Mar 14, 2021 |
| ASUSTek       | N552VX                      | Notebook    | [2bb101d8ca](https://linux-hardware.org/?probe=2bb101d8ca) | Mar 14, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [5843e7b038](https://linux-hardware.org/?probe=5843e7b038) | Mar 14, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [fc76eddc08](https://linux-hardware.org/?probe=fc76eddc08) | Mar 14, 2021 |
| HP            | G62                         | Notebook    | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [9ff279ae01](https://linux-hardware.org/?probe=9ff279ae01) | Mar 11, 2021 |
| Teclast       | F15                         | Notebook    | [2a9e97f18c](https://linux-hardware.org/?probe=2a9e97f18c) | Mar 10, 2021 |
| HP            | Notebook                    | Notebook    | [26fdd1f108](https://linux-hardware.org/?probe=26fdd1f108) | Mar 09, 2021 |
| Gigabyte      | B75-D3V                     | Desktop     | [f4b8176eb4](https://linux-hardware.org/?probe=f4b8176eb4) | Mar 09, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [7f408871f2](https://linux-hardware.org/?probe=7f408871f2) | Mar 09, 2021 |
| Dell          | Latitude E7250              | Notebook    | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [78933b8238](https://linux-hardware.org/?probe=78933b8238) | Mar 07, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [693347465d](https://linux-hardware.org/?probe=693347465d) | Mar 06, 2021 |
| Info Quest... | GTN1408                     | Notebook    | [571eedb776](https://linux-hardware.org/?probe=571eedb776) | Mar 03, 2021 |
| Toshiba       | NB100                       | Notebook    | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| MSI           | H81M PRO-VD                 | Desktop     | [efa82d3df7](https://linux-hardware.org/?probe=efa82d3df7) | Mar 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ebe53e8b99](https://linux-hardware.org/?probe=ebe53e8b99) | Feb 28, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [e2ede83088](https://linux-hardware.org/?probe=e2ede83088) | Feb 27, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [951acd6af9](https://linux-hardware.org/?probe=951acd6af9) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | Notebook    | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Gigabyte      | 8I915PL-G                   | Desktop     | [e9ed9c7fdf](https://linux-hardware.org/?probe=e9ed9c7fdf) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [cada48fb79](https://linux-hardware.org/?probe=cada48fb79) | Feb 27, 2021 |
| ASUSTek       | UX305CA                     | Notebook    | [65b536ca2f](https://linux-hardware.org/?probe=65b536ca2f) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c501aa1f72](https://linux-hardware.org/?probe=c501aa1f72) | Feb 26, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [c0301ac11d](https://linux-hardware.org/?probe=c0301ac11d) | Feb 26, 2021 |
| ASUSTek       | P6T                         | Desktop     | [c2d58a2c68](https://linux-hardware.org/?probe=c2d58a2c68) | Feb 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| MSI           | MS-7176                     | Desktop     | [f04765b1b9](https://linux-hardware.org/?probe=f04765b1b9) | Feb 24, 2021 |
| MSI           | MS-7176                     | Desktop     | [760a593d35](https://linux-hardware.org/?probe=760a593d35) | Feb 24, 2021 |
| Dell          | Latitude E6400              | Notebook    | [256426a815](https://linux-hardware.org/?probe=256426a815) | Feb 22, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [ec035af0d0](https://linux-hardware.org/?probe=ec035af0d0) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [563f422327](https://linux-hardware.org/?probe=563f422327) | Feb 21, 2021 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [74869ab078](https://linux-hardware.org/?probe=74869ab078) | Feb 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [38e7b43029](https://linux-hardware.org/?probe=38e7b43029) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aac0643552](https://linux-hardware.org/?probe=aac0643552) | Feb 21, 2021 |
| HP            | Pavilion AB7                | Notebook    | [410cf90e15](https://linux-hardware.org/?probe=410cf90e15) | Feb 20, 2021 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [9b2fc1e55f](https://linux-hardware.org/?probe=9b2fc1e55f) | Feb 19, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [492632cd6f](https://linux-hardware.org/?probe=492632cd6f) | Feb 19, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [2dae363129](https://linux-hardware.org/?probe=2dae363129) | Feb 19, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| ABIT          | FP-IN9 SLI                  | Desktop     | [91f5f66c7c](https://linux-hardware.org/?probe=91f5f66c7c) | Feb 17, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9e831f773a](https://linux-hardware.org/?probe=9e831f773a) | Feb 17, 2021 |
| Dell          | Studio 1557                 | Notebook    | [bf361a7ed3](https://linux-hardware.org/?probe=bf361a7ed3) | Feb 16, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [209ecb3837](https://linux-hardware.org/?probe=209ecb3837) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6c898a20f1](https://linux-hardware.org/?probe=6c898a20f1) | Feb 15, 2021 |
| Dell          | Precision M6400             | Notebook    | [2bd1a24330](https://linux-hardware.org/?probe=2bd1a24330) | Feb 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [3994b32fbb](https://linux-hardware.org/?probe=3994b32fbb) | Feb 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e688396a21](https://linux-hardware.org/?probe=e688396a21) | Feb 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [696129adca](https://linux-hardware.org/?probe=696129adca) | Feb 14, 2021 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [35291823d8](https://linux-hardware.org/?probe=35291823d8) | Feb 14, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [de94ccbf1a](https://linux-hardware.org/?probe=de94ccbf1a) | Feb 14, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [71b1c108c4](https://linux-hardware.org/?probe=71b1c108c4) | Feb 14, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [2dd140ff3e](https://linux-hardware.org/?probe=2dd140ff3e) | Feb 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [dfc223f07c](https://linux-hardware.org/?probe=dfc223f07c) | Feb 14, 2021 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e0ef54344d](https://linux-hardware.org/?probe=e0ef54344d) | Feb 14, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [3e6fa8f362](https://linux-hardware.org/?probe=3e6fa8f362) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [a9bc15b309](https://linux-hardware.org/?probe=a9bc15b309) | Feb 13, 2021 |
| Teclast       | F15                         | Notebook    | [1c7d49b0b0](https://linux-hardware.org/?probe=1c7d49b0b0) | Feb 13, 2021 |
| ASUSTek       | P7P55D-E DELUXE             | Desktop     | [b0857a93ff](https://linux-hardware.org/?probe=b0857a93ff) | Feb 13, 2021 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [0ebedefc78](https://linux-hardware.org/?probe=0ebedefc78) | Feb 13, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [654141e59d](https://linux-hardware.org/?probe=654141e59d) | Feb 13, 2021 |
| HP            | G62                         | Notebook    | [efd6ef9818](https://linux-hardware.org/?probe=efd6ef9818) | Feb 12, 2021 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [68c7aa1fa1](https://linux-hardware.org/?probe=68c7aa1fa1) | Feb 09, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [fb1dbcb32a](https://linux-hardware.org/?probe=fb1dbcb32a) | Feb 09, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [2ed0ae9569](https://linux-hardware.org/?probe=2ed0ae9569) | Feb 09, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [0a56b88fc8](https://linux-hardware.org/?probe=0a56b88fc8) | Feb 08, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [6b7db83192](https://linux-hardware.org/?probe=6b7db83192) | Feb 06, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [0022cd41e5](https://linux-hardware.org/?probe=0022cd41e5) | Feb 06, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [543b5a7398](https://linux-hardware.org/?probe=543b5a7398) | Feb 06, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [fc8c462cc7](https://linux-hardware.org/?probe=fc8c462cc7) | Feb 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [a95bc37d1f](https://linux-hardware.org/?probe=a95bc37d1f) | Feb 03, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| HP            | G62                         | Notebook    | [273bf04457](https://linux-hardware.org/?probe=273bf04457) | Feb 03, 2021 |
| HP            | G62                         | Notebook    | [a74ecdb45c](https://linux-hardware.org/?probe=a74ecdb45c) | Feb 03, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [fff0e370f8](https://linux-hardware.org/?probe=fff0e370f8) | Feb 01, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [4acc63b6b4](https://linux-hardware.org/?probe=4acc63b6b4) | Feb 01, 2021 |
| HP            | 1494                        | Desktop     | [d3fbad0c50](https://linux-hardware.org/?probe=d3fbad0c50) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| Foxconn       | P43A01                      | Desktop     | [6ebcadfb23](https://linux-hardware.org/?probe=6ebcadfb23) | Jan 31, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| Acer          | Aspire A517-51G             | Notebook    | [7b7f7244e6](https://linux-hardware.org/?probe=7b7f7244e6) | Jan 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [c53a37fb5a](https://linux-hardware.org/?probe=c53a37fb5a) | Jan 28, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [32605971fb](https://linux-hardware.org/?probe=32605971fb) | Jan 28, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [1ac6133a40](https://linux-hardware.org/?probe=1ac6133a40) | Jan 28, 2021 |
| Dell          | 06FW8P A01                  | Desktop     | [392c18a8d2](https://linux-hardware.org/?probe=392c18a8d2) | Jan 28, 2021 |
| HP            | Unknown                     | Notebook    | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [ce1a55614c](https://linux-hardware.org/?probe=ce1a55614c) | Jan 28, 2021 |
| HP            | Unknown                     | Notebook    | [b7892094b3](https://linux-hardware.org/?probe=b7892094b3) | Jan 27, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a85f6c4759](https://linux-hardware.org/?probe=a85f6c4759) | Jan 27, 2021 |
| IBM           | ThinkPad T41 2373271        | Notebook    | [71daf2c5b4](https://linux-hardware.org/?probe=71daf2c5b4) | Jan 26, 2021 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [a54f523eae](https://linux-hardware.org/?probe=a54f523eae) | Jan 26, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [7bcce8c99f](https://linux-hardware.org/?probe=7bcce8c99f) | Jan 22, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [ef38db344e](https://linux-hardware.org/?probe=ef38db344e) | Jan 20, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [0c61498134](https://linux-hardware.org/?probe=0c61498134) | Jan 19, 2021 |
| HP            | Unknown                     | Notebook    | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [6e7fe8b488](https://linux-hardware.org/?probe=6e7fe8b488) | Jan 18, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [df23913572](https://linux-hardware.org/?probe=df23913572) | Jan 18, 2021 |
| HP            | 550                         | Notebook    | [384b3f65ed](https://linux-hardware.org/?probe=384b3f65ed) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M55 880894G     | Desktop     | [3b766a7c24](https://linux-hardware.org/?probe=3b766a7c24) | Jan 17, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [c7045484b1](https://linux-hardware.org/?probe=c7045484b1) | Jan 16, 2021 |
| Sony          | VPCS11X9E                   | Notebook    | [279fb61afa](https://linux-hardware.org/?probe=279fb61afa) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ca2c414b09](https://linux-hardware.org/?probe=ca2c414b09) | Jan 13, 2021 |
| HP            | 3648h                       | Desktop     | [21e48412d9](https://linux-hardware.org/?probe=21e48412d9) | Jan 12, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [a137e1b57f](https://linux-hardware.org/?probe=a137e1b57f) | Jan 11, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [637d6c6ea6](https://linux-hardware.org/?probe=637d6c6ea6) | Jan 11, 2021 |
| Medion        | P6612                       | Notebook    | [5e83afdaae](https://linux-hardware.org/?probe=5e83afdaae) | Jan 11, 2021 |
| Dell          | G3 3579                     | Notebook    | [d48d0d6f85](https://linux-hardware.org/?probe=d48d0d6f85) | Jan 11, 2021 |
| HP            | 550                         | Notebook    | [10da4607b5](https://linux-hardware.org/?probe=10da4607b5) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | Notebook    | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9a71b52057](https://linux-hardware.org/?probe=9a71b52057) | Jan 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [6ba134cda2](https://linux-hardware.org/?probe=6ba134cda2) | Jan 11, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6164e26717](https://linux-hardware.org/?probe=6164e26717) | Jan 09, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a2113ca536](https://linux-hardware.org/?probe=a2113ca536) | Jan 08, 2021 |
| ASRock        | A320M Pro4                  | Desktop     | [df605a19b9](https://linux-hardware.org/?probe=df605a19b9) | Jan 07, 2021 |
| Dell          | Precision 3551              | Notebook    | [1f3d433e7b](https://linux-hardware.org/?probe=1f3d433e7b) | Jan 07, 2021 |
| Dell          | Precision 3551              | Notebook    | [b9869afb9a](https://linux-hardware.org/?probe=b9869afb9a) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [2040f17b4e](https://linux-hardware.org/?probe=2040f17b4e) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [7758717ed0](https://linux-hardware.org/?probe=7758717ed0) | Jan 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [394c90d235](https://linux-hardware.org/?probe=394c90d235) | Jan 06, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [7e9042951e](https://linux-hardware.org/?probe=7e9042951e) | Jan 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [d6f76d5ca0](https://linux-hardware.org/?probe=d6f76d5ca0) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [45519ff99d](https://linux-hardware.org/?probe=45519ff99d) | Jan 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [8708f0aa1a](https://linux-hardware.org/?probe=8708f0aa1a) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [6f3605f8a7](https://linux-hardware.org/?probe=6f3605f8a7) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [5939021d4c](https://linux-hardware.org/?probe=5939021d4c) | Jan 03, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [010507185c](https://linux-hardware.org/?probe=010507185c) | Jan 03, 2021 |
| HP            | G62                         | Notebook    | [26fedb2989](https://linux-hardware.org/?probe=26fedb2989) | Jan 03, 2021 |
| Sony          | VGN-CR11S_W                 | Notebook    | [e7b02a15dc](https://linux-hardware.org/?probe=e7b02a15dc) | Dec 30, 2020 |
| Sony          | VGN-CR11S_W                 | Notebook    | [3bbbfe0bd8](https://linux-hardware.org/?probe=3bbbfe0bd8) | Dec 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d8fb43bcba](https://linux-hardware.org/?probe=d8fb43bcba) | Dec 29, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [33e1b7b962](https://linux-hardware.org/?probe=33e1b7b962) | Dec 28, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [7463092751](https://linux-hardware.org/?probe=7463092751) | Dec 28, 2020 |
| ASRock        | J3455B-ITX                  | Desktop     | [188b19422f](https://linux-hardware.org/?probe=188b19422f) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | Notebook    | [502b2847a6](https://linux-hardware.org/?probe=502b2847a6) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | Notebook    | [29cadd906c](https://linux-hardware.org/?probe=29cadd906c) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [4bed00686e](https://linux-hardware.org/?probe=4bed00686e) | Dec 27, 2020 |
| Lenovo        | 3000 G530 444624G           | Notebook    | [34e6d98329](https://linux-hardware.org/?probe=34e6d98329) | Dec 27, 2020 |
| Dell          | 0WR7PY A03                  | Desktop     | [e9d1c14615](https://linux-hardware.org/?probe=e9d1c14615) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | Notebook    | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| HP            | Pavilion dv7                | Notebook    | [cc13d41ddd](https://linux-hardware.org/?probe=cc13d41ddd) | Dec 25, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [2974690eda](https://linux-hardware.org/?probe=2974690eda) | Dec 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| Dell          | G3 3590                     | Notebook    | [aaea8a972b](https://linux-hardware.org/?probe=aaea8a972b) | Dec 23, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [e530bd21e8](https://linux-hardware.org/?probe=e530bd21e8) | Dec 23, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [fe62a9556e](https://linux-hardware.org/?probe=fe62a9556e) | Dec 21, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [08f4092908](https://linux-hardware.org/?probe=08f4092908) | Dec 21, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5e08a85ebc](https://linux-hardware.org/?probe=5e08a85ebc) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [508111c39d](https://linux-hardware.org/?probe=508111c39d) | Dec 20, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [71036e26bf](https://linux-hardware.org/?probe=71036e26bf) | Dec 19, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [c58e872c12](https://linux-hardware.org/?probe=c58e872c12) | Dec 19, 2020 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [faacb1a39b](https://linux-hardware.org/?probe=faacb1a39b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X220 4291W3B       | Notebook    | [0cb7ed54d1](https://linux-hardware.org/?probe=0cb7ed54d1) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | Notebook    | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | Notebook    | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Toshiba       | NB100                       | Notebook    | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Dell          | Latitude D520               | Notebook    | [7f5d3e9a40](https://linux-hardware.org/?probe=7f5d3e9a40) | Dec 19, 2020 |
| Lenovo        | 3000 G530 444624G           | Notebook    | [fb187878c5](https://linux-hardware.org/?probe=fb187878c5) | Dec 16, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [6fcb38f3dc](https://linux-hardware.org/?probe=6fcb38f3dc) | Dec 15, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [d8723f48ef](https://linux-hardware.org/?probe=d8723f48ef) | Dec 15, 2020 |
| Sony          | VPCCB2S1E                   | Notebook    | [dadaeb0257](https://linux-hardware.org/?probe=dadaeb0257) | Dec 14, 2020 |
| Sony          | VPCCB2S1E                   | Notebook    | [b08942a95c](https://linux-hardware.org/?probe=b08942a95c) | Dec 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [de42fe0cb3](https://linux-hardware.org/?probe=de42fe0cb3) | Dec 14, 2020 |
| ECS           | GF7050VT-M5                 | Desktop     | [c29ca24015](https://linux-hardware.org/?probe=c29ca24015) | Dec 12, 2020 |
| ECS           | GF7050VT-M5                 | Desktop     | [657f63e3cb](https://linux-hardware.org/?probe=657f63e3cb) | Dec 12, 2020 |
| Sony          | VGN-CR11S_W                 | Notebook    | [96a49970af](https://linux-hardware.org/?probe=96a49970af) | Dec 11, 2020 |
| Lenovo        | G50-80 80L0                 | Notebook    | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| ASUSTek       | M4N78 PRO                   | Desktop     | [f25cf52f68](https://linux-hardware.org/?probe=f25cf52f68) | Dec 11, 2020 |
| Sony          | VGN-CR11S_W                 | Notebook    | [9f07e6181c](https://linux-hardware.org/?probe=9f07e6181c) | Dec 10, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [5866279b5d](https://linux-hardware.org/?probe=5866279b5d) | Dec 10, 2020 |
| HP            | OMEN by HP Laptop           | Notebook    | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [763ee2bb89](https://linux-hardware.org/?probe=763ee2bb89) | Dec 09, 2020 |
| Gigabyte      | 8IPE1000                    | Desktop     | [af54151e80](https://linux-hardware.org/?probe=af54151e80) | Dec 09, 2020 |
| HP            | 158B                        | Desktop     | [3a87a2e567](https://linux-hardware.org/?probe=3a87a2e567) | Dec 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7becb585e](https://linux-hardware.org/?probe=b7becb585e) | Dec 08, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [59d2069d40](https://linux-hardware.org/?probe=59d2069d40) | Dec 07, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [ce350750e3](https://linux-hardware.org/?probe=ce350750e3) | Dec 05, 2020 |
| Toshiba       | Satellite C850D-119         | Notebook    | [4a0f2ef22e](https://linux-hardware.org/?probe=4a0f2ef22e) | Dec 05, 2020 |
| HP            | Pavilion dv7                | Notebook    | [ea3cf2d030](https://linux-hardware.org/?probe=ea3cf2d030) | Dec 04, 2020 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [455f011c08](https://linux-hardware.org/?probe=455f011c08) | Dec 03, 2020 |
| ASUSTek       | X556UQK                     | Notebook    | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [584da25316](https://linux-hardware.org/?probe=584da25316) | Dec 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [24658bc507](https://linux-hardware.org/?probe=24658bc507) | Dec 01, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [09b180815e](https://linux-hardware.org/?probe=09b180815e) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [23ee81bd5e](https://linux-hardware.org/?probe=23ee81bd5e) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | Notebook    | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | Notebook    | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Sony          | VPCW12J1E                   | Notebook    | [7f54f3a6f0](https://linux-hardware.org/?probe=7f54f3a6f0) | Dec 01, 2020 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [32f996990f](https://linux-hardware.org/?probe=32f996990f) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a56d5a585c](https://linux-hardware.org/?probe=a56d5a585c) | Nov 30, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [2810240912](https://linux-hardware.org/?probe=2810240912) | Nov 30, 2020 |
| Acer          | Predator G5-793             | Notebook    | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| HP            | 1998                        | Desktop     | [33515aa889](https://linux-hardware.org/?probe=33515aa889) | Nov 29, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [e2e1a617e3](https://linux-hardware.org/?probe=e2e1a617e3) | Nov 29, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [c34c324fc5](https://linux-hardware.org/?probe=c34c324fc5) | Nov 28, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [e261ebbf0e](https://linux-hardware.org/?probe=e261ebbf0e) | Nov 26, 2020 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [c95d6e0e82](https://linux-hardware.org/?probe=c95d6e0e82) | Nov 24, 2020 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [bd69f808e5](https://linux-hardware.org/?probe=bd69f808e5) | Nov 24, 2020 |
| Toshiba       | Satellite P500              | Notebook    | [25e5577463](https://linux-hardware.org/?probe=25e5577463) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [0bc23c46e1](https://linux-hardware.org/?probe=0bc23c46e1) | Nov 23, 2020 |
| MSI           | H81M PRO-VD                 | Desktop     | [2ff7b9d197](https://linux-hardware.org/?probe=2ff7b9d197) | Nov 23, 2020 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [7e4f7fa402](https://linux-hardware.org/?probe=7e4f7fa402) | Nov 23, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [75644ed3b7](https://linux-hardware.org/?probe=75644ed3b7) | Nov 23, 2020 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [1dc63b8e97](https://linux-hardware.org/?probe=1dc63b8e97) | Nov 23, 2020 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [08ba3f8354](https://linux-hardware.org/?probe=08ba3f8354) | Nov 22, 2020 |
| Acer          | Aspire 9500                 | Notebook    | [14c016a2f9](https://linux-hardware.org/?probe=14c016a2f9) | Nov 22, 2020 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [a1d0d6fdb7](https://linux-hardware.org/?probe=a1d0d6fdb7) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [4818c2eae0](https://linux-hardware.org/?probe=4818c2eae0) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [b0cee03629](https://linux-hardware.org/?probe=b0cee03629) | Nov 22, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [6f38a56098](https://linux-hardware.org/?probe=6f38a56098) | Nov 20, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [00c9bbbec5](https://linux-hardware.org/?probe=00c9bbbec5) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [baae1bd1ef](https://linux-hardware.org/?probe=baae1bd1ef) | Nov 20, 2020 |
| HP            | 14                          | Notebook    | [99583d854a](https://linux-hardware.org/?probe=99583d854a) | Nov 20, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c893b56f4b](https://linux-hardware.org/?probe=c893b56f4b) | Nov 19, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e191bfb512](https://linux-hardware.org/?probe=e191bfb512) | Nov 19, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [44bf08a027](https://linux-hardware.org/?probe=44bf08a027) | Nov 19, 2020 |
| HP            | 158B                        | Desktop     | [048fb23518](https://linux-hardware.org/?probe=048fb23518) | Nov 19, 2020 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2385da6b14](https://linux-hardware.org/?probe=2385da6b14) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [f900377694](https://linux-hardware.org/?probe=f900377694) | Nov 18, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [6647cfca50](https://linux-hardware.org/?probe=6647cfca50) | Nov 18, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4a734aa939](https://linux-hardware.org/?probe=4a734aa939) | Nov 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [f2f6bcc691](https://linux-hardware.org/?probe=f2f6bcc691) | Nov 17, 2020 |
| HP            | Pavilion g6                 | Notebook    | [4a521aad50](https://linux-hardware.org/?probe=4a521aad50) | Nov 16, 2020 |
| Clevo         | W55xEU                      | Notebook    | [932e7d8f27](https://linux-hardware.org/?probe=932e7d8f27) | Nov 16, 2020 |
| MSI           | B365M PRO-VH                | Desktop     | [9edabdaf62](https://linux-hardware.org/?probe=9edabdaf62) | Nov 15, 2020 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [43e0f99b97](https://linux-hardware.org/?probe=43e0f99b97) | Nov 14, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [bd2dcac2ac](https://linux-hardware.org/?probe=bd2dcac2ac) | Nov 12, 2020 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [3233bbc0ec](https://linux-hardware.org/?probe=3233bbc0ec) | Nov 12, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [02f2260a96](https://linux-hardware.org/?probe=02f2260a96) | Nov 12, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [61fa8dc919](https://linux-hardware.org/?probe=61fa8dc919) | Nov 12, 2020 |
| MSI           | GE70 2OC\2OE                | Notebook    | [ba1376cdb9](https://linux-hardware.org/?probe=ba1376cdb9) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [0c0bf4e794](https://linux-hardware.org/?probe=0c0bf4e794) | Nov 11, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [005da6030a](https://linux-hardware.org/?probe=005da6030a) | Nov 11, 2020 |
| ASUSTek       | X540LJ                      | Notebook    | [3a7e7932f2](https://linux-hardware.org/?probe=3a7e7932f2) | Nov 10, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [a4aae311b7](https://linux-hardware.org/?probe=a4aae311b7) | Nov 09, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6ed5d0f8ea](https://linux-hardware.org/?probe=6ed5d0f8ea) | Nov 07, 2020 |
| HP            | 3397                        | Desktop     | [583e0c49c2](https://linux-hardware.org/?probe=583e0c49c2) | Nov 05, 2020 |
| MSI           | H81M PRO-VD                 | Desktop     | [b2b38f7c21](https://linux-hardware.org/?probe=b2b38f7c21) | Nov 05, 2020 |
| Dell          | Latitude 7400               | Notebook    | [95aa8c5f82](https://linux-hardware.org/?probe=95aa8c5f82) | Nov 04, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5b2b100711](https://linux-hardware.org/?probe=5b2b100711) | Nov 04, 2020 |
| ASUSTek       | K5130                       | Desktop     | [893f38d333](https://linux-hardware.org/?probe=893f38d333) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b30631ff4c](https://linux-hardware.org/?probe=b30631ff4c) | Nov 03, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [b087bebc1e](https://linux-hardware.org/?probe=b087bebc1e) | Nov 03, 2020 |
| HP            | 1998                        | Desktop     | [053d3aaa45](https://linux-hardware.org/?probe=053d3aaa45) | Nov 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5a78c67deb](https://linux-hardware.org/?probe=5a78c67deb) | Oct 30, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [a104997cae](https://linux-hardware.org/?probe=a104997cae) | Oct 30, 2020 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [ced2dcbac9](https://linux-hardware.org/?probe=ced2dcbac9) | Oct 29, 2020 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [f34d071ba0](https://linux-hardware.org/?probe=f34d071ba0) | Oct 29, 2020 |
| HP            | 15                          | Notebook    | [8ebe037b8f](https://linux-hardware.org/?probe=8ebe037b8f) | Oct 29, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ca94d5886](https://linux-hardware.org/?probe=7ca94d5886) | Oct 29, 2020 |
| Lenovo        | Board                       | Desktop     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| Toshiba       | Satellite C850D-119         | Notebook    | [493e216eea](https://linux-hardware.org/?probe=493e216eea) | Oct 25, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [08fdefffc8](https://linux-hardware.org/?probe=08fdefffc8) | Oct 24, 2020 |
| HP            | 255 G1                      | Notebook    | [bfd456834c](https://linux-hardware.org/?probe=bfd456834c) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | Desktop     | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| HP            | 84EE 1100                   | All in one  | [5fc64a8883](https://linux-hardware.org/?probe=5fc64a8883) | Oct 23, 2020 |
| MSI           | H81M PRO-VD                 | Desktop     | [12d71d6b83](https://linux-hardware.org/?probe=12d71d6b83) | Oct 21, 2020 |
| Toshiba       | Satellite P200              | Notebook    | [84d2d0d8cf](https://linux-hardware.org/?probe=84d2d0d8cf) | Oct 21, 2020 |
| Toshiba       | Satellite P200              | Notebook    | [932b71224c](https://linux-hardware.org/?probe=932b71224c) | Oct 21, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [b7f2a6ef39](https://linux-hardware.org/?probe=b7f2a6ef39) | Oct 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0f6b6ecd03](https://linux-hardware.org/?probe=0f6b6ecd03) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f6626ce773](https://linux-hardware.org/?probe=f6626ce773) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [a921662ed8](https://linux-hardware.org/?probe=a921662ed8) | Oct 17, 2020 |
| HP            | 84EE 1100                   | All in one  | [2154d1844e](https://linux-hardware.org/?probe=2154d1844e) | Oct 17, 2020 |
| Dell          | XPS L502X                   | Notebook    | [dc6eea4b63](https://linux-hardware.org/?probe=dc6eea4b63) | Oct 17, 2020 |
| HP            | 84EE 1100                   | All in one  | [31e1208249](https://linux-hardware.org/?probe=31e1208249) | Oct 17, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [456f1d4b3b](https://linux-hardware.org/?probe=456f1d4b3b) | Oct 16, 2020 |
| ASUSTek       | Rampage Formula             | Desktop     | [d015efaedd](https://linux-hardware.org/?probe=d015efaedd) | Oct 15, 2020 |
| Clevo         | M660SE                      | Notebook    | [01a8ac7cd9](https://linux-hardware.org/?probe=01a8ac7cd9) | Oct 14, 2020 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5752a1dbb8](https://linux-hardware.org/?probe=5752a1dbb8) | Oct 14, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [bd93e81149](https://linux-hardware.org/?probe=bd93e81149) | Oct 14, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4974ae8ad2](https://linux-hardware.org/?probe=4974ae8ad2) | Oct 13, 2020 |
| Sony          | VPCCB2S1E                   | Notebook    | [8a80ad4971](https://linux-hardware.org/?probe=8a80ad4971) | Oct 13, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [1d2919768b](https://linux-hardware.org/?probe=1d2919768b) | Oct 13, 2020 |
| Clevo         | M660SE                      | Notebook    | [9bd883acaa](https://linux-hardware.org/?probe=9bd883acaa) | Oct 12, 2020 |
| Dell          | G3 3590                     | Notebook    | [e710fb7efe](https://linux-hardware.org/?probe=e710fb7efe) | Oct 12, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [65de3956e6](https://linux-hardware.org/?probe=65de3956e6) | Oct 12, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [66eaa46127](https://linux-hardware.org/?probe=66eaa46127) | Oct 11, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [216ac30a9b](https://linux-hardware.org/?probe=216ac30a9b) | Oct 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [941d9edff3](https://linux-hardware.org/?probe=941d9edff3) | Oct 11, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [03d4495b89](https://linux-hardware.org/?probe=03d4495b89) | Oct 10, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [33f4f77db5](https://linux-hardware.org/?probe=33f4f77db5) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [8700c3217b](https://linux-hardware.org/?probe=8700c3217b) | Oct 10, 2020 |
| HP            | Notebook                    | Notebook    | [1e6bba57b7](https://linux-hardware.org/?probe=1e6bba57b7) | Oct 09, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [a6569d4074](https://linux-hardware.org/?probe=a6569d4074) | Oct 09, 2020 |
| Acer          | AO531h                      | Notebook    | [af1d7d28cc](https://linux-hardware.org/?probe=af1d7d28cc) | Oct 07, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [f814a33c4c](https://linux-hardware.org/?probe=f814a33c4c) | Oct 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c1ff9eb372](https://linux-hardware.org/?probe=c1ff9eb372) | Oct 06, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1f401d3ab8](https://linux-hardware.org/?probe=1f401d3ab8) | Oct 04, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [76406749f2](https://linux-hardware.org/?probe=76406749f2) | Oct 04, 2020 |
| ASUSTek       | Rampage Formula             | Desktop     | [8a50e35e65](https://linux-hardware.org/?probe=8a50e35e65) | Oct 04, 2020 |
| ASUSTek       | Rampage Formula             | Desktop     | [aa6626f3b5](https://linux-hardware.org/?probe=aa6626f3b5) | Oct 04, 2020 |
| ASUSTek       | Crosshair IV Extreme        | Desktop     | [7a1cab9b57](https://linux-hardware.org/?probe=7a1cab9b57) | Oct 04, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b88c0fed86](https://linux-hardware.org/?probe=b88c0fed86) | Oct 03, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [2436dcb42a](https://linux-hardware.org/?probe=2436dcb42a) | Oct 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [815070f834](https://linux-hardware.org/?probe=815070f834) | Oct 02, 2020 |
| Lenovo        | ThinkPad E580 20KS006GUK    | Notebook    | [43cd14b799](https://linux-hardware.org/?probe=43cd14b799) | Oct 01, 2020 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [df12d4ae9a](https://linux-hardware.org/?probe=df12d4ae9a) | Sep 30, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [dc08069215](https://linux-hardware.org/?probe=dc08069215) | Sep 29, 2020 |
| MSI           | H81M PRO-VD                 | Desktop     | [65d6038c79](https://linux-hardware.org/?probe=65d6038c79) | Sep 29, 2020 |
| Sony          | VPCM13M1E                   | Notebook    | [139119fce3](https://linux-hardware.org/?probe=139119fce3) | Sep 28, 2020 |
| Sony          | VPCM13M1E                   | Notebook    | [40da79e9dc](https://linux-hardware.org/?probe=40da79e9dc) | Sep 28, 2020 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [000ee6620d](https://linux-hardware.org/?probe=000ee6620d) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [f6809ca4e3](https://linux-hardware.org/?probe=f6809ca4e3) | Sep 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [135cb18944](https://linux-hardware.org/?probe=135cb18944) | Sep 26, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | Pavilion g6                 | Notebook    | [7ed6ea1d8e](https://linux-hardware.org/?probe=7ed6ea1d8e) | Sep 24, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [301fab4ca7](https://linux-hardware.org/?probe=301fab4ca7) | Sep 17, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [7f586384da](https://linux-hardware.org/?probe=7f586384da) | Sep 14, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [18771bd52f](https://linux-hardware.org/?probe=18771bd52f) | Sep 14, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [04b3b93310](https://linux-hardware.org/?probe=04b3b93310) | Sep 13, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | Notebook    | [9149c8b59c](https://linux-hardware.org/?probe=9149c8b59c) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | Notebook    | [d549f8665d](https://linux-hardware.org/?probe=d549f8665d) | Sep 11, 2020 |
| MSI           | B150M MORTAR                | Desktop     | [3a6d780eff](https://linux-hardware.org/?probe=3a6d780eff) | Sep 11, 2020 |
| HP            | 1495                        | Desktop     | [02bb1f1448](https://linux-hardware.org/?probe=02bb1f1448) | Sep 11, 2020 |
| Lenovo        | Board                       | Desktop     | [82306363c8](https://linux-hardware.org/?probe=82306363c8) | Sep 10, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | Notebook    | [41a8975f07](https://linux-hardware.org/?probe=41a8975f07) | Sep 09, 2020 |
| Fujitsu Si... | 8P965UBH-RH-FS              | Desktop     | [8469018851](https://linux-hardware.org/?probe=8469018851) | Sep 09, 2020 |
| Fujitsu Si... | 8P965UBH-RH-FS              | Desktop     | [d3e1b20591](https://linux-hardware.org/?probe=d3e1b20591) | Sep 09, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [dcdd010420](https://linux-hardware.org/?probe=dcdd010420) | Sep 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [118b474cc3](https://linux-hardware.org/?probe=118b474cc3) | Sep 06, 2020 |
| ASRock        | H81M-GL                     | Desktop     | [adca51da19](https://linux-hardware.org/?probe=adca51da19) | Sep 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ec5f49b3b8](https://linux-hardware.org/?probe=ec5f49b3b8) | Sep 03, 2020 |
| Dell          | Latitude 5400               | Notebook    | [1ae84c03c5](https://linux-hardware.org/?probe=1ae84c03c5) | Sep 02, 2020 |
| Gigabyte      | M68M-S2P                    | Desktop     | [acbf11a591](https://linux-hardware.org/?probe=acbf11a591) | Sep 02, 2020 |
| HP            | 15                          | Notebook    | [5b582297ed](https://linux-hardware.org/?probe=5b582297ed) | Sep 02, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ff5ef4f17a](https://linux-hardware.org/?probe=ff5ef4f17a) | Aug 31, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [355ea30725](https://linux-hardware.org/?probe=355ea30725) | Aug 30, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [c5c689fadd](https://linux-hardware.org/?probe=c5c689fadd) | Aug 30, 2020 |
| Dell          | Inspiron 7720               | Notebook    | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [9f0b4888f9](https://linux-hardware.org/?probe=9f0b4888f9) | Aug 22, 2020 |
| HP            | Compaq 6735s                | Notebook    | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [85dd645b39](https://linux-hardware.org/?probe=85dd645b39) | Aug 16, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [8b03ada262](https://linux-hardware.org/?probe=8b03ada262) | Aug 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a9262f65c0](https://linux-hardware.org/?probe=a9262f65c0) | Aug 15, 2020 |
| Dell          | Vostro 5481                 | Notebook    | [fc1a36f64d](https://linux-hardware.org/?probe=fc1a36f64d) | Aug 13, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [23932dee06](https://linux-hardware.org/?probe=23932dee06) | Aug 08, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [b2bb2e091d](https://linux-hardware.org/?probe=b2bb2e091d) | Aug 08, 2020 |
| Toshiba       | Satellite P200D             | Notebook    | [9bb94d56ed](https://linux-hardware.org/?probe=9bb94d56ed) | Aug 06, 2020 |
| Lenovo        | Board                       | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [20185e7b49](https://linux-hardware.org/?probe=20185e7b49) | Aug 04, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ce7d3839c2](https://linux-hardware.org/?probe=ce7d3839c2) | Aug 04, 2020 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [62925bc138](https://linux-hardware.org/?probe=62925bc138) | Aug 01, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [50226c4586](https://linux-hardware.org/?probe=50226c4586) | Jul 30, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [25489b5aa4](https://linux-hardware.org/?probe=25489b5aa4) | Jul 29, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [d690a1848c](https://linux-hardware.org/?probe=d690a1848c) | Jul 29, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [6b6a4fb2a4](https://linux-hardware.org/?probe=6b6a4fb2a4) | Jul 27, 2020 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [ea24181230](https://linux-hardware.org/?probe=ea24181230) | Jul 26, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7b6b423b68](https://linux-hardware.org/?probe=7b6b423b68) | Jul 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [ed0973a339](https://linux-hardware.org/?probe=ed0973a339) | Jul 23, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [192dd297bd](https://linux-hardware.org/?probe=192dd297bd) | Jul 22, 2020 |
| Dell          | G3 3590                     | Notebook    | [0bfa0fdeb2](https://linux-hardware.org/?probe=0bfa0fdeb2) | Jul 22, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [ab12b8b821](https://linux-hardware.org/?probe=ab12b8b821) | Jul 21, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [b73a34930b](https://linux-hardware.org/?probe=b73a34930b) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [a026a886dc](https://linux-hardware.org/?probe=a026a886dc) | Jul 18, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [41dd1d4d2f](https://linux-hardware.org/?probe=41dd1d4d2f) | Jul 18, 2020 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [9807c6ea02](https://linux-hardware.org/?probe=9807c6ea02) | Jul 18, 2020 |
| HP            | 339A                        | Desktop     | [1c3706f5bb](https://linux-hardware.org/?probe=1c3706f5bb) | Jul 17, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [83841db5dd](https://linux-hardware.org/?probe=83841db5dd) | Jul 17, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [58738fe100](https://linux-hardware.org/?probe=58738fe100) | Jul 17, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [6bcb4b0e88](https://linux-hardware.org/?probe=6bcb4b0e88) | Jul 13, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bb4aee1ce5](https://linux-hardware.org/?probe=bb4aee1ce5) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [39df7edbea](https://linux-hardware.org/?probe=39df7edbea) | Jul 09, 2020 |
| Dell          | 040DDP A01                  | Desktop     | [f45d9ec3af](https://linux-hardware.org/?probe=f45d9ec3af) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| ASRock        | B450M-HDV                   | Desktop     | [a74dc966e4](https://linux-hardware.org/?probe=a74dc966e4) | Jul 08, 2020 |
| Dell          | 0Y5FXV A00                  | Desktop     | [9e489ee5d4](https://linux-hardware.org/?probe=9e489ee5d4) | Jul 08, 2020 |
| MSI           | AM1I                        | Desktop     | [27e3770f9f](https://linux-hardware.org/?probe=27e3770f9f) | Jul 08, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [717049c98f](https://linux-hardware.org/?probe=717049c98f) | Jul 07, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f0a928112b](https://linux-hardware.org/?probe=f0a928112b) | Jul 07, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3fa02437d2](https://linux-hardware.org/?probe=3fa02437d2) | Jul 07, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [b6506c9a23](https://linux-hardware.org/?probe=b6506c9a23) | Jul 07, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [0488222130](https://linux-hardware.org/?probe=0488222130) | Jul 05, 2020 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [6f4a149255](https://linux-hardware.org/?probe=6f4a149255) | Jul 02, 2020 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Notebook      | NJ50_70CU                   | Notebook    | [5c9684cdab](https://linux-hardware.org/?probe=5c9684cdab) | Jun 29, 2020 |
| Lenovo        | G40-30 80FY                 | Notebook    | [157e79f788](https://linux-hardware.org/?probe=157e79f788) | Jun 28, 2020 |
| Lenovo        | G40-30 80FY                 | Notebook    | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| Notebook      | NJ50_70CU                   | Notebook    | [427a02d3bc](https://linux-hardware.org/?probe=427a02d3bc) | Jun 27, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [eadf2910c1](https://linux-hardware.org/?probe=eadf2910c1) | Jun 26, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [9b7f2ae65e](https://linux-hardware.org/?probe=9b7f2ae65e) | Jun 25, 2020 |
| HP            | ZBook 15                    | Notebook    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| HP            | ProBook 6560b               | Notebook    | [5db87fcc49](https://linux-hardware.org/?probe=5db87fcc49) | Jun 24, 2020 |
| HP            | ProBook 6560b               | Notebook    | [9a78de8ed6](https://linux-hardware.org/?probe=9a78de8ed6) | Jun 24, 2020 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [ad9f19123a](https://linux-hardware.org/?probe=ad9f19123a) | Jun 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [31b59ae094](https://linux-hardware.org/?probe=31b59ae094) | Jun 24, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | Notebook    | [68f2706e1c](https://linux-hardware.org/?probe=68f2706e1c) | Jun 22, 2020 |
| Sony          | VGN-N31Z_W                  | Notebook    | [9dbeef64ee](https://linux-hardware.org/?probe=9dbeef64ee) | Jun 22, 2020 |
| Gigabyte      | B360M D2V                   | Desktop     | [d5c81912f3](https://linux-hardware.org/?probe=d5c81912f3) | Jun 22, 2020 |
| ASUSTek       | K52JU                       | Notebook    | [38a9288b85](https://linux-hardware.org/?probe=38a9288b85) | Jun 21, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [9ef15f5d63](https://linux-hardware.org/?probe=9ef15f5d63) | Jun 21, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [a732fadebf](https://linux-hardware.org/?probe=a732fadebf) | Jun 21, 2020 |
| ASUSTek       | K52JU                       | Notebook    | [a07e2655ec](https://linux-hardware.org/?probe=a07e2655ec) | Jun 21, 2020 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [77f20e18fe](https://linux-hardware.org/?probe=77f20e18fe) | Jun 20, 2020 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [22e08e13fb](https://linux-hardware.org/?probe=22e08e13fb) | Jun 20, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b388cd0a96](https://linux-hardware.org/?probe=b388cd0a96) | Jun 20, 2020 |
| HP            | 18E4                        | Desktop     | [de1ec6cf05](https://linux-hardware.org/?probe=de1ec6cf05) | Jun 18, 2020 |
| ASUSTek       | X556UQK                     | Notebook    | [c6c57358a6](https://linux-hardware.org/?probe=c6c57358a6) | Jun 18, 2020 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5eec140218](https://linux-hardware.org/?probe=5eec140218) | Jun 18, 2020 |
| Toshiba       | Satellite A300D             | Notebook    | [872199f2c5](https://linux-hardware.org/?probe=872199f2c5) | Jun 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [eaccc0249f](https://linux-hardware.org/?probe=eaccc0249f) | Jun 17, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [5c2c44732b](https://linux-hardware.org/?probe=5c2c44732b) | Jun 17, 2020 |
| Toshiba       | Satellite A300D             | Notebook    | [8e0f23dc31](https://linux-hardware.org/?probe=8e0f23dc31) | Jun 16, 2020 |
| HP            | 15                          | Notebook    | [7644a7713f](https://linux-hardware.org/?probe=7644a7713f) | Jun 16, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [750c6c3f47](https://linux-hardware.org/?probe=750c6c3f47) | Jun 15, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [103b4d6704](https://linux-hardware.org/?probe=103b4d6704) | Jun 15, 2020 |
| HP            | 1495                        | Desktop     | [b5eb32227c](https://linux-hardware.org/?probe=b5eb32227c) | Jun 14, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a798cb0891](https://linux-hardware.org/?probe=a798cb0891) | Jun 12, 2020 |
| Acer          | Aspire 3935                 | Notebook    | [3957942dc1](https://linux-hardware.org/?probe=3957942dc1) | Jun 10, 2020 |
| Intel         | DN2820FYK H24582-202        | Desktop     | [58e20d2f89](https://linux-hardware.org/?probe=58e20d2f89) | Jun 08, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [45a4b1598d](https://linux-hardware.org/?probe=45a4b1598d) | Jun 07, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b43ad5a6b1](https://linux-hardware.org/?probe=b43ad5a6b1) | Jun 07, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [a594975388](https://linux-hardware.org/?probe=a594975388) | Jun 06, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [62134f37df](https://linux-hardware.org/?probe=62134f37df) | Jun 06, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6834600254](https://linux-hardware.org/?probe=6834600254) | Jun 05, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd81341297](https://linux-hardware.org/?probe=cd81341297) | Jun 03, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [71b460bd76](https://linux-hardware.org/?probe=71b460bd76) | Jun 02, 2020 |
| HP            | Pavilion dv7                | Notebook    | [27d5196b74](https://linux-hardware.org/?probe=27d5196b74) | May 30, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [99a79f4889](https://linux-hardware.org/?probe=99a79f4889) | May 30, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e4bba31386](https://linux-hardware.org/?probe=e4bba31386) | May 29, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bd6ea57435](https://linux-hardware.org/?probe=bd6ea57435) | May 29, 2020 |
| Toshiba       | Satellite S855D             | Notebook    | [2b4ff1e9b6](https://linux-hardware.org/?probe=2b4ff1e9b6) | May 29, 2020 |
| Toshiba       | Satellite S855D             | Notebook    | [8e54bbb3e2](https://linux-hardware.org/?probe=8e54bbb3e2) | May 29, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | Notebook    | [9975194681](https://linux-hardware.org/?probe=9975194681) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [a8a351b9b3](https://linux-hardware.org/?probe=a8a351b9b3) | May 28, 2020 |
| HP            | Pavilion g6                 | Notebook    | [1fd4402991](https://linux-hardware.org/?probe=1fd4402991) | May 28, 2020 |
| Dell          | 040DDP A01                  | Desktop     | [da5657c3c9](https://linux-hardware.org/?probe=da5657c3c9) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | Notebook    | [15696a9c46](https://linux-hardware.org/?probe=15696a9c46) | May 28, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0af569f207](https://linux-hardware.org/?probe=0af569f207) | May 27, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [14e6ced790](https://linux-hardware.org/?probe=14e6ced790) | May 27, 2020 |
| Lenovo        | Board                       | Desktop     | [dc3403470e](https://linux-hardware.org/?probe=dc3403470e) | May 27, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [0d35855885](https://linux-hardware.org/?probe=0d35855885) | May 25, 2020 |
| Lenovo        | ThinkPad T580 20L90023RT    | Notebook    | [a7b6c79ac0](https://linux-hardware.org/?probe=a7b6c79ac0) | May 24, 2020 |
| HP            | Pavilion dv7                | Notebook    | [9d4e0753f6](https://linux-hardware.org/?probe=9d4e0753f6) | May 23, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [33cbff4154](https://linux-hardware.org/?probe=33cbff4154) | May 23, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ed61c260f3](https://linux-hardware.org/?probe=ed61c260f3) | May 23, 2020 |
| HP            | 304Ah                       | Desktop     | [1634c5ba40](https://linux-hardware.org/?probe=1634c5ba40) | May 23, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [43e3fadb97](https://linux-hardware.org/?probe=43e3fadb97) | May 23, 2020 |
| ASRock        | H81M-GL                     | Desktop     | [40f0375a69](https://linux-hardware.org/?probe=40f0375a69) | May 23, 2020 |
| HP            | Unknown                     | Notebook    | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [7a127362d4](https://linux-hardware.org/?probe=7a127362d4) | May 22, 2020 |
| Dell          | Latitude E6410              | Notebook    | [7c8e49e14c](https://linux-hardware.org/?probe=7c8e49e14c) | May 22, 2020 |
| HP            | Unknown                     | Notebook    | [0be27afc58](https://linux-hardware.org/?probe=0be27afc58) | May 22, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Pavilion g6                 | Notebook    | [31a778de5b](https://linux-hardware.org/?probe=31a778de5b) | May 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [68952aafce](https://linux-hardware.org/?probe=68952aafce) | May 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [619ed13a7f](https://linux-hardware.org/?probe=619ed13a7f) | May 18, 2020 |
| Gigabyte      | 8I865G775-G                 | Desktop     | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [24f89ac1d4](https://linux-hardware.org/?probe=24f89ac1d4) | May 18, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [fa51e14d38](https://linux-hardware.org/?probe=fa51e14d38) | May 17, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [67b7ec6a84](https://linux-hardware.org/?probe=67b7ec6a84) | May 17, 2020 |
| HP            | Pavilion g6                 | Notebook    | [de917a6cdc](https://linux-hardware.org/?probe=de917a6cdc) | May 17, 2020 |
| HP            | Pavilion g6                 | Notebook    | [f5334be644](https://linux-hardware.org/?probe=f5334be644) | May 17, 2020 |
| HP            | 1998                        | Desktop     | [9ccf5438f1](https://linux-hardware.org/?probe=9ccf5438f1) | May 16, 2020 |
| HP            | 1998                        | Desktop     | [62c2c8d350](https://linux-hardware.org/?probe=62c2c8d350) | May 16, 2020 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [9f89d95532](https://linux-hardware.org/?probe=9f89d95532) | May 16, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4718002197](https://linux-hardware.org/?probe=4718002197) | May 16, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d12112ae8b](https://linux-hardware.org/?probe=d12112ae8b) | May 16, 2020 |
| Notebook      | W65_67SH                    | Notebook    | [497422c9fc](https://linux-hardware.org/?probe=497422c9fc) | May 16, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4b547ad198](https://linux-hardware.org/?probe=4b547ad198) | May 16, 2020 |
| Notebook      | W65_67SH                    | Notebook    | [9559aff349](https://linux-hardware.org/?probe=9559aff349) | May 16, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [01b6eef865](https://linux-hardware.org/?probe=01b6eef865) | May 14, 2020 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [d9884d1dfd](https://linux-hardware.org/?probe=d9884d1dfd) | May 14, 2020 |
| ASUSTek       | M3A78-T                     | Desktop     | [3d44016f99](https://linux-hardware.org/?probe=3d44016f99) | May 14, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [65825e0bec](https://linux-hardware.org/?probe=65825e0bec) | May 13, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1cb7e4e70a](https://linux-hardware.org/?probe=1cb7e4e70a) | May 13, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [75714d5542](https://linux-hardware.org/?probe=75714d5542) | May 13, 2020 |
| Dell          | Latitude E5410              | Notebook    | [b51e124387](https://linux-hardware.org/?probe=b51e124387) | May 13, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d225d411f9](https://linux-hardware.org/?probe=d225d411f9) | May 13, 2020 |
| HP            | 250 G4                      | Notebook    | [adc4529aff](https://linux-hardware.org/?probe=adc4529aff) | May 12, 2020 |
| Lenovo        | ThinkPad X230 23245D4       | Notebook    | [740b68266b](https://linux-hardware.org/?probe=740b68266b) | May 12, 2020 |
| Dell          | G3 3590                     | Notebook    | [85e10bcd60](https://linux-hardware.org/?probe=85e10bcd60) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| Toshiba       | NB100                       | Notebook    | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | Notebook    | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [bd8e53be4e](https://linux-hardware.org/?probe=bd8e53be4e) | May 11, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [72a8998b44](https://linux-hardware.org/?probe=72a8998b44) | May 11, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [70466d71d3](https://linux-hardware.org/?probe=70466d71d3) | May 11, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| HP            | G5000 (GF767EA#B1A)         | Notebook    | [39fd61954e](https://linux-hardware.org/?probe=39fd61954e) | May 10, 2020 |
| ASRock        | B75M R2.0                   | Desktop     | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [3cef46e3b5](https://linux-hardware.org/?probe=3cef46e3b5) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [425ab8fa42](https://linux-hardware.org/?probe=425ab8fa42) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [326dfdd03c](https://linux-hardware.org/?probe=326dfdd03c) | May 09, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [231fda4e89](https://linux-hardware.org/?probe=231fda4e89) | May 09, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [31d6317082](https://linux-hardware.org/?probe=31d6317082) | May 08, 2020 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [6b9367fb7d](https://linux-hardware.org/?probe=6b9367fb7d) | May 07, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [929c938534](https://linux-hardware.org/?probe=929c938534) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CLS0110B    | Notebook    | [9da7641ead](https://linux-hardware.org/?probe=9da7641ead) | May 07, 2020 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [419ece7416](https://linux-hardware.org/?probe=419ece7416) | May 06, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [0de2cd5337](https://linux-hardware.org/?probe=0de2cd5337) | May 06, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [aa3029d253](https://linux-hardware.org/?probe=aa3029d253) | May 06, 2020 |
| Pegatron      | D15R                        | Notebook    | [9b128d4d23](https://linux-hardware.org/?probe=9b128d4d23) | May 05, 2020 |
| Pegatron      | D15R                        | Notebook    | [25cf2e91d8](https://linux-hardware.org/?probe=25cf2e91d8) | May 05, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [061da7844f](https://linux-hardware.org/?probe=061da7844f) | May 05, 2020 |
| Sony          | VGN-CR590E                  | Notebook    | [cb2c7466cc](https://linux-hardware.org/?probe=cb2c7466cc) | May 04, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [097d9e6627](https://linux-hardware.org/?probe=097d9e6627) | May 03, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0b92e38d49](https://linux-hardware.org/?probe=0b92e38d49) | May 03, 2020 |
| Acer          | Aspire 5100                 | Notebook    | [0b4ce05d4b](https://linux-hardware.org/?probe=0b4ce05d4b) | May 03, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [b2d97bede2](https://linux-hardware.org/?probe=b2d97bede2) | May 02, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [a260c9daa7](https://linux-hardware.org/?probe=a260c9daa7) | May 01, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [206baf206d](https://linux-hardware.org/?probe=206baf206d) | May 01, 2020 |
| Dell          | 0PC5F7 A01                  | Desktop     | [541846e7d7](https://linux-hardware.org/?probe=541846e7d7) | May 01, 2020 |
| ASUSTek       | A7N8X-X                     | Desktop     | [e975d79594](https://linux-hardware.org/?probe=e975d79594) | May 01, 2020 |
| ASUSTek       | A7N8X-X                     | Desktop     | [75dea3bce3](https://linux-hardware.org/?probe=75dea3bce3) | May 01, 2020 |
| ASRock        | M3A785GXH/128M              | Desktop     | [2c2e4ffd37](https://linux-hardware.org/?probe=2c2e4ffd37) | May 01, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [81517bd66d](https://linux-hardware.org/?probe=81517bd66d) | May 01, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | Notebook    | [f77cb5d716](https://linux-hardware.org/?probe=f77cb5d716) | Apr 30, 2020 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [ae1bdb128c](https://linux-hardware.org/?probe=ae1bdb128c) | Apr 30, 2020 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [c59ce96e89](https://linux-hardware.org/?probe=c59ce96e89) | Apr 30, 2020 |
| ASUSTek       | A8V-MX                      | Desktop     | [48bf426b83](https://linux-hardware.org/?probe=48bf426b83) | Apr 30, 2020 |
| Lenovo        | G580 20150                  | Notebook    | [158ef386df](https://linux-hardware.org/?probe=158ef386df) | Apr 29, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7deee5c6f4](https://linux-hardware.org/?probe=7deee5c6f4) | Apr 28, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [b4516c2c86](https://linux-hardware.org/?probe=b4516c2c86) | Apr 28, 2020 |
| HP            | ProBook 6560b               | Notebook    | [f7e0abeaf2](https://linux-hardware.org/?probe=f7e0abeaf2) | Apr 27, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [feaefbb60c](https://linux-hardware.org/?probe=feaefbb60c) | Apr 26, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [2a49e8c3a6](https://linux-hardware.org/?probe=2a49e8c3a6) | Apr 26, 2020 |
| HP            | Pavilion g6                 | Notebook    | [166222e5c9](https://linux-hardware.org/?probe=166222e5c9) | Apr 26, 2020 |
| HP            | Pavilion g6                 | Notebook    | [e5e0d5140e](https://linux-hardware.org/?probe=e5e0d5140e) | Apr 25, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6770cf29bb](https://linux-hardware.org/?probe=6770cf29bb) | Apr 25, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [0f27fe0e9a](https://linux-hardware.org/?probe=0f27fe0e9a) | Apr 24, 2020 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [222a066411](https://linux-hardware.org/?probe=222a066411) | Apr 24, 2020 |
| ASRock        | G31M-S                      | Desktop     | [68a7deee55](https://linux-hardware.org/?probe=68a7deee55) | Apr 24, 2020 |
| Sony          | VGN-FE41E                   | Notebook    | [1d8645be3f](https://linux-hardware.org/?probe=1d8645be3f) | Apr 24, 2020 |
| Dell          | 0WF810                      | Desktop     | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| ASUSTek       | A8V-MX                      | Desktop     | [b881fd6abb](https://linux-hardware.org/?probe=b881fd6abb) | Apr 23, 2020 |
| Dell          | 0W2563                      | Desktop     | [d83c8ddedf](https://linux-hardware.org/?probe=d83c8ddedf) | Apr 22, 2020 |
| Dell          | 0W2563                      | Desktop     | [696b47564f](https://linux-hardware.org/?probe=696b47564f) | Apr 22, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [0b48cefe24](https://linux-hardware.org/?probe=0b48cefe24) | Apr 22, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [33530c3091](https://linux-hardware.org/?probe=33530c3091) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [b6d0779fb0](https://linux-hardware.org/?probe=b6d0779fb0) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [fbb9346ad4](https://linux-hardware.org/?probe=fbb9346ad4) | Apr 21, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [b039afa67d](https://linux-hardware.org/?probe=b039afa67d) | Apr 20, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [1696d2d9ce](https://linux-hardware.org/?probe=1696d2d9ce) | Apr 20, 2020 |
| Toshiba       | Satellite L450D             | Notebook    | [7f26f2d180](https://linux-hardware.org/?probe=7f26f2d180) | Apr 20, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9b01bf2a08](https://linux-hardware.org/?probe=9b01bf2a08) | Apr 20, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ee54fa2ed4](https://linux-hardware.org/?probe=ee54fa2ed4) | Apr 20, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [b36b50c3f7](https://linux-hardware.org/?probe=b36b50c3f7) | Apr 20, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [e08a09dd83](https://linux-hardware.org/?probe=e08a09dd83) | Apr 20, 2020 |
| HP            | Unknown                     | Notebook    | [6cd3c0a036](https://linux-hardware.org/?probe=6cd3c0a036) | Apr 19, 2020 |
| HP            | Unknown                     | Notebook    | [7a5b60f20c](https://linux-hardware.org/?probe=7a5b60f20c) | Apr 19, 2020 |
| HP            | Unknown                     | Notebook    | [97ca26d3d7](https://linux-hardware.org/?probe=97ca26d3d7) | Apr 19, 2020 |
| ASUSTek       | M3N78-EM                    | Desktop     | [9c8c19f179](https://linux-hardware.org/?probe=9c8c19f179) | Apr 18, 2020 |
| ZOTAC         | AMD HUDSON-M1               | Desktop     | [e312729536](https://linux-hardware.org/?probe=e312729536) | Apr 17, 2020 |
| ZOTAC         | AMD HUDSON-M1               | Desktop     | [de7fd27b31](https://linux-hardware.org/?probe=de7fd27b31) | Apr 17, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [1ba510148e](https://linux-hardware.org/?probe=1ba510148e) | Apr 16, 2020 |
| ASUSTek       | M2A-VM                      | Desktop     | [88101e3d2f](https://linux-hardware.org/?probe=88101e3d2f) | Apr 16, 2020 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [6095aae488](https://linux-hardware.org/?probe=6095aae488) | Apr 14, 2020 |
| Toshiba       | Satellite L450D             | Notebook    | [f541e27fef](https://linux-hardware.org/?probe=f541e27fef) | Apr 14, 2020 |
| Toshiba       | Satellite L450D             | Notebook    | [dd6245c9f1](https://linux-hardware.org/?probe=dd6245c9f1) | Apr 14, 2020 |
| HP            | Compaq 6710b (GR680EA#B1... | Notebook    | [fb9d604f9d](https://linux-hardware.org/?probe=fb9d604f9d) | Apr 13, 2020 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [41f0f05e33](https://linux-hardware.org/?probe=41f0f05e33) | Apr 13, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [eb57124022](https://linux-hardware.org/?probe=eb57124022) | Apr 13, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [85350a43d3](https://linux-hardware.org/?probe=85350a43d3) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [0fb509f423](https://linux-hardware.org/?probe=0fb509f423) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [63ce7e4135](https://linux-hardware.org/?probe=63ce7e4135) | Apr 12, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6dad99eced](https://linux-hardware.org/?probe=6dad99eced) | Apr 11, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [72f97922cc](https://linux-hardware.org/?probe=72f97922cc) | Apr 09, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [126766dead](https://linux-hardware.org/?probe=126766dead) | Apr 09, 2020 |
| Dell          | Inspiron 5558               | Notebook    | [9ecfa320c9](https://linux-hardware.org/?probe=9ecfa320c9) | Apr 08, 2020 |
| Dell          | G3 3590                     | Notebook    | [9466a720ff](https://linux-hardware.org/?probe=9466a720ff) | Apr 07, 2020 |
| HP            | Pavilion dv7                | Notebook    | [88ff5b44b7](https://linux-hardware.org/?probe=88ff5b44b7) | Apr 07, 2020 |
| Dell          | Latitude E6510              | Notebook    | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Dell          | 0F5C5X A00                  | Desktop     | [ee0a362506](https://linux-hardware.org/?probe=ee0a362506) | Apr 06, 2020 |
| HP            | Presario CQ62               | Notebook    | [3821156090](https://linux-hardware.org/?probe=3821156090) | Apr 06, 2020 |
| ASUSTek       | X540LJ                      | Notebook    | [3818f5dd9e](https://linux-hardware.org/?probe=3818f5dd9e) | Apr 05, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [3b7ede7bc6](https://linux-hardware.org/?probe=3b7ede7bc6) | Apr 05, 2020 |
| HP            | Pavilion dv7                | Notebook    | [88debf96e8](https://linux-hardware.org/?probe=88debf96e8) | Apr 04, 2020 |
| HP            | Pavilion dv7                | Notebook    | [a7adf60c3c](https://linux-hardware.org/?probe=a7adf60c3c) | Apr 04, 2020 |
| Lenovo        | Board                       | Desktop     | [943d4d3c19](https://linux-hardware.org/?probe=943d4d3c19) | Apr 04, 2020 |
| HP            | Pavilion dv7                | Notebook    | [2287c81b7d](https://linux-hardware.org/?probe=2287c81b7d) | Apr 04, 2020 |
| HP            | Pavilion dv7                | Notebook    | [d64ce74086](https://linux-hardware.org/?probe=d64ce74086) | Apr 04, 2020 |
| Sony          | VGN-CR590E                  | Notebook    | [121394a15c](https://linux-hardware.org/?probe=121394a15c) | Apr 03, 2020 |
| Dell          | G3 3590                     | Notebook    | [795e283ee9](https://linux-hardware.org/?probe=795e283ee9) | Apr 01, 2020 |
| E-shop.gr     | Innovator M1589             | Notebook    | [be146dfa67](https://linux-hardware.org/?probe=be146dfa67) | Mar 31, 2020 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [9c2eef7d10](https://linux-hardware.org/?probe=9c2eef7d10) | Mar 31, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [199d2287e2](https://linux-hardware.org/?probe=199d2287e2) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | Notebook    | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Apple         | MacBook1,1                  | Notebook    | [27d210b0e2](https://linux-hardware.org/?probe=27d210b0e2) | Mar 30, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b9f6bf0ad4](https://linux-hardware.org/?probe=b9f6bf0ad4) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | Notebook    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | Notebook    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [9b4c3e822f](https://linux-hardware.org/?probe=9b4c3e822f) | Mar 29, 2020 |
| Dell          | G3 3590                     | Notebook    | [6b8e66d086](https://linux-hardware.org/?probe=6b8e66d086) | Mar 29, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8b2b986525](https://linux-hardware.org/?probe=8b2b986525) | Mar 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [220c3c60b0](https://linux-hardware.org/?probe=220c3c60b0) | Mar 28, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f792e56769](https://linux-hardware.org/?probe=f792e56769) | Mar 28, 2020 |
| HP            | 3397                        | Desktop     | [f72e7a317a](https://linux-hardware.org/?probe=f72e7a317a) | Mar 28, 2020 |
| HP            | 3397                        | Desktop     | [2c1fd6a07a](https://linux-hardware.org/?probe=2c1fd6a07a) | Mar 28, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ae5dbcbc69](https://linux-hardware.org/?probe=ae5dbcbc69) | Mar 27, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5d80035b8d](https://linux-hardware.org/?probe=5d80035b8d) | Mar 27, 2020 |
| Dell          | G3 3590                     | Notebook    | [fb1cee5bb2](https://linux-hardware.org/?probe=fb1cee5bb2) | Mar 27, 2020 |
| HP            | Compaq Mini 110c-1000       | Notebook    | [ba8efb8d78](https://linux-hardware.org/?probe=ba8efb8d78) | Mar 26, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [55f19a4f35](https://linux-hardware.org/?probe=55f19a4f35) | Mar 26, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [4fff19bf83](https://linux-hardware.org/?probe=4fff19bf83) | Mar 24, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [d361a95cae](https://linux-hardware.org/?probe=d361a95cae) | Mar 24, 2020 |
| Dell          | G3 3590                     | Notebook    | [68c4b5c3e4](https://linux-hardware.org/?probe=68c4b5c3e4) | Mar 24, 2020 |
| Dell          | G3 3590                     | Notebook    | [05edd2dcde](https://linux-hardware.org/?probe=05edd2dcde) | Mar 24, 2020 |
| Dell          | G3 3590                     | Notebook    | [ff14d5222d](https://linux-hardware.org/?probe=ff14d5222d) | Mar 24, 2020 |
| Sony          | VGN-NR11Z_S                 | Notebook    | [69fb7aa4d4](https://linux-hardware.org/?probe=69fb7aa4d4) | Mar 23, 2020 |
| HP            | ProBook 6560b               | Notebook    | [40d00a5fb1](https://linux-hardware.org/?probe=40d00a5fb1) | Mar 16, 2020 |
| ASUSTek       | P6T                         | Desktop     | [dbf0c0687f](https://linux-hardware.org/?probe=dbf0c0687f) | Mar 15, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f304a58bec](https://linux-hardware.org/?probe=f304a58bec) | Mar 13, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | Notebook    | [a6b3d80476](https://linux-hardware.org/?probe=a6b3d80476) | Mar 11, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [3a037925b6](https://linux-hardware.org/?probe=3a037925b6) | Mar 08, 2020 |
| Lenovo        | ThinkPad T470 20HD000LUK    | Notebook    | [9c47172207](https://linux-hardware.org/?probe=9c47172207) | Mar 08, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | Notebook    | [ef4dbc4e8b](https://linux-hardware.org/?probe=ef4dbc4e8b) | Mar 06, 2020 |
| Lenovo        | ThinkPad T420 4236Q23       | Notebook    | [65d50c61eb](https://linux-hardware.org/?probe=65d50c61eb) | Mar 05, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ef194ecc3b](https://linux-hardware.org/?probe=ef194ecc3b) | Mar 03, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [2e61fd9e0b](https://linux-hardware.org/?probe=2e61fd9e0b) | Mar 03, 2020 |
| IBM           | 819421G                     | Desktop     | [60a7f83f19](https://linux-hardware.org/?probe=60a7f83f19) | Mar 03, 2020 |
| HP            | 3397                        | Desktop     | [e342a631c6](https://linux-hardware.org/?probe=e342a631c6) | Mar 02, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [b3fe433c07](https://linux-hardware.org/?probe=b3fe433c07) | Feb 29, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7a0b3876ca](https://linux-hardware.org/?probe=7a0b3876ca) | Feb 26, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [da6691585c](https://linux-hardware.org/?probe=da6691585c) | Feb 26, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [d98b80df64](https://linux-hardware.org/?probe=d98b80df64) | Feb 26, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [47a8fea61e](https://linux-hardware.org/?probe=47a8fea61e) | Feb 26, 2020 |
| Dell          | 0HD5W2 A00                  | Desktop     | [5e4dcd1b24](https://linux-hardware.org/?probe=5e4dcd1b24) | Feb 26, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [150b9c6b6d](https://linux-hardware.org/?probe=150b9c6b6d) | Feb 25, 2020 |
| ASRock        | H97 Pro4                    | Desktop     | [06a946b189](https://linux-hardware.org/?probe=06a946b189) | Feb 24, 2020 |
| Compal        | Unknown                     | Notebook    | [56b05900a0](https://linux-hardware.org/?probe=56b05900a0) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [270e63cceb](https://linux-hardware.org/?probe=270e63cceb) | Feb 23, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f8b4191082](https://linux-hardware.org/?probe=f8b4191082) | Feb 23, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [77543de863](https://linux-hardware.org/?probe=77543de863) | Feb 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f3fe28b459](https://linux-hardware.org/?probe=f3fe28b459) | Feb 19, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [6beff5886c](https://linux-hardware.org/?probe=6beff5886c) | Feb 19, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [542abc0408](https://linux-hardware.org/?probe=542abc0408) | Feb 18, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [612bf8e23e](https://linux-hardware.org/?probe=612bf8e23e) | Feb 17, 2020 |
| HP            | EliteBook 6930p (KK082AV... | Notebook    | [55a53b12ce](https://linux-hardware.org/?probe=55a53b12ce) | Feb 15, 2020 |
| HP            | EliteBook 6930p (KK082AV... | Notebook    | [745a30749e](https://linux-hardware.org/?probe=745a30749e) | Feb 15, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3995d0575b](https://linux-hardware.org/?probe=3995d0575b) | Feb 13, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [b57c6ec496](https://linux-hardware.org/?probe=b57c6ec496) | Feb 12, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [05ae411d1f](https://linux-hardware.org/?probe=05ae411d1f) | Feb 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [da709d9bae](https://linux-hardware.org/?probe=da709d9bae) | Feb 09, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [d311cc43c7](https://linux-hardware.org/?probe=d311cc43c7) | Feb 09, 2020 |
| Chuwi         | HeroBook                    | Notebook    | [c63663b03e](https://linux-hardware.org/?probe=c63663b03e) | Feb 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b350a4e79](https://linux-hardware.org/?probe=7b350a4e79) | Feb 07, 2020 |
| ASUSTek       | P5KPL-C/1600                | Desktop     | [3054120eee](https://linux-hardware.org/?probe=3054120eee) | Feb 06, 2020 |
| ASUSTek       | P5KPL-C/1600                | Desktop     | [733547325a](https://linux-hardware.org/?probe=733547325a) | Feb 06, 2020 |
| HP            | 15                          | Notebook    | [16b52341f5](https://linux-hardware.org/?probe=16b52341f5) | Feb 04, 2020 |
| Gigabyte      | 965P-S3                     | Desktop     | [9a3a48c621](https://linux-hardware.org/?probe=9a3a48c621) | Feb 01, 2020 |
| Acer          | TravelMate 2490             | Notebook    | [a93e1d86a8](https://linux-hardware.org/?probe=a93e1d86a8) | Jan 27, 2020 |
| VERO          | K147                        | Notebook    | [9f10ca8308](https://linux-hardware.org/?probe=9f10ca8308) | Jan 26, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [6fc14bf3ff](https://linux-hardware.org/?probe=6fc14bf3ff) | Jan 26, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [eec3f4a665](https://linux-hardware.org/?probe=eec3f4a665) | Jan 19, 2020 |
| AOpen         | i945GMm-HL 918EM10I4F0      | Desktop     | [8b319cd8a8](https://linux-hardware.org/?probe=8b319cd8a8) | Jan 18, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMH    | Notebook    | [3a02dced23](https://linux-hardware.org/?probe=3a02dced23) | Jan 14, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ae993b5ad5](https://linux-hardware.org/?probe=ae993b5ad5) | Jan 13, 2020 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [8ba74bb2b0](https://linux-hardware.org/?probe=8ba74bb2b0) | Jan 13, 2020 |
| Sony          | VGN-FW21M                   | Notebook    | [cda530b21f](https://linux-hardware.org/?probe=cda530b21f) | Jan 12, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [56d01c2d20](https://linux-hardware.org/?probe=56d01c2d20) | Jan 12, 2020 |
| HP            | 650                         | Notebook    | [41d463f623](https://linux-hardware.org/?probe=41d463f623) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | Notebook    | [b883b5c1af](https://linux-hardware.org/?probe=b883b5c1af) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | Notebook    | [76920bc1b7](https://linux-hardware.org/?probe=76920bc1b7) | Jan 03, 2020 |
| AMD           | 970A-UD3                    | Desktop     | [d1e093d616](https://linux-hardware.org/?probe=d1e093d616) | Jan 02, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [99f3d96106](https://linux-hardware.org/?probe=99f3d96106) | Dec 31, 2019 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d572c7a12](https://linux-hardware.org/?probe=4d572c7a12) | Dec 31, 2019 |
| MSI           | B150M BAZOOKA               | Desktop     | [3c0ca553e1](https://linux-hardware.org/?probe=3c0ca553e1) | Dec 30, 2019 |
| ASRock        | X370 Gaming X               | Desktop     | [035469bb6f](https://linux-hardware.org/?probe=035469bb6f) | Dec 29, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [1a90ac4588](https://linux-hardware.org/?probe=1a90ac4588) | Dec 26, 2019 |
| ASRock        | X370 Gaming X               | Desktop     | [5e8a739106](https://linux-hardware.org/?probe=5e8a739106) | Dec 26, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [966b8a2a9a](https://linux-hardware.org/?probe=966b8a2a9a) | Dec 23, 2019 |
| ASUSTek       | X551MA                      | Notebook    | [cc9b263062](https://linux-hardware.org/?probe=cc9b263062) | Dec 23, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [d1c32bf428](https://linux-hardware.org/?probe=d1c32bf428) | Dec 21, 2019 |
| HP            | EliteBook 8460p             | Notebook    | [00c6afae23](https://linux-hardware.org/?probe=00c6afae23) | Dec 19, 2019 |
| Acer          | Aspire A315-31              | Notebook    | [702d379dd6](https://linux-hardware.org/?probe=702d379dd6) | Dec 17, 2019 |
| ASUSTek       | M2A-MX                      | Desktop     | [487090e1b2](https://linux-hardware.org/?probe=487090e1b2) | Dec 17, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [6498ff99ee](https://linux-hardware.org/?probe=6498ff99ee) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [b27320fd81](https://linux-hardware.org/?probe=b27320fd81) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [38e30cfe23](https://linux-hardware.org/?probe=38e30cfe23) | Dec 14, 2019 |
| MSI           | B150M BAZOOKA               | Desktop     | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| HP            | 158B                        | Desktop     | [7a65e2f97f](https://linux-hardware.org/?probe=7a65e2f97f) | Dec 11, 2019 |
| Insyde        | CherryTrail                 | Notebook    | [deeda709d2](https://linux-hardware.org/?probe=deeda709d2) | Dec 07, 2019 |
| Insyde        | CherryTrail                 | Notebook    | [81201a03c1](https://linux-hardware.org/?probe=81201a03c1) | Dec 07, 2019 |
| HP            | 650                         | Notebook    | [1433fef646](https://linux-hardware.org/?probe=1433fef646) | Dec 03, 2019 |
| HP            | 650                         | Notebook    | [2a96c9ca75](https://linux-hardware.org/?probe=2a96c9ca75) | Dec 03, 2019 |
| HP            | 650                         | Notebook    | [9e558b592d](https://linux-hardware.org/?probe=9e558b592d) | Dec 03, 2019 |
| HP            | 650                         | Notebook    | [4a1d85a63b](https://linux-hardware.org/?probe=4a1d85a63b) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [4db92d49fe](https://linux-hardware.org/?probe=4db92d49fe) | Nov 30, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [495e998bda](https://linux-hardware.org/?probe=495e998bda) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | Notebook    | [d73b2ac7d1](https://linux-hardware.org/?probe=d73b2ac7d1) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | Notebook    | [20a9604e39](https://linux-hardware.org/?probe=20a9604e39) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5fd6ae6ef8](https://linux-hardware.org/?probe=5fd6ae6ef8) | Nov 28, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [bf342390e8](https://linux-hardware.org/?probe=bf342390e8) | Nov 24, 2019 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [d4897620b7](https://linux-hardware.org/?probe=d4897620b7) | Nov 22, 2019 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [68e4b5b760](https://linux-hardware.org/?probe=68e4b5b760) | Nov 22, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Dell          | Precision M3800             | Notebook    | [b133f93faa](https://linux-hardware.org/?probe=b133f93faa) | Nov 10, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [673d423adc](https://linux-hardware.org/?probe=673d423adc) | Nov 10, 2019 |
| MSI           | B450 TOMAHAWK               | Desktop     | [5ac9ac64f7](https://linux-hardware.org/?probe=5ac9ac64f7) | Nov 05, 2019 |
| Toshiba       | Satellite L50D-B            | Notebook    | [eb4b70f853](https://linux-hardware.org/?probe=eb4b70f853) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | Notebook    | [231e9df41d](https://linux-hardware.org/?probe=231e9df41d) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | Notebook    | [3b759734b2](https://linux-hardware.org/?probe=3b759734b2) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | Notebook    | [fe505beff6](https://linux-hardware.org/?probe=fe505beff6) | Nov 03, 2019 |
| Pegatron      | A15                         | Notebook    | [291f1aae6d](https://linux-hardware.org/?probe=291f1aae6d) | Oct 29, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [87a279150a](https://linux-hardware.org/?probe=87a279150a) | Oct 26, 2019 |
| Gigabyte      | H57M-USB3                   | Desktop     | [6929a58c82](https://linux-hardware.org/?probe=6929a58c82) | Oct 26, 2019 |
| Gigabyte      | H57M-USB3                   | Desktop     | [2b6c5d66f8](https://linux-hardware.org/?probe=2b6c5d66f8) | Oct 26, 2019 |
| Gigabyte      | nVidia-nForce2              | Desktop     | [38f4bb47c3](https://linux-hardware.org/?probe=38f4bb47c3) | Oct 26, 2019 |
| HP            | 630                         | Notebook    | [99ab4364d4](https://linux-hardware.org/?probe=99ab4364d4) | Oct 26, 2019 |
| Acer          | AOD270                      | Notebook    | [fbe9c7eee3](https://linux-hardware.org/?probe=fbe9c7eee3) | Oct 25, 2019 |
| Acer          | AOD270                      | Notebook    | [a00a0bd225](https://linux-hardware.org/?probe=a00a0bd225) | Oct 25, 2019 |
| Acer          | AOD270                      | Notebook    | [1797ad8387](https://linux-hardware.org/?probe=1797ad8387) | Oct 25, 2019 |
| Acer          | AOD270                      | Notebook    | [cfabf3084a](https://linux-hardware.org/?probe=cfabf3084a) | Oct 25, 2019 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [b6fa3d93af](https://linux-hardware.org/?probe=b6fa3d93af) | Oct 24, 2019 |
| HP            | Presario CQ57               | Notebook    | [758c395c78](https://linux-hardware.org/?probe=758c395c78) | Oct 23, 2019 |
| Acer          | AOD270                      | Notebook    | [1ae1144336](https://linux-hardware.org/?probe=1ae1144336) | Oct 19, 2019 |
| HP            | 3032h                       | Desktop     | [670f34074b](https://linux-hardware.org/?probe=670f34074b) | Oct 13, 2019 |
| HP            | 3032h                       | Desktop     | [aa6e54190f](https://linux-hardware.org/?probe=aa6e54190f) | Oct 13, 2019 |
| HP            | 3032h                       | Desktop     | [215daab3cb](https://linux-hardware.org/?probe=215daab3cb) | Oct 10, 2019 |
| HP            | 3032h                       | Desktop     | [61a5b05c99](https://linux-hardware.org/?probe=61a5b05c99) | Oct 06, 2019 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [44c4d203a8](https://linux-hardware.org/?probe=44c4d203a8) | Oct 05, 2019 |
| Sony          | SVE1512C6EW                 | Notebook    | [cc73d5214f](https://linux-hardware.org/?probe=cc73d5214f) | Sep 23, 2019 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7a646cb519](https://linux-hardware.org/?probe=7a646cb519) | Sep 20, 2019 |
| ASRock        | ConRoe1333-DVI/H            | Desktop     | [b7a267e0d3](https://linux-hardware.org/?probe=b7a267e0d3) | Sep 14, 2019 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [16ac788014](https://linux-hardware.org/?probe=16ac788014) | Sep 11, 2019 |
| Lenovo        | N22 80S6                    | Notebook    | [5850aa007f](https://linux-hardware.org/?probe=5850aa007f) | Sep 09, 2019 |
| Toshiba       | Satellite S855D             | Notebook    | [b0e8c02a13](https://linux-hardware.org/?probe=b0e8c02a13) | Sep 07, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [dad09e76f4](https://linux-hardware.org/?probe=dad09e76f4) | Sep 05, 2019 |
| ASRock        | H97M Pro4                   | Desktop     | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| HP            | Compaq Presario C700        | Notebook    | [f05eb74bea](https://linux-hardware.org/?probe=f05eb74bea) | Aug 31, 2019 |
| ASUSTek       | M2A-VM                      | Desktop     | [fd2fe6e6aa](https://linux-hardware.org/?probe=fd2fe6e6aa) | Aug 31, 2019 |
| HP            | Pavilion 15                 | Notebook    | [2f3cb20593](https://linux-hardware.org/?probe=2f3cb20593) | Aug 30, 2019 |
| Lenovo        | G550 20023                  | Notebook    | [d6126ff072](https://linux-hardware.org/?probe=d6126ff072) | Aug 30, 2019 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [d266d501ce](https://linux-hardware.org/?probe=d266d501ce) | Aug 27, 2019 |
| MSI           | 760GMA-P34                  | Desktop     | [e1cae3d6ee](https://linux-hardware.org/?probe=e1cae3d6ee) | Aug 24, 2019 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [bd54ee5e91](https://linux-hardware.org/?probe=bd54ee5e91) | Aug 20, 2019 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [2b457352c9](https://linux-hardware.org/?probe=2b457352c9) | Aug 17, 2019 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [5a16d7bc77](https://linux-hardware.org/?probe=5a16d7bc77) | Aug 14, 2019 |
| MiTAC         | PH10CI AAG92370-404         | All in one  | [da0c20fdf7](https://linux-hardware.org/?probe=da0c20fdf7) | Aug 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [61616fc1bf](https://linux-hardware.org/?probe=61616fc1bf) | Aug 10, 2019 |
| HP            | Pavilion 15                 | Notebook    | [dc6c804e81](https://linux-hardware.org/?probe=dc6c804e81) | Jul 26, 2019 |
| HP            | Pavilion 15                 | Notebook    | [3652e8f3c6](https://linux-hardware.org/?probe=3652e8f3c6) | Jul 26, 2019 |
| MSI           | MS-7309                     | Desktop     | [11d0376265](https://linux-hardware.org/?probe=11d0376265) | Jul 23, 2019 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [cdabcf84b6](https://linux-hardware.org/?probe=cdabcf84b6) | Jul 23, 2019 |
| ASRock        | 4Core1600P35-WiFi           | Desktop     | [878d54b863](https://linux-hardware.org/?probe=878d54b863) | Jul 21, 2019 |
| ASRock        | 4Core1600P35-WiFi           | Desktop     | [ec13c0e333](https://linux-hardware.org/?probe=ec13c0e333) | Jul 21, 2019 |
| ASRock        | 4Core1600P35-WiFi           | Desktop     | [d3d4f6ec9a](https://linux-hardware.org/?probe=d3d4f6ec9a) | Jul 21, 2019 |
| Pegatron      | A15                         | Notebook    | [1b6dcb6a34](https://linux-hardware.org/?probe=1b6dcb6a34) | Jul 20, 2019 |
| Lenovo        | N22 80S6                    | Notebook    | [5d140c644e](https://linux-hardware.org/?probe=5d140c644e) | Jul 19, 2019 |
| Lenovo        | N22 80S6                    | Notebook    | [a22adedc47](https://linux-hardware.org/?probe=a22adedc47) | Jul 19, 2019 |
| Lenovo        | N22 80S6                    | Notebook    | [97f993a2ca](https://linux-hardware.org/?probe=97f993a2ca) | Jul 19, 2019 |
| ASUSTek       | P6T                         | Desktop     | [42cc2f59e6](https://linux-hardware.org/?probe=42cc2f59e6) | Jul 17, 2019 |
| ASUSTek       | P6T                         | Desktop     | [6d2ab78f42](https://linux-hardware.org/?probe=6d2ab78f42) | Jul 16, 2019 |
| Packard Be... | EasyNote MH35               | Notebook    | [eb538975bd](https://linux-hardware.org/?probe=eb538975bd) | Jul 13, 2019 |
| HP            | Pavilion zd8000 (EL033EA... | Notebook    | [91c7ae2180](https://linux-hardware.org/?probe=91c7ae2180) | Jul 12, 2019 |
| MSI           | H61M-P21                    | Desktop     | [cbe52d9e29](https://linux-hardware.org/?probe=cbe52d9e29) | Jul 02, 2019 |
| E-shop.gr     | Innovator M1479C            | Tablet      | [ef78567252](https://linux-hardware.org/?probe=ef78567252) | Jun 21, 2019 |
| HP            | Compaq Presario CQ60        | Notebook    | [265a212fdc](https://linux-hardware.org/?probe=265a212fdc) | Jun 02, 2019 |
| HP            | Compaq Presario CQ60        | Notebook    | [324a4ad8f5](https://linux-hardware.org/?probe=324a4ad8f5) | Jun 02, 2019 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [9ec349ffc5](https://linux-hardware.org/?probe=9ec349ffc5) | Jun 02, 2019 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [7afdd3951c](https://linux-hardware.org/?probe=7afdd3951c) | Jun 01, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [5834730131](https://linux-hardware.org/?probe=5834730131) | May 31, 2019 |
| HP            | Compaq Presario CQ60        | Notebook    | [4e935854b3](https://linux-hardware.org/?probe=4e935854b3) | May 26, 2019 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [f2dffd30f5](https://linux-hardware.org/?probe=f2dffd30f5) | May 26, 2019 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [a8db92bb48](https://linux-hardware.org/?probe=a8db92bb48) | May 23, 2019 |
| ASUSTek       | STRIKER II NSE              | Desktop     | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock        | H97M Pro4                   | Desktop     | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [b823e3b7d6](https://linux-hardware.org/?probe=b823e3b7d6) | May 16, 2019 |
| HP            | 3032h                       | Desktop     | [68675fa918](https://linux-hardware.org/?probe=68675fa918) | May 16, 2019 |
| HP            | 3032h                       | Desktop     | [6e5ef629d4](https://linux-hardware.org/?probe=6e5ef629d4) | May 14, 2019 |
| MSI           | GE70 2PC                    | Notebook    | [347632684e](https://linux-hardware.org/?probe=347632684e) | May 10, 2019 |
| Unknown       | Unknown                     | Desktop     | [03322637f9](https://linux-hardware.org/?probe=03322637f9) | May 07, 2019 |
| Dell          | Inspiron 3537               | Notebook    | [b57530d6a4](https://linux-hardware.org/?probe=b57530d6a4) | May 07, 2019 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | Notebook    | [bf6bd6c60d](https://linux-hardware.org/?probe=bf6bd6c60d) | May 06, 2019 |
| Dell          | 0GXM1W A02                  | Desktop     | [1845f7e294](https://linux-hardware.org/?probe=1845f7e294) | May 05, 2019 |
| Fujitsu Si... | AMILO Xi 2428               | Notebook    | [7f4acc9070](https://linux-hardware.org/?probe=7f4acc9070) | May 03, 2019 |
| HP            | 3032h                       | Desktop     | [082db53390](https://linux-hardware.org/?probe=082db53390) | May 01, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [5913b022e4](https://linux-hardware.org/?probe=5913b022e4) | May 01, 2019 |
| HP            | 3032h                       | Desktop     | [d6a1c354eb](https://linux-hardware.org/?probe=d6a1c354eb) | May 01, 2019 |
| HP            | 3032h                       | Desktop     | [1478d41aec](https://linux-hardware.org/?probe=1478d41aec) | Apr 30, 2019 |
| HP            | 3032h                       | Desktop     | [39514177b3](https://linux-hardware.org/?probe=39514177b3) | Apr 30, 2019 |
| Toshiba       | Satellite S855D             | Notebook    | [134772dba8](https://linux-hardware.org/?probe=134772dba8) | Apr 30, 2019 |
| ASRock        | 970 Extreme4                | Desktop     | [6d8f048eff](https://linux-hardware.org/?probe=6d8f048eff) | Apr 29, 2019 |
| Toshiba       | Satellite S855D             | Notebook    | [5dd018b04a](https://linux-hardware.org/?probe=5dd018b04a) | Apr 28, 2019 |
| Toshiba       | Satellite S855D             | Notebook    | [6cfd5556fd](https://linux-hardware.org/?probe=6cfd5556fd) | Apr 28, 2019 |
| Toshiba       | Satellite S855D             | Notebook    | [b1213b7b31](https://linux-hardware.org/?probe=b1213b7b31) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | Notebook    | [90cf61c66f](https://linux-hardware.org/?probe=90cf61c66f) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | Notebook    | [820530546d](https://linux-hardware.org/?probe=820530546d) | Apr 28, 2019 |
| Pegatron      | Maureen                     | Desktop     | [ef835695b4](https://linux-hardware.org/?probe=ef835695b4) | Apr 25, 2019 |
| HP            | Pavilion g6                 | Notebook    | [50125f8815](https://linux-hardware.org/?probe=50125f8815) | Apr 25, 2019 |
| Dell          | Inspiron 5323               | Notebook    | [d25db8c5f1](https://linux-hardware.org/?probe=d25db8c5f1) | Apr 24, 2019 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f445f1b326](https://linux-hardware.org/?probe=f445f1b326) | Apr 23, 2019 |
| Dell          | 0F8096                      | Desktop     | [16ed8f93ee](https://linux-hardware.org/?probe=16ed8f93ee) | Apr 21, 2019 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [6881cfb846](https://linux-hardware.org/?probe=6881cfb846) | Apr 20, 2019 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6ef1bc0546](https://linux-hardware.org/?probe=6ef1bc0546) | Apr 19, 2019 |
| HP            | 3032h                       | Desktop     | [4ced55ed9e](https://linux-hardware.org/?probe=4ced55ed9e) | Apr 19, 2019 |
| HP            | 3032h                       | Desktop     | [ddae5ccdc7](https://linux-hardware.org/?probe=ddae5ccdc7) | Apr 18, 2019 |
| HP            | 3032h                       | Desktop     | [59e123a749](https://linux-hardware.org/?probe=59e123a749) | Apr 18, 2019 |
| HP            | 3032h                       | Desktop     | [c8c20910c3](https://linux-hardware.org/?probe=c8c20910c3) | Apr 18, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [b028e3e4f9](https://linux-hardware.org/?probe=b028e3e4f9) | Apr 18, 2019 |
| HP            | 3032h                       | Desktop     | [b9ec07b051](https://linux-hardware.org/?probe=b9ec07b051) | Apr 18, 2019 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [146663e5c0](https://linux-hardware.org/?probe=146663e5c0) | Apr 17, 2019 |
| Dell          | 0WMJ54 A01                  | Desktop     | [427e22d196](https://linux-hardware.org/?probe=427e22d196) | Apr 17, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [20df40c66d](https://linux-hardware.org/?probe=20df40c66d) | Apr 11, 2019 |
| Intel         | DQ67EP AAG12529-308         | Desktop     | [93a39661ec](https://linux-hardware.org/?probe=93a39661ec) | Apr 10, 2019 |
| Gigabyte      | X48-DS5                     | Desktop     | [79a097bf6f](https://linux-hardware.org/?probe=79a097bf6f) | Apr 07, 2019 |
| Info Quest... | GTN1408                     | Notebook    | [968a29d212](https://linux-hardware.org/?probe=968a29d212) | Apr 06, 2019 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f91e0fbe6b](https://linux-hardware.org/?probe=f91e0fbe6b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | Notebook    | [72dfd27f3b](https://linux-hardware.org/?probe=72dfd27f3b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | Notebook    | [7dfc4ddd35](https://linux-hardware.org/?probe=7dfc4ddd35) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | Notebook    | [bfc5bebd38](https://linux-hardware.org/?probe=bfc5bebd38) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | Notebook    | [b0a5ef56cb](https://linux-hardware.org/?probe=b0a5ef56cb) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | Notebook    | [4d7df702b8](https://linux-hardware.org/?probe=4d7df702b8) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | Notebook    | [1b08ea07c0](https://linux-hardware.org/?probe=1b08ea07c0) | Apr 05, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [648c433823](https://linux-hardware.org/?probe=648c433823) | Apr 04, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [2a14e96053](https://linux-hardware.org/?probe=2a14e96053) | Mar 30, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [cba4a3e3be](https://linux-hardware.org/?probe=cba4a3e3be) | Mar 30, 2019 |
| ASUSTek       | P5QL-E                      | Desktop     | [d4c43a54e2](https://linux-hardware.org/?probe=d4c43a54e2) | Mar 29, 2019 |
| ASUSTek       | A88XM-A                     | Desktop     | [0f01674bb9](https://linux-hardware.org/?probe=0f01674bb9) | Mar 28, 2019 |
| ASUSTek       | P5QL-E                      | Desktop     | [feee6b6b4b](https://linux-hardware.org/?probe=feee6b6b4b) | Mar 26, 2019 |
| ASUSTek       | P5QL-E                      | Desktop     | [2db3c1a436](https://linux-hardware.org/?probe=2db3c1a436) | Mar 26, 2019 |
| ASUSTek       | P5QL-E                      | Desktop     | [4fc067190a](https://linux-hardware.org/?probe=4fc067190a) | Mar 26, 2019 |
| Dell          | Inspiron 3576               | Notebook    | [132c5c22bb](https://linux-hardware.org/?probe=132c5c22bb) | Mar 24, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a660f1deba](https://linux-hardware.org/?probe=a660f1deba) | Mar 23, 2019 |
| Dell          | 0YXT71 A02                  | Desktop     | [bd2634142d](https://linux-hardware.org/?probe=bd2634142d) | Mar 21, 2019 |
| Dell          | Inspiron 3576               | Notebook    | [df5ad730b4](https://linux-hardware.org/?probe=df5ad730b4) | Mar 18, 2019 |
| Dell          | Inspiron 3576               | Notebook    | [a88f966e70](https://linux-hardware.org/?probe=a88f966e70) | Mar 18, 2019 |
| ASUSTek       | Rampage III GENE            | Desktop     | [a3dc9e143a](https://linux-hardware.org/?probe=a3dc9e143a) | Mar 17, 2019 |
| Intel         | D875PBZ AAC26680-303        | Desktop     | [399fe679ce](https://linux-hardware.org/?probe=399fe679ce) | Mar 16, 2019 |
| Toshiba       | Satellite C660D             | Notebook    | [884f236bc9](https://linux-hardware.org/?probe=884f236bc9) | Mar 14, 2019 |
| Toshiba       | Satellite C660D             | Notebook    | [ec10f22ef4](https://linux-hardware.org/?probe=ec10f22ef4) | Mar 12, 2019 |
| Sony          | VGN-SZ71XN_C                | Notebook    | [afbc222743](https://linux-hardware.org/?probe=afbc222743) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | Notebook    | [37cc1206c6](https://linux-hardware.org/?probe=37cc1206c6) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | Notebook    | [75a71aa3ec](https://linux-hardware.org/?probe=75a71aa3ec) | Mar 10, 2019 |
| Gigabyte      | B75-D3V                     | Desktop     | [e8b0d211d6](https://linux-hardware.org/?probe=e8b0d211d6) | Mar 08, 2019 |
| ASUSTek       | X555BA                      | Notebook    | [79a6f78b23](https://linux-hardware.org/?probe=79a6f78b23) | Mar 07, 2019 |
| Acer          | Aspire 5935                 | Notebook    | [454098b840](https://linux-hardware.org/?probe=454098b840) | Mar 04, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [f494cc6bb9](https://linux-hardware.org/?probe=f494cc6bb9) | Mar 03, 2019 |
| HP            | Pavilion dv5                | Notebook    | [cfd60bad2b](https://linux-hardware.org/?probe=cfd60bad2b) | Feb 23, 2019 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f1426dc86a](https://linux-hardware.org/?probe=f1426dc86a) | Feb 19, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f4642a0a54](https://linux-hardware.org/?probe=f4642a0a54) | Feb 17, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [bf3ef7e629](https://linux-hardware.org/?probe=bf3ef7e629) | Feb 17, 2019 |
| Dell          | Inspiron 5555               | Notebook    | [65100107dc](https://linux-hardware.org/?probe=65100107dc) | Feb 16, 2019 |
| HP            | 15                          | Notebook    | [30a42ae5dc](https://linux-hardware.org/?probe=30a42ae5dc) | Feb 13, 2019 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [bd5ed31e84](https://linux-hardware.org/?probe=bd5ed31e84) | Feb 10, 2019 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a60a6e48c0](https://linux-hardware.org/?probe=a60a6e48c0) | Feb 09, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | Notebook    | [5a68cab2c0](https://linux-hardware.org/?probe=5a68cab2c0) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | Notebook    | [d2e0a7dddf](https://linux-hardware.org/?probe=d2e0a7dddf) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | Notebook    | [103dc16b24](https://linux-hardware.org/?probe=103dc16b24) | Jan 24, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [e7121f92f8](https://linux-hardware.org/?probe=e7121f92f8) | Jan 20, 2019 |
| MSI           | MS-7329                     | Desktop     | [0e8628d300](https://linux-hardware.org/?probe=0e8628d300) | Jan 15, 2019 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [2c7c637090](https://linux-hardware.org/?probe=2c7c637090) | Jan 11, 2019 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [b559521683](https://linux-hardware.org/?probe=b559521683) | Jan 11, 2019 |
| ASRock        | G31M-GS                     | Desktop     | [bf12881f79](https://linux-hardware.org/?probe=bf12881f79) | Jan 07, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [5b72be1d6f](https://linux-hardware.org/?probe=5b72be1d6f) | Jan 01, 2019 |
| ASRock        | X470 Master SLI             | Desktop     | [061e4b9d1e](https://linux-hardware.org/?probe=061e4b9d1e) | Jan 01, 2019 |
| ASRock        | X470 Master SLI             | Desktop     | [3c27217608](https://linux-hardware.org/?probe=3c27217608) | Jan 01, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [44d69d32d5](https://linux-hardware.org/?probe=44d69d32d5) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [ac9ae784ed](https://linux-hardware.org/?probe=ac9ae784ed) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [9947b5b177](https://linux-hardware.org/?probe=9947b5b177) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [5100558204](https://linux-hardware.org/?probe=5100558204) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [3cc96f096e](https://linux-hardware.org/?probe=3cc96f096e) | Dec 28, 2018 |
| Dell          | Inspiron 3542               | Notebook    | [a630fe7049](https://linux-hardware.org/?probe=a630fe7049) | Dec 25, 2018 |
| Dell          | Inspiron 3542               | Notebook    | [cd0695d1aa](https://linux-hardware.org/?probe=cd0695d1aa) | Dec 25, 2018 |
| Dell          | Inspiron 3521               | Notebook    | [f56872fdba](https://linux-hardware.org/?probe=f56872fdba) | Dec 15, 2018 |
| Dell          | Inspiron 3521               | Notebook    | [a3e64442a6](https://linux-hardware.org/?probe=a3e64442a6) | Dec 15, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [03420d4e05](https://linux-hardware.org/?probe=03420d4e05) | Dec 03, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [5afd838dfc](https://linux-hardware.org/?probe=5afd838dfc) | Dec 03, 2018 |
| ASRock        | B450 Gaming K4              | Desktop     | [1a8e50aa1b](https://linux-hardware.org/?probe=1a8e50aa1b) | Dec 01, 2018 |
| ASRock        | B450 Gaming K4              | Desktop     | [8dc4fad051](https://linux-hardware.org/?probe=8dc4fad051) | Dec 01, 2018 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [123db2c68f](https://linux-hardware.org/?probe=123db2c68f) | Nov 27, 2018 |
| ASRock        | H97M Pro4                   | Desktop     | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Sony          | VGN-AR41L                   | Notebook    | [e80a4c81ba](https://linux-hardware.org/?probe=e80a4c81ba) | Nov 17, 2018 |
| Sony          | VGN-AR41L                   | Notebook    | [33c85bd949](https://linux-hardware.org/?probe=33c85bd949) | Nov 17, 2018 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [6474c9c0b3](https://linux-hardware.org/?probe=6474c9c0b3) | Nov 13, 2018 |
| HP            | 630                         | Notebook    | [375f1ecc8e](https://linux-hardware.org/?probe=375f1ecc8e) | Nov 11, 2018 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [6995918cdc](https://linux-hardware.org/?probe=6995918cdc) | Nov 06, 2018 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [e5a9a2740a](https://linux-hardware.org/?probe=e5a9a2740a) | Nov 03, 2018 |
| Lenovo        | ThinkPad X201 3680BW9       | Notebook    | [b2ac9f5577](https://linux-hardware.org/?probe=b2ac9f5577) | Nov 03, 2018 |
| HP            | Notebook                    | Notebook    | [643f8c70bb](https://linux-hardware.org/?probe=643f8c70bb) | Oct 30, 2018 |
| Gigabyte      | 965P-DQ6                    | Desktop     | [781abca00d](https://linux-hardware.org/?probe=781abca00d) | Oct 29, 2018 |
| Lenovo        | G700 20251                  | Notebook    | [25cef818bf](https://linux-hardware.org/?probe=25cef818bf) | Oct 22, 2018 |
| HP            | Notebook                    | Notebook    | [8be002c789](https://linux-hardware.org/?probe=8be002c789) | Oct 21, 2018 |
| MSI           | B150M MORTAR                | Desktop     | [889ed60d6d](https://linux-hardware.org/?probe=889ed60d6d) | Oct 11, 2018 |
| HP            | EliteBook 820 G1            | Notebook    | [5ffb2eac69](https://linux-hardware.org/?probe=5ffb2eac69) | Jun 12, 2018 |
| Lenovo        | ThinkPad X230 2320LFG       | Notebook    | [e96e3e911f](https://linux-hardware.org/?probe=e96e3e911f) | Jun 12, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [5bb8093b50](https://linux-hardware.org/?probe=5bb8093b50) | May 30, 2018 |
| Dell          | Latitude D530               | Notebook    | [37fd80baa9](https://linux-hardware.org/?probe=37fd80baa9) | May 18, 2018 |
| Dell          | Latitude D530               | Notebook    | [4a84b665e6](https://linux-hardware.org/?probe=4a84b665e6) | May 18, 2018 |
| Lenovo        | G510 20238                  | Notebook    | [f39685a972](https://linux-hardware.org/?probe=f39685a972) | Apr 22, 2018 |
| HP            | G62                         | Notebook    | [4fd190da5e](https://linux-hardware.org/?probe=4fd190da5e) | Apr 18, 2018 |
| ASUSTek       | M3A79-T DELUXE              | Desktop     | [409b3d680a](https://linux-hardware.org/?probe=409b3d680a) | Dec 15, 2017 |
| ASUSTek       | Rampage III GENE            | Desktop     | [e674cb2a2f](https://linux-hardware.org/?probe=e674cb2a2f) | Dec 07, 2017 |
| Clevo         | W251ESQ/W270ESQ             | Notebook    | [a9eccff022](https://linux-hardware.org/?probe=a9eccff022) | Aug 01, 2017 |
| ASUSTek       | UX31E                       | Notebook    | [6be30c42a9](https://linux-hardware.org/?probe=6be30c42a9) | Jun 28, 2017 |
| Dell          | Inspiron 5558               | Notebook    | [ffc88e7749](https://linux-hardware.org/?probe=ffc88e7749) | Apr 23, 2017 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [fcb3be90ef](https://linux-hardware.org/?probe=fcb3be90ef) | Apr 22, 2017 |
| Toshiba       | TECRA R850                  | Notebook    | [6f44cbe917](https://linux-hardware.org/?probe=6f44cbe917) | Mar 14, 2017 |
| ASUSTek       | Rampage III GENE            | Desktop     | [4863310b3c](https://linux-hardware.org/?probe=4863310b3c) | Mar 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 162       | 16.38%  |
| Ubuntu 18.04      | 125       | 12.64%  |
| OpenMandriva 4.2  | 36        | 3.64%   |
| KDE neon 20.04    | 23        | 2.33%   |
| Ubuntu MATE 20.04 | 20        | 2.02%   |
| Arch Rolling      | 20        | 2.02%   |
| Ubuntu 19.10      | 19        | 1.92%   |
| Linux Mint 19.3   | 19        | 1.92%   |
| Zorin 15          | 16        | 1.62%   |
| Ubuntu MATE 18.04 | 16        | 1.62%   |
| Arch              | 16        | 1.62%   |
| Ubuntu 19.04      | 15        | 1.52%   |
| Pop!_OS 20.04     | 15        | 1.52%   |
| Ubuntu 21.10      | 14        | 1.42%   |
| Manjaro           | 14        | 1.42%   |
| Linux Mint 20.1   | 14        | 1.42%   |
| Xubuntu 18.04     | 13        | 1.31%   |
| Kubuntu 20.04     | 13        | 1.31%   |
| Fedora 35         | 13        | 1.31%   |
| Xubuntu 20.04     | 12        | 1.21%   |
| Linux Mint 20.2   | 12        | 1.21%   |
| Gentoo 2.7        | 12        | 1.21%   |
| Debian 11         | 12        | 1.21%   |
| Zorin 16          | 11        | 1.11%   |
| Ubuntu 21.04      | 11        | 1.11%   |
| ROSA R10          | 11        | 1.11%   |
| Pop!_OS 21.04     | 11        | 1.11%   |
| Debian 10         | 11        | 1.11%   |
| ArcoLinux Rolling | 11        | 1.11%   |
| Ubuntu 16.04      | 9         | 0.91%   |
| Pop!_OS 20.10     | 9         | 0.91%   |
| OpenMandriva 4.3  | 9         | 0.91%   |
| Linux Mint 20     | 9         | 0.91%   |
| Fedora 32         | 9         | 0.91%   |
| Ubuntu 20.10      | 8         | 0.81%   |
| Pop!_OS 21.10     | 8         | 0.81%   |
| Ubuntu 18.10      | 7         | 0.71%   |
| Fedora 33         | 7         | 0.71%   |
| Linux Mint 20.3   | 6         | 0.61%   |
| Fedora 34         | 6         | 0.61%   |
| BlackPanther 18.1 | 6         | 0.61%   |
| Manjaro 20.2      | 5         | 0.51%   |
| LMDE 4            | 5         | 0.51%   |
| Gentoo 2.6        | 5         | 0.51%   |
| ALT Linux 10.0    | 5         | 0.51%   |
| ROSA R8.1         | 4         | 0.4%    |
| ROSA R11          | 4         | 0.4%    |
| Manjaro 20.0.3    | 4         | 0.4%    |
| Linux Mint 19.1   | 4         | 0.4%    |
| Debian Unstable   | 4         | 0.4%    |
| Debian Testing    | 4         | 0.4%    |
| Xero Rolling      | 3         | 0.3%    |
| ROSA R9           | 3         | 0.3%    |
| OpenMandriva 4.50 | 3         | 0.3%    |
| Manjaro 21.1.6    | 3         | 0.3%    |
| Manjaro 20.1      | 3         | 0.3%    |
| Lubuntu 20.04     | 3         | 0.3%    |
| LinuxFX 11        | 3         | 0.3%    |
| Linux Mint 19.2   | 3         | 0.3%    |
| Gentoo 2.8        | 3         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 352       | 37.49%  |
| Linux Mint    | 65        | 6.92%   |
| OpenMandriva  | 49        | 5.22%   |
| Pop!_OS       | 41        | 4.37%   |
| Fedora        | 40        | 4.26%   |
| Manjaro       | 39        | 4.15%   |
| Ubuntu MATE   | 37        | 3.94%   |
| Arch          | 35        | 3.73%   |
| Debian        | 30        | 3.19%   |
| Zorin         | 29        | 3.09%   |
| Xubuntu       | 29        | 3.09%   |
| KDE neon      | 25        | 2.66%   |
| ROSA          | 23        | 2.45%   |
| Kubuntu       | 20        | 2.13%   |
| Endless       | 17        | 1.81%   |
| Gentoo        | 14        | 1.49%   |
| ArcoLinux     | 13        | 1.38%   |
| BlackPanther  | 7         | 0.75%   |
| Elementary    | 6         | 0.64%   |
| Lubuntu       | 5         | 0.53%   |
| LMDE          | 5         | 0.53%   |
| ALT Linux     | 5         | 0.53%   |
| openSUSE      | 4         | 0.43%   |
| Kali          | 4         | 0.43%   |
| EndeavourOS   | 4         | 0.43%   |
| Artix         | 4         | 0.43%   |
| Xero          | 3         | 0.32%   |
| Ubuntu Budgie | 3         | 0.32%   |
| Peppermint    | 3         | 0.32%   |
| LinuxFX       | 3         | 0.32%   |
| CentOS        | 3         | 0.32%   |
| Void Linux    | 2         | 0.21%   |
| Solus         | 2         | 0.21%   |
| Slackware     | 2         | 0.21%   |
| Reborn OS     | 2         | 0.21%   |
| MX            | 2         | 0.21%   |
| Mageia        | 2         | 0.21%   |
| Raspbian      | 1         | 0.11%   |
| Parrot        | 1         | 0.11%   |
| GNOME OS      | 1         | 0.11%   |
| Garuda Linux  | 1         | 0.11%   |
| Devuan        | 1         | 0.11%   |
| Deepin        | 1         | 0.11%   |
| Clear Linux   | 1         | 0.11%   |
| Chrome OS     | 1         | 0.11%   |
| BlackArch     | 1         | 0.11%   |
| antiX         | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 35        | 3.19%   |
| 5.4.0-58-generic                | 20        | 1.82%   |
| 5.4.0-42-generic                | 19        | 1.73%   |
| 5.4.0-29-generic                | 14        | 1.28%   |
| 4.15.0-163-generic              | 14        | 1.28%   |
| 5.4.0-94-generic                | 13        | 1.19%   |
| 5.4.0-54-generic                | 11        | 1%      |
| 5.4.0-48-generic                | 11        | 1%      |
| 5.3.0-46-generic                | 11        | 1%      |
| 5.11.0-40-generic               | 11        | 1%      |
| 5.4.0-65-generic                | 10        | 0.91%   |
| 5.4.0-52-generic                | 10        | 0.91%   |
| 4.15.0-47-generic               | 10        | 0.91%   |
| 5.4.0-91-generic                | 9         | 0.82%   |
| 5.3.0-51-generic                | 9         | 0.82%   |
| 5.16.7-desktop-1omv4003         | 9         | 0.82%   |
| 5.4.0-56-generic                | 8         | 0.73%   |
| 5.4.0-40-generic                | 8         | 0.73%   |
| 5.4.0-37-generic                | 8         | 0.73%   |
| 5.3.0-45-generic                | 8         | 0.73%   |
| 5.3.0-42-generic                | 8         | 0.73%   |
| 5.11.0-38-generic               | 8         | 0.73%   |
| 5.11.0-37-generic               | 8         | 0.73%   |
| 5.0.0-37-generic                | 8         | 0.73%   |
| 5.0.0-13-generic                | 8         | 0.73%   |
| 4.15.0-45-generic               | 8         | 0.73%   |
| 5.8.0-43-generic                | 7         | 0.64%   |
| 5.4.0-53-generic                | 7         | 0.64%   |
| 5.3.0-28-generic                | 7         | 0.64%   |
| 5.13.0-39-generic               | 7         | 0.64%   |
| 5.8.0-55-generic                | 6         | 0.55%   |
| 5.4.0-72-generic                | 6         | 0.55%   |
| 5.4.0-66-generic                | 6         | 0.55%   |
| 5.4.0-59-generic                | 6         | 0.55%   |
| 5.4.0-47-generic                | 6         | 0.55%   |
| 5.4.0-26-generic                | 6         | 0.55%   |
| 5.11.0-7620-generic             | 6         | 0.55%   |
| 5.11.0-7614-generic             | 6         | 0.55%   |
| 5.0.0-25-generic                | 6         | 0.55%   |
| 5.0.0-23-generic                | 6         | 0.55%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 6         | 0.55%   |
| 4.18.0-25-generic               | 6         | 0.55%   |
| 5.8.0-7630-generic              | 5         | 0.46%   |
| 5.8.0-59-generic                | 5         | 0.46%   |
| 5.8.0-53-generic                | 5         | 0.46%   |
| 5.8.0-48-generic                | 5         | 0.46%   |
| 5.4.0-33-generic                | 5         | 0.46%   |
| 5.3.0-59-generic                | 5         | 0.46%   |
| 5.3.0-40-generic                | 5         | 0.46%   |
| 5.13.0-30-generic               | 5         | 0.46%   |
| 5.13.0-27-generic               | 5         | 0.46%   |
| 5.11.0-46-generic               | 5         | 0.46%   |
| 4.18.16-desktop-1bP             | 5         | 0.46%   |
| 4.18.0-17-generic               | 5         | 0.46%   |
| 4.18.0-15-generic               | 5         | 0.46%   |
| 4.15.0-96-generic               | 5         | 0.46%   |
| 4.15.0-50-generic               | 5         | 0.46%   |
| 4.15.0-43-generic               | 5         | 0.46%   |
| 5.8.0-7642-generic              | 4         | 0.36%   |
| 5.8.0-14-generic                | 4         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 229       | 22.34%  |
| 4.15.0  | 106       | 10.34%  |
| 5.11.0  | 82        | 8%      |
| 5.3.0   | 67        | 6.54%   |
| 5.8.0   | 65        | 6.34%   |
| 5.13.0  | 47        | 4.59%   |
| 5.0.0   | 38        | 3.71%   |
| 5.10.14 | 35        | 3.41%   |
| 4.18.0  | 30        | 2.93%   |
| 5.10.0  | 15        | 1.46%   |
| 4.19.0  | 14        | 1.37%   |
| 5.16.7  | 10        | 0.98%   |
| 5.9.11  | 7         | 0.68%   |
| 4.9.60  | 7         | 0.68%   |
| 5.10.88 | 6         | 0.59%   |
| 4.9.20  | 5         | 0.49%   |
| 4.18.16 | 5         | 0.49%   |
| 5.8.18  | 4         | 0.39%   |
| 5.17.1  | 4         | 0.39%   |
| 5.16.0  | 4         | 0.39%   |
| 5.15.32 | 4         | 0.39%   |
| 5.15.0  | 4         | 0.39%   |
| 5.14.14 | 4         | 0.39%   |
| 5.12.4  | 4         | 0.39%   |
| 5.11.12 | 4         | 0.39%   |
| 5.11.11 | 4         | 0.39%   |
| 5.7.2   | 3         | 0.29%   |
| 5.7.0   | 3         | 0.29%   |
| 5.6.10  | 3         | 0.29%   |
| 5.4.77  | 3         | 0.29%   |
| 5.3.18  | 3         | 0.29%   |
| 5.15.5  | 3         | 0.29%   |
| 5.15.19 | 3         | 0.29%   |
| 5.14.10 | 3         | 0.29%   |
| 5.10.33 | 3         | 0.29%   |
| 5.9.16  | 2         | 0.2%    |
| 5.9.14  | 2         | 0.2%    |
| 5.9.1   | 2         | 0.2%    |
| 5.9.0   | 2         | 0.2%    |
| 5.8.7   | 2         | 0.2%    |
| 5.8.6   | 2         | 0.2%    |
| 5.8.5   | 2         | 0.2%    |
| 5.8.16  | 2         | 0.2%    |
| 5.8.14  | 2         | 0.2%    |
| 5.8.11  | 2         | 0.2%    |
| 5.6.6   | 2         | 0.2%    |
| 5.6.14  | 2         | 0.2%    |
| 5.6.11  | 2         | 0.2%    |
| 5.5.13  | 2         | 0.2%    |
| 5.4.83  | 2         | 0.2%    |
| 5.4.52  | 2         | 0.2%    |
| 5.4.18  | 2         | 0.2%    |
| 5.17.4  | 2         | 0.2%    |
| 5.16.11 | 2         | 0.2%    |
| 5.15.7  | 2         | 0.2%    |
| 5.15.24 | 2         | 0.2%    |
| 5.15.16 | 2         | 0.2%    |
| 5.15.15 | 2         | 0.2%    |
| 5.14.16 | 2         | 0.2%    |
| 5.14.0  | 2         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 250       | 24.73%  |
| 4.15    | 106       | 10.48%  |
| 5.11    | 99        | 9.79%   |
| 5.8     | 86        | 8.51%   |
| 5.10    | 86        | 8.51%   |
| 5.3     | 73        | 7.22%   |
| 5.13    | 53        | 5.24%   |
| 5.0     | 42        | 4.15%   |
| 4.18    | 36        | 3.56%   |
| 5.15    | 30        | 2.97%   |
| 5.16    | 23        | 2.27%   |
| 5.9     | 19        | 1.88%   |
| 5.14    | 15        | 1.48%   |
| 4.19    | 15        | 1.48%   |
| 5.6     | 14        | 1.38%   |
| 4.9     | 14        | 1.38%   |
| 5.7     | 12        | 1.19%   |
| 5.12    | 10        | 0.99%   |
| 5.17    | 9         | 0.89%   |
| 5.5     | 7         | 0.69%   |
| 4.4     | 2         | 0.2%    |
| 4.1     | 2         | 0.2%    |
| 5.2     | 1         | 0.1%    |
| 5.1     | 1         | 0.1%    |
| 4.20    | 1         | 0.1%    |
| 4.16    | 1         | 0.1%    |
| 4.14    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |
| 3.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 849       | 93.81%  |
| i686    | 52        | 5.75%   |
| aarch64 | 3         | 0.33%   |
| armv6l  | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| GNOME               | 387       | 40.74%  |
| Unknown             | 147       | 15.47%  |
| KDE5                | 128       | 13.47%  |
| XFCE                | 84        | 8.84%   |
| X-Cinnamon          | 56        | 5.89%   |
| MATE                | 50        | 5.26%   |
| KDE                 | 37        | 3.89%   |
| KDE4                | 13        | 1.37%   |
| Unity               | 9         | 0.95%   |
| LXQt                | 6         | 0.63%   |
| Budgie              | 6         | 0.63%   |
| Pantheon            | 5         | 0.53%   |
| i3                  | 5         | 0.53%   |
| Cinnamon            | 5         | 0.53%   |
| LXDE                | 3         | 0.32%   |
| openbox             | 2         | 0.21%   |
| GNOME Classic       | 2         | 0.21%   |
| herbstluftwm        | 1         | 0.11%   |
| GNOME Flashback     | 1         | 0.11%   |
| Deepin              | 1         | 0.11%   |
| awesome             | 1         | 0.11%   |
| /usr/bin/startxfce4 | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 761       | 81.92%  |
| Unknown | 84        | 9.04%   |
| Wayland | 66        | 7.1%    |
| Tty     | 18        | 1.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 564       | 60%     |
| SDDM    | 118       | 12.55%  |
| GDM     | 86        | 9.15%   |
| LightDM | 85        | 9.04%   |
| GDM3    | 45        | 4.79%   |
| TDM     | 24        | 2.55%   |
| KDM     | 13        | 1.38%   |
| XDM     | 2         | 0.21%   |
| SLiM    | 2         | 0.21%   |
| Ly      | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 471       | 50.54%  |
| el_GR   | 265       | 28.43%  |
| Unknown | 144       | 15.45%  |
| en_GB   | 19        | 2.04%   |
| C       | 10        | 1.07%   |
| de_DE   | 8         | 0.86%   |
| ru_RU   | 3         | 0.32%   |
| POSIX   | 2         | 0.21%   |
| fr_FR   | 2         | 0.21%   |
| unm_US  | 1         | 0.11%   |
| pl_PL   | 1         | 0.11%   |
| it_IT   | 1         | 0.11%   |
| hu_HU   | 1         | 0.11%   |
| en_IE   | 1         | 0.11%   |
| en_AU   | 1         | 0.11%   |
| C.UTF8  | 1         | 0.11%   |
| anp_IN  | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 548       | 59.12%  |
| EFI  | 379       | 40.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 722       | 77.89%  |
| Overlay | 86        | 9.28%   |
| Btrfs   | 58        | 6.26%   |
| Unknown | 42        | 4.53%   |
| Xfs     | 8         | 0.86%   |
| Zfs     | 5         | 0.54%   |
| F2fs    | 2         | 0.22%   |
| Ext3    | 2         | 0.22%   |
| Tmpfs   | 1         | 0.11%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 605       | 65.76%  |
| GPT     | 208       | 22.61%  |
| MBR     | 107       | 11.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 784       | 84.85%  |
| Yes       | 140       | 15.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 579       | 63.14%  |
| Yes       | 338       | 36.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 146       | 16.13%  |
| ASUSTek Computer        | 137       | 15.14%  |
| Lenovo                  | 116       | 12.82%  |
| Dell                    | 113       | 12.49%  |
| Gigabyte Technology     | 107       | 11.82%  |
| ASRock                  | 45        | 4.97%   |
| Acer                    | 40        | 4.42%   |
| MSI                     | 35        | 3.87%   |
| Toshiba                 | 24        | 2.65%   |
| Sony                    | 23        | 2.54%   |
| Intel                   | 11        | 1.22%   |
| Fujitsu Siemens         | 11        | 1.22%   |
| Fujitsu                 | 9         | 0.99%   |
| Apple                   | 8         | 0.88%   |
| Unknown                 | 7         | 0.77%   |
| Notebook                | 5         | 0.55%   |
| HUAWEI                  | 5         | 0.55%   |
| Clevo                   | 5         | 0.55%   |
| Raspberry Pi Foundation | 4         | 0.44%   |
| Pegatron                | 4         | 0.44%   |
| Foxconn                 | 4         | 0.44%   |
| Teclast                 | 3         | 0.33%   |
| Samsung Electronics     | 3         | 0.33%   |
| IBM                     | 3         | 0.33%   |
| e-shop.gr               | 3         | 0.33%   |
| Chuwi                   | 3         | 0.33%   |
| Insyde                  | 2         | 0.22%   |
| Info Quest Technologies | 2         | 0.22%   |
| Hampoo                  | 2         | 0.22%   |
| ECS                     | 2         | 0.22%   |
| ZOTAC                   | 1         | 0.11%   |
| VIA Technologies        | 1         | 0.11%   |
| VERO                    | 1         | 0.11%   |
| TUXEDO                  | 1         | 0.11%   |
| Supermicro              | 1         | 0.11%   |
| Schenker                | 1         | 0.11%   |
| RuggedPC                | 1         | 0.11%   |
| Quest                   | 1         | 0.11%   |
| QDI                     | 1         | 0.11%   |
| PLAISIO COMPUTERS SA    | 1         | 0.11%   |
| PC Specialist           | 1         | 0.11%   |
| Packard Bell            | 1         | 0.11%   |
| MiTAC                   | 1         | 0.11%   |
| Medion                  | 1         | 0.11%   |
| Google                  | 1         | 0.11%   |
| Gateway                 | 1         | 0.11%   |
| Compal                  | 1         | 0.11%   |
| ARIMA                   | 1         | 0.11%   |
| AOpen                   | 1         | 0.11%   |
| AMD                     | 1         | 0.11%   |
| Alienware               | 1         | 0.11%   |
| Albatron                | 1         | 0.11%   |
| ABIT                    | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 12        | 1.33%   |
| ASUS All Series                        | 11        | 1.22%   |
| HP ProDesk 600 G1 SFF                  | 6         | 0.66%   |
| HP Pavilion g6                         | 6         | 0.66%   |
| HP Notebook                            | 6         | 0.66%   |
| Dell Inspiron 3542                     | 5         | 0.55%   |
| ASRock B450 Gaming K4                  | 5         | 0.55%   |
| HP G62                                 | 4         | 0.44%   |
| HP 255 G7 Notebook PC                  | 4         | 0.44%   |
| Gigabyte H61M-S2PV                     | 4         | 0.44%   |
| Dell OptiPlex GX520                    | 4         | 0.44%   |
| Dell OptiPlex 7010                     | 4         | 0.44%   |
| Dell Inspiron 3537                     | 4         | 0.44%   |
| RPi Raspberry Pi                       | 3         | 0.33%   |
| Lenovo G510 20238                      | 3         | 0.33%   |
| HP Pavilion dv7                        | 3         | 0.33%   |
| HP Compaq 8200 Elite SFF PC            | 3         | 0.33%   |
| Gigabyte G41M-Combo                    | 3         | 0.33%   |
| Gigabyte G31M-S2L                      | 3         | 0.33%   |
| Gigabyte B75M-D3H                      | 3         | 0.33%   |
| Gigabyte B450 AORUS M                  | 3         | 0.33%   |
| Gigabyte B250M-DS3H                    | 3         | 0.33%   |
| Dell OptiPlex GX620                    | 3         | 0.33%   |
| Dell OptiPlex 7040                     | 3         | 0.33%   |
| Dell Inspiron 5567                     | 3         | 0.33%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.33%   |
| ASUS ROG STRIX B350-F GAMING           | 3         | 0.33%   |
| ASUS P6T                               | 3         | 0.33%   |
| Acer Aspire A315-51                    | 3         | 0.33%   |
| Acer Aspire A315-31                    | 3         | 0.33%   |
| Toshiba Satellite C850D-119            | 2         | 0.22%   |
| Toshiba NB100                          | 2         | 0.22%   |
| Teclast F15                            | 2         | 0.22%   |
| Sony VPCM13M1E                         | 2         | 0.22%   |
| Sony VPCCB2S1E                         | 2         | 0.22%   |
| Notebook W54_W94_W955TU,-T,-C          | 2         | 0.22%   |
| MSI MS-7C31                            | 2         | 0.22%   |
| MSI MS-7C02                            | 2         | 0.22%   |
| MSI MS-7B78                            | 2         | 0.22%   |
| MSI MS-7972                            | 2         | 0.22%   |
| Lenovo ThinkCentre M71e 3167A46        | 2         | 0.22%   |
| Lenovo ThinkCentre E73 10AW008MMX      | 2         | 0.22%   |
| Lenovo MIIX 320-10ICR 80XF             | 2         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.22%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.22%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 2         | 0.22%   |
| Lenovo G700 20251                      | 2         | 0.22%   |
| Lenovo G70-35 80Q5                     | 2         | 0.22%   |
| Lenovo G50-70 20351                    | 2         | 0.22%   |
| Lenovo G40-30 80FY                     | 2         | 0.22%   |
| Intel Calistoga & ICH7M Chipset        | 2         | 0.22%   |
| Insyde CherryTrail                     | 2         | 0.22%   |
| HUAWEI NBLK-WAX9X                      | 2         | 0.22%   |
| HP Z820 Workstation                    | 2         | 0.22%   |
| HP ProBook 6560b                       | 2         | 0.22%   |
| HP Pavilion x2 Detachable              | 2         | 0.22%   |
| HP Pavilion Notebook                   | 2         | 0.22%   |
| HP Pavilion 15                         | 2         | 0.22%   |
| HP Laptop 17-ca1xxx                    | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 37        | 4.09%   |
| Lenovo ThinkPad       | 35        | 3.87%   |
| Acer Aspire           | 32        | 3.54%   |
| HP Pavilion           | 30        | 3.31%   |
| Lenovo IdeaPad        | 27        | 2.98%   |
| HP Compaq             | 25        | 2.76%   |
| Dell OptiPlex         | 25        | 2.76%   |
| Dell Latitude         | 25        | 2.76%   |
| Toshiba Satellite     | 21        | 2.32%   |
| Lenovo ThinkCentre    | 17        | 1.88%   |
| ASUS PRIME            | 14        | 1.55%   |
| Unknown               | 12        | 1.33%   |
| ASUS All              | 11        | 1.22%   |
| HP 255                | 10        | 1.1%    |
| HP EliteBook          | 9         | 0.99%   |
| Dell Precision        | 9         | 0.99%   |
| ASUS VivoBook         | 9         | 0.99%   |
| HP Laptop             | 8         | 0.88%   |
| ASUS TUF              | 8         | 0.88%   |
| HP ProDesk            | 7         | 0.77%   |
| HP ProBook            | 7         | 0.77%   |
| Fujitsu Siemens AMILO | 7         | 0.77%   |
| Fujitsu LIFEBOOK      | 7         | 0.77%   |
| ASUS ROG              | 7         | 0.77%   |
| HP Notebook           | 6         | 0.66%   |
| HP ENVY               | 6         | 0.66%   |
| Dell Vostro           | 6         | 0.66%   |
| HP 250                | 5         | 0.55%   |
| Dell XPS              | 5         | 0.55%   |
| ASRock B450           | 5         | 0.55%   |
| RPi Raspberry         | 4         | 0.44%   |
| HP G62                | 4         | 0.44%   |
| Gigabyte H61M-S2PV    | 4         | 0.44%   |
| Gigabyte B450         | 4         | 0.44%   |
| Lenovo Yoga           | 3         | 0.33%   |
| Lenovo MIIX           | 3         | 0.33%   |
| Lenovo Legion         | 3         | 0.33%   |
| Lenovo G510           | 3         | 0.33%   |
| HP Presario           | 3         | 0.33%   |
| HP EliteDesk          | 3         | 0.33%   |
| Gigabyte Z370         | 3         | 0.33%   |
| Gigabyte G41M-Combo   | 3         | 0.33%   |
| Gigabyte G31M-S2L     | 3         | 0.33%   |
| Gigabyte B75M-D3H     | 3         | 0.33%   |
| Gigabyte B250M-DS3H   | 3         | 0.33%   |
| ASUS P6T              | 3         | 0.33%   |
| ASUS P5Q              | 3         | 0.33%   |
| ASUS P5G41T-M         | 3         | 0.33%   |
| Toshiba NB100         | 2         | 0.22%   |
| Teclast F15           | 2         | 0.22%   |
| Sony VPCM13M1E        | 2         | 0.22%   |
| Sony VPCCB2S1E        | 2         | 0.22%   |
| Notebook W65          | 2         | 0.22%   |
| Notebook W54          | 2         | 0.22%   |
| MSI MS-7C31           | 2         | 0.22%   |
| MSI MS-7C02           | 2         | 0.22%   |
| MSI MS-7B78           | 2         | 0.22%   |
| MSI MS-7972           | 2         | 0.22%   |
| MSI GE70              | 2         | 0.22%   |
| Lenovo G700           | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 78        | 8.62%   |
| 2019    | 74        | 8.18%   |
| 2018    | 72        | 7.96%   |
| 2017    | 70        | 7.73%   |
| 2012    | 67        | 7.4%    |
| 2008    | 67        | 7.4%    |
| 2011    | 65        | 7.18%   |
| 2009    | 60        | 6.63%   |
| 2014    | 57        | 6.3%    |
| 2007    | 50        | 5.52%   |
| 2015    | 49        | 5.41%   |
| 2010    | 47        | 5.19%   |
| 2020    | 45        | 4.97%   |
| 2016    | 37        | 4.09%   |
| 2005    | 20        | 2.21%   |
| 2006    | 18        | 1.99%   |
| 2021    | 17        | 1.88%   |
| 2004    | 5         | 0.55%   |
| 2003    | 4         | 0.44%   |
| Unknown | 3         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 484       | 53.48%  |
| Desktop        | 390       | 43.09%  |
| Convertible    | 10        | 1.1%    |
| Tablet         | 7         | 0.77%   |
| System on chip | 4         | 0.44%   |
| All in one     | 4         | 0.44%   |
| Server         | 4         | 0.44%   |
| Mini pc        | 2         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 853       | 93.63%  |
| Enabled  | 58        | 6.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 904       | 99.89%  |
| Yes  | 1         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 259       | 28.15%  |
| 4.01-8.0    | 187       | 20.33%  |
| 8.01-16.0   | 167       | 18.15%  |
| 16.01-24.0  | 131       | 14.24%  |
| 1.01-2.0    | 91        | 9.89%   |
| 2.01-3.0    | 31        | 3.37%   |
| 32.01-64.0  | 30        | 3.26%   |
| 0.51-1.0    | 13        | 1.41%   |
| 64.01-256.0 | 7         | 0.76%   |
| 24.01-32.0  | 3         | 0.33%   |
| 0.01-0.5    | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 417       | 41.53%  |
| 2.01-3.0   | 232       | 23.11%  |
| 0.51-1.0   | 113       | 11.25%  |
| 3.01-4.0   | 99        | 9.86%   |
| 4.01-8.0   | 86        | 8.57%   |
| 8.01-16.0  | 28        | 2.79%   |
| 0.01-0.5   | 23        | 2.29%   |
| 16.01-24.0 | 5         | 0.5%    |
| 24.01-32.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 539       | 58.02%  |
| 2      | 256       | 27.56%  |
| 3      | 65        | 7%      |
| 4      | 34        | 3.66%   |
| 5      | 16        | 1.72%   |
| 6      | 9         | 0.97%   |
| 0      | 7         | 0.75%   |
| 7      | 2         | 0.22%   |
| 12     | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 459       | 50.44%  |
| No        | 451       | 49.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 820       | 90.51%  |
| No        | 86        | 9.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 623       | 68.24%  |
| No        | 290       | 31.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 475       | 51.91%  |
| Yes       | 440       | 48.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Greece  | 905       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Athens         | 474       | 49.02%  |
| Thessaloniki   | 156       | 16.13%  |
| Heraklion      | 17        | 1.76%   |
| Volos          | 15        | 1.55%   |
| Chalcis        | 15        | 1.55%   |
| Larissa        | 14        | 1.45%   |
| Old Faliron    | 12        | 1.24%   |
| Piraeus        | 10        | 1.03%   |
| Kavala         | 10        | 1.03%   |
| Ioannina       | 9         | 0.93%   |
| Chania         | 9         | 0.93%   |
| Xanthi         | 7         | 0.72%   |
| Trikala        | 7         | 0.72%   |
| Lamia          | 7         | 0.72%   |
| PГЎtrai      | 6         | 0.62%   |
| PÃ¡trai      | 6         | 0.62%   |
| Rhodes         | 5         | 0.52%   |
| Katerini       | 5         | 0.52%   |
| Corinth        | 5         | 0.52%   |
| Sparti         | 4         | 0.41%   |
| Ptolemaida     | 4         | 0.41%   |
| Megara         | 4         | 0.41%   |
| Kozani         | 4         | 0.41%   |
| Kalamata       | 4         | 0.41%   |
| Corfu          | 4         | 0.41%   |
| Argostoli      | 4         | 0.41%   |
| Vergina        | 3         | 0.31%   |
| Serres         | 3         | 0.31%   |
| Salamina       | 3         | 0.31%   |
| Rethymno       | 3         | 0.31%   |
| Limnos         | 3         | 0.31%   |
| Keratsini      | 3         | 0.31%   |
| Karlovasi      | 3         | 0.31%   |
| Fira           | 3         | 0.31%   |
| Argos          | 3         | 0.31%   |
| Alexandroupoli | 3         | 0.31%   |
| Zakynthos      | 2         | 0.21%   |
| Veroia         | 2         | 0.21%   |
| Skydra         | 2         | 0.21%   |
| Rafina         | 2         | 0.21%   |
| Peristeri      | 2         | 0.21%   |
| Peraia         | 2         | 0.21%   |
| Paros          | 2         | 0.21%   |
| Nea Moudania   | 2         | 0.21%   |
| Nea Michaniona | 2         | 0.21%   |
| Naousa         | 2         | 0.21%   |
| Mytilene       | 2         | 0.21%   |
| Loutraki       | 2         | 0.21%   |
| Kymi           | 2         | 0.21%   |
| Koropi         | 2         | 0.21%   |
| Kilkis         | 2         | 0.21%   |
| Kiato          | 2         | 0.21%   |
| Karditsa       | 2         | 0.21%   |
| Kamatero       | 2         | 0.21%   |
| Ilioupoli      | 2         | 0.21%   |
| Ierissos       | 2         | 0.21%   |
| Ierapetra      | 2         | 0.21%   |
| Florina        | 2         | 0.21%   |
| Cholargos      | 2         | 0.21%   |
| Ano Syros      | 2         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 261       | 428    | 19.65%  |
| Seagate                        | 201       | 295    | 15.14%  |
| Samsung Electronics            | 158       | 226    | 11.9%   |
| Toshiba                        | 115       | 143    | 8.66%   |
| Kingston                       | 78        | 99     | 5.87%   |
| SanDisk                        | 72        | 95     | 5.42%   |
| Unknown                        | 48        | 85     | 3.61%   |
| Patriot                        | 48        | 55     | 3.61%   |
| Hitachi                        | 40        | 42     | 3.01%   |
| SK Hynix                       | 27        | 38     | 2.03%   |
| Intenso                        | 24        | 29     | 1.81%   |
| HGST                           | 22        | 29     | 1.66%   |
| Intel                          | 21        | 28     | 1.58%   |
| Crucial                        | 20        | 32     | 1.51%   |
| Fujitsu                        | 18        | 18     | 1.36%   |
| Team                           | 16        | 22     | 1.2%    |
| OCZ                            | 13        | 16     | 0.98%   |
| Micron Technology              | 12        | 15     | 0.9%    |
| MAXTOR                         | 11        | 13     | 0.83%   |
| A-DATA Technology              | 11        | 16     | 0.83%   |
| PNY                            | 7         | 7      | 0.53%   |
| Phison                         | 7         | 10     | 0.53%   |
| KIOXIA                         | 7         | 7      | 0.53%   |
| JMicron                        | 7         | 10     | 0.53%   |
| Transcend                      | 5         | 5      | 0.38%   |
| Leven                          | 5         | 5      | 0.38%   |
| Gigabyte Technology            | 5         | 7      | 0.38%   |
| SPCC                           | 4         | 5      | 0.3%    |
| Corsair                        | 4         | 4      | 0.3%    |
| Unknown                        | 4         | 4      | 0.3%    |
| XPG                            | 3         | 4      | 0.23%   |
| Teclast                        | 3         | 3      | 0.23%   |
| Mushkin                        | 3         | 3      | 0.23%   |
| GOODRAM                        | 3         | 5      | 0.23%   |
| EMTEC                          | 3         | 6      | 0.23%   |
| China                          | 3         | 3      | 0.23%   |
| Apple                          | 3         | 3      | 0.23%   |
| Verbatim                       | 2         | 2      | 0.15%   |
| PLEXTOR                        | 2         | 2      | 0.15%   |
| Platinet                       | 2         | 2      | 0.15%   |
| LITEONIT                       | 2         | 2      | 0.15%   |
| Hewlett-Packard                | 2         | 2      | 0.15%   |
| DREVO                          | 2         | 2      | 0.15%   |
| WDC WDS                        | 1         | 1      | 0.08%   |
| USB30                          | 1         | 1      | 0.08%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.08%   |
| SSSTC                          | 1         | 1      | 0.08%   |
| Solid State Storage Technology | 1         | 1      | 0.08%   |
| SMI                            | 1         | 1      | 0.08%   |
| Silicon Motion                 | 1         | 1      | 0.08%   |
| Realtek Semiconductor          | 1         | 2      | 0.08%   |
| QUANTUM                        | 1         | 1      | 0.08%   |
| OCZ-AGIL                       | 1         | 1      | 0.08%   |
| Netac                          | 1         | 1      | 0.08%   |
| Micron/Crucial Technology      | 1         | 1      | 0.08%   |
| LITEON                         | 1         | 1      | 0.08%   |
| Lite-On                        | 1         | 4      | 0.08%   |
| KIOXIA-EXCERIA                 | 1         | 1      | 0.08%   |
| KingSpec                       | 1         | 1      | 0.08%   |
| InnoLite                       | 1         | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB           | 20        | 1.37%   |
| Unknown MMC Card  32GB              | 19        | 1.31%   |
| Kingston SA400S37120G 120GB SSD     | 15        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB     | 14        | 0.96%   |
| Samsung SSD 860 EVO 500GB           | 14        | 0.96%   |
| Patriot Burst 120GB SSD             | 14        | 0.96%   |
| Toshiba DT01ACA100 1TB              | 13        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 0.89%   |
| Samsung SSD 850 EVO 250GB           | 13        | 0.89%   |
| Toshiba MQ01ABF050 500GB            | 12        | 0.82%   |
| SK Hynix NVMe SSD Drive 256GB       | 11        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB      | 11        | 0.76%   |
| Patriot Burst 240GB SSD             | 11        | 0.76%   |
| Patriot Burst 480GB SSD             | 10        | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 0.62%   |
| Unknown MMC Card  64GB              | 9         | 0.62%   |
| Toshiba MQ01ABD100 1TB              | 9         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB     | 9         | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 0.62%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB            | 8         | 0.55%   |
| Toshiba DT01ACA200 2TB              | 8         | 0.55%   |
| Toshiba DT01ACA050 500GB            | 8         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 0.55%   |
| Samsung NVMe SSD Drive 500GB        | 8         | 0.55%   |
| Samsung SSD 850 EVO 500GB           | 7         | 0.48%   |
| Kingston SA400S37480G 480GB SSD     | 7         | 0.48%   |
| HGST HTS545050A7E680 500GB          | 7         | 0.48%   |
| Unknown MMC Card  128GB             | 6         | 0.41%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 0.41%   |
| Samsung NVMe SSD Drive 256GB        | 6         | 0.41%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 0.41%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 5         | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB            | 5         | 0.34%   |
| Seagate ST3500418AS 500GB           | 5         | 0.34%   |
| SanDisk SSD PLUS 240GB              | 5         | 0.34%   |
| SanDisk SSD PLUS 120GB              | 5         | 0.34%   |
| SanDisk SDSSDA120G 120GB            | 5         | 0.34%   |
| Sandisk NVMe SSD Drive 256GB        | 5         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB      | 5         | 0.34%   |
| Samsung SSD 850 EVO 120GB           | 5         | 0.34%   |
| Samsung SSD 840 Series 120GB        | 5         | 0.34%   |
| Samsung NVMe SSD Drive 1TB          | 5         | 0.34%   |
| PNY CS900 120GB SSD                 | 5         | 0.34%   |
| Intenso SSD Sata III 240GB          | 5         | 0.34%   |
| Intel SSDSA2BW120G3H 120GB          | 5         | 0.34%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.34%   |
| Fujitsu MHY2200BH 200GB             | 5         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4         | 0.27%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 4         | 0.27%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 0.27%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.27%   |
| Seagate ST9250315AS 250GB           | 4         | 0.27%   |
| Seagate ST3500630AS 500GB           | 4         | 0.27%   |
| Seagate ST3500320AS 500GB           | 4         | 0.27%   |
| Seagate ST3160815AS 160GB           | 4         | 0.27%   |
| Sandisk NVMe SSD Drive 512GB        | 4         | 0.27%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.27%   |
| Samsung SSD 840 EVO 250GB           | 4         | 0.27%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 223       | 351    | 35.57%  |
| Seagate             | 199       | 292    | 31.74%  |
| Toshiba             | 86        | 103    | 13.72%  |
| Hitachi             | 40        | 42     | 6.38%   |
| HGST                | 22        | 29     | 3.51%   |
| Samsung Electronics | 18        | 23     | 2.87%   |
| Fujitsu             | 18        | 18     | 2.87%   |
| MAXTOR              | 11        | 13     | 1.75%   |
| Intenso             | 3         | 4      | 0.48%   |
| Apple               | 2         | 2      | 0.32%   |
| QUANTUM             | 1         | 1      | 0.16%   |
| JMicron             | 1         | 1      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |
| IBM-ESXS            | 1         | 3      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 100       | 131    | 20.2%   |
| Kingston            | 64        | 83     | 12.93%  |
| SanDisk             | 59        | 80     | 11.92%  |
| Patriot             | 47        | 54     | 9.49%   |
| WDC                 | 31        | 61     | 6.26%   |
| Intenso             | 19        | 23     | 3.84%   |
| Crucial             | 18        | 30     | 3.64%   |
| Toshiba             | 17        | 24     | 3.43%   |
| Team                | 16        | 22     | 3.23%   |
| Intel               | 16        | 22     | 3.23%   |
| OCZ                 | 12        | 15     | 2.42%   |
| A-DATA Technology   | 10        | 15     | 2.02%   |
| PNY                 | 7         | 7      | 1.41%   |
| Micron Technology   | 7         | 8      | 1.41%   |
| Leven               | 5         | 5      | 1.01%   |
| Gigabyte Technology | 5         | 7      | 1.01%   |
| Transcend           | 4         | 4      | 0.81%   |
| SPCC                | 4         | 5      | 0.81%   |
| SK Hynix            | 4         | 4      | 0.81%   |
| JMicron             | 4         | 4      | 0.81%   |
| Corsair             | 4         | 4      | 0.81%   |
| Teclast             | 3         | 3      | 0.61%   |
| Mushkin             | 3         | 3      | 0.61%   |
| GOODRAM             | 3         | 5      | 0.61%   |
| EMTEC               | 3         | 6      | 0.61%   |
| China               | 3         | 3      | 0.61%   |
| Unknown             | 3         | 3      | 0.61%   |
| Verbatim            | 2         | 2      | 0.4%    |
| PLEXTOR             | 2         | 2      | 0.4%    |
| Platinet            | 2         | 2      | 0.4%    |
| LITEONIT            | 2         | 2      | 0.4%    |
| DREVO               | 2         | 2      | 0.4%    |
| WDC WDS             | 1         | 1      | 0.2%    |
| USB30               | 1         | 1      | 0.2%    |
| Unknown             | 1         | 6      | 0.2%    |
| OCZ-AGIL            | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| Lite-On             | 1         | 4      | 0.2%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| InnoLite            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| External            | 1         | 2      | 0.2%    |
| ASUS-PHISON         | 1         | 2      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |
| Apacer              | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 541       | 884    | 45.54%  |
| SSD     | 431       | 665    | 36.28%  |
| NVMe    | 159       | 214    | 13.38%  |
| MMC     | 49        | 85     | 4.12%   |
| Unknown | 8         | 12     | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 779       | 1517   | 76.45%  |
| NVMe | 159       | 214    | 15.6%   |
| MMC  | 49        | 85     | 4.81%   |
| SAS  | 32        | 44     | 3.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 666       | 1106   | 69.23%  |
| 0.51-1.0   | 214       | 318    | 22.25%  |
| 1.01-2.0   | 47        | 67     | 4.89%   |
| 3.01-4.0   | 16        | 20     | 1.66%   |
| 2.01-3.0   | 13        | 23     | 1.35%   |
| 4.01-10.0  | 5         | 13     | 0.52%   |
| 10.01-20.0 | 1         | 2      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 280       | 29.29%  |
| 251-500        | 192       | 20.08%  |
| 501-1000       | 106       | 11.09%  |
| 51-100         | 84        | 8.79%   |
| 1001-2000      | 71        | 7.43%   |
| 1-20           | 66        | 6.9%    |
| 21-50          | 58        | 6.07%   |
| Unknown        | 49        | 5.13%   |
| More than 3000 | 31        | 3.24%   |
| 2001-3000      | 19        | 1.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 391       | 39.86%  |
| 21-50          | 158       | 16.11%  |
| 51-100         | 110       | 11.21%  |
| 101-250        | 105       | 10.7%   |
| 251-500        | 68        | 6.93%   |
| 501-1000       | 49        | 4.99%   |
| Unknown        | 49        | 4.99%   |
| 1001-2000      | 29        | 2.96%   |
| More than 3000 | 16        | 1.63%   |
| 2001-3000      | 6         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 3         | 3      | 4.48%   |
| Seagate ST3500320AS 500GB             | 2         | 2      | 2.99%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 2.99%   |
| WDC WD800JB-00JJC0 80GB               | 1         | 1      | 1.49%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 1.49%   |
| WDC WD5000AAVS-22G9B1 500GB           | 1         | 1      | 1.49%   |
| WDC WD5000AAKB-00H8A0 500GB           | 1         | 1      | 1.49%   |
| WDC WD3200BEVT-26ZCT0 320GB           | 1         | 1      | 1.49%   |
| WDC WD3200BEVT-00A0RT0 320GB          | 1         | 1      | 1.49%   |
| WDC WD2500YS-01SHB1 256GB             | 1         | 2      | 1.49%   |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 1      | 1.49%   |
| WDC WD2500AAKX-083CA1 250GB           | 1         | 1      | 1.49%   |
| WDC WD20PURX-64P6ZY0 2TB              | 1         | 1      | 1.49%   |
| WDC WD2002FAEX-007BA0 2TB             | 1         | 2      | 1.49%   |
| WDC WD1600AAJS-22L7A0 160GB           | 1         | 1      | 1.49%   |
| WDC WD1200JD-00HBB0 120GB             | 1         | 2      | 1.49%   |
| WDC WD10EZEX-60WN4A1 1TB              | 1         | 2      | 1.49%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 1.49%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.49%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 1.49%   |
| Toshiba MQ01ABD100M 1TB               | 1         | 1      | 1.49%   |
| Toshiba MQ01ABD050 500GB              | 1         | 3      | 1.49%   |
| Toshiba MK1665GSX H 160GB             | 1         | 1      | 1.49%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.49%   |
| SK Hynix SC210 mSATA 256GB SSD        | 1         | 1      | 1.49%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 1.49%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.49%   |
| Seagate ST9160310AS 160GB             | 1         | 1      | 1.49%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.49%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.49%   |
| Seagate ST3402111AS 40GB              | 1         | 1      | 1.49%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.49%   |
| Seagate ST3320620AS 320GB             | 1         | 1      | 1.49%   |
| Seagate ST3320613AS 320GB             | 1         | 1      | 1.49%   |
| Seagate ST3250410AS 250GB             | 1         | 2      | 1.49%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 1.49%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.49%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 4      | 1.49%   |
| SanDisk SSD U100 128GB                | 1         | 1      | 1.49%   |
| SanDisk SDSSDXPS480G 480GB            | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.49%   |
| Samsung Electronics SSD 860 EVO 500GB | 1         | 1      | 1.49%   |
| Samsung Electronics HD501LJ 500GB     | 1         | 1      | 1.49%   |
| OCZ-AGIL ITY3 120GB SSD               | 1         | 1      | 1.49%   |
| MAXTOR 6Y060L0 64GB                   | 1         | 1      | 1.49%   |
| MAXTOR 4K040H2 40GB                   | 1         | 1      | 1.49%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 1.49%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD | 1         | 1      | 1.49%   |
| Intel SSDSC2BW240H6 240GB             | 1         | 1      | 1.49%   |
| Hitachi HTS723216L9A360 160GB         | 1         | 1      | 1.49%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 1.49%   |
| Hitachi HTS541612J9SA00 120GB         | 1         | 1      | 1.49%   |
| Hitachi HDT722516DLA380 164GB         | 1         | 1      | 1.49%   |
| Hitachi HDS721050DLE630 500GB         | 1         | 1      | 1.49%   |
| HGST HUS724030ALA640 3TB              | 1         | 1      | 1.49%   |
| Fujitsu MHT2080BH 80GB                | 1         | 1      | 1.49%   |
| Crucial CT256M550SSD1 256GB           | 1         | 2      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 22     | 27.27%  |
| WDC                 | 15        | 20     | 22.73%  |
| Toshiba             | 5         | 7      | 7.58%   |
| Hitachi             | 5         | 5      | 7.58%   |
| SanDisk             | 4         | 4      | 6.06%   |
| HGST                | 4         | 4      | 6.06%   |
| Samsung Electronics | 3         | 3      | 4.55%   |
| MAXTOR              | 2         | 2      | 3.03%   |
| Kingston            | 2         | 2      | 3.03%   |
| Corsair             | 2         | 2      | 3.03%   |
| SK Hynix            | 1         | 1      | 1.52%   |
| OCZ-AGIL            | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| Crucial             | 1         | 2      | 1.52%   |
| A-DATA Technology   | 1         | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 22     | 35.29%  |
| WDC                 | 15        | 20     | 29.41%  |
| Toshiba             | 5         | 7      | 9.8%    |
| Hitachi             | 5         | 5      | 9.8%    |
| HGST                | 4         | 4      | 7.84%   |
| MAXTOR              | 2         | 2      | 3.92%   |
| Samsung Electronics | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 62     | 75.81%  |
| SSD  | 13        | 14     | 20.97%  |
| NVMe | 2         | 2      | 3.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 1         | 1      | 50%     |
| Mushkin MKNSSDCR120GB-7   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Mushkin | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 641       | 1269   | 66.22%  |
| Works    | 265       | 511    | 27.38%  |
| Malfunc  | 60        | 78     | 6.2%    |
| Failed   | 2         | 2      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 616       | 57.14%  |
| AMD                              | 186       | 17.25%  |
| Samsung Electronics              | 58        | 5.38%   |
| JMicron Technology               | 32        | 2.97%   |
| SK Hynix                         | 22        | 2.04%   |
| Nvidia                           | 21        | 1.95%   |
| Sandisk                          | 20        | 1.86%   |
| Marvell Technology Group         | 18        | 1.67%   |
| Kingston Technology Company      | 15        | 1.39%   |
| ASMedia Technology               | 14        | 1.3%    |
| Toshiba America Info Systems     | 12        | 1.11%   |
| KIOXIA                           | 10        | 0.93%   |
| VIA Technologies                 | 9         | 0.83%   |
| Silicon Image                    | 7         | 0.65%   |
| Phison Electronics               | 7         | 0.65%   |
| Micron Technology                | 5         | 0.46%   |
| ADATA Technology                 | 4         | 0.37%   |
| Silicon Motion                   | 3         | 0.28%   |
| LSI Logic / Symbios Logic        | 3         | 0.28%   |
| Broadcom / LSI                   | 3         | 0.28%   |
| Union Memory (Shenzhen)          | 2         | 0.19%   |
| Realtek Semiconductor            | 2         | 0.19%   |
| Micron/Crucial Technology        | 2         | 0.19%   |
| Solid State Storage Technology   | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| Seagate Technology               | 1         | 0.09%   |
| Promise Technology               | 1         | 0.09%   |
| OCZ Technology Group             | 1         | 0.09%   |
| Lite-On Technology               | 1         | 0.09%   |
| Integrated Technology Express    | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 127       | 9.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 48        | 3.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 44        | 3.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 44        | 3.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40        | 2.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 36        | 2.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 33        | 2.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 30        | 2.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 27        | 2.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 23        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 22        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20        | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 19        | 1.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19        | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 17        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 13        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 13        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 13        | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13        | 0.97%   |
| AMD 300 Series Chipset SATA Controller                                                  | 13        | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 11        | 0.82%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 11        | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11        | 0.82%   |
| KIOXIA Non-Volatile memory controller                                                   | 10        | 0.75%   |
| JMicron JMB368 IDE controller                                                           | 10        | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 10        | 0.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 10        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 0.75%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 9         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 0.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 0.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8         | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 8         | 0.6%    |
| AMD FCH SATA Controller D                                                               | 8         | 0.6%    |
| SK Hynix BC511                                                                          | 7         | 0.52%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 7         | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                         | 7         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 7         | 0.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 7         | 0.52%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 6         | 0.45%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 6         | 0.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 0.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.45%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6         | 0.45%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6         | 0.45%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6         | 0.45%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 6         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 636       | 57.25%  |
| IDE  | 253       | 22.77%  |
| NVMe | 166       | 14.94%  |
| RAID | 50        | 4.5%    |
| SAS  | 5         | 0.45%   |
| SCSI | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 670       | 74.03%  |
| AMD          | 230       | 25.41%  |
| ARM          | 4         | 0.44%   |
| CentaurHauls | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.1%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 9         | 0.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 8         | 0.88%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.88%   |
| Intel Pentium 4 CPU 3.20GHz                   | 7         | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                   | 7         | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 7         | 0.77%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 7         | 0.77%   |
| AMD FX-6300 Six-Core Processor                | 7         | 0.77%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 6         | 0.66%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 0.66%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 6         | 0.66%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.66%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.66%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 0.66%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 6         | 0.66%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 6         | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5         | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 5         | 0.55%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.55%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.55%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 5         | 0.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.55%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.55%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.55%   |
| AMD Phenom II X4 965 Processor                | 5         | 0.55%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 4         | 0.44%   |
| Intel Pentium D CPU 2.80GHz                   | 4         | 0.44%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 4         | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.44%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 4         | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.44%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.44%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 4         | 0.44%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 4         | 0.44%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 0.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 0.44%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 4         | 0.44%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.44%   |
| AMD Phenom II X4 955 Processor                | 4         | 0.44%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+    | 4         | 0.44%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 4         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 155       | 17.11%  |
| Intel Core i7                  | 117       | 12.91%  |
| Intel Core 2 Duo               | 78        | 8.61%   |
| Intel Core i3                  | 75        | 8.28%   |
| AMD Ryzen 5                    | 61        | 6.73%   |
| Intel Celeron                  | 53        | 5.85%   |
| Intel Pentium                  | 35        | 3.86%   |
| Intel Atom                     | 33        | 3.64%   |
| AMD Ryzen 7                    | 28        | 3.09%   |
| Intel Pentium 4                | 19        | 2.1%    |
| AMD Ryzen 3                    | 18        | 1.99%   |
| Intel Core 2 Quad              | 17        | 1.88%   |
| Intel Core 2                   | 17        | 1.88%   |
| Other                          | 16        | 1.77%   |
| AMD FX                         | 15        | 1.66%   |
| Intel Pentium Dual-Core        | 14        | 1.55%   |
| Intel Xeon                     | 13        | 1.43%   |
| AMD Athlon 64 X2               | 12        | 1.32%   |
| AMD Phenom II X4               | 10        | 1.1%    |
| AMD A8                         | 10        | 1.1%    |
| AMD A6                         | 8         | 0.88%   |
| AMD A10                        | 8         | 0.88%   |
| Intel Pentium Dual             | 7         | 0.77%   |
| AMD E1                         | 7         | 0.77%   |
| AMD A4                         | 7         | 0.77%   |
| Intel Pentium D                | 6         | 0.66%   |
| AMD Ryzen 9                    | 6         | 0.66%   |
| Intel Genuine                  | 5         | 0.55%   |
| Intel Celeron M                | 5         | 0.55%   |
| Intel Pentium M                | 4         | 0.44%   |
| AMD Sempron                    | 3         | 0.33%   |
| AMD Ryzen 7 PRO                | 3         | 0.33%   |
| AMD Phenom II X6               | 3         | 0.33%   |
| AMD E                          | 3         | 0.33%   |
| AMD Athlon                     | 3         | 0.33%   |
| Intel Celeron Dual-Core        | 2         | 0.22%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.22%   |
| AMD Turion                     | 2         | 0.22%   |
| AMD Ryzen Threadripper         | 2         | 0.22%   |
| AMD Phenom                     | 2         | 0.22%   |
| AMD Athlon XP                  | 2         | 0.22%   |
| AMD Athlon 64                  | 2         | 0.22%   |
| Intel Pentium Gold             | 1         | 0.11%   |
| Intel Core m3                  | 1         | 0.11%   |
| Intel Core Duo                 | 1         | 0.11%   |
| Intel Core 2 Extreme           | 1         | 0.11%   |
| CentaurHauls VIA C7            | 1         | 0.11%   |
| ARM BCM                        | 1         | 0.11%   |
| AMD V140                       | 1         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.11%   |
| AMD Turion 64 Mobile           | 1         | 0.11%   |
| AMD Ryzen 5 PRO                | 1         | 0.11%   |
| AMD Phenom II X2               | 1         | 0.11%   |
| AMD E2                         | 1         | 0.11%   |
| AMD Dual Core Opteron          | 1         | 0.11%   |
| AMD Athlon II X4               | 1         | 0.11%   |
| AMD Athlon II X3               | 1         | 0.11%   |
| AMD Athlon II X2               | 1         | 0.11%   |
| AMD Athlon II Dual-Core        | 1         | 0.11%   |
| AMD Athlon Dual Core           | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 437       | 48.23%  |
| 4       | 292       | 32.23%  |
| 6       | 66        | 7.28%   |
| 1       | 56        | 6.18%   |
| 8       | 35        | 3.86%   |
| 3       | 9         | 0.99%   |
| 12      | 7         | 0.77%   |
| 16      | 3         | 0.33%   |
| Unknown | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 897       | 99.12%  |
| 2       | 7         | 0.77%   |
| Unknown | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 464       | 51.27%  |
| 1       | 439       | 48.51%  |
| 8       | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 857       | 94.28%  |
| 32-bit         | 32        | 3.52%   |
| Unknown        | 18        | 1.98%   |
| 64-bit         | 2         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 17.92%  |
| 0x206a7    | 60        | 6.44%   |
| 0x306c3    | 56        | 6.01%   |
| 0x306a9    | 42        | 4.51%   |
| 0x1067a    | 42        | 4.51%   |
| 0x40651    | 22        | 2.36%   |
| 0x10676    | 22        | 2.36%   |
| 0x6fd      | 20        | 2.15%   |
| 0x906ea    | 17        | 1.82%   |
| 0x08108102 | 17        | 1.82%   |
| 0x806ea    | 16        | 1.72%   |
| 0x506e3    | 15        | 1.61%   |
| 0x406c4    | 15        | 1.61%   |
| 0x0800820d | 15        | 1.61%   |
| 0x906e9    | 13        | 1.39%   |
| 0x806e9    | 13        | 1.39%   |
| 0x506c9    | 13        | 1.39%   |
| 0x08108109 | 13        | 1.39%   |
| 0x6f6      | 12        | 1.29%   |
| 0x306d4    | 12        | 1.29%   |
| 0x806ec    | 10        | 1.07%   |
| 0x30678    | 10        | 1.07%   |
| 0x106c2    | 10        | 1.07%   |
| 0x06000852 | 10        | 1.07%   |
| 0x906ed    | 9         | 0.97%   |
| 0x806c1    | 9         | 0.97%   |
| 0x406c3    | 9         | 0.97%   |
| 0x0810100b | 9         | 0.97%   |
| 0xf43      | 8         | 0.86%   |
| 0x6fb      | 8         | 0.86%   |
| 0x20655    | 8         | 0.86%   |
| 0x20652    | 8         | 0.86%   |
| 0x106e5    | 8         | 0.86%   |
| 0x406e3    | 7         | 0.75%   |
| 0xf41      | 6         | 0.64%   |
| 0x906eb    | 6         | 0.64%   |
| 0x6d8      | 6         | 0.64%   |
| 0x05000119 | 6         | 0.64%   |
| 0x010000c8 | 6         | 0.64%   |
| 0x706e5    | 5         | 0.54%   |
| 0x706a1    | 5         | 0.54%   |
| 0x6f2      | 5         | 0.54%   |
| 0x08701021 | 5         | 0.54%   |
| 0x08600104 | 5         | 0.54%   |
| 0x06006705 | 5         | 0.54%   |
| 0x06003106 | 5         | 0.54%   |
| 0xf29      | 4         | 0.43%   |
| 0xa0653    | 4         | 0.43%   |
| 0x6ec      | 4         | 0.43%   |
| 0x10677    | 4         | 0.43%   |
| 0x08600106 | 4         | 0.43%   |
| 0x08101016 | 4         | 0.43%   |
| 0x08001129 | 4         | 0.43%   |
| 0x0600611a | 4         | 0.43%   |
| 0xf47      | 3         | 0.32%   |
| 0x806eb    | 3         | 0.32%   |
| 0x106a5    | 3         | 0.32%   |
| 0x0a50000c | 3         | 0.32%   |
| 0x08701013 | 3         | 0.32%   |
| 0x0800820b | 3         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 97        | 10.71%  |
| Haswell         | 86        | 9.49%   |
| Penryn          | 83        | 9.16%   |
| SandyBridge     | 69        | 7.62%   |
| Core            | 63        | 6.95%   |
| Zen+            | 59        | 6.51%   |
| IvyBridge       | 56        | 6.18%   |
| Silvermont      | 38        | 4.19%   |
| Skylake         | 30        | 3.31%   |
| Zen             | 29        | 3.2%    |
| NetBurst        | 26        | 2.87%   |
| Zen 2           | 22        | 2.43%   |
| Westmere        | 22        | 2.43%   |
| K10             | 21        | 2.32%   |
| Piledriver      | 20        | 2.21%   |
| K8 Hammer       | 19        | 2.1%    |
| Goldmont        | 14        | 1.55%   |
| Bonnell         | 14        | 1.55%   |
| P6              | 13        | 1.43%   |
| Nehalem         | 13        | 1.43%   |
| Excavator       | 13        | 1.43%   |
| Broadwell       | 13        | 1.43%   |
| Zen 3           | 10        | 1.1%    |
| TigerLake       | 10        | 1.1%    |
| CometLake       | 9         | 0.99%   |
| Bobcat          | 9         | 0.99%   |
| Puma            | 7         | 0.77%   |
| IceLake         | 7         | 0.77%   |
| Goldmont plus   | 7         | 0.77%   |
| Steamroller     | 6         | 0.66%   |
| Unknown         | 6         | 0.66%   |
| K8 & K10 hybrid | 5         | 0.55%   |
| K10 Llano       | 4         | 0.44%   |
| K6              | 3         | 0.33%   |
| Jaguar          | 3         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 449       | 43.68%  |
| AMD                              | 287       | 27.92%  |
| Nvidia                           | 285       | 27.72%  |
| VIA Technologies                 | 3         | 0.29%   |
| Matrox Electronics Systems       | 2         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Conexant Systems                 | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 52        | 4.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 2.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19        | 1.75%   |
| Intel UHD Graphics 620                                                                   | 17        | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 1.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.29%   |
| Intel HD Graphics 620                                                                    | 14        | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 1.29%   |
| Intel HD Graphics 500                                                                    | 13        | 1.2%    |
| AMD Renoir                                                                               | 13        | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 1.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.01%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.01%   |
| Intel HD Graphics 530                                                                    | 11        | 1.01%   |
| Nvidia GT218 [GeForce 210]                                                               | 9         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.74%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 8         | 0.74%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.74%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 8         | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 0.65%   |
| Intel HD Graphics 630                                                                    | 7         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.65%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.55%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.55%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 6         | 0.55%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 6         | 0.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 6         | 0.55%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 6         | 0.55%   |
| AMD Cezanne                                                                              | 6         | 0.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.46%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.46%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 5         | 0.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.37%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.37%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.37%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4         | 0.37%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 329       | 36.15%  |
| 1 x AMD                        | 231       | 25.38%  |
| 1 x Nvidia                     | 195       | 21.43%  |
| Intel + Nvidia                 | 85        | 9.34%   |
| Intel + AMD                    | 30        | 3.3%    |
| 2 x AMD                        | 22        | 2.42%   |
| Other                          | 7         | 0.77%   |
| 1 x VIA                        | 3         | 0.33%   |
| AMD + Nvidia                   | 3         | 0.33%   |
| 1 x Matrox                     | 2         | 0.22%   |
| 2 x Nvidia                     | 1         | 0.11%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.11%   |
| 1 x SiS                        | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 745       | 81.42%  |
| Proprietary | 133       | 14.54%  |
| Unknown     | 37        | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 411       | 44.15%  |
| 1.01-2.0   | 160       | 17.19%  |
| 0.01-0.5   | 156       | 16.76%  |
| 0.51-1.0   | 96        | 10.31%  |
| 3.01-4.0   | 63        | 6.77%   |
| 7.01-8.0   | 20        | 2.15%   |
| 5.01-6.0   | 17        | 1.83%   |
| 2.01-3.0   | 6         | 0.64%   |
| 8.01-16.0  | 2         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 133       | 14.35%  |
| Goldstar                | 108       | 11.65%  |
| AU Optronics            | 92        | 9.92%   |
| LG Display              | 90        | 9.71%   |
| BOE                     | 73        | 7.87%   |
| Chimei Innolux          | 63        | 6.8%    |
| Dell                    | 51        | 5.5%    |
| Philips                 | 27        | 2.91%   |
| Hewlett-Packard         | 22        | 2.37%   |
| LG Electronics          | 21        | 2.27%   |
| Chi Mei Optoelectronics | 19        | 2.05%   |
| ViewSonic               | 16        | 1.73%   |
| AOC                     | 16        | 1.73%   |
| Lenovo                  | 14        | 1.51%   |
| BenQ                    | 14        | 1.51%   |
| LG Philips              | 13        | 1.4%    |
| Ancor Communications    | 13        | 1.4%    |
| Eizo                    | 9         | 0.97%   |
| Apple                   | 9         | 0.97%   |
| Sony                    | 8         | 0.86%   |
| Sharp                   | 8         | 0.86%   |
| Iiyama                  | 7         | 0.76%   |
| CPT                     | 7         | 0.76%   |
| Vestel Elektronik       | 6         | 0.65%   |
| Unknown                 | 6         | 0.65%   |
| NEC Computers           | 6         | 0.65%   |
| HannStar                | 5         | 0.54%   |
| PANDA                   | 4         | 0.43%   |
| JRY                     | 4         | 0.43%   |
| Fujitsu Siemens         | 4         | 0.43%   |
| Belinea                 | 4         | 0.43%   |
| Quanta Display          | 3         | 0.32%   |
| Medion                  | 3         | 0.32%   |
| InfoVision              | 3         | 0.32%   |
| ASUSTek Computer        | 3         | 0.32%   |
| Acer                    | 3         | 0.32%   |
| Nvidia                  | 2         | 0.22%   |
| Mi                      | 2         | 0.22%   |
| IBM                     | 2         | 0.22%   |
| FUS                     | 2         | 0.22%   |
| DAO                     | 2         | 0.22%   |
| CSO                     | 2         | 0.22%   |
| ZLX                     | 1         | 0.11%   |
| YM                      | 1         | 0.11%   |
| TSL                     | 1         | 0.11%   |
| Toshiba                 | 1         | 0.11%   |
| SKY                     | 1         | 0.11%   |
| RTK                     | 1         | 0.11%   |
| PER                     | 1         | 0.11%   |
| PDI                     | 1         | 0.11%   |
| Panasonic               | 1         | 0.11%   |
| OUT                     | 1         | 0.11%   |
| NCS                     | 1         | 0.11%   |
| Marantz                 | 1         | 0.11%   |
| LPL                     | 1         | 0.11%   |
| LLL                     | 1         | 0.11%   |
| Lite-On                 | 1         | 0.11%   |
| LGD                     | 1         | 0.11%   |
| KET                     | 1         | 0.11%   |
| KDC                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.05%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.74%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch     | 6         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 6         | 0.63%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.63%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 5         | 0.53%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 5         | 0.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 0.53%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch            | 4         | 0.42%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch        | 4         | 0.42%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch        | 4         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 4         | 0.42%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.42%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.42%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.42%   |
| Dell S2715H DEL40BB 1920x1080 598x336mm 27.0-inch                        | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 4         | 0.42%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch    | 4         | 0.42%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch        | 3         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch    | 3         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 3         | 0.32%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 3         | 0.32%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| Hewlett-Packard L2035 HWP2612 1600x1200 408x306mm 20.1-inch              | 3         | 0.32%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 3         | 0.32%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 3         | 0.32%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.32%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 3         | 0.32%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                    | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.32%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.32%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.32%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                       | 2         | 0.21%   |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch     | 2         | 0.21%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 2         | 0.21%   |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch     | 2         | 0.21%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.21%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 364       | 40.72%  |
| 1366x768 (WXGA)    | 189       | 21.14%  |
| 1280x1024 (SXGA)   | 60        | 6.71%   |
| 1280x800 (WXGA)    | 45        | 5.03%   |
| 1680x1050 (WSXGA+) | 36        | 4.03%   |
| 1600x900 (HD+)     | 29        | 3.24%   |
| 1440x900 (WXGA+)   | 28        | 3.13%   |
| 3840x2160 (4K)     | 27        | 3.02%   |
| 2560x1440 (QHD)    | 21        | 2.35%   |
| 1920x1200 (WUXGA)  | 15        | 1.68%   |
| 1360x768           | 11        | 1.23%   |
| 1024x768 (XGA)     | 11        | 1.23%   |
| 1024x600           | 9         | 1.01%   |
| Unknown            | 9         | 1.01%   |
| 1600x1200          | 6         | 0.67%   |
| 3840x1080          | 5         | 0.56%   |
| 3440x1440          | 4         | 0.45%   |
| 2560x1080          | 4         | 0.45%   |
| 2560x1600          | 2         | 0.22%   |
| 2160x1440          | 2         | 0.22%   |
| 2048x1152          | 2         | 0.22%   |
| 1920x540           | 2         | 0.22%   |
| 5120x1440          | 1         | 0.11%   |
| 4864x2160          | 1         | 0.11%   |
| 4480x1080          | 1         | 0.11%   |
| 3840x2400          | 1         | 0.11%   |
| 3600x1080          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 3000x1920          | 1         | 0.11%   |
| 2960x1050          | 1         | 0.11%   |
| 2880x1800          | 1         | 0.11%   |
| 2624x900           | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1280x768           | 1         | 0.11%   |
| 1024x576           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 276       | 29.84%  |
| 23      | 68        | 7.35%   |
| 21      | 65        | 7.03%   |
| 17      | 65        | 7.03%   |
| Unknown | 58        | 6.27%   |
| 13      | 57        | 6.16%   |
| 27      | 52        | 5.62%   |
| 14      | 47        | 5.08%   |
| 24      | 42        | 4.54%   |
| 19      | 40        | 4.32%   |
| 18      | 24        | 2.59%   |
| 20      | 21        | 2.27%   |
| 22      | 16        | 1.73%   |
| 11      | 12        | 1.3%    |
| 12      | 10        | 1.08%   |
| 10      | 10        | 1.08%   |
| 34      | 8         | 0.86%   |
| 31      | 8         | 0.86%   |
| 84      | 7         | 0.76%   |
| 54      | 5         | 0.54%   |
| 33      | 5         | 0.54%   |
| 72      | 4         | 0.43%   |
| 25      | 3         | 0.32%   |
| 16      | 3         | 0.32%   |
| 8       | 3         | 0.32%   |
| 49      | 2         | 0.22%   |
| 42      | 2         | 0.22%   |
| 32      | 2         | 0.22%   |
| 65      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 47      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 381       | 41.68%  |
| 501-600     | 148       | 16.19%  |
| 401-500     | 142       | 15.54%  |
| 351-400     | 67        | 7.33%   |
| 201-300     | 58        | 6.35%   |
| Unknown     | 58        | 6.35%   |
| 701-800     | 15        | 1.64%   |
| 601-700     | 14        | 1.53%   |
| 1001-1500   | 12        | 1.31%   |
| 1501-2000   | 11        | 1.2%    |
| 801-900     | 3         | 0.33%   |
| 101-200     | 3         | 0.33%   |
| 901-1000    | 2         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 591       | 69.2%   |
| 16/10   | 120       | 14.05%  |
| 5/4     | 50        | 5.85%   |
| Unknown | 50        | 5.85%   |
| 4/3     | 20        | 2.34%   |
| 6/5     | 7         | 0.82%   |
| 3/2     | 7         | 0.82%   |
| 21/9    | 7         | 0.82%   |
| 32/9    | 2         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 276       | 30.03%  |
| 201-250        | 158       | 17.19%  |
| 81-90          | 83        | 9.03%   |
| 151-200        | 78        | 8.49%   |
| Unknown        | 58        | 6.31%   |
| 301-350        | 52        | 5.66%   |
| 141-150        | 48        | 5.22%   |
| 121-130        | 26        | 2.83%   |
| 351-500        | 24        | 2.61%   |
| 71-80          | 21        | 2.29%   |
| More than 1000 | 20        | 2.18%   |
| 251-300        | 18        | 1.96%   |
| 51-60          | 12        | 1.31%   |
| 131-140        | 11        | 1.2%    |
| 41-50          | 10        | 1.09%   |
| 61-70          | 9         | 0.98%   |
| 501-1000       | 9         | 0.98%   |
| 1-40           | 3         | 0.33%   |
| 111-120        | 2         | 0.22%   |
| 91-100         | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 356       | 39.64%  |
| 101-120       | 244       | 27.17%  |
| 121-160       | 188       | 20.94%  |
| Unknown       | 58        | 6.46%   |
| 161-240       | 23        | 2.56%   |
| 1-50          | 20        | 2.23%   |
| More than 240 | 9         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 772       | 83.19%  |
| 2     | 104       | 11.21%  |
| 0     | 45        | 4.85%   |
| 3     | 7         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 515       | 38.18%  |
| Intel                                 | 352       | 26.09%  |
| Qualcomm Atheros                      | 166       | 12.31%  |
| Broadcom                              | 83        | 6.15%   |
| Marvell Technology Group              | 34        | 2.52%   |
| Ralink Technology                     | 26        | 1.93%   |
| TP-Link                               | 23        | 1.7%    |
| Ralink                                | 21        | 1.56%   |
| Broadcom Limited                      | 20        | 1.48%   |
| Nvidia                                | 17        | 1.26%   |
| Qualcomm Atheros Communications       | 9         | 0.67%   |
| VIA Technologies                      | 8         | 0.59%   |
| D-Link                                | 7         | 0.52%   |
| MediaTek                              | 5         | 0.37%   |
| Xiaomi                                | 4         | 0.3%    |
| NetGear                               | 4         | 0.3%    |
| Ericsson Business Mobile Networks     | 4         | 0.3%    |
| ASUSTek Computer                      | 4         | 0.3%    |
| Sierra Wireless                       | 3         | 0.22%   |
| JMicron Technology                    | 3         | 0.22%   |
| Huawei Technologies                   | 3         | 0.22%   |
| Hewlett-Packard                       | 3         | 0.22%   |
| Dell                                  | 3         | 0.22%   |
| Motorola                              | 2         | 0.15%   |
| Fujitsu Siemens Computers             | 2         | 0.15%   |
| Edimax Technology                     | 2         | 0.15%   |
| D-Link System                         | 2         | 0.15%   |
| Belkin Components                     | 2         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.15%   |
| ZyDAS                                 | 1         | 0.07%   |
| U-Blox                                | 1         | 0.07%   |
| Toshiba                               | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.07%   |
| Sitecom Europe                        | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.07%   |
| Samsung Electronics                   | 1         | 0.07%   |
| PCTel                                 | 1         | 0.07%   |
| Microsoft                             | 1         | 0.07%   |
| Micro Star International              | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| InProComm                             | 1         | 0.07%   |
| IBM                                   | 1         | 0.07%   |
| Google                                | 1         | 0.07%   |
| Dresden Elektronik                    | 1         | 0.07%   |
| Attansic Technology                   | 1         | 0.07%   |
| ASIX Electronics                      | 1         | 0.07%   |
| Aquantia                              | 1         | 0.07%   |
| AMD                                   | 1         | 0.07%   |
| Accton Technology                     | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 336       | 21.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 97        | 6.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 37        | 2.38%   |
| Intel I211 Gigabit Network Connection                                   | 28        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 22        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.29%   |
| Intel Wireless 3165                                                     | 18        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 17        | 1.09%   |
| Intel Ethernet Connection I217-LM                                       | 17        | 1.09%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.84%   |
| Intel Wireless 7260                                                     | 13        | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 0.71%   |
| Intel Wireless 7265                                                     | 11        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 10        | 0.64%   |
| Intel WiFi Link 5100                                                    | 10        | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 9         | 0.58%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.58%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 8         | 0.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 7         | 0.45%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 7         | 0.45%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.45%   |
| Intel Wireless 8260                                                     | 7         | 0.45%   |
| Intel Wireless 3160                                                     | 7         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                    | 7         | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.45%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                 | 7         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 6         | 0.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.39%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 6         | 0.39%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.39%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.39%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 5         | 0.32%   |
| Realtek RTL8187 Wireless Adapter                                        | 5         | 0.32%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 239       | 35.62%  |
| Realtek Semiconductor                 | 134       | 19.97%  |
| Qualcomm Atheros                      | 125       | 18.63%  |
| Broadcom                              | 51        | 7.6%    |
| Ralink Technology                     | 26        | 3.87%   |
| TP-Link                               | 21        | 3.13%   |
| Ralink                                | 21        | 3.13%   |
| Qualcomm Atheros Communications       | 9         | 1.34%   |
| Broadcom Limited                      | 8         | 1.19%   |
| D-Link                                | 7         | 1.04%   |
| NetGear                               | 4         | 0.6%    |
| ASUSTek Computer                      | 4         | 0.6%    |
| Sierra Wireless                       | 2         | 0.3%    |
| MediaTek                              | 2         | 0.3%    |
| Hewlett-Packard                       | 2         | 0.3%    |
| Fujitsu Siemens Computers             | 2         | 0.3%    |
| Edimax Technology                     | 2         | 0.3%    |
| Belkin Components                     | 2         | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.3%    |
| ZyDAS                                 | 1         | 0.15%   |
| Sitecom Europe                        | 1         | 0.15%   |
| Microsoft                             | 1         | 0.15%   |
| Micro Star International              | 1         | 0.15%   |
| Linksys                               | 1         | 0.15%   |
| InProComm                             | 1         | 0.15%   |
| Dell                                  | 1         | 0.15%   |
| Accton Technology                     | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 26        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 3.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 3.25%   |
| Intel Wireless 8265 / 8275                                              | 22        | 3.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.96%   |
| Intel Wireless 3165                                                     | 18        | 2.66%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 2.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 2.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 1.92%   |
| Intel Wireless 7260                                                     | 13        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 1.63%   |
| Intel Wireless 7265                                                     | 11        | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 10        | 1.48%   |
| Intel WiFi Link 5100                                                    | 10        | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.48%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.18%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 1.18%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.18%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 7         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.04%   |
| Intel Wireless-AC 9260                                                  | 7         | 1.04%   |
| Intel Wireless 8260                                                     | 7         | 1.04%   |
| Intel Wireless 3160                                                     | 7         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.04%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 6         | 0.89%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.89%   |
| Realtek RTL8187 Wireless Adapter                                        | 5         | 0.74%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 5         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 4         | 0.59%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 4         | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.59%   |
| D-Link 802.11ac NIC                                                     | 4         | 0.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 4         | 0.59%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 4         | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.44%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 476       | 56.4%   |
| Intel                             | 183       | 21.68%  |
| Qualcomm Atheros                  | 54        | 6.4%    |
| Broadcom                          | 36        | 4.27%   |
| Marvell Technology Group          | 34        | 4.03%   |
| Nvidia                            | 17        | 2.01%   |
| Broadcom Limited                  | 15        | 1.78%   |
| VIA Technologies                  | 7         | 0.83%   |
| Xiaomi                            | 4         | 0.47%   |
| JMicron Technology                | 3         | 0.36%   |
| TP-Link                           | 2         | 0.24%   |
| MediaTek                          | 2         | 0.24%   |
| D-Link System                     | 2         | 0.24%   |
| Sundance Technology Inc / IC Plus | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.12%   |
| Sierra Wireless                   | 1         | 0.12%   |
| Samsung Electronics               | 1         | 0.12%   |
| IBM                               | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| Attansic Technology               | 1         | 0.12%   |
| ASIX Electronics                  | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 336       | 39.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 11.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 4.32%   |
| Intel I211 Gigabit Network Connection                             | 28        | 3.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 9         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 7         | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 7         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 7         | 0.82%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 5         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.58%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.47%   |
| Nvidia MCP77 Ethernet                                             | 4         | 0.47%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3         | 0.35%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 3         | 0.35%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 3         | 0.35%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 3         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.35%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.35%   |
| Intel 82578DM Gigabit Network Connection                          | 3         | 0.35%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.35%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 3         | 0.35%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 3         | 0.35%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2         | 0.23%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.23%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.23%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.23%   |
| Nvidia MCP73 Ethernet                                             | 2         | 0.23%   |
| Nvidia MCP55 Ethernet                                             | 2         | 0.23%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.23%   |
| MediaTek NOA N2                                                   | 2         | 0.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 820       | 55.93%  |
| WiFi     | 622       | 42.43%  |
| Modem    | 24        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 557       | 51.96%  |
| WiFi     | 513       | 47.85%  |
| Modem    | 2         | 0.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 464       | 51.1%   |
| 1     | 406       | 44.71%  |
| 0     | 22        | 2.42%   |
| 3     | 13        | 1.43%   |
| 4     | 3         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 764       | 82.33%  |
| Yes  | 164       | 17.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 33.41%  |
| Realtek Semiconductor           | 62        | 13.9%   |
| Qualcomm Atheros Communications | 45        | 10.09%  |
| Cambridge Silicon Radio         | 41        | 9.19%   |
| Broadcom                        | 29        | 6.5%    |
| IMC Networks                    | 16        | 3.59%   |
| Toshiba                         | 14        | 3.14%   |
| Foxconn / Hon Hai               | 14        | 3.14%   |
| Hewlett-Packard                 | 13        | 2.91%   |
| Lite-On Technology              | 12        | 2.69%   |
| Ralink                          | 8         | 1.79%   |
| Apple                           | 7         | 1.57%   |
| Foxconn International           | 6         | 1.35%   |
| ASUSTek Computer                | 6         | 1.35%   |
| Alps Electric                   | 5         | 1.12%   |
| Realtek                         | 4         | 0.9%    |
| Dell                            | 4         | 0.9%    |
| Ralink Technology               | 3         | 0.67%   |
| Askey Computer                  | 3         | 0.67%   |
| Micro Star International        | 2         | 0.45%   |
| Syntek                          | 1         | 0.22%   |
| Mobile Action Technology        | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 73        | 16.37%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 41        | 9.19%   |
| Realtek Bluetooth Radio                               | 36        | 8.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 21        | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                    | 19        | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                        | 15        | 3.36%   |
| Intel AX201 Bluetooth                                 | 15        | 3.36%   |
| Intel AX200 Bluetooth                                 | 15        | 3.36%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 9         | 2.02%   |
| Ralink RT3290 Bluetooth                               | 8         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 8         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8         | 1.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 8         | 1.79%   |
| Realtek RTL8723B Bluetooth                            | 7         | 1.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7         | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                      | 7         | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 6         | 1.35%   |
| IMC Networks Bluetooth Radio                          | 6         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module     | 6         | 1.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 6         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 5         | 1.12%   |
| Toshiba RT Bluetooth Radio                            | 4         | 0.9%    |
| Toshiba Bluetooth Device                              | 4         | 0.9%    |
| Realtek Bluetooth Radio                               | 4         | 0.9%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                      | 4         | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                           | 4         | 0.9%    |
| Realtek RTL8723A Bluetooth                            | 3         | 0.67%   |
| Lite-On Bluetooth Device                              | 3         | 0.67%   |
| Intel Bluetooth Device                                | 3         | 0.67%   |
| IMC Networks Bluetooth Device                         | 3         | 0.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 3         | 0.67%   |
| Dell DW375 Bluetooth Module                           | 3         | 0.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3         | 0.67%   |
| Broadcom BCM2045 Bluetooth                            | 3         | 0.67%   |
| Askey Bluetooth Device                                | 3         | 0.67%   |
| Apple Bluetooth Host Controller                       | 3         | 0.67%   |
| Toshiba Integrated Bluetooth HCI                      | 2         | 0.45%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)            | 2         | 0.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 2         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.45%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device       | 2         | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 0.45%   |
| Broadcom Bluetooth 2.1 Device                         | 2         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 0.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 2         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 2         | 0.45%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 0.45%   |
| Alps Electric Bluetooth Adapter                       | 2         | 0.45%   |
| Alps Electric BCM2046 Bluetooth Device                | 2         | 0.45%   |
| Toshiba BCM43142A0                                    | 1         | 0.22%   |
| Toshiba Askey for                                     | 1         | 0.22%   |
| Syntek 802.11g + Bluetooth Wireless Adapter           | 1         | 0.22%   |
| Realtek 802.11n WLAN Adapter                          | 1         | 0.22%   |
| Ralink CSR BS8510                                     | 1         | 0.22%   |
| Mobile Action MA-730/MA-730G Bluetooth Adapter        | 1         | 0.22%   |
| Micro Star International Bluetooth EDR Device         | 1         | 0.22%   |
| Micro Star International Bluetooth Device             | 1         | 0.22%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 630       | 52.15%  |
| AMD                                             | 286       | 23.68%  |
| Nvidia                                          | 188       | 15.56%  |
| C-Media Electronics                             | 20        | 1.66%   |
| Creative Labs                                   | 10        | 0.83%   |
| Logitech                                        | 7         | 0.58%   |
| Creative Technology                             | 7         | 0.58%   |
| VIA Technologies                                | 6         | 0.5%    |
| Barco Display Systems                           | 5         | 0.41%   |
| Razer USA                                       | 4         | 0.33%   |
| BEHRINGER International                         | 4         | 0.33%   |
| Kingston Technology                             | 3         | 0.25%   |
| Texas Instruments                               | 2         | 0.17%   |
| Hewlett-Packard                                 | 2         | 0.17%   |
| Guillemot                                       | 2         | 0.17%   |
| Focusrite-Novation                              | 2         | 0.17%   |
| Ensoniq                                         | 2         | 0.17%   |
| AudioQuest                                      | 2         | 0.17%   |
| Altec Lansing Technologies                      | 2         | 0.17%   |
| Yamaha                                          | 1         | 0.08%   |
| Trust                                           | 1         | 0.08%   |
| Tenx Technology                                 | 1         | 0.08%   |
| SteelSeries ApS                                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.08%   |
| Shenzhen Riitek Technology                      | 1         | 0.08%   |
| Realtek Semiconductor                           | 1         | 0.08%   |
| Numark                                          | 1         | 0.08%   |
| Native Instruments                              | 1         | 0.08%   |
| Mark of the Unicorn                             | 1         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.08%   |
| Lenovo                                          | 1         | 0.08%   |
| JMTek                                           | 1         | 0.08%   |
| iCreate Technologies                            | 1         | 0.08%   |
| GN Netcom                                       | 1         | 0.08%   |
| Generalplus Technology                          | 1         | 0.08%   |
| Edifier Technology                              | 1         | 0.08%   |
| Dell                                            | 1         | 0.08%   |
| Cooler Master                                   | 1         | 0.08%   |
| CMX Systems                                     | 1         | 0.08%   |
| ClearOne Communications                         | 1         | 0.08%   |
| bestechnic                                      | 1         | 0.08%   |
| Asahi Kasei Microsystems                        | 1         | 0.08%   |
| AKAI Professional M.I.                          | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 60        | 4.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 59        | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 57        | 3.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 49        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 48        | 3.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 48        | 3.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 3.24%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 36        | 2.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 34        | 2.34%   |
| AMD FCH Azalia Controller                                                                         | 31        | 2.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 29        | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 28        | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 24        | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 1.65%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 24        | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 19        | 1.31%   |
| Nvidia High Definition Audio Controller                                                           | 18        | 1.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16        | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 16        | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 15        | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 0.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 0.9%    |
| Intel Broadwell-U Audio Controller                                                                | 13        | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 0.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 11        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 11        | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 11        | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 10        | 0.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 0.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 10        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.62%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 9         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.55%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 0.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 0.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.48%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                                 | 7         | 0.48%   |
| AMD High Definition Audio Controller                                                              | 7         | 0.48%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.41%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 6         | 0.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.41%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.34%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 0.34%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 79        | 18%     |
| SK Hynix            | 76        | 17.31%  |
| Unknown             | 75        | 17.08%  |
| Kingston            | 55        | 12.53%  |
| Micron Technology   | 34        | 7.74%   |
| Corsair             | 31        | 7.06%   |
| G.Skill             | 21        | 4.78%   |
| Crucial             | 19        | 4.33%   |
| Ramaxel Technology  | 10        | 2.28%   |
| Transcend           | 5         | 1.14%   |
| Elpida              | 5         | 1.14%   |
| Unknown (ABCD)      | 4         | 0.91%   |
| Team                | 4         | 0.91%   |
| A-DATA Technology   | 4         | 0.91%   |
| Nanya Technology    | 3         | 0.68%   |
| Apacer              | 3         | 0.68%   |
| Patriot             | 2         | 0.46%   |
| GOODRAM             | 2         | 0.46%   |
| Unknown             | 2         | 0.46%   |
| Toshiba             | 1         | 0.23%   |
| Qimonda             | 1         | 0.23%   |
| Infineon            | 1         | 0.23%   |
| HMD                 | 1         | 0.23%   |
| H                   | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s              | 7         | 1.44%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 5         | 1.03%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.03%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 4         | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 4         | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                          | 4         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 0.82%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.82%   |
| Unknown RAM Module 512MB DIMM SDRAM                                 | 3         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.62%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 3         | 0.62%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 3         | 0.62%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                              | 3         | 0.62%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.62%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.62%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.62%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.62%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s              | 3         | 0.62%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s              | 3         | 0.62%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s              | 3         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 2         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 2         | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                 | 2         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 2         | 0.41%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 2         | 0.41%   |
| Unknown RAM Module 1GB DIMM                                         | 2         | 0.41%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                          | 2         | 0.41%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                   | 2         | 0.41%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s               | 2         | 0.41%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.41%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.41%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.41%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.41%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.41%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 2         | 0.41%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.41%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                       | 2         | 0.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 0.41%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 2         | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.41%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.41%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s             | 2         | 0.41%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 0.41%   |
| Nanya RAM NT2GT64U8HD0BN-3C 2GB SODIMM DDR 667MT/s                  | 2         | 0.41%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 2         | 0.41%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.41%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 145       | 36.99%  |
| DDR3    | 132       | 33.67%  |
| DDR2    | 38        | 9.69%   |
| Unknown | 29        | 7.4%    |
| SDRAM   | 17        | 4.34%   |
| DDR     | 13        | 3.32%   |
| LPDDR4  | 12        | 3.06%   |
| LPDDR3  | 4         | 1.02%   |
| DRAM    | 2         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 203       | 52.73%  |
| DIMM         | 167       | 43.38%  |
| Row Of Chips | 14        | 3.64%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 140       | 32.48%  |
| 4096  | 128       | 29.7%   |
| 2048  | 90        | 20.88%  |
| 1024  | 33        | 7.66%   |
| 16384 | 29        | 6.73%   |
| 512   | 9         | 2.09%   |
| 32768 | 1         | 0.23%   |
| 256   | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 88        | 20.75%  |
| 2667    | 55        | 12.97%  |
| 3200    | 37        | 8.73%   |
| 2400    | 31        | 7.31%   |
| 1333    | 28        | 6.6%    |
| 667     | 24        | 5.66%   |
| Unknown | 21        | 4.95%   |
| 800     | 18        | 4.25%   |
| 2133    | 15        | 3.54%   |
| 1334    | 11        | 2.59%   |
| 1066    | 10        | 2.36%   |
| 533     | 10        | 2.36%   |
| 1067    | 9         | 2.12%   |
| 3466    | 8         | 1.89%   |
| 2933    | 8         | 1.89%   |
| 3600    | 5         | 1.18%   |
| 3266    | 5         | 1.18%   |
| 400     | 5         | 1.18%   |
| 4267    | 4         | 0.94%   |
| 3400    | 4         | 0.94%   |
| 1866    | 4         | 0.94%   |
| 4199    | 3         | 0.71%   |
| 1867    | 3         | 0.71%   |
| 333     | 3         | 0.71%   |
| 3000    | 2         | 0.47%   |
| 2733    | 2         | 0.47%   |
| 1800    | 2         | 0.47%   |
| 3733    | 1         | 0.24%   |
| 3333    | 1         | 0.24%   |
| 3007    | 1         | 0.24%   |
| 2800    | 1         | 0.24%   |
| 2666    | 1         | 0.24%   |
| 2048    | 1         | 0.24%   |
| 1639    | 1         | 0.24%   |
| 975     | 1         | 0.24%   |
| 200     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 58.97%  |
| Samsung Electronics | 6         | 15.38%  |
| Canon               | 6         | 15.38%  |
| Seiko Epson         | 1         | 2.56%   |
| Oki Data            | 1         | 2.56%   |
| Konica Minolta      | 1         | 2.56%   |
| Brother Industries  | 1         | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 4         | 10.26%  |
| HP LaserJet P1102                    | 2         | 5.13%   |
| HP DeskJet 3830 series               | 2         | 5.13%   |
| Canon TS3100 series                  | 2         | 5.13%   |
| Seiko Epson L312 Series              | 1         | 2.56%   |
| Samsung SCX-3400 Series              | 1         | 2.56%   |
| Samsung M2070 Series                 | 1         | 2.56%   |
| Oki Data USB Device                  | 1         | 2.56%   |
| Konica Minolta magicolor 1680MF scan | 1         | 2.56%   |
| HP Smart Tank 510 series             | 1         | 2.56%   |
| HP Officejet Pro L7400               | 1         | 2.56%   |
| HP OfficeJet Pro 8020 series         | 1         | 2.56%   |
| HP Officejet J4500 series            | 1         | 2.56%   |
| HP OfficeJet 6200                    | 1         | 2.56%   |
| HP Officejet 4500 G510g-m            | 1         | 2.56%   |
| HP LaserJet 1020                     | 1         | 2.56%   |
| HP LaserJet 1018                     | 1         | 2.56%   |
| HP Laser 107a                        | 1         | 2.56%   |
| HP DeskJet F300 series               | 1         | 2.56%   |
| HP DeskJet F2492 All-in-One          | 1         | 2.56%   |
| HP DeskJet D2300                     | 1         | 2.56%   |
| HP DeskJet 930c                      | 1         | 2.56%   |
| HP DeskJet 840c                      | 1         | 2.56%   |
| HP DeskJet 4670 series               | 1         | 2.56%   |
| HP DeskJet 4530 series               | 1         | 2.56%   |
| HP DeskJet 3700 series               | 1         | 2.56%   |
| HP Deskjet 2640 series               | 1         | 2.56%   |
| HP Color Laser 150nw                 | 1         | 2.56%   |
| Canon TR4500 series                  | 1         | 2.56%   |
| Canon PIXMA MX390 Series             | 1         | 2.56%   |
| Canon PIXMA MG5600 Series            | 1         | 2.56%   |
| Canon PIXMA MG5500 Series            | 1         | 2.56%   |
| Brother HL-2030 Laser Printer        | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |
| Mustek Systems  | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 20%     |
| Mustek Systems BearPaw 1200 CU Plus         | 1         | 20%     |
| HP ScanJet 4370                             | 1         | 20%     |
| Canon CanoScan LiDE 110                     | 1         | 20%     |
| Canon CanoScan LiDE 100                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 103       | 19.96%  |
| IMC Networks                           | 50        | 9.69%   |
| Realtek Semiconductor                  | 47        | 9.11%   |
| Microdia                               | 39        | 7.56%   |
| Logitech                               | 38        | 7.36%   |
| Acer                                   | 37        | 7.17%   |
| Suyin                                  | 30        | 5.81%   |
| Sunplus Innovation Technology          | 18        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.49%   |
| Ricoh                                  | 14        | 2.71%   |
| Quanta                                 | 14        | 2.71%   |
| Microsoft                              | 13        | 2.52%   |
| Alcor Micro                            | 12        | 2.33%   |
| Lite-On Technology                     | 11        | 2.13%   |
| Syntek                                 | 7         | 1.36%   |
| Generalplus Technology                 | 7         | 1.36%   |
| Z-Star Microelectronics                | 6         | 1.16%   |
| Apple                                  | 5         | 0.97%   |
| Silicon Motion                         | 4         | 0.78%   |
| Lenovo                                 | 4         | 0.78%   |
| Aveo Technology                        | 4         | 0.78%   |
| Arkmicro Technologies                  | 4         | 0.78%   |
| Samsung Electronics                    | 3         | 0.58%   |
| Luxvisions Innotech Limited            | 3         | 0.58%   |
| Razer USA                              | 2         | 0.39%   |
| Genesys Logic                          | 2         | 0.39%   |
| Creative Technology                    | 2         | 0.39%   |
| ALi                                    | 2         | 0.39%   |
| Xiongmai                               | 1         | 0.19%   |
| Sweex                                  | 1         | 0.19%   |
| Sonix Technology                       | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Pixart Imaging                         | 1         | 0.19%   |
| Philips (or NXP)                       | 1         | 0.19%   |
| OmniVision Technologies                | 1         | 0.19%   |
| Nokia Mobile Phones                    | 1         | 0.19%   |
| MacroSilicon                           | 1         | 0.19%   |
| Leap Motion                            | 1         | 0.19%   |
| Jieli Technology                       | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |
| Importek                               | 1         | 0.19%   |
| Guillemot                              | 1         | 0.19%   |
| GEMBIRD                                | 1         | 0.19%   |
| eMPIA Technology                       | 1         | 0.19%   |
| Cubeternet                             | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 18        | 3.47%   |
| Logitech Webcam C270                                | 15        | 2.89%   |
| Microdia Integrated_Webcam_HD                       | 13        | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 2.31%   |
| IMC Networks Integrated Camera                      | 12        | 2.31%   |
| Chicony Integrated Camera                           | 12        | 2.31%   |
| Chicony HP Truevision HD                            | 10        | 1.93%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 1.73%   |
| Realtek USB Camera                                  | 8         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 7         | 1.35%   |
| Acer Lenovo EasyCamera                              | 7         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 1.16%   |
| Chicony USB 2.0 Camera                              | 6         | 1.16%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 1.16%   |
| Acer BisonCam, NB Pro                               | 6         | 1.16%   |
| Logitech HD Pro Webcam C920                         | 5         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.96%   |
| Chicony HP Webcam                                   | 5         | 0.96%   |
| Alcor Micro USB 2.0 Camera                          | 5         | 0.96%   |
| Z-Star Venus USB2.0 Camera                          | 4         | 0.77%   |
| Syntek Integrated Camera                            | 4         | 0.77%   |
| Suyin Integrated_Webcam_HD                          | 4         | 0.77%   |
| Realtek Lenovo EasyCamera                           | 4         | 0.77%   |
| Quanta VGA WebCam                                   | 4         | 0.77%   |
| Microsoft LifeCam HD-3000                           | 4         | 0.77%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.77%   |
| Logitech Webcam C310                                | 4         | 0.77%   |
| IMC Networks EasyCamera                             | 4         | 0.77%   |
| Generalplus GENERAL WEBCAM                          | 4         | 0.77%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.77%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.77%   |
| Chicony HD Webcam                                   | 4         | 0.77%   |
| Aveo USB2.0 Camera                                  | 4         | 0.77%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 3         | 0.58%   |
| Suyin HP Truevision HD                              | 3         | 0.58%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 3         | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.58%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 0.58%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 3         | 0.58%   |
| Ricoh USB2.0 Camera                                 | 3         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam                        | 3         | 0.58%   |
| Realtek Integrated Webcam                           | 3         | 0.58%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.58%   |
| Microdia USB 2.0 Camera                             | 3         | 0.58%   |
| Microdia Camera                                     | 3         | 0.58%   |
| Logitech Webcam C300                                | 3         | 0.58%   |
| Logitech Webcam C170                                | 3         | 0.58%   |
| Lite-On Integrated Camera                           | 3         | 0.58%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.58%   |
| Generalplus 808 Camera #9 (web-cam mode)            | 3         | 0.58%   |
| Chicony VGA WebCam                                  | 3         | 0.58%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.58%   |
| Chicony HP Integrated Webcam                        | 3         | 0.58%   |
| Chicony HP HD Webcam                                | 3         | 0.58%   |
| Chicony EasyCamera                                  | 3         | 0.58%   |
| Chicony CKF7063 Webcam (HP)                         | 3         | 0.58%   |
| Arkmicro USB2.0 PC CAMERA                           | 3         | 0.58%   |
| Alcor Micro HP Webcam-101                           | 3         | 0.58%   |
| Acer USB2.0 Camera                                  | 3         | 0.58%   |
| Acer SunplusIT Integrated Camera                    | 3         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 27.78%  |
| Synaptics                  | 17        | 23.61%  |
| AuthenTec                  | 12        | 16.67%  |
| Upek                       | 10        | 13.89%  |
| Shenzhen Goodix Technology | 9         | 12.5%   |
| Elan Microelectronics      | 2         | 2.78%   |
| STMicroelectronics         | 1         | 1.39%   |
| LighTuning Technology      | 1         | 1.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 8.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.56%   |
| Synaptics  WBDI                                                            | 4         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.17%   |
| AuthenTec AES2810                                                          | 3         | 4.17%   |
| Unknown                                                                    | 3         | 4.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.78%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.78%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.39%   |
| Validity Sensors VFS491                                                    | 1         | 1.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.39%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.39%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.39%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.39%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.39%   |
| AuthenTec AES1600                                                          | 1         | 1.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 54.05%  |
| Alcor Micro | 7         | 18.92%  |
| O2 Micro    | 4         | 10.81%  |
| Upek        | 3         | 8.11%   |
| Lenovo      | 2         | 5.41%   |
| Yubico.com  | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 8         | 21.62%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 18.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 18.92%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10.81%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 8.11%   |
| Broadcom 5880                                                                | 3         | 8.11%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.41%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 673       | 72.91%  |
| 1     | 204       | 22.1%   |
| 2     | 38        | 4.12%   |
| 3     | 6         | 0.65%   |
| 6     | 1         | 0.11%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 24.41%  |
| Graphics card            | 53        | 17.97%  |
| Net/wireless             | 44        | 14.92%  |
| Chipcard                 | 33        | 11.19%  |
| Multimedia controller    | 17        | 5.76%   |
| Bluetooth                | 17        | 5.76%   |
| Communication controller | 12        | 4.07%   |
| Sound                    | 7         | 2.37%   |
| Modem                    | 7         | 2.37%   |
| Camera                   | 7         | 2.37%   |
| Storage                  | 5         | 1.69%   |
| Flash memory             | 4         | 1.36%   |
| Net/ethernet             | 3         | 1.02%   |
| Dvb card                 | 3         | 1.02%   |
| Card reader              | 3         | 1.02%   |
| Unassigned class         | 2         | 0.68%   |
| Network                  | 2         | 0.68%   |
| Firewire controller      | 2         | 0.68%   |
| Tv card                  | 1         | 0.34%   |
| Storage/raid             | 1         | 0.34%   |
