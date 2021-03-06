Sparky - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 25

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Intel    | H61                  | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP       | 3641h                | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| Intel    | H55                  | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI      | B450 GAMING PLUS MAX | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| MSI      | H310M PRO-VDH PLUS   | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI      | H310M PRO-VDH PLUS   | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP       | 805B                 | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte | H97-Gaming 3         | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| MSI      | A68HM-E33 V2         | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Gigabyte | H410M H              | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron | 2AC2A                | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron | 2AC2A                | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Pegatron | 2AC2A                | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP       | 8056                 | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Intel    | DG41TY AAE47335-300  | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Gigabyte | M68M-S2P             | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| Unknown  | 4CoreDX90-VSTA       | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Gigabyte | G41M-ES2L            | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte | G41M-ES2L            | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell     | 039VR8 A00           | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Vorke    | V1 Plus              | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel    | DG43RK AAE78175-402  | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| ASRock   | H61M-VG4             | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Sparky 6    | 7        | 38.89%  |
| Sparky 5.12 | 3        | 16.67%  |
| Sparky 6.3  | 2        | 11.11%  |
| Sparky 6.2  | 2        | 11.11%  |
| Sparky 6.1  | 2        | 11.11%  |
| Sparky 6.0  | 1        | 5.56%   |
| Sparky 5.10 | 1        | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 17       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.9.13-sparky-amd64 | 1        | 5.56%   |
| 5.7.2-sparky-amd64  | 1        | 5.56%   |
| 5.6.0-2-amd64       | 1        | 5.56%   |
| 5.17.3-sparky-amd64 | 1        | 5.56%   |
| 5.16.5-sparky-amd64 | 1        | 5.56%   |
| 5.10.0-9-amd64      | 1        | 5.56%   |
| 5.10.0-8-amd64      | 1        | 5.56%   |
| 5.10.0-7-amd64      | 1        | 5.56%   |
| 5.10.0-6-amd64      | 1        | 5.56%   |
| 5.10.0-3-amd64      | 1        | 5.56%   |
| 5.10.0-2-amd64      | 1        | 5.56%   |
| 5.10.0-14-amd64     | 1        | 5.56%   |
| 5.10.0-12-amd64     | 1        | 5.56%   |
| 5.10.0-11-686       | 1        | 5.56%   |
| 4.19.0-8-amd64      | 1        | 5.56%   |
| 4.19.0-12-amd64     | 1        | 5.56%   |
| 4.19.0-10-amd64     | 1        | 5.56%   |
| 4.19.0-10-686       | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 9        | 50%     |
| 4.19.0  | 4        | 22.22%  |
| 5.9.13  | 1        | 5.56%   |
| 5.7.2   | 1        | 5.56%   |
| 5.6.0   | 1        | 5.56%   |
| 5.17.3  | 1        | 5.56%   |
| 5.16.5  | 1        | 5.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 9        | 50%     |
| 4.19    | 4        | 22.22%  |
| 5.9     | 1        | 5.56%   |
| 5.7     | 1        | 5.56%   |
| 5.6     | 1        | 5.56%   |
| 5.17    | 1        | 5.56%   |
| 5.16    | 1        | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 88.24%  |
| i686   | 2        | 11.76%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 6        | 35.29%  |
| LXQt             | 5        | 29.41%  |
| X-Cinnamon       | 1        | 5.88%   |
| lightdm-xsession | 1        | 5.88%   |
| KDE5             | 1        | 5.88%   |
| ICEWM            | 1        | 5.88%   |
| GNOME            | 1        | 5.88%   |
| Unknown          | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 17       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 6        | 35.29%  |
| Unknown | 6        | 35.29%  |
| SDDM    | 4        | 23.53%  |
| LightDM | 1        | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 4        | 23.53%  |
| pt_BR | 3        | 17.65%  |
| es_ES | 2        | 11.76%  |
| sv_SE | 1        | 5.88%   |
| es_US | 1        | 5.88%   |
| es_AR | 1        | 5.88%   |
| en_ZA | 1        | 5.88%   |
| en_GB | 1        | 5.88%   |
| en_DK | 1        | 5.88%   |
| de_CH | 1        | 5.88%   |
| cs_CZ | 1        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 64.71%  |
| EFI  | 6        | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 16       | 94.12%  |
| Zfs  | 1        | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 6        | 35.29%  |
| Unknown | 6        | 35.29%  |
| MBR     | 5        | 29.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 82.35%  |
| Yes       | 3        | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 4        | 23.53%  |
| Gigabyte Technology | 4        | 23.53%  |
| MSI                 | 3        | 17.65%  |
| Hewlett-Packard     | 3        | 17.65%  |
| Dell                | 1        | 5.88%   |
| ASUSTek Computer    | 1        | 5.88%   |
| Unknown             | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| MSI MS-7C09                | 1        | 5.88%   |
| MSI MS-7B86                | 1        | 5.88%   |
| MSI MS-7721                | 1        | 5.88%   |
| Intel H61                  | 1        | 5.88%   |
| Intel H55                  | 1        | 5.88%   |
| Intel DG43RK AAE78175-402  | 1        | 5.88%   |
| Intel DG41TY AAE47335-300  | 1        | 5.88%   |
| HP t5740                   | 1        | 5.88%   |
| HP EliteDesk 800 G2 DM 65W | 1        | 5.88%   |
| HP EliteDesk 705 G2 MINI   | 1        | 5.88%   |
| Gigabyte M68M-S2P          | 1        | 5.88%   |
| Gigabyte H97-Gaming 3      | 1        | 5.88%   |
| Gigabyte H410M H           | 1        | 5.88%   |
| Gigabyte G41M-ES2L         | 1        | 5.88%   |
| Dell OptiPlex 580          | 1        | 5.88%   |
| ASUS CROSSHAIR VI HERO     | 1        | 5.88%   |
| Unknown                    | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP EliteDesk        | 2        | 11.76%  |
| MSI MS-7C09         | 1        | 5.88%   |
| MSI MS-7B86         | 1        | 5.88%   |
| MSI MS-7721         | 1        | 5.88%   |
| Intel H61           | 1        | 5.88%   |
| Intel H55           | 1        | 5.88%   |
| Intel DG43RK        | 1        | 5.88%   |
| Intel DG41TY        | 1        | 5.88%   |
| HP t5740            | 1        | 5.88%   |
| Gigabyte M68M-S2P   | 1        | 5.88%   |
| Gigabyte H97-Gaming | 1        | 5.88%   |
| Gigabyte H410M      | 1        | 5.88%   |
| Gigabyte G41M-ES2L  | 1        | 5.88%   |
| Dell OptiPlex       | 1        | 5.88%   |
| ASUS CROSSHAIR      | 1        | 5.88%   |
| Unknown             | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 4        | 23.53%  |
| 2018 | 2        | 11.76%  |
| 2015 | 2        | 11.76%  |
| 2014 | 2        | 11.76%  |
| 2021 | 1        | 5.88%   |
| 2020 | 1        | 5.88%   |
| 2019 | 1        | 5.88%   |
| 2017 | 1        | 5.88%   |
| 2012 | 1        | 5.88%   |
| 2010 | 1        | 5.88%   |
| 2007 | 1        | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 17       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 17       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 5        | 29.41%  |
| 3.01-4.0   | 4        | 23.53%  |
| 4.01-8.0   | 3        | 17.65%  |
| 1.01-2.0   | 2        | 11.76%  |
| 24.01-32.0 | 1        | 5.88%   |
| 2.01-3.0   | 1        | 5.88%   |
| 8.01-16.0  | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 12       | 66.67%  |
| 4.01-8.0 | 2        | 11.11%  |
| 2.01-3.0 | 2        | 11.11%  |
| 0.51-1.0 | 2        | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 61.11%  |
| 2      | 4        | 22.22%  |
| 4      | 2        | 11.11%  |
| 3      | 1        | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 94.12%  |
| No        | 1        | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 88.24%  |
| Yes       | 2        | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 3        | 17.65%  |
| Indonesia    | 2        | 11.76%  |
| Argentina    | 2        | 11.76%  |
| Venezuela    | 1        | 5.88%   |
| UK           | 1        | 5.88%   |
| Switzerland  | 1        | 5.88%   |
| Sweden       | 1        | 5.88%   |
| Spain        | 1        | 5.88%   |
| South Africa | 1        | 5.88%   |
| Lebanon      | 1        | 5.88%   |
| Germany      | 1        | 5.88%   |
| France       | 1        | 5.88%   |
| Czechia      | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Woking           | 1        | 5.88%   |
| Surabaya         | 1        | 5.88%   |
| Sin el Fil       | 1        | 5.88%   |
| San Crist??bal   | 1        | 5.88%   |
| Rosario          | 1        | 5.88%   |
| Rio de Janeiro   | 1        | 5.88%   |
| Rio Claro        | 1        | 5.88%   |
| Posadas          | 1        | 5.88%   |
| Mnisek pod Brdy  | 1        | 5.88%   |
| Kage             | 1        | 5.88%   |
| Grabs            | 1        | 5.88%   |
| Fuveau           | 1        | 5.88%   |
| Frankfurt (Oder) | 1        | 5.88%   |
| Duque de Caxias  | 1        | 5.88%   |
| Cape Town        | 1        | 5.88%   |
| Calanda          | 1        | 5.88%   |
| Bandung          | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 29.17%  |
| Samsung Electronics | 5        | 11     | 20.83%  |
| Seagate             | 4        | 5      | 16.67%  |
| Kingston            | 3        | 3      | 12.5%   |
| XPG                 | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 1      | 4.17%   |
| HGST                | 1        | 1      | 4.17%   |
| Gigabyte Technology | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung HD161GJ 160GB                | 2        | 7.14%   |
| XPG GAMMIX S11 Pro 1TB               | 1        | 3.57%   |
| WDC WD800JD-08MSA1 80GB              | 1        | 3.57%   |
| WDC WD5000AVVS-63ZWB0 500GB          | 1        | 3.57%   |
| WDC WD5000AAKS-75V0A0 500GB          | 1        | 3.57%   |
| WDC WD2500AAKX-07U6AA0 250GB         | 1        | 3.57%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1        | 3.57%   |
| WDC WD1600AAJS-08L7A0 160GB          | 1        | 3.57%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 3.57%   |
| Seagate ST9250315AS 250GB            | 1        | 3.57%   |
| Seagate ST500LT012-1DG142 500GB      | 1        | 3.57%   |
| Seagate ST3500312CS 500GB            | 1        | 3.57%   |
| Seagate ST3320418AS 320GB            | 1        | 3.57%   |
| Seagate ST2000VM003-1ET164 2TB       | 1        | 3.57%   |
| Samsung SSD 850 EVO 500GB            | 1        | 3.57%   |
| Samsung SSD 850 EVO 250GB            | 1        | 3.57%   |
| Samsung MZVPV256HDGL-000H1 256GB     | 1        | 3.57%   |
| Samsung HN-M320MBB 320GB             | 1        | 3.57%   |
| Samsung HD753LJ 752GB                | 1        | 3.57%   |
| Samsung HD154UI 1TB                  | 1        | 3.57%   |
| Kingston SV300S37A480G 480GB SSD     | 1        | 3.57%   |
| Kingston SA400S37120G 120GB SSD      | 1        | 3.57%   |
| Kingston SA400M8240G 240GB SSD       | 1        | 3.57%   |
| Intel SSDSA2BW120G3H 120GB           | 1        | 3.57%   |
| Hitachi HTS543232A7A384 320GB        | 1        | 3.57%   |
| HGST HTS545050A7E380 500GB           | 1        | 3.57%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 1        | 3.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 43.75%  |
| Seagate             | 4        | 5      | 25%     |
| Samsung Electronics | 3        | 7      | 18.75%  |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 3        | 3      | 42.86%  |
| Samsung Electronics | 2        | 3      | 28.57%  |
| Intel               | 1        | 1      | 14.29%  |
| Gigabyte Technology | 1        | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 21     | 60.87%  |
| SSD  | 7        | 8      | 30.43%  |
| NVMe | 2        | 2      | 8.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 29     | 90%     |
| NVMe | 2        | 2      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 23     | 85%     |
| 0.51-1.0   | 2        | 5      | 10%     |
| 1.01-2.0   | 1        | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 4        | 22.22%  |
| 101-250    | 4        | 22.22%  |
| 501-1000   | 3        | 16.67%  |
| 51-100     | 3        | 16.67%  |
| 2001-3000  | 2        | 11.11%  |
| 1-20       | 1        | 5.56%   |
| Unknown    | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 9        | 50%     |
| 21-50     | 2        | 11.11%  |
| 51-100    | 2        | 11.11%  |
| 251-500   | 1        | 5.56%   |
| 101-250   | 1        | 5.56%   |
| 1001-2000 | 1        | 5.56%   |
| 501-1000  | 1        | 5.56%   |
| Unknown   | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB | 1        | 1      | 33.33%  |
| WDC WD1600AAJS-08L7A0 160GB | 1        | 1      | 33.33%  |
| Seagate ST9250315AS 250GB   | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Works    | 11       | 15     | 55%     |
| Detected | 6        | 13     | 30%     |
| Malfunc  | 3        | 3      | 15%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 50%     |
| AMD                      | 5        | 25%     |
| VIA Technologies         | 1        | 5%      |
| Samsung Electronics      | 1        | 5%      |
| Nvidia                   | 1        | 5%      |
| Marvell Technology Group | 1        | 5%      |
| ADATA Technology         | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4        | 14.81%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 7.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 3.7%    |
| VIA VT8237A SATA 2-Port Controller                                            | 1        | 3.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1        | 3.7%    |
| Nvidia MCP61 SATA Controller                                                  | 1        | 3.7%    |
| Nvidia MCP61 IDE                                                              | 1        | 3.7%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                     | 1        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 3.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 3.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 3.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1        | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 3.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 3.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1        | 3.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 3.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 3.7%    |
| AMD X370 Series Chipset SATA Controller                                       | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 52.38%  |
| IDE  | 7        | 33.33%  |
| NVMe | 2        | 9.52%   |
| RAID | 1        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 64.71%  |
| AMD    | 6        | 35.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Pentium Gold G5400 CPU @ 3.70GHz       | 1        | 5.88%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz  | 1        | 5.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 5.88%   |
| Intel Core i7 CPU 860 @ 2.80GHz              | 1        | 5.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz             | 1        | 5.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1        | 5.88%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1        | 5.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 5.88%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 5.88%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz         | 1        | 5.88%   |
| Intel Atom CPU N280 @ 1.66GHz                | 1        | 5.88%   |
| AMD Sempron 145 Processor                    | 1        | 5.88%   |
| AMD Ryzen 7 1800X Eight-Core Processor       | 1        | 5.88%   |
| AMD Ryzen 3 3100 4-Core Processor            | 1        | 5.88%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G  | 1        | 5.88%   |
| AMD Athlon II X2 B22 Processor               | 1        | 5.88%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 3        | 17.65%  |
| Intel Core i7           | 2        | 11.76%  |
| Intel Core 2 Duo        | 2        | 11.76%  |
| Intel Pentium Gold      | 1        | 5.88%   |
| Intel Pentium Dual-Core | 1        | 5.88%   |
| Intel Core 2 Quad       | 1        | 5.88%   |
| Intel Atom              | 1        | 5.88%   |
| AMD Sempron             | 1        | 5.88%   |
| AMD Ryzen 7             | 1        | 5.88%   |
| AMD Ryzen 3             | 1        | 5.88%   |
| AMD PRO A8              | 1        | 5.88%   |
| AMD Athlon II X2        | 1        | 5.88%   |
| AMD A6                  | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 35.29%  |
| 2      | 6        | 35.29%  |
| 1      | 3        | 17.65%  |
| 8      | 1        | 5.88%   |
| 6      | 1        | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 52.94%  |
| 2      | 8        | 47.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 94.12%  |
| 32-bit         | 1        | 5.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 23.53%  |
| 0x0600611a | 2        | 11.76%  |
| 0xa0653    | 1        | 5.88%   |
| 0x6fd      | 1        | 5.88%   |
| 0x6fb      | 1        | 5.88%   |
| 0x506e3    | 1        | 5.88%   |
| 0x306c3    | 1        | 5.88%   |
| 0x306a9    | 1        | 5.88%   |
| 0x106e5    | 1        | 5.88%   |
| 0x1067a    | 1        | 5.88%   |
| 0x08701021 | 1        | 5.88%   |
| 0x08001138 | 1        | 5.88%   |
| 0x010000c8 | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Penryn    | 2        | 11.76%  |
| K10       | 2        | 11.76%  |
| Excavator | 2        | 11.76%  |
| Core      | 2        | 11.76%  |
| Zen 2     | 1        | 5.88%   |
| Zen       | 1        | 5.88%   |
| Skylake   | 1        | 5.88%   |
| Nehalem   | 1        | 5.88%   |
| KabyLake  | 1        | 5.88%   |
| IvyBridge | 1        | 5.88%   |
| Haswell   | 1        | 5.88%   |
| CometLake | 1        | 5.88%   |
| Bonnell   | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 8        | 42.11%  |
| Intel            | 7        | 36.84%  |
| Nvidia           | 3        | 15.79%  |
| VIA Technologies | 1        | 5.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 10.53%  |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 10.53%  |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.26%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5.26%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 5.26%   |
| Intel HD Graphics 530                                                       | 1        | 5.26%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 5.26%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 5.26%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 5.26%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 5.26%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 5.26%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 5.26%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 5.26%   |
| AMD Barts LE [Radeon HD 6790]                                               | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 7        | 41.18%  |
| 1 x Intel      | 6        | 35.29%  |
| 1 x Nvidia     | 2        | 11.76%  |
| 1 x VIA        | 1        | 5.88%   |
| Intel + Nvidia | 1        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 82.35%  |
| Unknown     | 2        | 11.76%  |
| Proprietary | 1        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 58.82%  |
| 0.51-1.0   | 2        | 11.76%  |
| 0.01-0.5   | 2        | 11.76%  |
| 7.01-8.0   | 1        | 5.88%   |
| 3.01-4.0   | 1        | 5.88%   |
| 1.01-2.0   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 23.53%  |
| Goldstar            | 4        | 23.53%  |
| Dell                | 3        | 17.65%  |
| BenQ                | 2        | 11.76%  |
| AOC                 | 2        | 11.76%  |
| Unknown             | 1        | 5.88%   |
| JCH                 | 1        | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 5.26%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch | 1        | 5.26%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 1        | 5.26%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch    | 1        | 5.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1        | 5.26%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                        | 1        | 5.26%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 5.26%   |
| Goldstar TV GSM9CF6 1360x768 700x390mm 31.5-inch                     | 1        | 5.26%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                 | 1        | 5.26%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1        | 5.26%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 1        | 5.26%   |
| Dell LCD Monitor S2715H 3840x1080                                    | 1        | 5.26%   |
| Dell LCD Monitor S2715H                                              | 1        | 5.26%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                     | 1        | 5.26%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                    | 1        | 5.26%   |
| BenQ FP202WA BNQ76C2 1680x1050 376x301mm 19.0-inch                   | 1        | 5.26%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                     | 1        | 5.26%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                      | 1        | 5.26%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 31.58%  |
| 1280x1024 (SXGA)   | 3        | 15.79%  |
| 1366x768 (WXGA)    | 2        | 10.53%  |
| 3840x1080          | 1        | 5.26%   |
| 2288x1287          | 1        | 5.26%   |
| 1680x1050 (WSXGA+) | 1        | 5.26%   |
| 1600x900 (HD+)     | 1        | 5.26%   |
| 1360x768           | 1        | 5.26%   |
| 1280x960           | 1        | 5.26%   |
| 1024x768 (XGA)     | 1        | 5.26%   |
| Unknown            | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 22.22%  |
| 17      | 3        | 16.67%  |
| 21      | 2        | 11.11%  |
| 20      | 2        | 11.11%  |
| 18      | 2        | 11.11%  |
| 142     | 1        | 5.56%   |
| 72      | 1        | 5.56%   |
| 16      | 1        | 5.56%   |
| 13      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 6        | 33.33%  |
| 501-600        | 4        | 22.22%  |
| 301-350        | 4        | 22.22%  |
| More than 2000 | 1        | 5.56%   |
| 201-300        | 1        | 5.56%   |
| 1501-2000      | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 55.56%  |
| 5/4     | 3        | 16.67%  |
| 4/3     | 2        | 11.11%  |
| 16/10   | 1        | 5.56%   |
| 1.00    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 5        | 27.78%  |
| 201-250        | 4        | 22.22%  |
| 151-200        | 4        | 22.22%  |
| More than 1000 | 2        | 11.11%  |
| 81-90          | 1        | 5.56%   |
| 121-130        | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 70.59%  |
| 1-50    | 2        | 11.76%  |
| 101-120 | 2        | 11.76%  |
| Unknown | 1        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 82.35%  |
| 2     | 3        | 17.65%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 34.78%  |
| Qualcomm Atheros      | 3        | 13.04%  |
| Intel                 | 3        | 13.04%  |
| Ralink Technology     | 2        | 8.7%    |
| Broadcom Limited      | 2        | 8.7%    |
| VIA Technologies      | 1        | 4.35%   |
| TP-Link               | 1        | 4.35%   |
| Nvidia                | 1        | 4.35%   |
| D-Link System         | 1        | 4.35%   |
| Broadcom              | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                           | 6        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 8.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 4.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 4.17%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 4.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 4.17%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 4.17%   |
| Nvidia MCP61 Ethernet                                                                       | 1        | 4.17%   |
| Intel Wireless 8260                                                                         | 1        | 4.17%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                                                       | 1        | 4.17%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 4.17%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 4.17%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                            | 1        | 4.17%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                                    | 1        | 4.17%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                                     | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Ralink Technology | 2        | 28.57%  |
| Qualcomm Atheros  | 2        | 28.57%  |
| TP-Link           | 1        | 14.29%  |
| Intel             | 1        | 14.29%  |
| D-Link System     | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 14.29%  |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 14.29%  |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 14.29%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 14.29%  |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 14.29%  |
| Intel Wireless 8260                                                                         | 1        | 14.29%  |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 47.06%  |
| Intel                 | 3        | 17.65%  |
| Broadcom Limited      | 2        | 11.76%  |
| VIA Technologies      | 1        | 5.88%   |
| Qualcomm Atheros      | 1        | 5.88%   |
| Nvidia                | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 35.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 11.76%  |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 5.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 5.88%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 1        | 5.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 5.88%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 5.88%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 5.88%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 5.88%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 69.57%  |
| WiFi     | 7        | 30.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 66.67%  |
| WiFi     | 6        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 82.35%  |
| 2     | 3        | 17.65%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 94.12%  |
| Yes  | 1        | 5.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 1        | 50%     |
| Intel                           | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Qualcomm Atheros Bluetooth         | 1        | 50%     |
| Intel Bluetooth wireless interface | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 10       | 41.67%  |
| AMD                 | 8        | 33.33%  |
| Nvidia              | 3        | 12.5%   |
| VIA Technologies    | 1        | 4.17%   |
| Plantronics         | 1        | 4.17%   |
| C-Media Electronics | 1        | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 6.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 6.9%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 6.9%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 3.45%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 3.45%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 3.45%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 3.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 3.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 3.45%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 3.45%   |
| C-Media Electronics USB Audio Device                                       | 1        | 3.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 3.45%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 3.45%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 3.45%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 33.33%  |
| Kingston            | 3        | 25%     |
| Samsung Electronics | 1        | 8.33%   |
| G.Skill             | 1        | 8.33%   |
| Crucial             | 1        | 8.33%   |
| Corsair             | 1        | 8.33%   |
| Avant               | 1        | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 2        | 16.67%  |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 8.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 8.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 8.33%   |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s            | 1        | 8.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 1        | 8.33%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3             | 1        | 8.33%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 8.33%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 8.33%   |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s   | 1        | 8.33%   |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s         | 1        | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 41.67%  |
| DDR4    | 3        | 25%     |
| Unknown | 2        | 16.67%  |
| SDRAM   | 1        | 8.33%   |
| DDR2    | 1        | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 83.33%  |
| SODIMM | 2        | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 41.67%  |
| 2048  | 3        | 25%     |
| 4096  | 2        | 16.67%  |
| 16384 | 1        | 8.33%   |
| 1024  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 25%     |
| 800     | 3        | 25%     |
| 3200    | 1        | 8.33%   |
| 2666    | 1        | 8.33%   |
| 2400    | 1        | 8.33%   |
| 2133    | 1        | 8.33%   |
| 1333    | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 66.67%  |
| Samsung Electronics | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 33.33%  |
| Logitech Webcam C270                    | 1        | 33.33%  |
| Logitech QuickCam Notebook Pro          | 1        | 33.33%  |

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
| 0     | 14       | 82.35%  |
| 1     | 2        | 11.76%  |
| 2     | 1        | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 50%     |
| Net/wireless  | 1        | 25%     |
| Camera        | 1        | 25%     |

