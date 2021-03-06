Ubuntu Studio - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

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

Total: 59

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X580... | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Getac         | S400G3                      | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Acer          | Aspire A114-32              | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Dell          | XPS 15 9570                 | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Google        | Nami                        | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| Dell          | Inspiron 3501               | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| Toshiba       | Satellite C855              | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| Intel Clie... | LAPBC510                    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | X541NA                      | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| Sony          | VGN-NS31M_W                 | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | U56E                        | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Dell          | Latitude E6530              | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| Dell          | Latitude E7250              | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| HP            | Compaq 8510p                | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASUSTek       | 1001P                       | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| Dell          | Inspiron 5566               | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| HP            | Notebook                    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 35        | 71.43%  |
| Ubuntu Studio 21.10 | 3         | 6.12%   |
| Ubuntu Studio 21.04 | 3         | 6.12%   |
| Ubuntu Studio 20.10 | 3         | 6.12%   |
| Ubuntu Studio 22.04 | 2         | 4.08%   |
| Ubuntu Studio 18.04 | 2         | 4.08%   |
| Ubuntu Studio 19.10 | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-52-lowlatency     | 3         | 6%      |
| 5.13.0-28-lowlatency    | 3         | 6%      |
| 5.8.0-55-lowlatency     | 2         | 4%      |
| 5.4.0-94-lowlatency     | 2         | 4%      |
| 5.4.0-65-lowlatency     | 2         | 4%      |
| 5.4.0-45-lowlatency     | 2         | 4%      |
| 5.4.0-42-lowlatency     | 2         | 4%      |
| 5.13.0-30-lowlatency    | 2         | 4%      |
| 5.11.0-34-lowlatency    | 2         | 4%      |
| 5.11.0-27-lowlatency    | 2         | 4%      |
| 5.8.0-59-lowlatency     | 1         | 2%      |
| 5.8.0-50-lowlatency     | 1         | 2%      |
| 5.8.0-44-lowlatency     | 1         | 2%      |
| 5.8.0-43-lowlatency     | 1         | 2%      |
| 5.8.0-34-generic        | 1         | 2%      |
| 5.8.0-29-lowlatency     | 1         | 2%      |
| 5.8.0-25-lowlatency     | 1         | 2%      |
| 5.7.6-050706-lowlatency | 1         | 2%      |
| 5.7.6-050706-generic    | 1         | 2%      |
| 5.4.0-96-lowlatency     | 1         | 2%      |
| 5.4.0-88-lowlatency     | 1         | 2%      |
| 5.4.0-52-generic        | 1         | 2%      |
| 5.4.0-45-generic        | 1         | 2%      |
| 5.4.0-34-lowlatency     | 1         | 2%      |
| 5.4.0-26-lowlatency     | 1         | 2%      |
| 5.4.0-107-lowlatency    | 1         | 2%      |
| 5.4.0-100-lowlatency    | 1         | 2%      |
| 5.3.0-19-lowlatency     | 1         | 2%      |
| 5.15.0-37-lowlatency    | 1         | 2%      |
| 5.15.0-30-lowlatency    | 1         | 2%      |
| 5.13.0-30-generic       | 1         | 2%      |
| 5.11.0-41-lowlatency    | 1         | 2%      |
| 5.11.0-36-lowlatency    | 1         | 2%      |
| 5.11.0-25-lowlatency    | 1         | 2%      |
| 5.11.0-22-lowlatency    | 1         | 2%      |
| 5.11.0-16-lowlatency    | 1         | 2%      |
| 4.15.0-91-lowlatency    | 1         | 2%      |
| 4.15.0-50-lowlatency    | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 38.78%  |
| 5.8.0   | 9         | 18.37%  |
| 5.11.0  | 9         | 18.37%  |
| 5.13.0  | 6         | 12.24%  |
| 5.15.0  | 2         | 4.08%   |
| 4.15.0  | 2         | 4.08%   |
| 5.7.6   | 1         | 2.04%   |
| 5.3.0   | 1         | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 38.78%  |
| 5.8     | 9         | 18.37%  |
| 5.11    | 9         | 18.37%  |
| 5.13    | 6         | 12.24%  |
| 5.15    | 2         | 4.08%   |
| 4.15    | 2         | 4.08%   |
| 5.7     | 1         | 2.04%   |
| 5.3     | 1         | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 34        | 69.39%  |
| KDE5  | 9         | 18.37%  |
| GNOME | 5         | 10.2%   |
| LXQt  | 1         | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 93.88%  |
| Wayland | 3         | 6.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 21        | 42.86%  |
| LightDM | 16        | 32.65%  |
| SDDM    | 6         | 12.24%  |
| GDM     | 5         | 10.2%   |
| LXDM    | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 21        | 42.86%  |
| fr_FR   | 9         | 18.37%  |
| C       | 4         | 8.16%   |
| pt_BR   | 2         | 4.08%   |
| en_CA   | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| ru_RU   | 1         | 2.04%   |
| it_IT   | 1         | 2.04%   |
| hu_HU   | 1         | 2.04%   |
| es_NI   | 1         | 2.04%   |
| es_ES   | 1         | 2.04%   |
| es_CR   | 1         | 2.04%   |
| en_NG   | 1         | 2.04%   |
| en_IE   | 1         | 2.04%   |
| de_DE   | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 29        | 59.18%  |
| BIOS | 20        | 40.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 91.84%  |
| Overlay | 4         | 8.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 32        | 65.31%  |
| MBR  | 17        | 34.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 89.8%   |
| Yes       | 5         | 10.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 51.02%  |
| Yes       | 24        | 48.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 12        | 24.49%  |
| Dell                   | 10        | 20.41%  |
| Hewlett-Packard        | 9         | 18.37%  |
| ASUSTek Computer       | 5         | 10.2%   |
| Toshiba                | 2         | 4.08%   |
| Acer                   | 2         | 4.08%   |
| Sony                   | 1         | 2.04%   |
| Samsung Electronics    | 1         | 2.04%   |
| Razer                  | 1         | 2.04%   |
| Intel Client Systems   | 1         | 2.04%   |
| HUAWEI                 | 1         | 2.04%   |
| Google                 | 1         | 2.04%   |
| Getac                  | 1         | 2.04%   |
| Clevo                  | 1         | 2.04%   |
| Avell High Performance | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                               | 2         | 4.08%   |
| HP Pavilion dv6                                  | 2         | 4.08%   |
| Toshiba Satellite L755D                          | 1         | 2.04%   |
| Toshiba Satellite C855                           | 1         | 2.04%   |
| Sony VGN-NS31M_W                                 | 1         | 2.04%   |
| Samsung 305V4A/305V5A                            | 1         | 2.04%   |
| Razer Blade Stealth 13 Late 2019                 | 1         | 2.04%   |
| Lenovo ThinkPad X230 2325AJG                     | 1         | 2.04%   |
| Lenovo ThinkPad X230 23245S1                     | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW         | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US         | 1         | 2.04%   |
| Lenovo ThinkPad W530 2447IG0                     | 1         | 2.04%   |
| Lenovo ThinkPad T520 4243K86                     | 1         | 2.04%   |
| Lenovo Legion 5 15ARH05H 82B1                    | 1         | 2.04%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4             | 1         | 2.04%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY             | 1         | 2.04%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                    | 1         | 2.04%   |
| Intel Client Systems LAPBC510                    | 1         | 2.04%   |
| HUAWEI HLYL-WXX9                                 | 1         | 2.04%   |
| HP Stream Laptop 14-cb0XX                        | 1         | 2.04%   |
| HP Sona                                          | 1         | 2.04%   |
| HP OMEN by Laptop 15-ce0xx                       | 1         | 2.04%   |
| HP Notebook                                      | 1         | 2.04%   |
| HP Laptop 15s-fq1xxx                             | 1         | 2.04%   |
| HP EliteBook 840 G3                              | 1         | 2.04%   |
| HP Compaq 8510p                                  | 1         | 2.04%   |
| Google Nami                                      | 1         | 2.04%   |
| Getac S400G3                                     | 1         | 2.04%   |
| Dell XPS 15 9570                                 | 1         | 2.04%   |
| Dell Precision M4500                             | 1         | 2.04%   |
| Dell Latitude E7250                              | 1         | 2.04%   |
| Dell Latitude E6530                              | 1         | 2.04%   |
| Dell Latitude E4300                              | 1         | 2.04%   |
| Dell Inspiron N5110                              | 1         | 2.04%   |
| Dell Inspiron 7348                               | 1         | 2.04%   |
| Dell Inspiron 5566                               | 1         | 2.04%   |
| Dell Inspiron 3543                               | 1         | 2.04%   |
| Dell Inspiron 1520                               | 1         | 2.04%   |
| Clevo W35_37ET                                   | 1         | 2.04%   |
| Avell High Performance Avell G1555 MUV / A62 MUV | 1         | 2.04%   |
| ASUS X541NA                                      | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X580GD_M580GD           | 1         | 2.04%   |
| ASUS UX305FA                                     | 1         | 2.04%   |
| ASUS U56E                                        | 1         | 2.04%   |
| ASUS ROG Zephyrus G15 GA502IU_GA502IU            | 1         | 2.04%   |
| Acer ASPIRE1420P_MSFT                            | 1         | 2.04%   |
| Acer Aspire A114-32                              | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 6         | 12.24%  |
| Dell Inspiron                 | 5         | 10.2%   |
| Lenovo IdeaPad                | 3         | 6.12%   |
| Dell Latitude                 | 3         | 6.12%   |
| Toshiba Satellite             | 2         | 4.08%   |
| Lenovo G50-45                 | 2         | 4.08%   |
| HP Pavilion                   | 2         | 4.08%   |
| Sony VGN-NS31M                | 1         | 2.04%   |
| Samsung 305V4A                | 1         | 2.04%   |
| Razer Blade                   | 1         | 2.04%   |
| Lenovo Legion                 | 1         | 2.04%   |
| Intel Client Systems LAPBC510 | 1         | 2.04%   |
| HUAWEI HLYL-WXX9              | 1         | 2.04%   |
| HP Stream                     | 1         | 2.04%   |
| HP Sona                       | 1         | 2.04%   |
| HP OMEN                       | 1         | 2.04%   |
| HP Notebook                   | 1         | 2.04%   |
| HP Laptop                     | 1         | 2.04%   |
| HP EliteBook                  | 1         | 2.04%   |
| HP Compaq                     | 1         | 2.04%   |
| Google Nami                   | 1         | 2.04%   |
| Getac S400G3                  | 1         | 2.04%   |
| Dell XPS                      | 1         | 2.04%   |
| Dell Precision                | 1         | 2.04%   |
| Clevo W35                     | 1         | 2.04%   |
| Avell High Performance Avell  | 1         | 2.04%   |
| ASUS X541NA                   | 1         | 2.04%   |
| ASUS VivoBook                 | 1         | 2.04%   |
| ASUS UX305FA                  | 1         | 2.04%   |
| ASUS U56E                     | 1         | 2.04%   |
| ASUS ROG                      | 1         | 2.04%   |
| Acer ASPIRE1420P              | 1         | 2.04%   |
| Acer Aspire                   | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 14.29%  |
| 2014 | 6         | 12.24%  |
| 2012 | 6         | 12.24%  |
| 2011 | 5         | 10.2%   |
| 2019 | 4         | 8.16%   |
| 2018 | 4         | 8.16%   |
| 2017 | 3         | 6.12%   |
| 2008 | 3         | 6.12%   |
| 2021 | 2         | 4.08%   |
| 2016 | 2         | 4.08%   |
| 2015 | 2         | 4.08%   |
| 2010 | 2         | 4.08%   |
| 2007 | 2         | 4.08%   |
| 2009 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 89.8%   |
| Enabled  | 5         | 10.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 95.92%  |
| Yes  | 2         | 4.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 48.98%  |
| 3.01-4.0   | 7         | 14.29%  |
| 16.01-24.0 | 7         | 14.29%  |
| 8.01-16.0  | 5         | 10.2%   |
| 32.01-64.0 | 2         | 4.08%   |
| 2.01-3.0   | 2         | 4.08%   |
| 24.01-32.0 | 1         | 2.04%   |
| 1.01-2.0   | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 22        | 44%     |
| 2.01-3.0  | 10        | 20%     |
| 3.01-4.0  | 8         | 16%     |
| 4.01-8.0  | 7         | 14%     |
| 8.01-16.0 | 2         | 4%      |
| 0.51-1.0  | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 73.47%  |
| 2      | 11        | 22.45%  |
| 0      | 2         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 63.27%  |
| Yes       | 18        | 36.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 97.96%  |
| No        | 1         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 73.47%  |
| No        | 13        | 26.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| USA        | 10        | 20.41%  |
| France     | 9         | 18.37%  |
| Germany    | 4         | 8.16%   |
| Russia     | 3         | 6.12%   |
| Canada     | 3         | 6.12%   |
| UK         | 2         | 4.08%   |
| Italy      | 2         | 4.08%   |
| Costa Rica | 2         | 4.08%   |
| Brazil     | 2         | 4.08%   |
| Turkey     | 1         | 2.04%   |
| Taiwan     | 1         | 2.04%   |
| Spain      | 1         | 2.04%   |
| Poland     | 1         | 2.04%   |
| Norway     | 1         | 2.04%   |
| Nigeria    | 1         | 2.04%   |
| Nicaragua  | 1         | 2.04%   |
| Mexico     | 1         | 2.04%   |
| Hungary    | 1         | 2.04%   |
| Finland    | 1         | 2.04%   |
| Bulgaria   | 1         | 2.04%   |
| Austria    | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| B??ziers               | 2         | 4.08%   |
| Yekaterinburg          | 1         | 2.04%   |
| Wroclaw                | 1         | 2.04%   |
| Woonsocket             | 1         | 2.04%   |
| Woodland Park          | 1         | 2.04%   |
| Vienna                 | 1         | 2.04%   |
| Velleron               | 1         | 2.04%   |
| Turin                  | 1         | 2.04%   |
| Taipei                 | 1         | 2.04%   |
| Sunderland             | 1         | 2.04%   |
| Stuttgart              | 1         | 2.04%   |
| Stabekk                | 1         | 2.04%   |
| Sofia                  | 1         | 2.04%   |
| Seropedica             | 1         | 2.04%   |
| San Juan               | 1         | 2.04%   |
| Samara                 | 1         | 2.04%   |
| Rio de Janeiro         | 1         | 2.04%   |
| Ragusa                 | 1         | 2.04%   |
| Portland               | 1         | 2.04%   |
| Port Harcourt          | 1         | 2.04%   |
| Phoenix                | 1         | 2.04%   |
| Moscow                 | 1         | 2.04%   |
| Montreal               | 1         | 2.04%   |
| Mississauga            | 1         | 2.04%   |
| Mexico City            | 1         | 2.04%   |
| Managua                | 1         | 2.04%   |
| Madrid                 | 1         | 2.04%   |
| Lindsay                | 1         | 2.04%   |
| Lille                  | 1         | 2.04%   |
| Kirkland               | 1         | 2.04%   |
| Istanbul               | 1         | 2.04%   |
| Illkirch-Graffenstaden | 1         | 2.04%   |
| Helsinki               | 1         | 2.04%   |
| Hamburg                | 1         | 2.04%   |
| Grasse                 | 1         | 2.04%   |
| Giroussens             | 1         | 2.04%   |
| Essen                  | 1         | 2.04%   |
| Esparza                | 1         | 2.04%   |
| Denver                 | 1         | 2.04%   |
| Concord                | 1         | 2.04%   |
| Chalette-sur-Loing     | 1         | 2.04%   |
| Cergy                  | 1         | 2.04%   |
| Budapest               | 1         | 2.04%   |
| Bryan                  | 1         | 2.04%   |
| Branson                | 1         | 2.04%   |
| Aylesbury              | 1         | 2.04%   |
| Auburn                 | 1         | 2.04%   |
| Aidlingen              | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 21.43%  |
| WDC                 | 7         | 7      | 12.5%   |
| SanDisk             | 6         | 6      | 10.71%  |
| Toshiba             | 5         | 5      | 8.93%   |
| Unknown             | 4         | 4      | 7.14%   |
| Seagate             | 3         | 3      | 5.36%   |
| Kingston            | 3         | 3      | 5.36%   |
| SK hynix            | 2         | 3      | 3.57%   |
| Intel               | 2         | 2      | 3.57%   |
| Hitachi             | 2         | 2      | 3.57%   |
| Union Memory        | 1         | 1      | 1.79%   |
| UMIS                | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| KIOXIA              | 1         | 1      | 1.79%   |
| KingSpec            | 1         | 1      | 1.79%   |
| JMicron Technology  | 1         | 1      | 1.79%   |
| HGST                | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |
| Crucial             | 1         | 1      | 1.79%   |
| BHT                 | 1         | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                    | 2         | 3.57%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 3.57%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 3.57%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.79%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.79%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1.79%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 1.79%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 1.79%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 1.79%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 1         | 1.79%   |
| Unknown MMC Card  4GB                     | 1         | 1.79%   |
| Unknown MMC Card  16GB                    | 1         | 1.79%   |
| Unknown DA4128  128GB                     | 1         | 1.79%   |
| Unknown 032G34  32GB                      | 1         | 1.79%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 1.79%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 1.79%   |
| Toshiba TR150 240GB SSD                   | 1         | 1.79%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.79%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.79%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.79%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 1.79%   |
| Seagate ST9320320AS 320GB                 | 1         | 1.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.79%   |
| SanDisk SSD PLUS 240GB                    | 1         | 1.79%   |
| SanDisk SD9SN8W128G1002 128GB SSD         | 1         | 1.79%   |
| SanDisk SD7SN3Q128G1002 128GB SSD         | 1         | 1.79%   |
| SanDisk Extreme SSD 1TB                   | 1         | 1.79%   |
| SanDisk DF4064  64GB                      | 1         | 1.79%   |
| SanDisk DF4032  32GB                      | 1         | 1.79%   |
| Samsung SSD PM851 mSATA 256GB             | 1         | 1.79%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.79%   |
| Samsung SSD 960 PRO 512GB                 | 1         | 1.79%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 1.79%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.79%   |
| Samsung PM981 NVMe 1024GB                 | 1         | 1.79%   |
| Samsung MZVLB512HBJQ-00000 512GB          | 1         | 1.79%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD      | 1         | 1.79%   |
| Samsung HN-M500MBB 500GB                  | 1         | 1.79%   |
| Samsung HM320JI 320GB                     | 1         | 1.79%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD  | 1         | 1.79%   |
| KIOXIA KBG40ZNV1T02 1TB                   | 1         | 1.79%   |
| Kingston SA2000M81000G 1TB                | 1         | 1.79%   |
| KingSpec P3-256 256GB SSD                 | 1         | 1.79%   |
| JMicron Generic 2TB                       | 1         | 1.79%   |
| Intel SSDSCKKF180H6H 180GB                | 1         | 1.79%   |
| Intel HBRPEKNX0202A 512GB                 | 1         | 1.79%   |
| Hitachi HTS727550A9E364 500GB             | 1         | 1.79%   |
| Hitachi HTS723232A7A364 320GB             | 1         | 1.79%   |
| HGST HTS725050A7E630 500GB                | 1         | 1.79%   |
| Fujitsu MJA2080BH G2 80GB                 | 1         | 1.79%   |
| Crucial CT256MX100SSD1 256GB              | 1         | 1.79%   |
| BHT WR202HH032G E70215F5 32GB SSD         | 1         | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 4         | 4      | 21.05%  |
| Seagate             | 3         | 3      | 15.79%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| JMicron Technology  | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 33.33%  |
| SanDisk             | 4         | 4      | 22.22%  |
| Kingston            | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| BHT                 | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 19     | 35.29%  |
| SSD  | 16        | 18     | 31.37%  |
| NVMe | 12        | 14     | 23.53%  |
| MMC  | 5         | 6      | 9.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 35     | 62.75%  |
| NVMe | 12        | 14     | 23.53%  |
| MMC  | 5         | 6      | 9.8%    |
| SAS  | 2         | 2      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 29     | 77.78%  |
| 0.51-1.0   | 7         | 7      | 19.44%  |
| 1.01-2.0   | 1         | 1      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 34.69%  |
| 251-500    | 10        | 20.41%  |
| 51-100     | 7         | 14.29%  |
| 21-50      | 6         | 12.24%  |
| 501-1000   | 5         | 10.2%   |
| 1-20       | 3         | 6.12%   |
| 1001-2000  | 1         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 48%     |
| 21-50     | 8         | 16%     |
| 101-250   | 8         | 16%     |
| 51-100    | 5         | 10%     |
| 251-500   | 2         | 4%      |
| 501-1000  | 2         | 4%      |
| 1001-2000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 6.67%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 6.67%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 6.67%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 6.67%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 6.67%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.67%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 6.67%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 26.67%  |
| Seagate             | 3         | 3      | 20%     |
| Samsung Electronics | 3         | 3      | 20%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 3         | 3      | 27.27%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Works    | 30        | 34     | 57.69%  |
| Malfunc  | 15        | 15     | 28.85%  |
| Detected | 7         | 8      | 13.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 34        | 61.82%  |
| AMD                         | 9         | 16.36%  |
| Samsung Electronics         | 4         | 7.27%   |
| Union Memory (Shenzhen)     | 2         | 3.64%   |
| SK hynix                    | 2         | 3.64%   |
| SanDisk                     | 2         | 3.64%   |
| KIOXIA                      | 1         | 1.82%   |
| Kingston Technology Company | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 13.56%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 8.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 6.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 6.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.08%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 3.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.39%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.69%   |
| SK hynix BC511                                                                 | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.69%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.69%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.69%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.69%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                    | 1         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.69%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.69%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 65.45%  |
| NVMe | 12        | 21.82%  |
| RAID | 4         | 7.27%   |
| IDE  | 3         | 5.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 79.59%  |
| AMD    | 10        | 20.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 6.12%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 3         | 6.12%   |
| Intel Processor 5Y10 CPU @ 0.80GHz          | 1         | 2.04%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 2.04%   |
| Intel Genuine CPU U2300 @ 1.20GHz           | 1         | 2.04%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 2.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 2.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 2.04%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 2.04%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 2.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 2.04%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 2.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 2.04%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 2.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 2.04%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 2.04%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 2.04%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 2.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 2.04%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 2.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 2.04%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 2.04%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 2.04%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 2.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 2.04%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 2.04%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 2.04%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz        | 1         | 2.04%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 2.04%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 2.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 2.04%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 2.04%   |
| AMD Ryzen 7 4800HS with Radeon Graphics     | 1         | 2.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 2.04%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics | 1         | 2.04%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics | 1         | 2.04%   |
| AMD E-350 Processor                         | 1         | 2.04%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics | 1         | 2.04%   |
| AMD A4-3310MX APU with Radeon HD Graphics   | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 13        | 26.53%  |
| Intel Core i7      | 12        | 24.49%  |
| Intel Celeron      | 4         | 8.16%   |
| Intel Core 2 Duo   | 3         | 6.12%   |
| AMD Ryzen 5        | 3         | 6.12%   |
| Other              | 2         | 4.08%   |
| Intel Core i3      | 2         | 4.08%   |
| AMD Ryzen 7        | 2         | 4.08%   |
| Intel Pentium Dual | 1         | 2.04%   |
| Intel Genuine      | 1         | 2.04%   |
| Intel Core i9      | 1         | 2.04%   |
| AMD E2             | 1         | 2.04%   |
| AMD E1             | 1         | 2.04%   |
| AMD E              | 1         | 2.04%   |
| AMD A6             | 1         | 2.04%   |
| AMD A4             | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 57.14%  |
| 4      | 14        | 28.57%  |
| 6      | 5         | 10.2%   |
| 8      | 2         | 4.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 65.31%  |
| 1      | 17        | 34.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 6         | 12.24%  |
| 0x306a9    | 4         | 8.16%   |
| 0x08600104 | 4         | 8.16%   |
| Unknown    | 4         | 8.16%   |
| 0x806ea    | 3         | 6.12%   |
| 0x306d4    | 3         | 6.12%   |
| 0x906ea    | 2         | 4.08%   |
| 0x706e5    | 2         | 4.08%   |
| 0x6fd      | 2         | 4.08%   |
| 0x406e3    | 2         | 4.08%   |
| 0x07030105 | 2         | 4.08%   |
| 0xa0652    | 1         | 2.04%   |
| 0x906e9    | 1         | 2.04%   |
| 0x806c1    | 1         | 2.04%   |
| 0x706a1    | 1         | 2.04%   |
| 0x6fb      | 1         | 2.04%   |
| 0x506c9    | 1         | 2.04%   |
| 0x406c4    | 1         | 2.04%   |
| 0x40651    | 1         | 2.04%   |
| 0x306c3    | 1         | 2.04%   |
| 0x106e5    | 1         | 2.04%   |
| 0x1067a    | 1         | 2.04%   |
| 0x08600103 | 1         | 2.04%   |
| 0x07030104 | 1         | 2.04%   |
| 0x05000029 | 1         | 2.04%   |
| 0x03000027 | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 14.29%  |
| SandyBridge   | 6         | 12.24%  |
| Zen 2         | 5         | 10.2%   |
| IvyBridge     | 4         | 8.16%   |
| Broadwell     | 4         | 8.16%   |
| Puma          | 3         | 6.12%   |
| Core          | 3         | 6.12%   |
| Skylake       | 2         | 4.08%   |
| Penryn        | 2         | 4.08%   |
| IceLake       | 2         | 4.08%   |
| Haswell       | 2         | 4.08%   |
| Westmere      | 1         | 2.04%   |
| TigerLake     | 1         | 2.04%   |
| Silvermont    | 1         | 2.04%   |
| Nehalem       | 1         | 2.04%   |
| K10 Llano     | 1         | 2.04%   |
| Goldmont plus | 1         | 2.04%   |
| Goldmont      | 1         | 2.04%   |
| CometLake     | 1         | 2.04%   |
| Bobcat        | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 57.38%  |
| Nvidia | 13        | 21.31%  |
| AMD    | 13        | 21.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 9.52%   |
| AMD Renoir                                                                               | 5         | 7.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.35%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.76%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 4.76%   |
| Nvidia TU117M                                                                            | 2         | 3.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 3.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.59%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.59%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 1.59%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 1.59%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.59%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.59%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.59%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.59%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.59%   |
| Intel HD Graphics 500                                                                    | 1         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.59%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.59%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.59%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.59%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 1         | 1.59%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 1.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.59%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.59%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 53.06%  |
| Intel + Nvidia | 8         | 16.33%  |
| 1 x AMD        | 8         | 16.33%  |
| AMD + Nvidia   | 3         | 6.12%   |
| 1 x Nvidia     | 2         | 4.08%   |
| 2 x AMD        | 1         | 2.04%   |
| Intel + AMD    | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 93.88%  |
| Proprietary | 3         | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 61.22%  |
| 0.51-1.0   | 7         | 14.29%  |
| 0.01-0.5   | 7         | 14.29%  |
| 5.01-6.0   | 2         | 4.08%   |
| 3.01-4.0   | 2         | 4.08%   |
| 1.01-2.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 23.21%  |
| LG Display              | 9         | 16.07%  |
| Samsung Electronics     | 8         | 14.29%  |
| Chimei Innolux          | 6         | 10.71%  |
| BOE                     | 6         | 10.71%  |
| Sharp                   | 2         | 3.57%   |
| Lenovo                  | 2         | 3.57%   |
| LG Philips              | 1         | 1.79%   |
| Iiyama                  | 1         | 1.79%   |
| Hannspree               | 1         | 1.79%   |
| Dell                    | 1         | 1.79%   |
| CPT                     | 1         | 1.79%   |
| Chi Mei Optoelectronics | 1         | 1.79%   |
| BenQ                    | 1         | 1.79%   |
| Arnos Instruments       | 1         | 1.79%   |
| Ancor Communications    | 1         | 1.79%   |
| Acer                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 3.57%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 3.57%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 2         | 3.57%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 1.79%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.79%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch  | 1         | 1.79%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.79%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 1         | 1.79%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 1         | 1.79%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                     | 1         | 1.79%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 1         | 1.79%   |
| CPT LCD Monitor CPT141F 1280x800 331x207mm 15.4-inch                     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.79%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE05F4 1366x768 277x156mm 12.5-inch                     | 1         | 1.79%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO42ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x174mm 14.0-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch            | 1         | 1.79%   |
| Arnos Instruments L-W22 AIC1003 1920x1080 477x268mm 21.5-inch            | 1         | 1.79%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch         | 1         | 1.79%   |
| Acer AL1715 ACR06B0 1280x1024 338x270mm 17.0-inch                        | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 42.31%  |
| 1366x768 (WXGA)    | 18        | 34.62%  |
| 1600x900 (HD+)     | 4         | 7.69%   |
| 3840x2160 (4K)     | 3         | 5.77%   |
| 1280x800 (WXGA)    | 2         | 3.85%   |
| 2560x1440 (QHD)    | 1         | 1.92%   |
| 1680x1050 (WSXGA+) | 1         | 1.92%   |
| 1440x900 (WXGA+)   | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 29        | 51.79%  |
| 13     | 8         | 14.29%  |
| 14     | 4         | 7.14%   |
| 24     | 3         | 5.36%   |
| 12     | 3         | 5.36%   |
| 27     | 2         | 3.57%   |
| 21     | 2         | 3.57%   |
| 84     | 1         | 1.79%   |
| 20     | 1         | 1.79%   |
| 19     | 1         | 1.79%   |
| 18     | 1         | 1.79%   |
| 16     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 69.09%  |
| 201-300     | 6         | 10.91%  |
| 401-500     | 5         | 9.09%   |
| 501-600     | 4         | 7.27%   |
| 351-400     | 1         | 1.82%   |
| 1501-2000   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 89.8%   |
| 16/10 | 5         | 10.2%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 53.57%  |
| 81-90          | 9         | 16.07%  |
| 71-80          | 3         | 5.36%   |
| 61-70          | 3         | 5.36%   |
| 201-250        | 3         | 5.36%   |
| 151-200        | 3         | 5.36%   |
| 301-350        | 2         | 3.57%   |
| More than 1000 | 1         | 1.79%   |
| 251-300        | 1         | 1.79%   |
| 141-150        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 38.89%  |
| 101-120       | 19        | 35.19%  |
| 51-100        | 9         | 16.67%  |
| 161-240       | 4         | 7.41%   |
| More than 240 | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 82%     |
| 2     | 8         | 16%     |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 39.74%  |
| Realtek Semiconductor             | 26        | 33.33%  |
| Qualcomm Atheros                  | 10        | 12.82%  |
| Broadcom                          | 3         | 3.85%   |
| Ralink                            | 2         | 2.56%   |
| MediaTek                          | 1         | 1.28%   |
| Marvell Technology Group          | 1         | 1.28%   |
| Huawei Technologies               | 1         | 1.28%   |
| Ericsson Business Mobile Networks | 1         | 1.28%   |
| Broadcom Limited                  | 1         | 1.28%   |
| ASIX Electronics                  | 1         | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 14        | 15.05%  |
| Intel Wireless 7265                                                | 6         | 6.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 5.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 5         | 5.38%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                     | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 2.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 2         | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 2         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 2         | 2.15%   |
| Intel Wireless 7260                                                | 2         | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 2         | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                      | 2         | 2.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1         | 1.08%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]   | 1         | 1.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                              | 1         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 1.08%   |
| MediaTek TECNO SPARK 3                                             | 1         | 1.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                         | 1         | 1.08%   |
| Intel Wireless 8260                                                | 1         | 1.08%   |
| Intel WiFi Link 5100                                               | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                | 1         | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection      | 1         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 1         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 1.08%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                               | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                              | 1         | 1.08%   |
| Intel Ethernet Connection (2) I218-LM                              | 1         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 1         | 1.08%   |
| Intel Centrino Wireless-N 6150                                     | 1         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                      | 1         | 1.08%   |
| Intel Centrino Wireless-N + WiMAX 6150                             | 1         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                           | 1         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                           | 1         | 1.08%   |
| Intel 82566MM Gigabit Network Connection                           | 1         | 1.08%   |
| Huawei Mobile                                                      | 1         | 1.08%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 1         | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                          | 1         | 1.08%   |
| Broadcom BCM4401-B0 100Base-TX                                     | 1         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                      | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 60.42%  |
| Realtek Semiconductor | 7         | 14.58%  |
| Qualcomm Atheros      | 7         | 14.58%  |
| Ralink                | 2         | 4.17%   |
| Broadcom              | 2         | 4.17%   |
| Broadcom Limited      | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 6         | 12.24%  |
| Intel Wi-Fi 6 AX200                                              | 3         | 6.12%   |
| Intel Centrino Ultimate-N 6300                                   | 3         | 6.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 3         | 6.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 2         | 4.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 4.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2         | 4.08%   |
| Intel Wireless 7260                                              | 2         | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 2         | 4.08%   |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 4.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 2.04%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                       | 1         | 2.04%   |
| Intel Wireless 8260                                              | 1         | 2.04%   |
| Intel WiFi Link 5100                                             | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                              | 1         | 2.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                   | 1         | 2.04%   |
| Intel Centrino Wireless-N 6150                                   | 1         | 2.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 1         | 2.04%   |
| Intel Centrino Wireless-N + WiMAX 6150                           | 1         | 2.04%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 50%     |
| Intel                    | 13        | 30.95%  |
| Qualcomm Atheros         | 4         | 9.52%   |
| MediaTek                 | 1         | 2.38%   |
| Marvell Technology Group | 1         | 2.38%   |
| Broadcom                 | 1         | 2.38%   |
| ASIX Electronics         | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 11.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.38%   |
| MediaTek TECNO SPARK 3                                            | 1         | 2.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.38%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.38%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.38%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 53.33%  |
| Ethernet | 40        | 44.44%  |
| Modem    | 2         | 2.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 82.35%  |
| Ethernet | 9         | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 75.51%  |
| 1     | 12        | 24.49%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 75.51%  |
| Yes  | 12        | 24.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 52.78%  |
| Qualcomm Atheros Communications | 4         | 11.11%  |
| Broadcom                        | 4         | 11.11%  |
| Realtek Semiconductor           | 3         | 8.33%   |
| Ralink Technology               | 2         | 5.56%   |
| Realtek                         | 1         | 2.78%   |
| Lite-On Technology              | 1         | 2.78%   |
| Hewlett-Packard                 | 1         | 2.78%   |
| Foxconn International           | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 10        | 27.78%  |
| Intel Bluetooth Device                            | 3         | 8.33%   |
| Intel AX200 Bluetooth                             | 3         | 8.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 3         | 8.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 5.56%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.78%   |
| Realtek Bluetooth Radio                           | 1         | 2.78%   |
| Realtek Bluetooth Radio                           | 1         | 2.78%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 2.78%   |
| Ralink CSR BS8510                                 | 1         | 2.78%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 2.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 2.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 2.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 2.78%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.78%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 39        | 58.21%  |
| AMD                        | 11        | 16.42%  |
| Nvidia                     | 10        | 14.93%  |
| Yealink Network Technology | 1         | 1.49%   |
| QinHeng Electronics        | 1         | 1.49%   |
| Mackie Designs             | 1         | 1.49%   |
| Logitech                   | 1         | 1.49%   |
| Jieli Technology           | 1         | 1.49%   |
| C-Media Electronics        | 1         | 1.49%   |
| Behringer.......           | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 7.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 6.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 4.94%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.94%   |
| AMD FCH Azalia Controller                                                                         | 4         | 4.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.47%   |
| Yealink Network Technology VoIP Phone                                                             | 1         | 1.23%   |
| QinHeng Electronics CH345 MIDI adapter                                                            | 1         | 1.23%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.23%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.23%   |
| Mackie Designs BIG KNOB STUDIO+                                                                   | 1         | 1.23%   |
| Logitech 960 Headset                                                                              | 1         | 1.23%   |
| Jieli Technology UACDemoV1.0                                                                      | 1         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.23%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.23%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 1.23%   |
| Behringer....... BIGFOOT                                                                          | 1         | 1.23%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.23%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.23%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 32.14%  |
| SK hynix            | 16        | 28.57%  |
| Kingston            | 6         | 10.71%  |
| Micron Technology   | 5         | 8.93%   |
| Unknown             | 3         | 5.36%   |
| Ramaxel Technology  | 2         | 3.57%   |
| Nanya Technology    | 2         | 3.57%   |
| Crucial             | 2         | 3.57%   |
| Transcend           | 1         | 1.79%   |
| Corsair             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s     | 3         | 4.84%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s          | 3         | 4.84%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s         | 2         | 3.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 3.23%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s              | 1         | 1.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                 | 1         | 1.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.61%   |
| Transcend RAM TS1GSK64W6H 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s               | 1         | 1.61%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s          | 1         | 1.61%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s  | 1         | 1.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s        | 1         | 1.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s               | 1         | 1.61%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 1.61%   |
| Samsung RAM Module 8192MB SODIMM DDR3 1600MT/s                | 1         | 1.61%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s        | 1         | 1.61%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CWE 8192MB SODIMM DDR4 3200MT/s      | 1         | 1.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.61%   |
| Samsung RAM M4 70T2864QZ3-CE6 1GB SODIMM DDR 1639MT/s         | 1         | 1.61%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.61%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8192MB SODIMM DDR4 2667MT/s  | 1         | 1.61%   |
| Nanya RAM NT2GT64U8HD0BN-3C 2GB SODIMM DDR 667MT/s            | 1         | 1.61%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s          | 1         | 1.61%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.61%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.61%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Micron RAM 16KTF51264HZ-1G6K1 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.61%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Kingston RAM HP16D3LS1KBGH/4G 4GB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s      | 1         | 1.61%   |
| Kingston RAM 99U5428-014.A00G 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.61%   |
| Kingston RAM 9905700-046.A00G 16384MB SODIMM DDR4 3200MT/s    | 1         | 1.61%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 1         | 1.61%   |
| Corsair RAM CMSO4GX4M1A2133C15 4GB SODIMM DDR4 2133MT/s       | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 26        | 50.98%  |
| DDR4   | 15        | 29.41%  |
| DDR2   | 4         | 7.84%   |
| SDRAM  | 2         | 3.92%   |
| LPDDR4 | 2         | 3.92%   |
| LPDDR3 | 2         | 3.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 85.71%  |
| Row Of Chips | 5         | 10.2%   |
| Chip         | 1         | 2.04%   |
| Unknown      | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 24        | 42.11%  |
| 8192  | 17        | 29.82%  |
| 2048  | 10        | 17.54%  |
| 16384 | 3         | 5.26%   |
| 1024  | 3         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 20        | 37.74%  |
| 1334    | 7         | 13.21%  |
| 3200    | 5         | 9.43%   |
| 2667    | 5         | 9.43%   |
| 2400    | 3         | 5.66%   |
| 2133    | 3         | 5.66%   |
| 667     | 3         | 5.66%   |
| 4267    | 2         | 3.77%   |
| 1333    | 2         | 3.77%   |
| 4199    | 1         | 1.89%   |
| 1639    | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1022 | 1         | 100%    |

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


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4200F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 31.71%  |
| IMC Networks                           | 5         | 12.2%   |
| Suyin                                  | 3         | 7.32%   |
| Sunplus Innovation Technology          | 3         | 7.32%   |
| Realtek Semiconductor                  | 3         | 7.32%   |
| Microdia                               | 3         | 7.32%   |
| Quanta                                 | 2         | 4.88%   |
| Acer                                   | 2         | 4.88%   |
| ViewQuest Technologies                 | 1         | 2.44%   |
| Syntek                                 | 1         | 2.44%   |
| Silicon Motion                         | 1         | 2.44%   |
| Ricoh                                  | 1         | 2.44%   |
| Philips (or NXP)                       | 1         | 2.44%   |
| Importek                               | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                   | 3         | 7.14%   |
| Chicony Integrated Camera                        | 3         | 7.14%   |
| Sunplus Integrated_Webcam_HD                     | 2         | 4.76%   |
| Microdia Integrated_Webcam_HD                    | 2         | 4.76%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 4.76%   |
| ViewQuest Ability GABB Webcam                    | 1         | 2.38%   |
| Syntek Integrated Camera                         | 1         | 2.38%   |
| Suyin HP Webcam                                  | 1         | 2.38%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 2.38%   |
| Suyin Asus Integrated Webcam                     | 1         | 2.38%   |
| Sunplus Dell HD Webcam                           | 1         | 2.38%   |
| Silicon Motion WebCam SCB-1100N                  | 1         | 2.38%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 2.38%   |
| Realtek VGA WebCam                               | 1         | 2.38%   |
| Realtek Lenovo EasyCamera                        | 1         | 2.38%   |
| Realtek HP Wide Vision HD Camera                 | 1         | 2.38%   |
| Quanta ov9734_techfront_camera                   | 1         | 2.38%   |
| Quanta HP TrueVision HD Camera                   | 1         | 2.38%   |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]       | 1         | 2.38%   |
| Microdia Integrated Webcam HD                    | 1         | 2.38%   |
| Importek TOSHIBA Web Camera - HD                 | 1         | 2.38%   |
| IMC Networks UVC VGA Webcam                      | 1         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                | 1         | 2.38%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 1         | 2.38%   |
| Chicony Integrated IR Camera                     | 1         | 2.38%   |
| Chicony HP Wide Vision HD Camera                 | 1         | 2.38%   |
| Chicony HP TrueVision HD                         | 1         | 2.38%   |
| Chicony HP HD Camera                             | 1         | 2.38%   |
| Chicony HD Webcam                                | 1         | 2.38%   |
| Chicony HD User Facing                           | 1         | 2.38%   |
| Chicony CNF9055 Toshiba Webcam                   | 1         | 2.38%   |
| Chicony 4-Port Hub                               | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.38%   |
| Acer Lenovo EasyCamera                           | 1         | 2.38%   |
| Acer BisonCam, NB Pro                            | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| LighTuning Technology      | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner             | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device              | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader               | 1         | 12.5%   |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor             | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Upek        | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 29        | 59.18%  |
| 1     | 17        | 34.69%  |
| 2     | 2         | 4.08%   |
| 3     | 1         | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 38.1%   |
| Graphics card         | 6         | 28.57%  |
| Chipcard              | 6         | 28.57%  |
| Multimedia controller | 1         | 4.76%   |

