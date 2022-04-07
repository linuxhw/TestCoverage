Sparky - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Sparky.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 30

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Pavilion dv5                | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| ASUSTek   | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek   | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| HP        | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP        | Pavilion g7                 | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell      | Inspiron N5010              | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP        | EliteBook Folio 9480m       | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google    | Banon                       | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| Lenovo    | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Apple     | MacBook1,1                  | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung   | NC10                        | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung   | NC10                        | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| Lenovo    | ThinkPad T61 7659AB7        | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Beelink   | BT3 PRO                     | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink   | BT3 PRO                     | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung   | NC10                        | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Dell      | Inspiron 5720               | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines | E525                        | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo    | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Dell      | Inspiron 5720               | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| HP        | Laptop 17z-ca100            | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP        | Laptop 17z-ca100            | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Apple     | MacBook1,1                  | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Acer      | Aspire 5742G                | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Lenovo    | ThinkPad T60 2007FUG        | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell      | Latitude XT3                | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell      | Inspiron 5770               | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP        | Pavilion dv9000 (GA359UA... | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | [622123c1e6](https://linux-hardware.org/?probe=622123c1e6) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Sparky 6    | 7         | 29.17%  |
| Sparky 6.1  | 4         | 16.67%  |
| Sparky 5.14 | 3         | 12.5%   |
| Sparky 7    | 2         | 8.33%   |
| Sparky 6.0  | 2         | 8.33%   |
| Sparky 5.13 | 2         | 8.33%   |
| Sparky 5.12 | 2         | 8.33%   |
| Sparky 5.10 | 2         | 8.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.10.0-9-amd64      | 2         | 8%      |
| 5.10.0-8-amd64      | 2         | 8%      |
| 5.10.0-11-686       | 2         | 8%      |
| 4.19.0-8-amd64      | 2         | 8%      |
| 4.19.0-13-686       | 2         | 8%      |
| 4.19.0-12-amd64     | 2         | 8%      |
| 5.9.0-4-amd64       | 1         | 4%      |
| 5.8.13-sparky-amd64 | 1         | 4%      |
| 5.8.0-2-amd64       | 1         | 4%      |
| 5.5.0-2-amd64       | 1         | 4%      |
| 5.4.7-sparky-amd64  | 1         | 4%      |
| 5.2.0-2-amd64       | 1         | 4%      |
| 5.16.0-5-amd64      | 1         | 4%      |
| 5.14.0-4-amd64      | 1         | 4%      |
| 5.10.4-sparky-amd64 | 1         | 4%      |
| 5.10.0-6-amd64      | 1         | 4%      |
| 5.10.0-3-amd64      | 1         | 4%      |
| 4.19.0-14-686       | 1         | 4%      |
| 4.19.0-10-686       | 1         | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 8         | 34.78%  |
| 4.19.0  | 6         | 26.09%  |
| 5.9.0   | 1         | 4.35%   |
| 5.8.13  | 1         | 4.35%   |
| 5.8.0   | 1         | 4.35%   |
| 5.5.0   | 1         | 4.35%   |
| 5.4.7   | 1         | 4.35%   |
| 5.2.0   | 1         | 4.35%   |
| 5.16.0  | 1         | 4.35%   |
| 5.14.0  | 1         | 4.35%   |
| 5.10.4  | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 9         | 39.13%  |
| 4.19    | 6         | 26.09%  |
| 5.8     | 2         | 8.7%    |
| 5.9     | 1         | 4.35%   |
| 5.5     | 1         | 4.35%   |
| 5.4     | 1         | 4.35%   |
| 5.2     | 1         | 4.35%   |
| 5.16    | 1         | 4.35%   |
| 5.14    | 1         | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 18        | 81.82%  |
| i686   | 4         | 18.18%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 7         | 30.43%  |
| LXQt    | 7         | 30.43%  |
| Unknown | 6         | 26.09%  |
| MATE    | 1         | 4.35%   |
| KDE5    | 1         | 4.35%   |
| GNOME   | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 20        | 86.96%  |
| Tty  | 3         | 13.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 6         | 27.27%  |
| Unknown | 6         | 27.27%  |
| SDDM    | 4         | 18.18%  |
| LightDM | 4         | 18.18%  |
| XDM     | 1         | 4.55%   |
| GDM     | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 8         | 36.36%  |
| pl_PL   | 3         | 13.64%  |
| en_GB   | 3         | 13.64%  |
| Unknown | 2         | 9.09%   |
| ja_JP   | 1         | 4.55%   |
| fr_FR   | 1         | 4.55%   |
| es_CL   | 1         | 4.55%   |
| en_PH   | 1         | 4.55%   |
| en_CA   | 1         | 4.55%   |
| de_DE   | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 16        | 72.73%  |
| EFI  | 6         | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 19        | 86.36%  |
| Overlay | 2         | 9.09%   |
| Btrfs   | 1         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 10        | 45.45%  |
| Unknown | 7         | 31.82%  |
| GPT     | 5         | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 68.18%  |
| Yes       | 7         | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 27.27%  |
| Lenovo              | 4         | 18.18%  |
| Dell                | 4         | 18.18%  |
| ASUSTek Computer    | 2         | 9.09%   |
| Samsung Electronics | 1         | 4.55%   |
| Google              | 1         | 4.55%   |
| eMachines           | 1         | 4.55%   |
| Beelink             | 1         | 4.55%   |
| Apple               | 1         | 4.55%   |
| Acer                | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 4.55%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 4.55%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 4.55%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 4.55%   |
| Lenovo IdeaPad S206 20154        | 1         | 4.55%   |
| HP Pavilion g7                   | 1         | 4.55%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 4.55%   |
| HP Pavilion dv5                  | 1         | 4.55%   |
| HP Laptop 17z-ca100              | 1         | 4.55%   |
| HP EliteBook Folio 9480m         | 1         | 4.55%   |
| HP EliteBook 8770w               | 1         | 4.55%   |
| Google Banon                     | 1         | 4.55%   |
| eMachines E525                   | 1         | 4.55%   |
| Dell Latitude XT3                | 1         | 4.55%   |
| Dell Inspiron N5010              | 1         | 4.55%   |
| Dell Inspiron 5770               | 1         | 4.55%   |
| Dell Inspiron 5720               | 1         | 4.55%   |
| Beelink BT3 PRO                  | 1         | 4.55%   |
| ASUS S101                        | 1         | 4.55%   |
| ASUS 1000HE                      | 1         | 4.55%   |
| Apple MacBook1,1                 | 1         | 4.55%   |
| Acer Aspire 5742G                | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 3         | 13.64%  |
| HP Pavilion     | 3         | 13.64%  |
| Dell Inspiron   | 3         | 13.64%  |
| HP EliteBook    | 2         | 9.09%   |
| Samsung NC10    | 1         | 4.55%   |
| Lenovo IdeaPad  | 1         | 4.55%   |
| HP Laptop       | 1         | 4.55%   |
| Google Banon    | 1         | 4.55%   |
| eMachines E525  | 1         | 4.55%   |
| Dell Latitude   | 1         | 4.55%   |
| Beelink BT3     | 1         | 4.55%   |
| ASUS S101       | 1         | 4.55%   |
| ASUS 1000HE     | 1         | 4.55%   |
| Apple MacBook1  | 1         | 4.55%   |
| Acer Aspire     | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 3         | 13.64%  |
| 2009 | 3         | 13.64%  |
| 2008 | 3         | 13.64%  |
| 2011 | 2         | 9.09%   |
| 2010 | 2         | 9.09%   |
| 2006 | 2         | 9.09%   |
| 2021 | 1         | 4.55%   |
| 2020 | 1         | 4.55%   |
| 2019 | 1         | 4.55%   |
| 2018 | 1         | 4.55%   |
| 2017 | 1         | 4.55%   |
| 2014 | 1         | 4.55%   |
| 2007 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 22        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 95.45%  |
| Yes  | 1         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 36.36%  |
| 4.01-8.0   | 4         | 18.18%  |
| 2.01-3.0   | 4         | 18.18%  |
| 1.01-2.0   | 2         | 9.09%   |
| 32.01-64.0 | 1         | 4.55%   |
| 24.01-32.0 | 1         | 4.55%   |
| 16.01-24.0 | 1         | 4.55%   |
| 0.51-1.0   | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 8         | 34.78%  |
| 1.01-2.0 | 6         | 26.09%  |
| 2.01-3.0 | 3         | 13.04%  |
| 4.01-8.0 | 2         | 8.7%    |
| 3.01-4.0 | 2         | 8.7%    |
| 0.01-0.5 | 2         | 8.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 77.27%  |
| 2      | 3         | 13.64%  |
| 5      | 1         | 4.55%   |
| 4      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 54.55%  |
| Yes       | 10        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 90.91%  |
| No        | 2         | 9.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 90.91%  |
| No        | 2         | 9.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 59.09%  |
| No        | 9         | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 36.36%  |
| UK          | 3         | 13.64%  |
| Poland      | 3         | 13.64%  |
| Germany     | 2         | 9.09%   |
| Canada      | 2         | 9.09%   |
| Philippines | 1         | 4.55%   |
| Japan       | 1         | 4.55%   |
| France      | 1         | 4.55%   |
| Chile       | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Wroclaw               | 1         | 4.17%   |
| Wenatchee             | 1         | 4.17%   |
| Tucson                | 1         | 4.17%   |
| Takahama              | 1         | 4.17%   |
| Spokane               | 1         | 4.17%   |
| San Antonio           | 1         | 4.17%   |
| Saint-Basile-le-Grand | 1         | 4.17%   |
| Pompano Beach         | 1         | 4.17%   |
| Pasig                 | 1         | 4.17%   |
| Paisley               | 1         | 4.17%   |
| Nasielsk              | 1         | 4.17%   |
| Montreuil             | 1         | 4.17%   |
| Montreal              | 1         | 4.17%   |
| Mannheim              | 1         | 4.17%   |
| Leipzig               | 1         | 4.17%   |
| La Florida            | 1         | 4.17%   |
| KoЕ‚o              | 1         | 4.17%   |
| Houston               | 1         | 4.17%   |
| Glasgow               | 1         | 4.17%   |
| East Wenatchee        | 1         | 4.17%   |
| Dunoon                | 1         | 4.17%   |
| Chicago               | 1         | 4.17%   |
| Birmingham            | 1         | 4.17%   |
| Barnsley              | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 8      | 18.52%  |
| Samsung Electronics | 4         | 4      | 14.81%  |
| Hitachi             | 4         | 5      | 14.81%  |
| WDC                 | 3         | 5      | 11.11%  |
| Unknown             | 2         | 2      | 7.41%   |
| GOODRAM             | 2         | 3      | 7.41%   |
| SPCC                | 1         | 2      | 3.7%    |
| ORICO               | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 2      | 3.7%    |
| ASUS-JM             | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Hitachi HTS545025B9A300 250GB            | 2         | 6.9%    |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 3.45%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 3.45%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 3.45%   |
| Unknown MMC Card  64GB                   | 1         | 3.45%   |
| Unknown HBG4a2  32GB                     | 1         | 3.45%   |
| SPCC Solid State Disk 256GB              | 1         | 3.45%   |
| Seagate ST9500325AS 500GB                | 1         | 3.45%   |
| Seagate ST9160310AS 160GB                | 1         | 3.45%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 3.45%   |
| Seagate Backup+ Hub BK 10TB              | 1         | 3.45%   |
| Seagate Backup+ Desk 5TB                 | 1         | 3.45%   |
| Samsung SSD 840 Series 120GB             | 1         | 3.45%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 3.45%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 3.45%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 3.45%   |
| ORICO M200 1TB                           | 1         | 3.45%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 3.45%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 3.45%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 3.45%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 3.45%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 3.45%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 3.45%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 3.45%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 3.45%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 3.45%   |
| A-DATA SX8200NP 480GB                    | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 7      | 38.46%  |
| Hitachi | 4         | 5      | 30.77%  |
| WDC     | 3         | 5      | 23.08%  |
| Fujitsu | 1         | 2      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 25%     |
| GOODRAM             | 2         | 3      | 25%     |
| SPCC                | 1         | 2      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |
| Intel               | 1         | 1      | 12.5%   |
| ASUS-JM             | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 13        | 19     | 48.15%  |
| SSD     | 7         | 10     | 25.93%  |
| NVMe    | 3         | 3      | 11.11%  |
| MMC     | 2         | 2      | 7.41%   |
| Unknown | 2         | 2      | 7.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 27     | 75%     |
| NVMe | 3         | 3      | 12.5%   |
| MMC  | 2         | 2      | 8.33%   |
| SAS  | 1         | 4      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 24     | 84.21%  |
| 0.51-1.0   | 2         | 2      | 10.53%  |
| 4.01-10.0  | 1         | 3      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 40.91%  |
| 1-20           | 3         | 13.64%  |
| 501-1000       | 3         | 13.64%  |
| 251-500        | 2         | 9.09%   |
| 21-50          | 2         | 9.09%   |
| More than 3000 | 1         | 4.55%   |
| 1001-2000      | 1         | 4.55%   |
| Unknown        | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 11        | 47.83%  |
| 21-50          | 3         | 13.04%  |
| 51-100         | 3         | 13.04%  |
| 101-250        | 2         | 8.7%    |
| More than 3000 | 1         | 4.35%   |
| 1001-2000      | 1         | 4.35%   |
| 501-1000       | 1         | 4.35%   |
| Unknown        | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 25%     |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 25%     |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 25%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 50%     |
| Seagate           | 1         | 1      | 25%     |
| Micron Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 10        | 17     | 43.48%  |
| Detected | 9         | 15     | 39.13%  |
| Malfunc  | 4         | 4      | 17.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 17        | 73.91%  |
| Samsung Electronics | 2         | 8.7%    |
| Silicon Motion      | 1         | 4.35%   |
| Nvidia              | 1         | 4.35%   |
| JMicron Technology  | 1         | 4.35%   |
| AMD                 | 1         | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 11.11%  |
| Samsung NVMe SSD Controller 980                                              | 2         | 7.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 7.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 2         | 7.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 2         | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 7.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 3.7%    |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 3.7%    |
| Nvidia MCP51 IDE                                                             | 1         | 3.7%    |
| JMicron JMB360 AHCI Controller                                               | 1         | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 60%     |
| IDE  | 7         | 28%     |
| NVMe | 3         | 12%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 86.36%  |
| AMD    | 3         | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 9.09%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 4.55%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 4.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 4.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 4.55%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 4.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.55%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 4.55%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 4.55%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 4.55%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 4.55%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 4.55%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 4.55%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 4.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 4.55%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 4.55%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 4.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD C-50 Processor                            | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4         | 18.18%  |
| Intel Atom              | 4         | 18.18%  |
| Intel Core i7           | 3         | 13.64%  |
| Intel Core 2 Duo        | 2         | 9.09%   |
| Intel Celeron           | 2         | 9.09%   |
| Intel Pentium           | 1         | 4.55%   |
| Intel Genuine           | 1         | 4.55%   |
| Intel Core i3           | 1         | 4.55%   |
| Intel Core 2            | 1         | 4.55%   |
| AMD Turion 64 X2 Mobile | 1         | 4.55%   |
| AMD Ryzen 5             | 1         | 4.55%   |
| AMD C-50                | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 50%     |
| 4      | 7         | 31.82%  |
| 1      | 4         | 18.18%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 54.55%  |
| 1      | 10        | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 81.82%  |
| 32-bit         | 4         | 18.18%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 18.18%  |
| 0x406c4    | 2         | 9.09%   |
| 0x306a9    | 2         | 9.09%   |
| 0x206a7    | 2         | 9.09%   |
| 0x20655    | 2         | 9.09%   |
| 0x106c2    | 2         | 9.09%   |
| 0x806ec    | 1         | 4.55%   |
| 0x806ea    | 1         | 4.55%   |
| 0x6f2      | 1         | 4.55%   |
| 0x40651    | 1         | 4.55%   |
| 0x1067a    | 1         | 4.55%   |
| 0x10676    | 1         | 4.55%   |
| 0x08108109 | 1         | 4.55%   |
| 0x05000029 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Bonnell     | 3         | 13.64%  |
| Westmere    | 2         | 9.09%   |
| Silvermont  | 2         | 9.09%   |
| SandyBridge | 2         | 9.09%   |
| Penryn      | 2         | 9.09%   |
| KabyLake    | 2         | 9.09%   |
| IvyBridge   | 2         | 9.09%   |
| Core        | 2         | 9.09%   |
| Zen+        | 1         | 4.55%   |
| P6          | 1         | 4.55%   |
| K8 Hammer   | 1         | 4.55%   |
| Haswell     | 1         | 4.55%   |
| Bobcat      | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 68.18%  |
| Nvidia | 4         | 18.18%  |
| AMD    | 3         | 13.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 14.81%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 11.11%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 7.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 7.41%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 3.7%    |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 3.7%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 3.7%    |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 3.7%    |
| Intel UHD Graphics 620                                                                   | 1         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 3.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 3.7%    |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 3.7%    |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 15        | 68.18%  |
| 1 x Nvidia | 4         | 18.18%  |
| 1 x AMD    | 3         | 13.64%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 95.45%  |
| Proprietary | 1         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 72.73%  |
| 0.01-0.5   | 3         | 13.64%  |
| 1.01-2.0   | 2         | 9.09%   |
| 0.51-1.0   | 1         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 22.73%  |
| AU Optronics        | 3         | 13.64%  |
| Samsung Electronics | 2         | 9.09%   |
| Lenovo              | 2         | 9.09%   |
| CPT                 | 2         | 9.09%   |
| Chimei Innolux      | 2         | 9.09%   |
| LG Philips          | 1         | 4.55%   |
| Insignia            | 1         | 4.55%   |
| Hitachi             | 1         | 4.55%   |
| HannStar            | 1         | 4.55%   |
| BOE                 | 1         | 4.55%   |
| Apple               | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 4.35%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 4.35%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 4.35%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 4.35%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 4.35%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 4.35%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 4.35%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 4.35%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 4.35%   |
| Insignia NS32DD200NA14 BBY0032 1680x1050 640x384mm 29.4-inch         | 1         | 4.35%   |
| Hitachi HDMI    HEC0088 1920x1080 1100x560mm 48.6-inch               | 1         | 4.35%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 4.35%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 4.35%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 4.35%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 4.35%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 6         | 26.09%  |
| 1366x768 (WXGA)  | 4         | 17.39%  |
| 1600x900 (HD+)   | 3         | 13.04%  |
| 1024x600         | 3         | 13.04%  |
| 1920x540         | 2         | 8.7%    |
| 1440x900 (WXGA+) | 2         | 8.7%    |
| 1280x800 (WXGA)  | 2         | 8.7%    |
| 1400x1050        | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 17     | 6         | 26.09%  |
| 15     | 6         | 26.09%  |
| 14     | 3         | 13.04%  |
| 10     | 3         | 13.04%  |
| 48     | 2         | 8.7%    |
| 13     | 2         | 8.7%    |
| 24     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 8         | 34.78%  |
| 351-400     | 6         | 26.09%  |
| 201-300     | 6         | 26.09%  |
| 1001-1500   | 2         | 8.7%    |
| 501-600     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 69.57%  |
| 16/10 | 4         | 17.39%  |
| 1.96  | 2         | 8.7%    |
| 4/3   | 1         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 26.09%  |
| 121-130        | 5         | 21.74%  |
| 41-50          | 3         | 13.04%  |
| 81-90          | 2         | 8.7%    |
| 71-80          | 2         | 8.7%    |
| 501-1000       | 2         | 8.7%    |
| 201-250        | 1         | 4.35%   |
| 131-140        | 1         | 4.35%   |
| 91-100         | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 45.45%  |
| 121-160 | 8         | 36.36%  |
| 1-50    | 2         | 9.09%   |
| 51-100  | 2         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 95.45%  |
| 2     | 1         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 10        | 30.3%   |
| Realtek Semiconductor    | 8         | 24.24%  |
| Qualcomm Atheros         | 7         | 21.21%  |
| Marvell Technology Group | 2         | 6.06%   |
| Broadcom Limited         | 2         | 6.06%   |
| TP-Link                  | 1         | 3.03%   |
| Ralink                   | 1         | 3.03%   |
| Nvidia                   | 1         | 3.03%   |
| Broadcom                 | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4         | 9.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 9.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 4.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 4.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 4.88%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 2.44%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 2.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 2.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 2.44%   |
| Intel Wireless 7265                                                     | 1         | 2.44%   |
| Intel Wireless 7260                                                     | 1         | 2.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.44%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.44%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 2.44%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.44%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.44%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 47.62%  |
| Qualcomm Atheros      | 6         | 28.57%  |
| Broadcom Limited      | 2         | 9.52%   |
| TP-Link               | 1         | 4.76%   |
| Realtek Semiconductor | 1         | 4.76%   |
| Ralink                | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 9.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 9.52%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 4.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 4.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 4.76%   |
| Intel Wireless 7265                                                     | 1         | 4.76%   |
| Intel Wireless 7260                                                     | 1         | 4.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 4.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 4.76%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 4.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 4.76%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 4.76%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 4.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 40%     |
| Intel                    | 5         | 25%     |
| Qualcomm Atheros         | 3         | 15%     |
| Marvell Technology Group | 2         | 10%     |
| Nvidia                   | 1         | 5%      |
| Broadcom                 | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 20%     |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10%     |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 5%      |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 5%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 5%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 5%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 5%      |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 5%      |
| Intel 82566MM Gigabit Network Connection                          | 1         | 5%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 50%     |
| Ethernet | 20        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 62.96%  |
| Ethernet | 10        | 37.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 81.82%  |
| 1     | 4         | 18.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 82.61%  |
| Yes  | 4         | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4         | 30.77%  |
| Broadcom                        | 3         | 23.08%  |
| Realtek Semiconductor           | 1         | 7.69%   |
| Qualcomm Atheros Communications | 1         | 7.69%   |
| Dell                            | 1         | 7.69%   |
| Cambridge Silicon Radio         | 1         | 7.69%   |
| ASUSTek Computer                | 1         | 7.69%   |
| Apple                           | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 15.38%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 7.69%   |
| Intel AX201 Bluetooth                               | 1         | 7.69%   |
| Dell Wireless 365 Bluetooth                         | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |
| Broadcom HP Portable SoftSailing                    | 1         | 7.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 7.69%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 7.69%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 7.69%   |
| Apple Bluetooth HCI                                 | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 78.26%  |
| Nvidia | 3         | 13.04%  |
| AMD    | 2         | 8.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 19.23%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 7.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 7.69%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 3.85%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 3.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 3.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 3.85%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.85%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 22.22%  |
| Unknown             | 3         | 16.67%  |
| SK Hynix            | 3         | 16.67%  |
| Nanya Technology    | 2         | 11.11%  |
| Micron Technology   | 2         | 11.11%  |
| Kingston            | 1         | 5.56%   |
| GOODRAM             | 1         | 5.56%   |
| G.Skill             | 1         | 5.56%   |
| Corsair             | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 5%      |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 5%      |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 1         | 5%      |
| Unknown RAM Module 1024MB SODIMM 800MT/s                 | 1         | 5%      |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 5%      |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 5%      |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 5%      |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 1         | 5%      |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 1         | 5%      |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s | 1         | 5%      |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 5%      |
| Samsung RAM K4E8E324EB-EGCF 2048MB LPDDR3 1600MT/s       | 1         | 5%      |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s  | 1         | 5%      |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s  | 1         | 5%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 1         | 5%      |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s   | 1         | 5%      |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s | 1         | 5%      |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 5%      |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s   | 1         | 5%      |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s   | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 9         | 56.25%  |
| SDRAM   | 2         | 12.5%   |
| DDR4    | 2         | 12.5%   |
| LPDDR3  | 1         | 6.25%   |
| DDR2    | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 14        | 93.33%  |
| Unknown | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 6         | 31.58%  |
| 4096  | 5         | 26.32%  |
| 8192  | 3         | 15.79%  |
| 1024  | 3         | 15.79%  |
| 16384 | 2         | 10.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 35.29%  |
| 2667    | 2         | 11.76%  |
| 1334    | 2         | 11.76%  |
| 1333    | 2         | 11.76%  |
| Unknown | 2         | 11.76%  |
| 4199    | 1         | 5.88%   |
| 1066    | 1         | 5.88%   |
| 800     | 1         | 5.88%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 41.18%  |
| Microdia                      | 3         | 17.65%  |
| Sunplus Innovation Technology | 2         | 11.76%  |
| Acer                          | 2         | 11.76%  |
| Z-Star Microelectronics       | 1         | 5.88%   |
| Suyin                         | 1         | 5.88%   |
| Microsoft                     | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 5.88%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.88%   |
| Sunplus Integrated Webcam                                   | 1         | 5.88%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 5.88%   |
| Microsoft LifeCam Cinema                                    | 1         | 5.88%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.88%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5.88%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 5.88%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 5.88%   |
| Chicony HP TrueVision HD Camera                             | 1         | 5.88%   |
| Chicony HP Integrated Webcam                                | 1         | 5.88%   |
| Chicony HP HD Webcam                                        | 1         | 5.88%   |
| Chicony HD WebCam                                           | 1         | 5.88%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 5.88%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 5.88%   |
| Acer Lenovo EasyCamera                                      | 1         | 5.88%   |
| Acer HP Webcam                                              | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 2         | 66.67%  |
| STMicroelectronics | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS491                    | 1         | 33.33%  |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 33.33%  |
| STMicroelectronics Fingerprint Reader      | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 68.18%  |
| 1     | 5         | 22.73%  |
| 2     | 2         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 3         | 33.33%  |
| Net/wireless          | 2         | 22.22%  |
| Multimedia controller | 2         | 22.22%  |
| Graphics card         | 1         | 11.11%  |
| Chipcard              | 1         | 11.11%  |
