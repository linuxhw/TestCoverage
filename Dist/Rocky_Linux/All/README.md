Rocky Linux - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Rocky_Linux/Desktop/README.md) and [notebooks](/Dist/Rocky_Linux/Notebook/README.md).

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

Total: 64

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 072T6D A01                  | Server      | [4b88759a98](https://linux-hardware.org/?probe=4b88759a98) | May 06, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | Desktop     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Supermicro    | X11SSH-CTF                  | Server      | [7a720a4e41](https://linux-hardware.org/?probe=7a720a4e41) | Mar 10, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| Supermicro    | X11SPW-TF                   | Server      | [a76bb2e30d](https://linux-hardware.org/?probe=a76bb2e30d) | Feb 07, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [02e5c56a80](https://linux-hardware.org/?probe=02e5c56a80) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [4aa06b4edd](https://linux-hardware.org/?probe=4aa06b4edd) | Feb 03, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | Desktop     | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| Dell          | 0X3D66 A07                  | Server      | [d5c4ef93c4](https://linux-hardware.org/?probe=d5c4ef93c4) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c7f9478d55](https://linux-hardware.org/?probe=c7f9478d55) | Jan 03, 2022 |
| AZW           | Gemini M                    | Desktop     | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | Desktop     | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Panther                     | Desktop     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo        | ThinkPad W540 20BGCTO1WW    | Notebook    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d7947a5a8](https://linux-hardware.org/?probe=9d7947a5a8) | Nov 06, 2021 |
| Toshiba       | TECRA W50-A                 | Notebook    | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406132G       | Notebook    | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| Acer          | Aspire VN7-591G             | Notebook    | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 30        | 57.69%  |
| Rocky Linux 8.4 | 19        | 36.54%  |
| Rocky Linux 8.3 | 2         | 3.85%   |
| Rocky Linux 8.6 | 1         | 1.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 52        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64 | 13        | 25%     |
| 4.18.0-348.7.1.el8_5.x86_64  | 8         | 15.38%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 6         | 11.54%  |
| 4.18.0-348.20.1.el8_5.x86_64 | 3         | 5.77%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 3         | 5.77%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 3.85%   |
| 4.18.0-305.el8.x86_64        | 2         | 3.85%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 3.85%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 2         | 3.85%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2         | 3.85%   |
| 4.18.0-240.22.1.el8.x86_64   | 2         | 3.85%   |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 1.92%   |
| 5.14.1-1.el8.elrepo.x86_64   | 1         | 1.92%   |
| 5.10.89-1.el8.x86_64         | 1         | 1.92%   |
| 5.10.52-v8.1.el8             | 1         | 1.92%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 1.92%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 1.92%   |
| 4.18.0-348.23.1.el8_5.x86_64 | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 48        | 92.31%  |
| 5.4.157 | 1         | 1.92%   |
| 5.14.1  | 1         | 1.92%   |
| 5.10.89 | 1         | 1.92%   |
| 5.10.52 | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 48        | 92.31%  |
| 5.10    | 2         | 3.85%   |
| 5.4     | 1         | 1.92%   |
| 5.14    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 51        | 98.08%  |
| aarch64 | 1         | 1.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 34        | 65.38%  |
| Unknown       | 7         | 13.46%  |
| KDE5          | 4         | 7.69%   |
| MATE          | 3         | 5.77%   |
| GNOME Classic | 2         | 3.85%   |
| XFCE          | 1         | 1.92%   |
| X-Cinnamon    | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 26        | 50%     |
| X11     | 21        | 40.38%  |
| Unknown | 5         | 9.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 51.92%  |
| GDM     | 20        | 38.46%  |
| SDDM    | 3         | 5.77%   |
| LightDM | 2         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 31        | 59.62%  |
| en_IL   | 3         | 5.77%   |
| ru_RU   | 2         | 3.85%   |
| en_ZA   | 2         | 3.85%   |
| en_SG   | 2         | 3.85%   |
| en_AU   | 2         | 3.85%   |
| de_DE   | 2         | 3.85%   |
| pt_BR   | 1         | 1.92%   |
| pl_PL   | 1         | 1.92%   |
| ja_JP   | 1         | 1.92%   |
| it_IT   | 1         | 1.92%   |
| es_CO   | 1         | 1.92%   |
| en_CA   | 1         | 1.92%   |
| af_ZA   | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 26        | 50%     |
| EFI  | 26        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 39        | 75%     |
| Ext4 | 13        | 25%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 44.23%  |
| GPT     | 18        | 34.62%  |
| MBR     | 11        | 21.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 88.46%  |
| Yes       | 6         | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 90.38%  |
| Yes       | 5         | 9.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 13        | 25%     |
| Dell                    | 13        | 25%     |
| ASUSTek Computer        | 5         | 9.62%   |
| Hewlett-Packard         | 4         | 7.69%   |
| Gigabyte Technology     | 3         | 5.77%   |
| Toshiba                 | 2         | 3.85%   |
| Supermicro              | 2         | 3.85%   |
| Raspberry Pi Foundation | 1         | 1.92%   |
| NCR                     | 1         | 1.92%   |
| MSI                     | 1         | 1.92%   |
| Intel                   | 1         | 1.92%   |
| IBM                     | 1         | 1.92%   |
| Google                  | 1         | 1.92%   |
| AZW                     | 1         | 1.92%   |
| ASRock                  | 1         | 1.92%   |
| Acer                    | 1         | 1.92%   |
| Unknown                 | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge R610                      | 2         | 3.85%   |
| Dell OptiPlex 9020                       | 2         | 3.85%   |
| Toshiba TECRA W50-A                      | 1         | 1.92%   |
| Toshiba Satellite E45-B                  | 1         | 1.92%   |
| Supermicro SYS-5029P-WTR                 | 1         | 1.92%   |
| Supermicro Super Server                  | 1         | 1.92%   |
| RPi Raspberry Pi                         | 1         | 1.92%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 1.92%   |
| MSI MS-7917                              | 1         | 1.92%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 1.92%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 1.92%   |
| Lenovo ThinkPad W500 406132G             | 1         | 1.92%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 1.92%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 1.92%   |
| Lenovo ThinkCentre M72e 36601Y8          | 1         | 1.92%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 1.92%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.92%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU        | 1         | 1.92%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.92%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 1.92%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.92%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 1.92%   |
| Intel S2600WFT                           | 1         | 1.92%   |
| IBM System x3200 M2 -[4368IGS]-          | 1         | 1.92%   |
| HP ZBook 15 G3                           | 1         | 1.92%   |
| HP Z600 Workstation                      | 1         | 1.92%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.92%   |
| HP EliteBook 840 G7 Notebook PC          | 1         | 1.92%   |
| Google Panther                           | 1         | 1.92%   |
| Gigabyte X570 AORUS ULTRA                | 1         | 1.92%   |
| Gigabyte H87-D3H                         | 1         | 1.92%   |
| Gigabyte G41MT-USB3                      | 1         | 1.92%   |
| Dell Vostro 3681                         | 1         | 1.92%   |
| Dell Precision Tower 7810                | 1         | 1.92%   |
| Dell Precision T7610                     | 1         | 1.92%   |
| Dell Precision T5610                     | 1         | 1.92%   |
| Dell PowerEdge R730xd                    | 1         | 1.92%   |
| Dell PowerEdge R720xd                    | 1         | 1.92%   |
| Dell OptiPlex 390                        | 1         | 1.92%   |
| Dell Latitude 5500                       | 1         | 1.92%   |
| Dell Latitude 3420                       | 1         | 1.92%   |
| AZW Gemini M                             | 1         | 1.92%   |
| ASUS PRIME TRX40-PRO S                   | 1         | 1.92%   |
| ASUS PRIME B450M-A II                    | 1         | 1.92%   |
| ASUS PRIME B450-PLUS                     | 1         | 1.92%   |
| ASUS P5Q DELUXE                          | 1         | 1.92%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 1.92%   |
| ASRock B450M Pro4                        | 1         | 1.92%   |
| Acer Aspire VN7-591G                     | 1         | 1.92%   |
| Unknown                                  | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 5         | 9.62%   |
| Lenovo IdeaPad           | 4         | 7.69%   |
| Dell PowerEdge           | 4         | 7.69%   |
| Dell Precision           | 3         | 5.77%   |
| Dell OptiPlex            | 3         | 5.77%   |
| ASUS PRIME               | 3         | 5.77%   |
| Lenovo Legion            | 2         | 3.85%   |
| Dell Latitude            | 2         | 3.85%   |
| Toshiba TECRA            | 1         | 1.92%   |
| Toshiba Satellite        | 1         | 1.92%   |
| Supermicro SYS-5029P-WTR | 1         | 1.92%   |
| Supermicro Super         | 1         | 1.92%   |
| RPi Raspberry            | 1         | 1.92%   |
| NCR xxxx-xxxx-xxxx       | 1         | 1.92%   |
| MSI MS-7917              | 1         | 1.92%   |
| Lenovo ThinkCentre       | 1         | 1.92%   |
| Lenovo IdeaPadFlex       | 1         | 1.92%   |
| Intel S2600WFT           | 1         | 1.92%   |
| IBM System               | 1         | 1.92%   |
| HP ZBook                 | 1         | 1.92%   |
| HP Z600                  | 1         | 1.92%   |
| HP Laptop                | 1         | 1.92%   |
| HP EliteBook             | 1         | 1.92%   |
| Google Panther           | 1         | 1.92%   |
| Gigabyte X570            | 1         | 1.92%   |
| Gigabyte H87-D3H         | 1         | 1.92%   |
| Gigabyte G41MT-USB3      | 1         | 1.92%   |
| Dell Vostro              | 1         | 1.92%   |
| AZW Gemini               | 1         | 1.92%   |
| ASUS P5Q                 | 1         | 1.92%   |
| ASUS ASUS                | 1         | 1.92%   |
| ASRock B450M             | 1         | 1.92%   |
| Acer Aspire              | 1         | 1.92%   |
| Unknown                  | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 8         | 15.38%  |
| 2021    | 6         | 11.54%  |
| 2014    | 6         | 11.54%  |
| 2019    | 5         | 9.62%   |
| 2018    | 5         | 9.62%   |
| 2015    | 4         | 7.69%   |
| 2013    | 4         | 7.69%   |
| 2011    | 4         | 7.69%   |
| 2016    | 2         | 3.85%   |
| 2009    | 2         | 3.85%   |
| 2008    | 2         | 3.85%   |
| 2022    | 1         | 1.92%   |
| 2012    | 1         | 1.92%   |
| 2010    | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 22        | 42.31%  |
| Notebook       | 20        | 38.46%  |
| Server         | 8         | 15.38%  |
| System on chip | 1         | 1.92%   |
| Convertible    | 1         | 1.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 98.08%  |
| Yes  | 1         | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 13        | 25%     |
| 32.01-64.0      | 9         | 17.31%  |
| 16.01-24.0      | 9         | 17.31%  |
| 8.01-16.0       | 8         | 15.38%  |
| 3.01-4.0        | 4         | 7.69%   |
| More than 256.0 | 3         | 5.77%   |
| 1.01-2.0        | 3         | 5.77%   |
| 64.01-256.0     | 2         | 3.85%   |
| 2.01-3.0        | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 26.92%  |
| 3.01-4.0  | 13        | 25%     |
| 1.01-2.0  | 11        | 21.15%  |
| 4.01-8.0  | 10        | 19.23%  |
| 8.01-16.0 | 2         | 3.85%   |
| 0.51-1.0  | 1         | 1.92%   |
| 0.01-0.5  | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 50%     |
| 2      | 12        | 23.08%  |
| 3      | 6         | 11.54%  |
| 4      | 4         | 7.69%   |
| 18     | 1         | 1.92%   |
| 16     | 1         | 1.92%   |
| 14     | 1         | 1.92%   |
| 8      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 61.54%  |
| Yes       | 20        | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 94.23%  |
| No        | 3         | 5.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 59.62%  |
| No        | 21        | 40.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 50%     |
| No        | 26        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 26.92%  |
| South Africa | 3         | 5.77%   |
| Singapore    | 3         | 5.77%   |
| Israel       | 3         | 5.77%   |
| Czechia      | 3         | 5.77%   |
| Russia       | 2         | 3.85%   |
| Poland       | 2         | 3.85%   |
| India        | 2         | 3.85%   |
| Germany      | 2         | 3.85%   |
| Canada       | 2         | 3.85%   |
| Belgium      | 2         | 3.85%   |
| Australia    | 2         | 3.85%   |
| UK           | 1         | 1.92%   |
| Slovakia     | 1         | 1.92%   |
| Portugal     | 1         | 1.92%   |
| Mexico       | 1         | 1.92%   |
| Malaysia     | 1         | 1.92%   |
| Kazakhstan   | 1         | 1.92%   |
| Japan        | 1         | 1.92%   |
| Italy        | 1         | 1.92%   |
| France       | 1         | 1.92%   |
| Colombia     | 1         | 1.92%   |
| China        | 1         | 1.92%   |
| Brazil       | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Singapore              | 3         | 5.77%   |
| Prague                 | 2         | 3.85%   |
| Melbourne              | 2         | 3.85%   |
| Haifa                  | 2         | 3.85%   |
| Centurion              | 2         | 3.85%   |
| ??ilina                | 1         | 1.92%   |
| Xi'an                  | 1         | 1.92%   |
| Waltham                | 1         | 1.92%   |
| Toronto                | 1         | 1.92%   |
| St Petersburg          | 1         | 1.92%   |
| Sobral de Monte Agraco | 1         | 1.92%   |
| Senigallia             | 1         | 1.92%   |
| Scarborough            | 1         | 1.92%   |
| Rehovot                | 1         | 1.92%   |
| Progresista            | 1         | 1.92%   |
| Philadelphia           | 1         | 1.92%   |
| Paris                  | 1         | 1.92%   |
| Ottignies              | 1         | 1.92%   |
| ??tsu                  | 1         | 1.92%   |
| Oakley                 | 1         | 1.92%   |
| Nur-Sultan             | 1         | 1.92%   |
| New York               | 1         | 1.92%   |
| Mossel Bay             | 1         | 1.92%   |
| Moscow                 | 1         | 1.92%   |
| Mequon                 | 1         | 1.92%   |
| Manassas               | 1         | 1.92%   |
| Lebanon                | 1         | 1.92%   |
| Kutno                  | 1         | 1.92%   |
| Krasova                | 1         | 1.92%   |
| Krakow                 | 1         | 1.92%   |
| Johor Bahru            | 1         | 1.92%   |
| Ja??                   | 1         | 1.92%   |
| Imphal                 | 1         | 1.92%   |
| Houston                | 1         | 1.92%   |
| Glasgow                | 1         | 1.92%   |
| Fredericton            | 1         | 1.92%   |
| Fredericksburg         | 1         | 1.92%   |
| Forest                 | 1         | 1.92%   |
| Dreieich               | 1         | 1.92%   |
| Corvallis              | 1         | 1.92%   |
| Burlington             | 1         | 1.92%   |
| Bucaramanga            | 1         | 1.92%   |
| Brussels               | 1         | 1.92%   |
| Berlin                 | 1         | 1.92%   |
| Bengaluru              | 1         | 1.92%   |
| Ashburn                | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 14        | 42     | 16.87%  |
| WDC                     | 11        | 23     | 13.25%  |
| Samsung Electronics     | 11        | 13     | 13.25%  |
| Toshiba                 | 9         | 9      | 10.84%  |
| Intel                   | 4         | 5      | 4.82%   |
| Unknown                 | 3         | 3      | 3.61%   |
| SK hynix                | 3         | 4      | 3.61%   |
| Hitachi                 | 3         | 4      | 3.61%   |
| SanDisk                 | 2         | 2      | 2.41%   |
| Phison                  | 2         | 2      | 2.41%   |
| Kingston                | 2         | 2      | 2.41%   |
| Crucial                 | 2         | 2      | 2.41%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.2%    |
| UMIS                    | 1         | 1      | 1.2%    |
| StoreJet                | 1         | 1      | 1.2%    |
| PNY                     | 1         | 1      | 1.2%    |
| LITEONIT                | 1         | 1      | 1.2%    |
| LITEON                  | 1         | 1      | 1.2%    |
| IBM                     | 1         | 1      | 1.2%    |
| HGST                    | 1         | 1      | 1.2%    |
| Gigabyte Technology     | 1         | 1      | 1.2%    |
| Fujitsu                 | 1         | 1      | 1.2%    |
| Dogfish                 | 1         | 1      | 1.2%    |
| Corsair                 | 1         | 1      | 1.2%    |
| China                   | 1         | 1      | 1.2%    |
| Apacer                  | 1         | 1      | 1.2%    |
| AGI                     | 1         | 1      | 1.2%    |
| ADATA Technology        | 1         | 1      | 1.2%    |
| A-DATA Technology       | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                       | 2         | 2.13%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 2.13%   |
| Seagate ST300MP0005 304GB                    | 2         | 2.13%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1.06%   |
| WDC WD80EZZX-11CSGA0 8TB                     | 1         | 1.06%   |
| WDC WD80EMAZ-00WJTA0 8TB                     | 1         | 1.06%   |
| WDC WD80EDAZ-11TA3A0 8TB                     | 1         | 1.06%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 1.06%   |
| WDC WD5000AAKX-75U6AA0 500GB                 | 1         | 1.06%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1         | 1.06%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1.06%   |
| WDC WD2500AAJS-22VTA0 250GB                  | 1         | 1.06%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 1.06%   |
| WDC WD120EDAZ-11F3RA0 12TB                   | 1         | 1.06%   |
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1.06%   |
| WDC WD100EMAZ-00WJTA0 10TB                   | 1         | 1.06%   |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 1.06%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB         | 1         | 1.06%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 1.06%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.06%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 1.06%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 1.06%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 1.06%   |
| Toshiba PX05SVB192Y 1.9TB                    | 1         | 1.06%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.06%   |
| Toshiba MG07ACA12TE 12TB                     | 1         | 1.06%   |
| Toshiba MG04ACA400E 4TB                      | 1         | 1.06%   |
| Toshiba MG03ACA400 4TB                       | 1         | 1.06%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1.06%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1.06%   |
| StoreJet Disk 2TB                            | 1         | 1.06%   |
| SK hynix SHGS31-1000GS-2 1TB SSD             | 1         | 1.06%   |
| SK hynix SH920 2.5 7MM 256GB SSD             | 1         | 1.06%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.06%   |
| SK hynix BC511 NVMe 512GB                    | 1         | 1.06%   |
| Seagate ST91000640SS 1TB                     | 1         | 1.06%   |
| Seagate ST8000DM004-2CX188 8TB               | 1         | 1.06%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 1.06%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1         | 1.06%   |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 1.06%   |
| Seagate ST3160318AS 160GB                    | 1         | 1.06%   |
| Seagate ST2000NX0433 2TB                     | 1         | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1.06%   |
| Seagate ST1000VX005-2EZ102 1TB               | 1         | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1.06%   |
| Seagate BUP Slim BL 1TB                      | 1         | 1.06%   |
| SanDisk SSD U110 16GB                        | 1         | 1.06%   |
| SanDisk SD5SG2256G1052E 256GB SSD            | 1         | 1.06%   |
| Samsung SSD 980 PRO 1TB                      | 1         | 1.06%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 1.06%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 1.06%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 1.06%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 1.06%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 1.06%   |
| Samsung SSD 860 EVO 1TB                      | 1         | 1.06%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 1.06%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 42     | 37.84%  |
| WDC                 | 9         | 20     | 24.32%  |
| Toshiba             | 5         | 5      | 13.51%  |
| Hitachi             | 3         | 4      | 8.11%   |
| Unknown             | 1         | 1      | 2.7%    |
| StoreJet            | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| IBM                 | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 23.08%  |
| Toshiba             | 3         | 3      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| SK hynix            | 2         | 2      | 7.69%   |
| SanDisk             | 2         | 2      | 7.69%   |
| PNY                 | 1         | 1      | 3.85%   |
| LITEONIT            | 1         | 1      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| Intel               | 1         | 2      | 3.85%   |
| Gigabyte Technology | 1         | 1      | 3.85%   |
| Dogfish             | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |
| Corsair             | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| Apacer              | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 77     | 39.13%  |
| SSD     | 22        | 28     | 31.88%  |
| NVMe    | 17        | 20     | 24.64%  |
| MMC     | 2         | 2      | 2.9%    |
| Unknown | 1         | 1      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 102    | 62.9%   |
| NVMe | 17        | 20     | 27.42%  |
| SAS  | 4         | 4      | 6.45%   |
| MMC  | 2         | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 38     | 44.44%  |
| 0.51-1.0   | 16        | 22     | 29.63%  |
| 1.01-2.0   | 6         | 9      | 11.11%  |
| 3.01-4.0   | 4         | 20     | 7.41%   |
| 10.01-20.0 | 2         | 3      | 3.7%    |
| 2.01-3.0   | 1         | 1      | 1.85%   |
| 4.01-10.0  | 1         | 12     | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 30.77%  |
| 251-500        | 9         | 17.31%  |
| 501-1000       | 8         | 15.38%  |
| More than 3000 | 6         | 11.54%  |
| 1001-2000      | 6         | 11.54%  |
| 2001-3000      | 3         | 5.77%   |
| 51-100         | 2         | 3.85%   |
| 1-20           | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 17        | 32.69%  |
| 21-50          | 12        | 23.08%  |
| 101-250        | 5         | 9.62%   |
| 51-100         | 5         | 9.62%   |
| More than 3000 | 3         | 5.77%   |
| 251-500        | 3         | 5.77%   |
| 501-1000       | 3         | 5.77%   |
| 1001-2000      | 2         | 3.85%   |
| 2001-3000      | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 12.5%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 12.5%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 12.5%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 12.5%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 12.5%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 12.5%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 13     | 37.5%   |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 4      | 12.5%   |
| IBM     | 1         | 1      | 12.5%   |
| Corsair | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 13     | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| WDC     | 1         | 4      | 14.29%  |
| IBM     | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 20     | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 27        | 67     | 45%     |
| Detected | 25        | 40     | 41.67%  |
| Malfunc  | 8         | 21     | 13.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 54.29%  |
| AMD                          | 8         | 11.43%  |
| Samsung Electronics          | 4         | 5.71%   |
| LSI Logic / Symbios Logic    | 4         | 5.71%   |
| Broadcom / LSI               | 3         | 4.29%   |
| Phison Electronics           | 2         | 2.86%   |
| Union Memory (Shenzhen)      | 1         | 1.43%   |
| Toshiba America Info Systems | 1         | 1.43%   |
| SK hynix                     | 1         | 1.43%   |
| SanDisk                      | 1         | 1.43%   |
| Realtek Semiconductor        | 1         | 1.43%   |
| Micron/Crucial Technology    | 1         | 1.43%   |
| Marvell Technology Group     | 1         | 1.43%   |
| Kingston Technology Company  | 1         | 1.43%   |
| ASMedia Technology           | 1         | 1.43%   |
| ADATA Technology             | 1         | 1.43%   |
| Adaptec                      | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 7.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 4.55%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 3.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.27%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 2.27%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 2.27%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 2.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.27%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.27%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2         | 2.27%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.14%   |
| SK hynix BC511                                                                          | 1         | 1.14%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 1.14%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.14%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 1.14%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1         | 1.14%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.14%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 1.14%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 1         | 1.14%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 1         | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 1.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.14%   |
| Intel SSD 660P Series                                                                   | 1         | 1.14%   |
| Intel PCIe Data Center SSD                                                              | 1         | 1.14%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                                | 1         | 1.14%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.14%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1         | 1.14%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.14%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 1.14%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 1.14%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.14%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1.14%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1         | 1.14%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 1         | 1.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.14%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1         | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.14%   |
| ADATA Non-Volatile memory controller                                                    | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 42.47%  |
| NVMe | 17        | 23.29%  |
| IDE  | 13        | 17.81%  |
| RAID | 8         | 10.96%  |
| SAS  | 3         | 4.11%   |
| SCSI | 1         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 76.92%  |
| AMD    | 11        | 21.15%  |
| ARM    | 1         | 1.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Xeon CPU L5530 @ 2.40GHz                 | 2         | 3.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 3.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2         | 3.85%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz           | 1         | 1.92%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz             | 1         | 1.92%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1         | 1.92%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1         | 1.92%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz            | 1         | 1.92%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz             | 1         | 1.92%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1         | 1.92%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1         | 1.92%   |
| Intel Xeon CPU E3110 @ 3.00GHz                 | 1         | 1.92%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz            | 1         | 1.92%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1         | 1.92%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1         | 1.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 1         | 1.92%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz             | 1         | 1.92%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz             | 1         | 1.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1         | 1.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.92%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz             | 1         | 1.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.92%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1         | 1.92%   |
| Intel Core i7-10610U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i5-8365U CPU @ 1.60GHz              | 1         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.92%   |
| Intel Core i5-3427U CPU @ 1.80GHz              | 1         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 1         | 1.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1         | 1.92%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 1.92%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.92%   |
| ARM Processor                                  | 1         | 1.92%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1         | 1.92%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 1.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 1         | 1.92%   |
| AMD Ryzen 7 4800H with Radeon Graphics         | 1         | 1.92%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1         | 1.92%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics     | 1         | 1.92%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 1         | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 1.92%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1         | 1.92%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 14        | 26.92%  |
| Intel Xeon              | 10        | 19.23%  |
| Intel Core i5           | 6         | 11.54%  |
| Other                   | 3         | 5.77%   |
| AMD Ryzen 7             | 3         | 5.77%   |
| AMD Ryzen 5             | 3         | 5.77%   |
| Intel Celeron           | 2         | 3.85%   |
| Intel Xeon Silver       | 1         | 1.92%   |
| Intel Xeon Gold         | 1         | 1.92%   |
| Intel Pentium Dual-Core | 1         | 1.92%   |
| Intel Pentium Dual      | 1         | 1.92%   |
| Intel Core i3           | 1         | 1.92%   |
| Intel Core 2 Quad       | 1         | 1.92%   |
| Intel Core 2 Duo        | 1         | 1.92%   |
| AMD Ryzen Threadripper  | 1         | 1.92%   |
| AMD Ryzen 9             | 1         | 1.92%   |
| AMD Ryzen 5 PRO         | 1         | 1.92%   |
| AMD Ryzen 3             | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 21        | 40.38%  |
| 2      | 11        | 21.15%  |
| 8      | 9         | 17.31%  |
| 6      | 4         | 7.69%   |
| 16     | 2         | 3.85%   |
| 12     | 2         | 3.85%   |
| 32     | 1         | 1.92%   |
| 28     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 86.54%  |
| 2      | 7         | 13.46%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 69.23%  |
| 1      | 16        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 7         | 13.46%  |
| 0x506e3    | 3         | 5.77%   |
| 0x206a7    | 3         | 5.77%   |
| 0x806ec    | 2         | 3.85%   |
| 0x40651    | 2         | 3.85%   |
| 0x306e4    | 2         | 3.85%   |
| 0x306a9    | 2         | 3.85%   |
| 0x106a5    | 2         | 3.85%   |
| 0x10676    | 2         | 3.85%   |
| 0x08600104 | 2         | 3.85%   |
| Unknown    | 2         | 3.85%   |
| 0xa0655    | 1         | 1.92%   |
| 0xa0652    | 1         | 1.92%   |
| 0x806c1    | 1         | 1.92%   |
| 0x706a8    | 1         | 1.92%   |
| 0x6fd      | 1         | 1.92%   |
| 0x50657    | 1         | 1.92%   |
| 0x50654    | 1         | 1.92%   |
| 0x406f1    | 1         | 1.92%   |
| 0x406e3    | 1         | 1.92%   |
| 0x306f2    | 1         | 1.92%   |
| 0x206d7    | 1         | 1.92%   |
| 0x206c2    | 1         | 1.92%   |
| 0x1067a    | 1         | 1.92%   |
| 0x10677    | 1         | 1.92%   |
| 0x0a50000c | 1         | 1.92%   |
| 0x0a201009 | 1         | 1.92%   |
| 0x0870100a | 1         | 1.92%   |
| 0x08608103 | 1         | 1.92%   |
| 0x08301039 | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |
| 0x08108102 | 1         | 1.92%   |
| 0x0800820d | 1         | 1.92%   |
| 0x06006705 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 11        | 21.15%  |
| Skylake       | 6         | 11.54%  |
| Zen 2         | 4         | 7.69%   |
| SandyBridge   | 4         | 7.69%   |
| Penryn        | 4         | 7.69%   |
| IvyBridge     | 4         | 7.69%   |
| Zen+          | 3         | 5.77%   |
| Zen 3         | 2         | 3.85%   |
| Nehalem       | 2         | 3.85%   |
| KabyLake      | 2         | 3.85%   |
| CometLake     | 2         | 3.85%   |
| Unknown       | 2         | 3.85%   |
| Westmere      | 1         | 1.92%   |
| TigerLake     | 1         | 1.92%   |
| Goldmont plus | 1         | 1.92%   |
| Excavator     | 1         | 1.92%   |
| Core          | 1         | 1.92%   |
| Broadwell     | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 24        | 37.5%   |
| Nvidia                     | 23        | 35.94%  |
| AMD                        | 10        | 15.63%  |
| Matrox Electronics Systems | 4         | 6.25%   |
| ASPEED Technology          | 3         | 4.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 4.69%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3         | 4.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 3.13%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 2         | 3.13%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 3.13%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 3.13%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 3.13%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.56%   |
| Nvidia TU117GL [T600]                                                       | 1         | 1.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.56%   |
| Nvidia GP107GL [Quadro P400]                                                | 1         | 1.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.56%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.56%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 1.56%   |
| Nvidia GM107GLM [Quadro M1000M]                                             | 1         | 1.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.56%   |
| Nvidia GK107M [GeForce GT 755M]                                             | 1         | 1.56%   |
| Nvidia GK107GL [Quadro K600]                                                | 1         | 1.56%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.56%   |
| Nvidia GK104GL [GRID K2]                                                    | 1         | 1.56%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.56%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.56%   |
| Intel HD Graphics P530                                                      | 1         | 1.56%   |
| Intel HD Graphics 530                                                       | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1         | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1         | 1.56%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                     | 1         | 1.56%   |
| AMD Renoir                                                                  | 1         | 1.56%   |
| AMD Lucienne                                                                | 1         | 1.56%   |
| AMD ES1000                                                                  | 1         | 1.56%   |
| AMD Cezanne                                                                 | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 13        | 25%     |
| 1 x Nvidia      | 12        | 23.08%  |
| Intel + Nvidia  | 9         | 17.31%  |
| 1 x AMD         | 8         | 15.38%  |
| 1 x Matrox      | 3         | 5.77%   |
| 1 x ASPEED      | 3         | 5.77%   |
| Other           | 1         | 1.92%   |
| Nvidia + Matrox | 1         | 1.92%   |
| Intel + AMD     | 1         | 1.92%   |
| AMD + Nvidia    | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 39        | 75%     |
| Proprietary | 10        | 19.23%  |
| Unknown     | 3         | 5.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 48.08%  |
| 1.01-2.0   | 8         | 15.38%  |
| 0.01-0.5   | 8         | 15.38%  |
| 3.01-4.0   | 4         | 7.69%   |
| 5.01-6.0   | 3         | 5.77%   |
| 0.51-1.0   | 3         | 5.77%   |
| 8.01-16.0  | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 10        | 18.18%  |
| Samsung Electronics | 5         | 9.09%   |
| LG Display          | 5         | 9.09%   |
| AU Optronics        | 5         | 9.09%   |
| Goldstar            | 4         | 7.27%   |
| Chimei Innolux      | 4         | 7.27%   |
| BOE                 | 4         | 7.27%   |
| AOC                 | 3         | 5.45%   |
| Philips             | 2         | 3.64%   |
| Iiyama              | 2         | 3.64%   |
| Acer                | 2         | 3.64%   |
| Sony                | 1         | 1.82%   |
| PANDA               | 1         | 1.82%   |
| Panasonic           | 1         | 1.82%   |
| Lenovo              | 1         | 1.82%   |
| IBM                 | 1         | 1.82%   |
| Hewlett-Packard     | 1         | 1.82%   |
| HCL                 | 1         | 1.82%   |
| ASUSTek Computer    | 1         | 1.82%   |
| ADR                 | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LG TV SNY045B 1920x540                                           | 1         | 1.72%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 1.72%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 1.72%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 1.72%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.72%   |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 1.72%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 1.72%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 1.72%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.72%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.72%   |
| Lenovo LCD Monitor LEN4055 1920x1200 330x210mm 15.4-inch              | 1         | 1.72%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1         | 1.72%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1         | 1.72%   |
| IBM RSA2 IBM029A 1024x768 300x225mm 14.8-inch                         | 1         | 1.72%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1         | 1.72%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1         | 1.72%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 1.72%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 1.72%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.72%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 1.72%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                     | 1         | 1.72%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 1.72%   |
| Dell S2421HS DEL41F4 1920x1080 527x296mm 23.8-inch                    | 1         | 1.72%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.72%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                      | 1         | 1.72%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                       | 1         | 1.72%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1         | 1.72%   |
| Dell LCD Monitor U2414H                                               | 1         | 1.72%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                     | 1         | 1.72%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 1.72%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 1.72%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14E6 1366x768 309x173mm 13.9-inch       | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 1         | 1.72%   |
| BOE LCD Monitor BOE09F0 1920x1080 309x174mm 14.0-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 1.72%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 1.72%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch          | 1         | 1.72%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1         | 1.72%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 1.72%   |
| AOC 1620 AOC1620 1366x768 340x190mm 15.3-inch                         | 1         | 1.72%   |
| ADR KVM-via-IP ADR0219 1280x1024                                      | 1         | 1.72%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 1         | 1.72%   |
| Acer G277HL ACR03FB 1920x1080 598x336mm 27.0-inch                     | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 42%     |
| 1600x900 (HD+)     | 5         | 10%     |
| 3840x2160 (4K)     | 3         | 6%      |
| 1366x768 (WXGA)    | 3         | 6%      |
| 1280x1024 (SXGA)   | 3         | 6%      |
| 3840x1080          | 2         | 4%      |
| 1920x1200 (WUXGA)  | 2         | 4%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 1440x900 (WXGA+)   | 2         | 4%      |
| Unknown            | 2         | 4%      |
| 3440x1440          | 1         | 2%      |
| 2560x1440 (QHD)    | 1         | 2%      |
| 2560x1080          | 1         | 2%      |
| 1920x540           | 1         | 2%      |
| 1024x768 (XGA)     | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 18.18%  |
| 27      | 8         | 14.55%  |
| 14      | 8         | 14.55%  |
| 17      | 4         | 7.27%   |
| 23      | 3         | 5.45%   |
| 21      | 3         | 5.45%   |
| 19      | 3         | 5.45%   |
| 13      | 3         | 5.45%   |
| 34      | 2         | 3.64%   |
| 24      | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| 65      | 1         | 1.82%   |
| 48      | 1         | 1.82%   |
| 31      | 1         | 1.82%   |
| 28      | 1         | 1.82%   |
| 22      | 1         | 1.82%   |
| 20      | 1         | 1.82%   |
| 18      | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 40%     |
| 501-600     | 13        | 23.64%  |
| 401-500     | 10        | 18.18%  |
| 701-800     | 2         | 3.64%   |
| 351-400     | 2         | 3.64%   |
| 1001-1500   | 2         | 3.64%   |
| Unknown     | 2         | 3.64%   |
| 601-700     | 1         | 1.82%   |
| 201-300     | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 32        | 69.57%  |
| 16/10   | 4         | 8.7%    |
| 5/4     | 3         | 6.52%   |
| 3/2     | 2         | 4.35%   |
| 21/9    | 2         | 4.35%   |
| 4/3     | 1         | 2.17%   |
| 32/9    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 18.52%  |
| 101-110        | 10        | 18.52%  |
| 301-350        | 8         | 14.81%  |
| 201-250        | 7         | 12.96%  |
| 151-200        | 5         | 9.26%   |
| 351-500        | 4         | 7.41%   |
| 141-150        | 3         | 5.56%   |
| 121-130        | 2         | 3.7%    |
| Unknown        | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 501-1000       | 1         | 1.85%   |
| 91-100         | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 40.74%  |
| 121-160       | 20        | 37.04%  |
| 101-120       | 7         | 12.96%  |
| Unknown       | 2         | 3.7%    |
| More than 240 | 1         | 1.85%   |
| 1-50          | 1         | 1.85%   |
| 161-240       | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 53.85%  |
| 0     | 11        | 21.15%  |
| 2     | 10        | 19.23%  |
| 3     | 2         | 3.85%   |
| 4     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 33        | 44%     |
| Realtek Semiconductor     | 21        | 28%     |
| Broadcom                  | 5         | 6.67%   |
| Qualcomm Atheros          | 4         | 5.33%   |
| Mellanox Technologies     | 3         | 4%      |
| Marvell Technology Group  | 2         | 2.67%   |
| Solarflare Communications | 1         | 1.33%   |
| Ralink Technology         | 1         | 1.33%   |
| Microsoft                 | 1         | 1.33%   |
| MediaTek                  | 1         | 1.33%   |
| Linksys                   | 1         | 1.33%   |
| BUFFALO                   | 1         | 1.33%   |
| Broadcom Limited          | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 19        | 21.11%  |
| Intel Ethernet Connection I217-LM                                                                                      | 5         | 5.56%   |
| Intel Wireless 7260                                                                                                    | 4         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 4         | 4.44%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 3         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 2         | 2.22%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 2.22%   |
| Intel Wireless 8260                                                                                                    | 2         | 2.22%   |
| Intel Wireless 3165                                                                                                    | 2         | 2.22%   |
| Intel I211 Gigabit Network Connection                                                                                  | 2         | 2.22%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 2         | 2.22%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 2         | 2.22%   |
| Solarflare SFC9020 10G Ethernet Controller                                                                             | 1         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 1         | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                                                                             | 1         | 1.11%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1         | 1.11%   |
| Realtek 802.11ac NIC                                                                                                   | 1         | 1.11%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 1         | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                                              | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                                       | 1         | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                                                       | 1         | 1.11%   |
| Microsoft Xbox 360 Wireless Adapter                                                                                    | 1         | 1.11%   |
| Mellanox MT27700 Family [ConnectX-4]                                                                                   | 1         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1         | 1.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1         | 1.11%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                                                                   | 1         | 1.11%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                                                      | 1         | 1.11%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                                    | 1         | 1.11%   |
| Intel Wireless 7265                                                                                                    | 1         | 1.11%   |
| Intel Wireless 3160                                                                                                    | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 1         | 1.11%   |
| Intel Ultimate N WiFi Link 5300                                                                                        | 1         | 1.11%   |
| Intel I350 Gigabit Network Connection                                                                                  | 1         | 1.11%   |
| Intel Ethernet Virtual Function 700 Series                                                                             | 1         | 1.11%   |
| Intel Ethernet Controller X550                                                                                         | 1         | 1.11%   |
| Intel Ethernet Connection I217-V                                                                                       | 1         | 1.11%   |
| Intel Ethernet Connection (6) I219-LM                                                                                  | 1         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 1         | 1.11%   |
| Intel Ethernet 10G 2P X520 Adapter                                                                                     | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                                                        | 1         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 1         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                                               | 1         | 1.11%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                                                   | 1         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                                                                               | 1         | 1.11%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                                                               | 1         | 1.11%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                                                      | 1         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                                                      | 1         | 1.11%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                                                | 1         | 1.11%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet                                                           | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 67.74%  |
| Qualcomm Atheros      | 3         | 9.68%   |
| Realtek Semiconductor | 2         | 6.45%   |
| Ralink Technology     | 1         | 3.23%   |
| Microsoft             | 1         | 3.23%   |
| MediaTek              | 1         | 3.23%   |
| Linksys               | 1         | 3.23%   |
| BUFFALO               | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 4         | 12.5%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 9.38%   |
| Intel Wireless 8260                                           | 2         | 6.25%   |
| Intel Wireless 3165                                           | 2         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 6.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 3.13%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 3.13%   |
| Realtek 802.11ac NIC                                          | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 3.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1         | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1         | 3.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 3.13%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter           | 1         | 3.13%   |
| Intel Wireless 7265                                           | 1         | 3.13%   |
| Intel Wireless 3160                                           | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 3.13%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 3.13%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]      | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 21        | 42%     |
| Intel                     | 19        | 38%     |
| Broadcom                  | 5         | 10%     |
| Marvell Technology Group  | 2         | 4%      |
| Solarflare Communications | 1         | 2%      |
| Qualcomm Atheros          | 1         | 2%      |
| Broadcom Limited          | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 34.55%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.64%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 3.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 3.64%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 1.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.82%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.82%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.82%   |
| Intel I350 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 1.82%   |
| Intel Ethernet Controller X550                                    | 1         | 1.82%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 1.82%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 1         | 1.82%   |
| Broadcom Limited NetXtreme II BCM57800 1/10 Gigabit Ethernet      | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 58.54%  |
| WiFi     | 31        | 37.8%   |
| Unknown  | 3         | 3.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 62.26%  |
| WiFi     | 19        | 35.85%  |
| Unknown  | 1         | 1.89%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 48.08%  |
| 1     | 19        | 36.54%  |
| 5     | 2         | 3.85%   |
| 3     | 2         | 3.85%   |
| 66    | 1         | 1.92%   |
| 8     | 1         | 1.92%   |
| 4     | 1         | 1.92%   |
| 0     | 1         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 78.85%  |
| Yes  | 11        | 21.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 69.23%  |
| Broadcom                        | 2         | 7.69%   |
| Realtek Semiconductor           | 1         | 3.85%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |
| Integrated System Solution      | 1         | 3.85%   |
| IMC Networks                    | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 11        | 42.31%  |
| Intel Bluetooth Device                                | 3         | 11.54%  |
| Intel AX200 Bluetooth                                 | 3         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1         | 3.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 3.85%   |
| IMC Networks Bluetooth Device                         | 1         | 3.85%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1         | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 3.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 45.71%  |
| Nvidia              | 18        | 25.71%  |
| AMD                 | 12        | 17.14%  |
| Logitech            | 2         | 2.86%   |
| C-Media Electronics | 2         | 2.86%   |
| Hewlett-Packard     | 1         | 1.43%   |
| GN Netcom           | 1         | 1.43%   |
| Conexant Systems    | 1         | 1.43%   |
| ASUSTek Computer    | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 5.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.38%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.38%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.38%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.38%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.19%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.19%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.19%   |
| Logitech Stereo H650e                                                      | 1         | 1.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.19%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.19%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.19%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.19%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.19%   |
| Conexant Systems HP Dock Audio                                             | 1         | 1.19%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.19%   |
| C-Media Electronics SKP PODCAST-300U                                       | 1         | 1.19%   |
| ASUSTek Computer USB Audio                                                 | 1         | 1.19%   |
| AMD High Definition Audio Controller                                       | 1         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 30%     |
| Samsung Electronics | 8         | 26.67%  |
| Unknown             | 3         | 10%     |
| SK hynix            | 3         | 10%     |
| G.Skill             | 3         | 10%     |
| Kingston            | 2         | 6.67%   |
| Crucial             | 1         | 3.33%   |
| Corsair             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                                   | 1         | 3.13%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 3.13%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                              | 1         | 3.13%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                   | 1         | 3.13%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                  | 1         | 3.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s             | 1         | 3.13%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s            | 1         | 3.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 3.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                 | 1         | 3.13%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s             | 1         | 3.13%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s                  | 1         | 3.13%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.13%   |
| Samsung RAM M393B2873DZ1-CF8 1GB DIMM DDR3 1066MT/s                   | 1         | 3.13%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                   | 1         | 3.13%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                  | 1         | 3.13%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                              | 1         | 3.13%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                   | 1         | 3.13%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                    | 1         | 3.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s         | 1         | 3.13%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s                  | 1         | 3.13%   |
| Micron RAM 36ASF4G72PZ-2G3D1 32GB DIMM DDR4 2400MT/s                  | 1         | 3.13%   |
| Micron RAM 3138485446313238373241592D3636374631 1GB DIMM DDR2 667MT/s | 1         | 3.13%   |
| Micron RAM 18ASF2G72AZ-2G3A1 16GB DIMM DDR4 2400MT/s                  | 1         | 3.13%   |
| Micron RAM 18ASF1G72PDZ-2G6F1 8GB DIMM DDR4 2666MT/s                  | 1         | 3.13%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s                   | 1         | 3.13%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 3.13%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s                 | 1         | 3.13%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s                   | 1         | 3.13%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s                  | 1         | 3.13%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s                    | 1         | 3.13%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s                  | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 51.72%  |
| DDR3    | 10        | 34.48%  |
| DDR2    | 2         | 6.9%    |
| LPDDR4  | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 20        | 68.97%  |
| SODIMM       | 7         | 24.14%  |
| Row Of Chips | 1         | 3.45%   |
| RIMM         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 40%     |
| 16384 | 5         | 16.67%  |
| 1024  | 5         | 16.67%  |
| 32768 | 4         | 13.33%  |
| 4096  | 2         | 6.67%   |
| 2048  | 2         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 20%     |
| 2667  | 4         | 13.33%  |
| 2400  | 3         | 10%     |
| 1600  | 3         | 10%     |
| 667   | 3         | 10%     |
| 2666  | 2         | 6.67%   |
| 2133  | 2         | 6.67%   |
| 1066  | 2         | 6.67%   |
| 4266  | 1         | 3.33%   |
| 2933  | 1         | 3.33%   |
| 2200  | 1         | 3.33%   |
| 1866  | 1         | 3.33%   |
| 1800  | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother HL-2030 Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP OfficeJet 6110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 6         | 24%     |
| Syntek                      | 4         | 16%     |
| Logitech                    | 3         | 12%     |
| Realtek Semiconductor       | 2         | 8%      |
| IMC Networks                | 2         | 8%      |
| Quanta                      | 1         | 4%      |
| Microdia                    | 1         | 4%      |
| Luxvisions Innotech Limited | 1         | 4%      |
| Lenovo                      | 1         | 4%      |
| Intel                       | 1         | 4%      |
| Huawei Technologies         | 1         | 4%      |
| Apple                       | 1         | 4%      |
| Acer                        | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 16%     |
| Syntek Lenovo EasyCamera                 | 2         | 8%      |
| Syntek Integrated Camera                 | 2         | 8%      |
| Realtek Integrated_Webcam_HD             | 1         | 4%      |
| Realtek EasyCamera                       | 1         | 4%      |
| Quanta HP Webcam                         | 1         | 4%      |
| Microdia Integrated_Webcam_HD            | 1         | 4%      |
| Luxvisions Innotech Limited HP HD Camera | 1         | 4%      |
| Logitech Webcam C270                     | 1         | 4%      |
| Logitech HD Pro Webcam C920              | 1         | 4%      |
| Logitech BRIO Ultra HD Webcam            | 1         | 4%      |
| Lenovo UVC Camera                        | 1         | 4%      |
| Intel RealSense 3D Camera (Front F200)   | 1         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 4%      |
| IMC Networks TOSHIBA Web Camera - HD     | 1         | 4%      |
| Huawei UVC Camera                        | 1         | 4%      |
| Chicony HP HD Camera                     | 1         | 4%      |
| Chicony HD WebCam                        | 1         | 4%      |
| Apple iPhone 5/5C/5S/6/SE                | 1         | 4%      |
| Acer Integrated Camera                   | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 2         | 33.33%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 16.67%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| AuthenTec AES2810                                         | 1         | 16.67%  |
| Unknown                                                   | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 28        | 53.85%  |
| 1     | 17        | 32.69%  |
| 2     | 5         | 9.62%   |
| 5     | 1         | 1.92%   |
| 4     | 1         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 19.35%  |
| Net/wireless             | 5         | 16.13%  |
| Unassigned class         | 4         | 12.9%   |
| Graphics card            | 4         | 12.9%   |
| Communication controller | 4         | 12.9%   |
| Network                  | 2         | 6.45%   |
| Net/ethernet             | 2         | 6.45%   |
| Chipcard                 | 2         | 6.45%   |
| Multimedia controller    | 1         | 3.23%   |
| Card reader              | 1         | 3.23%   |

