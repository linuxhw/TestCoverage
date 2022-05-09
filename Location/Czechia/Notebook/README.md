Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 1310

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [00f31c88cb](https://linux-hardware.org/?probe=00f31c88cb) | Apr 12, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| Acer          | Extensa 5630                | [1c814bd54d](https://linux-hardware.org/?probe=1c814bd54d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [aa729dad71](https://linux-hardware.org/?probe=aa729dad71) | Mar 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [628e312c2a](https://linux-hardware.org/?probe=628e312c2a) | Mar 08, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [41da3e93a9](https://linux-hardware.org/?probe=41da3e93a9) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [9eaab87e42](https://linux-hardware.org/?probe=9eaab87e42) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4a20a593d0](https://linux-hardware.org/?probe=4a20a593d0) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Google        | Akemi                       | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| HP            | OMEN by Laptop              | [dc7136f307](https://linux-hardware.org/?probe=dc7136f307) | Nov 19, 2021 |
| ASUSTek       | UX31E                       | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| Dell          | XPS 15 9550                 | [32ec7fd885](https://linux-hardware.org/?probe=32ec7fd885) | Oct 13, 2021 |
| Dell          | XPS 15 9550                 | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| ASUSTek       | UX31E                       | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| Sony          | VPCEB1E1E                   | [123ffa675e](https://linux-hardware.org/?probe=123ffa675e) | Oct 05, 2021 |
| ASUSTek       | UX31E                       | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Sony          | VPCEB1E1E                   | [f4ee361a8c](https://linux-hardware.org/?probe=f4ee361a8c) | Sep 25, 2021 |
| ASUSTek       | UX31E                       | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| HP            | 255 G4                      | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | [a7b62482c7](https://linux-hardware.org/?probe=a7b62482c7) | Sep 11, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Dell          | Latitude 5511               | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| Sony          | VPCEB1E1E                   | [7179056438](https://linux-hardware.org/?probe=7179056438) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Lenovo        | B50-80 80EW                 | [e3fd336b60](https://linux-hardware.org/?probe=e3fd336b60) | Aug 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | UX31E                       | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4736a01d82](https://linux-hardware.org/?probe=4736a01d82) | Aug 17, 2021 |
| Apple         | MacBookPro8,2               | [ca245e7e6a](https://linux-hardware.org/?probe=ca245e7e6a) | Aug 17, 2021 |
| ASUSTek       | UX31E                       | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| Acer          | Extensa 5630                | [29a71214dd](https://linux-hardware.org/?probe=29a71214dd) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef36f1dc4d](https://linux-hardware.org/?probe=ef36f1dc4d) | Aug 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [465b8fec82](https://linux-hardware.org/?probe=465b8fec82) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| Sony          | VPCEB1E1E                   | [a1cf02e78d](https://linux-hardware.org/?probe=a1cf02e78d) | Aug 14, 2021 |
| Sony          | VPCEB1E1E                   | [fa0edf6cbe](https://linux-hardware.org/?probe=fa0edf6cbe) | Aug 14, 2021 |
| ASUSTek       | UX31E                       | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| Acer          | Extensa 5630                | [43a2f7646a](https://linux-hardware.org/?probe=43a2f7646a) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| ASUSTek       | X553SA                      | [58875de3c3](https://linux-hardware.org/?probe=58875de3c3) | Aug 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c45478eae5](https://linux-hardware.org/?probe=c45478eae5) | Aug 12, 2021 |
| ASUSTek       | UX31E                       | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Latitude 5400               | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | UX31E                       | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [a52650a605](https://linux-hardware.org/?probe=a52650a605) | Aug 09, 2021 |
| Dell          | XPS 15 9550                 | [17e8358196](https://linux-hardware.org/?probe=17e8358196) | Aug 08, 2021 |
| Dell          | XPS 15 9550                 | [d668d80696](https://linux-hardware.org/?probe=d668d80696) | Aug 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [660b357dde](https://linux-hardware.org/?probe=660b357dde) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| Dell          | Latitude 7490               | [32c82c54b5](https://linux-hardware.org/?probe=32c82c54b5) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4ce0735262](https://linux-hardware.org/?probe=4ce0735262) | Aug 06, 2021 |
| HP            | Pavilion dv6500             | [983611f01f](https://linux-hardware.org/?probe=983611f01f) | Aug 05, 2021 |
| HP            | Pavilion dv6500             | [5e399cedc5](https://linux-hardware.org/?probe=5e399cedc5) | Aug 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| ASUSTek       | UX31E                       | [1e458b84be](https://linux-hardware.org/?probe=1e458b84be) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | [8951f246ed](https://linux-hardware.org/?probe=8951f246ed) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| Acer          | Swift SF514-54GT            | [bbe1d82ec7](https://linux-hardware.org/?probe=bbe1d82ec7) | Aug 02, 2021 |
| Sony          | VPCEB1E1E                   | [2bb17968f6](https://linux-hardware.org/?probe=2bb17968f6) | Aug 02, 2021 |
| Sony          | VPCEB1E1E                   | [10296df813](https://linux-hardware.org/?probe=10296df813) | Aug 02, 2021 |
| HP            | Pavilion g6                 | [f6ef28ddc4](https://linux-hardware.org/?probe=f6ef28ddc4) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [1d638fd7ae](https://linux-hardware.org/?probe=1d638fd7ae) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | [44b0620279](https://linux-hardware.org/?probe=44b0620279) | Jul 29, 2021 |
| HP            | ZBook 15 G6                 | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Laptop 15-da2xxx            | [b90f06f2eb](https://linux-hardware.org/?probe=b90f06f2eb) | Jul 28, 2021 |
| ASUSTek       | X556UQ                      | [9dee8d2c07](https://linux-hardware.org/?probe=9dee8d2c07) | Jul 27, 2021 |
| ASUSTek       | X556UQ                      | [88b38f3c6b](https://linux-hardware.org/?probe=88b38f3c6b) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [1ac5feaf25](https://linux-hardware.org/?probe=1ac5feaf25) | Jul 26, 2021 |
| ASUSTek       | F5RL                        | [3ca5d000c3](https://linux-hardware.org/?probe=3ca5d000c3) | Jul 26, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 429137G       | [ab41516068](https://linux-hardware.org/?probe=ab41516068) | Jul 25, 2021 |
| Acer          | Aspire V3-111P              | [e3aca6b408](https://linux-hardware.org/?probe=e3aca6b408) | Jul 24, 2021 |
| Acer          | Swift SF514-55GT            | [bb95e7c75b](https://linux-hardware.org/?probe=bb95e7c75b) | Jul 24, 2021 |
| Lenovo        | ThinkPad E495 20NE000BMC    | [487f5a67bf](https://linux-hardware.org/?probe=487f5a67bf) | Jul 24, 2021 |
| Sony          | VPCEB1E1E                   | [bbee4123c6](https://linux-hardware.org/?probe=bbee4123c6) | Jul 22, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [72cbbe92a0](https://linux-hardware.org/?probe=72cbbe92a0) | Jul 22, 2021 |
| HP            | EliteBook 850 G6            | [d0a8afe992](https://linux-hardware.org/?probe=d0a8afe992) | Jul 20, 2021 |
| Sony          | VPCEB1E1E                   | [ae09c176de](https://linux-hardware.org/?probe=ae09c176de) | Jul 20, 2021 |
| Sony          | VPCEB1E1E                   | [b57d8d169b](https://linux-hardware.org/?probe=b57d8d169b) | Jul 20, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [db3e0c8073](https://linux-hardware.org/?probe=db3e0c8073) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [594fbbbb38](https://linux-hardware.org/?probe=594fbbbb38) | Jul 17, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [d67f028892](https://linux-hardware.org/?probe=d67f028892) | Jul 15, 2021 |
| Toshiba       | Satellite L850              | [1697c7eaf6](https://linux-hardware.org/?probe=1697c7eaf6) | Jul 15, 2021 |
| Lenovo        | 0769BLG                     | [2d8e74d05c](https://linux-hardware.org/?probe=2d8e74d05c) | Jul 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Compaq 6730b (GB988EA)      | [ca4426ce30](https://linux-hardware.org/?probe=ca4426ce30) | Jul 11, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [eb84cf8198](https://linux-hardware.org/?probe=eb84cf8198) | Jul 10, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | EliteBook 840 G3            | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Apple         | MacBookAir7,2               | [a88a1df2f5](https://linux-hardware.org/?probe=a88a1df2f5) | Jul 07, 2021 |
| Apple         | MacBookAir7,2               | [77f6869d84](https://linux-hardware.org/?probe=77f6869d84) | Jul 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [dcad6f0184](https://linux-hardware.org/?probe=dcad6f0184) | Jul 06, 2021 |
| Packard Be... | EasyNote LS11HR             | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [761f3633cc](https://linux-hardware.org/?probe=761f3633cc) | Jul 05, 2021 |
| HP            | Pavilion dv7                | [43afdddf0e](https://linux-hardware.org/?probe=43afdddf0e) | Jul 04, 2021 |
| HP            | EliteBook 850 G6            | [27b614c70e](https://linux-hardware.org/?probe=27b614c70e) | Jul 04, 2021 |
| HP            | ProBook 4720s               | [2112bd8af0](https://linux-hardware.org/?probe=2112bd8af0) | Jul 03, 2021 |
| HP            | ProBook 4720s               | [f6be4a39bb](https://linux-hardware.org/?probe=f6be4a39bb) | Jul 03, 2021 |
| Dell          | Latitude E6400              | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [6e5f031c7a](https://linux-hardware.org/?probe=6e5f031c7a) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| Dell          | Latitude E6430              | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Acer          | E1-510                      | [74ed9018a7](https://linux-hardware.org/?probe=74ed9018a7) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c19ad895a0](https://linux-hardware.org/?probe=c19ad895a0) | Jul 02, 2021 |
| Acer          | E1-510                      | [1f5fc816d2](https://linux-hardware.org/?probe=1f5fc816d2) | Jul 02, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0260c559c1](https://linux-hardware.org/?probe=0260c559c1) | Jul 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [ee813e9b02](https://linux-hardware.org/?probe=ee813e9b02) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d26e9b673d](https://linux-hardware.org/?probe=d26e9b673d) | Jul 01, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [858ab16aee](https://linux-hardware.org/?probe=858ab16aee) | Jun 29, 2021 |
| Unknown       | Unknown                     | [4d4040c7bd](https://linux-hardware.org/?probe=4d4040c7bd) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Lenovo        | V330-15IKB 81AX             | [e6e76d81ec](https://linux-hardware.org/?probe=e6e76d81ec) | Jun 19, 2021 |
| Acer          | Nitro AN515-54              | [cf48431ab4](https://linux-hardware.org/?probe=cf48431ab4) | Jun 18, 2021 |
| Acer          | Nitro AN515-54              | [0db05d1420](https://linux-hardware.org/?probe=0db05d1420) | Jun 18, 2021 |
| Dell          | XPS 15 9550                 | [8c980bf3ca](https://linux-hardware.org/?probe=8c980bf3ca) | Jun 17, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| HP            | Pavilion dv5                | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| Dell          | Latitude E5510              | [648d4a58e1](https://linux-hardware.org/?probe=648d4a58e1) | Jun 06, 2021 |
| ASUSTek       | X55U                        | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion g6                 | [ca0eb881c4](https://linux-hardware.org/?probe=ca0eb881c4) | Jun 04, 2021 |
| HP            | Pavilion g6                 | [1bbb6d6e34](https://linux-hardware.org/?probe=1bbb6d6e34) | Jun 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e50e7e65b4](https://linux-hardware.org/?probe=e50e7e65b4) | May 28, 2021 |
| Insyde        | Braswell                    | [cedca78b3a](https://linux-hardware.org/?probe=cedca78b3a) | May 28, 2021 |
| HP            | ProBook 455 G7              | [fc1870a101](https://linux-hardware.org/?probe=fc1870a101) | May 28, 2021 |
| HP            | ProBook 455 G7              | [75f763a124](https://linux-hardware.org/?probe=75f763a124) | May 28, 2021 |
| HP            | Pavilion dv7                | [91d0ba53c9](https://linux-hardware.org/?probe=91d0ba53c9) | May 28, 2021 |
| ASUSTek       | K53SV                       | [a8fd68fccc](https://linux-hardware.org/?probe=a8fd68fccc) | May 26, 2021 |
| Dell          | G5 5587                     | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Dell          | Latitude 7420               | [38380cec21](https://linux-hardware.org/?probe=38380cec21) | May 22, 2021 |
| Dell          | Latitude 5511               | [6fdc31e1e9](https://linux-hardware.org/?probe=6fdc31e1e9) | May 21, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Dell          | XPS 15 9550                 | [ea3fabab64](https://linux-hardware.org/?probe=ea3fabab64) | May 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| HP            | ProBook 450 G7              | [cbde33b709](https://linux-hardware.org/?probe=cbde33b709) | May 16, 2021 |
| HP            | ProBook 4520s (WT121EA)     | [af5a9f1662](https://linux-hardware.org/?probe=af5a9f1662) | May 15, 2021 |
| HP            | ProBook 455 G7              | [faeed14705](https://linux-hardware.org/?probe=faeed14705) | May 15, 2021 |
| HP            | ProBook 455 G7              | [5a9153e5cc](https://linux-hardware.org/?probe=5a9153e5cc) | May 14, 2021 |
| Dell          | XPS 15 9550                 | [1bc7fd0025](https://linux-hardware.org/?probe=1bc7fd0025) | May 13, 2021 |
| Dell          | XPS 15 9550                 | [d3724e7086](https://linux-hardware.org/?probe=d3724e7086) | May 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [33069aaebb](https://linux-hardware.org/?probe=33069aaebb) | May 12, 2021 |
| Unknown       | Unknown                     | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Unknown       | Unknown                     | [e6eed05cc3](https://linux-hardware.org/?probe=e6eed05cc3) | May 12, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Acer          | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |
| Acer          | Aspire 5740                 | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ffaf24e2ab](https://linux-hardware.org/?probe=ffaf24e2ab) | May 06, 2021 |
| ASUSTek       | T100TA                      | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Lenovo        | B70-80 80MR                 | [17bea3da43](https://linux-hardware.org/?probe=17bea3da43) | May 04, 2021 |
| ASUSTek       | UX31E                       | [4acf6ce595](https://linux-hardware.org/?probe=4acf6ce595) | May 04, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Dell          | Vostro 3350                 | [9f2372a38c](https://linux-hardware.org/?probe=9f2372a38c) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36cd5135b6](https://linux-hardware.org/?probe=36cd5135b6) | May 02, 2021 |
| Sony          | VGN-FW31J                   | [87da15d562](https://linux-hardware.org/?probe=87da15d562) | May 01, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| Dell          | Latitude 5401               | [cd8363b187](https://linux-hardware.org/?probe=cd8363b187) | Apr 27, 2021 |
| Lenovo        | ThinkPad T430 23501F9       | [d855b9bf0f](https://linux-hardware.org/?probe=d855b9bf0f) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Acer          | TravelMate 6460             | [287952fb68](https://linux-hardware.org/?probe=287952fb68) | Apr 24, 2021 |
| Lenovo        | ThinkPad R500 2714AAG       | [0f62cca304](https://linux-hardware.org/?probe=0f62cca304) | Apr 20, 2021 |
| ASUSTek       | F5SL                        | [e1a84e3bdf](https://linux-hardware.org/?probe=e1a84e3bdf) | Apr 17, 2021 |
| HP            | ProBook 450 G7              | [45189929cc](https://linux-hardware.org/?probe=45189929cc) | Apr 17, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [4cc6403330](https://linux-hardware.org/?probe=4cc6403330) | Apr 15, 2021 |
| ASUSTek       | N73JQ                       | [29398a5494](https://linux-hardware.org/?probe=29398a5494) | Apr 15, 2021 |
| Dell          | XPS 13 9360                 | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [538618720c](https://linux-hardware.org/?probe=538618720c) | Apr 11, 2021 |
| HP            | ProBook 4530s               | [6b62bad9ad](https://linux-hardware.org/?probe=6b62bad9ad) | Apr 11, 2021 |
| HP            | Notebook                    | [b50b4aa14f](https://linux-hardware.org/?probe=b50b4aa14f) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| ASUSTek       | UX31E                       | [22901fcbc7](https://linux-hardware.org/?probe=22901fcbc7) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [71a5cf1e09](https://linux-hardware.org/?probe=71a5cf1e09) | Apr 11, 2021 |
| Fujitsu       | LIFEBOOK E5510              | [034e192416](https://linux-hardware.org/?probe=034e192416) | Apr 11, 2021 |
| Dell          | Inspiron 3501               | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Sony          | VPCEB1E1E                   | [d73e70bc03](https://linux-hardware.org/?probe=d73e70bc03) | Apr 10, 2021 |
| Toshiba       | Unknown                     | [0c98d143f2](https://linux-hardware.org/?probe=0c98d143f2) | Apr 09, 2021 |
| Dell          | Inspiron 5593               | [f41c784317](https://linux-hardware.org/?probe=f41c784317) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | [a1481ccf2a](https://linux-hardware.org/?probe=a1481ccf2a) | Apr 07, 2021 |
| Dell          | Inspiron 7348               | [bd1d84d6e7](https://linux-hardware.org/?probe=bd1d84d6e7) | Apr 07, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | [c7a893da2e](https://linux-hardware.org/?probe=c7a893da2e) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Precision 5530              | [64ca23f74b](https://linux-hardware.org/?probe=64ca23f74b) | Apr 06, 2021 |
| Toshiba       | Satellite L300D             | [35514af81d](https://linux-hardware.org/?probe=35514af81d) | Apr 04, 2021 |
| Dell          | Inspiron 5593               | [bf647eb6cd](https://linux-hardware.org/?probe=bf647eb6cd) | Apr 03, 2021 |
| Dell          | Inspiron N5110              | [6fe414f2da](https://linux-hardware.org/?probe=6fe414f2da) | Apr 02, 2021 |
| Acer          | Aspire A515-54G             | [4ceb1f2a16](https://linux-hardware.org/?probe=4ceb1f2a16) | Mar 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [fc6346c32b](https://linux-hardware.org/?probe=fc6346c32b) | Mar 29, 2021 |
| Dell          | Latitude 3400               | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| Lenovo        | B71-80 80RJ                 | [178235fdc8](https://linux-hardware.org/?probe=178235fdc8) | Mar 28, 2021 |
| HP            | EliteBook 850 G5            | [889d834138](https://linux-hardware.org/?probe=889d834138) | Mar 26, 2021 |
| HP            | 250 G2                      | [54d0d70b5f](https://linux-hardware.org/?probe=54d0d70b5f) | Mar 24, 2021 |
| Dell          | Inspiron 5570               | [4faf6a3407](https://linux-hardware.org/?probe=4faf6a3407) | Mar 23, 2021 |
| HP            | EliteBook 8530p             | [7ee41a2d5d](https://linux-hardware.org/?probe=7ee41a2d5d) | Mar 23, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [e4bd78422e](https://linux-hardware.org/?probe=e4bd78422e) | Mar 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [c99d44a48e](https://linux-hardware.org/?probe=c99d44a48e) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | [25834ccc9f](https://linux-hardware.org/?probe=25834ccc9f) | Mar 20, 2021 |
| Dell          | Latitude E6400              | [ae7a7ffce1](https://linux-hardware.org/?probe=ae7a7ffce1) | Mar 19, 2021 |
| HP            | 250 G6 Notebook PC          | [240e99298f](https://linux-hardware.org/?probe=240e99298f) | Mar 17, 2021 |
| Dell          | Latitude E6420              | [e7f5f57404](https://linux-hardware.org/?probe=e7f5f57404) | Mar 17, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [aad8ca4f6f](https://linux-hardware.org/?probe=aad8ca4f6f) | Mar 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [9f125de705](https://linux-hardware.org/?probe=9f125de705) | Mar 16, 2021 |
| Dell          | Latitude 5411               | [e992a2c9e6](https://linux-hardware.org/?probe=e992a2c9e6) | Mar 16, 2021 |
| HP            | 250 G6 Notebook PC          | [5d376beba8](https://linux-hardware.org/?probe=5d376beba8) | Mar 15, 2021 |
| HP            | ProBook 455 G7              | [c8bdece188](https://linux-hardware.org/?probe=c8bdece188) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [0072a02a5d](https://linux-hardware.org/?probe=0072a02a5d) | Mar 14, 2021 |
| Lenovo        | ThinkPad T400 6475R1G       | [9a6cc50c52](https://linux-hardware.org/?probe=9a6cc50c52) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [65c8aaa5aa](https://linux-hardware.org/?probe=65c8aaa5aa) | Mar 13, 2021 |
| HP            | Pavilion dv6                | [5eed23aaf7](https://linux-hardware.org/?probe=5eed23aaf7) | Mar 13, 2021 |
| Lenovo        | G500 20236                  | [453b938647](https://linux-hardware.org/?probe=453b938647) | Mar 13, 2021 |
| Lenovo        | G500 20236                  | [d4717a6af6](https://linux-hardware.org/?probe=d4717a6af6) | Mar 12, 2021 |
| HP            | 250 G6 Notebook PC          | [ecb1d8ee1d](https://linux-hardware.org/?probe=ecb1d8ee1d) | Mar 11, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [fc3b7d2f2b](https://linux-hardware.org/?probe=fc3b7d2f2b) | Mar 10, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [b1a4fc67b5](https://linux-hardware.org/?probe=b1a4fc67b5) | Mar 10, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [da00de06ed](https://linux-hardware.org/?probe=da00de06ed) | Mar 10, 2021 |
| HP            | EliteBook 2170p             | [dc06698753](https://linux-hardware.org/?probe=dc06698753) | Mar 10, 2021 |
| ASUSTek       | UX51VZA                     | [14ae24e6d8](https://linux-hardware.org/?probe=14ae24e6d8) | Mar 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [590b33fc27](https://linux-hardware.org/?probe=590b33fc27) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [094e63ef62](https://linux-hardware.org/?probe=094e63ef62) | Mar 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [fb0bf9134c](https://linux-hardware.org/?probe=fb0bf9134c) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [192f0fd756](https://linux-hardware.org/?probe=192f0fd756) | Mar 05, 2021 |
| Dell          | XPS 13 9300                 | [c4265bb6c4](https://linux-hardware.org/?probe=c4265bb6c4) | Mar 04, 2021 |
| Lenovo        | Flex 2 Pro-15 80FL          | [8e5ead087c](https://linux-hardware.org/?probe=8e5ead087c) | Mar 04, 2021 |
| Toshiba       | Satellite L740              | [91b7d3fb4d](https://linux-hardware.org/?probe=91b7d3fb4d) | Mar 02, 2021 |
| HP            | ProBook 470 G4              | [c3d85c83ec](https://linux-hardware.org/?probe=c3d85c83ec) | Feb 28, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [675be05d71](https://linux-hardware.org/?probe=675be05d71) | Feb 27, 2021 |
| Dell          | Latitude E6230              | [c3772d78aa](https://linux-hardware.org/?probe=c3772d78aa) | Feb 26, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5dcdaebb4e](https://linux-hardware.org/?probe=5dcdaebb4e) | Feb 26, 2021 |
| Dell          | Latitude E6410              | [6f3fa9e9f2](https://linux-hardware.org/?probe=6f3fa9e9f2) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| ASUSTek       | M50Vc                       | [8abf85e052](https://linux-hardware.org/?probe=8abf85e052) | Feb 24, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [58d3bac346](https://linux-hardware.org/?probe=58d3bac346) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Lenovo        | IdeaPad Z580                | [9cd18dc0e4](https://linux-hardware.org/?probe=9cd18dc0e4) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [3a9a5e9b7c](https://linux-hardware.org/?probe=3a9a5e9b7c) | Feb 24, 2021 |
| ASUSTek       | M50Vc                       | [295654ca20](https://linux-hardware.org/?probe=295654ca20) | Feb 24, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [f1d7117dc7](https://linux-hardware.org/?probe=f1d7117dc7) | Feb 23, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9d65892538](https://linux-hardware.org/?probe=9d65892538) | Feb 22, 2021 |
| Dell          | G5 5587                     | [0b0fc3b694](https://linux-hardware.org/?probe=0b0fc3b694) | Feb 22, 2021 |
| Lenovo        | ThinkPad T490 20N2000CMC    | [b23d98dd6a](https://linux-hardware.org/?probe=b23d98dd6a) | Feb 22, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [db101fb87e](https://linux-hardware.org/?probe=db101fb87e) | Feb 21, 2021 |
| HP            | ProBook 450 G7              | [71692bad33](https://linux-hardware.org/?probe=71692bad33) | Feb 20, 2021 |
| ASUSTek       | K55VM                       | [7e11b6bd85](https://linux-hardware.org/?probe=7e11b6bd85) | Feb 20, 2021 |
| Dell          | Latitude E6410              | [3334075d76](https://linux-hardware.org/?probe=3334075d76) | Feb 17, 2021 |
| HP            | EliteBook 2170p             | [36d10d9091](https://linux-hardware.org/?probe=36d10d9091) | Feb 16, 2021 |
| Dell          | Latitude 3400               | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| Lenovo        | Z710 20250                  | [c9694dd19b](https://linux-hardware.org/?probe=c9694dd19b) | Feb 15, 2021 |
| UMAX          | Visionbook 14Wa Plus        | [85de5460d8](https://linux-hardware.org/?probe=85de5460d8) | Feb 15, 2021 |
| ASUSTek       | F5RL                        | [6379e4d092](https://linux-hardware.org/?probe=6379e4d092) | Feb 12, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4ce0e6df68](https://linux-hardware.org/?probe=4ce0e6df68) | Feb 11, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| ASUSTek       | X453SA                      | [5e4fcc2492](https://linux-hardware.org/?probe=5e4fcc2492) | Feb 10, 2021 |
| HP            | EliteBook 850 G6            | [40877f0c5d](https://linux-hardware.org/?probe=40877f0c5d) | Feb 10, 2021 |
| HP            | EliteBook 840 G6            | [4caff97f56](https://linux-hardware.org/?probe=4caff97f56) | Feb 08, 2021 |
| Dell          | Latitude E6230              | [6562ca7135](https://linux-hardware.org/?probe=6562ca7135) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Sony          | VGN-FW31J                   | [3ac086a40c](https://linux-hardware.org/?probe=3ac086a40c) | Feb 07, 2021 |
| Dell          | Latitude E5450              | [9b2f037a8e](https://linux-hardware.org/?probe=9b2f037a8e) | Feb 06, 2021 |
| Dell          | Latitude E5450              | [9cce8a2306](https://linux-hardware.org/?probe=9cce8a2306) | Feb 06, 2021 |
| Dell          | Latitude E6410              | [02a7d362ab](https://linux-hardware.org/?probe=02a7d362ab) | Feb 05, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| Acer          | Aspire S3-391               | [c7205a1bc6](https://linux-hardware.org/?probe=c7205a1bc6) | Feb 02, 2021 |
| Lenovo        | G510 20238                  | [29483c03e0](https://linux-hardware.org/?probe=29483c03e0) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Dell          | Inspiron 7577               | [46453067b0](https://linux-hardware.org/?probe=46453067b0) | Jan 31, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [bbfd58bb17](https://linux-hardware.org/?probe=bbfd58bb17) | Jan 31, 2021 |
| Acer          | Aspire one                  | [596cf5fb05](https://linux-hardware.org/?probe=596cf5fb05) | Jan 30, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [ebe001400f](https://linux-hardware.org/?probe=ebe001400f) | Jan 30, 2021 |
| Acer          | Aspire V7-581G              | [bc8dcae398](https://linux-hardware.org/?probe=bc8dcae398) | Jan 28, 2021 |
| HP            | EliteBook 820 G2            | [655fd94c5b](https://linux-hardware.org/?probe=655fd94c5b) | Jan 27, 2021 |
| Dell          | Precision 5510              | [f548cf6034](https://linux-hardware.org/?probe=f548cf6034) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [59a1df6c23](https://linux-hardware.org/?probe=59a1df6c23) | Jan 27, 2021 |
| HP            | EliteBook 820 G2            | [0d9fb09cb0](https://linux-hardware.org/?probe=0d9fb09cb0) | Jan 27, 2021 |
| HP            | 250 G6 Notebook PC          | [e92acb1c9f](https://linux-hardware.org/?probe=e92acb1c9f) | Jan 25, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a519fed9ad](https://linux-hardware.org/?probe=a519fed9ad) | Jan 25, 2021 |
| Dell          | Latitude E5500              | [bf4f6f14c2](https://linux-hardware.org/?probe=bf4f6f14c2) | Jan 22, 2021 |
| Dell          | Precision 5510              | [023ebcd846](https://linux-hardware.org/?probe=023ebcd846) | Jan 21, 2021 |
| Dell          | Latitude E5440              | [462f80efe3](https://linux-hardware.org/?probe=462f80efe3) | Jan 20, 2021 |
| Dell          | Latitude D430               | [e364de4914](https://linux-hardware.org/?probe=e364de4914) | Jan 19, 2021 |
| Dell          | Latitude D430               | [632ede8190](https://linux-hardware.org/?probe=632ede8190) | Jan 19, 2021 |
| HP            | ProBook 4545s               | [a1361456ee](https://linux-hardware.org/?probe=a1361456ee) | Jan 19, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | [e6ea4283a5](https://linux-hardware.org/?probe=e6ea4283a5) | Jan 18, 2021 |
| Lenovo        | ThinkPad T400 6475Y4M       | [af004cce06](https://linux-hardware.org/?probe=af004cce06) | Jan 18, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [fc34b2d2b1](https://linux-hardware.org/?probe=fc34b2d2b1) | Jan 15, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [8ada2201db](https://linux-hardware.org/?probe=8ada2201db) | Jan 15, 2021 |
| Dell          | XPS 13 9360                 | [0a975a35b9](https://linux-hardware.org/?probe=0a975a35b9) | Jan 13, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMC    | [dc80798934](https://linux-hardware.org/?probe=dc80798934) | Jan 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b5b9926afa](https://linux-hardware.org/?probe=b5b9926afa) | Jan 11, 2021 |
| Sony          | VPCEB1M1E                   | [47b920b10a](https://linux-hardware.org/?probe=47b920b10a) | Jan 10, 2021 |
| HP            | Presario CQ57               | [f87fc12d71](https://linux-hardware.org/?probe=f87fc12d71) | Jan 10, 2021 |
| ASUSTek       | K50IJ                       | [986a4852e5](https://linux-hardware.org/?probe=986a4852e5) | Jan 09, 2021 |
| ASUSTek       | K50IJ                       | [260ee629ec](https://linux-hardware.org/?probe=260ee629ec) | Jan 09, 2021 |
| Dell          | Latitude E6430              | [33c8efc4d3](https://linux-hardware.org/?probe=33c8efc4d3) | Jan 09, 2021 |
| Dell          | Latitude E6430              | [6d373a3972](https://linux-hardware.org/?probe=6d373a3972) | Jan 09, 2021 |
| Dell          | Inspiron 5593               | [6d9d523357](https://linux-hardware.org/?probe=6d9d523357) | Jan 08, 2021 |
| ASUSTek       | G60JX                       | [e193018885](https://linux-hardware.org/?probe=e193018885) | Jan 03, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [9c7e318dbb](https://linux-hardware.org/?probe=9c7e318dbb) | Jan 01, 2021 |
| Acer          | TravelMate X314-51-MG       | [f2d686d743](https://linux-hardware.org/?probe=f2d686d743) | Jan 01, 2021 |
| Dell          | XPS 15 9550                 | [776e78f155](https://linux-hardware.org/?probe=776e78f155) | Jan 01, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [044a6a709e](https://linux-hardware.org/?probe=044a6a709e) | Dec 31, 2020 |
| ASUSTek       | F3E                         | [76935b8cde](https://linux-hardware.org/?probe=76935b8cde) | Dec 30, 2020 |
| ASUSTek       | F3E                         | [db7f14138d](https://linux-hardware.org/?probe=db7f14138d) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430 23444ZG       | [5904ca74c2](https://linux-hardware.org/?probe=5904ca74c2) | Dec 29, 2020 |
| HP            | EliteBook 840 G3            | [cd80521f36](https://linux-hardware.org/?probe=cd80521f36) | Dec 29, 2020 |
| Acer          | Aspire S3-391               | [cbb35e678a](https://linux-hardware.org/?probe=cbb35e678a) | Dec 29, 2020 |
| Lenovo        | G505s 20255                 | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [e43e83e37e](https://linux-hardware.org/?probe=e43e83e37e) | Dec 26, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [2352b3bdff](https://linux-hardware.org/?probe=2352b3bdff) | Dec 26, 2020 |
| MSI           | GE60 2QE                    | [57f71a51e7](https://linux-hardware.org/?probe=57f71a51e7) | Dec 25, 2020 |
| Dell          | Latitude E6430s             | [d9e710f80e](https://linux-hardware.org/?probe=d9e710f80e) | Dec 24, 2020 |
| Lenovo        | G780 20138                  | [337ed92b96](https://linux-hardware.org/?probe=337ed92b96) | Dec 21, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [c904ecb72d](https://linux-hardware.org/?probe=c904ecb72d) | Dec 18, 2020 |
| Lenovo        | G500 20236                  | [a9de7209d1](https://linux-hardware.org/?probe=a9de7209d1) | Dec 17, 2020 |
| Dell          | Latitude 7390               | [30de38003f](https://linux-hardware.org/?probe=30de38003f) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | [d4f9ccd7a6](https://linux-hardware.org/?probe=d4f9ccd7a6) | Dec 16, 2020 |
| Apple         | MacBookPro6,2               | [7faceca969](https://linux-hardware.org/?probe=7faceca969) | Dec 16, 2020 |
| Lenovo        | Flex 2-14 20404             | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| Lenovo        | ThinkPad T470 20HES18R19    | [11ce58f939](https://linux-hardware.org/?probe=11ce58f939) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| MSI           | MS-1688                     | [b56c16909d](https://linux-hardware.org/?probe=b56c16909d) | Dec 12, 2020 |
| Dell          | Precision 3551              | [ffc4c549c8](https://linux-hardware.org/?probe=ffc4c549c8) | Dec 11, 2020 |
| ASUSTek       | X550MJ                      | [66ed5909f8](https://linux-hardware.org/?probe=66ed5909f8) | Dec 10, 2020 |
| HP            | EliteBook 850 G5            | [ac22f08b80](https://linux-hardware.org/?probe=ac22f08b80) | Dec 09, 2020 |
| Dell          | Latitude E6520              | [ae5183024d](https://linux-hardware.org/?probe=ae5183024d) | Dec 08, 2020 |
| ASUSTek       | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| Intel         | STCK1A8LFC H67494-302       | [5cd8520aac](https://linux-hardware.org/?probe=5cd8520aac) | Dec 05, 2020 |
| Sony          | VGN-FW31J                   | [f12caf061a](https://linux-hardware.org/?probe=f12caf061a) | Dec 05, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5AD0... | [019dc4a90e](https://linux-hardware.org/?probe=019dc4a90e) | Dec 03, 2020 |
| Acer          | Extensa 5620                | [f2087b24cf](https://linux-hardware.org/?probe=f2087b24cf) | Dec 02, 2020 |
| ASUSTek       | GL552VX                     | [c93b1307eb](https://linux-hardware.org/?probe=c93b1307eb) | Dec 01, 2020 |
| Lenovo        | G500 20236                  | [f5d188f908](https://linux-hardware.org/?probe=f5d188f908) | Nov 28, 2020 |
| Sony          | VGN-Z21XN_B                 | [155a9f6fa6](https://linux-hardware.org/?probe=155a9f6fa6) | Nov 28, 2020 |
| HP            | Compaq 8510w                | [aa775a9324](https://linux-hardware.org/?probe=aa775a9324) | Nov 28, 2020 |
| Lenovo        | G500 20236                  | [89c53e4861](https://linux-hardware.org/?probe=89c53e4861) | Nov 27, 2020 |
| HP            | ProBook 6570b               | [679b85fd07](https://linux-hardware.org/?probe=679b85fd07) | Nov 27, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [db9601a874](https://linux-hardware.org/?probe=db9601a874) | Nov 26, 2020 |
| Dell          | Latitude 7390               | [f95f774a38](https://linux-hardware.org/?probe=f95f774a38) | Nov 26, 2020 |
| Jumper        | EZpad                       | [2c2ae2e061](https://linux-hardware.org/?probe=2c2ae2e061) | Nov 25, 2020 |
| Lenovo        | G500 20236                  | [e4b214e593](https://linux-hardware.org/?probe=e4b214e593) | Nov 24, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d39ba59434](https://linux-hardware.org/?probe=d39ba59434) | Nov 24, 2020 |
| HP            | ProBook 450 G7              | [2a3f3bd4a4](https://linux-hardware.org/?probe=2a3f3bd4a4) | Nov 22, 2020 |
| Jumper        | EZpad                       | [17c4e39db2](https://linux-hardware.org/?probe=17c4e39db2) | Nov 22, 2020 |
| Jumper        | EZpad                       | [807a525352](https://linux-hardware.org/?probe=807a525352) | Nov 21, 2020 |
| HP            | Pavilion TS 11              | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| Lenovo        | ThinkPad R61 8935WFB        | [b82d043b71](https://linux-hardware.org/?probe=b82d043b71) | Nov 18, 2020 |
| Dell          | XPS 15 7590                 | [e9b53cc836](https://linux-hardware.org/?probe=e9b53cc836) | Nov 18, 2020 |
| Acer          | Aspire V7-482P              | [c7b8a90092](https://linux-hardware.org/?probe=c7b8a90092) | Nov 17, 2020 |
| In-Sing       | NK81J                       | [2f129a4a67](https://linux-hardware.org/?probe=2f129a4a67) | Nov 16, 2020 |
| In-Sing       | NK81J                       | [a3282a8f65](https://linux-hardware.org/?probe=a3282a8f65) | Nov 16, 2020 |
| Lenovo        | ThinkPad Edge E530 3259B... | [c46ceddde5](https://linux-hardware.org/?probe=c46ceddde5) | Nov 16, 2020 |
| Acer          | Aspire E5-551G              | [8b8a83f80b](https://linux-hardware.org/?probe=8b8a83f80b) | Nov 15, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [3568e22cde](https://linux-hardware.org/?probe=3568e22cde) | Nov 14, 2020 |
| Acer          | Aspire V7-482P              | [cff0a4d702](https://linux-hardware.org/?probe=cff0a4d702) | Nov 14, 2020 |
| Dell          | XPS 13 9343                 | [4f86cf4cbf](https://linux-hardware.org/?probe=4f86cf4cbf) | Nov 13, 2020 |
| Fujitsu       | LIFEBOOK E734               | [5292c3d1c6](https://linux-hardware.org/?probe=5292c3d1c6) | Nov 13, 2020 |
| Lenovo        | G500 20236                  | [c721f58232](https://linux-hardware.org/?probe=c721f58232) | Nov 12, 2020 |
| Dell          | XPS 13 7390                 | [f816f90302](https://linux-hardware.org/?probe=f816f90302) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [41f4ce9090](https://linux-hardware.org/?probe=41f4ce9090) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [11e2a64b37](https://linux-hardware.org/?probe=11e2a64b37) | Nov 07, 2020 |
| HP            | Compaq Mini 110c-1100       | [1adcc4379a](https://linux-hardware.org/?probe=1adcc4379a) | Nov 07, 2020 |
| Lenovo        | G500 20236                  | [24a651c7ff](https://linux-hardware.org/?probe=24a651c7ff) | Nov 07, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [366328b790](https://linux-hardware.org/?probe=366328b790) | Nov 07, 2020 |
| Dell          | Precision 7740              | [887976cf88](https://linux-hardware.org/?probe=887976cf88) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | Compaq 6910p                | [116434c462](https://linux-hardware.org/?probe=116434c462) | Nov 04, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [02ed24cd0f](https://linux-hardware.org/?probe=02ed24cd0f) | Nov 04, 2020 |
| Lenovo        | G500 20236                  | [350dcf3c1d](https://linux-hardware.org/?probe=350dcf3c1d) | Nov 04, 2020 |
| MSI           | PS42 Modern 8RA             | [80629e1f55](https://linux-hardware.org/?probe=80629e1f55) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4b34114e72](https://linux-hardware.org/?probe=4b34114e72) | Nov 03, 2020 |
| Dell          | Latitude E5520              | [59e9f4557e](https://linux-hardware.org/?probe=59e9f4557e) | Nov 02, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [e49822ee09](https://linux-hardware.org/?probe=e49822ee09) | Nov 02, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [54079a5e32](https://linux-hardware.org/?probe=54079a5e32) | Nov 02, 2020 |
| ASUSTek       | X510UNR                     | [f97fa98c1f](https://linux-hardware.org/?probe=f97fa98c1f) | Nov 01, 2020 |
| HP            | ProBook 450 G7              | [d6ea9e1cd2](https://linux-hardware.org/?probe=d6ea9e1cd2) | Nov 01, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [dda213843b](https://linux-hardware.org/?probe=dda213843b) | Nov 01, 2020 |
| ASUSTek       | N73SV                       | [b2d4729f22](https://linux-hardware.org/?probe=b2d4729f22) | Nov 01, 2020 |
| Lenovo        | G500 20236                  | [12aa51894e](https://linux-hardware.org/?probe=12aa51894e) | Nov 01, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [f9755b992e](https://linux-hardware.org/?probe=f9755b992e) | Nov 01, 2020 |
| HP            | 255 G4                      | [e841543a23](https://linux-hardware.org/?probe=e841543a23) | Oct 31, 2020 |
| HP            | 255 G4                      | [79d387d0ab](https://linux-hardware.org/?probe=79d387d0ab) | Oct 31, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [85435abf0b](https://linux-hardware.org/?probe=85435abf0b) | Oct 31, 2020 |
| Lenovo        | G500 20236                  | [111bf85c2b](https://linux-hardware.org/?probe=111bf85c2b) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK U758               | [287e2c5d14](https://linux-hardware.org/?probe=287e2c5d14) | Oct 30, 2020 |
| Lenovo        | 3000 N100 0768Q4G           | [87ff568248](https://linux-hardware.org/?probe=87ff568248) | Oct 29, 2020 |
| Acer          | Extensa 5620                | [e7fab7440e](https://linux-hardware.org/?probe=e7fab7440e) | Oct 29, 2020 |
| Dell          | Inspiron 5593               | [3fbb5a72d7](https://linux-hardware.org/?probe=3fbb5a72d7) | Oct 28, 2020 |
| Toshiba       | Satellite P100              | [ea537c7d93](https://linux-hardware.org/?probe=ea537c7d93) | Oct 28, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b52e1d7ccf](https://linux-hardware.org/?probe=b52e1d7ccf) | Oct 27, 2020 |
| Acer          | Aspire E5-571G              | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Lenovo        | B51-80 80LM                 | [c40197b546](https://linux-hardware.org/?probe=c40197b546) | Oct 27, 2020 |
| HP            | EliteBook 830 G5            | [2ca9995218](https://linux-hardware.org/?probe=2ca9995218) | Oct 26, 2020 |
| Acer          | Aspire 8930                 | [fde733b7c7](https://linux-hardware.org/?probe=fde733b7c7) | Oct 25, 2020 |
| HP            | EliteBook 840 G5            | [4bba55301d](https://linux-hardware.org/?probe=4bba55301d) | Oct 24, 2020 |
| Dell          | Inspiron 5593               | [4f0c0f034e](https://linux-hardware.org/?probe=4f0c0f034e) | Oct 22, 2020 |
| Dell          | Inspiron 5593               | [aa31ceeb8f](https://linux-hardware.org/?probe=aa31ceeb8f) | Oct 22, 2020 |
| Dell          | Latitude E5520              | [2a250b5803](https://linux-hardware.org/?probe=2a250b5803) | Oct 22, 2020 |
| Dell          | Vostro 3350                 | [88e849444f](https://linux-hardware.org/?probe=88e849444f) | Oct 22, 2020 |
| HUAWEI        | MACH-WX9                    | [4b7b836641](https://linux-hardware.org/?probe=4b7b836641) | Oct 21, 2020 |
| Dell          | Vostro 1510                 | [dd9a477473](https://linux-hardware.org/?probe=dd9a477473) | Oct 21, 2020 |
| INET          | P201P                       | [644453ac6f](https://linux-hardware.org/?probe=644453ac6f) | Oct 21, 2020 |
| Dell          | Latitude E5540              | [7baf46ea1a](https://linux-hardware.org/?probe=7baf46ea1a) | Oct 21, 2020 |
| Sony          | VGN-FW31J                   | [a2ab2b1bee](https://linux-hardware.org/?probe=a2ab2b1bee) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [30cef457c4](https://linux-hardware.org/?probe=30cef457c4) | Oct 19, 2020 |
| HP            | ProBook 450 G5              | [054a64d6f2](https://linux-hardware.org/?probe=054a64d6f2) | Oct 18, 2020 |
| Lenovo        | G500 20236                  | [96e82da647](https://linux-hardware.org/?probe=96e82da647) | Oct 17, 2020 |
| MSI           | GE60 2QE                    | [246e6f7276](https://linux-hardware.org/?probe=246e6f7276) | Oct 17, 2020 |
| ASUSTek       | K50IJ                       | [0adb1dec20](https://linux-hardware.org/?probe=0adb1dec20) | Oct 16, 2020 |
| ASUSTek       | K50IJ                       | [c20f8b68f4](https://linux-hardware.org/?probe=c20f8b68f4) | Oct 16, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [9b67d68beb](https://linux-hardware.org/?probe=9b67d68beb) | Oct 14, 2020 |
| Lenovo        | ThinkPad T420 4178A9G       | [b0407d39c3](https://linux-hardware.org/?probe=b0407d39c3) | Oct 14, 2020 |
| Sony          | VGN-FW31J                   | [d9e0fff868](https://linux-hardware.org/?probe=d9e0fff868) | Oct 14, 2020 |
| Lenovo        | G510 20238                  | [65aff7828e](https://linux-hardware.org/?probe=65aff7828e) | Oct 13, 2020 |
| Sony          | VGN-FW31J                   | [eee35eb8e9](https://linux-hardware.org/?probe=eee35eb8e9) | Oct 13, 2020 |
| HP            | 250 G6 Notebook PC          | [8bdcdd3b6a](https://linux-hardware.org/?probe=8bdcdd3b6a) | Oct 13, 2020 |
| Lenovo        | G510 20238                  | [93221fbe75](https://linux-hardware.org/?probe=93221fbe75) | Oct 11, 2020 |
| Dell          | XPS 15 9500                 | [1a53ead300](https://linux-hardware.org/?probe=1a53ead300) | Oct 10, 2020 |
| Acer          | Aspire V3-551G              | [30f77b0594](https://linux-hardware.org/?probe=30f77b0594) | Oct 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [a14e9d2839](https://linux-hardware.org/?probe=a14e9d2839) | Oct 10, 2020 |
| Acer          | Aspire E5-551G              | [9911a6b479](https://linux-hardware.org/?probe=9911a6b479) | Oct 09, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | [726bdf3762](https://linux-hardware.org/?probe=726bdf3762) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | [289f93a7e6](https://linux-hardware.org/?probe=289f93a7e6) | Oct 08, 2020 |
| HP            | ProBook 455 G7              | [9649d645a8](https://linux-hardware.org/?probe=9649d645a8) | Oct 08, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [6870ec982e](https://linux-hardware.org/?probe=6870ec982e) | Oct 07, 2020 |
| Dell          | Latitude E5530 non-vPro     | [86aa78e5af](https://linux-hardware.org/?probe=86aa78e5af) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | [c535d537e1](https://linux-hardware.org/?probe=c535d537e1) | Oct 05, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4df9440dcd](https://linux-hardware.org/?probe=4df9440dcd) | Oct 04, 2020 |
| Timi          | TM1701                      | [816373e2e3](https://linux-hardware.org/?probe=816373e2e3) | Oct 03, 2020 |
| Lenovo        | ThinkPad Edge E535 3260E... | [0803716b4c](https://linux-hardware.org/?probe=0803716b4c) | Oct 02, 2020 |
| ASUSTek       | X202E                       | [12592ec3e9](https://linux-hardware.org/?probe=12592ec3e9) | Oct 01, 2020 |
| HP            | ProBook 450 G1              | [07e10b13eb](https://linux-hardware.org/?probe=07e10b13eb) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [6882b482eb](https://linux-hardware.org/?probe=6882b482eb) | Sep 27, 2020 |
| Acer          | Aspire V3-551G              | [8d1b0cab97](https://linux-hardware.org/?probe=8d1b0cab97) | Sep 27, 2020 |
| Acer          | Extensa 5620                | [7826e95ae0](https://linux-hardware.org/?probe=7826e95ae0) | Sep 27, 2020 |
| HP            | 500 Notebook PC (RQ260AA... | [01927c1bb9](https://linux-hardware.org/?probe=01927c1bb9) | Sep 27, 2020 |
| Sony          | VGN-FW31J                   | [3b9477c3ef](https://linux-hardware.org/?probe=3b9477c3ef) | Sep 27, 2020 |
| Lenovo        | ThinkPad T440 20B7A0VQMC    | [ee12117181](https://linux-hardware.org/?probe=ee12117181) | Sep 25, 2020 |
| Dell          | XPS 13 9370                 | [6790f8d26f](https://linux-hardware.org/?probe=6790f8d26f) | Sep 24, 2020 |
| Dell          | Latitude E7440              | [c6208fcbea](https://linux-hardware.org/?probe=c6208fcbea) | Sep 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2f26cddf81](https://linux-hardware.org/?probe=2f26cddf81) | Sep 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [440e2b757b](https://linux-hardware.org/?probe=440e2b757b) | Sep 18, 2020 |
| ASUSTek       | X202E                       | [e9e1d090a6](https://linux-hardware.org/?probe=e9e1d090a6) | Sep 17, 2020 |
| Panasonic     | CF-NX2LDHTS                 | [0a48a263df](https://linux-hardware.org/?probe=0a48a263df) | Sep 13, 2020 |
| Lenovo        | G500 20236                  | [d7d1e754de](https://linux-hardware.org/?probe=d7d1e754de) | Sep 13, 2020 |
| HP            | ProBook 450 G1              | [18a6803124](https://linux-hardware.org/?probe=18a6803124) | Sep 12, 2020 |
| Dell          | XPS 15 7590                 | [5111093893](https://linux-hardware.org/?probe=5111093893) | Sep 10, 2020 |
| Acer          | Aspire E5-551G              | [df6578f3e9](https://linux-hardware.org/?probe=df6578f3e9) | Sep 09, 2020 |
| Lenovo        | B50-80 80EW                 | [d29a056568](https://linux-hardware.org/?probe=d29a056568) | Sep 05, 2020 |
| Dell          | Latitude 3400               | [e1a6c8dd9b](https://linux-hardware.org/?probe=e1a6c8dd9b) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 4291B66       | [2f215c5090](https://linux-hardware.org/?probe=2f215c5090) | Sep 03, 2020 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [63815ec19a](https://linux-hardware.org/?probe=63815ec19a) | Sep 03, 2020 |
| Toshiba       | Satellite A300              | [9372f4dfac](https://linux-hardware.org/?probe=9372f4dfac) | Sep 03, 2020 |
| Acer          | Aspire A515-51              | [1563288867](https://linux-hardware.org/?probe=1563288867) | Sep 03, 2020 |
| Dell          | Latitude E5420              | [e384c49b73](https://linux-hardware.org/?probe=e384c49b73) | Sep 02, 2020 |
| HP            | ProBook 450 G5              | [e3ff6fe1b2](https://linux-hardware.org/?probe=e3ff6fe1b2) | Sep 01, 2020 |
| Lenovo        | G580 20150                  | [0615cf6255](https://linux-hardware.org/?probe=0615cf6255) | Aug 30, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [91d1161c68](https://linux-hardware.org/?probe=91d1161c68) | Aug 28, 2020 |
| HP            | ProBook 450 G1              | [129e313b94](https://linux-hardware.org/?probe=129e313b94) | Aug 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [82eff7291c](https://linux-hardware.org/?probe=82eff7291c) | Aug 28, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [70559c8ed2](https://linux-hardware.org/?probe=70559c8ed2) | Aug 28, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [09562f975b](https://linux-hardware.org/?probe=09562f975b) | Aug 28, 2020 |
| Dell          | Latitude 5401               | [fdb1d25e99](https://linux-hardware.org/?probe=fdb1d25e99) | Aug 27, 2020 |
| HP            | Presario CQ61               | [109f1ed355](https://linux-hardware.org/?probe=109f1ed355) | Aug 24, 2020 |
| Sony          | VGN-FW31J                   | [529ce44f71](https://linux-hardware.org/?probe=529ce44f71) | Aug 24, 2020 |
| HP            | EliteBook 850 G5            | [a178b4c510](https://linux-hardware.org/?probe=a178b4c510) | Aug 18, 2020 |
| HP            | EliteBook 850 G5            | [177085a712](https://linux-hardware.org/?probe=177085a712) | Aug 18, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [66477c8d6d](https://linux-hardware.org/?probe=66477c8d6d) | Aug 16, 2020 |
| Sony          | VGN-FW31J                   | [fc1b378b12](https://linux-hardware.org/?probe=fc1b378b12) | Aug 16, 2020 |
| Sony          | VGN-FW31J                   | [d8328832cd](https://linux-hardware.org/?probe=d8328832cd) | Aug 15, 2020 |
| HP            | EliteBook 840 G3            | [22fb77a6ee](https://linux-hardware.org/?probe=22fb77a6ee) | Aug 14, 2020 |
| Lenovo        | ThinkPad P51 20HHS16Q00     | [6742184806](https://linux-hardware.org/?probe=6742184806) | Aug 12, 2020 |
| HP            | EliteBook 840 G5            | [fafcd60747](https://linux-hardware.org/?probe=fafcd60747) | Aug 12, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| HP            | ProBook 650 G1              | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| DATABOX       | BusinessTab A10             | [40935402ee](https://linux-hardware.org/?probe=40935402ee) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| AMI           | Intel                       | [0158c3e564](https://linux-hardware.org/?probe=0158c3e564) | Aug 05, 2020 |
| DATABOX       | BusinessTab A10             | [3c57bb6b77](https://linux-hardware.org/?probe=3c57bb6b77) | Aug 05, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [62f9d9cc6b](https://linux-hardware.org/?probe=62f9d9cc6b) | Aug 03, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4eb7fb1ff6](https://linux-hardware.org/?probe=4eb7fb1ff6) | Jul 30, 2020 |
| Acer          | Aspire one                  | [7b088b2172](https://linux-hardware.org/?probe=7b088b2172) | Jul 25, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [87d5cec59e](https://linux-hardware.org/?probe=87d5cec59e) | Jul 25, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [31e73b2be3](https://linux-hardware.org/?probe=31e73b2be3) | Jul 25, 2020 |
| ASUSTek       | UX303UB                     | [09c02580de](https://linux-hardware.org/?probe=09c02580de) | Jul 23, 2020 |
| Acer          | Aspire A515-51G             | [95225ea41e](https://linux-hardware.org/?probe=95225ea41e) | Jul 23, 2020 |
| HP            | ProBook 430 G5              | [20568abfd1](https://linux-hardware.org/?probe=20568abfd1) | Jul 22, 2020 |
| HP            | ProBook 450 G1              | [683c0937ec](https://linux-hardware.org/?probe=683c0937ec) | Jul 21, 2020 |
| HP            | EliteBook 840 G5            | [2541c55ef9](https://linux-hardware.org/?probe=2541c55ef9) | Jul 18, 2020 |
| Sony          | VGN-FW21M                   | [d1010c28c7](https://linux-hardware.org/?probe=d1010c28c7) | Jul 18, 2020 |
| Dell          | Latitude 5401               | [31ac483afd](https://linux-hardware.org/?probe=31ac483afd) | Jul 18, 2020 |
| Dell          | Latitude 5401               | [ba847cf490](https://linux-hardware.org/?probe=ba847cf490) | Jul 17, 2020 |
| Lenovo        | ThinkPad T420 4180B12       | [8d78aded6b](https://linux-hardware.org/?probe=8d78aded6b) | Jul 17, 2020 |
| HP            | Presario CQ61               | [b4380f6a6a](https://linux-hardware.org/?probe=b4380f6a6a) | Jul 15, 2020 |
| HP            | Presario CQ61               | [3471fd4461](https://linux-hardware.org/?probe=3471fd4461) | Jul 15, 2020 |
| Dell          | Latitude 5401               | [d5cde026f3](https://linux-hardware.org/?probe=d5cde026f3) | Jul 14, 2020 |
| Acer          | Aspire 5930                 | [cf11228939](https://linux-hardware.org/?probe=cf11228939) | Jul 13, 2020 |
| Dell          | Latitude E7440              | [aec15e23f5](https://linux-hardware.org/?probe=aec15e23f5) | Jul 12, 2020 |
| Dell          | Latitude 5401               | [3ed0caa94c](https://linux-hardware.org/?probe=3ed0caa94c) | Jul 12, 2020 |
| Dell          | Latitude 5401               | [98717741ba](https://linux-hardware.org/?probe=98717741ba) | Jul 11, 2020 |
| Dell          | XPS 15 9560                 | [20b96fb678](https://linux-hardware.org/?probe=20b96fb678) | Jul 11, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [32cb4f1652](https://linux-hardware.org/?probe=32cb4f1652) | Jul 04, 2020 |
| Acer          | Extensa 5235                | [50f85b5c1d](https://linux-hardware.org/?probe=50f85b5c1d) | Jul 03, 2020 |
| Acer          | Extensa 5235                | [d03201b49a](https://linux-hardware.org/?probe=d03201b49a) | Jul 03, 2020 |
| MSI           | GF63 8RC                    | [080ebd9b80](https://linux-hardware.org/?probe=080ebd9b80) | Jul 02, 2020 |
| MSI           | GF63 8RC                    | [14e7833eea](https://linux-hardware.org/?probe=14e7833eea) | Jul 02, 2020 |
| HP            | EliteBook 8440p             | [0f6ba1b2e7](https://linux-hardware.org/?probe=0f6ba1b2e7) | Jun 29, 2020 |
| HP            | EliteBook 8440p             | [28e120bcfc](https://linux-hardware.org/?probe=28e120bcfc) | Jun 29, 2020 |
| Lenovo        | ThinkPad E580 20KS006AMC    | [1e8b0ede4b](https://linux-hardware.org/?probe=1e8b0ede4b) | Jun 29, 2020 |
| Acer          | Predator G5-793             | [83238b7fee](https://linux-hardware.org/?probe=83238b7fee) | Jun 28, 2020 |
| HP            | ProBook 650 G1              | [51b7fb4eed](https://linux-hardware.org/?probe=51b7fb4eed) | Jun 28, 2020 |
| ASUSTek       | G750JX                      | [f13199ca2e](https://linux-hardware.org/?probe=f13199ca2e) | Jun 22, 2020 |
| Acer          | Aspire 5310                 | [08abc8a867](https://linux-hardware.org/?probe=08abc8a867) | Jun 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5b3ce338db](https://linux-hardware.org/?probe=5b3ce338db) | Jun 21, 2020 |
| Sony          | VPCEH2J1E                   | [5cc5278df7](https://linux-hardware.org/?probe=5cc5278df7) | Jun 21, 2020 |
| IBM           | ThinkPad T42 2374Q16        | [58f9ce5671](https://linux-hardware.org/?probe=58f9ce5671) | Jun 21, 2020 |
| Acer          | Aspire 5735                 | [6f425e04b7](https://linux-hardware.org/?probe=6f425e04b7) | Jun 20, 2020 |
| Acer          | Aspire 5735                 | [a75d5e3368](https://linux-hardware.org/?probe=a75d5e3368) | Jun 20, 2020 |
| HP            | 250 G6 Notebook PC          | [f6cfdc816b](https://linux-hardware.org/?probe=f6cfdc816b) | Jun 20, 2020 |
| HP            | ProBook 455 G7              | [b90590bf42](https://linux-hardware.org/?probe=b90590bf42) | Jun 19, 2020 |
| Lenovo        | G50-30 80G0                 | [d9f9497fd7](https://linux-hardware.org/?probe=d9f9497fd7) | Jun 19, 2020 |
| HP            | 15                          | [72292536fc](https://linux-hardware.org/?probe=72292536fc) | Jun 18, 2020 |
| HP            | ProBook 430 G5              | [65159c7bfd](https://linux-hardware.org/?probe=65159c7bfd) | Jun 14, 2020 |
| HP            | ProBook 430 G5              | [43d3a1e357](https://linux-hardware.org/?probe=43d3a1e357) | Jun 14, 2020 |
| ASUSTek       | X510UNR                     | [244e7941f0](https://linux-hardware.org/?probe=244e7941f0) | Jun 12, 2020 |
| HP            | ProBook 455 G7              | [92527e490f](https://linux-hardware.org/?probe=92527e490f) | Jun 11, 2020 |
| HP            | ProBook 450 G1              | [aae53d6154](https://linux-hardware.org/?probe=aae53d6154) | Jun 09, 2020 |
| Lenovo        | ThinkPad T430 2349U4B       | [d65021b09d](https://linux-hardware.org/?probe=d65021b09d) | Jun 09, 2020 |
| Acer          | Aspire V3-112P              | [9a6e18cb80](https://linux-hardware.org/?probe=9a6e18cb80) | Jun 08, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [2902bb9460](https://linux-hardware.org/?probe=2902bb9460) | Jun 06, 2020 |
| Lenovo        | ThinkPad P52 20M9001LMC     | [065bddf59b](https://linux-hardware.org/?probe=065bddf59b) | Jun 06, 2020 |
| Acer          | Aspire 5530                 | [ebb35f1079](https://linux-hardware.org/?probe=ebb35f1079) | Jun 05, 2020 |
| HP            | EliteBook Folio 9470m       | [efa1beda42](https://linux-hardware.org/?probe=efa1beda42) | Jun 04, 2020 |
| ASUSTek       | X555LD                      | [5fcb4e6866](https://linux-hardware.org/?probe=5fcb4e6866) | Jun 03, 2020 |
| Acer          | Aspire V3-551G              | [e205e6c135](https://linux-hardware.org/?probe=e205e6c135) | Jun 03, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a84d2b6813](https://linux-hardware.org/?probe=a84d2b6813) | May 31, 2020 |
| Lenovo        | ThinkPad T490 20N2S03R00    | [707f01ab45](https://linux-hardware.org/?probe=707f01ab45) | May 30, 2020 |
| Dell          | Latitude E7240              | [6289a0fd13](https://linux-hardware.org/?probe=6289a0fd13) | May 28, 2020 |
| ASUSTek       | A7Sv                        | [785a42eb5b](https://linux-hardware.org/?probe=785a42eb5b) | May 27, 2020 |
| ASUSTek       | A7Sv                        | [a820cc1186](https://linux-hardware.org/?probe=a820cc1186) | May 27, 2020 |
| HP            | ProBook 450 G1              | [d2f6e88d35](https://linux-hardware.org/?probe=d2f6e88d35) | May 26, 2020 |
| MSI           | PS63 Modern 8M              | [a0f30a47ee](https://linux-hardware.org/?probe=a0f30a47ee) | May 24, 2020 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [37c69ea279](https://linux-hardware.org/?probe=37c69ea279) | May 24, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMC    | [1dcc1bede5](https://linux-hardware.org/?probe=1dcc1bede5) | May 24, 2020 |
| Acer          | Aspire A315-32              | [ce0e45003c](https://linux-hardware.org/?probe=ce0e45003c) | May 24, 2020 |
| Apple         | MacBookPro11,1              | [b0deaea4a8](https://linux-hardware.org/?probe=b0deaea4a8) | May 22, 2020 |
| Sony          | VPCEB3S1E                   | [14c94e8a5d](https://linux-hardware.org/?probe=14c94e8a5d) | May 22, 2020 |
| Dell          | Vostro 5568                 | [be3b19e976](https://linux-hardware.org/?probe=be3b19e976) | May 20, 2020 |
| Dell          | Latitude E7450              | [3d80b3ce29](https://linux-hardware.org/?probe=3d80b3ce29) | May 19, 2020 |
| Dell          | Latitude 5500               | [2264b71779](https://linux-hardware.org/?probe=2264b71779) | May 19, 2020 |
| Dell          | Latitude 5500               | [59b114b000](https://linux-hardware.org/?probe=59b114b000) | May 19, 2020 |
| Dell          | Latitude 5500               | [57af2e8877](https://linux-hardware.org/?probe=57af2e8877) | May 19, 2020 |
| ASUSTek       | A6R                         | [233eb1cb5a](https://linux-hardware.org/?probe=233eb1cb5a) | May 16, 2020 |
| HP            | ProBook 655 G1              | [b692081c5e](https://linux-hardware.org/?probe=b692081c5e) | May 16, 2020 |
| ASUSTek       | A6R                         | [5336380e70](https://linux-hardware.org/?probe=5336380e70) | May 16, 2020 |
| ASUSTek       | A6R                         | [b8bb81dd95](https://linux-hardware.org/?probe=b8bb81dd95) | May 16, 2020 |
| ASUSTek       | A6R                         | [364f7ae63c](https://linux-hardware.org/?probe=364f7ae63c) | May 16, 2020 |
| ASUSTek       | A6R                         | [6253744b9d](https://linux-hardware.org/?probe=6253744b9d) | May 16, 2020 |
| HP            | ProBook 450 G5              | [453202ad57](https://linux-hardware.org/?probe=453202ad57) | May 15, 2020 |
| HP            | ProBook 450 G5              | [b8f804e926](https://linux-hardware.org/?probe=b8f804e926) | May 15, 2020 |
| HP            | ProBook 450 G5              | [5d83f15483](https://linux-hardware.org/?probe=5d83f15483) | May 15, 2020 |
| HP            | ProBook 450 G5              | [99e7ac6aa7](https://linux-hardware.org/?probe=99e7ac6aa7) | May 15, 2020 |
| HP            | EliteBook 745 G6            | [3ae8a35f34](https://linux-hardware.org/?probe=3ae8a35f34) | May 15, 2020 |
| Dell          | Precision 5530              | [4cdc8a6d48](https://linux-hardware.org/?probe=4cdc8a6d48) | May 12, 2020 |
| Dell          | XPS 15 9560                 | [74b2ff5470](https://linux-hardware.org/?probe=74b2ff5470) | May 12, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [56fbe252d0](https://linux-hardware.org/?probe=56fbe252d0) | May 11, 2020 |
| HP            | ProBook 450 G5              | [709526e6b6](https://linux-hardware.org/?probe=709526e6b6) | May 10, 2020 |
| Dell          | XPS 15 9570                 | [6d6afe11e6](https://linux-hardware.org/?probe=6d6afe11e6) | May 10, 2020 |
| HP            | ProBook 655 G1              | [7260da6e47](https://linux-hardware.org/?probe=7260da6e47) | May 09, 2020 |
| Dell          | Latitude 5401               | [051cf9ab6f](https://linux-hardware.org/?probe=051cf9ab6f) | May 05, 2020 |
| Lenovo        | Z50-75 80EC                 | [324efc564b](https://linux-hardware.org/?probe=324efc564b) | May 05, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [b225d7378d](https://linux-hardware.org/?probe=b225d7378d) | May 04, 2020 |
| Lenovo        | ThinkPad X131e 3368A77      | [c376fe66df](https://linux-hardware.org/?probe=c376fe66df) | May 03, 2020 |
| HP            | Notebook                    | [44e80e2be4](https://linux-hardware.org/?probe=44e80e2be4) | May 02, 2020 |
| Lenovo        | Z50-75 80EC                 | [e60aeab4a5](https://linux-hardware.org/?probe=e60aeab4a5) | May 02, 2020 |
| HP            | EliteBook 8460p             | [bbcfbdb441](https://linux-hardware.org/?probe=bbcfbdb441) | May 02, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [88fa9aea33](https://linux-hardware.org/?probe=88fa9aea33) | May 01, 2020 |
| HP            | Notebook                    | [f423ba2d9f](https://linux-hardware.org/?probe=f423ba2d9f) | May 01, 2020 |
| Dell          | Latitude E6420              | [8adb8146f8](https://linux-hardware.org/?probe=8adb8146f8) | Apr 30, 2020 |
| Dell          | Latitude E6420              | [c5901834f5](https://linux-hardware.org/?probe=c5901834f5) | Apr 30, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [eabe84a8c7](https://linux-hardware.org/?probe=eabe84a8c7) | Apr 30, 2020 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [87a660b2af](https://linux-hardware.org/?probe=87a660b2af) | Apr 30, 2020 |
| Lenovo        | IdeaPad Y580                | [147e7ec673](https://linux-hardware.org/?probe=147e7ec673) | Apr 29, 2020 |
| Dell          | Latitude E5520              | [36e044faf3](https://linux-hardware.org/?probe=36e044faf3) | Apr 26, 2020 |
| Lenovo        | ThinkPad T61 7661BM5        | [b0e15a571e](https://linux-hardware.org/?probe=b0e15a571e) | Apr 26, 2020 |
| Dell          | Inspiron 5593               | [85d76a23e6](https://linux-hardware.org/?probe=85d76a23e6) | Apr 26, 2020 |
| Dell          | Latitude E6400              | [a4ed50bb29](https://linux-hardware.org/?probe=a4ed50bb29) | Apr 26, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | [5fb1e739a2](https://linux-hardware.org/?probe=5fb1e739a2) | Apr 26, 2020 |
| HP            | EliteBook 840 G5            | [bc9a01a10e](https://linux-hardware.org/?probe=bc9a01a10e) | Apr 24, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | [20d9b1ed17](https://linux-hardware.org/?probe=20d9b1ed17) | Apr 24, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | [cfaba4a598](https://linux-hardware.org/?probe=cfaba4a598) | Apr 24, 2020 |
| Lenovo        | ThinkPad R61 8933W6M        | [536beaf5b9](https://linux-hardware.org/?probe=536beaf5b9) | Apr 24, 2020 |
| Lenovo        | G50-45 80E3                 | [2d8aac7989](https://linux-hardware.org/?probe=2d8aac7989) | Apr 21, 2020 |
| Lenovo        | G50-45 80E3                 | [1a161abbf2](https://linux-hardware.org/?probe=1a161abbf2) | Apr 21, 2020 |
| ASUSTek       | K50IJ                       | [a1227639ac](https://linux-hardware.org/?probe=a1227639ac) | Apr 20, 2020 |
| ASUSTek       | K50IJ                       | [8b66782c6e](https://linux-hardware.org/?probe=8b66782c6e) | Apr 20, 2020 |
| ASUSTek       | P43SJ                       | [43a6fcc05e](https://linux-hardware.org/?probe=43a6fcc05e) | Apr 18, 2020 |
| Lenovo        | IdeaPad Y580                | [07c55f3d7b](https://linux-hardware.org/?probe=07c55f3d7b) | Apr 17, 2020 |
| Lenovo        | IdeaPad Y580                | [4f7c17303a](https://linux-hardware.org/?probe=4f7c17303a) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| HP            | EliteBook 840 G6            | [fcc4ad36bb](https://linux-hardware.org/?probe=fcc4ad36bb) | Apr 13, 2020 |
| Lenovo        | G40-45 80E1                 | [218110c7a1](https://linux-hardware.org/?probe=218110c7a1) | Apr 13, 2020 |
| ASUSTek       | X200CA                      | [3c52d09634](https://linux-hardware.org/?probe=3c52d09634) | Apr 12, 2020 |
| Lenovo        | Z50-75 80EC                 | [5817c93bd7](https://linux-hardware.org/?probe=5817c93bd7) | Apr 12, 2020 |
| ASUSTek       | A6R                         | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [7a1832a78f](https://linux-hardware.org/?probe=7a1832a78f) | Apr 11, 2020 |
| Dynabook      | dynabook PORTEGE X30-F      | [6b0ed71af5](https://linux-hardware.org/?probe=6b0ed71af5) | Apr 09, 2020 |
| Lenovo        | Z50-75 80EC                 | [7153cca02a](https://linux-hardware.org/?probe=7153cca02a) | Apr 07, 2020 |
| Acer          | Aspire 1410                 | [6cba695c63](https://linux-hardware.org/?probe=6cba695c63) | Apr 06, 2020 |
| Lenovo        | ThinkPad T510 4384Y13       | [327f86287f](https://linux-hardware.org/?probe=327f86287f) | Apr 06, 2020 |
| Lenovo        | ThinkPad T510 4384Y13       | [9cee021d7e](https://linux-hardware.org/?probe=9cee021d7e) | Apr 06, 2020 |
| Lenovo        | ThinkPad T510 4384Y13       | [cb50b8f064](https://linux-hardware.org/?probe=cb50b8f064) | Apr 06, 2020 |
| HP            | EliteBook 6930p             | [399229abd3](https://linux-hardware.org/?probe=399229abd3) | Apr 05, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [cd2c9976bc](https://linux-hardware.org/?probe=cd2c9976bc) | Apr 05, 2020 |
| Lenovo        | G40-45 80E1                 | [867e8c364d](https://linux-hardware.org/?probe=867e8c364d) | Apr 04, 2020 |
| Lenovo        | G40-45 80E1                 | [e34e785eb4](https://linux-hardware.org/?probe=e34e785eb4) | Apr 04, 2020 |
| Lenovo        | G40-45 80E1                 | [e3164413c4](https://linux-hardware.org/?probe=e3164413c4) | Apr 04, 2020 |
| HP            | EliteBook 840 G5            | [d556695db0](https://linux-hardware.org/?probe=d556695db0) | Apr 03, 2020 |
| HP            | Laptop 17-bs0xx             | [7ed301984e](https://linux-hardware.org/?probe=7ed301984e) | Apr 03, 2020 |
| HP            | ProBook 4525s               | [cb0a6c08db](https://linux-hardware.org/?probe=cb0a6c08db) | Mar 31, 2020 |
| HP            | ProBook 4525s               | [dc9164d939](https://linux-hardware.org/?probe=dc9164d939) | Mar 28, 2020 |
| Fujitsu       | LIFEBOOK S904               | [7e177f1dae](https://linux-hardware.org/?probe=7e177f1dae) | Mar 26, 2020 |
| ASUSTek       | UX305CA                     | [c3ef67f0ed](https://linux-hardware.org/?probe=c3ef67f0ed) | Mar 25, 2020 |
| ASUSTek       | UX305CA                     | [624e23640a](https://linux-hardware.org/?probe=624e23640a) | Mar 24, 2020 |
| Acer          | TravelMate 2490             | [00d179f01a](https://linux-hardware.org/?probe=00d179f01a) | Mar 23, 2020 |
| ASUSTek       | UX305CA                     | [029a5e5e9e](https://linux-hardware.org/?probe=029a5e5e9e) | Mar 23, 2020 |
| Acer          | TravelMate 5720             | [8c2056a761](https://linux-hardware.org/?probe=8c2056a761) | Mar 21, 2020 |
| Dell          | Inspiron 7347               | [77c2f26115](https://linux-hardware.org/?probe=77c2f26115) | Mar 20, 2020 |
| ASUSTek       | G73Jh                       | [8fab458245](https://linux-hardware.org/?probe=8fab458245) | Mar 18, 2020 |
| Lenovo        | ThinkPad X201 33238UG       | [ef40bcb4bd](https://linux-hardware.org/?probe=ef40bcb4bd) | Mar 18, 2020 |
| Acer          | Aspire ES1-711G             | [b34059b677](https://linux-hardware.org/?probe=b34059b677) | Mar 16, 2020 |
| ASUSTek       | K54C                        | [83b39008d5](https://linux-hardware.org/?probe=83b39008d5) | Mar 16, 2020 |
| HP            | EliteBook 840 G5            | [bbfa59e02d](https://linux-hardware.org/?probe=bbfa59e02d) | Mar 15, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | [6933f971d0](https://linux-hardware.org/?probe=6933f971d0) | Mar 14, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | [4f35448ece](https://linux-hardware.org/?probe=4f35448ece) | Mar 14, 2020 |
| HP            | Compaq 6715b (KE065EA#AK... | [6720a1a4dd](https://linux-hardware.org/?probe=6720a1a4dd) | Mar 14, 2020 |
| HP            | EliteBook 840 G5            | [857c21cba9](https://linux-hardware.org/?probe=857c21cba9) | Mar 13, 2020 |
| ASUSTek       | X51R                        | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| ASUSTek       | G73Jh                       | [05775bfd66](https://linux-hardware.org/?probe=05775bfd66) | Mar 09, 2020 |
| HP            | ProBook 6570b               | [c6d9be95fe](https://linux-hardware.org/?probe=c6d9be95fe) | Mar 09, 2020 |
| HP            | ProBook 470 G2              | [8ded132046](https://linux-hardware.org/?probe=8ded132046) | Mar 09, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [fc5a75980b](https://linux-hardware.org/?probe=fc5a75980b) | Mar 07, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [f1f0d87afd](https://linux-hardware.org/?probe=f1f0d87afd) | Mar 06, 2020 |
| HP            | ProBook 4540s               | [492404a7b5](https://linux-hardware.org/?probe=492404a7b5) | Mar 06, 2020 |
| ASUSTek       | X555LJ                      | [93e8da5f2a](https://linux-hardware.org/?probe=93e8da5f2a) | Mar 06, 2020 |
| ASUSTek       | X555LJ                      | [033da87d24](https://linux-hardware.org/?probe=033da87d24) | Mar 06, 2020 |
| Acer          | Extensa 5635ZG              | [bfda801594](https://linux-hardware.org/?probe=bfda801594) | Mar 04, 2020 |
| Acer          | Aspire A515-51G             | [f61491f270](https://linux-hardware.org/?probe=f61491f270) | Mar 03, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [92032f62ef](https://linux-hardware.org/?probe=92032f62ef) | Mar 01, 2020 |
| Acer          | Swift SF314-41              | [c2d4a2cffa](https://linux-hardware.org/?probe=c2d4a2cffa) | Mar 01, 2020 |
| ASUSTek       | G73Jh                       | [01afb8cba8](https://linux-hardware.org/?probe=01afb8cba8) | Mar 01, 2020 |
| Apple         | MacBookPro15,2              | [3e260beb60](https://linux-hardware.org/?probe=3e260beb60) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | [b2936932cf](https://linux-hardware.org/?probe=b2936932cf) | Feb 29, 2020 |
| Apple         | MacBookPro15,2              | [5c56805de1](https://linux-hardware.org/?probe=5c56805de1) | Feb 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMC    | [b511ab5202](https://linux-hardware.org/?probe=b511ab5202) | Feb 27, 2020 |
| Lenovo        | ThinkPad X270 20K5S0R100    | [50bddb4fd0](https://linux-hardware.org/?probe=50bddb4fd0) | Feb 26, 2020 |
| ASUSTek       | X555LD                      | [c3ba184dbb](https://linux-hardware.org/?probe=c3ba184dbb) | Feb 25, 2020 |
| Dell          | Latitude 5480               | [18b1fee704](https://linux-hardware.org/?probe=18b1fee704) | Feb 25, 2020 |
| Dell          | Precision 3530              | [a847df5d95](https://linux-hardware.org/?probe=a847df5d95) | Feb 20, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [5986ac405a](https://linux-hardware.org/?probe=5986ac405a) | Feb 20, 2020 |
| Toshiba       | Satellite P70-A             | [c575900b39](https://linux-hardware.org/?probe=c575900b39) | Feb 19, 2020 |
| Dell          | Precision 5540              | [4e027cdac7](https://linux-hardware.org/?probe=4e027cdac7) | Feb 15, 2020 |
| Dell          | Precision M6500             | [71a22eff06](https://linux-hardware.org/?probe=71a22eff06) | Feb 15, 2020 |
| HP            | ProBook 6555b               | [786df34e10](https://linux-hardware.org/?probe=786df34e10) | Feb 12, 2020 |
| HP            | ProBook 6555b               | [b09d4a9a07](https://linux-hardware.org/?probe=b09d4a9a07) | Feb 12, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| ASUSTek       | N75SF                       | [708afdd130](https://linux-hardware.org/?probe=708afdd130) | Feb 05, 2020 |
| HP            | ZBook 15 G2                 | [58fbde79b5](https://linux-hardware.org/?probe=58fbde79b5) | Feb 04, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | [38058cfd32](https://linux-hardware.org/?probe=38058cfd32) | Feb 02, 2020 |
| Acer          | Aspire SW5-271              | [193ff2efc6](https://linux-hardware.org/?probe=193ff2efc6) | Jan 31, 2020 |
| Sony          | VPCEB3L1E                   | [157ce63cf3](https://linux-hardware.org/?probe=157ce63cf3) | Jan 30, 2020 |
| ASUSTek       | N73SV                       | [38f088b8c0](https://linux-hardware.org/?probe=38f088b8c0) | Jan 29, 2020 |
| ASUSTek       | N73SV                       | [e8f4aa5f32](https://linux-hardware.org/?probe=e8f4aa5f32) | Jan 29, 2020 |
| Lenovo        | ThinkPad L480 20LS0017MC    | [55c9260451](https://linux-hardware.org/?probe=55c9260451) | Jan 29, 2020 |
| Sony          | VPCEA1S1E                   | [bcfcf8ae93](https://linux-hardware.org/?probe=bcfcf8ae93) | Jan 26, 2020 |
| Unknown       | V141                        | [d4b01fc8cb](https://linux-hardware.org/?probe=d4b01fc8cb) | Jan 26, 2020 |
| Alienware     | M17xR3                      | [4e9804e6ed](https://linux-hardware.org/?probe=4e9804e6ed) | Jan 24, 2020 |
| Lenovo        | ThinkPad T490 20N2S2UH00    | [832335bf08](https://linux-hardware.org/?probe=832335bf08) | Jan 24, 2020 |
| ASUSTek       | K50C                        | [a8f036e32b](https://linux-hardware.org/?probe=a8f036e32b) | Jan 23, 2020 |
| ASUSTek       | K50C                        | [bdb5f9ee19](https://linux-hardware.org/?probe=bdb5f9ee19) | Jan 22, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [73b2494a42](https://linux-hardware.org/?probe=73b2494a42) | Jan 22, 2020 |
| ASUSTek       | K50C                        | [db872fd6b0](https://linux-hardware.org/?probe=db872fd6b0) | Jan 21, 2020 |
| ASUSTek       | K50C                        | [b6c2e7b4f7](https://linux-hardware.org/?probe=b6c2e7b4f7) | Jan 21, 2020 |
| ASUSTek       | X555LJ                      | [731e144435](https://linux-hardware.org/?probe=731e144435) | Jan 20, 2020 |
| Dell          | Precision M6500             | [2bce7c4d41](https://linux-hardware.org/?probe=2bce7c4d41) | Jan 19, 2020 |
| ASUSTek       | N73SV                       | [1c2caa4c83](https://linux-hardware.org/?probe=1c2caa4c83) | Jan 18, 2020 |
| Dell          | G3 3779                     | [1a75467376](https://linux-hardware.org/?probe=1a75467376) | Jan 18, 2020 |
| Lenovo        | V330-15IKB 81AX             | [701f52dd25](https://linux-hardware.org/?probe=701f52dd25) | Jan 17, 2020 |
| HP            | EliteBook 735 G6            | [57d80b3164](https://linux-hardware.org/?probe=57d80b3164) | Jan 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [92086a7925](https://linux-hardware.org/?probe=92086a7925) | Jan 14, 2020 |
| Dell          | XPS 15 9560                 | [dbace2bb0a](https://linux-hardware.org/?probe=dbace2bb0a) | Jan 13, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [c24f015f0f](https://linux-hardware.org/?probe=c24f015f0f) | Jan 13, 2020 |
| Sony          | VGN-FW31E                   | [754869cea8](https://linux-hardware.org/?probe=754869cea8) | Jan 13, 2020 |
| Sony          | VGN-FW31E                   | [b9a26f01e9](https://linux-hardware.org/?probe=b9a26f01e9) | Jan 13, 2020 |
| ASUSTek       | X540SC                      | [67a473453a](https://linux-hardware.org/?probe=67a473453a) | Jan 12, 2020 |
| ASUSTek       | X540SC                      | [083adaccfd](https://linux-hardware.org/?probe=083adaccfd) | Jan 12, 2020 |
| ASUSTek       | X540SC                      | [35892a76e9](https://linux-hardware.org/?probe=35892a76e9) | Jan 12, 2020 |
| ASUSTek       | K50C                        | [11811afc67](https://linux-hardware.org/?probe=11811afc67) | Jan 10, 2020 |
| HP            | ZBook 15 G5                 | [09c73320da](https://linux-hardware.org/?probe=09c73320da) | Jan 08, 2020 |
| HP            | ProBook 4530s               | [371bf68041](https://linux-hardware.org/?probe=371bf68041) | Jan 07, 2020 |
| Acer          | TravelMate 6460             | [239f09af80](https://linux-hardware.org/?probe=239f09af80) | Jan 05, 2020 |
| ASUSTek       | K50C                        | [61431441f3](https://linux-hardware.org/?probe=61431441f3) | Jan 05, 2020 |
| Dell          | Precision M6500             | [9cf869c61a](https://linux-hardware.org/?probe=9cf869c61a) | Jan 05, 2020 |
| ASUSTek       | K50C                        | [607a22d4a2](https://linux-hardware.org/?probe=607a22d4a2) | Jan 03, 2020 |
| ASUSTek       | K50C                        | [cd9b2523a4](https://linux-hardware.org/?probe=cd9b2523a4) | Jan 03, 2020 |
| Dell          | Precision M6500             | [c481909dee](https://linux-hardware.org/?probe=c481909dee) | Dec 31, 2019 |
| HP            | ProBook 6560b               | [354538a3e7](https://linux-hardware.org/?probe=354538a3e7) | Dec 29, 2019 |
| Acer          | Aspire A515-51G             | [88f8ae0302](https://linux-hardware.org/?probe=88f8ae0302) | Dec 27, 2019 |
| Lenovo        | ThinkPad T420 42364F2       | [b470e45c2c](https://linux-hardware.org/?probe=b470e45c2c) | Dec 26, 2019 |
| Acer          | Aspire E3-111               | [f61e2d2b7b](https://linux-hardware.org/?probe=f61e2d2b7b) | Dec 26, 2019 |
| Packard Be... | EasyNote TS44HR             | [832f6ef100](https://linux-hardware.org/?probe=832f6ef100) | Dec 25, 2019 |
| Lenovo        | ThinkPad T430 2349KQ3       | [b162d0fd81](https://linux-hardware.org/?probe=b162d0fd81) | Dec 22, 2019 |
| HP            | EliteBook Revolve 810 G2    | [2dc8b3f35d](https://linux-hardware.org/?probe=2dc8b3f35d) | Dec 22, 2019 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [98794aceb7](https://linux-hardware.org/?probe=98794aceb7) | Dec 21, 2019 |
| HP            | EliteBook Revolve 810 G2    | [5b00879915](https://linux-hardware.org/?probe=5b00879915) | Dec 21, 2019 |
| HP            | EliteBook Revolve 810 G2    | [8194a016bc](https://linux-hardware.org/?probe=8194a016bc) | Dec 21, 2019 |
| ASUSTek       | X555LJ                      | [df4413af58](https://linux-hardware.org/?probe=df4413af58) | Dec 17, 2019 |
| Dell          | Inspiron 7520               | [e5cda35a9a](https://linux-hardware.org/?probe=e5cda35a9a) | Dec 16, 2019 |
| HP            | Compaq nw8440 (RY852EP#A... | [b38a821821](https://linux-hardware.org/?probe=b38a821821) | Dec 14, 2019 |
| HP            | Compaq 6510b (KV177EC#AB... | [a4d3f8a8ac](https://linux-hardware.org/?probe=a4d3f8a8ac) | Dec 13, 2019 |
| Samsung       | N145P/N250P/N260P           | [08fd697014](https://linux-hardware.org/?probe=08fd697014) | Dec 12, 2019 |
| Samsung       | N145P/N250P/N260P           | [6337a251d7](https://linux-hardware.org/?probe=6337a251d7) | Dec 12, 2019 |
| Lenovo        | Z50-70 20354                | [5377350816](https://linux-hardware.org/?probe=5377350816) | Dec 11, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [f473523657](https://linux-hardware.org/?probe=f473523657) | Dec 04, 2019 |
| ASUSTek       | 1000H                       | [22b31ccf0f](https://linux-hardware.org/?probe=22b31ccf0f) | Nov 29, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | [f80e2e7a87](https://linux-hardware.org/?probe=f80e2e7a87) | Nov 29, 2019 |
| Lenovo        | ThinkPad L480 20LS0017MC    | [711c3d5ea2](https://linux-hardware.org/?probe=711c3d5ea2) | Nov 27, 2019 |
| HP            | ProBook 4530s               | [7988187508](https://linux-hardware.org/?probe=7988187508) | Nov 25, 2019 |
| HP            | ProBook 4530s               | [130b1900ea](https://linux-hardware.org/?probe=130b1900ea) | Nov 25, 2019 |
| Lenovo        | ThinkPad T430 2349KQ3       | [a620a7cc4f](https://linux-hardware.org/?probe=a620a7cc4f) | Nov 22, 2019 |
| Lenovo        | ThinkPad L480 20LS0017MC    | [e512a5e1ee](https://linux-hardware.org/?probe=e512a5e1ee) | Nov 18, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | [e7b1fa1aa9](https://linux-hardware.org/?probe=e7b1fa1aa9) | Nov 14, 2019 |
| HP            | Notebook                    | [51d2b963e3](https://linux-hardware.org/?probe=51d2b963e3) | Nov 13, 2019 |
| Acer          | Aspire 5110                 | [2d2cbc0a8d](https://linux-hardware.org/?probe=2d2cbc0a8d) | Nov 12, 2019 |
| Acer          | Aspire 5110                 | [ff6142d68c](https://linux-hardware.org/?probe=ff6142d68c) | Nov 12, 2019 |
| HP            | EliteBook 745 G2            | [1c82c3c564](https://linux-hardware.org/?probe=1c82c3c564) | Nov 11, 2019 |
| HP            | EliteBook 8470p             | [905fa1bd8b](https://linux-hardware.org/?probe=905fa1bd8b) | Nov 04, 2019 |
| Acer          | Aspire E1-531               | [41c23f1259](https://linux-hardware.org/?probe=41c23f1259) | Nov 04, 2019 |
| HP            | EliteBook 840 G6            | [f6a8a19103](https://linux-hardware.org/?probe=f6a8a19103) | Nov 04, 2019 |
| Sony          | VPCEH2J1E                   | [09359ba2ca](https://linux-hardware.org/?probe=09359ba2ca) | Nov 01, 2019 |
| Sony          | VPCEH2J1E                   | [e0b7710731](https://linux-hardware.org/?probe=e0b7710731) | Oct 30, 2019 |
| HP            | Pavilion dv6                | [4ba52172ad](https://linux-hardware.org/?probe=4ba52172ad) | Oct 28, 2019 |
| HP            | Pavilion g6                 | [12b4f13a70](https://linux-hardware.org/?probe=12b4f13a70) | Oct 27, 2019 |
| HP            | Laptop 15-bw0xx             | [f1aa402558](https://linux-hardware.org/?probe=f1aa402558) | Oct 26, 2019 |
| Lenovo        | ThinkPad T440p 20ANA01P0... | [be20a32d4d](https://linux-hardware.org/?probe=be20a32d4d) | Oct 24, 2019 |
| Dell          | Vostro 3450                 | [55012132f6](https://linux-hardware.org/?probe=55012132f6) | Oct 21, 2019 |
| Dell          | Precision 5510              | [f9346dd032](https://linux-hardware.org/?probe=f9346dd032) | Oct 20, 2019 |
| ASUSTek       | X540SA                      | [fb8f7369fa](https://linux-hardware.org/?probe=fb8f7369fa) | Oct 20, 2019 |
| ASUSTek       | X540SA                      | [9e723b017a](https://linux-hardware.org/?probe=9e723b017a) | Oct 20, 2019 |
| ASUSTek       | X540SA                      | [2830c369c8](https://linux-hardware.org/?probe=2830c369c8) | Oct 20, 2019 |
| Acer          | Extensa 5620                | [c4feff7f79](https://linux-hardware.org/?probe=c4feff7f79) | Oct 17, 2019 |
| Acer          | Extensa 5235                | [525bd2b38a](https://linux-hardware.org/?probe=525bd2b38a) | Oct 17, 2019 |
| Acer          | Aspire E5-575G              | [cdf28aa8cc](https://linux-hardware.org/?probe=cdf28aa8cc) | Oct 16, 2019 |
| HP            | EliteBook 6930p             | [24f7e5bb5b](https://linux-hardware.org/?probe=24f7e5bb5b) | Oct 16, 2019 |
| Acer          | Extensa 5235                | [0da32ec2d0](https://linux-hardware.org/?probe=0da32ec2d0) | Oct 16, 2019 |
| ASUSTek       | UX310UAK                    | [05d33156f9](https://linux-hardware.org/?probe=05d33156f9) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | [4a302fca76](https://linux-hardware.org/?probe=4a302fca76) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | [3a7cedc107](https://linux-hardware.org/?probe=3a7cedc107) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | [6e1e8080d0](https://linux-hardware.org/?probe=6e1e8080d0) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | [678c55d478](https://linux-hardware.org/?probe=678c55d478) | Oct 14, 2019 |
| ASUSTek       | UX310UAK                    | [16b9adda22](https://linux-hardware.org/?probe=16b9adda22) | Oct 14, 2019 |
| Sony          | VPCEH2J1E                   | [45f4c3c1fe](https://linux-hardware.org/?probe=45f4c3c1fe) | Oct 13, 2019 |
| Acer          | Extensa 5620                | [e731e5a628](https://linux-hardware.org/?probe=e731e5a628) | Oct 10, 2019 |
| Dell          | Latitude 7480               | [df1f8299a4](https://linux-hardware.org/?probe=df1f8299a4) | Oct 09, 2019 |
| Dell          | Latitude 7480               | [77c51cdba1](https://linux-hardware.org/?probe=77c51cdba1) | Oct 09, 2019 |
| Dell          | Latitude 7480               | [211534820a](https://linux-hardware.org/?probe=211534820a) | Oct 09, 2019 |
| Acer          | Extensa 5220                | [5fe44df1d6](https://linux-hardware.org/?probe=5fe44df1d6) | Oct 08, 2019 |
| Sony          | VPCEB1E1E                   | [aa7b7564e5](https://linux-hardware.org/?probe=aa7b7564e5) | Oct 07, 2019 |
| Dell          | Precision 5530              | [56b4b63a9d](https://linux-hardware.org/?probe=56b4b63a9d) | Oct 03, 2019 |
| HP            | 655                         | [31291ad75e](https://linux-hardware.org/?probe=31291ad75e) | Sep 29, 2019 |
| HP            | 655                         | [9d49ceb29a](https://linux-hardware.org/?probe=9d49ceb29a) | Sep 29, 2019 |
| HP            | Pavilion g6                 | [5bbd20265c](https://linux-hardware.org/?probe=5bbd20265c) | Sep 29, 2019 |
| Dell          | Vostro 5581                 | [27fdc7a402](https://linux-hardware.org/?probe=27fdc7a402) | Sep 27, 2019 |
| ASUSTek       | X555LJ                      | [9cf22baa29](https://linux-hardware.org/?probe=9cf22baa29) | Sep 19, 2019 |
| HP            | Pavilion g6                 | [2a12e1f7bf](https://linux-hardware.org/?probe=2a12e1f7bf) | Sep 18, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | [b03fca451e](https://linux-hardware.org/?probe=b03fca451e) | Sep 18, 2019 |
| ASUSTek       | K50IJ                       | [43f9f6d938](https://linux-hardware.org/?probe=43f9f6d938) | Sep 16, 2019 |
| ASUSTek       | K50IJ                       | [a32aea019e](https://linux-hardware.org/?probe=a32aea019e) | Sep 16, 2019 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [23bf069faa](https://linux-hardware.org/?probe=23bf069faa) | Sep 15, 2019 |
| ASUSTek       | A8E                         | [ac8e6224b3](https://linux-hardware.org/?probe=ac8e6224b3) | Sep 14, 2019 |
| Dell          | Latitude E5470              | [dfb91a065c](https://linux-hardware.org/?probe=dfb91a065c) | Sep 13, 2019 |
| Lenovo        | ThinkPad T460 20FMS0QJ0P    | [c37e8c9e3e](https://linux-hardware.org/?probe=c37e8c9e3e) | Sep 12, 2019 |
| ASUSTek       | A8E                         | [3bfd78cdf3](https://linux-hardware.org/?probe=3bfd78cdf3) | Sep 12, 2019 |
| HP            | 250 G2                      | [0ee1d25c7e](https://linux-hardware.org/?probe=0ee1d25c7e) | Sep 07, 2019 |
| HP            | 250 G2                      | [169eb648ba](https://linux-hardware.org/?probe=169eb648ba) | Sep 07, 2019 |
| Lenovo        | Yoga 500-15IBD 80N6         | [7c54a20d12](https://linux-hardware.org/?probe=7c54a20d12) | Aug 29, 2019 |
| Lenovo        | Yoga 500-15IBD 80N6         | [5750f01b6a](https://linux-hardware.org/?probe=5750f01b6a) | Aug 29, 2019 |
| Lenovo        | Yoga 500-15IBD 80N6         | [7b7f45b3fd](https://linux-hardware.org/?probe=7b7f45b3fd) | Aug 29, 2019 |
| Dell          | Inspiron 7537               | [19d02b1151](https://linux-hardware.org/?probe=19d02b1151) | Aug 24, 2019 |
| HP            | G72                         | [dac5510694](https://linux-hardware.org/?probe=dac5510694) | Aug 23, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [a777349d95](https://linux-hardware.org/?probe=a777349d95) | Aug 21, 2019 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [3f3395ff9f](https://linux-hardware.org/?probe=3f3395ff9f) | Aug 21, 2019 |
| HP            | EliteBook 8730w             | [2b533b1416](https://linux-hardware.org/?probe=2b533b1416) | Aug 17, 2019 |
| Dell          | Latitude 7390               | [d360b45394](https://linux-hardware.org/?probe=d360b45394) | Aug 15, 2019 |
| Dell          | Latitude 7390               | [d1454b26c6](https://linux-hardware.org/?probe=d1454b26c6) | Aug 15, 2019 |
| Acer          | Extensa 5220                | [dfec154035](https://linux-hardware.org/?probe=dfec154035) | Aug 14, 2019 |
| Acer          | Extensa 5220                | [d34fb63ce3](https://linux-hardware.org/?probe=d34fb63ce3) | Aug 14, 2019 |
| Sony          | SVE14135CXP                 | [1b1819d6c0](https://linux-hardware.org/?probe=1b1819d6c0) | Aug 13, 2019 |
| Dell          | Latitude 7390               | [05cdc89a9d](https://linux-hardware.org/?probe=05cdc89a9d) | Aug 12, 2019 |
| Acer          | Extensa 5220                | [b33c5c819b](https://linux-hardware.org/?probe=b33c5c819b) | Aug 10, 2019 |
| ASUSTek       | X540SA                      | [4db48dfe19](https://linux-hardware.org/?probe=4db48dfe19) | Aug 08, 2019 |
| HP            | ZBook 17                    | [9d1c8ffb20](https://linux-hardware.org/?probe=9d1c8ffb20) | Jul 30, 2019 |
| EUROCOM       | Sky X4C                     | [4ced599618](https://linux-hardware.org/?probe=4ced599618) | Jul 26, 2019 |
| Insyde        | AS Series                   | [0994a3eeb3](https://linux-hardware.org/?probe=0994a3eeb3) | Jul 24, 2019 |
| HP            | Pavilion Laptop 15-cw1xx... | [048229855f](https://linux-hardware.org/?probe=048229855f) | Jul 23, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | [029641c14a](https://linux-hardware.org/?probe=029641c14a) | Jul 19, 2019 |
| Lenovo        | ThinkPad T420 4236BD5       | [eba01de2ba](https://linux-hardware.org/?probe=eba01de2ba) | Jul 19, 2019 |
| ASUSTek       | X555LJ                      | [ec150f49de](https://linux-hardware.org/?probe=ec150f49de) | Jul 14, 2019 |
| Acer          | TravelMate 7730G            | [c57ddb8581](https://linux-hardware.org/?probe=c57ddb8581) | Jul 14, 2019 |
| Acer          | TravelMate 7730G            | [b38c638fe2](https://linux-hardware.org/?probe=b38c638fe2) | Jul 14, 2019 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [83f2ff723d](https://linux-hardware.org/?probe=83f2ff723d) | Jul 13, 2019 |
| HP            | ProBook 4525s               | [23e7475693](https://linux-hardware.org/?probe=23e7475693) | Jul 10, 2019 |
| ASUSTek       | X101CH                      | [6fb4432f5a](https://linux-hardware.org/?probe=6fb4432f5a) | Jul 09, 2019 |
| Acer          | Extensa 5220                | [7387d70ad5](https://linux-hardware.org/?probe=7387d70ad5) | Jul 06, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | [23dac0f1b6](https://linux-hardware.org/?probe=23dac0f1b6) | Jul 05, 2019 |
| Fujitsu Si... | AMILO La1703                | [feda3b155d](https://linux-hardware.org/?probe=feda3b155d) | Jul 04, 2019 |
| Acer          | Aspire E1-522               | [5f96135c9a](https://linux-hardware.org/?probe=5f96135c9a) | Jun 30, 2019 |
| Acer          | Extensa 5220                | [9e0e784c24](https://linux-hardware.org/?probe=9e0e784c24) | Jun 30, 2019 |
| HP            | ProBook 430 G1              | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Acer          | Aspire A515-51G             | [6582422be8](https://linux-hardware.org/?probe=6582422be8) | Jun 21, 2019 |
| Lenovo        | ThinkPad T460s 20FAS2BM0... | [78932b3c9b](https://linux-hardware.org/?probe=78932b3c9b) | Jun 20, 2019 |
| UMAX          | VisionBook 13Wa Pro         | [237f54eb53](https://linux-hardware.org/?probe=237f54eb53) | Jun 17, 2019 |
| ASUSTek       | X453SA                      | [7a4394875f](https://linux-hardware.org/?probe=7a4394875f) | Jun 17, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c6c915f346](https://linux-hardware.org/?probe=c6c915f346) | Jun 14, 2019 |
| UMAX          | VisionBook 13Wa Pro         | [c6291842b6](https://linux-hardware.org/?probe=c6291842b6) | Jun 13, 2019 |
| UMAX          | VisionBook 13Wa Pro         | [299bc30247](https://linux-hardware.org/?probe=299bc30247) | Jun 13, 2019 |
| EUROCOM       | Sky X4C                     | [bd8361fe34](https://linux-hardware.org/?probe=bd8361fe34) | Jun 11, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | [73cfbc167f](https://linux-hardware.org/?probe=73cfbc167f) | Jun 09, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | [16090462f6](https://linux-hardware.org/?probe=16090462f6) | Jun 08, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | [81e1afe5a9](https://linux-hardware.org/?probe=81e1afe5a9) | Jun 08, 2019 |
| Lenovo        | ThinkPad X220 4291TGP       | [c90ba0b154](https://linux-hardware.org/?probe=c90ba0b154) | Jun 08, 2019 |
| HP            | 15                          | [b4e1df2016](https://linux-hardware.org/?probe=b4e1df2016) | Jun 05, 2019 |
| ASUSTek       | X453SA                      | [48a7d9e35b](https://linux-hardware.org/?probe=48a7d9e35b) | May 27, 2019 |
| Acer          | Aspire A515-51              | [586cd3ab4a](https://linux-hardware.org/?probe=586cd3ab4a) | May 25, 2019 |
| Dell          | XPS 13 9370                 | [54ed095d80](https://linux-hardware.org/?probe=54ed095d80) | May 24, 2019 |
| Acer          | Aspire A515-51G             | [994ff4beb4](https://linux-hardware.org/?probe=994ff4beb4) | May 21, 2019 |
| Acer          | Extensa 5620                | [2a3f563e9d](https://linux-hardware.org/?probe=2a3f563e9d) | May 21, 2019 |
| HP            | ZBook 17                    | [561770352f](https://linux-hardware.org/?probe=561770352f) | May 17, 2019 |
| UMAX          | 13Wa_Flex                   | [1b3276fb60](https://linux-hardware.org/?probe=1b3276fb60) | May 14, 2019 |
| Acer          | Extensa 5620                | [f80a434ab1](https://linux-hardware.org/?probe=f80a434ab1) | May 13, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [d6f5348ec7](https://linux-hardware.org/?probe=d6f5348ec7) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [dd79c77450](https://linux-hardware.org/?probe=dd79c77450) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [8169b27ee7](https://linux-hardware.org/?probe=8169b27ee7) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [fa9f954587](https://linux-hardware.org/?probe=fa9f954587) | May 09, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [b9c026d844](https://linux-hardware.org/?probe=b9c026d844) | May 09, 2019 |
| Dell          | Latitude 7290               | [3e31be830b](https://linux-hardware.org/?probe=3e31be830b) | May 06, 2019 |
| HP            | EliteBook 6930p             | [c949572837](https://linux-hardware.org/?probe=c949572837) | May 05, 2019 |
| HP            | EliteBook 6930p             | [1e0b8a0909](https://linux-hardware.org/?probe=1e0b8a0909) | May 05, 2019 |
| Acer          | Aspire A715-72G             | [291836cdce](https://linux-hardware.org/?probe=291836cdce) | Apr 30, 2019 |
| ASUSTek       | X555LJ                      | [d4041548f7](https://linux-hardware.org/?probe=d4041548f7) | Apr 27, 2019 |
| ASUSTek       | X555LJ                      | [70db2d5844](https://linux-hardware.org/?probe=70db2d5844) | Apr 22, 2019 |
| ASUSTek       | X555LJ                      | [0509a7b376](https://linux-hardware.org/?probe=0509a7b376) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK A530               | [5c06550c98](https://linux-hardware.org/?probe=5c06550c98) | Apr 16, 2019 |
| UMAX          | VisionBook 13Wa             | [f53622af88](https://linux-hardware.org/?probe=f53622af88) | Apr 14, 2019 |
| Acer          | Aspire 3750G                | [6f36d97878](https://linux-hardware.org/?probe=6f36d97878) | Apr 12, 2019 |
| ASUSTek       | E502SA                      | [bd2b6260c9](https://linux-hardware.org/?probe=bd2b6260c9) | Apr 12, 2019 |
| ASUSTek       | E502SA                      | [d4cd483c7e](https://linux-hardware.org/?probe=d4cd483c7e) | Apr 12, 2019 |
| Sony          | VPCEB1E1E                   | [9976a35e60](https://linux-hardware.org/?probe=9976a35e60) | Apr 12, 2019 |
| Sony          | VPCEB1E1E                   | [954cb6c789](https://linux-hardware.org/?probe=954cb6c789) | Apr 10, 2019 |
| Sony          | VPCEB1E1E                   | [eeb658c6eb](https://linux-hardware.org/?probe=eeb658c6eb) | Apr 10, 2019 |
| UMAX          | VisionBook 13Wa             | [568d0511c5](https://linux-hardware.org/?probe=568d0511c5) | Apr 06, 2019 |
| HP            | EliteBook 6930p             | [bb454edeb2](https://linux-hardware.org/?probe=bb454edeb2) | Apr 06, 2019 |
| Dell          | Precision M6500             | [089056d291](https://linux-hardware.org/?probe=089056d291) | Apr 06, 2019 |
| ASUSTek       | K55VJ                       | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| ASUSTek       | K53BY                       | [7eae69fedb](https://linux-hardware.org/?probe=7eae69fedb) | Mar 31, 2019 |
| Lenovo        | Y50-70 20378                | [bc4e358c02](https://linux-hardware.org/?probe=bc4e358c02) | Mar 28, 2019 |
| Sony          | VPCEA1S1E                   | [30221f58ec](https://linux-hardware.org/?probe=30221f58ec) | Mar 26, 2019 |
| Dell          | XPS 15 9575                 | [f5fdc69851](https://linux-hardware.org/?probe=f5fdc69851) | Mar 09, 2019 |
| Dell          | Latitude E5530 non-vPro     | [b139926981](https://linux-hardware.org/?probe=b139926981) | Feb 16, 2019 |
| Dell          | Latitude E5530 non-vPro     | [80b80427e7](https://linux-hardware.org/?probe=80b80427e7) | Feb 16, 2019 |
| HP            | EliteBook 8530p             | [5358bdeae7](https://linux-hardware.org/?probe=5358bdeae7) | Feb 05, 2019 |
| ASUSTek       | K70IC                       | [17e1c5ea47](https://linux-hardware.org/?probe=17e1c5ea47) | Feb 03, 2019 |
| ASUSTek       | K70IC                       | [b7c7acfec7](https://linux-hardware.org/?probe=b7c7acfec7) | Jan 23, 2019 |
| ASUSTek       | K70IC                       | [0a857f39b3](https://linux-hardware.org/?probe=0a857f39b3) | Jan 23, 2019 |
| Lenovo        | ThinkPad T440p 20ANA01P0... | [075bb02ebf](https://linux-hardware.org/?probe=075bb02ebf) | Jan 17, 2019 |
| Acer          | Aspire A515-51G             | [cecb4beb0b](https://linux-hardware.org/?probe=cecb4beb0b) | Jan 11, 2019 |
| Acer          | Aspire E1-530               | [c8bbd66689](https://linux-hardware.org/?probe=c8bbd66689) | Jan 10, 2019 |
| Acer          | Aspire A515-51G             | [e15bdbf5d9](https://linux-hardware.org/?probe=e15bdbf5d9) | Jan 10, 2019 |
| Sony          | VPCEB1E1E                   | [d9a4cec8c3](https://linux-hardware.org/?probe=d9a4cec8c3) | Jan 06, 2019 |
| Lenovo        | ThinkPad T460s 20FAS2BM0... | [5a912fd2ea](https://linux-hardware.org/?probe=5a912fd2ea) | Jan 03, 2019 |
| HP            | ProBook 4320s               | [44c1e7bb5c](https://linux-hardware.org/?probe=44c1e7bb5c) | Jan 03, 2019 |
| HP            | Pavilion x2 Detachable      | [40e42cb215](https://linux-hardware.org/?probe=40e42cb215) | Dec 30, 2018 |
| Acer          | Aspire A315-21G             | [fc3c439818](https://linux-hardware.org/?probe=fc3c439818) | Dec 30, 2018 |
| Sony          | VPCEB1E1E                   | [7d1522f747](https://linux-hardware.org/?probe=7d1522f747) | Dec 26, 2018 |
| Sony          | VPCEB1E1E                   | [d94bebc566](https://linux-hardware.org/?probe=d94bebc566) | Dec 26, 2018 |
| Sony          | VPCEB1E1E                   | [64be9e8809](https://linux-hardware.org/?probe=64be9e8809) | Dec 25, 2018 |
| HP            | Pavilion dv6                | [ed828ba9f4](https://linux-hardware.org/?probe=ed828ba9f4) | Dec 22, 2018 |
| HP            | Pavilion dv6                | [87716b9693](https://linux-hardware.org/?probe=87716b9693) | Dec 22, 2018 |
| HP            | Pavilion dv6                | [8f15df54b3](https://linux-hardware.org/?probe=8f15df54b3) | Dec 22, 2018 |
| ASUSTek       | X553SA                      | [f308c7c04a](https://linux-hardware.org/?probe=f308c7c04a) | Dec 10, 2018 |
| ASUSTek       | X553SA                      | [f4ae14c49b](https://linux-hardware.org/?probe=f4ae14c49b) | Dec 10, 2018 |
| Acer          | Aspire 6920                 | [c7f73c8073](https://linux-hardware.org/?probe=c7f73c8073) | Dec 06, 2018 |
| Acer          | Aspire 6920                 | [48bfc07b67](https://linux-hardware.org/?probe=48bfc07b67) | Dec 06, 2018 |
| Acer          | Aspire 6920                 | [5703320f98](https://linux-hardware.org/?probe=5703320f98) | Dec 06, 2018 |
| Lenovo        | ThinkPad T460s 20FAS2BN0... | [ac90cab72c](https://linux-hardware.org/?probe=ac90cab72c) | Dec 04, 2018 |
| HP            | Pavilion dv7                | [d0378a64aa](https://linux-hardware.org/?probe=d0378a64aa) | Nov 24, 2018 |
| HP            | ProBook 450 G5              | [70d66c5819](https://linux-hardware.org/?probe=70d66c5819) | Nov 22, 2018 |
| HP            | G62                         | [3dcd149ca9](https://linux-hardware.org/?probe=3dcd149ca9) | Nov 22, 2018 |
| Dell          | Latitude E6400              | [2ee9ca1698](https://linux-hardware.org/?probe=2ee9ca1698) | Nov 17, 2018 |
| ASUSTek       | K55VJ                       | [292714e2c9](https://linux-hardware.org/?probe=292714e2c9) | Nov 10, 2018 |
| ASUSTek       | K55VJ                       | [ee7e6a7365](https://linux-hardware.org/?probe=ee7e6a7365) | Nov 10, 2018 |
| Prestigio     | Multipad Visconte V         | [47813421d8](https://linux-hardware.org/?probe=47813421d8) | Oct 31, 2018 |
| Lenovo        | ThinkPad T540p 20BFS1Y50... | [dda01f57c1](https://linux-hardware.org/?probe=dda01f57c1) | Oct 30, 2018 |
| Lenovo        | ThinkPad W541 20EGS0R60R    | [3583ec2729](https://linux-hardware.org/?probe=3583ec2729) | Jul 18, 2018 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e1d0272f03](https://linux-hardware.org/?probe=e1d0272f03) | Jul 04, 2018 |
| Acer          | Aspire E5-575G              | [c90fdb8aae](https://linux-hardware.org/?probe=c90fdb8aae) | Jun 09, 2018 |
| Acer          | Aspire E5-575G              | [9c2b2a9807](https://linux-hardware.org/?probe=9c2b2a9807) | Jun 08, 2018 |
| Acer          | Aspire E5-575G              | [91699cbaf8](https://linux-hardware.org/?probe=91699cbaf8) | Apr 18, 2018 |
| Lenovo        | ThinkPad X220 4291EJ3       | [6ff9f41b4f](https://linux-hardware.org/?probe=6ff9f41b4f) | Mar 04, 2018 |
| Acer          | TravelMate P277-MG          | [4b3b9a06f5](https://linux-hardware.org/?probe=4b3b9a06f5) | Jan 23, 2018 |
| Lenovo        | ThinkPad X230 2330A33       | [2c83a63531](https://linux-hardware.org/?probe=2c83a63531) | Dec 30, 2017 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d7e0b7ca2e](https://linux-hardware.org/?probe=d7e0b7ca2e) | Dec 14, 2017 |
| Acer          | Aspire 3690                 | [833fd8cc02](https://linux-hardware.org/?probe=833fd8cc02) | Jul 27, 2017 |
| Acer          | TravelMate P253             | [1de286539e](https://linux-hardware.org/?probe=1de286539e) | May 21, 2017 |
| Acer          | TravelMate P277-MG          | [303cee3407](https://linux-hardware.org/?probe=303cee3407) | Feb 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 152       | 16.7%   |
| Ubuntu 18.04       | 81        | 8.9%    |
| OpenMandriva 4.2   | 74        | 8.13%   |
| OpenMandriva 4.50  | 40        | 4.4%    |
| Ubuntu 21.10       | 28        | 3.08%   |
| Ubuntu 19.10       | 22        | 2.42%   |
| Ubuntu 20.10       | 21        | 2.31%   |
| Fedora 34          | 21        | 2.31%   |
| Ubuntu 21.04       | 18        | 1.98%   |
| Linux Mint 20      | 16        | 1.76%   |
| Zorin 15           | 15        | 1.65%   |
| Linux Mint 19.3    | 15        | 1.65%   |
| Linux Mint 20.2    | 14        | 1.54%   |
| Linux Mint 20.1    | 13        | 1.43%   |
| Fedora 35          | 13        | 1.43%   |
| Fedora 33          | 13        | 1.43%   |
| Fedora 32          | 13        | 1.43%   |
| Fedora 31          | 13        | 1.43%   |
| Debian 11          | 13        | 1.43%   |
| Arch               | 13        | 1.43%   |
| Ubuntu 19.04       | 12        | 1.32%   |
| Xubuntu 20.04      | 10        | 1.1%    |
| OpenMandriva 4.3   | 10        | 1.1%    |
| Zorin 16           | 9         | 0.99%   |
| Kubuntu 20.04      | 9         | 0.99%   |
| Xubuntu 18.04      | 8         | 0.88%   |
| Ubuntu 16.04       | 8         | 0.88%   |
| Pop!_OS 20.04      | 8         | 0.88%   |
| Debian 10          | 8         | 0.88%   |
| Manjaro            | 7         | 0.77%   |
| Linux Mint 20.3    | 7         | 0.77%   |
| KDE neon 20.04     | 7         | 0.77%   |
| Arch Rolling       | 7         | 0.77%   |
| Ubuntu 18.10       | 6         | 0.66%   |
| Gentoo 2.7         | 6         | 0.66%   |
| Linux Mint 19.2    | 5         | 0.55%   |
| Lubuntu 18.04      | 4         | 0.44%   |
| Linux Mint 19.1    | 4         | 0.44%   |
| ArcoLinux Rolling  | 4         | 0.44%   |
| Xubuntu 21.04      | 3         | 0.33%   |
| ROSA R10           | 3         | 0.33%   |
| RHEL 8             | 3         | 0.33%   |
| Pop!_OS 21.10      | 3         | 0.33%   |
| Pop!_OS 21.04      | 3         | 0.33%   |
| Manjaro 21.2.4     | 3         | 0.33%   |
| Kubuntu 21.04      | 3         | 0.33%   |
| Gentoo 2.6         | 3         | 0.33%   |
| Fedora 29          | 3         | 0.33%   |
| Elementary 6.1     | 3         | 0.33%   |
| Elementary 6       | 3         | 0.33%   |
| Debian Testing     | 3         | 0.33%   |
| BlackPanther 18.1  | 3         | 0.33%   |
| Xubuntu 21.10      | 2         | 0.22%   |
| Xubuntu 19.10      | 2         | 0.22%   |
| ROSA R9            | 2         | 0.22%   |
| ROSA R8.1          | 2         | 0.22%   |
| ROSA R11.1         | 2         | 0.22%   |
| ROSA 12.2          | 2         | 0.22%   |
| Pop!_OS 20.10      | 2         | 0.22%   |
| openSUSE Leap-15.3 | 2         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 323       | 37.65%  |
| OpenMandriva     | 125       | 14.57%  |
| Fedora           | 78        | 9.09%   |
| Linux Mint       | 70        | 8.16%   |
| Xubuntu          | 27        | 3.15%   |
| Debian           | 26        | 3.03%   |
| Zorin            | 25        | 2.91%   |
| Manjaro          | 23        | 2.68%   |
| Arch             | 20        | 2.33%   |
| Kubuntu          | 17        | 1.98%   |
| Pop!_OS          | 14        | 1.63%   |
| ROSA             | 12        | 1.4%    |
| openSUSE         | 11        | 1.28%   |
| KDE neon         | 9         | 1.05%   |
| Gentoo           | 9         | 1.05%   |
| Lubuntu          | 8         | 0.93%   |
| Elementary       | 8         | 0.93%   |
| Kali             | 7         | 0.82%   |
| Endless          | 7         | 0.82%   |
| Ubuntu MATE      | 5         | 0.58%   |
| ArcoLinux        | 5         | 0.58%   |
| RHEL             | 3         | 0.35%   |
| MX               | 3         | 0.35%   |
| BlackPanther     | 3         | 0.35%   |
| LinuxFX          | 2         | 0.23%   |
| EndeavourOS      | 2         | 0.23%   |
| Void Linux       | 1         | 0.12%   |
| SystemRescue     | 1         | 0.12%   |
| Sabayon          | 1         | 0.12%   |
| Rocky Linux      | 1         | 0.12%   |
| Reborn OS        | 1         | 0.12%   |
| Peppermint       | 1         | 0.12%   |
| Parrot           | 1         | 0.12%   |
| org.kde.Platform | 1         | 0.12%   |
| LFS              | 1         | 0.12%   |
| Garuda Linux     | 1         | 0.12%   |
| Deepin           | 1         | 0.12%   |
| Clear Linux      | 1         | 0.12%   |
| BunsenLabs       | 1         | 0.12%   |
| Artix            | 1         | 0.12%   |
| ALT Linux        | 1         | 0.12%   |
| Alpine           | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 73        | 7.33%   |
| 5.14.7-desktop-1omv4050  | 39        | 3.92%   |
| 5.4.0-42-generic         | 23        | 2.31%   |
| 5.4.0-52-generic         | 16        | 1.61%   |
| 5.4.0-26-generic         | 13        | 1.31%   |
| 5.4.0-58-generic         | 12        | 1.2%    |
| 5.3.0-40-generic         | 11        | 1.1%    |
| 5.16.7-desktop-1omv4003  | 10        | 1%      |
| 5.4.0-65-generic         | 9         | 0.9%    |
| 5.0.0-37-generic         | 9         | 0.9%    |
| 5.8.0-59-generic         | 8         | 0.8%    |
| 5.4.0-48-generic         | 8         | 0.8%    |
| 5.4.0-40-generic         | 8         | 0.8%    |
| 5.13.0-21-generic        | 8         | 0.8%    |
| 5.11.0-27-generic        | 8         | 0.8%    |
| 5.4.0-91-generic         | 7         | 0.7%    |
| 5.8.0-53-generic         | 6         | 0.6%    |
| 5.4.0-70-generic         | 6         | 0.6%    |
| 5.4.0-56-generic         | 6         | 0.6%    |
| 5.4.0-37-generic         | 6         | 0.6%    |
| 5.4.0-29-generic         | 6         | 0.6%    |
| 5.3.0-46-generic         | 6         | 0.6%    |
| 5.3.0-42-generic         | 6         | 0.6%    |
| 5.3.0-28-generic         | 6         | 0.6%    |
| 5.13.0-30-generic        | 6         | 0.6%    |
| 5.11.0-34-generic        | 6         | 0.6%    |
| 5.11.0-25-generic        | 6         | 0.6%    |
| 5.11.0-22-generic        | 6         | 0.6%    |
| 5.0.0-31-generic         | 6         | 0.6%    |
| 5.0.0-25-generic         | 6         | 0.6%    |
| 5.8.0-48-generic         | 5         | 0.5%    |
| 5.8.0-43-generic         | 5         | 0.5%    |
| 5.4.0-7642-generic       | 5         | 0.5%    |
| 5.4.0-51-generic         | 5         | 0.5%    |
| 5.3.0-45-generic         | 5         | 0.5%    |
| 5.3.0-26-generic         | 5         | 0.5%    |
| 5.13.0-22-generic        | 5         | 0.5%    |
| 5.13.0-19-generic        | 5         | 0.5%    |
| 5.11.0-16-generic        | 5         | 0.5%    |
| 5.10.0-8-amd64           | 5         | 0.5%    |
| 5.0.0-29-generic         | 5         | 0.5%    |
| 5.0.0-27-generic         | 5         | 0.5%    |
| 4.15.0-43-generic        | 5         | 0.5%    |
| 5.8.0-29-generic         | 4         | 0.4%    |
| 5.4.0-88-generic         | 4         | 0.4%    |
| 5.4.0-33-generic         | 4         | 0.4%    |
| 5.4.0-31-generic         | 4         | 0.4%    |
| 5.3.0-53-generic         | 4         | 0.4%    |
| 5.3.0-51-generic         | 4         | 0.4%    |
| 5.3.0-18-generic         | 4         | 0.4%    |
| 5.13.0-35-generic        | 4         | 0.4%    |
| 5.11.0-43-generic        | 4         | 0.4%    |
| 5.11.0-41-generic        | 4         | 0.4%    |
| 5.11.0-38-generic        | 4         | 0.4%    |
| 5.11.0-37-generic        | 4         | 0.4%    |
| 5.0.0-32-generic         | 4         | 0.4%    |
| 5.0.0-13-generic         | 4         | 0.4%    |
| 4.15.0-96-generic        | 4         | 0.4%    |
| 4.15.0-55-generic        | 4         | 0.4%    |
| 4.15.0-54-generic        | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 178       | 19.28%  |
| 5.10.14 | 73        | 7.91%   |
| 5.3.0   | 67        | 7.26%   |
| 5.11.0  | 63        | 6.83%   |
| 5.8.0   | 57        | 6.18%   |
| 4.15.0  | 55        | 5.96%   |
| 5.13.0  | 52        | 5.63%   |
| 5.0.0   | 45        | 4.88%   |
| 5.14.7  | 40        | 4.33%   |
| 4.18.0  | 22        | 2.38%   |
| 5.10.0  | 19        | 2.06%   |
| 5.16.7  | 11        | 1.19%   |
| 4.19.0  | 7         | 0.76%   |
| 5.15.12 | 5         | 0.54%   |
| 4.13.0  | 5         | 0.54%   |
| 5.9.16  | 4         | 0.43%   |
| 5.9.0   | 4         | 0.43%   |
| 5.6.16  | 4         | 0.43%   |
| 5.3.18  | 4         | 0.43%   |
| 5.16.11 | 4         | 0.43%   |
| 5.11.12 | 4         | 0.43%   |
| 4.4.0   | 4         | 0.43%   |
| 5.8.18  | 3         | 0.33%   |
| 5.16.2  | 3         | 0.33%   |
| 5.15.0  | 3         | 0.33%   |
| 5.14.0  | 3         | 0.33%   |
| 5.11.16 | 3         | 0.33%   |
| 5.10.52 | 3         | 0.33%   |
| 5.9.3   | 2         | 0.22%   |
| 5.8.15  | 2         | 0.22%   |
| 5.8.14  | 2         | 0.22%   |
| 5.7.0   | 2         | 0.22%   |
| 5.6.8   | 2         | 0.22%   |
| 5.6.14  | 2         | 0.22%   |
| 5.6.10  | 2         | 0.22%   |
| 5.6.0   | 2         | 0.22%   |
| 5.5.7   | 2         | 0.22%   |
| 5.5.6   | 2         | 0.22%   |
| 5.4.32  | 2         | 0.22%   |
| 5.4.19  | 2         | 0.22%   |
| 5.4.15  | 2         | 0.22%   |
| 5.3.8   | 2         | 0.22%   |
| 5.3.15  | 2         | 0.22%   |
| 5.17.1  | 2         | 0.22%   |
| 5.16.0  | 2         | 0.22%   |
| 5.15.6  | 2         | 0.22%   |
| 5.15.5  | 2         | 0.22%   |
| 5.15.32 | 2         | 0.22%   |
| 5.14.15 | 2         | 0.22%   |
| 5.14.14 | 2         | 0.22%   |
| 5.14.10 | 2         | 0.22%   |
| 5.13.8  | 2         | 0.22%   |
| 5.13.5  | 2         | 0.22%   |
| 5.13.4  | 2         | 0.22%   |
| 5.13.19 | 2         | 0.22%   |
| 5.13.12 | 2         | 0.22%   |
| 5.11.3  | 2         | 0.22%   |
| 5.11.11 | 2         | 0.22%   |
| 5.11.10 | 2         | 0.22%   |
| 5.10.74 | 2         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 194       | 21.06%  |
| 5.10    | 116       | 12.6%   |
| 5.11    | 84        | 9.12%   |
| 5.3     | 75        | 8.14%   |
| 5.8     | 72        | 7.82%   |
| 5.13    | 64        | 6.95%   |
| 4.15    | 57        | 6.19%   |
| 5.14    | 53        | 5.75%   |
| 5.0     | 47        | 5.1%    |
| 5.16    | 27        | 2.93%   |
| 4.18    | 24        | 2.61%   |
| 5.15    | 22        | 2.39%   |
| 5.9     | 16        | 1.74%   |
| 5.6     | 15        | 1.63%   |
| 4.19    | 11        | 1.19%   |
| 4.9     | 7         | 0.76%   |
| 5.7     | 6         | 0.65%   |
| 5.5     | 6         | 0.65%   |
| 5.12    | 6         | 0.65%   |
| 5.17    | 5         | 0.54%   |
| 4.13    | 5         | 0.54%   |
| 4.4     | 4         | 0.43%   |
| 5.1     | 2         | 0.22%   |
| 4.8     | 1         | 0.11%   |
| 4.17    | 1         | 0.11%   |
| 4.14    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 813       | 96.33%  |
| i686   | 31        | 3.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 351       | 40.16%  |
| KDE5            | 187       | 21.4%   |
| Unknown         | 129       | 14.76%  |
| XFCE            | 71        | 8.12%   |
| X-Cinnamon      | 33        | 3.78%   |
| MATE            | 22        | 2.52%   |
| KDE             | 21        | 2.4%    |
| Cinnamon        | 17        | 1.95%   |
| Pantheon        | 8         | 0.92%   |
| Unity           | 6         | 0.69%   |
| KDE4            | 6         | 0.69%   |
| LXQt            | 5         | 0.57%   |
| LXDE            | 4         | 0.46%   |
| GNOME Flashback | 3         | 0.34%   |
| awesome         | 3         | 0.34%   |
| XSession        | 1         | 0.11%   |
| xinitrc         | 1         | 0.11%   |
| qtile           | 1         | 0.11%   |
| openbox         | 1         | 0.11%   |
| i3              | 1         | 0.11%   |
| Enlightenment   | 1         | 0.11%   |
| DWM             | 1         | 0.11%   |
| custom          | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 689       | 79.56%  |
| Wayland | 94        | 10.85%  |
| Unknown | 78        | 9.01%   |
| Tty     | 5         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 433       | 49.77%  |
| SDDM    | 182       | 20.92%  |
| GDM     | 109       | 12.53%  |
| LightDM | 55        | 6.32%   |
| TDM     | 40        | 4.6%    |
| GDM3    | 40        | 4.6%    |
| KDM     | 5         | 0.57%   |
| XDM     | 2         | 0.23%   |
| LXDM    | 2         | 0.23%   |
| SLiM    | 1         | 0.11%   |
| Ly      | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 457       | 53.08%  |
| en_US   | 227       | 26.36%  |
| Unknown | 121       | 14.05%  |
| en_GB   | 15        | 1.74%   |
| C       | 15        | 1.74%   |
| ru_RU   | 8         | 0.93%   |
| sk_SK   | 3         | 0.35%   |
| POSIX   | 2         | 0.23%   |
| pl_PL   | 2         | 0.23%   |
| fr_FR   | 2         | 0.23%   |
| de_DE   | 2         | 0.23%   |
| uk_UA   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| it_IT   | 1         | 0.12%   |
| es_ES   | 1         | 0.12%   |
| en_NG   | 1         | 0.12%   |
| en_150  | 1         | 0.12%   |
| el_GR   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 461       | 53.23%  |
| EFI  | 405       | 46.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 598       | 69.94%  |
| Overlay  | 144       | 16.84%  |
| Btrfs    | 51        | 5.96%   |
| Unknown  | 33        | 3.86%   |
| Xfs      | 15        | 1.75%   |
| Zfs      | 4         | 0.47%   |
| Tmpfs    | 2         | 0.23%   |
| Ext3     | 2         | 0.23%   |
| Ext2     | 2         | 0.23%   |
| Aufs     | 2         | 0.23%   |
| Reiserfs | 1         | 0.12%   |
| F2fs     | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 449       | 52.7%   |
| GPT     | 240       | 28.17%  |
| MBR     | 163       | 19.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 779       | 91.54%  |
| Yes       | 72        | 8.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 539       | 62.53%  |
| Yes       | 323       | 37.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 204       | 24.17%  |
| ASUSTek Computer    | 169       | 20.02%  |
| Hewlett-Packard     | 161       | 19.08%  |
| Dell                | 124       | 14.69%  |
| Acer                | 88        | 10.43%  |
| Toshiba             | 13        | 1.54%   |
| Sony                | 12        | 1.42%   |
| MSI                 | 12        | 1.42%   |
| UMAX                | 7         | 0.83%   |
| Fujitsu             | 7         | 0.83%   |
| Unknown             | 5         | 0.59%   |
| HUAWEI              | 4         | 0.47%   |
| Apple               | 4         | 0.47%   |
| Fujitsu Siemens     | 3         | 0.36%   |
| TUXEDO              | 2         | 0.24%   |
| Timi                | 2         | 0.24%   |
| Packard Bell        | 2         | 0.24%   |
| Insyde              | 2         | 0.24%   |
| Google              | 2         | 0.24%   |
| Alienware           | 2         | 0.24%   |
| Samsung Electronics | 1         | 0.12%   |
| Purism              | 1         | 0.12%   |
| Prestigio           | 1         | 0.12%   |
| Panasonic           | 1         | 0.12%   |
| Notebook            | 1         | 0.12%   |
| Medion              | 1         | 0.12%   |
| Jumper              | 1         | 0.12%   |
| Intel               | 1         | 0.12%   |
| INET                | 1         | 0.12%   |
| In-Sing             | 1         | 0.12%   |
| IBM                 | 1         | 0.12%   |
| Gigabyte Technology | 1         | 0.12%   |
| EUROCOM             | 1         | 0.12%   |
| Dynabook            | 1         | 0.12%   |
| DATABOX             | 1         | 0.12%   |
| Clevo               | 1         | 0.12%   |
| Chuwi               | 1         | 0.12%   |
| Bluechip Computer   | 1         | 0.12%   |
| AMI                 | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 83        | 9.83%   |
| HP ProBook 455 G7                     | 6         | 0.71%   |
| Unknown                               | 6         | 0.71%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.59%   |
| Dell Latitude E6400                   | 5         | 0.59%   |
| Dell Latitude 5401                    | 5         | 0.59%   |
| HP ProBook 4540s                      | 4         | 0.47%   |
| HP EliteBook 840 G6                   | 4         | 0.47%   |
| Dell XPS 15 7590                      | 4         | 0.47%   |
| Dell Precision M6500                  | 4         | 0.47%   |
| Acer Extensa 5620                     | 4         | 0.47%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.36%   |
| HP ProBook 4530s                      | 3         | 0.36%   |
| HP ProBook 4510s                      | 3         | 0.36%   |
| HP ProBook 450 G5                     | 3         | 0.36%   |
| HP Pavilion dv7                       | 3         | 0.36%   |
| HP Pavilion dv6                       | 3         | 0.36%   |
| HP Notebook                           | 3         | 0.36%   |
| HP EliteBook 855 G7 Notebook PC       | 3         | 0.36%   |
| HP EliteBook 850 G6                   | 3         | 0.36%   |
| HP EliteBook 840 G3                   | 3         | 0.36%   |
| HP 250 G6 Notebook PC                 | 3         | 0.36%   |
| Dell XPS 15 9560                      | 3         | 0.36%   |
| Dell Latitude E6420                   | 3         | 0.36%   |
| Dell Latitude E5520                   | 3         | 0.36%   |
| Dell Latitude 5480                    | 3         | 0.36%   |
| ASUS E502SA                           | 3         | 0.36%   |
| Acer Extensa 5235                     | 3         | 0.36%   |
| Acer Extensa 5220                     | 3         | 0.36%   |
| MSI GE620/GE620DX/FX620DX/FX623       | 2         | 0.24%   |
| Lenovo Z50-75 80EC                    | 2         | 0.24%   |
| Lenovo Yoga 500-15IBD 80N6            | 2         | 0.24%   |
| Lenovo V330-15IKB 81AX                | 2         | 0.24%   |
| Lenovo ThinkPad T480s 20L8S2N80D      | 2         | 0.24%   |
| Lenovo ThinkPad T440p 20ANA01P00      | 2         | 0.24%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437   | 2         | 0.24%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 2         | 0.24%   |
| Lenovo IdeaPad Z580                   | 2         | 0.24%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 2         | 0.24%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 2         | 0.24%   |
| Lenovo IdeaPad C340-14API 81N6        | 2         | 0.24%   |
| Lenovo IdeaPad 530S-14ARR 81H1        | 2         | 0.24%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 2         | 0.24%   |
| Lenovo B50-80 80EW                    | 2         | 0.24%   |
| HP ProBook 6570b                      | 2         | 0.24%   |
| HP ProBook 650 G1                     | 2         | 0.24%   |
| HP ProBook 4525s                      | 2         | 0.24%   |
| HP ProBook 430 G5                     | 2         | 0.24%   |
| HP Laptop 15-bw0xx                    | 2         | 0.24%   |
| HP EliteBook 8570w                    | 2         | 0.24%   |
| HP EliteBook 8530p                    | 2         | 0.24%   |
| HP EliteBook 850 G5                   | 2         | 0.24%   |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.24%   |
| HP EliteBook 820 G2                   | 2         | 0.24%   |
| HP EliteBook 2170p                    | 2         | 0.24%   |
| HP 250 G2                             | 2         | 0.24%   |
| HP 15                                 | 2         | 0.24%   |
| Dell XPS 13 9370                      | 2         | 0.24%   |
| Dell XPS 13 9360                      | 2         | 0.24%   |
| Dell XPS 13 9300                      | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 115       | 13.63%  |
| ASUS UX31E            | 83        | 9.83%   |
| Dell Latitude         | 66        | 7.82%   |
| Acer Aspire           | 53        | 6.28%   |
| HP ProBook            | 48        | 5.69%   |
| HP EliteBook          | 45        | 5.33%   |
| Lenovo IdeaPad        | 35        | 4.15%   |
| Dell XPS              | 20        | 2.37%   |
| HP Pavilion           | 19        | 2.25%   |
| Dell Inspiron         | 14        | 1.66%   |
| Dell Precision        | 13        | 1.54%   |
| Acer Extensa          | 13        | 1.54%   |
| Toshiba Satellite     | 12        | 1.42%   |
| HP Compaq             | 10        | 1.18%   |
| Acer TravelMate       | 9         | 1.07%   |
| Lenovo Yoga           | 8         | 0.95%   |
| HP ZBook              | 8         | 0.95%   |
| HP Laptop             | 8         | 0.95%   |
| Lenovo ThinkBook      | 7         | 0.83%   |
| Fujitsu LIFEBOOK      | 7         | 0.83%   |
| Dell Vostro           | 7         | 0.83%   |
| ASUS ZenBook          | 7         | 0.83%   |
| ASUS VivoBook         | 7         | 0.83%   |
| Lenovo Legion         | 6         | 0.71%   |
| Acer Swift            | 6         | 0.71%   |
| Unknown               | 6         | 0.71%   |
| UMAX VisionBook       | 5         | 0.59%   |
| HP 250                | 5         | 0.59%   |
| HP Notebook           | 3         | 0.36%   |
| Fujitsu Siemens AMILO | 3         | 0.36%   |
| ASUS ROG              | 3         | 0.36%   |
| ASUS E502SA           | 3         | 0.36%   |
| Packard Bell EasyNote | 2         | 0.24%   |
| MSI GE620             | 2         | 0.24%   |
| Lenovo Z50-75         | 2         | 0.24%   |
| Lenovo V330-15IKB     | 2         | 0.24%   |
| Lenovo G780           | 2         | 0.24%   |
| Lenovo Flex           | 2         | 0.24%   |
| Lenovo B50-80         | 2         | 0.24%   |
| HP Presario           | 2         | 0.24%   |
| HP OMEN               | 2         | 0.24%   |
| HP ENVY               | 2         | 0.24%   |
| HP 255                | 2         | 0.24%   |
| HP 15                 | 2         | 0.24%   |
| Dell G5               | 2         | 0.24%   |
| ASUS X556UQ           | 2         | 0.24%   |
| ASUS X555LJ           | 2         | 0.24%   |
| ASUS X550CC           | 2         | 0.24%   |
| ASUS X540SA           | 2         | 0.24%   |
| ASUS TUF              | 2         | 0.24%   |
| ASUS K55VJ            | 2         | 0.24%   |
| ASUS G73Jh            | 2         | 0.24%   |
| ASUS F5RL             | 2         | 0.24%   |
| ASUS ASUS             | 2         | 0.24%   |
| Acer Nitro            | 2         | 0.24%   |
| UMAX MediaBook        | 1         | 0.12%   |
| UMAX 13Wa             | 1         | 0.12%   |
| TUXEDO Pulse          | 1         | 0.12%   |
| TUXEDO InfinityBook   | 1         | 0.12%   |
| Timi TM1701           | 1         | 0.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 133       | 15.76%  |
| 2019    | 84        | 9.95%   |
| 2020    | 74        | 8.77%   |
| 2018    | 69        | 8.18%   |
| 2012    | 62        | 7.35%   |
| 2014    | 52        | 6.16%   |
| 2017    | 51        | 6.04%   |
| 2015    | 48        | 5.69%   |
| 2008    | 48        | 5.69%   |
| 2013    | 47        | 5.57%   |
| 2021    | 38        | 4.5%    |
| 2016    | 38        | 4.5%    |
| 2010    | 35        | 4.15%   |
| 2007    | 28        | 3.32%   |
| 2009    | 23        | 2.73%   |
| 2006    | 9         | 1.07%   |
| 2005    | 2         | 0.24%   |
| 2004    | 2         | 0.24%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 844       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 745       | 87.03%  |
| Enabled  | 111       | 12.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 841       | 99.64%  |
| Yes  | 3         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 258       | 30.14%  |
| 4.01-8.0    | 181       | 21.14%  |
| 8.01-16.0   | 134       | 15.65%  |
| 16.01-24.0  | 125       | 14.6%   |
| 32.01-64.0  | 59        | 6.89%   |
| 1.01-2.0    | 51        | 5.96%   |
| 24.01-32.0  | 17        | 1.99%   |
| 2.01-3.0    | 15        | 1.75%   |
| 0.51-1.0    | 12        | 1.4%    |
| 64.01-256.0 | 4         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 359       | 38.52%  |
| 2.01-3.0   | 196       | 21.03%  |
| 4.01-8.0   | 127       | 13.63%  |
| 3.01-4.0   | 112       | 12.02%  |
| 0.51-1.0   | 63        | 6.76%   |
| 8.01-16.0  | 52        | 5.58%   |
| 0.01-0.5   | 12        | 1.29%   |
| 16.01-24.0 | 8         | 0.86%   |
| 32.01-64.0 | 2         | 0.21%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 672       | 78.05%  |
| 2      | 152       | 17.65%  |
| 3      | 23        | 2.67%   |
| 0      | 12        | 1.39%   |
| 4      | 2         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 553       | 65.29%  |
| Yes       | 294       | 34.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 725       | 85.29%  |
| No        | 125       | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 830       | 98.22%  |
| No        | 15        | 1.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 596       | 69.63%  |
| No        | 260       | 30.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 844       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Prague                       | 350       | 39.91%  |
| Brno                         | 74        | 8.44%   |
| Ostrava                      | 25        | 2.85%   |
| Olomouc                      | 17        | 1.94%   |
| Pilsen                       | 15        | 1.71%   |
| Pardubice                    | 14        | 1.6%    |
| Liberec                      | 10        | 1.14%   |
| ДЊeskГ© BudД›jovice   | 8         | 0.91%   |
| Hradec KrÃ¡lovÃ©         | 7         | 0.8%    |
| Chomutov                     | 6         | 0.68%   |
| ZlГ­n                      | 5         | 0.57%   |
| Most                         | 5         | 0.57%   |
| Kladno                       | 5         | 0.57%   |
| Jihlava                      | 5         | 0.57%   |
| Hradec KrГЎlovГ©         | 5         | 0.57%   |
| ГљstГ­ nad Labem         | 4         | 0.46%   |
| Roznov pod Radhostem         | 4         | 0.46%   |
| Rokycany                     | 4         | 0.46%   |
| Kraluv Dvur                  | 4         | 0.46%   |
| Bohumin                      | 4         | 0.46%   |
| Znojmo                       | 3         | 0.34%   |
| Zbiroh                       | 3         | 0.34%   |
| TvaroЕѕnГЎ               | 3         | 0.34%   |
| Sumperk                      | 3         | 0.34%   |
| Opava                        | 3         | 0.34%   |
| Odolena Voda                 | 3         | 0.34%   |
| Milovice                     | 3         | 0.34%   |
| MariÃ¡nskÃ© LÃ¡znÄ› | 3         | 0.34%   |
| Kralupy nad Vltavou          | 3         | 0.34%   |
| Karlovy Vary                 | 3         | 0.34%   |
| Beroun                       | 3         | 0.34%   |
| ÄŒeskÃ© BudÄ›jovice   | 3         | 0.34%   |
| As                           | 3         | 0.34%   |
| ДЊeskГЅ Krumlov          | 2         | 0.23%   |
| ZlÃ­n                      | 2         | 0.23%   |
| Vsetin                       | 2         | 0.23%   |
| Trinec                       | 2         | 0.23%   |
| Trhove Sviny                 | 2         | 0.23%   |
| TÃ¡bor                     | 2         | 0.23%   |
| Stary Plzenec                | 2         | 0.23%   |
| Slany                        | 2         | 0.23%   |
| Senov                        | 2         | 0.23%   |
| Rudna                        | 2         | 0.23%   |
| Roztoky                      | 2         | 0.23%   |
| Rakovnik                     | 2         | 0.23%   |
| PЕ™Г­bram               | 2         | 0.23%   |
| PЕ™erov                   | 2         | 0.23%   |
| ProstД›jov                | 2         | 0.23%   |
| Prelouc                      | 2         | 0.23%   |
| Pelhrimov                    | 2         | 0.23%   |
| Ostrov                       | 2         | 0.23%   |
| Ostopovice                   | 2         | 0.23%   |
| Odry                         | 2         | 0.23%   |
| Nezvestice                   | 2         | 0.23%   |
| Nachod                       | 2         | 0.23%   |
| Myslivna Vidly               | 2         | 0.23%   |
| Kurim                        | 2         | 0.23%   |
| Klimkovice                   | 2         | 0.23%   |
| Klatovy                      | 2         | 0.23%   |
| Jindrichuv Hradec            | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 154       | 209    | 15.42%  |
| SanDisk                        | 128       | 133    | 12.81%  |
| WDC                            | 109       | 131    | 10.91%  |
| Seagate                        | 109       | 154    | 10.91%  |
| Toshiba                        | 86        | 111    | 8.61%   |
| Kingston                       | 58        | 62     | 5.81%   |
| Unknown                        | 53        | 74     | 5.31%   |
| SK Hynix                       | 44        | 52     | 4.4%    |
| Hitachi                        | 42        | 52     | 4.2%    |
| HGST                           | 31        | 37     | 3.1%    |
| Intel                          | 28        | 34     | 2.8%    |
| Micron Technology              | 24        | 32     | 2.4%    |
| A-DATA Technology              | 21        | 23     | 2.1%    |
| Crucial                        | 15        | 24     | 1.5%    |
| Patriot                        | 14        | 18     | 1.4%    |
| KIOXIA                         | 8         | 11     | 0.8%    |
| Transcend                      | 6         | 6      | 0.6%    |
| LITEONIT                       | 6         | 8      | 0.6%    |
| Fujitsu                        | 6         | 6      | 0.6%    |
| China                          | 6         | 7      | 0.6%    |
| LITEON                         | 4         | 4      | 0.4%    |
| Phison                         | 3         | 11     | 0.3%    |
| JMicron                        | 3         | 3      | 0.3%    |
| ASMedia                        | 3         | 5      | 0.3%    |
| Apple                          | 3         | 3      | 0.3%    |
| Team                           | 2         | 2      | 0.2%    |
| Silicon Motion                 | 2         | 2      | 0.2%    |
| Lite-On                        | 2         | 4      | 0.2%    |
| Lenovo                         | 2         | 3      | 0.2%    |
| Gigabyte Technology            | 2         | 3      | 0.2%    |
| Corsair                        | 2         | 2      | 0.2%    |
| Apacer                         | 2         | 4      | 0.2%    |
| XrayDisk                       | 1         | 1      | 0.1%    |
| XPG                            | 1         | 1      | 0.1%    |
| Verbatim                       | 1         | 1      | 0.1%    |
| Union Memory                   | 1         | 1      | 0.1%    |
| UMIS                           | 1         | 1      | 0.1%    |
| UMAX                           | 1         | 1      | 0.1%    |
| TO Exter                       | 1         | 2      | 0.1%    |
| Solid State Storage Technology | 1         | 1      | 0.1%    |
| ShanDianZhe                    | 1         | 1      | 0.1%    |
| SABRENT                        | 1         | 1      | 0.1%    |
| OCZ                            | 1         | 4      | 0.1%    |
| Mushkin                        | 1         | 1      | 0.1%    |
| Micron/Crucial Technology      | 1         | 1      | 0.1%    |
| Mass                           | 1         | 1      | 0.1%    |
| IBM/Hitachi                    | 1         | 1      | 0.1%    |
| HPE                            | 1         | 2      | 0.1%    |
| GOODRAM                        | 1         | 2      | 0.1%    |
| CT500MX5                       | 1         | 1      | 0.1%    |
| ASMT                           | 1         | 1      | 0.1%    |
| ADATA SU                       | 1         | 1      | 0.1%    |
| Unknown                        | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB               | 83        | 7.98%   |
| Samsung NVMe SSD Drive 512GB         | 15        | 1.44%   |
| Samsung SSD 860 EVO 500GB            | 13        | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB       | 12        | 1.15%   |
| HGST HTS721010A9E630 1TB             | 11        | 1.06%   |
| Kingston SA400S37480G 480GB SSD      | 9         | 0.87%   |
| Unknown MMC Card  32GB               | 8         | 0.77%   |
| Toshiba MQ01ABD100 1TB               | 8         | 0.77%   |
| Sandisk NVMe SSD Drive 512GB         | 8         | 0.77%   |
| Samsung SSD 850 EVO 250GB            | 8         | 0.77%   |
| Unknown MMC Card  64GB               | 7         | 0.67%   |
| Toshiba NVMe SSD Drive 256GB         | 7         | 0.67%   |
| SK Hynix NVMe SSD Drive 512GB        | 7         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 0.67%   |
| Sandisk NVMe SSD Drive 1024GB        | 7         | 0.67%   |
| HGST HTS725050A7E630 500GB           | 7         | 0.67%   |
| Toshiba NVMe SSD Drive 512GB         | 6         | 0.58%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 0.58%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 0.58%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB             | 5         | 0.48%   |
| Unknown MMC Card  16GB               | 5         | 0.48%   |
| Unknown MMC Card  128GB              | 5         | 0.48%   |
| Toshiba MQ04ABF100 1TB               | 5         | 0.48%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.48%   |
| Seagate ST9500420AS 500GB            | 5         | 0.48%   |
| Seagate ST500LM000-1EJ162 500GB      | 5         | 0.48%   |
| Samsung SSD 850 EVO 500GB            | 5         | 0.48%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 0.48%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 5         | 0.48%   |
| Patriot Burst 480GB SSD              | 5         | 0.48%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 5         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 4         | 0.38%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 4         | 0.38%   |
| Toshiba MQ01ABD075 752GB             | 4         | 0.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 0.38%   |
| Seagate ST500LM000-SSHD-8GB          | 4         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.38%   |
| Seagate Expansion+ 2TB               | 4         | 0.38%   |
| Samsung SSD 970 EVO 1TB              | 4         | 0.38%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.38%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 4         | 0.38%   |
| Kingston SHSS37A240G 240GB SSD       | 4         | 0.38%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 3         | 0.29%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 3         | 0.29%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 3         | 0.29%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 3         | 0.29%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 3         | 0.29%   |
| SK Hynix NVMe SSD Drive 256GB        | 3         | 0.29%   |
| Seagate ST980811AS 80GB              | 3         | 0.29%   |
| Seagate ST9750420AS 752GB            | 3         | 0.29%   |
| Seagate ST9500325AS 500GB            | 3         | 0.29%   |
| Seagate ST9250315AS 250GB            | 3         | 0.29%   |
| Seagate ST9160827AS 160GB            | 3         | 0.29%   |
| Seagate ST500LM030-2E717D 500GB      | 3         | 0.29%   |
| Seagate ST320LT007-9ZV142 320GB      | 3         | 0.29%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 108       | 153    | 35.18%  |
| WDC                 | 65        | 79     | 21.17%  |
| Toshiba             | 47        | 54     | 15.31%  |
| Hitachi             | 42        | 52     | 13.68%  |
| HGST                | 31        | 37     | 10.1%   |
| Fujitsu             | 6         | 6      | 1.95%   |
| Samsung Electronics | 2         | 2      | 0.65%   |
| ASMedia             | 2         | 3      | 0.65%   |
| Unknown             | 1         | 1      | 0.33%   |
| SABRENT             | 1         | 1      | 0.33%   |
| IBM/Hitachi         | 1         | 1      | 0.33%   |
| ASMT                | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 106       | 108    | 27.75%  |
| Samsung Electronics | 82        | 104    | 21.47%  |
| Kingston            | 46        | 50     | 12.04%  |
| A-DATA Technology   | 19        | 21     | 4.97%   |
| WDC                 | 18        | 24     | 4.71%   |
| Patriot             | 14        | 18     | 3.66%   |
| Crucial             | 14        | 23     | 3.66%   |
| Intel               | 13        | 14     | 3.4%    |
| SK Hynix            | 11        | 11     | 2.88%   |
| Toshiba             | 10        | 12     | 2.62%   |
| Micron Technology   | 10        | 15     | 2.62%   |
| Transcend           | 6         | 6      | 1.57%   |
| LITEONIT            | 6         | 8      | 1.57%   |
| China               | 6         | 7      | 1.57%   |
| LITEON              | 3         | 3      | 0.79%   |
| Apple               | 2         | 2      | 0.52%   |
| Apacer              | 2         | 4      | 0.52%   |
| Verbatim            | 1         | 1      | 0.26%   |
| UMIS                | 1         | 1      | 0.26%   |
| UMAX                | 1         | 1      | 0.26%   |
| TO Exter            | 1         | 2      | 0.26%   |
| Team                | 1         | 1      | 0.26%   |
| ShanDianZhe         | 1         | 1      | 0.26%   |
| Seagate             | 1         | 1      | 0.26%   |
| OCZ                 | 1         | 4      | 0.26%   |
| Mushkin             | 1         | 1      | 0.26%   |
| JMicron             | 1         | 1      | 0.26%   |
| GOODRAM             | 1         | 2      | 0.26%   |
| Gigabyte Technology | 1         | 1      | 0.26%   |
| CT500MX5            | 1         | 1      | 0.26%   |
| ADATA SU            | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 364       | 449    | 37.6%   |
| HDD     | 298       | 390    | 30.79%  |
| NVMe    | 245       | 331    | 25.31%  |
| MMC     | 55        | 79     | 5.68%   |
| Unknown | 6         | 8      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 603       | 810    | 64.77%  |
| NVMe | 245       | 331    | 26.32%  |
| MMC  | 55        | 79     | 5.91%   |
| SAS  | 28        | 37     | 3.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 491       | 615    | 75.08%  |
| 0.51-1.0   | 144       | 192    | 22.02%  |
| 1.01-2.0   | 18        | 30     | 2.75%   |
| 3.01-4.0   | 1         | 2      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 225       | 25.89%  |
| 251-500        | 187       | 21.52%  |
| 1-20           | 145       | 16.69%  |
| 501-1000       | 113       | 13%     |
| 51-100         | 69        | 7.94%   |
| 21-50          | 40        | 4.6%    |
| 1001-2000      | 39        | 4.49%   |
| Unknown        | 31        | 3.57%   |
| More than 3000 | 15        | 1.73%   |
| 2001-3000      | 5         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 423       | 46.64%  |
| 21-50          | 118       | 13.01%  |
| 101-250        | 114       | 12.57%  |
| 51-100         | 98        | 10.8%   |
| 251-500        | 70        | 7.72%   |
| Unknown        | 31        | 3.42%   |
| 501-1000       | 28        | 3.09%   |
| 1001-2000      | 15        | 1.65%   |
| More than 3000 | 6         | 0.66%   |
| 2001-3000      | 4         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                           | 83        | 83     | 61.94%  |
| HGST HTS725050A7E630 500GB                       | 3         | 3      | 2.24%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 1.49%   |
| Seagate ST9500420AS 500GB                        | 2         | 3      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 1.49%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1         | 1      | 0.75%   |
| WDC WD6400BPVT-60HXZT1 640GB                     | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 0.75%   |
| Toshiba MK8037GSX 80GB                           | 1         | 1      | 0.75%   |
| Toshiba MK6465GSXN 640GB                         | 1         | 1      | 0.75%   |
| Toshiba MK5056GSY 500GB                          | 1         | 1      | 0.75%   |
| Toshiba MK2552GSX 250GB                          | 1         | 1      | 0.75%   |
| Toshiba MK1234GSX 120GB                          | 1         | 1      | 0.75%   |
| SK Hynix HFS256G3BTND-N210A 256GB SSD            | 1         | 1      | 0.75%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 0.75%   |
| SK Hynix BC711 HFM512GD3JX013N 512GB             | 1         | 1      | 0.75%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 0.75%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 0.75%   |
| Seagate ST9250410ASG 250GB                       | 1         | 1      | 0.75%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 0.75%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 0.75%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 0.75%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 0.75%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 0.75%   |
| SanDisk SD8SBAT-032G-1006 32GB SSD               | 1         | 1      | 0.75%   |
| SanDisk SD7SB3Q256G1002 256GB SSD                | 1         | 1      | 0.75%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 0.75%   |
| Samsung Electronics MZVLB1T0HALR-000L2 1TB       | 1         | 1      | 0.75%   |
| Samsung Electronics MZ7TE256HMHP-000L7 256GB SSD | 1         | 1      | 0.75%   |
| LITEONIT LAT-128M2S 128GB SSD                    | 1         | 1      | 0.75%   |
| Intel SSDSCKJF240A5L 240GB                       | 1         | 1      | 0.75%   |
| Intel SSDSA2M160G2LE 160GB                       | 1         | 1      | 0.75%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB                | 1         | 1      | 0.75%   |
| Hitachi HTS725016A9A364 160GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS547564A9E384 640GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS545032B9SA02 320GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS545016B9A300 160GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS543232L9A300 320GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 0.75%   |
| Hitachi HTS421280H9AT00 80GB                     | 1         | 1      | 0.75%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 0.75%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 0.75%   |
| Fujitsu MHZ2250BH G2 250GB                       | 1         | 1      | 0.75%   |
| A-DATA Technology SP900 64GB SSD                 | 1         | 1      | 0.75%   |
| A-DATA Technology SP900 256GB SSD                | 1         | 1      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 85        | 85     | 63.43%  |
| Seagate             | 12        | 13     | 8.96%   |
| Hitachi             | 9         | 9      | 6.72%   |
| Toshiba             | 8         | 8      | 5.97%   |
| HGST                | 5         | 5      | 3.73%   |
| SK Hynix            | 3         | 3      | 2.24%   |
| Samsung Electronics | 3         | 3      | 2.24%   |
| WDC                 | 2         | 2      | 1.49%   |
| Intel               | 2         | 2      | 1.49%   |
| A-DATA Technology   | 2         | 2      | 1.49%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| IBM/Hitachi         | 1         | 1      | 0.75%   |
| Fujitsu             | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 12        | 13     | 31.58%  |
| Hitachi     | 9         | 9      | 23.68%  |
| Toshiba     | 8         | 8      | 21.05%  |
| HGST        | 5         | 5      | 13.16%  |
| WDC         | 2         | 2      | 5.26%   |
| IBM/Hitachi | 1         | 1      | 2.63%   |
| Fujitsu     | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 94        | 94     | 70.15%  |
| HDD  | 38        | 39     | 28.36%  |
| NVMe | 2         | 2      | 1.49%   |

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
| Detected | 472       | 781    | 53.88%  |
| Works    | 271       | 341    | 30.94%  |
| Malfunc  | 133       | 135    | 15.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 617       | 64.41%  |
| AMD                              | 89        | 9.29%   |
| Samsung Electronics              | 78        | 8.14%   |
| Sandisk                          | 43        | 4.49%   |
| SK Hynix                         | 31        | 3.24%   |
| Toshiba America Info Systems     | 29        | 3.03%   |
| Micron Technology                | 14        | 1.46%   |
| Kingston Technology Company      | 12        | 1.25%   |
| KIOXIA                           | 10        | 1.04%   |
| Phison Electronics               | 6         | 0.63%   |
| Silicon Motion                   | 4         | 0.42%   |
| Union Memory (Shenzhen)          | 3         | 0.31%   |
| Silicon Integrated Systems [SiS] | 3         | 0.31%   |
| Lite-On Technology               | 3         | 0.31%   |
| ADATA Technology                 | 3         | 0.31%   |
| Nvidia                           | 2         | 0.21%   |
| Micron/Crucial Technology        | 2         | 0.21%   |
| Lenovo                           | 2         | 0.21%   |
| ASMedia Technology               | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.1%    |
| Solid State Storage Technology   | 1         | 0.1%    |
| Marvell Technology Group         | 1         | 0.1%    |
| JMicron Technology               | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 126       | 12.27%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 69        | 6.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 58        | 5.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 58        | 5.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 42        | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 39        | 3.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 38        | 3.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 27        | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26        | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 2.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 25        | 2.43%   |
| Samsung NVMe SSD Controller 980                                                  | 21        | 2.04%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 18        | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 15        | 1.46%   |
| Micron Non-Volatile memory controller                                            | 14        | 1.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 14        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 1.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 11        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 11        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.07%   |
| SK Hynix Gold P31 SSD                                                            | 10        | 0.97%   |
| KIOXIA Non-Volatile memory controller                                            | 10        | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.97%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 9         | 0.88%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 9         | 0.88%   |
| SK Hynix Non-Volatile memory controller                                          | 8         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.78%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 7         | 0.68%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.68%   |
| SK Hynix BC511                                                                   | 6         | 0.58%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 6         | 0.58%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 6         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 0.58%   |
| Sandisk Non-Volatile memory controller                                           | 5         | 0.49%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.49%   |
| Intel SSD 660P Series                                                            | 5         | 0.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 0.49%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 4         | 0.39%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.39%   |
| Kingston Company A2000 NVMe SSD                                                  | 4         | 0.39%   |
| Intel Non-Volatile memory controller                                             | 4         | 0.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.39%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 4         | 0.39%   |
| AMD SB600 IDE                                                                    | 4         | 0.39%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.29%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.29%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 0.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.29%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 0.29%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.29%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 614       | 61.96%  |
| NVMe | 247       | 24.92%  |
| IDE  | 71        | 7.16%   |
| RAID | 59        | 5.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 711       | 84.24%  |
| AMD    | 133       | 15.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 83        | 9.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 16        | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.54%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.42%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 11        | 1.3%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.95%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.83%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 0.83%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 0.71%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.71%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 5         | 0.59%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 5         | 0.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 0.59%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.59%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 5         | 0.59%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.59%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.47%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.47%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.47%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 4         | 0.47%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.47%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.47%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.47%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 4         | 0.47%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 4         | 0.47%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.47%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.47%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 269       | 31.83%  |
| Intel Core i5           | 179       | 21.18%  |
| Intel Core 2 Duo        | 64        | 7.57%   |
| Intel Core i3           | 51        | 6.04%   |
| Intel Celeron           | 47        | 5.56%   |
| Other                   | 30        | 3.55%   |
| AMD Ryzen 5             | 29        | 3.43%   |
| AMD Ryzen 7             | 24        | 2.84%   |
| Intel Pentium           | 22        | 2.6%    |
| AMD Ryzen 7 PRO         | 18        | 2.13%   |
| Intel Atom              | 16        | 1.89%   |
| AMD A6                  | 10        | 1.18%   |
| AMD A8                  | 6         | 0.71%   |
| AMD A4                  | 6         | 0.71%   |
| Intel Pentium Dual-Core | 5         | 0.59%   |
| Intel Core 2            | 5         | 0.59%   |
| Intel Celeron M         | 5         | 0.59%   |
| Intel Xeon              | 4         | 0.47%   |
| Intel Pentium Silver    | 4         | 0.47%   |
| Intel Pentium M         | 3         | 0.36%   |
| Intel Pentium Dual      | 3         | 0.36%   |
| Intel Celeron Dual-Core | 3         | 0.36%   |
| AMD Turion II           | 3         | 0.36%   |
| AMD Turion 64 X2 Mobile | 3         | 0.36%   |
| AMD Ryzen 9             | 3         | 0.36%   |
| AMD Ryzen 5 PRO         | 3         | 0.36%   |
| AMD E1                  | 3         | 0.36%   |
| AMD E                   | 3         | 0.36%   |
| AMD A10                 | 3         | 0.36%   |
| Intel Genuine           | 2         | 0.24%   |
| Intel Core i9           | 2         | 0.24%   |
| AMD Mobile Sempron      | 2         | 0.24%   |
| AMD FX                  | 2         | 0.24%   |
| AMD Athlon X2           | 2         | 0.24%   |
| AMD A12                 | 2         | 0.24%   |
| Intel Core m5           | 1         | 0.12%   |
| Intel Core Duo          | 1         | 0.12%   |
| AMD Turion              | 1         | 0.12%   |
| AMD Ryzen 3 PRO         | 1         | 0.12%   |
| AMD Ryzen 3             | 1         | 0.12%   |
| AMD Phenom II           | 1         | 0.12%   |
| AMD E2                  | 1         | 0.12%   |
| AMD C-50                | 1         | 0.12%   |
| AMD Athlon II Dual-Core | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 470       | 55.62%  |
| 4       | 253       | 29.94%  |
| 6       | 55        | 6.51%   |
| 8       | 42        | 4.97%   |
| 1       | 24        | 2.84%   |
| Unknown | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 844       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 607       | 71.92%  |
| 1       | 236       | 27.96%  |
| Unknown | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 815       | 96.11%  |
| Unknown        | 17        | 2%      |
| 32-bit         | 15        | 1.77%   |
| 64-bit         | 1         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 129       | 14.86%  |
| Unknown    | 127       | 14.63%  |
| 0x306a9    | 46        | 5.3%    |
| 0x806ea    | 36        | 4.15%   |
| 0x806ec    | 31        | 3.57%   |
| 0x1067a    | 31        | 3.57%   |
| 0x406e3    | 26        | 3%      |
| 0x40651    | 26        | 3%      |
| 0x906ea    | 25        | 2.88%   |
| 0x306c3    | 24        | 2.76%   |
| 0x08600106 | 22        | 2.53%   |
| 0x806e9    | 21        | 2.42%   |
| 0x806c1    | 19        | 2.19%   |
| 0x6fd      | 19        | 2.19%   |
| 0x306d4    | 18        | 2.07%   |
| 0x30678    | 15        | 1.73%   |
| 0x20655    | 13        | 1.5%    |
| 0xa0652    | 10        | 1.15%   |
| 0x906e9    | 9         | 1.04%   |
| 0x406c3    | 9         | 1.04%   |
| 0x10676    | 9         | 1.04%   |
| 0x08108102 | 9         | 1.04%   |
| 0x906ed    | 8         | 0.92%   |
| 0x706a1    | 8         | 0.92%   |
| 0x506e3    | 8         | 0.92%   |
| 0x706e5    | 7         | 0.81%   |
| 0x506c9    | 7         | 0.81%   |
| 0x406c4    | 7         | 0.81%   |
| 0x20652    | 7         | 0.81%   |
| 0x106e5    | 7         | 0.81%   |
| 0x10661    | 7         | 0.81%   |
| 0x08600103 | 7         | 0.81%   |
| 0x806eb    | 6         | 0.69%   |
| 0x0a50000c | 6         | 0.69%   |
| 0x08608103 | 6         | 0.69%   |
| 0x08600104 | 6         | 0.69%   |
| 0x07030105 | 6         | 0.69%   |
| 0x06006705 | 6         | 0.69%   |
| 0x06001119 | 6         | 0.69%   |
| 0x6fb      | 5         | 0.58%   |
| 0x6f6      | 5         | 0.58%   |
| 0x30673    | 5         | 0.58%   |
| 0x6e8      | 4         | 0.46%   |
| 0x106c2    | 4         | 0.46%   |
| 0x08108109 | 4         | 0.46%   |
| 0x06006704 | 4         | 0.46%   |
| 0x010000c8 | 4         | 0.46%   |
| 0x6d8      | 3         | 0.35%   |
| 0x0810100b | 3         | 0.35%   |
| 0x06003106 | 3         | 0.35%   |
| 0x05000119 | 3         | 0.35%   |
| 0xa0660    | 2         | 0.23%   |
| 0x906c0    | 2         | 0.23%   |
| 0x806c2    | 2         | 0.23%   |
| 0x6fa      | 2         | 0.23%   |
| 0x0a50000b | 2         | 0.23%   |
| 0x08101007 | 2         | 0.23%   |
| 0x07030104 | 2         | 0.23%   |
| 0x0700010f | 2         | 0.23%   |
| 0x06006118 | 2         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 158       | 18.72%  |
| SandyBridge     | 137       | 16.23%  |
| Haswell         | 60        | 7.11%   |
| IvyBridge       | 56        | 6.64%   |
| Penryn          | 50        | 5.92%   |
| Zen 2           | 39        | 4.62%   |
| Skylake         | 38        | 4.5%    |
| Silvermont      | 38        | 4.5%    |
| Core            | 38        | 4.5%    |
| Westmere        | 25        | 2.96%   |
| TigerLake       | 24        | 2.84%   |
| Broadwell       | 21        | 2.49%   |
| Zen+            | 15        | 1.78%   |
| CometLake       | 13        | 1.54%   |
| Excavator       | 12        | 1.42%   |
| Zen 3           | 11        | 1.3%    |
| Goldmont plus   | 11        | 1.3%    |
| Unknown         | 10        | 1.18%   |
| Nehalem         | 9         | 1.07%   |
| Puma            | 8         | 0.95%   |
| Piledriver      | 8         | 0.95%   |
| P6              | 8         | 0.95%   |
| IceLake         | 8         | 0.95%   |
| Goldmont        | 8         | 0.95%   |
| Bonnell         | 6         | 0.71%   |
| Zen             | 5         | 0.59%   |
| K8 Hammer       | 5         | 0.59%   |
| K10             | 5         | 0.59%   |
| Bobcat          | 5         | 0.59%   |
| Steamroller     | 4         | 0.47%   |
| K8 & K10 hybrid | 3         | 0.36%   |
| Jaguar          | 3         | 0.36%   |
| Tremont         | 2         | 0.24%   |
| K10 Llano       | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 631       | 60.56%  |
| Nvidia                           | 209       | 20.06%  |
| AMD                              | 198       | 19%     |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| VIA Technologies                 | 1         | 0.1%    |
| ATI Technologies                 | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 131       | 11.96%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 4.75%   |
| Intel UHD Graphics 620                                                                   | 39        | 3.56%   |
| AMD Renoir                                                                               | 38        | 3.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 2.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 2.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 2.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 2.1%    |
| Intel HD Graphics 620                                                                    | 23        | 2.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.74%   |
| Intel HD Graphics 5500                                                                   | 18        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 12        | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 1%      |
| Intel HD Graphics 630                                                                    | 11        | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 0.91%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.82%   |
| AMD Lucienne                                                                             | 9         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.73%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.73%   |
| Intel HD Graphics 530                                                                    | 8         | 0.73%   |
| Intel HD Graphics 500                                                                    | 8         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.73%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 8         | 0.73%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 8         | 0.73%   |
| AMD Cezanne                                                                              | 8         | 0.73%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.64%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 7         | 0.64%   |
| Nvidia TU117M [GeForce MX450]                                                            | 6         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.55%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 6         | 0.55%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 5         | 0.46%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.46%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.46%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.46%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.37%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.37%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.37%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.37%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.37%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.37%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 4         | 0.37%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 4         | 0.37%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.37%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 4         | 0.37%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 441       | 52.25%  |
| Intel + Nvidia | 153       | 18.13%  |
| 1 x AMD        | 133       | 15.76%  |
| 1 x Nvidia     | 48        | 5.69%   |
| Intel + AMD    | 37        | 4.38%   |
| 2 x AMD        | 21        | 2.49%   |
| AMD + Nvidia   | 8         | 0.95%   |
| 1 x SiS        | 2         | 0.24%   |
| 1 x VIA        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 734       | 86.45%  |
| Proprietary | 90        | 10.6%   |
| Unknown     | 25        | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 550       | 63.81%  |
| 1.01-2.0   | 111       | 12.88%  |
| 0.01-0.5   | 107       | 12.41%  |
| 0.51-1.0   | 46        | 5.34%   |
| 3.01-4.0   | 34        | 3.94%   |
| 5.01-6.0   | 9         | 1.04%   |
| 2.01-3.0   | 3         | 0.35%   |
| 7.01-8.0   | 1         | 0.12%   |
| 8.01-16.0  | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 186       | 18.67%  |
| LG Display              | 133       | 13.35%  |
| Chimei Innolux          | 104       | 10.44%  |
| Samsung Electronics     | 89        | 8.94%   |
| CPT                     | 85        | 8.53%   |
| BOE                     | 79        | 7.93%   |
| Dell                    | 50        | 5.02%   |
| Sharp                   | 33        | 3.31%   |
| Chi Mei Optoelectronics | 26        | 2.61%   |
| Lenovo                  | 23        | 2.31%   |
| Eizo                    | 21        | 2.11%   |
| Hewlett-Packard         | 20        | 2.01%   |
| PANDA                   | 15        | 1.51%   |
| Philips                 | 14        | 1.41%   |
| LG Philips              | 13        | 1.31%   |
| BenQ                    | 13        | 1.31%   |
| Goldstar                | 11        | 1.1%    |
| Acer                    | 9         | 0.9%    |
| AOC                     | 8         | 0.8%    |
| Sony                    | 6         | 0.6%    |
| Quanta Display          | 6         | 0.6%    |
| Iiyama                  | 5         | 0.5%    |
| Ancor Communications    | 5         | 0.5%    |
| Toshiba                 | 4         | 0.4%    |
| Panasonic               | 4         | 0.4%    |
| InfoVision              | 4         | 0.4%    |
| CSO                     | 4         | 0.4%    |
| Apple                   | 4         | 0.4%    |
| HannStar                | 3         | 0.3%    |
| NEC Computers           | 2         | 0.2%    |
| Fujitsu Siemens         | 2         | 0.2%    |
| DENON                   | 2         | 0.2%    |
| ViewSonic               | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| TCL                     | 1         | 0.1%    |
| OEM                     | 1         | 0.1%    |
| MStar                   | 1         | 0.1%    |
| LPL                     | 1         | 0.1%    |
| LGD                     | 1         | 0.1%    |
| Lenovo Group Limited    | 1         | 0.1%    |
| JDI                     | 1         | 0.1%    |
| Hitachi                 | 1         | 0.1%    |
| GBM                     | 1         | 0.1%    |
| eMachines               | 1         | 0.1%    |
| ASUSTek Computer        | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 83        | 8.11%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 20        | 1.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 11        | 1.07%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 7         | 0.68%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.59%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.49%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 5         | 0.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 5         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 5         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 5         | 0.49%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 5         | 0.49%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x194mm 15.5-inch             | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.49%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 0.39%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 4         | 0.39%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 4         | 0.39%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                   | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch      | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch     | 3         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 3         | 0.29%   |
| Quanta Display LCD Monitor QDS0041 1280x800 331x207mm 15.4-inch           | 3         | 0.29%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 3         | 0.29%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                        | 3         | 0.29%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch               | 3         | 0.29%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 3         | 0.29%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 3         | 0.29%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 3         | 0.29%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                   | 3         | 0.29%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch                | 3         | 0.29%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 3         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 3         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 3         | 0.29%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                     | 3         | 0.29%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                     | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 382       | 41.16%  |
| 1366x768 (WXGA)    | 182       | 19.61%  |
| 1600x900 (HD+)     | 140       | 15.09%  |
| 1280x800 (WXGA)    | 54        | 5.82%   |
| 3840x2160 (4K)     | 53        | 5.71%   |
| 2560x1440 (QHD)    | 26        | 2.8%    |
| 1920x1200 (WUXGA)  | 25        | 2.69%   |
| 1440x900 (WXGA+)   | 12        | 1.29%   |
| 1680x1050 (WSXGA+) | 11        | 1.19%   |
| 1280x1024 (SXGA)   | 7         | 0.75%   |
| 2560x1600          | 4         | 0.43%   |
| 1024x600           | 4         | 0.43%   |
| 1360x768           | 3         | 0.32%   |
| 1024x768 (XGA)     | 3         | 0.32%   |
| Unknown            | 3         | 0.32%   |
| 3840x2400          | 2         | 0.22%   |
| 3200x1800 (QHD+)   | 2         | 0.22%   |
| 3000x2000          | 2         | 0.22%   |
| 2160x1440          | 2         | 0.22%   |
| 1920x540           | 2         | 0.22%   |
| 8320x2160          | 1         | 0.11%   |
| 5760x2160          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3456x2160          | 1         | 0.11%   |
| 3440x1440          | 1         | 0.11%   |
| 2160x1350          | 1         | 0.11%   |
| 1920x515           | 1         | 0.11%   |
| 1400x1050          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 350       | 35%     |
| 13      | 202       | 20.2%   |
| 14      | 108       | 10.8%   |
| 17      | 67        | 6.7%    |
| 24      | 57        | 5.7%    |
| 27      | 41        | 4.1%    |
| 31      | 28        | 2.8%    |
| 23      | 25        | 2.5%    |
| 12      | 23        | 2.3%    |
| 11      | 19        | 1.9%    |
| 21      | 17        | 1.7%    |
| Unknown | 12        | 1.2%    |
| 22      | 7         | 0.7%    |
| 18      | 7         | 0.7%    |
| 84      | 5         | 0.5%    |
| 10      | 5         | 0.5%    |
| 25      | 4         | 0.4%    |
| 20      | 4         | 0.4%    |
| 19      | 4         | 0.4%    |
| 32      | 3         | 0.3%    |
| 16      | 3         | 0.3%    |
| 72      | 2         | 0.2%    |
| 60      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 34      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 513       | 52.24%  |
| 201-300     | 185       | 18.84%  |
| 501-600     | 110       | 11.2%   |
| 351-400     | 77        | 7.84%   |
| 401-500     | 35        | 3.56%   |
| 601-700     | 34        | 3.46%   |
| Unknown     | 12        | 1.22%   |
| 1501-2000   | 7         | 0.71%   |
| 701-800     | 5         | 0.51%   |
| 1001-1500   | 4         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 702       | 82.98%  |
| 16/10   | 117       | 13.83%  |
| 5/4     | 7         | 0.83%   |
| Unknown | 7         | 0.83%   |
| 3/2     | 6         | 0.71%   |
| 4/3     | 4         | 0.47%   |
| 3.73    | 1         | 0.12%   |
| 3.20    | 1         | 0.12%   |
| 21/9    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 345       | 34.6%   |
| 81-90          | 175       | 17.55%  |
| 71-80          | 135       | 13.54%  |
| 201-250        | 80        | 8.02%   |
| 121-130        | 50        | 5.02%   |
| 301-350        | 42        | 4.21%   |
| 351-500        | 33        | 3.31%   |
| 251-300        | 26        | 2.61%   |
| 61-70          | 23        | 2.31%   |
| 51-60          | 19        | 1.91%   |
| 131-140        | 13        | 1.3%    |
| Unknown        | 12        | 1.2%    |
| More than 1000 | 10        | 1%      |
| 151-200        | 10        | 1%      |
| 141-150        | 10        | 1%      |
| 41-50          | 5         | 0.5%    |
| 111-120        | 4         | 0.4%    |
| 91-100         | 4         | 0.4%    |
| 501-1000       | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 464       | 48.69%  |
| 101-120       | 211       | 22.14%  |
| 51-100        | 191       | 20.04%  |
| 161-240       | 53        | 5.56%   |
| More than 240 | 17        | 1.78%   |
| Unknown       | 12        | 1.26%   |
| 1-50          | 5         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 644       | 74.02%  |
| 2     | 171       | 19.66%  |
| 0     | 29        | 3.33%   |
| 3     | 25        | 2.87%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 450       | 32.37%  |
| Realtek Semiconductor             | 342       | 24.6%   |
| Qualcomm Atheros                  | 274       | 19.71%  |
| Broadcom                          | 84        | 6.04%   |
| Samsung Electronics               | 83        | 5.97%   |
| Broadcom Limited                  | 32        | 2.3%    |
| Marvell Technology Group          | 18        | 1.29%   |
| Lenovo                            | 17        | 1.22%   |
| MEDIATEK                          | 12        | 0.86%   |
| Dell                              | 12        | 0.86%   |
| Sierra Wireless                   | 8         | 0.58%   |
| TP-Link                           | 7         | 0.5%    |
| DisplayLink                       | 7         | 0.5%    |
| Ralink                            | 6         | 0.43%   |
| Ralink Technology                 | 5         | 0.36%   |
| Qualcomm Atheros Communications   | 5         | 0.36%   |
| ASIX Electronics                  | 4         | 0.29%   |
| Hewlett-Packard                   | 3         | 0.22%   |
| Ericsson Business Mobile Networks | 3         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.14%   |
| D-Link                            | 2         | 0.14%   |
| Attansic Technology               | 2         | 0.14%   |
| Xiaomi                            | 1         | 0.07%   |
| VIA Technologies                  | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Huawei Technologies               | 1         | 0.07%   |
| Fujitsu Siemens Computers         | 1         | 0.07%   |
| Foxconn / Hon Hai                 | 1         | 0.07%   |
| Fibocom                           | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| Arduino SA                        | 1         | 0.07%   |
| AMD                               | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 235       | 14.11%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 104       | 6.24%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 82        | 4.92%   |
| Intel Wi-Fi 6 AX200                                                     | 58        | 3.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 47        | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 41        | 2.46%   |
| Intel Wireless 8265 / 8275                                              | 39        | 2.34%   |
| Intel Wireless 7260                                                     | 37        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 37        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 28        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 22        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                   | 21        | 1.26%   |
| Intel Wireless 8260                                                     | 19        | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 17        | 1.02%   |
| Intel 82567LM Gigabit Network Connection                                | 17        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 15        | 0.9%    |
| Intel Wireless 7265                                                     | 15        | 0.9%    |
| Intel Wireless 3165                                                     | 15        | 0.9%    |
| Intel WiFi Link 5100                                                    | 15        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 13        | 0.78%   |
| Intel Wireless 3160                                                     | 12        | 0.72%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.66%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 11        | 0.66%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                   | 10        | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                    | 10        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 9         | 0.54%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.54%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 0.54%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.48%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.48%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 7         | 0.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 7         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.42%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                   | 7         | 0.42%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 7         | 0.42%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 7         | 0.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 6         | 0.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.36%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 440       | 50.75%  |
| Qualcomm Atheros                | 241       | 27.8%   |
| Realtek Semiconductor           | 65        | 7.5%    |
| Broadcom                        | 50        | 5.77%   |
| Broadcom Limited                | 18        | 2.08%   |
| MEDIATEK                        | 12        | 1.38%   |
| TP-Link                         | 7         | 0.81%   |
| Ralink                          | 6         | 0.69%   |
| Dell                            | 6         | 0.69%   |
| Sierra Wireless                 | 5         | 0.58%   |
| Ralink Technology               | 5         | 0.58%   |
| Qualcomm Atheros Communications | 5         | 0.58%   |
| Qualcomm                        | 1         | 0.12%   |
| Lenovo                          | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Fujitsu Siemens Computers       | 1         | 0.12%   |
| Fibocom                         | 1         | 0.12%   |
| D-Link                          | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 104       | 11.95%  |
| Intel Wi-Fi 6 AX200                                                         | 58        | 6.67%   |
| Intel Wireless 8265 / 8275                                                  | 39        | 4.48%   |
| Intel Wireless 7260                                                         | 37        | 4.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 33        | 3.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 29        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 28        | 3.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 28        | 3.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 22        | 2.53%   |
| Intel Wireless 8260                                                         | 19        | 2.18%   |
| Intel Wi-Fi 6 AX201                                                         | 18        | 2.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 17        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 17        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 16        | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 16        | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 15        | 1.72%   |
| Intel Wireless 7265                                                         | 15        | 1.72%   |
| Intel Wireless 3165                                                         | 15        | 1.72%   |
| Intel WiFi Link 5100                                                        | 15        | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 15        | 1.72%   |
| Intel Wireless 3160                                                         | 12        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 11        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 11        | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 10        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 9         | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                             | 9         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 9         | 1.03%   |
| Intel Centrino Wireless-N 2230                                              | 9         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                               | 9         | 1.03%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter               | 8         | 0.92%   |
| Intel Centrino Advanced-N 6235                                              | 8         | 0.92%   |
| Intel Centrino Advanced-N 6200                                              | 8         | 0.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 7         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 7         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 7         | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 7         | 0.8%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 7         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 6         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 6         | 0.69%   |
| Intel Wireless-AC 9260                                                      | 6         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 6         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                               | 6         | 0.69%   |
| Broadcom BCM4311 802.11b/g WLAN                                             | 6         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 5         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 5         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                              | 5         | 0.57%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                        | 5         | 0.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 5         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                    | 4         | 0.46%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                         | 4         | 0.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 4         | 0.46%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 4         | 0.46%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 4         | 0.46%   |
| Sierra Wireless EM7455                                                      | 3         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 3         | 0.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 3         | 0.34%   |
| Qualcomm Atheros AR9271 802.11n                                             | 3         | 0.34%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 3         | 0.34%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 3         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 316       | 41.42%  |
| Intel                            | 185       | 24.25%  |
| Samsung Electronics              | 83        | 10.88%  |
| Qualcomm Atheros                 | 66        | 8.65%   |
| Broadcom                         | 40        | 5.24%   |
| Marvell Technology Group         | 18        | 2.36%   |
| Lenovo                           | 16        | 2.1%    |
| Broadcom Limited                 | 14        | 1.83%   |
| DisplayLink                      | 7         | 0.92%   |
| ASIX Electronics                 | 4         | 0.52%   |
| Sierra Wireless                  | 3         | 0.39%   |
| Silicon Integrated Systems [SiS] | 2         | 0.26%   |
| Attansic Technology              | 2         | 0.26%   |
| Xiaomi                           | 1         | 0.13%   |
| VIA Technologies                 | 1         | 0.13%   |
| Spreadtrum Communications        | 1         | 0.13%   |
| ICS Advent                       | 1         | 0.13%   |
| Hewlett-Packard                  | 1         | 0.13%   |
| Foxconn / Hon Hai                | 1         | 0.13%   |
| D-Link                           | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 235       | 30.17%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 82        | 10.53%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 47        | 6.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 41        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 37        | 4.75%   |
| Intel Ethernet Connection (4) I219-LM                                          | 21        | 2.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 17        | 2.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 13        | 1.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.67%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.54%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 11        | 1.41%   |
| Intel Ethernet Connection I217-LM                                              | 11        | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 1.28%   |
| Intel Ethernet Connection (6) I219-V                                           | 10        | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 9         | 1.16%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 7         | 0.9%    |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.9%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 0.77%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.64%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 5         | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 5         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4         | 0.51%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 4         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.51%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                                         | 4         | 0.51%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 0.51%   |
| Sierra Wireless EM7345 4G LTE                                                  | 3         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.39%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.39%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 0.39%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.26%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2         | 0.26%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2         | 0.26%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 2         | 0.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.26%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.26%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.26%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.26%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.26%   |
| DisplayLink USB3.0 5K Graphic Docking                                          | 2         | 0.26%   |
| DisplayLink ThinkPad USB 3.0 Dock                                              | 2         | 0.26%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.26%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 831       | 52.86%  |
| Ethernet | 724       | 46.06%  |
| Modem    | 17        | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 653       | 61.49%  |
| Ethernet | 408       | 38.42%  |
| Modem    | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 594       | 70.21%  |
| 1     | 226       | 26.71%  |
| 0     | 16        | 1.89%   |
| 3     | 10        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 768       | 89.93%  |
| Yes  | 86        | 10.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 297       | 49.5%   |
| Qualcomm Atheros Communications | 52        | 8.67%   |
| Realtek Semiconductor           | 42        | 7%      |
| IMC Networks                    | 40        | 6.67%   |
| Broadcom                        | 40        | 6.67%   |
| Lite-On Technology              | 30        | 5%      |
| Foxconn / Hon Hai               | 26        | 4.33%   |
| Hewlett-Packard                 | 21        | 3.5%    |
| Dell                            | 14        | 2.33%   |
| ASUSTek Computer                | 12        | 2%      |
| Alps Electric                   | 5         | 0.83%   |
| Toshiba                         | 3         | 0.5%    |
| Ralink                          | 3         | 0.5%    |
| MediaTek                        | 3         | 0.5%    |
| Apple                           | 3         | 0.5%    |
| Realtek                         | 2         | 0.33%   |
| Ralink Technology               | 2         | 0.33%   |
| Cambridge Silicon Radio         | 2         | 0.33%   |
| Fujitsu Siemens Computers       | 1         | 0.17%   |
| Foxconn International           | 1         | 0.17%   |
| Askey Computer                  | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 129       | 21.5%   |
| Intel AX200 Bluetooth                                                               | 58        | 9.67%   |
| Intel AX201 Bluetooth                                                               | 43        | 7.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 38        | 6.33%   |
| Realtek Bluetooth Radio                                                             | 25        | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 19        | 3.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 15        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 2.33%   |
| IMC Networks Bluetooth Device                                                       | 12        | 2%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.67%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 9         | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.5%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.33%   |
| Dell DW375 Bluetooth Module                                                         | 8         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 6         | 1%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1%      |
| IMC Networks Wireless_Device                                                        | 6         | 1%      |
| IMC Networks Bluetooth Radio                                                        | 6         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1%      |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 6         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.83%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.67%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.67%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 4         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                                        | 3         | 0.5%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.5%    |
| Intel Bluetooth Device                                                              | 3         | 0.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.5%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 3         | 0.5%    |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.33%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.33%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.33%   |
| MediaTek BT                                                                         | 2         | 0.33%   |
| Lite-On Wireless_Device                                                             | 2         | 0.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.33%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.33%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.33%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.33%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 0.33%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.33%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.33%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.33%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.33%   |
| Broadcom Bluetooth                                                                  | 2         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.33%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.33%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 2         | 0.33%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.33%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 693       | 67.02%  |
| AMD                                  | 161       | 15.57%  |
| Nvidia                               | 85        | 8.22%   |
| Lenovo                               | 18        | 1.74%   |
| Realtek Semiconductor                | 14        | 1.35%   |
| C-Media Electronics                  | 13        | 1.26%   |
| Logitech                             | 5         | 0.48%   |
| Hewlett-Packard                      | 5         | 0.48%   |
| GN Netcom                            | 5         | 0.48%   |
| Creative Technology                  | 4         | 0.39%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.29%   |
| JMTek                                | 3         | 0.29%   |
| Plantronics                          | 2         | 0.19%   |
| Dell                                 | 2         | 0.19%   |
| BEHRINGER International              | 2         | 0.19%   |
| VIA Technologies                     | 1         | 0.1%    |
| Trust                                | 1         | 0.1%    |
| Toshiba                              | 1         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.1%    |
| Sennheiser Communications            | 1         | 0.1%    |
| Samson Technologies                  | 1         | 0.1%    |
| RODE Microphones                     | 1         | 0.1%    |
| Orbbec 3D Technology International   | 1         | 0.1%    |
| M-Audio                              | 1         | 0.1%    |
| Kingston Technology                  | 1         | 0.1%    |
| GYROCOM C&C                          | 1         | 0.1%    |
| Generalplus Technology               | 1         | 0.1%    |
| Focusrite-Novation                   | 1         | 0.1%    |
| ELMCU                                | 1         | 0.1%    |
| DigiTech                             | 1         | 0.1%    |
| Datelink Technology                  | 1         | 0.1%    |
| Conexant Systems                     | 1         | 0.1%    |
| AudioQuest                           | 1         | 0.1%    |
| Apple                                | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 130       | 10.57%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 91        | 7.4%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 77        | 6.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 5.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 52        | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 47        | 3.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 2.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 2.52%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 2.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 2.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 27        | 2.2%    |
| AMD FCH Azalia Controller                                                                         | 26        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.71%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 1.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.22%   |
| Realtek Semiconductor USB Audio                                                                   | 14        | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 12        | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.98%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 11        | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 0.81%   |
| AMD High Definition Audio Controller                                                              | 10        | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 9         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 0.65%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 0.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.57%   |
| Nvidia Audio device                                                                               | 6         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.41%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.33%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.33%   |
| Hewlett-Packard USB Audio                                                                         | 4         | 0.33%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.33%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 0.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 0.33%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.24%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.24%   |
| GN Netcom Jabra Link 370                                                                          | 3         | 0.24%   |
| C-Media Electronics CM108 Audio Controller                                                        | 3         | 0.24%   |
| C-Media Electronics Audio Adapter                                                                 | 3         | 0.24%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3         | 0.24%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 128       | 22.9%   |
| SK Hynix            | 117       | 20.93%  |
| Elpida              | 95        | 16.99%  |
| Micron Technology   | 70        | 12.52%  |
| Kingston            | 52        | 9.3%    |
| Unknown             | 32        | 5.72%   |
| Crucial             | 17        | 3.04%   |
| Ramaxel Technology  | 13        | 2.33%   |
| A-DATA Technology   | 9         | 1.61%   |
| Corsair             | 7         | 1.25%   |
| Unknown (ABCD)      | 5         | 0.89%   |
| Nanya Technology    | 4         | 0.72%   |
| Patriot             | 3         | 0.54%   |
| Transcend           | 2         | 0.36%   |
| Unknown (AB)        | 1         | 0.18%   |
| OnBoard             | 1         | 0.18%   |
| Nayna               | 1         | 0.18%   |
| Golden Empire       | 1         | 0.18%   |
| G.Skill             | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 83        | 14.24%  |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 7         | 1.2%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 6         | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 1.03%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 5         | 0.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.69%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 4         | 0.69%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.69%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.69%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s          | 4         | 0.69%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 4         | 0.69%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s            | 4         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.51%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 3         | 0.51%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.51%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.51%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.51%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.51%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 0.51%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 3         | 0.51%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 3         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 3         | 0.51%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 3         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 0.51%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 3         | 0.51%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 3         | 0.51%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                    | 3         | 0.51%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 3         | 0.51%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 2         | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.34%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 2         | 0.34%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 2         | 0.34%   |
| Unknown RAM Module 1024MB SODIMM DDR                                | 2         | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s        | 2         | 0.34%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                     | 2         | 0.34%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                    | 2         | 0.34%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s            | 2         | 0.34%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 2         | 0.34%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 2         | 0.34%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 209       | 43.82%  |
| DDR4    | 197       | 41.3%   |
| LPDDR4  | 24        | 5.03%   |
| DDR2    | 19        | 3.98%   |
| LPDDR3  | 16        | 3.35%   |
| SDRAM   | 8         | 1.68%   |
| DDR     | 3         | 0.63%   |
| Unknown | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 436       | 91.02%  |
| Row Of Chips | 32        | 6.68%   |
| Chip         | 9         | 1.88%   |
| DIMM         | 2         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 149       | 28.99%  |
| 2048  | 135       | 26.26%  |
| 4096  | 121       | 23.54%  |
| 16384 | 85        | 16.54%  |
| 1024  | 12        | 2.33%   |
| 32768 | 9         | 1.75%   |
| 3072  | 1         | 0.19%   |
| 512   | 1         | 0.19%   |
| 256   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1333    | 99        | 19.45%  |
| 2667    | 92        | 18.07%  |
| 1600    | 86        | 16.9%   |
| 3200    | 70        | 13.75%  |
| 2400    | 44        | 8.64%   |
| 2133    | 21        | 4.13%   |
| 1334    | 21        | 4.13%   |
| 1867    | 10        | 1.96%   |
| Unknown | 10        | 1.96%   |
| 4267    | 9         | 1.77%   |
| 1067    | 7         | 1.38%   |
| 3266    | 6         | 1.18%   |
| 800     | 6         | 1.18%   |
| 667     | 5         | 0.98%   |
| 4199    | 4         | 0.79%   |
| 975     | 4         | 0.79%   |
| 3733    | 3         | 0.59%   |
| 1066    | 3         | 0.59%   |
| 533     | 3         | 0.59%   |
| 4266    | 2         | 0.39%   |
| 2048    | 2         | 0.39%   |
| 1639    | 1         | 0.2%    |
| 1400    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Prolific Technology | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung M2070 Series          | 1         | 33.33%  |
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| Canon LBP3010/LBP3018/LBP3050 | 1         | 33.33%  |

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
| Chicony Electronics                    | 194       | 29.09%  |
| Realtek Semiconductor                  | 71        | 10.64%  |
| Acer                                   | 65        | 9.75%   |
| Microdia                               | 56        | 8.4%    |
| IMC Networks                           | 53        | 7.95%   |
| Sunplus Innovation Technology          | 43        | 6.45%   |
| Lite-On Technology                     | 34        | 5.1%    |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.9%    |
| Suyin                                  | 23        | 3.45%   |
| Quanta                                 | 23        | 3.45%   |
| Syntek                                 | 18        | 2.7%    |
| Alcor Micro                            | 10        | 1.5%    |
| Ricoh                                  | 9         | 1.35%   |
| Lenovo                                 | 7         | 1.05%   |
| Apple                                  | 5         | 0.75%   |
| Samsung Electronics                    | 4         | 0.6%    |
| Logitech                               | 4         | 0.6%    |
| Primax Electronics                     | 3         | 0.45%   |
| Z-Star Microelectronics                | 1         | 0.15%   |
| Unknown                                | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| Sonix Technology                       | 1         | 0.15%   |
| Silicon Motion                         | 1         | 0.15%   |
| Ruision                                | 1         | 0.15%   |
| Pixart Imaging                         | 1         | 0.15%   |
| Orbbec 3D Technology International     | 1         | 0.15%   |
| Microsoft                              | 1         | 0.15%   |
| Luxvisions Innotech Limited            | 1         | 0.15%   |
| KYE Systems (Mouse Systems)            | 1         | 0.15%   |
| Intel                                  | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| GEMBIRD                                | 1         | 0.15%   |
| eMPIA Technology                       | 1         | 0.15%   |
| Elecom                                 | 1         | 0.15%   |
| DJJHFA1BIF5CB0                         | 1         | 0.15%   |
| Creative Technology                    | 1         | 0.15%   |
| ALi                                    | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                                | 47        | 7%      |
| Microdia Integrated_Webcam_HD                                            | 28        | 4.17%   |
| Realtek Integrated_Webcam_HD                                             | 24        | 3.58%   |
| IMC Networks Integrated Camera                                           | 22        | 3.28%   |
| Chicony HD WebCam                                                        | 21        | 3.13%   |
| Chicony HP HD Camera                                                     | 18        | 2.68%   |
| Acer Lenovo EasyCamera                                                   | 16        | 2.38%   |
| Lite-On HP HD Camera                                                     | 14        | 2.09%   |
| Acer Integrated Camera                                                   | 14        | 2.09%   |
| Chicony Integrated Camera (1280x720@30)                                  | 11        | 1.64%   |
| Lite-On Integrated Camera                                                | 10        | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 10        | 1.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 9         | 1.34%   |
| Sunplus Integrated_Webcam_HD                                             | 8         | 1.19%   |
| Realtek Integrated Webcam HD                                             | 8         | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 8         | 1.19%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 1.04%   |
| Realtek USB Camera                                                       | 7         | 1.04%   |
| Quanta HP HD Camera                                                      | 7         | 1.04%   |
| Microdia Integrated Webcam                                               | 7         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 7         | 1.04%   |
| Acer SunplusIT Integrated Camera                                         | 7         | 1.04%   |
| Sunplus Laptop Integrated WebCam HD                                      | 6         | 0.89%   |
| Sunplus HD WebCam                                                        | 6         | 0.89%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 6         | 0.89%   |
| Lenovo Integrated Webcam                                                 | 6         | 0.89%   |
| Chicony Lenovo EasyCamera                                                | 6         | 0.89%   |
| Chicony HP HD Webcam                                                     | 6         | 0.89%   |
| Syntek Integrated Camera                                                 | 5         | 0.75%   |
| Sunplus ASUS USB2.0 Webcam                                               | 5         | 0.75%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 0.75%   |
| Quanta HD User Facing                                                    | 5         | 0.75%   |
| Chicony FJ Camera                                                        | 5         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 5         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 5         | 0.75%   |
| Alcor Micro USB 2.0 Camera                                               | 5         | 0.75%   |
| Acer Lenovo Integrated Webcam                                            | 5         | 0.75%   |
| Sunplus HP HD Webcam [Fixed]                                             | 4         | 0.6%    |
| Samsung Galaxy A5 (MTP)                                                  | 4         | 0.6%    |
| Ricoh Sony Vaio Integrated Webcam                                        | 4         | 0.6%    |
| Ricoh Laptop_Integrated_Webcam_FHD                                       | 4         | 0.6%    |
| Lite-On HP HD Webcam                                                     | 4         | 0.6%    |
| Chicony HP Truevision HD                                                 | 4         | 0.6%    |
| Chicony HP HD Webcam [Fixed]                                             | 4         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 4         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 4         | 0.6%    |
| Apple iPhone 5/5C/5S/6/SE                                                | 4         | 0.6%    |
| Acer EasyCamera                                                          | 4         | 0.6%    |
| Suyin Acer CrystalEye Webcam                                             | 3         | 0.45%   |
| Suyin 1.3M HD WebCam                                                     | 3         | 0.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 3         | 0.45%   |
| Sunplus Integrated_Webcam_FHD                                            | 3         | 0.45%   |
| Realtek Lenovo EasyCamera                                                | 3         | 0.45%   |
| Realtek HP Truevision HD                                                 | 3         | 0.45%   |
| Realtek Acer 640 x 480 laptop camera                                     | 3         | 0.45%   |
| Primax HP HD Webcam [Fixed]                                              | 3         | 0.45%   |
| Microdia Webcam                                                          | 3         | 0.45%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 3         | 0.45%   |
| Lite-On HP Wide Vision HD Camera                                         | 3         | 0.45%   |
| Chicony USB2.0 Camera                                                    | 3         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 72        | 34.29%  |
| Synaptics                  | 68        | 32.38%  |
| AuthenTec                  | 23        | 10.95%  |
| Shenzhen Goodix Technology | 22        | 10.48%  |
| Upek                       | 11        | 5.24%   |
| Elan Microelectronics      | 9         | 4.29%   |
| LighTuning Technology      | 4         | 1.9%    |
| Microsoft                  | 1         | 0.48%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 9.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 6.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 5.24%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.24%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 5.24%   |
| AuthenTec AES2810                                                          | 10        | 4.76%   |
| Unknown                                                                    | 9         | 4.29%   |
| Validity Sensors VFS491                                                    | 8         | 3.81%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.86%   |
| AuthenTec AES1600                                                          | 6         | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 2.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.9%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.9%    |
| Synaptics  WBDI                                                            | 3         | 1.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.43%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.95%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.95%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.48%   |
| Synaptics WBDI Device                                                      | 1         | 0.48%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.48%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 46        | 53.49%  |
| Alcor Micro               | 22        | 25.58%  |
| O2 Micro                  | 8         | 9.3%    |
| Lenovo                    | 5         | 5.81%   |
| SCM Microsystems          | 2         | 2.33%   |
| Upek                      | 1         | 1.16%   |
| Purism, SPC               | 1         | 1.16%   |
| Aladdin Knowledge Systems | 1         | 1.16%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 25.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 15.12%  |
| Broadcom 58200                                                               | 13        | 15.12%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 11.63%  |
| Broadcom 5880                                                                | 10        | 11.63%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 8.14%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.81%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.16%   |
| Purism, SPC Librem Key                                                       | 1         | 1.16%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.16%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.16%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 486       | 56.32%  |
| 1     | 286       | 33.14%  |
| 2     | 76        | 8.81%   |
| 3     | 13        | 1.51%   |
| 4     | 2         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 206       | 43.74%  |
| Graphics card            | 77        | 16.35%  |
| Chipcard                 | 76        | 16.14%  |
| Net/wireless             | 33        | 7.01%   |
| Multimedia controller    | 18        | 3.82%   |
| Storage                  | 16        | 3.4%    |
| Bluetooth                | 10        | 2.12%   |
| Communication controller | 9         | 1.91%   |
| Flash memory             | 5         | 1.06%   |
| Card reader              | 5         | 1.06%   |
| Net/ethernet             | 4         | 0.85%   |
| Modem                    | 4         | 0.85%   |
| Camera                   | 4         | 0.85%   |
| Sound                    | 3         | 0.64%   |
| Storage/ata              | 1         | 0.21%   |
