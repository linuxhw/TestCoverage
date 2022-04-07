Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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

Total: 39

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pardus 21.1   | 6         | 20%     |
| Pardus 21.0   | 4         | 13.33%  |
| Pardus 19.5   | 4         | 13.33%  |
| Pardus 19.4-1 | 3         | 10%     |
| Pardus 19.4   | 3         | 10%     |
| Pardus 19.3   | 3         | 10%     |
| Pardus 19.2   | 3         | 10%     |
| Pardus 19.1   | 2         | 6.67%   |
| Pardus 19.0   | 2         | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 29        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-11-amd64      | 3         | 10%     |
| 4.19.0-6-amd64       | 3         | 10%     |
| 4.19.0-13-amd64      | 3         | 10%     |
| 4.19.0-10-amd64      | 3         | 10%     |
| 5.9.0-0.bpo.2-amd64  | 2         | 6.67%   |
| 5.10.0-9-amd64       | 2         | 6.67%   |
| 5.10.0-8-amd64       | 2         | 6.67%   |
| 5.10.0-10-amd64      | 2         | 6.67%   |
| 4.19.0-8-amd64       | 2         | 6.67%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 3.33%   |
| 5.10.0-12-amd64      | 1         | 3.33%   |
| 5.10.0-0.bpo.8-amd64 | 1         | 3.33%   |
| 4.19.0-5-amd64       | 1         | 3.33%   |
| 4.19.0-19-amd64      | 1         | 3.33%   |
| 4.19.0-18-amd64      | 1         | 3.33%   |
| 4.19.0-16-amd64      | 1         | 3.33%   |
| 4.19.0-12-amd64      | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 15        | 51.72%  |
| 5.10.0  | 11        | 37.93%  |
| 5.9.0   | 2         | 6.9%    |
| 5.4.0   | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 15        | 51.72%  |
| 5.10    | 11        | 37.93%  |
| 5.9     | 2         | 6.9%    |
| 5.4     | 1         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 19        | 65.52%  |
| GNOME   | 7         | 24.14%  |
| Unknown | 2         | 6.9%    |
| KDE5    | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 29        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 62.07%  |
| TDM     | 6         | 20.69%  |
| LightDM | 3         | 10.34%  |
| GDM     | 2         | 6.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 22        | 75.86%  |
| Unknown | 3         | 10.34%  |
| pt_BR   | 1         | 3.45%   |
| fr_FR   | 1         | 3.45%   |
| en_US   | 1         | 3.45%   |
| en_GB   | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 22        | 75.86%  |
| EFI  | 7         | 24.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 29        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 20        | 68.97%  |
| GPT     | 7         | 24.14%  |
| MBR     | 2         | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 96.55%  |
| Yes       | 1         | 3.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 82.76%  |
| Yes       | 5         | 17.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 27.59%  |
| Hewlett-Packard     | 4         | 13.79%  |
| ASUSTek Computer    | 4         | 13.79%  |
| Toshiba             | 2         | 6.9%    |
| Sony                | 2         | 6.9%    |
| Packard Bell        | 2         | 6.9%    |
| Gigabyte Technology | 2         | 6.9%    |
| Dell                | 2         | 6.9%    |
| Samsung Electronics | 1         | 3.45%   |
| Philco              | 1         | 3.45%   |
| MSI                 | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 3.45%   |
| Toshiba PORTEGE M780                       | 1         | 3.45%   |
| Sony SVF1521QSTB                           | 1         | 3.45%   |
| Sony SVE14A2V2ES                           | 1         | 3.45%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 3.45%   |
| Philco 14F                                 | 1         | 3.45%   |
| Packard Bell EasyNote_GN45                 | 1         | 3.45%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 3.45%   |
| MSI MS-7360                                | 1         | 3.45%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 3.45%   |
| Lenovo V145-15AST 81MT                     | 1         | 3.45%   |
| Lenovo V110-15ISK 80TL                     | 1         | 3.45%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 3.45%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 3.45%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 3.45%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 3.45%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 3.45%   |
| HP Pavilion 15                             | 1         | 3.45%   |
| HP Laptop 15-dw3xxx                        | 1         | 3.45%   |
| HP 250 G3                                  | 1         | 3.45%   |
| HP 15                                      | 1         | 3.45%   |
| Gigabyte A320M-S2H                         | 1         | 3.45%   |
| Gigabyte A320M-H                           | 1         | 3.45%   |
| Dell Latitude E6540                        | 1         | 3.45%   |
| Dell G5 5587                               | 1         | 3.45%   |
| ASUS X555YI                                | 1         | 3.45%   |
| ASUS V230IC-DDR4                           | 1         | 3.45%   |
| ASUS P5G41C-M LX                           | 1         | 3.45%   |
| ASUS E402BP                                | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 6.9%    |
| Lenovo ThinkPad          | 2         | 6.9%    |
| Toshiba Satellite        | 1         | 3.45%   |
| Toshiba PORTEGE          | 1         | 3.45%   |
| Sony SVF1521QSTB         | 1         | 3.45%   |
| Sony SVE14A2V2ES         | 1         | 3.45%   |
| Samsung 300E4A           | 1         | 3.45%   |
| Philco 14F               | 1         | 3.45%   |
| MSI MS-7360              | 1         | 3.45%   |
| Lenovo Yoga              | 1         | 3.45%   |
| Lenovo V145-15AST        | 1         | 3.45%   |
| Lenovo V110-15ISK        | 1         | 3.45%   |
| Lenovo ThinkCentre       | 1         | 3.45%   |
| Lenovo IdeaPad-510-15IKB | 1         | 3.45%   |
| Lenovo IdeaPad           | 1         | 3.45%   |
| HP Pavilion              | 1         | 3.45%   |
| HP Laptop                | 1         | 3.45%   |
| HP 250                   | 1         | 3.45%   |
| HP 15                    | 1         | 3.45%   |
| Gigabyte A320M-S2H       | 1         | 3.45%   |
| Gigabyte A320M-H         | 1         | 3.45%   |
| Dell Latitude            | 1         | 3.45%   |
| Dell G5                  | 1         | 3.45%   |
| ASUS X555YI              | 1         | 3.45%   |
| ASUS V230IC-DDR4         | 1         | 3.45%   |
| ASUS P5G41C-M            | 1         | 3.45%   |
| ASUS E402BP              | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 6         | 20.69%  |
| 2018 | 5         | 17.24%  |
| 2015 | 3         | 10.34%  |
| 2020 | 2         | 6.9%    |
| 2017 | 2         | 6.9%    |
| 2016 | 2         | 6.9%    |
| 2011 | 2         | 6.9%    |
| 2010 | 2         | 6.9%    |
| 2021 | 1         | 3.45%   |
| 2019 | 1         | 3.45%   |
| 2014 | 1         | 3.45%   |
| 2007 | 1         | 3.45%   |
| 2006 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 22        | 75.86%  |
| Desktop     | 5         | 17.24%  |
| Convertible | 1         | 3.45%   |
| All in one  | 1         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 11        | 37.93%  |
| 4.01-8.0   | 9         | 31.03%  |
| 16.01-24.0 | 4         | 13.79%  |
| 1.01-2.0   | 2         | 6.9%    |
| 8.01-16.0  | 2         | 6.9%    |
| 32.01-64.0 | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 11        | 36.67%  |
| 2.01-3.0   | 8         | 26.67%  |
| 3.01-4.0   | 6         | 20%     |
| 4.01-8.0   | 2         | 6.67%   |
| 24.01-32.0 | 1         | 3.33%   |
| 8.01-16.0  | 1         | 3.33%   |
| 0.51-1.0   | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 68.97%  |
| 2      | 7         | 24.14%  |
| 4      | 1         | 3.45%   |
| 3      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 58.62%  |
| No        | 12        | 41.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 82.76%  |
| No        | 5         | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 72.41%  |
| No        | 8         | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 26        | 89.66%  |
| UK      | 1         | 3.45%   |
| France  | 1         | 3.45%   |
| Brazil  | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Istanbul      | 9         | 30%     |
| Bursa         | 5         | 16.67%  |
| Izmir         | 3         | 10%     |
| Ankara        | 2         | 6.67%   |
| Г‡anakkale | 1         | 3.33%   |
| Soleymieu     | 1         | 3.33%   |
| Porto Alegre  | 1         | 3.33%   |
| Mersin        | 1         | 3.33%   |
| Malatya       | 1         | 3.33%   |
| London        | 1         | 3.33%   |
| Kosekoy       | 1         | 3.33%   |
| Konya         | 1         | 3.33%   |
| Gaziantep     | 1         | 3.33%   |
| Artvin        | 1         | 3.33%   |
| Antalya       | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 17.95%  |
| Samsung Electronics | 7         | 9      | 17.95%  |
| Seagate             | 6         | 7      | 15.38%  |
| SK Hynix            | 2         | 2      | 5.13%   |
| Kingston            | 2         | 2      | 5.13%   |
| HGST                | 2         | 2      | 5.13%   |
| Unknown             | 1         | 1      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| Team                | 1         | 1      | 2.56%   |
| SPCC                | 1         | 1      | 2.56%   |
| Silicon Motion      | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| Micron Technology   | 1         | 1      | 2.56%   |
| Lexar               | 1         | 1      | 2.56%   |
| KingSpec            | 1         | 1      | 2.56%   |
| Hitachi             | 1         | 1      | 2.56%   |
| Corsair             | 1         | 1      | 2.56%   |
| addlink             | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 5%      |
| WDC WD6402AAEX-00Y9A0 640GB                 | 1         | 2.5%    |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 2.5%    |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 2.5%    |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 2.5%    |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 2.5%    |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 2.5%    |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 2.5%    |
| Unknown MMC Card  64GB                      | 1         | 2.5%    |
| Toshiba DT01ACA100 1TB                      | 1         | 2.5%    |
| Team T253X1240G 240GB SSD                   | 1         | 2.5%    |
| SPCC Solid State Disk 512GB                 | 1         | 2.5%    |
| SK Hynix SC311 SATA 256GB SSD               | 1         | 2.5%    |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 2.5%    |
| Silicon Motion Longline SSD 512GB           | 1         | 2.5%    |
| Seagate ST9120822AS 120GB                   | 1         | 2.5%    |
| Seagate ST3160318AS 160GB                   | 1         | 2.5%    |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 2.5%    |
| Seagate Expansion 320GB                     | 1         | 2.5%    |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 2.5%    |
| SanDisk SDSSDA480G 480GB                    | 1         | 2.5%    |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.5%    |
| Samsung NVMe SSD Drive 512GB                | 1         | 2.5%    |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 2.5%    |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 2.5%    |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 2.5%    |
| Samsung HD501LJ 500GB                       | 1         | 2.5%    |
| Samsung HD160HJ 160GB                       | 1         | 2.5%    |
| Samsung HD103SJ 1TB                         | 1         | 2.5%    |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 2.5%    |
| Lexar 120GB SSD                             | 1         | 2.5%    |
| Kingston SHFS37A120G 120GB SSD              | 1         | 2.5%    |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.5%    |
| KingSpec P3-128 128GB                       | 1         | 2.5%    |
| Hitachi HTS545025B9A300 250GB               | 1         | 2.5%    |
| Corsair Force LS SSD 64GB                   | 1         | 2.5%    |
| addlink S10 120GB                           | 1         | 2.5%    |
| A-DATA SU650 120GB SSD                      | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 38.89%  |
| Seagate             | 5         | 6      | 27.78%  |
| Samsung Electronics | 2         | 3      | 11.11%  |
| HGST                | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 20%     |
| Kingston            | 2         | 2      | 13.33%  |
| Team                | 1         | 1      | 6.67%   |
| SPCC                | 1         | 1      | 6.67%   |
| SK Hynix            | 1         | 1      | 6.67%   |
| Seagate             | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Lexar               | 1         | 1      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Corsair             | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 16        | 22     | 47.06%  |
| SSD     | 13        | 15     | 38.24%  |
| NVMe    | 3         | 5      | 8.82%   |
| MMC     | 1         | 1      | 2.94%   |
| Unknown | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 26        | 37     | 83.87%  |
| NVMe | 3         | 5      | 9.68%   |
| SAS  | 1         | 1      | 3.23%   |
| MMC  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 25     | 68.97%  |
| 0.51-1.0   | 8         | 10     | 27.59%  |
| 1.01-2.0   | 1         | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 37.93%  |
| 251-500    | 9         | 31.03%  |
| 501-1000   | 3         | 10.34%  |
| 51-100     | 3         | 10.34%  |
| 21-50      | 2         | 6.9%    |
| 2001-3000  | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 11        | 37.93%  |
| 21-50    | 7         | 24.14%  |
| 51-100   | 6         | 20.69%  |
| 101-250  | 3         | 10.34%  |
| 251-500  | 1         | 3.45%   |
| 501-1000 | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9120822AS 120GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 20        | 33     | 68.97%  |
| Works    | 8         | 10     | 27.59%  |
| Malfunc  | 1         | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 66.67%  |
| AMD                      | 6         | 18.18%  |
| Samsung Electronics      | 2         | 6.06%   |
| SK Hynix                 | 1         | 3.03%   |
| Silicon Motion           | 1         | 3.03%   |
| Marvell Technology Group | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 13.16%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 10.53%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 7.89%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 5.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 5.26%   |
| AMD FCH SATA Controller D                                                        | 2         | 5.26%   |
| SK Hynix BC511                                                                   | 1         | 2.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.63%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.63%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1         | 2.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1         | 2.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 25        | 78.13%  |
| NVMe | 3         | 9.38%   |
| IDE  | 3         | 9.38%   |
| RAID | 1         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 79.31%  |
| AMD    | 6         | 20.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 3.45%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.45%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 3.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 3.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 3.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i5-6400T CPU @ 2.20GHz             | 1         | 3.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.45%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.45%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 3.45%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 3.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 3.45%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 3.45%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 3.45%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 3.45%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.45%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.45%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.45%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1         | 3.45%   |
| AMD C-50 Processor                            | 1         | 3.45%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.45%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.45%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 3.45%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 5         | 17.24%  |
| Other             | 4         | 13.79%  |
| Intel Core i7     | 4         | 13.79%  |
| Intel Core i3     | 4         | 13.79%  |
| Intel Pentium     | 2         | 6.9%    |
| Intel Core 2 Quad | 2         | 6.9%    |
| Intel Celeron     | 2         | 6.9%    |
| AMD A8            | 2         | 6.9%    |
| Intel Core i9     | 1         | 3.45%   |
| Intel Core 2      | 1         | 3.45%   |
| AMD Ryzen 5       | 1         | 3.45%   |
| AMD C-50          | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 62.07%  |
| 4      | 8         | 27.59%  |
| 6      | 2         | 6.9%    |
| 8      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 55.17%  |
| 1      | 13        | 44.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 68.97%  |
| 0x906ea    | 1         | 3.45%   |
| 0x806c1    | 1         | 3.45%   |
| 0x6f6      | 1         | 3.45%   |
| 0x506e3    | 1         | 3.45%   |
| 0x406e3    | 1         | 3.45%   |
| 0x306a9    | 1         | 3.45%   |
| 0x07030105 | 1         | 3.45%   |
| 0x06006705 | 1         | 3.45%   |
| 0x05000029 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 13.79%  |
| IvyBridge   | 3         | 10.34%  |
| Excavator   | 3         | 10.34%  |
| TigerLake   | 2         | 6.9%    |
| Skylake     | 2         | 6.9%    |
| SandyBridge | 2         | 6.9%    |
| Haswell     | 2         | 6.9%    |
| Core        | 2         | 6.9%    |
| Broadwell   | 2         | 6.9%    |
| Zen 2       | 1         | 3.45%   |
| Westmere    | 1         | 3.45%   |
| Silvermont  | 1         | 3.45%   |
| Puma        | 1         | 3.45%   |
| Penryn      | 1         | 3.45%   |
| Goldmont    | 1         | 3.45%   |
| Bobcat      | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 56.76%  |
| AMD    | 10        | 27.03%  |
| Nvidia | 6         | 16.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 7.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 4.88%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 4.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 4.88%   |
| Nvidia GT200 [GeForce GTX 260]                                                           | 1         | 2.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.44%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.44%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.44%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.44%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.44%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.44%   |
| Intel HD Graphics 620                                                                    | 1         | 2.44%   |
| Intel HD Graphics 530                                                                    | 1         | 2.44%   |
| Intel HD Graphics 520                                                                    | 1         | 2.44%   |
| Intel HD Graphics 500                                                                    | 1         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.44%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.44%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.44%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.44%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.44%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.44%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 2.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 2.44%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 44.83%  |
| Intel + Nvidia | 4         | 13.79%  |
| 1 x AMD        | 4         | 13.79%  |
| 2 x AMD        | 3         | 10.34%  |
| Intel + AMD    | 3         | 10.34%  |
| 1 x Nvidia     | 2         | 6.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 96.55%  |
| Proprietary | 1         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 86.21%  |
| 0.01-0.5   | 3         | 10.34%  |
| 5.01-6.0   | 1         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5         | 17.86%  |
| LG Display              | 4         | 14.29%  |
| AU Optronics            | 4         | 14.29%  |
| Chimei Innolux          | 3         | 10.71%  |
| BOE                     | 3         | 10.71%  |
| Goldstar                | 2         | 7.14%   |
| LG Philips              | 1         | 3.57%   |
| Lenovo                  | 1         | 3.57%   |
| Iiyama                  | 1         | 3.57%   |
| Chi Mei Optoelectronics | 1         | 3.57%   |
| Beko                    | 1         | 3.57%   |
| AOC                     | 1         | 3.57%   |
| AGO                     | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 3.45%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 3.45%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 3.45%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 3.45%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 3.45%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 3.45%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 3.45%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 1         | 3.45%   |
| Goldstar 2D HD TV GSM59CA 1920x1080 521x293mm 23.5-inch                  | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 3.45%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.45%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 3.45%   |
| Beko BK WUXGA BEK4448 1920x1080 1600x900mm 72.3-inch                     | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 3.45%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 1         | 3.45%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                    | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 12        | 42.86%  |
| 1920x1080 (FHD)    | 10        | 35.71%  |
| 1600x900 (HD+)     | 2         | 7.14%   |
| 3840x2160 (4K)     | 1         | 3.57%   |
| 1680x1050 (WSXGA+) | 1         | 3.57%   |
| 1280x800 (WXGA)    | 1         | 3.57%   |
| 1280x1024 (SXGA)   | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 16        | 55.17%  |
| 23     | 3         | 10.34%  |
| 14     | 2         | 6.9%    |
| 72     | 1         | 3.45%   |
| 31     | 1         | 3.45%   |
| 22     | 1         | 3.45%   |
| 20     | 1         | 3.45%   |
| 17     | 1         | 3.45%   |
| 13     | 1         | 3.45%   |
| 12     | 1         | 3.45%   |
| 11     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 67.86%  |
| 401-500     | 3         | 10.71%  |
| 501-600     | 2         | 7.14%   |
| 201-300     | 2         | 7.14%   |
| 601-700     | 1         | 3.57%   |
| 1501-2000   | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 82.14%  |
| 16/10 | 2         | 7.14%   |
| 5/4   | 1         | 3.57%   |
| 4/3   | 1         | 3.57%   |
| 3/2   | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 55.17%  |
| 201-250        | 4         | 13.79%  |
| 81-90          | 3         | 10.34%  |
| More than 1000 | 1         | 3.45%   |
| 71-80          | 1         | 3.45%   |
| 51-60          | 1         | 3.45%   |
| 351-500        | 1         | 3.45%   |
| 151-200        | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 34.48%  |
| 121-160 | 9         | 31.03%  |
| 51-100  | 8         | 27.59%  |
| 1-50    | 1         | 3.45%   |
| 161-240 | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 86.21%  |
| 2     | 3         | 10.34%  |
| 0     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 52.27%  |
| Intel                 | 10        | 22.73%  |
| Qualcomm Atheros      | 4         | 9.09%   |
| Ralink                | 2         | 4.55%   |
| Broadcom              | 2         | 4.55%   |
| ASUSTek Computer      | 2         | 4.55%   |
| JMicron Technology    | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 32.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 5.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.82%   |
| Intel Wireless 7265                                               | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.82%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.82%   |
| Intel Centrino Wireless-N 130                                     | 1         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.82%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.82%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.82%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 1.82%   |
| ASUS 802.11ac NIC                                                 | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 34.62%  |
| Realtek Semiconductor | 7         | 26.92%  |
| Qualcomm Atheros      | 4         | 15.38%  |
| Ralink                | 2         | 7.69%   |
| Broadcom              | 2         | 7.69%   |
| ASUSTek Computer      | 2         | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 11.54%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 7.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2         | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 7.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 3.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 3.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.85%   |
| Intel Wireless 7265                                        | 1         | 3.85%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 3.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.85%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.85%   |
| Intel Centrino Wireless-N 130                              | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.85%   |
| Intel Centrino Advanced-N 6200                             | 1         | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.85%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                        | 1         | 3.85%   |
| ASUS 802.11ac NIC                                          | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 82.14%  |
| Intel                 | 4         | 14.29%  |
| JMicron Technology    | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 62.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 13.79%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 3.45%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 53.85%  |
| WiFi     | 24        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 50%     |
| Ethernet | 22        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 79.31%  |
| 1     | 6         | 20.69%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 96.55%  |
| Yes  | 1         | 3.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 28.57%  |
| Realtek Semiconductor           | 5         | 23.81%  |
| Toshiba                         | 2         | 9.52%   |
| Qualcomm Atheros Communications | 2         | 9.52%   |
| IMC Networks                    | 2         | 9.52%   |
| Ralink                          | 1         | 4.76%   |
| Lite-On Technology              | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Broadcom                        | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 4         | 19.05%  |
| Qualcomm Atheros  Bluetooth Device               | 2         | 9.52%   |
| Intel Bluetooth wireless interface               | 2         | 9.52%   |
| Toshiba RT Bluetooth Radio                       | 1         | 4.76%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 4.76%   |
| Realtek RTL8821A Bluetooth                       | 1         | 4.76%   |
| Ralink RT3290 Bluetooth                          | 1         | 4.76%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 4.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 4.76%   |
| Intel AX201 Bluetooth                            | 1         | 4.76%   |
| IMC Networks Bluetooth Radio                     | 1         | 4.76%   |
| IMC Networks Bluetooth Device                    | 1         | 4.76%   |
| Foxconn / Hon Hai BCM43142A0                     | 1         | 4.76%   |
| Broadcom HP Portable Valentine                   | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 71.88%  |
| AMD                   | 7         | 21.88%  |
| Nvidia                | 1         | 3.13%   |
| Barco Display Systems | 1         | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 7.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 4.76%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.76%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.38%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 2.38%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 45.45%  |
| Unknown (0x4509)    | 1         | 9.09%   |
| Unknown             | 1         | 9.09%   |
| SK Hynix            | 1         | 9.09%   |
| Micron Technology   | 1         | 9.09%   |
| Kingmax             | 1         | 9.09%   |
| G.Skill             | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 9.09%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s          | 1         | 9.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 9.09%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s           | 1         | 9.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s           | 1         | 9.09%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 9.09%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 9.09%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 7         | 63.64%  |
| DDR3  | 2         | 18.18%  |
| SDRAM | 1         | 9.09%   |
| DDR2  | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 8         | 80%     |
| DIMM   | 2         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 5         | 50%     |
| 8192 | 3         | 30%     |
| 2048 | 2         | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2133    | 3         | 30%     |
| 3200    | 2         | 20%     |
| 2667    | 2         | 20%     |
| 1600    | 1         | 10%     |
| 1333    | 1         | 10%     |
| Unknown | 1         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Canon LBP6030/6030B/6018L | 1         | 100%    |

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 8         | 34.78%  |
| Microdia                    | 3         | 13.04%  |
| Luxvisions Innotech Limited | 2         | 8.7%    |
| IMC Networks                | 2         | 8.7%    |
| Acer                        | 2         | 8.7%    |
| Suyin                       | 1         | 4.35%   |
| Silicon Motion              | 1         | 4.35%   |
| Realtek Semiconductor       | 1         | 4.35%   |
| Lite-On Technology          | 1         | 4.35%   |
| Foxconn / Hon Hai           | 1         | 4.35%   |
| Arkmicro Technologies       | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 8.7%    |
| Acer EasyCamera                                     | 2         | 8.7%    |
| Suyin HP Webcam                                     | 1         | 4.35%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 4.35%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 4.35%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.35%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 4.35%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.35%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4.35%   |
| IMC Networks EasyCamera                             | 1         | 4.35%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 4.35%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.35%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 4.35%   |
| Chicony Integrated Camera                           | 1         | 4.35%   |
| Chicony HP Truevision HD                            | 1         | 4.35%   |
| Chicony Front Camera                                | 1         | 4.35%   |
| Chicony CNA7157                                     | 1         | 4.35%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| AuthenTec        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |
| AuthenTec AES1600                            | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 1         | 50%     |
| Advanced Card Systems | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20        | 66.67%  |
| 1     | 7         | 23.33%  |
| 2     | 3         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 25%     |
| Fingerprint reader       | 2         | 16.67%  |
| Chipcard                 | 2         | 16.67%  |
| Camera                   | 2         | 16.67%  |
| Net/wireless             | 1         | 8.33%   |
| Communication controller | 1         | 8.33%   |
| Bluetooth                | 1         | 8.33%   |
