Linux in Morocco - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 60

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0KJCC5 A00                  | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| ECS           | Nettle2                     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E4                        | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| HP            | 3396                        | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | 1589                        | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| HP            | 8054                        | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| HP            | 1998                        | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| HP            | 1998                        | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| Dell          | 0MWYPT A01                  | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | 1589                        | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| Pegatron      | 2AD5                        | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | 18E7                        | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| American M... | K7S41GX                     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| HP            | 3032h                       | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| HP            | 1589                        | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Foxconn       | 2ABF                        | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| HP            | 18E7                        | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| HP            | 0AACh                       | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| Lenovo        | SHARKBAY NOK                | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 339A                        | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Foxconn       | 2ABF                        | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Dell          | 0KC9NP A01                  | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| MSI           | 2A9C                        | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Foxconn       | 2ACA                        | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| ASUSTek       | Crosshair IV Formula        | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | 158A                        | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| ASUSTek       | Crosshair IV Formula        | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 304Ah                       | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| Dell          | 0MWYPT A01                  | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| HP            | 3398                        | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| HP            | 3397                        | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| HP            | 0A04h                       | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| HP            | 3397                        | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 1494                        | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Dell          | 0D28YY A03                  | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Lenovo        | MAHOBAY NO DPK              | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| Dell          | 0DR845                      | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 7        | 14.58%  |
| OpenMandriva 4.2  | 5        | 10.42%  |
| Ubuntu 18.04      | 4        | 8.33%   |
| OpenMandriva 4.50 | 4        | 8.33%   |
| Fedora 33         | 4        | 8.33%   |
| Debian 11         | 2        | 4.17%   |
| Zorin 15          | 1        | 2.08%   |
| Xubuntu 18.04     | 1        | 2.08%   |
| Ubuntu 20.10      | 1        | 2.08%   |
| Ubuntu 16.04      | 1        | 2.08%   |
| ROSA R8.1         | 1        | 2.08%   |
| Pop!_OS 21.04     | 1        | 2.08%   |
| Pop!_OS 20.10     | 1        | 2.08%   |
| Pear OS 21.04     | 1        | 2.08%   |
| Parrot 5.0        | 1        | 2.08%   |
| OpenMandriva 4.3  | 1        | 2.08%   |
| Manjaro 21.0.7    | 1        | 2.08%   |
| Lubuntu 18.04     | 1        | 2.08%   |
| Linux Mint 20.3   | 1        | 2.08%   |
| Linux Mint 20.2   | 1        | 2.08%   |
| Linux Mint 19.3   | 1        | 2.08%   |
| KDE neon 20.04    | 1        | 2.08%   |
| Kali 2021.4       | 1        | 2.08%   |
| Debian Unstable   | 1        | 2.08%   |
| Debian Testing    | 1        | 2.08%   |
| Debian 10         | 1        | 2.08%   |
| BlackPanther 18.1 | 1        | 2.08%   |
| ArcoLinux Rolling | 1        | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 13       | 28.26%  |
| OpenMandriva | 10       | 21.74%  |
| Fedora       | 4        | 8.7%    |
| Linux Mint   | 3        | 6.52%   |
| Debian       | 3        | 6.52%   |
| Pop!_OS      | 2        | 4.35%   |
| Zorin        | 1        | 2.17%   |
| Xubuntu      | 1        | 2.17%   |
| ROSA         | 1        | 2.17%   |
| Pear OS      | 1        | 2.17%   |
| Parrot       | 1        | 2.17%   |
| Manjaro      | 1        | 2.17%   |
| Lubuntu      | 1        | 2.17%   |
| KDE neon     | 1        | 2.17%   |
| Kali         | 1        | 2.17%   |
| BlackPanther | 1        | 2.17%   |
| ArcoLinux    | 1        | 2.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 5        | 9.62%   |
| 5.12.4-desktop-1omv4050         | 4        | 7.69%   |
| 5.8.18-300.fc33.x86_64          | 1        | 1.92%   |
| 5.8.0-7642-generic              | 1        | 1.92%   |
| 5.8.0-59-generic                | 1        | 1.92%   |
| 5.8.0-38-generic                | 1        | 1.92%   |
| 5.8.0-29-generic                | 1        | 1.92%   |
| 5.6.14-desktop-2bP              | 1        | 1.92%   |
| 5.4.0-90-generic                | 1        | 1.92%   |
| 5.4.0-74-generic                | 1        | 1.92%   |
| 5.4.0-70-generic                | 1        | 1.92%   |
| 5.4.0-60-generic                | 1        | 1.92%   |
| 5.4.0-59-generic                | 1        | 1.92%   |
| 5.4.0-58-generic                | 1        | 1.92%   |
| 5.4.0-48-generic                | 1        | 1.92%   |
| 5.4.0-42-generic                | 1        | 1.92%   |
| 5.4.0-39-generic                | 1        | 1.92%   |
| 5.3.0-46-generic                | 1        | 1.92%   |
| 5.3.0-42-generic                | 1        | 1.92%   |
| 5.16.7-desktop-1omv4003         | 1        | 1.92%   |
| 5.15.0-kali2-amd64              | 1        | 1.92%   |
| 5.15.0-33-generic               | 1        | 1.92%   |
| 5.15.0-2-amd64                  | 1        | 1.92%   |
| 5.14.0-9parrot1-amd64           | 1        | 1.92%   |
| 5.14.0-2-amd64                  | 1        | 1.92%   |
| 5.13.0-7620-generic             | 1        | 1.92%   |
| 5.11.8-200.fc33.x86_64          | 1        | 1.92%   |
| 5.11.0-43-generic               | 1        | 1.92%   |
| 5.11.0-37-generic               | 1        | 1.92%   |
| 5.11.0-25-generic               | 1        | 1.92%   |
| 5.10.88-2-lts                   | 1        | 1.92%   |
| 5.10.7-200.fc33.x86_64          | 1        | 1.92%   |
| 5.10.42-1-MANJARO               | 1        | 1.92%   |
| 5.10.15-200.fc33.x86_64         | 1        | 1.92%   |
| 5.10.11-200.fc33.x86_64         | 1        | 1.92%   |
| 5.10.0-9-amd64                  | 1        | 1.92%   |
| 5.10.0-9-686                    | 1        | 1.92%   |
| 5.10.0-1011-oem                 | 1        | 1.92%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 1        | 1.92%   |
| 4.19.0-17-amd64                 | 1        | 1.92%   |
| 4.18.0-25-generic               | 1        | 1.92%   |
| 4.15.0-42-generic               | 1        | 1.92%   |
| 4.15.0-29-generic               | 1        | 1.92%   |
| 4.15.0-163-generic              | 1        | 1.92%   |
| 4.15.0-162-lowlatency           | 1        | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 7        | 14%     |
| 5.10.14 | 5        | 10%     |
| 5.8.0   | 4        | 8%      |
| 5.12.4  | 4        | 8%      |
| 4.15.0  | 4        | 8%      |
| 5.15.0  | 3        | 6%      |
| 5.11.0  | 3        | 6%      |
| 5.10.0  | 3        | 6%      |
| 5.3.0   | 2        | 4%      |
| 5.14.0  | 2        | 4%      |
| 5.8.18  | 1        | 2%      |
| 5.6.14  | 1        | 2%      |
| 5.16.7  | 1        | 2%      |
| 5.13.0  | 1        | 2%      |
| 5.11.8  | 1        | 2%      |
| 5.10.88 | 1        | 2%      |
| 5.10.7  | 1        | 2%      |
| 5.10.42 | 1        | 2%      |
| 5.10.15 | 1        | 2%      |
| 5.10.11 | 1        | 2%      |
| 4.9.41  | 1        | 2%      |
| 4.19.0  | 1        | 2%      |
| 4.18.0  | 1        | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 12       | 24.49%  |
| 5.4     | 7        | 14.29%  |
| 5.8     | 5        | 10.2%   |
| 5.12    | 4        | 8.16%   |
| 5.11    | 4        | 8.16%   |
| 4.15    | 4        | 8.16%   |
| 5.15    | 3        | 6.12%   |
| 5.3     | 2        | 4.08%   |
| 5.14    | 2        | 4.08%   |
| 5.6     | 1        | 2.04%   |
| 5.16    | 1        | 2.04%   |
| 5.13    | 1        | 2.04%   |
| 4.9     | 1        | 2.04%   |
| 4.19    | 1        | 2.04%   |
| 4.18    | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 44       | 95.65%  |
| i686   | 2        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 19       | 39.58%  |
| KDE5       | 13       | 27.08%  |
| XFCE       | 3        | 6.25%   |
| Unknown    | 3        | 6.25%   |
| MATE       | 2        | 4.17%   |
| LXDE       | 2        | 4.17%   |
| KDE        | 2        | 4.17%   |
| X-Cinnamon | 1        | 2.08%   |
| qtile      | 1        | 2.08%   |
| KDE4       | 1        | 2.08%   |
| Cinnamon   | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 39       | 82.98%  |
| Wayland | 5        | 10.64%  |
| Tty     | 2        | 4.26%   |
| Unknown | 1        | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 37.5%   |
| SDDM    | 13       | 27.08%  |
| LightDM | 9        | 18.75%  |
| GDM     | 4        | 8.33%   |
| GDM3    | 2        | 4.17%   |
| TDM     | 1        | 2.08%   |
| KDM     | 1        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 46.81%  |
| fr_FR   | 15       | 31.91%  |
| Unknown | 5        | 10.64%  |
| en_GB   | 2        | 4.26%   |
| fr_CH   | 1        | 2.13%   |
| C       | 1        | 2.13%   |
| ar_MA   | 1        | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 63.04%  |
| EFI  | 17       | 36.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 29       | 63.04%  |
| Overlay | 11       | 23.91%  |
| Btrfs   | 4        | 8.7%    |
| Unknown | 2        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 50%     |
| GPT     | 14       | 30.43%  |
| MBR     | 9        | 19.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 76.6%   |
| Yes       | 11       | 23.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 56.52%  |
| No        | 20       | 43.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 22       | 47.83%  |
| Dell                | 8        | 17.39%  |
| ASUSTek Computer    | 5        | 10.87%  |
| Lenovo              | 3        | 6.52%   |
| Foxconn             | 3        | 6.52%   |
| Pegatron            | 1        | 2.17%   |
| MSI                 | 1        | 2.17%   |
| Gigabyte Technology | 1        | 2.17%   |
| ECS                 | 1        | 2.17%   |
| American Megatrends | 1        | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP ProDesk 600 G1 TWR                  | 2        | 4.35%   |
| HP EliteDesk 800 G1 SFF                | 2        | 4.35%   |
| HP Compaq Elite 8300 SFF               | 2        | 4.35%   |
| HP Compaq Elite 8300 CMT               | 2        | 4.35%   |
| HP Compaq dc7800 Convertible Minitower | 2        | 4.35%   |
| Dell OptiPlex 790                      | 2        | 4.35%   |
| Pegatron h8-1507ef                     | 1        | 2.17%   |
| MSI PPPPP-CCC#MMMMMMMM                 | 1        | 2.17%   |
| Lenovo ThinkCentre M93p 10AAS0R301     | 1        | 2.17%   |
| Lenovo ThinkCentre M910t 10MNS04E4X    | 1        | 2.17%   |
| Lenovo ThinkCentre M72e 3261A85        | 1        | 2.17%   |
| HP Z620 Workstation                    | 1        | 2.17%   |
| HP Z420 Workstation                    | 1        | 2.17%   |
| HP xw6400 Workstation                  | 1        | 2.17%   |
| HP EliteDesk 800 G2 SFF                | 1        | 2.17%   |
| HP EliteDesk 800 G1 TWR                | 1        | 2.17%   |
| HP dc5000 SFF(PP682US)                 | 1        | 2.17%   |
| HP Compaq Pro 6300 SFF                 | 1        | 2.17%   |
| HP Compaq Elite 8300 USDT              | 1        | 2.17%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.17%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 2.17%   |
| HP Compaq 8200 Elite CMT PC            | 1        | 2.17%   |
| HP Compaq 8100 Elite SFF PC            | 1        | 2.17%   |
| Gigabyte X570 AORUS MASTER             | 1        | 2.17%   |
| Foxconn Pro3500 Series                 | 1        | 2.17%   |
| Foxconn p6-2002es                      | 1        | 2.17%   |
| Foxconn CQ1140FRm                      | 1        | 2.17%   |
| ECS GV460AA-ABA a6217c                 | 1        | 2.17%   |
| Dell Vostro 3667                       | 1        | 2.17%   |
| Dell Precision Tower 7810              | 1        | 2.17%   |
| Dell Precision Tower 3620              | 1        | 2.17%   |
| Dell OptiPlex 9020                     | 1        | 2.17%   |
| Dell OptiPlex 760                      | 1        | 2.17%   |
| Dell OptiPlex 755                      | 1        | 2.17%   |
| ASUS Z170 PRO GAMING                   | 1        | 2.17%   |
| ASUS ROG STRIX B450-F GAMING           | 1        | 2.17%   |
| ASUS ROG CROSSHAIR VIII IMPACT         | 1        | 2.17%   |
| ASUS GV454AA-ABU s3230.uk              | 1        | 2.17%   |
| ASUS Crosshair IV Formula              | 1        | 2.17%   |
| American Megatrends K7S41GX            | 1        | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Compaq                   | 12       | 26.09%  |
| Dell OptiPlex               | 5        | 10.87%  |
| HP EliteDesk                | 4        | 8.7%    |
| Lenovo ThinkCentre          | 3        | 6.52%   |
| HP ProDesk                  | 2        | 4.35%   |
| Dell Precision              | 2        | 4.35%   |
| ASUS ROG                    | 2        | 4.35%   |
| Pegatron h8-1507ef          | 1        | 2.17%   |
| MSI PPPPP-CCC#MMMMMMMM      | 1        | 2.17%   |
| HP Z620                     | 1        | 2.17%   |
| HP Z420                     | 1        | 2.17%   |
| HP xw6400                   | 1        | 2.17%   |
| HP dc5000                   | 1        | 2.17%   |
| Gigabyte X570               | 1        | 2.17%   |
| Foxconn Pro3500             | 1        | 2.17%   |
| Foxconn p6-2002es           | 1        | 2.17%   |
| Foxconn CQ1140FRm           | 1        | 2.17%   |
| ECS GV460AA-ABA             | 1        | 2.17%   |
| Dell Vostro                 | 1        | 2.17%   |
| ASUS Z170                   | 1        | 2.17%   |
| ASUS GV454AA-ABU            | 1        | 2.17%   |
| ASUS Crosshair              | 1        | 2.17%   |
| American Megatrends K7S41GX | 1        | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 9        | 19.57%  |
| 2013 | 8        | 17.39%  |
| 2011 | 6        | 13.04%  |
| 2007 | 6        | 13.04%  |
| 2015 | 3        | 6.52%   |
| 2019 | 2        | 4.35%   |
| 2018 | 2        | 4.35%   |
| 2017 | 2        | 4.35%   |
| 2009 | 2        | 4.35%   |
| 2004 | 2        | 4.35%   |
| 2021 | 1        | 2.17%   |
| 2014 | 1        | 2.17%   |
| 2010 | 1        | 2.17%   |
| 2008 | 1        | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 46       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 45       | 95.74%  |
| Enabled  | 2        | 4.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 12       | 26.09%  |
| 3.01-4.0    | 11       | 23.91%  |
| 16.01-24.0  | 8        | 17.39%  |
| 1.01-2.0    | 4        | 8.7%    |
| 8.01-16.0   | 4        | 8.7%    |
| 64.01-256.0 | 3        | 6.52%   |
| 24.01-32.0  | 2        | 4.35%   |
| 2.01-3.0    | 2        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 23       | 46.94%  |
| 2.01-3.0 | 10       | 20.41%  |
| 0.51-1.0 | 6        | 12.24%  |
| 3.01-4.0 | 5        | 10.2%   |
| 4.01-8.0 | 4        | 8.16%   |
| 0.01-0.5 | 1        | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 57.45%  |
| 2      | 11       | 23.4%   |
| 3      | 7        | 14.89%  |
| 4      | 2        | 4.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 56.52%  |
| No        | 20       | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 56.52%  |
| No        | 20       | 43.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 78.26%  |
| Yes       | 10       | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Morocco | 46       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Casablanca    | 16       | 33.33%  |
| Agadir        | 6        | 12.5%   |
| Marrakesh     | 4        | 8.33%   |
| Fes           | 4        | 8.33%   |
| Tangier       | 2        | 4.17%   |
| Sal??         | 2        | 4.17%   |
| Youssoufia    | 1        | 2.08%   |
| Tiznit        | 1        | 2.08%   |
| T??touan      | 1        | 2.08%   |
| Temara        | 1        | 2.08%   |
| Taza          | 1        | 2.08%   |
| Taounate      | 1        | 2.08%   |
| Skhirate      | 1        | 2.08%   |
| Sidi Lmokhtar | 1        | 2.08%   |
| Safi          | 1        | 2.08%   |
| Ouirgane      | 1        | 2.08%   |
| Mohammedia    | 1        | 2.08%   |
| Meknes        | 1        | 2.08%   |
| Douar Kalaa   | 1        | 2.08%   |
| Berrechid     | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 15       | 22     | 22.39%  |
| WDC                   | 14       | 15     | 20.9%   |
| Samsung Electronics   | 8        | 13     | 11.94%  |
| Hitachi               | 7        | 8      | 10.45%  |
| Toshiba               | 5        | 9      | 7.46%   |
| Intel                 | 3        | 3      | 4.48%   |
| Micron Technology     | 2        | 3      | 2.99%   |
| HGST                  | 2        | 2      | 2.99%   |
| Fujitsu               | 2        | 2      | 2.99%   |
| Crucial               | 2        | 3      | 2.99%   |
| Realtek Semiconductor | 1        | 1      | 1.49%   |
| PNY                   | 1        | 1      | 1.49%   |
| Phison                | 1        | 2      | 1.49%   |
| Magnetic Data         | 1        | 1      | 1.49%   |
| LITEON                | 1        | 1      | 1.49%   |
| HS-SSD-E100           | 1        | 1      | 1.49%   |
| Unknown               | 1        | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 3        | 4.17%   |
| Seagate ST3250312AS 250GB            | 3        | 4.17%   |
| WDC WD800JD-00LSA0 80GB              | 2        | 2.78%   |
| Intel SSDSC2BF180A4H 180GB           | 2        | 2.78%   |
| Hitachi HDS721680PLA380 80GB         | 2        | 2.78%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1        | 1.39%   |
| WDC WD800JD-75MSA3 80GB              | 1        | 1.39%   |
| WDC WD5000BEKT-75KA9T0 500GB         | 1        | 1.39%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 1.39%   |
| WDC WD400BB-60DGA0 40GB              | 1        | 1.39%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1        | 1.39%   |
| WDC WD3200AAJS-65RYA0 320GB          | 1        | 1.39%   |
| WDC WD2500AAKX-603CA0 250GB          | 1        | 1.39%   |
| WDC WD2500AAJS-60Z0A0 250GB          | 1        | 1.39%   |
| WDC WD1600JS-55NCB1 160GB            | 1        | 1.39%   |
| WDC WD1600BEVT-80A23T0 160GB         | 1        | 1.39%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1        | 1.39%   |
| WDC WD1600AAJS-60M0A0 160GB          | 1        | 1.39%   |
| Toshiba MQ02ABF050H 500GB            | 1        | 1.39%   |
| Toshiba MQ01ABD050V -63 500GB        | 1        | 1.39%   |
| Toshiba DT01ACA200 2TB               | 1        | 1.39%   |
| Toshiba DT01ACA100 LENOVO 1TB        | 1        | 1.39%   |
| Toshiba DT01ACA100 1TB               | 1        | 1.39%   |
| Seagate ST9320325AS 320GB            | 1        | 1.39%   |
| Seagate ST500LT012-1DG142 500GB      | 1        | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB      | 1        | 1.39%   |
| Seagate ST500LM000-1EJ162 500GB      | 1        | 1.39%   |
| Seagate ST380011A 80GB               | 1        | 1.39%   |
| Seagate ST3500820AS 500GB            | 1        | 1.39%   |
| Seagate ST3500312CS 500GB            | 1        | 1.39%   |
| Seagate ST340016A 40GB               | 1        | 1.39%   |
| Seagate ST3160023AS 160GB            | 1        | 1.39%   |
| Seagate ST250DM000-1BD141 250GB      | 1        | 1.39%   |
| Seagate ST1000DM003-1ER162 1TB       | 1        | 1.39%   |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 1.39%   |
| Samsung SSD 960 EVO 250GB            | 1        | 1.39%   |
| Samsung SSD 870 QVO 1TB              | 1        | 1.39%   |
| Samsung SSD 860 QVO 1TB              | 1        | 1.39%   |
| Samsung MZVLB1T0HALR-00000 1TB       | 1        | 1.39%   |
| Samsung MZ7LN128HCHP-000H1 128GB SSD | 1        | 1.39%   |
| Samsung HD161GJ 160GB                | 1        | 1.39%   |
| Samsung HD103SJ 1TB                  | 1        | 1.39%   |
| Samsung HD103SI 1TB                  | 1        | 1.39%   |
| Samsung HD080HJ/ 80GB                | 1        | 1.39%   |
| Realtek NVMe SSD Drive 1024GB        | 1        | 1.39%   |
| PNY CS900 120GB SSD                  | 1        | 1.39%   |
| Phison Sabrent Rocket 4.0 2TB        | 1        | 1.39%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD  | 1        | 1.39%   |
| Micron Crucial X8 SSD 1TB            | 1        | 1.39%   |
| Magnetic Data MD03200-NVDW-RO 320GB  | 1        | 1.39%   |
| LITEON IT LCS-128L9S-HP 128GB SSD    | 1        | 1.39%   |
| Intel SSDSC2CT120A3 120GB            | 1        | 1.39%   |
| HS-SSD-E100 SSD 128G                 | 1        | 1.39%   |
| Hitachi HUS724030ALE641 3TB          | 1        | 1.39%   |
| Hitachi HUA723020ALA641 2TB          | 1        | 1.39%   |
| Hitachi HTS725032A7E630 320GB        | 1        | 1.39%   |
| Hitachi HTS542516K9SA00 160GB        | 1        | 1.39%   |
| Hitachi HDT721064SLA380 640GB        | 1        | 1.39%   |
| HGST HTS721010A9E630 1TB             | 1        | 1.39%   |
| HGST HTS545032A7E380 320GB           | 1        | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 22     | 30.61%  |
| WDC                 | 13       | 14     | 26.53%  |
| Hitachi             | 7        | 8      | 14.29%  |
| Toshiba             | 5        | 9      | 10.2%   |
| Samsung Electronics | 4        | 7      | 8.16%   |
| HGST                | 2        | 2      | 4.08%   |
| Fujitsu             | 2        | 2      | 4.08%   |
| Magnetic Data       | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Intel               | 3        | 3      | 21.43%  |
| Samsung Electronics | 2        | 4      | 14.29%  |
| Micron Technology   | 2        | 3      | 14.29%  |
| Crucial             | 2        | 3      | 14.29%  |
| WDC                 | 1        | 1      | 7.14%   |
| PNY                 | 1        | 1      | 7.14%   |
| LITEON              | 1        | 1      | 7.14%   |
| HS-SSD-E100         | 1        | 1      | 7.14%   |
| Unknown             | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 65     | 72.73%  |
| SSD  | 11       | 18     | 20%     |
| NVMe | 4        | 5      | 7.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 81     | 90%     |
| NVMe | 4        | 5      | 8%      |
| SAS  | 1        | 2      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 61     | 76.47%  |
| 0.51-1.0   | 9        | 18     | 17.65%  |
| 1.01-2.0   | 2        | 2      | 3.92%   |
| 2.01-3.0   | 1        | 2      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 29.17%  |
| 1-20           | 8        | 16.67%  |
| 251-500        | 7        | 14.58%  |
| 51-100         | 5        | 10.42%  |
| 21-50          | 4        | 8.33%   |
| 501-1000       | 4        | 8.33%   |
| More than 3000 | 2        | 4.17%   |
| Unknown        | 2        | 4.17%   |
| 2001-3000      | 1        | 2.08%   |
| 1001-2000      | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 25       | 49.02%  |
| 51-100         | 7        | 13.73%  |
| 21-50          | 6        | 11.76%  |
| 251-500        | 4        | 7.84%   |
| 101-250        | 3        | 5.88%   |
| 1001-2000      | 2        | 3.92%   |
| Unknown        | 2        | 3.92%   |
| More than 3000 | 1        | 1.96%   |
| 2001-3000      | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 3        | 3      | 27.27%  |
| Hitachi HDS721680PLA380 80GB      | 2        | 2      | 18.18%  |
| WDC WD2500AAJS-60Z0A0 250GB       | 1        | 1      | 9.09%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 9.09%   |
| Seagate ST340016A 40GB            | 1        | 1      | 9.09%   |
| Seagate ST3250312AS 250GB         | 1        | 1      | 9.09%   |
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 9.09%   |
| Fujitsu MHX2300BT 304GB           | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 54.55%  |
| Hitachi             | 2        | 2      | 18.18%  |
| WDC                 | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Fujitsu             | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 54.55%  |
| Hitachi             | 2        | 2      | 18.18%  |
| WDC                 | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Fujitsu             | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 11     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD800JD-00LSA0 80GB | 2        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 23       | 43     | 43.4%   |
| Works    | 17       | 32     | 32.08%  |
| Malfunc  | 11       | 11     | 20.75%  |
| Failed   | 2        | 2      | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 38       | 73.08%  |
| AMD                              | 5        | 9.62%   |
| Samsung Electronics              | 2        | 3.85%   |
| Nvidia                           | 2        | 3.85%   |
| Silicon Integrated Systems [SiS] | 1        | 1.92%   |
| Realtek Semiconductor            | 1        | 1.92%   |
| Phison Electronics               | 1        | 1.92%   |
| JMicron Technology               | 1        | 1.92%   |
| Broadcom / LSI                   | 1        | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 8.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 8.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 7.14%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 4.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 2.86%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 2.86%   |
| Nvidia MCP61 IDE                                                                        | 2        | 2.86%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 2.86%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 2.86%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 2.86%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.86%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 2.86%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2        | 2.86%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.43%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.43%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.43%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.43%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 1.43%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.43%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.43%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.43%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.43%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 1.43%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.43%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 52.54%  |
| IDE  | 18       | 30.51%  |
| RAID | 4        | 6.78%   |
| NVMe | 4        | 6.78%   |
| SAS  | 2        | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 38       | 82.61%  |
| AMD    | 8        | 17.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 10.87%  |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 4.35%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 4.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 4.35%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 2.17%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 2.17%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 2.17%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz         | 1        | 2.17%   |
| Intel Xeon CPU 5140 @ 2.33GHz               | 1        | 2.17%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2.17%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 2.17%   |
| Intel Pentium CPU G3220T @ 2.60GHz          | 1        | 2.17%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 2.17%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 2.17%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.17%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 1        | 2.17%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 2.17%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 2.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.17%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 2.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.17%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 2.17%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 2.17%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 2.17%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 2.17%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 2.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 2.17%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 2.17%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 2.17%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 2.17%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.17%   |
| AMD Phenom II X6 1090T Processor            | 1        | 2.17%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 2.17%   |
| AMD Athlon XP 2400+                         | 1        | 2.17%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 2.17%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+  | 1        | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 41.3%   |
| Intel Xeon              | 5        | 10.87%  |
| Intel Core i7           | 4        | 8.7%    |
| Intel Core i3           | 3        | 6.52%   |
| Intel Core 2 Duo        | 2        | 4.35%   |
| AMD Athlon 64 X2        | 2        | 4.35%   |
| Intel Pentium Dual-Core | 1        | 2.17%   |
| Intel Pentium Dual      | 1        | 2.17%   |
| Intel Pentium 4         | 1        | 2.17%   |
| Intel Pentium           | 1        | 2.17%   |
| Intel Core 2 Quad       | 1        | 2.17%   |
| AMD Ryzen 9             | 1        | 2.17%   |
| AMD Ryzen 7             | 1        | 2.17%   |
| AMD Ryzen 5             | 1        | 2.17%   |
| AMD Phenom II X6        | 1        | 2.17%   |
| AMD E                   | 1        | 2.17%   |
| AMD Athlon XP           | 1        | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 54.35%  |
| 2      | 13       | 28.26%  |
| 16     | 2        | 4.35%   |
| 6      | 2        | 4.35%   |
| 1      | 2        | 4.35%   |
| 12     | 1        | 2.17%   |
| 8      | 1        | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 95.65%  |
| 2      | 2        | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 67.39%  |
| 2      | 15       | 32.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 95.65%  |
| 32-bit         | 2        | 4.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 8        | 17.39%  |
| 0x306c3    | 7        | 15.22%  |
| Unknown    | 6        | 13.04%  |
| 0x206a7    | 5        | 10.87%  |
| 0x6fb      | 3        | 6.52%   |
| 0x506e3    | 3        | 6.52%   |
| 0x08701021 | 3        | 6.52%   |
| 0x906e9    | 2        | 4.35%   |
| 0x206d7    | 2        | 4.35%   |
| 0xf29      | 1        | 2.17%   |
| 0x6fd      | 1        | 2.17%   |
| 0x306f2    | 1        | 2.17%   |
| 0x106e5    | 1        | 2.17%   |
| 0x10676    | 1        | 2.17%   |
| 0x05000119 | 1        | 2.17%   |
| 0x010000dc | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 9        | 19.57%  |
| Haswell     | 8        | 17.39%  |
| SandyBridge | 7        | 15.22%  |
| Core        | 4        | 8.7%    |
| Zen 2       | 3        | 6.52%   |
| Skylake     | 3        | 6.52%   |
| Penryn      | 2        | 4.35%   |
| KabyLake    | 2        | 4.35%   |
| K8 Hammer   | 2        | 4.35%   |
| Westmere    | 1        | 2.17%   |
| NetBurst    | 1        | 2.17%   |
| Nehalem     | 1        | 2.17%   |
| K6          | 1        | 2.17%   |
| K10         | 1        | 2.17%   |
| Bobcat      | 1        | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 25       | 53.19%  |
| Nvidia                           | 12       | 25.53%  |
| AMD                              | 9        | 19.15%  |
| Silicon Integrated Systems [SiS] | 1        | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 7        | 14.29%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                           | 5        | 10.2%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 4        | 8.16%   |
| Nvidia GT218 [GeForce 210]                                                                 | 3        | 6.12%   |
| Intel HD Graphics 530                                                                      | 3        | 6.12%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 2        | 4.08%   |
| Nvidia GF119 [GeForce GT 610]                                                              | 2        | 4.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 4.08%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1        | 2.04%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                      | 1        | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 2.04%   |
| Nvidia GM204GL [Quadro M4000]                                                              | 1        | 2.04%   |
| Nvidia GK107GL [Quadro K420]                                                               | 1        | 2.04%   |
| Nvidia G72 [GeForce 7500 LE]                                                               | 1        | 2.04%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                     | 1        | 2.04%   |
| Intel HD Graphics 630                                                                      | 1        | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                        | 1        | 2.04%   |
| Intel 82Q35 Express Integrated Graphics Controller                                         | 1        | 2.04%   |
| Intel 82865G Integrated Graphics Controller                                                | 1        | 2.04%   |
| AMD Wrestler [Radeon HD 6320]                                                              | 1        | 2.04%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                             | 1        | 2.04%   |
| AMD RV610 [Radeon HD 2350]                                                                 | 1        | 2.04%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                      | 1        | 2.04%   |
| AMD RV370 [Radeon X600/X600 SE]                                                            | 1        | 2.04%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                                  | 1        | 2.04%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                      | 1        | 2.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                    | 1        | 2.04%   |
| AMD Hawaii XT / Grenada XT [Radeon R9 290X/390X]                                           | 1        | 2.04%   |
| AMD Barts XT [Radeon HD 6870]                                                              | 1        | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 24       | 52.17%  |
| 1 x Nvidia | 11       | 23.91%  |
| 1 x AMD    | 8        | 17.39%  |
| 2 x Nvidia | 1        | 2.17%   |
| 2 x AMD    | 1        | 2.17%   |
| 1 x SiS    | 1        | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 40       | 86.96%  |
| Proprietary | 5        | 10.87%  |
| Unknown     | 1        | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 46.81%  |
| 0.01-0.5   | 8        | 17.02%  |
| 1.01-2.0   | 6        | 12.77%  |
| 0.51-1.0   | 6        | 12.77%  |
| 3.01-4.0   | 3        | 6.38%   |
| 7.01-8.0   | 2        | 4.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 11       | 28.21%  |
| Samsung Electronics  | 9        | 23.08%  |
| Hewlett-Packard      | 6        | 15.38%  |
| Acer                 | 3        | 7.69%   |
| Iiyama               | 2        | 5.13%   |
| Goldstar             | 2        | 5.13%   |
| BenQ                 | 2        | 5.13%   |
| Philips              | 1        | 2.56%   |
| MiTAC                | 1        | 2.56%   |
| Lenovo               | 1        | 2.56%   |
| Ancor Communications | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                      | 3        | 7.5%    |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch   | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch   | 1        | 2.5%    |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch     | 1        | 2.5%    |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch      | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch  | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM0B2A 1280x720 949x543mm 43.0-inch   | 1        | 2.5%    |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                     | 1        | 2.5%    |
| MiTAC Mystery TV MTC9527 1920x1080 1150x650mm 52.0-inch                | 1        | 2.5%    |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                   | 1        | 2.5%    |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                  | 1        | 2.5%    |
| Iiyama PLB2712HDS IVM6602 1920x1080 598x336mm 27.0-inch                | 1        | 2.5%    |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch            | 1        | 2.5%    |
| Hewlett-Packard V213a HPN335B 1920x1080 458x258mm 20.7-inch            | 1        | 2.5%    |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1        | 2.5%    |
| Hewlett-Packard LCD Monitor E232 1920x1080                             | 1        | 2.5%    |
| Hewlett-Packard LA2006 HWP2943 1600x900 443x249mm 20.0-inch            | 1        | 2.5%    |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch              | 1        | 2.5%    |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                    | 1        | 2.5%    |
| Goldstar M2394D GSM56C4 1920x1080 509x286mm 23.0-inch                  | 1        | 2.5%    |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                      | 1        | 2.5%    |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                      | 1        | 2.5%    |
| Dell LCD Monitor P2417H 1920x1080                                      | 1        | 2.5%    |
| Dell E772p DEL7005 1152x864 300x225mm 14.8-inch                        | 1        | 2.5%    |
| Dell E2014H DELD03B 1600x900 432x240mm 19.5-inch                       | 1        | 2.5%    |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                      | 1        | 2.5%    |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                      | 1        | 2.5%    |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                      | 1        | 2.5%    |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                      | 1        | 2.5%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 1        | 2.5%    |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                      | 1        | 2.5%    |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 1        | 2.5%    |
| Acer V246HL ACR032E 1920x1080 531x299mm 24.0-inch                      | 1        | 2.5%    |
| Acer P193W ACR000C 1440x900 410x256mm 19.0-inch                        | 1        | 2.5%    |
| Acer AL1916W ACRAD80 1440x900 410x257mm 19.1-inch                      | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 48.72%  |
| 1280x1024 (SXGA)   | 6        | 15.38%  |
| 1440x900 (WXGA+)   | 4        | 10.26%  |
| 1680x1050 (WSXGA+) | 3        | 7.69%   |
| 3840x2160 (4K)     | 2        | 5.13%   |
| 1600x900 (HD+)     | 2        | 5.13%   |
| 1366x768 (WXGA)    | 1        | 2.56%   |
| 1280x720 (HD)      | 1        | 2.56%   |
| 1152x864           | 1        | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 25%     |
| 19      | 5        | 12.5%   |
| 17      | 5        | 12.5%   |
| 27      | 3        | 7.5%    |
| 23      | 2        | 5%      |
| 22      | 2        | 5%      |
| 21      | 2        | 5%      |
| 20      | 2        | 5%      |
| Unknown | 2        | 5%      |
| 54      | 1        | 2.5%    |
| 52      | 1        | 2.5%    |
| 43      | 1        | 2.5%    |
| 40      | 1        | 2.5%    |
| 18      | 1        | 2.5%    |
| 15      | 1        | 2.5%    |
| 14      | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 35%     |
| 401-500     | 11       | 27.5%   |
| 301-350     | 6        | 15%     |
| 1001-1500   | 2        | 5%      |
| Unknown     | 2        | 5%      |
| 801-900     | 1        | 2.5%    |
| 601-700     | 1        | 2.5%    |
| 351-400     | 1        | 2.5%    |
| 201-300     | 1        | 2.5%    |
| 901-1000    | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 23       | 58.97%  |
| 16/10   | 7        | 17.95%  |
| 5/4     | 6        | 15.38%  |
| Unknown | 2        | 5.13%   |
| 4/3     | 1        | 2.56%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 37.5%   |
| 151-200        | 8        | 20%     |
| 141-150        | 5        | 12.5%   |
| 301-350        | 3        | 7.5%    |
| More than 1000 | 2        | 5%      |
| 101-110        | 2        | 5%      |
| 501-1000       | 2        | 5%      |
| Unknown        | 2        | 5%      |
| 251-300        | 1        | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 75%     |
| 1-50    | 3        | 7.5%    |
| 101-120 | 3        | 7.5%    |
| Unknown | 2        | 5%      |
| 161-240 | 1        | 2.5%    |
| 121-160 | 1        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 93.62%  |
| 0     | 2        | 4.26%   |
| 2     | 1        | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 33       | 44%     |
| Realtek Semiconductor            | 13       | 17.33%  |
| Ralink Technology                | 8        | 10.67%  |
| Ralink                           | 4        | 5.33%   |
| Qualcomm Atheros                 | 4        | 5.33%   |
| TP-Link                          | 2        | 2.67%   |
| Nvidia                           | 2        | 2.67%   |
| D-Link System                    | 2        | 2.67%   |
| Broadcom                         | 2        | 2.67%   |
| Silicon Integrated Systems [SiS] | 1        | 1.33%   |
| Qualcomm Atheros Communications  | 1        | 1.33%   |
| Marvell Technology Group         | 1        | 1.33%   |
| Gemtek                           | 1        | 1.33%   |
| Broadcom Limited                 | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 15%     |
| Intel Ethernet Connection I217-LM                                              | 8        | 10%     |
| Ralink RT5370 Wireless Adapter                                                 | 7        | 8.75%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 5        | 6.25%   |
| Intel I211 Gigabit Network Connection                                          | 3        | 3.75%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 3.75%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 3.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2        | 2.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 2        | 2.5%    |
| Nvidia MCP61 Ethernet                                                          | 2        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                            | 2        | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 2.5%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1        | 1.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1        | 1.25%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 1.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 1.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.25%   |
| Realtek RTL8187 Wireless Adapter                                               | 1        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 1.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.25%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.25%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                           | 1        | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1        | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1        | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 1.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.25%   |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 1.25%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.25%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                              | 1        | 1.25%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]           | 1        | 1.25%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1        | 1.25%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1        | 1.25%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 1        | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 8        | 28.57%  |
| Realtek Semiconductor           | 5        | 17.86%  |
| Ralink                          | 4        | 14.29%  |
| Qualcomm Atheros                | 3        | 10.71%  |
| TP-Link                         | 2        | 7.14%   |
| Intel                           | 2        | 7.14%   |
| Qualcomm Atheros Communications | 1        | 3.57%   |
| Gemtek                          | 1        | 3.57%   |
| D-Link System                   | 1        | 3.57%   |
| Broadcom                        | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink RT5370 Wireless Adapter                                       | 7        | 23.33%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 6.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 2        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 3.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 3.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 3.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 3.33%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 3.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1        | 3.33%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 1        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 3.33%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 3.33%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1        | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 33       | 67.35%  |
| Realtek Semiconductor            | 8        | 16.33%  |
| Nvidia                           | 2        | 4.08%   |
| Silicon Integrated Systems [SiS] | 1        | 2.04%   |
| Qualcomm Atheros                 | 1        | 2.04%   |
| Marvell Technology Group         | 1        | 2.04%   |
| D-Link System                    | 1        | 2.04%   |
| Broadcom Limited                 | 1        | 2.04%   |
| Broadcom                         | 1        | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 24%     |
| Intel Ethernet Connection I217-LM                                              | 8        | 16%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 5        | 10%     |
| Intel I211 Gigabit Network Connection                                          | 3        | 6%      |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 6%      |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3        | 6%      |
| Nvidia MCP61 Ethernet                                                          | 2        | 4%      |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 4%      |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 2%      |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 2%      |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 2%      |
| Intel 82578DM Gigabit Network Connection                                       | 1        | 2%      |
| Intel 82574L Gigabit Network Connection                                        | 1        | 2%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 1        | 2%      |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1        | 2%      |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1        | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 63.89%  |
| WiFi     | 26       | 36.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 61.7%   |
| WiFi     | 18       | 38.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 73.91%  |
| 2     | 10       | 21.74%  |
| 3     | 2        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 46       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 20%     |
| Intel                           | 2        | 20%     |
| Broadcom                        | 2        | 20%     |
| Toshiba                         | 1        | 10%     |
| Realtek Semiconductor           | 1        | 10%     |
| Cambridge Silicon Radio         | 1        | 10%     |
| ASUSTek Computer                | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 20%     |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 10%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 10%     |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| Broadcom HP Portable Valentine                      | 1        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 10%     |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 38       | 61.29%  |
| Nvidia                           | 12       | 19.35%  |
| AMD                              | 8        | 12.9%   |
| Silicon Integrated Systems [SiS] | 1        | 1.61%   |
| Hewlett-Packard                  | 1        | 1.61%   |
| GEMBIRD                          | 1        | 1.61%   |
| C-Media Electronics              | 1        | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 9.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 9.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 9.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 9.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 5.48%   |
| Nvidia High Definition Audio Controller                                    | 3        | 4.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 4.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 4.11%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 2.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 2.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.74%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.37%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.37%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.37%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 1.37%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1        | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.37%   |
| Hewlett-Packard Digital Stereo Headset                                     | 1        | 1.37%   |
| GEMBIRD USB SkypePhone                                                     | 1        | 1.37%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.37%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.37%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.37%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 1        | 1.37%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1        | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 14       | 29.79%  |
| SK hynix            | 13       | 27.66%  |
| Micron Technology   | 7        | 14.89%  |
| Corsair             | 4        | 8.51%   |
| Kingston            | 3        | 6.38%   |
| Unknown             | 1        | 2.13%   |
| TakeMS              | 1        | 2.13%   |
| Qimonda             | 1        | 2.13%   |
| Nanya Technology    | 1        | 2.13%   |
| Apacer              | 1        | 2.13%   |
| Unknown             | 1        | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 4        | 8%      |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 3        | 6%      |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 3        | 6%      |
| Unknown RAM Module 2GB DIMM                              | 1        | 2%      |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s   | 1        | 2%      |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                   | 1        | 2%      |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT41GU6MFR8C-PB 8192MB DIMM DDR3 1600MT/s  | 1        | 2%      |
| SK hynix RAM HMT41GR7BFR4A-PB 8192MB DIMM DDR3 1600MT/s  | 1        | 2%      |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s  | 1        | 2%      |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s     | 1        | 2%      |
| SK hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s  | 1        | 2%      |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s     | 1        | 2%      |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s             | 1        | 2%      |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 2%      |
| Samsung RAM M393A4K40BB1-CRC 32GB RIMM DDR4 2400MT/s     | 1        | 2%      |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 1        | 2%      |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s   | 1        | 2%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s   | 1        | 2%      |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s     | 1        | 2%      |
| Samsung RAM M3 78T2953EZ3-CE6 1024MB DIMM DDR 667MT/s    | 1        | 2%      |
| Samsung RAM M3 78T2863DZS-CE6 1024MB DIMM DDR2 667MT/s   | 1        | 2%      |
| Samsung RAM M3 68L3223FTN-CB3 256MB DIMM DDR 333MT/s     | 1        | 2%      |
| Qimonda RAM 64T128020EU3SB2 1GB DIMM DDR2 667MT/s        | 1        | 2%      |
| Nanya RAM NT128D64SH4B1G-75B 128MB DIMM DDR 266MT/s      | 1        | 2%      |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s | 1        | 2%      |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s       | 1        | 2%      |
| Micron RAM 4JTF25664AZ-1G6E1 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Kingston RAM KTC1G-UDIMM 1GB DIMM DDR2 1639MT/s          | 1        | 2%      |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 2%      |
| Kingston RAM 9905429-002.A00LF 1GB DIMM DDR2 667MT/s     | 1        | 2%      |
| Corsair RAM CMW16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s    | 1        | 2%      |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s   | 1        | 2%      |
| Corsair RAM CMK32GX4M4B3600C16 8192MB DIMM DDR4 3600MT/s | 1        | 2%      |
| Corsair RAM CM3X2G1333C9 2GB DIMM 1333MT/s               | 1        | 2%      |
| Apacer RAM 76.A100G.C350C 2GB DIMM DDR3 1333MT/s         | 1        | 2%      |
| Unknown                                                  | 1        | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 15       | 46.88%  |
| SDRAM   | 6        | 18.75%  |
| DDR4    | 6        | 18.75%  |
| DDR2    | 3        | 9.38%   |
| DDR     | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 24       | 92.31%  |
| SODIMM | 1        | 3.85%   |
| RIMM   | 1        | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 38.24%  |
| 2048  | 6        | 17.65%  |
| 8192  | 5        | 14.71%  |
| 1024  | 5        | 14.71%  |
| 32768 | 2        | 5.88%   |
| 512   | 1        | 2.94%   |
| 256   | 1        | 2.94%   |
| 128   | 1        | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 36.11%  |
| 1333    | 5        | 13.89%  |
| 667     | 3        | 8.33%   |
| 3600    | 2        | 5.56%   |
| 2400    | 2        | 5.56%   |
| 3200    | 1        | 2.78%   |
| 2133    | 1        | 2.78%   |
| 1867    | 1        | 2.78%   |
| 1866    | 1        | 2.78%   |
| 1639    | 1        | 2.78%   |
| 1067    | 1        | 2.78%   |
| 800     | 1        | 2.78%   |
| 400     | 1        | 2.78%   |
| 333     | 1        | 2.78%   |
| 266     | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP Deskjet 3510 series | 1        | 50%     |
| Canon MB2000 series    | 1        | 50%     |

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


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Logitech           | 2        | 66.67%  |
| Lite-On Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 1        | 33.33%  |
| Logitech Logi 4K Stream Edition | 1        | 33.33%  |
| Lite-On EasyCamera 5M           | 1        | 33.33%  |

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
| 0     | 43       | 91.49%  |
| 1     | 3        | 6.38%   |
| 2     | 1        | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 1        | 25%     |
| Net/wireless             | 1        | 25%     |
| Graphics card            | 1        | 25%     |
| Communication controller | 1        | 25%     |

