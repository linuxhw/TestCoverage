Deepin - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Deepin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| Dell          | 07N90W A02                  | [43a5aec999](https://linux-hardware.org/?probe=43a5aec999) | Dec 07, 2021 |
| ECS           | H81H3-M4                    | [cdaf4b1031](https://linux-hardware.org/?probe=cdaf4b1031) | Dec 07, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [a428f57f6a](https://linux-hardware.org/?probe=a428f57f6a) | Sep 17, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Toshiba       | STI 005492G                 | [d7fe511a9e](https://linux-hardware.org/?probe=d7fe511a9e) | Jul 19, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| ECS           | H81H3-M4                    | [838f10c576](https://linux-hardware.org/?probe=838f10c576) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | [bfc9a4d537](https://linux-hardware.org/?probe=bfc9a4d537) | Jun 25, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Toshiba       | STI 005492G                 | [e28291b9ed](https://linux-hardware.org/?probe=e28291b9ed) | Jun 13, 2021 |
| MSI           | H81I                        | [a0f0f9e7e8](https://linux-hardware.org/?probe=a0f0f9e7e8) | May 06, 2021 |
| Huanan        | X99-8M-F V1.1               | [13daa2d4a6](https://linux-hardware.org/?probe=13daa2d4a6) | Apr 23, 2021 |
| ASUSTek       | P8H61-MX                    | [9212747e6a](https://linux-hardware.org/?probe=9212747e6a) | Apr 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [e6db1c79cc](https://linux-hardware.org/?probe=e6db1c79cc) | Mar 25, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [edb786e43a](https://linux-hardware.org/?probe=edb786e43a) | Mar 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [1db414e1cd](https://linux-hardware.org/?probe=1db414e1cd) | Mar 21, 2021 |
| Gigabyte      | H81M-D2V                    | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| Gigabyte      | H81M-D2V                    | [3fbfb29382](https://linux-hardware.org/?probe=3fbfb29382) | Mar 14, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [b165cd04ce](https://linux-hardware.org/?probe=b165cd04ce) | Feb 25, 2021 |
| Dell          | 0KWVT8 A00                  | [56f1d17280](https://linux-hardware.org/?probe=56f1d17280) | Feb 04, 2021 |
| Dell          | 00V62H A00                  | [863c1d64fe](https://linux-hardware.org/?probe=863c1d64fe) | Jan 23, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [842703dc6b](https://linux-hardware.org/?probe=842703dc6b) | Jan 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [5b9e365258](https://linux-hardware.org/?probe=5b9e365258) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | H81M-D2V                    | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Foxconn       | 2ADA                        | [2c76ab07eb](https://linux-hardware.org/?probe=2c76ab07eb) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0b46341e31](https://linux-hardware.org/?probe=0b46341e31) | Nov 07, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [a4fa363ca9](https://linux-hardware.org/?probe=a4fa363ca9) | Oct 29, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [181ccd5686](https://linux-hardware.org/?probe=181ccd5686) | Oct 10, 2020 |
| Toshiba       | STI 013442                  | [25aa1737df](https://linux-hardware.org/?probe=25aa1737df) | Oct 02, 2020 |
| Toshiba       | STI 013442                  | [325dccb021](https://linux-hardware.org/?probe=325dccb021) | Oct 01, 2020 |
| Toshiba       | STI 013442                  | [d878c17ac5](https://linux-hardware.org/?probe=d878c17ac5) | Oct 01, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [d5c18b2ad2](https://linux-hardware.org/?probe=d5c18b2ad2) | Sep 27, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [27f0cbcbfa](https://linux-hardware.org/?probe=27f0cbcbfa) | Sep 27, 2020 |
| ASUSTek       | P8H77-M PRO                 | [7318b0893d](https://linux-hardware.org/?probe=7318b0893d) | Sep 22, 2020 |
| Gigabyte      | H81M-D2V                    | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| Gigabyte      | Z77-DS3H                    | [d7f43611eb](https://linux-hardware.org/?probe=d7f43611eb) | Sep 13, 2020 |
| Foxconn       | 2ADA                        | [f1eb818ac5](https://linux-hardware.org/?probe=f1eb818ac5) | Sep 04, 2020 |
| HP            | 81B4                        | [9e3aa00a36](https://linux-hardware.org/?probe=9e3aa00a36) | Aug 21, 2020 |
| Foxconn       | 2ADA                        | [f93d4fa401](https://linux-hardware.org/?probe=f93d4fa401) | Jul 30, 2020 |
| HP            | 81B4                        | [03c849fcd2](https://linux-hardware.org/?probe=03c849fcd2) | Jul 26, 2020 |
| Foxconn       | 2ADA                        | [035b1fd159](https://linux-hardware.org/?probe=035b1fd159) | Jul 24, 2020 |
| ASUSTek       | AM1M-A/BR                   | [dafd042867](https://linux-hardware.org/?probe=dafd042867) | Jul 22, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| Positivo      | POS-PQ45AU                  | [056dd1ec51](https://linux-hardware.org/?probe=056dd1ec51) | Jul 15, 2020 |
| ASUSTek       | H110I-PLUS                  | [116754d157](https://linux-hardware.org/?probe=116754d157) | Jul 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [4a0dcf77f1](https://linux-hardware.org/?probe=4a0dcf77f1) | Jun 24, 2020 |
| MSI           | P67A-GD65                   | [c0df14bdee](https://linux-hardware.org/?probe=c0df14bdee) | Jun 22, 2020 |
| ASRock        | Z77 Extreme4                | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| Gigabyte      | 990XA-UD3                   | [cc7c6da435](https://linux-hardware.org/?probe=cc7c6da435) | May 19, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b8f32a998c](https://linux-hardware.org/?probe=b8f32a998c) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASRock        | J5005-ITX                   | [94c7463689](https://linux-hardware.org/?probe=94c7463689) | Mar 16, 2020 |
| ASRock        | J5005-ITX                   | [12e2c41514](https://linux-hardware.org/?probe=12e2c41514) | Mar 08, 2020 |
| ASRock        | J5005-ITX                   | [77ca797332](https://linux-hardware.org/?probe=77ca797332) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | [624ee7e0ec](https://linux-hardware.org/?probe=624ee7e0ec) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | [be5d91522e](https://linux-hardware.org/?probe=be5d91522e) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | [455989807e](https://linux-hardware.org/?probe=455989807e) | Mar 04, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8e114bee8](https://linux-hardware.org/?probe=c8e114bee8) | Feb 14, 2020 |
| Medion        | MS-7728                     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASUSTek       | Z170-AR                     | [cd4ef749f3](https://linux-hardware.org/?probe=cd4ef749f3) | Feb 03, 2020 |
| ASUSTek       | Z170-AR                     | [3c9887587e](https://linux-hardware.org/?probe=3c9887587e) | Feb 03, 2020 |
| ASUSTek       | Z170-AR                     | [74934afe78](https://linux-hardware.org/?probe=74934afe78) | Feb 03, 2020 |
| ASRock        | N68-S3 FX                   | [ddf39244d2](https://linux-hardware.org/?probe=ddf39244d2) | Dec 24, 2019 |
| ASRock        | N68-S3 FX                   | [5f2a15fa54](https://linux-hardware.org/?probe=5f2a15fa54) | Dec 24, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| ASUSTek       | Z97-A                       | [1c2f2dd0b9](https://linux-hardware.org/?probe=1c2f2dd0b9) | Aug 06, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [834659c2b7](https://linux-hardware.org/?probe=834659c2b7) | Jun 18, 2019 |
| ASUSTek       | P8H61-M LX2 R2.0            | [883fb20fad](https://linux-hardware.org/?probe=883fb20fad) | Jun 18, 2019 |
| ASUSTek       | P5Q-E                       | [f16456d590](https://linux-hardware.org/?probe=f16456d590) | Mar 28, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [dacef5f8e5](https://linux-hardware.org/?probe=dacef5f8e5) | Mar 28, 2019 |
| Positivo      | POS-EINM70CS POSITIVO       | [296a0cde2c](https://linux-hardware.org/?probe=296a0cde2c) | Mar 27, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Gigabyte      | H110M-H-CF                  | [730a46747b](https://linux-hardware.org/?probe=730a46747b) | Nov 07, 2018 |
| Gigabyte      | H110M-H-CF                  | [96835c9cef](https://linux-hardware.org/?probe=96835c9cef) | Oct 30, 2018 |
| Gigabyte      | H110M-H-CF                  | [0e7a915eb4](https://linux-hardware.org/?probe=0e7a915eb4) | Oct 30, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.70-amd64-desktop      | 7        | 13.21%  |
| 4.15.0-30deepin-generic   | 7        | 13.21%  |
| 4.15.0-29deepin-generic   | 7        | 13.21%  |
| 5.4.50-amd64-desktop      | 6        | 11.32%  |
| 5.3.0-3-amd64             | 6        | 11.32%  |
| 5.10.36-amd64-desktop     | 3        | 5.66%   |
| 5.7.7-amd64-desktop       | 2        | 3.77%   |
| 5.10.60-amd64-desktop     | 2        | 3.77%   |
| 5.10.29-amd64-desktop     | 2        | 3.77%   |
| 5.10.18-amd64-desktop     | 2        | 3.77%   |
| 4.19.0-amd64-desktop      | 2        | 3.77%   |
| 5.8.14-amd64-desktop      | 1        | 1.89%   |
| 5.5.4-xanmod3             | 1        | 1.89%   |
| 5.14.0-rc3-amd64-desktop  | 1        | 1.89%   |
| 5.10.50-amd64-desktop     | 1        | 1.89%   |
| 5.10.5-amd64-desktop+     | 1        | 1.89%   |
| 4.19.90-1.lns7.2.mips64el | 1        | 1.89%   |
| 4.19.0-5-amd64            | 1        | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 14       | 26.42%  |
| 5.4.70  | 7        | 13.21%  |
| 5.4.50  | 6        | 11.32%  |
| 5.3.0   | 6        | 11.32%  |
| 5.10.36 | 3        | 5.66%   |
| 4.19.0  | 3        | 5.66%   |
| 5.7.7   | 2        | 3.77%   |
| 5.10.60 | 2        | 3.77%   |
| 5.10.29 | 2        | 3.77%   |
| 5.10.18 | 2        | 3.77%   |
| 5.8.14  | 1        | 1.89%   |
| 5.5.4   | 1        | 1.89%   |
| 5.14.0  | 1        | 1.89%   |
| 5.10.50 | 1        | 1.89%   |
| 5.10.5  | 1        | 1.89%   |
| 4.19.90 | 1        | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 14       | 27.45%  |
| 5.4     | 12       | 23.53%  |
| 5.10    | 10       | 19.61%  |
| 5.3     | 6        | 11.76%  |
| 4.19    | 4        | 7.84%   |
| 5.7     | 2        | 3.92%   |
| 5.8     | 1        | 1.96%   |
| 5.5     | 1        | 1.96%   |
| 5.14    | 1        | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 98%     |
| mips64 | 1        | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 42       | 82.35%  |
| Unknown | 8        | 15.69%  |
| MATE    | 1        | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 49       | 98%     |
| Tty  | 1        | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 58%     |
| TDM     | 11       | 22%     |
| LightDM | 10       | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 21.57%  |
| pt_BR   | 10       | 19.61%  |
| Unknown | 8        | 15.69%  |
| zh_CN   | 7        | 13.73%  |
| es_ES   | 7        | 13.73%  |
| de_DE   | 3        | 5.88%   |
| ru_RU   | 1        | 1.96%   |
| lt_LT   | 1        | 1.96%   |
| it_IT   | 1        | 1.96%   |
| id_ID   | 1        | 1.96%   |
| fr_FR   | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 62%     |
| EFI  | 19       | 38%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 92%     |
| Unknown | 4        | 8%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 51.92%  |
| GPT     | 18       | 34.62%  |
| MBR     | 7        | 13.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 76.47%  |
| Yes       | 12       | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 80.39%  |
| Yes       | 10       | 19.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 12       | 24%     |
| Gigabyte Technology        | 9        | 18%     |
| TSINGHUA TONGFANG COMPUTER | 4        | 8%      |
| Dell                       | 4        | 8%      |
| ASRock                     | 4        | 8%      |
| MSI                        | 3        | 6%      |
| Semp Toshiba               | 2        | 4%      |
| Positivo                   | 2        | 4%      |
| Lenovo                     | 2        | 4%      |
| ECS                        | 2        | 4%      |
| Medion                     | 1        | 2%      |
| Loongson                   | 1        | 2%      |
| Huanan                     | 1        | 2%      |
| Hewlett-Packard            | 1        | 2%      |
| Foxconn                    | 1        | 2%      |
| AMD                        | 1        | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500               | 4        | 8%      |
| Semp Toshiba STI                              | 2        | 4%      |
| ECS H81H3-M4                                  | 2        | 4%      |
| ASUS All Series                               | 2        | 4%      |
| Positivo POS-PQ45AU                           | 1        | 2%      |
| Positivo POS-EINM70CS                         | 1        | 2%      |
| MSI MS-7C83                                   | 1        | 2%      |
| MSI MS-7851                                   | 1        | 2%      |
| MSI MS-7681                                   | 1        | 2%      |
| Medion MS-7728                                | 1        | 2%      |
| Loongson Loongson-LS3A3000-7A1000-1w-V1.2-Dev | 1        | 2%      |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW      | 1        | 2%      |
| Lenovo ThinkCentre M82 2929AJ2                | 1        | 2%      |
| Huanan X99-8M-F V1.1                          | 1        | 2%      |
| HP 260-P020il                                 | 1        | 2%      |
| Gigabyte Z77-DS3H                             | 1        | 2%      |
| Gigabyte Z170X-Gaming 7                       | 1        | 2%      |
| Gigabyte H81M-D2V                             | 1        | 2%      |
| Gigabyte H110M-H                              | 1        | 2%      |
| Gigabyte GA-78LMT-USB3                        | 1        | 2%      |
| Gigabyte B550M DS3H                           | 1        | 2%      |
| Gigabyte B365M D3H                            | 1        | 2%      |
| Gigabyte B360M AORUS Gaming 3                 | 1        | 2%      |
| Gigabyte 990XA-UD3                            | 1        | 2%      |
| Foxconn p7-1430br                             | 1        | 2%      |
| Dell Vostro 230                               | 1        | 2%      |
| Dell OptiPlex 9020                            | 1        | 2%      |
| Dell OptiPlex 760                             | 1        | 2%      |
| Dell Inspiron One 2020                        | 1        | 2%      |
| ASUS PRIME B450M-GAMING/BR                    | 1        | 2%      |
| ASUS PRIME B350-PLUS                          | 1        | 2%      |
| ASUS PRIME A320M-K                            | 1        | 2%      |
| ASUS P8H77-M PRO                              | 1        | 2%      |
| ASUS P8H61-MX                                 | 1        | 2%      |
| ASUS P8H61-M LX2 R2.0                         | 1        | 2%      |
| ASUS P5Q-E                                    | 1        | 2%      |
| ASUS P5G41T-M LX2/BR                          | 1        | 2%      |
| ASUS M5A78L-M/USB3                            | 1        | 2%      |
| ASUS H110I-PLUS                               | 1        | 2%      |
| ASRock Z77 Extreme4                           | 1        | 2%      |
| ASRock Z68 Extreme7 Gen3                      | 1        | 2%      |
| ASRock N68-S3 FX                              | 1        | 2%      |
| ASRock J5005-ITX                              | 1        | 2%      |
| AMD X64                                       | 1        | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                          | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500               | 4        | 8%      |
| ASUS PRIME                                    | 3        | 6%      |
| Semp Toshiba STI                              | 2        | 4%      |
| Lenovo ThinkCentre                            | 2        | 4%      |
| ECS H81H3-M4                                  | 2        | 4%      |
| Dell OptiPlex                                 | 2        | 4%      |
| ASUS All                                      | 2        | 4%      |
| Positivo POS-PQ45AU                           | 1        | 2%      |
| Positivo POS-EINM70CS                         | 1        | 2%      |
| MSI MS-7C83                                   | 1        | 2%      |
| MSI MS-7851                                   | 1        | 2%      |
| MSI MS-7681                                   | 1        | 2%      |
| Medion MS-7728                                | 1        | 2%      |
| Loongson Loongson-LS3A3000-7A1000-1w-V1.2-Dev | 1        | 2%      |
| Huanan X99-8M-F                               | 1        | 2%      |
| HP 260-P020il                                 | 1        | 2%      |
| Gigabyte Z77-DS3H                             | 1        | 2%      |
| Gigabyte Z170X-Gaming                         | 1        | 2%      |
| Gigabyte H81M-D2V                             | 1        | 2%      |
| Gigabyte H110M-H                              | 1        | 2%      |
| Gigabyte GA-78LMT-USB3                        | 1        | 2%      |
| Gigabyte B550M                                | 1        | 2%      |
| Gigabyte B365M                                | 1        | 2%      |
| Gigabyte B360M                                | 1        | 2%      |
| Gigabyte 990XA-UD3                            | 1        | 2%      |
| Foxconn p7-1430br                             | 1        | 2%      |
| Dell Vostro                                   | 1        | 2%      |
| Dell Inspiron                                 | 1        | 2%      |
| ASUS P8H77-M                                  | 1        | 2%      |
| ASUS P8H61-MX                                 | 1        | 2%      |
| ASUS P8H61-M                                  | 1        | 2%      |
| ASUS P5Q-E                                    | 1        | 2%      |
| ASUS P5G41T-M                                 | 1        | 2%      |
| ASUS M5A78L-M                                 | 1        | 2%      |
| ASUS H110I-PLUS                               | 1        | 2%      |
| ASRock Z77                                    | 1        | 2%      |
| ASRock Z68                                    | 1        | 2%      |
| ASRock N68-S3                                 | 1        | 2%      |
| ASRock J5005-ITX                              | 1        | 2%      |
| AMD X64                                       | 1        | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 16%     |
| 2014 | 8        | 16%     |
| 2013 | 8        | 16%     |
| 2018 | 6        | 12%     |
| 2012 | 6        | 12%     |
| 2021 | 3        | 6%      |
| 2016 | 3        | 6%      |
| 2011 | 2        | 4%      |
| 2010 | 2        | 4%      |
| 2009 | 2        | 4%      |
| 2019 | 1        | 2%      |
| 2015 | 1        | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 50       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 40%     |
| 8.01-16.0   | 13       | 26%     |
| 4.01-8.0    | 9        | 18%     |
| 3.01-4.0    | 6        | 12%     |
| 64.01-256.0 | 1        | 2%      |
| 1.01-2.0    | 1        | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 16       | 28.07%  |
| 4.01-8.0  | 15       | 26.32%  |
| 2.01-3.0  | 12       | 21.05%  |
| 3.01-4.0  | 9        | 15.79%  |
| 0.51-1.0  | 4        | 7.02%   |
| 8.01-16.0 | 1        | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 39.22%  |
| 1      | 20       | 39.22%  |
| 4      | 6        | 11.76%  |
| 3      | 4        | 7.84%   |
| 5      | 1        | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 61.54%  |
| Yes       | 20       | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 72%     |
| Yes       | 14       | 28%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 72%     |
| Yes       | 14       | 28%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Brazil      | 15       | 30%     |
| China       | 8        | 16%     |
| USA         | 4        | 8%      |
| Panama      | 2        | 4%      |
| Mexico      | 2        | 4%      |
| Germany     | 2        | 4%      |
| Argentina   | 2        | 4%      |
| Ukraine     | 1        | 2%      |
| Spain       | 1        | 2%      |
| Russia      | 1        | 2%      |
| Romania     | 1        | 2%      |
| Poland      | 1        | 2%      |
| New Zealand | 1        | 2%      |
| Namibia     | 1        | 2%      |
| Lithuania   | 1        | 2%      |
| Italy       | 1        | 2%      |
| Indonesia   | 1        | 2%      |
| India       | 1        | 2%      |
| Colombia    | 1        | 2%      |
| Belgium     | 1        | 2%      |
| Bangladesh  | 1        | 2%      |
| Austria     | 1        | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Beijing                 | 5        | 9.8%    |
| São Paulo              | 2        | 3.92%   |
| Rio de Janeiro          | 2        | 3.92%   |
| David                   | 2        | 3.92%   |
| Wuhan                   | 1        | 1.96%   |
| Windhoek                | 1        | 1.96%   |
| Vilnius                 | 1        | 1.96%   |
| Vienna                  | 1        | 1.96%   |
| São Bernardo do Campo  | 1        | 1.96%   |
| Surakarta               | 1        | 1.96%   |
| St Petersburg           | 1        | 1.96%   |
| Socorro                 | 1        | 1.96%   |
| Seesen                  | 1        | 1.96%   |
| S??o Paulo              | 1        | 1.96%   |
| San Francisco           | 1        | 1.96%   |
| Rzeszotary              | 1        | 1.96%   |
| Rome                    | 1        | 1.96%   |
| Para de Minas           | 1        | 1.96%   |
| Palo Alto               | 1        | 1.96%   |
| Niterói                | 1        | 1.96%   |
| Naucalpan               | 1        | 1.96%   |
| Nanjing                 | 1        | 1.96%   |
| Namur                   | 1        | 1.96%   |
| Mesa                    | 1        | 1.96%   |
| Medell?�n               | 1        | 1.96%   |
| Marília                | 1        | 1.96%   |
| Lviv                    | 1        | 1.96%   |
| Liège                  | 1        | 1.96%   |
| Leipzig                 | 1        | 1.96%   |
| Jaboatao dos Guararapes | 1        | 1.96%   |
| Grand Bourg             | 1        | 1.96%   |
| Getxo                   | 1        | 1.96%   |
| Dhaka                   | 1        | 1.96%   |
| Cypress Hills           | 1        | 1.96%   |
| Contagem                | 1        | 1.96%   |
| Cluj-Napoca             | 1        | 1.96%   |
| Chennai                 | 1        | 1.96%   |
| Campina Grande          | 1        | 1.96%   |
| Campeche                | 1        | 1.96%   |
| Brasília               | 1        | 1.96%   |
| Brandsen                | 1        | 1.96%   |
| Barueri                 | 1        | 1.96%   |
| Baixucun                | 1        | 1.96%   |
| Auckland                | 1        | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 17       | 22     | 18.28%  |
| Seagate               | 15       | 17     | 16.13%  |
| SanDisk               | 7        | 12     | 7.53%   |
| Toshiba               | 6        | 7      | 6.45%   |
| Samsung Electronics   | 6        | 7      | 6.45%   |
| Kingston              | 5        | 9      | 5.38%   |
| China                 | 4        | 4      | 4.3%    |
| A-DATA Technology     | 4        | 5      | 4.3%    |
| Hitachi               | 3        | 3      | 3.23%   |
| Crucial               | 3        | 4      | 3.23%   |
| SPCC                  | 2        | 2      | 2.15%   |
| MAXTOR                | 2        | 4      | 2.15%   |
| Hewlett-Packard       | 2        | 2      | 2.15%   |
| FORESEE               | 2        | 2      | 2.15%   |
| Vaseky                | 1        | 1      | 1.08%   |
| Unknown               | 1        | 2      | 1.08%   |
| Silicon Motion        | 1        | 1      | 1.08%   |
| Realtek Semiconductor | 1        | 1      | 1.08%   |
| Phison                | 1        | 1      | 1.08%   |
| Mushkin               | 1        | 1      | 1.08%   |
| Maxtor 6              | 1        | 1      | 1.08%   |
| LaCie                 | 1        | 2      | 1.08%   |
| KingDian              | 1        | 1      | 1.08%   |
| KINGBANK              | 1        | 1      | 1.08%   |
| JMicron               | 1        | 1      | 1.08%   |
| Intenso               | 1        | 1      | 1.08%   |
| Gigabyte Technology   | 1        | 1      | 1.08%   |
| Beijing Starblaze     | 1        | 1      | 1.08%   |
| Apacer                | 1        | 3      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB      | 3        | 3.03%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 2.02%   |
| Seagate ST1000DM003-1SB102 1TB      | 2        | 2.02%   |
| SanDisk SDSSDH3512G 512GB           | 2        | 2.02%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 2.02%   |
| FORESEE P900F256GBH                 | 2        | 2.02%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 1.01%   |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 1.01%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1        | 1.01%   |
| WDC WD80 0BEVE-11UYT0 80GB          | 1        | 1.01%   |
| WDC WD7500BPKX-22HPJT0 752GB        | 1        | 1.01%   |
| WDC WD6400AAKS-75A7B0 640GB         | 1        | 1.01%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1.01%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1        | 1.01%   |
| WDC WD5000AAJS-57TKA0 500GB         | 1        | 1.01%   |
| WDC WD3200AAKS-00VYA0 320GB         | 1        | 1.01%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1        | 1.01%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1.01%   |
| WDC WD1600AAJS-00L7A0 160GB         | 1        | 1.01%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1        | 1.01%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1.01%   |
| WDC WD10EFRX-68FYTN0 1TB            | 1        | 1.01%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1.01%   |
| Vaseky V800/256G 256GB SSD          | 1        | 1.01%   |
| Unknown SD/MMC/MS PRO 7GB           | 1        | 1.01%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1.01%   |
| Toshiba MQ01ABD075 752GB            | 1        | 1.01%   |
| Toshiba DT01ACA200 2TB              | 1        | 1.01%   |
| Toshiba DT01ACA100 LENOVO 1TB       | 1        | 1.01%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.01%   |
| Toshiba DT01ACA050 500GB            | 1        | 1.01%   |
| SPCC Solid State Disk 512GB         | 1        | 1.01%   |
| SPCC Solid State Disk 120GB         | 1        | 1.01%   |
| Silicon Motion NVME SSD 128GB       | 1        | 1.01%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.01%   |
| Seagate ST3750528AS 752GB           | 1        | 1.01%   |
| Seagate ST3500418AS 500GB           | 1        | 1.01%   |
| Seagate ST3250312AS 250GB           | 1        | 1.01%   |
| Seagate ST31000524AS 1TB            | 1        | 1.01%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 1.01%   |
| Seagate ST1500DL003-9VT16L 1TB      | 1        | 1.01%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1.01%   |
| Seagate ST1000DL002-9TT153 1TB      | 1        | 1.01%   |
| SanDisk SSD PLUS 240GB              | 1        | 1.01%   |
| SanDisk SSD PLUS 120GB              | 1        | 1.01%   |
| SanDisk SDSSDHP128G 128GB           | 1        | 1.01%   |
| SanDisk SDSSDH3 500G                | 1        | 1.01%   |
| SanDisk SDSSDA240G 240GB            | 1        | 1.01%   |
| SanDisk SDSSDA120G 120GB            | 1        | 1.01%   |
| SanDisk SD7SB6S-256G-1006 256GB SSD | 1        | 1.01%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.01%   |
| Samsung SSD 850 PRO 256GB           | 1        | 1.01%   |
| Samsung SSD 850 EVO 500GB           | 1        | 1.01%   |
| Samsung SSD 850 EVO 120GB           | 1        | 1.01%   |
| Samsung HD502HJ 500GB               | 1        | 1.01%   |
| Samsung HD250HJ 250GB               | 1        | 1.01%   |
| Realtek NVMe SSD Drive 256GB        | 1        | 1.01%   |
| Phison ESO256GMFCH-E3C-2 256GB      | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 33.33%  |
| WDC                 | 14       | 19     | 31.11%  |
| Toshiba             | 6        | 7      | 13.33%  |
| Hitachi             | 3        | 3      | 6.67%   |
| Samsung Electronics | 2        | 2      | 4.44%   |
| MAXTOR              | 2        | 4      | 4.44%   |
| Unknown             | 1        | 2      | 2.22%   |
| Maxtor 6            | 1        | 1      | 2.22%   |
| Hewlett-Packard     | 1        | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 7        | 12     | 18.42%  |
| Kingston            | 5        | 9      | 13.16%  |
| Samsung Electronics | 4        | 5      | 10.53%  |
| China               | 4        | 4      | 10.53%  |
| WDC                 | 3        | 3      | 7.89%   |
| Crucial             | 3        | 4      | 7.89%   |
| A-DATA Technology   | 3        | 4      | 7.89%   |
| SPCC                | 2        | 2      | 5.26%   |
| Vaseky              | 1        | 1      | 2.63%   |
| KingDian            | 1        | 1      | 2.63%   |
| KINGBANK            | 1        | 1      | 2.63%   |
| JMicron             | 1        | 1      | 2.63%   |
| Intenso             | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |
| Apacer              | 1        | 3      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 35       | 56     | 46.67%  |
| SSD     | 30       | 52     | 40%     |
| NVMe    | 9        | 9      | 12%     |
| Unknown | 1        | 2      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 103    | 79.03%  |
| NVMe | 9        | 9      | 14.52%  |
| SAS  | 4        | 7      | 6.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 70     | 55.88%  |
| 0.51-1.0   | 25       | 32     | 36.76%  |
| 1.01-2.0   | 5        | 6      | 7.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 15       | 29.41%  |
| 501-1000       | 11       | 21.57%  |
| 251-500        | 10       | 19.61%  |
| 101-250        | 7        | 13.73%  |
| 51-100         | 3        | 5.88%   |
| More than 3000 | 2        | 3.92%   |
| 2001-3000      | 2        | 3.92%   |
| Unknown        | 1        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 16       | 29.09%  |
| 501-1000  | 11       | 20%     |
| 21-50     | 8        | 14.55%  |
| 1-20      | 6        | 10.91%  |
| 51-100    | 5        | 9.09%   |
| 251-500   | 4        | 7.27%   |
| 1001-2000 | 3        | 5.45%   |
| 2001-3000 | 1        | 1.82%   |
| Unknown   | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 16.67%  |
| Seagate ST3750528AS 752GB          | 1        | 1      | 16.67%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 16.67%  |
| Seagate ST1000DL002-9TT153 1TB     | 1        | 1      | 16.67%  |
| Samsung Electronics HD502HJ 500GB  | 1        | 1      | 16.67%  |
| Samsung Electronics HD250HJ 250GB  | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HUA722010CLA330 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 29       | 68     | 47.54%  |
| Works    | 26       | 44     | 42.62%  |
| Malfunc  | 5        | 6      | 8.2%    |
| Failed   | 1        | 1      | 1.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 38       | 57.58%  |
| AMD                          | 10       | 15.15%  |
| ASMedia Technology           | 4        | 6.06%   |
| Marvell Technology Group     | 3        | 4.55%   |
| Silicon Motion               | 2        | 3.03%   |
| Shenzhen Longsys Electronics | 2        | 3.03%   |
| Phison Electronics           | 2        | 3.03%   |
| Realtek Semiconductor        | 1        | 1.52%   |
| Nvidia                       | 1        | 1.52%   |
| Loongson Technology          | 1        | 1.52%   |
| JMicron Technology           | 1        | 1.52%   |
| Beijing Starblaze Technology | 1        | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 6.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 6.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 6.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 5.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 5.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 5.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.8%    |
| Shenzhen Longsys Non-Volatile memory controller                                         | 2        | 2.53%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.53%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.27%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.27%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.27%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.27%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.27%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.27%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.27%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.27%   |
| Loongson SATA AHCI Controller                                                           | 1        | 1.27%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.27%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.27%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.27%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.27%   |
| Beijing Starblaze STAR1200C NVMe SSD                                                    | 1        | 1.27%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.27%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.27%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.27%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 65.08%  |
| IDE  | 12       | 19.05%  |
| NVMe | 8        | 12.7%   |
| RAID | 2        | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 38       | 76%     |
| AMD     | 11       | 22%     |
| Unknown | 1        | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 8%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 8%      |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 6%      |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 4%      |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 4%      |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 4%      |
| AMD FX-8320 Eight-Core Processor            | 2        | 4%      |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 2%      |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 2%      |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 2%      |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2%      |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 2%      |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2%      |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 2%      |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 2%      |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 2%      |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2%      |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2%      |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 2%      |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 2%      |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 2%      |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 2%      |
| Intel Core i3-3240T CPU @ 2.90GHz           | 1        | 2%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2%      |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 2%      |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1        | 2%      |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1        | 2%      |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2%      |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 2%      |
| AMD FX-6100 Six-Core Processor              | 1        | 2%      |
| AMD FX-4130 Quad-Core Processor             | 1        | 2%      |
| AMD C-60 APU with Radeon HD Graphics        | 1        | 2%      |
| AMD Athlon 5150 APU with Radeon R3          | 1        | 2%      |
| AMD A9-9820 Processor                       | 1        | 2%      |
|                                             | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 14       | 28%     |
| Intel Core i3           | 7        | 14%     |
| Intel Core i5           | 6        | 12%     |
| Intel Core 2 Duo        | 4        | 8%      |
| AMD FX                  | 4        | 8%      |
| Intel Celeron           | 3        | 6%      |
| AMD Ryzen 5             | 3        | 6%      |
| Other                   | 2        | 4%      |
| Intel Xeon              | 2        | 4%      |
| Intel Pentium Silver    | 1        | 2%      |
| Intel Pentium Dual-Core | 1        | 2%      |
| AMD Ryzen 3             | 1        | 2%      |
| AMD C-60                | 1        | 2%      |
| AMD Athlon              | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 52%     |
| 2      | 14       | 28%     |
| 6      | 5        | 10%     |
| 8      | 4        | 8%      |
| 3      | 1        | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 56%     |
| 1      | 22       | 44%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 45       | 90%     |
| Unknown        | 5        | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 31.37%  |
| 0x306a9    | 7        | 13.73%  |
| 0x306c3    | 6        | 11.76%  |
| 0x1067a    | 4        | 7.84%   |
| 0xa0655    | 2        | 3.92%   |
| 0x906e9    | 2        | 3.92%   |
| 0x206a7    | 2        | 3.92%   |
| 0xa0653    | 1        | 1.96%   |
| 0x906eb    | 1        | 1.96%   |
| 0x506e3    | 1        | 1.96%   |
| 0x306f2    | 1        | 1.96%   |
| 0x08701013 | 1        | 1.96%   |
| 0x08001138 | 1        | 1.96%   |
| 0x08001137 | 1        | 1.96%   |
| 0x07026101 | 1        | 1.96%   |
| 0x06000822 | 1        | 1.96%   |
| 0x06000629 | 1        | 1.96%   |
| 0x06000626 | 1        | 1.96%   |
| 0x0500010d | 1        | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 9        | 18%     |
| Haswell       | 7        | 14%     |
| Penryn        | 6        | 12%     |
| CometLake     | 5        | 10%     |
| KabyLake      | 4        | 8%      |
| Skylake       | 3        | 6%      |
| SandyBridge   | 3        | 6%      |
| Zen 2         | 2        | 4%      |
| Zen           | 2        | 4%      |
| Piledriver    | 2        | 4%      |
| Bulldozer     | 2        | 4%      |
| Unknown       | 2        | 4%      |
| Jaguar        | 1        | 2%      |
| Goldmont plus | 1        | 2%      |
| Bobcat        | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 21       | 39.62%  |
| AMD                 | 16       | 30.19%  |
| Intel               | 15       | 28.3%   |
| Loongson Technology | 1        | 1.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.7%    |
| Intel HD Graphics 630                                                       | 2        | 3.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.7%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.85%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.85%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.85%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.85%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.85%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.85%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.85%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.85%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.85%   |
| Loongson Technology Vivante GPU (Graphics Processing Unit)                  | 1        | 1.85%   |
| Loongson Technology DC (Display Controller)                                 | 1        | 1.85%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.85%   |
| AMD Wrestler [Radeon HD 6290]                                               | 1        | 1.85%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                     | 1        | 1.85%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.85%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 1.85%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.85%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 1        | 1.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.85%   |
| AMD Kryptos [Radeon RX 350]                                                 | 1        | 1.85%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                     | 1        | 1.85%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 1.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.85%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 21       | 42%     |
| 1 x AMD                 | 15       | 30%     |
| 1 x Intel               | 12       | 24%     |
| 1 x Loongson Technology | 1        | 2%      |
| Intel + AMD             | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 72%     |
| Proprietary | 12       | 24%     |
| Unknown     | 2        | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 44.23%  |
| 1.01-2.0   | 13       | 25%     |
| 3.01-4.0   | 6        | 11.54%  |
| 7.01-8.0   | 3        | 5.77%   |
| 0.51-1.0   | 3        | 5.77%   |
| 5.01-6.0   | 2        | 3.85%   |
| 0.01-0.5   | 2        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 21.15%  |
| Goldstar             | 7        | 13.46%  |
| Hewlett-Packard      | 5        | 9.62%   |
| Dell                 | 3        | 5.77%   |
| ViewSonic            | 2        | 3.85%   |
| Philips              | 2        | 3.85%   |
| Lenovo               | 2        | 3.85%   |
| Iiyama               | 2        | 3.85%   |
| AOC                  | 2        | 3.85%   |
| Ancor Communications | 2        | 3.85%   |
| Acer                 | 2        | 3.85%   |
| Unknown              | 1        | 1.92%   |
| Toshiba              | 1        | 1.92%   |
| TFC                  | 1        | 1.92%   |
| RTK                  | 1        | 1.92%   |
| Positivo             | 1        | 1.92%   |
| MSI                  | 1        | 1.92%   |
| Hisense              | 1        | 1.92%   |
| Gateway              | 1        | 1.92%   |
| DTV                  | 1        | 1.92%   |
| BOE                  | 1        | 1.92%   |
| BenQ                 | 1        | 1.92%   |
| ASUSTek Computer     | 1        | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 3.45%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 1        | 1.72%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1        | 1.72%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.72%   |
| Toshiba TV TSB0108 1920x1080 890x500mm 40.2-inch                        | 1        | 1.72%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 1.72%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1        | 1.72%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch    | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1        | 1.72%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1        | 1.72%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1        | 1.72%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 1.72%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 1.72%   |
| RTK PORPOISE RTKBC32 1920x1080 344x195mm 15.6-inch                      | 1        | 1.72%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1        | 1.72%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1        | 1.72%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 1.72%   |
| MSI MAG271C MSI3FA6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.72%   |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch                 | 1        | 1.72%   |
| Lenovo E1922s Wide LEN60BD 1366x768 410x230mm 18.5-inch                 | 1        | 1.72%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 1.72%   |
| Iiyama PL2792Q IVM662F 2560x1440 597x336mm 27.0-inch                    | 1        | 1.72%   |
| Hisense LCD Monitor HDMI 1360x768                                       | 1        | 1.72%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch            | 1        | 1.72%   |
| Hewlett-Packard Compaq F191 HWP3177 1366x768 410x230mm 18.5-inch        | 1        | 1.72%   |
| Hewlett-Packard 2511 HWP293E 1920x1080 553x311mm 25.0-inch              | 1        | 1.72%   |
| Hewlett-Packard 2311x HWP293A 1920x1080 510x287mm 23.0-inch             | 1        | 1.72%   |
| Hewlett-Packard 22f HPN3542 1920x1080 476x267mm 21.5-inch               | 1        | 1.72%   |
| Goldstar M227WD GSM56D4 1920x1080 476x268mm 21.5-inch                   | 1        | 1.72%   |
| Goldstar L196WTQ GSM4B50 1440x900 408x255mm 18.9-inch                   | 1        | 1.72%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 1        | 1.72%   |
| Goldstar E2360 GSM57E4 1920x1080 510x290mm 23.1-inch                    | 1        | 1.72%   |
| Goldstar 2D HD LG TV GSM59CA 1920x1080 510x290mm 23.1-inch              | 1        | 1.72%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                   | 1        | 1.72%   |
| Gateway HD2201 GWY08AF 1680x1050 465x261mm 21.0-inch                    | 1        | 1.72%   |
| DTV STI DTV0030 1600x1200 708x398mm 32.0-inch                           | 1        | 1.72%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                       | 1        | 1.72%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                       | 1        | 1.72%   |
| Dell 20 DELF112 1600x900 443x249mm 20.0-inch                            | 1        | 1.72%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                   | 1        | 1.72%   |
| BenQ ZOWIE XL LCD BNQ7F3D 1920x1080 531x298mm 24.0-inch                 | 1        | 1.72%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch            | 1        | 1.72%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                       | 1        | 1.72%   |
| AOC 2267W AOC2267 1920x1080 476x268mm 21.5-inch                         | 1        | 1.72%   |
| Ancor Communications LCD Monitor ASUS VS247 3840x1080                   | 1        | 1.72%   |
| Ancor Communications LCD Monitor ASUS VS247                             | 1        | 1.72%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 1        | 1.72%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch   | 1        | 1.72%   |
| Acer P193W ACRADAA 1440x900 408x255mm 18.9-inch                         | 1        | 1.72%   |
| Acer K272HUL ACR0524 2560x1440 598x336mm 27.0-inch                      | 1        | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 53.7%   |
| 1600x900 (HD+)     | 4        | 7.41%   |
| 2560x1440 (QHD)    | 3        | 5.56%   |
| 1366x768 (WXGA)    | 3        | 5.56%   |
| 3840x2160 (4K)     | 2        | 3.7%    |
| 3840x1080          | 2        | 3.7%    |
| 1440x900 (WXGA+)   | 2        | 3.7%    |
| 1360x768           | 2        | 3.7%    |
| Unknown            | 2        | 3.7%    |
| 2288x1287          | 1        | 1.85%   |
| 1920x540           | 1        | 1.85%   |
| 1920x1200 (WUXGA)  | 1        | 1.85%   |
| 1680x1050 (WSXGA+) | 1        | 1.85%   |
| 1280x1024 (SXGA)   | 1        | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 13       | 23.64%  |
| 24      | 7        | 12.73%  |
| Unknown | 7        | 12.73%  |
| 27      | 5        | 9.09%   |
| 21      | 4        | 7.27%   |
| 20      | 3        | 5.45%   |
| 18      | 3        | 5.45%   |
| 84      | 2        | 3.64%   |
| 19      | 2        | 3.64%   |
| 142     | 1        | 1.82%   |
| 72      | 1        | 1.82%   |
| 65      | 1        | 1.82%   |
| 32      | 1        | 1.82%   |
| 31      | 1        | 1.82%   |
| 25      | 1        | 1.82%   |
| 22      | 1        | 1.82%   |
| 15      | 1        | 1.82%   |
| 12      | 1        | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 25       | 46.3%   |
| 401-500        | 13       | 24.07%  |
| Unknown        | 7        | 12.96%  |
| 1501-2000      | 3        | 5.56%   |
| More than 2000 | 1        | 1.85%   |
| 701-800        | 1        | 1.85%   |
| 601-700        | 1        | 1.85%   |
| 301-350        | 1        | 1.85%   |
| 201-300        | 1        | 1.85%   |
| 1001-1500      | 1        | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 78.43%  |
| Unknown | 6        | 11.76%  |
| 16/10   | 4        | 7.84%   |
| 1.00    | 1        | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 36.36%  |
| 151-200        | 9        | 16.36%  |
| Unknown        | 7        | 12.73%  |
| More than 1000 | 5        | 9.09%   |
| 301-350        | 5        | 9.09%   |
| 251-300        | 3        | 5.45%   |
| 351-500        | 2        | 3.64%   |
| 141-150        | 2        | 3.64%   |
| 61-70          | 1        | 1.82%   |
| 101-110        | 1        | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 62.26%  |
| 101-120 | 8        | 15.09%  |
| Unknown | 7        | 13.21%  |
| 1-50    | 4        | 7.55%   |
| 161-240 | 1        | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 86.27%  |
| 2     | 7        | 13.73%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 34       | 52.31%  |
| Intel                    | 12       | 18.46%  |
| TP-Link                  | 3        | 4.62%   |
| Qualcomm Atheros         | 3        | 4.62%   |
| Broadcom                 | 3        | 4.62%   |
| Xiaomi                   | 1        | 1.54%   |
| Unknown                  | 1        | 1.54%   |
| Ralink                   | 1        | 1.54%   |
| NXP Semiconductors       | 1        | 1.54%   |
| Nvidia                   | 1        | 1.54%   |
| NetGear                  | 1        | 1.54%   |
| MediaTek                 | 1        | 1.54%   |
| Marvell Technology Group | 1        | 1.54%   |
| Loongson Technology      | 1        | 1.54%   |
| IMC Networks             | 1        | 1.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 41.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.78%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.78%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.39%   |
| Unknown Network controller                                        | 1        | 1.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 1.39%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.39%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 1.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1.39%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 1        | 1.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.39%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.39%   |
| NetGear A6210                                                     | 1        | 1.39%   |
| MediaTek WP5 Pro                                                  | 1        | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.39%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.39%   |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.39%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 1        | 1.39%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.39%   |
| Unknown                                                           | 1        | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 42.86%  |
| TP-Link               | 3        | 21.43%  |
| Ralink                | 1        | 7.14%   |
| Qualcomm Atheros      | 1        | 7.14%   |
| NetGear               | 1        | 7.14%   |
| Intel                 | 1        | 7.14%   |
| IMC Networks          | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]               | 1        | 7.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                       | 1        | 7.14%   |
| TP-Link 802.11ac WLAN Adapter                             | 1        | 7.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter   | 1        | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter           | 1        | 7.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                    | 1        | 7.14%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch) | 1        | 7.14%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter     | 1        | 7.14%   |
| Realtek RTL8188EE Wireless Network Adapter                | 1        | 7.14%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter    | 1        | 7.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter          | 1        | 7.14%   |
| NetGear A6210                                             | 1        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]          | 1        | 7.14%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]      | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 34       | 61.82%  |
| Intel                    | 11       | 20%     |
| Broadcom                 | 3        | 5.45%   |
| Qualcomm Atheros         | 2        | 3.64%   |
| Xiaomi                   | 1        | 1.82%   |
| Nvidia                   | 1        | 1.82%   |
| MediaTek                 | 1        | 1.82%   |
| Marvell Technology Group | 1        | 1.82%   |
| Loongson Technology      | 1        | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 53.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.57%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 3.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.57%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.79%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.79%   |
| MediaTek WP5 Pro                                                  | 1        | 1.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.79%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.79%   |
| Loongson Gigabit Ethernet Controller                              | 1        | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.79%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.79%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 75.76%  |
| WiFi     | 14       | 21.21%  |
| Modem    | 1        | 1.52%   |
| Unknown  | 1        | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 82.46%  |
| WiFi     | 9        | 15.79%  |
| Unknown  | 1        | 1.75%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 76.47%  |
| 2     | 12       | 23.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 98%     |
| Yes  | 1        | 2%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 10       | 66.67%  |
| Realtek Semiconductor           | 1        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Intel                           | 1        | 6.67%   |
| Dynex                           | 1        | 6.67%   |
| ASUSTek Computer                | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 10       | 66.67%  |
| Realtek Bluetooth Radio                                  | 1        | 6.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 6.67%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 38       | 44.71%  |
| AMD                     | 21       | 24.71%  |
| Nvidia                  | 20       | 23.53%  |
| C-Media Electronics     | 2        | 2.35%   |
| XMOS                    | 1        | 1.18%   |
| Microdia                | 1        | 1.18%   |
| Loongson Technology     | 1        | 1.18%   |
| BEHRINGER International | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 7.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 6.52%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 5.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 5.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 4.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 4.35%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 3.26%   |
| Nvidia GF116 High Definition Audio Controller                                     | 3        | 3.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 3.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 3.26%   |
| Nvidia High Definition Audio Controller                                           | 2        | 2.17%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 2.17%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 2.17%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 2.17%   |
| AMD FCH Azalia Controller                                                         | 2        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.17%   |
| XMOS iFi (by AMR) HD USB Audio                                                    | 1        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.09%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.09%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 1.09%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 1.09%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 1.09%   |
| Microdia USB Audio                                                                | 1        | 1.09%   |
| Loongson Technology HDA (High Definition Audio) Controller                        | 1        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.09%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.09%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 1.09%   |
| BEHRINGER International UMC202HD 192k                                             | 1        | 1.09%   |
| AMD Wrestler HDMI Audio                                                           | 1        | 1.09%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 1        | 1.09%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1        | 1.09%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 1        | 1.09%   |
| AMD Navi 10 HDMI Audio                                                            | 1        | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                          | 1        | 1.09%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                             | 1        | 1.09%   |
| AMD Audio device                                                                  | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 37.5%   |
| Unknown             | 5        | 20.83%  |
| G.Skill             | 2        | 8.33%   |
| Corsair             | 2        | 8.33%   |
| Team                | 1        | 4.17%   |
| Samsung Electronics | 1        | 4.17%   |
| Nanya Technology    | 1        | 4.17%   |
| CSX                 | 1        | 4.17%   |
| Apacer              | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s   | 2        | 7.69%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 3.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s             | 1        | 3.85%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 3.85%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s       | 1        | 3.85%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s      | 1        | 3.85%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 1        | 3.85%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s       | 1        | 3.85%   |
| Kingston RAM KTW149-ELF 1024MB DIMM DDR3 1333MT/s        | 1        | 3.85%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s        | 1        | 3.85%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1        | 3.85%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s      | 1        | 3.85%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 1        | 3.85%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1867MT/s   | 1        | 3.85%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s | 1        | 3.85%   |
| Kingston RAM 99U5474-038.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 3.85%   |
| Kingston RAM 99U5403-034.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.85%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s       | 1        | 3.85%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s    | 1        | 3.85%   |
| CSX RAM V01D3LF4GB26826813 4096MB DIMM DDR3 1333MT/s     | 1        | 3.85%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s    | 1        | 3.85%   |
| Apacer RAM 76.C346G.C850C 8192MB SODIMM DDR3 1600MT/s    | 1        | 3.85%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 2666MT/s          | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 11       | 50%     |
| DDR3    | 9        | 40.91%  |
| SDRAM   | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 95.45%  |
| SODIMM | 1        | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 72.73%  |
| 4096  | 3        | 13.64%  |
| 32768 | 1        | 4.55%   |
| 2048  | 1        | 4.55%   |
| 1024  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 4        | 16.67%  |
| 1867    | 3        | 12.5%   |
| 1600    | 3        | 12.5%   |
| 2667    | 2        | 8.33%   |
| 1333    | 2        | 8.33%   |
| 3500    | 1        | 4.17%   |
| 3466    | 1        | 4.17%   |
| 2933    | 1        | 4.17%   |
| 2800    | 1        | 4.17%   |
| 2666    | 1        | 4.17%   |
| 2400    | 1        | 4.17%   |
| 2133    | 1        | 4.17%   |
| 1067    | 1        | 4.17%   |
| 667     | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 5        | 55.56%  |
| Microdia               | 1        | 11.11%  |
| HD WEBCAM              | 1        | 11.11%  |
| Generalplus Technology | 1        | 11.11%  |
| Arkmicro Technologies  | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 3        | 33.33%  |
| Microdia Integrated_Webcam_HD | 1        | 11.11%  |
| Logitech Webcam C200          | 1        | 11.11%  |
| Logitech HD Pro Webcam C920   | 1        | 11.11%  |
| HD WEBCAM HD WEBCAM           | 1        | 11.11%  |
| Generalplus GENERAL WEBCAM    | 1        | 11.11%  |
| Arkmicro Acme CA04            | 1        | 11.11%  |

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
| 0     | 47       | 94%     |
| 1     | 2        | 4%      |
| 2     | 1        | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 75%     |
| Graphics card | 1        | 25%     |
