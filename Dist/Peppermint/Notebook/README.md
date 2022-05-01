Peppermint - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Peppermint.

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

Total: 277

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3421               | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | G575 4383                   | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| Dell          | Inspiron MM061              | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| Lenovo        | G575 4383                   | [7d2cce0d13](https://linux-hardware.org/?probe=7d2cce0d13) | Apr 01, 2022 |
| HP            | EliteBook 830 G5            | [271af2d869](https://linux-hardware.org/?probe=271af2d869) | Mar 30, 2022 |
| Packard Be... | EasyNote_MX45               | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| Dell          | Inspiron 1525               | [b8783a8415](https://linux-hardware.org/?probe=b8783a8415) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | [b0d58c6895](https://linux-hardware.org/?probe=b0d58c6895) | Mar 12, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Dell          | Latitude D630               | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Dell          | Latitude D630               | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Medion        | WIM2160                     | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| Medion        | WIM2160                     | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| ASUSTek       | 1000HE                      | [3cdc62c355](https://linux-hardware.org/?probe=3cdc62c355) | Jan 05, 2022 |
| Acer          | AOA110                      | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| Lenovo        | G575 4383                   | [ef4143d3b6](https://linux-hardware.org/?probe=ef4143d3b6) | Dec 22, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| Toshiba       | Satellite L300              | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| Acer          | Aspire 4810T                | [2f0aa07be8](https://linux-hardware.org/?probe=2f0aa07be8) | Nov 26, 2021 |
| Positivo      | Mobile                      | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Positivo      | Mobile                      | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| Dell          | Inspiron 1750               | [58d4a2dd00](https://linux-hardware.org/?probe=58d4a2dd00) | Nov 10, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | [15f9885d1f](https://linux-hardware.org/?probe=15f9885d1f) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| Toshiba       | Satellite L750D             | [e24684255d](https://linux-hardware.org/?probe=e24684255d) | Oct 26, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| Dell          | Inspiron 1750               | [0a56c60b24](https://linux-hardware.org/?probe=0a56c60b24) | Oct 11, 2021 |
| Dell          | Inspiron 1018               | [7f51bdb2d1](https://linux-hardware.org/?probe=7f51bdb2d1) | Oct 08, 2021 |
| HP            | 2000                        | [00f01e8929](https://linux-hardware.org/?probe=00f01e8929) | Oct 08, 2021 |
| Dell          | Inspiron 1750               | [be79dd5979](https://linux-hardware.org/?probe=be79dd5979) | Oct 06, 2021 |
| Acer          | Aspire R3-131T              | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| Unknown       | Unknown                     | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| Packard Be... | EasyNote TK85               | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| Sony          | VGN-S55B_S                  | [e531cd57e6](https://linux-hardware.org/?probe=e531cd57e6) | Aug 15, 2021 |
| HP            | EliteBook 820 G1            | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| Samsung       | N150P/N210P/N220P           | [0a9b2f9147](https://linux-hardware.org/?probe=0a9b2f9147) | Aug 08, 2021 |
| Olivetti      | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [827993d9c3](https://linux-hardware.org/?probe=827993d9c3) | Jul 17, 2021 |
| Olivetti      | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| Dell          | Precision M4600             | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| Olivetti      | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP            | Compaq Mini 110c-1100       | [9ba35acb61](https://linux-hardware.org/?probe=9ba35acb61) | Jun 24, 2021 |
| HP            | Compaq Mini 110c-1100       | [399e422d5b](https://linux-hardware.org/?probe=399e422d5b) | Jun 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09171395a9](https://linux-hardware.org/?probe=09171395a9) | Jun 22, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdbc4c8c02](https://linux-hardware.org/?probe=cdbc4c8c02) | Jun 22, 2021 |
| Toshiba       | NB500                       | [e5095d1545](https://linux-hardware.org/?probe=e5095d1545) | Jun 21, 2021 |
| Lenovo        | ThinkPad Edge E431 62775... | [6d6430f8ff](https://linux-hardware.org/?probe=6d6430f8ff) | Jun 18, 2021 |
| Acer          | AOA150                      | [7cbadcfcce](https://linux-hardware.org/?probe=7cbadcfcce) | Jun 13, 2021 |
| Toshiba       | NB500                       | [0a57436b83](https://linux-hardware.org/?probe=0a57436b83) | Jun 13, 2021 |
| Toshiba       | NB500                       | [be659779e6](https://linux-hardware.org/?probe=be659779e6) | Jun 13, 2021 |
| HP            | Mini 110-1100               | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| LincPlus      | P1                          | [4b49a81a7c](https://linux-hardware.org/?probe=4b49a81a7c) | May 30, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| LincPlus      | P1                          | [dd53e0757e](https://linux-hardware.org/?probe=dd53e0757e) | May 18, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| LincPlus      | P1                          | [bac5471f0f](https://linux-hardware.org/?probe=bac5471f0f) | May 15, 2021 |
| Sony          | VGN-S55B_S                  | [a874601f76](https://linux-hardware.org/?probe=a874601f76) | May 05, 2021 |
| JPSaCouto     | Intel powered classmate ... | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| Acer          | Extensa 5510                | [8e9e536486](https://linux-hardware.org/?probe=8e9e536486) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | [12b76c8bca](https://linux-hardware.org/?probe=12b76c8bca) | Apr 24, 2021 |
| HP            | EliteBook 2530p             | [d54424038e](https://linux-hardware.org/?probe=d54424038e) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | [562d38cca5](https://linux-hardware.org/?probe=562d38cca5) | Apr 18, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | [87befc0401](https://linux-hardware.org/?probe=87befc0401) | Apr 16, 2021 |
| Dell          | Inspiron 1545               | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Li1705                | [56c5cc70d1](https://linux-hardware.org/?probe=56c5cc70d1) | Apr 07, 2021 |
| Fujitsu Si... | AMILO Li1705                | [71e906faa3](https://linux-hardware.org/?probe=71e906faa3) | Apr 07, 2021 |
| Dell          | Latitude 7410               | [a72bb094fd](https://linux-hardware.org/?probe=a72bb094fd) | Mar 26, 2021 |
| Dell          | Vostro 3550                 | [ebd077e7f4](https://linux-hardware.org/?probe=ebd077e7f4) | Mar 16, 2021 |
| HP            | Pavilion g6                 | [6079cacf9b](https://linux-hardware.org/?probe=6079cacf9b) | Mar 14, 2021 |
| Samsung       | R530/R730/R540              | [a9fd173c51](https://linux-hardware.org/?probe=a9fd173c51) | Mar 13, 2021 |
| Dell          | Inspiron 1012               | [4c4bb4bd4a](https://linux-hardware.org/?probe=4c4bb4bd4a) | Mar 04, 2021 |
| Dell          | Inspiron N5050              | [b0cdfde6d1](https://linux-hardware.org/?probe=b0cdfde6d1) | Mar 02, 2021 |
| Dell          | Inspiron N5050              | [492714801f](https://linux-hardware.org/?probe=492714801f) | Mar 02, 2021 |
| ASUSTek       | K50C                        | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| Lenovo        | ThinkPad R60 94566FG        | [f0eb3f1d77](https://linux-hardware.org/?probe=f0eb3f1d77) | Feb 19, 2021 |
| Medion        | Akoya E4214 MD99570         | [3ae1e824ed](https://linux-hardware.org/?probe=3ae1e824ed) | Feb 13, 2021 |
| Toshiba       | Satellite L500              | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Apple         | MacBookAir3,2               | [e4d417012f](https://linux-hardware.org/?probe=e4d417012f) | Feb 08, 2021 |
| ASUSTek       | X541NA                      | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Unknown       | Unknown                     | [cf6b92a979](https://linux-hardware.org/?probe=cf6b92a979) | Feb 07, 2021 |
| Acer          | Aspire 7730G                | [6fadc9e655](https://linux-hardware.org/?probe=6fadc9e655) | Jan 31, 2021 |
| Toshiba       | Satellite L300              | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Sony          | VPCZ21V9E                   | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Acer          | AOD255                      | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Sony          | VPCZ21V9E                   | [27d806e418](https://linux-hardware.org/?probe=27d806e418) | Jan 02, 2021 |
| Sony          | VPCZ21V9E                   | [a1dc463ae7](https://linux-hardware.org/?probe=a1dc463ae7) | Jan 02, 2021 |
| Lenovo        | ThinkPad T450 20BUS3CF00    | [4dde602ff6](https://linux-hardware.org/?probe=4dde602ff6) | Jan 01, 2021 |
| Acer          | Extensa 5630                | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| Sony          | VPCZ21V9E                   | [b34a53e0e2](https://linux-hardware.org/?probe=b34a53e0e2) | Dec 29, 2020 |
| Acer          | Extensa 5510                | [efd4fce381](https://linux-hardware.org/?probe=efd4fce381) | Dec 29, 2020 |
| Acer          | Aspire 5738                 | [56f8292d5b](https://linux-hardware.org/?probe=56f8292d5b) | Dec 23, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Acer          | Extensa 5220                | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Dell          | Precision M4700             | [58d2d0e8d4](https://linux-hardware.org/?probe=58d2d0e8d4) | Dec 11, 2020 |
| Dell          | Precision M4700             | [379e1a461c](https://linux-hardware.org/?probe=379e1a461c) | Dec 09, 2020 |
| Dell          | Inspiron N5050              | [ac934f7ac7](https://linux-hardware.org/?probe=ac934f7ac7) | Dec 07, 2020 |
| Dell          | Inspiron N5050              | [8f2d17e846](https://linux-hardware.org/?probe=8f2d17e846) | Dec 07, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [7499600f8c](https://linux-hardware.org/?probe=7499600f8c) | Dec 02, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [fed85859bc](https://linux-hardware.org/?probe=fed85859bc) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| ASUSTek       | 1015PN                      | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
| Sony          | VGN-S55B_S                  | [534a526520](https://linux-hardware.org/?probe=534a526520) | Nov 08, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| Samsung       | N150P/N210P/N220P           | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| Google        | Gnawty                      | [6bb50a022d](https://linux-hardware.org/?probe=6bb50a022d) | Oct 10, 2020 |
| Toshiba       | QOSMIO F755                 | [defa9c775a](https://linux-hardware.org/?probe=defa9c775a) | Oct 01, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [64da7044cf](https://linux-hardware.org/?probe=64da7044cf) | Sep 26, 2020 |
| Medion        | Akoya E4214 MD99570         | [e45ead8de9](https://linux-hardware.org/?probe=e45ead8de9) | Sep 20, 2020 |
| Samsung       | R610                        | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| ASUSTek       | T101HA                      | [036f4f2304](https://linux-hardware.org/?probe=036f4f2304) | Sep 15, 2020 |
| ASUSTek       | P53E                        | [75d3fa4178](https://linux-hardware.org/?probe=75d3fa4178) | Sep 04, 2020 |
| Lenovo        | IdeaPad Z460 20059          | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| HP            | Stream Laptop 11-y0XX       | [06dd4aecb5](https://linux-hardware.org/?probe=06dd4aecb5) | Sep 01, 2020 |
| Acer          | TravelMate B115-M           | [d3395dca0c](https://linux-hardware.org/?probe=d3395dca0c) | Aug 30, 2020 |
| Itautec       | Infoway                     | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| Toshiba       | Satellite C660              | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| HP            | EliteBook 2740p             | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | Infoway                     | [27a7c624d8](https://linux-hardware.org/?probe=27a7c624d8) | Jul 17, 2020 |
| Itautec       | Infoway                     | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Positivo      | N1103                       | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| Lenovo        | B490 37722SP                | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| Toshiba       | Satellite L500              | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| HP            | Compaq Presario C700        | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Mini 110-1000               | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | [eef6f0a50b](https://linux-hardware.org/?probe=eef6f0a50b) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Clevo         | W55xEU                      | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Toshiba       | Satellite M70               | [c9e02a940d](https://linux-hardware.org/?probe=c9e02a940d) | May 13, 2020 |
| ASUSTek       | Q400A                       | [075d494ee2](https://linux-hardware.org/?probe=075d494ee2) | May 10, 2020 |
| Lenovo        | B575 1450A7U                | [b781397fa7](https://linux-hardware.org/?probe=b781397fa7) | May 05, 2020 |
| Toshiba       | Satellite C660              | [3d10f5b306](https://linux-hardware.org/?probe=3d10f5b306) | May 03, 2020 |
| Toshiba       | Satellite C660              | [0e91d35b8e](https://linux-hardware.org/?probe=0e91d35b8e) | May 03, 2020 |
| Sony          | VGN-FW140E                  | [8aad1d7bfc](https://linux-hardware.org/?probe=8aad1d7bfc) | May 02, 2020 |
| Toshiba       | Satellite C660              | [bc3bd72199](https://linux-hardware.org/?probe=bc3bd72199) | May 01, 2020 |
| Toshiba       | Satellite C660              | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| Toshiba       | Satellite PRO C850          | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5ddee791c7](https://linux-hardware.org/?probe=5ddee791c7) | Apr 20, 2020 |
| ASUSTek       | X45U                        | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Acer          | Aspire ES1-521              | [20e7fea349](https://linux-hardware.org/?probe=20e7fea349) | Apr 08, 2020 |
| Lenovo        | 433328G                     | [3c5b9e3703](https://linux-hardware.org/?probe=3c5b9e3703) | Apr 07, 2020 |
| Acer          | Aspire ES1-521              | [0c74c17c24](https://linux-hardware.org/?probe=0c74c17c24) | Apr 07, 2020 |
| HP            | 2133 (FU346EA)              | [499f685a66](https://linux-hardware.org/?probe=499f685a66) | Mar 31, 2020 |
| HP            | 2133 (FU346EA)              | [2c6f9bf922](https://linux-hardware.org/?probe=2c6f9bf922) | Mar 31, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [8fae01eff8](https://linux-hardware.org/?probe=8fae01eff8) | Mar 31, 2020 |
| HP            | 255 G2                      | [7cfb9e5a0e](https://linux-hardware.org/?probe=7cfb9e5a0e) | Mar 25, 2020 |
| Clevo         | W55xEU                      | [09d70e49b4](https://linux-hardware.org/?probe=09d70e49b4) | Mar 23, 2020 |
| ASUSTek       | F3E                         | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| ASUSTek       | F3E                         | [51ae68d38f](https://linux-hardware.org/?probe=51ae68d38f) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [5d53434528](https://linux-hardware.org/?probe=5d53434528) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [8491571d31](https://linux-hardware.org/?probe=8491571d31) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | Pavilion dv6500             | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| Lenovo        | 3000 N500 423374G           | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| eMachines     | E520                        | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| HP            | Pavilion dv4                | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Acer          | Aspire 7730G                | [f00cf2c184](https://linux-hardware.org/?probe=f00cf2c184) | Feb 13, 2020 |
| Toshiba       | Satellite C850-F117         | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Sony          | VGN-CR21S_P                 | [2ceca1462f](https://linux-hardware.org/?probe=2ceca1462f) | Feb 08, 2020 |
| Apple         | MacBook4,1                  | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| Apple         | MacBook4,1                  | [516c8bcbc2](https://linux-hardware.org/?probe=516c8bcbc2) | Feb 06, 2020 |
| Apple         | MacBook4,1                  | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Apple         | MacBook4,1                  | [17eb93e1dc](https://linux-hardware.org/?probe=17eb93e1dc) | Feb 04, 2020 |
| Toshiba       | NB520                       | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | [20c5cb5e37](https://linux-hardware.org/?probe=20c5cb5e37) | Feb 02, 2020 |
| Toshiba       | NB520                       | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | [e341d904c9](https://linux-hardware.org/?probe=e341d904c9) | Feb 01, 2020 |
| Apple         | MacBook4,1                  | [0244fb9c97](https://linux-hardware.org/?probe=0244fb9c97) | Feb 01, 2020 |
| ASUSTek       | S500CA                      | [4f82008cac](https://linux-hardware.org/?probe=4f82008cac) | Jan 29, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Sony          | VPCCW21FX                   | [78ac20109b](https://linux-hardware.org/?probe=78ac20109b) | Jan 21, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d87b9779d7](https://linux-hardware.org/?probe=d87b9779d7) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c6595736b8](https://linux-hardware.org/?probe=c6595736b8) | Jan 14, 2020 |
| HP            | Laptop 15-db0xxx            | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Toshiba       | Satellite C850-F117         | [5b8f68dbc9](https://linux-hardware.org/?probe=5b8f68dbc9) | Nov 26, 2019 |
| Toshiba       | Satellite C55D-B            | [0d1bbd1e60](https://linux-hardware.org/?probe=0d1bbd1e60) | Nov 25, 2019 |
| Toshiba       | Satellite C55D-B            | [98653dbce0](https://linux-hardware.org/?probe=98653dbce0) | Nov 25, 2019 |
| Lenovo        | G500 20236                  | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| HP            | Pavilion 11 x360 PC         | [6b30a9e102](https://linux-hardware.org/?probe=6b30a9e102) | Nov 11, 2019 |
| HP            | Pavilion 11 x360 PC         | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| HP            | Pavilion Notebook           | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | Pavilion Notebook           | [5f57cac098](https://linux-hardware.org/?probe=5f57cac098) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| Dell          | Inspiron 1501               | [a638607db3](https://linux-hardware.org/?probe=a638607db3) | Sep 11, 2019 |
| Unknown       | Unknown                     | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Pavilion dv7                | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | [cca643879f](https://linux-hardware.org/?probe=cca643879f) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | [de103d8a7d](https://linux-hardware.org/?probe=de103d8a7d) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| Gateway       | MX6940M                     | [668db92873](https://linux-hardware.org/?probe=668db92873) | May 09, 2019 |
| Dell          | Latitude D630               | [6ad005d6b7](https://linux-hardware.org/?probe=6ad005d6b7) | May 02, 2019 |
| WinBook       | GL Series                   | [89dac45ef6](https://linux-hardware.org/?probe=89dac45ef6) | Apr 28, 2019 |
| Dell          | Latitude D630               | [d8bf959191](https://linux-hardware.org/?probe=d8bf959191) | Apr 16, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | [c662baa8f5](https://linux-hardware.org/?probe=c662baa8f5) | Apr 10, 2019 |
| eMachines     | E620                        | [de3cfd34b1](https://linux-hardware.org/?probe=de3cfd34b1) | Apr 05, 2019 |
| Dell          | Latitude D430               | [aea800be22](https://linux-hardware.org/?probe=aea800be22) | Apr 04, 2019 |
| Dell          | Latitude D430               | [269e1c2948](https://linux-hardware.org/?probe=269e1c2948) | Apr 04, 2019 |
| Dell          | Latitude D430               | [9dd4a1b244](https://linux-hardware.org/?probe=9dd4a1b244) | Apr 04, 2019 |
| Dell          | Latitude D430               | [17a12cad0d](https://linux-hardware.org/?probe=17a12cad0d) | Apr 04, 2019 |
| Dell          | Latitude D430               | [16f2fbe2de](https://linux-hardware.org/?probe=16f2fbe2de) | Apr 04, 2019 |
| Dell          | Latitude D430               | [8543e95fc3](https://linux-hardware.org/?probe=8543e95fc3) | Apr 04, 2019 |
| Dell          | Latitude D430               | [9e16bfb2d0](https://linux-hardware.org/?probe=9e16bfb2d0) | Apr 04, 2019 |
| Dell          | Latitude D430               | [d223b893eb](https://linux-hardware.org/?probe=d223b893eb) | Apr 04, 2019 |
| Dell          | Latitude D430               | [61c869b04b](https://linux-hardware.org/?probe=61c869b04b) | Apr 04, 2019 |
| Dell          | Latitude D430               | [d1c49bd4e8](https://linux-hardware.org/?probe=d1c49bd4e8) | Apr 04, 2019 |
| Positivo      | Mobile                      | [dda25a3dc9](https://linux-hardware.org/?probe=dda25a3dc9) | Apr 03, 2019 |
| Positivo      | Mobile                      | [aebfedfabb](https://linux-hardware.org/?probe=aebfedfabb) | Apr 03, 2019 |
| HP            | Pavilion dv1000 (PS600EA... | [6802b34fdd](https://linux-hardware.org/?probe=6802b34fdd) | Mar 31, 2019 |
| Acer          | Aspire 7730G                | [1a165b3312](https://linux-hardware.org/?probe=1a165b3312) | Mar 08, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [0df880aebd](https://linux-hardware.org/?probe=0df880aebd) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Acer          | Aspire 7730G                | [09bd4355b9](https://linux-hardware.org/?probe=09bd4355b9) | Jan 30, 2019 |
| Clevo         | M660SR                      | [647fd58075](https://linux-hardware.org/?probe=647fd58075) | Jan 15, 2019 |
| Clevo         | M660SR                      | [ad84ff197d](https://linux-hardware.org/?probe=ad84ff197d) | Jan 15, 2019 |
| Lenovo        | ThinkPad W510 4391B49       | [227847df62](https://linux-hardware.org/?probe=227847df62) | Feb 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Peppermint 10   | 141       | 87.58%  |
| Peppermint 9    | 16        | 9.94%   |
| Peppermint 11.2 | 2         | 1.24%   |
| Peppermint 8    | 1         | 0.62%   |
| Peppermint      | 1         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Peppermint | 161       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.0.0-37-generic      | 23        | 12.64%  |
| 5.4.0-42-generic      | 8         | 4.4%    |
| 5.3.0-62-generic      | 7         | 3.85%   |
| 5.3.0-51-generic      | 7         | 3.85%   |
| 4.18.0-18-generic     | 7         | 3.85%   |
| 5.4.0-65-generic      | 6         | 3.3%    |
| 4.15.0-43-generic     | 6         | 3.3%    |
| 5.4.0-91-generic      | 4         | 2.2%    |
| 5.4.0-72-generic      | 4         | 2.2%    |
| 5.4.0-58-generic      | 4         | 2.2%    |
| 5.0.0-32-generic      | 4         | 2.2%    |
| 5.4.0-90-generic      | 3         | 1.65%   |
| 5.4.0-87-generic      | 3         | 1.65%   |
| 5.4.0-80-generic      | 3         | 1.65%   |
| 5.4.0-77-generic      | 3         | 1.65%   |
| 5.4.0-66-generic      | 3         | 1.65%   |
| 5.4.0-47-generic      | 3         | 1.65%   |
| 5.4.0-45-generic      | 3         | 1.65%   |
| 5.3.0-46-generic      | 3         | 1.65%   |
| 5.3.0-42-generic      | 3         | 1.65%   |
| 5.3.0-28-generic      | 3         | 1.65%   |
| 5.0.0-36-generic      | 3         | 1.65%   |
| 4.15.0-48-generic     | 3         | 1.65%   |
| 4.15.0-47-generic     | 3         | 1.65%   |
| 5.4.0-97-generic      | 2         | 1.1%    |
| 5.4.0-84-generic      | 2         | 1.1%    |
| 5.4.0-81-generic      | 2         | 1.1%    |
| 5.4.0-74-generic      | 2         | 1.1%    |
| 5.4.0-70-generic      | 2         | 1.1%    |
| 5.4.0-56-generic      | 2         | 1.1%    |
| 5.4.0-54-generic      | 2         | 1.1%    |
| 5.4.0-52-generic      | 2         | 1.1%    |
| 5.4.0-48-generic      | 2         | 1.1%    |
| 5.3.0-59-generic      | 2         | 1.1%    |
| 5.3.0-40-generic      | 2         | 1.1%    |
| 5.10.0-11-amd64       | 2         | 1.1%    |
| 5.0.0-27-generic      | 2         | 1.1%    |
| 4.18.0-21-generic     | 2         | 1.1%    |
| 4.15.0-76-generic     | 2         | 1.1%    |
| 5.4.95-050495-generic | 1         | 0.55%   |
| 5.4.0-99-generic      | 1         | 0.55%   |
| 5.4.0-94-generic      | 1         | 0.55%   |
| 5.4.0-92-generic      | 1         | 0.55%   |
| 5.4.0-73-generic      | 1         | 0.55%   |
| 5.4.0-71-generic      | 1         | 0.55%   |
| 5.4.0-67-generic      | 1         | 0.55%   |
| 5.4.0-64-generic      | 1         | 0.55%   |
| 5.4.0-62-generic      | 1         | 0.55%   |
| 5.4.0-60-generic      | 1         | 0.55%   |
| 5.4.0-59-generic      | 1         | 0.55%   |
| 5.4.0-53-generic      | 1         | 0.55%   |
| 5.4.0-51-generic      | 1         | 0.55%   |
| 5.4.0-49-generic      | 1         | 0.55%   |
| 5.4.0-44-generic      | 1         | 0.55%   |
| 5.4.0-109-generic     | 1         | 0.55%   |
| 5.4.0-104-generic     | 1         | 0.55%   |
| 5.3.6-050306-generic  | 1         | 0.55%   |
| 5.3.0-45-generic      | 1         | 0.55%   |
| 5.10.0-12-amd64       | 1         | 0.55%   |
| 5.1.11-050111-generic | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 75        | 44.64%  |
| 5.0.0   | 31        | 18.45%  |
| 5.3.0   | 27        | 16.07%  |
| 4.15.0  | 15        | 8.93%   |
| 4.18.0  | 13        | 7.74%   |
| 5.10.0  | 3         | 1.79%   |
| 5.4.95  | 1         | 0.6%    |
| 5.3.6   | 1         | 0.6%    |
| 5.1.11  | 1         | 0.6%    |
| 4.8.0   | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 45.24%  |
| 5.0     | 31        | 18.45%  |
| 5.3     | 28        | 16.67%  |
| 4.15    | 15        | 8.93%   |
| 4.18    | 13        | 7.74%   |
| 5.10    | 3         | 1.79%   |
| 5.1     | 1         | 0.6%    |
| 4.8     | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 62.73%  |
| i686   | 60        | 37.27%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXDE       | 119       | 72.56%  |
| Unknown    | 33        | 20.12%  |
| GNOME      | 7         | 4.27%   |
| XFCE       | 3         | 1.83%   |
| X-Cinnamon | 1         | 0.61%   |
| Peppermint | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 161       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 144       | 88.89%  |
| LightDM | 10        | 6.17%   |
| TDM     | 7         | 4.32%   |
| SDDM    | 1         | 0.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 50        | 30.49%  |
| Unknown | 27        | 16.46%  |
| en_GB   | 11        | 6.71%   |
| de_DE   | 10        | 6.1%    |
| pt_BR   | 8         | 4.88%   |
| it_IT   | 7         | 4.27%   |
| pl_PL   | 6         | 3.66%   |
| nl_NL   | 5         | 3.05%   |
| fr_FR   | 4         | 2.44%   |
| en_CA   | 4         | 2.44%   |
| C       | 4         | 2.44%   |
| ru_RU   | 3         | 1.83%   |
| es_AR   | 3         | 1.83%   |
| ja_JP   | 2         | 1.22%   |
| es_MX   | 2         | 1.22%   |
| en_IN   | 2         | 1.22%   |
| tr_TR   | 1         | 0.61%   |
| sv_SE   | 1         | 0.61%   |
| ro_RO   | 1         | 0.61%   |
| pt_PT   | 1         | 0.61%   |
| lv_LV   | 1         | 0.61%   |
| fi_FI   | 1         | 0.61%   |
| es_PE   | 1         | 0.61%   |
| es_PA   | 1         | 0.61%   |
| es_ES   | 1         | 0.61%   |
| es_CR   | 1         | 0.61%   |
| es_BO   | 1         | 0.61%   |
| en_ZA   | 1         | 0.61%   |
| en_PH   | 1         | 0.61%   |
| en_AU   | 1         | 0.61%   |
| el_GR   | 1         | 0.61%   |
| cs_CZ   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 128       | 79.5%   |
| EFI  | 33        | 20.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 135       | 82.82%  |
| Unknown  | 16        | 9.82%   |
| Overlay  | 5         | 3.07%   |
| Ext3     | 2         | 1.23%   |
| Ext2     | 2         | 1.23%   |
| Reiserfs | 1         | 0.61%   |
| Btrfs    | 1         | 0.61%   |
| Aufs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 147       | 90.74%  |
| GPT     | 8         | 4.94%   |
| MBR     | 7         | 4.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 94.48%  |
| Yes       | 9         | 5.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 87.8%   |
| Yes       | 20        | 12.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 20.5%   |
| Dell                | 19        | 11.8%   |
| Lenovo              | 18        | 11.18%  |
| ASUSTek Computer    | 17        | 10.56%  |
| Toshiba             | 16        | 9.94%   |
| Acer                | 14        | 8.7%    |
| Samsung Electronics | 7         | 4.35%   |
| Sony                | 5         | 3.11%   |
| Fujitsu Siemens     | 5         | 3.11%   |
| Positivo            | 3         | 1.86%   |
| eMachines           | 3         | 1.86%   |
| Packard Bell        | 2         | 1.24%   |
| Medion              | 2         | 1.24%   |
| IBM                 | 2         | 1.24%   |
| Gateway             | 2         | 1.24%   |
| Clevo               | 2         | 1.24%   |
| Apple               | 2         | 1.24%   |
| Unknown             | 2         | 1.24%   |
| WinBook             | 1         | 0.62%   |
| Olivetti            | 1         | 0.62%   |
| LincPlus            | 1         | 0.62%   |
| JPSaCouto           | 1         | 0.62%   |
| Itautec             | 1         | 0.62%   |
| Google              | 1         | 0.62%   |
| Fujitsu             | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite M70                      | 2         | 1.24%   |
| Toshiba Satellite L500                     | 2         | 1.24%   |
| Samsung N150P/N210P/N220P                  | 2         | 1.24%   |
| Positivo Mobile                            | 2         | 1.24%   |
| Lenovo G500 20236                          | 2         | 1.24%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 1.24%   |
| Dell Latitude D630                         | 2         | 1.24%   |
| Dell Inspiron N5050                        | 2         | 1.24%   |
| Acer Extensa 5630                          | 2         | 1.24%   |
| Unknown                                    | 2         | 1.24%   |
| WinBook GL Series                          | 1         | 0.62%   |
| Toshiba Satellite PRO C850                 | 1         | 0.62%   |
| Toshiba Satellite L750D                    | 1         | 0.62%   |
| Toshiba Satellite L310                     | 1         | 0.62%   |
| Toshiba Satellite L300                     | 1         | 0.62%   |
| Toshiba Satellite C850-F117                | 1         | 0.62%   |
| Toshiba Satellite C660                     | 1         | 0.62%   |
| Toshiba Satellite C55D-B                   | 1         | 0.62%   |
| Toshiba QOSMIO F755                        | 1         | 0.62%   |
| Toshiba PORTEGE R500                       | 1         | 0.62%   |
| Toshiba NB520                              | 1         | 0.62%   |
| Toshiba NB500                              | 1         | 0.62%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.62%   |
| Sony VPCZ21V9E                             | 1         | 0.62%   |
| Sony VPCCW21FX                             | 1         | 0.62%   |
| Sony VGN-S55B_S                            | 1         | 0.62%   |
| Sony VGN-FW140E                            | 1         | 0.62%   |
| Sony VGN-CR21S_P                           | 1         | 0.62%   |
| Samsung R610                               | 1         | 0.62%   |
| Samsung R530/R730/R540                     | 1         | 0.62%   |
| Samsung N150P                              | 1         | 0.62%   |
| Samsung N150/N210/N220                     | 1         | 0.62%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.62%   |
| Positivo N1103                             | 1         | 0.62%   |
| Packard Bell EasyNote_MX45                 | 1         | 0.62%   |
| Packard Bell EasyNote TK85                 | 1         | 0.62%   |
| Olivetti CL133A                            | 1         | 0.62%   |
| Medion WIM2160                             | 1         | 0.62%   |
| Medion Akoya E4214 MD99570                 | 1         | 0.62%   |
| LincPlus P1                                | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS0035US   | 1         | 0.62%   |
| Lenovo ThinkPad W510 4391B49               | 1         | 0.62%   |
| Lenovo ThinkPad T60 1951CJ4                | 1         | 0.62%   |
| Lenovo ThinkPad T450 20BUS3CF00            | 1         | 0.62%   |
| Lenovo ThinkPad R60 94566FG                | 1         | 0.62%   |
| Lenovo ThinkPad Edge E431 62775GU          | 1         | 0.62%   |
| Lenovo ThinkPad E490 20N90019BR            | 1         | 0.62%   |
| Lenovo IdeaPad Z460 20059                  | 1         | 0.62%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.62%   |
| Lenovo IdeaPad 1 11ADA05 82GV              | 1         | 0.62%   |
| Lenovo G575 4383                           | 1         | 0.62%   |
| Lenovo B575 1450A7U                        | 1         | 0.62%   |
| Lenovo B570e HuronRiver Platform           | 1         | 0.62%   |
| Lenovo B490 37722SP                        | 1         | 0.62%   |
| Lenovo 433328G                             | 1         | 0.62%   |
| Lenovo 3000 N500 423374G                   | 1         | 0.62%   |
| JPSaCouto Intel powered classmate PC       | 1         | 0.62%   |
| Itautec Infoway                            | 1         | 0.62%   |
| IBM ThinkPad X41 Tablet 1869CNG            | 1         | 0.62%   |
| IBM ThinkPad T43 2669GY4                   | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Toshiba Satellite       | 11        | 6.83%   |
| Dell Inspiron           | 10        | 6.21%   |
| HP Pavilion             | 9         | 5.59%   |
| Lenovo ThinkPad         | 7         | 4.35%   |
| HP Compaq               | 6         | 3.73%   |
| Dell Latitude           | 6         | 3.73%   |
| Acer Aspire             | 6         | 3.73%   |
| HP EliteBook            | 5         | 3.11%   |
| Acer Extensa            | 4         | 2.48%   |
| Samsung N150P           | 3         | 1.86%   |
| Lenovo IdeaPad          | 3         | 1.86%   |
| Fujitsu Siemens AMILO   | 3         | 1.86%   |
| Positivo Mobile         | 2         | 1.24%   |
| Packard Bell EasyNote   | 2         | 1.24%   |
| Lenovo G500             | 2         | 1.24%   |
| IBM ThinkPad            | 2         | 1.24%   |
| HP Stream               | 2         | 1.24%   |
| HP Mini                 | 2         | 1.24%   |
| HP Laptop               | 2         | 1.24%   |
| HP 255                  | 2         | 1.24%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.24%   |
| Dell Precision          | 2         | 1.24%   |
| Unknown                 | 2         | 1.24%   |
| WinBook GL              | 1         | 0.62%   |
| Toshiba QOSMIO          | 1         | 0.62%   |
| Toshiba PORTEGE         | 1         | 0.62%   |
| Toshiba NB520           | 1         | 0.62%   |
| Toshiba NB500           | 1         | 0.62%   |
| Toshiba dynabook        | 1         | 0.62%   |
| Sony VPCZ21V9E          | 1         | 0.62%   |
| Sony VPCCW21FX          | 1         | 0.62%   |
| Sony VGN-S55B           | 1         | 0.62%   |
| Sony VGN-FW140E         | 1         | 0.62%   |
| Sony VGN-CR21S          | 1         | 0.62%   |
| Samsung R610            | 1         | 0.62%   |
| Samsung R530            | 1         | 0.62%   |
| Samsung N150            | 1         | 0.62%   |
| Samsung 300E4A          | 1         | 0.62%   |
| Positivo N1103          | 1         | 0.62%   |
| Olivetti CL133A         | 1         | 0.62%   |
| Medion WIM2160          | 1         | 0.62%   |
| Medion Akoya            | 1         | 0.62%   |
| LincPlus P1             | 1         | 0.62%   |
| Lenovo G575             | 1         | 0.62%   |
| Lenovo B575             | 1         | 0.62%   |
| Lenovo B570e            | 1         | 0.62%   |
| Lenovo B490             | 1         | 0.62%   |
| Lenovo 433328G          | 1         | 0.62%   |
| Lenovo 3000             | 1         | 0.62%   |
| JPSaCouto Intel         | 1         | 0.62%   |
| Itautec Infoway         | 1         | 0.62%   |
| HP Presario             | 1         | 0.62%   |
| HP Notebook             | 1         | 0.62%   |
| HP 2133                 | 1         | 0.62%   |
| HP 2000                 | 1         | 0.62%   |
| HP 15                   | 1         | 0.62%   |
| Google Gnawty           | 1         | 0.62%   |
| Gateway MX6940M         | 1         | 0.62%   |
| Gateway Blade-K8F       | 1         | 0.62%   |
| Fujitsu LIFEBOOK        | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 25        | 15.53%  |
| 2011    | 19        | 11.8%   |
| 2009    | 17        | 10.56%  |
| 2010    | 16        | 9.94%   |
| 2007    | 16        | 9.94%   |
| 2006    | 12        | 7.45%   |
| 2012    | 10        | 6.21%   |
| 2013    | 9         | 5.59%   |
| 2014    | 7         | 4.35%   |
| 2015    | 6         | 3.73%   |
| 2018    | 5         | 3.11%   |
| 2016    | 5         | 3.11%   |
| 2005    | 5         | 3.11%   |
| 2019    | 3         | 1.86%   |
| 2017    | 3         | 1.86%   |
| 2020    | 2         | 1.24%   |
| Unknown | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 161       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 154       | 95.65%  |
| Enabled  | 7         | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 160       | 99.38%  |
| Yes  | 1         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 46        | 28.22%  |
| 1.01-2.0   | 46        | 28.22%  |
| 4.01-8.0   | 23        | 14.11%  |
| 0.51-1.0   | 17        | 10.43%  |
| 2.01-3.0   | 14        | 8.59%   |
| 8.01-16.0  | 10        | 6.13%   |
| 16.01-24.0 | 5         | 3.07%   |
| 32.01-64.0 | 1         | 0.61%   |
| 0.01-0.5   | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 69        | 38.33%  |
| 1.01-2.0 | 63        | 35%     |
| 2.01-3.0 | 25        | 13.89%  |
| 0.01-0.5 | 18        | 10%     |
| 3.01-4.0 | 3         | 1.67%   |
| 4.01-8.0 | 2         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 76.97%  |
| 2      | 31        | 18.79%  |
| 3      | 4         | 2.42%   |
| 0      | 3         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 58.9%   |
| No        | 67        | 41.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 92.55%  |
| No        | 12        | 7.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 98.76%  |
| No        | 2         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 53.09%  |
| Yes       | 76        | 46.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 40        | 24.84%  |
| Germany      | 16        | 9.94%   |
| UK           | 10        | 6.21%   |
| Netherlands  | 9         | 5.59%   |
| Italy        | 8         | 4.97%   |
| Canada       | 8         | 4.97%   |
| Brazil       | 8         | 4.97%   |
| Poland       | 6         | 3.73%   |
| France       | 5         | 3.11%   |
| Russia       | 4         | 2.48%   |
| Sweden       | 3         | 1.86%   |
| Spain        | 3         | 1.86%   |
| Romania      | 3         | 1.86%   |
| Mexico       | 3         | 1.86%   |
| Japan        | 3         | 1.86%   |
| Argentina    | 3         | 1.86%   |
| Portugal     | 2         | 1.24%   |
| India        | 2         | 1.24%   |
| Greece       | 2         | 1.24%   |
| Bolivia      | 2         | 1.24%   |
| Turkey       | 1         | 0.62%   |
| Switzerland  | 1         | 0.62%   |
| South Africa | 1         | 0.62%   |
| Serbia       | 1         | 0.62%   |
| Puerto Rico  | 1         | 0.62%   |
| Philippines  | 1         | 0.62%   |
| Peru         | 1         | 0.62%   |
| Panama       | 1         | 0.62%   |
| Norway       | 1         | 0.62%   |
| Namibia      | 1         | 0.62%   |
| Malaysia     | 1         | 0.62%   |
| Lithuania    | 1         | 0.62%   |
| Latvia       | 1         | 0.62%   |
| Kazakhstan   | 1         | 0.62%   |
| Ireland      | 1         | 0.62%   |
| Georgia      | 1         | 0.62%   |
| Finland      | 1         | 0.62%   |
| Czechia      | 1         | 0.62%   |
| Costa Rica   | 1         | 0.62%   |
| Belarus      | 1         | 0.62%   |
| Australia    | 1         | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toronto               | 4         | 2.4%    |
| Warsaw                | 2         | 1.2%    |
| Turin                 | 2         | 1.2%    |
| Topeka                | 2         | 1.2%    |
| Osasco                | 2         | 1.2%    |
| Oldenburg             | 2         | 1.2%    |
| Naples                | 2         | 1.2%    |
| Moscow                | 2         | 1.2%    |
| Bucharest             | 2         | 1.2%    |
| Bristol               | 2         | 1.2%    |
| Athens                | 2         | 1.2%    |
| Г„Г¤nekoski      | 1         | 0.6%    |
| Zvecka                | 1         | 0.6%    |
| Zaandam               | 1         | 0.6%    |
| Yokohama              | 1         | 0.6%    |
| Yacuiba               | 1         | 0.6%    |
| Wysokie Mazowieckie   | 1         | 0.6%    |
| Wutoeschingen         | 1         | 0.6%    |
| Windhoek              | 1         | 0.6%    |
| West Chester          | 1         | 0.6%    |
| Waalwijk              | 1         | 0.6%    |
| Villa MarÃ­a        | 1         | 0.6%    |
| Versailles            | 1         | 0.6%    |
| Verona                | 1         | 0.6%    |
| Venda do Pinheiro     | 1         | 0.6%    |
| Urk                   | 1         | 0.6%    |
| UmeГҐ               | 1         | 0.6%    |
| Tucson                | 1         | 0.6%    |
| The Hague             | 1         | 0.6%    |
| Telford               | 1         | 0.6%    |
| Tbilisi               | 1         | 0.6%    |
| Tahlequah             | 1         | 0.6%    |
| Stockton              | 1         | 0.6%    |
| Southampton           | 1         | 0.6%    |
| Sivas                 | 1         | 0.6%    |
| Sicklerville          | 1         | 0.6%    |
| Shoreham-by-Sea       | 1         | 0.6%    |
| Sherwood Park         | 1         | 0.6%    |
| Seattle               | 1         | 0.6%    |
| Scharendijke          | 1         | 0.6%    |
| Sao Paulo             | 1         | 0.6%    |
| Sant Celoni           | 1         | 0.6%    |
| Sant Boi de Llobregat | 1         | 0.6%    |
| San Rafael            | 1         | 0.6%    |
| Rugby                 | 1         | 0.6%    |
| Rotterdam             | 1         | 0.6%    |
| Queens                | 1         | 0.6%    |
| Pruzhany              | 1         | 0.6%    |
| Prince Frederick      | 1         | 0.6%    |
| Prague                | 1         | 0.6%    |
| Poznan                | 1         | 0.6%    |
| Pouso Alegre          | 1         | 0.6%    |
| Polokwane             | 1         | 0.6%    |
| Plankstadt            | 1         | 0.6%    |
| Piedmont              | 1         | 0.6%    |
| PetrГіpolis         | 1         | 0.6%    |
| Peseux                | 1         | 0.6%    |
| Perth                 | 1         | 0.6%    |
| Panama City           | 1         | 0.6%    |
| Oschatz               | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 40     | 21.84%  |
| WDC                 | 28        | 33     | 16.09%  |
| Unknown             | 18        | 21     | 10.34%  |
| Samsung Electronics | 18        | 30     | 10.34%  |
| Toshiba             | 16        | 17     | 9.2%    |
| Hitachi             | 14        | 17     | 8.05%   |
| Kingston            | 7         | 9      | 4.02%   |
| Fujitsu             | 5         | 6      | 2.87%   |
| SanDisk             | 4         | 5      | 2.3%    |
| HGST                | 4         | 5      | 2.3%    |
| PNY                 | 2         | 2      | 1.15%   |
| Integral            | 2         | 2      | 1.15%   |
| Zheino              | 1         | 1      | 0.57%   |
| TrekStor            | 1         | 1      | 0.57%   |
| TCSUNBOW            | 1         | 1      | 0.57%   |
| SK Hynix            | 1         | 1      | 0.57%   |
| SABRENT             | 1         | 1      | 0.57%   |
| Patriot             | 1         | 1      | 0.57%   |
| Micron Technology   | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| Intel               | 1         | 1      | 0.57%   |
| GOODRAM             | 1         | 1      | 0.57%   |
| FATTYDOVE           | 1         | 1      | 0.57%   |
| DREVO               | 1         | 1      | 0.57%   |
| Crucial             | 1         | 1      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| BHT                 | 1         | 2      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |
| Apacer              | 1         | 5      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                     | 6         | 3.37%   |
| Seagate ST9500325AS 500GB                  | 4         | 2.25%   |
| Seagate ST9250315AS 250GB                  | 4         | 2.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB        | 4         | 2.25%   |
| Seagate ST9320325AS 320GB                  | 3         | 1.69%   |
| Seagate ST500LT012-1DG142 500GB            | 3         | 1.69%   |
| WDC WD3200BPVT-24JJ5T0 320GB               | 2         | 1.12%   |
| WDC WD3200BPVT-22ZEST0 320GB               | 2         | 1.12%   |
| WDC WD1200BEVS-22UST0 120GB                | 2         | 1.12%   |
| Unknown SD/MMC/MS PRO 16GB                 | 2         | 1.12%   |
| Unknown MMC Card  64GB                     | 2         | 1.12%   |
| Unknown MMC Card  2GB                      | 2         | 1.12%   |
| Unknown MMC Card  16GB                     | 2         | 1.12%   |
| Toshiba MK5055GSX 500GB                    | 2         | 1.12%   |
| Seagate ST750LM022 HN-M750MBB 752GB        | 2         | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 1.12%   |
| Samsung HM160HI 160GB                      | 2         | 1.12%   |
| Kingston SA400S37240G 240GB SSD            | 2         | 1.12%   |
| Kingston SA400S37120G 120GB SSD            | 2         | 1.12%   |
| Hitachi HTS545025B9A300 250GB              | 2         | 1.12%   |
| HGST HTS725032A7E630 320GB                 | 2         | 1.12%   |
| Zheino CHN 25SATAA3 120 120GB SSD          | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD           | 1         | 0.56%   |
| WDC WD800BEVS-60LAT0 80GB                  | 1         | 0.56%   |
| WDC WD5000LPVX-60V0TT0 500GB               | 1         | 0.56%   |
| WDC WD5000LPVX-22V0TT0 500GB               | 1         | 0.56%   |
| WDC WD5000BPVT-00HXZT3 500GB               | 1         | 0.56%   |
| WDC WD3200BPVT-08JJ5T0 320GB               | 1         | 0.56%   |
| WDC WD3200BEVT-75ZCT2 320GB                | 1         | 0.56%   |
| WDC WD2500BPVT-24ZEST0 250GB               | 1         | 0.56%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 0.56%   |
| WDC WD2500BEVT-35A23T0 250GB               | 1         | 0.56%   |
| WDC WD2500BEVS-00UST0 250GB                | 1         | 0.56%   |
| WDC WD2500BEKT-66F3T2 250GB                | 1         | 0.56%   |
| WDC WD1600BEVT-60ZCT1 160GB                | 1         | 0.56%   |
| WDC WD1600BEVT-22ZCT0 160GB                | 1         | 0.56%   |
| WDC WD1600BEVT-00A23T0 160GB               | 1         | 0.56%   |
| WDC WD1600BEVS-22RST0 160GB                | 1         | 0.56%   |
| WDC WD1600BEVS-08VAT2 160GB                | 1         | 0.56%   |
| WDC WD1600BEVS-07RST0 160GB                | 1         | 0.56%   |
| WDC WD1600BEKT-75A25T0 160GB               | 1         | 0.56%   |
| WDC WD10SPCX-80HWST0 1TB                   | 1         | 0.56%   |
| WDC WD10JPVX-75JC3T0 1TB                   | 1         | 0.56%   |
| WDC WD10JPVX-60JC3T0 1TB                   | 1         | 0.56%   |
| Unknown SL16G  16GB                        | 1         | 0.56%   |
| Unknown SFSA120GM3AA4TO-I-LB-616-G30 120GB | 1         | 0.56%   |
| Unknown SE128  128GB                       | 1         | 0.56%   |
| Unknown MMC Card  970MB                    | 1         | 0.56%   |
| Unknown MMC Card  134GB                    | 1         | 0.56%   |
| Unknown MMC Card  128GB                    | 1         | 0.56%   |
| TrekStor TREKSTORSSD64GB                   | 1         | 0.56%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 0.56%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 0.56%   |
| Toshiba MQ01ABD032 320GB                   | 1         | 0.56%   |
| Toshiba MK8032GSX 80GB                     | 1         | 0.56%   |
| Toshiba MK7559GSXP 752GB                   | 1         | 0.56%   |
| Toshiba MK6008GAH 64GB                     | 1         | 0.56%   |
| Toshiba MK5055GSXN 500GB                   | 1         | 0.56%   |
| Toshiba MK3265GSX 320GB                    | 1         | 0.56%   |
| Toshiba MK2565GSX 250GB                    | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 39     | 32.74%  |
| WDC                 | 27        | 32     | 23.89%  |
| Toshiba             | 16        | 17     | 14.16%  |
| Hitachi             | 14        | 17     | 12.39%  |
| Samsung Electronics | 8         | 8      | 7.08%   |
| Fujitsu             | 5         | 6      | 4.42%   |
| HGST                | 4         | 5      | 3.54%   |
| Unknown             | 2         | 2      | 1.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 20     | 21.95%  |
| Kingston            | 7         | 9      | 17.07%  |
| SanDisk             | 4         | 5      | 9.76%   |
| PNY                 | 2         | 2      | 4.88%   |
| Integral            | 2         | 2      | 4.88%   |
| Zheino              | 1         | 1      | 2.44%   |
| WDC                 | 1         | 1      | 2.44%   |
| TrekStor            | 1         | 1      | 2.44%   |
| TCSUNBOW            | 1         | 1      | 2.44%   |
| Patriot             | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEONIT            | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |
| FATTYDOVE           | 1         | 1      | 2.44%   |
| DREVO               | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| China               | 1         | 1      | 2.44%   |
| BHT                 | 1         | 2      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |
| Apacer              | 1         | 5      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 111       | 126    | 64.53%  |
| SSD     | 40        | 60     | 23.26%  |
| MMC     | 16        | 19     | 9.3%    |
| Unknown | 3         | 3      | 1.74%   |
| NVMe    | 2         | 2      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 145       | 184    | 86.31%  |
| MMC  | 16        | 19     | 9.52%   |
| SAS  | 5         | 5      | 2.98%   |
| NVMe | 2         | 2      | 1.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 132       | 167    | 88%     |
| 0.51-1.0   | 16        | 17     | 10.67%  |
| 1.01-2.0   | 2         | 2      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 35.37%  |
| 251-500        | 35        | 21.34%  |
| 51-100         | 28        | 17.07%  |
| 21-50          | 20        | 12.2%   |
| 501-1000       | 10        | 6.1%    |
| 1-20           | 8         | 4.88%   |
| 1001-2000      | 2         | 1.22%   |
| More than 3000 | 1         | 0.61%   |
| 2001-3000      | 1         | 0.61%   |
| Unknown        | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 113       | 66.08%  |
| 21-50     | 33        | 19.3%   |
| 51-100    | 13        | 7.6%    |
| 101-250   | 7         | 4.09%   |
| 501-1000  | 3         | 1.75%   |
| 1001-2000 | 1         | 0.58%   |
| Unknown   | 1         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB       | 1         | 1      | 33.33%  |
| Seagate ST9250315AS 250GB       | 1         | 1      | 33.33%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Detected | 146       | 194    | 90.68%  |
| Works    | 12        | 13     | 7.45%   |
| Malfunc  | 3         | 3      | 1.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 121       | 79.61%  |
| AMD                              | 19        | 12.5%   |
| Silicon Integrated Systems [SiS] | 4         | 2.63%   |
| VIA Technologies                 | 3         | 1.97%   |
| Samsung Electronics              | 3         | 1.97%   |
| Nvidia                           | 2         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 18        | 9.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 16        | 8.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 12        | 6.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 12        | 6.49%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 11        | 5.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 11        | 5.95%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 9         | 4.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 8         | 4.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 6         | 3.24%   |
| Intel 82801FBM (ICH6M) SATA Controller                                       | 6         | 3.24%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 4         | 2.16%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 4         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 4         | 2.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 4         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 3         | 1.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 1.62%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 2         | 1.08%   |
| VIA VT8237A SATA 2-Port Controller                                           | 2         | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.08%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 2         | 1.08%   |
| AMD SB600 IDE                                                                | 2         | 1.08%   |
| AMD IXP SB4x0 IDE Controller                                                 | 2         | 1.08%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.54%   |
| Samsung Electronics SATA controller                                          | 1         | 0.54%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.54%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 0.54%   |
| Nvidia MCP67 AHCI Controller                                                 | 1         | 0.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 1         | 0.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 0.54%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                         | 1         | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 0.54%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 0.54%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 108       | 63.16%  |
| IDE  | 57        | 33.33%  |
| RAID | 4         | 2.34%   |
| NVMe | 2         | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 139       | 86.34%  |
| AMD          | 21        | 13.04%  |
| CentaurHauls | 1         | 0.62%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 8         | 4.97%   |
| Intel Pentium M processor 1.73GHz           | 6         | 3.73%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 3.73%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 2.48%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.86%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 1.86%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 1.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.86%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.24%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.24%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 2         | 1.24%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 1.24%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 1.24%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.24%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.24%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.24%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.24%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.24%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.24%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 1.24%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 1.24%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.24%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 1.24%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 1.24%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.24%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.24%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.24%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.24%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.24%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.62%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.62%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 0.62%   |
| Intel Pentium Dual CPU T2410 @ 2.00GHz      | 1         | 0.62%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.62%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.62%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.62%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.62%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.62%   |
| Intel Genuine CPU T1350 @ 1.86GHz           | 1         | 0.62%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.62%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.62%   |
| Intel Core i7-3820QM CPU @ 2.70GHz          | 1         | 0.62%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.62%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 0.62%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.62%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.62%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.62%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.62%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.62%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.62%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.62%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 24        | 14.91%  |
| Intel Celeron           | 21        | 13.04%  |
| Intel Core i7           | 13        | 8.07%   |
| Intel Core i5           | 13        | 8.07%   |
| Intel Core 2 Duo        | 13        | 8.07%   |
| Intel Genuine           | 11        | 6.83%   |
| Intel Core i3           | 10        | 6.21%   |
| Intel Pentium M         | 7         | 4.35%   |
| Intel Pentium           | 7         | 4.35%   |
| Intel Core 2            | 7         | 4.35%   |
| Intel Pentium Dual-Core | 6         | 3.73%   |
| Intel Pentium Dual      | 4         | 2.48%   |
| AMD E                   | 3         | 1.86%   |
| AMD A8                  | 3         | 1.86%   |
| AMD Turion 64 X2 Mobile | 2         | 1.24%   |
| AMD E2                  | 2         | 1.24%   |
| AMD Athlon              | 2         | 1.24%   |
| Other                   | 1         | 0.62%   |
| Intel Core Duo          | 1         | 0.62%   |
| Intel Celeron M         | 1         | 0.62%   |
| Intel Celeron Dual-Core | 1         | 0.62%   |
| CentaurHauls VIA C7     | 1         | 0.62%   |
| AMD Turion 64 Mobile    | 1         | 0.62%   |
| AMD Phenom II           | 1         | 0.62%   |
| AMD E1                  | 1         | 0.62%   |
| AMD C-60                | 1         | 0.62%   |
| AMD Athlon 64 X2        | 1         | 0.62%   |
| AMD A6                  | 1         | 0.62%   |
| AMD A4                  | 1         | 0.62%   |
| AMD A10                 | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 97        | 60.25%  |
| 1      | 42        | 26.09%  |
| 4      | 22        | 13.66%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 62.73%  |
| 2      | 60        | 37.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 124       | 76.54%  |
| 32-bit         | 26        | 16.05%  |
| Unknown        | 12        | 7.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 16        | 9.7%    |
| 0x206a7    | 14        | 8.48%   |
| Unknown    | 14        | 8.48%   |
| 0x306a9    | 13        | 7.88%   |
| 0x6fd      | 12        | 7.27%   |
| 0x106ca    | 12        | 7.27%   |
| 0x106c2    | 9         | 5.45%   |
| 0x6d8      | 7         | 4.24%   |
| 0x6e8      | 5         | 3.03%   |
| 0x30678    | 5         | 3.03%   |
| 0x10661    | 5         | 3.03%   |
| 0x6f6      | 4         | 2.42%   |
| 0x6ec      | 4         | 2.42%   |
| 0x406c4    | 4         | 2.42%   |
| 0x20655    | 4         | 2.42%   |
| 0x40651    | 3         | 1.82%   |
| 0x07030105 | 3         | 1.82%   |
| 0x06006705 | 3         | 1.82%   |
| 0x05000119 | 3         | 1.82%   |
| 0x806ec    | 2         | 1.21%   |
| 0x806e9    | 2         | 1.21%   |
| 0x6f2      | 2         | 1.21%   |
| 0x306d4    | 2         | 1.21%   |
| 0x10676    | 2         | 1.21%   |
| 0x806ea    | 1         | 0.61%   |
| 0x706a8    | 1         | 0.61%   |
| 0x706a1    | 1         | 0.61%   |
| 0x6fb      | 1         | 0.61%   |
| 0x506c9    | 1         | 0.61%   |
| 0x30661    | 1         | 0.61%   |
| 0x20652    | 1         | 0.61%   |
| 0x106e5    | 1         | 0.61%   |
| 0x08200103 | 1         | 0.61%   |
| 0x07030106 | 1         | 0.61%   |
| 0x0700010f | 1         | 0.61%   |
| 0x06006118 | 1         | 0.61%   |
| 0x06001119 | 1         | 0.61%   |
| 0x05000029 | 1         | 0.61%   |
| 0x010000c8 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Core          | 26        | 16.15%  |
| Bonnell       | 22        | 13.66%  |
| Penryn        | 18        | 11.18%  |
| P6            | 16        | 9.94%   |
| SandyBridge   | 14        | 8.7%    |
| IvyBridge     | 13        | 8.07%   |
| Silvermont    | 9         | 5.59%   |
| Westmere      | 6         | 3.73%   |
| KabyLake      | 5         | 3.11%   |
| K8 Hammer     | 5         | 3.11%   |
| Puma          | 4         | 2.48%   |
| Excavator     | 4         | 2.48%   |
| Bobcat        | 4         | 2.48%   |
| Haswell       | 3         | 1.86%   |
| Broadwell     | 3         | 1.86%   |
| Goldmont plus | 2         | 1.24%   |
| Zen           | 1         | 0.62%   |
| Piledriver    | 1         | 0.62%   |
| Nehalem       | 1         | 0.62%   |
| K10           | 1         | 0.62%   |
| Jaguar        | 1         | 0.62%   |
| Goldmont      | 1         | 0.62%   |
| Unknown       | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 119       | 71.69%  |
| AMD                              | 24        | 14.46%  |
| Nvidia                           | 16        | 9.64%   |
| Silicon Integrated Systems [SiS] | 4         | 2.41%   |
| VIA Technologies                 | 3         | 1.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 22        | 10.89%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 8.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 6.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 6.44%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 5.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 4.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 4.95%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 4.46%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.48%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.98%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.49%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.99%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.99%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.99%   |
| Intel HD Graphics 620                                                                    | 2         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.99%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.99%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.99%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.99%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.5%    |
| Nvidia GT218M [ION]                                                                      | 1         | 0.5%    |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.5%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.5%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.5%    |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.5%    |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.5%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.5%    |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.5%    |
| Intel UHD Graphics 620                                                                   | 1         | 0.5%    |
| Intel HD Graphics 500                                                                    | 1         | 0.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.5%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.5%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.5%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.5%    |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.5%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.5%    |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 0.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.5%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.5%    |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.5%    |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 1         | 0.5%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.5%    |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 0.5%    |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 0.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.5%    |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 0.5%    |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.5%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.5%    |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                                  | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 113       | 70.19%  |
| 1 x AMD        | 20        | 12.42%  |
| 1 x Nvidia     | 11        | 6.83%   |
| Intel + Nvidia | 5         | 3.11%   |
| 2 x AMD        | 4         | 2.48%   |
| 1 x SiS        | 4         | 2.48%   |
| 1 x VIA        | 3         | 1.86%   |
| Other          | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 148       | 91.36%  |
| Unknown     | 10        | 6.17%   |
| Proprietary | 4         | 2.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 71.78%  |
| 0.01-0.5   | 36        | 22.09%  |
| 0.51-1.0   | 6         | 3.68%   |
| 1.01-2.0   | 3         | 1.84%   |
| 3.01-4.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 22.01%  |
| Samsung Electronics     | 27        | 16.98%  |
| LG Display              | 18        | 11.32%  |
| LG Philips              | 13        | 8.18%   |
| Chi Mei Optoelectronics | 9         | 5.66%   |
| HannStar                | 8         | 5.03%   |
| Chimei Innolux          | 6         | 3.77%   |
| Lenovo                  | 4         | 2.52%   |
| CPT                     | 4         | 2.52%   |
| BOE                     | 4         | 2.52%   |
| Sony                    | 3         | 1.89%   |
| InfoVision              | 3         | 1.89%   |
| Dell                    | 3         | 1.89%   |
| Hitachi                 | 2         | 1.26%   |
| Hewlett-Packard         | 2         | 1.26%   |
| BenQ                    | 2         | 1.26%   |
| Apple                   | 2         | 1.26%   |
| Vizio                   | 1         | 0.63%   |
| ViewSonic               | 1         | 0.63%   |
| Seiko/Epson             | 1         | 0.63%   |
| Quanta Display          | 1         | 0.63%   |
| PANDA                   | 1         | 0.63%   |
| Optoma                  | 1         | 0.63%   |
| OEM                     | 1         | 0.63%   |
| LPL                     | 1         | 0.63%   |
| KDC                     | 1         | 0.63%   |
| HKC                     | 1         | 0.63%   |
| Element                 | 1         | 0.63%   |
| CVT                     | 1         | 0.63%   |
| Ancor Communications    | 1         | 0.63%   |
| Acer                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 6         | 3.7%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 2         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 1.23%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 2         | 1.23%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 1.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.23%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 1.23%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 1.23%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                        | 1         | 0.62%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 1         | 0.62%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                             | 1         | 0.62%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.62%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 1         | 0.62%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.62%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC5451 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.62%   |
| Quanta Display LCD Monitor QDS0033 1024x768 304x228mm 15.0-inch          | 1         | 0.62%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch                  | 1         | 0.62%   |
| Optoma WXGA OTM0550 1280x1024                                            | 1         | 0.62%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                          | 1         | 0.62%   |
| LPL LCD Monitor 1440x900                                                 | 1         | 0.62%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 1         | 0.62%   |
| LG Philips LCD Monitor LPLE600 1280x800 331x207mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPLCB00 1280x800 331x207mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPLBB00 1024x768 304x228mm 15.0-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPLA500 1280x800 304x190mm 14.1-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPL2388 1440x900 367x230mm 17.1-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch              | 1         | 0.62%   |
| LG Display LP140WH2-TLA1 LGD0201 1366x768 310x174mm 14.0-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD0380 1600x900 294x166mm 13.3-inch              | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 62        | 38.75%  |
| 1280x800 (WXGA)    | 29        | 18.13%  |
| 1920x1080 (FHD)    | 23        | 14.38%  |
| 1024x600           | 14        | 8.75%   |
| 1600x900 (HD+)     | 6         | 3.75%   |
| 1024x768 (XGA)     | 6         | 3.75%   |
| 3840x2160 (4K)     | 3         | 1.88%   |
| 1920x1200 (WUXGA)  | 3         | 1.88%   |
| 1440x900 (WXGA+)   | 3         | 1.88%   |
| 2560x1440 (QHD)    | 2         | 1.25%   |
| 1920x540           | 2         | 1.25%   |
| 1024x576           | 2         | 1.25%   |
| 1680x1050 (WSXGA+) | 1         | 0.63%   |
| 1360x768           | 1         | 0.63%   |
| 1280x960           | 1         | 0.63%   |
| 1280x768           | 1         | 0.63%   |
| 1280x1024 (SXGA)   | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 75        | 47.17%  |
| 14      | 15        | 9.43%   |
| 10      | 14        | 8.81%   |
| 13      | 13        | 8.18%   |
| 11      | 8         | 5.03%   |
| 17      | 7         | 4.4%    |
| 24      | 4         | 2.52%   |
| 84      | 3         | 1.89%   |
| 27      | 3         | 1.89%   |
| 21      | 3         | 1.89%   |
| 12      | 3         | 1.89%   |
| Unknown | 3         | 1.89%   |
| 18      | 2         | 1.26%   |
| 8       | 2         | 1.26%   |
| 39      | 1         | 0.63%   |
| 31      | 1         | 0.63%   |
| 23      | 1         | 0.63%   |
| 22      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 58.86%  |
| 201-300     | 32        | 20.25%  |
| 351-400     | 9         | 5.7%    |
| 501-600     | 8         | 5.06%   |
| 401-500     | 6         | 3.8%    |
| 1501-2000   | 3         | 1.9%    |
| Unknown     | 3         | 1.9%    |
| 101-200     | 2         | 1.27%   |
| 801-900     | 1         | 0.63%   |
| 601-700     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 106       | 71.14%  |
| 16/10   | 32        | 21.48%  |
| 4/3     | 7         | 4.7%    |
| 5/4     | 2         | 1.34%   |
| Unknown | 2         | 1.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 46.54%  |
| 81-90          | 22        | 13.84%  |
| 41-50          | 14        | 8.81%   |
| 51-60          | 8         | 5.03%   |
| 201-250        | 6         | 3.77%   |
| 71-80          | 5         | 3.14%   |
| 121-130        | 5         | 3.14%   |
| More than 1000 | 3         | 1.89%   |
| 61-70          | 3         | 1.89%   |
| 141-150        | 3         | 1.89%   |
| Unknown        | 3         | 1.89%   |
| 351-500        | 2         | 1.26%   |
| 1-40           | 2         | 1.26%   |
| 301-350        | 2         | 1.26%   |
| 151-200        | 2         | 1.26%   |
| 91-100         | 2         | 1.26%   |
| 251-300        | 1         | 0.63%   |
| 131-140        | 1         | 0.63%   |
| 501-1000       | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 75        | 48.39%  |
| 51-100  | 48        | 30.97%  |
| 121-160 | 26        | 16.77%  |
| 161-240 | 3         | 1.94%   |
| Unknown | 3         | 1.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 138       | 84.66%  |
| 2     | 18        | 11.04%  |
| 0     | 6         | 3.68%   |
| 3     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 78        | 27.18%  |
| Intel                             | 58        | 20.21%  |
| Qualcomm Atheros                  | 51        | 17.77%  |
| Broadcom                          | 43        | 14.98%  |
| Marvell Technology Group          | 15        | 5.23%   |
| Broadcom Limited                  | 11        | 3.83%   |
| Ralink                            | 4         | 1.39%   |
| Silicon Integrated Systems [SiS]  | 3         | 1.05%   |
| VIA Technologies                  | 2         | 0.7%    |
| Samsung Electronics               | 2         | 0.7%    |
| Ralink Technology                 | 2         | 0.7%    |
| JMicron Technology                | 2         | 0.7%    |
| TP-Link                           | 1         | 0.35%   |
| Spreadtrum Communications         | 1         | 0.35%   |
| Nvidia                            | 1         | 0.35%   |
| NetGear                           | 1         | 0.35%   |
| Micro Star International          | 1         | 0.35%   |
| MediaTek                          | 1         | 0.35%   |
| Huawei Technologies               | 1         | 0.35%   |
| Ericsson Business Mobile Networks | 1         | 0.35%   |
| DisplayLink                       | 1         | 0.35%   |
| Dell                              | 1         | 0.35%   |
| BUFFALO                           | 1         | 0.35%   |
| Belkin Components                 | 1         | 0.35%   |
| Attansic Technology               | 1         | 0.35%   |
| ASUSTek Computer                  | 1         | 0.35%   |
| ASIX Electronics                  | 1         | 0.35%   |
| AMD                               | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 8.71%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 27        | 8.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 4.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 4.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 2.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 8         | 2.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 2.4%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.5%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.2%    |
| Intel Wireless 7260                                                     | 4         | 1.2%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 1.2%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.9%    |
| Intel Wireless 7265                                                     | 3         | 0.9%    |
| Intel Wireless 3165                                                     | 3         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                          | 3         | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.6%    |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.6%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.6%    |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                    | 2         | 0.6%    |
| Intel WiFi Link 5100                                                    | 2         | 0.6%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.6%    |
| Intel 82573L Gigabit Ethernet Controller                                | 2         | 0.6%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 2         | 0.6%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 2         | 0.6%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.6%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                     | 2         | 0.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 56        | 33.33%  |
| Qualcomm Atheros         | 38        | 22.62%  |
| Broadcom                 | 31        | 18.45%  |
| Realtek Semiconductor    | 24        | 14.29%  |
| Broadcom Limited         | 7         | 4.17%   |
| Ralink                   | 4         | 2.38%   |
| Ralink Technology        | 2         | 1.19%   |
| TP-Link                  | 1         | 0.6%    |
| NetGear                  | 1         | 0.6%    |
| Micro Star International | 1         | 0.6%    |
| BUFFALO                  | 1         | 0.6%    |
| Belkin Components        | 1         | 0.6%    |
| ASUSTek Computer         | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 15        | 8.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 14        | 8.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 8         | 4.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 4.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 4.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 2.96%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 5         | 2.96%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 2.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 5         | 2.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 4         | 2.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 2.37%   |
| Intel Wireless 7260                                                           | 4         | 2.37%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 2.37%   |
| Intel Wireless 7265                                                           | 3         | 1.78%   |
| Intel Wireless 3165                                                           | 3         | 1.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 1.78%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 1.18%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.18%   |
| Realtek RTL8187B Wireless Adapter                                             | 2         | 1.18%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 2         | 1.18%   |
| Realtek 802.11ac NIC                                                          | 2         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.18%   |
| Intel WiFi Link 5100                                                          | 2         | 1.18%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.18%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.59%   |
| Realtek RTL8187 Wireless Adapter                                              | 1         | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.59%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.59%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)       | 1         | 0.59%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.59%   |
| NetGear A6150                                                                 | 1         | 0.59%   |
| Micro Star International RT2573                                               | 1         | 0.59%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 0.59%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.59%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.59%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 0.59%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.59%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 68        | 44.16%  |
| Qualcomm Atheros                 | 19        | 12.34%  |
| Intel                            | 16        | 10.39%  |
| Broadcom                         | 16        | 10.39%  |
| Marvell Technology Group         | 15        | 9.74%   |
| Broadcom Limited                 | 5         | 3.25%   |
| Silicon Integrated Systems [SiS] | 3         | 1.95%   |
| VIA Technologies                 | 2         | 1.3%    |
| Samsung Electronics              | 2         | 1.3%    |
| JMicron Technology               | 2         | 1.3%    |
| Spreadtrum Communications        | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| MediaTek                         | 1         | 0.65%   |
| DisplayLink                      | 1         | 0.65%   |
| Attansic Technology              | 1         | 0.65%   |
| ASIX Electronics                 | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 18.71%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 17.42%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 5.16%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 5.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 3.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.94%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.29%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.29%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 2         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.29%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.29%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 1.29%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.29%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.29%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 1.29%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.65%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.65%   |
| MediaTek WP7                                                      | 1         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.65%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.65%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.65%   |
| DisplayLink Targus USB3 DV4K DOCK w PD60W                         | 1         | 0.65%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.65%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.65%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.65%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.65%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.65%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.65%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 50.16%  |
| Ethernet | 149       | 47%     |
| Modem    | 9         | 2.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 142       | 56.57%  |
| Ethernet | 109       | 43.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 133       | 82.61%  |
| 1     | 25        | 15.53%  |
| 0     | 2         | 1.24%   |
| 3     | 1         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 151       | 92.64%  |
| Yes  | 12        | 7.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 24.68%  |
| Qualcomm Atheros Communications | 8         | 10.39%  |
| Broadcom                        | 8         | 10.39%  |
| Hewlett-Packard                 | 6         | 7.79%   |
| Realtek Semiconductor           | 5         | 6.49%   |
| Toshiba                         | 4         | 5.19%   |
| Lite-On Technology              | 4         | 5.19%   |
| Foxconn / Hon Hai               | 4         | 5.19%   |
| IMC Networks                    | 3         | 3.9%    |
| Foxconn International           | 3         | 3.9%    |
| Cambridge Silicon Radio         | 3         | 3.9%    |
| Ralink                          | 2         | 2.6%    |
| Dell                            | 2         | 2.6%    |
| Apple                           | 2         | 2.6%    |
| Alps Electric                   | 2         | 2.6%    |
| Fujitsu Siemens Computers       | 1         | 1.3%    |
| ASUSTek Computer                | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 14.29%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 7.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 5.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 3.9%    |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 3.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.9%    |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 3.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.6%    |
| Realtek Bluetooth Radio                             | 2         | 2.6%    |
| Ralink RT3290 Bluetooth                             | 2         | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.6%    |
| Lite-On Bluetooth Device                            | 2         | 2.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.6%    |
| Dell DW375 Bluetooth Module                         | 2         | 2.6%    |
| Toshiba RT Bluetooth Radio                          | 1         | 1.3%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.3%    |
| Toshiba Bluetooth Device                            | 1         | 1.3%    |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.3%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.3%    |
| Intel Bluetooth Device                              | 1         | 1.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.3%    |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.3%    |
| IMC Networks Bluetooth module                       | 1         | 1.3%    |
| IMC Networks Bluetooth Device                       | 1         | 1.3%    |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 1.3%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.3%    |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.3%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.3%    |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.3%    |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 1.3%    |
| Broadcom HP Portable SoftSailing                    | 1         | 1.3%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.3%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.3%    |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 1         | 1.3%    |
| Apple Bluetooth HCI                                 | 1         | 1.3%    |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.3%    |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 130       | 75.14%  |
| AMD                              | 21        | 12.14%  |
| Nvidia                           | 11        | 6.36%   |
| Silicon Integrated Systems [SiS] | 4         | 2.31%   |
| VIA Technologies                 | 3         | 1.73%   |
| Logitech                         | 2         | 1.16%   |
| Elite Silicon                    | 1         | 0.58%   |
| C-Media Electronics              | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 37        | 19.07%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 10.82%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 8.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 5.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.61%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 3.09%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 2.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.06%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.55%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.55%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.55%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.55%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.55%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.03%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.52%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.52%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Logitech Z305                                                                                     | 1         | 0.52%   |
| Logitech Headset H390                                                                             | 1         | 0.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.52%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.52%   |
| Elite Silicon USB Audio Device                                                                    | 1         | 0.52%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 0.52%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.52%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.52%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.52%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.52%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 12        | 28.57%  |
| Samsung Electronics | 10        | 23.81%  |
| SK Hynix            | 6         | 14.29%  |
| Kingston            | 3         | 7.14%   |
| Crucial             | 2         | 4.76%   |
| Corsair             | 2         | 4.76%   |
| Toshiba             | 1         | 2.38%   |
| Smart               | 1         | 2.38%   |
| Micron Technology   | 1         | 2.38%   |
| Infineon            | 1         | 2.38%   |
| Elpida              | 1         | 2.38%   |
| A-DATA Technology   | 1         | 2.38%   |
| 48spaces            | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 2         | 4.35%   |
| Unknown RAM Module SODIMM DDR                                                | 1         | 2.17%   |
| Unknown RAM Module 512MB SODIMM DDR                                          | 1         | 2.17%   |
| Unknown RAM Module 4GB SODIMM DDR3                                           | 1         | 2.17%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                          | 1         | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                        | 1         | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                               | 1         | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                               | 1         | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                               | 1         | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                        | 1         | 2.17%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                          | 1         | 2.17%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                        | 1         | 2.17%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                                 | 1         | 2.17%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s                           | 1         | 2.17%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s                         | 1         | 2.17%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                         | 1         | 2.17%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                                 | 1         | 2.17%   |
| SK Hynix RAM Module 512MB DIMM DDR2 533MT/s                                  | 1         | 2.17%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 2.17%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 2.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s                    | 1         | 2.17%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 2.17%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s                    | 1         | 2.17%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                       | 1         | 2.17%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 1         | 2.17%   |
| Samsung RAM M471B5674-M0-YK0 4096MB Chip DDR3 1600MT/s                       | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                     | 1         | 2.17%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 2.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 2.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s                  | 1         | 2.17%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s                     | 1         | 2.17%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                         | 1         | 2.17%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                        | 1         | 2.17%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s                          | 1         | 2.17%   |
| Kingston RAM ASU1333S9-4G-ECEWG 4GB SODIMM DDR3 1333MT/s                     | 1         | 2.17%   |
| Kingston RAM 9905428-196.A00LF 8192MB SODIMM DDR3 1333MT/s                   | 1         | 2.17%   |
| Infineon RAM Module 256MB DIMM DDR2 533MT/s                                  | 1         | 2.17%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s                     | 1         | 2.17%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.17%   |
| Crucial RAM CT102464BF1339.C16 8GB SODIMM DDR3 1333MT/s                      | 1         | 2.17%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.17%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s                       | 1         | 2.17%   |
| Corsair RAM CM3X4GSD1066 4GB SODIMM 1067MT/s                                 | 1         | 2.17%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s                         | 1         | 2.17%   |
| 48spaces RAM 012345678901234567890123456789012345 2048MB SODIMM DDR2 667MT/s | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 26        | 65%     |
| DDR2  | 5         | 12.5%   |
| SDRAM | 3         | 7.5%    |
| DDR   | 3         | 7.5%    |
| DDR4  | 2         | 5%      |
| DRAM  | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 92.5%   |
| Row Of Chips | 1         | 2.5%    |
| DIMM         | 1         | 2.5%    |
| Chip         | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 17        | 39.53%  |
| 2048    | 13        | 30.23%  |
| 8192    | 6         | 13.95%  |
| 1024    | 3         | 6.98%   |
| 512     | 2         | 4.65%   |
| 256     | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 34.88%  |
| Unknown | 8         | 18.6%   |
| 1333    | 6         | 13.95%  |
| 1334    | 3         | 6.98%   |
| 1066    | 2         | 4.65%   |
| 667     | 2         | 4.65%   |
| 3200    | 1         | 2.33%   |
| 2400    | 1         | 2.33%   |
| 2048    | 1         | 2.33%   |
| 1067    | 1         | 2.33%   |
| 800     | 1         | 2.33%   |
| 533     | 1         | 2.33%   |
| 100     | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 28.33%  |
| Suyin                                  | 11        | 9.17%   |
| IMC Networks                           | 10        | 8.33%   |
| Acer                                   | 10        | 8.33%   |
| Realtek Semiconductor                  | 8         | 6.67%   |
| Z-Star Microelectronics                | 6         | 5%      |
| Ricoh                                  | 6         | 5%      |
| Microdia                               | 6         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 6         | 5%      |
| Sunplus Innovation Technology          | 4         | 3.33%   |
| Syntek                                 | 3         | 2.5%    |
| Silicon Motion                         | 3         | 2.5%    |
| Importek                               | 3         | 2.5%    |
| ALi                                    | 3         | 2.5%    |
| Samsung Electronics                    | 1         | 0.83%   |
| OmniVision Technologies                | 1         | 0.83%   |
| Lite-On Technology                     | 1         | 0.83%   |
| Lenovo                                 | 1         | 0.83%   |
| DigiTech                               | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |
| Alcor Micro                            | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 4         | 3.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 4         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 4         | 3.33%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 2.5%    |
| Chicony USB 2.0 Camera                                      | 3         | 2.5%    |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 2.5%    |
| Acer Lenovo Integrated Webcam                               | 3         | 2.5%    |
| Ricoh Sony Vaio Integrated Webcam                           | 2         | 1.67%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.67%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 1.67%   |
| Importek HP Webcam-50                                       | 2         | 1.67%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.67%   |
| IMC Networks Integrated Webcam                              | 2         | 1.67%   |
| Chicony VGA Webcam                                          | 2         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.67%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.67%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 2         | 1.67%   |
| Acer Integrated Camera                                      | 2         | 1.67%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.83%   |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 0.83%   |
| Syntek USB Camera Device                                    | 1         | 0.83%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.83%   |
| Syntek Integrated Webcam                                    | 1         | 0.83%   |
| Suyin Webcam-101                                            | 1         | 0.83%   |
| Suyin HP Webcam                                             | 1         | 0.83%   |
| Suyin HP Truevision HD                                      | 1         | 0.83%   |
| Suyin HD Video WebCam                                       | 1         | 0.83%   |
| Suyin Acer OrbiCam                                          | 1         | 0.83%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.83%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.83%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.83%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 0.83%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.83%   |
| Sunplus Asus Webcam                                         | 1         | 0.83%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.83%   |
| Silicon Motion HP Webcam                                    | 1         | 0.83%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 0.83%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.83%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.83%   |
| Ricoh Integrated Webcam                                     | 1         | 0.83%   |
| Realtek USB Camera                                          | 1         | 0.83%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.83%   |
| Realtek Integrated_Webcam_HD                                | 1         | 0.83%   |
| Realtek Integrated Webcam                                   | 1         | 0.83%   |
| Realtek Integrated Camera 2M                                | 1         | 0.83%   |
| Realtek HP Truevision HD integrated webcam                  | 1         | 0.83%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.83%   |
| Realtek HD WebCam                                           | 1         | 0.83%   |
| OmniVision OV2640 Webcam                                    | 1         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_0.3M                      | 1         | 0.83%   |
| Microdia Integrated_Webcam_1.3M                             | 1         | 0.83%   |
| Microdia Integrated Webcam                                  | 1         | 0.83%   |
| Microdia 1.3 MPixel Integrated Webcam                       | 1         | 0.83%   |
| Lite-On TOSHIBA Web Camera                                  | 1         | 0.83%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 0.83%   |
| Importek Webcam-101                                         | 1         | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 0.83%   |
| IMC Networks USB2.0 UVC 2M WebCam                           | 1         | 0.83%   |
| IMC Networks TOSHIBA Web Camera - HD                        | 1         | 0.83%   |
| DigiTech USB 2.0 PC Camera                                  | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 4         | 50%     |
| Broadcom    | 3         | 37.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 105       | 64.42%  |
| 1     | 46        | 28.22%  |
| 2     | 12        | 7.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 24.64%  |
| Net/wireless             | 11        | 15.94%  |
| Graphics card            | 11        | 15.94%  |
| Chipcard                 | 8         | 11.59%  |
| Storage                  | 6         | 8.7%    |
| Modem                    | 5         | 7.25%   |
| Bluetooth                | 3         | 4.35%   |
| Flash memory             | 2         | 2.9%    |
| Communication controller | 2         | 2.9%    |
| Camera                   | 2         | 2.9%    |
| Storage/ide              | 1         | 1.45%   |
| Multimedia controller    | 1         | 1.45%   |
