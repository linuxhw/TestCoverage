Linux in Colombia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 713

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| HP            | Laptop 14-cm1xxx            | [269af04437](https://linux-hardware.org/?probe=269af04437) | Jun 13, 2022 |
| Dell          | Vostro 3560                 | [170031499c](https://linux-hardware.org/?probe=170031499c) | Jun 12, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [5e7659e141](https://linux-hardware.org/?probe=5e7659e141) | Jun 11, 2022 |
| HP            | Laptop 14-cm1xxx            | [77e3d238c1](https://linux-hardware.org/?probe=77e3d238c1) | Jun 10, 2022 |
| Dell          | Vostro 3560                 | [0664b57ae1](https://linux-hardware.org/?probe=0664b57ae1) | Jun 09, 2022 |
| HP            | ProBook 440 G2              | [47ef7a04b9](https://linux-hardware.org/?probe=47ef7a04b9) | Jun 06, 2022 |
| HP            | Laptop 15-db0xxx            | [e5998cb70e](https://linux-hardware.org/?probe=e5998cb70e) | Jun 05, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [1368d41e8e](https://linux-hardware.org/?probe=1368d41e8e) | Jun 04, 2022 |
| Sony          | VGN-CS240T                  | [b25cbd1a6b](https://linux-hardware.org/?probe=b25cbd1a6b) | Jun 03, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| MSI           | GE60 2PE                    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| MSI           | GE60 2PE                    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| MSI           | GE60 2PE                    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [159819d677](https://linux-hardware.org/?probe=159819d677) | May 26, 2022 |
| Dell          | Latitude E5410              | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-411               | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Laptop 15-da2xxx            | [7dd1f5b528](https://linux-hardware.org/?probe=7dd1f5b528) | May 23, 2022 |
| HP            | ProBook 450 G1              | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| HP            | Laptop 14-dk1xxx            | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [46f7672c43](https://linux-hardware.org/?probe=46f7672c43) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [6f6a96c1cb](https://linux-hardware.org/?probe=6f6a96c1cb) | May 22, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Acer          | Aspire A314-22              | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Dell          | Inspiron 3459               | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| Lenovo        | V14-IGL 82C2                | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | K53Z                        | [0d68cb4fdd](https://linux-hardware.org/?probe=0d68cb4fdd) | May 04, 2022 |
| Toshiba       | Satellite L735              | [cb523c0933](https://linux-hardware.org/?probe=cb523c0933) | May 02, 2022 |
| Lenovo        | G450 2949                   | [8a97581747](https://linux-hardware.org/?probe=8a97581747) | May 02, 2022 |
| Dell          | Vostro 1510                 | [3b071a4b76](https://linux-hardware.org/?probe=3b071a4b76) | Apr 29, 2022 |
| Dell          | Vostro 1510                 | [483727ec47](https://linux-hardware.org/?probe=483727ec47) | Apr 29, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [8a8d7b120a](https://linux-hardware.org/?probe=8a8d7b120a) | Apr 24, 2022 |
| Acer          | Aspire A515-51              | [9f8f3a2eb5](https://linux-hardware.org/?probe=9f8f3a2eb5) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [738850499d](https://linux-hardware.org/?probe=738850499d) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [fd8cacef33](https://linux-hardware.org/?probe=fd8cacef33) | Apr 23, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| MSI           | Creator 15 A10SFS           | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Acer          | Aspire 4740                 | [d401412daa](https://linux-hardware.org/?probe=d401412daa) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 4291AN3       | [848b7902d8](https://linux-hardware.org/?probe=848b7902d8) | Apr 10, 2022 |
| ASUSTek       | X541SA                      | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Toshiba       | Satellite L735              | [b7873249a4](https://linux-hardware.org/?probe=b7873249a4) | Apr 07, 2022 |
| Toshiba       | Satellite P755              | [b3601d9299](https://linux-hardware.org/?probe=b3601d9299) | Apr 05, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [38036fe92b](https://linux-hardware.org/?probe=38036fe92b) | Apr 05, 2022 |
| HP            | ProBook 430 G3              | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Dell          | Vostro 1500                 | [dc0e34cb10](https://linux-hardware.org/?probe=dc0e34cb10) | Mar 26, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| Acer          | Aspire 4738                 | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HP            | Pavilion 10 TS              | [e149d7ed93](https://linux-hardware.org/?probe=e149d7ed93) | Mar 23, 2022 |
| Dell          | Latitude E5420              | [b15d85a6e9](https://linux-hardware.org/?probe=b15d85a6e9) | Mar 22, 2022 |
| Toshiba       | Satellite P755              | [f8d12d8ab9](https://linux-hardware.org/?probe=f8d12d8ab9) | Mar 22, 2022 |
| HP            | 550                         | [91f443bb06](https://linux-hardware.org/?probe=91f443bb06) | Mar 18, 2022 |
| HP            | 550                         | [8acaec9ff1](https://linux-hardware.org/?probe=8acaec9ff1) | Mar 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8c94df31c1](https://linux-hardware.org/?probe=8c94df31c1) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T430 2347AF3       | [8fa4355200](https://linux-hardware.org/?probe=8fa4355200) | Mar 08, 2022 |
| MSI           | Alpha 17 B5EEK              | [3298d34369](https://linux-hardware.org/?probe=3298d34369) | Mar 07, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [b1a7b4593a](https://linux-hardware.org/?probe=b1a7b4593a) | Mar 07, 2022 |
| MSI           | Alpha 17 B5EEK              | [1e54d4f165](https://linux-hardware.org/?probe=1e54d4f165) | Mar 06, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [f10cf42ebf](https://linux-hardware.org/?probe=f10cf42ebf) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [b887ed3aa2](https://linux-hardware.org/?probe=b887ed3aa2) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [07cade8a02](https://linux-hardware.org/?probe=07cade8a02) | Mar 06, 2022 |
| HP            | 245 G3                      | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| ASUSTek       | K43E                        | [484fd9a41a](https://linux-hardware.org/?probe=484fd9a41a) | Feb 27, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| ASUSTek       | UX305FA                     | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Framework     | Laptop                      | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| HP            | 240 G7                      | [48bc3b139b](https://linux-hardware.org/?probe=48bc3b139b) | Feb 03, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| MSI           | GF75 Thin 10SER             | [2e94cc2b4c](https://linux-hardware.org/?probe=2e94cc2b4c) | Jan 22, 2022 |
| MSI           | GE72 2QE                    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| Acer          | Aspire V5-121               | [fb3b510c66](https://linux-hardware.org/?probe=fb3b510c66) | Jan 06, 2022 |
| Acer          | Aspire V5-121               | [be57155d1f](https://linux-hardware.org/?probe=be57155d1f) | Jan 06, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Dell          | XPS 13 7390                 | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [c9cffe7310](https://linux-hardware.org/?probe=c9cffe7310) | Dec 24, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| HUAWEI        | BOHB-WAX9                   | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| HP            | ProBook 6450b               | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| HP            | 14                          | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| HP            | Compaq CQ45                 | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| HP            | ProBook 440 G1              | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| ASUSTek       | X441NA                      | [da21de67fb](https://linux-hardware.org/?probe=da21de67fb) | Nov 18, 2021 |
| HP            | Pavilion dv9700             | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| ASUSTek       | X550ZE                      | [b98c646c47](https://linux-hardware.org/?probe=b98c646c47) | Nov 16, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [18152a84af](https://linux-hardware.org/?probe=18152a84af) | Nov 13, 2021 |
| Lenovo        | ThinkPad T495 20NKS0QN0V    | [ceab02dda1](https://linux-hardware.org/?probe=ceab02dda1) | Nov 07, 2021 |
| Dell          | Latitude 7490               | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| HP            | Pavilion dv4                | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| ASUSTek       | X550ZE                      | [dcd63f8987](https://linux-hardware.org/?probe=dcd63f8987) | Oct 31, 2021 |
| Dell          | Inspiron 5515               | [809fe8da11](https://linux-hardware.org/?probe=809fe8da11) | Oct 30, 2021 |
| Acer          | Nitro AN515-52              | [7f70de1771](https://linux-hardware.org/?probe=7f70de1771) | Oct 26, 2021 |
| Acer          | Nitro AN515-52              | [6777af6e6a](https://linux-hardware.org/?probe=6777af6e6a) | Oct 26, 2021 |
| Lenovo        | G40-45 80E1                 | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| Acer          | Aspire E1-522               | [dc7a02c862](https://linux-hardware.org/?probe=dc7a02c862) | Oct 15, 2021 |
| HP            | 240 G3                      | [a083502110](https://linux-hardware.org/?probe=a083502110) | Oct 11, 2021 |
| HP            | 240 G3                      | [1772f88ed6](https://linux-hardware.org/?probe=1772f88ed6) | Oct 11, 2021 |
| Toshiba       | Satellite C45-A             | [ee28fa6dfb](https://linux-hardware.org/?probe=ee28fa6dfb) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| ASUSTek       | K53SD                       | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| Dell          | XPS 15 9550                 | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| HP            | ProBook 450 G1              | [e6fbfad3de](https://linux-hardware.org/?probe=e6fbfad3de) | Sep 16, 2021 |
| Gateway       | NV47H                       | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Dell          | Latitude E7270              | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2300be2f19](https://linux-hardware.org/?probe=2300be2f19) | Sep 13, 2021 |
| HP            | 2000                        | [7d8cd719a2](https://linux-hardware.org/?probe=7d8cd719a2) | Sep 09, 2021 |
| Dell          | Inspiron 1110               | [890d9d9d24](https://linux-hardware.org/?probe=890d9d9d24) | Sep 08, 2021 |
| Dell          | Inspiron 1110               | [e299761316](https://linux-hardware.org/?probe=e299761316) | Sep 08, 2021 |
| ASUSTek       | X555QA                      | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| ASUSTek       | X555QG                      | [badf1b0736](https://linux-hardware.org/?probe=badf1b0736) | Aug 30, 2021 |
| Unknown       | Unknown                     | [33a8107059](https://linux-hardware.org/?probe=33a8107059) | Aug 28, 2021 |
| Unknown       | Unknown                     | [fe2ba9da7c](https://linux-hardware.org/?probe=fe2ba9da7c) | Aug 28, 2021 |
| HP            | EliteBook 840 G6            | [08c766b957](https://linux-hardware.org/?probe=08c766b957) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| HP            | 14                          | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Timi          | A35S                        | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Dell          | Precision 3551              | [aeeeb63990](https://linux-hardware.org/?probe=aeeeb63990) | Aug 10, 2021 |
| Dell          | Latitude D630               | [ceb9ca591f](https://linux-hardware.org/?probe=ceb9ca591f) | Aug 05, 2021 |
| Dell          | XPS 13 9310                 | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| MSI           | MS-16GF                     | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| ASUSTek       | K46CM                       | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 4293B43       | [7accb85da9](https://linux-hardware.org/?probe=7accb85da9) | Jul 30, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| HP            | Presario CQ42               | [fa65f13c3b](https://linux-hardware.org/?probe=fa65f13c3b) | Jul 23, 2021 |
| Dell          | Inspiron 3493               | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| HP            | Laptop 15-db0xxx            | [9182648939](https://linux-hardware.org/?probe=9182648939) | Jul 19, 2021 |
| Acer          | TravelMate P2410-G2-M       | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| ASUSTek       | K401UQ                      | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | G73Jw                       | [b1d6609434](https://linux-hardware.org/?probe=b1d6609434) | Jul 03, 2021 |
| Lenovo        | ThinkPad W510 4391BY8       | [12d0ff5c27](https://linux-hardware.org/?probe=12d0ff5c27) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [bc19b4b3bf](https://linux-hardware.org/?probe=bc19b4b3bf) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c1442501a0](https://linux-hardware.org/?probe=c1442501a0) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude 7414               | [5557aada9a](https://linux-hardware.org/?probe=5557aada9a) | Jun 28, 2021 |
| ASUSTek       | X441UA                      | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| HP            | Pavilion 10 TS              | [1759d8d1f8](https://linux-hardware.org/?probe=1759d8d1f8) | Jun 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Acer          | A315-41G                    | [c3b9603724](https://linux-hardware.org/?probe=c3b9603724) | Jun 15, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Acer          | Aspire E5-471               | [f15409e7cc](https://linux-hardware.org/?probe=f15409e7cc) | Jun 10, 2021 |
| Dell          | Vostro 3400                 | [2e841a4dc4](https://linux-hardware.org/?probe=2e841a4dc4) | Jun 09, 2021 |
| HP            | ProBook 440 G3              | [a5547e4146](https://linux-hardware.org/?probe=a5547e4146) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [d15f22008c](https://linux-hardware.org/?probe=d15f22008c) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [82dff2688d](https://linux-hardware.org/?probe=82dff2688d) | Jun 07, 2021 |
| HP            | Pavilion 10 TS              | [ad461cbf3e](https://linux-hardware.org/?probe=ad461cbf3e) | Jun 07, 2021 |
| HP            | 245 G6                      | [a3594ab925](https://linux-hardware.org/?probe=a3594ab925) | Jun 03, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Acer          | Aspire 4750                 | [499479904d](https://linux-hardware.org/?probe=499479904d) | May 27, 2021 |
| ASUSTek       | UX430UAR                    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| HP            | Notebook                    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| Toshiba       | Satellite C850-B797         | [834d15c08c](https://linux-hardware.org/?probe=834d15c08c) | May 16, 2021 |
| Toshiba       | Satellite C850-B797         | [0ece4b9e9e](https://linux-hardware.org/?probe=0ece4b9e9e) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Apple         | MacBookAir7,2               | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| Toshiba       | Satellite C850-B797         | [1355c6e459](https://linux-hardware.org/?probe=1355c6e459) | May 13, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| Dell          | Inspiron 3480               | [5ad427cffb](https://linux-hardware.org/?probe=5ad427cffb) | May 04, 2021 |
| Dell          | XPS 15 9550                 | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| Notebook      | N150CU                      | [e62762a731](https://linux-hardware.org/?probe=e62762a731) | Apr 14, 2021 |
| Lenovo        | ThinkPad X260 20F5A0HB00    | [9163ce31dc](https://linux-hardware.org/?probe=9163ce31dc) | Apr 14, 2021 |
| Lenovo        | G40-45 80E1                 | [1263e938c8](https://linux-hardware.org/?probe=1263e938c8) | Apr 13, 2021 |
| Lenovo        | G40-45 80E1                 | [5fada7c64a](https://linux-hardware.org/?probe=5fada7c64a) | Apr 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Lenovo        | V330-14IKB 81B0             | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Lenovo        | ThinkPad X230 2325BG3       | [90f6078b02](https://linux-hardware.org/?probe=90f6078b02) | Apr 04, 2021 |
| ASUSTek       | X555DG                      | [334a8d4184](https://linux-hardware.org/?probe=334a8d4184) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2c67d604ff](https://linux-hardware.org/?probe=2c67d604ff) | Mar 28, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| ASUSTek       | N53SM                       | [87e7b3b248](https://linux-hardware.org/?probe=87e7b3b248) | Mar 22, 2021 |
| Toshiba       | Satellite U505              | [1d422767e1](https://linux-hardware.org/?probe=1d422767e1) | Mar 20, 2021 |
| Toshiba       | Satellite U505              | [ccb5c756ee](https://linux-hardware.org/?probe=ccb5c756ee) | Mar 20, 2021 |
| Acer          | AOD255                      | [2e5b228a04](https://linux-hardware.org/?probe=2e5b228a04) | Mar 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [843d061b78](https://linux-hardware.org/?probe=843d061b78) | Mar 15, 2021 |
| HP            | Laptop 14-cm1xxx            | [87cabd058e](https://linux-hardware.org/?probe=87cabd058e) | Mar 13, 2021 |
| HP            | 245 G7 Notebook PC          | [8cb18a4f6c](https://linux-hardware.org/?probe=8cb18a4f6c) | Mar 11, 2021 |
| HP            | 245 G7 Notebook PC          | [a6e9e8ea5e](https://linux-hardware.org/?probe=a6e9e8ea5e) | Mar 11, 2021 |
| Acer          | AOD255                      | [f3a5b4b0e4](https://linux-hardware.org/?probe=f3a5b4b0e4) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d9708c63f5](https://linux-hardware.org/?probe=d9708c63f5) | Mar 04, 2021 |
| Dell          | Precision 3551              | [d75a598209](https://linux-hardware.org/?probe=d75a598209) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [bc879be58b](https://linux-hardware.org/?probe=bc879be58b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [27b7f94851](https://linux-hardware.org/?probe=27b7f94851) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [935f9c5571](https://linux-hardware.org/?probe=935f9c5571) | Mar 03, 2021 |
| HP            | Pavilion 10 TS              | [5998c38555](https://linux-hardware.org/?probe=5998c38555) | Feb 26, 2021 |
| Dell          | Latitude E6220              | [1c0ab9fab1](https://linux-hardware.org/?probe=1c0ab9fab1) | Feb 23, 2021 |
| Dell          | Latitude E6220              | [19e1a4a1d6](https://linux-hardware.org/?probe=19e1a4a1d6) | Feb 23, 2021 |
| Dell          | Inspiron 3493               | [684245175e](https://linux-hardware.org/?probe=684245175e) | Feb 20, 2021 |
| Acer          | TravelMate P449-G2-M        | [7581904d41](https://linux-hardware.org/?probe=7581904d41) | Feb 20, 2021 |
| Apple         | MacBookPro15,1              | [a148b9034a](https://linux-hardware.org/?probe=a148b9034a) | Feb 19, 2021 |
| HP            | ProBook 440 G7              | [f6830c6ac2](https://linux-hardware.org/?probe=f6830c6ac2) | Feb 18, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [ecddf05f3e](https://linux-hardware.org/?probe=ecddf05f3e) | Feb 16, 2021 |
| BAKED         | P7xxDM2(-G)                 | [824169b9f7](https://linux-hardware.org/?probe=824169b9f7) | Feb 16, 2021 |
| HP            | ProBook 440 G2              | [8be5048c51](https://linux-hardware.org/?probe=8be5048c51) | Feb 15, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [8da12e7518](https://linux-hardware.org/?probe=8da12e7518) | Feb 14, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [5e5731f2b0](https://linux-hardware.org/?probe=5e5731f2b0) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [90847dec81](https://linux-hardware.org/?probe=90847dec81) | Feb 12, 2021 |
| HP            | Notebook                    | [5224b13971](https://linux-hardware.org/?probe=5224b13971) | Feb 08, 2021 |
| Dell          | Inspiron 7586               | [7e6463f517](https://linux-hardware.org/?probe=7e6463f517) | Feb 05, 2021 |
| ASUSTek       | X505BA                      | [8059f98337](https://linux-hardware.org/?probe=8059f98337) | Feb 03, 2021 |
| HP            | Presario CQ43               | [13eb02bc61](https://linux-hardware.org/?probe=13eb02bc61) | Feb 02, 2021 |
| HP            | Presario CQ43               | [a6d1b8df1e](https://linux-hardware.org/?probe=a6d1b8df1e) | Feb 02, 2021 |
| Notebook      | N150CU                      | [7753afd04f](https://linux-hardware.org/?probe=7753afd04f) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| Acer          | Aspire E5-575G              | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| HP            | Laptop 15-db0xxx            | [ab91702ac3](https://linux-hardware.org/?probe=ab91702ac3) | Jan 26, 2021 |
| GreatWall     | K41                         | [ddf99d904e](https://linux-hardware.org/?probe=ddf99d904e) | Jan 25, 2021 |
| ASUSTek       | X555LN                      | [e649cc1304](https://linux-hardware.org/?probe=e649cc1304) | Jan 24, 2021 |
| ASUSTek       | X441UVK                     | [c73eaa8a8f](https://linux-hardware.org/?probe=c73eaa8a8f) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ca25f14fb](https://linux-hardware.org/?probe=0ca25f14fb) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [419800f72d](https://linux-hardware.org/?probe=419800f72d) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [844d185dae](https://linux-hardware.org/?probe=844d185dae) | Jan 21, 2021 |
| Dell          | XPS 15 9550                 | [91a85ad436](https://linux-hardware.org/?probe=91a85ad436) | Jan 20, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [62de1cd91f](https://linux-hardware.org/?probe=62de1cd91f) | Jan 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [edcaecc674](https://linux-hardware.org/?probe=edcaecc674) | Jan 14, 2021 |
| ASUSTek       | K46CM                       | [e5d77ec648](https://linux-hardware.org/?probe=e5d77ec648) | Jan 14, 2021 |
| Dell          | Precision 3551              | [c6524a92a4](https://linux-hardware.org/?probe=c6524a92a4) | Jan 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6d637febe2](https://linux-hardware.org/?probe=6d637febe2) | Jan 10, 2021 |
| ASUSTek       | X455LJ                      | [05b3190864](https://linux-hardware.org/?probe=05b3190864) | Jan 08, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [0d58fd33df](https://linux-hardware.org/?probe=0d58fd33df) | Jan 07, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [d1947d8c18](https://linux-hardware.org/?probe=d1947d8c18) | Jan 07, 2021 |
| Dell          | System XPS L502X            | [6548d3214b](https://linux-hardware.org/?probe=6548d3214b) | Jan 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4e9f49422a](https://linux-hardware.org/?probe=4e9f49422a) | Jan 04, 2021 |
| BAKED         | P7xxDM2(-G)                 | [c4206ecc26](https://linux-hardware.org/?probe=c4206ecc26) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [f995163ff4](https://linux-hardware.org/?probe=f995163ff4) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [2758658d90](https://linux-hardware.org/?probe=2758658d90) | Jan 04, 2021 |
| ASUSTek       | X555QG                      | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6b7c6db0c5](https://linux-hardware.org/?probe=6b7c6db0c5) | Dec 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [10b0b04256](https://linux-hardware.org/?probe=10b0b04256) | Dec 30, 2020 |
| Notebook      | NB50TJ1_TK1                 | [10d64eecc5](https://linux-hardware.org/?probe=10d64eecc5) | Dec 30, 2020 |
| HP            | Laptop 14-cm1xxx            | [e850bec31a](https://linux-hardware.org/?probe=e850bec31a) | Dec 29, 2020 |
| Acer          | Aspire E5-575G              | [3c4ea54770](https://linux-hardware.org/?probe=3c4ea54770) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d61f2aa238](https://linux-hardware.org/?probe=d61f2aa238) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [bca2708dcd](https://linux-hardware.org/?probe=bca2708dcd) | Dec 25, 2020 |
| ASUSTek       | X450CP                      | [1d2d82e5ee](https://linux-hardware.org/?probe=1d2d82e5ee) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | [e395d72cbb](https://linux-hardware.org/?probe=e395d72cbb) | Dec 21, 2020 |
| HP            | Pavilion dv4                | [0f86ea7cab](https://linux-hardware.org/?probe=0f86ea7cab) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Notebook      | NB50TJ1_TK1                 | [c23ae5c475](https://linux-hardware.org/?probe=c23ae5c475) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [2475252354](https://linux-hardware.org/?probe=2475252354) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [a08f4cf4e5](https://linux-hardware.org/?probe=a08f4cf4e5) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| HP            | Laptop 15-da0xxx            | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [dd0d449586](https://linux-hardware.org/?probe=dd0d449586) | Dec 14, 2020 |
| Notebook      | NB50TJ1_TK1                 | [246d659f60](https://linux-hardware.org/?probe=246d659f60) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| Lenovo        | Yoga 700-11ISK 80QE         | [1a353b9226](https://linux-hardware.org/?probe=1a353b9226) | Dec 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3962cbfb58](https://linux-hardware.org/?probe=3962cbfb58) | Dec 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d5a1c07e6](https://linux-hardware.org/?probe=3d5a1c07e6) | Dec 05, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [02fb63a36f](https://linux-hardware.org/?probe=02fb63a36f) | Dec 04, 2020 |
| ASUSTek       | X555QG                      | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| ASUSTek       | K46CM                       | [490bae951e](https://linux-hardware.org/?probe=490bae951e) | Dec 01, 2020 |
| Lenovo        | G470 20078                  | [b0564c0e50](https://linux-hardware.org/?probe=b0564c0e50) | Dec 01, 2020 |
| ASUSTek       | X555QG                      | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | IdeaPad U510 20191          | [895b641220](https://linux-hardware.org/?probe=895b641220) | Nov 30, 2020 |
| MSI           | PS63 Modern 8RC             | [0a4b399149](https://linux-hardware.org/?probe=0a4b399149) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [0c9f7ea289](https://linux-hardware.org/?probe=0c9f7ea289) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [a5f5b59788](https://linux-hardware.org/?probe=a5f5b59788) | Nov 26, 2020 |
| HP            | Laptop 15-db0xxx            | [503b8f9701](https://linux-hardware.org/?probe=503b8f9701) | Nov 25, 2020 |
| ASUSTek       | X441NA                      | [61a5d6947b](https://linux-hardware.org/?probe=61a5d6947b) | Nov 25, 2020 |
| Unknown       | Unknown                     | [73dc6959d6](https://linux-hardware.org/?probe=73dc6959d6) | Nov 23, 2020 |
| Unknown       | Unknown                     | [b0c0ef90cd](https://linux-hardware.org/?probe=b0c0ef90cd) | Nov 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a997f8c186](https://linux-hardware.org/?probe=a997f8c186) | Nov 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e24dba10a2](https://linux-hardware.org/?probe=e24dba10a2) | Nov 22, 2020 |
| ASUSTek       | X441NA                      | [e301cabf95](https://linux-hardware.org/?probe=e301cabf95) | Nov 21, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5021095fd1](https://linux-hardware.org/?probe=5021095fd1) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [e5e8cfd574](https://linux-hardware.org/?probe=e5e8cfd574) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [026fdce11f](https://linux-hardware.org/?probe=026fdce11f) | Nov 13, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [b3752255e5](https://linux-hardware.org/?probe=b3752255e5) | Nov 13, 2020 |
| HP            | ProBook 6450b               | [74c2b345b8](https://linux-hardware.org/?probe=74c2b345b8) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [5efbf0cf43](https://linux-hardware.org/?probe=5efbf0cf43) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [3f9b54f16c](https://linux-hardware.org/?probe=3f9b54f16c) | Nov 05, 2020 |
| Lenovo        | G450 2949                   | [f9bb66b7a2](https://linux-hardware.org/?probe=f9bb66b7a2) | Nov 03, 2020 |
| ASUSTek       | X411UQ                      | [f3e110826b](https://linux-hardware.org/?probe=f3e110826b) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | [9786cce501](https://linux-hardware.org/?probe=9786cce501) | Nov 01, 2020 |
| Lenovo        | Z50-70 20354                | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| Dell          | XPS 15 9550                 | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | [dcd8f2aa99](https://linux-hardware.org/?probe=dcd8f2aa99) | Oct 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cafb41376f](https://linux-hardware.org/?probe=cafb41376f) | Oct 26, 2020 |
| HP            | Laptop 15-db0xxx            | [fa89c085cf](https://linux-hardware.org/?probe=fa89c085cf) | Oct 25, 2020 |
| Acer          | Aspire 4730Z                | [7157a6069b](https://linux-hardware.org/?probe=7157a6069b) | Oct 21, 2020 |
| Acer          | Aspire 4730Z                | [fb18c13ac7](https://linux-hardware.org/?probe=fb18c13ac7) | Oct 21, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [89c3fe76c0](https://linux-hardware.org/?probe=89c3fe76c0) | Oct 18, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [0a4d06561e](https://linux-hardware.org/?probe=0a4d06561e) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [8fb2a0621d](https://linux-hardware.org/?probe=8fb2a0621d) | Oct 12, 2020 |
| Lenovo        | G40-45 80E1                 | [eefc7c92b2](https://linux-hardware.org/?probe=eefc7c92b2) | Oct 11, 2020 |
| Dell          | Latitude E7270              | [cff6ba0c00](https://linux-hardware.org/?probe=cff6ba0c00) | Oct 11, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [e04a055ab8](https://linux-hardware.org/?probe=e04a055ab8) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [c376c39381](https://linux-hardware.org/?probe=c376c39381) | Oct 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4e2c32a972](https://linux-hardware.org/?probe=4e2c32a972) | Oct 07, 2020 |
| Dell          | Inspiron 3480               | [243905bcf2](https://linux-hardware.org/?probe=243905bcf2) | Oct 06, 2020 |
| HP            | Laptop 15-db0xxx            | [eaeba54519](https://linux-hardware.org/?probe=eaeba54519) | Oct 05, 2020 |
| MPS Mayori... | COIN ST800EDU               | [11e4ae4bfe](https://linux-hardware.org/?probe=11e4ae4bfe) | Oct 03, 2020 |
| MPS Mayori... | COIN ST800EDU               | [38a7d9f974](https://linux-hardware.org/?probe=38a7d9f974) | Oct 03, 2020 |
| HP            | Laptop 15-db0xxx            | [eb0e17a039](https://linux-hardware.org/?probe=eb0e17a039) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | [e0afc29d83](https://linux-hardware.org/?probe=e0afc29d83) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4ff7a5528c](https://linux-hardware.org/?probe=4ff7a5528c) | Sep 29, 2020 |
| HP            | EliteBook 8440p             | [21ecdf1804](https://linux-hardware.org/?probe=21ecdf1804) | Sep 28, 2020 |
| HP            | Pavilion 10 TS              | [393e09d070](https://linux-hardware.org/?probe=393e09d070) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7ec7b7dbb0](https://linux-hardware.org/?probe=7ec7b7dbb0) | Sep 27, 2020 |
| Dell          | Inspiron 3493               | [be76b68bff](https://linux-hardware.org/?probe=be76b68bff) | Sep 25, 2020 |
| HP            | Notebook                    | [97099ba5b3](https://linux-hardware.org/?probe=97099ba5b3) | Sep 23, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [4b3f7c31cc](https://linux-hardware.org/?probe=4b3f7c31cc) | Sep 21, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [bf2a498d90](https://linux-hardware.org/?probe=bf2a498d90) | Sep 21, 2020 |
| ASUSTek       | X441UVK                     | [4be17c95ab](https://linux-hardware.org/?probe=4be17c95ab) | Sep 18, 2020 |
| Dell          | Latitude E7270              | [76c31048e9](https://linux-hardware.org/?probe=76c31048e9) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| Dell          | Studio 1558                 | [bfa6ee72ad](https://linux-hardware.org/?probe=bfa6ee72ad) | Sep 11, 2020 |
| Dell          | Studio 1558                 | [09283ede94](https://linux-hardware.org/?probe=09283ede94) | Sep 11, 2020 |
| Acer          | TravelMate 5744             | [cd7e3646ff](https://linux-hardware.org/?probe=cd7e3646ff) | Sep 09, 2020 |
| HP            | EliteBook 840 G5            | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Dell          | Inspiron N5040              | [7d81a97615](https://linux-hardware.org/?probe=7d81a97615) | Sep 07, 2020 |
| Dell          | Inspiron 5570               | [c184b08cc3](https://linux-hardware.org/?probe=c184b08cc3) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| Acer          | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| Dell          | Inspiron 3493               | [11adb16243](https://linux-hardware.org/?probe=11adb16243) | Sep 03, 2020 |
| ASUSTek       | X442UA                      | [cad592ae29](https://linux-hardware.org/?probe=cad592ae29) | Aug 31, 2020 |
| ASUSTek       | X442UA                      | [7697815bb5](https://linux-hardware.org/?probe=7697815bb5) | Aug 31, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Samsung       | R430/R480/R440              | [c37003dbfc](https://linux-hardware.org/?probe=c37003dbfc) | Aug 30, 2020 |
| Lenovo        | IdeaPad Z480                | [c1fe24f51b](https://linux-hardware.org/?probe=c1fe24f51b) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [eb0990afbe](https://linux-hardware.org/?probe=eb0990afbe) | Aug 23, 2020 |
| Lenovo        | IdeaPad Z480                | [f43e5244bc](https://linux-hardware.org/?probe=f43e5244bc) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [27987ebfb1](https://linux-hardware.org/?probe=27987ebfb1) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2151fb7ccb](https://linux-hardware.org/?probe=2151fb7ccb) | Aug 15, 2020 |
| Acer          | AOD255                      | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | Laptop 14-cm1xxx            | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c958c50dad](https://linux-hardware.org/?probe=c958c50dad) | Aug 07, 2020 |
| HP            | ENVY 15                     | [d2fab519a5](https://linux-hardware.org/?probe=d2fab519a5) | Aug 04, 2020 |
| Toshiba       | Satellite L645              | [2f81e753a6](https://linux-hardware.org/?probe=2f81e753a6) | Jul 31, 2020 |
| HP            | 245 G6                      | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [1b4b43f382](https://linux-hardware.org/?probe=1b4b43f382) | Jul 29, 2020 |
| HP            | G42                         | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| HP            | Laptop 15-db0xxx            | [0928c9c524](https://linux-hardware.org/?probe=0928c9c524) | Jul 27, 2020 |
| HP            | Compaq CQ45                 | [26022f582b](https://linux-hardware.org/?probe=26022f582b) | Jul 26, 2020 |
| HP            | Compaq CQ45                 | [74cad2f13e](https://linux-hardware.org/?probe=74cad2f13e) | Jul 26, 2020 |
| HP            | Laptop 15-db0xxx            | [75928e5332](https://linux-hardware.org/?probe=75928e5332) | Jul 25, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b4f52ba1be](https://linux-hardware.org/?probe=b4f52ba1be) | Jul 25, 2020 |
| Lenovo        | IdeaPad Z480                | [17ecc94bc0](https://linux-hardware.org/?probe=17ecc94bc0) | Jul 24, 2020 |
| Toshiba       | Satellite M505              | [518faca568](https://linux-hardware.org/?probe=518faca568) | Jul 21, 2020 |
| Toshiba       | Satellite S75-A             | [a2fc5378af](https://linux-hardware.org/?probe=a2fc5378af) | Jul 21, 2020 |
| Toshiba       | Satellite M505              | [64f79b1c45](https://linux-hardware.org/?probe=64f79b1c45) | Jul 21, 2020 |
| Dell          | Latitude E7270              | [3240f0ae94](https://linux-hardware.org/?probe=3240f0ae94) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1839ba41d3](https://linux-hardware.org/?probe=1839ba41d3) | Jul 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f179e69271](https://linux-hardware.org/?probe=f179e69271) | Jul 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [543185b30a](https://linux-hardware.org/?probe=543185b30a) | Jul 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e66cd74e47](https://linux-hardware.org/?probe=e66cd74e47) | Jul 18, 2020 |
| ASUSTek       | X456UA                      | [0bc503ae0b](https://linux-hardware.org/?probe=0bc503ae0b) | Jul 16, 2020 |
| HP            | Laptop 15-db0xxx            | [8a858d88d0](https://linux-hardware.org/?probe=8a858d88d0) | Jul 15, 2020 |
| HP            | Laptop 15-db0xxx            | [260563b336](https://linux-hardware.org/?probe=260563b336) | Jul 15, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| ASUSTek       | X456UA                      | [6b61996456](https://linux-hardware.org/?probe=6b61996456) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [858cd73913](https://linux-hardware.org/?probe=858cd73913) | Jul 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [fc5d45e94a](https://linux-hardware.org/?probe=fc5d45e94a) | Jul 10, 2020 |
| HP            | Compaq 6730s                | [e128a9542c](https://linux-hardware.org/?probe=e128a9542c) | Jul 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dd5e302721](https://linux-hardware.org/?probe=dd5e302721) | Jul 03, 2020 |
| ASUSTek       | K46CM                       | [5260584205](https://linux-hardware.org/?probe=5260584205) | Jun 30, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [0999108dfb](https://linux-hardware.org/?probe=0999108dfb) | Jun 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a54dfa2b8b](https://linux-hardware.org/?probe=a54dfa2b8b) | Jun 27, 2020 |
| Dell          | XPS 15 9550                 | [fae71e18b2](https://linux-hardware.org/?probe=fae71e18b2) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [7e4c8ea12c](https://linux-hardware.org/?probe=7e4c8ea12c) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [5e921d68ff](https://linux-hardware.org/?probe=5e921d68ff) | Jun 25, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [7e8026e797](https://linux-hardware.org/?probe=7e8026e797) | Jun 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | [29f9ac42d8](https://linux-hardware.org/?probe=29f9ac42d8) | Jun 21, 2020 |
| Unknown       | Unknown                     | [73cda410f2](https://linux-hardware.org/?probe=73cda410f2) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7d7f2f4f3](https://linux-hardware.org/?probe=a7d7f2f4f3) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d194146ff8](https://linux-hardware.org/?probe=d194146ff8) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5b4fdab686](https://linux-hardware.org/?probe=5b4fdab686) | Jun 18, 2020 |
| Dell          | Inspiron N4010              | [a1ae232e58](https://linux-hardware.org/?probe=a1ae232e58) | Jun 13, 2020 |
| Acer          | Aspire 5532                 | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Gateway       | M-6319                      | [5b3e8b9ef1](https://linux-hardware.org/?probe=5b3e8b9ef1) | Jun 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [52c8b6876e](https://linux-hardware.org/?probe=52c8b6876e) | Jun 08, 2020 |
| ASUSTek       | T100TA                      | [aad1de590c](https://linux-hardware.org/?probe=aad1de590c) | Jun 07, 2020 |
| Acer          | Aspire E1-421               | [81073e838e](https://linux-hardware.org/?probe=81073e838e) | Jun 05, 2020 |
| ASUSTek       | X455LJ                      | [e7901f9d16](https://linux-hardware.org/?probe=e7901f9d16) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| ASUSTek       | X555LJ                      | [9585e46a59](https://linux-hardware.org/?probe=9585e46a59) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430u 86143HU      | [5a3bf0a8f5](https://linux-hardware.org/?probe=5a3bf0a8f5) | Jun 03, 2020 |
| ASUSTek       | X555LJ                      | [d45d40decd](https://linux-hardware.org/?probe=d45d40decd) | Jun 03, 2020 |
| ASUSTek       | K46CM                       | [994e39c619](https://linux-hardware.org/?probe=994e39c619) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| Acer          | Aspire E1-421               | [618908f152](https://linux-hardware.org/?probe=618908f152) | May 27, 2020 |
| ASUSTek       | X411UQ                      | [a3e9e016a6](https://linux-hardware.org/?probe=a3e9e016a6) | May 27, 2020 |
| Lenovo        | ThinkPad A475 20KMS0NG00    | [4572fa1657](https://linux-hardware.org/?probe=4572fa1657) | May 27, 2020 |
| Dell          | Inspiron 5521               | [169492fdd8](https://linux-hardware.org/?probe=169492fdd8) | May 26, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [871784f430](https://linux-hardware.org/?probe=871784f430) | May 26, 2020 |
| HP            | 430                         | [54ba3df0c8](https://linux-hardware.org/?probe=54ba3df0c8) | May 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c4c76cecbd](https://linux-hardware.org/?probe=c4c76cecbd) | May 23, 2020 |
| HP            | Laptop 14-bw0xx             | [c9c485db32](https://linux-hardware.org/?probe=c9c485db32) | May 22, 2020 |
| Sony          | SVF14A15CLB                 | [7fb2e1bda0](https://linux-hardware.org/?probe=7fb2e1bda0) | May 20, 2020 |
| Samsung       | 535U3C                      | [b3983a1b17](https://linux-hardware.org/?probe=b3983a1b17) | May 20, 2020 |
| Dell          | Inspiron 1420               | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| Dell          | Inspiron N4010              | [fe9c89b85a](https://linux-hardware.org/?probe=fe9c89b85a) | May 17, 2020 |
| Lenovo        | G40-80 80E4                 | [70a6d29aa3](https://linux-hardware.org/?probe=70a6d29aa3) | May 15, 2020 |
| Samsung       | 535U3C                      | [fe2d93033d](https://linux-hardware.org/?probe=fe2d93033d) | May 13, 2020 |
| Lenovo        | V330-14IKB 81B0             | [5ed9a929ec](https://linux-hardware.org/?probe=5ed9a929ec) | May 10, 2020 |
| Sony          | SVE14121CLP                 | [df7e4c2b9f](https://linux-hardware.org/?probe=df7e4c2b9f) | May 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [69942e79bd](https://linux-hardware.org/?probe=69942e79bd) | May 02, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [91627f8ac4](https://linux-hardware.org/?probe=91627f8ac4) | Apr 29, 2020 |
| Toshiba       | Satellite L515              | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Inspur        | M11JB R2.0/R1.1             | [7f92b47ef4](https://linux-hardware.org/?probe=7f92b47ef4) | Apr 27, 2020 |
| HP            | Pavilion dv6                | [163dac19b3](https://linux-hardware.org/?probe=163dac19b3) | Apr 26, 2020 |
| HP            | Pavilion dv6                | [13cb9e8a90](https://linux-hardware.org/?probe=13cb9e8a90) | Apr 26, 2020 |
| Lenovo        | Z50-70 20354                | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Dell          | G5 5587                     | [dd4521b554](https://linux-hardware.org/?probe=dd4521b554) | Apr 21, 2020 |
| HP            | Laptop 14-bs0xx             | [e5243ea838](https://linux-hardware.org/?probe=e5243ea838) | Apr 21, 2020 |
| HP            | Pavilion g4                 | [7e9785b653](https://linux-hardware.org/?probe=7e9785b653) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| HP            | Pavilion g4                 | [3c6a4199c7](https://linux-hardware.org/?probe=3c6a4199c7) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Acer          | Aspire V5-471               | [6540209d65](https://linux-hardware.org/?probe=6540209d65) | Apr 16, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [010fdcb7ab](https://linux-hardware.org/?probe=010fdcb7ab) | Apr 16, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8eae2753ce](https://linux-hardware.org/?probe=8eae2753ce) | Apr 16, 2020 |
| HP            | Laptop 15-db0xxx            | [6ec2d663e5](https://linux-hardware.org/?probe=6ec2d663e5) | Apr 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4b76d231e](https://linux-hardware.org/?probe=a4b76d231e) | Apr 15, 2020 |
| Acer          | Aspire A515-51              | [cb760929c4](https://linux-hardware.org/?probe=cb760929c4) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [25e23d0bf7](https://linux-hardware.org/?probe=25e23d0bf7) | Apr 13, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [823afb58b0](https://linux-hardware.org/?probe=823afb58b0) | Apr 12, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [90b23eb96e](https://linux-hardware.org/?probe=90b23eb96e) | Apr 12, 2020 |
| Dell          | System Inspiron 5420        | [f74d698b46](https://linux-hardware.org/?probe=f74d698b46) | Apr 11, 2020 |
| Toshiba       | Satellite A505              | [f7f3c03ad9](https://linux-hardware.org/?probe=f7f3c03ad9) | Apr 10, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| HP            | Laptop 15-db0xxx            | [c4c866db0d](https://linux-hardware.org/?probe=c4c866db0d) | Apr 04, 2020 |
| HP            | Laptop 15-db0xxx            | [0bb263546b](https://linux-hardware.org/?probe=0bb263546b) | Apr 04, 2020 |
| ASUSTek       | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f9921167fc](https://linux-hardware.org/?probe=f9921167fc) | Apr 02, 2020 |
| HP            | Mini 311-1100               | [d4918f7f3c](https://linux-hardware.org/?probe=d4918f7f3c) | Mar 27, 2020 |
| ASUSTek       | X455LD                      | [ec6c4486ca](https://linux-hardware.org/?probe=ec6c4486ca) | Mar 26, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [60f3879e96](https://linux-hardware.org/?probe=60f3879e96) | Mar 25, 2020 |
| Acer          | Aspire 4750                 | [4757577c86](https://linux-hardware.org/?probe=4757577c86) | Mar 23, 2020 |
| ASUSTek       | K52JT                       | [38330a61d2](https://linux-hardware.org/?probe=38330a61d2) | Mar 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S0VE00    | [4d090cecde](https://linux-hardware.org/?probe=4d090cecde) | Mar 22, 2020 |
| Toshiba       | Satellite C645              | [38d4ca1005](https://linux-hardware.org/?probe=38d4ca1005) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | ProBook 440 G6              | [d42c9c08ee](https://linux-hardware.org/?probe=d42c9c08ee) | Mar 19, 2020 |
| Apple         | MacBookPro8,3               | [1279383fb8](https://linux-hardware.org/?probe=1279383fb8) | Mar 17, 2020 |
| ASUSTek       | X505BP                      | [11da78a649](https://linux-hardware.org/?probe=11da78a649) | Mar 16, 2020 |
| Google        | Pantheon                    | [20acb09771](https://linux-hardware.org/?probe=20acb09771) | Mar 09, 2020 |
| Sony          | VGN-SR51MF_S                | [8783bf4fe5](https://linux-hardware.org/?probe=8783bf4fe5) | Mar 09, 2020 |
| HP            | Laptop 15-db0xxx            | [def3aa7871](https://linux-hardware.org/?probe=def3aa7871) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6dccf0159e](https://linux-hardware.org/?probe=6dccf0159e) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6ec6d9847c](https://linux-hardware.org/?probe=6ec6d9847c) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [e5c1b0bdce](https://linux-hardware.org/?probe=e5c1b0bdce) | Mar 07, 2020 |
| Lenovo        | IdeaPad Z470                | [20a4bdc803](https://linux-hardware.org/?probe=20a4bdc803) | Mar 05, 2020 |
| Lenovo        | IdeaPad Z470                | [b4898d9e36](https://linux-hardware.org/?probe=b4898d9e36) | Mar 05, 2020 |
| ASUSTek       | X505BP                      | [88ec1bf424](https://linux-hardware.org/?probe=88ec1bf424) | Feb 29, 2020 |
| Toshiba       | Satellite L305              | [fd8dfe766e](https://linux-hardware.org/?probe=fd8dfe766e) | Feb 24, 2020 |
| Toshiba       | Satellite L305              | [96c28903af](https://linux-hardware.org/?probe=96c28903af) | Feb 24, 2020 |
| HP            | Pavilion 10 TS              | [1ee504b68f](https://linux-hardware.org/?probe=1ee504b68f) | Feb 24, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [c74cb1d856](https://linux-hardware.org/?probe=c74cb1d856) | Feb 22, 2020 |
| HP            | Laptop 14-bp0xx             | [303f2ada85](https://linux-hardware.org/?probe=303f2ada85) | Feb 19, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [968045d52d](https://linux-hardware.org/?probe=968045d52d) | Feb 19, 2020 |
| HP            | Pavilion 10 TS              | [ed95aa0537](https://linux-hardware.org/?probe=ed95aa0537) | Feb 16, 2020 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [d0276ea845](https://linux-hardware.org/?probe=d0276ea845) | Feb 14, 2020 |
| Acer          | Aspire A315-51              | [1d69448de6](https://linux-hardware.org/?probe=1d69448de6) | Feb 09, 2020 |
| Acer          | Aspire A315-51              | [6d4ecdb510](https://linux-hardware.org/?probe=6d4ecdb510) | Feb 09, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [30b395a14f](https://linux-hardware.org/?probe=30b395a14f) | Feb 08, 2020 |
| Dell          | Vostro 3400                 | [7ad384214e](https://linux-hardware.org/?probe=7ad384214e) | Feb 06, 2020 |
| Apple         | MacBookPro11,1              | [b3a11d5f5d](https://linux-hardware.org/?probe=b3a11d5f5d) | Jan 20, 2020 |
| Unknown       | Unknown                     | [25f6d11655](https://linux-hardware.org/?probe=25f6d11655) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| ASUSTek       | X550ZE                      | [e06f76becf](https://linux-hardware.org/?probe=e06f76becf) | Jan 08, 2020 |
| HP            | Laptop 14-bp0xx             | [30389049c2](https://linux-hardware.org/?probe=30389049c2) | Jan 07, 2020 |
| ASUSTek       | X555YI                      | [06421a5c44](https://linux-hardware.org/?probe=06421a5c44) | Jan 05, 2020 |
| HP            | Laptop 15-db0xxx            | [db9c0c83ce](https://linux-hardware.org/?probe=db9c0c83ce) | Jan 03, 2020 |
| HP            | Laptop 14-bs0xx             | [854604bdad](https://linux-hardware.org/?probe=854604bdad) | Dec 31, 2019 |
| Dell          | Inspiron 5423               | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b6846dfd95](https://linux-hardware.org/?probe=b6846dfd95) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [75a94cfe2f](https://linux-hardware.org/?probe=75a94cfe2f) | Dec 28, 2019 |
| Dell          | Inspiron 5748               | [17ed1f4194](https://linux-hardware.org/?probe=17ed1f4194) | Dec 22, 2019 |
| HP            | Laptop 14-bp0xx             | [c99b71d804](https://linux-hardware.org/?probe=c99b71d804) | Dec 18, 2019 |
| Lenovo        | G40-45 80E1                 | [b1f6e07d2b](https://linux-hardware.org/?probe=b1f6e07d2b) | Dec 09, 2019 |
| HP            | Pavilion 10 TS              | [fbe754b72c](https://linux-hardware.org/?probe=fbe754b72c) | Nov 29, 2019 |
| Lenovo        | Flex 2-14D 20376            | [d78bbdfa2a](https://linux-hardware.org/?probe=d78bbdfa2a) | Nov 18, 2019 |
| Lenovo        | Flex 2-14D 20376            | [7e957006e4](https://linux-hardware.org/?probe=7e957006e4) | Nov 18, 2019 |
| HP            | Laptop 15-da0xxx            | [cb6e592c0d](https://linux-hardware.org/?probe=cb6e592c0d) | Nov 18, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| ASUSTek       | X550DP                      | [9515caaefa](https://linux-hardware.org/?probe=9515caaefa) | Nov 17, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [4e2ba6330f](https://linux-hardware.org/?probe=4e2ba6330f) | Nov 09, 2019 |
| Lenovo        | ThinkPad E460 20EUA00900    | [a549aed5b4](https://linux-hardware.org/?probe=a549aed5b4) | Nov 08, 2019 |
| HP            | Laptop 14-bs0xx             | [36570780b5](https://linux-hardware.org/?probe=36570780b5) | Oct 30, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [5d4e6e95f1](https://linux-hardware.org/?probe=5d4e6e95f1) | Oct 30, 2019 |
| Dell          | XPS 15 9550                 | [7323abf391](https://linux-hardware.org/?probe=7323abf391) | Oct 29, 2019 |
| HP            | Laptop 14-bs0xx             | [4270a9638b](https://linux-hardware.org/?probe=4270a9638b) | Oct 29, 2019 |
| Dell          | XPS 15 9550                 | [c70f66f439](https://linux-hardware.org/?probe=c70f66f439) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [666b6342e0](https://linux-hardware.org/?probe=666b6342e0) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [36c76546e9](https://linux-hardware.org/?probe=36c76546e9) | Oct 29, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [3469bcd886](https://linux-hardware.org/?probe=3469bcd886) | Oct 28, 2019 |
| HP            | Laptop 14-bp0xx             | [2e6a129f3e](https://linux-hardware.org/?probe=2e6a129f3e) | Oct 24, 2019 |
| VIT           | P2412                       | [2604d0b890](https://linux-hardware.org/?probe=2604d0b890) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6206eb1a2f](https://linux-hardware.org/?probe=6206eb1a2f) | Oct 11, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9a54660b4f](https://linux-hardware.org/?probe=9a54660b4f) | Oct 11, 2019 |
| Toshiba       | NB 105                      | [07f2ac3953](https://linux-hardware.org/?probe=07f2ac3953) | Oct 08, 2019 |
| Toshiba       | NB 105                      | [56d1fb0551](https://linux-hardware.org/?probe=56d1fb0551) | Oct 08, 2019 |
| ASUSTek       | X505BP                      | [147a0012a9](https://linux-hardware.org/?probe=147a0012a9) | Oct 08, 2019 |
| HP            | Pavilion 10 TS              | [f1d915aa56](https://linux-hardware.org/?probe=f1d915aa56) | Oct 06, 2019 |
| Acer          | Aspire E3-111               | [cb12dc0dcd](https://linux-hardware.org/?probe=cb12dc0dcd) | Sep 18, 2019 |
| Chuwi         | LapBook Plus                | [2cc2dc7812](https://linux-hardware.org/?probe=2cc2dc7812) | Sep 15, 2019 |
| Samsung       | 535U3C                      | [3605b4bcc2](https://linux-hardware.org/?probe=3605b4bcc2) | Sep 15, 2019 |
| Fujitsu       | LIFEBOOK T734               | [38a59cafac](https://linux-hardware.org/?probe=38a59cafac) | Sep 07, 2019 |
| Acer          | Aspire E1-571               | [f7809cd921](https://linux-hardware.org/?probe=f7809cd921) | Sep 06, 2019 |
| HP            | 240 G4 Notebook PC          | [c29c743021](https://linux-hardware.org/?probe=c29c743021) | Sep 06, 2019 |
| HP            | Laptop 15-db0xxx            | [47661b90c1](https://linux-hardware.org/?probe=47661b90c1) | Aug 31, 2019 |
| HP            | Laptop 14-ck0xxx            | [e4ca853a88](https://linux-hardware.org/?probe=e4ca853a88) | Aug 30, 2019 |
| HP            | Laptop 14-ck0xxx            | [ebb5e97cc6](https://linux-hardware.org/?probe=ebb5e97cc6) | Aug 30, 2019 |
| Samsung       | 535U3C                      | [05752face4](https://linux-hardware.org/?probe=05752face4) | Aug 29, 2019 |
| Lenovo        | G40-80 80E4                 | [386e041ee1](https://linux-hardware.org/?probe=386e041ee1) | Aug 27, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [934edb8a8d](https://linux-hardware.org/?probe=934edb8a8d) | Aug 19, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [d9d655f7eb](https://linux-hardware.org/?probe=d9d655f7eb) | Aug 19, 2019 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c3f8c454d5](https://linux-hardware.org/?probe=c3f8c454d5) | Aug 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [60d6ad276f](https://linux-hardware.org/?probe=60d6ad276f) | Aug 16, 2019 |
| HP            | Laptop 15-db0xxx            | [9b10892d1f](https://linux-hardware.org/?probe=9b10892d1f) | Aug 12, 2019 |
| HP            | 240 G4 Notebook PC          | [8abebd7b2f](https://linux-hardware.org/?probe=8abebd7b2f) | Jul 31, 2019 |
| ASUSTek       | G73Jw                       | [34c2f4a1e6](https://linux-hardware.org/?probe=34c2f4a1e6) | Jul 31, 2019 |
| Acer          | Aspire V3-471               | [6e533b7623](https://linux-hardware.org/?probe=6e533b7623) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [7637f3de5f](https://linux-hardware.org/?probe=7637f3de5f) | Jul 28, 2019 |
| Acer          | Aspire 4750                 | [481b67d08f](https://linux-hardware.org/?probe=481b67d08f) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| Acer          | Aspire 4750                 | [bf530b04c7](https://linux-hardware.org/?probe=bf530b04c7) | Jul 22, 2019 |
| HP            | Presario CQ43               | [4201cdd966](https://linux-hardware.org/?probe=4201cdd966) | Jul 20, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ca74df306b](https://linux-hardware.org/?probe=ca74df306b) | Jul 14, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [c75d45bec4](https://linux-hardware.org/?probe=c75d45bec4) | Jul 14, 2019 |
| HP            | Laptop 14-ck0xxx            | [05497b6d61](https://linux-hardware.org/?probe=05497b6d61) | Jul 12, 2019 |
| HP            | Laptop 14-bs0xx             | [7a8cfa539b](https://linux-hardware.org/?probe=7a8cfa539b) | Jun 23, 2019 |
| HP            | ProBook 440 G2              | [592064f97e](https://linux-hardware.org/?probe=592064f97e) | Jun 23, 2019 |
| ASUSTek       | X542URR                     | [adf12d067f](https://linux-hardware.org/?probe=adf12d067f) | Jun 19, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [3cecb13c13](https://linux-hardware.org/?probe=3cecb13c13) | Jun 18, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [af291d02cf](https://linux-hardware.org/?probe=af291d02cf) | Jun 17, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7061046667](https://linux-hardware.org/?probe=7061046667) | Jun 15, 2019 |
| HP            | Pavilion dm1                | [01e9de8250](https://linux-hardware.org/?probe=01e9de8250) | Jun 13, 2019 |
| HP            | Pavilion dm1                | [40f5482a9d](https://linux-hardware.org/?probe=40f5482a9d) | Jun 13, 2019 |
| HP            | Laptop 15-db0xxx            | [f69654fec4](https://linux-hardware.org/?probe=f69654fec4) | Jun 13, 2019 |
| ASUSTek       | X455LAB                     | [6fc7fb8c0e](https://linux-hardware.org/?probe=6fc7fb8c0e) | Jun 12, 2019 |
| ASUSTek       | X455LAB                     | [a8004d007d](https://linux-hardware.org/?probe=a8004d007d) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | [cb1771b144](https://linux-hardware.org/?probe=cb1771b144) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | [ca315cb07b](https://linux-hardware.org/?probe=ca315cb07b) | Jun 12, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [5e80fdb647](https://linux-hardware.org/?probe=5e80fdb647) | Jun 11, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8eaae370e1](https://linux-hardware.org/?probe=8eaae370e1) | Jun 10, 2019 |
| ASUSTek       | X450CC                      | [9604bdacb2](https://linux-hardware.org/?probe=9604bdacb2) | Jun 10, 2019 |
| Lenovo        | IdeaPadFlex 14 20308        | [23bd541bf1](https://linux-hardware.org/?probe=23bd541bf1) | Jun 10, 2019 |
| Dell          | Inspiron 1420               | [09ca7997ac](https://linux-hardware.org/?probe=09ca7997ac) | Jun 09, 2019 |
| HP            | Pavilion tx1000             | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| HP            | Notebook                    | [c428093164](https://linux-hardware.org/?probe=c428093164) | Jun 06, 2019 |
| HP            | EliteBook 840 G3            | [b828ffaace](https://linux-hardware.org/?probe=b828ffaace) | Jun 05, 2019 |
| HP            | ENVY 15                     | [f1ee36482d](https://linux-hardware.org/?probe=f1ee36482d) | Jun 03, 2019 |
| HP            | ENVY 15                     | [da05c24e64](https://linux-hardware.org/?probe=da05c24e64) | Jun 03, 2019 |
| HP            | ENVY 15                     | [b450947391](https://linux-hardware.org/?probe=b450947391) | Jun 03, 2019 |
| Acer          | Nitro AN515-52              | [30f1da590b](https://linux-hardware.org/?probe=30f1da590b) | Jun 03, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e11ecb2f55](https://linux-hardware.org/?probe=e11ecb2f55) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [5b282c8861](https://linux-hardware.org/?probe=5b282c8861) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [48cc73875b](https://linux-hardware.org/?probe=48cc73875b) | May 26, 2019 |
| ASUSTek       | X555LN                      | [2022ef16da](https://linux-hardware.org/?probe=2022ef16da) | May 23, 2019 |
| Lenovo        | ThinkPad X230 2325P35       | [d666ba7823](https://linux-hardware.org/?probe=d666ba7823) | May 22, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [197946e655](https://linux-hardware.org/?probe=197946e655) | May 09, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [1700077449](https://linux-hardware.org/?probe=1700077449) | May 07, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [0a5569615d](https://linux-hardware.org/?probe=0a5569615d) | May 07, 2019 |
| Acer          | Aspire E5-575G              | [253b707c92](https://linux-hardware.org/?probe=253b707c92) | May 05, 2019 |
| Toshiba       | NB 105                      | [4662d43a44](https://linux-hardware.org/?probe=4662d43a44) | Apr 29, 2019 |
| Toshiba       | NB 105                      | [65ef86cd1c](https://linux-hardware.org/?probe=65ef86cd1c) | Apr 29, 2019 |
| ASUSTek       | X705UDR                     | [32a2339838](https://linux-hardware.org/?probe=32a2339838) | Apr 27, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [a6a1ecf366](https://linux-hardware.org/?probe=a6a1ecf366) | Apr 24, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b34ded162f](https://linux-hardware.org/?probe=b34ded162f) | Apr 22, 2019 |
| ASUSTek       | G73Jw                       | [2626377d36](https://linux-hardware.org/?probe=2626377d36) | Apr 20, 2019 |
| Apple         | MacBookAir6,2               | [a6dd71fdd3](https://linux-hardware.org/?probe=a6dd71fdd3) | Apr 19, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | [c488c71bcd](https://linux-hardware.org/?probe=c488c71bcd) | Apr 17, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | [f5fc1d9048](https://linux-hardware.org/?probe=f5fc1d9048) | Apr 17, 2019 |
| PCSMART       | AIRNOTE                     | [8ccaad6ff9](https://linux-hardware.org/?probe=8ccaad6ff9) | Apr 16, 2019 |
| PCSMART       | AIRNOTE                     | [fd6c64b14c](https://linux-hardware.org/?probe=fd6c64b14c) | Apr 16, 2019 |
| Acer          | Aspire A515-51              | [b1b58b7d6b](https://linux-hardware.org/?probe=b1b58b7d6b) | Apr 16, 2019 |
| ASUSTek       | X505BP                      | [dcaf818df8](https://linux-hardware.org/?probe=dcaf818df8) | Apr 16, 2019 |
| Fujitsu       | LIFEBOOK T734               | [06582bdb98](https://linux-hardware.org/?probe=06582bdb98) | Apr 13, 2019 |
| HP            | Laptop 14-bs0xx             | [73f15e5986](https://linux-hardware.org/?probe=73f15e5986) | Apr 12, 2019 |
| ASUSTek       | N56JRH                      | [5764250d85](https://linux-hardware.org/?probe=5764250d85) | Apr 03, 2019 |
| HP            | Pavilion Notebook           | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP            | Pavilion Notebook           | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| ASUSTek       | TAICHI21                    | [ceedb83caa](https://linux-hardware.org/?probe=ceedb83caa) | Mar 25, 2019 |
| HP            | 14                          | [3532a15338](https://linux-hardware.org/?probe=3532a15338) | Mar 19, 2019 |
| Sony          | SVE14A27CXH                 | [f8e75b8eca](https://linux-hardware.org/?probe=f8e75b8eca) | Mar 17, 2019 |
| Acer          | Aspire E3-111               | [e11f7a05d2](https://linux-hardware.org/?probe=e11f7a05d2) | Mar 14, 2019 |
| ASUSTek       | TAICHI21                    | [a90d891180](https://linux-hardware.org/?probe=a90d891180) | Mar 07, 2019 |
| ASUSTek       | X541NA                      | [4fb49f65ef](https://linux-hardware.org/?probe=4fb49f65ef) | Feb 28, 2019 |
| HP            | Laptop 15-da0xxx            | [e1e477a44d](https://linux-hardware.org/?probe=e1e477a44d) | Jan 24, 2019 |
| Dell          | Inspiron 5423               | [0ae4be99f8](https://linux-hardware.org/?probe=0ae4be99f8) | Jan 23, 2019 |
| Dell          | Inspiron 5423               | [0f80a72955](https://linux-hardware.org/?probe=0f80a72955) | Jan 23, 2019 |
| HP            | Laptop 15-da0xxx            | [2ec93c29be](https://linux-hardware.org/?probe=2ec93c29be) | Jan 08, 2019 |
| HP            | 245 G6                      | [feeb8ea6f8](https://linux-hardware.org/?probe=feeb8ea6f8) | Jan 03, 2019 |
| ASUSTek       | X505BP                      | [7f4192344e](https://linux-hardware.org/?probe=7f4192344e) | Dec 29, 2018 |
| ASUSTek       | X505BP                      | [0999f0abc7](https://linux-hardware.org/?probe=0999f0abc7) | Dec 29, 2018 |
| HP            | 245 G6                      | [4289ff0916](https://linux-hardware.org/?probe=4289ff0916) | Dec 28, 2018 |
| HP            | 14                          | [0fe4f88e5a](https://linux-hardware.org/?probe=0fe4f88e5a) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | [d6d801ec2b](https://linux-hardware.org/?probe=d6d801ec2b) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | [002ca9c182](https://linux-hardware.org/?probe=002ca9c182) | Dec 19, 2018 |
| ASUSTek       | X505BP                      | [1388526b7f](https://linux-hardware.org/?probe=1388526b7f) | Dec 17, 2018 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [57ba3702e3](https://linux-hardware.org/?probe=57ba3702e3) | Dec 11, 2018 |
| Dell          | Latitude D620               | [81774e2415](https://linux-hardware.org/?probe=81774e2415) | Dec 07, 2018 |
| Acer          | Unknown                     | [02419cd635](https://linux-hardware.org/?probe=02419cd635) | Dec 03, 2018 |
| Samsung       | N148P                       | [629403b78b](https://linux-hardware.org/?probe=629403b78b) | Nov 25, 2018 |
| Acer          | Unknown                     | [e25ca67959](https://linux-hardware.org/?probe=e25ca67959) | Nov 20, 2018 |
| Acer          | Unknown                     | [f5a1c21578](https://linux-hardware.org/?probe=f5a1c21578) | Nov 18, 2018 |
| HP            | 1000                        | [e8425d849b](https://linux-hardware.org/?probe=e8425d849b) | Nov 10, 2018 |
| Toshiba       | Satellite C675D             | [aa4071d1df](https://linux-hardware.org/?probe=aa4071d1df) | Nov 05, 2018 |
| ASUSTek       | X542URR                     | [a5e2816233](https://linux-hardware.org/?probe=a5e2816233) | Nov 03, 2018 |
| ASUSTek       | X542URR                     | [2a42f7d935](https://linux-hardware.org/?probe=2a42f7d935) | Nov 03, 2018 |
| Acer          | Aspire 4736Z                | [0d5e0790a7](https://linux-hardware.org/?probe=0d5e0790a7) | Oct 30, 2018 |
| Acer          | Aspire 4736Z                | [17113b9ae5](https://linux-hardware.org/?probe=17113b9ae5) | Oct 30, 2018 |
| ASUSTek       | X505BP                      | [09546ff0fe](https://linux-hardware.org/?probe=09546ff0fe) | Oct 29, 2018 |
| ASUSTek       | X505BP                      | [24dffba93d](https://linux-hardware.org/?probe=24dffba93d) | Oct 29, 2018 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [890de967ad](https://linux-hardware.org/?probe=890de967ad) | Oct 26, 2018 |
| HP            | Pavilion 14                 | [a708531868](https://linux-hardware.org/?probe=a708531868) | Oct 25, 2018 |
| HP            | Pavilion 14                 | [dcd47dff54](https://linux-hardware.org/?probe=dcd47dff54) | Oct 25, 2018 |
| Toshiba       | Satellite C655              | [b158836f6e](https://linux-hardware.org/?probe=b158836f6e) | Oct 23, 2018 |
| Toshiba       | Satellite C655              | [347c50681c](https://linux-hardware.org/?probe=347c50681c) | Oct 23, 2018 |
| ASUSTek       | X455LD                      | [6224197a75](https://linux-hardware.org/?probe=6224197a75) | Oct 12, 2018 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [9f2347db71](https://linux-hardware.org/?probe=9f2347db71) | Oct 09, 2018 |
| ASUSTek       | G550JK                      | [af5510f93b](https://linux-hardware.org/?probe=af5510f93b) | Jun 19, 2018 |
| HP            | 14                          | [13f12e2f48](https://linux-hardware.org/?probe=13f12e2f48) | May 23, 2018 |
| HP            | Compaq Presario CQ45        | [762d293955](https://linux-hardware.org/?probe=762d293955) | May 12, 2018 |
| Acer          | Aspire 4739                 | [31eeafc656](https://linux-hardware.org/?probe=31eeafc656) | Jan 04, 2018 |
| Lenovo        | G40-80 80E4                 | [1855d90774](https://linux-hardware.org/?probe=1855d90774) | Dec 19, 2017 |
| Acer          | Aspire 4739                 | [dc6c363798](https://linux-hardware.org/?probe=dc6c363798) | Oct 02, 2017 |
| HP            | Compaq Presario CQ45        | [5c6365ef1a](https://linux-hardware.org/?probe=5c6365ef1a) | Jul 21, 2017 |
| HP            | Compaq Presario CQ45        | [909a456d4f](https://linux-hardware.org/?probe=909a456d4f) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | [6571151136](https://linux-hardware.org/?probe=6571151136) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | [dc632cca26](https://linux-hardware.org/?probe=dc632cca26) | Mar 18, 2017 |
| HP            | Compaq Presario CQ45        | [c8bbfe9037](https://linux-hardware.org/?probe=c8bbfe9037) | Jan 04, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 79        | 15.49%  |
| Ubuntu 18.04                 | 65        | 12.75%  |
| OpenMandriva 4.3             | 18        | 3.53%   |
| Ubuntu 19.04                 | 11        | 2.16%   |
| KDE neon 20.04               | 10        | 1.96%   |
| OpenMandriva 4.2             | 9         | 1.76%   |
| Arch                         | 9         | 1.76%   |
| Fedora 34                    | 8         | 1.57%   |
| Zorin 15                     | 7         | 1.37%   |
| Ubuntu 20.10                 | 7         | 1.37%   |
| Ubuntu 19.10                 | 7         | 1.37%   |
| ROSA R10                     | 7         | 1.37%   |
| Manjaro                      | 7         | 1.37%   |
| Linux Mint 20.3              | 7         | 1.37%   |
| Linux Mint 20.1              | 7         | 1.37%   |
| Linux Mint 19.3              | 7         | 1.37%   |
| Debian 11                    | 7         | 1.37%   |
| Arch Rolling                 | 7         | 1.37%   |
| Zorin 16                     | 6         | 1.18%   |
| Ubuntu 16.04                 | 6         | 1.18%   |
| Pop!_OS 20.04                | 6         | 1.18%   |
| Ubuntu 22.04                 | 5         | 0.98%   |
| Ubuntu 21.04                 | 5         | 0.98%   |
| Linux Mint 20.2              | 5         | 0.98%   |
| Linux Mint 20                | 5         | 0.98%   |
| Kubuntu 20.04                | 5         | 0.98%   |
| Fedora 33                    | 5         | 0.98%   |
| Debian 10                    | 5         | 0.98%   |
| Ubuntu 18.10                 | 4         | 0.78%   |
| Linux Mint 19.2              | 4         | 0.78%   |
| Fedora 31                    | 4         | 0.78%   |
| Endless 3.8.3                | 4         | 0.78%   |
| Xubuntu 20.04                | 3         | 0.59%   |
| Xubuntu 18.04                | 3         | 0.59%   |
| Pop!_OS 21.10                | 3         | 0.59%   |
| Pop!_OS 20.10                | 3         | 0.59%   |
| Linux Mint 19.1              | 3         | 0.59%   |
| Fedora 35                    | 3         | 0.59%   |
| Fedora 32                    | 3         | 0.59%   |
| Endless 3.9.1                | 3         | 0.59%   |
| Endless 3.9.0                | 3         | 0.59%   |
| Endless 3.8.4                | 3         | 0.59%   |
| Endless 3.8.1                | 3         | 0.59%   |
| Endless 3.6.0                | 3         | 0.59%   |
| Endless 3.5.7                | 3         | 0.59%   |
| Debian 9                     | 3         | 0.59%   |
| Ubuntu 21.10                 | 2         | 0.39%   |
| Ubuntu                       | 2         | 0.39%   |
| ROSA R9                      | 2         | 0.39%   |
| ROSA R11.1                   | 2         | 0.39%   |
| ROSA R11                     | 2         | 0.39%   |
| Pop!_OS 22.04                | 2         | 0.39%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.39%   |
| Manjaro 21.1.0               | 2         | 0.39%   |
| Kubuntu 21.04                | 2         | 0.39%   |
| KDE neon 18.04               | 2         | 0.39%   |
| Kali Rolling                 | 2         | 0.39%   |
| Kali 2022.1                  | 2         | 0.39%   |
| Garuda Linux Soaring         | 2         | 0.39%   |
| Fedora 36                    | 2         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 185       | 38.14%  |
| Endless       | 55        | 11.34%  |
| Linux Mint    | 38        | 7.84%   |
| OpenMandriva  | 27        | 5.57%   |
| Fedora        | 24        | 4.95%   |
| Manjaro       | 19        | 3.92%   |
| Arch          | 16        | 3.3%    |
| Pop!_OS       | 15        | 3.09%   |
| Debian        | 15        | 3.09%   |
| Zorin         | 13        | 2.68%   |
| ROSA          | 13        | 2.68%   |
| KDE neon      | 11        | 2.27%   |
| Kubuntu       | 9         | 1.86%   |
| Xubuntu       | 7         | 1.44%   |
| Kali          | 7         | 1.44%   |
| Elementary    | 5         | 1.03%   |
| Lubuntu       | 3         | 0.62%   |
| ArcoLinux     | 3         | 0.62%   |
| openSUSE      | 2         | 0.41%   |
| MX            | 2         | 0.41%   |
| Garuda Linux  | 2         | 0.41%   |
| EndeavourOS   | 2         | 0.41%   |
| Clear Linux   | 2         | 0.41%   |
| UbuntuDDE     | 1         | 0.21%   |
| Ubuntu Budgie | 1         | 0.21%   |
| RHEL          | 1         | 0.21%   |
| Parrot        | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |
| Mageia        | 1         | 0.21%   |
| LinuxFX       | 1         | 0.21%   |
| Linux Lite    | 1         | 0.21%   |
| Deepin        | 1         | 0.21%   |
| CentOS        | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 19        | 3.53%   |
| 5.16.7-desktop-1omv4003         | 18        | 3.34%   |
| 5.8.0-14-generic                | 12        | 2.23%   |
| 5.4.0-19-generic                | 11        | 2.04%   |
| 5.4.0-58-generic                | 10        | 1.86%   |
| 5.10.14-desktop-1omv4002        | 9         | 1.67%   |
| 5.3.0-46-generic                | 7         | 1.3%    |
| 5.3.0-28-generic                | 6         | 1.11%   |
| 4.18.0-25-generic               | 6         | 1.11%   |
| 4.18.0-15-generic               | 6         | 1.11%   |
| 5.8.0-43-generic                | 5         | 0.93%   |
| 5.4.0-48-generic                | 5         | 0.93%   |
| 5.4.0-31-generic                | 5         | 0.93%   |
| 5.3.0-40-generic                | 5         | 0.93%   |
| 5.13.0-40-generic               | 5         | 0.93%   |
| 5.0.0-37-generic                | 5         | 0.93%   |
| 5.0.0-25-generic                | 5         | 0.93%   |
| 5.8.0-59-generic                | 4         | 0.74%   |
| 5.8.0-44-generic                | 4         | 0.74%   |
| 5.4.0-65-generic                | 4         | 0.74%   |
| 5.4.0-64-generic                | 4         | 0.74%   |
| 5.4.0-54-generic                | 4         | 0.74%   |
| 5.4.0-37-generic                | 4         | 0.74%   |
| 5.4.0-26-generic                | 4         | 0.74%   |
| 5.13.0-30-generic               | 4         | 0.74%   |
| 5.11.0-40-generic               | 4         | 0.74%   |
| 5.0.0-15-generic                | 4         | 0.74%   |
| 5.0.0-13-generic                | 4         | 0.74%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4         | 0.74%   |
| 5.4.0-70-generic                | 3         | 0.56%   |
| 5.4.0-59-generic                | 3         | 0.56%   |
| 5.4.0-47-generic                | 3         | 0.56%   |
| 5.4.0-33-generic                | 3         | 0.56%   |
| 5.4.0-107-generic               | 3         | 0.56%   |
| 5.11.0-38-generic               | 3         | 0.56%   |
| 5.11.0-34-generic               | 3         | 0.56%   |
| 5.11.0-27-generic               | 3         | 0.56%   |
| 5.11.0-25-generic               | 3         | 0.56%   |
| 5.10.0-9-amd64                  | 3         | 0.56%   |
| 5.1.0-2-generic                 | 3         | 0.56%   |
| 4.18.0-21-generic               | 3         | 0.56%   |
| 4.18.0-11-generic               | 3         | 0.56%   |
| 4.15.0-47-generic               | 3         | 0.56%   |
| 5.9.16-200.fc33.x86_64          | 2         | 0.37%   |
| 5.8.0-7642-generic              | 2         | 0.37%   |
| 5.8.0-55-generic                | 2         | 0.37%   |
| 5.8.0-48-generic                | 2         | 0.37%   |
| 5.4.0-89-generic                | 2         | 0.37%   |
| 5.4.0-84-generic                | 2         | 0.37%   |
| 5.4.0-67-generic                | 2         | 0.37%   |
| 5.4.0-52-generic                | 2         | 0.37%   |
| 5.4.0-49-generic                | 2         | 0.37%   |
| 5.4.0-40-generic                | 2         | 0.37%   |
| 5.4.0-39-generic                | 2         | 0.37%   |
| 5.4.0-109-generic               | 2         | 0.37%   |
| 5.4.0-105-generic               | 2         | 0.37%   |
| 5.4.0-100-generic               | 2         | 0.37%   |
| 5.3.0-62-generic                | 2         | 0.37%   |
| 5.3.0-53-generic                | 2         | 0.37%   |
| 5.3.0-51-generic                | 2         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 113       | 21.69%  |
| 4.15.0  | 42        | 8.06%   |
| 5.8.0   | 41        | 7.87%   |
| 5.3.0   | 39        | 7.49%   |
| 5.0.0   | 33        | 6.33%   |
| 4.18.0  | 26        | 4.99%   |
| 5.13.0  | 25        | 4.8%    |
| 5.11.0  | 24        | 4.61%   |
| 5.16.7  | 18        | 3.45%   |
| 5.10.14 | 9         | 1.73%   |
| 5.10.0  | 8         | 1.54%   |
| 5.15.0  | 6         | 1.15%   |
| 4.9.60  | 5         | 0.96%   |
| 4.19.0  | 5         | 0.96%   |
| 4.13.0  | 4         | 0.77%   |
| 5.9.16  | 3         | 0.58%   |
| 5.14.0  | 3         | 0.58%   |
| 5.1.0   | 3         | 0.58%   |
| 4.9.0   | 3         | 0.58%   |
| 4.4.0   | 3         | 0.58%   |
| 5.9.1   | 2         | 0.38%   |
| 5.7.19  | 2         | 0.38%   |
| 5.6.0   | 2         | 0.38%   |
| 5.4.32  | 2         | 0.38%   |
| 5.17.5  | 2         | 0.38%   |
| 5.17.3  | 2         | 0.38%   |
| 5.15.7  | 2         | 0.38%   |
| 5.15.28 | 2         | 0.38%   |
| 5.13.5  | 2         | 0.38%   |
| 5.13.4  | 2         | 0.38%   |
| 5.11.11 | 2         | 0.38%   |
| 4.9.20  | 2         | 0.38%   |
| 5.9.6   | 1         | 0.19%   |
| 5.9.14  | 1         | 0.19%   |
| 5.9.11  | 1         | 0.19%   |
| 5.9.10  | 1         | 0.19%   |
| 5.8.7   | 1         | 0.19%   |
| 5.8.5   | 1         | 0.19%   |
| 5.8.18  | 1         | 0.19%   |
| 5.8.16  | 1         | 0.19%   |
| 5.7.8   | 1         | 0.19%   |
| 5.7.6   | 1         | 0.19%   |
| 5.7.17  | 1         | 0.19%   |
| 5.7.0   | 1         | 0.19%   |
| 5.6.8   | 1         | 0.19%   |
| 5.6.6   | 1         | 0.19%   |
| 5.6.3   | 1         | 0.19%   |
| 5.6.2   | 1         | 0.19%   |
| 5.6.19  | 1         | 0.19%   |
| 5.6.15  | 1         | 0.19%   |
| 5.6.14  | 1         | 0.19%   |
| 5.6.10  | 1         | 0.19%   |
| 5.5.8   | 1         | 0.19%   |
| 5.5.5   | 1         | 0.19%   |
| 5.5.15  | 1         | 0.19%   |
| 5.5.1   | 1         | 0.19%   |
| 5.4.24  | 1         | 0.19%   |
| 5.3.8   | 1         | 0.19%   |
| 5.3.7   | 1         | 0.19%   |
| 5.3.12  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 116       | 22.52%  |
| 5.8     | 45        | 8.74%   |
| 5.3     | 43        | 8.35%   |
| 4.15    | 42        | 8.16%   |
| 5.13    | 34        | 6.6%    |
| 5.0     | 34        | 6.6%    |
| 5.11    | 29        | 5.63%   |
| 5.10    | 28        | 5.44%   |
| 4.18    | 27        | 5.24%   |
| 5.16    | 21        | 4.08%   |
| 5.15    | 15        | 2.91%   |
| 4.9     | 12        | 2.33%   |
| 5.6     | 10        | 1.94%   |
| 5.9     | 8         | 1.55%   |
| 5.17    | 8         | 1.55%   |
| 5.7     | 6         | 1.17%   |
| 4.19    | 6         | 1.17%   |
| 5.14    | 5         | 0.97%   |
| 5.5     | 4         | 0.78%   |
| 5.12    | 4         | 0.78%   |
| 4.13    | 4         | 0.78%   |
| 5.1     | 3         | 0.58%   |
| 4.4     | 3         | 0.58%   |
| 5.18    | 2         | 0.39%   |
| 5.2     | 1         | 0.19%   |
| 4.20    | 1         | 0.19%   |
| 4.14    | 1         | 0.19%   |
| 4.12    | 1         | 0.19%   |
| 4.10    | 1         | 0.19%   |
| 4.1     | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 463       | 97.27%  |
| i686   | 13        | 2.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 232       | 47.15%  |
| Unknown    | 92        | 18.7%   |
| KDE5       | 56        | 11.38%  |
| XFCE       | 34        | 6.91%   |
| X-Cinnamon | 21        | 4.27%   |
| KDE        | 18        | 3.66%   |
| KDE4       | 8         | 1.63%   |
| Pantheon   | 5         | 1.02%   |
| MATE       | 5         | 1.02%   |
| Cinnamon   | 5         | 1.02%   |
| Unity      | 4         | 0.81%   |
| Budgie     | 3         | 0.61%   |
| LXDE       | 2         | 0.41%   |
| Deepin     | 2         | 0.41%   |
| bspwm      | 2         | 0.41%   |
| LXQt       | 1         | 0.2%    |
| ICEWM      | 1         | 0.2%    |
| awesome    | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 387       | 79.79%  |
| Unknown | 64        | 13.2%   |
| Wayland | 32        | 6.6%    |
| Tty     | 2         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 305       | 62.5%   |
| GDM     | 50        | 10.25%  |
| SDDM    | 49        | 10.04%  |
| LightDM | 36        | 7.38%   |
| GDM3    | 25        | 5.12%   |
| TDM     | 14        | 2.87%   |
| KDM     | 8         | 1.64%   |
| LXDM    | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_CO   | 218       | 44.4%   |
| en_US   | 117       | 23.83%  |
| Unknown | 99        | 20.16%  |
| es_ES   | 28        | 5.7%    |
| es_MX   | 11        | 2.24%   |
| es_PE   | 3         | 0.61%   |
| en_GB   | 3         | 0.61%   |
| es_EC   | 2         | 0.41%   |
| pt_PT   | 1         | 0.2%    |
| pl_PL   | 1         | 0.2%    |
| it_IT   | 1         | 0.2%    |
| fr_FR   | 1         | 0.2%    |
| es_VE   | 1         | 0.2%    |
| es_CL   | 1         | 0.2%    |
| es_AR   | 1         | 0.2%    |
| en      | 1         | 0.2%    |
| de_DE   | 1         | 0.2%    |
| C       | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 264       | 54.32%  |
| BIOS | 222       | 45.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 393       | 80.53%  |
| Unknown | 38        | 7.79%   |
| Overlay | 28        | 5.74%   |
| Btrfs   | 18        | 3.69%   |
| Xfs     | 8         | 1.64%   |
| Tmpfs   | 1         | 0.2%    |
| F2fs    | 1         | 0.2%    |
| Ext2    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 331       | 68.96%  |
| GPT     | 108       | 22.5%   |
| MBR     | 41        | 8.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 427       | 88.04%  |
| Yes       | 58        | 11.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 322       | 66.8%   |
| Yes       | 160       | 33.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 116       | 24.37%  |
| Hewlett-Packard              | 102       | 21.43%  |
| Lenovo                       | 89        | 18.7%   |
| Dell                         | 44        | 9.24%   |
| Acer                         | 44        | 9.24%   |
| Toshiba                      | 19        | 3.99%   |
| Samsung Electronics          | 12        | 2.52%   |
| MSI                          | 9         | 1.89%   |
| Apple                        | 9         | 1.89%   |
| Sony                         | 8         | 1.68%   |
| HUAWEI                       | 4         | 0.84%   |
| Unknown                      | 4         | 0.84%   |
| Notebook                     | 2         | 0.42%   |
| Gateway                      | 2         | 0.42%   |
| VIT                          | 1         | 0.21%   |
| Timi                         | 1         | 0.21%   |
| PCSMART                      | 1         | 0.21%   |
| MPS Mayorista de Colombia SA | 1         | 0.21%   |
| Inspur                       | 1         | 0.21%   |
| GreatWall                    | 1         | 0.21%   |
| Google                       | 1         | 0.21%   |
| Fujitsu Siemens              | 1         | 0.21%   |
| Fujitsu                      | 1         | 0.21%   |
| Framework                    | 1         | 0.21%   |
| Chuwi                        | 1         | 0.21%   |
| BAKED                        | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-db0xxx                        | 11        | 2.31%   |
| Samsung 300E4C/300E5C/300E7C               | 5         | 1.05%   |
| HP Laptop 14-bs0xx                         | 5         | 1.05%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 5         | 1.05%   |
| Unknown                                    | 5         | 1.05%   |
| HP Notebook                                | 4         | 0.84%   |
| HP Laptop 14-cm1xxx                        | 4         | 0.84%   |
| HP 14                                      | 4         | 0.84%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.84%   |
| Lenovo IdeaPad S340-14API 81NB             | 3         | 0.63%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 3         | 0.63%   |
| Lenovo G40-80 80E4                         | 3         | 0.63%   |
| Lenovo G40-45 80E1                         | 3         | 0.63%   |
| HP ProBook 450 G1                          | 3         | 0.63%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 3         | 0.63%   |
| HP Laptop 15-da0xxx                        | 3         | 0.63%   |
| HP 245 G6                                  | 3         | 0.63%   |
| Dell XPS 15 9550                           | 3         | 0.63%   |
| Dell Vostro 3400                           | 3         | 0.63%   |
| ASUS X555QG                                | 3         | 0.63%   |
| ASUS X505BP                                | 3         | 0.63%   |
| ASUS X455LJ                                | 3         | 0.63%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB     | 3         | 0.63%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA     | 3         | 0.63%   |
| ASUS VivoBook_ASUSLaptop X409DA_M409DA     | 3         | 0.63%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 3         | 0.63%   |
| Acer Aspire E5-575G                        | 3         | 0.63%   |
| Acer Aspire A515-51                        | 3         | 0.63%   |
| Acer Aspire 4750                           | 3         | 0.63%   |
| Toshiba Satellite U505                     | 2         | 0.42%   |
| Toshiba NB 105                             | 2         | 0.42%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.42%   |
| Lenovo V330-14IKB 81B0                     | 2         | 0.42%   |
| Lenovo ThinkPad X13 Gen 1 20UGS2B800       | 2         | 0.42%   |
| Lenovo ThinkBook 13s G2 ITL 20V9           | 2         | 0.42%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 2         | 0.42%   |
| Lenovo IdeaPad 110-14IBR 80T6              | 2         | 0.42%   |
| HP ProBook 440 G7                          | 2         | 0.42%   |
| HP ProBook 440 G3                          | 2         | 0.42%   |
| HP ProBook 440 G2                          | 2         | 0.42%   |
| HP Presario CQ43                           | 2         | 0.42%   |
| HP Pavilion Laptop 15-cw0xxx               | 2         | 0.42%   |
| HP Pavilion g4                             | 2         | 0.42%   |
| HP Pavilion dv4                            | 2         | 0.42%   |
| HP Pavilion 10 TS                          | 2         | 0.42%   |
| HP Laptop 14-ck0xxx                        | 2         | 0.42%   |
| HP Laptop 14-bp0xx                         | 2         | 0.42%   |
| HP ENVY 15                                 | 2         | 0.42%   |
| HP Compaq CQ45                             | 2         | 0.42%   |
| Dell Precision 3551                        | 2         | 0.42%   |
| Dell Inspiron 5423                         | 2         | 0.42%   |
| Dell Inspiron 3493                         | 2         | 0.42%   |
| Dell Inspiron 3480                         | 2         | 0.42%   |
| Dell Inspiron 1420                         | 2         | 0.42%   |
| ASUS X555LN                                | 2         | 0.42%   |
| ASUS X550ZE                                | 2         | 0.42%   |
| ASUS X542URR                               | 2         | 0.42%   |
| ASUS X455LD                                | 2         | 0.42%   |
| ASUS X441UVK                               | 2         | 0.42%   |
| ASUS X441NA                                | 2         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 46        | 9.66%   |
| Lenovo IdeaPad     | 32        | 6.72%   |
| Acer Aspire        | 31        | 6.51%   |
| Lenovo ThinkPad    | 30        | 6.3%    |
| HP Laptop          | 30        | 6.3%    |
| HP Pavilion        | 19        | 3.99%   |
| Dell Inspiron      | 17        | 3.57%   |
| Toshiba Satellite  | 16        | 3.36%   |
| HP ProBook         | 16        | 3.36%   |
| Dell Latitude      | 10        | 2.1%    |
| HP Compaq          | 6         | 1.26%   |
| Dell Vostro        | 6         | 1.26%   |
| ASUS ZenBook       | 6         | 1.26%   |
| Samsung 300E4C     | 5         | 1.05%   |
| HP 245             | 5         | 1.05%   |
| Dell XPS           | 5         | 1.05%   |
| Unknown            | 5         | 1.05%   |
| HP Notebook        | 4         | 0.84%   |
| HP EliteBook       | 4         | 0.84%   |
| HP 14              | 4         | 0.84%   |
| Lenovo G40-80      | 3         | 0.63%   |
| Lenovo G40-45      | 3         | 0.63%   |
| HP Presario        | 3         | 0.63%   |
| HP 240             | 3         | 0.63%   |
| ASUS X555QG        | 3         | 0.63%   |
| ASUS X505BP        | 3         | 0.63%   |
| ASUS X455LJ        | 3         | 0.63%   |
| ASUS TUF           | 3         | 0.63%   |
| ASUS ROG           | 3         | 0.63%   |
| Acer TravelMate    | 3         | 0.63%   |
| Acer Nitro         | 3         | 0.63%   |
| Toshiba NB         | 2         | 0.42%   |
| MSI PS63           | 2         | 0.42%   |
| MSI GE60           | 2         | 0.42%   |
| Lenovo Yoga        | 2         | 0.42%   |
| Lenovo Y520-15IKBN | 2         | 0.42%   |
| Lenovo V330-14IKB  | 2         | 0.42%   |
| Lenovo ThinkBook   | 2         | 0.42%   |
| Lenovo Legion      | 2         | 0.42%   |
| HP ENVY            | 2         | 0.42%   |
| Dell System        | 2         | 0.42%   |
| Dell Precision     | 2         | 0.42%   |
| ASUS X555LN        | 2         | 0.42%   |
| ASUS X550ZE        | 2         | 0.42%   |
| ASUS X542URR       | 2         | 0.42%   |
| ASUS X455LD        | 2         | 0.42%   |
| ASUS X441UVK       | 2         | 0.42%   |
| ASUS X441NA        | 2         | 0.42%   |
| ASUS X411UQ        | 2         | 0.42%   |
| Acer AOD255        | 2         | 0.42%   |
| VIT P2412          | 1         | 0.21%   |
| Toshiba PORTEGE    | 1         | 0.21%   |
| Timi A35S          | 1         | 0.21%   |
| Sony VPCEH37FJ     | 1         | 0.21%   |
| Sony VGN-SR51MF    | 1         | 0.21%   |
| Sony VGN-NR310FH   | 1         | 0.21%   |
| Sony VGN-FW170J    | 1         | 0.21%   |
| Sony VGN-CS240T    | 1         | 0.21%   |
| Sony SVF14A15CLB   | 1         | 0.21%   |
| Sony SVE14A27CXH   | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 65        | 13.66%  |
| 2017 | 53        | 11.13%  |
| 2018 | 52        | 10.92%  |
| 2015 | 36        | 7.56%   |
| 2012 | 36        | 7.56%   |
| 2011 | 33        | 6.93%   |
| 2020 | 31        | 6.51%   |
| 2014 | 31        | 6.51%   |
| 2010 | 30        | 6.3%    |
| 2013 | 26        | 5.46%   |
| 2009 | 21        | 4.41%   |
| 2016 | 19        | 3.99%   |
| 2021 | 18        | 3.78%   |
| 2008 | 13        | 2.73%   |
| 2007 | 7         | 1.47%   |
| 2006 | 3         | 0.63%   |
| 2022 | 2         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 476       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 423       | 88.49%  |
| Enabled  | 55        | 11.51%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 475       | 99.79%  |
| Yes  | 1         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 167       | 34.79%  |
| 3.01-4.0    | 133       | 27.71%  |
| 8.01-16.0   | 77        | 16.04%  |
| 16.01-24.0  | 42        | 8.75%   |
| 1.01-2.0    | 25        | 5.21%   |
| 2.01-3.0    | 16        | 3.33%   |
| 32.01-64.0  | 9         | 1.88%   |
| 24.01-32.0  | 5         | 1.04%   |
| 0.51-1.0    | 5         | 1.04%   |
| 64.01-256.0 | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 192       | 37.14%  |
| 2.01-3.0  | 150       | 29.01%  |
| 3.01-4.0  | 72        | 13.93%  |
| 4.01-8.0  | 51        | 9.86%   |
| 0.51-1.0  | 34        | 6.58%   |
| 8.01-16.0 | 16        | 3.09%   |
| 0.01-0.5  | 2         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 395       | 81.95%  |
| 2      | 79        | 16.39%  |
| 3      | 6         | 1.24%   |
| 4      | 2         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 310       | 64.99%  |
| Yes       | 167       | 35.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 392       | 82.01%  |
| No        | 86        | 17.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 471       | 98.95%  |
| No        | 5         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 381       | 79.87%  |
| No        | 96        | 20.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Colombia | 476       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Bogot??                     | 195       | 39.16%  |
| Medell??n                   | 61        | 12.25%  |
| Santiago de Cali            | 42        | 8.43%   |
| Barranquilla                | 23        | 4.62%   |
| Bucaramanga                 | 21        | 4.22%   |
| Pereira                     | 16        | 3.21%   |
| Cartagena                   | 15        | 3.01%   |
| Manizales                   | 11        | 2.21%   |
| Envigado                    | 8         | 1.61%   |
| Popay??n                    | 7         | 1.41%   |
| C??cuta                     | 7         | 1.41%   |
| Villavicencio               | 5         | 1%      |
| Santa Marta                 | 5         | 1%      |
| Ibague                      | 4         | 0.8%    |
| Fusagasuga                  | 4         | 0.8%    |
| Bello                       | 4         | 0.8%    |
| Armenia                     | 4         | 0.8%    |
| Tunja                       | 3         | 0.6%    |
| Sincelejo                   | 3         | 0.6%    |
| Monter??a                   | 3         | 0.6%    |
| Yopal                       | 2         | 0.4%    |
| Valledupar                  | 2         | 0.4%    |
| Soacha                      | 2         | 0.4%    |
| Sabaneta                    | 2         | 0.4%    |
| Rionegro                    | 2         | 0.4%    |
| Neiva                       | 2         | 0.4%    |
| Los Patios                  | 2         | 0.4%    |
| La Estrella                 | 2         | 0.4%    |
| Ipiales                     | 2         | 0.4%    |
| Chia                        | 2         | 0.4%    |
| Bogot????                   | 2         | 0.4%    |
| Barrancabermeja             | 2         | 0.4%    |
| Zarzal                      | 1         | 0.2%    |
| Villa de San Diego de Ubate | 1         | 0.2%    |
| Sogamoso                    | 1         | 0.2%    |
| San Gil                     | 1         | 0.2%    |
| San Andres de Palomo        | 1         | 0.2%    |
| San Agustin                 | 1         | 0.2%    |
| Pitalito                    | 1         | 0.2%    |
| Piendamo                    | 1         | 0.2%    |
| Pasto                       | 1         | 0.2%    |
| Palmira                     | 1         | 0.2%    |
| Mosquera                    | 1         | 0.2%    |
| Mit??                       | 1         | 0.2%    |
| Marinilla                   | 1         | 0.2%    |
| Magangu??                   | 1         | 0.2%    |
| Itaguei                     | 1         | 0.2%    |
| Giron                       | 1         | 0.2%    |
| Funza                       | 1         | 0.2%    |
| Floridablanca               | 1         | 0.2%    |
| Florencia                   | 1         | 0.2%    |
| Flandes                     | 1         | 0.2%    |
| Facatativ??                 | 1         | 0.2%    |
| El Socorro                  | 1         | 0.2%    |
| El Carmen de Viboral        | 1         | 0.2%    |
| Duitama                     | 1         | 0.2%    |
| Cota                        | 1         | 0.2%    |
| Corozal                     | 1         | 0.2%    |
| Copacabana                  | 1         | 0.2%    |
| Chiquinquira                | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 118       | 139    | 21.03%  |
| Toshiba                   | 89        | 101    | 15.86%  |
| WDC                       | 73        | 90     | 13.01%  |
| SanDisk                   | 33        | 36     | 5.88%   |
| Samsung Electronics       | 33        | 39     | 5.88%   |
| Kingston                  | 32        | 36     | 5.7%    |
| HGST                      | 29        | 38     | 5.17%   |
| A-DATA Technology         | 22        | 25     | 3.92%   |
| Hitachi                   | 19        | 23     | 3.39%   |
| Crucial                   | 19        | 19     | 3.39%   |
| Unknown                   | 17        | 17     | 3.03%   |
| SK hynix                  | 12        | 17     | 2.14%   |
| Intel                     | 12        | 13     | 2.14%   |
| China                     | 8         | 8      | 1.43%   |
| Micron Technology         | 6         | 6      | 1.07%   |
| Apple                     | 6         | 6      | 1.07%   |
| Realtek Semiconductor     | 4         | 5      | 0.71%   |
| Silicon Motion            | 3         | 3      | 0.53%   |
| LITEONIT                  | 3         | 3      | 0.53%   |
| Fujitsu                   | 3         | 3      | 0.53%   |
| Phison                    | 2         | 3      | 0.36%   |
| JMicron Technology        | 2         | 2      | 0.36%   |
| Hewlett-Packard           | 2         | 2      | 0.36%   |
| Zheino                    | 1         | 1      | 0.18%   |
| XPG                       | 1         | 1      | 0.18%   |
| Transcend                 | 1         | 1      | 0.18%   |
| SSSTC                     | 1         | 1      | 0.18%   |
| RDM-II                    | 1         | 2      | 0.18%   |
| PNY                       | 1         | 1      | 0.18%   |
| Netac                     | 1         | 1      | 0.18%   |
| Micron/Crucial Technology | 1         | 1      | 0.18%   |
| LITEON                    | 1         | 2      | 0.18%   |
| Lexar                     | 1         | 1      | 0.18%   |
| KIOXIA                    | 1         | 2      | 0.18%   |
| KingSpec                  | 1         | 1      | 0.18%   |
| Gigabyte Technology       | 1         | 1      | 0.18%   |
| ASMT                      | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 37        | 6.51%   |
| Toshiba MQ04ABF100 1TB              | 29        | 5.11%   |
| Toshiba MQ01ABF050 500GB            | 17        | 2.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 2.82%   |
| Toshiba MQ01ABD100 1TB              | 14        | 2.46%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 2.11%   |
| HGST HTS541010A9E680 1TB            | 8         | 1.41%   |
| Crucial CT240BX500SSD1 240GB        | 8         | 1.41%   |
| HGST HTS541010B7E610 1TB            | 7         | 1.23%   |
| WDC WD10SPZX-24Z10 1TB              | 6         | 1.06%   |
| Seagate ST500LT012-9WS142 500GB     | 6         | 1.06%   |
| SanDisk NVMe SSD Drive 512GB        | 6         | 1.06%   |
| HGST HTS545050A7E680 500GB          | 6         | 1.06%   |
| Seagate ST500LM030-1RK17D 500GB     | 5         | 0.88%   |
| SanDisk NVMe SSD Drive 256GB        | 5         | 0.88%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 0.88%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 0.88%   |
| Intel NVMe SSD Drive 512GB          | 5         | 0.88%   |
| WDC WD10SPZX-60Z10T0 1TB            | 4         | 0.7%    |
| SK hynix NVMe SSD Drive 256GB       | 4         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.7%    |
| SanDisk NVMe SSD Drive 1TB          | 4         | 0.7%    |
| A-DATA SU650 120GB SSD              | 4         | 0.7%    |
| WDC WD1600BEVT-75ZCT2 160GB         | 3         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB            | 3         | 0.53%   |
| Unknown MMC Card  64GB              | 3         | 0.53%   |
| Unknown MMC Card  32GB              | 3         | 0.53%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.53%   |
| Seagate ST9500420AS 500GB           | 3         | 0.53%   |
| Seagate ST9500325AS 500GB           | 3         | 0.53%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 0.53%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.53%   |
| SanDisk NVMe SSD Drive 500GB        | 3         | 0.53%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 0.53%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 0.53%   |
| Samsung NVMe SSD Drive 1024GB       | 3         | 0.53%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.53%   |
| Kingston SA400M8240G 240GB SSD      | 3         | 0.53%   |
| Kingston NVMe SSD Drive 512GB       | 3         | 0.53%   |
| Hitachi HTS543225L9A300 250GB       | 3         | 0.53%   |
| HGST HTS541010A7E630 1TB            | 3         | 0.53%   |
| Crucial CT500MX500SSD1 500GB        | 3         | 0.53%   |
| Crucial CT1000BX500SSD1 1TB         | 3         | 0.53%   |
| A-DATA SU630 480GB SSD              | 3         | 0.53%   |
| WDC WD5000LPVT-75G33T0 500GB        | 2         | 0.35%   |
| WDC WD10SPZX-75Z10T3 1TB            | 2         | 0.35%   |
| WDC WD10SPCX-24HWST1 1TB            | 2         | 0.35%   |
| WDC WD10JPVX-60JC3T1 1TB            | 2         | 0.35%   |
| Toshiba MK5076GSX 500GB             | 2         | 0.35%   |
| Toshiba MK3275GSX 320GB             | 2         | 0.35%   |
| Toshiba MK1652GSX 160GB             | 2         | 0.35%   |
| Toshiba HDWL110 1TB                 | 2         | 0.35%   |
| SK hynix NVMe SSD Drive 512GB       | 2         | 0.35%   |
| Seagate ST9320423AS 320GB           | 2         | 0.35%   |
| Seagate ST9320325AS 320GB           | 2         | 0.35%   |
| Seagate ST9250410AS 250GB           | 2         | 0.35%   |
| SanDisk SSD U100 24GB               | 2         | 0.35%   |
| SanDisk NVMe SSD Drive 1024GB       | 2         | 0.35%   |
| Realtek NVMe SSD Drive 512GB        | 2         | 0.35%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 118       | 139    | 36.09%  |
| Toshiba             | 85        | 95     | 25.99%  |
| WDC                 | 65        | 82     | 19.88%  |
| HGST                | 29        | 38     | 8.87%   |
| Hitachi             | 19        | 23     | 5.81%   |
| Samsung Electronics | 4         | 4      | 1.22%   |
| Fujitsu             | 3         | 3      | 0.92%   |
| Unknown             | 1         | 1      | 0.31%   |
| Phison              | 1         | 2      | 0.31%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 25     | 18.55%  |
| A-DATA Technology   | 20        | 23     | 16.13%  |
| Crucial             | 17        | 17     | 13.71%  |
| SanDisk             | 12        | 13     | 9.68%   |
| Samsung Electronics | 12        | 13     | 9.68%   |
| China               | 8         | 8      | 6.45%   |
| Toshiba             | 5         | 6      | 4.03%   |
| Intel               | 4         | 5      | 3.23%   |
| Apple               | 4         | 4      | 3.23%   |
| Micron Technology   | 3         | 3      | 2.42%   |
| LITEONIT            | 3         | 3      | 2.42%   |
| WDC                 | 2         | 2      | 1.61%   |
| SK hynix            | 2         | 5      | 1.61%   |
| Zheino              | 1         | 1      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| LITEON              | 1         | 2      | 0.81%   |
| Lexar               | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| Hewlett-Packard     | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 320       | 389    | 58.39%  |
| SSD     | 120       | 137    | 21.9%   |
| NVMe    | 88        | 104    | 16.06%  |
| MMC     | 16        | 16     | 2.92%   |
| Unknown | 4         | 5      | 0.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 403       | 520    | 77.95%  |
| NVMe | 88        | 104    | 17.02%  |
| MMC  | 16        | 16     | 3.09%   |
| SAS  | 10        | 11     | 1.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 251       | 310    | 57.97%  |
| 0.51-1.0   | 172       | 202    | 39.72%  |
| 1.01-2.0   | 9         | 12     | 2.08%   |
| 0          | 1         | 2      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 137       | 27.57%  |
| 101-250        | 130       | 26.16%  |
| 501-1000       | 107       | 21.53%  |
| 1-20           | 37        | 7.44%   |
| 51-100         | 37        | 7.44%   |
| 21-50          | 23        | 4.63%   |
| 1001-2000      | 18        | 3.62%   |
| Unknown        | 4         | 0.8%    |
| More than 3000 | 2         | 0.4%    |
| 2001-3000      | 2         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 214       | 41.8%   |
| 21-50     | 111       | 21.68%  |
| 101-250   | 72        | 14.06%  |
| 51-100    | 58        | 11.33%  |
| 251-500   | 32        | 6.25%   |
| 501-1000  | 20        | 3.91%   |
| Unknown   | 4         | 0.78%   |
| 1001-2000 | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 3      | 8.57%   |
| A-DATA Technology SU630 480GB SSD              | 2         | 2      | 5.71%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-22A0RT0 500GB                   | 1         | 1      | 2.86%   |
| WDC WD3200BPVT-24JJ5T0 320GB                   | 1         | 1      | 2.86%   |
| WDC WD3200BEKT-60F3T1 320GB                    | 1         | 1      | 2.86%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 2.86%   |
| WDC WD1600BEKT-60V5T1 160GB                    | 1         | 1      | 2.86%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 2.86%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.86%   |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 2.86%   |
| Toshiba MK5076GSX 500GB                        | 1         | 1      | 2.86%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 2.86%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 2.86%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 2.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 2.86%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.86%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.86%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 2      | 2.86%   |
| Hitachi HTS725032A9A364 320GB                  | 1         | 1      | 2.86%   |
| Hitachi HTS721080G9SA00 80GB                   | 1         | 1      | 2.86%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 2.86%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 2.86%   |
| Hitachi HTS543225L9A300 250GB                  | 1         | 5      | 2.86%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 2.86%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.86%   |
| Crucial M4-CT128M4SSD2 128GB                   | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 11        | 11     | 31.43%  |
| WDC               | 6         | 6      | 17.14%  |
| Hitachi           | 6         | 10     | 17.14%  |
| Toshiba           | 5         | 6      | 14.29%  |
| HGST              | 2         | 2      | 5.71%   |
| A-DATA Technology | 2         | 2      | 5.71%   |
| Micron Technology | 1         | 1      | 2.86%   |
| Intel             | 1         | 2      | 2.86%   |
| Crucial           | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 11        | 11     | 36.67%  |
| WDC     | 6         | 6      | 20%     |
| Hitachi | 6         | 10     | 20%     |
| Toshiba | 5         | 6      | 16.67%  |
| HGST    | 2         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 35     | 85.29%  |
| SSD  | 5         | 6      | 14.71%  |

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
| Detected | 343       | 473    | 69.57%  |
| Works    | 116       | 137    | 23.53%  |
| Malfunc  | 34        | 41     | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 321       | 60.45%  |
| AMD                            | 116       | 21.85%  |
| SanDisk                        | 26        | 4.9%    |
| Samsung Electronics            | 17        | 3.2%    |
| SK hynix                       | 10        | 1.88%   |
| Kingston Technology Company    | 8         | 1.51%   |
| Nvidia                         | 7         | 1.32%   |
| Realtek Semiconductor          | 6         | 1.13%   |
| Micron Technology              | 4         | 0.75%   |
| Silicon Motion                 | 3         | 0.56%   |
| VIA Technologies               | 2         | 0.38%   |
| Micron/Crucial Technology      | 2         | 0.38%   |
| Marvell Technology Group       | 2         | 0.38%   |
| Union Memory (Shenzhen)        | 1         | 0.19%   |
| Solid State Storage Technology | 1         | 0.19%   |
| Phison Electronics             | 1         | 0.19%   |
| KIOXIA                         | 1         | 0.19%   |
| Biwin Storage Technology       | 1         | 0.19%   |
| Apple                          | 1         | 0.19%   |
| ADATA Technology               | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 107       | 19.01%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 45        | 7.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 36        | 6.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 34        | 6.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 25        | 4.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 2.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 2.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 2.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 2.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 1.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 1.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 7         | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.24%   |
| Realtek Realtek Non-Volatile memory controller                                   | 6         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 1.07%   |
| SanDisk PC SN520 NVMe SSD                                                        | 5         | 0.89%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.89%   |
| Intel SSD 660P Series                                                            | 5         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 0.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.71%   |
| Micron Non-Volatile memory controller                                            | 4         | 0.71%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.71%   |
| SK hynix Gold P31 SSD                                                            | 3         | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.53%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.53%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.53%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.53%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.53%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3         | 0.53%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.36%   |
| VIA VT8237A SATA 2-Port Controller                                               | 2         | 0.36%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 0.36%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.36%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.36%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.36%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.36%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.36%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.36%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.36%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 2         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 391       | 71.48%  |
| NVMe | 87        | 15.9%   |
| RAID | 37        | 6.76%   |
| IDE  | 32        | 5.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 344       | 72.27%  |
| AMD    | 132       | 27.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 23        | 4.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 11        | 2.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 9         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 9         | 1.89%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 9         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 8         | 1.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 8         | 1.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 8         | 1.68%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 8         | 1.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 7         | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 7         | 1.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 6         | 1.26%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 6         | 1.26%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 1.26%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 6         | 1.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 5         | 1.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 5         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 1.05%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 5         | 1.05%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 5         | 1.05%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 4         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 4         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.84%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 4         | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 0.84%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.84%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 4         | 0.84%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 4         | 0.84%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 4         | 0.84%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 4         | 0.84%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 4         | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 4         | 0.84%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 4         | 0.84%   |
| AMD E-300 APU with Radeon HD Graphics           | 4         | 0.84%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 3         | 0.63%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 3         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 0.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 3         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 3         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 3         | 0.63%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 3         | 0.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 3         | 0.63%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 3         | 0.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 3         | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 0.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 3         | 0.63%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G   | 3         | 0.63%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics     | 3         | 0.63%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 3         | 0.63%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 2         | 0.42%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 2         | 0.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.42%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 2         | 0.42%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 2         | 0.42%   |
| Intel Core i7-3517U CPU @ 1.90GHz               | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 102       | 21.43%  |
| Intel Core i7                  | 89        | 18.7%   |
| Intel Core i3                  | 53        | 11.13%  |
| Intel Celeron                  | 34        | 7.14%   |
| AMD Ryzen 5                    | 33        | 6.93%   |
| Other                          | 27        | 5.67%   |
| Intel Atom                     | 15        | 3.15%   |
| Intel Core 2 Duo               | 14        | 2.94%   |
| AMD Ryzen 3                    | 11        | 2.31%   |
| AMD Ryzen 7                    | 9         | 1.89%   |
| AMD A12                        | 9         | 1.89%   |
| AMD E1                         | 8         | 1.68%   |
| AMD A10                        | 8         | 1.68%   |
| Intel Pentium                  | 7         | 1.47%   |
| AMD Ryzen 7 PRO                | 6         | 1.26%   |
| Intel Pentium Dual-Core        | 5         | 1.05%   |
| Intel Pentium Dual             | 5         | 1.05%   |
| AMD A8                         | 5         | 1.05%   |
| AMD A6                         | 5         | 1.05%   |
| AMD A4                         | 5         | 1.05%   |
| AMD E                          | 4         | 0.84%   |
| AMD E2                         | 3         | 0.63%   |
| Intel Core m5                  | 2         | 0.42%   |
| Intel Celeron M                | 2         | 0.42%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.42%   |
| AMD Ryzen 9                    | 2         | 0.42%   |
| AMD Athlon                     | 2         | 0.42%   |
| Intel Genuine                  | 1         | 0.21%   |
| Intel Core M                   | 1         | 0.21%   |
| Intel Core 2                   | 1         | 0.21%   |
| AMD V120                       | 1         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.21%   |
| AMD Mobile Sempron             | 1         | 0.21%   |
| AMD C-70                       | 1         | 0.21%   |
| AMD C-60                       | 1         | 0.21%   |
| AMD Athlon II Neo              | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 283       | 59.33%  |
| 4       | 143       | 29.98%  |
| 1       | 21        | 4.4%    |
| 8       | 16        | 3.35%   |
| 6       | 11        | 2.31%   |
| 14      | 2         | 0.42%   |
| Unknown | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 476       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 343       | 71.91%  |
| 1       | 132       | 27.67%  |
| 8       | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 441       | 91.68%  |
| Unknown        | 31        | 6.44%   |
| 64-bit         | 6         | 1.25%   |
| 32-bit         | 3         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 15.23%  |
| 0x306a9    | 30        | 6.17%   |
| 0x206a7    | 28        | 5.76%   |
| 0x806ea    | 24        | 4.94%   |
| 0x406e3    | 21        | 4.32%   |
| 0x40651    | 17        | 3.5%    |
| 0x06006705 | 17        | 3.5%    |
| 0x08108109 | 15        | 3.09%   |
| 0x306d4    | 14        | 2.88%   |
| 0x806ec    | 13        | 2.67%   |
| 0x08108102 | 13        | 2.67%   |
| 0x306c3    | 11        | 2.26%   |
| 0x806c1    | 10        | 2.06%   |
| 0x20655    | 10        | 2.06%   |
| 0x1067a    | 10        | 2.06%   |
| 0x906ea    | 9         | 1.85%   |
| 0x806e9    | 9         | 1.85%   |
| 0x706e5    | 9         | 1.85%   |
| 0x6fd      | 9         | 1.85%   |
| 0x406c4    | 9         | 1.85%   |
| 0x706a1    | 8         | 1.65%   |
| 0x806eb    | 7         | 1.44%   |
| 0x06006118 | 7         | 1.44%   |
| 0x05000119 | 7         | 1.44%   |
| 0x106ca    | 6         | 1.23%   |
| 0x08101007 | 6         | 1.23%   |
| 0x0600611a | 6         | 1.23%   |
| 0x30678    | 5         | 1.03%   |
| 0x20652    | 5         | 1.03%   |
| 0xa0652    | 4         | 0.82%   |
| 0x106e5    | 4         | 0.82%   |
| 0x106c2    | 4         | 0.82%   |
| 0x0a50000c | 4         | 0.82%   |
| 0x08600106 | 4         | 0.82%   |
| 0x0810100b | 4         | 0.82%   |
| 0x07030104 | 4         | 0.82%   |
| 0x06006704 | 4         | 0.82%   |
| 0x6f6      | 3         | 0.62%   |
| 0x506e3    | 3         | 0.62%   |
| 0x10676    | 3         | 0.62%   |
| 0x07030105 | 3         | 0.62%   |
| 0x0700010f | 3         | 0.62%   |
| 0x06003106 | 3         | 0.62%   |
| 0x906e9    | 2         | 0.41%   |
| 0x906a3    | 2         | 0.41%   |
| 0x706a8    | 2         | 0.41%   |
| 0x506c9    | 2         | 0.41%   |
| 0x406c3    | 2         | 0.41%   |
| 0x10661    | 2         | 0.41%   |
| 0x08608103 | 2         | 0.41%   |
| 0x08600104 | 2         | 0.41%   |
| 0x06001119 | 2         | 0.41%   |
| 0x6fa      | 1         | 0.21%   |
| 0x30673    | 1         | 0.21%   |
| 0x30661    | 1         | 0.21%   |
| 0x0700010b | 1         | 0.21%   |
| 0x06006115 | 1         | 0.21%   |
| 0x0600111f | 1         | 0.21%   |
| 0x03000027 | 1         | 0.21%   |
| 0x02000057 | 1         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 16.39%  |
| Excavator        | 35        | 7.35%   |
| Zen+             | 34        | 7.14%   |
| IvyBridge        | 34        | 7.14%   |
| SandyBridge      | 33        | 6.93%   |
| Haswell          | 32        | 6.72%   |
| Skylake          | 27        | 5.67%   |
| Westmere         | 19        | 3.99%   |
| Silvermont       | 18        | 3.78%   |
| Core             | 17        | 3.57%   |
| Penryn           | 14        | 2.94%   |
| Broadwell        | 14        | 2.94%   |
| Zen              | 11        | 2.31%   |
| TigerLake        | 11        | 2.31%   |
| IceLake          | 11        | 2.31%   |
| Bonnell          | 11        | 2.31%   |
| Goldmont plus    | 10        | 2.1%    |
| Zen 2            | 9         | 1.89%   |
| Puma             | 8         | 1.68%   |
| Bobcat           | 8         | 1.68%   |
| Zen 3            | 5         | 1.05%   |
| Jaguar           | 5         | 1.05%   |
| CometLake        | 5         | 1.05%   |
| Nehalem          | 4         | 0.84%   |
| K8 Hammer        | 4         | 0.84%   |
| Goldmont         | 4         | 0.84%   |
| Steamroller      | 3         | 0.63%   |
| Piledriver       | 3         | 0.63%   |
| Unknown          | 3         | 0.63%   |
| K10              | 2         | 0.42%   |
| Alderlake Hybrid | 2         | 0.42%   |
| K8 & K10 hybrid  | 1         | 0.21%   |
| K10 Llano        | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 328       | 56.65%  |
| AMD              | 144       | 24.87%  |
| Nvidia           | 105       | 18.13%  |
| VIA Technologies | 2         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 5.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 5.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 5.34%   |
| Intel UHD Graphics 620                                                                   | 21        | 3.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 3.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 3.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 2.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 2.75%   |
| Intel HD Graphics 620                                                                    | 14        | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 14        | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 12        | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.62%   |
| AMD Renoir                                                                               | 9         | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.29%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.13%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 7         | 1.13%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 7         | 1.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.97%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.81%   |
| Intel HD Graphics 530                                                                    | 5         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.81%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.65%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.65%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 4         | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.65%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.65%   |
| AMD Cezanne                                                                              | 4         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.49%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.49%   |
| Intel HD Graphics 630                                                                    | 3         | 0.49%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 3         | 0.49%   |
| AMD Lucienne                                                                             | 3         | 0.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.49%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 3         | 0.49%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 2         | 0.32%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.32%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.32%   |
| Nvidia GP107GLM [Quadro P620]                                                            | 2         | 0.32%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.32%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.32%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.32%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 2         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 232       | 48.74%  |
| 1 x AMD        | 99        | 20.8%   |
| Intel + Nvidia | 84        | 17.65%  |
| 2 x AMD        | 26        | 5.46%   |
| 1 x Nvidia     | 14        | 2.94%   |
| Intel + AMD    | 12        | 2.52%   |
| AMD + Nvidia   | 7         | 1.47%   |
| 1 x VIA        | 2         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 413       | 86.22%  |
| Proprietary | 45        | 9.39%   |
| Unknown     | 21        | 4.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 271       | 55.99%  |
| 1.01-2.0   | 85        | 17.56%  |
| 0.01-0.5   | 74        | 15.29%  |
| 3.01-4.0   | 25        | 5.17%   |
| 0.51-1.0   | 24        | 4.96%   |
| 5.01-6.0   | 3         | 0.62%   |
| 7.01-8.0   | 1         | 0.21%   |
| 8.01-16.0  | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 121       | 22.53%  |
| AU Optronics            | 96        | 17.88%  |
| BOE                     | 77        | 14.34%  |
| Samsung Electronics     | 61        | 11.36%  |
| LG Display              | 61        | 11.36%  |
| Goldstar                | 19        | 3.54%   |
| Chi Mei Optoelectronics | 12        | 2.23%   |
| PANDA                   | 10        | 1.86%   |
| Apple                   | 10        | 1.86%   |
| Dell                    | 9         | 1.68%   |
| Sharp                   | 7         | 1.3%    |
| Hewlett-Packard         | 7         | 1.3%    |
| InnoLux Display         | 5         | 0.93%   |
| Sony                    | 4         | 0.74%   |
| LG Philips              | 4         | 0.74%   |
| Lenovo                  | 4         | 0.74%   |
| InfoVision              | 4         | 0.74%   |
| AOC                     | 4         | 0.74%   |
| Acer                    | 4         | 0.74%   |
| CSO                     | 3         | 0.56%   |
| ViewSonic               | 2         | 0.37%   |
| HannStar                | 2         | 0.37%   |
| BenQ                    | 2         | 0.37%   |
| MSI                     | 1         | 0.19%   |
| LTM                     | 1         | 0.19%   |
| KTC                     | 1         | 0.19%   |
| KDC                     | 1         | 0.19%   |
| HannStar Display        | 1         | 0.19%   |
| eMachines               | 1         | 0.19%   |
| ELD                     | 1         | 0.19%   |
| CHO                     | 1         | 0.19%   |
| Ancor Communications    | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 15        | 2.77%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 12        | 2.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 10        | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 9         | 1.66%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 9         | 1.66%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                    | 8         | 1.48%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch           | 8         | 1.48%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch           | 8         | 1.48%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 7         | 1.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 6         | 1.11%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                 | 5         | 0.92%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 5         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch         | 5         | 0.92%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch           | 5         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch        | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch         | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 4         | 0.74%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                    | 4         | 0.74%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 4         | 0.74%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                    | 4         | 0.74%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 4         | 0.74%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                 | 3         | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 3         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 3         | 0.55%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch             | 3         | 0.55%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 3         | 0.55%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 3         | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch        | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch         | 3         | 0.55%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                   | 3         | 0.55%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                    | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch           | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 3         | 0.55%   |
| Sony TV SNYF301 1920x1080                                               | 2         | 0.37%   |
| Samsung Electronics U28E510 SAM0D63 3840x2160 607x345mm 27.5-inch       | 2         | 0.37%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch       | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch    | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch    | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2         | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2         | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 0.37%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                 | 2         | 0.37%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 2         | 0.37%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 2         | 0.37%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch             | 2         | 0.37%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch        | 2         | 0.37%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 295       | 57.73%  |
| 1920x1080 (FHD)   | 114       | 22.31%  |
| 1600x900 (HD+)    | 19        | 3.72%   |
| 3840x2160 (4K)    | 18        | 3.52%   |
| 1280x800 (WXGA)   | 17        | 3.33%   |
| 1440x900 (WXGA+)  | 10        | 1.96%   |
| 1024x600          | 7         | 1.37%   |
| 1920x1200 (WUXGA) | 6         | 1.17%   |
| 2560x1440 (QHD)   | 5         | 0.98%   |
| 1280x1024 (SXGA)  | 5         | 0.98%   |
| 2560x1600         | 3         | 0.59%   |
| 3456x2160         | 2         | 0.39%   |
| 2160x1440         | 2         | 0.39%   |
| 1360x768          | 2         | 0.39%   |
| 3840x1080         | 1         | 0.2%    |
| 3440x1440         | 1         | 0.2%    |
| 2880x1800         | 1         | 0.2%    |
| 2560x1080         | 1         | 0.2%    |
| 2256x1504         | 1         | 0.2%    |
| 1024x768 (XGA)    | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 168       | 31.05%  |
| 13      | 129       | 23.84%  |
| 14      | 104       | 19.22%  |
| 17      | 21        | 3.88%   |
| 21      | 17        | 3.14%   |
| 23      | 14        | 2.59%   |
| 11      | 12        | 2.22%   |
| 12      | 10        | 1.85%   |
| 27      | 9         | 1.66%   |
| 24      | 7         | 1.29%   |
| 10      | 7         | 1.29%   |
| 18      | 6         | 1.11%   |
| 19      | 5         | 0.92%   |
| 72      | 4         | 0.74%   |
| 31      | 4         | 0.74%   |
| 20      | 4         | 0.74%   |
| 47      | 3         | 0.55%   |
| 84      | 2         | 0.37%   |
| 34      | 2         | 0.37%   |
| 8       | 2         | 0.37%   |
| Unknown | 2         | 0.37%   |
| 61      | 1         | 0.18%   |
| 54      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 43      | 1         | 0.18%   |
| 40      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 26      | 1         | 0.18%   |
| 22      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 374       | 70.04%  |
| 201-300     | 53        | 9.93%   |
| 401-500     | 33        | 6.18%   |
| 501-600     | 25        | 4.68%   |
| 351-400     | 19        | 3.56%   |
| 601-700     | 9         | 1.69%   |
| 1501-2000   | 6         | 1.12%   |
| 1001-1500   | 6         | 1.12%   |
| 701-800     | 3         | 0.56%   |
| 101-200     | 2         | 0.37%   |
| Unknown     | 2         | 0.37%   |
| 801-900     | 1         | 0.19%   |
| 901-1000    | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 419       | 88.4%   |
| 16/10   | 41        | 8.65%   |
| 5/4     | 5         | 1.05%   |
| 3/2     | 4         | 0.84%   |
| 21/9    | 2         | 0.42%   |
| 4/3     | 1         | 0.21%   |
| 32/9    | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 214       | 39.78%  |
| 101-110        | 168       | 31.23%  |
| 201-250        | 31        | 5.76%   |
| 71-80          | 17        | 3.16%   |
| 51-60          | 12        | 2.23%   |
| 121-130        | 12        | 2.23%   |
| 151-200        | 11        | 2.04%   |
| 141-150        | 11        | 2.04%   |
| 61-70          | 10        | 1.86%   |
| 301-350        | 10        | 1.86%   |
| More than 1000 | 8         | 1.49%   |
| 351-500        | 7         | 1.3%    |
| 41-50          | 7         | 1.3%    |
| 501-1000       | 6         | 1.12%   |
| 251-300        | 5         | 0.93%   |
| 131-140        | 4         | 0.74%   |
| 1-40           | 2         | 0.37%   |
| Unknown        | 2         | 0.37%   |
| 111-120        | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 298       | 56.65%  |
| 121-160       | 113       | 21.48%  |
| 51-100        | 73        | 13.88%  |
| 161-240       | 18        | 3.42%   |
| More than 240 | 11        | 2.09%   |
| 1-50          | 11        | 2.09%   |
| Unknown       | 2         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 378       | 76.99%  |
| 2     | 87        | 17.72%  |
| 0     | 21        | 4.28%   |
| 3     | 4         | 0.81%   |
| 4     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 312       | 40.89%  |
| Intel                           | 162       | 21.23%  |
| Qualcomm Atheros                | 141       | 18.48%  |
| Broadcom                        | 48        | 6.29%   |
| Broadcom Limited                | 22        | 2.88%   |
| Ralink                          | 11        | 1.44%   |
| TP-Link                         | 9         | 1.18%   |
| Marvell Technology Group        | 9         | 1.18%   |
| Nvidia                          | 6         | 0.79%   |
| Samsung Electronics             | 5         | 0.66%   |
| Ralink Technology               | 5         | 0.66%   |
| Qualcomm Atheros Communications | 4         | 0.52%   |
| MediaTek                        | 4         | 0.52%   |
| Huawei Technologies             | 4         | 0.52%   |
| ASIX Electronics                | 3         | 0.39%   |
| Xiaomi                          | 2         | 0.26%   |
| VIA Technologies                | 2         | 0.26%   |
| D-Link System                   | 2         | 0.26%   |
| T & A Mobile Phones             | 1         | 0.13%   |
| STMicroelectronics              | 1         | 0.13%   |
| Quanta                          | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| Prolific Technology             | 1         | 0.13%   |
| Motorola PCS                    | 1         | 0.13%   |
| Lenovo                          | 1         | 0.13%   |
| JMicron Technology              | 1         | 0.13%   |
| Google                          | 1         | 0.13%   |
| DisplayLink                     | 1         | 0.13%   |
| Dell                            | 1         | 0.13%   |
| 3Com                            | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 192       | 21.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 69        | 7.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 4.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 32        | 3.5%    |
| Intel Wireless 8265 / 8275                                              | 25        | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 20        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.2%    |
| Intel Wireless 7260                                                     | 10        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.77%   |
| Intel Wireless 8260                                                     | 7         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.66%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.66%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.55%   |
| Intel Wireless 7265                                                     | 5         | 0.55%   |
| Intel Wireless 3160                                                     | 5         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 5         | 0.55%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 5         | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 4         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.44%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.44%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.44%   |
| Huawei COL-L29                                                          | 4         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.33%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.33%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 3         | 0.33%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 3         | 0.33%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 31.46%  |
| Realtek Semiconductor           | 129       | 25.85%  |
| Qualcomm Atheros                | 123       | 24.65%  |
| Broadcom                        | 36        | 7.21%   |
| Broadcom Limited                | 16        | 3.21%   |
| Ralink                          | 11        | 2.2%    |
| TP-Link                         | 9         | 1.8%    |
| Ralink Technology               | 5         | 1%      |
| Qualcomm Atheros Communications | 4         | 0.8%    |
| MediaTek                        | 3         | 0.6%    |
| D-Link System                   | 2         | 0.4%    |
| Qualcomm                        | 1         | 0.2%    |
| Marvell Technology Group        | 1         | 0.2%    |
| Dell                            | 1         | 0.2%    |
| 3Com                            | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 7.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 32        | 6.39%   |
| Intel Wireless 8265 / 8275                                              | 25        | 4.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 4.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 20        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 3.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 3.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.59%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 2.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 2.2%    |
| Intel Wireless 7260                                                     | 10        | 2%      |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.4%    |
| Intel Wireless 8260                                                     | 7         | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 1.2%    |
| Intel Centrino Wireless-N 2230                                          | 6         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1%      |
| Intel Wireless 7265                                                     | 5         | 1%      |
| Intel Wireless 3160                                                     | 5         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1%      |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 5         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.8%    |
| Realtek 802.11ac NIC                                                    | 3         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.6%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.6%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.4%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.4%    |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter              | 2         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.4%    |
| Intel Wireless-AC 9260                                                  | 2         | 0.4%    |
| Intel WiFi Link 5100                                                    | 2         | 0.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.4%    |
| Intel Centrino Wireless-N 130                                           | 2         | 0.4%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.4%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 278       | 68.14%  |
| Intel                    | 38        | 9.31%   |
| Qualcomm Atheros         | 33        | 8.09%   |
| Broadcom                 | 16        | 3.92%   |
| Marvell Technology Group | 8         | 1.96%   |
| Nvidia                   | 6         | 1.47%   |
| Broadcom Limited         | 6         | 1.47%   |
| Samsung Electronics      | 5         | 1.23%   |
| Huawei Technologies      | 4         | 0.98%   |
| ASIX Electronics         | 3         | 0.74%   |
| Xiaomi                   | 2         | 0.49%   |
| VIA Technologies         | 2         | 0.49%   |
| T & A Mobile Phones      | 1         | 0.25%   |
| Quanta                   | 1         | 0.25%   |
| Prolific Technology      | 1         | 0.25%   |
| MediaTek                 | 1         | 0.25%   |
| Lenovo                   | 1         | 0.25%   |
| JMicron Technology       | 1         | 0.25%   |
| DisplayLink              | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 192       | 46.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 69        | 16.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.46%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.98%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.98%   |
| Huawei COL-L29                                                    | 4         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.73%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.73%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.73%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.49%   |
| Nvidia MCP67 Ethernet                                             | 2         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.49%   |
| ASIX AX88772B                                                     | 2         | 0.49%   |
| T & A Mobile Phones A507DL                                        | 1         | 0.24%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.24%   |
| Quanta HSUSB Device                                               | 1         | 0.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.24%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.24%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.24%   |
| Prolific PL25A1 Host-Host Bridge                                  | 1         | 0.24%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.24%   |
| MediaTek TECNO SPARK 6 Go                                         | 1         | 0.24%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.24%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.24%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.24%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.24%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.24%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.24%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.24%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.24%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.24%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.24%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.24%   |
| DisplayLink HP Port Replicator (Composite Device)                 | 1         | 0.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.24%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 471       | 54.45%  |
| Ethernet | 391       | 45.2%   |
| Unknown  | 2         | 0.23%   |
| Modem    | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 380       | 74.36%  |
| Ethernet | 130       | 25.44%  |
| Unknown  | 1         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 364       | 76.47%  |
| 1     | 108       | 22.69%  |
| 0     | 3         | 0.63%   |
| 3     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 449       | 93.74%  |
| Yes  | 30        | 6.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 33.07%  |
| Realtek Semiconductor           | 69        | 17.97%  |
| IMC Networks                    | 49        | 12.76%  |
| Qualcomm Atheros Communications | 41        | 10.68%  |
| Lite-On Technology              | 26        | 6.77%   |
| Broadcom                        | 17        | 4.43%   |
| Foxconn / Hon Hai               | 10        | 2.6%    |
| Cambridge Silicon Radio         | 8         | 2.08%   |
| Apple                           | 8         | 2.08%   |
| Ralink                          | 7         | 1.82%   |
| Hewlett-Packard                 | 6         | 1.56%   |
| Toshiba                         | 4         | 1.04%   |
| Foxconn International           | 3         | 0.78%   |
| Alps Electric                   | 3         | 0.78%   |
| Realtek                         | 2         | 0.52%   |
| Dell                            | 2         | 0.52%   |
| MediaTek                        | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 57        | 14.84%  |
| Realtek  Bluetooth 4.2 Adapter                              | 38        | 9.9%    |
| IMC Networks Bluetooth Radio                                | 27        | 7.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 25        | 6.51%   |
| Realtek Bluetooth Radio                                     | 21        | 5.47%   |
| Qualcomm Atheros  Bluetooth Device                          | 21        | 5.47%   |
| Intel Bluetooth Device                                      | 17        | 4.43%   |
| IMC Networks Bluetooth Device                               | 15        | 3.91%   |
| Intel AX200 Bluetooth                                       | 13        | 3.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 9         | 2.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 9         | 2.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 2.08%   |
| Ralink RT3290 Bluetooth                                     | 7         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 7         | 1.82%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                | 6         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 5         | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 1.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 4         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 1.04%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 4         | 1.04%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 1.04%   |
| Apple Bluetooth Host Controller                             | 4         | 1.04%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.78%   |
| Lite-On Bluetooth Device                                    | 3         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module           | 3         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                          | 3         | 0.78%   |
| Broadcom BCM20702A0                                         | 3         | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 0.78%   |
| Apple Bluetooth USB Host Controller                         | 3         | 0.78%   |
| Alps Electric BCM2046 Bluetooth Device                      | 3         | 0.78%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 0.52%   |
| Realtek Bluetooth Radio                                     | 2         | 0.52%   |
| Lite-On Bluetooth Radio                                     | 2         | 0.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.52%   |
| IMC Networks Wireless_Device                                | 2         | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 2         | 0.52%   |
| Dell Wireless 360 Bluetooth                                 | 2         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.52%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                      | 2         | 0.52%   |
| Toshiba RT Bluetooth Radio                                  | 1         | 0.26%   |
| Toshiba Bluetooth Device                                    | 1         | 0.26%   |
| Toshiba BCM43142A0                                          | 1         | 0.26%   |
| Toshiba Askey Bluetooth Module                              | 1         | 0.26%   |
| Realtek CSR BS8510                                          | 1         | 0.26%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.26%   |
| MediaTek Wireless_Device                                    | 1         | 0.26%   |
| Lite-On BCM20702A0                                          | 1         | 0.26%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.26%   |
| Intel AX210 Bluetooth                                       | 1         | 0.26%   |
| IMC Networks Bluetooth USB Host Controller                  | 1         | 0.26%   |
| IMC Networks Bluetooth                                      | 1         | 0.26%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.26%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.26%   |
| Foxconn / Hon Hai BT                                        | 1         | 0.26%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.26%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.26%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 333       | 62.59%  |
| AMD                       | 134       | 25.19%  |
| Nvidia                    | 42        | 7.89%   |
| Realtek Semiconductor     | 3         | 0.56%   |
| Logitech                  | 3         | 0.56%   |
| C-Media Electronics       | 3         | 0.56%   |
| VIA Technologies          | 2         | 0.38%   |
| Plantronics               | 2         | 0.38%   |
| JMTek                     | 2         | 0.38%   |
| Texas Instruments         | 1         | 0.19%   |
| Sennheiser Communications | 1         | 0.19%   |
| Microsoft                 | 1         | 0.19%   |
| Generalplus Technology    | 1         | 0.19%   |
| Corsair                   | 1         | 0.19%   |
| BEHRINGER International   | 1         | 0.19%   |
| Astro Gaming              | 1         | 0.19%   |
| Apple                     | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 61        | 8.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 59        | 8.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 44        | 6.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 41        | 5.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 35        | 5%      |
| AMD Kabini HDMI/DP Audio                                                                          | 27        | 3.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 3.71%   |
| AMD FCH Azalia Controller                                                                         | 24        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 23        | 3.29%   |
| AMD High Definition Audio Controller                                                              | 21        | 3%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 2.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.71%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.57%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.43%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.43%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.43%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.29%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.29%   |
| Nvidia MCP67 High Definition Audio                                                                | 2         | 0.29%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.29%   |
| Nvidia Audio device                                                                               | 2         | 0.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.29%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.29%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.14%   |
| Sennheiser Communications SC60 for Lync                                                           | 1         | 0.14%   |
| Plantronics C725                                                                                  | 1         | 0.14%   |
| Plantronics Blackwire 5220 Series                                                                 | 1         | 0.14%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.14%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.14%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.14%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.14%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 30.52%  |
| SK hynix            | 57        | 22.89%  |
| Micron Technology   | 39        | 15.66%  |
| Kingston            | 16        | 6.43%   |
| Unknown             | 14        | 5.62%   |
| A-DATA Technology   | 12        | 4.82%   |
| Ramaxel Technology  | 7         | 2.81%   |
| Elpida              | 5         | 2.01%   |
| Crucial             | 5         | 2.01%   |
| Avant               | 3         | 1.2%    |
| Apacer              | 3         | 1.2%    |
| Nanya Technology    | 2         | 0.8%    |
| Unknown (08AE)      | 1         | 0.4%    |
| Team                | 1         | 0.4%    |
| Qimonda             | 1         | 0.4%    |
| PUSKILL             | 1         | 0.4%    |
| PNY                 | 1         | 0.4%    |
| Goldkey             | 1         | 0.4%    |
| ChangXin Memory     | 1         | 0.4%    |
| Centon              | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| Unknown             | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 8         | 3.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 7         | 2.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 6         | 2.33%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 5         | 1.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 1.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 5         | 1.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 3         | 1.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.17%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 1.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.17%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 3         | 1.17%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 2         | 0.78%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 2         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 2         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 2         | 0.78%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 0.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 2         | 0.78%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s          | 2         | 0.78%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 2         | 0.78%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s       | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.78%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 2         | 0.78%   |
| Micron RAM 4KTF25664HZ-1G9P1 2GB SODIMM DDR3 1776MT/s          | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| Apacer RAM 76.A302G.D330B 2GB SODIMM DDR4 2400MT/s             | 2         | 0.78%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.78%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DRAM 533MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.39%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DRAM 533MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 0.39%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 0.39%   |
| Unknown (08AE) RAM Module 8192MB SODIMM DDR3 1333MT/s          | 1         | 0.39%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s          | 1         | 0.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 0.39%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                | 1         | 0.39%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1067MT/s                | 1         | 0.39%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s           | 1         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s       | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 91        | 46.91%  |
| DDR3    | 73        | 37.63%  |
| DDR2    | 11        | 5.67%   |
| LPDDR4  | 9         | 4.64%   |
| SDRAM   | 4         | 2.06%   |
| LPDDR3  | 4         | 2.06%   |
| DRAM    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 181       | 94.27%  |
| Row Of Chips | 11        | 5.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 100       | 43.67%  |
| 8192  | 63        | 27.51%  |
| 2048  | 32        | 13.97%  |
| 16384 | 19        | 8.3%    |
| 1024  | 11        | 4.8%    |
| 32768 | 3         | 1.31%   |
| 512   | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 56        | 26.54%  |
| 1600    | 52        | 24.64%  |
| 3200    | 19        | 9%      |
| 2400    | 18        | 8.53%   |
| 1334    | 11        | 5.21%   |
| 2133    | 8         | 3.79%   |
| 3266    | 7         | 3.32%   |
| 1333    | 6         | 2.84%   |
| 1067    | 5         | 2.37%   |
| Unknown | 5         | 2.37%   |
| 4267    | 4         | 1.9%    |
| 667     | 4         | 1.9%    |
| 4199    | 3         | 1.42%   |
| 800     | 3         | 1.42%   |
| 1776    | 2         | 0.95%   |
| 1066    | 2         | 0.95%   |
| 533     | 2         | 0.95%   |
| 4800    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 3733    | 1         | 0.47%   |
| 975     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L210 Series          | 1         | 33.33%  |
| Samsung M2020 Series             | 1         | 33.33%  |
| HP LaserJet Professional P 1102w | 1         | 33.33%  |

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
| Chicony Electronics                    | 95        | 21.3%   |
| IMC Networks                           | 89        | 19.96%  |
| Realtek Semiconductor                  | 35        | 7.85%   |
| Acer                                   | 32        | 7.17%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 6.73%   |
| Microdia                               | 26        | 5.83%   |
| Sunplus Innovation Technology          | 21        | 4.71%   |
| Quanta                                 | 19        | 4.26%   |
| Lite-On Technology                     | 17        | 3.81%   |
| Silicon Motion                         | 14        | 3.14%   |
| Syntek                                 | 12        | 2.69%   |
| Suyin                                  | 12        | 2.69%   |
| Ricoh                                  | 5         | 1.12%   |
| Logitech                               | 5         | 1.12%   |
| Apple                                  | 5         | 1.12%   |
| Alcor Micro                            | 5         | 1.12%   |
| ALi                                    | 4         | 0.9%    |
| Z-Star Microelectronics                | 3         | 0.67%   |
| Importek                               | 3         | 0.67%   |
| Samsung Electronics                    | 2         | 0.45%   |
| OmniVision Technologies                | 2         | 0.45%   |
| Lenovo                                 | 2         | 0.45%   |
| Sunplus Technology                     | 1         | 0.22%   |
| Sonix Technology                       | 1         | 0.22%   |
| Pixart Imaging                         | 1         | 0.22%   |
| KYE Systems (Mouse Systems)            | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| Genesys Logic                          | 1         | 0.22%   |
| Arkmicro Technologies                  | 1         | 0.22%   |
| Alcorlink                              | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 41        | 9.19%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 23        | 5.16%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 14        | 3.14%   |
| Chicony Integrated Camera                                      | 12        | 2.69%   |
| Microdia Integrated_Webcam_HD                                  | 10        | 2.24%   |
| Chicony HP TrueVision HD Camera                                | 9         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 8         | 1.79%   |
| Lite-On HP Webcam                                              | 7         | 1.57%   |
| Chicony Lenovo EasyCamera                                      | 7         | 1.57%   |
| Acer Integrated Camera                                         | 7         | 1.57%   |
| Realtek USB Camera                                             | 6         | 1.35%   |
| IMC Networks Integrated Camera                                 | 6         | 1.35%   |
| Chicony HP Webcam                                              | 6         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 6         | 1.35%   |
| Syntek Integrated Camera                                       | 5         | 1.12%   |
| Acer Lenovo EasyCamera                                         | 5         | 1.12%   |
| Syntek EasyCamera                                              | 4         | 0.9%    |
| Suyin 1.3M HD WebCam                                           | 4         | 0.9%    |
| Sunplus Integrated_Webcam_HD                                   | 4         | 0.9%    |
| Sunplus HD WebCam                                              | 4         | 0.9%    |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.9%    |
| Realtek HD WebCam                                              | 4         | 0.9%    |
| Quanta HP Webcam                                               | 4         | 0.9%    |
| Lite-On HP HD Camera                                           | 4         | 0.9%    |
| IMC Networks VGA UVC WebCam                                    | 4         | 0.9%    |
| IMC Networks EasyCamera                                        | 4         | 0.9%    |
| Chicony HD WebCam                                              | 4         | 0.9%    |
| Acer HD Webcam                                                 | 4         | 0.9%    |
| Syntek Lenovo EasyCamera                                       | 3         | 0.67%   |
| Sunplus ASUS Webcam                                            | 3         | 0.67%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.67%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.67%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 0.67%   |
| Realtek HP Truevision HD                                       | 3         | 0.67%   |
| Quanta VGA WebCam                                              | 3         | 0.67%   |
| Quanta HD Webcam                                               | 3         | 0.67%   |
| Microdia Integrated Webcam                                     | 3         | 0.67%   |
| Lite-On Integrated Camera                                      | 3         | 0.67%   |
| Chicony HP HD Camera                                           | 3         | 0.67%   |
| Chicony EasyCamera                                             | 3         | 0.67%   |
| Chicony CNF9055 Toshiba Webcam                                 | 3         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 3         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 3         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 3         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 0.67%   |
| ALi Gateway Webcam                                             | 3         | 0.67%   |
| Acer EasyCamera                                                | 3         | 0.67%   |
| Z-Star Webcam                                                  | 2         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 2         | 0.45%   |
| Suyin HD WebCam                                                | 2         | 0.45%   |
| Silicon Motion WebCam SC-03FFL11939N                           | 2         | 0.45%   |
| Silicon Motion HP Webcam-50                                    | 2         | 0.45%   |
| Silicon Motion HP Webcam                                       | 2         | 0.45%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 0.45%   |
| Realtek Integrated Webcam                                      | 2         | 0.45%   |
| Realtek Asus laptop camera                                     | 2         | 0.45%   |
| Realtek Acer 640 x 480 laptop camera                           | 2         | 0.45%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 0.45%   |
| Quanta HD User Facing                                          | 2         | 0.45%   |
| OmniVision OV2640 Webcam                                       | 2         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 37.88%  |
| Synaptics                  | 15        | 22.73%  |
| Elan Microelectronics      | 11        | 16.67%  |
| Shenzhen Goodix Technology | 6         | 9.09%   |
| Upek                       | 4         | 6.06%   |
| LighTuning Technology      | 2         | 3.03%   |
| AuthenTec                  | 2         | 3.03%   |
| STMicroelectronics         | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 11        | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 7.58%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.58%   |
| Unknown                                                                    | 5         | 7.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 6.06%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 3.03%   |
| Synaptics  WBDI                                                            | 2         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.52%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.52%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.52%   |
| Synaptics WBDI Device                                                      | 1         | 1.52%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.52%   |
| AuthenTec AES2810                                                          | 1         | 1.52%   |
| AuthenTec AES1600                                                          | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 35.71%  |
| Upek                  | 2         | 14.29%  |
| O2 Micro              | 2         | 14.29%  |
| Lenovo                | 2         | 14.29%  |
| Alcor Micro           | 2         | 14.29%  |
| Gemalto (was Gemplus) | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 4         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 14.29%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 7.14%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 298       | 61.7%   |
| 1     | 155       | 32.09%  |
| 2     | 29        | 6%      |
| 7     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 31.13%  |
| Net/wireless             | 45        | 21.23%  |
| Graphics card            | 35        | 16.51%  |
| Multimedia controller    | 20        | 9.43%   |
| Chipcard                 | 14        | 6.6%    |
| Bluetooth                | 11        | 5.19%   |
| Communication controller | 4         | 1.89%   |
| Camera                   | 4         | 1.89%   |
| Storage                  | 3         | 1.42%   |
| Sound                    | 3         | 1.42%   |
| Card reader              | 3         | 1.42%   |
| Net/ethernet             | 2         | 0.94%   |
| Flash memory             | 1         | 0.47%   |
| Firewire controller      | 1         | 0.47%   |

