Ubuntu Budgie - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie/Notebook/README.md).

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

Total: 707

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Positivo      | Q232A                       | Notebook    | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | Notebook    | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e97309bc05](https://linux-hardware.org/?probe=e97309bc05) | May 07, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [9505d0e8b7](https://linux-hardware.org/?probe=9505d0e8b7) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [a94d46ec1d](https://linux-hardware.org/?probe=a94d46ec1d) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [f62d16f3b1](https://linux-hardware.org/?probe=f62d16f3b1) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Dell          | 0RW199                      | Desktop     | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d7414a7101](https://linux-hardware.org/?probe=d7414a7101) | Jan 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| Teclast       | X6 plus                     | Tablet      | [d476f875d2](https://linux-hardware.org/?probe=d476f875d2) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| HP            | Pavilion dm1                | Notebook    | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [8ecbd29abd](https://linux-hardware.org/?probe=8ecbd29abd) | Oct 29, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [feb38e948d](https://linux-hardware.org/?probe=feb38e948d) | Sep 13, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | Notebook    | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Google        | Peppy                       | Notebook    | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP            | 1588h                       | Desktop     | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | Notebook    | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| AWOW          | AK41                        | Notebook    | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | Notebook    | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | Latitude D531               | Notebook    | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | Notebook    | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9c8b7bc48a](https://linux-hardware.org/?probe=9c8b7bc48a) | Apr 06, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | Notebook    | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [104c966a1a](https://linux-hardware.org/?probe=104c966a1a) | Mar 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f769aaeedd](https://linux-hardware.org/?probe=f769aaeedd) | Mar 26, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP            | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [d9cc78fcff](https://linux-hardware.org/?probe=d9cc78fcff) | Mar 07, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [bc79c52365](https://linux-hardware.org/?probe=bc79c52365) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Dell          | 0KJCC5 A00                  | Desktop     | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| BCM           | RX965Q                      | Desktop     | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek       | H61M-A                      | Desktop     | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Lenovo        | 36F2 SDK0J40700 WIN 3258... | All in one  | [f172b5b1ea](https://linux-hardware.org/?probe=f172b5b1ea) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Dell          | XPS L322X                   | Notebook    | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP            | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI           | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| eMachines     | EZ1600                      | All in one  | [2c5f74bdac](https://linux-hardware.org/?probe=2c5f74bdac) | Jan 01, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Toshiba       | Satellite P750              | Notebook    | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| eMachines     | EZ1600                      | All in one  | [2181178e2b](https://linux-hardware.org/?probe=2181178e2b) | Dec 25, 2020 |
| Dell          | 0PK096                      | Desktop     | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | Notebook    | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda    | Alpha                       | Desktop     | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| LattePanda    | Alpha                       | Desktop     | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | Notebook    | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Apple         | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| HP            | ZBook 14                    | Notebook    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP            | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| Dell          | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock        | Q1900B-ITX                  | Desktop     | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| Dell          | 0M9KCM A00                  | Desktop     | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI           | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell          | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Dell          | 0RY007                      | Desktop     | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa         | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | Notebook    | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | Notebook    | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | Notebook    | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | Notebook    | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard      | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP            | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP            | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP            | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell          | 0P301D A02                  | Desktop     | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| MSI           | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | Notebook    | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer          | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | Notebook    | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| HP            | 0A80h                       | Desktop     | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| HP            | 8433 11                     | Desktop     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| HP            | 84EE 1100                   | All in one  | [870857c93c](https://linux-hardware.org/?probe=870857c93c) | Mar 30, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| HP            | Compaq 6720s                | Notebook    | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | Notebook    | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | Notebook    | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell          | Latitude 5400               | Notebook    | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | Notebook    | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | Notebook    | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e008a514e](https://linux-hardware.org/?probe=1e008a514e) | Mar 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [01c8982ddb](https://linux-hardware.org/?probe=01c8982ddb) | Mar 06, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | Notebook    | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| eMachines     | EL1852G                     | Desktop     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| HP            | ENVY x360 Convertible       | Convertible | [d98a9e0c48](https://linux-hardware.org/?probe=d98a9e0c48) | Feb 27, 2020 |
| Intel         | DQ965CO AAD34641-506        | Desktop     | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| HP            | 2215                        | Desktop     | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| HP            | 2000                        | Notebook    | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | Notebook    | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | Notebook    | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Supermicro    | X9DRT                       | Server      | [f5f0a90676](https://linux-hardware.org/?probe=f5f0a90676) | Nov 19, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| Dell          | 0G9322                      | Desktop     | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 240       | 48.29%  |
| Ubuntu Budgie 20.10 | 61        | 12.27%  |
| Ubuntu Budgie 21.10 | 55        | 11.07%  |
| Ubuntu Budgie 18.04 | 38        | 7.65%   |
| Ubuntu Budgie 21.04 | 35        | 7.04%   |
| Ubuntu Budgie 22.04 | 34        | 6.84%   |
| Ubuntu Budgie 19.10 | 29        | 5.84%   |
| Ubuntu Budgie       | 3         | 0.6%    |
| Ubuntu Budgie 16.04 | 2         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 478       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 27        | 4.98%   |
| 5.3.0-40-generic  | 15        | 2.77%   |
| 5.13.0-22-generic | 14        | 2.58%   |
| 5.4.0-40-generic  | 13        | 2.4%    |
| 5.15.0-27-generic | 11        | 2.03%   |
| 5.4.0-52-generic  | 10        | 1.85%   |
| 5.4.0-37-generic  | 10        | 1.85%   |
| 5.13.0-19-generic | 10        | 1.85%   |
| 5.4.0-58-generic  | 9         | 1.66%   |
| 5.4.0-48-generic  | 9         | 1.66%   |
| 5.4.0-29-generic  | 9         | 1.66%   |
| 5.13.0-39-generic | 9         | 1.66%   |
| 5.8.0-48-generic  | 8         | 1.48%   |
| 5.8.0-44-generic  | 8         | 1.48%   |
| 5.8.0-41-generic  | 8         | 1.48%   |
| 5.13.0-40-generic | 8         | 1.48%   |
| 5.13.0-28-generic | 8         | 1.48%   |
| 5.8.0-43-generic  | 7         | 1.29%   |
| 5.4.0-47-generic  | 7         | 1.29%   |
| 5.4.0-33-generic  | 7         | 1.29%   |
| 5.4.0-31-generic  | 7         | 1.29%   |
| 5.13.0-30-generic | 7         | 1.29%   |
| 5.8.0-53-generic  | 6         | 1.11%   |
| 5.8.0-45-generic  | 6         | 1.11%   |
| 5.8.0-29-generic  | 6         | 1.11%   |
| 5.15.0-30-generic | 6         | 1.11%   |
| 5.13.0-35-generic | 6         | 1.11%   |
| 5.11.0-41-generic | 6         | 1.11%   |
| 5.8.0-33-generic  | 5         | 0.92%   |
| 5.8.0-25-generic  | 5         | 0.92%   |
| 5.4.0-91-generic  | 5         | 0.92%   |
| 5.4.0-45-generic  | 5         | 0.92%   |
| 5.3.0-42-generic  | 5         | 0.92%   |
| 5.3.0-26-generic  | 5         | 0.92%   |
| 5.15.0-39-generic | 5         | 0.92%   |
| 5.11.0-22-generic | 5         | 0.92%   |
| 5.11.0-16-generic | 5         | 0.92%   |
| 5.8.0-59-generic  | 4         | 0.74%   |
| 5.8.0-26-generic  | 4         | 0.74%   |
| 5.4.0-72-generic  | 4         | 0.74%   |
| 5.4.0-66-generic  | 4         | 0.74%   |
| 5.4.0-59-generic  | 4         | 0.74%   |
| 5.4.0-28-generic  | 4         | 0.74%   |
| 5.11.0-34-generic | 4         | 0.74%   |
| 5.11.0-25-generic | 4         | 0.74%   |
| 5.11.0-18-generic | 4         | 0.74%   |
| 5.8.0-50-generic  | 3         | 0.55%   |
| 5.8.0-31-generic  | 3         | 0.55%   |
| 5.4.0-80-generic  | 3         | 0.55%   |
| 5.4.0-73-generic  | 3         | 0.55%   |
| 5.4.0-65-generic  | 3         | 0.55%   |
| 5.4.0-62-generic  | 3         | 0.55%   |
| 5.4.0-54-generic  | 3         | 0.55%   |
| 5.4.0-26-generic  | 3         | 0.55%   |
| 5.3.0-24-generic  | 3         | 0.55%   |
| 5.15.0-33-generic | 3         | 0.55%   |
| 5.15.0-25-generic | 3         | 0.55%   |
| 5.13.0-27-generic | 3         | 0.55%   |
| 5.13.0-25-generic | 3         | 0.55%   |
| 5.13.0-21-generic | 3         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 169       | 33.73%  |
| 5.8.0   | 89        | 17.76%  |
| 5.13.0  | 76        | 15.17%  |
| 5.11.0  | 51        | 10.18%  |
| 5.3.0   | 42        | 8.38%   |
| 5.15.0  | 32        | 6.39%   |
| 4.15.0  | 12        | 2.4%    |
| 5.6.0   | 3         | 0.6%    |
| 5.0.0   | 3         | 0.6%    |
| 5.6.7   | 2         | 0.4%    |
| 5.12.0  | 2         | 0.4%    |
| 5.10.0  | 2         | 0.4%    |
| 4.18.0  | 2         | 0.4%    |
| 5.9.1   | 1         | 0.2%    |
| 5.9.0   | 1         | 0.2%    |
| 5.8.6   | 1         | 0.2%    |
| 5.8.11  | 1         | 0.2%    |
| 5.7.7   | 1         | 0.2%    |
| 5.5.8   | 1         | 0.2%    |
| 5.5.0   | 1         | 0.2%    |
| 5.17.2  | 1         | 0.2%    |
| 5.17.1  | 1         | 0.2%    |
| 5.16.2  | 1         | 0.2%    |
| 5.16.14 | 1         | 0.2%    |
| 5.15.11 | 1         | 0.2%    |
| 5.14.2  | 1         | 0.2%    |
| 5.14.1  | 1         | 0.2%    |
| 5.10.11 | 1         | 0.2%    |
| 4.4.0   | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 169       | 33.8%   |
| 5.8     | 91        | 18.2%   |
| 5.13    | 76        | 15.2%   |
| 5.11    | 51        | 10.2%   |
| 5.3     | 42        | 8.4%    |
| 5.15    | 33        | 6.6%    |
| 4.15    | 12        | 2.4%    |
| 5.6     | 5         | 1%      |
| 5.10    | 3         | 0.6%    |
| 5.0     | 3         | 0.6%    |
| 5.9     | 2         | 0.4%    |
| 5.5     | 2         | 0.4%    |
| 5.17    | 2         | 0.4%    |
| 5.16    | 2         | 0.4%    |
| 5.12    | 2         | 0.4%    |
| 4.18    | 2         | 0.4%    |
| 5.7     | 1         | 0.2%    |
| 5.14    | 1         | 0.2%    |
| 4.4     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 465       | 97.28%  |
| i686    | 9         | 1.88%   |
| aarch64 | 3         | 0.63%   |
| armv7l  | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 468       | 97.91%  |
| GNOME  | 8         | 1.67%   |
| XFCE   | 1         | 0.21%   |
| KDE    | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 466       | 97.49%  |
| Wayland | 10        | 2.09%   |
| Tty     | 2         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 228       | 46.82%  |
| LightDM | 124       | 25.46%  |
| TDM     | 92        | 18.89%  |
| GDM     | 31        | 6.37%   |
| GDM3    | 10        | 2.05%   |
| SDDM    | 2         | 0.41%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 173       | 36.12%  |
| de_DE   | 64        | 13.36%  |
| pt_BR   | 34        | 7.1%    |
| fr_FR   | 32        | 6.68%   |
| en_GB   | 26        | 5.43%   |
| en_CA   | 19        | 3.97%   |
| it_IT   | 12        | 2.51%   |
| ru_RU   | 11        | 2.3%    |
| es_ES   | 9         | 1.88%   |
| es_AR   | 9         | 1.88%   |
| en_IN   | 9         | 1.88%   |
| es_MX   | 8         | 1.67%   |
| en_AU   | 8         | 1.67%   |
| Unknown | 6         | 1.25%   |
| C       | 5         | 1.04%   |
| pl_PL   | 4         | 0.84%   |
| es_CL   | 4         | 0.84%   |
| uk_UA   | 3         | 0.63%   |
| pt_PT   | 3         | 0.63%   |
| nl_NL   | 3         | 0.63%   |
| hu_HU   | 3         | 0.63%   |
| de_AT   | 3         | 0.63%   |
| zh_TW   | 2         | 0.42%   |
| fi_FI   | 2         | 0.42%   |
| es_CO   | 2         | 0.42%   |
| en_IE   | 2         | 0.42%   |
| de_CH   | 2         | 0.42%   |
| zh_CN   | 1         | 0.21%   |
| tr_TR   | 1         | 0.21%   |
| sv_SE   | 1         | 0.21%   |
| ru_UA   | 1         | 0.21%   |
| ro_RO   | 1         | 0.21%   |
| nl_BE   | 1         | 0.21%   |
| nb_NO   | 1         | 0.21%   |
| lv_LV   | 1         | 0.21%   |
| ja_JP   | 1         | 0.21%   |
| id_ID   | 1         | 0.21%   |
| fr_CH   | 1         | 0.21%   |
| fr_CA   | 1         | 0.21%   |
| fr_BE   | 1         | 0.21%   |
| es_US   | 1         | 0.21%   |
| es_SV   | 1         | 0.21%   |
| es_GT   | 1         | 0.21%   |
| es_EC   | 1         | 0.21%   |
| en_ZA   | 1         | 0.21%   |
| en_SG   | 1         | 0.21%   |
| en_IL   | 1         | 0.21%   |
| bg_BG   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 271       | 54.97%  |
| BIOS | 222       | 45.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 447       | 93.13%  |
| Zfs     | 13        | 2.71%   |
| Overlay | 10        | 2.08%   |
| Btrfs   | 6         | 1.25%   |
| Xfs     | 3         | 0.63%   |
| Jfs     | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 282       | 58.51%  |
| GPT     | 163       | 33.82%  |
| MBR     | 37        | 7.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 416       | 85.6%   |
| Yes       | 70        | 14.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 335       | 68.79%  |
| Yes       | 152       | 31.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 72        | 15.06%  |
| Hewlett-Packard         | 71        | 14.85%  |
| Lenovo                  | 65        | 13.6%   |
| Dell                    | 55        | 11.51%  |
| TUXEDO                  | 33        | 6.9%    |
| Gigabyte Technology     | 30        | 6.28%   |
| Apple                   | 24        | 5.02%   |
| MSI                     | 23        | 4.81%   |
| Acer                    | 22        | 4.6%    |
| ASRock                  | 11        | 2.3%    |
| Samsung Electronics     | 6         | 1.26%   |
| Intel                   | 6         | 1.26%   |
| Sony                    | 5         | 1.05%   |
| HUAWEI                  | 5         | 1.05%   |
| Unknown                 | 5         | 1.05%   |
| Fujitsu                 | 4         | 0.84%   |
| Toshiba                 | 3         | 0.63%   |
| Raspberry Pi Foundation | 3         | 0.63%   |
| Packard Bell            | 3         | 0.63%   |
| Google                  | 3         | 0.63%   |
| Timi                    | 2         | 0.42%   |
| Standard                | 2         | 0.42%   |
| Positivo                | 2         | 0.42%   |
| eMachines               | 2         | 0.42%   |
| Viglen                  | 1         | 0.21%   |
| Teclast                 | 1         | 0.21%   |
| Supermicro              | 1         | 0.21%   |
| Razer                   | 1         | 0.21%   |
| Radxa                   | 1         | 0.21%   |
| Quanta                  | 1         | 0.21%   |
| Pegatron                | 1         | 0.21%   |
| PCSMART                 | 1         | 0.21%   |
| PC Specialist           | 1         | 0.21%   |
| Microsoft               | 1         | 0.21%   |
| LattePanda              | 1         | 0.21%   |
| Huanan                  | 1         | 0.21%   |
| GPU Company             | 1         | 0.21%   |
| EVOO                    | 1         | 0.21%   |
| Chuwi                   | 1         | 0.21%   |
| Biostar                 | 1         | 0.21%   |
| BCM                     | 1         | 0.21%   |
| BANGHO                  | 1         | 0.21%   |
| AWOW                    | 1         | 0.21%   |
| Avell High Performance  | 1         | 0.21%   |
| Alienware               | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 15        | 3.14%   |
| ASUS All Series                        | 5         | 1.05%   |
| HP Pavilion g6                         | 3         | 0.63%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 0.42%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 0.42%   |
| TUXEDO InfinityBook S 14 Gen6          | 2         | 0.42%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 0.42%   |
| TUXEDO Aura 15 Gen1                    | 2         | 0.42%   |
| Standard MT40II                        | 2         | 0.42%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 2         | 0.42%   |
| MSI MS-7C84                            | 2         | 0.42%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.42%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.42%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 2         | 0.42%   |
| HP ZBook Studio G3                     | 2         | 0.42%   |
| HP Notebook                            | 2         | 0.42%   |
| HP ENVY 15                             | 2         | 0.42%   |
| HP EliteDesk 800 G1 SFF                | 2         | 0.42%   |
| HP 2000                                | 2         | 0.42%   |
| Gigabyte Z68M-D2H                      | 2         | 0.42%   |
| Gigabyte AB350-Gaming 3                | 2         | 0.42%   |
| Dell XPS 13 9380                       | 2         | 0.42%   |
| Dell Precision WorkStation T3500       | 2         | 0.42%   |
| Dell OptiPlex 9010                     | 2         | 0.42%   |
| Dell OptiPlex 780                      | 2         | 0.42%   |
| Dell Latitude E6540                    | 2         | 0.42%   |
| Dell Latitude 5400                     | 2         | 0.42%   |
| Dell Inspiron 5570                     | 2         | 0.42%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT | 2         | 0.42%   |
| ASUS P8H77-M PRO                       | 2         | 0.42%   |
| Apple MacPro1,1                        | 2         | 0.42%   |
| Apple MacBookPro8,1                    | 2         | 0.42%   |
| Acer TravelMate P446-M                 | 2         | 0.42%   |
| Viglen VUB1                            | 1         | 0.21%   |
| TUXEDO Stellaris Intel Gen3 (TGL)      | 1         | 0.21%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.21%   |
| TUXEDO Pulse 15 Gen1                   | 1         | 0.21%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.21%   |
| TUXEDO Polaris 17 AMD Gen1             | 1         | 0.21%   |
| TUXEDO P95_HR                          | 1         | 0.21%   |
| TUXEDO P95_HP                          | 1         | 0.21%   |
| TUXEDO P7xxTM1                         | 1         | 0.21%   |
| TUXEDO InfinityBook S 14 v5            | 1         | 0.21%   |
| TUXEDO InfinityBook Pro 15 v4          | 1         | 0.21%   |
| TUXEDO Book_XA1510                     | 1         | 0.21%   |
| TUXEDO Book XP1511                     | 1         | 0.21%   |
| TUXEDO Book XP15 / XP17 Gen12          | 1         | 0.21%   |
| Toshiba Satellite S55-C                | 1         | 0.21%   |
| Toshiba Satellite P750                 | 1         | 0.21%   |
| Toshiba Satellite P300                 | 1         | 0.21%   |
| Timi TM1701                            | 1         | 0.21%   |
| Timi TM1604                            | 1         | 0.21%   |
| Teclast X6 plus                        | 1         | 0.21%   |
| Supermicro X9DRT                       | 1         | 0.21%   |
| Sony VPCEK20AL                         | 1         | 0.21%   |
| Sony VPCEJ1L1E                         | 1         | 0.21%   |
| Sony VPCEA47FX                         | 1         | 0.21%   |
| Sony VPCCW25FL                         | 1         | 0.21%   |
| Sony SVS13A25PBS                       | 1         | 0.21%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 29        | 6.07%   |
| HP Pavilion           | 15        | 3.14%   |
| Dell Latitude         | 15        | 3.14%   |
| Dell Inspiron         | 15        | 3.14%   |
| Unknown               | 15        | 3.14%   |
| Lenovo IdeaPad        | 14        | 2.93%   |
| Acer Aspire           | 14        | 2.93%   |
| Dell XPS              | 9         | 1.88%   |
| TUXEDO InfinityBook   | 8         | 1.67%   |
| HP EliteBook          | 8         | 1.67%   |
| HP ENVY               | 7         | 1.46%   |
| Dell OptiPlex         | 7         | 1.46%   |
| ASUS ROG              | 7         | 1.46%   |
| HP Compaq             | 6         | 1.26%   |
| ASUS VivoBook         | 6         | 1.26%   |
| ASUS PRIME            | 6         | 1.26%   |
| HP Spectre            | 5         | 1.05%   |
| Dell Precision        | 5         | 1.05%   |
| ASUS All              | 5         | 1.05%   |
| TUXEDO Polaris        | 4         | 0.84%   |
| HP ZBook              | 4         | 0.84%   |
| HP Laptop             | 4         | 0.84%   |
| HP EliteDesk          | 4         | 0.84%   |
| Acer Swift            | 4         | 0.84%   |
| TUXEDO Book           | 3         | 0.63%   |
| Toshiba Satellite     | 3         | 0.63%   |
| RPi Raspberry         | 3         | 0.63%   |
| Lenovo Yoga           | 3         | 0.63%   |
| Lenovo ThinkBook      | 3         | 0.63%   |
| HP ProBook            | 3         | 0.63%   |
| Fujitsu LIFEBOOK      | 3         | 0.63%   |
| ASUS TUF              | 3         | 0.63%   |
| ASUS P8H77-M          | 3         | 0.63%   |
| Apple MacBookPro8     | 3         | 0.63%   |
| TUXEDO Stellaris      | 2         | 0.42%   |
| TUXEDO P95            | 2         | 0.42%   |
| TUXEDO Aura           | 2         | 0.42%   |
| Standard MT40II       | 2         | 0.42%   |
| Packard Bell EasyNote | 2         | 0.42%   |
| MSI Prestige          | 2         | 0.42%   |
| MSI MS-7C84           | 2         | 0.42%   |
| MSI Modern            | 2         | 0.42%   |
| Lenovo IdeaCentre     | 2         | 0.42%   |
| HP Stream             | 2         | 0.42%   |
| HP Notebook           | 2         | 0.42%   |
| HP 2000               | 2         | 0.42%   |
| Gigabyte Z68M-D2H     | 2         | 0.42%   |
| Gigabyte B360         | 2         | 0.42%   |
| Gigabyte AB350-Gaming | 2         | 0.42%   |
| Dell Vostro           | 2         | 0.42%   |
| ASUS P8Z68-V          | 2         | 0.42%   |
| ASRock B550           | 2         | 0.42%   |
| Apple MacPro1         | 2         | 0.42%   |
| Apple MacBookPro11    | 2         | 0.42%   |
| Apple iMac18          | 2         | 0.42%   |
| Acer TravelMate       | 2         | 0.42%   |
| Viglen VUB1           | 1         | 0.21%   |
| TUXEDO Pulse          | 1         | 0.21%   |
| TUXEDO P7xxTM1        | 1         | 0.21%   |
| Timi TM1701           | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 62        | 12.97%  |
| 2018    | 58        | 12.13%  |
| 2020    | 50        | 10.46%  |
| 2017    | 38        | 7.95%   |
| 2011    | 36        | 7.53%   |
| 2012    | 34        | 7.11%   |
| 2013    | 33        | 6.9%    |
| 2014    | 27        | 5.65%   |
| 2021    | 25        | 5.23%   |
| 2015    | 25        | 5.23%   |
| 2016    | 23        | 4.81%   |
| 2010    | 19        | 3.97%   |
| 2009    | 16        | 3.35%   |
| 2008    | 15        | 3.14%   |
| 2007    | 13        | 2.72%   |
| Unknown | 3         | 0.63%   |
| 2022    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 296       | 61.92%  |
| Desktop        | 141       | 29.5%   |
| All in one     | 13        | 2.72%   |
| Convertible    | 12        | 2.51%   |
| Mini pc        | 6         | 1.26%   |
| Tablet         | 5         | 1.05%   |
| System on chip | 4         | 0.84%   |
| Server         | 1         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 441       | 91.88%  |
| Enabled  | 39        | 8.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 475       | 99.37%  |
| Yes  | 3         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 120       | 24.84%  |
| 4.01-8.0    | 114       | 23.6%   |
| 3.01-4.0    | 80        | 16.56%  |
| 8.01-16.0   | 79        | 16.36%  |
| 32.01-64.0  | 51        | 10.56%  |
| 64.01-256.0 | 19        | 3.93%   |
| 1.01-2.0    | 10        | 2.07%   |
| 24.01-32.0  | 5         | 1.04%   |
| 2.01-3.0    | 3         | 0.62%   |
| 0.51-1.0    | 2         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 160       | 31.01%  |
| 1.01-2.0   | 142       | 27.52%  |
| 4.01-8.0   | 92        | 17.83%  |
| 3.01-4.0   | 85        | 16.47%  |
| 8.01-16.0  | 25        | 4.84%   |
| 0.51-1.0   | 9         | 1.74%   |
| 32.01-64.0 | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 286       | 58.49%  |
| 2      | 128       | 26.18%  |
| 3      | 36        | 7.36%   |
| 4      | 17        | 3.48%   |
| 5      | 12        | 2.45%   |
| 8      | 4         | 0.82%   |
| 6      | 3         | 0.61%   |
| 11     | 1         | 0.2%    |
| 9      | 1         | 0.2%    |
| 0      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 304       | 63.33%  |
| Yes       | 176       | 36.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 401       | 83.72%  |
| No        | 78        | 16.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 82.5%   |
| No        | 84        | 17.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 69.29%  |
| No        | 148       | 30.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 90        | 18.79%  |
| Germany            | 72        | 15.03%  |
| Brazil             | 36        | 7.52%   |
| France             | 32        | 6.68%   |
| Canada             | 18        | 3.76%   |
| UK                 | 17        | 3.55%   |
| Italy              | 15        | 3.13%   |
| Russia             | 13        | 2.71%   |
| Argentina          | 12        | 2.51%   |
| India              | 11        | 2.3%    |
| Poland             | 10        | 2.09%   |
| Netherlands        | 10        | 2.09%   |
| Mexico             | 10        | 2.09%   |
| Spain              | 9         | 1.88%   |
| Australia          | 8         | 1.67%   |
| Ukraine            | 7         | 1.46%   |
| Switzerland        | 7         | 1.46%   |
| Austria            | 7         | 1.46%   |
| Norway             | 6         | 1.25%   |
| Portugal           | 5         | 1.04%   |
| Japan              | 5         | 1.04%   |
| Hungary            | 5         | 1.04%   |
| Sweden             | 4         | 0.84%   |
| Finland            | 4         | 0.84%   |
| Croatia            | 4         | 0.84%   |
| Chile              | 4         | 0.84%   |
| Belgium            | 4         | 0.84%   |
| Turkey             | 3         | 0.63%   |
| South Africa       | 3         | 0.63%   |
| Ireland            | 3         | 0.63%   |
| Iran               | 3         | 0.63%   |
| Greece             | 3         | 0.63%   |
| Dominican Republic | 3         | 0.63%   |
| Colombia           | 3         | 0.63%   |
| Slovenia           | 2         | 0.42%   |
| Romania            | 2         | 0.42%   |
| Malaysia           | 2         | 0.42%   |
| Indonesia          | 2         | 0.42%   |
| Ecuador            | 2         | 0.42%   |
| Thailand           | 1         | 0.21%   |
| Taiwan             | 1         | 0.21%   |
| Slovakia           | 1         | 0.21%   |
| Singapore          | 1         | 0.21%   |
| Serbia             | 1         | 0.21%   |
| Saudi Arabia       | 1         | 0.21%   |
| Puerto Rico        | 1         | 0.21%   |
| Philippines        | 1         | 0.21%   |
| Myanmar            | 1         | 0.21%   |
| Libya              | 1         | 0.21%   |
| Latvia             | 1         | 0.21%   |
| Kenya              | 1         | 0.21%   |
| Jordan             | 1         | 0.21%   |
| Israel             | 1         | 0.21%   |
| Hong Kong          | 1         | 0.21%   |
| Honduras           | 1         | 0.21%   |
| Guatemala          | 1         | 0.21%   |
| Ghana              | 1         | 0.21%   |
| El Salvador        | 1         | 0.21%   |
| Egypt              | 1         | 0.21%   |
| Bulgaria           | 1         | 0.21%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 7         | 1.44%   |
| Ravensburg         | 5         | 1.03%   |
| Moscow             | 5         | 1.03%   |
| Hamburg            | 5         | 1.03%   |
| Berlin             | 5         | 1.03%   |
| Montreal           | 4         | 0.82%   |
| Budapest           | 4         | 0.82%   |
| Zurich             | 3         | 0.62%   |
| Zagreb             | 3         | 0.62%   |
| Vienna             | 3         | 0.62%   |
| Tehran             | 3         | 0.62%   |
| Sydney             | 3         | 0.62%   |
| Santo Domingo Este | 3         | 0.62%   |
| Paris              | 3         | 0.62%   |
| Miami              | 3         | 0.62%   |
| Lisbon             | 3         | 0.62%   |
| Dublin             | 3         | 0.62%   |
| Bras??lia          | 3         | 0.62%   |
| Bogot??            | 3         | 0.62%   |
| Barcelona          | 3         | 0.62%   |
| Athens             | 3         | 0.62%   |
| Vancouver          | 2         | 0.41%   |
| Uman               | 2         | 0.41%   |
| Trondheim          | 2         | 0.41%   |
| Toronto            | 2         | 0.41%   |
| Timi??oara         | 2         | 0.41%   |
| Stuttgart          | 2         | 0.41%   |
| St Petersburg      | 2         | 0.41%   |
| San Miguel         | 2         | 0.41%   |
| San Jose           | 2         | 0.41%   |
| San Francisco      | 2         | 0.41%   |
| San Antonio        | 2         | 0.41%   |
| Queens             | 2         | 0.41%   |
| Nuremberg          | 2         | 0.41%   |
| Niter??i           | 2         | 0.41%   |
| New York           | 2         | 0.41%   |
| Nagoya             | 2         | 0.41%   |
| M??nster           | 2         | 0.41%   |
| Munich             | 2         | 0.41%   |
| Mumbai             | 2         | 0.41%   |
| Milan              | 2         | 0.41%   |
| Maring??           | 2         | 0.41%   |
| Los Angeles        | 2         | 0.41%   |
| Kyiv               | 2         | 0.41%   |
| Kassel             | 2         | 0.41%   |
| Istanbul           | 2         | 0.41%   |
| Gurgaon            | 2         | 0.41%   |
| Frankfurt am Main  | 2         | 0.41%   |
| Dresden            | 2         | 0.41%   |
| Dnipro             | 2         | 0.41%   |
| Dallas             | 2         | 0.41%   |
| Cologne            | 2         | 0.41%   |
| Burzaco            | 2         | 0.41%   |
| Belo Horizonte     | 2         | 0.41%   |
| Bamberg            | 2         | 0.41%   |
| Austin             | 2         | 0.41%   |
| Zambr??w           | 1         | 0.21%   |
| Zabrze             | 1         | 0.21%   |
| Yuma               | 1         | 0.21%   |
| Yangon             | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 134       | 187     | 18.79%  |
| WDC                       | 99        | 144     | 13.88%  |
| Seagate                   | 96        | 140     | 13.46%  |
| Toshiba                   | 50        | 54      | 7.01%   |
| SanDisk                   | 42        | 53      | 5.89%   |
| Unknown                   | 34        | 40      | 4.77%   |
| Kingston                  | 33        | 43      | 4.63%   |
| Intel                     | 21        | 36      | 2.95%   |
| Hitachi                   | 20        | 27      | 2.81%   |
| Crucial                   | 19        | 22      | 2.66%   |
| SK hynix                  | 16        | 18      | 2.24%   |
| Phison                    | 12        | 17      | 1.68%   |
| HGST                      | 11        | 15      | 1.54%   |
| A-DATA Technology         | 11        | 15      | 1.54%   |
| Apple                     | 10        | 12      | 1.4%    |
| China                     | 9         | 11      | 1.26%   |
| SPCC                      | 7         | 9       | 0.98%   |
| PNY                       | 7         | 9       | 0.98%   |
| Micron Technology         | 7         | 10      | 0.98%   |
| Patriot                   | 4         | 6       | 0.56%   |
| JMicron Technology        | 4         | 5       | 0.56%   |
| OCZ                       | 3         | 6       | 0.42%   |
| Micron/Crucial Technology | 3         | 3       | 0.42%   |
| Maxtor                    | 3         | 6       | 0.42%   |
| LITEON                    | 3         | 3       | 0.42%   |
| KIOXIA                    | 3         | 3       | 0.42%   |
| Transcend                 | 2         | 2       | 0.28%   |
| SABRENT                   | 2         | 3       | 0.28%   |
| Netac                     | 2         | 2       | 0.28%   |
| Lenovo                    | 2         | 2       | 0.28%   |
| LaCie                     | 2         | 2       | 0.28%   |
| Intenso                   | 2         | 3       | 0.28%   |
| HS-SSD-C100               | 2         | 2       | 0.28%   |
| Gigabyte Technology       | 2         | 2       | 0.28%   |
| Apacer                    | 2         | 2       | 0.28%   |
| AMD                       | 2         | 17      | 0.28%   |
| Zheino                    | 1         | 1       | 0.14%   |
| XrayDisk                  | 1         | 1       | 0.14%   |
| Vaseky                    | 1         | 1       | 0.14%   |
| USB30                     | 1         | 1       | 0.14%   |
| USB3.0                    | 1         | 1       | 0.14%   |
| Union Memory              | 1         | 1       | 0.14%   |
| TO Exter                  | 1         | 1       | 0.14%   |
| Teclast                   | 1         | 1       | 0.14%   |
| TDAS                      | 1         | 3       | 0.14%   |
| Silicon Motion            | 1         | 1       | 0.14%   |
| Realtek Semiconductor     | 1         | 2       | 0.14%   |
| Plextor                   | 1         | 1       | 0.14%   |
| Phison Electronics        | 1         | 1       | 0.14%   |
| OWC                       | 1         | 1       | 0.14%   |
| MDT                       | 1         | 1       | 0.14%   |
| LITEONIT                  | 1         | 1       | 0.14%   |
| LDLC                      | 1         | 1       | 0.14%   |
| KingSpec                  | 1         | 1       | 0.14%   |
| KingDian                  | 1         | 1       | 0.14%   |
| KimMiDi                   | 1         | 1       | 0.14%   |
| HP Phison                 | 1         | 1       | 0.14%   |
| Hewlett-Packard           | 1         | Unknown | 0.14%   |
| Goodram                   | 1         | 1       | 0.14%   |
| GALAX TA                  | 1         | 1       | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 9         | 1.13%   |
| Samsung NVMe SSD Drive 512GB           | 9         | 1.13%   |
| Unknown MMC Card  64GB                 | 8         | 1%      |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 8         | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 7         | 0.88%   |
| Samsung NVMe SSD Drive 1TB             | 7         | 0.88%   |
| Unknown MMC Card  32GB                 | 6         | 0.75%   |
| Seagate ST9500325AS 500GB              | 6         | 0.75%   |
| Samsung SSD 860 QVO 1TB                | 6         | 0.75%   |
| Samsung NVMe SSD Drive 256GB           | 6         | 0.75%   |
| Kingston SA400S37480G 480GB SSD        | 6         | 0.75%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB               | 5         | 0.63%   |
| Toshiba MQ04ABF100 1TB                 | 5         | 0.63%   |
| Toshiba MQ01ABD100 1TB                 | 5         | 0.63%   |
| SK hynix NVMe SSD Drive 256GB          | 5         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB        | 5         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 5         | 0.63%   |
| SanDisk SDSSDA240G 240GB               | 5         | 0.63%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.63%   |
| WDC WD5000AAKS-00UU3A0 500GB           | 4         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB            | 4         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB        | 4         | 0.5%    |
| SanDisk SDSSDA120G 120GB               | 4         | 0.5%    |
| SanDisk NVMe SSD Drive 512GB           | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB         | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB           | 4         | 0.5%    |
| Samsung SSD 860 EVO M.2 250GB          | 4         | 0.5%    |
| Samsung SSD 860 EVO 250GB              | 4         | 0.5%    |
| Samsung SSD 850 EVO 250GB              | 4         | 0.5%    |
| Samsung SSD 750 EVO 250GB              | 4         | 0.5%    |
| Samsung NVMe SSD Drive 2TB             | 4         | 0.5%    |
| Samsung NVMe SSD Drive 250GB           | 4         | 0.5%    |
| Intel NVMe SSD Drive 512GB             | 4         | 0.5%    |
| China SATA SSD 240GB                   | 4         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 3         | 0.38%   |
| WDC WD5000AAKX-001CA0 500GB            | 3         | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3         | 0.38%   |
| Unknown MMC Card  16GB                 | 3         | 0.38%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.38%   |
| Seagate ST4000DM000-1F2168 4TB         | 3         | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB         | 3         | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB         | 3         | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB         | 3         | 0.38%   |
| Seagate ST1000LX015-1U7172 1TB         | 3         | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB         | 3         | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB         | 3         | 0.38%   |
| Samsung SSD 970 EVO 500GB              | 3         | 0.38%   |
| Samsung SSD 860 EVO M.2 500GB          | 3         | 0.38%   |
| Phison NVMe SSD Drive 1TB              | 3         | 0.38%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 3         | 0.38%   |
| JMicron Generic 2TB                    | 3         | 0.38%   |
| Intel NVMe SSD Drive 32GB              | 3         | 0.38%   |
| Hitachi HTS545050A7E380 500GB          | 3         | 0.38%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.25%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2         | 0.25%   |
| WDC WD7501AALS-00J7B1 752GB            | 2         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 137    | 35.5%   |
| WDC                 | 75        | 116    | 28.63%  |
| Toshiba             | 40        | 43     | 15.27%  |
| Hitachi             | 20        | 27     | 7.63%   |
| HGST                | 11        | 15     | 4.2%    |
| Samsung Electronics | 6         | 7      | 2.29%   |
| Unknown             | 4         | 4      | 1.53%   |
| Apple               | 4         | 4      | 1.53%   |
| Maxtor              | 3         | 6      | 1.15%   |
| JMicron Technology  | 3         | 3      | 1.15%   |
| USB3.0              | 1         | 1      | 0.38%   |
| Fujitsu             | 1         | 1      | 0.38%   |
| ASMT109x            | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 93     | 28.86%  |
| SanDisk             | 29        | 37     | 11.79%  |
| Kingston            | 29        | 37     | 11.79%  |
| Crucial             | 17        | 20     | 6.91%   |
| WDC                 | 15        | 15     | 6.1%    |
| China               | 9         | 11     | 3.66%   |
| A-DATA Technology   | 9         | 13     | 3.66%   |
| SPCC                | 6         | 8      | 2.44%   |
| PNY                 | 6         | 8      | 2.44%   |
| Intel               | 5         | 5      | 2.03%   |
| Apple               | 5         | 5      | 2.03%   |
| Patriot             | 4         | 6      | 1.63%   |
| Micron Technology   | 3         | 4      | 1.22%   |
| LITEON              | 3         | 3      | 1.22%   |
| SK hynix            | 2         | 2      | 0.81%   |
| Seagate             | 2         | 2      | 0.81%   |
| OCZ                 | 2         | 2      | 0.81%   |
| Netac               | 2         | 2      | 0.81%   |
| Intenso             | 2         | 3      | 0.81%   |
| Gigabyte Technology | 2         | 2      | 0.81%   |
| Apacer              | 2         | 2      | 0.81%   |
| AMD                 | 2         | 17     | 0.81%   |
| Zheino              | 1         | 1      | 0.41%   |
| Vaseky              | 1         | 1      | 0.41%   |
| USB30               | 1         | 1      | 0.41%   |
| Unknown             | 1         | 1      | 0.41%   |
| Union Memory        | 1         | 1      | 0.41%   |
| Transcend           | 1         | 1      | 0.41%   |
| Toshiba             | 1         | 1      | 0.41%   |
| TO Exter            | 1         | 1      | 0.41%   |
| Teclast             | 1         | 1      | 0.41%   |
| Plextor             | 1         | 1      | 0.41%   |
| OWC                 | 1         | 1      | 0.41%   |
| LITEONIT            | 1         | 1      | 0.41%   |
| KingSpec            | 1         | 1      | 0.41%   |
| KingDian            | 1         | 1      | 0.41%   |
| HP Phison           | 1         | 1      | 0.41%   |
| Goodram             | 1         | 1      | 0.41%   |
| Dogfish             | 1         | 1      | 0.41%   |
| BIWIN               | 1         | 1      | 0.41%   |
| Axiom               | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 365    | 34.69%  |
| SSD     | 208       | 316    | 32.65%  |
| NVMe    | 164       | 230    | 25.75%  |
| MMC     | 30        | 37     | 4.71%   |
| Unknown | 14        | 17     | 2.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 342       | 667    | 60.75%  |
| NVMe | 163       | 227    | 28.95%  |
| MMC  | 30        | 37     | 5.33%   |
| SAS  | 28        | 34     | 4.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 260       | 417    | 58.17%  |
| 0.51-1.0   | 132       | 181    | 29.53%  |
| 1.01-2.0   | 32        | 52     | 7.16%   |
| 3.01-4.0   | 14        | 21     | 3.13%   |
| 4.01-10.0  | 6         | 7      | 1.34%   |
| 2.01-3.0   | 3         | 3      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 148       | 29.96%  |
| 251-500        | 134       | 27.13%  |
| 501-1000       | 76        | 15.38%  |
| 51-100         | 34        | 6.88%   |
| 1001-2000      | 32        | 6.48%   |
| 21-50          | 20        | 4.05%   |
| More than 3000 | 17        | 3.44%   |
| 1-20           | 15        | 3.04%   |
| 2001-3000      | 11        | 2.23%   |
| Unknown        | 7         | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 167       | 33%     |
| 21-50          | 93        | 18.38%  |
| 101-250        | 89        | 17.59%  |
| 51-100         | 63        | 12.45%  |
| 251-500        | 42        | 8.3%    |
| 501-1000       | 22        | 4.35%   |
| 1001-2000      | 15        | 2.96%   |
| Unknown        | 7         | 1.38%   |
| More than 3000 | 6         | 1.19%   |
| 2001-3000      | 2         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 7.14%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 2      | 4.76%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 4.76%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 4.76%   |
| WDC WD6400BPVT-60HXZT3 640GB        | 1         | 1      | 2.38%   |
| WDC WD6000HLHX-01JJPV0 600GB        | 1         | 1      | 2.38%   |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 1      | 2.38%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 1      | 2.38%   |
| WDC WD4003FZEX-00Z4SA0 4TB          | 1         | 1      | 2.38%   |
| WDC WD2500AAJS-60M0A0 250GB         | 1         | 1      | 2.38%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 2.38%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 2.38%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 2.38%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 2.38%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 2.38%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 2.38%   |
| Seagate ST5000DM000-1FK178 5TB      | 1         | 1      | 2.38%   |
| Seagate ST3500320AS 500GB           | 1         | 1      | 2.38%   |
| Seagate ST3320620AS 320GB           | 1         | 1      | 2.38%   |
| Seagate ST3160815AS 160GB           | 1         | 1      | 2.38%   |
| Seagate ST1000DX001-1NS162 1TB      | 1         | 1      | 2.38%   |
| Seagate ST1000DM003-1SB102 1TB      | 1         | 1      | 2.38%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 2.38%   |
| Patriot Pyro m3 240GB SSD           | 1         | 1      | 2.38%   |
| Maxtor STM3250310AS 250GB           | 1         | 1      | 2.38%   |
| Maxtor 6B200M0 208GB                | 1         | 2      | 2.38%   |
| Kingston SNS4151S316G 16GB SSD      | 1         | 1      | 2.38%   |
| HP Phison PSSBN032GA27MC1 32GB      | 1         | 1      | 2.38%   |
| Hitachi HTS545025B9SA02 250GB       | 1         | 1      | 2.38%   |
| Hitachi HDS721032CLA362 320GB       | 1         | 1      | 2.38%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 2.38%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 2.38%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 15        | 15     | 35.71%  |
| WDC       | 10        | 11     | 23.81%  |
| Toshiba   | 6         | 6      | 14.29%  |
| Maxtor    | 2         | 3      | 4.76%   |
| Hitachi   | 2         | 2      | 4.76%   |
| HGST      | 2         | 3      | 4.76%   |
| PNY       | 1         | 1      | 2.38%   |
| Patriot   | 1         | 1      | 2.38%   |
| Kingston  | 1         | 1      | 2.38%   |
| HP Phison | 1         | 1      | 2.38%   |
| Crucial   | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 15     | 40.54%  |
| WDC     | 10        | 11     | 27.03%  |
| Toshiba | 6         | 6      | 16.22%  |
| Maxtor  | 2         | 3      | 5.41%   |
| Hitachi | 2         | 2      | 5.41%   |
| HGST    | 2         | 3      | 5.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 40     | 86.49%  |
| SSD  | 4         | 4      | 10.81%  |
| NVMe | 1         | 1      | 2.7%    |

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
| Detected | 302       | 633    | 58.3%   |
| Works    | 179       | 287    | 34.56%  |
| Malfunc  | 37        | 45     | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 333       | 56.63%  |
| Samsung Electronics           | 70        | 11.9%   |
| AMD                           | 67        | 11.39%  |
| SanDisk                       | 23        | 3.91%   |
| Phison Electronics            | 14        | 2.38%   |
| SK hynix                      | 12        | 2.04%   |
| Marvell Technology Group      | 9         | 1.53%   |
| Toshiba America Info Systems  | 8         | 1.36%   |
| JMicron Technology            | 6         | 1.02%   |
| Nvidia                        | 5         | 0.85%   |
| Micron/Crucial Technology     | 5         | 0.85%   |
| Kingston Technology Company   | 5         | 0.85%   |
| ASMedia Technology            | 5         | 0.85%   |
| Micron Technology             | 4         | 0.68%   |
| KIOXIA                        | 4         | 0.68%   |
| Silicon Motion                | 3         | 0.51%   |
| ADATA Technology              | 3         | 0.51%   |
| Realtek Semiconductor         | 2         | 0.34%   |
| Lenovo                        | 2         | 0.34%   |
| Unknown                       | 1         | 0.17%   |
| Union Memory (Shenzhen)       | 1         | 0.17%   |
| Silicon Image                 | 1         | 0.17%   |
| Shenzhen Longsys Electronics  | 1         | 0.17%   |
| OCZ Technology Group          | 1         | 0.17%   |
| Integrated Technology Express | 1         | 0.17%   |
| Apple                         | 1         | 0.17%   |
| Adaptec                       | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 49        | 7.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 42        | 6.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 33        | 4.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14        | 2.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 13        | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 1.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10        | 1.5%    |
| Intel SATA Controller [RAID mode]                                                | 9         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                           | 8         | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 1.2%    |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.05%   |
| Phison E12 NVMe Controller                                                       | 7         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.05%   |
| Intel SSD 660P Series                                                            | 6         | 0.9%    |
| Intel Non-Volatile memory controller                                             | 6         | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 0.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.75%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.6%    |
| Micron Non-Volatile memory controller                                            | 4         | 0.6%    |
| KIOXIA Non-Volatile memory controller                                            | 4         | 0.6%    |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 4         | 0.6%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                     | 4         | 0.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.45%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.45%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.45%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.45%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 3         | 0.45%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 3         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 343       | 57.74%  |
| NVMe | 166       | 27.95%  |
| IDE  | 50        | 8.42%   |
| RAID | 33        | 5.56%   |
| SAS  | 2         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 392       | 82.01%  |
| AMD    | 82        | 17.15%  |
| ARM    | 4         | 0.84%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 2.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.04%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.04%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.84%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.84%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.84%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 3         | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.63%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.63%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.63%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 3         | 0.63%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.63%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.63%   |
| ARM Processor                                 | 3         | 0.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.63%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 0.63%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.63%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 2         | 0.42%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.42%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 2         | 0.42%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.42%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.42%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.42%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.42%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.42%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.42%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.42%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.42%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.42%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.42%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.42%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 149       | 31.11%  |
| Intel Core i5           | 103       | 21.5%   |
| Intel Core i3           | 29        | 6.05%   |
| AMD Ryzen 5             | 25        | 5.22%   |
| Other                   | 24        | 5.01%   |
| Intel Core 2 Duo        | 19        | 3.97%   |
| AMD Ryzen 7             | 19        | 3.97%   |
| Intel Celeron           | 16        | 3.34%   |
| Intel Xeon              | 11        | 2.3%    |
| Intel Pentium           | 11        | 2.3%    |
| Intel Atom              | 9         | 1.88%   |
| Intel Core i9           | 5         | 1.04%   |
| Intel Core 2            | 5         | 1.04%   |
| Intel Pentium Dual      | 4         | 0.84%   |
| AMD Ryzen 9             | 4         | 0.84%   |
| AMD Ryzen 3             | 4         | 0.84%   |
| Intel Pentium Silver    | 3         | 0.63%   |
| Intel Genuine           | 3         | 0.63%   |
| AMD FX                  | 3         | 0.63%   |
| AMD E                   | 3         | 0.63%   |
| AMD A8                  | 3         | 0.63%   |
| AMD A6                  | 3         | 0.63%   |
| Intel Pentium Dual-Core | 2         | 0.42%   |
| Intel Core m3           | 2         | 0.42%   |
| AMD Turion 64 X2 Mobile | 2         | 0.42%   |
| AMD E1                  | 2         | 0.42%   |
| AMD A4                  | 2         | 0.42%   |
| AMD A10                 | 2         | 0.42%   |
| Intel Pentium 4         | 1         | 0.21%   |
| Intel Core m5           | 1         | 0.21%   |
| Intel Core 2 Quad       | 1         | 0.21%   |
| ARM BCM                 | 1         | 0.21%   |
| AMD Sempron             | 1         | 0.21%   |
| AMD Ryzen Threadripper  | 1         | 0.21%   |
| AMD Quad-Core           | 1         | 0.21%   |
| AMD Phenom II X6        | 1         | 0.21%   |
| AMD Phenom II X4        | 1         | 0.21%   |
| AMD Phenom II X2        | 1         | 0.21%   |
| AMD Embedded            | 1         | 0.21%   |
| AMD Athlon II           | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 204       | 42.68%  |
| 2      | 174       | 36.4%   |
| 6      | 46        | 9.62%   |
| 8      | 37        | 7.74%   |
| 1      | 7         | 1.46%   |
| 16     | 4         | 0.84%   |
| 12     | 2         | 0.42%   |
| 3      | 2         | 0.42%   |
| 24     | 1         | 0.21%   |
| 14     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 471       | 98.54%  |
| 2      | 7         | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 334       | 69.73%  |
| 1      | 145       | 30.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 472       | 98.74%  |
| 32-bit         | 3         | 0.63%   |
| Unknown        | 3         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 27.02%  |
| 0x206a7    | 32        | 6.45%   |
| 0x306a9    | 29        | 5.85%   |
| 0x806ec    | 22        | 4.44%   |
| 0x306c3    | 21        | 4.23%   |
| 0x906ea    | 16        | 3.23%   |
| 0x806ea    | 15        | 3.02%   |
| 0x806e9    | 13        | 2.62%   |
| 0x1067a    | 13        | 2.62%   |
| 0x40651    | 12        | 2.42%   |
| 0x806c1    | 11        | 2.22%   |
| 0x906e9    | 10        | 2.02%   |
| 0x406e3    | 9         | 1.81%   |
| 0x506e3    | 8         | 1.61%   |
| 0x306d4    | 8         | 1.61%   |
| 0x806eb    | 6         | 1.21%   |
| 0x08600103 | 6         | 1.21%   |
| 0x30678    | 5         | 1.01%   |
| 0x106e5    | 5         | 1.01%   |
| 0xa0652    | 4         | 0.81%   |
| 0x706e5    | 4         | 0.81%   |
| 0x6fd      | 4         | 0.81%   |
| 0x20655    | 4         | 0.81%   |
| 0x10676    | 4         | 0.81%   |
| 0x0a50000c | 4         | 0.81%   |
| 0x08701021 | 4         | 0.81%   |
| 0x08108109 | 4         | 0.81%   |
| 0x0810100b | 4         | 0.81%   |
| 0x0800820d | 4         | 0.81%   |
| 0xa0660    | 3         | 0.6%    |
| 0x906ed    | 3         | 0.6%    |
| 0x906ec    | 3         | 0.6%    |
| 0x706a1    | 3         | 0.6%    |
| 0x6f6      | 3         | 0.6%    |
| 0x6f2      | 3         | 0.6%    |
| 0x406c4    | 3         | 0.6%    |
| 0x406c3    | 3         | 0.6%    |
| 0x08600106 | 3         | 0.6%    |
| 0x08600104 | 3         | 0.6%    |
| 0x0600611a | 3         | 0.6%    |
| 0x05000119 | 3         | 0.6%    |
| 0xa0671    | 2         | 0.4%    |
| 0x706a8    | 2         | 0.4%    |
| 0x206d7    | 2         | 0.4%    |
| 0x20652    | 2         | 0.4%    |
| 0x08701013 | 2         | 0.4%    |
| 0x0700010f | 2         | 0.4%    |
| 0x06001119 | 2         | 0.4%    |
| 0x06000852 | 2         | 0.4%    |
| 0x010000c8 | 2         | 0.4%    |
| 0xf34      | 1         | 0.2%    |
| 0xa0655    | 1         | 0.2%    |
| 0x906eb    | 1         | 0.2%    |
| 0x906c0    | 1         | 0.2%    |
| 0x906a3    | 1         | 0.2%    |
| 0x806d1    | 1         | 0.2%    |
| 0x6fb      | 1         | 0.2%    |
| 0x6fa      | 1         | 0.2%    |
| 0x506c9    | 1         | 0.2%    |
| 0x406f1    | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 123       | 25.73%  |
| SandyBridge      | 40        | 8.37%   |
| IvyBridge        | 40        | 8.37%   |
| Haswell          | 39        | 8.16%   |
| Zen 2            | 28        | 5.86%   |
| Penryn           | 21        | 4.39%   |
| Skylake          | 20        | 4.18%   |
| Silvermont       | 15        | 3.14%   |
| TigerLake        | 14        | 2.93%   |
| Core             | 14        | 2.93%   |
| CometLake        | 12        | 2.51%   |
| Broadwell        | 12        | 2.51%   |
| Zen+             | 11        | 2.3%    |
| Westmere         | 10        | 2.09%   |
| IceLake          | 9         | 1.88%   |
| Zen              | 8         | 1.67%   |
| Goldmont plus    | 8         | 1.67%   |
| Nehalem          | 7         | 1.46%   |
| Excavator        | 6         | 1.26%   |
| Unknown          | 6         | 1.26%   |
| Zen 3            | 5         | 1.05%   |
| Piledriver       | 5         | 1.05%   |
| K10              | 5         | 1.05%   |
| Puma             | 3         | 0.63%   |
| Jaguar           | 3         | 0.63%   |
| Bobcat           | 3         | 0.63%   |
| K8 Hammer        | 2         | 0.42%   |
| Bonnell          | 2         | 0.42%   |
| Tremont          | 1         | 0.21%   |
| Steamroller      | 1         | 0.21%   |
| P6               | 1         | 0.21%   |
| NetBurst         | 1         | 0.21%   |
| K10 Llano        | 1         | 0.21%   |
| Goldmont         | 1         | 0.21%   |
| Alderlake Hybrid | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 311       | 53.62%  |
| Nvidia                     | 158       | 27.24%  |
| AMD                        | 109       | 18.79%  |
| Matrox Electronics Systems | 1         | 0.17%   |
| ASPEED Technology          | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 5.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 3.73%   |
| Intel UHD Graphics 620                                                                   | 22        | 3.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.73%   |
| Intel HD Graphics 620                                                                    | 14        | 2.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.37%   |
| AMD Renoir                                                                               | 14        | 2.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 2.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 1.53%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.36%   |
| Intel HD Graphics 630                                                                    | 8         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.85%   |
| Intel Comet Lake UHD Graphics                                                            | 5         | 0.85%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5         | 0.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4         | 0.68%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.68%   |
| Intel HD Graphics 530                                                                    | 4         | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.68%   |
| AMD Cezanne                                                                              | 4         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.51%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.51%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.51%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.51%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.34%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2         | 0.34%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.34%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.34%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 222       | 45.87%  |
| 1 x AMD         | 78        | 16.12%  |
| 1 x Nvidia      | 77        | 15.91%  |
| Intel + Nvidia  | 69        | 14.26%  |
| Intel + AMD     | 17        | 3.51%   |
| AMD + Nvidia    | 10        | 2.07%   |
| Other           | 4         | 0.83%   |
| 2 x AMD         | 3         | 0.62%   |
| 2 x Nvidia      | 1         | 0.21%   |
| 2 x Intel       | 1         | 0.21%   |
| Nvidia + Matrox | 1         | 0.21%   |
| 1 x ASPEED      | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 354       | 72.54%  |
| Proprietary | 120       | 24.59%  |
| Unknown     | 14        | 2.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 301       | 61.05%  |
| 1.01-2.0   | 52        | 10.55%  |
| 3.01-4.0   | 32        | 6.49%   |
| 0.01-0.5   | 31        | 6.29%   |
| 7.01-8.0   | 26        | 5.27%   |
| 0.51-1.0   | 25        | 5.07%   |
| 5.01-6.0   | 23        | 4.67%   |
| 2.01-3.0   | 2         | 0.41%   |
| 8.01-16.0  | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 70        | 12.54%  |
| AU Optronics            | 68        | 12.19%  |
| Samsung Electronics     | 65        | 11.65%  |
| BOE                     | 44        | 7.89%   |
| LG Display              | 42        | 7.53%   |
| Dell                    | 38        | 6.81%   |
| Goldstar                | 21        | 3.76%   |
| Hewlett-Packard         | 20        | 3.58%   |
| Apple                   | 17        | 3.05%   |
| Acer                    | 15        | 2.69%   |
| AOC                     | 12        | 2.15%   |
| Ancor Communications    | 12        | 2.15%   |
| BenQ                    | 10        | 1.79%   |
| Sharp                   | 9         | 1.61%   |
| Philips                 | 9         | 1.61%   |
| Chi Mei Optoelectronics | 9         | 1.61%   |
| Lenovo                  | 8         | 1.43%   |
| Unknown                 | 7         | 1.25%   |
| PANDA                   | 6         | 1.08%   |
| ASUSTek Computer        | 6         | 1.08%   |
| LG Electronics          | 4         | 0.72%   |
| InfoVision              | 4         | 0.72%   |
| Iiyama                  | 4         | 0.72%   |
| Idek Iiyama             | 4         | 0.72%   |
| LGD                     | 3         | 0.54%   |
| Fujitsu Siemens         | 3         | 0.54%   |
| Eizo                    | 3         | 0.54%   |
| ViewSonic               | 2         | 0.36%   |
| Unknown (AAA)           | 2         | 0.36%   |
| Sony                    | 2         | 0.36%   |
| Sceptre Tech            | 2         | 0.36%   |
| MStar                   | 2         | 0.36%   |
| Medion                  | 2         | 0.36%   |
| AGO                     | 2         | 0.36%   |
| Vizio                   | 1         | 0.18%   |
| VIZ                     | 1         | 0.18%   |
| Vestel Elektronik       | 1         | 0.18%   |
| Vestel                  | 1         | 0.18%   |
| UPD                     | 1         | 0.18%   |
| Unknown (XXX)           | 1         | 0.18%   |
| Sun                     | 1         | 0.18%   |
| SANYO                   | 1         | 0.18%   |
| RTK                     | 1         | 0.18%   |
| Pioneer Electronic      | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| Orion                   | 1         | 0.18%   |
| ONN                     | 1         | 0.18%   |
| NEC Computers           | 1         | 0.18%   |
| MPI                     | 1         | 0.18%   |
| Microstep               | 1         | 0.18%   |
| LG Philips              | 1         | 0.18%   |
| LaCie                   | 1         | 0.18%   |
| KTC                     | 1         | 0.18%   |
| JDI                     | 1         | 0.18%   |
| ITE                     | 1         | 0.18%   |
| Insignia                | 1         | 0.18%   |
| InnoLux Display         | 1         | 0.18%   |
| Hyundai ImageQuest      | 1         | 0.18%   |
| Huion                   | 1         | 0.18%   |
| HCD                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch        | 5         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch        | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 0.51%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch          | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.51%   |
| Unknown LCD Monitor SAMSUNG                                             | 2         | 0.34%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 0.34%   |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2         | 0.34%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2         | 0.34%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 2         | 0.34%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2         | 0.34%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2         | 0.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 2         | 0.34%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.34%   |
| LGD LCD Monitor 1920x1080                                               | 2         | 0.34%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 2         | 0.34%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 2         | 0.34%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 0.34%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch             | 2         | 0.34%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch              | 2         | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2         | 0.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 0.34%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                       | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch        | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 2         | 0.34%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 2         | 0.34%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                       | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch           | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch          | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch           | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.34%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch           | 2         | 0.34%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch   | 2         | 0.34%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch   | 2         | 0.34%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                       | 1         | 0.17%   |
| Vizio D50u-D1 VIZ1011 3840x2160 941x529mm 42.5-inch                     | 1         | 0.17%   |
| VIZ LCD Monitor M50-C1 3840x2160                                        | 1         | 0.17%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch           | 1         | 0.17%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch            | 1         | 0.17%   |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                 | 1         | 0.17%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                           | 1         | 0.17%   |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                        | 1         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 233       | 43.8%   |
| 1366x768 (WXGA)    | 102       | 19.17%  |
| 3840x2160 (4K)     | 29        | 5.45%   |
| 2560x1440 (QHD)    | 20        | 3.76%   |
| 1600x900 (HD+)     | 16        | 3.01%   |
| 1280x1024 (SXGA)   | 15        | 2.82%   |
| Unknown            | 14        | 2.63%   |
| 1920x1200 (WUXGA)  | 13        | 2.44%   |
| 1280x800 (WXGA)    | 11        | 2.07%   |
| 1680x1050 (WSXGA+) | 10        | 1.88%   |
| 3440x1440          | 8         | 1.5%    |
| 2560x1080          | 8         | 1.5%    |
| 3840x1080          | 6         | 1.13%   |
| 1440x900 (WXGA+)   | 6         | 1.13%   |
| 3200x1800 (QHD+)   | 4         | 0.75%   |
| 2880x1800          | 4         | 0.75%   |
| 2560x1600          | 3         | 0.56%   |
| 3520x1080          | 2         | 0.38%   |
| 2160x1440          | 2         | 0.38%   |
| 1920x540           | 2         | 0.38%   |
| 1600x1200          | 2         | 0.38%   |
| 7680x2160          | 1         | 0.19%   |
| 5760x2160          | 1         | 0.19%   |
| 4480x1080          | 1         | 0.19%   |
| 3840x2400          | 1         | 0.19%   |
| 3840x1440          | 1         | 0.19%   |
| 3840x1200          | 1         | 0.19%   |
| 3840x1100          | 1         | 0.19%   |
| 3600x1080          | 1         | 0.19%   |
| 3000x2000          | 1         | 0.19%   |
| 2880x1920          | 1         | 0.19%   |
| 2646x768           | 1         | 0.19%   |
| 2560x1024          | 1         | 0.19%   |
| 2390x768           | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 2256x1504          | 1         | 0.19%   |
| 2048x1152          | 1         | 0.19%   |
| 1920x1280          | 1         | 0.19%   |
| 1400x1050          | 1         | 0.19%   |
| 1360x768           | 1         | 0.19%   |
| 1280x960           | 1         | 0.19%   |
| 1280x768           | 1         | 0.19%   |
| 1280x720 (HD)      | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 144       | 25.95%  |
| 13      | 71        | 12.79%  |
| Unknown | 49        | 8.83%   |
| 14      | 46        | 8.29%   |
| 24      | 41        | 7.39%   |
| 27      | 36        | 6.49%   |
| 23      | 33        | 5.95%   |
| 17      | 23        | 4.14%   |
| 21      | 20        | 3.6%    |
| 19      | 12        | 2.16%   |
| 34      | 11        | 1.98%   |
| 11      | 9         | 1.62%   |
| 12      | 8         | 1.44%   |
| 31      | 7         | 1.26%   |
| 54      | 5         | 0.9%    |
| 18      | 5         | 0.9%    |
| 22      | 4         | 0.72%   |
| 20      | 4         | 0.72%   |
| 84      | 3         | 0.54%   |
| 52      | 2         | 0.36%   |
| 48      | 2         | 0.36%   |
| 40      | 2         | 0.36%   |
| 32      | 2         | 0.36%   |
| 29      | 2         | 0.36%   |
| 28      | 2         | 0.36%   |
| 142     | 1         | 0.18%   |
| 72      | 1         | 0.18%   |
| 63      | 1         | 0.18%   |
| 46      | 1         | 0.18%   |
| 44      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 37      | 1         | 0.18%   |
| 26      | 1         | 0.18%   |
| 25      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |
| 10      | 1         | 0.18%   |
| 8       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 224       | 40.65%  |
| 501-600        | 102       | 18.51%  |
| 201-300        | 56        | 10.16%  |
| Unknown        | 49        | 8.89%   |
| 401-500        | 37        | 6.72%   |
| 351-400        | 31        | 5.63%   |
| 601-700        | 17        | 3.09%   |
| 701-800        | 13        | 2.36%   |
| 1001-1500      | 11        | 2%      |
| 1501-2000      | 4         | 0.73%   |
| 801-900        | 3         | 0.54%   |
| 901-1000       | 2         | 0.36%   |
| More than 2000 | 1         | 0.18%   |
| 101-200        | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 352       | 71.69%  |
| 16/10   | 49        | 9.98%   |
| Unknown | 44        | 8.96%   |
| 5/4     | 13        | 2.65%   |
| 21/9    | 13        | 2.65%   |
| 4/3     | 8         | 1.63%   |
| 3/2     | 7         | 1.43%   |
| 32/9    | 2         | 0.41%   |
| 6/5     | 1         | 0.2%    |
| 3.40    | 1         | 0.2%    |
| 1.00    | 1         | 0.2%    |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 142       | 25.87%  |
| 81-90          | 85        | 15.48%  |
| 201-250        | 71        | 12.93%  |
| Unknown        | 49        | 8.93%   |
| 301-350        | 36        | 6.56%   |
| 71-80          | 34        | 6.19%   |
| 351-500        | 22        | 4.01%   |
| 151-200        | 21        | 3.83%   |
| 251-300        | 20        | 3.64%   |
| 121-130        | 15        | 2.73%   |
| More than 1000 | 14        | 2.55%   |
| 51-60          | 10        | 1.82%   |
| 141-150        | 9         | 1.64%   |
| 501-1000       | 7         | 1.28%   |
| 61-70          | 5         | 0.91%   |
| 131-140        | 5         | 0.91%   |
| 91-100         | 2         | 0.36%   |
| 41-50          | 1         | 0.18%   |
| 1-40           | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 145       | 27.1%   |
| 121-160       | 138       | 25.79%  |
| 101-120       | 128       | 23.93%  |
| Unknown       | 49        | 9.16%   |
| 161-240       | 39        | 7.29%   |
| More than 240 | 21        | 3.93%   |
| 1-50          | 15        | 2.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 368       | 75.1%   |
| 2     | 94        | 19.18%  |
| 3     | 14        | 2.86%   |
| 0     | 13        | 2.65%   |
| 4     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 261       | 35.32%  |
| Realtek Semiconductor                 | 248       | 33.56%  |
| Qualcomm Atheros                      | 87        | 11.77%  |
| Broadcom                              | 47        | 6.36%   |
| Broadcom Limited                      | 14        | 1.89%   |
| Marvell Technology Group              | 8         | 1.08%   |
| Ralink Technology                     | 7         | 0.95%   |
| Ralink                                | 7         | 0.95%   |
| Nvidia                                | 5         | 0.68%   |
| MediaTek                              | 4         | 0.54%   |
| Hewlett-Packard                       | 4         | 0.54%   |
| ASIX Electronics                      | 4         | 0.54%   |
| Xiaomi                                | 3         | 0.41%   |
| Qualcomm Atheros Communications       | 3         | 0.41%   |
| Microsoft                             | 3         | 0.41%   |
| D-Link System                         | 3         | 0.41%   |
| Sierra Wireless                       | 2         | 0.27%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.27%   |
| Linksys                               | 2         | 0.27%   |
| Lenovo                                | 2         | 0.27%   |
| JMicron Technology                    | 2         | 0.27%   |
| Huawei Technologies                   | 2         | 0.27%   |
| Wacom                                 | 1         | 0.14%   |
| TP-Link                               | 1         | 0.14%   |
| Samsung Electronics                   | 1         | 0.14%   |
| Realtek                               | 1         | 0.14%   |
| Novatek Microelectronics              | 1         | 0.14%   |
| NetGear                               | 1         | 0.14%   |
| Luminary Micro                        | 1         | 0.14%   |
| Google                                | 1         | 0.14%   |
| Exar                                  | 1         | 0.14%   |
| Ericsson Business Mobile Networks     | 1         | 0.14%   |
| Edimax Technology                     | 1         | 0.14%   |
| DisplayLink                           | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| D-Link                                | 1         | 0.14%   |
| BUFFALO                               | 1         | 0.14%   |
| Belkin Components                     | 1         | 0.14%   |
| ASUSTek Computer                      | 1         | 0.14%   |
| Apple                                 | 1         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 159       | 18.4%   |
| Intel Wi-Fi 6 AX200                                               | 43        | 4.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 24        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 2.08%   |
| Intel Wireless-AC 9260                                            | 18        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.39%   |
| Intel Wireless 7265                                               | 12        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.16%   |
| Intel Wireless 8260                                               | 10        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.81%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.69%   |
| Intel Wireless 7260                                               | 6         | 0.69%   |
| Intel Wireless 3165                                               | 6         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.46%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.46%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.35%   |
| Realtek 802.11ac NIC                                              | 3         | 0.35%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.35%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.35%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.35%   |
| Intel WiFi Link 5100                                              | 3         | 0.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.35%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 213       | 51.08%  |
| Qualcomm Atheros                      | 68        | 16.31%  |
| Realtek Semiconductor                 | 51        | 12.23%  |
| Broadcom                              | 32        | 7.67%   |
| Broadcom Limited                      | 11        | 2.64%   |
| Ralink Technology                     | 7         | 1.68%   |
| Ralink                                | 7         | 1.68%   |
| MediaTek                              | 4         | 0.96%   |
| Qualcomm Atheros Communications       | 3         | 0.72%   |
| Microsoft                             | 3         | 0.72%   |
| Sierra Wireless                       | 2         | 0.48%   |
| Linksys                               | 2         | 0.48%   |
| D-Link System                         | 2         | 0.48%   |
| Wacom                                 | 1         | 0.24%   |
| TP-Link                               | 1         | 0.24%   |
| Realtek                               | 1         | 0.24%   |
| NetGear                               | 1         | 0.24%   |
| Marvell Technology Group              | 1         | 0.24%   |
| Hewlett-Packard                       | 1         | 0.24%   |
| Edimax Technology                     | 1         | 0.24%   |
| D-Link                                | 1         | 0.24%   |
| BUFFALO                               | 1         | 0.24%   |
| Belkin Components                     | 1         | 0.24%   |
| ASUSTek Computer                      | 1         | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 43        | 10.26%  |
| Intel Wireless 8265 / 8275                                     | 24        | 5.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 4.3%    |
| Intel Wireless-AC 9260                                         | 18        | 4.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 3.1%    |
| Intel Wireless 7265                                            | 12        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.39%   |
| Intel Wireless 8260                                            | 10        | 2.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.91%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.43%   |
| Intel Wireless 7260                                            | 6         | 1.43%   |
| Intel Wireless 3165                                            | 6         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.95%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 0.95%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.72%   |
| Realtek 802.11ac NIC                                           | 3         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 0.72%   |
| Intel WiFi Link 5100                                           | 3         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.72%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.48%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.48%   |
| Ralink RT5372 Wireless Adapter                                 | 2         | 0.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.48%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 0.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.48%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]              | 2         | 0.48%   |
| Intel Wireless 3160                                            | 2         | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.48%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 224       | 52.83%  |
| Intel                         | 116       | 27.36%  |
| Qualcomm Atheros              | 26        | 6.13%   |
| Broadcom                      | 24        | 5.66%   |
| Marvell Technology Group      | 7         | 1.65%   |
| Nvidia                        | 5         | 1.18%   |
| ASIX Electronics              | 4         | 0.94%   |
| Xiaomi                        | 3         | 0.71%   |
| Broadcom Limited              | 3         | 0.71%   |
| OnePlus Technology (Shenzhen) | 2         | 0.47%   |
| Lenovo                        | 2         | 0.47%   |
| JMicron Technology            | 2         | 0.47%   |
| Samsung Electronics           | 1         | 0.24%   |
| Hewlett-Packard               | 1         | 0.24%   |
| Google                        | 1         | 0.24%   |
| DisplayLink                   | 1         | 0.24%   |
| D-Link System                 | 1         | 0.24%   |
| Apple                         | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 159       | 36.47%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 30        | 6.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 6.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 22        | 5.05%   |
| Realtek RTL8125 2.5GbE Controller                                              | 12        | 2.75%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.83%   |
| Intel Ethernet Connection (7) I219-V                                           | 8         | 1.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.61%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.61%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 1.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.15%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.15%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 4         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.69%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.69%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.69%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.69%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.69%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.69%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 0.69%   |
| Intel 82566DM Gigabit Network Connection                                       | 3         | 0.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.46%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                                     | 2         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.46%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.46%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 2         | 0.46%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.23%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.23%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.23%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.23%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.23%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.23%   |
| Lenovo Thinkpad LAN                                                            | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 401       | 49.81%  |
| WiFi     | 395       | 49.07%  |
| Modem    | 9         | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 329       | 64.38%  |
| Ethernet | 182       | 35.62%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 279       | 58.25%  |
| 1     | 175       | 36.53%  |
| 0     | 13        | 2.71%   |
| 3     | 12        | 2.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 415       | 85.74%  |
| Yes  | 69        | 14.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 173       | 51.34%  |
| Qualcomm Atheros Communications | 29        | 8.61%   |
| Realtek Semiconductor           | 23        | 6.82%   |
| Cambridge Silicon Radio         | 21        | 6.23%   |
| Apple                           | 20        | 5.93%   |
| Broadcom                        | 16        | 4.75%   |
| Lite-On Technology              | 10        | 2.97%   |
| IMC Networks                    | 9         | 2.67%   |
| Foxconn / Hon Hai               | 8         | 2.37%   |
| Hewlett-Packard                 | 5         | 1.48%   |
| Realtek                         | 4         | 1.19%   |
| Dell                            | 4         | 1.19%   |
| Ralink                          | 3         | 0.89%   |
| ASUSTek Computer                | 3         | 0.89%   |
| Toshiba                         | 2         | 0.59%   |
| Belkin Components               | 2         | 0.59%   |
| Unknown                         | 1         | 0.3%    |
| MediaTek                        | 1         | 0.3%    |
| Marvell Semiconductor           | 1         | 0.3%    |
| Integrated System Solution      | 1         | 0.3%    |
| Foxconn International           | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 59        | 17.51%  |
| Intel AX200 Bluetooth                                                               | 41        | 12.17%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 6.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 6.23%   |
| Intel Bluetooth Device                                                              | 20        | 5.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 18        | 5.34%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4.15%   |
| Realtek Bluetooth Radio                                                             | 11        | 3.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 2.37%   |
| Apple Bluetooth Host Controller                                                     | 8         | 2.37%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.48%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.48%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.19%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.19%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.19%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.19%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.89%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.89%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.89%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.59%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.59%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.59%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.59%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 2         | 0.59%   |
| Unknown Bluetooth Device                                                            | 1         | 0.3%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.3%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.3%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.3%    |
| MediaTek Wireless_Device                                                            | 1         | 0.3%    |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.3%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.3%    |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.3%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.3%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.3%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.3%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.3%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.3%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.3%    |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.3%    |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.3%    |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.3%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.3%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 376       | 56.54%  |
| Nvidia                    | 110       | 16.54%  |
| AMD                       | 107       | 16.09%  |
| C-Media Electronics       | 9         | 1.35%   |
| Realtek Semiconductor     | 7         | 1.05%   |
| Logitech                  | 7         | 1.05%   |
| JMTek                     | 4         | 0.6%    |
| GN Netcom                 | 4         | 0.6%    |
| Creative Labs             | 4         | 0.6%    |
| Sennheiser Communications | 3         | 0.45%   |
| Kingston Technology       | 3         | 0.45%   |
| Creative Technology       | 3         | 0.45%   |
| Samson Technologies       | 2         | 0.3%    |
| Plantronics               | 2         | 0.3%    |
| Focusrite-Novation        | 2         | 0.3%    |
| Blue Microphones          | 2         | 0.3%    |
| XMOS                      | 1         | 0.15%   |
| Texas Instruments         | 1         | 0.15%   |
| SteelSeries ApS           | 1         | 0.15%   |
| Razer USA                 | 1         | 0.15%   |
| OPPO Electronics          | 1         | 0.15%   |
| No brand                  | 1         | 0.15%   |
| Native Instruments        | 1         | 0.15%   |
| Nam Tai E&E Products      | 1         | 0.15%   |
| Microsoft                 | 1         | 0.15%   |
| M-Audio                   | 1         | 0.15%   |
| Lenovo                    | 1         | 0.15%   |
| Hewlett-Packard           | 1         | 0.15%   |
| Giga-Byte Technology      | 1         | 0.15%   |
| Generalplus Technology    | 1         | 0.15%   |
| Conexant Systems          | 1         | 0.15%   |
| Cambridge Audio           | 1         | 0.15%   |
| C&T                       | 1         | 0.15%   |
| Bose                      | 1         | 0.15%   |
| Apple                     | 1         | 0.15%   |
| AKAI Professional M.I.    | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 51        | 6.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 3.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 24        | 3.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 2.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 14        | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 1.69%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 1.43%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 1.04%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 0.52%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.52%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.39%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.39%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.39%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.39%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.39%   |
| Nvidia Audio device                                                                               | 3         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 85        | 27.51%  |
| SK hynix            | 64        | 20.71%  |
| Kingston            | 30        | 9.71%   |
| Micron Technology   | 26        | 8.41%   |
| Unknown             | 22        | 7.12%   |
| Crucial             | 18        | 5.83%   |
| Corsair             | 10        | 3.24%   |
| Ramaxel Technology  | 9         | 2.91%   |
| G.Skill             | 6         | 1.94%   |
| A-DATA Technology   | 5         | 1.62%   |
| Unknown (ABCD)      | 4         | 1.29%   |
| Team                | 3         | 0.97%   |
| Teikon              | 2         | 0.65%   |
| Smart               | 2         | 0.65%   |
| PNY                 | 2         | 0.65%   |
| Nanya Technology    | 2         | 0.65%   |
| Goodram             | 2         | 0.65%   |
| Elpida              | 2         | 0.65%   |
| Unknown             | 2         | 0.65%   |
| Unknown (F301)      | 1         | 0.32%   |
| Unknown (0x873E)    | 1         | 0.32%   |
| Transcend           | 1         | 0.32%   |
| Timetec             | 1         | 0.32%   |
| Smart Brazil        | 1         | 0.32%   |
| Sesame              | 1         | 0.32%   |
| Patriot             | 1         | 0.32%   |
| Kingmax             | 1         | 0.32%   |
| Goldkey             | 1         | 0.32%   |
| Cors                | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| ASint Technology    | 1         | 0.32%   |
| Apacer              | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.53%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 5         | 1.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 1.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 1.53%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 1.22%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 4         | 1.22%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 3         | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.92%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.92%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.92%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 0.92%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 3         | 0.92%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 0.92%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 3         | 0.92%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                       | 2         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 2         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.61%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.61%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 2         | 0.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.61%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s            | 2         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.61%   |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s            | 2         | 0.61%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 0.61%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s               | 2         | 0.61%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s               | 2         | 0.61%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s              | 2         | 0.61%   |
| Unknown                                                             | 2         | 0.61%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 0.31%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.31%   |
| Unknown RAM Module 512MB DIMM 533MT/s                               | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.31%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM                                    | 1         | 0.31%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                              | 1         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                         | 1         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.31%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                         | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 123       | 46.24%  |
| DDR3    | 94        | 35.34%  |
| LPDDR3  | 13        | 4.89%   |
| LPDDR4  | 12        | 4.51%   |
| DDR2    | 10        | 3.76%   |
| SDRAM   | 7         | 2.63%   |
| Unknown | 5         | 1.88%   |
| DDR     | 2         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 168       | 64.37%  |
| DIMM         | 65        | 24.9%   |
| Row Of Chips | 23        | 8.81%   |
| FB-DIMM      | 2         | 0.77%   |
| RIMM         | 1         | 0.38%   |
| Chip         | 1         | 0.38%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 102       | 35.29%  |
| 4096  | 94        | 32.53%  |
| 16384 | 41        | 14.19%  |
| 2048  | 29        | 10.03%  |
| 32768 | 12        | 4.15%   |
| 1024  | 9         | 3.11%   |
| 512   | 2         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 67        | 22.79%  |
| 2667    | 62        | 21.09%  |
| 3200    | 31        | 10.54%  |
| 2400    | 26        | 8.84%   |
| 2133    | 19        | 6.46%   |
| 1333    | 18        | 6.12%   |
| 1334    | 10        | 3.4%    |
| 667     | 7         | 2.38%   |
| Unknown | 6         | 2.04%   |
| 3266    | 5         | 1.7%    |
| 1867    | 5         | 1.7%    |
| 4267    | 4         | 1.36%   |
| 1067    | 4         | 1.36%   |
| 800     | 4         | 1.36%   |
| 4199    | 3         | 1.02%   |
| 3600    | 3         | 1.02%   |
| 1066    | 3         | 1.02%   |
| 533     | 3         | 1.02%   |
| 4266    | 1         | 0.34%   |
| 3733    | 1         | 0.34%   |
| 3500    | 1         | 0.34%   |
| 3466    | 1         | 0.34%   |
| 3007    | 1         | 0.34%   |
| 3000    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |
| 2666    | 1         | 0.34%   |
| 2134    | 1         | 0.34%   |
| 2048    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1800    | 1         | 0.34%   |
| 1639    | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 4         | 36.36%  |
| Hewlett-Packard     | 3         | 27.27%  |
| Sharp               | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Fuji Xerox          | 1         | 9.09%   |
| Brother Industries  | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Sharp AL-2030                 | 1         | 9.09%   |
| Samsung M2020 Series          | 1         | 9.09%   |
| HP Deskjet 3050 J610 series   | 1         | 9.09%   |
| HP Deskjet 2540 series        | 1         | 9.09%   |
| HP DeskJet 2130 series        | 1         | 9.09%   |
| Fuji Xerox DocuPrint CM305 df | 1         | 9.09%   |
| Canon TR7500 series           | 1         | 9.09%   |
| Canon MF4010 series           | 1         | 9.09%   |
| Canon MF240 Series V4         | 1         | 9.09%   |
| Canon LiDE 400                | 1         | 9.09%   |
| Brother MFC-1810              | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 78        | 24%     |
| Acer                                   | 28        | 8.62%   |
| Sunplus Innovation Technology          | 27        | 8.31%   |
| Realtek Semiconductor                  | 26        | 8%      |
| IMC Networks                           | 26        | 8%      |
| Microdia                               | 24        | 7.38%   |
| Apple                                  | 17        | 5.23%   |
| Logitech                               | 16        | 4.92%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 4%      |
| Syntek                                 | 9         | 2.77%   |
| Suyin                                  | 8         | 2.46%   |
| Quanta                                 | 8         | 2.46%   |
| Silicon Motion                         | 6         | 1.85%   |
| Lite-On Technology                     | 5         | 1.54%   |
| Ricoh                                  | 3         | 0.92%   |
| Microsoft                              | 3         | 0.92%   |
| Generalplus Technology                 | 3         | 0.92%   |
| Alcor Micro                            | 3         | 0.92%   |
| Luxvisions Innotech Limited            | 2         | 0.62%   |
| LG Electronics                         | 2         | 0.62%   |
| ARC International                      | 2         | 0.62%   |
| Z-Star Microelectronics                | 1         | 0.31%   |
| Unknown                                | 1         | 0.31%   |
| Tobii Technology AB                    | 1         | 0.31%   |
| Sonix Technology                       | 1         | 0.31%   |
| Samsung Electronics                    | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| OPPO Electronics                       | 1         | 0.31%   |
| Omnivision                             | 1         | 0.31%   |
| Linux Foundation                       | 1         | 0.31%   |
| IPEVO                                  | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| icSpring                               | 1         | 0.31%   |
| Guillemot                              | 1         | 0.31%   |
| Cubeternet                             | 1         | 0.31%   |
| Creative Technology                    | 1         | 0.31%   |
| Unknown                                | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 14        | 4.28%   |
| Chicony HD Webcam                                                          | 12        | 3.67%   |
| Chicony Integrated Camera                                                  | 11        | 3.36%   |
| Microdia Integrated_Webcam_HD                                              | 9         | 2.75%   |
| IMC Networks Integrated Camera                                             | 9         | 2.75%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 2.45%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 2.14%   |
| Sunplus HD WebCam                                                          | 5         | 1.53%   |
| Chicony HP HD Camera                                                       | 5         | 1.53%   |
| Apple FaceTime HD Camera (Built-in)                                        | 5         | 1.53%   |
| Apple Built-in iSight                                                      | 5         | 1.53%   |
| Acer Integrated Camera                                                     | 5         | 1.53%   |
| Acer HD Webcam                                                             | 5         | 1.53%   |
| Acer BisonCam,NB Pro                                                       | 5         | 1.53%   |
| Syntek Integrated Camera                                                   | 4         | 1.22%   |
| Logitech HD Pro Webcam C920                                                | 4         | 1.22%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 4         | 1.22%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.22%   |
| Sunplus Asus Webcam                                                        | 3         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.92%   |
| Realtek Integrated Webcam                                                  | 3         | 0.92%   |
| Microdia Sonix USB 2.0 Camera                                              | 3         | 0.92%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 0.92%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 0.92%   |
| Acer BisonCam, NB Pro                                                      | 3         | 0.92%   |
| Syntek EasyCamera                                                          | 2         | 0.61%   |
| Suyin HP Truevision HD                                                     | 2         | 0.61%   |
| Sunplus USB Camera                                                         | 2         | 0.61%   |
| Sunplus Lenovo EasyCamera                                                  | 2         | 0.61%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.61%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.61%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.61%   |
| Sunplus HD User Facing                                                     | 2         | 0.61%   |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.61%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.61%   |
| Realtek HD WebCam                                                          | 2         | 0.61%   |
| Microsoft LifeCam HD-3000                                                  | 2         | 0.61%   |
| Logitech Webcam C270                                                       | 2         | 0.61%   |
| Logitech Webcam B500                                                       | 2         | 0.61%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.61%   |
| IMC Networks HD Camera                                                     | 2         | 0.61%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 0.61%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 2         | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.61%   |
| Chicony thinkpad t430s camera                                              | 2         | 0.61%   |
| Chicony HP Wide Vision FHD Camera                                          | 2         | 0.61%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.61%   |
| Chicony HP Integrated Webcam                                               | 2         | 0.61%   |
| Chicony HD WebCam (Asus N-series)                                          | 2         | 0.61%   |
| Chicony FJ Camera                                                          | 2         | 0.61%   |
| Chicony EasyCamera                                                         | 2         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.61%   |
| ARC International Camera                                                   | 2         | 0.61%   |
| Alcor Micro USB 2.0 Camera                                                 | 2         | 0.61%   |
| Acer USB HD Webcam                                                         | 2         | 0.61%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 0.61%   |
| Acer EasyCamera                                                            | 2         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 31        | 39.74%  |
| Validity Sensors           | 23        | 29.49%  |
| Shenzhen Goodix Technology | 10        | 12.82%  |
| LighTuning Technology      | 6         | 7.69%   |
| Elan Microelectronics      | 5         | 6.41%   |
| AuthenTec                  | 3         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 12        | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10.26%  |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 10.26%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 7.69%   |
| Elan ELAN:Fingerprint                                                      | 5         | 6.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 5.13%   |
| Synaptics WBDI Device                                                      | 4         | 5.13%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.56%   |
| Validity Sensors VFS491                                                    | 2         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.28%   |
| Synaptics  WBDI                                                            | 1         | 1.28%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.28%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.28%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.28%   |
| AuthenTec AES2810                                                          | 1         | 1.28%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.28%   |
| AuthenTec AES1600                                                          | 1         | 1.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 45%     |
| Upek        | 5         | 25%     |
| Alcor Micro | 4         | 20%     |
| Lenovo      | 2         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15%     |
| Broadcom 5880                                                                | 3         | 15%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10%     |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 328       | 67.77%  |
| 1     | 125       | 25.83%  |
| 2     | 26        | 5.37%   |
| 3     | 3         | 0.62%   |
| 4     | 2         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 77        | 42.31%  |
| Graphics card            | 34        | 18.68%  |
| Chipcard                 | 19        | 10.44%  |
| Net/wireless             | 14        | 7.69%   |
| Communication controller | 13        | 7.14%   |
| Multimedia controller    | 5         | 2.75%   |
| Camera                   | 5         | 2.75%   |
| Storage                  | 3         | 1.65%   |
| Card reader              | 3         | 1.65%   |
| Bluetooth                | 3         | 1.65%   |
| Unassigned class         | 2         | 1.1%    |
| Sound                    | 2         | 1.1%    |
| Net/ethernet             | 2         | 1.1%    |

