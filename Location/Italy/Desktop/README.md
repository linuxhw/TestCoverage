Linux in Italy - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 2926

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| HP            | 18E7                        | [57194bb53c](https://linux-hardware.org/?probe=57194bb53c) | May 04, 2022 |
| ASUSTek       | CM6650                      | [d41d1228db](https://linux-hardware.org/?probe=d41d1228db) | May 04, 2022 |
| ASUSTek       | PRIME X370-A                | [4d1f9886c2](https://linux-hardware.org/?probe=4d1f9886c2) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| ASUSTek       | H61M-K                      | [a32313a065](https://linux-hardware.org/?probe=a32313a065) | May 01, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [8d3881574d](https://linux-hardware.org/?probe=8d3881574d) | Apr 30, 2022 |
| HP            | 1494                        | [939f3b7987](https://linux-hardware.org/?probe=939f3b7987) | Apr 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8c1bf73769](https://linux-hardware.org/?probe=8c1bf73769) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ec7e5a0314](https://linux-hardware.org/?probe=ec7e5a0314) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [db3540f085](https://linux-hardware.org/?probe=db3540f085) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| HP            | 1588h                       | [20624367eb](https://linux-hardware.org/?probe=20624367eb) | Apr 27, 2022 |
| HP            | 1588h                       | [831e4e5993](https://linux-hardware.org/?probe=831e4e5993) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [80792ef9d7](https://linux-hardware.org/?probe=80792ef9d7) | Apr 27, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire TC-780               | [501877dba5](https://linux-hardware.org/?probe=501877dba5) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [35975b7d55](https://linux-hardware.org/?probe=35975b7d55) | Apr 25, 2022 |
| ASUSTek       | P8H61-M LX2                 | [a60c0bf48d](https://linux-hardware.org/?probe=a60c0bf48d) | Apr 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| ASUSTek       | P5GD1                       | [11b7aa3465](https://linux-hardware.org/?probe=11b7aa3465) | Apr 24, 2022 |
| HP            | 09F8h                       | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| MSI           | Boston                      | [2f29911ce8](https://linux-hardware.org/?probe=2f29911ce8) | Apr 22, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [30f8dbd98c](https://linux-hardware.org/?probe=30f8dbd98c) | Apr 22, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [179d1e1a0f](https://linux-hardware.org/?probe=179d1e1a0f) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Lenovo        | SDK0E50510 WIN              | [3d829a871e](https://linux-hardware.org/?probe=3d829a871e) | Apr 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [beab5308cb](https://linux-hardware.org/?probe=beab5308cb) | Apr 19, 2022 |
| ASUSTek       | PRIME H510M-A               | [59fb2af2c2](https://linux-hardware.org/?probe=59fb2af2c2) | Apr 18, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [98637b4cf2](https://linux-hardware.org/?probe=98637b4cf2) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0169381aeb](https://linux-hardware.org/?probe=0169381aeb) | Apr 15, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [c3d8900f58](https://linux-hardware.org/?probe=c3d8900f58) | Apr 15, 2022 |
| Dell          | 0HN7XN A01                  | [5a9ba12201](https://linux-hardware.org/?probe=5a9ba12201) | Apr 15, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [36d5c02824](https://linux-hardware.org/?probe=36d5c02824) | Apr 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [7cc9a1bbb7](https://linux-hardware.org/?probe=7cc9a1bbb7) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | A68HM-P33                   | [8c395556de](https://linux-hardware.org/?probe=8c395556de) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [58dab53fb1](https://linux-hardware.org/?probe=58dab53fb1) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [8c2362aa24](https://linux-hardware.org/?probe=8c2362aa24) | Apr 11, 2022 |
| MSI           | Boston                      | [4dd70b97f5](https://linux-hardware.org/?probe=4dd70b97f5) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [14b70a1c77](https://linux-hardware.org/?probe=14b70a1c77) | Apr 10, 2022 |
| ASUSTek       | M2N8L                       | [dc78c18c3f](https://linux-hardware.org/?probe=dc78c18c3f) | Apr 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a56209b0c7](https://linux-hardware.org/?probe=a56209b0c7) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [8d440b5da5](https://linux-hardware.org/?probe=8d440b5da5) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| HP            | 3397                        | [d22ff33b0e](https://linux-hardware.org/?probe=d22ff33b0e) | Apr 08, 2022 |
| Lenovo        | ThinkStation S20 4157WC1    | [d64502fb70](https://linux-hardware.org/?probe=d64502fb70) | Apr 08, 2022 |
| Intel         | STK2MV64CC H89290-502       | [b2cb31c994](https://linux-hardware.org/?probe=b2cb31c994) | Apr 07, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| ASRock        | C2750D4I                    | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASRock        | 970 Extreme4                | [cc65547e82](https://linux-hardware.org/?probe=cc65547e82) | Apr 03, 2022 |
| MSI           | Z590-A PRO                  | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Acer          | Aspire M1920                | [00d3df045a](https://linux-hardware.org/?probe=00d3df045a) | Apr 02, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [3807eeb187](https://linux-hardware.org/?probe=3807eeb187) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| ASUSTek       | A68HM-K                     | [482d5e9c62](https://linux-hardware.org/?probe=482d5e9c62) | Apr 01, 2022 |
| ASRock        | 775Dual-VSTA                | [f5aea8ce64](https://linux-hardware.org/?probe=f5aea8ce64) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [79a7adfb69](https://linux-hardware.org/?probe=79a7adfb69) | Mar 29, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [641cb912c4](https://linux-hardware.org/?probe=641cb912c4) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [5a75a3f121](https://linux-hardware.org/?probe=5a75a3f121) | Mar 29, 2022 |
| ASUSTek       | AM1M-A                      | [29e10859da](https://linux-hardware.org/?probe=29e10859da) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [9688bbdb3f](https://linux-hardware.org/?probe=9688bbdb3f) | Mar 28, 2022 |
| ASUSTek       | H110M-K                     | [4e238835bd](https://linux-hardware.org/?probe=4e238835bd) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [cfd10c0239](https://linux-hardware.org/?probe=cfd10c0239) | Mar 28, 2022 |
| ASRock        | AMCP7AION-HT                | [23f929c975](https://linux-hardware.org/?probe=23f929c975) | Mar 27, 2022 |
| ASUSTek       | H110M-K                     | [14f509aa32](https://linux-hardware.org/?probe=14f509aa32) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [31098e4c80](https://linux-hardware.org/?probe=31098e4c80) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [e4526228cd](https://linux-hardware.org/?probe=e4526228cd) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [402c4d5758](https://linux-hardware.org/?probe=402c4d5758) | Mar 26, 2022 |
| MSI           | IONA                        | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| Gigabyte      | MZBAYAP-D9                  | [2c077e2993](https://linux-hardware.org/?probe=2c077e2993) | Mar 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58cfc7fbae](https://linux-hardware.org/?probe=58cfc7fbae) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [481f4ad619](https://linux-hardware.org/?probe=481f4ad619) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [8ba917619e](https://linux-hardware.org/?probe=8ba917619e) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [48c7f5e6ae](https://linux-hardware.org/?probe=48c7f5e6ae) | Mar 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [73bf7d8080](https://linux-hardware.org/?probe=73bf7d8080) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| HP            | 3397                        | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASRock        | G31M-VS2                    | [129721c7ce](https://linux-hardware.org/?probe=129721c7ce) | Mar 17, 2022 |
| Acer          | EM61SM/EM61PM               | [a33e5dfb8e](https://linux-hardware.org/?probe=a33e5dfb8e) | Mar 17, 2022 |
| Acer          | EM61SM/EM61PM               | [6f3290f91a](https://linux-hardware.org/?probe=6f3290f91a) | Mar 17, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [42ce115c70](https://linux-hardware.org/?probe=42ce115c70) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690-A                | [228a532955](https://linux-hardware.org/?probe=228a532955) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| HP            | ProLiant MicroServer Gen... | [9da39d2356](https://linux-hardware.org/?probe=9da39d2356) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [162abf1031](https://linux-hardware.org/?probe=162abf1031) | Mar 15, 2022 |
| MSI           | Boston                      | [418b80d035](https://linux-hardware.org/?probe=418b80d035) | Mar 14, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [ec5ae37f66](https://linux-hardware.org/?probe=ec5ae37f66) | Mar 14, 2022 |
| Packard Be... | P5N-E SLI                   | [7b991e7fe6](https://linux-hardware.org/?probe=7b991e7fe6) | Mar 14, 2022 |
| Dell          | 0GM819                      | [bf94874639](https://linux-hardware.org/?probe=bf94874639) | Mar 13, 2022 |
| MSI           | B360M MORTAR                | [a00a055108](https://linux-hardware.org/?probe=a00a055108) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| Dell          | 0GM819                      | [acc1399bb2](https://linux-hardware.org/?probe=acc1399bb2) | Mar 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0b912c2834](https://linux-hardware.org/?probe=0b912c2834) | Mar 12, 2022 |
| ASUSTek       | X99-A                       | [4c62821984](https://linux-hardware.org/?probe=4c62821984) | Mar 12, 2022 |
| ECS           | Nettle3                     | [7a96fa9c3f](https://linux-hardware.org/?probe=7a96fa9c3f) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| Acer          | Veriton X2610G              | [1f5f3ecca1](https://linux-hardware.org/?probe=1f5f3ecca1) | Mar 09, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [7d31af4995](https://linux-hardware.org/?probe=7d31af4995) | Mar 08, 2022 |
| HP            | 1497                        | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [8d0b8e2e12](https://linux-hardware.org/?probe=8d0b8e2e12) | Mar 07, 2022 |
| Pegatron      | 2AC3                        | [ea3781cdac](https://linux-hardware.org/?probe=ea3781cdac) | Mar 07, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [bde9b00de4](https://linux-hardware.org/?probe=bde9b00de4) | Mar 07, 2022 |
| ASUSTek       | PRIME H510M-A               | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| MSI           | Z590-A PRO                  | [5f37c84d61](https://linux-hardware.org/?probe=5f37c84d61) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| ASUSTek       | PRIME H510M-A               | [6381e8c673](https://linux-hardware.org/?probe=6381e8c673) | Mar 06, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [a4335990af](https://linux-hardware.org/?probe=a4335990af) | Mar 05, 2022 |
| HP            | 339A                        | [c26acecee2](https://linux-hardware.org/?probe=c26acecee2) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [70405d9cb0](https://linux-hardware.org/?probe=70405d9cb0) | Mar 05, 2022 |
| SiComputer    | Activa Pico                 | [ff99171465](https://linux-hardware.org/?probe=ff99171465) | Mar 05, 2022 |
| Foxconn       | Irvine HP P/N               | [1d37020507](https://linux-hardware.org/?probe=1d37020507) | Mar 03, 2022 |
| Lenovo        | 31900058 STD                | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| Intel         | H61 V1.05                   | [51ad5bd7b7](https://linux-hardware.org/?probe=51ad5bd7b7) | Mar 02, 2022 |
| ASRock        | 990FX Extreme9              | [408514b026](https://linux-hardware.org/?probe=408514b026) | Mar 01, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [e40aac52d8](https://linux-hardware.org/?probe=e40aac52d8) | Feb 28, 2022 |
| HP            | 09F8h                       | [19dc89049d](https://linux-hardware.org/?probe=19dc89049d) | Feb 28, 2022 |
| MSI           | Boston                      | [b5bf0fa044](https://linux-hardware.org/?probe=b5bf0fa044) | Feb 26, 2022 |
| Clientron ... | L700                        | [c2cebca02b](https://linux-hardware.org/?probe=c2cebca02b) | Feb 26, 2022 |
| ASRock        | A75 Extreme6                | [8db778fe6e](https://linux-hardware.org/?probe=8db778fe6e) | Feb 26, 2022 |
| Gigabyte      | F2A88X-D3H                  | [bc86e829a1](https://linux-hardware.org/?probe=bc86e829a1) | Feb 26, 2022 |
| Acer          | Aspire XC-830               | [89acf6268c](https://linux-hardware.org/?probe=89acf6268c) | Feb 25, 2022 |
| MSI           | Boston                      | [f832f5e63a](https://linux-hardware.org/?probe=f832f5e63a) | Feb 24, 2022 |
| Clientron ... | L700                        | [0a16915d4f](https://linux-hardware.org/?probe=0a16915d4f) | Feb 23, 2022 |
| Clientron ... | L700                        | [64f361f774](https://linux-hardware.org/?probe=64f361f774) | Feb 23, 2022 |
| ASRock        | H310M-ITX/ac                | [c5a3dacac5](https://linux-hardware.org/?probe=c5a3dacac5) | Feb 23, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [db5c30632e](https://linux-hardware.org/?probe=db5c30632e) | Feb 22, 2022 |
| MSI           | MAG B460M MORTAR WIFI       | [50536f1318](https://linux-hardware.org/?probe=50536f1318) | Feb 22, 2022 |
| MSI           | MAG B460M MORTAR WIFI       | [b6a9e09f78](https://linux-hardware.org/?probe=b6a9e09f78) | Feb 22, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [286998a230](https://linux-hardware.org/?probe=286998a230) | Feb 22, 2022 |
| ASRock        | X370 Taichi                 | [d4d5aa3b0a](https://linux-hardware.org/?probe=d4d5aa3b0a) | Feb 21, 2022 |
| ASRock        | ALiveNF6P-VSTA              | [eb361d0491](https://linux-hardware.org/?probe=eb361d0491) | Feb 20, 2022 |
| Lenovo        | 3098 0B98401 PRO            | [709ca2add8](https://linux-hardware.org/?probe=709ca2add8) | Feb 20, 2022 |
| Unknown       | Intel X79                   | [7968affda8](https://linux-hardware.org/?probe=7968affda8) | Feb 19, 2022 |
| PROLINE       | ProlinePartner              | [df914c13d7](https://linux-hardware.org/?probe=df914c13d7) | Feb 19, 2022 |
| ASRock        | A320M-HDV                   | [6678e3ba4a](https://linux-hardware.org/?probe=6678e3ba4a) | Feb 18, 2022 |
| ASRock        | A320M-HDV                   | [f37110c1d5](https://linux-hardware.org/?probe=f37110c1d5) | Feb 18, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5a5f32380c](https://linux-hardware.org/?probe=5a5f32380c) | Feb 18, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [3228f18f20](https://linux-hardware.org/?probe=3228f18f20) | Feb 17, 2022 |
| Gigabyte      | H97M-D3H                    | [da5a6a7160](https://linux-hardware.org/?probe=da5a6a7160) | Feb 17, 2022 |
| HP            | 1497                        | [8693cfc8c8](https://linux-hardware.org/?probe=8693cfc8c8) | Feb 17, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [dba2436c5c](https://linux-hardware.org/?probe=dba2436c5c) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| Pegatron      | 2AB6                        | [4659956809](https://linux-hardware.org/?probe=4659956809) | Feb 17, 2022 |
| HP            | 304Ah                       | [8bbd035899](https://linux-hardware.org/?probe=8bbd035899) | Feb 16, 2022 |
| ASRock        | Q1900B-ITX                  | [b205b32b2a](https://linux-hardware.org/?probe=b205b32b2a) | Feb 16, 2022 |
| ASUSTek       | P5QPL-AM                    | [c42862bbdb](https://linux-hardware.org/?probe=c42862bbdb) | Feb 15, 2022 |
| ASUSTek       | P5QPL-AM                    | [185fed2422](https://linux-hardware.org/?probe=185fed2422) | Feb 15, 2022 |
| Unknown       | Intel X79                   | [4073004b50](https://linux-hardware.org/?probe=4073004b50) | Feb 15, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [71ecb0275e](https://linux-hardware.org/?probe=71ecb0275e) | Feb 15, 2022 |
| Gigabyte      | H81M-D2V                    | [283cf4fd8d](https://linux-hardware.org/?probe=283cf4fd8d) | Feb 15, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [b11d43558e](https://linux-hardware.org/?probe=b11d43558e) | Feb 15, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [a2ee2f6a38](https://linux-hardware.org/?probe=a2ee2f6a38) | Feb 15, 2022 |
| ASRock        | 880GMH/USB3                 | [2789041a4d](https://linux-hardware.org/?probe=2789041a4d) | Feb 15, 2022 |
| Acer          | EM61SM/EM61PM               | [f5ed41debc](https://linux-hardware.org/?probe=f5ed41debc) | Feb 14, 2022 |
| YANYU         | H17SL                       | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| BESSTAR Te... | UM270 V1.0                  | [1916cd8623](https://linux-hardware.org/?probe=1916cd8623) | Feb 14, 2022 |
| MSI           | MS-7360                     | [9f4470ea28](https://linux-hardware.org/?probe=9f4470ea28) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | [f1b4a515a3](https://linux-hardware.org/?probe=f1b4a515a3) | Feb 13, 2022 |
| HP            | 339A                        | [05148d7fb4](https://linux-hardware.org/?probe=05148d7fb4) | Feb 13, 2022 |
| Gateway       | SX2865 V1.0                 | [890768bebd](https://linux-hardware.org/?probe=890768bebd) | Feb 12, 2022 |
| HP            | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Dell          | 0KH290                      | [c4684237ef](https://linux-hardware.org/?probe=c4684237ef) | Feb 12, 2022 |
| Unknown       | Unknown                     | [b1ed0635ab](https://linux-hardware.org/?probe=b1ed0635ab) | Feb 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [dec96a3fee](https://linux-hardware.org/?probe=dec96a3fee) | Feb 12, 2022 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51095189f7](https://linux-hardware.org/?probe=51095189f7) | Feb 12, 2022 |
| Acer          | EM61SM/EM61PM               | [8398f79f2a](https://linux-hardware.org/?probe=8398f79f2a) | Feb 12, 2022 |
| ASRock        | A320M-DVS R4.0              | [5356027467](https://linux-hardware.org/?probe=5356027467) | Feb 12, 2022 |
| MSI           | MS-7345                     | [3412e837ef](https://linux-hardware.org/?probe=3412e837ef) | Feb 12, 2022 |
| MSI           | 0A48                        | [29ea38af38](https://linux-hardware.org/?probe=29ea38af38) | Feb 12, 2022 |
| HP            | 304Bh                       | [ee8368a314](https://linux-hardware.org/?probe=ee8368a314) | Feb 11, 2022 |
| Gigabyte      | H170M-HD3 DDR3-CF           | [5503a29249](https://linux-hardware.org/?probe=5503a29249) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| HP            | 2B34                        | [1281e2e4dd](https://linux-hardware.org/?probe=1281e2e4dd) | Feb 10, 2022 |
| Packard Be... | FIH57                       | [d0d43c4388](https://linux-hardware.org/?probe=d0d43c4388) | Feb 10, 2022 |
| HP            | 83E0                        | [12a6ad4f59](https://linux-hardware.org/?probe=12a6ad4f59) | Feb 10, 2022 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [421e056029](https://linux-hardware.org/?probe=421e056029) | Feb 10, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [5afe97188b](https://linux-hardware.org/?probe=5afe97188b) | Feb 10, 2022 |
| ASUSTek       | B150M-K D3                  | [2f698f5683](https://linux-hardware.org/?probe=2f698f5683) | Feb 10, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [0094ddce46](https://linux-hardware.org/?probe=0094ddce46) | Feb 10, 2022 |
| Dell          | 0C27VV A00                  | [4ce2b5c0b9](https://linux-hardware.org/?probe=4ce2b5c0b9) | Feb 09, 2022 |
| ASUSTek       | M4A77TD                     | [7c3ac4c29f](https://linux-hardware.org/?probe=7c3ac4c29f) | Feb 09, 2022 |
| YANYU         | H17SL                       | [9fabebacc4](https://linux-hardware.org/?probe=9fabebacc4) | Feb 09, 2022 |
| Dell          | 0773VG A00                  | [e81f82fd5e](https://linux-hardware.org/?probe=e81f82fd5e) | Feb 09, 2022 |
| ASUSTek       | Rampage Formula             | [2cf0349fbe](https://linux-hardware.org/?probe=2cf0349fbe) | Feb 08, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| Gigabyte      | Z390 UD                     | [523ae21d77](https://linux-hardware.org/?probe=523ae21d77) | Feb 08, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [73da97a50b](https://linux-hardware.org/?probe=73da97a50b) | Feb 07, 2022 |
| YANYU         | H17SL                       | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [4664ace096](https://linux-hardware.org/?probe=4664ace096) | Feb 05, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| ASRock        | J4105M                      | [2f9baf0de0](https://linux-hardware.org/?probe=2f9baf0de0) | Feb 05, 2022 |
| Dell          | 0N826N A03                  | [87c3ec3dac](https://linux-hardware.org/?probe=87c3ec3dac) | Feb 04, 2022 |
| ASUSTek       | Puffer                      | [a0a948ecf5](https://linux-hardware.org/?probe=a0a948ecf5) | Feb 04, 2022 |
| Gigabyte      | P35-DS3L                    | [20541a0b3c](https://linux-hardware.org/?probe=20541a0b3c) | Feb 02, 2022 |
| ASUSTek       | H87M-PRO                    | [0f96c91905](https://linux-hardware.org/?probe=0f96c91905) | Feb 01, 2022 |
| Unknown       | Intel X79                   | [4442c93211](https://linux-hardware.org/?probe=4442c93211) | Jan 31, 2022 |
| ASUSTek       | CM6870                      | [f217244fb2](https://linux-hardware.org/?probe=f217244fb2) | Jan 31, 2022 |
| ASRock        | 890GX Extreme3              | [30d08c4c1f](https://linux-hardware.org/?probe=30d08c4c1f) | Jan 31, 2022 |
| Chuwi         | RZBOX                       | [bea5e134d8](https://linux-hardware.org/?probe=bea5e134d8) | Jan 30, 2022 |
| Gigabyte      | H110M-S2H-CF                | [fe5bd0b5ed](https://linux-hardware.org/?probe=fe5bd0b5ed) | Jan 29, 2022 |
| ASUSTek       | Z170-K                      | [33d0a3b270](https://linux-hardware.org/?probe=33d0a3b270) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek       | Z97-PRO                     | [256f789c6d](https://linux-hardware.org/?probe=256f789c6d) | Jan 27, 2022 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [044e014d11](https://linux-hardware.org/?probe=044e014d11) | Jan 26, 2022 |
| ASUSTek       | H97M-E                      | [5e3573c525](https://linux-hardware.org/?probe=5e3573c525) | Jan 26, 2022 |
| HP            | 1905                        | [d0ef619547](https://linux-hardware.org/?probe=d0ef619547) | Jan 25, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [7f69220928](https://linux-hardware.org/?probe=7f69220928) | Jan 24, 2022 |
| ASUSTek       | H81M-K                      | [6b834ecf57](https://linux-hardware.org/?probe=6b834ecf57) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [cae6b39683](https://linux-hardware.org/?probe=cae6b39683) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [75e0b58fa2](https://linux-hardware.org/?probe=75e0b58fa2) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| ASRock        | AM1B-ITX                    | [5f089eb5bf](https://linux-hardware.org/?probe=5f089eb5bf) | Jan 24, 2022 |
| Acer          | FIH57                       | [af79e42583](https://linux-hardware.org/?probe=af79e42583) | Jan 23, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [ff2dd45add](https://linux-hardware.org/?probe=ff2dd45add) | Jan 21, 2022 |
| ASRock        | H510 Pro BTC+               | [234acd7143](https://linux-hardware.org/?probe=234acd7143) | Jan 21, 2022 |
| Gigabyte      | Z390 UD                     | [cf1efe764d](https://linux-hardware.org/?probe=cf1efe764d) | Jan 21, 2022 |
| ASUSTek       | TUF GAMING B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| Unknown       | HX90                        | [43efcb00a2](https://linux-hardware.org/?probe=43efcb00a2) | Jan 20, 2022 |
| Gigabyte      | B460M D3H                   | [d64f06fd5a](https://linux-hardware.org/?probe=d64f06fd5a) | Jan 20, 2022 |
| Unknown       | HX90                        | [d12701e394](https://linux-hardware.org/?probe=d12701e394) | Jan 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [993543545b](https://linux-hardware.org/?probe=993543545b) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7e0c6ebfc9](https://linux-hardware.org/?probe=7e0c6ebfc9) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [d531de56b2](https://linux-hardware.org/?probe=d531de56b2) | Jan 18, 2022 |
| Gigabyte      | MZBSWBP-00                  | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| ASRock        | H61M-HVS                    | [95bbde94a9](https://linux-hardware.org/?probe=95bbde94a9) | Jan 18, 2022 |
| HP            | 1495                        | [f67a5913e3](https://linux-hardware.org/?probe=f67a5913e3) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| Gigabyte      | Z97M-D3H                    | [dfbc85bafe](https://linux-hardware.org/?probe=dfbc85bafe) | Jan 17, 2022 |
| ASUSTek       | Z87-A                       | [b6d5a58347](https://linux-hardware.org/?probe=b6d5a58347) | Jan 17, 2022 |
| Dell          | 0PP150 A00                  | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Unknown       | K8Upgrade-1689              | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| ASUSTek       | H110-PLUS                   | [baea3e1d59](https://linux-hardware.org/?probe=baea3e1d59) | Jan 13, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| ASRock        | FM2A88M-HD+                 | [2d834a40f5](https://linux-hardware.org/?probe=2d834a40f5) | Jan 10, 2022 |
| Unknown       | RS780-SB700                 | [b5bd3c5c5d](https://linux-hardware.org/?probe=b5bd3c5c5d) | Jan 10, 2022 |
| Unknown       | RS780-SB700                 | [93db27a4d8](https://linux-hardware.org/?probe=93db27a4d8) | Jan 10, 2022 |
| HP            | 09F8h                       | [b17a2aef1b](https://linux-hardware.org/?probe=b17a2aef1b) | Jan 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b431bed91e](https://linux-hardware.org/?probe=b431bed91e) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1ef1dec7bc](https://linux-hardware.org/?probe=1ef1dec7bc) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [cba57c7cfe](https://linux-hardware.org/?probe=cba57c7cfe) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASUSTek       | P5K-E                       | [f3ebd22f2f](https://linux-hardware.org/?probe=f3ebd22f2f) | Jan 08, 2022 |
| ASUSTek       | P8P67 DELUXE                | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| ASUSTek       | H110-PLUS                   | [c3fd3de501](https://linux-hardware.org/?probe=c3fd3de501) | Jan 08, 2022 |
| HP            | 3397                        | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| MSI           | X570-A PRO                  | [8319fcd2fe](https://linux-hardware.org/?probe=8319fcd2fe) | Jan 07, 2022 |
| ASUSTek       | PRIME J4005I-C              | [b73988a1c9](https://linux-hardware.org/?probe=b73988a1c9) | Jan 07, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| Gigabyte      | GA-970A-D3                  | [98280b3f37](https://linux-hardware.org/?probe=98280b3f37) | Jan 04, 2022 |
| Dell          | 0MM599                      | [82532cb19f](https://linux-hardware.org/?probe=82532cb19f) | Jan 03, 2022 |
| ASRock        | G41C-GS                     | [841dc47501](https://linux-hardware.org/?probe=841dc47501) | Jan 01, 2022 |
| ABIT          | AW9D-MAX                    | [104f0e6fde](https://linux-hardware.org/?probe=104f0e6fde) | Jan 01, 2022 |
| HP            | 0AA0h                       | [bf7b3e968e](https://linux-hardware.org/?probe=bf7b3e968e) | Jan 01, 2022 |
| MSI           | 760GM-P23                   | [96ce7a909b](https://linux-hardware.org/?probe=96ce7a909b) | Jan 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | [398a0cf729](https://linux-hardware.org/?probe=398a0cf729) | Dec 30, 2021 |
| ASUSTek       | P8H61                       | [682efb70d7](https://linux-hardware.org/?probe=682efb70d7) | Dec 29, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| HP            | 2AF7                        | [646ae9f001](https://linux-hardware.org/?probe=646ae9f001) | Dec 29, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | CM6870                      | [0a24371b49](https://linux-hardware.org/?probe=0a24371b49) | Dec 27, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [d139e4cfa0](https://linux-hardware.org/?probe=d139e4cfa0) | Dec 27, 2021 |
| MSI           | B450M MORTAR MAX            | [82cd3a640e](https://linux-hardware.org/?probe=82cd3a640e) | Dec 26, 2021 |
| MSI           | B450M MORTAR MAX            | [bcfc2dd514](https://linux-hardware.org/?probe=bcfc2dd514) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [fa1d026542](https://linux-hardware.org/?probe=fa1d026542) | Dec 23, 2021 |
| ASRock        | 970 Extreme4                | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| MSI           | A68HM-P33 V2                | [4b36ec9c1a](https://linux-hardware.org/?probe=4b36ec9c1a) | Dec 23, 2021 |
| ASUSTek       | P5P43TD PRO                 | [6019461793](https://linux-hardware.org/?probe=6019461793) | Dec 22, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [c66f391530](https://linux-hardware.org/?probe=c66f391530) | Dec 22, 2021 |
| ASUSTek       | H97M-PLUS                   | [d81c8e7d01](https://linux-hardware.org/?probe=d81c8e7d01) | Dec 18, 2021 |
| Unknown       | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [92f0b24884](https://linux-hardware.org/?probe=92f0b24884) | Dec 16, 2021 |
| Dell          | 0WR7PY A02                  | [459b162eab](https://linux-hardware.org/?probe=459b162eab) | Dec 16, 2021 |
| ASRock        | X58 Extreme                 | [ac26e59e63](https://linux-hardware.org/?probe=ac26e59e63) | Dec 15, 2021 |
| MSI           | Z97 GUARD-PRO               | [dcc4b73b5c](https://linux-hardware.org/?probe=dcc4b73b5c) | Dec 14, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| HP            | 1495                        | [05cbcf49b8](https://linux-hardware.org/?probe=05cbcf49b8) | Dec 12, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [815ae34e1d](https://linux-hardware.org/?probe=815ae34e1d) | Dec 11, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [aeb068d87a](https://linux-hardware.org/?probe=aeb068d87a) | Dec 11, 2021 |
| ASUSTek       | P6T DELUXE V2               | [def7aa454b](https://linux-hardware.org/?probe=def7aa454b) | Dec 11, 2021 |
| Acer          | Aspire X5950                | [26b0d257ef](https://linux-hardware.org/?probe=26b0d257ef) | Dec 10, 2021 |
| ASRock        | H170A-X1                    | [9e5931fa7d](https://linux-hardware.org/?probe=9e5931fa7d) | Dec 10, 2021 |
| ASUSTek       | Z170M-PLUS                  | [730046deb9](https://linux-hardware.org/?probe=730046deb9) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| Gigabyte      | H77-DS3H                    | [5754691e4b](https://linux-hardware.org/?probe=5754691e4b) | Dec 08, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [160b6097cd](https://linux-hardware.org/?probe=160b6097cd) | Dec 08, 2021 |
| HP            | 8184 X4                     | [3a2d5e3c77](https://linux-hardware.org/?probe=3a2d5e3c77) | Dec 08, 2021 |
| HP            | 8184 X4                     | [e225665abc](https://linux-hardware.org/?probe=e225665abc) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ASRock        | M3A770DE                    | [f0f197bdf8](https://linux-hardware.org/?probe=f0f197bdf8) | Dec 07, 2021 |
| MSI           | Z390-A PRO                  | [f67e3e407c](https://linux-hardware.org/?probe=f67e3e407c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Gigabyte      | H310N x.x                   | [57267d12ff](https://linux-hardware.org/?probe=57267d12ff) | Dec 03, 2021 |
| ASRock        | X58 Extreme                 | [1a9d6547f0](https://linux-hardware.org/?probe=1a9d6547f0) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Unknown       | Intel X79                   | [e1ef0e8dc9](https://linux-hardware.org/?probe=e1ef0e8dc9) | Dec 02, 2021 |
| Unknown       | Intel X79                   | [5e2313b90b](https://linux-hardware.org/?probe=5e2313b90b) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [3439a0acde](https://linux-hardware.org/?probe=3439a0acde) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| ASRock        | G41M-VS3                    | [e2d4b12fef](https://linux-hardware.org/?probe=e2d4b12fef) | Dec 01, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1d6ece4240](https://linux-hardware.org/?probe=1d6ece4240) | Dec 01, 2021 |
| ASRock        | Q1900-ITX                   | [878cd074fb](https://linux-hardware.org/?probe=878cd074fb) | Nov 30, 2021 |
| ASRock        | Q1900-ITX                   | [3468f76ee4](https://linux-hardware.org/?probe=3468f76ee4) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [fe3d4f5bc1](https://linux-hardware.org/?probe=fe3d4f5bc1) | Nov 30, 2021 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | [25d7f6e054](https://linux-hardware.org/?probe=25d7f6e054) | Nov 30, 2021 |
| ASUSTek       | P5QL                        | [70e9ac5d75](https://linux-hardware.org/?probe=70e9ac5d75) | Nov 29, 2021 |
| Dell          | 0XPDFK A00                  | [50d479c71e](https://linux-hardware.org/?probe=50d479c71e) | Nov 29, 2021 |
| Unknown       | Unknown                     | [08926b737d](https://linux-hardware.org/?probe=08926b737d) | Nov 28, 2021 |
| HP            | 8299                        | [105c1751dc](https://linux-hardware.org/?probe=105c1751dc) | Nov 28, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8ffbfad5e8](https://linux-hardware.org/?probe=8ffbfad5e8) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASRock        | H61M-VS                     | [4aefcd6dd3](https://linux-hardware.org/?probe=4aefcd6dd3) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| ASRock        | 970M Pro3                   | [3c1b7aba70](https://linux-hardware.org/?probe=3c1b7aba70) | Nov 26, 2021 |
| Gigabyte      | H77M-D3H                    | [a2606aebd8](https://linux-hardware.org/?probe=a2606aebd8) | Nov 26, 2021 |
| MSI           | B450M-A PRO MAX             | [602d5d0655](https://linux-hardware.org/?probe=602d5d0655) | Nov 26, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| Acer          | EG43M                       | [328e16606e](https://linux-hardware.org/?probe=328e16606e) | Nov 25, 2021 |
| HP            | 8054                        | [28cdc58146](https://linux-hardware.org/?probe=28cdc58146) | Nov 25, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [6a0e22157b](https://linux-hardware.org/?probe=6a0e22157b) | Nov 24, 2021 |
| HP            | 339A                        | [1a13b170eb](https://linux-hardware.org/?probe=1a13b170eb) | Nov 23, 2021 |
| ASRock        | H81M-DGS R2.0               | [138f5b0109](https://linux-hardware.org/?probe=138f5b0109) | Nov 23, 2021 |
| HP            | 1495                        | [6be5bb9489](https://linux-hardware.org/?probe=6be5bb9489) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| HP            | 1495                        | [f52ded8998](https://linux-hardware.org/?probe=f52ded8998) | Nov 20, 2021 |
| Lenovo        | ThinkServer TS140           | [da5af2478e](https://linux-hardware.org/?probe=da5af2478e) | Nov 20, 2021 |
| ASUSTek       | PRIME H510M-K               | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| HP            | 3047h                       | [a8b27aa212](https://linux-hardware.org/?probe=a8b27aa212) | Nov 20, 2021 |
| HP            | 304Ah                       | [988e1e374a](https://linux-hardware.org/?probe=988e1e374a) | Nov 18, 2021 |
| HP            | 1494                        | [a1e8628159](https://linux-hardware.org/?probe=a1e8628159) | Nov 17, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [246e62e738](https://linux-hardware.org/?probe=246e62e738) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| ASRock        | B450M Pro4                  | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [71342b9603](https://linux-hardware.org/?probe=71342b9603) | Nov 14, 2021 |
| ASUSTek       | M4A77TD PRO                 | [fadecb8927](https://linux-hardware.org/?probe=fadecb8927) | Nov 14, 2021 |
| HP            | 1495                        | [5fd0d39362](https://linux-hardware.org/?probe=5fd0d39362) | Nov 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ae75212ce](https://linux-hardware.org/?probe=7ae75212ce) | Nov 13, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [5d283e7da8](https://linux-hardware.org/?probe=5d283e7da8) | Nov 13, 2021 |
| ASUSTek       | TUF GAMING B560M-PLUS WI... | [f609e8c701](https://linux-hardware.org/?probe=f609e8c701) | Nov 12, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [a13e2b71e5](https://linux-hardware.org/?probe=a13e2b71e5) | Nov 12, 2021 |
| ASUSTek       | M4N78-AM                    | [33e5f6918d](https://linux-hardware.org/?probe=33e5f6918d) | Nov 11, 2021 |
| ASUSTek       | P5KPL-CM                    | [e89b41000d](https://linux-hardware.org/?probe=e89b41000d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| ASUSTek       | Maximus V EXTREME           | [c0aa47a4a3](https://linux-hardware.org/?probe=c0aa47a4a3) | Nov 09, 2021 |
| ASUSTek       | H81M-K                      | [e2c43ab9cf](https://linux-hardware.org/?probe=e2c43ab9cf) | Nov 08, 2021 |
| Gigabyte      | Z77X-UD5H                   | [85d8ecd997](https://linux-hardware.org/?probe=85d8ecd997) | Nov 08, 2021 |
| Gigabyte      | Z77X-UD5H                   | [be0d9a92af](https://linux-hardware.org/?probe=be0d9a92af) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| ASRock        | B450M Pro4                  | [4138b9cffa](https://linux-hardware.org/?probe=4138b9cffa) | Nov 08, 2021 |
| ASUSTek       | H81M-C                      | [09306240c7](https://linux-hardware.org/?probe=09306240c7) | Nov 07, 2021 |
| ASUSTek       | H81M-C                      | [707a5aa817](https://linux-hardware.org/?probe=707a5aa817) | Nov 07, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [914d585adc](https://linux-hardware.org/?probe=914d585adc) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| ASUSTek       | P5LD2                       | [7fd427c196](https://linux-hardware.org/?probe=7fd427c196) | Nov 06, 2021 |
| ASUSTek       | P9X79                       | [062b1aa83d](https://linux-hardware.org/?probe=062b1aa83d) | Nov 04, 2021 |
| Gigabyte      | 945GZM-S2                   | [df920d0ad1](https://linux-hardware.org/?probe=df920d0ad1) | Nov 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f8baadef0e](https://linux-hardware.org/?probe=f8baadef0e) | Nov 03, 2021 |
| MSI           | Z97 GAMING 3                | [75a7ea92de](https://linux-hardware.org/?probe=75a7ea92de) | Nov 03, 2021 |
| ASRock        | H81M-VG4 R2.0               | [57bd551a7e](https://linux-hardware.org/?probe=57bd551a7e) | Nov 02, 2021 |
| Lenovo        | MAHOBAY                     | [75dba94995](https://linux-hardware.org/?probe=75dba94995) | Nov 01, 2021 |
| MSI           | X58 Pro                     | [e37a1a6dd3](https://linux-hardware.org/?probe=e37a1a6dd3) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [74ac661b7e](https://linux-hardware.org/?probe=74ac661b7e) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [63d574bb8a](https://linux-hardware.org/?probe=63d574bb8a) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [3067e726ce](https://linux-hardware.org/?probe=3067e726ce) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [d8d613566e](https://linux-hardware.org/?probe=d8d613566e) | Nov 01, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce74345bf7](https://linux-hardware.org/?probe=ce74345bf7) | Nov 01, 2021 |
| HP            | 339A                        | [8dc56deebb](https://linux-hardware.org/?probe=8dc56deebb) | Nov 01, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [f8a7da7b89](https://linux-hardware.org/?probe=f8a7da7b89) | Nov 01, 2021 |
| ASRock        | B450M Pro4                  | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| Gigabyte      | G31M-ES2L                   | [23b6458508](https://linux-hardware.org/?probe=23b6458508) | Oct 30, 2021 |
| ASUSTek       | SABERTOOTH X79              | [0c14ffd402](https://linux-hardware.org/?probe=0c14ffd402) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [89c1a7f472](https://linux-hardware.org/?probe=89c1a7f472) | Oct 28, 2021 |
| Unknown       | T3 MRD                      | [033fe23df1](https://linux-hardware.org/?probe=033fe23df1) | Oct 28, 2021 |
| ASUSTek       | CM6870                      | [1575e2c682](https://linux-hardware.org/?probe=1575e2c682) | Oct 28, 2021 |
| ASRock        | H110 Pro BTC+               | [6b4c3f811b](https://linux-hardware.org/?probe=6b4c3f811b) | Oct 27, 2021 |
| MSI           | GF615M-P33                  | [79851e843c](https://linux-hardware.org/?probe=79851e843c) | Oct 27, 2021 |
| MSI           | X570-A PRO                  | [6ce1beb282](https://linux-hardware.org/?probe=6ce1beb282) | Oct 26, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [c7b95d7362](https://linux-hardware.org/?probe=c7b95d7362) | Oct 26, 2021 |
| ASUSTek       | PRIME Z370-A                | [b87a3ed6f4](https://linux-hardware.org/?probe=b87a3ed6f4) | Oct 25, 2021 |
| MSI           | B450M-A PRO MAX             | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | Leonite2                    | [6c12f8eadc](https://linux-hardware.org/?probe=6c12f8eadc) | Oct 23, 2021 |
| Acer          | Aspire TC-281               | [5114976821](https://linux-hardware.org/?probe=5114976821) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [6e3084cf7f](https://linux-hardware.org/?probe=6e3084cf7f) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [c1808f5d2f](https://linux-hardware.org/?probe=c1808f5d2f) | Oct 23, 2021 |
| ASUSTek       | P5Q                         | [3291b34601](https://linux-hardware.org/?probe=3291b34601) | Oct 23, 2021 |
| ASRock        | B365M Pro4                  | [ec939fb289](https://linux-hardware.org/?probe=ec939fb289) | Oct 20, 2021 |
| Lenovo        | ThinkCentre M58p 6137A1G    | [ed1d55e70a](https://linux-hardware.org/?probe=ed1d55e70a) | Oct 19, 2021 |
| MSI           | Boston                      | [16b390163e](https://linux-hardware.org/?probe=16b390163e) | Oct 18, 2021 |
| Gigabyte      | H310M H                     | [c8106b6a92](https://linux-hardware.org/?probe=c8106b6a92) | Oct 18, 2021 |
| Lenovo        | ThinkCentre M58p 6137A1G    | [7d9fb13a94](https://linux-hardware.org/?probe=7d9fb13a94) | Oct 18, 2021 |
| Gigabyte      | Z77X-UD5H                   | [dd8ce106ae](https://linux-hardware.org/?probe=dd8ce106ae) | Oct 17, 2021 |
| MSI           | Z77A-G45                    | [3d516c23c5](https://linux-hardware.org/?probe=3d516c23c5) | Oct 17, 2021 |
| ASUSTek       | PRIME H270-PRO              | [4e41f87995](https://linux-hardware.org/?probe=4e41f87995) | Oct 16, 2021 |
| ASUSTek       | Z170-A                      | [d3e0e0f937](https://linux-hardware.org/?probe=d3e0e0f937) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [8b50d81590](https://linux-hardware.org/?probe=8b50d81590) | Oct 16, 2021 |
| MSI           | X58 Pro                     | [83bc2fb756](https://linux-hardware.org/?probe=83bc2fb756) | Oct 15, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [6e15fcad52](https://linux-hardware.org/?probe=6e15fcad52) | Oct 15, 2021 |
| MSI           | Boston                      | [4ec59b6358](https://linux-hardware.org/?probe=4ec59b6358) | Oct 15, 2021 |
| ASRock        | FM2A68M-HD+                 | [3f95ddf15a](https://linux-hardware.org/?probe=3f95ddf15a) | Oct 15, 2021 |
| ASUSTek       | P5K PRO                     | [77b7d82f05](https://linux-hardware.org/?probe=77b7d82f05) | Oct 15, 2021 |
| ASRock        | G41C-GS                     | [7b91f52e83](https://linux-hardware.org/?probe=7b91f52e83) | Oct 14, 2021 |
| Pegatron      | 2AB6                        | [903bb1752e](https://linux-hardware.org/?probe=903bb1752e) | Oct 14, 2021 |
| ASRock        | FM2A68M-HD+                 | [f192680213](https://linux-hardware.org/?probe=f192680213) | Oct 14, 2021 |
| Dell          | 0MN1TX A02                  | [f107638d6e](https://linux-hardware.org/?probe=f107638d6e) | Oct 14, 2021 |
| ASUSTek       | Basswood                    | [eab83905be](https://linux-hardware.org/?probe=eab83905be) | Oct 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [294d1f6a89](https://linux-hardware.org/?probe=294d1f6a89) | Oct 13, 2021 |
| ASUSTek       | Basswood                    | [509df39bec](https://linux-hardware.org/?probe=509df39bec) | Oct 13, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [5964c48c2c](https://linux-hardware.org/?probe=5964c48c2c) | Oct 12, 2021 |
| MSI           | B450M-A PRO MAX             | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| ASRock        | P4VM8                       | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| MSI           | MEG X570 UNIFY              | [4d49755fc4](https://linux-hardware.org/?probe=4d49755fc4) | Oct 10, 2021 |
| ASRock        | P4VM8                       | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| Packard Be... | IMEDIA S3712                | [769a6a4900](https://linux-hardware.org/?probe=769a6a4900) | Oct 09, 2021 |
| ASUSTek       | M4N78-AM                    | [9005621271](https://linux-hardware.org/?probe=9005621271) | Oct 08, 2021 |
| Unknown       | Unknown                     | [54642e6ee3](https://linux-hardware.org/?probe=54642e6ee3) | Oct 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [990facb027](https://linux-hardware.org/?probe=990facb027) | Oct 06, 2021 |
| ASRock        | 775Dual-VSTA                | [6df28d7ea1](https://linux-hardware.org/?probe=6df28d7ea1) | Oct 06, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [182591a045](https://linux-hardware.org/?probe=182591a045) | Oct 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [323303e8a2](https://linux-hardware.org/?probe=323303e8a2) | Oct 04, 2021 |
| Intel         | DQ57TM AAE70931-403         | [bf6d27f32d](https://linux-hardware.org/?probe=bf6d27f32d) | Oct 04, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [f89ce83c89](https://linux-hardware.org/?probe=f89ce83c89) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [f72bc27861](https://linux-hardware.org/?probe=f72bc27861) | Oct 03, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [5904ce7230](https://linux-hardware.org/?probe=5904ce7230) | Oct 03, 2021 |
| ASUSTek       | P5K-VM                      | [04c2c920fe](https://linux-hardware.org/?probe=04c2c920fe) | Oct 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [2f27c4c6f0](https://linux-hardware.org/?probe=2f27c4c6f0) | Sep 29, 2021 |
| ASRock        | FM2A55M-HD+                 | [ebdbd50dcb](https://linux-hardware.org/?probe=ebdbd50dcb) | Sep 28, 2021 |
| Dell          | 0D24M8 A01                  | [f1f58938d1](https://linux-hardware.org/?probe=f1f58938d1) | Sep 27, 2021 |
| ASRock        | X300M-STX                   | [800d0584ad](https://linux-hardware.org/?probe=800d0584ad) | Sep 27, 2021 |
| ASUSTek       | PRIME X470-PRO              | [85925128ef](https://linux-hardware.org/?probe=85925128ef) | Sep 27, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [fcb09a46a1](https://linux-hardware.org/?probe=fcb09a46a1) | Sep 27, 2021 |
| Gigabyte      | Z97X-UD5H                   | [86a2ff019c](https://linux-hardware.org/?probe=86a2ff019c) | Sep 26, 2021 |
| ASUSTek       | TUF GAMING H570-PRO         | [97c090583f](https://linux-hardware.org/?probe=97c090583f) | Sep 26, 2021 |
| Foxconn       | 2ABF                        | [c18c7a80c7](https://linux-hardware.org/?probe=c18c7a80c7) | Sep 26, 2021 |
| ASUSTek       | P5K SE/EPU                  | [df44856137](https://linux-hardware.org/?probe=df44856137) | Sep 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [469a7b17fa](https://linux-hardware.org/?probe=469a7b17fa) | Sep 25, 2021 |
| ASRock        | 775VM800                    | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| Acer          | H57M01                      | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | Z77-DS3H                    | [40468f1cff](https://linux-hardware.org/?probe=40468f1cff) | Sep 23, 2021 |
| HP            | 0AA8h                       | [b702f1c3a2](https://linux-hardware.org/?probe=b702f1c3a2) | Sep 23, 2021 |
| ASUSTek       | SABERTOOTH X58              | [5947903d48](https://linux-hardware.org/?probe=5947903d48) | Sep 23, 2021 |
| HP            | 21F5                        | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| ASUSTek       | Z87-C                       | [2ca018510e](https://linux-hardware.org/?probe=2ca018510e) | Sep 22, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [5172a1a665](https://linux-hardware.org/?probe=5172a1a665) | Sep 22, 2021 |
| HP            | 0AA8h                       | [27262b41aa](https://linux-hardware.org/?probe=27262b41aa) | Sep 22, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [b44b19f051](https://linux-hardware.org/?probe=b44b19f051) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [a5211dc1bb](https://linux-hardware.org/?probe=a5211dc1bb) | Sep 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Acer          | FIH57                       | [af740ea4c9](https://linux-hardware.org/?probe=af740ea4c9) | Sep 18, 2021 |
| Acer          | FIH57                       | [1f486783b8](https://linux-hardware.org/?probe=1f486783b8) | Sep 18, 2021 |
| ASUSTek       | PRIME X570-P                | [3ef71721e0](https://linux-hardware.org/?probe=3ef71721e0) | Sep 16, 2021 |
| ASRock        | N68C-S UCC                  | [a44caf0bdc](https://linux-hardware.org/?probe=a44caf0bdc) | Sep 13, 2021 |
| Intel         | DQ57TM AAE70931-403         | [fca25108b4](https://linux-hardware.org/?probe=fca25108b4) | Sep 12, 2021 |
| MSI           | Z170A GAMING M7             | [7e104e0d59](https://linux-hardware.org/?probe=7e104e0d59) | Sep 12, 2021 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [1b82d2d167](https://linux-hardware.org/?probe=1b82d2d167) | Sep 12, 2021 |
| ASRock        | H87 Pro4                    | [2dc902069e](https://linux-hardware.org/?probe=2dc902069e) | Sep 11, 2021 |
| ASRock        | Z77 Extreme4                | [4e164a0a47](https://linux-hardware.org/?probe=4e164a0a47) | Sep 11, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [4e38c7976d](https://linux-hardware.org/?probe=4e38c7976d) | Sep 11, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [bbfc6ac323](https://linux-hardware.org/?probe=bbfc6ac323) | Sep 10, 2021 |
| ASRock        | A75M-HVS                    | [865936d9fc](https://linux-hardware.org/?probe=865936d9fc) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5ccce57d3f](https://linux-hardware.org/?probe=5ccce57d3f) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4b7b87adc3](https://linux-hardware.org/?probe=4b7b87adc3) | Sep 08, 2021 |
| Intel         | DQ57TM AAE70931-403         | [6add940021](https://linux-hardware.org/?probe=6add940021) | Sep 07, 2021 |
| Dell          | 033FF6 A00                  | [9b0b45b6fb](https://linux-hardware.org/?probe=9b0b45b6fb) | Sep 06, 2021 |
| ASUSTek       | Z87-C                       | [d12600995f](https://linux-hardware.org/?probe=d12600995f) | Sep 06, 2021 |
| ASRock        | H170 Pro4                   | [9f587f8b51](https://linux-hardware.org/?probe=9f587f8b51) | Sep 06, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [10f34cd263](https://linux-hardware.org/?probe=10f34cd263) | Sep 05, 2021 |
| Dell          | 08HPGT A01                  | [eea1f6e691](https://linux-hardware.org/?probe=eea1f6e691) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| MSI           | Z170A GAMING M7             | [439d21f863](https://linux-hardware.org/?probe=439d21f863) | Sep 04, 2021 |
| Pegatron      | Maureen                     | [c5ab105ead](https://linux-hardware.org/?probe=c5ab105ead) | Sep 04, 2021 |
| Gigabyte      | AX370M-Gaming 3-CF          | [393846cf6c](https://linux-hardware.org/?probe=393846cf6c) | Sep 03, 2021 |
| Gigabyte      | AX370M-Gaming 3-CF          | [02edd5f25e](https://linux-hardware.org/?probe=02edd5f25e) | Sep 03, 2021 |
| Pegatron      | Maureen                     | [8591d54048](https://linux-hardware.org/?probe=8591d54048) | Sep 03, 2021 |
| ASRock        | 970M Pro3                   | [3931271e02](https://linux-hardware.org/?probe=3931271e02) | Sep 02, 2021 |
| ASRock        | 970M Pro3                   | [a3e28f8cc9](https://linux-hardware.org/?probe=a3e28f8cc9) | Sep 02, 2021 |
| MSI           | A75A-G55                    | [eb17249857](https://linux-hardware.org/?probe=eb17249857) | Sep 02, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c3354f8b3d](https://linux-hardware.org/?probe=c3354f8b3d) | Sep 02, 2021 |
| ASUSTek       | Puffer                      | [5019322121](https://linux-hardware.org/?probe=5019322121) | Sep 01, 2021 |
| ASUSTek       | Puffer                      | [b4ab7c9946](https://linux-hardware.org/?probe=b4ab7c9946) | Sep 01, 2021 |
| ASUSTek       | Z87-K                       | [286d6314d1](https://linux-hardware.org/?probe=286d6314d1) | Sep 01, 2021 |
| ASUSTek       | P5N-MX                      | [f748ee1490](https://linux-hardware.org/?probe=f748ee1490) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| Dell          | 0TDG4V A01                  | [d41deb84bf](https://linux-hardware.org/?probe=d41deb84bf) | Aug 30, 2021 |
| MSI           | 2A78h                       | [2fbe95f312](https://linux-hardware.org/?probe=2fbe95f312) | Aug 29, 2021 |
| MSI           | 2A78h                       | [b39690d456](https://linux-hardware.org/?probe=b39690d456) | Aug 29, 2021 |
| ASUSTek       | P8Z77-V                     | [b763e20e1f](https://linux-hardware.org/?probe=b763e20e1f) | Aug 27, 2021 |
| Intel         | DH67BL AAG10189-206         | [cf6543044c](https://linux-hardware.org/?probe=cf6543044c) | Aug 25, 2021 |
| Intel         | DH67BL AAG10189-206         | [67f7ee5fde](https://linux-hardware.org/?probe=67f7ee5fde) | Aug 25, 2021 |
| MSI           | B550-A PRO                  | [f06e43a572](https://linux-hardware.org/?probe=f06e43a572) | Aug 25, 2021 |
| ASRock        | FM2A88X-ITX+                | [3fc477b58a](https://linux-hardware.org/?probe=3fc477b58a) | Aug 24, 2021 |
| Gigabyte      | H77-DS3H                    | [de1a6ba085](https://linux-hardware.org/?probe=de1a6ba085) | Aug 24, 2021 |
| Dell          | 0D28YY A01                  | [343f1e9cf8](https://linux-hardware.org/?probe=343f1e9cf8) | Aug 24, 2021 |
| ASRock        | Q77M vPro                   | [f53a9f288f](https://linux-hardware.org/?probe=f53a9f288f) | Aug 24, 2021 |
| MSI           | MS-7142                     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| ASUSTek       | M2N-E SLI                   | [149d762d08](https://linux-hardware.org/?probe=149d762d08) | Aug 20, 2021 |
| Dell          | 0KV62T A00                  | [d7fd97ec39](https://linux-hardware.org/?probe=d7fd97ec39) | Aug 20, 2021 |
| Pegatron      | 2A94                        | [89f32c6f1d](https://linux-hardware.org/?probe=89f32c6f1d) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [4c1a100ab1](https://linux-hardware.org/?probe=4c1a100ab1) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | [810f986c77](https://linux-hardware.org/?probe=810f986c77) | Aug 19, 2021 |
| NEC Comput... | GA-8TRC410M-NF              | [e2215fc750](https://linux-hardware.org/?probe=e2215fc750) | Aug 18, 2021 |
| NEC Comput... | GA-8TRC410M-NF              | [552abea580](https://linux-hardware.org/?probe=552abea580) | Aug 18, 2021 |
| ASUSTek       | P7P55D-E                    | [14baafdcc0](https://linux-hardware.org/?probe=14baafdcc0) | Aug 18, 2021 |
| Foxconn       | 946 7MA Series              | [09da5fab45](https://linux-hardware.org/?probe=09da5fab45) | Aug 17, 2021 |
| MSI           | 2AE0                        | [ee9bcaef5f](https://linux-hardware.org/?probe=ee9bcaef5f) | Aug 17, 2021 |
| ASUSTek       | PRIME B360M-K               | [8a77b11785](https://linux-hardware.org/?probe=8a77b11785) | Aug 15, 2021 |
| ASUSTek       | PRIME B365M-A               | [0aabfbb3fd](https://linux-hardware.org/?probe=0aabfbb3fd) | Aug 14, 2021 |
| HP            | 8653 A                      | [7ba975c504](https://linux-hardware.org/?probe=7ba975c504) | Aug 13, 2021 |
| Dell          | 0WR7PY A02                  | [3e13aec14c](https://linux-hardware.org/?probe=3e13aec14c) | Aug 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [02f3303081](https://linux-hardware.org/?probe=02f3303081) | Aug 12, 2021 |
| Intel         | DX38BT AAD85848-503         | [d9ea2aa414](https://linux-hardware.org/?probe=d9ea2aa414) | Aug 12, 2021 |
| Dell          | 0C27VV A01                  | [4a0484868d](https://linux-hardware.org/?probe=4a0484868d) | Aug 11, 2021 |
| Intel         | DX38BT AAD85848-503         | [9495ca3432](https://linux-hardware.org/?probe=9495ca3432) | Aug 09, 2021 |
| ASUSTek       | H97-PLUS                    | [e37b36a31b](https://linux-hardware.org/?probe=e37b36a31b) | Aug 06, 2021 |
| Alienware     | 046MHW A00                  | [15eb46f84e](https://linux-hardware.org/?probe=15eb46f84e) | Aug 06, 2021 |
| Foxconn       | 2ABF                        | [5407e26d8d](https://linux-hardware.org/?probe=5407e26d8d) | Aug 05, 2021 |
| Unknown       | Intel X79                   | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| ASUSTek       | P5Q SE PLUS                 | [4bde9c26aa](https://linux-hardware.org/?probe=4bde9c26aa) | Aug 04, 2021 |
| Pegatron      | 2A94                        | [02959528ba](https://linux-hardware.org/?probe=02959528ba) | Aug 04, 2021 |
| MSI           | Z170A KRAIT GAMING          | [58edc5351f](https://linux-hardware.org/?probe=58edc5351f) | Aug 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [95bc356b41](https://linux-hardware.org/?probe=95bc356b41) | Aug 03, 2021 |
| Gigabyte      | H77-DS3H                    | [54fc7d3a23](https://linux-hardware.org/?probe=54fc7d3a23) | Aug 03, 2021 |
| Pegatron      | 2A94                        | [f8aa38fd3c](https://linux-hardware.org/?probe=f8aa38fd3c) | Aug 03, 2021 |
| Acer          | FQ965M                      | [3b458ed3ee](https://linux-hardware.org/?probe=3b458ed3ee) | Aug 01, 2021 |
| ASUSTek       | H81M-PLUS                   | [02f7a21c31](https://linux-hardware.org/?probe=02f7a21c31) | Jul 29, 2021 |
| Intel         | DP67DE AAG10217-300         | [e5f06ddd1f](https://linux-hardware.org/?probe=e5f06ddd1f) | Jul 29, 2021 |
| ASUSTek       | H170-PRO                    | [39486efb08](https://linux-hardware.org/?probe=39486efb08) | Jul 29, 2021 |
| ASUSTek       | P8H61-M LX2                 | [678c76b2b6](https://linux-hardware.org/?probe=678c76b2b6) | Jul 27, 2021 |
| Shuttle       | FDX30                       | [4032fc8496](https://linux-hardware.org/?probe=4032fc8496) | Jul 27, 2021 |
| Shuttle       | FL10J                       | [0f9fb196fb](https://linux-hardware.org/?probe=0f9fb196fb) | Jul 27, 2021 |
| ASUSTek       | Z87-C                       | [02864b35ef](https://linux-hardware.org/?probe=02864b35ef) | Jul 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [02dad54406](https://linux-hardware.org/?probe=02dad54406) | Jul 25, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [deeb6b1a2f](https://linux-hardware.org/?probe=deeb6b1a2f) | Jul 25, 2021 |
| MSI           | Z490-A PRO                  | [740f322568](https://linux-hardware.org/?probe=740f322568) | Jul 25, 2021 |
| ASUSTek       | PRIME H310T2 R2.0           | [0ea7ca0a7e](https://linux-hardware.org/?probe=0ea7ca0a7e) | Jul 24, 2021 |
| Dell          | 0D24M8 A01                  | [2080a71bc0](https://linux-hardware.org/?probe=2080a71bc0) | Jul 24, 2021 |
| YANYU         | ITX-M51_D2L baytrail        | [92dcf334a1](https://linux-hardware.org/?probe=92dcf334a1) | Jul 21, 2021 |
| HP            | 0A1Ch E                     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [0f6b60cc29](https://linux-hardware.org/?probe=0f6b60cc29) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | [704aa27146](https://linux-hardware.org/?probe=704aa27146) | Jul 19, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [788a713bdd](https://linux-hardware.org/?probe=788a713bdd) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [d2f11dc136](https://linux-hardware.org/?probe=d2f11dc136) | Jul 18, 2021 |
| Huanan        | Board                       | [d7a6661942](https://linux-hardware.org/?probe=d7a6661942) | Jul 17, 2021 |
| Huanan        | Board                       | [2c4a829d6f](https://linux-hardware.org/?probe=2c4a829d6f) | Jul 17, 2021 |
| ASUSTek       | Z97-PRO                     | [20baa30b1c](https://linux-hardware.org/?probe=20baa30b1c) | Jul 16, 2021 |
| HP            | 8653 A                      | [0871d86f09](https://linux-hardware.org/?probe=0871d86f09) | Jul 16, 2021 |
| Dell          | 0KV62T A00                  | [82819ad99c](https://linux-hardware.org/?probe=82819ad99c) | Jul 15, 2021 |
| HP            | 8653 A                      | [458b24e30d](https://linux-hardware.org/?probe=458b24e30d) | Jul 15, 2021 |
| ASUSTek       | P7P55D PREMIUM              | [fdc5878250](https://linux-hardware.org/?probe=fdc5878250) | Jul 14, 2021 |
| MSI           | Z170A GAMING M7             | [6efd63dc8b](https://linux-hardware.org/?probe=6efd63dc8b) | Jul 13, 2021 |
| SYWZ          | S200 Series                 | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Gigabyte      | X570 AORUS PRO              | [4108591a0b](https://linux-hardware.org/?probe=4108591a0b) | Jul 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [ff86957404](https://linux-hardware.org/?probe=ff86957404) | Jul 09, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [ff3d4c04a4](https://linux-hardware.org/?probe=ff3d4c04a4) | Jul 08, 2021 |
| HP            | 3646h                       | [fb103b4efb](https://linux-hardware.org/?probe=fb103b4efb) | Jul 08, 2021 |
| ASUSTek       | M5A78L-M LX                 | [2762e93602](https://linux-hardware.org/?probe=2762e93602) | Jul 07, 2021 |
| Gigabyte      | X299 UD4 Pro-CF             | [d68d953aae](https://linux-hardware.org/?probe=d68d953aae) | Jul 07, 2021 |
| MSI           | Z490-A PRO                  | [9a7f6c3cc6](https://linux-hardware.org/?probe=9a7f6c3cc6) | Jul 06, 2021 |
| Gigabyte      | X299 UD4 Pro-CF             | [6f5d0598c3](https://linux-hardware.org/?probe=6f5d0598c3) | Jul 06, 2021 |
| Intel         | DQ57TM AAE70931-402         | [cde4ef6ebf](https://linux-hardware.org/?probe=cde4ef6ebf) | Jul 05, 2021 |
| MSI           | B360M BAZOOKA               | [383e335ebb](https://linux-hardware.org/?probe=383e335ebb) | Jul 05, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [b37f10ecef](https://linux-hardware.org/?probe=b37f10ecef) | Jul 05, 2021 |
| Intel         | DQ77MK AAG39642-500         | [4b6753e3b4](https://linux-hardware.org/?probe=4b6753e3b4) | Jul 04, 2021 |
| ASUSTek       | Berkeley                    | [339fe7d7de](https://linux-hardware.org/?probe=339fe7d7de) | Jul 04, 2021 |
| ASUSTek       | Berkeley                    | [d777062dd1](https://linux-hardware.org/?probe=d777062dd1) | Jul 04, 2021 |
| MSI           | G41M-P33                    | [8bc3bbf743](https://linux-hardware.org/?probe=8bc3bbf743) | Jul 04, 2021 |
| ASUSTek       | P5K                         | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| MSI           | B450M PRO-VDH PLUS          | [2cbbf71a66](https://linux-hardware.org/?probe=2cbbf71a66) | Jul 02, 2021 |
| MSI           | MEG X570 ACE                | [ad5fb0116a](https://linux-hardware.org/?probe=ad5fb0116a) | Jul 02, 2021 |
| Pegatron      | VIOLET                      | [3a69706315](https://linux-hardware.org/?probe=3a69706315) | Jul 02, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [ac7bf0575f](https://linux-hardware.org/?probe=ac7bf0575f) | Jul 01, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [9a6e18e56a](https://linux-hardware.org/?probe=9a6e18e56a) | Jul 01, 2021 |
| ASUSTek       | P8B75-M LX                  | [887c8ea2af](https://linux-hardware.org/?probe=887c8ea2af) | Jul 01, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [d56325b68b](https://linux-hardware.org/?probe=d56325b68b) | Jun 30, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [01a3fb2374](https://linux-hardware.org/?probe=01a3fb2374) | Jun 30, 2021 |
| MSI           | Z77A-G43                    | [072048636a](https://linux-hardware.org/?probe=072048636a) | Jun 29, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [a2398ab2d4](https://linux-hardware.org/?probe=a2398ab2d4) | Jun 29, 2021 |
| ASUSTek       | PRIME B460M-A               | [2edcde427c](https://linux-hardware.org/?probe=2edcde427c) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| HP            | 8750                        | [86cf510b70](https://linux-hardware.org/?probe=86cf510b70) | Jun 25, 2021 |
| ASUSTek       | P4P800                      | [34311a4871](https://linux-hardware.org/?probe=34311a4871) | Jun 24, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | P5K SE/EPU                  | [2ac4f62ee0](https://linux-hardware.org/?probe=2ac4f62ee0) | Jun 22, 2021 |
| HP            | 09F0h                       | [87e8574f22](https://linux-hardware.org/?probe=87e8574f22) | Jun 21, 2021 |
| ASRock        | H87 Pro4                    | [700a3a261f](https://linux-hardware.org/?probe=700a3a261f) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| ASRock        | H310CM-HDV                  | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| IBM           | 8183V6D                     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Dell          | 06JWJY A01                  | [c89316e492](https://linux-hardware.org/?probe=c89316e492) | Jun 17, 2021 |
| ASUSTek       | H87-PRO                     | [acd35c74b5](https://linux-hardware.org/?probe=acd35c74b5) | Jun 17, 2021 |
| ASUSTek       | H110M-R                     | [00bac228a5](https://linux-hardware.org/?probe=00bac228a5) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-K               | [6ba9397454](https://linux-hardware.org/?probe=6ba9397454) | Jun 15, 2021 |
| ASUSTek       | PRIME Z590-A                | [ad883d60a1](https://linux-hardware.org/?probe=ad883d60a1) | Jun 14, 2021 |
| HP            | 198E                        | [4d38d777c3](https://linux-hardware.org/?probe=4d38d777c3) | Jun 13, 2021 |
| ASUSTek       | PRIME B450M-A               | [9640e0c3b6](https://linux-hardware.org/?probe=9640e0c3b6) | Jun 13, 2021 |
| HP            | 198E                        | [056f258949](https://linux-hardware.org/?probe=056f258949) | Jun 13, 2021 |
| ASUSTek       | PRIME B365M-A               | [bc646daae3](https://linux-hardware.org/?probe=bc646daae3) | Jun 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| Dell          | 0KV62T A00                  | [180d4c1e75](https://linux-hardware.org/?probe=180d4c1e75) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| Gigabyte      | G41MT-USB3                  | [df62a2a7e0](https://linux-hardware.org/?probe=df62a2a7e0) | Jun 11, 2021 |
| Pegatron      | Narra6                      | [50ed53f75c](https://linux-hardware.org/?probe=50ed53f75c) | Jun 11, 2021 |
| ASUSTek       | P7P55 LX                    | [ab33816373](https://linux-hardware.org/?probe=ab33816373) | Jun 10, 2021 |
| ASUSTek       | P7P55 LX                    | [fe68f058d6](https://linux-hardware.org/?probe=fe68f058d6) | Jun 10, 2021 |
| HP            | 198E                        | [683e970f55](https://linux-hardware.org/?probe=683e970f55) | Jun 10, 2021 |
| Pegatron      | Narra6                      | [1d703f0683](https://linux-hardware.org/?probe=1d703f0683) | Jun 10, 2021 |
| Packard Be... | ipower G5800                | [6978d14549](https://linux-hardware.org/?probe=6978d14549) | Jun 10, 2021 |
| HP            | 8436                        | [f8cefa0267](https://linux-hardware.org/?probe=f8cefa0267) | Jun 09, 2021 |
| ASUSTek       | H81M-P PLUS                 | [832c44928a](https://linux-hardware.org/?probe=832c44928a) | Jun 08, 2021 |
| ASUSTek       | H61M-K                      | [ff3298a573](https://linux-hardware.org/?probe=ff3298a573) | Jun 08, 2021 |
| Lenovo        | ThinkCentre M58 7638CH6     | [17a54739fd](https://linux-hardware.org/?probe=17a54739fd) | Jun 08, 2021 |
| Dell          | 0VD5HY A04                  | [504f3bb1bf](https://linux-hardware.org/?probe=504f3bb1bf) | Jun 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| HP            | 3396                        | [0cb8ca8887](https://linux-hardware.org/?probe=0cb8ca8887) | Jun 07, 2021 |
| HP            | ProLiant Micro Server       | [789d7d0e90](https://linux-hardware.org/?probe=789d7d0e90) | Jun 06, 2021 |
| Dell          | 0GXM1W A00                  | [78f74c7eeb](https://linux-hardware.org/?probe=78f74c7eeb) | Jun 06, 2021 |
| Packard Be... | ipower G5800                | [22042b1727](https://linux-hardware.org/?probe=22042b1727) | Jun 06, 2021 |
| ASUSTek       | P8B75-M LX                  | [f08258e247](https://linux-hardware.org/?probe=f08258e247) | Jun 06, 2021 |
| ASUSTek       | Z87M-PLUS                   | [6416e75d0f](https://linux-hardware.org/?probe=6416e75d0f) | Jun 05, 2021 |
| ASUSTek       | Z87M-PLUS                   | [92afe18e55](https://linux-hardware.org/?probe=92afe18e55) | Jun 05, 2021 |
| ASRock        | FM2A68M-DG3+                | [81fee2b563](https://linux-hardware.org/?probe=81fee2b563) | Jun 04, 2021 |
| ASRock        | A320M-DVS R4.0              | [4ce3673d2d](https://linux-hardware.org/?probe=4ce3673d2d) | Jun 04, 2021 |
| ASUSTek       | M4A88T-M/USB3               | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| MSI           | H81M-P33                    | [40cf3439db](https://linux-hardware.org/?probe=40cf3439db) | Jun 02, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [d80338f3e9](https://linux-hardware.org/?probe=d80338f3e9) | Jun 02, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [93670ccf22](https://linux-hardware.org/?probe=93670ccf22) | Jun 02, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5cbd925314](https://linux-hardware.org/?probe=5cbd925314) | Jun 02, 2021 |
| MSI           | B450M GAMING PLUS           | [cdbf3bb107](https://linux-hardware.org/?probe=cdbf3bb107) | Jun 02, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a133667e3c](https://linux-hardware.org/?probe=a133667e3c) | May 31, 2021 |
| MSI           | Z390-A PRO                  | [995ef5ecd6](https://linux-hardware.org/?probe=995ef5ecd6) | May 30, 2021 |
| MSI           | Z390-A PRO                  | [821ef6c770](https://linux-hardware.org/?probe=821ef6c770) | May 30, 2021 |
| Acer          | Veriton X270                | [d6cb41706d](https://linux-hardware.org/?probe=d6cb41706d) | May 30, 2021 |
| ASRock        | 890FX Deluxe3               | [2b9cbc3fac](https://linux-hardware.org/?probe=2b9cbc3fac) | May 30, 2021 |
| ASUSTek       | P5QPL-AM                    | [5101982911](https://linux-hardware.org/?probe=5101982911) | May 30, 2021 |
| HP            | 3048h                       | [39204d22ae](https://linux-hardware.org/?probe=39204d22ae) | May 29, 2021 |
| Acer          | F672CR R01-B1               | [652ed79c86](https://linux-hardware.org/?probe=652ed79c86) | May 29, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | [4b4d8aa09f](https://linux-hardware.org/?probe=4b4d8aa09f) | May 28, 2021 |
| ASRock        | Q1900M                      | [cfca765670](https://linux-hardware.org/?probe=cfca765670) | May 27, 2021 |
| ASRock        | G41C-GS                     | [3b3b30bf78](https://linux-hardware.org/?probe=3b3b30bf78) | May 27, 2021 |
| ASUSTek       | P8Z77-V LX                  | [330b8b499b](https://linux-hardware.org/?probe=330b8b499b) | May 27, 2021 |
| MSI           | H110M PRO-VD                | [21eb602a48](https://linux-hardware.org/?probe=21eb602a48) | May 26, 2021 |
| ASUSTek       | Rampage Formula             | [4f6defb975](https://linux-hardware.org/?probe=4f6defb975) | May 26, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [78392163bc](https://linux-hardware.org/?probe=78392163bc) | May 26, 2021 |
| Acer          | F672CR R01-B1               | [0c35af28cc](https://linux-hardware.org/?probe=0c35af28cc) | May 26, 2021 |
| HP            | 821D                        | [b67ebd33a8](https://linux-hardware.org/?probe=b67ebd33a8) | May 26, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [3b8ddca28e](https://linux-hardware.org/?probe=3b8ddca28e) | May 26, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [01379ec7fb](https://linux-hardware.org/?probe=01379ec7fb) | May 26, 2021 |
| Foxconn       | 2ABF                        | [57ffe115ac](https://linux-hardware.org/?probe=57ffe115ac) | May 26, 2021 |
| MSI           | B450M GAMING PLUS           | [9b8f51b1d4](https://linux-hardware.org/?probe=9b8f51b1d4) | May 26, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [e6f55faad0](https://linux-hardware.org/?probe=e6f55faad0) | May 25, 2021 |
| ASRock        | X370 Pro4                   | [838ce3fb95](https://linux-hardware.org/?probe=838ce3fb95) | May 25, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [1db1dcbb2c](https://linux-hardware.org/?probe=1db1dcbb2c) | May 25, 2021 |
| Foxconn       | ETON                        | [e00899cc83](https://linux-hardware.org/?probe=e00899cc83) | May 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [57dddd9077](https://linux-hardware.org/?probe=57dddd9077) | May 25, 2021 |
| Unknown       | 1.0                         | [704db88794](https://linux-hardware.org/?probe=704db88794) | May 25, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [f0606e05ac](https://linux-hardware.org/?probe=f0606e05ac) | May 24, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [23198e478a](https://linux-hardware.org/?probe=23198e478a) | May 24, 2021 |
| Gigabyte      | B450 AORUS M                | [a9539e0359](https://linux-hardware.org/?probe=a9539e0359) | May 24, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | [46d8de81b9](https://linux-hardware.org/?probe=46d8de81b9) | May 24, 2021 |
| Intel         | DH67CL AAG10212-210         | [e513453d87](https://linux-hardware.org/?probe=e513453d87) | May 23, 2021 |
| Gigabyte      | F2A78M-DS2                  | [da126fa410](https://linux-hardware.org/?probe=da126fa410) | May 23, 2021 |
| Gigabyte      | H77-DS3H                    | [ba8ceed42c](https://linux-hardware.org/?probe=ba8ceed42c) | May 23, 2021 |
| ASUSTek       | ET2700I                     | [a3edd93ada](https://linux-hardware.org/?probe=a3edd93ada) | May 23, 2021 |
| MSI           | B450-A PRO MAX              | [a42f5b4313](https://linux-hardware.org/?probe=a42f5b4313) | May 22, 2021 |
| Foxconn       | 2ABF                        | [7806332395](https://linux-hardware.org/?probe=7806332395) | May 19, 2021 |
| ASUSTek       | TUF GAMING Z590-PLUS WIF... | [3814598db5](https://linux-hardware.org/?probe=3814598db5) | May 19, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [cfe0035561](https://linux-hardware.org/?probe=cfe0035561) | May 19, 2021 |
| ASUSTek       | Z97-K                       | [ace0bb9d53](https://linux-hardware.org/?probe=ace0bb9d53) | May 19, 2021 |
| Gigabyte      | B360M DS3H                  | [cd81d5a6be](https://linux-hardware.org/?probe=cd81d5a6be) | May 18, 2021 |
| MSI           | B450M-A PRO MAX             | [2f09898c11](https://linux-hardware.org/?probe=2f09898c11) | May 18, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [d8d106f47b](https://linux-hardware.org/?probe=d8d106f47b) | May 18, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [828dbdcd9e](https://linux-hardware.org/?probe=828dbdcd9e) | May 17, 2021 |
| Pegatron      | Benicia                     | [e051360964](https://linux-hardware.org/?probe=e051360964) | May 17, 2021 |
| Foxconn       | 2ABF                        | [b8de97b4c0](https://linux-hardware.org/?probe=b8de97b4c0) | May 17, 2021 |
| Acer          | F672CR R01-B1               | [bd8067c8cf](https://linux-hardware.org/?probe=bd8067c8cf) | May 16, 2021 |
| Foxconn       | 2ABF                        | [6e96a8df5f](https://linux-hardware.org/?probe=6e96a8df5f) | May 16, 2021 |
| Gigabyte      | H77-DS3H                    | [033400e8bc](https://linux-hardware.org/?probe=033400e8bc) | May 15, 2021 |
| HP            | 8653 A                      | [a9b6e036cd](https://linux-hardware.org/?probe=a9b6e036cd) | May 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [dce57e5149](https://linux-hardware.org/?probe=dce57e5149) | May 14, 2021 |
| MSI           | B560M PRO-VDH WIFI          | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| ASRock        | X570 Creator                | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [acdc104331](https://linux-hardware.org/?probe=acdc104331) | May 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [3199607565](https://linux-hardware.org/?probe=3199607565) | May 13, 2021 |
| ASRock        | 960GM/U3S3 FX               | [6bdf2e77c2](https://linux-hardware.org/?probe=6bdf2e77c2) | May 12, 2021 |
| HP            | 8298                        | [d5257ee99c](https://linux-hardware.org/?probe=d5257ee99c) | May 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c88308fb06](https://linux-hardware.org/?probe=c88308fb06) | May 09, 2021 |
| ASRock        | H81M-HDS R2.0               | [c25f7a35df](https://linux-hardware.org/?probe=c25f7a35df) | May 09, 2021 |
| Acer          | Veriton X490G               | [a729505133](https://linux-hardware.org/?probe=a729505133) | May 08, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [240f428975](https://linux-hardware.org/?probe=240f428975) | May 07, 2021 |
| HP            | 0AA8h                       | [73de7edd60](https://linux-hardware.org/?probe=73de7edd60) | May 07, 2021 |
| HP            | 18E7                        | [6165bab829](https://linux-hardware.org/?probe=6165bab829) | May 07, 2021 |
| ASUSTek       | H110M-PLUS                  | [4ed02bf7a2](https://linux-hardware.org/?probe=4ed02bf7a2) | May 05, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| MSI           | MPG Z490M GAMING EDGE WI... | [34660a208d](https://linux-hardware.org/?probe=34660a208d) | May 04, 2021 |
| IBM           | 8183V6D                     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| ASUSTek       | M3A79-T DELUXE              | [3a7bb902f4](https://linux-hardware.org/?probe=3a7bb902f4) | May 02, 2021 |
| ASUSTek       | H170M-PLUS                  | [9759cdb995](https://linux-hardware.org/?probe=9759cdb995) | May 02, 2021 |
| ASUSTek       | Q87T                        | [808a17b746](https://linux-hardware.org/?probe=808a17b746) | May 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5896a72e6f](https://linux-hardware.org/?probe=5896a72e6f) | May 01, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | [c33283ad59](https://linux-hardware.org/?probe=c33283ad59) | May 01, 2021 |
| ASUSTek       | UN45                        | [6abde89216](https://linux-hardware.org/?probe=6abde89216) | Apr 29, 2021 |
| ASUSTek       | PRIME H370-PLUS             | [da586f48d4](https://linux-hardware.org/?probe=da586f48d4) | Apr 29, 2021 |
| Acer          | Aspire X5950                | [a18a958cf8](https://linux-hardware.org/?probe=a18a958cf8) | Apr 28, 2021 |
| Gigabyte      | B450 AORUS M                | [487d3c6959](https://linux-hardware.org/?probe=487d3c6959) | Apr 27, 2021 |
| ASUSTek       | M2N-E                       | [a4394162e1](https://linux-hardware.org/?probe=a4394162e1) | Apr 27, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [43367e9899](https://linux-hardware.org/?probe=43367e9899) | Apr 26, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [5c8af3a6f6](https://linux-hardware.org/?probe=5c8af3a6f6) | Apr 26, 2021 |
| MSI           | B450-A PRO MAX              | [8b8739af7f](https://linux-hardware.org/?probe=8b8739af7f) | Apr 25, 2021 |
| MSI           | Z97I AC                     | [f4b6014b42](https://linux-hardware.org/?probe=f4b6014b42) | Apr 25, 2021 |
| Gigabyte      | GA-73VM-S2                  | [a8aff187a3](https://linux-hardware.org/?probe=a8aff187a3) | Apr 25, 2021 |
| ASRock        | FM2A68M-HD+                 | [254f079c86](https://linux-hardware.org/?probe=254f079c86) | Apr 25, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [f648d54072](https://linux-hardware.org/?probe=f648d54072) | Apr 24, 2021 |
| Alienware     | 046MHW A00                  | [791f444e79](https://linux-hardware.org/?probe=791f444e79) | Apr 24, 2021 |
| ASUSTek       | PRIME H270-PRO              | [163211473a](https://linux-hardware.org/?probe=163211473a) | Apr 23, 2021 |
| ASUSTek       | P8P67                       | [e9c8622c63](https://linux-hardware.org/?probe=e9c8622c63) | Apr 23, 2021 |
| HP            | 0B48h                       | [a6862c2a01](https://linux-hardware.org/?probe=a6862c2a01) | Apr 23, 2021 |
| MSI           | H81M-P33                    | [4197922248](https://linux-hardware.org/?probe=4197922248) | Apr 22, 2021 |
| LattePanda    | Alpha                       | [a16a117b5a](https://linux-hardware.org/?probe=a16a117b5a) | Apr 22, 2021 |
| LattePanda    | Alpha                       | [2a92af628e](https://linux-hardware.org/?probe=2a92af628e) | Apr 22, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [6d786229f3](https://linux-hardware.org/?probe=6d786229f3) | Apr 21, 2021 |
| Acer          | Aspire XC-885 V:1.1         | [d659fa1ad2](https://linux-hardware.org/?probe=d659fa1ad2) | Apr 21, 2021 |
| ASUSTek       | H97M-E                      | [31aab66985](https://linux-hardware.org/?probe=31aab66985) | Apr 21, 2021 |
| Acer          | F672CR R01-B1               | [e41788bfca](https://linux-hardware.org/?probe=e41788bfca) | Apr 20, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | [cc19aae500](https://linux-hardware.org/?probe=cc19aae500) | Apr 20, 2021 |
| Dell          | 0G7W4R A00                  | [477ba6a2a6](https://linux-hardware.org/?probe=477ba6a2a6) | Apr 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [0bb4e622db](https://linux-hardware.org/?probe=0bb4e622db) | Apr 19, 2021 |
| Dell          | 0KV62T A00                  | [4adc8bc921](https://linux-hardware.org/?probe=4adc8bc921) | Apr 18, 2021 |
| ASUSTek       | H61M-K                      | [e63cdf17ed](https://linux-hardware.org/?probe=e63cdf17ed) | Apr 17, 2021 |
| ASRock        | X79 Extreme3                | [7a4d566f94](https://linux-hardware.org/?probe=7a4d566f94) | Apr 16, 2021 |
| Unknown       | RS780-SB700                 | [f3faf71595](https://linux-hardware.org/?probe=f3faf71595) | Apr 16, 2021 |
| Gigabyte      | EX58-UD3R                   | [0adcffb219](https://linux-hardware.org/?probe=0adcffb219) | Apr 15, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [69b0143e69](https://linux-hardware.org/?probe=69b0143e69) | Apr 15, 2021 |
| Pegatron      | Benicia                     | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| MSI           | B350 TOMAHAWK               | [382673d3f6](https://linux-hardware.org/?probe=382673d3f6) | Apr 15, 2021 |
| ASUSTek       | P8P67 EVO                   | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Dell          | 0KRC95 A02                  | [13439b846f](https://linux-hardware.org/?probe=13439b846f) | Apr 14, 2021 |
| ASUSTek       | P5GD1-VM                    | [3be5f678de](https://linux-hardware.org/?probe=3be5f678de) | Apr 13, 2021 |
| HP            | 0AA0h                       | [1a9967aefe](https://linux-hardware.org/?probe=1a9967aefe) | Apr 12, 2021 |
| ASRock        | X79 Extreme3                | [7d3e0b3326](https://linux-hardware.org/?probe=7d3e0b3326) | Apr 12, 2021 |
| Acer          | Veriton M490G               | [35b50e1b82](https://linux-hardware.org/?probe=35b50e1b82) | Apr 11, 2021 |
| BESSTAR Te... | UM250 V1.0                  | [4def631c3f](https://linux-hardware.org/?probe=4def631c3f) | Apr 11, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [3bc558699a](https://linux-hardware.org/?probe=3bc558699a) | Apr 11, 2021 |
| Dell          | 0CT017                      | [a57cbe27ac](https://linux-hardware.org/?probe=a57cbe27ac) | Apr 11, 2021 |
| ASUSTek       | H61M-K                      | [d8c2b8c6f1](https://linux-hardware.org/?probe=d8c2b8c6f1) | Apr 10, 2021 |
| ASUSTek       | H61M-K                      | [50baaadc88](https://linux-hardware.org/?probe=50baaadc88) | Apr 10, 2021 |
| HP            | 86E9 A                      | [4391ffaa59](https://linux-hardware.org/?probe=4391ffaa59) | Apr 09, 2021 |
| ASRock        | B365 Pro4                   | [c16dc79b70](https://linux-hardware.org/?probe=c16dc79b70) | Apr 09, 2021 |
| Gigabyte      | EX58-UD3R                   | [72136cdcb4](https://linux-hardware.org/?probe=72136cdcb4) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | [ffb7b0bfdf](https://linux-hardware.org/?probe=ffb7b0bfdf) | Apr 09, 2021 |
| Unknown       | Unknown                     | [48c3da2346](https://linux-hardware.org/?probe=48c3da2346) | Apr 09, 2021 |
| HP            | 0AA0h                       | [7b37a65309](https://linux-hardware.org/?probe=7b37a65309) | Apr 09, 2021 |
| Gigabyte      | G31M-ES2L                   | [1a28b142a6](https://linux-hardware.org/?probe=1a28b142a6) | Apr 08, 2021 |
| Gigabyte      | G31M-ES2L                   | [08105265b6](https://linux-hardware.org/?probe=08105265b6) | Apr 08, 2021 |
| Gigabyte      | X570 AORUS PRO              | [3676c6c723](https://linux-hardware.org/?probe=3676c6c723) | Apr 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [e4e5849dc3](https://linux-hardware.org/?probe=e4e5849dc3) | Apr 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | [bbba9f20f9](https://linux-hardware.org/?probe=bbba9f20f9) | Apr 07, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [b0530164f5](https://linux-hardware.org/?probe=b0530164f5) | Apr 06, 2021 |
| HP            | 0B48h                       | [3f20bd760d](https://linux-hardware.org/?probe=3f20bd760d) | Apr 06, 2021 |
| ASUSTek       | P5Q                         | [ebd008d62f](https://linux-hardware.org/?probe=ebd008d62f) | Apr 06, 2021 |
| ASUSTek       | Z170-A                      | [0e290cc57a](https://linux-hardware.org/?probe=0e290cc57a) | Apr 05, 2021 |
| ASRock        | H81M                        | [5c1ff2d024](https://linux-hardware.org/?probe=5c1ff2d024) | Apr 05, 2021 |
| ASRock        | H81M                        | [e3362d225b](https://linux-hardware.org/?probe=e3362d225b) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| MSI           | P45-C51                     | [fd6b5e81cc](https://linux-hardware.org/?probe=fd6b5e81cc) | Apr 04, 2021 |
| Acer          | Aspire XC-703               | [a0ff265d62](https://linux-hardware.org/?probe=a0ff265d62) | Apr 04, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b7ddba0e80](https://linux-hardware.org/?probe=b7ddba0e80) | Apr 04, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [7086b0c8af](https://linux-hardware.org/?probe=7086b0c8af) | Apr 03, 2021 |
| ASUSTek       | H110M-C                     | [5809742ae4](https://linux-hardware.org/?probe=5809742ae4) | Apr 02, 2021 |
| ASRock        | B365 Pro4                   | [4752444738](https://linux-hardware.org/?probe=4752444738) | Apr 02, 2021 |
| Dell          | 0GM819                      | [a96a855376](https://linux-hardware.org/?probe=a96a855376) | Apr 01, 2021 |
| ASUSTek       | PRIME Z490-P                | [ddc489f5a0](https://linux-hardware.org/?probe=ddc489f5a0) | Apr 01, 2021 |
| HP            | 8433 11                     | [e9742c8d9f](https://linux-hardware.org/?probe=e9742c8d9f) | Mar 31, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5fd55d3c2b](https://linux-hardware.org/?probe=5fd55d3c2b) | Mar 30, 2021 |
| AZW           | Gemini X45                  | [47684b9b79](https://linux-hardware.org/?probe=47684b9b79) | Mar 30, 2021 |
| Unknown       | 2Core1333-2.66G             | [e677b96dba](https://linux-hardware.org/?probe=e677b96dba) | Mar 28, 2021 |
| ASUSTek       | CM1740                      | [96dd2d8f2b](https://linux-hardware.org/?probe=96dd2d8f2b) | Mar 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [1a1f695752](https://linux-hardware.org/?probe=1a1f695752) | Mar 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cd78c529ab](https://linux-hardware.org/?probe=cd78c529ab) | Mar 26, 2021 |
| MSI           | B450-A PRO MAX              | [00e17958e2](https://linux-hardware.org/?probe=00e17958e2) | Mar 26, 2021 |
| AAEON         | UP-APL01 V0.4               | [9a724f738f](https://linux-hardware.org/?probe=9a724f738f) | Mar 26, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f52a9800ea](https://linux-hardware.org/?probe=f52a9800ea) | Mar 26, 2021 |
| ASUSTek       | PRIME Z390-P                | [efaace4042](https://linux-hardware.org/?probe=efaace4042) | Mar 25, 2021 |
| ASUSTek       | P5KPL-SE                    | [f894abd641](https://linux-hardware.org/?probe=f894abd641) | Mar 25, 2021 |
| ASRock        | B365 Pro4                   | [df23ae3c63](https://linux-hardware.org/?probe=df23ae3c63) | Mar 25, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [4cec86e841](https://linux-hardware.org/?probe=4cec86e841) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| ASUSTek       | H81-PLUS                    | [771f8dbc5d](https://linux-hardware.org/?probe=771f8dbc5d) | Mar 25, 2021 |
| ASUSTek       | PRIME H310M-K               | [1faa19e424](https://linux-hardware.org/?probe=1faa19e424) | Mar 24, 2021 |
| ASRock        | 4CoreDual-VSTA              | [517b90d6f4](https://linux-hardware.org/?probe=517b90d6f4) | Mar 24, 2021 |
| ASRock        | 4CoreDual-VSTA              | [20e21ed03f](https://linux-hardware.org/?probe=20e21ed03f) | Mar 24, 2021 |
| ASUSTek       | M4A87TD/USB3                | [c98e498e71](https://linux-hardware.org/?probe=c98e498e71) | Mar 24, 2021 |
| ASUSTek       | M4A87TD/USB3                | [9c88c5fbd7](https://linux-hardware.org/?probe=9c88c5fbd7) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | [b33fccab41](https://linux-hardware.org/?probe=b33fccab41) | Mar 24, 2021 |
| Dell          | 03NVJ6 A02                  | [255c511610](https://linux-hardware.org/?probe=255c511610) | Mar 23, 2021 |
| ASUSTek       | P8P67                       | [22670bee96](https://linux-hardware.org/?probe=22670bee96) | Mar 23, 2021 |
| Gigabyte      | 945GZM-S2                   | [3da6cb6a08](https://linux-hardware.org/?probe=3da6cb6a08) | Mar 22, 2021 |
| Gigabyte      | H410M S2H                   | [8acf257064](https://linux-hardware.org/?probe=8acf257064) | Mar 22, 2021 |
| Unknown       | Intel X79                   | [8bd86d25b8](https://linux-hardware.org/?probe=8bd86d25b8) | Mar 22, 2021 |
| Dell          | 03NVJ6 A02                  | [e3ba207d42](https://linux-hardware.org/?probe=e3ba207d42) | Mar 22, 2021 |
| Gigabyte      | Z97X-UD5H                   | [600eb1487a](https://linux-hardware.org/?probe=600eb1487a) | Mar 21, 2021 |
| ASRock        | 4Core1600Twins-P35          | [5df045db58](https://linux-hardware.org/?probe=5df045db58) | Mar 21, 2021 |
| MSI           | A320M-A PRO                 | [9bd4224188](https://linux-hardware.org/?probe=9bd4224188) | Mar 21, 2021 |
| ASRock        | 4CoreDual-VSTA              | [5f974c11f5](https://linux-hardware.org/?probe=5f974c11f5) | Mar 20, 2021 |
| HP            | 3031h                       | [b30170a46c](https://linux-hardware.org/?probe=b30170a46c) | Mar 18, 2021 |
| HP            | 3396                        | [752b8343d6](https://linux-hardware.org/?probe=752b8343d6) | Mar 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [fd5b65a6e0](https://linux-hardware.org/?probe=fd5b65a6e0) | Mar 18, 2021 |
| HP            | 3396                        | [9517a9cae5](https://linux-hardware.org/?probe=9517a9cae5) | Mar 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [11e009f263](https://linux-hardware.org/?probe=11e009f263) | Mar 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8a918cbbd](https://linux-hardware.org/?probe=b8a918cbbd) | Mar 17, 2021 |
| ASRock        | H61M-DGS                    | [7bda431c0e](https://linux-hardware.org/?probe=7bda431c0e) | Mar 17, 2021 |
| ASRock        | H270 Pro4                   | [417c8cce2b](https://linux-hardware.org/?probe=417c8cce2b) | Mar 17, 2021 |
| Dell          | 0KWVT8 A03                  | [9a3fd32ec9](https://linux-hardware.org/?probe=9a3fd32ec9) | Mar 17, 2021 |
| Intel         | DZ68DB AAG27985-101         | [f0962cd3b3](https://linux-hardware.org/?probe=f0962cd3b3) | Mar 17, 2021 |
| MSI           | 0A90                        | [77af045208](https://linux-hardware.org/?probe=77af045208) | Mar 15, 2021 |
| HP            | 1494                        | [9b362701c1](https://linux-hardware.org/?probe=9b362701c1) | Mar 14, 2021 |
| HP            | ProLiant MicroServer Gen... | [e11bd273fa](https://linux-hardware.org/?probe=e11bd273fa) | Mar 14, 2021 |
| Gigabyte      | H77-DS3H                    | [e7da1f552e](https://linux-hardware.org/?probe=e7da1f552e) | Mar 14, 2021 |
| MSI           | H97 GAMING 3                | [16f03f3813](https://linux-hardware.org/?probe=16f03f3813) | Mar 14, 2021 |
| ASUSTek       | P5KPL-SE                    | [d863235bc9](https://linux-hardware.org/?probe=d863235bc9) | Mar 13, 2021 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [a80d2276e2](https://linux-hardware.org/?probe=a80d2276e2) | Mar 13, 2021 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [0628a7cc4a](https://linux-hardware.org/?probe=0628a7cc4a) | Mar 13, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1d728a566c](https://linux-hardware.org/?probe=1d728a566c) | Mar 13, 2021 |
| ASRock        | X570 Taichi                 | [625f6e648c](https://linux-hardware.org/?probe=625f6e648c) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| MSI           | H97 GAMING 3                | [d0fa1639a2](https://linux-hardware.org/?probe=d0fa1639a2) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| MSI           | H81M-P33                    | [899f875163](https://linux-hardware.org/?probe=899f875163) | Mar 12, 2021 |
| MSI           | B360 GAMING ARCTIC          | [f1a02da1b7](https://linux-hardware.org/?probe=f1a02da1b7) | Mar 11, 2021 |
| Lenovo        | MAHOBAY                     | [56806bedad](https://linux-hardware.org/?probe=56806bedad) | Mar 09, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e3da7825b3](https://linux-hardware.org/?probe=e3da7825b3) | Mar 09, 2021 |
| AZW           | Gemini X45                  | [d764bffd6d](https://linux-hardware.org/?probe=d764bffd6d) | Mar 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [86f2569d5b](https://linux-hardware.org/?probe=86f2569d5b) | Mar 08, 2021 |
| Sapphire      | IPC-E350M1                  | [5a2727c2b6](https://linux-hardware.org/?probe=5a2727c2b6) | Mar 08, 2021 |
| ASUSTek       | P7P55D-E                    | [171f37f987](https://linux-hardware.org/?probe=171f37f987) | Mar 07, 2021 |
| Gigabyte      | X58A-UD3R                   | [1598a586c7](https://linux-hardware.org/?probe=1598a586c7) | Mar 07, 2021 |
| Dell          | 0R849J A00                  | [5327d9f4a3](https://linux-hardware.org/?probe=5327d9f4a3) | Mar 06, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [ba7359637e](https://linux-hardware.org/?probe=ba7359637e) | Mar 06, 2021 |
| MSI           | A88X-G45 GAMING             | [6f50656aec](https://linux-hardware.org/?probe=6f50656aec) | Mar 06, 2021 |
| BESSTAR Te... | UM300 V1.0                  | [c4e04796d1](https://linux-hardware.org/?probe=c4e04796d1) | Mar 05, 2021 |
| Intel         | DH67GD AAG10206-205         | [2f7536f0a1](https://linux-hardware.org/?probe=2f7536f0a1) | Mar 05, 2021 |
| Intel         | DH67GD AAG10206-205         | [990269df5a](https://linux-hardware.org/?probe=990269df5a) | Mar 05, 2021 |
| ASUSTek       | P5K-E                       | [7609423845](https://linux-hardware.org/?probe=7609423845) | Mar 04, 2021 |
| ASUSTek       | H81M-C                      | [d0e8823978](https://linux-hardware.org/?probe=d0e8823978) | Mar 04, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [77c229f6c5](https://linux-hardware.org/?probe=77c229f6c5) | Mar 04, 2021 |
| ASUSTek       | H81-PLUS                    | [8afbcaceb0](https://linux-hardware.org/?probe=8afbcaceb0) | Mar 02, 2021 |
| Lenovo        | ThinkCentre M55 8805W2G     | [cc0bd5d059](https://linux-hardware.org/?probe=cc0bd5d059) | Mar 01, 2021 |
| ASUSTek       | CM1740                      | [766be51205](https://linux-hardware.org/?probe=766be51205) | Mar 01, 2021 |
| Acer          | Veriton X2640G V:1.0        | [c6a5bb827b](https://linux-hardware.org/?probe=c6a5bb827b) | Mar 01, 2021 |
| ASRock        | 4CoreDual-SATA2             | [5360846610](https://linux-hardware.org/?probe=5360846610) | Mar 01, 2021 |
| ASUSTek       | P8H61-M LX                  | [0c1cb15e47](https://linux-hardware.org/?probe=0c1cb15e47) | Feb 28, 2021 |
| ASUSTek       | P8H61-M LX                  | [4774dabe35](https://linux-hardware.org/?probe=4774dabe35) | Feb 28, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c87ec564b4](https://linux-hardware.org/?probe=c87ec564b4) | Feb 27, 2021 |
| ASRock        | 970 Pro3 R2.0               | [a3bffeaaf2](https://linux-hardware.org/?probe=a3bffeaaf2) | Feb 27, 2021 |
| MSI           | B350 TOMAHAWK               | [f516c094eb](https://linux-hardware.org/?probe=f516c094eb) | Feb 27, 2021 |
| Intel         | DZ68DB AAG27985-101         | [ea0a526461](https://linux-hardware.org/?probe=ea0a526461) | Feb 27, 2021 |
| Gigabyte      | 990FXA-UD3                  | [696779c52c](https://linux-hardware.org/?probe=696779c52c) | Feb 26, 2021 |
| Intel         | H55 INTEL                   | [a4a500bdaf](https://linux-hardware.org/?probe=a4a500bdaf) | Feb 26, 2021 |
| HP            | 3029h                       | [c1402e7026](https://linux-hardware.org/?probe=c1402e7026) | Feb 26, 2021 |
| ASUSTek       | M2A-MX                      | [38f069f44b](https://linux-hardware.org/?probe=38f069f44b) | Feb 26, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [4c6960746c](https://linux-hardware.org/?probe=4c6960746c) | Feb 25, 2021 |
| Gigabyte      | G31M-ES2L                   | [e046f54c33](https://linux-hardware.org/?probe=e046f54c33) | Feb 25, 2021 |
| ASUSTek       | P5LD2EB-DHS                 | [d5d6c2b0b1](https://linux-hardware.org/?probe=d5d6c2b0b1) | Feb 24, 2021 |
| ASUSTek       | P5LD2EB-DHS                 | [12d5d97c6c](https://linux-hardware.org/?probe=12d5d97c6c) | Feb 23, 2021 |
| ASRock        | X300M-STX                   | [89f61ec69c](https://linux-hardware.org/?probe=89f61ec69c) | Feb 23, 2021 |
| MSI           | Z97A GAMING 7               | [1e83e02b7c](https://linux-hardware.org/?probe=1e83e02b7c) | Feb 22, 2021 |
| ASUSTek       | P8H61                       | [d9f4d2b35c](https://linux-hardware.org/?probe=d9f4d2b35c) | Feb 22, 2021 |
| ASUSTek       | PRIME B250M-K               | [d38faa9c22](https://linux-hardware.org/?probe=d38faa9c22) | Feb 22, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| Pegatron      | Benicia                     | [0854946ffb](https://linux-hardware.org/?probe=0854946ffb) | Feb 21, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [68470237ba](https://linux-hardware.org/?probe=68470237ba) | Feb 21, 2021 |
| ASUSTek       | CM1740                      | [693f25a9f3](https://linux-hardware.org/?probe=693f25a9f3) | Feb 21, 2021 |
| ASRock        | 4Core1600Twins-P35          | [59f122b797](https://linux-hardware.org/?probe=59f122b797) | Feb 20, 2021 |
| ASUSTek       | J1900I-C                    | [2ea5f955cc](https://linux-hardware.org/?probe=2ea5f955cc) | Feb 20, 2021 |
| ASUSTek       | CM6870                      | [18028e1493](https://linux-hardware.org/?probe=18028e1493) | Feb 20, 2021 |
| ASUSTek       | CM6870                      | [29d2b97d40](https://linux-hardware.org/?probe=29d2b97d40) | Feb 20, 2021 |
| Dell          | 0F373D A00                  | [d5c249a450](https://linux-hardware.org/?probe=d5c249a450) | Feb 20, 2021 |
| HP            | 0B48h                       | [a5f4a89246](https://linux-hardware.org/?probe=a5f4a89246) | Feb 20, 2021 |
| MSI           | Boston                      | [c8c1122097](https://linux-hardware.org/?probe=c8c1122097) | Feb 20, 2021 |
| HP            | 0B48h                       | [cfdbc06fe9](https://linux-hardware.org/?probe=cfdbc06fe9) | Feb 20, 2021 |
| HP            | 8399                        | [733813e901](https://linux-hardware.org/?probe=733813e901) | Feb 20, 2021 |
| Gigabyte      | 945GZM-S2                   | [5e0ae1b6d4](https://linux-hardware.org/?probe=5e0ae1b6d4) | Feb 20, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [7d790f5bf5](https://linux-hardware.org/?probe=7d790f5bf5) | Feb 19, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [4028652c66](https://linux-hardware.org/?probe=4028652c66) | Feb 19, 2021 |
| ASUSTek       | F1A55-M LE R2.0             | [cd88fb9009](https://linux-hardware.org/?probe=cd88fb9009) | Feb 18, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [fe9cd3d909](https://linux-hardware.org/?probe=fe9cd3d909) | Feb 17, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [49c1acd924](https://linux-hardware.org/?probe=49c1acd924) | Feb 17, 2021 |
| ASRock        | B365 Pro4                   | [d788bfcc9b](https://linux-hardware.org/?probe=d788bfcc9b) | Feb 17, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [d716bdd4fd](https://linux-hardware.org/?probe=d716bdd4fd) | Feb 17, 2021 |
| Gigabyte      | Z370M D3H-CF                | [d47a646398](https://linux-hardware.org/?probe=d47a646398) | Feb 16, 2021 |
| Acer          | RS780HVF                    | [fe3895a973](https://linux-hardware.org/?probe=fe3895a973) | Feb 16, 2021 |
| ASUSTek       | BM6835_BM6635_BP6335        | [2ca35f372f](https://linux-hardware.org/?probe=2ca35f372f) | Feb 16, 2021 |
| ASRock        | 775VM800                    | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| ASRock        | B75M DASH G/A               | [417bcccfa6](https://linux-hardware.org/?probe=417bcccfa6) | Feb 15, 2021 |
| Biostar       | G41D3+                      | [b184b1bd6e](https://linux-hardware.org/?probe=b184b1bd6e) | Feb 15, 2021 |
| ECS           | Nettle3                     | [661bebb77e](https://linux-hardware.org/?probe=661bebb77e) | Feb 14, 2021 |
| ECS           | Nettle3                     | [c6e68b8a1f](https://linux-hardware.org/?probe=c6e68b8a1f) | Feb 14, 2021 |
| Dell          | 0WR7PY A02                  | [4005ac4804](https://linux-hardware.org/?probe=4005ac4804) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [70733c3f45](https://linux-hardware.org/?probe=70733c3f45) | Feb 14, 2021 |
| ASRock        | Q1900M                      | [96839e6929](https://linux-hardware.org/?probe=96839e6929) | Feb 14, 2021 |
| ASUSTek       | P8H67                       | [1305a1af87](https://linux-hardware.org/?probe=1305a1af87) | Feb 14, 2021 |
| Gigabyte      | EP45-UD3LR                  | [7b77685578](https://linux-hardware.org/?probe=7b77685578) | Feb 13, 2021 |
| ASRock        | 939A790GMH                  | [cd38d5001b](https://linux-hardware.org/?probe=cd38d5001b) | Feb 13, 2021 |
| Intel         | DH55TC AAE70932-205         | [7d462f007b](https://linux-hardware.org/?probe=7d462f007b) | Feb 13, 2021 |
| ASUSTek       | PRIME X470-PRO              | [bf8919baa3](https://linux-hardware.org/?probe=bf8919baa3) | Feb 13, 2021 |
| Dell          | 0P301D A02                  | [478789c1ce](https://linux-hardware.org/?probe=478789c1ce) | Feb 13, 2021 |
| ASRock        | 960GC-GS FX                 | [637fce941a](https://linux-hardware.org/?probe=637fce941a) | Feb 13, 2021 |
| NEC Comput... | P5S800-VM                   | [9f494b661d](https://linux-hardware.org/?probe=9f494b661d) | Feb 13, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [9b87958706](https://linux-hardware.org/?probe=9b87958706) | Feb 13, 2021 |
| ASUSTek       | CM1745                      | [c15e7fd26c](https://linux-hardware.org/?probe=c15e7fd26c) | Feb 13, 2021 |
| HP            | 8653 A                      | [202f2b5577](https://linux-hardware.org/?probe=202f2b5577) | Feb 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [f913e542e3](https://linux-hardware.org/?probe=f913e542e3) | Feb 13, 2021 |
| ASRock        | 775VM800                    | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Gigabyte      | B460M DS3H                  | [e63b1cebf6](https://linux-hardware.org/?probe=e63b1cebf6) | Feb 12, 2021 |
| ASUSTek       | P7H55-M                     | [3e549760d6](https://linux-hardware.org/?probe=3e549760d6) | Feb 11, 2021 |
| ASUSTek       | P7H55-M                     | [d1e1f45d46](https://linux-hardware.org/?probe=d1e1f45d46) | Feb 11, 2021 |
| Foxconn       | ETON                        | [a31fe17933](https://linux-hardware.org/?probe=a31fe17933) | Feb 11, 2021 |
| ASUSTek       | PRIME B460M-A               | [4ed65d02f4](https://linux-hardware.org/?probe=4ed65d02f4) | Feb 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [74923ee3cb](https://linux-hardware.org/?probe=74923ee3cb) | Feb 10, 2021 |
| ASRock        | 960GC-GS FX                 | [2c27dc7b91](https://linux-hardware.org/?probe=2c27dc7b91) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MS-7369                     | [ecadac56ef](https://linux-hardware.org/?probe=ecadac56ef) | Feb 10, 2021 |
| Packard Be... | ipower G5800                | [427dc8145b](https://linux-hardware.org/?probe=427dc8145b) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | Z97-C                       | [72636a31f4](https://linux-hardware.org/?probe=72636a31f4) | Feb 08, 2021 |
| ASRock        | H81M-DGS R2.0               | [d02448fddf](https://linux-hardware.org/?probe=d02448fddf) | Feb 08, 2021 |
| ASRock        | H81M-DGS R2.0               | [062114a51e](https://linux-hardware.org/?probe=062114a51e) | Feb 08, 2021 |
| MSI           | Z97S SLI Krait Edition      | [16e02897fa](https://linux-hardware.org/?probe=16e02897fa) | Feb 08, 2021 |
| Lenovo        | ThinkStation C20 4263BA7    | [28462a6dc9](https://linux-hardware.org/?probe=28462a6dc9) | Feb 07, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [ab23a1c50f](https://linux-hardware.org/?probe=ab23a1c50f) | Feb 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4f4c90183a](https://linux-hardware.org/?probe=4f4c90183a) | Feb 07, 2021 |
| Lenovo        | ThinkStation C20 4263BA7    | [2ff2c91b5c](https://linux-hardware.org/?probe=2ff2c91b5c) | Feb 07, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [66acbd8fa1](https://linux-hardware.org/?probe=66acbd8fa1) | Feb 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | [4eee0834a9](https://linux-hardware.org/?probe=4eee0834a9) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [b5231d5568](https://linux-hardware.org/?probe=b5231d5568) | Feb 07, 2021 |
| Packard Be... | imedia S3710                | [31dca23626](https://linux-hardware.org/?probe=31dca23626) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | [3ab207950b](https://linux-hardware.org/?probe=3ab207950b) | Feb 06, 2021 |
| MSI           | B250M BAZOOKA               | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Gigabyte      | B460M DS3H                  | [7b608b30e3](https://linux-hardware.org/?probe=7b608b30e3) | Feb 06, 2021 |
| ASUSTek       | CM1740                      | [8486c6b481](https://linux-hardware.org/?probe=8486c6b481) | Feb 06, 2021 |
| Intel         | D33217GKE G76540-205        | [acd358e227](https://linux-hardware.org/?probe=acd358e227) | Feb 06, 2021 |
| MSI           | Boston                      | [951d581270](https://linux-hardware.org/?probe=951d581270) | Feb 05, 2021 |
| Gigabyte      | AB350M-D3V-CF               | [38a9e8bdd4](https://linux-hardware.org/?probe=38a9e8bdd4) | Feb 05, 2021 |
| ASUSTek       | P7H55-M                     | [4a548dc93d](https://linux-hardware.org/?probe=4a548dc93d) | Feb 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | [449cccd96f](https://linux-hardware.org/?probe=449cccd96f) | Feb 04, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d6cb6e6165](https://linux-hardware.org/?probe=d6cb6e6165) | Feb 02, 2021 |
| Acer          | Veriton EX2620G             | [5910d11d96](https://linux-hardware.org/?probe=5910d11d96) | Feb 02, 2021 |
| Intel         | X99 V102A                   | [3e013f95b2](https://linux-hardware.org/?probe=3e013f95b2) | Feb 02, 2021 |
| MSI           | MS-7369                     | [c2f302e3a8](https://linux-hardware.org/?probe=c2f302e3a8) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM                    | [aab0858c5a](https://linux-hardware.org/?probe=aab0858c5a) | Feb 02, 2021 |
| Dell          | 0F373D A00                  | [fd104a556c](https://linux-hardware.org/?probe=fd104a556c) | Feb 02, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [a7bcd3dde6](https://linux-hardware.org/?probe=a7bcd3dde6) | Feb 02, 2021 |
| ASRock        | FM2A88X-ITX+                | [6783176d71](https://linux-hardware.org/?probe=6783176d71) | Feb 01, 2021 |
| Gigabyte      | 970A-DS3P                   | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| HP            | 1589                        | [9f0f12f814](https://linux-hardware.org/?probe=9f0f12f814) | Jan 31, 2021 |
| ASUSTek       | UN45                        | [076e620008](https://linux-hardware.org/?probe=076e620008) | Jan 31, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6994939b1d](https://linux-hardware.org/?probe=6994939b1d) | Jan 31, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [f334a52590](https://linux-hardware.org/?probe=f334a52590) | Jan 31, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [8b07b90352](https://linux-hardware.org/?probe=8b07b90352) | Jan 31, 2021 |
| ASRock        | 4CoreDual-VSTA              | [bb2ed11a08](https://linux-hardware.org/?probe=bb2ed11a08) | Jan 31, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6e7d00c1d9](https://linux-hardware.org/?probe=6e7d00c1d9) | Jan 31, 2021 |
| Gigabyte      | 970A-DS3P                   | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| ASRock        | 939NF6G-VSTA                | [c6097bdda4](https://linux-hardware.org/?probe=c6097bdda4) | Jan 30, 2021 |
| Intel         | DH67GD AAG10206-205         | [6c715227d3](https://linux-hardware.org/?probe=6c715227d3) | Jan 30, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [6ffd330855](https://linux-hardware.org/?probe=6ffd330855) | Jan 29, 2021 |
| ASRock        | FM2A88M-HD+                 | [fab91b3884](https://linux-hardware.org/?probe=fab91b3884) | Jan 29, 2021 |
| ASUSTek       | P5QPL-AM                    | [cc076d1a0a](https://linux-hardware.org/?probe=cc076d1a0a) | Jan 29, 2021 |
| Gigabyte      | F2A75M-D3H                  | [e3f0de09ce](https://linux-hardware.org/?probe=e3f0de09ce) | Jan 28, 2021 |
| Pegatron      | 2AB5                        | [3503b6f1fe](https://linux-hardware.org/?probe=3503b6f1fe) | Jan 28, 2021 |
| Medion        | H81M-E34                    | [fd62670499](https://linux-hardware.org/?probe=fd62670499) | Jan 28, 2021 |
| Medion        | H81M-E34                    | [8dd34b06cd](https://linux-hardware.org/?probe=8dd34b06cd) | Jan 28, 2021 |
| ASRock        | B85M DASH/OL R2.0           | [c1c5847225](https://linux-hardware.org/?probe=c1c5847225) | Jan 28, 2021 |
| ASUSTek       | Z170-P                      | [418c7ffce0](https://linux-hardware.org/?probe=418c7ffce0) | Jan 27, 2021 |
| ASUSTek       | P7H55-M                     | [39cfab59c1](https://linux-hardware.org/?probe=39cfab59c1) | Jan 27, 2021 |
| ASUSTek       | P7H55-M                     | [37675f6e80](https://linux-hardware.org/?probe=37675f6e80) | Jan 27, 2021 |
| ASUSTek       | P8H61-M LX2                 | [3e24489886](https://linux-hardware.org/?probe=3e24489886) | Jan 27, 2021 |
| ASUSTek       | P5KPL-SE                    | [4670e6e02f](https://linux-hardware.org/?probe=4670e6e02f) | Jan 27, 2021 |
| ASRock        | B460M-ITX/ac                | [6d401c805f](https://linux-hardware.org/?probe=6d401c805f) | Jan 27, 2021 |
| ASUSTek       | P7H55-M                     | [91c1996345](https://linux-hardware.org/?probe=91c1996345) | Jan 26, 2021 |
| Pegatron      | 2AB5                        | [faac4ce72a](https://linux-hardware.org/?probe=faac4ce72a) | Jan 26, 2021 |
| Pegatron      | 2AB5                        | [596191c549](https://linux-hardware.org/?probe=596191c549) | Jan 26, 2021 |
| Gigabyte      | F2A78M-DS2                  | [ae311c5753](https://linux-hardware.org/?probe=ae311c5753) | Jan 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [34cb18dd9a](https://linux-hardware.org/?probe=34cb18dd9a) | Jan 25, 2021 |
| ASUSTek       | P5QPL-AM                    | [5a79da6b85](https://linux-hardware.org/?probe=5a79da6b85) | Jan 24, 2021 |
| ASRock        | G41C-GS                     | [3f31619ae1](https://linux-hardware.org/?probe=3f31619ae1) | Jan 24, 2021 |
| ASRock        | G41C-GS                     | [b7141557eb](https://linux-hardware.org/?probe=b7141557eb) | Jan 24, 2021 |
| ASRock        | G41C-GS                     | [d18b91b397](https://linux-hardware.org/?probe=d18b91b397) | Jan 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a2454e8838](https://linux-hardware.org/?probe=a2454e8838) | Jan 24, 2021 |
| Biostar       | X370GT3                     | [737e7e535f](https://linux-hardware.org/?probe=737e7e535f) | Jan 24, 2021 |
| Gigabyte      | B460M DS3H                  | [2520198c21](https://linux-hardware.org/?probe=2520198c21) | Jan 24, 2021 |
| Pegatron      | 2ACF                        | [f046e35734](https://linux-hardware.org/?probe=f046e35734) | Jan 23, 2021 |
| HP            | 2AFE                        | [f9e753f06a](https://linux-hardware.org/?probe=f9e753f06a) | Jan 23, 2021 |
| eMachines     | EMCP73M                     | [e05d7446ca](https://linux-hardware.org/?probe=e05d7446ca) | Jan 23, 2021 |
| Dell          | 0R230R A00                  | [2e5d077900](https://linux-hardware.org/?probe=2e5d077900) | Jan 23, 2021 |
| Dell          | 0R230R A00                  | [d77b24fcf6](https://linux-hardware.org/?probe=d77b24fcf6) | Jan 23, 2021 |
| Packard Be... | MCP61DM2MA                  | [2e5c05be13](https://linux-hardware.org/?probe=2e5c05be13) | Jan 22, 2021 |
| ASUSTek       | H97-PLUS                    | [16aa8394b9](https://linux-hardware.org/?probe=16aa8394b9) | Jan 22, 2021 |
| Gigabyte      | 970A-DS3P                   | [7da289b0da](https://linux-hardware.org/?probe=7da289b0da) | Jan 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ce6127fa37](https://linux-hardware.org/?probe=ce6127fa37) | Jan 22, 2021 |
| ASUSTek       | PRIME H310M-A R2.0          | [49961d23ab](https://linux-hardware.org/?probe=49961d23ab) | Jan 21, 2021 |
| ASRock        | B250 Pro4                   | [11be188ad0](https://linux-hardware.org/?probe=11be188ad0) | Jan 21, 2021 |
| Gigabyte      | EP45-UD3LR                  | [577e4b805c](https://linux-hardware.org/?probe=577e4b805c) | Jan 20, 2021 |
| HP            | 0AACh                       | [b15932be81](https://linux-hardware.org/?probe=b15932be81) | Jan 20, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6da3f3a28](https://linux-hardware.org/?probe=e6da3f3a28) | Jan 20, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9f0a0ed303](https://linux-hardware.org/?probe=9f0a0ed303) | Jan 20, 2021 |
| ASUSTek       | M4A78LT-M                   | [222cc21390](https://linux-hardware.org/?probe=222cc21390) | Jan 20, 2021 |
| Pegatron      | 2AB5                        | [4b06224bf0](https://linux-hardware.org/?probe=4b06224bf0) | Jan 19, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d1cec92ce9](https://linux-hardware.org/?probe=d1cec92ce9) | Jan 19, 2021 |
| MSI           | MS-7025                     | [0c428ef80e](https://linux-hardware.org/?probe=0c428ef80e) | Jan 19, 2021 |
| MSI           | MS-7369                     | [150a31f864](https://linux-hardware.org/?probe=150a31f864) | Jan 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [33358fa215](https://linux-hardware.org/?probe=33358fa215) | Jan 18, 2021 |
| MSI           | 970 GAMING                  | [454cdc1cd3](https://linux-hardware.org/?probe=454cdc1cd3) | Jan 18, 2021 |
| MSI           | MS-7025                     | [454418f14e](https://linux-hardware.org/?probe=454418f14e) | Jan 18, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [e1b1ace23c](https://linux-hardware.org/?probe=e1b1ace23c) | Jan 18, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [58a18b8307](https://linux-hardware.org/?probe=58a18b8307) | Jan 18, 2021 |
| Intel         | DP965LT AAD41694-206        | [36ae23cf0b](https://linux-hardware.org/?probe=36ae23cf0b) | Jan 17, 2021 |
| MSI           | P45-C51                     | [5b67bdfc19](https://linux-hardware.org/?probe=5b67bdfc19) | Jan 17, 2021 |
| ASUSTek       | M2N-E                       | [6e33400fd7](https://linux-hardware.org/?probe=6e33400fd7) | Jan 17, 2021 |
| Gigabyte      | B75M-D3H                    | [b9f9eca8e5](https://linux-hardware.org/?probe=b9f9eca8e5) | Jan 16, 2021 |
| MSI           | MS-7025                     | [9a918a807f](https://linux-hardware.org/?probe=9a918a807f) | Jan 16, 2021 |
| HP            | 2129                        | [449a9223a3](https://linux-hardware.org/?probe=449a9223a3) | Jan 15, 2021 |
| ASUSTek       | P8H67-M                     | [d865d7e26e](https://linux-hardware.org/?probe=d865d7e26e) | Jan 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9e6ea2ee30](https://linux-hardware.org/?probe=9e6ea2ee30) | Jan 13, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [d02ae9455d](https://linux-hardware.org/?probe=d02ae9455d) | Jan 12, 2021 |
| Acer          | Aspire X3990                | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [ff86923105](https://linux-hardware.org/?probe=ff86923105) | Jan 11, 2021 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [efd9160db0](https://linux-hardware.org/?probe=efd9160db0) | Jan 11, 2021 |
| Dell          | 0GY6Y8 A03                  | [16cbc4a80e](https://linux-hardware.org/?probe=16cbc4a80e) | Jan 11, 2021 |
| HP            | 2AF3                        | [3f2cb9ee9f](https://linux-hardware.org/?probe=3f2cb9ee9f) | Jan 11, 2021 |
| ASRock        | 880GM-LE                    | [21afeee128](https://linux-hardware.org/?probe=21afeee128) | Jan 11, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [34a48cac4c](https://linux-hardware.org/?probe=34a48cac4c) | Jan 11, 2021 |
| Dell          | 06D7TR A00                  | [9f539e89f0](https://linux-hardware.org/?probe=9f539e89f0) | Jan 10, 2021 |
| ASUSTek       | PRIME B250-PRO              | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| ASUSTek       | P5Q DELUXE                  | [84e0ce2e7b](https://linux-hardware.org/?probe=84e0ce2e7b) | Jan 10, 2021 |
| Dell          | 06D7TR A00                  | [7d0183a5cc](https://linux-hardware.org/?probe=7d0183a5cc) | Jan 10, 2021 |
| ASRock        | 970 Extreme3 R2.0           | [58014b2267](https://linux-hardware.org/?probe=58014b2267) | Jan 10, 2021 |
| ASRock        | 970 Extreme3 R2.0           | [0a3600ee8e](https://linux-hardware.org/?probe=0a3600ee8e) | Jan 10, 2021 |
| Gigabyte      | H61M-S1                     | [7a797e4f57](https://linux-hardware.org/?probe=7a797e4f57) | Jan 10, 2021 |
| Gigabyte      | H310M H x.x                 | [241fca8d88](https://linux-hardware.org/?probe=241fca8d88) | Jan 09, 2021 |
| HP            | 3648h                       | [95ce8ac6d8](https://linux-hardware.org/?probe=95ce8ac6d8) | Jan 09, 2021 |
| ASUSTek       | P5KPL-SE                    | [b0547d2088](https://linux-hardware.org/?probe=b0547d2088) | Jan 09, 2021 |
| HP            | 2B46                        | [9fc7425e3d](https://linux-hardware.org/?probe=9fc7425e3d) | Jan 09, 2021 |
| ASUSTek       | CM6870                      | [8be9137cff](https://linux-hardware.org/?probe=8be9137cff) | Jan 08, 2021 |
| Gigabyte      | H310M H x.x                 | [93002aa7cb](https://linux-hardware.org/?probe=93002aa7cb) | Jan 07, 2021 |
| Gigabyte      | H310M H x.x                 | [43109f160f](https://linux-hardware.org/?probe=43109f160f) | Jan 07, 2021 |
| Biostar       | G41D3+                      | [a05601c5de](https://linux-hardware.org/?probe=a05601c5de) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [4e7d5b4879](https://linux-hardware.org/?probe=4e7d5b4879) | Jan 07, 2021 |
| ASRock        | H270 Pro4                   | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [5db133158d](https://linux-hardware.org/?probe=5db133158d) | Jan 06, 2021 |
| Acer          | Aspire TC-605               | [7c05356d53](https://linux-hardware.org/?probe=7c05356d53) | Jan 06, 2021 |
| HP            | 3048h                       | [4476c19b01](https://linux-hardware.org/?probe=4476c19b01) | Jan 03, 2021 |
| Gigabyte      | H77-DS3H                    | [a4b1543319](https://linux-hardware.org/?probe=a4b1543319) | Jan 03, 2021 |
| ASUSTek       | P5Q DELUXE                  | [0d86198fb4](https://linux-hardware.org/?probe=0d86198fb4) | Jan 03, 2021 |
| ASUSTek       | P5Q DELUXE                  | [dc098267a8](https://linux-hardware.org/?probe=dc098267a8) | Jan 03, 2021 |
| MSI           | B450-A PRO                  | [75c5106ead](https://linux-hardware.org/?probe=75c5106ead) | Jan 02, 2021 |
| MSI           | B450-A PRO                  | [38e0eb896d](https://linux-hardware.org/?probe=38e0eb896d) | Jan 02, 2021 |
| ASUSTek       | P5P41TD                     | [4f72243a54](https://linux-hardware.org/?probe=4f72243a54) | Jan 02, 2021 |
| HP            | 1497                        | [e7a4352647](https://linux-hardware.org/?probe=e7a4352647) | Jan 01, 2021 |
| HP            | 1497                        | [25218d0878](https://linux-hardware.org/?probe=25218d0878) | Jan 01, 2021 |
| ASUSTek       | P5KPL-SE                    | [e2cfacc3fd](https://linux-hardware.org/?probe=e2cfacc3fd) | Jan 01, 2021 |
| ASUSTek       | P5P41TD                     | [0f5165ce7f](https://linux-hardware.org/?probe=0f5165ce7f) | Dec 31, 2020 |
| HP            | 2B5E                        | [7778b6569b](https://linux-hardware.org/?probe=7778b6569b) | Dec 31, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e0f11c806](https://linux-hardware.org/?probe=1e0f11c806) | Dec 31, 2020 |
| Acer          | F690GVM                     | [c1e015108d](https://linux-hardware.org/?probe=c1e015108d) | Dec 30, 2020 |
| ASRock        | G41C-GS                     | [b88f5bb549](https://linux-hardware.org/?probe=b88f5bb549) | Dec 29, 2020 |
| ASUSTek       | P7H55-M                     | [b054eb3bdb](https://linux-hardware.org/?probe=b054eb3bdb) | Dec 29, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [cb0c5723ee](https://linux-hardware.org/?probe=cb0c5723ee) | Dec 29, 2020 |
| Gigabyte      | H310M S2H x.x               | [0164c1cfb6](https://linux-hardware.org/?probe=0164c1cfb6) | Dec 29, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [97448f5729](https://linux-hardware.org/?probe=97448f5729) | Dec 28, 2020 |
| HP            | 8653 A                      | [4bd6c2307c](https://linux-hardware.org/?probe=4bd6c2307c) | Dec 28, 2020 |
| ASUSTek       | PRIME A320M-K               | [cc4041e701](https://linux-hardware.org/?probe=cc4041e701) | Dec 28, 2020 |
| ASRock        | B450 Gaming K4              | [7cedc48cf7](https://linux-hardware.org/?probe=7cedc48cf7) | Dec 28, 2020 |
| MSI           | Z170A GAMING M5             | [3bba863bdc](https://linux-hardware.org/?probe=3bba863bdc) | Dec 28, 2020 |
| ASRock        | G41M-VS3                    | [849d5d66dd](https://linux-hardware.org/?probe=849d5d66dd) | Dec 28, 2020 |
| ASUSTek       | PRIME A320M-K               | [44883e9a94](https://linux-hardware.org/?probe=44883e9a94) | Dec 27, 2020 |
| ASUSTek       | PRIME A320M-K               | [2a09840862](https://linux-hardware.org/?probe=2a09840862) | Dec 27, 2020 |
| ASRock        | H81M-DG4                    | [f05367a2a9](https://linux-hardware.org/?probe=f05367a2a9) | Dec 27, 2020 |
| MSI           | Z270I GAMING PRO CARBON ... | [cebddd06ef](https://linux-hardware.org/?probe=cebddd06ef) | Dec 26, 2020 |
| ASRock        | G41C-S                      | [cc6d96677d](https://linux-hardware.org/?probe=cc6d96677d) | Dec 26, 2020 |
| Intel         | X99                         | [e7c73714c7](https://linux-hardware.org/?probe=e7c73714c7) | Dec 26, 2020 |
| Gigabyte      | 965P-DS4                    | [0ca9dd8b94](https://linux-hardware.org/?probe=0ca9dd8b94) | Dec 26, 2020 |
| ASUSTek       | H170 PRO GAMING             | [5ea602351f](https://linux-hardware.org/?probe=5ea602351f) | Dec 26, 2020 |
| Foxconn       | 2ADA                        | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| Biostar       | GF7050V-M7 SE               | [974a439cc4](https://linux-hardware.org/?probe=974a439cc4) | Dec 23, 2020 |
| HP            | 2ADC                        | [81d55608b8](https://linux-hardware.org/?probe=81d55608b8) | Dec 23, 2020 |
| Dell          | 042P49 A02                  | [76cdd69b4d](https://linux-hardware.org/?probe=76cdd69b4d) | Dec 23, 2020 |
| Dell          | 042P49 A02                  | [8cac85c675](https://linux-hardware.org/?probe=8cac85c675) | Dec 23, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4986f5040a](https://linux-hardware.org/?probe=4986f5040a) | Dec 23, 2020 |
| MSI           | A320M PRO-VD PLUS           | [eb1f0354f0](https://linux-hardware.org/?probe=eb1f0354f0) | Dec 23, 2020 |
| ASUSTek       | Leonite2                    | [a6d0f90420](https://linux-hardware.org/?probe=a6d0f90420) | Dec 23, 2020 |
| HP            | 2ADC                        | [1492d1cd69](https://linux-hardware.org/?probe=1492d1cd69) | Dec 22, 2020 |
| ASRock        | 990FX Professional          | [3d2c0caaaf](https://linux-hardware.org/?probe=3d2c0caaaf) | Dec 22, 2020 |
| ASRock        | N68-S                       | [fcc903e81f](https://linux-hardware.org/?probe=fcc903e81f) | Dec 22, 2020 |
| ASUSTek       | P8H61-MX USB3               | [4bd395ddd4](https://linux-hardware.org/?probe=4bd395ddd4) | Dec 22, 2020 |
| ASUSTek       | P8H61-MX USB3               | [b2af2dc8e1](https://linux-hardware.org/?probe=b2af2dc8e1) | Dec 22, 2020 |
| ASUSTek       | M3N78-EMH HDMI              | [72db0d0125](https://linux-hardware.org/?probe=72db0d0125) | Dec 20, 2020 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [9b4c82cd04](https://linux-hardware.org/?probe=9b4c82cd04) | Dec 20, 2020 |
| MSI           | B250M BAZOOKA               | [8630427e0f](https://linux-hardware.org/?probe=8630427e0f) | Dec 20, 2020 |
| Biostar       | GF7050V-M7 SE               | [f8b16e111c](https://linux-hardware.org/?probe=f8b16e111c) | Dec 19, 2020 |
| Lenovo        | MAHOBAY                     | [e5c7508173](https://linux-hardware.org/?probe=e5c7508173) | Dec 19, 2020 |
| HP            | 8459                        | [b5eb47ab31](https://linux-hardware.org/?probe=b5eb47ab31) | Dec 19, 2020 |
| Gigabyte      | F2A75M-D3H                  | [e244930a07](https://linux-hardware.org/?probe=e244930a07) | Dec 19, 2020 |
| ASUSTek       | P5GD1                       | [5a7acf0d43](https://linux-hardware.org/?probe=5a7acf0d43) | Dec 19, 2020 |
| Foxconn       | 2ABF                        | [6ece19775c](https://linux-hardware.org/?probe=6ece19775c) | Dec 18, 2020 |
| ASUSTek       | PRIME A320M-K               | [ebfbca84d4](https://linux-hardware.org/?probe=ebfbca84d4) | Dec 18, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [56d8809172](https://linux-hardware.org/?probe=56d8809172) | Dec 17, 2020 |
| ASUSTek       | Basswood                    | [7c56c0a8fa](https://linux-hardware.org/?probe=7c56c0a8fa) | Dec 17, 2020 |
| Wistron       | ProLiant ML110 G6           | [d865e0d758](https://linux-hardware.org/?probe=d865e0d758) | Dec 17, 2020 |
| Wistron       | ProLiant ML110 G6           | [ee22201e3c](https://linux-hardware.org/?probe=ee22201e3c) | Dec 17, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [4743f200f7](https://linux-hardware.org/?probe=4743f200f7) | Dec 16, 2020 |
| ASUSTek       | P7H55-M                     | [1552511aae](https://linux-hardware.org/?probe=1552511aae) | Dec 16, 2020 |
| ASUSTek       | P7H55-M                     | [099c39f097](https://linux-hardware.org/?probe=099c39f097) | Dec 16, 2020 |
| Acer          | FIH57                       | [fce988e698](https://linux-hardware.org/?probe=fce988e698) | Dec 16, 2020 |
| Intel         | DB65AL AAG12530-310         | [4116c02e66](https://linux-hardware.org/?probe=4116c02e66) | Dec 16, 2020 |
| ASRock        | B550 Phantom Gaming-ITX/... | [61e3659f55](https://linux-hardware.org/?probe=61e3659f55) | Dec 15, 2020 |
| Intel         | DP55WB AAE64798-206         | [86ac31c5bc](https://linux-hardware.org/?probe=86ac31c5bc) | Dec 15, 2020 |
| Intel         | DP55WB AAE64798-206         | [80bdd13fee](https://linux-hardware.org/?probe=80bdd13fee) | Dec 15, 2020 |
| MSI           | B250M BAZOOKA               | [35ed33a3a6](https://linux-hardware.org/?probe=35ed33a3a6) | Dec 15, 2020 |
| HP            | 2B28                        | [896a921ff8](https://linux-hardware.org/?probe=896a921ff8) | Dec 15, 2020 |
| HP            | 2B28                        | [ed223f8b74](https://linux-hardware.org/?probe=ed223f8b74) | Dec 15, 2020 |
| Clevo         | L390T                       | [fe920018c7](https://linux-hardware.org/?probe=fe920018c7) | Dec 15, 2020 |
| MSI           | MS-7369                     | [4c4ea0775a](https://linux-hardware.org/?probe=4c4ea0775a) | Dec 15, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [bb8fbc85b2](https://linux-hardware.org/?probe=bb8fbc85b2) | Dec 15, 2020 |
| ASRock        | Z170 Pro4S                  | [e1c94d7cd8](https://linux-hardware.org/?probe=e1c94d7cd8) | Dec 14, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | [1b09a29231](https://linux-hardware.org/?probe=1b09a29231) | Dec 14, 2020 |
| HP            | 198E                        | [bdc804bed3](https://linux-hardware.org/?probe=bdc804bed3) | Dec 14, 2020 |
| ASUSTek       | Z97-K R2.0                  | [b8a7f3c172](https://linux-hardware.org/?probe=b8a7f3c172) | Dec 13, 2020 |
| Dell          | 09KPNV A01                  | [46d3f40433](https://linux-hardware.org/?probe=46d3f40433) | Dec 13, 2020 |
| ASUSTek       | P5KPL-SE                    | [0c7e08c60b](https://linux-hardware.org/?probe=0c7e08c60b) | Dec 13, 2020 |
| ASRock        | H110M-ITX                   | [9e1bfa9957](https://linux-hardware.org/?probe=9e1bfa9957) | Dec 13, 2020 |
| ASUSTek       | PRIME H410M-K               | [f20c2d0552](https://linux-hardware.org/?probe=f20c2d0552) | Dec 12, 2020 |
| ASUSTek       | P5GD1                       | [99cca54b2e](https://linux-hardware.org/?probe=99cca54b2e) | Dec 12, 2020 |
| ASRock        | B365 Pro4                   | [fa0e224b0d](https://linux-hardware.org/?probe=fa0e224b0d) | Dec 12, 2020 |
| ASUSTek       | V-P7H55E                    | [ab830cc2f1](https://linux-hardware.org/?probe=ab830cc2f1) | Dec 11, 2020 |
| ASUSTek       | PRIME Z370-P II             | [06a9e07fd7](https://linux-hardware.org/?probe=06a9e07fd7) | Dec 11, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [f24affd04f](https://linux-hardware.org/?probe=f24affd04f) | Dec 11, 2020 |
| EVGA          | Classified SR-2 X58         | [0dcf21f1e7](https://linux-hardware.org/?probe=0dcf21f1e7) | Dec 10, 2020 |
| Pegatron      | BOWIE                       | [40f3ca1c9b](https://linux-hardware.org/?probe=40f3ca1c9b) | Dec 10, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0a73a1cecf](https://linux-hardware.org/?probe=0a73a1cecf) | Dec 10, 2020 |
| Intel         | DB65AL AAG12530-310         | [0d55d21a8f](https://linux-hardware.org/?probe=0d55d21a8f) | Dec 10, 2020 |
| ASUSTek       | P5KPL-SE                    | [3cad7b72d4](https://linux-hardware.org/?probe=3cad7b72d4) | Dec 10, 2020 |
| Dell          | 0J3C2F A00                  | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| Gigabyte      | F2A75M-D3H                  | [4d56696368](https://linux-hardware.org/?probe=4d56696368) | Dec 09, 2020 |
| ASRock        | H55M Pro                    | [aecd729ae4](https://linux-hardware.org/?probe=aecd729ae4) | Dec 09, 2020 |
| ASUSTek       | V-P7H55E                    | [dcc0a47a6b](https://linux-hardware.org/?probe=dcc0a47a6b) | Dec 09, 2020 |
| HP            | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |
| ASUSTek       | M5A97                       | [540f25b6a7](https://linux-hardware.org/?probe=540f25b6a7) | Dec 08, 2020 |
| ASRock        | H55M Pro                    | [ddbb1b1bfc](https://linux-hardware.org/?probe=ddbb1b1bfc) | Dec 08, 2020 |
| Acer          | Veriton X2610G              | [90886662bd](https://linux-hardware.org/?probe=90886662bd) | Dec 08, 2020 |
| Foxconn       | 2ABF                        | [048af32bdd](https://linux-hardware.org/?probe=048af32bdd) | Dec 08, 2020 |
| Dell          | 0F1262                      | [90378abac3](https://linux-hardware.org/?probe=90378abac3) | Dec 08, 2020 |
| Dell          | 0F1262                      | [63e64577e4](https://linux-hardware.org/?probe=63e64577e4) | Dec 08, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [910a8c0514](https://linux-hardware.org/?probe=910a8c0514) | Dec 08, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [4fec34daaf](https://linux-hardware.org/?probe=4fec34daaf) | Dec 08, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [c381251f06](https://linux-hardware.org/?probe=c381251f06) | Dec 08, 2020 |
| Dell          | 0RW199                      | [635a5a5449](https://linux-hardware.org/?probe=635a5a5449) | Dec 07, 2020 |
| ASUSTek       | M5A97 R2.0                  | [f1cd497947](https://linux-hardware.org/?probe=f1cd497947) | Dec 07, 2020 |
| Gigabyte      | H77-DS3H                    | [04346614fa](https://linux-hardware.org/?probe=04346614fa) | Dec 07, 2020 |
| Gigabyte      | H77-DS3H                    | [03c7283a19](https://linux-hardware.org/?probe=03c7283a19) | Dec 07, 2020 |
| Sapphire      | PI-AM3RS785G                | [dea28c98e7](https://linux-hardware.org/?probe=dea28c98e7) | Dec 06, 2020 |
| Dell          | 0KP561                      | [cbbc323d4c](https://linux-hardware.org/?probe=cbbc323d4c) | Dec 06, 2020 |
| Dell          | 0KP561                      | [070bfb2894](https://linux-hardware.org/?probe=070bfb2894) | Dec 06, 2020 |
| ASUSTek       | PRIME B450M-K               | [5af5f92a13](https://linux-hardware.org/?probe=5af5f92a13) | Dec 06, 2020 |
| ASUSTek       | PRIME B450M-K               | [a03a13da0f](https://linux-hardware.org/?probe=a03a13da0f) | Dec 06, 2020 |
| ASRock        | Z370M-ITX/ac                | [3997021d7c](https://linux-hardware.org/?probe=3997021d7c) | Dec 05, 2020 |
| MSI           | B450-A PRO MAX              | [49d076693b](https://linux-hardware.org/?probe=49d076693b) | Dec 05, 2020 |
| ASUSTek       | H81M-PLUS                   | [2b112b3bc2](https://linux-hardware.org/?probe=2b112b3bc2) | Dec 05, 2020 |
| Gigabyte      | AB350M-DS3H-CF              | [4e2f0f47dd](https://linux-hardware.org/?probe=4e2f0f47dd) | Dec 05, 2020 |
| Dell          | 09KPNV A01                  | [7615b677f1](https://linux-hardware.org/?probe=7615b677f1) | Dec 05, 2020 |
| ASRock        | Z97 Pro4                    | [dddc399946](https://linux-hardware.org/?probe=dddc399946) | Dec 05, 2020 |
| Gigabyte      | X570 AORUS PRO              | [733bb2971a](https://linux-hardware.org/?probe=733bb2971a) | Dec 05, 2020 |
| HP            | 1495                        | [5fcb2c848a](https://linux-hardware.org/?probe=5fcb2c848a) | Dec 04, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [ba02c398cd](https://linux-hardware.org/?probe=ba02c398cd) | Dec 04, 2020 |
| ASRock        | 775Dual-VSTA                | [b226a3533a](https://linux-hardware.org/?probe=b226a3533a) | Dec 04, 2020 |
| ASRock        | B365 Pro4                   | [99561a0b41](https://linux-hardware.org/?probe=99561a0b41) | Dec 04, 2020 |
| MSI           | 2A9C                        | [6ec88ebfd5](https://linux-hardware.org/?probe=6ec88ebfd5) | Dec 04, 2020 |
| Lenovo        | MAHOBAY                     | [8f4652139b](https://linux-hardware.org/?probe=8f4652139b) | Dec 04, 2020 |
| Gigabyte      | Z370P D3-CF                 | [5f32a51b25](https://linux-hardware.org/?probe=5f32a51b25) | Dec 03, 2020 |
| Acer          | EG43M                       | [25d693e97e](https://linux-hardware.org/?probe=25d693e97e) | Dec 03, 2020 |
| ASUSTek       | P7H55-M                     | [797544586e](https://linux-hardware.org/?probe=797544586e) | Dec 03, 2020 |
| HP            | 8459                        | [3755e58561](https://linux-hardware.org/?probe=3755e58561) | Dec 03, 2020 |
| Intel         | D54250WYK H13922-303        | [334440444a](https://linux-hardware.org/?probe=334440444a) | Dec 03, 2020 |
| Gigabyte      | Z370P D3-CF                 | [9149b65713](https://linux-hardware.org/?probe=9149b65713) | Dec 02, 2020 |
| MSI           | H110M PRO-VD                | [d60f6af679](https://linux-hardware.org/?probe=d60f6af679) | Dec 02, 2020 |
| HP            | 198E                        | [29688e066f](https://linux-hardware.org/?probe=29688e066f) | Dec 02, 2020 |
| ASUSTek       | M3A78                       | [f6b55f7969](https://linux-hardware.org/?probe=f6b55f7969) | Dec 01, 2020 |
| ASRock        | B450M Pro4-F                | [1e395f258f](https://linux-hardware.org/?probe=1e395f258f) | Dec 01, 2020 |
| MSI           | B450-A PRO MAX              | [b66e3a8fe3](https://linux-hardware.org/?probe=b66e3a8fe3) | Dec 01, 2020 |
| Intel         | DP55WB AAE64798-206         | [72330be67d](https://linux-hardware.org/?probe=72330be67d) | Nov 30, 2020 |
| MSI           | B450M PRO-VDH MAX           | [9f4b9ffcaf](https://linux-hardware.org/?probe=9f4b9ffcaf) | Nov 30, 2020 |
| MSI           | B450M PRO-VDH MAX           | [1440a56bea](https://linux-hardware.org/?probe=1440a56bea) | Nov 30, 2020 |
| Intel         | DP55WB AAE64798-206         | [3fbfbe0a79](https://linux-hardware.org/?probe=3fbfbe0a79) | Nov 29, 2020 |
| MSI           | B450M PRO-VDH MAX           | [7bc78d3081](https://linux-hardware.org/?probe=7bc78d3081) | Nov 29, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [7ab01a639c](https://linux-hardware.org/?probe=7ab01a639c) | Nov 29, 2020 |
| Acer          | EG31M P01-A0                | [eb454eff52](https://linux-hardware.org/?probe=eb454eff52) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| ASRock        | AB350 Pro4                  | [b483575230](https://linux-hardware.org/?probe=b483575230) | Nov 29, 2020 |
| ASUSTek       | Maximus V EXTREME           | [c93e0ae0be](https://linux-hardware.org/?probe=c93e0ae0be) | Nov 29, 2020 |
| Gigabyte      | P35-DS3R                    | [2ebb03f2c6](https://linux-hardware.org/?probe=2ebb03f2c6) | Nov 29, 2020 |
| HP            | 198E                        | [6aa754112f](https://linux-hardware.org/?probe=6aa754112f) | Nov 28, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0a6c332847](https://linux-hardware.org/?probe=0a6c332847) | Nov 28, 2020 |
| ASUSTek       | H81M-PLUS                   | [273ff7166e](https://linux-hardware.org/?probe=273ff7166e) | Nov 27, 2020 |
| ASUSTek       | H81M-PLUS                   | [27e030ad5f](https://linux-hardware.org/?probe=27e030ad5f) | Nov 27, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [17dc6fdc48](https://linux-hardware.org/?probe=17dc6fdc48) | Nov 27, 2020 |
| ASRock        | 990FX Professional          | [fb773aef22](https://linux-hardware.org/?probe=fb773aef22) | Nov 27, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [cb176e711f](https://linux-hardware.org/?probe=cb176e711f) | Nov 27, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [0d3e1f7192](https://linux-hardware.org/?probe=0d3e1f7192) | Nov 26, 2020 |
| ASRock        | G31M-S                      | [95e5057598](https://linux-hardware.org/?probe=95e5057598) | Nov 26, 2020 |
| ASRock        | 4Core1600-GLAN              | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| MSI           | B450M PRO-VDH MAX           | [45d7b325d6](https://linux-hardware.org/?probe=45d7b325d6) | Nov 24, 2020 |
| HP            | 2820h                       | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| Fujitsu Si... | P5GD1-FM                    | [8473e30bdd](https://linux-hardware.org/?probe=8473e30bdd) | Nov 23, 2020 |
| ASUSTek       | P5G41T-M LE                 | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE                 | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [3993d4bbbc](https://linux-hardware.org/?probe=3993d4bbbc) | Nov 22, 2020 |
| Gigabyte      | H97-D3H-CF                  | [e7073d9128](https://linux-hardware.org/?probe=e7073d9128) | Nov 22, 2020 |
| Gigabyte      | H97-D3H-CF                  | [0eefb83237](https://linux-hardware.org/?probe=0eefb83237) | Nov 22, 2020 |
| Gigabyte      | B360M DS3H                  | [4854b3a89f](https://linux-hardware.org/?probe=4854b3a89f) | Nov 22, 2020 |
| Pegatron      | Benicia                     | [5022820b4c](https://linux-hardware.org/?probe=5022820b4c) | Nov 22, 2020 |
| ASUSTek       | Maximus V EXTREME           | [925ec1c4fd](https://linux-hardware.org/?probe=925ec1c4fd) | Nov 22, 2020 |
| ASUSTek       | P6T                         | [476ca12d7b](https://linux-hardware.org/?probe=476ca12d7b) | Nov 22, 2020 |
| ASUSTek       | Leonite2                    | [da73ca2135](https://linux-hardware.org/?probe=da73ca2135) | Nov 22, 2020 |
| ASUSTek       | M2N-MX                      | [28a1700f96](https://linux-hardware.org/?probe=28a1700f96) | Nov 21, 2020 |
| ASUSTek       | PRIME Z370-P II             | [8acf76cf5c](https://linux-hardware.org/?probe=8acf76cf5c) | Nov 21, 2020 |
| ASUSTek       | PRIME Z370-P II             | [5ee3f37ae3](https://linux-hardware.org/?probe=5ee3f37ae3) | Nov 21, 2020 |
| ASRock        | 890GM Pro3 R2.0             | [8660008e9a](https://linux-hardware.org/?probe=8660008e9a) | Nov 21, 2020 |
| HP            | 304Ah                       | [94ae3f54d1](https://linux-hardware.org/?probe=94ae3f54d1) | Nov 20, 2020 |
| HP            | 304Ah                       | [b2aad1ea8f](https://linux-hardware.org/?probe=b2aad1ea8f) | Nov 20, 2020 |
| Lenovo        | MAHOBAY NOK                 | [72927d0fcf](https://linux-hardware.org/?probe=72927d0fcf) | Nov 20, 2020 |
| ASUSTek       | P8H61-M LX2 R2.0            | [44f1b006e2](https://linux-hardware.org/?probe=44f1b006e2) | Nov 20, 2020 |
| ASRock        | Q1900M                      | [2d0b876209](https://linux-hardware.org/?probe=2d0b876209) | Nov 20, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [16946154fb](https://linux-hardware.org/?probe=16946154fb) | Nov 20, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [2426b5aa5d](https://linux-hardware.org/?probe=2426b5aa5d) | Nov 20, 2020 |
| ABIT          | IP35 Pro                    | [6f3779061d](https://linux-hardware.org/?probe=6f3779061d) | Nov 20, 2020 |
| ASUSTek       | Maximus VI HERO             | [5c82deb589](https://linux-hardware.org/?probe=5c82deb589) | Nov 19, 2020 |
| Packard Be... | WMCP78M                     | [1e2c0c3bba](https://linux-hardware.org/?probe=1e2c0c3bba) | Nov 19, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [6d885b58e3](https://linux-hardware.org/?probe=6d885b58e3) | Nov 19, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [9e7ed21896](https://linux-hardware.org/?probe=9e7ed21896) | Nov 19, 2020 |
| ASUSTek       | PRIME B250-PLUS             | [54a29849d1](https://linux-hardware.org/?probe=54a29849d1) | Nov 19, 2020 |
| Lenovo        | Board                       | [d4ed53af3a](https://linux-hardware.org/?probe=d4ed53af3a) | Nov 18, 2020 |
| ASRock        | H110M-HDV                   | [d7b5f7e755](https://linux-hardware.org/?probe=d7b5f7e755) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [51d5cdb6e0](https://linux-hardware.org/?probe=51d5cdb6e0) | Nov 18, 2020 |
| ASUSTek       | KFSN4-DRE/RS161             | [993ad878de](https://linux-hardware.org/?probe=993ad878de) | Nov 18, 2020 |
| ASUSTek       | KFSN4-DRE/RS161             | [7efab423c1](https://linux-hardware.org/?probe=7efab423c1) | Nov 18, 2020 |
| ASUSTek       | KFSN4-DRE/RS161             | [dcdbcbc3e0](https://linux-hardware.org/?probe=dcdbcbc3e0) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [629de7ba17](https://linux-hardware.org/?probe=629de7ba17) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [1d03694366](https://linux-hardware.org/?probe=1d03694366) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [abae415b73](https://linux-hardware.org/?probe=abae415b73) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [d647a8e806](https://linux-hardware.org/?probe=d647a8e806) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [7e476adc3f](https://linux-hardware.org/?probe=7e476adc3f) | Nov 18, 2020 |
| Supermicro    | H8DM8-2                     | [c1591cf9d0](https://linux-hardware.org/?probe=c1591cf9d0) | Nov 18, 2020 |
| TYAN Compu... | S3992-E                     | [268b57c4f4](https://linux-hardware.org/?probe=268b57c4f4) | Nov 18, 2020 |
| TYAN Compu... | S3992-E                     | [ad10a59447](https://linux-hardware.org/?probe=ad10a59447) | Nov 18, 2020 |
| TYAN Compu... | S3992-E                     | [0bfb1fe339](https://linux-hardware.org/?probe=0bfb1fe339) | Nov 18, 2020 |
| TYAN Compu... | S8230                       | [c761d2a512](https://linux-hardware.org/?probe=c761d2a512) | Nov 18, 2020 |
| TYAN Compu... | S8230                       | [d3ecc95b54](https://linux-hardware.org/?probe=d3ecc95b54) | Nov 18, 2020 |
| Supermicro    | H8DI3+                      | [cdbfbfdd91](https://linux-hardware.org/?probe=cdbfbfdd91) | Nov 18, 2020 |
| ASUSTek       | Leonite2                    | [228667efee](https://linux-hardware.org/?probe=228667efee) | Nov 17, 2020 |
| Supermicro    | H8DI3+                      | [c163123358](https://linux-hardware.org/?probe=c163123358) | Nov 17, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [fd299b0592](https://linux-hardware.org/?probe=fd299b0592) | Nov 17, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [df1c6b016b](https://linux-hardware.org/?probe=df1c6b016b) | Nov 17, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [a1b9161d48](https://linux-hardware.org/?probe=a1b9161d48) | Nov 16, 2020 |
| Pegatron      | 2A94h                       | [bebfc490ab](https://linux-hardware.org/?probe=bebfc490ab) | Nov 16, 2020 |
| HP            | 09F8h                       | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| ASUSTek       | Leonite2                    | [78122e2426](https://linux-hardware.org/?probe=78122e2426) | Nov 16, 2020 |
| ASRock        | N68C-S UCC                  | [3232d78ba4](https://linux-hardware.org/?probe=3232d78ba4) | Nov 16, 2020 |
| ASUSTek       | Leonite2                    | [efd44b6309](https://linux-hardware.org/?probe=efd44b6309) | Nov 15, 2020 |
| Acer          | FIH57                       | [87dd6423cd](https://linux-hardware.org/?probe=87dd6423cd) | Nov 15, 2020 |
| Acer          | Aspire X3990                | [2e0c343e2d](https://linux-hardware.org/?probe=2e0c343e2d) | Nov 15, 2020 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [f8a0dc0c6c](https://linux-hardware.org/?probe=f8a0dc0c6c) | Nov 15, 2020 |
| MSI           | 0A90                        | [a6831b8f30](https://linux-hardware.org/?probe=a6831b8f30) | Nov 15, 2020 |
| Acer          | EG31M P01-A0                | [b055d24a18](https://linux-hardware.org/?probe=b055d24a18) | Nov 14, 2020 |
| IBM           | 8183V6D                     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ASRock        | FM2A88X-ITX+                | [5f21f534ef](https://linux-hardware.org/?probe=5f21f534ef) | Nov 14, 2020 |
| Packard Be... | H57M01                      | [37144ffe6e](https://linux-hardware.org/?probe=37144ffe6e) | Nov 13, 2020 |
| ASUSTek       | H81M-C                      | [565b80c506](https://linux-hardware.org/?probe=565b80c506) | Nov 12, 2020 |
| ASUSTek       | A88XM-E                     | [52b7c8a912](https://linux-hardware.org/?probe=52b7c8a912) | Nov 12, 2020 |
| ASUSTek       | H81M-C                      | [2c7441d190](https://linux-hardware.org/?probe=2c7441d190) | Nov 12, 2020 |
| ASUSTek       | PRIME B250-PLUS             | [e4b0348a15](https://linux-hardware.org/?probe=e4b0348a15) | Nov 12, 2020 |
| MSI           | X570-A PRO                  | [3d28186c29](https://linux-hardware.org/?probe=3d28186c29) | Nov 12, 2020 |
| Fujitsu       | D3403-B1 S26361-D3403-B1    | [a960aef3ae](https://linux-hardware.org/?probe=a960aef3ae) | Nov 11, 2020 |
| HP            | 86E9 A                      | [a6bdc589f5](https://linux-hardware.org/?probe=a6bdc589f5) | Nov 11, 2020 |
| Packard Be... | MCP73VT-PM                  | [cbc5eb625b](https://linux-hardware.org/?probe=cbc5eb625b) | Nov 11, 2020 |
| Packard Be... | P5N-E SLI                   | [be9e616b08](https://linux-hardware.org/?probe=be9e616b08) | Nov 10, 2020 |
| ASUSTek       | PRIME X570-P                | [798cae3014](https://linux-hardware.org/?probe=798cae3014) | Nov 10, 2020 |
| MSI           | 870A-G54                    | [8b8d7d6bf8](https://linux-hardware.org/?probe=8b8d7d6bf8) | Nov 09, 2020 |
| Gigabyte      | 990XA-UD3                   | [6ca931347b](https://linux-hardware.org/?probe=6ca931347b) | Nov 09, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [0cf4a191cd](https://linux-hardware.org/?probe=0cf4a191cd) | Nov 09, 2020 |
| Acer          | Veriton M275                | [823573b508](https://linux-hardware.org/?probe=823573b508) | Nov 08, 2020 |
| Lenovo        | MAHOBAY NOK                 | [25538c089f](https://linux-hardware.org/?probe=25538c089f) | Nov 08, 2020 |
| ASRock        | N68C-S UCC                  | [35d9993cdc](https://linux-hardware.org/?probe=35d9993cdc) | Nov 08, 2020 |
| ASUSTek       | Z87-K                       | [f4328192d9](https://linux-hardware.org/?probe=f4328192d9) | Nov 08, 2020 |
| Unknown       | Intel X79                   | [18497be397](https://linux-hardware.org/?probe=18497be397) | Nov 08, 2020 |
| Unknown       | Intel X79                   | [fcea813710](https://linux-hardware.org/?probe=fcea813710) | Nov 08, 2020 |
| Gigabyte      | H310M H x.x                 | [2a339d856a](https://linux-hardware.org/?probe=2a339d856a) | Nov 08, 2020 |
| HP            | 1998                        | [437a5584ed](https://linux-hardware.org/?probe=437a5584ed) | Nov 08, 2020 |
| ASRock        | G31M-S                      | [dd2ce31e02](https://linux-hardware.org/?probe=dd2ce31e02) | Nov 08, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [c955e14b30](https://linux-hardware.org/?probe=c955e14b30) | Nov 08, 2020 |
| Gigabyte      | EX58-UD5                    | [230ca41ab6](https://linux-hardware.org/?probe=230ca41ab6) | Nov 08, 2020 |
| ASUSTek       | A8R32-MVP Deluxe            | [648ea0ecfc](https://linux-hardware.org/?probe=648ea0ecfc) | Nov 07, 2020 |
| Acer          | EG31M P01-A0                | [64c959aef6](https://linux-hardware.org/?probe=64c959aef6) | Nov 07, 2020 |
| Acer          | EG31M P01-A0                | [5c7295f0a1](https://linux-hardware.org/?probe=5c7295f0a1) | Nov 07, 2020 |
| ASUSTek       | H97-PLUS                    | [041523b28a](https://linux-hardware.org/?probe=041523b28a) | Nov 07, 2020 |
| Packard Be... | WMCP78M                     | [f21e854cee](https://linux-hardware.org/?probe=f21e854cee) | Nov 07, 2020 |
| ASRock        | H67M-ITX/HT                 | [6d6253736c](https://linux-hardware.org/?probe=6d6253736c) | Nov 06, 2020 |
| ASRock        | B450M-HDV R4.0              | [014846f9a3](https://linux-hardware.org/?probe=014846f9a3) | Nov 06, 2020 |
| HP            | 0A58h                       | [7e4ce13808](https://linux-hardware.org/?probe=7e4ce13808) | Nov 06, 2020 |
| ASRock        | 4Core1600-GLAN              | [e6edfc8360](https://linux-hardware.org/?probe=e6edfc8360) | Nov 06, 2020 |
| Gigabyte      | H310M H x.x                 | [5e93101af2](https://linux-hardware.org/?probe=5e93101af2) | Nov 06, 2020 |
| Wistron       | ProLiant ML110 G6           | [841ca791c1](https://linux-hardware.org/?probe=841ca791c1) | Nov 05, 2020 |
| HP            | 0A58h                       | [5375959148](https://linux-hardware.org/?probe=5375959148) | Nov 05, 2020 |
| ASUSTek       | Z170M-PLUS                  | [436e8c5ead](https://linux-hardware.org/?probe=436e8c5ead) | Nov 05, 2020 |
| ASUSTek       | Z170M-PLUS                  | [4a14036d89](https://linux-hardware.org/?probe=4a14036d89) | Nov 05, 2020 |
| Gigabyte      | 970A-DS3P                   | [e993445a95](https://linux-hardware.org/?probe=e993445a95) | Nov 05, 2020 |
| ASRock        | H67M-ITX/HT                 | [97deca845c](https://linux-hardware.org/?probe=97deca845c) | Nov 05, 2020 |
| ASUSTek       | H97-PLUS                    | [b96127d9ca](https://linux-hardware.org/?probe=b96127d9ca) | Nov 05, 2020 |
| Intel         | DX48BT2 AAE26191-207        | [cbf8e3b6c7](https://linux-hardware.org/?probe=cbf8e3b6c7) | Nov 05, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [0c7c43397a](https://linux-hardware.org/?probe=0c7c43397a) | Nov 04, 2020 |
| Fujitsu Si... | P5GD1-FM                    | [71495035b8](https://linux-hardware.org/?probe=71495035b8) | Nov 04, 2020 |
| ASUSTek       | Z87-C                       | [5c78f5aa4b](https://linux-hardware.org/?probe=5c78f5aa4b) | Nov 04, 2020 |
| Pegatron      | 2A99                        | [5215de685e](https://linux-hardware.org/?probe=5215de685e) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | [2139a80238](https://linux-hardware.org/?probe=2139a80238) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [51e32470f3](https://linux-hardware.org/?probe=51e32470f3) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [e8e4d91e96](https://linux-hardware.org/?probe=e8e4d91e96) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [26041c308a](https://linux-hardware.org/?probe=26041c308a) | Nov 03, 2020 |
| ASRock        | 4CoreDual-SATA2             | [3bfd42e25e](https://linux-hardware.org/?probe=3bfd42e25e) | Nov 03, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | [d50246d128](https://linux-hardware.org/?probe=d50246d128) | Nov 03, 2020 |
| Gigabyte      | 945GZM-S2                   | [b2df27738c](https://linux-hardware.org/?probe=b2df27738c) | Nov 03, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | [190dc9fd32](https://linux-hardware.org/?probe=190dc9fd32) | Nov 02, 2020 |
| IBM           | 8183V6D                     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Acer          | Aspire MC605 v1.0           | [a8285944df](https://linux-hardware.org/?probe=a8285944df) | Nov 02, 2020 |
| HP            | 0A58h                       | [796cd4ef09](https://linux-hardware.org/?probe=796cd4ef09) | Nov 02, 2020 |
| Pegatron      | 2A99                        | [cb57d7ec0d](https://linux-hardware.org/?probe=cb57d7ec0d) | Nov 01, 2020 |
| ASUSTek       | X99-A/USB                   | [9b9bac781d](https://linux-hardware.org/?probe=9b9bac781d) | Nov 01, 2020 |
| ASUSTek       | F2A85-M LE                  | [b197e3e4cc](https://linux-hardware.org/?probe=b197e3e4cc) | Nov 01, 2020 |
| ASRock        | B450M-HDV R4.0              | [248756f9c0](https://linux-hardware.org/?probe=248756f9c0) | Nov 01, 2020 |
| ASRock        | B450M-HDV R4.0              | [b7aecdaa6e](https://linux-hardware.org/?probe=b7aecdaa6e) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| ASUSTek       | P5K PRO                     | [6067c97f8f](https://linux-hardware.org/?probe=6067c97f8f) | Nov 01, 2020 |
| Acer          | Aspire TC-605               | [341fd321c2](https://linux-hardware.org/?probe=341fd321c2) | Nov 01, 2020 |
| Dell          | 0KP561                      | [8f31ea50ed](https://linux-hardware.org/?probe=8f31ea50ed) | Oct 31, 2020 |
| MSI           | B250 GAMING M3              | [07e2abf8db](https://linux-hardware.org/?probe=07e2abf8db) | Oct 31, 2020 |
| ASRock        | B460M-ITX/ac                | [9974585b86](https://linux-hardware.org/?probe=9974585b86) | Oct 31, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [c09451097d](https://linux-hardware.org/?probe=c09451097d) | Oct 31, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [dbed707ded](https://linux-hardware.org/?probe=dbed707ded) | Oct 30, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [0af79f0761](https://linux-hardware.org/?probe=0af79f0761) | Oct 30, 2020 |
| Gigabyte      | EX58-UD5                    | [4b457110b3](https://linux-hardware.org/?probe=4b457110b3) | Oct 30, 2020 |
| MSI           | B250M BAZOOKA               | [496a5ca5d8](https://linux-hardware.org/?probe=496a5ca5d8) | Oct 29, 2020 |
| Gigabyte      | GA-870A-USB3                | [213ab86014](https://linux-hardware.org/?probe=213ab86014) | Oct 28, 2020 |
| Fujitsu Si... | P5GD1-FM                    | [23f70182fd](https://linux-hardware.org/?probe=23f70182fd) | Oct 28, 2020 |
| Fujitsu Si... | P5GD1-FM                    | [bae48146c3](https://linux-hardware.org/?probe=bae48146c3) | Oct 28, 2020 |
| ASUSTek       | PRIME A320M-K               | [580695e51d](https://linux-hardware.org/?probe=580695e51d) | Oct 27, 2020 |
| Fujitsu Si... | D2594-A1 S26361-D2594-A1    | [64b720d5dc](https://linux-hardware.org/?probe=64b720d5dc) | Oct 26, 2020 |
| Fujitsu Si... | D2594-A1 S26361-D2594-A1    | [1ea42061f4](https://linux-hardware.org/?probe=1ea42061f4) | Oct 26, 2020 |
| ASUSTek       | H81M-K                      | [3eb760827a](https://linux-hardware.org/?probe=3eb760827a) | Oct 26, 2020 |
| ASUSTek       | Maximus V EXTREME           | [9cbc236515](https://linux-hardware.org/?probe=9cbc236515) | Oct 25, 2020 |
| Acer          | JM11-MS                     | [069625e15a](https://linux-hardware.org/?probe=069625e15a) | Oct 25, 2020 |
| Packard Be... | P5N-E SLI                   | [1e7cd8cd35](https://linux-hardware.org/?probe=1e7cd8cd35) | Oct 24, 2020 |
| ASUSTek       | TUF GAMING Z490-PLUS        | [26af23411b](https://linux-hardware.org/?probe=26af23411b) | Oct 24, 2020 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | [d19a6fb1ad](https://linux-hardware.org/?probe=d19a6fb1ad) | Oct 24, 2020 |
| ASUSTek       | EB1007                      | [ba4ebffcea](https://linux-hardware.org/?probe=ba4ebffcea) | Oct 24, 2020 |
| MSI           | B75MA-P45                   | [3db10a8e54](https://linux-hardware.org/?probe=3db10a8e54) | Oct 24, 2020 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [51a8e7def6](https://linux-hardware.org/?probe=51a8e7def6) | Oct 23, 2020 |
| ASRock        | Z370 Pro4                   | [54521c791e](https://linux-hardware.org/?probe=54521c791e) | Oct 22, 2020 |
| ASRock        | Z370 Pro4                   | [d5024394f6](https://linux-hardware.org/?probe=d5024394f6) | Oct 22, 2020 |
| MSI           | B450M PRO-VDH MAX           | [232d1ed8b3](https://linux-hardware.org/?probe=232d1ed8b3) | Oct 22, 2020 |
| MSI           | B450M PRO-VDH MAX           | [41c93457a9](https://linux-hardware.org/?probe=41c93457a9) | Oct 22, 2020 |
| HP            | 3032h                       | [8ae510c9e4](https://linux-hardware.org/?probe=8ae510c9e4) | Oct 22, 2020 |
| ASRock        | H81M-DGS R2.0               | [3a1392ea30](https://linux-hardware.org/?probe=3a1392ea30) | Oct 21, 2020 |
| ASRock        | ALiveNF6G-VSTA              | [fa2b83511a](https://linux-hardware.org/?probe=fa2b83511a) | Oct 21, 2020 |
| ASRock        | ALiveNF6G-VSTA              | [04a8a81dc9](https://linux-hardware.org/?probe=04a8a81dc9) | Oct 21, 2020 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [3be207a8ab](https://linux-hardware.org/?probe=3be207a8ab) | Oct 20, 2020 |
| ASUSTek       | P5G41T-M LX                 | [90cfb4eb84](https://linux-hardware.org/?probe=90cfb4eb84) | Oct 20, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [cdda211f63](https://linux-hardware.org/?probe=cdda211f63) | Oct 19, 2020 |
| ASUSTek       | M5A97 R2.0                  | [b95967317c](https://linux-hardware.org/?probe=b95967317c) | Oct 19, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [1f02e0a2e4](https://linux-hardware.org/?probe=1f02e0a2e4) | Oct 19, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [2cf52e1ad7](https://linux-hardware.org/?probe=2cf52e1ad7) | Oct 19, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [d3a113a283](https://linux-hardware.org/?probe=d3a113a283) | Oct 19, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [8cce199ab5](https://linux-hardware.org/?probe=8cce199ab5) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| ASUSTek       | EB1007                      | [2e087c4075](https://linux-hardware.org/?probe=2e087c4075) | Oct 18, 2020 |
| Acer          | Predator G3610              | [919189d43a](https://linux-hardware.org/?probe=919189d43a) | Oct 18, 2020 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [c94071c5d1](https://linux-hardware.org/?probe=c94071c5d1) | Oct 18, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [1e58e00331](https://linux-hardware.org/?probe=1e58e00331) | Oct 18, 2020 |
| ASUSTek       | M4A78LT-M                   | [05d6ef0ede](https://linux-hardware.org/?probe=05d6ef0ede) | Oct 17, 2020 |
| Acer          | G31                         | [5eb228cd87](https://linux-hardware.org/?probe=5eb228cd87) | Oct 17, 2020 |
| HP            | 8433 11                     | [670028bf54](https://linux-hardware.org/?probe=670028bf54) | Oct 16, 2020 |
| ASUSTek       | M5A97 R2.0                  | [77ddfc098b](https://linux-hardware.org/?probe=77ddfc098b) | Oct 16, 2020 |
| Acer          | G31                         | [4a9ca6c37e](https://linux-hardware.org/?probe=4a9ca6c37e) | Oct 16, 2020 |
| MSI           | Z97A GAMING 9 ACK           | [b5e973e4f0](https://linux-hardware.org/?probe=b5e973e4f0) | Oct 16, 2020 |
| Gigabyte      | 970A-DS3P                   | [7f1e2386ac](https://linux-hardware.org/?probe=7f1e2386ac) | Oct 15, 2020 |
| ASUSTek       | M5A78L-M LX3                | [1dbe6e7540](https://linux-hardware.org/?probe=1dbe6e7540) | Oct 14, 2020 |
| Lenovo        | Board                       | [c2eb28c9f6](https://linux-hardware.org/?probe=c2eb28c9f6) | Oct 14, 2020 |
| Lenovo        | Board                       | [a829cdeb90](https://linux-hardware.org/?probe=a829cdeb90) | Oct 14, 2020 |
| ASRock        | B75 Pro3                    | [f7471e2dac](https://linux-hardware.org/?probe=f7471e2dac) | Oct 13, 2020 |
| ASUSTek       | H97M-E                      | [10ef051d48](https://linux-hardware.org/?probe=10ef051d48) | Oct 13, 2020 |
| Gigabyte      | 970A-DS3P                   | [e5b439d44c](https://linux-hardware.org/?probe=e5b439d44c) | Oct 13, 2020 |
| ASUSTek       | P8H61-M LE                  | [cadcc85a1e](https://linux-hardware.org/?probe=cadcc85a1e) | Oct 12, 2020 |
| ASUSTek       | P8H61-M LE                  | [18b0973b17](https://linux-hardware.org/?probe=18b0973b17) | Oct 12, 2020 |
| Gigabyte      | B450M S2H                   | [9b61991076](https://linux-hardware.org/?probe=9b61991076) | Oct 12, 2020 |
| ASRock        | 990FX Professional          | [97ce7ab2bc](https://linux-hardware.org/?probe=97ce7ab2bc) | Oct 12, 2020 |
| ASUSTek       | P7P55D-E                    | [53d11e2f7e](https://linux-hardware.org/?probe=53d11e2f7e) | Oct 12, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [e6831f4a4d](https://linux-hardware.org/?probe=e6831f4a4d) | Oct 12, 2020 |
| HP            | 3029h                       | [5156424aad](https://linux-hardware.org/?probe=5156424aad) | Oct 11, 2020 |
| Packard Be... | imedia S3810                | [a8aea761b4](https://linux-hardware.org/?probe=a8aea761b4) | Oct 11, 2020 |
| Packard Be... | imedia S3810                | [ba8094c4d6](https://linux-hardware.org/?probe=ba8094c4d6) | Oct 11, 2020 |
| ASUSTek       | G11CB                       | [9fafa60d0b](https://linux-hardware.org/?probe=9fafa60d0b) | Oct 11, 2020 |
| ASRock        | B450M-HDV R4.0              | [f6fcbdf241](https://linux-hardware.org/?probe=f6fcbdf241) | Oct 10, 2020 |
| Dell          | 0KRC95 A02                  | [66b9bd16fd](https://linux-hardware.org/?probe=66b9bd16fd) | Oct 10, 2020 |
| MSI           | MEG Z490 UNIFY              | [e9e7233c5d](https://linux-hardware.org/?probe=e9e7233c5d) | Oct 09, 2020 |
| MSI           | MEG Z490 UNIFY              | [a4189eceb8](https://linux-hardware.org/?probe=a4189eceb8) | Oct 09, 2020 |
| Acer          | Veriton S6610G              | [4514554900](https://linux-hardware.org/?probe=4514554900) | Oct 08, 2020 |
| ASUSTek       | P7P55D-E PRO                | [8006046378](https://linux-hardware.org/?probe=8006046378) | Oct 08, 2020 |
| Acer          | EG43M                       | [46015a6b9f](https://linux-hardware.org/?probe=46015a6b9f) | Oct 08, 2020 |
| Wistron       | ProLiant ML110 G5           | [c5f95c5205](https://linux-hardware.org/?probe=c5f95c5205) | Oct 08, 2020 |
| Lenovo        | SHARKBAY 31900058 STD       | [dccea75dd0](https://linux-hardware.org/?probe=dccea75dd0) | Oct 07, 2020 |
| MSI           | X58 Pro                     | [cba6a4e0ca](https://linux-hardware.org/?probe=cba6a4e0ca) | Oct 07, 2020 |
| Gigabyte      | Z87N-WIFI                   | [a91e9c1d77](https://linux-hardware.org/?probe=a91e9c1d77) | Oct 06, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [b1f0d81fa3](https://linux-hardware.org/?probe=b1f0d81fa3) | Oct 06, 2020 |
| Acer          | H57M01                      | [d13ed33786](https://linux-hardware.org/?probe=d13ed33786) | Oct 06, 2020 |
| ASRock        | H170 Pro4                   | [177ec64179](https://linux-hardware.org/?probe=177ec64179) | Oct 05, 2020 |
| ASUSTek       | P5VD2-VM SE                 | [0316df3f18](https://linux-hardware.org/?probe=0316df3f18) | Oct 04, 2020 |
| ASUSTek       | Maximus V EXTREME           | [dd6242b672](https://linux-hardware.org/?probe=dd6242b672) | Oct 03, 2020 |
| Intel         | DH55HC AAE70933-506         | [c4cdddc83b](https://linux-hardware.org/?probe=c4cdddc83b) | Oct 03, 2020 |
| ASUSTek       | P5VD2-VM SE                 | [c4db0a9703](https://linux-hardware.org/?probe=c4db0a9703) | Oct 03, 2020 |
| ASUSTek       | F1A75-V PRO                 | [e8b974939e](https://linux-hardware.org/?probe=e8b974939e) | Oct 02, 2020 |
| ASUSTek       | P5K                         | [c1c290f102](https://linux-hardware.org/?probe=c1c290f102) | Oct 02, 2020 |
| ASUSTek       | PRIME Z270-A                | [894f4ade05](https://linux-hardware.org/?probe=894f4ade05) | Oct 02, 2020 |
| MSI           | MEG X570 ACE                | [fcc94a3bad](https://linux-hardware.org/?probe=fcc94a3bad) | Oct 02, 2020 |
| MSI           | MEG X570 ACE                | [5736977893](https://linux-hardware.org/?probe=5736977893) | Oct 02, 2020 |
| Acer          | Veriton S6610G              | [a71f91a516](https://linux-hardware.org/?probe=a71f91a516) | Oct 02, 2020 |
| Acer          | Veriton S6610G              | [fd0fde6eda](https://linux-hardware.org/?probe=fd0fde6eda) | Oct 02, 2020 |
| ASUSTek       | V-P7H55E                    | [3233e607de](https://linux-hardware.org/?probe=3233e607de) | Oct 01, 2020 |
| Acer          | EG43M                       | [75e7e1fada](https://linux-hardware.org/?probe=75e7e1fada) | Oct 01, 2020 |
| ASUSTek       | V-P7H55E                    | [2acc237639](https://linux-hardware.org/?probe=2acc237639) | Oct 01, 2020 |
| ASUSTek       | V-P7H55E                    | [01511df391](https://linux-hardware.org/?probe=01511df391) | Oct 01, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [2b20bf294d](https://linux-hardware.org/?probe=2b20bf294d) | Oct 01, 2020 |
| ASRock        | A770CrossFire               | [1f0b3f065a](https://linux-hardware.org/?probe=1f0b3f065a) | Oct 01, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [47dde5c1dc](https://linux-hardware.org/?probe=47dde5c1dc) | Oct 01, 2020 |
| ASUSTek       | V-M4A3000E                  | [16f62b2645](https://linux-hardware.org/?probe=16f62b2645) | Oct 01, 2020 |
| Gigabyte      | X570 UD                     | [ae5fcdea31](https://linux-hardware.org/?probe=ae5fcdea31) | Sep 30, 2020 |
| Acer          | G31                         | [57f21d51f3](https://linux-hardware.org/?probe=57f21d51f3) | Sep 30, 2020 |
| ASUSTek       | Crosshair IV Formula        | [148be00ebb](https://linux-hardware.org/?probe=148be00ebb) | Sep 29, 2020 |
| MSI           | B550-A PRO                  | [5be6140d9e](https://linux-hardware.org/?probe=5be6140d9e) | Sep 29, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [3e56820897](https://linux-hardware.org/?probe=3e56820897) | Sep 29, 2020 |
| ASRock        | N68-S                       | [a9df8fb261](https://linux-hardware.org/?probe=a9df8fb261) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| ASUSTek       | V-M4A3000E                  | [09011a2a44](https://linux-hardware.org/?probe=09011a2a44) | Sep 28, 2020 |
| MSI           | B550-A PRO                  | [8e57e2861e](https://linux-hardware.org/?probe=8e57e2861e) | Sep 28, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| ASRock        | N68-S                       | [53a1e8cd7a](https://linux-hardware.org/?probe=53a1e8cd7a) | Sep 27, 2020 |
| Acer          | Predator G3610              | [604138adc5](https://linux-hardware.org/?probe=604138adc5) | Sep 27, 2020 |
| ASUSTek       | P5KPL-AM                    | [d42399006f](https://linux-hardware.org/?probe=d42399006f) | Sep 27, 2020 |
| Dell          | 042P49 A00                  | [f5d7976cc5](https://linux-hardware.org/?probe=f5d7976cc5) | Sep 27, 2020 |
| Dell          | 042P49 A00                  | [47243f2117](https://linux-hardware.org/?probe=47243f2117) | Sep 27, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [2efdb2957d](https://linux-hardware.org/?probe=2efdb2957d) | Sep 26, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [893d264166](https://linux-hardware.org/?probe=893d264166) | Sep 26, 2020 |
| ASRock        | 775i65G                     | [0d0504c1a5](https://linux-hardware.org/?probe=0d0504c1a5) | Sep 24, 2020 |
| Dell          | 0KRC95 A02                  | [9b45d9ea72](https://linux-hardware.org/?probe=9b45d9ea72) | Sep 22, 2020 |
| MSI           | H81M-E35 V2                 | [39b34c3236](https://linux-hardware.org/?probe=39b34c3236) | Sep 22, 2020 |
| MSI           | B450M PRO-VDH MAX           | [79147c29d6](https://linux-hardware.org/?probe=79147c29d6) | Sep 21, 2020 |
| Intel         | DH55HC AAE70933-506         | [7c8236c425](https://linux-hardware.org/?probe=7c8236c425) | Sep 20, 2020 |
| ASRock        | Z68 Extreme4                | [d82b1b3cbd](https://linux-hardware.org/?probe=d82b1b3cbd) | Sep 20, 2020 |
| Pegatron      | IPPCR-SS                    | [a96ae0a909](https://linux-hardware.org/?probe=a96ae0a909) | Sep 19, 2020 |
| Pegatron      | IPPCR-SS                    | [b45ffe6f4b](https://linux-hardware.org/?probe=b45ffe6f4b) | Sep 19, 2020 |
| MSI           | Boston                      | [dc5892ca4c](https://linux-hardware.org/?probe=dc5892ca4c) | Sep 18, 2020 |
| Gigabyte      | X570 AORUS PRO              | [19318482e4](https://linux-hardware.org/?probe=19318482e4) | Sep 18, 2020 |
| Gigabyte      | X570 AORUS PRO              | [5a574590f7](https://linux-hardware.org/?probe=5a574590f7) | Sep 18, 2020 |
| Packard Be... | MCP73VT-PM                  | [6a6d47f6fd](https://linux-hardware.org/?probe=6a6d47f6fd) | Sep 17, 2020 |
| AOpen         | D1007 0BBA                  | [f9360bc720](https://linux-hardware.org/?probe=f9360bc720) | Sep 17, 2020 |
| ASUSTek       | AM1I-A                      | [f5969ea216](https://linux-hardware.org/?probe=f5969ea216) | Sep 17, 2020 |
| ASUSTek       | AM1I-A                      | [800e6b279f](https://linux-hardware.org/?probe=800e6b279f) | Sep 17, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [2c69624930](https://linux-hardware.org/?probe=2c69624930) | Sep 16, 2020 |
| Dell          | 0KRC95 A00                  | [2dc3913c7e](https://linux-hardware.org/?probe=2dc3913c7e) | Sep 16, 2020 |
| ASUSTek       | Maximus VIII GENE           | [6dc96029ec](https://linux-hardware.org/?probe=6dc96029ec) | Sep 16, 2020 |
| HP            | 0AA8h                       | [cbfb0bcb1c](https://linux-hardware.org/?probe=cbfb0bcb1c) | Sep 15, 2020 |
| ASUSTek       | Benicia                     | [9c0dcf3d26](https://linux-hardware.org/?probe=9c0dcf3d26) | Sep 14, 2020 |
| ASUSTek       | P5KPL-AM                    | [3f22ea2e15](https://linux-hardware.org/?probe=3f22ea2e15) | Sep 13, 2020 |
| Dell          | 0CU409                      | [845bb2c1eb](https://linux-hardware.org/?probe=845bb2c1eb) | Sep 13, 2020 |
| Dell          | 0CU409                      | [4990cb2b3d](https://linux-hardware.org/?probe=4990cb2b3d) | Sep 13, 2020 |
| Gigabyte      | B450M DS3H-CF               | [3dcef22058](https://linux-hardware.org/?probe=3dcef22058) | Sep 13, 2020 |
| Acer          | Veriton M2631 V:1.0         | [c492401ffc](https://linux-hardware.org/?probe=c492401ffc) | Sep 13, 2020 |
| Lenovo        | Board                       | [f8dc9acb3f](https://linux-hardware.org/?probe=f8dc9acb3f) | Sep 13, 2020 |
| Lenovo        | Board                       | [9f4325cb06](https://linux-hardware.org/?probe=9f4325cb06) | Sep 13, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [09611dd419](https://linux-hardware.org/?probe=09611dd419) | Sep 13, 2020 |
| Gigabyte      | Z77-DS3H                    | [d7f43611eb](https://linux-hardware.org/?probe=d7f43611eb) | Sep 13, 2020 |
| ASUSTek       | P5Q DELUXE                  | [960c7e17db](https://linux-hardware.org/?probe=960c7e17db) | Sep 12, 2020 |
| ASUSTek       | Maximus V EXTREME           | [581d8c601b](https://linux-hardware.org/?probe=581d8c601b) | Sep 12, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8a5dbecbe9](https://linux-hardware.org/?probe=8a5dbecbe9) | Sep 11, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [72c445d61b](https://linux-hardware.org/?probe=72c445d61b) | Sep 11, 2020 |
| MSI           | B250M BAZOOKA               | [7094b10098](https://linux-hardware.org/?probe=7094b10098) | Sep 10, 2020 |
| MSI           | B250M BAZOOKA               | [1e577c0a90](https://linux-hardware.org/?probe=1e577c0a90) | Sep 10, 2020 |
| Dell          | 0CU409                      | [437f18e1b4](https://linux-hardware.org/?probe=437f18e1b4) | Sep 10, 2020 |
| MSI           | B250M BAZOOKA               | [58ba1595d0](https://linux-hardware.org/?probe=58ba1595d0) | Sep 10, 2020 |
| AZW           | Gemini X55                  | [b109444fe7](https://linux-hardware.org/?probe=b109444fe7) | Sep 10, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [c42eeae6ed](https://linux-hardware.org/?probe=c42eeae6ed) | Sep 10, 2020 |
| AZW           | Gemini X55                  | [2ba4c8e41a](https://linux-hardware.org/?probe=2ba4c8e41a) | Sep 09, 2020 |
| ASUSTek       | H97M-E                      | [88557c5aba](https://linux-hardware.org/?probe=88557c5aba) | Sep 09, 2020 |
| ASRock        | J3455-ITX                   | [8c3e19471e](https://linux-hardware.org/?probe=8c3e19471e) | Sep 08, 2020 |
| Acer          | F672CR R01-A4               | [05829f1c84](https://linux-hardware.org/?probe=05829f1c84) | Sep 08, 2020 |
| MSI           | MAG Z390 TOMAHAWK           | [a146781c5e](https://linux-hardware.org/?probe=a146781c5e) | Sep 08, 2020 |
| Packard Be... | MCP73VT-PM                  | [97d74c4182](https://linux-hardware.org/?probe=97d74c4182) | Sep 07, 2020 |
| ASUSTek       | Maximus V EXTREME           | [a8cd81b816](https://linux-hardware.org/?probe=a8cd81b816) | Sep 07, 2020 |
| Acer          | EM61SM/EM61PM               | [2c469cf161](https://linux-hardware.org/?probe=2c469cf161) | Sep 07, 2020 |
| Packard Be... | MCP73VT-PM                  | [681e92bb0d](https://linux-hardware.org/?probe=681e92bb0d) | Sep 06, 2020 |
| HP            | 0AA8h                       | [ee05e7e954](https://linux-hardware.org/?probe=ee05e7e954) | Sep 06, 2020 |
| ASUSTek       | P7P55D-E                    | [aea812777f](https://linux-hardware.org/?probe=aea812777f) | Sep 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [a1530272c6](https://linux-hardware.org/?probe=a1530272c6) | Sep 06, 2020 |
| ASUSTek       | A_F_K31AN                   | [bd624f8159](https://linux-hardware.org/?probe=bd624f8159) | Sep 06, 2020 |
| HP            | 1998                        | [8726c8ded4](https://linux-hardware.org/?probe=8726c8ded4) | Sep 05, 2020 |
| HP            | 82F2 A01                    | [f01ac2045a](https://linux-hardware.org/?probe=f01ac2045a) | Sep 05, 2020 |
| Lenovo        | SHARKBAY 31900002 WIN       | [0d3c6c1c68](https://linux-hardware.org/?probe=0d3c6c1c68) | Sep 05, 2020 |
| MSI           | B450-A PRO MAX              | [70ab0b4101](https://linux-hardware.org/?probe=70ab0b4101) | Sep 05, 2020 |
| ASUSTek       | H170I-PRO                   | [98faccc7f5](https://linux-hardware.org/?probe=98faccc7f5) | Sep 05, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [5197abcc56](https://linux-hardware.org/?probe=5197abcc56) | Sep 04, 2020 |
| MSI           | B450-A PRO MAX              | [12ebb330e9](https://linux-hardware.org/?probe=12ebb330e9) | Sep 04, 2020 |
| MSI           | 990FXA-GD80                 | [577dec9786](https://linux-hardware.org/?probe=577dec9786) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII HERO           | [2dc46d052a](https://linux-hardware.org/?probe=2dc46d052a) | Sep 04, 2020 |
| Acer          | MCP7A                       | [2feb2b6dc6](https://linux-hardware.org/?probe=2feb2b6dc6) | Sep 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [242f9cb8c6](https://linux-hardware.org/?probe=242f9cb8c6) | Sep 03, 2020 |
| Gigabyte      | B450M S2H                   | [422a6dd7be](https://linux-hardware.org/?probe=422a6dd7be) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [63ed157e3a](https://linux-hardware.org/?probe=63ed157e3a) | Sep 03, 2020 |
| ASRock        | B85 Pro4                    | [a7cf83e421](https://linux-hardware.org/?probe=a7cf83e421) | Sep 02, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [9c4adb3b7e](https://linux-hardware.org/?probe=9c4adb3b7e) | Sep 02, 2020 |
| MSI           | B250M BAZOOKA               | [67974ea52a](https://linux-hardware.org/?probe=67974ea52a) | Sep 02, 2020 |
| MSI           | B250M BAZOOKA               | [7a4553d0bf](https://linux-hardware.org/?probe=7a4553d0bf) | Sep 01, 2020 |
| MSI           | B250M BAZOOKA               | [f3a000fae6](https://linux-hardware.org/?probe=f3a000fae6) | Sep 01, 2020 |
| AZW           | Gemini X55                  | [ae62c11442](https://linux-hardware.org/?probe=ae62c11442) | Aug 31, 2020 |
| AZW           | Gemini X55                  | [aee08f6134](https://linux-hardware.org/?probe=aee08f6134) | Aug 31, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78553c451b](https://linux-hardware.org/?probe=78553c451b) | Aug 31, 2020 |
| MSI           | MS-7472 0A                  | [e101e99912](https://linux-hardware.org/?probe=e101e99912) | Aug 31, 2020 |
| AZW           | Gemini X55                  | [8a36c4b885](https://linux-hardware.org/?probe=8a36c4b885) | Aug 31, 2020 |
| AZW           | Gemini X55                  | [588a458429](https://linux-hardware.org/?probe=588a458429) | Aug 31, 2020 |
| ASUSTek       | M2N-MX                      | [f8f6538928](https://linux-hardware.org/?probe=f8f6538928) | Aug 30, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d5fc85acb2](https://linux-hardware.org/?probe=d5fc85acb2) | Aug 30, 2020 |
| Intel         | DZ68DB AAG27985-101         | [6dde305ad2](https://linux-hardware.org/?probe=6dde305ad2) | Aug 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [83c8a33e5b](https://linux-hardware.org/?probe=83c8a33e5b) | Aug 29, 2020 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [4f0828c293](https://linux-hardware.org/?probe=4f0828c293) | Aug 29, 2020 |
| Gigabyte      | Z87N-WIFI                   | [07f8dfbb24](https://linux-hardware.org/?probe=07f8dfbb24) | Aug 29, 2020 |
| HP            | 0AA8h                       | [56cdc6aff9](https://linux-hardware.org/?probe=56cdc6aff9) | Aug 29, 2020 |
| ASUSTek       | PRIME B250M-A               | [76ed04af78](https://linux-hardware.org/?probe=76ed04af78) | Aug 28, 2020 |
| Gigabyte      | X570 AORUS PRO              | [0769c8d889](https://linux-hardware.org/?probe=0769c8d889) | Aug 28, 2020 |
| Acer          | Aspire XC-330               | [eeb5156867](https://linux-hardware.org/?probe=eeb5156867) | Aug 28, 2020 |
| Gigabyte      | EX58-UD5                    | [ba4030e3bc](https://linux-hardware.org/?probe=ba4030e3bc) | Aug 28, 2020 |
| ASUSTek       | M4A78LT-M                   | [af3c3aee59](https://linux-hardware.org/?probe=af3c3aee59) | Aug 27, 2020 |
| ASUSTek       | M4A78LT-M                   | [cae2109038](https://linux-hardware.org/?probe=cae2109038) | Aug 27, 2020 |
| ASUSTek       | ET1612I                     | [9cc05b2a9e](https://linux-hardware.org/?probe=9cc05b2a9e) | Aug 27, 2020 |
| Gigabyte      | G33M-S2L                    | [433fdcffca](https://linux-hardware.org/?probe=433fdcffca) | Aug 26, 2020 |
| Dell          | 0CU409                      | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| MSI           | H81I                        | [0d2bafed80](https://linux-hardware.org/?probe=0d2bafed80) | Aug 26, 2020 |
| ASUSTek       | ET1612I                     | [82b55a1903](https://linux-hardware.org/?probe=82b55a1903) | Aug 25, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [021f8b7ce5](https://linux-hardware.org/?probe=021f8b7ce5) | Aug 25, 2020 |
| HP            | 2B17                        | [3ed7ff6cc4](https://linux-hardware.org/?probe=3ed7ff6cc4) | Aug 24, 2020 |
| Gigabyte      | G33M-S2L                    | [9c80a0e899](https://linux-hardware.org/?probe=9c80a0e899) | Aug 24, 2020 |
| ASUSTek       | ET1612I                     | [a69dacee1d](https://linux-hardware.org/?probe=a69dacee1d) | Aug 24, 2020 |
| Lenovo        | MAHOBAY NOK                 | [7ec33920d1](https://linux-hardware.org/?probe=7ec33920d1) | Aug 24, 2020 |
| Lenovo        | MAHOBAY NOK                 | [5d88d45801](https://linux-hardware.org/?probe=5d88d45801) | Aug 24, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [1849c98429](https://linux-hardware.org/?probe=1849c98429) | Aug 24, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [3e2a1282e2](https://linux-hardware.org/?probe=3e2a1282e2) | Aug 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2fddf4f65e](https://linux-hardware.org/?probe=2fddf4f65e) | Aug 23, 2020 |
| Gigabyte      | M68M-S2P                    | [0bdde8f2b3](https://linux-hardware.org/?probe=0bdde8f2b3) | Aug 21, 2020 |
| ASUSTek       | P8B WS                      | [e432e3cf01](https://linux-hardware.org/?probe=e432e3cf01) | Aug 20, 2020 |
| ASRock        | AB350M Pro4                 | [95b6dbdf4e](https://linux-hardware.org/?probe=95b6dbdf4e) | Aug 20, 2020 |
| Dell          | 0KRC95 A00                  | [67d78c4b30](https://linux-hardware.org/?probe=67d78c4b30) | Aug 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [5c09a8571d](https://linux-hardware.org/?probe=5c09a8571d) | Aug 19, 2020 |
| Packard Be... | IMEDIA S3712                | [a6be18b3d6](https://linux-hardware.org/?probe=a6be18b3d6) | Aug 19, 2020 |
| Packard Be... | IMEDIA S3712                | [fb0f76e829](https://linux-hardware.org/?probe=fb0f76e829) | Aug 19, 2020 |
| Dell          | 0KRC95 A00                  | [caabd17c2d](https://linux-hardware.org/?probe=caabd17c2d) | Aug 17, 2020 |
| Gigabyte      | 945GZM-S2                   | [08706b8787](https://linux-hardware.org/?probe=08706b8787) | Aug 17, 2020 |
| ASUSTek       | M2A-MX                      | [a4496076d9](https://linux-hardware.org/?probe=a4496076d9) | Aug 16, 2020 |
| Packard Be... | IMEDIA S3712                | [a14ff9c2b8](https://linux-hardware.org/?probe=a14ff9c2b8) | Aug 16, 2020 |
| ASUSTek       | Benicia                     | [53d2a78245](https://linux-hardware.org/?probe=53d2a78245) | Aug 16, 2020 |
| MSI           | A320M-A PRO                 | [e0c25fa813](https://linux-hardware.org/?probe=e0c25fa813) | Aug 15, 2020 |
| ASRock        | AB350 Pro4                  | [3c5418e4f4](https://linux-hardware.org/?probe=3c5418e4f4) | Aug 14, 2020 |
| ASRock        | B450M Pro4                  | [ea3d073f80](https://linux-hardware.org/?probe=ea3d073f80) | Aug 14, 2020 |
| MSI           | MAG Z390 TOMAHAWK           | [927bfed96f](https://linux-hardware.org/?probe=927bfed96f) | Aug 13, 2020 |
| ASRock        | N3000-NUC                   | [ab1cfbb701](https://linux-hardware.org/?probe=ab1cfbb701) | Aug 12, 2020 |
| MSI           | 2A9C                        | [cc5bd25366](https://linux-hardware.org/?probe=cc5bd25366) | Aug 11, 2020 |
| Dell          | 0KRC95 A00                  | [0a27f87f0c](https://linux-hardware.org/?probe=0a27f87f0c) | Aug 11, 2020 |
| ASUSTek       | P5QC                        | [959e926cbd](https://linux-hardware.org/?probe=959e926cbd) | Aug 11, 2020 |
| HP            | 8459                        | [c0c5068e12](https://linux-hardware.org/?probe=c0c5068e12) | Aug 08, 2020 |
| ASUSTek       | M3N78-VM                    | [2158eae3c4](https://linux-hardware.org/?probe=2158eae3c4) | Aug 08, 2020 |
| ASUSTek       | M2A-MX                      | [5a05a19683](https://linux-hardware.org/?probe=5a05a19683) | Aug 08, 2020 |
| ASUSTek       | P8H77-M                     | [fa7d8422b1](https://linux-hardware.org/?probe=fa7d8422b1) | Aug 07, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [659e601b97](https://linux-hardware.org/?probe=659e601b97) | Aug 07, 2020 |
| Gigabyte      | B75M-D3H                    | [0503eff9c6](https://linux-hardware.org/?probe=0503eff9c6) | Aug 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [cdd9be8875](https://linux-hardware.org/?probe=cdd9be8875) | Aug 07, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [c2c3bf94b7](https://linux-hardware.org/?probe=c2c3bf94b7) | Aug 07, 2020 |
| ASUSTek       | Leonite2                    | [5d4611db68](https://linux-hardware.org/?probe=5d4611db68) | Aug 05, 2020 |
| ASUSTek       | Leonite2                    | [c8680a6679](https://linux-hardware.org/?probe=c8680a6679) | Aug 05, 2020 |
| ASRock        | 4CoreDual-SATA2             | [020c7766df](https://linux-hardware.org/?probe=020c7766df) | Aug 05, 2020 |
| MSI           | A78M-E35                    | [f76c445af2](https://linux-hardware.org/?probe=f76c445af2) | Aug 04, 2020 |
| Gigabyte      | B360M H                     | [f9b9e806d8](https://linux-hardware.org/?probe=f9b9e806d8) | Aug 04, 2020 |
| HP            | 0A54h                       | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| MSI           | A88XM-E35 V2                | [34d22ff366](https://linux-hardware.org/?probe=34d22ff366) | Aug 02, 2020 |
| MSI           | A88XM-E35 V2                | [c589a29940](https://linux-hardware.org/?probe=c589a29940) | Aug 02, 2020 |
| ASUSTek       | P5QC                        | [96a57feffe](https://linux-hardware.org/?probe=96a57feffe) | Aug 02, 2020 |
| Packard Be... | MCP73VT-PM                  | [0b32c22f34](https://linux-hardware.org/?probe=0b32c22f34) | Aug 01, 2020 |
| MSI           | A75MA-G55                   | [f6e27145ee](https://linux-hardware.org/?probe=f6e27145ee) | Aug 01, 2020 |
| Gigabyte      | H81M-S1                     | [551d479063](https://linux-hardware.org/?probe=551d479063) | Jul 31, 2020 |
| Gigabyte      | Z87N-WIFI                   | [4eddbe510a](https://linux-hardware.org/?probe=4eddbe510a) | Jul 31, 2020 |
| Gigabyte      | B360M H                     | [df45e94e6d](https://linux-hardware.org/?probe=df45e94e6d) | Jul 30, 2020 |
| ASRock        | B85M-HDS                    | [7e7ad89d55](https://linux-hardware.org/?probe=7e7ad89d55) | Jul 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [65fcb7a07e](https://linux-hardware.org/?probe=65fcb7a07e) | Jul 28, 2020 |
| ASUSTek       | P5LD2EB-DHS                 | [ebb58f610e](https://linux-hardware.org/?probe=ebb58f610e) | Jul 28, 2020 |
| ASUSTek       | PRIME A320M-K               | [02e55833c8](https://linux-hardware.org/?probe=02e55833c8) | Jul 28, 2020 |
| HP            | 3048h                       | [07fb23bdba](https://linux-hardware.org/?probe=07fb23bdba) | Jul 28, 2020 |
| ASUSTek       | P5Q PRO TURBO               | [f2e010d67a](https://linux-hardware.org/?probe=f2e010d67a) | Jul 27, 2020 |
| ASUSTek       | P5K                         | [6ef5c0d847](https://linux-hardware.org/?probe=6ef5c0d847) | Jul 26, 2020 |
| Gigabyte      | EX58-UD5                    | [c3d39bbc2b](https://linux-hardware.org/?probe=c3d39bbc2b) | Jul 26, 2020 |
| Gigabyte      | EX58-UD5                    | [488a7105c5](https://linux-hardware.org/?probe=488a7105c5) | Jul 26, 2020 |
| ASUSTek       | P5G41T-M LX                 | [52ca0c747d](https://linux-hardware.org/?probe=52ca0c747d) | Jul 24, 2020 |
| MSI           | G31TM-P35                   | [956c575a24](https://linux-hardware.org/?probe=956c575a24) | Jul 24, 2020 |
| ASUSTek       | PRIME Z370-P                | [f995b63717](https://linux-hardware.org/?probe=f995b63717) | Jul 23, 2020 |
| ASUSTek       | PRIME Z370-P                | [ab812f9721](https://linux-hardware.org/?probe=ab812f9721) | Jul 23, 2020 |
| Dell          | 0VNP2H A00                  | [3c3e0dfe36](https://linux-hardware.org/?probe=3c3e0dfe36) | Jul 23, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [b93adeffe2](https://linux-hardware.org/?probe=b93adeffe2) | Jul 21, 2020 |
| ASUSTek       | PRIME Z370-P                | [ff6559cd34](https://linux-hardware.org/?probe=ff6559cd34) | Jul 20, 2020 |
| MSI           | A75MA-G55                   | [9061f7d6fb](https://linux-hardware.org/?probe=9061f7d6fb) | Jul 20, 2020 |
| HP            | 8433 11                     | [ffad5f25ec](https://linux-hardware.org/?probe=ffad5f25ec) | Jul 19, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e4f030d3cd](https://linux-hardware.org/?probe=e4f030d3cd) | Jul 19, 2020 |
| ASUSTek       | PRIME B365M-K               | [596a9f4f53](https://linux-hardware.org/?probe=596a9f4f53) | Jul 19, 2020 |
| HP            | 8433 11                     | [47a876ed5d](https://linux-hardware.org/?probe=47a876ed5d) | Jul 18, 2020 |
| MSI           | C847MS-E33                  | [b91f8a59b0](https://linux-hardware.org/?probe=b91f8a59b0) | Jul 18, 2020 |
| ASUSTek       | H97-PLUS                    | [9ec87ba4f9](https://linux-hardware.org/?probe=9ec87ba4f9) | Jul 18, 2020 |
| HP            | 2AF3                        | [c1a8ddc92e](https://linux-hardware.org/?probe=c1a8ddc92e) | Jul 17, 2020 |
| HP            | 8433 11                     | [eefc213074](https://linux-hardware.org/?probe=eefc213074) | Jul 17, 2020 |
| ASUSTek       | P5K                         | [4b059df343](https://linux-hardware.org/?probe=4b059df343) | Jul 17, 2020 |
| Packard Be... | MCP73VT-PM                  | [4a200efcb6](https://linux-hardware.org/?probe=4a200efcb6) | Jul 17, 2020 |
| MSI           | MS-7472 0A                  | [91fe1ec711](https://linux-hardware.org/?probe=91fe1ec711) | Jul 17, 2020 |
| ASUSTek       | M2A-MX                      | [b35aa1c01f](https://linux-hardware.org/?probe=b35aa1c01f) | Jul 16, 2020 |
| ASUSTek       | H81-PLUS                    | [0e79ae7820](https://linux-hardware.org/?probe=0e79ae7820) | Jul 16, 2020 |
| ASUSTek       | H81-PLUS                    | [915f6d5a88](https://linux-hardware.org/?probe=915f6d5a88) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| Gigabyte      | B360M DS3H                  | [2b3a3c7303](https://linux-hardware.org/?probe=2b3a3c7303) | Jul 15, 2020 |
| ASRock        | 775Dual-VSTA                | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P8P67                       | [2fba0d81c7](https://linux-hardware.org/?probe=2fba0d81c7) | Jul 15, 2020 |
| Dell          | 0VNP2H A00                  | [06acb4c0ab](https://linux-hardware.org/?probe=06acb4c0ab) | Jul 15, 2020 |
| Dell          | 0VNP2H A00                  | [a8561b5e78](https://linux-hardware.org/?probe=a8561b5e78) | Jul 15, 2020 |
| Biostar       | N61PB-M2S                   | [ff80a14160](https://linux-hardware.org/?probe=ff80a14160) | Jul 14, 2020 |
| Biostar       | N61PB-M2S                   | [2183cfa370](https://linux-hardware.org/?probe=2183cfa370) | Jul 14, 2020 |
| ASRock        | 775Dual-VSTA                | [6439049888](https://linux-hardware.org/?probe=6439049888) | Jul 14, 2020 |
| Packard Be... | imedia S2110A               | [5933579e4d](https://linux-hardware.org/?probe=5933579e4d) | Jul 14, 2020 |
| ASUSTek       | P5KPL-CM                    | [9299d16536](https://linux-hardware.org/?probe=9299d16536) | Jul 13, 2020 |
| ASUSTek       | P5KPL-CM                    | [1a83eca815](https://linux-hardware.org/?probe=1a83eca815) | Jul 13, 2020 |
| ASUSTek       | P5QPL-AM                    | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [c4a39e060a](https://linux-hardware.org/?probe=c4a39e060a) | Jul 11, 2020 |
| Acer          | Extensa X2610G              | [12b9c02a39](https://linux-hardware.org/?probe=12b9c02a39) | Jul 11, 2020 |
| HP            | 3397                        | [8ea6a197a8](https://linux-hardware.org/?probe=8ea6a197a8) | Jul 10, 2020 |
| ASRock        | 990FX Extreme3              | [e93aee1b98](https://linux-hardware.org/?probe=e93aee1b98) | Jul 10, 2020 |
| ASRock        | 990FX Extreme3              | [faff0dc399](https://linux-hardware.org/?probe=faff0dc399) | Jul 10, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [242e497d92](https://linux-hardware.org/?probe=242e497d92) | Jul 09, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [3ea9c8a2d1](https://linux-hardware.org/?probe=3ea9c8a2d1) | Jul 08, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [7a5a0f43ec](https://linux-hardware.org/?probe=7a5a0f43ec) | Jul 08, 2020 |
| ASRock        | B450M Pro4                  | [cfb4f21a98](https://linux-hardware.org/?probe=cfb4f21a98) | Jul 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [5b0c93c1e2](https://linux-hardware.org/?probe=5b0c93c1e2) | Jul 07, 2020 |
| Acer          | Aspire MC605 v1.0           | [1ddf75d3b7](https://linux-hardware.org/?probe=1ddf75d3b7) | Jul 06, 2020 |
| HP            | ProLiant MicroServer        | [41ee975578](https://linux-hardware.org/?probe=41ee975578) | Jul 06, 2020 |
| HP            | ProLiant MicroServer        | [245e8721c3](https://linux-hardware.org/?probe=245e8721c3) | Jul 06, 2020 |
| ASUSTek       | P5QC                        | [27e9af4f63](https://linux-hardware.org/?probe=27e9af4f63) | Jul 05, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [5ba6a65149](https://linux-hardware.org/?probe=5ba6a65149) | Jul 05, 2020 |
| ASRock        | ALiveNF6G-GLAN              | [9182a219ee](https://linux-hardware.org/?probe=9182a219ee) | Jul 04, 2020 |
| HP            | 1998                        | [bb467b5229](https://linux-hardware.org/?probe=bb467b5229) | Jul 04, 2020 |
| HP            | 1998                        | [0cd44e7556](https://linux-hardware.org/?probe=0cd44e7556) | Jul 04, 2020 |
| ASUSTek       | P8H61-M LE                  | [617e5603a9](https://linux-hardware.org/?probe=617e5603a9) | Jul 04, 2020 |
| ASRock        | B450M-HDV R4.0              | [614c7cc9e6](https://linux-hardware.org/?probe=614c7cc9e6) | Jul 03, 2020 |
| HP            | 3032h                       | [ad8bada424](https://linux-hardware.org/?probe=ad8bada424) | Jul 02, 2020 |
| HP            | 1497                        | [b5dc79b8d1](https://linux-hardware.org/?probe=b5dc79b8d1) | Jul 01, 2020 |
| MSI           | MS-B9181                    | [4881a33c91](https://linux-hardware.org/?probe=4881a33c91) | Jul 01, 2020 |
| ASRock        | AM2NF6G-VSTA                | [81cb2b3479](https://linux-hardware.org/?probe=81cb2b3479) | Jun 30, 2020 |
| Packard Be... | MCP73VT-PM                  | [94b69b3a78](https://linux-hardware.org/?probe=94b69b3a78) | Jun 30, 2020 |
| Lenovo        | MAHOBAY NOK                 | [3897c3155a](https://linux-hardware.org/?probe=3897c3155a) | Jun 30, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d5e1369eb5](https://linux-hardware.org/?probe=d5e1369eb5) | Jun 29, 2020 |
| ASRock        | B450M Pro4                  | [655a32c9b7](https://linux-hardware.org/?probe=655a32c9b7) | Jun 29, 2020 |
| ASRock        | B450M Pro4                  | [81a973fe65](https://linux-hardware.org/?probe=81a973fe65) | Jun 29, 2020 |
| Packard Be... | MCP73VT-PM                  | [2e65c4602d](https://linux-hardware.org/?probe=2e65c4602d) | Jun 29, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [f463c2798b](https://linux-hardware.org/?probe=f463c2798b) | Jun 28, 2020 |
| Foxconn       | Newark HP P/N               | [9a3f224628](https://linux-hardware.org/?probe=9a3f224628) | Jun 28, 2020 |
| Gigabyte      | H77-DS3H                    | [7d3953be6a](https://linux-hardware.org/?probe=7d3953be6a) | Jun 28, 2020 |
| ASRock        | H110M-DVS R2.0              | [76d63ded63](https://linux-hardware.org/?probe=76d63ded63) | Jun 27, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d4c360c2e2](https://linux-hardware.org/?probe=d4c360c2e2) | Jun 27, 2020 |
| Gigabyte      | GA-MA74GM-S2                | [e062e442fb](https://linux-hardware.org/?probe=e062e442fb) | Jun 26, 2020 |
| ASUSTek       | H81M-K                      | [9f6d2e42f4](https://linux-hardware.org/?probe=9f6d2e42f4) | Jun 26, 2020 |
| ASUSTek       | H81M-K                      | [fd8489dbb8](https://linux-hardware.org/?probe=fd8489dbb8) | Jun 26, 2020 |
| ASRock        | G31M-GS                     | [1f5ef51755](https://linux-hardware.org/?probe=1f5ef51755) | Jun 26, 2020 |
| ASUSTek       | P6T SE                      | [1ad936a2e5](https://linux-hardware.org/?probe=1ad936a2e5) | Jun 25, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | [6604575d55](https://linux-hardware.org/?probe=6604575d55) | Jun 25, 2020 |
| ASRock        | 4Core1600Twins-P35          | [3a320b2593](https://linux-hardware.org/?probe=3a320b2593) | Jun 25, 2020 |
| Packard Be... | MCP73VT-PM                  | [1af9bd68bf](https://linux-hardware.org/?probe=1af9bd68bf) | Jun 24, 2020 |
| Acer          | Aspire MC605 v1.0           | [9b75146b34](https://linux-hardware.org/?probe=9b75146b34) | Jun 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [7cb9959792](https://linux-hardware.org/?probe=7cb9959792) | Jun 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [81c7861e5a](https://linux-hardware.org/?probe=81c7861e5a) | Jun 24, 2020 |
| Packard Be... | MCP73VT-PM                  | [4a41a878a2](https://linux-hardware.org/?probe=4a41a878a2) | Jun 24, 2020 |
| Acer          | E915GVM R01-B2              | [68b1733b02](https://linux-hardware.org/?probe=68b1733b02) | Jun 24, 2020 |
| Acer          | E915GVM R01-B2              | [f02e3f263d](https://linux-hardware.org/?probe=f02e3f263d) | Jun 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [3534191c32](https://linux-hardware.org/?probe=3534191c32) | Jun 23, 2020 |
| Gigabyte      | Z87-HD3                     | [a595b0b50d](https://linux-hardware.org/?probe=a595b0b50d) | Jun 23, 2020 |
| ASRock        | G31M-GS                     | [b7468bf9f3](https://linux-hardware.org/?probe=b7468bf9f3) | Jun 22, 2020 |
| HP            | 1998                        | [dcc038ad2f](https://linux-hardware.org/?probe=dcc038ad2f) | Jun 21, 2020 |
| MSI           | MS-7255                     | [27a9cb796a](https://linux-hardware.org/?probe=27a9cb796a) | Jun 20, 2020 |
| Dell          | 0M858N A01                  | [9c4096f26a](https://linux-hardware.org/?probe=9c4096f26a) | Jun 20, 2020 |
| HP            | 1998                        | [97cd87fec2](https://linux-hardware.org/?probe=97cd87fec2) | Jun 19, 2020 |
| HP            | 1998                        | [8cc98988bd](https://linux-hardware.org/?probe=8cc98988bd) | Jun 19, 2020 |
| Dell          | 0J584C A00                  | [68509e129e](https://linux-hardware.org/?probe=68509e129e) | Jun 19, 2020 |
| ASUSTek       | H97M-E                      | [c352132bb5](https://linux-hardware.org/?probe=c352132bb5) | Jun 19, 2020 |
| Gigabyte      | B75M-D3V                    | [f3f1248ba8](https://linux-hardware.org/?probe=f3f1248ba8) | Jun 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4ab486dad3](https://linux-hardware.org/?probe=4ab486dad3) | Jun 19, 2020 |
| Lenovo        | Board                       | [b54709c54c](https://linux-hardware.org/?probe=b54709c54c) | Jun 18, 2020 |
| ASUSTek       | P5LD2                       | [62afb6c0f6](https://linux-hardware.org/?probe=62afb6c0f6) | Jun 17, 2020 |
| MSI           | 0A48                        | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| ASUSTek       | TUF Z370-PLUS GAMING II     | [44fc6290e2](https://linux-hardware.org/?probe=44fc6290e2) | Jun 17, 2020 |
| ASRock        | B450M-HDV R4.0              | [1d65bfcfd8](https://linux-hardware.org/?probe=1d65bfcfd8) | Jun 16, 2020 |
| ASRock        | Z87 Extreme4                | [48d5db7d11](https://linux-hardware.org/?probe=48d5db7d11) | Jun 15, 2020 |
| ASUSTek       | H170M-PLUS                  | [6cd72601db](https://linux-hardware.org/?probe=6cd72601db) | Jun 15, 2020 |
| ASUSTek       | P6T SE                      | [e9c237721a](https://linux-hardware.org/?probe=e9c237721a) | Jun 14, 2020 |
| Foxconn       | H55M-S                      | [1351c7b098](https://linux-hardware.org/?probe=1351c7b098) | Jun 14, 2020 |
| ASUSTek       | P6T SE                      | [0d83187de0](https://linux-hardware.org/?probe=0d83187de0) | Jun 13, 2020 |
| ASUSTek       | K31CD-K                     | [61a41772a3](https://linux-hardware.org/?probe=61a41772a3) | Jun 13, 2020 |
| ASRock        | P67 Pro3                    | [deaf1b5c77](https://linux-hardware.org/?probe=deaf1b5c77) | Jun 13, 2020 |
| ASRock        | Z170 Gaming K6+             | [291717bd8f](https://linux-hardware.org/?probe=291717bd8f) | Jun 12, 2020 |
| ASRock        | H81M-HDS R2.0               | [8d02c07803](https://linux-hardware.org/?probe=8d02c07803) | Jun 11, 2020 |
| ASUSTek       | A88XM-E                     | [2bfa6a1ebb](https://linux-hardware.org/?probe=2bfa6a1ebb) | Jun 11, 2020 |
| HP            | 2AF3                        | [0cedf0f08e](https://linux-hardware.org/?probe=0cedf0f08e) | Jun 11, 2020 |
| ASRock        | X99 WS                      | [9234f00976](https://linux-hardware.org/?probe=9234f00976) | Jun 11, 2020 |
| ASUSTek       | M5A78L-M LX3                | [ef59083b39](https://linux-hardware.org/?probe=ef59083b39) | Jun 11, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [d3226f3a97](https://linux-hardware.org/?probe=d3226f3a97) | Jun 11, 2020 |
| ASUSTek       | H81M-C                      | [25b68c6674](https://linux-hardware.org/?probe=25b68c6674) | Jun 11, 2020 |
| ASUSTek       | P5QPL-AM                    | [994e3df746](https://linux-hardware.org/?probe=994e3df746) | Jun 11, 2020 |
| Acer          | Aspire MC605 v1.0           | [351886a313](https://linux-hardware.org/?probe=351886a313) | Jun 10, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [60c0907918](https://linux-hardware.org/?probe=60c0907918) | Jun 09, 2020 |
| Dell          | 0M859N A00                  | [2f351afb31](https://linux-hardware.org/?probe=2f351afb31) | Jun 09, 2020 |
| Foxconn       | CALI                        | [3b87fbb0f6](https://linux-hardware.org/?probe=3b87fbb0f6) | Jun 08, 2020 |
| ASUSTek       | H81-PLUS                    | [c206a632a4](https://linux-hardware.org/?probe=c206a632a4) | Jun 08, 2020 |
| MSI           | Z390-A PRO                  | [ac8ac15297](https://linux-hardware.org/?probe=ac8ac15297) | Jun 07, 2020 |
| ASUSTek       | H81-PLUS                    | [7d17230c42](https://linux-hardware.org/?probe=7d17230c42) | Jun 07, 2020 |
| Gigabyte      | Z87-HD3                     | [db7f196be9](https://linux-hardware.org/?probe=db7f196be9) | Jun 07, 2020 |
| Gigabyte      | Z87-HD3                     | [819b048062](https://linux-hardware.org/?probe=819b048062) | Jun 07, 2020 |
| MSI           | MS-7367                     | [903853f0e0](https://linux-hardware.org/?probe=903853f0e0) | Jun 06, 2020 |
| MSI           | MS-7367                     | [ff291d3d82](https://linux-hardware.org/?probe=ff291d3d82) | Jun 06, 2020 |
| MSI           | 990FXA-GD80                 | [5b22c52803](https://linux-hardware.org/?probe=5b22c52803) | Jun 06, 2020 |
| Unknown       | SKYBAY                      | [1b3ecede5c](https://linux-hardware.org/?probe=1b3ecede5c) | Jun 05, 2020 |
| ASUSTek       | P5QL/EPU                    | [fad6d611e4](https://linux-hardware.org/?probe=fad6d611e4) | Jun 04, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [cbd263b17c](https://linux-hardware.org/?probe=cbd263b17c) | Jun 04, 2020 |
| HP            | 1905                        | [8392184a35](https://linux-hardware.org/?probe=8392184a35) | Jun 04, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| MSI           | 870A-G54                    | [f87a0d555b](https://linux-hardware.org/?probe=f87a0d555b) | Jun 04, 2020 |
| MSI           | 990FXA-GD80                 | [edd2d74904](https://linux-hardware.org/?probe=edd2d74904) | Jun 04, 2020 |
| Foxconn       | Newark HP P/N               | [78bd876125](https://linux-hardware.org/?probe=78bd876125) | Jun 03, 2020 |
| Lenovo        | Board                       | [67ffdf7c6b](https://linux-hardware.org/?probe=67ffdf7c6b) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X99 WS                      | [6855b583fc](https://linux-hardware.org/?probe=6855b583fc) | Jun 02, 2020 |
| ASUSTek       | TUF Z270 MARK 1             | [bd664fdcfb](https://linux-hardware.org/?probe=bd664fdcfb) | Jun 02, 2020 |
| ASRock        | 990FX Extreme4              | [46941a2ab6](https://linux-hardware.org/?probe=46941a2ab6) | Jun 02, 2020 |
| ASUSTek       | M4A78-E                     | [8d2fd93356](https://linux-hardware.org/?probe=8d2fd93356) | Jun 02, 2020 |
| ASUSTek       | M4A78-E                     | [925cfdaac0](https://linux-hardware.org/?probe=925cfdaac0) | Jun 02, 2020 |
| Lenovo        | Board                       | [b061f7cdf0](https://linux-hardware.org/?probe=b061f7cdf0) | Jun 01, 2020 |
| MSI           | B450-A PRO                  | [fcb9deefb9](https://linux-hardware.org/?probe=fcb9deefb9) | Jun 01, 2020 |
| MSI           | H81M-E33 V2                 | [b39a1f46b0](https://linux-hardware.org/?probe=b39a1f46b0) | May 31, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2b1da70b37](https://linux-hardware.org/?probe=2b1da70b37) | May 31, 2020 |
| ASRock        | J3455-ITX                   | [a57f0c75a9](https://linux-hardware.org/?probe=a57f0c75a9) | May 31, 2020 |
| ASUSTek       | BM5242                      | [21e9a468e7](https://linux-hardware.org/?probe=21e9a468e7) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| HP            | 0B54h D                     | [c2ecf87364](https://linux-hardware.org/?probe=c2ecf87364) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| Acer          | Aspire MC605 v1.0           | [f1876ad26c](https://linux-hardware.org/?probe=f1876ad26c) | May 29, 2020 |
| ASUSTek       | M5A78L-M LX3                | [bf8c7cf374](https://linux-hardware.org/?probe=bf8c7cf374) | May 29, 2020 |
| HP            | 1497                        | [cbe7690d2b](https://linux-hardware.org/?probe=cbe7690d2b) | May 29, 2020 |
| Acer          | Predator G3610              | [795bb124bd](https://linux-hardware.org/?probe=795bb124bd) | May 28, 2020 |
| ASUSTek       | P8H61-M LE                  | [d225118544](https://linux-hardware.org/?probe=d225118544) | May 28, 2020 |
| ASUSTek       | P8H61-M LE                  | [cc579e4b79](https://linux-hardware.org/?probe=cc579e4b79) | May 28, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [ab6eeb6b03](https://linux-hardware.org/?probe=ab6eeb6b03) | May 28, 2020 |
| Packard Be... | P5N-E SLI                   | [98b756ca5f](https://linux-hardware.org/?probe=98b756ca5f) | May 27, 2020 |
| ASRock        | B85M Pro4                   | [e757509bb5](https://linux-hardware.org/?probe=e757509bb5) | May 27, 2020 |
| ASRock        | B85M Pro4                   | [a0de60b801](https://linux-hardware.org/?probe=a0de60b801) | May 27, 2020 |
| ASUSTek       | P5KPL-VM                    | [ce9a82085b](https://linux-hardware.org/?probe=ce9a82085b) | May 27, 2020 |
| ASUSTek       | B150M-A                     | [6e5665e630](https://linux-hardware.org/?probe=6e5665e630) | May 27, 2020 |
| ASUSTek       | B150M-A                     | [b56e76e2e2](https://linux-hardware.org/?probe=b56e76e2e2) | May 27, 2020 |
| Gigabyte      | G31M-ES2L                   | [f9f7ec4c96](https://linux-hardware.org/?probe=f9f7ec4c96) | May 27, 2020 |
| ASUSTek       | M2A-MX                      | [9a548e9997](https://linux-hardware.org/?probe=9a548e9997) | May 26, 2020 |
| Acer          | Aspire MC605 v1.0           | [7c514cba36](https://linux-hardware.org/?probe=7c514cba36) | May 26, 2020 |
| MSI           | B75MA-P45                   | [3e047b1755](https://linux-hardware.org/?probe=3e047b1755) | May 26, 2020 |
| MSI           | Z97-GD65 GAMING             | [25bf43ac63](https://linux-hardware.org/?probe=25bf43ac63) | May 26, 2020 |
| Acer          | Aspire MC605 v1.0           | [367c03176d](https://linux-hardware.org/?probe=367c03176d) | May 26, 2020 |
| ABIT          | AG8                         | [da1995fd27](https://linux-hardware.org/?probe=da1995fd27) | May 25, 2020 |
| Gigabyte      | 970A-DS3P                   | [22fd82c249](https://linux-hardware.org/?probe=22fd82c249) | May 25, 2020 |
| ASRock        | Z87 Extreme4                | [142c4bbeb9](https://linux-hardware.org/?probe=142c4bbeb9) | May 25, 2020 |
| Acer          | Aspire TC-380               | [b21d6c5e0a](https://linux-hardware.org/?probe=b21d6c5e0a) | May 24, 2020 |
| Acer          | Aspire XC-703               | [39e547010a](https://linux-hardware.org/?probe=39e547010a) | May 24, 2020 |
| ASUSTek       | Rampage IV BLACK EDITION    | [ffef931e4f](https://linux-hardware.org/?probe=ffef931e4f) | May 24, 2020 |
| Dell          | 0200DY A01                  | [e692fa2c01](https://linux-hardware.org/?probe=e692fa2c01) | May 24, 2020 |
| ASUSTek       | H81-PLUS                    | [d5ecf72e99](https://linux-hardware.org/?probe=d5ecf72e99) | May 24, 2020 |
| ASUSTek       | B85M-G                      | [a83129ffae](https://linux-hardware.org/?probe=a83129ffae) | May 24, 2020 |
| Packard Be... | P5N-E SLI                   | [02945a8083](https://linux-hardware.org/?probe=02945a8083) | May 24, 2020 |
| Gigabyte      | Z87-HD3                     | [c8e2899998](https://linux-hardware.org/?probe=c8e2899998) | May 24, 2020 |
| Gigabyte      | Z87-HD3                     | [ed9b39d90f](https://linux-hardware.org/?probe=ed9b39d90f) | May 24, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [9a9af742c1](https://linux-hardware.org/?probe=9a9af742c1) | May 24, 2020 |
| ASUSTek       | D520MT_D520SF_D320MT        | [1222887619](https://linux-hardware.org/?probe=1222887619) | May 23, 2020 |
| ASUSTek       | M4N78 PRO                   | [4ab6c179f7](https://linux-hardware.org/?probe=4ab6c179f7) | May 23, 2020 |
| ASUSTek       | P5KPL-SE                    | [01318bf092](https://linux-hardware.org/?probe=01318bf092) | May 23, 2020 |
| ASUSTek       | P5QC                        | [bda5dfd8a8](https://linux-hardware.org/?probe=bda5dfd8a8) | May 22, 2020 |
| Acer          | Aspire XC-703               | [833660cb87](https://linux-hardware.org/?probe=833660cb87) | May 22, 2020 |
| Lenovo        | ThinkServer TS440           | [cb5fceb934](https://linux-hardware.org/?probe=cb5fceb934) | May 22, 2020 |
| Lenovo        | ThinkServer TS440           | [df1f30389d](https://linux-hardware.org/?probe=df1f30389d) | May 22, 2020 |
| Lenovo        | ThinkServer TS440           | [ec12232ca4](https://linux-hardware.org/?probe=ec12232ca4) | May 22, 2020 |
| ASUSTek       | P5QL-EM                     | [08e1b7191d](https://linux-hardware.org/?probe=08e1b7191d) | May 22, 2020 |
| ASUSTek       | P5QL-EM                     | [41a37083ee](https://linux-hardware.org/?probe=41a37083ee) | May 22, 2020 |
| ASUSTek       | P5QL-EM                     | [cfeb32ae8d](https://linux-hardware.org/?probe=cfeb32ae8d) | May 22, 2020 |
| ASUSTek       | H97-PLUS                    | [5b2b484f0e](https://linux-hardware.org/?probe=5b2b484f0e) | May 22, 2020 |
| ASRock        | H87 Pro4                    | [f1bf6d531f](https://linux-hardware.org/?probe=f1bf6d531f) | May 21, 2020 |
| ASUSTek       | P8H61                       | [43cf7287a5](https://linux-hardware.org/?probe=43cf7287a5) | May 21, 2020 |
| ASUSTek       | P5KPL-AM                    | [5fed9ba31b](https://linux-hardware.org/?probe=5fed9ba31b) | May 21, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [75407105a2](https://linux-hardware.org/?probe=75407105a2) | May 21, 2020 |
| ASUSTek       | M2N                         | [3430ea0717](https://linux-hardware.org/?probe=3430ea0717) | May 21, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b44991ab2a](https://linux-hardware.org/?probe=b44991ab2a) | May 21, 2020 |
| Gigabyte      | H310M S2H x.x               | [08dedd0736](https://linux-hardware.org/?probe=08dedd0736) | May 21, 2020 |
| ASRock        | H81M-HDS R2.0               | [b86e36e0e6](https://linux-hardware.org/?probe=b86e36e0e6) | May 20, 2020 |
| ASUSTek       | P5KR                        | [cbf5397d26](https://linux-hardware.org/?probe=cbf5397d26) | May 20, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| ASUSTek       | M2N                         | [4402b28a97](https://linux-hardware.org/?probe=4402b28a97) | May 19, 2020 |
| Acer          | Aspire XC-703               | [a9536218e3](https://linux-hardware.org/?probe=a9536218e3) | May 19, 2020 |
| ASUSTek       | Rampage III Extreme         | [b29b0df19a](https://linux-hardware.org/?probe=b29b0df19a) | May 18, 2020 |
| HP            | 18E5                        | [d20242d012](https://linux-hardware.org/?probe=d20242d012) | May 18, 2020 |
| ASRock        | 970 Pro3 R2.0               | [fcdc86702e](https://linux-hardware.org/?probe=fcdc86702e) | May 18, 2020 |
| Gigabyte      | Z87X-UD7 TH-CF              | [5d08766762](https://linux-hardware.org/?probe=5d08766762) | May 18, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [d50f2e8d20](https://linux-hardware.org/?probe=d50f2e8d20) | May 17, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [8ccc20ec45](https://linux-hardware.org/?probe=8ccc20ec45) | May 17, 2020 |
| ASRock        | G31M-GS                     | [b172d8f701](https://linux-hardware.org/?probe=b172d8f701) | May 17, 2020 |
| MSI           | A320M PRO-VD/S              | [c2ff29aad0](https://linux-hardware.org/?probe=c2ff29aad0) | May 17, 2020 |
| ASUSTek       | BM5242                      | [20636dd2dc](https://linux-hardware.org/?probe=20636dd2dc) | May 17, 2020 |
| HP            | 0B4Ch D                     | [370d732bb1](https://linux-hardware.org/?probe=370d732bb1) | May 16, 2020 |
| HP            | 0B4Ch D                     | [7231b7a7e0](https://linux-hardware.org/?probe=7231b7a7e0) | May 16, 2020 |
| Gigabyte      | H97-HD3                     | [9e55f80594](https://linux-hardware.org/?probe=9e55f80594) | May 16, 2020 |
| Gigabyte      | H97-HD3                     | [ec6d78f2d0](https://linux-hardware.org/?probe=ec6d78f2d0) | May 16, 2020 |
| Unknown       | X79A                        | [898c290e35](https://linux-hardware.org/?probe=898c290e35) | May 16, 2020 |
| ASUSTek       | M2N                         | [8476414a35](https://linux-hardware.org/?probe=8476414a35) | May 16, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [ed3b185bfe](https://linux-hardware.org/?probe=ed3b185bfe) | May 16, 2020 |
| ASUSTek       | M2N                         | [baa1c7b3a3](https://linux-hardware.org/?probe=baa1c7b3a3) | May 16, 2020 |
| ASUSTek       | M2N                         | [0dc968f3dd](https://linux-hardware.org/?probe=0dc968f3dd) | May 16, 2020 |
| HP            | 18E5                        | [789e80dc68](https://linux-hardware.org/?probe=789e80dc68) | May 16, 2020 |
| ASUSTek       | P5GD1                       | [01dcb22582](https://linux-hardware.org/?probe=01dcb22582) | May 15, 2020 |
| MSI           | B75MA-P45                   | [7d562591b4](https://linux-hardware.org/?probe=7d562591b4) | May 15, 2020 |
| ASRock        | X570 Extreme4               | [f27120c647](https://linux-hardware.org/?probe=f27120c647) | May 15, 2020 |
| HP            | 0A00h                       | [b2d56089ac](https://linux-hardware.org/?probe=b2d56089ac) | May 15, 2020 |
| ASRock        | H81M-HDS R2.0               | [50e7e825a5](https://linux-hardware.org/?probe=50e7e825a5) | May 15, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [8558e7f816](https://linux-hardware.org/?probe=8558e7f816) | May 15, 2020 |
| ASRock        | 970 Pro3 R2.0               | [4feef6431f](https://linux-hardware.org/?probe=4feef6431f) | May 15, 2020 |
| ASUSTek       | P8H61-M LE                  | [44e17deb82](https://linux-hardware.org/?probe=44e17deb82) | May 15, 2020 |
| ASUSTek       | PRIME A320M-K               | [bf9d111e62](https://linux-hardware.org/?probe=bf9d111e62) | May 15, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| ASUSTek       | B75M-A                      | [c2166b0fd6](https://linux-hardware.org/?probe=c2166b0fd6) | May 14, 2020 |
| ASUSTek       | B75M-A                      | [1f7883ca50](https://linux-hardware.org/?probe=1f7883ca50) | May 14, 2020 |
| ASUSTek       | M2N                         | [0fcb482456](https://linux-hardware.org/?probe=0fcb482456) | May 14, 2020 |
| ASUSTek       | M2N                         | [ee90a31b7c](https://linux-hardware.org/?probe=ee90a31b7c) | May 14, 2020 |
| Dell          | 0KRC95 A02                  | [76e436d39a](https://linux-hardware.org/?probe=76e436d39a) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [58b07f389d](https://linux-hardware.org/?probe=58b07f389d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [47c81c501b](https://linux-hardware.org/?probe=47c81c501b) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [2ae542835d](https://linux-hardware.org/?probe=2ae542835d) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3b57496d5](https://linux-hardware.org/?probe=b3b57496d5) | May 13, 2020 |
| MSI           | B75MA-P45                   | [1937259a0d](https://linux-hardware.org/?probe=1937259a0d) | May 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [4c8df7e63e](https://linux-hardware.org/?probe=4c8df7e63e) | May 12, 2020 |
| Dell          | 0M859N A00                  | [b78c1a964f](https://linux-hardware.org/?probe=b78c1a964f) | May 12, 2020 |
| Dell          | 0M859N A00                  | [87337cb26b](https://linux-hardware.org/?probe=87337cb26b) | May 12, 2020 |
| Gigabyte      | H81M-S2V                    | [83f94b3a67](https://linux-hardware.org/?probe=83f94b3a67) | May 12, 2020 |
| Gigabyte      | H81M-S2V                    | [735da03dae](https://linux-hardware.org/?probe=735da03dae) | May 12, 2020 |
| ASUSTek       | P6T DELUXE V2               | [01eaa9281b](https://linux-hardware.org/?probe=01eaa9281b) | May 12, 2020 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [b95be763fd](https://linux-hardware.org/?probe=b95be763fd) | May 11, 2020 |
| ASUSTek       | P5QC                        | [e2a6be3e26](https://linux-hardware.org/?probe=e2a6be3e26) | May 10, 2020 |
| ASUSTek       | Rampage III Extreme         | [33e413d30b](https://linux-hardware.org/?probe=33e413d30b) | May 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [656d026898](https://linux-hardware.org/?probe=656d026898) | May 10, 2020 |
| MSI           | X99S SLI PLUS               | [350cac4135](https://linux-hardware.org/?probe=350cac4135) | May 10, 2020 |
| Acer          | Predator G3610              | [5650f42fd4](https://linux-hardware.org/?probe=5650f42fd4) | May 10, 2020 |
| Lenovo        | Board                       | [aa12d5c975](https://linux-hardware.org/?probe=aa12d5c975) | May 10, 2020 |
| ASUSTek       | VM40B                       | [bb482dfa03](https://linux-hardware.org/?probe=bb482dfa03) | May 09, 2020 |
| ASUSTek       | VM40B                       | [167e4b604a](https://linux-hardware.org/?probe=167e4b604a) | May 09, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [1abce91d71](https://linux-hardware.org/?probe=1abce91d71) | May 08, 2020 |
| Gateway       | FG43D                       | [8768f2455d](https://linux-hardware.org/?probe=8768f2455d) | May 07, 2020 |
| Gateway       | FG43D                       | [7822e5bde4](https://linux-hardware.org/?probe=7822e5bde4) | May 07, 2020 |
| ASUSTek       | P5QC                        | [10112b3f2c](https://linux-hardware.org/?probe=10112b3f2c) | May 06, 2020 |
| Dell          | 0GU083 A00                  | [5f05efe407](https://linux-hardware.org/?probe=5f05efe407) | May 06, 2020 |
| Unknown       | Unknown                     | [57964c259f](https://linux-hardware.org/?probe=57964c259f) | May 06, 2020 |
| Packard Be... | RC415                       | [5622763899](https://linux-hardware.org/?probe=5622763899) | May 05, 2020 |
| ASRock        | A320M-HDV                   | [d8eddb8d6d](https://linux-hardware.org/?probe=d8eddb8d6d) | May 05, 2020 |
| ASUSTek       | CM6870                      | [711f850b1f](https://linux-hardware.org/?probe=711f850b1f) | May 03, 2020 |
| Intel         | D525MW AAE93082-402         | [97d38493fc](https://linux-hardware.org/?probe=97d38493fc) | May 03, 2020 |
| Acer          | F672CR R01-A4               | [5f46154217](https://linux-hardware.org/?probe=5f46154217) | May 02, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [fb5bc9acce](https://linux-hardware.org/?probe=fb5bc9acce) | May 02, 2020 |
| ASRock        | H310M-HDV                   | [f647c8cd04](https://linux-hardware.org/?probe=f647c8cd04) | May 02, 2020 |
| ASUSTek       | P5GD1                       | [de0b190907](https://linux-hardware.org/?probe=de0b190907) | May 02, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [b92ae2e711](https://linux-hardware.org/?probe=b92ae2e711) | May 02, 2020 |
| VIA Techno... | P4X266-8233                 | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| ASUSTek       | P7P55D LE                   | [556741d80f](https://linux-hardware.org/?probe=556741d80f) | May 02, 2020 |
| Packard Be... | iMedia S2883                | [40908ea5f5](https://linux-hardware.org/?probe=40908ea5f5) | May 02, 2020 |
| ASUSTek       | H110M-R                     | [ae1a9bd460](https://linux-hardware.org/?probe=ae1a9bd460) | May 02, 2020 |
| ASRock        | H87 Pro4                    | [f9947cb060](https://linux-hardware.org/?probe=f9947cb060) | May 02, 2020 |
| HP            | 1790                        | [730d11b794](https://linux-hardware.org/?probe=730d11b794) | May 01, 2020 |
| Packard Be... | iMedia S2883                | [81d435f21b](https://linux-hardware.org/?probe=81d435f21b) | May 01, 2020 |
| MSI           | B360M BAZOOKA               | [56931d8a6a](https://linux-hardware.org/?probe=56931d8a6a) | May 01, 2020 |
| ASUSTek       | P6T DELUXE V2               | [317ca29a07](https://linux-hardware.org/?probe=317ca29a07) | May 01, 2020 |
| Packard Be... | RC415                       | [7b59e9b270](https://linux-hardware.org/?probe=7b59e9b270) | May 01, 2020 |
| Packard Be... | iMedia S2883                | [0cfaf4e4f7](https://linux-hardware.org/?probe=0cfaf4e4f7) | May 01, 2020 |
| ASUSTek       | P5Q3                        | [5b8dafd7d6](https://linux-hardware.org/?probe=5b8dafd7d6) | May 01, 2020 |
| Packard Be... | iMedia S2883                | [b9769749e0](https://linux-hardware.org/?probe=b9769749e0) | May 01, 2020 |
| Packard Be... | iMedia S2883                | [15cfccfb60](https://linux-hardware.org/?probe=15cfccfb60) | May 01, 2020 |
| Packard Be... | P5N-E SLI                   | [1657b88c97](https://linux-hardware.org/?probe=1657b88c97) | May 01, 2020 |
| ASRock        | B450M-HDV R4.0              | [95aefb5e5e](https://linux-hardware.org/?probe=95aefb5e5e) | May 01, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [d0fe69a9da](https://linux-hardware.org/?probe=d0fe69a9da) | Apr 30, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [0f93edbbad](https://linux-hardware.org/?probe=0f93edbbad) | Apr 30, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [ce15f64a3a](https://linux-hardware.org/?probe=ce15f64a3a) | Apr 30, 2020 |
| ASUSTek       | PRIME B365M-K               | [bd8d537bfe](https://linux-hardware.org/?probe=bd8d537bfe) | Apr 30, 2020 |
| Foxconn       | H61MXT1/F2/-S/-V            | [9ccf03cfb4](https://linux-hardware.org/?probe=9ccf03cfb4) | Apr 30, 2020 |
| MSI           | P55M-GD45                   | [4771b4f606](https://linux-hardware.org/?probe=4771b4f606) | Apr 29, 2020 |
| MSI           | P55M-GD45                   | [d4ee90b159](https://linux-hardware.org/?probe=d4ee90b159) | Apr 29, 2020 |
| Dell          | 0FJ030                      | [8cae3f8b96](https://linux-hardware.org/?probe=8cae3f8b96) | Apr 29, 2020 |
| MSI           | B360M BAZOOKA               | [20b3124f40](https://linux-hardware.org/?probe=20b3124f40) | Apr 29, 2020 |
| ASUSTek       | P5VDC-TVM                   | [b57a63cb7a](https://linux-hardware.org/?probe=b57a63cb7a) | Apr 29, 2020 |
| ASRock        | 960GC-GS FX                 | [7151586804](https://linux-hardware.org/?probe=7151586804) | Apr 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [abb6b19d0d](https://linux-hardware.org/?probe=abb6b19d0d) | Apr 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [4d1570be7f](https://linux-hardware.org/?probe=4d1570be7f) | Apr 29, 2020 |
| Sapphire      | PC-AM2RS790G                | [4431c5fffc](https://linux-hardware.org/?probe=4431c5fffc) | Apr 29, 2020 |
| Sapphire      | PC-AM2RS790G                | [b19fa02891](https://linux-hardware.org/?probe=b19fa02891) | Apr 29, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [bddaf3c123](https://linux-hardware.org/?probe=bddaf3c123) | Apr 28, 2020 |
| HP            | 09F0h                       | [810a0c1fa8](https://linux-hardware.org/?probe=810a0c1fa8) | Apr 28, 2020 |
| Sapphire      | PC-AM2RS790G                | [45f0a95c2f](https://linux-hardware.org/?probe=45f0a95c2f) | Apr 28, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [40afc65fe2](https://linux-hardware.org/?probe=40afc65fe2) | Apr 28, 2020 |
| Sapphire      | PC-AM2RS790G                | [6b4a5a8cc3](https://linux-hardware.org/?probe=6b4a5a8cc3) | Apr 28, 2020 |
| ASRock        | ConRoe1333-D667             | [3598a3b12f](https://linux-hardware.org/?probe=3598a3b12f) | Apr 27, 2020 |
| ASRock        | ConRoe1333-D667             | [5ebaff49f6](https://linux-hardware.org/?probe=5ebaff49f6) | Apr 27, 2020 |
| Sapphire      | PC-AM2RS790G                | [48f2c478f1](https://linux-hardware.org/?probe=48f2c478f1) | Apr 27, 2020 |
| HP            | 0A00h                       | [49db06b1c7](https://linux-hardware.org/?probe=49db06b1c7) | Apr 27, 2020 |
| HP            | 0A00h                       | [1202e0dbe0](https://linux-hardware.org/?probe=1202e0dbe0) | Apr 27, 2020 |
| Sapphire      | PC-AM2RS790G                | [f06326b9fd](https://linux-hardware.org/?probe=f06326b9fd) | Apr 27, 2020 |
| Sapphire      | PC-AM2RS790G                | [c5815f3d90](https://linux-hardware.org/?probe=c5815f3d90) | Apr 27, 2020 |
| Sapphire      | PC-AM2RS790G                | [9c8e2d93f2](https://linux-hardware.org/?probe=9c8e2d93f2) | Apr 27, 2020 |
| Pegatron      | Benicia                     | [97c28368c1](https://linux-hardware.org/?probe=97c28368c1) | Apr 27, 2020 |
| HP            | 0A00h                       | [1c8e6418a6](https://linux-hardware.org/?probe=1c8e6418a6) | Apr 26, 2020 |
| ASRock        | G41M-S3                     | [16aa260792](https://linux-hardware.org/?probe=16aa260792) | Apr 26, 2020 |
| ASUSTek       | P5B                         | [a7e0edcdc1](https://linux-hardware.org/?probe=a7e0edcdc1) | Apr 26, 2020 |
| ASUSTek       | Berkeley                    | [5059348fc2](https://linux-hardware.org/?probe=5059348fc2) | Apr 26, 2020 |
| IP3 Tech      | GB3                         | [334e87a3e6](https://linux-hardware.org/?probe=334e87a3e6) | Apr 26, 2020 |
| ASUSTek       | Berkeley                    | [4c665eb82c](https://linux-hardware.org/?probe=4c665eb82c) | Apr 26, 2020 |
| IP3 Tech      | GB3                         | [fa71fcce62](https://linux-hardware.org/?probe=fa71fcce62) | Apr 26, 2020 |
| IP3 Tech      | GB3                         | [2f6c60a8f6](https://linux-hardware.org/?probe=2f6c60a8f6) | Apr 26, 2020 |
| Lenovo        | 1.0                         | [c808008439](https://linux-hardware.org/?probe=c808008439) | Apr 26, 2020 |
| Sapphire      | PC-AM2RS790G                | [3ead8542b1](https://linux-hardware.org/?probe=3ead8542b1) | Apr 26, 2020 |
| Gigabyte      | H77-DS3H                    | [e47dd23222](https://linux-hardware.org/?probe=e47dd23222) | Apr 26, 2020 |
| Sapphire      | PC-AM2RS790G                | [0275e388db](https://linux-hardware.org/?probe=0275e388db) | Apr 26, 2020 |
| Sapphire      | PC-AM2RS790G                | [4dd02b48e4](https://linux-hardware.org/?probe=4dd02b48e4) | Apr 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [b78fe72f96](https://linux-hardware.org/?probe=b78fe72f96) | Apr 26, 2020 |
| Acer          | Aspire M3970                | [6a9efe189f](https://linux-hardware.org/?probe=6a9efe189f) | Apr 26, 2020 |
| ASUSTek       | M5A99X EVO                  | [bf6131996f](https://linux-hardware.org/?probe=bf6131996f) | Apr 25, 2020 |
| ABIT          | IP35 Pro                    | [23dae6710c](https://linux-hardware.org/?probe=23dae6710c) | Apr 25, 2020 |
| ABIT          | IP35 Pro                    | [0465b43386](https://linux-hardware.org/?probe=0465b43386) | Apr 25, 2020 |
| ASRock        | AM2NF6G-VSTA                | [b701c37d96](https://linux-hardware.org/?probe=b701c37d96) | Apr 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | [53da2ed7fd](https://linux-hardware.org/?probe=53da2ed7fd) | Apr 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | [95dbe6cf3c](https://linux-hardware.org/?probe=95dbe6cf3c) | Apr 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | [dd12dc9477](https://linux-hardware.org/?probe=dd12dc9477) | Apr 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | [e5ec721a65](https://linux-hardware.org/?probe=e5ec721a65) | Apr 23, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [19a9020fef](https://linux-hardware.org/?probe=19a9020fef) | Apr 22, 2020 |
| IBM           | Board                       | [bcbf4f1456](https://linux-hardware.org/?probe=bcbf4f1456) | Apr 21, 2020 |
| ASUSTek       | M2A-MX                      | [1a52399cac](https://linux-hardware.org/?probe=1a52399cac) | Apr 21, 2020 |
| Lenovo        | Board                       | [981421d4ed](https://linux-hardware.org/?probe=981421d4ed) | Apr 21, 2020 |
| ABIT          | IL8                         | [712447d549](https://linux-hardware.org/?probe=712447d549) | Apr 21, 2020 |
| ABIT          | IL8                         | [fbbd462af2](https://linux-hardware.org/?probe=fbbd462af2) | Apr 21, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [908176d872](https://linux-hardware.org/?probe=908176d872) | Apr 20, 2020 |
| ASUSTek       | Z97-DELUXE                  | [44ff723c0e](https://linux-hardware.org/?probe=44ff723c0e) | Apr 20, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | [17a06687d4](https://linux-hardware.org/?probe=17a06687d4) | Apr 20, 2020 |
| ASUSTek       | P5V-VM SE DH                | [ae60d767a3](https://linux-hardware.org/?probe=ae60d767a3) | Apr 20, 2020 |
| AMI           | Cherry Trail CR             | [dfd8e663f9](https://linux-hardware.org/?probe=dfd8e663f9) | Apr 19, 2020 |
| MSI           | Z97M-G43                    | [f5a08f55c6](https://linux-hardware.org/?probe=f5a08f55c6) | Apr 19, 2020 |
| IBM           | Board                       | [5419a52872](https://linux-hardware.org/?probe=5419a52872) | Apr 19, 2020 |
| ASUSTek       | LOCKTITE                    | [53e1852894](https://linux-hardware.org/?probe=53e1852894) | Apr 19, 2020 |
| MSI           | Z270 GAMING M5              | [1b4bf985a0](https://linux-hardware.org/?probe=1b4bf985a0) | Apr 18, 2020 |
| ASUSTek       | P8P67 LE                    | [6dcd647bf7](https://linux-hardware.org/?probe=6dcd647bf7) | Apr 18, 2020 |
| ABIT          | IL8                         | [0c284dcdad](https://linux-hardware.org/?probe=0c284dcdad) | Apr 18, 2020 |
| ABIT          | IP35 Pro                    | [c1d15add68](https://linux-hardware.org/?probe=c1d15add68) | Apr 18, 2020 |
| ASUSTek       | M2R-FVM                     | [3bef28de93](https://linux-hardware.org/?probe=3bef28de93) | Apr 17, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [0146fda3a1](https://linux-hardware.org/?probe=0146fda3a1) | Apr 17, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [704789bcd1](https://linux-hardware.org/?probe=704789bcd1) | Apr 17, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [361a6489f3](https://linux-hardware.org/?probe=361a6489f3) | Apr 17, 2020 |
| ASUSTek       | P8Z77-M                     | [665e2e1f1b](https://linux-hardware.org/?probe=665e2e1f1b) | Apr 16, 2020 |
| ASUSTek       | P8Z77-M                     | [ff16f66fab](https://linux-hardware.org/?probe=ff16f66fab) | Apr 16, 2020 |
| ASUSTek       | P8Z77-M                     | [812b5e4992](https://linux-hardware.org/?probe=812b5e4992) | Apr 16, 2020 |
| ASRock        | ALiveNF6G-GLAN              | [7c79905071](https://linux-hardware.org/?probe=7c79905071) | Apr 16, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [7a4f6d1d63](https://linux-hardware.org/?probe=7a4f6d1d63) | Apr 16, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [647c2fc253](https://linux-hardware.org/?probe=647c2fc253) | Apr 16, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [06ea93b075](https://linux-hardware.org/?probe=06ea93b075) | Apr 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b6f50271de](https://linux-hardware.org/?probe=b6f50271de) | Apr 15, 2020 |
| ASUSTek       | P5Q-PRO                     | [0bf976b026](https://linux-hardware.org/?probe=0bf976b026) | Apr 14, 2020 |
| HP            | 8459                        | [c241c2fa75](https://linux-hardware.org/?probe=c241c2fa75) | Apr 13, 2020 |
| ASUSTek       | A88XM-PLUS                  | [2d34598a72](https://linux-hardware.org/?probe=2d34598a72) | Apr 13, 2020 |
| Acer          | Veriton M275                | [01ac64098a](https://linux-hardware.org/?probe=01ac64098a) | Apr 12, 2020 |
| Acer          | Veriton M275                | [11cf2e3a5f](https://linux-hardware.org/?probe=11cf2e3a5f) | Apr 12, 2020 |
| ASUSTek       | H81M-C                      | [fb8936ea7c](https://linux-hardware.org/?probe=fb8936ea7c) | Apr 12, 2020 |
| Pegatron      | Benicia                     | [834f8499aa](https://linux-hardware.org/?probe=834f8499aa) | Apr 12, 2020 |
| ASUSTek       | H81M-C                      | [0d90df7f1d](https://linux-hardware.org/?probe=0d90df7f1d) | Apr 12, 2020 |
| ASUSTek       | H81M-C                      | [7ae6d7f5f0](https://linux-hardware.org/?probe=7ae6d7f5f0) | Apr 12, 2020 |
| MSI           | B75MA-P45                   | [2d42555b6f](https://linux-hardware.org/?probe=2d42555b6f) | Apr 11, 2020 |
| ASUSTek       | H87M-PRO                    | [0df5cc9951](https://linux-hardware.org/?probe=0df5cc9951) | Apr 11, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7c58e766b8](https://linux-hardware.org/?probe=7c58e766b8) | Apr 11, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [5157b01553](https://linux-hardware.org/?probe=5157b01553) | Apr 11, 2020 |
| ASUSTek       | P6T DELUXE V2               | [a07541d089](https://linux-hardware.org/?probe=a07541d089) | Apr 11, 2020 |
| ASUSTek       | P5K-VM                      | [90e9457471](https://linux-hardware.org/?probe=90e9457471) | Apr 11, 2020 |
| ASRock        | Z170M Pro4S                 | [9453bc1d99](https://linux-hardware.org/?probe=9453bc1d99) | Apr 10, 2020 |
| ASRock        | Z170 Pro4S                  | [063d99b2f3](https://linux-hardware.org/?probe=063d99b2f3) | Apr 10, 2020 |
| Pegatron      | Benicia                     | [1f1e11cc3d](https://linux-hardware.org/?probe=1f1e11cc3d) | Apr 10, 2020 |
| Pegatron      | Benicia                     | [b985c461f2](https://linux-hardware.org/?probe=b985c461f2) | Apr 10, 2020 |
| PROLINE       | ProlinePartner              | [0975ec8527](https://linux-hardware.org/?probe=0975ec8527) | Apr 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f1545c9695](https://linux-hardware.org/?probe=f1545c9695) | Apr 10, 2020 |
| Gigabyte      | B360N WIFI-CF               | [bbcff2e362](https://linux-hardware.org/?probe=bbcff2e362) | Apr 09, 2020 |
| Acer          | F89M R03-A4                 | [fca7fd42d3](https://linux-hardware.org/?probe=fca7fd42d3) | Apr 09, 2020 |
| Acer          | Aspire M1930                | [0d3a06e61c](https://linux-hardware.org/?probe=0d3a06e61c) | Apr 09, 2020 |
| HP            | 09E8h                       | [07a8064330](https://linux-hardware.org/?probe=07a8064330) | Apr 09, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a8f302d3d9](https://linux-hardware.org/?probe=a8f302d3d9) | Apr 09, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [60a1680e59](https://linux-hardware.org/?probe=60a1680e59) | Apr 09, 2020 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [8831718f63](https://linux-hardware.org/?probe=8831718f63) | Apr 08, 2020 |
| ASRock        | J3455-ITX                   | [d88f5df6ae](https://linux-hardware.org/?probe=d88f5df6ae) | Apr 07, 2020 |
| ASUSTek       | M4A78 PRO                   | [09eebe5f93](https://linux-hardware.org/?probe=09eebe5f93) | Apr 07, 2020 |
| HP            | 0AE8h C                     | [b89098aef9](https://linux-hardware.org/?probe=b89098aef9) | Apr 07, 2020 |
| ASRock        | Q1900M                      | [11c1c6b498](https://linux-hardware.org/?probe=11c1c6b498) | Apr 06, 2020 |
| HP            | 2820h                       | [bcfc7372d3](https://linux-hardware.org/?probe=bcfc7372d3) | Apr 05, 2020 |
| ASUSTek       | M2N-E SLI                   | [67526e6d00](https://linux-hardware.org/?probe=67526e6d00) | Apr 05, 2020 |
| Packard Be... | imedia S3850                | [c7fcff3554](https://linux-hardware.org/?probe=c7fcff3554) | Apr 05, 2020 |
| Packard Be... | imedia S3850                | [3fd14e61c0](https://linux-hardware.org/?probe=3fd14e61c0) | Apr 05, 2020 |
| ASRock        | B85M DASH/OL R2.0           | [e7a1d7cb2d](https://linux-hardware.org/?probe=e7a1d7cb2d) | Apr 04, 2020 |
| ASUSTek       | M2N-E SLI                   | [5f55724855](https://linux-hardware.org/?probe=5f55724855) | Apr 04, 2020 |
| ASRock        | B75M DASH G/A               | [fdc8bc5879](https://linux-hardware.org/?probe=fdc8bc5879) | Apr 04, 2020 |
| ASUSTek       | EB1012P                     | [48018968da](https://linux-hardware.org/?probe=48018968da) | Apr 04, 2020 |
| Acer          | Veriton X270                | [54a698a4fe](https://linux-hardware.org/?probe=54a698a4fe) | Apr 03, 2020 |
| ASUSTek       | P5B                         | [63df636f26](https://linux-hardware.org/?probe=63df636f26) | Apr 03, 2020 |
| Biostar       | G41D3+                      | [63d7a92feb](https://linux-hardware.org/?probe=63d7a92feb) | Apr 03, 2020 |
| Pegatron      | Narra6                      | [12207a4617](https://linux-hardware.org/?probe=12207a4617) | Apr 03, 2020 |
| MSI           | Z97S SLI Krait Edition      | [788d189c2d](https://linux-hardware.org/?probe=788d189c2d) | Apr 02, 2020 |
| Lenovo        | SHARKBAY NOK                | [cb0a726c0b](https://linux-hardware.org/?probe=cb0a726c0b) | Apr 02, 2020 |
| Acer          | Aspire M1930                | [4287f93dfc](https://linux-hardware.org/?probe=4287f93dfc) | Apr 02, 2020 |
| Acer          | Aspire M1930                | [9c008552bc](https://linux-hardware.org/?probe=9c008552bc) | Apr 02, 2020 |
| ASUSTek       | EB1012P                     | [daec395f29](https://linux-hardware.org/?probe=daec395f29) | Apr 02, 2020 |
| Packard Be... | H57M01                      | [1e0cffbb84](https://linux-hardware.org/?probe=1e0cffbb84) | Apr 01, 2020 |
| HP            | 2820h                       | [4118b6145d](https://linux-hardware.org/?probe=4118b6145d) | Apr 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [500a401a31](https://linux-hardware.org/?probe=500a401a31) | Apr 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b4135a559e](https://linux-hardware.org/?probe=b4135a559e) | Apr 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [6c02c278f7](https://linux-hardware.org/?probe=6c02c278f7) | Apr 01, 2020 |
| Lenovo        | SHARKBAY NOK                | [f3d3747b56](https://linux-hardware.org/?probe=f3d3747b56) | Mar 31, 2020 |
| Acer          | EG31M R01-A3                | [38c5df6599](https://linux-hardware.org/?probe=38c5df6599) | Mar 31, 2020 |
| HP            | 2820h                       | [c31058208d](https://linux-hardware.org/?probe=c31058208d) | Mar 31, 2020 |
| HP            | 2820h                       | [962d4c2805](https://linux-hardware.org/?probe=962d4c2805) | Mar 31, 2020 |
| Gigabyte      | X99P-SLI-CF                 | [7e9a256992](https://linux-hardware.org/?probe=7e9a256992) | Mar 31, 2020 |
| Gigabyte      | X99P-SLI-CF                 | [403ba7d527](https://linux-hardware.org/?probe=403ba7d527) | Mar 31, 2020 |
| Gigabyte      | X99P-SLI-CF                 | [a585635a04](https://linux-hardware.org/?probe=a585635a04) | Mar 31, 2020 |
| Packard Be... | PBGL00                      | [15a3d69bad](https://linux-hardware.org/?probe=15a3d69bad) | Mar 30, 2020 |
| ASRock        | B85M DASH/OL R2.0           | [2237c8a97a](https://linux-hardware.org/?probe=2237c8a97a) | Mar 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [50d41d02af](https://linux-hardware.org/?probe=50d41d02af) | Mar 30, 2020 |
| ASUSTek       | P7P55 WS SUPERCOMPUTER      | [8de506df3f](https://linux-hardware.org/?probe=8de506df3f) | Mar 30, 2020 |
| ASUSTek       | P5B                         | [9b46a501ad](https://linux-hardware.org/?probe=9b46a501ad) | Mar 29, 2020 |
| ASUSTek       | P5B                         | [42af89f000](https://linux-hardware.org/?probe=42af89f000) | Mar 28, 2020 |
| Packard Be... | H57M01                      | [1b972e7238](https://linux-hardware.org/?probe=1b972e7238) | Mar 28, 2020 |
| MSI           | 0A48                        | [ef81bcbd99](https://linux-hardware.org/?probe=ef81bcbd99) | Mar 28, 2020 |
| ASUSTek       | PRIME Z270-A                | [848f7859fe](https://linux-hardware.org/?probe=848f7859fe) | Mar 28, 2020 |
| ASUSTek       | M3N78-VM                    | [063f395c03](https://linux-hardware.org/?probe=063f395c03) | Mar 27, 2020 |
| ASRock        | 890GX Pro3                  | [b6e1b24703](https://linux-hardware.org/?probe=b6e1b24703) | Mar 27, 2020 |
| ASRock        | 890GX Pro3                  | [018e6d5f28](https://linux-hardware.org/?probe=018e6d5f28) | Mar 27, 2020 |
| ASRock        | G41M-VS3                    | [9a633ab363](https://linux-hardware.org/?probe=9a633ab363) | Mar 26, 2020 |
| ASRock        | G41M-VS3                    | [985df839b0](https://linux-hardware.org/?probe=985df839b0) | Mar 26, 2020 |
| ASUSTek       | M4A87TD/USB3                | [f866cfa800](https://linux-hardware.org/?probe=f866cfa800) | Mar 26, 2020 |
| ASUSTek       | P5G41T-M LE                 | [05ac658c7f](https://linux-hardware.org/?probe=05ac658c7f) | Mar 26, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [2160b3217e](https://linux-hardware.org/?probe=2160b3217e) | Mar 25, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [105f3f7e4b](https://linux-hardware.org/?probe=105f3f7e4b) | Mar 25, 2020 |
| MSI           | H110M PRO-D                 | [8f32d8b56f](https://linux-hardware.org/?probe=8f32d8b56f) | Mar 25, 2020 |
| HP            | 3032h                       | [9b8163360b](https://linux-hardware.org/?probe=9b8163360b) | Mar 24, 2020 |
| ASUSTek       | P5Q-PRO                     | [65d45b878e](https://linux-hardware.org/?probe=65d45b878e) | Mar 24, 2020 |
| Acer          | RS780DV                     | [21944869fd](https://linux-hardware.org/?probe=21944869fd) | Mar 24, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9404088765](https://linux-hardware.org/?probe=9404088765) | Mar 24, 2020 |
| HP            | 83F0                        | [78b57c49a6](https://linux-hardware.org/?probe=78b57c49a6) | Mar 23, 2020 |
| ASRock        | B450M-HDV R4.0              | [b06b8e469d](https://linux-hardware.org/?probe=b06b8e469d) | Mar 23, 2020 |
| HP            | 3029h                       | [928204ecf0](https://linux-hardware.org/?probe=928204ecf0) | Mar 22, 2020 |
| MSI           | B450-A PRO                  | [1de480e90f](https://linux-hardware.org/?probe=1de480e90f) | Mar 22, 2020 |
| MSI           | B450-A PRO                  | [0f47330ed4](https://linux-hardware.org/?probe=0f47330ed4) | Mar 22, 2020 |
| ASUSTek       | K8V-MX                      | [cf2b767974](https://linux-hardware.org/?probe=cf2b767974) | Mar 22, 2020 |
| ASRock        | J3455-ITX                   | [dc5c76ee52](https://linux-hardware.org/?probe=dc5c76ee52) | Mar 22, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | [f2848a92da](https://linux-hardware.org/?probe=f2848a92da) | Mar 22, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [401f95eb7d](https://linux-hardware.org/?probe=401f95eb7d) | Mar 21, 2020 |
| ASUSTek       | P5B-E                       | [ac36f1cf72](https://linux-hardware.org/?probe=ac36f1cf72) | Mar 21, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [b4d14a98ef](https://linux-hardware.org/?probe=b4d14a98ef) | Mar 20, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | [6e9e6c7f1e](https://linux-hardware.org/?probe=6e9e6c7f1e) | Mar 20, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [642694d59f](https://linux-hardware.org/?probe=642694d59f) | Mar 19, 2020 |
| HP            | 3029h                       | [c784005e2d](https://linux-hardware.org/?probe=c784005e2d) | Mar 18, 2020 |
| Gigabyte      | M61PME-S2P                  | [fd2e75315a](https://linux-hardware.org/?probe=fd2e75315a) | Mar 18, 2020 |
| Gigabyte      | M61PME-S2P                  | [38af4d7d2e](https://linux-hardware.org/?probe=38af4d7d2e) | Mar 18, 2020 |
| ASUSTek       | M5A97 R2.0                  | [ce917a03e4](https://linux-hardware.org/?probe=ce917a03e4) | Mar 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [86896f4c65](https://linux-hardware.org/?probe=86896f4c65) | Mar 17, 2020 |
| ASUSTek       | P5GPL-X SE                  | [31e180a996](https://linux-hardware.org/?probe=31e180a996) | Mar 16, 2020 |
| Biostar       | X370GTN                     | [30089deda0](https://linux-hardware.org/?probe=30089deda0) | Mar 16, 2020 |
| HP            | 09F8h                       | [98cd0e0f9f](https://linux-hardware.org/?probe=98cd0e0f9f) | Mar 15, 2020 |
| MSI           | B85M-E45                    | [4d5f4578b5](https://linux-hardware.org/?probe=4d5f4578b5) | Mar 15, 2020 |
| HP            | 83F0                        | [4956b74113](https://linux-hardware.org/?probe=4956b74113) | Mar 15, 2020 |
| MSI           | B150M GAMING PRO            | [20374d8ed1](https://linux-hardware.org/?probe=20374d8ed1) | Mar 15, 2020 |
| ASUSTek       | M4A78-E                     | [91352fe477](https://linux-hardware.org/?probe=91352fe477) | Mar 15, 2020 |
| Lenovo        | Board                       | [91366ff008](https://linux-hardware.org/?probe=91366ff008) | Mar 15, 2020 |
| Lenovo        | Board                       | [5856f51060](https://linux-hardware.org/?probe=5856f51060) | Mar 15, 2020 |
| ASRock        | X99 WS                      | [5a28a3d867](https://linux-hardware.org/?probe=5a28a3d867) | Mar 14, 2020 |
| MSI           | B450-A PRO                  | [d63438d58c](https://linux-hardware.org/?probe=d63438d58c) | Mar 14, 2020 |
| MSI           | B450-A PRO                  | [176d9d4283](https://linux-hardware.org/?probe=176d9d4283) | Mar 14, 2020 |
| MSI           | B450-A PRO                  | [8a500b4715](https://linux-hardware.org/?probe=8a500b4715) | Mar 14, 2020 |
| MSI           | B450-A PRO                  | [6e4d550bd3](https://linux-hardware.org/?probe=6e4d550bd3) | Mar 14, 2020 |
| Gigabyte      | B360M DS3H                  | [4f73435514](https://linux-hardware.org/?probe=4f73435514) | Mar 14, 2020 |
| ASUSTek       | CM6340                      | [15567a680a](https://linux-hardware.org/?probe=15567a680a) | Mar 10, 2020 |
| Intel         | DG31PR AAD97573-204         | [438c0c0e43](https://linux-hardware.org/?probe=438c0c0e43) | Mar 10, 2020 |
| ASRock        | ConRoe1333-D667             | [ea02c8028b](https://linux-hardware.org/?probe=ea02c8028b) | Mar 10, 2020 |
| ABIT          | IL8                         | [957ca551b0](https://linux-hardware.org/?probe=957ca551b0) | Mar 10, 2020 |
| MSI           | B365M PRO-VDH               | [ae7b865014](https://linux-hardware.org/?probe=ae7b865014) | Mar 09, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [44ea344dde](https://linux-hardware.org/?probe=44ea344dde) | Mar 09, 2020 |
| ASRock        | ConRoe1333-D667             | [a86a07dabe](https://linux-hardware.org/?probe=a86a07dabe) | Mar 08, 2020 |
| Acer          | Extensa X2610G              | [cc0dd1d856](https://linux-hardware.org/?probe=cc0dd1d856) | Mar 08, 2020 |
| ABIT          | IL8                         | [fc0deb5d8b](https://linux-hardware.org/?probe=fc0deb5d8b) | Mar 07, 2020 |
| Packard Be... | imedia S3712                | [616cb16b09](https://linux-hardware.org/?probe=616cb16b09) | Mar 07, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [b5e6c4ca51](https://linux-hardware.org/?probe=b5e6c4ca51) | Mar 06, 2020 |
| HP            | 3085B                       | [46e47f957d](https://linux-hardware.org/?probe=46e47f957d) | Mar 06, 2020 |
| ASUSTek       | H170M-PLUS                  | [3e730fa387](https://linux-hardware.org/?probe=3e730fa387) | Mar 06, 2020 |
| ASUSTek       | H170M-PLUS                  | [2cf3457090](https://linux-hardware.org/?probe=2cf3457090) | Mar 06, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [bad44f5189](https://linux-hardware.org/?probe=bad44f5189) | Mar 05, 2020 |
| Dell          | 0F6X5P A00                  | [e95da966ff](https://linux-hardware.org/?probe=e95da966ff) | Mar 05, 2020 |
| Dell          | 0F6X5P A00                  | [ef99636fb4](https://linux-hardware.org/?probe=ef99636fb4) | Mar 05, 2020 |
| ASUSTek       | M2N68-AM Plus               | [b082fbf211](https://linux-hardware.org/?probe=b082fbf211) | Mar 05, 2020 |
| Dell          | 0F6X5P A00                  | [655fd0eb7c](https://linux-hardware.org/?probe=655fd0eb7c) | Mar 05, 2020 |
| Dell          | 0F6X5P A00                  | [67db7a8824](https://linux-hardware.org/?probe=67db7a8824) | Mar 05, 2020 |
| ABIT          | IL8                         | [e8fa6fa32c](https://linux-hardware.org/?probe=e8fa6fa32c) | Mar 05, 2020 |
| ABIT          | IL8                         | [af28510f88](https://linux-hardware.org/?probe=af28510f88) | Mar 05, 2020 |
| Acer          | Aspire XC-230               | [d0f18a2da1](https://linux-hardware.org/?probe=d0f18a2da1) | Mar 05, 2020 |
| Acer          | RS880M05                    | [6a62d0375d](https://linux-hardware.org/?probe=6a62d0375d) | Mar 05, 2020 |
| ABIT          | IL8                         | [00cf41e3de](https://linux-hardware.org/?probe=00cf41e3de) | Mar 04, 2020 |
| MSI           | H81M-P33                    | [b0244c7c4c](https://linux-hardware.org/?probe=b0244c7c4c) | Mar 04, 2020 |
| MSI           | H81M-P33                    | [976ebecca1](https://linux-hardware.org/?probe=976ebecca1) | Mar 04, 2020 |
| MSI           | H81M-P33                    | [a6c9b7dd2b](https://linux-hardware.org/?probe=a6c9b7dd2b) | Mar 04, 2020 |
| MSI           | H81M-P33                    | [d9b698cbed](https://linux-hardware.org/?probe=d9b698cbed) | Mar 04, 2020 |
| MSI           | H81M-P33                    | [ae21843ab4](https://linux-hardware.org/?probe=ae21843ab4) | Mar 04, 2020 |
| ASRock        | H81M-VG4 R2.0               | [3708a45377](https://linux-hardware.org/?probe=3708a45377) | Mar 03, 2020 |
| MSI           | B365M PRO-VDH               | [120662d5e4](https://linux-hardware.org/?probe=120662d5e4) | Mar 03, 2020 |
| ASUSTek       | P5VDC-X                     | [bfa978def2](https://linux-hardware.org/?probe=bfa978def2) | Mar 02, 2020 |
| QDI           | P4I865MA                    | [14dd36d514](https://linux-hardware.org/?probe=14dd36d514) | Mar 02, 2020 |
| MSI           | CX-7528                     | [c86ea2e390](https://linux-hardware.org/?probe=c86ea2e390) | Mar 02, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [36e250f930](https://linux-hardware.org/?probe=36e250f930) | Mar 01, 2020 |
| ASRock        | G31M-S                      | [f8df490a86](https://linux-hardware.org/?probe=f8df490a86) | Feb 29, 2020 |
| QDI           | P4I865MA                    | [abdbf93db4](https://linux-hardware.org/?probe=abdbf93db4) | Feb 29, 2020 |
| ASUSTek       | P5VDC-X                     | [e925327947](https://linux-hardware.org/?probe=e925327947) | Feb 28, 2020 |
| Intel         | DQ67OW AAG28716-306         | [07dc216d1d](https://linux-hardware.org/?probe=07dc216d1d) | Feb 28, 2020 |
| Acer          | WMCP78M                     | [ab041d6368](https://linux-hardware.org/?probe=ab041d6368) | Feb 28, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [5e6d53e2ac](https://linux-hardware.org/?probe=5e6d53e2ac) | Feb 27, 2020 |
| ASUSTek       | H81M-K                      | [6adb3339f8](https://linux-hardware.org/?probe=6adb3339f8) | Feb 26, 2020 |
| ASUSTek       | H81M-K                      | [fd72ac39b0](https://linux-hardware.org/?probe=fd72ac39b0) | Feb 26, 2020 |
| MSI           | B365M PRO-VDH               | [498f1d5cd0](https://linux-hardware.org/?probe=498f1d5cd0) | Feb 26, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [df58761358](https://linux-hardware.org/?probe=df58761358) | Feb 26, 2020 |
| ASUSTek       | AT3N7A-I                    | [c60298bd54](https://linux-hardware.org/?probe=c60298bd54) | Feb 26, 2020 |
| ASUSTek       | PRIME Z390-P                | [1adae8c5e8](https://linux-hardware.org/?probe=1adae8c5e8) | Feb 25, 2020 |
| ASUSTek       | PRIME B360M-A               | [36a9a7e83f](https://linux-hardware.org/?probe=36a9a7e83f) | Feb 24, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [fe11ad505e](https://linux-hardware.org/?probe=fe11ad505e) | Feb 24, 2020 |
| Acer          | EM61SM/EM61PM               | [67cbaff497](https://linux-hardware.org/?probe=67cbaff497) | Feb 23, 2020 |
| Acer          | EM61SM/EM61PM               | [77ae636dab](https://linux-hardware.org/?probe=77ae636dab) | Feb 23, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bca2bf9248](https://linux-hardware.org/?probe=bca2bf9248) | Feb 23, 2020 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [c238ddcb06](https://linux-hardware.org/?probe=c238ddcb06) | Feb 23, 2020 |
| ASUSTek       | P6T DELUXE V2               | [46d0f797cb](https://linux-hardware.org/?probe=46d0f797cb) | Feb 22, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [107b2c10b1](https://linux-hardware.org/?probe=107b2c10b1) | Feb 21, 2020 |
| MSI           | Z97S SLI Krait Edition      | [cf1e9dba3f](https://linux-hardware.org/?probe=cf1e9dba3f) | Feb 20, 2020 |
| ASUSTek       | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Intel         | D34010WYK H14771-303        | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| Gigabyte      | P67A-D3-B3                  | [d6de32a669](https://linux-hardware.org/?probe=d6de32a669) | Feb 18, 2020 |
| Gigabyte      | H270M-DS3H-CF               | [57de48d8e3](https://linux-hardware.org/?probe=57de48d8e3) | Feb 15, 2020 |
| ASUSTek       | P5QL/EPU                    | [0375e592fd](https://linux-hardware.org/?probe=0375e592fd) | Feb 15, 2020 |
| ASUSTek       | P5QL/EPU                    | [7f8cb3318b](https://linux-hardware.org/?probe=7f8cb3318b) | Feb 14, 2020 |
| ASUSTek       | P5QL/EPU                    | [4766801b58](https://linux-hardware.org/?probe=4766801b58) | Feb 14, 2020 |
| Lenovo        | MAHOBAY                     | [f4695737da](https://linux-hardware.org/?probe=f4695737da) | Feb 13, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [975f23e96f](https://linux-hardware.org/?probe=975f23e96f) | Feb 13, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [b0e3f73fd9](https://linux-hardware.org/?probe=b0e3f73fd9) | Feb 13, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [e5dda37f22](https://linux-hardware.org/?probe=e5dda37f22) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| Gigabyte      | P67A-D3-B3                  | [ec9e9cfd84](https://linux-hardware.org/?probe=ec9e9cfd84) | Feb 12, 2020 |
| ASUSTek       | P5VDC-X                     | [1f6194ab88](https://linux-hardware.org/?probe=1f6194ab88) | Feb 12, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [2d0a423903](https://linux-hardware.org/?probe=2d0a423903) | Feb 11, 2020 |
| ASUSTek       | P5VDC-X                     | [c287fb697e](https://linux-hardware.org/?probe=c287fb697e) | Feb 11, 2020 |
| ASUSTek       | P5VDC-X                     | [0156213909](https://linux-hardware.org/?probe=0156213909) | Feb 11, 2020 |
| Gigabyte      | P67A-D3-B3                  | [1b5dbc8cb2](https://linux-hardware.org/?probe=1b5dbc8cb2) | Feb 10, 2020 |
| ASRock        | 4CoreDual-SATA2             | [28f308a559](https://linux-hardware.org/?probe=28f308a559) | Feb 10, 2020 |
| ASUSTek       | P5K-E                       | [c755d3536a](https://linux-hardware.org/?probe=c755d3536a) | Feb 09, 2020 |
| Gigabyte      | B360M DS3H                  | [06592d7ffb](https://linux-hardware.org/?probe=06592d7ffb) | Feb 08, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [b7799e0013](https://linux-hardware.org/?probe=b7799e0013) | Feb 07, 2020 |
| Gigabyte      | P67A-D3-B3                  | [e35e89c3d0](https://linux-hardware.org/?probe=e35e89c3d0) | Feb 07, 2020 |
| Acer          | H57M01                      | [98807b6a80](https://linux-hardware.org/?probe=98807b6a80) | Feb 07, 2020 |
| Acer          | H57M01                      | [341bbfe493](https://linux-hardware.org/?probe=341bbfe493) | Feb 07, 2020 |
| ASUSTek       | P5S533-TVM SE               | [199135df50](https://linux-hardware.org/?probe=199135df50) | Feb 06, 2020 |
| MSI           | Z87-G45 GAMING              | [7bcfe49dba](https://linux-hardware.org/?probe=7bcfe49dba) | Feb 06, 2020 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [0c7a430645](https://linux-hardware.org/?probe=0c7a430645) | Feb 06, 2020 |
| ASUSTek       | H97M-E                      | [11ee892c2f](https://linux-hardware.org/?probe=11ee892c2f) | Feb 05, 2020 |
| ASUSTek       | H97M-E                      | [23805fb325](https://linux-hardware.org/?probe=23805fb325) | Feb 05, 2020 |
| Dell          | 0KRC95 A02                  | [2b786edb48](https://linux-hardware.org/?probe=2b786edb48) | Feb 04, 2020 |
| Acer          | Veriton M680G               | [0786938f58](https://linux-hardware.org/?probe=0786938f58) | Feb 04, 2020 |
| Acer          | Veriton M680G               | [dd2d69e81f](https://linux-hardware.org/?probe=dd2d69e81f) | Feb 03, 2020 |
| ASUSTek       | P5VDC-MX/2.x                | [1a3f6db756](https://linux-hardware.org/?probe=1a3f6db756) | Feb 02, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [16f6ff52f4](https://linux-hardware.org/?probe=16f6ff52f4) | Feb 02, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [0b6823359e](https://linux-hardware.org/?probe=0b6823359e) | Jan 31, 2020 |
| ASUSTek       | ET2012E                     | [32c68521c8](https://linux-hardware.org/?probe=32c68521c8) | Jan 30, 2020 |
| ASUSTek       | ET2012E                     | [ee24204ba8](https://linux-hardware.org/?probe=ee24204ba8) | Jan 30, 2020 |
| Gigabyte      | B85M-D3V                    | [cf2612f344](https://linux-hardware.org/?probe=cf2612f344) | Jan 29, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [4d1bedd519](https://linux-hardware.org/?probe=4d1bedd519) | Jan 29, 2020 |
| ASUSTek       | H97-PLUS                    | [d0b92b9616](https://linux-hardware.org/?probe=d0b92b9616) | Jan 28, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9d52ffbd7d](https://linux-hardware.org/?probe=9d52ffbd7d) | Jan 28, 2020 |
| Dell          | 0KRC95 A02                  | [66dba88242](https://linux-hardware.org/?probe=66dba88242) | Jan 27, 2020 |
| Unknown       | SKYBAY                      | [15bbbdb9c3](https://linux-hardware.org/?probe=15bbbdb9c3) | Jan 27, 2020 |
| Dell          | 0KRC95 A02                  | [eb960b0e23](https://linux-hardware.org/?probe=eb960b0e23) | Jan 27, 2020 |
| Dell          | 0KRC95 A02                  | [12b1661220](https://linux-hardware.org/?probe=12b1661220) | Jan 27, 2020 |
| ASUSTek       | P5G41T-M LE                 | [571220fc69](https://linux-hardware.org/?probe=571220fc69) | Jan 27, 2020 |
| ASRock        | FM2A75M-DGS                 | [d684793272](https://linux-hardware.org/?probe=d684793272) | Jan 27, 2020 |
| ASRock        | N68-VS3 FX                  | [a62c59e33f](https://linux-hardware.org/?probe=a62c59e33f) | Jan 25, 2020 |
| ASRock        | H110M-HDV                   | [71b475448a](https://linux-hardware.org/?probe=71b475448a) | Jan 24, 2020 |
| Gigabyte      | P67A-D3-B3                  | [3b7ed5f2a2](https://linux-hardware.org/?probe=3b7ed5f2a2) | Jan 24, 2020 |
| ASRock        | J3455M                      | [5ee905d8b9](https://linux-hardware.org/?probe=5ee905d8b9) | Jan 24, 2020 |
| ASUSTek       | P5S533-TVM SE               | [321b162f85](https://linux-hardware.org/?probe=321b162f85) | Jan 23, 2020 |
| ASUSTek       | Maximus IX FORMULA          | [b67bbc7e71](https://linux-hardware.org/?probe=b67bbc7e71) | Jan 22, 2020 |
| ASRock        | G31M-GS                     | [170174b905](https://linux-hardware.org/?probe=170174b905) | Jan 20, 2020 |
| Intel         | DH55HC AAE70933-505         | [a8bd4f87a5](https://linux-hardware.org/?probe=a8bd4f87a5) | Jan 18, 2020 |
| MSI           | IONA                        | [ab9095f444](https://linux-hardware.org/?probe=ab9095f444) | Jan 18, 2020 |
| HP            | 1998                        | [70156b9878](https://linux-hardware.org/?probe=70156b9878) | Jan 18, 2020 |
| Gigabyte      | H81M-DS2V                   | [15455c7443](https://linux-hardware.org/?probe=15455c7443) | Jan 17, 2020 |
| Gigabyte      | P67A-D3-B3                  | [aeb326bb34](https://linux-hardware.org/?probe=aeb326bb34) | Jan 17, 2020 |
| Dell          | 0GU083 A00                  | [d7341fdb94](https://linux-hardware.org/?probe=d7341fdb94) | Jan 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [04a55575ed](https://linux-hardware.org/?probe=04a55575ed) | Jan 14, 2020 |
| ASUSTek       | Z97-P                       | [0152e847db](https://linux-hardware.org/?probe=0152e847db) | Jan 13, 2020 |
| ASUSTek       | Z97-P                       | [0589d3b163](https://linux-hardware.org/?probe=0589d3b163) | Jan 13, 2020 |
| ASUSTek       | Z97-P                       | [72807aca5b](https://linux-hardware.org/?probe=72807aca5b) | Jan 13, 2020 |
| ASUSTek       | P5QD TURBO                  | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| ASRock        | N3700-ITX                   | [f4d6b574a1](https://linux-hardware.org/?probe=f4d6b574a1) | Jan 12, 2020 |
| ASRock        | N3700-ITX                   | [6c5b698db6](https://linux-hardware.org/?probe=6c5b698db6) | Jan 12, 2020 |
| ASUSTek       | A88XM-PLUS                  | [2017281aa7](https://linux-hardware.org/?probe=2017281aa7) | Jan 12, 2020 |
| HP            | 3397                        | [9602ebe2d2](https://linux-hardware.org/?probe=9602ebe2d2) | Jan 11, 2020 |
| ASUSTek       | P7H55-M PRO                 | [8f6541c269](https://linux-hardware.org/?probe=8f6541c269) | Jan 10, 2020 |
| Sapphire      | PI-AM3RS760G                | [c3b3676a40](https://linux-hardware.org/?probe=c3b3676a40) | Jan 08, 2020 |
| Sapphire      | PI-AM3RS760G                | [c6b68917b2](https://linux-hardware.org/?probe=c6b68917b2) | Jan 08, 2020 |
| ASUSTek       | P7H55-M PRO                 | [025a73d4e0](https://linux-hardware.org/?probe=025a73d4e0) | Jan 07, 2020 |
| ASUSTek       | P7P55D                      | [03dd49405e](https://linux-hardware.org/?probe=03dd49405e) | Jan 07, 2020 |
| Acer          | Predator G3600              | [88b192dfa2](https://linux-hardware.org/?probe=88b192dfa2) | Jan 07, 2020 |
| Gigabyte      | Z97P-D3                     | [957b6521ad](https://linux-hardware.org/?probe=957b6521ad) | Jan 07, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| MSI           | B450M GAMING PLUS           | [c1f215d1ee](https://linux-hardware.org/?probe=c1f215d1ee) | Jan 05, 2020 |
| HP            | 0A64h                       | [98c423be6f](https://linux-hardware.org/?probe=98c423be6f) | Jan 04, 2020 |
| HP            | 0A64h                       | [4ab1ade3e0](https://linux-hardware.org/?probe=4ab1ade3e0) | Jan 03, 2020 |
| ASUSTek       | P7H55                       | [30852471e5](https://linux-hardware.org/?probe=30852471e5) | Jan 03, 2020 |
| ASRock        | B450M-HDV                   | [fb4890a4dd](https://linux-hardware.org/?probe=fb4890a4dd) | Jan 01, 2020 |
| HP            | 0968h                       | [66884f83c7](https://linux-hardware.org/?probe=66884f83c7) | Dec 31, 2019 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2bef5f71a2](https://linux-hardware.org/?probe=2bef5f71a2) | Dec 31, 2019 |
| ASRock        | H110M-HDV                   | [a7ffab572c](https://linux-hardware.org/?probe=a7ffab572c) | Dec 31, 2019 |
| ASRock        | H110M-HDV                   | [af950ec3c0](https://linux-hardware.org/?probe=af950ec3c0) | Dec 30, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | [59ea5d950b](https://linux-hardware.org/?probe=59ea5d950b) | Dec 30, 2019 |
| ASRock        | H110M-HDV                   | [1811d1ee7a](https://linux-hardware.org/?probe=1811d1ee7a) | Dec 29, 2019 |
| ASRock        | H110M-HDV                   | [8b2f6ded4b](https://linux-hardware.org/?probe=8b2f6ded4b) | Dec 28, 2019 |
| Dell          | 0G919G A00                  | [91fd789e18](https://linux-hardware.org/?probe=91fd789e18) | Dec 27, 2019 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [2f126b4841](https://linux-hardware.org/?probe=2f126b4841) | Dec 27, 2019 |
| Intel         | DH61BE AAG14062-206         | [d399f689f0](https://linux-hardware.org/?probe=d399f689f0) | Dec 25, 2019 |
| ASUSTek       | P7H55                       | [522ae798b9](https://linux-hardware.org/?probe=522ae798b9) | Dec 25, 2019 |
| ASUSTek       | P7H55                       | [a8a928ed59](https://linux-hardware.org/?probe=a8a928ed59) | Dec 25, 2019 |
| ASUSTek       | P6T                         | [ddf9d08a22](https://linux-hardware.org/?probe=ddf9d08a22) | Dec 24, 2019 |
| ASRock        | A75M-HVS                    | [0abb4f0e21](https://linux-hardware.org/?probe=0abb4f0e21) | Dec 24, 2019 |
| ASUSTek       | P6T                         | [eba82f7c39](https://linux-hardware.org/?probe=eba82f7c39) | Dec 24, 2019 |
| ASUSTek       | P6T                         | [6c870ef211](https://linux-hardware.org/?probe=6c870ef211) | Dec 23, 2019 |
| Dell          | 0F896N A03                  | [113ed4d732](https://linux-hardware.org/?probe=113ed4d732) | Dec 20, 2019 |
| ASUSTek       | P6T                         | [f7f43b688e](https://linux-hardware.org/?probe=f7f43b688e) | Dec 20, 2019 |
| ASUSTek       | P6T                         | [b2536c0fde](https://linux-hardware.org/?probe=b2536c0fde) | Dec 20, 2019 |
| Acer          | Veriton EX2620G             | [897135872a](https://linux-hardware.org/?probe=897135872a) | Dec 18, 2019 |
| Acer          | Veriton EX2620G             | [fcae0a2802](https://linux-hardware.org/?probe=fcae0a2802) | Dec 18, 2019 |
| MSI           | 0A48                        | [696b638b80](https://linux-hardware.org/?probe=696b638b80) | Dec 18, 2019 |
| ASRock        | ConRoe1333-D667             | [62de4da398](https://linux-hardware.org/?probe=62de4da398) | Dec 17, 2019 |
| HP            | 339A                        | [2962b36d7e](https://linux-hardware.org/?probe=2962b36d7e) | Dec 17, 2019 |
| MSI           | H110M PRO-VD                | [ff12d313a1](https://linux-hardware.org/?probe=ff12d313a1) | Dec 17, 2019 |
| Gigabyte      | H81M-DS2V                   | [410eb6b767](https://linux-hardware.org/?probe=410eb6b767) | Dec 16, 2019 |
| ASUSTek       | K31CD-K                     | [cc599b8a3a](https://linux-hardware.org/?probe=cc599b8a3a) | Dec 16, 2019 |
| Gigabyte      | H81M-DS2V                   | [de56ff74c4](https://linux-hardware.org/?probe=de56ff74c4) | Dec 15, 2019 |
| ASRock        | H81M-HDS                    | [754ce872b9](https://linux-hardware.org/?probe=754ce872b9) | Dec 15, 2019 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [f66245aea5](https://linux-hardware.org/?probe=f66245aea5) | Dec 12, 2019 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [8c1a290948](https://linux-hardware.org/?probe=8c1a290948) | Dec 12, 2019 |
| Gigabyte      | GA-73PVM-S2H                | [8996cebf5b](https://linux-hardware.org/?probe=8996cebf5b) | Dec 10, 2019 |
| Pegatron      | 2ACF                        | [74374104d4](https://linux-hardware.org/?probe=74374104d4) | Dec 08, 2019 |
| Gigabyte      | P67A-D3-B3                  | [2327d3ddb8](https://linux-hardware.org/?probe=2327d3ddb8) | Dec 08, 2019 |
| Pegatron      | 2ACF                        | [773e16c768](https://linux-hardware.org/?probe=773e16c768) | Dec 07, 2019 |
| MSI           | H110M PRO-VH                | [1e55d134a9](https://linux-hardware.org/?probe=1e55d134a9) | Dec 06, 2019 |
| Gigabyte      | GA-73PVM-S2H                | [9f1614f7fa](https://linux-hardware.org/?probe=9f1614f7fa) | Dec 05, 2019 |
| Gigabyte      | GA-73PVM-S2H                | [1785d7e5d2](https://linux-hardware.org/?probe=1785d7e5d2) | Dec 05, 2019 |
| HP            | 0A54h                       | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| HP            | 843C                        | [7773dc895e](https://linux-hardware.org/?probe=7773dc895e) | Dec 05, 2019 |
| Gigabyte      | P67A-D3-B3                  | [39ba700154](https://linux-hardware.org/?probe=39ba700154) | Dec 04, 2019 |
| Dell          | 040DDP A00                  | [2e66049230](https://linux-hardware.org/?probe=2e66049230) | Dec 04, 2019 |
| Lenovo        | MAHOBAY NO DPK              | [a08028c506](https://linux-hardware.org/?probe=a08028c506) | Dec 04, 2019 |
| HP            | 81B3                        | [2f0c4abc2e](https://linux-hardware.org/?probe=2f0c4abc2e) | Dec 04, 2019 |
| Gigabyte      | P67A-D3-B3                  | [91e4f52056](https://linux-hardware.org/?probe=91e4f52056) | Dec 01, 2019 |
| HP            | 18E7                        | [e985589c0c](https://linux-hardware.org/?probe=e985589c0c) | Dec 01, 2019 |
| Gigabyte      | P67A-D3-B3                  | [ede9852067](https://linux-hardware.org/?probe=ede9852067) | Nov 30, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [01eb44dd37](https://linux-hardware.org/?probe=01eb44dd37) | Nov 30, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [f1a7bbb174](https://linux-hardware.org/?probe=f1a7bbb174) | Nov 30, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [00931dd0b2](https://linux-hardware.org/?probe=00931dd0b2) | Nov 29, 2019 |
| HP            | 82B4                        | [0773ba459e](https://linux-hardware.org/?probe=0773ba459e) | Nov 29, 2019 |
| Gigabyte      | X58A-UD3R                   | [13728b17ae](https://linux-hardware.org/?probe=13728b17ae) | Nov 28, 2019 |
| HP            | 843C                        | [924bd2b91c](https://linux-hardware.org/?probe=924bd2b91c) | Nov 26, 2019 |
| ECS           | P4VMM2                      | [f7f643e659](https://linux-hardware.org/?probe=f7f643e659) | Nov 26, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [a4a6c357ee](https://linux-hardware.org/?probe=a4a6c357ee) | Nov 26, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | [0217f128ca](https://linux-hardware.org/?probe=0217f128ca) | Nov 25, 2019 |
| Gigabyte      | P67A-D3-B3                  | [485b557d7d](https://linux-hardware.org/?probe=485b557d7d) | Nov 24, 2019 |
| IBM           | Board                       | [4ebf1fea5a](https://linux-hardware.org/?probe=4ebf1fea5a) | Nov 24, 2019 |
| ASRock        | ConRoe1333-D667             | [ce7f8a5da5](https://linux-hardware.org/?probe=ce7f8a5da5) | Nov 22, 2019 |
| HP            | 843C                        | [a8be575f0e](https://linux-hardware.org/?probe=a8be575f0e) | Nov 22, 2019 |
| ASUSTek       | H97-PLUS                    | [96007b1835](https://linux-hardware.org/?probe=96007b1835) | Nov 22, 2019 |
| ASUSTek       | H97-PLUS                    | [a9c62e74c0](https://linux-hardware.org/?probe=a9c62e74c0) | Nov 22, 2019 |
| Gigabyte      | EP35-DS3L                   | [8c45d223f8](https://linux-hardware.org/?probe=8c45d223f8) | Nov 21, 2019 |
| MSI           | MPG Z390 GAMING PLUS        | [b903ad14bd](https://linux-hardware.org/?probe=b903ad14bd) | Nov 21, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [4060eb4962](https://linux-hardware.org/?probe=4060eb4962) | Nov 20, 2019 |
| Gigabyte      | M68M-S2P                    | [d3d67a469b](https://linux-hardware.org/?probe=d3d67a469b) | Nov 20, 2019 |
| Gigabyte      | M68M-S2P                    | [f01fe72735](https://linux-hardware.org/?probe=f01fe72735) | Nov 20, 2019 |
| ASUSTek       | H61M-K                      | [8f3427e15f](https://linux-hardware.org/?probe=8f3427e15f) | Nov 19, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [56f0a1e0f6](https://linux-hardware.org/?probe=56f0a1e0f6) | Nov 19, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [621e3424c9](https://linux-hardware.org/?probe=621e3424c9) | Nov 19, 2019 |
| MSI           | MS-7528                     | [ce46bf7581](https://linux-hardware.org/?probe=ce46bf7581) | Nov 18, 2019 |
| Gigabyte      | P67A-D3-B3                  | [152172a4eb](https://linux-hardware.org/?probe=152172a4eb) | Nov 17, 2019 |
| HP            | 1589                        | [9d85c4ca60](https://linux-hardware.org/?probe=9d85c4ca60) | Nov 17, 2019 |
| HP            | 1998                        | [9e58678ae8](https://linux-hardware.org/?probe=9e58678ae8) | Nov 17, 2019 |
| HP            | 2820h                       | [22d8188fd8](https://linux-hardware.org/?probe=22d8188fd8) | Nov 16, 2019 |
| HP            | 2820h                       | [11fce44b86](https://linux-hardware.org/?probe=11fce44b86) | Nov 16, 2019 |
| ASRock        | P67 Pro3 SE                 | [8c62d74dd3](https://linux-hardware.org/?probe=8c62d74dd3) | Nov 16, 2019 |
| MSI           | Z77A-GD55                   | [32dd5baeec](https://linux-hardware.org/?probe=32dd5baeec) | Nov 15, 2019 |
| Gigabyte      | GA-73PVM-S2H                | [6b8473d21f](https://linux-hardware.org/?probe=6b8473d21f) | Nov 15, 2019 |
| Gigabyte      | F2A88XM-HD3                 | [22a571b2e7](https://linux-hardware.org/?probe=22a571b2e7) | Nov 13, 2019 |
| ASUSTek       | P5Q SE PLUS                 | [4edf9cc762](https://linux-hardware.org/?probe=4edf9cc762) | Nov 13, 2019 |
| Dell          | 0HP962                      | [9b674786d6](https://linux-hardware.org/?probe=9b674786d6) | Nov 13, 2019 |
| ASUSTek       | M51AC                       | [3329113338](https://linux-hardware.org/?probe=3329113338) | Nov 13, 2019 |
| ASUSTek       | M51AC                       | [ccd2fb274a](https://linux-hardware.org/?probe=ccd2fb274a) | Nov 13, 2019 |
| ASUSTek       | P5Q SE PLUS                 | [e5cb6d564f](https://linux-hardware.org/?probe=e5cb6d564f) | Nov 12, 2019 |
| ASUSTek       | P5Q SE PLUS                 | [ac67d516f9](https://linux-hardware.org/?probe=ac67d516f9) | Nov 12, 2019 |
| ASUSTek       | P5Q SE PLUS                 | [304cf052bc](https://linux-hardware.org/?probe=304cf052bc) | Nov 12, 2019 |
| ASRock        | 870 Extreme3                | [57024648c9](https://linux-hardware.org/?probe=57024648c9) | Nov 12, 2019 |
| ASUSTek       | P5Q SE PLUS                 | [c6f604105f](https://linux-hardware.org/?probe=c6f604105f) | Nov 11, 2019 |
| WINCOR NIX... | G1-CPU-IMP Motherboard_G... | [a6f4bd8866](https://linux-hardware.org/?probe=a6f4bd8866) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [e4ae098bfc](https://linux-hardware.org/?probe=e4ae098bfc) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| ASUSTek       | M5A97 R2.0                  | [e4e6ac6035](https://linux-hardware.org/?probe=e4e6ac6035) | Nov 10, 2019 |
| ASUSTek       | M5A97 R2.0                  | [14b215a494](https://linux-hardware.org/?probe=14b215a494) | Nov 10, 2019 |
| NEC Comput... | ECS-945G                    | [3494d9ef49](https://linux-hardware.org/?probe=3494d9ef49) | Nov 10, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [4e1905a9e4](https://linux-hardware.org/?probe=4e1905a9e4) | Nov 10, 2019 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [071e4e8502](https://linux-hardware.org/?probe=071e4e8502) | Nov 10, 2019 |
| HP            | 843C                        | [2447ef07c5](https://linux-hardware.org/?probe=2447ef07c5) | Nov 09, 2019 |
| ASUSTek       | Z87-C                       | [58a50ce298](https://linux-hardware.org/?probe=58a50ce298) | Nov 08, 2019 |
| ASUSTek       | H97-PLUS                    | [114df4b3c4](https://linux-hardware.org/?probe=114df4b3c4) | Nov 08, 2019 |
| HP            | 843C                        | [f3766b7759](https://linux-hardware.org/?probe=f3766b7759) | Nov 08, 2019 |
| ASUSTek       | P7H55-M                     | [df4ba14e49](https://linux-hardware.org/?probe=df4ba14e49) | Nov 08, 2019 |
| ASUSTek       | P5KPL-SE                    | [52f046e511](https://linux-hardware.org/?probe=52f046e511) | Nov 08, 2019 |
| ASRock        | N68-GS4/USB3 FX             | [fdf42f20bb](https://linux-hardware.org/?probe=fdf42f20bb) | Nov 05, 2019 |
| HP            | 18E5                        | [8753639d1c](https://linux-hardware.org/?probe=8753639d1c) | Nov 04, 2019 |
| HP            | 0AA8h                       | [bd84f3feeb](https://linux-hardware.org/?probe=bd84f3feeb) | Nov 02, 2019 |
| HP            | 3048h                       | [aa87243773](https://linux-hardware.org/?probe=aa87243773) | Nov 02, 2019 |
| MSI           | Boston                      | [898b642950](https://linux-hardware.org/?probe=898b642950) | Nov 02, 2019 |
| Gigabyte      | P67A-D3-B3                  | [f6a063be97](https://linux-hardware.org/?probe=f6a063be97) | Nov 02, 2019 |
| HP            | 843B                        | [913eb3adcc](https://linux-hardware.org/?probe=913eb3adcc) | Nov 01, 2019 |
| ASRock        | H55M Pro                    | [1d9934126c](https://linux-hardware.org/?probe=1d9934126c) | Oct 30, 2019 |
| ASUSTek       | M4A78L-M                    | [96360ebd03](https://linux-hardware.org/?probe=96360ebd03) | Oct 28, 2019 |
| ASRock        | J3455B-ITX                  | [8a9b3e5533](https://linux-hardware.org/?probe=8a9b3e5533) | Oct 27, 2019 |
| ASUSTek       | M4A79T Deluxe               | [5d250ed2a6](https://linux-hardware.org/?probe=5d250ed2a6) | Oct 26, 2019 |
| ASUSTek       | K8V-MX                      | [78e1bdc29b](https://linux-hardware.org/?probe=78e1bdc29b) | Oct 25, 2019 |
| ASRock        | FM2A75M-DGS                 | [fb8d17d634](https://linux-hardware.org/?probe=fb8d17d634) | Oct 25, 2019 |
| Acer          | EG31M P01-A0L               | [d4716810fc](https://linux-hardware.org/?probe=d4716810fc) | Oct 25, 2019 |
| Intel         | DB75EN AAG39650-303         | [a306fadc3b](https://linux-hardware.org/?probe=a306fadc3b) | Oct 25, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | [acdd9e30c7](https://linux-hardware.org/?probe=acdd9e30c7) | Oct 24, 2019 |
| MSI           | X370 GAMING PRO CARBON      | [4e83715b2b](https://linux-hardware.org/?probe=4e83715b2b) | Oct 20, 2019 |
| MSI           | X370 GAMING PRO CARBON      | [9437f9c02b](https://linux-hardware.org/?probe=9437f9c02b) | Oct 20, 2019 |
| ASUSTek       | H97-PLUS                    | [76f4ce91dc](https://linux-hardware.org/?probe=76f4ce91dc) | Oct 20, 2019 |
| Gigabyte      | F2A75M-D3H                  | [5101bf81d3](https://linux-hardware.org/?probe=5101bf81d3) | Oct 19, 2019 |
| ASUSTek       | H97-PLUS                    | [28b7567c65](https://linux-hardware.org/?probe=28b7567c65) | Oct 19, 2019 |
| ASUSTek       | P5G41T-M LX                 | [f54cb2be14](https://linux-hardware.org/?probe=f54cb2be14) | Oct 16, 2019 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [3ace0e7247](https://linux-hardware.org/?probe=3ace0e7247) | Oct 15, 2019 |
| ASUSTek       | PRIME A320M-K               | [e19045809a](https://linux-hardware.org/?probe=e19045809a) | Oct 13, 2019 |
| ASUSTek       | H87M-PRO                    | [7f5844dacd](https://linux-hardware.org/?probe=7f5844dacd) | Oct 13, 2019 |
| ASRock        | H110M-ITX/ac                | [005d67d00b](https://linux-hardware.org/?probe=005d67d00b) | Oct 11, 2019 |
| Acer          | G31                         | [a0bd82d6b8](https://linux-hardware.org/?probe=a0bd82d6b8) | Oct 11, 2019 |
| ASUSTek       | PRIME A320M-K               | [fe5048f982](https://linux-hardware.org/?probe=fe5048f982) | Oct 10, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | [942d009565](https://linux-hardware.org/?probe=942d009565) | Oct 09, 2019 |
| Pegatron      | NARRA5                      | [1ff2518d54](https://linux-hardware.org/?probe=1ff2518d54) | Oct 08, 2019 |
| Pegatron      | NARRA5                      | [63fc8bdbe2](https://linux-hardware.org/?probe=63fc8bdbe2) | Oct 08, 2019 |
| HP            | 1998                        | [8d826a36d2](https://linux-hardware.org/?probe=8d826a36d2) | Oct 07, 2019 |
| HP            | 1998                        | [2b762dba06](https://linux-hardware.org/?probe=2b762dba06) | Oct 07, 2019 |
| MSI           | X99A RAIDER                 | [fde33600e4](https://linux-hardware.org/?probe=fde33600e4) | Oct 05, 2019 |
| MSI           | X99A RAIDER                 | [2a8b9bf1a8](https://linux-hardware.org/?probe=2a8b9bf1a8) | Oct 05, 2019 |
| ASRock        | 870 Extreme3                | [4afd0f77ed](https://linux-hardware.org/?probe=4afd0f77ed) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [d65cf164cf](https://linux-hardware.org/?probe=d65cf164cf) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [c7840d0aee](https://linux-hardware.org/?probe=c7840d0aee) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [0eb6da3548](https://linux-hardware.org/?probe=0eb6da3548) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [75278c5e8d](https://linux-hardware.org/?probe=75278c5e8d) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [b54e1574a4](https://linux-hardware.org/?probe=b54e1574a4) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [f09805b8fb](https://linux-hardware.org/?probe=f09805b8fb) | Oct 02, 2019 |
| ASRock        | 870 Extreme3                | [15ff0c25e2](https://linux-hardware.org/?probe=15ff0c25e2) | Oct 02, 2019 |
| ASRock        | Z77 Pro4-M                  | [7291533e89](https://linux-hardware.org/?probe=7291533e89) | Oct 01, 2019 |
| ASRock        | H97 Anniversary             | [3a60d4e5ce](https://linux-hardware.org/?probe=3a60d4e5ce) | Oct 01, 2019 |
| ASUSTek       | E35M1-M                     | [86d0caf97c](https://linux-hardware.org/?probe=86d0caf97c) | Sep 29, 2019 |
| HP            | 3397                        | [ec39b3f48a](https://linux-hardware.org/?probe=ec39b3f48a) | Sep 27, 2019 |
| Dell          | 0HJ054                      | [4e41dee061](https://linux-hardware.org/?probe=4e41dee061) | Sep 26, 2019 |
| ASUSTek       | Z170-A                      | [b5c466bde4](https://linux-hardware.org/?probe=b5c466bde4) | Sep 25, 2019 |
| ASRock        | Q1900M                      | [f8ca2fbb82](https://linux-hardware.org/?probe=f8ca2fbb82) | Sep 24, 2019 |
| Intel         | DG41TY AAE47335-302         | [6c85e652d6](https://linux-hardware.org/?probe=6c85e652d6) | Sep 24, 2019 |
| Dell          | 0H1290                      | [580679094a](https://linux-hardware.org/?probe=580679094a) | Sep 24, 2019 |
| Dell          | 0H1290                      | [18cf7c0503](https://linux-hardware.org/?probe=18cf7c0503) | Sep 24, 2019 |
| ECS           | P4VMM2                      | [1d92b8ade6](https://linux-hardware.org/?probe=1d92b8ade6) | Sep 24, 2019 |
| Unknown       | Unknown                     | [a6659ee127](https://linux-hardware.org/?probe=a6659ee127) | Sep 20, 2019 |
| Unknown       | Unknown                     | [873928e925](https://linux-hardware.org/?probe=873928e925) | Sep 20, 2019 |
| Unknown       | Unknown                     | [e92b43cca6](https://linux-hardware.org/?probe=e92b43cca6) | Sep 20, 2019 |
| ASRock        | Q1900M                      | [685005e7e9](https://linux-hardware.org/?probe=685005e7e9) | Sep 20, 2019 |
| Gigabyte      | Z170X-Gaming 7              | [112140b1a6](https://linux-hardware.org/?probe=112140b1a6) | Sep 19, 2019 |
| ASRock        | Q1900M                      | [f1461986cf](https://linux-hardware.org/?probe=f1461986cf) | Sep 19, 2019 |
| Acer          | Aspire TC-280               | [86472bf81e](https://linux-hardware.org/?probe=86472bf81e) | Sep 18, 2019 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [dfd254c12b](https://linux-hardware.org/?probe=dfd254c12b) | Sep 18, 2019 |
| Gigabyte      | Z87X-OC Force-CF            | [e8870caa15](https://linux-hardware.org/?probe=e8870caa15) | Sep 17, 2019 |
| MSI           | X99A RAIDER                 | [6642f9e5eb](https://linux-hardware.org/?probe=6642f9e5eb) | Sep 16, 2019 |
| Gigabyte      | J4005ND2P-CF                | [f325c7da06](https://linux-hardware.org/?probe=f325c7da06) | Sep 15, 2019 |
| ASRock        | G41M-LE                     | [24879f27ef](https://linux-hardware.org/?probe=24879f27ef) | Sep 15, 2019 |
| ASUSTek       | P5B SE                      | [196bdf7448](https://linux-hardware.org/?probe=196bdf7448) | Sep 14, 2019 |
| Dell          | 0WMJ54 A01                  | [7c9c7ac9a1](https://linux-hardware.org/?probe=7c9c7ac9a1) | Sep 14, 2019 |
| ASRock        | 960GM-GS3 FX                | [b0d3c36cba](https://linux-hardware.org/?probe=b0d3c36cba) | Sep 13, 2019 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [b39cf7d47c](https://linux-hardware.org/?probe=b39cf7d47c) | Sep 13, 2019 |
| ASRock        | 960GM-GS3 FX                | [53e418b0f6](https://linux-hardware.org/?probe=53e418b0f6) | Sep 11, 2019 |
| ASRock        | 960GM-GS3 FX                | [58194091d1](https://linux-hardware.org/?probe=58194091d1) | Sep 11, 2019 |
| MSI           | 0A90                        | [8b0e25bd50](https://linux-hardware.org/?probe=8b0e25bd50) | Sep 08, 2019 |
| MSI           | 0A90                        | [acde29aba2](https://linux-hardware.org/?probe=acde29aba2) | Sep 06, 2019 |
| MSI           | 0A90                        | [54cfa6c69e](https://linux-hardware.org/?probe=54cfa6c69e) | Sep 06, 2019 |
| HP            | 2B35                        | [cc65af2a5b](https://linux-hardware.org/?probe=cc65af2a5b) | Sep 06, 2019 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [4cdb503b48](https://linux-hardware.org/?probe=4cdb503b48) | Sep 05, 2019 |
| Intel         | DG41TY AAE47335-302         | [cf48865878](https://linux-hardware.org/?probe=cf48865878) | Sep 05, 2019 |
| ASRock        | J3455M                      | [b4c9d2d073](https://linux-hardware.org/?probe=b4c9d2d073) | Sep 04, 2019 |
| ASRock        | J3455M                      | [985e1d0532](https://linux-hardware.org/?probe=985e1d0532) | Sep 04, 2019 |
| ASRock        | J3455M                      | [9312d422c1](https://linux-hardware.org/?probe=9312d422c1) | Sep 04, 2019 |
| HP            | 82B4                        | [cddec07481](https://linux-hardware.org/?probe=cddec07481) | Sep 04, 2019 |
| ASUSTek       | M4A78LT-M                   | [46bb5efd11](https://linux-hardware.org/?probe=46bb5efd11) | Sep 04, 2019 |
| Packard Be... | FMP55                       | [c388ccfbbb](https://linux-hardware.org/?probe=c388ccfbbb) | Sep 03, 2019 |
| Packard Be... | FMP55                       | [301af29234](https://linux-hardware.org/?probe=301af29234) | Sep 02, 2019 |
| ASUSTek       | H87M-PRO                    | [a277faecf4](https://linux-hardware.org/?probe=a277faecf4) | Sep 02, 2019 |
| ECS           | P4VMM2                      | [20e434665a](https://linux-hardware.org/?probe=20e434665a) | Sep 02, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [4d977809c7](https://linux-hardware.org/?probe=4d977809c7) | Aug 31, 2019 |
| Unknown       | Unknown                     | [6788990f5b](https://linux-hardware.org/?probe=6788990f5b) | Aug 29, 2019 |
| Unknown       | Unknown                     | [8432401c21](https://linux-hardware.org/?probe=8432401c21) | Aug 29, 2019 |
| Unknown       | Unknown                     | [a079d5ea0a](https://linux-hardware.org/?probe=a079d5ea0a) | Aug 29, 2019 |
| Unknown       | K10N78hSLI-WiFi             | [411ae44fde](https://linux-hardware.org/?probe=411ae44fde) | Aug 29, 2019 |
| AMI           | Cherry Trail CR             | [8050dc14fc](https://linux-hardware.org/?probe=8050dc14fc) | Aug 28, 2019 |
| ECS           | P4VMM2                      | [3999ffd185](https://linux-hardware.org/?probe=3999ffd185) | Aug 26, 2019 |
| Gigabyte      | Z170X-Gaming 7              | [3e2c758994](https://linux-hardware.org/?probe=3e2c758994) | Aug 24, 2019 |
| ASUSTek       | H87M-E                      | [20eb7128f0](https://linux-hardware.org/?probe=20eb7128f0) | Aug 24, 2019 |
| ASUSTek       | P5K SE/EPU                  | [c9449f1c4a](https://linux-hardware.org/?probe=c9449f1c4a) | Aug 24, 2019 |
| ASUSTek       | H110M-A/M.2                 | [596d2f7a72](https://linux-hardware.org/?probe=596d2f7a72) | Aug 23, 2019 |
| MSI           | 970 GAMING                  | [c785453555](https://linux-hardware.org/?probe=c785453555) | Aug 21, 2019 |
| MSI           | 970 GAMING                  | [c52678aebe](https://linux-hardware.org/?probe=c52678aebe) | Aug 21, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [51ea8170ef](https://linux-hardware.org/?probe=51ea8170ef) | Aug 21, 2019 |
| ASUSTek       | P5K-E                       | [75a8124577](https://linux-hardware.org/?probe=75a8124577) | Aug 19, 2019 |
| Fujitsu Si... | P5RS600-FVM                 | [37d5168f87](https://linux-hardware.org/?probe=37d5168f87) | Aug 19, 2019 |
| Packard Be... | CLR0 MP                     | [0c4ddb4115](https://linux-hardware.org/?probe=0c4ddb4115) | Aug 17, 2019 |
| Packard Be... | CLR0 MP                     | [9f282aa9b1](https://linux-hardware.org/?probe=9f282aa9b1) | Aug 17, 2019 |
| MSI           | 970 GAMING                  | [1c58331441](https://linux-hardware.org/?probe=1c58331441) | Aug 17, 2019 |
| ASUSTek       | M2NPV-VM                    | [6a07bb6de3](https://linux-hardware.org/?probe=6a07bb6de3) | Aug 16, 2019 |
| Dell          | 0FM586                      | [ae3a8ac9ac](https://linux-hardware.org/?probe=ae3a8ac9ac) | Aug 15, 2019 |
| ASUSTek       | PRIME X370-PRO              | [cc66863a72](https://linux-hardware.org/?probe=cc66863a72) | Aug 14, 2019 |
| Dell          | 0VHWTR A02                  | [ef816b48e7](https://linux-hardware.org/?probe=ef816b48e7) | Aug 14, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [d0b4620c9c](https://linux-hardware.org/?probe=d0b4620c9c) | Aug 13, 2019 |
| MSI           | 2A78h                       | [ff2075223c](https://linux-hardware.org/?probe=ff2075223c) | Aug 13, 2019 |
| ASUSTek       | P7H55D-M EVO                | [3770b95c02](https://linux-hardware.org/?probe=3770b95c02) | Aug 13, 2019 |
| Intel         | DG41WV AAE90316-104         | [5c368b1257](https://linux-hardware.org/?probe=5c368b1257) | Aug 12, 2019 |
| Gigabyte      | GA-MA78GM-S2H               | [8d9dbecbba](https://linux-hardware.org/?probe=8d9dbecbba) | Aug 11, 2019 |
| MSI           | 2A78h                       | [0bacd3a8d5](https://linux-hardware.org/?probe=0bacd3a8d5) | Aug 11, 2019 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [5015c308c8](https://linux-hardware.org/?probe=5015c308c8) | Aug 10, 2019 |
| ASRock        | J3455B-ITX                  | [1dec1979b1](https://linux-hardware.org/?probe=1dec1979b1) | Aug 10, 2019 |
| Dell          | 0Y2MRG A00                  | [dbcec87fcf](https://linux-hardware.org/?probe=dbcec87fcf) | Aug 10, 2019 |
| ASRock        | Q77M vPro                   | [73e9d6a145](https://linux-hardware.org/?probe=73e9d6a145) | Aug 09, 2019 |
| Pegatron      | 2A94h                       | [2a826cb6a9](https://linux-hardware.org/?probe=2a826cb6a9) | Aug 07, 2019 |
| ASRock        | 939A785GMH/128M             | [34e166ca13](https://linux-hardware.org/?probe=34e166ca13) | Aug 06, 2019 |
| ASRock        | 939A785GMH/128M             | [fc44594794](https://linux-hardware.org/?probe=fc44594794) | Aug 06, 2019 |
| ASRock        | 939A785GMH/128M             | [a71a136fbe](https://linux-hardware.org/?probe=a71a136fbe) | Aug 06, 2019 |
| Acer          | F672CR R01-B1               | [9849dad801](https://linux-hardware.org/?probe=9849dad801) | Aug 01, 2019 |
| ASRock        | N68C-S UCC                  | [87e89e7b91](https://linux-hardware.org/?probe=87e89e7b91) | Aug 01, 2019 |
| ASRock        | N68C-S UCC                  | [566703c97a](https://linux-hardware.org/?probe=566703c97a) | Aug 01, 2019 |
| Dell          | 042P49 A00                  | [ccafba61e8](https://linux-hardware.org/?probe=ccafba61e8) | Jul 31, 2019 |
| Unknown       | G31M-GS                     | [a2b4ea4540](https://linux-hardware.org/?probe=a2b4ea4540) | Jul 30, 2019 |
| HP            | 304Bh                       | [16c4c7c1c0](https://linux-hardware.org/?probe=16c4c7c1c0) | Jul 27, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [33f663a020](https://linux-hardware.org/?probe=33f663a020) | Jul 25, 2019 |
| ASRock        | ALiveNF6G-GLAN              | [816fe60d2d](https://linux-hardware.org/?probe=816fe60d2d) | Jul 25, 2019 |
| AMD           | Kabini CRB                  | [8c6609b568](https://linux-hardware.org/?probe=8c6609b568) | Jul 23, 2019 |
| MSI           | P43T-C51                    | [9994fb8aba](https://linux-hardware.org/?probe=9994fb8aba) | Jul 20, 2019 |
| MSI           | P43T-C51                    | [d2b57fe7aa](https://linux-hardware.org/?probe=d2b57fe7aa) | Jul 20, 2019 |
| Pegatron      | IPMMB-MQ1                   | [e3cb82e571](https://linux-hardware.org/?probe=e3cb82e571) | Jul 19, 2019 |
| ASUSTek       | Z87-PRO                     | [b61d174c21](https://linux-hardware.org/?probe=b61d174c21) | Jul 17, 2019 |
| Dell          | 0WR7PY A02                  | [87dab1466b](https://linux-hardware.org/?probe=87dab1466b) | Jul 16, 2019 |
| Dell          | 03KWTV A00                  | [2454aeb8ab](https://linux-hardware.org/?probe=2454aeb8ab) | Jul 15, 2019 |
| Intel         | D34010WYK H14771-302        | [84e10f6b4c](https://linux-hardware.org/?probe=84e10f6b4c) | Jul 15, 2019 |
| ASUSTek       | M2A-VM                      | [eb0cdd472f](https://linux-hardware.org/?probe=eb0cdd472f) | Jul 14, 2019 |
| ASRock        | H61M-VG4                    | [516ebdd1c3](https://linux-hardware.org/?probe=516ebdd1c3) | Jul 13, 2019 |
| ASUSTek       | F1A75-M PRO                 | [7a1ebd3e5d](https://linux-hardware.org/?probe=7a1ebd3e5d) | Jul 13, 2019 |
| ASRock        | H61M-VG4                    | [6b82eae1a5](https://linux-hardware.org/?probe=6b82eae1a5) | Jul 10, 2019 |
| MSI           | X399 SLI PLUS               | [a9b1fd6467](https://linux-hardware.org/?probe=a9b1fd6467) | Jul 09, 2019 |
| AMI           | Cherry Trail CR             | [52d4377bd6](https://linux-hardware.org/?probe=52d4377bd6) | Jul 08, 2019 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [d8dff6cec0](https://linux-hardware.org/?probe=d8dff6cec0) | Jul 06, 2019 |
| ASRock        | 990FX Extreme9              | [7b99fd4c95](https://linux-hardware.org/?probe=7b99fd4c95) | Jul 06, 2019 |
| ASUSTek       | M5A97 R2.0                  | [22ef3947c2](https://linux-hardware.org/?probe=22ef3947c2) | Jul 05, 2019 |
| HP            | 18E5                        | [a7a1e71c76](https://linux-hardware.org/?probe=a7a1e71c76) | Jul 01, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [71188db9d0](https://linux-hardware.org/?probe=71188db9d0) | Jun 30, 2019 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [42619a6cca](https://linux-hardware.org/?probe=42619a6cca) | Jun 26, 2019 |
| Intel         | X58                         | [4221302feb](https://linux-hardware.org/?probe=4221302feb) | Jun 25, 2019 |
| ASUSTek       | Z87I-PRO                    | [ec0a4b72f3](https://linux-hardware.org/?probe=ec0a4b72f3) | Jun 23, 2019 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [30ac23f3b3](https://linux-hardware.org/?probe=30ac23f3b3) | Jun 23, 2019 |
| ASUSTek       | Z87I-PRO                    | [04c0853eaf](https://linux-hardware.org/?probe=04c0853eaf) | Jun 23, 2019 |
| ASUSTek       | Z87I-PRO                    | [680a34868a](https://linux-hardware.org/?probe=680a34868a) | Jun 23, 2019 |
| ASUSTek       | P5E                         | [6486bde550](https://linux-hardware.org/?probe=6486bde550) | Jun 22, 2019 |
| Dell          | 0MWYPT A02                  | [c4aba2451d](https://linux-hardware.org/?probe=c4aba2451d) | Jun 20, 2019 |
| Dell          | 0MWYPT A02                  | [cbb41a8401](https://linux-hardware.org/?probe=cbb41a8401) | Jun 18, 2019 |
| ASUSTek       | P5W DH Deluxe               | [6932570c80](https://linux-hardware.org/?probe=6932570c80) | Jun 17, 2019 |
| Dell          | 0MWYPT A02                  | [a466e917ee](https://linux-hardware.org/?probe=a466e917ee) | Jun 17, 2019 |
| Dell          | 0MWYPT A02                  | [c1a479f581](https://linux-hardware.org/?probe=c1a479f581) | Jun 17, 2019 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [ca162546ee](https://linux-hardware.org/?probe=ca162546ee) | Jun 16, 2019 |
| Acer          | WG43M                       | [cb4bd052fc](https://linux-hardware.org/?probe=cb4bd052fc) | Jun 14, 2019 |
| AMI           | Cherry Trail CR             | [a55363d509](https://linux-hardware.org/?probe=a55363d509) | Jun 11, 2019 |
| ASUSTek       | P7H55-M LX                  | [9a8e939d8b](https://linux-hardware.org/?probe=9a8e939d8b) | Jun 10, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | [c582a1389f](https://linux-hardware.org/?probe=c582a1389f) | Jun 09, 2019 |
| Dell          | 0FM586                      | [6b1ccc7aa5](https://linux-hardware.org/?probe=6b1ccc7aa5) | Jun 08, 2019 |
| ZOTAC         | AMD HUDSON-M1               | [4b87155829](https://linux-hardware.org/?probe=4b87155829) | Jun 07, 2019 |
| ZOTAC         | AMD HUDSON-M1               | [d572258ad6](https://linux-hardware.org/?probe=d572258ad6) | Jun 07, 2019 |
| ASRock        | 4Core1600P35-WiFi+          | [7ab7663ace](https://linux-hardware.org/?probe=7ab7663ace) | Jun 05, 2019 |
| Packard Be... | imedia S3840                | [bd8007cd7c](https://linux-hardware.org/?probe=bd8007cd7c) | Jun 05, 2019 |
| Packard Be... | imedia S3840                | [deb19f989e](https://linux-hardware.org/?probe=deb19f989e) | Jun 05, 2019 |
| Dell          | 0215PR A02                  | [adb52fae26](https://linux-hardware.org/?probe=adb52fae26) | Jun 05, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [b4329a898c](https://linux-hardware.org/?probe=b4329a898c) | Jun 04, 2019 |
| AAEON         | UP-CHT01 V0.4               | [90f9bd30f6](https://linux-hardware.org/?probe=90f9bd30f6) | Jun 04, 2019 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7bca31b8da](https://linux-hardware.org/?probe=7bca31b8da) | Jun 04, 2019 |
| ASRock        | H77M                        | [40f6677c70](https://linux-hardware.org/?probe=40f6677c70) | Jun 02, 2019 |
| ASRock        | H77M                        | [42871b6a90](https://linux-hardware.org/?probe=42871b6a90) | Jun 02, 2019 |
| ASRock        | 960GM-VGS3 FX               | [b3601d20da](https://linux-hardware.org/?probe=b3601d20da) | May 31, 2019 |
| ASUSTek       | H97-PLUS                    | [04ce720011](https://linux-hardware.org/?probe=04ce720011) | May 30, 2019 |
| ASUSTek       | H97-PLUS                    | [e1866544d3](https://linux-hardware.org/?probe=e1866544d3) | May 30, 2019 |
| ASUSTek       | H97-PLUS                    | [1436e4ed60](https://linux-hardware.org/?probe=1436e4ed60) | May 30, 2019 |
| ASUSTek       | H97-PLUS                    | [ee8ff9f3d0](https://linux-hardware.org/?probe=ee8ff9f3d0) | May 30, 2019 |
| ASUSTek       | H97-PLUS                    | [aa04fc3ccb](https://linux-hardware.org/?probe=aa04fc3ccb) | May 30, 2019 |
| ASUSTek       | CROSSHAIR VI HERO           | [e45c3cb530](https://linux-hardware.org/?probe=e45c3cb530) | May 30, 2019 |
| HP            | 2820h                       | [4e78b7bb0b](https://linux-hardware.org/?probe=4e78b7bb0b) | May 30, 2019 |
| ASUSTek       | F1A55-M                     | [ef4e23ece5](https://linux-hardware.org/?probe=ef4e23ece5) | May 30, 2019 |
| ASUSTek       | Z87-C                       | [286c38f586](https://linux-hardware.org/?probe=286c38f586) | May 29, 2019 |
| Acer          | Aspire M3920                | [650eae20b3](https://linux-hardware.org/?probe=650eae20b3) | May 26, 2019 |
| Acer          | Aspire M3920                | [7b09cf5725](https://linux-hardware.org/?probe=7b09cf5725) | May 26, 2019 |
| Acer          | Aspire M3920                | [f5b54ae9a2](https://linux-hardware.org/?probe=f5b54ae9a2) | May 26, 2019 |
| NEC Comput... | K8M800-8237                 | [b7cec1644d](https://linux-hardware.org/?probe=b7cec1644d) | May 26, 2019 |
| ASUSTek       | P5Q-PRO                     | [28dfb478b7](https://linux-hardware.org/?probe=28dfb478b7) | May 26, 2019 |
| Unknown       | RS780-SB700                 | [51d8ebc0be](https://linux-hardware.org/?probe=51d8ebc0be) | May 25, 2019 |
| Lenovo        | NOK                         | [1696af786f](https://linux-hardware.org/?probe=1696af786f) | May 25, 2019 |
| Acer          | Predator G3600              | [dd9cd8b1c7](https://linux-hardware.org/?probe=dd9cd8b1c7) | May 25, 2019 |
| ASUSTek       | P8H61-M LE                  | [66aa87d249](https://linux-hardware.org/?probe=66aa87d249) | May 24, 2019 |
| ASUSTek       | A8N-VM/PVG                  | [3f5df90ee9](https://linux-hardware.org/?probe=3f5df90ee9) | May 22, 2019 |
| Acer          | Predator G3600              | [45e024bb55](https://linux-hardware.org/?probe=45e024bb55) | May 22, 2019 |
| ASUSTek       | M2N68-CM                    | [88eb91b4f7](https://linux-hardware.org/?probe=88eb91b4f7) | May 22, 2019 |
| ASUSTek       | M2N68-CM                    | [719bd4f66e](https://linux-hardware.org/?probe=719bd4f66e) | May 22, 2019 |
| ASUSTek       | M2N68-CM                    | [f87f2821b4](https://linux-hardware.org/?probe=f87f2821b4) | May 22, 2019 |
| ASUSTek       | M5A97 LE R2.0               | [345b8e38ba](https://linux-hardware.org/?probe=345b8e38ba) | May 22, 2019 |
| ASUSTek       | M5A97 LE R2.0               | [200c4f7e43](https://linux-hardware.org/?probe=200c4f7e43) | May 22, 2019 |
| ASUSTek       | M5A97 LE R2.0               | [9a90057972](https://linux-hardware.org/?probe=9a90057972) | May 22, 2019 |
| Intel         | DB65AL AAG12530-307         | [fe045a83c1](https://linux-hardware.org/?probe=fe045a83c1) | May 21, 2019 |
| MSI           | X99A SLI PLUS               | [608fafb692](https://linux-hardware.org/?probe=608fafb692) | May 19, 2019 |
| ASUSTek       | P8H61-M LE                  | [9d383e22cb](https://linux-hardware.org/?probe=9d383e22cb) | May 19, 2019 |
| ASUSTek       | PRIME A320M-K               | [fd5e41554c](https://linux-hardware.org/?probe=fd5e41554c) | May 19, 2019 |
| Acer          | Predator G3600              | [0244042bb6](https://linux-hardware.org/?probe=0244042bb6) | May 19, 2019 |
| Acer          | Predator G3600              | [1629f4052b](https://linux-hardware.org/?probe=1629f4052b) | May 19, 2019 |
| ASUSTek       | H87M-PRO                    | [d01f60a7dd](https://linux-hardware.org/?probe=d01f60a7dd) | May 19, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | [2c69988ab8](https://linux-hardware.org/?probe=2c69988ab8) | May 19, 2019 |
| ASUSTek       | PRIME A320M-R               | [e33f222370](https://linux-hardware.org/?probe=e33f222370) | May 18, 2019 |
| Packard Be... | FMCP7AM                     | [5443c8ec11](https://linux-hardware.org/?probe=5443c8ec11) | May 18, 2019 |
| ASUSTek       | M4N78 SE                    | [2cae195313](https://linux-hardware.org/?probe=2cae195313) | May 17, 2019 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [c4788779c1](https://linux-hardware.org/?probe=c4788779c1) | May 17, 2019 |
| Pegatron      | NARRA5                      | [1c7c48b06d](https://linux-hardware.org/?probe=1c7c48b06d) | May 16, 2019 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [4d05b20e54](https://linux-hardware.org/?probe=4d05b20e54) | May 15, 2019 |
| ASUSTek       | PRIME A320M-R               | [a30f3a7128](https://linux-hardware.org/?probe=a30f3a7128) | May 15, 2019 |
| ASUSTek       | PRIME A320M-R               | [f8b724aefd](https://linux-hardware.org/?probe=f8b724aefd) | May 14, 2019 |
| ASUSTek       | PRIME X370-A                | [8c9fbbb860](https://linux-hardware.org/?probe=8c9fbbb860) | May 14, 2019 |
| ASUSTek       | PRIME A320M-R               | [5964f7a3c8](https://linux-hardware.org/?probe=5964f7a3c8) | May 14, 2019 |
| ASUSTek       | PRIME A320M-R               | [4622adbbf5](https://linux-hardware.org/?probe=4622adbbf5) | May 14, 2019 |
| ASUSTek       | PRIME A320M-R               | [f7a56ec606](https://linux-hardware.org/?probe=f7a56ec606) | May 14, 2019 |
| ASUSTek       | PRIME A320M-R               | [15147c3009](https://linux-hardware.org/?probe=15147c3009) | May 14, 2019 |
| Pegatron      | NARRA5                      | [abecccc330](https://linux-hardware.org/?probe=abecccc330) | May 13, 2019 |
| Pegatron      | VIOLET                      | [2e29a30fa2](https://linux-hardware.org/?probe=2e29a30fa2) | May 13, 2019 |
| ASUSTek       | P5PL2                       | [fd2b46befa](https://linux-hardware.org/?probe=fd2b46befa) | May 12, 2019 |
| MSI           | MS-7758                     | [46d7f071f8](https://linux-hardware.org/?probe=46d7f071f8) | May 12, 2019 |
| MSI           | MS-7758                     | [19384b31bb](https://linux-hardware.org/?probe=19384b31bb) | May 12, 2019 |
| MSI           | MS-7758                     | [b510cafc77](https://linux-hardware.org/?probe=b510cafc77) | May 12, 2019 |
| Pegatron      | NARRA5                      | [efd216fd90](https://linux-hardware.org/?probe=efd216fd90) | May 11, 2019 |
| Dell          | 0WG864                      | [c50923e1a9](https://linux-hardware.org/?probe=c50923e1a9) | May 08, 2019 |
| Dell          | 0WG864                      | [212d2cc5ee](https://linux-hardware.org/?probe=212d2cc5ee) | May 08, 2019 |
| Dell          | 0WG864                      | [2c95b596f6](https://linux-hardware.org/?probe=2c95b596f6) | May 08, 2019 |
| ASRock        | P4i65GV                     | [700b2827fd](https://linux-hardware.org/?probe=700b2827fd) | May 07, 2019 |
| ASUSTek       | P5KR                        | [14aff7e585](https://linux-hardware.org/?probe=14aff7e585) | May 07, 2019 |
| Acer          | EM61SM/EM61PM               | [507f08ed31](https://linux-hardware.org/?probe=507f08ed31) | May 05, 2019 |
| Gigabyte      | EP31-DS3L                   | [2d9d561137](https://linux-hardware.org/?probe=2d9d561137) | May 05, 2019 |
| ASRock        | G31M-GS                     | [dfad60705b](https://linux-hardware.org/?probe=dfad60705b) | May 04, 2019 |
| ASRock        | G31M-GS                     | [b92ae462bd](https://linux-hardware.org/?probe=b92ae462bd) | May 04, 2019 |
| ASRock        | G31M-GS                     | [f690fa1af5](https://linux-hardware.org/?probe=f690fa1af5) | May 04, 2019 |
| ASRock        | P4i65GV                     | [d6c086202a](https://linux-hardware.org/?probe=d6c086202a) | May 03, 2019 |
| MSI           | Z370 GAMING PLUS            | [0e6d239f5b](https://linux-hardware.org/?probe=0e6d239f5b) | May 02, 2019 |
| ASUSTek       | M5A97 LE R2.0               | [4280987378](https://linux-hardware.org/?probe=4280987378) | May 02, 2019 |
| Acer          | FC51GM                      | [d6d1dc7cd6](https://linux-hardware.org/?probe=d6d1dc7cd6) | May 02, 2019 |
| ASUSTek       | PRIME B360M-A               | [04c0bfbf31](https://linux-hardware.org/?probe=04c0bfbf31) | May 02, 2019 |
| HP            | 82F2                        | [a94c2196f9](https://linux-hardware.org/?probe=a94c2196f9) | May 02, 2019 |
| ASUSTek       | PRIME X399-A                | [1ac34242fa](https://linux-hardware.org/?probe=1ac34242fa) | May 01, 2019 |
| Dell          | 0CKCXH A03                  | [9bf556ca2f](https://linux-hardware.org/?probe=9bf556ca2f) | May 01, 2019 |
| ASUSTek       | PRIME X399-A                | [0f37a61aa0](https://linux-hardware.org/?probe=0f37a61aa0) | May 01, 2019 |
| ASUSTek       | P7P55 LX                    | [6703609944](https://linux-hardware.org/?probe=6703609944) | Apr 28, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [cbc1cb5648](https://linux-hardware.org/?probe=cbc1cb5648) | Apr 28, 2019 |
| ASUSTek       | PRIME B360M-A               | [cc5c9f6b7e](https://linux-hardware.org/?probe=cc5c9f6b7e) | Apr 26, 2019 |
| ASRock        | N68C-S UCC                  | [e8f504dee8](https://linux-hardware.org/?probe=e8f504dee8) | Apr 26, 2019 |
| HP            | 09F8h                       | [7a6835908d](https://linux-hardware.org/?probe=7a6835908d) | Apr 25, 2019 |
| ASRock        | A75M-HVS                    | [11f4ded10c](https://linux-hardware.org/?probe=11f4ded10c) | Apr 25, 2019 |
| MSI           | Z370 GAMING PLUS            | [d1b17f65ff](https://linux-hardware.org/?probe=d1b17f65ff) | Apr 25, 2019 |
| MSI           | Z370 GAMING PLUS            | [7874d42d64](https://linux-hardware.org/?probe=7874d42d64) | Apr 25, 2019 |
| MSI           | Z370 GAMING PLUS            | [1b7113e7b1](https://linux-hardware.org/?probe=1b7113e7b1) | Apr 25, 2019 |
| Foxconn       | nT-i1000 Series PCB         | [a8642fb2fb](https://linux-hardware.org/?probe=a8642fb2fb) | Apr 24, 2019 |
| Foxconn       | nT-i1000 Series PCB         | [af352f1417](https://linux-hardware.org/?probe=af352f1417) | Apr 24, 2019 |
| Foxconn       | nT-i1000 Series PCB         | [9002c31319](https://linux-hardware.org/?probe=9002c31319) | Apr 24, 2019 |
| ASRock        | A790GXH/128M                | [f95add372c](https://linux-hardware.org/?probe=f95add372c) | Apr 24, 2019 |
| ASRock        | 970 Extreme3 R2.0           | [3488b0af2f](https://linux-hardware.org/?probe=3488b0af2f) | Apr 22, 2019 |
| ASRock        | H110 Pro BTC+               | [c242b583ec](https://linux-hardware.org/?probe=c242b583ec) | Apr 22, 2019 |
| MSI           | Gypsum                      | [5cbbe8f938](https://linux-hardware.org/?probe=5cbbe8f938) | Apr 20, 2019 |
| MSI           | G41M-P33 Combo              | [74c3a10e25](https://linux-hardware.org/?probe=74c3a10e25) | Apr 19, 2019 |
| ASUSTek       | P5QL/EPU                    | [d741a77579](https://linux-hardware.org/?probe=d741a77579) | Apr 15, 2019 |
| Lenovo        | Board                       | [d03ee36403](https://linux-hardware.org/?probe=d03ee36403) | Apr 14, 2019 |
| Gigabyte      | X58A-UD3R                   | [5feafd37c9](https://linux-hardware.org/?probe=5feafd37c9) | Apr 14, 2019 |
| ASUSTek       | M2N68-AM                    | [4732ce2414](https://linux-hardware.org/?probe=4732ce2414) | Apr 13, 2019 |
| Wistron       | ProLiant ML110 G5           | [8a73a236da](https://linux-hardware.org/?probe=8a73a236da) | Apr 12, 2019 |
| Wistron       | ProLiant ML110 G5           | [05589bdd3e](https://linux-hardware.org/?probe=05589bdd3e) | Apr 12, 2019 |
| Packard Be... | FX58                        | [6415e2e4d3](https://linux-hardware.org/?probe=6415e2e4d3) | Apr 12, 2019 |
| Packard Be... | FX58                        | [53eac3cb41](https://linux-hardware.org/?probe=53eac3cb41) | Apr 12, 2019 |
| ASUSTek       | P9X79                       | [bd2d2edb1b](https://linux-hardware.org/?probe=bd2d2edb1b) | Apr 12, 2019 |
| HP            | 2215                        | [1b3213ca06](https://linux-hardware.org/?probe=1b3213ca06) | Apr 11, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [0308fca137](https://linux-hardware.org/?probe=0308fca137) | Apr 08, 2019 |
| Sapphire      | Pure Platinum A75 0ABWM0... | [7707a1b5e7](https://linux-hardware.org/?probe=7707a1b5e7) | Apr 07, 2019 |
| Intel         | DQ67SW AAG12527-310         | [a44ce70ff7](https://linux-hardware.org/?probe=a44ce70ff7) | Apr 07, 2019 |
| Foxconn       | Irvine HP P/N               | [71ecb869b0](https://linux-hardware.org/?probe=71ecb869b0) | Apr 07, 2019 |
| HP            | 82F2                        | [2fe91dede5](https://linux-hardware.org/?probe=2fe91dede5) | Apr 07, 2019 |
| ASUSTek       | P5B                         | [6ed9a92bcb](https://linux-hardware.org/?probe=6ed9a92bcb) | Apr 06, 2019 |
| Sapphire      | Pure Platinum A75 0ABWM0... | [45e3774ef9](https://linux-hardware.org/?probe=45e3774ef9) | Apr 06, 2019 |
| MSI           | B75A-G41                    | [7347b4c9ed](https://linux-hardware.org/?probe=7347b4c9ed) | Apr 06, 2019 |
| ASRock        | 890FX Deluxe4               | [6039533473](https://linux-hardware.org/?probe=6039533473) | Apr 05, 2019 |
| ASUSTek       | P9X79                       | [7f1677c1fd](https://linux-hardware.org/?probe=7f1677c1fd) | Apr 05, 2019 |
| ASUSTek       | P9X79                       | [937d996496](https://linux-hardware.org/?probe=937d996496) | Apr 05, 2019 |
| ASRock        | H61M-ITX                    | [d1aaddc33a](https://linux-hardware.org/?probe=d1aaddc33a) | Apr 05, 2019 |
| Gigabyte      | G31M-ES2L                   | [2344aec798](https://linux-hardware.org/?probe=2344aec798) | Apr 04, 2019 |
| Foxconn       | Irvine HP P/N               | [e003dc5cfd](https://linux-hardware.org/?probe=e003dc5cfd) | Apr 04, 2019 |
| Gateway       | DT31                        | [de2c9e810c](https://linux-hardware.org/?probe=de2c9e810c) | Mar 31, 2019 |
| Apple         | Mac-F4208DC8 PVT            | [45cef6727f](https://linux-hardware.org/?probe=45cef6727f) | Mar 31, 2019 |
| HP            | 1998                        | [a5ad67c9e4](https://linux-hardware.org/?probe=a5ad67c9e4) | Mar 31, 2019 |
| HP            | 1998                        | [27782ee9c4](https://linux-hardware.org/?probe=27782ee9c4) | Mar 30, 2019 |
| Dell          | 0D6H9T A00                  | [68ecbc0d7a](https://linux-hardware.org/?probe=68ecbc0d7a) | Mar 28, 2019 |
| ASUSTek       | P5Q SE/R                    | [2d171c7607](https://linux-hardware.org/?probe=2d171c7607) | Mar 28, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [b41472725b](https://linux-hardware.org/?probe=b41472725b) | Mar 28, 2019 |
| Acer          | Veriton M4610G              | [2f8eddd53d](https://linux-hardware.org/?probe=2f8eddd53d) | Mar 24, 2019 |
| ASRock        | FM2A75M-DGS                 | [f6de22fd19](https://linux-hardware.org/?probe=f6de22fd19) | Mar 24, 2019 |
| ASRock        | 960GC-GS FX                 | [cf74aabe5e](https://linux-hardware.org/?probe=cf74aabe5e) | Mar 23, 2019 |
| MSI           | 760GM-P33                   | [0b9f27acd5](https://linux-hardware.org/?probe=0b9f27acd5) | Mar 23, 2019 |
| ABIT          | IS-10                       | [14744c26c5](https://linux-hardware.org/?probe=14744c26c5) | Mar 23, 2019 |
| Dell          | 0RF703                      | [bbc6b47eed](https://linux-hardware.org/?probe=bbc6b47eed) | Mar 23, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7e41958b72](https://linux-hardware.org/?probe=7e41958b72) | Mar 22, 2019 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [0fe70fbf04](https://linux-hardware.org/?probe=0fe70fbf04) | Mar 22, 2019 |
| ASUSTek       | P5K SE                      | [4dd77dd778](https://linux-hardware.org/?probe=4dd77dd778) | Mar 18, 2019 |
| Gigabyte      | B450 AORUS PRO-CF           | [c343341c9f](https://linux-hardware.org/?probe=c343341c9f) | Mar 15, 2019 |
| Pegatron      | Benicia                     | [a7cbffecf0](https://linux-hardware.org/?probe=a7cbffecf0) | Mar 13, 2019 |
| Intel         | DQ67SW AAG12527-310         | [a678e2b4fc](https://linux-hardware.org/?probe=a678e2b4fc) | Mar 07, 2019 |
| MSI           | MS-7345                     | [1ccbb9556f](https://linux-hardware.org/?probe=1ccbb9556f) | Mar 04, 2019 |
| ASRock        | FM2A75M-DGS R2.0            | [24c1ab909a](https://linux-hardware.org/?probe=24c1ab909a) | Feb 25, 2019 |
| ASUSTek       | P8H61/USB3                  | [ec3e833088](https://linux-hardware.org/?probe=ec3e833088) | Feb 24, 2019 |
| Acer          | Aspire TC-780               | [30a1f0e90f](https://linux-hardware.org/?probe=30a1f0e90f) | Feb 24, 2019 |
| ASUSTek       | D520MT_D520SF_D320MT        | [a5b780e131](https://linux-hardware.org/?probe=a5b780e131) | Feb 22, 2019 |
| ASUSTek       | H170 PRO GAMING             | [d654a8db62](https://linux-hardware.org/?probe=d654a8db62) | Feb 22, 2019 |
| ASUSTek       | H170 PRO GAMING             | [81baad9132](https://linux-hardware.org/?probe=81baad9132) | Feb 22, 2019 |
| Foxconn       | P4M900-8237A                | [6a98e2c476](https://linux-hardware.org/?probe=6a98e2c476) | Feb 22, 2019 |
| ASUSTek       | P5KC                        | [7d23dd895a](https://linux-hardware.org/?probe=7d23dd895a) | Feb 14, 2019 |
| ASUSTek       | P5KC                        | [cf4de580b7](https://linux-hardware.org/?probe=cf4de580b7) | Feb 14, 2019 |
| ASUSTek       | P5KC                        | [6fc43ef3be](https://linux-hardware.org/?probe=6fc43ef3be) | Feb 14, 2019 |
| ASUSTek       | M4A78LT-M-LE                | [19741eb873](https://linux-hardware.org/?probe=19741eb873) | Feb 13, 2019 |
| American M... | P4S61                       | [9c2dd93e2e](https://linux-hardware.org/?probe=9c2dd93e2e) | Feb 11, 2019 |
| ASUSTek       | M5A99FX PRO R2.0            | [2bb9f36e68](https://linux-hardware.org/?probe=2bb9f36e68) | Feb 10, 2019 |
| ASUSTek       | M2N-MX                      | [8c4716b30a](https://linux-hardware.org/?probe=8c4716b30a) | Feb 09, 2019 |
| ASUSTek       | M2N-MX                      | [7c41426c71](https://linux-hardware.org/?probe=7c41426c71) | Feb 09, 2019 |
| Alienware     | 0R3FWM A00                  | [30eaa0ac0a](https://linux-hardware.org/?probe=30eaa0ac0a) | Feb 01, 2019 |
| ASRock        | H110M-HDV                   | [54368ba4d1](https://linux-hardware.org/?probe=54368ba4d1) | Jan 29, 2019 |
| ASRock        | H110M-HDV                   | [218242e989](https://linux-hardware.org/?probe=218242e989) | Jan 29, 2019 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [30bc86cdbe](https://linux-hardware.org/?probe=30bc86cdbe) | Jan 28, 2019 |
| Intel         | DG41WV AAE90316-104         | [b5dd161856](https://linux-hardware.org/?probe=b5dd161856) | Jan 27, 2019 |
| ASUSTek       | P7H55-M/USB3                | [b378ad2452](https://linux-hardware.org/?probe=b378ad2452) | Jan 27, 2019 |
| Intel         | DG41WV AAE90316-104         | [a8e56904d2](https://linux-hardware.org/?probe=a8e56904d2) | Jan 26, 2019 |
| Dell          | 0HHV7N A00                  | [2369e0376d](https://linux-hardware.org/?probe=2369e0376d) | Jan 25, 2019 |
| ASRock        | H61M-ITX                    | [444985c9a5](https://linux-hardware.org/?probe=444985c9a5) | Jan 24, 2019 |
| Alienware     | 0R3FWM A00                  | [827502254d](https://linux-hardware.org/?probe=827502254d) | Jan 24, 2019 |
| ASUSTek       | M4A88T-V EVO                | [9f6a6f2a7f](https://linux-hardware.org/?probe=9f6a6f2a7f) | Jan 21, 2019 |
| ASUSTek       | H81M-K                      | [5802ade744](https://linux-hardware.org/?probe=5802ade744) | Jan 20, 2019 |
| IBM           | Board                       | [59e9c26aad](https://linux-hardware.org/?probe=59e9c26aad) | Jan 18, 2019 |
| IBM           | Board                       | [97804a6851](https://linux-hardware.org/?probe=97804a6851) | Jan 18, 2019 |
| Pegatron      | Benicia                     | [e8351f801e](https://linux-hardware.org/?probe=e8351f801e) | Jan 11, 2019 |
| Fujitsu       | D3003-S3 S26361-D3003-S3    | [311bcdd823](https://linux-hardware.org/?probe=311bcdd823) | Jan 10, 2019 |
| Acer          | FG43D                       | [38e32ac147](https://linux-hardware.org/?probe=38e32ac147) | Jan 09, 2019 |
| Acer          | FG43D                       | [addb6fb0d9](https://linux-hardware.org/?probe=addb6fb0d9) | Jan 09, 2019 |
| Gigabyte      | G31M-ES2L                   | [d69a897cf8](https://linux-hardware.org/?probe=d69a897cf8) | Jan 07, 2019 |
| Gigabyte      | G31M-ES2L                   | [75827661a7](https://linux-hardware.org/?probe=75827661a7) | Jan 07, 2019 |
| Gigabyte      | G31M-ES2L                   | [8531feefb2](https://linux-hardware.org/?probe=8531feefb2) | Jan 07, 2019 |
| ASRock        | Z170 Gaming-ITX/ac          | [7a0fc72547](https://linux-hardware.org/?probe=7a0fc72547) | Jan 05, 2019 |
| MSI           | X370 GAMING PRO CARBON      | [5323c68fa8](https://linux-hardware.org/?probe=5323c68fa8) | Jan 05, 2019 |
| MSI           | X370 GAMING PRO CARBON      | [dff462287f](https://linux-hardware.org/?probe=dff462287f) | Jan 05, 2019 |
| ASUSTek       | LEONITE                     | [6fc9b4048b](https://linux-hardware.org/?probe=6fc9b4048b) | Jan 04, 2019 |
| ASUSTek       | LEONITE                     | [40f7eaddac](https://linux-hardware.org/?probe=40f7eaddac) | Jan 04, 2019 |
| ASRock        | H55M-LE                     | [221f27f481](https://linux-hardware.org/?probe=221f27f481) | Jan 02, 2019 |
| ASRock        | H55M-LE                     | [791e87f6bf](https://linux-hardware.org/?probe=791e87f6bf) | Jan 02, 2019 |
| ASUSTek       | M4A78LT-M-LE                | [fe8424f4d4](https://linux-hardware.org/?probe=fe8424f4d4) | Jan 01, 2019 |
| Gigabyte      | H81M-D2V                    | [789464d860](https://linux-hardware.org/?probe=789464d860) | Dec 27, 2018 |
| Lenovo        | Board                       | [72f3ae3f7d](https://linux-hardware.org/?probe=72f3ae3f7d) | Dec 25, 2018 |
| Lenovo        | Board                       | [900cf9b2b2](https://linux-hardware.org/?probe=900cf9b2b2) | Dec 25, 2018 |
| Lenovo        | Board                       | [fc38539f2d](https://linux-hardware.org/?probe=fc38539f2d) | Dec 25, 2018 |
| Lenovo        | Board                       | [12948b282a](https://linux-hardware.org/?probe=12948b282a) | Dec 25, 2018 |
| ASUSTek       | A88XM-A                     | [08da0b9e0b](https://linux-hardware.org/?probe=08da0b9e0b) | Dec 24, 2018 |
| eMachines     | MCP61PM-GM                  | [537937fbe2](https://linux-hardware.org/?probe=537937fbe2) | Dec 20, 2018 |
| Gigabyte      | X58A-UD3R                   | [8d5f93fffc](https://linux-hardware.org/?probe=8d5f93fffc) | Dec 17, 2018 |
| MSI           | 0A48                        | [98cd0351c6](https://linux-hardware.org/?probe=98cd0351c6) | Dec 15, 2018 |
| HP            | 18E4                        | [9c96d3613a](https://linux-hardware.org/?probe=9c96d3613a) | Dec 14, 2018 |
| Pegatron      | 2A73h                       | [f45f113932](https://linux-hardware.org/?probe=f45f113932) | Dec 08, 2018 |
| Pegatron      | 2A73h                       | [9c12b09695](https://linux-hardware.org/?probe=9c12b09695) | Dec 08, 2018 |
| Dell          | 09KPNV A00                  | [ae161c9207](https://linux-hardware.org/?probe=ae161c9207) | Dec 06, 2018 |
| HP            | 8399                        | [9440f6405b](https://linux-hardware.org/?probe=9440f6405b) | Dec 04, 2018 |
| ASUSTek       | P8H61-M LX R2.0             | [bf021cba4f](https://linux-hardware.org/?probe=bf021cba4f) | Dec 02, 2018 |
| Fujitsu Si... | D1327 S26361-D1327          | [2ab4ef4b41](https://linux-hardware.org/?probe=2ab4ef4b41) | Dec 01, 2018 |
| ASRock        | AB350M-HDV                  | [5e77397648](https://linux-hardware.org/?probe=5e77397648) | Nov 28, 2018 |
| HP            | 8399                        | [b0f6174974](https://linux-hardware.org/?probe=b0f6174974) | Nov 26, 2018 |
| ABIT          | IP35                        | [5c0fc04230](https://linux-hardware.org/?probe=5c0fc04230) | Nov 24, 2018 |
| ABIT          | IP35                        | [04d500e758](https://linux-hardware.org/?probe=04d500e758) | Nov 24, 2018 |
| ABIT          | IP35                        | [bec1e5bda4](https://linux-hardware.org/?probe=bec1e5bda4) | Nov 24, 2018 |
| ABIT          | IP35                        | [f2a1818345](https://linux-hardware.org/?probe=f2a1818345) | Nov 23, 2018 |
| ABIT          | IP35                        | [714715e472](https://linux-hardware.org/?probe=714715e472) | Nov 23, 2018 |
| ABIT          | IP35                        | [ad4855ee87](https://linux-hardware.org/?probe=ad4855ee87) | Nov 23, 2018 |
| ASUSTek       | P8H77-V                     | [0f38e59fd3](https://linux-hardware.org/?probe=0f38e59fd3) | Nov 22, 2018 |
| ASRock        | G31M-GS                     | [9c1a149f7c](https://linux-hardware.org/?probe=9c1a149f7c) | Nov 17, 2018 |
| ASRock        | G31M-GS                     | [cd4d4ebed5](https://linux-hardware.org/?probe=cd4d4ebed5) | Nov 17, 2018 |
| MSI           | H81I                        | [bbbe063975](https://linux-hardware.org/?probe=bbbe063975) | Nov 17, 2018 |
| MSI           | H81I                        | [b3dc18a7ac](https://linux-hardware.org/?probe=b3dc18a7ac) | Nov 17, 2018 |
| ASUSTek       | P5VD2-VM SE                 | [b41f8abc76](https://linux-hardware.org/?probe=b41f8abc76) | Nov 13, 2018 |
| ASUSTek       | P5VD2-VM SE                 | [96ffe39cbd](https://linux-hardware.org/?probe=96ffe39cbd) | Nov 13, 2018 |
| ASUSTek       | P5KPL-VM                    | [45fcbc8b9a](https://linux-hardware.org/?probe=45fcbc8b9a) | Nov 13, 2018 |
| ASUSTek       | P5KPL-VM                    | [87ab309588](https://linux-hardware.org/?probe=87ab309588) | Nov 13, 2018 |
| ASUSTek       | AM1M-A                      | [2b706273bd](https://linux-hardware.org/?probe=2b706273bd) | Nov 11, 2018 |
| ASUSTek       | AM1M-A                      | [9cdec81379](https://linux-hardware.org/?probe=9cdec81379) | Nov 11, 2018 |
| ASUSTek       | AM1M-A                      | [be18959cdc](https://linux-hardware.org/?probe=be18959cdc) | Nov 11, 2018 |
| MSI           | B450M PRO-M2                | [f83c6e1394](https://linux-hardware.org/?probe=f83c6e1394) | Nov 08, 2018 |
| Unknown       | SKYBAY                      | [658ac65ba1](https://linux-hardware.org/?probe=658ac65ba1) | Nov 08, 2018 |
| ASUSTek       | F1A55-M LE                  | [c8ef367493](https://linux-hardware.org/?probe=c8ef367493) | Nov 06, 2018 |
| ASUSTek       | F1A55-M LE                  | [80e8542424](https://linux-hardware.org/?probe=80e8542424) | Nov 06, 2018 |
| ASRock        | FM2A58M-DG3+                | [a2530eeec3](https://linux-hardware.org/?probe=a2530eeec3) | Nov 04, 2018 |
| ASRock        | FM2A58M-DG3+                | [76931a39f2](https://linux-hardware.org/?probe=76931a39f2) | Nov 04, 2018 |
| ASUSTek       | P5N-E SLI                   | [55d1430fc2](https://linux-hardware.org/?probe=55d1430fc2) | Nov 04, 2018 |
| ASRock        | H110M-HDV                   | [646413bc3f](https://linux-hardware.org/?probe=646413bc3f) | Nov 01, 2018 |
| ASRock        | H110M-HDV                   | [720ad741cc](https://linux-hardware.org/?probe=720ad741cc) | Oct 30, 2018 |
| ASUSTek       | CM6870                      | [49cb8fdcc7](https://linux-hardware.org/?probe=49cb8fdcc7) | Oct 29, 2018 |
| ASUSTek       | B85M-E                      | [8321542cc3](https://linux-hardware.org/?probe=8321542cc3) | Oct 27, 2018 |
| ASUSTek       | P8P67                       | [177da06fdd](https://linux-hardware.org/?probe=177da06fdd) | Oct 27, 2018 |
| ASRock        | A790GXH/128M                | [19a4bae006](https://linux-hardware.org/?probe=19a4bae006) | Oct 25, 2018 |
| ASRock        | A790GXH/128M                | [6bdf47a3f7](https://linux-hardware.org/?probe=6bdf47a3f7) | Oct 25, 2018 |
| Intel         | DQ965GF AAD41676-305        | [a876d7fa9f](https://linux-hardware.org/?probe=a876d7fa9f) | Oct 25, 2018 |
| ASRock        | H110M-HDV                   | [3c66fe73bc](https://linux-hardware.org/?probe=3c66fe73bc) | Oct 23, 2018 |
| ASUSTek       | B75M-A                      | [9740c7ca90](https://linux-hardware.org/?probe=9740c7ca90) | Oct 13, 2018 |
| ASUSTek       | B75M-A                      | [7f0ccabd64](https://linux-hardware.org/?probe=7f0ccabd64) | Oct 13, 2018 |
| ASUSTek       | B75M-A                      | [83a4070f71](https://linux-hardware.org/?probe=83a4070f71) | Oct 13, 2018 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [57510c73af](https://linux-hardware.org/?probe=57510c73af) | Oct 12, 2018 |
| ASUSTek       | PRIME X370-PRO              | [50986e373a](https://linux-hardware.org/?probe=50986e373a) | Oct 10, 2018 |
| ASUSTek       | PRIME X370-PRO              | [1ae1b1695a](https://linux-hardware.org/?probe=1ae1b1695a) | Oct 09, 2018 |
| ASUSTek       | CM1435                      | [670c180bea](https://linux-hardware.org/?probe=670c180bea) | Oct 08, 2018 |
| ASUSTek       | CM1435                      | [3e4e48d214](https://linux-hardware.org/?probe=3e4e48d214) | Oct 08, 2018 |
| ASUSTek       | CM1435                      | [e9a208ac1b](https://linux-hardware.org/?probe=e9a208ac1b) | Oct 08, 2018 |
| ASUSTek       | CM1435                      | [f53ba1a779](https://linux-hardware.org/?probe=f53ba1a779) | Oct 08, 2018 |
| ASUSTek       | CM1435                      | [1364502e7c](https://linux-hardware.org/?probe=1364502e7c) | Oct 08, 2018 |
| Gigabyte      | GA-MA790FX-DQ6              | [a06e30b4b5](https://linux-hardware.org/?probe=a06e30b4b5) | Oct 04, 2018 |
| Gigabyte      | GA-MA790FX-DQ6              | [cbc3009bde](https://linux-hardware.org/?probe=cbc3009bde) | Oct 04, 2018 |
| ASUSTek       | H97-PRO                     | [383ceccd01](https://linux-hardware.org/?probe=383ceccd01) | Oct 01, 2018 |
| ASUSTek       | P6T DELUXE V2               | [0621a268eb](https://linux-hardware.org/?probe=0621a268eb) | Sep 29, 2018 |
| HP            | 3397                        | [ead7241972](https://linux-hardware.org/?probe=ead7241972) | Sep 23, 2018 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [b676102907](https://linux-hardware.org/?probe=b676102907) | Sep 22, 2018 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [05333d5cd5](https://linux-hardware.org/?probe=05333d5cd5) | Sep 22, 2018 |
| Alienware     | 0KM92T A01                  | [cba5d3466f](https://linux-hardware.org/?probe=cba5d3466f) | Sep 21, 2018 |
| ASRock        | FM2A58M-DG3+                | [9944072a79](https://linux-hardware.org/?probe=9944072a79) | Sep 09, 2018 |
| ASUSTek       | P8H77-M                     | [e44fbb6e80](https://linux-hardware.org/?probe=e44fbb6e80) | Aug 25, 2018 |
| ASUSTek       | P5KPL-AM EPU                | [a8617f6757](https://linux-hardware.org/?probe=a8617f6757) | Aug 22, 2018 |
| MSI           | MS-7369                     | [2168e29cd2](https://linux-hardware.org/?probe=2168e29cd2) | Aug 20, 2018 |
| ASUSTek       | P5LD2-SE                    | [14bbc0909d](https://linux-hardware.org/?probe=14bbc0909d) | Aug 16, 2018 |
| ASUSTek       | H87-PRO                     | [04639570f3](https://linux-hardware.org/?probe=04639570f3) | Aug 16, 2018 |
| ASUSTek       | P5LD2-SE                    | [b77721282e](https://linux-hardware.org/?probe=b77721282e) | Aug 11, 2018 |
| ASUSTek       | P8B75-M LX                  | [673d732d4b](https://linux-hardware.org/?probe=673d732d4b) | Aug 10, 2018 |
| Biostar       | TF570 SLI A2+               | [93cd5b587f](https://linux-hardware.org/?probe=93cd5b587f) | Jul 23, 2018 |
| ASUSTek       | P6TD DELUXE                 | [9687b78324](https://linux-hardware.org/?probe=9687b78324) | Jul 19, 2018 |
| Intel         | D865GLC AAC28909-413        | [1b7ee2439a](https://linux-hardware.org/?probe=1b7ee2439a) | Jun 18, 2018 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [bb3b9b883b](https://linux-hardware.org/?probe=bb3b9b883b) | Jun 13, 2018 |
| Acer          | Aspire X1700                | [6db3031d1e](https://linux-hardware.org/?probe=6db3031d1e) | Jun 04, 2018 |
| Acer          | Aspire X1700                | [f034094a38](https://linux-hardware.org/?probe=f034094a38) | Jun 02, 2018 |
| Acer          | Aspire X1700                | [8e792c1322](https://linux-hardware.org/?probe=8e792c1322) | Jun 01, 2018 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [d7ce3e314f](https://linux-hardware.org/?probe=d7ce3e314f) | May 31, 2018 |
| MSI           | Boston                      | [b77a077837](https://linux-hardware.org/?probe=b77a077837) | May 31, 2018 |
| ASRock        | AB350M-HDV                  | [94b0cbf647](https://linux-hardware.org/?probe=94b0cbf647) | May 26, 2018 |
| ASUSTek       | M4A78T-E                    | [9bc8084a3e](https://linux-hardware.org/?probe=9bc8084a3e) | May 05, 2018 |
| American M... | K7S41GX                     | [f878099d6d](https://linux-hardware.org/?probe=f878099d6d) | Mar 29, 2018 |
| ASRock        | H81M-HDS R2.0               | [c27bf308e2](https://linux-hardware.org/?probe=c27bf308e2) | Mar 25, 2018 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [4c516558e0](https://linux-hardware.org/?probe=4c516558e0) | Mar 25, 2018 |
| MSI           | 970 GAMING                  | [c0f433d67b](https://linux-hardware.org/?probe=c0f433d67b) | Mar 19, 2018 |
| ASUSTek       | M4N78 SE                    | [f938584c96](https://linux-hardware.org/?probe=f938584c96) | Mar 11, 2018 |
| ASUSTek       | M5A78L/USB3                 | [9664aa0934](https://linux-hardware.org/?probe=9664aa0934) | Mar 02, 2018 |
| ASUSTek       | Rampage V EDITION 10        | [c21900b2a2](https://linux-hardware.org/?probe=c21900b2a2) | Feb 22, 2018 |
| ASUSTek       | M4A77TD PRO                 | [781fe5db32](https://linux-hardware.org/?probe=781fe5db32) | Feb 21, 2018 |
| ASUSTek       | M4A78T-E                    | [3444e5caf7](https://linux-hardware.org/?probe=3444e5caf7) | Feb 15, 2018 |
| ASUSTek       | M4N78 SE                    | [80623de393](https://linux-hardware.org/?probe=80623de393) | Jan 27, 2018 |
| ASUSTek       | P5QL                        | [b42067ae5a](https://linux-hardware.org/?probe=b42067ae5a) | Jan 20, 2018 |
| MSI           | 0A48                        | [d5bb47bc4a](https://linux-hardware.org/?probe=d5bb47bc4a) | Jan 14, 2018 |
| Acer          | F89M R03-A4                 | [b2f6f334bf](https://linux-hardware.org/?probe=b2f6f334bf) | Jan 13, 2018 |
| ASUSTek       | P5KPL-AM EPU                | [ea04a3420c](https://linux-hardware.org/?probe=ea04a3420c) | Jan 10, 2018 |
| ASUSTek       | M3N78-EMH HDMI              | [6124e61650](https://linux-hardware.org/?probe=6124e61650) | Jan 07, 2018 |
| Gigabyte      | GA-MA78LMT-S2               | [5ed098d56c](https://linux-hardware.org/?probe=5ed098d56c) | Jan 07, 2018 |
| ASUSTek       | P5KPL-AM EPU                | [a7e3bc770c](https://linux-hardware.org/?probe=a7e3bc770c) | Jan 06, 2018 |
| Packard Be... | ixtreme M5860               | [7309ec9e94](https://linux-hardware.org/?probe=7309ec9e94) | Dec 20, 2017 |
| HP            | 3048h                       | [b60039a681](https://linux-hardware.org/?probe=b60039a681) | Dec 16, 2017 |
| Acer          | Aspire TC-780               | [04cee62819](https://linux-hardware.org/?probe=04cee62819) | Dec 12, 2017 |
| ASRock        | ConRoe1333-D667             | [b193872571](https://linux-hardware.org/?probe=b193872571) | Dec 09, 2017 |
| ASRock        | ConRoe1333-D667             | [adbecc9568](https://linux-hardware.org/?probe=adbecc9568) | Dec 09, 2017 |
| HP            | 3031h                       | [5cb194e5b4](https://linux-hardware.org/?probe=5cb194e5b4) | Nov 19, 2017 |
| Acer          | EM61SM/EM61PM               | [0f1e4fd81e](https://linux-hardware.org/?probe=0f1e4fd81e) | Nov 12, 2017 |
| ASUSTek       | X79-DELUXE                  | [27e7bda60a](https://linux-hardware.org/?probe=27e7bda60a) | Nov 09, 2017 |
| ASUSTek       | X79-DELUXE                  | [5aa8c1cfc3](https://linux-hardware.org/?probe=5aa8c1cfc3) | Nov 09, 2017 |
| Gigabyte      | EP43T-UD3L                  | [afa74c42cc](https://linux-hardware.org/?probe=afa74c42cc) | Nov 02, 2017 |
| Gigabyte      | EP43T-UD3L                  | [2f8363e928](https://linux-hardware.org/?probe=2f8363e928) | Nov 02, 2017 |
| Gigabyte      | EP43T-UD3L                  | [dfb0e9f882](https://linux-hardware.org/?probe=dfb0e9f882) | Nov 02, 2017 |
| Gigabyte      | 945GCMX-S2                  | [fc1fd98471](https://linux-hardware.org/?probe=fc1fd98471) | Sep 30, 2017 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [df83cb29d0](https://linux-hardware.org/?probe=df83cb29d0) | Sep 23, 2017 |
| Gigabyte      | Z97X-UD5H                   | [689a9ecd23](https://linux-hardware.org/?probe=689a9ecd23) | Sep 01, 2017 |
| ASRock        | Q1900B-ITX                  | [6081b5dd6f](https://linux-hardware.org/?probe=6081b5dd6f) | Aug 15, 2017 |
| ASRock        | Q1900B-ITX                  | [8f7861430a](https://linux-hardware.org/?probe=8f7861430a) | Aug 15, 2017 |
| Gigabyte      | G41M-Combo                  | [4040304ce4](https://linux-hardware.org/?probe=4040304ce4) | Aug 11, 2017 |
| ASUSTek       | P8B75-M LX                  | [a5e4dd2410](https://linux-hardware.org/?probe=a5e4dd2410) | Aug 09, 2017 |
| ASRock        | 775VM800                    | [10131635de](https://linux-hardware.org/?probe=10131635de) | Jul 26, 2017 |
| Gigabyte      | MZBSWBP-00                  | [8b674b2728](https://linux-hardware.org/?probe=8b674b2728) | Jul 25, 2017 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3cd2ac8c7d](https://linux-hardware.org/?probe=3cd2ac8c7d) | Jul 17, 2017 |
| ASRock        | 4CoreN73PV-HD720p           | [64e722cec4](https://linux-hardware.org/?probe=64e722cec4) | Jul 15, 2017 |
| ASUSTek       | H81M-K                      | [94f00107ce](https://linux-hardware.org/?probe=94f00107ce) | Jul 12, 2017 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4dcf86e650](https://linux-hardware.org/?probe=4dcf86e650) | Jul 03, 2017 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f9d410f5f3](https://linux-hardware.org/?probe=f9d410f5f3) | Jun 25, 2017 |
| Gigabyte      | Z97X-UD5H                   | [03dab45b38](https://linux-hardware.org/?probe=03dab45b38) | Jun 21, 2017 |
| Gigabyte      | Z97X-UD5H                   | [7f33f9ecdc](https://linux-hardware.org/?probe=7f33f9ecdc) | Jun 20, 2017 |
| ASUSTek       | P8Z68-V PRO                 | [a4a08e3712](https://linux-hardware.org/?probe=a4a08e3712) | May 28, 2017 |
| ASRock        | 775VM800                    | [2418894b55](https://linux-hardware.org/?probe=2418894b55) | May 25, 2017 |
| ASRock        | 775VM800                    | [7417b81653](https://linux-hardware.org/?probe=7417b81653) | May 20, 2017 |
| ASUSTek       | M4A78                       | [e5a3e3df43](https://linux-hardware.org/?probe=e5a3e3df43) | May 12, 2017 |
| ASUSTek       | M4A78                       | [ef7d1d0731](https://linux-hardware.org/?probe=ef7d1d0731) | May 12, 2017 |
| ASUSTek       | M4N78 SE                    | [282da82f3e](https://linux-hardware.org/?probe=282da82f3e) | May 08, 2017 |
| ASUSTek       | P6TD DELUXE                 | [5db85501f5](https://linux-hardware.org/?probe=5db85501f5) | May 07, 2017 |
| MSI           | 0A48                        | [3fe3ab3894](https://linux-hardware.org/?probe=3fe3ab3894) | Apr 25, 2017 |
| ASUSTek       | P6TD DELUXE                 | [607cc050e1](https://linux-hardware.org/?probe=607cc050e1) | Apr 23, 2017 |
| MSI           | 0A48                        | [fc3e8882c9](https://linux-hardware.org/?probe=fc3e8882c9) | Apr 19, 2017 |
| ASUSTek       | P5KPL-VM                    | [b82b8cd5ae](https://linux-hardware.org/?probe=b82b8cd5ae) | Mar 20, 2017 |
| ASUSTek       | H97M-E                      | [ad6f0de19e](https://linux-hardware.org/?probe=ad6f0de19e) | Mar 19, 2017 |
| ASRock        | AD510PV                     | [989fb4525c](https://linux-hardware.org/?probe=989fb4525c) | Feb 27, 2017 |
| MSI           | B150M BAZOOKA               | [9958b3728e](https://linux-hardware.org/?probe=9958b3728e) | Dec 26, 2016 |
| MSI           | B150M BAZOOKA               | [ae97650e7c](https://linux-hardware.org/?probe=ae97650e7c) | Dec 26, 2016 |
| ASUSTek       | P5KPL-SE                    | [03c6596d7e](https://linux-hardware.org/?probe=03c6596d7e) | Dec 14, 2016 |
| HP            | 09FCh                       | [e9647f808a](https://linux-hardware.org/?probe=e9647f808a) | Dec 06, 2016 |
| ASUSTek       | F1A55-M LE R2.0             | [27f53344ce](https://linux-hardware.org/?probe=27f53344ce) | Dec 02, 2016 |
| ASUSTek       | F1A55-M LE R2.0             | [52fe33b19f](https://linux-hardware.org/?probe=52fe33b19f) | Dec 02, 2016 |
| ASUSTek       | F1A55-M LE R2.0             | [ef2518b297](https://linux-hardware.org/?probe=ef2518b297) | Dec 02, 2016 |
| ASRock        | N68-GS4 FX                  | [9f9e718ba4](https://linux-hardware.org/?probe=9f9e718ba4) | Nov 15, 2016 |
| MSI           | G31M3                       | [15a8eccb99](https://linux-hardware.org/?probe=15a8eccb99) | Nov 12, 2016 |
| ASUSTek       | X79-DELUXE                  | [d6bb56c8f8](https://linux-hardware.org/?probe=d6bb56c8f8) | Nov 12, 2016 |
| ASUSTek       | X79-DELUXE                  | [dedac27995](https://linux-hardware.org/?probe=dedac27995) | Nov 11, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 355      | 18.9%   |
| Ubuntu 18.04        | 239      | 12.73%  |
| OpenMandriva 4.2    | 97       | 5.17%   |
| Ubuntu 20.10        | 52       | 2.77%   |
| Ubuntu 19.04        | 47       | 2.5%    |
| Ubuntu 19.10        | 43       | 2.29%   |
| OpenMandriva 4.3    | 40       | 2.13%   |
| Xubuntu 20.04       | 36       | 1.92%   |
| KDE neon 20.04      | 36       | 1.92%   |
| Xubuntu 18.04       | 32       | 1.7%    |
| ROSA R10            | 32       | 1.7%    |
| Ubuntu 21.10        | 30       | 1.6%    |
| Ubuntu 21.04        | 30       | 1.6%    |
| Arch                | 28       | 1.49%   |
| Debian 10           | 27       | 1.44%   |
| Manjaro             | 26       | 1.38%   |
| Ubuntu 18.10        | 24       | 1.28%   |
| Ubuntu 16.04        | 23       | 1.22%   |
| Linux Mint 19.3     | 23       | 1.22%   |
| Debian 11           | 23       | 1.22%   |
| Kubuntu 20.04       | 22       | 1.17%   |
| Linux Mint 20.2     | 21       | 1.12%   |
| Linux Mint 20.1     | 21       | 1.12%   |
| ROSA R11            | 20       | 1.06%   |
| Linux Mint 20       | 20       | 1.06%   |
| ROSA R9             | 19       | 1.01%   |
| Pop!_OS 20.10       | 18       | 0.96%   |
| Zorin 16            | 16       | 0.85%   |
| Zorin 15            | 16       | 0.85%   |
| Fedora 33           | 15       | 0.8%    |
| Fedora 32           | 15       | 0.8%    |
| Arch Rolling        | 15       | 0.8%    |
| ROSA R11.1          | 14       | 0.75%   |
| Xubuntu 19.10       | 13       | 0.69%   |
| Fedora 35           | 13       | 0.69%   |
| BlackPanther 18.1   | 13       | 0.69%   |
| Fedora 34           | 12       | 0.64%   |
| KDE neon 18.04      | 11       | 0.59%   |
| Pop!_OS 21.04       | 10       | 0.53%   |
| Pop!_OS 20.04       | 10       | 0.53%   |
| Linux Mint 20.3     | 10       | 0.53%   |
| Debian Testing      | 10       | 0.53%   |
| ROSA R8.1           | 9        | 0.48%   |
| OpenMandriva 4.50   | 9        | 0.48%   |
| Lubuntu 20.04       | 9        | 0.48%   |
| Fedora 31           | 9        | 0.48%   |
| ROSA R8             | 8        | 0.43%   |
| Pop!_OS 21.10       | 8        | 0.43%   |
| Peppermint 10       | 7        | 0.37%   |
| Linux Mint 19.1     | 7        | 0.37%   |
| EndeavourOS Rolling | 7        | 0.37%   |
| Ubuntu MATE 18.04   | 6        | 0.32%   |
| Linux Mint 19.2     | 6        | 0.32%   |
| Xubuntu 16.04       | 5        | 0.27%   |
| Lubuntu 18.04       | 5        | 0.27%   |
| Fedora 30           | 5        | 0.27%   |
| Zorin 12            | 4        | 0.21%   |
| Xubuntu 21.10       | 4        | 0.21%   |
| Xubuntu 21.04       | 4        | 0.21%   |
| Xubuntu 20.10       | 4        | 0.21%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 812      | 45.41%  |
| OpenMandriva  | 146      | 8.17%   |
| Linux Mint    | 107      | 5.98%   |
| Xubuntu       | 92       | 5.15%   |
| ROSA          | 88       | 4.92%   |
| Debian        | 68       | 3.8%    |
| Fedora        | 64       | 3.58%   |
| Manjaro       | 51       | 2.85%   |
| Pop!_OS       | 47       | 2.63%   |
| KDE neon      | 46       | 2.57%   |
| Arch          | 42       | 2.35%   |
| Kubuntu       | 39       | 2.18%   |
| Zorin         | 36       | 2.01%   |
| Lubuntu       | 21       | 1.17%   |
| Ubuntu MATE   | 15       | 0.84%   |
| BlackPanther  | 13       | 0.73%   |
| EndeavourOS   | 11       | 0.62%   |
| Clear Linux   | 11       | 0.62%   |
| openSUSE      | 10       | 0.56%   |
| Endless       | 10       | 0.56%   |
| Peppermint    | 7        | 0.39%   |
| Gentoo        | 7        | 0.39%   |
| Elementary    | 7        | 0.39%   |
| Slackware     | 4        | 0.22%   |
| LMDE          | 4        | 0.22%   |
| ArcoLinux     | 4        | 0.22%   |
| Garuda Linux  | 3        | 0.17%   |
| Ubuntu Budgie | 2        | 0.11%   |
| RHEL          | 2        | 0.11%   |
| Parrot        | 2        | 0.11%   |
| LinuxFX       | 2        | 0.11%   |
| Chrome OS     | 2        | 0.11%   |
| CentOS        | 2        | 0.11%   |
| Xero          | 1        | 0.06%   |
| Siduction     | 1        | 0.06%   |
| Puppy         | 1        | 0.06%   |
| Parabola      | 1        | 0.06%   |
| Oracle Linux  | 1        | 0.06%   |
| MX            | 1        | 0.06%   |
| Mageia        | 1        | 0.06%   |
| Kali          | 1        | 0.06%   |
| Jingos        | 1        | 0.06%   |
| Deepin        | 1        | 0.06%   |
| Artix         | 1        | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 95       | 4.48%   |
| 5.4.0-42-generic                | 53       | 2.5%    |
| 5.4.0-52-generic                | 44       | 2.07%   |
| 5.16.7-desktop-1omv4003         | 40       | 1.89%   |
| 5.4.0-58-generic                | 25       | 1.18%   |
| 5.4.0-48-generic                | 25       | 1.18%   |
| 5.4.0-56-generic                | 23       | 1.08%   |
| 5.3.0-46-generic                | 23       | 1.08%   |
| 5.3.0-40-generic                | 23       | 1.08%   |
| 5.4.0-29-generic                | 21       | 0.99%   |
| 5.4.0-26-generic                | 21       | 0.99%   |
| 5.4.0-54-generic                | 20       | 0.94%   |
| 5.4.0-40-generic                | 19       | 0.9%    |
| 5.4.0-28-generic                | 18       | 0.85%   |
| 5.8.0-59-generic                | 17       | 0.8%    |
| 5.0.0-32-generic                | 17       | 0.8%    |
| 5.8.0-41-generic                | 16       | 0.75%   |
| 5.4.0-65-generic                | 16       | 0.75%   |
| 5.4.0-37-generic                | 16       | 0.75%   |
| 5.4.0-33-generic                | 16       | 0.75%   |
| 5.11.0-38-generic               | 16       | 0.75%   |
| 5.3.0-42-generic                | 15       | 0.71%   |
| 5.8.0-44-generic                | 14       | 0.66%   |
| 5.4.0-31-generic                | 14       | 0.66%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.66%   |
| 4.18.0-25-generic               | 14       | 0.66%   |
| 5.13.0-39-generic               | 13       | 0.61%   |
| 4.18.16-desktop-1bP             | 13       | 0.61%   |
| 4.15.0-29-generic               | 13       | 0.61%   |
| 5.8.0-48-generic                | 12       | 0.57%   |
| 5.4.0-47-generic                | 12       | 0.57%   |
| 5.11.0-27-generic               | 12       | 0.57%   |
| 5.0.0-27-generic                | 12       | 0.57%   |
| 5.0.0-23-generic                | 12       | 0.57%   |
| 5.0.0-13-generic                | 12       | 0.57%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 12       | 0.57%   |
| 5.8.0-50-generic                | 11       | 0.52%   |
| 5.8.0-29-generic                | 11       | 0.52%   |
| 5.4.0-73-generic                | 11       | 0.52%   |
| 5.11.0-41-generic               | 11       | 0.52%   |
| 5.11.0-40-generic               | 11       | 0.52%   |
| 5.0.0-25-generic                | 11       | 0.52%   |
| 5.8.0-7630-generic              | 10       | 0.47%   |
| 5.4.0-53-generic                | 10       | 0.47%   |
| 5.3.0-28-generic                | 10       | 0.47%   |
| 5.3.0-26-generic                | 10       | 0.47%   |
| 5.0.0-37-generic                | 10       | 0.47%   |
| 4.18.0-15-generic               | 10       | 0.47%   |
| 4.15.0-43-generic               | 10       | 0.47%   |
| 5.4.0-45-generic                | 9        | 0.42%   |
| 5.4.0-39-generic                | 9        | 0.42%   |
| 5.3.0-53-generic                | 9        | 0.42%   |
| 5.3.0-45-generic                | 9        | 0.42%   |
| 5.3.0-18-generic                | 9        | 0.42%   |
| 5.10.0-11-amd64                 | 9        | 0.42%   |
| 4.15.0-72-generic               | 9        | 0.42%   |
| 5.8.0-43-generic                | 8        | 0.38%   |
| 5.8.0-36-generic                | 8        | 0.38%   |
| 5.8.0-33-generic                | 8        | 0.38%   |
| 5.4.0-91-generic                | 8        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 467      | 24.11%  |
| 4.15.0  | 202      | 10.43%  |
| 5.8.0   | 163      | 8.42%   |
| 5.3.0   | 140      | 7.23%   |
| 5.11.0  | 111      | 5.73%   |
| 5.0.0   | 98       | 5.06%   |
| 5.10.14 | 96       | 4.96%   |
| 5.13.0  | 71       | 3.67%   |
| 4.18.0  | 63       | 3.25%   |
| 5.16.7  | 41       | 2.12%   |
| 4.19.0  | 24       | 1.24%   |
| 5.10.0  | 22       | 1.14%   |
| 4.9.60  | 18       | 0.93%   |
| 4.9.20  | 17       | 0.88%   |
| 4.18.16 | 14       | 0.72%   |
| 5.15.0  | 9        | 0.46%   |
| 4.4.0   | 9        | 0.46%   |
| 5.12.4  | 8        | 0.41%   |
| 5.9.16  | 7        | 0.36%   |
| 5.4.32  | 6        | 0.31%   |
| 5.16.11 | 6        | 0.31%   |
| 5.15.15 | 6        | 0.31%   |
| 4.1.34  | 6        | 0.31%   |
| 5.9.1   | 5        | 0.26%   |
| 5.8.18  | 5        | 0.26%   |
| 5.7.0   | 5        | 0.26%   |
| 4.9.155 | 5        | 0.26%   |
| 4.9.124 | 5        | 0.26%   |
| 5.9.14  | 4        | 0.21%   |
| 5.9.0   | 4        | 0.21%   |
| 5.16.18 | 4        | 0.21%   |
| 5.16.0  | 4        | 0.21%   |
| 5.15.7  | 4        | 0.21%   |
| 5.13.19 | 4        | 0.21%   |
| 5.11.11 | 4        | 0.21%   |
| 5.10.13 | 4        | 0.21%   |
| 4.9.76  | 4        | 0.21%   |
| 4.9.111 | 4        | 0.21%   |
| 4.9.0   | 4        | 0.21%   |
| 5.8.7   | 3        | 0.15%   |
| 5.8.6   | 3        | 0.15%   |
| 5.8.5   | 3        | 0.15%   |
| 5.8.12  | 3        | 0.15%   |
| 5.6.12  | 3        | 0.15%   |
| 5.6.0   | 3        | 0.15%   |
| 5.15.32 | 3        | 0.15%   |
| 5.14.9  | 3        | 0.15%   |
| 5.13.4  | 3        | 0.15%   |
| 5.11.16 | 3        | 0.15%   |
| 4.9.95  | 3        | 0.15%   |
| 4.9.9   | 3        | 0.15%   |
| 4.13.0  | 3        | 0.15%   |
| 4.1.38  | 3        | 0.15%   |
| 5.9.8   | 2        | 0.1%    |
| 5.9.6   | 2        | 0.1%    |
| 5.9.3   | 2        | 0.1%    |
| 5.9.13  | 2        | 0.1%    |
| 5.9.12  | 2        | 0.1%    |
| 5.9.11  | 2        | 0.1%    |
| 5.9.10  | 2        | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 492      | 25.76%  |
| 4.15    | 203      | 10.63%  |
| 5.8     | 187      | 9.79%   |
| 5.3     | 145      | 7.59%   |
| 5.10    | 142      | 7.43%   |
| 5.11    | 130      | 6.81%   |
| 5.0     | 101      | 5.29%   |
| 4.18    | 81       | 4.24%   |
| 5.13    | 79       | 4.14%   |
| 5.16    | 65       | 3.4%    |
| 4.9     | 54       | 2.83%   |
| 5.15    | 38       | 1.99%   |
| 4.19    | 35       | 1.83%   |
| 5.9     | 33       | 1.73%   |
| 5.6     | 21       | 1.1%    |
| 5.12    | 20       | 1.05%   |
| 5.7     | 19       | 0.99%   |
| 5.14    | 13       | 0.68%   |
| 4.1     | 10       | 0.52%   |
| 5.17    | 9        | 0.47%   |
| 4.4     | 9        | 0.47%   |
| 5.5     | 8        | 0.42%   |
| 4.13    | 4        | 0.21%   |
| 5.1     | 2        | 0.1%    |
| 4.20    | 2        | 0.1%    |
| 5.2     | 1        | 0.05%   |
| 4.8     | 1        | 0.05%   |
| 4.7     | 1        | 0.05%   |
| 4.17    | 1        | 0.05%   |
| 4.14    | 1        | 0.05%   |
| 4.12    | 1        | 0.05%   |
| 3.14    | 1        | 0.05%   |
| 2.6.35  | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1641     | 94.26%  |
| i686   | 100      | 5.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 711      | 39.09%  |
| Unknown          | 341      | 18.75%  |
| KDE5             | 274      | 15.06%  |
| XFCE             | 140      | 7.7%    |
| X-Cinnamon       | 80       | 4.4%    |
| KDE              | 60       | 3.3%    |
| KDE4             | 57       | 3.13%   |
| MATE             | 48       | 2.64%   |
| LXQt             | 26       | 1.43%   |
| LXDE             | 19       | 1.04%   |
| Unity            | 15       | 0.82%   |
| Cinnamon         | 15       | 0.82%   |
| GNOME Flashback  | 8        | 0.44%   |
| Pantheon         | 6        | 0.33%   |
| GNOME Classic    | 6        | 0.33%   |
| Deepin           | 5        | 0.27%   |
| Budgie           | 3        | 0.16%   |
| Lubuntu          | 1        | 0.05%   |
| lightdm-xsession | 1        | 0.05%   |
| i3               | 1        | 0.05%   |
| herbstluftwm     | 1        | 0.05%   |
| FVWM             | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1468     | 82.56%  |
| Unknown | 178      | 10.01%  |
| Wayland | 108      | 6.07%   |
| Tty     | 24       | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1124     | 62.31%  |
| SDDM    | 269      | 14.91%  |
| GDM     | 129      | 7.15%   |
| GDM3    | 81       | 4.49%   |
| LightDM | 80       | 4.43%   |
| KDM     | 59       | 3.27%   |
| TDM     | 58       | 3.22%   |
| XDM     | 3        | 0.17%   |
| NODM    | 1        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| it_IT       | 1098     | 61.51%  |
| Unknown     | 378      | 21.18%  |
| en_US       | 237      | 13.28%  |
| en_GB       | 33       | 1.85%   |
| C           | 21       | 1.18%   |
| it_CH       | 3        | 0.17%   |
| de_DE       | 3        | 0.17%   |
| ru_RU       | 2        | 0.11%   |
| fr_FR       | 2        | 0.11%   |
| de_AT       | 2        | 0.11%   |
| POSIX       | 1        | 0.06%   |
| es_MX       | 1        | 0.06%   |
| es_ES       | 1        | 0.06%   |
| en_US.ASCII | 1        | 0.06%   |
| en_IE       | 1        | 0.06%   |
| de_IT       | 1        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1223     | 68.9%   |
| EFI  | 552      | 31.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1391     | 78.41%  |
| Overlay | 165      | 9.3%    |
| Unknown | 116      | 6.54%   |
| Btrfs   | 53       | 2.99%   |
| Xfs     | 22       | 1.24%   |
| Ext3    | 9        | 0.51%   |
| Zfs     | 7        | 0.39%   |
| Ext2    | 7        | 0.39%   |
| Tmpfs   | 3        | 0.17%   |
| Aufs    | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1189     | 67.25%  |
| GPT     | 341      | 19.29%  |
| MBR     | 238      | 13.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1420     | 79.6%   |
| Yes       | 364      | 20.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1059     | 59.46%  |
| Yes       | 722      | 40.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 566      | 32.55%  |
| ASRock              | 236      | 13.57%  |
| MSI                 | 181      | 10.41%  |
| Gigabyte Technology | 159      | 9.14%   |
| Hewlett-Packard     | 135      | 7.76%   |
| Dell                | 81       | 4.66%   |
| Acer                | 77       | 4.43%   |
| Lenovo              | 48       | 2.76%   |
| Intel               | 39       | 2.24%   |
| Pegatron            | 27       | 1.55%   |
| Packard Bell        | 22       | 1.27%   |
| Unknown             | 22       | 1.27%   |
| Fujitsu             | 20       | 1.15%   |
| Foxconn             | 17       | 0.98%   |
| Fujitsu Siemens     | 11       | 0.63%   |
| Supermicro          | 8        | 0.46%   |
| Biostar             | 7        | 0.4%    |
| ABIT                | 6        | 0.35%   |
| TYAN Computer       | 5        | 0.29%   |
| Sapphire            | 5        | 0.29%   |
| BESSTAR Tech        | 5        | 0.29%   |
| AMI                 | 5        | 0.29%   |
| Wistron             | 4        | 0.23%   |
| NEC Computers       | 4        | 0.23%   |
| IBM                 | 4        | 0.23%   |
| Apple               | 4        | 0.23%   |
| Gateway             | 3        | 0.17%   |
| ECS                 | 3        | 0.17%   |
| AZW                 | 3        | 0.17%   |
| Alienware           | 3        | 0.17%   |
| YANYU               | 2        | 0.12%   |
| Shuttle             | 2        | 0.12%   |
| PROLINE             | 2        | 0.12%   |
| LattePanda          | 2        | 0.12%   |
| eMachines           | 2        | 0.12%   |
| American Megatrends | 2        | 0.12%   |
| AAEON               | 2        | 0.12%   |
| ZOTAC               | 1        | 0.06%   |
| WINCOR NIXDORF      | 1        | 0.06%   |
| VIA Technologies    | 1        | 0.06%   |
| SYWZ                | 1        | 0.06%   |
| SiComputer          | 1        | 0.06%   |
| QDI                 | 1        | 0.06%   |
| Medion              | 1        | 0.06%   |
| IP3 Tech            | 1        | 0.06%   |
| Huanan              | 1        | 0.06%   |
| EVGA                | 1        | 0.06%   |
| Clientron Crop.     | 1        | 0.06%   |
| Clevo               | 1        | 0.06%   |
| Chuwi               | 1        | 0.06%   |
| AOpen               | 1        | 0.06%   |
| AMD                 | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 56       | 3.22%   |
| Unknown                            | 22       | 1.27%   |
| MSI MS-7B86                        | 10       | 0.58%   |
| Dell OptiPlex 7010                 | 10       | 0.58%   |
| ASUS PRIME A320M-K                 | 10       | 0.58%   |
| Supermicro H8DM8-2                 | 7        | 0.4%    |
| MSI MS-7C37                        | 7        | 0.4%    |
| ASUS P5KPL-SE                      | 7        | 0.4%    |
| HP Compaq Elite 8300 SFF           | 6        | 0.35%   |
| Gigabyte B450M DS3H                | 6        | 0.35%   |
| ASUS TUF GAMING X570-PLUS          | 6        | 0.35%   |
| MSI MS-7C56                        | 5        | 0.29%   |
| Dell OptiPlex 990                  | 5        | 0.29%   |
| Dell OptiPlex 760                  | 5        | 0.29%   |
| ASUS ROG STRIX B450-F GAMING       | 5        | 0.29%   |
| ASRock Q1900M                      | 5        | 0.29%   |
| ASRock N68C-S UCC                  | 5        | 0.29%   |
| ASRock G31M-GS                     | 5        | 0.29%   |
| ASRock B450M-HDV R4.0              | 5        | 0.29%   |
| MSI MS-7A32                        | 4        | 0.23%   |
| MSI MS-7996                        | 4        | 0.23%   |
| HP Pavilion Desktop TP01-0xxx      | 4        | 0.23%   |
| HP Compaq dc7800 Small Form Factor | 4        | 0.23%   |
| HP Compaq dc7600 Small Form Factor | 4        | 0.23%   |
| HP Compaq 6200 Pro SFF PC          | 4        | 0.23%   |
| Gigabyte X570 AORUS PRO            | 4        | 0.23%   |
| Gigabyte G31M-ES2L                 | 4        | 0.23%   |
| Dell Precision WorkStation T3500   | 4        | 0.23%   |
| Dell OptiPlex 780                  | 4        | 0.23%   |
| Dell OptiPlex 390                  | 4        | 0.23%   |
| Dell OptiPlex 3020                 | 4        | 0.23%   |
| ASUS P8H61-M LE                    | 4        | 0.23%   |
| ASUS P7H55-M                       | 4        | 0.23%   |
| ASUS P6T DELUXE V2                 | 4        | 0.23%   |
| ASUS P5G41T-M LX                   | 4        | 0.23%   |
| ASUS M5A97 LE R2.0                 | 4        | 0.23%   |
| ASUS M4A89GTD-PRO/USB3             | 4        | 0.23%   |
| ASUS M2A-MX                        | 4        | 0.23%   |
| ASUS CM6870                        | 4        | 0.23%   |
| ASRock H110M-HDV                   | 4        | 0.23%   |
| ASRock ConRoe1333-D667             | 4        | 0.23%   |
| Acer Aspire T180                   | 4        | 0.23%   |
| TYAN S3992-E                       | 3        | 0.17%   |
| MSI MS-7C84                        | 3        | 0.17%   |
| MSI MS-7C75                        | 3        | 0.17%   |
| MSI MS-7C52                        | 3        | 0.17%   |
| MSI MS-7B85                        | 3        | 0.17%   |
| MSI MS-7A70                        | 3        | 0.17%   |
| MSI MS-7A38                        | 3        | 0.17%   |
| MSI MS-7885                        | 3        | 0.17%   |
| MSI MS-7817                        | 3        | 0.17%   |
| MSI MS-7758                        | 3        | 0.17%   |
| MSI MS-7721                        | 3        | 0.17%   |
| MSI MS-7693                        | 3        | 0.17%   |
| MSI MS-7025                        | 3        | 0.17%   |
| MSI Compaq dx2200 MT               | 3        | 0.17%   |
| HP ProDesk 600 G1 SFF              | 3        | 0.17%   |
| HP Compaq Pro 6300 SFF             | 3        | 0.17%   |
| HP Compaq dc5800 Small Form Factor | 3        | 0.17%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 72       | 4.14%   |
| HP Compaq               | 63       | 3.62%   |
| ASUS All                | 56       | 3.22%   |
| Dell OptiPlex           | 49       | 2.82%   |
| Acer Aspire             | 45       | 2.59%   |
| Lenovo ThinkCentre      | 29       | 1.67%   |
| ASUS TUF                | 29       | 1.67%   |
| ASUS ROG                | 26       | 1.5%    |
| Acer Veriton            | 24       | 1.38%   |
| Unknown                 | 22       | 1.27%   |
| Fujitsu ESPRIMO         | 17       | 0.98%   |
| ASUS P8H61-M            | 16       | 0.92%   |
| Packard Bell iMedia     | 15       | 0.86%   |
| HP Pavilion             | 14       | 0.81%   |
| Dell Precision          | 14       | 0.81%   |
| HP EliteDesk            | 11       | 0.63%   |
| Gigabyte X570           | 11       | 0.63%   |
| MSI MS-7B86             | 10       | 0.58%   |
| ASUS P5Q                | 10       | 0.58%   |
| HP ProDesk              | 9        | 0.52%   |
| Gigabyte B450           | 9        | 0.52%   |
| ASUS P5KPL-AM           | 9        | 0.52%   |
| ASUS P5K                | 9        | 0.52%   |
| ASUS M5A97              | 9        | 0.52%   |
| Gigabyte B450M          | 8        | 0.46%   |
| ASUS P6T                | 8        | 0.46%   |
| Supermicro H8DM8-2      | 7        | 0.4%    |
| MSI MS-7C37             | 7        | 0.4%    |
| MSI Compaq              | 7        | 0.4%    |
| ASUS P8P67              | 7        | 0.4%    |
| ASUS P7H55-M            | 7        | 0.4%    |
| ASUS P5KPL-SE           | 7        | 0.4%    |
| ASUS P5G41T-M           | 7        | 0.4%    |
| ASUS M5A78L-M           | 7        | 0.4%    |
| Lenovo ThinkStation     | 6        | 0.35%   |
| Fujitsu Siemens ESPRIMO | 6        | 0.35%   |
| ASUS SABERTOOTH         | 6        | 0.35%   |
| ASUS Rampage            | 6        | 0.35%   |
| ASUS P8Z77-V            | 6        | 0.35%   |
| ASRock B450M-HDV        | 6        | 0.35%   |
| ASRock 970              | 6        | 0.35%   |
| MSI MS-7C56             | 5        | 0.29%   |
| Lenovo H50-50           | 5        | 0.29%   |
| Dell Vostro             | 5        | 0.29%   |
| ASUS P5QL               | 5        | 0.29%   |
| ASRock Q1900M           | 5        | 0.29%   |
| ASRock N68C-S           | 5        | 0.29%   |
| ASRock G31M-GS          | 5        | 0.29%   |
| Wistron ProLiant        | 4        | 0.23%   |
| Pegatron Pro            | 4        | 0.23%   |
| Packard Bell ixtreme    | 4        | 0.23%   |
| MSI MS-7A32             | 4        | 0.23%   |
| MSI MS-7996             | 4        | 0.23%   |
| Lenovo IdeaCentre       | 4        | 0.23%   |
| HP ProLiant             | 4        | 0.23%   |
| Gigabyte Z390           | 4        | 0.23%   |
| Gigabyte X470           | 4        | 0.23%   |
| Gigabyte H310M          | 4        | 0.23%   |
| Gigabyte G31M-ES2L      | 4        | 0.23%   |
| Dell Inspiron           | 4        | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2009    | 164      | 9.43%   |
| 2018    | 144      | 8.28%   |
| 2008    | 142      | 8.17%   |
| 2013    | 139      | 7.99%   |
| 2012    | 135      | 7.76%   |
| 2011    | 132      | 7.59%   |
| 2010    | 121      | 6.96%   |
| 2019    | 110      | 6.33%   |
| 2014    | 110      | 6.33%   |
| 2007    | 107      | 6.15%   |
| 2017    | 92       | 5.29%   |
| 2015    | 78       | 4.49%   |
| 2020    | 68       | 3.91%   |
| 2006    | 58       | 3.34%   |
| 2016    | 53       | 3.05%   |
| 2005    | 36       | 2.07%   |
| 2021    | 31       | 1.78%   |
| 2004    | 10       | 0.58%   |
| 2003    | 4        | 0.23%   |
| 2001    | 2        | 0.12%   |
| 2022    | 1        | 0.06%   |
| 2002    | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1739     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1703     | 97.82%  |
| Enabled  | 38       | 2.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1739     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 402      | 22.81%  |
| 8.01-16.0       | 389      | 22.08%  |
| 16.01-24.0      | 319      | 18.1%   |
| 4.01-8.0        | 274      | 15.55%  |
| 32.01-64.0      | 134      | 7.6%    |
| 1.01-2.0        | 122      | 6.92%   |
| 64.01-256.0     | 42       | 2.38%   |
| 2.01-3.0        | 32       | 1.82%   |
| 24.01-32.0      | 25       | 1.42%   |
| 0.51-1.0        | 19       | 1.08%   |
| More than 256.0 | 2        | 0.11%   |
| 0.01-0.5        | 2        | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 885      | 45.85%  |
| 2.01-3.0   | 403      | 20.88%  |
| 0.51-1.0   | 230      | 11.92%  |
| 3.01-4.0   | 169      | 8.76%   |
| 4.01-8.0   | 162      | 8.39%   |
| 8.01-16.0  | 39       | 2.02%   |
| 0.01-0.5   | 28       | 1.45%   |
| 16.01-24.0 | 8        | 0.41%   |
| 24.01-32.0 | 4        | 0.21%   |
| 32.01-64.0 | 1        | 0.05%   |
| Unknown    | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 709      | 39.08%  |
| 2       | 575      | 31.7%   |
| 3       | 266      | 14.66%  |
| 4       | 131      | 7.22%   |
| 5       | 59       | 3.25%   |
| 6       | 27       | 1.49%   |
| 0       | 22       | 1.21%   |
| 7       | 8        | 0.44%   |
| 8       | 7        | 0.39%   |
| 10      | 4        | 0.22%   |
| 9       | 3        | 0.17%   |
| 13      | 1        | 0.06%   |
| 12      | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1136     | 64.51%  |
| No        | 625      | 35.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1727     | 99.31%  |
| No        | 12       | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1049     | 59.67%  |
| Yes       | 709      | 40.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1403     | 79.22%  |
| Yes       | 368      | 20.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 1739     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Rome                | 232      | 11.79%  |
| Milan               | 215      | 10.93%  |
| Turin               | 72       | 3.66%   |
| Naples              | 48       | 2.44%   |
| Florence            | 47       | 2.39%   |
| Bologna             | 43       | 2.19%   |
| Genoa               | 33       | 1.68%   |
| Padova              | 24       | 1.22%   |
| Palermo             | 21       | 1.07%   |
| Verona              | 18       | 0.92%   |
| Pisa                | 17       | 0.86%   |
| Reggio Emilia       | 15       | 0.76%   |
| Cagliari            | 15       | 0.76%   |
| Rho                 | 14       | 0.71%   |
| Catania             | 14       | 0.71%   |
| Pescara             | 12       | 0.61%   |
| Modena              | 12       | 0.61%   |
| Vicenza             | 11       | 0.56%   |
| Perugia             | 11       | 0.56%   |
| Bari                | 11       | 0.56%   |
| Taranto             | 10       | 0.51%   |
| Venice              | 9        | 0.46%   |
| Trieste             | 9        | 0.46%   |
| Sesto San Giovanni  | 9        | 0.46%   |
| Pesaro              | 9        | 0.46%   |
| Monza               | 9        | 0.46%   |
| Bergamo             | 9        | 0.46%   |
| Udine               | 8        | 0.41%   |
| Trento              | 8        | 0.41%   |
| Brescia             | 8        | 0.41%   |
| Bolzano             | 7        | 0.36%   |
| Ravenna             | 6        | 0.31%   |
| Novara              | 6        | 0.31%   |
| Mestre              | 6        | 0.31%   |
| Lissone             | 6        | 0.31%   |
| La Spezia           | 6        | 0.31%   |
| Cosenza             | 6        | 0.31%   |
| Treviso             | 5        | 0.25%   |
| Rimini              | 5        | 0.25%   |
| Piacenza            | 5        | 0.25%   |
| Lecce               | 5        | 0.25%   |
| Desio               | 5        | 0.25%   |
| Dairago             | 5        | 0.25%   |
| Casalecchio di Reno | 5        | 0.25%   |
| Sassari             | 4        | 0.2%    |
| Salerno             | 4        | 0.2%    |
| Pordenone           | 4        | 0.2%    |
| Pistoia             | 4        | 0.2%    |
| Parma               | 4        | 0.2%    |
| Paese               | 4        | 0.2%    |
| Montebelluna        | 4        | 0.2%    |
| Lucca               | 4        | 0.2%    |
| Lecco               | 4        | 0.2%    |
| Imola               | 4        | 0.2%    |
| Ferrara             | 4        | 0.2%    |
| Fano                | 4        | 0.2%    |
| Cinisello Balsamo   | 4        | 0.2%    |
| Chieti              | 4        | 0.2%    |
| Chieri              | 4        | 0.2%    |
| Castel Maggiore     | 4        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 662      | 1116   | 22.07%  |
| WDC                       | 590      | 972    | 19.67%  |
| Samsung Electronics       | 407      | 624    | 13.57%  |
| Kingston                  | 220      | 319    | 7.34%   |
| MAXTOR                    | 149      | 209    | 4.97%   |
| Crucial                   | 147      | 204    | 4.9%    |
| Toshiba                   | 144      | 245    | 4.8%    |
| Hitachi                   | 122      | 168    | 4.07%   |
| SanDisk                   | 102      | 150    | 3.4%    |
| Unknown                   | 43       | 62     | 1.43%   |
| Phison                    | 34       | 45     | 1.13%   |
| Intel                     | 22       | 30     | 0.73%   |
| China                     | 21       | 24     | 0.7%    |
| Corsair                   | 20       | 26     | 0.67%   |
| Intenso                   | 18       | 22     | 0.6%    |
| HGST                      | 18       | 31     | 0.6%    |
| Micron/Crucial Technology | 17       | 21     | 0.57%   |
| SPCC                      | 16       | 20     | 0.53%   |
| Transcend                 | 14       | 20     | 0.47%   |
| PNY                       | 13       | 18     | 0.43%   |
| Micron Technology         | 13       | 14     | 0.43%   |
| A-DATA Technology         | 13       | 20     | 0.43%   |
| KingDian                  | 12       | 13     | 0.4%    |
| OCZ                       | 11       | 13     | 0.37%   |
| Patriot                   | 9        | 12     | 0.3%    |
| Fujitsu                   | 9        | 9      | 0.3%    |
| SK Hynix                  | 8        | 9      | 0.27%   |
| Drevo                     | 8        | 9      | 0.27%   |
| GOODRAM                   | 7        | 12     | 0.23%   |
| TCSUNBOW                  | 6        | 7      | 0.2%    |
| Silicon Motion            | 6        | 7      | 0.2%    |
| Jmicron                   | 5        | 5      | 0.17%   |
| ASMT                      | 5        | 5      | 0.17%   |
| XPG                       | 4        | 4      | 0.13%   |
| Team                      | 4        | 5      | 0.13%   |
| LaCie                     | 4        | 6      | 0.13%   |
| Gigabyte Technology       | 4        | 11     | 0.13%   |
| Dogfish                   | 4        | 7      | 0.13%   |
| Verbatim                  | 3        | 3      | 0.1%    |
| SABRENT                   | 3        | 3      | 0.1%    |
| Netac                     | 3        | 3      | 0.1%    |
| LITEONIT                  | 3        | 3      | 0.1%    |
| Lexar                     | 3        | 3      | 0.1%    |
| KIOXIA-EXCERIA            | 3        | 3      | 0.1%    |
| Inateck                   | 3        | 3      | 0.1%    |
| Apple                     | 3        | 3      | 0.1%    |
| USB                       | 2        | 2      | 0.07%   |
| S3+                       | 2        | 3      | 0.07%   |
| Reeinno                   | 2        | 2      | 0.07%   |
| PLEXTOR                   | 2        | 5      | 0.07%   |
| Marvell                   | 2        | 3      | 0.07%   |
| KingSpec                  | 2        | 3      | 0.07%   |
| HS-SSD-E100               | 2        | 2      | 0.07%   |
| External                  | 2        | 2      | 0.07%   |
| BAITITON                  | 2        | 2      | 0.07%   |
| AS25                      | 2        | 2      | 0.07%   |
| Apacer                    | 2        | 2      | 0.07%   |
| WD MediaMax               | 1        | 1      | 0.03%   |
| Vaseky                    | 1        | 1      | 0.03%   |
| USB3.0                    | 1        | 1      | 0.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 75       | 2.17%   |
| Kingston SA400S37240G 240GB SSD     | 58       | 1.68%   |
| Seagate ST1000DM010-2EP102 1TB      | 50       | 1.45%   |
| Samsung SSD 860 EVO 500GB           | 47       | 1.36%   |
| Toshiba DT01ACA100 1TB              | 43       | 1.24%   |
| Samsung SSD 850 EVO 250GB           | 40       | 1.16%   |
| Seagate ST3500418AS 500GB           | 37       | 1.07%   |
| Kingston SA400S37480G 480GB SSD     | 37       | 1.07%   |
| Samsung SSD 850 EVO 500GB           | 34       | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB      | 32       | 0.93%   |
| Crucial CT500MX500SSD1 500GB        | 32       | 0.93%   |
| Seagate ST31000528AS 1TB            | 28       | 0.81%   |
| Samsung SSD 860 EVO 250GB           | 26       | 0.75%   |
| Samsung NVMe SSD Drive 500GB        | 26       | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB            | 24       | 0.69%   |
| Seagate ST2000DM001-1ER164 2TB      | 24       | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 24       | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB      | 23       | 0.67%   |
| Samsung SSD 840 EVO 250GB           | 20       | 0.58%   |
| Crucial CT240BX500SSD1 240GB        | 20       | 0.58%   |
| Toshiba DT01ACA050 500GB            | 19       | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB      | 19       | 0.55%   |
| Kingston SV300S37A120G 120GB SSD    | 19       | 0.55%   |
| Seagate ST3500413AS 500GB           | 18       | 0.52%   |
| Seagate ST1000DM003-1SB10C 1TB      | 18       | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB      | 16       | 0.46%   |
| Seagate ST1000DM003-9YN162 1TB      | 16       | 0.46%   |
| SanDisk SSD PLUS 240GB              | 16       | 0.46%   |
| MAXTOR STM3250310AS 250GB           | 15       | 0.43%   |
| Crucial CT1000MX500SSD1 1TB         | 15       | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB            | 14       | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 14       | 0.41%   |
| Toshiba DT01ACA200 2TB              | 14       | 0.41%   |
| Seagate ST3250310AS 249GB           | 14       | 0.41%   |
| Seagate M3 Portable 4TB             | 14       | 0.41%   |
| Seagate Expansion+ 2TB              | 14       | 0.41%   |
| Samsung SSD 750 EVO 250GB           | 14       | 0.41%   |
| Samsung NVMe SSD Drive 1TB          | 14       | 0.41%   |
| MAXTOR 6Y080L0 82GB                 | 14       | 0.41%   |
| WDC WD20EFRX-68EUZN0 2TB            | 13       | 0.38%   |
| Seagate STM3500418AS 500GB          | 13       | 0.38%   |
| Samsung SSD 850 PRO 256GB           | 13       | 0.38%   |
| Samsung NVMe SSD Drive 250GB        | 13       | 0.38%   |
| MAXTOR STM3320820AS 320GB           | 13       | 0.38%   |
| Kingston SV300S37A240G 240GB SSD    | 13       | 0.38%   |
| Crucial CT120BX500SSD1 120GB        | 13       | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB         | 12       | 0.35%   |
| Seagate ST31000524AS 1TB            | 12       | 0.35%   |
| Samsung SSD 860 QVO 1TB             | 12       | 0.35%   |
| Hitachi HDP725050GLA360 500GB       | 12       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB            | 11       | 0.32%   |
| Toshiba HDWD110 1TB                 | 11       | 0.32%   |
| Seagate ST3160815AS 160GB           | 11       | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB      | 11       | 0.32%   |
| Seagate ST1000DM003-1SB102 1TB      | 11       | 0.32%   |
| Samsung SSD 860 EVO 1TB             | 11       | 0.32%   |
| Phison Sabrent 256GB                | 11       | 0.32%   |
| Micron/Crucial NVMe SSD Drive 500GB | 11       | 0.32%   |
| WDC WD20EZRX-00D8PB0 2TB            | 10       | 0.29%   |
| WDC WD10EZEX-60WN4A0 1TB            | 10       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 652      | 1092   | 37.43%  |
| WDC                 | 552      | 892    | 31.69%  |
| MAXTOR              | 149      | 209    | 8.55%   |
| Toshiba             | 125      | 215    | 7.18%   |
| Hitachi             | 122      | 168    | 7%      |
| Samsung Electronics | 72       | 93     | 4.13%   |
| Unknown             | 19       | 25     | 1.09%   |
| HGST                | 18       | 31     | 1.03%   |
| Fujitsu             | 9        | 9      | 0.52%   |
| SABRENT             | 3        | 3      | 0.17%   |
| ASMT                | 3        | 3      | 0.17%   |
| Inateck             | 2        | 2      | 0.11%   |
| Apple               | 2        | 2      | 0.11%   |
| WD MediaMax         | 1        | 1      | 0.06%   |
| USB3.0              | 1        | 1      | 0.06%   |
| USB 3.0             | 1        | 2      | 0.06%   |
| USB                 | 1        | 1      | 0.06%   |
| Promise             | 1        | 1      | 0.06%   |
| PI-041              | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 2      | 0.06%   |
| Intenso             | 1        | 3      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Hewlett-Packard     | 1        | 1      | 0.06%   |
| FC-1307             | 1        | 2      | 0.06%   |
| Config              | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 273      | 401    | 27.38%  |
| Kingston            | 212      | 305    | 21.26%  |
| Crucial             | 131      | 187    | 13.14%  |
| SanDisk             | 86       | 127    | 8.63%   |
| WDC                 | 44       | 66     | 4.41%   |
| China               | 21       | 24     | 2.11%   |
| Toshiba             | 20       | 28     | 2.01%   |
| Intenso             | 16       | 17     | 1.6%    |
| Corsair             | 16       | 21     | 1.6%    |
| SPCC                | 14       | 18     | 1.4%    |
| PNY                 | 13       | 18     | 1.3%    |
| Transcend           | 12       | 18     | 1.2%    |
| KingDian            | 12       | 13     | 1.2%    |
| Intel               | 11       | 18     | 1.1%    |
| A-DATA Technology   | 11       | 18     | 1.1%    |
| OCZ                 | 10       | 12     | 1%      |
| Patriot             | 9        | 12     | 0.9%    |
| Micron Technology   | 7        | 8      | 0.7%    |
| GOODRAM             | 7        | 12     | 0.7%    |
| TCSUNBOW            | 6        | 7      | 0.6%    |
| Team                | 4        | 5      | 0.4%    |
| Drevo               | 4        | 4      | 0.4%    |
| Dogfish             | 4        | 7      | 0.4%    |
| Verbatim            | 3        | 3      | 0.3%    |
| Unknown             | 3        | 4      | 0.3%    |
| LITEONIT            | 3        | 3      | 0.3%    |
| KIOXIA-EXCERIA      | 3        | 3      | 0.3%    |
| Gigabyte Technology | 3        | 10     | 0.3%    |
| S3+                 | 2        | 3      | 0.2%    |
| PLEXTOR             | 2        | 5      | 0.2%    |
| Netac               | 2        | 2      | 0.2%    |
| Lexar               | 2        | 2      | 0.2%    |
| KingSpec            | 2        | 3      | 0.2%    |
| JMicron             | 2        | 2      | 0.2%    |
| External            | 2        | 2      | 0.2%    |
| BAITITON            | 2        | 2      | 0.2%    |
| AS25                | 2        | 2      | 0.2%    |
| Apacer              | 2        | 2      | 0.2%    |
| Vaseky              | 1        | 1      | 0.1%    |
| TO Exter            | 1        | 1      | 0.1%    |
| Teclast             | 1        | 1      | 0.1%    |
| SK Hynix            | 1        | 1      | 0.1%    |
| Seagate             | 1        | 1      | 0.1%    |
| Reeinno             | 1        | 1      | 0.1%    |
| Qumox               | 1        | 1      | 0.1%    |
| LITEON              | 1        | 2      | 0.1%    |
| kimtigo             | 1        | 1      | 0.1%    |
| HS-SSD-E100         | 1        | 1      | 0.1%    |
| Hoodisk             | 1        | 2      | 0.1%    |
| GLOWAY              | 1        | 1      | 0.1%    |
| GBDriver            | 1        | 2      | 0.1%    |
| Foxline             | 1        | 1      | 0.1%    |
| EMTEC               | 1        | 1      | 0.1%    |
| CT250MX5            | 1        | 2      | 0.1%    |
| ASMT                | 1        | 1      | 0.1%    |
| Apple               | 1        | 1      | 0.1%    |
| Advantech           | 1        | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1331     | 2763   | 53.71%  |
| SSD     | 849      | 1417   | 34.26%  |
| NVMe    | 232      | 326    | 9.36%   |
| Unknown | 52       | 75     | 2.1%    |
| MMC     | 14       | 17     | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1644     | 4123   | 82.78%  |
| NVMe | 232      | 324    | 11.68%  |
| SAS  | 96       | 134    | 4.83%   |
| MMC  | 14       | 17     | 0.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1368     | 2586   | 59.58%  |
| 0.51-1.0   | 574      | 936    | 25%     |
| 1.01-2.0   | 197      | 357    | 8.58%   |
| 2.01-3.0   | 65       | 112    | 2.83%   |
| 3.01-4.0   | 60       | 112    | 2.61%   |
| 4.01-10.0  | 28       | 69     | 1.22%   |
| 10.01-20.0 | 4        | 8      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 461      | 24.64%  |
| 251-500        | 339      | 18.12%  |
| 501-1000       | 236      | 12.61%  |
| 1001-2000      | 187      | 9.99%   |
| 51-100         | 158      | 8.44%   |
| 1-20           | 144      | 7.7%    |
| More than 3000 | 124      | 6.63%   |
| 2001-3000      | 83       | 4.44%   |
| Unknown        | 73       | 3.9%    |
| 21-50          | 66       | 3.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 768      | 39.92%  |
| 21-50          | 269      | 13.98%  |
| 101-250        | 184      | 9.56%   |
| 51-100         | 177      | 9.2%    |
| 501-1000       | 141      | 7.33%   |
| 251-500        | 139      | 7.22%   |
| 1001-2000      | 88       | 4.57%   |
| Unknown        | 73       | 3.79%   |
| More than 3000 | 56       | 2.91%   |
| 2001-3000      | 29       | 1.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 10       | 12     | 5.03%   |
| Seagate ST3500418AS 500GB       | 8        | 12     | 4.02%   |
| Unknown MM0500EANCR 500GB       | 4        | 9      | 2.01%   |
| MAXTOR STM3320820AS 320GB       | 4        | 4      | 2.01%   |
| Seagate ST31500341AS 1TB        | 3        | 3      | 1.51%   |
| Seagate ST31000528AS 1TB        | 3        | 8      | 1.51%   |
| MAXTOR STM3250310AS 250GB       | 3        | 3      | 1.51%   |
| MAXTOR 6Y080L0 82GB             | 3        | 3      | 1.51%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 2        | 2      | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 3      | 1.01%   |
| WDC WD30EFRX-68EUZN0 3TB        | 2        | 2      | 1.01%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2        | 3      | 1.01%   |
| WDC WD1002FAEX-00Z3A0 1TB       | 2        | 2      | 1.01%   |
| Toshiba DT01ACA050 500GB        | 2        | 2      | 1.01%   |
| Seagate ST9500530NS 500GB       | 2        | 3      | 1.01%   |
| Seagate ST3500320AS 500GB       | 2        | 2      | 1.01%   |
| Seagate ST3250820AS 250GB       | 2        | 3      | 1.01%   |
| Seagate ST3250310AS 249GB       | 2        | 2      | 1.01%   |
| Seagate ST2000DM001-1ER164 2TB  | 2        | 6      | 1.01%   |
| MAXTOR STM3160815AS 160GB       | 2        | 2      | 1.01%   |
| Kingston SA400S37480G 480GB SSD | 2        | 2      | 1.01%   |
| Hitachi HTS725050A9A364 500GB   | 2        | 2      | 1.01%   |
| Hitachi HDS721010CLA332 1TB     | 2        | 2      | 1.01%   |
| WDC WD7501AAES-60Z2A0 752GB     | 1        | 1      | 0.5%    |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 1      | 0.5%    |
| WDC WD6400AAKS-22A7B0 640GB     | 1        | 1      | 0.5%    |
| WDC WD5001AALS-00L3B2 500GB     | 1        | 1      | 0.5%    |
| WDC WD5000LPVX-28V0TT1 500GB    | 1        | 2      | 0.5%    |
| WDC WD5000AAVS-00ZTB0 500GB     | 1        | 1      | 0.5%    |
| WDC WD5000AAKX-003CA0 500GB     | 1        | 1      | 0.5%    |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 2      | 0.5%    |
| WDC WD40PURZ-85TTDY0 4TB        | 1        | 1      | 0.5%    |
| WDC WD4003FZEX-00Z4SA0 4TB      | 1        | 2      | 0.5%    |
| WDC WD3200AAJS-65B4A0 320GB     | 1        | 1      | 0.5%    |
| WDC WD3200AAJS-60M0A1 320GB     | 1        | 1      | 0.5%    |
| WDC WD3200AAJS-56M0A0 320GB     | 1        | 1      | 0.5%    |
| WDC WD30EZRZ-00GXCB0 3TB        | 1        | 1      | 0.5%    |
| WDC WD2500BEVS-22UST0 250GB     | 1        | 1      | 0.5%    |
| WDC WD2500AVJS-63B6A0 250GB     | 1        | 1      | 0.5%    |
| WDC WD2500AAKS-00F0A0 250GB     | 1        | 1      | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 1      | 0.5%    |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 2      | 0.5%    |
| WDC WD20EVDS-63T3B0 2TB         | 1        | 1      | 0.5%    |
| WDC WD20EARS-60MVWB0 2TB        | 1        | 1      | 0.5%    |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 1      | 0.5%    |
| WDC WD2002FAEX-007BA0 2TB       | 1        | 1      | 0.5%    |
| WDC WD2000JS-00MHB0 200GB       | 1        | 1      | 0.5%    |
| WDC WD1600JD-00HBC0 160GB       | 1        | 1      | 0.5%    |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 1      | 0.5%    |
| WDC WD15EARS-00MVWB0 1TB        | 1        | 1      | 0.5%    |
| WDC WD10EZEX-22RKKA0 1TB        | 1        | 1      | 0.5%    |
| WDC WD10EAVS-00D7B1 1TB         | 1        | 1      | 0.5%    |
| WDC WD10EARS-22Y5B1 1TB         | 1        | 1      | 0.5%    |
| WDC WD10EARS-00Z5B1 1TB         | 1        | 1      | 0.5%    |
| WDC WD10EADX-22TDHB0 1TB        | 1        | 1      | 0.5%    |
| WDC WD10EADS-00M2B0 1TB         | 1        | 1      | 0.5%    |
| WDC WD1003FBYX-18Y7B0 1TB       | 1        | 1      | 0.5%    |
| WDC WD1003FBYX-01Y7B1 1TB       | 1        | 1      | 0.5%    |
| WDC WD1002FAEX-00Y9A0 1TB       | 1        | 1      | 0.5%    |
| Toshiba MK8037GSX 80GB          | 1        | 1      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 65       | 102    | 34.21%  |
| WDC                 | 44       | 52     | 23.16%  |
| MAXTOR              | 24       | 28     | 12.63%  |
| Hitachi             | 20       | 23     | 10.53%  |
| Samsung Electronics | 10       | 13     | 5.26%   |
| Kingston            | 9        | 9      | 4.74%   |
| Unknown             | 4        | 9      | 2.11%   |
| Toshiba             | 4        | 4      | 2.11%   |
| Crucial             | 2        | 2      | 1.05%   |
| SanDisk             | 1        | 1      | 0.53%   |
| Micron Technology   | 1        | 1      | 0.53%   |
| Intenso             | 1        | 1      | 0.53%   |
| HGST                | 1        | 2      | 0.53%   |
| Fujitsu             | 1        | 1      | 0.53%   |
| DREVO               | 1        | 1      | 0.53%   |
| Corsair             | 1        | 2      | 0.53%   |
| ASMT                | 1        | 1      | 0.53%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 65       | 102    | 38.01%  |
| WDC                 | 44       | 52     | 25.73%  |
| MAXTOR              | 24       | 28     | 14.04%  |
| Hitachi             | 20       | 23     | 11.7%   |
| Samsung Electronics | 7        | 8      | 4.09%   |
| Unknown             | 4        | 9      | 2.34%   |
| Toshiba             | 4        | 4      | 2.34%   |
| HGST                | 1        | 2      | 0.58%   |
| Fujitsu             | 1        | 1      | 0.58%   |
| ASMT                | 1        | 1      | 0.58%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 150      | 230    | 88.76%  |
| SSD  | 16       | 19     | 9.47%   |
| NVMe | 3        | 3      | 1.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate STM3250318AS 250GB      | 1        | 1      | 25%     |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 25%     |
| Hitachi HTS725050A7E630 500GB   | 1        | 1      | 25%     |
| Hitachi HTS543216L9A300 160GB   | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 50%     |
| Hitachi | 2        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1209     | 3101   | 63.77%  |
| Works    | 521      | 1241   | 27.48%  |
| Malfunc  | 162      | 252    | 8.54%   |
| Failed   | 4        | 4      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1154     | 50.24%  |
| AMD                              | 430      | 18.72%  |
| Nvidia                           | 102      | 4.44%   |
| JMicron Technology               | 102      | 4.44%   |
| Samsung Electronics              | 100      | 4.35%   |
| Marvell Technology Group         | 96       | 4.18%   |
| ASMedia Technology               | 69       | 3%      |
| Phison Electronics               | 41       | 1.78%   |
| VIA Technologies                 | 40       | 1.74%   |
| Micron/Crucial Technology        | 30       | 1.31%   |
| Sandisk                          | 24       | 1.04%   |
| Adaptec                          | 14       | 0.61%   |
| Kingston Technology Company      | 13       | 0.57%   |
| Silicon Motion                   | 11       | 0.48%   |
| Silicon Integrated Systems [SiS] | 8        | 0.35%   |
| Micron Technology                | 8        | 0.35%   |
| SK Hynix                         | 7        | 0.3%    |
| Silicon Image                    | 7        | 0.3%    |
| Broadcom / LSI                   | 7        | 0.3%    |
| ADATA Technology                 | 6        | 0.26%   |
| Toshiba America Info Systems     | 5        | 0.22%   |
| LSI Logic / Symbios Logic        | 5        | 0.22%   |
| Promise Technology               | 3        | 0.13%   |
| Broadcom                         | 3        | 0.13%   |
| ULi Electronics                  | 2        | 0.09%   |
| Integrated Technology Express    | 2        | 0.09%   |
| HighPoint Technologies           | 2        | 0.09%   |
| Unknown                          | 1        | 0.04%   |
| Seagate Technology               | 1        | 0.04%   |
| Realtek Semiconductor            | 1        | 0.04%   |
| OCZ Technology Group             | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| Initio                           | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 237      | 7.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 125      | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 118      | 3.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 103      | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 94       | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 88       | 2.83%   |
| AMD 400 Series Chipset SATA Controller                                                  | 83       | 2.67%   |
| Intel SATA Controller [RAID mode]                                                       | 75       | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 75       | 2.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 68       | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 67       | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 66       | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 64       | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 63       | 2.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 59       | 1.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 53       | 1.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 50       | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 43       | 1.38%   |
| Nvidia MCP61 SATA Controller                                                            | 41       | 1.32%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 41       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 1.32%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 39       | 1.25%   |
| Nvidia MCP61 IDE                                                                        | 34       | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 33       | 1.06%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 33       | 1.06%   |
| JMicron JMB368 IDE controller                                                           | 31       | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 28       | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 28       | 0.9%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 27       | 0.87%   |
| Phison E12 NVMe Controller                                                              | 27       | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 27       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 26       | 0.84%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 25       | 0.8%    |
| AMD FCH SATA Controller D                                                               | 20       | 0.64%   |
| AMD FCH IDE Controller                                                                  | 20       | 0.64%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 0.61%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 17       | 0.55%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 17       | 0.55%   |
| Samsung NVMe SSD Controller 980                                                         | 16       | 0.51%   |
| AMD X370 Series Chipset SATA Controller                                                 | 16       | 0.51%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 15       | 0.48%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 15       | 0.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 15       | 0.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15       | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 14       | 0.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14       | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 0.42%   |
| Nvidia MCP73 IDE Controller                                                             | 13       | 0.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13       | 0.42%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 13       | 0.42%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 13       | 0.42%   |
| AMD SB600 IDE                                                                           | 13       | 0.42%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 13       | 0.42%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 12       | 0.39%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 12       | 0.39%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 12       | 0.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 12       | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 12       | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1157     | 50.75%  |
| IDE  | 722      | 31.67%  |
| NVMe | 238      | 10.44%  |
| RAID | 148      | 6.49%   |
| SCSI | 9        | 0.39%   |
| SAS  | 6        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1221     | 70.21%  |
| AMD          | 517      | 29.73%  |
| CentaurHauls | 1        | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 29       | 1.66%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 29       | 1.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 23       | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor           | 23       | 1.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 22       | 1.26%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 22       | 1.26%   |
| Intel Pentium 4 CPU 3.00GHz                 | 20       | 1.15%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 1.09%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 18       | 1.03%   |
| AMD FX-8350 Eight-Core Processor            | 18       | 1.03%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 17       | 0.97%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 16       | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 16       | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 14       | 0.8%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 14       | 0.8%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 13       | 0.74%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 13       | 0.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 13       | 0.74%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 12       | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 12       | 0.69%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 12       | 0.69%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 11       | 0.63%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 11       | 0.63%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 11       | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 11       | 0.63%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 11       | 0.63%   |
| AMD Six-Core Opteron Processor 8435         | 11       | 0.63%   |
| Intel Pentium 4 CPU 3.20GHz                 | 10       | 0.57%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 10       | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 10       | 0.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 0.57%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10       | 0.57%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 10       | 0.57%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 10       | 0.57%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 10       | 0.57%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 10       | 0.57%   |
| AMD Athlon II X4 640 Processor              | 10       | 0.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 9        | 0.52%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 9        | 0.52%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 9        | 0.52%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 9        | 0.52%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 9        | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 9        | 0.52%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 0.52%   |
| AMD Phenom II X4 955 Processor              | 9        | 0.52%   |
| AMD FX-8320 Eight-Core Processor            | 9        | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 9        | 0.52%   |
| Intel Pentium D CPU 3.40GHz                 | 8        | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8        | 0.46%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 8        | 0.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8        | 0.46%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.46%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 8        | 0.46%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 8        | 0.46%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 8        | 0.46%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 8        | 0.46%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 8        | 0.46%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 8        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 302      | 17.31%  |
| Intel Core i7           | 209      | 11.98%  |
| Intel Core i3           | 125      | 7.16%   |
| Intel Core 2 Duo        | 88       | 5.04%   |
| Intel Core 2 Quad       | 85       | 4.87%   |
| AMD Ryzen 5             | 83       | 4.76%   |
| AMD Ryzen 7             | 65       | 3.72%   |
| Intel Pentium Dual-Core | 64       | 3.67%   |
| Intel Celeron           | 63       | 3.61%   |
| Intel Xeon              | 61       | 3.5%    |
| Intel Pentium 4         | 53       | 3.04%   |
| Intel Pentium           | 50       | 2.87%   |
| AMD FX                  | 48       | 2.75%   |
| AMD Athlon 64 X2        | 41       | 2.35%   |
| Intel Core 2            | 32       | 1.83%   |
| AMD Ryzen 9             | 25       | 1.43%   |
| Intel Pentium Dual      | 22       | 1.26%   |
| AMD Ryzen 3             | 22       | 1.26%   |
| AMD Phenom II X4        | 22       | 1.26%   |
| AMD A8                  | 22       | 1.26%   |
| Intel Pentium D         | 20       | 1.15%   |
| Intel Atom              | 20       | 1.15%   |
| AMD Sempron             | 17       | 0.97%   |
| AMD Phenom II X6        | 17       | 0.97%   |
| AMD Athlon II X2        | 15       | 0.86%   |
| Intel Core i9           | 14       | 0.8%    |
| AMD Athlon II X4        | 14       | 0.8%    |
| Other                   | 13       | 0.74%   |
| AMD Phenom              | 13       | 0.74%   |
| AMD A10                 | 13       | 0.74%   |
| AMD Six-Core Opteron    | 11       | 0.63%   |
| AMD Athlon 64           | 11       | 0.63%   |
| AMD Athlon              | 10       | 0.57%   |
| AMD A6                  | 10       | 0.57%   |
| AMD A4                  | 10       | 0.57%   |
| AMD Athlon II X3        | 9        | 0.52%   |
| AMD Athlon X4           | 6        | 0.34%   |
| AMD Ryzen Threadripper  | 5        | 0.29%   |
| AMD Quad-Core Opteron   | 4        | 0.23%   |
| AMD Phenom II X2        | 3        | 0.17%   |
| AMD E                   | 3        | 0.17%   |
| AMD Ryzen 5 PRO         | 2        | 0.11%   |
| AMD Opteron             | 2        | 0.11%   |
| AMD E1                  | 2        | 0.11%   |
| AMD Athlon Dual Core    | 2        | 0.11%   |
| Intel Xeon Bronze       | 1        | 0.06%   |
| Intel Pentium Silver    | 1        | 0.06%   |
| Intel Pentium Gold      | 1        | 0.06%   |
| Intel Genuine           | 1        | 0.06%   |
| Intel Core m5           | 1        | 0.06%   |
| Intel Core m3           | 1        | 0.06%   |
| CentaurHauls VIA Eden   | 1        | 0.06%   |
| AMD Turion II Neo       | 1        | 0.06%   |
| AMD Ryzen 7 PRO         | 1        | 0.06%   |
| AMD Phenom II X3        | 1        | 0.06%   |
| AMD GX                  | 1        | 0.06%   |
| AMD G                   | 1        | 0.06%   |
| AMD E2                  | 1        | 0.06%   |
| AMD Athlon XP           | 1        | 0.06%   |
| AMD Athlon X2           | 1        | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 704      | 40.39%  |
| 2       | 559      | 32.07%  |
| 6       | 170      | 9.75%   |
| 8       | 114      | 6.54%   |
| 1       | 111      | 6.37%   |
| 12      | 30       | 1.72%   |
| 3       | 26       | 1.49%   |
| 16      | 12       | 0.69%   |
| 10      | 11       | 0.63%   |
| 24      | 3        | 0.17%   |
| 64      | 1        | 0.06%   |
| 5       | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1707     | 98.16%  |
| 2      | 32       | 1.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1020     | 58.55%  |
| 2       | 721      | 41.39%  |
| Unknown | 1        | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1700     | 97.42%  |
| Unknown        | 25       | 1.43%   |
| 32-bit         | 20       | 1.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 341      | 18.93%  |
| 0x306c3    | 143      | 7.94%   |
| 0x1067a    | 124      | 6.89%   |
| 0x206a7    | 113      | 6.27%   |
| 0x306a9    | 84       | 4.66%   |
| 0x506e3    | 50       | 2.78%   |
| 0x6fb      | 49       | 2.72%   |
| 0x906e9    | 47       | 2.61%   |
| 0x08701021 | 45       | 2.5%    |
| 0x906ea    | 35       | 1.94%   |
| 0x010000c8 | 31       | 1.72%   |
| 0x6fd      | 29       | 1.61%   |
| 0x0800820d | 29       | 1.61%   |
| 0x06000852 | 26       | 1.44%   |
| 0x6f6      | 24       | 1.33%   |
| 0x10676    | 22       | 1.22%   |
| 0x106e5    | 21       | 1.17%   |
| 0x106a5    | 19       | 1.05%   |
| 0x08701013 | 19       | 1.05%   |
| 0x06001119 | 19       | 1.05%   |
| 0x906ed    | 18       | 1%      |
| 0x20655    | 18       | 1%      |
| 0x10677    | 17       | 0.94%   |
| 0x20652    | 15       | 0.83%   |
| 0x08108109 | 14       | 0.78%   |
| 0xf49      | 13       | 0.72%   |
| 0xf43      | 13       | 0.72%   |
| 0xa0655    | 13       | 0.72%   |
| 0x03000027 | 13       | 0.72%   |
| 0x010000dc | 13       | 0.72%   |
| 0x30678    | 12       | 0.67%   |
| 0x08001138 | 12       | 0.67%   |
| 0x06003106 | 12       | 0.67%   |
| 0x306f2    | 11       | 0.61%   |
| 0x01000083 | 11       | 0.61%   |
| 0xf41      | 10       | 0.56%   |
| 0x706a1    | 10       | 0.56%   |
| 0x6f2      | 10       | 0.56%   |
| 0x0a50000c | 10       | 0.56%   |
| 0xf64      | 9        | 0.5%    |
| 0xa0653    | 9        | 0.5%    |
| 0x906eb    | 9        | 0.5%    |
| 0x0a201016 | 9        | 0.5%    |
| 0x08101016 | 9        | 0.5%    |
| 0xf65      | 8        | 0.44%   |
| 0xa0671    | 8        | 0.44%   |
| 0x406c4    | 8        | 0.44%   |
| 0x0810100b | 8        | 0.44%   |
| 0x406c3    | 7        | 0.39%   |
| 0x206d7    | 7        | 0.39%   |
| 0x206c2    | 7        | 0.39%   |
| 0x010000db | 7        | 0.39%   |
| 0x010000da | 7        | 0.39%   |
| 0x906ec    | 6        | 0.33%   |
| 0x506c9    | 6        | 0.33%   |
| 0x0a201009 | 6        | 0.33%   |
| 0x08001137 | 6        | 0.33%   |
| 0x010000c7 | 6        | 0.33%   |
| 0xf29      | 5        | 0.28%   |
| 0x306e4    | 5        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 183      | 10.49%  |
| Haswell          | 177      | 10.15%  |
| KabyLake         | 143      | 8.2%    |
| SandyBridge      | 142      | 8.14%   |
| Core             | 125      | 7.17%   |
| K10              | 117      | 6.71%   |
| IvyBridge        | 100      | 5.73%   |
| NetBurst         | 79       | 4.53%   |
| Zen 2            | 75       | 4.3%    |
| Skylake          | 66       | 3.78%   |
| K8 Hammer        | 66       | 3.78%   |
| Piledriver       | 61       | 3.5%    |
| Zen+             | 55       | 3.15%   |
| Nehalem          | 51       | 2.92%   |
| Zen              | 49       | 2.81%   |
| Westmere         | 49       | 2.81%   |
| Silvermont       | 35       | 2.01%   |
| CometLake        | 30       | 1.72%   |
| Zen 3            | 29       | 1.66%   |
| K10 Llano        | 16       | 0.92%   |
| Steamroller      | 15       | 0.86%   |
| Goldmont plus    | 13       | 0.75%   |
| Excavator        | 12       | 0.69%   |
| Bonnell          | 11       | 0.63%   |
| Goldmont         | 9        | 0.52%   |
| Bulldozer        | 8        | 0.46%   |
| Jaguar           | 6        | 0.34%   |
| Icelake          | 6        | 0.34%   |
| Bobcat           | 5        | 0.29%   |
| Puma             | 4        | 0.23%   |
| Unknown          | 4        | 0.23%   |
| K6               | 1        | 0.06%   |
| Broadwell        | 1        | 0.06%   |
| Alderlake Hybrid | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 751      | 41.49%  |
| AMD                                          | 542      | 29.94%  |
| Intel                                        | 490      | 27.07%  |
| VIA Technologies                             | 9        | 0.5%    |
| Matrox Electronics Systems                   | 7        | 0.39%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.28%   |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.17%   |
| ASPEED Technology                            | 3        | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 65       | 3.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 65       | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 59       | 3.18%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 50       | 2.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 49       | 2.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 48       | 2.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 40       | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 36       | 1.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 28       | 1.51%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 24       | 1.29%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 24       | 1.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 24       | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 23       | 1.24%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 22       | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 21       | 1.13%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 20       | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 19       | 1.02%   |
| Intel HD Graphics 530                                                                    | 19       | 1.02%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 19       | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 17       | 0.91%   |
| Intel HD Graphics 630                                                                    | 17       | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17       | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17       | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17       | 0.91%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 16       | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 16       | 0.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 16       | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15       | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14       | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14       | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 14       | 0.75%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 13       | 0.7%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 13       | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13       | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 12       | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 12       | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12       | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 11       | 0.59%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 11       | 0.59%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 11       | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 10       | 0.54%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 10       | 0.54%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 10       | 0.54%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 10       | 0.54%   |
| AMD ES1000                                                                               | 10       | 0.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 9        | 0.48%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 9        | 0.48%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 9        | 0.48%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 9        | 0.48%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 9        | 0.48%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 9        | 0.48%   |
| AMD Cezanne                                                                              | 9        | 0.48%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 8        | 0.43%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 8        | 0.43%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 8        | 0.43%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 8        | 0.43%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 8        | 0.43%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 8        | 0.43%   |
| Intel HD Graphics 500                                                                    | 8        | 0.43%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 8        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 724      | 41.32%  |
| 1 x AMD              | 488      | 27.85%  |
| 1 x Intel            | 445      | 25.4%   |
| 2 x AMD              | 36       | 2.05%   |
| Intel + Nvidia       | 14       | 0.8%    |
| 1 x VIA              | 9        | 0.51%   |
| AMD + Nvidia         | 9        | 0.51%   |
| 1 x SiS              | 5        | 0.29%   |
| Intel + AMD          | 5        | 0.29%   |
| 1 x XGI              | 3        | 0.17%   |
| Nvidia + Matrox      | 3        | 0.17%   |
| 1 x Matrox           | 3        | 0.17%   |
| 1 x ASPEED           | 3        | 0.17%   |
| Other                | 1        | 0.06%   |
| 2 x Nvidia           | 1        | 0.06%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.06%   |
| Intel + 2 x AMD      | 1        | 0.06%   |
| AMD + Matrox         | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1345     | 75.43%  |
| Proprietary | 375      | 21.03%  |
| Unknown     | 63       | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 631      | 35.08%  |
| 0.01-0.5   | 303      | 16.84%  |
| 1.01-2.0   | 289      | 16.06%  |
| 0.51-1.0   | 275      | 15.29%  |
| 3.01-4.0   | 126      | 7%      |
| 7.01-8.0   | 81       | 4.5%    |
| 5.01-6.0   | 56       | 3.11%   |
| 2.01-3.0   | 24       | 1.33%   |
| 8.01-16.0  | 12       | 0.67%   |
| 4.01-5.0   | 1        | 0.06%   |
| 16.01-24.0 | 1        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 363      | 20.8%   |
| Philips                 | 174      | 9.97%   |
| Hewlett-Packard         | 172      | 9.86%   |
| Goldstar                | 157      | 9%      |
| Ancor Communications    | 157      | 9%      |
| Acer                    | 128      | 7.34%   |
| Dell                    | 84       | 4.81%   |
| BenQ                    | 73       | 4.18%   |
| AOC                     | 66       | 3.78%   |
| Unknown                 | 30       | 1.72%   |
| HannStar                | 30       | 1.72%   |
| LG Electronics          | 29       | 1.66%   |
| Sony                    | 22       | 1.26%   |
| Lenovo                  | 22       | 1.26%   |
| Fujitsu Siemens         | 15       | 0.86%   |
| ASUSTek Computer        | 13       | 0.74%   |
| Eizo                    | 12       | 0.69%   |
| Packard Bell            | 9        | 0.52%   |
| Belinea                 | 8        | 0.46%   |
| Sharp                   | 7        | 0.4%    |
| Vestel Elektronik       | 6        | 0.34%   |
| NEC Computers           | 6        | 0.34%   |
| HPN                     | 6        | 0.34%   |
| CVT                     | 6        | 0.34%   |
| OEM                     | 5        | 0.29%   |
| MSI                     | 5        | 0.29%   |
| Lenovo Group Limited    | 5        | 0.29%   |
| Chi Mei Optoelectronics | 5        | 0.29%   |
| Panasonic               | 4        | 0.23%   |
| MiTAC                   | 4        | 0.23%   |
| Microstep               | 4        | 0.23%   |
| Hyundai ImageQuest      | 4        | 0.23%   |
| HannStar Display        | 4        | 0.23%   |
| FUS                     | 4        | 0.23%   |
| Compaq Computer         | 4        | 0.23%   |
| Arnos Instruments       | 4        | 0.23%   |
| ViewSonic               | 3        | 0.17%   |
| Vestel                  | 3        | 0.17%   |
| RTK                     | 3        | 0.17%   |
| QBell                   | 3        | 0.17%   |
| Plain Tree Systems      | 3        | 0.17%   |
| PKB                     | 3        | 0.17%   |
| Iiyama                  | 3        | 0.17%   |
| IBM                     | 3        | 0.17%   |
| GDH                     | 3        | 0.17%   |
| AU Optronics            | 3        | 0.17%   |
| Targa Visionary         | 2        | 0.11%   |
| MStar                   | 2        | 0.11%   |
| Mi                      | 2        | 0.11%   |
| Impression              | 2        | 0.11%   |
| HKC                     | 2        | 0.11%   |
| Hitachi                 | 2        | 0.11%   |
| Hannspree               | 2        | 0.11%   |
| Grundig                 | 2        | 0.11%   |
| EXP                     | 2        | 0.11%   |
| Daewoo                  | 2        | 0.11%   |
| CHR                     | 2        | 0.11%   |
| CHI                     | 2        | 0.11%   |
| AUS                     | 2        | 0.11%   |
| Apple                   | 2        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 11       | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 10       | 0.54%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 9        | 0.49%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 8        | 0.43%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 8        | 0.43%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 8        | 0.43%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 7        | 0.38%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 7        | 0.38%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch     | 7        | 0.38%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch  | 6        | 0.32%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 6        | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 0.32%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6        | 0.32%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 6        | 0.32%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 6        | 0.32%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 6        | 0.32%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 5        | 0.27%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 5        | 0.27%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 5        | 0.27%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 5        | 0.27%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 5        | 0.27%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 5        | 0.27%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 5        | 0.27%   |
| Hewlett-Packard 27fw HPN354B 1920x1080 598x336mm 27.0-inch            | 5        | 0.27%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch             | 5        | 0.27%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 5        | 0.27%   |
| Goldstar M2280D GSM57B9 1920x1080 480x270mm 21.7-inch                 | 5        | 0.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 5        | 0.27%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 5        | 0.27%   |
| Dell 2009W DEL4042 1680x1050 433x271mm 20.1-inch                      | 5        | 0.27%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 5        | 0.27%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 5        | 0.27%   |
| Ancor Communications ASUS VX279 ACI27E4 1920x1080 598x336mm 27.0-inch | 5        | 0.27%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch | 5        | 0.27%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 5        | 0.27%   |
| Samsung Electronics SAMTRON STN0021 1280x1024 338x270mm 17.0-inch     | 4        | 0.22%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 0.22%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch     | 4        | 0.22%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch | 4        | 0.22%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 4        | 0.22%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch     | 4        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4        | 0.22%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 4        | 0.22%   |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch            | 4        | 0.22%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 4        | 0.22%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                   | 4        | 0.22%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 4        | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4        | 0.22%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 4        | 0.22%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch        | 4        | 0.22%   |
| Ancor Communications VW225 ACI22A0 1680x1050 473x296mm 22.0-inch      | 4        | 0.22%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 4        | 0.22%   |
| Ancor Communications ASUS VW221 ACI22A8 1680x1050 473x296mm 22.0-inch | 4        | 0.22%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 4        | 0.22%   |
| Unknown LCD Monitor TV@ PHILCO 1280x720                               | 3        | 0.16%   |
| Sony LCD Monitor TV 1920x1080                                         | 3        | 0.16%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.16%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3        | 0.16%   |
| Samsung Electronics T22E390 SAM0C1E 1920x1080 477x268mm 21.5-inch     | 3        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 812      | 47.07%  |
| 1280x1024 (SXGA)   | 216      | 12.52%  |
| 1680x1050 (WSXGA+) | 120      | 6.96%   |
| 1440x900 (WXGA+)   | 117      | 6.78%   |
| 3840x2160 (4K)     | 88       | 5.1%    |
| 2560x1440 (QHD)    | 63       | 3.65%   |
| 1366x768 (WXGA)    | 43       | 2.49%   |
| Unknown            | 43       | 2.49%   |
| 1360x768           | 40       | 2.32%   |
| 1600x900 (HD+)     | 27       | 1.57%   |
| 1920x1200 (WUXGA)  | 26       | 1.51%   |
| 1024x768 (XGA)     | 26       | 1.51%   |
| 3840x1080          | 17       | 0.99%   |
| 2560x1080          | 14       | 0.81%   |
| 1600x1200          | 12       | 0.7%    |
| 3440x1440          | 8        | 0.46%   |
| 1920x540           | 6        | 0.35%   |
| 1280x720 (HD)      | 6        | 0.35%   |
| 3200x1080          | 3        | 0.17%   |
| 2560x1600          | 3        | 0.17%   |
| 8960x2160          | 2        | 0.12%   |
| 5120x1440          | 2        | 0.12%   |
| 4480x1440          | 2        | 0.12%   |
| 2640x1024          | 2        | 0.12%   |
| 2304x1024          | 2        | 0.12%   |
| 2288x1287          | 2        | 0.12%   |
| 1818x1022          | 2        | 0.12%   |
| 1280x768           | 2        | 0.12%   |
| 6784x2160          | 1        | 0.06%   |
| 5760x2160          | 1        | 0.06%   |
| 5760x1080          | 1        | 0.06%   |
| 5520x2160          | 1        | 0.06%   |
| 4480x1080          | 1        | 0.06%   |
| 3968x1152          | 1        | 0.06%   |
| 3840x1920          | 1        | 0.06%   |
| 3840x1200          | 1        | 0.06%   |
| 3360x1080          | 1        | 0.06%   |
| 3040x900           | 1        | 0.06%   |
| 2944x1080          | 1        | 0.06%   |
| 2800x900           | 1        | 0.06%   |
| 2390x768           | 1        | 0.06%   |
| 2160x1200          | 1        | 0.06%   |
| 2080x1024          | 1        | 0.06%   |
| 1920x1440          | 1        | 0.06%   |
| 1800x1440          | 1        | 0.06%   |
| 1400x1050          | 1        | 0.06%   |
| 1280x800 (WXGA)    | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 250      | 14.32%  |
| 21      | 227      | 13%     |
| 27      | 210      | 12.03%  |
| 24      | 198      | 11.34%  |
| 19      | 182      | 10.42%  |
| 23      | 159      | 9.11%   |
| 17      | 101      | 5.78%   |
| 18      | 85       | 4.87%   |
| 22      | 66       | 3.78%   |
| 20      | 58       | 3.32%   |
| 15      | 36       | 2.06%   |
| 31      | 31       | 1.78%   |
| 34      | 24       | 1.37%   |
| 84      | 17       | 0.97%   |
| 54      | 16       | 0.92%   |
| 32      | 11       | 0.63%   |
| 40      | 10       | 0.57%   |
| 25      | 8        | 0.46%   |
| 72      | 7        | 0.4%    |
| 42      | 5        | 0.29%   |
| 28      | 5        | 0.29%   |
| 48      | 4        | 0.23%   |
| 47      | 4        | 0.23%   |
| 60      | 3        | 0.17%   |
| 52      | 3        | 0.17%   |
| 39      | 3        | 0.17%   |
| 33      | 3        | 0.17%   |
| 142     | 2        | 0.11%   |
| 50      | 2        | 0.11%   |
| 43      | 2        | 0.11%   |
| 37      | 2        | 0.11%   |
| 16      | 2        | 0.11%   |
| 14      | 2        | 0.11%   |
| 74      | 1        | 0.06%   |
| 65      | 1        | 0.06%   |
| 57      | 1        | 0.06%   |
| 55      | 1        | 0.06%   |
| 46      | 1        | 0.06%   |
| 30      | 1        | 0.06%   |
| 26      | 1        | 0.06%   |
| 12      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 527      | 30.78%  |
| 401-500        | 508      | 29.67%  |
| Unknown        | 250      | 14.6%   |
| 301-350        | 132      | 7.71%   |
| 351-400        | 117      | 6.83%   |
| 601-700        | 54       | 3.15%   |
| 701-800        | 37       | 2.16%   |
| 1001-1500      | 36       | 2.1%    |
| 1501-2000      | 25       | 1.46%   |
| 801-900        | 16       | 0.93%   |
| 901-1000       | 6        | 0.35%   |
| More than 2000 | 2        | 0.12%   |
| 201-300        | 2        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 919      | 54.6%   |
| 16/10   | 253      | 15.03%  |
| Unknown | 220      | 13.07%  |
| 5/4     | 202      | 12%     |
| 4/3     | 47       | 2.79%   |
| 21/9    | 21       | 1.25%   |
| 6/5     | 8        | 0.48%   |
| 3/2     | 8        | 0.48%   |
| 32/9    | 3        | 0.18%   |
| 1.00    | 2        | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 518      | 30.01%  |
| 151-200        | 345      | 19.99%  |
| Unknown        | 250      | 14.48%  |
| 301-350        | 210      | 12.17%  |
| 141-150        | 141      | 8.17%   |
| 351-500        | 69       | 4%      |
| 251-300        | 63       | 3.65%   |
| More than 1000 | 56       | 3.24%   |
| 101-110        | 33       | 1.91%   |
| 501-1000       | 32       | 1.85%   |
| 131-140        | 4        | 0.23%   |
| 91-100         | 2        | 0.12%   |
| 81-90          | 1        | 0.06%   |
| 71-80          | 1        | 0.06%   |
| 111-120        | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1049     | 62.14%  |
| 101-120 | 281      | 16.65%  |
| Unknown | 250      | 14.81%  |
| 1-50    | 54       | 3.2%    |
| 121-160 | 34       | 2.01%   |
| 161-240 | 20       | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1508     | 85.58%  |
| 2     | 165      | 9.36%   |
| 0     | 73       | 4.14%   |
| 3     | 16       | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1028     | 41.98%  |
| Intel                                 | 575      | 23.48%  |
| Qualcomm Atheros                      | 174      | 7.1%    |
| Nvidia                                | 82       | 3.35%   |
| Broadcom                              | 78       | 3.18%   |
| Ralink Technology                     | 66       | 2.69%   |
| TP-Link                               | 53       | 2.16%   |
| Marvell Technology Group              | 51       | 2.08%   |
| Ralink                                | 32       | 1.31%   |
| Qualcomm Atheros Communications       | 31       | 1.27%   |
| Broadcom Limited                      | 30       | 1.22%   |
| D-Link System                         | 26       | 1.06%   |
| VIA Technologies                      | 24       | 0.98%   |
| Huawei Technologies                   | 20       | 0.82%   |
| D-Link                                | 20       | 0.82%   |
| Sitecom Europe                        | 16       | 0.65%   |
| NetGear                               | 15       | 0.61%   |
| ASUSTek Computer                      | 13       | 0.53%   |
| Samsung Electronics                   | 12       | 0.49%   |
| Xiaomi                                | 11       | 0.45%   |
| MediaTek                              | 7        | 0.29%   |
| Belkin Components                     | 7        | 0.29%   |
| Aquantia                              | 7        | 0.29%   |
| Silicon Integrated Systems [SiS]      | 6        | 0.24%   |
| Microsoft                             | 6        | 0.24%   |
| Gemtek                                | 6        | 0.24%   |
| 3Com                                  | 5        | 0.2%    |
| Linksys                               | 4        | 0.16%   |
| DisplayLink                           | 4        | 0.16%   |
| ASIX Electronics                      | 4        | 0.16%   |
| OPPO Electronics                      | 3        | 0.12%   |
| Motorola                              | 3        | 0.12%   |
| ZTE WCDMA Technologies MSM            | 2        | 0.08%   |
| Smart Link                            | 2        | 0.08%   |
| Microchip Technology                  | 2        | 0.08%   |
| Exar                                  | 2        | 0.08%   |
| AVM                                   | 2        | 0.08%   |
| ZyDAS                                 | 1        | 0.04%   |
| Uniden                                | 1        | 0.04%   |
| ULi Electronics                       | 1        | 0.04%   |
| U.S. Robotics                         | 1        | 0.04%   |
| U-Blox                                | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.04%   |
| STMicroelectronics                    | 1        | 0.04%   |
| Qualcomm                              | 1        | 0.04%   |
| OnePlus                               | 1        | 0.04%   |
| Motorola PCS                          | 1        | 0.04%   |
| LSI                                   | 1        | 0.04%   |
| LG Electronics                        | 1        | 0.04%   |
| JMicron Technology                    | 1        | 0.04%   |
| HMD Global                            | 1        | 0.04%   |
| Fiberline                             | 1        | 0.04%   |
| Dresden Elektronik                    | 1        | 0.04%   |
| Compal Electronics                    | 1        | 0.04%   |
| AMD                                   | 1        | 0.04%   |
| AboCom Systems                        | 1        | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 817      | 30.21%  |
| Intel Ethernet Connection (2) I219-V                                       | 73       | 2.7%    |
| Intel I211 Gigabit Network Connection                                      | 70       | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 64       | 2.37%   |
| Intel 82579V Gigabit Network Connection                                    | 43       | 1.59%   |
| Intel Wi-Fi 6 AX200                                                        | 40       | 1.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 37       | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 36       | 1.33%   |
| Nvidia MCP61 Ethernet                                                      | 33       | 1.22%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 31       | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                            | 30       | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                          | 29       | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 26       | 0.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 26       | 0.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 26       | 0.96%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 25       | 0.92%   |
| Intel Ethernet Connection I217-LM                                          | 24       | 0.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 21       | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 21       | 0.78%   |
| Intel Ethernet Controller I225-V                                           | 21       | 0.78%   |
| Intel Ethernet Connection I217-V                                           | 21       | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 20       | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                       | 20       | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 18       | 0.67%   |
| Realtek 802.11ac NIC                                                       | 18       | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 18       | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 17       | 0.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 16       | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 16       | 0.59%   |
| Ralink MT7601U Wireless Adapter                                            | 16       | 0.59%   |
| Intel Ethernet Connection (2) I218-V                                       | 15       | 0.55%   |
| Intel Wireless-AC 9260                                                     | 14       | 0.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 14       | 0.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 13       | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 13       | 0.48%   |
| Nvidia MCP73 Ethernet                                                      | 13       | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 13       | 0.48%   |
| Intel 82578DC Gigabit Network Connection                                   | 13       | 0.48%   |
| Ralink RT5370 Wireless Adapter                                             | 12       | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 11       | 0.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 11       | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 11       | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 11       | 0.41%   |
| Nvidia MCP77 Ethernet                                                      | 11       | 0.41%   |
| Intel 82578DM Gigabit Network Connection                                   | 11       | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 11       | 0.41%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                      | 10       | 0.37%   |
| TP-Link 802.11ac WLAN Adapter                                              | 10       | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 10       | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 10       | 0.37%   |
| Intel Wireless 7260                                                        | 10       | 0.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 9        | 0.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 9        | 0.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 9        | 0.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 9        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 9        | 0.33%   |
| Intel Wireless 7265                                                        | 9        | 0.33%   |
| Intel NM10/ICH7 Family LAN Controller                                      | 9        | 0.33%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 9        | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 8        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 212      | 28.01%  |
| Intel                                 | 129      | 17.04%  |
| Qualcomm Atheros                      | 88       | 11.62%  |
| Ralink Technology                     | 66       | 8.72%   |
| TP-Link                               | 52       | 6.87%   |
| Ralink                                | 32       | 4.23%   |
| Qualcomm Atheros Communications       | 31       | 4.1%    |
| Broadcom                              | 30       | 3.96%   |
| D-Link                                | 20       | 2.64%   |
| D-Link System                         | 19       | 2.51%   |
| Sitecom Europe                        | 16       | 2.11%   |
| NetGear                               | 15       | 1.98%   |
| ASUSTek Computer                      | 12       | 1.59%   |
| Belkin Components                     | 7        | 0.92%   |
| Gemtek                                | 6        | 0.79%   |
| Microsoft                             | 5        | 0.66%   |
| Broadcom Limited                      | 5        | 0.66%   |
| Linksys                               | 4        | 0.53%   |
| AVM                                   | 2        | 0.26%   |
| ZyDAS                                 | 1        | 0.13%   |
| Samsung Electronics                   | 1        | 0.13%   |
| MediaTek                              | 1        | 0.13%   |
| Fiberline                             | 1        | 0.13%   |
| AboCom Systems                        | 1        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 40       | 5.23%   |
| Qualcomm Atheros AR9271 802.11n                                               | 30       | 3.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 26       | 3.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 21       | 2.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 20       | 2.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 18       | 2.35%   |
| Realtek 802.11ac NIC                                                          | 18       | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 17       | 2.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 16       | 2.09%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 16       | 2.09%   |
| Ralink MT7601U Wireless Adapter                                               | 16       | 2.09%   |
| Intel Wireless-AC 9260                                                        | 14       | 1.83%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 14       | 1.83%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 13       | 1.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 13       | 1.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 13       | 1.7%    |
| Ralink RT5370 Wireless Adapter                                                | 12       | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 11       | 1.44%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                         | 10       | 1.31%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 10       | 1.31%   |
| Intel Wireless 7260                                                           | 10       | 1.31%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 9        | 1.18%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 9        | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 9        | 1.18%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 9        | 1.18%   |
| Intel Wireless 7265                                                           | 9        | 1.18%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 9        | 1.18%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 8        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8        | 1.05%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 8        | 1.05%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 7        | 0.92%   |
| Realtek RTL8187 Wireless Adapter                                              | 7        | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 7        | 0.92%   |
| Intel Wireless 3165                                                           | 7        | 0.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 7        | 0.92%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]            | 7        | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 6        | 0.78%   |
| Ralink RT5572 Wireless Adapter                                                | 6        | 0.78%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 6        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 6        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 6        | 0.78%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                             | 6        | 0.78%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 6        | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 5        | 0.65%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 5        | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5        | 0.65%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]                        | 5        | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 5        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 5        | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4        | 0.52%   |
| Sitecom Europe RTL8188S WLAN Adapter                                          | 4        | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 4        | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.52%   |
| Realtek RTL8192SE Wireless LAN Controller                                     | 4        | 0.52%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                   | 4        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 4        | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 4        | 0.52%   |
| Ralink RT3072 Wireless Adapter                                                | 4        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 946      | 50.48%  |
| Intel                             | 504      | 26.89%  |
| Qualcomm Atheros                  | 100      | 5.34%   |
| Nvidia                            | 82       | 4.38%   |
| Marvell Technology Group          | 51       | 2.72%   |
| Broadcom                          | 50       | 2.67%   |
| Broadcom Limited                  | 25       | 1.33%   |
| VIA Technologies                  | 23       | 1.23%   |
| Huawei Technologies               | 18       | 0.96%   |
| Xiaomi                            | 11       | 0.59%   |
| Samsung Electronics               | 11       | 0.59%   |
| D-Link System                     | 7        | 0.37%   |
| Aquantia                          | 7        | 0.37%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.32%   |
| MediaTek                          | 6        | 0.32%   |
| 3Com                              | 5        | 0.27%   |
| DisplayLink                       | 4        | 0.21%   |
| ASIX Electronics                  | 4        | 0.21%   |
| OPPO Electronics                  | 3        | 0.16%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.11%   |
| ULi Electronics                   | 1        | 0.05%   |
| TP-Link                           | 1        | 0.05%   |
| Sundance Technology Inc / IC Plus | 1        | 0.05%   |
| Qualcomm                          | 1        | 0.05%   |
| Motorola PCS                      | 1        | 0.05%   |
| LG Electronics                    | 1        | 0.05%   |
| JMicron Technology                | 1        | 0.05%   |
| HMD Global                        | 1        | 0.05%   |
| ASUSTek Computer                  | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 817      | 42.66%  |
| Intel Ethernet Connection (2) I219-V                              | 73       | 3.81%   |
| Intel I211 Gigabit Network Connection                             | 70       | 3.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64       | 3.34%   |
| Intel 82579V Gigabit Network Connection                           | 43       | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37       | 1.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36       | 1.88%   |
| Nvidia MCP61 Ethernet                                             | 33       | 1.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 31       | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29       | 1.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 26       | 1.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26       | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25       | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 24       | 1.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 21       | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 21       | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 21       | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 20       | 1.04%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 18       | 0.94%   |
| Intel Ethernet Connection (2) I218-V                              | 15       | 0.78%   |
| Nvidia MCP73 Ethernet                                             | 13       | 0.68%   |
| Intel 82578DC Gigabit Network Connection                          | 13       | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11       | 0.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 11       | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 0.57%   |
| Nvidia MCP77 Ethernet                                             | 11       | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 11       | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10       | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.47%   |
| Intel NM10/ICH7 Family LAN Controller                             | 9        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8        | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 8        | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 8        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.42%   |
| Intel 82567V-2 Gigabit Network Connection                         | 8        | 0.42%   |
| Nvidia MCP51 Ethernet Controller                                  | 7        | 0.37%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 7        | 0.37%   |
| Huawei JNY-LX1                                                    | 7        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.37%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 7        | 0.37%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 7        | 0.37%   |
| Intel 82566DM Gigabit Network Connection                          | 6        | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 6        | 0.31%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 6        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5        | 0.26%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 5        | 0.26%   |
| Intel Ethernet Connection (5) I219-LM                             | 5        | 0.26%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 5        | 0.26%   |
| Huawei E353/E3131                                                 | 5        | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5        | 0.26%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.26%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4        | 0.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.21%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.21%   |
| Nvidia MCP79 Ethernet                                             | 4        | 0.21%   |
| MediaTek NOA N2                                                   | 4        | 0.21%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 4        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1726     | 70.25%  |
| WiFi     | 707      | 28.77%  |
| Modem    | 21       | 0.85%   |
| Unknown  | 3        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1428     | 74.3%   |
| WiFi     | 493      | 25.65%  |
| Unknown  | 1        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1241     | 70.91%  |
| 2     | 442      | 25.26%  |
| 3     | 51       | 2.91%   |
| 0     | 10       | 0.57%   |
| 4     | 3        | 0.17%   |
| 12    | 1        | 0.06%   |
| 6     | 1        | 0.06%   |
| 5     | 1        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1691     | 96.85%  |
| Yes  | 55       | 3.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 124      | 33.07%  |
| Intel                           | 112      | 29.87%  |
| Realtek Semiconductor           | 31       | 8.27%   |
| Broadcom                        | 31       | 8.27%   |
| ASUSTek Computer                | 27       | 7.2%    |
| Qualcomm Atheros Communications | 14       | 3.73%   |
| IMC Networks                    | 9        | 2.4%    |
| Integrated System Solution      | 7        | 1.87%   |
| Apple                           | 7        | 1.87%   |
| Belkin Components               | 3        | 0.8%    |
| Lite-On Technology              | 2        | 0.53%   |
| Sitecom Europe                  | 1        | 0.27%   |
| Logitech                        | 1        | 0.27%   |
| HTC (High Tech Computer)        | 1        | 0.27%   |
| Hewlett-Packard                 | 1        | 0.27%   |
| Fujitsu Siemens Computers       | 1        | 0.27%   |
| Foxconn / Hon Hai               | 1        | 0.27%   |
| Dell                            | 1        | 0.27%   |
| Conwise Technology              | 1        | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 124      | 32.98%  |
| Intel AX200 Bluetooth                                                | 36       | 9.57%   |
| Intel Bluetooth wireless interface                                   | 29       | 7.71%   |
| Realtek Bluetooth Radio                                              | 16       | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14       | 3.72%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 13       | 3.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 12       | 3.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 12       | 3.19%   |
| Intel AX201 Bluetooth                                                | 11       | 2.93%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 10       | 2.66%   |
| Broadcom BCM2045 Bluetooth                                           | 10       | 2.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9        | 2.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 7        | 1.86%   |
| IMC Networks Bluetooth Device                                        | 5        | 1.33%   |
| ASUS Bluetooth Radio                                                 | 5        | 1.33%   |
| ASUS BCM20702A0                                                      | 5        | 1.33%   |
| Intel AX210 Bluetooth                                                | 4        | 1.06%   |
| Integrated System Solution Bluetooth Device                          | 4        | 1.06%   |
| Apple Bluetooth USB Host Controller                                  | 4        | 1.06%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 3        | 0.8%    |
| IMC Networks Bluetooth Radio                                         | 3        | 0.8%    |
| Broadcom BCM2035 Bluetooth dongle                                    | 3        | 0.8%    |
| ASUS Qualcomm Bluetooth 4.1                                          | 3        | 0.8%    |
| ASUS Bluetooth Adapter                                               | 3        | 0.8%    |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 0.53%   |
| Lite-On Bluetooth Device                                             | 2        | 0.53%   |
| Belkin Components F8T012 Bluetooth Adapter                           | 2        | 0.53%   |
| Apple Bluetooth HCI                                                  | 2        | 0.53%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521            | 1        | 0.27%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1        | 0.27%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.27%   |
| IMC Networks BCM20702A0                                              | 1        | 0.27%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1        | 0.27%   |
| Fujitsu Siemens Computers Bluetooth Device                           | 1        | 0.27%   |
| Foxconn / Hon Hai Acer Bluetooth module                              | 1        | 0.27%   |
| Dell BCM20702A0 Bluetooth Module                                     | 1        | 0.27%   |
| Conwise CW6622                                                       | 1        | 0.27%   |
| Broadcom Bluetooth dongle                                            | 1        | 0.27%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.27%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.27%   |
| Broadcom BCM92046DG-CL1ROM                                           | 1        | 0.27%   |
| Broadcom BCM92045B3 ROM                                              | 1        | 0.27%   |
| Broadcom ANYCOM Blue USB-200/250                                     | 1        | 0.27%   |
| Belkin Components Bluetooth Device with trace filter                 | 1        | 0.27%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.27%   |
| ASUS Bluetooth Device                                                | 1        | 0.27%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1123     | 40.69%  |
| Nvidia                               | 664      | 24.06%  |
| AMD                                  | 641      | 23.22%  |
| C-Media Electronics                  | 74       | 2.68%   |
| Creative Labs                        | 34       | 1.23%   |
| VIA Technologies                     | 28       | 1.01%   |
| Logitech                             | 18       | 0.65%   |
| M-Audio                              | 10       | 0.36%   |
| Creative Technology                  | 10       | 0.36%   |
| Silicon Integrated Systems [SiS]     | 8        | 0.29%   |
| JMTek                                | 8        | 0.29%   |
| Texas Instruments                    | 7        | 0.25%   |
| Razer USA                            | 7        | 0.25%   |
| Focusrite-Novation                   | 7        | 0.25%   |
| Tenx Technology                      | 6        | 0.22%   |
| Ensoniq                              | 6        | 0.22%   |
| ASUSTek Computer                     | 6        | 0.22%   |
| Microsoft                            | 5        | 0.18%   |
| Generalplus Technology               | 5        | 0.18%   |
| BEHRINGER International              | 5        | 0.18%   |
| Thesycon Systemsoftware & Consulting | 4        | 0.14%   |
| Plantronics                          | 4        | 0.14%   |
| Micro Star International             | 4        | 0.14%   |
| Kingston Technology                  | 4        | 0.14%   |
| Dell                                 | 4        | 0.14%   |
| XMOS                                 | 3        | 0.11%   |
| Trust                                | 3        | 0.11%   |
| Sennheiser Communications            | 3        | 0.11%   |
| SAVITECH                             | 3        | 0.11%   |
| GN Netcom                            | 3        | 0.11%   |
| Corsair                              | 3        | 0.11%   |
| ZOOM                                 | 2        | 0.07%   |
| Yamaha                               | 2        | 0.07%   |
| ULi Electronics                      | 2        | 0.07%   |
| Studiologic                          | 2        | 0.07%   |
| Samson Technologies                  | 2        | 0.07%   |
| RODE Microphones                     | 2        | 0.07%   |
| Bose                                 | 2        | 0.07%   |
| Astro Gaming                         | 2        | 0.07%   |
| Xilinx                               | 1        | 0.04%   |
| Veho                                 | 1        | 0.04%   |
| Unknown                              | 1        | 0.04%   |
| TerraTec Electronic                  | 1        | 0.04%   |
| Tdlasunnic                           | 1        | 0.04%   |
| Sony                                 | 1        | 0.04%   |
| Roland                               | 1        | 0.04%   |
| Realtek Semiconductor                | 1        | 0.04%   |
| PreSonus Audio Electronics           | 1        | 0.04%   |
| No brand                             | 1        | 0.04%   |
| Microdia                             | 1        | 0.04%   |
| Megawin Technology                   | 1        | 0.04%   |
| MAG Technology                       | 1        | 0.04%   |
| iSoft Silicon                        | 1        | 0.04%   |
| Giga-Byte Technology                 | 1        | 0.04%   |
| Fnatic Gear                          | 1        | 0.04%   |
| FiiO Electronics Technology          | 1        | 0.04%   |
| EasyPass Industrial                  | 1        | 0.04%   |
| Cooler Master                        | 1        | 0.04%   |
| Conrad Electronic SE                 | 1        | 0.04%   |
| Casio Computer                       | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 135      | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 133      | 4.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 133      | 4.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 124      | 3.99%   |
| AMD Starship/Matisse HD Audio Controller                                          | 89       | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 85       | 2.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 80       | 2.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 77       | 2.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 75       | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 74       | 2.38%   |
| Nvidia High Definition Audio Controller                                           | 71       | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 71       | 2.29%   |
| Intel 200 Series PCH HD Audio                                                     | 69       | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 67       | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 65       | 2.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 63       | 2.03%   |
| AMD FCH Azalia Controller                                                         | 62       | 2%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 51       | 1.64%   |
| AMD Family 17h/19h HD Audio Controller                                            | 50       | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                        | 48       | 1.54%   |
| Nvidia GF108 High Definition Audio Controller                                     | 44       | 1.42%   |
| Nvidia MCP61 High Definition Audio                                                | 39       | 1.26%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 39       | 1.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 39       | 1.26%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 39       | 1.26%   |
| Nvidia GF119 HDMI Audio Controller                                                | 38       | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                                     | 36       | 1.16%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 34       | 1.09%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 33       | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 32       | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 31       | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 29       | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 28       | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 27       | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                | 25       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                                     | 21       | 0.68%   |
| AMD Navi 10 HDMI Audio                                                            | 21       | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 19       | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                                     | 18       | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                                     | 18       | 0.58%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 17       | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 16       | 0.51%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 16       | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                                | 15       | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                                | 15       | 0.48%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 14       | 0.45%   |
| Nvidia MCP73 High Definition Audio                                                | 14       | 0.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 14       | 0.45%   |
| Intel Comet Lake PCH cAVS                                                         | 13       | 0.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 13       | 0.42%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 13       | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                 | 13       | 0.42%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 12       | 0.39%   |
| Nvidia GM204 High Definition Audio Controller                                     | 12       | 0.39%   |
| Nvidia GF106 High Definition Audio Controller                                     | 12       | 0.39%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 12       | 0.39%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 12       | 0.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12       | 0.39%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 11       | 0.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 11       | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 177      | 21.56%  |
| Kingston                     | 163      | 19.85%  |
| Corsair                      | 110      | 13.4%   |
| Crucial                      | 75       | 9.14%   |
| Samsung Electronics          | 68       | 8.28%   |
| SK Hynix                     | 56       | 6.82%   |
| G.Skill                      | 39       | 4.75%   |
| Micron Technology            | 35       | 4.26%   |
| A-DATA Technology            | 14       | 1.71%   |
| Team                         | 11       | 1.34%   |
| Patriot                      | 11       | 1.34%   |
| Nanya Technology             | 9        | 1.1%    |
| Elpida                       | 8        | 0.97%   |
| Unknown (ABCD)               | 6        | 0.73%   |
| Ramaxel Technology           | 6        | 0.73%   |
| Unifosa                      | 5        | 0.61%   |
| Transcend                    | 5        | 0.61%   |
| Qimonda                      | 2        | 0.24%   |
| PLEXHD                       | 2        | 0.24%   |
| Hewlett-Packard              | 2        | 0.24%   |
| A Force                      | 2        | 0.24%   |
| Unknown                      | 2        | 0.24%   |
| Unknown (AB)                 | 1        | 0.12%   |
| TwinMOS                      | 1        | 0.12%   |
| Toshiba                      | 1        | 0.12%   |
| Thermaltake                  | 1        | 0.12%   |
| Silicon Power                | 1        | 0.12%   |
| PUSKILL                      | 1        | 0.12%   |
| Patriot Memory (PDP Systems) | 1        | 0.12%   |
| KomputerBay                  | 1        | 0.12%   |
| Kingmax                      | 1        | 0.12%   |
| GOODRAM                      | 1        | 0.12%   |
| GeIL                         | 1        | 0.12%   |
| CSX                          | 1        | 0.12%   |
| ASint Technology             | 1        | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                  | 13       | 1.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s        | 13       | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 12       | 1.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 10       | 1.08%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 10       | 1.08%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 9        | 0.97%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s         | 7        | 0.76%   |
| Unknown RAM Module 512MB DIMM SDRAM                          | 6        | 0.65%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 6        | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 6        | 0.65%   |
| Unknown RAM Module 1024MB DIMM                               | 6        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 6        | 0.65%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 6        | 0.65%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s       | 6        | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 5        | 0.54%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 5        | 0.54%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 5        | 0.54%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 5        | 0.54%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s         | 5        | 0.54%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s        | 5        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 4        | 0.43%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 4        | 0.43%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 4        | 0.43%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 4        | 0.43%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 1639MT/s      | 4        | 0.43%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s         | 4        | 0.43%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s          | 4        | 0.43%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 4        | 0.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 4        | 0.43%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s       | 4        | 0.43%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 4        | 0.43%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s       | 4        | 0.43%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s       | 4        | 0.43%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s          | 4        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 4        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 3        | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                  | 3        | 0.32%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 3        | 0.32%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                       | 3        | 0.32%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 3        | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 3        | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 3        | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 3        | 0.32%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 3        | 0.32%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s           | 3        | 0.32%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 3        | 0.32%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                 | 3        | 0.32%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 3        | 0.32%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s          | 3        | 0.32%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s                  | 3        | 0.32%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                 | 3        | 0.32%   |
| Kingston RAM KHX2666C15D4/4G 4096MB DIMM DDR4 3200MT/s       | 3        | 0.32%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s          | 3        | 0.32%   |
| Kingston RAM KHX1866C10D3/ 4GB DIMM DDR3 1866MT/s            | 3        | 0.32%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 3        | 0.32%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s     | 3        | 0.32%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s        | 3        | 0.32%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s          | 3        | 0.32%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 3        | 0.32%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s         | 3        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 265      | 35.38%  |
| DDR4    | 261      | 34.85%  |
| DDR2    | 96       | 12.82%  |
| SDRAM   | 55       | 7.34%   |
| Unknown | 48       | 6.41%   |
| DDR     | 15       | 2%      |
| LPDDR4  | 7        | 0.93%   |
| LPDDR3  | 2        | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 694      | 95.86%  |
| SODIMM  | 28       | 3.87%   |
| FB-DIMM | 2        | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 253      | 31.04%  |
| 4096  | 197      | 24.17%  |
| 2048  | 180      | 22.09%  |
| 16384 | 77       | 9.45%   |
| 1024  | 69       | 8.47%   |
| 512   | 17       | 2.09%   |
| 32768 | 16       | 1.96%   |
| 256   | 4        | 0.49%   |
| 3072  | 1        | 0.12%   |
| 32    | 1        | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 142      | 17.66%  |
| 1333    | 99       | 12.31%  |
| 3200    | 58       | 7.21%   |
| 800     | 55       | 6.84%   |
| 2400    | 45       | 5.6%    |
| 3600    | 42       | 5.22%   |
| 2667    | 37       | 4.6%    |
| Unknown | 35       | 4.35%   |
| 667     | 33       | 4.1%    |
| 2133    | 27       | 3.36%   |
| 1867    | 21       | 2.61%   |
| 3466    | 16       | 1.99%   |
| 3000    | 16       | 1.99%   |
| 2933    | 16       | 1.99%   |
| 266     | 14       | 1.74%   |
| 1866    | 13       | 1.62%   |
| 1066    | 12       | 1.49%   |
| 400     | 11       | 1.37%   |
| 1800    | 10       | 1.24%   |
| 3533    | 8        | 1%      |
| 2666    | 8        | 1%      |
| 1334    | 7        | 0.87%   |
| 333     | 7        | 0.87%   |
| 3400    | 6        | 0.75%   |
| 533     | 6        | 0.75%   |
| 2000    | 5        | 0.62%   |
| 49926   | 4        | 0.5%    |
| 3733    | 4        | 0.5%    |
| 2048    | 4        | 0.5%    |
| 1639    | 4        | 0.5%    |
| 1067    | 4        | 0.5%    |
| 3333    | 3        | 0.37%   |
| 2800    | 3        | 0.37%   |
| 1400    | 3        | 0.37%   |
| 3800    | 2        | 0.25%   |
| 3334    | 2        | 0.25%   |
| 3151    | 2        | 0.25%   |
| 3100    | 2        | 0.25%   |
| 2733    | 2        | 0.25%   |
| 52217   | 1        | 0.12%   |
| 52028   | 1        | 0.12%   |
| 4800    | 1        | 0.12%   |
| 4200    | 1        | 0.12%   |
| 4133    | 1        | 0.12%   |
| 4000    | 1        | 0.12%   |
| 3866    | 1        | 0.12%   |
| 3266    | 1        | 0.12%   |
| 3066    | 1        | 0.12%   |
| 3007    | 1        | 0.12%   |
| 2747    | 1        | 0.12%   |
| 2176    | 1        | 0.12%   |
| 2134    | 1        | 0.12%   |
| 1648    | 1        | 0.12%   |
| 1332    | 1        | 0.12%   |
| 200     | 1        | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 63       | 41.72%  |
| Samsung Electronics   | 24       | 15.89%  |
| Canon                 | 18       | 11.92%  |
| Brother Industries    | 17       | 11.26%  |
| Seiko Epson           | 16       | 10.6%   |
| Lexmark International | 3        | 1.99%   |
| Xerox                 | 2        | 1.32%   |
| Prolific Technology   | 2        | 1.32%   |
| Oki Data              | 2        | 1.32%   |
| Sato                  | 1        | 0.66%   |
| Ricoh                 | 1        | 0.66%   |
| QinHeng Electronics   | 1        | 0.66%   |
| Pantum                | 1        | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2510 Series                                            | 6        | 3.97%   |
| Samsung M2020 Series                                                  | 6        | 3.97%   |
| HP OfficeJet 6950                                                     | 6        | 3.97%   |
| HP LaserJet 1018                                                      | 4        | 2.65%   |
| HP ENVY 4520 series                                                   | 4        | 2.65%   |
| Canon PIXMA MG3600 Series                                             | 4        | 2.65%   |
| Seiko Epson Printer                                                   | 3        | 1.99%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 3        | 1.99%   |
| Samsung ML-216x Series Laser Printer                                  | 3        | 1.99%   |
| Samsung M267x 287x Series                                             | 3        | 1.99%   |
| Samsung Composite Device                                              | 3        | 1.99%   |
| HP LaserJet Professional P 1102w                                      | 3        | 1.99%   |
| HP LaserJet P1005                                                     | 3        | 1.99%   |
| HP Deskjet F4500 series                                               | 3        | 1.99%   |
| HP Deskjet 2050 J510                                                  | 3        | 1.99%   |
| Brother DCP-1610W                                                     | 3        | 1.99%   |
| Samsung ML-1660 Series                                                | 2        | 1.32%   |
| Prolific PL2305 Parallel Port                                         | 2        | 1.32%   |
| Oki Data USB Device                                                   | 2        | 1.32%   |
| Lexmark International InkJet Color Printer                            | 2        | 1.32%   |
| HP OfficeJet 5200 series                                              | 2        | 1.32%   |
| HP Officejet 2620 series                                              | 2        | 1.32%   |
| HP LaserJet P1102                                                     | 2        | 1.32%   |
| HP DeskJet F4200 series                                               | 2        | 1.32%   |
| HP Deskjet 3050A                                                      | 2        | 1.32%   |
| HP DeskJet 2130 series                                                | 2        | 1.32%   |
| Canon PIXMA MX920 Series                                              | 2        | 1.32%   |
| Canon LiDE 400                                                        | 2        | 1.32%   |
| Canon CanoScan LiDE 300                                               | 2        | 1.32%   |
| Brother MFC-L2700DW                                                   | 2        | 1.32%   |
| Brother DCP-1510                                                      | 2        | 1.32%   |
| Xerox Phaser 6121MFP Scan                                             | 1        | 0.66%   |
| Xerox Phaser 6010N                                                    | 1        | 0.66%   |
| Seiko Epson WF-3520 Series                                            | 1        | 0.66%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F                | 1        | 0.66%   |
| Seiko Epson L4150 Series                                              | 1        | 0.66%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One]            | 1        | 0.66%   |
| Sato CG408                                                            | 1        | 0.66%   |
| Samsung SCX-4623 Series                                               | 1        | 0.66%   |
| Samsung SCX-4600 Series                                               | 1        | 0.66%   |
| Samsung ML-3470 Series                                                | 1        | 0.66%   |
| Samsung ML-2250 Series                                                | 1        | 0.66%   |
| Samsung ML-1640 Series Laser Printer                                  | 1        | 0.66%   |
| Samsung ML-1610 Mono Laser Printer                                    | 1        | 0.66%   |
| Samsung M2070 Series                                                  | 1        | 0.66%   |
| Ricoh SP 150w                                                         | 1        | 0.66%   |
| QinHeng CH340S                                                        | 1        | 0.66%   |
| Pantum P2000 Series                                                   | 1        | 0.66%   |
| Lexmark International CS417dn                                         | 1        | 0.66%   |
| HP OfficeJet Pro 7720 series                                          | 1        | 0.66%   |
| HP Officejet Pro 6230                                                 | 1        | 0.66%   |
| HP OfficeJet 4650 series                                              | 1        | 0.66%   |
| HP Officejet 4630 series                                              | 1        | 0.66%   |
| HP Officejet 4500 G510n-z                                             | 1        | 0.66%   |
| HP LaserJet Professional P1102w                                       | 1        | 0.66%   |
| HP LaserJet Pro M12a                                                  | 1        | 0.66%   |
| HP LaserJet M101-M106                                                 | 1        | 0.66%   |
| HP LaserJet CP1025nw                                                  | 1        | 0.66%   |
| HP LaserJet 200 colorMFP M276nw                                       | 1        | 0.66%   |
| HP LaserJet 1200                                                      | 1        | 0.66%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 27       | 52.94%  |
| Seiko Epson        | 12       | 23.53%  |
| Hewlett-Packard    | 7        | 13.73%  |
| Mustek Systems     | 3        | 5.88%   |
| Ultima Electronics | 1        | 1.96%   |
| Plustek            | 1        | 1.96%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                                               | 5        | 9.8%    |
| Canon CanoScan LiDE 110                                                               | 5        | 9.8%    |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 5.88%   |
| Canon CanoScan LiDE 120                                                               | 3        | 5.88%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 3.92%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2        | 3.92%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 3.92%   |
| HP Scanjet 200                                                                        | 2        | 3.92%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.92%   |
| Canon CanoScan LiDE 100                                                               | 2        | 3.92%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.96%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 1.96%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 1.96%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1        | 1.96%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1        | 1.96%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.96%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.96%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 1.96%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.96%   |
| Plustek 600DPI USB Scanner                                                            | 1        | 1.96%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 1.96%   |
| HP ScanJet 3800c                                                                      | 1        | 1.96%   |
| HP ScanJet 3400cse                                                                    | 1        | 1.96%   |
| HP ScanJet 2400c                                                                      | 1        | 1.96%   |
| HP PSC 1200                                                                           | 1        | 1.96%   |
| HP HP4470C                                                                            | 1        | 1.96%   |
| Canon CanoScan LiDE 90                                                                | 1        | 1.96%   |
| Canon CanoScan LiDE 700F                                                              | 1        | 1.96%   |
| Canon CanoScan LiDE 600F                                                              | 1        | 1.96%   |
| Canon CanoScan LiDE 60                                                                | 1        | 1.96%   |
| Canon CanoScan LIDE 25                                                                | 1        | 1.96%   |
| Canon CanoScan LiDE 220                                                               | 1        | 1.96%   |
| Canon CanoScan 4200F                                                                  | 1        | 1.96%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 113      | 35.09%  |
| Microsoft                     | 34       | 10.56%  |
| Microdia                      | 32       | 9.94%   |
| ARC International             | 12       | 3.73%   |
| Trust                         | 11       | 3.42%   |
| Sunplus Innovation Technology | 11       | 3.42%   |
| Samsung Electronics           | 10       | 3.11%   |
| Chicony Electronics           | 10       | 3.11%   |
| Cubeternet                    | 7        | 2.17%   |
| Huawei Technologies           | 6        | 1.86%   |
| Z-Star Microelectronics       | 5        | 1.55%   |
| KYE Systems (Mouse Systems)   | 5        | 1.55%   |
| Generalplus Technology        | 5        | 1.55%   |
| webcam                        | 4        | 1.24%   |
| Sunplus IT                    | 4        | 1.24%   |
| Realtek Semiconductor         | 4        | 1.24%   |
| Apple                         | 4        | 1.24%   |
| MacroSilicon                  | 3        | 0.93%   |
| IMC Networks                  | 3        | 0.93%   |
| Genesys Logic                 | 3        | 0.93%   |
| GEMBIRD                       | 3        | 0.93%   |
| Aveo Technology               | 3        | 0.93%   |
| Xiongmai                      | 2        | 0.62%   |
| WaveRider Communications      | 2        | 0.62%   |
| LG Electronics                | 2        | 0.62%   |
| Jieli Technology              | 2        | 0.62%   |
| Hewlett-Packard               | 2        | 0.62%   |
| Arkmicro Technologies         | 2        | 0.62%   |
| Unknown                       | 1        | 0.31%   |
| TerraTec Electronic           | 1        | 0.31%   |
| Syntek                        | 1        | 0.31%   |
| Suyin                         | 1        | 0.31%   |
| Sunplus Technology            | 1        | 0.31%   |
| Sonix Technology              | 1        | 0.31%   |
| SiGma Micro                   | 1        | 0.31%   |
| Razer USA                     | 1        | 0.31%   |
| OmniVision Technologies       | 1        | 0.31%   |
| Novatel Wireless              | 1        | 0.31%   |
| Nintendo                      | 1        | 0.31%   |
| Guillemot                     | 1        | 0.31%   |
| eMPIA Technology              | 1        | 0.31%   |
| Creative Technology           | 1        | 0.31%   |
| CQG-5693-201019               | 1        | 0.31%   |
| ANYKA                         | 1        | 0.31%   |
| Alcor Micro                   | 1        | 0.31%   |
| Acer                          | 1        | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 32       | 9.88%   |
| Microsoft LifeCam HD-3000                             | 18       | 5.56%   |
| Logitech Webcam C170                                  | 17       | 5.25%   |
| Logitech HD Pro Webcam C920                           | 15       | 4.63%   |
| ARC International Camera                              | 12       | 3.7%    |
| Samsung Galaxy A5 (MTP)                               | 10       | 3.09%   |
| Microdia Webcam Vitade AF                             | 8        | 2.47%   |
| Microdia Camera                                       | 7        | 2.16%   |
| Sunplus Aukey-PC-LM1E Camera                          | 6        | 1.85%   |
| Microdia USB 2.0 Camera                               | 6        | 1.85%   |
| Logitech Webcam C310                                  | 6        | 1.85%   |
| Logitech QuickCam Pro 9000                            | 6        | 1.85%   |
| Huawei UVC Camera                                     | 6        | 1.85%   |
| Microdia Sonix USB 2.0 Camera                         | 5        | 1.54%   |
| webcam webcam                                         | 4        | 1.23%   |
| Trust WB-6250X Webcam                                 | 4        | 1.23%   |
| Trust 17676 Webcam                                    | 4        | 1.23%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 4        | 1.23%   |
| Microsoft LifeCam VX-2000                             | 4        | 1.23%   |
| Microdia Laptop_Integrated_Webcam_FHD                 | 4        | 1.23%   |
| Logitech Webcam C200                                  | 4        | 1.23%   |
| Logitech HD Webcam C910                               | 4        | 1.23%   |
| Logitech C922 Pro Stream Webcam                       | 4        | 1.23%   |
| Trust Webcam                                          | 3        | 0.93%   |
| Sunplus Full HD webcam                                | 3        | 0.93%   |
| Microsoft LifeCam VX-5000                             | 3        | 0.93%   |
| Logitech QuickCam E 3500                              | 3        | 0.93%   |
| Logitech HD Webcam C525                               | 3        | 0.93%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 3        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3        | 0.93%   |
| Z-Star Sirius USB2.0 Camera                           | 2        | 0.62%   |
| Xiongmai web camera                                   | 2        | 0.62%   |
| WaveRider USB Live camera                             | 2        | 0.62%   |
| Realtek FULL HD 1080P Webcam                          | 2        | 0.62%   |
| Microsoft LifeCam VX-800                              | 2        | 0.62%   |
| Microsoft LifeCam VX-700                              | 2        | 0.62%   |
| Microsoft LifeCam HD-5000                             | 2        | 0.62%   |
| MacroSilicon USB Video                                | 2        | 0.62%   |
| Logitech Webcam C250                                  | 2        | 0.62%   |
| Logitech Webcam C210                                  | 2        | 0.62%   |
| Logitech QuickCam Communicate MP/S5500                | 2        | 0.62%   |
| Logitech BRIO Ultra HD Webcam                         | 2        | 0.62%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 0.62%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 2        | 0.62%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 2        | 0.62%   |
| Jieli USB PHY 2.0                                     | 2        | 0.62%   |
| Genesys Logic Camera                                  | 2        | 0.62%   |
| Generalplus GENERAL WEBCAM                            | 2        | 0.62%   |
| GEMBIRD USB2.0 PC CAMERA                              | 2        | 0.62%   |
| Cubeternet USB2.0 Camera                              | 2        | 0.62%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 2        | 0.62%   |
| Chicony CNF7166                                       | 2        | 0.62%   |
| Aveo USB2.0 Camera                                    | 2        | 0.62%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 0.31%   |
| Z-Star Sirius USB 2.0 Camera                          | 1        | 0.31%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA                  | 1        | 0.31%   |
| Unknown HD camera                                     | 1        | 0.31%   |
| TerraTec Electronic TerraCam X2                       | 1        | 0.31%   |
| Syntek USB Video Device                               | 1        | 0.31%   |
| Suyin Acer/Lenovo Webcam [CN0316]                     | 1        | 0.31%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 15       | 39.47%  |
| Realtek Semiconductor     | 4        | 10.53%  |
| BIT4ID                    | 4        | 10.53%  |
| Gemalto (was Gemplus)     | 3        | 7.89%   |
| Clay Logic                | 3        | 7.89%   |
| Alcor Micro               | 3        | 7.89%   |
| OmniKey                   | 2        | 5.26%   |
| SCM Microsystems          | 1        | 2.63%   |
| Reiner SCT Kartensysteme  | 1        | 2.63%   |
| Microchip Technology      | 1        | 2.63%   |
| Fujitsu Siemens Computers | 1        | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 13       | 33.33%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 10.26%  |
| BIT4ID miniLector EVO                                                      | 4        | 10.26%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 7.69%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 7.69%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 5.13%   |
| Advanced Card Systems ACR122U                                              | 2        | 5.13%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.56%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.56%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.56%   |
| OmniKey 3x21 Smart Card Reader                                             | 1        | 2.56%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 2.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.56%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 2.56%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1529     | 86.29%  |
| 1     | 214      | 12.08%  |
| 2     | 22       | 1.24%   |
| 3     | 4        | 0.23%   |
| 5     | 2        | 0.11%   |
| 4     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 80       | 29.74%  |
| Net/wireless             | 69       | 25.65%  |
| Communication controller | 27       | 10.04%  |
| Chipcard                 | 23       | 8.55%   |
| Unassigned class         | 19       | 7.06%   |
| Card reader              | 8        | 2.97%   |
| Sound                    | 7        | 2.6%    |
| Multimedia controller    | 7        | 2.6%    |
| Modem                    | 6        | 2.23%   |
| Camera                   | 6        | 2.23%   |
| Dvb card                 | 3        | 1.12%   |
| Bluetooth                | 3        | 1.12%   |
| Video                    | 2        | 0.74%   |
| Tv card                  | 2        | 0.74%   |
| Storage/raid             | 2        | 0.74%   |
| Firewire controller      | 2        | 0.74%   |
| Storage/ide              | 1        | 0.37%   |
| Network                  | 1        | 0.37%   |
| Net/ethernet             | 1        | 0.37%   |
