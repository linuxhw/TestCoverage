Ubuntu Budgie - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 412

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Acer          | Swift SF114-34              | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Dell          | Inspiron 14 5401            | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| HP            | Pavilion dm4                | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| ASUSTek       | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Samsung       | 305V4A/305V5A               | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| Sony          | SVS13A25PBS                 | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1a5d62c5fb](https://linux-hardware.org/?probe=1a5d62c5fb) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | G50-45 80E3                 | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [249a326a8b](https://linux-hardware.org/?probe=249a326a8b) | Jan 17, 2022 |
| Lenovo        | G50-45 80E3                 | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo        | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| EVOO          | EV-C-116-7                  | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| HP            | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| Sony          | VPCEA47FX                   | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Sony          | VPCEJ1L1E                   | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Acer          | Swift SF114-32              | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell          | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| Lenovo        | G570 4334                   | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Inspiron 5570               | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| FUJITSU CL... | LIFEBOOK U9311A             | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| Google        | Peppy                       | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| TUXEDO        | Book XP1511                 | [7526222677](https://linux-hardware.org/?probe=7526222677) | Aug 15, 2021 |
| TUXEDO        | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| TUXEDO        | TUXEDO_Book_XA1510          | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO        | Unknown                     | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Fujitsu       | LIFEBOOK E756               | [1c72549a32](https://linux-hardware.org/?probe=1c72549a32) | Jun 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| HP            | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba       | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Toshiba       | Satellite P300              | [a53633e2b1](https://linux-hardware.org/?probe=a53633e2b1) | Jun 09, 2021 |
| Toshiba       | Satellite P300              | [3984b7401d](https://linux-hardware.org/?probe=3984b7401d) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| AWOW          | AK41                        | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek       | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| Dell          | Latitude D531               | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| HP            | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| Apple         | MacBookPro11,1              | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| Fujitsu       | LIFEBOOK E756               | [2e450a6687](https://linux-hardware.org/?probe=2e450a6687) | Mar 06, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Timi          | TM1701                      | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| Fujitsu       | LIFEBOOK A555               | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| Dell          | XPS 13 7390                 | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | N53SM                       | [e4689416a8](https://linux-hardware.org/?probe=e4689416a8) | Feb 02, 2021 |
| Positivo      | C14CR21TV                   | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| HUAWEI        | KLVC-WXX9                   | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| ASUSTek       | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI           | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Toshiba       | Satellite P750              | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| TUXEDO        | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Unknown       | Unknown                     | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [8937271376](https://linux-hardware.org/?probe=8937271376) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| Acer          | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| ASUSTek       | FX503VD                     | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| HP            | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| HP            | Laptop 17-ak0xx             | [e51b8a2e3d](https://linux-hardware.org/?probe=e51b8a2e3d) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Fujitsu       | LIFEBOOK E756               | [3d1548beea](https://linux-hardware.org/?probe=3d1548beea) | Nov 06, 2020 |
| Sony          | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP            | ZBook 14                    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell          | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI           | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell          | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP            | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell          | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| Sony          | VPCEK20AL                   | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [89e1df883c](https://linux-hardware.org/?probe=89e1df883c) | Aug 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [545f6ed65f](https://linux-hardware.org/?probe=545f6ed65f) | Jul 31, 2020 |
| Apple         | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI        | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell          | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI           | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek       | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| TUXEDO        | Unknown                     | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP            | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer          | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| TUXEDO        | Unknown                     | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [e4d76f72dc](https://linux-hardware.org/?probe=e4d76f72dc) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| TUXEDO        | Unknown                     | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| TUXEDO        | Unknown                     | [36f3db3281](https://linux-hardware.org/?probe=36f3db3281) | May 10, 2020 |
| TUXEDO        | Unknown                     | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| ASUSTek       | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| HP            | Compaq 6720s                | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| Dell          | Latitude 5400               | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | Latitude E6420              | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| ASUSTek       | N501VW                      | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | [7f2259cf54](https://linux-hardware.org/?probe=7f2259cf54) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Unknown       | Unknown                     | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| HP            | 2000                        | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | [f35ce62181](https://linux-hardware.org/?probe=f35ce62181) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Dell          | Inspiron 5559               | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 158       | 56.23%  |
| Ubuntu Budgie 20.10 | 34        | 12.1%   |
| Ubuntu Budgie 21.10 | 28        | 9.96%   |
| Ubuntu Budgie 18.04 | 22        | 7.83%   |
| Ubuntu Budgie 21.04 | 19        | 6.76%   |
| Ubuntu Budgie 19.10 | 13        | 4.63%   |
| Ubuntu Budgie 22.04 | 4         | 1.42%   |
| Ubuntu Budgie 16.04 | 2         | 0.71%   |
| Ubuntu Budgie       | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 277       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 17        | 5.56%   |
| 5.3.0-40-generic           | 10        | 3.27%   |
| 5.13.0-22-generic          | 10        | 3.27%   |
| 5.4.0-40-generic           | 9         | 2.94%   |
| 5.13.0-28-generic          | 8         | 2.61%   |
| 5.8.0-41-generic           | 7         | 2.29%   |
| 5.4.0-37-generic           | 6         | 1.96%   |
| 5.4.0-29-generic           | 6         | 1.96%   |
| 5.13.0-39-generic          | 6         | 1.96%   |
| 5.8.0-53-generic           | 5         | 1.63%   |
| 5.8.0-48-generic           | 5         | 1.63%   |
| 5.4.0-52-generic           | 5         | 1.63%   |
| 5.4.0-48-generic           | 5         | 1.63%   |
| 5.4.0-33-generic           | 5         | 1.63%   |
| 5.8.0-44-generic           | 4         | 1.31%   |
| 5.8.0-33-generic           | 4         | 1.31%   |
| 5.8.0-29-generic           | 4         | 1.31%   |
| 5.4.0-58-generic           | 4         | 1.31%   |
| 5.4.0-31-generic           | 4         | 1.31%   |
| 5.13.0-40-generic          | 4         | 1.31%   |
| 5.13.0-35-generic          | 4         | 1.31%   |
| 5.13.0-30-generic          | 4         | 1.31%   |
| 5.13.0-19-generic          | 4         | 1.31%   |
| 5.11.0-34-generic          | 4         | 1.31%   |
| 5.11.0-16-generic          | 4         | 1.31%   |
| 5.8.0-45-generic           | 3         | 0.98%   |
| 5.4.0-91-generic           | 3         | 0.98%   |
| 5.4.0-73-generic           | 3         | 0.98%   |
| 5.4.0-28-generic           | 3         | 0.98%   |
| 5.13.0-27-generic          | 3         | 0.98%   |
| 5.11.0-41-generic          | 3         | 0.98%   |
| 5.11.0-31-generic          | 3         | 0.98%   |
| 5.11.0-27-generic          | 3         | 0.98%   |
| 5.11.0-25-generic          | 3         | 0.98%   |
| 5.8.0-63-generic           | 2         | 0.65%   |
| 5.8.0-59-generic           | 2         | 0.65%   |
| 5.8.0-49-generic           | 2         | 0.65%   |
| 5.8.0-43-generic           | 2         | 0.65%   |
| 5.8.0-38-generic           | 2         | 0.65%   |
| 5.8.0-34-generic           | 2         | 0.65%   |
| 5.8.0-26-generic           | 2         | 0.65%   |
| 5.4.0-89-generic           | 2         | 0.65%   |
| 5.4.0-80-generic           | 2         | 0.65%   |
| 5.4.0-77-generic           | 2         | 0.65%   |
| 5.4.0-72-generic           | 2         | 0.65%   |
| 5.4.0-66-generic           | 2         | 0.65%   |
| 5.4.0-65-generic           | 2         | 0.65%   |
| 5.4.0-60-generic           | 2         | 0.65%   |
| 5.4.0-59-generic           | 2         | 0.65%   |
| 5.4.0-56-generic           | 2         | 0.65%   |
| 5.4.0-47-generic           | 2         | 0.65%   |
| 5.4.0-26-generic           | 2         | 0.65%   |
| 5.3.0-42-generic           | 2         | 0.65%   |
| 5.3.0-24-generic           | 2         | 0.65%   |
| 5.11.0-22-generic          | 2         | 0.65%   |
| 5.11.0-17-generic          | 2         | 0.65%   |
| 5.0.0-37-generic           | 2         | 0.65%   |
| 4.18.0-17-generic          | 2         | 0.65%   |
| 4.15.0-99-generic          | 2         | 0.65%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 100       | 35.21%  |
| 5.8.0   | 54        | 19.01%  |
| 5.13.0  | 46        | 16.2%   |
| 5.11.0  | 31        | 10.92%  |
| 5.3.0   | 21        | 7.39%   |
| 4.15.0  | 9         | 3.17%   |
| 5.15.0  | 5         | 1.76%   |
| 5.6.0   | 3         | 1.06%   |
| 5.12.0  | 2         | 0.7%    |
| 5.0.0   | 2         | 0.7%    |
| 4.18.0  | 2         | 0.7%    |
| 5.9.0   | 1         | 0.35%   |
| 5.8.11  | 1         | 0.35%   |
| 5.6.7   | 1         | 0.35%   |
| 5.5.0   | 1         | 0.35%   |
| 5.16.14 | 1         | 0.35%   |
| 5.15.11 | 1         | 0.35%   |
| 5.10.11 | 1         | 0.35%   |
| 5.10.0  | 1         | 0.35%   |
| 4.4.0   | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 100       | 35.21%  |
| 5.8     | 55        | 19.37%  |
| 5.13    | 46        | 16.2%   |
| 5.11    | 31        | 10.92%  |
| 5.3     | 21        | 7.39%   |
| 4.15    | 9         | 3.17%   |
| 5.15    | 6         | 2.11%   |
| 5.6     | 4         | 1.41%   |
| 5.12    | 2         | 0.7%    |
| 5.10    | 2         | 0.7%    |
| 5.0     | 2         | 0.7%    |
| 4.18    | 2         | 0.7%    |
| 5.9     | 1         | 0.35%   |
| 5.5     | 1         | 0.35%   |
| 5.16    | 1         | 0.35%   |
| 4.4     | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 274       | 98.92%  |
| i686   | 3         | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 273       | 98.56%  |
| GNOME  | 3         | 1.08%   |
| XFCE   | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 269       | 97.11%  |
| Wayland | 8         | 2.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 122       | 43.57%  |
| LightDM | 72        | 25.71%  |
| TDM     | 57        | 20.36%  |
| GDM     | 23        | 8.21%   |
| GDM3    | 5         | 1.79%   |
| SDDM    | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 92        | 33.09%  |
| de_DE   | 40        | 14.39%  |
| pt_BR   | 20        | 7.19%   |
| en_GB   | 17        | 6.12%   |
| fr_FR   | 16        | 5.76%   |
| en_CA   | 10        | 3.6%    |
| ru_RU   | 9         | 3.24%   |
| it_IT   | 8         | 2.88%   |
| en_IN   | 8         | 2.88%   |
| es_AR   | 7         | 2.52%   |
| es_MX   | 6         | 2.16%   |
| es_ES   | 4         | 1.44%   |
| es_CL   | 3         | 1.08%   |
| en_AU   | 3         | 1.08%   |
| de_AT   | 3         | 1.08%   |
| C       | 3         | 1.08%   |
| Unknown | 3         | 1.08%   |
| pt_PT   | 2         | 0.72%   |
| pl_PL   | 2         | 0.72%   |
| hu_HU   | 2         | 0.72%   |
| fi_FI   | 2         | 0.72%   |
| en_IE   | 2         | 0.72%   |
| de_CH   | 2         | 0.72%   |
| zh_CN   | 1         | 0.36%   |
| uk_UA   | 1         | 0.36%   |
| tr_TR   | 1         | 0.36%   |
| nl_NL   | 1         | 0.36%   |
| nl_BE   | 1         | 0.36%   |
| nb_NO   | 1         | 0.36%   |
| lv_LV   | 1         | 0.36%   |
| id_ID   | 1         | 0.36%   |
| fr_CH   | 1         | 0.36%   |
| es_US   | 1         | 0.36%   |
| es_SV   | 1         | 0.36%   |
| es_GT   | 1         | 0.36%   |
| en_ZA   | 1         | 0.36%   |
| en_SG   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 181       | 64.18%  |
| BIOS | 101       | 35.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 261       | 93.88%  |
| Zfs     | 8         | 2.88%   |
| Overlay | 3         | 1.08%   |
| Btrfs   | 3         | 1.08%   |
| Xfs     | 2         | 0.72%   |
| Jfs     | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 148       | 53.24%  |
| GPT     | 109       | 39.21%  |
| MBR     | 21        | 7.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 253       | 90.36%  |
| Yes       | 27        | 9.64%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 193       | 69.18%  |
| Yes       | 86        | 30.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 53        | 19.13%  |
| Hewlett-Packard                  | 44        | 15.88%  |
| Dell                             | 37        | 13.36%  |
| TUXEDO                           | 33        | 11.91%  |
| ASUSTek Computer                 | 29        | 10.47%  |
| Acer                             | 19        | 6.86%   |
| Apple                            | 10        | 3.61%   |
| MSI                              | 9         | 3.25%   |
| Sony                             | 5         | 1.81%   |
| Samsung Electronics              | 5         | 1.81%   |
| HUAWEI                           | 5         | 1.81%   |
| Toshiba                          | 3         | 1.08%   |
| Packard Bell                     | 3         | 1.08%   |
| Unknown                          | 3         | 1.08%   |
| Standard                         | 2         | 0.72%   |
| Google                           | 2         | 0.72%   |
| Fujitsu                          | 2         | 0.72%   |
| Viglen                           | 1         | 0.36%   |
| Timi                             | 1         | 0.36%   |
| Razer                            | 1         | 0.36%   |
| Quanta                           | 1         | 0.36%   |
| Positivo                         | 1         | 0.36%   |
| PC Specialist                    | 1         | 0.36%   |
| GPU Company                      | 1         | 0.36%   |
| Gigabyte Technology              | 1         | 0.36%   |
| FUJITSU CLIENT COMPUTING LIMITED | 1         | 0.36%   |
| EVOO                             | 1         | 0.36%   |
| BANGHO                           | 1         | 0.36%   |
| AWOW                             | 1         | 0.36%   |
| Alienware                        | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 13        | 4.69%   |
| TUXEDO Polaris 15 AMD Gen1                            | 2         | 0.72%   |
| TUXEDO InfinityBook S 15 Gen6                         | 2         | 0.72%   |
| TUXEDO InfinityBook S 14 Gen6                         | 2         | 0.72%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 2         | 0.72%   |
| TUXEDO Aura 15 Gen1                                   | 2         | 0.72%   |
| Standard MT40II                                       | 2         | 0.72%   |
| Lenovo IdeaPad 330S-15ARR 81FB                        | 2         | 0.72%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 2         | 0.72%   |
| HP ZBook Studio G3                                    | 2         | 0.72%   |
| HP Pavilion g6                                        | 2         | 0.72%   |
| HP Notebook                                           | 2         | 0.72%   |
| HP ENVY 15                                            | 2         | 0.72%   |
| HP 2000                                               | 2         | 0.72%   |
| Dell XPS 13 9380                                      | 2         | 0.72%   |
| Dell Latitude E6540                                   | 2         | 0.72%   |
| Dell Latitude 5400                                    | 2         | 0.72%   |
| Dell Inspiron 5570                                    | 2         | 0.72%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT                | 2         | 0.72%   |
| Apple MacBookPro8,1                                   | 2         | 0.72%   |
| Acer TravelMate P446-M                                | 2         | 0.72%   |
| Viglen VUB1                                           | 1         | 0.36%   |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.36%   |
| TUXEDO Stellaris Intel Gen3 (TGL)                     | 1         | 0.36%   |
| TUXEDO Stellaris AMD Gen3 (CZN)                       | 1         | 0.36%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.36%   |
| TUXEDO Polaris AMD Gen3 (CZN)                         | 1         | 0.36%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.36%   |
| TUXEDO P95_HR                                         | 1         | 0.36%   |
| TUXEDO P95_HP                                         | 1         | 0.36%   |
| TUXEDO P7xxTM1                                        | 1         | 0.36%   |
| TUXEDO InfinityBook S 14 v5                           | 1         | 0.36%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.36%   |
| TUXEDO Book XP1511                                    | 1         | 0.36%   |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.36%   |
| Toshiba Satellite S55-C                               | 1         | 0.36%   |
| Toshiba Satellite P750                                | 1         | 0.36%   |
| Toshiba Satellite P300                                | 1         | 0.36%   |
| Timi TM1701                                           | 1         | 0.36%   |
| Sony VPCEK20AL                                        | 1         | 0.36%   |
| Sony VPCEJ1L1E                                        | 1         | 0.36%   |
| Sony VPCEA47FX                                        | 1         | 0.36%   |
| Sony VPCCW25FL                                        | 1         | 0.36%   |
| Sony SVS13A25PBS                                      | 1         | 0.36%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.36%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.36%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.36%   |
| Samsung 305V4A/305V5A                                 | 1         | 0.36%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.36%   |
| Razer Blade Stealth                                   | 1         | 0.36%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.36%   |
| Positivo C14CR21TV                                    | 1         | 0.36%   |
| PC Specialist OctaneVI 15                             | 1         | 0.36%   |
| Packard Bell ENLE11BZ                                 | 1         | 0.36%   |
| Packard Bell EasyNote TM98                            | 1         | 0.36%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.36%   |
| MSI Vector GP66 12UGS                                 | 1         | 0.36%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.36%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.36%   |
| MSI Modern 14 A10RB                                   | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 27        | 9.75%   |
| Dell Latitude          | 15        | 5.42%   |
| Unknown                | 13        | 4.69%   |
| Acer Aspire            | 12        | 4.33%   |
| Lenovo IdeaPad         | 11        | 3.97%   |
| Dell Inspiron          | 11        | 3.97%   |
| HP Pavilion            | 10        | 3.61%   |
| TUXEDO InfinityBook    | 8         | 2.89%   |
| HP EliteBook           | 8         | 2.89%   |
| Dell XPS               | 7         | 2.53%   |
| HP ENVY                | 5         | 1.81%   |
| ASUS VivoBook          | 5         | 1.81%   |
| TUXEDO Polaris         | 4         | 1.44%   |
| HP ZBook               | 4         | 1.44%   |
| HP Laptop              | 4         | 1.44%   |
| Acer Swift             | 4         | 1.44%   |
| Toshiba Satellite      | 3         | 1.08%   |
| Lenovo ThinkBook       | 3         | 1.08%   |
| HP ProBook             | 3         | 1.08%   |
| HP Compaq              | 3         | 1.08%   |
| Apple MacBookPro8      | 3         | 1.08%   |
| TUXEDO Stellaris       | 2         | 0.72%   |
| TUXEDO P95             | 2         | 0.72%   |
| TUXEDO Book            | 2         | 0.72%   |
| TUXEDO Aura            | 2         | 0.72%   |
| Standard MT40II        | 2         | 0.72%   |
| Packard Bell EasyNote  | 2         | 0.72%   |
| MSI Prestige           | 2         | 0.72%   |
| Lenovo Yoga            | 2         | 0.72%   |
| HP Notebook            | 2         | 0.72%   |
| HP 2000                | 2         | 0.72%   |
| Fujitsu LIFEBOOK       | 2         | 0.72%   |
| Dell Vostro            | 2         | 0.72%   |
| Apple MacBookPro11     | 2         | 0.72%   |
| Acer TravelMate        | 2         | 0.72%   |
| Viglen VUB1            | 1         | 0.36%   |
| TUXEDO TUXEDO          | 1         | 0.36%   |
| TUXEDO Pulse           | 1         | 0.36%   |
| TUXEDO P7xxTM1         | 1         | 0.36%   |
| Timi TM1701            | 1         | 0.36%   |
| Sony VPCEK20AL         | 1         | 0.36%   |
| Sony VPCEJ1L1E         | 1         | 0.36%   |
| Sony VPCEA47FX         | 1         | 0.36%   |
| Sony VPCCW25FL         | 1         | 0.36%   |
| Sony SVS13A25PBS       | 1         | 0.36%   |
| Samsung 905S3G         | 1         | 0.36%   |
| Samsung 530U3C         | 1         | 0.36%   |
| Samsung 340XAA         | 1         | 0.36%   |
| Samsung 305V4A         | 1         | 0.36%   |
| Samsung 300E5EV        | 1         | 0.36%   |
| Razer Blade            | 1         | 0.36%   |
| Quanta R460-L.BG22P1   | 1         | 0.36%   |
| Positivo C14CR21TV     | 1         | 0.36%   |
| PC Specialist OctaneVI | 1         | 0.36%   |
| Packard Bell ENLE11BZ  | 1         | 0.36%   |
| MSI Vector             | 1         | 0.36%   |
| MSI Modern             | 1         | 0.36%   |
| MSI GP73               | 1         | 0.36%   |
| MSI GP72               | 1         | 0.36%   |
| MSI GL62M              | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 45        | 16.25%  |
| 2018 | 35        | 12.64%  |
| 2020 | 28        | 10.11%  |
| 2011 | 23        | 8.3%    |
| 2017 | 21        | 7.58%   |
| 2012 | 21        | 7.58%   |
| 2013 | 17        | 6.14%   |
| 2014 | 16        | 5.78%   |
| 2016 | 15        | 5.42%   |
| 2015 | 15        | 5.42%   |
| 2021 | 13        | 4.69%   |
| 2010 | 9         | 3.25%   |
| 2008 | 7         | 2.53%   |
| 2007 | 6         | 2.17%   |
| 2009 | 5         | 1.81%   |
| 2022 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 277       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 245       | 88.45%  |
| Enabled  | 32        | 11.55%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 275       | 99.28%  |
| Yes  | 2         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 82        | 29.39%  |
| 16.01-24.0  | 57        | 20.43%  |
| 3.01-4.0    | 46        | 16.49%  |
| 8.01-16.0   | 46        | 16.49%  |
| 32.01-64.0  | 29        | 10.39%  |
| 64.01-256.0 | 8         | 2.87%   |
| 1.01-2.0    | 6         | 2.15%   |
| 24.01-32.0  | 3         | 1.08%   |
| 2.01-3.0    | 2         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 92        | 31.29%  |
| 1.01-2.0   | 80        | 27.21%  |
| 4.01-8.0   | 54        | 18.37%  |
| 3.01-4.0   | 51        | 17.35%  |
| 8.01-16.0  | 13        | 4.42%   |
| 0.51-1.0   | 3         | 1.02%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 203       | 72.76%  |
| 2      | 70        | 25.09%  |
| 3      | 6         | 2.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 187       | 67.27%  |
| Yes       | 91        | 32.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 224       | 80.58%  |
| No        | 54        | 19.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 99.28%  |
| No        | 2         | 0.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 83.09%  |
| No        | 47        | 16.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 46        | 16.55%  |
| USA                | 34        | 12.23%  |
| Brazil             | 22        | 7.91%   |
| France             | 16        | 5.76%   |
| Russia             | 11        | 3.96%   |
| Italy              | 11        | 3.96%   |
| UK                 | 10        | 3.6%    |
| India              | 10        | 3.6%    |
| Argentina          | 9         | 3.24%   |
| Canada             | 8         | 2.88%   |
| Netherlands        | 7         | 2.52%   |
| Mexico             | 7         | 2.52%   |
| Poland             | 6         | 2.16%   |
| Spain              | 5         | 1.8%    |
| Ukraine            | 4         | 1.44%   |
| Switzerland        | 4         | 1.44%   |
| Finland            | 4         | 1.44%   |
| Austria            | 4         | 1.44%   |
| Turkey             | 3         | 1.08%   |
| South Africa       | 3         | 1.08%   |
| Portugal           | 3         | 1.08%   |
| Norway             | 3         | 1.08%   |
| Iran               | 3         | 1.08%   |
| Hungary            | 3         | 1.08%   |
| Greece             | 3         | 1.08%   |
| Dominican Republic | 3         | 1.08%   |
| Chile              | 3         | 1.08%   |
| Australia          | 3         | 1.08%   |
| Sweden             | 2         | 0.72%   |
| Malaysia           | 2         | 0.72%   |
| Japan              | 2         | 0.72%   |
| Ireland            | 2         | 0.72%   |
| Indonesia          | 2         | 0.72%   |
| Belgium            | 2         | 0.72%   |
| Slovenia           | 1         | 0.36%   |
| Singapore          | 1         | 0.36%   |
| Serbia             | 1         | 0.36%   |
| Philippines        | 1         | 0.36%   |
| Myanmar            | 1         | 0.36%   |
| Libya              | 1         | 0.36%   |
| Latvia             | 1         | 0.36%   |
| Kenya              | 1         | 0.36%   |
| Jordan             | 1         | 0.36%   |
| Hong Kong          | 1         | 0.36%   |
| Honduras           | 1         | 0.36%   |
| Guatemala          | 1         | 0.36%   |
| Ghana              | 1         | 0.36%   |
| El Salvador        | 1         | 0.36%   |
| Egypt              | 1         | 0.36%   |
| Ecuador            | 1         | 0.36%   |
| Croatia            | 1         | 0.36%   |
| Colombia           | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Sao Paulo               | 5         | 1.74%   |
| Munich                  | 4         | 1.39%   |
| Moscow                  | 4         | 1.39%   |
| Tehran                  | 3         | 1.05%   |
| Stuttgart               | 3         | 1.05%   |
| Santo Domingo Este      | 3         | 1.05%   |
| Ravensburg              | 3         | 1.05%   |
| Paris                   | 3         | 1.05%   |
| Montreal                | 3         | 1.05%   |
| Budapest                | 3         | 1.05%   |
| Athens                  | 3         | 1.05%   |
| St Petersburg           | 2         | 0.7%    |
| San Francisco           | 2         | 0.7%    |
| Salt Lake City          | 2         | 0.7%    |
| Pune                    | 2         | 0.7%    |
| NiterГіi              | 2         | 0.7%    |
| Los Angeles             | 2         | 0.7%    |
| Llavallol               | 2         | 0.7%    |
| Lisbon                  | 2         | 0.7%    |
| Kyiv                    | 2         | 0.7%    |
| Hamburg                 | 2         | 0.7%    |
| Dublin                  | 2         | 0.7%    |
| BrasГ­lia             | 2         | 0.7%    |
| Berlin                  | 2         | 0.7%    |
| Belo Horizonte          | 2         | 0.7%    |
| Bamberg                 | 2         | 0.7%    |
| Austin                  | 2         | 0.7%    |
| Zheleznodorozhnyy       | 1         | 0.35%   |
| Zagreb                  | 1         | 0.35%   |
| Zabrze                  | 1         | 0.35%   |
| Yuma                    | 1         | 0.35%   |
| Yangon                  | 1         | 0.35%   |
| Wolfsburg               | 1         | 0.35%   |
| Woking                  | 1         | 0.35%   |
| Wilchingen, Osterfingen | 1         | 0.35%   |
| West End                | 1         | 0.35%   |
| Waterloo                | 1         | 0.35%   |
| Warsaw                  | 1         | 0.35%   |
| Villingen-Schwenningen  | 1         | 0.35%   |
| Vienna                  | 1         | 0.35%   |
| Vicente Lopez           | 1         | 0.35%   |
| Vendelso                | 1         | 0.35%   |
| Vantaa                  | 1         | 0.35%   |
| Vancouver               | 1         | 0.35%   |
| Valros                  | 1         | 0.35%   |
| Uniontown               | 1         | 0.35%   |
| Tuttlingen              | 1         | 0.35%   |
| Tuscola                 | 1         | 0.35%   |
| Turku                   | 1         | 0.35%   |
| Turin                   | 1         | 0.35%   |
| Tripoli                 | 1         | 0.35%   |
| Trets                   | 1         | 0.35%   |
| Totana                  | 1         | 0.35%   |
| Tokyo                   | 1         | 0.35%   |
| Tiel                    | 1         | 0.35%   |
| The Hague               | 1         | 0.35%   |
| Teresina                | 1         | 0.35%   |
| Temperley               | 1         | 0.35%   |
| Tangerang               | 1         | 0.35%   |
| SГЈo LuГ­s          | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 78        | 103     | 22.54%  |
| WDC                       | 41        | 43      | 11.85%  |
| Seagate                   | 38        | 41      | 10.98%  |
| Toshiba                   | 29        | 32      | 8.38%   |
| SanDisk                   | 23        | 26      | 6.65%   |
| Unknown                   | 22        | 25      | 6.36%   |
| Crucial                   | 12        | 13      | 3.47%   |
| SK Hynix                  | 11        | 13      | 3.18%   |
| Kingston                  | 11        | 11      | 3.18%   |
| Intel                     | 11        | 14      | 3.18%   |
| HGST                      | 8         | 11      | 2.31%   |
| A-DATA Technology         | 7         | 8       | 2.02%   |
| Micron Technology         | 6         | 8       | 1.73%   |
| Hitachi                   | 6         | 6       | 1.73%   |
| China                     | 5         | 5       | 1.45%   |
| Apple                     | 5         | 5       | 1.45%   |
| SPCC                      | 4         | 4       | 1.16%   |
| PNY                       | 4         | 7       | 1.16%   |
| LITEON                    | 2         | 2       | 0.58%   |
| Lenovo                    | 2         | 2       | 0.58%   |
| Intenso                   | 2         | 3       | 0.58%   |
| Vaseky                    | 1         | 1       | 0.29%   |
| USB30                     | 1         | 1       | 0.29%   |
| Union Memory              | 1         | 1       | 0.29%   |
| Realtek Semiconductor     | 1         | 1       | 0.29%   |
| OWC                       | 1         | 1       | 0.29%   |
| Micron/Crucial Technology | 1         | 1       | 0.29%   |
| LITEONIT                  | 1         | 1       | 0.29%   |
| LaCie                     | 1         | 1       | 0.29%   |
| KIOXIA                    | 1         | 1       | 0.29%   |
| KingSpec                  | 1         | 1       | 0.29%   |
| KimMiDi                   | 1         | 1       | 0.29%   |
| Hewlett-Packard           | 1         | Unknown | 0.29%   |
| Gigabyte Technology       | 1         | 1       | 0.29%   |
| GALAX TA                  | 1         | 1       | 0.29%   |
| Fujitsu                   | 1         | 1       | 0.29%   |
| DOGFISH                   | 1         | 1       | 0.29%   |
| Corsair                   | 1         | 1       | 0.29%   |
| BIWIN                     | 1         | 1       | 0.29%   |
| Unknown                   | 1         | 1       | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 5         | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.4%    |
| Samsung NVMe SSD Drive 1TB           | 5         | 1.4%    |
| Unknown MMC Card  32GB               | 4         | 1.12%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.12%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.12%   |
| SK Hynix NVMe SSD Drive 256GB        | 4         | 1.12%   |
| Seagate ST9500325AS 500GB            | 4         | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.12%   |
| Sandisk NVMe SSD Drive 512GB         | 4         | 1.12%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.12%   |
| Samsung SSD 860 EVO M.2 250GB        | 4         | 1.12%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 1.12%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 1.12%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.84%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.84%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.84%   |
| Samsung SSD 860 EVO M.2 500GB        | 3         | 0.84%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.84%   |
| Samsung SSD 750 EVO 250GB            | 3         | 0.84%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.84%   |
| Samsung NVMe SSD Drive 250GB         | 3         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.56%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 2         | 0.56%   |
| Unknown SD64G  64GB                  | 2         | 0.56%   |
| Unknown SD/MMC/MS PRO 16GB           | 2         | 0.56%   |
| Unknown MMC Card  16GB               | 2         | 0.56%   |
| Toshiba MQ01ACF050 500GB             | 2         | 0.56%   |
| SPCC Solid State Disk 120GB          | 2         | 0.56%   |
| Seagate Expansion Desk 4TB           | 2         | 0.56%   |
| Seagate BUP Slim BK 1TB              | 2         | 0.56%   |
| SanDisk X400 M.2 2280 512GB SSD      | 2         | 0.56%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.56%   |
| SanDisk SSD PLUS 120GB               | 2         | 0.56%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.56%   |
| Samsung SSD 980 PRO 1TB              | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.56%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.56%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 0.56%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 2         | 0.56%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.56%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.56%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.56%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.56%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 0.56%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 0.56%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.56%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.56%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.56%   |
| China SATA SSD 240GB                 | 2         | 0.56%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.28%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.28%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.28%   |
| WDC WDS100T2B0A 1TB SSD              | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 35        | 38     | 36.84%  |
| WDC     | 22        | 23     | 23.16%  |
| Toshiba | 21        | 24     | 22.11%  |
| HGST    | 8         | 11     | 8.42%   |
| Hitachi | 6         | 6      | 6.32%   |
| Unknown | 2         | 2      | 2.11%   |
| Fujitsu | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 49     | 29.69%  |
| SanDisk             | 16        | 16     | 12.5%   |
| Crucial             | 11        | 12     | 8.59%   |
| Kingston            | 10        | 10     | 7.81%   |
| WDC                 | 8         | 9      | 6.25%   |
| A-DATA Technology   | 6         | 7      | 4.69%   |
| China               | 5         | 5      | 3.91%   |
| SPCC                | 4         | 4      | 3.13%   |
| PNY                 | 4         | 7      | 3.13%   |
| Apple               | 4         | 4      | 3.13%   |
| Micron Technology   | 3         | 5      | 2.34%   |
| Seagate             | 2         | 2      | 1.56%   |
| LITEON              | 2         | 2      | 1.56%   |
| Intenso             | 2         | 3      | 1.56%   |
| Intel               | 2         | 2      | 1.56%   |
| Vaseky              | 1         | 1      | 0.78%   |
| USB30               | 1         | 1      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |
| Toshiba             | 1         | 1      | 0.78%   |
| SK Hynix            | 1         | 1      | 0.78%   |
| OWC                 | 1         | 1      | 0.78%   |
| LITEONIT            | 1         | 1      | 0.78%   |
| KingSpec            | 1         | 1      | 0.78%   |
| Gigabyte Technology | 1         | 1      | 0.78%   |
| DOGFISH             | 1         | 1      | 0.78%   |
| BIWIN               | 1         | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 117       | 148    | 35.35%  |
| NVMe    | 97        | 120    | 29.31%  |
| HDD     | 92        | 105    | 27.79%  |
| MMC     | 20        | 23     | 6.04%   |
| Unknown | 5         | 4      | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 245    | 58.2%   |
| NVMe | 97        | 120    | 31.19%  |
| MMC  | 20        | 23     | 6.43%   |
| SAS  | 13        | 12     | 4.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 161    | 64.88%  |
| 0.51-1.0   | 63        | 82     | 30.73%  |
| 1.01-2.0   | 7         | 8      | 3.41%   |
| 3.01-4.0   | 2         | 2      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 85        | 30.14%  |
| 101-250        | 84        | 29.79%  |
| 501-1000       | 40        | 14.18%  |
| 51-100         | 24        | 8.51%   |
| 21-50          | 15        | 5.32%   |
| 1001-2000      | 15        | 5.32%   |
| 1-20           | 7         | 2.48%   |
| 2001-3000      | 6         | 2.13%   |
| More than 3000 | 3         | 1.06%   |
| Unknown        | 3         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 97        | 33.92%  |
| 101-250        | 57        | 19.93%  |
| 21-50          | 54        | 18.88%  |
| 51-100         | 37        | 12.94%  |
| 251-500        | 20        | 6.99%   |
| 501-1000       | 12        | 4.2%    |
| 1001-2000      | 4         | 1.4%    |
| Unknown        | 3         | 1.05%   |
| More than 3000 | 2         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 11.76%  |
| WDC WD6400BPVT-60HXZT3 640GB        | 1         | 1      | 5.88%   |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 5.88%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 5.88%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 5.88%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 5.88%   |
| Kingston SNS4151S316G 16GB SSD      | 1         | 1      | 5.88%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 5.88%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 5.88%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 6         | 6      | 35.29%  |
| Seagate  | 4         | 4      | 23.53%  |
| WDC      | 2         | 2      | 11.76%  |
| HGST     | 2         | 3      | 11.76%  |
| PNY      | 1         | 1      | 5.88%   |
| Kingston | 1         | 1      | 5.88%   |
| Crucial  | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 42.86%  |
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| HGST    | 2         | 3      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 82.35%  |
| SSD  | 2         | 2      | 11.76%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Detected | 162       | 234    | 54.92%  |
| Works    | 116       | 148    | 39.32%  |
| Malfunc  | 17        | 18     | 5.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 200       | 62.89%  |
| Samsung Electronics          | 45        | 14.15%  |
| AMD                          | 22        | 6.92%   |
| Sandisk                      | 17        | 5.35%   |
| SK Hynix                     | 9         | 2.83%   |
| Toshiba America Info Systems | 7         | 2.2%    |
| Micron Technology            | 3         | 0.94%   |
| Realtek Semiconductor        | 2         | 0.63%   |
| Micron/Crucial Technology    | 2         | 0.63%   |
| Lenovo                       | 2         | 0.63%   |
| Union Memory (Shenzhen)      | 1         | 0.31%   |
| Silicon Motion               | 1         | 0.31%   |
| Shenzhen Longsys Electronics | 1         | 0.31%   |
| Phison Electronics           | 1         | 0.31%   |
| Nvidia                       | 1         | 0.31%   |
| KIOXIA                       | 1         | 0.31%   |
| Kingston Technology Company  | 1         | 0.31%   |
| Apple                        | 1         | 0.31%   |
| ADATA Technology             | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 8.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 8.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 7.76%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 5.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 5.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 4.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2.69%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 2.39%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 2.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.49%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.19%   |
| Sandisk PC SN520 NVMe SSD                                                        | 4         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.19%   |
| Intel SSD 660P Series                                                            | 4         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.9%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.9%    |
| Micron Non-Volatile memory controller                                            | 3         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.9%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.6%    |
| SK Hynix Non-Volatile memory controller                                          | 2         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.6%    |
| Samsung Electronics SATA controller                                              | 2         | 0.6%    |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.6%    |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.6%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.6%    |
| Intel Non-Volatile memory controller                                             | 2         | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.6%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.3%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.3%    |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.3%    |
| SK Hynix BC511                                                                   | 1         | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.3%    |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.3%    |
| Samsung Apple PCIe SSD                                                           | 1         | 0.3%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.3%    |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.3%    |
| Nvidia MCP51 IDE                                                                 | 1         | 0.3%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.3%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.3%    |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.3%    |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 201       | 61.28%  |
| NVMe | 98        | 29.88%  |
| RAID | 18        | 5.49%   |
| IDE  | 11        | 3.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 242       | 87.36%  |
| AMD    | 35        | 12.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 5.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.44%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 1.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.08%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.08%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.08%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.08%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.72%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.72%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.72%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.72%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.72%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 0.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.72%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.72%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.72%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.36%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.36%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.36%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.36%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.36%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.36%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 106       | 38.27%  |
| Intel Core i5           | 68        | 24.55%  |
| Intel Core i3           | 17        | 6.14%   |
| Other                   | 13        | 4.69%   |
| AMD Ryzen 5             | 11        | 3.97%   |
| Intel Celeron           | 10        | 3.61%   |
| Intel Core 2 Duo        | 8         | 2.89%   |
| AMD Ryzen 7             | 8         | 2.89%   |
| Intel Pentium           | 6         | 2.17%   |
| Intel Pentium Silver    | 3         | 1.08%   |
| Intel Atom              | 3         | 1.08%   |
| AMD E                   | 3         | 1.08%   |
| AMD A8                  | 3         | 1.08%   |
| Intel Pentium Dual      | 2         | 0.72%   |
| Intel Genuine           | 2         | 0.72%   |
| AMD Turion 64 X2 Mobile | 2         | 0.72%   |
| AMD Ryzen 9             | 2         | 0.72%   |
| AMD A6                  | 2         | 0.72%   |
| Intel Pentium Dual-Core | 1         | 0.36%   |
| Intel Core m5           | 1         | 0.36%   |
| Intel Core m3           | 1         | 0.36%   |
| Intel Core i9           | 1         | 0.36%   |
| AMD Quad-Core           | 1         | 0.36%   |
| AMD E1                  | 1         | 0.36%   |
| AMD Athlon II           | 1         | 0.36%   |
| AMD A10                 | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 121       | 43.68%  |
| 2      | 117       | 42.24%  |
| 6      | 22        | 7.94%   |
| 8      | 13        | 4.69%   |
| 1      | 2         | 0.72%   |
| 16     | 1         | 0.36%   |
| 14     | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 277       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 217       | 78.34%  |
| 1      | 60        | 21.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 276       | 99.64%  |
| 32-bit         | 1         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 21.2%   |
| 0x806ec    | 19        | 6.71%   |
| 0x306a9    | 19        | 6.71%   |
| 0x206a7    | 19        | 6.71%   |
| 0x906ea    | 13        | 4.59%   |
| 0x806ea    | 13        | 4.59%   |
| 0x40651    | 11        | 3.89%   |
| 0x806e9    | 10        | 3.53%   |
| 0x806c1    | 9         | 3.18%   |
| 0x306c3    | 9         | 3.18%   |
| 0x406e3    | 8         | 2.83%   |
| 0x906e9    | 7         | 2.47%   |
| 0x306d4    | 7         | 2.47%   |
| 0x806eb    | 5         | 1.77%   |
| 0x08600103 | 5         | 1.77%   |
| 0xa0652    | 4         | 1.41%   |
| 0x1067a    | 4         | 1.41%   |
| 0xa0660    | 3         | 1.06%   |
| 0x706e5    | 3         | 1.06%   |
| 0x506e3    | 3         | 1.06%   |
| 0x406c3    | 3         | 1.06%   |
| 0x30678    | 3         | 1.06%   |
| 0x20655    | 3         | 1.06%   |
| 0x10676    | 3         | 1.06%   |
| 0x08108109 | 3         | 1.06%   |
| 0x0810100b | 3         | 1.06%   |
| 0x05000119 | 3         | 1.06%   |
| 0x706a1    | 2         | 0.71%   |
| 0x6fd      | 2         | 0.71%   |
| 0x20652    | 2         | 0.71%   |
| 0x0a50000c | 2         | 0.71%   |
| 0x08600106 | 2         | 0.71%   |
| 0x08600104 | 2         | 0.71%   |
| 0x906ed    | 1         | 0.35%   |
| 0x906c0    | 1         | 0.35%   |
| 0x906a3    | 1         | 0.35%   |
| 0x806d1    | 1         | 0.35%   |
| 0x706a8    | 1         | 0.35%   |
| 0x6fb      | 1         | 0.35%   |
| 0x506c9    | 1         | 0.35%   |
| 0x406c4    | 1         | 0.35%   |
| 0x40661    | 1         | 0.35%   |
| 0x106e5    | 1         | 0.35%   |
| 0x106ca    | 1         | 0.35%   |
| 0x08701013 | 1         | 0.35%   |
| 0x08608103 | 1         | 0.35%   |
| 0x08600102 | 1         | 0.35%   |
| 0x07030105 | 1         | 0.35%   |
| 0x0700010f | 1         | 0.35%   |
| 0x06006705 | 1         | 0.35%   |
| 0x0600611a | 1         | 0.35%   |
| 0x06001119 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 88        | 31.77%  |
| IvyBridge        | 24        | 8.66%   |
| SandyBridge      | 22        | 7.94%   |
| Haswell          | 22        | 7.94%   |
| Skylake          | 13        | 4.69%   |
| Zen 2            | 12        | 4.33%   |
| TigerLake        | 10        | 3.61%   |
| Silvermont       | 9         | 3.25%   |
| CometLake        | 9         | 3.25%   |
| Broadwell        | 9         | 3.25%   |
| Penryn           | 8         | 2.89%   |
| Westmere         | 6         | 2.17%   |
| IceLake          | 6         | 2.17%   |
| Goldmont plus    | 6         | 2.17%   |
| Core             | 4         | 1.44%   |
| Zen+             | 3         | 1.08%   |
| Zen              | 3         | 1.08%   |
| Bobcat           | 3         | 1.08%   |
| Zen 3            | 2         | 0.72%   |
| Puma             | 2         | 0.72%   |
| K8 Hammer        | 2         | 0.72%   |
| Jaguar           | 2         | 0.72%   |
| Excavator        | 2         | 0.72%   |
| Tremont          | 1         | 0.36%   |
| Piledriver       | 1         | 0.36%   |
| P6               | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| K10 Llano        | 1         | 0.36%   |
| K10              | 1         | 0.36%   |
| Goldmont         | 1         | 0.36%   |
| Bonnell          | 1         | 0.36%   |
| Alderlake Hybrid | 1         | 0.36%   |
| Unknown          | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 226       | 63.31%  |
| Nvidia | 80        | 22.41%  |
| AMD    | 51        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 6.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 5.77%   |
| Intel UHD Graphics 620                                                                   | 20        | 5.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.3%    |
| Intel HD Graphics 620                                                                    | 11        | 3.02%   |
| AMD Renoir                                                                               | 11        | 3.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 2.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 2.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.47%   |
| Intel HD Graphics 630                                                                    | 8         | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.92%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.1%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.1%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.1%    |
| Intel Comet Lake UHD Graphics                                                            | 4         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.82%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.82%   |
| Intel HD Graphics 530                                                                    | 3         | 0.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.55%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.55%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 2         | 0.55%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.55%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.55%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.55%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.55%   |
| AMD Mars [Radeon HD 8730M]                                                               | 2         | 0.55%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 2         | 0.55%   |
| AMD Cezanne                                                                              | 2         | 0.55%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.27%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.27%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.27%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                   | 1         | 0.27%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.27%   |
| Nvidia GT215M [GeForce GTS 250M]                                                         | 1         | 0.27%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.27%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 151       | 54.51%  |
| Intel + Nvidia | 61        | 22.02%  |
| 1 x AMD        | 29        | 10.47%  |
| 1 x Nvidia     | 14        | 5.05%   |
| Intel + AMD    | 14        | 5.05%   |
| AMD + Nvidia   | 5         | 1.81%   |
| 2 x AMD        | 3         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 219       | 78.49%  |
| Proprietary | 56        | 20.07%  |
| Unknown     | 4         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 67.5%   |
| 1.01-2.0   | 30        | 10.71%  |
| 0.01-0.5   | 16        | 5.71%   |
| 3.01-4.0   | 15        | 5.36%   |
| 0.51-1.0   | 14        | 5%      |
| 5.01-6.0   | 8         | 2.86%   |
| 7.01-8.0   | 7         | 2.5%    |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 62        | 18.67%  |
| AU Optronics            | 60        | 18.07%  |
| LG Display              | 40        | 12.05%  |
| BOE                     | 39        | 11.75%  |
| Samsung Electronics     | 27        | 8.13%   |
| Dell                    | 13        | 3.92%   |
| Goldstar                | 10        | 3.01%   |
| Apple                   | 9         | 2.71%   |
| Chi Mei Optoelectronics | 8         | 2.41%   |
| Sharp                   | 7         | 2.11%   |
| PANDA                   | 6         | 1.81%   |
| Hewlett-Packard         | 6         | 1.81%   |
| Lenovo                  | 5         | 1.51%   |
| Acer                    | 5         | 1.51%   |
| BenQ                    | 4         | 1.2%    |
| Philips                 | 3         | 0.9%    |
| LGD                     | 3         | 0.9%    |
| InfoVision              | 3         | 0.9%    |
| Ancor Communications    | 3         | 0.9%    |
| Fujitsu Siemens         | 2         | 0.6%    |
| ASUSTek Computer        | 2         | 0.6%    |
| AOC                     | 2         | 0.6%    |
| Vestel Elektronik       | 1         | 0.3%    |
| UPD                     | 1         | 0.3%    |
| Unknown (AAA)           | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| LG Philips              | 1         | 0.3%    |
| Lacie                   | 1         | 0.3%    |
| KTC                     | 1         | 0.3%    |
| JDI                     | 1         | 0.3%    |
| InnoLux Display         | 1         | 0.3%    |
| Iiyama                  | 1         | 0.3%    |
| GDH                     | 1         | 0.3%    |
| Eizo                    | 1         | 0.3%    |
| CSO                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 1.48%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 4         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 3         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.89%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.89%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 3         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.59%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.59%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.59%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.59%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.59%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.59%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.59%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 2         | 0.59%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch      | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch      | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.59%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch        | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch         | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 0.59%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch | 2         | 0.59%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 1         | 0.3%    |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                      | 1         | 0.3%    |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768           | 1         | 0.3%    |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.3%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.3%    |
| Sharp LQ133Z1JW26 SHP1493 3200x1800 294x165mm 13.3-inch               | 1         | 0.3%    |
| Sharp LQ133M1JW48A SHP1531 1920x1080 294x165mm 13.3-inch              | 1         | 0.3%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.3%    |
| Sharp LCD Monitor SHP14C6 1920x1080 344x194mm 15.5-inch               | 1         | 0.3%    |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.3%    |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.3%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch  | 1         | 0.3%    |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 1         | 0.3%    |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch   | 1         | 0.3%    |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1         | 0.3%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.3%    |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch     | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.3%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 139       | 45.28%  |
| 1366x768 (WXGA)   | 85        | 27.69%  |
| 2560x1440 (QHD)   | 16        | 5.21%   |
| 1600x900 (HD+)    | 13        | 4.23%   |
| 3840x2160 (4K)    | 10        | 3.26%   |
| 1280x800 (WXGA)   | 10        | 3.26%   |
| 1440x900 (WXGA+)  | 5         | 1.63%   |
| 1920x1200 (WUXGA) | 4         | 1.3%    |
| 3440x1440         | 3         | 0.98%   |
| 3200x1800 (QHD+)  | 3         | 0.98%   |
| 2880x1800         | 3         | 0.98%   |
| 2560x1080         | 2         | 0.65%   |
| 2160x1440         | 2         | 0.65%   |
| 1280x1024 (SXGA)  | 2         | 0.65%   |
| 3840x2400         | 1         | 0.33%   |
| 3840x1100         | 1         | 0.33%   |
| 3840x1080         | 1         | 0.33%   |
| 3000x2000         | 1         | 0.33%   |
| 2560x1600         | 1         | 0.33%   |
| 2256x1504         | 1         | 0.33%   |
| 1920x1280         | 1         | 0.33%   |
| 1600x1200         | 1         | 0.33%   |
| 1360x768          | 1         | 0.33%   |
| 1280x768          | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 126       | 37.5%   |
| 13      | 59        | 17.56%  |
| 14      | 42        | 12.5%   |
| 24      | 18        | 5.36%   |
| 17      | 17        | 5.06%   |
| 27      | 13        | 3.87%   |
| 23      | 11        | 3.27%   |
| 11      | 8         | 2.38%   |
| 21      | 6         | 1.79%   |
| 34      | 5         | 1.49%   |
| 12      | 5         | 1.49%   |
| Unknown | 5         | 1.49%   |
| 31      | 4         | 1.19%   |
| 19      | 4         | 1.19%   |
| 48      | 2         | 0.6%    |
| 32      | 2         | 0.6%    |
| 18      | 2         | 0.6%    |
| 84      | 1         | 0.3%    |
| 72      | 1         | 0.3%    |
| 54      | 1         | 0.3%    |
| 44      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 22      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 193       | 58.31%  |
| 201-300     | 43        | 12.99%  |
| 501-600     | 38        | 11.48%  |
| 351-400     | 22        | 6.65%   |
| 401-500     | 11        | 3.32%   |
| 701-800     | 7         | 2.11%   |
| 601-700     | 5         | 1.51%   |
| Unknown     | 5         | 1.51%   |
| 1001-1500   | 3         | 0.91%   |
| 1501-2000   | 2         | 0.6%    |
| 801-900     | 1         | 0.3%    |
| 901-1000    | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 242       | 83.45%  |
| 16/10   | 28        | 9.66%   |
| 3/2     | 5         | 1.72%   |
| 21/9    | 5         | 1.72%   |
| Unknown | 5         | 1.72%   |
| 5/4     | 2         | 0.69%   |
| 4/3     | 1         | 0.34%   |
| 32/9    | 1         | 0.34%   |
| 3.40    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 37.72%  |
| 81-90          | 77        | 23.05%  |
| 201-250        | 28        | 8.38%   |
| 71-80          | 23        | 6.89%   |
| 121-130        | 14        | 4.19%   |
| 301-350        | 13        | 3.89%   |
| 351-500        | 12        | 3.59%   |
| 51-60          | 9         | 2.69%   |
| 251-300        | 6         | 1.8%    |
| 61-70          | 5         | 1.5%    |
| Unknown        | 5         | 1.5%    |
| More than 1000 | 4         | 1.2%    |
| 151-200        | 4         | 1.2%    |
| 131-140        | 3         | 0.9%    |
| 501-1000       | 3         | 0.9%    |
| 141-150        | 2         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 124       | 38.04%  |
| 101-120       | 98        | 30.06%  |
| 51-100        | 56        | 17.18%  |
| 161-240       | 23        | 7.06%   |
| More than 240 | 14        | 4.29%   |
| 1-50          | 6         | 1.84%   |
| Unknown       | 5         | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 220       | 78.01%  |
| 2     | 48        | 17.02%  |
| 3     | 10        | 3.55%   |
| 0     | 4         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 167       | 36.95%  |
| Realtek Semiconductor                 | 144       | 31.86%  |
| Qualcomm Atheros                      | 66        | 14.6%   |
| Broadcom                              | 22        | 4.87%   |
| Broadcom Limited                      | 11        | 2.43%   |
| Marvell Technology Group              | 6         | 1.33%   |
| Ralink                                | 5         | 1.11%   |
| Hewlett-Packard                       | 3         | 0.66%   |
| Sierra Wireless                       | 2         | 0.44%   |
| Lenovo                                | 2         | 0.44%   |
| JMicron Technology                    | 2         | 0.44%   |
| Huawei Technologies                   | 2         | 0.44%   |
| ASIX Electronics                      | 2         | 0.44%   |
| Xiaomi                                | 1         | 0.22%   |
| TP-Link                               | 1         | 0.22%   |
| Samsung Electronics                   | 1         | 0.22%   |
| Ralink Technology                     | 1         | 0.22%   |
| Qualcomm Atheros Communications       | 1         | 0.22%   |
| Nvidia                                | 1         | 0.22%   |
| Novatek Microelectronics              | 1         | 0.22%   |
| NetGear                               | 1         | 0.22%   |
| MEDIATEK                              | 1         | 0.22%   |
| Google                                | 1         | 0.22%   |
| Ericsson Business Mobile Networks     | 1         | 0.22%   |
| Edimax Technology                     | 1         | 0.22%   |
| DisplayLink                           | 1         | 0.22%   |
| Dell                                  | 1         | 0.22%   |
| BUFFALO                               | 1         | 0.22%   |
| ASUSTek Computer                      | 1         | 0.22%   |
| Apple                                 | 1         | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 16.24%  |
| Intel Wi-Fi 6 AX200                                               | 30        | 5.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.06%   |
| Intel Wireless 8265 / 8275                                        | 20        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.58%   |
| Intel Wireless-AC 9260                                            | 13        | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.85%   |
| Intel Wireless 7265                                               | 10        | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.66%   |
| Intel Wireless 8260                                               | 9         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.11%   |
| Intel Wireless 7260                                               | 6         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.74%   |
| Intel Wireless 3165                                               | 4         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.55%   |
| Intel WiFi Link 5100                                              | 3         | 0.55%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.55%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.55%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.37%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.37%   |
| Intel Wireless 3160                                               | 2         | 0.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.37%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.37%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 162       | 55.86%  |
| Qualcomm Atheros                      | 54        | 18.62%  |
| Realtek Semiconductor                 | 32        | 11.03%  |
| Broadcom                              | 18        | 6.21%   |
| Broadcom Limited                      | 8         | 2.76%   |
| Ralink                                | 5         | 1.72%   |
| Sierra Wireless                       | 2         | 0.69%   |
| TP-Link                               | 1         | 0.34%   |
| Ralink Technology                     | 1         | 0.34%   |
| Qualcomm Atheros Communications       | 1         | 0.34%   |
| NetGear                               | 1         | 0.34%   |
| MEDIATEK                              | 1         | 0.34%   |
| Edimax Technology                     | 1         | 0.34%   |
| BUFFALO                               | 1         | 0.34%   |
| ASUSTek Computer                      | 1         | 0.34%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 30        | 10.31%  |
| Intel Wireless 8265 / 8275                                     | 20        | 6.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 4.81%   |
| Intel Wireless-AC 9260                                         | 13        | 4.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 3.44%   |
| Intel Wireless 7265                                            | 10        | 3.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 3.09%   |
| Intel Wireless 8260                                            | 9         | 3.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.06%   |
| Intel Wireless 7260                                            | 6         | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.37%   |
| Intel Wireless 3165                                            | 4         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.03%   |
| Intel WiFi Link 5100                                           | 3         | 1.03%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.03%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.03%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.69%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.69%   |
| Intel Wireless 3160                                            | 2         | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.69%   |
| Intel Centrino Wireless-N 2200                                 | 2         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.69%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 2         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 0.34%   |
| Sierra Wireless EM7421                                         | 1         | 0.34%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.34%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.34%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.34%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.34%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.34%   |
| Realtek 802.11ac NIC                                           | 1         | 0.34%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 129       | 54.43%  |
| Intel                    | 57        | 24.05%  |
| Qualcomm Atheros         | 19        | 8.02%   |
| Broadcom                 | 10        | 4.22%   |
| Marvell Technology Group | 6         | 2.53%   |
| Broadcom Limited         | 3         | 1.27%   |
| Lenovo                   | 2         | 0.84%   |
| JMicron Technology       | 2         | 0.84%   |
| ASIX Electronics         | 2         | 0.84%   |
| Xiaomi                   | 1         | 0.42%   |
| Samsung Electronics      | 1         | 0.42%   |
| Nvidia                   | 1         | 0.42%   |
| Hewlett-Packard          | 1         | 0.42%   |
| Google                   | 1         | 0.42%   |
| DisplayLink              | 1         | 0.42%   |
| Apple                    | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 88        | 36.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 9.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 19        | 7.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 2.46%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 1.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.64%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.23%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.82%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.41%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.41%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.41%   |
| Lenovo Thinkpad USB LAN                                                        | 1         | 0.41%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.41%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.41%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.41%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.41%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.41%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.41%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.41%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 1         | 0.41%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.41%   |
| DisplayLink GIQ Triple-display Mini Docking station                            | 1         | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.41%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.41%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.41%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 0.41%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 275       | 54.35%  |
| Ethernet | 224       | 44.27%  |
| Modem    | 7         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 256       | 64.97%  |
| Ethernet | 137       | 34.77%  |
| Modem    | 1         | 0.25%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 211       | 75.9%   |
| 1     | 62        | 22.3%   |
| 0     | 4         | 1.44%   |
| 3     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 245       | 87.19%  |
| Yes  | 36        | 12.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 54.51%  |
| Qualcomm Atheros Communications | 24        | 10.3%   |
| Realtek Semiconductor           | 16        | 6.87%   |
| Broadcom                        | 11        | 4.72%   |
| Lite-On Technology              | 9         | 3.86%   |
| Apple                           | 9         | 3.86%   |
| Foxconn / Hon Hai               | 8         | 3.43%   |
| IMC Networks                    | 6         | 2.58%   |
| Hewlett-Packard                 | 5         | 2.15%   |
| Dell                            | 4         | 1.72%   |
| Realtek                         | 3         | 1.29%   |
| Ralink                          | 3         | 1.29%   |
| Toshiba                         | 2         | 0.86%   |
| Cambridge Silicon Radio         | 2         | 0.86%   |
| Unknown                         | 1         | 0.43%   |
| Integrated System Solution      | 1         | 0.43%   |
| Foxconn International           | 1         | 0.43%   |
| Belkin Components               | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 49        | 21.03%  |
| Intel AX200 Bluetooth                                                               | 28        | 12.02%  |
| Intel Bluetooth Device                                                              | 14        | 6.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 6.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 13        | 5.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 5.15%   |
| Realtek Bluetooth Radio                                                             | 7         | 3%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 2.58%   |
| Lite-On Bluetooth Device                                                            | 5         | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.72%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.72%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.29%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.29%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.29%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.29%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.86%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.86%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.86%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.86%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.86%   |
| Unknown Bluetooth Device                                                            | 1         | 0.43%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.43%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.43%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.43%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.43%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.43%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.43%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.43%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.43%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.43%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.43%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.43%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.43%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.43%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.43%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.43%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.43%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.43%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 239       | 68.88%  |
| AMD                       | 41        | 11.82%  |
| Nvidia                    | 40        | 11.53%  |
| Realtek Semiconductor     | 6         | 1.73%   |
| Kingston Technology       | 2         | 0.58%   |
| GN Netcom                 | 2         | 0.58%   |
| C-Media Electronics       | 2         | 0.58%   |
| XMOS                      | 1         | 0.29%   |
| Sennheiser Communications | 1         | 0.29%   |
| Samson Technologies       | 1         | 0.29%   |
| Razer USA                 | 1         | 0.29%   |
| Plantronics               | 1         | 0.29%   |
| No brand                  | 1         | 0.29%   |
| Logitech                  | 1         | 0.29%   |
| Lenovo                    | 1         | 0.29%   |
| JMTek                     | 1         | 0.29%   |
| Hewlett-Packard           | 1         | 0.29%   |
| Generalplus Technology    | 1         | 0.29%   |
| Conexant Systems          | 1         | 0.29%   |
| CMX Systems               | 1         | 0.29%   |
| Cambridge Audio           | 1         | 0.29%   |
| Apple                     | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 10.4%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 6.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 5.2%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 4.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 3.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.97%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.23%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.23%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.73%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.74%   |
| Nvidia Audio device                                                                               | 3         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.74%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.5%    |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.5%    |
| XMOS BLUE USB Audio 2.0                                                                           | 1         | 0.25%   |
| Sennheiser Communications Sennheiser DECT                                                         | 1         | 0.25%   |
| Samson Technologies Q2U handheld mic with XLR                                                     | 1         | 0.25%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.25%   |
| Plantronics C320-M                                                                                | 1         | 0.25%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.25%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.25%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.25%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.25%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.25%   |
| No brand Thunderbolt 3 Audio                                                                      | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 65        | 34.21%  |
| SK Hynix            | 46        | 24.21%  |
| Micron Technology   | 21        | 11.05%  |
| Kingston            | 11        | 5.79%   |
| Ramaxel Technology  | 9         | 4.74%   |
| Unknown             | 8         | 4.21%   |
| Crucial             | 8         | 4.21%   |
| Corsair             | 3         | 1.58%   |
| A-DATA Technology   | 3         | 1.58%   |
| Unknown (ABCD)      | 2         | 1.05%   |
| Smart               | 2         | 1.05%   |
| Unknown             | 2         | 1.05%   |
| Teikon              | 1         | 0.53%   |
| SMART Brazil        | 1         | 0.53%   |
| PNY                 | 1         | 0.53%   |
| Patriot             | 1         | 0.53%   |
| Nanya Technology    | 1         | 0.53%   |
| Kingmax             | 1         | 0.53%   |
| Goldkey             | 1         | 0.53%   |
| Elpida              | 1         | 0.53%   |
| Cors                | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 2.46%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 2.46%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.97%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 4         | 1.97%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 4         | 1.97%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 4         | 1.97%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 1.48%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 3         | 1.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.48%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 1.48%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 1.48%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.48%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.48%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 1.48%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.99%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.99%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.99%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.99%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 0.99%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.99%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.99%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.99%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.99%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.99%   |
| Unknown                                                          | 2         | 0.99%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM                                 | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.49%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.49%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.49%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s         | 1         | 0.49%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 1         | 0.49%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.49%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.49%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.49%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 0.49%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.49%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 667MT/s                   | 1         | 0.49%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 533MT/s                      | 1         | 0.49%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                 | 1         | 0.49%   |
| SK Hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 0.49%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.49%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.49%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 50.61%  |
| DDR3    | 56        | 34.15%  |
| LPDDR3  | 10        | 6.1%    |
| LPDDR4  | 7         | 4.27%   |
| SDRAM   | 3         | 1.83%   |
| DDR2    | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |
| DDR     | 1         | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 88.75%  |
| Row Of Chips | 16        | 10%     |
| Chip         | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 64        | 35.75%  |
| 8192  | 61        | 34.08%  |
| 16384 | 28        | 15.64%  |
| 2048  | 14        | 7.82%   |
| 32768 | 9         | 5.03%   |
| 1024  | 3         | 1.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 55        | 30.05%  |
| 1600    | 40        | 21.86%  |
| 3200    | 17        | 9.29%   |
| 2133    | 17        | 9.29%   |
| 2400    | 13        | 7.1%    |
| 1333    | 9         | 4.92%   |
| 1334    | 7         | 3.83%   |
| 3266    | 4         | 2.19%   |
| 1067    | 4         | 2.19%   |
| 4199    | 3         | 1.64%   |
| 1867    | 3         | 1.64%   |
| Unknown | 3         | 1.64%   |
| 4267    | 2         | 1.09%   |
| 667     | 2         | 1.09%   |
| 4266    | 1         | 0.55%   |
| 3733    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 533     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 33.33%  |
| HP DeskJet 2130 series | 1         | 33.33%  |
| Brother MFC-1810       | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 70        | 27.89%  |
| Acer                                   | 25        | 9.96%   |
| Sunplus Innovation Technology          | 23        | 9.16%   |
| Realtek Semiconductor                  | 23        | 9.16%   |
| IMC Networks                           | 23        | 9.16%   |
| Microdia                               | 20        | 7.97%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.98%   |
| Apple                                  | 9         | 3.59%   |
| Suyin                                  | 8         | 3.19%   |
| Syntek                                 | 7         | 2.79%   |
| Quanta                                 | 7         | 2.79%   |
| Silicon Motion                         | 6         | 2.39%   |
| Ricoh                                  | 3         | 1.2%    |
| Lite-On Technology                     | 3         | 1.2%    |
| Luxvisions Innotech Limited            | 2         | 0.8%    |
| Z-Star Microelectronics                | 1         | 0.4%    |
| USB Camera                             | 1         | 0.4%    |
| Sonix Technology                       | 1         | 0.4%    |
| Samsung Electronics                    | 1         | 0.4%    |
| Primax Electronics                     | 1         | 0.4%    |
| Logitech                               | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |
| Generalplus Technology                 | 1         | 0.4%    |
| Creative Technology                    | 1         | 0.4%    |
| Alcor Micro                            | 1         | 0.4%    |
| Unknown                                | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                       | 14        | 5.58%   |
| Chicony HD Webcam                                           | 12        | 4.78%   |
| Chicony Integrated Camera                                   | 10        | 3.98%   |
| Microdia Integrated_Webcam_HD                               | 9         | 3.59%   |
| IMC Networks Integrated Camera                              | 7         | 2.79%   |
| Realtek Integrated_Webcam_HD                                | 6         | 2.39%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 2.39%   |
| Chicony HP HD Camera                                        | 5         | 1.99%   |
| Acer HD Webcam                                              | 5         | 1.99%   |
| Acer BisonCam,NB Pro                                        | 5         | 1.99%   |
| Sunplus HD WebCam                                           | 4         | 1.59%   |
| IMC Networks VGA UVC WebCam                                 | 4         | 1.59%   |
| Apple FaceTime HD Camera                                    | 4         | 1.59%   |
| Acer Integrated Camera                                      | 4         | 1.59%   |
| Sunplus Asus Webcam                                         | 3         | 1.2%    |
| Realtek USB2.0 HD UVC WebCam                                | 3         | 1.2%    |
| Realtek Integrated Webcam                                   | 3         | 1.2%    |
| Chicony Integrated Camera [ThinkPad]                        | 3         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 3         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE                                   | 3         | 1.2%    |
| Acer BisonCam, NB Pro                                       | 3         | 1.2%    |
| Syntek Integrated Camera                                    | 2         | 0.8%    |
| Syntek EasyCamera                                           | 2         | 0.8%    |
| Suyin HP Truevision HD                                      | 2         | 0.8%    |
| Sunplus Lenovo EasyCamera                                   | 2         | 0.8%    |
| Sunplus Integrated_Webcam_HD                                | 2         | 0.8%    |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 0.8%    |
| Sunplus HD User Facing                                      | 2         | 0.8%    |
| Realtek Lenovo EasyCamera                                   | 2         | 0.8%    |
| Realtek HP "Truevision HD" laptop camera                    | 2         | 0.8%    |
| Realtek HD WebCam                                           | 2         | 0.8%    |
| Microdia Sonix USB 2.0 Camera                               | 2         | 0.8%    |
| IMC Networks ov9734_azurewave_camera                        | 2         | 0.8%    |
| IMC Networks HD Camera                                      | 2         | 0.8%    |
| Chicony thinkpad t430s camera                               | 2         | 0.8%    |
| Chicony HD WebCam (Asus N-series)                           | 2         | 0.8%    |
| Chicony FJ Camera                                           | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 0.8%    |
| Acer SunplusIT Integrated Camera                            | 2         | 0.8%    |
| Acer EasyCamera                                             | 2         | 0.8%    |
| Z-Star Lenovo EasyCamera                                    | 1         | 0.4%    |
| USB Camera USB Camera                                       | 1         | 0.4%    |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.4%    |
| Syntek USB2.0 Camera                                        | 1         | 0.4%    |
| Syntek Lenovo EasyCamera                                    | 1         | 0.4%    |
| Suyin Webcam-101                                            | 1         | 0.4%    |
| Suyin USB 2.0 Camera                                        | 1         | 0.4%    |
| Suyin Sony Visual Communication Camera                      | 1         | 0.4%    |
| Suyin HD WebCam                                             | 1         | 0.4%    |
| Suyin Acer HD Crystal Eye webcam                            | 1         | 0.4%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.4%    |
| Sunplus USB Camera                                          | 1         | 0.4%    |
| Sunplus MTD Camera                                          | 1         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.4%    |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.4%    |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.4%    |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.4%    |
| Sunplus Integrated Camera                                   | 1         | 0.4%    |
| Sunplus Aukey-PC-LM1E Camera                                | 1         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 37.5%   |
| Validity Sensors           | 21        | 32.81%  |
| Shenzhen Goodix Technology | 8         | 12.5%   |
| LighTuning Technology      | 6         | 9.38%   |
| Elan Microelectronics      | 3         | 4.69%   |
| AuthenTec                  | 2         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 10.94%  |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 10.94%  |
| Unknown                                                                    | 7         | 10.94%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 9.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 6.25%   |
| Synaptics WBDI Device                                                      | 4         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 4.69%   |
| Elan ELAN:Fingerprint                                                      | 3         | 4.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.13%   |
| Validity Sensors VFS491                                                    | 2         | 3.13%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.56%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.56%   |
| AuthenTec AES1600                                                          | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 47.37%  |
| Upek        | 5         | 26.32%  |
| Alcor Micro | 3         | 15.79%  |
| Lenovo      | 2         | 10.53%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15.79%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 15.79%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10.53%  |
| Broadcom 58200                                                               | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 56.63%  |
| 1     | 98        | 35.13%  |
| 2     | 21        | 7.53%   |
| 4     | 1         | 0.36%   |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 45%     |
| Graphics card            | 21        | 15%     |
| Chipcard                 | 18        | 12.86%  |
| Communication controller | 12        | 8.57%   |
| Net/wireless             | 10        | 7.14%   |
| Storage                  | 3         | 2.14%   |
| Multimedia controller    | 3         | 2.14%   |
| Card reader              | 3         | 2.14%   |
| Camera                   | 3         | 2.14%   |
| Bluetooth                | 3         | 2.14%   |
| Net/ethernet             | 1         | 0.71%   |
