Peppermint - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Peppermint.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Peppermint/Desktop/README.md) and [notebooks](/Dist/Peppermint/Notebook/README.md).

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

Total: 399

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [4b63d98b33](https://linux-hardware.org/?probe=4b63d98b33) | May 16, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [271af2d869](https://linux-hardware.org/?probe=271af2d869) | Mar 30, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [e6a885c5df](https://linux-hardware.org/?probe=e6a885c5df) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b8783a8415](https://linux-hardware.org/?probe=b8783a8415) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b0d58c6895](https://linux-hardware.org/?probe=b0d58c6895) | Mar 12, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Dell          | Latitude D630               | Notebook    | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Dell          | Latitude D630               | Notebook    | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Medion        | WIM2160                     | Notebook    | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| Medion        | WIM2160                     | Notebook    | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [3cdc62c355](https://linux-hardware.org/?probe=3cdc62c355) | Jan 05, 2022 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | Notebook    | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| Lenovo        | G575 4383                   | Notebook    | [ef4143d3b6](https://linux-hardware.org/?probe=ef4143d3b6) | Dec 22, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | Notebook    | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [9b874becf9](https://linux-hardware.org/?probe=9b874becf9) | Dec 01, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [ae2963be56](https://linux-hardware.org/?probe=ae2963be56) | Dec 01, 2021 |
| Acer          | Aspire 4810T                | Notebook    | [2f0aa07be8](https://linux-hardware.org/?probe=2f0aa07be8) | Nov 26, 2021 |
| ECS           | 945GCT-M3                   | Desktop     | [a81a27ac47](https://linux-hardware.org/?probe=a81a27ac47) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| ECS           | Nettle3                     | Desktop     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [58d4a2dd00](https://linux-hardware.org/?probe=58d4a2dd00) | Nov 10, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [15f9885d1f](https://linux-hardware.org/?probe=15f9885d1f) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| Intel         | H61                         | Desktop     | [f1d3a975c0](https://linux-hardware.org/?probe=f1d3a975c0) | Oct 26, 2021 |
| Toshiba       | Satellite L750D             | Notebook    | [e24684255d](https://linux-hardware.org/?probe=e24684255d) | Oct 26, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | Notebook    | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| ECS           | MCP61PM-GM                  | Desktop     | [1d13b80285](https://linux-hardware.org/?probe=1d13b80285) | Oct 13, 2021 |
| ASRock        | P4VM8                       | Desktop     | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| ASRock        | P4VM8                       | Desktop     | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [7f51bdb2d1](https://linux-hardware.org/?probe=7f51bdb2d1) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [00f01e8929](https://linux-hardware.org/?probe=00f01e8929) | Oct 08, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [be79dd5979](https://linux-hardware.org/?probe=be79dd5979) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [c5492b6d2f](https://linux-hardware.org/?probe=c5492b6d2f) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [522a137a4e](https://linux-hardware.org/?probe=522a137a4e) | Oct 05, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | Notebook    | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | Notebook    | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [0a9b2f9147](https://linux-hardware.org/?probe=0a9b2f9147) | Aug 08, 2021 |
| HP            | 2AE3                        | Desktop     | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [827993d9c3](https://linux-hardware.org/?probe=827993d9c3) | Jul 17, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| Dell          | Precision M4600             | Notebook    | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [9ba35acb61](https://linux-hardware.org/?probe=9ba35acb61) | Jun 24, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [399e422d5b](https://linux-hardware.org/?probe=399e422d5b) | Jun 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09171395a9](https://linux-hardware.org/?probe=09171395a9) | Jun 22, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdbc4c8c02](https://linux-hardware.org/?probe=cdbc4c8c02) | Jun 22, 2021 |
| Toshiba       | NB500                       | Notebook    | [e5095d1545](https://linux-hardware.org/?probe=e5095d1545) | Jun 21, 2021 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6d6430f8ff](https://linux-hardware.org/?probe=6d6430f8ff) | Jun 18, 2021 |
| Acer          | AOA150                      | Notebook    | [7cbadcfcce](https://linux-hardware.org/?probe=7cbadcfcce) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [0a57436b83](https://linux-hardware.org/?probe=0a57436b83) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [be659779e6](https://linux-hardware.org/?probe=be659779e6) | Jun 13, 2021 |
| HP            | Mini 110-1100               | Notebook    | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | Notebook    | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| LincPlus      | P1                          | Notebook    | [4b49a81a7c](https://linux-hardware.org/?probe=4b49a81a7c) | May 30, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [9c2c0af05f](https://linux-hardware.org/?probe=9c2c0af05f) | May 27, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [0a5e45a21e](https://linux-hardware.org/?probe=0a5e45a21e) | May 27, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| LincPlus      | P1                          | Notebook    | [bac5471f0f](https://linux-hardware.org/?probe=bac5471f0f) | May 15, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| Acer          | Extensa 5510                | Notebook    | [8e9e536486](https://linux-hardware.org/?probe=8e9e536486) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | Notebook    | [12b76c8bca](https://linux-hardware.org/?probe=12b76c8bca) | Apr 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [d54424038e](https://linux-hardware.org/?probe=d54424038e) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [562d38cca5](https://linux-hardware.org/?probe=562d38cca5) | Apr 18, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [87befc0401](https://linux-hardware.org/?probe=87befc0401) | Apr 16, 2021 |
| Pegatron      | Benicia                     | Desktop     | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [56c5cc70d1](https://linux-hardware.org/?probe=56c5cc70d1) | Apr 07, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [71e906faa3](https://linux-hardware.org/?probe=71e906faa3) | Apr 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [a72bb094fd](https://linux-hardware.org/?probe=a72bb094fd) | Mar 26, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [14c65221b8](https://linux-hardware.org/?probe=14c65221b8) | Mar 20, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [ce116189a9](https://linux-hardware.org/?probe=ce116189a9) | Mar 19, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [1f7de7a842](https://linux-hardware.org/?probe=1f7de7a842) | Mar 19, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [ebd077e7f4](https://linux-hardware.org/?probe=ebd077e7f4) | Mar 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [6079cacf9b](https://linux-hardware.org/?probe=6079cacf9b) | Mar 14, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [a9fd173c51](https://linux-hardware.org/?probe=a9fd173c51) | Mar 13, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [efab4d96e9](https://linux-hardware.org/?probe=efab4d96e9) | Mar 10, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [514d4c99a1](https://linux-hardware.org/?probe=514d4c99a1) | Mar 10, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [2407fc2f7a](https://linux-hardware.org/?probe=2407fc2f7a) | Mar 09, 2021 |
| Dell          | Dimension E521              | Desktop     | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | 0C522T A01                  | Desktop     | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [4c4bb4bd4a](https://linux-hardware.org/?probe=4c4bb4bd4a) | Mar 04, 2021 |
| HP            | 3032h                       | Desktop     | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [b0cdfde6d1](https://linux-hardware.org/?probe=b0cdfde6d1) | Mar 02, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [492714801f](https://linux-hardware.org/?probe=492714801f) | Mar 02, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| HP            | 8458                        | Mini pc     | [87e6e38b4a](https://linux-hardware.org/?probe=87e6e38b4a) | Feb 20, 2021 |
| HP            | 8458                        | Mini pc     | [51c854280c](https://linux-hardware.org/?probe=51c854280c) | Feb 20, 2021 |
| Lenovo        | ThinkPad R60 94566FG        | Notebook    | [f0eb3f1d77](https://linux-hardware.org/?probe=f0eb3f1d77) | Feb 19, 2021 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [3ae1e824ed](https://linux-hardware.org/?probe=3ae1e824ed) | Feb 13, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f7fc4d663b](https://linux-hardware.org/?probe=f7fc4d663b) | Feb 08, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e4d417012f](https://linux-hardware.org/?probe=e4d417012f) | Feb 08, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [cf6b92a979](https://linux-hardware.org/?probe=cf6b92a979) | Feb 07, 2021 |
| Acer          | Aspire 7730G                | Notebook    | [6fadc9e655](https://linux-hardware.org/?probe=6fadc9e655) | Jan 31, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Dell          | 0TP406                      | Desktop     | [0980bfcfe9](https://linux-hardware.org/?probe=0980bfcfe9) | Jan 28, 2021 |
| Dell          | 0K216C                      | Desktop     | [c1cf70d814](https://linux-hardware.org/?probe=c1cf70d814) | Jan 19, 2021 |
| Sony          | VPCZ21V9E                   | Notebook    | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [b0f061dfba](https://linux-hardware.org/?probe=b0f061dfba) | Jan 08, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [da98de1775](https://linux-hardware.org/?probe=da98de1775) | Jan 08, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5494aa2859](https://linux-hardware.org/?probe=5494aa2859) | Jan 04, 2021 |
| Acer          | AOD255                      | Notebook    | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Lenovo        | ThinkPad T450 20BUS3CF00    | Notebook    | [4dde602ff6](https://linux-hardware.org/?probe=4dde602ff6) | Jan 01, 2021 |
| Acer          | Extensa 5630                | Notebook    | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| Sony          | VPCZ21V9E                   | Notebook    | [b34a53e0e2](https://linux-hardware.org/?probe=b34a53e0e2) | Dec 29, 2020 |
| Acer          | Extensa 5510                | Notebook    | [efd4fce381](https://linux-hardware.org/?probe=efd4fce381) | Dec 29, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [56f8292d5b](https://linux-hardware.org/?probe=56f8292d5b) | Dec 23, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| MSI           | MS-7211                     | Desktop     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Acer          | Extensa 5220                | Notebook    | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | Notebook    | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Dell          | Precision M4700             | Notebook    | [58d2d0e8d4](https://linux-hardware.org/?probe=58d2d0e8d4) | Dec 11, 2020 |
| Dell          | Precision M4700             | Notebook    | [379e1a461c](https://linux-hardware.org/?probe=379e1a461c) | Dec 09, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [ac934f7ac7](https://linux-hardware.org/?probe=ac934f7ac7) | Dec 07, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [8f2d17e846](https://linux-hardware.org/?probe=8f2d17e846) | Dec 07, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [7499600f8c](https://linux-hardware.org/?probe=7499600f8c) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Nvidia        | MCP7A 2                     | Desktop     | [c18fd136a9](https://linux-hardware.org/?probe=c18fd136a9) | Nov 24, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | Notebook    | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [9ab6ea275f](https://linux-hardware.org/?probe=9ab6ea275f) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [ae71ad880b](https://linux-hardware.org/?probe=ae71ad880b) | Nov 10, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | Notebook    | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| Google        | Gnawty                      | Notebook    | [6bb50a022d](https://linux-hardware.org/?probe=6bb50a022d) | Oct 10, 2020 |
| Toshiba       | QOSMIO F755                 | Notebook    | [defa9c775a](https://linux-hardware.org/?probe=defa9c775a) | Oct 01, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [64da7044cf](https://linux-hardware.org/?probe=64da7044cf) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| HP            | 1494                        | Desktop     | [3d33e5eb9e](https://linux-hardware.org/?probe=3d33e5eb9e) | Sep 20, 2020 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [e45ead8de9](https://linux-hardware.org/?probe=e45ead8de9) | Sep 20, 2020 |
| Samsung       | R610                        | Notebook    | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| ASUSTek       | T101HA                      | Notebook    | [036f4f2304](https://linux-hardware.org/?probe=036f4f2304) | Sep 15, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| ASUSTek       | P53E                        | Notebook    | [75d3fa4178](https://linux-hardware.org/?probe=75d3fa4178) | Sep 04, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [06dd4aecb5](https://linux-hardware.org/?probe=06dd4aecb5) | Sep 01, 2020 |
| Acer          | TravelMate B115-M           | Notebook    | [d3395dca0c](https://linux-hardware.org/?probe=d3395dca0c) | Aug 30, 2020 |
| Itautec       | W7655                       | Notebook    | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| HP            | 8265                        | Desktop     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [fc54031f7e](https://linux-hardware.org/?probe=fc54031f7e) | Aug 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | Notebook    | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | Notebook    | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| HP            | 0A54h                       | Desktop     | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| Samsung       | N150/N210/N220              | Notebook    | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                   | Desktop     | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                        | Desktop     | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| HP            | EliteBook 2740p             | Notebook    | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | Notebook    | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | Notebook    | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | W7655                       | Notebook    | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| Positivo      | N1103                       | Notebook    | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | Notebook    | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | Notebook    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| HP            | 1494                        | Desktop     | [69ad46d94d](https://linux-hardware.org/?probe=69ad46d94d) | Jun 11, 2020 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| Lenovo        | B490 37722SP                | Notebook    | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| MSI           | MS-7267                     | Desktop     | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Mini 110-1000               | Notebook    | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | Notebook    | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Clevo         | W55xEU                      | Notebook    | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [4fa188ca3e](https://linux-hardware.org/?probe=4fa188ca3e) | May 15, 2020 |
| ECS           | Alhena5                     | Desktop     | [be2ff7b4dc](https://linux-hardware.org/?probe=be2ff7b4dc) | May 15, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a0112b2478](https://linux-hardware.org/?probe=a0112b2478) | May 14, 2020 |
| Toshiba       | Satellite M70               | Notebook    | [c9e02a940d](https://linux-hardware.org/?probe=c9e02a940d) | May 13, 2020 |
| ASUSTek       | Q400A                       | Notebook    | [075d494ee2](https://linux-hardware.org/?probe=075d494ee2) | May 10, 2020 |
| Lenovo        | B575 1450A7U                | Notebook    | [b781397fa7](https://linux-hardware.org/?probe=b781397fa7) | May 05, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [3d10f5b306](https://linux-hardware.org/?probe=3d10f5b306) | May 03, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [0e91d35b8e](https://linux-hardware.org/?probe=0e91d35b8e) | May 03, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [8aad1d7bfc](https://linux-hardware.org/?probe=8aad1d7bfc) | May 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [9957230890](https://linux-hardware.org/?probe=9957230890) | Apr 30, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Toshiba       | Satellite Pro C850          | Notebook    | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
| Dell          | 0WF810                      | Desktop     | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [79e6fc40f4](https://linux-hardware.org/?probe=79e6fc40f4) | Apr 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5ddee791c7](https://linux-hardware.org/?probe=5ddee791c7) | Apr 20, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [15b2fb3807](https://linux-hardware.org/?probe=15b2fb3807) | Apr 20, 2020 |
| ASUSTek       | X45U                        | Notebook    | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [e6b8191910](https://linux-hardware.org/?probe=e6b8191910) | Apr 16, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [e4cfc413e7](https://linux-hardware.org/?probe=e4cfc413e7) | Apr 08, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [20e7fea349](https://linux-hardware.org/?probe=20e7fea349) | Apr 08, 2020 |
| Lenovo        | 433328G                     | Notebook    | [3c5b9e3703](https://linux-hardware.org/?probe=3c5b9e3703) | Apr 07, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [0c74c17c24](https://linux-hardware.org/?probe=0c74c17c24) | Apr 07, 2020 |
| Gigabyte      | VM900M                      | Desktop     | [8554ccddc2](https://linux-hardware.org/?probe=8554ccddc2) | Apr 03, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [499f685a66](https://linux-hardware.org/?probe=499f685a66) | Mar 31, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [2c6f9bf922](https://linux-hardware.org/?probe=2c6f9bf922) | Mar 31, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [8fae01eff8](https://linux-hardware.org/?probe=8fae01eff8) | Mar 31, 2020 |
| HP            | 1494                        | Desktop     | [b34629c804](https://linux-hardware.org/?probe=b34629c804) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| HP            | 255 G2                      | Notebook    | [7cfb9e5a0e](https://linux-hardware.org/?probe=7cfb9e5a0e) | Mar 25, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [a16a39037a](https://linux-hardware.org/?probe=a16a39037a) | Mar 24, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [f5dcbfaa11](https://linux-hardware.org/?probe=f5dcbfaa11) | Mar 24, 2020 |
| Clevo         | W55xEU                      | Notebook    | [09d70e49b4](https://linux-hardware.org/?probe=09d70e49b4) | Mar 23, 2020 |
| Unknown       | G41 Series                  | Desktop     | [597b5edb76](https://linux-hardware.org/?probe=597b5edb76) | Mar 20, 2020 |
| ASUSTek       | F3E                         | Notebook    | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| ASUSTek       | F3E                         | Notebook    | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | 0AA8h                       | Desktop     | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73        | Desktop     | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| ECS           | Alhena5                     | Desktop     | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| eMachines     | E520 V1.06                  | Notebook    | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Acer          | Aspire 7730G                | Notebook    | [f00cf2c184](https://linux-hardware.org/?probe=f00cf2c184) | Feb 13, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| Toshiba       | Satellite C850-F117         | Notebook    | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Sony          | VGN-CR21S_P                 | Notebook    | [2ceca1462f](https://linux-hardware.org/?probe=2ceca1462f) | Feb 08, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| HP            | 0AA8h                       | Desktop     | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | NB520                       | Notebook    | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | Notebook    | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [0244fb9c97](https://linux-hardware.org/?probe=0244fb9c97) | Feb 01, 2020 |
| ASUSTek       | S500CA                      | Notebook    | [4f82008cac](https://linux-hardware.org/?probe=4f82008cac) | Jan 29, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [4d8db6ee1f](https://linux-hardware.org/?probe=4d8db6ee1f) | Jan 22, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [6320c5f50f](https://linux-hardware.org/?probe=6320c5f50f) | Jan 22, 2020 |
| Sony          | VPCCW21FX                   | Notebook    | [78ac20109b](https://linux-hardware.org/?probe=78ac20109b) | Jan 21, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c7c5cc3339](https://linux-hardware.org/?probe=c7c5cc3339) | Jan 17, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [4e6cff6c0e](https://linux-hardware.org/?probe=4e6cff6c0e) | Jan 17, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [75648daef1](https://linux-hardware.org/?probe=75648daef1) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | Desktop     | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d87b9779d7](https://linux-hardware.org/?probe=d87b9779d7) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c6595736b8](https://linux-hardware.org/?probe=c6595736b8) | Jan 14, 2020 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [db8eaef3e7](https://linux-hardware.org/?probe=db8eaef3e7) | Jan 09, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [847cb4544c](https://linux-hardware.org/?probe=847cb4544c) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [cf7e7bc433](https://linux-hardware.org/?probe=cf7e7bc433) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [d7442beee0](https://linux-hardware.org/?probe=d7442beee0) | Dec 23, 2019 |
| HP            | 0A54h                       | Desktop     | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [f30cd368d8](https://linux-hardware.org/?probe=f30cd368d8) | Dec 02, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [86b1a4acd7](https://linux-hardware.org/?probe=86b1a4acd7) | Dec 02, 2019 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [f2817e5306](https://linux-hardware.org/?probe=f2817e5306) | Nov 29, 2019 |
| Biostar       | A68N-5600E                  | Desktop     | [d91042148c](https://linux-hardware.org/?probe=d91042148c) | Nov 27, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [5b8f68dbc9](https://linux-hardware.org/?probe=5b8f68dbc9) | Nov 26, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d1bbd1e60](https://linux-hardware.org/?probe=0d1bbd1e60) | Nov 25, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [98653dbce0](https://linux-hardware.org/?probe=98653dbce0) | Nov 25, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                     | Desktop     | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | Notebook    | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                   | Desktop     | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                      | Desktop     | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| Lenovo        | 31900058 STD                | Desktop     | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Gigabyte      | H61M-S1                     | Desktop     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                     | Desktop     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                     | Desktop     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | Desktop     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [a638607db3](https://linux-hardware.org/?probe=a638607db3) | Sep 11, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [85ac9b2b53](https://linux-hardware.org/?probe=85ac9b2b53) | Aug 20, 2019 |
| Foxconn       | 2AB7                        | Desktop     | [f1f1f7133a](https://linux-hardware.org/?probe=f1f1f7133a) | Aug 18, 2019 |
| ASUSTek       | P5K-VM                      | Desktop     | [e2d3942d30](https://linux-hardware.org/?probe=e2d3942d30) | Jul 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [d1b680dc39](https://linux-hardware.org/?probe=d1b680dc39) | Jul 05, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [986146d6eb](https://linux-hardware.org/?probe=986146d6eb) | Jul 01, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [ee64cbe6b5](https://linux-hardware.org/?probe=ee64cbe6b5) | Jun 28, 2019 |
| HP            | Pavilion dv7                | Notebook    | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | Notebook    | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | Notebook    | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | Notebook    | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | Notebook    | [cca643879f](https://linux-hardware.org/?probe=cca643879f) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | Notebook    | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | Notebook    | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| Gateway       | MX6940M                     | Notebook    | [668db92873](https://linux-hardware.org/?probe=668db92873) | May 09, 2019 |
| Pegatron      | NARRA5                      | Desktop     | [123cff15b7](https://linux-hardware.org/?probe=123cff15b7) | May 04, 2019 |
| Dell          | Latitude D630               | Notebook    | [6ad005d6b7](https://linux-hardware.org/?probe=6ad005d6b7) | May 02, 2019 |
| WinBook       | GL Series                   | Notebook    | [89dac45ef6](https://linux-hardware.org/?probe=89dac45ef6) | Apr 28, 2019 |
| Dell          | Latitude D630               | Notebook    | [d8bf959191](https://linux-hardware.org/?probe=d8bf959191) | Apr 16, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | Notebook    | [c662baa8f5](https://linux-hardware.org/?probe=c662baa8f5) | Apr 10, 2019 |
| Intel         | D945GNT AAC96324-402        | Desktop     | [23bac57788](https://linux-hardware.org/?probe=23bac57788) | Apr 07, 2019 |
| eMachines     | E620                        | Notebook    | [de3cfd34b1](https://linux-hardware.org/?probe=de3cfd34b1) | Apr 05, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [81ec6c8fb1](https://linux-hardware.org/?probe=81ec6c8fb1) | Apr 04, 2019 |
| Dell          | Latitude D430               | Notebook    | [269e1c2948](https://linux-hardware.org/?probe=269e1c2948) | Apr 04, 2019 |
| Dell          | Latitude D430               | Notebook    | [d1c49bd4e8](https://linux-hardware.org/?probe=d1c49bd4e8) | Apr 04, 2019 |
| Positivo      | UW3                         | Notebook    | [dda25a3dc9](https://linux-hardware.org/?probe=dda25a3dc9) | Apr 03, 2019 |
| Positivo      | UW3                         | Notebook    | [aebfedfabb](https://linux-hardware.org/?probe=aebfedfabb) | Apr 03, 2019 |
| HP            | Pavilion dv1000 (PS600EA... | Notebook    | [6802b34fdd](https://linux-hardware.org/?probe=6802b34fdd) | Mar 31, 2019 |
| HP            | 17E2                        | Mini pc     | [982f591b41](https://linux-hardware.org/?probe=982f591b41) | Feb 23, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Acer          | Aspire 7730G                | Notebook    | [09bd4355b9](https://linux-hardware.org/?probe=09bd4355b9) | Jan 30, 2019 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [11425d1746](https://linux-hardware.org/?probe=11425d1746) | Jan 27, 2019 |
| Clevo         | M660SR VT6363A              | Notebook    | [647fd58075](https://linux-hardware.org/?probe=647fd58075) | Jan 15, 2019 |
| Clevo         | M660SR VT6363A              | Notebook    | [ad84ff197d](https://linux-hardware.org/?probe=ad84ff197d) | Jan 15, 2019 |
| Lenovo        | ThinkPad W510 4391B49       | Notebook    | [227847df62](https://linux-hardware.org/?probe=227847df62) | Feb 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Peppermint 10   | 227       | 86.97%  |
| Peppermint 9    | 28        | 10.73%  |
| Peppermint      | 3         | 1.15%   |
| Peppermint 11.2 | 2         | 0.77%   |
| Peppermint 8    | 1         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Peppermint | 261       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.0.0-37-generic      | 39        | 13.31%  |
| 4.18.0-18-generic     | 11        | 3.75%   |
| 5.4.0-42-generic      | 10        | 3.41%   |
| 5.3.0-51-generic      | 10        | 3.41%   |
| 5.3.0-62-generic      | 8         | 2.73%   |
| 4.15.0-43-generic     | 8         | 2.73%   |
| 5.4.0-65-generic      | 7         | 2.39%   |
| 5.3.0-46-generic      | 7         | 2.39%   |
| 5.0.0-36-generic      | 7         | 2.39%   |
| 5.0.0-32-generic      | 7         | 2.39%   |
| 5.4.0-87-generic      | 6         | 2.05%   |
| 5.4.0-66-generic      | 6         | 2.05%   |
| 5.4.0-58-generic      | 6         | 2.05%   |
| 5.4.0-91-generic      | 5         | 1.71%   |
| 5.4.0-52-generic      | 5         | 1.71%   |
| 5.3.0-40-generic      | 5         | 1.71%   |
| 5.3.0-28-generic      | 5         | 1.71%   |
| 5.4.0-90-generic      | 4         | 1.37%   |
| 5.4.0-80-generic      | 4         | 1.37%   |
| 5.4.0-72-generic      | 4         | 1.37%   |
| 5.4.0-67-generic      | 4         | 1.37%   |
| 5.4.0-54-generic      | 4         | 1.37%   |
| 5.4.0-48-generic      | 4         | 1.37%   |
| 5.4.0-45-generic      | 4         | 1.37%   |
| 5.3.0-59-generic      | 4         | 1.37%   |
| 4.18.0-25-generic     | 4         | 1.37%   |
| 4.15.0-47-generic     | 4         | 1.37%   |
| 5.4.0-81-generic      | 3         | 1.02%   |
| 5.4.0-77-generic      | 3         | 1.02%   |
| 5.4.0-70-generic      | 3         | 1.02%   |
| 5.4.0-56-generic      | 3         | 1.02%   |
| 5.4.0-47-generic      | 3         | 1.02%   |
| 5.3.0-47-generic      | 3         | 1.02%   |
| 5.3.0-42-generic      | 3         | 1.02%   |
| 5.10.0-11-amd64       | 3         | 1.02%   |
| 5.0.0-29-generic      | 3         | 1.02%   |
| 4.15.0-76-generic     | 3         | 1.02%   |
| 4.15.0-48-generic     | 3         | 1.02%   |
| 5.4.0-97-generic      | 2         | 0.68%   |
| 5.4.0-84-generic      | 2         | 0.68%   |
| 5.4.0-74-generic      | 2         | 0.68%   |
| 5.4.0-62-generic      | 2         | 0.68%   |
| 5.4.0-60-generic      | 2         | 0.68%   |
| 5.4.0-49-generic      | 2         | 0.68%   |
| 5.3.6-050306-generic  | 2         | 0.68%   |
| 5.3.0-45-generic      | 2         | 0.68%   |
| 5.0.0-27-generic      | 2         | 0.68%   |
| 5.0.0-25-generic      | 2         | 0.68%   |
| 4.18.0-24-generic     | 2         | 0.68%   |
| 4.18.0-21-generic     | 2         | 0.68%   |
| 4.15.0-45-generic     | 2         | 0.68%   |
| 4.15.0-135-generic    | 2         | 0.68%   |
| 4.15.0-101-generic    | 2         | 0.68%   |
| 5.7.1-050701-generic  | 1         | 0.34%   |
| 5.6.7-050607-generic  | 1         | 0.34%   |
| 5.4.95-050495-generic | 1         | 0.34%   |
| 5.4.0-96-generic      | 1         | 0.34%   |
| 5.4.0-94-generic      | 1         | 0.34%   |
| 5.4.0-92-generic      | 1         | 0.34%   |
| 5.4.0-89-generic      | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 109       | 39.93%  |
| 5.0.0   | 57        | 20.88%  |
| 5.3.0   | 47        | 17.22%  |
| 4.15.0  | 27        | 9.89%   |
| 4.18.0  | 20        | 7.33%   |
| 5.10.0  | 5         | 1.83%   |
| 5.3.6   | 2         | 0.73%   |
| 5.7.1   | 1         | 0.37%   |
| 5.6.7   | 1         | 0.37%   |
| 5.4.95  | 1         | 0.37%   |
| 5.3.9   | 1         | 0.37%   |
| 5.1.11  | 1         | 0.37%   |
| 4.8.0   | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 110       | 40.29%  |
| 5.0     | 57        | 20.88%  |
| 5.3     | 50        | 18.32%  |
| 4.15    | 27        | 9.89%   |
| 4.18    | 20        | 7.33%   |
| 5.10    | 5         | 1.83%   |
| 5.7     | 1         | 0.37%   |
| 5.6     | 1         | 0.37%   |
| 5.1     | 1         | 0.37%   |
| 4.8     | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 66.03%  |
| i686   | 89        | 33.97%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXDE       | 197       | 73.78%  |
| Unknown    | 52        | 19.48%  |
| GNOME      | 10        | 3.75%   |
| XFCE       | 5         | 1.87%   |
| Peppermint | 2         | 0.75%   |
| X-Cinnamon | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 261       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 236       | 89.39%  |
| LightDM | 16        | 6.06%   |
| TDM     | 11        | 4.17%   |
| SDDM    | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 87        | 32.46%  |
| Unknown | 44        | 16.42%  |
| de_DE   | 16        | 5.97%   |
| en_GB   | 15        | 5.6%    |
| pt_BR   | 14        | 5.22%   |
| it_IT   | 14        | 5.22%   |
| pl_PL   | 7         | 2.61%   |
| C       | 7         | 2.61%   |
| fr_FR   | 6         | 2.24%   |
| en_IN   | 6         | 2.24%   |
| ru_RU   | 5         | 1.87%   |
| nl_NL   | 5         | 1.87%   |
| en_CA   | 5         | 1.87%   |
| es_MX   | 4         | 1.49%   |
| es_AR   | 4         | 1.49%   |
| ro_RO   | 3         | 1.12%   |
| fi_FI   | 3         | 1.12%   |
| ja_JP   | 2         | 0.75%   |
| es_PE   | 2         | 0.75%   |
| es_ES   | 2         | 0.75%   |
| en_PH   | 2         | 0.75%   |
| en_AU   | 2         | 0.75%   |
| tr_TR   | 1         | 0.37%   |
| sv_SE   | 1         | 0.37%   |
| pt_PT   | 1         | 0.37%   |
| lv_LV   | 1         | 0.37%   |
| es_PA   | 1         | 0.37%   |
| es_EC   | 1         | 0.37%   |
| es_CR   | 1         | 0.37%   |
| es_BO   | 1         | 0.37%   |
| en_ZA   | 1         | 0.37%   |
| en_NZ   | 1         | 0.37%   |
| en_IE   | 1         | 0.37%   |
| el_GR   | 1         | 0.37%   |
| cs_CZ   | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 209       | 79.77%  |
| EFI  | 53        | 20.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 221       | 83.08%  |
| Unknown  | 25        | 9.4%    |
| Overlay  | 8         | 3.01%   |
| Btrfs    | 4         | 1.5%    |
| Ext2     | 3         | 1.13%   |
| Ext3     | 2         | 0.75%   |
| Xfs      | 1         | 0.38%   |
| Reiserfs | 1         | 0.38%   |
| Aufs     | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 244       | 93.13%  |
| GPT     | 10        | 3.82%   |
| MBR     | 8         | 3.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 245       | 92.45%  |
| Yes       | 20        | 7.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 229       | 86.74%  |
| Yes       | 35        | 13.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 47        | 18.01%  |
| ASUSTek Computer    | 36        | 13.79%  |
| Dell                | 33        | 12.64%  |
| Lenovo              | 25        | 9.58%   |
| Toshiba             | 16        | 6.13%   |
| Acer                | 16        | 6.13%   |
| Gigabyte Technology | 11        | 4.21%   |
| Samsung Electronics | 7         | 2.68%   |
| Intel               | 7         | 2.68%   |
| Fujitsu Siemens     | 7         | 2.68%   |
| Sony                | 5         | 1.92%   |
| eMachines           | 5         | 1.92%   |
| ECS                 | 5         | 1.92%   |
| ASRock              | 4         | 1.53%   |
| Positivo            | 3         | 1.15%   |
| Pegatron            | 3         | 1.15%   |
| Gateway             | 3         | 1.15%   |
| Apple               | 3         | 1.15%   |
| Unknown             | 3         | 1.15%   |
| Packard Bell        | 2         | 0.77%   |
| MSI                 | 2         | 0.77%   |
| Medion              | 2         | 0.77%   |
| IBM                 | 2         | 0.77%   |
| Fujitsu             | 2         | 0.77%   |
| Clevo               | 2         | 0.77%   |
| WinBook             | 1         | 0.38%   |
| Olivetti            | 1         | 0.38%   |
| Nvidia              | 1         | 0.38%   |
| LincPlus            | 1         | 0.38%   |
| JPSaCouto           | 1         | 0.38%   |
| Itautec             | 1         | 0.38%   |
| Google              | 1         | 0.38%   |
| Foxconn             | 1         | 0.38%   |
| Biostar             | 1         | 0.38%   |
| AAEON               | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad 2in1 14 81CW                | 3         | 1.15%   |
| Lenovo G500 20236                          | 3         | 1.15%   |
| Unknown                                    | 3         | 1.15%   |
| Toshiba Satellite M70                      | 2         | 0.77%   |
| Toshiba Satellite L500                     | 2         | 0.77%   |
| Samsung N150P/N210P/N220P                  | 2         | 0.77%   |
| Positivo Mobile                            | 2         | 0.77%   |
| HP Compaq dc7900 Convertible Minitower     | 2         | 0.77%   |
| HP Compaq 8200 Elite CMT PC                | 2         | 0.77%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.77%   |
| Fujitsu Siemens D1931                      | 2         | 0.77%   |
| Dell Latitude D630                         | 2         | 0.77%   |
| Dell Inspiron N5050                        | 2         | 0.77%   |
| ASRock N68-S3 FX                           | 2         | 0.77%   |
| Acer Extensa 5630                          | 2         | 0.77%   |
| WinBook GL Series                          | 1         | 0.38%   |
| Toshiba Satellite Pro C850                 | 1         | 0.38%   |
| Toshiba Satellite L750D                    | 1         | 0.38%   |
| Toshiba Satellite L310                     | 1         | 0.38%   |
| Toshiba Satellite L300                     | 1         | 0.38%   |
| Toshiba Satellite C850-F117                | 1         | 0.38%   |
| Toshiba Satellite C660                     | 1         | 0.38%   |
| Toshiba Satellite C55D-B                   | 1         | 0.38%   |
| Toshiba QOSMIO F755                        | 1         | 0.38%   |
| Toshiba PORTEGE R500                       | 1         | 0.38%   |
| Toshiba NB520                              | 1         | 0.38%   |
| Toshiba NB500                              | 1         | 0.38%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.38%   |
| Sony VPCZ21V9E                             | 1         | 0.38%   |
| Sony VPCCW21FX                             | 1         | 0.38%   |
| Sony VGN-S55B_S                            | 1         | 0.38%   |
| Sony VGN-FW140E                            | 1         | 0.38%   |
| Sony VGN-CR21S_P                           | 1         | 0.38%   |
| Samsung R610                               | 1         | 0.38%   |
| Samsung R530/R730/R540                     | 1         | 0.38%   |
| Samsung N150P                              | 1         | 0.38%   |
| Samsung N150/N210/N220                     | 1         | 0.38%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.38%   |
| Positivo N1103                             | 1         | 0.38%   |
| Pegatron FR502AA-ABZ m9355.it              | 1         | 0.38%   |
| Pegatron CQ1506LA                          | 1         | 0.38%   |
| Pegatron AY627AA-ABA a4313w                | 1         | 0.38%   |
| Packard Bell EasyNote_MX45                 | 1         | 0.38%   |
| Packard Bell EasyNote TK85                 | 1         | 0.38%   |
| Olivetti CL133A                            | 1         | 0.38%   |
| Nvidia MCP7A                               | 1         | 0.38%   |
| MSI MS-7267                                | 1         | 0.38%   |
| MSI MS-7211                                | 1         | 0.38%   |
| Medion WIM2160                             | 1         | 0.38%   |
| Medion Akoya E4214 MD99570                 | 1         | 0.38%   |
| LincPlus P1                                | 1         | 0.38%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS0035US   | 1         | 0.38%   |
| Lenovo ThinkPad W510 4391B49               | 1         | 0.38%   |
| Lenovo ThinkPad T60 1951CJ4                | 1         | 0.38%   |
| Lenovo ThinkPad T450 20BUS3CF00            | 1         | 0.38%   |
| Lenovo ThinkPad R60 94566FG                | 1         | 0.38%   |
| Lenovo ThinkPad Edge E431 62775GU          | 1         | 0.38%   |
| Lenovo ThinkPad E490 20N90019BR            | 1         | 0.38%   |
| Lenovo ThinkCentre M78 10BR0005US          | 1         | 0.38%   |
| Lenovo MIIX 310-10ICR 80SG                 | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 14        | 5.36%   |
| Dell Inspiron           | 14        | 5.36%   |
| Toshiba Satellite       | 11        | 4.21%   |
| HP Pavilion             | 9         | 3.45%   |
| Acer Aspire             | 8         | 3.07%   |
| Lenovo ThinkPad         | 7         | 2.68%   |
| Lenovo IdeaPad          | 6         | 2.3%    |
| Dell OptiPlex           | 6         | 2.3%    |
| Dell Latitude           | 6         | 2.3%    |
| HP EliteBook            | 5         | 1.92%   |
| Acer Extensa            | 4         | 1.53%   |
| Samsung N150P           | 3         | 1.15%   |
| Lenovo G500             | 3         | 1.15%   |
| HP Laptop               | 3         | 1.15%   |
| Fujitsu Siemens AMILO   | 3         | 1.15%   |
| Dell Precision          | 3         | 1.15%   |
| Unknown                 | 3         | 1.15%   |
| Positivo Mobile         | 2         | 0.77%   |
| Packard Bell EasyNote   | 2         | 0.77%   |
| IBM ThinkPad            | 2         | 0.77%   |
| HP Stream               | 2         | 0.77%   |
| HP Mini                 | 2         | 0.77%   |
| HP 255                  | 2         | 0.77%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.77%   |
| Fujitsu Siemens D1931   | 2         | 0.77%   |
| ASUS ROG                | 2         | 0.77%   |
| ASRock N68-S3           | 2         | 0.77%   |
| WinBook GL              | 1         | 0.38%   |
| Toshiba QOSMIO          | 1         | 0.38%   |
| Toshiba PORTEGE         | 1         | 0.38%   |
| Toshiba NB520           | 1         | 0.38%   |
| Toshiba NB500           | 1         | 0.38%   |
| Toshiba dynabook        | 1         | 0.38%   |
| Sony VPCZ21V9E          | 1         | 0.38%   |
| Sony VPCCW21FX          | 1         | 0.38%   |
| Sony VGN-S55B           | 1         | 0.38%   |
| Sony VGN-FW140E         | 1         | 0.38%   |
| Sony VGN-CR21S          | 1         | 0.38%   |
| Samsung R610            | 1         | 0.38%   |
| Samsung R530            | 1         | 0.38%   |
| Samsung N150            | 1         | 0.38%   |
| Samsung 300E4A          | 1         | 0.38%   |
| Positivo N1103          | 1         | 0.38%   |
| Pegatron FR502AA-ABZ    | 1         | 0.38%   |
| Pegatron CQ1506LA       | 1         | 0.38%   |
| Pegatron AY627AA-ABA    | 1         | 0.38%   |
| Olivetti CL133A         | 1         | 0.38%   |
| Nvidia MCP7A            | 1         | 0.38%   |
| MSI MS-7267             | 1         | 0.38%   |
| MSI MS-7211             | 1         | 0.38%   |
| Medion WIM2160          | 1         | 0.38%   |
| Medion Akoya            | 1         | 0.38%   |
| LincPlus P1             | 1         | 0.38%   |
| Lenovo ThinkCentre      | 1         | 0.38%   |
| Lenovo MIIX             | 1         | 0.38%   |
| Lenovo IdeaCentre       | 1         | 0.38%   |
| Lenovo G575             | 1         | 0.38%   |
| Lenovo B575             | 1         | 0.38%   |
| Lenovo B570e            | 1         | 0.38%   |
| Lenovo B490             | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 34        | 13.03%  |
| 2007    | 32        | 12.26%  |
| 2011    | 29        | 11.11%  |
| 2009    | 24        | 9.2%    |
| 2010    | 23        | 8.81%   |
| 2006    | 19        | 7.28%   |
| 2013    | 18        | 6.9%    |
| 2012    | 17        | 6.51%   |
| 2015    | 10        | 3.83%   |
| 2005    | 10        | 3.83%   |
| 2017    | 8         | 3.07%   |
| 2014    | 8         | 3.07%   |
| 2019    | 7         | 2.68%   |
| 2018    | 7         | 2.68%   |
| 2016    | 7         | 2.68%   |
| 2020    | 4         | 1.53%   |
| 2004    | 2         | 0.77%   |
| 2001    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 164       | 62.84%  |
| Desktop     | 90        | 34.48%  |
| Convertible | 3         | 1.15%   |
| Mini pc     | 2         | 0.77%   |
| Tablet      | 1         | 0.38%   |
| All in one  | 1         | 0.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 252       | 96.55%  |
| Enabled  | 9         | 3.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 260       | 99.62%  |
| Yes  | 1         | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 80        | 30.08%  |
| 1.01-2.0   | 69        | 25.94%  |
| 4.01-8.0   | 31        | 11.65%  |
| 8.01-16.0  | 27        | 10.15%  |
| 2.01-3.0   | 21        | 7.89%   |
| 0.51-1.0   | 20        | 7.52%   |
| 16.01-24.0 | 11        | 4.14%   |
| 32.01-64.0 | 5         | 1.88%   |
| 24.01-32.0 | 1         | 0.38%   |
| 0.01-0.5   | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 109       | 37.85%  |
| 1.01-2.0  | 106       | 36.81%  |
| 2.01-3.0  | 32        | 11.11%  |
| 0.01-0.5  | 23        | 7.99%   |
| 3.01-4.0  | 9         | 3.13%   |
| 4.01-8.0  | 7         | 2.43%   |
| 8.01-16.0 | 2         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 194       | 72.66%  |
| 2      | 54        | 20.22%  |
| 3      | 11        | 4.12%   |
| 0      | 3         | 1.12%   |
| 4      | 2         | 0.75%   |
| 7      | 1         | 0.37%   |
| 6      | 1         | 0.37%   |
| 5      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 61.6%   |
| No        | 101       | 38.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 93.1%   |
| No        | 18        | 6.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 82.76%  |
| No        | 45        | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 60.69%  |
| Yes       | 103       | 39.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 77        | 29.39%  |
| Germany      | 24        | 9.16%   |
| Italy        | 15        | 5.73%   |
| UK           | 14        | 5.34%   |
| Brazil       | 14        | 5.34%   |
| Netherlands  | 10        | 3.82%   |
| Canada       | 10        | 3.82%   |
| Romania      | 7         | 2.67%   |
| Poland       | 7         | 2.67%   |
| India        | 7         | 2.67%   |
| Russia       | 6         | 2.29%   |
| Sweden       | 5         | 1.91%   |
| Spain        | 5         | 1.91%   |
| Mexico       | 5         | 1.91%   |
| France       | 5         | 1.91%   |
| Argentina    | 5         | 1.91%   |
| Finland      | 4         | 1.53%   |
| Portugal     | 3         | 1.15%   |
| Japan        | 3         | 1.15%   |
| Greece       | 3         | 1.15%   |
| Philippines  | 2         | 0.76%   |
| Peru         | 2         | 0.76%   |
| Ireland      | 2         | 0.76%   |
| Bolivia      | 2         | 0.76%   |
| Australia    | 2         | 0.76%   |
| Algeria      | 2         | 0.76%   |
| Ukraine      | 1         | 0.38%   |
| Turkey       | 1         | 0.38%   |
| Switzerland  | 1         | 0.38%   |
| South Africa | 1         | 0.38%   |
| Serbia       | 1         | 0.38%   |
| Puerto Rico  | 1         | 0.38%   |
| Panama       | 1         | 0.38%   |
| Norway       | 1         | 0.38%   |
| New Zealand  | 1         | 0.38%   |
| Namibia      | 1         | 0.38%   |
| Malaysia     | 1         | 0.38%   |
| Lithuania    | 1         | 0.38%   |
| Latvia       | 1         | 0.38%   |
| Kazakhstan   | 1         | 0.38%   |
| Georgia      | 1         | 0.38%   |
| Ecuador      | 1         | 0.38%   |
| Czechia      | 1         | 0.38%   |
| Costa Rica   | 1         | 0.38%   |
| Bulgaria     | 1         | 0.38%   |
| Belgium      | 1         | 0.38%   |
| Belarus      | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toronto                | 4         | 1.47%   |
| Charlotte              | 4         | 1.47%   |
| Bucharest              | 4         | 1.47%   |
| Villingen-Schwenningen | 3         | 1.1%    |
| Turin                  | 3         | 1.1%    |
| New York               | 3         | 1.1%    |
| Warsaw                 | 2         | 0.74%   |
| Topeka                 | 2         | 0.74%   |
| Tokyo                  | 2         | 0.74%   |
| Tahlequah              | 2         | 0.74%   |
| Spokane                | 2         | 0.74%   |
| Seattle                | 2         | 0.74%   |
| Perth                  | 2         | 0.74%   |
| Osasco                 | 2         | 0.74%   |
| Naples                 | 2         | 0.74%   |
| Moscow                 | 2         | 0.74%   |
| Lima                   | 2         | 0.74%   |
| Hamburg                | 2         | 0.74%   |
| Friesoythe             | 2         | 0.74%   |
| Dublin                 | 2         | 0.74%   |
| Buenos Aires           | 2         | 0.74%   |
| Brunswick              | 2         | 0.74%   |
| Berlin                 | 2         | 0.74%   |
| Bengaluru              | 2         | 0.74%   |
| Airdrie                | 2         | 0.74%   |
| Zgierz                 | 1         | 0.37%   |
| York                   | 1         | 0.37%   |
| Yokohama               | 1         | 0.37%   |
| Wysokie Mazowieckie    | 1         | 0.37%   |
| Wroclaw                | 1         | 0.37%   |
| Worthing               | 1         | 0.37%   |
| Windhoek               | 1         | 0.37%   |
| West New York          | 1         | 0.37%   |
| West Chester           | 1         | 0.37%   |
| Weinheim               | 1         | 0.37%   |
| Wassenaar              | 1         | 0.37%   |
| Washington             | 1         | 0.37%   |
| Waalwijk               | 1         | 0.37%   |
| Volos                  | 1         | 0.37%   |
| Vit??ria               | 1         | 0.37%   |
| Villa Mar??a           | 1         | 0.37%   |
| Vijayawada             | 1         | 0.37%   |
| Venda do Pinheiro      | 1         | 0.37%   |
| Varna                  | 1         | 0.37%   |
| Van Vleck              | 1         | 0.37%   |
| Ume??                  | 1         | 0.37%   |
| Tsarskoye Selo         | 1         | 0.37%   |
| Trento                 | 1         | 0.37%   |
| Thatcher               | 1         | 0.37%   |
| Telford                | 1         | 0.37%   |
| Taranto                | 1         | 0.37%   |
| Tampere                | 1         | 0.37%   |
| Talala                 | 1         | 0.37%   |
| Swidnica               | 1         | 0.37%   |
| Stockton               | 1         | 0.37%   |
| Stockholm              | 1         | 0.37%   |
| Staffanstorp           | 1         | 0.37%   |
| Southampton            | 1         | 0.37%   |
| South Jordan           | 1         | 0.37%   |
| Sicklerville           | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 73     | 21.36%  |
| WDC                 | 62        | 85     | 20.06%  |
| Samsung Electronics | 34        | 49     | 11%     |
| Hitachi             | 29        | 39     | 9.39%   |
| Toshiba             | 21        | 22     | 6.8%    |
| Unknown             | 20        | 23     | 6.47%   |
| Kingston            | 15        | 19     | 4.85%   |
| Maxtor              | 9         | 11     | 2.91%   |
| SanDisk             | 7         | 8      | 2.27%   |
| Fujitsu             | 6         | 7      | 1.94%   |
| HGST                | 4         | 5      | 1.29%   |
| PNY                 | 3         | 4      | 0.97%   |
| Intel               | 3         | 3      | 0.97%   |
| Crucial             | 3         | 4      | 0.97%   |
| Integral            | 2         | 2      | 0.65%   |
| China               | 2         | 2      | 0.65%   |
| ASMT                | 2         | 3      | 0.65%   |
| Zheino              | 1         | 1      | 0.32%   |
| WD MediaMax         | 1         | 1      | 0.32%   |
| TrekStor            | 1         | 1      | 0.32%   |
| TCSUNBOW            | 1         | 1      | 0.32%   |
| SK hynix            | 1         | 1      | 0.32%   |
| SABRENT             | 1         | 1      | 0.32%   |
| Phison              | 1         | 2      | 0.32%   |
| Patriot             | 1         | 1      | 0.32%   |
| OCZ                 | 1         | 1      | 0.32%   |
| Micron Technology   | 1         | 1      | 0.32%   |
| LITEONIT            | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| Goodram             | 1         | 1      | 0.32%   |
| GAMER               | 1         | 1      | 0.32%   |
| FATTYDOVE           | 1         | 1      | 0.32%   |
| Drevo               | 1         | 1      | 0.32%   |
| Dogfish             | 1         | 1      | 0.32%   |
| BHT                 | 1         | 2      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |
| Apacer              | 1         | 3      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 1.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 1.55%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 1.55%   |
| Seagate ST9500325AS 500GB           | 4         | 1.24%   |
| Seagate ST9320325AS 320GB           | 4         | 1.24%   |
| Seagate ST9250315AS 250GB           | 4         | 1.24%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 1.24%   |
| Unknown MMC Card  64GB              | 3         | 0.93%   |
| Unknown MMC Card  16GB              | 3         | 0.93%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 0.93%   |
| SanDisk SDSSDA120G 120GB            | 3         | 0.93%   |
| Hitachi HTS545025B9A300 250GB       | 3         | 0.93%   |
| Hitachi HDT721016SLA380 160GB       | 3         | 0.93%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 0.62%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.62%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.62%   |
| Unknown SD/MMC/MS PRO 128GB         | 2         | 0.62%   |
| Unknown MMC Card  2GB               | 2         | 0.62%   |
| Toshiba MK5055GSX 500GB             | 2         | 0.62%   |
| Seagate ST9160314AS 160GB           | 2         | 0.62%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.62%   |
| Seagate ST3500418AS 500GB           | 2         | 0.62%   |
| Seagate ST3250310AS 250GB           | 2         | 0.62%   |
| Seagate ST3160813AS 160GB           | 2         | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.62%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.62%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.62%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.62%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.62%   |
| Samsung HM160HI 160GB               | 2         | 0.62%   |
| Maxtor STM3160215AS 160GB           | 2         | 0.62%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.62%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 0.62%   |
| Hitachi HDS721050CLA362 500GB       | 2         | 0.62%   |
| Hitachi HDP725050GLA360 500GB       | 2         | 0.62%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.62%   |
| Zheino CHN 25SATAA3 120 120GB SSD   | 1         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.31%   |
| WDC WD800JD-75MSA1 80GB             | 1         | 0.31%   |
| WDC WD800JD-60LSA5 80GB             | 1         | 0.31%   |
| WDC WD800JD-00MSA1 80GB             | 1         | 0.31%   |
| WDC WD800BEVS-60LAT0 80GB           | 1         | 0.31%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1         | 0.31%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.31%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1         | 0.31%   |
| WDC WD5000BPVT-00HXZT3 500GB        | 1         | 0.31%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 0.31%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 0.31%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.31%   |
| WDC WD4000AAJS-22TKA0 400GB         | 1         | 0.31%   |
| WDC WD4000AAJS-00YFA0 400GB         | 1         | 0.31%   |
| WDC WD3200JS-22PDB0 320GB           | 1         | 0.31%   |
| WDC WD3200BPVT-08JJ5T0 320GB        | 1         | 0.31%   |
| WDC WD3200BEVT-75ZCT2 320GB         | 1         | 0.31%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 72     | 30.23%  |
| WDC                 | 60        | 83     | 27.91%  |
| Hitachi             | 29        | 39     | 13.49%  |
| Toshiba             | 21        | 22     | 9.77%   |
| Samsung Electronics | 17        | 20     | 7.91%   |
| Maxtor              | 9         | 11     | 4.19%   |
| Fujitsu             | 6         | 7      | 2.79%   |
| HGST                | 4         | 5      | 1.86%   |
| Unknown             | 2         | 2      | 0.93%   |
| WD MediaMax         | 1         | 1      | 0.47%   |
| ASMT                | 1         | 2      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 19     | 22.39%  |
| Samsung Electronics | 14        | 25     | 20.9%   |
| SanDisk             | 7         | 8      | 10.45%  |
| PNY                 | 3         | 4      | 4.48%   |
| Intel               | 3         | 3      | 4.48%   |
| Crucial             | 3         | 4      | 4.48%   |
| WDC                 | 2         | 2      | 2.99%   |
| Integral            | 2         | 2      | 2.99%   |
| China               | 2         | 2      | 2.99%   |
| Zheino              | 1         | 1      | 1.49%   |
| TrekStor            | 1         | 1      | 1.49%   |
| TCSUNBOW            | 1         | 1      | 1.49%   |
| Patriot             | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| Goodram             | 1         | 1      | 1.49%   |
| FATTYDOVE           | 1         | 1      | 1.49%   |
| Drevo               | 1         | 1      | 1.49%   |
| Dogfish             | 1         | 1      | 1.49%   |
| BHT                 | 1         | 2      | 1.49%   |
| ASMT                | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |
| Apacer              | 1         | 3      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 195       | 264    | 67.47%  |
| SSD     | 66        | 88     | 22.84%  |
| MMC     | 18        | 21     | 6.23%   |
| NVMe    | 5         | 6      | 1.73%   |
| Unknown | 5         | 5      | 1.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 241       | 347    | 88.28%  |
| MMC  | 18        | 21     | 6.59%   |
| SAS  | 9         | 10     | 3.3%    |
| NVMe | 5         | 6      | 1.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 214       | 287    | 80.15%  |
| 0.51-1.0   | 40        | 47     | 14.98%  |
| 1.01-2.0   | 11        | 15     | 4.12%   |
| 2.01-3.0   | 1         | 2      | 0.37%   |
| 4.01-10.0  | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 96        | 35.69%  |
| 251-500        | 51        | 18.96%  |
| 51-100         | 42        | 15.61%  |
| 501-1000       | 27        | 10.04%  |
| 21-50          | 26        | 9.67%   |
| 1-20           | 10        | 3.72%   |
| 1001-2000      | 9         | 3.35%   |
| More than 3000 | 3         | 1.12%   |
| Unknown        | 3         | 1.12%   |
| 2001-3000      | 2         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 165       | 59.78%  |
| 21-50          | 52        | 18.84%  |
| 51-100         | 23        | 8.33%   |
| 101-250        | 21        | 7.61%   |
| 501-1000       | 7         | 2.54%   |
| Unknown        | 3         | 1.09%   |
| 251-500        | 2         | 0.72%   |
| 1001-2000      | 2         | 0.72%   |
| More than 3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB          | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB          | 1         | 1      | 16.67%  |
| Seagate ST9250315AS 250GB          | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 16.67%  |
| Seagate ST31500341AS 1TB           | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

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
| Detected | 242       | 360    | 92.02%  |
| Works    | 15        | 18     | 5.7%    |
| Malfunc  | 6         | 6      | 2.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 68.94%  |
| AMD                              | 36        | 13.64%  |
| Nvidia                           | 15        | 5.68%   |
| VIA Technologies                 | 7         | 2.65%   |
| Silicon Integrated Systems [SiS] | 6         | 2.27%   |
| Samsung Electronics              | 5         | 1.89%   |
| JMicron Technology               | 5         | 1.89%   |
| Marvell Technology Group         | 3         | 1.14%   |
| ULi Electronics                  | 1         | 0.38%   |
| Silicon Image                    | 1         | 0.38%   |
| Phison Electronics               | 1         | 0.38%   |
| LSI Logic / Symbios Logic        | 1         | 0.38%   |
| ASMedia Technology               | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 24        | 6.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 5.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 5.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14        | 3.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 13        | 3.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 11        | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 11        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 2.27%   |
| Nvidia MCP61 SATA Controller                                                   | 7         | 1.99%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 6         | 1.7%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 6         | 1.7%    |
| Nvidia MCP61 IDE                                                               | 6         | 1.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.7%    |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 6         | 1.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 6         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 5         | 1.42%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.14%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.14%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4         | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 3         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 3         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 3         | 0.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3         | 0.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 0.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.85%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 3         | 0.85%   |
| AMD SB600 IDE                                                                  | 3         | 0.85%   |
| AMD IXP SB4x0 IDE Controller                                                   | 3         | 0.85%   |
| VIA VT8237A SATA 2-Port Controller                                             | 2         | 0.57%   |
| VIA VT8237/8251 Serial ATA Controller                                          | 2         | 0.57%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 2         | 0.57%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2         | 0.57%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.57%   |
| JMicron JMB368 IDE controller                                                  | 2         | 0.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.57%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2         | 0.57%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                  | 2         | 0.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 0.57%   |
| AMD FCH SATA Controller [IDE mode]                                             | 2         | 0.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 0.57%   |
| ULi ULi 5287 SATA                                                              | 1         | 0.28%   |
| ULi M5229 IDE                                                                  | 1         | 0.28%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 153       | 53.5%   |
| IDE  | 114       | 39.86%  |
| RAID | 13        | 4.55%   |
| NVMe | 5         | 1.75%   |
| SAS  | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 213       | 81.61%  |
| AMD          | 47        | 18.01%  |
| CentaurHauls | 1         | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 8         | 3.07%   |
| Intel Pentium M processor 1.73GHz           | 6         | 2.3%    |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 2.3%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4         | 1.53%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 1.53%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.15%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 3         | 1.15%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 1.15%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.15%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 1.15%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.15%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 1.15%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.15%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.15%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.77%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.77%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.77%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2         | 0.77%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 0.77%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 0.77%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 0.77%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.77%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.77%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 0.77%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 0.77%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 0.77%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 0.77%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 0.77%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 0.77%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2         | 0.77%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 0.77%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 0.77%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 0.77%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2         | 0.77%   |
| Intel Celeron CPU 1017U @ 1.60GHz           | 2         | 0.77%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 0.77%   |
| AMD Phenom II X4 840 Processor              | 2         | 0.77%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 0.77%   |
| AMD Athlon II X2 250 Processor              | 2         | 0.77%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2         | 0.77%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 0.77%   |
| Intel Xeon E-2124G CPU @ 3.40GHz            | 1         | 0.38%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.38%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1         | 0.38%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1         | 0.38%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.38%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.38%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.38%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.38%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.38%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 0.38%   |
| Intel Pentium Dual CPU T2410 @ 2.00GHz      | 1         | 0.38%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.38%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.38%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 29        | 11.11%  |
| Intel Celeron           | 28        | 10.73%  |
| Intel Core i7           | 20        | 7.66%   |
| Intel Core i5           | 20        | 7.66%   |
| Intel Core 2 Duo        | 20        | 7.66%   |
| Intel Pentium           | 14        | 5.36%   |
| Intel Core i3           | 12        | 4.6%    |
| Intel Pentium Dual-Core | 11        | 4.21%   |
| Intel Genuine           | 11        | 4.21%   |
| Intel Core 2            | 10        | 3.83%   |
| Intel Core 2 Quad       | 8         | 3.07%   |
| Intel Pentium M         | 7         | 2.68%   |
| Intel Pentium 4         | 7         | 2.68%   |
| AMD Athlon 64 X2        | 7         | 2.68%   |
| Intel Pentium Dual      | 6         | 2.3%    |
| Other                   | 4         | 1.53%   |
| Intel Xeon              | 4         | 1.53%   |
| AMD A8                  | 4         | 1.53%   |
| AMD Phenom II X4        | 3         | 1.15%   |
| AMD E                   | 3         | 1.15%   |
| Intel Pentium D         | 2         | 0.77%   |
| AMD Turion 64 X2 Mobile | 2         | 0.77%   |
| AMD FX                  | 2         | 0.77%   |
| AMD E2                  | 2         | 0.77%   |
| AMD E1                  | 2         | 0.77%   |
| AMD Athlon II X2        | 2         | 0.77%   |
| AMD Athlon              | 2         | 0.77%   |
| AMD A6                  | 2         | 0.77%   |
| AMD A4                  | 2         | 0.77%   |
| Intel Core Duo          | 1         | 0.38%   |
| Intel Celeron M         | 1         | 0.38%   |
| Intel Celeron Dual-Core | 1         | 0.38%   |
| CentaurHauls VIA C7     | 1         | 0.38%   |
| AMD Turion 64 Mobile    | 1         | 0.38%   |
| AMD Sempron             | 1         | 0.38%   |
| AMD Ryzen 5             | 1         | 0.38%   |
| AMD Ryzen 3             | 1         | 0.38%   |
| AMD Phenom II           | 1         | 0.38%   |
| AMD Phenom              | 1         | 0.38%   |
| AMD G                   | 1         | 0.38%   |
| AMD C-60                | 1         | 0.38%   |
| AMD Athlon II X4        | 1         | 0.38%   |
| AMD Athlon 64           | 1         | 0.38%   |
| AMD A10                 | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 142       | 54.41%  |
| 1      | 61        | 23.37%  |
| 4      | 52        | 19.92%  |
| 6      | 5         | 1.92%   |
| 3      | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 261       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 168       | 64.37%  |
| 2      | 93        | 35.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 212       | 80.61%  |
| 32-bit         | 31        | 11.79%  |
| Unknown        | 20        | 7.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 28        | 10.57%  |
| Unknown    | 28        | 10.57%  |
| 0x206a7    | 19        | 7.17%   |
| 0x306a9    | 18        | 6.79%   |
| 0x6fd      | 16        | 6.04%   |
| 0x106ca    | 13        | 4.91%   |
| 0x106c2    | 11        | 4.15%   |
| 0x10661    | 8         | 3.02%   |
| 0x6d8      | 7         | 2.64%   |
| 0x806e9    | 6         | 2.26%   |
| 0x6f6      | 6         | 2.26%   |
| 0x406c4    | 6         | 2.26%   |
| 0x30678    | 6         | 2.26%   |
| 0x20655    | 6         | 2.26%   |
| 0x6e8      | 5         | 1.89%   |
| 0x05000119 | 5         | 1.89%   |
| 0x010000c8 | 5         | 1.89%   |
| 0xf41      | 4         | 1.51%   |
| 0x6fb      | 4         | 1.51%   |
| 0x6ec      | 4         | 1.51%   |
| 0x6f2      | 3         | 1.13%   |
| 0x40651    | 3         | 1.13%   |
| 0x10676    | 3         | 1.13%   |
| 0x07030105 | 3         | 1.13%   |
| 0x06006705 | 3         | 1.13%   |
| 0x06001119 | 3         | 1.13%   |
| 0xf65      | 2         | 0.75%   |
| 0x906ea    | 2         | 0.75%   |
| 0x806ec    | 2         | 0.75%   |
| 0x306d4    | 2         | 0.75%   |
| 0x306c3    | 2         | 0.75%   |
| 0x206c2    | 2         | 0.75%   |
| 0x20652    | 2         | 0.75%   |
| 0x07030106 | 2         | 0.75%   |
| 0xf62      | 1         | 0.38%   |
| 0xf47      | 1         | 0.38%   |
| 0xf43      | 1         | 0.38%   |
| 0xf33      | 1         | 0.38%   |
| 0xf27      | 1         | 0.38%   |
| 0x806ea    | 1         | 0.38%   |
| 0x806c1    | 1         | 0.38%   |
| 0x706a8    | 1         | 0.38%   |
| 0x706a1    | 1         | 0.38%   |
| 0x506c9    | 1         | 0.38%   |
| 0x306f2    | 1         | 0.38%   |
| 0x30661    | 1         | 0.38%   |
| 0x106e5    | 1         | 0.38%   |
| 0x106a5    | 1         | 0.38%   |
| 0x10677    | 1         | 0.38%   |
| 0x08701013 | 1         | 0.38%   |
| 0x08200103 | 1         | 0.38%   |
| 0x08108109 | 1         | 0.38%   |
| 0x0700010f | 1         | 0.38%   |
| 0x0600611a | 1         | 0.38%   |
| 0x06006118 | 1         | 0.38%   |
| 0x06000852 | 1         | 0.38%   |
| 0x06000822 | 1         | 0.38%   |
| 0x05000029 | 1         | 0.38%   |
| 0x010000db | 1         | 0.38%   |
| 0x01000083 | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Core          | 39        | 14.94%  |
| Penryn        | 33        | 12.64%  |
| Bonnell       | 25        | 9.58%   |
| IvyBridge     | 20        | 7.66%   |
| SandyBridge   | 19        | 7.28%   |
| P6            | 16        | 6.13%   |
| Silvermont    | 12        | 4.6%    |
| K8 Hammer     | 12        | 4.6%    |
| Westmere      | 11        | 4.21%   |
| NetBurst      | 11        | 4.21%   |
| KabyLake      | 11        | 4.21%   |
| K10           | 9         | 3.45%   |
| Haswell       | 7         | 2.68%   |
| Piledriver    | 6         | 2.3%    |
| Bobcat        | 6         | 2.3%    |
| Puma          | 5         | 1.92%   |
| Excavator     | 5         | 1.92%   |
| Broadwell     | 3         | 1.15%   |
| Nehalem       | 2         | 0.77%   |
| Goldmont plus | 2         | 0.77%   |
| Zen+          | 1         | 0.38%   |
| Zen 2         | 1         | 0.38%   |
| Zen           | 1         | 0.38%   |
| TigerLake     | 1         | 0.38%   |
| Jaguar        | 1         | 0.38%   |
| Goldmont      | 1         | 0.38%   |
| Unknown       | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 162       | 60%     |
| AMD                              | 52        | 19.26%  |
| Nvidia                           | 47        | 17.41%  |
| VIA Technologies                 | 5         | 1.85%   |
| Silicon Integrated Systems [SiS] | 4         | 1.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 22        | 7.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 5.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 3.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.26%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 2.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 2.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.95%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 6         | 1.95%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 1.63%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 1.3%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.3%    |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 0.98%   |
| Intel HD Graphics 620                                                                    | 3         | 0.98%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.98%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.98%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.98%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 0.98%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.98%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.65%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.65%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.65%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.65%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2         | 0.65%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2         | 0.65%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.65%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.65%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 2         | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.65%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 2         | 0.65%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.65%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.65%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 0.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.65%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 0.33%   |
| Nvidia NV44A [GeForce 6200]                                                              | 1         | 0.33%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                                    | 1         | 0.33%   |
| Nvidia NV43 [GeForce 6600 LE]                                                            | 1         | 0.33%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 0.33%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.33%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.33%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.33%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.33%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1         | 0.33%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.33%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.33%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 58.24%  |
| 1 x AMD        | 47        | 18.01%  |
| 1 x Nvidia     | 40        | 15.33%  |
| Intel + Nvidia | 7         | 2.68%   |
| 1 x VIA        | 5         | 1.92%   |
| 2 x AMD        | 4         | 1.53%   |
| 1 x SiS        | 4         | 1.53%   |
| Other          | 1         | 0.38%   |
| Intel + AMD    | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 233       | 88.59%  |
| Proprietary | 16        | 6.08%   |
| Unknown     | 14        | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 61.6%   |
| 0.01-0.5   | 63        | 23.95%  |
| 0.51-1.0   | 18        | 6.84%   |
| 1.01-2.0   | 13        | 4.94%   |
| 3.01-4.0   | 5         | 1.9%    |
| 7.01-8.0   | 1         | 0.38%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 15.54%  |
| AU Optronics            | 36        | 14.34%  |
| LG Display              | 18        | 7.17%   |
| Dell                    | 14        | 5.58%   |
| LG Philips              | 13        | 5.18%   |
| Acer                    | 13        | 5.18%   |
| Chi Mei Optoelectronics | 10        | 3.98%   |
| Hewlett-Packard         | 9         | 3.59%   |
| Goldstar                | 9         | 3.59%   |
| HannStar                | 8         | 3.19%   |
| BOE                     | 7         | 2.79%   |
| BenQ                    | 7         | 2.79%   |
| Chimei Innolux          | 6         | 2.39%   |
| Sony                    | 5         | 1.99%   |
| Lenovo                  | 5         | 1.99%   |
| CPT                     | 5         | 1.99%   |
| InfoVision              | 3         | 1.2%    |
| Hitachi                 | 3         | 1.2%    |
| Apple                   | 3         | 1.2%    |
| AOC                     | 3         | 1.2%    |
| Ancor Communications    | 3         | 1.2%    |
| ___                     | 2         | 0.8%    |
| ViewSonic               | 2         | 0.8%    |
| Unknown                 | 2         | 0.8%    |
| Sharp                   | 2         | 0.8%    |
| LG Electronics          | 2         | 0.8%    |
| Vizio                   | 1         | 0.4%    |
| VIZ                     | 1         | 0.4%    |
| Vestel Elektronik       | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| Seiko/Epson             | 1         | 0.4%    |
| Sceptre Tech            | 1         | 0.4%    |
| Quanta Display          | 1         | 0.4%    |
| PANDA                   | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| Optoma                  | 1         | 0.4%    |
| OEM                     | 1         | 0.4%    |
| MPI                     | 1         | 0.4%    |
| LPL                     | 1         | 0.4%    |
| Lite-On                 | 1         | 0.4%    |
| KTC                     | 1         | 0.4%    |
| KDC                     | 1         | 0.4%    |
| Insignia                | 1         | 0.4%    |
| HKC                     | 1         | 0.4%    |
| FUS                     | 1         | 0.4%    |
| Fujitsu Siemens         | 1         | 0.4%    |
| Element                 | 1         | 0.4%    |
| CVT                     | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 2.33%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.16%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.16%   |
| BOE LCD Monitor BOE0705 1366x768 309x173mm 13.9-inch                     | 3         | 1.16%   |
| ___ LCD TV ___0101 1360x768                                              | 2         | 0.78%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch  | 2         | 0.78%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.78%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 0.78%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.78%   |
| Dell 1905FP DEL400C 1280x1024 380x310mm 19.3-inch                        | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.78%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 0.78%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                        | 2         | 0.78%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                        | 1         | 0.39%   |
| VIZ LCD Monitor D50-D1 1920x1080                                         | 1         | 0.39%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                 | 1         | 0.39%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 1         | 0.39%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                            | 1         | 0.39%   |
| Toshiba TV TSB0206 1920x1080                                             | 1         | 0.39%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                             | 1         | 0.39%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                      | 1         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.39%   |
| Sony LCD Monitor TV                                                      | 1         | 0.39%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 0.39%   |
| Sharp LCD SHP1047 1920x1080                                              | 1         | 0.39%   |
| Sharp LCD SHP0FF0 1360x768                                               | 1         | 0.39%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.39%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                    | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch     | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch     | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch     | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.39%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.39%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch         | 1         | 0.39%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SyncMaster 2624x1200                     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SMB1930NW 1440x900                       | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 71        | 28.29%  |
| 1920x1080 (FHD)    | 53        | 21.12%  |
| 1280x800 (WXGA)    | 29        | 11.55%  |
| 1024x600           | 14        | 5.58%   |
| 1280x1024 (SXGA)   | 13        | 5.18%   |
| 1600x900 (HD+)     | 10        | 3.98%   |
| 1024x768 (XGA)     | 9         | 3.59%   |
| 1440x900 (WXGA+)   | 7         | 2.79%   |
| 2560x1440 (QHD)    | 6         | 2.39%   |
| 1360x768           | 6         | 2.39%   |
| 3840x2160 (4K)     | 5         | 1.99%   |
| 1680x1050 (WSXGA+) | 5         | 1.99%   |
| 1920x1200 (WUXGA)  | 4         | 1.59%   |
| 1920x540           | 3         | 1.2%    |
| Unknown            | 3         | 1.2%    |
| 2560x1080          | 2         | 0.8%    |
| 1280x768           | 2         | 0.8%    |
| 1024x576           | 2         | 0.8%    |
| 3840x1200          | 1         | 0.4%    |
| 3840x1080          | 1         | 0.4%    |
| 2624x1200          | 1         | 0.4%    |
| 2048x1152          | 1         | 0.4%    |
| 1600x1200          | 1         | 0.4%    |
| 1280x960           | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 82        | 32.54%  |
| Unknown | 17        | 6.75%   |
| 14      | 16        | 6.35%   |
| 13      | 16        | 6.35%   |
| 17      | 14        | 5.56%   |
| 10      | 14        | 5.56%   |
| 21      | 10        | 3.97%   |
| 27      | 9         | 3.57%   |
| 19      | 9         | 3.57%   |
| 24      | 8         | 3.17%   |
| 18      | 8         | 3.17%   |
| 11      | 8         | 3.17%   |
| 84      | 5         | 1.98%   |
| 31      | 5         | 1.98%   |
| 23      | 5         | 1.98%   |
| 22      | 5         | 1.98%   |
| 20      | 3         | 1.19%   |
| 12      | 3         | 1.19%   |
| 8       | 3         | 1.19%   |
| 72      | 2         | 0.79%   |
| 34      | 2         | 0.79%   |
| 26      | 2         | 0.79%   |
| 74      | 1         | 0.4%    |
| 41      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 39      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 109       | 43.78%  |
| 201-300     | 33        | 13.25%  |
| 401-500     | 28        | 11.24%  |
| 501-600     | 22        | 8.84%   |
| 351-400     | 18        | 7.23%   |
| Unknown     | 17        | 6.83%   |
| 1501-2000   | 8         | 3.21%   |
| 601-700     | 5         | 2.01%   |
| 701-800     | 3         | 1.2%    |
| 101-200     | 3         | 1.2%    |
| 801-900     | 2         | 0.8%    |
| 901-1000    | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 154       | 65.25%  |
| 16/10   | 41        | 17.37%  |
| Unknown | 13        | 5.51%   |
| 5/4     | 11        | 4.66%   |
| 4/3     | 11        | 4.66%   |
| 6/5     | 3         | 1.27%   |
| 21/9    | 2         | 0.85%   |
| 1.98    | 1         | 0.42%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 32.27%  |
| 81-90          | 25        | 9.96%   |
| 201-250        | 20        | 7.97%   |
| 151-200        | 18        | 7.17%   |
| Unknown        | 17        | 6.77%   |
| 41-50          | 14        | 5.58%   |
| 141-150        | 14        | 5.58%   |
| 351-500        | 9         | 3.59%   |
| More than 1000 | 8         | 3.19%   |
| 51-60          | 8         | 3.19%   |
| 301-350        | 8         | 3.19%   |
| 121-130        | 6         | 2.39%   |
| 71-80          | 5         | 1.99%   |
| 251-300        | 5         | 1.99%   |
| 61-70          | 3         | 1.2%    |
| 1-40           | 3         | 1.2%    |
| 501-1000       | 3         | 1.2%    |
| 131-140        | 2         | 0.8%    |
| 91-100         | 2         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 100       | 41.15%  |
| 101-120 | 89        | 36.63%  |
| 121-160 | 27        | 11.11%  |
| Unknown | 17        | 7%      |
| 1-50    | 6         | 2.47%   |
| 161-240 | 4         | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 223       | 84.79%  |
| 2     | 28        | 10.65%  |
| 0     | 10        | 3.8%    |
| 3     | 2         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 125       | 28.15%  |
| Intel                             | 83        | 18.69%  |
| Qualcomm Atheros                  | 66        | 14.86%  |
| Broadcom                          | 56        | 12.61%  |
| Marvell Technology Group          | 18        | 4.05%   |
| Broadcom Limited                  | 14        | 3.15%   |
| Nvidia                            | 13        | 2.93%   |
| Ralink Technology                 | 10        | 2.25%   |
| Ralink                            | 6         | 1.35%   |
| VIA Technologies                  | 5         | 1.13%   |
| Samsung Electronics               | 4         | 0.9%    |
| TP-Link                           | 3         | 0.68%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.68%   |
| Qualcomm Atheros Communications   | 3         | 0.68%   |
| Gemtek                            | 3         | 0.68%   |
| D-Link                            | 3         | 0.68%   |
| ASUSTek Computer                  | 3         | 0.68%   |
| NetGear                           | 2         | 0.45%   |
| JMicron Technology                | 2         | 0.45%   |
| DisplayLink                       | 2         | 0.45%   |
| Belkin Components                 | 2         | 0.45%   |
| 3Com                              | 2         | 0.45%   |
| Xiaomi                            | 1         | 0.23%   |
| Spreadtrum Communications         | 1         | 0.23%   |
| Motorola PCS                      | 1         | 0.23%   |
| Micro Star International          | 1         | 0.23%   |
| MediaTek                          | 1         | 0.23%   |
| Linksys                           | 1         | 0.23%   |
| LG Electronics                    | 1         | 0.23%   |
| Huawei Technologies               | 1         | 0.23%   |
| Ericsson Business Mobile Networks | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| BUFFALO                           | 1         | 0.23%   |
| Attansic Technology               | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |
| AMD                               | 1         | 0.23%   |
| ADMtek                            | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 52        | 10.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 34        | 6.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 16        | 3.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 2.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 8         | 1.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.4%    |
| Nvidia MCP61 Ethernet                                                   | 7         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 6         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 1%      |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1%      |
| VIA VT6102/VT6103 [Rhine-II]                                            | 4         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.8%    |
| Realtek 802.11ac NIC                                                    | 4         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.8%    |
| Intel Wireless 7260                                                     | 4         | 0.8%    |
| Intel Wireless 3165                                                     | 4         | 0.8%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.8%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                              | 4         | 0.8%    |
| Broadcom BCM4401-B0 100Base-TX                                          | 4         | 0.8%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.6%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 3         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.6%    |
| Intel Wireless 7265                                                     | 3         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.6%    |
| Intel 82579V Gigabit Network Connection                                 | 3         | 0.6%    |
| Intel 82566DM Gigabit Network Connection                                | 3         | 0.6%    |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 3         | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.4%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.4%    |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 2         | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.4%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 25.65%  |
| Qualcomm Atheros                | 48        | 20.87%  |
| Realtek Semiconductor           | 40        | 17.39%  |
| Broadcom                        | 33        | 14.35%  |
| Ralink Technology               | 10        | 4.35%   |
| Broadcom Limited                | 8         | 3.48%   |
| Ralink                          | 6         | 2.61%   |
| TP-Link                         | 3         | 1.3%    |
| Qualcomm Atheros Communications | 3         | 1.3%    |
| Gemtek                          | 3         | 1.3%    |
| D-Link                          | 3         | 1.3%    |
| ASUSTek Computer                | 3         | 1.3%    |
| NetGear                         | 2         | 0.87%   |
| Belkin Components               | 2         | 0.87%   |
| VIA Technologies                | 1         | 0.43%   |
| Samsung Electronics             | 1         | 0.43%   |
| Micro Star International        | 1         | 0.43%   |
| Marvell Technology Group        | 1         | 0.43%   |
| Linksys                         | 1         | 0.43%   |
| D-Link System                   | 1         | 0.43%   |
| BUFFALO                         | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 15        | 6.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 14        | 6.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 8         | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 6         | 2.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 2.16%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 5         | 2.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 5         | 2.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 4         | 1.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 4         | 1.73%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.73%   |
| Ralink MT7601U Wireless Adapter                                               | 4         | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 1.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 1.73%   |
| Intel Wireless 7260                                                           | 4         | 1.73%   |
| Intel Wireless 3165                                                           | 4         | 1.73%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 1.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 3         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3         | 1.3%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 3         | 1.3%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 3         | 1.3%    |
| Ralink RT5370 Wireless Adapter                                                | 3         | 1.3%    |
| Intel Wireless 7265                                                           | 3         | 1.3%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.3%    |
| Gemtek WUBR-177G [Ralink RT2571W]                                             | 3         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.87%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 0.87%   |
| Realtek RTL8187B Wireless Adapter                                             | 2         | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 0.87%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 0.87%   |
| Intel WiFi Link 5100                                                          | 2         | 0.87%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.87%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                  | 1         | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.43%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.43%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                              | 1         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.43%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 0.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.43%   |
| Realtek RTL8187 Wireless Adapter                                              | 1         | 0.43%   |
| Ralink RT5572 Wireless Adapter                                                | 1         | 0.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.43%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1         | 0.43%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1         | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.43%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 107       | 41.63%  |
| Intel                            | 39        | 15.18%  |
| Broadcom                         | 27        | 10.51%  |
| Qualcomm Atheros                 | 24        | 9.34%   |
| Marvell Technology Group         | 17        | 6.61%   |
| Nvidia                           | 13        | 5.06%   |
| Broadcom Limited                 | 7         | 2.72%   |
| VIA Technologies                 | 4         | 1.56%   |
| Silicon Integrated Systems [SiS] | 3         | 1.17%   |
| Samsung Electronics              | 3         | 1.17%   |
| JMicron Technology               | 2         | 0.78%   |
| DisplayLink                      | 2         | 0.78%   |
| 3Com                             | 2         | 0.78%   |
| Xiaomi                           | 1         | 0.39%   |
| Spreadtrum Communications        | 1         | 0.39%   |
| MediaTek                         | 1         | 0.39%   |
| LG Electronics                   | 1         | 0.39%   |
| Attansic Technology              | 1         | 0.39%   |
| ASIX Electronics                 | 1         | 0.39%   |
| ADMtek                           | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 20.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 13.13%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16        | 6.18%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 3.09%   |
| Nvidia MCP61 Ethernet                                             | 7         | 2.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 2.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.54%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 4         | 1.54%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.16%   |
| Intel 82566DM Gigabit Network Connection                          | 3         | 1.16%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.77%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.77%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.77%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 0.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 0.77%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 0.77%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.77%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.77%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.77%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 0.77%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2         | 0.77%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.39%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.39%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.39%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.39%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.39%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.39%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.39%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 0.39%   |
| MediaTek TECNO SPARK 6 Go                                         | 1         | 0.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.39%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.39%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 0.39%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.39%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.39%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.39%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 242       | 51.71%  |
| WiFi     | 216       | 46.15%  |
| Modem    | 9         | 1.92%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 61.54%  |
| Ethernet | 105       | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 162       | 62.07%  |
| 1     | 90        | 34.48%  |
| 0     | 6         | 2.3%    |
| 3     | 3         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 246       | 93.54%  |
| Yes  | 17        | 6.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 21.15%  |
| Qualcomm Atheros Communications | 14        | 13.46%  |
| Cambridge Silicon Radio         | 11        | 10.58%  |
| Broadcom                        | 11        | 10.58%  |
| Realtek Semiconductor           | 6         | 5.77%   |
| Hewlett-Packard                 | 6         | 5.77%   |
| Toshiba                         | 4         | 3.85%   |
| Lite-On Technology              | 4         | 3.85%   |
| Foxconn International           | 4         | 3.85%   |
| Foxconn / Hon Hai               | 4         | 3.85%   |
| IMC Networks                    | 3         | 2.88%   |
| ASUSTek Computer                | 3         | 2.88%   |
| Apple                           | 3         | 2.88%   |
| Ralink                          | 2         | 1.92%   |
| Dell                            | 2         | 1.92%   |
| Alps Electric                   | 2         | 1.92%   |
| Primax Electronics              | 1         | 0.96%   |
| Kensington                      | 1         | 0.96%   |
| Fujitsu Siemens Computers       | 1         | 0.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 11.54%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 10.58%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 5.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 4.81%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 3.85%   |
| Realtek Bluetooth Radio                             | 3         | 2.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 2.88%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 2.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.92%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.92%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.92%   |
| ASUS Bluetooth Radio                                | 2         | 1.92%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.92%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.96%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.96%   |
| Toshiba Bluetooth Device                            | 1         | 0.96%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.96%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.96%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.96%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1         | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.96%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.96%   |
| Lite-On Bluetooth Device                            | 1         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.96%   |
| Kensington Bluetooth EDR Dongle                     | 1         | 0.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.96%   |
| Intel Bluetooth Device                              | 1         | 0.96%   |
| Intel AX200 Bluetooth                               | 1         | 0.96%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.96%   |
| IMC Networks Bluetooth module                       | 1         | 0.96%   |
| IMC Networks Bluetooth Device                       | 1         | 0.96%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 0.96%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.96%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 0.96%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.96%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.96%   |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 0.96%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.96%   |
| Broadcom Bluetooth Controller                       | 1         | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.96%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.96%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.96%   |
| Apple Bluetooth HCI                                 | 1         | 0.96%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 0.96%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 191       | 62.42%  |
| AMD                                             | 48        | 15.69%  |
| Nvidia                                          | 35        | 11.44%  |
| VIA Technologies                                | 7         | 2.29%   |
| C-Media Electronics                             | 7         | 2.29%   |
| Silicon Integrated Systems [SiS]                | 5         | 1.63%   |
| Creative Labs                                   | 5         | 1.63%   |
| Logitech                                        | 2         | 0.65%   |
| ULi Electronics                                 | 1         | 0.33%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.33%   |
| Generalplus Technology                          | 1         | 0.33%   |
| Elite Silicon                                   | 1         | 0.33%   |
| Creative Technology                             | 1         | 0.33%   |
| Corsair                                         | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 50        | 14.62%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 27        | 7.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 4.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 4.09%   |
| AMD FCH Azalia Controller                                                                         | 11        | 3.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 2.05%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 7         | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.46%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.46%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 4         | 1.17%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.17%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 1.17%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.17%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 3         | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 0.88%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.58%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.58%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.58%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 2         | 0.58%   |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.58%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 2         | 0.58%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.58%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.58%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.58%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 0.58%   |
| ULi Electronics HD Audio Controller                                                               | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.29%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.29%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.29%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.29%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.29%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 15        | 25%     |
| Samsung Electronics | 13        | 21.67%  |
| SK hynix            | 8         | 13.33%  |
| Micron Technology   | 5         | 8.33%   |
| Kingston            | 4         | 6.67%   |
| Crucial             | 3         | 5%      |
| Corsair             | 2         | 3.33%   |
| Toshiba             | 1         | 1.67%   |
| Smart               | 1         | 1.67%   |
| Ramaxel Technology  | 1         | 1.67%   |
| Nanya Technology    | 1         | 1.67%   |
| Infineon            | 1         | 1.67%   |
| G.Skill             | 1         | 1.67%   |
| Elpida              | 1         | 1.67%   |
| A-DATA Technology   | 1         | 1.67%   |
| 48spaces            | 1         | 1.67%   |
| Unknown             | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 2.99%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 2         | 2.99%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s                 | 2         | 2.99%   |
| Unknown RAM Module SODIMM DDR                               | 1         | 1.49%   |
| Unknown RAM Module 512MB SODIMM DDR                         | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DRAM                       | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s              | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s              | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s              | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3                       | 1         | 1.49%   |
| Unknown RAM Module 1GB SODIMM SDRAM                         | 1         | 1.49%   |
| Unknown RAM Module 1GB DIMM DDR2                            | 1         | 1.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 1.49%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                | 1         | 1.49%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                      | 1         | 1.49%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                    | 1         | 1.49%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s       | 1         | 1.49%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s        | 1         | 1.49%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s        | 1         | 1.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                | 1         | 1.49%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                 | 1         | 1.49%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                  | 1         | 1.49%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1         | 1.49%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 1.49%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 1.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s         | 1         | 1.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.49%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 1         | 1.49%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s       | 1         | 1.49%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s        | 1         | 1.49%   |
| Samsung RAM M378B2873FHS-CH9 1024MB DIMM DDR3 1333MT/s      | 1         | 1.49%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.49%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s          | 1         | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 1         | 1.49%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s          | 1         | 1.49%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.49%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s         | 1         | 1.49%   |
| Kingston RAM ASU1333S9-4G-ECEWG 4GB SODIMM DDR3 1333MT/s    | 1         | 1.49%   |
| Kingston RAM 9905734-019.A00G 16384MB DIMM DDR4 2400MT/s    | 1         | 1.49%   |
| Kingston RAM 9905713-017.A00G 4GB DIMM DDR4 2866MT/s        | 1         | 1.49%   |
| Kingston RAM 9905428-196.A00LF 8192MB SODIMM DDR3 1333MT/s  | 1         | 1.49%   |
| Infineon RAM Module 256MB DIMM DDR2 533MT/s                 | 1         | 1.49%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1867MT/s          | 1         | 1.49%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s       | 1         | 1.49%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s  | 1         | 1.49%   |
| Crucial RAM CT102464BF1339.C16 8GB SODIMM DDR3 1333MT/s     | 1         | 1.49%   |
| Crucial RAM BLS8G3D18ADS3 8GB DIMM DDR3 1866MT/s            | 1         | 1.49%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s  | 1         | 1.49%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s      | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 35        | 61.4%   |
| DDR2    | 7         | 12.28%  |
| SDRAM   | 5         | 8.77%   |
| DDR     | 4         | 7.02%   |
| DDR4    | 3         | 5.26%   |
| Unknown | 2         | 3.51%   |
| DRAM    | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 67.86%  |
| DIMM         | 16        | 28.57%  |
| Row Of Chips | 1         | 1.79%   |
| Chip         | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 20        | 32.26%  |
| 2048    | 20        | 32.26%  |
| 1024    | 9         | 14.52%  |
| 8192    | 8         | 12.9%   |
| 512     | 2         | 3.23%   |
| 16384   | 1         | 1.61%   |
| 256     | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 32.79%  |
| 1333    | 10        | 16.39%  |
| Unknown | 9         | 14.75%  |
| 1334    | 3         | 4.92%   |
| 800     | 3         | 4.92%   |
| 2400    | 2         | 3.28%   |
| 1066    | 2         | 3.28%   |
| 667     | 2         | 3.28%   |
| 41632   | 1         | 1.64%   |
| 3200    | 1         | 1.64%   |
| 2866    | 1         | 1.64%   |
| 2048    | 1         | 1.64%   |
| 1867    | 1         | 1.64%   |
| 1866    | 1         | 1.64%   |
| 1067    | 1         | 1.64%   |
| 533     | 1         | 1.64%   |
| 320     | 1         | 1.64%   |
| 100     | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Seiko Epson         | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson XP-243 245 247 Series    | 1         | 14.29%  |
| Samsung ML-216x Series Laser Printer | 1         | 14.29%  |
| HP OfficeJet 5200 series             | 1         | 14.29%  |
| Canon TS3300 series                  | 1         | 14.29%  |
| Brother HL-L2360D series             | 1         | 14.29%  |
| Brother HL-L2350DW series            | 1         | 14.29%  |
| Brother HL-L2340D series             | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 24.82%  |
| Acer                                   | 13        | 9.49%   |
| Suyin                                  | 11        | 8.03%   |
| Realtek Semiconductor                  | 10        | 7.3%    |
| IMC Networks                           | 10        | 7.3%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.11%   |
| Z-Star Microelectronics                | 6         | 4.38%   |
| Ricoh                                  | 6         | 4.38%   |
| Microdia                               | 6         | 4.38%   |
| Sunplus Innovation Technology          | 5         | 3.65%   |
| Syntek                                 | 3         | 2.19%   |
| Silicon Motion                         | 3         | 2.19%   |
| Logitech                               | 3         | 2.19%   |
| Importek                               | 3         | 2.19%   |
| ALi                                    | 3         | 2.19%   |
| Samsung Electronics                    | 2         | 1.46%   |
| Cubeternet                             | 2         | 1.46%   |
| Apple                                  | 2         | 1.46%   |
| OmniVision Technologies                | 1         | 0.73%   |
| Lite-On Technology                     | 1         | 0.73%   |
| LG Electronics                         | 1         | 0.73%   |
| Lenovo                                 | 1         | 0.73%   |
| GEO Semi                               | 1         | 0.73%   |
| DigiTech                               | 1         | 0.73%   |
| Aveo Technology                        | 1         | 0.73%   |
| Alcor Micro                            | 1         | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 4         | 2.92%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 4         | 2.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 4         | 2.92%   |
| Acer EasyCamera                                             | 4         | 2.92%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 2.19%   |
| Chicony USB 2.0 Camera                                      | 3         | 2.19%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 2.19%   |
| Acer Lenovo Integrated Webcam                               | 3         | 2.19%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 2         | 1.46%   |
| Ricoh Sony Vaio Integrated Webcam                           | 2         | 1.46%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.46%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.46%   |
| Realtek Integrated Webcam                                   | 2         | 1.46%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 1.46%   |
| Importek HP Webcam-50                                       | 2         | 1.46%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.46%   |
| IMC Networks Integrated Webcam                              | 2         | 1.46%   |
| Chicony VGA Webcam                                          | 2         | 1.46%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.46%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.46%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 2         | 1.46%   |
| Acer Integrated Camera                                      | 2         | 1.46%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.73%   |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 0.73%   |
| Syntek USB Camera Device                                    | 1         | 0.73%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.73%   |
| Syntek Integrated Webcam                                    | 1         | 0.73%   |
| Suyin HP Webcam 101                                         | 1         | 0.73%   |
| Suyin HP Webcam                                             | 1         | 0.73%   |
| Suyin HP Truevision HD                                      | 1         | 0.73%   |
| Suyin HD Video WebCam                                       | 1         | 0.73%   |
| Suyin Acer OrbiCam                                          | 1         | 0.73%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.73%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.73%   |
| Sunplus SPCA2281 Web Camera                                 | 1         | 0.73%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.73%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 0.73%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.73%   |
| Sunplus Asus Webcam                                         | 1         | 0.73%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.73%   |
| Silicon Motion HP Webcam                                    | 1         | 0.73%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 0.73%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.73%   |
| Ricoh Integrated Webcam                                     | 1         | 0.73%   |
| Realtek USB2.0 camera                                       | 1         | 0.73%   |
| Realtek USB Camera                                          | 1         | 0.73%   |
| Realtek Integrated_Webcam_HD                                | 1         | 0.73%   |
| Realtek HP Truevision HD integrated webcam                  | 1         | 0.73%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.73%   |
| Realtek HD WebCam                                           | 1         | 0.73%   |
| OmniVision OV2640 Webcam                                    | 1         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_0.3M                      | 1         | 0.73%   |
| Microdia Integrated_Webcam_1.3M                             | 1         | 0.73%   |
| Microdia Integrated Webcam                                  | 1         | 0.73%   |
| Microdia 1.3 MPixel Integrated Webcam                       | 1         | 0.73%   |
| Logitech Webcam C270                                        | 1         | 0.73%   |
| Logitech Webcam C210                                        | 1         | 0.73%   |
| Logitech Webcam C110                                        | 1         | 0.73%   |
| Lite-On TOSHIBA Web Camera                                  | 1         | 0.73%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)       | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 33.33%  |
| AuthenTec             | 5         | 27.78%  |
| STMicroelectronics    | 4         | 22.22%  |
| Upek                  | 1         | 5.56%   |
| Synaptics             | 1         | 5.56%   |
| LighTuning Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                                      | 4         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 5.56%   |
| AuthenTec AES2810                                                          | 1         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 5.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.56%   |
| AuthenTec AES1600                                                          | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| O2 Micro         | 4         | 44.44%  |
| Broadcom         | 3         | 33.33%  |
| SCM Microsystems | 1         | 11.11%  |
| Alcor Micro      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 182       | 68.68%  |
| 1     | 67        | 25.28%  |
| 2     | 15        | 5.66%   |
| 4     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 21        | 21.21%  |
| Fingerprint reader       | 17        | 17.17%  |
| Graphics card            | 15        | 15.15%  |
| Communication controller | 9         | 9.09%   |
| Chipcard                 | 9         | 9.09%   |
| Storage                  | 6         | 6.06%   |
| Modem                    | 5         | 5.05%   |
| Camera                   | 4         | 4.04%   |
| Bluetooth                | 3         | 3.03%   |
| Sound                    | 2         | 2.02%   |
| Multimedia controller    | 2         | 2.02%   |
| Flash memory             | 2         | 2.02%   |
| Unassigned class         | 1         | 1.01%   |
| Storage/raid             | 1         | 1.01%   |
| Storage/ide              | 1         | 1.01%   |
| Net/ethernet             | 1         | 1.01%   |

