Linux in Costa Rica - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 73

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| HP            | 83EE                     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| Dell          | 040DDP A01               | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| ZOTAC         | NM10                     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING       | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Dell          | 040DDP A01               | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend        | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Dell          | 0RW203 A00               | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| Dell          | 09KPNV A01               | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI    | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Gigabyte      | Z690 UD AX DDR4          | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING  | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                   | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                 | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                 | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS    | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| TPV-INVENT... | 2AF2 A01                 | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| ZOTAC         | NM10                     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| ZOTAC         | NM10                     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                   | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI    | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| ASUSTek       | PRIME A320M-K            | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Pegatron      | 2AE4                     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Intel         | D33217CK G76541-302      | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | PRIME A320M-K            | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01               | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                    | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF           | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Pegatron      | 2AE4                     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                  | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3             | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| Unknown       | i845G-W83627HF           | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF           | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7           | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF              | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3               | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0       | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01               | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| Gigabyte      | B450 AORUS ELITE         | [92169337a2](https://linux-hardware.org/?probe=92169337a2) | Sep 03, 2020 |
| Dell          | 042P49 A01               | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Gigabyte      | H110M-H-CF               | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Gateway       | FMCP7AM                  | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                 | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0            | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING               | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| ASRock        | B450 Steel Legend        | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| MSI           | B450 GAMING PLUS MAX     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [1a20ef05b3](https://linux-hardware.org/?probe=1a20ef05b3) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [31bfc16ada](https://linux-hardware.org/?probe=31bfc16ada) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| ASRock        | 775i65GV                 | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| ASRock        | 775i65GV                 | [6bcd6d12f1](https://linux-hardware.org/?probe=6bcd6d12f1) | Dec 31, 2019 |
| ASRock        | 775i65GV                 | [46cbfd5ee9](https://linux-hardware.org/?probe=46cbfd5ee9) | Dec 25, 2019 |
| ASRock        | 775i65GV                 | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| Dell          | 042P49 A01               | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| Gigabyte      | GA-78LMT-S2              | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| Biostar       | H61MGV3                  | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| Biostar       | H61MGV3                  | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103      | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| Lenovo        | SHARKBAY 31900003 STD    | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 9        | 15.79%  |
| Ubuntu 20.04        | 8        | 14.04%  |
| Ubuntu 18.04        | 3        | 5.26%   |
| Linux Mint 20.2     | 3        | 5.26%   |
| Pop!_OS 21.04       | 2        | 3.51%   |
| OpenMandriva 4.3    | 2        | 3.51%   |
| Linux Mint 19.3     | 2        | 3.51%   |
| Fedora 32           | 2        | 3.51%   |
| Zorin 15            | 1        | 1.75%   |
| Zorin 12            | 1        | 1.75%   |
| Ubuntu 20.10        | 1        | 1.75%   |
| Ubuntu 19.10        | 1        | 1.75%   |
| ROSA R8.1           | 1        | 1.75%   |
| ROSA R11.1          | 1        | 1.75%   |
| ROSA R11            | 1        | 1.75%   |
| Pop!_OS 20.10       | 1        | 1.75%   |
| Pop!_OS 20.04       | 1        | 1.75%   |
| OpenMandriva 4.50   | 1        | 1.75%   |
| Manjaro 21.2.5      | 1        | 1.75%   |
| Manjaro 21.2.0      | 1        | 1.75%   |
| Lubuntu 22.04       | 1        | 1.75%   |
| Lubuntu 21.10       | 1        | 1.75%   |
| Lubuntu 20.04       | 1        | 1.75%   |
| Linux Mint 20       | 1        | 1.75%   |
| KDE neon 18.04      | 1        | 1.75%   |
| Fedora 34           | 1        | 1.75%   |
| EndeavourOS Rolling | 1        | 1.75%   |
| Elementary 6        | 1        | 1.75%   |
| Elementary 5.1.7    | 1        | 1.75%   |
| Debian Testing      | 1        | 1.75%   |
| Debian 11           | 1        | 1.75%   |
| BlackPanther 18.1   | 1        | 1.75%   |
| Arch Rolling        | 1        | 1.75%   |
| Arch                | 1        | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 13       | 24.07%  |
| OpenMandriva | 12       | 22.22%  |
| Linux Mint   | 6        | 11.11%  |
| Pop!_OS      | 4        | 7.41%   |
| Fedora       | 3        | 5.56%   |
| Zorin        | 2        | 3.7%    |
| ROSA         | 2        | 3.7%    |
| Manjaro      | 2        | 3.7%    |
| Elementary   | 2        | 3.7%    |
| Debian       | 2        | 3.7%    |
| Arch         | 2        | 3.7%    |
| Lubuntu      | 1        | 1.85%   |
| KDE neon     | 1        | 1.85%   |
| EndeavourOS  | 1        | 1.85%   |
| BlackPanther | 1        | 1.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 9        | 15%     |
| 5.4.0-70-generic                | 3        | 5%      |
| 5.4.0-42-generic                | 2        | 3.33%   |
| 5.16.7-desktop-1omv4003         | 2        | 3.33%   |
| 5.9.9-arch1-1                   | 1        | 1.67%   |
| 5.9.14-arch1-1                  | 1        | 1.67%   |
| 5.8.0-7630-generic              | 1        | 1.67%   |
| 5.8.0-50-generic                | 1        | 1.67%   |
| 5.8.0-41-generic                | 1        | 1.67%   |
| 5.8.0-34-generic                | 1        | 1.67%   |
| 5.7.0-1-amd64                   | 1        | 1.67%   |
| 5.6.19-300.fc32.x86_64          | 1        | 1.67%   |
| 5.6.16-300.fc32.x86_64          | 1        | 1.67%   |
| 5.6.14-desktop-2bP              | 1        | 1.67%   |
| 5.6.13-arch1-1                  | 1        | 1.67%   |
| 5.4.40-generic-1rosa-x86_64     | 1        | 1.67%   |
| 5.4.0-91-generic                | 1        | 1.67%   |
| 5.4.0-88-generic                | 1        | 1.67%   |
| 5.4.0-60-generic                | 1        | 1.67%   |
| 5.4.0-56-generic                | 1        | 1.67%   |
| 5.4.0-52-generic                | 1        | 1.67%   |
| 5.4.0-45-generic                | 1        | 1.67%   |
| 5.4.0-29-generic                | 1        | 1.67%   |
| 5.4.0-26-generic                | 1        | 1.67%   |
| 5.3.0-62-generic                | 1        | 1.67%   |
| 5.3.0-51-generic                | 1        | 1.67%   |
| 5.15.11-1-MANJARO               | 1        | 1.67%   |
| 5.15.0-25-generic               | 1        | 1.67%   |
| 5.14.14-desktop-1omv4050        | 1        | 1.67%   |
| 5.13.9-200.fc34.x86_64          | 1        | 1.67%   |
| 5.13.0-7620-generic             | 1        | 1.67%   |
| 5.13.0-16-generic               | 1        | 1.67%   |
| 5.11.11-arch1-1                 | 1        | 1.67%   |
| 5.11.0-7620-generic             | 1        | 1.67%   |
| 5.11.0-7614-generic             | 1        | 1.67%   |
| 5.11.0-41-generic               | 1        | 1.67%   |
| 5.11.0-27-generic               | 1        | 1.67%   |
| 5.10.94-xanmod2                 | 1        | 1.67%   |
| 5.10.105-1-MANJARO              | 1        | 1.67%   |
| 5.10.0-2-amd64                  | 1        | 1.67%   |
| 4.18.0-21-generic               | 1        | 1.67%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 1        | 1.67%   |
| 4.15.0-74-generic               | 1        | 1.67%   |
| 4.15.0-72-generic               | 1        | 1.67%   |
| 4.15.0-39-generic               | 1        | 1.67%   |
| 4.15.0-167-generic              | 1        | 1.67%   |
| 4.15.0-147-generic              | 1        | 1.67%   |
| 4.1.38-nrj-desktop-2rosa-x86_64 | 1        | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 12       | 20.69%  |
| 5.10.14  | 9        | 15.52%  |
| 4.15.0   | 5        | 8.62%   |
| 5.8.0    | 4        | 6.9%    |
| 5.11.0   | 4        | 6.9%    |
| 5.3.0    | 2        | 3.45%   |
| 5.16.7   | 2        | 3.45%   |
| 5.13.0   | 2        | 3.45%   |
| 5.9.9    | 1        | 1.72%   |
| 5.9.14   | 1        | 1.72%   |
| 5.7.0    | 1        | 1.72%   |
| 5.6.19   | 1        | 1.72%   |
| 5.6.16   | 1        | 1.72%   |
| 5.6.14   | 1        | 1.72%   |
| 5.6.13   | 1        | 1.72%   |
| 5.4.40   | 1        | 1.72%   |
| 5.15.11  | 1        | 1.72%   |
| 5.15.0   | 1        | 1.72%   |
| 5.14.14  | 1        | 1.72%   |
| 5.13.9   | 1        | 1.72%   |
| 5.11.11  | 1        | 1.72%   |
| 5.10.94  | 1        | 1.72%   |
| 5.10.105 | 1        | 1.72%   |
| 5.10.0   | 1        | 1.72%   |
| 4.18.0   | 1        | 1.72%   |
| 4.1.38   | 1        | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 13       | 22.41%  |
| 5.10    | 12       | 20.69%  |
| 5.11    | 5        | 8.62%   |
| 4.15    | 5        | 8.62%   |
| 5.8     | 4        | 6.9%    |
| 5.6     | 4        | 6.9%    |
| 5.13    | 3        | 5.17%   |
| 5.9     | 2        | 3.45%   |
| 5.3     | 2        | 3.45%   |
| 5.16    | 2        | 3.45%   |
| 5.15    | 2        | 3.45%   |
| 5.7     | 1        | 1.72%   |
| 5.14    | 1        | 1.72%   |
| 4.18    | 1        | 1.72%   |
| 4.1     | 1        | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 94.23%  |
| i686   | 3        | 5.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 19       | 35.85%  |
| KDE5          | 15       | 28.3%   |
| Unknown       | 6        | 11.32%  |
| X-Cinnamon    | 3        | 5.66%   |
| Pantheon      | 2        | 3.77%   |
| MATE          | 2        | 3.77%   |
| XFCE          | 1        | 1.89%   |
| LXQt          | 1        | 1.89%   |
| KDE           | 1        | 1.89%   |
| GNOME Classic | 1        | 1.89%   |
| Deepin        | 1        | 1.89%   |
| Cinnamon      | 1        | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 48       | 92.31%  |
| Wayland | 3        | 5.77%   |
| Tty     | 1        | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 50%     |
| SDDM    | 16       | 30.77%  |
| GDM     | 5        | 9.62%   |
| TDM     | 3        | 5.77%   |
| LightDM | 1        | 1.92%   |
| GDM3    | 1        | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 50%     |
| es_CR   | 18       | 33.33%  |
| Unknown | 5        | 9.26%   |
| es_ES   | 3        | 5.56%   |
| de_DE   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 29       | 55.77%  |
| BIOS | 23       | 44.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 37       | 71.15%  |
| Overlay | 11       | 21.15%  |
| Btrfs   | 2        | 3.85%   |
| Xfs     | 1        | 1.92%   |
| Unknown | 1        | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 50%     |
| GPT     | 20       | 38.46%  |
| MBR     | 6        | 11.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 82.69%  |
| Yes       | 9        | 17.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 51.92%  |
| Yes       | 25       | 48.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 10       | 19.23%  |
| ASUSTek Computer    | 10       | 19.23%  |
| Gigabyte Technology | 9        | 17.31%  |
| ASRock              | 5        | 9.62%   |
| MSI                 | 4        | 7.69%   |
| Intel               | 2        | 3.85%   |
| Hewlett-Packard     | 2        | 3.85%   |
| ZOTAC               | 1        | 1.92%   |
| TPV-INVENTA         | 1        | 1.92%   |
| Supermicro          | 1        | 1.92%   |
| Pegatron            | 1        | 1.92%   |
| Lenovo              | 1        | 1.92%   |
| Gateway             | 1        | 1.92%   |
| Biostar             | 1        | 1.92%   |
| Alienware           | 1        | 1.92%   |
| ABIT                | 1        | 1.92%   |
| Unknown             | 1        | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 5        | 9.62%   |
| Gigabyte B250M-DS3H                      | 2        | 3.85%   |
| ASUS PRIME A320M-K                       | 2        | 3.85%   |
| ASRock B450 Steel Legend                 | 2        | 3.85%   |
| ZOTAC NM10                               | 1        | 1.92%   |
| TPV-INVENTA 18-2003LA                    | 1        | 1.92%   |
| Supermicro X9DAi                         | 1        | 1.92%   |
| Pegatron CQ2728LA                        | 1        | 1.92%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 1.92%   |
| MSI MS-7B86                              | 1        | 1.92%   |
| MSI MS-7693                              | 1        | 1.92%   |
| MSI MS-7636                              | 1        | 1.92%   |
| Lenovo H530S 10132                       | 1        | 1.92%   |
| Intel DG41WV AAE90316-103                | 1        | 1.92%   |
| Intel D33217CK G76541-302                | 1        | 1.92%   |
| HP ProDesk 600 G4 SFF                    | 1        | 1.92%   |
| HP EliteDesk 800 G1 TWR                  | 1        | 1.92%   |
| Gigabyte Z690 UD AX DDR4                 | 1        | 1.92%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.92%   |
| Gigabyte X570 I AORUS PRO WIFI           | 1        | 1.92%   |
| Gigabyte H110M-S2                        | 1        | 1.92%   |
| Gigabyte H110M-H                         | 1        | 1.92%   |
| Gigabyte GA-970A-D3                      | 1        | 1.92%   |
| Gigabyte B450 AORUS ELITE                | 1        | 1.92%   |
| Gateway LX6810-01                        | 1        | 1.92%   |
| Dell Precision WorkStation T5400         | 1        | 1.92%   |
| Dell Precision WorkStation T3500         | 1        | 1.92%   |
| Dell OptiPlex 755                        | 1        | 1.92%   |
| Dell OptiPlex 7040                       | 1        | 1.92%   |
| Dell OptiPlex 3010                       | 1        | 1.92%   |
| Biostar H61MGV3                          | 1        | 1.92%   |
| ASUS TUF GAMING X570-PLUS                | 1        | 1.92%   |
| ASUS TUF GAMING B550M-PLUS               | 1        | 1.92%   |
| ASUS STRIX Z270G GAMING                  | 1        | 1.92%   |
| ASUS SABERTOOTH 990FX R2.0               | 1        | 1.92%   |
| ASUS ROG STRIX B550-F GAMING             | 1        | 1.92%   |
| ASUS PRIME H310M-E R2.0                  | 1        | 1.92%   |
| ASUS H110M-K                             | 1        | 1.92%   |
| ASUS All Series                          | 1        | 1.92%   |
| ASRock H81M-VG4 R2.0                     | 1        | 1.92%   |
| ASRock 970 Extreme3                      | 1        | 1.92%   |
| ASRock 775i65GV                          | 1        | 1.92%   |
| Alienware X51                            | 1        | 1.92%   |
| ABIT AW9D-MAX                            | 1        | 1.92%   |
| Unknown                                  | 1        | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 8        | 15.38%  |
| ASUS PRIME            | 3        | 5.77%   |
| Gigabyte B250M-DS3H   | 2        | 3.85%   |
| Dell Precision        | 2        | 3.85%   |
| ASUS TUF              | 2        | 3.85%   |
| ASRock B450           | 2        | 3.85%   |
| ZOTAC NM10            | 1        | 1.92%   |
| TPV-INVENTA 18-2003LA | 1        | 1.92%   |
| Supermicro X9DAi      | 1        | 1.92%   |
| Pegatron CQ2728LA     | 1        | 1.92%   |
| MSI Z390              | 1        | 1.92%   |
| MSI MS-7B86           | 1        | 1.92%   |
| MSI MS-7693           | 1        | 1.92%   |
| MSI MS-7636           | 1        | 1.92%   |
| Lenovo H530S          | 1        | 1.92%   |
| Intel DG41WV          | 1        | 1.92%   |
| Intel D33217CK        | 1        | 1.92%   |
| HP ProDesk            | 1        | 1.92%   |
| HP EliteDesk          | 1        | 1.92%   |
| Gigabyte Z690         | 1        | 1.92%   |
| Gigabyte Z170X-Gaming | 1        | 1.92%   |
| Gigabyte X570         | 1        | 1.92%   |
| Gigabyte H110M-S2     | 1        | 1.92%   |
| Gigabyte H110M-H      | 1        | 1.92%   |
| Gigabyte GA-970A-D3   | 1        | 1.92%   |
| Gigabyte B450         | 1        | 1.92%   |
| Gateway LX6810-01     | 1        | 1.92%   |
| Biostar H61MGV3       | 1        | 1.92%   |
| ASUS STRIX            | 1        | 1.92%   |
| ASUS SABERTOOTH       | 1        | 1.92%   |
| ASUS ROG              | 1        | 1.92%   |
| ASUS H110M-K          | 1        | 1.92%   |
| ASUS All              | 1        | 1.92%   |
| ASRock H81M-VG4       | 1        | 1.92%   |
| ASRock 970            | 1        | 1.92%   |
| ASRock 775i65GV       | 1        | 1.92%   |
| Alienware X51         | 1        | 1.92%   |
| ABIT AW9D-MAX         | 1        | 1.92%   |
| Unknown               | 1        | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 7        | 13.46%  |
| 2014 | 7        | 13.46%  |
| 2016 | 6        | 11.54%  |
| 2013 | 6        | 11.54%  |
| 2012 | 5        | 9.62%   |
| 2018 | 4        | 7.69%   |
| 2017 | 3        | 5.77%   |
| 2008 | 3        | 5.77%   |
| 2020 | 2        | 3.85%   |
| 2011 | 2        | 3.85%   |
| 2010 | 2        | 3.85%   |
| 2005 | 2        | 3.85%   |
| 2021 | 1        | 1.92%   |
| 2009 | 1        | 1.92%   |
| 2007 | 1        | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 52       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 48       | 92.31%  |
| Enabled  | 4        | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 16       | 30.19%  |
| 8.01-16.0       | 13       | 24.53%  |
| 3.01-4.0        | 9        | 16.98%  |
| 4.01-8.0        | 6        | 11.32%  |
| 1.01-2.0        | 4        | 7.55%   |
| 32.01-64.0      | 3        | 5.66%   |
| More than 256.0 | 1        | 1.89%   |
| 2.01-3.0        | 1        | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 24       | 42.86%  |
| 2.01-3.0   | 10       | 17.86%  |
| 4.01-8.0   | 9        | 16.07%  |
| 0.51-1.0   | 4        | 7.14%   |
| 3.01-4.0   | 3        | 5.36%   |
| 0.01-0.5   | 3        | 5.36%   |
| 24.01-32.0 | 1        | 1.79%   |
| 16.01-24.0 | 1        | 1.79%   |
| 8.01-16.0  | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 50%     |
| 2      | 15       | 27.78%  |
| 4      | 6        | 11.11%  |
| 3      | 4        | 7.41%   |
| 8      | 1        | 1.85%   |
| 5      | 1        | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 50.94%  |
| No        | 26       | 49.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 51       | 98.08%  |
| No        | 1        | 1.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 59.62%  |
| Yes       | 21       | 40.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 75.47%  |
| Yes       | 13       | 24.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 52       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| San JosГ© | 15       | 27.27%  |
| Heredia     | 13       | 23.64%  |
| San JosÃ© | 8        | 14.55%  |
| Alajuela    | 5        | 9.09%   |
| Puntarenas  | 3        | 5.45%   |
| Moravia     | 2        | 3.64%   |
| Cartago     | 2        | 3.64%   |
| SÃ¡mara   | 1        | 1.82%   |
| Santa Ana   | 1        | 1.82%   |
| San Pedro   | 1        | 1.82%   |
| San José   | 1        | 1.82%   |
| Nicoya      | 1        | 1.82%   |
| LimÃ³n    | 1        | 1.82%   |
| Alajuelita  | 1        | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 20       | 36     | 22.99%  |
| WDC                   | 16       | 18     | 18.39%  |
| A-DATA Technology     | 10       | 10     | 11.49%  |
| Toshiba               | 7        | 8      | 8.05%   |
| Samsung Electronics   | 6        | 10     | 6.9%    |
| Kingston              | 6        | 8      | 6.9%    |
| Hitachi               | 5        | 7      | 5.75%   |
| XPG                   | 4        | 4      | 4.6%    |
| ZOTAC                 | 2        | 3      | 2.3%    |
| Realtek Semiconductor | 2        | 3      | 2.3%    |
| MAXTOR                | 2        | 2      | 2.3%    |
| HGST                  | 2        | 2      | 2.3%    |
| WD MediaMax           | 1        | 1      | 1.15%   |
| SanDisk               | 1        | 1      | 1.15%   |
| Patriot               | 1        | 1      | 1.15%   |
| JMicron               | 1        | 1      | 1.15%   |
| Crucial               | 1        | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| A-DATA SU630 480GB SSD               | 5        | 5.26%   |
| WDC WD10EZEX-75WN4A1 1TB             | 3        | 3.16%   |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 3.16%   |
| Kingston SA400S37240G 240GB SSD      | 3        | 3.16%   |
| XPG GAMMIX S11 Pro 512GB             | 2        | 2.11%   |
| Toshiba DT01ACA100 1TB               | 2        | 2.11%   |
| Seagate ST8000DM004-2CX188 8TB       | 2        | 2.11%   |
| Seagate ST380815AS 80GB              | 2        | 2.11%   |
| A-DATA SU650 120GB SSD               | 2        | 2.11%   |
| ZOTAC ZTSSD-S11-240G-P 240GB         | 1        | 1.05%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB        | 1        | 1.05%   |
| XPG NVMe SSD Drive 512GB             | 1        | 1.05%   |
| XPG NVMe SSD Drive 1TB               | 1        | 1.05%   |
| WDC WD6400AAKS-22A7B0 640GB          | 1        | 1.05%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1        | 1.05%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1        | 1.05%   |
| WDC WD2500AAJS-00VTA0 250GB          | 1        | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 1.05%   |
| WDC WD1600BEVS-26VAT0 160GB          | 1        | 1.05%   |
| WDC WD1500HLFS-01G6U0 150GB          | 1        | 1.05%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1        | 1.05%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1        | 1.05%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1.05%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1        | 1.05%   |
| WDC WD10EADS-65M2BX 1TB              | 1        | 1.05%   |
| WD MediaMax WL3000GSA6472 3TB        | 1        | 1.05%   |
| Toshiba THNSN5512GPUK NVMe 512GB     | 1        | 1.05%   |
| Toshiba RD400 256GB                  | 1        | 1.05%   |
| Toshiba MQ01ABD100 1TB               | 1        | 1.05%   |
| Toshiba HDWD110 1TB                  | 1        | 1.05%   |
| Toshiba HDWD105 500GB                | 1        | 1.05%   |
| Seagate ST8000DM005-2EH112 8TB       | 1        | 1.05%   |
| Seagate ST6000VN0033-2EE110 6TB      | 1        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1.05%   |
| Seagate ST4000DM006-2G5107 4TB       | 1        | 1.05%   |
| Seagate ST3500418AS 500GB            | 1        | 1.05%   |
| Seagate ST3500414CS 500GB            | 1        | 1.05%   |
| Seagate ST3500320AS 500GB            | 1        | 1.05%   |
| Seagate ST3320413CS 320GB            | 1        | 1.05%   |
| Seagate ST3250318AS 250GB            | 1        | 1.05%   |
| Seagate ST3160811AS 160GB            | 1        | 1.05%   |
| Seagate ST31000322CS 1TB             | 1        | 1.05%   |
| Seagate ST250DM000-1BD141 250GB      | 1        | 1.05%   |
| Seagate ST2000LM015-2E8174 2TB       | 1        | 1.05%   |
| Seagate ST2000LM007-1R8174 2TB       | 1        | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 1.05%   |
| Seagate Expansion Desk 3TB           | 1        | 1.05%   |
| Seagate Backup+ Hub BK 6TB           | 1        | 1.05%   |
| Seagate Backup+ Desk 5TB             | 1        | 1.05%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD  | 1        | 1.05%   |
| Samsung SSD 980 PRO 500GB            | 1        | 1.05%   |
| Samsung SSD 850 EVO 250GB            | 1        | 1.05%   |
| Samsung SSD 830 Series 256GB         | 1        | 1.05%   |
| Samsung MZVLV512HCJH-00000 512GB     | 1        | 1.05%   |
| Samsung MZVLB512HAJQ-00000 512GB     | 1        | 1.05%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD | 1        | 1.05%   |
| Realtek NVMe SSD Drive 512GB         | 1        | 1.05%   |
| Realtek NVMe SSD Drive 256GB         | 1        | 1.05%   |
| Patriot Burst 480GB SSD              | 1        | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 19       | 35     | 38.78%  |
| WDC     | 16       | 18     | 32.65%  |
| Toshiba | 5        | 6      | 10.2%   |
| Hitachi | 5        | 7      | 10.2%   |
| MAXTOR  | 2        | 2      | 4.08%   |
| HGST    | 2        | 2      | 4.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| A-DATA Technology   | 9        | 9      | 37.5%   |
| Kingston            | 6        | 8      | 25%     |
| Samsung Electronics | 3        | 5      | 12.5%   |
| ZOTAC               | 2        | 3      | 8.33%   |
| SanDisk             | 1        | 1      | 4.17%   |
| Patriot             | 1        | 1      | 4.17%   |
| JMicron             | 1        | 1      | 4.17%   |
| Crucial             | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 39       | 70     | 54.17%  |
| SSD     | 22       | 29     | 30.56%  |
| NVMe    | 10       | 15     | 13.89%  |
| Unknown | 1        | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 50       | 93     | 78.13%  |
| NVMe | 10       | 15     | 15.63%  |
| SAS  | 4        | 8      | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 55     | 55.07%  |
| 0.51-1.0   | 21       | 26     | 30.43%  |
| 4.01-10.0  | 5        | 8      | 7.25%   |
| 1.01-2.0   | 3        | 4      | 4.35%   |
| 3.01-4.0   | 1        | 1      | 1.45%   |
| 2.01-3.0   | 1        | 5      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 18.52%  |
| 1-20           | 9        | 16.67%  |
| 501-1000       | 9        | 16.67%  |
| More than 3000 | 6        | 11.11%  |
| 251-500        | 6        | 11.11%  |
| 1001-2000      | 6        | 11.11%  |
| 51-100         | 6        | 11.11%  |
| 21-50          | 1        | 1.85%   |
| Unknown        | 1        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 43.64%  |
| 21-50          | 6        | 10.91%  |
| 251-500        | 5        | 9.09%   |
| 101-250        | 5        | 9.09%   |
| More than 3000 | 4        | 7.27%   |
| 1001-2000      | 3        | 5.45%   |
| 501-1000       | 3        | 5.45%   |
| 2001-3000      | 2        | 3.64%   |
| 51-100         | 2        | 3.64%   |
| Unknown        | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD10EADS-65M2BX 1TB             | 1        | 1      | 16.67%  |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 16.67%  |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 1        | 1      | 16.67%  |
| MAXTOR STM3160215AS 160GB           | 1        | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1      | 16.67%  |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 16.67%  |
| Seagate  | 1        | 2      | 16.67%  |
| SanDisk  | 1        | 1      | 16.67%  |
| MAXTOR   | 1        | 1      | 16.67%  |
| Kingston | 1        | 1      | 16.67%  |
| Hitachi  | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 2      | 25%     |
| MAXTOR  | 1        | 1      | 25%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Detected | 29       | 66     | 51.79%  |
| Works    | 21       | 43     | 37.5%   |
| Malfunc  | 6        | 7      | 10.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 35       | 49.3%   |
| AMD                          | 16       | 22.54%  |
| ASMedia Technology           | 4        | 5.63%   |
| ADATA Technology             | 4        | 5.63%   |
| Samsung Electronics          | 3        | 4.23%   |
| Realtek Semiconductor        | 3        | 4.23%   |
| Toshiba America Info Systems | 1        | 1.41%   |
| Silicon Image                | 1        | 1.41%   |
| OCZ Technology Group         | 1        | 1.41%   |
| Nvidia                       | 1        | 1.41%   |
| Marvell Technology Group     | 1        | 1.41%   |
| JMicron Technology           | 1        | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 10.98%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 9.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 6.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 4.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 4.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 4.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.66%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 2.44%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.44%   |
| AMD FCH SATA Controller D                                                               | 2        | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.44%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.22%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.22%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.22%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 1.22%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 1.22%   |
| Nvidia MCP79 RAID Controller                                                            | 1        | 1.22%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.22%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 1.22%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.22%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.22%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.22%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 1.22%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 1.22%   |
| Intel 82801DB (ICH4) IDE Controller                                                     | 1        | 1.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.22%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 1.22%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 64.71%  |
| NVMe | 10       | 14.71%  |
| IDE  | 9        | 13.24%  |
| RAID | 4        | 5.88%   |
| SAS  | 1        | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 69.23%  |
| AMD    | 16       | 30.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 9.62%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 7.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 3.85%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 3.85%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 3.85%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.92%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 1.92%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 1.92%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.92%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.92%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.92%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 1.92%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.92%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.92%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.92%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.92%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.92%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.92%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.92%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.92%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.92%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.92%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.92%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.92%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.92%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1.92%   |
| Intel Celeron CPU 2.66GHz                   | 1        | 1.92%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.92%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.92%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 1        | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.92%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 1.92%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 1.92%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 1.92%   |
| AMD FX-8320E Eight-Core Processor           | 1        | 1.92%   |
| AMD FX-8120 Eight-Core Processor            | 1        | 1.92%   |
| AMD FX-6350 Six-Core Processor              | 1        | 1.92%   |
| AMD E2-1800 APU with Radeon HD Graphics     | 1        | 1.92%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1        | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 28.85%  |
| AMD Ryzen 5             | 6        | 11.54%  |
| Intel Core i3           | 5        | 9.62%   |
| AMD FX                  | 4        | 7.69%   |
| Intel Xeon              | 3        | 5.77%   |
| Intel Pentium           | 2        | 3.85%   |
| Intel Core i7           | 2        | 3.85%   |
| AMD Ryzen 7             | 2        | 3.85%   |
| Other                   | 1        | 1.92%   |
| Intel Pentium Dual-Core | 1        | 1.92%   |
| Intel Pentium 4         | 1        | 1.92%   |
| Intel Core i9           | 1        | 1.92%   |
| Intel Core 2 Quad       | 1        | 1.92%   |
| Intel Core 2 Duo        | 1        | 1.92%   |
| Intel Core 2            | 1        | 1.92%   |
| Intel Celeron           | 1        | 1.92%   |
| Intel Atom              | 1        | 1.92%   |
| AMD Ryzen 7 PRO         | 1        | 1.92%   |
| AMD Ryzen 3             | 1        | 1.92%   |
| AMD E2                  | 1        | 1.92%   |
| AMD E1                  | 1        | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 24       | 46.15%  |
| 2      | 11       | 21.15%  |
| 6      | 7        | 13.46%  |
| 8      | 4        | 7.69%   |
| 1      | 3        | 5.77%   |
| 20     | 1        | 1.92%   |
| 10     | 1        | 1.92%   |
| 3      | 1        | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 98.08%  |
| 2      | 1        | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 57.69%  |
| 2      | 22       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 50       | 96.15%  |
| 32-bit         | 1        | 1.92%   |
| Unknown        | 1        | 1.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 14.81%  |
| Unknown    | 6        | 11.11%  |
| 0x906e9    | 4        | 7.41%   |
| 0x306a9    | 4        | 7.41%   |
| 0x08701021 | 4        | 7.41%   |
| 0x506e3    | 2        | 3.7%    |
| 0x10676    | 2        | 3.7%    |
| 0x06000852 | 2        | 3.7%    |
| 0x05000119 | 2        | 3.7%    |
| 0xf49      | 1        | 1.85%   |
| 0xf29      | 1        | 1.85%   |
| 0x906ec    | 1        | 1.85%   |
| 0x906eb    | 1        | 1.85%   |
| 0x906ea    | 1        | 1.85%   |
| 0x90672    | 1        | 1.85%   |
| 0x6f6      | 1        | 1.85%   |
| 0x306e4    | 1        | 1.85%   |
| 0x106e5    | 1        | 1.85%   |
| 0x106ca    | 1        | 1.85%   |
| 0x106a5    | 1        | 1.85%   |
| 0x10677    | 1        | 1.85%   |
| 0x08701013 | 1        | 1.85%   |
| 0x08701011 | 1        | 1.85%   |
| 0x0870100a | 1        | 1.85%   |
| 0x08600106 | 1        | 1.85%   |
| 0x08108109 | 1        | 1.85%   |
| 0x0800820d | 1        | 1.85%   |
| 0x0500010d | 1        | 1.85%   |
| 0x00000000 | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Haswell    | 9        | 17.31%  |
| KabyLake   | 8        | 15.38%  |
| Zen 2      | 7        | 13.46%  |
| IvyBridge  | 5        | 9.62%   |
| Penryn     | 4        | 7.69%   |
| Skylake    | 3        | 5.77%   |
| Piledriver | 3        | 5.77%   |
| Zen+       | 2        | 3.85%   |
| NetBurst   | 2        | 3.85%   |
| Nehalem    | 2        | 3.85%   |
| Bobcat     | 2        | 3.85%   |
| Zen 3      | 1        | 1.92%   |
| Core       | 1        | 1.92%   |
| Bulldozer  | 1        | 1.92%   |
| Bonnell    | 1        | 1.92%   |
| Unknown    | 1        | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 23       | 40.35%  |
| Nvidia | 22       | 38.6%   |
| AMD    | 12       | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 13.79%  |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 5.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.17%   |
| Intel HD Graphics 630                                                       | 3        | 5.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 5.17%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.45%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 3.45%   |
| Intel HD Graphics 530                                                       | 2        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.72%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 1.72%   |
| Nvidia GT218 [ION]                                                          | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.72%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1        | 1.72%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.72%   |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.72%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.72%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.72%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device          | 1        | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.72%   |
| AMD Wrestler [Radeon HD 7340]                                               | 1        | 1.72%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.72%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.72%   |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                        | 1        | 1.72%   |
| AMD RV530 [Radeon X1650] (Secondary)                                        | 1        | 1.72%   |
| AMD Renoir                                                                  | 1        | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.72%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 21       | 39.62%  |
| 1 x Nvidia     | 19       | 35.85%  |
| 1 x AMD        | 9        | 16.98%  |
| AMD + Nvidia   | 2        | 3.77%   |
| 2 x AMD        | 1        | 1.89%   |
| Intel + Nvidia | 1        | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 40       | 76.92%  |
| Proprietary | 12       | 23.08%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 37.04%  |
| 1.01-2.0   | 9        | 16.67%  |
| 0.51-1.0   | 7        | 12.96%  |
| 0.01-0.5   | 6        | 11.11%  |
| 5.01-6.0   | 5        | 9.26%   |
| 3.01-4.0   | 5        | 9.26%   |
| 7.01-8.0   | 2        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 16       | 27.12%  |
| Hewlett-Packard      | 9        | 15.25%  |
| Goldstar             | 6        | 10.17%  |
| Dell                 | 5        | 8.47%   |
| ViewSonic            | 3        | 5.08%   |
| BenQ                 | 3        | 5.08%   |
| Sony                 | 2        | 3.39%   |
| Samsung Electronics  | 2        | 3.39%   |
| Acer                 | 2        | 3.39%   |
| Xerox                | 1        | 1.69%   |
| Unknown (XXX)        | 1        | 1.69%   |
| Royal Information    | 1        | 1.69%   |
| Philips              | 1        | 1.69%   |
| Panasonic            | 1        | 1.69%   |
| MSI                  | 1        | 1.69%   |
| LTM                  | 1        | 1.69%   |
| Lenovo               | 1        | 1.69%   |
| Haier                | 1        | 1.69%   |
| Ancor Communications | 1        | 1.69%   |
| AGO                  | 1        | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 8.06%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 3.23%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 1.61%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 1.61%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 1.61%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 1.61%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.61%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                        | 1        | 1.61%   |
| Sony TV SNY0902 1360x768                                             | 1        | 1.61%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 1.61%   |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 1.61%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                   | 1        | 1.61%   |
| MSI MAG271CQP MSI3FA7 2560x1440 597x336mm 27.0-inch                  | 1        | 1.61%   |
| LTM LCD_VGA LTM0659 1024x768 880x500mm 39.8-inch                     | 1        | 1.61%   |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch             | 1        | 1.61%   |
| Hewlett-Packard V193 HWP3178 1366x768 410x230mm 18.5-inch            | 1        | 1.61%   |
| Hewlett-Packard P223 HPN3391 1920x1080 477x268mm 21.5-inch           | 1        | 1.61%   |
| Hewlett-Packard LCD Monitor L1908w 1440x900                          | 1        | 1.61%   |
| Hewlett-Packard LCD Monitor Compaq W185q 3286x1080                   | 1        | 1.61%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.61%   |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 1        | 1.61%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 1        | 1.61%   |
| Hewlett-Packard Compaq W1952a HWP3010 1366x768 410x230mm 18.5-inch   | 1        | 1.61%   |
| Hewlett-Packard All in One HWP410E 1366x768 410x230mm 18.5-inch      | 1        | 1.61%   |
| Hewlett-Packard 24uh HWP3221 1920x1080 531x299mm 24.0-inch           | 1        | 1.61%   |
| Haier HAIER HRE0030 1920x1080 708x398mm 32.0-inch                    | 1        | 1.61%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 1        | 1.61%   |
| Goldstar MP59G GSM5B33 1920x1080 480x270mm 21.7-inch                 | 1        | 1.61%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 1.61%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch              | 1        | 1.61%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 1        | 1.61%   |
| Goldstar FULL HD GSM5B9E 1920x1080 600x340mm 27.2-inch               | 1        | 1.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.61%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 1.61%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                    | 1        | 1.61%   |
| Dell E2211H DELA071 1920x1080 477x268mm 21.5-inch                    | 1        | 1.61%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 1        | 1.61%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                    | 1        | 1.61%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 1        | 1.61%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                    | 1        | 1.61%   |
| BenQ PC BNQ7816 1366x768 430x254mm 19.7-inch                         | 1        | 1.61%   |
| BenQ GL2450 BNQ78A4 1920x1080 531x298mm 24.0-inch                    | 1        | 1.61%   |
| AOC LCD Monitor 2260WG5 1920x1080                                    | 1        | 1.61%   |
| AOC LCD Monitor 2036 1600x900                                        | 1        | 1.61%   |
| AOC LCD Monitor 1970W                                                | 1        | 1.61%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 1        | 1.61%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 1        | 1.61%   |
| AOC 2769M AOC2769 1920x1080 598x336mm 27.0-inch                      | 1        | 1.61%   |
| AOC 2590G5 AOC2590 1920x1080 544x303mm 24.5-inch                     | 1        | 1.61%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 1        | 1.61%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 1        | 1.61%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 1        | 1.61%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                       | 1        | 1.61%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 408x255mm 18.9-inch | 1        | 1.61%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 1        | 1.61%   |
| Acer LCD Monitor S220HQL 1920x1080                                   | 1        | 1.61%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                    | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 22       | 37.29%  |
| 1366x768 (WXGA)   | 8        | 13.56%  |
| 1280x1024 (SXGA)  | 6        | 10.17%  |
| 3840x2160 (4K)    | 5        | 8.47%   |
| 1440x900 (WXGA+)  | 3        | 5.08%   |
| 3286x1080         | 2        | 3.39%   |
| 2560x1080         | 2        | 3.39%   |
| 1600x900 (HD+)    | 2        | 3.39%   |
| 1280x720 (HD)     | 2        | 3.39%   |
| Unknown           | 2        | 3.39%   |
| 2560x1440 (QHD)   | 1        | 1.69%   |
| 1920x1200 (WUXGA) | 1        | 1.69%   |
| 1360x768          | 1        | 1.69%   |
| 1280x960          | 1        | 1.69%   |
| 1024x768 (XGA)    | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 7        | 12.07%  |
| 23      | 7        | 12.07%  |
| Unknown | 7        | 12.07%  |
| 19      | 6        | 10.34%  |
| 18      | 6        | 10.34%  |
| 21      | 5        | 8.62%   |
| 17      | 4        | 6.9%    |
| 27      | 3        | 5.17%   |
| 72      | 2        | 3.45%   |
| 43      | 2        | 3.45%   |
| 34      | 2        | 3.45%   |
| 15      | 2        | 3.45%   |
| 84      | 1        | 1.72%   |
| 54      | 1        | 1.72%   |
| 39      | 1        | 1.72%   |
| 32      | 1        | 1.72%   |
| 12      | 1        | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 29.31%  |
| 401-500     | 15       | 25.86%  |
| Unknown     | 7        | 12.07%  |
| 301-350     | 5        | 8.62%   |
| 701-800     | 3        | 5.17%   |
| 351-400     | 3        | 5.17%   |
| 1501-2000   | 3        | 5.17%   |
| 901-1000    | 2        | 3.45%   |
| 801-900     | 1        | 1.72%   |
| 201-300     | 1        | 1.72%   |
| 1001-1500   | 1        | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 63.64%  |
| Unknown | 7        | 12.73%  |
| 5/4     | 5        | 9.09%   |
| 16/10   | 4        | 7.27%   |
| 4/3     | 2        | 3.64%   |
| 21/9    | 2        | 3.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 25.42%  |
| 141-150        | 9        | 15.25%  |
| 151-200        | 8        | 13.56%  |
| Unknown        | 7        | 11.86%  |
| More than 1000 | 4        | 6.78%   |
| 351-500        | 3        | 5.08%   |
| 301-350        | 3        | 5.08%   |
| 251-300        | 3        | 5.08%   |
| 501-1000       | 3        | 5.08%   |
| 71-80          | 1        | 1.69%   |
| 131-140        | 1        | 1.69%   |
| 111-120        | 1        | 1.69%   |
| 101-110        | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 57.89%  |
| 101-120 | 8        | 14.04%  |
| Unknown | 7        | 12.28%  |
| 1-50    | 6        | 10.53%  |
| 161-240 | 3        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 83.02%  |
| 2     | 8        | 15.09%  |
| 0     | 1        | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 51.39%  |
| Intel                 | 15       | 20.83%  |
| Qualcomm Atheros      | 7        | 9.72%   |
| Xiaomi                | 2        | 2.78%   |
| TP-Link               | 2        | 2.78%   |
| Ralink                | 2        | 2.78%   |
| Linksys               | 2        | 2.78%   |
| Broadcom              | 2        | 2.78%   |
| Ralink Technology     | 1        | 1.39%   |
| Nvidia                | 1        | 1.39%   |
| D-Link                | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 31       | 39.74%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2        | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 2.56%   |
| Intel Centrino Advanced-N 6235                                                                | 2        | 2.56%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 1.28%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 1.28%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 1        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 1.28%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.28%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.28%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 1.28%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1        | 1.28%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 1.28%   |
| Nvidia MCP79 Ethernet                                                                         | 1        | 1.28%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1        | 1.28%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 1.28%   |
| Intel Wireless-AC 9260                                                                        | 1        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 1.28%   |
| Intel I350 Gigabit Network Connection                                                         | 1        | 1.28%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.28%   |
| Intel Ethernet Controller I225-V                                                              | 1        | 1.28%   |
| Intel Ethernet Connection I217-LM                                                             | 1        | 1.28%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 1        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.28%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                                            | 1        | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 1        | 1.28%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                          | 1        | 1.28%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                | 1        | 1.28%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 1        | 1.28%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                                       | 1        | 1.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 26.09%  |
| Realtek Semiconductor | 5        | 21.74%  |
| Qualcomm Atheros      | 4        | 17.39%  |
| TP-Link               | 2        | 8.7%    |
| Ralink                | 2        | 8.7%    |
| Linksys               | 2        | 8.7%    |
| Ralink Technology     | 1        | 4.35%   |
| D-Link                | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 8.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 8.7%    |
| Intel Centrino Advanced-N 6235                                                                | 2        | 8.7%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 4.35%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 4.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4.35%   |
| Realtek 802.11ac NIC                                                                          | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 4.35%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1        | 4.35%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1        | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1        | 4.35%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1        | 4.35%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1        | 4.35%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1        | 4.35%   |
| Intel Wireless-AC 9260                                                                        | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 4.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 4.35%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 36       | 66.67%  |
| Intel                 | 10       | 18.52%  |
| Qualcomm Atheros      | 3        | 5.56%   |
| Xiaomi                | 2        | 3.7%    |
| Broadcom              | 2        | 3.7%    |
| Nvidia                | 1        | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 56.36%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.64%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.82%   |
| Nvidia MCP79 Ethernet                                             | 1        | 1.82%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.82%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1        | 1.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.82%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.82%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.82%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 51       | 70.83%  |
| WiFi     | 21       | 29.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 74.58%  |
| WiFi     | 15       | 25.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 61.54%  |
| 2     | 20       | 38.46%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 42.86%  |
| Cambridge Silicon Radio | 5        | 35.71%  |
| ASUSTek Computer        | 2        | 14.29%  |
| Broadcom                | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 5        | 35.71%  |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 7.14%   |
| Intel AX201 Bluetooth                                        | 1        | 7.14%   |
| Intel AX200 Bluetooth                                        | 1        | 7.14%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 7.14%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 33       | 41.25%  |
| Nvidia                  | 21       | 26.25%  |
| AMD                     | 19       | 23.75%  |
| Realtek Semiconductor   | 1        | 1.25%   |
| Logitech                | 1        | 1.25%   |
| GN Netcom               | 1        | 1.25%   |
| Corsair                 | 1        | 1.25%   |
| C-Media Electronics     | 1        | 1.25%   |
| BEHRINGER International | 1        | 1.25%   |
| Argosy research         | 1        | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 9.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 7.53%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 7.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 5.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 5.38%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 4.3%    |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 3.23%   |
| Nvidia High Definition Audio Controller                                           | 3        | 3.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 3.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 3.23%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 2.15%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 2.15%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 2.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 2.15%   |
| Realtek Semiconductor TX-Hifi Type_C Audio                                        | 1        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 1.08%   |
| Nvidia MCP79 High Definition Audio                                                | 1        | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 1.08%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 1.08%   |
| Logitech AudioHub Speaker                                                         | 1        | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.08%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 1        | 1.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.08%   |
| GN Netcom Jabra EVOLVE LINK MS                                                    | 1        | 1.08%   |
| Corsair VIRTUOSO USB Gaming Headset                                               | 1        | 1.08%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 1        | 1.08%   |
| BEHRINGER International UMC202HD 192k                                             | 1        | 1.08%   |
| Argosy research Argosy Multimedia audio controller                                | 1        | 1.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1        | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.08%   |
| AMD FCH Azalia Controller                                                         | 1        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 28.21%  |
| Micron Technology   | 8        | 20.51%  |
| SK Hynix            | 5        | 12.82%  |
| Samsung Electronics | 3        | 7.69%   |
| Corsair             | 3        | 7.69%   |
| G.Skill             | 2        | 5.13%   |
| Crucial             | 2        | 5.13%   |
| A-DATA Technology   | 2        | 5.13%   |
| Unknown             | 1        | 2.56%   |
| Patriot             | 1        | 2.56%   |
| Kimtigo             | 1        | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 5        | 11.36%  |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s     | 3        | 6.82%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s      | 2        | 4.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1        | 2.27%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1        | 2.27%   |
| SK Hynix RAM Module 16GB DIMM DDR4 2667MT/s               | 1        | 2.27%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s   | 1        | 2.27%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s   | 1        | 2.27%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 2.27%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 2.27%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1        | 2.27%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 2.27%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s       | 1        | 2.27%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s      | 1        | 2.27%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s           | 1        | 2.27%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s  | 1        | 2.27%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 1        | 2.27%   |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM 1333MT/s           | 1        | 2.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 2.27%   |
| Kingston RAM KHX2666C15/16G 16GB DIMM DDR4 2666MT/s       | 1        | 2.27%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 2.27%   |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2400MT/s    | 1        | 2.27%   |
| Kingston RAM 99U5403-067.A00LF 4096MB DIMM DDR3 1600MT/s  | 1        | 2.27%   |
| Kingston RAM 99U5403-050.A00 F 4GB DIMM DDR3 667MT/s      | 1        | 2.27%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 2.27%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s      | 1        | 2.27%   |
| Kingston RAM 9905402-413.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 2.27%   |
| Kimtigo RAM KTR1333U4G 4096MB DIMM DDR3 1333MT/s          | 1        | 2.27%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s    | 1        | 2.27%   |
| G.Skill RAM F4-3200C16-8GFX 8GB DIMM DDR4 3200MT/s        | 1        | 2.27%   |
| Crucial RAM CT4G4DFS824A.C8FBD1 4096MB DIMM DDR4 2400MT/s | 1        | 2.27%   |
| Crucial RAM BLS8G4D240FSE.16FBD 8GB DIMM DDR4 2400MT/s    | 1        | 2.27%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 2.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.27%   |
| Corsair RAM CMD16GX4M2B3000C15 8GB DIMM DDR4 3100MT/s     | 1        | 2.27%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s               | 1        | 2.27%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s              | 1        | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 15       | 50%     |
| DDR3  | 12       | 40%     |
| SDRAM | 2        | 6.67%   |
| DDR2  | 1        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 25       | 89.29%  |
| SODIMM | 3        | 10.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 12       | 38.71%  |
| 8192  | 10       | 32.26%  |
| 2048  | 5        | 16.13%  |
| 16384 | 3        | 9.68%   |
| 32768 | 1        | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 30.56%  |
| 2667  | 4        | 11.11%  |
| 2400  | 3        | 8.33%   |
| 1333  | 3        | 8.33%   |
| 3600  | 2        | 5.56%   |
| 3466  | 2        | 5.56%   |
| 3200  | 2        | 5.56%   |
| 2933  | 2        | 5.56%   |
| 667   | 2        | 5.56%   |
| 3100  | 1        | 2.78%   |
| 2934  | 1        | 2.78%   |
| 2800  | 1        | 2.78%   |
| 2666  | 1        | 2.78%   |
| 1800  | 1        | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 50%     |
| Canon           | 2        | 33.33%  |
| Seiko Epson     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Seiko Epson L3110 Series | 1        | 16.67%  |
| HP DeskJet 2600 series   | 1        | 16.67%  |
| HP DeskJet 2130 series   | 1        | 16.67%  |
| HP Deskjet 2050 J510     | 1        | 16.67%  |
| Canon G2000 series       | 1        | 16.67%  |
| Canon E400 series        | 1        | 16.67%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 5        | 35.71%  |
| Microsoft               | 2        | 14.29%  |
| Z-Star Microelectronics | 1        | 7.14%   |
| Philips (or NXP)        | 1        | 7.14%   |
| Microdia                | 1        | 7.14%   |
| Huawei Technologies     | 1        | 7.14%   |
| Chicony Electronics     | 1        | 7.14%   |
| Aveo Technology         | 1        | 7.14%   |
| Arkmicro Technologies   | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 3        | 21.43%  |
| Microsoft LifeCam HD-3000             | 2        | 14.29%  |
| Z-Star Vimicro USB Camera (Altair)    | 1        | 7.14%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 7.14%   |
| Microdia USB 2.0 Camera               | 1        | 7.14%   |
| Logitech Webcam Pro 9000              | 1        | 7.14%   |
| Logitech HD Pro Webcam C920           | 1        | 7.14%   |
| Huawei UVC Camera                     | 1        | 7.14%   |
| Chicony HP High Definition 1MP Webcam | 1        | 7.14%   |
| Aveo USB2.0 UVC PC Camera             | 1        | 7.14%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 7.14%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| OmniKey                    | 1        | 50%     |
| Athena Smartcard Solutions | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121              | 1        | 50%     |
| Athena Smartcard Solutions ASEDrive CCID | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 79.25%  |
| 1     | 8        | 15.09%  |
| 3     | 2        | 3.77%   |
| 2     | 1        | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 33.33%  |
| Graphics card            | 3        | 20%     |
| Communication controller | 3        | 20%     |
| Chipcard                 | 2        | 13.33%  |
| Sound                    | 1        | 6.67%   |
| Network                  | 1        | 6.67%   |
