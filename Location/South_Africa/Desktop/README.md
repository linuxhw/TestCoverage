Linux in South Africa - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Africa.

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

Total: 486

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [1faf7dc08f](https://linux-hardware.org/?probe=1faf7dc08f) | Jun 25, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [87e5572caa](https://linux-hardware.org/?probe=87e5572caa) | Jun 24, 2022 |
| Intel         | DH77KC AAG39641-401         | [3d2faf0e14](https://linux-hardware.org/?probe=3d2faf0e14) | Jun 19, 2022 |
| Biostar       | H81MLV3                     | [d24427bbc8](https://linux-hardware.org/?probe=d24427bbc8) | Jun 18, 2022 |
| ASUSTek       | PRIME X570-P                | [4dc736e2b5](https://linux-hardware.org/?probe=4dc736e2b5) | Jun 16, 2022 |
| Nvidia        | MCP73                       | [4af86ef214](https://linux-hardware.org/?probe=4af86ef214) | Jun 15, 2022 |
| Nvidia        | MCP73                       | [bc4b2de5bc](https://linux-hardware.org/?probe=bc4b2de5bc) | Jun 15, 2022 |
| Supermicro    | X8STi                       | [d99d775afe](https://linux-hardware.org/?probe=d99d775afe) | Jun 12, 2022 |
| Intel         | DQ965GF AAD41676-601        | [13eadd3c2f](https://linux-hardware.org/?probe=13eadd3c2f) | Jun 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ee38b0dd57](https://linux-hardware.org/?probe=ee38b0dd57) | Jun 02, 2022 |
| Intel         | DH55TC AAE70932-206         | [923699ceec](https://linux-hardware.org/?probe=923699ceec) | Jun 01, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Mustek6376... | 945GZT-M ECS                | [0d5f40920b](https://linux-hardware.org/?probe=0d5f40920b) | May 14, 2022 |
| MSI           | H110M PRO-VD                | [f43f2e2bee](https://linux-hardware.org/?probe=f43f2e2bee) | May 10, 2022 |
| MSI           | H110M PRO-VD                | [3d0c46dc84](https://linux-hardware.org/?probe=3d0c46dc84) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [9b78e9af72](https://linux-hardware.org/?probe=9b78e9af72) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | [6e37f18366](https://linux-hardware.org/?probe=6e37f18366) | Apr 21, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| MSI           | X370 KRAIT GAMING           | [26be53ebd1](https://linux-hardware.org/?probe=26be53ebd1) | Apr 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Gigabyte      | H61M-DS2                    | [af56c63db4](https://linux-hardware.org/?probe=af56c63db4) | Apr 12, 2022 |
| Gigabyte      | B150M-D3H-CF                | [1aee3c0b22](https://linux-hardware.org/?probe=1aee3c0b22) | Apr 12, 2022 |
| NCR           | Pocono BIOS.5.1             | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Intel         | DQ965GF AAD41676-601        | [61fca7acbc](https://linux-hardware.org/?probe=61fca7acbc) | Apr 07, 2022 |
| MSI           | X58M                        | [d4146d0724](https://linux-hardware.org/?probe=d4146d0724) | Apr 05, 2022 |
| Foxconn       | 2A8Ch                       | [6354cfe078](https://linux-hardware.org/?probe=6354cfe078) | Apr 04, 2022 |
| Dell          | 0FPP7F A00                  | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [2a333a0767](https://linux-hardware.org/?probe=2a333a0767) | Mar 25, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| Biostar       | G41D3+                      | [8d6a4e54b1](https://linux-hardware.org/?probe=8d6a4e54b1) | Mar 20, 2022 |
| Biostar       | Hi-Fi H61S3                 | [469edf935f](https://linux-hardware.org/?probe=469edf935f) | Mar 14, 2022 |
| Foxconn       | H61MXE/-S/-V/-K             | [8aa740825f](https://linux-hardware.org/?probe=8aa740825f) | Mar 06, 2022 |
| MSI           | Z170A TOMAHAWK              | [e2956753b7](https://linux-hardware.org/?probe=e2956753b7) | Mar 02, 2022 |
| MSI           | Z170A TOMAHAWK              | [ccf1a5fa76](https://linux-hardware.org/?probe=ccf1a5fa76) | Mar 02, 2022 |
| HP            | 1494                        | [f2b67d46d0](https://linux-hardware.org/?probe=f2b67d46d0) | Feb 19, 2022 |
| Gigabyte      | B75M-D3H                    | [469ab361d5](https://linux-hardware.org/?probe=469ab361d5) | Feb 13, 2022 |
| Gigabyte      | B75M-D3H                    | [0d9d3a0b9b](https://linux-hardware.org/?probe=0d9d3a0b9b) | Feb 12, 2022 |
| MSI           | B360-A PRO                  | [1447e1f0e6](https://linux-hardware.org/?probe=1447e1f0e6) | Feb 11, 2022 |
| MSI           | A320M PRO-VD PLUS           | [078b45782e](https://linux-hardware.org/?probe=078b45782e) | Feb 11, 2022 |
| HP            | 1497                        | [3781103124](https://linux-hardware.org/?probe=3781103124) | Feb 09, 2022 |
| ASUSTek       | PRIME B550M-K               | [b4fe3a7a24](https://linux-hardware.org/?probe=b4fe3a7a24) | Feb 07, 2022 |
| MSI           | Z77A-G45                    | [ff87ac3184](https://linux-hardware.org/?probe=ff87ac3184) | Feb 07, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [e514d0d302](https://linux-hardware.org/?probe=e514d0d302) | Feb 03, 2022 |
| Intel         | DH55TC AAE70932-302         | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| Intel         | H81                         | [1f7ff2e980](https://linux-hardware.org/?probe=1f7ff2e980) | Jan 26, 2022 |
| Dell          | 0Y7WYT A00                  | [80295dd814](https://linux-hardware.org/?probe=80295dd814) | Jan 26, 2022 |
| MSI           | B550-A PRO                  | [72d6b552aa](https://linux-hardware.org/?probe=72d6b552aa) | Jan 17, 2022 |
| ECS           | G31T-M7                     | [12ad49d909](https://linux-hardware.org/?probe=12ad49d909) | Jan 16, 2022 |
| ECS           | G31T-M7                     | [5c10976292](https://linux-hardware.org/?probe=5c10976292) | Jan 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [32cae94f00](https://linux-hardware.org/?probe=32cae94f00) | Jan 06, 2022 |
| MSI           | B450M PRO-M2 MAX            | [c103969fdf](https://linux-hardware.org/?probe=c103969fdf) | Jan 06, 2022 |
| Biostar       | Hi-Fi H61S3                 | [6d68cbf5a2](https://linux-hardware.org/?probe=6d68cbf5a2) | Dec 31, 2021 |
| ASRock        | B85M-HDS                    | [8806a9db07](https://linux-hardware.org/?probe=8806a9db07) | Dec 29, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| HP            | 0A58h                       | [2fce860bda](https://linux-hardware.org/?probe=2fce860bda) | Dec 19, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Biostar       | Hi-Fi H61S3                 | [e1362b0ad2](https://linux-hardware.org/?probe=e1362b0ad2) | Dec 14, 2021 |
| ASRock        | AB350 Pro4                  | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| MSI           | H61M-P31                    | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| ASUSTek       | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Gigabyte      | XP-M5S661GX                 | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| HP            | 1497                        | [9a7d6ebc52](https://linux-hardware.org/?probe=9a7d6ebc52) | Nov 26, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| Dell          | 0M9KCM A00                  | [e0f0471cee](https://linux-hardware.org/?probe=e0f0471cee) | Nov 20, 2021 |
| Gigabyte      | Z77-DS3H                    | [e8ef916c87](https://linux-hardware.org/?probe=e8ef916c87) | Nov 18, 2021 |
| MSI           | 970 GAMING                  | [1515779722](https://linux-hardware.org/?probe=1515779722) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | [b74fb29b9b](https://linux-hardware.org/?probe=b74fb29b9b) | Nov 15, 2021 |
| Gigabyte      | H61M-S2PV                   | [c62a6022e8](https://linux-hardware.org/?probe=c62a6022e8) | Nov 14, 2021 |
| ASUSTek       | P8P67-M                     | [1cb5f14632](https://linux-hardware.org/?probe=1cb5f14632) | Nov 13, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b7579cb355](https://linux-hardware.org/?probe=b7579cb355) | Nov 12, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [39e3c646ff](https://linux-hardware.org/?probe=39e3c646ff) | Nov 11, 2021 |
| ASUSTek       | P8P67-M                     | [701e60decc](https://linux-hardware.org/?probe=701e60decc) | Nov 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | [62ba7df7ec](https://linux-hardware.org/?probe=62ba7df7ec) | Nov 11, 2021 |
| HP            | ProLiant MicroServer        | [383b7f1862](https://linux-hardware.org/?probe=383b7f1862) | Nov 11, 2021 |
| MSI           | H110M PRO-VH PLUS           | [02f1a55757](https://linux-hardware.org/?probe=02f1a55757) | Nov 08, 2021 |
| NCR           | Pocono BIOS.3.1             | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| MSI           | H110M PRO-VH PLUS           | [57417d57e3](https://linux-hardware.org/?probe=57417d57e3) | Nov 06, 2021 |
| HP            | 0B4Ch D                     | [f51fee36d1](https://linux-hardware.org/?probe=f51fee36d1) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [dd22d96d07](https://linux-hardware.org/?probe=dd22d96d07) | Oct 30, 2021 |
| Biostar       | B350GTN                     | [53c5fd6db4](https://linux-hardware.org/?probe=53c5fd6db4) | Oct 26, 2021 |
| Gigabyte      | H61M-S2PV                   | [37ae9a9258](https://linux-hardware.org/?probe=37ae9a9258) | Oct 23, 2021 |
| Lenovo        | ThinkCentre M91p 4512A12    | [1ecb7a6910](https://linux-hardware.org/?probe=1ecb7a6910) | Oct 19, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| Dell          | 0M9KCM A00                  | [d837406f2a](https://linux-hardware.org/?probe=d837406f2a) | Oct 16, 2021 |
| NCR           | Pocono BIOS.3.1             | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| HP            | 81C3                        | [df2caaf484](https://linux-hardware.org/?probe=df2caaf484) | Oct 11, 2021 |
| MSI           | Z170A TOMAHAWK              | [e39ce9ade6](https://linux-hardware.org/?probe=e39ce9ade6) | Oct 09, 2021 |
| MSI           | Z170A TOMAHAWK              | [5a5c0c8f90](https://linux-hardware.org/?probe=5a5c0c8f90) | Oct 07, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [42a76fbc95](https://linux-hardware.org/?probe=42a76fbc95) | Oct 05, 2021 |
| Nvidia        | MCP73                       | [7099e6ef4b](https://linux-hardware.org/?probe=7099e6ef4b) | Oct 02, 2021 |
| ASRock        | B550M Steel Legend          | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| Gigabyte      | B150M-D3H-CF                | [8fe1edb38b](https://linux-hardware.org/?probe=8fe1edb38b) | Sep 30, 2021 |
| HP            | 1497                        | [a792022089](https://linux-hardware.org/?probe=a792022089) | Sep 30, 2021 |
| Gigabyte      | G31M-S2L                    | [3255b4d143](https://linux-hardware.org/?probe=3255b4d143) | Sep 28, 2021 |
| Intel         | DQ77CP AAG67261-300         | [2da6abda17](https://linux-hardware.org/?probe=2da6abda17) | Sep 25, 2021 |
| Gigabyte      | H55M-S2H                    | [82fe8d569f](https://linux-hardware.org/?probe=82fe8d569f) | Sep 11, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | Z170A PC MATE               | [192a0d3f1a](https://linux-hardware.org/?probe=192a0d3f1a) | Sep 07, 2021 |
| Dell          | 0GM819                      | [f0cc146236](https://linux-hardware.org/?probe=f0cc146236) | Sep 04, 2021 |
| Intel         | D865GLC AAC28906-407        | [5936f5b3ba](https://linux-hardware.org/?probe=5936f5b3ba) | Sep 01, 2021 |
| Intel         | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Gigabyte      | G33M-DS2R                   | [0b340c6818](https://linux-hardware.org/?probe=0b340c6818) | Aug 29, 2021 |
| HP            | 212B                        | [10646959ce](https://linux-hardware.org/?probe=10646959ce) | Aug 27, 2021 |
| Biostar       | H61MGV3                     | [fa2b470ff5](https://linux-hardware.org/?probe=fa2b470ff5) | Aug 26, 2021 |
| Biostar       | H61MGV3                     | [19eacc88f5](https://linux-hardware.org/?probe=19eacc88f5) | Aug 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 0HH807                      | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| MSI           | B450M PRO-M2 MAX            | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| HP            | 0A50h                       | [f7ea4959d2](https://linux-hardware.org/?probe=f7ea4959d2) | Aug 21, 2021 |
| MSI           | G41M4                       | [c5c2a6945a](https://linux-hardware.org/?probe=c5c2a6945a) | Aug 20, 2021 |
| MSI           | G41M4                       | [3862c2333b](https://linux-hardware.org/?probe=3862c2333b) | Aug 20, 2021 |
| Intel         | DH61WW AAG23116-300         | [0a023d2778](https://linux-hardware.org/?probe=0a023d2778) | Aug 17, 2021 |
| MSI           | 970A-G46                    | [1d552fc481](https://linux-hardware.org/?probe=1d552fc481) | Aug 14, 2021 |
| MSI           | 970A-G46                    | [ee8d3d8ed0](https://linux-hardware.org/?probe=ee8d3d8ed0) | Aug 14, 2021 |
| HP            | 3031h                       | [201543483c](https://linux-hardware.org/?probe=201543483c) | Aug 13, 2021 |
| ASUSTek       | Rampage II GENE             | [ec056ad7c5](https://linux-hardware.org/?probe=ec056ad7c5) | Aug 12, 2021 |
| Intel         | DH61WW AAG23116-300         | [95ed07c904](https://linux-hardware.org/?probe=95ed07c904) | Aug 05, 2021 |
| Gigabyte      | G41MT-S2PT                  | [cf42c809f2](https://linux-hardware.org/?probe=cf42c809f2) | Aug 04, 2021 |
| MSI           | G31M3-F V2                  | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| Intel         | DH61WW AAG23116-300         | [886881e04d](https://linux-hardware.org/?probe=886881e04d) | Aug 01, 2021 |
| Dell          | 096JG8 A01                  | [b45d7e4f99](https://linux-hardware.org/?probe=b45d7e4f99) | Jul 29, 2021 |
| Dell          | 096JG8 A01                  | [290acd3514](https://linux-hardware.org/?probe=290acd3514) | Jul 28, 2021 |
| Intel         | DH55HC AAE70933-504         | [f3a838da1b](https://linux-hardware.org/?probe=f3a838da1b) | Jul 28, 2021 |
| MSI           | 990FXA-GD65                 | [6fe8efac3a](https://linux-hardware.org/?probe=6fe8efac3a) | Jul 25, 2021 |
| Gigabyte      | G41MT-S2PT                  | [7e37603df2](https://linux-hardware.org/?probe=7e37603df2) | Jul 23, 2021 |
| Intel         | DH61WW AAG23116-300         | [fd7862ecd9](https://linux-hardware.org/?probe=fd7862ecd9) | Jul 23, 2021 |
| HP            | 1494                        | [fe57b848c7](https://linux-hardware.org/?probe=fe57b848c7) | Jul 22, 2021 |
| Intel         | DP35DP AAD81073-207         | [7ff35da9be](https://linux-hardware.org/?probe=7ff35da9be) | Jul 22, 2021 |
| Intel         | DP35DP AAD81073-207         | [179a2a6dbb](https://linux-hardware.org/?probe=179a2a6dbb) | Jul 21, 2021 |
| Intel         | DP35DP AAD81073-207         | [9ab1130986](https://linux-hardware.org/?probe=9ab1130986) | Jul 21, 2021 |
| HP            | 1494                        | [2c30dc2cf3](https://linux-hardware.org/?probe=2c30dc2cf3) | Jul 19, 2021 |
| MSI           | TRX40 PRO 10G               | [a06646b4da](https://linux-hardware.org/?probe=a06646b4da) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-300         | [455abdf0c3](https://linux-hardware.org/?probe=455abdf0c3) | Jul 18, 2021 |
| Gigabyte      | G33M-DS2R                   | [04b5a9113c](https://linux-hardware.org/?probe=04b5a9113c) | Jul 17, 2021 |
| ASUSTek       | P5K                         | [8e28e97b01](https://linux-hardware.org/?probe=8e28e97b01) | Jul 16, 2021 |
| Intel         | DH61WW AAG23116-300         | [0de164a96d](https://linux-hardware.org/?probe=0de164a96d) | Jul 16, 2021 |
| Intel         | DH61WW AAG23116-300         | [d14aa75f4c](https://linux-hardware.org/?probe=d14aa75f4c) | Jul 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [1b156e0069](https://linux-hardware.org/?probe=1b156e0069) | Jul 12, 2021 |
| Intel         | DG31PR AAD97573-306         | [a81005ef0b](https://linux-hardware.org/?probe=a81005ef0b) | Jul 10, 2021 |
| MSI           | H81M-P33                    | [a03d8e33d2](https://linux-hardware.org/?probe=a03d8e33d2) | Jul 08, 2021 |
| MSI           | H81M-P33                    | [48a72375f0](https://linux-hardware.org/?probe=48a72375f0) | Jul 08, 2021 |
| Acer          | Aspire X3950                | [1ff3961dca](https://linux-hardware.org/?probe=1ff3961dca) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | [7756be5173](https://linux-hardware.org/?probe=7756be5173) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | [9282eabbef](https://linux-hardware.org/?probe=9282eabbef) | Jul 06, 2021 |
| Intel         | DQ77CP AAG67261-300         | [de63bf6b9c](https://linux-hardware.org/?probe=de63bf6b9c) | Jul 06, 2021 |
| Lenovo        | SDK0E50510 WIN              | [d37ee6f754](https://linux-hardware.org/?probe=d37ee6f754) | Jul 04, 2021 |
| Lenovo        | SDK0E50510 WIN              | [2d6120fa61](https://linux-hardware.org/?probe=2d6120fa61) | Jul 04, 2021 |
| ASRock        | H110M-DGS                   | [1439cc6a27](https://linux-hardware.org/?probe=1439cc6a27) | Jul 04, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ea982e9d39](https://linux-hardware.org/?probe=ea982e9d39) | Jul 03, 2021 |
| Foxconn       | 2ABF                        | [b54459c5ca](https://linux-hardware.org/?probe=b54459c5ca) | Jul 01, 2021 |
| MSI           | Z170A PC MATE               | [bd3c620117](https://linux-hardware.org/?probe=bd3c620117) | Jun 24, 2021 |
| Biostar       | TB250-BTC                   | [135a42fc66](https://linux-hardware.org/?probe=135a42fc66) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | [acdf9bed0d](https://linux-hardware.org/?probe=acdf9bed0d) | Jun 19, 2021 |
| Intel         | DH55HC AAE70933-505         | [7b2f77f8db](https://linux-hardware.org/?probe=7b2f77f8db) | Jun 17, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [6a2ce38cb0](https://linux-hardware.org/?probe=6a2ce38cb0) | Jun 12, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [77f9400e70](https://linux-hardware.org/?probe=77f9400e70) | Jun 11, 2021 |
| ASRock        | H61M-VS4                    | [4e96d5e81a](https://linux-hardware.org/?probe=4e96d5e81a) | Jun 10, 2021 |
| Intel         | DQ57TM AAE70931-400         | [d770d5673c](https://linux-hardware.org/?probe=d770d5673c) | Jun 04, 2021 |
| MSI           | B450M PRO-M2 MAX            | [71bd5e1a20](https://linux-hardware.org/?probe=71bd5e1a20) | Jun 04, 2021 |
| ASRock        | B550M Steel Legend          | [f39108e22f](https://linux-hardware.org/?probe=f39108e22f) | May 29, 2021 |
| ASUSTek       | M2NPV-MX                    | [37bc060302](https://linux-hardware.org/?probe=37bc060302) | May 27, 2021 |
| ASUSTek       | M2NPV-MX                    | [11cee33a59](https://linux-hardware.org/?probe=11cee33a59) | May 27, 2021 |
| Intel         | H81                         | [9107f9abe6](https://linux-hardware.org/?probe=9107f9abe6) | May 25, 2021 |
| ASUSTek       | PRIME B250M-A               | [2961088957](https://linux-hardware.org/?probe=2961088957) | May 24, 2021 |
| Gigabyte      | H97-Gaming 3                | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| Gigabyte      | G31M-ES2C                   | [98e3f46335](https://linux-hardware.org/?probe=98e3f46335) | May 21, 2021 |
| HP            | 802F                        | [88fa80f493](https://linux-hardware.org/?probe=88fa80f493) | May 20, 2021 |
| ASUSTek       | PRIME B250M-A               | [b646c2612a](https://linux-hardware.org/?probe=b646c2612a) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| ASUSTek       | PRIME X570-P                | [8d4f6e55dc](https://linux-hardware.org/?probe=8d4f6e55dc) | May 14, 2021 |
| Acer          | Veriton M4620G v1.0         | [bec2435c15](https://linux-hardware.org/?probe=bec2435c15) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Gigabyte      | H110-D3A-CF                 | [016d2f25a7](https://linux-hardware.org/?probe=016d2f25a7) | May 06, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [9d01fac140](https://linux-hardware.org/?probe=9d01fac140) | May 06, 2021 |
| ASUSTek       | Z87-K                       | [6d9e2228c3](https://linux-hardware.org/?probe=6d9e2228c3) | May 05, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| MSI           | H110M PRO-VD PLUS           | [f9f1775d7a](https://linux-hardware.org/?probe=f9f1775d7a) | Apr 24, 2021 |
| MSI           | H110M PRO-VD PLUS           | [8356cbd097](https://linux-hardware.org/?probe=8356cbd097) | Apr 24, 2021 |
| Unknown       | NF-MCP61                    | [2ba92fa1b6](https://linux-hardware.org/?probe=2ba92fa1b6) | Apr 12, 2021 |
| Unknown       | NF-MCP61                    | [265d75e8f5](https://linux-hardware.org/?probe=265d75e8f5) | Apr 12, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c49b7e8d5d](https://linux-hardware.org/?probe=c49b7e8d5d) | Apr 01, 2021 |
| ASRock        | H110M-DGS                   | [786c07faff](https://linux-hardware.org/?probe=786c07faff) | Mar 29, 2021 |
| ASRock        | H110M-DGS                   | [e47641b719](https://linux-hardware.org/?probe=e47641b719) | Mar 29, 2021 |
| HP            | 3397                        | [8bf9eb3e2b](https://linux-hardware.org/?probe=8bf9eb3e2b) | Mar 24, 2021 |
| MSI           | Z370 GAMING PRO CARBON A... | [19c2138c14](https://linux-hardware.org/?probe=19c2138c14) | Mar 21, 2021 |
| Intel         | H61M-DS2                    | [26d3b20dae](https://linux-hardware.org/?probe=26d3b20dae) | Mar 20, 2021 |
| Intel         | H61M-DS2                    | [d92567fa4b](https://linux-hardware.org/?probe=d92567fa4b) | Mar 20, 2021 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [863c61112e](https://linux-hardware.org/?probe=863c61112e) | Mar 15, 2021 |
| ASRock        | H110M-DGS                   | [fb02551d4b](https://linux-hardware.org/?probe=fb02551d4b) | Mar 09, 2021 |
| Acer          | Veriton M4620G v1.0         | [dd94f284a7](https://linux-hardware.org/?probe=dd94f284a7) | Mar 06, 2021 |
| Acer          | Veriton M4620G v1.0         | [3a6a85e270](https://linux-hardware.org/?probe=3a6a85e270) | Mar 06, 2021 |
| Intel         | DG31PR AAD97573-301         | [afbd63a295](https://linux-hardware.org/?probe=afbd63a295) | Mar 02, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [7a590f917d](https://linux-hardware.org/?probe=7a590f917d) | Mar 01, 2021 |
| MSI           | H81M-P33                    | [0842ade22d](https://linux-hardware.org/?probe=0842ade22d) | Feb 28, 2021 |
| MSI           | H81M-P33                    | [4de126b116](https://linux-hardware.org/?probe=4de126b116) | Feb 28, 2021 |
| MSI           | X570-A PRO                  | [d49fa2b9b8](https://linux-hardware.org/?probe=d49fa2b9b8) | Feb 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24edce07be](https://linux-hardware.org/?probe=24edce07be) | Feb 23, 2021 |
| Foxconn       | H61MXP                      | [048b9579b0](https://linux-hardware.org/?probe=048b9579b0) | Feb 23, 2021 |
| ASUSTek       | P8Z68-V                     | [af7b978365](https://linux-hardware.org/?probe=af7b978365) | Feb 22, 2021 |
| ASUSTek       | P8Z68-V                     | [8e7261c2a4](https://linux-hardware.org/?probe=8e7261c2a4) | Feb 22, 2021 |
| ASRock        | H110M-DVS R2.0              | [58d85cf78e](https://linux-hardware.org/?probe=58d85cf78e) | Feb 21, 2021 |
| ASUSTek       | SABERTOOTH Z170 S           | [8cee0d69e5](https://linux-hardware.org/?probe=8cee0d69e5) | Feb 18, 2021 |
| ASUSTek       | SABERTOOTH Z170 S           | [490d7048e7](https://linux-hardware.org/?probe=490d7048e7) | Feb 18, 2021 |
| Intel         | DH67CL AAG10212-210         | [5995dadf6e](https://linux-hardware.org/?probe=5995dadf6e) | Feb 18, 2021 |
| Foxconn       | H61MXP                      | [d4938b881d](https://linux-hardware.org/?probe=d4938b881d) | Feb 17, 2021 |
| MSI           | B250I GAMING PRO AC         | [e451c5c4c0](https://linux-hardware.org/?probe=e451c5c4c0) | Feb 17, 2021 |
| MSI           | X570-A PRO                  | [615e4e0a09](https://linux-hardware.org/?probe=615e4e0a09) | Feb 17, 2021 |
| ASRock        | H110M-DGS                   | [7f8d441dad](https://linux-hardware.org/?probe=7f8d441dad) | Feb 17, 2021 |
| MSI           | X99A SLI PLUS               | [db1e5dad24](https://linux-hardware.org/?probe=db1e5dad24) | Feb 16, 2021 |
| MSI           | X99A SLI PLUS               | [9dd966644d](https://linux-hardware.org/?probe=9dd966644d) | Feb 16, 2021 |
| Acer          | Aspire XC-830               | [9aa4fa465f](https://linux-hardware.org/?probe=9aa4fa465f) | Feb 07, 2021 |
| Acer          | Aspire XC-830               | [fd4af8dfa8](https://linux-hardware.org/?probe=fd4af8dfa8) | Feb 07, 2021 |
| Unknown       | NF-MCP61                    | [0025bae7bc](https://linux-hardware.org/?probe=0025bae7bc) | Feb 07, 2021 |
| Unknown       | NF-MCP61                    | [655941b24c](https://linux-hardware.org/?probe=655941b24c) | Feb 07, 2021 |
| MSI           | B350M GAMING PRO            | [c8bbdc9014](https://linux-hardware.org/?probe=c8bbdc9014) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M57p 6073WB2    | [519a5dab13](https://linux-hardware.org/?probe=519a5dab13) | Jan 31, 2021 |
| Dell          | 0M9KCM A00                  | [bb2c2af939](https://linux-hardware.org/?probe=bb2c2af939) | Jan 30, 2021 |
| Lenovo        | ThinkCentre M57p 6073WB2    | [6845c1eca5](https://linux-hardware.org/?probe=6845c1eca5) | Jan 29, 2021 |
| Foxconn       | H61MXP                      | [9104fd06b9](https://linux-hardware.org/?probe=9104fd06b9) | Jan 24, 2021 |
| ASUSTek       | Q87M-E                      | [dc1ef1ca11](https://linux-hardware.org/?probe=dc1ef1ca11) | Jan 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [073c824145](https://linux-hardware.org/?probe=073c824145) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | [ab6314ffcb](https://linux-hardware.org/?probe=ab6314ffcb) | Jan 21, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [ceef024b73](https://linux-hardware.org/?probe=ceef024b73) | Jan 20, 2021 |
| MSI           | H77MA-G43                   | [d949ec9e22](https://linux-hardware.org/?probe=d949ec9e22) | Jan 20, 2021 |
| Biostar       | H61MGV                      | [41870b834e](https://linux-hardware.org/?probe=41870b834e) | Jan 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| ASUSTek       | H110M-K                     | [475b3240df](https://linux-hardware.org/?probe=475b3240df) | Jan 15, 2021 |
| Intel         | DH55TC AAE70932-302         | [37fa6be89b](https://linux-hardware.org/?probe=37fa6be89b) | Jan 12, 2021 |
| HP            | 1497                        | [1983edaa9d](https://linux-hardware.org/?probe=1983edaa9d) | Jan 10, 2021 |
| Gigabyte      | B75M-D3H                    | [8b9b3a12bf](https://linux-hardware.org/?probe=8b9b3a12bf) | Jan 09, 2021 |
| Gigabyte      | B75M-D3H                    | [08608262c0](https://linux-hardware.org/?probe=08608262c0) | Jan 09, 2021 |
| MSI           | Z77A-GD55                   | [7a756f5970](https://linux-hardware.org/?probe=7a756f5970) | Jan 08, 2021 |
| Gigabyte      | X58A-UD3R                   | [860a73fabe](https://linux-hardware.org/?probe=860a73fabe) | Dec 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [0dd4ebf5b8](https://linux-hardware.org/?probe=0dd4ebf5b8) | Dec 29, 2020 |
| ASUSTek       | M4A78T-E                    | [cba05b27c4](https://linux-hardware.org/?probe=cba05b27c4) | Dec 26, 2020 |
| ASUSTek       | P8B75-V                     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| Gigabyte      | EG31M-S2                    | [cf3ce9357e](https://linux-hardware.org/?probe=cf3ce9357e) | Dec 14, 2020 |
| Lenovo        | ThinkCentre M90p 3853W1B    | [2a0f16e160](https://linux-hardware.org/?probe=2a0f16e160) | Dec 08, 2020 |
| Gigabyte      | H81M-S2PH                   | [86bd640aaa](https://linux-hardware.org/?probe=86bd640aaa) | Dec 07, 2020 |
| Gigabyte      | Z370 HD3-CF                 | [7e191e6e88](https://linux-hardware.org/?probe=7e191e6e88) | Dec 07, 2020 |
| Dell          | OptiPlex 3010               | [41dabae1fc](https://linux-hardware.org/?probe=41dabae1fc) | Dec 07, 2020 |
| MSI           | NF980-G65                   | [905c03a3d4](https://linux-hardware.org/?probe=905c03a3d4) | Dec 02, 2020 |
| ASRock        | 970 Pro3 R2.0               | [0b92fa9e96](https://linux-hardware.org/?probe=0b92fa9e96) | Dec 01, 2020 |
| ASRock        | 970 Pro3 R2.0               | [1526683bfc](https://linux-hardware.org/?probe=1526683bfc) | Nov 30, 2020 |
| ASRock        | 970 Pro3 R2.0               | [4e0a5a0779](https://linux-hardware.org/?probe=4e0a5a0779) | Nov 25, 2020 |
| ASUSTek       | H110M-K                     | [b19f8914b4](https://linux-hardware.org/?probe=b19f8914b4) | Nov 20, 2020 |
| ASUSTek       | H110M-K                     | [c7bdefa142](https://linux-hardware.org/?probe=c7bdefa142) | Nov 20, 2020 |
| MSI           | H61M-P25                    | [d61bf84dc4](https://linux-hardware.org/?probe=d61bf84dc4) | Nov 20, 2020 |
| ASUSTek       | H110M-R                     | [c20406a1b5](https://linux-hardware.org/?probe=c20406a1b5) | Nov 20, 2020 |
| ASUSTek       | H81M-C                      | [aa50c863e9](https://linux-hardware.org/?probe=aa50c863e9) | Nov 20, 2020 |
| ASUSTek       | M4A78T-E                    | [503cfe38f0](https://linux-hardware.org/?probe=503cfe38f0) | Nov 18, 2020 |
| MSI           | MAG B550M MORTAR            | [61d2df9a57](https://linux-hardware.org/?probe=61d2df9a57) | Nov 17, 2020 |
| Intel         | DH67BL AAG10189-206         | [0762d1d1ce](https://linux-hardware.org/?probe=0762d1d1ce) | Nov 14, 2020 |
| Acer          | Aspire XC-705               | [143555ecdc](https://linux-hardware.org/?probe=143555ecdc) | Nov 09, 2020 |
| ASUSTek       | H110M-K D3                  | [114c634725](https://linux-hardware.org/?probe=114c634725) | Nov 09, 2020 |
| MSI           | NF980-G65                   | [91f0882001](https://linux-hardware.org/?probe=91f0882001) | Nov 04, 2020 |
| HP            | ProLiant MicroServer        | [cdc24d2269](https://linux-hardware.org/?probe=cdc24d2269) | Nov 02, 2020 |
| Gigabyte      | G41MT-ES2L                  | [c729daf76c](https://linux-hardware.org/?probe=c729daf76c) | Nov 02, 2020 |
| Acer          | Aspire XC-705               | [f306c95ded](https://linux-hardware.org/?probe=f306c95ded) | Nov 02, 2020 |
| Acer          | Aspire XC-705               | [8816461fc2](https://linux-hardware.org/?probe=8816461fc2) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| MSI           | B450M PRO-M2 MAX            | [192c993267](https://linux-hardware.org/?probe=192c993267) | Oct 26, 2020 |
| MSI           | NF980-G65                   | [b37787e43b](https://linux-hardware.org/?probe=b37787e43b) | Oct 24, 2020 |
| Dell          | 0V8F20 A01                  | [458ed5a803](https://linux-hardware.org/?probe=458ed5a803) | Oct 21, 2020 |
| Gigabyte      | G1.Sniper 2                 | [c4e2198b02](https://linux-hardware.org/?probe=c4e2198b02) | Oct 17, 2020 |
| Gigabyte      | G1.Sniper 2                 | [020c0aa748](https://linux-hardware.org/?probe=020c0aa748) | Oct 17, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [7fecbf8628](https://linux-hardware.org/?probe=7fecbf8628) | Oct 13, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [42fe628907](https://linux-hardware.org/?probe=42fe628907) | Oct 13, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [b166b30db3](https://linux-hardware.org/?probe=b166b30db3) | Oct 08, 2020 |
| Lenovo        | ThinkCentre A70 0889F4G     | [1e6d80b5da](https://linux-hardware.org/?probe=1e6d80b5da) | Oct 06, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [e161c96649](https://linux-hardware.org/?probe=e161c96649) | Sep 30, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [b21331d245](https://linux-hardware.org/?probe=b21331d245) | Sep 30, 2020 |
| ASUSTek       | Z170-E                      | [bebee961b4](https://linux-hardware.org/?probe=bebee961b4) | Sep 30, 2020 |
| MSI           | H77MA-G43                   | [bc6fb15e78](https://linux-hardware.org/?probe=bc6fb15e78) | Sep 29, 2020 |
| MSI           | H77MA-G43                   | [07f4ed634b](https://linux-hardware.org/?probe=07f4ed634b) | Sep 29, 2020 |
| ASRock        | H110M-ITX/ac                | [9c30ba348a](https://linux-hardware.org/?probe=9c30ba348a) | Sep 28, 2020 |
| ASUSTek       | Z170-E                      | [c5e88dea7d](https://linux-hardware.org/?probe=c5e88dea7d) | Sep 27, 2020 |
| ASUSTek       | Z170-E                      | [9c106c44cf](https://linux-hardware.org/?probe=9c106c44cf) | Sep 27, 2020 |
| Biostar       | H61MGV                      | [003204ad9f](https://linux-hardware.org/?probe=003204ad9f) | Sep 20, 2020 |
| Intel         | DH87MC AAG74242-401         | [640d76455f](https://linux-hardware.org/?probe=640d76455f) | Sep 20, 2020 |
| Biostar       | H61MLV3                     | [706ef154e2](https://linux-hardware.org/?probe=706ef154e2) | Sep 14, 2020 |
| Biostar       | H61MLV3                     | [837ad7626c](https://linux-hardware.org/?probe=837ad7626c) | Sep 14, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [3a6da8abca](https://linux-hardware.org/?probe=3a6da8abca) | Sep 13, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [e5854eb062](https://linux-hardware.org/?probe=e5854eb062) | Sep 12, 2020 |
| MSI           | X570-A PRO                  | [656188adb4](https://linux-hardware.org/?probe=656188adb4) | Sep 09, 2020 |
| MSI           | H81M-E33                    | [b95a7fc433](https://linux-hardware.org/?probe=b95a7fc433) | Sep 09, 2020 |
| Gigabyte      | G31M-S2L                    | [a70420ab80](https://linux-hardware.org/?probe=a70420ab80) | Sep 07, 2020 |
| MSI           | Z170A GAMING PRO            | [a23e1ab6f7](https://linux-hardware.org/?probe=a23e1ab6f7) | Sep 06, 2020 |
| MSI           | Z170A GAMING PRO            | [e12a573590](https://linux-hardware.org/?probe=e12a573590) | Sep 06, 2020 |
| Gigabyte      | 8VM800PMD-775               | [5556df1576](https://linux-hardware.org/?probe=5556df1576) | Sep 06, 2020 |
| Gigabyte      | 8VM800PMD-775               | [69d3d97213](https://linux-hardware.org/?probe=69d3d97213) | Sep 06, 2020 |
| Intel         | DQ77MK AAG39642-400         | [e44a1ed00a](https://linux-hardware.org/?probe=e44a1ed00a) | Sep 05, 2020 |
| MSI           | MPG Z390 GAMING EDGE AC     | [8b70f4c277](https://linux-hardware.org/?probe=8b70f4c277) | Sep 04, 2020 |
| ASRock        | B450M Pro4                  | [58a5d68d50](https://linux-hardware.org/?probe=58a5d68d50) | Sep 03, 2020 |
| MSI           | 0A48                        | [0b6b6f4e6c](https://linux-hardware.org/?probe=0b6b6f4e6c) | Sep 01, 2020 |
| MSI           | B350M MORTAR                | [95318ea3f4](https://linux-hardware.org/?probe=95318ea3f4) | Aug 31, 2020 |
| ASUSTek       | H110M-K D3                  | [5e4fc68354](https://linux-hardware.org/?probe=5e4fc68354) | Aug 28, 2020 |
| Biostar       | H61MGV                      | [6fc04609f6](https://linux-hardware.org/?probe=6fc04609f6) | Aug 26, 2020 |
| ASUSTek       | P8H67-M LX                  | [1b2d7271d9](https://linux-hardware.org/?probe=1b2d7271d9) | Aug 26, 2020 |
| ASUSTek       | P8H67-M LX                  | [839d7c2a46](https://linux-hardware.org/?probe=839d7c2a46) | Aug 26, 2020 |
| Intel         | E98683-352                  | [2cced3a630](https://linux-hardware.org/?probe=2cced3a630) | Aug 26, 2020 |
| Acer          | Aspire XC-705               | [a14063c53e](https://linux-hardware.org/?probe=a14063c53e) | Aug 25, 2020 |
| MSI           | 0A48                        | [ecc5cc9591](https://linux-hardware.org/?probe=ecc5cc9591) | Aug 24, 2020 |
| MSI           | 0A48                        | [6cd21feb7e](https://linux-hardware.org/?probe=6cd21feb7e) | Aug 23, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0d285d0379](https://linux-hardware.org/?probe=0d285d0379) | Aug 22, 2020 |
| Intel         | DH67BL AAG10189-206         | [e160d14621](https://linux-hardware.org/?probe=e160d14621) | Aug 22, 2020 |
| MSI           | H310M PRO-VH PLUS           | [faecb20cfb](https://linux-hardware.org/?probe=faecb20cfb) | Aug 19, 2020 |
| HP            | 1495                        | [c801ac56c4](https://linux-hardware.org/?probe=c801ac56c4) | Aug 18, 2020 |
| ASRock        | G31M-S                      | [decbf99a87](https://linux-hardware.org/?probe=decbf99a87) | Aug 17, 2020 |
| ASRock        | G31M-S                      | [4915506e2e](https://linux-hardware.org/?probe=4915506e2e) | Aug 17, 2020 |
| Intel         | DH77EB AAG39073-304         | [ae001e48e0](https://linux-hardware.org/?probe=ae001e48e0) | Aug 16, 2020 |
| ASRock        | H61M-VS3                    | [d140a21b1c](https://linux-hardware.org/?probe=d140a21b1c) | Aug 16, 2020 |
| ASRock        | A320M                       | [e0c8cc0af2](https://linux-hardware.org/?probe=e0c8cc0af2) | Aug 14, 2020 |
| MSI           | 0A48                        | [24b38b5516](https://linux-hardware.org/?probe=24b38b5516) | Aug 12, 2020 |
| MSI           | 0A48                        | [a3f7719625](https://linux-hardware.org/?probe=a3f7719625) | Aug 12, 2020 |
| Dell          | 06D7TR A00                  | [71d3a723ab](https://linux-hardware.org/?probe=71d3a723ab) | Aug 11, 2020 |
| Gigabyte      | H61M-DS2                    | [218e35b46b](https://linux-hardware.org/?probe=218e35b46b) | Aug 10, 2020 |
| Gigabyte      | H61M-DS2                    | [4ff4ced1de](https://linux-hardware.org/?probe=4ff4ced1de) | Aug 10, 2020 |
| Intel         | DQ965GF AAD41676-402        | [c3ceaf788a](https://linux-hardware.org/?probe=c3ceaf788a) | Aug 10, 2020 |
| ASRock        | H61M-VS3                    | [ec2a94de5a](https://linux-hardware.org/?probe=ec2a94de5a) | Aug 09, 2020 |
| Gigabyte      | XP-M5S661GX                 | [5f94eae640](https://linux-hardware.org/?probe=5f94eae640) | Aug 07, 2020 |
| MSI           | H310M PRO-VH PLUS           | [2f79221a54](https://linux-hardware.org/?probe=2f79221a54) | Aug 02, 2020 |
| Nvidia        | MCP73                       | [51821b9a72](https://linux-hardware.org/?probe=51821b9a72) | Aug 01, 2020 |
| Acer          | Aspire XC-705               | [c17f70b052](https://linux-hardware.org/?probe=c17f70b052) | Aug 01, 2020 |
| MSI           | H81M-P33                    | [2b15f51554](https://linux-hardware.org/?probe=2b15f51554) | Jul 29, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [be59eae36f](https://linux-hardware.org/?probe=be59eae36f) | Jul 28, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [adb494dfce](https://linux-hardware.org/?probe=adb494dfce) | Jul 28, 2020 |
| Foxconn       | P4M890-8237A                | [c26157f6a1](https://linux-hardware.org/?probe=c26157f6a1) | Jul 23, 2020 |
| Intel         | DH87MC AAG74242-401         | [4a60cb40c9](https://linux-hardware.org/?probe=4a60cb40c9) | Jul 20, 2020 |
| Dell          | 06D7TR A00                  | [ba6562dccd](https://linux-hardware.org/?probe=ba6562dccd) | Jul 18, 2020 |
| Intel         | DP55WB AAE64798-206         | [f533450c99](https://linux-hardware.org/?probe=f533450c99) | Jul 16, 2020 |
| HP            | ProLiant ML110 G7           | [bb50bb3a46](https://linux-hardware.org/?probe=bb50bb3a46) | Jul 15, 2020 |
| Intel         | DH67BL AAG10189-206         | [4548f15388](https://linux-hardware.org/?probe=4548f15388) | Jul 12, 2020 |
| Lenovo        | MAHOBAY NOK                 | [c6660d16e0](https://linux-hardware.org/?probe=c6660d16e0) | Jul 08, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [de85d7ecf6](https://linux-hardware.org/?probe=de85d7ecf6) | Jul 07, 2020 |
| ASRock        | AB350M-HDV                  | [db7ec5e511](https://linux-hardware.org/?probe=db7ec5e511) | Jun 29, 2020 |
| ECS           | G31T-M7                     | [95eaae406a](https://linux-hardware.org/?probe=95eaae406a) | Jun 27, 2020 |
| Intel         | DH67BL AAG10189-206         | [693e0bb2f6](https://linux-hardware.org/?probe=693e0bb2f6) | Jun 22, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ddda4255d1](https://linux-hardware.org/?probe=ddda4255d1) | Jun 19, 2020 |
| Gigabyte      | H81M-S2PH                   | [871a6364d4](https://linux-hardware.org/?probe=871a6364d4) | Jun 19, 2020 |
| ASUSTek       | Q87M-E                      | [5b07966114](https://linux-hardware.org/?probe=5b07966114) | Jun 18, 2020 |
| MSI           | MS-7528                     | [dc65359d28](https://linux-hardware.org/?probe=dc65359d28) | Jun 11, 2020 |
| HP            | 805B                        | [442ee42078](https://linux-hardware.org/?probe=442ee42078) | Jun 10, 2020 |
| Biostar       | H61MLV2                     | [7c2d6cc69e](https://linux-hardware.org/?probe=7c2d6cc69e) | Jun 10, 2020 |
| Biostar       | H61MLV2                     | [707e32f26c](https://linux-hardware.org/?probe=707e32f26c) | Jun 09, 2020 |
| HP            | 83F3                        | [5338d0b301](https://linux-hardware.org/?probe=5338d0b301) | Jun 06, 2020 |
| Dell          | 0GDG8Y A00                  | [25d22f7216](https://linux-hardware.org/?probe=25d22f7216) | Jun 03, 2020 |
| Intel         | DG33FB AAD81072-306         | [e3bd459f84](https://linux-hardware.org/?probe=e3bd459f84) | Jun 01, 2020 |
| Intel         | DG33FB AAD81072-306         | [fcc918ad60](https://linux-hardware.org/?probe=fcc918ad60) | May 31, 2020 |
| Gigabyte      | B85M-HD3                    | [7cdfc70ee9](https://linux-hardware.org/?probe=7cdfc70ee9) | May 30, 2020 |
| Gigabyte      | B85M-HD3                    | [4b5ddc99c9](https://linux-hardware.org/?probe=4b5ddc99c9) | May 30, 2020 |
| Gigabyte      | H81M-S2PH                   | [45b32108e4](https://linux-hardware.org/?probe=45b32108e4) | May 27, 2020 |
| ASUSTek       | P8H61-M LX                  | [cb9d706df6](https://linux-hardware.org/?probe=cb9d706df6) | May 26, 2020 |
| ECS           | H55H-M                      | [077724dbf5](https://linux-hardware.org/?probe=077724dbf5) | May 20, 2020 |
| ECS           | H55H-M                      | [a1eede754f](https://linux-hardware.org/?probe=a1eede754f) | May 20, 2020 |
| Unknown       | P4M800Pro-8237              | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| Intel         | DQ57TM AAE70931-402         | [b8442a4625](https://linux-hardware.org/?probe=b8442a4625) | May 17, 2020 |
| Unknown       | P4M800Pro-8237              | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| ECS           | G41T-M                      | [6349e4f073](https://linux-hardware.org/?probe=6349e4f073) | May 13, 2020 |
| Gigabyte      | H77M-D3H                    | [de237bc9f1](https://linux-hardware.org/?probe=de237bc9f1) | May 12, 2020 |
| HP            | 1495                        | [6829e49d1b](https://linux-hardware.org/?probe=6829e49d1b) | May 12, 2020 |
| Biostar       | TB250-BTC PRO               | [7274c8e573](https://linux-hardware.org/?probe=7274c8e573) | May 12, 2020 |
| HP            | 1495                        | [bdada1df43](https://linux-hardware.org/?probe=bdada1df43) | May 11, 2020 |
| ASUSTek       | Q87M-E                      | [4aab40e3ef](https://linux-hardware.org/?probe=4aab40e3ef) | May 09, 2020 |
| ASUSTek       | P5N-D                       | [d77f4b93e4](https://linux-hardware.org/?probe=d77f4b93e4) | May 07, 2020 |
| Lenovo        | ThinkCentre M57 6075WAU     | [1ceade6e83](https://linux-hardware.org/?probe=1ceade6e83) | May 06, 2020 |
| ASUSTek       | P8H61-I R2.0                | [1cbb308058](https://linux-hardware.org/?probe=1cbb308058) | May 06, 2020 |
| Intel         | DQ57TM AAE70931-403         | [ea3398787c](https://linux-hardware.org/?probe=ea3398787c) | May 06, 2020 |
| Intel         | DQ57TM AAE70931-403         | [4771e12533](https://linux-hardware.org/?probe=4771e12533) | May 05, 2020 |
| ASUSTek       | P8H61-I R2.0                | [a90f974870](https://linux-hardware.org/?probe=a90f974870) | May 05, 2020 |
| Intel         | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek       | M3A79-T DELUXE              | [d70c0d15c6](https://linux-hardware.org/?probe=d70c0d15c6) | Apr 30, 2020 |
| Lenovo        | MAHOBAY                     | [a9fa20578e](https://linux-hardware.org/?probe=a9fa20578e) | Apr 28, 2020 |
| Lenovo        | MAHOBAY                     | [bd69f0db96](https://linux-hardware.org/?probe=bd69f0db96) | Apr 28, 2020 |
| Intel         | DQ57TM AAE70931-402         | [346f94096c](https://linux-hardware.org/?probe=346f94096c) | Apr 27, 2020 |
| Nvidia        | MCP73                       | [df5be54153](https://linux-hardware.org/?probe=df5be54153) | Apr 27, 2020 |
| Intel         | DQ57TM AAE70931-402         | [da9fd9a546](https://linux-hardware.org/?probe=da9fd9a546) | Apr 27, 2020 |
| ASUSTek       | Maximus IX HERO             | [184ef341c4](https://linux-hardware.org/?probe=184ef341c4) | Apr 23, 2020 |
| ASUSTek       | Maximus IX HERO             | [2b950abd55](https://linux-hardware.org/?probe=2b950abd55) | Apr 23, 2020 |
| ASUSTek       | Maximus IX HERO             | [7e34d139fc](https://linux-hardware.org/?probe=7e34d139fc) | Apr 23, 2020 |
| Lenovo        | ThinkCentre A55 963672G     | [f33142fc46](https://linux-hardware.org/?probe=f33142fc46) | Apr 17, 2020 |
| MSI           | MS-7388                     | [1bf85fec38](https://linux-hardware.org/?probe=1bf85fec38) | Apr 17, 2020 |
| MSI           | B150M BAZOOKA               | [2bda20adc0](https://linux-hardware.org/?probe=2bda20adc0) | Apr 16, 2020 |
| MSI           | B150M BAZOOKA               | [d2e90e08eb](https://linux-hardware.org/?probe=d2e90e08eb) | Apr 16, 2020 |
| ASUSTek       | Q87M-E                      | [9998ec29fd](https://linux-hardware.org/?probe=9998ec29fd) | Apr 11, 2020 |
| ASUSTek       | Q87M-E                      | [8300430118](https://linux-hardware.org/?probe=8300430118) | Apr 10, 2020 |
| ASUSTek       | Q87M-E                      | [6d6740d6e5](https://linux-hardware.org/?probe=6d6740d6e5) | Apr 10, 2020 |
| ASUSTek       | Q87M-E                      | [70b7d8282a](https://linux-hardware.org/?probe=70b7d8282a) | Apr 10, 2020 |
| ASUSTek       | P5G41T-M LX3                | [31c445f67f](https://linux-hardware.org/?probe=31c445f67f) | Apr 09, 2020 |
| Lite-On       | 08FCh E01                   | [e5a23af168](https://linux-hardware.org/?probe=e5a23af168) | Apr 05, 2020 |
| Lite-On       | 08FCh E01                   | [b2adb5c48e](https://linux-hardware.org/?probe=b2adb5c48e) | Apr 05, 2020 |
| HP            | 805B                        | [2fe00b7859](https://linux-hardware.org/?probe=2fe00b7859) | Apr 03, 2020 |
| Intel         | DH87MC AAG74242-401         | [d6fec3460a](https://linux-hardware.org/?probe=d6fec3460a) | Mar 22, 2020 |
| ASUSTek       | P5Q-PRO                     | [0fb21440b5](https://linux-hardware.org/?probe=0fb21440b5) | Mar 15, 2020 |
| ASRock        | G31M-VS                     | [3256f062c5](https://linux-hardware.org/?probe=3256f062c5) | Mar 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [7668f2f550](https://linux-hardware.org/?probe=7668f2f550) | Mar 06, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [ccaffec62a](https://linux-hardware.org/?probe=ccaffec62a) | Mar 06, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [15b50d0d21](https://linux-hardware.org/?probe=15b50d0d21) | Mar 06, 2020 |
| Gigabyte      | Q270M-D3H                   | [8d63f92e6f](https://linux-hardware.org/?probe=8d63f92e6f) | Mar 03, 2020 |
| Gigabyte      | Q270M-D3H                   | [1a69b0489c](https://linux-hardware.org/?probe=1a69b0489c) | Mar 03, 2020 |
| Intel         | DH61WW AAG23116-303         | [fed0d77a30](https://linux-hardware.org/?probe=fed0d77a30) | Feb 04, 2020 |
| Gigabyte      | H81M-DS2                    | [2017ebe76b](https://linux-hardware.org/?probe=2017ebe76b) | Feb 02, 2020 |
| Biostar       | TPower X58                  | [94920b348a](https://linux-hardware.org/?probe=94920b348a) | Jan 28, 2020 |
| Gigabyte      | H81M-DS2                    | [f0fca4cc90](https://linux-hardware.org/?probe=f0fca4cc90) | Jan 28, 2020 |
| Gigabyte      | H81M-DS2                    | [d5427ab6fc](https://linux-hardware.org/?probe=d5427ab6fc) | Jan 27, 2020 |
| MSI           | Z97 PC Mate                 | [7b9527402d](https://linux-hardware.org/?probe=7b9527402d) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | B75M-D3V                    | [c900d7a6e2](https://linux-hardware.org/?probe=c900d7a6e2) | Jan 20, 2020 |
| HP            | ML150 G3                    | [b4f5ff56bd](https://linux-hardware.org/?probe=b4f5ff56bd) | Jan 09, 2020 |
| ASUSTek       | P5Q-PRO                     | [9cd8c465bf](https://linux-hardware.org/?probe=9cd8c465bf) | Jan 03, 2020 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [18674d7b06](https://linux-hardware.org/?probe=18674d7b06) | Dec 31, 2019 |
| Dell          | 0V8F20 A01                  | [0f87997cd1](https://linux-hardware.org/?probe=0f87997cd1) | Dec 18, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [84669a36b5](https://linux-hardware.org/?probe=84669a36b5) | Dec 18, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e87c9c3d58](https://linux-hardware.org/?probe=e87c9c3d58) | Dec 18, 2019 |
| Biostar       | H110MHV3                    | [8ae0080096](https://linux-hardware.org/?probe=8ae0080096) | Dec 14, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [688d57e1a1](https://linux-hardware.org/?probe=688d57e1a1) | Dec 06, 2019 |
| ASRock        | H61M-VS                     | [5da8f545aa](https://linux-hardware.org/?probe=5da8f545aa) | Nov 30, 2019 |
| Biostar       | H110MHV3                    | [7656b302ec](https://linux-hardware.org/?probe=7656b302ec) | Nov 26, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5783b5888e](https://linux-hardware.org/?probe=5783b5888e) | Oct 31, 2019 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [32f516b0a3](https://linux-hardware.org/?probe=32f516b0a3) | Oct 31, 2019 |
| Gigabyte      | EP45T-UD3LR                 | [4565af098e](https://linux-hardware.org/?probe=4565af098e) | Oct 26, 2019 |
| Gigabyte      | H55M-S2H                    | [09b0e06bf9](https://linux-hardware.org/?probe=09b0e06bf9) | Oct 09, 2019 |
| MSI           | X99S SLI PLUS               | [5ef345d877](https://linux-hardware.org/?probe=5ef345d877) | Sep 27, 2019 |
| Dell          | 0200DY A01                  | [bfea104c20](https://linux-hardware.org/?probe=bfea104c20) | Sep 26, 2019 |
| MSI           | X99S SLI PLUS               | [9c67e3a660](https://linux-hardware.org/?probe=9c67e3a660) | Sep 18, 2019 |
| HP            | 1632                        | [3f5304647a](https://linux-hardware.org/?probe=3f5304647a) | Sep 07, 2019 |
| Intel         | DG33FB AAD81072-307         | [53195aa497](https://linux-hardware.org/?probe=53195aa497) | Sep 01, 2019 |
| Intel         | DG33FB AAD81072-307         | [51521e9703](https://linux-hardware.org/?probe=51521e9703) | Sep 01, 2019 |
| Intel         | DG33FB AAD81072-307         | [941dc4e852](https://linux-hardware.org/?probe=941dc4e852) | Sep 01, 2019 |
| Intel         | D946GZIS AAD83227-402       | [ec6430c030](https://linux-hardware.org/?probe=ec6430c030) | Aug 29, 2019 |
| Gigabyte      | H55M-S2H                    | [e106c00a0a](https://linux-hardware.org/?probe=e106c00a0a) | Aug 27, 2019 |
| HP            | 304Bh                       | [0e9912689f](https://linux-hardware.org/?probe=0e9912689f) | Aug 23, 2019 |
| ASUSTek       | PRIME A320M-K               | [31e1665c16](https://linux-hardware.org/?probe=31e1665c16) | Aug 22, 2019 |
| Intel         | D946GZIS AAD83227-402       | [8053ea70b7](https://linux-hardware.org/?probe=8053ea70b7) | Aug 11, 2019 |
| Foxconn       | 2ABF                        | [ec9d343037](https://linux-hardware.org/?probe=ec9d343037) | Aug 03, 2019 |
| Dell          | 0Y2MRG A00                  | [fed40374f1](https://linux-hardware.org/?probe=fed40374f1) | Jul 19, 2019 |
| Gigabyte      | B360M D3H-CF                | [b1e690fc69](https://linux-hardware.org/?probe=b1e690fc69) | Jul 14, 2019 |
| ASUSTek       | Z170-K                      | [4fc2e905b4](https://linux-hardware.org/?probe=4fc2e905b4) | Jul 04, 2019 |
| ASUSTek       | Z170-K                      | [7eecce410f](https://linux-hardware.org/?probe=7eecce410f) | Jul 04, 2019 |
| Gigabyte      | G31M-S2C                    | [b4020c7021](https://linux-hardware.org/?probe=b4020c7021) | Jun 20, 2019 |
| Gigabyte      | G31M-S2C                    | [83ef6f0482](https://linux-hardware.org/?probe=83ef6f0482) | Jun 20, 2019 |
| Foxconn       | nT-iBT18_nT-iBT19_nT-iBT... | [0c90b25a45](https://linux-hardware.org/?probe=0c90b25a45) | May 28, 2019 |
| Dell          | 0V8F20 A01                  | [29eca9d63c](https://linux-hardware.org/?probe=29eca9d63c) | May 20, 2019 |
| Gigabyte      | B85M-HD3                    | [d5af14209b](https://linux-hardware.org/?probe=d5af14209b) | May 10, 2019 |
| ASUSTek       | H61M-E                      | [758b0583b1](https://linux-hardware.org/?probe=758b0583b1) | May 04, 2019 |
| Intel         | DQ57TM AAE70931-402         | [3135496cc0](https://linux-hardware.org/?probe=3135496cc0) | Apr 29, 2019 |
| ASUSTek       | P5G41T-M LX                 | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Dell          | 09KPNV A00                  | [bca2ebdbaf](https://linux-hardware.org/?probe=bca2ebdbaf) | Apr 03, 2019 |
| ASUSTek       | H81-GAMER                   | [27465fddb7](https://linux-hardware.org/?probe=27465fddb7) | Mar 28, 2019 |
| MSI           | Z370 SLI PLUS               | [ce19512cbb](https://linux-hardware.org/?probe=ce19512cbb) | Mar 18, 2019 |
| MSI           | Z370 SLI PLUS               | [38b37701fa](https://linux-hardware.org/?probe=38b37701fa) | Mar 18, 2019 |
| HP            | 1632                        | [8d82d4b75c](https://linux-hardware.org/?probe=8d82d4b75c) | Jan 30, 2019 |
| HP            | 1632                        | [24f2034cf5](https://linux-hardware.org/?probe=24f2034cf5) | Jan 26, 2019 |
| Lenovo        | ThinkCentre A57 97027LG     | [3f2f50064e](https://linux-hardware.org/?probe=3f2f50064e) | Dec 21, 2018 |
| Dell          | 0GDG8Y A00                  | [0491674dac](https://linux-hardware.org/?probe=0491674dac) | Nov 27, 2018 |
| Foxconn       | H55MXV Series               | [6b384caea8](https://linux-hardware.org/?probe=6b384caea8) | Nov 26, 2018 |
| Unknown       | NF-MCP61                    | [34b91208c5](https://linux-hardware.org/?probe=34b91208c5) | Oct 31, 2018 |
| HP            | ProLiant MicroServer        | [1dd894b330](https://linux-hardware.org/?probe=1dd894b330) | Oct 19, 2018 |
| HP            | ProLiant MicroServer        | [9d5778f932](https://linux-hardware.org/?probe=9d5778f932) | Oct 19, 2018 |
| ASUSTek       | P5QL-EM                     | [dcc6824dc1](https://linux-hardware.org/?probe=dcc6824dc1) | Feb 21, 2018 |
| MSI           | H81M-P33                    | [376a9193df](https://linux-hardware.org/?probe=376a9193df) | Jun 27, 2017 |
| Lenovo        | NO DPK                      | [21f98e8f6c](https://linux-hardware.org/?probe=21f98e8f6c) | May 07, 2017 |
| ASRock        | H61M-VS3                    | [c0b09d5096](https://linux-hardware.org/?probe=c0b09d5096) | Apr 29, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 69       | 21.56%  |
| Ubuntu 18.04      | 31       | 9.69%   |
| Pop!_OS 20.10     | 11       | 3.44%   |
| Linux Mint 19.3   | 10       | 3.13%   |
| Ubuntu 16.04      | 9        | 2.81%   |
| Pop!_OS 21.04     | 9        | 2.81%   |
| Pop!_OS 20.04     | 9        | 2.81%   |
| Manjaro           | 9        | 2.81%   |
| Zorin 15          | 8        | 2.5%    |
| OpenMandriva 4.2  | 7        | 2.19%   |
| Linux Mint 20.1   | 7        | 2.19%   |
| KDE neon 20.04    | 7        | 2.19%   |
| Ubuntu 21.04      | 6        | 1.88%   |
| Ubuntu 19.10      | 6        | 1.88%   |
| Zorin 16          | 5        | 1.56%   |
| OpenMandriva 4.3  | 5        | 1.56%   |
| Linux Mint 20.3   | 5        | 1.56%   |
| ArcoLinux Rolling | 5        | 1.56%   |
| Ubuntu 22.04      | 4        | 1.25%   |
| Pop!_OS 21.10     | 4        | 1.25%   |
| Linux Mint 19     | 4        | 1.25%   |
| Kubuntu 20.04     | 4        | 1.25%   |
| BlackPanther 18.1 | 4        | 1.25%   |
| Ubuntu 21.10      | 3        | 0.94%   |
| ROSA R9           | 3        | 0.94%   |
| ROSA R11.1        | 3        | 0.94%   |
| Linux Mint 19.2   | 3        | 0.94%   |
| Arch Rolling      | 3        | 0.94%   |
| Xubuntu 20.04     | 2        | 0.63%   |
| Ubuntu 20.10      | 2        | 0.63%   |
| Ubuntu 19.04      | 2        | 0.63%   |
| Ubuntu 18.10      | 2        | 0.63%   |
| Pop!_OS 22.04     | 2        | 0.63%   |
| OpenMandriva 4.50 | 2        | 0.63%   |
| Lubuntu 20.04     | 2        | 0.63%   |
| LinuxFX 10        | 2        | 0.63%   |
| Linux Mint 20     | 2        | 0.63%   |
| Kubuntu 22.04     | 2        | 0.63%   |
| Fedora 33         | 2        | 0.63%   |
| Debian 11         | 2        | 0.63%   |
| Debian 10         | 2        | 0.63%   |
| Arch              | 2        | 0.63%   |
| Xubuntu 21.10     | 1        | 0.31%   |
| Xubuntu 18.04     | 1        | 0.31%   |
| Ubuntu MATE 21.04 | 1        | 0.31%   |
| Ubuntu 14.04      | 1        | 0.31%   |
| Sparky 6          | 1        | 0.31%   |
| Slackware 15.0    | 1        | 0.31%   |
| ROSA R10          | 1        | 0.31%   |
| Rocky Linux 8.5   | 1        | 0.31%   |
| Q4OS 4            | 1        | 0.31%   |
| Manjaro 21.3.1    | 1        | 0.31%   |
| Manjaro 21.2.6    | 1        | 0.31%   |
| Manjaro 21.0.6    | 1        | 0.31%   |
| Manjaro 20.2.1    | 1        | 0.31%   |
| Manjaro 20.2      | 1        | 0.31%   |
| Manjaro 18.1.5    | 1        | 0.31%   |
| Lubuntu 18.04     | 1        | 0.31%   |
| LMDE 4            | 1        | 0.31%   |
| LinuxFX 11        | 1        | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 127      | 41.1%   |
| Pop!_OS      | 34       | 11%     |
| Linux Mint   | 33       | 10.68%  |
| OpenMandriva | 14       | 4.53%   |
| Zorin        | 13       | 4.21%   |
| Manjaro      | 13       | 4.21%   |
| KDE neon     | 8        | 2.59%   |
| ROSA         | 7        | 2.27%   |
| Kubuntu      | 6        | 1.94%   |
| Debian       | 6        | 1.94%   |
| Fedora       | 5        | 1.62%   |
| ArcoLinux    | 5        | 1.62%   |
| Arch         | 5        | 1.62%   |
| Xubuntu      | 4        | 1.29%   |
| BlackPanther | 4        | 1.29%   |
| Lubuntu      | 3        | 0.97%   |
| LinuxFX      | 3        | 0.97%   |
| Endless      | 2        | 0.65%   |
| Clear Linux  | 2        | 0.65%   |
| CentOS       | 2        | 0.65%   |
| Ubuntu MATE  | 1        | 0.32%   |
| Sparky       | 1        | 0.32%   |
| Slackware    | 1        | 0.32%   |
| Rocky Linux  | 1        | 0.32%   |
| Q4OS         | 1        | 0.32%   |
| LMDE         | 1        | 0.32%   |
| KaOS         | 1        | 0.32%   |
| Kali         | 1        | 0.32%   |
| Kaisen       | 1        | 0.32%   |
| Gentoo       | 1        | 0.32%   |
| Garuda Linux | 1        | 0.32%   |
| EndeavourOS  | 1        | 0.32%   |
| Elementary   | 1        | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.4.0-42-generic                | 13       | 3.65%   |
| 5.4.0-58-generic                | 7        | 1.97%   |
| 5.4.0-52-generic                | 7        | 1.97%   |
| 5.8.0-7642-generic              | 6        | 1.69%   |
| 5.13.0-7614-generic             | 6        | 1.69%   |
| 5.16.7-desktop-1omv4003         | 5        | 1.4%    |
| 5.11.0-40-generic               | 5        | 1.4%    |
| 5.10.14-desktop-1omv4002        | 5        | 1.4%    |
| 4.15.0-54-generic               | 5        | 1.4%    |
| 5.8.0-59-generic                | 4        | 1.12%   |
| 5.4.0-7634-generic              | 4        | 1.12%   |
| 5.4.0-72-generic                | 4        | 1.12%   |
| 5.4.0-54-generic                | 4        | 1.12%   |
| 5.3.0-46-generic                | 4        | 1.12%   |
| 5.11.0-41-generic               | 4        | 1.12%   |
| 5.11.0-27-generic               | 4        | 1.12%   |
| 5.11.0-25-generic               | 4        | 1.12%   |
| 4.18.16-desktop-1bP             | 4        | 1.12%   |
| 5.8.0-7630-generic              | 3        | 0.84%   |
| 5.8.0-43-generic                | 3        | 0.84%   |
| 5.4.0-45-generic                | 3        | 0.84%   |
| 5.4.0-37-generic                | 3        | 0.84%   |
| 5.3.0-53-generic                | 3        | 0.84%   |
| 5.13.0-28-generic               | 3        | 0.84%   |
| 5.11.0-7620-generic             | 3        | 0.84%   |
| 5.11.0-7614-generic             | 3        | 0.84%   |
| 5.11.0-38-generic               | 3        | 0.84%   |
| 5.0.0-37-generic                | 3        | 0.84%   |
| 4.15.0-112-generic              | 3        | 0.84%   |
| 5.8.0-55-generic                | 2        | 0.56%   |
| 5.8.0-40-generic                | 2        | 0.56%   |
| 5.4.0-77-generic                | 2        | 0.56%   |
| 5.4.0-7642-generic              | 2        | 0.56%   |
| 5.4.0-73-generic                | 2        | 0.56%   |
| 5.4.0-65-generic                | 2        | 0.56%   |
| 5.4.0-47-generic                | 2        | 0.56%   |
| 5.4.0-40-generic                | 2        | 0.56%   |
| 5.4.0-38-generic                | 2        | 0.56%   |
| 5.4.0-31-generic                | 2        | 0.56%   |
| 5.4.0-29-generic                | 2        | 0.56%   |
| 5.4.0-28-generic                | 2        | 0.56%   |
| 5.4.0-26-generic                | 2        | 0.56%   |
| 5.4.0-113-generic               | 2        | 0.56%   |
| 5.4.0-107-generic               | 2        | 0.56%   |
| 5.3.0-24-generic                | 2        | 0.56%   |
| 5.16.19-76051619-generic        | 2        | 0.56%   |
| 5.15.32-1-MANJARO               | 2        | 0.56%   |
| 5.15.3-1-clear                  | 2        | 0.56%   |
| 5.15.15-76051515-generic        | 2        | 0.56%   |
| 5.15.0-39-generic               | 2        | 0.56%   |
| 5.15.0-33-generic               | 2        | 0.56%   |
| 5.13.13-arch1-1                 | 2        | 0.56%   |
| 5.13.0-30-generic               | 2        | 0.56%   |
| 5.11.12-desktop-1omv4002        | 2        | 0.56%   |
| 5.11.0-37-generic               | 2        | 0.56%   |
| 5.0.0-25-generic                | 2        | 0.56%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2        | 0.56%   |
| 4.18.0-25-generic               | 2        | 0.56%   |
| 4.18.0-18-generic               | 2        | 0.56%   |
| 4.18.0-16-generic               | 2        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 83       | 25.15%  |
| 5.11.0   | 34       | 10.3%   |
| 4.15.0   | 31       | 9.39%   |
| 5.8.0    | 30       | 9.09%   |
| 5.13.0   | 18       | 5.45%   |
| 5.3.0    | 16       | 4.85%   |
| 4.18.0   | 12       | 3.64%   |
| 5.0.0    | 9        | 2.73%   |
| 5.15.0   | 6        | 1.82%   |
| 5.16.7   | 5        | 1.52%   |
| 5.10.14  | 5        | 1.52%   |
| 5.10.0   | 5        | 1.52%   |
| 4.4.0    | 5        | 1.52%   |
| 4.18.16  | 4        | 1.21%   |
| 4.9.20   | 3        | 0.91%   |
| 5.9.0    | 2        | 0.61%   |
| 5.6.0    | 2        | 0.61%   |
| 5.17.5   | 2        | 0.61%   |
| 5.17.1   | 2        | 0.61%   |
| 5.16.19  | 2        | 0.61%   |
| 5.15.5   | 2        | 0.61%   |
| 5.15.32  | 2        | 0.61%   |
| 5.15.3   | 2        | 0.61%   |
| 5.15.15  | 2        | 0.61%   |
| 5.13.13  | 2        | 0.61%   |
| 5.11.12  | 2        | 0.61%   |
| 4.19.0   | 2        | 0.61%   |
| 5.9.16   | 1        | 0.3%    |
| 5.8.15   | 1        | 0.3%    |
| 5.8.1    | 1        | 0.3%    |
| 5.6.7    | 1        | 0.3%    |
| 5.6.11   | 1        | 0.3%    |
| 5.5.19   | 1        | 0.3%    |
| 5.5.0    | 1        | 0.3%    |
| 5.4.80   | 1        | 0.3%    |
| 5.4.60   | 1        | 0.3%    |
| 5.4.44   | 1        | 0.3%    |
| 5.4.39   | 1        | 0.3%    |
| 5.4.32   | 1        | 0.3%    |
| 5.4.22   | 1        | 0.3%    |
| 5.4.14   | 1        | 0.3%    |
| 5.4.132  | 1        | 0.3%    |
| 5.16.11  | 1        | 0.3%    |
| 5.16.0   | 1        | 0.3%    |
| 5.15.7   | 1        | 0.3%    |
| 5.15.6   | 1        | 0.3%    |
| 5.15.4   | 1        | 0.3%    |
| 5.13.19  | 1        | 0.3%    |
| 5.12.9   | 1        | 0.3%    |
| 5.12.7   | 1        | 0.3%    |
| 5.12.4   | 1        | 0.3%    |
| 5.12.13  | 1        | 0.3%    |
| 5.11.16  | 1        | 0.3%    |
| 5.11.11  | 1        | 0.3%    |
| 5.10.56  | 1        | 0.3%    |
| 5.10.41  | 1        | 0.3%    |
| 5.10.18  | 1        | 0.3%    |
| 5.10.16  | 1        | 0.3%    |
| 5.10.123 | 1        | 0.3%    |
| 5.10.1   | 1        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 90       | 27.44%  |
| 5.11    | 38       | 11.59%  |
| 5.8     | 32       | 9.76%   |
| 4.15    | 31       | 9.45%   |
| 5.13    | 21       | 6.4%    |
| 5.15    | 17       | 5.18%   |
| 5.3     | 16       | 4.88%   |
| 4.18    | 16       | 4.88%   |
| 5.10    | 15       | 4.57%   |
| 5.16    | 9        | 2.74%   |
| 5.0     | 9        | 2.74%   |
| 4.9     | 5        | 1.52%   |
| 4.4     | 5        | 1.52%   |
| 5.6     | 4        | 1.22%   |
| 5.17    | 4        | 1.22%   |
| 5.12    | 4        | 1.22%   |
| 5.9     | 3        | 0.91%   |
| 4.19    | 3        | 0.91%   |
| 5.5     | 2        | 0.61%   |
| 5.1     | 1        | 0.3%    |
| 3.16    | 1        | 0.3%    |
| 3.13    | 1        | 0.3%    |
| 3.10    | 1        | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 293      | 96.38%  |
| i686   | 11       | 3.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 154      | 49.04%  |
| Unknown       | 46       | 14.65%  |
| KDE5          | 38       | 12.1%   |
| X-Cinnamon    | 24       | 7.64%   |
| XFCE          | 15       | 4.78%   |
| KDE           | 11       | 3.5%    |
| Unity         | 5        | 1.59%   |
| MATE          | 4        | 1.27%   |
| LXQt          | 3        | 0.96%   |
| LXDE          | 3        | 0.96%   |
| KDE4          | 3        | 0.96%   |
| i3            | 3        | 0.96%   |
| Cinnamon      | 2        | 0.64%   |
| trinity       | 1        | 0.32%   |
| Pantheon      | 1        | 0.32%   |
| GNOME Classic | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 262      | 85.34%  |
| Unknown | 19       | 6.19%   |
| Wayland | 18       | 5.86%   |
| Tty     | 8        | 2.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 220      | 70.29%  |
| SDDM    | 36       | 11.5%   |
| GDM3    | 24       | 7.67%   |
| GDM     | 12       | 3.83%   |
| TDM     | 10       | 3.19%   |
| LightDM | 8        | 2.56%   |
| KDM     | 3        | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_ZA   | 192      | 60.38%  |
| en_US   | 63       | 19.81%  |
| Unknown | 39       | 12.26%  |
| en_GB   | 10       | 3.14%   |
| C       | 7        | 2.2%    |
| en_ZW   | 5        | 1.57%   |
| af_ZA   | 2        | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 210      | 68.18%  |
| EFI  | 98       | 31.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 254      | 82.47%  |
| Overlay | 16       | 5.19%   |
| Unknown | 15       | 4.87%   |
| Btrfs   | 12       | 3.9%    |
| Xfs     | 7        | 2.27%   |
| Zfs     | 2        | 0.65%   |
| Tmpfs   | 1        | 0.32%   |
| Ext2    | 1        | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 228      | 75%     |
| GPT     | 50       | 16.45%  |
| MBR     | 26       | 8.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 259      | 83.82%  |
| Yes       | 50       | 16.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 210      | 68.18%  |
| Yes       | 98       | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 62       | 20.53%  |
| ASUSTek Computer    | 49       | 16.23%  |
| Gigabyte Technology | 44       | 14.57%  |
| Intel               | 34       | 11.26%  |
| Hewlett-Packard     | 20       | 6.62%   |
| Lenovo              | 16       | 5.3%    |
| Dell                | 16       | 5.3%    |
| ASRock              | 15       | 4.97%   |
| Biostar             | 12       | 3.97%   |
| Foxconn             | 10       | 3.31%   |
| ECS                 | 4        | 1.32%   |
| Acer                | 4        | 1.32%   |
| Unknown             | 4        | 1.32%   |
| Apple               | 3        | 0.99%   |
| Supermicro          | 2        | 0.66%   |
| NCR                 | 2        | 0.66%   |
| Fujitsu             | 2        | 0.66%   |
| Nvidia              | 1        | 0.33%   |
| Mustek6376 mst6376  | 1        | 0.33%   |
| Lite-On             | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 6        | 1.99%   |
| MSI MS-7817                 | 5        | 1.66%   |
| MSI MS-7B84                 | 4        | 1.32%   |
| Unknown                     | 4        | 1.32%   |
| MSI MS-7756                 | 3        | 0.99%   |
| HP ProLiant MicroServer     | 3        | 0.99%   |
| Gigabyte G31M-ES2C          | 3        | 0.99%   |
| Dell Vostro 3670            | 3        | 0.99%   |
| Apple MacPro3,1             | 3        | 0.99%   |
| MSI MS-7C91                 | 2        | 0.66%   |
| MSI MS-7C37                 | 2        | 0.66%   |
| MSI MS-7B89                 | 2        | 0.66%   |
| MSI MS-7A15                 | 2        | 0.66%   |
| MSI MS-7971                 | 2        | 0.66%   |
| MSI MS-7970                 | 2        | 0.66%   |
| MSI MS-7885                 | 2        | 0.66%   |
| MSI MS-7693                 | 2        | 0.66%   |
| MSI MS-7612                 | 2        | 0.66%   |
| Intel Mecer_X102            | 2        | 0.66%   |
| Intel H81                   | 2        | 0.66%   |
| Intel DH61WW AAG23116-300   | 2        | 0.66%   |
| Intel DH55TC AAE70932-302   | 2        | 0.66%   |
| Gigabyte XP-M5S661GX        | 2        | 0.66%   |
| Gigabyte H81M-S2PH          | 2        | 0.66%   |
| Gigabyte H61M-S2V-B3        | 2        | 0.66%   |
| Gigabyte H61M-DS2           | 2        | 0.66%   |
| Gigabyte G41MT-S2PT         | 2        | 0.66%   |
| Gigabyte G31M-S2L           | 2        | 0.66%   |
| Gigabyte B85M-HD3           | 2        | 0.66%   |
| Gigabyte B75M-D3H           | 2        | 0.66%   |
| ECS G31T-M7                 | 2        | 0.66%   |
| Dell OptiPlex 7040          | 2        | 0.66%   |
| ASUS PRIME X570-P           | 2        | 0.66%   |
| ASUS H110M-K                | 2        | 0.66%   |
| ASRock H61M-VS3             | 2        | 0.66%   |
| Supermicro X8STi            | 1        | 0.33%   |
| Supermicro SSG-6047R-E1R24N | 1        | 0.33%   |
| Nvidia MCP73                | 1        | 0.33%   |
| NCR xxxx-xxxx-xxxx          | 1        | 0.33%   |
| NCR 7606-1309-8801          | 1        | 0.33%   |
| Mustek6376 mst6376 945GZT-M | 1        | 0.33%   |
| MSI MS-7C94                 | 1        | 0.33%   |
| MSI MS-7C60                 | 1        | 0.33%   |
| MSI MS-7C56                 | 1        | 0.33%   |
| MSI MS-7C13                 | 1        | 0.33%   |
| MSI MS-7B93                 | 1        | 0.33%   |
| MSI MS-7B90                 | 1        | 0.33%   |
| MSI MS-7B79                 | 1        | 0.33%   |
| MSI MS-7B46                 | 1        | 0.33%   |
| MSI MS-7B45                 | 1        | 0.33%   |
| MSI MS-7B38                 | 1        | 0.33%   |
| MSI MS-7B22                 | 1        | 0.33%   |
| MSI MS-7B17                 | 1        | 0.33%   |
| MSI MS-7A67                 | 1        | 0.33%   |
| MSI MS-7A39                 | 1        | 0.33%   |
| MSI MS-7A37                 | 1        | 0.33%   |
| MSI MS-7A33                 | 1        | 0.33%   |
| MSI MS-7A32                 | 1        | 0.33%   |
| MSI MS-7996                 | 1        | 0.33%   |
| MSI MS-7984                 | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Lenovo ThinkCentre          | 16       | 5.3%    |
| Dell OptiPlex               | 9        | 2.98%   |
| HP Compaq                   | 8        | 2.65%   |
| ASUS PRIME                  | 6        | 1.99%   |
| ASUS All                    | 6        | 1.99%   |
| MSI MS-7817                 | 5        | 1.66%   |
| HP ProLiant                 | 5        | 1.66%   |
| MSI MS-7B84                 | 4        | 1.32%   |
| Dell Vostro                 | 4        | 1.32%   |
| ASUS ROG                    | 4        | 1.32%   |
| Unknown                     | 4        | 1.32%   |
| MSI MS-7756                 | 3        | 0.99%   |
| Intel Mecer                 | 3        | 0.99%   |
| Intel DH61WW                | 3        | 0.99%   |
| Intel DH55TC                | 3        | 0.99%   |
| Gigabyte G31M-ES2C          | 3        | 0.99%   |
| ASUS H110M-K                | 3        | 0.99%   |
| Apple MacPro3               | 3        | 0.99%   |
| Acer Aspire                 | 3        | 0.99%   |
| MSI MS-7C91                 | 2        | 0.66%   |
| MSI MS-7C37                 | 2        | 0.66%   |
| MSI MS-7B89                 | 2        | 0.66%   |
| MSI MS-7A15                 | 2        | 0.66%   |
| MSI MS-7971                 | 2        | 0.66%   |
| MSI MS-7970                 | 2        | 0.66%   |
| MSI MS-7885                 | 2        | 0.66%   |
| MSI MS-7693                 | 2        | 0.66%   |
| MSI MS-7612                 | 2        | 0.66%   |
| Intel H81                   | 2        | 0.66%   |
| Intel DH55HC                | 2        | 0.66%   |
| Intel DG33FB                | 2        | 0.66%   |
| Intel DG31PR                | 2        | 0.66%   |
| Gigabyte XP-M5S661GX        | 2        | 0.66%   |
| Gigabyte H81M-S2PH          | 2        | 0.66%   |
| Gigabyte H61M-S2V-B3        | 2        | 0.66%   |
| Gigabyte H61M-DS2           | 2        | 0.66%   |
| Gigabyte G41MT-S2PT         | 2        | 0.66%   |
| Gigabyte G31M-S2L           | 2        | 0.66%   |
| Gigabyte B85M-HD3           | 2        | 0.66%   |
| Gigabyte B75M-D3H           | 2        | 0.66%   |
| Foxconn Pro                 | 2        | 0.66%   |
| ECS G31T-M7                 | 2        | 0.66%   |
| Biostar TB250-BTC           | 2        | 0.66%   |
| ASUS SABERTOOTH             | 2        | 0.66%   |
| ASUS P8H61-M                | 2        | 0.66%   |
| ASUS P5G41T-M               | 2        | 0.66%   |
| ASRock H61M-VS3             | 2        | 0.66%   |
| Supermicro X8STi            | 1        | 0.33%   |
| Supermicro SSG-6047R-E1R24N | 1        | 0.33%   |
| Nvidia MCP73                | 1        | 0.33%   |
| NCR xxxx-xxxx-xxxx          | 1        | 0.33%   |
| NCR 7606-1309-8801          | 1        | 0.33%   |
| Mustek6376 mst6376 945GZT-M | 1        | 0.33%   |
| MSI MS-7C94                 | 1        | 0.33%   |
| MSI MS-7C60                 | 1        | 0.33%   |
| MSI MS-7C56                 | 1        | 0.33%   |
| MSI MS-7C13                 | 1        | 0.33%   |
| MSI MS-7B93                 | 1        | 0.33%   |
| MSI MS-7B90                 | 1        | 0.33%   |
| MSI MS-7B79                 | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 40       | 13.25%  |
| 2011 | 33       | 10.93%  |
| 2013 | 29       | 9.6%    |
| 2010 | 25       | 8.28%   |
| 2008 | 24       | 7.95%   |
| 2018 | 22       | 7.28%   |
| 2016 | 21       | 6.95%   |
| 2017 | 17       | 5.63%   |
| 2009 | 17       | 5.63%   |
| 2007 | 16       | 5.3%    |
| 2019 | 13       | 4.3%    |
| 2015 | 13       | 4.3%    |
| 2014 | 11       | 3.64%   |
| 2020 | 8        | 2.65%   |
| 2006 | 7        | 2.32%   |
| 2005 | 3        | 0.99%   |
| 2022 | 1        | 0.33%   |
| 2021 | 1        | 0.33%   |
| 2004 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 302      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 296      | 97.69%  |
| Enabled  | 7        | 2.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 302      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 74       | 24.18%  |
| 8.01-16.0   | 68       | 22.22%  |
| 16.01-24.0  | 61       | 19.93%  |
| 4.01-8.0    | 47       | 15.36%  |
| 1.01-2.0    | 22       | 7.19%   |
| 32.01-64.0  | 21       | 6.86%   |
| 24.01-32.0  | 5        | 1.63%   |
| 64.01-256.0 | 3        | 0.98%   |
| 0.51-1.0    | 3        | 0.98%   |
| 2.01-3.0    | 2        | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 159      | 47.75%  |
| 2.01-3.0    | 66       | 19.82%  |
| 4.01-8.0    | 39       | 11.71%  |
| 3.01-4.0    | 26       | 7.81%   |
| 0.51-1.0    | 26       | 7.81%   |
| 8.01-16.0   | 8        | 2.4%    |
| 0.01-0.5    | 6        | 1.8%    |
| 64.01-256.0 | 1        | 0.3%    |
| 16.01-24.0  | 1        | 0.3%    |
| Unknown     | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 117      | 37.14%  |
| 2       | 95       | 30.16%  |
| 3       | 48       | 15.24%  |
| 4       | 32       | 10.16%  |
| 5       | 6        | 1.9%    |
| 8       | 4        | 1.27%   |
| 7       | 4        | 1.27%   |
| 6       | 4        | 1.27%   |
| 0       | 4        | 1.27%   |
| Unknown | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 54.05%  |
| Yes       | 142      | 45.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 298      | 98.68%  |
| No        | 4        | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 198      | 64.5%   |
| Yes       | 109      | 35.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 85.67%  |
| Yes       | 44       | 14.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| South Africa | 302      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Cape Town        | 80       | 25.32%  |
| Johannesburg     | 64       | 20.25%  |
| Pretoria         | 49       | 15.51%  |
| Durban           | 16       | 5.06%   |
| Centurion        | 14       | 4.43%   |
| Port Elizabeth   | 6        | 1.9%    |
| Kempton Park     | 5        | 1.58%   |
| Benoni           | 5        | 1.58%   |
| Alberton         | 5        | 1.58%   |
| Pietermaritzburg | 4        | 1.27%   |
| Bellville        | 4        | 1.27%   |
| Stellenbosch     | 3        | 0.95%   |
| Sasolburg        | 3        | 0.95%   |
| Midrand          | 3        | 0.95%   |
| Westville        | 2        | 0.63%   |
| Vanderbijlpark   | 2        | 0.63%   |
| Roodepoort       | 2        | 0.63%   |
| Randburg         | 2        | 0.63%   |
| Plettenberg Bay  | 2        | 0.63%   |
| Oudtshoorn       | 2        | 0.63%   |
| Germiston        | 2        | 0.63%   |
| George           | 2        | 0.63%   |
| Edenvale         | 2        | 0.63%   |
| East London      | 2        | 0.63%   |
| Boksburg         | 2        | 0.63%   |
| Bloemfontein     | 2        | 0.63%   |
| Zeerust          | 1        | 0.32%   |
| Uitenhage        | 1        | 0.32%   |
| Thabazimbi       | 1        | 0.32%   |
| Somerset West    | 1        | 0.32%   |
| Sir Lowry's Pass | 1        | 0.32%   |
| Secunda          | 1        | 0.32%   |
| Sandton          | 1        | 0.32%   |
| Rustenburg       | 1        | 0.32%   |
| Richards Bay     | 1        | 0.32%   |
| Queenstown       | 1        | 0.32%   |
| Polokwane        | 1        | 0.32%   |
| Paarl            | 1        | 0.32%   |
| Nottingham Road  | 1        | 0.32%   |
| Newcastle        | 1        | 0.32%   |
| Nelspruit        | 1        | 0.32%   |
| Musgrave         | 1        | 0.32%   |
| Mulbarton        | 1        | 0.32%   |
| Mossel Bay       | 1        | 0.32%   |
| Modimolle        | 1        | 0.32%   |
| Mid-Ennerdale    | 1        | 0.32%   |
| Marquard         | 1        | 0.32%   |
| Louis Trichardt  | 1        | 0.32%   |
| Lichtenburg      | 1        | 0.32%   |
| Laudium          | 1        | 0.32%   |
| Krugersdorp      | 1        | 0.32%   |
| Katlehong        | 1        | 0.32%   |
| Hermanus         | 1        | 0.32%   |
| Groot-Brakrivier | 1        | 0.32%   |
| Gansbaai         | 1        | 0.32%   |
| Durbanville      | 1        | 0.32%   |
| Apel             | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 154      | 287    | 29.17%  |
| WDC                   | 141      | 208    | 26.7%   |
| Samsung Electronics   | 72       | 106    | 13.64%  |
| Toshiba               | 28       | 37     | 5.3%    |
| Hitachi               | 19       | 32     | 3.6%    |
| Transcend             | 9        | 13     | 1.7%    |
| Kingston              | 9        | 10     | 1.7%    |
| A-DATA Technology     | 9        | 10     | 1.7%    |
| Crucial               | 7        | 9      | 1.33%   |
| Silicon Motion        | 6        | 7      | 1.14%   |
| Maxtor                | 6        | 7      | 1.14%   |
| HGST                  | 6        | 7      | 1.14%   |
| Hewlett-Packard       | 6        | 6      | 1.14%   |
| TO Exter              | 5        | 5      | 0.95%   |
| SanDisk               | 5        | 5      | 0.95%   |
| SK hynix              | 4        | 4      | 0.76%   |
| Phison                | 4        | 6      | 0.76%   |
| Kingmax               | 4        | 5      | 0.76%   |
| HS-SSD-E100           | 3        | 4      | 0.57%   |
| HS-SSD-C100           | 3        | 3      | 0.57%   |
| Unknown               | 2        | 3      | 0.38%   |
| Realtek Semiconductor | 2        | 2      | 0.38%   |
| Mushkin               | 2        | 2      | 0.38%   |
| Intel                 | 2        | 2      | 0.38%   |
| Hikvision             | 2        | 2      | 0.38%   |
| Corsair               | 2        | 4      | 0.38%   |
| USB                   | 1        | 1      | 0.19%   |
| SOLIDATA              | 1        | 1      | 0.19%   |
| Plextor               | 1        | 2      | 0.19%   |
| OCZ                   | 1        | 2      | 0.19%   |
| Micron Technology     | 1        | 1      | 0.19%   |
| LITEON                | 1        | 1      | 0.19%   |
| KingSpec              | 1        | 2      | 0.19%   |
| HPE                   | 1        | 2      | 0.19%   |
| Gigabyte Technology   | 1        | 1      | 0.19%   |
| Fujitsu               | 1        | 1      | 0.19%   |
| External              | 1        | 1      | 0.19%   |
| Biostar               | 1        | 1      | 0.19%   |
| ASMT                  | 1        | 1      | 0.19%   |
| Apacer                | 1        | 2      | 0.19%   |
| Acer                  | 1        | 1      | 0.19%   |
| Unknown               | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 19       | 2.98%   |
| Seagate ST3500418AS 500GB           | 14       | 2.2%    |
| Seagate ST380815AS 80GB             | 10       | 1.57%   |
| Samsung HD103SI 1TB                 | 9        | 1.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 8        | 1.26%   |
| WDC WD10EZEX-08WN4A0 1TB            | 8        | 1.26%   |
| Seagate ST3500413AS 500GB           | 8        | 1.26%   |
| Seagate ST4000DM000-1F2168 4TB      | 7        | 1.1%    |
| Seagate ST3250318AS 250GB           | 7        | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB      | 7        | 1.1%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 6        | 0.94%   |
| WDC WD20EARX-00PASB0 2TB            | 6        | 0.94%   |
| Seagate ST4000DM004-2CV104 4TB      | 6        | 0.94%   |
| Seagate ST3160815AS 160GB           | 6        | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB      | 6        | 0.94%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 5        | 0.78%   |
| WDC WD20EZRX-00D8PB0 2TB            | 5        | 0.78%   |
| TO Exter nal USB 3.0 256GB          | 5        | 0.78%   |
| Seagate ST31500341AS 1TB            | 5        | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 0.78%   |
| Samsung SSD 850 EVO 250GB           | 5        | 0.78%   |
| Samsung HD502HI 500GB               | 5        | 0.78%   |
| WDC WD10EZEX-00WN4A0 1TB            | 4        | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 0.63%   |
| Toshiba MQ01ABD100 1TB              | 4        | 0.63%   |
| Toshiba HDWD110 1TB                 | 4        | 0.63%   |
| Toshiba DT01ACA100 1TB              | 4        | 0.63%   |
| Seagate ST3320620AS 320GB           | 4        | 0.63%   |
| Seagate ST3250310AS 250GB           | 4        | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 0.63%   |
| Samsung SSD 750 EVO 250GB           | 4        | 0.63%   |
| Samsung HM321HI 320GB               | 4        | 0.63%   |
| Samsung HD204UI 2TB                 | 4        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 3        | 0.47%   |
| WDC WD5000AVVS-63ZWB0 500GB         | 3        | 0.47%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 3        | 0.47%   |
| WDC WD3200AAJS-00RYA0 320GB         | 3        | 0.47%   |
| WDC WD10EZEX-00MFCA0 1TB            | 3        | 0.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.47%   |
| Seagate ST3160813AS 160GB           | 3        | 0.47%   |
| Seagate ST3160811AS 160GB           | 3        | 0.47%   |
| Seagate ST31000528AS 1TB            | 3        | 0.47%   |
| Seagate ST31000524AS 1TB            | 3        | 0.47%   |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 0.47%   |
| Seagate Expansion+ Desk 4TB         | 3        | 0.47%   |
| Seagate Expansion 1TB               | 3        | 0.47%   |
| Samsung SSD 860 EVO 250GB           | 3        | 0.47%   |
| Samsung NVMe SSD Drive 250GB        | 3        | 0.47%   |
| HGST HTS545050A7E680 500GB          | 3        | 0.47%   |
| HP VB0250EAVER 250GB                | 3        | 0.47%   |
| Crucial CT250MX500SSD1 250GB        | 3        | 0.47%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 2        | 0.31%   |
| WDC WD800JD-00LSA5 80GB             | 2        | 0.31%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 2        | 0.31%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 2        | 0.31%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 2        | 0.31%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 0.31%   |
| WDC WD30EZRZ-00Z5HB0 3TB            | 2        | 0.31%   |
| WDC WD30EZRX-00MMMB0 3TB            | 2        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 152      | 280    | 39.07%  |
| WDC                 | 125      | 181    | 32.13%  |
| Samsung Electronics | 43       | 62     | 11.05%  |
| Toshiba             | 27       | 36     | 6.94%   |
| Hitachi             | 19       | 32     | 4.88%   |
| Maxtor              | 6        | 7      | 1.54%   |
| HGST                | 6        | 7      | 1.54%   |
| Hewlett-Packard     | 5        | 5      | 1.29%   |
| Unknown             | 2        | 3      | 0.51%   |
| USB                 | 1        | 1      | 0.26%   |
| HPE                 | 1        | 2      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 27     | 21.5%   |
| Samsung Electronics | 23       | 32     | 21.5%   |
| Transcend           | 8        | 12     | 7.48%   |
| A-DATA Technology   | 8        | 9      | 7.48%   |
| Kingston            | 7        | 8      | 6.54%   |
| Crucial             | 7        | 9      | 6.54%   |
| TO Exter            | 5        | 5      | 4.67%   |
| Kingmax             | 4        | 5      | 3.74%   |
| SK hynix            | 2        | 2      | 1.87%   |
| SanDisk             | 2        | 2      | 1.87%   |
| Mushkin             | 2        | 2      | 1.87%   |
| HS-SSD-E100         | 2        | 2      | 1.87%   |
| Toshiba             | 1        | 1      | 0.93%   |
| SOLIDATA            | 1        | 1      | 0.93%   |
| Plextor             | 1        | 2      | 0.93%   |
| OCZ                 | 1        | 2      | 0.93%   |
| Micron Technology   | 1        | 1      | 0.93%   |
| LITEON              | 1        | 1      | 0.93%   |
| KingSpec            | 1        | 2      | 0.93%   |
| Intel               | 1        | 1      | 0.93%   |
| Gigabyte Technology | 1        | 1      | 0.93%   |
| Corsair             | 1        | 3      | 0.93%   |
| Biostar             | 1        | 1      | 0.93%   |
| Apacer              | 1        | 2      | 0.93%   |
| Acer                | 1        | 1      | 0.93%   |
| Unknown             | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 262      | 618    | 67.7%   |
| SSD     | 85       | 135    | 21.96%  |
| NVMe    | 34       | 45     | 8.79%   |
| Unknown | 6        | 9      | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 288      | 732    | 84.71%  |
| NVMe | 33       | 44     | 9.71%   |
| SAS  | 19       | 31     | 5.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 228      | 401    | 50.55%  |
| 0.51-1.0   | 117      | 185    | 25.94%  |
| 1.01-2.0   | 53       | 77     | 11.75%  |
| 3.01-4.0   | 28       | 50     | 6.21%   |
| 2.01-3.0   | 17       | 19     | 3.77%   |
| 4.01-10.0  | 6        | 17     | 1.33%   |
| 10.01-20.0 | 2        | 4      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 74       | 23.27%  |
| 251-500        | 63       | 19.81%  |
| 501-1000       | 41       | 12.89%  |
| More than 3000 | 37       | 11.64%  |
| 1001-2000      | 36       | 11.32%  |
| 1-20           | 19       | 5.97%   |
| 2001-3000      | 18       | 5.66%   |
| 51-100         | 14       | 4.4%    |
| 21-50          | 8        | 2.52%   |
| Unknown        | 8        | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 112      | 34.46%  |
| 21-50          | 39       | 12%     |
| 101-250        | 38       | 11.69%  |
| 51-100         | 31       | 9.54%   |
| 251-500        | 29       | 8.92%   |
| 1001-2000      | 20       | 6.15%   |
| More than 3000 | 18       | 5.54%   |
| 501-1000       | 18       | 5.54%   |
| 2001-3000      | 12       | 3.69%   |
| Unknown        | 8        | 2.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB           | 3        | 4      | 7.69%   |
| WDC WD3200AAJS-00RYA0 320GB         | 2        | 2      | 5.13%   |
| WDC WD6400AAKS-75A7B0 640GB         | 1        | 1      | 2.56%   |
| WDC WD5000AVVS-63ZWB0 500GB         | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-221CA1 500GB         | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 2      | 2.56%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1        | 1      | 2.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1      | 2.56%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 2.56%   |
| WDC WD1600AAJS-08L7A0 160GB         | 1        | 1      | 2.56%   |
| WDC WD15EADS-00P8B0 1TB             | 1        | 1      | 2.56%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1      | 2.56%   |
| WDC WD10EADS-67M2B0 1TB             | 1        | 2      | 2.56%   |
| WDC WD10EACS-00ZJB0 1TB             | 1        | 1      | 2.56%   |
| Transcend TS64GSSD720 64GB          | 1        | 1      | 2.56%   |
| SOLIDATA SSD 120GB                  | 1        | 1      | 2.56%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 2.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 2.56%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 2.56%   |
| Seagate ST4000DM000-1F2168 4TB      | 1        | 2      | 2.56%   |
| Seagate ST3320418AS 320GB           | 1        | 1      | 2.56%   |
| Seagate ST32000542AS 2TB            | 1        | 1      | 2.56%   |
| Seagate ST3160815AS 160GB           | 1        | 2      | 2.56%   |
| Seagate ST31500341AS 1TB            | 1        | 1      | 2.56%   |
| Seagate ST31000520AS 1TB            | 1        | 1      | 2.56%   |
| Seagate ST3000DM001-1CH166 3TB      | 1        | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 1      | 2.56%   |
| Samsung Electronics HD203WI 2TB     | 1        | 1      | 2.56%   |
| Samsung Electronics HD154UI 1TB     | 1        | 1      | 2.56%   |
| Samsung Electronics HD103SI 1TB     | 1        | 2      | 2.56%   |
| Hitachi HDS721010KLA33R RSD HUA 1TB | 1        | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB          | 1        | 1      | 2.56%   |
| Hewlett-Packard SSD EX900 250GB     | 1        | 1      | 2.56%   |
| Hewlett-Packard GB0250EAFYK 250GB   | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 17     | 38.46%  |
| Seagate             | 15       | 18     | 38.46%  |
| Samsung Electronics | 3        | 4      | 7.69%   |
| Hewlett-Packard     | 2        | 2      | 5.13%   |
| Transcend           | 1        | 1      | 2.56%   |
| SOLIDATA            | 1        | 1      | 2.56%   |
| Hitachi             | 1        | 1      | 2.56%   |
| HGST                | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 17     | 41.67%  |
| Seagate             | 15       | 18     | 41.67%  |
| Samsung Electronics | 3        | 4      | 8.33%   |
| Hitachi             | 1        | 1      | 2.78%   |
| HGST                | 1        | 1      | 2.78%   |
| Hewlett-Packard     | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 42     | 90.91%  |
| SSD  | 2        | 2      | 6.06%   |
| NVMe | 1        | 1      | 3.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB | 2        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 234      | 626    | 70.48%  |
| Works    | 65       | 134    | 19.58%  |
| Malfunc  | 31       | 45     | 9.34%   |
| Failed   | 2        | 2      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 237      | 63.2%   |
| AMD                              | 52       | 13.87%  |
| Samsung Electronics              | 12       | 3.2%    |
| Marvell Technology Group         | 10       | 2.67%   |
| JMicron Technology               | 10       | 2.67%   |
| Silicon Motion                   | 9        | 2.4%    |
| Nvidia                           | 9        | 2.4%    |
| ASMedia Technology               | 9        | 2.4%    |
| Phison Electronics               | 6        | 1.6%    |
| VIA Technologies                 | 3        | 0.8%    |
| SanDisk                          | 3        | 0.8%    |
| SK hynix                         | 2        | 0.53%   |
| Silicon Integrated Systems [SiS] | 2        | 0.53%   |
| Silicon Image                    | 2        | 0.53%   |
| Seagate Technology               | 2        | 0.53%   |
| Realtek Semiconductor            | 2        | 0.53%   |
| Kingston Technology Company      | 2        | 0.53%   |
| LSI Logic / Symbios Logic        | 1        | 0.27%   |
| Broadcom / LSI                   | 1        | 0.27%   |
| ADATA Technology                 | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32       | 6.07%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 5.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26       | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26       | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26       | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 25       | 4.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 4.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 3.98%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 3.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 2.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 2.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 11       | 2.09%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 11       | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.09%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 9        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1.52%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 6        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6        | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 1.14%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 5        | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.95%   |
| AMD FCH SATA Controller D                                                               | 5        | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.76%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.76%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 4        | 0.76%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 4        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 0.76%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.57%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 3        | 0.57%   |
| Nvidia MCP51 IDE                                                                        | 3        | 0.57%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.57%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.57%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.57%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 2        | 0.38%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]               | 2        | 0.38%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2        | 0.38%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.38%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.38%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.38%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 0.38%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.38%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.38%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.38%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.38%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 184      | 48.81%  |
| IDE  | 131      | 34.75%  |
| NVMe | 35       | 9.28%   |
| RAID | 23       | 6.1%    |
| SAS  | 2        | 0.53%   |
| SCSI | 2        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 245      | 81.13%  |
| AMD    | 57       | 18.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 2.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 2.98%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 8        | 2.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 6        | 1.99%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 1.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 1.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 1.32%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 1.32%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.32%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 1.32%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 1.32%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 1.32%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 4        | 1.32%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.32%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 3        | 0.99%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.99%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3        | 0.99%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 3        | 0.99%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 3        | 0.99%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 3        | 0.99%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.99%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.99%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 0.99%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 0.99%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 0.99%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 3        | 0.99%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.99%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2        | 0.66%   |
| Intel Pentium CPU G850 @ 2.90GHz            | 2        | 0.66%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 2        | 0.66%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.66%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2        | 0.66%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 2        | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.66%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.66%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.66%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.66%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.66%   |
| Intel Core 2 Duo CPU E8200 @ 2.66GHz        | 2        | 0.66%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 0.66%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 2        | 0.66%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 2        | 0.66%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 2        | 0.66%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.66%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 0.66%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 59       | 19.54%  |
| Intel Core i7           | 50       | 16.56%  |
| Intel Core i3           | 34       | 11.26%  |
| Intel Pentium           | 21       | 6.95%   |
| Intel Core 2 Duo        | 21       | 6.95%   |
| AMD Ryzen 5             | 18       | 5.96%   |
| Intel Xeon              | 13       | 4.3%    |
| Intel Core 2 Quad       | 11       | 3.64%   |
| Intel Celeron           | 11       | 3.64%   |
| AMD Ryzen 7             | 8        | 2.65%   |
| Intel Pentium 4         | 7        | 2.32%   |
| Intel Pentium Dual-Core | 6        | 1.99%   |
| AMD FX                  | 6        | 1.99%   |
| AMD Ryzen 9             | 5        | 1.66%   |
| Intel Pentium Dual      | 4        | 1.32%   |
| AMD Turion II Neo       | 3        | 0.99%   |
| AMD Ryzen 3             | 3        | 0.99%   |
| AMD Athlon 64 X2        | 3        | 0.99%   |
| Other                   | 2        | 0.66%   |
| Intel Pentium D         | 2        | 0.66%   |
| Intel Core 2            | 2        | 0.66%   |
| AMD Phenom II X4        | 2        | 0.66%   |
| AMD Phenom II X2        | 2        | 0.66%   |
| Intel Genuine           | 1        | 0.33%   |
| Intel Core 2 Extreme    | 1        | 0.33%   |
| Intel Celeron D         | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Phenom II X3        | 1        | 0.33%   |
| AMD Athlon 64           | 1        | 0.33%   |
| AMD A8                  | 1        | 0.33%   |
| AMD A12                 | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 126      | 41.72%  |
| 2      | 113      | 37.42%  |
| 6      | 26       | 8.61%   |
| 8      | 13       | 4.3%    |
| 1      | 13       | 4.3%    |
| 12     | 4        | 1.32%   |
| 16     | 3        | 0.99%   |
| 3      | 3        | 0.99%   |
| 24     | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 297      | 98.34%  |
| 2      | 5        | 1.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 52.98%  |
| 2      | 142      | 47.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 294      | 96.71%  |
| Unknown        | 8        | 2.63%   |
| 32-bit         | 2        | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 23.49%  |
| 0x306a9    | 36       | 11.43%  |
| 0x206a7    | 26       | 8.25%   |
| 0x306c3    | 22       | 6.98%   |
| 0x506e3    | 16       | 5.08%   |
| 0x1067a    | 14       | 4.44%   |
| 0x10676    | 10       | 3.17%   |
| 0x906e9    | 9        | 2.86%   |
| 0x6fb      | 9        | 2.86%   |
| 0x906ea    | 8        | 2.54%   |
| 0x20652    | 8        | 2.54%   |
| 0x6fd      | 7        | 2.22%   |
| 0x08701021 | 7        | 2.22%   |
| 0x106a5    | 6        | 1.9%    |
| 0x010000db | 5        | 1.59%   |
| 0x20655    | 4        | 1.27%   |
| 0x106e5    | 4        | 1.27%   |
| 0x0800820d | 4        | 1.27%   |
| 0x06000852 | 4        | 1.27%   |
| 0x0600611a | 3        | 0.95%   |
| 0x010000c8 | 3        | 0.95%   |
| 0xf65      | 2        | 0.63%   |
| 0xf41      | 2        | 0.63%   |
| 0x906eb    | 2        | 0.63%   |
| 0x6f2      | 2        | 0.63%   |
| 0x0a50000c | 2        | 0.63%   |
| 0x0a201016 | 2        | 0.63%   |
| 0x08108109 | 2        | 0.63%   |
| 0x08001137 | 2        | 0.63%   |
| 0xf64      | 1        | 0.32%   |
| 0xf4a      | 1        | 0.32%   |
| 0xf49      | 1        | 0.32%   |
| 0xf47      | 1        | 0.32%   |
| 0xf43      | 1        | 0.32%   |
| 0xf33      | 1        | 0.32%   |
| 0x90672    | 1        | 0.32%   |
| 0x706a1    | 1        | 0.32%   |
| 0x6f7      | 1        | 0.32%   |
| 0x306f2    | 1        | 0.32%   |
| 0x30678    | 1        | 0.32%   |
| 0x206d7    | 1        | 0.32%   |
| 0x206c2    | 1        | 0.32%   |
| 0x0a201006 | 1        | 0.32%   |
| 0x08600106 | 1        | 0.32%   |
| 0x0810100b | 1        | 0.32%   |
| 0x08101007 | 1        | 0.32%   |
| 0x08001138 | 1        | 0.32%   |
| 0x08001126 | 1        | 0.32%   |
| 0x0600084f | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 45       | 14.9%   |
| SandyBridge   | 33       | 10.93%  |
| Penryn        | 33       | 10.93%  |
| Haswell       | 30       | 9.93%   |
| KabyLake      | 24       | 7.95%   |
| Skylake       | 23       | 7.62%   |
| Core          | 20       | 6.62%   |
| Westmere      | 13       | 4.3%    |
| Zen 2         | 11       | 3.64%   |
| NetBurst      | 11       | 3.64%   |
| Nehalem       | 10       | 3.31%   |
| Zen           | 9        | 2.98%   |
| Zen+          | 8        | 2.65%   |
| Zen 3         | 8        | 2.65%   |
| K10           | 8        | 2.65%   |
| Piledriver    | 6        | 1.99%   |
| K8 Hammer     | 4        | 1.32%   |
| Excavator     | 3        | 0.99%   |
| Silvermont    | 1        | 0.33%   |
| Goldmont plus | 1        | 0.33%   |
| Unknown       | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 130      | 40.75%  |
| Nvidia                           | 113      | 35.42%  |
| AMD                              | 69       | 21.63%  |
| Matrox Electronics Systems       | 4        | 1.25%   |
| VIA Technologies                 | 1        | 0.31%   |
| Silicon Motion                   | 1        | 0.31%   |
| Silicon Integrated Systems [SiS] | 1        | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 19       | 5.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 19       | 5.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 18       | 5.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 17       | 5.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 13       | 4%      |
| Nvidia GT218 [GeForce 210]                                                    | 12       | 3.69%   |
| Intel Core Processor Integrated Graphics Controller                           | 9        | 2.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 7        | 2.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 7        | 2.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6        | 1.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 5        | 1.54%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 5        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 4        | 1.23%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 4        | 1.23%   |
| Nvidia GF108 [GeForce GT 730]                                                 | 4        | 1.23%   |
| Intel HD Graphics 630                                                         | 4        | 1.23%   |
| Intel HD Graphics 530                                                         | 4        | 1.23%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 4        | 1.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 4        | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 4        | 1.23%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                             | 4        | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3        | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 3        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 3        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 3        | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3        | 0.92%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 3        | 0.92%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 3        | 0.92%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                             | 3        | 0.92%   |
| Nvidia GT215 [GeForce GT 240]                                                 | 2        | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2        | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 2        | 0.62%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 2        | 0.62%   |
| Nvidia GM107 [GeForce GTX 750]                                                | 2        | 0.62%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 0.62%   |
| Nvidia GK104 [GeForce GTX 670]                                                | 2        | 0.62%   |
| Nvidia GF108 [GeForce GT 620]                                                 | 2        | 0.62%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 2        | 0.62%   |
| Nvidia G96C [GeForce 9400 GT]                                                 | 2        | 0.62%   |
| Nvidia G92 [GeForce 8800 GT]                                                  | 2        | 0.62%   |
| Nvidia C77 [nForce 780a/980a SLI]                                             | 2        | 0.62%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 2        | 0.62%   |
| Intel HD Graphics 610                                                         | 2        | 0.62%   |
| Intel HD Graphics 510                                                         | 2        | 0.62%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 2        | 0.62%   |
| Intel 82865G Integrated Graphics Controller                                   | 2        | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2        | 0.62%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                   | 2        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 0.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2        | 0.62%   |
| AMD Park [Mobility Radeon HD 5430]                                            | 2        | 0.62%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                   | 2        | 0.62%   |
| AMD Cezanne                                                                   | 2        | 0.62%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 0.62%   |
| AMD Cayman PRO [Radeon HD 6950]                                               | 2        | 0.62%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                | 2        | 0.62%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2        | 0.62%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.31%   |
| Silicon Motion SM712 LynxEM+                                                  | 1        | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 114      | 37.62%  |
| 1 x Nvidia         | 105      | 34.65%  |
| 1 x AMD            | 60       | 19.8%   |
| Intel + Nvidia     | 6        | 1.98%   |
| 2 x AMD            | 5        | 1.65%   |
| 1 x Matrox         | 3        | 0.99%   |
| Other              | 2        | 0.66%   |
| Intel + AMD        | 2        | 0.66%   |
| AMD + Nvidia       | 2        | 0.66%   |
| 1 x VIA            | 1        | 0.33%   |
| 1 x SiS            | 1        | 0.33%   |
| 1 x Silicon Motion | 1        | 0.33%   |
| AMD + Matrox       | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 227      | 74.43%  |
| Proprietary | 56       | 18.36%  |
| Unknown     | 22       | 7.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 153      | 48.73%  |
| 1.01-2.0   | 54       | 17.2%   |
| 0.51-1.0   | 35       | 11.15%  |
| 0.01-0.5   | 26       | 8.28%   |
| 3.01-4.0   | 20       | 6.37%   |
| 7.01-8.0   | 12       | 3.82%   |
| 5.01-6.0   | 8        | 2.55%   |
| 2.01-3.0   | 3        | 0.96%   |
| 8.01-16.0  | 2        | 0.64%   |
| 16.01-24.0 | 1        | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 85       | 28.81%  |
| Dell                 | 59       | 20%     |
| Goldstar             | 46       | 15.59%  |
| Philips              | 11       | 3.73%   |
| AOC                  | 10       | 3.39%   |
| Unknown              | 9        | 3.05%   |
| Hewlett-Packard      | 9        | 3.05%   |
| BenQ                 | 9        | 3.05%   |
| LG Electronics       | 6        | 2.03%   |
| Acer                 | 6        | 2.03%   |
| VIE                  | 5        | 1.69%   |
| Ancor Communications | 4        | 1.36%   |
| Toshiba              | 3        | 1.02%   |
| PRI                  | 3        | 1.02%   |
| MECER                | 3        | 1.02%   |
| Sony                 | 2        | 0.68%   |
| Plain Tree Systems   | 2        | 0.68%   |
| Onkyo                | 2        | 0.68%   |
| NEC Computers        | 2        | 0.68%   |
| CTV                  | 2        | 0.68%   |
| ___                  | 1        | 0.34%   |
| ViewSonic            | 1        | 0.34%   |
| Tatung               | 1        | 0.34%   |
| STD                  | 1        | 0.34%   |
| SKY                  | 1        | 0.34%   |
| SBI                  | 1        | 0.34%   |
| Sampo                | 1        | 0.34%   |
| RTK                  | 1        | 0.34%   |
| PKB                  | 1        | 0.34%   |
| Packard Bell         | 1        | 0.34%   |
| Marantz              | 1        | 0.34%   |
| Hitachi              | 1        | 0.34%   |
| FUS                  | 1        | 0.34%   |
| Fujitsu Siemens      | 1        | 0.34%   |
| Eizo                 | 1        | 0.34%   |
| ASUSTek Computer     | 1        | 0.34%   |
| Unknown              | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 7        | 2.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6        | 1.88%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6        | 1.88%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                    | 5        | 1.57%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 4        | 1.25%   |
| Samsung Electronics SMBX2031 SAM076B 1600x900 443x249mm 20.0-inch     | 3        | 0.94%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3        | 0.94%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 3        | 0.94%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 3        | 0.94%   |
| Goldstar W2443 GSM571B 1920x1080 474x296mm 22.0-inch                  | 3        | 0.94%   |
| Dell SE2719H DELF10C 1920x1080 598x336mm 27.0-inch                    | 3        | 0.94%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3        | 0.94%   |
| Dell S2340L DELD058 1920x1080 510x290mm 23.1-inch                     | 3        | 0.94%   |
| VIE S20W VIE2080 1600x900 443x249mm 20.0-inch                         | 2        | 0.63%   |
| Unknown LCD Monitor XXX AAA 1920x1080                                 | 2        | 0.63%   |
| Samsung Electronics SyncMaster SAM058E 1920x1080 477x268mm 21.5-inch  | 2        | 0.63%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch  | 2        | 0.63%   |
| Samsung Electronics SMB2230 SAM063F 1920x1080 477x268mm 21.5-inch     | 2        | 0.63%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch     | 2        | 0.63%   |
| Samsung Electronics S23B300 SAM08AE 1680x1050 510x290mm 23.1-inch     | 2        | 0.63%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 2        | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.63%   |
| Philips 202EL PHLC05C 1600x900 443x249mm 20.0-inch                    | 2        | 0.63%   |
| MECER TW999 MUS9996 1440x900 408x255mm 18.9-inch                      | 2        | 0.63%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 5120x1080                     | 2        | 0.63%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                               | 2        | 0.63%   |
| Hewlett-Packard L1740 HWP2649 1280x1024 338x270mm 17.0-inch           | 2        | 0.63%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 338x270mm 17.0-inch           | 2        | 0.63%   |
| Hewlett-Packard E273m HPN346E 1920x1080 598x336mm 27.0-inch           | 2        | 0.63%   |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                 | 2        | 0.63%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                 | 2        | 0.63%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.63%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 2        | 0.63%   |
| Dell SE2216H DELF070 1920x1080 476x268mm 21.5-inch                    | 2        | 0.63%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 2        | 0.63%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                    | 2        | 0.63%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                     | 2        | 0.63%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 2        | 0.63%   |
| Dell LCD Monitor DELF115 1920x1080 600x340mm 27.2-inch                | 2        | 0.63%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 2        | 0.63%   |
| CTV CTV CTV0030 1920x1080 708x398mm 32.0-inch                         | 2        | 0.63%   |
| BenQ G925HDA BNQ7843 1366x768 410x230mm 18.5-inch                     | 2        | 0.63%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 0.63%   |
| ___ LCD Monitor ___A770 1280x1024 320x240mm 15.7-inch                 | 1        | 0.31%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 1        | 0.31%   |
| VIE VIEWG 23WG VIE2320 1920x1080 2200x1125mm 97.3-inch                | 1        | 0.31%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                         | 1        | 0.31%   |
| VIE A/G2256 VIE2150 1920x1080 473x296mm 22.0-inch                     | 1        | 0.31%   |
| Unknown LCD Monitor XXX HISENSE                                       | 1        | 0.31%   |
| Unknown LCD Monitor XXX AAA                                           | 1        | 0.31%   |
| Unknown LCD Monitor VTK VIOTEKGN35LD 2560x1080                        | 1        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.31%   |
| Unknown LCD Monitor MUS MECER JP577 1280x1024                         | 1        | 0.31%   |
| Unknown LCD Monitor Kingston Technology 32 DISPLAY 1280x720           | 1        | 0.31%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 1920x1080 | 1        | 0.31%   |
| Unknown LCD Monitor CHD CHUD 1920x1080                                | 1        | 0.31%   |
| Toshiba LCD-MONITOR LCDEC80 1680x1050 470x300mm 22.0-inch             | 1        | 0.31%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 1        | 0.31%   |
| Toshiba LCD Monitor 15" 1 5" LCD000D 1024x768 304x228mm 15.0-inch     | 1        | 0.31%   |
| Tatung VM7E TATF770 1280x1024 300x230mm 14.9-inch                     | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 121      | 41.58%  |
| 1600x900 (HD+)     | 31       | 10.65%  |
| 1280x1024 (SXGA)   | 27       | 9.28%   |
| 1366x768 (WXGA)    | 25       | 8.59%   |
| 3840x2160 (4K)     | 10       | 3.44%   |
| 1440x900 (WXGA+)   | 10       | 3.44%   |
| 1680x1050 (WSXGA+) | 9        | 3.09%   |
| Unknown            | 9        | 3.09%   |
| 2560x1440 (QHD)    | 8        | 2.75%   |
| 2560x1080          | 7        | 2.41%   |
| 1360x768           | 6        | 2.06%   |
| 1024x768 (XGA)     | 6        | 2.06%   |
| 1920x540           | 3        | 1.03%   |
| 1920x1200 (WUXGA)  | 3        | 1.03%   |
| 5120x1080          | 2        | 0.69%   |
| 3840x1080          | 2        | 0.69%   |
| 1152x864           | 2        | 0.69%   |
| 720x480            | 1        | 0.34%   |
| 4880x1080          | 1        | 0.34%   |
| 4480x1080          | 1        | 0.34%   |
| 3360x1080          | 1        | 0.34%   |
| 3286x1080          | 1        | 0.34%   |
| 3280x1200          | 1        | 0.34%   |
| 2048x1536          | 1        | 0.34%   |
| 1600x1200          | 1        | 0.34%   |
| 1400x1050          | 1        | 0.34%   |
| 1280x720 (HD)      | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 34       | 11.6%   |
| Unknown | 33       | 11.26%  |
| 21      | 30       | 10.24%  |
| 24      | 27       | 9.22%   |
| 18      | 25       | 8.53%   |
| 20      | 24       | 8.19%   |
| 19      | 23       | 7.85%   |
| 27      | 22       | 7.51%   |
| 17      | 14       | 4.78%   |
| 22      | 11       | 3.75%   |
| 15      | 9        | 3.07%   |
| 34      | 6        | 2.05%   |
| 31      | 6        | 2.05%   |
| 40      | 5        | 1.71%   |
| 84      | 3        | 1.02%   |
| 72      | 3        | 1.02%   |
| 32      | 3        | 1.02%   |
| 54      | 2        | 0.68%   |
| 48      | 2        | 0.68%   |
| 46      | 2        | 0.68%   |
| 25      | 2        | 0.68%   |
| 97      | 1        | 0.34%   |
| 67      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 28      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 14      | 1        | 0.34%   |
| 13      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 100      | 35.21%  |
| 501-600        | 80       | 28.17%  |
| Unknown        | 33       | 11.62%  |
| 301-350        | 22       | 7.75%   |
| 351-400        | 10       | 3.52%   |
| 701-800        | 9        | 3.17%   |
| 601-700        | 8        | 2.82%   |
| 1001-1500      | 8        | 2.82%   |
| 1501-2000      | 6        | 2.11%   |
| 801-900        | 5        | 1.76%   |
| 201-300        | 2        | 0.7%    |
| More than 2000 | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 170      | 63.2%   |
| Unknown | 28       | 10.41%  |
| 16/10   | 24       | 8.92%   |
| 5/4     | 22       | 8.18%   |
| 4/3     | 14       | 5.2%    |
| 21/9    | 6        | 2.23%   |
| 3/2     | 2        | 0.74%   |
| 1.96    | 2        | 0.74%   |
| 32/9    | 1        | 0.37%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 86       | 30.39%  |
| 151-200        | 57       | 20.14%  |
| 141-150        | 33       | 11.66%  |
| Unknown        | 33       | 11.66%  |
| 301-350        | 23       | 8.13%   |
| 351-500        | 15       | 5.3%    |
| More than 1000 | 12       | 4.24%   |
| 501-1000       | 8        | 2.83%   |
| 101-110        | 6        | 2.12%   |
| 251-300        | 4        | 1.41%   |
| 111-120        | 4        | 1.41%   |
| 81-90          | 1        | 0.35%   |
| 131-140        | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 180      | 65.22%  |
| 101-120 | 45       | 16.3%   |
| Unknown | 33       | 11.96%  |
| 1-50    | 14       | 5.07%   |
| 161-240 | 2        | 0.72%   |
| 121-160 | 2        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 237      | 76.45%  |
| 2     | 43       | 13.87%  |
| 0     | 26       | 8.39%   |
| 3     | 3        | 0.97%   |
| 4     | 1        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 179      | 43.45%  |
| Intel                            | 101      | 24.51%  |
| Qualcomm Atheros                 | 30       | 7.28%   |
| Broadcom                         | 12       | 2.91%   |
| TP-Link                          | 11       | 2.67%   |
| Ralink Technology                | 11       | 2.67%   |
| Huawei Technologies              | 10       | 2.43%   |
| Samsung Electronics              | 8        | 1.94%   |
| Nvidia                           | 8        | 1.94%   |
| D-Link System                    | 5        | 1.21%   |
| Ralink                           | 4        | 0.97%   |
| D-Link                           | 4        | 0.97%   |
| Microsoft                        | 3        | 0.73%   |
| Broadcom Limited                 | 3        | 0.73%   |
| Aquantia                         | 3        | 0.73%   |
| ZyXEL Communications             | 2        | 0.49%   |
| Silicon Integrated Systems [SiS] | 2        | 0.49%   |
| MediaTek                         | 2        | 0.49%   |
| Marvell Technology Group         | 2        | 0.49%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.24%   |
| TRENDnet                         | 1        | 0.24%   |
| Spreadtrum Communications        | 1        | 0.24%   |
| Qualcomm Atheros Communications  | 1        | 0.24%   |
| Motorola                         | 1        | 0.24%   |
| Linux 2.6.31.6 with s3c-udc      | 1        | 0.24%   |
| IBM                              | 1        | 0.24%   |
| Foxconn / Hon Hai                | 1        | 0.24%   |
| Edimax Technology                | 1        | 0.24%   |
| CyberTAN Technology              | 1        | 0.24%   |
| Belkin Components                | 1        | 0.24%   |
| Unknown                          | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 141      | 30.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17       | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 3.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 14       | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 2.62%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 2.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 1.53%   |
| Intel I211 Gigabit Network Connection                             | 7        | 1.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 6        | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.31%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 6        | 1.31%   |
| Intel 82578DM Gigabit Network Connection                          | 6        | 1.31%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 5        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 0.87%   |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.87%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.87%   |
| Intel 82566DM Gigabit Network Connection                          | 4        | 0.87%   |
| Huawei COL-L29                                                    | 4        | 0.87%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3        | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.66%   |
| Nvidia MCP51 Ethernet Controller                                  | 3        | 0.66%   |
| Microsoft Xbox 360 Wireless Adapter                               | 3        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.66%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.66%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.66%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 3        | 0.66%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 3        | 0.66%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 3        | 0.66%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2        | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 2        | 0.44%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.44%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.44%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.44%   |
| Intel Wireless 8265 / 8275                                        | 2        | 0.44%   |
| Intel Wireless 8260                                               | 2        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.44%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.44%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 2        | 0.44%   |
| Huawei E353/E3131                                                 | 2        | 0.44%   |
| D-Link 802.11 n WLAN                                              | 2        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 37       | 32.46%  |
| Qualcomm Atheros                | 19       | 16.67%  |
| Intel                           | 13       | 11.4%   |
| Ralink Technology               | 11       | 9.65%   |
| TP-Link                         | 10       | 8.77%   |
| Ralink                          | 4        | 3.51%   |
| D-Link                          | 4        | 3.51%   |
| Microsoft                       | 3        | 2.63%   |
| ZyXEL Communications            | 2        | 1.75%   |
| D-Link System                   | 2        | 1.75%   |
| Broadcom                        | 2        | 1.75%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.88%   |
| TRENDnet                        | 1        | 0.88%   |
| Qualcomm Atheros Communications | 1        | 0.88%   |
| MediaTek                        | 1        | 0.88%   |
| Edimax Technology               | 1        | 0.88%   |
| CyberTAN Technology             | 1        | 0.88%   |
| Belkin Components               | 1        | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 14       | 12.07%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 8        | 6.9%    |
| Ralink MT7601U Wireless Adapter                                                   | 7        | 6.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 6        | 5.17%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                        | 6        | 5.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 5        | 4.31%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 4        | 3.45%   |
| Ralink RT5370 Wireless Adapter                                                    | 4        | 3.45%   |
| Intel Wi-Fi 6 AX200                                                               | 4        | 3.45%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 3        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 3        | 2.59%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 3        | 2.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 2        | 1.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 2        | 1.72%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 2        | 1.72%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                              | 2        | 1.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 2        | 1.72%   |
| Intel Wireless 8265 / 8275                                                        | 2        | 1.72%   |
| Intel Wireless 8260                                                               | 2        | 1.72%   |
| D-Link 802.11 n WLAN                                                              | 2        | 1.72%   |
| ZyXEL ZyAIR G-202 802.11bg                                                        | 1        | 0.86%   |
| ZyXEL NWD2105 802.11bgn Wireless Adapter [Ralink RT3070]                          | 1        | 0.86%   |
| ZTE WCDMA MSM K3772-Z                                                             | 1        | 0.86%   |
| TRENDnet 802.11n WLAN Adapter                                                     | 1        | 0.86%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                                       | 1        | 0.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.86%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 0.86%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                            | 1        | 0.86%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                              | 1        | 0.86%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                            | 1        | 0.86%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                         | 1        | 0.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 0.86%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                          | 1        | 0.86%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                         | 1        | 0.86%   |
| Ralink RT2760 Wireless 802.11n 1T/2R                                              | 1        | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 0.86%   |
| MediaTek 802.11 n WLAN                                                            | 1        | 0.86%   |
| Intel Wireless-AC 9260                                                            | 1        | 0.86%   |
| Intel Wireless 7265                                                               | 1        | 0.86%   |
| Intel Wireless 3160                                                               | 1        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 0.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                  | 1        | 0.86%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                    | 1        | 0.86%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 0.86%   |
| D-Link System DWA-126 802.11n Wireless Adapter [Atheros AR9271]                   | 1        | 0.86%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1        | 0.86%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                     | 1        | 0.86%   |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]      | 1        | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 1        | 0.86%   |
| Broadcom BCM43217 802.11b/g/n                                                     | 1        | 0.86%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]            | 1        | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 170      | 51.52%  |
| Intel                            | 96       | 29.09%  |
| Qualcomm Atheros                 | 13       | 3.94%   |
| Broadcom                         | 10       | 3.03%   |
| Samsung Electronics              | 8        | 2.42%   |
| Nvidia                           | 8        | 2.42%   |
| Huawei Technologies              | 8        | 2.42%   |
| D-Link System                    | 3        | 0.91%   |
| Broadcom Limited                 | 3        | 0.91%   |
| Aquantia                         | 3        | 0.91%   |
| Silicon Integrated Systems [SiS] | 2        | 0.61%   |
| Marvell Technology Group         | 2        | 0.61%   |
| TP-Link                          | 1        | 0.3%    |
| Spreadtrum Communications        | 1        | 0.3%    |
| MediaTek                         | 1        | 0.3%    |
| Foxconn / Hon Hai                | 1        | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 141      | 41.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17       | 5.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 5.06%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 3.57%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 2.98%   |
| Intel I211 Gigabit Network Connection                             | 7        | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.79%   |
| Intel 82578DM Gigabit Network Connection                          | 6        | 1.79%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.19%   |
| Intel 82566DM Gigabit Network Connection                          | 4        | 1.19%   |
| Huawei COL-L29                                                    | 4        | 1.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.89%   |
| Nvidia MCP51 Ethernet Controller                                  | 3        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.89%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.89%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 3        | 0.89%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 3        | 0.89%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 3        | 0.89%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 2        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.6%    |
| Nvidia MCP77 Ethernet                                             | 2        | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 2        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 2        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.6%    |
| Intel 82562EZ 10/100 Ethernet Controller                          | 2        | 0.6%    |
| Huawei E353/E3131                                                 | 2        | 0.6%    |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 2        | 0.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.6%    |
| TP-Link M7200                                                     | 1        | 0.3%    |
| Spreadtrum Spreadtrum Phone                                       | 1        | 0.3%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.3%    |
| Nvidia MCP55 Ethernet                                             | 1        | 0.3%    |
| MediaTek TECNO SPARK 6 Go                                         | 1        | 0.3%    |
| Intel PRO/100 VE Network Connection                               | 1        | 0.3%    |
| Intel I350 Gigabit Network Connection                             | 1        | 0.3%    |
| Intel Ethernet Controller I225-V                                  | 1        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.3%    |
| Huawei Ideos (tethering mode)                                     | 1        | 0.3%    |
| Huawei ALE-L21                                                    | 1        | 0.3%    |
| Foxconn / Hon Hai Nokia 7.1                                       | 1        | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.3%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 298      | 72.33%  |
| WiFi     | 108      | 26.21%  |
| Modem    | 4        | 0.97%   |
| Unknown  | 2        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 229      | 74.84%  |
| WiFi     | 77       | 25.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 238      | 77.78%  |
| 2     | 58       | 18.95%  |
| 3     | 6        | 1.96%   |
| 0     | 3        | 0.98%   |
| 4     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 299      | 98.36%  |
| Yes  | 5        | 1.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 21       | 47.73%  |
| Intel                           | 11       | 25%     |
| Qualcomm Atheros Communications | 3        | 6.82%   |
| Broadcom                        | 3        | 6.82%   |
| Apple                           | 3        | 6.82%   |
| Micro Star International        | 1        | 2.27%   |
| Edimax Technology               | 1        | 2.27%   |
| ASUSTek Computer                | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 21       | 47.73%  |
| Intel Bluetooth wireless interface                      | 6        | 13.64%  |
| Qualcomm Atheros  Bluetooth Device                      | 3        | 6.82%   |
| Intel AX200 Bluetooth                                   | 3        | 6.82%   |
| Apple Bluetooth HCI                                     | 3        | 6.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 2        | 4.55%   |
| Micro Star International Bluetooth dongle               | 1        | 2.27%   |
| Intel Bluetooth Device                                  | 1        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 2.27%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 2.27%   |
| Broadcom BCM2035 Bluetooth dongle                       | 1        | 2.27%   |
| ASUS Bluetooth Adapter                                  | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 228      | 49.35%  |
| Nvidia                           | 99       | 21.43%  |
| AMD                              | 83       | 17.97%  |
| C-Media Electronics              | 9        | 1.95%   |
| Creative Labs                    | 6        | 1.3%    |
| VIA Technologies                 | 3        | 0.65%   |
| Logitech                         | 3        | 0.65%   |
| Corsair                          | 3        | 0.65%   |
| Silicon Integrated Systems [SiS] | 2        | 0.43%   |
| Sennheiser Communications        | 2        | 0.43%   |
| Samson Technologies              | 2        | 0.43%   |
| Razer USA                        | 2        | 0.43%   |
| Plantronics                      | 2        | 0.43%   |
| Microsoft                        | 2        | 0.43%   |
| JMTek                            | 2        | 0.43%   |
| Hewlett-Packard                  | 2        | 0.43%   |
| ASUSTek Computer                 | 2        | 0.43%   |
| Syntek                           | 1        | 0.22%   |
| Sony                             | 1        | 0.22%   |
| Micro Star International         | 1        | 0.22%   |
| iPassion Technology              | 1        | 0.22%   |
| GYROCOM C&C                      | 1        | 0.22%   |
| GN Netcom                        | 1        | 0.22%   |
| Generalplus Technology           | 1        | 0.22%   |
| Cooler Master                    | 1        | 0.22%   |
| Cambridge Silicon Radio          | 1        | 0.22%   |
| Astro Gaming                     | 1        | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 50       | 9.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30       | 5.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28       | 5.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25       | 4.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23       | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16       | 3.12%   |
| Nvidia High Definition Audio Controller                                    | 15       | 2.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 2.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 13       | 2.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 2.53%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.34%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7        | 1.36%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.97%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4        | 0.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 0.78%   |
| Nvidia GF116 High Definition Audio Controller                              | 3        | 0.58%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.58%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 3        | 0.58%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3        | 0.58%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3        | 0.58%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 2        | 0.39%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 2        | 0.39%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.39%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.39%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 2        | 0.39%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.39%   |
| Nvidia MCP51 High Definition Audio                                         | 2        | 0.39%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.39%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.39%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 0.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.39%   |
| Microsoft LifeChat LX-3000 Headset                                         | 2        | 0.39%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.39%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.39%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 2        | 0.39%   |
| Hewlett-Packard E273m                                                      | 2        | 0.39%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 0.39%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 2        | 0.39%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 0.39%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2        | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 20       | 15.87%  |
| Kingston            | 20       | 15.87%  |
| Corsair             | 19       | 15.08%  |
| SK hynix            | 9        | 7.14%   |
| Transcend           | 8        | 6.35%   |
| G.Skill             | 8        | 6.35%   |
| Micron Technology   | 7        | 5.56%   |
| Samsung Electronics | 6        | 4.76%   |
| Patriot             | 6        | 4.76%   |
| Crucial             | 6        | 4.76%   |
| A-DATA Technology   | 5        | 3.97%   |
| Team                | 2        | 1.59%   |
| KLEVV               | 2        | 1.59%   |
| Apacer              | 2        | 1.59%   |
| Strontium           | 1        | 0.79%   |
| Silicon Power       | 1        | 0.79%   |
| Ramaxel Technology  | 1        | 0.79%   |
| Qimonda             | 1        | 0.79%   |
| Kingmax             | 1        | 0.79%   |
| Elpida              | 1        | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Transcend RAM TS512MLK64V6H 4GB DIMM DDR3 1600MT/s                          | 3        | 2.11%   |
| Unknown RAM Module 512MB DIMM 400MT/s                                       | 2        | 1.41%   |
| Unknown RAM Module 4GB DIMM 800MT/s                                         | 2        | 1.41%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                         | 2        | 1.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                        | 2        | 1.41%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                     | 2        | 1.41%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                        | 2        | 1.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                        | 2        | 1.41%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                        | 2        | 1.41%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                             | 2        | 1.41%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                              | 2        | 1.41%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                         | 2        | 1.41%   |
| KLEVV RAM KD4AGUA8A-26N1900 16GB DIMM DDR4 2667MT/s                         | 2        | 1.41%   |
| Kingston RAM 9905678-023.A00G 8192MB DIMM DDR4 2134MT/s                     | 2        | 1.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s                         | 2        | 1.41%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 800MT/s                         | 2        | 1.41%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s                      | 2        | 1.41%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s                      | 2        | 1.41%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2133MT/s                                 | 2        | 1.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                   | 1        | 0.7%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                                        | 1        | 0.7%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                                | 1        | 0.7%    |
| Unknown RAM Module 4096MB DIMM                                              | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                    | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                    | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM 800MT/s                                         | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                                        | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                 | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                                  | 1        | 0.7%    |
| Unknown RAM Module 2048MB DIMM 41632MT/s                                    | 1        | 0.7%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                    | 1        | 0.7%    |
| Unknown RAM Module 1GB DIMM                                                 | 1        | 0.7%    |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                                  | 1        | 0.7%    |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s                            | 1        | 0.7%    |
| Transcend RAM TS1GLK64V3H 8192MB DIMM DDR3 1067MT/s                         | 1        | 0.7%    |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s                            | 1        | 0.7%    |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s                           | 1        | 0.7%    |
| Transcend RAM JM1333KLH-8G 8192MB DIMM DDR3 1333MT/s                        | 1        | 0.7%    |
| Transcend RAM 4A4D383030514C552D314720202020202020 1024MB DIMM DDR2 800MT/s | 1        | 0.7%    |
| Transcend RAM 4A4D383030514C4A2D314720202020202020 1024MB DIMM DDR2 800MT/s | 1        | 0.7%    |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                         | 1        | 0.7%    |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                                  | 1        | 0.7%    |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s                       | 1        | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                | 1        | 0.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                        | 1        | 0.7%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                        | 1        | 0.7%    |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s                     | 1        | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                   | 1        | 0.7%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s                     | 1        | 0.7%    |
| SK hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s                     | 1        | 0.7%    |
| SK hynix RAM DMT125U6BFR8C-H9 2GB DIMM DDR3 1333MT/s                        | 1        | 0.7%    |
| Silicon Power RAM DBLT4GN568S 4GB DIMM 1333MT/s                             | 1        | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 1        | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                       | 1        | 0.7%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s                       | 1        | 0.7%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                         | 1        | 0.7%    |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                         | 1        | 0.7%    |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s                         | 1        | 0.7%    |
| Ramaxel RAM RML1520EG38D6W-667 512MB DIMM DDR2 667MT/s                      | 1        | 0.7%    |
| Qimonda RAM 64T64000HU3SB 512MB DIMM DDR2 667MT/s                           | 1        | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 44       | 40.37%  |
| DDR4    | 42       | 38.53%  |
| Unknown | 14       | 12.84%  |
| DDR2    | 7        | 6.42%   |
| DDR     | 2        | 1.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 101      | 92.66%  |
| SODIMM  | 7        | 6.42%   |
| FB-DIMM | 1        | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 45       | 37.5%   |
| 8192  | 38       | 31.67%  |
| 16384 | 15       | 12.5%   |
| 2048  | 13       | 10.83%  |
| 1024  | 5        | 4.17%   |
| 512   | 3        | 2.5%    |
| 32768 | 1        | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 21.85%  |
| 1333    | 21       | 17.65%  |
| 2133    | 8        | 6.72%   |
| 800     | 8        | 6.72%   |
| 2667    | 6        | 5.04%   |
| 3466    | 4        | 3.36%   |
| 400     | 4        | 3.36%   |
| 3200    | 3        | 2.52%   |
| 2400    | 3        | 2.52%   |
| 667     | 3        | 2.52%   |
| 3600    | 2        | 1.68%   |
| 3100    | 2        | 1.68%   |
| 2934    | 2        | 1.68%   |
| 2933    | 2        | 1.68%   |
| 2666    | 2        | 1.68%   |
| 2134    | 2        | 1.68%   |
| 1867    | 2        | 1.68%   |
| 1800    | 2        | 1.68%   |
| 1067    | 2        | 1.68%   |
| Unknown | 2        | 1.68%   |
| 41632   | 1        | 0.84%   |
| 6000    | 1        | 0.84%   |
| 3800    | 1        | 0.84%   |
| 3733    | 1        | 0.84%   |
| 3533    | 1        | 0.84%   |
| 3400    | 1        | 0.84%   |
| 3266    | 1        | 0.84%   |
| 3066    | 1        | 0.84%   |
| 3000    | 1        | 0.84%   |
| 2800    | 1        | 0.84%   |
| 2733    | 1        | 0.84%   |
| 2200    | 1        | 0.84%   |
| 133     | 1        | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 28.57%  |
| Pantum              | 3        | 21.43%  |
| Canon               | 3        | 21.43%  |
| Seiko Epson         | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Dell                | 1        | 7.14%   |
| Brother Industries  | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Pantum P2200 series          | 3        | 21.43%  |
| Seiko Epson L3110 Series     | 1        | 7.14%   |
| Samsung SCX-4623 Series      | 1        | 7.14%   |
| Samsung M2070 Series         | 1        | 7.14%   |
| Samsung M2020 Series         | 1        | 7.14%   |
| Samsung Composite Device     | 1        | 7.14%   |
| HP OfficeJet Pro 9010 series | 1        | 7.14%   |
| Dell 1250c Color Printer     | 1        | 7.14%   |
| Canon PIXMA MX410            | 1        | 7.14%   |
| Canon PIXMA MG3600 Series    | 1        | 7.14%   |
| Canon G3010 series           | 1        | 7.14%   |
| Brother HL-2130 series       | 1        | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1        | 50%     |
| HP OfficeJet 6110                                  | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 51.52%  |
| Microsoft                     | 4        | 12.12%  |
| Sunplus Innovation Technology | 2        | 6.06%   |
| Samsung Electronics           | 2        | 6.06%   |
| Apple                         | 2        | 6.06%   |
| Z-Star Microelectronics       | 1        | 3.03%   |
| Syntek                        | 1        | 3.03%   |
| SN0002                        | 1        | 3.03%   |
| KYE Systems (Mouse Systems)   | 1        | 3.03%   |
| Google                        | 1        | 3.03%   |
| Asuscom Network               | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 5        | 14.71%  |
| Logitech Webcam C170                      | 3        | 8.82%   |
| Sunplus Full HD webcam                    | 2        | 5.88%   |
| Microsoft LifeCam VX-800                  | 2        | 5.88%   |
| Logitech Webcam C200                      | 2        | 5.88%   |
| Logitech HD Webcam C615                   | 2        | 5.88%   |
| Z-Star Venus USB2.0 Camera                | 1        | 2.94%   |
| Syntek XYZ printing cameraR2              | 1        | 2.94%   |
| Syntek XYZ printing cameraL2              | 1        | 2.94%   |
| SN0002 1080P Web Camera                   | 1        | 2.94%   |
| Samsung USB2.0 UVC HQ WebCam              | 1        | 2.94%   |
| Samsung Galaxy series, misc. (MTP mode)   | 1        | 2.94%   |
| Microsoft LifeCam HD-3000                 | 1        | 2.94%   |
| Microsoft LifeCam Cinema                  | 1        | 2.94%   |
| Logitech Webcam C210                      | 1        | 2.94%   |
| Logitech QuickCam Sphere                  | 1        | 2.94%   |
| Logitech QuickCam Pro 9000                | 1        | 2.94%   |
| Logitech HD Webcam C525                   | 1        | 2.94%   |
| Logitech C920 PRO HD Webcam               | 1        | 2.94%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 2.94%   |
| Google HD USB Camera                      | 1        | 2.94%   |
| Asuscom Network HD 1080P PC-Camera        | 1        | 2.94%   |
| Apple iPod Touch 5.Gen [A1421]            | 1        | 2.94%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 2.94%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 257      | 84.26%  |
| 1     | 40       | 13.11%  |
| 2     | 7        | 2.3%    |
| 5     | 1        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 25       | 45.45%  |
| Net/wireless             | 12       | 21.82%  |
| Communication controller | 6        | 10.91%  |
| Unassigned class         | 3        | 5.45%   |
| Sound                    | 3        | 5.45%   |
| Net/ethernet             | 2        | 3.64%   |
| Storage/nvme             | 1        | 1.82%   |
| Network                  | 1        | 1.82%   |
| Modem                    | 1        | 1.82%   |
| Camera                   | 1        | 1.82%   |

