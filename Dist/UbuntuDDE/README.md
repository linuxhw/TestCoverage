UbuntuDDE - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for UbuntuDDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/UbuntuDDE/Desktop/README.md) and [notebooks](/Dist/UbuntuDDE/Notebook/README.md).

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

Total: 116

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| ECS           | Nettle2                     | Desktop     | [7de5975b89](https://linux-hardware.org/?probe=7de5975b89) | Mar 20, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| ECS           | Nettle2                     | Desktop     | [cd98e7180c](https://linux-hardware.org/?probe=cd98e7180c) | Feb 12, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Framework     | Laptop                      | Notebook    | [081416685c](https://linux-hardware.org/?probe=081416685c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Google        | Banon                       | Notebook    | [a6febddf28](https://linux-hardware.org/?probe=a6febddf28) | Jan 06, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [71958172cf](https://linux-hardware.org/?probe=71958172cf) | Oct 08, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [661937dcfa](https://linux-hardware.org/?probe=661937dcfa) | Sep 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [a950c391ee](https://linux-hardware.org/?probe=a950c391ee) | Sep 12, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| Acer          | F672CR R01-B1               | Desktop     | [652ed79c86](https://linux-hardware.org/?probe=652ed79c86) | May 29, 2021 |
| MSI           | GS60 2QE                    | Notebook    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| MSI           | GS60 2QE                    | Notebook    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| Acer          | F672CR R01-B1               | Desktop     | [bd8067c8cf](https://linux-hardware.org/?probe=bd8067c8cf) | May 16, 2021 |
| Acer          | Predator PH317-52           | Notebook    | [5737732bb0](https://linux-hardware.org/?probe=5737732bb0) | May 15, 2021 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [1c51e0899d](https://linux-hardware.org/?probe=1c51e0899d) | Apr 06, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [d03bb12703](https://linux-hardware.org/?probe=d03bb12703) | Apr 06, 2021 |
| MSI           | G41M-S01                    | Desktop     | [fae5d5a101](https://linux-hardware.org/?probe=fae5d5a101) | Mar 31, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| MSI           | G41M-P26                    | Desktop     | [2b503c1c1d](https://linux-hardware.org/?probe=2b503c1c1d) | Jan 07, 2021 |
| Dell          | Latitude E6320              | Notebook    | [8e7c6ced02](https://linux-hardware.org/?probe=8e7c6ced02) | Dec 15, 2020 |
| BESSTAR Te... | VB9                         | All in one  | [c6c030bd9f](https://linux-hardware.org/?probe=c6c030bd9f) | Nov 28, 2020 |
| BANGHO        | MZBSWAP-00                  | Desktop     | [c0b3c1bae1](https://linux-hardware.org/?probe=c0b3c1bae1) | Nov 13, 2020 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [51733fd6ab](https://linux-hardware.org/?probe=51733fd6ab) | Nov 02, 2020 |
| MSI           | Z87-G43                     | Desktop     | [055e733f90](https://linux-hardware.org/?probe=055e733f90) | Nov 01, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8f5f5aba10](https://linux-hardware.org/?probe=8f5f5aba10) | Oct 31, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e070ae2fd4](https://linux-hardware.org/?probe=e070ae2fd4) | Oct 19, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [5e81f45485](https://linux-hardware.org/?probe=5e81f45485) | Oct 09, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [83adab7085](https://linux-hardware.org/?probe=83adab7085) | Oct 08, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [ae5665efc4](https://linux-hardware.org/?probe=ae5665efc4) | Oct 02, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [a316ca39ef](https://linux-hardware.org/?probe=a316ca39ef) | Sep 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1865dce38e](https://linux-hardware.org/?probe=1865dce38e) | Sep 24, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [006c313ab9](https://linux-hardware.org/?probe=006c313ab9) | Sep 13, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [8abc37bdcc](https://linux-hardware.org/?probe=8abc37bdcc) | Sep 06, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [ae07f658e9](https://linux-hardware.org/?probe=ae07f658e9) | Sep 04, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5779a0397d](https://linux-hardware.org/?probe=5779a0397d) | Aug 26, 2020 |
| HP            | Pavilion dm4                | Notebook    | [7ab3fbd60d](https://linux-hardware.org/?probe=7ab3fbd60d) | Aug 26, 2020 |
| HP            | Pavilion dm4                | Notebook    | [f3f1ea6d44](https://linux-hardware.org/?probe=f3f1ea6d44) | Aug 26, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [b7c774660b](https://linux-hardware.org/?probe=b7c774660b) | Aug 23, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [08bdddfbb1](https://linux-hardware.org/?probe=08bdddfbb1) | Aug 23, 2020 |
| Dell          | System XPS L502X            | Notebook    | [caa5473285](https://linux-hardware.org/?probe=caa5473285) | Aug 13, 2020 |
| Lenovo        | G480 20150                  | Notebook    | [4531dd50a5](https://linux-hardware.org/?probe=4531dd50a5) | Aug 11, 2020 |
| Lenovo        | G480 20150                  | Notebook    | [8e51b2cb2d](https://linux-hardware.org/?probe=8e51b2cb2d) | Aug 11, 2020 |
| Dell          | System XPS L502X            | Notebook    | [019fc71c57](https://linux-hardware.org/?probe=019fc71c57) | Aug 05, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [4cb4390fa3](https://linux-hardware.org/?probe=4cb4390fa3) | Aug 01, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [e273444401](https://linux-hardware.org/?probe=e273444401) | Aug 01, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [19876e9920](https://linux-hardware.org/?probe=19876e9920) | Jul 25, 2020 |
| Dell          | G7 7588                     | Notebook    | [34805cf5b8](https://linux-hardware.org/?probe=34805cf5b8) | Jul 24, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | Desktop     | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| Toshiba       | Satellite S55t-B            | Notebook    | [01aa2bca69](https://linux-hardware.org/?probe=01aa2bca69) | Jun 28, 2020 |
| Toshiba       | Satellite S55t-B            | Notebook    | [71ae60ebc0](https://linux-hardware.org/?probe=71ae60ebc0) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [2a82822b1d](https://linux-hardware.org/?probe=2a82822b1d) | Jun 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f58b08659](https://linux-hardware.org/?probe=9f58b08659) | Jun 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [75682d8cbd](https://linux-hardware.org/?probe=75682d8cbd) | Jun 23, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ffccba3844](https://linux-hardware.org/?probe=ffccba3844) | Jun 23, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [f01a10328b](https://linux-hardware.org/?probe=f01a10328b) | Jun 17, 2020 |
| HP            | Presario CQ56               | Notebook    | [211a5c9ec1](https://linux-hardware.org/?probe=211a5c9ec1) | Jun 17, 2020 |
| Intel         | B75                         | Desktop     | [cbfecb01d1](https://linux-hardware.org/?probe=cbfecb01d1) | Jun 14, 2020 |
| Acer          | Aspire V5-471               | Notebook    | [346de9f5d8](https://linux-hardware.org/?probe=346de9f5d8) | Jun 14, 2020 |
| Unknown       | Unknown                     | Notebook    | [1da538b1cf](https://linux-hardware.org/?probe=1da538b1cf) | Jun 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [950be7ae19](https://linux-hardware.org/?probe=950be7ae19) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [77d17289e7](https://linux-hardware.org/?probe=77d17289e7) | May 31, 2020 |
| Dell          | 0H4VK7 A01                  | Desktop     | [0d7b561033](https://linux-hardware.org/?probe=0d7b561033) | May 24, 2020 |
| Dell          | 0H4VK7 A01                  | Desktop     | [6c8989e6c6](https://linux-hardware.org/?probe=6c8989e6c6) | May 24, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ea23c3bbdb](https://linux-hardware.org/?probe=ea23c3bbdb) | May 16, 2020 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [7ec29f824e](https://linux-hardware.org/?probe=7ec29f824e) | May 16, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [d55c3ee4b0](https://linux-hardware.org/?probe=d55c3ee4b0) | May 16, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [5a566d4992](https://linux-hardware.org/?probe=5a566d4992) | May 12, 2020 |
| HP            | 8433 11                     | Desktop     | [e302f75c67](https://linux-hardware.org/?probe=e302f75c67) | May 12, 2020 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [31b70f1160](https://linux-hardware.org/?probe=31b70f1160) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [2a1a979433](https://linux-hardware.org/?probe=2a1a979433) | May 11, 2020 |
| HP            | Pavilion 14                 | Notebook    | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [ad8e2069c8](https://linux-hardware.org/?probe=ad8e2069c8) | May 11, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [2a575bf9f0](https://linux-hardware.org/?probe=2a575bf9f0) | May 11, 2020 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [6c9138359f](https://linux-hardware.org/?probe=6c9138359f) | May 10, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [0b99805df1](https://linux-hardware.org/?probe=0b99805df1) | May 09, 2020 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [9bad08782f](https://linux-hardware.org/?probe=9bad08782f) | May 09, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [628255b107](https://linux-hardware.org/?probe=628255b107) | May 08, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6f59de9a48](https://linux-hardware.org/?probe=6f59de9a48) | May 08, 2020 |
| MSI           | G41M-P25                    | Desktop     | [e1592a090c](https://linux-hardware.org/?probe=e1592a090c) | May 08, 2020 |
| Dell          | Inspiron N7010              | Notebook    | [2568ca0355](https://linux-hardware.org/?probe=2568ca0355) | May 07, 2020 |
| HP            | 3397                        | Desktop     | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| Medion        | MS-7848                     | Desktop     | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [7580875f9d](https://linux-hardware.org/?probe=7580875f9d) | May 06, 2020 |
| HP            | 3397                        | Desktop     | [d5693de014](https://linux-hardware.org/?probe=d5693de014) | May 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [46c69aad2a](https://linux-hardware.org/?probe=46c69aad2a) | Apr 30, 2020 |
| Dell          | 0FM586                      | Desktop     | [0d813a7cc7](https://linux-hardware.org/?probe=0d813a7cc7) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [76eb877783](https://linux-hardware.org/?probe=76eb877783) | Apr 26, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [e5ec721a65](https://linux-hardware.org/?probe=e5ec721a65) | Apr 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| eMachines     | WMCP61M                     | Desktop     | [0d3017399b](https://linux-hardware.org/?probe=0d3017399b) | Apr 16, 2020 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [a877d12e85](https://linux-hardware.org/?probe=a877d12e85) | Apr 14, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [76bbb57b26](https://linux-hardware.org/?probe=76bbb57b26) | Apr 11, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [f38f6111a4](https://linux-hardware.org/?probe=f38f6111a4) | Apr 07, 2020 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [ea7a9aa4f0](https://linux-hardware.org/?probe=ea7a9aa4f0) | Mar 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ed6853b51d](https://linux-hardware.org/?probe=ed6853b51d) | Feb 28, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d33696bceb](https://linux-hardware.org/?probe=d33696bceb) | Nov 24, 2019 |
| Dell          | Latitude E5440              | Notebook    | [6c3cb81d00](https://linux-hardware.org/?probe=6c3cb81d00) | Aug 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| UbuntuDDE 20.04 | 63        | 73.26%  |
| UbuntuDDE 21.10 | 7         | 8.14%   |
| UbuntuDDE 21.04 | 6         | 6.98%   |
| UbuntuDDE 20.10 | 5         | 5.81%   |
| UbuntuDDE 18.04 | 4         | 4.65%   |
| UbuntuDDE 18.10 | 1         | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 86        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-29-generic    | 18        | 20.45%  |
| 5.4.0-42-generic    | 11        | 12.5%   |
| 5.4.0-21-generic    | 6         | 6.82%   |
| 5.4.0-37-generic    | 5         | 5.68%   |
| 5.4.0-48-generic    | 4         | 4.55%   |
| 5.8.0-33-generic    | 2         | 2.27%   |
| 5.4.0-52-generic    | 2         | 2.27%   |
| 5.4.0-39-generic    | 2         | 2.27%   |
| 5.3.0-40-generic    | 2         | 2.27%   |
| 5.11.0-17-generic   | 2         | 2.27%   |
| 5.8.0-53-generic    | 1         | 1.14%   |
| 5.8.0-50-generic    | 1         | 1.14%   |
| 5.8.0-48-generic    | 1         | 1.14%   |
| 5.8.0-41-generic    | 1         | 1.14%   |
| 5.8.0-23-generic    | 1         | 1.14%   |
| 5.6.0-1008-oem      | 1         | 1.14%   |
| 5.4.0-96-generic    | 1         | 1.14%   |
| 5.4.0-94-generic    | 1         | 1.14%   |
| 5.4.0-88-generic    | 1         | 1.14%   |
| 5.4.0-84-generic    | 1         | 1.14%   |
| 5.4.0-70-generic    | 1         | 1.14%   |
| 5.4.0-53-generic    | 1         | 1.14%   |
| 5.4.0-45-generic    | 1         | 1.14%   |
| 5.4.0-40-lowlatency | 1         | 1.14%   |
| 5.4.0-34-generic    | 1         | 1.14%   |
| 5.4.0-33-generic    | 1         | 1.14%   |
| 5.4.0-31-generic    | 1         | 1.14%   |
| 5.4.0-26-generic    | 1         | 1.14%   |
| 5.4.0-24-generic    | 1         | 1.14%   |
| 5.13.0-44-generic   | 1         | 1.14%   |
| 5.13.0-39-generic   | 1         | 1.14%   |
| 5.13.0-35-generic   | 1         | 1.14%   |
| 5.13.0-30-generic   | 1         | 1.14%   |
| 5.13.0-28-generic   | 1         | 1.14%   |
| 5.13.0-23-generic   | 1         | 1.14%   |
| 5.13.0-22-generic   | 1         | 1.14%   |
| 5.13.0-21-generic   | 1         | 1.14%   |
| 5.11.0-46-generic   | 1         | 1.14%   |
| 5.11.0-31-generic   | 1         | 1.14%   |
| 5.11.0-25-generic   | 1         | 1.14%   |
| 5.11.0-16-generic   | 1         | 1.14%   |
| 5.0.0-36-generic    | 1         | 1.14%   |
| 4.15.0-29-generic   | 1         | 1.14%   |
| 4.15.0-122-generic  | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 60        | 69.77%  |
| 5.8.0   | 7         | 8.14%   |
| 5.13.0  | 7         | 8.14%   |
| 5.11.0  | 6         | 6.98%   |
| 5.3.0   | 2         | 2.33%   |
| 4.15.0  | 2         | 2.33%   |
| 5.6.0   | 1         | 1.16%   |
| 5.0.0   | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 69.77%  |
| 5.8     | 7         | 8.14%   |
| 5.13    | 7         | 8.14%   |
| 5.11    | 6         | 6.98%   |
| 5.3     | 2         | 2.33%   |
| 4.15    | 2         | 2.33%   |
| 5.6     | 1         | 1.16%   |
| 5.0     | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 86        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 96.51%  |
| Wayland | 2         | 2.33%   |
| Tty     | 1         | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 65.52%  |
| LightDM | 12        | 13.79%  |
| GDM     | 11        | 12.64%  |
| TDM     | 6         | 6.9%    |
| SDDM    | 1         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 31        | 36.05%  |
| pt_BR   | 10        | 11.63%  |
| es_ES   | 5         | 5.81%   |
| C       | 5         | 5.81%   |
| fr_FR   | 4         | 4.65%   |
| en_GB   | 4         | 4.65%   |
| es_AR   | 3         | 3.49%   |
| de_DE   | 3         | 3.49%   |
| ru_RU   | 2         | 2.33%   |
| it_IT   | 2         | 2.33%   |
| uk_UA   | 1         | 1.16%   |
| th_TH   | 1         | 1.16%   |
| sr_RS   | 1         | 1.16%   |
| pl_PL   | 1         | 1.16%   |
| nl_NL   | 1         | 1.16%   |
| id_ID   | 1         | 1.16%   |
| fi_FI   | 1         | 1.16%   |
| es_MX   | 1         | 1.16%   |
| es_CR   | 1         | 1.16%   |
| es_CO   | 1         | 1.16%   |
| en_ZA   | 1         | 1.16%   |
| en_IN   | 1         | 1.16%   |
| en_CA   | 1         | 1.16%   |
| en_BW   | 1         | 1.16%   |
| en_AU   | 1         | 1.16%   |
| de_CH   | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 50.57%  |
| EFI  | 43        | 49.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 78        | 90.7%   |
| Overlay | 4         | 4.65%   |
| Zfs     | 1         | 1.16%   |
| Ext2    | 1         | 1.16%   |
| Btrfs   | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 70.93%  |
| GPT     | 21        | 24.42%  |
| MBR     | 4         | 4.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 84.88%  |
| Yes       | 13        | 15.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 50.57%  |
| Yes       | 43        | 49.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 17.44%  |
| ASUSTek Computer    | 15        | 17.44%  |
| Dell                | 12        | 13.95%  |
| MSI                 | 7         | 8.14%   |
| Lenovo              | 7         | 8.14%   |
| Gigabyte Technology | 5         | 5.81%   |
| Acer                | 5         | 5.81%   |
| Intel               | 4         | 4.65%   |
| Toshiba             | 2         | 2.33%   |
| Apple               | 2         | 2.33%   |
| Unknown             | 2         | 2.33%   |
| Medion              | 1         | 1.16%   |
| HUAWEI              | 1         | 1.16%   |
| Google              | 1         | 1.16%   |
| Fujitsu Siemens     | 1         | 1.16%   |
| Framework           | 1         | 1.16%   |
| eMachines           | 1         | 1.16%   |
| ECS                 | 1         | 1.16%   |
| BESSTAR Tech        | 1         | 1.16%   |
| BANGHO              | 1         | 1.16%   |
| ASRock              | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7592                                | 3         | 3.49%   |
| Unknown                                    | 2         | 2.33%   |
| Toshiba Satellite S55t-B                   | 1         | 1.16%   |
| Toshiba Satellite C55-B                    | 1         | 1.16%   |
| MSI MS-7B84                                | 1         | 1.16%   |
| MSI MS-7816                                | 1         | 1.16%   |
| MSI MS-7693                                | 1         | 1.16%   |
| MSI GS60 2QE                               | 1         | 1.16%   |
| Medion MS-7848                             | 1         | 1.16%   |
| Lenovo ThinkPad X200 Tablet 7449FWG        | 1         | 1.16%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJ0017US | 1         | 1.16%   |
| Lenovo ThinkPad T430 2349DS5               | 1         | 1.16%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300       | 1         | 1.16%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 1.16%   |
| Lenovo IdeaPad 510-15IKB 80SV              | 1         | 1.16%   |
| Lenovo G480 20150                          | 1         | 1.16%   |
| Intel NUC8i7BEH                            | 1         | 1.16%   |
| Intel DQ45CB AAE30148-207                  | 1         | 1.16%   |
| Intel D33217CK G76541-302                  | 1         | 1.16%   |
| Intel B75                                  | 1         | 1.16%   |
| HUAWEI MACH-WX9                            | 1         | 1.16%   |
| HP Spectre x360 Convertible 13-aw0xxx      | 1         | 1.16%   |
| HP ProBook 650 G3                          | 1         | 1.16%   |
| HP Presario CQ56                           | 1         | 1.16%   |
| HP Pavilion dv6                            | 1         | 1.16%   |
| HP Pavilion dm4                            | 1         | 1.16%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.16%   |
| HP Pavilion 14                             | 1         | 1.16%   |
| HP OMEN by Laptop 17-cb1xxx                | 1         | 1.16%   |
| HP Notebook                                | 1         | 1.16%   |
| HP Laptop 15-dy1xxx                        | 1         | 1.16%   |
| HP Laptop 15-da0xxx                        | 1         | 1.16%   |
| HP EliteBook 2540p                         | 1         | 1.16%   |
| HP Compaq Elite 8300 SFF                   | 1         | 1.16%   |
| HP Compaq Elite 8300 MT                    | 1         | 1.16%   |
| HP 250 G4 Notebook PC                      | 1         | 1.16%   |
| Google Banon                               | 1         | 1.16%   |
| Gigabyte GB-BXi7-5500                      | 1         | 1.16%   |
| Gigabyte GA-MA74GM-S2                      | 1         | 1.16%   |
| Gigabyte GA-970A-D3                        | 1         | 1.16%   |
| Gigabyte F2A55M-HD2                        | 1         | 1.16%   |
| Gigabyte B75M-D3H                          | 1         | 1.16%   |
| Fujitsu Siemens ESPRIMO P5730              | 1         | 1.16%   |
| Framework Laptop                           | 1         | 1.16%   |
| eMachines EL1333G                          | 1         | 1.16%   |
| ECS GL307AA-ABA a6123w                     | 1         | 1.16%   |
| Dell XPS 15 9570                           | 1         | 1.16%   |
| Dell System XPS L502X                      | 1         | 1.16%   |
| Dell PowerEdge T40                         | 1         | 1.16%   |
| Dell Latitude E6320                        | 1         | 1.16%   |
| Dell Latitude E5440                        | 1         | 1.16%   |
| Dell Inspiron N7010                        | 1         | 1.16%   |
| Dell Inspiron N4030                        | 1         | 1.16%   |
| Dell Inspiron 5447                         | 1         | 1.16%   |
| Dell Inspiron 530                          | 1         | 1.16%   |
| Dell Inspiron 3670                         | 1         | 1.16%   |
| Dell Inspiron 1525                         | 1         | 1.16%   |
| Dell G7 7588                               | 1         | 1.16%   |
| BESSTAR Tech U700                          | 1         | 1.16%   |
| BANGHO CUBIC                               | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 6         | 6.98%   |
| Lenovo ThinkPad         | 4         | 4.65%   |
| HP Pavilion             | 4         | 4.65%   |
| MSI MS-7592             | 3         | 3.49%   |
| Acer Aspire             | 3         | 3.49%   |
| Toshiba Satellite       | 2         | 2.33%   |
| Lenovo IdeaPad          | 2         | 2.33%   |
| HP Laptop               | 2         | 2.33%   |
| HP Compaq               | 2         | 2.33%   |
| Dell Latitude           | 2         | 2.33%   |
| ASUS VivoBook           | 2         | 2.33%   |
| ASUS PRIME              | 2         | 2.33%   |
| Unknown                 | 2         | 2.33%   |
| MSI MS-7B84             | 1         | 1.16%   |
| MSI MS-7816             | 1         | 1.16%   |
| MSI MS-7693             | 1         | 1.16%   |
| MSI GS60                | 1         | 1.16%   |
| Medion MS-7848          | 1         | 1.16%   |
| Lenovo G480             | 1         | 1.16%   |
| Intel NUC8i7BEH         | 1         | 1.16%   |
| Intel DQ45CB            | 1         | 1.16%   |
| Intel D33217CK          | 1         | 1.16%   |
| Intel B75               | 1         | 1.16%   |
| HUAWEI MACH-WX9         | 1         | 1.16%   |
| HP Spectre              | 1         | 1.16%   |
| HP ProBook              | 1         | 1.16%   |
| HP Presario             | 1         | 1.16%   |
| HP OMEN                 | 1         | 1.16%   |
| HP Notebook             | 1         | 1.16%   |
| HP EliteBook            | 1         | 1.16%   |
| HP 250                  | 1         | 1.16%   |
| Google Banon            | 1         | 1.16%   |
| Gigabyte GB-BXi7-5500   | 1         | 1.16%   |
| Gigabyte GA-MA74GM-S2   | 1         | 1.16%   |
| Gigabyte GA-970A-D3     | 1         | 1.16%   |
| Gigabyte F2A55M-HD2     | 1         | 1.16%   |
| Gigabyte B75M-D3H       | 1         | 1.16%   |
| Fujitsu Siemens ESPRIMO | 1         | 1.16%   |
| Framework Laptop        | 1         | 1.16%   |
| eMachines EL1333G       | 1         | 1.16%   |
| ECS GL307AA-ABA         | 1         | 1.16%   |
| Dell XPS                | 1         | 1.16%   |
| Dell System             | 1         | 1.16%   |
| Dell PowerEdge          | 1         | 1.16%   |
| Dell G7                 | 1         | 1.16%   |
| BESSTAR Tech U700       | 1         | 1.16%   |
| BANGHO CUBIC            | 1         | 1.16%   |
| ASUS X555QG             | 1         | 1.16%   |
| ASUS TP300LA            | 1         | 1.16%   |
| ASUS S551LN             | 1         | 1.16%   |
| ASUS P6X58D-E           | 1         | 1.16%   |
| ASUS P5KPL-AM           | 1         | 1.16%   |
| ASUS P5G41C-M           | 1         | 1.16%   |
| ASUS H61M-D             | 1         | 1.16%   |
| ASUS G550JK             | 1         | 1.16%   |
| ASUS D820MT             | 1         | 1.16%   |
| ASUS CROSSHAIR          | 1         | 1.16%   |
| ASUS A68HM-PLUS         | 1         | 1.16%   |
| ASRock X370             | 1         | 1.16%   |
| Apple iMac8             | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 12        | 13.95%  |
| 2014 | 9         | 10.47%  |
| 2010 | 8         | 9.3%    |
| 2008 | 8         | 9.3%    |
| 2012 | 7         | 8.14%   |
| 2011 | 7         | 8.14%   |
| 2020 | 6         | 6.98%   |
| 2019 | 6         | 6.98%   |
| 2013 | 6         | 6.98%   |
| 2016 | 4         | 4.65%   |
| 2021 | 3         | 3.49%   |
| 2015 | 3         | 3.49%   |
| 2009 | 3         | 3.49%   |
| 2017 | 2         | 2.33%   |
| 2007 | 2         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 50%     |
| Desktop     | 37        | 43.02%  |
| All in one  | 3         | 3.49%   |
| Tablet      | 1         | 1.16%   |
| Convertible | 1         | 1.16%   |
| Mini pc     | 1         | 1.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 91.95%  |
| Enabled  | 7         | 8.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 98.84%  |
| Yes  | 1         | 1.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 24.42%  |
| 3.01-4.0    | 21        | 24.42%  |
| 16.01-24.0  | 17        | 19.77%  |
| 8.01-16.0   | 15        | 17.44%  |
| 32.01-64.0  | 6         | 6.98%   |
| 2.01-3.0    | 3         | 3.49%   |
| 24.01-32.0  | 1         | 1.16%   |
| 64.01-256.0 | 1         | 1.16%   |
| 1.01-2.0    | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 32        | 36.78%  |
| 2.01-3.0  | 31        | 35.63%  |
| 4.01-8.0  | 11        | 12.64%  |
| 3.01-4.0  | 9         | 10.34%  |
| 8.01-16.0 | 2         | 2.3%    |
| 0.51-1.0  | 2         | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 58.14%  |
| 2      | 31        | 36.05%  |
| 3      | 5         | 5.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 56.98%  |
| Yes       | 37        | 43.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 87.21%  |
| No        | 11        | 12.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 76.74%  |
| No        | 20        | 23.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 61.63%  |
| No        | 33        | 38.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 18.39%  |
| Brazil       | 12        | 13.79%  |
| Germany      | 5         | 5.75%   |
| Argentina    | 5         | 5.75%   |
| France       | 4         | 4.6%    |
| Ukraine      | 3         | 3.45%   |
| UK           | 3         | 3.45%   |
| Spain        | 3         | 3.45%   |
| Portugal     | 3         | 3.45%   |
| India        | 3         | 3.45%   |
| Thailand     | 2         | 2.3%    |
| Poland       | 2         | 2.3%    |
| Mexico       | 2         | 2.3%    |
| Indonesia    | 2         | 2.3%    |
| Hungary      | 2         | 2.3%    |
| Costa Rica   | 2         | 2.3%    |
| Austria      | 2         | 2.3%    |
| Turkey       | 1         | 1.15%   |
| Sweden       | 1         | 1.15%   |
| South Africa | 1         | 1.15%   |
| Serbia       | 1         | 1.15%   |
| Netherlands  | 1         | 1.15%   |
| Luxembourg   | 1         | 1.15%   |
| Jamaica      | 1         | 1.15%   |
| Italy        | 1         | 1.15%   |
| Israel       | 1         | 1.15%   |
| Hong Kong    | 1         | 1.15%   |
| Finland      | 1         | 1.15%   |
| Colombia     | 1         | 1.15%   |
| Canada       | 1         | 1.15%   |
| Belgium      | 1         | 1.15%   |
| Australia    | 1         | 1.15%   |
| Algeria      | 1         | 1.15%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lisbon                      | 2         | 2.3%    |
| Budapest                    | 2         | 2.3%    |
| Zaporizhzhia                | 1         | 1.15%   |
| Yogyakarta                  | 1         | 1.15%   |
| Wolfheze                    | 1         | 1.15%   |
| Villahermosa                | 1         | 1.15%   |
| Vienna                      | 1         | 1.15%   |
| Tuen Mun                    | 1         | 1.15%   |
| Tomah                       | 1         | 1.15%   |
| Tiete                       | 1         | 1.15%   |
| S??ubice                    | 1         | 1.15%   |
| Surabaya                    | 1         | 1.15%   |
| Siquirres                   | 1         | 1.15%   |
| Seville                     | 1         | 1.15%   |
| Sao Paulo                   | 1         | 1.15%   |
| Sao Jose do Rio Preto       | 1         | 1.15%   |
| Sao Bernardo do Campo       | 1         | 1.15%   |
| Sankt P??lten               | 1         | 1.15%   |
| San Telmo                   | 1         | 1.15%   |
| San Nicol??s de los Arroyos | 1         | 1.15%   |
| Salvador                    | 1         | 1.15%   |
| Rosario                     | 1         | 1.15%   |
| Rome                        | 1         | 1.15%   |
| Rodgau                      | 1         | 1.15%   |
| Ratingen                    | 1         | 1.15%   |
| Quilmes                     | 1         | 1.15%   |
| Pontpierre                  | 1         | 1.15%   |
| Patna                       | 1         | 1.15%   |
| Paris                       | 1         | 1.15%   |
| Oakville                    | 1         | 1.15%   |
| Newburgh                    | 1         | 1.15%   |
| New York                    | 1         | 1.15%   |
| Nanterre                    | 1         | 1.15%   |
| Nakhon Pathom               | 1         | 1.15%   |
| Monterrey                   | 1         | 1.15%   |
| Monte Carmelo               | 1         | 1.15%   |
| Molesey                     | 1         | 1.15%   |
| Milan                       | 1         | 1.15%   |
| Midlothian                  | 1         | 1.15%   |
| Melbourne                   | 1         | 1.15%   |
| McCallsburg                 | 1         | 1.15%   |
| Manaus                      | 1         | 1.15%   |
| Maitland                    | 1         | 1.15%   |
| Madrid                      | 1         | 1.15%   |
| Lviv                        | 1         | 1.15%   |
| Luhansk                     | 1         | 1.15%   |
| La Louvi??re                | 1         | 1.15%   |
| Krefeld                     | 1         | 1.15%   |
| Krakow                      | 1         | 1.15%   |
| Kingston                    | 1         | 1.15%   |
| Johannesburg                | 1         | 1.15%   |
| Istanbul                    | 1         | 1.15%   |
| Heredia                     | 1         | 1.15%   |
| Helsinki                    | 1         | 1.15%   |
| Ganei Tikva                 | 1         | 1.15%   |
| Ephrata                     | 1         | 1.15%   |
| Enskede-Arsta-Vantoer       | 1         | 1.15%   |
| Decatur                     | 1         | 1.15%   |
| Dearborn Heights            | 1         | 1.15%   |
| Dayton                      | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 19.83%  |
| Samsung Electronics | 17        | 17     | 14.66%  |
| WDC                 | 16        | 21     | 13.79%  |
| Toshiba             | 14        | 14     | 12.07%  |
| Kingston            | 7         | 7      | 6.03%   |
| Crucial             | 6         | 6      | 5.17%   |
| SanDisk             | 4         | 4      | 3.45%   |
| Hitachi             | 4         | 5      | 3.45%   |
| Unknown             | 3         | 3      | 2.59%   |
| Micron Technology   | 3         | 3      | 2.59%   |
| HGST                | 2         | 2      | 1.72%   |
| Fujitsu             | 2         | 2      | 1.72%   |
| XrayDisk            | 1         | 1      | 0.86%   |
| Vaseky              | 1         | 1      | 0.86%   |
| SK hynix            | 1         | 3      | 0.86%   |
| PNY                 | 1         | 2      | 0.86%   |
| Plextor             | 1         | 1      | 0.86%   |
| Maxtor              | 1         | 1      | 0.86%   |
| Leven               | 1         | 1      | 0.86%   |
| KingSpec            | 1         | 1      | 0.86%   |
| KingFast            | 1         | 1      | 0.86%   |
| Intenso             | 1         | 1      | 0.86%   |
| Hoodisk             | 1         | 1      | 0.86%   |
| Goodram             | 1         | 1      | 0.86%   |
| China               | 1         | 1      | 0.86%   |
| Apple               | 1         | 1      | 0.86%   |
| A-DATA Technology   | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 4         | 3.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2.48%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 2.48%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 2         | 1.65%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.65%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 1.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 1.65%   |
| Samsung SSD 850 EVO 250GB           | 2         | 1.65%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 1.65%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 1.65%   |
| Crucial CT240BX500SSD1 240GB        | 2         | 1.65%   |
| XrayDisk 240GB                      | 1         | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.83%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 1         | 0.83%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1         | 0.83%   |
| WDC WD7501AALS-75J7B0 752GB         | 1         | 0.83%   |
| WDC WD7500BPKX-22HPJT0 752GB        | 1         | 0.83%   |
| WDC WD60EDAZ-11BMZB0 6TB            | 1         | 0.83%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 0.83%   |
| WDC WD3200AAJS-00B4A0 320GB         | 1         | 0.83%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.83%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1         | 0.83%   |
| WDC WD2500AAKX-001CA0 250GB         | 1         | 0.83%   |
| WDC WD1200BEVS-00UST0 120GB         | 1         | 0.83%   |
| WDC WD10SPZX-75Z10T2 1TB            | 1         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.83%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 0.83%   |
| WDC WD1003FZEX-00K3CA0 1TB          | 1         | 0.83%   |
| Vaseky V800/128G 128GB              | 1         | 0.83%   |
| Unknown SD16G  16GB                 | 1         | 0.83%   |
| Unknown MMC Card  16GB              | 1         | 0.83%   |
| Unknown HAG4a2  16GB                | 1         | 0.83%   |
| Toshiba THNSFC128GBSJ SSD           | 1         | 0.83%   |
| Toshiba MQ04ABF100 1TB              | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB              | 1         | 0.83%   |
| Toshiba MQ01ABD075 752GB            | 1         | 0.83%   |
| Toshiba MK7559GSXP 752GB            | 1         | 0.83%   |
| Toshiba MK5059GSXP 500GB            | 1         | 0.83%   |
| Toshiba MK3275GSX 320GB             | 1         | 0.83%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1         | 0.83%   |
| SK hynix PC401 NVMe 1TB             | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 1024GB      | 1         | 0.83%   |
| Seagate ST9500325AS 500GB           | 1         | 0.83%   |
| Seagate ST500LT015-1DJ142 500GB     | 1         | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB      | 1         | 0.83%   |
| Seagate ST3500630AS 500GB           | 1         | 0.83%   |
| Seagate ST3500413AS 500GB           | 1         | 0.83%   |
| Seagate ST3500312CS 500GB           | 1         | 0.83%   |
| Seagate ST3320418AS 320GB           | 1         | 0.83%   |
| Seagate ST3250820AS 250GB           | 1         | 0.83%   |
| Seagate ST31000524AS 1TB            | 1         | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB      | 1         | 0.83%   |
| Seagate ST2000DM001-9YN164 2TB      | 1         | 0.83%   |
| Seagate ST1000VT000 HN-M101MBB 1TB  | 1         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 0.83%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB      | 1         | 0.83%   |
| Seagate NVMe SSD Drive 250GB        | 1         | 0.83%   |
| SanDisk Ultra II 480GB SSD          | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 23     | 35.48%  |
| WDC                 | 13        | 15     | 20.97%  |
| Toshiba             | 12        | 12     | 19.35%  |
| Samsung Electronics | 5         | 5      | 8.06%   |
| Hitachi             | 4         | 5      | 6.45%   |
| HGST                | 2         | 2      | 3.23%   |
| Fujitsu             | 2         | 2      | 3.23%   |
| Maxtor              | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 15.79%  |
| Samsung Electronics | 5         | 5      | 13.16%  |
| Crucial             | 5         | 5      | 13.16%  |
| WDC                 | 4         | 5      | 10.53%  |
| SanDisk             | 4         | 4      | 10.53%  |
| Micron Technology   | 2         | 2      | 5.26%   |
| Vaseky              | 1         | 1      | 2.63%   |
| Toshiba             | 1         | 1      | 2.63%   |
| PNY                 | 1         | 2      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Leven               | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| KingFast            | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| Hoodisk             | 1         | 1      | 2.63%   |
| Goodram             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 55        | 66     | 52.38%  |
| SSD     | 33        | 40     | 31.43%  |
| NVMe    | 13        | 16     | 12.38%  |
| MMC     | 3         | 3      | 2.86%   |
| Unknown | 1         | 1      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 106    | 81.11%  |
| NVMe | 13        | 16     | 14.44%  |
| MMC  | 3         | 3      | 3.33%   |
| SAS  | 1         | 1      | 1.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 58     | 53.93%  |
| 0.51-1.0   | 33        | 38     | 37.08%  |
| 1.01-2.0   | 4         | 4      | 4.49%   |
| 2.01-3.0   | 2         | 3      | 2.25%   |
| 3.01-4.0   | 1         | 1      | 1.12%   |
| 4.01-10.0  | 1         | 2      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 41.86%  |
| 501-1000       | 14        | 16.28%  |
| 251-500        | 13        | 15.12%  |
| 1001-2000      | 7         | 8.14%   |
| 51-100         | 6         | 6.98%   |
| 21-50          | 3         | 3.49%   |
| 1-20           | 3         | 3.49%   |
| More than 3000 | 2         | 2.33%   |
| Unknown        | 2         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 55.17%  |
| 101-250   | 11        | 12.64%  |
| 21-50     | 10        | 11.49%  |
| 251-500   | 6         | 6.9%    |
| 51-100    | 5         | 5.75%   |
| 1001-2000 | 3         | 3.45%   |
| 501-1000  | 2         | 2.3%    |
| Unknown   | 2         | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST3320418AS 320GB      | 1         | 1      | 33.33%  |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS543232A7A384 320GB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 63        | 92     | 70%     |
| Works    | 24        | 31     | 26.67%  |
| Malfunc  | 3         | 3      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 65        | 66.33%  |
| AMD                              | 11        | 11.22%  |
| Samsung Electronics              | 9         | 9.18%   |
| Silicon Integrated Systems [SiS] | 2         | 2.04%   |
| Nvidia                           | 2         | 2.04%   |
| Toshiba America Info Systems     | 1         | 1.02%   |
| SK hynix                         | 1         | 1.02%   |
| Seagate Technology               | 1         | 1.02%   |
| SanDisk                          | 1         | 1.02%   |
| Micron/Crucial Technology        | 1         | 1.02%   |
| Micron Technology                | 1         | 1.02%   |
| Marvell Technology Group         | 1         | 1.02%   |
| Kingston Technology Company      | 1         | 1.02%   |
| ASMedia Technology               | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 6.61%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 4.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 4.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 4.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 4.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 3.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 3.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.48%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.65%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 1.65%   |
| Nvidia MCP61 IDE                                                                 | 2         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 2         | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 2         | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.65%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.65%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.83%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.83%   |
| Seagate FireCuda 510 SSD                                                         | 1         | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.83%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.83%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1         | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.83%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.83%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1         | 0.83%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.83%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 0.83%   |
| AMD X370 Series Chipset SATA Controller                                          | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                               | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 0.83%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 0.83%   |
| AMD FCH SATA Controller D                                                        | 1         | 0.83%   |
| AMD FCH IDE Controller                                                           | 1         | 0.83%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                           | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 56        | 56.57%  |
| IDE  | 18        | 18.18%  |
| NVMe | 15        | 15.15%  |
| RAID | 10        | 10.1%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 84.88%  |
| AMD    | 13        | 15.12%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.33%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 2.33%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 2.33%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 2.33%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.33%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 1.16%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.16%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.16%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1         | 1.16%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 1.16%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.16%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 1.16%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.16%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.16%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.16%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.16%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.16%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 1         | 1.16%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.16%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.16%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1         | 1.16%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-5675R CPU @ 3.10GHz           | 1         | 1.16%   |
| Intel Core i5-5257U CPU @ 2.70GHz           | 1         | 1.16%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1         | 1.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.16%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.16%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.16%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.16%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 1.16%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.16%   |
| Intel Core i3-5020U CPU @ 2.20GHz           | 1         | 1.16%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.16%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.16%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.16%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.16%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1         | 1.16%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1         | 1.16%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1         | 1.16%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.16%   |
| Intel Core 2 CPU 6320 @ 1.86GHz             | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 23.26%  |
| Intel Core i7           | 18        | 20.93%  |
| Intel Core i3           | 13        | 15.12%  |
| Intel Core 2 Duo        | 4         | 4.65%   |
| Intel Core 2 Quad       | 3         | 3.49%   |
| Intel Celeron           | 3         | 3.49%   |
| AMD Ryzen 5             | 3         | 3.49%   |
| Other                   | 2         | 2.33%   |
| Intel Xeon              | 2         | 2.33%   |
| Intel Pentium Dual-Core | 2         | 2.33%   |
| Intel Pentium Dual      | 2         | 2.33%   |
| AMD FX                  | 2         | 2.33%   |
| AMD A10                 | 2         | 2.33%   |
| Intel Pentium           | 1         | 1.16%   |
| Intel Core i9           | 1         | 1.16%   |
| Intel Core 2            | 1         | 1.16%   |
| Intel Celeron Dual-Core | 1         | 1.16%   |
| AMD Ryzen 7             | 1         | 1.16%   |
| AMD Phenom II X6        | 1         | 1.16%   |
| AMD Phenom              | 1         | 1.16%   |
| AMD Athlon Dual Core    | 1         | 1.16%   |
| AMD Athlon 64 X2        | 1         | 1.16%   |
| AMD A4                  | 1         | 1.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 46        | 53.49%  |
| 4      | 30        | 34.88%  |
| 6      | 8         | 9.3%    |
| 8      | 1         | 1.16%   |
| 1      | 1         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 86        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 62.79%  |
| 1      | 32        | 37.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 86        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 16.09%  |
| 0x306a9    | 8         | 9.2%    |
| 0x206a7    | 6         | 6.9%    |
| 0x1067a    | 6         | 6.9%    |
| 0x806ea    | 5         | 5.75%   |
| 0x906ea    | 4         | 4.6%    |
| 0x40651    | 4         | 4.6%    |
| 0x306d4    | 4         | 4.6%    |
| 0x706e5    | 3         | 3.45%   |
| 0x306c3    | 3         | 3.45%   |
| 0x806c1    | 2         | 2.3%    |
| 0x6fd      | 2         | 2.3%    |
| 0x20655    | 2         | 2.3%    |
| 0x10677    | 2         | 2.3%    |
| 0x10676    | 2         | 2.3%    |
| 0x06000852 | 2         | 2.3%    |
| 0xa0652    | 1         | 1.15%   |
| 0x906ed    | 1         | 1.15%   |
| 0x906eb    | 1         | 1.15%   |
| 0x806e9    | 1         | 1.15%   |
| 0x6f6      | 1         | 1.15%   |
| 0x506e3    | 1         | 1.15%   |
| 0x406c4    | 1         | 1.15%   |
| 0x406c3    | 1         | 1.15%   |
| 0x40671    | 1         | 1.15%   |
| 0x30678    | 1         | 1.15%   |
| 0x106a5    | 1         | 1.15%   |
| 0x08701021 | 1         | 1.15%   |
| 0x08101016 | 1         | 1.15%   |
| 0x08001138 | 1         | 1.15%   |
| 0x0600611a | 1         | 1.15%   |
| 0x06003106 | 1         | 1.15%   |
| 0x010000dc | 1         | 1.15%   |
| 0x01000083 | 1         | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 15        | 17.44%  |
| Penryn      | 10        | 11.63%  |
| Haswell     | 9         | 10.47%  |
| IvyBridge   | 8         | 9.3%    |
| SandyBridge | 6         | 6.98%   |
| Broadwell   | 6         | 6.98%   |
| Westmere    | 4         | 4.65%   |
| Core        | 4         | 4.65%   |
| Silvermont  | 3         | 3.49%   |
| Piledriver  | 3         | 3.49%   |
| IceLake     | 3         | 3.49%   |
| Zen         | 2         | 2.33%   |
| TigerLake   | 2         | 2.33%   |
| K8 Hammer   | 2         | 2.33%   |
| K10         | 2         | 2.33%   |
| Zen+        | 1         | 1.16%   |
| Zen 2       | 1         | 1.16%   |
| Steamroller | 1         | 1.16%   |
| Skylake     | 1         | 1.16%   |
| Nehalem     | 1         | 1.16%   |
| Excavator   | 1         | 1.16%   |
| CometLake   | 1         | 1.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 53.4%   |
| Nvidia                           | 30        | 29.13%  |
| AMD                              | 16        | 15.53%  |
| Silicon Integrated Systems [SiS] | 2         | 1.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.72%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.77%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 2.83%   |
| Intel HD Graphics 620                                                                    | 3         | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.83%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 1.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.89%   |
| AMD RV770 [Radeon HD 4850]                                                               | 2         | 1.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.89%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.94%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.94%   |
| Nvidia GT215 [GeForce GT 320]                                                            | 1         | 0.94%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.94%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.94%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.94%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.94%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.94%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1         | 0.94%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.94%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1         | 0.94%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.94%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1         | 0.94%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1         | 0.94%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.94%   |
| Nvidia GF108GL [Quadro 600]                                                              | 1         | 0.94%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 0.94%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1         | 0.94%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.94%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 0.94%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.94%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.94%   |
| Intel HD Graphics 630                                                                    | 1         | 0.94%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.94%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.94%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1         | 0.94%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 44.19%  |
| 1 x Nvidia     | 17        | 19.77%  |
| Intel + Nvidia | 13        | 15.12%  |
| 1 x AMD        | 11        | 12.79%  |
| Intel + AMD    | 3         | 3.49%   |
| 2 x AMD        | 2         | 2.33%   |
| 1 x SiS        | 2         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 65        | 74.71%  |
| Proprietary | 17        | 19.54%  |
| Unknown     | 5         | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 55.17%  |
| 0.51-1.0   | 14        | 16.09%  |
| 3.01-4.0   | 10        | 11.49%  |
| 1.01-2.0   | 10        | 11.49%  |
| 7.01-8.0   | 2         | 2.3%    |
| 0.01-0.5   | 2         | 2.3%    |
| 2.01-3.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 20.45%  |
| LG Display              | 8         | 9.09%   |
| BOE                     | 8         | 9.09%   |
| AU Optronics            | 8         | 9.09%   |
| Goldstar                | 5         | 5.68%   |
| Hewlett-Packard         | 4         | 4.55%   |
| Dell                    | 3         | 3.41%   |
| Ancor Communications    | 3         | 3.41%   |
| Philips                 | 2         | 2.27%   |
| Lenovo                  | 2         | 2.27%   |
| Chimei Innolux          | 2         | 2.27%   |
| BenQ                    | 2         | 2.27%   |
| ASUSTek Computer        | 2         | 2.27%   |
| Apple                   | 2         | 2.27%   |
| Acer                    | 2         | 2.27%   |
| Vizio                   | 1         | 1.14%   |
| ViewSonic               | 1         | 1.14%   |
| Vestel Elektronik       | 1         | 1.14%   |
| Unknown                 | 1         | 1.14%   |
| Toshiba                 | 1         | 1.14%   |
| SKY                     | 1         | 1.14%   |
| Sharp                   | 1         | 1.14%   |
| MSI                     | 1         | 1.14%   |
| LG Electronics          | 1         | 1.14%   |
| JDI                     | 1         | 1.14%   |
| Insignia                | 1         | 1.14%   |
| Huion                   | 1         | 1.14%   |
| HPN                     | 1         | 1.14%   |
| HannStar                | 1         | 1.14%   |
| Eizo                    | 1         | 1.14%   |
| Chi Mei Optoelectronics | 1         | 1.14%   |
| AOC                     | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 2         | 2.15%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 2.15%   |
| Vizio LCD Monitor VIZ0026 1360x768 580x320mm 26.1-inch                | 1         | 1.08%   |
| ViewSonic VA912-4SERIES VSC721C 1280x1024 376x301mm 19.0-inch         | 1         | 1.08%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                         | 1         | 1.08%   |
| Unknown LCD Monitor Sony 55R617 1920x1080                             | 1         | 1.08%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                       | 1         | 1.08%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                  | 1         | 1.08%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.08%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 1.08%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 1.08%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 480x270mm 21.7-inch     | 1         | 1.08%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 261x163mm 12.1-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 1.08%   |
| Philips LCD Monitor 150C4 1024x768                                    | 1         | 1.08%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1         | 1.08%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 1         | 1.08%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 1.08%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0582 3000x2000 275x183mm 13.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD037C 1366x768 310x174mm 14.0-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch           | 1         | 1.08%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch               | 1         | 1.08%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.08%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 1.08%   |
| Insignia NS28ED200NA14 BBY0032 1680x1050 640x384mm 29.4-inch          | 1         | 1.08%   |
| Huion GT-133 HAT1330 1920x1080 294x165mm 13.3-inch                    | 1         | 1.08%   |
| HPN LCD Monitor HP 24o 1920x1080                                      | 1         | 1.08%   |
| Hewlett-Packard ZR2240w HWP2952 1920x1080 475x267mm 21.5-inch         | 1         | 1.08%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1         | 1.08%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 510x287mm 23.0-inch          | 1         | 1.08%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 1         | 1.08%   |
| HannStar iH282 HSD20E6 1920x1200 593x371mm 27.5-inch                  | 1         | 1.08%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 1         | 1.08%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1         | 1.08%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                 | 1         | 1.08%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1         | 1.08%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 1         | 1.08%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                     | 1         | 1.08%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                     | 1         | 1.08%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1         | 1.08%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 1         | 1.08%   |
| Dell LCD Monitor ST2220L 3840x1080                                    | 1         | 1.08%   |
| Dell LCD Monitor ST2220L                                              | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 32        | 35.56%  |
| 1366x768 (WXGA)   | 22        | 24.44%  |
| 3840x2160 (4K)    | 8         | 8.89%   |
| 1920x1200 (WUXGA) | 5         | 5.56%   |
| 1600x900 (HD+)    | 3         | 3.33%   |
| 1440x900 (WXGA+)  | 3         | 3.33%   |
| 3840x1080         | 2         | 2.22%   |
| 3000x2000         | 2         | 2.22%   |
| 2560x1080         | 2         | 2.22%   |
| 1280x800 (WXGA)   | 2         | 2.22%   |
| Unknown           | 2         | 2.22%   |
| 3440x1440         | 1         | 1.11%   |
| 2256x1504         | 1         | 1.11%   |
| 1920x540          | 1         | 1.11%   |
| 1360x768          | 1         | 1.11%   |
| 1280x720 (HD)     | 1         | 1.11%   |
| 1280x1024 (SXGA)  | 1         | 1.11%   |
| 1024x768 (XGA)    | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 28.89%  |
| 24      | 9         | 10%     |
| 27      | 8         | 8.89%   |
| 14      | 7         | 7.78%   |
| Unknown | 7         | 7.78%   |
| 13      | 6         | 6.67%   |
| 23      | 4         | 4.44%   |
| 21      | 4         | 4.44%   |
| 19      | 3         | 3.33%   |
| 17      | 3         | 3.33%   |
| 34      | 2         | 2.22%   |
| 31      | 2         | 2.22%   |
| 20      | 2         | 2.22%   |
| 12      | 2         | 2.22%   |
| 84      | 1         | 1.11%   |
| 48      | 1         | 1.11%   |
| 43      | 1         | 1.11%   |
| 40      | 1         | 1.11%   |
| 26      | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 35.96%  |
| 501-600     | 19        | 21.35%  |
| 401-500     | 8         | 8.99%   |
| 201-300     | 7         | 7.87%   |
| Unknown     | 7         | 7.87%   |
| 351-400     | 6         | 6.74%   |
| 601-700     | 4         | 4.49%   |
| 701-800     | 2         | 2.25%   |
| 801-900     | 1         | 1.12%   |
| 1501-2000   | 1         | 1.12%   |
| 1001-1500   | 1         | 1.12%   |
| 901-1000    | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 69.05%  |
| 16/10   | 11        | 13.1%   |
| Unknown | 7         | 8.33%   |
| 3/2     | 4         | 4.76%   |
| 21/9    | 2         | 2.38%   |
| 5/4     | 1         | 1.19%   |
| 1.96    | 1         | 1.19%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 28.09%  |
| 81-90          | 10        | 11.24%  |
| 201-250        | 10        | 11.24%  |
| 301-350        | 8         | 8.99%   |
| 151-200        | 7         | 7.87%   |
| Unknown        | 7         | 7.87%   |
| 251-300        | 5         | 5.62%   |
| 351-500        | 4         | 4.49%   |
| 71-80          | 3         | 3.37%   |
| 121-130        | 3         | 3.37%   |
| 501-1000       | 3         | 3.37%   |
| 61-70          | 2         | 2.25%   |
| More than 1000 | 1         | 1.12%   |
| 91-100         | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 28        | 32.18%  |
| 101-120       | 24        | 27.59%  |
| 121-160       | 20        | 22.99%  |
| Unknown       | 7         | 8.05%   |
| More than 240 | 3         | 3.45%   |
| 1-50          | 3         | 3.45%   |
| 161-240       | 2         | 2.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 82.76%  |
| 2     | 10        | 11.49%  |
| 0     | 4         | 4.6%    |
| 3     | 1         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 43        | 33.08%  |
| Intel                            | 38        | 29.23%  |
| Qualcomm Atheros                 | 21        | 16.15%  |
| Broadcom                         | 8         | 6.15%   |
| TP-Link                          | 3         | 2.31%   |
| Marvell Technology Group         | 3         | 2.31%   |
| Silicon Integrated Systems [SiS] | 2         | 1.54%   |
| Qualcomm Atheros Communications  | 2         | 1.54%   |
| Nvidia                           | 2         | 1.54%   |
| Xiaomi                           | 1         | 0.77%   |
| T & A Mobile Phones              | 1         | 0.77%   |
| Ralink Technology                | 1         | 0.77%   |
| Ralink                           | 1         | 0.77%   |
| Qualcomm                         | 1         | 0.77%   |
| Linksys                          | 1         | 0.77%   |
| Broadcom Limited                 | 1         | 0.77%   |
| ASUSTek Computer                 | 1         | 0.77%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 33        | 22%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 2.67%   |
| Intel Wireless 3160                                                                           | 4         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                                 | 2         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2         | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 1.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2         | 1.33%   |
| Nvidia MCP61 Ethernet                                                                         | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.33%   |
| Intel Wireless 7265                                                                           | 2         | 1.33%   |
| Intel Wireless 3165                                                                           | 2         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.33%   |
| Intel I211 Gigabit Network Connection                                                         | 2         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 2         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                               | 1         | 0.67%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 0.67%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 0.67%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                                                    | 1         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.67%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.67%   |
| Qualcomm MDM9207-MTP _SN:D3BB13ED                                                             | 1         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                         | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                                    | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.67%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1         | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                          | 1         | 0.67%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1         | 0.67%   |
| Intel Wireless 8260                                                                           | 1         | 0.67%   |
| Intel Wireless 7260                                                                           | 1         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 0.67%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.67%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 0.67%   |
| Intel Ethernet Connection I218-LM                                                             | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                                          | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                                          | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 41.43%  |
| Qualcomm Atheros                | 15        | 21.43%  |
| Realtek Semiconductor           | 10        | 14.29%  |
| Broadcom                        | 7         | 10%     |
| TP-Link                         | 2         | 2.86%   |
| Qualcomm Atheros Communications | 2         | 2.86%   |
| Ralink Technology               | 1         | 1.43%   |
| Ralink                          | 1         | 1.43%   |
| Linksys                         | 1         | 1.43%   |
| Broadcom Limited                | 1         | 1.43%   |
| ASUSTek Computer                | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 5.71%   |
| Intel Wireless 3160                                                                           | 4         | 5.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 4.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 2         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 2.86%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2         | 2.86%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 2.86%   |
| Intel Wireless 7265                                                                           | 2         | 2.86%   |
| Intel Wireless 3165                                                                           | 2         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 2.86%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                                 | 2         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 2.86%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.86%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 1.43%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.43%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 1.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.43%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.43%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1         | 1.43%   |
| Intel Wireless 8260                                                                           | 1         | 1.43%   |
| Intel Wireless 7260                                                                           | 1         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.43%   |
| Intel Ultimate N WiFi Link 5300                                                               | 1         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.43%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.43%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                          | 1         | 1.43%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 1.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1         | 1.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 1.43%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1         | 1.43%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 39        | 50%     |
| Intel                            | 16        | 20.51%  |
| Qualcomm Atheros                 | 9         | 11.54%  |
| Marvell Technology Group         | 3         | 3.85%   |
| Broadcom                         | 3         | 3.85%   |
| Silicon Integrated Systems [SiS] | 2         | 2.56%   |
| Nvidia                           | 2         | 2.56%   |
| Xiaomi                           | 1         | 1.28%   |
| TP-Link                          | 1         | 1.28%   |
| T & A Mobile Phones              | 1         | 1.28%   |
| Qualcomm                         | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 41.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 2.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 2.5%    |
| Nvidia MCP61 Ethernet                                             | 2         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 2         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.25%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.25%   |
| Qualcomm MDM9207-MTP _SN:D3BB13ED                                 | 1         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.25%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.25%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1         | 1.25%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 1.25%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 75        | 53.19%  |
| WiFi     | 66        | 46.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 60.22%  |
| Ethernet | 37        | 39.78%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 55.81%  |
| 1     | 33        | 38.37%  |
| 3     | 3         | 3.49%   |
| 0     | 2         | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 93.02%  |
| Yes  | 6         | 6.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 43.4%   |
| Qualcomm Atheros Communications | 6         | 11.32%  |
| Cambridge Silicon Radio         | 6         | 11.32%  |
| Realtek Semiconductor           | 4         | 7.55%   |
| IMC Networks                    | 3         | 5.66%   |
| Apple                           | 3         | 5.66%   |
| Broadcom                        | 2         | 3.77%   |
| Toshiba                         | 1         | 1.89%   |
| Ralink Technology               | 1         | 1.89%   |
| Integrated System Solution      | 1         | 1.89%   |
| Hewlett-Packard                 | 1         | 1.89%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| Dell                            | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 24.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 11.32%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 5.66%   |
| Intel Bluetooth Device                              | 3         | 5.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 3.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 3.77%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.77%   |
| Apple Bluetooth USB Host Controller                 | 2         | 3.77%   |
| Toshiba Bluetooth Device                            | 1         | 1.89%   |
| Realtek Bluetooth Radio                             | 1         | 1.89%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.89%   |
| Intel AX210 Bluetooth                               | 1         | 1.89%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.89%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.89%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.89%   |
| Dell Wireless 355 Bluetooth                         | 1         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.89%   |
| Apple Bluetooth HCI                                 | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 71        | 59.17%  |
| Nvidia                                          | 20        | 16.67%  |
| AMD                                             | 16        | 13.33%  |
| Logitech                                        | 3         | 2.5%    |
| Texas Instruments                               | 2         | 1.67%   |
| Silicon Integrated Systems [SiS]                | 2         | 1.67%   |
| C-Media Electronics                             | 2         | 1.67%   |
| Razer USA                                       | 1         | 0.83%   |
| M2Tech                                          | 1         | 0.83%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.83%   |
| Generalplus Technology                          | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 4.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 4.26%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.55%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 2.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.13%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.42%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 1.42%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.42%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.42%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2         | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.42%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.71%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.71%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.71%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.71%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.71%   |
| M2Tech hiFaceDAC UAC2                                                                             | 1         | 0.71%   |
| Logitech QuickCam Fusion                                                                          | 1         | 0.71%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 0.71%   |
| Logitech Headset H390                                                                             | 1         | 0.71%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 0.71%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.71%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.71%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 1         | 0.71%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.71%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 1         | 0.71%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.71%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.71%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 30.95%  |
| SK hynix            | 7         | 16.67%  |
| Micron Technology   | 5         | 11.9%   |
| Kingston            | 5         | 11.9%   |
| Unknown             | 4         | 9.52%   |
| Crucial             | 2         | 4.76%   |
| Teikon              | 1         | 2.38%   |
| Ramaxel Technology  | 1         | 2.38%   |
| Patriot             | 1         | 2.38%   |
| Nanya Technology    | 1         | 2.38%   |
| G.Skill             | 1         | 2.38%   |
| Corsair             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                      | 2         | 4.65%   |
| Unknown RAM Module 4096MB DIMM SDRAM 800MT/s                               | 1         | 2.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                    | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 956MT/s                               | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                               | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                     | 1         | 2.33%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.33%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                      | 1         | 2.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                  | 1         | 2.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s                  | 1         | 2.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.33%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s                        | 1         | 2.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                      | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s                   | 1         | 2.33%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s               | 1         | 2.33%   |
| Samsung RAM 4D332037385432383633515A532D43463720 1024MB DIMM DDR2 800MT/s  | 1         | 2.33%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s                   | 1         | 2.33%   |
| Patriot RAM PSD432G32002 32GB DIMM DDR4 3200MT/s                           | 1         | 2.33%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 49926MT/s                     | 1         | 2.33%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 2.33%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s                   | 1         | 2.33%   |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s                       | 1         | 2.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                      | 1         | 2.33%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s                     | 1         | 2.33%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                                  | 1         | 2.33%   |
| Kingston RAM KHX2133C13S4/4G 4GB SODIMM DDR4 2133MT/s                      | 1         | 2.33%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.33%   |
| Kingston RAM 9905734-018.A00G 16384MB DIMM DDR4 2667MT/s                   | 1         | 2.33%   |
| Kingston RAM 202020202020202020202020202020202020 2048MB DIMM DDR2 800MT/s | 1         | 2.33%   |
| G.Skill RAM F3-19200C10-8GBZHD 8192MB DIMM DDR3 1333MT/s                   | 1         | 2.33%   |
| Crucial RAM CT25664A 2GB DIMM DDR2 800MT/s                                 | 1         | 2.33%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s                 | 1         | 2.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s                   | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 42.42%  |
| DDR3    | 10        | 30.3%   |
| DDR2    | 3         | 9.09%   |
| SDRAM   | 2         | 6.06%   |
| Unknown | 2         | 6.06%   |
| LPDDR4  | 1         | 3.03%   |
| LPDDR3  | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 60.61%  |
| DIMM         | 11        | 33.33%  |
| Row Of Chips | 1         | 3.03%   |
| Unknown      | 1         | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 32.43%  |
| 4096  | 10        | 27.03%  |
| 2048  | 8         | 21.62%  |
| 16384 | 4         | 10.81%  |
| 1024  | 2         | 5.41%   |
| 32768 | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 10        | 27.78%  |
| 2667  | 7         | 19.44%  |
| 3200  | 4         | 11.11%  |
| 800   | 4         | 11.11%  |
| 2400  | 3         | 8.33%   |
| 1333  | 2         | 5.56%   |
| 49926 | 1         | 2.78%   |
| 4267  | 1         | 2.78%   |
| 3466  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1334  | 1         | 2.78%   |
| 956   | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |
| Fuji Xerox      | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson ET-2720 Series       | 1         | 20%     |
| HP Officejet 6600                | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Fuji Xerox DocuPrint M205 b      | 1         | 20%     |
| Canon MF240 Series V4            | 1         | 20%     |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 23.4%   |
| Microdia                      | 6         | 12.77%  |
| Suyin                         | 4         | 8.51%   |
| Acer                          | 4         | 8.51%   |
| Sunplus Innovation Technology | 3         | 6.38%   |
| Realtek Semiconductor         | 3         | 6.38%   |
| Quanta                        | 3         | 6.38%   |
| IMC Networks                  | 3         | 6.38%   |
| Huawei Technologies           | 2         | 4.26%   |
| Apple                         | 2         | 4.26%   |
| Z-Star Microelectronics       | 1         | 2.13%   |
| Silicon Motion                | 1         | 2.13%   |
| Logitech                      | 1         | 2.13%   |
| Jieli Technology              | 1         | 2.13%   |
| Importek                      | 1         | 2.13%   |
| Cubeternet                    | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                         | 2         | 4.26%   |
| Huawei UVC Camera                                                     | 2         | 4.26%   |
| Chicony Integrated Camera                                             | 2         | 4.26%   |
| Z-Star A4 tech USB2.0 Camera                                          | 1         | 2.13%   |
| Suyin WebCam                                                          | 1         | 2.13%   |
| Suyin HP Truevision HD                                                | 1         | 2.13%   |
| Suyin Asus Integrated Webcam                                          | 1         | 2.13%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 2.13%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 2.13%   |
| Sunplus Integrated_Webcam_HD                                          | 1         | 2.13%   |
| Sunplus HD WebCam                                                     | 1         | 2.13%   |
| Silicon Motion HP Webcam-101 Integrated Camera                        | 1         | 2.13%   |
| Realtek USB2.0 VGA UVC WebCam                                         | 1         | 2.13%   |
| Realtek Laptop Camera                                                 | 1         | 2.13%   |
| Realtek HP Truevision HD                                              | 1         | 2.13%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                  | 1         | 2.13%   |
| Quanta HP TrueVision HD Camera                                        | 1         | 2.13%   |
| Quanta HD Webcam                                                      | 1         | 2.13%   |
| Microdia Sonix USB 2.0 Camera                                         | 1         | 2.13%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                        | 1         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 2.13%   |
| Microdia Integrated Webcam                                            | 1         | 2.13%   |
| Logitech HD Pro Webcam C920                                           | 1         | 2.13%   |
| Jieli USB PHY 2.0                                                     | 1         | 2.13%   |
| Importek HP Truevision HD Integrated Webcam                           | 1         | 2.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 1         | 2.13%   |
| IMC Networks USB2.0 UVC HD Webcam                                     | 1         | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 2.13%   |
| Cubeternet HDMI to U3 capture                                         | 1         | 2.13%   |
| Chicony USB 2.0 Camera                                                | 1         | 2.13%   |
| Chicony TOSHIBA Web Camera - HD                                       | 1         | 2.13%   |
| Chicony Lenovo EasyCamera                                             | 1         | 2.13%   |
| Chicony HP Wide Vision HD Camera                                      | 1         | 2.13%   |
| Chicony HP Webcam [2 MP Macro]                                        | 1         | 2.13%   |
| Chicony HP Webcam                                                     | 1         | 2.13%   |
| Chicony HP HD Camera                                                  | 1         | 2.13%   |
| Chicony HD WebCam                                                     | 1         | 2.13%   |
| Chicony EasyCamera                                                    | 1         | 2.13%   |
| Apple FaceTime HD Camera (Built-in)                                   | 1         | 2.13%   |
| Apple Built-in iSight                                                 | 1         | 2.13%   |
| Acer Integrated Camera                                                | 1         | 2.13%   |
| Acer HP TrueVision HD Webcam                                          | 1         | 2.13%   |
| Acer EasyCamera                                                       | 1         | 2.13%   |
| Acer BisonCam, NB Pro                                                 | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner       | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 16.67%  |
| AuthenTec AES2810                          | 1         | 16.67%  |
| Unknown                                    | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 76.74%  |
| 1     | 18        | 20.93%  |
| 2     | 2         | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 7         | 36.84%  |
| Fingerprint reader | 6         | 31.58%  |
| Net/wireless       | 2         | 10.53%  |
| Chipcard           | 2         | 10.53%  |
| Net/ethernet       | 1         | 5.26%   |
| Bluetooth          | 1         | 5.26%   |

