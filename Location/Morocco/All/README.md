Linux in Morocco - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Morocco/Desktop/README.md) and [notebooks](/Location/Morocco/Notebook/README.md).

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

Total: 272

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | Notebook    | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [45ad38e728](https://linux-hardware.org/?probe=45ad38e728) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d809b304eb](https://linux-hardware.org/?probe=d809b304eb) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | Notebook    | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| HP            | 18E4                        | Desktop     | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | Notebook    | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | Notebook    | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | 3396                        | Desktop     | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| HP            | 1589                        | Desktop     | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | Notebook    | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| HP            | 8054                        | Desktop     | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | Desktop     | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8a415c9db8](https://linux-hardware.org/?probe=8a415c9db8) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3027f5288e](https://linux-hardware.org/?probe=3027f5288e) | Dec 04, 2021 |
| HP            | 1998                        | Desktop     | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | Notebook    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| Apple         | MacBookPro13,3              | Notebook    | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | 1589                        | Desktop     | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | Notebook    | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | Notebook    | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| HP            | 3032h                       | Desktop     | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | Notebook    | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| HP            | 18E7                        | Desktop     | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [99c878cd5e](https://linux-hardware.org/?probe=99c878cd5e) | Sep 04, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | 0AACh                       | Desktop     | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | Desktop     | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 15                          | Notebook    | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| HP            | 339A                        | Desktop     | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | Desktop     | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | Desktop     | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | Desktop     | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| Foxconn       | 2ACA                        | Desktop     | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | Notebook    | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | Desktop     | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| HP            | Notebook                    | Notebook    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | Notebook    | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | Notebook    | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| Acer          | AO722                       | Notebook    | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | Notebook    | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| HP            | 158A                        | Desktop     | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| Dell          | Latitude E6440              | Notebook    | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 650                         | Notebook    | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | Notebook    | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | Notebook    | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| Dell          | Latitude E6440              | Notebook    | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| Dell          | 0MWYPT A01                  | Desktop     | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | Notebook    | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| HP            | 3398                        | Desktop     | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| Dell          | Latitude E5270              | Notebook    | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| HP            | 3397                        | Desktop     | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | Notebook    | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | Notebook    | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | Notebook    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| HP            | 0A04h                       | Desktop     | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | Desktop     | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | Notebook    | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 3397                        | Desktop     | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 250 G3                      | Notebook    | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | Notebook    | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Unknown       | Unknown                     | Phone       | [4ff689998e](https://linux-hardware.org/?probe=4ff689998e) | Feb 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | Notebook    | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | Notebook    | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | Notebook    | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | Notebook    | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| HP            | 1494                        | Desktop     | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | Notebook    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | Notebook    | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | Notebook    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Dell          | 0D28YY A03                  | Desktop     | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | Notebook    | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| ASUSTek       | F5VL                        | Notebook    | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |
| Dell          | 0DR845                      | Desktop     | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 42        | 21.11%  |
| Ubuntu 18.04       | 16        | 8.04%   |
| OpenMandriva 4.2   | 12        | 6.03%   |
| KDE neon 20.04     | 8         | 4.02%   |
| Linux Mint 20.2    | 7         | 3.52%   |
| Debian 11          | 6         | 3.02%   |
| Ubuntu 20.10       | 5         | 2.51%   |
| Ubuntu 16.04       | 5         | 2.51%   |
| OpenMandriva 4.3   | 5         | 2.51%   |
| Linux Mint 20.3    | 5         | 2.51%   |
| Fedora 33          | 5         | 2.51%   |
| Zorin 16           | 4         | 2.01%   |
| Ubuntu 19.10       | 4         | 2.01%   |
| OpenMandriva 4.50  | 4         | 2.01%   |
| ArcoLinux Rolling  | 4         | 2.01%   |
| Ubuntu 22.04       | 3         | 1.51%   |
| Linux Mint 19.3    | 3         | 1.51%   |
| Zorin 15           | 2         | 1.01%   |
| Ubuntu 21.10       | 2         | 1.01%   |
| Ubuntu 21.04       | 2         | 1.01%   |
| Pop!_OS 22.04      | 2         | 1.01%   |
| Pop!_OS 21.10      | 2         | 1.01%   |
| Pop!_OS 20.10      | 2         | 1.01%   |
| Parrot 5.0         | 2         | 1.01%   |
| Manjaro            | 2         | 1.01%   |
| Kali 2019.4        | 2         | 1.01%   |
| Debian 10          | 2         | 1.01%   |
| Arch               | 2         | 1.01%   |
| Xubuntu 20.04      | 1         | 0.5%    |
| Xubuntu 18.04      | 1         | 0.5%    |
| Xero Rolling       | 1         | 0.5%    |
| Ubuntu MATE 20.04  | 1         | 0.5%    |
| Ubuntu 19.04       | 1         | 0.5%    |
| Ubuntu             | 1         | 0.5%    |
| ROSA R8.1          | 1         | 0.5%    |
| RHEL 8             | 1         | 0.5%    |
| Raspbian 10        | 1         | 0.5%    |
| Pop!_OS 21.04      | 1         | 0.5%    |
| Pear OS 21.04      | 1         | 0.5%    |
| openSUSE Leap-15.2 | 1         | 0.5%    |
| Manjaro 21.1.6     | 1         | 0.5%    |
| Manjaro 21.0.7     | 1         | 0.5%    |
| Manjaro 20.1       | 1         | 0.5%    |
| Lubuntu 18.04      | 1         | 0.5%    |
| Linux Mint 20      | 1         | 0.5%    |
| Linux Mint 19.2    | 1         | 0.5%    |
| Kubuntu 21.04      | 1         | 0.5%    |
| Kali Rolling       | 1         | 0.5%    |
| Kali 2021.4        | 1         | 0.5%    |
| Kali 2021.3        | 1         | 0.5%    |
| Kali 2019.1        | 1         | 0.5%    |
| Fedora 35          | 1         | 0.5%    |
| Fedora 34          | 1         | 0.5%    |
| Fedora 32          | 1         | 0.5%    |
| Endless 3.9.5      | 1         | 0.5%    |
| Endless 3.5.1      | 1         | 0.5%    |
| Endless 3.3.20     | 1         | 0.5%    |
| EndeavourOS        | 1         | 0.5%    |
| Elementary 6       | 1         | 0.5%    |
| Elementary 5.1     | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 75        | 39.27%  |
| OpenMandriva | 21        | 10.99%  |
| Linux Mint   | 17        | 8.9%    |
| KDE neon     | 8         | 4.19%   |
| Fedora       | 8         | 4.19%   |
| Debian       | 8         | 4.19%   |
| Pop!_OS      | 7         | 3.66%   |
| Zorin        | 6         | 3.14%   |
| Kali         | 6         | 3.14%   |
| Manjaro      | 5         | 2.62%   |
| ArcoLinux    | 4         | 2.09%   |
| Endless      | 3         | 1.57%   |
| Arch         | 3         | 1.57%   |
| Xubuntu      | 2         | 1.05%   |
| Parrot       | 2         | 1.05%   |
| Elementary   | 2         | 1.05%   |
| Xero         | 1         | 0.52%   |
| Ubuntu MATE  | 1         | 0.52%   |
| ROSA         | 1         | 0.52%   |
| RHEL         | 1         | 0.52%   |
| Raspbian     | 1         | 0.52%   |
| Pear OS      | 1         | 0.52%   |
| openSUSE     | 1         | 0.52%   |
| Lubuntu      | 1         | 0.52%   |
| Kubuntu      | 1         | 0.52%   |
| EndeavourOS  | 1         | 0.52%   |
| CentOS       | 1         | 0.52%   |
| BunsenLabs   | 1         | 0.52%   |
| BlackPanther | 1         | 0.52%   |
| Android      | 1         | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002     | 12        | 5.56%   |
| 5.4.0-58-generic             | 5         | 2.31%   |
| 5.4.0-48-generic             | 5         | 2.31%   |
| 5.16.7-desktop-1omv4003      | 5         | 2.31%   |
| 5.13.0-40-generic            | 5         | 2.31%   |
| 5.8.0-43-generic             | 4         | 1.85%   |
| 5.4.0-42-generic             | 4         | 1.85%   |
| 5.12.4-desktop-1omv4050      | 4         | 1.85%   |
| 5.11.0-37-generic            | 4         | 1.85%   |
| 5.8.0-38-generic             | 3         | 1.39%   |
| 5.3.0-40-generic             | 3         | 1.39%   |
| 5.17.5-76051705-generic      | 3         | 1.39%   |
| 5.8.0-48-generic             | 2         | 0.93%   |
| 5.8.0-33-generic             | 2         | 0.93%   |
| 5.4.0-96-generic             | 2         | 0.93%   |
| 5.4.0-90-generic             | 2         | 0.93%   |
| 5.4.0-88-generic             | 2         | 0.93%   |
| 5.4.0-74-generic             | 2         | 0.93%   |
| 5.4.0-65-generic             | 2         | 0.93%   |
| 5.4.0-59-generic             | 2         | 0.93%   |
| 5.4.0-37-generic             | 2         | 0.93%   |
| 5.4.0-33-generic             | 2         | 0.93%   |
| 5.4.0-29-generic             | 2         | 0.93%   |
| 5.3.0-kali2-686-pae          | 2         | 0.93%   |
| 5.3.0-51-generic             | 2         | 0.93%   |
| 5.3.0-28-generic             | 2         | 0.93%   |
| 5.14.14-arch1-1              | 2         | 0.93%   |
| 5.13.0-27-generic            | 2         | 0.93%   |
| 5.13.0-19-generic            | 2         | 0.93%   |
| 5.11.0-46-generic            | 2         | 0.93%   |
| 5.11.0-36-generic            | 2         | 0.93%   |
| 5.10.0-9-amd64               | 2         | 0.93%   |
| 5.0.0-23-generic             | 2         | 0.93%   |
| 4.15.0-29-generic            | 2         | 0.93%   |
| 5.8.18-300.fc33.x86_64       | 1         | 0.46%   |
| 5.8.15-201.fc32.x86_64       | 1         | 0.46%   |
| 5.8.1-050801-generic         | 1         | 0.46%   |
| 5.8.0-rc6-3.g007dcf0-default | 1         | 0.46%   |
| 5.8.0-7642-generic           | 1         | 0.46%   |
| 5.8.0-63-generic             | 1         | 0.46%   |
| 5.8.0-59-generic             | 1         | 0.46%   |
| 5.8.0-55-generic             | 1         | 0.46%   |
| 5.8.0-41-generic             | 1         | 0.46%   |
| 5.8.0-36-generic             | 1         | 0.46%   |
| 5.8.0-34-generic             | 1         | 0.46%   |
| 5.8.0-29-generic             | 1         | 0.46%   |
| 5.8.0-14-generic             | 1         | 0.46%   |
| 5.7.15-1-MANJARO             | 1         | 0.46%   |
| 5.6.14-desktop-2bP           | 1         | 0.46%   |
| 5.4.0-84-generic             | 1         | 0.46%   |
| 5.4.0-80-generic             | 1         | 0.46%   |
| 5.4.0-70-generic             | 1         | 0.46%   |
| 5.4.0-64-generic             | 1         | 0.46%   |
| 5.4.0-60-generic             | 1         | 0.46%   |
| 5.4.0-56-generic             | 1         | 0.46%   |
| 5.4.0-54-generic             | 1         | 0.46%   |
| 5.4.0-52-generic             | 1         | 0.46%   |
| 5.4.0-47-generic             | 1         | 0.46%   |
| 5.4.0-39-generic             | 1         | 0.46%   |
| 5.4.0-31-generic             | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 41        | 20.5%   |
| 5.8.0    | 18        | 9%      |
| 5.11.0   | 16        | 8%      |
| 4.15.0   | 14        | 7%      |
| 5.3.0    | 12        | 6%      |
| 5.10.14  | 12        | 6%      |
| 5.13.0   | 10        | 5%      |
| 5.10.0   | 8         | 4%      |
| 5.15.0   | 6         | 3%      |
| 5.0.0    | 6         | 3%      |
| 5.16.7   | 5         | 2.5%    |
| 5.12.4   | 4         | 2%      |
| 4.18.0   | 4         | 2%      |
| 5.17.5   | 3         | 1.5%    |
| 5.14.0   | 3         | 1.5%    |
| 4.19.0   | 3         | 1.5%    |
| 5.16.0   | 2         | 1%      |
| 5.14.14  | 2         | 1%      |
| 5.8.18   | 1         | 0.5%    |
| 5.8.15   | 1         | 0.5%    |
| 5.8.1    | 1         | 0.5%    |
| 5.7.15   | 1         | 0.5%    |
| 5.6.14   | 1         | 0.5%    |
| 5.18.1   | 1         | 0.5%    |
| 5.17.9   | 1         | 0.5%    |
| 5.17.1   | 1         | 0.5%    |
| 5.16.2   | 1         | 0.5%    |
| 5.15.4   | 1         | 0.5%    |
| 5.15.23  | 1         | 0.5%    |
| 5.15.21  | 1         | 0.5%    |
| 5.15.15  | 1         | 0.5%    |
| 5.15.12  | 1         | 0.5%    |
| 5.14.16  | 1         | 0.5%    |
| 5.13.19  | 1         | 0.5%    |
| 5.13.10  | 1         | 0.5%    |
| 5.11.8   | 1         | 0.5%    |
| 5.11.7   | 1         | 0.5%    |
| 5.11.14  | 1         | 0.5%    |
| 5.10.88  | 1         | 0.5%    |
| 5.10.87  | 1         | 0.5%    |
| 5.10.7   | 1         | 0.5%    |
| 5.10.42  | 1         | 0.5%    |
| 5.10.15  | 1         | 0.5%    |
| 5.10.11  | 1         | 0.5%    |
| 5.10.103 | 1         | 0.5%    |
| 4.9.41   | 1         | 0.5%    |
| 4.4.0    | 1         | 0.5%    |
| 4.13.0   | 1         | 0.5%    |
| 3.18.35  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 20.6%   |
| 5.10    | 26        | 13.07%  |
| 5.8     | 21        | 10.55%  |
| 5.11    | 19        | 9.55%   |
| 4.15    | 14        | 7.04%   |
| 5.3     | 12        | 6.03%   |
| 5.13    | 12        | 6.03%   |
| 5.15    | 11        | 5.53%   |
| 5.16    | 8         | 4.02%   |
| 5.14    | 6         | 3.02%   |
| 5.0     | 6         | 3.02%   |
| 5.17    | 5         | 2.51%   |
| 5.12    | 4         | 2.01%   |
| 4.18    | 4         | 2.01%   |
| 4.19    | 3         | 1.51%   |
| 5.7     | 1         | 0.5%    |
| 5.6     | 1         | 0.5%    |
| 5.18    | 1         | 0.5%    |
| 4.9     | 1         | 0.5%    |
| 4.4     | 1         | 0.5%    |
| 4.13    | 1         | 0.5%    |
| 3.18    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 178       | 94.68%  |
| i686   | 8         | 4.26%   |
| armv8l | 1         | 0.53%   |
| armv7l | 1         | 0.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 91        | 47.15%  |
| KDE5            | 35        | 18.13%  |
| Unknown         | 15        | 7.77%   |
| XFCE            | 11        | 5.7%    |
| X-Cinnamon      | 11        | 5.7%    |
| KDE             | 8         | 4.15%   |
| Unity           | 4         | 2.07%   |
| MATE            | 4         | 2.07%   |
| LXDE            | 3         | 1.55%   |
| Cinnamon        | 3         | 1.55%   |
| Pantheon        | 2         | 1.04%   |
| xmonad          | 1         | 0.52%   |
| qtile           | 1         | 0.52%   |
| KDE4            | 1         | 0.52%   |
| i3              | 1         | 0.52%   |
| GNOME Flashback | 1         | 0.52%   |
| Budgie          | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 163       | 84.46%  |
| Wayland | 19        | 9.84%   |
| Unknown | 8         | 4.15%   |
| Tty     | 3         | 1.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 96        | 49.23%  |
| SDDM    | 35        | 17.95%  |
| GDM     | 27        | 13.85%  |
| LightDM | 22        | 11.28%  |
| GDM3    | 10        | 5.13%   |
| TDM     | 4         | 2.05%   |
| KDM     | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 99        | 51.83%  |
| fr_FR   | 55        | 28.8%   |
| Unknown | 18        | 9.42%   |
| en_GB   | 8         | 4.19%   |
| de_DE   | 3         | 1.57%   |
| C       | 2         | 1.05%   |
| ar_MA   | 2         | 1.05%   |
| fr_MA   | 1         | 0.52%   |
| fr_CH   | 1         | 0.52%   |
| es_ES   | 1         | 0.52%   |
| ar_EG   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 114       | 60.32%  |
| EFI  | 75        | 39.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 148       | 78.31%  |
| Overlay | 23        | 12.17%  |
| Btrfs   | 11        | 5.82%   |
| Unknown | 5         | 2.65%   |
| Xfs     | 2         | 1.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 55.56%  |
| GPT     | 57        | 30.16%  |
| MBR     | 27        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 85.71%  |
| Yes       | 27        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 58.73%  |
| Yes       | 78        | 41.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 71        | 37.77%  |
| Dell                    | 28        | 14.89%  |
| Lenovo                  | 27        | 14.36%  |
| ASUSTek Computer        | 15        | 7.98%   |
| Toshiba                 | 6         | 3.19%   |
| Acer                    | 6         | 3.19%   |
| Sony                    | 3         | 1.6%    |
| Packard Bell            | 3         | 1.6%    |
| Foxconn                 | 3         | 1.6%    |
| Unknown                 | 3         | 1.6%    |
| Timi                    | 2         | 1.06%   |
| Samsung Electronics     | 2         | 1.06%   |
| Medion                  | 2         | 1.06%   |
| Gigabyte Technology     | 2         | 1.06%   |
| Apple                   | 2         | 1.06%   |
| TUXEDO                  | 1         | 0.53%   |
| TrekStor                | 1         | 0.53%   |
| Razer                   | 1         | 0.53%   |
| Raspberry Pi Foundation | 1         | 0.53%   |
| Pegatron                | 1         | 0.53%   |
| MSI                     | 1         | 0.53%   |
| Mediacom                | 1         | 0.53%   |
| GPD                     | 1         | 0.53%   |
| Google                  | 1         | 0.53%   |
| eMachines               | 1         | 0.53%   |
| ECS                     | 1         | 0.53%   |
| Clevo                   | 1         | 0.53%   |
| American Megatrends     | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 2.13%   |
| HP EliteBook 8440p                         | 3         | 1.6%    |
| HP EliteBook 840 G2                        | 3         | 1.6%    |
| Timi TM1701                                | 2         | 1.06%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 1.06%   |
| HP ZBook 15                                | 2         | 1.06%   |
| HP ProDesk 600 G1 TWR                      | 2         | 1.06%   |
| HP ProBook 6470b                           | 2         | 1.06%   |
| HP Notebook                                | 2         | 1.06%   |
| HP Laptop 15-dw3xxx                        | 2         | 1.06%   |
| HP EliteDesk 800 G1 SFF                    | 2         | 1.06%   |
| HP EliteBook 8460p                         | 2         | 1.06%   |
| HP Compaq Elite 8300 SFF                   | 2         | 1.06%   |
| HP Compaq Elite 8300 CMT                   | 2         | 1.06%   |
| HP Compaq dc7800 Convertible Minitower     | 2         | 1.06%   |
| Dell OptiPlex 790                          | 2         | 1.06%   |
| Dell Latitude E6520                        | 2         | 1.06%   |
| ASUS X540LA                                | 2         | 1.06%   |
| TUXEDO N13xWU                              | 1         | 0.53%   |
| TrekStor Surfbook W2                       | 1         | 0.53%   |
| Toshiba Satellite Pro C650                 | 1         | 0.53%   |
| Toshiba Satellite L750                     | 1         | 0.53%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.53%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.53%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.53%   |
| Toshiba Satellite C660                     | 1         | 0.53%   |
| Sony VPCEH1L8E                             | 1         | 0.53%   |
| Sony VGN-FW11L                             | 1         | 0.53%   |
| Sony SVE14122CAW                           | 1         | 0.53%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.53%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.53%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.53%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 1         | 0.53%   |
| Pegatron h8-1507ef                         | 1         | 0.53%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.53%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.53%   |
| Packard Bell EasyNote TK85                 | 1         | 0.53%   |
| MSI PPPPP-CCC#MMMMMMMM                     | 1         | 0.53%   |
| Medion S4401 MD61533                       | 1         | 0.53%   |
| Medion P7615                               | 1         | 0.53%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 1         | 0.53%   |
| Lenovo Z70-80 80FG                         | 1         | 0.53%   |
| Lenovo ThinkPad X380 Yoga 20LJS3JB00       | 1         | 0.53%   |
| Lenovo ThinkPad X280 20KF001KFR            | 1         | 0.53%   |
| Lenovo ThinkPad X250 20CLS4WV08            | 1         | 0.53%   |
| Lenovo ThinkPad X240 20AMA09VFR            | 1         | 0.53%   |
| Lenovo ThinkPad X220 4291V5K               | 1         | 0.53%   |
| Lenovo ThinkPad X220 4291B66               | 1         | 0.53%   |
| Lenovo ThinkPad X13 Gen 2i 20WK00AJGE      | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JGE   | 1         | 0.53%   |
| Lenovo ThinkPad T480s 20L8S3P300           | 1         | 0.53%   |
| Lenovo ThinkPad T460 20FN002SUS            | 1         | 0.53%   |
| Lenovo ThinkPad T440p 20AWS3DD1Z           | 1         | 0.53%   |
| Lenovo ThinkPad T440 20B7S2MF01            | 1         | 0.53%   |
| Lenovo ThinkPad T430 2349BS7               | 1         | 0.53%   |
| Lenovo ThinkPad P50 20EQS6J100             | 1         | 0.53%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00F00     | 1         | 0.53%   |
| Lenovo ThinkPad E590 20NB002AMB            | 1         | 0.53%   |
| Lenovo ThinkPad E570 20H50078IX            | 1         | 0.53%   |
| Lenovo ThinkCentre M93p 10AAS0R301         | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 9.04%   |
| HP EliteBook           | 14        | 7.45%   |
| HP Compaq              | 13        | 6.91%   |
| Dell Latitude          | 13        | 6.91%   |
| HP Pavilion            | 7         | 3.72%   |
| HP Laptop              | 7         | 3.72%   |
| Toshiba Satellite      | 6         | 3.19%   |
| HP ProBook             | 6         | 3.19%   |
| Dell OptiPlex          | 5         | 2.66%   |
| Lenovo IdeaPad         | 4         | 2.13%   |
| HP EliteDesk           | 4         | 2.13%   |
| Dell Precision         | 4         | 2.13%   |
| Acer Aspire            | 4         | 2.13%   |
| Unknown                | 4         | 2.13%   |
| Packard Bell EasyNote  | 3         | 1.6%    |
| Lenovo ThinkCentre     | 3         | 1.6%    |
| HP ZBook               | 3         | 1.6%    |
| HP 250                 | 3         | 1.6%    |
| Timi TM1701            | 2         | 1.06%   |
| HP ProDesk             | 2         | 1.06%   |
| HP Notebook            | 2         | 1.06%   |
| Dell XPS               | 2         | 1.06%   |
| Dell Vostro            | 2         | 1.06%   |
| Dell Inspiron          | 2         | 1.06%   |
| ASUS X540LA            | 2         | 1.06%   |
| ASUS ROG               | 2         | 1.06%   |
| TUXEDO N13xWU          | 1         | 0.53%   |
| TrekStor Surfbook      | 1         | 0.53%   |
| Sony VPCEH1L8E         | 1         | 0.53%   |
| Sony VGN-FW11L         | 1         | 0.53%   |
| Sony SVE14122CAW       | 1         | 0.53%   |
| Samsung 355V4C         | 1         | 0.53%   |
| Samsung 300E4A         | 1         | 0.53%   |
| Razer Blade            | 1         | 0.53%   |
| RPi Raspberry          | 1         | 0.53%   |
| Pegatron h8-1507ef     | 1         | 0.53%   |
| MSI PPPPP-CCC#MMMMMMMM | 1         | 0.53%   |
| Medion S4401           | 1         | 0.53%   |
| Medion P7615           | 1         | 0.53%   |
| Mediacom WinPad        | 1         | 0.53%   |
| Lenovo Z70-80          | 1         | 0.53%   |
| Lenovo ThinkBook       | 1         | 0.53%   |
| Lenovo G50-70          | 1         | 0.53%   |
| HP Z620                | 1         | 0.53%   |
| HP Z420                | 1         | 0.53%   |
| HP xw6400              | 1         | 0.53%   |
| HP Presario            | 1         | 0.53%   |
| HP ENVY                | 1         | 0.53%   |
| HP dc5000              | 1         | 0.53%   |
| HP 650                 | 1         | 0.53%   |
| HP 255                 | 1         | 0.53%   |
| HP 15                  | 1         | 0.53%   |
| GPD MicroPC            | 1         | 0.53%   |
| Google Banon           | 1         | 0.53%   |
| Gigabyte X570          | 1         | 0.53%   |
| Gigabyte AERO          | 1         | 0.53%   |
| Foxconn Pro3500        | 1         | 0.53%   |
| Foxconn p6-2002es      | 1         | 0.53%   |
| Foxconn CQ1140FRm      | 1         | 0.53%   |
| eMachines eM350        | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 25        | 13.3%   |
| 2011    | 22        | 11.7%   |
| 2012    | 19        | 10.11%  |
| 2018    | 14        | 7.45%   |
| 2015    | 14        | 7.45%   |
| 2016    | 13        | 6.91%   |
| 2010    | 13        | 6.91%   |
| 2017    | 12        | 6.38%   |
| 2019    | 11        | 5.85%   |
| 2021    | 8         | 4.26%   |
| 2007    | 8         | 4.26%   |
| 2020    | 7         | 3.72%   |
| 2014    | 7         | 3.72%   |
| 2009    | 7         | 3.72%   |
| 2008    | 3         | 1.6%    |
| 2004    | 2         | 1.06%   |
| Unknown | 2         | 1.06%   |
| 2005    | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 135       | 71.81%  |
| Desktop        | 46        | 24.47%  |
| Convertible    | 5         | 2.66%   |
| Phone          | 1         | 0.53%   |
| System on chip | 1         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 180       | 93.75%  |
| Enabled  | 12        | 6.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 99.47%  |
| Yes  | 1         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 33.51%  |
| 3.01-4.0    | 49        | 26.06%  |
| 16.01-24.0  | 25        | 13.3%   |
| 8.01-16.0   | 20        | 10.64%  |
| 1.01-2.0    | 15        | 7.98%   |
| 32.01-64.0  | 4         | 2.13%   |
| 24.01-32.0  | 4         | 2.13%   |
| 2.01-3.0    | 3         | 1.6%    |
| 64.01-256.0 | 3         | 1.6%    |
| 0.51-1.0    | 2         | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 86        | 42.16%  |
| 2.01-3.0  | 61        | 29.9%   |
| 3.01-4.0  | 22        | 10.78%  |
| 4.01-8.0  | 21        | 10.29%  |
| 0.51-1.0  | 12        | 5.88%   |
| 8.01-16.0 | 1         | 0.49%   |
| 0.01-0.5  | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 77.37%  |
| 2      | 31        | 16.32%  |
| 3      | 10        | 5.26%   |
| 4      | 2         | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 50%     |
| No        | 94        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 88.3%   |
| No        | 22        | 11.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 87.3%   |
| No        | 24        | 12.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 58.42%  |
| No        | 79        | 41.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 188       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Casablanca       | 52        | 26%     |
| Marrakesh        | 21        | 10.5%   |
| Rabat            | 18        | 9%      |
| Agadir           | 18        | 9%      |
| Fes              | 13        | 6.5%    |
| Tangier          | 8         | 4%      |
| Sal??            | 7         | 3.5%    |
| Oujda            | 7         | 3.5%    |
| Kenitra          | 6         | 3%      |
| Meknes           | 5         | 2.5%    |
| Khouribga        | 5         | 2.5%    |
| Tiznit           | 4         | 2%      |
| Temara           | 3         | 1.5%    |
| Taza             | 3         | 1.5%    |
| Nador            | 3         | 1.5%    |
| Youssoufia       | 2         | 1%      |
| T??touan         | 2         | 1%      |
| Skhirate         | 2         | 1%      |
| Safi             | 2         | 1%      |
| Mohammedia       | 2         | 1%      |
| Beni Mellal      | 2         | 1%      |
| Taourirt         | 1         | 0.5%    |
| Taounate         | 1         | 0.5%    |
| Sidi Lmokhtar    | 1         | 0.5%    |
| Sidi Kacem       | 1         | 0.5%    |
| Ouirgane         | 1         | 0.5%    |
| Midelt           | 1         | 0.5%    |
| Ksar El Kebir    | 1         | 0.5%    |
| Karia Ba Mohamed | 1         | 0.5%    |
| Guelmim          | 1         | 0.5%    |
| Douar Kalaa      | 1         | 0.5%    |
| Berrechid        | 1         | 0.5%    |
| Berkane          | 1         | 0.5%    |
| Al Aaroui        | 1         | 0.5%    |
| Agdz             | 1         | 0.5%    |
| Agdal            | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 42        | 57     | 18.5%   |
| WDC                   | 33        | 38     | 14.54%  |
| Samsung Electronics   | 30        | 42     | 13.22%  |
| Toshiba               | 27        | 41     | 11.89%  |
| Hitachi               | 13        | 15     | 5.73%   |
| Unknown               | 9         | 12     | 3.96%   |
| HGST                  | 8         | 8      | 3.52%   |
| Intel                 | 7         | 8      | 3.08%   |
| SanDisk               | 6         | 6      | 2.64%   |
| Kingston              | 5         | 6      | 2.2%    |
| SK hynix              | 4         | 4      | 1.76%   |
| PNY                   | 3         | 4      | 1.32%   |
| Phison                | 3         | 4      | 1.32%   |
| LITEON                | 3         | 3      | 1.32%   |
| KIOXIA                | 3         | 3      | 1.32%   |
| Fujitsu               | 3         | 3      | 1.32%   |
| Crucial               | 3         | 4      | 1.32%   |
| Apple                 | 3         | 3      | 1.32%   |
| Micron Technology     | 2         | 3      | 0.88%   |
| KingDian              | 2         | 3      | 0.88%   |
| China                 | 2         | 3      | 0.88%   |
| TwinMOS               | 1         | 1      | 0.44%   |
| Realtek Semiconductor | 1         | 1      | 0.44%   |
| RCESSD                | 1         | 1      | 0.44%   |
| Magnetic Data         | 1         | 1      | 0.44%   |
| LITEONIT              | 1         | 1      | 0.44%   |
| KingSpec              | 1         | 1      | 0.44%   |
| KingFast              | 1         | 2      | 0.44%   |
| Indilinx              | 1         | 1      | 0.44%   |
| IBM/Hitachi           | 1         | 1      | 0.44%   |
| HS-SSD-E100           | 1         | 1      | 0.44%   |
| Hewlett-Packard       | 1         | 1      | 0.44%   |
| Goodram               | 1         | 1      | 0.44%   |
| BIWIN                 | 1         | 1      | 0.44%   |
| Apacer                | 1         | 1      | 0.44%   |
| 2.5"                  | 1         | 1      | 0.44%   |
| Unknown               | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 2.09%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.67%   |
| Samsung NVMe SSD Drive 512GB       | 4         | 1.67%   |
| Toshiba MQ01ACF050 500GB           | 3         | 1.26%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 1.26%   |
| Seagate ST3250312AS 250GB          | 3         | 1.26%   |
| Intel SSDSC2BF180A4H 180GB         | 3         | 1.26%   |
| WDC WD800JD-00LSA0 80GB            | 2         | 0.84%   |
| WDC WD5000LPCX-80VHAT1 500GB       | 2         | 0.84%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.84%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 2         | 0.84%   |
| Unknown MMC Card  32GB             | 2         | 0.84%   |
| Unknown MMC Card  16GB             | 2         | 0.84%   |
| Toshiba MQ04ABF100 1TB             | 2         | 0.84%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.84%   |
| Toshiba MQ01ABD100 1TB             | 2         | 0.84%   |
| Seagate ST9500325AS 500GB          | 2         | 0.84%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.84%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.84%   |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 0.84%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.84%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.84%   |
| Samsung MZVLB512HAJQ-000L7 512GB   | 2         | 0.84%   |
| Samsung MZVLB1T0HALR-00000 1TB     | 2         | 0.84%   |
| PNY CS900 120GB SSD                | 2         | 0.84%   |
| LITEON IT LCS-128L9S-HP 128GB SSD  | 2         | 0.84%   |
| Hitachi HTS723232A7A364 320GB      | 2         | 0.84%   |
| Hitachi HDS721680PLA380 80GB       | 2         | 0.84%   |
| HGST HTS725050A7E630 500GB         | 2         | 0.84%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.84%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.84%   |
| WDC WDS256G1X0C-00ENX0 256GB       | 1         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.42%   |
| WDC WD800JD-75MSA3 80GB            | 1         | 0.42%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.42%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 0.42%   |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 0.42%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1         | 0.42%   |
| WDC WD400BB-60DGA0 40GB            | 1         | 0.42%   |
| WDC WD3200BUCT-63TWBY0 320GB       | 1         | 0.42%   |
| WDC WD3200BPVT-22ZEST0 320GB       | 1         | 0.42%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 0.42%   |
| WDC WD3200BEKT-60F3T1 320GB        | 1         | 0.42%   |
| WDC WD3200AAJS-65RYA0 320GB        | 1         | 0.42%   |
| WDC WD2500BPVT-22ZEST0 250GB       | 1         | 0.42%   |
| WDC WD2500BEVT-22A23T0 250GB       | 1         | 0.42%   |
| WDC WD2500BEKT-60V5T1 250GB        | 1         | 0.42%   |
| WDC WD2500AAKX-603CA0 250GB        | 1         | 0.42%   |
| WDC WD2500AAJS-60Z0A0 250GB        | 1         | 0.42%   |
| WDC WD1600JS-55NCB1 160GB          | 1         | 0.42%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 0.42%   |
| WDC WD1600AAJS-75M0A0 160GB        | 1         | 0.42%   |
| WDC WD1600AAJS-60M0A0 160GB        | 1         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 0.42%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.42%   |
| WDC WD10JUCT-63CYNY0 1TB           | 1         | 0.42%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 0.42%   |
| Unknown SB32G  32GB                | 1         | 0.42%   |
| Unknown SB128  128GB               | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 57     | 32.56%  |
| WDC                 | 31        | 36     | 24.03%  |
| Toshiba             | 23        | 31     | 17.83%  |
| Hitachi             | 13        | 15     | 10.08%  |
| HGST                | 8         | 8      | 6.2%    |
| Samsung Electronics | 6         | 9      | 4.65%   |
| Fujitsu             | 3         | 3      | 2.33%   |
| Magnetic Data       | 1         | 1      | 0.78%   |
| IBM/Hitachi         | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 12     | 12.96%  |
| SanDisk             | 6         | 6      | 11.11%  |
| Kingston            | 4         | 5      | 7.41%   |
| Intel               | 4         | 5      | 7.41%   |
| PNY                 | 3         | 4      | 5.56%   |
| LITEON              | 3         | 3      | 5.56%   |
| Crucial             | 3         | 4      | 5.56%   |
| SK hynix            | 2         | 2      | 3.7%    |
| Micron Technology   | 2         | 3      | 3.7%    |
| KingDian            | 2         | 3      | 3.7%    |
| China               | 2         | 3      | 3.7%    |
| WDC                 | 1         | 1      | 1.85%   |
| TwinMOS             | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| RCESSD              | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| KingSpec            | 1         | 1      | 1.85%   |
| KingFast            | 1         | 1      | 1.85%   |
| Indilinx            | 1         | 1      | 1.85%   |
| HS-SSD-E100         | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |
| Goodram             | 1         | 1      | 1.85%   |
| BIWIN               | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |
| Apacer              | 1         | 1      | 1.85%   |
| 2.5"                | 1         | 1      | 1.85%   |
| Unknown             | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 119       | 162    | 56.13%  |
| SSD     | 50        | 66     | 23.58%  |
| NVMe    | 33        | 46     | 15.57%  |
| MMC     | 9         | 12     | 4.25%   |
| Unknown | 1         | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 227    | 78.28%  |
| NVMe | 33        | 46     | 16.67%  |
| MMC  | 9         | 12     | 4.55%   |
| SAS  | 1         | 2      | 0.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 127       | 169    | 76.51%  |
| 0.51-1.0   | 36        | 55     | 21.69%  |
| 1.01-2.0   | 2         | 2      | 1.2%    |
| 2.01-3.0   | 1         | 2      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 55        | 28.35%  |
| 251-500        | 50        | 25.77%  |
| 501-1000       | 21        | 10.82%  |
| 1-20           | 19        | 9.79%   |
| 51-100         | 19        | 9.79%   |
| 21-50          | 18        | 9.28%   |
| Unknown        | 5         | 2.58%   |
| 1001-2000      | 4         | 2.06%   |
| More than 3000 | 2         | 1.03%   |
| 2001-3000      | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 92        | 44.66%  |
| 21-50          | 42        | 20.39%  |
| 101-250        | 27        | 13.11%  |
| 51-100         | 24        | 11.65%  |
| 251-500        | 10        | 4.85%   |
| Unknown        | 5         | 2.43%   |
| 1001-2000      | 2         | 0.97%   |
| 501-1000       | 2         | 0.97%   |
| More than 3000 | 1         | 0.49%   |
| 2001-3000      | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3         | 3      | 12%     |
| Seagate ST9500325AS 500GB         | 2         | 2      | 8%      |
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 8%      |
| Hitachi HDS721680PLA380 80GB      | 2         | 2      | 8%      |
| WDC WD5000BPVT-22HXZT1 500GB      | 1         | 1      | 4%      |
| WDC WD2500AAJS-60Z0A0 250GB       | 1         | 1      | 4%      |
| WDC WD10JPVX-60JC3T0 1TB          | 1         | 2      | 4%      |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 4%      |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 4%      |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 4%      |
| Toshiba MK1237GSX 120GB           | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 4%      |
| Seagate ST340016A 40GB            | 1         | 1      | 4%      |
| Seagate ST3250312AS 250GB         | 1         | 1      | 4%      |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 4%      |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 4%      |
| Hitachi HTS723232A7A364 320GB     | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB     | 1         | 2      | 4%      |
| Fujitsu MHX2300BT 304GB           | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 40%     |
| Toshiba             | 5         | 5      | 20%     |
| Hitachi             | 4         | 5      | 16%     |
| WDC                 | 3         | 4      | 12%     |
| SanDisk             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 41.67%  |
| Toshiba             | 5         | 5      | 20.83%  |
| Hitachi             | 4         | 5      | 16.67%  |
| WDC                 | 3         | 4      | 12.5%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 26     | 96%     |
| SSD  | 1         | 1      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 2      | 50%     |
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 25%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 75%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 111       | 164    | 54.15%  |
| Works    | 65        | 91     | 31.71%  |
| Malfunc  | 25        | 27     | 12.2%   |
| Failed   | 4         | 5      | 1.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 151       | 74.75%  |
| Samsung Electronics              | 18        | 8.91%   |
| AMD                              | 12        | 5.94%   |
| Toshiba America Info Systems     | 3         | 1.49%   |
| Phison Electronics               | 3         | 1.49%   |
| Nvidia                           | 3         | 1.49%   |
| KIOXIA                           | 3         | 1.49%   |
| SK hynix                         | 2         | 0.99%   |
| Silicon Integrated Systems [SiS] | 2         | 0.99%   |
| SanDisk                          | 1         | 0.5%    |
| Realtek Semiconductor            | 1         | 0.5%    |
| Kingston Technology Company      | 1         | 0.5%    |
| JMicron Technology               | 1         | 0.5%    |
| Broadcom / LSI                   | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 6.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 6.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 5.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 4.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 4.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 4.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 4.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 3.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 3.06%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 3.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 2.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 2.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.18%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.75%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 4         | 1.75%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.75%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 1.31%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.87%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.87%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.87%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.87%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.87%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.87%   |
| Intel SSD 660P Series                                                                   | 2         | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.87%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 0.87%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.87%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.44%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.44%   |
| SanDisk WD Black NVMe SSD                                                               | 1         | 0.44%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.44%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.44%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.44%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.44%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.44%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.44%   |
| Intel SSD 600P Series                                                                   | 1         | 0.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 0.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.44%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1         | 0.44%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 0.44%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 63.55%  |
| NVMe | 33        | 15.42%  |
| IDE  | 22        | 10.28%  |
| RAID | 21        | 9.81%   |
| SAS  | 2         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 168       | 89.36%  |
| AMD    | 18        | 9.57%   |
| ARM    | 2         | 1.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 3.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 2.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 5         | 2.66%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 2.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 2.13%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.6%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.06%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 1.06%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 1.06%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.06%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 1.06%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.06%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.06%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.06%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.06%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.06%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.06%   |
| AMD C-60 APU with Radeon HD Graphics        | 2         | 1.06%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.53%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 0.53%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.53%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz         | 1         | 0.53%   |
| Intel Xeon CPU 5140 @ 2.33GHz               | 1         | 0.53%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.53%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.53%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.53%   |
| Intel Pentium CPU G3220T @ 2.60GHz          | 1         | 0.53%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.53%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.53%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.53%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.53%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.53%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 1         | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.53%   |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.53%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 1         | 0.53%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 0.53%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 72        | 38.3%   |
| Intel Core i7           | 33        | 17.55%  |
| Intel Core i3           | 24        | 12.77%  |
| Intel Core 2 Duo        | 9         | 4.79%   |
| Other                   | 5         | 2.66%   |
| Intel Xeon              | 5         | 2.66%   |
| Intel Celeron           | 5         | 2.66%   |
| Intel Atom              | 5         | 2.66%   |
| AMD Ryzen 5             | 4         | 2.13%   |
| Intel Pentium Dual-Core | 3         | 1.6%    |
| AMD C-60                | 2         | 1.06%   |
| AMD Athlon 64 X2        | 2         | 1.06%   |
| Intel Pentium M         | 1         | 0.53%   |
| Intel Pentium Gold      | 1         | 0.53%   |
| Intel Pentium Dual      | 1         | 0.53%   |
| Intel Pentium 4         | 1         | 0.53%   |
| Intel Pentium           | 1         | 0.53%   |
| Intel Core 2 Quad       | 1         | 0.53%   |
| Intel Celeron M         | 1         | 0.53%   |
| ARM BCM                 | 1         | 0.53%   |
| ARM AArch64             | 1         | 0.53%   |
| AMD Ryzen 9             | 1         | 0.53%   |
| AMD Ryzen 7 PRO         | 1         | 0.53%   |
| AMD Ryzen 7             | 1         | 0.53%   |
| AMD Phenom II X6        | 1         | 0.53%   |
| AMD E1                  | 1         | 0.53%   |
| AMD E                   | 1         | 0.53%   |
| AMD Athlon XP           | 1         | 0.53%   |
| AMD A8                  | 1         | 0.53%   |
| AMD A6                  | 1         | 0.53%   |
| AMD A4                  | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 55.32%  |
| 4      | 66        | 35.11%  |
| 1      | 6         | 3.19%   |
| 6      | 5         | 2.66%   |
| 8      | 4         | 2.13%   |
| 16     | 2         | 1.06%   |
| 12     | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 98.94%  |
| 2      | 2         | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 127       | 67.55%  |
| 1      | 61        | 32.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 181       | 96.28%  |
| 32-bit         | 4         | 2.13%   |
| Unknown        | 3         | 1.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 13.09%  |
| 0x206a7    | 21        | 10.99%  |
| 0x306c3    | 16        | 8.38%   |
| 0x306a9    | 16        | 8.38%   |
| 0x806ea    | 10        | 5.24%   |
| 0x306d4    | 10        | 5.24%   |
| 0x40651    | 7         | 3.66%   |
| 0x806e9    | 6         | 3.14%   |
| 0x506e3    | 6         | 3.14%   |
| 0x406e3    | 6         | 3.14%   |
| 0x20655    | 6         | 3.14%   |
| 0x1067a    | 5         | 2.62%   |
| 0x806ec    | 4         | 2.09%   |
| 0x806c1    | 4         | 2.09%   |
| 0x20652    | 4         | 2.09%   |
| 0x906e9    | 3         | 1.57%   |
| 0x6fb      | 3         | 1.57%   |
| 0x10676    | 3         | 1.57%   |
| 0x08701021 | 3         | 1.57%   |
| 0x906ea    | 2         | 1.05%   |
| 0x706e5    | 2         | 1.05%   |
| 0x6fd      | 2         | 1.05%   |
| 0x406c4    | 2         | 1.05%   |
| 0x406c3    | 2         | 1.05%   |
| 0x30678    | 2         | 1.05%   |
| 0x206d7    | 2         | 1.05%   |
| 0x05000119 | 2         | 1.05%   |
| 0xf29      | 1         | 0.52%   |
| 0x806eb    | 1         | 0.52%   |
| 0x706a1    | 1         | 0.52%   |
| 0x6ec      | 1         | 0.52%   |
| 0x6d8      | 1         | 0.52%   |
| 0x306f2    | 1         | 0.52%   |
| 0x30673    | 1         | 0.52%   |
| 0x30661    | 1         | 0.52%   |
| 0x106e5    | 1         | 0.52%   |
| 0x0a50000c | 1         | 0.52%   |
| 0x08608103 | 1         | 0.52%   |
| 0x08108102 | 1         | 0.52%   |
| 0x07030105 | 1         | 0.52%   |
| 0x06006705 | 1         | 0.52%   |
| 0x05000101 | 1         | 0.52%   |
| 0x03000027 | 1         | 0.52%   |
| 0x010000dc | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 14.89%  |
| Haswell       | 26        | 13.83%  |
| SandyBridge   | 24        | 12.77%  |
| IvyBridge     | 17        | 9.04%   |
| Skylake       | 14        | 7.45%   |
| Westmere      | 11        | 5.85%   |
| Penryn        | 10        | 5.32%   |
| Broadwell     | 10        | 5.32%   |
| Silvermont    | 7         | 3.72%   |
| TigerLake     | 5         | 2.66%   |
| Core          | 5         | 2.66%   |
| Unknown       | 5         | 2.66%   |
| Bobcat        | 4         | 2.13%   |
| Zen 2         | 3         | 1.6%    |
| P6            | 2         | 1.06%   |
| K8 Hammer     | 2         | 1.06%   |
| IceLake       | 2         | 1.06%   |
| Bonnell       | 2         | 1.06%   |
| Zen+          | 1         | 0.53%   |
| Zen 3         | 1         | 0.53%   |
| Puma          | 1         | 0.53%   |
| NetBurst      | 1         | 0.53%   |
| Nehalem       | 1         | 0.53%   |
| K6            | 1         | 0.53%   |
| K10 Llano     | 1         | 0.53%   |
| K10           | 1         | 0.53%   |
| Goldmont plus | 1         | 0.53%   |
| Excavator     | 1         | 0.53%   |
| CometLake     | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 144       | 66.98%  |
| Nvidia                           | 42        | 19.53%  |
| AMD                              | 28        | 13.02%  |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 20        | 9.17%   |
| Intel UHD Graphics 620                                                                     | 11        | 5.05%   |
| Intel HD Graphics 5500                                                                     | 10        | 4.59%   |
| Intel Core Processor Integrated Graphics Controller                                        | 10        | 4.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 9         | 4.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 8         | 3.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 7         | 3.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 7         | 3.21%   |
| Intel HD Graphics 620                                                                      | 7         | 3.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 7         | 3.21%   |
| Intel HD Graphics 530                                                                      | 6         | 2.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                           | 5         | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 4         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 4         | 1.83%   |
| Nvidia GT218 [GeForce 210]                                                                 | 3         | 1.38%   |
| Nvidia GK106GLM [Quadro K2100M]                                                            | 3         | 1.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 3         | 1.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 3         | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                       | 3         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 3         | 1.38%   |
| Nvidia GP108M [GeForce MX150]                                                              | 2         | 0.92%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.92%   |
| Nvidia GK208M [GeForce GT 740M]                                                            | 2         | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 2         | 0.92%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.92%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 2         | 0.92%   |
| Nvidia GF119 [GeForce GT 610]                                                              | 2         | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 2         | 0.92%   |
| Intel HD Graphics 630                                                                      | 2         | 0.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 2         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2         | 0.92%   |
| AMD Wrestler [Radeon HD 6290]                                                              | 2         | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 2         | 0.92%   |
| AMD Lucienne                                                                               | 2         | 0.92%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 0.46%   |
| Nvidia TU117M [GeForce MX450]                                                              | 1         | 0.46%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                         | 1         | 0.46%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                      | 1         | 0.46%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                    | 1         | 0.46%   |
| Nvidia GT218M [GeForce G210M]                                                              | 1         | 0.46%   |
| Nvidia GT216M [GeForce GT 330M]                                                            | 1         | 0.46%   |
| Nvidia GP107M [GeForce MX350]                                                              | 1         | 0.46%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                    | 1         | 0.46%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                                | 1         | 0.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 0.46%   |
| Nvidia GM204GL [Quadro M4000]                                                              | 1         | 0.46%   |
| Nvidia GM107GLM [Quadro M2000M]                                                            | 1         | 0.46%   |
| Nvidia GM107GLM [Quadro M1000M]                                                            | 1         | 0.46%   |
| Nvidia GK107GL [Quadro K420]                                                               | 1         | 0.46%   |
| Nvidia GF106GLM [Quadro 2000M]                                                             | 1         | 0.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                            | 1         | 0.46%   |
| Nvidia G96GLM [Quadro FX 770M]                                                             | 1         | 0.46%   |
| Nvidia G72 [GeForce 7500 LE]                                                               | 1         | 0.46%   |
| Nvidia C79 [GeForce 9400M G]                                                               | 1         | 0.46%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                     | 1         | 0.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                       | 1         | 0.46%   |
| Intel Tiger Lake UHD Graphics                                                              | 1         | 0.46%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1         | 0.46%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 1         | 0.46%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 115       | 61.17%  |
| Intel + Nvidia | 24        | 12.77%  |
| 1 x AMD        | 23        | 12.23%  |
| 1 x Nvidia     | 17        | 9.04%   |
| Intel + AMD    | 4         | 2.13%   |
| Other          | 2         | 1.06%   |
| 2 x Nvidia     | 1         | 0.53%   |
| 2 x AMD        | 1         | 0.53%   |
| 1 x SiS        | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 163       | 84.9%   |
| Proprietary | 20        | 10.42%  |
| Unknown     | 9         | 4.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 66.15%  |
| 1.01-2.0   | 23        | 11.98%  |
| 0.01-0.5   | 22        | 11.46%  |
| 0.51-1.0   | 9         | 4.69%   |
| 3.01-4.0   | 8         | 4.17%   |
| 7.01-8.0   | 2         | 1.04%   |
| 2.01-3.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 29        | 16.11%  |
| AU Optronics            | 29        | 16.11%  |
| LG Display              | 27        | 15%     |
| Chimei Innolux          | 21        | 11.67%  |
| BOE                     | 18        | 10%     |
| Dell                    | 15        | 8.33%   |
| Hewlett-Packard         | 9         | 5%      |
| InfoVision              | 5         | 2.78%   |
| Lenovo                  | 4         | 2.22%   |
| Sharp                   | 3         | 1.67%   |
| Chi Mei Optoelectronics | 3         | 1.67%   |
| Acer                    | 3         | 1.67%   |
| LG Philips              | 2         | 1.11%   |
| Iiyama                  | 2         | 1.11%   |
| Goldstar                | 2         | 1.11%   |
| BenQ                    | 2         | 1.11%   |
| Apple                   | 2         | 1.11%   |
| Philips                 | 1         | 0.56%   |
| MiTAC                   | 1         | 0.56%   |
| LGD                     | 1         | 0.56%   |
| Ancor Communications    | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                       | 3         | 1.66%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch         | 3         | 1.66%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 3         | 1.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch    | 2         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch    | 2         | 1.1%    |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch             | 2         | 1.1%    |
| Lenovo LCD Monitor LEN1144 1920x1200 520x320mm 24.0-inch                | 2         | 1.1%    |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                      | 2         | 1.1%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 2         | 1.1%    |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch    | 1         | 0.55%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch      | 1         | 0.55%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.55%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0B2A 1280x720 949x543mm 43.0-inch    | 1         | 0.55%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                      | 1         | 0.55%   |
| MiTAC Mystery TV MTC9527 1920x1080 1150x650mm 52.0-inch                 | 1         | 0.55%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.55%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch             | 1         | 0.55%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD059A 1920x1080 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD04A2 1920x1080 276x156mm 12.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD03E0 1366x768 345x194mm 15.6-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch             | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 67        | 38.29%  |
| 1920x1080 (FHD)    | 59        | 33.71%  |
| 1600x900 (HD+)     | 13        | 7.43%   |
| 1280x1024 (SXGA)   | 7         | 4%      |
| 1680x1050 (WSXGA+) | 6         | 3.43%   |
| 3840x2160 (4K)     | 4         | 2.29%   |
| 1440x900 (WXGA+)   | 4         | 2.29%   |
| 1280x800 (WXGA)    | 4         | 2.29%   |
| 1024x600           | 3         | 1.71%   |
| 3840x2400          | 2         | 1.14%   |
| 2880x1800          | 1         | 0.57%   |
| 1920x1200 (WUXGA)  | 1         | 0.57%   |
| 1400x1050          | 1         | 0.57%   |
| 1280x720 (HD)      | 1         | 0.57%   |
| 1152x864           | 1         | 0.57%   |
| 1024x768 (XGA)     | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 44.2%   |
| 14      | 19        | 10.5%   |
| 13      | 15        | 8.29%   |
| 24      | 13        | 7.18%   |
| 17      | 10        | 5.52%   |
| 12      | 8         | 4.42%   |
| 19      | 6         | 3.31%   |
| 23      | 4         | 2.21%   |
| 22      | 4         | 2.21%   |
| 27      | 3         | 1.66%   |
| 18      | 3         | 1.66%   |
| Unknown | 3         | 1.66%   |
| 21      | 2         | 1.1%    |
| 20      | 2         | 1.1%    |
| 11      | 2         | 1.1%    |
| 10      | 2         | 1.1%    |
| 84      | 1         | 0.55%   |
| 54      | 1         | 0.55%   |
| 52      | 1         | 0.55%   |
| 43      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 59.67%  |
| 201-300     | 21        | 11.6%   |
| 501-600     | 19        | 10.5%   |
| 401-500     | 14        | 7.73%   |
| 351-400     | 10        | 5.52%   |
| Unknown     | 3         | 1.66%   |
| 1001-1500   | 2         | 1.1%    |
| 801-900     | 1         | 0.55%   |
| 601-700     | 1         | 0.55%   |
| 1501-2000   | 1         | 0.55%   |
| 901-1000    | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 143       | 81.71%  |
| 16/10   | 19        | 10.86%  |
| 5/4     | 7         | 4%      |
| 4/3     | 3         | 1.71%   |
| Unknown | 3         | 1.71%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 44.75%  |
| 81-90          | 26        | 14.36%  |
| 201-250        | 20        | 11.05%  |
| 151-200        | 9         | 4.97%   |
| 61-70          | 8         | 4.42%   |
| 141-150        | 7         | 3.87%   |
| 71-80          | 6         | 3.31%   |
| 121-130        | 4         | 2.21%   |
| More than 1000 | 3         | 1.66%   |
| 301-350        | 3         | 1.66%   |
| 251-300        | 3         | 1.66%   |
| Unknown        | 3         | 1.66%   |
| 51-60          | 2         | 1.1%    |
| 41-50          | 2         | 1.1%    |
| 501-1000       | 2         | 1.1%    |
| 131-140        | 1         | 0.55%   |
| 91-100         | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 65        | 36.11%  |
| 121-160       | 49        | 27.22%  |
| 51-100        | 48        | 26.67%  |
| 161-240       | 9         | 5%      |
| More than 240 | 3         | 1.67%   |
| 1-50          | 3         | 1.67%   |
| Unknown       | 3         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 174       | 91.58%  |
| 2     | 10        | 5.26%   |
| 0     | 6         | 3.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 107       | 37.15%  |
| Realtek Semiconductor            | 78        | 27.08%  |
| Qualcomm Atheros                 | 37        | 12.85%  |
| Broadcom                         | 24        | 8.33%   |
| Ralink Technology                | 11        | 3.82%   |
| Ralink                           | 7         | 2.43%   |
| TP-Link                          | 4         | 1.39%   |
| Nvidia                           | 3         | 1.04%   |
| Marvell Technology Group         | 2         | 0.69%   |
| Lenovo                           | 2         | 0.69%   |
| D-Link System                    | 2         | 0.69%   |
| Broadcom Limited                 | 2         | 0.69%   |
| Xiaomi                           | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Samsung Electronics              | 1         | 0.35%   |
| Qualcomm Atheros Communications  | 1         | 0.35%   |
| JMicron Technology               | 1         | 0.35%   |
| Gemtek                           | 1         | 0.35%   |
| Fibocom                          | 1         | 0.35%   |
| Dell                             | 1         | 0.35%   |
| Arduino SA                       | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 13.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 5.95%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 3.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.68%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.98%   |
| Ralink RT5370 Wireless Adapter                                    | 7         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.98%   |
| Intel Wireless 8260                                               | 7         | 1.98%   |
| Intel Wireless 7265                                               | 7         | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 1.7%    |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.42%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.42%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.42%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.13%   |
| Intel Wireless 7260                                               | 4         | 1.13%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.85%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.85%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.57%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.57%   |
| Intel Wireless 3165                                               | 2         | 0.57%   |
| Intel WiFi Link 5100                                              | 2         | 0.57%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.57%   |
| Broadcom BCM43225 802.11b/g/n                                     | 2         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.28%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 41.86%  |
| Qualcomm Atheros                | 32        | 18.6%   |
| Realtek Semiconductor           | 24        | 13.95%  |
| Broadcom                        | 17        | 9.88%   |
| Ralink Technology               | 11        | 6.4%    |
| Ralink                          | 7         | 4.07%   |
| TP-Link                         | 4         | 2.33%   |
| Qualcomm Atheros Communications | 1         | 0.58%   |
| Gemtek                          | 1         | 0.58%   |
| Fibocom                         | 1         | 0.58%   |
| D-Link System                   | 1         | 0.58%   |
| Broadcom Limited                | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 10        | 5.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 5.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.02%   |
| Ralink RT5370 Wireless Adapter                                          | 7         | 4.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.02%   |
| Intel Wireless 8260                                                     | 7         | 4.02%   |
| Intel Wireless 7265                                                     | 7         | 4.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.87%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.87%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 2.87%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 2.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.3%    |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 2.3%    |
| Intel Wireless 7260                                                     | 4         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.15%   |
| Intel Wireless 3165                                                     | 2         | 1.15%   |
| Intel WiFi Link 5100                                                    | 2         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.15%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.57%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.57%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.57%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.57%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.57%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                    | 1         | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.57%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.57%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.57%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.57%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 1         | 0.57%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 0.57%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]    | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 44%     |
| Realtek Semiconductor            | 67        | 38.29%  |
| Qualcomm Atheros                 | 10        | 5.71%   |
| Broadcom                         | 8         | 4.57%   |
| Nvidia                           | 3         | 1.71%   |
| Marvell Technology Group         | 2         | 1.14%   |
| Lenovo                           | 2         | 1.14%   |
| Xiaomi                           | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Samsung Electronics              | 1         | 0.57%   |
| JMicron Technology               | 1         | 0.57%   |
| D-Link System                    | 1         | 0.57%   |
| Broadcom Limited                 | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 46        | 26.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 11.93%  |
| Intel Ethernet Connection I217-LM                                              | 14        | 7.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 13        | 7.39%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 3.41%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 3.41%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.7%    |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.7%    |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.7%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.14%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 1.14%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 1.14%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.14%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.57%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.57%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.57%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.57%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.57%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 1         | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.57%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 49.7%   |
| WiFi     | 165       | 49.4%   |
| Modem    | 3         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 73.4%   |
| Ethernet | 50        | 26.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 129       | 68.25%  |
| 1     | 52        | 27.51%  |
| 0     | 5         | 2.65%   |
| 3     | 3         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 45.05%  |
| Realtek Semiconductor           | 15        | 13.51%  |
| Qualcomm Atheros Communications | 13        | 11.71%  |
| Broadcom                        | 9         | 8.11%   |
| Dell                            | 4         | 3.6%    |
| Ralink                          | 3         | 2.7%    |
| Lite-On Technology              | 3         | 2.7%    |
| IMC Networks                    | 3         | 2.7%    |
| Hewlett-Packard                 | 3         | 2.7%    |
| Toshiba                         | 2         | 1.8%    |
| ASUSTek Computer                | 2         | 1.8%    |
| Foxconn / Hon Hai               | 1         | 0.9%    |
| Cambridge Silicon Radio         | 1         | 0.9%    |
| Apple                           | 1         | 0.9%    |
| Alps Electric                   | 1         | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 25.23%  |
| Realtek Bluetooth Radio                             | 10        | 9.01%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 4.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 4.5%    |
| Intel Bluetooth Device                              | 5         | 4.5%    |
| Intel AX200 Bluetooth                               | 5         | 4.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.6%    |
| Ralink RT3290 Bluetooth                             | 3         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.7%    |
| IMC Networks Bluetooth Device                       | 3         | 2.7%    |
| Dell DW375 Bluetooth Module                         | 3         | 2.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.8%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.8%    |
| Toshiba Bluetooth Device                            | 1         | 0.9%    |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.9%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.9%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.9%    |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.9%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.9%    |
| Dell Wireless 360 Bluetooth                         | 1         | 0.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.9%    |
| Broadcom HP Portable Valentine                      | 1         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 1         | 0.9%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.9%    |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.9%    |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 1         | 0.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.9%    |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 73.21%  |
| Nvidia                           | 29        | 12.95%  |
| AMD                              | 22        | 9.82%   |
| Silicon Integrated Systems [SiS] | 2         | 0.89%   |
| Lenovo                           | 2         | 0.89%   |
| Logitech                         | 1         | 0.45%   |
| Hewlett-Packard                  | 1         | 0.45%   |
| GN Netcom                        | 1         | 0.45%   |
| GEMBIRD                          | 1         | 0.45%   |
| C-Media Electronics              | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 9.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 7.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 6.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 5.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 4.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.72%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.35%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 2.97%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.86%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.12%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.12%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.74%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.74%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.74%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia Audio device                                                                               | 1         | 0.37%   |
| Logitech Headset H390                                                                             | 1         | 0.37%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.37%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.37%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller                                    | 1         | 0.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.37%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 1         | 0.37%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1         | 0.37%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.37%   |
| Hewlett-Packard Digital Stereo Headset                                                            | 1         | 0.37%   |
| GN Netcom Jabra LINK 230                                                                          | 1         | 0.37%   |
| GEMBIRD USB SkypePhone                                                                            | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 39        | 29.1%   |
| Samsung Electronics | 36        | 26.87%  |
| Micron Technology   | 18        | 13.43%  |
| Kingston            | 14        | 10.45%  |
| Unknown             | 5         | 3.73%   |
| Corsair             | 4         | 2.99%   |
| Crucial             | 3         | 2.24%   |
| Ramaxel Technology  | 2         | 1.49%   |
| Nanya Technology    | 2         | 1.49%   |
| Elpida              | 2         | 1.49%   |
| Transcend           | 1         | 0.75%   |
| Toshiba             | 1         | 0.75%   |
| TakeMS              | 1         | 0.75%   |
| Sesame              | 1         | 0.75%   |
| Qimonda             | 1         | 0.75%   |
| ASint Technology    | 1         | 0.75%   |
| Apacer              | 1         | 0.75%   |
| A-DATA Technology   | 1         | 0.75%   |
| Unknown             | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                 | 4         | 2.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 4         | 2.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                | 3         | 2.07%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                  | 3         | 2.07%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s             | 3         | 2.07%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                  | 3         | 2.07%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 2         | 1.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 2         | 1.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 2         | 1.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                | 2         | 1.38%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s              | 2         | 1.38%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s                | 2         | 1.38%   |
| Unknown RAM Module 4GB SODIMM DDR3                                   | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                       | 1         | 0.69%   |
| Unknown RAM Module 2GB DIMM                                          | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                         | 1         | 0.69%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s               | 1         | 0.69%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s                 | 1         | 0.69%   |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s               | 1         | 0.69%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.69%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.69%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                               | 1         | 0.69%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                 | 1         | 0.69%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s                 | 1         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s                 | 1         | 0.69%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8192MB DIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |
| SK hynix RAM HMT41GR7BFR4A-PB 8192MB DIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s              | 1         | 0.69%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s            | 1         | 0.69%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.69%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s                 | 1         | 0.69%   |
| SK hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s              | 1         | 0.69%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s              | 1         | 0.69%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s               | 1         | 0.69%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s                 | 1         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s               | 1         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.69%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 0.69%   |
| SK hynix RAM H9HCNNNFAMALTR-NEE 16384MB Row Of Chips LPDDR4 3733MT/s | 1         | 0.69%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2048MB LPDDR3 1600MT/s               | 1         | 0.69%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR3 1600MT/s                 | 1         | 0.69%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s                         | 1         | 0.69%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                            | 1         | 0.69%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s                | 1         | 0.69%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                | 1         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 0.69%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 51        | 50%     |
| DDR4    | 29        | 28.43%  |
| SDRAM   | 7         | 6.86%   |
| DDR2    | 6         | 5.88%   |
| LPDDR4  | 4         | 3.92%   |
| LPDDR3  | 3         | 2.94%   |
| DDR     | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 68.09%  |
| DIMM         | 25        | 26.6%   |
| Row Of Chips | 3         | 3.19%   |
| RIMM         | 1         | 1.06%   |
| Unknown      | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 50        | 45.45%  |
| 8192  | 32        | 29.09%  |
| 2048  | 14        | 12.73%  |
| 1024  | 5         | 4.55%   |
| 16384 | 4         | 3.64%   |
| 32768 | 2         | 1.82%   |
| 512   | 1         | 0.91%   |
| 256   | 1         | 0.91%   |
| 128   | 1         | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 34.23%  |
| 2667    | 13        | 11.71%  |
| 1333    | 9         | 8.11%   |
| 1334    | 8         | 7.21%   |
| 3200    | 6         | 5.41%   |
| 2400    | 6         | 5.41%   |
| 2133    | 6         | 5.41%   |
| 667     | 3         | 2.7%    |
| Unknown | 3         | 2.7%    |
| 3600    | 2         | 1.8%    |
| 1867    | 2         | 1.8%    |
| 1067    | 2         | 1.8%    |
| 1066    | 2         | 1.8%    |
| 4267    | 1         | 0.9%    |
| 4199    | 1         | 0.9%    |
| 3733    | 1         | 0.9%    |
| 3266    | 1         | 0.9%    |
| 1866    | 1         | 0.9%    |
| 1639    | 1         | 0.9%    |
| 975     | 1         | 0.9%    |
| 800     | 1         | 0.9%    |
| 400     | 1         | 0.9%    |
| 333     | 1         | 0.9%    |
| 266     | 1         | 0.9%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP Deskjet 3510 series | 1         | 50%     |
| Canon MB2000 series    | 1         | 50%     |

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
| Chicony Electronics                    | 37        | 30.58%  |
| IMC Networks                           | 14        | 11.57%  |
| Cheng Uei Precision Industry (Foxlink) | 12        | 9.92%   |
| Realtek Semiconductor                  | 9         | 7.44%   |
| Suyin                                  | 8         | 6.61%   |
| Sunplus Innovation Technology          | 7         | 5.79%   |
| Lite-On Technology                     | 7         | 5.79%   |
| Microdia                               | 6         | 4.96%   |
| Ricoh                                  | 4         | 3.31%   |
| Quanta                                 | 3         | 2.48%   |
| Acer                                   | 3         | 2.48%   |
| Luxvisions Innotech Limited            | 2         | 1.65%   |
| Logitech                               | 2         | 1.65%   |
| Alcor Micro                            | 2         | 1.65%   |
| Syntek                                 | 1         | 0.83%   |
| Sunplus Technology                     | 1         | 0.83%   |
| Silicon Motion                         | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |
| ALi                                    | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 6         | 4.92%   |
| IMC Networks Integrated Camera                              | 5         | 4.1%    |
| Chicony HP Webcam [2 MP Macro]                              | 4         | 3.28%   |
| Microdia Integrated Webcam                                  | 3         | 2.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.46%   |
| Chicony HP Webcam                                           | 3         | 2.46%   |
| Chicony HP HD Webcam                                        | 3         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 2.46%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 2         | 1.64%   |
| Sunplus HP Universal Camera                                 | 2         | 1.64%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.64%   |
| Realtek USB Camera                                          | 2         | 1.64%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.64%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.64%   |
| Lite-On HP HD Webcam                                        | 2         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.64%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.64%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.64%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.64%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.64%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.64%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.64%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.82%   |
| Suyin WebCam                                                | 1         | 0.82%   |
| Suyin USB2.0 RGBIR Camera                                   | 1         | 0.82%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.82%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.82%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.82%   |
| Suyin HP Webcam-50                                          | 1         | 0.82%   |
| Sunplus 1.3M WebCam                                         | 1         | 0.82%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.82%   |
| Sunplus HP Truevision HD                                    | 1         | 0.82%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.82%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.82%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 0.82%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.82%   |
| Realtek Integrated Webcam                                   | 1         | 0.82%   |
| Realtek Integrated Camera                                   | 1         | 0.82%   |
| Realtek HP Webcam                                           | 1         | 0.82%   |
| Realtek HP Truevision HD integrated webcam                  | 1         | 0.82%   |
| Quanta VGA WebCam                                           | 1         | 0.82%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.82%   |
| Quanta HP Webcam                                            | 1         | 0.82%   |
| Microdia WebCam SC-13HDL12639P                              | 1         | 0.82%   |
| Microdia Integrated Webcam HD                               | 1         | 0.82%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 0.82%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 0.82%   |
| Logitech Webcam C270                                        | 1         | 0.82%   |
| Logitech Logi 4K Stream Edition                             | 1         | 0.82%   |
| Lite-On HP Webcam                                           | 1         | 0.82%   |
| Lite-On HP HD Camera                                        | 1         | 0.82%   |
| Lite-On EasyCamera 5M                                       | 1         | 0.82%   |
| IMC Networks Lenovo EasyCamera                              | 1         | 0.82%   |
| IMC Networks Integrated Webcam                              | 1         | 0.82%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 22        | 70.97%  |
| Synaptics             | 5         | 16.13%  |
| Elan Microelectronics | 3         | 9.68%   |
| Upek                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 8         | 25.81%  |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 3         | 9.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 9.68%   |
| Validity Sensors VFS491                                     | 2         | 6.45%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                       | 2         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                             | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 1         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 3.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 3.23%   |
| Elan ELAN:ARM-M4                                            | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 60%     |
| Alcor Micro | 5         | 33.33%  |
| O2 Micro    | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| Broadcom 5880                                                                | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 126       | 64.95%  |
| 1     | 53        | 27.32%  |
| 2     | 14        | 7.22%   |
| 3     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 37.8%   |
| Chipcard                 | 15        | 18.29%  |
| Graphics card            | 13        | 15.85%  |
| Net/wireless             | 6         | 7.32%   |
| Storage                  | 4         | 4.88%   |
| Communication controller | 3         | 3.66%   |
| Bluetooth                | 3         | 3.66%   |
| Unassigned class         | 2         | 2.44%   |
| Sound                    | 1         | 1.22%   |
| Net/ethernet             | 1         | 1.22%   |
| Multimedia controller    | 1         | 1.22%   |
| Modem                    | 1         | 1.22%   |
| Camera                   | 1         | 1.22%   |

