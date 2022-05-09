Linux in Norway - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

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

Total: 643

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5430 non-vPro     | [2075bfcc02](https://linux-hardware.org/?probe=2075bfcc02) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | [71f8f45765](https://linux-hardware.org/?probe=71f8f45765) | May 05, 2022 |
| HP            | ProBook 4330s               | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Acer          | Swift SF514-51              | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| Dell          | Latitude E6430              | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| Google        | Cave                        | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| Lenovo        | V130-14IKB 81HQ             | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| ASUSTek       | K52Dr                       | [29124147fe](https://linux-hardware.org/?probe=29124147fe) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490s 20NX003UM... | [60dca75a93](https://linux-hardware.org/?probe=60dca75a93) | Apr 14, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [7f83d03bf3](https://linux-hardware.org/?probe=7f83d03bf3) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [bbcb05781f](https://linux-hardware.org/?probe=bbcb05781f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [8421f0505f](https://linux-hardware.org/?probe=8421f0505f) | Apr 13, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| HP            | EliteBook 840 G4            | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| Dell          | Inspiron 5370               | [abc7562fb9](https://linux-hardware.org/?probe=abc7562fb9) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [79c6231f19](https://linux-hardware.org/?probe=79c6231f19) | Apr 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| HP            | EliteBook 840 G4            | [16262ac312](https://linux-hardware.org/?probe=16262ac312) | Mar 31, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [ea012026c5](https://linux-hardware.org/?probe=ea012026c5) | Mar 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a68b0e55c](https://linux-hardware.org/?probe=0a68b0e55c) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | GL502VMK                    | [f2fedaa3c3](https://linux-hardware.org/?probe=f2fedaa3c3) | Mar 18, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [acef37559c](https://linux-hardware.org/?probe=acef37559c) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [884e853e6f](https://linux-hardware.org/?probe=884e853e6f) | Mar 14, 2022 |
| Intel Clie... | LAPQC71A                    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Dell          | Latitude 5480               | [d7fe091593](https://linux-hardware.org/?probe=d7fe091593) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Lenovo        | ThinkPad T480 20L60033MX    | [fda7557aa0](https://linux-hardware.org/?probe=fda7557aa0) | Mar 07, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Lenovo        | ThinkPad Edge E330 3354D... | [0337480978](https://linux-hardware.org/?probe=0337480978) | Feb 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| HP            | ProBook 4330s               | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| ASUSTek       | G74Sx                       | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [ab580c3edd](https://linux-hardware.org/?probe=ab580c3edd) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [c11f9d5c6d](https://linux-hardware.org/?probe=c11f9d5c6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0FJ0... | [6dc9215373](https://linux-hardware.org/?probe=6dc9215373) | Feb 07, 2022 |
| Acer          | Swift SF314-511             | [9f7733e6ec](https://linux-hardware.org/?probe=9f7733e6ec) | Feb 03, 2022 |
| Dell          | Latitude E4200              | [35dbab3b2e](https://linux-hardware.org/?probe=35dbab3b2e) | Jan 31, 2022 |
| Toshiba       | Satellite C660D             | [d6498c16bb](https://linux-hardware.org/?probe=d6498c16bb) | Jan 27, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [698c80468a](https://linux-hardware.org/?probe=698c80468a) | Jan 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b9dfe5b842](https://linux-hardware.org/?probe=b9dfe5b842) | Jan 21, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [6b9dcc88b7](https://linux-hardware.org/?probe=6b9dcc88b7) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [beb9306791](https://linux-hardware.org/?probe=beb9306791) | Jan 21, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Lenovo        | G50-30 80G0                 | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| HP            | Laptop 17-cn0xxx            | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Dell          | Precision 7560              | [a58a852902](https://linux-hardware.org/?probe=a58a852902) | Jan 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | [831591fe79](https://linux-hardware.org/?probe=831591fe79) | Jan 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [62bf8bc805](https://linux-hardware.org/?probe=62bf8bc805) | Jan 10, 2022 |
| MSI           | GS66 Stealth 10UH           | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Dell          | Latitude 5480               | [c572bd1eac](https://linux-hardware.org/?probe=c572bd1eac) | Jan 08, 2022 |
| Apple         | MacBookPro9,2               | [b5bd2eca7d](https://linux-hardware.org/?probe=b5bd2eca7d) | Jan 07, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [60b74121ad](https://linux-hardware.org/?probe=60b74121ad) | Jan 02, 2022 |
| Lenovo        | ThinkPad T410s 2924W79      | [43fe13f2a4](https://linux-hardware.org/?probe=43fe13f2a4) | Dec 30, 2021 |
| Dell          | Latitude 5480               | [e560c10eb8](https://linux-hardware.org/?probe=e560c10eb8) | Dec 29, 2021 |
| Acer          | Aspire E1-572               | [ab9c63e097](https://linux-hardware.org/?probe=ab9c63e097) | Dec 28, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [04ebd359f1](https://linux-hardware.org/?probe=04ebd359f1) | Dec 28, 2021 |
| Acer          | Aspire E1-572               | [63f4428f24](https://linux-hardware.org/?probe=63f4428f24) | Dec 28, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| HP            | ZBook 15                    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Dell          | Latitude 5480               | [5c91ed91a8](https://linux-hardware.org/?probe=5c91ed91a8) | Dec 24, 2021 |
| Acer          | Aspire xxxx                 | [13b21c09d2](https://linux-hardware.org/?probe=13b21c09d2) | Dec 23, 2021 |
| Dell          | XPS 15 9500                 | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Lenovo        | ThinkPad T410s 2924W79      | [f26b8b4f98](https://linux-hardware.org/?probe=f26b8b4f98) | Dec 17, 2021 |
| Acer          | Aspire xxxx                 | [dfa568d766](https://linux-hardware.org/?probe=dfa568d766) | Dec 17, 2021 |
| Toshiba       | Satellite L750              | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| HP            | ZBook 15                    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| HP            | ZBook 15                    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | N550JV                      | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | OMEN by Laptop              | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [c579de06b5](https://linux-hardware.org/?probe=c579de06b5) | Dec 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Acer          | Aspire A114-32              | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| Acer          | Aspire A114-32              | [2135c64df3](https://linux-hardware.org/?probe=2135c64df3) | Nov 28, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| Acer          | Aspire A114-32              | [1a5573373d](https://linux-hardware.org/?probe=1a5573373d) | Nov 26, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [969dde57b0](https://linux-hardware.org/?probe=969dde57b0) | Nov 22, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [1d12ea147a](https://linux-hardware.org/?probe=1d12ea147a) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [c6e0003dcb](https://linux-hardware.org/?probe=c6e0003dcb) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [6b485f4c9a](https://linux-hardware.org/?probe=6b485f4c9a) | Nov 20, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | ProBook 440 G4              | [f5d53e44ae](https://linux-hardware.org/?probe=f5d53e44ae) | Nov 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| Lenovo        | ThinkPad W540 20BHS0NQ00    | [69f4b3d974](https://linux-hardware.org/?probe=69f4b3d974) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0b7ae3ebf5](https://linux-hardware.org/?probe=0b7ae3ebf5) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Acer          | Aspire 5739G                | [9366122bdb](https://linux-hardware.org/?probe=9366122bdb) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [aaf8f33249](https://linux-hardware.org/?probe=aaf8f33249) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [00eedd879b](https://linux-hardware.org/?probe=00eedd879b) | Oct 30, 2021 |
| Acer          | Aspire 5739G                | [7979c29593](https://linux-hardware.org/?probe=7979c29593) | Oct 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [df466b506d](https://linux-hardware.org/?probe=df466b506d) | Oct 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [748d3e56a7](https://linux-hardware.org/?probe=748d3e56a7) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Dell          | XPS 15 9570                 | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [fe7520a392](https://linux-hardware.org/?probe=fe7520a392) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8fab065f3b](https://linux-hardware.org/?probe=8fab065f3b) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8502c5d5f7](https://linux-hardware.org/?probe=8502c5d5f7) | Oct 13, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [d7f1b3f27e](https://linux-hardware.org/?probe=d7f1b3f27e) | Oct 12, 2021 |
| Acer          | Aspire A515-45              | [4b45531984](https://linux-hardware.org/?probe=4b45531984) | Oct 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Acer          | Aspire A114-32              | [7820ed30d6](https://linux-hardware.org/?probe=7820ed30d6) | Sep 30, 2021 |
| Acer          | Aspire A114-32              | [e1dc7a64a4](https://linux-hardware.org/?probe=e1dc7a64a4) | Sep 30, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [51346d44d3](https://linux-hardware.org/?probe=51346d44d3) | Sep 26, 2021 |
| Dell          | Latitude E5530 non-vPro     | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [bf5a5a2c74](https://linux-hardware.org/?probe=bf5a5a2c74) | Sep 26, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| Dell          | XPS 15 9570                 | [a54466b990](https://linux-hardware.org/?probe=a54466b990) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| Dell          | Latitude E5470              | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| ASUSTek       | E402NA                      | [8262dd102f](https://linux-hardware.org/?probe=8262dd102f) | Sep 23, 2021 |
| Lenovo        | ThinkPad E15 20RES6DF07     | [2f5045ab95](https://linux-hardware.org/?probe=2f5045ab95) | Sep 21, 2021 |
| Acer          | Aspire A114-32              | [333d881ec2](https://linux-hardware.org/?probe=333d881ec2) | Sep 20, 2021 |
| Acer          | Aspire A114-32              | [da860f1378](https://linux-hardware.org/?probe=da860f1378) | Sep 20, 2021 |
| HUAWEI        | EUL-WX9                     | [4ab59b64df](https://linux-hardware.org/?probe=4ab59b64df) | Sep 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Latitude 5480               | [ac2c5649d3](https://linux-hardware.org/?probe=ac2c5649d3) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a92f9c3457](https://linux-hardware.org/?probe=a92f9c3457) | Sep 15, 2021 |
| HP            | EliteBook 820 G1            | [cf1e0581f3](https://linux-hardware.org/?probe=cf1e0581f3) | Sep 15, 2021 |
| MSI           | Alpha 17 A4DE               | [0be8b0b607](https://linux-hardware.org/?probe=0be8b0b607) | Sep 14, 2021 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [2b5735f34c](https://linux-hardware.org/?probe=2b5735f34c) | Sep 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [0918a27e6a](https://linux-hardware.org/?probe=0918a27e6a) | Sep 08, 2021 |
| Acer          | Aspire 5745G                | [680d788d4b](https://linux-hardware.org/?probe=680d788d4b) | Sep 07, 2021 |
| Acer          | Aspire 5745G                | [34e858aa67](https://linux-hardware.org/?probe=34e858aa67) | Sep 07, 2021 |
| MSI           | Alpha 17 A4DE               | [3f0de31253](https://linux-hardware.org/?probe=3f0de31253) | Sep 06, 2021 |
| Dell          | Precision 5510              | [1339721ac0](https://linux-hardware.org/?probe=1339721ac0) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [7bc3201683](https://linux-hardware.org/?probe=7bc3201683) | Sep 06, 2021 |
| Samsung       | RF511/RF411/RF711           | [332124aa7f](https://linux-hardware.org/?probe=332124aa7f) | Sep 04, 2021 |
| Acer          | Aspire A515-45              | [16a250faf6](https://linux-hardware.org/?probe=16a250faf6) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| Dell          | Latitude E7270              | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| ASUSTek       | UX430UQ                     | [2bd5adb706](https://linux-hardware.org/?probe=2bd5adb706) | Aug 31, 2021 |
| Acer          | Aspire 5745G                | [2e54861625](https://linux-hardware.org/?probe=2e54861625) | Aug 30, 2021 |
| Lenovo        | G710 20252                  | [bcb68ab6d0](https://linux-hardware.org/?probe=bcb68ab6d0) | Aug 21, 2021 |
| Dell          | Studio 1747                 | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| Teclast       | F6 Plus                     | [a1df449dea](https://linux-hardware.org/?probe=a1df449dea) | Aug 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5742cb7dd7](https://linux-hardware.org/?probe=5742cb7dd7) | Aug 12, 2021 |
| Alienware     | x17 R1                      | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| Apple         | MacBookPro11,5              | [938ff270ef](https://linux-hardware.org/?probe=938ff270ef) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| HP            | ProBook 4740s               | [624b649eb0](https://linux-hardware.org/?probe=624b649eb0) | Jul 28, 2021 |
| HP            | EliteBook 1040 G4           | [693137b6b8](https://linux-hardware.org/?probe=693137b6b8) | Jul 26, 2021 |
| Dell          | Latitude 5480               | [64665ed287](https://linux-hardware.org/?probe=64665ed287) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Presario CQ56               | [7148aa989e](https://linux-hardware.org/?probe=7148aa989e) | Jul 21, 2021 |
| Apple         | MacBook8,1                  | [1220a734d7](https://linux-hardware.org/?probe=1220a734d7) | Jul 20, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [788b497894](https://linux-hardware.org/?probe=788b497894) | Jul 19, 2021 |
| Dell          | XPS 15 9500                 | [610bb918de](https://linux-hardware.org/?probe=610bb918de) | Jul 14, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [eba2e6ade8](https://linux-hardware.org/?probe=eba2e6ade8) | Jul 13, 2021 |
| HP            | Presario CQ56               | [7a202a99e9](https://linux-hardware.org/?probe=7a202a99e9) | Jul 11, 2021 |
| Acer          | Aspire E5-575G              | [27fd4c16ae](https://linux-hardware.org/?probe=27fd4c16ae) | Jul 08, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [b8a40b6dbd](https://linux-hardware.org/?probe=b8a40b6dbd) | Jul 02, 2021 |
| Lenovo        | G50-80 80L0                 | [ca1d482329](https://linux-hardware.org/?probe=ca1d482329) | Jun 27, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| Lenovo        | ThinkPad T460s 20FA0047M... | [eeb383631b](https://linux-hardware.org/?probe=eeb383631b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T520 4243W83       | [b17a1f2c15](https://linux-hardware.org/?probe=b17a1f2c15) | Jun 19, 2021 |
| HP            | EliteBook 820 G1            | [09ff787c3f](https://linux-hardware.org/?probe=09ff787c3f) | Jun 17, 2021 |
| HP            | EliteBook 820 G1            | [b64bd1afcd](https://linux-hardware.org/?probe=b64bd1afcd) | Jun 17, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [bbedefdee0](https://linux-hardware.org/?probe=bbedefdee0) | Jun 16, 2021 |
| Dell          | XPS 13 9380                 | [41972327e1](https://linux-hardware.org/?probe=41972327e1) | Jun 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440p 20AW0048G... | [8b1ba139f9](https://linux-hardware.org/?probe=8b1ba139f9) | Jun 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [9674952e07](https://linux-hardware.org/?probe=9674952e07) | Jun 11, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [b39699b009](https://linux-hardware.org/?probe=b39699b009) | Jun 11, 2021 |
| Lenovo        | ThinkPad T410s 291236G      | [ebbdc74a27](https://linux-hardware.org/?probe=ebbdc74a27) | Jun 06, 2021 |
| Acer          | Nitro AN515-42              | [28aadacd07](https://linux-hardware.org/?probe=28aadacd07) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [aef8c27b50](https://linux-hardware.org/?probe=aef8c27b50) | May 31, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| HUAWEI        | MACH-WX9                    | [7fd687d091](https://linux-hardware.org/?probe=7fd687d091) | May 29, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| ASUSTek       | N53TK                       | [cee81adbaf](https://linux-hardware.org/?probe=cee81adbaf) | May 25, 2021 |
| Dell          | XPS 15 9500                 | [8c072ea1c4](https://linux-hardware.org/?probe=8c072ea1c4) | May 24, 2021 |
| Acer          | Aspire 5745G                | [30f455f132](https://linux-hardware.org/?probe=30f455f132) | May 22, 2021 |
| HP            | Spectre Pro x360 G2         | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Acer          | Aspire 5745G                | [cb987a733a](https://linux-hardware.org/?probe=cb987a733a) | May 15, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [c4b7c3340c](https://linux-hardware.org/?probe=c4b7c3340c) | May 11, 2021 |
| Toshiba       | Satellite L510              | [01753d1f93](https://linux-hardware.org/?probe=01753d1f93) | May 02, 2021 |
| Acer          | TravelMate 8472             | [bdf53780fb](https://linux-hardware.org/?probe=bdf53780fb) | May 01, 2021 |
| Lenovo        | ThinkPad T490s 20NX0054M... | [4cc25622a5](https://linux-hardware.org/?probe=4cc25622a5) | Apr 28, 2021 |
| Acer          | TravelMate 8472             | [84fea7d029](https://linux-hardware.org/?probe=84fea7d029) | Apr 25, 2021 |
| Acer          | TravelMate 8472             | [a4aafc8541](https://linux-hardware.org/?probe=a4aafc8541) | Apr 25, 2021 |
| MSI           | MS-175A                     | [3e3f73559d](https://linux-hardware.org/?probe=3e3f73559d) | Apr 23, 2021 |
| MSI           | MS-175A                     | [22e9e676d9](https://linux-hardware.org/?probe=22e9e676d9) | Apr 23, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [58df3a61b0](https://linux-hardware.org/?probe=58df3a61b0) | Apr 21, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [67c2373bdf](https://linux-hardware.org/?probe=67c2373bdf) | Apr 15, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [7143a1f845](https://linux-hardware.org/?probe=7143a1f845) | Apr 15, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [db960abcdb](https://linux-hardware.org/?probe=db960abcdb) | Apr 15, 2021 |
| Dell          | XPS 13 9380                 | [cf23d87096](https://linux-hardware.org/?probe=cf23d87096) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| Dell          | XPS 13 9380                 | [1631f6bb81](https://linux-hardware.org/?probe=1631f6bb81) | Apr 06, 2021 |
| HP            | ProBook 430 G1              | [6d2b17825a](https://linux-hardware.org/?probe=6d2b17825a) | Apr 05, 2021 |
| Dell          | Latitude E6530              | [0078b55697](https://linux-hardware.org/?probe=0078b55697) | Apr 05, 2021 |
| Acer          | Aspire V3-571G              | [a5268098b2](https://linux-hardware.org/?probe=a5268098b2) | Apr 02, 2021 |
| Dell          | Studio 1747                 | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| HP            | Pavilion Notebook           | [6189b0e033](https://linux-hardware.org/?probe=6189b0e033) | Mar 27, 2021 |
| HP            | Pavilion Notebook           | [df09bd2c58](https://linux-hardware.org/?probe=df09bd2c58) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad X201 4492A23       | [0cace83a52](https://linux-hardware.org/?probe=0cace83a52) | Mar 23, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [45dfd87503](https://linux-hardware.org/?probe=45dfd87503) | Mar 22, 2021 |
| ASUSTek       | GL553VW                     | [7d8aed9645](https://linux-hardware.org/?probe=7d8aed9645) | Mar 21, 2021 |
| Acer          | Nitro AN515-51              | [79b5d4aed8](https://linux-hardware.org/?probe=79b5d4aed8) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1725699a96](https://linux-hardware.org/?probe=1725699a96) | Mar 12, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [f55532e284](https://linux-hardware.org/?probe=f55532e284) | Mar 12, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e74933164b](https://linux-hardware.org/?probe=e74933164b) | Mar 10, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [406b41e802](https://linux-hardware.org/?probe=406b41e802) | Mar 10, 2021 |
| HP            | EliteBook 830 G6            | [45f8bdabb0](https://linux-hardware.org/?probe=45f8bdabb0) | Mar 09, 2021 |
| HP            | EliteBook 830 G6            | [de6b1ee9fe](https://linux-hardware.org/?probe=de6b1ee9fe) | Mar 09, 2021 |
| HP            | EliteBook 8470p             | [d97eb7724a](https://linux-hardware.org/?probe=d97eb7724a) | Mar 04, 2021 |
| Acer          | Aspire E5-575G              | [9f523080d5](https://linux-hardware.org/?probe=9f523080d5) | Mar 03, 2021 |
| Dell          | Precision 5550              | [98abf3a7d0](https://linux-hardware.org/?probe=98abf3a7d0) | Mar 02, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8235a48b49](https://linux-hardware.org/?probe=8235a48b49) | Feb 26, 2021 |
| HP            | EliteBook 820 G3            | [22a4daed00](https://linux-hardware.org/?probe=22a4daed00) | Feb 25, 2021 |
| HP            | ZBook 15 G3                 | [7c24c07795](https://linux-hardware.org/?probe=7c24c07795) | Feb 25, 2021 |
| HP            | OMEN by HP Laptop 17-cb0... | [a2fdf109b0](https://linux-hardware.org/?probe=a2fdf109b0) | Feb 20, 2021 |
| HP            | Pavilion Notebook           | [db4bc9fa7a](https://linux-hardware.org/?probe=db4bc9fa7a) | Feb 20, 2021 |
| Lenovo        | ThinkPad T460s 20F90057M... | [2bf00440b7](https://linux-hardware.org/?probe=2bf00440b7) | Feb 18, 2021 |
| Apple         | MacBookAir7,2               | [01c84ea037](https://linux-hardware.org/?probe=01c84ea037) | Feb 18, 2021 |
| Lenovo        | Z50-70 20354                | [84b15e21ec](https://linux-hardware.org/?probe=84b15e21ec) | Feb 17, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [626009a335](https://linux-hardware.org/?probe=626009a335) | Feb 16, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [d11dd1d1a0](https://linux-hardware.org/?probe=d11dd1d1a0) | Feb 14, 2021 |
| Packard Be... | SJV50MV                     | [aba113ee3f](https://linux-hardware.org/?probe=aba113ee3f) | Feb 14, 2021 |
| ASUSTek       | X556URK                     | [6af569fcf4](https://linux-hardware.org/?probe=6af569fcf4) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [9a71946a9e](https://linux-hardware.org/?probe=9a71946a9e) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [f43d50a826](https://linux-hardware.org/?probe=f43d50a826) | Feb 13, 2021 |
| ASUSTek       | X55U                        | [aea7a001db](https://linux-hardware.org/?probe=aea7a001db) | Feb 13, 2021 |
| Unknown       | T3 MRD                      | [a71b7acc18](https://linux-hardware.org/?probe=a71b7acc18) | Feb 10, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [f26de119c9](https://linux-hardware.org/?probe=f26de119c9) | Feb 08, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [670ce5270a](https://linux-hardware.org/?probe=670ce5270a) | Feb 07, 2021 |
| Acer          | NG-AN515-52-74W6            | [70574e752f](https://linux-hardware.org/?probe=70574e752f) | Feb 05, 2021 |
| Clevo         | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| ASUSTek       | N501VW                      | [a5a63c6343](https://linux-hardware.org/?probe=a5a63c6343) | Feb 01, 2021 |
| Acer          | Aspire M3-581TG             | [f87979122a](https://linux-hardware.org/?probe=f87979122a) | Jan 31, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [c71286b553](https://linux-hardware.org/?probe=c71286b553) | Jan 31, 2021 |
| Apple         | MacBookAir4,2               | [590fdfe6bb](https://linux-hardware.org/?probe=590fdfe6bb) | Jan 30, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Lenovo        | ThinkPad T500 22439AG       | [fe8ffb1fc3](https://linux-hardware.org/?probe=fe8ffb1fc3) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [a2b88b8f9d](https://linux-hardware.org/?probe=a2b88b8f9d) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [29f9f04453](https://linux-hardware.org/?probe=29f9f04453) | Jan 27, 2021 |
| Lenovo        | ThinkPad T480 20L6002DMX    | [5dd69602d6](https://linux-hardware.org/?probe=5dd69602d6) | Jan 27, 2021 |
| ASUSTek       | GL753VE                     | [af8e0933c0](https://linux-hardware.org/?probe=af8e0933c0) | Jan 24, 2021 |
| Acer          | NU-A515-44-R68D             | [69612ffeb2](https://linux-hardware.org/?probe=69612ffeb2) | Jan 20, 2021 |
| Acer          | Swift SF314-42              | [daeea162bf](https://linux-hardware.org/?probe=daeea162bf) | Jan 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [aca39bcba0](https://linux-hardware.org/?probe=aca39bcba0) | Jan 18, 2021 |
| MSI           | GE72VR 7RF                  | [1dfd19668d](https://linux-hardware.org/?probe=1dfd19668d) | Jan 14, 2021 |
| Acer          | NU-A515-44-R68D             | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [69a7ec5b7c](https://linux-hardware.org/?probe=69a7ec5b7c) | Jan 07, 2021 |
| Acer          | Swift SF314-42              | [5761cc2a05](https://linux-hardware.org/?probe=5761cc2a05) | Jan 06, 2021 |
| Dell          | XPS 15 7590                 | [69a5abe225](https://linux-hardware.org/?probe=69a5abe225) | Jan 05, 2021 |
| ASUSTek       | GL552JX                     | [5dd9cde584](https://linux-hardware.org/?probe=5dd9cde584) | Jan 03, 2021 |
| ASUSTek       | GL552JX                     | [4dfc0f1909](https://linux-hardware.org/?probe=4dfc0f1909) | Jan 03, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [70d4988c38](https://linux-hardware.org/?probe=70d4988c38) | Dec 30, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [bef81325c0](https://linux-hardware.org/?probe=bef81325c0) | Dec 27, 2020 |
| ASUSTek       | G75VW                       | [d04692210c](https://linux-hardware.org/?probe=d04692210c) | Dec 23, 2020 |
| ASUSTek       | G75VW                       | [cc1a212c60](https://linux-hardware.org/?probe=cc1a212c60) | Dec 23, 2020 |
| ASUSTek       | N61Ja                       | [324c64905b](https://linux-hardware.org/?probe=324c64905b) | Dec 20, 2020 |
| Dell          | Latitude E6420              | [d4e4d15cf4](https://linux-hardware.org/?probe=d4e4d15cf4) | Dec 20, 2020 |
| Acer          | Swift SF514-51              | [f04b672d42](https://linux-hardware.org/?probe=f04b672d42) | Dec 15, 2020 |
| Acer          | Swift SF514-51              | [31b51cc2b0](https://linux-hardware.org/?probe=31b51cc2b0) | Dec 13, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [7a59304f76](https://linux-hardware.org/?probe=7a59304f76) | Dec 08, 2020 |
| Dell          | XPS 15 9570                 | [d164834ae1](https://linux-hardware.org/?probe=d164834ae1) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | [5031a2060f](https://linux-hardware.org/?probe=5031a2060f) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | [b30cae7041](https://linux-hardware.org/?probe=b30cae7041) | Dec 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [80b2a9b7a0](https://linux-hardware.org/?probe=80b2a9b7a0) | Dec 01, 2020 |
| Dell          | Precision 5530              | [2d3e299290](https://linux-hardware.org/?probe=2d3e299290) | Nov 29, 2020 |
| Dell          | XPS 13 9380                 | [c27456cd80](https://linux-hardware.org/?probe=c27456cd80) | Nov 28, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [0b39212390](https://linux-hardware.org/?probe=0b39212390) | Nov 26, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [cb0b2991f5](https://linux-hardware.org/?probe=cb0b2991f5) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | [29f9bd8133](https://linux-hardware.org/?probe=29f9bd8133) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | [c7a03e79d1](https://linux-hardware.org/?probe=c7a03e79d1) | Nov 26, 2020 |
| HP            | EliteBook 840 G1            | [44f18b2c9c](https://linux-hardware.org/?probe=44f18b2c9c) | Nov 25, 2020 |
| Dell          | XPS 15 9530                 | [498a6352ca](https://linux-hardware.org/?probe=498a6352ca) | Nov 17, 2020 |
| HP            | Presario CQ56               | [dc13808697](https://linux-hardware.org/?probe=dc13808697) | Nov 15, 2020 |
| HP            | EliteBook 840 G4            | [5476e88101](https://linux-hardware.org/?probe=5476e88101) | Nov 13, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [94c7b24f6f](https://linux-hardware.org/?probe=94c7b24f6f) | Nov 12, 2020 |
| HP            | EliteBook 840 G4            | [365d184384](https://linux-hardware.org/?probe=365d184384) | Nov 12, 2020 |
| Acer          | Swift SF314-42              | [b1d5b6d202](https://linux-hardware.org/?probe=b1d5b6d202) | Nov 11, 2020 |
| Razer         | Blade 15 Base Model (Ear... | [8aaa52acfe](https://linux-hardware.org/?probe=8aaa52acfe) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | [1edba5531d](https://linux-hardware.org/?probe=1edba5531d) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | [c8f54522bc](https://linux-hardware.org/?probe=c8f54522bc) | Nov 11, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [2c04018d8b](https://linux-hardware.org/?probe=2c04018d8b) | Nov 10, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [e1bfa030b6](https://linux-hardware.org/?probe=e1bfa030b6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d80b3d6e1b](https://linux-hardware.org/?probe=d80b3d6e1b) | Nov 10, 2020 |
| Apple         | MacBookPro10,1              | [de48058cc4](https://linux-hardware.org/?probe=de48058cc4) | Nov 07, 2020 |
| Lenovo        | ThinkPad T470s 20HGS33N0... | [46e54eb12c](https://linux-hardware.org/?probe=46e54eb12c) | Nov 05, 2020 |
| ASUSTek       | E203NA                      | [83f3bbfada](https://linux-hardware.org/?probe=83f3bbfada) | Nov 05, 2020 |
| Acer          | Aspire V3-571G              | [43a7cef240](https://linux-hardware.org/?probe=43a7cef240) | Nov 01, 2020 |
| Razer         | Blade 15 Base Model (Ear... | [5ec26083ab](https://linux-hardware.org/?probe=5ec26083ab) | Oct 31, 2020 |
| Acer          | Swift SF314-42              | [2b56b5b407](https://linux-hardware.org/?probe=2b56b5b407) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | [4b0d12f5b0](https://linux-hardware.org/?probe=4b0d12f5b0) | Oct 29, 2020 |
| Acer          | Aspire V3-571G              | [aed3a57697](https://linux-hardware.org/?probe=aed3a57697) | Oct 28, 2020 |
| HP            | EliteBook 8540w             | [22041bab6b](https://linux-hardware.org/?probe=22041bab6b) | Oct 28, 2020 |
| HP            | Pavilion g6                 | [de072f8297](https://linux-hardware.org/?probe=de072f8297) | Oct 26, 2020 |
| HP            | EliteBook 8540w             | [d7a8999c8f](https://linux-hardware.org/?probe=d7a8999c8f) | Oct 22, 2020 |
| HP            | EliteBook 840 G6            | [47c1ff9096](https://linux-hardware.org/?probe=47c1ff9096) | Oct 19, 2020 |
| HP            | EliteBook 725 G2            | [fbdc47c84f](https://linux-hardware.org/?probe=fbdc47c84f) | Oct 15, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| HP            | ProBook 6475b               | [c547b7b23e](https://linux-hardware.org/?probe=c547b7b23e) | Oct 11, 2020 |
| Clevo         | W150HRM                     | [8859e15cb5](https://linux-hardware.org/?probe=8859e15cb5) | Oct 10, 2020 |
| Acer          | Swift SF314-42              | [6eed561c0c](https://linux-hardware.org/?probe=6eed561c0c) | Oct 07, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Toshiba       | Satellite A100              | [93f3a15a9e](https://linux-hardware.org/?probe=93f3a15a9e) | Oct 04, 2020 |
| Toshiba       | Satellite C55-A-1MW         | [a0a0d949d6](https://linux-hardware.org/?probe=a0a0d949d6) | Oct 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06cc9298b0](https://linux-hardware.org/?probe=06cc9298b0) | Oct 02, 2020 |
| Acer          | Swift SF314-42              | [2d84532f4b](https://linux-hardware.org/?probe=2d84532f4b) | Sep 30, 2020 |
| Acer          | Swift SF314-42              | [040ebde0a0](https://linux-hardware.org/?probe=040ebde0a0) | Sep 30, 2020 |
| HP            | EliteBook 830 G6            | [f3313ab891](https://linux-hardware.org/?probe=f3313ab891) | Sep 28, 2020 |
| Apple         | MacBook2,1                  | [a11af3313e](https://linux-hardware.org/?probe=a11af3313e) | Sep 28, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| HP            | ProBook 6550b               | [b5e0d7059d](https://linux-hardware.org/?probe=b5e0d7059d) | Sep 25, 2020 |
| Acer          | Swift SF314-42              | [710530e3b4](https://linux-hardware.org/?probe=710530e3b4) | Sep 23, 2020 |
| ASUSTek       | K75DE                       | [f58f907928](https://linux-hardware.org/?probe=f58f907928) | Sep 20, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [88f6a44ae4](https://linux-hardware.org/?probe=88f6a44ae4) | Sep 17, 2020 |
| Acer          | Swift SF314-42              | [07a0b1c144](https://linux-hardware.org/?probe=07a0b1c144) | Sep 14, 2020 |
| Acer          | Swift SF314-42              | [e535312c87](https://linux-hardware.org/?probe=e535312c87) | Sep 14, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9adcfd59a](https://linux-hardware.org/?probe=c9adcfd59a) | Sep 13, 2020 |
| HP            | EliteBook Revolve 810 G2    | [5aaf924422](https://linux-hardware.org/?probe=5aaf924422) | Sep 13, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Acer          | Swift SF314-42              | [488f845e14](https://linux-hardware.org/?probe=488f845e14) | Sep 10, 2020 |
| Acer          | Swift SF314-42              | [8a98439ec4](https://linux-hardware.org/?probe=8a98439ec4) | Sep 08, 2020 |
| Acer          | Swift SF314-42              | [c5d49dd8ff](https://linux-hardware.org/?probe=c5d49dd8ff) | Sep 08, 2020 |
| Lenovo        | ThinkPad S2 20GKS03C00      | [3db4820f00](https://linux-hardware.org/?probe=3db4820f00) | Sep 05, 2020 |
| Acer          | Swift SF314-42              | [ce9ddc343f](https://linux-hardware.org/?probe=ce9ddc343f) | Sep 04, 2020 |
| Acer          | Swift SF314-42              | [fcce649648](https://linux-hardware.org/?probe=fcce649648) | Sep 04, 2020 |
| Dell          | XPS 13 9380                 | [d97dc026d9](https://linux-hardware.org/?probe=d97dc026d9) | Sep 03, 2020 |
| Clevo         | P15xEMx                     | [6aa236976d](https://linux-hardware.org/?probe=6aa236976d) | Sep 03, 2020 |
| HP            | EliteBook Revolve 810 G2    | [62bf637d91](https://linux-hardware.org/?probe=62bf637d91) | Sep 02, 2020 |
| HP            | EliteBook Revolve 810 G2    | [dd002c86c4](https://linux-hardware.org/?probe=dd002c86c4) | Sep 02, 2020 |
| Lenovo        | ThinkPad X201 3323BSG       | [16840940a8](https://linux-hardware.org/?probe=16840940a8) | Sep 02, 2020 |
| Apple         | MacBookPro12,1              | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| Apple         | MacBookPro12,1              | [d48e12ebbd](https://linux-hardware.org/?probe=d48e12ebbd) | Aug 31, 2020 |
| HP            | EliteBook 840 G3            | [e87474d550](https://linux-hardware.org/?probe=e87474d550) | Aug 31, 2020 |
| Dell          | Latitude E7450              | [96a90e1ad3](https://linux-hardware.org/?probe=96a90e1ad3) | Aug 30, 2020 |
| HP            | EliteBook Revolve 810 G2    | [a0f29a4ba9](https://linux-hardware.org/?probe=a0f29a4ba9) | Aug 30, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d045f2314f](https://linux-hardware.org/?probe=d045f2314f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X250 20CLS8MD00    | [cdc5a7009e](https://linux-hardware.org/?probe=cdc5a7009e) | Aug 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a83273e54](https://linux-hardware.org/?probe=2a83273e54) | Aug 16, 2020 |
| HP            | G62                         | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | EliteBook 8540w             | [d89e8704d1](https://linux-hardware.org/?probe=d89e8704d1) | Aug 03, 2020 |
| HP            | G62                         | [1ba7e38fa9](https://linux-hardware.org/?probe=1ba7e38fa9) | Aug 01, 2020 |
| HP            | G62                         | [2c304963c6](https://linux-hardware.org/?probe=2c304963c6) | Jul 31, 2020 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [58887ecbe5](https://linux-hardware.org/?probe=58887ecbe5) | Jul 28, 2020 |
| Notebook      | W230SD                      | [17334fe86e](https://linux-hardware.org/?probe=17334fe86e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [2617c14fa9](https://linux-hardware.org/?probe=2617c14fa9) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [16ae7ff56d](https://linux-hardware.org/?probe=16ae7ff56d) | Jul 23, 2020 |
| Packard Be... | EasyNote_BU45               | [8e4b6e270b](https://linux-hardware.org/?probe=8e4b6e270b) | Jul 21, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| HP            | EliteBook 850 G3            | [6bdfab8f44](https://linux-hardware.org/?probe=6bdfab8f44) | Jul 19, 2020 |
| HP            | Notebook                    | [47c49601e5](https://linux-hardware.org/?probe=47c49601e5) | Jul 17, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| ASUSTek       | GL552VX                     | [b1e86e0658](https://linux-hardware.org/?probe=b1e86e0658) | Jul 13, 2020 |
| HP            | Notebook                    | [0193bf657a](https://linux-hardware.org/?probe=0193bf657a) | Jul 10, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [323451d34a](https://linux-hardware.org/?probe=323451d34a) | Jul 07, 2020 |
| HP            | Notebook                    | [7abd0ca231](https://linux-hardware.org/?probe=7abd0ca231) | Jul 05, 2020 |
| HP            | Notebook                    | [5e580a0f3c](https://linux-hardware.org/?probe=5e580a0f3c) | Jun 28, 2020 |
| Lenovo        | ThinkPad X220 429137G       | [81eaa774db](https://linux-hardware.org/?probe=81eaa774db) | Jun 27, 2020 |
| HP            | EliteBook 840 G2            | [4030e9a77b](https://linux-hardware.org/?probe=4030e9a77b) | Jun 26, 2020 |
| HP            | ProBook 430 G2              | [5a207f8ecb](https://linux-hardware.org/?probe=5a207f8ecb) | Jun 22, 2020 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [ac9b1fcfc1](https://linux-hardware.org/?probe=ac9b1fcfc1) | Jun 19, 2020 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [aae11be071](https://linux-hardware.org/?probe=aae11be071) | Jun 19, 2020 |
| Lenovo        | ThinkPad X220 5114707       | [b7b5a2d3c4](https://linux-hardware.org/?probe=b7b5a2d3c4) | Jun 17, 2020 |
| Acer          | Nitro AN517-51              | [e97d053d44](https://linux-hardware.org/?probe=e97d053d44) | Jun 14, 2020 |
| HP            | Notebook                    | [b8be0bbcb6](https://linux-hardware.org/?probe=b8be0bbcb6) | Jun 11, 2020 |
| HP            | ZBook Studio G3             | [fa56c43e8b](https://linux-hardware.org/?probe=fa56c43e8b) | Jun 08, 2020 |
| ASUSTek       | K53SK                       | [70a8febf11](https://linux-hardware.org/?probe=70a8febf11) | Jun 06, 2020 |
| HP            | ProBook 450 G4              | [0fb21e7f95](https://linux-hardware.org/?probe=0fb21e7f95) | Jun 06, 2020 |
| HP            | ProBook 450 G4              | [59b277ce7e](https://linux-hardware.org/?probe=59b277ce7e) | Jun 06, 2020 |
| HP            | Notebook                    | [f1901b2318](https://linux-hardware.org/?probe=f1901b2318) | Jun 06, 2020 |
| HP            | Notebook                    | [6f1b312f58](https://linux-hardware.org/?probe=6f1b312f58) | Jun 04, 2020 |
| Apple         | MacBookPro12,1              | [a173aacb52](https://linux-hardware.org/?probe=a173aacb52) | Jun 03, 2020 |
| HP            | Notebook                    | [0a8acead1e](https://linux-hardware.org/?probe=0a8acead1e) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| HP            | Notebook                    | [b7a8271246](https://linux-hardware.org/?probe=b7a8271246) | Jun 02, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [272d2636c4](https://linux-hardware.org/?probe=272d2636c4) | Jun 02, 2020 |
| HP            | Notebook                    | [6b852ca6a9](https://linux-hardware.org/?probe=6b852ca6a9) | Jun 02, 2020 |
| Apple         | MacBookPro8,2               | [0916b13ab9](https://linux-hardware.org/?probe=0916b13ab9) | May 30, 2020 |
| HP            | Notebook                    | [7e61dd9af1](https://linux-hardware.org/?probe=7e61dd9af1) | May 29, 2020 |
| Lenovo        | ThinkPad X200 74598Y7       | [4552172a72](https://linux-hardware.org/?probe=4552172a72) | May 28, 2020 |
| HP            | Notebook                    | [7f45b38cd4](https://linux-hardware.org/?probe=7f45b38cd4) | May 28, 2020 |
| HP            | ProBook 6550b               | [be0095e38a](https://linux-hardware.org/?probe=be0095e38a) | May 27, 2020 |
| HP            | Notebook                    | [0cbe35c25f](https://linux-hardware.org/?probe=0cbe35c25f) | May 26, 2020 |
| HP            | ProBook 6560b               | [db77e16126](https://linux-hardware.org/?probe=db77e16126) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Packard Be... | EasyNote TS11HR             | [6983e57f22](https://linux-hardware.org/?probe=6983e57f22) | May 24, 2020 |
| Packard Be... | EasyNote TS11HR             | [119030dda6](https://linux-hardware.org/?probe=119030dda6) | May 24, 2020 |
| Packard Be... | EasyNote TS11HR             | [6191587002](https://linux-hardware.org/?probe=6191587002) | May 24, 2020 |
| HP            | Notebook                    | [cdabffddbf](https://linux-hardware.org/?probe=cdabffddbf) | May 24, 2020 |
| HP            | Notebook                    | [bf45de0480](https://linux-hardware.org/?probe=bf45de0480) | May 22, 2020 |
| HP            | EliteBook 8560p             | [4e386aed8d](https://linux-hardware.org/?probe=4e386aed8d) | May 22, 2020 |
| HP            | EliteBook 8560p             | [97625a0aa5](https://linux-hardware.org/?probe=97625a0aa5) | May 21, 2020 |
| HP            | Notebook                    | [b3fc689390](https://linux-hardware.org/?probe=b3fc689390) | May 20, 2020 |
| HP            | Notebook                    | [37c26e04b4](https://linux-hardware.org/?probe=37c26e04b4) | May 19, 2020 |
| HP            | Notebook                    | [b003dbc951](https://linux-hardware.org/?probe=b003dbc951) | May 18, 2020 |
| HP            | Notebook                    | [c1e6b43323](https://linux-hardware.org/?probe=c1e6b43323) | May 18, 2020 |
| HP            | ZBook 15 G6                 | [4826fc8a4e](https://linux-hardware.org/?probe=4826fc8a4e) | May 15, 2020 |
| HP            | Notebook                    | [07cb54da5e](https://linux-hardware.org/?probe=07cb54da5e) | May 15, 2020 |
| HP            | Notebook                    | [ca4b050d87](https://linux-hardware.org/?probe=ca4b050d87) | May 12, 2020 |
| HP            | Notebook                    | [e38e8614b8](https://linux-hardware.org/?probe=e38e8614b8) | May 11, 2020 |
| Lenovo        | ThinkPad X220 42915CG       | [57fd312a24](https://linux-hardware.org/?probe=57fd312a24) | May 10, 2020 |
| Lenovo        | ThinkPad X220 42915CG       | [2f5ff0ecb0](https://linux-hardware.org/?probe=2f5ff0ecb0) | May 10, 2020 |
| Dell          | Latitude E5450              | [1267f8327e](https://linux-hardware.org/?probe=1267f8327e) | May 05, 2020 |
| Dell          | Latitude E5450              | [869437538e](https://linux-hardware.org/?probe=869437538e) | May 05, 2020 |
| Dell          | Precision M4600             | [f08cd698ff](https://linux-hardware.org/?probe=f08cd698ff) | May 05, 2020 |
| Dell          | Latitude E6330              | [e4ed5b9a57](https://linux-hardware.org/?probe=e4ed5b9a57) | May 05, 2020 |
| HP            | ProBook 6360b               | [877e10ccd2](https://linux-hardware.org/?probe=877e10ccd2) | May 03, 2020 |
| HP            | Presario V6500              | [f4363eb821](https://linux-hardware.org/?probe=f4363eb821) | May 03, 2020 |
| HP            | Notebook                    | [f7d85f991f](https://linux-hardware.org/?probe=f7d85f991f) | May 03, 2020 |
| HP            | Notebook                    | [d026953629](https://linux-hardware.org/?probe=d026953629) | May 02, 2020 |
| HP            | Notebook                    | [ad98977da0](https://linux-hardware.org/?probe=ad98977da0) | May 01, 2020 |
| Packard Be... | EasyNote MB65               | [afdaaf53ba](https://linux-hardware.org/?probe=afdaaf53ba) | Apr 30, 2020 |
| HP            | Notebook                    | [55442425a3](https://linux-hardware.org/?probe=55442425a3) | Apr 30, 2020 |
| Packard Be... | EasyNote MB65               | [77835fdd2a](https://linux-hardware.org/?probe=77835fdd2a) | Apr 30, 2020 |
| HP            | Notebook                    | [6b8cdc24af](https://linux-hardware.org/?probe=6b8cdc24af) | Apr 30, 2020 |
| Packard Be... | EasyNote MB65               | [18bc60d2a7](https://linux-hardware.org/?probe=18bc60d2a7) | Apr 30, 2020 |
| Dell          | Precision 5540              | [6cf02adf6c](https://linux-hardware.org/?probe=6cf02adf6c) | Apr 29, 2020 |
| HP            | Notebook                    | [edd7cc080c](https://linux-hardware.org/?probe=edd7cc080c) | Apr 29, 2020 |
| HP            | OMEN by HP Laptop           | [afa4e06e15](https://linux-hardware.org/?probe=afa4e06e15) | Apr 27, 2020 |
| Dell          | Precision 5540              | [520210c4e8](https://linux-hardware.org/?probe=520210c4e8) | Apr 26, 2020 |
| Dell          | Precision 5540              | [0c96c9ee27](https://linux-hardware.org/?probe=0c96c9ee27) | Apr 26, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [48c077167c](https://linux-hardware.org/?probe=48c077167c) | Apr 24, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2f07d3f214](https://linux-hardware.org/?probe=2f07d3f214) | Apr 23, 2020 |
| Lenovo        | ThinkPad T430s 2356GCG      | [9204f9b549](https://linux-hardware.org/?probe=9204f9b549) | Apr 21, 2020 |
| Lenovo        | ThinkPad T430s 2356GCG      | [8adfba26f0](https://linux-hardware.org/?probe=8adfba26f0) | Apr 21, 2020 |
| HP            | EliteBook 840 G6            | [b177ca5c0c](https://linux-hardware.org/?probe=b177ca5c0c) | Apr 19, 2020 |
| HP            | EliteBook 840 G6            | [ace8e5ae82](https://linux-hardware.org/?probe=ace8e5ae82) | Apr 19, 2020 |
| HP            | EliteBook 840 G6            | [91f5cf26b2](https://linux-hardware.org/?probe=91f5cf26b2) | Apr 19, 2020 |
| HP            | EliteBook 840 G6            | [d0dd5b9cfe](https://linux-hardware.org/?probe=d0dd5b9cfe) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [4cf3de7438](https://linux-hardware.org/?probe=4cf3de7438) | Apr 19, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| Lenovo        | IdeaPad S510p 20298         | [41e6690bfd](https://linux-hardware.org/?probe=41e6690bfd) | Apr 17, 2020 |
| ASUSTek       | K53E                        | [006182b224](https://linux-hardware.org/?probe=006182b224) | Apr 17, 2020 |
| ASUSTek       | K53E                        | [629684fd27](https://linux-hardware.org/?probe=629684fd27) | Apr 17, 2020 |
| ASUSTek       | K53E                        | [07c8dde574](https://linux-hardware.org/?probe=07c8dde574) | Apr 17, 2020 |
| Apple         | MacBookPro12,1              | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| Acer          | Aspire ES1-520              | [1ebbc3ef40](https://linux-hardware.org/?probe=1ebbc3ef40) | Apr 13, 2020 |
| Acer          | Aspire ES1-520              | [27ba93c17e](https://linux-hardware.org/?probe=27ba93c17e) | Apr 13, 2020 |
| HP            | EliteBook 8470p             | [8607854607](https://linux-hardware.org/?probe=8607854607) | Apr 13, 2020 |
| HP            | EliteBook 8470p             | [4ea04e46a0](https://linux-hardware.org/?probe=4ea04e46a0) | Apr 13, 2020 |
| HP            | EliteBook 840 G5            | [b0d990b779](https://linux-hardware.org/?probe=b0d990b779) | Apr 12, 2020 |
| Lenovo        | Flex 3-1480                 | [4327baf273](https://linux-hardware.org/?probe=4327baf273) | Apr 11, 2020 |
| HP            | G62                         | [65f362927c](https://linux-hardware.org/?probe=65f362927c) | Apr 04, 2020 |
| HP            | G62                         | [7c0c376cdf](https://linux-hardware.org/?probe=7c0c376cdf) | Apr 04, 2020 |
| HP            | Compaq 8710w (GC125EA#AB... | [a06e142488](https://linux-hardware.org/?probe=a06e142488) | Mar 28, 2020 |
| Lenovo        | ThinkPad T450 20BV003SMN    | [15d72b17e9](https://linux-hardware.org/?probe=15d72b17e9) | Mar 27, 2020 |
| Dell          | Inspiron 910                | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| Dell          | Inspiron 910                | [6441625d8b](https://linux-hardware.org/?probe=6441625d8b) | Mar 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c8544c05c8](https://linux-hardware.org/?probe=c8544c05c8) | Mar 23, 2020 |
| Dell          | Inspiron 910                | [50081ceef7](https://linux-hardware.org/?probe=50081ceef7) | Mar 22, 2020 |
| HP            | G62                         | [10f3f45b4c](https://linux-hardware.org/?probe=10f3f45b4c) | Mar 21, 2020 |
| HP            | G62                         | [6f4776017d](https://linux-hardware.org/?probe=6f4776017d) | Mar 21, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| Dell          | Inspiron 910                | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Lenovo        | ThinkPad W500 40613EG       | [07fbc1a98c](https://linux-hardware.org/?probe=07fbc1a98c) | Mar 16, 2020 |
| Lenovo        | ThinkPad T560 20FH0036MN    | [443d40d6e8](https://linux-hardware.org/?probe=443d40d6e8) | Mar 15, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9e6de9df80](https://linux-hardware.org/?probe=9e6de9df80) | Mar 15, 2020 |
| HP            | ProBook 6360b               | [a8c5eab6cb](https://linux-hardware.org/?probe=a8c5eab6cb) | Mar 14, 2020 |
| Acer          | Aspire E1-572G              | [cc8b5532c5](https://linux-hardware.org/?probe=cc8b5532c5) | Mar 12, 2020 |
| Dell          | Inspiron 910                | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| HP            | ProBook 6360b               | [b3c23a39d0](https://linux-hardware.org/?probe=b3c23a39d0) | Mar 06, 2020 |
| HP            | ProBook 6360b               | [d6a416981a](https://linux-hardware.org/?probe=d6a416981a) | Mar 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7d5b5cbba](https://linux-hardware.org/?probe=a7d5b5cbba) | Mar 05, 2020 |
| HP            | ProBook 6360b               | [0a33c7ca36](https://linux-hardware.org/?probe=0a33c7ca36) | Mar 05, 2020 |
| Acer          | Aspire 5552                 | [b10fce36b2](https://linux-hardware.org/?probe=b10fce36b2) | Feb 28, 2020 |
| Acer          | Aspire A517-51              | [2e94416a6c](https://linux-hardware.org/?probe=2e94416a6c) | Feb 28, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [41b2c57c35](https://linux-hardware.org/?probe=41b2c57c35) | Feb 26, 2020 |
| Lenovo        | B575e 36852EG               | [af105c3035](https://linux-hardware.org/?probe=af105c3035) | Feb 23, 2020 |
| HP            | EliteBook 2570p             | [ee7aa6d846](https://linux-hardware.org/?probe=ee7aa6d846) | Feb 23, 2020 |
| HP            | EliteBook 2570p             | [910fb6d461](https://linux-hardware.org/?probe=910fb6d461) | Feb 23, 2020 |
| Samsung       | N150/N210/N220              | [ee94964d7c](https://linux-hardware.org/?probe=ee94964d7c) | Feb 23, 2020 |
| HP            | Pavilion dv8                | [58ccc99c12](https://linux-hardware.org/?probe=58ccc99c12) | Feb 22, 2020 |
| Notebook      | N8xEJEK                     | [8fc5a6eb72](https://linux-hardware.org/?probe=8fc5a6eb72) | Feb 22, 2020 |
| Dell          | Inspiron 1545               | [174a4904a7](https://linux-hardware.org/?probe=174a4904a7) | Feb 18, 2020 |
| HP            | ProBook 440 G5              | [eee6e3a9af](https://linux-hardware.org/?probe=eee6e3a9af) | Feb 16, 2020 |
| Dell          | Precision 5530              | [354c8ce45c](https://linux-hardware.org/?probe=354c8ce45c) | Feb 10, 2020 |
| MSI           | GL62M 7REX                  | [c80fad9158](https://linux-hardware.org/?probe=c80fad9158) | Feb 09, 2020 |
| MSI           | GL62M 7REX                  | [4c531bb627](https://linux-hardware.org/?probe=4c531bb627) | Feb 09, 2020 |
| MSI           | GL62M 7REX                  | [a40633b816](https://linux-hardware.org/?probe=a40633b816) | Feb 09, 2020 |
| Dell          | Precision 5530              | [520e69cfef](https://linux-hardware.org/?probe=520e69cfef) | Feb 03, 2020 |
| Toshiba       | NB520                       | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | [20c5cb5e37](https://linux-hardware.org/?probe=20c5cb5e37) | Feb 02, 2020 |
| Toshiba       | NB520                       | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Dell          | Precision 5530              | [b28c9b7db5](https://linux-hardware.org/?probe=b28c9b7db5) | Feb 01, 2020 |
| Dell          | Precision 5530              | [767587099c](https://linux-hardware.org/?probe=767587099c) | Feb 01, 2020 |
| Lenovo        | ThinkPad X230 2325WBG       | [bd6ea83361](https://linux-hardware.org/?probe=bd6ea83361) | Jan 25, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [02e3ab48e4](https://linux-hardware.org/?probe=02e3ab48e4) | Jan 20, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [a343aeccf1](https://linux-hardware.org/?probe=a343aeccf1) | Jan 15, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [d1ef555bfb](https://linux-hardware.org/?probe=d1ef555bfb) | Jan 15, 2020 |
| Lenovo        | Z50-70 20354                | [37002c2466](https://linux-hardware.org/?probe=37002c2466) | Jan 12, 2020 |
| HUAWEI        | WRT-WX9                     | [30f6145d8c](https://linux-hardware.org/?probe=30f6145d8c) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [c0a2dbc240](https://linux-hardware.org/?probe=c0a2dbc240) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [e809c2c313](https://linux-hardware.org/?probe=e809c2c313) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [b639ae9260](https://linux-hardware.org/?probe=b639ae9260) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [2d2afb9984](https://linux-hardware.org/?probe=2d2afb9984) | Jan 08, 2020 |
| HP            | Pavilion Notebook           | [3aa5a0e012](https://linux-hardware.org/?probe=3aa5a0e012) | Dec 31, 2019 |
| HP            | ENVY Laptop 13-ad1xx        | [e44d4d3221](https://linux-hardware.org/?probe=e44d4d3221) | Dec 21, 2019 |
| Packard Be... | EasyNote TE11HC             | [7857e6a77b](https://linux-hardware.org/?probe=7857e6a77b) | Dec 18, 2019 |
| HP            | Compaq 8710w (GC125EA#AB... | [d201d96afe](https://linux-hardware.org/?probe=d201d96afe) | Dec 12, 2019 |
| ASUSTek       | TP500LA                     | [5e1d50070f](https://linux-hardware.org/?probe=5e1d50070f) | Nov 25, 2019 |
| HP            | EliteBook 840 G6            | [a64d688094](https://linux-hardware.org/?probe=a64d688094) | Nov 23, 2019 |
| Lenovo        | ThinkPad T480 20L60033MX    | [6bc4be7b85](https://linux-hardware.org/?probe=6bc4be7b85) | Nov 23, 2019 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ce78a45975](https://linux-hardware.org/?probe=ce78a45975) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [3200b20576](https://linux-hardware.org/?probe=3200b20576) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [65529afb99](https://linux-hardware.org/?probe=65529afb99) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [b7089462b3](https://linux-hardware.org/?probe=b7089462b3) | Nov 16, 2019 |
| Apple         | MacBookPro6,1               | [4f5f07bc6e](https://linux-hardware.org/?probe=4f5f07bc6e) | Nov 10, 2019 |
| Apple         | MacBookPro6,1               | [604898fc11](https://linux-hardware.org/?probe=604898fc11) | Nov 09, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [71a554266d](https://linux-hardware.org/?probe=71a554266d) | Nov 08, 2019 |
| HP            | Pavilion dv6                | [bf5a8c1756](https://linux-hardware.org/?probe=bf5a8c1756) | Nov 01, 2019 |
| HP            | Pavilion dv6                | [5d194be097](https://linux-hardware.org/?probe=5d194be097) | Nov 01, 2019 |
| Apple         | MacBookPro6,1               | [2029685373](https://linux-hardware.org/?probe=2029685373) | Oct 19, 2019 |
| Dell          | Latitude D531               | [e5d515dd75](https://linux-hardware.org/?probe=e5d515dd75) | Oct 19, 2019 |
| Acer          | Aspire xxxx                 | [d4d6a3752e](https://linux-hardware.org/?probe=d4d6a3752e) | Oct 18, 2019 |
| Toshiba       | Unknown                     | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aced6cd1bd](https://linux-hardware.org/?probe=aced6cd1bd) | Oct 17, 2019 |
| Acer          | Aspire V3-574G              | [632726f3fc](https://linux-hardware.org/?probe=632726f3fc) | Oct 16, 2019 |
| Acer          | Aspire V3-574G              | [933dfaebec](https://linux-hardware.org/?probe=933dfaebec) | Oct 16, 2019 |
| HUAWEI        | MACH-WX9                    | [aaa6c2a79e](https://linux-hardware.org/?probe=aaa6c2a79e) | Oct 10, 2019 |
| HP            | ProBook 6550b               | [f359c727c3](https://linux-hardware.org/?probe=f359c727c3) | Oct 07, 2019 |
| HP            | ProBook 430 G2              | [845cc60615](https://linux-hardware.org/?probe=845cc60615) | Oct 02, 2019 |
| Acer          | Aspire xxxx                 | [d0a2f6ba0e](https://linux-hardware.org/?probe=d0a2f6ba0e) | Sep 08, 2019 |
| Acer          | Aspire xxxx                 | [d3ce6b0db9](https://linux-hardware.org/?probe=d3ce6b0db9) | Sep 08, 2019 |
| Acer          | Aspire xxxx                 | [ac165ecd91](https://linux-hardware.org/?probe=ac165ecd91) | Sep 06, 2019 |
| Lenovo        | ThinkPad T530 2392APU       | [1236a173c5](https://linux-hardware.org/?probe=1236a173c5) | Sep 02, 2019 |
| Lenovo        | ThinkPad T430 23472M1       | [0327550660](https://linux-hardware.org/?probe=0327550660) | Sep 01, 2019 |
| Acer          | Aspire xxxx                 | [41c261aedb](https://linux-hardware.org/?probe=41c261aedb) | Aug 17, 2019 |
| HP            | OMEN by HP Laptop           | [60a6a7a4f4](https://linux-hardware.org/?probe=60a6a7a4f4) | Aug 13, 2019 |
| Acer          | Aspire xxxx                 | [99d73ebf91](https://linux-hardware.org/?probe=99d73ebf91) | Aug 09, 2019 |
| HUAWEI        | MACH-WX9                    | [5f7a70586e](https://linux-hardware.org/?probe=5f7a70586e) | Jul 27, 2019 |
| Acer          | Aspire xxxx                 | [e01cce8165](https://linux-hardware.org/?probe=e01cce8165) | Jul 26, 2019 |
| Lenovo        | ThinkPad T420 4180EA3       | [fbf8462f41](https://linux-hardware.org/?probe=fbf8462f41) | Jul 22, 2019 |
| Lenovo        | G550 20023                  | [370dcd58cc](https://linux-hardware.org/?probe=370dcd58cc) | Jul 22, 2019 |
| Acer          | Aspire A515-52G             | [517cad6069](https://linux-hardware.org/?probe=517cad6069) | Jul 18, 2019 |
| HP            | ProBook 430 G2              | [3e165ac0a4](https://linux-hardware.org/?probe=3e165ac0a4) | Jul 17, 2019 |
| HP            | Laptop 14-bp0xx             | [6fdcfe86c2](https://linux-hardware.org/?probe=6fdcfe86c2) | Jul 14, 2019 |
| Acer          | Aspire xxxx                 | [a67af78289](https://linux-hardware.org/?probe=a67af78289) | Jul 13, 2019 |
| Acer          | Aspire xxxx                 | [7bc2ed3297](https://linux-hardware.org/?probe=7bc2ed3297) | Jul 11, 2019 |
| HP            | ProBook 430 G2              | [c935897214](https://linux-hardware.org/?probe=c935897214) | Jul 10, 2019 |
| Lenovo        | ThinkPad T420s 4174PEG      | [270133c428](https://linux-hardware.org/?probe=270133c428) | Jul 07, 2019 |
| HP            | ProBook 430 G2              | [45ad728ed9](https://linux-hardware.org/?probe=45ad728ed9) | Jul 03, 2019 |
| HP            | ProBook 430 G2              | [7ca78fa791](https://linux-hardware.org/?probe=7ca78fa791) | Jul 02, 2019 |
| HP            | ProBook 430 G2              | [909a60cd55](https://linux-hardware.org/?probe=909a60cd55) | Jul 02, 2019 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3c2262b65c](https://linux-hardware.org/?probe=3c2262b65c) | Jun 19, 2019 |
| Lenovo        | ThinkPad T420s 4174PEG      | [eedc970aa6](https://linux-hardware.org/?probe=eedc970aa6) | Jun 17, 2019 |
| HP            | EliteBook 8470p             | [707703a569](https://linux-hardware.org/?probe=707703a569) | Jun 09, 2019 |
| Dell          | Precision 7520              | [edeb5aff4c](https://linux-hardware.org/?probe=edeb5aff4c) | Jun 08, 2019 |
| ASUSTek       | K53TK                       | [6a47875df8](https://linux-hardware.org/?probe=6a47875df8) | Jun 08, 2019 |
| Dell          | Latitude E6510              | [a9143beecd](https://linux-hardware.org/?probe=a9143beecd) | Jun 05, 2019 |
| Dell          | G3 3579                     | [59eaf9f30e](https://linux-hardware.org/?probe=59eaf9f30e) | May 17, 2019 |
| Dell          | G3 3579                     | [47fb6be810](https://linux-hardware.org/?probe=47fb6be810) | May 17, 2019 |
| Acer          | Swift SF315-51              | [1bb011abd5](https://linux-hardware.org/?probe=1bb011abd5) | May 12, 2019 |
| Acer          | Nitro AN515-52              | [4b221958a2](https://linux-hardware.org/?probe=4b221958a2) | Apr 28, 2019 |
| Lenovo        | ThinkPad X201 3626GWG       | [18496881cc](https://linux-hardware.org/?probe=18496881cc) | Apr 23, 2019 |
| Samsung       | R19/R20/R21                 | [5d5c459e44](https://linux-hardware.org/?probe=5d5c459e44) | Apr 19, 2019 |
| Dell          | Inspiron MP061              | [d671256209](https://linux-hardware.org/?probe=d671256209) | Apr 18, 2019 |
| Dell          | Inspiron MP061              | [0fd2ab6ca2](https://linux-hardware.org/?probe=0fd2ab6ca2) | Apr 18, 2019 |
| HUAWEI        | MACH-WX9                    | [9c7220422a](https://linux-hardware.org/?probe=9c7220422a) | Apr 07, 2019 |
| ASUSTek       | Zephyrus M GM501GM          | [db4f84abe8](https://linux-hardware.org/?probe=db4f84abe8) | Mar 28, 2019 |
| ASUSTek       | K56CA                       | [8b6978a8bf](https://linux-hardware.org/?probe=8b6978a8bf) | Mar 24, 2019 |
| ASUSTek       | K56CA                       | [0aa8c51eca](https://linux-hardware.org/?probe=0aa8c51eca) | Mar 20, 2019 |
| Lenovo        | ThinkPad T450s 20BX000VM... | [f15c77aa62](https://linux-hardware.org/?probe=f15c77aa62) | Mar 20, 2019 |
| Dell          | Precision 5530              | [0590fe5aab](https://linux-hardware.org/?probe=0590fe5aab) | Mar 01, 2019 |
| HUAWEI        | MACH-WX9                    | [910d0e78a5](https://linux-hardware.org/?probe=910d0e78a5) | Jan 14, 2019 |
| HP            | EliteBook 8560p             | [c94827d5d2](https://linux-hardware.org/?probe=c94827d5d2) | Jan 07, 2019 |
| ASUSTek       | N53SV                       | [ba26650150](https://linux-hardware.org/?probe=ba26650150) | Dec 10, 2018 |
| HP            | EliteBook 850 G2            | [9bc872a1df](https://linux-hardware.org/?probe=9bc872a1df) | Nov 16, 2018 |
| HP            | ProBook 4340s               | [f37c4eb7b0](https://linux-hardware.org/?probe=f37c4eb7b0) | Nov 06, 2018 |
| HP            | ProBook 4340s               | [f8a6517e9f](https://linux-hardware.org/?probe=f8a6517e9f) | Nov 06, 2018 |
| Lenovo        | ThinkPad X220 42914CG       | [218f1cab0a](https://linux-hardware.org/?probe=218f1cab0a) | Oct 21, 2018 |
| Unknown       | Unknown                     | [59c80c3cb7](https://linux-hardware.org/?probe=59c80c3cb7) | Oct 17, 2018 |
| Unknown       | Unknown                     | [ced1bff049](https://linux-hardware.org/?probe=ced1bff049) | Oct 17, 2018 |
| Apple         | MacBook6,1                  | [546260009b](https://linux-hardware.org/?probe=546260009b) | Aug 14, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 75        | 18.07%  |
| Ubuntu 18.04                 | 34        | 8.19%   |
| OpenMandriva 4.2             | 11        | 2.65%   |
| Fedora 35                    | 11        | 2.65%   |
| Fedora 31                    | 11        | 2.65%   |
| Debian 11                    | 10        | 2.41%   |
| Ubuntu 20.10                 | 9         | 2.17%   |
| Pop!_OS 21.10                | 9         | 2.17%   |
| KDE neon 20.04               | 9         | 2.17%   |
| Fedora 34                    | 9         | 2.17%   |
| Ubuntu 19.04                 | 8         | 1.93%   |
| Pop!_OS 21.04                | 8         | 1.93%   |
| Pop!_OS 20.10                | 8         | 1.93%   |
| Linux Mint 20.2              | 8         | 1.93%   |
| Arch Rolling                 | 8         | 1.93%   |
| Xubuntu 20.04                | 7         | 1.69%   |
| ArcoLinux Rolling            | 7         | 1.69%   |
| Zorin 16                     | 6         | 1.45%   |
| Ubuntu 19.10                 | 6         | 1.45%   |
| Pop!_OS 20.04                | 6         | 1.45%   |
| Manjaro                      | 6         | 1.45%   |
| Linux Mint 20.1              | 5         | 1.2%    |
| Linux Mint 19.3              | 5         | 1.2%    |
| Debian 10                    | 5         | 1.2%    |
| Arch                         | 5         | 1.2%    |
| Zorin 15                     | 4         | 0.96%   |
| Ubuntu 21.10                 | 4         | 0.96%   |
| Manjaro 20.2.1               | 4         | 0.96%   |
| Linux Mint 20.3              | 4         | 0.96%   |
| Linux Mint 19.1              | 4         | 0.96%   |
| Fedora 33                    | 4         | 0.96%   |
| Xubuntu 18.04                | 3         | 0.72%   |
| Ubuntu MATE 20.04            | 3         | 0.72%   |
| Ubuntu 18.10                 | 3         | 0.72%   |
| OpenMandriva 4.3             | 3         | 0.72%   |
| KDE neon 18.04               | 3         | 0.72%   |
| Fedora 36                    | 3         | 0.72%   |
| EndeavourOS Rolling          | 3         | 0.72%   |
| Ubuntu Budgie 20.04          | 2         | 0.48%   |
| Ubuntu 21.04                 | 2         | 0.48%   |
| ROSA R10                     | 2         | 0.48%   |
| openSUSE Tumbleweed-20200128 | 2         | 0.48%   |
| OpenMandriva 4.50            | 2         | 0.48%   |
| Manjaro 21.0.5               | 2         | 0.48%   |
| Manjaro 18.1.5               | 2         | 0.48%   |
| Linux Mint 20                | 2         | 0.48%   |
| Kubuntu 20.04                | 2         | 0.48%   |
| Gentoo 2.7                   | 2         | 0.48%   |
| Gentoo 2.6                   | 2         | 0.48%   |
| Fedora 32                    | 2         | 0.48%   |
| Fedora 30                    | 2         | 0.48%   |
| Fedora 29                    | 2         | 0.48%   |
| Elementary 6.1               | 2         | 0.48%   |
| Debian Testing               | 2         | 0.48%   |
| CentOS 8                     | 2         | 0.48%   |
| Zorin 12                     | 1         | 0.24%   |
| Xubuntu 19.10                | 1         | 0.24%   |
| Xero Rolling                 | 1         | 0.24%   |
| Void Linux                   | 1         | 0.24%   |
| Ubuntu MATE 18.04            | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 141       | 35.34%  |
| Fedora        | 40        | 10.03%  |
| Pop!_OS       | 31        | 7.77%   |
| Linux Mint    | 27        | 6.77%   |
| Manjaro       | 22        | 5.51%   |
| Debian        | 19        | 4.76%   |
| OpenMandriva  | 16        | 4.01%   |
| Arch          | 13        | 3.26%   |
| Zorin         | 11        | 2.76%   |
| Xubuntu       | 11        | 2.76%   |
| KDE neon      | 11        | 2.76%   |
| openSUSE      | 7         | 1.75%   |
| ArcoLinux     | 7         | 1.75%   |
| Ubuntu MATE   | 4         | 1%      |
| Gentoo        | 4         | 1%      |
| Elementary    | 4         | 1%      |
| Ubuntu Budgie | 3         | 0.75%   |
| ROSA          | 3         | 0.75%   |
| Kubuntu       | 3         | 0.75%   |
| Kali          | 3         | 0.75%   |
| EndeavourOS   | 3         | 0.75%   |
| Clear Linux   | 3         | 0.75%   |
| Lubuntu       | 2         | 0.5%    |
| CentOS        | 2         | 0.5%    |
| Xero          | 1         | 0.25%   |
| Void Linux    | 1         | 0.25%   |
| Solus         | 1         | 0.25%   |
| Peppermint    | 1         | 0.25%   |
| MX            | 1         | 0.25%   |
| Devuan        | 1         | 0.25%   |
| Cleanjaro     | 1         | 0.25%   |
| Chrome OS     | 1         | 0.25%   |
| antergos      | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 2.21%   |
| 5.4.0-42-generic         | 9         | 1.99%   |
| 5.3.0-46-generic         | 7         | 1.55%   |
| 5.4.0-58-generic         | 6         | 1.32%   |
| 5.4.0-48-generic         | 6         | 1.32%   |
| 5.11.0-40-generic        | 6         | 1.32%   |
| 5.8.0-44-generic         | 5         | 1.1%    |
| 5.4.0-91-generic         | 5         | 1.1%    |
| 5.4.0-74-generic         | 5         | 1.1%    |
| 5.4.0-33-generic         | 5         | 1.1%    |
| 5.4.0-26-generic         | 5         | 1.1%    |
| 5.8.0-7630-generic       | 4         | 0.88%   |
| 5.8.0-43-generic         | 4         | 0.88%   |
| 5.4.0-45-generic         | 4         | 0.88%   |
| 5.4.0-28-generic         | 4         | 0.88%   |
| 5.3.0-40-generic         | 4         | 0.88%   |
| 5.16.11-76051611-generic | 4         | 0.88%   |
| 5.13.0-7620-generic      | 4         | 0.88%   |
| 5.13.0-39-generic        | 4         | 0.88%   |
| 5.13.0-28-generic        | 4         | 0.88%   |
| 5.11.0-7620-generic      | 4         | 0.88%   |
| 5.10.0-8-amd64           | 4         | 0.88%   |
| 5.0.0-31-generic         | 4         | 0.88%   |
| 5.8.0-7642-generic       | 3         | 0.66%   |
| 5.8.0-50-generic         | 3         | 0.66%   |
| 5.8.0-48-generic         | 3         | 0.66%   |
| 5.4.0-81-generic         | 3         | 0.66%   |
| 5.4.0-56-generic         | 3         | 0.66%   |
| 5.4.0-53-generic         | 3         | 0.66%   |
| 5.4.0-40-generic         | 3         | 0.66%   |
| 5.4.0-31-generic         | 3         | 0.66%   |
| 5.4.0-29-generic         | 3         | 0.66%   |
| 5.4.0-107-generic        | 3         | 0.66%   |
| 5.3.0-42-generic         | 3         | 0.66%   |
| 5.3.0-28-generic         | 3         | 0.66%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.66%   |
| 5.16.15-76051615-generic | 3         | 0.66%   |
| 5.14.16-301.fc35.x86_64  | 3         | 0.66%   |
| 5.11.0-7614-generic      | 3         | 0.66%   |
| 5.11.0-36-generic        | 3         | 0.66%   |
| 5.11.0-27-generic        | 3         | 0.66%   |
| 5.10.7-3-MANJARO         | 3         | 0.66%   |
| 5.0.0-23-generic         | 3         | 0.66%   |
| 4.18.0-25-generic        | 3         | 0.66%   |
| 4.18.0-16-generic        | 3         | 0.66%   |
| 5.9.16-1-MANJARO         | 2         | 0.44%   |
| 5.9.0-1-amd64            | 2         | 0.44%   |
| 5.8.0-59-generic         | 2         | 0.44%   |
| 5.8.0-33-generic         | 2         | 0.44%   |
| 5.5.5-200.fc31.x86_64    | 2         | 0.44%   |
| 5.4.8-200.fc31.x86_64    | 2         | 0.44%   |
| 5.4.6-2-MANJARO          | 2         | 0.44%   |
| 5.4.14-1-default         | 2         | 0.44%   |
| 5.4.0-96-generic         | 2         | 0.44%   |
| 5.4.0-89-generic         | 2         | 0.44%   |
| 5.4.0-73-generic         | 2         | 0.44%   |
| 5.4.0-70-generic         | 2         | 0.44%   |
| 5.4.0-66-generic         | 2         | 0.44%   |
| 5.4.0-52-generic         | 2         | 0.44%   |
| 5.4.0-48-lowlatency      | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 93        | 21.73%  |
| 5.8.0   | 32        | 7.48%   |
| 5.11.0  | 28        | 6.54%   |
| 4.15.0  | 25        | 5.84%   |
| 5.3.0   | 23        | 5.37%   |
| 5.13.0  | 20        | 4.67%   |
| 5.0.0   | 15        | 3.5%    |
| 5.10.0  | 12        | 2.8%    |
| 4.18.0  | 12        | 2.8%    |
| 5.10.14 | 10        | 2.34%   |
| 5.16.11 | 6         | 1.4%    |
| 4.19.0  | 4         | 0.93%   |
| 5.9.0   | 3         | 0.7%    |
| 5.5.5   | 3         | 0.7%    |
| 5.4.14  | 3         | 0.7%    |
| 5.16.7  | 3         | 0.7%    |
| 5.16.15 | 3         | 0.7%    |
| 5.16.10 | 3         | 0.7%    |
| 5.15.5  | 3         | 0.7%    |
| 5.15.12 | 3         | 0.7%    |
| 5.14.16 | 3         | 0.7%    |
| 5.13.19 | 3         | 0.7%    |
| 5.12.4  | 3         | 0.7%    |
| 5.10.7  | 3         | 0.7%    |
| 5.9.8   | 2         | 0.47%   |
| 5.9.16  | 2         | 0.47%   |
| 5.4.8   | 2         | 0.47%   |
| 5.4.6   | 2         | 0.47%   |
| 5.3.7   | 2         | 0.47%   |
| 5.3.11  | 2         | 0.47%   |
| 5.17.1  | 2         | 0.47%   |
| 5.17.0  | 2         | 0.47%   |
| 5.15.8  | 2         | 0.47%   |
| 5.15.11 | 2         | 0.47%   |
| 5.15.10 | 2         | 0.47%   |
| 5.14.14 | 2         | 0.47%   |
| 5.13.8  | 2         | 0.47%   |
| 5.13.15 | 2         | 0.47%   |
| 5.13.14 | 2         | 0.47%   |
| 5.13.12 | 2         | 0.47%   |
| 5.12.9  | 2         | 0.47%   |
| 5.11.12 | 2         | 0.47%   |
| 5.9.6   | 1         | 0.23%   |
| 5.9.2   | 1         | 0.23%   |
| 5.9.14  | 1         | 0.23%   |
| 5.9.11  | 1         | 0.23%   |
| 5.8.9   | 1         | 0.23%   |
| 5.8.3   | 1         | 0.23%   |
| 5.8.16  | 1         | 0.23%   |
| 5.8.12  | 1         | 0.23%   |
| 5.8.10  | 1         | 0.23%   |
| 5.8.1   | 1         | 0.23%   |
| 5.7.8   | 1         | 0.23%   |
| 5.7.14  | 1         | 0.23%   |
| 5.7.0   | 1         | 0.23%   |
| 5.6.4   | 1         | 0.23%   |
| 5.6.3   | 1         | 0.23%   |
| 5.5.8   | 1         | 0.23%   |
| 5.5.6   | 1         | 0.23%   |
| 5.4.66  | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 105       | 25%     |
| 5.8     | 38        | 9.05%   |
| 5.13    | 34        | 8.1%    |
| 5.11    | 34        | 8.1%    |
| 5.3     | 31        | 7.38%   |
| 5.10    | 30        | 7.14%   |
| 4.15    | 25        | 5.95%   |
| 5.16    | 20        | 4.76%   |
| 5.15    | 15        | 3.57%   |
| 5.0     | 15        | 3.57%   |
| 4.18    | 15        | 3.57%   |
| 5.9     | 11        | 2.62%   |
| 5.14    | 10        | 2.38%   |
| 5.12    | 7         | 1.67%   |
| 4.19    | 6         | 1.43%   |
| 5.5     | 5         | 1.19%   |
| 5.17    | 5         | 1.19%   |
| 5.7     | 3         | 0.71%   |
| 4.9     | 3         | 0.71%   |
| 5.6     | 2         | 0.48%   |
| 5.2     | 2         | 0.48%   |
| 5.1     | 2         | 0.48%   |
| 5.18    | 1         | 0.24%   |
| 4.4     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 376       | 96.66%  |
| i686   | 12        | 3.08%   |
| armv7l | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 195       | 48.39%  |
| Unknown           | 56        | 13.9%   |
| KDE5              | 49        | 12.16%  |
| XFCE              | 37        | 9.18%   |
| X-Cinnamon        | 15        | 3.72%   |
| KDE               | 12        | 2.98%   |
| MATE              | 8         | 1.99%   |
| Cinnamon          | 6         | 1.49%   |
| GNOME Flashback   | 4         | 0.99%   |
| Unity             | 3         | 0.74%   |
| Pantheon          | 3         | 0.74%   |
| Budgie            | 3         | 0.74%   |
| LXQt              | 2         | 0.5%    |
| LXDE              | 2         | 0.5%    |
| KDE4              | 2         | 0.5%    |
| i3                | 2         | 0.5%    |
| Yaru:ubuntu:GNOME | 1         | 0.25%   |
| xinit-compat      | 1         | 0.25%   |
| Deepin            | 1         | 0.25%   |
| bspwm             | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 313       | 78.25%  |
| Wayland | 52        | 13%     |
| Unknown | 31        | 7.75%   |
| Tty     | 4         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 206       | 51.63%  |
| GDM     | 71        | 17.79%  |
| SDDM    | 46        | 11.53%  |
| LightDM | 37        | 9.27%   |
| GDM3    | 18        | 4.51%   |
| TDM     | 16        | 4.01%   |
| KDM     | 3         | 0.75%   |
| XDM     | 2         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 205       | 51.38%  |
| nb_NO       | 94        | 23.56%  |
| Unknown     | 55        | 13.78%  |
| en_GB       | 16        | 4.01%   |
| C           | 7         | 1.75%   |
| nn_NO       | 5         | 1.25%   |
| pl_PL       | 3         | 0.75%   |
| en_DK       | 3         | 0.75%   |
| de_DE       | 3         | 0.75%   |
| pt_PT       | 1         | 0.25%   |
| POSIX       | 1         | 0.25%   |
| fi_FI       | 1         | 0.25%   |
| en_US.utf-8 | 1         | 0.25%   |
| en_IE       | 1         | 0.25%   |
| en_150      | 1         | 0.25%   |
| en_001      | 1         | 0.25%   |
| el_GR       | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 208       | 53.06%  |
| BIOS | 184       | 46.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 318       | 80.51%  |
| Btrfs   | 32        | 8.1%    |
| Overlay | 22        | 5.57%   |
| Unknown | 11        | 2.78%   |
| Xfs     | 9         | 2.28%   |
| Zfs     | 2         | 0.51%   |
| Ext3    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 222       | 56.63%  |
| GPT     | 136       | 34.69%  |
| MBR     | 34        | 8.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 358       | 91.79%  |
| Yes       | 32        | 8.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 77.81%  |
| Yes       | 87        | 22.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 118       | 30.33%  |
| Hewlett-Packard      | 75        | 19.28%  |
| Dell                 | 56        | 14.4%   |
| ASUSTek Computer     | 40        | 10.28%  |
| Acer                 | 31        | 7.97%   |
| Apple                | 15        | 3.86%   |
| HUAWEI               | 12        | 3.08%   |
| Toshiba              | 7         | 1.8%    |
| Samsung Electronics  | 6         | 1.54%   |
| Packard Bell         | 6         | 1.54%   |
| MSI                  | 6         | 1.54%   |
| Clevo                | 4         | 1.03%   |
| Notebook             | 3         | 0.77%   |
| Unknown              | 3         | 0.77%   |
| Teclast              | 1         | 0.26%   |
| Razer                | 1         | 0.26%   |
| Nokia                | 1         | 0.26%   |
| LAMINA               | 1         | 0.26%   |
| Intel Client Systems | 1         | 0.26%   |
| Google               | 1         | 0.26%   |
| Alienware            | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HUAWEI MACH-WX9                                    | 5         | 1.29%   |
| Dell Precision 5530                                | 5         | 1.29%   |
| Unknown                                            | 4         | 1.03%   |
| HUAWEI WRT-WX9                                     | 3         | 0.77%   |
| HP ProBook 430 G2                                  | 3         | 0.77%   |
| HP EliteBook 8470p                                 | 3         | 0.77%   |
| HP EliteBook 840 G6                                | 3         | 0.77%   |
| Dell XPS 15 9570                                   | 3         | 0.77%   |
| Dell XPS 13 9380                                   | 3         | 0.77%   |
| Apple MacBookPro12,1                               | 3         | 0.77%   |
| Lenovo Z50-70 20354                                | 2         | 0.51%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                    | 2         | 0.51%   |
| Lenovo Y520-15IKBN 80WK                            | 2         | 0.51%   |
| Lenovo ThinkPad X230 23252EG                       | 2         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1MX           | 2         | 0.51%   |
| Lenovo ThinkPad L450 20DT001NMN                    | 2         | 0.51%   |
| HP ProBook 6550b                                   | 2         | 0.51%   |
| HP ProBook 4330s                                   | 2         | 0.51%   |
| HP Pavilion Notebook                               | 2         | 0.51%   |
| HP OMEN by HP Laptop                               | 2         | 0.51%   |
| HP EliteBook 8560p                                 | 2         | 0.51%   |
| HP EliteBook 840 G5                                | 2         | 0.51%   |
| HP EliteBook 840 G4                                | 2         | 0.51%   |
| HP EliteBook 830 G6                                | 2         | 0.51%   |
| HP EliteBook 820 G1                                | 2         | 0.51%   |
| Dell XPS 15 9500                                   | 2         | 0.51%   |
| Dell XPS 15 7590                                   | 2         | 0.51%   |
| Dell Latitude E6530                                | 2         | 0.51%   |
| Dell Latitude E5470                                | 2         | 0.51%   |
| Dell Latitude E5450                                | 2         | 0.51%   |
| Dell Latitude 5480                                 | 2         | 0.51%   |
| ASUS UX430UQ                                       | 2         | 0.51%   |
| Apple MacBookPro11,1                               | 2         | 0.51%   |
| Acer Swift SF514-51                                | 2         | 0.51%   |
| Acer Aspire V3-571G                                | 2         | 0.51%   |
| Acer Aspire E5-575G                                | 2         | 0.51%   |
| Toshiba Satellite L750                             | 1         | 0.26%   |
| Toshiba Satellite L510                             | 1         | 0.26%   |
| Toshiba Satellite C660D                            | 1         | 0.26%   |
| Toshiba Satellite C55-A-1MW                        | 1         | 0.26%   |
| Toshiba Satellite A100                             | 1         | 0.26%   |
| Toshiba NB520                                      | 1         | 0.26%   |
| Teclast F6 Plus                                    | 1         | 0.26%   |
| Samsung RF511/RF411/RF711                          | 1         | 0.26%   |
| Samsung R19/R20/R21                                | 1         | 0.26%   |
| Samsung N150/N210/N220                             | 1         | 0.26%   |
| Samsung 950XCJ/951XCJ/950XCR                       | 1         | 0.26%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                | 1         | 0.26%   |
| Samsung 870Z5G/880Z5F                              | 1         | 0.26%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.26%   |
| Packard Bell SJV50MV                               | 1         | 0.26%   |
| Packard Bell EasyNote_BU45                         | 1         | 0.26%   |
| Packard Bell EasyNote TS11HR                       | 1         | 0.26%   |
| Packard Bell EasyNote TE11HC                       | 1         | 0.26%   |
| Packard Bell EasyNote MB65                         | 1         | 0.26%   |
| Packard Bell EasyNote ENTG71BM                     | 1         | 0.26%   |
| Notebook W230SD                                    | 1         | 0.26%   |
| Notebook NV4XMB,ME,MZ                              | 1         | 0.26%   |
| Notebook N8xEJEK                                   | 1         | 0.26%   |
| Nokia N900                                         | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 92        | 23.65%  |
| HP EliteBook          | 29        | 7.46%   |
| Dell Latitude         | 22        | 5.66%   |
| Acer Aspire           | 20        | 5.14%   |
| HP ProBook            | 16        | 4.11%   |
| Dell XPS              | 13        | 3.34%   |
| Dell Precision        | 13        | 3.34%   |
| HP ZBook              | 8         | 2.06%   |
| Lenovo IdeaPad        | 7         | 1.8%    |
| HP Pavilion           | 6         | 1.54%   |
| Dell Inspiron         | 6         | 1.54%   |
| Toshiba Satellite     | 5         | 1.29%   |
| Packard Bell EasyNote | 5         | 1.29%   |
| Lenovo Yoga           | 5         | 1.29%   |
| HUAWEI MACH-WX9       | 5         | 1.29%   |
| HP OMEN               | 5         | 1.29%   |
| ASUS VivoBook         | 5         | 1.29%   |
| Acer Swift            | 5         | 1.29%   |
| Unknown               | 4         | 1.03%   |
| HUAWEI WRT-WX9        | 3         | 0.77%   |
| HP Laptop             | 3         | 0.77%   |
| ASUS ZenBook          | 3         | 0.77%   |
| Apple MacBookPro12    | 3         | 0.77%   |
| Apple MacBookPro11    | 3         | 0.77%   |
| Acer Nitro            | 3         | 0.77%   |
| Lenovo Z50-70         | 2         | 0.51%   |
| Lenovo Y520-15IKBN    | 2         | 0.51%   |
| Lenovo Legion         | 2         | 0.51%   |
| HP Presario           | 2         | 0.51%   |
| ASUS Zephyrus         | 2         | 0.51%   |
| ASUS UX430UQ          | 2         | 0.51%   |
| Toshiba NB520         | 1         | 0.26%   |
| Teclast F6            | 1         | 0.26%   |
| Samsung RF511         | 1         | 0.26%   |
| Samsung R19           | 1         | 0.26%   |
| Samsung N150          | 1         | 0.26%   |
| Samsung 950XCJ        | 1         | 0.26%   |
| Samsung 900X3C        | 1         | 0.26%   |
| Samsung 870Z5G        | 1         | 0.26%   |
| Razer Blade           | 1         | 0.26%   |
| Packard Bell SJV50MV  | 1         | 0.26%   |
| Notebook W230SD       | 1         | 0.26%   |
| Notebook NV4XMB       | 1         | 0.26%   |
| Notebook N8xEJEK      | 1         | 0.26%   |
| Nokia N900            | 1         | 0.26%   |
| MSI GS66              | 1         | 0.26%   |
| MSI GS65              | 1         | 0.26%   |
| MSI GP70              | 1         | 0.26%   |
| MSI GL62M             | 1         | 0.26%   |
| MSI GE72VR            | 1         | 0.26%   |
| MSI Alpha             | 1         | 0.26%   |
| Lenovo V15            | 1         | 0.26%   |
| Lenovo V130-14IKB     | 1         | 0.26%   |
| Lenovo G710           | 1         | 0.26%   |
| Lenovo G550           | 1         | 0.26%   |
| Lenovo G50-80         | 1         | 0.26%   |
| Lenovo G50-30         | 1         | 0.26%   |
| Lenovo Flex           | 1         | 0.26%   |
| Lenovo B575e          | 1         | 0.26%   |
| LAMINA T-1012B        | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 46        | 11.83%  |
| 2019    | 42        | 10.8%   |
| 2016    | 39        | 10.03%  |
| 2012    | 37        | 9.51%   |
| 2011    | 33        | 8.48%   |
| 2020    | 31        | 7.97%   |
| 2017    | 29        | 7.46%   |
| 2015    | 26        | 6.68%   |
| 2014    | 25        | 6.43%   |
| 2010    | 25        | 6.43%   |
| 2021    | 15        | 3.86%   |
| 2013    | 13        | 3.34%   |
| 2009    | 11        | 2.83%   |
| 2007    | 8         | 2.06%   |
| 2008    | 5         | 1.29%   |
| 2022    | 1         | 0.26%   |
| 2006    | 1         | 0.26%   |
| 2005    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 389       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 341       | 87.21%  |
| Enabled  | 50        | 12.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 387       | 99.49%  |
| Yes  | 2         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 122       | 31.04%  |
| 16.01-24.0  | 91        | 23.16%  |
| 8.01-16.0   | 67        | 17.05%  |
| 3.01-4.0    | 55        | 13.99%  |
| 32.01-64.0  | 35        | 8.91%   |
| 1.01-2.0    | 10        | 2.54%   |
| 64.01-256.0 | 4         | 1.02%   |
| 24.01-32.0  | 3         | 0.76%   |
| 2.01-3.0    | 3         | 0.76%   |
| 0.51-1.0    | 2         | 0.51%   |
| 0.01-0.5    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 137       | 32.16%  |
| 2.01-3.0   | 105       | 24.65%  |
| 4.01-8.0   | 75        | 17.61%  |
| 3.01-4.0   | 72        | 16.9%   |
| 0.51-1.0   | 17        | 3.99%   |
| 8.01-16.0  | 14        | 3.29%   |
| 0.01-0.5   | 4         | 0.94%   |
| 16.01-24.0 | 2         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 312       | 78.79%  |
| 2      | 72        | 18.18%  |
| 3      | 7         | 1.77%   |
| 0      | 3         | 0.76%   |
| 6      | 1         | 0.25%   |
| 4      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 290       | 74.17%  |
| Yes       | 101       | 25.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 320       | 82.05%  |
| No        | 70        | 17.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 385       | 98.97%  |
| No        | 4         | 1.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 78.59%  |
| No        | 85        | 21.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Norway  | 389       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Oslo             | 118       | 28.78%  |
| Trondheim        | 23        | 5.61%   |
| Bergen           | 21        | 5.12%   |
| Stavanger        | 11        | 2.68%   |
| Kristiansand     | 10        | 2.44%   |
| TromsГё        | 9         | 2.2%    |
| Drammen          | 8         | 1.95%   |
| Skien            | 6         | 1.46%   |
| Haugesund        | 5         | 1.22%   |
| Г…lesund      | 4         | 0.98%   |
| Sarpsborg        | 4         | 0.98%   |
| Nesttun          | 4         | 0.98%   |
| Fredrikstad      | 4         | 0.98%   |
| Bryne            | 4         | 0.98%   |
| Solbergelva      | 3         | 0.73%   |
| Nesoddtangen     | 3         | 0.73%   |
| Moss             | 3         | 0.73%   |
| Molde            | 3         | 0.73%   |
| Larvik           | 3         | 0.73%   |
| Kolbotn          | 3         | 0.73%   |
| Harstad          | 3         | 0.73%   |
| Halden           | 3         | 0.73%   |
| GjÃ¸vik        | 3         | 0.73%   |
| Fornebu          | 3         | 0.73%   |
| Asker            | 3         | 0.73%   |
| As               | 3         | 0.73%   |
| Arendal          | 3         | 0.73%   |
| Vollen           | 2         | 0.49%   |
| TromsÃ¸        | 2         | 0.49%   |
| Svelvik          | 2         | 0.49%   |
| Strommen         | 2         | 0.49%   |
| Stjordal         | 2         | 0.49%   |
| Sofiemyr         | 2         | 0.49%   |
| Ski              | 2         | 0.49%   |
| Sandnes          | 2         | 0.49%   |
| Sandefjord       | 2         | 0.49%   |
| Saetre           | 2         | 0.49%   |
| Royse            | 2         | 0.49%   |
| Melhus           | 2         | 0.49%   |
| Loddefjord       | 2         | 0.49%   |
| LillestrГёm    | 2         | 0.49%   |
| Lillehammer      | 2         | 0.49%   |
| Kopervik         | 2         | 0.49%   |
| Kodal            | 2         | 0.49%   |
| Hvalstad         | 2         | 0.49%   |
| Honefoss         | 2         | 0.49%   |
| Floro            | 2         | 0.49%   |
| Fiskum           | 2         | 0.49%   |
| Brumunddal       | 2         | 0.49%   |
| Borre            | 2         | 0.49%   |
| BodÃ¸          | 2         | 0.49%   |
| Berger           | 2         | 0.49%   |
| Vinstra          | 1         | 0.24%   |
| Vikhamar         | 1         | 0.24%   |
| Vestby           | 1         | 0.24%   |
| Vegarshei        | 1         | 0.24%   |
| Vear             | 1         | 0.24%   |
| Valldal          | 1         | 0.24%   |
| Valestrandfossen | 1         | 0.24%   |
| Tromsø          | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 109       | 145    | 23.44%  |
| Toshiba             | 42        | 47     | 9.03%   |
| SanDisk             | 40        | 45     | 8.6%    |
| WDC                 | 37        | 44     | 7.96%   |
| Seagate             | 36        | 41     | 7.74%   |
| SK Hynix            | 26        | 28     | 5.59%   |
| Unknown             | 25        | 30     | 5.38%   |
| Intel               | 21        | 24     | 4.52%   |
| Kingston            | 16        | 18     | 3.44%   |
| Micron Technology   | 14        | 18     | 3.01%   |
| Crucial             | 14        | 16     | 3.01%   |
| Hitachi             | 13        | 18     | 2.8%    |
| LITEON              | 10        | 14     | 2.15%   |
| HGST                | 10        | 10     | 2.15%   |
| Apple               | 10        | 12     | 2.15%   |
| Lenovo              | 4         | 4      | 0.86%   |
| KIOXIA              | 4         | 10     | 0.86%   |
| A-DATA Technology   | 4         | 6      | 0.86%   |
| Fujitsu             | 3         | 3      | 0.65%   |
| Corsair             | 3         | 3      | 0.65%   |
| XPG                 | 2         | 2      | 0.43%   |
| Transcend           | 2         | 2      | 0.43%   |
| PNY                 | 2         | 3      | 0.43%   |
| Phison              | 2         | 3      | 0.43%   |
| OCZ                 | 2         | 2      | 0.43%   |
| LITEONIT            | 2         | 2      | 0.43%   |
| Lexar               | 2         | 2      | 0.43%   |
| China               | 2         | 2      | 0.43%   |
| Ugreen              | 1         | 1      | 0.22%   |
| Teclast             | 1         | 1      | 0.22%   |
| STEC                | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| Linux               | 1         | 1      | 0.22%   |
| LaCie               | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| Artisan             | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB          | 12        | 2.48%   |
| Toshiba NVMe SSD Drive 256GB          | 6         | 1.24%   |
| Unknown MMC Card  64GB                | 5         | 1.04%   |
| Sandisk NVMe SSD Drive 512GB          | 5         | 1.04%   |
| Samsung NVMe SSD Drive 1024GB         | 5         | 1.04%   |
| HGST HTS721010A9E630 1TB              | 5         | 1.04%   |
| Toshiba NVMe SSD Drive 512GB          | 4         | 0.83%   |
| Sandisk NVMe SSD Drive 500GB          | 4         | 0.83%   |
| Sandisk NVMe SSD Drive 256GB          | 4         | 0.83%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 0.83%   |
| Intel NVMe SSD Drive 512GB            | 4         | 0.83%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 3         | 0.62%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 3         | 0.62%   |
| Unknown MMC Card  16GB                | 3         | 0.62%   |
| SK Hynix PC401 NVMe 512GB             | 3         | 0.62%   |
| SK Hynix PC401 NVMe 1TB               | 3         | 0.62%   |
| SK Hynix NVMe SSD Drive 512GB         | 3         | 0.62%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 3         | 0.62%   |
| Seagate ST9500325AS 500GB             | 3         | 0.62%   |
| Seagate Expansion+ 2TB                | 3         | 0.62%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD   | 3         | 0.62%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD   | 3         | 0.62%   |
| Samsung NVMe SSD Drive 500GB          | 3         | 0.62%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD  | 3         | 0.62%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 3         | 0.62%   |
| Hitachi HTS545050B9A300 500GB         | 3         | 0.62%   |
| HGST HTS725050A7E630 500GB            | 3         | 0.62%   |
| Crucial CT120BX500SSD1 120GB          | 3         | 0.62%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 2         | 0.41%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB  | 2         | 0.41%   |
| WDC PC SN720 SDAPNTW-256G-1027 256GB  | 2         | 0.41%   |
| Unknown MMC Card  7GB                 | 2         | 0.41%   |
| Toshiba MQ01ABD075 752GB              | 2         | 0.41%   |
| Toshiba MQ01ABD050V -63 500GB         | 2         | 0.41%   |
| Toshiba MK5059GSXP 500GB              | 2         | 0.41%   |
| Toshiba KXG60ZNV512G NVMe 512GB       | 2         | 0.41%   |
| SK Hynix NVMe SSD Drive 1024GB        | 2         | 0.41%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 2         | 0.41%   |
| Seagate ST9500420AS 500GB             | 2         | 0.41%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 2         | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 0.41%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 0.41%   |
| Seagate ST1000LM014-SSHD-8GB          | 2         | 0.41%   |
| SanDisk SD8TB8U256G1001 256GB SSD     | 2         | 0.41%   |
| Sandisk NVMe SSD Drive 1TB            | 2         | 0.41%   |
| Sandisk NVMe SSD Drive 1024GB         | 2         | 0.41%   |
| Samsung SSD PM810 2.5 7mm 128GB       | 2         | 0.41%   |
| Samsung SSD 960 EVO 1TB               | 2         | 0.41%   |
| Samsung SSD 850 EVO 500GB             | 2         | 0.41%   |
| Samsung SSD 850 EVO 250GB             | 2         | 0.41%   |
| Samsung SSD 840 EVO 120GB             | 2         | 0.41%   |
| Samsung NVMe SSD Drive 512GB          | 2         | 0.41%   |
| Samsung MZVLW256HEHP-000H1 256GB      | 2         | 0.41%   |
| Samsung MZVLB512HBJQ-000L7 512GB      | 2         | 0.41%   |
| Samsung MZVLB512HAJQ-000H1 512GB      | 2         | 0.41%   |
| Samsung MZVLB256HAHQ-000L7 256GB      | 2         | 0.41%   |
| Samsung MZVLB256HAHQ-000H1 256GB      | 2         | 0.41%   |
| Samsung MZVKW512HMJP-000H1 512GB      | 2         | 0.41%   |
| Samsung MZ7TE256HMHP-000L7 256GB SSD  | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 36.08%  |
| WDC                 | 17        | 21     | 17.53%  |
| Toshiba             | 15        | 17     | 15.46%  |
| Hitachi             | 13        | 18     | 13.4%   |
| HGST                | 10        | 10     | 10.31%  |
| Fujitsu             | 3         | 3      | 3.09%   |
| Unknown             | 1         | 1      | 1.03%   |
| Samsung Electronics | 1         | 4      | 1.03%   |
| LaCie               | 1         | 1      | 1.03%   |
| ASMT                | 1         | 1      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 68     | 29.51%  |
| SanDisk             | 22        | 25     | 12.02%  |
| Kingston            | 15        | 17     | 8.2%    |
| Crucial             | 14        | 16     | 7.65%   |
| Intel               | 13        | 15     | 7.1%    |
| Micron Technology   | 9         | 12     | 4.92%   |
| Apple               | 9         | 11     | 4.92%   |
| SK Hynix            | 8         | 9      | 4.37%   |
| LITEON              | 8         | 12     | 4.37%   |
| WDC                 | 6         | 9      | 3.28%   |
| Toshiba             | 6         | 6      | 3.28%   |
| Corsair             | 3         | 3      | 1.64%   |
| A-DATA Technology   | 3         | 5      | 1.64%   |
| Transcend           | 2         | 2      | 1.09%   |
| PNY                 | 2         | 3      | 1.09%   |
| OCZ                 | 2         | 2      | 1.09%   |
| LITEONIT            | 2         | 2      | 1.09%   |
| China               | 2         | 2      | 1.09%   |
| Teclast             | 1         | 1      | 0.55%   |
| Seagate             | 1         | 1      | 0.55%   |
| Patriot             | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 172       | 222    | 38.74%  |
| NVMe    | 146       | 188    | 32.88%  |
| HDD     | 95        | 116    | 21.4%   |
| MMC     | 24        | 29     | 5.41%   |
| Unknown | 7         | 7      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 244       | 321    | 56.61%  |
| NVMe | 146       | 188    | 33.87%  |
| MMC  | 24        | 29     | 5.57%   |
| SAS  | 17        | 24     | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 207       | 271    | 77.24%  |
| 0.51-1.0   | 50        | 53     | 18.66%  |
| 1.01-2.0   | 8         | 10     | 2.99%   |
| 4.01-10.0  | 3         | 4      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 152       | 37.72%  |
| 251-500        | 97        | 24.07%  |
| 501-1000       | 44        | 10.92%  |
| 1-20           | 33        | 8.19%   |
| 1001-2000      | 24        | 5.96%   |
| 51-100         | 18        | 4.47%   |
| 21-50          | 12        | 2.98%   |
| More than 3000 | 9         | 2.23%   |
| 2001-3000      | 8         | 1.99%   |
| Unknown        | 6         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 177       | 42.04%  |
| 21-50          | 68        | 16.15%  |
| 101-250        | 58        | 13.78%  |
| 51-100         | 50        | 11.88%  |
| 251-500        | 35        | 8.31%   |
| 1001-2000      | 13        | 3.09%   |
| 501-1000       | 10        | 2.38%   |
| Unknown        | 6         | 1.43%   |
| More than 3000 | 4         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 4.76%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 4.76%   |
| SK Hynix SH920 2.5 7MM 128GB SSD                    | 1         | 1      | 4.76%   |
| SK Hynix SC210 2.5 7MM 256GB SSD                    | 1         | 1      | 4.76%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 4.76%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 4.76%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 4.76%   |
| Seagate ST1000LM014-SSHD-8GB                        | 1         | 1      | 4.76%   |
| SanDisk SD8TN8U-256G-1006 256GB SSD                 | 1         | 1      | 4.76%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB         | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 3      | 4.76%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD      | 1         | 1      | 4.76%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD      | 1         | 1      | 4.76%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB                | 1         | 1      | 4.76%   |
| Intel SSDSA1M080G2LE 80GB                           | 1         | 1      | 4.76%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 4.76%   |
| Crucial CT256M550SSD1 256GB                         | 1         | 1      | 4.76%   |
| Corsair Performance Pro 128GB SSD                   | 1         | 1      | 4.76%   |
| Corsair Force GS 240GB SSD                          | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 19.05%  |
| SK Hynix            | 3         | 3      | 14.29%  |
| Micron Technology   | 3         | 5      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| Corsair             | 2         | 2      | 9.52%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Lenovo              | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 14     | 57.14%  |
| HDD  | 8         | 8      | 38.1%   |
| NVMe | 1         | 1      | 4.76%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 242       | 345    | 58.31%  |
| Works    | 152       | 194    | 36.63%  |
| Malfunc  | 21        | 23     | 5.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 268       | 59.42%  |
| Samsung Electronics          | 61        | 13.53%  |
| Sandisk                      | 30        | 6.65%   |
| AMD                          | 30        | 6.65%   |
| Toshiba America Info Systems | 21        | 4.66%   |
| SK Hynix                     | 18        | 3.99%   |
| Micron Technology            | 5         | 1.11%   |
| Lenovo                       | 4         | 0.89%   |
| KIOXIA                       | 3         | 0.67%   |
| Phison Electronics           | 2         | 0.44%   |
| Nvidia                       | 2         | 0.44%   |
| Lite-On Technology           | 2         | 0.44%   |
| ADATA Technology             | 2         | 0.44%   |
| Marvell Technology Group     | 1         | 0.22%   |
| Kingston Technology Company  | 1         | 0.22%   |
| Apple                        | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 37        | 7.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 34        | 7.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 28        | 5.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 26        | 5.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 24        | 5.05%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 4.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 19        | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 19        | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 14        | 2.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 2.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 12        | 2.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 11        | 2.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 11        | 2.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 11        | 2.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 2.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 11        | 2.32%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                            | 8         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 8         | 1.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 7         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 7         | 1.47%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 1.26%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 5         | 1.05%   |
| Samsung Electronics SATA controller                                                    | 5         | 1.05%   |
| Micron Non-Volatile memory controller                                                  | 5         | 1.05%   |
| Intel SSD 660P Series                                                                  | 5         | 1.05%   |
| SK Hynix Non-Volatile memory controller                                                | 4         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 0.84%   |
| Lenovo Non-Volatile memory controller                                                  | 4         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 4         | 0.84%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.63%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 0.63%   |
| KIOXIA Non-Volatile memory controller                                                  | 3         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.63%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.42%   |
| SK Hynix Gold P31 SSD                                                                  | 2         | 0.42%   |
| Sandisk PC SN520 NVMe SSD                                                              | 2         | 0.42%   |
| Sandisk Non-Volatile memory controller                                                 | 2         | 0.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.42%   |
| Lite-On Non-Volatile memory controller                                                 | 2         | 0.42%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 0.42%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 0.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.42%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 2         | 0.42%   |
| AMD SB600 IDE                                                                          | 2         | 0.42%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 2         | 0.42%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.21%   |
| SK Hynix BC511                                                                         | 1         | 0.21%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 260       | 56.89%  |
| NVMe | 145       | 31.73%  |
| RAID | 31        | 6.78%   |
| IDE  | 21        | 4.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 341       | 87.66%  |
| AMD    | 47        | 12.08%  |
| ARM    | 1         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 3.34%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 3.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 2.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 2.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 2.31%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 9         | 2.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 2.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 6         | 1.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.29%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 5         | 1.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.29%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.29%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 5         | 1.29%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 4         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.03%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.03%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.03%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.77%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.77%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 3         | 0.77%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 3         | 0.77%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 0.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.77%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.77%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 0.77%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 3         | 0.77%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 3         | 0.77%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.77%   |
| Intel Genuine CPU T2080 @ 1.73GHz             | 2         | 0.51%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.51%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.51%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.51%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.51%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 2         | 0.51%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.51%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.51%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.51%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.51%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.51%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 133       | 34.19%  |
| Intel Core i5           | 123       | 31.62%  |
| Intel Core i3           | 20        | 5.14%   |
| Intel Celeron           | 13        | 3.34%   |
| Other                   | 12        | 3.08%   |
| AMD Ryzen 7             | 11        | 2.83%   |
| Intel Core 2 Duo        | 10        | 2.57%   |
| AMD Ryzen 5             | 8         | 2.06%   |
| Intel Pentium           | 6         | 1.54%   |
| Intel Core i9           | 6         | 1.54%   |
| Intel Atom              | 5         | 1.29%   |
| Intel Genuine           | 4         | 1.03%   |
| Intel Core 2            | 4         | 1.03%   |
| AMD A8                  | 4         | 1.03%   |
| AMD Ryzen 7 PRO         | 3         | 0.77%   |
| AMD A6                  | 3         | 0.77%   |
| Intel Pentium Dual-Core | 2         | 0.51%   |
| AMD Turion 64 X2 Mobile | 2         | 0.51%   |
| AMD Ryzen 3             | 2         | 0.51%   |
| AMD Phenom II           | 2         | 0.51%   |
| AMD E2                  | 2         | 0.51%   |
| Intel Xeon              | 1         | 0.26%   |
| Intel Pentium Gold      | 1         | 0.26%   |
| Intel Core M            | 1         | 0.26%   |
| Intel Core 2 Solo       | 1         | 0.26%   |
| Intel Celeron Dual-Core | 1         | 0.26%   |
| AMD V160                | 1         | 0.26%   |
| AMD V120                | 1         | 0.26%   |
| AMD Ryzen 9             | 1         | 0.26%   |
| AMD Ryzen 5 PRO         | 1         | 0.26%   |
| AMD E1                  | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD Athlon II           | 1         | 0.26%   |
| AMD Athlon              | 1         | 0.26%   |
| AMD A10                 | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 201       | 51.67%  |
| 4      | 124       | 31.88%  |
| 6      | 39        | 10.03%  |
| 8      | 17        | 4.37%   |
| 1      | 7         | 1.8%    |
| 3      | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 389       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 311       | 79.74%  |
| 1      | 78        | 20%     |
| 8      | 1         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 376       | 96.41%  |
| Unknown        | 9         | 2.31%   |
| 32-bit         | 5         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 22.11%  |
| 0x206a7    | 27        | 6.78%   |
| 0x906ea    | 24        | 6.03%   |
| 0x306a9    | 23        | 5.78%   |
| 0x406e3    | 19        | 4.77%   |
| 0x40651    | 18        | 4.52%   |
| 0x806ea    | 17        | 4.27%   |
| 0x806ec    | 15        | 3.77%   |
| 0x806e9    | 14        | 3.52%   |
| 0x306d4    | 13        | 3.27%   |
| 0x20655    | 11        | 2.76%   |
| 0x306c3    | 9         | 2.26%   |
| 0x1067a    | 9         | 2.26%   |
| 0xa0652    | 8         | 2.01%   |
| 0x506e3    | 8         | 2.01%   |
| 0x906e9    | 7         | 1.76%   |
| 0x806eb    | 7         | 1.76%   |
| 0x806c1    | 5         | 1.26%   |
| 0x20652    | 5         | 1.26%   |
| 0x010000c8 | 5         | 1.26%   |
| 0x08600106 | 4         | 1.01%   |
| 0x08600103 | 4         | 1.01%   |
| 0x906ed    | 3         | 0.75%   |
| 0x806d1    | 3         | 0.75%   |
| 0x506c9    | 3         | 0.75%   |
| 0x08600104 | 3         | 0.75%   |
| 0x08108109 | 3         | 0.75%   |
| 0x08108102 | 3         | 0.75%   |
| 0x05000119 | 3         | 0.75%   |
| 0x6f6      | 2         | 0.5%    |
| 0x406c3    | 2         | 0.5%    |
| 0x30678    | 2         | 0.5%    |
| 0x106e5    | 2         | 0.5%    |
| 0x10676    | 2         | 0.5%    |
| 0x08608103 | 2         | 0.5%    |
| 0x08600102 | 2         | 0.5%    |
| 0x06006704 | 2         | 0.5%    |
| 0x03000027 | 2         | 0.5%    |
| 0x706e5    | 1         | 0.25%   |
| 0x706a1    | 1         | 0.25%   |
| 0x6fd      | 1         | 0.25%   |
| 0x6fb      | 1         | 0.25%   |
| 0x6f2      | 1         | 0.25%   |
| 0x6ec      | 1         | 0.25%   |
| 0x6e8      | 1         | 0.25%   |
| 0x406c4    | 1         | 0.25%   |
| 0x30673    | 1         | 0.25%   |
| 0x30661    | 1         | 0.25%   |
| 0x106ca    | 1         | 0.25%   |
| 0x106c2    | 1         | 0.25%   |
| 0x0a50000c | 1         | 0.25%   |
| 0x0a50000b | 1         | 0.25%   |
| 0x0810100b | 1         | 0.25%   |
| 0x0700010f | 1         | 0.25%   |
| 0x06006110 | 1         | 0.25%   |
| 0x06003106 | 1         | 0.25%   |
| 0x06001119 | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 108       | 27.76%  |
| Haswell       | 36        | 9.25%   |
| Skylake       | 35        | 9%      |
| SandyBridge   | 32        | 8.23%   |
| IvyBridge     | 31        | 7.97%   |
| Broadwell     | 20        | 5.14%   |
| Westmere      | 17        | 4.37%   |
| Zen 2         | 14        | 3.6%    |
| Penryn        | 14        | 3.6%    |
| TigerLake     | 9         | 2.31%   |
| CometLake     | 8         | 2.06%   |
| Zen+          | 7         | 1.8%    |
| Silvermont    | 7         | 1.8%    |
| K10           | 5         | 1.29%   |
| Core          | 5         | 1.29%   |
| Unknown       | 5         | 1.29%   |
| P6            | 3         | 0.77%   |
| Nehalem       | 3         | 0.77%   |
| Icelake       | 3         | 0.77%   |
| Goldmont plus | 3         | 0.77%   |
| Goldmont      | 3         | 0.77%   |
| Excavator     | 3         | 0.77%   |
| Bonnell       | 3         | 0.77%   |
| Bobcat        | 3         | 0.77%   |
| Zen 3         | 2         | 0.51%   |
| Piledriver    | 2         | 0.51%   |
| K8 Hammer     | 2         | 0.51%   |
| K10 Llano     | 2         | 0.51%   |
| Zen           | 1         | 0.26%   |
| Steamroller   | 1         | 0.26%   |
| Puma          | 1         | 0.26%   |
| Jaguar        | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 309       | 61.55%  |
| Nvidia | 122       | 24.3%   |
| AMD    | 71        | 14.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 5.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 5.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 4.84%   |
| Intel UHD Graphics 620                                                                   | 24        | 4.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 4.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 4.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 4.26%   |
| Intel HD Graphics 620                                                                    | 19        | 3.68%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.91%   |
| AMD Renoir                                                                               | 14        | 2.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 2.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.94%   |
| Intel HD Graphics 530                                                                    | 9         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.55%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.36%   |
| Intel HD Graphics 630                                                                    | 6         | 1.16%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 5         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.97%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.78%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.78%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.58%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 3         | 0.58%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.58%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.58%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 3         | 0.58%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 0.58%   |
| Intel Iris Graphics 6100                                                                 | 3         | 0.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.58%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.58%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 3         | 0.58%   |
| AMD Lucienne                                                                             | 3         | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.58%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.39%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.39%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.39%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 2         | 0.39%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 2         | 0.39%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.39%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.39%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 2         | 0.39%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.39%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.39%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 2         | 0.39%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 197       | 50.51%  |
| Intel + Nvidia | 98        | 25.13%  |
| 1 x AMD        | 47        | 12.05%  |
| 1 x Nvidia     | 22        | 5.64%   |
| Intel + AMD    | 14        | 3.59%   |
| 2 x AMD        | 9         | 2.31%   |
| AMD + Nvidia   | 2         | 0.51%   |
| Other          | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 318       | 80.51%  |
| Proprietary | 66        | 16.71%  |
| Unknown     | 11        | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 252       | 63.64%  |
| 1.01-2.0   | 49        | 12.37%  |
| 0.01-0.5   | 38        | 9.6%    |
| 3.01-4.0   | 28        | 7.07%   |
| 0.51-1.0   | 17        | 4.29%   |
| 5.01-6.0   | 8         | 2.02%   |
| 7.01-8.0   | 3         | 0.76%   |
| 2.01-3.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 82        | 17.63%  |
| AU Optronics            | 79        | 16.99%  |
| BOE                     | 46        | 9.89%   |
| Samsung Electronics     | 45        | 9.68%   |
| Chimei Innolux          | 45        | 9.68%   |
| Sharp                   | 22        | 4.73%   |
| Dell                    | 19        | 4.09%   |
| Lenovo                  | 18        | 3.87%   |
| Apple                   | 15        | 3.23%   |
| Hewlett-Packard         | 12        | 2.58%   |
| AOC                     | 10        | 2.15%   |
| InfoVision              | 8         | 1.72%   |
| Chi Mei Optoelectronics | 8         | 1.72%   |
| BenQ                    | 7         | 1.51%   |
| JDI                     | 6         | 1.29%   |
| PANDA                   | 5         | 1.08%   |
| Ancor Communications    | 5         | 1.08%   |
| Acer                    | 5         | 1.08%   |
| Philips                 | 4         | 0.86%   |
| Goldstar                | 3         | 0.65%   |
| Sony                    | 2         | 0.43%   |
| Grundig                 | 2         | 0.43%   |
| CSO                     | 2         | 0.43%   |
| VOXICON                 | 1         | 0.22%   |
| Vestel Elektronik       | 1         | 0.22%   |
| Toshiba                 | 1         | 0.22%   |
| Tatung                  | 1         | 0.22%   |
| SSD                     | 1         | 0.22%   |
| S2-Tek                  | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| MiTAC                   | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| LG Philips              | 1         | 0.22%   |
| HannStar                | 1         | 0.22%   |
| Fujitsu Siemens         | 1         | 0.22%   |
| CTO                     | 1         | 0.22%   |
| CMN                     | 1         | 0.22%   |
| ASUSTek Computer        | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 7         | 1.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 5         | 1.06%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                     | 5         | 1.06%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 1.06%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 4         | 0.85%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 3         | 0.64%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 3         | 0.64%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 3         | 0.64%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 3         | 0.64%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 3         | 0.64%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch               | 3         | 0.64%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 3         | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 0.64%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 3         | 0.64%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 3         | 0.64%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                         | 3         | 0.64%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                         | 3         | 0.64%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch          | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.64%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                        | 3         | 0.64%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                   | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch      | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 2         | 0.42%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                   | 2         | 0.42%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 2         | 0.42%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch              | 2         | 0.42%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch               | 2         | 0.42%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.42%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 0.42%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch              | 2         | 0.42%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch             | 2         | 0.42%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                        | 2         | 0.42%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                         | 2         | 0.42%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.42%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 2         | 0.42%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 2         | 0.42%   |
| BOE LCD Monitor BOE06FF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.42%   |
| BOE LCD Monitor BOE06EB 1920x1080 309x173mm 13.9-inch                     | 2         | 0.42%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.42%   |
| BOE LCD Monitor BOE05F5 1366x768 277x156mm 12.5-inch                      | 2         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 206       | 47.14%  |
| 1366x768 (WXGA)   | 80        | 18.31%  |
| 3840x2160 (4K)    | 35        | 8.01%   |
| 1600x900 (HD+)    | 27        | 6.18%   |
| 2560x1440 (QHD)   | 16        | 3.66%   |
| 1920x1200 (WUXGA) | 15        | 3.43%   |
| 1280x800 (WXGA)   | 12        | 2.75%   |
| 3000x2000         | 6         | 1.37%   |
| 1440x900 (WXGA+)  | 6         | 1.37%   |
| 2560x1600         | 5         | 1.14%   |
| 2880x1800         | 4         | 0.92%   |
| 2160x1440         | 4         | 0.92%   |
| 1280x1024 (SXGA)  | 4         | 0.92%   |
| 3840x2400         | 3         | 0.69%   |
| 1024x600          | 3         | 0.69%   |
| 1360x768          | 2         | 0.46%   |
| 9600x2160         | 1         | 0.23%   |
| 3840x1100         | 1         | 0.23%   |
| 3840x1080         | 1         | 0.23%   |
| 2560x1080         | 1         | 0.23%   |
| 2304x1440         | 1         | 0.23%   |
| 2048x1152         | 1         | 0.23%   |
| 1920x540          | 1         | 0.23%   |
| 1280x720 (HD)     | 1         | 0.23%   |
| Unknown           | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 153       | 32.97%  |
| 13      | 76        | 16.38%  |
| 14      | 73        | 15.73%  |
| 27      | 31        | 6.68%   |
| 17      | 31        | 6.68%   |
| 12      | 28        | 6.03%   |
| 24      | 22        | 4.74%   |
| Unknown | 7         | 1.51%   |
| 31      | 6         | 1.29%   |
| 23      | 5         | 1.08%   |
| 25      | 3         | 0.65%   |
| 84      | 2         | 0.43%   |
| 54      | 2         | 0.43%   |
| 48      | 2         | 0.43%   |
| 43      | 2         | 0.43%   |
| 26      | 2         | 0.43%   |
| 21      | 2         | 0.43%   |
| 19      | 2         | 0.43%   |
| 11      | 2         | 0.43%   |
| 10      | 2         | 0.43%   |
| 72      | 1         | 0.22%   |
| 55      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 39      | 1         | 0.22%   |
| 36      | 1         | 0.22%   |
| 32      | 1         | 0.22%   |
| 28      | 1         | 0.22%   |
| 22      | 1         | 0.22%   |
| 18      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 252       | 54.9%   |
| 201-300     | 77        | 16.78%  |
| 501-600     | 53        | 11.55%  |
| 351-400     | 38        | 8.28%   |
| 601-700     | 12        | 2.61%   |
| Unknown     | 7         | 1.53%   |
| 1001-1500   | 5         | 1.09%   |
| 401-500     | 4         | 0.87%   |
| 1501-2000   | 3         | 0.65%   |
| 901-1000    | 3         | 0.65%   |
| 801-900     | 2         | 0.44%   |
| 701-800     | 2         | 0.44%   |
| 101-200     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 329       | 82.66%  |
| 16/10   | 43        | 10.8%   |
| 3/2     | 13        | 3.27%   |
| 5/4     | 5         | 1.26%   |
| Unknown | 5         | 1.26%   |
| 32/9    | 1         | 0.25%   |
| 3.40    | 1         | 0.25%   |
| 21/9    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 152       | 32.83%  |
| 81-90          | 114       | 24.62%  |
| 71-80          | 35        | 7.56%   |
| 301-350        | 31        | 6.7%    |
| 61-70          | 27        | 5.83%   |
| 121-130        | 27        | 5.83%   |
| 201-250        | 22        | 4.75%   |
| 251-300        | 12        | 2.59%   |
| More than 1000 | 7         | 1.51%   |
| 351-500        | 7         | 1.51%   |
| 501-1000       | 7         | 1.51%   |
| Unknown        | 7         | 1.51%   |
| 51-60          | 3         | 0.65%   |
| 141-150        | 3         | 0.65%   |
| 131-140        | 3         | 0.65%   |
| 41-50          | 2         | 0.43%   |
| 151-200        | 2         | 0.43%   |
| 1-40           | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 219       | 47.82%  |
| 101-120       | 88        | 19.21%  |
| 51-100        | 72        | 15.72%  |
| 161-240       | 38        | 8.3%    |
| More than 240 | 29        | 6.33%   |
| Unknown       | 7         | 1.53%   |
| 1-50          | 5         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 291       | 73.3%   |
| 2     | 81        | 20.4%   |
| 3     | 13        | 3.27%   |
| 0     | 12        | 3.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 260       | 43.12%  |
| Realtek Semiconductor             | 148       | 24.54%  |
| Qualcomm Atheros                  | 60        | 9.95%   |
| Broadcom                          | 44        | 7.3%    |
| Broadcom Limited                  | 15        | 2.49%   |
| Ericsson Business Mobile Networks | 14        | 2.32%   |
| Dell                              | 10        | 1.66%   |
| Sierra Wireless                   | 9         | 1.49%   |
| Hewlett-Packard                   | 5         | 0.83%   |
| Ralink                            | 4         | 0.66%   |
| Marvell Technology Group          | 4         | 0.66%   |
| Lenovo                            | 4         | 0.66%   |
| ASUSTek Computer                  | 4         | 0.66%   |
| Fibocom                           | 3         | 0.5%    |
| DisplayLink                       | 3         | 0.5%    |
| Ralink Technology                 | 2         | 0.33%   |
| Qualcomm                          | 2         | 0.33%   |
| Nvidia                            | 2         | 0.33%   |
| NetGear                           | 2         | 0.33%   |
| MEDIATEK                          | 2         | 0.33%   |
| JMicron Technology                | 2         | 0.33%   |
| TP-Link                           | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 101       | 13.17%  |
| Intel Wireless 8265 / 8275                                         | 33        | 4.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 31        | 4.04%   |
| Intel Wi-Fi 6 AX200                                                | 28        | 3.65%   |
| Intel Wireless 8260                                                | 23        | 3%      |
| Intel Wireless 7265                                                | 23        | 3%      |
| Intel Wireless 7260                                                | 19        | 2.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 19        | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 15        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 14        | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 13        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 12        | 1.56%   |
| Intel Centrino Ultimate-N 6300                                     | 12        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 11        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 11        | 1.43%   |
| Intel Ethernet Connection (4) I219-V                               | 11        | 1.43%   |
| Intel Ethernet Connection I219-LM                                  | 10        | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                              | 10        | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                              | 10        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                    | 10        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 9         | 1.17%   |
| Intel Wireless-AC 9260                                             | 9         | 1.17%   |
| Intel Ethernet Connection I218-LM                                  | 8         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                               | 8         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                           | 8         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 8         | 1.04%   |
| Ericsson Business Mobile Networks F5521gw                          | 7         | 0.91%   |
| Intel WiFi Link 5100                                               | 6         | 0.78%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 0.78%   |
| Intel Ethernet Connection I219-V                                   | 6         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 6         | 0.78%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 6         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 6         | 0.78%   |
| Sierra Wireless EM7455                                             | 5         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 5         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 5         | 0.65%   |
| Intel Centrino Advanced-N 6235                                     | 5         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 4         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 4         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 4         | 0.52%   |
| Intel Wireless 3165                                                | 4         | 0.52%   |
| Intel Ethernet Connection I217-LM                                  | 4         | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 4         | 0.52%   |
| Intel Centrino Advanced-N 6200                                     | 4         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                           | 4         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                    | 4         | 0.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 4         | 0.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 4         | 0.52%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 4         | 0.52%   |
| Sierra Wireless EM7345 4G LTE                                      | 3         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 3         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 3         | 0.39%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                       | 3         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                             | 3         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 3         | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3         | 0.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection      | 3         | 0.39%   |
| Intel Ethernet Connection (3) I218-V                               | 3         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                              | 3         | 0.39%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                  | 3         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 249       | 59.86%  |
| Qualcomm Atheros                | 53        | 12.74%  |
| Broadcom                        | 36        | 8.65%   |
| Realtek Semiconductor           | 31        | 7.45%   |
| Broadcom Limited                | 13        | 3.13%   |
| Sierra Wireless                 | 6         | 1.44%   |
| Dell                            | 5         | 1.2%    |
| Ralink                          | 4         | 0.96%   |
| ASUSTek Computer                | 4         | 0.96%   |
| Fibocom                         | 3         | 0.72%   |
| Ralink Technology               | 2         | 0.48%   |
| Qualcomm                        | 2         | 0.48%   |
| NetGear                         | 2         | 0.48%   |
| MediaTek                        | 2         | 0.48%   |
| Hewlett-Packard                 | 2         | 0.48%   |
| TP-Link                         | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 33        | 7.93%   |
| Intel Wi-Fi 6 AX200                                            | 28        | 6.73%   |
| Intel Wireless 8260                                            | 23        | 5.53%   |
| Intel Wireless 7265                                            | 23        | 5.53%   |
| Intel Wireless 7260                                            | 19        | 4.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 4.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 2.88%   |
| Intel Centrino Ultimate-N 6300                                 | 12        | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 2.16%   |
| Intel Wireless-AC 9260                                         | 9         | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.92%   |
| Intel WiFi Link 5100                                           | 6         | 1.44%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 1.44%   |
| Sierra Wireless EM7455                                         | 5         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.2%    |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 0.96%   |
| Intel Wireless 3165                                            | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.96%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.96%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 4         | 0.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.72%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 3         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.72%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 3         | 0.72%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 3         | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 0.72%   |
| ASUS 802.11ac NIC                                              | 3         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.48%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 2         | 0.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.48%   |
| Intel Wireless 3160                                            | 2         | 0.48%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.48%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.48%   |
| HP lt4112 Gobi 4G Module Network Device                        | 2         | 0.48%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.48%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.24%   |
| Sierra Wireless EM7355 Qualcomm Gobi 4G LTE/HSPA+/EVDO         | 1         | 0.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 137       | 41.64%  |
| Realtek Semiconductor    | 132       | 40.12%  |
| Qualcomm Atheros         | 19        | 5.78%   |
| Broadcom                 | 18        | 5.47%   |
| Marvell Technology Group | 4         | 1.22%   |
| Lenovo                   | 4         | 1.22%   |
| Sierra Wireless          | 3         | 0.91%   |
| DisplayLink              | 3         | 0.91%   |
| Broadcom Limited         | 3         | 0.91%   |
| Nvidia                   | 2         | 0.61%   |
| JMicron Technology       | 2         | 0.61%   |
| Samsung Electronics      | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 30.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 9.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 4.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.26%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 3.34%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 3.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 3.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 3.04%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 2.43%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 2.43%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 2.43%   |
| Intel Ethernet Connection I219-V                                  | 6         | 1.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.22%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.22%   |
| Sierra Wireless EM7345 4G LTE                                     | 3         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.91%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.91%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.61%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.61%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.61%   |
| Intel PRO/100 VE Network Connection                               | 2         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.61%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.3%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.3%    |
| Nvidia MCP67 Ethernet                                             | 1         | 0.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.3%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.3%    |
| Lenovo ThinkPad Lan                                               | 1         | 0.3%    |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 1         | 0.3%    |
| Intel Ethernet controller                                         | 1         | 0.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.3%    |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.3%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.3%    |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.3%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.3%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.3%    |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.3%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.3%    |
| Huawei JNY-LX1                                                    | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 385       | 53.1%   |
| Ethernet | 318       | 43.86%  |
| Modem    | 21        | 2.9%    |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 363       | 69.67%  |
| Ethernet | 155       | 29.75%  |
| Modem    | 3         | 0.58%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 291       | 74.81%  |
| 1     | 93        | 23.91%  |
| 3     | 3         | 0.77%   |
| 0     | 2         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 358       | 90.86%  |
| Yes  | 36        | 9.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 55.24%  |
| Broadcom                        | 38        | 12.06%  |
| Qualcomm Atheros Communications | 15        | 4.76%   |
| Realtek Semiconductor           | 13        | 4.13%   |
| Lite-On Technology              | 13        | 4.13%   |
| Apple                           | 12        | 3.81%   |
| Foxconn / Hon Hai               | 10        | 3.17%   |
| Dell                            | 10        | 3.17%   |
| Hewlett-Packard                 | 9         | 2.86%   |
| IMC Networks                    | 8         | 2.54%   |
| ASUSTek Computer                | 6         | 1.9%    |
| Realtek                         | 2         | 0.63%   |
| Cambridge Silicon Radio         | 2         | 0.63%   |
| Ralink Technology               | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 88        | 27.94%  |
| Intel AX200 Bluetooth                                  | 27        | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 22        | 6.98%   |
| Intel AX201 Bluetooth                                  | 18        | 5.71%   |
| Broadcom BCM2045B (BDC-2.1)                            | 12        | 3.81%   |
| Realtek Bluetooth Radio                                | 10        | 3.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 9         | 2.86%   |
| Apple Bluetooth Host Controller                        | 8         | 2.54%   |
| HP Broadcom 2070 Bluetooth Combo                       | 7         | 2.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 7         | 2.22%   |
| Lite-On Bluetooth Device                               | 6         | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth                      | 5         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth             | 5         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 5         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                     | 5         | 1.59%   |
| Qualcomm Atheros  Bluetooth Device                     | 4         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                       | 4         | 1.27%   |
| Broadcom BCM20702A0                                    | 4         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]     | 4         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 3         | 0.95%   |
| Intel AX210 Bluetooth                                  | 3         | 0.95%   |
| IMC Networks Bluetooth Radio                           | 3         | 0.95%   |
| IMC Networks Bluetooth Device                          | 3         | 0.95%   |
| Dell DW375 Bluetooth Module                            | 3         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth Device                   | 3         | 0.95%   |
| Realtek Bluetooth Radio                                | 2         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth                      | 2         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                       | 2         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 2         | 0.63%   |
| Foxconn / Hon Hai Acer Bluetooth module                | 2         | 0.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 2         | 0.63%   |
| Broadcom HP Portable SoftSailing                       | 2         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth                          | 2         | 0.63%   |
| ASUS BT-270 Bluetooth Adapter                          | 2         | 0.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 2         | 0.63%   |
| Apple Bluetooth USB Host Controller                    | 2         | 0.63%   |
| Realtek RTL8821A Bluetooth                             | 1         | 0.32%   |
| Realtek RTL8723B Bluetooth                             | 1         | 0.32%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 0.32%   |
| Ralink CSR BS8510                                      | 1         | 0.32%   |
| Ralink RT3290 Bluetooth                                | 1         | 0.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                 | 1         | 0.32%   |
| MediaTek BT                                            | 1         | 0.32%   |
| Lite-On Atheros Bluetooth                              | 1         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 0.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 0.32%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 0.32%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 0.32%   |
| Foxconn / Hon Hai BCM20702A0                           | 1         | 0.32%   |
| Foxconn / Hon Hai BCM2045A0                            | 1         | 0.32%   |
| Dell Wireless 365 Bluetooth                            | 1         | 0.32%   |
| Dell Wireless 355 Bluetooth                            | 1         | 0.32%   |
| Dell BCM2046 Bluetooth Device                          | 1         | 0.32%   |
| Broadcom HP Portable Bumble Bee                        | 1         | 0.32%   |
| Broadcom Bluetooth 2.1 Device                          | 1         | 0.32%   |
| Broadcom Bluetooth                                     | 1         | 0.32%   |
| Broadcom BCM2070 Bluetooth 3.0 + HS                    | 1         | 0.32%   |
| ASUS BT-253 Bluetooth Adapter                          | 1         | 0.32%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                  | 1         | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 336       | 68.71%  |
| AMD                   | 60        | 12.27%  |
| Nvidia                | 55        | 11.25%  |
| Realtek Semiconductor | 9         | 1.84%   |
| Lenovo                | 6         | 1.23%   |
| Kingston Technology   | 5         | 1.02%   |
| Logitech              | 4         | 0.82%   |
| GN Netcom             | 2         | 0.41%   |
| Sonicstar             | 1         | 0.2%    |
| Roland                | 1         | 0.2%    |
| ROCCAT                | 1         | 0.2%    |
| Razer USA             | 1         | 0.2%    |
| OLKB                  | 1         | 0.2%    |
| NAD                   | 1         | 0.2%    |
| Mark of the Unicorn   | 1         | 0.2%    |
| Hewlett-Packard       | 1         | 0.2%    |
| Focusrite-Novation    | 1         | 0.2%    |
| Corsair               | 1         | 0.2%    |
| Conexant Systems      | 1         | 0.2%    |
| C-Media Electronics   | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 70        | 11.99%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 5.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 29        | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 4.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 3.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 3.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 3.42%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 3.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 3.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.05%   |
| Realtek Semiconductor USB Audio                                                                   | 9         | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 1.54%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.86%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 4         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.34%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.34%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 0.34%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 2         | 0.34%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 0.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.34%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.34%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.34%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.34%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.34%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.34%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.34%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.34%   |
| Sonicstar Klipsch R-15PM                                                                          | 1         | 0.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 36.93%  |
| SK Hynix            | 63        | 26.14%  |
| Micron Technology   | 31        | 12.86%  |
| Kingston            | 17        | 7.05%   |
| Unknown             | 12        | 4.98%   |
| Elpida              | 8         | 3.32%   |
| Crucial             | 5         | 2.07%   |
| Corsair             | 4         | 1.66%   |
| Ramaxel Technology  | 3         | 1.24%   |
| A-DATA Technology   | 3         | 1.24%   |
| Unknown (ABCD)      | 1         | 0.41%   |
| Transcend           | 1         | 0.41%   |
| Team                | 1         | 0.41%   |
| Nanya Technology    | 1         | 0.41%   |
| ASint Technology    | 1         | 0.41%   |
| 48spaces            | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.98%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 5         | 1.98%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 4         | 1.59%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.59%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 4         | 1.59%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.19%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 1.19%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 3         | 1.19%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 1.19%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 3         | 1.19%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 1.19%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 3         | 1.19%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.19%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 3         | 1.19%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 1.19%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 2         | 0.79%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.79%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.79%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 2         | 0.79%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 2         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.79%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.79%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.79%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 0.79%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 2         | 0.79%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 0.79%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.79%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 2         | 0.79%   |
| Kingston RAM MSI16D3LS1MNG/8G 8GB SODIMM DDR3 1600MT/s              | 2         | 0.79%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.79%   |
| Kingston RAM 9905703-008.A00G 16GB SODIMM DDR4 2667MT/s             | 2         | 0.79%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s               | 2         | 0.79%   |
| Unknown RAM Module 8GB SODIMM LPDDR4 4266MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                    | 1         | 0.4%    |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4266MT/s              | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1866MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM 1066MT/s                           | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.4%    |
| Transcend RAM TS256MSK64V3N 2048MB SODIMM 1066MT/s                  | 1         | 0.4%    |
| Team RAM TEAMGROUP-lnd-2400 4GB SODIMM DDR4 2400MT/s                | 1         | 0.4%    |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 94        | 45.41%  |
| DDR3    | 75        | 36.23%  |
| LPDDR3  | 23        | 11.11%  |
| LPDDR4  | 9         | 4.35%   |
| SDRAM   | 3         | 1.45%   |
| DDR2    | 2         | 0.97%   |
| Unknown | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 170       | 80.95%  |
| Row Of Chips | 30        | 14.29%  |
| Chip         | 8         | 3.81%   |
| Unknown      | 2         | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 82        | 37.61%  |
| 4096  | 81        | 37.16%  |
| 16384 | 36        | 16.51%  |
| 2048  | 15        | 6.88%   |
| 32768 | 4         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 60        | 27.15%  |
| 1600  | 54        | 24.43%  |
| 2133  | 35        | 15.84%  |
| 3200  | 19        | 8.6%    |
| 1867  | 10        | 4.52%   |
| 1334  | 10        | 4.52%   |
| 2400  | 9         | 4.07%   |
| 1333  | 5         | 2.26%   |
| 1067  | 4         | 1.81%   |
| 4267  | 3         | 1.36%   |
| 4199  | 3         | 1.36%   |
| 4266  | 2         | 0.9%    |
| 1066  | 2         | 0.9%    |
| 667   | 2         | 0.9%    |
| 3266  | 1         | 0.45%   |
| 1866  | 1         | 0.45%   |
| 975   | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP Printing Support       | 1         | 25%     |
| HP ENVY Photo 6200 series | 1         | 25%     |
| Brother PT-2450DX         | 1         | 25%     |
| Brother HL-1210W series   | 1         | 25%     |

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
| Chicony Electronics                    | 90        | 24.93%  |
| Acer                                   | 45        | 12.47%  |
| IMC Networks                           | 38        | 10.53%  |
| Microdia                               | 29        | 8.03%   |
| Sunplus Innovation Technology          | 24        | 6.65%   |
| Realtek Semiconductor                  | 18        | 4.99%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 4.99%   |
| Quanta                                 | 16        | 4.43%   |
| Lite-On Technology                     | 16        | 4.43%   |
| Apple                                  | 11        | 3.05%   |
| Lenovo                                 | 10        | 2.77%   |
| Suyin                                  | 9         | 2.49%   |
| Logitech                               | 7         | 1.94%   |
| Samsung Electronics                    | 4         | 1.11%   |
| Primax Electronics                     | 4         | 1.11%   |
| Alcor Micro                            | 4         | 1.11%   |
| Silicon Motion                         | 3         | 0.83%   |
| DJJHFA1BIF5CB0                         | 3         | 0.83%   |
| Ricoh                                  | 2         | 0.55%   |
| Generalplus Technology                 | 2         | 0.55%   |
| ALi                                    | 2         | 0.55%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |
| Syntek                                 | 1         | 0.28%   |
| Mustek Systems                         | 1         | 0.28%   |
| Intel                                  | 1         | 0.28%   |
| Creative Technology                    | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 30        | 8.24%   |
| Microdia Integrated_Webcam_HD                       | 19        | 5.22%   |
| IMC Networks Integrated Camera                      | 12        | 3.3%    |
| Sunplus Integrated_Webcam_HD                        | 10        | 2.75%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 2.75%   |
| Acer Integrated Camera                              | 9         | 2.47%   |
| Lite-On Integrated Camera                           | 8         | 2.2%    |
| Chicony HD Webcam                                   | 8         | 2.2%    |
| Chicony HP HD Webcam                                | 7         | 1.92%   |
| Chicony HP HD Camera                                | 7         | 1.92%   |
| Acer Lenovo EasyCamera                              | 7         | 1.92%   |
| Acer BisonCam, NB Pro                               | 7         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 6         | 1.65%   |
| Sunplus HD WebCam                                   | 5         | 1.37%   |
| Realtek Integrated_Webcam_HD                        | 5         | 1.37%   |
| Lite-On HP HD Camera                                | 5         | 1.37%   |
| Lenovo Integrated Webcam [R5U877]                   | 5         | 1.37%   |
| Chicony Integrated HP HD Webcam                     | 5         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 1.37%   |
| Acer SunplusIT Integrated Camera                    | 5         | 1.37%   |
| Acer Lenovo Integrated Webcam                       | 5         | 1.37%   |
| Samsung Galaxy A5 (MTP)                             | 4         | 1.1%    |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 1.1%    |
| Quanta HD User Facing                               | 4         | 1.1%    |
| Primax HP HD Webcam [Fixed]                         | 4         | 1.1%    |
| Microdia Integrated Webcam                          | 4         | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 1.1%    |
| Quanta HP HD Camera                                 | 3         | 0.82%   |
| Quanta HD Webcam                                    | 3         | 0.82%   |
| Lite-On HP HD Webcam                                | 3         | 0.82%   |
| Lenovo Integrated Webcam                            | 3         | 0.82%   |
| IMC Networks USB camera                             | 3         | 0.82%   |
| DJJHFA1BIF5CB0 HP HD Camera                         | 3         | 0.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 3         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.82%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.82%   |
| Acer EasyCamera                                     | 3         | 0.82%   |
| Sunplus Laptop Integrated Webcam HD                 | 2         | 0.55%   |
| Sunplus ASUS Webcam                                 | 2         | 0.55%   |
| Realtek USB Camera                                  | 2         | 0.55%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 0.55%   |
| Quanta HP Webcam                                    | 2         | 0.55%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.55%   |
| Microdia Dell Integrated HD Webcam                  | 2         | 0.55%   |
| Lenovo UVC Camera                                   | 2         | 0.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 2         | 0.55%   |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.55%   |
| IMC Networks HD Camera                              | 2         | 0.55%   |
| IMC Networks 2M Integrated Webcam                   | 2         | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.55%   |
| Chicony USB2.0 0.3M UVC WebCam                      | 2         | 0.55%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.55%   |
| Chicony Integrated IR Camera                        | 2         | 0.55%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.55%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.55%   |
| Chicony HD User Facing                              | 2         | 0.55%   |
| Chicony CNF9055 Toshiba Webcam                      | 2         | 0.55%   |
| Chicony 1.3M Webcam                                 | 2         | 0.55%   |
| Apple FaceTime HD Camera                            | 2         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 46        | 42.59%  |
| Synaptics                  | 30        | 27.78%  |
| Upek                       | 13        | 12.04%  |
| Shenzhen Goodix Technology | 8         | 7.41%   |
| Elan Microelectronics      | 5         | 4.63%   |
| AuthenTec                  | 3         | 2.78%   |
| LighTuning Technology      | 2         | 1.85%   |
| Samsung Electronics        | 1         | 0.93%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 12.96%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 10.19%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 9.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 6.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 6.48%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.7%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 3.7%    |
| Validity Sensors VFS491                                                    | 3         | 2.78%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.78%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.85%   |
| AuthenTec AES2810                                                          | 2         | 1.85%   |
| Unknown                                                                    | 2         | 1.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.93%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.93%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.93%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.93%   |
| AuthenTec AES1600                                                          | 1         | 0.93%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 18        | 38.3%   |
| Broadcom              | 17        | 36.17%  |
| Upek                  | 7         | 14.89%  |
| Lenovo                | 4         | 8.51%   |
| Gemalto (was Gemplus) | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 38.3%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 14.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 14.89%  |
| Broadcom 5880                                                                | 5         | 10.64%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 8.51%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 6.38%   |
| Broadcom 58200                                                               | 2         | 4.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 218       | 54.36%  |
| 1     | 138       | 34.41%  |
| 2     | 38        | 9.48%   |
| 3     | 7         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 108       | 48%     |
| Chipcard              | 41        | 18.22%  |
| Graphics card         | 36        | 16%     |
| Net/wireless          | 18        | 8%      |
| Multimedia controller | 9         | 4%      |
| Card reader           | 4         | 1.78%   |
| Camera                | 4         | 1.78%   |
| Storage               | 3         | 1.33%   |
| Net/ethernet          | 1         | 0.44%   |
| Bluetooth             | 1         | 0.44%   |
