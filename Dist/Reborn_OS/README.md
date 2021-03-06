Reborn OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Reborn OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Reborn_OS/Desktop/README.md) and [notebooks](/Dist/Reborn_OS/Notebook/README.md).

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

Total: 178

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Shuttle       | FZ270                       | Desktop     | [ed3e018227](https://linux-hardware.org/?probe=ed3e018227) | Mar 09, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [5ac6cdc8fb](https://linux-hardware.org/?probe=5ac6cdc8fb) | Feb 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc31f5f2bd](https://linux-hardware.org/?probe=bc31f5f2bd) | Jan 17, 2022 |
| Dell          | 0V8DVD A01                  | All in one  | [1645dd96fd](https://linux-hardware.org/?probe=1645dd96fd) | Jan 04, 2022 |
| HP            | ProBook 6550b               | Notebook    | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [714f759476](https://linux-hardware.org/?probe=714f759476) | Dec 06, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7dba1540ad](https://linux-hardware.org/?probe=7dba1540ad) | Dec 06, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [66c592a074](https://linux-hardware.org/?probe=66c592a074) | Nov 05, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [6b0d6d003d](https://linux-hardware.org/?probe=6b0d6d003d) | Nov 03, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [9fd4c9e3a2](https://linux-hardware.org/?probe=9fd4c9e3a2) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [fd68d44a6a](https://linux-hardware.org/?probe=fd68d44a6a) | Oct 16, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [409fb80ae5](https://linux-hardware.org/?probe=409fb80ae5) | Sep 10, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [8c38c04148](https://linux-hardware.org/?probe=8c38c04148) | Sep 05, 2021 |
| Acer          | Aspire V3-111P              | Notebook    | [af61c27b54](https://linux-hardware.org/?probe=af61c27b54) | Sep 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [13aee77624](https://linux-hardware.org/?probe=13aee77624) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [19226582d9](https://linux-hardware.org/?probe=19226582d9) | May 31, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [dd4a0707ba](https://linux-hardware.org/?probe=dd4a0707ba) | May 19, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [426fc0381c](https://linux-hardware.org/?probe=426fc0381c) | May 08, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [58fbf7553b](https://linux-hardware.org/?probe=58fbf7553b) | May 03, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [27595787eb](https://linux-hardware.org/?probe=27595787eb) | Apr 26, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec119e020d](https://linux-hardware.org/?probe=ec119e020d) | Apr 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [989604544a](https://linux-hardware.org/?probe=989604544a) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1b1d0bc44f](https://linux-hardware.org/?probe=1b1d0bc44f) | Mar 27, 2021 |
| CyberPower... | Tracer Series               | Notebook    | [295977bfa3](https://linux-hardware.org/?probe=295977bfa3) | Mar 24, 2021 |
| HP            | 3048h                       | Desktop     | [b61eb90220](https://linux-hardware.org/?probe=b61eb90220) | Mar 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [890d530c6a](https://linux-hardware.org/?probe=890d530c6a) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0e8f323e0f](https://linux-hardware.org/?probe=0e8f323e0f) | Mar 18, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [a949911df6](https://linux-hardware.org/?probe=a949911df6) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4a76fb93d3](https://linux-hardware.org/?probe=4a76fb93d3) | Mar 16, 2021 |
| Dell          | Latitude E6320              | Notebook    | [9439943a67](https://linux-hardware.org/?probe=9439943a67) | Mar 15, 2021 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [926ae13f69](https://linux-hardware.org/?probe=926ae13f69) | Mar 09, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [1f0a994797](https://linux-hardware.org/?probe=1f0a994797) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6c98f8666d](https://linux-hardware.org/?probe=6c98f8666d) | Feb 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [e6476ce804](https://linux-hardware.org/?probe=e6476ce804) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6042185966](https://linux-hardware.org/?probe=6042185966) | Feb 05, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c4549fed4](https://linux-hardware.org/?probe=8c4549fed4) | Feb 05, 2021 |
| Dell          | Precision M4600             | Notebook    | [661670d030](https://linux-hardware.org/?probe=661670d030) | Jan 27, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0bb6c600d0](https://linux-hardware.org/?probe=0bb6c600d0) | Jan 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [cb03a43d6b](https://linux-hardware.org/?probe=cb03a43d6b) | Jan 18, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [e95dad9e90](https://linux-hardware.org/?probe=e95dad9e90) | Jan 14, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b07052df59](https://linux-hardware.org/?probe=b07052df59) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| MSI           | MEG X570 ACE                | Desktop     | [5b061048ce](https://linux-hardware.org/?probe=5b061048ce) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [f50fd232e1](https://linux-hardware.org/?probe=f50fd232e1) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3e1cc88a](https://linux-hardware.org/?probe=ed3e1cc88a) | Jan 04, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fb77017d74](https://linux-hardware.org/?probe=fb77017d74) | Jan 04, 2021 |
| ASUSTek       | P8B75-V                     | Desktop     | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d4c9b8f1](https://linux-hardware.org/?probe=60d4c9b8f1) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bab82e261e](https://linux-hardware.org/?probe=bab82e261e) | Jan 02, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [253b9e5126](https://linux-hardware.org/?probe=253b9e5126) | Jan 01, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [016282f72d](https://linux-hardware.org/?probe=016282f72d) | Jan 01, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [45b5f0850b](https://linux-hardware.org/?probe=45b5f0850b) | Dec 30, 2020 |
| HP            | Pavilion g7                 | Notebook    | [4df7168c54](https://linux-hardware.org/?probe=4df7168c54) | Dec 27, 2020 |
| HP            | Pavilion g7                 | Notebook    | [e2b98139df](https://linux-hardware.org/?probe=e2b98139df) | Dec 27, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | ThinkPad E570 20H50048US    | Notebook    | [db0d5b5a47](https://linux-hardware.org/?probe=db0d5b5a47) | Dec 15, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [c537d4854e](https://linux-hardware.org/?probe=c537d4854e) | Dec 14, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [f1f14b545e](https://linux-hardware.org/?probe=f1f14b545e) | Dec 13, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [d0fc564ec7](https://linux-hardware.org/?probe=d0fc564ec7) | Dec 11, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [c5a5070a6f](https://linux-hardware.org/?probe=c5a5070a6f) | Dec 10, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [f5429557cc](https://linux-hardware.org/?probe=f5429557cc) | Dec 10, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [2385d54def](https://linux-hardware.org/?probe=2385d54def) | Dec 09, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [6ea56336d8](https://linux-hardware.org/?probe=6ea56336d8) | Dec 03, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [a4e4cd792d](https://linux-hardware.org/?probe=a4e4cd792d) | Dec 02, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [a5ec379304](https://linux-hardware.org/?probe=a5ec379304) | Dec 01, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [67aeba9d99](https://linux-hardware.org/?probe=67aeba9d99) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y450                | Notebook    | [300a14fb31](https://linux-hardware.org/?probe=300a14fb31) | Nov 29, 2020 |
| HP            | ProBook 640 G5              | Notebook    | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| Lenovo        | G470 20078                  | Notebook    | [98c4778da6](https://linux-hardware.org/?probe=98c4778da6) | Nov 18, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [a135ed4b82](https://linux-hardware.org/?probe=a135ed4b82) | Nov 08, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [151ca5d99e](https://linux-hardware.org/?probe=151ca5d99e) | Nov 08, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [9153f43376](https://linux-hardware.org/?probe=9153f43376) | Nov 02, 2020 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [d6fd55eee0](https://linux-hardware.org/?probe=d6fd55eee0) | Nov 01, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | ThinkCentre M58 6258WCY     | Desktop     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| Dell          | Latitude 5500               | Notebook    | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| Sony          | VPCEH10EB                   | Notebook    | [167720fe57](https://linux-hardware.org/?probe=167720fe57) | Oct 25, 2020 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [5f4ab6b326](https://linux-hardware.org/?probe=5f4ab6b326) | Oct 18, 2020 |
| Foxconn       | H61S                        | Desktop     | [0fd947c658](https://linux-hardware.org/?probe=0fd947c658) | Oct 12, 2020 |
| Razer         | Blade                       | Notebook    | [14ed46b628](https://linux-hardware.org/?probe=14ed46b628) | Oct 04, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [337abf3073](https://linux-hardware.org/?probe=337abf3073) | Sep 30, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6141f19045](https://linux-hardware.org/?probe=6141f19045) | Sep 17, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [a34a40a5ff](https://linux-hardware.org/?probe=a34a40a5ff) | Sep 17, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4fcaaadd6e](https://linux-hardware.org/?probe=4fcaaadd6e) | Sep 12, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [e0551a0a1c](https://linux-hardware.org/?probe=e0551a0a1c) | Sep 10, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [69b6d5e2e2](https://linux-hardware.org/?probe=69b6d5e2e2) | Sep 08, 2020 |
| Huanan        | X79-8D VAA31                | Desktop     | [66006c461d](https://linux-hardware.org/?probe=66006c461d) | Sep 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [524f57a765](https://linux-hardware.org/?probe=524f57a765) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3fe15728ad](https://linux-hardware.org/?probe=3fe15728ad) | Sep 06, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [e3f12cdd9b](https://linux-hardware.org/?probe=e3f12cdd9b) | Sep 05, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [8af1b0565b](https://linux-hardware.org/?probe=8af1b0565b) | Sep 03, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| HP            | 630                         | Notebook    | [baf66f73a2](https://linux-hardware.org/?probe=baf66f73a2) | Aug 14, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [49170a6643](https://linux-hardware.org/?probe=49170a6643) | Aug 12, 2020 |
| HP            | 630                         | Notebook    | [1f0b52b96d](https://linux-hardware.org/?probe=1f0b52b96d) | Aug 12, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [27ed844469](https://linux-hardware.org/?probe=27ed844469) | Aug 08, 2020 |
| MSI           | IONA                        | Desktop     | [0510d0f8ef](https://linux-hardware.org/?probe=0510d0f8ef) | Aug 06, 2020 |
| MSI           | IONA                        | Desktop     | [446e406f22](https://linux-hardware.org/?probe=446e406f22) | Aug 06, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [d40ce43d66](https://linux-hardware.org/?probe=d40ce43d66) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9c79ef0e1c](https://linux-hardware.org/?probe=9c79ef0e1c) | Jul 31, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [242b101828](https://linux-hardware.org/?probe=242b101828) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | Notebook    | [3b431d9c9a](https://linux-hardware.org/?probe=3b431d9c9a) | Jul 31, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [3fea05b48d](https://linux-hardware.org/?probe=3fea05b48d) | Jul 30, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [52b8fcb9b0](https://linux-hardware.org/?probe=52b8fcb9b0) | Jul 26, 2020 |
| Dell          | Latitude E6430              | Notebook    | [d14e88e089](https://linux-hardware.org/?probe=d14e88e089) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [56cc69c796](https://linux-hardware.org/?probe=56cc69c796) | Jun 27, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [a1aaa82c04](https://linux-hardware.org/?probe=a1aaa82c04) | Jun 25, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [1bab33423f](https://linux-hardware.org/?probe=1bab33423f) | Jun 25, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [9db3e10b4f](https://linux-hardware.org/?probe=9db3e10b4f) | Jun 21, 2020 |
| Lenovo        | ThinkPad T510 4349BS9       | Notebook    | [c525e8d7d2](https://linux-hardware.org/?probe=c525e8d7d2) | May 18, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | Notebook    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [cd1f7d692d](https://linux-hardware.org/?probe=cd1f7d692d) | May 01, 2020 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7f1a8c200a](https://linux-hardware.org/?probe=7f1a8c200a) | Apr 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [ddff2712b8](https://linux-hardware.org/?probe=ddff2712b8) | Apr 17, 2020 |
| Dell          | G7 7588                     | Notebook    | [68c487eb50](https://linux-hardware.org/?probe=68c487eb50) | Apr 15, 2020 |
| Lenovo        | ThinkPad 10 20C10026UK      | Tablet      | [6460dcf515](https://linux-hardware.org/?probe=6460dcf515) | Apr 13, 2020 |
| Gigabyte      | F2A75-D3H                   | Desktop     | [59a8d5230f](https://linux-hardware.org/?probe=59a8d5230f) | Apr 09, 2020 |
| Pegatron      | 2A99                        | Desktop     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [c27fa8aa9c](https://linux-hardware.org/?probe=c27fa8aa9c) | Apr 06, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [97ffeec17e](https://linux-hardware.org/?probe=97ffeec17e) | Mar 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [9d64ff0beb](https://linux-hardware.org/?probe=9d64ff0beb) | Mar 22, 2020 |
| Dell          | Inspiron 5421               | Notebook    | [2d8871e6ac](https://linux-hardware.org/?probe=2d8871e6ac) | Mar 19, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aaac6f9d4d](https://linux-hardware.org/?probe=aaac6f9d4d) | Mar 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [63b8db155d](https://linux-hardware.org/?probe=63b8db155d) | Mar 02, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [ed0b979970](https://linux-hardware.org/?probe=ed0b979970) | Mar 01, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [85c6480266](https://linux-hardware.org/?probe=85c6480266) | Mar 01, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [0f180375d6](https://linux-hardware.org/?probe=0f180375d6) | Feb 25, 2020 |
| HP            | Pavilion 17                 | Notebook    | [5d3ccb9ed7](https://linux-hardware.org/?probe=5d3ccb9ed7) | Feb 24, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [55c569be56](https://linux-hardware.org/?probe=55c569be56) | Feb 23, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [98ae2a8227](https://linux-hardware.org/?probe=98ae2a8227) | Feb 22, 2020 |
| HP            | Pavilion dm1                | Notebook    | [e2e4a2c41f](https://linux-hardware.org/?probe=e2e4a2c41f) | Feb 13, 2020 |
| HP            | Pavilion 17                 | Notebook    | [26bdca3832](https://linux-hardware.org/?probe=26bdca3832) | Feb 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [48487463eb](https://linux-hardware.org/?probe=48487463eb) | Feb 09, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b189e00138](https://linux-hardware.org/?probe=b189e00138) | Jan 16, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [ecb6ade802](https://linux-hardware.org/?probe=ecb6ade802) | Jan 16, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [9c202df9eb](https://linux-hardware.org/?probe=9c202df9eb) | Jan 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | Notebook    | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | Notebook    | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | Notebook    | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [64266b67a2](https://linux-hardware.org/?probe=64266b67a2) | Dec 26, 2019 |
| HP            | 82F2 A01                    | Desktop     | [0b8306e086](https://linux-hardware.org/?probe=0b8306e086) | Nov 18, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [adf2d5daca](https://linux-hardware.org/?probe=adf2d5daca) | Oct 31, 2019 |
| Dell          | 0773VG A00                  | Desktop     | [2f3044da6d](https://linux-hardware.org/?probe=2f3044da6d) | Oct 31, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [fcc16b2804](https://linux-hardware.org/?probe=fcc16b2804) | Oct 11, 2019 |
| MSI           | C236A WORKSTATION           | Desktop     | [f68bc503a9](https://linux-hardware.org/?probe=f68bc503a9) | Oct 11, 2019 |
| ASUSTek       | X555YI                      | Notebook    | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | Notebook    | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2560a1cb4e](https://linux-hardware.org/?probe=2560a1cb4e) | Aug 28, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b013eab87a](https://linux-hardware.org/?probe=b013eab87a) | Aug 27, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [81c929f40d](https://linux-hardware.org/?probe=81c929f40d) | Jan 23, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2180eb318a](https://linux-hardware.org/?probe=2180eb318a) | Dec 30, 2018 |
| Lenovo        | G570 20079                  | Notebook    | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |
| ASRock        | H97M Pro4                   | Desktop     | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [812afde3d9](https://linux-hardware.org/?probe=812afde3d9) | Nov 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Reborn OS         | 112       | 88.89%  |
| Reborn OS Rolling | 14        | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Reborn OS | 126       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.9.14-arch1-1       | 8         | 5.97%   |
| 5.9.1-arch1-1        | 4         | 2.99%   |
| 5.7.12-arch1-1       | 4         | 2.99%   |
| 5.5.9-arch1-2        | 4         | 2.99%   |
| 5.10.3-arch1-1       | 4         | 2.99%   |
| 5.9.10-arch1-1       | 3         | 2.24%   |
| 5.8.5-arch1-1        | 3         | 2.24%   |
| 5.5.2-arch1-1        | 3         | 2.24%   |
| 5.4.10-arch1-1       | 3         | 2.24%   |
| 5.9.13-arch1-1       | 2         | 1.49%   |
| 5.9.11-arch2-1       | 2         | 1.49%   |
| 5.8.7-arch1-1        | 2         | 1.49%   |
| 5.7.11-arch1-1       | 2         | 1.49%   |
| 5.7.10-arch1-1       | 2         | 1.49%   |
| 5.6.4-arch1-1        | 2         | 1.49%   |
| 5.6.3-arch1-1        | 2         | 1.49%   |
| 5.2.9-arch1-1-ARCH   | 2         | 1.49%   |
| 5.16.9-arch1-1       | 2         | 1.49%   |
| 5.16.12-arch1-1      | 2         | 1.49%   |
| 5.14.16-arch1-1      | 2         | 1.49%   |
| 5.11.7-arch1-1       | 2         | 1.49%   |
| 5.11.6-arch1-1       | 2         | 1.49%   |
| 5.11.1-arch1-1       | 2         | 1.49%   |
| 5.10.4-arch2-1       | 2         | 1.49%   |
| 5.10.13-arch1-1      | 2         | 1.49%   |
| 5.9.6-arch1-1        | 1         | 0.75%   |
| 5.9.3-arch1-1        | 1         | 0.75%   |
| 5.9.2-zen1-1-zen     | 1         | 0.75%   |
| 5.9.2-arch1-1        | 1         | 0.75%   |
| 5.9.12-arch1-1       | 1         | 0.75%   |
| 5.9.10-zen1-1-zen    | 1         | 0.75%   |
| 5.8.8-arch1-1        | 1         | 0.75%   |
| 5.8.6-arch1-1        | 1         | 0.75%   |
| 5.8.14-arch1-1       | 1         | 0.75%   |
| 5.8.13-arch1-1       | 1         | 0.75%   |
| 5.8.12-arch1-1       | 1         | 0.75%   |
| 5.8.1-arch1-1        | 1         | 0.75%   |
| 5.7.8-arch1-1        | 1         | 0.75%   |
| 5.7.6-arch1-1-custom | 1         | 0.75%   |
| 5.7.6-arch1-1        | 1         | 0.75%   |
| 5.7.5-arch1-1        | 1         | 0.75%   |
| 5.6.6-arch1-1        | 1         | 0.75%   |
| 5.6.2-arch1-2        | 1         | 0.75%   |
| 5.6.13-arch1-1       | 1         | 0.75%   |
| 5.6.10-arch1-1       | 1         | 0.75%   |
| 5.5.5-arch1-1        | 1         | 0.75%   |
| 5.5.11-arch1-1       | 1         | 0.75%   |
| 5.4.8-arch1-1        | 1         | 0.75%   |
| 5.4.78-1-lts         | 1         | 0.75%   |
| 5.4.77-1-lts         | 1         | 0.75%   |
| 5.4.72-1-lts         | 1         | 0.75%   |
| 5.4.6-arch3-1        | 1         | 0.75%   |
| 5.3.7-arch1-2-ARCH   | 1         | 0.75%   |
| 5.3.5-arch1-1-ARCH   | 1         | 0.75%   |
| 5.3.11-arch1-1       | 1         | 0.75%   |
| 5.3.1-arch1-1-ARCH   | 1         | 0.75%   |
| 5.16.0-zen1-1-zen    | 1         | 0.75%   |
| 5.15.7-arch1-1       | 1         | 0.75%   |
| 5.15.6-arch2-1       | 1         | 0.75%   |
| 5.15.21-1-lts        | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 8         | 6.02%   |
| 5.9.10  | 4         | 3.01%   |
| 5.9.1   | 4         | 3.01%   |
| 5.7.12  | 4         | 3.01%   |
| 5.5.9   | 4         | 3.01%   |
| 5.10.3  | 4         | 3.01%   |
| 5.8.5   | 3         | 2.26%   |
| 5.5.2   | 3         | 2.26%   |
| 5.4.10  | 3         | 2.26%   |
| 5.9.2   | 2         | 1.5%    |
| 5.9.13  | 2         | 1.5%    |
| 5.9.11  | 2         | 1.5%    |
| 5.8.7   | 2         | 1.5%    |
| 5.7.6   | 2         | 1.5%    |
| 5.7.11  | 2         | 1.5%    |
| 5.7.10  | 2         | 1.5%    |
| 5.6.4   | 2         | 1.5%    |
| 5.6.3   | 2         | 1.5%    |
| 5.2.9   | 2         | 1.5%    |
| 5.16.9  | 2         | 1.5%    |
| 5.16.12 | 2         | 1.5%    |
| 5.14.16 | 2         | 1.5%    |
| 5.11.7  | 2         | 1.5%    |
| 5.11.6  | 2         | 1.5%    |
| 5.11.11 | 2         | 1.5%    |
| 5.11.1  | 2         | 1.5%    |
| 5.10.4  | 2         | 1.5%    |
| 5.10.13 | 2         | 1.5%    |
| 5.9.6   | 1         | 0.75%   |
| 5.9.3   | 1         | 0.75%   |
| 5.9.12  | 1         | 0.75%   |
| 5.8.8   | 1         | 0.75%   |
| 5.8.6   | 1         | 0.75%   |
| 5.8.14  | 1         | 0.75%   |
| 5.8.13  | 1         | 0.75%   |
| 5.8.12  | 1         | 0.75%   |
| 5.8.1   | 1         | 0.75%   |
| 5.7.8   | 1         | 0.75%   |
| 5.7.5   | 1         | 0.75%   |
| 5.6.6   | 1         | 0.75%   |
| 5.6.2   | 1         | 0.75%   |
| 5.6.13  | 1         | 0.75%   |
| 5.6.10  | 1         | 0.75%   |
| 5.5.5   | 1         | 0.75%   |
| 5.5.11  | 1         | 0.75%   |
| 5.4.8   | 1         | 0.75%   |
| 5.4.78  | 1         | 0.75%   |
| 5.4.77  | 1         | 0.75%   |
| 5.4.72  | 1         | 0.75%   |
| 5.4.6   | 1         | 0.75%   |
| 5.3.7   | 1         | 0.75%   |
| 5.3.5   | 1         | 0.75%   |
| 5.3.11  | 1         | 0.75%   |
| 5.3.1   | 1         | 0.75%   |
| 5.16.0  | 1         | 0.75%   |
| 5.15.7  | 1         | 0.75%   |
| 5.15.6  | 1         | 0.75%   |
| 5.15.21 | 1         | 0.75%   |
| 5.14.7  | 1         | 0.75%   |
| 5.14.15 | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9     | 25        | 19.08%  |
| 5.10    | 16        | 12.21%  |
| 5.7     | 12        | 9.16%   |
| 5.8     | 11        | 8.4%    |
| 5.11    | 11        | 8.4%    |
| 5.5     | 9         | 6.87%   |
| 5.6     | 8         | 6.11%   |
| 5.4     | 8         | 6.11%   |
| 5.16    | 5         | 3.82%   |
| 5.14    | 5         | 3.82%   |
| 5.3     | 4         | 3.05%   |
| 5.12    | 4         | 3.05%   |
| 4.19    | 4         | 3.05%   |
| 5.15    | 3         | 2.29%   |
| 5.2     | 2         | 1.53%   |
| 5.13    | 2         | 1.53%   |
| 4.20    | 1         | 0.76%   |
| 4.18    | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 126       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 29        | 22.83%  |
| KDE               | 17        | 13.39%  |
| X-Cinnamon        | 16        | 12.6%   |
| Deepin            | 16        | 12.6%   |
| XFCE              | 14        | 11.02%  |
| Unknown           | 10        | 7.87%   |
| KDE5              | 7         | 5.51%   |
| Budgie            | 5         | 3.94%   |
| LXQt              | 4         | 3.15%   |
| MATE              | 3         | 2.36%   |
| i3                | 3         | 2.36%   |
| Yaru:ubuntu:GNOME | 1         | 0.79%   |
| Enlightenment     | 1         | 0.79%   |
| Cinnamon          | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 83.46%  |
| Wayland | 21        | 16.54%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 85.04%  |
| LightDM | 7         | 5.51%   |
| TDM     | 6         | 4.72%   |
| GDM     | 3         | 2.36%   |
| SDDM    | 2         | 1.57%   |
| XDM     | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 43        | 34.13%  |
| Unknown | 11        | 8.73%   |
| pt_BR   | 9         | 7.14%   |
| de_DE   | 9         | 7.14%   |
| en_AU   | 8         | 6.35%   |
| es_ES   | 7         | 5.56%   |
| en_GB   | 7         | 5.56%   |
| ru_RU   | 5         | 3.97%   |
| en_CA   | 4         | 3.17%   |
| es_MX   | 3         | 2.38%   |
| pl_PL   | 2         | 1.59%   |
| nl_NL   | 2         | 1.59%   |
| es_AR   | 2         | 1.59%   |
| sv_SE   | 1         | 0.79%   |
| ru_UA   | 1         | 0.79%   |
| pt_PT   | 1         | 0.79%   |
| fr_FR   | 1         | 0.79%   |
| fr_BE   | 1         | 0.79%   |
| fi_FI   | 1         | 0.79%   |
| es_PA   | 1         | 0.79%   |
| es_CL   | 1         | 0.79%   |
| en_PH   | 1         | 0.79%   |
| en_DK   | 1         | 0.79%   |
| el_GR   | 1         | 0.79%   |
| de_CH   | 1         | 0.79%   |
| de_AT   | 1         | 0.79%   |
| cs_CZ   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 89        | 70.08%  |
| EFI  | 38        | 29.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 77.95%  |
| Unknown | 11        | 8.66%   |
| Tmpfs   | 9         | 7.09%   |
| Btrfs   | 4         | 3.15%   |
| Xfs     | 3         | 2.36%   |
| Ext3    | 1         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 85.71%  |
| GPT     | 14        | 11.11%  |
| MBR     | 4         | 3.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 95.24%  |
| Yes       | 6         | 4.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 92.91%  |
| Yes       | 9         | 7.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 20.63%  |
| ASUSTek Computer       | 22        | 17.46%  |
| Dell                   | 20        | 15.87%  |
| Hewlett-Packard        | 11        | 8.73%   |
| Gigabyte Technology    | 9         | 7.14%   |
| Acer                   | 9         | 7.14%   |
| ASRock                 | 7         | 5.56%   |
| MSI                    | 6         | 4.76%   |
| Avell High Performance | 2         | 1.59%   |
| Toshiba                | 1         | 0.79%   |
| Sony                   | 1         | 0.79%   |
| Shuttle                | 1         | 0.79%   |
| Razer                  | 1         | 0.79%   |
| Pegatron               | 1         | 0.79%   |
| OEM                    | 1         | 0.79%   |
| Microsoft              | 1         | 0.79%   |
| Medion                 | 1         | 0.79%   |
| Intel                  | 1         | 0.79%   |
| HUAWEI                 | 1         | 0.79%   |
| Huanan                 | 1         | 0.79%   |
| Foxconn                | 1         | 0.79%   |
| Digma                  | 1         | 0.79%   |
| CyberPowerPC           | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 2.38%   |
| Dell Inspiron 5520                     | 3         | 2.38%   |
| MSI MS-7721                            | 2         | 1.59%   |
| Dell Latitude E6430                    | 2         | 1.59%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 1.59%   |
| ASRock X570 Phantom Gaming 4           | 2         | 1.59%   |
| Toshiba Satellite C850-C1S             | 1         | 0.79%   |
| Sony VPCEH10EB                         | 1         | 0.79%   |
| Shuttle SZ270                          | 1         | 0.79%   |
| Razer Blade                            | 1         | 0.79%   |
| Pegatron CQ3476L                       | 1         | 0.79%   |
| OEM G41 775 ICH7 8712                  | 1         | 0.79%   |
| MSI WK711AA-ACB HPE-110ru              | 1         | 0.79%   |
| MSI MS-7C35                            | 1         | 0.79%   |
| MSI MS-7A36                            | 1         | 0.79%   |
| MSI MS-7998                            | 1         | 0.79%   |
| Microsoft Surface Pro 4                | 1         | 0.79%   |
| Medion P961x                           | 1         | 0.79%   |
| Lenovo Z70-80 80FG                     | 1         | 0.79%   |
| Lenovo Yoga Book C930 ZA3S             | 1         | 0.79%   |
| Lenovo Y50-70 20378                    | 1         | 0.79%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 0.79%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 0.79%   |
| Lenovo ThinkPad T410 253725G           | 1         | 0.79%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 0.79%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 0.79%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 0.79%   |
| Lenovo ThinkPad 10 20C10026UK          | 1         | 0.79%   |
| Lenovo ThinkCentre M92 32071F5         | 1         | 0.79%   |
| Lenovo ThinkCentre M91p 0266RZ1        | 1         | 0.79%   |
| Lenovo ThinkCentre M75q-1 11A4001WUS   | 1         | 0.79%   |
| Lenovo ThinkCentre M58 6258WCY         | 1         | 0.79%   |
| Lenovo IdeaPad Y580                    | 1         | 0.79%   |
| Lenovo IdeaPad Y450                    | 1         | 0.79%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 0.79%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 0.79%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 0.79%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 0.79%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 0.79%   |
| Lenovo G570 20079                      | 1         | 0.79%   |
| Lenovo G470 20078                      | 1         | 0.79%   |
| Intel DH55HC AAE70933-501              | 1         | 0.79%   |
| HUAWEI MRC-WX0                         | 1         | 0.79%   |
| Huanan X79-8D VAA31                    | 1         | 0.79%   |
| HP ProBook 6550b                       | 1         | 0.79%   |
| HP ProBook 640 G5                      | 1         | 0.79%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 0.79%   |
| HP Pavilion g7                         | 1         | 0.79%   |
| HP Pavilion dm1                        | 1         | 0.79%   |
| HP Pavilion Desktop PC 570-p0XX        | 1         | 0.79%   |
| HP Pavilion 17                         | 1         | 0.79%   |
| HP ENVY x360 m6 Convertible            | 1         | 0.79%   |
| HP EliteBook 8460p                     | 1         | 0.79%   |
| HP EliteBook 2560p                     | 1         | 0.79%   |
| HP Compaq 6000 Pro MT PC               | 1         | 0.79%   |
| Gigabyte Z87-HD3                       | 1         | 0.79%   |
| Gigabyte X570 AORUS ELITE              | 1         | 0.79%   |
| Gigabyte H61M-DS2                      | 1         | 0.79%   |
| Gigabyte H110M-S2PT-CF                 | 1         | 0.79%   |
| Gigabyte GA-880GM-UD2H                 | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 10        | 7.94%   |
| Lenovo ThinkPad              | 7         | 5.56%   |
| Acer Aspire                  | 7         | 5.56%   |
| Dell Inspiron                | 6         | 4.76%   |
| HP Pavilion                  | 5         | 3.97%   |
| Dell OptiPlex                | 5         | 3.97%   |
| Dell Latitude                | 5         | 3.97%   |
| ASUS PRIME                   | 5         | 3.97%   |
| Lenovo ThinkCentre           | 4         | 3.17%   |
| ASUS ROG                     | 3         | 2.38%   |
| ASRock X570                  | 3         | 2.38%   |
| MSI MS-7721                  | 2         | 1.59%   |
| HP ProBook                   | 2         | 1.59%   |
| HP EliteBook                 | 2         | 1.59%   |
| ASUS VivoBook                | 2         | 1.59%   |
| Toshiba Satellite            | 1         | 0.79%   |
| Sony VPCEH10EB               | 1         | 0.79%   |
| Shuttle SZ270                | 1         | 0.79%   |
| Razer Blade                  | 1         | 0.79%   |
| Pegatron CQ3476L             | 1         | 0.79%   |
| OEM G41                      | 1         | 0.79%   |
| MSI WK711AA-ACB              | 1         | 0.79%   |
| MSI MS-7C35                  | 1         | 0.79%   |
| MSI MS-7A36                  | 1         | 0.79%   |
| MSI MS-7998                  | 1         | 0.79%   |
| Microsoft Surface            | 1         | 0.79%   |
| Medion P961x                 | 1         | 0.79%   |
| Lenovo Z70-80                | 1         | 0.79%   |
| Lenovo Yoga                  | 1         | 0.79%   |
| Lenovo Y50-70                | 1         | 0.79%   |
| Lenovo G570                  | 1         | 0.79%   |
| Lenovo G470                  | 1         | 0.79%   |
| Intel DH55HC                 | 1         | 0.79%   |
| HUAWEI MRC-WX0               | 1         | 0.79%   |
| Huanan X79-8D                | 1         | 0.79%   |
| HP ENVY                      | 1         | 0.79%   |
| HP Compaq                    | 1         | 0.79%   |
| Gigabyte Z87-HD3             | 1         | 0.79%   |
| Gigabyte X570                | 1         | 0.79%   |
| Gigabyte H61M-DS2            | 1         | 0.79%   |
| Gigabyte H110M-S2PT-CF       | 1         | 0.79%   |
| Gigabyte GA-880GM-UD2H       | 1         | 0.79%   |
| Gigabyte F2A85X-UP4          | 1         | 0.79%   |
| Gigabyte F2A75-D3H           | 1         | 0.79%   |
| Gigabyte EP43-UD3L           | 1         | 0.79%   |
| Gigabyte B450                | 1         | 0.79%   |
| Foxconn H61S                 | 1         | 0.79%   |
| Digma EVE                    | 1         | 0.79%   |
| Dell XPS                     | 1         | 0.79%   |
| Dell Studio                  | 1         | 0.79%   |
| Dell Precision               | 1         | 0.79%   |
| Dell G7                      | 1         | 0.79%   |
| CyberPowerPC Tracer          | 1         | 0.79%   |
| Avell High Performance G1550 | 1         | 0.79%   |
| Avell High Performance A62   | 1         | 0.79%   |
| ASUS Z8NA-D6                 | 1         | 0.79%   |
| ASUS X555YI                  | 1         | 0.79%   |
| ASUS X540SA                  | 1         | 0.79%   |
| ASUS UX430UAR                | 1         | 0.79%   |
| ASUS STRIX                   | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 18        | 14.29%  |
| 2012 | 16        | 12.7%   |
| 2018 | 12        | 9.52%   |
| 2013 | 12        | 9.52%   |
| 2011 | 11        | 8.73%   |
| 2016 | 10        | 7.94%   |
| 2009 | 10        | 7.94%   |
| 2020 | 9         | 7.14%   |
| 2010 | 8         | 6.35%   |
| 2014 | 7         | 5.56%   |
| 2017 | 5         | 3.97%   |
| 2015 | 5         | 3.97%   |
| 2008 | 2         | 1.59%   |
| 2021 | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 61        | 48.41%  |
| Desktop     | 58        | 46.03%  |
| Tablet      | 3         | 2.38%   |
| Convertible | 2         | 1.59%   |
| Mini pc     | 1         | 0.79%   |
| All in one  | 1         | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 126       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 126       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 32.03%  |
| 8.01-16.0   | 28        | 21.88%  |
| 16.01-24.0  | 24        | 18.75%  |
| 3.01-4.0    | 19        | 14.84%  |
| 32.01-64.0  | 13        | 10.16%  |
| 2.01-3.0    | 1         | 0.78%   |
| 64.01-256.0 | 1         | 0.78%   |
| 1.01-2.0    | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 43.94%  |
| 2.01-3.0  | 41        | 31.06%  |
| 3.01-4.0  | 13        | 9.85%   |
| 4.01-8.0  | 11        | 8.33%   |
| 0.51-1.0  | 6         | 4.55%   |
| 8.01-16.0 | 3         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 55.04%  |
| 2      | 36        | 27.91%  |
| 3      | 9         | 6.98%   |
| 4      | 8         | 6.2%    |
| 0      | 2         | 1.55%   |
| 7      | 1         | 0.78%   |
| 6      | 1         | 0.78%   |
| 5      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 53.54%  |
| Yes       | 59        | 46.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 84.92%  |
| No        | 19        | 15.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 77.78%  |
| No        | 28        | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 54.76%  |
| No        | 57        | 45.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 31        | 24.6%   |
| Germany     | 11        | 8.73%   |
| Brazil      | 10        | 7.94%   |
| Spain       | 8         | 6.35%   |
| Canada      | 7         | 5.56%   |
| UK          | 6         | 4.76%   |
| Russia      | 6         | 4.76%   |
| Australia   | 6         | 4.76%   |
| Netherlands | 5         | 3.97%   |
| Mexico      | 3         | 2.38%   |
| Turkey      | 2         | 1.59%   |
| Thailand    | 2         | 1.59%   |
| Portugal    | 2         | 1.59%   |
| Poland      | 2         | 1.59%   |
| Panama      | 2         | 1.59%   |
| India       | 2         | 1.59%   |
| Greece      | 2         | 1.59%   |
| Estonia     | 2         | 1.59%   |
| Argentina   | 2         | 1.59%   |
| Ukraine     | 1         | 0.79%   |
| Switzerland | 1         | 0.79%   |
| Sweden      | 1         | 0.79%   |
| Philippines | 1         | 0.79%   |
| Hungary     | 1         | 0.79%   |
| Finland     | 1         | 0.79%   |
| Egypt       | 1         | 0.79%   |
| Czechia     | 1         | 0.79%   |
| Costa Rica  | 1         | 0.79%   |
| Colombia    | 1         | 0.79%   |
| Chile       | 1         | 0.79%   |
| Benin       | 1         | 0.79%   |
| Belgium     | 1         | 0.79%   |
| Azerbaijan  | 1         | 0.79%   |
| Austria     | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Melbourne      | 3         | 2.31%   |
| Aleksandrov    | 3         | 2.31%   |
| Tres Cantos    | 2         | 1.54%   |
| Toronto        | 2         | 1.54%   |
| Tallinn        | 2         | 1.54%   |
| Sao Paulo      | 2         | 1.54%   |
| Santa Clara    | 2         | 1.54%   |
| Miami          | 2         | 1.54%   |
| Lelystad       | 2         | 1.54%   |
| Cologne        | 2         | 1.54%   |
| Buffalo        | 2         | 1.54%   |
| Athens         | 2         | 1.54%   |
| Zutphen        | 1         | 0.77%   |
| Zabrze         | 1         | 0.77%   |
| Yadrin         | 1         | 0.77%   |
| Wuppertal      | 1         | 0.77%   |
| Winsted        | 1         | 0.77%   |
| Watford        | 1         | 0.77%   |
| Warsaw         | 1         | 0.77%   |
| Villahermosa   | 1         | 0.77%   |
| Verwood        | 1         | 0.77%   |
| Toledo         | 1         | 0.77%   |
| The Hague      | 1         | 0.77%   |
| Szeksz??rd     | 1         | 0.77%   |
| Sydney         | 1         | 0.77%   |
| Surrey         | 1         | 0.77%   |
| Stuttgart      | 1         | 0.77%   |
| Streatham      | 1         | 0.77%   |
| Spremberg      | 1         | 0.77%   |
| Southampton    | 1         | 0.77%   |
| Smithfield     | 1         | 0.77%   |
| Si Racha       | 1         | 0.77%   |
| Seville        | 1         | 0.77%   |
| Santiago       | 1         | 0.77%   |
| Salt Lake City | 1         | 0.77%   |
| Roebel         | 1         | 0.77%   |
| Reno           | 1         | 0.77%   |
| Quezon City    | 1         | 0.77%   |
| Queens         | 1         | 0.77%   |
| Purdon         | 1         | 0.77%   |
| Potts Camp     | 1         | 0.77%   |
| Portsmouth     | 1         | 0.77%   |
| Porto Uniao    | 1         | 0.77%   |
| Pont-y-clun    | 1         | 0.77%   |
| Phoenix        | 1         | 0.77%   |
| Perth          | 1         | 0.77%   |
| Orem           | 1         | 0.77%   |
| Novosibirsk    | 1         | 0.77%   |
| North Bay      | 1         | 0.77%   |
| Nijmegen       | 1         | 0.77%   |
| Newport News   | 1         | 0.77%   |
| Newcastle      | 1         | 0.77%   |
| New Orleans    | 1         | 0.77%   |
| New Delhi      | 1         | 0.77%   |
| Mogi Mirim     | 1         | 0.77%   |
| Mexico City    | 1         | 0.77%   |
| Mascouche      | 1         | 0.77%   |
| Madrid         | 1         | 0.77%   |
| Littleton      | 1         | 0.77%   |
| Limeira        | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 45     | 19.8%   |
| Samsung Electronics | 28        | 34     | 14.21%  |
| Seagate             | 27        | 35     | 13.71%  |
| Toshiba             | 16        | 18     | 8.12%   |
| Unknown             | 10        | 12     | 5.08%   |
| Kingston            | 8         | 9      | 4.06%   |
| Crucial             | 8         | 9      | 4.06%   |
| SanDisk             | 7         | 9      | 3.55%   |
| Hitachi             | 7         | 7      | 3.55%   |
| Phison              | 6         | 7      | 3.05%   |
| Intel               | 5         | 5      | 2.54%   |
| HGST                | 4         | 4      | 2.03%   |
| ZOTAC               | 2         | 2      | 1.02%   |
| SPCC                | 2         | 3      | 1.02%   |
| SK hynix            | 2         | 2      | 1.02%   |
| PNY                 | 2         | 2      | 1.02%   |
| Patriot             | 2         | 2      | 1.02%   |
| EMTEC               | 2         | 3      | 1.02%   |
| Dell                | 2         | 2      | 1.02%   |
| XPG                 | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Phison Electronics  | 1         | 2      | 0.51%   |
| OYUNKEY             | 1         | 1      | 0.51%   |
| OCZ                 | 1         | 2      | 0.51%   |
| Micron Technology   | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| JMicron Technology  | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 2      | 0.51%   |
| Gigabyte Technology | 1         | 2      | 0.51%   |
| Drevo               | 1         | 1      | 0.51%   |
| ASMT                | 1         | 1      | 0.51%   |
| AMD                 | 1         | 1      | 0.51%   |
| addlink             | 1         | 1      | 0.51%   |
| ADATA Technology    | 1         | 1      | 0.51%   |
| A-DATA Technology   | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                 | 5         | 2.33%   |
| Samsung SSD 860 EVO 500GB              | 4         | 1.86%   |
| Intel NVMe SSD Drive 512GB             | 4         | 1.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 1.4%    |
| WDC WD10JPVT-08A1YT2 1TB               | 2         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.93%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 0.93%   |
| WDC WD1001FALS-403AA0 1TB              | 2         | 0.93%   |
| Unknown SD/MMC/MS PRO 128GB            | 2         | 0.93%   |
| Toshiba NVMe SSD Drive 512GB           | 2         | 0.93%   |
| Toshiba DT01ACA100 1TB                 | 2         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB          | 2         | 0.93%   |
| Seagate ST9500325AS 500GB              | 2         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.93%   |
| Seagate ST3500312CS 500GB              | 2         | 0.93%   |
| Seagate ST2000DM006-2DM164 2TB         | 2         | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB         | 2         | 0.93%   |
| Samsung SSD 850 EVO 500GB              | 2         | 0.93%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.93%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2         | 0.93%   |
| Samsung NVMe SSD Drive 512GB           | 2         | 0.93%   |
| PNY CS900 120GB SSD                    | 2         | 0.93%   |
| Phison NVMe SSD Drive 960GB            | 2         | 0.93%   |
| Phison NVMe SSD Drive 240GB            | 2         | 0.93%   |
| Phison NVMe SSD Drive 1TB              | 2         | 0.93%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.93%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.93%   |
| ZOTAC ZTSSD-S11-120G-P 120GB           | 1         | 0.47%   |
| ZOTAC ZTSSD-A4P-120G                   | 1         | 0.47%   |
| XPG NVMe SSD Drive 1TB                 | 1         | 0.47%   |
| WDC WDS500G2X0C-00L350 500GB           | 1         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.47%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.47%   |
| WDC WD7500LPCX-60HWST0 752GB           | 1         | 0.47%   |
| WDC WD6400AAKS-22A7B0 640GB            | 1         | 0.47%   |
| WDC WD6400AAKS-00A7B2 640GB            | 1         | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.47%   |
| WDC WD5000LPVX-00V0TT0 500GB           | 1         | 0.47%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.47%   |
| WDC WD5000AZLX-00JKKA0 500GB           | 1         | 0.47%   |
| WDC WD5000AVDS-63U7B1 500GB            | 1         | 0.47%   |
| WDC WD5000AAKX-753CA1 500GB            | 1         | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB            | 1         | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 1         | 0.47%   |
| WDC WD3200AAKS-00UU3A0 320GB           | 1         | 0.47%   |
| WDC WD30PURX-64P6ZY0 3TB               | 1         | 0.47%   |
| WDC WD2500JS-00MHB0 250GB              | 1         | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB               | 1         | 0.47%   |
| WDC WD20EURX-63T0FY0 2TB               | 1         | 0.47%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 1         | 0.47%   |
| WDC WD2003FYPS-27Y2B0 2TB              | 1         | 0.47%   |
| WDC WD15EADS-65P8B1 1TB                | 1         | 0.47%   |
| WDC WD10SPZX-22Z10T0 1TB               | 1         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.47%   |
| WDC WD10EZRX-00L4HB0 1TB               | 1         | 0.47%   |
| WDC WD10EZEX-22MFCA0 1TB               | 1         | 0.47%   |
| WDC WD10EZEX-21WN4A0 1TB               | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 39     | 39.08%  |
| Seagate             | 27        | 35     | 31.03%  |
| Toshiba             | 9         | 10     | 10.34%  |
| Hitachi             | 7         | 7      | 8.05%   |
| HGST                | 4         | 4      | 4.6%    |
| Samsung Electronics | 3         | 3      | 3.45%   |
| Unknown             | 2         | 2      | 2.3%    |
| ASMT                | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 30.16%  |
| Kingston            | 8         | 9      | 12.7%   |
| Crucial             | 7         | 8      | 11.11%  |
| SanDisk             | 6         | 8      | 9.52%   |
| WDC                 | 3         | 3      | 4.76%   |
| ZOTAC               | 2         | 2      | 3.17%   |
| Toshiba             | 2         | 2      | 3.17%   |
| PNY                 | 2         | 2      | 3.17%   |
| Patriot             | 2         | 2      | 3.17%   |
| Transcend           | 1         | 1      | 1.59%   |
| SPCC                | 1         | 2      | 1.59%   |
| OCZ                 | 1         | 2      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| JMicron Technology  | 1         | 1      | 1.59%   |
| Hewlett-Packard     | 1         | 2      | 1.59%   |
| Gigabyte Technology | 1         | 2      | 1.59%   |
| EMTEC               | 1         | 1      | 1.59%   |
| Drevo               | 1         | 1      | 1.59%   |
| AMD                 | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 71        | 101    | 41.76%  |
| SSD     | 53        | 74     | 31.18%  |
| NVMe    | 34        | 41     | 20%     |
| MMC     | 7         | 10     | 4.12%   |
| Unknown | 5         | 6      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 170    | 67.76%  |
| NVMe | 34        | 41     | 22.37%  |
| SAS  | 8         | 11     | 5.26%   |
| MMC  | 7         | 10     | 4.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 99     | 54.74%  |
| 0.51-1.0   | 49        | 58     | 35.77%  |
| 1.01-2.0   | 8         | 11     | 5.84%   |
| 2.01-3.0   | 3         | 4      | 2.19%   |
| 3.01-4.0   | 2         | 3      | 1.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 38        | 29.23%  |
| 101-250        | 29        | 22.31%  |
| 501-1000       | 27        | 20.77%  |
| 51-100         | 12        | 9.23%   |
| 1001-2000      | 7         | 5.38%   |
| More than 3000 | 6         | 4.62%   |
| Unknown        | 6         | 4.62%   |
| 2001-3000      | 3         | 2.31%   |
| 21-50          | 2         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 47        | 35.34%  |
| 21-50     | 34        | 25.56%  |
| 101-250   | 15        | 11.28%  |
| 51-100    | 13        | 9.77%   |
| 251-500   | 8         | 6.02%   |
| 501-1000  | 6         | 4.51%   |
| Unknown   | 6         | 4.51%   |
| 2001-3000 | 3         | 2.26%   |
| 1001-2000 | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 113       | 197    | 88.28%  |
| Works    | 15        | 35     | 11.72%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 87        | 56.13%  |
| AMD                          | 31        | 20%     |
| Samsung Electronics          | 9         | 5.81%   |
| Phison Electronics           | 8         | 5.16%   |
| Toshiba America Info Systems | 5         | 3.23%   |
| SanDisk                      | 3         | 1.94%   |
| JMicron Technology           | 3         | 1.94%   |
| ADATA Technology             | 3         | 1.94%   |
| SK hynix                     | 2         | 1.29%   |
| Nvidia                       | 1         | 0.65%   |
| Micron/Crucial Technology    | 1         | 0.65%   |
| Micron Technology            | 1         | 0.65%   |
| ASMedia Technology           | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 14.75%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 3.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 3.28%   |
| Phison E12 NVMe Controller                                                              | 5         | 2.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 2.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 2.73%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 2.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 2.19%   |
| Intel SSD 660P Series                                                                   | 3         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.64%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.64%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.09%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.09%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.09%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 1.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.55%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.55%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.55%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.55%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.55%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.55%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.55%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.55%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.55%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.55%   |
| Intel SSD 600P Series                                                                   | 1         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.55%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 62.18%  |
| NVMe | 33        | 21.15%  |
| IDE  | 19        | 12.18%  |
| RAID | 7         | 4.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 73.02%  |
| AMD    | 34        | 26.98%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 3.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.36%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.57%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 2         | 1.57%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.57%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.57%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.57%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 1.57%   |
| AMD A4-5300 APU with Radeon HD Graphics       | 2         | 1.57%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2         | 1.57%   |
| Intel Xeon CPU E5530 @ 2.40GHz                | 1         | 0.79%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 1         | 0.79%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz           | 1         | 0.79%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz           | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.79%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.79%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.79%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.79%   |
| Intel Pentium CPU G3258 @ 3.20GHz             | 1         | 0.79%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.79%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.79%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 1         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.79%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.79%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.79%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.79%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.79%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.79%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.79%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 0.79%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.79%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 0.79%   |
| Intel Core i5-4570T CPU @ 2.90GHz             | 1         | 0.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.79%   |
| Intel Core i5-3340 CPU @ 3.10GHz              | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 27.56%  |
| Intel Core i7           | 24        | 18.9%   |
| AMD Ryzen 5             | 10        | 7.87%   |
| Intel Core 2 Duo        | 8         | 6.3%    |
| Intel Core i3           | 7         | 5.51%   |
| Intel Celeron           | 7         | 5.51%   |
| AMD Ryzen 7             | 7         | 5.51%   |
| Intel Xeon              | 4         | 3.15%   |
| Intel Pentium           | 4         | 3.15%   |
| AMD FX                  | 3         | 2.36%   |
| Intel Pentium Dual-Core | 2         | 1.57%   |
| AMD Ryzen 3             | 2         | 1.57%   |
| AMD A8                  | 2         | 1.57%   |
| AMD A4                  | 2         | 1.57%   |
| AMD A10                 | 2         | 1.57%   |
| Other                   | 1         | 0.79%   |
| Intel Core m3           | 1         | 0.79%   |
| Intel Atom              | 1         | 0.79%   |
| AMD Ryzen 9             | 1         | 0.79%   |
| AMD Ryzen 5 PRO         | 1         | 0.79%   |
| AMD Phenom II X4        | 1         | 0.79%   |
| AMD E                   | 1         | 0.79%   |
| AMD Athlon II X2        | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 43.65%  |
| 4      | 47        | 37.3%   |
| 6      | 13        | 10.32%  |
| 8      | 6         | 4.76%   |
| 1      | 2         | 1.59%   |
| 24     | 1         | 0.79%   |
| 12     | 1         | 0.79%   |
| 3      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 98.41%  |
| 2      | 2         | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 66.67%  |
| 1      | 42        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 92.06%  |
| Unknown        | 10        | 7.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 28.13%  |
| 0x306a9    | 11        | 8.59%   |
| 0x206a7    | 9         | 7.03%   |
| 0x306c3    | 7         | 5.47%   |
| 0x506e3    | 5         | 3.91%   |
| 0x906ea    | 4         | 3.13%   |
| 0x1067a    | 4         | 3.13%   |
| 0x0800820d | 4         | 3.13%   |
| 0x06001119 | 4         | 3.13%   |
| 0x906e9    | 3         | 2.34%   |
| 0x806e9    | 3         | 2.34%   |
| 0x20652    | 3         | 2.34%   |
| 0x806ec    | 2         | 1.56%   |
| 0x806eb    | 2         | 1.56%   |
| 0x40651    | 2         | 1.56%   |
| 0x20655    | 2         | 1.56%   |
| 0x106e5    | 2         | 1.56%   |
| 0x08108109 | 2         | 1.56%   |
| 0x806ea    | 1         | 0.78%   |
| 0x6fb      | 1         | 0.78%   |
| 0x406e3    | 1         | 0.78%   |
| 0x406c3    | 1         | 0.78%   |
| 0x306e4    | 1         | 0.78%   |
| 0x306d4    | 1         | 0.78%   |
| 0x30678    | 1         | 0.78%   |
| 0x106a5    | 1         | 0.78%   |
| 0x10676    | 1         | 0.78%   |
| 0x0a201016 | 1         | 0.78%   |
| 0x0a201009 | 1         | 0.78%   |
| 0x08701021 | 1         | 0.78%   |
| 0x08600102 | 1         | 0.78%   |
| 0x0810100b | 1         | 0.78%   |
| 0x08001138 | 1         | 0.78%   |
| 0x07030106 | 1         | 0.78%   |
| 0x06006704 | 1         | 0.78%   |
| 0x06006113 | 1         | 0.78%   |
| 0x0600081c | 1         | 0.78%   |
| 0x06000817 | 1         | 0.78%   |
| 0x05000119 | 1         | 0.78%   |
| 0x010000c8 | 1         | 0.78%   |
| 0x010000b6 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 15.08%  |
| IvyBridge     | 15        | 11.9%   |
| SandyBridge   | 13        | 10.32%  |
| Zen+          | 11        | 8.73%   |
| Haswell       | 11        | 8.73%   |
| Penryn        | 8         | 6.35%   |
| Skylake       | 7         | 5.56%   |
| Westmere      | 6         | 4.76%   |
| Piledriver    | 6         | 4.76%   |
| Zen 2         | 5         | 3.97%   |
| Zen           | 3         | 2.38%   |
| Silvermont    | 3         | 2.38%   |
| Nehalem       | 3         | 2.38%   |
| Goldmont plus | 3         | 2.38%   |
| Zen 3         | 2         | 1.59%   |
| Puma          | 2         | 1.59%   |
| K10           | 2         | 1.59%   |
| Excavator     | 2         | 1.59%   |
| Goldmont      | 1         | 0.79%   |
| Core          | 1         | 0.79%   |
| CometLake     | 1         | 0.79%   |
| Broadwell     | 1         | 0.79%   |
| Bobcat        | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 66        | 45.21%  |
| Nvidia            | 41        | 28.08%  |
| AMD               | 38        | 26.03%  |
| ASPEED Technology | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 7.95%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 5.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 3.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 2.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 2.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.99%   |
| Nvidia GF108 [GeForce GT 730]                                               | 3         | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.99%   |
| Intel UHD Graphics 620                                                      | 3         | 1.99%   |
| Intel HD Graphics 530                                                       | 3         | 1.99%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.99%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                   | 3         | 1.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.32%   |
| Intel HD Graphics 620                                                       | 2         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.32%   |
| AMD Trinity [Radeon HD 7660D]                                               | 2         | 1.32%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.32%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2         | 1.32%   |
| Nvidia TU117M                                                               | 1         | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.66%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 0.66%   |
| Nvidia GT218M [NVS 3100M]                                                   | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.66%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.66%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 1         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.66%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.66%   |
| Nvidia GM206M [GeForce GTX 965M]                                            | 1         | 0.66%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1         | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.66%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.66%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.66%   |
| Nvidia GK208M [GeForce GT 730M]                                             | 1         | 0.66%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.66%   |
| Nvidia GK104GL [Tesla K10]                                                  | 1         | 0.66%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.66%   |
| Nvidia GF108GLM [Quadro 1000M]                                              | 1         | 0.66%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 0.66%   |
| Nvidia GF108 [GeForce GT 420]                                               | 1         | 0.66%   |
| Nvidia G96CM [GeForce GT 130M]                                              | 1         | 0.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.66%   |
| Intel HD Graphics P530                                                      | 1         | 0.66%   |
| Intel HD Graphics 630                                                       | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 36.51%  |
| 1 x AMD        | 31        | 24.6%   |
| 1 x Nvidia     | 28        | 22.22%  |
| Intel + Nvidia | 12        | 9.52%   |
| Intel + AMD    | 5         | 3.97%   |
| 2 x AMD        | 2         | 1.59%   |
| 3 x Nvidia     | 1         | 0.79%   |
| 1 x ASPEED     | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 109       | 85.83%  |
| Proprietary | 17        | 13.39%  |
| Unknown     | 1         | 0.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 57.14%  |
| 0.51-1.0   | 13        | 10.32%  |
| 1.01-2.0   | 11        | 8.73%   |
| 0.01-0.5   | 10        | 7.94%   |
| 7.01-8.0   | 8         | 6.35%   |
| 3.01-4.0   | 6         | 4.76%   |
| 8.01-16.0  | 3         | 2.38%   |
| 2.01-3.0   | 2         | 1.59%   |
| 5.01-6.0   | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 22        | 16.3%   |
| AU Optronics            | 21        | 15.56%  |
| LG Display              | 14        | 10.37%  |
| Hewlett-Packard         | 8         | 5.93%   |
| BOE                     | 8         | 5.93%   |
| Dell                    | 7         | 5.19%   |
| Chimei Innolux          | 7         | 5.19%   |
| BenQ                    | 6         | 4.44%   |
| Goldstar                | 5         | 3.7%    |
| Acer                    | 5         | 3.7%    |
| Philips                 | 4         | 2.96%   |
| Chi Mei Optoelectronics | 4         | 2.96%   |
| AOC                     | 3         | 2.22%   |
| Ancor Communications    | 3         | 2.22%   |
| Sony                    | 2         | 1.48%   |
| MSI                     | 2         | 1.48%   |
| Vizio                   | 1         | 0.74%   |
| Vestel                  | 1         | 0.74%   |
| Unknown                 | 1         | 0.74%   |
| Sharp                   | 1         | 0.74%   |
| Sceptre Tech            | 1         | 0.74%   |
| Plain Tree Systems      | 1         | 0.74%   |
| Microstep               | 1         | 0.74%   |
| Medion                  | 1         | 0.74%   |
| Lenovo                  | 1         | 0.74%   |
| InfoVision              | 1         | 0.74%   |
| Iiyama                  | 1         | 0.74%   |
| GRM                     | 1         | 0.74%   |
| CSO                     | 1         | 0.74%   |
| ASUSTek Computer        | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 2.08%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 2.08%   |
| Samsung Electronics SA300/SA350 SAM0791 1920x1080 510x287mm 23.0-inch    | 2         | 1.39%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                   | 2         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 1.39%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 1.39%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 1         | 0.69%   |
| Vestel LCD Monitor 32W_LCD_TV                                            | 1         | 0.69%   |
| Unknown LCD Monitor DAC Moniter 5760x1080                                | 1         | 0.69%   |
| Sony TV SNYF301 1920x1080                                                | 1         | 0.69%   |
| Sony TV *30 SNY7105 3840x2160 952x535mm 43.0-inch                        | 1         | 0.69%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 0.69%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch           | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 0.69%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.69%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 0.69%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.69%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch        | 1         | 0.69%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch        | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC5744 1920x1080 344x194mm 15.5-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080                        | 1         | 0.69%   |
| Samsung Electronics LCD Monitor S24D300 1920x1080                        | 1         | 0.69%   |
| Samsung Electronics LCD Monitor S22D300 1920x1080                        | 1         | 0.69%   |
| Plain Tree Systems TFT19DXP PTS03A0 1280x1024 376x301mm 19.0-inch        | 1         | 0.69%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 1         | 0.69%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                  | 1         | 0.69%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                 | 1         | 0.69%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                                 | 1         | 0.69%   |
| Philips LCD Monitor PHL 276E8V                                           | 1         | 0.69%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                   | 1         | 0.69%   |
| MSI MPG341CQR MSI3DA0 3440x1440 797x334mm 34.0-inch                      | 1         | 0.69%   |
| Microstep LCD Monitor Optix MAG24C 3840x1200                             | 1         | 0.69%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch               | 1         | 0.69%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 0.69%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.69%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 0.69%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 0.69%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 0.69%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.69%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 0.69%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 0.69%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 0.69%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 1         | 0.69%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 0.69%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                     | 1         | 0.69%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 509x286mm 23.0-inch             | 1         | 0.69%   |
| Hewlett-Packard w2228h HWP2810 1680x1050 473x296mm 22.0-inch             | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 39.85%  |
| 1366x768 (WXGA)    | 36        | 27.07%  |
| 1600x900 (HD+)     | 8         | 6.02%   |
| 1680x1050 (WSXGA+) | 7         | 5.26%   |
| 3840x2160 (4K)     | 5         | 3.76%   |
| 1440x900 (WXGA+)   | 4         | 3.01%   |
| Unknown            | 4         | 3.01%   |
| 1280x1024 (SXGA)   | 3         | 2.26%   |
| 7680x2160          | 2         | 1.5%    |
| 3440x1440          | 2         | 1.5%    |
| 2560x1440 (QHD)    | 2         | 1.5%    |
| 1920x1200 (WUXGA)  | 2         | 1.5%    |
| 5760x1080          | 1         | 0.75%   |
| 3840x1200          | 1         | 0.75%   |
| 2736x1824          | 1         | 0.75%   |
| 2560x1600          | 1         | 0.75%   |
| 1360x768           | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 24.82%  |
| 23      | 12        | 8.76%   |
| 14      | 11        | 8.03%   |
| 21      | 10        | 7.3%    |
| Unknown | 9         | 6.57%   |
| 24      | 7         | 5.11%   |
| 17      | 7         | 5.11%   |
| 13      | 7         | 5.11%   |
| 22      | 6         | 4.38%   |
| 27      | 5         | 3.65%   |
| 19      | 5         | 3.65%   |
| 18      | 4         | 2.92%   |
| 54      | 2         | 1.46%   |
| 34      | 2         | 1.46%   |
| 31      | 2         | 1.46%   |
| 20      | 2         | 1.46%   |
| 11      | 2         | 1.46%   |
| 84      | 1         | 0.73%   |
| 72      | 1         | 0.73%   |
| 65      | 1         | 0.73%   |
| 49      | 1         | 0.73%   |
| 46      | 1         | 0.73%   |
| 33      | 1         | 0.73%   |
| 28      | 1         | 0.73%   |
| 16      | 1         | 0.73%   |
| 12      | 1         | 0.73%   |
| 10      | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 37.78%  |
| 401-500     | 24        | 17.78%  |
| 501-600     | 21        | 15.56%  |
| 351-400     | 10        | 7.41%   |
| Unknown     | 9         | 6.67%   |
| 201-300     | 6         | 4.44%   |
| 1001-1500   | 5         | 3.7%    |
| 601-700     | 4         | 2.96%   |
| 701-800     | 3         | 2.22%   |
| 1501-2000   | 2         | 1.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 99        | 77.95%  |
| 16/10   | 13        | 10.24%  |
| Unknown | 9         | 7.09%   |
| 5/4     | 3         | 2.36%   |
| 21/9    | 2         | 1.57%   |
| 3/2     | 1         | 0.79%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 25.37%  |
| 201-250        | 29        | 21.64%  |
| 81-90          | 16        | 11.94%  |
| 151-200        | 10        | 7.46%   |
| Unknown        | 9         | 6.72%   |
| 121-130        | 7         | 5.22%   |
| More than 1000 | 6         | 4.48%   |
| 351-500        | 5         | 3.73%   |
| 301-350        | 5         | 3.73%   |
| 141-150        | 4         | 2.99%   |
| 71-80          | 2         | 1.49%   |
| 51-60          | 2         | 1.49%   |
| 61-70          | 1         | 0.75%   |
| 41-50          | 1         | 0.75%   |
| 251-300        | 1         | 0.75%   |
| 111-120        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 45        | 33.33%  |
| 51-100        | 45        | 33.33%  |
| 121-160       | 27        | 20%     |
| Unknown       | 9         | 6.67%   |
| 1-50          | 5         | 3.7%    |
| 161-240       | 3         | 2.22%   |
| More than 240 | 1         | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 86.61%  |
| 2     | 14        | 11.02%  |
| 0     | 2         | 1.57%   |
| 3     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 68        | 35.6%   |
| Intel                             | 61        | 31.94%  |
| Qualcomm Atheros                  | 25        | 13.09%  |
| Broadcom                          | 8         | 4.19%   |
| Ralink Technology                 | 4         | 2.09%   |
| TP-Link                           | 3         | 1.57%   |
| Microsoft                         | 3         | 1.57%   |
| Huawei Technologies               | 3         | 1.57%   |
| Xiaomi                            | 2         | 1.05%   |
| Ralink                            | 2         | 1.05%   |
| Spreadtrum Communications         | 1         | 0.52%   |
| Sierra Wireless                   | 1         | 0.52%   |
| Samsung Electronics               | 1         | 0.52%   |
| Qualcomm Atheros Communications   | 1         | 0.52%   |
| Nvidia                            | 1         | 0.52%   |
| NetXen Incorporated               | 1         | 0.52%   |
| Marvell Technology Group          | 1         | 0.52%   |
| Ericsson Business Mobile Networks | 1         | 0.52%   |
| DisplayLink                       | 1         | 0.52%   |
| Dell                              | 1         | 0.52%   |
| Broadcom Limited                  | 1         | 0.52%   |
| Belkin Components                 | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 45        | 20.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 4.5%    |
| Intel I211 Gigabit Network Connection                                   | 10        | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 4.05%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.25%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.8%    |
| Intel Wireless-AC 9260                                                  | 4         | 1.8%    |
| Intel Wireless 8265 / 8275                                              | 4         | 1.8%    |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 1.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 3         | 1.35%   |
| Huawei E353/E3131                                                       | 3         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.9%    |
| Ralink RT5572 Wireless Adapter                                          | 2         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.9%    |
| Intel Wireless 7265                                                     | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.45%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.45%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1         | 0.45%   |
| Spreadtrum Unisoc Phone                                                 | 1         | 0.45%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.45%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.45%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.45%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter    | 1         | 0.45%   |
| Microsoft XBOX ACC                                                      | 1         | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.45%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                       | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 40.2%   |
| Qualcomm Atheros                | 23        | 22.55%  |
| Realtek Semiconductor           | 17        | 16.67%  |
| Broadcom                        | 5         | 4.9%    |
| Ralink Technology               | 4         | 3.92%   |
| TP-Link                         | 3         | 2.94%   |
| Ralink                          | 2         | 1.96%   |
| Microsoft                       | 2         | 1.96%   |
| Sierra Wireless                 | 1         | 0.98%   |
| Qualcomm Atheros Communications | 1         | 0.98%   |
| Marvell Technology Group        | 1         | 0.98%   |
| Broadcom Limited                | 1         | 0.98%   |
| Belkin Components               | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 8         | 7.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 5.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.85%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 4.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.88%   |
| Intel Wireless-AC 9260                                                  | 4         | 3.88%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 2.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 2.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 1.94%   |
| Ralink RT5572 Wireless Adapter                                          | 2         | 1.94%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.94%   |
| Intel Wireless 7265                                                     | 2         | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.94%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.97%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 1         | 0.97%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.97%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.97%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.97%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.97%   |
| Microsoft XBOX ACC                                                      | 1         | 0.97%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.97%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.97%   |
| Intel Wireless 7260                                                     | 1         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.97%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.97%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.97%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.97%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.97%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.97%   |
| Broadcom BCM43217 802.11b/g/n                                           | 1         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.97%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]  | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 57        | 48.72%  |
| Intel                     | 40        | 34.19%  |
| Qualcomm Atheros          | 6         | 5.13%   |
| Huawei Technologies       | 3         | 2.56%   |
| Broadcom                  | 3         | 2.56%   |
| Xiaomi                    | 2         | 1.71%   |
| Spreadtrum Communications | 1         | 0.85%   |
| Samsung Electronics       | 1         | 0.85%   |
| Nvidia                    | 1         | 0.85%   |
| NetXen Incorporated       | 1         | 0.85%   |
| Microsoft                 | 1         | 0.85%   |
| DisplayLink               | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 45        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 10        | 8.55%   |
| Intel I211 Gigabit Network Connection                                | 10        | 8.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 9         | 7.69%   |
| Intel Ethernet Connection I217-LM                                    | 4         | 3.42%   |
| Intel 82577LM Gigabit Network Connection                             | 3         | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 3         | 2.56%   |
| Huawei E353/E3131                                                    | 3         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 2         | 1.71%   |
| Intel Ethernet Connection (2) I219-V                                 | 2         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1         | 0.85%   |
| Spreadtrum Unisoc Phone                                              | 1         | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1         | 0.85%   |
| Nvidia MCP61 Ethernet                                                | 1         | 0.85%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.85%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                    | 1         | 0.85%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                                 | 1         | 0.85%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 0.85%   |
| Intel 82578DC Gigabit Network Connection                             | 1         | 0.85%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 0.85%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.85%   |
| DisplayLink Dell Universal Dock D6000                                | 1         | 0.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 1         | 0.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 1         | 0.85%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 107       | 51.69%  |
| WiFi     | 98        | 47.34%  |
| Modem    | 2         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 50%     |
| Ethernet | 64        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 65        | 51.59%  |
| 1     | 53        | 42.06%  |
| 0     | 4         | 3.17%   |
| 3     | 3         | 2.38%   |
| 6     | 1         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 92.91%  |
| Yes  | 9         | 7.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 42.03%  |
| Cambridge Silicon Radio         | 7         | 10.14%  |
| Realtek Semiconductor           | 6         | 8.7%    |
| Qualcomm Atheros Communications | 6         | 8.7%    |
| Lite-On Technology              | 5         | 7.25%   |
| IMC Networks                    | 3         | 4.35%   |
| Dell                            | 3         | 4.35%   |
| Broadcom                        | 3         | 4.35%   |
| Foxconn / Hon Hai               | 2         | 2.9%    |
| ASUSTek Computer                | 2         | 2.9%    |
| Marvell Semiconductor           | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Foxconn International           | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 11.59%  |
| Intel AX200 Bluetooth                               | 8         | 11.59%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 10.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 7.25%   |
| Realtek Bluetooth Radio                             | 4         | 5.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 5.8%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.9%    |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 2.9%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.45%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.45%   |
| Lite-On BCM43142A0                                  | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.45%   |
| Intel Bluetooth Device                              | 1         | 1.45%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.45%   |
| IMC Networks Bluetooth Module                       | 1         | 1.45%   |
| IMC Networks Bluetooth Device                       | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.45%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.45%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.45%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.45%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.45%   |
| ASUS BCM20702A0                                     | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 90        | 49.45%  |
| AMD                    | 41        | 22.53%  |
| Nvidia                 | 35        | 19.23%  |
| C-Media Electronics    | 4         | 2.2%    |
| JMTek                  | 2         | 1.1%    |
| GN Netcom              | 2         | 1.1%    |
| Plantronics            | 1         | 0.55%   |
| Microsoft              | 1         | 0.55%   |
| Logitech               | 1         | 0.55%   |
| Generalplus Technology | 1         | 0.55%   |
| Focusrite-Novation     | 1         | 0.55%   |
| Creative Labs          | 1         | 0.55%   |
| Blue Microphones       | 1         | 0.55%   |
| Alesis                 | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 3.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 3.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.31%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 2.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 2.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.85%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 1.39%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 1.39%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 1.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.39%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.93%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.93%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.93%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.93%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.93%   |
| Plantronics RIG 800HD                                                                             | 1         | 0.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.46%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.46%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.46%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.46%   |
| Microsoft Surface Pro 3 Docking Station Audio Device                                              | 1         | 0.46%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.46%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.46%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 17.39%  |
| SK hynix            | 3         | 13.04%  |
| Micron Technology   | 3         | 13.04%  |
| Kingston            | 3         | 13.04%  |
| Unknown             | 2         | 8.7%    |
| Team                | 2         | 8.7%    |
| Crucial             | 2         | 8.7%    |
| Smart               | 1         | 4.35%   |
| Ramaxel Technology  | 1         | 4.35%   |
| G.Skill             | 1         | 4.35%   |
| Corsair             | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s        | 2         | 7.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 3.85%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                        | 1         | 3.85%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 3.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.85%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 1         | 3.85%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 1         | 3.85%   |
| Samsung RAM K3QF3F30BM-AGCF 2GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.85%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s      | 1         | 3.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 1         | 3.85%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s  | 1         | 3.85%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8192MB DIMM DDR4 2400MT/s       | 1         | 3.85%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 1         | 3.85%   |
| Kingston RAM 99P5471-002.A00LF 2GB DIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Kingston RAM 99P5471-001.A01LF 2GB DIMM DDR3 1333MT/s        | 1         | 3.85%   |
| Kingston RAM 99P5471-001.A00LF 2GB DIMM DDR3 1333MT/s        | 1         | 3.85%   |
| Kingston RAM 9905584-023.A00LF 4GB DIMM DDR3 1600MT/s        | 1         | 3.85%   |
| G.Skill RAM F4-3600C16-8GVKC 8192MB DIMM DDR4 3600MT/s       | 1         | 3.85%   |
| Crucial RAM BLT4G3D1869DT 4096MB DIMM DDR3 1333MT/s          | 1         | 3.85%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s     | 1         | 3.85%   |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 45.45%  |
| DDR3    | 8         | 36.36%  |
| SDRAM   | 1         | 4.55%   |
| LPDDR4  | 1         | 4.55%   |
| LPDDR3  | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 45%     |
| DIMM         | 9         | 45%     |
| Row Of Chips | 2         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 34.78%  |
| 4096  | 7         | 30.43%  |
| 2048  | 4         | 17.39%  |
| 32768 | 3         | 13.04%  |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 25%     |
| 3200  | 3         | 12.5%   |
| 2667  | 3         | 12.5%   |
| 2400  | 2         | 8.33%   |
| 1867  | 2         | 8.33%   |
| 1333  | 2         | 8.33%   |
| 3733  | 1         | 4.17%   |
| 3600  | 1         | 4.17%   |
| 3500  | 1         | 4.17%   |
| 3000  | 1         | 4.17%   |
| 1067  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Seiko Epson     | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L120 Series            | 1         | 16.67%  |
| HP LaserJet 1300                   | 1         | 16.67%  |
| HP DeskJet 3830 series             | 1         | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 16.67%  |
| Canon PIXMA MX920 Series           | 1         | 16.67%  |
| Canon PIXMA MG2500 Series          | 1         | 16.67%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 19.72%  |
| Microdia                               | 10        | 14.08%  |
| IMC Networks                           | 7         | 9.86%   |
| Realtek Semiconductor                  | 6         | 8.45%   |
| Acer                                   | 6         | 8.45%   |
| Logitech                               | 5         | 7.04%   |
| Syntek                                 | 3         | 4.23%   |
| Suyin                                  | 3         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Samsung Electronics                    | 2         | 2.82%   |
| Quanta                                 | 2         | 2.82%   |
| Generalplus Technology                 | 2         | 2.82%   |
| Alcor Micro                            | 2         | 2.82%   |
| Sunplus Innovation Technology          | 1         | 1.41%   |
| Ricoh                                  | 1         | 1.41%   |
| Lite-On Technology                     | 1         | 1.41%   |
| Lenovo                                 | 1         | 1.41%   |
| KYE Systems (Mouse Systems)            | 1         | 1.41%   |
| GEMBIRD                                | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                          | 5         | 7.04%   |
| Logitech HD Pro Webcam C920                                                | 3         | 4.23%   |
| Chicony Integrated Camera                                                  | 3         | 4.23%   |
| Acer EasyCamera                                                            | 3         | 4.23%   |
| Syntek Integrated Camera                                                   | 2         | 2.82%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 2.82%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 2.82%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 2.82%   |
| IMC Networks Integrated Camera                                             | 2         | 2.82%   |
| Generalplus 808 Camera                                                     | 2         | 2.82%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 2.82%   |
| Acer Lenovo EasyCamera                                                     | 2         | 2.82%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.41%   |
| Suyin Sony Visual Communication Camera                                     | 1         | 1.41%   |
| Suyin Lenovo EasyCamera                                                    | 1         | 1.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.41%   |
| Sunplus HD WebCam                                                          | 1         | 1.41%   |
| Ricoh HD Webcam                                                            | 1         | 1.41%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.41%   |
| Realtek USB Camera                                                         | 1         | 1.41%   |
| Realtek Laptop_Integrated_Webcam_HD                                        | 1         | 1.41%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.41%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.41%   |
| Realtek HD WebCam                                                          | 1         | 1.41%   |
| Quanta hm1091_techfront                                                    | 1         | 1.41%   |
| Quanta HD User Facing                                                      | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.41%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 1.41%   |
| Microdia Integrated_Webcam_FHD                                             | 1         | 1.41%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.41%   |
| Logitech Webcam C110                                                       | 1         | 1.41%   |
| Logitech C922 Pro Stream Webcam                                            | 1         | 1.41%   |
| Lite-On HP Wide Vision HD Camera                                           | 1         | 1.41%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.41%   |
| KYE Systems (Mouse Systems) Slim 1322AF                                    | 1         | 1.41%   |
| IMC Networks XHC Camera                                                    | 1         | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.41%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.41%   |
| IMC Networks EasyCamera                                                    | 1         | 1.41%   |
| GEMBIRD USB2.0 PC CAMERA                                                   | 1         | 1.41%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.41%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.41%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 1         | 1.41%   |
| Alcor Micro USB 2.0 PC Camera                                              | 1         | 1.41%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.41%   |
| Acer HD Webcam                                                             | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 60%     |
| Synaptics             | 2         | 20%     |
| Elan Microelectronics | 2         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 20%     |
| Elan ELAN:Fingerprint                                      | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 73.02%  |
| 1     | 29        | 23.02%  |
| 2     | 5         | 3.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 10        | 25.64%  |
| Fingerprint reader       | 10        | 25.64%  |
| Chipcard                 | 6         | 15.38%  |
| Multimedia controller    | 4         | 10.26%  |
| Graphics card            | 4         | 10.26%  |
| Storage                  | 2         | 5.13%   |
| Tv card                  | 1         | 2.56%   |
| Communication controller | 1         | 2.56%   |
| Camera                   | 1         | 2.56%   |

