Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 625

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8e507ac560](https://linux-hardware.org/?probe=8e507ac560) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef6b39f974](https://linux-hardware.org/?probe=ef6b39f974) | Mar 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1530a92d0](https://linux-hardware.org/?probe=c1530a92d0) | Mar 06, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cbb0be1510](https://linux-hardware.org/?probe=cbb0be1510) | Mar 02, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [30aa62dcf6](https://linux-hardware.org/?probe=30aa62dcf6) | Mar 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [20162eca98](https://linux-hardware.org/?probe=20162eca98) | Mar 01, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [52a3bf87da](https://linux-hardware.org/?probe=52a3bf87da) | Feb 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6850290145](https://linux-hardware.org/?probe=6850290145) | Feb 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [36aa0c0c4a](https://linux-hardware.org/?probe=36aa0c0c4a) | Feb 27, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2e43f94c93](https://linux-hardware.org/?probe=2e43f94c93) | Feb 25, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [5cbfcf93fe](https://linux-hardware.org/?probe=5cbfcf93fe) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [3b3c03d206](https://linux-hardware.org/?probe=3b3c03d206) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [be96e376bd](https://linux-hardware.org/?probe=be96e376bd) | Sep 02, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [0bcae30730](https://linux-hardware.org/?probe=0bcae30730) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [7b1f35e70f](https://linux-hardware.org/?probe=7b1f35e70f) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [aef2376a1b](https://linux-hardware.org/?probe=aef2376a1b) | Mar 25, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [50cc42af18](https://linux-hardware.org/?probe=50cc42af18) | Mar 24, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [fcb1a0a7f0](https://linux-hardware.org/?probe=fcb1a0a7f0) | Feb 22, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [75538dc806](https://linux-hardware.org/?probe=75538dc806) | Jan 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | XPS L502X                   | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | XPS L502X                   | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [2b8b2aec58](https://linux-hardware.org/?probe=2b8b2aec58) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| MSI           | MS-7270                     | Desktop     | [9b7caf1b44](https://linux-hardware.org/?probe=9b7caf1b44) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Board                       | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Dell          | Board                       | Desktop     | [a74c37f279](https://linux-hardware.org/?probe=a74c37f279) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [464a456cc4](https://linux-hardware.org/?probe=464a456cc4) | Oct 25, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Board                       | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | Board                       | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | Board                       | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [270b48d11a](https://linux-hardware.org/?probe=270b48d11a) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | Board                       | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | Board                       | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | Board                       | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | Board                       | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6ffc46e99c](https://linux-hardware.org/?probe=6ffc46e99c) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [bc407f7c3d](https://linux-hardware.org/?probe=bc407f7c3d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [c9342cdd0b](https://linux-hardware.org/?probe=c9342cdd0b) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [a5d8a60392](https://linux-hardware.org/?probe=a5d8a60392) | Apr 25, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| ABIT          | KN9                         | Desktop     | [dcc26c22fc](https://linux-hardware.org/?probe=dcc26c22fc) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | Notebook    | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | Notebook    | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| ABIT          | KN9                         | Desktop     | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Dell          | Latitude E5450              | Notebook    | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | Notebook    | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Dell          | XPS M1530                   | Notebook    | [dbd1208fb0](https://linux-hardware.org/?probe=dbd1208fb0) | Apr 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d882ce78cd](https://linux-hardware.org/?probe=d882ce78cd) | Apr 09, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | Notebook    | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [3ec999d67c](https://linux-hardware.org/?probe=3ec999d67c) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| Lenovo        | Board                       | Desktop     | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Lenovo        | Board                       | Desktop     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | Board                       | Desktop     | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | Desktop     | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | Desktop     | [620c1b46ca](https://linux-hardware.org/?probe=620c1b46ca) | Feb 24, 2020 |
| ABIT          | KN9                         | Desktop     | [1a97e76aaf](https://linux-hardware.org/?probe=1a97e76aaf) | Feb 23, 2020 |
| ABIT          | KN9                         | Desktop     | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| Dell          | Precision M6300             | Notebook    | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | Notebook    | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | Notebook    | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ec722fbbfe](https://linux-hardware.org/?probe=ec722fbbfe) | Feb 01, 2020 |
| HP            | 1998                        | Desktop     | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [82bfd8fc5c](https://linux-hardware.org/?probe=82bfd8fc5c) | Jan 18, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | Notebook    | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | Notebook    | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| System76      | Galago Pro                  | Notebook    | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | Notebook    | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | Notebook    | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | Notebook    | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | Notebook    | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | Notebook    | [7dc27cbde9](https://linux-hardware.org/?probe=7dc27cbde9) | Sep 18, 2019 |
| Seco          | C40 C                       | Desktop     | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | Notebook    | [6c0b10b183](https://linux-hardware.org/?probe=6c0b10b183) | Sep 12, 2019 |
| System76      | Galago Pro                  | Notebook    | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Seco          | C40 C                       | Desktop     | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Seco          | C40 C                       | Desktop     | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [b998963e7a](https://linux-hardware.org/?probe=b998963e7a) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [80df58f615](https://linux-hardware.org/?probe=80df58f615) | Aug 17, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| ASUSTek       | K5130                       | Desktop     | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| DFI           | INF P35                     | Desktop     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | Desktop     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Advent        | Roma                        | Notebook    | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | Notebook    | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [8f87769d12](https://linux-hardware.org/?probe=8f87769d12) | Jun 19, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| Dell          | 0FJ030                      | Desktop     | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| ASRock        | G31M-S                      | Desktop     | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | Desktop     | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | Notebook    | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | Notebook    | [44c9ce32b9](https://linux-hardware.org/?probe=44c9ce32b9) | May 18, 2019 |
| ASUSTek       | K53U                        | Notebook    | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | Notebook    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | Notebook    | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [4b838f8f56](https://linux-hardware.org/?probe=4b838f8f56) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | Desktop     | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2bf103dd36](https://linux-hardware.org/?probe=2bf103dd36) | Feb 23, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2907768caa](https://linux-hardware.org/?probe=2907768caa) | Feb 23, 2019 |
| Dell          | 0CRH6C A00                  | Desktop     | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [0df880aebd](https://linux-hardware.org/?probe=0df880aebd) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | Notebook    | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [6aa573349b](https://linux-hardware.org/?probe=6aa573349b) | Jan 18, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [f7ad5aeb4b](https://linux-hardware.org/?probe=f7ad5aeb4b) | Jan 18, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| Toshiba       | Satellite Pro C660          | Notebook    | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | Notebook    | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| Dell          | Latitude E6230              | Notebook    | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1d52b52b65](https://linux-hardware.org/?probe=1d52b52b65) | Feb 28, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Dell          | Latitude E6230              | Notebook    | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | Notebook    | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 78        | 18.35%  |
| Ubuntu 18.04        | 47        | 11.06%  |
| OpenMandriva 4.2    | 12        | 2.82%   |
| Debian 10           | 10        | 2.35%   |
| Ubuntu 19.04        | 9         | 2.12%   |
| Pop!_OS 21.10       | 9         | 2.12%   |
| Linux Mint 20.2     | 9         | 2.12%   |
| ArcoLinux Rolling   | 9         | 2.12%   |
| Pop!_OS 20.10       | 8         | 1.88%   |
| Manjaro             | 8         | 1.88%   |
| Linux Mint 20       | 8         | 1.88%   |
| Pop!_OS 20.04       | 7         | 1.65%   |
| KDE neon 20.04      | 7         | 1.65%   |
| Debian 11           | 7         | 1.65%   |
| BlackPanther 18.1   | 7         | 1.65%   |
| Ubuntu 19.10        | 6         | 1.41%   |
| Arch                | 6         | 1.41%   |
| Ubuntu 21.10        | 5         | 1.18%   |
| ROSA R11            | 5         | 1.18%   |
| ROSA R10            | 5         | 1.18%   |
| Linux Mint 20.1     | 5         | 1.18%   |
| Linux Mint 19.3     | 5         | 1.18%   |
| Fedora 35           | 5         | 1.18%   |
| Fedora 33           | 5         | 1.18%   |
| Fedora 32           | 5         | 1.18%   |
| Arch Rolling        | 5         | 1.18%   |
| Zorin 15            | 4         | 0.94%   |
| Ubuntu 20.10        | 4         | 0.94%   |
| Ubuntu 16.04        | 4         | 0.94%   |
| Kubuntu 20.04       | 4         | 0.94%   |
| Fedora 34           | 4         | 0.94%   |
| Debian Unstable     | 4         | 0.94%   |
| Zorin 16            | 3         | 0.71%   |
| Pop!_OS 21.04       | 3         | 0.71%   |
| OpenMandriva 4.50   | 3         | 0.71%   |
| Lubuntu 20.04       | 3         | 0.71%   |
| Linux Mint 19.2     | 3         | 0.71%   |
| Linux Mint 19.1     | 3         | 0.71%   |
| Linux Mint 19       | 3         | 0.71%   |
| Linux Mint 18.3     | 3         | 0.71%   |
| Endless 3.7.8       | 3         | 0.71%   |
| Xubuntu 20.04       | 2         | 0.47%   |
| Ubuntu MATE 20.04   | 2         | 0.47%   |
| ROSA R9             | 2         | 0.47%   |
| ROSA R11.1          | 2         | 0.47%   |
| OpenMandriva 4.3    | 2         | 0.47%   |
| Manjaro 21.0.7      | 2         | 0.47%   |
| Manjaro 21.0.5      | 2         | 0.47%   |
| Manjaro 20.2        | 2         | 0.47%   |
| Kubuntu 21.10       | 2         | 0.47%   |
| Kubuntu 21.04       | 2         | 0.47%   |
| Kubuntu 20.10       | 2         | 0.47%   |
| KDE neon 18.04      | 2         | 0.47%   |
| Gentoo 2.7          | 2         | 0.47%   |
| Elementary 5.1.7    | 2         | 0.47%   |
| Debian 9            | 2         | 0.47%   |
| Xubuntu 20.10       | 1         | 0.24%   |
| Ubuntu Core 16      | 1         | 0.24%   |
| Ubuntu Budgie 22.04 | 1         | 0.24%   |
| Ubuntu Budgie 21.04 | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 153       | 37.59%  |
| Linux Mint    | 35        | 8.6%    |
| Pop!_OS       | 28        | 6.88%   |
| Debian        | 23        | 5.65%   |
| Manjaro       | 20        | 4.91%   |
| Fedora        | 20        | 4.91%   |
| OpenMandriva  | 17        | 4.18%   |
| ROSA          | 12        | 2.95%   |
| Kubuntu       | 11        | 2.7%    |
| Arch          | 11        | 2.7%    |
| ArcoLinux     | 9         | 2.21%   |
| KDE neon      | 8         | 1.97%   |
| Zorin         | 7         | 1.72%   |
| BlackPanther  | 7         | 1.72%   |
| Elementary    | 6         | 1.47%   |
| Lubuntu       | 5         | 1.23%   |
| Endless       | 5         | 1.23%   |
| openSUSE      | 4         | 0.98%   |
| Xubuntu       | 3         | 0.74%   |
| Ubuntu Budgie | 3         | 0.74%   |
| Gentoo        | 3         | 0.74%   |
| Clear Linux   | 3         | 0.74%   |
| Ubuntu MATE   | 2         | 0.49%   |
| Peppermint    | 2         | 0.49%   |
| Kali          | 2         | 0.49%   |
| CentOS        | 2         | 0.49%   |
| Trisquel      | 1         | 0.25%   |
| Solus         | 1         | 0.25%   |
| RHEL          | 1         | 0.25%   |
| MX            | 1         | 0.25%   |
| LMDE          | 1         | 0.25%   |
| Chrome OS     | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 15        | 3.21%   |
| 5.10.14-desktop-1omv4002        | 12        | 2.57%   |
| 5.3.0-46-generic                | 10        | 2.14%   |
| 4.18.16-desktop-1bP             | 6         | 1.28%   |
| 5.4.0-91-generic                | 5         | 1.07%   |
| 5.4.0-52-generic                | 5         | 1.07%   |
| 5.4.0-48-generic                | 5         | 1.07%   |
| 5.11.0-27-generic               | 5         | 1.07%   |
| 5.8.0-7630-generic              | 4         | 0.86%   |
| 5.8.0-43-generic                | 4         | 0.86%   |
| 5.4.0-72-generic                | 4         | 0.86%   |
| 5.4.0-47-generic                | 4         | 0.86%   |
| 5.4.0-31-generic                | 4         | 0.86%   |
| 5.4.0-29-generic                | 4         | 0.86%   |
| 5.4.0-26-generic                | 4         | 0.86%   |
| 5.3.0-28-generic                | 4         | 0.86%   |
| 4.18.0-15-generic               | 4         | 0.86%   |
| 5.8.0-53-generic                | 3         | 0.64%   |
| 5.8.0-41-generic                | 3         | 0.64%   |
| 5.4.0-80-generic                | 3         | 0.64%   |
| 5.4.0-77-generic                | 3         | 0.64%   |
| 5.4.0-7634-generic              | 3         | 0.64%   |
| 5.4.0-58-generic                | 3         | 0.64%   |
| 5.4.0-54-generic                | 3         | 0.64%   |
| 5.4.0-51-generic                | 3         | 0.64%   |
| 5.4.0-39-generic                | 3         | 0.64%   |
| 5.4.0-37-generic                | 3         | 0.64%   |
| 5.3.0-45-generic                | 3         | 0.64%   |
| 5.3.0-40-generic                | 3         | 0.64%   |
| 5.16.15-76051615-generic        | 3         | 0.64%   |
| 5.15.11-76051511-generic        | 3         | 0.64%   |
| 5.12.4-desktop-1omv4050         | 3         | 0.64%   |
| 5.11.0-38-generic               | 3         | 0.64%   |
| 5.10.0-8-amd64                  | 3         | 0.64%   |
| 5.0.0-25-generic                | 3         | 0.64%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.64%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 3         | 0.64%   |
| 4.19.0-9-amd64                  | 3         | 0.64%   |
| 4.15.0-50-generic               | 3         | 0.64%   |
| 4.10.0-38-generic               | 3         | 0.64%   |
| 5.8.14-arch1-1                  | 2         | 0.43%   |
| 5.8.0-7625-generic              | 2         | 0.43%   |
| 5.8.0-33-generic                | 2         | 0.43%   |
| 5.8.0-26-generic                | 2         | 0.43%   |
| 5.7.12-arch1-1                  | 2         | 0.43%   |
| 5.4.0-88-generic                | 2         | 0.43%   |
| 5.4.0-7625-generic              | 2         | 0.43%   |
| 5.4.0-73-generic                | 2         | 0.43%   |
| 5.4.0-70-generic                | 2         | 0.43%   |
| 5.4.0-65-generic                | 2         | 0.43%   |
| 5.4.0-62-generic                | 2         | 0.43%   |
| 5.4.0-56-generic                | 2         | 0.43%   |
| 5.4.0-53-generic                | 2         | 0.43%   |
| 5.4.0-40-generic                | 2         | 0.43%   |
| 5.4.0-13-generic                | 2         | 0.43%   |
| 5.3.0-53-generic                | 2         | 0.43%   |
| 5.3.0-18-generic                | 2         | 0.43%   |
| 5.16.7-desktop-1omv4003         | 2         | 0.43%   |
| 5.16.11-76051611-generic        | 2         | 0.43%   |
| 5.15.7-arch1-1                  | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 104       | 23.91%  |
| 4.15.0  | 36        | 8.28%   |
| 5.8.0   | 28        | 6.44%   |
| 5.3.0   | 26        | 5.98%   |
| 5.11.0  | 24        | 5.52%   |
| 5.0.0   | 15        | 3.45%   |
| 5.13.0  | 12        | 2.76%   |
| 5.10.14 | 12        | 2.76%   |
| 4.19.0  | 11        | 2.53%   |
| 4.18.0  | 11        | 2.53%   |
| 5.10.0  | 9         | 2.07%   |
| 4.18.16 | 6         | 1.38%   |
| 5.16.11 | 4         | 0.92%   |
| 4.9.60  | 4         | 0.92%   |
| 5.8.14  | 3         | 0.69%   |
| 5.6.0   | 3         | 0.69%   |
| 5.16.15 | 3         | 0.69%   |
| 5.15.12 | 3         | 0.69%   |
| 5.15.11 | 3         | 0.69%   |
| 5.12.4  | 3         | 0.69%   |
| 4.9.155 | 3         | 0.69%   |
| 4.10.0  | 3         | 0.69%   |
| 5.7.9   | 2         | 0.46%   |
| 5.7.12  | 2         | 0.46%   |
| 5.6.7   | 2         | 0.46%   |
| 5.6.15  | 2         | 0.46%   |
| 5.16.7  | 2         | 0.46%   |
| 5.15.7  | 2         | 0.46%   |
| 5.15.6  | 2         | 0.46%   |
| 5.15.5  | 2         | 0.46%   |
| 5.15.0  | 2         | 0.46%   |
| 5.13.19 | 2         | 0.46%   |
| 5.13.13 | 2         | 0.46%   |
| 5.12.8  | 2         | 0.46%   |
| 5.12.2  | 2         | 0.46%   |
| 5.11.11 | 2         | 0.46%   |
| 5.11.10 | 2         | 0.46%   |
| 5.10.42 | 2         | 0.46%   |
| 5.10.2  | 2         | 0.46%   |
| 4.9.41  | 2         | 0.46%   |
| 4.13.0  | 2         | 0.46%   |
| 4.12.14 | 2         | 0.46%   |
| 3.10.0  | 2         | 0.46%   |
| 5.9.3   | 1         | 0.23%   |
| 5.9.16  | 1         | 0.23%   |
| 5.9.11  | 1         | 0.23%   |
| 5.9.1   | 1         | 0.23%   |
| 5.9.0   | 1         | 0.23%   |
| 5.9     | 1         | 0.23%   |
| 5.8.7   | 1         | 0.23%   |
| 5.8.18  | 1         | 0.23%   |
| 5.8.11  | 1         | 0.23%   |
| 5.8.10  | 1         | 0.23%   |
| 5.7.8   | 1         | 0.23%   |
| 5.7.7   | 1         | 0.23%   |
| 5.7.11  | 1         | 0.23%   |
| 5.6.3   | 1         | 0.23%   |
| 5.6.14  | 1         | 0.23%   |
| 5.6.10  | 1         | 0.23%   |
| 5.5.6   | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 109       | 25.59%  |
| 4.15    | 36        | 8.45%   |
| 5.8     | 35        | 8.22%   |
| 5.10    | 34        | 7.98%   |
| 5.11    | 30        | 7.04%   |
| 5.3     | 27        | 6.34%   |
| 5.13    | 18        | 4.23%   |
| 4.18    | 17        | 3.99%   |
| 5.15    | 16        | 3.76%   |
| 5.0     | 15        | 3.52%   |
| 4.19    | 12        | 2.82%   |
| 5.16    | 11        | 2.58%   |
| 4.9     | 11        | 2.58%   |
| 5.6     | 10        | 2.35%   |
| 5.12    | 8         | 1.88%   |
| 5.7     | 7         | 1.64%   |
| 5.9     | 5         | 1.17%   |
| 5.14    | 5         | 1.17%   |
| 5.17    | 4         | 0.94%   |
| 4.10    | 3         | 0.7%    |
| 4.4     | 2         | 0.47%   |
| 4.13    | 2         | 0.47%   |
| 4.12    | 2         | 0.47%   |
| 3.10    | 2         | 0.47%   |
| 5.5     | 1         | 0.23%   |
| 5.2     | 1         | 0.23%   |
| 5       | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| 4.1     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 373       | 94.43%  |
| i686    | 15        | 3.8%    |
| aarch64 | 7         | 1.77%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 179       | 42.93%  |
| Unknown         | 66        | 15.83%  |
| KDE5            | 57        | 13.67%  |
| XFCE            | 27        | 6.47%   |
| X-Cinnamon      | 20        | 4.8%    |
| KDE             | 18        | 4.32%   |
| MATE            | 8         | 1.92%   |
| Cinnamon        | 7         | 1.68%   |
| KDE4            | 6         | 1.44%   |
| Unity           | 5         | 1.2%    |
| Pantheon        | 5         | 1.2%    |
| LXQt            | 5         | 1.2%    |
| i3              | 4         | 0.96%   |
| Budgie          | 3         | 0.72%   |
| GNOME Flashback | 2         | 0.48%   |
| GNOME Classic   | 2         | 0.48%   |
| LXDE            | 1         | 0.24%   |
| LeftWM          | 1         | 0.24%   |
| Enlightenment   | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 330       | 82.91%  |
| Unknown | 38        | 9.55%   |
| Wayland | 23        | 5.78%   |
| Tty     | 7         | 1.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 237       | 58.66%  |
| SDDM    | 57        | 14.11%  |
| GDM     | 49        | 12.13%  |
| LightDM | 26        | 6.44%   |
| TDM     | 19        | 4.7%    |
| GDM3    | 9         | 2.23%   |
| KDM     | 6         | 1.49%   |
| LXDM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 193       | 47.42%  |
| Unknown | 66        | 16.22%  |
| en_US   | 64        | 15.72%  |
| en_GB   | 63        | 15.48%  |
| pl_PL   | 10        | 2.46%   |
| es_ES   | 2         | 0.49%   |
| C       | 2         | 0.49%   |
| ru_RU   | 1         | 0.25%   |
| it_IT   | 1         | 0.25%   |
| ga_IE   | 1         | 0.25%   |
| fr_FR   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| en_CA   | 1         | 0.25%   |
| bg_BG   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 215       | 54.02%  |
| EFI  | 183       | 45.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 315       | 79.35%  |
| Overlay             | 29        | 7.3%    |
| Unknown             | 23        | 5.79%   |
| Btrfs               | 19        | 4.79%   |
| Xfs                 | 5         | 1.26%   |
| Zfs                 | 4         | 1.01%   |
| Fuse.fuse-overlayfs | 1         | 0.25%   |
| F2fs                | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 239       | 60.05%  |
| GPT     | 117       | 29.4%   |
| MBR     | 42        | 10.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 339       | 85.18%  |
| Yes       | 59        | 14.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 293       | 73.25%  |
| Yes       | 107       | 26.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 76        | 19.34%  |
| Lenovo                  | 69        | 17.56%  |
| ASUSTek Computer        | 50        | 12.72%  |
| Hewlett-Packard         | 45        | 11.45%  |
| Gigabyte Technology     | 19        | 4.83%   |
| Acer                    | 19        | 4.83%   |
| MSI                     | 14        | 3.56%   |
| Apple                   | 14        | 3.56%   |
| Toshiba                 | 10        | 2.54%   |
| ASRock                  | 10        | 2.54%   |
| Intel                   | 6         | 1.53%   |
| Samsung Electronics     | 4         | 1.02%   |
| PC Specialist           | 4         | 1.02%   |
| Medion                  | 4         | 1.02%   |
| TUXEDO                  | 3         | 0.76%   |
| Notebook                | 3         | 0.76%   |
| Foxconn                 | 3         | 0.76%   |
| Timi                    | 2         | 0.51%   |
| System76                | 2         | 0.51%   |
| Shuttle                 | 2         | 0.51%   |
| Seco                    | 2         | 0.51%   |
| Raspberry Pi Foundation | 2         | 0.51%   |
| Packard Bell            | 2         | 0.51%   |
| Nvidia                  | 2         | 0.51%   |
| HUAWEI                  | 2         | 0.51%   |
| Entroware               | 2         | 0.51%   |
| eMachines               | 2         | 0.51%   |
| Chuwi                   | 2         | 0.51%   |
| Sony UK                 | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| SLIMBOOK                | 1         | 0.25%   |
| Schenker                | 1         | 0.25%   |
| Rockchip                | 1         | 0.25%   |
| Pine Microsystems       | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |
| MiTAC                   | 1         | 0.25%   |
| Microtech               | 1         | 0.25%   |
| IP3 Tech                | 1         | 0.25%   |
| Fujitsu Siemens         | 1         | 0.25%   |
| DFI                     | 1         | 0.25%   |
| AVITA                   | 1         | 0.25%   |
| AMI                     | 1         | 0.25%   |
| Alienware               | 1         | 0.25%   |
| Advent                  | 1         | 0.25%   |
| ABIT                    | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 5         | 1.27%   |
| Gigabyte B450M DS3H                      | 4         | 1.02%   |
| Lenovo V145-15AST 81MT                   | 3         | 0.76%   |
| HP Compaq 8200 Elite SFF PC              | 3         | 0.76%   |
| Dell OptiPlex 790                        | 3         | 0.76%   |
| Dell OptiPlex 7010                       | 3         | 0.76%   |
| ASUS ROG STRIX B450-F GAMING             | 3         | 0.76%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.51%   |
| Seco C40                                 | 2         | 0.51%   |
| RPi Raspberry Pi                         | 2         | 0.51%   |
| Nvidia Tegra                             | 2         | 0.51%   |
| MSI MS-7B79                              | 2         | 0.51%   |
| Lenovo ThinkStation D20 415892G          | 2         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 3443CTO        | 2         | 0.51%   |
| Lenovo IdeaPad 510-15ISK 80SR            | 2         | 0.51%   |
| HP Notebook                              | 2         | 0.51%   |
| HP EliteDesk 800 G1 SFF                  | 2         | 0.51%   |
| Gigabyte X570 AORUS ULTRA                | 2         | 0.51%   |
| Dell XPS 13 9310                         | 2         | 0.51%   |
| Dell XPS 13 9300                         | 2         | 0.51%   |
| Dell XPS 13 7390                         | 2         | 0.51%   |
| Dell Precision 5550                      | 2         | 0.51%   |
| Dell OptiPlex 780                        | 2         | 0.51%   |
| Dell Latitude E6230                      | 2         | 0.51%   |
| Dell Inspiron 13-5378                    | 2         | 0.51%   |
| ASUS TUF GAMING X570-PLUS                | 2         | 0.51%   |
| ASUS P8P67 PRO                           | 2         | 0.51%   |
| ASUS M5A78L/USB3                         | 2         | 0.51%   |
| Apple MacBook6,1                         | 2         | 0.51%   |
| Acer Aspire E5-575G                      | 2         | 0.51%   |
| Unknown                                  | 2         | 0.51%   |
| TUXEDO InfinityBook Pro 15 v5            | 1         | 0.25%   |
| Toshiba TECRA R850                       | 1         | 0.25%   |
| Toshiba TECRA M4                         | 1         | 0.25%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.25%   |
| Toshiba Satellite Pro C660               | 1         | 0.25%   |
| Toshiba Satellite L500                   | 1         | 0.25%   |
| Toshiba Satellite L50-C                  | 1         | 0.25%   |
| Toshiba Satellite L50-B                  | 1         | 0.25%   |
| Toshiba Satellite C50-B                  | 1         | 0.25%   |
| Toshiba Satellite A300                   | 1         | 0.25%   |
| Toshiba PORTEGE R830                     | 1         | 0.25%   |
| Timi TM1703                              | 1         | 0.25%   |
| Timi TM1607                              | 1         | 0.25%   |
| System76 Galago Pro                      | 1         | 0.25%   |
| System76 Bonobo Extreme                  | 1         | 0.25%   |
| Sony VPCCB35FG                           | 1         | 0.25%   |
| Sony UK Raspberry Pi 3 Model B           | 1         | 0.25%   |
| SLIMBOOK PROX15                          | 1         | 0.25%   |
| Shuttle XS35V4                           | 1         | 0.25%   |
| Shuttle XS35V3                           | 1         | 0.25%   |
| Schenker XMG NEO (TGL/M21)               | 1         | 0.25%   |
| Samsung N150/N210/N220                   | 1         | 0.25%   |
| Samsung Galaxy TabPro S                  | 1         | 0.25%   |
| Samsung 550P5C/550P7C                    | 1         | 0.25%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.25%   |
| Pine Microsystems Pine64 PinePhone (1.2) | 1         | 0.25%   |
| Pegatron Pro 3010 Microtower PC          | 1         | 0.25%   |
| PC Specialist TF                         | 1         | 0.25%   |
| PC Specialist PCX0DX                     | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 30        | 7.63%   |
| Dell Latitude       | 22        | 5.6%    |
| Dell Inspiron       | 14        | 3.56%   |
| Acer Aspire         | 14        | 3.56%   |
| Dell OptiPlex       | 13        | 3.31%   |
| Lenovo IdeaPad      | 12        | 3.05%   |
| Dell XPS            | 11        | 2.8%    |
| HP Pavilion         | 8         | 2.04%   |
| HP EliteBook        | 8         | 2.04%   |
| Dell Precision      | 8         | 2.04%   |
| Toshiba Satellite   | 7         | 1.78%   |
| Lenovo ThinkCentre  | 7         | 1.78%   |
| HP Compaq           | 7         | 1.78%   |
| ASUS TUF            | 6         | 1.53%   |
| ASUS ROG            | 5         | 1.27%   |
| ASUS PRIME          | 5         | 1.27%   |
| ASUS All            | 5         | 1.27%   |
| Gigabyte B450M      | 4         | 1.02%   |
| Dell Vostro         | 4         | 1.02%   |
| Lenovo Yoga         | 3         | 0.76%   |
| Lenovo V145-15AST   | 3         | 0.76%   |
| HP Presario         | 3         | 0.76%   |
| HP Laptop           | 3         | 0.76%   |
| HP EliteDesk        | 3         | 0.76%   |
| Apple MacBookPro5   | 3         | 0.76%   |
| TUXEDO Pulse        | 2         | 0.51%   |
| Toshiba TECRA       | 2         | 0.51%   |
| Seco C40            | 2         | 0.51%   |
| RPi Raspberry       | 2         | 0.51%   |
| Nvidia Tegra        | 2         | 0.51%   |
| MSI MS-7B79         | 2         | 0.51%   |
| Lenovo ThinkStation | 2         | 0.51%   |
| HP Notebook         | 2         | 0.51%   |
| Gigabyte X570       | 2         | 0.51%   |
| Gigabyte B450       | 2         | 0.51%   |
| Foxconn Pro         | 2         | 0.51%   |
| Dell Studio         | 2         | 0.51%   |
| ASUS ZenBook        | 2         | 0.51%   |
| ASUS P8P67          | 2         | 0.51%   |
| ASUS Maximus        | 2         | 0.51%   |
| ASUS M5A78L         | 2         | 0.51%   |
| ASUS CROSSHAIR      | 2         | 0.51%   |
| ASRock Z77          | 2         | 0.51%   |
| Apple MacBook6      | 2         | 0.51%   |
| Unknown             | 2         | 0.51%   |
| TUXEDO InfinityBook | 1         | 0.25%   |
| Toshiba PORTEGE     | 1         | 0.25%   |
| Timi TM1703         | 1         | 0.25%   |
| Timi TM1607         | 1         | 0.25%   |
| System76 Galago     | 1         | 0.25%   |
| System76 Bonobo     | 1         | 0.25%   |
| Sony VPCCB35FG      | 1         | 0.25%   |
| Sony UK Raspberry   | 1         | 0.25%   |
| SLIMBOOK PROX15     | 1         | 0.25%   |
| Shuttle XS35V4      | 1         | 0.25%   |
| Shuttle XS35V3      | 1         | 0.25%   |
| Schenker XMG        | 1         | 0.25%   |
| Samsung N150        | 1         | 0.25%   |
| Samsung Galaxy      | 1         | 0.25%   |
| Samsung 550P5C      | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 43        | 10.94%  |
| 2018    | 39        | 9.92%   |
| 2012    | 35        | 8.91%   |
| 2011    | 34        | 8.65%   |
| 2013    | 33        | 8.4%    |
| 2020    | 30        | 7.63%   |
| 2017    | 27        | 6.87%   |
| 2010    | 24        | 6.11%   |
| 2008    | 22        | 5.6%    |
| 2016    | 18        | 4.58%   |
| 2014    | 18        | 4.58%   |
| 2015    | 17        | 4.33%   |
| 2009    | 17        | 4.33%   |
| 2021    | 13        | 3.31%   |
| 2007    | 9         | 2.29%   |
| Unknown | 6         | 1.53%   |
| 2006    | 5         | 1.27%   |
| 2005    | 2         | 0.51%   |
| 2003    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 229       | 58.27%  |
| Desktop        | 135       | 34.35%  |
| Convertible    | 7         | 1.78%   |
| System on chip | 6         | 1.53%   |
| Mini pc        | 6         | 1.53%   |
| All in one     | 6         | 1.53%   |
| Tablet         | 3         | 0.76%   |
| Phone          | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 360       | 90.91%  |
| Enabled  | 36        | 9.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 393       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 23.44%  |
| 3.01-4.0    | 80        | 19.95%  |
| 16.01-24.0  | 75        | 18.7%   |
| 8.01-16.0   | 72        | 17.96%  |
| 32.01-64.0  | 41        | 10.22%  |
| 1.01-2.0    | 15        | 3.74%   |
| 64.01-256.0 | 9         | 2.24%   |
| 24.01-32.0  | 6         | 1.5%    |
| 2.01-3.0    | 5         | 1.25%   |
| 0.51-1.0    | 3         | 0.75%   |
| 0.01-0.5    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 160       | 37.12%  |
| 2.01-3.0   | 107       | 24.83%  |
| 3.01-4.0   | 60        | 13.92%  |
| 4.01-8.0   | 45        | 10.44%  |
| 0.51-1.0   | 36        | 8.35%   |
| 8.01-16.0  | 14        | 3.25%   |
| 0.01-0.5   | 5         | 1.16%   |
| 16.01-24.0 | 3         | 0.7%    |
| 32.01-64.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 58.21%  |
| 2      | 97        | 23.43%  |
| 3      | 34        | 8.21%   |
| 4      | 17        | 4.11%   |
| 5      | 11        | 2.66%   |
| 7      | 4         | 0.97%   |
| 6      | 4         | 0.97%   |
| 0      | 3         | 0.72%   |
| 10     | 2         | 0.48%   |
| 9      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 229       | 57.25%  |
| Yes       | 171       | 42.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 341       | 86.77%  |
| No        | 52        | 13.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 327       | 82.78%  |
| No        | 68        | 17.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 62%     |
| No        | 152       | 38%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 393       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Dublin        | 241       | 58.64%  |
| Cork          | 20        | 4.87%   |
| Naas          | 12        | 2.92%   |
| Limerick      | 10        | 2.43%   |
| Galway        | 8         | 1.95%   |
| Navan         | 6         | 1.46%   |
| Sligo         | 4         | 0.97%   |
| Portlaoise    | 4         | 0.97%   |
| Kilkenny      | 4         | 0.97%   |
| Kenmare       | 4         | 0.97%   |
| Gorey         | 4         | 0.97%   |
| Ennis         | 4         | 0.97%   |
| Athlone       | 4         | 0.97%   |
| Tuam          | 3         | 0.73%   |
| Swords        | 3         | 0.73%   |
| Nenagh        | 3         | 0.73%   |
| Midleton      | 3         | 0.73%   |
| Mallow        | 3         | 0.73%   |
| Enniscorthy   | 3         | 0.73%   |
| Enfield       | 3         | 0.73%   |
| Drogheda      | 3         | 0.73%   |
| Cavan         | 3         | 0.73%   |
| Westport      | 2         | 0.49%   |
| Macroom       | 2         | 0.49%   |
| Longford      | 2         | 0.49%   |
| Letterkenny   | 2         | 0.49%   |
| Clonsilla     | 2         | 0.49%   |
| Clonmel       | 2         | 0.49%   |
| Celbridge     | 2         | 0.49%   |
| Carrigaline   | 2         | 0.49%   |
| Bray          | 2         | 0.49%   |
| Ballina       | 2         | 0.49%   |
| Athy          | 2         | 0.49%   |
| Wicklow       | 1         | 0.24%   |
| Wexford       | 1         | 0.24%   |
| Waterford     | 1         | 0.24%   |
| Tipperary     | 1         | 0.24%   |
| Tallaght      | 1         | 0.24%   |
| Shannon       | 1         | 0.24%   |
| Roscommon     | 1         | 0.24%   |
| Rathcoole     | 1         | 0.24%   |
| New Ross      | 1         | 0.24%   |
| Mullingar     | 1         | 0.24%   |
| Maynooth      | 1         | 0.24%   |
| Malahide      | 1         | 0.24%   |
| Leixlip       | 1         | 0.24%   |
| Killorglin    | 1         | 0.24%   |
| Killaloe      | 1         | 0.24%   |
| Kilcoole      | 1         | 0.24%   |
| Kilcock       | 1         | 0.24%   |
| Kells         | 1         | 0.24%   |
| Harristown    | 1         | 0.24%   |
| Fermoy        | 1         | 0.24%   |
| Edenderry     | 1         | 0.24%   |
| Dungarvan     | 1         | 0.24%   |
| Dundalk       | 1         | 0.24%   |
| Droichead Nua | 1         | 0.24%   |
| Donegal       | 1         | 0.24%   |
| Cobh          | 1         | 0.24%   |
| Clonakilty    | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 111       | 185    | 18.75%  |
| Samsung Electronics       | 102       | 154    | 17.23%  |
| Seagate                   | 77        | 132    | 13.01%  |
| Toshiba                   | 39        | 49     | 6.59%   |
| Crucial                   | 31        | 40     | 5.24%   |
| Unknown                   | 30        | 38     | 5.07%   |
| Hitachi                   | 30        | 40     | 5.07%   |
| SanDisk                   | 27        | 33     | 4.56%   |
| Kingston                  | 17        | 22     | 2.87%   |
| Intel                     | 12        | 15     | 2.03%   |
| HGST                      | 10        | 10     | 1.69%   |
| Micron Technology         | 9         | 10     | 1.52%   |
| Fujitsu                   | 7         | 10     | 1.18%   |
| A-DATA Technology         | 7         | 12     | 1.18%   |
| SK Hynix                  | 6         | 6      | 1.01%   |
| Phison                    | 5         | 10     | 0.84%   |
| Verbatim                  | 4         | 4      | 0.68%   |
| LITEON                    | 4         | 4      | 0.68%   |
| China                     | 4         | 7      | 0.68%   |
| Apple                     | 4         | 5      | 0.68%   |
| Silicon Motion            | 3         | 5      | 0.51%   |
| PNY                       | 3         | 3      | 0.51%   |
| Micron/Crucial Technology | 3         | 4      | 0.51%   |
| KingSpec                  | 3         | 3      | 0.51%   |
| ASMT                      | 3         | 5      | 0.51%   |
| Union Memory              | 2         | 2      | 0.34%   |
| Transcend                 | 2         | 2      | 0.34%   |
| Team                      | 2         | 2      | 0.34%   |
| OCZ                       | 2         | 2      | 0.34%   |
| Netac                     | 2         | 2      | 0.34%   |
| MAXTOR                    | 2         | 2      | 0.34%   |
| KIOXIA                    | 2         | 3      | 0.34%   |
| KingDian                  | 2         | 5      | 0.34%   |
| Integral                  | 2         | 2      | 0.34%   |
| Zheino                    | 1         | 1      | 0.17%   |
| WDS100T1                  | 1         | 1      | 0.17%   |
| W800S                     | 1         | 2      | 0.17%   |
| USB3.0                    | 1         | 1      | 0.17%   |
| TCSUNBOW                  | 1         | 1      | 0.17%   |
| Sabrent                   | 1         | 2      | 0.17%   |
| QNAP                      | 1         | 1      | 0.17%   |
| PLEXTOR                   | 1         | 1      | 0.17%   |
| PALIT                     | 1         | 1      | 0.17%   |
| MaxDigital                | 1         | 1      | 0.17%   |
| LITEONIT                  | 1         | 1      | 0.17%   |
| LaCie                     | 1         | 1      | 0.17%   |
| KESU                      | 1         | 1      | 0.17%   |
| JMicron                   | 1         | 1      | 0.17%   |
| Hikvision                 | 1         | 1      | 0.17%   |
| FORESEE                   | 1         | 1      | 0.17%   |
| ExcelStor                 | 1         | 2      | 0.17%   |
| Emtec                     | 1         | 2      | 0.17%   |
| DRVEO                     | 1         | 1      | 0.17%   |
| DOGFISH                   | 1         | 1      | 0.17%   |
| Corsair                   | 1         | 2      | 0.17%   |
| AMD                       | 1         | 1      | 0.17%   |
| ADplus                    | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 0.91%   |
| Samsung SSD 840 EVO 250GB          | 6         | 0.91%   |
| Samsung NVMe SSD Drive 500GB       | 6         | 0.91%   |
| Unknown MMC Card  32GB             | 5         | 0.76%   |
| Toshiba MQ01ABD100 1TB             | 5         | 0.76%   |
| Seagate ST8000DM004-2CX188 8TB     | 5         | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.76%   |
| Samsung SSD 970 EVO Plus 500GB     | 5         | 0.76%   |
| Samsung SSD 850 EVO 250GB          | 5         | 0.76%   |
| Crucial CT1000MX500SSD1 1TB        | 5         | 0.76%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 4         | 0.6%    |
| Verbatim Vi550 S3 SSD 128GB        | 4         | 0.6%    |
| Seagate ST2000DL003-9VT166 2TB     | 4         | 0.6%    |
| Seagate Expansion Desk 3TB         | 4         | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 4         | 0.6%    |
| Samsung NVMe SSD Drive 256GB       | 4         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.6%    |
| Crucial CT500MX500SSD1 500GB       | 4         | 0.6%    |
| WDC WD5000AAKX-60U6AA0 500GB       | 3         | 0.45%   |
| WDC WD3200AAJS-60Z0A0 320GB        | 3         | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB           | 3         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.45%   |
| WDC WD10EURX-83UY4Y0 1TB           | 3         | 0.45%   |
| WDC WD10EALX-009BA0 1TB            | 3         | 0.45%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.45%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.45%   |
| Seagate ST3500418AS 500GB          | 3         | 0.45%   |
| Seagate ST3500312CS 500GB          | 3         | 0.45%   |
| Seagate ST31000528AS 1TB           | 3         | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.45%   |
| Sandisk NVMe SSD Drive 512GB       | 3         | 0.45%   |
| Samsung SSD 970 EVO 500GB          | 3         | 0.45%   |
| Samsung SSD 860 QVO 1TB            | 3         | 0.45%   |
| Samsung SSD 850 EVO 500GB          | 3         | 0.45%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 0.45%   |
| PNY CS900 120GB SSD                | 3         | 0.45%   |
| Micron 2300 NVMe 512GB             | 3         | 0.45%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 0.45%   |
| Hitachi HTS723232A7A364 320GB      | 3         | 0.45%   |
| Hitachi HDS721032CLA362 320GB      | 3         | 0.45%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.45%   |
| HGST HTS545050A7E680 500GB         | 3         | 0.45%   |
| Crucial M4-CT128M4SSD2 128GB       | 3         | 0.45%   |
| Crucial CT480BX500SSD1 480GB       | 3         | 0.45%   |
| WDC WDS250G2B0C-00PXH0 250GB       | 2         | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.3%    |
| WDC WDS100T1B0A-00H9H0 1TB SSD     | 2         | 0.3%    |
| WDC WD5000AAKX-22ERMA0 500GB       | 2         | 0.3%    |
| WDC WD40EZRZ-19GXCB0 4TB           | 2         | 0.3%    |
| WDC WD2500AAKX-753CA1 250GB        | 2         | 0.3%    |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.3%    |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 0.3%    |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.3%    |
| WDC WD10JPVX-00JC3T0 1TB           | 2         | 0.3%    |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.3%    |
| WDC WD10EZEX-00BN5A0 1TB           | 2         | 0.3%    |
| Unknown HBG4a2  32GB               | 2         | 0.3%    |
| Toshiba NVMe SSD Drive 256GB       | 2         | 0.3%    |
| Toshiba MQ04ABF100 1TB             | 2         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 86        | 152    | 33.08%  |
| Seagate             | 76        | 131    | 29.23%  |
| Hitachi             | 30        | 40     | 11.54%  |
| Toshiba             | 28        | 34     | 10.77%  |
| Samsung Electronics | 10        | 12     | 3.85%   |
| HGST                | 10        | 10     | 3.85%   |
| Fujitsu             | 7         | 10     | 2.69%   |
| ASMT                | 3         | 5      | 1.15%   |
| MAXTOR              | 2         | 2      | 0.77%   |
| Apple               | 2         | 2      | 0.77%   |
| Unknown             | 1         | 1      | 0.38%   |
| Sabrent             | 1         | 2      | 0.38%   |
| QNAP                | 1         | 1      | 0.38%   |
| LaCie               | 1         | 1      | 0.38%   |
| KESU                | 1         | 1      | 0.38%   |
| ExcelStor           | 1         | 2      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 58        | 81     | 30.05%  |
| Crucial             | 28        | 37     | 14.51%  |
| SanDisk             | 17        | 20     | 8.81%   |
| Kingston            | 16        | 20     | 8.29%   |
| WDC                 | 11        | 17     | 5.7%    |
| Intel               | 5         | 5      | 2.59%   |
| A-DATA Technology   | 5         | 9      | 2.59%   |
| Verbatim            | 4         | 4      | 2.07%   |
| LITEON              | 4         | 4      | 2.07%   |
| China               | 4         | 7      | 2.07%   |
| Toshiba             | 3         | 4      | 1.55%   |
| PNY                 | 3         | 3      | 1.55%   |
| Micron Technology   | 3         | 3      | 1.55%   |
| KingSpec            | 3         | 3      | 1.55%   |
| Apple               | 3         | 3      | 1.55%   |
| Transcend           | 2         | 2      | 1.04%   |
| Team                | 2         | 2      | 1.04%   |
| OCZ                 | 2         | 2      | 1.04%   |
| Netac               | 2         | 2      | 1.04%   |
| KingDian            | 2         | 5      | 1.04%   |
| Integral            | 2         | 2      | 1.04%   |
| Zheino              | 1         | 1      | 0.52%   |
| W800S               | 1         | 2      | 0.52%   |
| USB3.0              | 1         | 1      | 0.52%   |
| TCSUNBOW            | 1         | 1      | 0.52%   |
| SK Hynix            | 1         | 1      | 0.52%   |
| PLEXTOR             | 1         | 1      | 0.52%   |
| PALIT               | 1         | 1      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| Hikvision           | 1         | 1      | 0.52%   |
| FORESEE             | 1         | 1      | 0.52%   |
| Emtec               | 1         | 2      | 0.52%   |
| DRVEO               | 1         | 1      | 0.52%   |
| DOGFISH             | 1         | 1      | 0.52%   |
| Corsair             | 1         | 2      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 208       | 406    | 40.39%  |
| SSD     | 170       | 252    | 33.01%  |
| NVMe    | 102       | 152    | 19.81%  |
| MMC     | 28        | 39     | 5.44%   |
| Unknown | 7         | 7      | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 309       | 636    | 67.17%  |
| NVMe | 102       | 152    | 22.17%  |
| MMC  | 28        | 39     | 6.09%   |
| SAS  | 21        | 29     | 4.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 231       | 375    | 56.34%  |
| 0.51-1.0   | 121       | 177    | 29.51%  |
| 1.01-2.0   | 28        | 40     | 6.83%   |
| 3.01-4.0   | 11        | 24     | 2.68%   |
| 2.01-3.0   | 11        | 18     | 2.68%   |
| 4.01-10.0  | 8         | 24     | 1.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 100       | 24.04%  |
| 251-500        | 98        | 23.56%  |
| 501-1000       | 56        | 13.46%  |
| 51-100         | 38        | 9.13%   |
| 1-20           | 36        | 8.65%   |
| 1001-2000      | 26        | 6.25%   |
| More than 3000 | 25        | 6.01%   |
| Unknown        | 15        | 3.61%   |
| 21-50          | 13        | 3.13%   |
| 2001-3000      | 9         | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 167       | 38.75%  |
| 101-250        | 63        | 14.62%  |
| 21-50          | 58        | 13.46%  |
| 51-100         | 48        | 11.14%  |
| 251-500        | 28        | 6.5%    |
| 501-1000       | 25        | 5.8%    |
| Unknown        | 15        | 3.48%   |
| More than 3000 | 12        | 2.78%   |
| 1001-2000      | 8         | 1.86%   |
| 2001-3000      | 7         | 1.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 5.66%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 5.66%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 2      | 3.77%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.77%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.89%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 1.89%   |
| WDC WD40EFRX-68WT0N0 4TB                       | 1         | 1      | 1.89%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.89%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.89%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.89%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 1.89%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.89%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.89%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.89%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.89%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.89%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 1.89%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.89%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.89%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.89%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.89%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.89%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.89%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.89%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.89%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.89%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.89%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.89%   |
| Netac SSD 128GB                                | 1         | 1      | 1.89%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.89%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.89%   |
| MAXTOR STM3250310AS 250GB                      | 1         | 1      | 1.89%   |
| Intel SSDSA2M080G2GC 80GB                      | 1         | 1      | 1.89%   |
| Hitachi HUS724030ALA640 3TB                    | 1         | 2      | 1.89%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.89%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 1      | 1.89%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.89%   |
| Hitachi HDT721016SLA380 160GB                  | 1         | 2      | 1.89%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 1.89%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.89%   |
| HGST HTS541010A7E630 1TB                       | 1         | 1      | 1.89%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 1.89%   |
| DRVEO X1 SSD 480GB                             | 1         | 1      | 1.89%   |
| China T480 480GB SSD                           | 1         | 1      | 1.89%   |
| A-DATA Technology SU800 128GB SSD              | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 22     | 24%     |
| Seagate             | 10        | 14     | 20%     |
| Hitachi             | 8         | 10     | 16%     |
| Toshiba             | 5         | 5      | 10%     |
| Samsung Electronics | 3         | 3      | 6%      |
| Micron Technology   | 2         | 2      | 4%      |
| HGST                | 2         | 2      | 4%      |
| SanDisk             | 1         | 1      | 2%      |
| Netac               | 1         | 1      | 2%      |
| MAXTOR              | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| DRVEO               | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 22     | 29.27%  |
| Seagate             | 10        | 14     | 24.39%  |
| Hitachi             | 8         | 10     | 19.51%  |
| Toshiba             | 5         | 5      | 12.2%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| MAXTOR              | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 57     | 78.05%  |
| SSD  | 7         | 7      | 17.07%  |
| NVMe | 2         | 2      | 4.88%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 249       | 511    | 57.64%  |
| Works    | 143       | 279    | 33.1%   |
| Malfunc  | 40        | 66     | 9.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 261       | 54.38%  |
| AMD                          | 72        | 15%     |
| Samsung Electronics          | 43        | 8.96%   |
| Sandisk                      | 22        | 4.58%   |
| Nvidia                       | 12        | 2.5%    |
| Toshiba America Info Systems | 9         | 1.88%   |
| Marvell Technology Group     | 8         | 1.67%   |
| ASMedia Technology           | 8         | 1.67%   |
| Micron/Crucial Technology    | 6         | 1.25%   |
| Micron Technology            | 6         | 1.25%   |
| SK Hynix                     | 5         | 1.04%   |
| Phison Electronics           | 5         | 1.04%   |
| JMicron Technology           | 5         | 1.04%   |
| Silicon Motion               | 3         | 0.63%   |
| LSI Logic / Symbios Logic    | 3         | 0.63%   |
| Union Memory (Shenzhen)      | 2         | 0.42%   |
| KIOXIA                       | 2         | 0.42%   |
| ULi Electronics              | 1         | 0.21%   |
| Silicon Image                | 1         | 0.21%   |
| Seagate Technology           | 1         | 0.21%   |
| Realtek Semiconductor        | 1         | 0.21%   |
| Kingston Technology Company  | 1         | 0.21%   |
| Broadcom / LSI               | 1         | 0.21%   |
| ADATA Technology             | 1         | 0.21%   |
| Adaptec                      | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53        | 9.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28        | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 28        | 4.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 3.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 16        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 2.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8         | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.42%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.24%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 1.24%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 1.07%   |
| Micron Non-Volatile memory controller                                                   | 6         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.07%   |
| Nvidia MCP79 AHCI Controller                                                            | 5         | 0.89%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.89%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.71%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.71%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 3         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.53%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3         | 0.53%   |
| Intel SSD 660P Series                                                                   | 3         | 0.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.53%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2         | 0.36%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.36%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.36%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 292       | 60.33%  |
| NVMe | 102       | 21.07%  |
| IDE  | 61        | 12.6%   |
| RAID | 26        | 5.37%   |
| SCSI | 3         | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 298       | 75.83%  |
| AMD    | 88        | 22.39%  |
| ARM    | 7         | 1.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.77%   |
| ARM Processor                                 | 7         | 1.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 1.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.27%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 5         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.01%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 1.01%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.01%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.01%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.01%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.76%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.76%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.76%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.76%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.76%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.76%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.76%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.76%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.76%   |
| AMD Athlon II X4 620 Processor                | 3         | 0.76%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.76%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 2         | 0.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.51%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.51%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.51%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.51%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.51%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.51%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.51%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.51%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.51%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.51%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2         | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.51%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 2         | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.51%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 85        | 21.52%  |
| Intel Core i7           | 82        | 20.76%  |
| Intel Core i3           | 29        | 7.34%   |
| Other                   | 23        | 5.82%   |
| AMD Ryzen 5             | 23        | 5.82%   |
| Intel Core 2 Duo        | 22        | 5.57%   |
| Intel Celeron           | 19        | 4.81%   |
| Intel Atom              | 10        | 2.53%   |
| AMD Ryzen 7             | 9         | 2.28%   |
| Intel Core 2 Quad       | 7         | 1.77%   |
| AMD Ryzen 9             | 7         | 1.77%   |
| Intel Xeon              | 6         | 1.52%   |
| Intel Pentium           | 6         | 1.52%   |
| AMD FX                  | 6         | 1.52%   |
| AMD Athlon 64 X2        | 5         | 1.27%   |
| Intel Pentium Dual-Core | 4         | 1.01%   |
| AMD Ryzen 3             | 4         | 1.01%   |
| AMD A8                  | 4         | 1.01%   |
| AMD Athlon II X4        | 3         | 0.76%   |
| AMD A6                  | 3         | 0.76%   |
| Intel Pentium 4         | 2         | 0.51%   |
| Intel Core m3           | 2         | 0.51%   |
| Intel Core i9           | 2         | 0.51%   |
| Intel Core 2            | 2         | 0.51%   |
| Intel Celeron Dual-Core | 2         | 0.51%   |
| AMD Ryzen Threadripper  | 2         | 0.51%   |
| AMD Ryzen Embedded      | 2         | 0.51%   |
| AMD Phenom II X6        | 2         | 0.51%   |
| AMD A4                  | 2         | 0.51%   |
| Intel Pentium Silver    | 1         | 0.25%   |
| Intel Pentium M         | 1         | 0.25%   |
| Intel Pentium III       | 1         | 0.25%   |
| Intel Pentium D         | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| Intel Core m7           | 1         | 0.25%   |
| Intel Core m5           | 1         | 0.25%   |
| Intel Core 2 Extreme    | 1         | 0.25%   |
| Intel Celeron M         | 1         | 0.25%   |
| AMD Turion 64 X2 Mobile | 1         | 0.25%   |
| AMD Sempron             | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD Phenom II           | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD Athlon II X2        | 1         | 0.25%   |
| AMD Athlon Dual Core    | 1         | 0.25%   |
| AMD Athlon              | 1         | 0.25%   |
| AMD A10                 | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 159       | 40.36%  |
| 4       | 157       | 39.85%  |
| 6       | 32        | 8.12%   |
| 8       | 16        | 4.06%   |
| 1       | 15        | 3.81%   |
| 12      | 9         | 2.28%   |
| 3       | 3         | 0.76%   |
| 32      | 1         | 0.25%   |
| 14      | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 390       | 99.24%  |
| 2      | 3         | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 247       | 62.53%  |
| 1       | 147       | 37.22%  |
| Unknown | 1         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 375       | 94.94%  |
| Unknown        | 17        | 4.3%    |
| 32-bit         | 3         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 22.33%  |
| 0x306a9    | 27        | 6.7%    |
| 0x206a7    | 24        | 5.96%   |
| 0x1067a    | 20        | 4.96%   |
| 0x306c3    | 15        | 3.72%   |
| 0x806e9    | 14        | 3.47%   |
| 0x806ec    | 13        | 3.23%   |
| 0x806ea    | 9         | 2.23%   |
| 0x406e3    | 9         | 2.23%   |
| 0x806c1    | 8         | 1.99%   |
| 0x40651    | 8         | 1.99%   |
| 0x906ea    | 7         | 1.74%   |
| 0x10676    | 7         | 1.74%   |
| 0x906e9    | 6         | 1.49%   |
| 0x406c4    | 6         | 1.49%   |
| 0x306d4    | 6         | 1.49%   |
| 0x30678    | 6         | 1.49%   |
| 0x08701021 | 6         | 1.49%   |
| 0xa0652    | 5         | 1.24%   |
| 0x20655    | 5         | 1.24%   |
| 0x0810100b | 5         | 1.24%   |
| 0x06006705 | 5         | 1.24%   |
| 0x6fd      | 4         | 0.99%   |
| 0x08108109 | 4         | 0.99%   |
| 0x08108102 | 4         | 0.99%   |
| 0x0800820d | 4         | 0.99%   |
| 0xa0653    | 3         | 0.74%   |
| 0x706e5    | 3         | 0.74%   |
| 0x6fb      | 3         | 0.74%   |
| 0x506e3    | 3         | 0.74%   |
| 0x206c2    | 3         | 0.74%   |
| 0x106ca    | 3         | 0.74%   |
| 0x08701013 | 3         | 0.74%   |
| 0x06001119 | 3         | 0.74%   |
| 0x06000852 | 3         | 0.74%   |
| 0x010000c8 | 3         | 0.74%   |
| 0x906ed    | 2         | 0.5%    |
| 0x806d1    | 2         | 0.5%    |
| 0x706a8    | 2         | 0.5%    |
| 0x706a1    | 2         | 0.5%    |
| 0x6f6      | 2         | 0.5%    |
| 0x6d8      | 2         | 0.5%    |
| 0x30661    | 2         | 0.5%    |
| 0x20652    | 2         | 0.5%    |
| 0x106e5    | 2         | 0.5%    |
| 0x106a5    | 2         | 0.5%    |
| 0x0a50000c | 2         | 0.5%    |
| 0x08600103 | 2         | 0.5%    |
| 0x07030106 | 2         | 0.5%    |
| 0x010000db | 2         | 0.5%    |
| 0xf47      | 1         | 0.25%   |
| 0xf43      | 1         | 0.25%   |
| 0xf41      | 1         | 0.25%   |
| 0x906eb    | 1         | 0.25%   |
| 0x906a3    | 1         | 0.25%   |
| 0x6f7      | 1         | 0.25%   |
| 0x6ec      | 1         | 0.25%   |
| 0x6b1      | 1         | 0.25%   |
| 0x506c9    | 1         | 0.25%   |
| 0x406c3    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 57        | 14.5%   |
| IvyBridge        | 36        | 9.16%   |
| SandyBridge      | 34        | 8.65%   |
| Penryn           | 28        | 7.12%   |
| Haswell          | 27        | 6.87%   |
| Zen+             | 18        | 4.58%   |
| Skylake          | 18        | 4.58%   |
| Zen 2            | 17        | 4.33%   |
| Silvermont       | 17        | 4.33%   |
| Westmere         | 14        | 3.56%   |
| Core             | 11        | 2.8%    |
| K10              | 9         | 2.29%   |
| CometLake        | 9         | 2.29%   |
| Zen              | 8         | 2.04%   |
| TigerLake        | 8         | 2.04%   |
| Piledriver       | 8         | 2.04%   |
| K8 Hammer        | 8         | 2.04%   |
| Excavator        | 8         | 2.04%   |
| Broadwell        | 7         | 1.78%   |
| Unknown          | 7         | 1.78%   |
| Nehalem          | 6         | 1.53%   |
| Icelake          | 6         | 1.53%   |
| Goldmont plus    | 6         | 1.53%   |
| Zen 3            | 5         | 1.27%   |
| Bonnell          | 5         | 1.27%   |
| P6               | 4         | 1.02%   |
| Puma             | 3         | 0.76%   |
| NetBurst         | 3         | 0.76%   |
| Bobcat           | 2         | 0.51%   |
| Steamroller      | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |
| Bulldozer        | 1         | 0.25%   |
| Alderlake Hybrid | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 221       | 48.89%  |
| Nvidia | 127       | 28.1%   |
| AMD    | 104       | 23.01%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 4.26%   |
| Intel HD Graphics 620                                                                    | 13        | 2.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.71%   |
| Intel HD Graphics 630                                                                    | 8         | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.49%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.07%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.07%   |
| AMD Renoir                                                                               | 5         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 0.85%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.85%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3         | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.64%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 3         | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.64%   |
| Intel HD Graphics 515                                                                    | 3         | 0.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.64%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 3         | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.64%   |
| AMD Cezanne                                                                              | 3         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.43%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.43%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.43%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.43%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.43%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.43%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 167       | 42.07%  |
| 1 x AMD        | 83        | 20.91%  |
| 1 x Nvidia     | 76        | 19.14%  |
| Intel + Nvidia | 43        | 10.83%  |
| 2 x AMD        | 10        | 2.52%   |
| Other          | 7         | 1.76%   |
| AMD + Nvidia   | 7         | 1.76%   |
| Intel + AMD    | 3         | 0.76%   |
| 2 x Nvidia     | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 314       | 78.5%   |
| Proprietary | 64        | 16%     |
| Unknown     | 22        | 5.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 209       | 51.1%   |
| 0.01-0.5   | 51        | 12.47%  |
| 1.01-2.0   | 42        | 10.27%  |
| 0.51-1.0   | 37        | 9.05%   |
| 3.01-4.0   | 34        | 8.31%   |
| 7.01-8.0   | 18        | 4.4%    |
| 5.01-6.0   | 11        | 2.69%   |
| 2.01-3.0   | 4         | 0.98%   |
| 8.01-16.0  | 2         | 0.49%   |
| 16.01-24.0 | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 48        | 11.68%  |
| AU Optronics            | 47        | 11.44%  |
| Dell                    | 45        | 10.95%  |
| Samsung Electronics     | 42        | 10.22%  |
| Chimei Innolux          | 29        | 7.06%   |
| BOE                     | 27        | 6.57%   |
| Acer                    | 18        | 4.38%   |
| Sharp                   | 17        | 4.14%   |
| Hewlett-Packard         | 14        | 3.41%   |
| Apple                   | 14        | 3.41%   |
| BenQ                    | 12        | 2.92%   |
| Philips                 | 11        | 2.68%   |
| Iiyama                  | 9         | 2.19%   |
| Goldstar                | 8         | 1.95%   |
| AOC                     | 8         | 1.95%   |
| Lenovo                  | 7         | 1.7%    |
| Chi Mei Optoelectronics | 6         | 1.46%   |
| PANDA                   | 4         | 0.97%   |
| Ancor Communications    | 4         | 0.97%   |
| Vestel Elektronik       | 3         | 0.73%   |
| InfoVision              | 3         | 0.73%   |
| HannStar                | 3         | 0.73%   |
| ViewSonic               | 2         | 0.49%   |
| Toshiba                 | 2         | 0.49%   |
| Sony                    | 2         | 0.49%   |
| LG Philips              | 2         | 0.49%   |
| CPT                     | 2         | 0.49%   |
| BOE Technology Group    | 2         | 0.49%   |
| ___                     | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |
| Targa Visionary         | 1         | 0.24%   |
| Targa                   | 1         | 0.24%   |
| RTK                     | 1         | 0.24%   |
| Quanta Display          | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| OEM                     | 1         | 0.24%   |
| NEC Computers           | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |
| MiTAC                   | 1         | 0.24%   |
| Medion                  | 1         | 0.24%   |
| LGD                     | 1         | 0.24%   |
| Lenovo Group Limited    | 1         | 0.24%   |
| HYO                     | 1         | 0.24%   |
| HKC                     | 1         | 0.24%   |
| CSO                     | 1         | 0.24%   |
| CHR                     | 1         | 0.24%   |
| ASUSTek Computer        | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5         | 1.14%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.92%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch | 3         | 0.69%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.69%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 3         | 0.69%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch              | 3         | 0.69%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 2         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.46%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.46%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.46%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 2         | 0.46%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 2         | 0.46%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 2         | 0.46%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2         | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.46%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.46%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.46%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.46%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.46%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.46%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.46%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.46%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                    | 2         | 0.46%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                    | 2         | 0.46%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                    | 2         | 0.46%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                    | 2         | 0.46%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                    | 2         | 0.46%   |
| Dell E171FP DEL300F 1280x1024 340x270mm 17.1-inch                    | 2         | 0.46%   |
| Dell 2007FP DELA020 1600x1200 367x275mm 18.1-inch                    | 2         | 0.46%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                    | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.46%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 2         | 0.46%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch        | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.46%   |
| Apple LED Cinema APP9236 1920x1200 518x324mm 24.1-inch               | 2         | 0.46%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                    | 2         | 0.46%   |
| Acer K222HQL ACR040D 1920x1080 477x268mm 21.5-inch                   | 2         | 0.46%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.23%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1         | 0.23%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1         | 0.23%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.23%   |
| Toshiba TV TSB1206 1360x768                                          | 1         | 0.23%   |
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch            | 1         | 0.23%   |
| Targa Visionary LCD22-1 Wide TARA229 1680x1050 474x297mm 22.0-inch   | 1         | 0.23%   |
| Targa LCD Monitor LCDTV16 1360x768                                   | 1         | 0.23%   |
| Sony TV SNY4302 1920x1080                                            | 1         | 0.23%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                 | 1         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 174       | 43.28%  |
| 1366x768 (WXGA)    | 80        | 19.9%   |
| 3840x2160 (4K)     | 24        | 5.97%   |
| 2560x1440 (QHD)    | 16        | 3.98%   |
| 1600x900 (HD+)     | 15        | 3.73%   |
| 1920x1200 (WUXGA)  | 12        | 2.99%   |
| 1440x900 (WXGA+)   | 12        | 2.99%   |
| 1280x800 (WXGA)    | 12        | 2.99%   |
| 1280x1024 (SXGA)   | 10        | 2.49%   |
| 3440x1440          | 7         | 1.74%   |
| 1680x1050 (WSXGA+) | 6         | 1.49%   |
| 1360x768           | 6         | 1.49%   |
| Unknown            | 6         | 1.49%   |
| 3840x2400          | 3         | 0.75%   |
| 3840x1080          | 3         | 0.75%   |
| 1600x1200          | 3         | 0.75%   |
| 1024x600           | 3         | 0.75%   |
| 3200x1800 (QHD+)   | 2         | 0.5%    |
| 1024x768 (XGA)     | 2         | 0.5%    |
| 6400x2160          | 1         | 0.25%   |
| 5280x2560          | 1         | 0.25%   |
| 3600x1080          | 1         | 0.25%   |
| 2560x1600          | 1         | 0.25%   |
| 2560x1080          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 27.23%  |
| 27      | 40        | 9.64%   |
| 14      | 38        | 9.16%   |
| 13      | 33        | 7.95%   |
| 24      | 30        | 7.23%   |
| 23      | 25        | 6.02%   |
| 21      | 22        | 5.3%    |
| Unknown | 22        | 5.3%    |
| 17      | 20        | 4.82%   |
| 12      | 12        | 2.89%   |
| 19      | 8         | 1.93%   |
| 34      | 7         | 1.69%   |
| 31      | 7         | 1.69%   |
| 18      | 7         | 1.69%   |
| 20      | 5         | 1.2%    |
| 84      | 4         | 0.96%   |
| 11      | 4         | 0.96%   |
| 32      | 3         | 0.72%   |
| 25      | 3         | 0.72%   |
| 10      | 3         | 0.72%   |
| 72      | 2         | 0.48%   |
| 40      | 2         | 0.48%   |
| 22      | 2         | 0.48%   |
| 49      | 1         | 0.24%   |
| 46      | 1         | 0.24%   |
| 35      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 40.29%  |
| 501-600     | 85        | 20.88%  |
| 401-500     | 41        | 10.07%  |
| 201-300     | 40        | 9.83%   |
| Unknown     | 22        | 5.41%   |
| 351-400     | 21        | 5.16%   |
| 601-700     | 13        | 3.19%   |
| 701-800     | 10        | 2.46%   |
| 1501-2000   | 6         | 1.47%   |
| 801-900     | 3         | 0.74%   |
| 1001-1500   | 2         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 282       | 75.81%  |
| 16/10   | 45        | 12.1%   |
| Unknown | 18        | 4.84%   |
| 5/4     | 10        | 2.69%   |
| 21/9    | 8         | 2.15%   |
| 4/3     | 5         | 1.34%   |
| 3/2     | 3         | 0.81%   |
| 32/9    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 26.86%  |
| 201-250        | 62        | 14.87%  |
| 81-90          | 53        | 12.71%  |
| 301-350        | 40        | 9.59%   |
| Unknown        | 22        | 5.28%   |
| 151-200        | 20        | 4.8%    |
| 71-80          | 19        | 4.56%   |
| 351-500        | 18        | 4.32%   |
| 251-300        | 16        | 3.84%   |
| 141-150        | 12        | 2.88%   |
| 61-70          | 11        | 2.64%   |
| 121-130        | 11        | 2.64%   |
| More than 1000 | 6         | 1.44%   |
| 51-60          | 4         | 0.96%   |
| 501-1000       | 4         | 0.96%   |
| 41-50          | 3         | 0.72%   |
| 131-140        | 3         | 0.72%   |
| 111-120        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 119       | 29.46%  |
| 101-120       | 111       | 27.48%  |
| 121-160       | 109       | 26.98%  |
| 161-240       | 23        | 5.69%   |
| Unknown       | 22        | 5.45%   |
| More than 240 | 10        | 2.48%   |
| 1-50          | 10        | 2.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 311       | 77.17%  |
| 2     | 66        | 16.38%  |
| 0     | 20        | 4.96%   |
| 3     | 5         | 1.24%   |
| 4     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 208       | 33.93%  |
| Realtek Semiconductor             | 184       | 30.02%  |
| Qualcomm Atheros                  | 64        | 10.44%  |
| Broadcom                          | 46        | 7.5%    |
| Ralink Technology                 | 12        | 1.96%   |
| Broadcom Limited                  | 12        | 1.96%   |
| Nvidia                            | 11        | 1.79%   |
| Ralink                            | 9         | 1.47%   |
| Marvell Technology Group          | 9         | 1.47%   |
| TP-Link                           | 8         | 1.31%   |
| Ericsson Business Mobile Networks | 5         | 0.82%   |
| Samsung Electronics               | 4         | 0.65%   |
| Microsoft                         | 4         | 0.65%   |
| MEDIATEK                          | 3         | 0.49%   |
| Lenovo                            | 3         | 0.49%   |
| NetGear                           | 2         | 0.33%   |
| ICS Advent                        | 2         | 0.33%   |
| DisplayLink                       | 2         | 0.33%   |
| Belkin Components                 | 2         | 0.33%   |
| Xilinx                            | 1         | 0.16%   |
| Xiaomi                            | 1         | 0.16%   |
| Van Ooijen Technische Informatica | 1         | 0.16%   |
| ULi Electronics                   | 1         | 0.16%   |
| Toshiba                           | 1         | 0.16%   |
| T & A Mobile Phones               | 1         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.16%   |
| NetXen Incorporated               | 1         | 0.16%   |
| Microchip Technology              | 1         | 0.16%   |
| LSI                               | 1         | 0.16%   |
| LG Electronics                    | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| IMC Networks                      | 1         | 0.16%   |
| HMD Global                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| Bose                              | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| ASIX Electronics                  | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |
| 3Com                              | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123       | 16.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 4.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 3.56%   |
| Intel Wi-Fi 6 AX200                                               | 25        | 3.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.23%   |
| Realtek 802.11ac NIC                                              | 9         | 1.23%   |
| Intel Wireless 7260                                               | 9         | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.23%   |
| Intel Wireless-AC 9260                                            | 8         | 1.1%    |
| Intel Wireless 7265                                               | 8         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.96%   |
| Intel Wireless 8260                                               | 7         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.68%   |
| Intel Wireless 3165                                               | 5         | 0.68%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 0.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.55%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.55%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.55%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 3         | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.41%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.41%   |
| Intel Wireless 3160                                               | 3         | 0.41%   |
| Intel WiFi Link 5100                                              | 3         | 0.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.41%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.41%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 45.38%  |
| Qualcomm Atheros                | 56        | 16.18%  |
| Realtek Semiconductor           | 49        | 14.16%  |
| Broadcom                        | 33        | 9.54%   |
| Ralink Technology               | 12        | 3.47%   |
| Ralink                          | 9         | 2.6%    |
| TP-Link                         | 8         | 2.31%   |
| Microsoft                       | 4         | 1.16%   |
| Broadcom Limited                | 4         | 1.16%   |
| MEDIATEK                        | 3         | 0.87%   |
| NetGear                         | 2         | 0.58%   |
| Belkin Components               | 2         | 0.58%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| Qualcomm                        | 1         | 0.29%   |
| LG Electronics                  | 1         | 0.29%   |
| IMC Networks                    | 1         | 0.29%   |
| Dell                            | 1         | 0.29%   |
| ASUSTek Computer                | 1         | 0.29%   |
| Apple                           | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 25        | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4%      |
| Intel Wireless 8265 / 8275                                              | 12        | 3.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.57%   |
| Realtek 802.11ac NIC                                                    | 9         | 2.57%   |
| Intel Wireless 7260                                                     | 9         | 2.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 2.57%   |
| Intel Wireless-AC 9260                                                  | 8         | 2.29%   |
| Intel Wireless 7265                                                     | 8         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2%      |
| Intel Wireless 8260                                                     | 7         | 2%      |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.43%   |
| Intel Wireless 3165                                                     | 5         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.43%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.14%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 4         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.14%   |
| TP-Link 802.11ac WLAN Adapter                                           | 3         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.86%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 0.86%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.86%   |
| Intel Wireless 3160                                                     | 3         | 0.86%   |
| Intel WiFi Link 5100                                                    | 3         | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.86%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.57%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2         | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.57%   |
| NetGear A6210                                                           | 2         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.57%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.57%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.57%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.57%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 162       | 44.88%  |
| Intel                         | 115       | 31.86%  |
| Broadcom                      | 18        | 4.99%   |
| Qualcomm Atheros              | 15        | 4.16%   |
| Nvidia                        | 11        | 3.05%   |
| Marvell Technology Group      | 9         | 2.49%   |
| Broadcom Limited              | 9         | 2.49%   |
| Samsung Electronics           | 4         | 1.11%   |
| Lenovo                        | 3         | 0.83%   |
| ICS Advent                    | 2         | 0.55%   |
| DisplayLink                   | 2         | 0.55%   |
| Xilinx                        | 1         | 0.28%   |
| Xiaomi                        | 1         | 0.28%   |
| ULi Electronics               | 1         | 0.28%   |
| T & A Mobile Phones           | 1         | 0.28%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| NetXen Incorporated           | 1         | 0.28%   |
| Microchip Technology          | 1         | 0.28%   |
| JMicron Technology            | 1         | 0.28%   |
| HMD Global                    | 1         | 0.28%   |
| ASIX Electronics              | 1         | 0.28%   |
| 3Com                          | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123       | 33.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 8.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 7.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.98%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.44%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.81%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.54%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.54%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.54%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.54%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.54%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 0.54%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2         | 0.54%   |
| Xilinx Ethernet controller                                        | 1         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.27%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 1         | 0.27%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.27%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.27%   |
| OnePlus (Shenzhen) AC2001                                         | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 341       | 50.44%  |
| WiFi     | 324       | 47.93%  |
| Modem    | 11        | 1.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 52.89%  |
| Ethernet | 227       | 46.9%   |
| Modem    | 1         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 233       | 58.99%  |
| 1     | 142       | 35.95%  |
| 3     | 9         | 2.28%   |
| 0     | 9         | 2.28%   |
| 6     | 1         | 0.25%   |
| 4     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 366       | 92.42%  |
| Yes  | 30        | 7.58%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 118       | 47.01%  |
| Broadcom                        | 21        | 8.37%   |
| Cambridge Silicon Radio         | 20        | 7.97%   |
| Realtek Semiconductor           | 19        | 7.57%   |
| Qualcomm Atheros Communications | 13        | 5.18%   |
| IMC Networks                    | 13        | 5.18%   |
| Apple                           | 12        | 4.78%   |
| Lite-On Technology              | 10        | 3.98%   |
| Dell                            | 7         | 2.79%   |
| Hewlett-Packard                 | 5         | 1.99%   |
| ASUSTek Computer                | 3         | 1.2%    |
| Toshiba                         | 2         | 0.8%    |
| Realtek                         | 2         | 0.8%    |
| Ralink                          | 1         | 0.4%    |
| Foxconn International           | 1         | 0.4%    |
| Foxconn / Hon Hai               | 1         | 0.4%    |
| Edimax Technology               | 1         | 0.4%    |
| Conwise Technology              | 1         | 0.4%    |
| Belkin Components               | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 50        | 19.84%  |
| Intel AX200 Bluetooth                                       | 24        | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 20        | 7.94%   |
| Intel AX201 Bluetooth                                       | 18        | 7.14%   |
| Realtek Bluetooth Radio                                     | 11        | 4.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 3.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 8         | 3.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6         | 2.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 2.38%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 1.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 1.98%   |
| IMC Networks Bluetooth Device                               | 5         | 1.98%   |
| Apple Bluetooth Host Controller                             | 5         | 1.98%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 1.59%   |
| IMC Networks Bluetooth Radio                                | 4         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 1.59%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.19%   |
| Apple Bluetooth USB Host Controller                         | 3         | 1.19%   |
| Apple Bluetooth HCI                                         | 3         | 1.19%   |
| Realtek Bluetooth Radio                                     | 2         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 0.79%   |
| Intel Bluetooth Device                                      | 2         | 0.79%   |
| Intel AX210 Bluetooth                                       | 2         | 0.79%   |
| IMC Networks Wireless_Device                                | 2         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.79%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 0.79%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.79%   |
| Toshiba Bluetooth Device                                    | 1         | 0.4%    |
| Toshiba BCM43142A0                                          | 1         | 0.4%    |
| Realtek 802.11n WLAN Adapter                                | 1         | 0.4%    |
| Ralink RT3290 Bluetooth                                     | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.4%    |
| Lite-On Wireless_Device                                     | 1         | 0.4%    |
| Lite-On BCM43142A0                                          | 1         | 0.4%    |
| Lite-On Atheros Bluetooth                                   | 1         | 0.4%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.4%    |
| Foxconn International BCM43142A0 Bluetooth module           | 1         | 0.4%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.4%    |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 0.4%    |
| Dell Wireless 365 Bluetooth                                 | 1         | 0.4%    |
| Dell Wireless 350 Bluetooth                                 | 1         | 0.4%    |
| Dell BT Mini-Receiver                                       | 1         | 0.4%    |
| Conwise CW6622                                              | 1         | 0.4%    |
| Broadcom Bluetooth Device                                   | 1         | 0.4%    |
| Broadcom BCM92045B3 ROM                                     | 1         | 0.4%    |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 0.4%    |
| Belkin Components F8T012 Bluetooth Adapter                  | 1         | 0.4%    |
| ASUS Qualcomm Bluetooth 4.1                                 | 1         | 0.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.4%    |
| ASUS Bluetooth Device                                       | 1         | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 283       | 51.45%  |
| AMD                                             | 114       | 20.73%  |
| Nvidia                                          | 100       | 18.18%  |
| C-Media Electronics                             | 6         | 1.09%   |
| Creative Technology                             | 4         | 0.73%   |
| Creative Labs                                   | 4         | 0.73%   |
| Plantronics                                     | 3         | 0.55%   |
| GN Netcom                                       | 3         | 0.55%   |
| Texas Instruments                               | 2         | 0.36%   |
| Realtek Semiconductor                           | 2         | 0.36%   |
| Logitech                                        | 2         | 0.36%   |
| Lenovo                                          | 2         | 0.36%   |
| JMTek                                           | 2         | 0.36%   |
| Ensoniq                                         | 2         | 0.36%   |
| VIA Technologies                                | 1         | 0.18%   |
| ULi Electronics                                 | 1         | 0.18%   |
| Turtle Beach                                    | 1         | 0.18%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.18%   |
| Sony                                            | 1         | 0.18%   |
| SAVITECH                                        | 1         | 0.18%   |
| RODE Microphones                                | 1         | 0.18%   |
| Razer USA                                       | 1         | 0.18%   |
| Micronas                                        | 1         | 0.18%   |
| M-Audio                                         | 1         | 0.18%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.18%   |
| Kingston Technology                             | 1         | 0.18%   |
| Giga-Byte Technology                            | 1         | 0.18%   |
| Focusrite-Novation                              | 1         | 0.18%   |
| FiiO Electronics Technology                     | 1         | 0.18%   |
| ESS Technology                                  | 1         | 0.18%   |
| Corsair                                         | 1         | 0.18%   |
| AudioQuest                                      | 1         | 0.18%   |
| AUDIOLAB                                        | 1         | 0.18%   |
| Audio-Technica                                  | 1         | 0.18%   |
| Audient                                         | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 5.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 5.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 3.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 2.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 13        | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 11        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.4%    |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.4%    |
| AMD FCH Azalia Controller                                                                         | 9         | 1.4%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 8         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8         | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7         | 1.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.09%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.94%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 0.94%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.78%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.78%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.47%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.47%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.47%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3         | 0.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 19.74%  |
| SK Hynix            | 34        | 14.59%  |
| Unknown             | 29        | 12.45%  |
| Corsair             | 24        | 10.3%   |
| Crucial             | 23        | 9.87%   |
| Micron Technology   | 21        | 9.01%   |
| Kingston            | 19        | 8.15%   |
| Ramaxel Technology  | 7         | 3%      |
| G.Skill             | 6         | 2.58%   |
| Elpida              | 5         | 2.15%   |
| Team                | 3         | 1.29%   |
| Nanya Technology    | 3         | 1.29%   |
| Unknown (ABCD)      | 2         | 0.86%   |
| Patriot             | 2         | 0.86%   |
| Apacer              | 2         | 0.86%   |
| Transcend           | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| SHARETRONIC         | 1         | 0.43%   |
| OSV                 | 1         | 0.43%   |
| Infineon            | 1         | 0.43%   |
| CSX                 | 1         | 0.43%   |
| A Force             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 5         | 1.99%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.2%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.2%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 3         | 1.2%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 1.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 3         | 1.2%    |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s             | 3         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                             | 2         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 2         | 0.8%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 2         | 0.8%    |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                          | 2         | 0.8%    |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.8%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 2         | 0.8%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.8%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.8%    |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 0.8%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 0.8%    |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s                | 2         | 0.8%    |
| Elpida RAM EBJ41UF8BDU0-DJ-F 2048MB Chip DDR3 1333MT/s              | 2         | 0.8%    |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s               | 2         | 0.8%    |
| Crucial RAM CT16G4SFRA32A.M16FRS 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.8%    |
| Corsair RAM CMK16GX4M2D3000C16 8192MB DIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 0.4%    |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.4%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                             | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                                | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM 800MT/s                            | 1         | 0.4%    |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.4%    |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 1         | 0.4%    |
| Unknown RAM Module 256MB SODIMM DRAM                                | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1         | 0.4%    |
| Unknown RAM Module 2048MB DIMM                                      | 1         | 0.4%    |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.4%    |
| Unknown RAM Module 1GB DIMM 667MT/s                                 | 1         | 0.4%    |
| Unknown RAM Module 128MB SODIMM DRAM                                | 1         | 0.4%    |
| Unknown RAM Module 128MB DIMM SDRAM                                 | 1         | 0.4%    |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 1         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.4%    |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                   | 1         | 0.4%    |
| Toshiba RAM 99U5702-094.A00G 8192MB DIMM DDR4 2400MT/s              | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-2400 16384MB DIMM DDR4 2400MT/s              | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 42.79%  |
| DDR3    | 66        | 31.73%  |
| DDR2    | 12        | 5.77%   |
| Unknown | 12        | 5.77%   |
| SDRAM   | 9         | 4.33%   |
| LPDDR4  | 9         | 4.33%   |
| LPDDR3  | 6         | 2.88%   |
| DDR     | 3         | 1.44%   |
| DRAM    | 2         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 55.83%  |
| DIMM         | 70        | 33.98%  |
| Row Of Chips | 15        | 7.28%   |
| Chip         | 4         | 1.94%   |
| Unknown      | 2         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 34.08%  |
| 4096  | 63        | 28.25%  |
| 2048  | 35        | 15.7%   |
| 16384 | 32        | 14.35%  |
| 1024  | 9         | 4.04%   |
| 32768 | 4         | 1.79%   |
| 128   | 2         | 0.9%    |
| 512   | 1         | 0.45%   |
| 256   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 44        | 19.38%  |
| 2667    | 34        | 14.98%  |
| 3200    | 19        | 8.37%   |
| 2400    | 18        | 7.93%   |
| 2133    | 16        | 7.05%   |
| 1333    | 13        | 5.73%   |
| 800     | 12        | 5.29%   |
| 667     | 9         | 3.96%   |
| 3600    | 7         | 3.08%   |
| 1334    | 7         | 3.08%   |
| 4267    | 6         | 2.64%   |
| 3266    | 5         | 2.2%    |
| Unknown | 5         | 2.2%    |
| 1867    | 4         | 1.76%   |
| 1067    | 4         | 1.76%   |
| 3466    | 3         | 1.32%   |
| 4199    | 2         | 0.88%   |
| 3400    | 2         | 0.88%   |
| 1866    | 2         | 0.88%   |
| 1800    | 2         | 0.88%   |
| 1066    | 2         | 0.88%   |
| 975     | 2         | 0.88%   |
| 533     | 2         | 0.88%   |
| 4800    | 1         | 0.44%   |
| 3800    | 1         | 0.44%   |
| 3733    | 1         | 0.44%   |
| 3000    | 1         | 0.44%   |
| 2933    | 1         | 0.44%   |
| 2048    | 1         | 0.44%   |
| 400     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| STMicroelectronics  | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 20%     |
| Samsung M2070 Series                                      | 1         | 20%     |
| Canon PIXMA MG2500 Series                                 | 1         | 20%     |
| Brother MFC-L2700DW                                       | 1         | 20%     |
| Brother HL-L2340D series                                  | 1         | 20%     |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 60        | 24.69%  |
| Realtek Semiconductor                  | 28        | 11.52%  |
| Microdia                               | 20        | 8.23%   |
| IMC Networks                           | 20        | 8.23%   |
| Acer                                   | 20        | 8.23%   |
| Logitech                               | 16        | 6.58%   |
| Apple                                  | 11        | 4.53%   |
| Sunplus Innovation Technology          | 8         | 3.29%   |
| Quanta                                 | 8         | 3.29%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.88%   |
| Suyin                                  | 6         | 2.47%   |
| Samsung Electronics                    | 5         | 2.06%   |
| ALi                                    | 5         | 2.06%   |
| Microsoft                              | 4         | 1.65%   |
| Syntek                                 | 3         | 1.23%   |
| Silicon Motion                         | 3         | 1.23%   |
| Ricoh                                  | 3         | 1.23%   |
| Lite-On Technology                     | 2         | 0.82%   |
| Creative Technology                    | 2         | 0.82%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Y Media                                | 1         | 0.41%   |
| USB3.0 HD Audio Capture                | 1         | 0.41%   |
| Trust                                  | 1         | 0.41%   |
| Razer USA                              | 1         | 0.41%   |
| Nikon                                  | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| GenesysLogic Technology                | 1         | 0.41%   |
| Generalplus Technology                 | 1         | 0.41%   |
| GEMBIRD                                | 1         | 0.41%   |
| CQG-5693-201019                        | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 13        | 5.28%   |
| Microdia Integrated_Webcam_HD                    | 9         | 3.66%   |
| Chicony Integrated Camera                        | 9         | 3.66%   |
| Apple Built-in iSight                            | 8         | 3.25%   |
| Chicony USB2.0 Camera                            | 7         | 2.85%   |
| Chicony HD Webcam                                | 7         | 2.85%   |
| IMC Networks Integrated Camera                   | 6         | 2.44%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 2.03%   |
| Logitech HD Pro Webcam C920                      | 5         | 2.03%   |
| Microdia Integrated Webcam                       | 4         | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam                | 4         | 1.63%   |
| Acer Integrated Camera                           | 4         | 1.63%   |
| Acer EasyCamera                                  | 4         | 1.63%   |
| Realtek Integrated Webcam HD                     | 3         | 1.22%   |
| Microsoft LifeCam HD-3000                        | 3         | 1.22%   |
| Logitech Webcam C270                             | 3         | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.22%   |
| Chicony Lenovo EasyCamera                        | 3         | 1.22%   |
| Chicony EasyCamera                               | 3         | 1.22%   |
| ALi WebCam                                       | 3         | 1.22%   |
| Acer BisonCam, NB Pro                            | 3         | 1.22%   |
| Syntek EasyCamera                                | 2         | 0.81%   |
| Suyin HP Truevision HD                           | 2         | 0.81%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 0.81%   |
| Sunplus Full HD webcam                           | 2         | 0.81%   |
| Realtek USB Camera                               | 2         | 0.81%   |
| Realtek HD WebCam                                | 2         | 0.81%   |
| Realtek EasyCamera                               | 2         | 0.81%   |
| Quanta HP Webcam                                 | 2         | 0.81%   |
| Logitech C922 Pro Stream Webcam                  | 2         | 0.81%   |
| Logitech B525 HD Webcam                          | 2         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.81%   |
| IMC Networks TOSHIBA Web Camera - HD             | 2         | 0.81%   |
| IMC Networks EasyCamera                          | 2         | 0.81%   |
| Creative Live! Cam Sync HD [VF0770]              | 2         | 0.81%   |
| Chicony thinkpad t430s camera                    | 2         | 0.81%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 0.81%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 0.81%   |
| Chicony HP TrueVision HD Camera                  | 2         | 0.81%   |
| Chicony HP Truevision HD                         | 2         | 0.81%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE                        | 2         | 0.81%   |
| ALi Gateway Webcam                               | 2         | 0.81%   |
| Acer Lenovo EasyCamera                           | 2         | 0.81%   |
| Acer BisonCam,NB Pro                             | 2         | 0.81%   |
| Z-Star Webcam                                    | 1         | 0.41%   |
| Y Media USB Camera                               | 1         | 0.41%   |
| USB3.0 HD Audio Capture USB3.0 HD Video Capture  | 1         | 0.41%   |
| Trust USB Camera                                 | 1         | 0.41%   |
| Syntek Integrated Camera                         | 1         | 0.41%   |
| Suyin VGA Webcam                                 | 1         | 0.41%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.41%   |
| Suyin Acer CrystalEye Webcam                     | 1         | 0.41%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.41%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.41%   |
| Sunplus HD Webcam                                | 1         | 0.41%   |
| Sunplus DELL XPS Integrated Webcam               | 1         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 32.73%  |
| Validity Sensors           | 16        | 29.09%  |
| Shenzhen Goodix Technology | 9         | 16.36%  |
| Upek                       | 4         | 7.27%   |
| LighTuning Technology      | 2         | 3.64%   |
| Elan Microelectronics      | 2         | 3.64%   |
| AuthenTec                  | 2         | 3.64%   |
| STMicroelectronics         | 1         | 1.82%   |
| Focal-systems.Corp         | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 16.36%  |
| Shenzhen Goodix FingerPrint                                | 6         | 10.91%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 7.27%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.64%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.64%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.64%   |
| Synaptics  WBDI                                            | 2         | 3.64%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.64%   |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 3.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.64%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.64%   |
| AuthenTec Fingerprint Sensor                               | 2         | 3.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.82%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.82%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.82%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.82%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 51.72%  |
| Upek        | 5         | 17.24%  |
| O2 Micro    | 4         | 13.79%  |
| Alcor Micro | 4         | 13.79%  |
| Lenovo      | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 17.24%  |
| Broadcom 58200                                                               | 5         | 17.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.79%  |
| Broadcom 5880                                                                | 4         | 13.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 264       | 65.84%  |
| 1     | 113       | 28.18%  |
| 2     | 19        | 4.74%   |
| 3     | 5         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 54        | 34.39%  |
| Net/wireless             | 30        | 19.11%  |
| Chipcard                 | 27        | 17.2%   |
| Graphics card            | 21        | 13.38%  |
| Multimedia controller    | 9         | 5.73%   |
| Communication controller | 5         | 3.18%   |
| Storage                  | 4         | 2.55%   |
| Camera                   | 3         | 1.91%   |
| Net/ethernet             | 1         | 0.64%   |
| Modem                    | 1         | 0.64%   |
| Card reader              | 1         | 0.64%   |
| Bluetooth                | 1         | 0.64%   |
