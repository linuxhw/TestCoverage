Rocky Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 28

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad X1 Carbon 34483... | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell    | Latitude 3420               | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| HP      | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell    | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell    | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Lenovo  | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP      | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo  | Legion 5 15ARH05H 82B1      | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo  | IdeaPad 500S-14ISK 80Q3     | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo  | ThinkPad W540 20BGCTO1WW    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| HP      | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Toshiba | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Lenovo  | ThinkPad W500 406132G       | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba | Satellite E45-B             | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| Acer    | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 11        | 55%     |
| Rocky Linux 8.4 | 8         | 40%     |
| Rocky Linux 8.3 | 1         | 5%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 20        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 15%     |
| 4.18.0-348.20.1.el8_5.x86_64 | 2         | 10%     |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 10%     |
| 4.18.0-305.el8.x86_64        | 2         | 10%     |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 10%     |
| 4.18.0-305.25.1.el8_4.x86_64 | 2         | 10%     |
| 4.18.0-305.10.2.el8_4.x86_64 | 2         | 10%     |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 5%      |
| 5.10.89-1.el8.x86_64         | 1         | 5%      |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 5%      |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 5%      |
| 4.18.0-240.22.1.el8.x86_64   | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 18        | 90%     |
| 5.4.157 | 1         | 5%      |
| 5.10.89 | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 18        | 90%     |
| 5.4     | 1         | 5%      |
| 5.10    | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 14        | 70%     |
| MATE          | 2         | 10%     |
| XFCE          | 1         | 5%      |
| X-Cinnamon    | 1         | 5%      |
| KDE5          | 1         | 5%      |
| GNOME Classic | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 10        | 50%     |
| Wayland | 10        | 50%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 65%     |
| GDM     | 4         | 20%     |
| LightDM | 2         | 10%     |
| SDDM    | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 14        | 70%     |
| en_ZA | 2         | 10%     |
| de_DE | 2         | 10%     |
| pt_BR | 1         | 5%      |
| it_IT | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 14        | 70%     |
| BIOS | 6         | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 14        | 70%     |
| Ext4 | 6         | 30%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 75%     |
| GPT     | 5         | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 90%     |
| Yes       | 2         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 55%     |
| Hewlett-Packard  | 3         | 15%     |
| Toshiba          | 2         | 10%     |
| Dell             | 2         | 10%     |
| ASUSTek Computer | 1         | 5%      |
| Acer             | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 5%      |
| Toshiba Satellite E45-B                  | 1         | 5%      |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 5%      |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 5%      |
| Lenovo ThinkPad W500 406132G             | 1         | 5%      |
| Lenovo ThinkPad T420 42365H1             | 1         | 5%      |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 5%      |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 5%      |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 5%      |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 5%      |
| Lenovo IdeaPad Y410P 20216               | 1         | 5%      |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 5%      |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 5%      |
| HP ZBook 15 G3                           | 1         | 5%      |
| HP Laptop 17-ca1xxx                      | 1         | 5%      |
| HP EliteBook 840 G7 Notebook PC          | 1         | 5%      |
| Dell Latitude 5500                       | 1         | 5%      |
| Dell Latitude 3420                       | 1         | 5%      |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 5%      |
| Acer Aspire VN7-591G                     | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 25%     |
| Lenovo IdeaPad    | 4         | 20%     |
| Lenovo Legion     | 2         | 10%     |
| Dell Latitude     | 2         | 10%     |
| Toshiba TECRA     | 1         | 5%      |
| Toshiba Satellite | 1         | 5%      |
| HP ZBook          | 1         | 5%      |
| HP Laptop         | 1         | 5%      |
| HP EliteBook      | 1         | 5%      |
| ASUS ASUS         | 1         | 5%      |
| Acer Aspire       | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 20%     |
| 2019 | 3         | 15%     |
| 2014 | 3         | 15%     |
| 2021 | 2         | 10%     |
| 2016 | 2         | 10%     |
| 2018 | 1         | 5%      |
| 2015 | 1         | 5%      |
| 2013 | 1         | 5%      |
| 2012 | 1         | 5%      |
| 2011 | 1         | 5%      |
| 2009 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 6         | 30%     |
| 4.01-8.0   | 5         | 25%     |
| 16.01-24.0 | 5         | 25%     |
| 32.01-64.0 | 3         | 15%     |
| 3.01-4.0   | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 6         | 30%     |
| 3.01-4.0  | 6         | 30%     |
| 2.01-3.0  | 4         | 20%     |
| 1.01-2.0  | 3         | 15%     |
| 8.01-16.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 65%     |
| 2      | 4         | 20%     |
| 3      | 3         | 15%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 85%     |
| Yes       | 3         | 15%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 95%     |
| No        | 1         | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 90%     |
| No        | 2         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 6         | 30%     |
| South Africa | 2         | 10%     |
| Germany      | 2         | 10%     |
| Belgium      | 2         | 10%     |
| Slovakia     | 1         | 5%      |
| Poland       | 1         | 5%      |
| Malaysia     | 1         | 5%      |
| Kazakhstan   | 1         | 5%      |
| Italy        | 1         | 5%      |
| Czechia      | 1         | 5%      |
| China        | 1         | 5%      |
| Brazil       | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| ??ilina      | 1         | 5%      |
| Xi'an        | 1         | 5%      |
| Senigallia   | 1         | 5%      |
| Scarborough  | 1         | 5%      |
| Prague       | 1         | 5%      |
| Philadelphia | 1         | 5%      |
| Ottignies    | 1         | 5%      |
| Oakley       | 1         | 5%      |
| Nur-Sultan   | 1         | 5%      |
| Mossel Bay   | 1         | 5%      |
| Kutno        | 1         | 5%      |
| Johor Bahru  | 1         | 5%      |
| Ja??         | 1         | 5%      |
| Houston      | 1         | 5%      |
| Forest       | 1         | 5%      |
| Dreieich     | 1         | 5%      |
| Centurion    | 1         | 5%      |
| Brussels     | 1         | 5%      |
| Berlin       | 1         | 5%      |
| Ashburn      | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 8         | 10     | 25%     |
| Toshiba                 | 3         | 3      | 9.38%   |
| WDC                     | 2         | 2      | 6.25%   |
| Unknown                 | 2         | 2      | 6.25%   |
| Kingston                | 2         | 2      | 6.25%   |
| Union Memory (Shenzhen) | 1         | 1      | 3.13%   |
| UMIS                    | 1         | 1      | 3.13%   |
| StoreJet                | 1         | 1      | 3.13%   |
| SK hynix                | 1         | 2      | 3.13%   |
| Seagate                 | 1         | 1      | 3.13%   |
| SanDisk                 | 1         | 1      | 3.13%   |
| LITEONIT                | 1         | 1      | 3.13%   |
| LITEON                  | 1         | 1      | 3.13%   |
| Intel                   | 1         | 1      | 3.13%   |
| Hitachi                 | 1         | 1      | 3.13%   |
| Fujitsu                 | 1         | 1      | 3.13%   |
| Dogfish                 | 1         | 1      | 3.13%   |
| AGI                     | 1         | 1      | 3.13%   |
| ADATA Technology        | 1         | 1      | 3.13%   |
| A-DATA Technology       | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 2.94%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 2.94%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 2.94%   |
| Unknown MMC Card  64GB                       | 1         | 2.94%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.94%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 2.94%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 2.94%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 2.94%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.94%   |
| StoreJet Disk 2TB                            | 1         | 2.94%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 2.94%   |
| SK hynix BC511 NVMe 512GB                    | 1         | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.94%   |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 2.94%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 2.94%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 2.94%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 2.94%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 2.94%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 2.94%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 2.94%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 2.94%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 2.94%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 2.94%   |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 2.94%   |
| LITEON CV1-DB256 256GB SSD                   | 1         | 2.94%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 2.94%   |
| Kingston NVMe SSD Drive 512GB                | 1         | 2.94%   |
| Intel NVMe SSD Drive 512GB                   | 1         | 2.94%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 2.94%   |
| Fujitsu MHV2080BH 80GB                       | 1         | 2.94%   |
| Dogfish SSD 2TB                              | 1         | 2.94%   |
| AGI AGI960G18AI238 960GB                     | 1         | 2.94%   |
| ADATA NVMe SSD Drive 512GB                   | 1         | 2.94%   |
| A-DATA SWORDFISH 1TB                         | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 28.57%  |
| Unknown  | 1         | 1      | 14.29%  |
| StoreJet | 1         | 1      | 14.29%  |
| Seagate  | 1         | 1      | 14.29%  |
| Hitachi  | 1         | 1      | 14.29%  |
| Fujitsu  | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 41.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| SanDisk             | 1         | 1      | 8.33%   |
| LITEONIT            | 1         | 1      | 8.33%   |
| LITEON              | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Dogfish             | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 10        | 13     | 38.46%  |
| SSD     | 9         | 13     | 34.62%  |
| HDD     | 5         | 7      | 19.23%  |
| MMC     | 1         | 1      | 3.85%   |
| Unknown | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 18     | 46.15%  |
| NVMe | 10        | 13     | 38.46%  |
| SAS  | 3         | 3      | 11.54%  |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 9      | 41.18%  |
| 0.51-1.0   | 6         | 6      | 35.29%  |
| 1.01-2.0   | 3         | 3      | 17.65%  |
| 3.01-4.0   | 1         | 2      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 40%     |
| 101-250        | 6         | 30%     |
| 501-1000       | 2         | 10%     |
| More than 3000 | 1         | 5%      |
| 2001-3000      | 1         | 5%      |
| 1001-2000      | 1         | 5%      |
| 51-100         | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 7         | 35%     |
| 21-50     | 4         | 20%     |
| 101-250   | 4         | 20%     |
| 51-100    | 2         | 10%     |
| 251-500   | 1         | 5%      |
| 1001-2000 | 1         | 5%      |
| 501-1000  | 1         | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 15        | 24     | 68.18%  |
| Works    | 7         | 11     | 31.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 14        | 53.85%  |
| Samsung Electronics          | 3         | 11.54%  |
| AMD                          | 3         | 11.54%  |
| Union Memory (Shenzhen)      | 1         | 3.85%   |
| Toshiba America Info Systems | 1         | 3.85%   |
| SK hynix                     | 1         | 3.85%   |
| Realtek Semiconductor        | 1         | 3.85%   |
| Kingston Technology Company  | 1         | 3.85%   |
| ADATA Technology             | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 10.34%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 10.34%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 6.9%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 3.45%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 3.45%   |
| SK hynix BC511                                                                         | 1         | 3.45%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 3.45%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 3.45%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 3.45%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 3.45%   |
| Intel SSD 660P Series                                                                  | 1         | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 3.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 3.45%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 3.45%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 51.85%  |
| NVMe | 10        | 37.04%  |
| IDE  | 3         | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 75%     |
| AMD    | 5         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 10%     |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 5%      |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 5%      |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 5%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 5%      |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 5%      |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 5%      |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 5%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 5%      |
| Intel Core i5-3427U CPU @ 1.80GHz             | 1         | 5%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 5%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 5%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 5%      |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 5%      |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 5%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 9         | 45%     |
| Intel Core i5    | 4         | 20%     |
| Other            | 2         | 10%     |
| AMD Ryzen 5      | 2         | 10%     |
| Intel Core 2 Duo | 1         | 5%      |
| AMD Ryzen 7      | 1         | 5%      |
| AMD Ryzen 5 PRO  | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 10        | 50%     |
| 2      | 6         | 30%     |
| 6      | 3         | 15%     |
| 8      | 1         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 85%     |
| 1      | 3         | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 20%     |
| 0x806ec    | 2         | 10%     |
| 0x506e3    | 2         | 10%     |
| 0x08600104 | 2         | 10%     |
| 0xa0652    | 1         | 5%      |
| 0x806c1    | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x40651    | 1         | 5%      |
| 0x306a9    | 1         | 5%      |
| 0x206a7    | 1         | 5%      |
| 0x10676    | 1         | 5%      |
| 0x0a50000c | 1         | 5%      |
| 0x08108102 | 1         | 5%      |
| 0x06006705 | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 5         | 25%     |
| Skylake     | 3         | 15%     |
| Zen 2       | 2         | 10%     |
| KabyLake    | 2         | 10%     |
| Zen+        | 1         | 5%      |
| Zen 3       | 1         | 5%      |
| TigerLake   | 1         | 5%      |
| SandyBridge | 1         | 5%      |
| Penryn      | 1         | 5%      |
| IvyBridge   | 1         | 5%      |
| Excavator   | 1         | 5%      |
| CometLake   | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 43.33%  |
| Nvidia | 12        | 40%     |
| AMD    | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 10%     |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 6.67%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 2         | 6.67%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 3.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 3.33%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 3.33%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 3.33%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 3.33%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 3.33%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 3.33%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 3.33%   |
| Intel HD Graphics 530                                                     | 1         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 3.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.33%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 3.33%   |
| AMD Renoir                                                                | 1         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.33%   |
| AMD Cezanne                                                               | 1         | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 8         | 40%     |
| 1 x Intel      | 4         | 20%     |
| 1 x Nvidia     | 3         | 15%     |
| 1 x AMD        | 3         | 15%     |
| Intel + AMD    | 1         | 5%      |
| AMD + Nvidia   | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 14        | 70%     |
| Proprietary | 6         | 30%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 40%     |
| 1.01-2.0   | 4         | 20%     |
| 0.01-0.5   | 3         | 15%     |
| 5.01-6.0   | 2         | 10%     |
| 3.01-4.0   | 2         | 10%     |
| 0.51-1.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 15.15%  |
| AU Optronics        | 5         | 15.15%  |
| Goldstar            | 4         | 12.12%  |
| Dell                | 4         | 12.12%  |
| BOE                 | 4         | 12.12%  |
| Chimei Innolux      | 3         | 9.09%   |
| Philips             | 2         | 6.06%   |
| AOC                 | 2         | 6.06%   |
| Samsung Electronics | 1         | 3.03%   |
| PANDA               | 1         | 3.03%   |
| Panasonic           | 1         | 3.03%   |
| Lenovo              | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 2.86%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 2.86%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 2.86%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 2.86%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 2.86%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 2.86%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 2.86%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4055 1920x1200 330x210mm 15.4-inch              | 1         | 2.86%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 2.86%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 2.86%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 2.86%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 2.86%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 2.86%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 2.86%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 2.86%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 2.86%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 2.86%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 2.86%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1         | 2.86%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 14        | 51.85%  |
| 1600x900 (HD+)     | 3         | 11.11%  |
| 3840x2160 (4K)     | 2         | 7.41%   |
| 1680x1050 (WSXGA+) | 2         | 7.41%   |
| 3440x1440          | 1         | 3.7%    |
| 2560x1440 (QHD)    | 1         | 3.7%    |
| 2560x1080          | 1         | 3.7%    |
| 1920x1200 (WUXGA)  | 1         | 3.7%    |
| 1366x768 (WXGA)    | 1         | 3.7%    |
| Unknown            | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 27.27%  |
| 14     | 7         | 21.21%  |
| 27     | 5         | 15.15%  |
| 21     | 3         | 9.09%   |
| 34     | 2         | 6.06%   |
| 17     | 2         | 6.06%   |
| 13     | 2         | 6.06%   |
| 24     | 1         | 3.03%   |
| 23     | 1         | 3.03%   |
| 22     | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 54.55%  |
| 501-600     | 6         | 18.18%  |
| 401-500     | 5         | 15.15%  |
| 701-800     | 2         | 6.06%   |
| 351-400     | 2         | 6.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 79.17%  |
| 21/9  | 2         | 8.33%   |
| 16/10 | 2         | 8.33%   |
| 3/2   | 1         | 4.17%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 28.13%  |
| 101-110        | 9         | 28.13%  |
| 301-350        | 5         | 15.63%  |
| 201-250        | 4         | 12.5%   |
| 351-500        | 2         | 6.25%   |
| 121-130        | 2         | 6.25%   |
| 151-200        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 56.25%  |
| 101-120       | 6         | 18.75%  |
| 51-100        | 6         | 18.75%  |
| More than 240 | 1         | 3.13%   |
| 161-240       | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 9         | 45%     |
| 2     | 8         | 40%     |
| 3     | 2         | 10%     |
| 4     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 53.13%  |
| Realtek Semiconductor | 11        | 34.38%  |
| Qualcomm Atheros      | 2         | 6.25%   |
| MediaTek              | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 25%     |
| Intel Wireless 7260                                               | 4         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5%      |
| Intel Wireless 8260                                               | 2         | 5%      |
| Intel Ethernet Connection I217-LM                                 | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 5%      |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.5%    |
| Intel Wireless 7265                                               | 1         | 2.5%    |
| Intel Wireless 3160                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.5%    |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 85%     |
| Realtek Semiconductor | 1         | 5%      |
| Qualcomm Atheros      | 1         | 5%      |
| MediaTek              | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 4         | 20%     |
| Intel Wireless 8260                                           | 2         | 10%     |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 10%     |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 5%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 5%      |
| Intel Wireless 7265                                           | 1         | 5%      |
| Intel Wireless 3160                                           | 1         | 5%      |
| Intel Wi-Fi 6 AX201                                           | 1         | 5%      |
| Intel Wi-Fi 6 AX200                                           | 1         | 5%      |
| Intel Ultimate N WiFi Link 5300                               | 1         | 5%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 5%      |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 5%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 57.89%  |
| Intel                 | 6         | 31.58%  |
| Qualcomm Atheros      | 1         | 5.26%   |
| Broadcom              | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 50%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 10%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 10%     |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 5%      |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 5%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5%      |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 52.63%  |
| Ethernet | 18        | 47.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 68.18%  |
| Ethernet | 7         | 31.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 80%     |
| 1     | 3         | 15%     |
| 3     | 1         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 13        | 65%     |
| Yes  | 7         | 35%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 77.78%  |
| Realtek Semiconductor           | 1         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 9         | 50%     |
| Intel Bluetooth Device                             | 3         | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 5.56%   |
| Intel AX200 Bluetooth                              | 1         | 5.56%   |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 15        | 44.12%  |
| Nvidia              | 8         | 23.53%  |
| AMD                 | 5         | 14.71%  |
| Logitech            | 2         | 5.88%   |
| Hewlett-Packard     | 1         | 2.94%   |
| GN Netcom           | 1         | 2.94%   |
| Conexant Systems    | 1         | 2.94%   |
| C-Media Electronics | 1         | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 9.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 7.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 4.76%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 4.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 4.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.38%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.38%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 2.38%   |
| Logitech Stereo H650e                                                      | 1         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.38%   |
| Hewlett-Packard USB Audio                                                  | 1         | 2.38%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 2.38%   |
| Conexant Systems HP Dock Audio                                             | 1         | 2.38%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.38%   |
| AMD High Definition Audio Controller                                       | 1         | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 50%     |
| SK hynix            | 2         | 33.33%  |
| Crucial             | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s  | 1         | 16.67%  |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s | 1         | 16.67%  |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 16.67%  |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 16.67%  |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s  | 1         | 16.67%  |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s | 1         | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 3         | 50%     |
| DDR3   | 2         | 33.33%  |
| LPDDR4 | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 6         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 66.67%  |
| 16384 | 2         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 50%     |
| 4266  | 1         | 16.67%  |
| 3200  | 1         | 16.67%  |
| 1600  | 1         | 16.67%  |

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


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 6         | 28.57%  |
| Syntek                      | 3         | 14.29%  |
| Realtek Semiconductor       | 2         | 9.52%   |
| IMC Networks                | 2         | 9.52%   |
| Quanta                      | 1         | 4.76%   |
| Microdia                    | 1         | 4.76%   |
| Luxvisions Innotech Limited | 1         | 4.76%   |
| Logitech                    | 1         | 4.76%   |
| Lenovo                      | 1         | 4.76%   |
| Intel                       | 1         | 4.76%   |
| Apple                       | 1         | 4.76%   |
| Acer                        | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 19.05%  |
| Syntek Lenovo EasyCamera                 | 2         | 9.52%   |
| Syntek Integrated Camera                 | 1         | 4.76%   |
| Realtek Integrated_Webcam_HD             | 1         | 4.76%   |
| Realtek EasyCamera                       | 1         | 4.76%   |
| Quanta HP Webcam                         | 1         | 4.76%   |
| Microdia Integrated_Webcam_HD            | 1         | 4.76%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 4.76%   |
| Logitech BRIO Ultra HD Webcam            | 1         | 4.76%   |
| Lenovo UVC Camera                        | 1         | 4.76%   |
| Intel RealSense 3D Camera (Front F200)   | 1         | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 4.76%   |
| IMC Networks TOSHIBA Web Camera - HD     | 1         | 4.76%   |
| Chicony HP HD Camera                     | 1         | 4.76%   |
| Chicony HD WebCam                        | 1         | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE                | 1         | 4.76%   |
| Acer Integrated Camera                   | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Synaptics        | 1         | 20%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 20%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| AuthenTec AES2810                                         | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |
| Broadcom 58200                       | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 9         | 45%     |
| 1     | 8         | 40%     |
| 2     | 3         | 15%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 35.71%  |
| Net/wireless          | 2         | 14.29%  |
| Graphics card         | 2         | 14.29%  |
| Chipcard              | 2         | 14.29%  |
| Net/ethernet          | 1         | 7.14%   |
| Multimedia controller | 1         | 7.14%   |
| Card reader           | 1         | 7.14%   |

