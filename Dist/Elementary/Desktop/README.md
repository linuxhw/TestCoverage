Elementary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 444

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF X470-PLUS GAMING        | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Pegatron      | 2ACD                        | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | [25a8936801](https://linux-hardware.org/?probe=25a8936801) | Jun 11, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| ASUSTek       | P8H61                       | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| MSI           | B85I                        | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| HP            | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS           | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| Inventec      | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| HP            | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Dell          | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell          | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP            | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP            | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek       | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Intel         | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek       | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP            | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown       | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI           | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH        | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI           | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte      | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| ASRock        | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI           | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn       | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Pegatron      | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Acer          | Aspire X3990                | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Pegatron      | Benicia                     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP            | 8653 A                      | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| ASUSTek       | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Biostar       | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek       | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Acer          | Aspire X3990                | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Foxconn       | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| HP            | 1825                        | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Foxconn       | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Gigabyte      | EP43T-USB3                  | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Gigabyte      | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| MSI           | 970A-G43                    | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Intel         | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASRock        | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Foxconn       | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| HP            | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP            | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell          | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Gigabyte      | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Apple         | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek       | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Gigabyte      | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Intel         | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Gigabyte      | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Gigabyte      | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Intel         | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek       | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte      | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Acer          | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASRock        | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek       | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell          | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell          | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI           | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP            | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| Gigabyte      | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP            | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte      | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| ASRock        | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar       | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA          | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI           | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | [4e7d5b4879](https://linux-hardware.org/?probe=4e7d5b4879) | Jan 07, 2021 |
| ASUSTek       | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI           | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell          | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek       | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| Biostar       | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock        | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell          | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| HP            | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte      | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP            | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte      | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| ASUSTek       | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte      | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| MSI           | B450M PRO-M2 MAX            | [f2face0a01](https://linux-hardware.org/?probe=f2face0a01) | Nov 07, 2020 |
| ASUSTek       | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines     | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| HP            | 8433 11                     | [670028bf54](https://linux-hardware.org/?probe=670028bf54) | Oct 16, 2020 |
| MSI           | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI           | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP            | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek       | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer          | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel         | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI           | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek       | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP            | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP            | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI           | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |
| ASUSTek       | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| SYS           | H310CH5-TI2                 | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [6cf9ba1da5](https://linux-hardware.org/?probe=6cf9ba1da5) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [9372988884](https://linux-hardware.org/?probe=9372988884) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [ca6080756b](https://linux-hardware.org/?probe=ca6080756b) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [41e1632a84](https://linux-hardware.org/?probe=41e1632a84) | Jul 24, 2020 |
| HP            | 2ADC                        | [2faf91f855](https://linux-hardware.org/?probe=2faf91f855) | Jul 02, 2020 |
| MSI           | B450M PRO-VDH MAX           | [9159f538a0](https://linux-hardware.org/?probe=9159f538a0) | Jun 28, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f7a297ae2c](https://linux-hardware.org/?probe=f7a297ae2c) | Jun 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [f9f7ec4c96](https://linux-hardware.org/?probe=f9f7ec4c96) | May 27, 2020 |
| ASUSTek       | P8Z77-V LX                  | [aa53a3eba5](https://linux-hardware.org/?probe=aa53a3eba5) | May 26, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0e7c8d0cdc](https://linux-hardware.org/?probe=0e7c8d0cdc) | May 25, 2020 |
| Acer          | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [14dfb9eb8c](https://linux-hardware.org/?probe=14dfb9eb8c) | May 22, 2020 |
| ASUSTek       | PRIME A320M-K               | [299eb96cce](https://linux-hardware.org/?probe=299eb96cce) | May 22, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [cb10b79124](https://linux-hardware.org/?probe=cb10b79124) | May 16, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [592e93d734](https://linux-hardware.org/?probe=592e93d734) | May 16, 2020 |
| MSI           | GF615M-P33 V2               | [e6c02461aa](https://linux-hardware.org/?probe=e6c02461aa) | May 14, 2020 |
| ASRock        | B450M-HDV R4.0              | [484cc8fd5a](https://linux-hardware.org/?probe=484cc8fd5a) | May 07, 2020 |
| ASRock        | B450M-HDV R4.0              | [dbbea9cdaf](https://linux-hardware.org/?probe=dbbea9cdaf) | May 07, 2020 |
| Intel         | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7a18707ff5](https://linux-hardware.org/?probe=7a18707ff5) | Apr 26, 2020 |
| Acer          | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| eMachines     | EL1358G                     | [0ec6f0c0df](https://linux-hardware.org/?probe=0ec6f0c0df) | Apr 20, 2020 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [7fa6504e44](https://linux-hardware.org/?probe=7fa6504e44) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [21eac3f5ab](https://linux-hardware.org/?probe=21eac3f5ab) | Apr 14, 2020 |
| MSI           | H110M PRO-VD                | [a69e76d844](https://linux-hardware.org/?probe=a69e76d844) | Apr 11, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [fb24b9471a](https://linux-hardware.org/?probe=fb24b9471a) | Apr 08, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [9ba07d6518](https://linux-hardware.org/?probe=9ba07d6518) | Apr 08, 2020 |
| ASUSTek       | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| MSI           | MPG Z390 GAMING PRO CARB... | [d69e7b9642](https://linux-hardware.org/?probe=d69e7b9642) | Apr 02, 2020 |
| ECS           | H55H-M                      | [1673d5808e](https://linux-hardware.org/?probe=1673d5808e) | Mar 31, 2020 |
| ASRock        | Z77 Extreme4                | [1ea076e57b](https://linux-hardware.org/?probe=1ea076e57b) | Mar 19, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [642694d59f](https://linux-hardware.org/?probe=642694d59f) | Mar 19, 2020 |
| ASUSTek       | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [86896f4c65](https://linux-hardware.org/?probe=86896f4c65) | Mar 17, 2020 |
| ASRock        | Z77 Extreme4                | [847badc92c](https://linux-hardware.org/?probe=847badc92c) | Mar 17, 2020 |
| ASRock        | B85M Pro3                   | [765094a989](https://linux-hardware.org/?probe=765094a989) | Mar 10, 2020 |
| MSI           | Z170A PC MATE               | [201d14e45c](https://linux-hardware.org/?probe=201d14e45c) | Mar 09, 2020 |
| ASUSTek       | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [9c21c6ca8e](https://linux-hardware.org/?probe=9c21c6ca8e) | Feb 17, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [8eb7f19502](https://linux-hardware.org/?probe=8eb7f19502) | Feb 17, 2020 |
| ASUSTek       | Maximus V FORMULA           | [713f5c5aaf](https://linux-hardware.org/?probe=713f5c5aaf) | Feb 14, 2020 |
| Gigabyte      | H67M-D2-B3                  | [8b9d4bcb86](https://linux-hardware.org/?probe=8b9d4bcb86) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [03eef2b7d3](https://linux-hardware.org/?probe=03eef2b7d3) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [cd4d0236ad](https://linux-hardware.org/?probe=cd4d0236ad) | Jan 30, 2020 |
| MSI           | FM2-A55M-E33                | [4587ab8edd](https://linux-hardware.org/?probe=4587ab8edd) | Jan 25, 2020 |
| MSI           | FM2-A55M-E33                | [93fb1697b5](https://linux-hardware.org/?probe=93fb1697b5) | Jan 25, 2020 |
| Gigabyte      | H97-HD3                     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| ASRock        | Z87 Extreme6                | [ffb3f65bcd](https://linux-hardware.org/?probe=ffb3f65bcd) | Jan 18, 2020 |
| Dell          | 0KWVT8 A00                  | [55b5255c24](https://linux-hardware.org/?probe=55b5255c24) | Jan 18, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Pegatron      | IPMH61P1                    | [2a47818e18](https://linux-hardware.org/?probe=2a47818e18) | Jan 06, 2020 |
| ASRock        | H87M Pro4                   | [40dee920a9](https://linux-hardware.org/?probe=40dee920a9) | Dec 25, 2019 |
| Gigabyte      | Z390 GAMING SLI-CF          | [41795f04de](https://linux-hardware.org/?probe=41795f04de) | Dec 24, 2019 |
| MSI           | A320M PRO-VD PLUS           | [805e960aa9](https://linux-hardware.org/?probe=805e960aa9) | Dec 18, 2019 |
| ASRock        | X399 Phantom Gaming 6       | [b89b031eb9](https://linux-hardware.org/?probe=b89b031eb9) | Dec 14, 2019 |
| MSI           | B150M BAZOOKA               | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| Gigabyte      | H61M-S1                     | [2302b497cc](https://linux-hardware.org/?probe=2302b497cc) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [c9400c1fcb](https://linux-hardware.org/?probe=c9400c1fcb) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [18d758491c](https://linux-hardware.org/?probe=18d758491c) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [cfbe6b0f33](https://linux-hardware.org/?probe=cfbe6b0f33) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [c5b3e3f258](https://linux-hardware.org/?probe=c5b3e3f258) | Dec 11, 2019 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a548b448e7](https://linux-hardware.org/?probe=a548b448e7) | Dec 09, 2019 |
| MSI           | PH67A-C43                   | [35ffc61791](https://linux-hardware.org/?probe=35ffc61791) | Dec 06, 2019 |
| MSI           | PH67A-C43                   | [1a5faa8a98](https://linux-hardware.org/?probe=1a5faa8a98) | Dec 05, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [889648300b](https://linux-hardware.org/?probe=889648300b) | Oct 04, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [28d0871f17](https://linux-hardware.org/?probe=28d0871f17) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [22a74597d5](https://linux-hardware.org/?probe=22a74597d5) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [31f72c0672](https://linux-hardware.org/?probe=31f72c0672) | Oct 02, 2019 |
| Dell          | 048DY8 A00                  | [500dc4f9f5](https://linux-hardware.org/?probe=500dc4f9f5) | Sep 11, 2019 |
| ASRock        | H97M Pro4                   | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| MSI           | Z97A GAMING 6               | [6a9086bf86](https://linux-hardware.org/?probe=6a9086bf86) | Jul 06, 2019 |
| ASUSTek       | PRIME A320M-K               | [0f2ef33214](https://linux-hardware.org/?probe=0f2ef33214) | Jun 27, 2019 |
| Dell          | 09KPNV A00                  | [b1769092a2](https://linux-hardware.org/?probe=b1769092a2) | Jun 22, 2019 |
| Dell          | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASUSTek       | STRIKER II NSE              | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock        | H97M Pro4                   | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI           | B450 TOMAHAWK               | [336d0df071](https://linux-hardware.org/?probe=336d0df071) | May 03, 2019 |
| Intel         | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Intel         | SHARKBAY                    | [d411643b19](https://linux-hardware.org/?probe=d411643b19) | Apr 23, 2019 |
| Dell          | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [cbb0c4be39](https://linux-hardware.org/?probe=cbb0c4be39) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [6fb3422b8b](https://linux-hardware.org/?probe=6fb3422b8b) | Apr 11, 2019 |
| HP            | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Intel         | DH55HC AAE70933-502         | [8f109c807c](https://linux-hardware.org/?probe=8f109c807c) | Feb 15, 2019 |
| Intel         | DH55HC AAE70933-502         | [be7548c062](https://linux-hardware.org/?probe=be7548c062) | Feb 15, 2019 |
| Wibtek        | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ECS           | H61H2-M2                    | [ed1e345718](https://linux-hardware.org/?probe=ed1e345718) | Feb 02, 2019 |
| ECS           | H61H2-M2                    | [554a16077e](https://linux-hardware.org/?probe=554a16077e) | Feb 01, 2019 |
| Gigabyte      | G31M-ES2L                   | [8531feefb2](https://linux-hardware.org/?probe=8531feefb2) | Jan 07, 2019 |
| Gigabyte      | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte      | B85M-D3H                    | [d206454b5f](https://linux-hardware.org/?probe=d206454b5f) | Aug 27, 2018 |
| ASUSTek       | P5GD1 PRO                   | [7f52004043](https://linux-hardware.org/?probe=7f52004043) | Aug 02, 2018 |
| ECS           | H61H2-M2                    | [765806fe73](https://linux-hardware.org/?probe=765806fe73) | Jun 01, 2018 |
| Gigabyte      | GA-990FXA-UD3               | [2e67236dbb](https://linux-hardware.org/?probe=2e67236dbb) | Feb 23, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Elementary 6.1   | 119      | 36.62%  |
| Elementary 6     | 67       | 20.62%  |
| Elementary 5.1.7 | 65       | 20%     |
| Elementary 5.1   | 17       | 5.23%   |
| Elementary 5.0   | 17       | 5.23%   |
| Elementary 5.1.2 | 10       | 3.08%   |
| Elementary 5.1.4 | 7        | 2.15%   |
| Elementary 5.1.3 | 7        | 2.15%   |
| Elementary 5.1.6 | 6        | 1.85%   |
| Elementary 0.4.1 | 6        | 1.85%   |
| Elementary 6.0   | 2        | 0.62%   |
| Elementary 5.1.5 | 2        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 303      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.11.0-43-generic  | 26       | 7.26%   |
| 5.11.0-41-generic  | 20       | 5.59%   |
| 5.13.0-39-generic  | 17       | 4.75%   |
| 5.13.0-28-generic  | 16       | 4.47%   |
| 5.11.0-40-generic  | 16       | 4.47%   |
| 5.0.0-37-generic   | 11       | 3.07%   |
| 5.13.0-30-generic  | 10       | 2.79%   |
| 5.11.0-27-generic  | 10       | 2.79%   |
| 5.4.0-42-generic   | 9        | 2.51%   |
| 5.13.0-40-generic  | 9        | 2.51%   |
| 5.13.0-27-generic  | 9        | 2.51%   |
| 5.4.0-48-generic   | 8        | 2.23%   |
| 5.13.0-35-generic  | 7        | 1.96%   |
| 5.11.0-37-generic  | 7        | 1.96%   |
| 5.4.0-65-generic   | 6        | 1.68%   |
| 5.4.0-58-generic   | 6        | 1.68%   |
| 5.11.0-25-generic  | 6        | 1.68%   |
| 5.4.0-54-generic   | 5        | 1.4%    |
| 5.3.0-46-generic   | 5        | 1.4%    |
| 5.3.0-40-generic   | 5        | 1.4%    |
| 5.13.0-37-generic  | 5        | 1.4%    |
| 5.11.0-38-generic  | 5        | 1.4%    |
| 5.13.0-51-generic  | 4        | 1.12%   |
| 5.13.0-44-generic  | 4        | 1.12%   |
| 5.11.0-44-generic  | 4        | 1.12%   |
| 5.8.0-50-generic   | 3        | 0.84%   |
| 5.4.0-56-generic   | 3        | 0.84%   |
| 5.4.0-52-generic   | 3        | 0.84%   |
| 5.4.0-47-generic   | 3        | 0.84%   |
| 5.3.0-53-generic   | 3        | 0.84%   |
| 5.3.0-28-generic   | 3        | 0.84%   |
| 5.13.0-48-generic  | 3        | 0.84%   |
| 4.15.0-51-generic  | 3        | 0.84%   |
| 4.15.0-47-generic  | 3        | 0.84%   |
| 5.4.0-90-generic   | 2        | 0.56%   |
| 5.4.0-80-generic   | 2        | 0.56%   |
| 5.4.0-71-generic   | 2        | 0.56%   |
| 5.4.0-70-generic   | 2        | 0.56%   |
| 5.4.0-60-generic   | 2        | 0.56%   |
| 5.4.0-53-generic   | 2        | 0.56%   |
| 5.3.0-62-generic   | 2        | 0.56%   |
| 5.3.0-51-generic   | 2        | 0.56%   |
| 5.3.0-45-generic   | 2        | 0.56%   |
| 5.3.0-42-generic   | 2        | 0.56%   |
| 5.3.0-26-generic   | 2        | 0.56%   |
| 5.13.0-41-generic  | 2        | 0.56%   |
| 5.13.0-25-generic  | 2        | 0.56%   |
| 5.11.0-46-generic  | 2        | 0.56%   |
| 5.11.0-36-generic  | 2        | 0.56%   |
| 5.11.0-34-generic  | 2        | 0.56%   |
| 4.15.0-96-generic  | 2        | 0.56%   |
| 4.15.0-45-generic  | 2        | 0.56%   |
| 4.15.0-161-generic | 2        | 0.56%   |
| 4.15.0-128-generic | 2        | 0.56%   |
| 4.15.0-112-generic | 2        | 0.56%   |
| 5.8.0-63-generic   | 1        | 0.28%   |
| 5.8.0-55-generic   | 1        | 0.28%   |
| 5.4.0-94-generic   | 1        | 0.28%   |
| 5.4.0-91-generic   | 1        | 0.28%   |
| 5.4.0-84-generic   | 1        | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 95       | 29.87%  |
| 5.13.0  | 81       | 25.47%  |
| 5.4.0   | 62       | 19.5%   |
| 5.3.0   | 24       | 7.55%   |
| 4.15.0  | 22       | 6.92%   |
| 5.0.0   | 15       | 4.72%   |
| 5.8.0   | 5        | 1.57%   |
| 4.18.0  | 3        | 0.94%   |
| 4.4.0   | 2        | 0.63%   |
| 5.2.11  | 1        | 0.31%   |
| 5.17.3  | 1        | 0.31%   |
| 5.17.0  | 1        | 0.31%   |
| 5.15.36 | 1        | 0.31%   |
| 5.15.12 | 1        | 0.31%   |
| 5.15.1  | 1        | 0.31%   |
| 5.14.0  | 1        | 0.31%   |
| 5.0.11  | 1        | 0.31%   |
| 4.10.0  | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 95       | 29.87%  |
| 5.13    | 81       | 25.47%  |
| 5.4     | 62       | 19.5%   |
| 5.3     | 24       | 7.55%   |
| 4.15    | 22       | 6.92%   |
| 5.0     | 16       | 5.03%   |
| 5.8     | 5        | 1.57%   |
| 5.15    | 3        | 0.94%   |
| 4.18    | 3        | 0.94%   |
| 5.17    | 2        | 0.63%   |
| 4.4     | 2        | 0.63%   |
| 5.2     | 1        | 0.31%   |
| 5.14    | 1        | 0.31%   |
| 4.10    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 303      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 280      | 90.61%  |
| Unknown  | 26       | 8.41%   |
| GNOME    | 2        | 0.65%   |
| MATE     | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 302      | 99.67%  |
| Unknown | 1        | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 253      | 81.88%  |
| LightDM | 38       | 12.3%   |
| TDM     | 16       | 5.18%   |
| SDDM    | 1        | 0.32%   |
| GDM     | 1        | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 117      | 37.5%   |
| de_DE   | 32       | 10.26%  |
| Unknown | 24       | 7.69%   |
| es_ES   | 23       | 7.37%   |
| en_GB   | 16       | 5.13%   |
| fr_FR   | 12       | 3.85%   |
| pt_BR   | 11       | 3.53%   |
| ru_RU   | 10       | 3.21%   |
| en_CA   | 8        | 2.56%   |
| pl_PL   | 6        | 1.92%   |
| it_IT   | 6        | 1.92%   |
| tr_TR   | 5        | 1.6%    |
| es_MX   | 3        | 0.96%   |
| en_AU   | 3        | 0.96%   |
| de_CH   | 3        | 0.96%   |
| zh_CN   | 2        | 0.64%   |
| pt_PT   | 2        | 0.64%   |
| ja_JP   | 2        | 0.64%   |
| en_IN   | 2        | 0.64%   |
| zh_TW   | 1        | 0.32%   |
| uk_UA   | 1        | 0.32%   |
| sv_SE   | 1        | 0.32%   |
| sr_RS   | 1        | 0.32%   |
| nl_NL   | 1        | 0.32%   |
| id_ID   | 1        | 0.32%   |
| hu_HU   | 1        | 0.32%   |
| hr_HR   | 1        | 0.32%   |
| gl_ES   | 1        | 0.32%   |
| fr_CA   | 1        | 0.32%   |
| fr_BE   | 1        | 0.32%   |
| fi_FI   | 1        | 0.32%   |
| es_VE   | 1        | 0.32%   |
| es_SV   | 1        | 0.32%   |
| es_PA   | 1        | 0.32%   |
| es_EC   | 1        | 0.32%   |
| en_ZA   | 1        | 0.32%   |
| en_PH   | 1        | 0.32%   |
| en_IE   | 1        | 0.32%   |
| en_HK   | 1        | 0.32%   |
| el_GR   | 1        | 0.32%   |
| de_AT   | 1        | 0.32%   |
| cs_CZ   | 1        | 0.32%   |
| ca_ES   | 1        | 0.32%   |
| ar_EG   | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 155      | 50.32%  |
| EFI  | 153      | 49.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 286      | 93.16%  |
| Btrfs   | 11       | 3.58%   |
| Unknown | 6        | 1.95%   |
| Xfs     | 3        | 0.98%   |
| Overlay | 1        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 265      | 86.32%  |
| GPT     | 26       | 8.47%   |
| MBR     | 16       | 5.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 279      | 91.78%  |
| Yes       | 25       | 8.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 252      | 82.62%  |
| Yes       | 53       | 17.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 81       | 26.73%  |
| Gigabyte Technology | 53       | 17.49%  |
| MSI                 | 38       | 12.54%  |
| Hewlett-Packard     | 28       | 9.24%   |
| ASRock              | 25       | 8.25%   |
| Dell                | 19       | 6.27%   |
| Intel               | 10       | 3.3%    |
| Biostar             | 9        | 2.97%   |
| Lenovo              | 6        | 1.98%   |
| Acer                | 5        | 1.65%   |
| Pegatron            | 4        | 1.32%   |
| Foxconn             | 3        | 0.99%   |
| ECS                 | 3        | 0.99%   |
| Apple               | 3        | 0.99%   |
| Wibtek              | 2        | 0.66%   |
| Unknown             | 2        | 0.66%   |
| T-bao               | 1        | 0.33%   |
| SYS                 | 1        | 0.33%   |
| Shuttle             | 1        | 0.33%   |
| LORD ELECTRONICS    | 1        | 0.33%   |
| Inventec            | 1        | 0.33%   |
| Fujitsu             | 1        | 0.33%   |
| FIRICH              | 1        | 0.33%   |
| EVGA                | 1        | 0.33%   |
| eMachines           | 1        | 0.33%   |
| AZW                 | 1        | 0.33%   |
| AOpen               | 1        | 0.33%   |
| AMI                 | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 8        | 2.64%   |
| ASUS P8H61-M LX3 R2.0                             | 4        | 1.32%   |
| MSI MS-7C02                                       | 3        | 0.99%   |
| ASUS PRIME A320M-K                                | 3        | 0.99%   |
| Wibtek H61-M HDMI2                                | 2        | 0.66%   |
| Pegatron IPMH61P1                                 | 2        | 0.66%   |
| MSI MS-7C35                                       | 2        | 0.66%   |
| MSI MS-7B86                                       | 2        | 0.66%   |
| MSI MS-7817                                       | 2        | 0.66%   |
| MSI MS-7721                                       | 2        | 0.66%   |
| Intel H61                                         | 2        | 0.66%   |
| HP Compaq Pro 6300 MT                             | 2        | 0.66%   |
| Gigabyte Z390 UD                                  | 2        | 0.66%   |
| Gigabyte H61M-DS2                                 | 2        | 0.66%   |
| ECS H55H-M                                        | 2        | 0.66%   |
| Dell OptiPlex 9010                                | 2        | 0.66%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 0.66%   |
| ASUS ROG STRIX B350-F GAMING                      | 2        | 0.66%   |
| ASRock B450M-HDV R4.0                             | 2        | 0.66%   |
| Unknown                                           | 2        | 0.66%   |
| T-bao MINI PC                                     | 1        | 0.33%   |
| SYS H310CH5-TI2                                   | 1        | 0.33%   |
| Shuttle DS61                                      | 1        | 0.33%   |
| Pegatron p7-1174                                  | 1        | 0.33%   |
| Pegatron KJ379AA-ABA a6400f                       | 1        | 0.33%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.33%   |
| MSI P35 Platinum(MS-7345)                         | 1        | 0.33%   |
| MSI MS-7D52                                       | 1        | 0.33%   |
| MSI MS-7C94                                       | 1        | 0.33%   |
| MSI MS-7C91                                       | 1        | 0.33%   |
| MSI MS-7C83                                       | 1        | 0.33%   |
| MSI MS-7C52                                       | 1        | 0.33%   |
| MSI MS-7B84                                       | 1        | 0.33%   |
| MSI MS-7B79                                       | 1        | 0.33%   |
| MSI MS-7B46                                       | 1        | 0.33%   |
| MSI MS-7B38                                       | 1        | 0.33%   |
| MSI MS-7B17                                       | 1        | 0.33%   |
| MSI MS-7A59                                       | 1        | 0.33%   |
| MSI MS-7A40                                       | 1        | 0.33%   |
| MSI MS-7A38                                       | 1        | 0.33%   |
| MSI MS-7996                                       | 1        | 0.33%   |
| MSI MS-7971                                       | 1        | 0.33%   |
| MSI MS-7918                                       | 1        | 0.33%   |
| MSI MS-7917                                       | 1        | 0.33%   |
| MSI MS-7885                                       | 1        | 0.33%   |
| MSI MS-7851                                       | 1        | 0.33%   |
| MSI MS-7823                                       | 1        | 0.33%   |
| MSI MS-7788                                       | 1        | 0.33%   |
| MSI MS-7693                                       | 1        | 0.33%   |
| MSI MS-7673                                       | 1        | 0.33%   |
| MSI MS-7597                                       | 1        | 0.33%   |
| MSI Elite 7100 Microtower PC                      | 1        | 0.33%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.33%   |
| Lenovo ThinkCentre M92p 3227D13                   | 1        | 0.33%   |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.33%   |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.33%   |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.33%   |
| Lenovo ThinkCentre M55E 9632BU8                   | 1        | 0.33%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.33%   |
| Inventec D CLASS                                  | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 15       | 4.95%   |
| Dell OptiPlex          | 13       | 4.29%   |
| ASUS ROG               | 11       | 3.63%   |
| ASUS TUF               | 9        | 2.97%   |
| ASUS All               | 8        | 2.64%   |
| HP Compaq              | 7        | 2.31%   |
| Lenovo ThinkCentre     | 5        | 1.65%   |
| Gigabyte Z390          | 5        | 1.65%   |
| ASUS P8H61-M           | 5        | 1.65%   |
| Dell Precision         | 4        | 1.32%   |
| MSI MS-7C02            | 3        | 0.99%   |
| HP ProDesk             | 3        | 0.99%   |
| Gigabyte X570          | 3        | 0.99%   |
| ASUS SABERTOOTH        | 3        | 0.99%   |
| ASUS M5A78L-M          | 3        | 0.99%   |
| Acer Aspire            | 3        | 0.99%   |
| Wibtek H61-M           | 2        | 0.66%   |
| Pegatron IPMH61P1      | 2        | 0.66%   |
| MSI MS-7C35            | 2        | 0.66%   |
| MSI MS-7B86            | 2        | 0.66%   |
| MSI MS-7817            | 2        | 0.66%   |
| MSI MS-7721            | 2        | 0.66%   |
| Intel H61              | 2        | 0.66%   |
| HP Pavilion            | 2        | 0.66%   |
| Gigabyte H61M-DS2      | 2        | 0.66%   |
| Gigabyte H310M         | 2        | 0.66%   |
| Gigabyte B450M         | 2        | 0.66%   |
| Gigabyte B450          | 2        | 0.66%   |
| Gigabyte A320M-S2H     | 2        | 0.66%   |
| ECS H55H-M             | 2        | 0.66%   |
| ASUS STRIKER           | 2        | 0.66%   |
| ASUS P8Z77-V           | 2        | 0.66%   |
| ASRock B450M-HDV       | 2        | 0.66%   |
| Unknown                | 2        | 0.66%   |
| T-bao MINI             | 1        | 0.33%   |
| SYS H310CH5-TI2        | 1        | 0.33%   |
| Shuttle DS61           | 1        | 0.33%   |
| Pegatron p7-1174       | 1        | 0.33%   |
| Pegatron KJ379AA-ABA   | 1        | 0.33%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.33%   |
| MSI P35                | 1        | 0.33%   |
| MSI MS-7D52            | 1        | 0.33%   |
| MSI MS-7C94            | 1        | 0.33%   |
| MSI MS-7C91            | 1        | 0.33%   |
| MSI MS-7C83            | 1        | 0.33%   |
| MSI MS-7C52            | 1        | 0.33%   |
| MSI MS-7B84            | 1        | 0.33%   |
| MSI MS-7B79            | 1        | 0.33%   |
| MSI MS-7B46            | 1        | 0.33%   |
| MSI MS-7B38            | 1        | 0.33%   |
| MSI MS-7B17            | 1        | 0.33%   |
| MSI MS-7A59            | 1        | 0.33%   |
| MSI MS-7A40            | 1        | 0.33%   |
| MSI MS-7A38            | 1        | 0.33%   |
| MSI MS-7996            | 1        | 0.33%   |
| MSI MS-7971            | 1        | 0.33%   |
| MSI MS-7918            | 1        | 0.33%   |
| MSI MS-7917            | 1        | 0.33%   |
| MSI MS-7885            | 1        | 0.33%   |
| MSI MS-7851            | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 38       | 12.54%  |
| 2018 | 35       | 11.55%  |
| 2013 | 31       | 10.23%  |
| 2011 | 28       | 9.24%   |
| 2019 | 26       | 8.58%   |
| 2010 | 21       | 6.93%   |
| 2017 | 19       | 6.27%   |
| 2020 | 18       | 5.94%   |
| 2015 | 17       | 5.61%   |
| 2014 | 15       | 4.95%   |
| 2016 | 13       | 4.29%   |
| 2008 | 12       | 3.96%   |
| 2009 | 11       | 3.63%   |
| 2021 | 10       | 3.3%    |
| 2022 | 3        | 0.99%   |
| 2007 | 3        | 0.99%   |
| 2006 | 2        | 0.66%   |
| 2005 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 303      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 291      | 96.04%  |
| Enabled  | 12       | 3.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 303      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 70       | 23.03%  |
| 8.01-16.0   | 66       | 21.71%  |
| 4.01-8.0    | 55       | 18.09%  |
| 32.01-64.0  | 51       | 16.78%  |
| 3.01-4.0    | 39       | 12.83%  |
| 64.01-256.0 | 8        | 2.63%   |
| 1.01-2.0    | 6        | 1.97%   |
| 24.01-32.0  | 5        | 1.64%   |
| 2.01-3.0    | 4        | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 126      | 36.84%  |
| 2.01-3.0   | 98       | 28.65%  |
| 3.01-4.0   | 52       | 15.2%   |
| 4.01-8.0   | 49       | 14.33%  |
| 8.01-16.0  | 8        | 2.34%   |
| 0.51-1.0   | 8        | 2.34%   |
| 32.01-64.0 | 1        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 113      | 36.22%  |
| 1      | 111      | 35.58%  |
| 3      | 41       | 13.14%  |
| 4      | 24       | 7.69%   |
| 5      | 13       | 4.17%   |
| 7      | 4        | 1.28%   |
| 6      | 4        | 1.28%   |
| 8      | 1        | 0.32%   |
| 0      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 56.31%  |
| Yes       | 135      | 43.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 300      | 99.01%  |
| No        | 3        | 0.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 51.47%  |
| Yes       | 149      | 48.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 202      | 66.01%  |
| Yes       | 104      | 33.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 31       | 10.2%   |
| Germany      | 30       | 9.87%   |
| Brazil       | 22       | 7.24%   |
| UK           | 19       | 6.25%   |
| Spain        | 16       | 5.26%   |
| Russia       | 14       | 4.61%   |
| Canada       | 14       | 4.61%   |
| France       | 12       | 3.95%   |
| Indonesia    | 11       | 3.62%   |
| Poland       | 8        | 2.63%   |
| Mexico       | 8        | 2.63%   |
| Turkey       | 7        | 2.3%    |
| Italy        | 7        | 2.3%    |
| India        | 7        | 2.3%    |
| Argentina    | 6        | 1.97%   |
| Austria      | 5        | 1.64%   |
| Australia    | 5        | 1.64%   |
| Sweden       | 4        | 1.32%   |
| Netherlands  | 4        | 1.32%   |
| Egypt        | 4        | 1.32%   |
| Ukraine      | 3        | 0.99%   |
| Switzerland  | 3        | 0.99%   |
| Malaysia     | 3        | 0.99%   |
| Japan        | 3        | 0.99%   |
| Hong Kong    | 3        | 0.99%   |
| Greece       | 3        | 0.99%   |
| Finland      | 3        | 0.99%   |
| Czechia      | 3        | 0.99%   |
| Bulgaria     | 3        | 0.99%   |
| Venezuela    | 2        | 0.66%   |
| Romania      | 2        | 0.66%   |
| Philippines  | 2        | 0.66%   |
| Iran         | 2        | 0.66%   |
| Costa Rica   | 2        | 0.66%   |
| Colombia     | 2        | 0.66%   |
| China        | 2        | 0.66%   |
| Belgium      | 2        | 0.66%   |
| Vietnam      | 1        | 0.33%   |
| Thailand     | 1        | 0.33%   |
| Sri Lanka    | 1        | 0.33%   |
| South Africa | 1        | 0.33%   |
| Sint Maarten | 1        | 0.33%   |
| Serbia       | 1        | 0.33%   |
| Portugal     | 1        | 0.33%   |
| Panama       | 1        | 0.33%   |
| Norway       | 1        | 0.33%   |
| New Zealand  | 1        | 0.33%   |
| Luxembourg   | 1        | 0.33%   |
| Lithuania    | 1        | 0.33%   |
| Kosovo       | 1        | 0.33%   |
| Kenya        | 1        | 0.33%   |
| Israel       | 1        | 0.33%   |
| Ireland      | 1        | 0.33%   |
| Hungary      | 1        | 0.33%   |
| Eswatini     | 1        | 0.33%   |
| Estonia      | 1        | 0.33%   |
| El Salvador  | 1        | 0.33%   |
| Ecuador      | 1        | 0.33%   |
| Denmark      | 1        | 0.33%   |
| Croatia      | 1        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Warsaw               | 4        | 1.24%   |
| Rio de Janeiro       | 4        | 1.24%   |
| Paris                | 4        | 1.24%   |
| Fortaleza            | 4        | 1.24%   |
| Berlin               | 4        | 1.24%   |
| Vienna               | 3        | 0.93%   |
| Sofia                | 3        | 0.93%   |
| Moscow               | 3        | 0.93%   |
| Montreal             | 3        | 0.93%   |
| Istanbul             | 3        | 0.93%   |
| Hamburg              | 3        | 0.93%   |
| Brisbane             | 3        | 0.93%   |
| Tangerang            | 2        | 0.62%   |
| Sao Paulo            | 2        | 0.62%   |
| Novosibirsk          | 2        | 0.62%   |
| Morelia              | 2        | 0.62%   |
| Montenegro           | 2        | 0.62%   |
| Milan                | 2        | 0.62%   |
| Mexico City          | 2        | 0.62%   |
| Kazan???             | 2        | 0.62%   |
| George Town          | 2        | 0.62%   |
| Central              | 2        | 0.62%   |
| Cairo                | 2        | 0.62%   |
| Bogor                | 2        | 0.62%   |
| Zagreb               | 1        | 0.31%   |
| Zabrze               | 1        | 0.31%   |
| Yucca Valley         | 1        | 0.31%   |
| Yokohama             | 1        | 0.31%   |
| Yarang               | 1        | 0.31%   |
| Xicheng District     | 1        | 0.31%   |
| Wroclaw              | 1        | 0.31%   |
| Woolloongabba        | 1        | 0.31%   |
| Wolgast              | 1        | 0.31%   |
| Wigan                | 1        | 0.31%   |
| Vit??ria             | 1        | 0.31%   |
| Villahermosa         | 1        | 0.31%   |
| Vigo                 | 1        | 0.31%   |
| Vanse                | 1        | 0.31%   |
| Vancouver            | 1        | 0.31%   |
| Valinhos             | 1        | 0.31%   |
| Tucson               | 1        | 0.31%   |
| Tseung Kwan O        | 1        | 0.31%   |
| Trivandrum           | 1        | 0.31%   |
| Tournus              | 1        | 0.31%   |
| Toronto              | 1        | 0.31%   |
| Tolyatti             | 1        | 0.31%   |
| Thrissur             | 1        | 0.31%   |
| Thessaloniki         | 1        | 0.31%   |
| Theodore             | 1        | 0.31%   |
| Tel Aviv             | 1        | 0.31%   |
| Tehran               | 1        | 0.31%   |
| Tanta                | 1        | 0.31%   |
| Tampere              | 1        | 0.31%   |
| Tallinn              | 1        | 0.31%   |
| Talavera de la Reina | 1        | 0.31%   |
| Taiping              | 1        | 0.31%   |
| Sydney               | 1        | 0.31%   |
| Surgut               | 1        | 0.31%   |
| Suresnes             | 1        | 0.31%   |
| Sukabumi             | 1        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 102      | 143    | 18.65%  |
| WDC                       | 99       | 151    | 18.1%   |
| Samsung Electronics       | 78       | 134    | 14.26%  |
| Kingston                  | 48       | 71     | 8.78%   |
| SanDisk                   | 28       | 31     | 5.12%   |
| Crucial                   | 28       | 37     | 5.12%   |
| Toshiba                   | 27       | 47     | 4.94%   |
| Hitachi                   | 15       | 16     | 2.74%   |
| Intel                     | 10       | 10     | 1.83%   |
| A-DATA Technology         | 10       | 11     | 1.83%   |
| Unknown                   | 9        | 18     | 1.65%   |
| Phison                    | 6        | 7      | 1.1%    |
| OCZ                       | 5        | 7      | 0.91%   |
| Micron/Crucial Technology | 5        | 10     | 0.91%   |
| HGST                      | 5        | 9      | 0.91%   |
| China                     | 5        | 5      | 0.91%   |
| Transcend                 | 4        | 4      | 0.73%   |
| PNY                       | 4        | 9      | 0.73%   |
| Micron Technology         | 4        | 4      | 0.73%   |
| Corsair                   | 4        | 4      | 0.73%   |
| Team                      | 3        | 4      | 0.55%   |
| Plextor                   | 3        | 3      | 0.55%   |
| Patriot                   | 3        | 3      | 0.55%   |
| Maxtor                    | 3        | 3      | 0.55%   |
| Intenso                   | 3        | 3      | 0.55%   |
| ASMT                      | 3        | 3      | 0.55%   |
| Realtek Semiconductor     | 2        | 2      | 0.37%   |
| LITEON                    | 2        | 2      | 0.37%   |
| JMicron Technology        | 2        | 2      | 0.37%   |
| Goodram                   | 2        | 5      | 0.37%   |
| Gigabyte Technology       | 2        | 2      | 0.37%   |
| XPG                       | 1        | 1      | 0.18%   |
| WDC WDS                   | 1        | 1      | 0.18%   |
| USB3.1                    | 1        | 1      | 0.18%   |
| tigo                      | 1        | 1      | 0.18%   |
| SPCC                      | 1        | 1      | 0.18%   |
| SK hynix                  | 1        | 1      | 0.18%   |
| Silicon Motion            | 1        | 1      | 0.18%   |
| ROG                       | 1        | 1      | 0.18%   |
| OWC                       | 1        | 1      | 0.18%   |
| OCZ-VERTEX3               | 1        | 1      | 0.18%   |
| OCZ-VERTEX2               | 1        | 2      | 0.18%   |
| Netac                     | 1        | 1      | 0.18%   |
| MidasForce                | 1        | 1      | 0.18%   |
| Leven                     | 1        | 1      | 0.18%   |
| KingSpec                  | 1        | 1      | 0.18%   |
| Kingmax                   | 1        | 1      | 0.18%   |
| HS-SSD-C100               | 1        | 1      | 0.18%   |
| Hikvision                 | 1        | 1      | 0.18%   |
| Hewlett-Packard           | 1        | 1      | 0.18%   |
| GeIL                      | 1        | 1      | 0.18%   |
| GALAX                     | 1        | 1      | 0.18%   |
| Apple                     | 1        | 1      | 0.18%   |
| Apacer                    | 1        | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD        | 14       | 2.24%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 11       | 1.76%   |
| WDC WD10EZEX-08WN4A0 1TB               | 9        | 1.44%   |
| Samsung SSD 850 EVO 250GB              | 9        | 1.44%   |
| Kingston SA400S37120G 120GB SSD        | 8        | 1.28%   |
| Samsung NVMe SSD Drive 1TB             | 7        | 1.12%   |
| Kingston SV300S37A120G 120GB SSD       | 7        | 1.12%   |
| Toshiba DT01ACA100 1TB                 | 6        | 0.96%   |
| Toshiba DT01ACA050 500GB               | 6        | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB         | 6        | 0.96%   |
| Seagate ST1000DM003-1ER162 1TB         | 6        | 0.96%   |
| Samsung SSD 860 EVO 250GB              | 6        | 0.96%   |
| Crucial CT240BX500SSD1 240GB           | 6        | 0.96%   |
| Seagate ST500DM002-1BD142 500GB        | 5        | 0.8%    |
| Seagate ST3500418AS 500GB              | 5        | 0.8%    |
| Samsung SSD 860 EVO 1TB                | 5        | 0.8%    |
| WDC WD5000AAKX-00ERMA0 500GB           | 4        | 0.64%   |
| WDC WD5000AAKX-001CA0 500GB            | 4        | 0.64%   |
| Seagate ST3500312CS 500GB              | 4        | 0.64%   |
| Seagate ST31000528AS 1TB               | 4        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB         | 4        | 0.64%   |
| SanDisk SSD PLUS 480GB                 | 4        | 0.64%   |
| SanDisk NVMe SSD Drive 500GB           | 4        | 0.64%   |
| Samsung SSD 860 EVO 500GB              | 4        | 0.64%   |
| Samsung SSD 850 PRO 256GB              | 4        | 0.64%   |
| Samsung SSD 850 EVO 500GB              | 4        | 0.64%   |
| Samsung SSD 840 EVO 120GB              | 4        | 0.64%   |
| Phison NVMe SSD Drive 1TB              | 4        | 0.64%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 4        | 0.64%   |
| WDC WD5000AAKS-00UU3A0 500GB           | 3        | 0.48%   |
| WDC WD5000AAKS-00A7B2 500GB            | 3        | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB               | 3        | 0.48%   |
| WDC WD10EURX-63UY4Y0 1TB               | 3        | 0.48%   |
| Unknown SD/MMC 16GB                    | 3        | 0.48%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 3        | 0.48%   |
| Toshiba HDWD110 1TB                    | 3        | 0.48%   |
| Seagate ST3250310AS 250GB              | 3        | 0.48%   |
| Seagate ST3160815AS 160GB              | 3        | 0.48%   |
| Seagate ST250DM000-1BD141 250GB        | 3        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB         | 3        | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB         | 3        | 0.48%   |
| SanDisk SSD PLUS 240GB                 | 3        | 0.48%   |
| Samsung SSD 870 QVO 1TB                | 3        | 0.48%   |
| Samsung SSD 840 EVO 500GB              | 3        | 0.48%   |
| Samsung SSD 840 EVO 250GB              | 3        | 0.48%   |
| Samsung NVMe SSD Drive 256GB           | 3        | 0.48%   |
| Kingston SA400S37480G 480GB SSD        | 3        | 0.48%   |
| Kingston NVMe SSD Drive 1TB            | 3        | 0.48%   |
| Intel NVMe SSD Drive 512GB             | 3        | 0.48%   |
| Crucial CT240BX200SSD1 240GB           | 3        | 0.48%   |
| Crucial CT120BX300SSD1 120GB           | 3        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB            | 3        | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 2        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2        | 0.32%   |
| WDC WD5000AAKX-003CA0 500GB            | 2        | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB               | 2        | 0.32%   |
| WDC WD20EARX-00PASB0 2TB               | 2        | 0.32%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2        | 0.32%   |
| WDC WD10EZEX-22MFCA0 1TB               | 2        | 0.32%   |
| WDC WD10EZEX-08M2NA0 1TB               | 2        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 99       | 137    | 38.98%  |
| WDC                 | 86       | 126    | 33.86%  |
| Toshiba             | 26       | 46     | 10.24%  |
| Samsung Electronics | 15       | 17     | 5.91%   |
| Hitachi             | 15       | 16     | 5.91%   |
| HGST                | 5        | 9      | 1.97%   |
| Unknown             | 2        | 3      | 0.79%   |
| Maxtor              | 2        | 2      | 0.79%   |
| ASMT                | 2        | 2      | 0.79%   |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| Apple               | 1        | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 51       | 76     | 22.08%  |
| Kingston            | 42       | 53     | 18.18%  |
| Crucial             | 27       | 35     | 11.69%  |
| SanDisk             | 22       | 23     | 9.52%   |
| WDC                 | 14       | 21     | 6.06%   |
| A-DATA Technology   | 9        | 10     | 3.9%    |
| OCZ                 | 5        | 7      | 2.16%   |
| Intel               | 5        | 5      | 2.16%   |
| China               | 5        | 5      | 2.16%   |
| Transcend           | 4        | 4      | 1.73%   |
| PNY                 | 4        | 9      | 1.73%   |
| Corsair             | 4        | 4      | 1.73%   |
| Team                | 3        | 4      | 1.3%    |
| Plextor             | 3        | 3      | 1.3%    |
| Patriot             | 3        | 3      | 1.3%    |
| Intenso             | 3        | 3      | 1.3%    |
| Micron Technology   | 2        | 2      | 0.87%   |
| LITEON              | 2        | 2      | 0.87%   |
| Goodram             | 2        | 5      | 0.87%   |
| WDC WDS             | 1        | 1      | 0.43%   |
| Toshiba             | 1        | 1      | 0.43%   |
| tigo                | 1        | 1      | 0.43%   |
| SPCC                | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| Seagate             | 1        | 2      | 0.43%   |
| ROG                 | 1        | 1      | 0.43%   |
| OWC                 | 1        | 1      | 0.43%   |
| OCZ-VERTEX3         | 1        | 1      | 0.43%   |
| OCZ-VERTEX2         | 1        | 2      | 0.43%   |
| MidasForce          | 1        | 1      | 0.43%   |
| Maxtor              | 1        | 1      | 0.43%   |
| Leven               | 1        | 1      | 0.43%   |
| KingSpec            | 1        | 1      | 0.43%   |
| Kingmax             | 1        | 1      | 0.43%   |
| HS-SSD-C100         | 1        | 1      | 0.43%   |
| Hikvision           | 1        | 1      | 0.43%   |
| Gigabyte Technology | 1        | 1      | 0.43%   |
| GeIL                | 1        | 1      | 0.43%   |
| GALAX               | 1        | 1      | 0.43%   |
| Apacer              | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 203      | 360    | 43.66%  |
| SSD     | 186      | 297    | 40%     |
| NVMe    | 63       | 105    | 13.55%  |
| Unknown | 11       | 20     | 2.37%   |
| MMC     | 2        | 2      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 284      | 643    | 76.55%  |
| NVMe | 63       | 105    | 16.98%  |
| SAS  | 22       | 34     | 5.93%   |
| MMC  | 2        | 2      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 234      | 415    | 59.69%  |
| 0.51-1.0   | 103      | 157    | 26.28%  |
| 1.01-2.0   | 23       | 35     | 5.87%   |
| 2.01-3.0   | 13       | 27     | 3.32%   |
| 3.01-4.0   | 10       | 12     | 2.55%   |
| 4.01-10.0  | 9        | 11     | 2.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 98       | 30.43%  |
| 251-500        | 74       | 22.98%  |
| 501-1000       | 54       | 16.77%  |
| 1001-2000      | 29       | 9.01%   |
| 51-100         | 20       | 6.21%   |
| More than 3000 | 18       | 5.59%   |
| 21-50          | 18       | 5.59%   |
| 2001-3000      | 9        | 2.8%    |
| 1-20           | 2        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 125      | 36.55%  |
| 21-50          | 60       | 17.54%  |
| 101-250        | 44       | 12.87%  |
| 51-100         | 44       | 12.87%  |
| 251-500        | 24       | 7.02%   |
| 501-1000       | 22       | 6.43%   |
| 1001-2000      | 13       | 3.8%    |
| More than 3000 | 6        | 1.75%   |
| 2001-3000      | 4        | 1.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 4.35%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 4.35%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 4.35%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 4.35%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 4.35%   |
| Seagate ST3500414CS 500GB         | 1        | 2      | 4.35%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 4.35%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 4.35%   |
| Seagate ST3160813AS 160GB         | 1        | 1      | 4.35%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 4.35%   |
| SanDisk SSD PLUS 240GB            | 1        | 1      | 4.35%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 4.35%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 4.35%   |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 4.35%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 4.35%   |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 4.35%   |
| Hitachi HDT721064SLA360 640GB     | 1        | 1      | 4.35%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 4.35%   |
| HGST HUS724030ALA640 3TB          | 1        | 1      | 4.35%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 30.43%  |
| Seagate             | 6        | 7      | 26.09%  |
| Samsung Electronics | 3        | 3      | 13.04%  |
| Hitachi             | 3        | 3      | 13.04%  |
| SanDisk             | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 35%     |
| Seagate             | 6        | 7      | 30%     |
| Samsung Electronics | 3        | 3      | 15%     |
| Hitachi             | 3        | 3      | 15%     |
| HGST                | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 21     | 85%     |
| SSD  | 3        | 3      | 15%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 266      | 675    | 82.35%  |
| Works    | 38       | 85     | 11.76%  |
| Malfunc  | 19       | 24     | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 208      | 50.86%  |
| AMD                         | 83       | 20.29%  |
| Samsung Electronics         | 31       | 7.58%   |
| ASMedia Technology          | 14       | 3.42%   |
| Nvidia                      | 11       | 2.69%   |
| SanDisk                     | 9        | 2.2%    |
| Marvell Technology Group    | 9        | 2.2%    |
| JMicron Technology          | 9        | 2.2%    |
| Kingston Technology Company | 8        | 1.96%   |
| Phison Electronics          | 6        | 1.47%   |
| Micron/Crucial Technology   | 6        | 1.47%   |
| Realtek Semiconductor       | 3        | 0.73%   |
| Seagate Technology          | 2        | 0.49%   |
| Micron Technology           | 2        | 0.49%   |
| LSI Logic / Symbios Logic   | 2        | 0.49%   |
| ADATA Technology            | 2        | 0.49%   |
| VIA Technologies            | 1        | 0.24%   |
| Silicon Motion              | 1        | 0.24%   |
| Silicon Image               | 1        | 0.24%   |
| Broadcom / LSI              | 1        | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 52       | 9.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 27       | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24       | 4.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23       | 4.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 3.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17       | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17       | 3.24%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15       | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 2.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.53%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.53%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 1.34%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.34%   |
| Kingston Company A2000 NVMe SSD                                                         | 6        | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5        | 0.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 0.95%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.76%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.76%   |
| Intel SSD 660P Series                                                                   | 4        | 0.76%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.57%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 3        | 0.57%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 3        | 0.57%   |
| Nvidia MCP55 SATA Controller                                                            | 3        | 0.57%   |
| Nvidia MCP55 IDE                                                                        | 3        | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.57%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.38%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.38%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.38%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.38%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.38%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.38%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.38%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2        | 0.38%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.38%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 0.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 234      | 58.35%  |
| IDE  | 76       | 18.95%  |
| NVMe | 65       | 16.21%  |
| RAID | 22       | 5.49%   |
| SAS  | 3        | 0.75%   |
| SCSI | 1        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 211      | 69.64%  |
| AMD    | 92       | 30.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 10       | 3.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 2.64%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.32%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 4        | 1.32%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 1.32%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 1.32%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.32%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.32%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 0.99%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.99%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.99%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 0.99%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.99%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 0.99%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 0.99%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 0.99%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.99%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3        | 0.99%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 0.99%   |
| AMD FX-6100 Six-Core Processor              | 3        | 0.99%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.66%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.66%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.66%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 0.66%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.66%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.66%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.66%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.66%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.66%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 2        | 0.66%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 0.66%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.66%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.66%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.66%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 0.66%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 2        | 0.66%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 0.66%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.66%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.66%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.66%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.66%   |
| AMD Phenom II X4 965 Processor              | 2        | 0.66%   |
| AMD Phenom II X4 955 Processor              | 2        | 0.66%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.66%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 66       | 21.78%  |
| Intel Core i7           | 46       | 15.18%  |
| Intel Core i3           | 25       | 8.25%   |
| AMD Ryzen 5             | 25       | 8.25%   |
| Intel Xeon              | 20       | 6.6%    |
| AMD Ryzen 7             | 14       | 4.62%   |
| Intel Celeron           | 12       | 3.96%   |
| Intel Core 2 Quad       | 9        | 2.97%   |
| AMD FX                  | 9        | 2.97%   |
| Intel Core 2 Duo        | 8        | 2.64%   |
| AMD Phenom II X4        | 8        | 2.64%   |
| AMD Ryzen 9             | 7        | 2.31%   |
| Other                   | 6        | 1.98%   |
| Intel Pentium           | 6        | 1.98%   |
| AMD Ryzen 3             | 6        | 1.98%   |
| Intel Core i9           | 4        | 1.32%   |
| AMD A8                  | 4        | 1.32%   |
| Intel Pentium Dual-Core | 3        | 0.99%   |
| Intel Atom              | 3        | 0.99%   |
| AMD Athlon II X4        | 3        | 0.99%   |
| AMD A4                  | 3        | 0.99%   |
| AMD Phenom              | 2        | 0.66%   |
| AMD Athlon II X2        | 2        | 0.66%   |
| AMD Athlon              | 2        | 0.66%   |
| AMD A10                 | 2        | 0.66%   |
| Intel Pentium Dual      | 1        | 0.33%   |
| Intel Pentium D         | 1        | 0.33%   |
| Intel Pentium 4         | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD G                   | 1        | 0.33%   |
| AMD Athlon X4           | 1        | 0.33%   |
| AMD Athlon II X3        | 1        | 0.33%   |
| AMD A6                  | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 140      | 45.9%   |
| 2      | 65       | 21.31%  |
| 6      | 41       | 13.44%  |
| 8      | 33       | 10.82%  |
| 12     | 9        | 2.95%   |
| 3      | 7        | 2.3%    |
| 1      | 7        | 2.3%    |
| 16     | 2        | 0.66%   |
| 10     | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 298      | 98.35%  |
| 2      | 5        | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 162      | 53.29%  |
| 1      | 142      | 46.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 299      | 98.36%  |
| Unknown        | 5        | 1.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 34       | 10.97%  |
| 0x206a7    | 33       | 10.65%  |
| 0x306a9    | 24       | 7.74%   |
| Unknown    | 21       | 6.77%   |
| 0x08701021 | 15       | 4.84%   |
| 0x906ea    | 10       | 3.23%   |
| 0x906e9    | 9        | 2.9%    |
| 0x506e3    | 9        | 2.9%    |
| 0x1067a    | 9        | 2.9%    |
| 0x0800820d | 8        | 2.58%   |
| 0x906ed    | 7        | 2.26%   |
| 0x906eb    | 7        | 2.26%   |
| 0x08108109 | 6        | 1.94%   |
| 0x010000c8 | 6        | 1.94%   |
| 0x6fb      | 5        | 1.61%   |
| 0x206d7    | 5        | 1.61%   |
| 0x20652    | 5        | 1.61%   |
| 0x06000852 | 5        | 1.61%   |
| 0xa0671    | 4        | 1.29%   |
| 0x106a5    | 4        | 1.29%   |
| 0x10676    | 4        | 1.29%   |
| 0x08701013 | 4        | 1.29%   |
| 0x08001138 | 4        | 1.29%   |
| 0x06001119 | 4        | 1.29%   |
| 0x0600063e | 4        | 1.29%   |
| 0x010000db | 4        | 1.29%   |
| 0xa0655    | 3        | 0.97%   |
| 0x20655    | 3        | 0.97%   |
| 0x106e5    | 3        | 0.97%   |
| 0x0a201016 | 3        | 0.97%   |
| 0x0600611a | 3        | 0.97%   |
| 0x06003106 | 3        | 0.97%   |
| 0xa0653    | 2        | 0.65%   |
| 0x906ec    | 2        | 0.65%   |
| 0x406c4    | 2        | 0.65%   |
| 0x306e4    | 2        | 0.65%   |
| 0x0a50000c | 2        | 0.65%   |
| 0x08101016 | 2        | 0.65%   |
| 0x0810100b | 2        | 0.65%   |
| 0x0800820b | 2        | 0.65%   |
| 0xf47      | 1        | 0.32%   |
| 0xf43      | 1        | 0.32%   |
| 0x90672    | 1        | 0.32%   |
| 0x806c1    | 1        | 0.32%   |
| 0x706a8    | 1        | 0.32%   |
| 0x6fd      | 1        | 0.32%   |
| 0x6f7      | 1        | 0.32%   |
| 0x6f6      | 1        | 0.32%   |
| 0x40671    | 1        | 0.32%   |
| 0x306f2    | 1        | 0.32%   |
| 0x30678    | 1        | 0.32%   |
| 0x30673    | 1        | 0.32%   |
| 0x206c2    | 1        | 0.32%   |
| 0x106ca    | 1        | 0.32%   |
| 0x10677    | 1        | 0.32%   |
| 0x0a201205 | 1        | 0.32%   |
| 0x0a201009 | 1        | 0.32%   |
| 0x08101007 | 1        | 0.32%   |
| 0x08001137 | 1        | 0.32%   |
| 0x08001129 | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 40       | 13.2%   |
| Haswell          | 39       | 12.87%  |
| KabyLake         | 38       | 12.54%  |
| IvyBridge        | 26       | 8.58%   |
| Zen 2            | 19       | 6.27%   |
| Zen+             | 17       | 5.61%   |
| K10              | 16       | 5.28%   |
| Penryn           | 14       | 4.62%   |
| Zen              | 12       | 3.96%   |
| Westmere         | 9        | 2.97%   |
| Skylake          | 9        | 2.97%   |
| Piledriver       | 9        | 2.97%   |
| Core             | 9        | 2.97%   |
| Zen 3            | 7        | 2.31%   |
| Nehalem          | 7        | 2.31%   |
| CometLake        | 5        | 1.65%   |
| Silvermont       | 4        | 1.32%   |
| Icelake          | 4        | 1.32%   |
| Bulldozer        | 4        | 1.32%   |
| Steamroller      | 3        | 0.99%   |
| Excavator        | 3        | 0.99%   |
| NetBurst         | 2        | 0.66%   |
| TigerLake        | 1        | 0.33%   |
| K10 Llano        | 1        | 0.33%   |
| Goldmont plus    | 1        | 0.33%   |
| Broadwell        | 1        | 0.33%   |
| Bonnell          | 1        | 0.33%   |
| Bobcat           | 1        | 0.33%   |
| Alderlake Hybrid | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 128      | 38.67%  |
| AMD              | 106      | 32.02%  |
| Intel            | 95       | 28.7%   |
| Conexant Systems | 1        | 0.3%    |
| ATI Technologies | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 5.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 5.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16       | 4.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 3.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 2.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7        | 2.06%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6        | 1.77%   |
| Intel HD Graphics 530                                                                    | 6        | 1.77%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5        | 1.47%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 5        | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.47%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5        | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 1.47%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.47%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 5        | 1.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.18%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.18%   |
| Intel HD Graphics 630                                                                    | 4        | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.18%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4        | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 0.88%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.88%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3        | 0.88%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 3        | 0.88%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 3        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.88%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 3        | 0.88%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 3        | 0.88%   |
| AMD RS880 [Radeon HD 4200]                                                               | 3        | 0.88%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3        | 0.88%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 0.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 0.88%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.59%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2        | 0.59%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.59%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 2        | 0.59%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2        | 0.59%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 2        | 0.59%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2        | 0.59%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2        | 0.59%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2        | 0.59%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 2        | 0.59%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.59%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.59%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.59%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2        | 0.59%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 2        | 0.59%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                                         | 2        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 119      | 38.89%  |
| 1 x AMD                        | 95       | 31.05%  |
| 1 x Intel                      | 74       | 24.18%  |
| Intel + Nvidia                 | 5        | 1.63%   |
| 2 x AMD                        | 4        | 1.31%   |
| Intel + AMD                    | 4        | 1.31%   |
| AMD + Nvidia                   | 2        | 0.65%   |
| 2 x Nvidia                     | 1        | 0.33%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.33%   |
| Intel + 2 x AMD                | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 219      | 71.34%  |
| Proprietary | 82       | 26.71%  |
| Unknown     | 6        | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 27.42%  |
| 1.01-2.0   | 64       | 20.65%  |
| 0.51-1.0   | 41       | 13.23%  |
| 3.01-4.0   | 37       | 11.94%  |
| 7.01-8.0   | 32       | 10.32%  |
| 0.01-0.5   | 26       | 8.39%   |
| 5.01-6.0   | 15       | 4.84%   |
| 8.01-16.0  | 6        | 1.94%   |
| 2.01-3.0   | 4        | 1.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 56       | 16.67%  |
| Goldstar             | 37       | 11.01%  |
| Hewlett-Packard      | 29       | 8.63%   |
| Dell                 | 28       | 8.33%   |
| Acer                 | 28       | 8.33%   |
| AOC                  | 20       | 5.95%   |
| Ancor Communications | 18       | 5.36%   |
| BenQ                 | 16       | 4.76%   |
| Philips              | 15       | 4.46%   |
| LG Electronics       | 14       | 4.17%   |
| Lenovo               | 7        | 2.08%   |
| ViewSonic            | 6        | 1.79%   |
| Unknown              | 6        | 1.79%   |
| Vizio                | 3        | 0.89%   |
| NEC Computers        | 3        | 0.89%   |
| HPN                  | 3        | 0.89%   |
| Fujitsu Siemens      | 3        | 0.89%   |
| ___                  | 2        | 0.6%    |
| Iiyama               | 2        | 0.6%    |
| Grundig              | 2        | 0.6%    |
| CHR                  | 2        | 0.6%    |
| AUS                  | 2        | 0.6%    |
| Apple                | 2        | 0.6%    |
| Unknown              | 2        | 0.6%    |
| Vestel               | 1        | 0.3%    |
| TBD                  | 1        | 0.3%    |
| SPC                  | 1        | 0.3%    |
| Sony                 | 1        | 0.3%    |
| SKY                  | 1        | 0.3%    |
| Sharp                | 1        | 0.3%    |
| SAC                  | 1        | 0.3%    |
| Ruijiang             | 1        | 0.3%    |
| PDA                  | 1        | 0.3%    |
| Onkyo                | 1        | 0.3%    |
| MSI                  | 1        | 0.3%    |
| Mi                   | 1        | 0.3%    |
| LLP                  | 1        | 0.3%    |
| LLL                  | 1        | 0.3%    |
| Lenovo Group Limited | 1        | 0.3%    |
| KIV                  | 1        | 0.3%    |
| ITR INFOTRONIC       | 1        | 0.3%    |
| ITE                  | 1        | 0.3%    |
| IOD                  | 1        | 0.3%    |
| IBM                  | 1        | 0.3%    |
| HOP                  | 1        | 0.3%    |
| HKC                  | 1        | 0.3%    |
| Hitachi              | 1        | 0.3%    |
| Haier                | 1        | 0.3%    |
| Element              | 1        | 0.3%    |
| Eizo                 | 1        | 0.3%    |
| Denver               | 1        | 0.3%    |
| CHD                  | 1        | 0.3%    |
| BOE                  | 1        | 0.3%    |
| ASUSTek Computer     | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 4        | 1.12%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch  | 3        | 0.84%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 3        | 0.84%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.84%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.84%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 3        | 0.84%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.84%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.56%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                     | 2        | 0.56%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                              | 2        | 0.56%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 2        | 0.56%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch      | 2        | 0.56%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2        | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 0.56%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                  | 2        | 0.56%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 2        | 0.56%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2        | 0.56%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.56%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                     | 2        | 0.56%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 0.56%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 0.56%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 2        | 0.56%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.56%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2        | 0.56%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                    | 2        | 0.56%   |
| Unknown                                                               | 2        | 0.56%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.28%   |
| ___ LCD TV ___0101 1360x768                                           | 1        | 0.28%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                     | 1        | 0.28%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                    | 1        | 0.28%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                   | 1        | 0.28%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 1        | 0.28%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1        | 0.28%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1        | 0.28%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch         | 1        | 0.28%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch          | 1        | 0.28%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1        | 0.28%   |
| ViewSonic LCD Monitor VX2260WM                                        | 1        | 0.28%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                             | 1        | 0.28%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.28%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.28%   |
| Unknown LCD Monitor VIE LED MONITOR 1920x1080                         | 1        | 0.28%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                            | 1        | 0.28%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                         | 1        | 0.28%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                  | 1        | 0.28%   |
| Sony TV SNYD703 1360x768                                              | 1        | 0.28%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                  | 1        | 0.28%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                       | 1        | 0.28%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1        | 0.28%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch     | 1        | 0.28%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch     | 1        | 0.28%   |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch     | 1        | 0.28%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1        | 0.28%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch  | 1        | 0.28%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch  | 1        | 0.28%   |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch  | 1        | 0.28%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.28%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch   | 1        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 140      | 42.68%  |
| 3840x2160 (4K)     | 24       | 7.32%   |
| 2560x1440 (QHD)    | 24       | 7.32%   |
| 1680x1050 (WSXGA+) | 23       | 7.01%   |
| 1600x900 (HD+)     | 19       | 5.79%   |
| 1366x768 (WXGA)    | 16       | 4.88%   |
| 1280x1024 (SXGA)   | 14       | 4.27%   |
| Unknown            | 14       | 4.27%   |
| 3840x1080          | 8        | 2.44%   |
| 1440x900 (WXGA+)   | 8        | 2.44%   |
| 1360x768           | 6        | 1.83%   |
| 2560x1080          | 5        | 1.52%   |
| 1920x1200 (WUXGA)  | 5        | 1.52%   |
| 3440x1440          | 4        | 1.22%   |
| 5120x1440          | 3        | 0.91%   |
| 2560x1600          | 2        | 0.61%   |
| 1600x1200          | 2        | 0.61%   |
| 7680x2160          | 1        | 0.3%    |
| 7680x1600          | 1        | 0.3%    |
| 5760x2160          | 1        | 0.3%    |
| 5760x1080          | 1        | 0.3%    |
| 4480x1440          | 1        | 0.3%    |
| 3968x1280          | 1        | 0.3%    |
| 3840x1600          | 1        | 0.3%    |
| 3600x1080          | 1        | 0.3%    |
| 2288x1287          | 1        | 0.3%    |
| 2048x1152          | 1        | 0.3%    |
| 1024x768 (XGA)     | 1        | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 73       | 22.12%  |
| 21      | 37       | 11.21%  |
| 27      | 32       | 9.7%    |
| 24      | 32       | 9.7%    |
| 23      | 31       | 9.39%   |
| 22      | 18       | 5.45%   |
| 19      | 16       | 4.85%   |
| 20      | 13       | 3.94%   |
| 31      | 11       | 3.33%   |
| 18      | 11       | 3.33%   |
| 17      | 8        | 2.42%   |
| 32      | 7        | 2.12%   |
| 34      | 5        | 1.52%   |
| 72      | 4        | 1.21%   |
| 54      | 4        | 1.21%   |
| 15      | 4        | 1.21%   |
| 84      | 3        | 0.91%   |
| 29      | 3        | 0.91%   |
| 49      | 2        | 0.61%   |
| 33      | 2        | 0.61%   |
| 28      | 2        | 0.61%   |
| 25      | 2        | 0.61%   |
| 57      | 1        | 0.3%    |
| 55      | 1        | 0.3%    |
| 48      | 1        | 0.3%    |
| 43      | 1        | 0.3%    |
| 40      | 1        | 0.3%    |
| 39      | 1        | 0.3%    |
| 38      | 1        | 0.3%    |
| 37      | 1        | 0.3%    |
| 26      | 1        | 0.3%    |
| 16      | 1        | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 86       | 27.04%  |
| 501-600     | 85       | 26.73%  |
| Unknown     | 73       | 22.96%  |
| 601-700     | 22       | 6.92%   |
| 701-800     | 14       | 4.4%    |
| 301-350     | 11       | 3.46%   |
| 1001-1500   | 9        | 2.83%   |
| 1501-2000   | 7        | 2.2%    |
| 351-400     | 6        | 1.89%   |
| 801-900     | 4        | 1.26%   |
| 901-1000    | 1        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 170      | 57.05%  |
| Unknown | 69       | 23.15%  |
| 16/10   | 34       | 11.41%  |
| 5/4     | 11       | 3.69%   |
| 21/9    | 8        | 2.68%   |
| 4/3     | 2        | 0.67%   |
| 32/9    | 2        | 0.67%   |
| 3/2     | 2        | 0.67%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 91       | 28.35%  |
| Unknown        | 73       | 22.74%  |
| 151-200        | 37       | 11.53%  |
| 301-350        | 33       | 10.28%  |
| 351-500        | 27       | 8.41%   |
| 141-150        | 17       | 5.3%    |
| 251-300        | 16       | 4.98%   |
| More than 1000 | 14       | 4.36%   |
| 501-1000       | 7        | 2.18%   |
| 101-110        | 3        | 0.93%   |
| 131-140        | 1        | 0.31%   |
| 111-120        | 1        | 0.31%   |
| 91-100         | 1        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 160      | 51.95%  |
| Unknown | 73       | 23.7%   |
| 101-120 | 55       | 17.86%  |
| 1-50    | 12       | 3.9%    |
| 121-160 | 8        | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 244      | 78.71%  |
| 2     | 49       | 15.81%  |
| 3     | 10       | 3.23%   |
| 0     | 7        | 2.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 193      | 43.57%  |
| Intel                           | 116      | 26.19%  |
| Qualcomm Atheros                | 23       | 5.19%   |
| Broadcom                        | 20       | 4.51%   |
| TP-Link                         | 18       | 4.06%   |
| Ralink Technology               | 13       | 2.93%   |
| Nvidia                          | 8        | 1.81%   |
| Samsung Electronics             | 7        | 1.58%   |
| Xiaomi                          | 5        | 1.13%   |
| Qualcomm Atheros Communications | 4        | 0.9%    |
| Ralink                          | 3        | 0.68%   |
| Microsoft                       | 3        | 0.68%   |
| Marvell Technology Group        | 3        | 0.68%   |
| D-Link System                   | 3        | 0.68%   |
| Linksys                         | 2        | 0.45%   |
| Huawei Technologies             | 2        | 0.45%   |
| D-Link                          | 2        | 0.45%   |
| Broadcom Limited                | 2        | 0.45%   |
| vivo                            | 1        | 0.23%   |
| VIA Technologies                | 1        | 0.23%   |
| TRENDnet                        | 1        | 0.23%   |
| Realtek                         | 1        | 0.23%   |
| OPPO Electronics                | 1        | 0.23%   |
| NetGear                         | 1        | 0.23%   |
| Motorola PCS                    | 1        | 0.23%   |
| MediaTek                        | 1        | 0.23%   |
| LG Electronics                  | 1        | 0.23%   |
| Input Club                      | 1        | 0.23%   |
| Edimax Technology               | 1        | 0.23%   |
| BUFFALO                         | 1        | 0.23%   |
| AVM                             | 1        | 0.23%   |
| ASUSTek Computer                | 1        | 0.23%   |
| Aquantia                        | 1        | 0.23%   |
| AboCom Systems                  | 1        | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 149      | 29.8%   |
| Intel I211 Gigabit Network Connection                                             | 18       | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 15       | 3%      |
| Intel Wi-Fi 6 AX200                                                               | 14       | 2.8%    |
| Realtek RTL8125 2.5GbE Controller                                                 | 12       | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                              | 12       | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 11       | 2.2%    |
| Intel Ethernet Connection (7) I219-V                                              | 9        | 1.8%    |
| Ralink MT7601U Wireless Adapter                                                   | 8        | 1.6%    |
| Intel 82579V Gigabit Network Connection                                           | 8        | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 7        | 1.4%    |
| Realtek 802.11ac NIC                                                              | 6        | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 6        | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 5        | 1%      |
| Intel Ethernet Connection I217-LM                                                 | 5        | 1%      |
| Intel 82574L Gigabit Network Connection                                           | 5        | 1%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 4        | 0.8%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 4        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 4        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 4        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 4        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 4        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 4        | 0.8%    |
| Intel Wireless-AC 9260                                                            | 4        | 0.8%    |
| Intel Ethernet Controller I225-V                                                  | 4        | 0.8%    |
| Intel Ethernet Connection I217-V                                                  | 4        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 4        | 0.8%    |
| Intel 82578DM Gigabit Network Connection                                          | 4        | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 4        | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 4        | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 3        | 0.6%    |
| TP-Link 802.11ac NIC                                                              | 3        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                     | 3        | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 3        | 0.6%    |
| Nvidia MCP77 Ethernet                                                             | 3        | 0.6%    |
| Nvidia MCP61 Ethernet                                                             | 3        | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 3        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                              | 3        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                                        | 3        | 0.6%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 3        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 0.4%    |
| Realtek RTL8187 Wireless Adapter                                                  | 2        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 2        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                     | 2        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                          | 2        | 0.4%    |
| Nvidia MCP55 Ethernet                                                             | 2        | 0.4%    |
| Intel Wireless 8260                                                               | 2        | 0.4%    |
| Intel Wireless 7260                                                               | 2        | 0.4%    |
| Intel Wireless 3165                                                               | 2        | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 2        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 0.4%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                            | 2        | 0.4%    |
| Huawei COL-L29                                                                    | 2        | 0.4%    |
| vivo 1806                                                                         | 1        | 0.2%    |
| VIA VT6105/VT6106S [Rhine-III]                                                    | 1        | 0.2%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 41       | 25%     |
| Intel                           | 40       | 24.39%  |
| TP-Link                         | 18       | 10.98%  |
| Broadcom                        | 14       | 8.54%   |
| Ralink Technology               | 13       | 7.93%   |
| Qualcomm Atheros                | 10       | 6.1%    |
| Qualcomm Atheros Communications | 4        | 2.44%   |
| Ralink                          | 3        | 1.83%   |
| Microsoft                       | 3        | 1.83%   |
| Linksys                         | 2        | 1.22%   |
| D-Link System                   | 2        | 1.22%   |
| D-Link                          | 2        | 1.22%   |
| Broadcom Limited                | 2        | 1.22%   |
| TRENDnet                        | 1        | 0.61%   |
| Realtek                         | 1        | 0.61%   |
| NetGear                         | 1        | 0.61%   |
| Marvell Technology Group        | 1        | 0.61%   |
| LG Electronics                  | 1        | 0.61%   |
| Edimax Technology               | 1        | 0.61%   |
| BUFFALO                         | 1        | 0.61%   |
| AVM                             | 1        | 0.61%   |
| ASUSTek Computer                | 1        | 0.61%   |
| AboCom Systems                  | 1        | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 14       | 8.38%   |
| Ralink MT7601U Wireless Adapter                                                   | 8        | 4.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 7        | 4.19%   |
| Realtek 802.11ac NIC                                                              | 6        | 3.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 6        | 3.59%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 4        | 2.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 4        | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 4        | 2.4%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 4        | 2.4%    |
| Intel Wireless-AC 9260                                                            | 4        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 4        | 2.4%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 4        | 2.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 4        | 2.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 1.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 3        | 1.8%    |
| TP-Link 802.11ac NIC                                                              | 3        | 1.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 3        | 1.8%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 3        | 1.8%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 3        | 1.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 1.2%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 2        | 1.2%    |
| Realtek RTL8187 Wireless Adapter                                                  | 2        | 1.2%    |
| Intel Wireless 8260                                                               | 2        | 1.2%    |
| Intel Wireless 7260                                                               | 2        | 1.2%    |
| Intel Wireless 3165                                                               | 2        | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 2        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 1.2%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.6%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 0.6%    |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.6%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                         | 1        | 0.6%    |
| TP-Link 802.11ac WLAN Adapter                                                     | 1        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                   | 1        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                           | 1        | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                   | 1        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 0.6%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.6%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                        | 1        | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 0.6%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 1        | 0.6%    |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.6%    |
| Realtek 802.11n NIC                                                               | 1        | 0.6%    |
| Ralink RT5572 Wireless Adapter                                                    | 1        | 0.6%    |
| Ralink RT5372 Wireless Adapter                                                    | 1        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                                    | 1        | 0.6%    |
| Ralink RT3072 Wireless Adapter                                                    | 1        | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 1        | 0.6%    |
| Ralink RT5592 PCIe Wireless Network Adapter                                       | 1        | 0.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 0.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                    | 1        | 0.6%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 178      | 54.6%   |
| Intel                    | 97       | 29.75%  |
| Qualcomm Atheros         | 14       | 4.29%   |
| Nvidia                   | 8        | 2.45%   |
| Samsung Electronics      | 7        | 2.15%   |
| Broadcom                 | 6        | 1.84%   |
| Xiaomi                   | 5        | 1.53%   |
| Marvell Technology Group | 2        | 0.61%   |
| Huawei Technologies      | 2        | 0.61%   |
| vivo                     | 1        | 0.31%   |
| VIA Technologies         | 1        | 0.31%   |
| OPPO Electronics         | 1        | 0.31%   |
| Motorola PCS             | 1        | 0.31%   |
| MediaTek                 | 1        | 0.31%   |
| D-Link System            | 1        | 0.31%   |
| Aquantia                 | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 149      | 44.88%  |
| Intel I211 Gigabit Network Connection                             | 18       | 5.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15       | 4.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 3.61%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 3.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 3.31%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.71%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 1.51%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 1.2%    |
| Intel Ethernet Controller I225-V                                  | 4        | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 4        | 1.2%    |
| Intel 82578DM Gigabit Network Connection                          | 4        | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.9%    |
| Nvidia MCP77 Ethernet                                             | 3        | 0.9%    |
| Nvidia MCP61 Ethernet                                             | 3        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.6%    |
| Nvidia MCP55 Ethernet                                             | 2        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.6%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 0.6%    |
| Huawei COL-L29                                                    | 2        | 0.6%    |
| vivo 1806                                                         | 1        | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.3%    |
| OPPO Find X2 Lite                                                 | 1        | 0.3%    |
| Motorola PCS moto g stylus                                        | 1        | 0.3%    |
| MediaTek TECNO SPARK 3                                            | 1        | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.3%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.3%    |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.3%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.3%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.3%    |
| Intel 82566DC Gigabit Network Connection                          | 1        | 0.3%    |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.3%    |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)          | 1        | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.3%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 0.3%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.3%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.3%    |
| Aquantia Ethernet controller                                      | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 300      | 66.37%  |
| WiFi     | 151      | 33.41%  |
| Modem    | 1        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 224      | 72.73%  |
| WiFi     | 84       | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 205      | 67.21%  |
| 2     | 82       | 26.89%  |
| 3     | 13       | 4.26%   |
| 0     | 4        | 1.31%   |
| 4     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 250      | 81.43%  |
| Yes  | 57       | 18.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 38       | 35.51%  |
| Cambridge Silicon Radio         | 36       | 33.64%  |
| Realtek Semiconductor           | 8        | 7.48%   |
| Broadcom                        | 7        | 6.54%   |
| ASUSTek Computer                | 7        | 6.54%   |
| Apple                           | 5        | 4.67%   |
| IMC Networks                    | 2        | 1.87%   |
| Belkin Components               | 2        | 1.87%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| Qcom                            | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 36       | 33.64%  |
| Intel AX200 Bluetooth                                 | 13       | 12.15%  |
| Intel Bluetooth wireless interface                    | 8        | 7.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 4.67%   |
| Realtek Bluetooth Radio                               | 4        | 3.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 3.74%   |
| Intel Bluetooth Device                                | 4        | 3.74%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 2.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 2.8%    |
| Apple Bluetooth USB Host Controller                   | 3        | 2.8%    |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 1.87%   |
| Intel AX210 Bluetooth                                 | 2        | 1.87%   |
| IMC Networks BCM20702A0                               | 2        | 1.87%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 1.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.87%   |
| Belkin Components Bluetooth Mini Dongle               | 2        | 1.87%   |
| ASUS BCM20702A0                                       | 2        | 1.87%   |
| Realtek Bluetooth 5.1 Radio                           | 1        | 0.93%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.93%   |
| Qcom Bluetooth USB                                    | 1        | 0.93%   |
| Broadcom Bluetooth dongle                             | 1        | 0.93%   |
| Broadcom Bluetooth 3.0 Dongle                         | 1        | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 0.93%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.93%   |
| ASUS Bluetooth Radio                                  | 1        | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 0.93%   |
| Apple Bluetooth HCI                                   | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 198      | 37.5%   |
| AMD                                  | 130      | 24.62%  |
| Nvidia                               | 124      | 23.48%  |
| C-Media Electronics                  | 23       | 4.36%   |
| Creative Labs                        | 11       | 2.08%   |
| Logitech                             | 7        | 1.33%   |
| Generalplus Technology               | 5        | 0.95%   |
| JMTek                                | 4        | 0.76%   |
| Creative Technology                  | 4        | 0.76%   |
| Razer USA                            | 3        | 0.57%   |
| GN Netcom                            | 2        | 0.38%   |
| Focusrite-Novation                   | 2        | 0.38%   |
| BEHRINGER International              | 2        | 0.38%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.19%   |
| Texas Instruments                    | 1        | 0.19%   |
| PreSonus Audio Electronics           | 1        | 0.19%   |
| Plantronics                          | 1        | 0.19%   |
| Native Instruments                   | 1        | 0.19%   |
| Micro Star International             | 1        | 0.19%   |
| Hewlett-Packard                      | 1        | 0.19%   |
| Fortemedia                           | 1        | 0.19%   |
| Corsair                              | 1        | 0.19%   |
| BY EDIFIER                           | 1        | 0.19%   |
| ATI Technologies                     | 1        | 0.19%   |
| ASUSTek Computer                     | 1        | 0.19%   |
| Astro Gaming                         | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 42       | 6.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 28       | 4.62%   |
| AMD Starship/Matisse HD Audio Controller                                          | 22       | 3.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 20       | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 3.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17       | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16       | 2.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16       | 2.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 16       | 2.64%   |
| Intel 200 Series PCH HD Audio                                                     | 15       | 2.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 14       | 2.31%   |
| AMD Family 17h/19h HD Audio Controller                                            | 13       | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 13       | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 11       | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11       | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 11       | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 10       | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10       | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 1.49%   |
| AMD FCH Azalia Controller                                                         | 9        | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 7        | 1.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                     | 6        | 0.99%   |
| Nvidia High Definition Audio Controller                                           | 6        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                                     | 6        | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6        | 0.99%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 0.99%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 0.99%   |
| Nvidia TU104 HD Audio Controller                                                  | 5        | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                                | 5        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 0.83%   |
| Generalplus Technology IMYB 7.1 Channel                                           | 5        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.66%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 4        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.66%   |
| JMTek USB PnP Audio Device                                                        | 4        | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4        | 0.66%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.66%   |
| Nvidia MCP55 High Definition Audio                                                | 3        | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 0.5%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 0.5%    |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 3        | 0.5%    |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 3        | 0.5%    |
| C-Media Electronics USB Audio Device                                              | 3        | 0.5%    |
| AMD Trinity HDMI Audio Controller                                                 | 3        | 0.5%    |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 3        | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 0.5%    |
| AMD Kaveri HDMI/DP Audio Controller                                               | 3        | 0.5%    |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 25       | 25.77%  |
| Unknown             | 11       | 11.34%  |
| Samsung Electronics | 11       | 11.34%  |
| SK hynix            | 9        | 9.28%   |
| Corsair             | 9        | 9.28%   |
| G.Skill             | 8        | 8.25%   |
| Crucial             | 7        | 7.22%   |
| Patriot             | 3        | 3.09%   |
| Micron Technology   | 3        | 3.09%   |
| Ramaxel Technology  | 2        | 2.06%   |
| Nanya Technology    | 2        | 2.06%   |
| Unknown (82B5)      | 1        | 1.03%   |
| Transcend           | 1        | 1.03%   |
| Team                | 1        | 1.03%   |
| PNY                 | 1        | 1.03%   |
| Neo Forza           | 1        | 1.03%   |
| Apacer              | 1        | 1.03%   |
| A-DATA Technology   | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 2        | 1.96%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s            | 2        | 1.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2        | 1.96%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s             | 2        | 1.96%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 1        | 0.98%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                         | 1        | 0.98%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.98%   |
| Unknown RAM Module 512MB DIMM SDRAM                             | 1        | 0.98%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 1        | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.98%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 0.98%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                      | 1        | 0.98%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 0.98%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 1        | 0.98%   |
| Unknown (82B5) RAM OP 117100 05/14 2M 4096MB DIMM DDR3 1333MT/s | 1        | 0.98%   |
| Transcend RAM JM1333KLN-2G 2048MB DIMM DDR3 1333MT/s            | 1        | 0.98%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 1        | 0.98%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s         | 1        | 0.98%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s           | 1        | 0.98%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.98%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 0.98%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 1        | 0.98%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                    | 1        | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1        | 0.98%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1        | 0.98%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s             | 1        | 0.98%   |
| Samsung RAM M393B1K70CHD-CH9 8GB DIMM DDR3 1333MT/s             | 1        | 0.98%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s             | 1        | 0.98%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s             | 1        | 0.98%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s             | 1        | 0.98%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s          | 1        | 0.98%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s       | 1        | 0.98%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s        | 1        | 0.98%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s             | 1        | 0.98%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                 | 1        | 0.98%   |
| Patriot RAM PSD22G8002 2GB DIMM DDR2 800MT/s                    | 1        | 0.98%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s              | 1        | 0.98%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s           | 1        | 0.98%   |
| Nanya RAM Module 4GB FB-DIMM DDR2 667MT/s                       | 1        | 0.98%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.98%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s                    | 1        | 0.98%   |
| Micron RAM 16JTF25664AZ-1G4F 2GB DIMM DDR3 1333MT/s             | 1        | 0.98%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s             | 1        | 0.98%   |
| Kingston RAM Module 4GB FB-DIMM DDR2 667MT/s                    | 1        | 0.98%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1        | 0.98%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 0.98%   |
| Kingston RAM KHX3466C16D4/8GX 8192MB DIMM DDR4 3466MT/s         | 1        | 0.98%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 0.98%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 1        | 0.98%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s             | 1        | 0.98%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s               | 1        | 0.98%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s             | 1        | 0.98%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 1        | 0.98%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s            | 1        | 0.98%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 1        | 0.98%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s           | 1        | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 35       | 46.05%  |
| DDR4    | 24       | 31.58%  |
| DDR2    | 7        | 9.21%   |
| Unknown | 5        | 6.58%   |
| SDRAM   | 4        | 5.26%   |
| DDR     | 1        | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 69       | 92%     |
| SODIMM  | 5        | 6.67%   |
| FB-DIMM | 1        | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 39.08%  |
| 4096  | 22       | 25.29%  |
| 2048  | 14       | 16.09%  |
| 16384 | 11       | 12.64%  |
| 1024  | 4        | 4.6%    |
| 32768 | 1        | 1.15%   |
| 512   | 1        | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 18       | 20.45%  |
| 1600    | 17       | 19.32%  |
| 3200    | 6        | 6.82%   |
| 2400    | 5        | 5.68%   |
| 667     | 5        | 5.68%   |
| 3600    | 4        | 4.55%   |
| 3466    | 3        | 3.41%   |
| 2133    | 3        | 3.41%   |
| 1867    | 3        | 3.41%   |
| 1800    | 3        | 3.41%   |
| 1066    | 3        | 3.41%   |
| 800     | 3        | 3.41%   |
| 3000    | 2        | 2.27%   |
| 2933    | 2        | 2.27%   |
| 4800    | 1        | 1.14%   |
| 3334    | 1        | 1.14%   |
| 3007    | 1        | 1.14%   |
| 2934    | 1        | 1.14%   |
| 2800    | 1        | 1.14%   |
| 2666    | 1        | 1.14%   |
| 2200    | 1        | 1.14%   |
| 1866    | 1        | 1.14%   |
| 1639    | 1        | 1.14%   |
| 133     | 1        | 1.14%   |
| Unknown | 1        | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 7        | 53.85%  |
| Brother Industries | 3        | 23.08%  |
| Canon              | 2        | 15.38%  |
| Dymo-CoStar        | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Printing Support         | 1        | 7.69%   |
| HP LaserJet Pro M201dw      | 1        | 7.69%   |
| HP LaserJet M101-M106       | 1        | 7.69%   |
| HP LaserJet 1320            | 1        | 7.69%   |
| HP Ink Tank 110 series      | 1        | 7.69%   |
| HP Deskjet 2050 J510        | 1        | 7.69%   |
| HP Deskjet 1000 J110 series | 1        | 7.69%   |
| Dymo-CoStar LabelWriter 450 | 1        | 7.69%   |
| Canon TR8500 series         | 1        | 7.69%   |
| Canon PIXMA MG3600 Series   | 1        | 7.69%   |
| Brother MFC-T910DW          | 1        | 7.69%   |
| Brother HL-4140CN series    | 1        | 7.69%   |
| Brother DCP-L2550DN series  | 1        | 7.69%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 33.85%  |
| Microsoft                     | 6        | 9.23%   |
| Microdia                      | 6        | 9.23%   |
| Chicony Electronics           | 5        | 7.69%   |
| Apple                         | 4        | 6.15%   |
| Sunplus Innovation Technology | 3        | 4.62%   |
| Z-Star Microelectronics       | 2        | 3.08%   |
| Generalplus Technology        | 2        | 3.08%   |
| Cubeternet                    | 2        | 3.08%   |
| Alcor Micro                   | 2        | 3.08%   |
| Teslong Camera                | 1        | 1.54%   |
| SunplusIT                     | 1        | 1.54%   |
| Samsung Electronics           | 1        | 1.54%   |
| Realtek Semiconductor         | 1        | 1.54%   |
| Razer USA                     | 1        | 1.54%   |
| LG Electronics                | 1        | 1.54%   |
| KYE Systems (Mouse Systems)   | 1        | 1.54%   |
| Hewlett-Packard               | 1        | 1.54%   |
| Guillemot                     | 1        | 1.54%   |
| Creative Technology           | 1        | 1.54%   |
| ANYKA                         | 1        | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 6        | 9.23%   |
| Logitech Webcam C270                                  | 3        | 4.62%   |
| Chicony HP High Definition 1MP Webcam                 | 3        | 4.62%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3        | 4.62%   |
| Sunplus FHD Camera Microphone                         | 2        | 3.08%   |
| Microsoft LifeCam HD-3000                             | 2        | 3.08%   |
| Microdia Integrated Camera                            | 2        | 3.08%   |
| Logitech Logi 4K Stream Edition                       | 2        | 3.08%   |
| Logitech HD Webcam C615                               | 2        | 3.08%   |
| Logitech B525 HD Webcam                               | 2        | 3.08%   |
| Generalplus GENERAL WEBCAM                            | 2        | 3.08%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 2        | 3.08%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 1.54%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 1.54%   |
| Teslong Camera                                        | 1        | 1.54%   |
| SunplusIT MTD camera                                  | 1        | 1.54%   |
| Sunplus Aukey-PC-LM1E Camera                          | 1        | 1.54%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 1.54%   |
| Realtek FULL HD 1080P Webcam                          | 1        | 1.54%   |
| Razer USA Razer Kiyo Pro                              | 1        | 1.54%   |
| Microsoft Xbox NUI Camera                             | 1        | 1.54%   |
| Microsoft LifeCam VX-800                              | 1        | 1.54%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.54%   |
| Microsoft LifeCam HD-5000                             | 1        | 1.54%   |
| Microdia Webcam Vitade AF                             | 1        | 1.54%   |
| Microdia USB 2.0 Camera                               | 1        | 1.54%   |
| Microdia Sonix USB 2.0 Camera                         | 1        | 1.54%   |
| Microdia Rapoo camera                                 | 1        | 1.54%   |
| Logitech Webcam C925e                                 | 1        | 1.54%   |
| Logitech Webcam C310                                  | 1        | 1.54%   |
| Logitech Webcam C250                                  | 1        | 1.54%   |
| Logitech QuickCam Communicate Deluxe                  | 1        | 1.54%   |
| Logitech HD Webcam C910                               | 1        | 1.54%   |
| Logitech C505 HD Webcam                               | 1        | 1.54%   |
| Logitech BCC950 ConferenceCam                         | 1        | 1.54%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.54%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 1        | 1.54%   |
| HP Webcam HD-2200                                     | 1        | 1.54%   |
| Guillemot Hercules Dualpix Exchange                   | 1        | 1.54%   |
| Creative Live! Cam Sync 1080p                         | 1        | 1.54%   |
| Chicony USB2.0 UVC VGA                                | 1        | 1.54%   |
| Chicony HP 1.0MP High Definition Webcam               | 1        | 1.54%   |
| Apple iPhone 4                                        | 1        | 1.54%   |
| ANYKA V380 FHD Camera                                 | 1        | 1.54%   |
| Alcor Micro USB 2.0 PC Camera                         | 1        | 1.54%   |
| Alcor Micro USB 2.0 Camera                            | 1        | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 271      | 87.14%  |
| 1     | 33       | 10.61%  |
| 2     | 4        | 1.29%   |
| 4     | 2        | 0.64%   |
| 3     | 1        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 22       | 47.83%  |
| Graphics card            | 8        | 17.39%  |
| Sound                    | 4        | 8.7%    |
| Unassigned class         | 2        | 4.35%   |
| Network                  | 2        | 4.35%   |
| Camera                   | 2        | 4.35%   |
| Storage/ide              | 1        | 2.17%   |
| Multimedia controller    | 1        | 2.17%   |
| Fingerprint reader       | 1        | 2.17%   |
| Communication controller | 1        | 2.17%   |
| Card reader              | 1        | 2.17%   |
| Bluetooth                | 1        | 2.17%   |

