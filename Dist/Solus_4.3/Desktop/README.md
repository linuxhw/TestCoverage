Solus 4.3 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 41

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo     | CRESCENTBAY 31900058 STD    | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| Gigabyte   | Z68AP-D3                    | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| ASUSTek    | B85M-E                      | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek    | B85M-E                      | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI        | B450M MORTAR                | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Gigabyte   | F2A68HM-H                   | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte   | GA-MA770-UD3                | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown    | HX90                        | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown    | HX90                        | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown    | HX90                        | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| ASUSTek    | A88X-PRO                    | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Dell       | 06X1TJ A00                  | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA       | G41T-M7 LGT                 | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte   | B85M-D3H                    | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| MSI        | B350 TOMAHAWK ARCTIC        | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASRock     | X470 Master SLI             | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| HP         | 805F                        | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda | Alpha                       | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar    | H61MLV2                     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Gigabyte   | P31-ES3G                    | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte   | P31-ES3G                    | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| eMachines  | EL1852G                     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines  | EL1852G                     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Gigabyte   | H81M-S2V                    | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte   | H81M-S2V                    | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte   | B360M AORUS Gaming 3-CF     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo     | ThinkCentre M71e 3157G6S    | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.15.32-213.current | 5        | 17.86%  |
| 5.14.21-210.current | 4        | 14.29%  |
| 5.14.16-205.current | 4        | 14.29%  |
| 5.13.12-193.current | 3        | 10.71%  |
| 5.15.43-215.current | 2        | 7.14%   |
| 5.15.30-212.current | 2        | 7.14%   |
| 5.14.14-202.current | 2        | 7.14%   |
| 5.13.6-190.current  | 2        | 7.14%   |
| 5.13.1-187.current  | 2        | 7.14%   |
| 5.15.26-211.current | 1        | 3.57%   |
| 5.13.8-191.current  | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.32 | 5        | 17.86%  |
| 5.14.21 | 4        | 14.29%  |
| 5.14.16 | 4        | 14.29%  |
| 5.13.12 | 3        | 10.71%  |
| 5.15.43 | 2        | 7.14%   |
| 5.15.30 | 2        | 7.14%   |
| 5.14.14 | 2        | 7.14%   |
| 5.13.6  | 2        | 7.14%   |
| 5.13.1  | 2        | 7.14%   |
| 5.15.26 | 1        | 3.57%   |
| 5.13.8  | 1        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 10       | 35.71%  |
| 5.14    | 10       | 35.71%  |
| 5.13    | 8        | 28.57%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 27       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 21       | 77.78%  |
| KDE5    | 2        | 7.41%   |
| GNOME   | 2        | 7.41%   |
| KDE     | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 26       | 96.3%   |
| Wayland | 1        | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 74.07%  |
| LightDM | 5        | 18.52%  |
| SDDM    | 2        | 7.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 50%     |
| ru_RU | 2        | 7.14%   |
| fr_FR | 2        | 7.14%   |
| en_GB | 2        | 7.14%   |
| de_DE | 2        | 7.14%   |
| pt_BR | 1        | 3.57%   |
| nl_NL | 1        | 3.57%   |
| es_VE | 1        | 3.57%   |
| es_ES | 1        | 3.57%   |
| ar_SA | 1        | 3.57%   |
| ar_EG | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 16       | 59.26%  |
| EFI  | 11       | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 25       | 92.59%  |
| Xfs   | 1        | 3.7%    |
| Btrfs | 1        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 81.48%  |
| MBR     | 3        | 11.11%  |
| GPT     | 2        | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 89.29%  |
| Yes       | 3        | 10.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 81.48%  |
| Yes       | 5        | 18.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 29.63%  |
| ASUSTek Computer    | 5        | 18.52%  |
| MSI                 | 3        | 11.11%  |
| Lenovo              | 2        | 7.41%   |
| ASRock              | 2        | 7.41%   |
| MEGA                | 1        | 3.7%    |
| Hewlett-Packard     | 1        | 3.7%    |
| Fujitsu             | 1        | 3.7%    |
| eMachines           | 1        | 3.7%    |
| Dell                | 1        | 3.7%    |
| Biostar             | 1        | 3.7%    |
| Unknown             | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7B89                      | 1        | 3.7%    |
| MSI MS-7B85                      | 1        | 3.7%    |
| MSI MS-7A34                      | 1        | 3.7%    |
| MEGA G41T-M7 LGT                 | 1        | 3.7%    |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 3.7%    |
| Lenovo C50-30 F0B1002EFR         | 1        | 3.7%    |
| HP ProDesk 490 G3 MT Business PC | 1        | 3.7%    |
| Gigabyte Z68AP-D3                | 1        | 3.7%    |
| Gigabyte P31-ES3G                | 1        | 3.7%    |
| Gigabyte H81M-S2V                | 1        | 3.7%    |
| Gigabyte H110M-DS2V              | 1        | 3.7%    |
| Gigabyte GA-MA770-UD3            | 1        | 3.7%    |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 3.7%    |
| Gigabyte F2A68HM-H               | 1        | 3.7%    |
| Gigabyte B85M-D3H                | 1        | 3.7%    |
| Fujitsu CELSIUS W530             | 1        | 3.7%    |
| eMachines EL1852G                | 1        | 3.7%    |
| Dell OptiPlex 9020               | 1        | 3.7%    |
| Biostar H61MLV2                  | 1        | 3.7%    |
| ASUS TUF Gaming X570-PRO         | 1        | 3.7%    |
| ASUS TUF B450-PRO GAMING         | 1        | 3.7%    |
| ASUS ROG STRIX B450-F GAMING     | 1        | 3.7%    |
| ASUS All Series                  | 1        | 3.7%    |
| ASUS A88X-PRO                    | 1        | 3.7%    |
| ASRock H81 Pro BTC R2.0          | 1        | 3.7%    |
| ASRock B450 Gaming-ITX/ac        | 1        | 3.7%    |
| Unknown                          | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 2        | 7.41%   |
| MSI MS-7B89            | 1        | 3.7%    |
| MSI MS-7B85            | 1        | 3.7%    |
| MSI MS-7A34            | 1        | 3.7%    |
| MEGA G41T-M7           | 1        | 3.7%    |
| Lenovo ThinkCentre     | 1        | 3.7%    |
| Lenovo C50-30          | 1        | 3.7%    |
| HP ProDesk             | 1        | 3.7%    |
| Gigabyte Z68AP-D3      | 1        | 3.7%    |
| Gigabyte P31-ES3G      | 1        | 3.7%    |
| Gigabyte H81M-S2V      | 1        | 3.7%    |
| Gigabyte H110M-DS2V    | 1        | 3.7%    |
| Gigabyte GA-MA770-UD3  | 1        | 3.7%    |
| Gigabyte GA-78LMT-USB3 | 1        | 3.7%    |
| Gigabyte F2A68HM-H     | 1        | 3.7%    |
| Gigabyte B85M-D3H      | 1        | 3.7%    |
| Fujitsu CELSIUS        | 1        | 3.7%    |
| eMachines EL1852G      | 1        | 3.7%    |
| Dell OptiPlex          | 1        | 3.7%    |
| Biostar H61MLV2        | 1        | 3.7%    |
| ASUS ROG               | 1        | 3.7%    |
| ASUS All               | 1        | 3.7%    |
| ASUS A88X-PRO          | 1        | 3.7%    |
| ASRock H81             | 1        | 3.7%    |
| ASRock B450            | 1        | 3.7%    |
| Unknown                | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 5        | 18.52%  |
| 2014 | 5        | 18.52%  |
| 2011 | 4        | 14.81%  |
| 2015 | 3        | 11.11%  |
| 2016 | 2        | 7.41%   |
| 2013 | 2        | 7.41%   |
| 2008 | 2        | 7.41%   |
| 2021 | 1        | 3.7%    |
| 2020 | 1        | 3.7%    |
| 2017 | 1        | 3.7%    |
| 2012 | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 27       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 7        | 25.93%  |
| 3.01-4.0   | 6        | 22.22%  |
| 8.01-16.0  | 6        | 22.22%  |
| 32.01-64.0 | 4        | 14.81%  |
| 4.01-8.0   | 3        | 11.11%  |
| 2.01-3.0   | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 10       | 35.71%  |
| 4.01-8.0 | 6        | 21.43%  |
| 2.01-3.0 | 6        | 21.43%  |
| 3.01-4.0 | 5        | 17.86%  |
| 0.51-1.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 32.14%  |
| 2      | 8        | 28.57%  |
| 4      | 7        | 25%     |
| 3      | 3        | 10.71%  |
| 5      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 51.85%  |
| Yes       | 13       | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 59.26%  |
| Yes       | 11       | 40.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 59.26%  |
| Yes       | 11       | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 5        | 18.52%  |
| Germany      | 4        | 14.81%  |
| Venezuela    | 1        | 3.7%    |
| Thailand     | 1        | 3.7%    |
| Sweden       | 1        | 3.7%    |
| Spain        | 1        | 3.7%    |
| Saudi Arabia | 1        | 3.7%    |
| Russia       | 1        | 3.7%    |
| Philippines  | 1        | 3.7%    |
| Norway       | 1        | 3.7%    |
| Netherlands  | 1        | 3.7%    |
| Kazakhstan   | 1        | 3.7%    |
| Iran         | 1        | 3.7%    |
| India        | 1        | 3.7%    |
| Guyana       | 1        | 3.7%    |
| Greece       | 1        | 3.7%    |
| France       | 1        | 3.7%    |
| Canada       | 1        | 3.7%    |
| Brazil       | 1        | 3.7%    |
| Albania      | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Weil am Rhein   | 1        | 3.7%    |
| Toronto         | 1        | 3.7%    |
| Thessaloniki    | 1        | 3.7%    |
| Stockholm       | 1        | 3.7%    |
| Songkhla        | 1        | 3.7%    |
| Seville         | 1        | 3.7%    |
| Severna Park    | 1        | 3.7%    |
| Portsmouth      | 1        | 3.7%    |
| Phoenix         | 1        | 3.7%    |
| Oslo            | 1        | 3.7%    |
| Orenburg        | 1        | 3.7%    |
| Ochten          | 1        | 3.7%    |
| Lipa City       | 1        | 3.7%    |
| Lexington       | 1        | 3.7%    |
| Krefeld         | 1        | 3.7%    |
| Kolkata         | 1        | 3.7%    |
| Huntington Park | 1        | 3.7%    |
| Hamburg         | 1        | 3.7%    |
| Georgetown      | 1        | 3.7%    |
| Durr??s         | 1        | 3.7%    |
| Dammam          | 1        | 3.7%    |
| Curitiba        | 1        | 3.7%    |
| Caracas         | 1        | 3.7%    |
| Caen            | 1        | 3.7%    |
| Bad Homburg     | 1        | 3.7%    |
| Atyrau          | 1        | 3.7%    |
| Arak            | 1        | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 27.78%  |
| Samsung Electronics | 12       | 16     | 22.22%  |
| Seagate             | 6        | 6      | 11.11%  |
| Kingston            | 6        | 8      | 11.11%  |
| Toshiba             | 3        | 3      | 5.56%   |
| Crucial             | 3        | 3      | 5.56%   |
| Hitachi             | 2        | 2      | 3.7%    |
| SanDisk             | 1        | 1      | 1.85%   |
| PNY                 | 1        | 1      | 1.85%   |
| Phison              | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 1      | 1.85%   |
| Intenso             | 1        | 2      | 1.85%   |
| HFS512GD            | 1        | 1      | 1.85%   |
| China               | 1        | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3        | 4.76%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 3.17%   |
| WDC WD10EZEX-08M2NA0 1TB               | 2        | 3.17%   |
| Toshiba DT01ACA050 500GB               | 2        | 3.17%   |
| Samsung SSD 850 EVO 250GB              | 2        | 3.17%   |
| Kingston SA400S37480G 480GB SSD        | 2        | 3.17%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 3.17%   |
| Crucial CT1000P1SSD8 1TB               | 2        | 3.17%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD       | 1        | 1.59%   |
| WDC WD6400AAKS-75A7B2 640GB            | 1        | 1.59%   |
| WDC WD5000AVDS-63U7B1 500GB            | 1        | 1.59%   |
| WDC WD5000AVCS-632DY1 500GB            | 1        | 1.59%   |
| WDC WD5000AAKX-003CA0 500GB            | 1        | 1.59%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 1        | 1.59%   |
| WDC WD3200AAJS-00YZCA0 320GB           | 1        | 1.59%   |
| WDC WD32 00AAJS-00L7A0 320GB           | 1        | 1.59%   |
| WDC WD3000GLFS-01F8U0 304GB            | 1        | 1.59%   |
| WDC WD2500HHTZ-04N21V1 250GB           | 1        | 1.59%   |
| WDC WD2003FZEX-00Z4SA0 2TB             | 1        | 1.59%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 1        | 1.59%   |
| WDC WD10EZRX-00L4HB0 1TB               | 1        | 1.59%   |
| WDC WD10EADS-00P8B0 1TB                | 1        | 1.59%   |
| WDC WD10EADS-00M2B0 1TB                | 1        | 1.59%   |
| WDC WD1003FBYX-01Y7B0 1TB              | 1        | 1.59%   |
| WDC WD My Passport 25F3 512GB          | 1        | 1.59%   |
| Toshiba DT01ACA100 1TB                 | 1        | 1.59%   |
| Seagate ST500DM002-1BD142 500GB        | 1        | 1.59%   |
| Seagate ST4000DM004-2CV104 4TB         | 1        | 1.59%   |
| Seagate ST3320418AS 320GB              | 1        | 1.59%   |
| Seagate ST2000LM007-1R8174 2TB         | 1        | 1.59%   |
| Seagate ST2000DM006-2DM164 2TB         | 1        | 1.59%   |
| Seagate ST2000DM005-2CW102 2TB         | 1        | 1.59%   |
| SanDisk SDSSDP064G 64GB                | 1        | 1.59%   |
| Samsung SSD 870 QVO 2TB                | 1        | 1.59%   |
| Samsung SSD 860 EVO 500GB              | 1        | 1.59%   |
| Samsung SSD 860 EVO 250GB              | 1        | 1.59%   |
| Samsung SSD 860 EVO 1TB                | 1        | 1.59%   |
| Samsung SSD 850 EVO 120GB              | 1        | 1.59%   |
| Samsung SSD 840 PRO Series 256GB       | 1        | 1.59%   |
| Samsung SSD 840 EVO 120GB              | 1        | 1.59%   |
| Samsung MZ7LN128HCHP-000H1 128GB SSD   | 1        | 1.59%   |
| Samsung HD502HI 500GB                  | 1        | 1.59%   |
| PNY CS1311 120GB SSD                   | 1        | 1.59%   |
| Phison NVMe SSD Drive 256GB            | 1        | 1.59%   |
| Micron M600_MTFDDAK256MBFZ 256GB SSD   | 1        | 1.59%   |
| Kingston SHSS37A240G 240GB SSD         | 1        | 1.59%   |
| Kingston NVMe SSD Drive 512GB          | 1        | 1.59%   |
| Kingston NVMe SSD Drive 500GB          | 1        | 1.59%   |
| Intenso External USB 3.0 1TB           | 1        | 1.59%   |
| Hitachi HTS545032B9A300 320GB          | 1        | 1.59%   |
| Hitachi HDS721616PLA380 160GB          | 1        | 1.59%   |
| HFS512GD 9TNG-62A0A 8000 512GB         | 1        | 1.59%   |
| Crucial CT1000MX500SSD1 1TB            | 1        | 1.59%   |
| China SSD 128GB                        | 1        | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 19     | 51.85%  |
| Seagate             | 6        | 6      | 22.22%  |
| Toshiba             | 3        | 3      | 11.11%  |
| Hitachi             | 2        | 2      | 7.41%   |
| Samsung Electronics | 1        | 1      | 3.7%    |
| Intenso             | 1        | 2      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 12     | 50%     |
| Kingston            | 4        | 6      | 20%     |
| WDC                 | 1        | 1      | 5%      |
| SanDisk             | 1        | 1      | 5%      |
| PNY                 | 1        | 1      | 5%      |
| Micron Technology   | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |
| China               | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 22       | 33     | 46.81%  |
| SSD     | 15       | 24     | 31.91%  |
| NVMe    | 8        | 8      | 17.02%  |
| Unknown | 2        | 2      | 4.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 54     | 69.44%  |
| NVMe | 8        | 8      | 22.22%  |
| SAS  | 3        | 5      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 34     | 48.72%  |
| 0.51-1.0   | 12       | 15     | 30.77%  |
| 1.01-2.0   | 6        | 6      | 15.38%  |
| 3.01-4.0   | 2        | 2      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 8        | 29.63%  |
| 501-1000       | 6        | 22.22%  |
| 101-250        | 4        | 14.81%  |
| 1001-2000      | 4        | 14.81%  |
| More than 3000 | 3        | 11.11%  |
| 21-50          | 1        | 3.7%    |
| 51-100         | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 8        | 29.63%  |
| 101-250        | 5        | 18.52%  |
| 501-1000       | 4        | 14.81%  |
| 21-50          | 3        | 11.11%  |
| 1001-2000      | 3        | 11.11%  |
| 251-500        | 2        | 7.41%   |
| More than 3000 | 1        | 3.7%    |
| 51-100         | 1        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Crucial CT1000P1SSD8 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 22       | 56     | 75.86%  |
| Works    | 6        | 10     | 20.69%  |
| Malfunc  | 1        | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 15       | 44.12%  |
| AMD                         | 12       | 35.29%  |
| Samsung Electronics         | 2        | 5.88%   |
| Micron/Crucial Technology   | 2        | 5.88%   |
| Kingston Technology Company | 2        | 5.88%   |
| Phison Electronics          | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 16.28%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 13.95%  |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 11.63%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 4.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 4.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 4.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 4.65%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.33%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 2.33%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.33%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 2.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 63.89%  |
| NVMe | 7        | 19.44%  |
| IDE  | 6        | 16.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 55.56%  |
| AMD    | 12       | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 7.41%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 3.7%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 3.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 3.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 3.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 3.7%    |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 3.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1        | 3.7%    |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1        | 3.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 3.7%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 3.7%    |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1        | 3.7%    |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1        | 3.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1        | 3.7%    |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 3.7%    |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 3.7%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 3.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 3.7%    |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 3.7%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 3.7%    |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 3.7%    |
| AMD Phenom II X4 955 Processor                  | 1        | 3.7%    |
| AMD FX-6300 Six-Core Processor                  | 1        | 3.7%    |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.7%    |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 4        | 14.81%  |
| Intel Core i3           | 4        | 14.81%  |
| AMD Ryzen 7             | 4        | 14.81%  |
| AMD Ryzen 5             | 3        | 11.11%  |
| Intel Core i7           | 2        | 7.41%   |
| Intel Celeron           | 2        | 7.41%   |
| AMD A10                 | 2        | 7.41%   |
| Intel Xeon              | 1        | 3.7%    |
| Intel Pentium Dual-Core | 1        | 3.7%    |
| Intel Core 2 Quad       | 1        | 3.7%    |
| AMD Ryzen 9             | 1        | 3.7%    |
| AMD Phenom II X4        | 1        | 3.7%    |
| AMD FX                  | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 37.04%  |
| 4      | 8        | 29.63%  |
| 8      | 5        | 18.52%  |
| 6      | 3        | 11.11%  |
| 3      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 70.37%  |
| 1      | 8        | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 6        | 22.22%  |
| 0x1067a    | 3        | 11.11%  |
| 0x0800820d | 3        | 11.11%  |
| 0x206a7    | 2        | 7.41%   |
| 0x08701021 | 2        | 7.41%   |
| 0x06003106 | 2        | 7.41%   |
| 0x906e9    | 1        | 3.7%    |
| 0x506e3    | 1        | 3.7%    |
| 0x40651    | 1        | 3.7%    |
| 0x306a9    | 1        | 3.7%    |
| 0x0a50000c | 1        | 3.7%    |
| 0x0a201204 | 1        | 3.7%    |
| 0x08701013 | 1        | 3.7%    |
| 0x06000852 | 1        | 3.7%    |
| 0x010000c8 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 25.93%  |
| Zen+        | 3        | 11.11%  |
| Zen 2       | 3        | 11.11%  |
| Penryn      | 3        | 11.11%  |
| Zen 3       | 2        | 7.41%   |
| Steamroller | 2        | 7.41%   |
| SandyBridge | 2        | 7.41%   |
| Skylake     | 1        | 3.7%    |
| Piledriver  | 1        | 3.7%    |
| KabyLake    | 1        | 3.7%    |
| K10         | 1        | 3.7%    |
| IvyBridge   | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 39.39%  |
| Nvidia | 10       | 30.3%   |
| Intel  | 10       | 30.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 6.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 6.06%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.03%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 3.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.03%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 3.03%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 3.03%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 3.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1        | 3.03%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 3.03%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 3.03%   |
| Intel HD Graphics 530                                                       | 1        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 3.03%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 3.03%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 3.03%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 3.03%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 3.03%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 3.03%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.03%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.03%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 3.03%   |
| AMD Cezanne                                                                 | 1        | 3.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 12       | 44.44%  |
| 1 x Nvidia     | 8        | 29.63%  |
| 1 x Intel      | 4        | 14.81%  |
| Intel + Nvidia | 2        | 7.41%   |
| Intel + AMD    | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 21       | 77.78%  |
| Proprietary | 6        | 22.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 7        | 25.93%  |
| 0.51-1.0   | 7        | 25.93%  |
| Unknown    | 4        | 14.81%  |
| 7.01-8.0   | 2        | 7.41%   |
| 5.01-6.0   | 2        | 7.41%   |
| 3.01-4.0   | 2        | 7.41%   |
| 8.01-16.0  | 2        | 7.41%   |
| 0.01-0.5   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 7        | 22.58%  |
| Goldstar             | 5        | 16.13%  |
| Samsung Electronics  | 4        | 12.9%   |
| Dell                 | 3        | 9.68%   |
| NEC Computers        | 2        | 6.45%   |
| Acer                 | 2        | 6.45%   |
| Sharp                | 1        | 3.23%   |
| Microstep            | 1        | 3.23%   |
| LG Electronics       | 1        | 3.23%   |
| Hewlett-Packard      | 1        | 3.23%   |
| BenQ                 | 1        | 3.23%   |
| ASUSTek Computer     | 1        | 3.23%   |
| Ancor Communications | 1        | 3.23%   |
| Unknown              | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3        | 8.82%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 2.94%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 2.94%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 2.94%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1        | 2.94%   |
| Microstep LCD Monitor MSI G241                                       | 1        | 2.94%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 2.94%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1        | 2.94%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 2.94%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 2.94%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 2.94%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 2.94%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 2.94%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1        | 2.94%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1        | 2.94%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1        | 2.94%   |
| BenQ LCD Monitor T2200HD 5760x1080                                   | 1        | 2.94%   |
| BenQ LCD Monitor T2200HD                                             | 1        | 2.94%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1        | 2.94%   |
| ASUSTek Computer MG248 AUS24A3 1920x1080 531x299mm 24.0-inch         | 1        | 2.94%   |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                    | 1        | 2.94%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                      | 1        | 2.94%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 1        | 2.94%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 1        | 2.94%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1        | 2.94%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1        | 2.94%   |
| Acer V236HL ACR0350 1920x1080 510x290mm 23.1-inch                    | 1        | 2.94%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                    | 1        | 2.94%   |
| Unknown                                                              | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 43.75%  |
| 2560x1440 (QHD)    | 4        | 12.5%   |
| 1366x768 (WXGA)    | 3        | 9.38%   |
| 1280x1024 (SXGA)   | 2        | 6.25%   |
| 5760x1080          | 1        | 3.13%   |
| 3840x2160 (4K)     | 1        | 3.13%   |
| 2560x1080          | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1600x900 (HD+)     | 1        | 3.13%   |
| 1440x900 (WXGA+)   | 1        | 3.13%   |
| 1360x768           | 1        | 3.13%   |
| 1024x768 (XGA)     | 1        | 3.13%   |
| Unknown            | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 7        | 24.14%  |
| Unknown | 6        | 20.69%  |
| 18      | 4        | 13.79%  |
| 23      | 3        | 10.34%  |
| 21      | 2        | 6.9%    |
| 31      | 1        | 3.45%   |
| 29      | 1        | 3.45%   |
| 27      | 1        | 3.45%   |
| 22      | 1        | 3.45%   |
| 20      | 1        | 3.45%   |
| 19      | 1        | 3.45%   |
| 15      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 37.93%  |
| 401-500     | 8        | 27.59%  |
| Unknown     | 6        | 20.69%  |
| 601-700     | 2        | 6.9%    |
| 351-400     | 1        | 3.45%   |
| 301-350     | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 53.33%  |
| Unknown | 6        | 20%     |
| 16/10   | 5        | 16.67%  |
| 5/4     | 1        | 3.33%   |
| 4/3     | 1        | 3.33%   |
| 21/9    | 1        | 3.33%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 34.48%  |
| Unknown        | 6        | 20.69%  |
| 251-300        | 3        | 10.34%  |
| 151-200        | 3        | 10.34%  |
| 141-150        | 3        | 10.34%  |
| 301-350        | 2        | 6.9%    |
| 351-500        | 1        | 3.45%   |
| 101-110        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 64.29%  |
| Unknown | 6        | 21.43%  |
| 101-120 | 3        | 10.71%  |
| 161-240 | 1        | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 66.67%  |
| 2     | 8        | 29.63%  |
| 3     | 1        | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 52.5%   |
| Intel                 | 8        | 20%     |
| Qualcomm Atheros      | 2        | 5%      |
| MediaTek              | 2        | 5%      |
| Xiaomi                | 1        | 2.5%    |
| Ralink Technology     | 1        | 2.5%    |
| Linksys               | 1        | 2.5%    |
| Huawei Technologies   | 1        | 2.5%    |
| D-Link System         | 1        | 2.5%    |
| Broadcom              | 1        | 2.5%    |
| Belkin Components     | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 19       | 41.3%   |
| Intel I211 Gigabit Network Connection                                                   | 3        | 6.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 4.35%   |
| Intel Ethernet Controller I225-V                                                        | 2        | 4.35%   |
| Intel Ethernet Connection I217-LM                                                       | 2        | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 1        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 2.17%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1        | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 2.17%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 2.17%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 2.17%   |
| Intel Wireless-AC 9260                                                                  | 1        | 2.17%   |
| Intel Wireless 3165                                                                     | 1        | 2.17%   |
| Intel Wi-Fi 6 AX200                                                                     | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 2.17%   |
| Huawei COL-L29                                                                          | 1        | 2.17%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 2.17%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 29.41%  |
| Intel                 | 4        | 23.53%  |
| MediaTek              | 2        | 11.76%  |
| Ralink Technology     | 1        | 5.88%   |
| Qualcomm Atheros      | 1        | 5.88%   |
| Linksys               | 1        | 5.88%   |
| D-Link System         | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |
| Belkin Components     | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 11.76%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 5.88%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 5.88%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 5.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 5.88%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 5.88%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 5.88%   |
| Intel Wireless-AC 9260                                                                  | 1        | 5.88%   |
| Intel Wireless 3165                                                                     | 1        | 5.88%   |
| Intel Wi-Fi 6 AX200                                                                     | 1        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1        | 5.88%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 5.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 5.88%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 65.52%  |
| Intel                 | 7        | 24.14%  |
| Xiaomi                | 1        | 3.45%   |
| Qualcomm Atheros      | 1        | 3.45%   |
| Huawei Technologies   | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 65.52%  |
| Intel I211 Gigabit Network Connection                             | 3        | 10.34%  |
| Intel Ethernet Controller I225-V                                  | 2        | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 6.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 3.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 3.45%   |
| Huawei COL-L29                                                    | 1        | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 69.23%  |
| WiFi     | 12       | 30.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 70%     |
| WiFi     | 9        | 30%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 74.07%  |
| 2     | 7        | 25.93%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 70.37%  |
| Yes  | 8        | 29.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 30.77%  |
| Cambridge Silicon Radio         | 3        | 23.08%  |
| Broadcom                        | 2        | 15.38%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| Qualcomm Atheros Communications | 1        | 7.69%   |
| MediaTek                        | 1        | 7.69%   |
| ASUSTek Computer                | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 7.69%   |
| MediaTek Wireless_Device                            | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.69%   |
| Intel Bluetooth wireless interface                  | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Broadcom BCM92045B3 ROM                             | 1        | 7.69%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 7.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 34.09%  |
| AMD                 | 14       | 31.82%  |
| Nvidia              | 9        | 20.45%  |
| Blue Microphones    | 2        | 4.55%   |
| Texas Instruments   | 1        | 2.27%   |
| Tenx Technology     | 1        | 2.27%   |
| Cooler Master       | 1        | 2.27%   |
| C-Media Electronics | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 10%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 6.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 5%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.33%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 3.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 3.33%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 3.33%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.33%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1        | 1.67%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.67%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.67%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.67%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.67%   |
| Cooler Master CH321                                                        | 1        | 1.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.67%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 1.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.67%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.67%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Crucial           | 2        | 28.57%  |
| Unknown           | 1        | 14.29%  |
| Transcend         | 1        | 14.29%  |
| Patriot           | 1        | 14.29%  |
| Corsair           | 1        | 14.29%  |
| A-DATA Technology | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 14.29%  |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s         | 1        | 14.29%  |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s       | 1        | 14.29%  |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 14.29%  |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s | 1        | 14.29%  |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s     | 1        | 14.29%  |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 50%     |
| DDR3 | 3        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 4        | 57.14%  |
| 4096 | 3        | 42.86%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 28.57%  |
| 2400  | 2        | 28.57%  |
| 1600  | 2        | 28.57%  |
| 1333  | 1        | 14.29%  |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Logitech        | 4        | 44.44%  |
| MacroSilicon    | 1        | 11.11%  |
| LG Electronics  | 1        | 11.11%  |
| Hewlett-Packard | 1        | 11.11%  |
| Acer            | 1        | 11.11%  |
| A4Tech          | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| MacroSilicon ShadowCast              | 1        | 11.11%  |
| Logitech Webcam C270                 | 1        | 11.11%  |
| Logitech HD Pro Webcam C920          | 1        | 11.11%  |
| Logitech C922 Pro Stream Webcam      | 1        | 11.11%  |
| Logitech C920 PRO HD Webcam          | 1        | 11.11%  |
| LG Optimus (Various Models) MTP Mode | 1        | 11.11%  |
| HP Webcam HD 2300                    | 1        | 11.11%  |
| Acer LENOVO LBG 720P CAM             | 1        | 11.11%  |
| A4Tech FHD 1080P PC Camera           | 1        | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 24       | 88.89%  |
| 1     | 2        | 7.41%   |
| 3     | 1        | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 57.14%  |
| Multimedia controller | 1        | 14.29%  |
| Graphics card         | 1        | 14.29%  |
| Camera                | 1        | 14.29%  |

