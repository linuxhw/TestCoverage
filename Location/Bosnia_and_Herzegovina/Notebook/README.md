Linux in Bosnia and Herzegovina - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

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

Total: 95

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Acer          | Aspire F5-573G              | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| Dell          | Inspiron 5323               | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | EliteBook 8470p             | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| HP            | ProBook 470 G0              | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Dell          | G3 3590                     | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| eMachines     | eME728                      | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| Dell          | Latitude E7470              | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| HP            | EliteBook 8560p             | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| Dell          | System Inspiron N7110       | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| HP            | EliteBook 8460p             | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| Dell          | G3 3590                     | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| Acer          | AO756                       | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| Acer          | Aspire 7741                 | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| Unknown       | Unknown                     | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ASUSTek       | X75VBP                      | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Lenovo        | G505 20240                  | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| HP            | ENVY TS 15                  | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| HP            | EliteBook 8470p             | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| HP            | Compaq CQ58                 | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| HP            | 255 G2                      | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Acer          | Aspire 9300                 | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| ASUSTek       | X751MD                      | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| Dell          | Inspiron 3521               | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Sony          | VGN-BX41VN                  | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 13        | 18.57%  |
| Pop!_OS 21.04          | 6         | 8.57%   |
| Ubuntu 18.04           | 4         | 5.71%   |
| Linux Mint 20.2        | 4         | 5.71%   |
| Zorin 16               | 3         | 4.29%   |
| Manjaro                | 3         | 4.29%   |
| Ubuntu 20.10           | 2         | 2.86%   |
| Ubuntu 19.04           | 2         | 2.86%   |
| Pop!_OS 20.04          | 2         | 2.86%   |
| OpenMandriva 4.3       | 2         | 2.86%   |
| Lubuntu 19.10          | 2         | 2.86%   |
| Linux Mint 19.3        | 2         | 2.86%   |
| ArcoLinux Rolling      | 2         | 2.86%   |
| Zorin 15               | 1         | 1.43%   |
| Xubuntu 20.04          | 1         | 1.43%   |
| Xubuntu 18.04          | 1         | 1.43%   |
| Ubuntu 22.04           | 1         | 1.43%   |
| Ubuntu 21.10           | 1         | 1.43%   |
| Ubuntu 21.04           | 1         | 1.43%   |
| Ubuntu 16.04           | 1         | 1.43%   |
| ROSA R10               | 1         | 1.43%   |
| PureOS 9.0             | 1         | 1.43%   |
| Pop!_OS 21.10          | 1         | 1.43%   |
| Pop!_OS 20.10          | 1         | 1.43%   |
| Manjaro 21.2.5         | 1         | 1.43%   |
| Manjaro 21.0.7         | 1         | 1.43%   |
| Linux Mint 20          | 1         | 1.43%   |
| KDE neon 20.04         | 1         | 1.43%   |
| Fedora 32              | 1         | 1.43%   |
| Endless 3.7.8          | 1         | 1.43%   |
| Endless 3.5.1          | 1         | 1.43%   |
| Endless 3.3.19-nexthw1 | 1         | 1.43%   |
| Debian Testing         | 1         | 1.43%   |
| Debian 10              | 1         | 1.43%   |
| Arch Rolling           | 1         | 1.43%   |
| Arch                   | 1         | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 24        | 35.29%  |
| Pop!_OS      | 10        | 14.71%  |
| Linux Mint   | 6         | 8.82%   |
| Manjaro      | 5         | 7.35%   |
| Zorin        | 4         | 5.88%   |
| Endless      | 3         | 4.41%   |
| Xubuntu      | 2         | 2.94%   |
| OpenMandriva | 2         | 2.94%   |
| Lubuntu      | 2         | 2.94%   |
| Debian       | 2         | 2.94%   |
| ArcoLinux    | 2         | 2.94%   |
| Arch         | 2         | 2.94%   |
| ROSA         | 1         | 1.47%   |
| PureOS       | 1         | 1.47%   |
| KDE neon     | 1         | 1.47%   |
| Fedora       | 1         | 1.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.3.0-46-generic                | 3         | 4.29%   |
| 5.3.0-28-generic                | 3         | 4.29%   |
| 5.4.0-89-generic                | 2         | 2.86%   |
| 5.4.0-52-generic                | 2         | 2.86%   |
| 5.16.7-desktop-1omv4003         | 2         | 2.86%   |
| 5.13.0-7620-generic             | 2         | 2.86%   |
| 5.13.0-7614-generic             | 2         | 2.86%   |
| 5.13.0-39-generic               | 2         | 2.86%   |
| 5.11.0-40-generic               | 2         | 2.86%   |
| 5.9.0-3-amd64                   | 1         | 1.43%   |
| 5.8.9-200.fc32.x86_64           | 1         | 1.43%   |
| 5.8.0-7630-generic              | 1         | 1.43%   |
| 5.8.0-53-generic                | 1         | 1.43%   |
| 5.8.0-49-generic                | 1         | 1.43%   |
| 5.8.0-44-generic                | 1         | 1.43%   |
| 5.8.0-34-generic                | 1         | 1.43%   |
| 5.8.0-26-generic                | 1         | 1.43%   |
| 5.7.0-1-librem5                 | 1         | 1.43%   |
| 5.4.52-1-MANJARO                | 1         | 1.43%   |
| 5.4.33-3-MANJARO                | 1         | 1.43%   |
| 5.4.23-1-MANJARO                | 1         | 1.43%   |
| 5.4.0-90-generic                | 1         | 1.43%   |
| 5.4.0-80-generic                | 1         | 1.43%   |
| 5.4.0-7625-generic              | 1         | 1.43%   |
| 5.4.0-72-generic                | 1         | 1.43%   |
| 5.4.0-67-generic                | 1         | 1.43%   |
| 5.4.0-58-generic                | 1         | 1.43%   |
| 5.4.0-54-generic                | 1         | 1.43%   |
| 5.4.0-48-generic                | 1         | 1.43%   |
| 5.4.0-33-generic                | 1         | 1.43%   |
| 5.4.0-26-generic                | 1         | 1.43%   |
| 5.3.0-51-generic                | 1         | 1.43%   |
| 5.16.14-1-MANJARO               | 1         | 1.43%   |
| 5.16.11-arch1-1                 | 1         | 1.43%   |
| 5.15.23-76051523-generic        | 1         | 1.43%   |
| 5.15.11-76051511-generic        | 1         | 1.43%   |
| 5.15.0-39-generic               | 1         | 1.43%   |
| 5.13.9-arch1-1                  | 1         | 1.43%   |
| 5.13.0-48-generic               | 1         | 1.43%   |
| 5.13.0-30-generic               | 1         | 1.43%   |
| 5.13.0-27-generic               | 1         | 1.43%   |
| 5.13.0-22-generic               | 1         | 1.43%   |
| 5.11.18-hardened1-1-hardened    | 1         | 1.43%   |
| 5.11.0-7633-generic             | 1         | 1.43%   |
| 5.11.0-7614-generic             | 1         | 1.43%   |
| 5.11.0-38-generic               | 1         | 1.43%   |
| 5.11.0-26-generic               | 1         | 1.43%   |
| 5.10.42-1-MANJARO               | 1         | 1.43%   |
| 5.10.37-1-lts                   | 1         | 1.43%   |
| 5.10.0-0.bpo.5-amd64            | 1         | 1.43%   |
| 5.0.0-27-generic                | 1         | 1.43%   |
| 5.0.0-23-generic                | 1         | 1.43%   |
| 5.0.0-13-generic                | 1         | 1.43%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 1         | 1.43%   |
| 4.18.0-10-generic               | 1         | 1.43%   |
| 4.15.0-45-generic               | 1         | 1.43%   |
| 4.15.0-39-generic               | 1         | 1.43%   |
| 4.15.0-15-generic               | 1         | 1.43%   |
| 4.15.0-124-generic              | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 14        | 20%     |
| 5.13.0  | 10        | 14.29%  |
| 5.3.0   | 7         | 10%     |
| 5.8.0   | 6         | 8.57%   |
| 5.11.0  | 6         | 8.57%   |
| 4.15.0  | 4         | 5.71%   |
| 5.0.0   | 3         | 4.29%   |
| 5.16.7  | 2         | 2.86%   |
| 5.9.0   | 1         | 1.43%   |
| 5.8.9   | 1         | 1.43%   |
| 5.7.0   | 1         | 1.43%   |
| 5.4.52  | 1         | 1.43%   |
| 5.4.33  | 1         | 1.43%   |
| 5.4.23  | 1         | 1.43%   |
| 5.16.14 | 1         | 1.43%   |
| 5.16.11 | 1         | 1.43%   |
| 5.15.23 | 1         | 1.43%   |
| 5.15.11 | 1         | 1.43%   |
| 5.15.0  | 1         | 1.43%   |
| 5.13.9  | 1         | 1.43%   |
| 5.11.18 | 1         | 1.43%   |
| 5.10.42 | 1         | 1.43%   |
| 5.10.37 | 1         | 1.43%   |
| 5.10.0  | 1         | 1.43%   |
| 4.9.60  | 1         | 1.43%   |
| 4.18.0  | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 17        | 24.29%  |
| 5.13    | 11        | 15.71%  |
| 5.8     | 7         | 10%     |
| 5.3     | 7         | 10%     |
| 5.11    | 7         | 10%     |
| 5.16    | 4         | 5.71%   |
| 4.15    | 4         | 5.71%   |
| 5.15    | 3         | 4.29%   |
| 5.10    | 3         | 4.29%   |
| 5.0     | 3         | 4.29%   |
| 5.9     | 1         | 1.43%   |
| 5.7     | 1         | 1.43%   |
| 4.9     | 1         | 1.43%   |
| 4.18    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 63        | 94.03%  |
| i686    | 3         | 4.48%   |
| aarch64 | 1         | 1.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 39        | 57.35%  |
| XFCE       | 9         | 13.24%  |
| KDE5       | 6         | 8.82%   |
| Unknown    | 6         | 8.82%   |
| X-Cinnamon | 2         | 2.94%   |
| LXQt       | 2         | 2.94%   |
| MATE       | 1         | 1.47%   |
| KDE4       | 1         | 1.47%   |
| KDE        | 1         | 1.47%   |
| bspwm      | 1         | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 82.09%  |
| Wayland | 7         | 10.45%  |
| Unknown | 5         | 7.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 46        | 65.71%  |
| SDDM    | 8         | 11.43%  |
| GDM     | 7         | 10%     |
| LightDM | 5         | 7.14%   |
| GDM3    | 3         | 4.29%   |
| KDM     | 1         | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 50        | 73.53%  |
| Unknown | 6         | 8.82%   |
| hr_HR   | 4         | 5.88%   |
| bs_BA   | 3         | 4.41%   |
| C       | 2         | 2.94%   |
| en_GB   | 1         | 1.47%   |
| en_AU   | 1         | 1.47%   |
| de_CH   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 45        | 66.18%  |
| EFI  | 23        | 33.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 59        | 88.06%  |
| Btrfs   | 3         | 4.48%   |
| Unknown | 3         | 4.48%   |
| Overlay | 2         | 2.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 73.91%  |
| GPT     | 12        | 17.39%  |
| MBR     | 6         | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 94.03%  |
| Yes       | 4         | 5.97%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 82.09%  |
| Yes       | 12        | 17.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 20        | 29.85%  |
| Lenovo           | 12        | 17.91%  |
| ASUSTek Computer | 11        | 16.42%  |
| Acer             | 10        | 14.93%  |
| Dell             | 7         | 10.45%  |
| Toshiba          | 1         | 1.49%   |
| Sony             | 1         | 1.49%   |
| NEC Computers    | 1         | 1.49%   |
| HUAWEI           | 1         | 1.49%   |
| Fujitsu Siemens  | 1         | 1.49%   |
| eMachines        | 1         | 1.49%   |
| Unknown          | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 8460p                     | 2         | 2.99%   |
| Dell G3 3590                           | 2         | 2.99%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA | 2         | 2.99%   |
| Toshiba Satellite C850-1GF             | 1         | 1.49%   |
| Sony VGN-BX41VN                        | 1         | 1.49%   |
| NEC Computers VERSAP550 NN951700753    | 1         | 1.49%   |
| Lenovo ThinkPad X301 277418G           | 1         | 1.49%   |
| Lenovo ThinkPad T430 2349G2G           | 1         | 1.49%   |
| Lenovo ThinkPad T420 4180WAP           | 1         | 1.49%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ     | 1         | 1.49%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC   | 1         | 1.49%   |
| Lenovo Legion 7 15IMHg05 81YU          | 1         | 1.49%   |
| Lenovo IdeaPad Y570 20091              | 1         | 1.49%   |
| Lenovo IdeaPad L340-15IWL 81LG         | 1         | 1.49%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1.49%   |
| Lenovo IdeaPad 320-15IKB 81BG          | 1         | 1.49%   |
| Lenovo IdeaPad 110S-11IBR 80WG         | 1         | 1.49%   |
| Lenovo G505 20240                      | 1         | 1.49%   |
| HUAWEI BOHK-WAX9X                      | 1         | 1.49%   |
| HP ProBook 4710s                       | 1         | 1.49%   |
| HP ProBook 470 G2                      | 1         | 1.49%   |
| HP ProBook 470 G0                      | 1         | 1.49%   |
| HP Pavilion Gaming Laptop 15-dk2xxx    | 1         | 1.49%   |
| HP Laptop 15-rb0xx                     | 1         | 1.49%   |
| HP ENVY TS 15                          | 1         | 1.49%   |
| HP ENVY 6                              | 1         | 1.49%   |
| HP EliteBook 8560p                     | 1         | 1.49%   |
| HP EliteBook 850 G8 Notebook PC        | 1         | 1.49%   |
| HP EliteBook 850 G3                    | 1         | 1.49%   |
| HP EliteBook 8470p                     | 1         | 1.49%   |
| HP EliteBook 840 G1                    | 1         | 1.49%   |
| HP EliteBook 2560p                     | 1         | 1.49%   |
| HP Compaq CQ58                         | 1         | 1.49%   |
| HP 550                                 | 1         | 1.49%   |
| HP 255 G2                              | 1         | 1.49%   |
| HP 250 G7 Notebook PC                  | 1         | 1.49%   |
| HP 250 G6 Notebook PC                  | 1         | 1.49%   |
| Fujitsu Siemens AMILO Li 2727          | 1         | 1.49%   |
| eMachines eME728                       | 1         | 1.49%   |
| Dell XPS 15 9570                       | 1         | 1.49%   |
| Dell System Inspiron N7110             | 1         | 1.49%   |
| Dell Latitude E7470                    | 1         | 1.49%   |
| Dell Inspiron 5323                     | 1         | 1.49%   |
| Dell Inspiron 3521                     | 1         | 1.49%   |
| ASUS ZenBook UX433FA_UX433FA           | 1         | 1.49%   |
| ASUS X75VBP                            | 1         | 1.49%   |
| ASUS X751MD                            | 1         | 1.49%   |
| ASUS X550ZE                            | 1         | 1.49%   |
| ASUS X540SAA                           | 1         | 1.49%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA | 1         | 1.49%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR   | 1         | 1.49%   |
| ASUS TUF Gaming FX705DY_FX705DY        | 1         | 1.49%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM  | 1         | 1.49%   |
| Acer Switch One SW1-011                | 1         | 1.49%   |
| Acer Aspire F5-573G                    | 1         | 1.49%   |
| Acer Aspire E5-575G                    | 1         | 1.49%   |
| Acer Aspire A315-31                    | 1         | 1.49%   |
| Acer Aspire 9300                       | 1         | 1.49%   |
| Acer Aspire 8950G                      | 1         | 1.49%   |
| Acer Aspire 7741                       | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 8         | 11.94%  |
| Acer Aspire             | 7         | 10.45%  |
| Lenovo ThinkPad         | 5         | 7.46%   |
| Lenovo IdeaPad          | 5         | 7.46%   |
| ASUS VivoBook           | 4         | 5.97%   |
| HP ProBook              | 3         | 4.48%   |
| HP ENVY                 | 2         | 2.99%   |
| HP 250                  | 2         | 2.99%   |
| Dell Inspiron           | 2         | 2.99%   |
| Dell G3                 | 2         | 2.99%   |
| Toshiba Satellite       | 1         | 1.49%   |
| Sony VGN-BX41VN         | 1         | 1.49%   |
| NEC Computers VERSAP550 | 1         | 1.49%   |
| Lenovo Legion           | 1         | 1.49%   |
| Lenovo G505             | 1         | 1.49%   |
| HUAWEI BOHK-WAX9X       | 1         | 1.49%   |
| HP Pavilion             | 1         | 1.49%   |
| HP Laptop               | 1         | 1.49%   |
| HP Compaq               | 1         | 1.49%   |
| HP 550                  | 1         | 1.49%   |
| HP 255                  | 1         | 1.49%   |
| Fujitsu Siemens AMILO   | 1         | 1.49%   |
| eMachines eME728        | 1         | 1.49%   |
| Dell XPS                | 1         | 1.49%   |
| Dell System             | 1         | 1.49%   |
| Dell Latitude           | 1         | 1.49%   |
| ASUS ZenBook            | 1         | 1.49%   |
| ASUS X75VBP             | 1         | 1.49%   |
| ASUS X751MD             | 1         | 1.49%   |
| ASUS X550ZE             | 1         | 1.49%   |
| ASUS X540SAA            | 1         | 1.49%   |
| ASUS TUF                | 1         | 1.49%   |
| ASUS ROG                | 1         | 1.49%   |
| Acer Switch             | 1         | 1.49%   |
| Acer AO756              | 1         | 1.49%   |
| Acer AO725              | 1         | 1.49%   |
| Unknown                 | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 10        | 14.93%  |
| 2012    | 8         | 11.94%  |
| 2019    | 7         | 10.45%  |
| 2016    | 6         | 8.96%   |
| 2013    | 6         | 8.96%   |
| 2018    | 5         | 7.46%   |
| 2020    | 4         | 5.97%   |
| 2017    | 4         | 5.97%   |
| 2014    | 4         | 5.97%   |
| 2021    | 2         | 2.99%   |
| 2010    | 2         | 2.99%   |
| 2009    | 2         | 2.99%   |
| 2007    | 2         | 2.99%   |
| 2015    | 1         | 1.49%   |
| 2008    | 1         | 1.49%   |
| 2006    | 1         | 1.49%   |
| 2005    | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 65        | 97.01%  |
| Enabled  | 2         | 2.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 23        | 34.33%  |
| 3.01-4.0   | 16        | 23.88%  |
| 1.01-2.0   | 9         | 13.43%  |
| 16.01-24.0 | 8         | 11.94%  |
| 8.01-16.0  | 7         | 10.45%  |
| 2.01-3.0   | 2         | 2.99%   |
| 32.01-64.0 | 1         | 1.49%   |
| 0.51-1.0   | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 40.58%  |
| 2.01-3.0  | 17        | 24.64%  |
| 0.51-1.0  | 8         | 11.59%  |
| 3.01-4.0  | 7         | 10.14%  |
| 4.01-8.0  | 6         | 8.7%    |
| 8.01-16.0 | 2         | 2.9%    |
| 0.01-0.5  | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 80.6%   |
| 2      | 13        | 19.4%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 52.24%  |
| Yes       | 32        | 47.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 80.88%  |
| No        | 13        | 19.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 95.52%  |
| No        | 3         | 4.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 73.53%  |
| No        | 18        | 26.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 24        | 34.78%  |
| Banja Luka        | 12        | 17.39%  |
| Tuzla             | 5         | 7.25%   |
| Gracanica         | 3         | 4.35%   |
| Srebrenik         | 2         | 2.9%    |
| Zivinice          | 1         | 1.45%   |
| Zepce             | 1         | 1.45%   |
| Zenica            | 1         | 1.45%   |
| Velika Kladu????a | 1         | 1.45%   |
| Trebinje          | 1         | 1.45%   |
| Teslic            | 1         | 1.45%   |
| Stjepan-Polje     | 1         | 1.45%   |
| Solina            | 1         | 1.45%   |
| Prijedor          | 1         | 1.45%   |
| Posusje           | 1         | 1.45%   |
| Pale              | 1         | 1.45%   |
| Orahovica Donja   | 1         | 1.45%   |
| Novi Travnik      | 1         | 1.45%   |
| Nevesinje         | 1         | 1.45%   |
| Mostar            | 1         | 1.45%   |
| Maglaj            | 1         | 1.45%   |
| Lukavac           | 1         | 1.45%   |
| Ljubuski          | 1         | 1.45%   |
| Ilidza            | 1         | 1.45%   |
| Grude             | 1         | 1.45%   |
| Doboj             | 1         | 1.45%   |
| Brcko             | 1         | 1.45%   |
| Banovici          | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 9      | 11.54%  |
| SanDisk             | 9         | 11     | 11.54%  |
| Samsung Electronics | 9         | 9      | 11.54%  |
| Kingston            | 9         | 9      | 11.54%  |
| Hitachi             | 8         | 8      | 10.26%  |
| WDC                 | 6         | 7      | 7.69%   |
| Seagate             | 6         | 9      | 7.69%   |
| SK hynix            | 5         | 6      | 6.41%   |
| Unknown             | 3         | 3      | 3.85%   |
| Intel               | 3         | 3      | 3.85%   |
| A-DATA Technology   | 2         | 2      | 2.56%   |
| Vaseky              | 1         | 1      | 1.28%   |
| Team                | 1         | 1      | 1.28%   |
| Patriot             | 1         | 1      | 1.28%   |
| OCZ                 | 1         | 2      | 1.28%   |
| KIOXIA              | 1         | 1      | 1.28%   |
| Intenso             | 1         | 1      | 1.28%   |
| HGST                | 1         | 1      | 1.28%   |
| Goodram             | 1         | 1      | 1.28%   |
| Crucial             | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 3.8%    |
| SK hynix NVMe SSD Drive 512GB        | 3         | 3.8%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 3.8%    |
| Unknown MMC Card  32GB               | 2         | 2.53%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 2.53%   |
| Kingston SHFS37A120G 120GB SSD       | 2         | 2.53%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1         | 1.27%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 1         | 1.27%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 1.27%   |
| WDC WD5000LPVT-75G33T0 500GB         | 1         | 1.27%   |
| WDC WD5000BEKT-22KA9T0 500GB         | 1         | 1.27%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.27%   |
| Vaseky V800/128G 128GB               | 1         | 1.27%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.27%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.27%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.27%   |
| Toshiba MK3263GSX 320GB              | 1         | 1.27%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1.27%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1.27%   |
| Toshiba KXG60ZNV512G 512GB           | 1         | 1.27%   |
| Team T253X1120G 120GB SSD            | 1         | 1.27%   |
| SK hynix SC300 M.2 2280 256GB SSD    | 1         | 1.27%   |
| SK hynix HFM001TD3JX013N 1TB         | 1         | 1.27%   |
| SK hynix BC501 NVMe 512GB            | 1         | 1.27%   |
| Seagate ST9120817AS 120GB            | 1         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.27%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.27%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.27%   |
| SanDisk SSD PLUS 120GB               | 1         | 1.27%   |
| SanDisk SD9SB8W256G1002 256GB SSD    | 1         | 1.27%   |
| SanDisk SD8SBAT128G1002 128GB SSD    | 1         | 1.27%   |
| SanDisk SD7TB3Q-128G-1006 128GB SSD  | 1         | 1.27%   |
| SanDisk NVMe SSD Drive 512GB         | 1         | 1.27%   |
| SanDisk NVMe SSD Drive 1024GB        | 1         | 1.27%   |
| SanDisk DF4032  32GB                 | 1         | 1.27%   |
| Samsung SSD 830 Series 256GB         | 1         | 1.27%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 1.27%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 1         | 1.27%   |
| Samsung MZVLQ256HAJD-000H1 256GB     | 1         | 1.27%   |
| Samsung MZNLN256HAJQ-000L2 256GB SSD | 1         | 1.27%   |
| Samsung MZMTE256HMHP-000L1 256GB SSD | 1         | 1.27%   |
| Samsung MZMPC032HBCD-000H1 32GB SSD  | 1         | 1.27%   |
| Samsung MZ7TD256HAFV-000L9 256GB SSD | 1         | 1.27%   |
| Samsung MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1.27%   |
| Patriot Burst 240GB SSD              | 1         | 1.27%   |
| OCZ AGILITY3 480GB SSD               | 1         | 1.27%   |
| KIOXIA KBG40ZNV512G 512GB            | 1         | 1.27%   |
| Kingston SM2280S3G2240G 240GB SSD    | 1         | 1.27%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 1.27%   |
| Kingston SA400M8240G 240GB SSD       | 1         | 1.27%   |
| Kingston RBUSNS8154P3512GJ 512GB     | 1         | 1.27%   |
| Intenso SSD Sata III 128GB           | 1         | 1.27%   |
| Intel SSDSC2KW256G8L 256GB           | 1         | 1.27%   |
| Intel SSDSC2BF180A4L 180GB           | 1         | 1.27%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1.27%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1.27%   |
| Hitachi HTS547575A9E384 752GB        | 1         | 1.27%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 27.59%  |
| Hitachi | 8         | 8      | 27.59%  |
| Seagate | 6         | 9      | 20.69%  |
| WDC     | 5         | 6      | 17.24%  |
| Unknown | 1         | 1      | 3.45%   |
| HGST    | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 26.67%  |
| Samsung Electronics | 6         | 6      | 20%     |
| SanDisk             | 4         | 5      | 13.33%  |
| Intel               | 2         | 2      | 6.67%   |
| A-DATA Technology   | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| Vaseky              | 1         | 1      | 3.33%   |
| Team                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Patriot             | 1         | 1      | 3.33%   |
| OCZ                 | 1         | 2      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| Goodram             | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 29        | 32     | 37.66%  |
| HDD  | 29        | 33     | 37.66%  |
| NVMe | 16        | 18     | 20.78%  |
| MMC  | 3         | 3      | 3.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 64     | 71.43%  |
| NVMe | 16        | 18     | 22.86%  |
| MMC  | 3         | 3      | 4.29%   |
| SAS  | 1         | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 54     | 81.82%  |
| 0.51-1.0   | 9         | 9      | 16.36%  |
| 1.01-2.0   | 1         | 2      | 1.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 39.71%  |
| 251-500        | 20        | 29.41%  |
| 21-50          | 8         | 11.76%  |
| 51-100         | 5         | 7.35%   |
| 501-1000       | 4         | 5.88%   |
| More than 3000 | 1         | 1.47%   |
| 2001-3000      | 1         | 1.47%   |
| 1-20           | 1         | 1.47%   |
| Unknown        | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 28        | 39.44%  |
| 21-50    | 24        | 33.8%   |
| 51-100   | 12        | 16.9%   |
| 101-250  | 4         | 5.63%   |
| 251-500  | 1         | 1.41%   |
| 501-1000 | 1         | 1.41%   |
| Unknown  | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD | 1         | 1      | 50%     |
| Crucial CT500P1SSD8 500GB                     | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Crucial             | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| SSD  | 1         | 1      | 50%     |

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
| Detected | 52        | 67     | 75.36%  |
| Works    | 15        | 17     | 21.74%  |
| Malfunc  | 2         | 2      | 2.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 51        | 67.11%  |
| AMD                          | 8         | 10.53%  |
| SK hynix                     | 4         | 5.26%   |
| SanDisk                      | 4         | 5.26%   |
| Samsung Electronics          | 3         | 3.95%   |
| Toshiba America Info Systems | 1         | 1.32%   |
| Nvidia                       | 1         | 1.32%   |
| Micron/Crucial Technology    | 1         | 1.32%   |
| KIOXIA                       | 1         | 1.32%   |
| Kingston Technology Company  | 1         | 1.32%   |
| JMicron Technology           | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 9.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 9.88%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 4.94%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 3.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 3.7%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 2.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.47%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.23%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.23%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.23%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 1.23%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.23%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.23%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 1.23%   |
| KIOXIA Non-Volatile memory controller                                            | 1         | 1.23%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.23%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.23%   |
| Intel SSD 600P Series                                                            | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 64.56%  |
| NVMe | 16        | 20.25%  |
| RAID | 6         | 7.59%   |
| IDE  | 6         | 7.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 80.6%   |
| AMD    | 12        | 17.91%  |
| ARM    | 1         | 1.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2540M CPU @ 2.60GHz               | 3         | 4.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 2.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 2.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 2.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 2.99%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 2         | 2.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 2.99%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 2         | 2.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 2.99%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 2         | 2.99%   |
| Intel Pentium M processor 1.73GHz               | 1         | 1.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 1.49%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 1         | 1.49%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.49%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 1.49%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 1.49%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 1.49%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 1.49%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 1.49%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 1         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.49%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 1.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 1.49%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1         | 1.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 1.49%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 1.49%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz            | 1         | 1.49%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 1.49%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz            | 1         | 1.49%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz            | 1         | 1.49%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 1.49%   |
| Intel Celeron CPU N3160 @ 1.60GHz               | 1         | 1.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 1.49%   |
| Intel Celeron CPU B815 @ 1.60GHz                | 1         | 1.49%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 1         | 1.49%   |
| Intel Celeron CPU 1000M @ 1.80GHz               | 1         | 1.49%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 1.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 1.49%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 1         | 1.49%   |
| ARM Processor                                   | 1         | 1.49%   |
| AMD Turion 64 Mobile Technology MK-38           | 1         | 1.49%   |
| AMD Ryzen 9 5900HS with Radeon Graphics         | 1         | 1.49%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 1.49%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 1         | 1.49%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G   | 1         | 1.49%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 1         | 1.49%   |
| AMD C-60 APU with Radeon HD Graphics            | 1         | 1.49%   |
| AMD A10-7400P Radeon R6, 10 Compute Cores 4C+6G | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 26.87%  |
| Intel Core i5           | 13        | 19.4%   |
| Intel Celeron           | 6         | 8.96%   |
| Intel Core i3           | 5         | 7.46%   |
| Other                   | 4         | 5.97%   |
| Intel Core 2 Duo        | 4         | 5.97%   |
| AMD Ryzen 5             | 3         | 4.48%   |
| AMD E1                  | 3         | 4.48%   |
| Intel Pentium M         | 1         | 1.49%   |
| Intel Pentium Dual-Core | 1         | 1.49%   |
| Intel Pentium Dual      | 1         | 1.49%   |
| Intel Pentium           | 1         | 1.49%   |
| Intel Atom              | 1         | 1.49%   |
| AMD Turion 64 Mobile    | 1         | 1.49%   |
| AMD Ryzen 9             | 1         | 1.49%   |
| AMD Ryzen 7             | 1         | 1.49%   |
| AMD E2                  | 1         | 1.49%   |
| AMD C-60                | 1         | 1.49%   |
| AMD A10                 | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 55.22%  |
| 4      | 23        | 34.33%  |
| 6      | 3         | 4.48%   |
| 8      | 2         | 2.99%   |
| 1      | 2         | 2.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 67.16%  |
| 1      | 22        | 32.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 94.03%  |
| Unknown        | 3         | 4.48%   |
| 32-bit         | 1         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 30.88%  |
| 0x306a9    | 7         | 10.29%  |
| 0x206a7    | 7         | 10.29%  |
| 0x406e3    | 3         | 4.41%   |
| 0x806ea    | 2         | 2.94%   |
| 0x806c1    | 2         | 2.94%   |
| 0x40651    | 2         | 2.94%   |
| 0x10676    | 2         | 2.94%   |
| 0x05000119 | 2         | 2.94%   |
| 0xa0652    | 1         | 1.47%   |
| 0x906ea    | 1         | 1.47%   |
| 0x806ec    | 1         | 1.47%   |
| 0x806eb    | 1         | 1.47%   |
| 0x806e9    | 1         | 1.47%   |
| 0x706e5    | 1         | 1.47%   |
| 0x6fd      | 1         | 1.47%   |
| 0x6fa      | 1         | 1.47%   |
| 0x6d8      | 1         | 1.47%   |
| 0x506c9    | 1         | 1.47%   |
| 0x406c4    | 1         | 1.47%   |
| 0x406c3    | 1         | 1.47%   |
| 0x306c3    | 1         | 1.47%   |
| 0x30678    | 1         | 1.47%   |
| 0x106e5    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x0a50000c | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x08108102 | 1         | 1.47%   |
| 0x0700010f | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 11        | 16.42%  |
| SandyBridge | 10        | 14.93%  |
| IvyBridge   | 8         | 11.94%  |
| Zen+        | 4         | 5.97%   |
| Silvermont  | 4         | 5.97%   |
| Haswell     | 4         | 5.97%   |
| TigerLake   | 3         | 4.48%   |
| Skylake     | 3         | 4.48%   |
| Penryn      | 3         | 4.48%   |
| Core        | 3         | 4.48%   |
| Jaguar      | 2         | 2.99%   |
| Bobcat      | 2         | 2.99%   |
| Zen 3       | 1         | 1.49%   |
| Steamroller | 1         | 1.49%   |
| P6          | 1         | 1.49%   |
| Nehalem     | 1         | 1.49%   |
| K8 Hammer   | 1         | 1.49%   |
| IceLake     | 1         | 1.49%   |
| Goldmont    | 1         | 1.49%   |
| Excavator   | 1         | 1.49%   |
| CometLake   | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 52.33%  |
| AMD    | 23        | 26.74%  |
| Nvidia | 18        | 20.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 7.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 7.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.37%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.37%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.25%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.25%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.25%   |
| Intel HD Graphics 620                                                                    | 2         | 2.25%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 2.25%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.25%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 2.25%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 1.12%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.12%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.12%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.12%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.12%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.12%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.12%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 1.12%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.12%   |
| Intel HD Graphics 500                                                                    | 1         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.12%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.12%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 1.12%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 1.12%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.12%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 1.12%   |
| AMD RV550/M71 [Mobility Radeon HD 2300]                                                  | 1         | 1.12%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 1         | 1.12%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 1.12%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 1.12%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 1.12%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.12%   |
| AMD Granville [Radeon HD 6850M/6870M]                                                    | 1         | 1.12%   |
| AMD Cezanne                                                                              | 1         | 1.12%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 38.81%  |
| 1 x AMD        | 16        | 23.88%  |
| Intel + Nvidia | 15        | 22.39%  |
| Intel + AMD    | 4         | 5.97%   |
| 2 x AMD        | 2         | 2.99%   |
| 1 x Nvidia     | 2         | 2.99%   |
| Other          | 1         | 1.49%   |
| AMD + Nvidia   | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 80.6%   |
| Proprietary | 11        | 16.42%  |
| Unknown     | 2         | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 55.07%  |
| 1.01-2.0   | 11        | 15.94%  |
| 0.51-1.0   | 7         | 10.14%  |
| 0.01-0.5   | 7         | 10.14%  |
| 3.01-4.0   | 3         | 4.35%   |
| 5.01-6.0   | 2         | 2.9%    |
| 7.01-8.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 23.53%  |
| LG Display              | 15        | 22.06%  |
| Chimei Innolux          | 9         | 13.24%  |
| BOE                     | 8         | 11.76%  |
| Samsung Electronics     | 6         | 8.82%   |
| Sharp                   | 2         | 2.94%   |
| LG Philips              | 2         | 2.94%   |
| Chi Mei Optoelectronics | 2         | 2.94%   |
| AOC                     | 2         | 2.94%   |
| Philips                 | 1         | 1.47%   |
| PANDA                   | 1         | 1.47%   |
| NEC Computers           | 1         | 1.47%   |
| Lenovo                  | 1         | 1.47%   |
| Goldstar                | 1         | 1.47%   |
| Dell                    | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 5.8%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 3         | 4.35%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch              | 2         | 2.9%    |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch               | 2         | 2.9%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 2.9%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 1.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.45%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                          | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch      | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch      | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch      | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch      | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 1         | 1.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 1.45%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                   | 1         | 1.45%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 338x270mm 17.0-inch             | 1         | 1.45%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 1         | 1.45%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch              | 1         | 1.45%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 1.45%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch                   | 1         | 1.45%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch                  | 1         | 1.45%   |
| Dell 1704FPT DEL4004 1280x1024 340x270mm 17.1-inch                        | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch          | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 1.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch  | 1         | 1.45%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                      | 1         | 1.45%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 1.45%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO429D 1920x1080 382x215mm 17.3-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO038E 1920x1080 344x193mm 15.5-inch            | 1         | 1.45%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 340x190mm 15.3-inch             | 1         | 1.45%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 1         | 1.45%   |
| AOC 2270W AOC2271 1920x1080 477x268mm 21.5-inch                           | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 29        | 43.94%  |
| 1366x768 (WXGA)  | 19        | 28.79%  |
| 1600x900 (HD+)   | 11        | 16.67%  |
| 1440x900 (WXGA+) | 2         | 3.03%   |
| 1280x800 (WXGA)  | 2         | 3.03%   |
| 1280x1024 (SXGA) | 2         | 3.03%   |
| 2560x1440 (QHD)  | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 36        | 52.94%  |
| 17      | 10        | 14.71%  |
| 14      | 6         | 8.82%   |
| 13      | 6         | 8.82%   |
| 11      | 3         | 4.41%   |
| 33      | 1         | 1.47%   |
| 24      | 1         | 1.47%   |
| 23      | 1         | 1.47%   |
| 21      | 1         | 1.47%   |
| 18      | 1         | 1.47%   |
| 12      | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 68.66%  |
| 351-400     | 8         | 11.94%  |
| 201-300     | 7         | 10.45%  |
| 501-600     | 2         | 2.99%   |
| 401-500     | 2         | 2.99%   |
| 701-800     | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 90.48%  |
| 16/10 | 4         | 6.35%   |
| 5/4   | 2         | 3.17%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 52.24%  |
| 81-90          | 9         | 13.43%  |
| 121-130        | 6         | 8.96%   |
| 71-80          | 3         | 4.48%   |
| 51-60          | 3         | 4.48%   |
| 201-250        | 2         | 2.99%   |
| 141-150        | 2         | 2.99%   |
| 131-140        | 2         | 2.99%   |
| 61-70          | 1         | 1.49%   |
| 351-500        | 1         | 1.49%   |
| 151-200        | 1         | 1.49%   |
| 91-100         | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 33        | 48.53%  |
| 101-120 | 24        | 35.29%  |
| 51-100  | 9         | 13.24%  |
| 161-240 | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 58        | 86.57%  |
| 2     | 6         | 8.96%   |
| 0     | 2         | 2.99%   |
| 3     | 1         | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 34        | 33.33%  |
| Intel                           | 24        | 23.53%  |
| Qualcomm Atheros                | 23        | 22.55%  |
| Broadcom                        | 7         | 6.86%   |
| Ralink                          | 3         | 2.94%   |
| Ralink Technology               | 2         | 1.96%   |
| Marvell Technology Group        | 2         | 1.96%   |
| TP-Link                         | 1         | 0.98%   |
| Qualcomm Atheros Communications | 1         | 0.98%   |
| Nvidia                          | 1         | 0.98%   |
| HTC (High Tech Computer)        | 1         | 0.98%   |
| Hewlett-Packard                 | 1         | 0.98%   |
| D-Link                          | 1         | 0.98%   |
| Broadcom Limited                | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 21        | 16.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 4.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.56%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.56%   |
| Intel Wireless 8260                                                     | 2         | 1.56%   |
| Intel Wireless 7260                                                     | 2         | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.56%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.78%   |
| Realtek Realtek Network controller                                      | 1         | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.78%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.78%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                 | 1         | 0.78%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.78%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.78%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.78%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.78%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.78%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 1         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 0.78%   |
| Intel 82562GT 10/100 Network Connection                                 | 1         | 0.78%   |
| HTC (High Tech Computer) Desire HD (modem mode)                         | 1         | 0.78%   |
| HP hs2350 HSPA+ MobileBroadband                                         | 1         | 0.78%   |
| D-Link GO-USB-N150 N Adapter                                            | 1         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 0.78%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe                 | 1         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 33.33%  |
| Qualcomm Atheros                | 21        | 30.43%  |
| Realtek Semiconductor           | 11        | 15.94%  |
| Broadcom                        | 6         | 8.7%    |
| Ralink                          | 3         | 4.35%   |
| Ralink Technology               | 2         | 2.9%    |
| TP-Link                         | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| D-Link                          | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 10.14%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 8.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 8.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 5.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 4.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 4.35%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.9%    |
| Intel Wireless 8260                                                     | 2         | 2.9%    |
| Intel Wireless 7260                                                     | 2         | 2.9%    |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.45%   |
| Realtek Realtek Network controller                                      | 1         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.45%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.45%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.45%   |
| D-Link GO-USB-N150 N Adapter                                            | 1         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 58.18%  |
| Intel                    | 12        | 21.82%  |
| Qualcomm Atheros         | 5         | 9.09%   |
| Marvell Technology Group | 2         | 3.64%   |
| Broadcom                 | 2         | 3.64%   |
| Nvidia                   | 1         | 1.82%   |
| Broadcom Limited         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 14.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.57%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.79%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.79%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.79%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.79%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 52.46%  |
| Ethernet | 55        | 45.08%  |
| Modem    | 3         | 2.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 79.71%  |
| Ethernet | 13        | 18.84%  |
| Modem    | 1         | 1.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 77.61%  |
| 1     | 13        | 19.4%   |
| 0     | 2         | 2.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 95.52%  |
| Yes  | 3         | 4.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 22%     |
| Qualcomm Atheros Communications | 9         | 18%     |
| IMC Networks                    | 7         | 14%     |
| Realtek Semiconductor           | 5         | 10%     |
| Lite-On Technology              | 4         | 8%      |
| Broadcom                        | 4         | 8%      |
| Ralink                          | 3         | 6%      |
| Hewlett-Packard                 | 2         | 4%      |
| Toshiba                         | 1         | 2%      |
| Realtek                         | 1         | 2%      |
| Foxconn / Hon Hai               | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |
| Alps Electric                   | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 5         | 10%     |
| Intel Bluetooth wireless interface                  | 4         | 8%      |
| IMC Networks Bluetooth Radio                        | 4         | 8%      |
| Realtek Bluetooth Radio                             | 3         | 6%      |
| Ralink RT3290 Bluetooth                             | 3         | 6%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 6%      |
| Intel Bluetooth Device                              | 3         | 6%      |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 4%      |
| IMC Networks Bluetooth Device                       | 2         | 4%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4%      |
| Toshiba RT Bluetooth Radio                          | 1         | 2%      |
| Realtek Bluetooth Radio                             | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2%      |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 2%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2%      |
| Intel AX200 Bluetooth                               | 1         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2%      |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2%      |
| Broadcom HP Portable Valentine                      | 1         | 2%      |
| Broadcom HP Portable SoftSailing                    | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2%      |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2%      |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 53        | 66.25%  |
| AMD               | 17        | 21.25%  |
| Nvidia            | 7         | 8.75%   |
| Logitech          | 2         | 2.5%    |
| Texas Instruments | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 9.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 9.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 8.42%   |
| AMD FCH Azalia Controller                                                                         | 5         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 4.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.16%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.11%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.11%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 2.11%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia Audio device                                                                               | 1         | 1.05%   |
| Logitech USB Headset                                                                              | 1         | 1.05%   |
| Logitech 960 Headset                                                                              | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.05%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 1.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.05%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.05%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.05%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 1.05%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 33.33%  |
| Micron Technology   | 7         | 29.17%  |
| Samsung Electronics | 3         | 12.5%   |
| Kingston            | 2         | 8.33%   |
| A-DATA Technology   | 2         | 8.33%   |
| Crucial             | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 7.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.7%    |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s         | 1         | 3.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s      | 1         | 3.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s            | 1         | 3.7%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 3.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 3.7%    |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                   | 1         | 3.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s          | 1         | 3.7%    |
| Micron RAM MT52L512M32D2PF-09 4096MB Row Of Chips LPDDR3 2133MT/s | 1         | 3.7%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s             | 1         | 3.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s         | 1         | 3.7%    |
| Micron RAM 16JSF25664HY-1G1D1 2GB SODIMM DDR3 1066MT/s            | 1         | 3.7%    |
| Micron RAM 16ATF1G64HZ-2G1B1 8192MB SODIMM DDR4 2133MT/s          | 1         | 3.7%    |
| Kingston RAM KKN2NM-MIE 4GB SODIMM DDR4 2667MT/s                  | 1         | 3.7%    |
| Kingston RAM HP16D3LS1KBG/4G 4096MB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s           | 1         | 3.7%    |
| Corsair RAM CMSX4GX3M1A1600C9 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| A-DATA RAM AO1P24HC8T1-BQXS 8GB SODIMM DDR4 2400MT/s              | 1         | 3.7%    |
| A-DATA RAM AM1U16BC4P2-B19H 4096MB SODIMM DDR3 1600MT/s           | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 11        | 50%     |
| DDR4   | 9         | 40.91%  |
| LPDDR4 | 1         | 4.55%   |
| LPDDR3 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 90.91%  |
| Row Of Chips | 2         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 15        | 65.22%  |
| 8192  | 5         | 21.74%  |
| 2048  | 2         | 8.7%    |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 9         | 39.13%  |
| 2667  | 4         | 17.39%  |
| 3200  | 3         | 13.04%  |
| 2400  | 2         | 8.7%    |
| 2133  | 2         | 8.7%    |
| 1334  | 1         | 4.35%   |
| 1333  | 1         | 4.35%   |
| 1066  | 1         | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Hewlett-Packard       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 50%     |
| HP LaserJet 1000                           | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 26.79%  |
| Realtek Semiconductor                  | 8         | 14.29%  |
| IMC Networks                           | 7         | 12.5%   |
| Sunplus Innovation Technology          | 4         | 7.14%   |
| Acer                                   | 4         | 7.14%   |
| Suyin                                  | 3         | 5.36%   |
| Quanta                                 | 3         | 5.36%   |
| Microdia                               | 3         | 5.36%   |
| Syntek                                 | 2         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.57%   |
| Ricoh                                  | 1         | 1.79%   |
| Luxvisions Innotech Limited            | 1         | 1.79%   |
| Lite-On Technology                     | 1         | 1.79%   |
| Lenovo                                 | 1         | 1.79%   |
| ALi                                    | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                          | 4         | 7.14%   |
| Microdia Integrated_Webcam_HD                               | 3         | 5.36%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 3.57%   |
| Realtek HD WebCam                                           | 2         | 3.57%   |
| Chicony HP Truevision HD                                    | 2         | 3.57%   |
| Acer EasyCamera                                             | 2         | 3.57%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.79%   |
| Syntek Integrated Camera                                    | 1         | 1.79%   |
| Suyin HP Truevision HD                                      | 1         | 1.79%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.79%   |
| Sunplus HP Universal Camera                                 | 1         | 1.79%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.79%   |
| Sunplus HD WebCam                                           | 1         | 1.79%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.79%   |
| Realtek VGA WebCam                                          | 1         | 1.79%   |
| Realtek USB Camera                                          | 1         | 1.79%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.79%   |
| Realtek Integrated Webcam HD                                | 1         | 1.79%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.79%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.79%   |
| Quanta HP Webcam                                            | 1         | 1.79%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.79%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.79%   |
| Lite-On HP HD Webcam                                        | 1         | 1.79%   |
| Lenovo UVC Camera                                           | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.79%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.79%   |
| IMC Networks ov9734_azurewave_camera                        | 1         | 1.79%   |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 1.79%   |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.79%   |
| Chicony thinkpad t430s camera                               | 1         | 1.79%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.79%   |
| Chicony Integrated HP HD Webcam                             | 1         | 1.79%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.79%   |
| Chicony integrated camera                                   | 1         | 1.79%   |
| Chicony HP Truevision HD camera                             | 1         | 1.79%   |
| Chicony HP HD Webcam                                        | 1         | 1.79%   |
| Chicony HP HD Camera                                        | 1         | 1.79%   |
| Chicony HD WebCam                                           | 1         | 1.79%   |
| Chicony CNF8243 Webcam                                      | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 1.79%   |
| ALi Gateway Webcam                                          | 1         | 1.79%   |
| Acer Orbicam                                                | 1         | 1.79%   |
| Acer Integrated Camera                                      | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 58.33%  |
| Shenzhen Goodix Technology | 2         | 16.67%  |
| Synaptics                  | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 3         | 25%     |
| Validity Sensors VFS471 Fingerprint Reader | 3         | 25%     |
| Shenzhen Goodix  FingerPrint Device        | 2         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 8.33%   |
| LighTuning Fingerprint Reader              | 1         | 8.33%   |
| AuthenTec AES2810                          | 1         | 8.33%   |
| Unknown                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |
| Broadcom 5880                                              | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 58.82%  |
| 1     | 24        | 35.29%  |
| 2     | 3         | 4.41%   |
| 3     | 1         | 1.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 38.71%  |
| Graphics card         | 6         | 19.35%  |
| Net/wireless          | 4         | 12.9%   |
| Chipcard              | 3         | 9.68%   |
| Bluetooth             | 3         | 9.68%   |
| Sound                 | 1         | 3.23%   |
| Multimedia controller | 1         | 3.23%   |
| Modem                 | 1         | 3.23%   |

