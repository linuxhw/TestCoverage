Elementary 6 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6/Desktop/README.md) and [notebooks](/Dist/Elementary_6/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 282

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Inventec      | D CLASS A02                 | Desktop     | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| LG Electro... | P1-JSUVT                    | Notebook    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| ASUSTek       | GL502VS                     | Notebook    | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| ASRock        | Z590 Phantom Gaming 4/ac    | Desktop     | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7b3efc8cd8](https://linux-hardware.org/?probe=7b3efc8cd8) | Dec 14, 2021 |
| Pegatron      | IPMH61P1                    | Desktop     | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | Notebook    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| Google        | Cyan                        | Notebook    | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Dell          | Latitude E5420              | Notebook    | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [73f375d3ac](https://linux-hardware.org/?probe=73f375d3ac) | Dec 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| Acer          | Aspire X3990                | Desktop     | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | Notebook    | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [c9fe8f5431](https://linux-hardware.org/?probe=c9fe8f5431) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| HP            | 2B07                        | All in one  | [b6cf0a1651](https://linux-hardware.org/?probe=b6cf0a1651) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Pegatron      | Benicia                     | Desktop     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| HP            | 8653 A                      | Desktop     | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Google        | Kip                         | Notebook    | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar       | TH55XE                      | Desktop     | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | Desktop     | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| HP            | Pavilion dm4                | Notebook    | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | Notebook    | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Acer          | Aspire X3990                | Desktop     | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Notebook      | L140CU                      | Notebook    | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| Acer          | Iconia Tab W500             | Tablet      | [5984a91751](https://linux-hardware.org/?probe=5984a91751) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | 1825                        | Desktop     | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | Desktop     | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| MSI           | GF72 7RE                    | Notebook    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [e7e27b16de](https://linux-hardware.org/?probe=e7e27b16de) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| HP            | 0AECh D                     | Desktop     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | Notebook    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [078e3be7c3](https://linux-hardware.org/?probe=078e3be7c3) | Nov 17, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | Notebook    | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | 0F2A20 A00                  | All in one  | [e98616633d](https://linux-hardware.org/?probe=e98616633d) | Nov 16, 2021 |
| Gigabyte      | EP43T-USB3                  | Desktop     | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [197f5e1565](https://linux-hardware.org/?probe=197f5e1565) | Nov 12, 2021 |
| Sony          | SVE15115EN                  | Notebook    | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| MSI           | 970A-G43                    | Desktop     | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Dell          | 05R2TK A01                  | All in one  | [0b728f2263](https://linux-hardware.org/?probe=0b728f2263) | Nov 07, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | Notebook    | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [66109af766](https://linux-hardware.org/?probe=66109af766) | Nov 05, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | Notebook    | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6461bfc243](https://linux-hardware.org/?probe=6461bfc243) | Oct 26, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | 84EE 1100                   | All in one  | [225f3ee57b](https://linux-hardware.org/?probe=225f3ee57b) | Oct 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | Notebook    | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | Notebook    | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| HP            | 339A                        | Desktop     | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | Notebook    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | Desktop     | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [06f11c0449](https://linux-hardware.org/?probe=06f11c0449) | Sep 30, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [961d53afb6](https://linux-hardware.org/?probe=961d53afb6) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Dell          | Precision M4800             | Notebook    | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | Notebook    | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | Notebook    | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | Notebook    | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | Notebook    | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | Notebook    | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | Notebook    | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Intel         | H61                         | Desktop     | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | 8767 A                      | Desktop     | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | Notebook    | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfb9789af2](https://linux-hardware.org/?probe=dfb9789af2) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ebd997cb1a](https://linux-hardware.org/?probe=ebd997cb1a) | Sep 05, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a5d7b5a10e](https://linux-hardware.org/?probe=a5d7b5a10e) | Sep 05, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | 86ED A01                    | All in one  | [78778f22a2](https://linux-hardware.org/?probe=78778f22a2) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | Notebook    | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | Desktop     | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | Notebook    | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [aeec497ed8](https://linux-hardware.org/?probe=aeec497ed8) | Aug 28, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| HP            | 86ED A01                    | All in one  | [402a8e492c](https://linux-hardware.org/?probe=402a8e492c) | Aug 24, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | Notebook    | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | Notebook    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | Notebook    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a8d4959fde](https://linux-hardware.org/?probe=a8d4959fde) | Aug 14, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | Notebook    | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google        | Cave                        | Notebook    | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP            | 8433 11                     | Desktop     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-40-generic      | 53        | 21.99%  |
| 5.11.0-41-generic      | 42        | 17.43%  |
| 5.11.0-27-generic      | 40        | 16.6%   |
| 5.11.0-38-generic      | 27        | 11.2%   |
| 5.11.0-37-generic      | 24        | 9.96%   |
| 5.11.0-25-generic      | 17        | 7.05%   |
| 5.11.0-34-generic      | 14        | 5.81%   |
| 5.8.0-50-generic       | 5         | 2.07%   |
| 5.11.0-36-generic      | 4         | 1.66%   |
| 5.8.0-55-generic       | 3         | 1.24%   |
| 5.8.0-63-generic       | 2         | 0.83%   |
| 5.8.0-53-generic       | 1         | 0.41%   |
| 5.8.0-44-generic       | 1         | 0.41%   |
| 5.4.0-91-generic       | 1         | 0.41%   |
| 5.4.0-58-generic       | 1         | 0.41%   |
| 5.4.0-56-generic       | 1         | 0.41%   |
| 5.15.1-xanmod1         | 1         | 0.41%   |
| 5.14.7-xanmod1-cacule  | 1         | 0.41%   |
| 5.14.14-051414-generic | 1         | 0.41%   |
| 5.11.0-41-lowlatency   | 1         | 0.41%   |
| 5.11.0-051100-generic  | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 213       | 92.21%  |
| 5.8.0   | 12        | 5.19%   |
| 5.4.0   | 3         | 1.3%    |
| 5.15.1  | 1         | 0.43%   |
| 5.14.7  | 1         | 0.43%   |
| 5.14.14 | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 213       | 92.21%  |
| 5.8     | 12        | 5.19%   |
| 5.4     | 3         | 1.3%    |
| 5.14    | 2         | 0.87%   |
| 5.15    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 231       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 211       | 90.95%  |
| Unknown    | 15        | 6.47%   |
| GNOME      | 3         | 1.29%   |
| X-Cinnamon | 2         | 0.86%   |
| MATE       | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 231       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 181       | 78.35%  |
| LightDM | 40        | 17.32%  |
| TDM     | 7         | 3.03%   |
| GDM     | 3         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 116       | 50.22%  |
| de_DE | 24        | 10.39%  |
| es_ES | 19        | 8.23%   |
| ru_RU | 8         | 3.46%   |
| pt_BR | 8         | 3.46%   |
| fr_FR | 8         | 3.46%   |
| en_GB | 6         | 2.6%    |
| en_CA | 5         | 2.16%   |
| pl_PL | 4         | 1.73%   |
| it_IT | 4         | 1.73%   |
| zh_CN | 3         | 1.3%    |
| tr_TR | 3         | 1.3%    |
| en_AU | 3         | 1.3%    |
| cs_CZ | 3         | 1.3%    |
| nl_NL | 2         | 0.87%   |
| de_CH | 2         | 0.87%   |
| ca_ES | 2         | 0.87%   |
| vi_VN | 1         | 0.43%   |
| ro_RO | 1         | 0.43%   |
| lt_LT | 1         | 0.43%   |
| id_ID | 1         | 0.43%   |
| hu_HU | 1         | 0.43%   |
| hr_HR | 1         | 0.43%   |
| gl_ES | 1         | 0.43%   |
| fr_BE | 1         | 0.43%   |
| fi_FI | 1         | 0.43%   |
| es_MX | 1         | 0.43%   |
| da_DK | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 144       | 62.07%  |
| BIOS | 88        | 37.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 222       | 96.1%   |
| Overlay | 5         | 2.16%   |
| Btrfs   | 4         | 1.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 191       | 82.68%  |
| GPT     | 29        | 12.55%  |
| MBR     | 11        | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 220       | 95.24%  |
| Yes       | 11        | 4.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 87.88%  |
| Yes       | 28        | 12.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 48        | 20.78%  |
| Lenovo                  | 27        | 11.69%  |
| Dell                    | 25        | 10.82%  |
| ASUSTek Computer        | 25        | 10.82%  |
| Apple                   | 16        | 6.93%   |
| Acer                    | 16        | 6.93%   |
| Gigabyte Technology     | 15        | 6.49%   |
| MSI                     | 8         | 3.46%   |
| ASRock                  | 8         | 3.46%   |
| Toshiba                 | 4         | 1.73%   |
| Intel                   | 3         | 1.3%    |
| HUAWEI                  | 3         | 1.3%    |
| Google                  | 3         | 1.3%    |
| TUXEDO                  | 2         | 0.87%   |
| Sony                    | 2         | 0.87%   |
| Pegatron                | 2         | 0.87%   |
| Microsoft               | 2         | 0.87%   |
| Medion                  | 2         | 0.87%   |
| Biostar                 | 2         | 0.87%   |
| Star Labs               | 1         | 0.43%   |
| Shuttle                 | 1         | 0.43%   |
| Schenker                | 1         | 0.43%   |
| Samsung Electronics     | 1         | 0.43%   |
| Quanta                  | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Packard Bell            | 1         | 0.43%   |
| Notebook                | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| Inventec                | 1         | 0.43%   |
| HCL Infosystems Limited | 1         | 0.43%   |
| Gateway                 | 1         | 0.43%   |
| Fujitsu                 | 1         | 0.43%   |
| eMachines               | 1         | 0.43%   |
| Chuwi                   | 1         | 0.43%   |
| Alienware               | 1         | 0.43%   |
| Acidanthera             | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1           | 2         | 0.87%   |
| HP Pavilion Notebook                 | 2         | 0.87%   |
| Dell XPS 13 9350                     | 2         | 0.87%   |
| Dell Inspiron N5110                  | 2         | 0.87%   |
| Apple MacBookPro9,1                  | 2         | 0.87%   |
| Apple MacBookPro10,2                 | 2         | 0.87%   |
| Apple MacBookAir7,2                  | 2         | 0.87%   |
| TUXEDO Pulse 15 Gen1                 | 1         | 0.43%   |
| TUXEDO InfinityBook S 14 Gen6        | 1         | 0.43%   |
| Toshiba Satellite P100               | 1         | 0.43%   |
| Toshiba Satellite L840               | 1         | 0.43%   |
| Toshiba Satellite L750               | 1         | 0.43%   |
| Toshiba Satellite L500               | 1         | 0.43%   |
| Star Labs StarBook                   | 1         | 0.43%   |
| Sony SVE15115EN                      | 1         | 0.43%   |
| Sony Serie VJC14                     | 1         | 0.43%   |
| Shuttle DS61                         | 1         | 0.43%   |
| Schenker X170KM-G                    | 1         | 0.43%   |
| Samsung 550XDA                       | 1         | 0.43%   |
| Quanta TW9/SW9                       | 1         | 0.43%   |
| Pegatron KJ379AA-ABA a6400f          | 1         | 0.43%   |
| Pegatron IPMH61P1                    | 1         | 0.43%   |
| Panasonic FZ-G1ASH39E3               | 1         | 0.43%   |
| Packard Bell EasyNote LS11HR         | 1         | 0.43%   |
| Notebook L140CU                      | 1         | 0.43%   |
| MSI MS-7C83                          | 1         | 0.43%   |
| MSI MS-7B79                          | 1         | 0.43%   |
| MSI MS-7B46                          | 1         | 0.43%   |
| MSI MS-7817                          | 1         | 0.43%   |
| MSI MS-7693                          | 1         | 0.43%   |
| MSI Modern 14 B4MW                   | 1         | 0.43%   |
| MSI GF72 7RE                         | 1         | 0.43%   |
| MSI Elite 7100 Microtower PC         | 1         | 0.43%   |
| Microsoft Surface Pro 4              | 1         | 0.43%   |
| Microsoft Surface Pro 3              | 1         | 0.43%   |
| Medion E7218                         | 1         | 0.43%   |
| Medion Akoya THE TOUCH 10            | 1         | 0.43%   |
| LG P1-JSUVT                          | 1         | 0.43%   |
| Lenovo V330-15IKB 81AX               | 1         | 0.43%   |
| Lenovo ThinkPad X250 20CLS32H00      | 1         | 0.43%   |
| Lenovo ThinkPad X230 23259L3         | 1         | 0.43%   |
| Lenovo ThinkPad X201 Tablet 311396G  | 1         | 0.43%   |
| Lenovo ThinkPad X201 3249CTO         | 1         | 0.43%   |
| Lenovo ThinkPad X140e 20BLS00400     | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 3448B86    | 1         | 0.43%   |
| Lenovo ThinkPad W700 2758MVG         | 1         | 0.43%   |
| Lenovo ThinkPad T470 20HD004AUS      | 1         | 0.43%   |
| Lenovo ThinkPad T460s 20F9CTO1WW     | 1         | 0.43%   |
| Lenovo ThinkPad T460s 20F90042MS     | 1         | 0.43%   |
| Lenovo ThinkPad T430 2342A19         | 1         | 0.43%   |
| Lenovo ThinkPad T410s 292494G        | 1         | 0.43%   |
| Lenovo ThinkPad T14 Gen 1 20UES5SR00 | 1         | 0.43%   |
| Lenovo ThinkPad SL400 2743A37        | 1         | 0.43%   |
| Lenovo ThinkPad E470 20H10052IG      | 1         | 0.43%   |
| Lenovo ThinkPad E14 Gen 3 20Y7006XMX | 1         | 0.43%   |
| Lenovo IdeaPad S145-15AST 81N3       | 1         | 0.43%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 1         | 0.43%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 1         | 0.43%   |
| Lenovo IdeaPad 330-15IKB 81FE        | 1         | 0.43%   |
| Lenovo IdeaPad 320S-14IKB 81BN       | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 6.93%   |
| HP Pavilion            | 13        | 5.63%   |
| Acer Aspire            | 11        | 4.76%   |
| Dell Inspiron          | 7         | 3.03%   |
| Lenovo IdeaPad         | 6         | 2.6%    |
| HP ProBook             | 6         | 2.6%    |
| HP Laptop              | 6         | 2.6%    |
| HP EliteBook           | 6         | 2.6%    |
| Dell XPS               | 6         | 2.6%    |
| HP ENVY                | 5         | 2.16%   |
| Toshiba Satellite      | 4         | 1.73%   |
| Dell Latitude          | 4         | 1.73%   |
| Dell OptiPlex          | 3         | 1.3%    |
| ASUS TUF               | 3         | 1.3%    |
| ASUS ROG               | 3         | 1.3%    |
| ASUS PRIME             | 3         | 1.3%    |
| Microsoft Surface      | 2         | 0.87%   |
| Lenovo Yoga            | 2         | 0.87%   |
| HP Compaq              | 2         | 0.87%   |
| Gigabyte X570          | 2         | 0.87%   |
| Gigabyte B450M         | 2         | 0.87%   |
| Dell System            | 2         | 0.87%   |
| Dell Precision         | 2         | 0.87%   |
| Apple MacBookPro9      | 2         | 0.87%   |
| Apple MacBookPro8      | 2         | 0.87%   |
| Apple MacBookPro10     | 2         | 0.87%   |
| Apple MacBookAir7      | 2         | 0.87%   |
| Acer Swift             | 2         | 0.87%   |
| Acer ConceptD          | 2         | 0.87%   |
| TUXEDO Pulse           | 1         | 0.43%   |
| TUXEDO InfinityBook    | 1         | 0.43%   |
| Star Labs StarBook     | 1         | 0.43%   |
| Sony SVE15115EN        | 1         | 0.43%   |
| Sony Serie             | 1         | 0.43%   |
| Shuttle DS61           | 1         | 0.43%   |
| Schenker X170KM-G      | 1         | 0.43%   |
| Samsung 550XDA         | 1         | 0.43%   |
| Quanta TW9             | 1         | 0.43%   |
| Pegatron KJ379AA-ABA   | 1         | 0.43%   |
| Pegatron IPMH61P1      | 1         | 0.43%   |
| Panasonic FZ-G1ASH39E3 | 1         | 0.43%   |
| Packard Bell EasyNote  | 1         | 0.43%   |
| Notebook L140CU        | 1         | 0.43%   |
| MSI MS-7C83            | 1         | 0.43%   |
| MSI MS-7B79            | 1         | 0.43%   |
| MSI MS-7B46            | 1         | 0.43%   |
| MSI MS-7817            | 1         | 0.43%   |
| MSI MS-7693            | 1         | 0.43%   |
| MSI Modern             | 1         | 0.43%   |
| MSI GF72               | 1         | 0.43%   |
| MSI Elite              | 1         | 0.43%   |
| Medion E7218           | 1         | 0.43%   |
| Medion Akoya           | 1         | 0.43%   |
| LG P1-JSUVT            | 1         | 0.43%   |
| Lenovo V330-15IKB      | 1         | 0.43%   |
| Lenovo IdeaCentre      | 1         | 0.43%   |
| Lenovo G50-45          | 1         | 0.43%   |
| Inventec D             | 1         | 0.43%   |
| Intel X64              | 1         | 0.43%   |
| Intel NUC7i3BNH        | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 28        | 12.12%  |
| 2018    | 23        | 9.96%   |
| 2011    | 22        | 9.52%   |
| 2010    | 20        | 8.66%   |
| 2019    | 19        | 8.23%   |
| 2017    | 18        | 7.79%   |
| 2016    | 18        | 7.79%   |
| 2021    | 17        | 7.36%   |
| 2012    | 17        | 7.36%   |
| 2015    | 15        | 6.49%   |
| 2014    | 11        | 4.76%   |
| 2013    | 8         | 3.46%   |
| 2009    | 7         | 3.03%   |
| 2008    | 4         | 1.73%   |
| 2007    | 2         | 0.87%   |
| 2006    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 141       | 61.04%  |
| Desktop     | 67        | 29%     |
| All in one  | 11        | 4.76%   |
| Convertible | 6         | 2.6%    |
| Tablet      | 4         | 1.73%   |
| Mini pc     | 2         | 0.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 193       | 83.55%  |
| Enabled  | 38        | 16.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 227       | 98.27%  |
| Yes  | 4         | 1.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 67        | 29%     |
| 16.01-24.0  | 46        | 19.91%  |
| 3.01-4.0    | 41        | 17.75%  |
| 8.01-16.0   | 37        | 16.02%  |
| 32.01-64.0  | 24        | 10.39%  |
| 1.01-2.0    | 10        | 4.33%   |
| 24.01-32.0  | 3         | 1.3%    |
| 64.01-256.0 | 2         | 0.87%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 100       | 41.49%  |
| 2.01-3.0   | 68        | 28.22%  |
| 3.01-4.0   | 34        | 14.11%  |
| 4.01-8.0   | 33        | 13.69%  |
| 0.51-1.0   | 3         | 1.24%   |
| 8.01-16.0  | 2         | 0.83%   |
| 32.01-64.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 63.52%  |
| 2      | 60        | 25.75%  |
| 3      | 12        | 5.15%   |
| 4      | 9         | 3.86%   |
| 5      | 3         | 1.29%   |
| 6      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 68.4%   |
| Yes       | 73        | 31.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 82.25%  |
| No        | 41        | 17.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 84.85%  |
| No        | 35        | 15.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 73.28%  |
| No        | 62        | 26.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 31        | 13.36%  |
| Germany            | 23        | 9.91%   |
| India              | 14        | 6.03%   |
| Canada             | 12        | 5.17%   |
| UK                 | 11        | 4.74%   |
| Russia             | 10        | 4.31%   |
| Brazil             | 10        | 4.31%   |
| France             | 8         | 3.45%   |
| Mexico             | 7         | 3.02%   |
| Argentina          | 7         | 3.02%   |
| Netherlands        | 6         | 2.59%   |
| Indonesia          | 6         | 2.59%   |
| Spain              | 5         | 2.16%   |
| Turkey             | 4         | 1.72%   |
| Poland             | 4         | 1.72%   |
| Italy              | 4         | 1.72%   |
| Finland            | 4         | 1.72%   |
| Denmark            | 4         | 1.72%   |
| Czechia            | 4         | 1.72%   |
| Australia          | 4         | 1.72%   |
| Vietnam            | 3         | 1.29%   |
| Sweden             | 3         | 1.29%   |
| Belgium            | 3         | 1.29%   |
| Austria            | 3         | 1.29%   |
| Switzerland        | 2         | 0.86%   |
| Romania            | 2         | 0.86%   |
| Paraguay           | 2         | 0.86%   |
| Kenya              | 2         | 0.86%   |
| Guatemala          | 2         | 0.86%   |
| Estonia            | 2         | 0.86%   |
| China              | 2         | 0.86%   |
| Chile              | 2         | 0.86%   |
| Uruguay            | 1         | 0.43%   |
| Ukraine            | 1         | 0.43%   |
| Thailand           | 1         | 0.43%   |
| Sri Lanka          | 1         | 0.43%   |
| South Africa       | 1         | 0.43%   |
| Slovenia           | 1         | 0.43%   |
| Serbia             | 1         | 0.43%   |
| Philippines        | 1         | 0.43%   |
| New Zealand        | 1         | 0.43%   |
| Myanmar            | 1         | 0.43%   |
| Morocco            | 1         | 0.43%   |
| Malaysia           | 1         | 0.43%   |
| Lithuania          | 1         | 0.43%   |
| Latvia             | 1         | 0.43%   |
| Kazakhstan         | 1         | 0.43%   |
| Japan              | 1         | 0.43%   |
| Ireland            | 1         | 0.43%   |
| Hungary            | 1         | 0.43%   |
| Guyana             | 1         | 0.43%   |
| Greece             | 1         | 0.43%   |
| Dominican Republic | 1         | 0.43%   |
| Croatia            | 1         | 0.43%   |
| Costa Rica         | 1         | 0.43%   |
| Colombia           | 1         | 0.43%   |
| Belarus            | 1         | 0.43%   |
| Albania            | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Vienna             | 3         | 1.27%   |
| Vernon             | 3         | 1.27%   |
| Paris              | 3         | 1.27%   |
| Moscow             | 3         | 1.27%   |
| Mexico City        | 3         | 1.27%   |
| Warsaw             | 2         | 0.84%   |
| Valladolid         | 2         | 0.84%   |
| Tallinn            | 2         | 0.84%   |
| Sassnitz           | 2         | 0.84%   |
| Sao Paulo          | 2         | 0.84%   |
| Santiago           | 2         | 0.84%   |
| San Jose           | 2         | 0.84%   |
| Perth              | 2         | 0.84%   |
| Nairobi            | 2         | 0.84%   |
| Mumbai             | 2         | 0.84%   |
| Montreal           | 2         | 0.84%   |
| Milan              | 2         | 0.84%   |
| Kolkata            | 2         | 0.84%   |
| Istanbul           | 2         | 0.84%   |
| Ho Chi Minh City   | 2         | 0.84%   |
| Guatemala City     | 2         | 0.84%   |
| Copenhagen         | 2         | 0.84%   |
| Coimbatore         | 2         | 0.84%   |
| Calgary            | 2         | 0.84%   |
| Buenos Aires       | 2         | 0.84%   |
| Berlin             | 2         | 0.84%   |
| Zurich             | 1         | 0.42%   |
| Zonguldak          | 1         | 0.42%   |
| Xicheng District   | 1         | 0.42%   |
| Woodbridge         | 1         | 0.42%   |
| Wigan              | 1         | 0.42%   |
| Walsrode           | 1         | 0.42%   |
| Wakefield          | 1         | 0.42%   |
| Vit??ria           | 1         | 0.42%   |
| Vilnius            | 1         | 0.42%   |
| Villeurbanne       | 1         | 0.42%   |
| Villahermosa       | 1         | 0.42%   |
| Victoria           | 1         | 0.42%   |
| Vertaizon          | 1         | 0.42%   |
| Vancouver          | 1         | 0.42%   |
| V??lenii ??omcutei | 1         | 0.42%   |
| Turku              | 1         | 0.42%   |
| Turin              | 1         | 0.42%   |
| Tucson             | 1         | 0.42%   |
| Tolyatti           | 1         | 0.42%   |
| Toledo             | 1         | 0.42%   |
| The Hague          | 1         | 0.42%   |
| Temecula           | 1         | 0.42%   |
| Taganrog           | 1         | 0.42%   |
| Surabaya           | 1         | 0.42%   |
| Sukabumi           | 1         | 0.42%   |
| Stockport          | 1         | 0.42%   |
| Stockholm          | 1         | 0.42%   |
| Stevenage          | 1         | 0.42%   |
| Sparti             | 1         | 0.42%   |
| Skanderborg        | 1         | 0.42%   |
| Sinop              | 1         | 0.42%   |
| Simferopol         | 1         | 0.42%   |
| Setagaya-ku        | 1         | 0.42%   |
| Sedlec             | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 55        | 67     | 17.35%  |
| Samsung Electronics       | 50        | 65     | 15.77%  |
| Seagate                   | 37        | 45     | 11.67%  |
| SanDisk                   | 23        | 26     | 7.26%   |
| Toshiba                   | 19        | 19     | 5.99%   |
| Kingston                  | 15        | 20     | 4.73%   |
| Crucial                   | 14        | 17     | 4.42%   |
| Unknown                   | 13        | 14     | 4.1%    |
| Hitachi                   | 8         | 8      | 2.52%   |
| HGST                      | 8         | 8      | 2.52%   |
| Apple                     | 8         | 8      | 2.52%   |
| Micron Technology         | 7         | 7      | 2.21%   |
| Intel                     | 6         | 6      | 1.89%   |
| SK hynix                  | 5         | 6      | 1.58%   |
| Phison                    | 3         | 4      | 0.95%   |
| Patriot                   | 3         | 3      | 0.95%   |
| OCZ                       | 3         | 3      | 0.95%   |
| LITEON                    | 3         | 3      | 0.95%   |
| KIOXIA                    | 3         | 3      | 0.95%   |
| Gigabyte Technology       | 3         | 3      | 0.95%   |
| A-DATA Technology         | 3         | 4      | 0.95%   |
| Transcend                 | 2         | 3      | 0.63%   |
| Silicon Motion            | 2         | 2      | 0.63%   |
| Micron/Crucial Technology | 2         | 3      | 0.63%   |
| LITEONIT                  | 2         | 2      | 0.63%   |
| China                     | 2         | 2      | 0.63%   |
| USB3.1                    | 1         | 1      | 0.32%   |
| Union Memory              | 1         | 1      | 0.32%   |
| Team                      | 1         | 1      | 0.32%   |
| StoreJet                  | 1         | 1      | 0.32%   |
| Star Drive                | 1         | 1      | 0.32%   |
| OCZ-VERTEX2               | 1         | 1      | 0.32%   |
| Netac                     | 1         | 1      | 0.32%   |
| Mercury                   | 1         | 1      | 0.32%   |
| LS                        | 1         | 1      | 0.32%   |
| Kingmax                   | 1         | 1      | 0.32%   |
| Intenso                   | 1         | 1      | 0.32%   |
| HUAWEI                    | 1         | 1      | 0.32%   |
| Hewlett-Packard           | 1         | 1      | 0.32%   |
| GALAX                     | 1         | 1      | 0.32%   |
| Fujitsu                   | 1         | 1      | 0.32%   |
| Dogfish                   | 1         | 1      | 0.32%   |
| CLOVER                    | 1         | 1      | 0.32%   |
| Apacer                    | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 7         | 2.05%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 6         | 1.76%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.76%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 1.47%   |
| Samsung NVMe SSD Drive 256GB           | 5         | 1.47%   |
| Unknown MMC Card  128GB                | 4         | 1.17%   |
| Samsung NVMe SSD Drive 1TB             | 4         | 1.17%   |
| Intel NVMe SSD Drive 512GB             | 4         | 1.17%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 1.17%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.88%   |
| Toshiba MQ01ABD100V -63 1TB            | 3         | 0.88%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 3         | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.88%   |
| SanDisk NVMe SSD Drive 500GB           | 3         | 0.88%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.88%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 0.88%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.59%   |
| WDC WD5000AAKX-003CA0 500GB            | 2         | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB               | 2         | 0.59%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2         | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.59%   |
| Unknown MMC Card  32GB                 | 2         | 0.59%   |
| Unknown MMC Card  16GB                 | 2         | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.59%   |
| Toshiba MK6475GSX 640GB                | 2         | 0.59%   |
| SK hynix NVMe SSD Drive 512GB          | 2         | 0.59%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.59%   |
| Seagate ST250DM000-1BD141 250GB        | 2         | 0.59%   |
| Seagate ST2000LX001-1RG174 2TB         | 2         | 0.59%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 0.59%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.59%   |
| Samsung SSD 840 EVO 120GB              | 2         | 0.59%   |
| KIOXIA NVMe SSD Drive 512GB            | 2         | 0.59%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.59%   |
| Crucial CT525MX300SSD1 528GB           | 2         | 0.59%   |
| Crucial CT250MX500SSD1 250GB           | 2         | 0.59%   |
| Crucial CT240BX200SSD1 240GB           | 2         | 0.59%   |
| Apple SSD SD128E 121GB                 | 2         | 0.59%   |
| WDC WDS500G2B0A 500GB SSD              | 1         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.29%   |
| WDC WDS200T2B0B-00YS70 2TB SSD         | 1         | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.29%   |
| WDC WD6401AALS-00J7B0 640GB            | 1         | 0.29%   |
| WDC WD6400BEVT-22A0RT0 640GB           | 1         | 0.29%   |
| WDC WD5000LPLX-08ZNTT0 500GB           | 1         | 0.29%   |
| WDC WD5000BPVT-75HXZT1 500GB           | 1         | 0.29%   |
| WDC WD5000BPVT-22HXZT3 500GB           | 1         | 0.29%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.29%   |
| WDC WD5000BPVT-00HXZT1 500GB           | 1         | 0.29%   |
| WDC WD5000BPKT-75PK4T0 500GB           | 1         | 0.29%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 1         | 0.29%   |
| WDC WD5000AAKX-603CA0 500GB            | 1         | 0.29%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 1         | 0.29%   |
| WDC WD5000AAKX-001CA0 500GB            | 1         | 0.29%   |
| WDC WD50 00LUCT-61C26Y0 500GB          | 1         | 0.29%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 1         | 0.29%   |
| WDC WD40EZAZ-00SF3B0 4TB               | 1         | 0.29%   |
| WDC WD3200BEVT-75A23T0 320GB           | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 56     | 38.21%  |
| Seagate             | 36        | 43     | 29.27%  |
| Toshiba             | 15        | 15     | 12.2%   |
| Hitachi             | 8         | 8      | 6.5%    |
| HGST                | 8         | 8      | 6.5%    |
| Samsung Electronics | 5         | 5      | 4.07%   |
| Apple               | 2         | 2      | 1.63%   |
| Unknown             | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 18.35%  |
| Crucial             | 14        | 17     | 12.84%  |
| SanDisk             | 12        | 13     | 11.01%  |
| Kingston            | 12        | 16     | 11.01%  |
| WDC                 | 6         | 6      | 5.5%    |
| Apple               | 6         | 6      | 5.5%    |
| Patriot             | 3         | 3      | 2.75%   |
| OCZ                 | 3         | 3      | 2.75%   |
| Micron Technology   | 3         | 3      | 2.75%   |
| LITEON              | 3         | 3      | 2.75%   |
| A-DATA Technology   | 3         | 4      | 2.75%   |
| Transcend           | 2         | 3      | 1.83%   |
| SK hynix            | 2         | 2      | 1.83%   |
| LITEONIT            | 2         | 2      | 1.83%   |
| Intel               | 2         | 2      | 1.83%   |
| China               | 2         | 2      | 1.83%   |
| Toshiba             | 1         | 1      | 0.92%   |
| Team                | 1         | 1      | 0.92%   |
| StoreJet            | 1         | 1      | 0.92%   |
| OCZ-VERTEX2         | 1         | 1      | 0.92%   |
| Netac               | 1         | 1      | 0.92%   |
| Mercury             | 1         | 1      | 0.92%   |
| LS                  | 1         | 1      | 0.92%   |
| Kingmax             | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |
| Gigabyte Technology | 1         | 1      | 0.92%   |
| GALAX               | 1         | 1      | 0.92%   |
| Dogfish             | 1         | 1      | 0.92%   |
| Apacer              | 1         | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 113       | 139    | 38.18%  |
| SSD     | 96        | 125    | 32.43%  |
| NVMe    | 70        | 87     | 23.65%  |
| MMC     | 11        | 12     | 3.72%   |
| Unknown | 6         | 6      | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 180       | 261    | 67.16%  |
| NVMe | 70        | 87     | 26.12%  |
| MMC  | 11        | 12     | 4.1%    |
| SAS  | 7         | 9      | 2.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 172    | 62.15%  |
| 0.51-1.0   | 65        | 74     | 30.37%  |
| 1.01-2.0   | 11        | 12     | 5.14%   |
| 2.01-3.0   | 3         | 4      | 1.4%    |
| 3.01-4.0   | 2         | 2      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 36.48%  |
| 251-500        | 65        | 27.9%   |
| 501-1000       | 30        | 12.88%  |
| 51-100         | 15        | 6.44%   |
| 21-50          | 12        | 5.15%   |
| 1001-2000      | 10        | 4.29%   |
| 2001-3000      | 6         | 2.58%   |
| 1-20           | 6         | 2.58%   |
| More than 3000 | 4         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 122       | 52.36%  |
| 21-50     | 49        | 21.03%  |
| 51-100    | 27        | 11.59%  |
| 101-250   | 16        | 6.87%   |
| 501-1000  | 7         | 3%      |
| 251-500   | 6         | 2.58%   |
| 1001-2000 | 4         | 1.72%   |
| 2001-3000 | 2         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 7.14%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 7.14%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 7.14%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1      | 7.14%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 7.14%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 7.14%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 7.14%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 7.14%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 7.14%   |
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9SA00 250GB       | 1         | 1      | 7.14%   |
| Crucial CT256M550SSD1 256GB         | 1         | 1      | 7.14%   |
| Apple HDD HTS541010A9E662 1TB       | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 35.71%  |
| Seagate             | 3         | 3      | 21.43%  |
| Toshiba             | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Seagate             | 3         | 3      | 25%     |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 83.33%  |
| SSD  | 2         | 2      | 16.67%  |

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
| Detected | 194       | 311    | 81.17%  |
| Works    | 34        | 44     | 14.23%  |
| Malfunc  | 11        | 14     | 4.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 166       | 56.46%  |
| AMD                          | 39        | 13.27%  |
| Samsung Electronics          | 33        | 11.22%  |
| SanDisk                      | 18        | 6.12%   |
| Phison Electronics           | 5         | 1.7%    |
| Micron Technology            | 4         | 1.36%   |
| Toshiba America Info Systems | 3         | 1.02%   |
| SK hynix                     | 3         | 1.02%   |
| Marvell Technology Group     | 3         | 1.02%   |
| KIOXIA                       | 3         | 1.02%   |
| Kingston Technology Company  | 3         | 1.02%   |
| Silicon Motion               | 2         | 0.68%   |
| Nvidia                       | 2         | 0.68%   |
| Micron/Crucial Technology    | 2         | 0.68%   |
| JMicron Technology           | 2         | 0.68%   |
| ASMedia Technology           | 2         | 0.68%   |
| VIA Technologies             | 1         | 0.34%   |
| Seagate Technology           | 1         | 0.34%   |
| LSI Logic / Symbios Logic    | 1         | 0.34%   |
| Broadcom / LSI               | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 8.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 3.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 3.03%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.42%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 1.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 5         | 1.52%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.21%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.21%   |
| SK hynix Gold P31 SSD                                                                   | 3         | 0.91%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.91%   |
| Samsung Electronics SATA controller                                                     | 3         | 0.91%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.91%   |
| Intel SSD 660P Series                                                                   | 3         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 0.91%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.61%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.61%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.61%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.61%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 0.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 168       | 57.93%  |
| NVMe | 70        | 24.14%  |
| RAID | 26        | 8.97%   |
| IDE  | 24        | 8.28%   |
| SAS  | 1         | 0.34%   |
| SCSI | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 184       | 79.65%  |
| AMD    | 47        | 20.35%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.6%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 2.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.73%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 1.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.3%    |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 1.3%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.87%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.87%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.87%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 0.87%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.87%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 0.87%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.87%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2         | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.87%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 0.87%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 0.87%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2         | 0.87%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 0.87%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.43%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1         | 0.43%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1         | 0.43%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.43%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.43%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.43%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.43%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.43%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1         | 0.43%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.43%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.43%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.43%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.43%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.43%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.43%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.43%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.43%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.43%   |
| Intel Core i7-5557U CPU @ 3.10GHz           | 1         | 0.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 25.54%  |
| Intel Core i7           | 42        | 18.18%  |
| Intel Core i3           | 22        | 9.52%   |
| Other                   | 15        | 6.49%   |
| Intel Celeron           | 14        | 6.06%   |
| AMD Ryzen 7             | 12        | 5.19%   |
| AMD Ryzen 5             | 12        | 5.19%   |
| Intel Pentium           | 11        | 4.76%   |
| Intel Core 2 Duo        | 7         | 3.03%   |
| Intel Xeon              | 5         | 2.16%   |
| AMD FX                  | 3         | 1.3%    |
| Intel Pentium Silver    | 2         | 0.87%   |
| Intel Pentium Dual-Core | 2         | 0.87%   |
| Intel Core 2            | 2         | 0.87%   |
| AMD Ryzen 9             | 2         | 0.87%   |
| AMD A8                  | 2         | 0.87%   |
| AMD A6                  | 2         | 0.87%   |
| AMD A4                  | 2         | 0.87%   |
| Intel Pentium Dual      | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Celeron M         | 1         | 0.43%   |
| AMD Ryzen 7 PRO         | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Ryzen 3             | 1         | 0.43%   |
| AMD Phenom II X4        | 1         | 0.43%   |
| AMD Phenom II           | 1         | 0.43%   |
| AMD Phenom              | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD C-60                | 1         | 0.43%   |
| AMD C-50                | 1         | 0.43%   |
| AMD Athlon II X4        | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 106       | 45.89%  |
| 4      | 74        | 32.03%  |
| 6      | 25        | 10.82%  |
| 8      | 18        | 7.79%   |
| 12     | 4         | 1.73%   |
| 1      | 3         | 1.3%    |
| 3      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 228       | 98.7%   |
| 2      | 3         | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 158       | 68.4%   |
| 1      | 73        | 31.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 231       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 23        | 9.83%   |
| Unknown    | 18        | 7.69%   |
| 0x306c3    | 12        | 5.13%   |
| 0x306a9    | 12        | 5.13%   |
| 0x806c1    | 11        | 4.7%    |
| 0x406e3    | 10        | 4.27%   |
| 0x20655    | 7         | 2.99%   |
| 0x906e9    | 6         | 2.56%   |
| 0x806ea    | 6         | 2.56%   |
| 0x40651    | 6         | 2.56%   |
| 0x306d4    | 6         | 2.56%   |
| 0x20652    | 6         | 2.56%   |
| 0x1067a    | 6         | 2.56%   |
| 0x08701021 | 6         | 2.56%   |
| 0x806e9    | 5         | 2.14%   |
| 0x906ea    | 4         | 1.71%   |
| 0x30678    | 4         | 1.71%   |
| 0x0800820d | 4         | 1.71%   |
| 0xa0671    | 3         | 1.28%   |
| 0x806ec    | 3         | 1.28%   |
| 0x706a8    | 3         | 1.28%   |
| 0x6fb      | 3         | 1.28%   |
| 0x406c4    | 3         | 1.28%   |
| 0x08600104 | 3         | 1.28%   |
| 0xa0655    | 2         | 0.85%   |
| 0xa0653    | 2         | 0.85%   |
| 0xa0652    | 2         | 0.85%   |
| 0x806eb    | 2         | 0.85%   |
| 0x706a1    | 2         | 0.85%   |
| 0x6fd      | 2         | 0.85%   |
| 0x506e3    | 2         | 0.85%   |
| 0x406c3    | 2         | 0.85%   |
| 0x40661    | 2         | 0.85%   |
| 0x206d7    | 2         | 0.85%   |
| 0x106a5    | 2         | 0.85%   |
| 0x08701013 | 2         | 0.85%   |
| 0x08101007 | 2         | 0.85%   |
| 0x07030105 | 2         | 0.85%   |
| 0x0600611a | 2         | 0.85%   |
| 0x06000852 | 2         | 0.85%   |
| 0x05000119 | 2         | 0.85%   |
| 0x906ed    | 1         | 0.43%   |
| 0x906eb    | 1         | 0.43%   |
| 0x806d1    | 1         | 0.43%   |
| 0x706e5    | 1         | 0.43%   |
| 0x6fa      | 1         | 0.43%   |
| 0x6f6      | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |
| 0x40671    | 1         | 0.43%   |
| 0x306e4    | 1         | 0.43%   |
| 0x206c2    | 1         | 0.43%   |
| 0x106e5    | 1         | 0.43%   |
| 0x10676    | 1         | 0.43%   |
| 0x0a50000c | 1         | 0.43%   |
| 0x0a201016 | 1         | 0.43%   |
| 0x08608103 | 1         | 0.43%   |
| 0x08600106 | 1         | 0.43%   |
| 0x08600103 | 1         | 0.43%   |
| 0x08108109 | 1         | 0.43%   |
| 0x08101016 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 13.85%  |
| SandyBridge   | 28        | 12.12%  |
| Haswell       | 20        | 8.66%   |
| Zen 2         | 14        | 6.06%   |
| Westmere      | 14        | 6.06%   |
| Skylake       | 14        | 6.06%   |
| IvyBridge     | 13        | 5.63%   |
| TigerLake     | 11        | 4.76%   |
| Silvermont    | 10        | 4.33%   |
| Penryn        | 7         | 3.03%   |
| Core          | 7         | 3.03%   |
| Broadwell     | 7         | 3.03%   |
| Zen+          | 6         | 2.6%    |
| CometLake     | 6         | 2.6%    |
| Zen           | 5         | 2.16%   |
| Icelake       | 5         | 2.16%   |
| Goldmont plus | 5         | 2.16%   |
| K10           | 4         | 1.73%   |
| Zen 3         | 3         | 1.3%    |
| Piledriver    | 3         | 1.3%    |
| Nehalem       | 3         | 1.3%    |
| Excavator     | 3         | 1.3%    |
| Bobcat        | 3         | 1.3%    |
| Puma          | 2         | 0.87%   |
| Jaguar        | 2         | 0.87%   |
| Unknown       | 2         | 0.87%   |
| Goldmont      | 1         | 0.43%   |
| Bulldozer     | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 148       | 54.81%  |
| Nvidia           | 60        | 22.22%  |
| AMD              | 60        | 22.22%  |
| Conexant Systems | 1         | 0.37%   |
| ATI Technologies | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 7.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 4.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.18%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.18%   |
| AMD Renoir                                                                               | 6         | 2.18%   |
| Intel HD Graphics 630                                                                    | 5         | 1.82%   |
| Intel HD Graphics 620                                                                    | 5         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.45%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.09%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.73%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.73%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.73%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.73%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.73%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.73%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.73%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 2         | 0.73%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.73%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.73%   |
| AMD RS780D [Radeon HD 3300]                                                              | 2         | 0.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.73%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2         | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.73%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.73%   |
| AMD Cezanne                                                                              | 2         | 0.73%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.36%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.36%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.36%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.36%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.36%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.36%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 113       | 48.92%  |
| 1 x AMD                        | 48        | 20.78%  |
| 1 x Nvidia                     | 30        | 12.99%  |
| Intel + Nvidia                 | 28        | 12.12%  |
| Intel + AMD                    | 6         | 2.6%    |
| 2 x AMD                        | 3         | 1.3%    |
| AMD + Nvidia                   | 2         | 0.87%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 203       | 86.75%  |
| Proprietary | 27        | 11.54%  |
| Unknown     | 4         | 1.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 57.51%  |
| 1.01-2.0   | 25        | 10.73%  |
| 0.01-0.5   | 21        | 9.01%   |
| 0.51-1.0   | 18        | 7.73%   |
| 3.01-4.0   | 15        | 6.44%   |
| 7.01-8.0   | 13        | 5.58%   |
| 5.01-6.0   | 3         | 1.29%   |
| 2.01-3.0   | 2         | 0.86%   |
| 8.01-16.0  | 2         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 12%     |
| Samsung Electronics     | 27        | 10.8%   |
| LG Display              | 24        | 9.6%    |
| Chimei Innolux          | 24        | 9.6%    |
| BOE                     | 20        | 8%      |
| Hewlett-Packard         | 15        | 6%      |
| Apple                   | 15        | 6%      |
| Goldstar                | 10        | 4%      |
| Lenovo                  | 9         | 3.6%    |
| Dell                    | 9         | 3.6%    |
| BenQ                    | 7         | 2.8%    |
| Acer                    | 7         | 2.8%    |
| AOC                     | 6         | 2.4%    |
| Sharp                   | 5         | 2%      |
| Ancor Communications    | 5         | 2%      |
| Chi Mei Optoelectronics | 4         | 1.6%    |
| Vizio                   | 3         | 1.2%    |
| ViewSonic               | 3         | 1.2%    |
| CPT                     | 3         | 1.2%    |
| MSI                     | 2         | 0.8%    |
| LG Electronics          | 2         | 0.8%    |
| CSO                     | 2         | 0.8%    |
| Toshiba                 | 1         | 0.4%    |
| TBD                     | 1         | 0.4%    |
| SKY                     | 1         | 0.4%    |
| Seiko/Epson             | 1         | 0.4%    |
| Philips                 | 1         | 0.4%    |
| PANDA                   | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| NEC Computers           | 1         | 0.4%    |
| LGD                     | 1         | 0.4%    |
| LG Philips              | 1         | 0.4%    |
| Lenovo Group Limited    | 1         | 0.4%    |
| HOP                     | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| Grundig                 | 1         | 0.4%    |
| Denver                  | 1         | 0.4%    |
| AUS                     | 1         | 0.4%    |
| ASUSTek Computer        | 1         | 0.4%    |
| Unknown                 | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.95%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.56%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.78%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x174mm 14.0-inch           | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.78%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 0.78%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 0.78%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.78%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 0.78%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.78%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                        | 2         | 0.78%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                        | 1         | 0.39%   |
| Vizio L37 HD VIZ1300 1366x768 820x460mm 37.0-inch                        | 1         | 0.39%   |
| Vizio E321VL VIZ0083 1920x1080 700x400mm 31.7-inch                       | 1         | 0.39%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch            | 1         | 0.39%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.39%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch            | 1         | 0.39%   |
| Toshiba TV TSB0206 1920x1080                                             | 1         | 0.39%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 0.39%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                     | 1         | 0.39%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch                  | 1         | 0.39%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.39%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch     | 1         | 0.39%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch        | 1         | 0.39%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch        | 1         | 0.39%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch   | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor S24F350                                  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                        | 1         | 0.39%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch       | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 95        | 39.92%  |
| 1366x768 (WXGA)    | 54        | 22.69%  |
| 1600x900 (HD+)     | 14        | 5.88%   |
| 3840x2160 (4K)     | 13        | 5.46%   |
| 2560x1440 (QHD)    | 10        | 4.2%    |
| 1280x800 (WXGA)    | 9         | 3.78%   |
| 1440x900 (WXGA+)   | 8         | 3.36%   |
| 2560x1600          | 5         | 2.1%    |
| 1920x1200 (WUXGA)  | 5         | 2.1%    |
| 1680x1050 (WSXGA+) | 5         | 2.1%    |
| Unknown            | 4         | 1.68%   |
| 3840x1080          | 3         | 1.26%   |
| 2560x1080          | 3         | 1.26%   |
| 5760x1080          | 1         | 0.42%   |
| 5120x1440          | 1         | 0.42%   |
| 4480x1440          | 1         | 0.42%   |
| 3840x2400          | 1         | 0.42%   |
| 3440x1440          | 1         | 0.42%   |
| 3000x2000          | 1         | 0.42%   |
| 2880x1800          | 1         | 0.42%   |
| 2736x1824          | 1         | 0.42%   |
| 2160x1440          | 1         | 0.42%   |
| 1280x1024 (SXGA)   | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 27.13%  |
| 13      | 29        | 11.74%  |
| 27      | 21        | 8.5%    |
| 14      | 21        | 8.5%    |
| 21      | 16        | 6.48%   |
| 23      | 14        | 5.67%   |
| 17      | 12        | 4.86%   |
| Unknown | 12        | 4.86%   |
| 24      | 8         | 3.24%   |
| 12      | 8         | 3.24%   |
| 11      | 6         | 2.43%   |
| 20      | 4         | 1.62%   |
| 19      | 4         | 1.62%   |
| 54      | 3         | 1.21%   |
| 31      | 3         | 1.21%   |
| 49      | 2         | 0.81%   |
| 34      | 2         | 0.81%   |
| 10      | 2         | 0.81%   |
| 74      | 1         | 0.4%    |
| 72      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 33      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 22      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 41.32%  |
| 501-600     | 36        | 14.88%  |
| 201-300     | 33        | 13.64%  |
| 401-500     | 25        | 10.33%  |
| 351-400     | 13        | 5.37%   |
| Unknown     | 12        | 4.96%   |
| 601-700     | 10        | 4.13%   |
| 1001-1500   | 5         | 2.07%   |
| 701-800     | 4         | 1.65%   |
| 801-900     | 2         | 0.83%   |
| 1501-2000   | 2         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 75.56%  |
| 16/10   | 31        | 13.78%  |
| Unknown | 12        | 5.33%   |
| 3/2     | 5         | 2.22%   |
| 21/9    | 4         | 1.78%   |
| 32/9    | 2         | 0.89%   |
| 5/4     | 1         | 0.44%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 27.24%  |
| 81-90          | 37        | 15.04%  |
| 201-250        | 31        | 12.6%   |
| 301-350        | 23        | 9.35%   |
| 71-80          | 13        | 5.28%   |
| 151-200        | 13        | 5.28%   |
| Unknown        | 12        | 4.88%   |
| 61-70          | 8         | 3.25%   |
| 121-130        | 8         | 3.25%   |
| 351-500        | 7         | 2.85%   |
| 51-60          | 6         | 2.44%   |
| More than 1000 | 5         | 2.03%   |
| 251-300        | 4         | 1.63%   |
| 501-1000       | 4         | 1.63%   |
| 131-140        | 3         | 1.22%   |
| 41-50          | 2         | 0.81%   |
| 141-150        | 2         | 0.81%   |
| 111-120        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 30.67%  |
| 101-120       | 72        | 30.25%  |
| 51-100        | 57        | 23.95%  |
| 161-240       | 13        | 5.46%   |
| Unknown       | 12        | 5.04%   |
| 1-50          | 6         | 2.52%   |
| More than 240 | 5         | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 197       | 84.91%  |
| 2     | 23        | 9.91%   |
| 3     | 7         | 3.02%   |
| 0     | 5         | 2.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 132       | 36.67%  |
| Intel                             | 98        | 27.22%  |
| Qualcomm Atheros                  | 34        | 9.44%   |
| Broadcom                          | 33        | 9.17%   |
| TP-Link                           | 10        | 2.78%   |
| Broadcom Limited                  | 8         | 2.22%   |
| Ralink Technology                 | 6         | 1.67%   |
| Xiaomi                            | 4         | 1.11%   |
| Ralink                            | 4         | 1.11%   |
| Marvell Technology Group          | 4         | 1.11%   |
| Sierra Wireless                   | 3         | 0.83%   |
| MediaTek                          | 3         | 0.83%   |
| Samsung Electronics               | 2         | 0.56%   |
| Hewlett-Packard                   | 2         | 0.56%   |
| Realtek                           | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| NetGear                           | 1         | 0.28%   |
| NEC Computers                     | 1         | 0.28%   |
| LSI                               | 1         | 0.28%   |
| Linksys                           | 1         | 0.28%   |
| Huawei Technologies               | 1         | 0.28%   |
| Google                            | 1         | 0.28%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |
| Edimax Technology                 | 1         | 0.28%   |
| DisplayLink                       | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| Attansic Technology               | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85        | 20.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.03%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.66%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.42%   |
| Intel Wireless 8260                                               | 6         | 1.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.18%   |
| Intel Wireless 7265                                               | 5         | 1.18%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.95%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.95%   |
| Intel Wireless 7260                                               | 4         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.71%   |
| Intel Wireless 3160                                               | 3         | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.71%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.47%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.47%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.47%   |
| MediaTek TECNO SPARK 3                                            | 2         | 0.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.47%   |
| Intel Wireless 3165                                               | 2         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.47%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.47%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 80        | 37.56%  |
| Realtek Semiconductor    | 39        | 18.31%  |
| Broadcom                 | 29        | 13.62%  |
| Qualcomm Atheros         | 28        | 13.15%  |
| TP-Link                  | 10        | 4.69%   |
| Ralink Technology        | 6         | 2.82%   |
| Broadcom Limited         | 6         | 2.82%   |
| Ralink                   | 4         | 1.88%   |
| Sierra Wireless          | 3         | 1.41%   |
| Marvell Technology Group | 2         | 0.94%   |
| Realtek                  | 1         | 0.47%   |
| NetGear                  | 1         | 0.47%   |
| MediaTek                 | 1         | 0.47%   |
| Edimax Technology        | 1         | 0.47%   |
| D-Link                   | 1         | 0.47%   |
| ASUSTek Computer         | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 5.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.29%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.82%   |
| Intel Wireless 8260                                            | 6         | 2.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.35%   |
| Intel Wireless 7265                                            | 5         | 2.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.35%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.88%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.88%   |
| Intel Wireless 7260                                            | 4         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.41%   |
| Intel Wireless 3160                                            | 3         | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.41%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.94%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.94%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.94%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 0.94%   |
| Intel Wireless 3165                                            | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.94%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.94%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.47%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.47%   |
| Sierra Wireless EM7455                                         | 1         | 0.47%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.47%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.47%   |
| Realtek 802.11ac NIC                                           | 1         | 0.47%   |
| Realtek 802.11n NIC                                            | 1         | 0.47%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 55.22%  |
| Intel                    | 44        | 21.89%  |
| Broadcom                 | 14        | 6.97%   |
| Qualcomm Atheros         | 11        | 5.47%   |
| Xiaomi                   | 4         | 1.99%   |
| Samsung Electronics      | 2         | 1%      |
| MediaTek                 | 2         | 1%      |
| Marvell Technology Group | 2         | 1%      |
| Broadcom Limited         | 2         | 1%      |
| Qualcomm                 | 1         | 0.5%    |
| OPPO Electronics         | 1         | 0.5%    |
| Nvidia                   | 1         | 0.5%    |
| LSI                      | 1         | 0.5%    |
| Linksys                  | 1         | 0.5%    |
| Google                   | 1         | 0.5%    |
| DisplayLink              | 1         | 0.5%    |
| Attansic Technology      | 1         | 0.5%    |
| ASIX Electronics         | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85        | 41.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.45%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.45%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.47%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.98%   |
| MediaTek TECNO SPARK 3                                            | 2         | 0.98%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.49%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.49%   |
| OPPO Find X2 Lite                                                 | 1         | 0.49%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 0.49%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.49%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.49%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.49%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 0.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.49%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.49%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.49%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.49%   |
| ASIX AX88772B                                                     | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 50.13%  |
| Ethernet | 190       | 48.59%  |
| Modem    | 4         | 1.02%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 67.81%  |
| Ethernet | 75        | 32.19%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 132       | 57.14%  |
| 1     | 95        | 41.13%  |
| 3     | 3         | 1.3%    |
| 0     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 73.28%  |
| Yes  | 62        | 26.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 38.82%  |
| Realtek Semiconductor           | 23        | 13.53%  |
| Apple                           | 17        | 10%     |
| Qualcomm Atheros Communications | 15        | 8.82%   |
| Broadcom                        | 13        | 7.65%   |
| Cambridge Silicon Radio         | 12        | 7.06%   |
| Lite-On Technology              | 5         | 2.94%   |
| Foxconn / Hon Hai               | 4         | 2.35%   |
| IMC Networks                    | 3         | 1.76%   |
| Ralink                          | 2         | 1.18%   |
| Marvell Semiconductor           | 2         | 1.18%   |
| Dell                            | 2         | 1.18%   |
| Toshiba                         | 1         | 0.59%   |
| Realtek                         | 1         | 0.59%   |
| Qcom                            | 1         | 0.59%   |
| Hewlett-Packard                 | 1         | 0.59%   |
| Belkin Components               | 1         | 0.59%   |
| ASUSTek Computer                | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 14.71%  |
| Realtek Bluetooth Radio                             | 13        | 7.65%   |
| Intel Bluetooth Device                              | 12        | 7.06%   |
| Intel AX200 Bluetooth                               | 12        | 7.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 7.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 5.29%   |
| Apple Bluetooth USB Host Controller                 | 8         | 4.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.12%   |
| Apple Bluetooth Host Controller                     | 7         | 4.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 3.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.76%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.18%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.18%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.59%   |
| Realtek Bluetooth Radio                             | 1         | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.59%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.59%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.59%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.59%   |
| Lite-On Wireless_Device                             | 1         | 0.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.59%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.59%   |
| Lite-On Bluetooth Device                            | 1         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.59%   |
| Intel AX210 Bluetooth                               | 1         | 0.59%   |
| IMC Networks BCM20702A0                             | 1         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.59%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.59%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.59%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.59%   |
| Broadcom HP Portable Valentine                      | 1         | 0.59%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.59%   |
| Broadcom BCM20702A0                                 | 1         | 0.59%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 0.59%   |
| ASUS Bluetooth Radio                                | 1         | 0.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.59%   |
| Apple Bluetooth HCI                                 | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 181       | 58.01%  |
| AMD                                  | 61        | 19.55%  |
| Nvidia                               | 42        | 13.46%  |
| C-Media Electronics                  | 7         | 2.24%   |
| Logitech                             | 3         | 0.96%   |
| Generalplus Technology               | 3         | 0.96%   |
| Creative Labs                        | 3         | 0.96%   |
| JMTek                                | 2         | 0.64%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.32%   |
| TEAC                                 | 1         | 0.32%   |
| Razer USA                            | 1         | 0.32%   |
| GN Netcom                            | 1         | 0.32%   |
| Focusrite-Novation                   | 1         | 0.32%   |
| Creative Technology                  | 1         | 0.32%   |
| Corsair                              | 1         | 0.32%   |
| BY EDIFIER                           | 1         | 0.32%   |
| ATI Technologies                     | 1         | 0.32%   |
| ASUSTek Computer                     | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 6.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 6.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 4.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 3.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.95%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.88%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.34%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.34%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.34%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.07%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.8%    |
| Generalplus Technology IMYB 7.1 Channel                                                           | 3         | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.54%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.54%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 2         | 0.54%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 2         | 0.54%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.54%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 0.27%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.27%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 24.68%  |
| SK hynix            | 14        | 18.18%  |
| Kingston            | 12        | 15.58%  |
| Micron Technology   | 10        | 12.99%  |
| Unknown             | 3         | 3.9%    |
| G.Skill             | 3         | 3.9%    |
| Crucial             | 3         | 3.9%    |
| Ramaxel Technology  | 2         | 2.6%    |
| Corsair             | 2         | 2.6%    |
| A-DATA Technology   | 2         | 2.6%    |
| Toshiba             | 1         | 1.3%    |
| Qimonda             | 1         | 1.3%    |
| Neo Forza           | 1         | 1.3%    |
| Nanya Technology    | 1         | 1.3%    |
| Kllisre             | 1         | 1.3%    |
| GSkill              | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 3.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 2.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 2.5%    |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 1.25%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s            | 1         | 1.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s       | 1         | 1.25%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s        | 1         | 1.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.25%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s  | 1         | 1.25%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s     | 1         | 1.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1.25%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471B2873FHS-CF8 1024MB SODIMM DDR3 1067MT/s    | 1         | 1.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.25%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s       | 1         | 1.25%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s        | 1         | 1.25%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.25%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 1         | 1.25%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s      | 1         | 1.25%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s       | 1         | 1.25%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 1.25%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s        | 1         | 1.25%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s       | 1         | 1.25%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM 1334MT/s           | 1         | 1.25%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Kllisre RAM KRE-D3S1600M/8G 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.25%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s         | 1         | 1.25%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s       | 1         | 1.25%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s         | 1         | 1.25%   |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.25%   |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s           | 1         | 1.25%   |
| Kingston RAM 99U5458-001.A00LF 2GB DIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 48.33%  |
| DDR3   | 25        | 41.67%  |
| SDRAM  | 2         | 3.33%   |
| LPDDR4 | 2         | 3.33%   |
| DDR2   | 2         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 72.58%  |
| DIMM         | 13        | 20.97%  |
| Row Of Chips | 2         | 3.23%   |
| Chip         | 2         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 36.23%  |
| 4096  | 21        | 30.43%  |
| 2048  | 11        | 15.94%  |
| 16384 | 10        | 14.49%  |
| 1024  | 2         | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 26.47%  |
| 3200  | 12        | 17.65%  |
| 2667  | 11        | 16.18%  |
| 2400  | 4         | 5.88%   |
| 2133  | 4         | 5.88%   |
| 1333  | 4         | 5.88%   |
| 1867  | 3         | 4.41%   |
| 3600  | 2         | 2.94%   |
| 4267  | 1         | 1.47%   |
| 4199  | 1         | 1.47%   |
| 3007  | 1         | 1.47%   |
| 3000  | 1         | 1.47%   |
| 2666  | 1         | 1.47%   |
| 2048  | 1         | 1.47%   |
| 1334  | 1         | 1.47%   |
| 1067  | 1         | 1.47%   |
| 1066  | 1         | 1.47%   |
| 800   | 1         | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet M101-M106    | 1         | 25%     |
| HP Deskjet F4500 series  | 1         | 25%     |
| Brother MFC-T800W        | 1         | 25%     |
| Brother HL-4140CN series | 1         | 25%     |

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
| Chicony Electronics                    | 39        | 25%     |
| Microdia                               | 14        | 8.97%   |
| Realtek Semiconductor                  | 13        | 8.33%   |
| Apple                                  | 13        | 8.33%   |
| Acer                                   | 10        | 6.41%   |
| Quanta                                 | 9         | 5.77%   |
| Logitech                               | 9         | 5.77%   |
| Sunplus Innovation Technology          | 8         | 5.13%   |
| Suyin                                  | 7         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.49%   |
| Syntek                                 | 4         | 2.56%   |
| Lenovo                                 | 4         | 2.56%   |
| Microsoft                              | 3         | 1.92%   |
| Luxvisions Innotech Limited            | 3         | 1.92%   |
| Lite-On Technology                     | 3         | 1.92%   |
| IMC Networks                           | 3         | 1.92%   |
| Z-Star Microelectronics                | 1         | 0.64%   |
| Primax Electronics                     | 1         | 0.64%   |
| Importek                               | 1         | 0.64%   |
| icSpring                               | 1         | 0.64%   |
| Generalplus Technology                 | 1         | 0.64%   |
| Creative Technology                    | 1         | 0.64%   |
| 2M UVC CAMERA                          | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 5.06%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.53%   |
| Chicony HD WebCam                                   | 4         | 2.53%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 2.53%   |
| Apple FaceTime HD Camera                            | 4         | 2.53%   |
| Suyin 1.3M HD WebCam                                | 3         | 1.9%    |
| Realtek HD WebCam                                   | 3         | 1.9%    |
| Quanta HP TrueVision HD Camera                      | 3         | 1.9%    |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.9%    |
| Chicony HP Truevision HD                            | 3         | 1.9%    |
| Chicony HP HD Webcam [Fixed]                        | 3         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.9%    |
| Acer Lenovo EasyCamera                              | 3         | 1.9%    |
| Syntek Integrated Camera                            | 2         | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 2         | 1.27%   |
| Realtek USB Camera                                  | 2         | 1.27%   |
| Microdia Webcam Vitade AF                           | 2         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.27%   |
| Microdia Integrated Webcam HD                       | 2         | 1.27%   |
| Logitech Webcam C270                                | 2         | 1.27%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.27%   |
| Lite-On Integrated Camera                           | 2         | 1.27%   |
| Lenovo Integrated Webcam                            | 2         | 1.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.27%   |
| Chicony USB2.0 Camera                               | 2         | 1.27%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.27%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.27%   |
| Apple Built-in iSight                               | 2         | 1.27%   |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.63%   |
| Syntek USB2.0 Camera                                | 1         | 0.63%   |
| Syntek EasyCamera                                   | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.63%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_1.3M               | 1         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.63%   |
| Sunplus FHD Camera Microphone                       | 1         | 0.63%   |
| Sunplus Aukey-PC-LM1E Camera                        | 1         | 0.63%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.63%   |
| Realtek Integrated Webcam                           | 1         | 0.63%   |
| Realtek Integrated Camera                           | 1         | 0.63%   |
| Realtek HP Truevision HD                            | 1         | 0.63%   |
| Quanta ov9734_techfront_camera                      | 1         | 0.63%   |
| Quanta HP Webcam                                    | 1         | 0.63%   |
| Quanta HP TrueVision HD Webcam                      | 1         | 0.63%   |
| Quanta HP 5M Camera                                 | 1         | 0.63%   |
| Quanta HD User Facing                               | 1         | 0.63%   |
| Quanta HD Camera                                    | 1         | 0.63%   |
| Primax Villem                                       | 1         | 0.63%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.63%   |
| Microsoft LifeCam Rear                              | 1         | 0.63%   |
| Microsoft LifeCam HD-3000                           | 1         | 0.63%   |
| Microsoft LifeCam Front                             | 1         | 0.63%   |
| Microdia USB 2.0 Camera                             | 1         | 0.63%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 42.42%  |
| Synaptics                  | 4         | 12.12%  |
| Upek                       | 3         | 9.09%   |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| LighTuning Technology      | 3         | 9.09%   |
| AuthenTec                  | 3         | 9.09%   |
| STMicroelectronics         | 1         | 3.03%   |
| Focal-systems.Corp         | 1         | 3.03%   |
| Elan Microelectronics      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.03%   |
| Validity Sensors VFS491                                                    | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 3.03%   |
| Synaptics  WBDI                                                            | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.03%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.03%   |
| AuthenTec AES2810                                                          | 1         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 3.03%   |
| Unknown                                                                    | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 164       | 70.69%  |
| 1     | 56        | 24.14%  |
| 2     | 11        | 4.74%   |
| 3     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 39.76%  |
| Net/wireless             | 16        | 19.28%  |
| Graphics card            | 12        | 14.46%  |
| Multimedia controller    | 8         | 9.64%   |
| Chipcard                 | 5         | 6.02%   |
| Sound                    | 2         | 2.41%   |
| Net/ethernet             | 2         | 2.41%   |
| Bluetooth                | 2         | 2.41%   |
| Storage                  | 1         | 1.2%    |
| Communication controller | 1         | 1.2%    |
| Camera                   | 1         | 1.2%    |

